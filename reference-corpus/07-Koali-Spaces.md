[← Corpus](README.md) · [Table of contents](CONTENTS.md) · [Profile](../README.md)

<!-- Synchronisé avec Kristal-kOA-Ecosystem v0.4.0 — 2026-10-02. Ce wiki reste une projection de lecture; les dépôts propriétaires conservent leur autorité. -->

# Koali Spaces

Koali Spaces est la couche de composition de présentation du Digital Ecosystem.

Sa fonction couvre notamment :

- shell global et navigation;
- routage et registre de surfaces;
- composition de l’expérience;
- thèmes et surfaces globales;
- présentation d’applications autonomes;
- lifecycle des Spaces;
- visibilité de health/readiness;
- expérience adaptée aux états offline ou dégradés.

## Une règle essentielle

Koali Spaces **ne doit pas réimplémenter l’autorité métier** de Konnaxion, Orgo, Kristal, UCKK ou d’une autre application. Il présente, compose et route; les systèmes propriétaires conservent leurs décisions et leurs données.

La distinction importante est :

> **activer une surface ≠ activer un Runtime Pack**

Une expérience peut devenir visible dans le shell sans que Koali Spaces acquière le droit d’effectuer une transition privilégiée dans le runtime d’un autre système.

## Documents de référence

- [Product definition](https://github.com/Rejean-McCormick/Koali-Spaces/blob/main/docs/01-product/00-product-definition.md)
- [System overview](https://github.com/Rejean-McCormick/Koali-Spaces/blob/main/docs/02-architecture/00-system-overview.md)
- [Authority boundaries](https://github.com/Rejean-McCormick/Koali-Spaces/blob/main/docs/02-architecture/01-authority-boundaries.md)
- [Global shell](https://github.com/Rejean-McCormick/Koali-Spaces/blob/main/docs/04-shell/00-global-shell.md)
- [Offline model](https://github.com/Rejean-McCormick/Koali-Spaces/blob/main/docs/10-offline/00-offline-model.md)
- [Integration principles](https://github.com/Rejean-McCormick/Koali-Spaces/blob/main/docs/11-integrations/00-integration-principles.md)
