# Gel démo - Informaticaire v0.6.1

## Version gelée

Version gelée pour démonstration : **v0.6.1**.

Cette version correspond à l'état v0.6 démontrable, consolidé par le hotfix recherche/alias v0.6.1.

## Objectif du prototype

Informaticaire est un prototype de mémoire vivante et communautaire de l'intercompréhension.

Il aide à :

- retrouver des ressources, projets, outils, corpus, acteurs et besoins ;
- comprendre leur histoire et leurs relations ;
- identifier les ressources fragiles ou à récupérer ;
- préparer des contributions documentaires vérifiables ;
- discuter collectivement de la réutilisation, de la maintenance et de la transmission.

## État fonctionnel actuel

La version gelée contient :

- 42 fiches documentées ;
- une recherche robuste avec alias et variantes de noms ;
- des filtres par type, statut et public ;
- des fiches détaillées en modale ;
- une visite guidée en 5 étapes ;
- une démo rapide centrée sur Galanet ;
- une carte relationnelle simple ;
- une campagne `Ressources à sauver ensemble` ;
- une vue `À partager en priorité` ;
- un formulaire local de contribution avec brouillon JSON ;
- un export JSON des fiches ;
- un export CSV de la campagne de récupération ;
- des sections de limites publiques et de décisions communautaires.

## Fichiers principaux

- `index.html` : interface statique.
- `styles.css` : mise en page et responsive.
- `data.js` : données des fiches, relations, preuves, récupération, champs communautaires et alias.
- `script.js` : recherche, filtres, rendu des vues, modale, exports, contribution et démo Galanet.
- `README.md` : présentation générale.
- `demo-script.md` : scripts de présentation 5 minutes et 12 minutes.
- `reports/` : rapports des itérations.

## Parcours de démo recommandé

1. Ouvrir l'accueil et présenter Informaticaire comme mémoire communautaire de l'intercompréhension.
2. Montrer les indicateurs : fiches, ressources à sauver, fiches à partager, publics, relations.
3. Utiliser `Découvrir Informaticaire en 5 étapes`.
4. Lancer `Démo rapide` avec le parcours Galanet.
5. Montrer la fiche détaillée Galanet : historique, relations, état, récupération, personnes/projets liés.
6. Chercher `EuRom 5` puis `EuRom5` pour montrer le hotfix recherche/alias.
7. Montrer un filtre par public ou par type.
8. Montrer `Ressources à sauver ensemble`.
9. Montrer le formulaire `Contribuer` et expliquer que la contribution reste locale et relue humainement.
10. Finir par `Ce prototype n'est pas encore...` et `Prochaines décisions communautaires`.

## Recherches de test à vérifier avant présentation

Avant une présentation, vérifier rapidement que ces recherches retournent une fiche pertinente :

- `EuRom 5`
- `EuRom5`
- `eurom web`
- `GalaNet`
- `GalaPro`
- `Myriadi`
- `Miriadi`
- `Romanophonie`
- `Romanofonía`
- `Repli4C`
- `Reply for C`
- `Iplera`

## Points forts

- Le prototype est lisible sans backend ni installation.
- La démo Galanet donne un parcours narratif clair.
- Les alias rendent la recherche plus robuste aux graphies réelles des utilisateurs.
- Les fiches relient ressources, acteurs, projets, risques et actions possibles.
- La campagne de récupération transforme la mémoire dispersée en actions discutables.
- Le formulaire de contribution prépare un geste communautaire simple sans automatiser la validation.

## Limites à annoncer

- Ce prototype n'est pas une base officielle.
- Il n'est pas exhaustif.
- Les droits, licences et accès doivent être vérifiés.
- Les contributions sont locales et doivent être relues humainement.
- Les données viennent d'une première exploitation d'entretiens et doivent être consolidées collectivement.
- La recherche n'est pas une recherche floue complète : les alias devront être enrichis avec les retours utilisateurs.
- La gouvernance, l'hébergement durable et la validation des fiches restent à décider.

## Questions à poser aux testeurs

- Comprenez-vous en moins de deux minutes à quoi sert Informaticaire ?
- Quelle section vous semble la plus utile pour votre rôle ?
- Quels termes chercheriez-vous spontanément ?
- Quelles fiches ou ressources devraient être validées en priorité ?
- Quelles ressources vous semblent les plus urgentes à sauver ?
- Qui pourrait confirmer l'état actuel de Galanet, Galapro, Miriadi, APICAD, EuRom ou REPLI4C ?
- Le formulaire de contribution donne-t-il envie de signaler une ressource, un lien ou une archive ?
- Quelles informations ne devraient pas être publiées sans vérification préalable ?

## Avertissement git

Attention : ne pas embarquer dans une livraison ou un commit Informaticaire les changements préexistants dans `prototypes/00-ic-hub`.

Pour une livraison propre, ne sélectionner que les fichiers de `prototypes/07-informaticaire`.
