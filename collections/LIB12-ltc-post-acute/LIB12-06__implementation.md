# Prepare staff and interfaces for facility service
**Collection:** LIB-12 Long-term care and post-acute pharmacy  
**Document type:** implementation  
**Audience:** Long-term care pharmacists; facility nursing leaders; post-acute administrators; healthcare regulatory counsel  
**Jurisdiction:** US CMS 42 CFR §483.45; Texas Class C overlays; DEA CS  
**Risk tier:** L2  
**Version:** 0.3-final-draft  
**Last verified:** 2026-09-19  
**Not:** legal advice, clinical protocol, survey-outcome guarantee, or therapy algorithm

## What this helps you decide or do
Test interfaces (e-prescribe, delivery confirmation, secure messaging) and staff roles with synthetic data before go-live.

## Who should use it / who else to involve
Pharmacy IT; consultant; facility ADON; courier lead.

## How to use the companion tools
| Companion | Use |
|-----------|-----|
| `LIB12-01__introduction.md` | Facility–pharmacy–prescriber service map |
| `LIB12-02__business_workbook.md` | LTC costing & continuity capacity |
| `LIB12-03__authority_map.md` | Requirements matrix & evidence locator |
| `LIB12-04__workflow.md` | Transition + DRR findings routing |
| `LIB12-05__template_pack.md` | Findings & acknowledgment records |
| `LIB12-06__implementation.md` | Staff/interface readiness |
| `LIB12-07__quality_toolkit.md` | Reliability & follow-through measures |
| `LIB12-08__client_development.md` | Facility proposal & renewal |

## Core content
| Interface | Test case (synthetic) | Pass criteria | Owner |
|-----------|----------------------|---------------|-------|
| Order inbound | New admit 5-med list | All lines coded; mismatches flagged | |
| DRR export | Monthly batch | Reports generated without live PHI in test | |
| Courier scan | STAT evening | Timestamp + signature capture | |
| After-hours escalate | On-call tree | Reachability drill logged | |

Training: facility nursing on how irregularity reports arrive; pharmacy staff on not giving therapy directives outside scope.

## Setting branches
Skip any branch that does not apply to your operation. Synthetic examples only — no real patient or facility identifiers.

### Community (independent / retail)
Closed-door LTC dispensing from a community license is a distinct ops model — confirm Texas class and delivery rules before quoting facility contracts. Do not apply nursing-home CoP text as if it binds the pharmacy alone; §483.45 binds the **facility** [1].

### ASC / consulting pharmacy
ASC consulting (LIB11) ≠ nursing-home monthly DRR. Different federal texts. Keep contracts and visit cadences separate.

### Clinic-embedded
Post-acute clinics may need med reconciliation support without becoming the facility’s required consultant pharmacist. Document scope boundaries.

### Specialty / infusion / compounding
IV antibiotics or specialty agents in SNF/LTACH raise sterile and REMS issues — branch to LIB15/LIB17; do not invent compounding privileges.

### Telepharmacy / delivery
Remote chart review can support DRR but facility still needs compliant pharmaceutical services and CS controls [1][4]. Delivery SLAs belong in the business workbook.

## Local adaptation — Texas verification checklist
- [ ] Confirm whether the Texas pharmacy license class is Class A closed-door, Class C, or other — do not guess [3].
- [ ] If Class C: apply PIC/consultant written agreement and bed-count limits [3].
- [ ] Map CMS §483.45 facility obligations vs pharmacy vendor duties in the contract [1].
- [ ] Confirm monthly DRR includes chart review and written irregularity reports to MD/DON/attending path [1].
- [ ] Align CS reconciliation and locked storage expectations with facility + DEA registrant duties [1][4][5].
- [ ] BAA in place before PHI exchange with facility CE [6].
- [ ] Re-verify current Appendix PP / F-tag surveyor guidance links before survey coaching [2].

## Sources
1. 42 CFR §483.45 Pharmacy services. eCFR. https://www.ecfr.gov/current/title-42/chapter-IV/subchapter-G/part-483/subpart-B/section-483.45. Accessed 2026-09-19.
2. CMS. State Operations Manual Appendix PP (download). https://www.cms.gov/medicare/provider-enrollment-and-certification/guidanceforlawsandregulations/downloads/appendix-pp-state-operations-manual.pdf. Accessed 2026-09-19.
3. TSBP. Class C Pharmacy Rules (May 2024 PDF). https://www.pharmacy.texas.gov/files_pdf/BN/May24/C.3.2.1.pdf. Accessed 2026-09-19.
4. 21 CFR §1301.71. eCFR. Accessed 2026-09-19.
5. DEA. Theft/Loss Reporting. https://www.deadiversion.usdoj.gov/21cfr_reports/theft/theft-loss.html. Accessed 2026-09-19.
6. HHS OCR. Covered Entities and Business Associates. https://www.hhs.gov/hipaa/for-professionals/covered-entities/index.html. Accessed 2026-09-19.
7. Clark J et al. ASHP CS diversion guidelines. *AJHP*. 2022. PMID:36208462. Accessed 2026-09-19.
8. ASHP National Survey … Operations and Technology—2023. PMID:38780002. Accessed 2026-09-19.
9. Pharmacist-led medication review in LTC (PMC8994296) — practice evidence orientation. Accessed 2026-09-19.

## Unresolved / held

Do **not** promote held claims without primary confirmation.

| Claim ID | Held statement | Why held | Reviewer |
|----------|----------------|----------|----------|
| C12-007 | Provisional transition lists until MAR reconciliation | Process tip / tom_original | LTC RPh |
| U12-01 | Appendix PP revision currency | Re-verify CMS download | Counsel |
| U12-03 | Exact TX license class for a site | Site facts held | PIC+counsel |
