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

## Deployment (GitHub Pages)

This is a plain static site, so GitHub can serve it directly from the branch — no build
step. To turn it on (one time):

1. Go to **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Set **Branch** to `claude/portfolio-github-pages-02kn7x` and the folder to **`/ (root)`**, then **Save**.

The site publishes at
https://crnazar.github.io/interdisciplinaryteachingportfolio/ within a minute or two,
and rebuilds automatically on every push. The `.nojekyll` file tells Pages to serve the
files as-is.
