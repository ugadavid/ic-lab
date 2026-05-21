# Prototype 04 — V0.1 Rewrite Report

## Correction du bug HTML

La V0 affichait parfois littéralement des fragments comme `<span class="false-friend">bocadillo</span>`.

La fonction de rendu a été corrigée avec une petite liste de balisage autorisé : seul le motif interne `<span class="false-friend">…</span>` est interprété comme HTML. Le reste du texte continue d’être échappé.

Cette solution reste légère et adaptée au prototype, sans ouvrir un rendu HTML libre.

## Suppression de `librería`

`librería` a été retiré du prototype. Dans un cadrage FR → ES, ce mot correspond bien à “librairie” pour un francophone ; il ne jouait donc pas correctement le rôle de faux ami.

La scène de la “bibliothèque qui n’en est pas une” a été supprimée.

## Ajout de `constipado`

La scène remplacée introduit maintenant `constipado`.

Le mot est présenté dans une interaction incarnée avec une personne enrhumée :

- toux ;
- mouchoir ;
- froid ;
- nez ;
- fatigue ;
- refus d’une boisson trop froide.

Le prototype ne donne pas une correction directe. Il laisse le contexte déplacer progressivement l’hypothèse initiale.

## Ralentissement narratif

La V0.1 privilégie moins d’exemples et plus de vécu.

La scène `bocadillo` a été ralentie :

- installation à la terrasse ;
- lecture partielle de la carte ;
- confiance après la commande ;
- attente ;
- arrivée de l’assiette ;
- observation silencieuse.

La scène `embarazada` a aussi été ralentie :

- conversation plus installée ;
- sentiment de compréhension ;
- hypothèse immédiate ;
- indices progressifs autour du bébé, de la famille, du prénom, du rendez-vous médical et de la naissance.

## Pourquoi moins d’exemples

Le prototype ne cherche pas à faire une collection de faux amis. Il cherche à faire ressentir le moment où une hypothèse plausible commence à craquer.

Trois moments suffisent pour cette V0.1 :

- `bocadillo` : l’image mentale déplacée par l’assiette ;
- `constipado` : le mot déplacé par les gestes et le contexte ;
- `embarazada` : l’hypothèse déplacée par les indices narratifs.

Ce ralentissement rend l’expérience plus narrative, moins démonstrative, et plus conforme au thème : “L’élégance d’être perdu sans paniquer.”

## Points à observer au prochain test manuel

- Le rendu des mots stylés fonctionne-t-il bien sur desktop et mobile ?
- `constipado` produit-il un flottement compréhensible sans correction explicite ?
- Les scènes semblent-elles plus vécues et moins listées ?
- Le rythme est-il assez lent sans devenir trop long ?
- Le ton reste-t-il drôle sans devenir moqueur ?
- L’écran final reformule-t-il les réponses sans donner l’impression d’évaluer ?
