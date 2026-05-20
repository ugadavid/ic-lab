# Prototype 02 — V0.1 Reflective Ending

## Ce qui a été ajouté

Cette passe ajoute un écran final réflexif à `index-0.0.1.html`, sous la forme d’un petit panneau :

> 🐭 Ton petit carnet de voyage

Le panneau apparaît après la dernière scène et reprend doucement les réponses de l’utilisateur :

- hypothèse sur le mot `viaje` ;
- impression de compréhension face à l’étiquette en espagnol ;
- indices déclarés comme utiles dans la scène italienne ;
- hypothèse sur le contenu du carnet.

## Choix UX

- Le panneau garde le ton narratif et non scolaire du prototype.
- Les réponses sont reformulées comme des traces de cheminement, pas comme des résultats.
- Aucune réponse n’est corrigée ou validée.
- Les formulations restent prudentes : “peut-être”, “souvent”, “hypothèses”.
- La conclusion revient à Lumi et à l’idée de compréhension partielle mais active.

## Simplifications

- Les réponses restent dans `answers{}` uniquement pendant la session.
- Aucun stockage ni export n’a été ajouté.
- Le carnet est généré par une seule fonction légère.
- Il n’y a pas de logique d’interprétation automatique des réponses libres.
- Les réponses vides sont accueillies avec une phrase douce de remplacement.

## Intérêt pédagogique

Ce miroir final aide à transformer l’expérience en observation métacognitive : le lecteur peut voir qu’il a deviné, comparé, continué, hésité, et construit du sens malgré l’incertitude.

L’écran ne dit pas “tu as réussi”. Il suggère plutôt :

> voilà ce qui s’est peut-être passé pendant ta compréhension.

## À observer en test

- Le carnet arrive-t-il comme une conclusion chaleureuse ou comme un ajout trop explicatif ?
- Les lecteurs reconnaissent-ils leurs propres stratégies dans les reformulations ?
- Les réponses vides restent-elles acceptables sans créer de gêne ?
- Le bouton “Recommencer” est-il assez clair après le carnet ?
