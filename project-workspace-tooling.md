# Workspace Intake and Health Checks

[Portfolio home](README.md) · [All projects](CATALOG.md)

Python tools that inventory incoming files, suggest destinations and check the integrity of a structured working directory.

**Technologies:** Python · SHA-256 · JSON · Markdown · macOS scheduling

**Status:** Implemented internal utilities. The intake monitor operates in preview mode.

## Problem

A growing working directory accumulates source files, previews, revisions and delivered documents. Manual filing makes it easy to lose provenance or confuse a candidate version with an accepted deliverable.

## My work

- Implemented intake scanning with file metadata, SHA-256 hashes, naming checks and destination suggestions.
- Created a state fingerprint and Markdown/JSON reports for subsequent review.
- Kept the background monitor in preview mode, without moving, renaming, overwriting or deleting incoming files.
- Developed separate checks for index links, unexpected root items, unlisted projects and duplicate-file relationships.

## Evidence and results

The monitor and health-check implementations are present with usage instructions and background-task configuration scripts. The monitor source contains scanning, hashing, state and report-generation functions.

## Scope and limitations

Destination suggestions use explicit rules and require interpretation for ambiguous files. This project is not an autonomous semantic document classifier, and the current configuration is tailored to one workspace.

## Source availability

This page is a project case study. Implementation repositories and business source materials are not included in this portfolio.
