# Changelog

Versioned summaries of changes to the model. For lasting decisions and their
rationale, see the [decision log](docs/decision-log.md).

## [v1.2.0 — Six Steps, One Process](https://github.com/shpoont/project-execution-model/releases/tag/v1.2.0) — 2026-10-28

### Changed

- Made **Mock** and **Prepare Tests** distinct recurring steps alongside
  **Define, Design, Implement, and Deliver**. Planning, review and testing
  continue throughout one iterative process; findings can reopen affected work.
- Made architecture, responsibilities, ownership, interfaces and interactions
  explicit in Design. Substantial subsystems can apply the full cycle within
  their scope, inheriting parent context and returning real results and checks;
  the parent still verifies the combined outcome.
- Connected recursive mock and check coverage to every designed element's
  responsibilities and constraints. Explained the four relationships between
  mocks and tests, their evidence limits, and useful retained substitutes.
- Clarified that the implementation contract covers all agreed expectations,
  conditions and assessment, including obligations an omitted test does not
  remove. Prepare checks before the behavior they guide while scenarios and
  checks develop incrementally.
- Added assessment validation against acceptable results and plausible
  violations, coverage review for omissions, and explicit handling of
  assessment failures and insufficient evidence.
- Strengthened connected use, diagnosis, maintenance and extension of design,
  mocks, checks and evidence across contributors, including a representative
  practical-usability assessment with proportionate effort and evidence reuse.
- Reorganized the café example and references for the six steps. Added a
  pointed pyramid overview with step names inside its layers, editable source,
  and consistent placement of café images before their matching examples.

Retained readiness and authority safeguards, real combined-result verification,
and separate acceptance, benefit, constraint and closure responsibilities.
The reviews and walkthroughs do not establish improved outcomes in real projects.

Sources: [six-step revision (#6)](https://github.com/shpoont/project-execution-model/pull/6)
and [requirements (#4)](https://github.com/shpoont/project-execution-model/issues/4).

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
