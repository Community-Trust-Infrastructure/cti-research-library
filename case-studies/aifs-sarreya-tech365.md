# AIFS × Sarreya Sport — When the technology wasn't the hard part

**CTI applied research case study · Working draft v0.1 · 10 November 2026**  
**Setting:** Hargeisa, Somaliland · **Pilot:** September 2025–July 2026  
**Partners/context:** All In For Sport (AIFS), Sarreya Sport, Olympism365 Innovation Hub; Women Win involved in funding administration  
**Research status:** Retrospective, practice-based case analysis. Not an independent evaluation, an audited technical assessment, or proof of CTI effectiveness.

> **Publication caution:** This case is derived from internal AIFS–Sarreya materials and an adapted UNICEF application writing sample. Technical vulnerabilities, the reported loss, safeguarding issues and partner descriptions require AIFS/Sarreya confirmation and approval before broad public promotion. No participant names, images, transaction addresses or identifiable attendance records are reproduced here.

## Abstract

The AIFS × Sarreya pilot began with a practical question: could a grassroots sport community record its own activities and decisions in a verifiable way that would be legible to external funders without adding conventional reporting burdens? The project explored a messaging-based signal workflow, attestations, a transparent USDC treasury and locally mediated cash-out. Field experience exposed a more fundamental problem than payment speed: what makes a community's evidence recognizable, interpretable and legitimate to an institution that did not witness the underlying activity?

The pilot offers **design constraints and falsifiable hypotheses**, not proof that portable trust has been achieved. Technical records can be incomplete, unauthorized or unsafe to publish; financial access can depend on trusted people; and human stewardship may be more appropriate than automation at small scale.

## 1. Research questions

**Primary question:** Can evidence generated close to community activity be validated in ways that preserve local authority while improving the quality of information available to funders?

Secondary questions:
1. Can participants create and confirm records without specialized financial or blockchain expertise?
2. Can a validator's authority be established and revoked, rather than merely inferred from possession of a signing key?
3. Can funds reach a community through workable local settlement channels without confusing successful payment with legitimate allocation?
4. Can the approach reduce reporting effort without creating new privacy, security or stewardship burdens?

## 2. Setting and approach

The internal project record describes a USD 30,000 Olympism365 Tech365 pilot running September 2025–July 2026. The work included co-design, prototype development, field workshop activities and operational learning. The technical components included **Prueba** (an attestation schema/protocol), **Witness** (a messaging-based Somali/English signal-capture workflow), an indexer/dashboard, a USDC treasury and a locally mediated off-ramp.

A two-day workshop in Hargeisa on **15–16 May 2026** reportedly convened **31 women**. Activities included community agenda-setting and a paper-ballot decision concerning **USD 1,000** in equipment spending. These are project-reported observations, not independently validated participant outcomes. Participation figures should not be extrapolated into claims about population-level impact.

The study is a retrospective analysis of implementation documents and team observations, not a controlled comparison. There is no reported counterfactual, validated baseline of reporting cost, or independent measurement of changes in funder decisions.

## 3. What was observed

### 3.1 Recognition before speed

**Reported observation:** Faster digital transfer mechanisms did not by themselves solve financial exclusion, unfamiliarity with crypto flows or questions of who had legitimate authority to make and verify decisions.

**Interpretation:** An institution needs to understand not only that a transfer is possible, but why an allocation is justified and whether the underlying community decision was legitimate.

**Alternative explanation:** The obstacles could be specific to local regulation, financial literacy, organizational maturity or provider availability rather than evidence infrastructure as such.

### 3.2 Local relationships enabled financial access

**Reported observation:** A relationship with ELAV Capital provided an off-ramp path to local currency; access depended on personal introductions and human coordination.

**Interpretation:** Financial interoperability is partly relational and institutional, not merely technical.

**Failure mode:** A single trusted intermediary can become a continuity, concentration or accountability risk.

### 3.3 Community confirmation mattered more than the ledger choice

**Reported observation:** Workshop participants used familiar, deliberative mechanisms—including a paper ballot—to make decisions. Messaging tools were used to explore low-friction capture of activity and attestations.

**Interpretation:** Community authorization and the ability to contest or correct records should precede decisions about where records are stored.

**Unresolved:** Whether participants experienced the system as genuinely empowering, and how dissent or withdrawal of consent was handled, require direct community feedback.

### 3.4 Manual stewardship was practical at pilot scale

**Reported observation:** Human-stewarded distribution and support were used rather than fully automated flows.

**Interpretation:** Automation is not inherently more trustworthy or economical. At small scale, accountable human review may be appropriate.

**Unresolved:** A comparative cost and reliability assessment has not been completed.

## 4. Technical and governance failures that matter

The October 2026 CTI thesis manuscript identifies several implementation issues reported in an August internal team draft. These are important **unverified internal findings requiring technical-owner review** before external attribution.

| Reported issue | Why it matters | CTI design requirement |
| --- | --- | --- |
| v1 schema reportedly truncated IPFS identifiers | An on-chain pointer may be technically recorded yet unusable as evidence | Test retrieval integrity end to end |
| Intended distinct-participant confirmation threshold reportedly not enforced; a bot-controlled key signed | A signature is not proof of community authorization | Enforce distinct signers, mandate scope and revocation in running code |
| Reported USD 1,000 address-poisoning loss | Irreversible transactions amplify operational error and attack exposure | Address verification, test transfers, dual control and incident procedures |
| Publicly stored photographs create privacy persistence risks | Revoking an attestation does not remove already public media | Private storage, informed consent, minimization and removal procedures |
| Documentation reportedly diverged from implementation | Misdescribed systems cannot be reliably audited or reused | Versioned technical documentation and acceptance tests |

