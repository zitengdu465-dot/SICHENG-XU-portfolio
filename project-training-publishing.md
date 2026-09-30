# Training Publishing and Quality Checks

[Portfolio home](README.md) · [All projects](CATALOG.md)

Python tooling for recurring course publication, paired with checks for layout, contrast, stale references and information preservation.

**Technologies:** Python · python-pptx · PDF tools · Shell

**Status:** Used in the local publishing workflow; content and tooling continue to evolve.

## Problem

Maintaining a large course collection requires more than consistent styling. Revisions can introduce clipped text, unreadable colour combinations, copied lesson names or missing numerical qualifications.

## My work

- Developed shared slide-building functions and separated lesson metadata, page content and reusable layout code.
- Assembled a build sequence for PPTX generation, PDF conversion and visual contact sheets.
- Created checks for rendered text overlap, boundary violations, contrast, line-start punctuation and stale lesson names.
- Added a before/after information comparison for numbers, units, references, headings and qualifying language.

## Evidence and results

A direct inventory on 29 September 2026 found 50 PPTX files containing 1,100 slides, alongside 150 PDF files in the current course delivery directory. These counts describe the collection size, not proof of approval or a fresh page-by-page audit.

## Scope and limitations

Some scripts contain environment-specific paths. Checks combine deterministic rules with review heuristics; they support human review and do not prove content accuracy. Runtime configuration and error propagation need review before distributing the build workflow.

## Source availability

This page is a project case study. Implementation repositories and business source materials are not included in this portfolio.
