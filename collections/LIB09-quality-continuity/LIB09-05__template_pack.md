# Risk, learning, and exercise records
**Collection:** LIB-09 Quality, risk & business continuity (Topic 08)  
**Document type:** template_pack  
**Audience:** Owners, PICs, quality/risk leads, facility EP coordinators  
**Jurisdiction:** US CMS EP (covered types); HIPAA contingency; Texas Class C; voluntary COM COOP  
**Risk tier:** L2  
**Version:** 0.3-final-draft  
**Last verified:** 2026-09-19  
**Not:** patient identifiers in shared examples

**L3 review warning:** This is a private research draft. Do **not** treat ChatGPT (or any LLM) output as legal advice, board interpretation, or a compliance guarantee. Before operational use, have a Texas-licensed pharmacist and qualified counsel review L3 claims against current primary sources.

## What this helps you decide or do
Capture process evidence without patient information in shared examples.

## Who should use it / who else to involve
Quality lead (records custodian); PIC; drill participants.

## How to use the companion tools
| Companion | Use |
|-----------|-----|
| `LIB09-02__business_workbook.md` | Risk register + BIA (local $) |
| `LIB09-03__authority_map.md` | CMS EP vs voluntary; HIPAA; DEA; TSBP |
| `LIB09-04__workflow.md` | Detect → contain → notify → learn → exercise |
| `LIB09-05__template_pack.md` | Incident, CAPA, AAR, COOP one-pager |
| `LIB09-06__implementation.md` | RACI, comms tree, alternate site |
| `LIB09-07__quality_toolkit.md` | Metrics dashboard, drill calendar |
| `LIB09-08__client_development.md` | Continuity diagnostic for ASC clients |


## Core content
### Incident form (synthetic fields)
Date/time · Reporter · Type (outage/variance/near miss/diversion/suspect product) · NCC MERP category if applicable [9] · Immediate actions · Notifications sent · CAPA # · Closed date

### CAPA log
ID · Finding · Root cause · Action · Owner · Due · Status · Effectiveness check

### Exercise after-action (AAR)
| Item | Entry |
|------|-------|
| Scenario | |
| Date | |
| Objectives met Y/N | |
| Gaps | |
| CAPAs opened | |
| Next exercise due | |

### Voluntary COOP one-pager (COM — editorial, not CMS shall)
Power · Staffing call tree · CS security during closure · Claim/PMS downtime · Wholesaler secondary · Communications owner · Alternate pickup/delivery notes

### ADC / downtime recovery checklist (Class C orientation)
- [ ] Recovery plan current [7]  
- [ ] Board notification criteria understood ( >2 days or significant service limit) [7]  
- [ ] Manual dispensing/record path tested  

### Evidence discipline
Applicability mistakes are common: do not tell a stand-alone community pharmacy it “must” meet CMS EP Rule elements [3]. Do tell Medicare ASC pharmacy leaders to align with facility EP [1][2]. ISMP and NCC MERP are link-only professional sources — do not republish newsletters [9][10][11]. Guided CQI evidence shows culture benefits without promising reporting-volume miracles [12].

## Setting branches
Skip any branch that does not apply. Synthetic examples only — no real patient or facility identifiers.

### Community (independent / retail)
CMS Emergency Preparedness Rule FAQ states the regulation does **not** apply to stand-alone community pharmacies [3]. Still maintain a voluntary COOP one-pager (power, staffing, CS security, claim downtime) as editorial good practice — not a federal shall. Build CQI using NCC MERP taxonomy and dispensing recommendations; state CQI mandates vary and Texas mandatory CQI is **unverified** in this pack [10][13].

### ASC / consulting pharmacy
Medicare-participating ASCs are covered EP provider types; pharmacy departments align to the facility EP program’s four core elements and annual review [1][2][3]. Texas Class C requires an emergency preparedness plan among drug-distribution P&P topics and ADC recovery plans with Board notice triggers [7].

### Clinic-embedded
Hospital or clinic pharmacies that are departments of Medicare-participating facilities fall under the facility EP program rather than a stand-alone pharmacy exclusion [3]. Coordinate incident clocks (DEA Form 106, DSCSA suspect product) with facility quality [6][8].

