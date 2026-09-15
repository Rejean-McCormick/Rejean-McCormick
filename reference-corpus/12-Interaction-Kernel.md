[← Corpus](README.md) · [Table of contents](CONTENTS.md) · [Profile](../README.md)

# Interaction Kernel

L’Interaction Kernel est un protocole d’interopérabilité entre systèmes autonomes.

Il standardise des formes d’interaction comme :

- **Command**
- **Query**
- **Event**
- **Receipt**
- **QueryResult**
- échange d’artefacts
- profils et capacités
- livraison fiable
- réconciliation

## Pourquoi un protocole séparé

Sans protocole clair, l’intégration entre deux applications finit souvent par devenir un accès direct à la base de données de l’autre. Cela crée du couplage, brouille les responsabilités et rend le remplacement d’un composant difficile.

L’Interaction Kernel impose plutôt une relation explicite :

> **demander / signaler / recevoir / attester**, sans transfert implicite de propriété du domaine.

Une acceptation de commande ne signifie pas nécessairement que l’effet final est déjà réalisé. Les reçus, événements, idempotency et mécanismes de réconciliation permettent de représenter proprement cette différence.

## Documents de référence

- [Architecture](https://github.com/Rejean-McCormick/Interaction-Kernel/blob/main/docs/architecture.md)
- [Core protocol](https://github.com/Rejean-McCormick/Interaction-Kernel/blob/main/docs/core-protocol.md)
- [Envelope](https://github.com/Rejean-McCormick/Interaction-Kernel/blob/main/docs/envelope.md)
- [Reliability](https://github.com/Rejean-McCormick/Interaction-Kernel/blob/main/docs/reliability.md)
- [Security and authority](https://github.com/Rejean-McCormick/Interaction-Kernel/blob/main/docs/security-authority.md)
- [Artifact interchange](https://github.com/Rejean-McCormick/Interaction-Kernel/blob/main/docs/artifact-interchange.md)
- [Conformance](https://github.com/Rejean-McCormick/Interaction-Kernel/blob/main/docs/conformance.md)
- [Kristal / Da’at](https://github.com/Rejean-McCormick/Interaction-Kernel/blob/main/docs/kristal-daat.md)
