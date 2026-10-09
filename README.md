# How access works at NCSA — current state

A single-page, plain-language guide to the systems that turn an approved allocation
into a working account at NCSA.

**Audience:** anyone at NCSA who is technically inclined but is not a systems
administrator — people who keep hearing "IDDS," "acctd" or "charge group" and have
never been told what they are.

It is a knowledge-sharing reference, not an administration guide and not a design
proposal. It describes current state only.

## What's in it

- **Start here** — the five stages every access path passes through, and the three
  components that carry most of the weight.
- **By system** — the practical page. Pick a resource (Delta via ACCESS, Delta via
  Illinois Computes, DeltaAI, Radiant, Nightingale/ACHE, Illinois Campus Cluster,
  Taiga, Granite) and see the path a request actually takes through it, step by step,
  with each step marked automated, manual or absent.
- **The pieces** — one card per component: what it does, and what it is commonly
  assumed to do but does not. Filterable by stage.
- **Logins & identity** — which credential opens which door, and why nothing
  reconciles them.
- **Glossary** — every acronym decoded.

## Running it

`index.html` is a single self-contained file. No build, no dependencies, no network
calls. Open it locally or serve the directory; GitHub Pages works as-is.

## Provenance and caveats

Content is derived from the NCSA IAM and access discovery record as of October 2026 —
internal documentation plus read-only inspection of live systems. Some of it is
documented but not independently confirmed; those places are marked on the page.
Where the record itself is contradictory (provisioning cadence, for instance), the
page describes the behaviour rather than quoting a disputed figure.

Corrections to the boundaries are more valuable than added detail. Open an issue, or
email Chris Keeley directly at keeley4@illinois.edu.

## Related

This grew out of the "Request to Access" current-state walkthrough prepared for CI
Directors (`keeley4/iam_access_modernization_discovery`), which was built for a
leadership audience and a specific decision. This repository is the general-purpose
version: same evidence base, different job.
