[← Corpus](README.md) · [Table of contents](CONTENTS.md) · [Profile](../README.md)

# Carte des sources et autorité documentaire

Cette page indique **où regarder lorsque deux documents semblent dire des choses différentes**.

## Règle générale

Pour une question technique précise, préférer :

1. le dépôt du composant qui possède le domaine;
2. ses contrats, ADR, schémas et documents normatifs;
3. les contrats d’intégration entre composants;
4. les tests et preuves;
5. les dossiers de statut pour l’état courant;
6. ce wiki de synthèse;
7. les documents narratifs ou prospectifs.

Le wiki explique la carte; il ne doit pas devenir une deuxième source de vérité technique.

## Carte des dépôts

| Domaine | Dépôt principal | Références |
|---|---|---|
| Hôte, souveraineté, lifecycle | [kOA-Linux-Koali](https://github.com/Rejean-McCormick/kOA-Linux-Koali) | [Constitution](https://github.com/Rejean-McCormick/kOA-Linux-Koali/tree/main/docs/01-constitution) · [System](https://github.com/Rejean-McCormick/kOA-Linux-Koali/tree/main/docs/02-system) |
| Expérience Koali | [Koali-Spaces](https://github.com/Rejean-McCormick/Koali-Spaces) | [Architecture](https://github.com/Rejean-McCormick/Koali-Spaces/tree/main/docs/02-architecture) |
| Civic / délibération | [Konnaxion](https://github.com/Rejean-McCormick/Konnaxion) | [Technical Reference](https://github.com/Rejean-McCormick/Konnaxion/tree/main/docs/Technical-Reference) |
| Exécution opérationnelle | [Orgo](https://github.com/Rejean-McCormick/Orgo) | [Technical Reference](https://github.com/Rejean-McCormick/Orgo/tree/master/docs/Technical-Reference) |
| Connaissance / provenance | [Kristal-Framework](https://github.com/Rejean-McCormick/Kristal-Framework) | [Kristal v5](https://github.com/Rejean-McCormick/Kristal-Framework/tree/main/docs/Technical-Reference/kristal-docs-v5) |
| Interopérabilité | [Interaction-Kernel](https://github.com/Rejean-McCormick/Interaction-Kernel) | [docs](https://github.com/Rejean-McCormick/Interaction-Kernel/tree/main/docs) |
| Vue système | [kOA-Digital-Ecosystem](https://github.com/Rejean-McCormick/kOA-Digital-Ecosystem) | [Layer Model](https://github.com/Rejean-McCormick/kOA-Digital-Ecosystem/tree/main/docs/3-Layer-Model) |
| Learning / diffusion | [UCKK](https://github.com/Rejean-McCormick/UCKK) | [docs](https://github.com/Rejean-McCormick/UCKK/tree/main/docs) |
| Narrative | [King-Klown-Canon](https://github.com/Rejean-McCormick/King-Klown-Canon) | [START HERE](https://github.com/Rejean-McCormick/King-Klown-Canon/blob/main/START_HERE.md) |
| Physical infrastructure | [Kristal-Farms](https://github.com/Rejean-McCormick/Kristal-Farms) | [Core architecture](https://github.com/Rejean-McCormick/Kristal-Farms/tree/main/docs/10-core) |
| NLG multilingue | [SemantiK-Architect](https://github.com/Rejean-McCormick/SemantiK-Architect) | [docs](https://github.com/Rejean-McCormick/SemantiK-Architect/tree/main/docs) |
| Diagnostics / conformance | [Konnaxion-SecurityDiag](https://github.com/Rejean-McCormick/Konnaxion-SecurityDiag) | [docs](https://github.com/Rejean-McCormick/Konnaxion-SecurityDiag/tree/main/docs) |
| Entity reconciliation | [SenTient](https://github.com/Rejean-McCormick/SenTient) | [README](https://github.com/Rejean-McCormick/SenTient/blob/main/README.md) |

## Intégrations majeures

- Koali ↔ UCKK : [external integrations](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/02-system/16-external-integrations.md)
- Konnaxion ↔ Orgo : [integration index](https://github.com/Rejean-McCormick/kOA-Digital-Ecosystem/blob/main/docs/2-Technical-Reference/40-integration/orgo-konnaxion/index.md)
- Interaction Kernel ↔ Kristal / Da’at : [kristal-daat](https://github.com/Rejean-McCormick/Interaction-Kernel/blob/main/docs/kristal-daat.md)
- Koali Spaces ↔ apps : [integration principles](https://github.com/Rejean-McCormick/Koali-Spaces/blob/main/docs/11-integrations/00-integration-principles.md)
