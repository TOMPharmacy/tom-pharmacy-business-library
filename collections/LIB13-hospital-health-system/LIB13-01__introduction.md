# Map the hospital pharmacy operating environment
**Collection:** LIB-13 Hospital and health-system pharmacy  
**Document type:** introduction  
**Audience:** Hospital pharmacy directors; informatics pharmacists; nursing leaders; hospital compliance officers  
**Jurisdiction:** US CMS 42 CFR §482.25; Texas Class C; DEA; CMS EP  
**Risk tier:** L2 (model) / L3 (CoP/Class C)  
**Version:** 0.3-final-draft  
**Last verified:** 2026-09-19  
**Not:** legal advice, accreditation manual copy, clinical protocol, or survey-outcome guarantee

**L3 review warning:** This is a private research draft. Do **not** treat ChatGPT (or any LLM) output as legal advice, board interpretation, or a compliance guarantee. Before operational use, have a Texas-licensed pharmacist and qualified counsel review L3 claims against current primary sources.

## What this helps you decide or do
Map inpatient distribution, clinical services, governance (P&T), technology, and diversion controls against CMS hospital pharmaceutical-services CoP orientation [1] and Texas Class C rules [2]. Use ASHP national survey data as practice context for ADC/autoverification prevalence — not as shall statements [7][9].

## Who should use it / who else to involve
Pharmacy director; CNO liaison; compliance; informatics; medical staff pharmacy committee chair.

## How to use the companion tools
| Companion | Use |
|-----------|-----|
| `LIB13-01__introduction.md` | Operating environment map |
| `LIB13-02__business_workbook.md` | Service-change business case |
| `LIB13-03__authority_map.md` | Authority & governance evidence |
| `LIB13-04__workflow.md` | Governance routing for med-system changes |
| `LIB13-05__template_pack.md` | Committee & exception tools |
| `LIB13-06__implementation.md` | Tech deployment & reconciliation tests |
| `LIB13-07__quality_toolkit.md` | Performance & risk review |
| `LIB13-08__client_development.md` | Internal service agreements |

## Core content — environment map
| Domain | Questions | Evidence |
|--------|-----------|----------|
| License / PIC | Class C bed model; PIC limits [2] | License + PIC letter |
| CoP pharmacy | Pharmacist direction; formulary; CS records [1] | P&P + committee minutes |
| Distribution | ADC vs cartfill; machine-readable checks [7] | Ops metrics |
| Clinical services | Unit coverage; stewardship [9] | Service grid |
| EP / continuity | Pharmacy role in facility EP [4] | EP annex |
| Diversion | ADC discrepancy workflow [5] | Diversion committee |

## Setting branches
Skip any branch that does not apply to your operation. Synthetic examples only — no real patient or facility identifiers.

### Community (independent / retail)
Hospital CoP §482.25 does not govern freestanding Class A community pharmacies. If a health system owns retail sites, keep license classes and dashboards separate.

### ASC / consulting pharmacy
Hospital Class C ≠ freestanding ASC — bed-count and continuous-supervision rules differ [2]. Cross-link LIB11 for ASC-specific CfC §416.48.

### Clinic-embedded
Hospital outpatient clinics may share formulary/EHR but still need clear medication-use accountability and, when Part B clinic billing applies, different payment rules than inpatient.

### Specialty / infusion / compounding
Sterile compounding and specialty hubs need separate privilege and USP-linked procedures (link only). Diversion risk rises with ADC floor stock [5][7].

### Telepharmacy / delivery
Remote order verification can support coverage but does not erase Texas on-site supervision rules for Class C by bed count [2]. Document downtime paths.

## Local adaptation — Texas verification checklist
- [ ] Confirm Texas Class C license and bed-count supervision model [2].
- [ ] Map PIC appointment and 10-day change notice [6].
- [ ] Align hospital pharmacy P&P with CoP §482.25 pharmaceutical services orientation [1].
- [ ] Confirm DEA effective controls and diversion reporting path [3][5].
- [ ] Align pharmacy with facility CMS Emergency Preparedness program [4].
- [ ] BAAs for vendors touching PHI [8].
- [ ] Do not paste TJC/DNV manual text — link facility standards lead instead (U13-02).

## Sources
1. 42 CFR §482.25 Condition of participation: Pharmaceutical services. eCFR. https://www.ecfr.gov/current/title-42/chapter-IV/subchapter-G/part-482/subpart-C/section-482.25. Accessed 2026-09-19.
2. TSBP. Class C Pharmacy Rules (May 2024 PDF). https://www.pharmacy.texas.gov/files_pdf/BN/May24/C.3.2.1.pdf. Accessed 2026-09-19.
3. 21 CFR §1301.71. eCFR. Accessed 2026-09-19.
4. CMS. Emergency Preparedness Rule. https://www.cms.gov/medicare/health-safety-standards/quality-safety-oversight-emergency-preparedness/emergency-preparedness-rule. Accessed 2026-09-19.
5. Clark J et al. ASHP Guidelines on Preventing Diversion of Controlled Substances. PMID:36208462. Accessed 2026-09-19.
6. TSBP. Pharmacy Update Forms — PIC change. https://www.pharmacy.texas.gov/licensees/pharmacy-update-forms.asp. Accessed 2026-09-19.
7. ASHP National Survey … Operations and Technology—2023. PMID:38780002. Accessed 2026-09-19.
8. HHS OCR. Covered Entities and Business Associates. Accessed 2026-09-19.
9. ASHP National Survey … Clinical Services and Workforce—2024. doi:10.1093/ajhp/zxaf150. Accessed 2026-09-19.
10. ASHP Guidelines: Minimum Standard for Pharmacies in Hospitals. doi:10.2146/sp130001. Accessed 2026-09-19.

## Unresolved / held

Do **not** promote held claims without primary confirmation.

| Claim ID | Held statement | Why held | Reviewer |
|----------|----------------|----------|----------|
| C13-006 | Governance routing for med-system changes | tom_original process design | Pharmacy director |
| U13-01 | Local medical-staff bylaws language | Facility-specific | Counsel |
| U13-02 | Accreditation manual text | Link/cite only — no copy | Quality |
