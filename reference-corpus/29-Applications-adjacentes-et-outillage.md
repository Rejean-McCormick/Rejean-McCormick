[← Corpus](README.md) · [Table of contents](CONTENTS.md) · [Profile](../README.md)

<!-- Synchronisé avec Kristal-kOA-Ecosystem v0.4.0 — 2026-10-02. Ce wiki reste une projection de lecture; les dépôts propriétaires conservent leur autorité. -->

# Applications adjacentes, périphériques et outillage

Le Kristal distingue le **noyau du Digital Ecosystem** de plusieurs systèmes qui peuvent le compléter, l’outiller ou l’explorer sans devenir automatiquement des autorités du noyau.

Cette page évite deux erreurs symétriques : les ignorer parce qu’ils ne sont pas centraux, ou les absorber dans kOA simplement parce qu’ils sont utiles.

## Ariane

Ariane est cartographié comme système de navigation sémantique d’applications fondé sur un Atlas versionné d’états/transitions.

Sous-systèmes :

- **Ariane Atlas** — carte machine-readable d’états, éléments, transitions, fingerprints et résultats attendus;
- **Ariane Runtime / Theseus** — boucle `observe → match → plan → act → verify`, avec arrêt sur incertitude non résolue;
- **Ariane Safety / approvals** — classification de risque, politiques fail-closed et approbation humaine;
- **Ariane Assist Client** — surface optionnelle de guidance/overlay et validation par capture.

La frontière Koali est représentée comme **préparée mais non activable** tant que les conditions de source/pin de release ne sont pas résolues. Le Kristal ne transforme donc pas une intégration envisagée en intégration active.

## Kamel

Kamel est un système d’assemblage de connaissance/contenu qui compose rôles, contextes, inventaires, cartes et modules en decks structurés et validés pour compréhension, décision et apprentissage.

Le Kristal le relie à des artefacts tels que `AssemblyRequest`, `ResolvedComposition`, `CompiledDeck` et manifests, mais le maintient comme **adjacent_not_core**.

## Konfid

Konfid est un plan de sécurité transversal pour :

- identity bindings;
- autorisation contextuelle;
- détection de risque;
- containment;
- approbations;
- preuve auditable.

Il est explicitement borné pour ne pas devenir un **super-admin universel**. Les systèmes propriétaires peuvent rester plus restrictifs, Orgo conserve les workflows humains/escalades et les agents locaux conservent l’exécution privilégiée bornée.

## Konductor

Konductor est un runtime durable pour du travail IA autonome **borné** : workflows typés, routage validé, outils permissionnés, checkpoints, événements, human-in-the-loop et reprise.

Il soutient des workflows agentiques sans devenir l’autorité civique de Konnaxion, l’autorité institutionnelle de workflow d’Orgo ni l’autorité de connaissance de Kristal.

## KeyFlow

KeyFlow est présent dans le Kristal avec un statut **claimed / candidate_unresolved**. L’inventaire disponible suggère un rôle de formulaires/intake, mais l’architecture détaillée n’était pas suffisamment documentée dans la passe de synthèse pour lui attribuer une autorité ou une place plus forte.

Cette incertitude est volontairement conservée au lieu d’être comblée par inférence.

## Kintsugi / Kompendio

Kintsugi / Kompendio est un **cadre d’intégration et catalogue de contrats**, pas une nouvelle autorité métier.

Il formalise notamment deux modes :

- **Mimic** — reproduire un pattern/capacité utile nativement, sans absorber la base externe;
- **Annex** — intégrer un outil externe par adaptateurs et frontières explicites.

Principe : pas de double vérité, propriété des données explicite, routes et audits explicites, replaceability préservée.

## SwarmCraft

SwarmCraft est représenté comme pattern/capacité conceptuelle d’exécution bornée de tâches gouvernées. Il ne désigne pas automatiquement une implémentation universelle ni une autorité d’exécution qui remplacerait Orgo ou Konductor.

## Règle de placement

Ces systèmes peuvent être :

- **peripheral_app**;
- **tooling**;
- **digital_conceptual**;
- **research_adjacent**.

Leur relation avec kOA doit être exprimée par des capacités, contrats et handoffs concrets plutôt que par une appartenance implicite.
