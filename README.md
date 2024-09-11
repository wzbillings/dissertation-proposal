# Zane’s dissertation proposal

Dissertation proposal for Zane Billings prepared in the course of obtaining a
PhD in Epidemiology & Biostatistics from the University of Georgia. I was
supervised by [Andreas Handel, PhD](https://andreashandel.com).

The final document can be viewed [here](_book/proposal.docx).
The final presentation to accompany the text can be viewed
[here](proposal-slides-final-version.pptx).

Please feel free to contact me at wzbillings at protonmail dot com if you
have any questions.

## Overview

This repository contains all code, exploratory data analysis,
figure/table generation, and text for my **dissertation proposal**,
which I will interchangeably call my **prospectus.** From my
department’s handbook:

> The proposal will include research goals and aims, background and
> rationale, literature review, detailed description of methods
> proposed, and an analytic strategy.

## File structure

This repository is structured as a quarto book project.

* `_book`: contains the final rendered word document output by `quarto render`.
* `figures`: contains all images embedded in the document.
* `README.md`: contains the text you are reading now.
* `proposal-slides-final-version.pptx`: final version of slides presented based on this text.
* Main text sections:
  * `index.qmd`: frontmatter
  * `aims.qmd`: specific aims page
  * `significance.qmd`: significance section
  * `approach.qmd`: approach section
  * `references.qmd`: references and backmatter
* Other files needed for text rendering:
  * `aje.csl`: contains the CSL file for reference formatting.
  * `references.bib`: BibTeX file for generating bibliography.
  * `template.docx`: word template for specifying document formatting.
  * `_quarto.yml`: contains settings for `quarto render` to produce the book.
* Housekeeping and other not-important files
  * `innovation.qmd`: we decided I didn't need to include an innovation section and I forgot to remove this.
  * `notes`: miscellaneous files (todo archive elsewhere)
  * `refs`: more miscellaneous files (todo archive elsewhere)
  * `renv`: housekeeping directory where the `renv` cache and other files are stored.
  * `.Rprofile`, `README.qmd`, `renv.lock`, `_reqs.R`, `dissertation-proposal.Rproj`: housekeeping files

## Acknowledgements

This work would not have been possible without the following people, listed
in arbitrary order:
Ye Shen,
Amy Winter,
Natalie Dean,
Amanda Skarlupka,
Yang Ge,
Tzu-Chun Chu,
Veronika Zarnitsyna,
Savannah Hammerton,
Jessica Knight,
Meng-Hsuan Sung,
Steve Rathbun,
Mark Ebell,
Ted Ross,
Michael Carlock,
Andrea Sant,
Ben Cowling and lab group,
Sarah Cobey and lab group,
Nichole McCorkle,
the UGA Infectious Disease Interest Group,
the IMAG-MSM Immunology Subgroup,
funding from NIH CIVICs (CIVR-HRP) and CEIRR (CIDER),
and my Georgia Research Education Award Traineeship from the
UGA Graduate School.

## Licensing

All figures and text created by me are licensed under the
[CC-BY-SA-NC 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.en)
Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license.
Some figures were generated using biorender.com with a professional plan and are
licensed for reuse under the terms and conditions of the biorender license.
Any third-party materials were reused under the conditions of their own license
or under free use for educational purposes. I do not retain the license to any
materials not created by me.


<!-- End of file -->
