# Security Policy
Version 1.0 | 2026-10-23 | Applies to public repo, Drive, Slack, scripts and outreach.

## Data and access classification
PUBLIC: independently safe references and redacted examples. COMMUNITY: membership-level discussion without private infrastructure. INTERNAL: operational details requiring controlled access. RESTRICTED: credentials, student records, personal contacts and critical systems. Default to restricted when uncertain. Public GitHub accepts PUBLIC material only.

## Controls
Use least privilege; do not paste secrets/tokens/passwords, private keys, live admin commands embedding credentials, student names, identifiable student images, private hostnames/topologies or network records into public documentation. Sanitize screenshots and logs. Use placeholders in code and keep actual secrets in access-controlled tools; never publish them for reproducibility. Treat third-party connectors and automation as authorization boundaries.

## Approval gates
Obtain explicit authorization before publication, creating accounts, invitations, bulk communication, permission changes, channel/file deletion, paid advertising or spend, billing changes and destructive system actions. Confirm target workspace or tenancy before changes. Safeguard current GitHub/Docs revisions and preserve original resources.

## Incident handling
Stop unsafe disclosure, restrict affected access with authorized administrators, preserve evidence privately, rotate compromised credentials through official mechanisms, and document remediation without reproducing secrets. Do not disclose student/teacher private data through cross-platform sync. Recheck share permissions after a move/copy if the platform may inherit access.

## Verification
Before releasing: review identifiers, links, screenshots, shell history, configuration, metadata and comments for sensitive data. After external writes, verify destination and access classification where the connector exposes it. An unknown visibility status is not proof of privacy.
