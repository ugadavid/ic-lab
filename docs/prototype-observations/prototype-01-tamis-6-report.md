# Prototype 01 — Tamis 6

## Ce qui a été ajouté

Cette passe active le tamis 6, “Morphosyntaxe”, dans `index-0.0.8.2.html`.

Le tamis 6 ajoute un calque d’observation grammaticale légère :

- repérage de quelques signaux visibles dans les mots du texte ;
- affichage d’une explication courte lors de l’inspection ;
- formulation prudente avec “probable”, “possible”, “souvent” ;
- style visuel distinct, orange, pour les mots concernés ;
- légende dédiée ;
- micro-guide dédié ;
- synthèse des signaux repérés dans le panneau “Indices / transformations”.

## Signaux grammaticaux retenus

Les signaux retenus sont simples et volontairement peu nombreux :

- déterminants probables : `la`, `el`, `una` ;
- formes verbales probables : `observan`, `permite`, `circula`, `existe`, mais aussi quelques formes visibles du texte comme `promueve`, `resulta`, `imaginaban`, `es` ;
- infinitifs probables : `traducir`, `identificar`, `desarrollar`, `comprender`, `reconocer`, `construir` ;
- adverbes en `-mente` : par exemple `rápidamente`, `especialmente` ;
- marques de pluriel possibles : finales `-s` ou `-es`, par exemple `universidades`, `estudiantes`, `contextos`.

Ces signaux sont utilisés comme indices d’organisation de la langue, pas comme étiquettes grammaticales définitives.

## Simplifications assumées

- Le tamis 6 ne fait aucune analyse grammaticale complète.
- Il ne reconnaît pas les temps, modes, personnes ou accords.
- Il ne distingue pas tous les cas où `-s` marque réellement un pluriel.
- Les formes verbales probables sont en partie listées à la main.
- Les infinitifs sont repérés à partir d’exemples du texte, pas par un moteur général.
- Les catégories peuvent se recouper avec d’autres tamis, notamment le tamis 5 ou le tamis 7.

## Pourquoi cette version reste volontairement légère

L’objectif est de faire sentir une mécanique visible : petits mots structurants, verbes probables, finales utiles, indices de nombre. Une version plus ambitieuse transformerait vite le prototype en parseur ou en cours de grammaire, ce qui irait contre l’esprit IC-Lab.

Cette V1 reste donc proche de l’expérience de lecture : l’apprenant observe des régularités et formule des hypothèses sans devoir maîtriser la terminologie grammaticale.

## Ce qui semble pédagogiquement prometteur

- Les déterminants peuvent aider à repérer des groupes de mots.
- Les formes verbales probables peuvent soutenir la question “qui fait quoi ?”.
- Les infinitifs donnent un signal très visible de fonctionnement verbal.
- Les adverbes en `-mente` font le lien avec les transformations déjà observées dans les autres tamis.
- Les marques de pluriel peuvent aider à voir que certains mots appartiennent à des ensembles.
- Le tamis 6 peut produire le sentiment recherché : “je ne comprends pas tout, mais je vois des pièces de la mécanique”.
