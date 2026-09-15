[← Corpus](README.md) · [Table of contents](CONTENTS.md) · [Profile](../README.md)

# Koali / kOA-Linux

Koali est l’environnement opératoire du kOA Digital Ecosystem. Il ne s’agit pas d’une couche métier qui décide à la place des applications.

Son rôle concerne notamment :

- identité et confiance;
- politiques locales;
- ressources et privilèges;
- lifecycle des composants;
- artifacts et releases;
- backup, restore et rollback;
- profils de déploiement;
- continuité offline;
- frontières avec les services externes;
- expérience locale via Koali Spaces.

## Koali comme base souveraine

L’objectif est de préserver un cœur local gouvernable : une instance ne devrait pas perdre son identité, ses politiques, ses données, ses capacités autorisées et sa mémoire simplement parce qu’un service distant disparaît.

## UCKK comme intégration externe

Koali définit des ponts explicites vers UCKK. La publication sortante passe par un **Publication Gateway**, puis par un **UCKK Publication Bridge**. L’import est une direction séparée, avec quarantaine, validation et acceptation locale. Cela évite de transformer une intégration en synchronisation implicite.

## Documents de référence

- [Koali — charter](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/01-constitution/00-charter.md)
- [Koali — system overview](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/02-system/00-system-overview.md)
- [Koali — logical architecture](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/02-system/02-logical-architecture.md)
- [Koali — operating modes](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/02-system/03-operating-modes.md)
- [Koali — external integrations](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/02-system/16-external-integrations.md)
- [Publication Gateway](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/04-components/publication-gateway.md)
- [UCKK Publication Bridge](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/04-components/uckk-publication-bridge.md)
- [UCKK Import Bridge](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/04-components/uckk-import-bridge.md)

Pour l’état courant : [État courant et sources vivantes](24-Etat-courant.md).
