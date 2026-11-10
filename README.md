# CTI Research Library

A public, searchable and version-controlled literature index maintained by **Community Trust Infrastructure**.

**Website:** https://communitytrustinfra.com/  
**GitHub repository:** https://github.com/Community-Trust-Infrastructure/cti-research-library

## Overview

The library explores research on community finance, trust, attestations, governance, tokenization, digital payments, AI and accountable capital allocation. It is inspired by the usability of [Design Reservoir](https://brandiejanow.github.io/design-reservoir/) but uses its own design and implementation.

**Version 0.1:** A starter collection of 10 source-linked records. It is not yet the complete historical CTI Literature Index. Summaries and CTI relevance are editorial notes; inclusion does not imply endorsement by the cited institutions. Some dates are recorded by year pending detailed citation review.

## Website features

- Full-text keyword search
- Research theme and evidence-type filters
- Sort by publication year or title
- Pagination and mobile-responsive layout
- Original source links and separate CTI relevance summaries

## Data

The master file is [data/literature.json](data/literature.json). Each record has a stable ID, title, author/institution, year, category, resource type, region, URL, summary and CTI relevance.

To add a source, insert a new object in the `resources` array. Validate the original link and publication metadata first. Avoid copying long copyrighted passages; write original summaries.

## Publish via GitHub Pages

In this repository, open **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, and save. The intended URL is:

https://community-trust-infrastructure.github.io/cti-research-library/

No build tools or dependencies are required.

## Contributions

Suggest sources or corrections using [GitHub Issues](https://github.com/Community-Trust-Infrastructure/cti-research-library/issues/new). See [Methodology](methodology.html).

No code/content license has been selected yet. External research remains the property of its original publishers.
