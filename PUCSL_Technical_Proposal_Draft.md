# Technical Proposal — DRAFT (Abatis / Platinum Contribution)

**Assignment:** Assessment on Cybersecurity Readiness of Electricity Network and Critical Generation Facilities in Sri Lanka and Development of a Cybersecurity Audit Framework Specific to Grid Operations, SCADA and Critical Infrastructure Protection

**Procuring Entity:** Public Utilities Commission of Sri Lanka (PUCSL)

**Bidder:** Joint Venture of **Platinum High Integrity Technologies Limited (Malta)** — Lead JV Partner — and **EML Consultants PLC (Sri Lanka)** — Local JV Partner

**Status:** Working draft, 29 July 2026. Verify every section against the official tender document once purchased by EML. Items marked `[TBC]` require input listed in the workbook's "Outstanding Items" sheet.

---

## 1. Covering Letter (draft text)

> Dear Chairman / Members of the Procurement Committee,
>
> We, the Joint Venture of Platinum High Integrity Technologies Limited (Malta) as Lead Joint Venture Partner and EML Consultants PLC as Local Joint Venture Partner, are pleased to submit our Technical and Financial Proposals for the *Assessment on Cybersecurity Readiness of Electricity Network and Critical Generation Facilities in Sri Lanka and Development of a Cybersecurity Audit Framework Specific to Grid Operations, SCADA and Critical Infrastructure Protection*.
>
> Our Joint Venture combines internationally proven Operational Technology (OT) and Critical National Infrastructure (CNI) cybersecurity expertise — built over two decades protecting government and military-grade critical assets — with the strongest locally listed engineering consultancy in Sri Lanka, providing power-systems and SCADA engineering capability, stakeholder engagement and full local delivery support.
>
> We confirm that our proposal remains valid for the period stated in the RFP `[TBC]`, that the information provided is true and correct, and that both Joint Venture partners accept joint responsibility for the performance of the assignment.

Signatories: Authorised representative of Platinum High Integrity Technologies Limited (Malta); authorised representative of EML Consultants PLC. `[Power of attorney / board authorisation — TBC]`

---

## 2. Consultant's Organisation and Experience

### 2.1 Lead JV Partner — Platinum High Integrity Technologies Limited (Malta), with Abatis Security Innovations & Technologies GmbH (Switzerland)

- **Abatis Security Innovations & Technologies GmbH** was incorporated in Switzerland in **October 2004**. Its founding engagement was at the request of the **Swiss government**: technology designed for national critical-infrastructure protection and implemented by the **Swiss military**.
- Over 20+ years of operation there has been **no reported breach against the Abatis code and no CVE (Common Vulnerabilities and Exposures) registered against it** — a record we believe is unique in the security industry.
- The Abatis approach is **deterministic and rule-enforcing**: attacks are stopped before they start, in nanoseconds — against an industry mean time to identify and contain a breach of ~270 days at an average cost of USD 4.5M (IBM, global).
- The group's current portfolio spans **critical national infrastructure, smart-city OT programmes in the Gulf** (e.g., major smart-city and metro OT cybersecurity programmes), **energy-sector engagements** (including a current engagement with a Gulf national energy company), government projects in **Africa and Latin America**, and OEM security integration at device-manufacturing point.
- Consultancy and advisory work (governance, risk, maturity assessment, regulatory support) represents a substantial share of the group's business alongside technology licensing.
- Platinum High Integrity Technologies Limited (Malta) is the group's EU-domiciled entity and owns the commercial delivery of the Abatis capability; it therefore leads the Joint Venture, carrying the principal technical scope and specialist resources. `[Insert Malta incorporation details — TBC]`
- UK affiliate: Platinum High Integrity Technologies Limited, Kemp House, 152–160 City Road, London EC1V 2NX (Company No. 13674653).

### 2.2 Local JV Partner — EML Consultants PLC (Sri Lanka)

