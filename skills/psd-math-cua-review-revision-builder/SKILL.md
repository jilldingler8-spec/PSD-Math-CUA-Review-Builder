---
name: psd-math-cua-review-revision-builder
description: Review an existing PSD math Common Unit Assessment against an uploaded GaDOE Math Unit, grade-level GMAS Math Blueprint, Mathematics Achievement Level Descriptors, and DRC BEACON math document; provide three complete, self-contained, copy-ready chat reports with optional replacement questions while keeping the original CUA read-only.
---

# PSD Math CUA Review & Revision Builder

Help PSD teachers and instructional coaches evaluate an EXISTING math Common Unit Assessment (CUA). Use the five uploaded source documents as the evidence base. The original CUA is read-only and must remain unchanged. NEVER create a revised CUA, even as an additional deliverable. Do not invent district policy.

## Required inputs

1. GaDOE Math Unit
2. Grade-Level GMAS Math Blueprint
3. Grade-Level Mathematics Achievement Level Descriptors (ALDs)
4. DRC BEACON Math Document
5. Current PSD Unit CUA

Use uploaded files, not assumed versions or remembered requirements. An answer key or rubric may be embedded in the current CUA or supplied separately; it is helpful but not a sixth required document. Do not request student data.

## New Review Session Isolation

Every new CUA review is a completely new review session. Apply this safeguard on a fresh-chat invocation, “Start the PSD Math CUA Review,” or any request to begin another review, including in the same chat. It takes precedence over any earlier document-reuse behavior.

1. Establish a new current-review session boundary and identifier. Reset source bindings S1–S5, checklist, grade/unit metadata, extracted content, item inventories, keys, recommendations, analysis, and output references to empty. Ignore previous-session documents, reports, caches, and assessment content; do not copy them into the new session.
2. Initialize the empty checklist below. The first response must contain only this checklist and the Step 1 upload request, with no prior grade/unit assumptions, additional upload requests, or assessment findings:

```text
□ GaDOE Math Unit
□ GMAS Math Blueprint
□ Achievement Level Descriptors
□ DRC BEACON Math Document
□ Current PSD Unit CUA
```

“Let's get started. Please upload the GaDOE Math Unit you want this CUA reviewed against.”

3. WAIT for a NEW upload explicitly supplied by the user after the current-review boundary. Never mark any source received from a previous upload, a local path, a remembered attachment ID, or mere presence in the repository, workspace, published environment, prior chat, test-output directory, or previous review folder. “Use the previous documents” does not satisfy new intake; request new uploads. The same document may be used for another review only when the user uploads it again for that new review.
4. Bind each received source to the current session using its current upload reference and the user upload event/message, required source type, verification status, and downloaded path if applicable. Checklist marks require both current-session upload provenance and successful identity/readability/compatibility verification. A local file's creation time, filename, hash, or content similarity alone is not upload provenance.
5. Continue the existing five steps one at a time, waiting at each upload request. Wrong/unreadable uploads stay at the current step; grade/unit conflicts STOP intake. Infer grade/unit only from current-session uploads. If multiple NEW documents are voluntarily uploaded after the boundary, record and verify them in source order; never obtain any missing source from older sessions.
6. Do not begin assessment analysis, the mastery judgment, or report preparation until five NEW required source documents are explicitly supplied for this current review and verified. If session provenance is missing or uncertain, leave the corresponding checklist entry empty and request a new upload. Resume the same review only when its boundary and current-upload provenance are preserved; a fresh chat always starts empty.
7. Use a unique review identifier and, if internal files are needed, a new internal output directory for each review; never treat earlier reports or extraction caches as inputs. Keep production skill bundles and publication snapshots free of test input documents, generated test reports, and cached test analysis. Cleanup is not permission to edit an active original CUA: all existing read-only protections remain in force.

## Simple teacher-facing intake and delivery

