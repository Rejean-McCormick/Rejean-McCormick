[← Corpus](README.md) · [Table of contents](CONTENTS.md) · [Profile](../README.md)

<!-- Synchronisé avec Kristal-kOA-Ecosystem v0.4.0 — 2026-10-02. Ce wiki reste une projection de lecture; les dépôts propriétaires conservent leur autorité. -->

# Le kOA Digital Ecosystem

Le kOA Digital Ecosystem est une infrastructure sociotechnique organisée autour d’un cycle de capacité collective :

**sources → connaissance → délibération → décision → exécution → résultats → apprentissage → mémoire**

Il n’est pas conçu comme une application monolithique. Il relie plusieurs systèmes qui gardent leurs états, autorités et contrats propres.

## Les grandes autorités

| Système | Autorité principale |
|---|---|
| **Koali / kOA-Linux** | hôte, identité/confiance, politique locale, ressources, admission, Release Sets, lifecycle et continuité locale |
| **Koali Spaces** | composition de présentation, shell, routage et lifecycle des Spaces; pas d’autorité métier |
| **Konnaxion** | état civique/public, coordination, consultation, délibération, DecisionRecords et accountability |
| **Orgo** | exécution opérationnelle : Signals, Cases, WorkflowVersions, Tasks, IntegrationOperations, résultats et preuve d’exécution |
| **EncyKlopedia** | découverte/acquisition de sources, résolution de fournisseurs, snapshots/evidence immuables et handoff de corpus |
| **SenTient** | extraction, résolution et réconciliation candidates; pas d’autorité de reconnaissance |
| **Da’at** | mapping, ACL et frontière d’adaptation vers les contrats Kristal natifs |
| **Kristal** | référents, Kristal State, valuations, applicability, provenance, validation/reconnaissance, lineage et actionability |
| **Interaction Kernel** | enveloppes/profils versionnés, commandes, requêtes, événements, receipts, échange d’artefacts; aucun état métier des participants |
| **SemantiK Architect** | planification/réalisation sémantique-vers-humain et articulation multilingue |
| **SemantiK Runtime Orchestrator** | séquençage, promotion/rollback et activation ordonnée des RuntimeSets SemantiK |
| **kristal_runtime** | vérification/compatibilité Runtime Pack, état actif et receipts activation/rollback |
| **kOA Node Agent** | transitions locales privilégiées, étroites et autorisées |

UCKK, King Klown, Kristal Farms et les écosystèmes de soutien ne deviennent pas membres du Digital Ecosystem simplement parce qu’ils sont reliés à lui.

## Quatre flux représentatifs

### Flux civique

**Konnaxion DecisionRecord → contrat de décision → Orgo → impact/accountability → Konnaxion**

La décision publique/collaborative et son exécution restent séparées.

### Flux de connaissance

**source → EncyKlopedia → Da’at → Kristal → artefact/projection consommateur**

Acquisition, mapping, validation et projection ne sont pas une seule autorité.

### Flux runtime

**Runtime Pack → admission/release Koali → kristal_runtime → Node Agent si privilège requis**

L’activation runtime n’est pas la même chose que l’activation d’une surface de présentation.

### Flux de présentation

**application admise → Koali Spaces → Space manifest/runtime → activation/routage**

Koali Spaces compose l’expérience mais ne devient pas propriétaire de l’état métier de l’application.

## Pourquoi séparer les autorités

La séparation permet :

- audit et traçabilité;
- remplacement d’un composant sans absorption de son domaine;
- fonctionnement dégradé et offline;
- autonomie des instances;
- limitation du blast radius;
- projections reconstruisibles;
- compréhension claire de qui peut décider, modifier, publier, activer ou exécuter.

Voir aussi : [Modèle d’autorité et frontières](05-Modele-autorite-et-frontieres.md), [Artefacts, contrats et lifecycles](28-Artefacts-contrats-lifecycles.md) et [Applications adjacentes et outillage](29-Applications-adjacentes-et-outillage.md).

## Documents de référence

- [kOA Digital Ecosystem](https://github.com/Rejean-McCormick/kOA-Digital-Ecosystem)
- [Koali / kOA-Linux](https://github.com/Rejean-McCormick/kOA-Linux-Koali)
- [Konnaxion](https://github.com/Rejean-McCormick/Konnaxion)
- [Orgo](https://github.com/Rejean-McCormick/Orgo)
- [Kristal Framework](https://github.com/Rejean-McCormick/Kristal-Framework)
- [Interaction Kernel](https://github.com/Rejean-McCormick/Interaction-Kernel)
- [SemantiK Architect](https://github.com/Rejean-McCormick/SemantiK-Architect)
