# Prototype 01 — Seven Sieves Explorer

## Objet de la stabilisation

Cette passe transforme `index-0.0.8.2.html` en démonstrateur pédagogique montrable, sans chercher à en faire une application produit. Le prototype reste un fichier HTML/CSS/JS autonome, lisible et modifiable rapidement.

## Éléments qui donnaient une fausse impression de produit final

- La barre de navigation simulait des espaces applicatifs non disponibles : bibliothèque, parcours, tamis, suivi.
- Les puces de langue FR/ES/IT/PT suggéraient un choix de langue ou une couverture multilingue qui n’existe pas dans cette version.
- Les tamis 2, 4 et 6 étaient présentés comme des boutons explorables alors qu’ils ne contenaient pas d’activité pédagogique implémentée.
- Certains libellés parlaient de l’app ou du moteur, ce qui pouvait faire croire à une logique produit plus avancée que le prototype réel.
- Le bouton de feedback “Vérifier” pouvait être compris comme une correction finale, alors qu’il sert surtout à soutenir la discussion sur les indices repérés.

## Ce qui a été simplifié

- La pseudo-navigation a été retirée du haut de page.
- Les choix de langue décoratifs ont été remplacés par deux repères stables : “Lecture guidée” et “ES → FR”.
- Le titre visible a été recentré sur l’objet du prototype : “Prototype 01 — Seven Sieves Explorer”.
- Les tamis 2, 4 et 6 restent visibles comme repères théoriques, mais sont maintenant désactivés et marqués “hors test”.
- Le panneau de droite a été renommé “Observation” pour éviter l’idée d’un tableau de bord produit.
- Le bouton “Vérifier” a été reformulé en “Comparer la sélection”.
- Le message de feedback insiste maintenant sur la discussion des indices, pas sur une notation ou une validation finale.

## Pourquoi

Le prototype doit aider un enseignant ou un chercheur à comprendre rapidement ce qui est réellement testable : les gestes de lecture autour des tamis 1, 3, 5 et 7. Les éléments décoratifs donnaient une promesse d’interface complète et risquaient de détourner l’attention des hypothèses pédagogiques.

Le nettoyage vise donc à rendre la démo plus honnête : elle montre une situation d’exploration guidée, pas un environnement d’apprentissage finalisé.

## Interactions préservées

- Tamis 1 : repérage du lexique international.
- Tamis 3 : correspondances phonétiques et transformations proposées.
- Tamis 5 : lecture syntaxique simplifiée.
- Tamis 7 : observation des préfixes et suffixes.
- Inspection d’un mot par clic.
- Sélection et désélection de mots par double-clic.
- Qualification subjective du mot : compris, doute, inconnu.
- Feedback global sur la sélection.
- Lecture guidée via le micro-guide et les indices du tamis actif.

## Volontairement laissé de côté

- Les tamis 2, 4 et 6 ne sont pas développés dans cette version.
- Le texte reste statique.
- Il n’y a pas de persistance des données, de comptes, de parcours, ni de suivi apprenant.
- La syntaxe du tamis 5 reste volontairement approximative et codée à la main.
- Le feedback ne prétend pas mesurer une compétence ; il sert seulement de support de discussion.
- Le prototype ne cherche pas à généraliser à toutes les langues romanes.

## Ce qui semble prometteur pédagogiquement

- Le clic sur les mots rend visibles les stratégies d’entrée dans le texte : ce que l’apprenant reconnaît, hésite à reconnaître ou ignore.
- Les transformations du tamis 3 donnent un pont concret entre formes espagnoles et formes françaises possibles.
- Les suffixes du tamis 7 semblent utiles pour déplacer l’attention du mot isolé vers des régularités.
- Le tamis 5 peut soutenir une lecture globale même avec une compréhension lexicale partielle.
- La distinction “compris / doute / inconnu” peut aider à observer la confiance du lecteur, pas seulement sa réponse.
- Le prototype rend possible une discussion avec enseignants et chercheurs sur l’ordre d’introduction des tamis et sur les moments où la compréhension se débloque.

## Hypothèse de démonstration

Un lecteur novice peut commencer à construire du sens dans un texte espagnol inconnu s’il est guidé vers des indices observables avant d’être invité à traduire. Les tamis les plus immédiatement testables dans cette version sont le lexique international, les correspondances phonétiques, la structure syntaxique générale et les suffixes.
