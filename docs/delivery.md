# Delivery and Releases

The result people receive is the model and its illustrations in
[deliverables](../deliverables/README.md). The README is its short introduction.
GitHub releases and immutable version tags identify published versions; the
working branch may contain changes that have not been released.

## Use and Acceptance

The [published-results page](../deliverables/README.md) points to a tagged model,
its images and release notes. Earlier releases retain their original paths.
The model can be read as Markdown with a suitable viewer and needs no particular
work-management system or AI runtime.

The maintainer accepts an increment against its issue and pull-request
agreement. Review and publication evidence concern that delivery. Whether
using PEM produces the intended benefits needs evidence from actual use;
feedback and follow-up work are recorded through GitHub issues.

## Prepare a Release

Publication needs explicit authorization. Follow applicable local publication
instructions as well as this public overview. Review the intended scope and
evidence, settle any checks required for publication, and keep unresolved limits
visible. Record meaningful changes under Unreleased until preparing the release.

Version the project as a whole using `MAJOR.MINOR.PATCH`: major for incompatible
published paths or workflows, minor for compatible additions, and patch for
corrections preserving the intended agreements. Project Structure's adopted
version in [.project-structure.yaml](../.project-structure.yaml) changes only
when a newer starter baseline is deliberately adopted.

Finalize the model's release line, README and deliverables version links,
dated changelog entry and relevant decisions. Keep the initial release date
and earlier release records intact. Commit the intended files with a subject
and explanatory body, then create an annotated `vMAJOR.MINOR.PATCH` tag on that
exact commit. The hosted release must use the same tag. Released tags stay
fixed; corrections receive a new version.

## Verify Publication and Handover

Use the [release checks](../tests/README.md#release-checks) to verify the actual
stable publication, remote tag and commit, notes, versioned files and current
links. A local tag or a successful push alone does not establish publication.
Distinguish a published result from acceptance or successful use by another project.

After verification, complete any applicable publication handoff. Keep private
operational records outside public files. The maintainer retains responsibility
for subsequent corrections and feedback; adopter projects choose their own
authorized timing for upgrades.

## Version 2 Layout Change

From v2.0.0 the canonical model and PNG files live under `deliverables/`.
The former [model location](project-execution-model.md) provides forwarding
links. Earlier tag URLs keep their files unchanged, including the v1.0.0
baseline. Direct image and diagram-source URLs on a moving branch have changed;
the forwarding document is not a byte-compatible replacement for the old raw
model URL. Consumers of those paths need to use the new locations or a pinned
earlier release.
