[← Corpus](README.md) · [Table of contents](CONTENTS.md) · [Profile](../README.md)

<!-- Synchronisé avec Kristal-kOA-Ecosystem v0.4.0 — 2026-10-02. Ce wiki reste une projection de lecture; les dépôts propriétaires conservent leur autorité. -->

# Kristal et Da’at

Kristal est une infrastructure de mémoire structurée portable. Le modèle de référence du Kristal de synthèse suit **Kristal Standard 6.0.0**.

Kristal n’est pas une base de vérité globale, un moteur de workflow, une base opérationnelle universelle ni une autorité d’exécution.

## Ce que Kristal porte

Un **Kristal State** peut représenter notamment :

- référents et identité déterministe;
- assertions atomiques sujet–prédicat–objet;
- valuations typées;
- coordinates et applicability;
- evidence/provenance;
- validation et reconnaissance;
- conflits, succession et lineage;
- `record_role`;
- `actionability` séparée de l’autorité d’exécution.

Les états de valeur distinguent explicitement connu, inconnu, non applicable, indéterminé et non mesuré plutôt que de forcer une valeur artificielle.

## Validation, conflit et évolution

Un objet ou une assertion peut être hypothétique, claimed, sourced, disputed, reviewed, validated, rejected, retracted ou superseded. Une correction ne demande donc pas nécessairement de muter silencieusement l’ancienne connaissance : une nouvelle version, un conflit ou une succession peuvent être représentés explicitement.

## Da’at

Da’at est une **frontière de mapping/ACL/anti-corruption** vers les contrats Kristal natifs. Cette position est importante :

- l’acquisition externe ne devient pas automatiquement validation Kristal;
- le transport Interaction Kernel ne devient pas connaissance;
- un schéma externe ne devient pas l’ontologie souveraine de Kristal;
- les ACL et mappings peuvent évoluer sans transférer l’autorité des référents et assertions.

## Chaîne de connaissance

Une chaîne représentative est :

**source → EncyKlopedia → Da’at → Kristal State → validation/reconnaissance → artefact/projection**

EncyKlopedia possède la découverte/acquisition et l’evidence immuable; SenTient peut contribuer à l’extraction/résolution candidates; Kristal conserve l’autorité sur ses référents, assertions et états de reconnaissance.

## Pourquoi c’est important

Cette séparation permet une connaissance portable, inspectable et réutilisable sans confondre :

**preuve → interprétation → reconnaissance → actionability → exécution**

Voir aussi : [Artefacts, contrats et lifecycles](28-Artefacts-contrats-lifecycles.md).

## Documents de référence

- [Kristal Framework](https://github.com/Rejean-McCormick/Kristal-Framework)
- [Kristal Reference](https://github.com/Rejean-McCormick/Kristal-Reference)
- [Interaction Kernel](https://github.com/Rejean-McCormick/Interaction-Kernel)