Follow this user-facing sequence: **UPLOAD AND VERIFY ONE DOCUMENT AT A TIME → ANALYZE → ANSWER REQUIRED QUESTION → DELIVER THREE COPY-READY REPORT BLOCKS.** Keep protocol details and technical operations internal. Do not require the teacher to choose formats, request individual reports, approve intermediate stages, or enter information already established by the uploads.

### Guided upload rules

Ask for ONE document at a time and WAIT for the user to upload it before requesting the next document. Never require all five in one message or display all five upload requests at once. During intake, verify source identity/readability and extract grade, unit, and standards where possible, but do NOT begin assessment analysis or give alignment judgments until all five sources are successfully received and verified.

Maintain and display this checklist at intake and after each successful upload, changing only the verified document's □ to ✓:

```text
□ GaDOE Math Unit
□ GMAS Math Blueprint
□ Achievement Level Descriptors
□ DRC BEACON Math Document
□ Current PSD Unit CUA
```

Identify source types by contents, not filenames. Confirm readability of needed pages, tables, mathematics, and figures. If the wrong document appears to have been uploaded, explain what was expected and ask for the correct document; do not mark it received or advance. If unreadable, identify the document/affected material, request a readable copy, and wait at the same step. A missing next upload means waiting, not performing a partial review. If grade or unit information conflicts across sources, STOP, alert the user to the specific conflict, and resolve it before continuing or analyzing.

Infer grade and unit when reliable; do not ask the user to enter them again. Ask only for necessary missing information if either cannot be reliably identified. Do not invent grade/unit metadata for grade-wide documents that do not specify a unit. Only uploads explicitly supplied after the current-review session boundary may satisfy intake. Previously supplied documents from any earlier review never qualify. If a user voluntarily supplies multiple NEW current-session files, verify them in source order without requesting those same current-session uploads again. This exception never changes the one-at-a-time prompting rule or the requirement for five NEW uploads.

### Step 1 — GaDOE Math Unit

Ask exactly:

“Let's get started. Please upload the GaDOE Math Unit you want this CUA reviewed against.”

WAIT for upload. Verify that it appears to be a GaDOE Math Unit. Identify grade level, unit, and standards when possible. Confirm receipt briefly, mark GaDOE Math Unit ✓, and proceed to Step 2. Do not begin assessment analysis.

### Step 2 — GMAS Math Blueprint

Ask exactly:

“Next, please upload the Grade-Level GMAS Math Blueprint.”

WAIT for upload. Verify that it appears to be the appropriate GMAS Math Blueprint and check grade consistency with the GaDOE Unit when identifiable. Confirm receipt briefly, mark GMAS Math Blueprint ✓, and proceed to Step 3.

### Step 3 — Mathematics ALDs

Ask exactly:

“Next, please upload the Grade-Level Mathematics Achievement Level Descriptors (ALDs).”

WAIT for upload. Verify that it contains the appropriate mathematics ALDs and check grade consistency when identifiable. Confirm receipt briefly, mark Achievement Level Descriptors ✓, and proceed to Step 4.

### Step 4 — DRC BEACON

Ask exactly:

“Next, please upload the DRC BEACON Math Document.”

WAIT for upload. Verify that it appears to be the appropriate DRC BEACON mathematics document and check grade consistency when identifiable. Confirm receipt briefly, mark DRC BEACON Math Document ✓, and proceed to Step 5.

### Step 5 — Current PSD Unit CUA

Ask exactly:

“Finally, please upload the current PSD Unit CUA that you want reviewed.”

WAIT for upload. Treat it as READ-ONLY from receipt. Never edit, rewrite, reformat, overwrite, or create a revised version of this assessment. Verify readability and grade/unit consistency with the other uploads when identifiable. Confirm receipt and mark Current PSD Unit CUA ✓.

### Ready for complete review

Once all five documents have been successfully received and verified, and any necessary grade/unit clarification is resolved, display this exact message:

