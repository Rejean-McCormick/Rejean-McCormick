[← Corpus](README.md) · [Table of contents](CONTENTS.md) · [Profile](../README.md)

<!-- Synchronisé avec Kristal-kOA-Ecosystem v0.4.0 — 2026-10-02. Ce wiki reste une projection de lecture; les dépôts propriétaires conservent leur autorité. -->

# Diagnostics et conformance

Les outils de diagnostic sont séparés des systèmes qu’ils examinent.

Cette séparation est importante : un outil de diagnostic peut mesurer, vérifier, produire des rapports, préserver des preuves et soutenir des gates sans devenir l’autorité métier du système cible.

## Famille Diagnostics & Conformance

Le Kristal regroupe cette fonction comme une famille de tooling, tout en gardant chaque outil distinct :

- **Konnaxion SecurityDiag** — qualification sécurité et durcissement de déploiement;
- **Konnaxion LevelUpDiag** — diagnostic/qualification de Konnaxion;
- **LevelUpDiag kOA-Linux** — validation et qualification de Koali;
- **LevelUpDiag Kristal** — qualification du système Kristal;
- **LevelUpDiag Orgo** — qualification d’Orgo;
- **LevelUpDiag SemantiK Architect** — qualification de SemantiK;
- **LevelUpDiag MediKristal** — qualification de MediKristal.

## Principe

> **Diagnostic ≠ autorité.**

Un diagnostic peut :

- observer;
- tester;
- classer un résultat;
- conserver une preuve;
- recommander ou bloquer selon un contrat de gate;
- soutenir une décision de release.

Il ne doit pas pour autant devenir propriétaire des données, workflows, politiques, connaissances ou décisions du système contrôlé.

Cette même règle s’applique au sous-écosystème GF : **Wordbench produit des preuves de validation, Observatory les projette, mais GF/RGL garde l’autorité d’exécution linguistique et la revue humaine garde l’acceptation linguistique lorsque requise.**

## Références détaillées

### Konnaxion SecurityDiag

- [Security model](https://github.com/Rejean-McCormick/Konnaxion-SecurityDiag/blob/main/docs/SECURITY_MODEL.md)
- [Level contract](https://github.com/Rejean-McCormick/Konnaxion-SecurityDiag/blob/main/docs/LEVEL_CONTRACT.md)
- [Release profiles](https://github.com/Rejean-McCormick/Konnaxion-SecurityDiag/blob/main/docs/RELEASE_PROFILES.md)
- [Release runbook](https://github.com/Rejean-McCormick/Konnaxion-SecurityDiag/blob/main/docs/RELEASE_RUNBOOK.md)

### Koali LevelUpDiag

- [Architecture](https://github.com/Rejean-McCormick/LevelUpDiag-kOA-Linux/blob/main/docs/ARCHITECTURE.md)
- [Koali sequence](https://github.com/Rejean-McCormick/LevelUpDiag-kOA-Linux/blob/main/docs/KOALI_SEQUENCE.md)
- [Result model](https://github.com/Rejean-McCormick/LevelUpDiag-kOA-Linux/blob/main/docs/RESULT_MODEL.md)
- [Security model](https://github.com/Rejean-McCormick/LevelUpDiag-kOA-Linux/blob/main/docs/SECURITY_MODEL.md)

## Références

- [Konnaxion SecurityDiag](https://github.com/Rejean-McCormick/Konnaxion-SecurityDiag)
- [Konnaxion LevelUpDiag](https://github.com/Rejean-McCormick/Konnaxion-LevelUpDiag)
- [LevelUpDiag kOA-Linux](https://github.com/Rejean-McCormick/LevelUpDiag-kOA-Linux)
- [LevelUpDiag Kristal](https://github.com/Rejean-McCormick/LevelUpDiag-Kristal)
- [LevelUpDiag Orgo](https://github.com/Rejean-McCormick/LevelUpDiag-Orgo)
- [LevelUpDiag SemantiK Architect](https://github.com/Rejean-McCormick/LevelUpDiag_SemantiK-Architect)
- [GF Wordbench](https://github.com/MA-Gustave/GF_Wordbench)
