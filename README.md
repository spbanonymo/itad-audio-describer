# Iterative Timestamped Audio Describer — Interactive Demos

Self-contained interactive demos accompanying the paper submission. Open `index.html`
or visit the hosted page. All assets are local; there are no external dependencies.

## Demos

| Page | What it shows |
|---|---|
| `viewers/describer_passes.html` | One clip described incrementally, one pass at a time. |
| `viewers/understand_all.html` | Describe-then-reason across four benchmarks: MMSU, MSU-Bench, Daily-Omni, Video-Holmes. |
| `viewers/gen_emphasis.html` | Word-level emphasis control driven from the caption text. |
| `viewers/gen_reconstruction.html` | Real clip → structured description → re-generated audio. |

Each input is described once, question-agnostically, with timestamps. A frozen
text-only reasoner — which never sees or hears the raw signal — then answers from
that description alone.

## Source material

The audio and video excerpts shown here are taken from publicly released research
benchmarks (MMSU, MSU-Bench, Daily-Omni, Video-Holmes) and are reproduced solely to
illustrate model behaviour for peer review. All rights remain with the original
dataset and content authors.
