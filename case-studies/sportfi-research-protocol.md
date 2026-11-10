# SportFi — Research and Evaluation Protocol

**AIFS × Women Win × participating communities**  
**Working draft v0.1 — 10 November 2026**  
**Status: Team review required; not an approved protocol, final implementation specification or outcome report.**

> **Publication and consent caution:** This draft is held in a **public GitHub repository** for collaboration. It deliberately excludes wallet addresses, private contacts, participant-level data, security procedures and non-public financial details. Community partners and Women Win should approve external descriptions, data handling and attribution before wider circulation. Public access does not imply partner endorsement.

## 1. Purpose

SportFi is an applied experiment in **community-governed finance and evidence infrastructure**, using grassroots sport as a setting. It explores whether communities can produce useful, verifiable evidence of their own activities while retaining authority over interpretation and disclosure—and whether this evidence changes how funders understand, authorize or allocate resources.

SportFi is **not** a claim that yield generation, tokenization, AI or an attestation system has already demonstrated improved community outcomes. It is a test environment that can refine the technology-neutral **Community Trust Infrastructure (CTI)** reference architecture.

**Research sequence:** Architecture → Pilot implementation → Evidence and learning → Revised architecture → Potential adoption.

## 2. Research proposition

**Primary question:** Does a lightweight, community-authorized signal and attestation process produce evidence that funders can use for more accountable, responsive capital allocation **without increasing reporting burden or weakening community autonomy**?

### Sub-questions

1. **Evidence:** Are activity signals sufficiently complete, retrievable, interpretable and correctable?
2. **Authority:** Can community members establish who may attest, validate, approve, contest and revoke?
3. **Usefulness:** Do funders actually make different or better-reasoned decisions with this evidence compared with conventional reporting?
4. **Burden:** What are the total time, training, maintenance, privacy and governance costs for communities?
5. **Portability:** Can the architecture work in Somaliland and Bolivia while preserving different local governance and communication practices?
6. **Capital flows:** Can a modest yield-funded distribution mechanism operate reliably and transparently without creating new dependency or unacceptable financial risk?
7. **Equity:** Who is excluded, overburdened or exposed by the workflow, including people without compatible devices or financial literacy?

## 3. Pilot scope and current status — confirm with team

| Element | Current working understanding | Verification needed |
| --- | --- | --- |
| Lead collaboration | AIFS and Women Win | Contractual and communications roles |
| Community settings | Sarreya Sport (Somaliland) and Ayni Skate Project (Bolivia) | Community consent, representatives, precise scope |
| Funding envelope | USD 60,000: approximately USD 10,000 build/operations and USD 50,000 capital base | Approved budget and restrictions |
| Planned period | 2026 through 31 January 2027; earlier drafts differed on start date | Actual start, milestones, end date |
| Capital status (November update) | Capital reportedly deployed; multisignature authority being finalized | Exact meaning of deployed, control structure, dates |
| Next milestone | Target around 15 November 2026 for tokens to reach user wallets | Confirm whether target remains current; do not imply completion |
| Evidence layer | Witness / Prueba signals and steward attestations | Production status, consent, validation implementation |
| Financial layer | Yield / distribution mechanism with Bread Cooperative-related infrastructure under discussion or implementation | Actual rails, asset exposure, custodial responsibilities and payout mechanics |
| Interfaces | Community messaging, steward workflows and funder-facing reporting | Which interfaces are operational versus planned |

**Important:** The September 2026 Bolivia meeting notes discuss a potential USD 500/month distribution and specific wallet/DeFi arrangements. These remain **design discussions**, not verified distribution results or final commitments. Do not describe a fixed yield, guaranteed monthly amount or risk-free principal.

## 4. Evaluation design

This is a **prospective mixed-methods feasibility study**, not a randomized trial. The unit of analysis is the community workflow and allocation decision, not individual participant worth or a numerical trust score.

### 4.1 Baseline (before each community's first active evaluation cycle)

Record:
- Existing reporting workflow, typical staff/steward hours, and which reports are actually used by funders.
- Existing governance: decision authority, approval thresholds, dispute handling, record access and consent.
- Available connectivity, devices, preferred communication channels, payment and cash-out options.
- Community-defined activities worth recognizing; explicitly record activities that should **not** be captured.
- Existing funding decision cadence, documentation requirements and common delays.
- Pre-specified costs and risks of the proposed technical and human processes.

