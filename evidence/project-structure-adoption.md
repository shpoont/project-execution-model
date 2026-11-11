# Project Structure Adoption Checks

This is the pre-publication source and navigation record for PEM v2.0.0's
repository-layout change, compared with [v1.3.2](https://github.com/shpoont/project-execution-model/tree/v1.3.2).
Publication and downstream adoption need their own readback; this record does
not claim either outcome.

## Preserved Sources

The complete model was compared byte for byte after replacing only its release
line with the same fixed marker in both versions. The normalized bodies have the same SHA-256:

```text
731f41094cd53e3eb925c5b4663bb815ea360d30b5b1c875c1da5f76556bf61a
```

The candidate model's complete SHA-256 file hash is

```text
8c01ccfaf7885619a2a85214a345d59928c74da32060f9b0931b2c08ec2c3757
```

The five PNGs match their v1.3.2 Git originals byte for byte at the new locations.
This comparison uses repository bytes, not image copies processed by a review
service; a visual review of such copies cannot establish binary identity.

| Image in `deliverables/assets/` | SHA-256 |
| --- | --- |
| `cafe-define.png` | `dd70f7acc7ad15e96359dd003a69691a6ab5816347338e20645905bc553e0e05` |
| `cafe-deliver-learn.png` | `65b7f4990594a702de8191ace144274e2a75f3267702189653afef39a61cb77c` |
| `cafe-design.png` | `b89310daedccc15f107445055fd3d9551d8bd77ceefc001f772b76c2534fd8e0` |
| `cafe-implement.png` | `4b6836baf3ece7ddf0e721b47b539a4e5740fa7cea0bcd18dc1f1e8f2d6f7f92` |
| `project-execution-model-overview.png` | `22a83f3f857033a8026ccb98696841e3a962195c35b47ed6d55f246484ba794f` |

The overview HTML also matches its earlier source. The README's model summary,
legal text, author, initial date and earlier release entries are preserved.
Earlier decisions differ only in current-guidance link destinations. All ten
pre-existing tag objects remain unchanged; the v1.0.0 baseline is retained.
The local publication instructions were preserved without being copied into
public records.

## Links and Lookup Checks

All local Markdown references and heading targets resolved in the proposed
files. The old model page retains forwarding routes for the original headings.
A local Chrome preview rendered all fifteen Markdown pages at desktop and
phone widths without horizontal page overflow; the model's five images loaded.
Nine navigation checks passed, covering:

- README to published results and the maintained model.
- Reader access to all five illustrations.
- Contributor guidance to current work and agreements.
- Repository guidance to checks and delivery.
- The former model path to the moved Prepare Tests section.
- Working-material guidance to the editable diagram.
- A model link opening initially collapsed implementation-contract guidance.

The preview rewrites Markdown links to its local rendered pages. These checks
exercise the proposed routes and presentation; they do not certify GitHub's
hosted rendering or assistive-technology behavior. The published tag links are
verified separately when the release exists.

## Scope and Remaining Limits

Source-reference safety, starter provenance, intended file scope and
`git diff --check` passed. Project Structure 1.1.0 is the repository baseline;
PEM 2.0.0 is the separately versioned published result.

The former Markdown location is a forwarding document, not a raw-compatible
copy. Direct main-branch image and diagram-source paths change; earlier release
URLs stay fixed. See [delivery](../docs/delivery.md#version-2-layout-change).

These are source, rendering and simulated lookup checks. They do not demonstrate
understanding by people unfamiliar with PEM, real-project effectiveness or
adopter migration. The [checks guide](../tests/README.md) explains the assessment.
The [verification record in issue #31](https://github.com/shpoont/project-execution-model/issues/31)
identifies the reviewed sources, results, limits and implementation pull request.
