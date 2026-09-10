# HTML Letter Lab

INST630 Homework 1: mark up a supplied letter with semantic HTML, connect its
provided CSS, include a local image, and publish the result with GitHub Pages.

## Files

- `tutorial_1.html`: complete supplied letter with semantic HTML and CSS classes.
- `tutorial_1_letter_styles.css`: supplied stylesheet, preserved unchanged.

Keep the HTML and stylesheet in the same folder for grading.

## Preview

Open `tutorial_1.html` in a browser, or use VS Code Live Server. No build step or
project dependencies are required. The HTML links the supplied stylesheet
using a relative path.

## Status

A local image and GitHub Pages deployment remain to be completed. Final browser
and asset verification are pending. The university dates and dance research
references have no supplied URLs and remain plain text.

## Check the styles

Reload the letter after saving changes. In browser Developer Tools, open Network
and reload again to check that `tutorial_1_letter_styles.css` loads. Inspect the
subject heading and confirm that `.letter-subject` supplies its blue color.
Inspect the greeting to see both `.letter-paragraph` and `.letter-greeting`.

The semester and research lists carry their classes on `ul` and `ol`. The
stylesheet targets their items through `.semester-dates li` and
`.priority-list li`; those items do not need an additional class.
