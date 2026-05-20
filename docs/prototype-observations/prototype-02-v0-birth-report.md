# Prototype 02 — V0 Birth Report

## Objet

Cette V0 donne une première forme jouable à “Lumi et la boîte mystérieuse”. Le but est de faire naître une expérience observable, pas de produire une application complète.

Le prototype est contenu dans un seul fichier HTML autonome : `prototypes/02-multilingual-story/index-0.0.1.html`.

## Choix UX retenus

- Progression scène par scène, avec un bouton “Continuer”.
- Chaque scène apparaît par petits blocs, jamais comme un mur de texte.
- Les questions sont douces et non évaluatives : hypothèse libre, impression de compréhension, stratégies perçues.
- Les réponses sont conservées uniquement en mémoire de page, sans stockage.
- L’interface reste calme : grande zone de lecture, fond doux, repères visuels simples, rythme lent.
- Un panneau visuel accompagne le récit avec Lumi, la boîte, le grenier, la langue dominante et la progression.
- Le bouton “Revoir” permet de revenir légèrement en arrière sans complexifier l’expérience.

## Simplifications faites

- Aucun framework ni dépendance externe.
- Pas de système de sauvegarde.
- Pas de score, correction ou validation.
- Pas de moteur de narration.
- Pas de gestion avancée des réponses.
- Les animations sont limitées à une apparition simple des lignes.
- L’illustration est faite en CSS pour rester modifiable dans le même fichier.
- Le prototype ne cherche pas encore à produire des données de recherche exportables.

## Ce qui semble prometteur

- Lumi agit comme compagnon émotionnel : elle hésite, observe, puis continue.
- Le passage progressif FR → ES → IT → PT → FR soutient l’idée de compréhension malgré l’incertitude.
- Les questions demandent “qu’est-ce que tu ressens / qu’est-ce qui t’aide ?” plutôt que “as-tu la bonne réponse ?”.
- Les blocs courts peuvent réduire l’anxiété face aux langues inconnues.
- Le mot `viaje` et les phrases courtes dans d’autres langues créent des points d’inférence très observables.
- La scène finale reformule explicitement l’hypothèse pédagogique : on peut traverser plusieurs langues en comprenant plus que prévu.

## Ajustements probables après premiers tests

- Observer si le rythme est trop lent ou trop rapide.
- Vérifier si les enfants ou adultes comprennent qu’ils peuvent répondre librement sans être corrigés.
- Voir si les passages en espagnol, italien et portugais sont assez accessibles.
- Tester si la phrase finale arrive comme une découverte ou comme une explication trop directe.
- Ajuster la quantité de texte par bloc selon la fatigue de lecture.
- Ajouter plus tard une collecte légère des réponses si l’observation de terrain le justifie.
- Tester si Lumi est suffisamment présente émotionnellement sans devenir trop décorative.

## Hypothèse de cette V0

Une narration douce et continue peut aider un lecteur à traverser plusieurs langues sans se bloquer, parce que le contexte, la curiosité et quelques mots reconnaissables soutiennent l’inférence.
