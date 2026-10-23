# Documentation Standard
Version 1.0 | 2026-10-23 | Owner: Knowledge stewardship

## Mandatory metadata
Each reusable Markdown handout begins with Title, Purpose, Category, Audience, Language, Status (proposed/verified/stale), Version, Last verified (date or unknown), Environment, Visibility, Canonical path, and Related references. Georgian text remains Georgian; knowledge-register field names stay English. Metadata describing a historical guide may state that tests were run in the past without claiming they were rerun today.

## Technical handout sections
1. Problem and expected result.
2. Tested environment, device/software versions, prerequisites and access privileges.
3. Initial symptoms, relevant logs and exact errors.
4. Diagnostic decisions and checks in chronological order.
5. Failed attempts and identified reasons; mark unconfirmed causes as hypotheses.
6. Successful performed configuration and actual outputs.
7. Relevant alternatives, including when they are preferable.
8. Exact file paths and commands in correctly labeled code blocks.
9. Risk, data exposure, backup, reset, recovery and rollback.
10. Expected result, one reproducible verification check, residual limitations and revalidation trigger.

Distinguish OBSERVED, VERIFIED, FAILED, PROPOSED and UNKNOWN, especially where the original session did not record outcomes. Do not invent successful tests. Include a concise practical quick-start only after capturing evidence. Do not publish secrets or student-identifying data.

## Review gates
Confirm file content, commands, platform and version context; ensure the full history is represented; check language and links; check public-safety classification; check Markdown headings and filenames; verify the stated destination after writing. An editorial review alone never upgrades technical status to VERIFIED. Maintainers sign off on publication and record the verification date when an actual check occurred.

## Runbooks
For operational runbooks also add impact, preflight/approval, step order, stop conditions, validation, rollback, recovery and owner. Use one command block per coherent procedure, with explanatory expected output. Avoid unsafe commands without bounded targets.
