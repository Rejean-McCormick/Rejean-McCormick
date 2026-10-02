[← Corpus](README.md) · [Table of contents](CONTENTS.md) · [Profile](../README.md)

<!-- Synchronisé avec Kristal-kOA-Ecosystem v0.4.0 — 2026-10-02. Ce wiki reste une projection de lecture; les dépôts propriétaires conservent leur autorité. -->

# Langage, SemantiK Architect et SenTient

La couche langage/sémantique sépare **interprétation**, **connaissance**, **réalisation linguistique** et **ingénierie de langue**. Une bonne intégration ne doit pas transformer un outil linguistique externe en autorité sur le sens ou la vérité du Digital Ecosystem.

## SemantiK Architect

SemantiK Architect réalise des représentations sémantiques vers des sorties humaines multilingues. Il peut planifier et articuler, mais n’est pas l’autorité de connaissance de Kristal et n’exécute pas automatiquement une `actionability` comme une directive.

La frontière avec GF est importante : le runtime SemantiK consomme des artefacts linguistiques validés; il ne devient pas l’atelier qui modifie silencieusement les sources GF/RGL.

## SemantiK Runtime Orchestrator

Le Runtime Orchestrator gère le séquençage de release, la promotion/rollback et l’ordre d’activation des RuntimeSets SemantiK. Il orchestre la transition runtime sans devenir l’autorité linguistique GF/RGL ni l’autorité de connaissance Kristal.

## SenTient

SenTient fournit extraction, résolution et réconciliation candidates. Il aide à transformer des entrées ambiguës en structures plus explicites tout en conservant l’incertitude nécessaire.

> **Résoudre un candidat ≠ reconnaître un référent comme autorité canonique.**

La reconnaissance, la provenance et l’état épistémique restent gouvernés par les systèmes qui les possèdent.

## Écosystème GF / MA-Gustave

L’ingénierie linguistique GF est **en amont** du runtime SemantiK et constitue un écosystème de soutien indépendant :

```text
GF / RGL
  → GF RGL AI Compendium
  → GF Wordbench
  → Ars Magna Lulli
       ↘ GF Observatory
  → artefact PGF / grammar immuable + preuves
  → conformance SemantiK
  → RuntimeSet
```

Les responsabilités restent distinctes :

- **GF/RGL** : autorité d’exécution/structure — typing, compilation, parsing, linearization, génération, morphologie, PGF;
- **GF RGL AI Compendium** : contrats, provenance, règles de preuve, workflows et gates; ne compile pas;
- **GF Wordbench** : validation native GF, diagnostics, régression, goldens, manifests et preuves;
- **Ars Magna Lulli** : orchestration GitOps multi-projets et états de promotion;
- **GF Observatory** : projection read-only de maturité/readiness/preuves;
- **revue humaine** : acceptation linguistique/publication lorsque requise.

Le handoff `semantik-wordbench-handoff-v1` est fail-closed et distingue explicitement **accepté pour validation Wordbench** de **preuve de release**.

## Outils externes de soutien

- **Ninai** : input/adaptateur sémantique optionnel à la frontière SemantiK;
- **OpenRefine** : nettoyage/réconciliation de données et soutien à la résolution de candidats;
- **OpenTapioca** : entity linking Wikidata externe;
- **Grammatical Framework** : autorité linguistique externe, pas membre du Digital Ecosystem.

Voir [Écosystèmes et outils de soutien](27-Ecosystemes-de-soutien.md).

## Documents de référence

- [SemantiK Architect](https://github.com/Rejean-McCormick/SemantiK-Architect)
- [SenTient](https://github.com/Rejean-McCormick/SenTient)
- [GF RGL AI Compendium](https://github.com/MA-Gustave/GF_RGL_AI_Compendium)
- [GF Wordbench](https://github.com/MA-Gustave/GF_Wordbench)
- [GF Observatory](https://github.com/MA-Gustave/GF_Observatory)
- [Ars Magna Lulli](https://github.com/MA-Gustave/Ars-Magna-Lulli)
- [GF Zone Auditor](https://github.com/Rejean-McCormick/SemantiK-Architect-GF-Zone-Auditor)
- [Grammatical Framework audit](https://github.com/Rejean-McCormick/Grammatical-Framework-audit)
