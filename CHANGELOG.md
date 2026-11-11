# Changelog

Versioned summaries of model and repository changes. For lasting decisions and their
rationale, see the [decision log](docs/decision-log.md).

## [v2.0.0 — Published Deliverables and Project Structure](https://github.com/shpoont/project-execution-model/releases/tag/v2.0.0) — 2026-11-11

### Changed

- Moved the canonical model to `deliverables/project-execution-model.md` and
  its five PNG illustrations to `deliverables/assets/`. Added a published-results
  page with tagged models, release notes and earlier versions.
- Moved the editable overview HTML to `src/diagrams/`. Retained one maintained
  source for the model and each image; the model is editable Markdown as delivered.
- Adopted Project Structure v1.1.0 for maintaining this repository. Added a
  project agreement and connected contributor, repository, check, evidence and
  delivery guides. Active agreements remain in GitHub issues and pull requests.
- Updated current links and release references. Kept a forwarding document at
  the old model path, including its section routes, and left earlier tags fixed.

This major version changes published file paths. Update raw-model, direct image
or diagram-source URLs that follow a moving branch. Existing pinned releases
remain unchanged. The model body and rules are unchanged apart from its release
line; image bytes, placement, author, initial release date and legal text are
preserved. Repository guidance adds no requirements for projects using PEM.

The [adoption record](evidence/project-structure-adoption.md) reports the checks
and their limits. Source preservation and simulated reader tasks support
documentary readiness, not actual adoption or improved project outcomes.