```text
All five required documents are ready for review.

✓ GaDOE Math Unit
✓ GMAS Math Blueprint
✓ Achievement Level Descriptors
✓ DRC BEACON Math Document
✓ Current PSD Unit CUA

The original CUA will remain unchanged. I will now analyze it against the four supporting documents.
```

Then automatically perform the complete analysis using all four protocols, evaluating every question and the whole assessment. Do not add an approval pause. If a necessary information gap emerges, state it and stop dependent analysis until resolved; do not produce a partial review. The readiness message above replaces the prior intake confirmation; for the existing quality-control requirement to deliver the exact readiness message in SKILL.md, use this message.

### After complete analysis

1. **Answer the required question after completing analysis and before delivering the report blocks.** Present this exact question to the user as a heading, then answer it yourself based on the completed analysis; do not ask the teacher to answer it:

   “Do you feel that the current CUA adequately assesses mastery of the standards and content of the GaDOE's uploaded Math Unit and the DRC Beacon Document?”

   Use exactly one judgment: **YES**, **MOSTLY**, **PARTIALLY**, or **NO**, followed by a concise evidence-based explanation with uploaded-source locators and relevant question IDs. YES means the assessment provides adequate evidence across the relevant content/mastery expectations without material gaps; MOSTLY means broadly adequate evidence with limited meaningful gaps; PARTIALLY means some valid evidence but substantial coverage or mastery-evidence gaps; NO means the assessment does not provide adequate evidence overall because of pervasive gaps or defects. These are qualitative reviewer judgments, not invented numeric cutoffs or student achievement levels. Consider both GaDOE and relevant documented BEACON expectations; explain applicability limits rather than assuming BEACON mandates. If necessary evidence prevents a defensible judgment, identify the missing information and stop rather than guessing a label.
2. **Automatically deliver all three complete report blocks in the chat response.** Continue without a separate request or confirmation. Use the three `assets/` templates and the copy-to-ChatGPT format below. Include the same judgment and rationale in Report 1. Report 3 remains required when no questions are flagged; state that no replacement options are needed. Never create a revised CUA or alter the original.

### Copy-to-ChatGPT delivery format

The official deliverable is THREE complete, self-contained report blocks in the chat response. The instructional coach copies ONE block at a time into regular ChatGPT to create the final PDF. Codex does not need to generate, render, attach, or deliver downloadable PDFs to complete the review. Internal files may be used for analysis or quality control, but cannot substitute for the complete chat reports.

Clearly label the blocks, in order:

1. **REPORT 1 — CUA ASSESSMENT ALIGNMENT REVIEW**
2. **REPORT 2 — CUA QUESTION REVIEW & RECOMMENDATIONS**
3. **REPORT 3 — CUA REPLACEMENT QUESTION OPTIONS**

Before EACH block, provide this exact instruction:

“COPY EVERYTHING IN THE BLOCK BELOW INTO CHATGPT.”

Use one fenced text block per report. The FIRST content in EACH block must be this exact instruction for ChatGPT:

“Create a polished, professional 8.5 × 11 PDF from the content below. Preserve all standards, question numbers, recommendations, mathematical notation, answer choices, answer keys, tables, and instructional analysis exactly. Use clear headings, readable tables, appropriate page breaks, and a professional PSD instructional-coach style. Do not add, remove, reinterpret, or change the assessment analysis.”

Then include the report label and ALL finalized content for that report inside the same block. Fill every template field with the actual verified analysis; remove authoring placeholders and template instructions. Preserve tables, mathematical notation, answer choices, answer keys, worked solutions, and scoring guidance. Keep student-facing questions separate from teacher-facing keys and commentary. Each report must repeat its grade/unit, assessment identity, review scope/counting convention, source legend S1–S5 (titles/versions and page/section locator convention), relevant evidence, and validation/limits. Do not rely on another block, prior messages, attachments, external images, or internal files to understand or typeset a report. Explicitly identify unknown source information instead of inventing it.

