# Crick-UCLH-Legacy-mucosal-neutralisation-2023-12
Crick-UCLH-Legacy-mucosal-neutralisation-2023-12

This repository contains data and code to support:

Please cite the paper if you re-use data or code.


### Notes

1. The paper was written using quarto [https://quarto.org].

__In short__: refer to the text of the citation above, not this repository.

Quarto links the manuscript text, R code and results in a single file (`.qmd`) which generates a single `.docx` with embedded figures.

The supplementary text was written separately in Word, and relevant quarto figures moved over to the supplementary docx.

The provided `.qmd` file contains:
- the approved-by-reviewers main text.
- It does not contain journal edits, or corrections or typographical fixes + clarifications at the proofing stage (eg a reference is duplicated).
- Additionally, there are advanced formatting options like two sets of authors with equal contribution that quarto does not yet support - we added these in Word before submission.

All R code to draw plots and generate statistics is housed within the `.qmd` file.

The `.docx` file is generated when `.qmd` is rendered, using the other supporting files in this repository.


2. The public data has some redactions

We have removed age and gender (only used in table 1), and generated new identifiers for study participants, and new identifiers for barcodes. Only data columns required for the manuscript are included.

The code for table 1 is provided, but not executed.
