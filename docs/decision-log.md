# Decision log

This is the repository's dedicated record of lasting decisions. The
[Project Execution Model](project-execution-model.md) contains current
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

**Current guidance:** [goal](project-execution-model.md#goal).

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
[main concepts](project-execution-model.md#main-concepts).

## D03 — 2026-06-19: Test draft end-user documentation before implementation

**Status: retained where draft usage guidance answers a relevant question;
universal documentation-before-implementation requirement superseded by D15.**
The owner originally required draft end-user documentation before implementation
as a UX test surface. Reading or walking through it can expose missing context,
confusing steps, unsafe assumptions, expected results, and recovery needs while
the design is inexpensive to change.

When used, draft documentation remains unverified until reconciled with the
actual result. It complements appropriate usage evidence.

**Current guidance:** [review the proposal with mocks](project-execution-model.md#review-the-proposal-with-mocks).

## D04 — 2026-06-19: Check the project as a whole

**Status: retained.** Review found that a process for individual contributions
was insufficient to guide a whole project. The standard was expanded to cover
the project record, decomposition, sequencing, budget and capacity, shared
dependencies, integration, release, adoption, support, and final completion.

The second review confirmed those additions. That review is evidence of
document coverage, not empirical proof that the standard guarantees successful
projects. Component results still need a combined-result assessment.

**Current guidance:** [test the combined result](project-execution-model.md#implement)
and [deliver and learn](project-execution-model.md#deliver--learn).

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

**Current guidance:** [evidence limits](project-execution-model.md#main-concepts).

## D07 — 2026-06-26: Make material project decisions reviewable

**Status: retained for project evidence; generic authority semantics are
outside this model's scope.** Usage feedback showed that a response could be
interpreted more broadly than the decision actually presented. The owner chose
a written-evidence approach rather than a prescribed human-agent interaction.

Project decision material must identify the proposal, responsible decision
owner, evidence, outcome, and scope. Routine work uses existing authorization;
unresolved project decisions need clarification. This project model does not
define the general meaning or effect of agreement or authority.

**Current guidance:** [readiness and evidence](project-execution-model.md#main-concepts)
and the [model boundary](project-execution-model.md#boundary).

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

**Current guidance:** [review the proposal with mocks](project-execution-model.md#review-the-proposal-with-mocks)
and [develop tests throughout](project-execution-model.md#develop-tests-throughout).

## D10 — 2026-07-04: Keep the project outcome central

**Status: retained.** The owner approved a clearer goal describing progress
through understandable stages from idea to accepted result.

The goal connects useful work, appropriate evidence, user understanding,
managed change, real-result verification, acceptance, and ownership. Model
exploration must not displace that project purpose.

**Current guidance:** [project goal](project-execution-model.md#goal).

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

**Current guidance:** [apply the model at a useful scale](project-execution-model.md#apply-the-model-at-a-useful-scale)
and [test the combined result](project-execution-model.md#implement).

## D12 — 2026-07-09 to 2026-07-10: Keep general work semantics outside this model

**Status: scope boundary retained; migration into a general work model
superseded by D13.** A general work model was considered as the destination
for this repository. The owner chose to keep project execution here while
developing general work semantics separately.

Provisional definitions of generic work items, roles, relationships, and
authority are not specifications for this repository. Its current scope and
meaning are defined by the project model itself.

**Current guidance:** [project model boundary](project-execution-model.md#boundary).

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
[project model boundary](project-execution-model.md#boundary).

## D14 — 2026-09-05: Make execution stages the main document structure

**Status: visibility principle retained; stage structure revised in D15 and
D17.** The owner found that the execution stages were difficult to locate under
the broad label "Prepare and deliver." The then-current standard made its
longer sequence explicit, with project setup, repeated delivery stages,
integration, release, and handoff. Version 1.0 later replaced that structure
with seven steps while keeping the sequence visible and iterative.

**Current guidance:** [project journey](project-execution-model.md#the-project-journey).

## D15 — 2026-09-22 to 2026-09-23: Adopt and lock Version 1.0

**Status: adopted; seven-step structure superseded by D17.** The Project
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
file were retired. The Version 1.0 designation remains inside the model rather
than in its filename.

**Current guidance:** [Project Execution Model](project-execution-model.md).

## D16 — 2026-09-23: Maintain reusable quality standards separately

**Status: adopted.** Documentation and evidence quality standards should guide
daily human and agent work across projects. Their applicability is broader than
this project's execution model, so maintain them separately.

The existing standards were moved without changing their substantive criteria.
The Project Execution Model remains self-contained; projects may apply relevant
standards without treating the whole collection as a required part of the model.

## D17 — 2026-09-24: Use Recurring Areas of Work and Implementation Contracts

**Status: adopted.** Organize the model around Define, Design, Implement, and
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

**Current guidance:** [project journey](project-execution-model.md#the-project-journey),
[implementation contract](project-execution-model.md#agree-on-the-implementation-contract),
and [tests throughout the project](project-execution-model.md#develop-tests-throughout).
