[← Corpus](README.md) · [Table of contents](CONTENTS.md) · [Profile](../README.md)

<!-- Synchronisé avec Kristal-kOA-Ecosystem v0.4.0 — 2026-10-02. Ce wiki reste une projection de lecture; les dépôts propriétaires conservent leur autorité. -->

# Orgo

Orgo est l’autorité de travail opérationnel.

Sa logique centrale transforme des **signaux** en structures d’exécution :

**Signal → Case → Workflow → Task → Result / Evidence**

Orgo sert à rendre explicites :

- responsabilités;
- rôles;
- étapes;
- escalades;
- tâches;
- état d’exécution;
- cycles de revue;
- preuves de réalisation;
- suivi de cas.

## Relation avec Konnaxion

Konnaxion peut produire une décision, une consultation ou un signal collectif. Orgo peut ensuite transformer un signal autorisé en exécution opérationnelle. Les deux systèmes restent séparés afin que l’exécution ne puisse pas réécrire silencieusement la décision d’origine.

## Orgo Worlds

Orgo Worlds applique la logique de contexte/world à l’exécution opérationnelle afin que des environnements logiquement distincts puissent partager une plateforme sans partager implicitement leur état.

## Contrats de frontière

Le Kristal rend explicite un aller-retour sans fusion des autorités :

- `governance.decision.execute/1.0.0` : **Konnaxion → Orgo**, transporte une décision finalisée vers l’exécution gouvernée;
- `accountability.impact.publish/1.0.0` : **Orgo → Konnaxion**, retourne impact et accountability vers l’autorité civique source.

Orgo possède notamment **Signal, WorkflowVersion, Case, Task, IntegrationOperation**, l’état de retry/outbox et les résultats opérationnels. Il ne devient pas propriétaire du DecisionRecord source.

## Documents de référence

- [Orgo — README](https://github.com/Rejean-McCormick/Orgo/blob/master/docs/README.md)
- [Target Architecture](https://github.com/Rejean-McCormick/Orgo/blob/master/docs/Technical-Reference/TARGET_ARCHITECTURE.md)
- [Task, Case and Workflow Contract](https://github.com/Rejean-McCormick/Orgo/blob/master/docs/Technical-Reference/v3/3-Orgo%20v3%20-%20Task%20Case%20and%20Workflow%20Contract.md)
- [Architecture and Invariants](https://github.com/Rejean-McCormick/Orgo/blob/master/docs/Technical-Reference/v3/2-Orgo%20v3%20-%20Architecture%20and%20Invariants.md)
- [Integration Bridge](https://github.com/Rejean-McCormick/Orgo/blob/master/docs/Technical-Reference/INTEGRATION_BRIDGE.md)
- [Orgo Worlds — README](https://github.com/Rejean-McCormick/Orgo-Worlds/blob/main/docs/README.md)

Pour l’état courant : [État courant et sources vivantes](24-Etat-courant.md).
