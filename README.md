# GCC of CI — Image Assets

Public asset repo, separate from the private `gcc-of-ci-pipeline` automation repo.
Holds only images (carousel cards, covers) that need a stable, publicly-fetchable
URL for the Zernio API to pull from when posting to Instagram. No automation
logic, tokens, or business content lives here — just images.

Rendered carousel cards come from `gcc-of-ci-pipeline`'s
`templates/carousel/render.mjs`.
