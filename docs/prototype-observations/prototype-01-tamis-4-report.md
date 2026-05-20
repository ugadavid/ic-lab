# Prototype 01 — Tamis 4

## Ce qui a été ajouté

Cette passe active le tamis 4, “Graphies / prononciations”, dans `index-0.0.8.2.html`.

Le tamis 4 est maintenant cliquable comme les tamis 1, 3, 5 et 7. Il permet de :

- marquer les mots du texte qui contiennent un signal grapho-phonétique suivi par la démo ;
- afficher une explication courte lors de l’inspection d’un mot ;
- afficher une prudence quand la correspondance est approximative ;
- lister les mots détectés dans le panneau “Indices / transformations” ;
- utiliser un style visuel distinct, bleu-vert, pour différencier ce tamis des suffixes, transformations et rôles syntaxiques.

## Règles retenues

Les règles sont volontairement manuelles et lisibles :

- `ñ` : rapprochement possible avec `gn`.
- `ll` : zone d’observation possible autour de `ill` / `y`.
- `h` initial : généralement muet en espagnol.
- `qu` : indice de prononciation, souvent proche de /k/ devant `e` ou `i`.
- `gu` : indice de prononciation, avec prudence selon la lettre suivante et le tréma éventuel.
- `j` espagnol : attention à ne pas le lire comme le `j` français.
- `c` devant `e` ou `i` : variation graphique importante en espagnol.
- `z` : zone de variation graphique et phonétique.

Dans le texte actuel, les règles les plus visibles sont surtout `c` devant `e/i`, `qu`, `gu`, `j`, `ll` et `z`. Les règles `ñ` et `h` initial restent présentes dans le code comme repères pédagogiques, même si le texte de démonstration ne les mobilise pas fortement.

## Limites assumées

- Le tamis 4 ne produit pas une analyse phonétique complète.
- Les règles ne tiennent pas compte de tous les contextes graphiques possibles.
- Les variantes régionales de prononciation ne sont pas modélisées.
- Certains mots peuvent être signalés par plusieurs tamis, notamment les mots en `-ción`, ce qui est accepté pour la discussion pédagogique.
- Les règles sont appliquées au mot isolé, sans analyse de phrase ni de syllabe.
- Le prototype ne propose pas de transcription phonétique.

## Pourquoi le tamis 4 reste simple

Le but de cette version est de faire observer des signaux, pas d’enseigner toute la phonologie espagnole. Pour un démonstrateur IC-Lab, la simplicité permet de tester rapidement une question pédagogique : est-ce que des indices graphiques très visibles aident le lecteur à ralentir, comparer et éviter une lecture trop francisée ?

Garder le tamis 4 simple permet aussi de préserver le prototype comme support de discussion avec enseignants et chercheurs. Les règles peuvent être ajoutées, retirées ou reformulées sans refonte technique.
