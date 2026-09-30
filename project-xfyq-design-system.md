# Cross-media Design System

[Portfolio home](README.md) · [All projects](CATALOG.md)

A React and TypeScript component library with semantic design tokens for web, print, slides and documents.

**Technologies:** React · TypeScript · CSS · tsup · Node.js

**Status:** Implemented library; token lint and TypeScript checks passed on 29 September 2026.

## Problem

A single brand needs consistent visual rules across screens, printed materials, slide decks and long documents. These formats share colours but require different sizes, spacing and presentation rules.

## My work

- Developed a semantic token layer so components consume visual roles instead of hard-coded brand colours.
- Implemented 19 exported React components with TypeScript interfaces, including data cards, comparison tables, process chains and charts.
- Added four media modes and two theme presets, with HTML and React sharing the component stylesheet.
- Wrote a static checker that flags raw-colour references and hard-coded hex colours in component code.

## Evidence and results

The local package includes component documentation, a style guide, CSS/JSON tokens, declaration files and build scripts. The token checker scanned 22 files successfully; TypeScript completed with no reported errors.

## Scope and limitations

These checks cover the token rules and type consistency. They do not establish that every component layout or accessibility requirement has been verified. The local README also records remaining styling issues.

## Source availability

This page is a project case study. Implementation repositories and business source materials are not included in this portfolio.
