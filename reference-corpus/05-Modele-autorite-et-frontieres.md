[← Corpus](README.md) · [Table of contents](CONTENTS.md) · [Profile](../README.md)

<!-- Synchronisé avec Kristal-kOA-Ecosystem v0.4.0 — 2026-10-02. Ce wiki reste une projection de lecture; les dépôts propriétaires conservent leur autorité. -->

# Modèle d’autorité et frontières

Le principe central est simple :

> **Intégrer n’est pas fusionner les autorités.**

Un composant peut demander une opération à un autre, recevoir un résultat, transporter un artefact ou matérialiser une projection sans devenir propriétaire du domaine de l’autre.

## Invariants d’autorité

- **Un état canonique a un propriétaire explicite.**
- **Pas d’écriture directe dans la base d’un autre système.** Les échanges passent par contrats, artefacts, commandes, événements ou projections.
- **Une projection doit rester reconstruisible** depuis l’autorité qui la source.
- **Acquisition ≠ validation.** Trouver et préserver une source ne suffit pas à la reconnaître comme connaissance validée.
- **Identifiant externe ≠ autorité.** Un QID, ID de fournisseur ou autre identifiant peut référencer sans définir la vérité interne.
- **Interaction Kernel n’est pas un propriétaire d’état métier.** Il transporte et fiabilise les échanges.
- **Space activation ≠ Runtime Pack activation.** Présentation et exécution ne partagent pas la même autorité.
- **Accepted ≠ succeeded.** L’acceptation d’une demande ou d’un artefact n’est pas la preuve de son exécution réussie.
- **Actionability ≠ execution authority.** Savoir qu’une action est applicable n’accorde pas le droit de l’exécuter.
- **Support ≠ appartenance.** Un outil ou écosystème de soutien peut être essentiel sans devenir membre du kOA Digital Ecosystem.

## Exemples

- Konnaxion peut posséder un **DecisionRecord** sans devenir le système de tâches d’Orgo.
- Orgo peut exécuter un workflow issu d’une décision sans réécrire rétroactivement cette décision.
- EncyKlopedia peut préserver une source et produire des candidats sans devenir l’autorité de validation de Kristal.
- Kristal peut indiquer une `actionability` sans devenir l’autorité opérationnelle qui exécute l’action.
- UCKK peut matérialiser une projection d’un artefact Kristal sans devenir le canon Kristal.
- Koali Spaces peut activer une surface sans activer un Runtime Pack.
- GF Wordbench peut produire une preuve de validation GF sans devenir l’autorité linguistique GF/RGL.
- GF Observatory peut agréger des preuves sans devenir le compilateur ni le propriétaire des workspaces.

## Principe d’autorité explicite

Les systèmes critiques doivent rendre explicite :

- qui possède la donnée;
- qui peut la modifier;
- qui peut la projeter;
- qui peut la publier;
- qui peut déclencher une transition;
- qui peut l’exécuter;
- comment une transition est attestée;
- quelles preuves doivent survivre;
- ce qui se passe lorsqu’un service externe n’est pas disponible.

## Invariants transversaux de cohérence

Le Kristal conserve aussi les règles suivantes : immutabilité des références publiées, validation avant promotion, préservation de l’ambiguïté, articulation sans nouveaux faits, vérification fail-closed, feedback gouverné/non mutant et traçabilité bout-en-bout.

## Documents de référence

- [Koali — explicit authority](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/01-constitution/04-explicit-authority.md)
- [Koali — fail-closed authority](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/01-constitution/05-fail-closed-authority.md)
- [Koali — data authority and ownership](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/01-constitution/08-data-authority-and-ownership.md)
- [Konnaxion — boundaries and ownership](https://github.com/Rejean-McCormick/Konnaxion/blob/main/docs/Technical-Reference/BOUNDARIES_AND_OWNERSHIP.md)
- [Orgo — boundaries and ownership](https://github.com/Rejean-McCormick/Orgo/blob/master/docs/Technical-Reference/BOUNDARIES_AND_OWNERSHIP.md)
- [SemantiK — ecosystem boundaries](https://github.com/Rejean-McCormick/SemantiK-Architect/blob/main/docs/15_ECOSYSTEM_BOUNDARIES.md)
