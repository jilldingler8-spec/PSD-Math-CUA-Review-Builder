# PSD Math CUA Review & Revision Builder

A reusable Codex skill for PSD teachers and instructional coaches reviewing an existing math Common Unit Assessment against five uploaded source documents. The original CUA remains read-only and unchanged. The skill never creates a revised CUA.

## Install

Copy `skills/psd-math-cua-review-revision-builder` into your Codex skills directory (typically `$CODEX_HOME/skills` or `~/.codex/skills`). Keep `SKILL.md`, `references/`, and `assets/` together. Restart Codex if needed to discover the skill. This repository contains the skill; it has not been installed into a personal skills directory automatically.

## How to Use This Skill

Invoke **PSD Math CUA Review & Revision Builder** in Codex (for example, “Use $psd-math-cua-review-revision-builder”). The skill guides you through these uploads **one at a time**, waiting for each before asking for the next:

1. “Let's get started. Please upload the GaDOE Math Unit you want this CUA reviewed against.”
2. “Next, please upload the Grade-Level GMAS Math Blueprint.”
3. “Next, please upload the Grade-Level Mathematics Achievement Level Descriptors (ALDs).”
4. “Next, please upload the DRC BEACON Math Document.”
5. “Finally, please upload the current PSD Unit CUA that you want reviewed.”

After each upload, the skill checks the document, briefly confirms receipt, and marks it received on a checklist. You do not need to upload all five in one message. If a file is wrong or unreadable, it asks for the correct/readable document and waits at that step. If grade or unit information conflicts, it stops and explains the conflict before analysis.

The skill identifies grade and unit from your documents, asking only when necessary. Every new review starts with an empty checklist and requires five new uploads, even when you have used the same files before. Files from prior reviews, chats, test folders, or the workspace are never reused as inputs. Only uploads supplied for the current review count. No assessment analysis begins until all five documents are received and verified. Your original CUA stays read-only and unchanged throughout.

When all five are ready, you see:

```text
All five required documents are ready for review.

✓ GaDOE Math Unit
✓ GMAS Math Blueprint
✓ Achievement Level Descriptors
✓ DRC BEACON Math Document
✓ Current PSD Unit CUA

The original CUA will remain unchanged. I will now analyze it against the four supporting documents.
```

It then analyzes the full CUA and answers the required mastery question with **YES, MOSTLY, PARTIALLY, or NO**, supported by uploaded-source evidence. It automatically provides THREE complete, self-contained, copy-ready report blocks in chat; no separate report requests or PDF-download capability are needed.

**UPLOAD AND VERIFY ONE DOCUMENT AT A TIME → ANALYZE → ANSWER REQUIRED QUESTION → DELIVER THREE COPY-READY REPORT BLOCKS**

The official outputs are:

1. **REPORT 1 — CUA ASSESSMENT ALIGNMENT REVIEW** — Overall Alignment; the required question and judgment; Evidence-based Explanation; Strongest Areas; Largest Gaps; Rigor Concerns; Recommendation; complete Standards Coverage; Bottom Line; source analysis and validation.
2. **REPORT 2 — CUA QUESTION REVIEW & RECOMMENDATIONS** — begins with Questions to KEEP and Questions to CONSIDER REPLACING; covers every original question with its number, standard/substandard, decision, evidence-based rationale, and full question-review findings.
3. **REPORT 3 — CUA REPLACEMENT QUESTION OPTIONS** — only flagged parents; four meaningfully different complete candidate questions per parent, all choices, verified keys/solutions, standards, target skills, estimated DOK, formats, and proposed scoring; exactly one RECOMMENDED OPTION per set with an assessment-level explanation. If no questions are flagged, the third block states that no replacements are needed.

## Copy each report into regular ChatGPT

Before each report, Codex displays:

“COPY EVERYTHING IN THE BLOCK BELOW INTO CHATGPT.”

Each report is presented in ONE fenced text block. Its first content is this exact instruction:

“Create a polished, professional 8.5 × 11 PDF from the content below. Preserve all standards, question numbers, recommendations, mathematical notation, answer choices, answer keys, tables, and instructional analysis exactly. Use clear headings, readable tables, appropriate page breaks, and a professional PSD instructional-coach style. Do not add, remove, reinterpret, or change the assessment analysis.”

Copy the entire block for ONE report into regular ChatGPT. That block includes the instruction, report title, full analysis, source legend/locators, all necessary mathematical content, and validation/limits. No explanation, other report, prior chat, attachment, or workspace file is needed. Repeat for the other two reports. ChatGPT creates the final PDFs; Codex does not claim to have generated or inspected those downstream PDFs.

Codex may use internal files for analysis or quality control, but the official deliverable is the three complete chat blocks. It does not provide workspace paths or inaccessible PDF links and does not attempt GitHub, Google Drive, or other external delivery. PDF generation, rendering, and downloadable attachment availability are not completion prerequisites.

The skill still checks mathematical correctness, scoring, reasoning demands, usability, and source grounding. Grade-wide blueprint weights, ALDs, and BEACON specifications retain their documented contexts and are not assumed to be mandatory unit-assessment rules. Replacement options remain separate teacher-facing recommendations and are never assembled into a revised assessment.

No publishing credentials or PDF-generation dependencies are required for chat delivery. Source-document reading capabilities must still support the needed mathematics, tables, and figures. A real five-document review is needed to validate end-to-end behavior.

The four protocols preserve five NEW uploads per review, one-at-a-time intake, session isolation, complete five-source analysis, every-standard and every-question coverage, evidence-based KEEP / CONSIDER REPLACING decisions, exactly four options with one recommendation, independent mathematical verification, and original-file preservation. The three templates live in `assets/`. Missing necessary source evidence still blocks finalized analysis; unavailable PDF/download tooling does not. Repository publication distributes the Skill and templates only; assessment source documents and generated review reports are excluded.