Source: [repository adoption (#31)](https://github.com/shpoont/project-execution-model/issues/31).

## [v1.3.2 — Clearer Explanations and Examples](https://github.com/shpoont/project-execution-model/releases/tag/v1.3.2) — 2026-11-11

### Changed

- Added a compact shelf story across all six steps. Show sufficient
  preparation for a small change, reuse of existing information and ordinary
  notes, checks of the real result, and a separate check of the benefit in use.
- Reworked the journey and Main Concepts as connected explanations, with
  short introductions and expandable Working Guidance. Improved navigation
  for early decisions, preparation, coordination, checks, handover and closure.
- Clarified how the six steps build on one another without requiring each
  to finish before another starts. Retained readiness judgment for each
  consequential action and connected changed demands to decision authority.
- Consolidated intended-use checks in the implementation contract. Clarified
  test timing, present measurement capability for later checks, valid failure
  versus indeterminate assessment, and what repeated observations can establish.
- Made reuse and stopping conditions clearer without reducing whole-system
  or designed-part coverage. Kept operational planning mechanics outside PEM.
- Kept the café opening with Define and labelled its images, numbers and
  operating limits as illustrative. Added starting observations, a packing
  backlog clock that further enquiries do not reset, quoted-time limits and
  their response. Carried those limits into the trial and handover; distinguished
  an observed improvement from causal proof and qualified the dashboard evidence.

This patch explains and illustrates existing guidance. Retained the six
recurring steps, five Main Concepts, mocks-first and tests-first direction,
justified bounded trials, coverage, evidence and authority safeguards, real
combined verification, later outcome ownership and closure. Added no stage,
required document or general operating threshold. The figures, initial release
date and earlier version tags are unchanged.

Comparative Pro reviews, editorial cycles, independent complete-source
preservation checks and hypothetical applications found no required correction
within their reviewed scopes. The final small wording changes received a
separate preservation check and targeted Pro verification. The user read and
approved the final model. These checks support documentary readiness, not
measured unfamiliar-human usability, reduced effort or real-project
effectiveness. The document remains a substantial reference; hosted rendering
and assistive-technology behavior remain unverified.

Sources: [small worked example (#29)](https://github.com/shpoont/project-execution-model/pull/29),
addressing [issue #28](https://github.com/shpoont/project-execution-model/issues/28),
and [readability revision (#32)](https://github.com/shpoont/project-execution-model/pull/32),
addressing the model-document part of
[issue #30](https://github.com/shpoont/project-execution-model/issues/30).
The separate editorial-cycle skill work and practical validation are not
claimed by this release.

## [v1.3.1 — Guidance for Intended Use](https://github.com/shpoont/project-execution-model/releases/tag/v1.3.1) — 2026-11-06

### Changed

- Clarified how to identify guidance for the delivered result's intended
  users and participants, including operators, maintainers, AI agents and
  connected systems where relevant. Match its form to actual tasks and
  conditions: cues, assistance or training, operating references or interface
  information. Reuse suitable guidance without assuming manual reading or
  requiring a separate document per role.
- Added representative usage checks with the support and prerequisites
  participants will actually have, including unbriefed use where expected.
  Keep applicable guidance consistent with the real result and verify it
  through the agreed checks.
- Made guidance upkeep and superseded instructions explicit at handover.
  Distinguished customer directions from the staff reference in the café
  example and added a direct handover lookup link to Deliver.

This patch clarifies existing documentation, intended-use and handover
responsibilities. Retained the six recurring steps, five Main Concepts,
mocks-first and tests-first direction, bounded-trial policy, evidence and
readiness safeguards, later outcome ownership and Work Management Model
boundary. Added no stage, mandatory manual or general documentation standard.

Comparative Pro review, the seven-step editorial cycle, independent full-model
preservation and hypothetical applications found no required correction within
the increment. Pro covered the substantive pre-editorial draft; final
preservation and blind comprehension cover the subsequent navigation link.
These checks support documentary readiness, not measured human comprehension,
participant performance, interoperability or improved project outcomes.
Hosted rendering and assistive-technology use remain unverified. Broader
inherited pacing, wording and illustration preferences remain follow-ups.

Source: [guidance for users and participants (#27)](https://github.com/shpoont/project-execution-model/pull/27),
addressing [issue #26](https://github.com/shpoont/project-execution-model/issues/26).

## [v1.3.0 — Proportionate Real Trials](https://github.com/shpoont/project-execution-model/releases/tag/v1.3.0) — 2026-11-06

### Changed

- Added a justified bounded real-trial route for a particular material question
  when preparing or reviewing a credible mock would require disproportionate
  effort for the evidence it could add. Compare suitable options, including
  simpler or reused mocks, against the trial's evidence, effort, delay,
  consequences and uncertainty. Cost alone is insufficient.
- Made the trial's question, prepared assessment, limits, authorization and
  stopping conditions explicit. Keep risks and commitments within project
  obligations and authority; reconsider the next commitment if neither route
  is acceptable.
- Carry reviewed findings and uncertainty into design, test preparation and
  the next commitment decision. Other significant review obligations remain.
  Aligned the related references and added a short linked README qualification.

This minor release resolves the real-trial question left open in v1.2.2–v1.2.4.
Those historical entries describe their releases' guidance. Retained mocks-first,
the existing route for questions mocks cannot credibly answer, the six recurring
steps, five Main Concepts and all other safeguards. The café example, figures
and Work Management Model boundary are unchanged. Added no stage, required
document, template, tool or operational planning method.

Comparative Pro review, the seven-step editorial cycle, independent preservation
across eleven areas and fresh blind applications found no required correction.
They support documentary readiness, not measured human comprehension, reliable
cost or risk estimates, safer real trials or improved project outcomes.

Pro reviewed the pre-editorial draft; independent preservation and comprehension
cover the final two qualifiers. Its temporary chat remained personalized, so
strict blindness is unverified. The software and venue case comparisons depend
on replacing an otherwise-needed credible mock review; the final music-school
case exercises the existing experiment route. Hosted rendering and
assistive-technology use remain unverified.

Source: [bounded real trials (#25)](https://github.com/shpoont/project-execution-model/pull/25),
addressing [issue #22](https://github.com/shpoont/project-execution-model/issues/22).

## [v1.2.4 — Purpose and First Steps](https://github.com/shpoont/project-execution-model/releases/tag/v1.2.4) — 2026-11-06

### Changed

- Refocused the Goal on turning a need into a working result and learning
  whether it produces the intended benefit. Explain the execution journey
  first, then how contributors carry relevant reasoning between steps.
- Added a short, plain-language README summary of the six recurring steps,
  their connections and how to begin. Keep the full model authoritative and
  the README as the single maintained summary.
- Connected the overview to detailed guidance for readiness, evidence limits,
  incremental real implementation, acceptance and later benefit assessment.

This is an editorial patch release. Retained the six recurring steps, five Main
Concepts, existing safeguards, café example, images and Work Management Model
boundary. Added no stage, required document, tool or operating rule. The broader
real-trial policy question remains unresolved and deferred in
[#22](https://github.com/shpoont/project-execution-model/issues/22).

Comparative Pro reviews, seven-step editorial cycles, independent meaning
preservation and blind simulated applications support documentary readiness.
They do not establish measured human-reader usability or improved project
outcomes. Hosted rendering and assistive-technology use remain unverified.

Sources: [Goal opening (#23)](https://github.com/shpoont/project-execution-model/pull/23),
addressing [issue #20](https://github.com/shpoont/project-execution-model/issues/20),
and [README summary (#24)](https://github.com/shpoont/project-execution-model/pull/24),
addressing [issue #21](https://github.com/shpoont/project-execution-model/issues/21).

## [v1.2.3 — Journey and Working Reference](https://github.com/shpoont/project-execution-model/releases/tag/v1.2.3) — 2026-11-01

### Changed

- Separated the learning journey and café example from complete working
  guidance in one canonical document. Retained qualified summaries and direct
  links where the full rules apply.
- Moved full mock coverage and review guidance beside progressive replacement,
  and the full implementation agreement and scenario guidance beside test
  development. Added a task index, including monitoring and later benefit
  assessment.
- Introduced Design terms through concrete meanings. Retired the unused
  labels "child elements" and "decomposition" while preserving nested parts
  and their responsibilities. Clarified mock stopping, hierarchical check
  coverage and the value of further evidence for an investment decision.
- Gave the café agreement for the whole increment its own illustrative
  heading before selecting the next scenario. Retargeted checklist links,
  placed the handover note beside use and maintenance, and moved guidance
  for work after closure below the complete Deliver vignette.

Retained the six recurring steps, five Main Concepts, all substantive safeguards,
café facts and images, and the Work Management Model boundary. Added no stage,
required document, template, tool or operating method. The existing provision
for bounded real experiments is unchanged. The question of using a real trial
when a credible mock is disproportionately costly remains unresolved.

The journey is shorter while the complete document and reference are longer.
Comparative Pro reviews, the seven-step editorial cycle and simulated cases
found no required correction within the reviewed scope. They do not establish
measured human comprehension, reduced effort or real-project effectiveness;
hosted rendering and assistive-technology use remain unverified.

Sources: [readability and navigation (#19)](https://github.com/shpoont/project-execution-model/pull/19),
addressing [issue #18](https://github.com/shpoont/project-execution-model/issues/18).

## [v1.2.2 — Evidence for the Next Commitment](https://github.com/shpoont/project-execution-model/releases/tag/v1.2.2) — 2026-11-01

### Changed

- Connected ongoing planning and coordination to choosing increments and
  checking readiness, accounting for priorities, dependencies, available
  resources and existing commitments. PEM remains self-contained; scheduling
  and assignment mechanics remain outside its responsibility boundary.
- Clarified shared mock and test coverage, reuse of applicable review evidence,
  and when to stop adding mock detail or revisit affected coverage. Preserve
  each part's significant responsibilities and the mocks-first direction.
- Extended the café example to distinguish passing checks from sufficient
  evidence for a particular commitment. Compare a targeted further trial,
  monitored regular use and a permanent refit, including when more evidence
  could change the decision and when repeating checks adds little.
- Added an illustrative café handover note connecting permission, supporting
  context, scoped passes, the pending benefit check, and ownership of recording,
  escalation and later decisions after setup work closes.

Retained the six recurring steps and existing safeguards, with no new stage,
required document, template or tool. The question of substituting a real trial
for a credible but disproportionately costly mock remains unresolved; the
existing bounded-experiment provision is unchanged.

Comparative Pro reviews, independent editorial reviews and simulated cases
support documentary readiness. They do not establish improved human-reader
usability, decisions, handovers or real-project outcomes. The café evidence is
fictional, and its trial does not prove the later weekly benefit.

Sources: [planning and coordination (#14)](https://github.com/shpoont/project-execution-model/pull/14),
[proportionate mock coverage (#15)](https://github.com/shpoont/project-execution-model/pull/15),
[evidence sufficiency (#16)](https://github.com/shpoont/project-execution-model/pull/16),
and [worked handover record (#17)](https://github.com/shpoont/project-execution-model/pull/17),
addressing issues [#10](https://github.com/shpoont/project-execution-model/issues/10),
[#9](https://github.com/shpoont/project-execution-model/issues/9),
[#11](https://github.com/shpoont/project-execution-model/issues/11)
and [#12](https://github.com/shpoont/project-execution-model/issues/12).

## [v1.2.1 — Iteration and Work Records](https://github.com/shpoont/project-execution-model/releases/tag/v1.2.1) — 2026-10-29

### Changed

- Clarified how findings lead to investigation, review of challenged decisions,
  assessment of affected work and evidence, and readiness for the next
  commitment. Reuse what still applies and repeat necessary checks.
- Made useful work-record preservation explicit throughout execution: retain
  context and useful abandoned approaches, reuse adequate existing records,
  distinguish observations from explanations and attempts from demonstrated
  results, and keep material corrections and recording gaps understandable.
- Clarified that concise project notes do not replace systematic evidence
  needed for checks or operation. Consolidated overlapping retention guidance
  in **Advance With Evidence**.

Retained the six recurring steps and their existing safeguards, with no new
required document, record schema or tool. Independent reviews and matched
simulated cases support documentary readiness; both versions produced sound
decisions, so comparative decision improvement and real-project benefits remain
unproven.

Sources: [iteration clarification (#7)](https://github.com/shpoont/project-execution-model/pull/7),
[work-record clarification (#8)](https://github.com/shpoont/project-execution-model/pull/8),
and [work-record requirements (#5)](https://github.com/shpoont/project-execution-model/issues/5).

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
