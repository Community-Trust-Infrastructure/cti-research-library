# CTI Research Library

A public, searchable and version-controlled literature index maintained by **Community Trust Infrastructure**.

**Website:** https://communitytrustinfra.com/  
**GitHub repository:** https://github.com/Community-Trust-Infrastructure/cti-research-library

## Overview

The library explores research on community finance, trust, attestations, governance, tokenization, digital payments, AI and accountable capital allocation. It is inspired by the usability of [Design Reservoir](https://brandiejanow.github.io/design-reservoir/) but uses its own design and implementation.

**Version 0.2:** 21 source-linked research records, with the 11-category CTI Literature Index v2.0 taxonomy preserved in `data/taxonomy.json`. It is not yet the complete historical CTI Literature Index. Summaries and CTI relevance are editorial notes; inclusion does not imply endorsement by the cited institutions. Some dates are recorded by year pending detailed citation review.

## Origins and acknowledgments

Community Trust Infrastructure (CTI) has developed through research and practical experimentation undertaken within **All In For Sport (AIFS)**. AIFS has provided an important collaborative setting for exploring community governance, verification, coordination and more equitable approaches to resource allocation. Learning from AIFS collaborations, including with **Sarreya Sport** in Somaliland, has informed the architecture's research questions and implementation safeguards. These observations do not imply that partners endorse every CTI proposition or that the architecture is independently validated.

CTI's research scope extends beyond sport and beyond the AIFS case studies. It is an open, technology-agnostic architecture intended for critique and comparative testing across governance, evidence, privacy, AI-assisted interpretation, community finance and capital allocation. Those research directions may, in turn, create opportunities for AIFS and other collaborators to test and innovate. Research authorship, organizational contributions and community-generated knowledge should be attributed distinctly, with partner consent and autonomy respected.

## Website features

- Full-text keyword search
- Research theme and evidence-type filters
- Sort by publication year or title
- Pagination and mobile-responsive layout
- Original source links and separate CTI relevance summaries

## Data

The searchable master file is [data/literature.json](data/literature.json). Related registers are [applied cases](data/applied-cases.json), [Canada–EU monetary interoperability](data/canada-eu-research.json), and [the 11-category taxonomy](data/taxonomy.json). These are intentionally separate from the public literature directory until reviewed.  Each record has a stable ID, title, author/institution, year, category, resource type, region, URL, summary and CTI relevance.

To add a source, insert a new object in the `resources` array. Validate the original link and publication metadata first. Avoid copying long copyrighted passages; write original summaries.

## Publish via GitHub Pages

In this repository, open **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, and save. The intended URL is:

https://community-trust-infrastructure.github.io/cti-research-library/

No build tools or dependencies are required.

## Contributions

We invite research, critical perspectives, alternative approaches, case studies and architectural challenges. Read [Contributing to CTI](CONTRIBUTING.md) for separate pathways for literature suggestions, architecture discussions and field learning, as well as stewardship, review, consent and attribution safeguards. Open a [GitHub Issue](https://github.com/Community-Trust-Infrastructure/cti-research-library/issues/new) to get started. Inclusion in the literature index does not imply endorsement or incorporation into the CTI architecture. See [Methodology](methodology.html).

No code/content license has been selected yet. External research remains the property of its original publishers.

## Analytical research notes

Five working research notes now live in [`research-notes/`](research-notes/): [BIS measurement](research-notes/bis-measurement.md), [Moneta adoption](research-notes/moneta-adoption.md), [Canton/Broadridge interoperability](research-notes/canton-broadridge.md), [ENS governance](research-notes/ens-governance.md), and [CSA tokenization](research-notes/csa-tokenization.md). Each distinguishes the source's contribution, CTI interpretation, evidence limitations, testable questions and outstanding bibliographic verification. Four notes are linked from matching directory entries; Canton/Broadridge awaits a verified primary-source citation before adding a new literature entry.

These are **working analytical notes**, not completed source-critical reviews. Do not present unverified findings as established empirical evidence.

## Core CTI manuscript

[**Community Trust Infrastructure V2.2 — An Open Reference Architecture for Portable Operational Trust**](manuscripts/cti-v2.2.md) is the November 2026 public research edition. The linked page is an **editorial guide**, not the complete 10-page PDF. The authoritative PDF was supplied in the research conversation but has **not yet been uploaded to this repository**; please do not cite the guide as the full manuscript.

The V2.2 edition integrates the CTI functional architecture, Sarreya observations, SportFi evaluation questions and an institutional comparison to [World Bank FundsChain](research-notes/world-bank-fundschain.md). Canada–EU monetary interoperability remains a separate exploratory branch.
