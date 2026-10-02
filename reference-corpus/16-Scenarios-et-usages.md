[← Corpus](README.md) · [Table of contents](CONTENTS.md) · [Profile](../README.md)

<!-- Synchronisé avec Kristal-kOA-Ecosystem v0.4.0 — 2026-10-02. Ce wiki reste une projection de lecture; les dépôts propriétaires conservent leur autorité. -->

# Scénarios et usages

Les scénarios sont une couche de **composition architecturale**. Ils montrent comment un problème peut traverser plusieurs capacités et composants sans supposer qu’un produit monolithique possède tout le workflow.

Le corpus synchronisé distingue :

- **120 scénarios Mosaic**;
- **36 archétypes de problèmes**;
- **24 patterns de workflow réutilisables**;
- **8 familles d’utilité**.

## À quoi sert le corpus

Les scénarios permettent notamment de :

- tester si l’architecture couvre un besoin de bout en bout;
- découvrir quelles capacités doivent coopérer;
- identifier les handoffs et frontières d’autorité;
- repérer les pertes possibles de contexte, preuve ou responsabilité;
- comparer des compositions dans différents domaines;
- voir quelles fonctions doivent continuer en mode dégradé/offline;
- révéler des capacités transversales, comme la continuité de contexte.

## Ce que le corpus ne prétend pas

Un scénario n’est pas automatiquement :

- un déploiement en production;
- une preuve d’intégration runtime;
- un produit distinct;
- une exigence universelle;
- une preuve que tous les composants nommés sont indispensables.

La notation conceptuelle `COMPOSED · runtime UNVERIFIED` signifie qu’une composition est documentée/plausible au niveau architecture, pas qu’elle a été exécutée avec succès en production.

## Du scénario au workflow

Le Kristal évite de transformer les 120 scénarios en 120 features. Il les rattache plutôt à des patterns réutilisables tels que :

- Investigate a signal;
- Reconstruct context and provenance;
- Turn an incident into coordinated response;
- Maintain a changing shared situation;
- Keep working in field/offline mode;
- Turn a decision into governed work;
- Preserve why a decision was made;
- Convert outcomes into reusable memory.

Voir [Utilités et patterns de workflow](26-Utilites-et-workflows.md).

## Explorer

- [Koali Scenario Mosaic](https://koaliscenariomosaic.netlify.app/en/uses/)
- [Koali Scenario Mosaic — dépôt](https://github.com/Rejean-McCormick/Koali-Scenario-Mosaic)