If baseline data cannot be collected retrospectively with reasonable confidence, mark it **missing**; do not invent a pre-pilot comparison.

### 4.2 Observation and data collection

Use the least intrusive combination of:
- **Aggregate workflow logs:** timestamps, completion/error status, non-identifying record identifiers, correction events.
- **Steward journals:** time spent, assistance provided, disagreements, escalations and failure modes.
- **Community feedback:** voluntary short interviews or discussions, including dissent and accessibility barriers.
- **Funder decision logs:** what information was reviewed, what decision was made, why, and whether evidence changed the decision.
- **Financial reconciliation:** aggregate intended versus actual distributions, delays, fees and failed transactions.
- **Technical acceptance tests:** signer authorization, revocation, retrieval, privacy controls and recovery from provider outages.

**No participant-level records or identifiable photos should be put into the public CTI repository.** Consent, retention and removal protocols require community approval before data collection.

### 4.3 Cross-context comparison

Compare **functional requirements** across Sarreya and Ayni, not community performance rankings. A common schema may capture activity, provenance, consent and authorization while leaving locally meaningful definitions and decision rules to each community.

Document every context-specific adaptation, engineering hours, translation and steward support. An internal working threshold of **more than two weeks of bespoke engineering for Bolivia** is a useful review trigger from the CTI thesis, **not a universal failure threshold**.

## 5. Measurement matrix

| Dimension | Suggested indicator | Evidence source | Interpretation / caution |
| --- | --- | --- | --- |
| Signal integrity | Share of sampled records complete and retrievable; corrections required | Technical audit | Completeness does not equal truth |
| Authorization | Share of attestations backed by valid, distinct mandates; revocation tests passed | Governance register + acceptance tests | Wallet control alone is insufficient |
| Community burden | Median minutes per report, confirmation and correction; steward support hours | Time diary + observation | Include unpaid labor and training |
| Accessibility | Completion and assistance rates by access mode, reported barriers | Voluntary feedback + aggregate logs | Do not create sensitive demographic profiles |
| Decision usefulness | Share of sampled funding decisions citing community evidence; documented change in reasoning | Funder decision log + interviews | Citation does not prove causality |
| Financial reliability | Intended vs. received distributions, fee share, delays, failed/reversed attempts | Reconciliation | Do not confuse yield with impact |
| Financial risk | Principal exposure, liquidity constraints, incidents and realized losses | Finance/risk register | No assumed guaranteed returns |
| Portability | Common schema fields retained, local modifications, engineering and training hours | Implementation log | A shared codebase is not proof of governance portability |
| Community agency | Who defines valid signals, who can challenge, withdraw consent or revoke authority | Governance review + interviews | Avoid treating token votes as universal legitimacy |
| Safeguarding | Consent adherence, unauthorized disclosures, resolution of complaints | Restricted safeguarding register | Public reporting must be aggregated and approved |

**Set denominators, sampling frequency, responsible stewards and data access rules before collection.** Record missing data explicitly.

## 6. Pre-registered decision and failure criteria (proposed)

The team should agree on these **before** evaluating results:

- **Evidence integrity:** Any irretrievable, falsely attributed or unauthorized claim used for an allocation decision triggers a pause and investigation.
- **Governance:** If a revoked or unauthorized signer can approve an attestation, the relevant workflow fails acceptance testing.
- **Safeguarding:** An unauthorized public disclosure of sensitive participant information triggers incident response and suspension of that publication path.
- **Reporting burden:** If total community time (including steward labor and training) exceeds the baseline without a community-endorsed benefit, the low-burden hypothesis is not supported.
- **Decision relevance:** If funders cannot identify a decision in which the evidence materially affected reasoning or action, the claimed allocation benefit remains unproven.
- **Portability:** Significant bespoke engineering, externally imposed governance rules or dependency on one irreplaceable operator weakens portability claims.
- **Financial viability:** Unreconciled distributions, unacceptable loss exposure, inability to redeem or significant operational dependence require redesign or discontinuation.