- Incorporated **1993** as EML Consultants (Pvt) Ltd — originally established with **Ernst & Young** and **DHV Netherlands**; fully Sri Lankan-owned since **2003**; re-registered as **EML Consultants PLC (Reg. No. PQ 00240481)** and **listed on the Colombo Stock Exchange** (name change effective 19 November 2021) — **the only consultancy company listed on the CSE**.
- **600+ consultancy projects** delivered across engineering, environment, water, irrigation, urban infrastructure, governance, institutional development and capacity building.
- **ISO 9001:2015** (Certificate GISL-0009-QC) and **ISO 14001:2015** (Certificate GISL-0009-EC) certified.
- International JV experience including with **Niras (Netherlands)** on Sri Lanka port projects; current major assignments include a hyperscale data-centre project, a 50-storey mixed development at Port City Colombo, and the Grand Hyatt Colombo project.
- Registered member of the Central Environmental Authority; member of the National Chamber of Commerce.
- Role in this assignment: local project management (Deputy Project Manager — Power Systems/SCADA Engineer), electrical engineering support, stakeholder engagement with PUCSL and the utilities, workshops and capacity-building logistics, QA/QC under its ISO 9001-certified system, administration, and physical preparation/submission of the proposal.

### 2.3 Division of Responsibilities

| Workstream | Lead |
|---|---|
| Technical methodology, risk/threat assessment, C2M2 maturity scoring, audit framework | Abatis (Platinum) |
| Staffing strategy, work plan, principal technical deliverables | Abatis (Platinum) |
| Power systems / SCADA engineering, site & field assessment support | EML |
| Stakeholder engagement, workshops, capacity building delivery, SOP localisation | EML (content by Abatis) |
| QA/QC, report coordination, administration, local logistics | EML |
| Proposal integration and submission in Sri Lanka | EML (both parties approve final documents) |

---

## 3. Approach and Methodology — Readiness Assessment

### 3.1 Assessment Philosophy

Documented policies and procedures do not by themselves constitute security. Our methodology explicitly tests whether processes are **understood, followed and effective in practice** — interviewing multiple seniority levels for the same function (operator, supervisor, manager, executive), because in our experience the gaps most often sit between the document and the day-to-day operation of the control room.

### 3.2 Phased Methodology

**Phase 0 — Mobilisation & Inception (Weeks 1–2).** Kick-off workshop with PUCSL and utility stakeholders; confirmation of scope (facilities, systems, sites `[count TBC]`); stakeholder map; data-request register; confidentiality arrangements and a **secure artefact-collection portal** provided by Abatis for all evidence exchange. Output: **Inception Report**.

**Phase 1 — Information Gathering (Weeks 2–4).** Collection and desk review of security policies, SOPs, network and SCADA/EMS architectures, asset registers, remote-access arrangements, vendor/support contracts, incident history and prior audits — reviewed against C2M2, IEC 62443 and NIST CSF control expectations. Output: document review register and preliminary gap log.

**Phase 2 — Interviews & Site Assessment (Weeks 4–8).** Structured multi-level interviews; site visits to system control centre(s), SCADA/EMS master stations, selected substations/RTU sites, critical generation facilities (DCS environments) and the IT/OT boundary; control validation in the field by EML's power-systems and SCADA engineers working with Abatis OT/ICS specialists.

**Phase 3 — Maturity & Risk Analysis (Weeks 8–11).**
- **C2M2 (DOE Cybersecurity Capability Maturity Model, v2.1)** evaluation across all ten domains — ASSET, THREAT, RISK, ACCESS, SITUATION, RESPONSE, THIRD-PARTIES, WORKFORCE, ARCHITECTURE, PROGRAM — scored MIL0–MIL3 per objective, evidence-based, with a moderated scoring workshop and a target-profile gap analysis.
- **Threat modelling** aligned to MITRE ATT&CK for ICS: utility-specific scenarios including ransomware against EMS/SCADA, supply-chain compromise, remote-access abuse, insider threat and nation-state pre-positioning.
- **Risk assessment**: likelihood × impact on safety, grid reliability and regulatory compliance; prioritised, costed treatment plan.
- **Standards benchmark**: IEC 62443 (zones & conduits; target vs achieved security levels), NIST CSF 2.0, ISO/IEC 27001/27019, with NERC CIP as an international reference model for critical-infrastructure-protection obligations.

Output: **Cybersecurity Readiness Assessment Report** with C2M2 maturity profile, risk register and prioritised remediation roadmap.

### 3.3 Why C2M2 as the Maturity Backbone

