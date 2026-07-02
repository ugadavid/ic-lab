# IC-Lab Hub V0.6 - MariaDB

Cette couche MariaDB est experimentale. Le mode JSON reste le mode par defaut et les fichiers JSON ne sont pas supprimes.

## Prerequis

- MariaDB accessible sur `127.0.0.1:3306`
- Base creee manuellement : `ic_hub`
- Utilisateur cree manuellement : `ic_hub_user`
- Ne pas toucher a la base `ic_dico`

Variables attendues :

```env
IC_HUB_STORE=mariadb
IC_HUB_DB_HOST=127.0.0.1
IC_HUB_DB_PORT=3306
IC_HUB_DB_NAME=ic_hub
IC_HUB_DB_USER=ic_hub_user
IC_HUB_DB_PASSWORD=ic_hub_pass
```

Un modele est disponible dans `server/.env.example`.

## Installation dependance

```powershell
cd "J:\2026\UGA\M2\Stage-Memoire\Applications\IC-Lab\prototypes\00-ic-hub\server"
npm install
```

La seule dependance ajoutee est `mysql2`.

## Migration JSON vers MariaDB

```powershell
cd "J:\2026\UGA\M2\Stage-Memoire\Applications\IC-Lab\prototypes\00-ic-hub\server"
node db/migrate-json-to-mariadb.js
```

Dry-run :

```powershell
node db/migrate-json-to-mariadb.js --dry-run
```

Le script :

- se connecte a `ic_hub`;
- execute `db/schema.sql`;
- lit les fichiers JSON existants;
- insere/met a jour les tables avec `INSERT ... ON DUPLICATE KEY UPDATE`;
- ne fait pas de `DROP TABLE` et ne supprime pas les fichiers JSON.

## Lancement serveur

Mode JSON, par defaut :

```powershell
node server.js
```

Mode MariaDB :

```powershell
$env:IC_HUB_STORE="mariadb"
node server.js
```

Si MariaDB est indisponible au demarrage ou pendant une operation, le serveur bascule temporairement en fallback JSON et log l'erreur.

## Retour arriere

Fermer le serveur, puis relancer sans `IC_HUB_STORE=mariadb` :

```powershell
Remove-Item Env:\IC_HUB_STORE
node server.js
```

Les fichiers JSON restent la source de secours.

## Limites

- La couche MariaDB est une premiere abstraction compatible avec les stores JSON.
- Les dates restent stockees en chaines ISO pour preserver les donnees prototype.
- Il n'y a pas encore de transactions applicatives fines.
- Certaines suppressions restent volontairement prudentes ; le runtime couvre les suppressions de sessions, mais la migration n'efface pas les donnees existantes.
- Aucune table de Dico-IC ni la base `ic_dico` ne sont modifiees.
