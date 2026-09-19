# Data responsibilities, access, and legal applicability
**Collection:** LIB-07 Technology, privacy & records (Topic 07)  
**Document type:** authority_map  
**Audience:** Owners, PICs, privacy/security officials, IT leads, vendor managers  
**Jurisdiction:** US HIPAA (OCR); DEA e-CS Rx records; Texas Class C data-processing worksheet  
**Risk tier:** L3  
**Version:** 0.3-final-draft  
**Last verified:** 2026-09-19  
**Not:** complete privacy opinion or multi-state licensing map

**L3 review warning:** This is a private research draft. Do **not** treat ChatGPT (or any LLM) output as legal advice, board interpretation, or a compliance guarantee. Before operational use, have a Texas-licensed pharmacist and qualified counsel review L3 claims against current primary sources.

## What this helps you decide or do
Identify privacy, security, retention, and contractual duties by data flow. Reference-only—counsel confirms.

## Who should use it / who else to involve
Security official + counsel (L3); PIC; vendor contract owner.

## How to use the companion tools

| Companion | Where to find it | Use |
|-----------|------------------|-----|
| Business workbook | Same collection → LIB07-02 | TCO, migration, exit, breach-cost scenarios (synthetic $) |
| Authority map | Same collection → LIB07-03 | CE/BA · Privacy · Security · Breach · DEA e-Rx |
| Workflow | Same collection → LIB07-04 | Request → test → approve → monitor change |
| Template pack | Same collection → LIB07-05 | RFP scorecard, BAA checklist, access review, retention |
| Implementation | Same collection → LIB07-06 | Roles, MFA, audit logs, synthetic acceptance |
| Quality toolkit | Same collection → LIB07-07 | SRA cadence, tabletop breach, downtime drill |
| Client development | Same collection → LIB07-08 | Explain digital service & data boundaries to partners |
| Claim ledger | Same collection → claim ledger (`CLAIM-LEDGER.csv`) | Supported vs held claims |


## Core content — authority matrix
| Topic | Instrument | Key duty (orientation) | Cite |
|-------|------------|------------------------|------|
| CE determination | OCR CE/BA | Pharmacy as CE when standard e-transactions | [1] |
| BA contracts | OCR CE/BA | Written BA; BA direct liability (certain provisions) | [1] |
| Privacy Rule | OCR Privacy summary | Uses/disclosures; workforce training outline | [2] |
| Security Rule | OCR Security summary | CIA of ePHI; risk analysis; contingency; 6-year docs; security official | [3] |
| Breach | OCR Breach Rule | Individual/Secretary/media; BA ≤60 days to CE | [4] |
| e-CS Rx records | 21 CFR 1304.04(h)(5), 1304.06 | Maintain in Part 1311 apps; readily retrievable/printable | [5] |
| TX Class C DP | 22 TAC §291.75 | Monthly backup; 10-day significant data-loss report; downtime auxiliary | [6] |

### Data-flow prompts (synthetic)
1. Does vendor create/receive/maintain/transmit PHI for us? → BA path [1].  
2. Remote verification across sites? → authentication, encryption, SRA entry (editorial + [3]).  
3. Camera over counseling area? → minimize PHI; policy with Topic 06 inventory cameras.

### Evidence discipline
Prefer OCR primary summaries for Privacy, Security, and Breach duties [1][2][3][4]. Texas Class C data-processing shalls are setting-specific — confirm class before applying [6]. HIT safety papers support training and SRA scoping, not vendor awards [7][8][9]. Monitor OCR notices for Security Rule proposed modifications; this pack cites the current summary only.

## Setting branches
Skip any branch that does not apply. Synthetic examples only — no real patient or facility identifiers.

### Community (independent / retail)
Retail PMS plus e-prescribing networks are the usual ePHI spine. Score vendors on signed BAA, unique user ID/MFA, and audit-log export before price [1][3]. Peer-reviewed sociotechnical work shows e-prescribing can introduce new hazards across technology, people, and organization [7][8] — use that to design verification checklists, not to ban e-Rx.