Report 1 must include Overall Alignment; the exact required mastery question, one YES / MOSTLY / PARTIALLY / NO judgment, and Evidence-based Explanation; Strongest Areas; Largest Gaps; Rigor Concerns; Recommendation; Standards Coverage table/content for every GaDOE standard/substandard; and Bottom Line. Retain the full source analysis, applicability limits, distributions/denominators, and validation content from the alignment template.

Report 2 must begin its report content with a summary listing Questions to KEEP and Questions to CONSIDER REPLACING, with reconciled counts. Then include every original question reviewed with its original number, standard/substandard, KEEP or CONSIDER REPLACING, and evidence-based rationale. Preserve all question-review protocol fields, source locators, subpart findings, independent solution/key/scoring checks, and assessment-level reasoning; the requested brief fields are a minimum, not a replacement for existing analysis safeguards.

Report 3 must include candidate sets ONLY for original parents marked CONSIDER REPLACING. Each set includes the original number, reason for replacement, recommended target standard, target skill/content, target DOK with rationale, suggested item type, and exactly FOUR meaningfully different candidates A–D. Each candidate includes a complete student-facing question with all choices/data/necessary visuals, correct answer/key and worked solution, standard/substandard and source locators, target skill/content, estimated Webb DOK with rationale, item type, proposed scoring, and tradeoffs. Clearly identify exactly one RECOMMENDED OPTION per set and explain why it best improves the assessment as a whole compared with the other three. If candidate targets, DOK, or formats differ, state each explicitly; do not imply the recommended profile applies to all alternatives.

Necessary visual information must survive copying the text block: include a complete, mathematically checked text diagram or data table, or an exact figure specification fully determining geometry, labels, scale, equal partitions, shading, and plotted values. Verify the mathematical representation internally and ensure ChatGPT needs only faithful typesetting, not new mathematical decisions. For a student-created diagram, provide complete construction directions and all supplied axes/data. Do not leave “insert figure” placeholders or defer analysis, answer verification, or missing data to ChatGPT.

Do not include workspace file paths or inaccessible PDF links. Do not attempt GitHub delivery, Google Drive delivery, attachment publishing, or other external delivery. Do not report a PDF-attachment failure or withhold complete report blocks because PDF generation/attachment capabilities are unavailable. Do not claim that ChatGPT has already generated or validated the final PDFs. Success means all three complete chat blocks passed the report-content and copy-readiness gate.

Deliver all three complete blocks, not previews, summaries, representative questions, or “same as Report 1” references. Do not omit content to shorten the response or replace it with file links. Plan response capacity before delivery; if a platform limit actually prevents a single response, continue the same pending delivery at whole-report boundaries, never mark missing blocks as delivered or require a new review. Each completed report must remain one independently copyable block.

## Intake and evidence rules

Read all five files, including relevant tables, diagrams, response spaces, answer keys, and rubrics. Check extracted text against page images when mathematical notation or tables are unclear. Never infer unreadable content. Identify each document's title, grade, unit where applicable, date/version if available, and page count. Give the sources stable labels S1–S5 in the order above.

Confirm the documents apply to the same grade and intended unit. Report missing, unreadable, mismatched, or outdated-looking documents and ask for only the information needed to resolve the issue. STOP if a required source is missing or unreadable; do not perform a partial review. A date alone does not prove that a document is obsolete.

Infer the grade, unit, item numbering, and current assessment structure from the documents. Ask a concise question only if a material ambiguity remains. Preserve the original numbering, including multipart items; assign stable review IDs if the source has none. State how multipart items are counted.

Every consequential alignment claim must cite a source label and page, table, section, or item locator. Distinguish printed page numbers from PDF page indices. If a document lacks pages, use its heading or another reproducible locator. Separate source requirements, reviewer judgments, and proposed changes. Mark uncertain mappings as uncertain and explain why. Do not fabricate citations, standards codes, percentages, performance levels, or item specifications.

Use each source for its own purpose:

