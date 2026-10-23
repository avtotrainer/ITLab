# Technical Diagnostics
Version 1.0 | 2026-10-23

## Intake
Capture goal, symptoms, observed error verbatim, environment versions, hardware/software identity, privileges, current topology, last working state and recent changes. Remove secrets before publication. Classify evaluation/build/activation/boot/runtime/data/UI/workflow/connectivity.

## Hypothesis loop
Prefer read-only checks. Show one testable hypothesis and its expected output; evaluate the result before mutation. Separate local symptoms from domain/tenant policy, network addressing from routing, application state from data state, and GUI failure from backend completion. Document rejected hypotheses as FAILED only when actually tested.

## Platform-specific boundaries
- NixOS: distinguish evaluation, build, activation, reboot and declarative persistence; avoid treating successful build as successful activation.
- Windows: distinguish local device drivers, Group Policy, domain join, Entra/Intune device management and user account profile state.
- Networking: record interface, IP/prefix, route, gateway, DNS, VLAN, radio association, reachability and firewall evidence.
- Printing: distinguish network discovery, IP transport, printer protocol, driver/filter, queue and physical device behavior.
- Google Workspace: distinguish account roles, organizational unit path, API authorization, Apps Script execution and user interface state.
- Development: distinguish dependency install, build, execution, tests, API integration and persistent data.

## Resolution and handoff
Before any risky change, state backup/rollback and blast radius. Require an observable success check and version-scoped conclusion. If no success evidence is available, label result unverified. For transferability, create a Georgian handout with successful and unsuccessful steps, reset/recovery and exact commands. Close by linking the canonical document and recording relevant future test conditions.
