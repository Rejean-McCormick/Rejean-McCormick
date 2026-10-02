[← Corpus](README.md) · [Table of contents](CONTENTS.md) · [Profile](../README.md)

<!-- Synchronisé avec Kristal-kOA-Ecosystem v0.4.0 — 2026-10-02. Ce wiki reste une projection de lecture; les dépôts propriétaires conservent leur autorité. -->

# Offline, souveraineté et résilience

La continuité offline est un principe d’architecture, pas seulement une option d’interface.

Une instance locale doit pouvoir conserver les capacités que son profil classe comme continues lorsque disparaissent :

- Internet;
- un fournisseur cloud;
- un service d’IA;
- un pair distant;
- une API externe;
- une infrastructure optionnelle.

Les opérations impossibles ou dangereuses doivent devenir explicitement **dégradées, différées ou bloquées**, plutôt que d’être simulées.

## Pourquoi

Cette propriété est pertinente pour :

- communautés éloignées;
- écoles ou organisations à connectivité limitée;
- infrastructures critiques;
- panne d’un fournisseur;
- censure;
- observation hostile;
- incident cyber;
- besoin volontaire de souveraineté locale.

Ce n’est pas une promesse d’invulnérabilité. C’est une stratégie de **réduction de dépendance et de limitation du rayon d’impact**.

## Ce que le Kristal relie à la résilience

La résilience n’est pas un composant unique. Elle combine notamment identité locale, politiques locales, ressources, releases vérifiables, backup/recovery, fonctionnement dégradé, artefacts portables, protocoles d’échange et capacité de reconstruire des projections. Les workflows de scénario ajoutent une dimension importante : **continuité de contexte** à travers un handoff, un incident, un changement de personne, une panne réseau ou une restauration.

## Documents de référence

- [Koali — offline continuity](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/01-constitution/09-offline-continuity.md)
- [Koali — portability, restore and exit](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/01-constitution/11-portability-restore-and-exit.md)
- [Koali — offline behavior](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/02-system/08-offline-behavior.md)
- [Koali Spaces — offline model](https://github.com/Rejean-McCormick/Koali-Spaces/blob/main/docs/10-offline/00-offline-model.md)
- [Koali Spaces — degradation](https://github.com/Rejean-McCormick/Koali-Spaces/blob/main/docs/10-offline/02-degradation.md)
- [Koali Spaces — recovery](https://github.com/Rejean-McCormick/Koali-Spaces/blob/main/docs/10-offline/03-recovery.md)
- [Interaction Kernel — reliability](https://github.com/Rejean-McCormick/Interaction-Kernel/blob/main/docs/reliability.md)
