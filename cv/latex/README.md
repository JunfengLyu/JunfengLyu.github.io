# Alan Lyu CV

This directory contains the editable LaTeX source for Alan Lyu's CV. It is based on the official [ModernCV](https://github.com/moderncv/moderncv) template and uses the `classic` style with a blue accent.

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

This compiles the CV and copies it to `assets/pdf/Alan_Lyu_CV.pdf`, which is the file linked from the About and CV pages. Commit and push both the LaTeX source and the updated PDF:

```bash
git add cv/latex assets/pdf/Alan_Lyu_CV.pdf
git commit -m "Update CV"
git push origin main
```

## Requirements

The build uses [Tectonic](https://tectonic-typesetting.github.io/), which is already installed on this computer.
