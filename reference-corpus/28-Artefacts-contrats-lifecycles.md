[← Corpus](README.md) · [Table of contents](CONTENTS.md) · [Profile](../README.md)

<!-- Synchronisé avec Kristal-kOA-Ecosystem v0.4.0 — 2026-10-02. Ce wiki reste une projection de lecture; les dépôts propriétaires conservent leur autorité. -->

# Artefacts, contrats et lifecycles

La carte des composants devient beaucoup plus utile lorsqu’elle montre **ce qui traverse les frontières**. Le Kristal représente donc des artefacts, contrats et lifecycles de premier ordre.

## Artefacts représentatifs

| Artefact | Propriétaire / rôle principal |
|---|---|
| **DecisionRecord** | décision civique finalisée de Konnaxion |
| **Signal** | entrée opérationnelle Orgo |
| **WorkflowVersion** | définition versionnée de workflow Orgo |
| **Case** | conteneur de suivi opérationnel Orgo |
| **Task** | unité de travail assignable/exécutable |
| **IntegrationOperation** | effet/intégration gouverné avec état/retry/receipt |
| **Corpus Harvest Handoff** | transfert d’evidence/candidats EncyKlopedia → Da’at |
| **Kristal State** | état de connaissance structuré |
| **Working Artifact** | artefact de travail non nécessairement reconnu |
| **Reference Artifact** | artefact reconnu/versionné consommable |
| **Runtime Pack** | artefact exécutable/offline vérifiable |
| **Release Set** | composition de release Koali |
| **RuntimeSet** | composition runtime SemantiK |
| **Space Manifest** | description d’une surface Koali Spaces |
| **Activation / rollback receipt** | preuve d’une transition runtime |
| **Impact / accountability publication** | retour d’exécution vers l’autorité civique |
| **GF/RGL Language Pack** | contexte/profil d’ingénierie linguistique |
| **GF Wordbench Run Bundle** | preuve structurée de validation/exécution GF |
| **Immutable PGF / grammar artifact** | artefact linguistique exécutable/versionné |
| **GF Maturity Snapshot** | projection d’état/maturité pour observation |

## Contrats représentatifs

### Civique ↔ opérationnel

- `governance.decision.execute/1.0.0` — **Konnaxion → Orgo**.
- `accountability.impact.publish/1.0.0` — **Orgo → Konnaxion**.

### Acquisition → connaissance

- `encyklopedia.corpus-harvest-handoff/1.0.0` — **EncyKlopedia → Da’at**; transfère evidence et candidats sans valider automatiquement.
- `Kristal Standard 6.0.0` — contrat du Kristal State, assertions, valuations, provenance, validation et actionability.
- `Referent Registry 1.0.0` — identité/résolution des référents.

### Kristal → projections

- `kristal.build.request/2.0.0` — demande de build/compilation sous profil explicite.
- `kristal.artifact.ready/2.0.0` — annonce d’un artefact prêt.
- `uckk.univers-cite-projection/1.0.0` — projection consommateur Kristal → UCKK sans transfert du canon.

### Langage

- `semantik-wordbench-handoff-v1` — candidat SemantiK → validation GF Wordbench; l’acceptation du handoff **n’est pas** une preuve de release.
- `GF Four-System Total Alignment / 1.0` — séparation des responsabilités entre GF/RGL, Compendium, Wordbench, Lulli, Observatory et revue humaine.

## Lifecycles

Le Kristal suit notamment :

1. **Acquisition / sensing** — découverte, capture, snapshot, extraction et handoff.
2. **Compilation / reconnaissance épistémique** — mapping, référents, Kristal State, validation/reconnaissance et projections.
3. **Deliberation / decision** — consultation, débat, drafting, décision et publication.
4. **Operational execution** — signal, case, workflow, task, effet, résultat et accountability.
5. **Release / activation** — admission, Release Set, vérification, activation et rollback.
6. **Presentation** — manifests, Spaces, routage et activation des surfaces.
7. **Projection / learning / diffusion** — matérialisation consommateur, apprentissage, archive et diffusion.
8. **GF language engineering** — evidence → architecture → contrats → implémentation → compilation → tests → release candidate → artefact immuable.

## Pourquoi les lifecycles comptent

Deux composants peuvent partager une capacité mais intervenir à des moments très différents. La carte lifecycle permet donc de répondre à :

- qui crée l’objet?;
- qui le valide?;
- qui le transforme?;
- qui peut l’activer?;
- qui observe le résultat?;
- qui garde la preuve?;
- comment une correction produit-elle un nouveau cycle plutôt qu’une mutation cachée?

Voir aussi : [Modèle d’autorité et frontières](05-Modele-autorite-et-frontieres.md) et [Utilités et patterns de workflow](26-Utilites-et-workflows.md).
