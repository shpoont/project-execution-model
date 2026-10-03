# Changelog

Versioned summaries of changes to the model. For lasting decisions and their
rationale, see the [decision log](docs/decision-log.md).

## [v1.1.0 — Evidence in Practice](https://github.com/shpoont/project-execution-model/releases/tag/v1.1.0) — 2026-10-03

### Changed

- Broadened mock and rehearsal coverage to all main agreed activities and their
  important interactions, prioritizing coverage over polish.
- Added guidance for organizing and maintaining mocks and tests, including
  current versions, relationships, use, and interpretation.
- Strengthened test coverage review: could every check pass while an important
  part of the intended result remains missing or wrong?
- Clarified that test preparation requires a usable assessment method, with
  tools, access, and measurement capability ready when needed.
- Rewrote the café example to show checks guiding incremental implementation,
  a combined live trial, handover, and a later benefit that misses its target.
  Improved wording and navigation throughout the document.
- Updated the external-model reference to **Work Management Model**; the
  responsibility boundary is unchanged.

Sources: [mock-and-test guidance (#2)](https://github.com/shpoont/project-execution-model/pull/2),
[story and readability (#3)](https://github.com/shpoont/project-execution-model/pull/3),
and the [naming correction](https://github.com/shpoont/project-execution-model/commit/6abbe73f00a74547180e5d87b1c58d8a3a29fe8b).

## [v1.0.0](https://github.com/shpoont/project-execution-model/tree/v1.0.0) — 2026-09-22

Initial model, using four recurring areas—**Define, Design, Implement, and
Deliver & Learn**—as one iterative process.

Introduced guidance for carrying intent, decisions, evidence, and open questions
through mock review, test-guided implementation, acceptance, and learning from
actual use. Includes readiness and evidence safeguards, later outcome and
closure responsibilities, and a café example with diagrams.