**Important distinction:** These issues should not be presented as independently established security findings. The case describes what internal documents reported and what would follow *if confirmed*.

## 5. Mapping the pilot to the CTI reference architecture

| CTI stage | Pilot manifestation | What remains unproven |
| --- | --- | --- |
| **Activity** | Community sport sessions, workshop participation, collective decisions | Representativeness and long-term outcomes |
| **Signal** | Messaging-based activity records and workshop documentation | Completeness, consent and error rates |
| **Attestation** | Prueba / Witness claims and signing workflows | Whether each signer had valid, distinct community authority |
| **Validation** | Steward review and community confirmation | Repeatability, independence and contestation mechanisms |
| **Trust context** | Proposed portable account of evidence, authority and limitations | Whether external institutions can interpret it consistently |
| **Capital allocation** | Community decision concerning equipment spending | Whether validated evidence changed funder allocation decisions |
| **Settlement** *(adjacent)* | USDC treasury and local off-ramp | Reliability, resilience, cost and provider independence |

**Architectural boundary:** CTI is a proposed evidence, validation and authorization interface. It does not itself issue currency, hold reserves or settle payments.

## 6. Findings versus hypotheses

**Supported as internal pilot observations:** The workshop took place according to project records; participants used community decision-making; the team built and tested prototype signal/attestation and treasury workflows; off-ramping and messaging-platform access required practical workarounds.

**Reasonable interpretations, not demonstrated causal findings:** Human relationships can be essential to financial access; locally authorized confirmations may be more meaningful than technically valid records alone; simpler stewardship may outperform premature automation.

**Not established:** Reduced reporting costs, increased funder confidence, better allocation outcomes, generalizable portability, independent security assurance, improved long-term wellbeing or validated ROI.

## 7. Design revisions arising from the case

1. **Authority must be executable:** a validator's mandate, scope, expiry and revocation must be technically enforced, not merely documented.
2. **Proof must remain retrievable and contestable:** integrity tests must include the full evidence retrieval chain and correction path.
3. **Privacy precedes transparency:** participant media and sensitive data require consent, selective disclosure and deletion-compatible storage.
4. **Human stewardship is a first-class design option:** automation should be justified by comparative safety, cost and accountability.
5. **Settlement must be replaceable:** dependence on one wallet, off-ramp, messaging platform or vendor should not be treated as permanent architecture.
6. **Evidence should be proportionate:** avoid imposing more verification effort than the allocation decision reasonably requires.

## 8. Proposed next experiments and measurements

The subsequent SportFi work with Sarreya and Ayni Skate Project in Bolivia offers a possible comparative setting, **not a completed validation**.

| Test | Measure | Potential falsifier |
| --- | --- | --- |
| Evidence quality | Missing fields, retrieval success, disputed claims, steward disagreement | Records cannot be independently interpreted or corrected |
| Governance legitimacy | Verified mandates, distinct confirmations, revocation tests | Unauthorized signers can validate or revoke records |
| User burden | Time to submit and confirm, assistance needed, dropout | New workflow costs exceed conventional reporting burden |
| Funder usefulness | Decisions made with/without trust context; stated confidence and actual allocation changes | Better records do not change decisions or improve reasoning |
| Portability | Same claim type across two communities with locally governed validation | Shared schema requires imposing one community's governance on another |
| Resilience | Recovery time after provider loss, failed transfers, off-ramp interruption | Critical workflows depend on one unavailable provider |
| Safeguarding | Consent coverage, access logs, removal requests, unintended disclosure | Evidence publication creates unacceptable participant risk |

Define measurement methods, consent arrangements and comparison criteria **before** interpreting pilot results.

## 9. Limitations, ethics and review

This is a single-context, team-authored case with no independent audit or counterfactual. Participants' accounts and community consent have not been independently reviewed for this publication. Technical findings and partner descriptions should be checked with implementation owners; safeguarding considerations should be reviewed with Sarreya before publishing identifiable artifacts. Financial and security incidents should be described only at an appropriate level of detail agreed with the responsible parties.

The case must not be used to imply that a blockchain, AI agent, stablecoin or CTI itself caused better social outcomes. Nor should it turn a community's activities into an extractive data source for funders.

## 10. Source and provenance register

- **Internal source:** Rajani, H., and Lanigan, S. (26 August 2026), *What we learned and what happens next: AIFS × Sarreya, Tech365 pilot*, draft v1, cited in the CTI thesis manuscript. Internal; not independently audited.
- **Supporting source:** *AIFS Sarreya Project — Final Grant Report — July 2026*, draft with several fields marked for confirmation. Internal; not a final verified source.
- **Adapted narrative:** Shannon Lanigan, *What We Learned When the Technology Wasn't the Hard Part*, UNICEF SPARK application writing sample. Team-informed account, not an independent evaluation.
- **Synthesis:** *CTI Thesis V2.1 Revised Manuscript*, October 2026, Part III §§14–17 and source/evidence register. Internal working manuscript.

**Editorial review required before public promotion:** AIFS technical lead; Sarreya community representative; partner naming and permissions; exact grant figures and workshop metrics; implementation status of safeguards; incident wording; consent and image-use permissions.

---

**Research conclusion:** The pilot's contribution is not proof that CTI works. It demonstrates why an architecture connecting real-world activity, authorized claims, contextual validation and accountable allocation is worth testing—and how easily that architecture can fail if governance, privacy and operational reality are treated as secondary to transaction technology.