C2M2 was developed by the U.S. Department of Energy specifically for the energy sector, covers both IT and OT, is free to adopt and re-run (supporting PUCSL's ongoing regulatory monitoring), and maps cleanly to NIST CSF and IEC 62443 — allowing one assessment effort to serve maturity measurement, gap analysis and audit-framework design simultaneously.

---

## 4. Approach and Methodology — Cybersecurity Audit Framework

**Phase 4 — Audit Framework Development (Weeks 10–13).** A PUCSL-specific audit framework enabling the regulator to audit licensees' cybersecurity on a repeatable, defensible basis:

1. **Audit universe & scoping model** — which entities, systems and facilities are auditable, with criticality-based tiering (grid operations, SCADA/EMS, generation control, market systems).
2. **Control catalogue** — mapped to C2M2 domains, IEC 62443 and NIST CSF, tailored to Sri Lankan grid operations.
3. **Audit procedures & evidence requirements** per control — what an auditor asks, observes, tests and collects.
4. **Maturity-based scoring & reporting templates** — consistent scoring, findings classification, and board/regulator-level reporting formats.
5. **Audit cycle & escalation model** — frequency by criticality tier, follow-up/remediation tracking, regulatory escalation.
6. **Auditor competency requirements** — skills, training and certification expectations for PUCSL audit staff.

**4.3 SOPs & Regulatory Guidance.** Local SOPs and regulatory guidance notes co-developed with EML, drafted to operate under current Sri Lankan law while remaining forward-compatible with anticipated national cyber/CNI legislation. `[Existing PUCSL regulatory instruments — TBC from EML]`

---

## 5. Capacity Building & Knowledge Transfer

Four workshops (local delivery by EML, content by Abatis):

1. **Project Kick-off Workshop** — scope, expectations, data collection mobilisation.
2. **Technical Findings & Governance Framework Workshop** — validation of assessment findings and draft framework with stakeholders.
3. **Knowledge Transfer Workshop** — auditor enablement: operating the audit framework, C2M2 re-assessment, continuous monitoring; train-the-trainer materials.
4. **Executive Presentation & Final Workshop** — leadership briefing on findings, roadmap and framework adoption.

All training materials are handed over for PUCSL's continued use.

---

## 6. Project Management, QA and Security of Information

- **Governance:** Abatis Team Leader directs the technical programme; EML Deputy Project Manager (Power Systems/SCADA Engineer) manages local delivery; joint weekly progress reviews; both parties copied on all PUCSL correspondence.
- **QA:** dual assurance — Abatis technical peer review of every specialist deliverable; EML QA/QC Manager operating under its ISO 9001:2015-certified system; neither party amends the other's contribution without prior agreement.
- **Information security:** secure artefact-collection portal for all assessment evidence; strict confidentiality handling; in-country retention of sensitive material where required by PUCSL.

---

## 7. Added Value

- **Regulatory foresight:** the JV can support PUCSL and the Government of Sri Lanka beyond this assignment in drafting/updating national cyber and CNI legislation, drawing on EU regulatory experience (incl. cyber-sovereignty regimes) and Gulf implementations (e.g., Saudi NCA-style regimes).
- **Practical protective capability:** uniquely among consultancies, the technical partner also builds protective technology with a 20-year zero-breach, zero-CVE record — assessment recommendations are grounded in what demonstrably works in live CNI environments.
- **Long-term local presence:** EML provides continuity for follow-up audits, re-assessments and capacity building.

---

## 8. Work Plan & Staffing (summary)

16-week programme (detail in workbook "Work Plan" and "Staffing & Rates" sheets):

- **Abatis: 120 man-days** — Team Leader (30), Senior OT/ICS Specialist (60), Governance Specialist (20), IEC 62443/C2M2 Specialist (5), Training Specialist (5).
- **EML: 145 man-days** — DPM Power Systems/SCADA Engineer (50), Electrical Engineer (25), Stakeholder Engagement (15), QA/QC (10), Report Coordinator (15), Project Administrator (30).
- 2 international missions; 20 site-days in Sri Lanka; 4 workshops.

**Financial summary (internal):** Base USD 162,350 + 15% profit = **USD 192,790.63 excl. taxes**; with VAT 18% + SSCL 2.5% = **USD 233,180.26**. `[Currency and tax treatment for the financial forms — TBC]`

---

## 9. Open Items Before Submission

See workbook "Outstanding Items" sheet — most critical:

1. **Official tender pack** (EML purchasing) — this draft must be reconciled clause-by-clause against the actual TOR and forms.
2. Additional forms/annexes (compliance spreadsheet in Excel?) — question already put to EML.
3. Bid security requirement — unknown.
4. Signed JV Letter of Intent naming **Platinum Malta as Lead JV Partner**.
5. CVs (Abatis + EML) in tender format; academic-credential strategy agreed (EML fields degree-qualified engineers; Abatis fields MCIIS/IISP practitioners plus academically credentialed specialists as needed).
