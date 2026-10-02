[← Corpus](README.md) · [Table of contents](CONTENTS.md) · [Profile](../README.md)

<!-- Synchronisé avec Kristal-kOA-Ecosystem v0.4.0 — 2026-10-02. Ce wiki reste une projection de lecture; les dépôts propriétaires conservent leur autorité. -->

# Carte des sources et autorité documentaire

Cette page indique **où regarder lorsque deux documents semblent dire des choses différentes**.

## Règle générale

Pour une question technique précise, préférer :

1. le dépôt du composant qui possède le domaine;
2. ses contrats, ADR, schémas et documents normatifs;
3. les contrats d’intégration entre composants;
4. les tests, preuves et artefacts signés/versionnés;
5. les dossiers de statut pour l’état courant;
6. le Kristal de synthèse pour la carte inter-systèmes;
7. ce wiki de lecture;
8. les documents narratifs, commerciaux ou prospectifs.

Le wiki explique la carte; le Kristal relie la carte; **ni l’un ni l’autre ne doit silencieusement remplacer l’autorité du dépôt propriétaire**.

## Carte des dépôts

| Domaine | Dépôt principal | Rôle |
|---|---|---|
| Vue système | [kOA-Digital-Ecosystem](https://github.com/Rejean-McCormick/kOA-Digital-Ecosystem) | architecture système-de-systèmes et contrats inter-domaines |
| Hôte / souveraineté / lifecycle | [kOA-Linux-Koali](https://github.com/Rejean-McCormick/kOA-Linux-Koali) | environnement opératoire et autorité hôte |
| Expérience Koali | [Koali-Spaces](https://github.com/Rejean-McCormick/Koali-Spaces) | composition de présentation |
| Civique / délibération | [Konnaxion](https://github.com/Rejean-McCormick/Konnaxion) | état civique, consultation, délibération, DecisionRecords |
| Exécution opérationnelle | [Orgo](https://github.com/Rejean-McCormick/Orgo) | Signals, Cases, Workflows, Tasks, résultats |
| Connaissance / provenance | [Kristal-Framework](https://github.com/Rejean-McCormick/Kristal-Framework) | Kristal State, référents, assertions, validation/reconnaissance |
| Interopérabilité | [Interaction-Kernel](https://github.com/Rejean-McCormick/Interaction-Kernel) | enveloppes/profils et transport inter-systèmes |
| Learning / diffusion | [UCKK](https://github.com/Rejean-McCormick/UCKK) | apprentissage, archive/médiathèque, diffusion |
| NLG multilingue | [SemantiK-Architect](https://github.com/Rejean-McCormick/SemantiK-Architect) | réalisation sémantique vers humain |
| Résolution sémantique | [SenTient](https://github.com/Rejean-McCormick/SenTient) | extraction/réconciliation candidates |
| Narrative | [King-Klown-Canon](https://github.com/Rejean-McCormick/King-Klown-Canon) | narration et mobilisation |
| Infrastructure physique | [Kristal-Farms](https://github.com/Rejean-McCormick/Kristal-Farms) | énergie, calcul, fibre, chaleur utile |

## Écosystème de soutien GF / MA-Gustave

Ces dépôts sont **indépendants du kOA Digital Ecosystem** même lorsqu’ils soutiennent SemantiK et les capacités multilingues :

- [GF RGL AI Compendium](https://github.com/MA-Gustave/GF_RGL_AI_Compendium)
- [GF Wordbench](https://github.com/MA-Gustave/GF_Wordbench)
- [GF Observatory](https://github.com/MA-Gustave/GF_Observatory)
- [Ars Magna Lulli](https://github.com/MA-Gustave/Ars-Magna-Lulli)

Grammatical Framework / RGL conserve son autorité propre d’exécution et de structure linguistique.

## Outils/patterns externes

**Decidim, Ninai, OpenRefine et OpenTapioca** sont représentés comme soutiens/patterns externes. Leur présence dans une chaîne fonctionnelle n’implique ni appartenance à kOA ni transfert d’autorité.

## Intégrations majeures

- Konnaxion → Orgo : décision civique vers exécution gouvernée;
- Orgo → Konnaxion : impact/accountability;
- EncyKlopedia → Da’at : handoff de corpus/evidence, sans validation épistémique automatique;
- Kristal → UCKK : projection consommateur rebuildable;
- GF/Wordbench → SemantiK : artefacts linguistiques + preuves, puis conformance/runtime propre à SemantiK;
- Koali Spaces ↔ applications : présentation/routage sans absorption de l’état métier.

Voir aussi : [Artefacts, contrats et lifecycles](28-Artefacts-contrats-lifecycles.md).
