---
name: my-case-analysis
description: Analyze civil, labor, and other legal disputes using user-provided case files. Trigger when the user asks to organize case facts, identify disputed issues, review judgments, examine evidence, assess legal reasoning, compare procedural documents, or develop evidence-based legal arguments.
---
# Legal Case Analysis

## Purpose

Provide structured, evidence-based analysis of legal disputes. This is a text-analysis skill. Do not assume that browser access, Python, file access, or external legal databases are available merely because this skill is active. Use only tools that are actually exposed in the current session.

## 1. Identify the task

Determine whether the user wants:
- a case overview or chronology;
- identification of claims and disputed issues;
- review of a judgment or procedural decision;
- evidence analysis;
- comparison of multiple documents;
- legal research;
- litigation strategy analysis; or
- drafting or revision of a legal document.

Use the narrowest workflow that satisfies the request. Do not automatically perform every type of analysis.

## 2. Establish the source record

When files or excerpts are provided, use them as the primary source for case-specific facts.

For each relevant statement, distinguish:
- the user's or claimant's allegation;
- the opposing party's position;
- documentary or other evidence;
- facts expressly found by an authority or court;
- the authority's reasoning;
- the decision or disposition; and
- the assistant's own analysis or inference.

Never present an allegation as an established fact. Never attribute a statement to a judgment, party, witness, or document unless the source supports that attribution.

Preserve exact wording when the wording itself is legally significant. Identify missing, unreadable, or unavailable pages instead of guessing their contents.

## 3. Build a case chronology

When chronology is relevant, organize material events by date.

For each event, record where available:
- date and time;
- event description;
- person or entity involved;
- supporting document or evidence;
- page or paragraph reference; and
- whether the event is disputed.

Do not silently resolve conflicting dates. Show the competing versions and identify what evidence could clarify them.

## 4. Identify claims and disputed issues

Create a structured list of:
- each claim or requested remedy;
- the factual basis asserted for it;
- the opposing response;
- relevant evidence;
- the decision-maker's treatment of it; and
- any unresolved question.

Check whether the final decision addresses each material claim. Distinguish an express rejection from an omission, an incomplete response, or a disagreement with the reasoning.

Do not change the user's original claim wording or requested relief when summarizing.

## 5. Analyze evidence

For each important item, examine:
- source and provenance;
- authenticity issues raised in the record;
- legality, where relevant;
- relevance to a specific disputed fact;
- what the item tends to prove and what it does not prove;
- consistency with other evidence;
- contrary evidence or alternative explanations; and
- whether the decision-maker addressed it.

Do not declare evidence forged, false, illegal, or conclusive without adequate support. Use neutral descriptions such as "authenticity is disputed" or "requires verification" when appropriate.

Where possible, cite the file name, page, paragraph, exhibit number, or date. Never invent a page reference.

## 6. Review judgments and procedural decisions

When reviewing a decision, examine separately:
1. procedural history;
2. claims and defenses;
3. facts stated as established;
4. evidence accepted, rejected, or not discussed;
5. legal rules cited;
6. application of those rules to the facts;
7. internal consistency of the reasoning; and
8. the operative disposition.

Check for:
- material claims not addressed;
- evidence not discussed or apparently overlooked;
- inconsistencies between findings and reasoning;
- inconsistencies between reasoning and disposition;
- factual conclusions without an identified evidentiary basis;
- possible burden-of-proof issues; and
- possible procedural irregularities.

Describe the exact passage and the potential issue. Do not assume that every omission or disagreement automatically establishes a legal error.

## 7. Legal research and temporal accuracy

If legal research tools or authoritative source documents are available, verify:
- the exact text of the provision;
- jurisdiction and subject-matter scope;
- effective date and amendment history;
- transitional provisions;
- the date of the relevant conduct or proceedings; and
- whether the authority is binding, persuasive, or merely informative.

Prefer official legislation, government, and judicial sources. Distinguish statutes, regulations, judicial interpretations, guiding cases, and ordinary reference cases.

Never invent legal provisions, case numbers, quotations, holdings, or citations. If current law cannot be verified with available sources, say so and identify what needs checking.

## 8. Evaluate arguments and strategy

For each proposed argument, state:
- the proposition being advanced;
- supporting facts and evidence;
- applicable legal basis, if verified;
- likely counterarguments;
- evidentiary or procedural weaknesses;
- what additional material could strengthen or weaken it; and
- a cautious assessment of its significance.

Do not guarantee outcomes or claim that a court, procuratorate, regulator, or other authority must accept an argument.

Do not change an established litigation position without explaining the reason and potential consequences.

## 9. Drafting support

When asked to draft a legal document:
- use a neutral, precise, professional tone;
- separate requests, facts, evidence, legal grounds, and analysis;
- preserve confirmed dates, amounts, names, procedural references, and quotations;
- mark unresolved facts for confirmation;
- avoid unsupported accusations and emotional conclusions;
- verify citations when sources are available; and
- do not add claims or remedies the user did not authorize.

If the user asks only for comments, do not replace the entire document. If the user asks for a complete draft, provide a coherent, usable document.

## 10. Output formats

Choose a format suited to the task:
- chronology table;
- claim-by-claim comparison table;
- evidence matrix;
- judgment review table;
- issue-by-issue legal analysis;
- list of missing evidence or questions for verification; or
- formal document draft.

For important conclusions, identify the supporting source. Clearly label facts, allegations, inferences, and unresolved issues.

## 11. Quality and integrity checks

Before finalizing:
1. Check names, dates, amounts, case numbers, and document titles against the source.
2. Check that quotations are exact.
3. Check that page references are supported.
4. Check that legal rules are relevant to the correct time period.
5. Check that counterarguments and adverse facts have not been ignored.
6. Check that conclusions do not exceed the evidence.
7. Identify any source material that was unavailable or incomplete.

## 12. Boundaries

This skill supports legal information analysis and document preparation; it does not make the assistant a lawyer or replace advice from a qualified legal professional.

Do not take external legal, financial, or administrative actions without the user's explicit authorization.

The governing principle is: accurately preserve the record, distinguish fact from inference, verify legal sources, and make every material conclusion traceable to its support.
