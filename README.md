# Project 2 - Equilibrium Tutor
Prepared for Aditya Raj | Basic Engineering Mechanics | 12 November 2026

## What this project delivers
One ordinary-chat teaching agent with the five required instruction files, source-traceable practice inputs, independent mechanics work, coordinate SVG FBDs, executed local checks, test-record templates and a report. No API or paid API access is needed.

## Use the agent
1. Open a fresh ordinary LLM chat.
2. Attach ALL five files in agent/: SKILL.md, input-schema.md, mechanics-rules.md, output-rules.md and verification.md. If attachments are unsupported, paste each complete file with its filename.
3. Paste: "Follow these five files as one Equilibrium Tutor. Confirm each file you can access. Use Hint mode for the attached original tutorial problem. Do not reveal final reactions."
4. Attach the original problem only. Do not attach reference/, verification results, or report answer sections in the first run.
5. Make your own numbered attempt, then ask for Audit or explicitly request Solve. Export the unedited conversation.

## Honest completion status
The implementation and authored practice checks are supplied. The lecturer's tutorial sheet is absent. PRACTICE-* labels are local examples, NOT invented tutorial IDs or approved replacements. Lecturer approval, actual tutorial IDs, student attempts, ordinary-chat Hint-to-Solve/Audit transcripts, two genuinely unseen final tests and the three-chat difficult-case repeat are pending. Do not describe this package as fully verified on the lecturer's sheet. Any automated evaluations recorded here are development evidence only.

## Files
- agent/: exactly five instruction files for one agent.
- practice/: eight authored inputs; D1-D4 are development mechanics examples, X1-X4 are supplementary boundaries/mode examples.
- reference/: independent hand calculations, not first-run inputs.
- diagrams/: coordinate-based equivalent FBDs for D1-D4.
- verification/: executable Python arithmetic checks and actual outputs.
- records/: selection sheet, raw-run template, design log, file hashes and any explicitly labelled automated outputs.
- Project_2_Report.pdf: readable project report and pending-submission checklist.

## Reproduce arithmetic checks
Python 3 standard library is sufficient:
`python verification/check_practice.py`
This recalculates practice reactions from a second moment origin and checks load integrals, ranks, contact feasibility and a signed distribution. It is not an LLM, and it does not test Hint/Audit behaviour.

## Submission steps still required
Obtain the lecturer-approved tutorial selection; preserve original IDs; prepare independent work before testing; run four development cases with raw exports; document real revisions; freeze agent files; run two unseen final cases; repeat one difficult case in three fresh chats; complete the rubric. Do not expose held-back questions or keys to the agent author before the final test.

## AI-use declaration
ChatGPT generated the five instruction files, authored practice examples, supporting calculations/code, diagrams and report. Local Python was used for arithmetic checks and PDF/SVG creation. Any agent-based development tests are labelled by their actual execution context. No lecturer tutorial evidence, learner attempt or approval has been fabricated. The student must understand and be able to modify and explain the work.

## Source
Mechanics_Agent_Project_Briefs.pdf supplied by the user: common specification pp. 1-2, Project 2 pp. 5-6, testing p. 19, submission/assessment p. 20. No external reference was consulted for this build. The original brief lists further mechanics references if needed.
