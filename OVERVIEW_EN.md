**Language / Nyelv:** [English](OVERVIEW_EN.md) · [Magyar](OVERVIEW_HU.md)

# LEGAL-RQV Professional — Overview

**A source-bound framework for preparing and checking legal work with AI**

Author: Almási Andor · Current release: v1.1.1 (October 2026) · Public overview

> This is a public overview. It explains what the system is, why it exists and which principles it follows. It does not contain code, schemas, configuration, test cases, scoring rules or any other detail from which the system could be rebuilt. The full package is confidential and is shared only under a non-disclosure agreement.

## What it is

LEGAL-RQV Professional is a structured framework for legal research, legal interpretation and the preparation of legal documents with AI assistance, focused primarily on Hungarian and European Union law.

It does not try to make an AI "sound like a lawyer". Its purpose is the opposite: to make every substantive legal statement **checkable**. Each claim must be tied to an official source and to the exact provision it relies on, and the work is not considered ready until a human professional has reviewed it.

It supports, among others:

- legal research and targeted legal questions;
- drafting new contracts and reviewing existing ones;
- legal letters (demand letters, replies, complaints);
- procedural filings to courts and authorities;
- compliance reviews;
- evidence matrices;
- legal translation.

## Why it was created

Large language models write fluent legal text, and that fluency is exactly the risk. In practice, the same failure types appear again and again:

- a section or paragraph is cited that **does not exist**;
- the law is applied in the **wrong temporal state** — an old or not-yet-effective version;
- the **jurisdiction** is assumed silently instead of being established;
- a contract looks complete but **a necessary clause is missing**;
- a **deadline** is miscalculated or its legal basis is not checked.

Each of these can be invisible in a well-written answer and costly in a real case. LEGAL-RQV was built to make such errors structurally harder to produce and easier to catch.

## Core principles

1. **No legal claim without a source.** Every substantive legal statement is linked to an official, authoritative source and the exact provision. Sources are graded by how authoritative they are; a consolidated or secondary text is not treated as equal to the official publication.
2. **Jurisdiction is never silent.** The applicable legal system must be established explicitly and traceably. The system does not quietly fall back to a default.
3. **Time is handled separately.** The time of the answer, the date of the legal state examined, the date of the relevant events and the time each source was checked are recorded as separate facts, not mixed.
4. **Deadlines are checked on their own.** Deadlines and their legal basis are verified as a separate step.
5. **Document-type completeness.** Each document type (for example a contract, a letter or a filing) has its own mandatory elements, and missing elements are flagged.
6. **Clear verdicts.** A critical error cannot be hidden behind a high quality score; blocking problems cap the overall result.
7. **Honest provenance.** A result counts as executed only if it was actually run, not merely read or described by another AI engine.
8. **Human review gate.** No contract, filing or legal letter is treated as final until the required human professional review has taken place.
9. **Engine-independent.** The framework is not tied to a single AI vendor; it is designed to work in any capable project environment.

## How it was developed

The framework was developed with several AI engines working in separate roles — drafting, critique and cross-validation — under human direction, with professional review by a practising lawyer. It has been used in practice on real legal materials, not only on test examples.

The release is versioned and accompanied by its own automated self-tests and structured legal test cases; the reproduced results of the current release pass without failures.

## What it is not

LEGAL-RQV is a discipline for **preparing** legal work to a professional standard. It does not create a lawyer–client relationship, does not represent anyone, and does not replace the professional responsibility of a lawyer.

## Access

The detailed professional specification and the runnable package are confidential. They can be made available for professional evaluation under a non-disclosure agreement.

Contact: [hyperbetteri@gmail.com](mailto:hyperbetteri@gmail.com) · [github.com/hyperbetteri](https://github.com/hyperbetteri)

---

© 2026 Almási Andor. All rights reserved. May be freely quoted with attribution.
