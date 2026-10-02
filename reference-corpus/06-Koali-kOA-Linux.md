[← Corpus](README.md) · [Table of contents](CONTENTS.md) · [Profile](../README.md)

<!-- Synchronisé avec Kristal-kOA-Ecosystem v0.4.0 — 2026-10-02. Ce wiki reste une projection de lecture; les dépôts propriétaires conservent leur autorité. -->

# Koali / kOA-Linux

Koali est l’environnement opératoire et l’autorité hôte du kOA Digital Ecosystem. Il ne s’agit pas d’une couche métier qui décide à la place des applications.

Son rôle couvre notamment identité/confiance, politiques, ressources, admission, lifecycle, releases, récupération, continuité offline et transitions locales privilégiées.

## Sous-systèmes distingués dans le Kristal

| Sous-système | Responsabilité |
|---|---|
| **Identity & Trust** | identité et preuves de confiance bornées; ne décide pas l’autorisation métier |
| **Governance Policy Runtime** | évalue les politiques locales versionnées et produit décisions/obligations/receipts sans exécuter l’opération |
| **Resource Governor** | admission, enveloppes, allocation, scheduling, throttling et suspension des ressources |
| **Audit Broker** | custodie bornée de l’audit, rétention, divulgation sélective et chaîne de garde |
| **Publication Gateway** | médiation de publication entre domaines d’autorité/disclosure avec preuve terminale |
| **kOA Mediatheque** | catalogue média local/offline, versions, provenance, droits, renditions et lifecycle |
| **kOA Assembly** | résout profils, dépendances, ressources, stockage, services et Release Sets vers des plans déterministes |
| **kristal_runtime** | vérifie Runtime Packs, compatibilité, état actif et activation/rollback |
| **kOA Node Agent** | exécute les transitions locales privilégiées autorisées |

**Koali Control Panel** est un outil de développement/orchestration : workspaces, diagnostics, validation, assemblage, tests et workflows de release. Il soutient Koali mais ne possède pas l’autorité métier runtime.

## Koali comme base souveraine

L’objectif est de préserver un cœur local gouvernable : une instance ne devrait pas perdre son identité, ses politiques, ses données, ses capacités autorisées et sa mémoire simplement parce qu’un service distant disparaît.

La continuité offline ne signifie pas que toute fonction est toujours disponible. Elle signifie que les capacités prévues par le profil local peuvent continuer ou se dégrader de manière explicite plutôt que dépendre silencieusement d’un service externe.

## UCKK comme intégration externe

Koali définit des ponts explicites vers UCKK. La publication sortante passe par une frontière de publication; l’import suit une direction distincte avec ses propres gates. Une intégration ne devient donc pas une synchronisation implicite ni un transfert d’autorité.

## Deux activations à ne pas confondre

- **Space activation** : présentation/routage dans Koali Spaces.
- **Runtime Pack activation** : transition d’exécution gouvernée par la chaîne Koali/kristal_runtime et, si nécessaire, le Node Agent.

## Documents de référence

- [Koali — charter](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/01-constitution/00-charter.md)
- [Koali — system overview](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/02-system/00-system-overview.md)
- [Koali — logical architecture](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/02-system/02-logical-architecture.md)
- [Koali — operating modes](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/02-system/03-operating-modes.md)
- [Koali — external integrations](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/02-system/16-external-integrations.md)
- [Koali Control Panel](https://github.com/Rejean-McCormick/Koali-Control-Panel)
- [LevelUpDiag-kOA-Linux](https://github.com/Rejean-McCormick/LevelUpDiag-kOA-Linux)

Pour l’état courant : [État courant et sources vivantes](24-Etat-courant.md).
