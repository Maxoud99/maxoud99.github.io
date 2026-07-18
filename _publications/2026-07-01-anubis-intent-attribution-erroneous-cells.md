---
title: "ANUBIS: Towards Intent Attribution for Erroneous Cells in Tabular Data"
collection: publications
category: conferences
permalink: /publication/2026-07-01-anubis-intent-attribution-erroneous-cells
excerpt: 'ANUBIS decides, for each erroneous cell in a dirty table, whether the value was changed deliberately or by accident — with no clean reference values required.'
date: 2026-07-01
venue: 'Under review — Proceedings of the VLDB Endowment (PVLDB)'
paperurl: 'https://github.com/Maxoud99/Anubis'
citation: 'Abdelmaksoud, Mohamed, Konrad Rieck, and Ziawasch Abedjan. &quot;ANUBIS: Towards Intent Attribution for Erroneous Cells in Tabular Data.&quot; Under review at <i>PVLDB</i>.'
---

Data quality management treats every detected error as an accidental deviation from a recoverable ground truth, repairing or imputing it regardless of cause. This assumption fails for *intentional* errors — gain-targeted manipulation, fairness masking, and obfuscation — where repair destroys the very evidence an audit needs.

ANUBIS studies **intent attribution**: deciding for each erroneous cell in a dirty table whether the value was changed deliberately or by accident, with no clean reference values required. It fingerprints each erroneous cell with 12 structural features computed from the dirty table and propagates intent labels from a seed of 1% labeled cells. On the first intent-annotated benchmark — nine datasets spanning five error-generating mechanisms, from confirmed financial fraud to LLM-authored and adversarial manipulations — ANUBIS outperforms every intention-unaware baseline on all but one of the two-class datasets, while LLM judges, statistical outlier detection, and label-matched classifiers fail to recover intent reliably.

**Authors:** Mohamed Abdelmaksoud, Konrad Rieck, Ziawasch Abedjan

**Code & artifacts:** [github.com/Maxoud99/Anubis](https://github.com/Maxoud99/Anubis)
