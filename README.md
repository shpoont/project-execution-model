# Project Execution Model

The Project Execution Model helps people turn a need into a working result
and learn whether it produces the intended benefit. Use it for projects in any
field, from one-person efforts to work shared by human or AI contributors.

## The Model in Brief

These six steps recur as the project develops.

1. **[Define](docs/project-execution-model.md#define).** Choose the need, who
   should benefit, and the intended benefit. Agree what would make the result
   acceptable, the limits to respect, and why the approach is worth pursuing.
2. **[Design](docs/project-execution-model.md#design).** Work out how the result
   should work, including its parts, their responsibilities, and how people or
   parts pass work and information between them.
3. **[Mock](docs/project-execution-model.md#mock).** Try and review prototypes,
   samples or rehearsals first. Use a
   [bounded real experiment](docs/project-execution-model.md#check-readiness-before-committing)
   instead only where justified. Reuse reviewed evidence that still applies. Record
   findings and what remains unproven in real operation.
4. **[Prepare Tests](docs/project-execution-model.md#prepare-tests).** Agree what
   the next manageable piece must deliver and how to assess it, using the design
   and review findings. Prepare usable checks before doing the work they guide.
   Tests can be manual or automated.
5. **[Implement](docs/project-execution-model.md#implement).** Make the result
   real incrementally, replacing relevant stand-ins and putting rehearsed work
   into practice. Run relevant checks after each change and correct problems.
   Satisfy agreed expectations and verify the real parts working together in
   their intended setting where available.
6. **[Deliver](docs/project-execution-model.md#deliver).** Accept and hand over
   the result, agreeing who will handle ongoing checks and monitoring. Assign
   who will assess the benefit in actual use and when, then use the findings to
   continue, improve, reconsider, or stop. Acceptance alone does not prove the
   benefit.

## How the Steps Work Together

Planning, review, and testing run throughout. Tests develop as expectations
emerge. Findings can reopen any affected decision: revisit that work and keep
what still applies. Carry the relevant goal, decisions and their reasons,
evidence, and open questions between steps and contributors.

[Before a consequential commitment](docs/project-execution-model.md#check-readiness-before-committing),
confirm that the approach and dependencies are ready, resources are available,
authorization is in place, and the required evidence is sufficient. A passed
check supports only what was tested; failed or pending checks are not passes.

## Start Here

Start with a current need: who needs what, and why? Follow the full model's
[café journey](docs/project-execution-model.md#the-project-journey), then use
[Main Concepts](docs/project-execution-model.md#main-concepts) as a working
reference for its complete guidance.

## Documents

- [Model v1.3.1 — Guidance for Intended Use](docs/project-execution-model.md)
  — the full model, café example, and detailed guidance.
- [Release notes](https://github.com/shpoont/project-execution-model/releases/tag/v1.3.1)
  — changes in the current release.
- [Decision log](docs/decision-log.md) — lasting decisions and their rationale.
  The model document contains the guidance to use.
- [Changelog](CHANGELOG.md) — summaries of changes by version.

## Feedback

Use GitHub Issues for feedback. A proposal becomes guidance only after a model
change is adopted and its lasting decision is recorded.

## License

The model and repository documents are available under the [MIT License](LICENSE).

## Disclaimer

This model is provided "as is", without warranties of any kind. To the maximum
extent permitted by law, the owner and contributors are not liable for any loss,
damage, or other consequences arising from its use. Review the model's guidance
and its suitability for your project before applying it.

This model is an independent project and is not affiliated with, endorsed by,
or sponsored by OpenAI.
