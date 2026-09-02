# Alan Lyu CV

This directory contains the editable LaTeX source for Alan Lyu's compact CV. The template uses a 10 pt article layout, narrow list spacing, blue links, and section rules. The section bodies are intentionally empty so their titles, order, and content can be rebuilt from scratch.

## Preview locally

From this directory, run:

```bash
make build
```

The preview PDF will be generated at `build/Alan_Lyu_CV.pdf`. Building a preview does not change the CV shown on the website.

## Publish to the homepage

After checking the preview, run:

```bash
make publish
```

This compiles the CV and copies it to `assets/pdf/Alan_Lyu_CV.pdf`, which is linked from the About page. Then commit and push the LaTeX source, the updated PDF, and the About page when its download link changes:

```bash
git add cv/latex assets/pdf/Alan_Lyu_CV.pdf _pages/about.md
git commit -m "Update CV"
git push origin main
```

## Requirements

The build uses [Tectonic](https://tectonic-typesetting.github.io/), which is already installed on this computer.