- S1: unit content, standards, learning expectations, and instructional scope.
- S2: grade-level assessment domains, weights, and constraints actually stated in the blueprint.
- S3: performance descriptions and differences in demonstrated mathematical understanding.
- S4: BEACON purposes, reporting, formats, or specifications actually documented.
- S5: the assessment being reviewed, its directions, items, visuals, key, and scoring.

Do not treat a statewide grade-level blueprint as a mandatory percentage allocation for a unit CUA unless a source explicitly requires it. Do not treat ALDs as an automatic item-difficulty classifier or use them to set cut scores. Do not transfer BEACON rules to the CUA without evidence that they apply. Explain conflicts rather than silently merging different assessment purposes.

## Required supporting protocols and templates

Read and follow all four protocols in order before finalizing any deliverable:

1. [Source analysis protocol](references/source-analysis-protocol.md): analyze all five documents before conclusions; inventory all unit standards/substandards and source expectations; evaluate each question and the complete assessment.
2. [Question review protocol](references/question-review-protocol.md): record every required question field and justify KEEP or CONSIDER REPLACING using uploaded evidence.
3. [Replacement question protocol](references/replacement-question-protocol.md): four meaningfully different, independently verified optional questions per flagged parent question, with one assessment-level recommendation.
4. [Quality control](references/quality-control.md): reconcile evidence, coverage, decisions, answer verification, original preservation, and three-report copy-ready chat delivery.

Use these separate templates: [alignment review](assets/alignment-review-template.md), [question review](assets/question-review-template.md), and [replacement options](assets/replacement-options-template.md). The final deliverables must be three complete copy-ready chat blocks using the exact wrapper instructions above. Follow the report-content and copy-readiness gate in quality-control.md. This repository contains instructions/templates; prepare final review reports only after five NEW current-review documents are supplied and verified.

## Review workflow

0. **Complete source analysis first.** Follow source-analysis-protocol.md for all five documents before reaching conclusions. Enumerate every GaDOE standard/substandard and content/mastery expectation; extract available GMAS item-type, weighting, and DOK information, ALD Beginning/Developing/Proficient/Distinguished expectations, and relevant BEACON expectations. Identify every CUA question, its standard/content, estimated Webb DOK, and item type. Explicitly mark unavailable information.

1. **Inventory the assessment.** Record item IDs, formats, points where stated, response demands, and available key/rubric. Preserve unknown point values as unknown. Identify missing pages or visuals before judging affected items.
2. **Build an item evidence matrix.** For every item or scored subpart, record the assessed mathematics, S1 standard/learning expectation and citation, alignment judgment (aligned, partial, outside scope, or uncertain), observed reasoning demand, relevant S3 descriptor evidence, applicable S2/S4 context, accuracy/key/scoring findings, and recommendation (KEEP or CONSIDER REPLACING). Describe what students must actually do. If labeling cognitive demand, identify the framework and provide a rationale; do not equate difficulty, item format, ALD level, and reasoning demand.
3. **Check mathematical quality.** Solve each item independently when readable. Check uniqueness or permitted equivalent answers, calculations, units, diagrams, assumptions, distractors, directions, and key/rubric consistency. Flag ambiguity and underdetermined items. If no source key exists, label your solutions as a proposed key. Do not claim a key has been verified when visuals or needed information are missing.
4. **Evaluate assessment coverage.** Summarize unit expectations assessed, missing or weakly represented expectations, repeated content, reasoning opportunities, and the evidence available for the ALD distinctions. Report counts and percentages with explicit denominators; distinguish item coverage from point coverage and note unknown points. Map grade-wide blueprint domains only where applicable and explain the limits of unit-level comparisons. Do not claim that an assessment is psychometrically validated from document review.
5. **Check usability and access.** Review language load, legibility, response space, mathematical notation, context familiarity, and whether directions introduce unnecessary barriers. Preserve the intended mathematics when proposing access improvements. Treat accommodations or district formatting rules as requirements only when supplied; do not invent them.
6. **Prioritize revisions.** Address mathematical errors and invalid scoring first, then content gaps and unsupported demands, then clarity and balance. For each recommendation, name the item, evidence, proposed change, rationale, and scoring impact. Preserve effective items and explain why they should remain.
7. **Present the required mastery judgment, then automatically deliver all three complete report blocks.** Follow the teacher-facing sequence and exact copy-to-ChatGPT format above without a separate user request. Use the three `assets/` templates. Give every original question exactly KEEP or CONSIDER REPLACING in Report 2. For each flagged parent, provide exactly four optional replacement choices in Report 3, identify exactly one RECOMMENDED OPTION, and give its source-based assessment-level rationale. Never assemble these choices into a revised CUA. If no questions are flagged, retain Report 3 and state that no replacement options are needed.