Do not define success solely as number of wallets, attestations, token transfers or nominal yield.

## 7. Financial architecture and risk boundary

Distinguish four separate questions:

1. **Capital generation:** Is yield generated, and at what financial, smart-contract, counterparty, liquidity and currency risks?
2. **Allocation authority:** Who decides the beneficiary, amount, timing and permitted use?
3. **Trust evidence:** What authorized, contestable information supports that decision?
4. **Settlement and receipt:** Did the intended recipient receive usable value, including access to local currency if required?

The pilot should disclose the difference between principal and distributed yield; who controls custody or signing; redemption and recovery options; fee drag; and the possibility of zero or negative net returns. Community members should not bear risks they have not been informed about or agreed to.

**No yield or payout is guaranteed by this research protocol.**

## 8. Ethical governance and data stewardship

Before data collection, participating communities should agree on:
- Which signals are worth capturing and which are out of scope.
- Who owns or controls records, who can access them and how they can be corrected or removed.
- Explicit consent for media and any data relating to minors or vulnerable participants.
- An accessible complaint/appeal process outside the technical platform.
- Compensation and recognition of steward labor.
- Conditions for public release, retention, deletion and third-party sharing.
- Authority to pause or withdraw from the experiment without losing unrelated support.

The research should not produce a universal community ranking, personal trust score, surveillance dashboard or automatic exclusion rule. AI may assist with organization and anomaly flagging, but consequential decisions remain with authorized people.

## 9. Roles and approvals (to assign)

| Decision or workstream | Proposed accountable party | Status |
| --- | --- | --- |
| Overall protocol, scope and budget | AIFS + Women Win | Confirm |
| Community research questions and consent | Sarreya / Ayni designated representatives | Confirm |
| Signal and attestation schema | Prueba / Witness technical leads | Confirm |
| Validation rules, signing and revocation | Community-authorized governance leads + technical leads | Confirm |
| Financial operations and risk register | Authorized multisig signers / finance leads | Confirm |
| Independent or external review | To be appointed if feasible | Open |
| Public release and safeguarding | Community representatives + AIFS + relevant partners | Approval required |

## 10. Reporting cadence and outputs

**At onboarding:** Baseline, consent and governance decisions, financial risk disclosure, test plan.

**During pilot:** Brief monthly learning memo, aggregate metrics, deviations, incidents, unresolved design decisions and changes to implementation. Record *negative* findings as carefully as successes.

**At closeout (planned January 2027, subject to confirmation):**
1. Evidence-quality and governance test results.
2. Full cost and reporting-burden comparison, including unpaid labor.
3. Funder decision-usefulness assessment.
4. Community feedback and portability analysis.
5. Financial reconciliation and risk outcomes.
6. CTI architecture changes and a decision on whether further pilots are justified.

## 11. Team review checklist

- [ ] Confirm funding agreement, actual dates, partner names and permissions.
- [ ] Confirm capital deployment, multisig and token-wallet status; remove obsolete targets.
- [ ] Confirm financial mechanisms and risk disclosures with implementation leads.
- [ ] Agree the primary research question and which funder decisions can actually be observed.
- [ ] Approve data collection, consent, safeguarding, retention and community access.
- [ ] Choose indicators, baselines, sample sizes and data owners.
- [ ] Confirm failure thresholds, incident escalation and who may pause the pilot.
- [ ] Review whether the Sarreya case study may be externally circulated.
- [ ] Obtain community and partner approval for any public-facing report.

## 12. Source and provenance

This working protocol synthesizes:
- *CTI Thesis V2.1 Revised Manuscript* (October 2026), especially §17 on SportFi and cross-context evaluation.
- AIFS / Women Win SportFi project discussions and funding outline (working records; budget and dates to verify).
- *AYNI // Crypto Yield Fund* meeting notes (23 September 2026; auto-generated notes, accuracy requires participant review).
- *AIFS × Sarreya* internal project materials, which inform the governance, evidence and safeguarding risk register.

**Research conclusion:** SportFi should be evaluated not on whether digital finance can move funds or produce yield, but on whether community-controlled evidence becomes more useful to institutions **without making community participation more extractive, fragile or costly**.
