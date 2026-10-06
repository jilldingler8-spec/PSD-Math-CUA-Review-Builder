# Quality-control gate

Run this gate before finalizing. Record passed, blocked, and not-applicable checks honestly; resolve failures before claiming completion.

## New Review Session Isolation

Check session isolation BEFORE source analysis, not only at finalization:

- Every fresh chat/new-review request established a new session boundary and empty checklist, source bindings, grade/unit metadata, extracted content, analysis, and output references.
- The initial response requested ONLY the GaDOE Math Unit with the exact Step 1 wording and displayed the empty five-source checklist; no previous-session source was marked received.
- Each S1–S5 source has a NEW upload event/reference explicitly supplied by the user after this review's boundary and recorded with its current session identifier, source type, downloaded path where applicable, and successful verification status.
- No source was accepted merely because it existed in a repository, workspace, environment snapshot, prior chat, test-output directory, cache, or previous review folder. Previous upload IDs and prior review content were never copied into the current session.
- All five NEW current-session documents passed intake before assessment analysis, mastery judgment, or report preparation. Wrong/unreadable files did not advance intake; conflicts stopped it. Missing/uncertain provenance requires a new upload, never an assumption.
- Each review uses a separate output location. Production bundles/snapshots exclude test inputs, generated test reports, and cached test analysis. Templates/protocols remain available but contain no accepted current-review sources.
- Existing read-only CUA protections and all analysis/verification requirements remain unchanged. Do not edit an active original to enforce isolation.

## Evidence and completeness

- All five required source documents were available and readable, including needed math, tables, and figures; grade/unit compatibility was checked.
- All five were analyzed before conclusions were reached.
- Every GaDOE Unit standard and substandard was considered in the coverage ledger, including unassessed entries.
- Every original CUA question/subpart was reviewed and reconciled with source numbering.
- No standards, source specifications, weights, or expectations were invented; missing information was not filled from assumptions.
- Substantive recommendations have uploaded-source locators and distinguish source requirements from reviewer estimates/judgments.
- Question-level findings and whole-assessment conclusions agree; counts, point totals, denominators, overlapping mappings, DOK, and item types are consistent.
- Each finalized question has exactly KEEP or CONSIDER REPLACING; flags have documented concerns rather than a preference for harder questions.

## Replacement integrity

- Each flagged parent question has exactly four meaningfully different options, each with all required fields, and exactly one recommendation with a whole-assessment improvement rationale.
- Options address actual identified gaps or concerns, not hypothetical weaknesses.
- Answer keys were independently verified; math, unique/allowed answers, units, distractors, scoring, grade appropriateness, alignment, clarity, and DOK were checked.
- Necessary figures are mathematically verified and completely represented inside the copy-ready block by checked text diagrams/data tables or exact specifications; copying the block loses no essential data, labels, scales, partitions, shading, or values. Student-created figures have complete construction directions. No unresolved placeholders or deferred mathematical decisions are passed off as complete questions.

## Original preservation

Treat the original CUA as read-only throughout. If a local file is available, record a SHA-256 hash before analysis and compare it after report generation; do not modify permissions or file contents merely to establish read-only handling. For externally hosted originals, use read-only operations and report that integrity verification is limited to those operations. Verify the original remains completely unchanged. Any internal analysis or quality-control files must be separate from the source; the final deliverables are chat report blocks, not source annotations or edits. No revised CUA was created, including an assembled set of recommended replacements.

## Teacher-facing sequence check

- Intake began empty for every new review and requested five NEW current-session uploads one at a time; only already verified uploads from that same review avoided duplicate requests. Grade/unit were inferred only from current-session documents when reliable.
- All five source types were verified before analysis, and the exact readiness message in SKILL.md was delivered.
- The required mastery question was answered with YES, MOSTLY, PARTIALLY, or NO and a concise cited explanation before delivery of the report blocks.
- All three complete report blocks were delivered automatically without separate requests or approval steps, and Report 1 repeats the judgment and rationale.

## Report-content and copy-readiness gate

