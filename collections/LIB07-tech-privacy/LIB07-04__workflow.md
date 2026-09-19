# Request, test, approve, and monitor a system change
**Collection:** LIB-07 Technology, privacy & records (Topic 07)  
**Document type:** workflow  
**Audience:** Owners, PICs, privacy/security officials, IT leads, vendor managers  
**Jurisdiction:** US HIPAA (OCR); DEA e-CS Rx records; Texas Class C data-processing worksheet  
**Risk tier:** L2  
**Version:** 0.3-final-draft  
**Last verified:** 2026-09-19  
**Not:** clinical software validation protocol or FDA device clearance advice

**L3 review warning:** This is a private research draft. Do **not** treat ChatGPT (or any LLM) output as legal advice, board interpretation, or a compliance guarantee. Before operational use, have a Texas-licensed pharmacist and qualified counsel review L3 claims against current primary sources.

## What this helps you decide or do
Control workflow changes and failures without implying clinical validation. Every material change gets request → risk note → test → approve → monitor → rollback criteria.

## Who should use it / who else to involve
Change owner (IT/PIC); security official for ePHI impact; approver (owner/PIC).

## How to use the companion tools
| Companion | Use |
|-----------|-----|
| `LIB07-02__business_workbook.md` | TCO, migration, exit, breach-cost scenarios (synthetic $) |
| `LIB07-03__authority_map.md` | CE/BA · Privacy · Security · Breach · DEA e-Rx |
| `LIB07-04__workflow.md` | Request → test → approve → monitor change |
| `LIB07-05__template_pack.md` | RFP scorecard, BAA checklist, access review, retention |
| `LIB07-06__implementation.md` | Roles, MFA, audit logs, synthetic acceptance |
| `LIB07-07__quality_toolkit.md` | SRA cadence, tabletop breach, downtime drill |
| `LIB07-08__client_development.md` | Explain digital service & data boundaries to partners |
| `../CLAIM-LEDGER.csv` | Supported vs held claims |


## Core content — change workflow
1. **Request** — problem statement, vendor ticket, data classes touched (ePHI? CS Rx?).  
2. **Screen** — CE/BA impact [1]; Security contingency impact [3]; Class C downtime procedure still valid [6].  
3. **Test** — synthetic patients only; audit-log export; MFA path; e-Rx hazard checks informed by [7][8].  
4. **Approve** — named approver; go-live window; rollback owner.  
5. **Monitor** — 72-hour hypercare: error queue, claim rejects, access anomalies.  
6. **Breach/security incident path** — if unsecured PHI compromised, start Breach Rule analysis [4].  
7. **Close** — update SRA if risk profile changed [3]; retain docs 6 years [3].

### Stop conditions
- No signed BAA for new PHI processor [1]  
- Cannot retrieve CS e-Rx records at registered location [5]  
- No downtime auxiliary procedure [6]

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
- OCR Security Rule NPRM (proposed modifications) noted on OCR pages — monitor for final rule; this pack cites the current summary only.
- Product-specific PMS/e-Rx endorsements: **out of scope**.
- **HELD (editorial):** MFA/RTO/RPO scoring tips; telepharmacy encryption stack tips — practice suggestions, not shalls.
- Exact multi-year Texas pharmacy record retention matrix beyond Class C citations: verify Class A / other classes separately before publishing a single statewide table.
