# HTML Letter Lab

INST630 Homework 1: mark up a supplied letter with semantic HTML, connect its
provided CSS, include a local image, and publish the result with GitHub Pages.

## Files

- `tutorial_1.html`: complete supplied letter with semantic HTML and CSS classes.
- `tutorial_1_letter_styles.css`: supplied stylesheet, preserved unchanged.
- `microscope.png`: local microscope illustration, displayed at 90 by 112 pixels.

Keep the HTML, stylesheet, and `microscope.png` in the same folder for grading.
The image must accompany the HTML submission or its relative path will break.

## Preview

Open `tutorial_1.html` in a browser, or use VS Code Live Server. No build step or
project dependencies are required. The HTML links the supplied stylesheet
using a relative path.

## Status

GitHub Pages deployment remains to be completed. Styled Safari screenshots
have been reviewed; the new image still needs browser verification. The university dates and dance research
references have no supplied URLs and remain plain text.

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