Final deliverables are THREE complete, self-contained chat blocks using the `assets/` templates:

1. **REPORT 1 — CUA ASSESSMENT ALIGNMENT REVIEW**
2. **REPORT 2 — CUA QUESTION REVIEW & RECOMMENDATIONS**
3. **REPORT 3 — CUA REPLACEMENT QUESTION OPTIONS**

Before EACH block, verify this exact instruction appears:

“COPY EVERYTHING IN THE BLOCK BELOW INTO CHATGPT.”

The FIRST content inside EACH fenced text block must be this exact instruction:

“Create a polished, professional 8.5 × 11 PDF from the content below. Preserve all standards, question numbers, recommendations, mathematical notation, answer choices, answer keys, tables, and instructional analysis exactly. Use clear headings, readable tables, appropriate page breaks, and a professional PSD instructional-coach style. Do not add, remove, reinterpret, or change the assessment analysis.”

Check each block as if it alone were copied into a fresh regular ChatGPT conversation:

- The label, grade/unit, assessment identity, scope/counting convention, source legend S1–S5 with titles/versions and locator convention, and relevant validation/limits are present inside that block. Unknown fields remain explicitly unknown. No needed information is located only outside the block or in another report.
- Every substantive source claim has a locator. Source summaries, applicability limits, mathematical notation, tables, question numbers, response requirements, answer choices, keys, worked solutions, and proposed scoring agree with the verified analysis inventory.
- Report 1 contains Overall Alignment; the exact required question; exactly one YES / MOSTLY / PARTIALLY / NO judgment; Evidence-based Explanation; Strongest Areas; Largest Gaps; Rigor Concerns; Recommendation; Standards Coverage for every standard/substandard including unassessed entries; Bottom Line; full source analysis, distributions/denominators, and validation.
- Report 2 begins its report content with lists of Questions to KEEP and Questions to CONSIDER REPLACING and reconciled counts. Every original question/subpart is accounted for with original numbering, actual standard/substandard, final decision, and cited rationale. All additional question-review protocol fields and solution/key/scoring findings remain complete.
- Report 3 has candidate sets only for the flagged parents from Report 2. Each set includes the original number, reason, recommended target standard, target skill/content, target DOK and rationale, and suggested item type. Exactly four complete, meaningfully different candidates A–D are included per parent, each with all student directions/data/choices/visual information, verified answer/key/solution, standard and source locator, target skill, estimated DOK/rationale, format, proposed scoring, and tradeoffs. Exactly one is clearly marked RECOMMENDED OPTION with a whole-assessment rationale and comparison with the other three. When none are flagged, the third block still provides its scope/source legend and states that no replacements are needed.
- Figures, tables, labels, units, axes, scales, equal partitions, shading, and plotted values are fully determined in copyable text. Inspect any internally rendered figures used for verification, but do not rely on image attachments surviving the copy. No “insert diagram,” missing choices, authoring placeholders, or unstated geometric assumptions remain. Faithful ChatGPT typesetting must not require new analysis or mathematical choices.
- Each report is ONE independently copyable fenced text block with balanced delimiters and no internal fence that splits it. No required text is truncated, abbreviated to “same as above,” replaced by a file/link, or left to another report. Complete all three; if an actual platform limit requires continuation, preserve whole-report boundaries and track pending blocks without claiming full delivery prematurely.
- No workspace paths, inaccessible PDF links, downloadable-attachment claims, or attachment-failure fallback statements appear in the deliverable. No GitHub, Google Drive, attachment publishing, or other external delivery is attempted.

Completion depends on verified analysis and all three complete copy-ready chat blocks. Codex PDF generation, PDF rendering/inspection, and downloadable attachment delivery are NOT required. Internal files may support analysis or quality control; they never replace the chat blocks. Do not withhold finalized reports because PDF tooling is absent, and do not claim that regular ChatGPT has already generated or validated the final PDFs.

Missing/unreadable required source evidence still triggers the existing STOP rules; no delivery-format change permits fabricated or partial analysis. These checks do not establish psychometric validity or district approval.
