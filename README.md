# IC-Lab — Intercomprehension Lab

IC-Lab est un laboratoire de prototypage pédagogique rapide centré sur l’intercompréhension (IC).

Son objectif est d’explorer, tester et matérialiser rapidement des idées pédagogiques autour de la compréhension plurilingue, avant toute stabilisation théorique ou technique.

IC-Lab privilégie les démonstrateurs concrets, observables et montrables à des enseignants, chercheurs et apprenants.

---

## Pourquoi IC-Lab ?

Certaines idées pédagogiques gagnent à être explorées rapidement.

L’intercompréhension soulève de nombreuses hypothèses :

* Comment un apprenant entre-t-il dans une langue inconnue ?
* Quels indices facilitent réellement la compréhension ?
* Quels gestes de lecture émergent spontanément ?
* Comment guider sans sur-expliquer ?
* Quels dispositifs favorisent la confiance dans la compréhension partielle ?

Plutôt que d’attendre un système complet, IC-Lab permet de construire des prototypes rapides pour observer ces questions en situation.

---

## Relation avec Boost Hyper Engine (BHE)

IC-Lab n’est pas BHE.

BHE explore une architecture pédagogique générale, modulaire et durable.

IC-Lab fonctionne comme un espace d’expérimentation plus léger :

**BHE = architecture profonde**
**IC-Lab = expérimentation rapide**

Les prototypes d’IC-Lab peuvent nourrir BHE, mais ne cherchent pas à respecter immédiatement ses contraintes architecturales.

Le code peut être simplifié, partiellement jetable ou fortement expérimental si cela accélère l’exploration pédagogique.

---

## Philosophie du laboratoire

Nous privilégions :

* des prototypes simples et rapidement testables ;
* du HTML/CSS/JS autonome quand cela suffit ;
* une logique d’itération rapide ;
* des observations pédagogiques concrètes ;
* des démonstrateurs montrables plutôt que des produits finalisés.

Nous évitons :

* l’overengineering ;
* la construction prématurée de frameworks ;
* les abstractions trop tôt ;
* l’illusion d’un produit fini.

Un prototype n’a pas besoin d’être parfait.

Il doit surtout permettre de **voir quelque chose, comprendre quelque chose, discuter quelque chose**.

---

## Structure du projet

```txt
docs/
├── interview-feedback/
├── pedagogical-signals/
└── prototype-observations/

prototypes/
└── XX-prototype-name/

playground/
```

### `prototype-observations`

Rapports de stabilisation, hypothèses, signaux observés.

### `pedagogical-signals`

Idées pédagogiques récurrentes ou émergentes.

### `interview-feedback`

Retours issus d’enseignants, chercheurs ou expérimentations.

### `playground`

Zone libre d’exploration rapide.

---

## Workflow de prototypage

Chaque prototype suit une logique simple :

**idée → prototype → observation → discussion → itération**

Chaque prototype devrait idéalement documenter :

* une question pédagogique ;
* une hypothèse ;
* une mécanique testée ;
* ce qu’on cherche à observer ;
* ses limites actuelles.

---

## Travail avec Codex

Dans IC-Lab, Codex agit principalement comme :

**maker rapide + implémenteur propre**

Son rôle :

* coder vite ;
* stabiliser légèrement ;
* nettoyer ;
* produire des rapports ;
* documenter les hypothèses observables.

Il ne définit pas seul la vision pédagogique.

Les arbitrages pédagogiques restent humains.

---

## Principe fondamental

> Prototype rapide.
> Observation sérieuse.
> Complexité différée.