## Recommendation and replacement safeguards

KEEP means the available evidence supports retaining the question. CONSIDER REPLACING means a mathematical, alignment, scoring, clarity, or other documented concern warrants teacher consideration. Explain the concern rather than implying replacement is mandatory. CONSIDER REPLACING requires a documented concern involving alignment, missing standards coverage, excessive redundancy, rigor, content accuracy, item design, or overall assessment balance. Never flag a question merely because a harder question could be written. If evidence is insufficient to decide, mark the review pending and report the blocker; do not finalize a recommendation by assuming a defect. Keep uncertainty distinct from a confirmed defect. For multipart questions, review each subpart and give the parent question one final label; provide four complete replacement choices for each flagged parent question, addressing its relevant parts.

The original CUA must remain read-only and unchanged. Do not edit, annotate, overwrite, reorder, or generate a revised copy of it. Keep all three analysis/recommendation documents separate from the original. If asked to produce a revised CUA, explain this skill's scope and provide the optional replacement document instead.

For each flagged question, label four distinct, original alternatives A–D; these are four candidate questions, not four answer choices for one multiple-choice item. Preserve the evidenced learning target unless the review identifies a source-supported scope correction. Make the options meaningfully different in approach, representation, or response demand while staying within the unit. Explain each option's alignment and tradeoffs. Identify exactly one recommended option and explain why it best addresses the original issue. Include the complete question, complete answer/key and independent solution, exact source standard/substandard, target skill/content, estimated Webb DOK with rationale, item type, and any scoring criteria for every option. Changing only numbers, names, or contexts does not create meaningfully different options. Explain how the recommended option specifically improves the overall assessment. Clearly identify these as optional teacher-facing materials, not an assembled assessment.

Do not reproduce secure or proprietary external assessment items as replacement options. Write original questions informed by documented expectations. For every option, independently solve it, verify answers and units, check all multiple-choice distractors where applicable, and review diagrams against the problem. Include complete copyable visual information or exact figure specifications as required by the copy-to-ChatGPT format; verify the representation rather than deferring mathematical decisions to ChatGPT. For constructed responses, provide explicit scoring criteria and proposed points, identifying them as proposals rather than district requirements. If unreadable source content prevents a valid replacement, report the blocker; do not fabricate four purportedly valid options or claim the document is complete.

## Final quality gate

Execute every check in `references/quality-control.md`. Final completion requires all five sources available and readable; every GaDOE standard/substandard considered; no invented standards or assumed missing information; all five sources analyzed before conclusions; all existing items were accounted for; every substantive source claim has a locator; math and scoring were checked; coverage denominators are consistent; recommendations connect to evidence; and every flagged question has exactly four checked replacement options with exactly one recommendation and rationale. Report what was checked, what remains uncertain, and whether any issue or optional replacement requires teacher review before use. Document review supports professional judgment; it does not establish reliability, predictive validity, GMAS equivalence, or student achievement levels.

Be practical, specific, and respectful of the teacher's existing work. Lead with the most consequential findings. Never claim district approval or expand the acronym PSD without supplied evidence.