### Specialty / infusion / compounding
Include cold-chain failure and wholesaler outage in the risk assessment (editorial). Suspect-product and recall events are quality incidents intersecting safe supply [8].

### Telepharmacy / delivery
Define failover verification site and patient/facility communication scripts before an outage (editorial). HIPAA Security contingency (backup/restore/emergency-mode) still applies to ePHI systems [5].


## Local adaptation — Texas verification checklist

Complete with PIC (and counsel for L3 rows) against **live** primary pages on the day you rely on them. Forms and PDF revisions change.

- [ ] Class C: written **emergency preparedness plan** (continuity of patient therapy and public safety) among drug-distribution P&P topics [7].
- [ ] Class C with automated medication supply: written **recovery plan** for downtime; Board notification when downtime exceeds **two days** of operation or significantly limits services [7].
- [ ] Wire DEA Form 106 clock into incident workflow [6].
- [ ] DSCSA suspect-product events treated as quality incidents [8].
- [ ] **Do not** claim Texas mandatory community-pharmacy CQI until separately verified against TSBP — national survey found only 16 states required CQI as of 2021 study [13].
- [ ] If pharmacy is a **department** of Medicare ASC/hospital: CMS EP applies to the facility program [1][3].

## Sources
1. CMS. Emergency Preparedness Rule hub. https://www.cms.gov/medicare/health-safety-standards/quality-safety-oversight-emergency-preparedness/emergency-preparedness-rule. Accessed 2026-09-19.
2. CMS. Core EP Rule Elements. https://www.cms.gov/medicare/health-safety-standards/quality-safety-oversight-emergency-preparedness/core-ep-rule-elements. Accessed 2026-09-19.
3. CMS. Emergency Preparedness Frequently Asked Questions (PDF). https://www.cms.gov/medicare/provider-enrollment-and-certification/surveycertemergprep/downloads/frequently-asked-questions-faqs.pdf. Accessed 2026-09-19.
4. CMS. Health Care Provider Guidance (EP). https://www.cms.gov/medicare/health-safety-standards/quality-safety-oversight-emergency-preparedness/health-care-provider-guidance. Accessed 2026-09-19.
5. HHS OCR. Summary of the HIPAA Security Rule (contingency). https://www.hhs.gov/hipaa/for-professionals/security/laws-regulations/index.html. Accessed 2026-09-19.
6. DEA Diversion Control. Theft/Loss Reporting. https://www.deadiversion.usdoj.gov/21cfr_reports/theft/theft-loss.html. Accessed 2026-09-19.
7. Texas State Board of Pharmacy. Class C Pharmacy Rules (May 2024 PDF). https://www.pharmacy.texas.gov/files_pdf/BN/May24/C.3.2.1.pdf. Accessed 2026-09-19.
8. FDA. Pharmacists DSCSA overview. https://www.fda.gov/drugs/drug-supply-chain-security-act-dscsa/pharmacists-utilize-dscsa-requirements-protect-your-patients. Accessed 2026-09-19.
9. NCC MERP. Types of Medication Errors / Index (rev. Oct 2022). https://www.nccmerp.org/types-medication-errors. Accessed 2026-09-19.
10. NCC MERP. Recommendations to Enhance Accuracy of Dispensing Medications. https://www.nccmerp.org/recommendations-enhance-accuracy-dispensing-medications. Accessed 2026-09-19.
11. Institute for Safe Medication Practices (ISMP). https://www.ismp.org/. Accessed 2026-09-19. Rights: link-only.
12. Chinthammit C et al. Evaluation of a guided continuous quality improvement program in community pharmacies. *J Pharm Policy Pract*. 2017;10:26. PMID:28878928. Accessed 2026-09-19.
13. Fay AE et al. Continuous quality improvement regulations for community pharmacy practice in the United States. *J Am Pharm Assoc*. 2021. PMID:33722542. Accessed 2026-09-19.

## Unresolved / held
- Texas Board CQI “shall” status for stand-alone community pharmacy: **verify separately** before claiming mandatory CQI [13].
- U08-01 **closed:** CMS FAQ confirms stand-alone community pharmacies excluded from EP Rule [3].
- **HELD (editorial):** voluntary COM COOP one-pager; SPC cold-chain/wholesaler outage in RA; TEL failover scripts — not federal shalls.
