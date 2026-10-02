[← Corpus](README.md) · [Table of contents](CONTENTS.md) · [Profile](../README.md)

<!-- Synchronisé avec Kristal-kOA-Ecosystem v0.4.0 — 2026-10-02. Ce wiki reste une projection de lecture; les dépôts propriétaires conservent leur autorité. -->

# Écosystèmes et outils de soutien

Une limite importante du modèle est maintenant explicite :

> **Support ≠ appartenance.**

Un outil peut soutenir une capacité de kOA sans devenir un composant du kOA Digital Ecosystem, sans posséder son état et sans être requis pour tous les déploiements.

## Sources de patterns externes

### Decidim

Decidim est représenté comme **source de patterns de participation** pour ethiKos, notamment le scaffolding de processus participatifs. Le Kristal ne le traite pas comme un sous-composant de Konnaxion ni comme une autorité civique interne.

## Outils sémantiques/données externes

### Ninai

Ninai est un input/adaptateur sémantique optionnel à la frontière SemantiK. Ses types terminent à un adaptateur; ils ne définissent pas le modèle canonique SemantiK.

### OpenRefine

OpenRefine soutient le nettoyage, la réconciliation de données et la préparation/résolution de candidats. Il ne devient pas l’autorité des référents Kristal.

### OpenTapioca

OpenTapioca soutient l’entity linking Wikidata. Un lien externe aide à résoudre un candidat mais ne transfère pas l’autorité de reconnaissance au service externe.

## Grammatical Framework / RGL

GF/RGL est une **autorité externe d’exécution et de structure linguistique**. Le Digital Ecosystem peut dépendre de certains artefacts GF pour la réalisation multilingue, mais GF reste externe à kOA.

## MA-Gustave GF Language Engineering Ecosystem

Cet ensemble est modélisé comme **supporting_ecosystem** indépendant :

```text
GF / RGL
  = autorité d’exécution et structurelle

GF RGL AI Compendium
  = contrats + provenance + règles de preuve + workflows + gates
        ↓
GF Wordbench
  = exécution GF + diagnostics + régression + preuves préservées
        ↓
Ars Magna Lulli
  = orchestration GitOps multi-projets + états de promotion
        ↘
         GF Observatory
         = vue read-only de maturité/readiness/preuves
        ↓
artefact PGF/grammar immuable + validation evidence
        ↓
conformance / RuntimeSet SemantiK
```

### Frontières d’autorité

- **GF** décide typing, compilation, parsing, linearization, génération, morphologie et production PGF.
- **Compendium** gouverne le contexte d’ingénierie mais ne compile pas.
- **Wordbench** exécute/observe/valide et préserve la preuve; il ne devient pas l’autorité linguistique.
- **Lulli** orchestre les projets et pipelines; il ne réinterprète pas les verdicts.
- **Observatory** agrège des preuves; il ne compile pas et ne modifie pas les workspaces.
- **SemantiK** consomme les artefacts après sa propre frontière de conformance/release.
- **La revue humaine** conserve l’acceptation linguistique/publication lorsqu’elle est requise.

## Pourquoi cette distinction compte

Sans cette frontière, une carte d’écosystème tend à absorber tout outil utile et finit par ne plus distinguer :

- composant propriétaire;
- extension;
- outil de qualification;
- source de pattern;
- dépendance externe;
- écosystème de soutien autonome.

Le Kristal conserve ces catégories afin qu’une intégration puisse être forte **sans devenir une assimilation**.

## Références

- [MA-Gustave](https://github.com/MA-Gustave)
- [GF RGL AI Compendium](https://github.com/MA-Gustave/GF_RGL_AI_Compendium)
- [GF Wordbench](https://github.com/MA-Gustave/GF_Wordbench)
- [GF Observatory](https://github.com/MA-Gustave/GF_Observatory)
- [Ars Magna Lulli](https://github.com/MA-Gustave/Ars-Magna-Lulli)
- [SemantiK Architect — ecosystem boundaries](https://github.com/Rejean-McCormick/SemantiK-Architect/blob/main/docs/15_ECOSYSTEM_BOUNDARIES.md)
