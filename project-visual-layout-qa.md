# Visual Alignment and Clearance Inspector

[Portfolio home](README.md) · [All projects](CATALOG.md)

An image-analysis utility for measuring visual balance, apparent edges and clearance inside a layout container.

**Technologies:** Python · Image analysis · Command-line tooling

**Status:** Implemented utility; a benchmark across unrelated layouts has not been prepared.

## Problem

Geometric centring does not always look visually centred. Rounded containers and uneven content distribution also complicate measurements based on simple bounding boxes.

## My work

- Developed background estimation using middle sections of container edges rather than corner pixels.
- Measured perceptual content edges on a blurred image and clearance on the original image.
- Implemented rounded-container masks, visual-centroid measurements and annotated output.
- Reported numerical deviations while leaving design-intent decisions to the reviewer.

## Evidence and results

The source separates background estimation, masking, measurement, annotation and clearance reporting. It also documents a failure case involving rounded-container corners.

## Scope and limitations

The method relies on assumptions about the background and content contrast. Its measurements inform layout review; they do not provide a universal aesthetic score.

## Source availability

This page is a project case study. Implementation repositories and business source materials are not included in this portfolio.
