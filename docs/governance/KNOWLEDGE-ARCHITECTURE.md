# Knowledge Architecture
Version 1.0 | 2026-10-23

## Roles of systems
GitHub Markdown is the canonical version-controlled knowledge source. Google Docs is a collaboration and reader-friendly representation that can develop independent edits. Slack captures discussions and decisions; messenger platforms deliver audience-specific communication; social media points to approved public resources. None of these transient channels becomes canonical through usage alone.

## Object lifecycle
Intake (question, incident, experiment) → diagnosis with evidence → verified implementation or clearly labeled proposal → Georgian technical handout or English internal reference → review for security and completeness → GitHub canonical publication → optional Docs mirror → knowledge register → periodic revalidation or archival.

Every object needs one canonical path and a stable title. Categories follow real topics, not empty directory scaffolding. Preserve historical evidence and failed attempts. Link related objects in both directions when useful.

## Register contract
At docs/knowledge/KNOWLEDGE-REGISTER.md maintain Title, Category, Canonical path, Google Docs URL, Language, Version, Last verified, Visibility, Sync status, Related resources. Use 'none' for absent Docs representation, 'unknown' for unverified dates/conditions. Allowed sync statuses: canonical-only, in-sync, docs-ahead, repo-ahead, conflict, unknown.

## Synchronization protocol
1. Fetch current canonical file and Google Doc; record revisions and last edit.
2. Compare content and independently authored changes, not only file dates.
3. If conflicts exist, label conflict and request reconciliation; never silently overwrite.
4. Update one version only after defining the direction and approving risky rewrites.
5. Read back both content and location; label in-sync only when substantive parity is checked.
6. Update register, reciprocal links and last sync note.
Google Drive does not automatically supply files to ChatGPT Project Knowledge. Keep operational secrets out of public artifacts.
