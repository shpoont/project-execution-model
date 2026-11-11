# Checks and Reviews

Checks start from the expectations agreed in the issue or pull request. Prepare
the relevant assessment before making the change it guides. Use checks suited
to the change: a moved file needs navigation and asset checks, while revised
guidance also needs assessment of meaning and reading.

## Text and Source Checks

For a model revision, compare complete before-and-after sources, including the
necessary images. Check rules, conditions, exceptions, responsibilities, timing
and evidence limits, as well as examples and their implications. Keep a source
identifier for each review. For a layout-only move, verify the model text and
image bytes directly rather than infer preservation from a rename.

Check terminology and cross-references in context. For new or substantially
changed guidance, a reader review should show understanding and a plausible use,
with reading difficulties and limits retained separately from preservation.

## Links and Reading Format

Check local Markdown targets, heading anchors and all image references. Open
the rendered result to assess layout and follow important routes: from README
to the published model, from a work agreement to its checks, and from the
repository guide to delivery and decisions. Check initially collapsed guidance
where relevant. Source search alone does not demonstrate a usable route.

For a move, check forwarding links and document any changed raw-file paths.
Compare the images at their new locations and retain alternative text.
Run `git diff --check` and inspect the exact intended change before committing.

## Release Checks

Before tagging, check that the model release line, README, deliverables page,
changelog and decisions agree. Check the separate Project Structure provenance,
the license and initial date, private-reference safety, intended file scope and
unchanged earlier tags. Follow the [delivery procedure](../docs/delivery.md).

After publication, read back the actual release: stable/draft status, tag,
commit, notes, and versioned model and asset URLs. Verify published files against
the intended bytes, confirm the appropriate latest-release status and check that
the local branch is synchronized. Keep publication, downstream receipt and
actual adoption distinct.

## Results and Limits

Record each result with the source or version, conditions, method and remaining
uncertainty. Keep passed, failed and pending results distinct; a failed attempt
at assessment is not automatically a failed criterion or a pass. Carry findings
back to the affected agreement before choosing a remedy.

Retain useful evidence through the [evidence guide](../evidence/README.md).
Reviews, source checks and hypothetical cases do not demonstrate how people
unfamiliar with PEM understand and use it, or improved outcomes in actual projects.
