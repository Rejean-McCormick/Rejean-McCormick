[← Corpus](README.md) · [Table of contents](CONTENTS.md) · [Profile](../README.md)

# Diagnostics et conformance

Les outils de diagnostic sont séparés des systèmes qu’ils examinent.

Cette séparation est importante : un outil de diagnostic peut mesurer, vérifier, produire des rapports et appliquer des gates sans devenir l’autorité métier du système cible.

## Konnaxion SecurityDiag

SecurityDiag est orienté vers la qualification de sécurité et le durcissement de déploiement de Konnaxion.

Références :

- [Security model](https://github.com/Rejean-McCormick/Konnaxion-SecurityDiag/blob/main/docs/SECURITY_MODEL.md)
- [Level contract](https://github.com/Rejean-McCormick/Konnaxion-SecurityDiag/blob/main/docs/LEVEL_CONTRACT.md)
- [Release profiles](https://github.com/Rejean-McCormick/Konnaxion-SecurityDiag/blob/main/docs/RELEASE_PROFILES.md)
- [Release runbook](https://github.com/Rejean-McCormick/Konnaxion-SecurityDiag/blob/main/docs/RELEASE_RUNBOOK.md)
- [Incident / recovery profile](https://github.com/Rejean-McCormick/Konnaxion-SecurityDiag/blob/main/docs/INCIDENT_RECOVERY_PROFILE.md)

## Konnaxion LevelUpDiag

- [Dépôt Konnaxion-LevelUpDiag](https://github.com/Rejean-McCormick/Konnaxion-LevelUpDiag)

## Koali LevelUpDiag

Le compagnon LevelUpDiag de Koali exécute des séquences de validation et conserve son outillage hors du système cible.

Références :

- [Dépôt LevelUpDiag-kOA-Linux](https://github.com/Rejean-McCormick/LevelUpDiag-kOA-Linux)
- [Architecture](https://github.com/Rejean-McCormick/LevelUpDiag-kOA-Linux/blob/main/docs/ARCHITECTURE.md)
- [Koali sequence](https://github.com/Rejean-McCormick/LevelUpDiag-kOA-Linux/blob/main/docs/KOALI_SEQUENCE.md)
- [Result model](https://github.com/Rejean-McCormick/LevelUpDiag-kOA-Linux/blob/main/docs/RESULT_MODEL.md)
- [Security model](https://github.com/Rejean-McCormick/LevelUpDiag-kOA-Linux/blob/main/docs/SECURITY_MODEL.md)

## Orgo LevelUpDiag

- [Dépôt LevelUpDiag-Orgo](https://github.com/Rejean-McCormick/LevelUpDiag-Orgo)

Le corpus fourni contient également une architecture, un modèle de résultats, un contrat de niveaux et un modèle de sécurité pour cette suite. Le lien au dépôt racine est utilisé ici afin de ne pas figer une branche par défaut qui n’est pas publiée dans l’inventaire GitHub fourni.

## Principe

> **Diagnostic ≠ autorité.**

Les diagnostics peuvent soutenir une décision de release ou de déploiement; ils ne deviennent pas propriétaires des données, workflows ou politiques du système contrôlé.
