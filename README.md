# Teaching Portfolio — Christina Restrepo Nazar, Ph.D.

A digital-humanities teaching portfolio built as a static site and deployed to GitHub Pages.

**Live site:** https://crnazar.github.io/interdisciplinaryteachingportfolio/

## What's here

| Page | File |
|------|------|
| Home | `index.html` |
| Teaching Statement | `teaching-statement.html` |
| Encountering the World (syllabus) | `syllabus.html` |
| The Field Log and Its Double (signature assignment) | `signature-assignment.html` |
| Curriculum Vitae | `cv.html` |
| Reflection | `reflection.html` |

Shared styling lives in `css/style.css`.

## Design

A warm, boho / borderlands aesthetic — cream backgrounds, terracotta, ochre, sage,
teal, and plum accents, organic arch shapes, and a repeating "seam" motif that echoes
the portfolio's organizing idea: *what the machine cannot cross*, the border between
lived and machine knowledge. Display type is Fraunces; body type is Mulish.

## Building

The pages are plain HTML/CSS with no build step required to view. They were generated
from a single Python script so the shared navigation, header, and footer stay
consistent across pages.

## Deployment

`.github/workflows/pages.yml` publishes the site to GitHub Pages on every push to the
project branch (and `main`). The workflow auto-enables Pages the first time it runs.