### ASC / consulting pharmacy
ADC–EHR interfaces and Class C data-processing rules (monthly backup, downtime auxiliary procedure, 10-day significant data-loss report) apply alongside HIPAA Security contingency planning [3][6]. Name who is security official for the pharmacy versus the facility IT lead.

### Clinic-embedded
Shared clinic EHRs force an early CE/BA determination: is the pharmacy workforce of the clinic CE, a separate CE, or a BA? Do not share PHI with a new app vendor without a written BA arrangement when required [1].

### Specialty / infusion / compounding
Specialty hubs often add remote access, patient support portals, and courier integrations. Each processor that creates/receives/maintains/transmits PHI needs BA review [1]. Retain Security Rule documentation six years [3].

### Telepharmacy / delivery
Remote verification stacks need unique authentication and encryption addressed in the security risk analysis (editorial practice tip + Security Rule risk analysis duty) [3]. Electronic CS prescription records must remain readily retrievable/printable at the registered location under Part 1304 orientations [5].


## Local adaptation — Texas verification checklist

Complete with PIC (and counsel for L3 rows) against **live** primary pages on the day you rely on them. Forms and PDF revisions change.

- [ ] Confirm Class C backup: information in data processing system backed up at least **monthly** [6].
- [ ] PIC reports **significant loss of information** to the Board within **10 days** of discovery [6].
- [ ] Auxiliary procedure for data-processing **downtime** that retains data for later on-line entry [6].
- [ ] Map HIPAA Security contingency plan duties (backup/restore/emergency-mode) to pharmacy downtime SOP [3].
- [ ] Confirm electronic CS Rx records readily retrievable/printable at registered location per Part 1304 / 1311 stack [5].
- [ ] Name security official responsible for Security Rule policies [3].
- [ ] Retention: Security Rule documentation ≥ **6 years** after later of creation or last effective date [3].

## Sources
1. HHS OCR. Covered Entities and Business Associates. https://www.hhs.gov/hipaa/for-professionals/covered-entities/index.html. Accessed 2026-09-19.
2. HHS OCR. Summary of the HIPAA Privacy Rule. https://www.hhs.gov/hipaa/for-professionals/privacy/laws-regulations/index.html. Accessed 2026-09-19.
3. HHS OCR. Summary of the HIPAA Security Rule. https://www.hhs.gov/hipaa/for-professionals/security/laws-regulations/index.html. Accessed 2026-09-19.
4. HHS OCR. Breach Notification Rule. https://www.hhs.gov/hipaa/for-professionals/breach-notification/index.html. Accessed 2026-09-19.
5. 21 CFR Part 1304 (incl. §§1304.04(h)(5), 1304.06). eCFR. https://www.ecfr.gov/current/title-21/chapter-II/part-1304. Accessed 2026-09-19.
6. Texas State Board of Pharmacy. Class C Pharmacy Rules (May 2024 PDF). https://www.pharmacy.texas.gov/files_pdf/BN/May24/C.3.2.1.pdf. Accessed 2026-09-19.
7. Odukoya OK, Chui MA. E-prescribing: a focused review and new approach to addressing safety in pharmacies and primary care. *Res Social Adm Pharm*. 2013;9(6):e1-e14. PMID:23062769. Accessed 2026-09-19.
8. Odukoya OK, Chui MA. e-Prescribing: characterisation of patient safety hazards in community pharmacies using a sociotechnical systems approach. *BMJ Qual Saf*. 2014;23(6):437-446. PMID:23708439. Accessed 2026-09-19.
9. Health Information Technology Use and Patient Safety: Study of Pharmacists in Nebraska. PMC6473452. https://pmc.ncbi.nlm.nih.gov/articles/PMC6473452/. Accessed 2026-09-19.

## Unresolved / held
- OCR Security Rule NPRM (proposed modifications) noted on OCR pages — monitor for final rule; this pack cites current Security Rule summary.
- Product-specific PMS/e-Rx endorsements: **out of scope**.
- **HELD (editorial):** MFA/RTO/RPO scoring tips; telepharmacy encryption stack tips — practice suggestions, not shalls.
- Exact multi-year Texas pharmacy record retention matrix beyond Class C citations: verify Class A / other classes separately before publishing a single statewide table.
