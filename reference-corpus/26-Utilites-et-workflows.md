[← Corpus](README.md) · [Table of contents](CONTENTS.md) · [Profile](../README.md)

<!-- Synchronisé avec Kristal-kOA-Ecosystem v0.4.0 — 2026-10-02. Ce wiki reste une projection de lecture; les dépôts propriétaires conservent leur autorité. -->

# Utilités et patterns de workflow

Le Kristal ajoute une lecture orientée usage qui évite de confondre besoins, features et produits.

```text
Need
  ↓
Utility
  ↓
Workflow Pattern
  ↓
Capabilities
  ↓
Components
  ↓
Artifacts / contracts / results
```

## Huit familles d’utilité

| Utilité | Question pratique |
|---|---|
| **Find & Understand** | Comment passer d’un signal/question à un contexte structuré, sourcé et intelligible? |
| **Learn & Share** | Comment transformer savoir et pratique en apprentissage transmissible? |
| **Collaborate & Create** | Comment réunir personnes, responsabilités, versions et artefacts pour produire ensemble? |
| **Choose & Govern** | Comment délibérer, comparer, prioriser et conserver le pourquoi d’une décision? |
| **Organize & Act** | Comment transformer intention/décision en travail attribué et vérifiable? |
| **Respond & Coordinate** | Comment maintenir une situation commune et coordonner sous changement ou crise? |
| **Remember & Improve** | Comment convertir résultats, erreurs et preuves en mémoire et capacité future? |
| **Disseminate & Connect to the Public** | Comment expliquer, publier, enseigner et garder les sorties reliées aux sources? |

## Patterns réutilisables

Les 24 patterns servent de géométrie intermédiaire entre scénario et composant. Exemples :

- investiguer un signal;
- reconstruire contexte et provenance;
- construire une vue partagée à partir de sources dispersées;
- créer un parcours d’apprentissage à partir d’une pratique;
- former une équipe autour d’un besoin;
- délibérer et produire une décision traçable;
- transformer une décision en travail gouverné;
- coordonner une réponse à un incident;
- maintenir une situation partagée qui change;
- continuer à travailler en mode terrain/offline;
- publier vers le public avec provenance;
- convertir résultats et corrections en mémoire réutilisable.

## Continuité de contexte

Les scénarios font ressortir une capacité transversale : **garder ensemble le pourquoi, l’état courant, les sources, les incertitudes, les responsabilités, les questions ouvertes, les décisions et les résultats à travers les handoffs**.

Cette continuité doit survivre notamment :

- au changement de personne;
- au passage entre systèmes;
- à un incident;
- à une période offline;
- à un changement de version;
- au passage décision → exécution;
- au passage exécution → apprentissage.

## Exemple de composition

```text
Respond & Coordinate
  ↓
Turn an incident into coordinated response
  ↓
Sensing + structured knowledge + context continuity
+ workflow routing + reliable integration
+ offline operation + accountability
  ↓
composition possible de Kristal, Orgo, Konnaxion,
Koali, Interaction Kernel, Konfid, Ariane, etc.
```

Le mot **possible** est essentiel : la composition montre une architecture candidate, pas un déploiement prouvé.

## Pourquoi cette couche est utile

Elle permet de demander au corpus non seulement **« quels composants existent? »**, mais aussi :

- quel besoin cette capacité adresse-t-elle?;
- quels workflows traversent plusieurs autorités?;
- quels composants sont substituables ou complémentaires?;
- où faut-il un contrat/handoff?;
- où risque-t-on de perdre provenance, contexte ou responsabilité?;
- quelles capacités doivent survivre offline?

Voir aussi : [Scénarios et usages](16-Scenarios-et-usages.md) et [Artefacts, contrats et lifecycles](28-Artefacts-contrats-lifecycles.md).
