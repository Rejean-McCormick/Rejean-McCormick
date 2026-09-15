[← Corpus](README.md) · [Table of contents](CONTENTS.md) · [Profile](../README.md)

# UCKK

UCKK est l’infrastructure d’apprentissage et de diffusion du corpus.

L’implémentation actuelle est construite sur Moodle et ajoute une distribution coordonnée de plugins pour créer notamment :

- parcours et cours;
- défis;
- assemblées;
- archives;
- mécanismes d’intégrité;
- reporting;
- médiathèque publique;
- workflows de création et de publication.

## Une plateforme réutilisable

UCKK ne doit pas être confondu avec le seul contenu King Klown/kOA.

La distribution technique peut être adaptée pour un professeur, une institution, un gouvernement, une communauté, une organisation ou un créateur avec un autre contenu et une autre identité.

## Standalone et intégrations

Le mode standalone est un principe important : UCKK doit pouvoir fonctionner comme environnement Moodle complet sans dépendance obligatoire à Konnaxion.

Les intégrations externes sont optionnelles. Lorsqu’elles existent, elles ne doivent pas contourner les permissions, la confidentialité ni les journaux d’audit de Moodle.

## Médiathèque

La Médiathèque est une surface publique de consultation; l’Explorateur Médiathèque fournit recherche, filtres, navigation et découverte. Les médias, collections, sources, relations, droits et politiques restent possédés par le module d’archive.

## Publication depuis Koali

La publication vers UCKK est un flux gouverné : un contenu local sélectionné passe d’abord par le Publication Gateway de Koali, puis par le UCKK Publication Bridge pour l’emballage et le transport. Cela ne crée pas de synchronisation automatique.

## Documents de référence

- [UCKK — master execution doctrine](https://github.com/Rejean-McCormick/UCKK/blob/main/docs/00_master_execution_doctrine.md)
- [Domain boundaries and glossary](https://github.com/Rejean-McCormick/UCKK/blob/main/docs/01_domain_boundaries_and_glossary.md)
- [Distribution architecture](https://github.com/Rejean-McCormick/UCKK/blob/main/docs/02_distribution_architecture.md)
- [Pedagogy, courses, competencies and badges](https://github.com/Rejean-McCormick/UCKK/blob/main/docs/06_pedagogy_courses_competencies_badges.md)
- [Challenges and assemblies](https://github.com/Rejean-McCormick/UCKK/blob/main/docs/07_challenges_and_assemblies.md)
- [Integrity, archives and privacy](https://github.com/Rejean-McCormick/UCKK/blob/main/docs/08_integrity_archives_and_privacy.md)
- [Integrations, reporting and delivery](https://github.com/Rejean-McCormick/UCKK/blob/main/docs/09_integrations_reporting_delivery.md)
- [Médiathèque / Explorateur](https://github.com/Rejean-McCormick/UCKK/blob/main/docs/DOC_mediatheque_explorateur.md)
- [Faculty public contract](https://github.com/Rejean-McCormick/UCKK/blob/main/docs/12_faculty_pages_atlas_public_contract.md)
- [Koali — UCKK Publication Bridge](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/04-components/uckk-publication-bridge.md)

Surface publique : [uckk.org](https://uckk.org)
