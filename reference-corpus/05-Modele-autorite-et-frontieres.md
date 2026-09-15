[← Corpus](README.md) · [Table of contents](CONTENTS.md) · [Profile](../README.md)

# Modèle d’autorité et frontières

Le principe le plus important pour comprendre l’architecture est simple :

> **Intégrer n’est pas fusionner les autorités.**

Un composant peut demander une opération à un autre, recevoir un résultat ou transporter un artefact sans devenir propriétaire du domaine de l’autre.

## Exemples

- Konnaxion peut produire une décision publique sans devenir le système de tâches d’Orgo.
- Orgo peut exécuter un workflow issu d’une décision sans réécrire rétroactivement la décision.
- Kristal peut produire un artefact de connaissance sans devenir l’autorité d’identité de Koali.
- UCKK peut recevoir un contenu publié sans devenir propriétaire de la source locale.
- Koali Spaces peut présenter plusieurs applications sans absorber leur logique métier.

## Principe d’autorité explicite

Les systèmes critiques doivent rendre explicite :

- qui possède la donnée;
- qui peut la modifier;
- qui peut l’exposer;
- qui peut déclencher une transition;
- comment une transition est attestée;
- ce qui se passe lorsqu’un service externe n’est pas disponible.

## Documents de référence

- [Koali — explicit authority](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/01-constitution/04-explicit-authority.md)
- [Koali — fail-closed authority](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/01-constitution/05-fail-closed-authority.md)
- [Koali — data authority and ownership](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/01-constitution/08-data-authority-and-ownership.md)
- [Koali — component boundaries](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/02-system/04-component-boundaries.md)
- [Koali — data authority](https://github.com/Rejean-McCormick/kOA-Linux-Koali/blob/main/docs/02-system/05-data-authority-and-ownership.md)
- [Konnaxion — boundaries and ownership](https://github.com/Rejean-McCormick/Konnaxion/blob/main/docs/Technical-Reference/BOUNDARIES_AND_OWNERSHIP.md)
- [Orgo — boundaries and ownership](https://github.com/Rejean-McCormick/Orgo/blob/master/docs/Technical-Reference/BOUNDARIES_AND_OWNERSHIP.md)
