# Decision log

This is the repository's dedicated record of lasting decisions. The
[Project Execution Model](../deliverables/project-execution-model.md) contains current
project guidance; this log explains why it took its present form and where
earlier decisions changed scope.

Earlier decisions were consolidated on 2026-09-05. Dates identify when each
direction was discussed or adopted, not when this log was written. Superseded
directions are identified explicitly. This log records decisions and their
reasons rather than transcripts, tool runs, or draft versions.

## D01 — 2026-06-12 to 2026-06-19: General project execution

**Status: general scope retained.** The original need included software and
non-code personal or administrative projects. The owner later confirmed that
the model should be usable by people and agents.

The repository provides project execution practices. A particular AI runtime,
test framework, work-management tool, or organization design is not a
prerequisite. Reusable quality standards are maintained separately under D16.
General work-system design does not define this repository's deliverable.

**Current guidance:** [goal](../deliverables/project-execution-model.md#goal).

## D02 — 2026-06-18 to 2026-06-19: Prepare delivery in useful increments

**Status: incremental preparation retained; fixed risk tiers and a separate
planning stage superseded by D15.** Establish the intended outcome, criteria,
reviewed evidence, and relevant checks before a consequential implementation
increment. Plan throughout the project and confirm readiness before each
substantial commitment.

The review of the initial proposal identified excessive ceremony and false
confidence from mocks as risks. The retained principle is to prepare at a useful
scale, state what a mock leaves unproven, and verify the real combined result.

**Current guidance:**
[main concepts](../deliverables/project-execution-model.md#main-concepts).

## D03 — 2026-06-19: Test draft end-user documentation before implementation

**Status: retained where draft usage guidance answers a relevant question;
universal documentation-before-implementation requirement superseded by D15.**
The owner originally required draft end-user documentation before implementation
as a UX test surface. Reading or walking through it can expose missing context,
confusing steps, unsafe assumptions, expected results, and recovery needs while
the design is inexpensive to change.

When used, draft documentation remains unverified until reconciled with the
actual result. It complements appropriate usage evidence.

**Current guidance:** [mock review](../deliverables/project-execution-model.md#mock).

## D04 — 2026-06-19: Check the project as a whole

**Status: retained.** Review found that a process for individual contributions
was insufficient to guide a whole project. The standard was expanded to cover
the project record, decomposition, sequencing, budget and capacity, shared
dependencies, integration, release, adoption, support, and final completion.

The second review confirmed those additions. That review is evidence of
document coverage, not empirical proof that the standard guarantees successful
projects. Component results still need a combined-result assessment.

**Current guidance:** [test the combined result](../deliverables/project-execution-model.md#implement)
and [delivery and learning](../deliverables/project-execution-model.md#deliver).

## D05 — 2026-06-19: One core standard with focused supporting standards

**Status: one core document retained; former name and co-location of standards
superseded by D15 and D16.** The owner originally selected Project Execution
Standards as the repository name, with one main execution document and focused
supporting quality standards.

The lasting principle is one authoritative project model rather than competing
descriptions of the process. Reusable quality criteria are maintained outside
this model.

**Current guidance:** [repository documents](../README.md#documents).

## D06 — 2026-06-23: Adopt the evidence quality standard

**Status: rationale retained; standard moved under D16.** Following a focused
review and owner approval, the evidence quality standard was added as a
supporting asset. Evidence needs to support a specific claim with suitable
provenance, freshness, inspectability, source verification, and clear limitations
at the project's risk level.

Generated summaries and positive reviews cannot replace the underlying result
or source. Sensitive evidence should be minimized and retained only where it
serves a real project need.

**Current guidance:** [evidence limits](../deliverables/project-execution-model.md#main-concepts).

## D07 — 2026-06-26: Make material project decisions reviewable

**Status: retained for project evidence; generic authority semantics are
outside this model's scope.** Usage feedback showed that a response could be
interpreted more broadly than the decision actually presented. The owner chose
a written-evidence approach rather than a prescribed human-agent interaction.

Project decision material must identify the proposal, responsible decision
owner, evidence, outcome, and scope. Routine work uses existing authorization;
unresolved project decisions need clarification. This project model does not
define the general meaning or effect of agreement or authority.

**Current guidance:** [readiness and evidence](../deliverables/project-execution-model.md#main-concepts)
and the [model boundary](../deliverables/project-execution-model.md#boundary).

## D08 — 2026-06-28: Use issues for repository feedback

**Status: retained.** The owner authorized issue intake for feedback,
questions, defects, and proposals. Maintainers assess the evidence and decide
whether to answer, investigate, defer, reject, or make a model change.

An issue's existence does not adopt its proposal. Lasting repository decisions
belong in this log; issue discussion can support them without becoming another
canonical document.

**Current guidance:** [feedback](../README.md#feedback).

## D09 — 2026-06-29: Preserve realistic usage evidence and a delivery baseline

**Status: realistic usage evidence retained; mandatory stable package
superseded by D15's ongoing planning and readiness checks.** Following usage
feedback, the owner required stronger preparation for consequential public or
operator surfaces: testable usage, explicit interface expectations, and checks
of documentation, errors, compatibility, and unsupported cases where relevant.

Static material cannot silently substitute for stronger practical usage
evidence where it is required. Review findings remain distinct from
implementation or release authorization. Detailed universal approval gates
were removed under D13; project readiness checks remain.

**Current guidance:** [mock review](../deliverables/project-execution-model.md#mock)
and [develop tests throughout](../deliverables/project-execution-model.md#develop-tests-throughout).

## D10 — 2026-07-04: Keep the project outcome central

**Status: retained.** The owner approved a clearer goal describing progress
through understandable stages from idea to accepted result.

The goal connects useful work, appropriate evidence, user understanding,
managed change, real-result verification, acceptance, and ownership. Model
exploration must not displace that project purpose.

**Current guidance:** [project goal](../deliverables/project-execution-model.md#goal).

## D11 — 2026-07-04 to 2026-07-05: Support nested and cross-team projects

**Status: project requirements retained; generic relationship semantics are
outside this model's scope.** The owner required support for hierarchical
execution, then challenged a team-only hierarchy with a feature spanning two
of three teams. A project can also sit within a larger initiative.

Project planning must track outcomes, participating teams, dependencies,
interfaces, integration evidence, and relevant exclusions. Completion of
individual contributions does not replace checking the combined project
outcome. The general representation of work relationships is handled outside
this repository.

**Current guidance:** [apply the model at a useful scale](../deliverables/project-execution-model.md#apply-the-model-at-a-useful-scale)
and [test the combined result](../deliverables/project-execution-model.md#implement).

## D12 — 2026-07-09 to 2026-07-10: Keep general work semantics outside this model

**Status: scope boundary retained; migration into a general work model
superseded by D13.** A general work model was considered as the destination
for this repository. The owner chose to keep project execution here while
developing general work semantics separately.

Provisional definitions of generic work items, roles, relationships, and
authority are not specifications for this repository. Its current scope and
meaning are defined by the project model itself.

**Current guidance:** [project model boundary](../deliverables/project-execution-model.md#boundary).

## D13 — 2026-09-05: Refocus this repository and consolidate its history

**Status: repository focus retained; document structure and standards placement
later changed in D15 and D16.** The owner kept this repository about project
execution while leaving general work semantics outside its scope.

The reorganization retained the then-current project stages, delivery
practices, quality standards, planning prompts, and issue intake. It removed
local generic model definitions, universal gate machinery, migration drafts,
review transcripts, session-event files, and generated historical audits.
Lasting decisions were consolidated here.

The cleanup applies to repository working documents. Existing Git commits are
not rewritten. Required delivery evidence in adopting projects is not subject
to this documentation-history cleanup.

**Current guidance:** [README](../README.md) and
[project model boundary](../deliverables/project-execution-model.md#boundary).

## D14 — 2026-09-05: Make execution stages the main document structure

**Status: visibility principle retained; stage structure revised in D15 and
D17.** The owner found that the execution stages were difficult to locate under
the broad label "Prepare and deliver." The then-current standard made its
longer sequence explicit, with project setup, repeated delivery stages,
integration, release, and handoff. Version 1.0 later replaced that structure
with seven steps while keeping the sequence visible and iterative.

**Current guidance:** [project journey](../deliverables/project-execution-model.md#the-project-journey).

## D15 — 2026-09-22 to 2026-09-23: Adopt and lock Version 1.0

**Status: adopted for the initial version; seven-step structure superseded by
D17.** The Project
Execution Model is the one current core document, named
`docs/project-execution-model.md`. Its original seven steps showed
increasing commitment with returns to affected earlier decisions. Planning
continues throughout rather than occupying a separate stage; readiness is
checked before consequential commitments.

The model carries reviewed mock findings into test preparation, replaces mocks
with reality in useful increments, and verifies the real combined result.
Evidence limits remain visible. Delivery acceptance, execution constraints,
and benefit from actual use are separate claims, with a receiving owner for
later outcome checks. Apply the model at a useful scale without requiring a
document for every activity. General work semantics remain outside this model's
scope.

The former ten-stage standard, record template, and separate model-boundary
file were retired. The version designation remains inside the model rather
than in its filename.

**Current guidance:** [Project Execution Model](../deliverables/project-execution-model.md).

## D16 — 2026-09-23: Maintain reusable quality standards separately

**Status: adopted.** Documentation and evidence quality standards should guide
daily human and agent work across projects. Their applicability is broader than
this project's execution model, so maintain them separately.

The existing standards were moved without changing their substantive criteria.
The Project Execution Model remains self-contained; projects may apply relevant
standards without treating the whole collection as a required part of the model.

## D17 — 2026-09-24: Use Recurring Areas of Work and Implementation Contracts

**Status: adopted for v1.1.0; structure and contract definition revised by D24
for v1.2.0.** Organize the
model around Define, Design, Implement, and
Deliver & Learn as recurring areas within one iterative process. Mock review,
test preparation, and testing continue throughout the project rather than
occupying separate stages. Findings can reopen affected decisions while valid
work and evidence carry forward. Readiness checks govern specific commitments;
milestones may record those decisions without declaring an area permanently
finished.

Preserve review before the relevant commitment and tests before the relevant
implementation. Tests develop across all four areas as expectations emerge;
mock review informs them but need not precede every test. Choose mocks for the
uncertainty they resolve, reuse applicable reviewed evidence, and use bounded
real experiments for questions mocks cannot credibly answer.

For each increment, agree the subset of tests that covers its implementation
responsibilities. This implementation contract is the main agreement between
Design and Implementation, supported by the intended result and its reasoning.
It requires no separate document or test framework. Later outcome checks can
create current obligations, such as implementing measurement capability.

Implementation satisfies the assigned checks and adds verification of its own
construction and integration. Internal verification is subject to the same
evidence and failure-handling rules. New findings may reveal missing contract
coverage or challenge the design; changes to expectations must be explicit.
Verify the relevant real combined result. Test substitutes can remain useful
for controlled conditions, but their passes do not establish that substituted
components or real interactions work.

Readiness, permitted exceptions, and honest test statuses remain in force.
Implementation completion does not require every project test to have passed.
Checks needing later delivery or actual use retain explicit ownership and
timing. Acceptance, benefit, constraints, handover, and closure remain distinct
responsibilities, including receiving-owner decisions after project closure.

For live services, implementation and delivery may overlap; assign checks to
the commitments and conditions they can actually assess. Expected failures
from missing implementation may share the existing implementation agreement
as their recorded decision and follow-up. Findings that challenge that
agreement need a further decision. Exceptions remain bounded by the project's
agreed limits, applicable obligations, and the decision-maker's authority.

**Published v1.1.0 guidance:** [project journey](https://github.com/shpoont/project-execution-model/blob/v1.1.0/docs/project-execution-model.md#the-project-journey),
[implementation contract](https://github.com/shpoont/project-execution-model/blob/v1.1.0/docs/project-execution-model.md#agree-on-the-implementation-contract),
and [tests throughout the project](https://github.com/shpoont/project-execution-model/blob/v1.1.0/docs/project-execution-model.md#develop-tests-throughout).

## D18 — 2026-09-25: Update the Name of the Separate Work Model

**Status: adopted.** The separate model formerly called Work Execution Model
is now named Work Management Model. This naming change leaves its concepts and
semantics unchanged. The responsibility boundary also remains unchanged:
this repository covers project execution, while the separate model covers
general work definitions and the mechanics of operational planning.

**Current guidance:** [project model boundary](../deliverables/project-execution-model.md#boundary).

## D19 — 2026-10-03: Strengthen Mock and Test Practice and Release Version 1.1.0

**Status: adopted.** [PR #2](https://github.com/shpoont/project-execution-model/pull/2)
strengthens mock coverage, organization of mocks and tests, and practical test
preparation. The aim is to expose important missing behavior, keep contributors'
working material understandable and current, and make assessments usable before
relying on them. Review whether all checks could pass while an important part
of the intended result remains missing or wrong.

[PR #3](https://github.com/shpoont/project-execution-model/pull/3) rewrites the
café example and improves wording and navigation. The example should show checks
guiding actual implementation and corrections, verification of the combined
service, and a later benefit review that can challenge an accepted result.

Release these changes as **v1.1.0 — Evidence in Practice**, preserving the four
recurring areas, readiness and evidence safeguards, and outcome and closure
responsibilities. Add no stage or required project document. Retain the initial
release date, 22 September 2026, and the `v1.0.0` baseline at `eb126d1`.
Versioned change summaries belong in the changelog; this log preserves decisions
and their reasons.

**Published v1.1.0 guidance:** [mock review](https://github.com/shpoont/project-execution-model/blob/v1.1.0/docs/project-execution-model.md#review-the-proposal-with-mocks),
[test preparation](https://github.com/shpoont/project-execution-model/blob/v1.1.0/docs/project-execution-model.md#develop-tests-throughout),
and the [changelog](../CHANGELOG.md).

## D20 — 2026-10-24: Propose Six Recurring Steps and Subsystem Cycles

**Status: proposed for issue #4, increment 1; adopted by D24 for v1.2.0.** Give Mock and
Prepare Tests their own recurring steps alongside Define, Design, Implement
and Deliver. Their work needs greater visibility and clearer connections to
the designed system. Deliver retains learning, later outcome checks and
closure responsibilities.

Make Design explicit about the system's elements, responsibilities, ownership,
interfaces, interactions and decomposition. Apply the full cycle within
substantial subsystems when uncertainty or consequential commitments warrant
it. Inherit relevant parent context, return findings that challenge parent
decisions, and return real results, checks and evidence. The parent remains
responsible for integration and verification of the combined outcome. Minor,
well-understood tasks need no nested cycle or separate set of documents.

This revises D17's four-area structure while preserving its iteration,
implementation-contract, readiness and evidence principles. Implementation
replaces relevant mocks with real parts; useful test substitutes may remain
with their evidence limits explicit. Separate steps do not freeze earlier
decisions or require a separate document for each activity.

Mock/test relationships, assessment validation and practical usability are
covered by D21–D23. D24 records adoption of the complete revision after review.

**Current guidance:** [project journey](../deliverables/project-execution-model.md#the-project-journey),
[design](../deliverables/project-execution-model.md#design), and
[application at a useful scale](../deliverables/project-execution-model.md#apply-the-model-at-a-useful-scale).

## D21 — 2026-10-26: Propose Recursive Coverage and Incremental Test Preparation

**Status: proposed for issue #4, increment 2; adopted by D24 for v1.2.0.** Connect mock and
check coverage to the designed system and every child element. Assess each
element's significant aspects against its own responsibilities, requirements,
constraints and interactions. Recursive coverage does not require a separate
mock artifact or full project cycle for every child.

Keep Mock and Prepare Tests distinct. Explain reviewing mocks to develop
checks, checking actual elements with mocked dependencies, checking mocks
themselves, and applying suitable shared checks to substitutes and their real
replacements. Their evidence has different limits; useful dependency
substitutes can remain alongside checks of actual elements and integration.

Review and reuse existing checks, adapt or correct them, and retire obsolete
or redundant checks without losing coverage of still-agreed expectations.
Prepare usable checks for the next behavior before implementing it, while
scenarios and checks develop incrementally. Set expected outcomes from agreed
expectations rather than copying observed output, and refine implementation
without silently changing its target.

Preserve contract coverage, readiness for each commitment, evidence states,
real combined verification and later outcome obligations. A complete, frozen
suite is not a prerequisite to starting implementation. Assessment validation
and practical usability are covered by D22 and D23. D24 adopts the complete
revision for v1.2.0.

**Current guidance:** [mock coverage](../deliverables/project-execution-model.md#cover-the-system-and-its-parts),
[mock/test relationships](../deliverables/project-execution-model.md#connect-mocks-and-tests),
and [incremental check preparation](../deliverables/project-execution-model.md#prepare-scenario-checks).

## D22 — 2026-10-26: Propose Assessment Validation and Explicit Assessment Failures

**Status: proposed for issue #4, increment 3; adopted by D24 for v1.2.0.** Validate checks
and assessment methods with representative acceptable results and plausible
violations. Establish reference assessments independently from the method
being checked, using agreed expectations, relevant evidence and appropriate
review. Include acceptable variation, investigate mistaken acceptance and
rejection, and check judgment consistency where it matters. Scale validation
to the expectation and the decisions that depend on it.

Review the collection for important omissions even when its included checks
pass. Preserve the implementation contract and coverage of still-agreed
expectations; correcting an assessment does not quietly change its target.

Distinguish a failed assessment attempt or insufficient evidence from an
observed violation of the work's criterion. An assessment that cannot establish
an outcome remains pending with the reason. Missing access to evidence differs
from evidence that a required result is absent. Neither an assessment failure
nor an authorized exception supplies a valid pass or changes an observed result.

Keep Passed, Failed and Pending, commitment-specific readiness, real combined
verification, later outcome responsibilities and the six-step process. Add no
required framework, dataset or document. The broader practical-use workflow
is covered by D23. D24 adopts the complete revision for v1.2.0.

**Current guidance:** [assessment validation](../deliverables/project-execution-model.md#validate-assessments)
and [result interpretation](../deliverables/project-execution-model.md#interpret-results).

## D23 — 2026-10-27: Propose Connected Use and Maintenance of Mocks and Checks

**Status: proposed for issue #4, increment 4; adopted by D24 for v1.2.0.** Connect the current
design, mocks, checks and evidence so contributors can select relevant work,
establish usable prerequisites, apply instructions and interpret scoped results.
Include checks for affected smaller and larger parts and how they work together,
and retain the checks required for each commitment.

Use evidence to investigate whether a finding concerns implementation, a mock,
an assessment, supporting arrangements or unresolved expectations. Involve the
relevant owner or decision-maker and keep uncertain causes and follow-up visible.
Coordinate affected updates, prepare checks before the behavior they guide,
and revisit relevant assessment validation when its basis changes.

Retain decisions and reasons, findings, evidence and open questions across
contributors. Distinguish current, superseded and historical work, and reuse
suitable work and evidence with effort proportionate to risk and uncertainty.
Preserve existing coverage, authority, result states and evidence limits.
Assess the collection's practical usability through a representative workflow,
reusing suitable evidence and keeping the effort proportionate.

Add no execution stage, required document, project layout, runner or framework.
Keep the public model self-contained. D24 records adoption of the complete
revision after integrated review.

**Current guidance:** [use and maintenance](../deliverables/project-execution-model.md#use-and-maintain-mocks-and-checks).

## D24 — 2026-10-28: Adopt Six Recurring Steps and Release Version 1.2.0

**Status: adopted.** Adopt the complete revision from
[issue #4](https://github.com/shpoont/project-execution-model/issues/4), merged in
[PR #6](https://github.com/shpoont/project-execution-model/pull/6), including D20–D23.
Give Mock and Prepare Tests their own work and connections within **Define →
Design → Mock → Prepare Tests → Implement → Deliver**. This makes exploration,
assessment preparation and their relationship to design more visible without
turning the model into a single pass. Planning, review and testing continue
throughout; findings can reopen affected decisions while valid work is reused.

Clarify Design's architecture and ownership, recursive mock and check coverage,
assessment validation, and the connected collection's practical usability.
Substantial subsystems can use the full cycle with inherited context and return
real results, checks and evidence; the parent still verifies the combined outcome.

Revise D17's implementation-contract definition: the agreement covers what an
increment must deliver, its conditions and how completion will be assessed.
Prepared tests guide and assess these expectations; missing tests do not remove
agreed obligations. Preserve checks before the behavior they guide, incremental
real replacement of mocks, real combined verification, honest evidence states,
readiness and authority, and later outcome and receiving-owner responsibilities.
Add no required document, hierarchy of named tiers, runner or framework.

Release this model as **v1.2.0 — Six Steps, One Process**, with the pointed
pyramid overview and café images introducing their matching examples. Retain
the initial release date, 22 September 2026. Keep `v1.0.0` at `eb126d1` and
`v1.1.0` at `fa06d11`; earlier published guidance remains available at those tags.

Independent reviews and representative walkthroughs support the revision's
clarity, consistency and bounded usability. They do not establish improved
reliability, efficiency or benefits in real projects; those claims need evidence
from subsequent use.

**Current guidance:** [project journey](../deliverables/project-execution-model.md#the-project-journey),
[implementation contract](../deliverables/project-execution-model.md#agree-on-the-implementation-contract),
and [changelog](../CHANGELOG.md).

## D25 — 2026-10-29: Clarify Iteration and Work Records

**Status: adopted for v1.2.1.** Adopt the clarifications merged in
[PR #7](https://github.com/shpoont/project-execution-model/pull/7) and
[PR #8](https://github.com/shpoont/project-execution-model/pull/8), the latter
addressing [issue #5](https://github.com/shpoont/project-execution-model/issues/5).

Connect investigation of findings to the decisions they challenge, affected
work and evidence, and readiness for the next commitment. Investigate before
choosing a remedy rather than prescribing a fixed return to a particular step.
Keep applicable work and evidence and repeat necessary checks.

Make useful work-record preservation explicit in Advance With Evidence.
Retain context, including useful exploration and abandoned approaches, while
reusing adequate existing records. Distinguish observations from explanations
and attempts from demonstrated results. Keep material corrections and known
recording gaps understandable. Concise project notes do not replace the
underlying evidence required for checks or operation, and missing records do
not establish that nothing happened.

Release these clarifications as **v1.2.1 — Iteration and Work Records**. They
clarify the existing six-step model without adding a stage, required document,
record schema or tool. Preserve the initial release date and earlier tags.

The seven-step editorial cycle, independent meaning-preservation review and
matched simulated cases support documentary readiness. Both original and
revised versions produced sound decisions in the cases; comparative decision
improvement and effectiveness in real projects remain unproven.

**Current guidance:** [Advance With Evidence](../deliverables/project-execution-model.md#advance-with-evidence)
and [changelog](../CHANGELOG.md).

## D26 — 2026-11-01: Clarify Evidence for the Next Commitment

**Status: adopted for v1.2.2.** Adopt the clarifications addressing issues
[#9](https://github.com/shpoont/project-execution-model/issues/9),
[#10](https://github.com/shpoont/project-execution-model/issues/10),
[#11](https://github.com/shpoont/project-execution-model/issues/11)
and [#12](https://github.com/shpoont/project-execution-model/issues/12), merged in
[PR #14](https://github.com/shpoont/project-execution-model/pull/14),
[PR #15](https://github.com/shpoont/project-execution-model/pull/15),
[PR #16](https://github.com/shpoont/project-execution-model/pull/16)
and [PR #17](https://github.com/shpoont/project-execution-model/pull/17).

Connect planning inputs and existing commitments to increment selection and
readiness. Keep PEM usable without adopting the Work Management Model; general
scheduling and assignment mechanics remain outside PEM.

Judge additional mock detail by uncovered significant aspects and material
questions for the next commitment. Shared mocks, checks and applicable review
evidence can cover several parts without removing each part's obligations.
Retain the mocks-first direction and current bounded-experiment provision;
whether a credible but disproportionately costly mock may be replaced by a
real trial remains unresolved.

Use the café story to explain why the same evidence can justify monitored,
reversible use while leaving a permanent investment unsupported. Show when
further evidence could change the decision and when accumulating similar
passes adds little. An ordinary handover note carries permission, reasons,
scoped results and follow-up together without requiring a new record format.
Acceptance and setup closure do not prove the benefit or remove its owner's
later review and decision.

Release these clarifications as **v1.2.2 — Evidence for the Next Commitment**.
Preserve the six recurring steps, tests before the behavior they guide, readiness
and authority, honest result states, real combined verification and later
outcome responsibilities. Add no stage, required document, template or tool.
Retain the initial release date and all earlier version tags.

Comparative Pro reviews, independent editorial reviews and simulated cases
support documentary readiness within the reviewed scope. The café evidence is
fictional; improved human-reader usability, decisions, handovers and real-project
outcomes remain unproven.

**Current guidance:** [project journey](../deliverables/project-execution-model.md#the-project-journey),
[mock coverage](../deliverables/project-execution-model.md#cover-the-system-and-its-parts),
[commitment readiness](../deliverables/project-execution-model.md#check-readiness-before-committing),
[handover note](../deliverables/project-execution-model.md#example-a-handover-note)
and [changelog](../CHANGELOG.md).

## D27 — 2026-11-01: Adopt the Journey and Working Reference

**Status: adopted for v1.2.3.** Adopt the editorial revision from
[issue #18](https://github.com/shpoont/project-execution-model/issues/18), merged
in [PR #19](https://github.com/shpoont/project-execution-model/pull/19).

Keep one canonical model with a learning journey, café example and complete
working reference. First reading and later lookup need different levels of detail;
qualified summaries, direct links and a task index connect them
without making the full guidance optional. Place detailed mock review beside
progressive replacement and the complete agreement and scenario rules beside
test development.

Distinguish the pickup agreement for the whole increment from choosing its
next scenario. Place the handover example beside use and maintenance, and
guidance for work after closure below the complete Deliver vignette. Introduce
Design terms through their meanings; retire the two unused labels "child elements"
and "decomposition" while retaining nested parts and all related obligations.
Explain stopping, check coverage and evidence value in ordinary language.

Preserve the six recurring steps, five Main Concepts, mocks-first and
tests-first direction, agreed expectations, evidence and authority limits,
real combined verification, and later outcome and receiving-owner duties.
Keep the café's facts and images and the Work Management Model boundary.
Add no stage, required artifact, template, tool or operating method. The
question of using a real trial when a credible mock is disproportionately
costly remains unresolved.

Release this revision as **v1.2.3 — Journey and Working Reference**. Retain
the initial release date, 22 September 2026, and every earlier version tag.
Accept the trade-off of a shorter journey and a longer complete reference;
word counts alone do not establish less effort or better understanding.

Independent comparisons found no substantive loss, and a fresh blind
application outside software found no required change. These reviews and
fictional cases support documentary readiness, not measured human usability
or real-project effectiveness. Optional preferences for image orientation and a
component example do not require another revision before this release.

**Current guidance:** [project journey](../deliverables/project-execution-model.md#the-project-journey),
[working reference](../deliverables/project-execution-model.md#main-concepts),
[implementation agreement](../deliverables/project-execution-model.md#agree-on-the-implementation-contract)
and [changelog](../CHANGELOG.md).

## D28 — 2026-11-06: Lead With Purpose and Provide a Summary for First-Time Readers

**Status: adopted for v1.2.4.** Adopt the Goal revision from
[issue #20](https://github.com/shpoont/project-execution-model/issues/20), merged
in [PR #23](https://github.com/shpoont/project-execution-model/pull/23), and the
README summary from [issue #21](https://github.com/shpoont/project-execution-model/issues/21),
merged in [PR #24](https://github.com/shpoont/project-execution-model/pull/24).

Introduce the model through what it helps people accomplish: turn a need into
a working result and assess the intended benefit. Explain connected reasoning
as support for that journey. Retain the relevant goal, decisions and their
reasons, evidence and open questions across steps and contributors.

Give newcomers a concise, plain-language overview of the six recurring steps
and a way to begin in the README. Maintain one summary rather than a second
independent copy. The full model remains authoritative; link to its detailed
guidance instead of compressing every safeguard into the introduction.

Release these editorial changes as **v1.2.4 — Purpose and First Steps**. Preserve
the existing model rules, café example, images and Work Management Model
boundary. Add no stage, required document, tool or operating rule. Keep the
initial release date, 22 September 2026, and all earlier version tags. The
broader real-trial policy remains unresolved and deferred in
[#22](https://github.com/shpoont/project-execution-model/issues/22).

Comparative Pro reviews, the seven-step editorial cycles, independent
preservation and fresh blind applications support documentary readiness.
They do not establish measured human-reader usability or real-project
effectiveness. The README summary fits the agreed one-page print format;
this does not imply that the entire README fits one page or every viewport.

**Current guidance:** [Goal](../deliverables/project-execution-model.md#goal),
[README summary](../README.md#the-model-in-brief),
[starting point](../README.md#start-here) and [changelog](../CHANGELOG.md).

## D29 — 2026-11-06: Allow Justified Trials When Mocking Is Disproportionate

**Status: adopted for v1.3.0.** Adopt the additional bounded-trial route from
[issue #22](https://github.com/shpoont/project-execution-model/issues/22), merged
in [PR #25](https://github.com/shpoont/project-execution-model/pull/25).

A credible mock can answer a question yet require disproportionate preparation
or review for the evidence it would add. Permit a bounded real trial instead
for a particular material question when comparing suitable mock options,
including simpler or reused work, with the proposed trial justifies that choice.
Consider evidence, effort, delay, consequences and remaining uncertainty; cost
alone is insufficient. Keep the reasons in the existing project record.

Preserve mocks-first and the existing experiment route for questions no mock
can credibly answer. Require a clear question, prepared assessment, limits,
authorization and stopping conditions within project obligations and authority.
The new permission does not waive required checks or prove untested claims.
Review findings under their conditions and carry them and remaining uncertainty
into design, test preparation and the next commitment. Other review obligations
remain; reconsider a commitment with no acceptable route.

This resolves the policy question left open in D26–D28. Their unresolved or
deferred statements, and those in earlier changelog entries, record the state
of those releases rather than the current policy.

Release this addition as **v1.3.0 — Proportionate Real Trials**. Use a minor
version because it adds a permitted approach, not merely an editorial correction.
Retain the six recurring steps, five Main Concepts, tests-first direction,
evidence and authority limits, real combined verification and later outcome
responsibilities. Preserve the café example, figures, Work Management Model
boundary, initial release date and all earlier tags. Add no stage, required
document, template, tool or operational planning method.

Comparative and independent editorial reviews support documentary readiness,
not demonstrated human usability or real-project effectiveness. Pro covered the
pre-editorial draft and its temporary chat remained personalized; final-source
preservation and blind comprehension followed. The software and venue case
differences depend on a missing credible mock review, and the final music-school
case does not independently demonstrate the new proportionality route.

**Current guidance:** [commitment readiness](../deliverables/project-execution-model.md#check-readiness-before-committing),
[mock review](../deliverables/project-execution-model.md#mock),
[review findings](../deliverables/project-execution-model.md#review-and-carry-findings-forward),
[README summary](../README.md#the-model-in-brief) and [changelog](../CHANGELOG.md).

## D30 — 2026-11-06: Provide Guidance Suited to Intended Users and Participants

**Status: adopted for v1.3.1.** Adopt the clarification from
[issue #26](https://github.com/shpoont/project-execution-model/issues/26), merged
in [PR #27](https://github.com/shpoont/project-execution-model/pull/27).

Project history and evidence explain decisions and what was established.
People, AI agents or connected systems using or participating in the result
also need guidance suited to their actual tasks and conditions. Customers may
rely on signs, prompts, assistance or the experience itself; operators may
need training and a current reference, and connected systems may need interface
information. Reuse suitable guidance. Do not assume manual reading or require
a separate document per role.

Identify needed guidance during Design and use drafts in review where helpful.
Prepare representative usage checks with the support and prerequisites
participants will actually have, including unbriefed use where expected.
Reconcile applicable guidance with the real result and check its use. A readable
reference or rehearsal does not prove successful real operation. Retain the
existing investigation, evidence and commitment rules when use fails or a
check genuinely belongs later.

Include current guidance and its upkeep responsibility in handover, keeping
affected instructions aligned with changes and distinguishing superseded
versions. Preserve useful project history and operational records. The café's
customer directions and shared staff reference illustrate the different needs;
the handover lookup row points directly to Deliver.

Release this clarification as **v1.3.1 — Guidance for Intended Use**. Use a patch
version for making existing documentation, intended-use and handover duties
explicit. Preserve the six recurring steps, five Main Concepts, mocks-first
and tests-first direction, justified bounded trials, readiness, evidence limits,
later outcome ownership and Work Management Model boundary. Add no stage,
mandatory manual, general documentation standard or operational planning method.
Retain the initial release date and every earlier tag.

Fresh comparative Pro review and the seven-step editorial cycle found no
required correction within the increment. Pro covered the substantive draft;
independent full-model preservation and final blind comprehension cover the
later navigation link. The museum and book-swap applications were hypothetical.
They support documentary readiness, not actual participant performance,
interoperability or improved project outcomes. Broader inherited pacing,
wording and illustration preferences remain follow-ups.

**Current guidance:** [audiences and guidance](../deliverables/project-execution-model.md#design),
[usage checks](../deliverables/project-execution-model.md#prepare-tests),
[real-result verification](../deliverables/project-execution-model.md#implement),
[handover and upkeep](../deliverables/project-execution-model.md#deliver)
and [changelog](../CHANGELOG.md).

## D31 — 2026-11-07: Show Proportionate Preparation Through a Small Example

**Status: adopted for v1.3.2.** Adopt the clarification from
[issue #28](https://github.com/shpoont/project-execution-model/issues/28), merged
in [PR #29](https://github.com/shpoont/project-execution-model/pull/29).

Make lightweight use easier to judge without asking readers to reconstruct
the existing proportionality rules from several sections. Start with the
next commitment: what evidence and review are needed, what still applies,
and what is the simplest credible way to cover the rest?

Use one compact classroom-shelf story across the six steps. Existing product
information and class notes support the work. A taped outline reveals a
positioning problem before purchase; prepared checks then assess the real
assembled and loaded result. The next class supplies separate evidence of
the intended benefit, with continuing ownership of the arrangement.

The example illustrates sufficient preparation for that change, not a new
universal minimum or permission to omit obligations. Preserve significant
coverage, manual review where required, tests before the work they guide,
readiness and authorization, and the justified bounded-trial routes. Reuse
applicable evidence and records rather than require new artifacts.

Reviews and hypothetical applications support the example's clarity and
preservation of existing guidance. They do not establish physical safety,
reduced project effort or improved outcomes in actual use.

**Current guidance:** [small example and project journey](../deliverables/project-execution-model.md#the-project-journey),
[coverage and stopping](../deliverables/project-execution-model.md#cover-the-system-and-its-parts)
and [changelog](../CHANGELOG.md).

## D32 — 2026-11-11: Explain the Model Clearly While Preserving Its Substance

**Status: adopted for v1.3.2.** Adopt the model-document revision from
[issue #30](https://github.com/shpoont/project-execution-model/issues/30), merged
in [PR #32](https://github.com/shpoont/project-execution-model/pull/32).

Explain the work and its reasons in connected prose rather than relying on
long sequences of commands. Keep the learning journey and complete working
reference in one model. Short concept introductions, expandable Working
Guidance and direct lookup routes serve different reading needs; summaries
do not replace the applicable rules and conditions.

Keep all six steps in their existing order, with Mock prominent. The order
shows how work builds within one iterative process, not a requirement to
finish one step before another begins. Tests can develop with expectations,
and implementation and delivery can overlap. Readiness remains specific to
the consequential action; findings return changed demands to the people
responsible for priorities, resources and commitments. PEM remains usable
without adopting the Work Management Model or its planning mechanics.

Give intended-use checks one complete home in the implementation agreement.
Clarify current measurement capability for later checks, evidence reuse,
coverage and stopping, failure versus an indeterminate assessment, and the
value of another observation without weakening any existing condition.
Retain the distinction between acceptance, actual benefit and constraints,
along with real combined verification, authority, exceptions and later owners.

Keep the café opening in Define. Mark the story and figures as illustrative;
use starting observations, a backlog clock with no reset on further enquiries,
quoted-time limits and their operating response to make the example concrete.
Carry those conditions into the trial and handover. Preserve the target and
outcomes, and distinguish an observed improvement from proof of causation.
These example details add no general operating threshold.

Release D31 and this revision as **v1.3.2 — Clearer Explanations and Examples**.
Use a patch version because the changes explain and illustrate the existing
model without adding a stage, required document or execution route. Retain
the six steps, five Main Concepts, all rules and qualifications, shelf story,
figures, initial release date and earlier version tags.

Independent complete-source preservation and fresh blind comprehension
reviews, comparative Pro reviews and checks of the final wording found no
required correction within their scopes. The user read and approved the
final model. This supports documentary readiness, not measured human
readability or real-project effectiveness; some reference density remains.
The editorial-cycle skill work and practical validation remain separate
from this adopted document revision.

**Current guidance:** [project journey](../deliverables/project-execution-model.md#the-project-journey),
[working reference](../deliverables/project-execution-model.md#main-concepts),
[implementation agreement](../deliverables/project-execution-model.md#agree-on-the-implementation-contract)
and [changelog](../CHANGELOG.md).

## D33 — 2026-11-11: Adopt Project Structure and Publish Results in Deliverables

**Status: adopted for v2.0.0.** Implement the repository adoption in
[issue #31](https://github.com/shpoont/project-execution-model/issues/31), using
[Project Structure v1.1.0](https://github.com/shpoont/project-structure/tree/v1.1.0).
The adopted starter baseline is separate from PEM's release version.

Give readers an actual result area: move the canonical model and its five PNGs
to `deliverables/`, with a landing page identifying published and working
versions. Move the editable overview HTML to `src/diagrams/`. Keep one maintained
copy of each result. Retain forwarding routes from the former model document
and leave all earlier release tags unchanged.

Use a short project agreement and contributor guide, with connected repository,
check, evidence and delivery records. GitHub issues and pull requests remain
the current sources for increment agreements and active work. Combine records
and omit unused template areas rather than populate every starter folder.
Preserve the existing local instructions and publication responsibilities.

This organization governs maintaining the repository, not projects using PEM.
The model remains self-contained and its body, rules, examples, image placement,
author and initial release date are unchanged. Earlier decisions retain their
wording; their current-guidance links now point to the moved model.

Release as **v2.0.0 — Published Deliverables and Project Structure** because the
published layout changes. A forwarding document helps existing readers, but
direct raw-model, image and source paths on a moving branch are not fully
backward compatible. Pinned earlier releases keep their original contents and
paths. Adoption of Project Structure introduces no new model stage, required
project record, runtime or work-management tool.

Source, link and navigation checks support repository adoption and publication
readiness. Editorial reviews and hypothetical lookup tasks do not establish
usability for people unfamiliar with PEM, downstream migration or real-project effectiveness.

**Current records:** [project agreement](../PROJECT.md),
[repository guide](README.md), [published results](../deliverables/README.md),
[delivery](delivery.md) and [adoption checks](../evidence/project-structure-adoption.md).
