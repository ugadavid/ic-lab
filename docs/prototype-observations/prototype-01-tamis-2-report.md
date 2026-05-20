# Prototype 01 — Tamis 2

## Ce qui a été ajouté

Cette passe active le tamis 2, “Lexique pan-roman”, dans `index-0.0.8.2.html`.

Le tamis 2 permet maintenant de :

- repérer des mots du texte associés à un mini lexique pan-roman manuel ;
- afficher des formes proches en français, italien et portugais lors de l’inspection ;
- proposer une famille lexicale romane quand elle est utile ;
- rappeler que l’objectif est l’observation et l’inférence, pas la traduction automatique ;
- lister le mini lexique suivi dans le panneau “Indices / transformations” ;
- utiliser un style visuel vert distinct pour les mots concernés.

## Construction du mini lexique

Le mini lexique a été construit uniquement à partir de mots présents dans le texte actuel. Il contient 20 entrées, donc il reste volontairement petit et vérifiable à la main.

Les mots retenus privilégient plusieurs cas pédagogiques :

- des proximités très visibles : `base`, `elementos`, `textos`, `universidades` ;
- des familles lexicales reconnaissables malgré des finales différentes : `lenguas`, `común`, `cultural`, `familiares` ;
- des formes qui demandent davantage d’observation : `palabra`, `mejor`, `muchos`, `desconocidos` ;
- des verbes utiles pour construire le sens : `comprender`, `observan`, `permite`.

Chaque entrée contient au minimum des formes proches en FR / IT / PT, une indication de famille lexicale et une courte note pédagogique.

## Limites assumées

- Le tamis 2 n’est pas un dictionnaire.
- Les formes proposées ne couvrent pas tous les sens possibles des mots.
- Les correspondances sont sélectionnées pour soutenir l’observation, pas pour garantir une équivalence stricte.
- Le lexique ne couvre pas tout le texte.
- Certaines entrées sont plus transparentes que d’autres, ce qui est assumé : l’intérêt est aussi de discuter les degrés de parenté perçue.
- Les langues représentées sont limitées à FR / IT / PT pour cette V1.

## Pourquoi cette version reste simple

Le prototype doit rester montrable, modifiable et rapide à discuter. Une grande base lexicale ferait glisser le tamis 2 vers un outil de traduction ou un dictionnaire, alors que l’objectif est de déclencher une observation : “ces formes ont un air de famille”.

La version simple permet de tester si quelques exemples bien choisis suffisent à renforcer l’inférence et le sentiment de parenté linguistique chez un lecteur novice.

## Ce qui semble pédagogiquement prometteur

- Le tamis 2 peut aider à distinguer “mot transparent” et “mot apparenté mais moins immédiat”.
- La comparaison FR / IT / PT ouvre une lecture plurilingue sans demander à l’apprenant de maîtriser ces langues.
- Les familles lexicales peuvent rendre visible une continuité romane au-delà du seul couple espagnol-français.
- Les mots moins évidents, comme `palabra` ou `mejor`, peuvent provoquer des discussions utiles sur la ressemblance partielle.
- Le tamis encourage l’hypothèse et la comparaison plutôt que la recherche d’une réponse unique.
