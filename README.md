# HTML Letter Lab

INST630 Homework 1: mark up a supplied letter with semantic HTML, connect its
provided CSS, include a local image, and publish the result with GitHub Pages.

## Files

- `index.html`: complete supplied letter with semantic HTML and CSS classes.
- `tutorial_1_letter_styles.css`: supplied stylesheet, preserved unchanged.
- `microscope.png`: local microscope illustration, displayed at 90 by 112 pixels.

Keep the HTML, stylesheet, and `microscope.png` in the same folder for grading.
The image must accompany the HTML submission or its relative path will break.

## Preview

Open `index.html` in a browser, or use VS Code Live Server. No build step or
project dependencies are required. The HTML links the supplied stylesheet
using a relative path.

## Status

GitHub Pages is deployed. The live HTML, CSS, and PNG returned HTTP 200 with
correct content types and matched the local files byte for byte on September
10, 2026. Local Safari screenshots confirm both styling and microscope rendering.
Live browser appearance and Developer Tools checks remain pending. The university
dates and dance research references have no supplied URLs and remain plain text.

## Check the styles

Reload the letter after saving changes. In browser Developer Tools, open Network
and reload again to check that `tutorial_1_letter_styles.css` loads. Inspect the
subject heading and confirm that `.letter-subject` supplies its blue color.
Inspect the greeting to see both `.letter-paragraph` and `.letter-greeting`.

The semester and research lists carry their classes on `ul` and `ol`. The
stylesheet targets their items through `.semester-dates li` and
`.priority-list li`; those items do not need an additional class.

## Image source

`microscope.png` is an unchanged local copy of
[Microscope icon.png](https://commons.wikimedia.org/wiki/File:Microscope_icon.png)
from Wikimedia Commons. The page credits Musaromana for the original image and
MaxBet for removing the background, and lists the image as public domain.

The HTML supplies alternative text describing the microscope and explicit
width and height matching the source image. Reload the page to confirm it
appears above the letter. In Developer Tools, check that `microscope.png` loads
and that the image has natural dimensions of 90 by 112 pixels.

## Submission and deployment

Submit `index.html` with `microscope.png`, keeping both beside
`tutorial_1_letter_styles.css`. The HTML was renamed from `tutorial_1.html` so
GitHub Pages can use it as the site entry page. Its content and relative asset
paths are unchanged.

For GitHub Pages, publish from the `main` branch and the repository root (`/`).
No custom build workflow is needed.

- [Repository](https://github.com/kennethyeaher/KY_htmlLab)
- [Live letter](https://kennethyeaher.github.io/KY_htmlLab/)

The Pages build and deployment passed. GitHub reported a Node deprecation warning
in its managed build workflow; the lab itself has no Node dependency.

The assignment calls Pages optional, but its rubric assigns deployment four
points out of twenty. Deployment is therefore included in the submission plan.

| Rubric criterion | Current evidence |
| --- | --- |
| Semantic HTML structure | Text preservation and structure checks passed; Safari screenshots reviewed. |
| Image inclusion | Live PNG returned HTTP 200 and matched the local file; local Safari rendering confirmed. |
| CSS linking | Live CSS returned HTTP 200 and matched the supplied stylesheet; local styled Safari screenshots reviewed. |
| CSS classes | All 26 supplied class names applied; element mappings checked. |
| GitHub Pages | Deployment passed; live HTML and both assets returned HTTP 200 and matched local files. |
