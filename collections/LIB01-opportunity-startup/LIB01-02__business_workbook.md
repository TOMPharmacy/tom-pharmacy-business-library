# From service idea to opening cash plan
**Collection:** LIB-01 Pharmacy business opportunity and startup  
**Document type:** business_workbook  
**Audience:** Pharmacy business operator; Community practice pharmacist; Pharmacy accountant; State pharmacy counsel  
**Jurisdiction:** US-wide; Texas verification worksheet attached where needed  
**Risk tier:** L1  
**Version:** 0.3-final-draft  
**Last verified:** 2026-09-19  
**Not:** legal advice, clinical protocol, or guarantee of payment/compliance


## What this helps you decide or do

Translate a chosen pharmacy concept into dependencies, cost categories, and cash scenarios using **your** inputs. SBA guidance separates one-time vs monthly expenses and offers a break-even method: Fixed Costs ÷ (Price − Variable Cost per unit) [16]. This workbook never invents pharmacy payback months or ROI [held: 01-C016]. Independent pharmacy turnover context [9][19] and payment-model sustainability concerns [20] motivate a documented working-capital buffer — size it yourself with a CPA.

## Who should use it / who else to involve

Decision owner and PIC candidate complete assumptions; CPA builds projections you will show a lender; counsel confirms entity/FEIN timing. Do not treat SBA 7(a) eligibility language as a loan promise — 7(a) may fund working capital, equipment, real estate, and ownership changes up to a $5M maximum via lenders [17], but underwriting is fact-specific.

## How to use the companion tools

| Tool | Path | Use |
|------|------|-----|
| Cash assumptions CSV | `tools/LIB01-cash-assumptions-blank.csv` | Enter quotes only |
| Stop/proceed log | `tools/LIB01-stop-proceed-log.md` | Gate decisions |
| Enrich worksheet | `../artifacts/01-stop-proceed-decision-worksheet.md` | Full prompt set |
| Launch cash CSV (enrich) | `../artifacts/01-launch-cash-assumptions.csv` | Cross-check categories |
| Class map | `../artifacts/01-texas-class-selection-map.md` | Class → cost drivers |

**Method:** (1) freeze the concept from LIB01-01, (2) fill one-time and monthly columns from vendor/CPA quotes, (3) run sensitivity by changing *your* volume and margin assumptions — never paste invented template rates, (4) record stop/proceed.

## Core content

### Tab logic (implement in spreadsheet or keep CSV + notes)

1. **Setup** — Setting label; TX class hypothesis [1][2]; DEA needed Y/N [7][8]; NPI path [13].  
2. **One-time** — Licenses, buildout, equipment, opening inventory, legal/CPA. Fee *amounts* stay blank; link TSBP fee page [5].  
3. **Monthly burn** — Rent, payroll, insurance, software, wholesaler terms (user), delivery (tele).  
4. **Revenue stubs** — User-entered only; payment timing deferred to LIB05. Qualitative pressure from DIR/payment literature [20] is context, not a rate.  
5. **Sensitivity** — Best / base / downside using *your* inputs; document which assumption moved.  
6. **Funding path** — Cash, partners, or lender materials (business plan, expense sheet, projections per SBA [16]); optional 7(a) exploration [17].

### Synthetic example (FICTIONAL dollars — replace)

**Setting: COM.** Fictional “Oak Street Planning LLC” enters: buildout quote $__ (blank until GC bid), opening inventory quote pending wholesaler, PIC LOI salary $__, rent $__. They compute months of buffer as `cash_on_hand ÷ monthly_burn` using only entered numbers. They do **not** claim “industry average payback.” Decision: proceed-with-conditions pending wholesaler credit letter [5].

### Dependency list before “opening cash plan” is credible

- Entity + FEIN stable (TX cancel risk if changed mid-app) [4]  
- Class and sterile scope frozen [1][10]  
- PIC identified for pre-inspect [6]  
- Wholesaler credit letter path [5]  
- DEA/NPI tracks listed if applicable [7][8][13]  
- Cash CSV has no blank critical rows (or blanks explicitly accepted as stop)

## Setting branches

### Community (independent / retail)
Apply open-door vs closed-door, hours, counseling space, and delivery footprint. Keep sterile compounding out of Class A-only workflows unless the sterile subclass path is confirmed with the board. Use local need evidence; do not invent script volume or ROI.

### ASC / consulting pharmacy
Separate facility medication-use accountability from consultant pharmacist scope. Confirm institutional / Class C sequencing and HHSC (or equivalent) facility status before promising start dates. Document who owns procurement, storage, and controlled-substance records in writing.

### Clinic-embedded
Clarify limited formulary vs full community dispensing. Watch entity boundaries (clinic vs pharmacy FEIN) for billing and ownership. In Texas, Class D shall not be issued to a physician's office — verify class fit before filing.

### Specialty / infusion / compounding
Branch early on 503A vs 503B, sterile classification, prior-authorization load, and COGS float. Do not paste USP chapter text; link when verified. Keep all patient and dollar examples synthetic and labeled fictional.

### Telepharmacy / delivery
Separate remote verification roles from driver logistics. Multi-state practice needs location-specific registrations. Allocate delivery cost as its own cash line so logistics margin stays visible on the dashboard.


## Local adaptation — Texas verification checklist

| # | Check | Source | Done? |
|---|-------|--------|-------|
| T1 | Class matches services (A/A-S/C/D/E/G etc.) | [1][2] | ☐ |
| T2 | Separate license per location (§560.102) | [3] | ☐ |
| T3 | Class A packet items: ownership/FEIN/SOS, officers, lease, LIC-018, wholesaler credit, LIC-000A | [5] | ☐ |
| T4 | PIC + owner available for pre-inspect (291.1(e)) or waiver path | [5][6] | ☐ |
| T5 | Mid-review ownership/officer/location change cancels app | [4] | ☐ |
| T6 | DEA Form 224 if CS; each location separate | [7][8] | ☐ |
| T7 | NPI path identified (NPPES/EFI/CMS-10114) | [13] | ☐ |
| T8 | Class C: HHSC facility substantially complete before expecting license | [12] | ☐ |
| T9 | Class D not physician office; Class G no bulk/dispense | [14][15] | ☐ |
| T10 | Other states: verify home board — do not assume TX rules | held 01-C017 | ☐ |



## Additional operating notes

### Evidence discipline
Every material “shall” in launch conversations must trace to statute, regulation, or board/agency page with a retrieval date [see Sources]. Secondary blogs are discovery only. Journal articles on turnover and access [9][18][19] support diligence framing, not numeric guarantees.

### Coordination with later collections
- Ownership change after open → LIB02.  
- Daily request-to-handoff → LIB03.  
- Payer cash and denials → LIB05.  
- Workforce/PIC coverage → LIB06.

### Synthetic multi-setting stress questions
1. If we add delivery next quarter, which counseling/delivery rows reopen?  
2. If an ASC asks us to manage their med room, are we selling retail Class A services or Class C consulting?  
3. If sterile demand appears, do we stop and re-class rather than “just start”? [1][10]

Document answers in the decision log before changing marketing copy.

## Sources

1. Texas State Board of Pharmacy (TSBP). Apply | New Pharmacy License. https://www.pharmacy.texas.gov/applicants/new-pharmacy.asp. Accessed 2026-09-19.
2. Tex. Occ. Code §560.051. https://texas.public.law/statutes/tex._occ._code_section_560.051. Accessed 2026-09-19.
3. Tex. Occ. Code §560.102. https://texas.public.law/statutes/tex._occ._code_section_560.102. Accessed 2026-09-19.
4. TSBP. Apply | New Pharmacy License — mid-review cancel banner. Same as [1]. Accessed 2026-09-19.
5. TSBP. Class A Application Checklist (PDF). https://www.pharmacy.texas.gov/files_pdf/INSTRUCTIONS_CLASS_A_PHY.pdf. Accessed 2026-09-19.
6. TSBP. Class A checklist citing Rule 291.1(e)/(f). Same PDF as [5]. Accessed 2026-09-19.
7. DEA. Pharmacist's Manual (2022). https://www.deadiversion.usdoj.gov/GDP/(DEA-DC-046R1)(EO-DEA154R1)_Pharmacist's_Manual_DEA.pdf. Accessed 2026-09-19.
8. DEA. Registration. https://www.deadiversion.usdoj.gov/drugreg/registration.html. Accessed 2026-09-19.
9. Mattingly TJ 2nd et al. Community Pharmacy Turnover… *JAMA Netw Open*. 2025. PMID:40748545. https://pubmed.ncbi.nlm.nih.gov/40748545/. Accessed 2026-09-19.
10. FDA. FD&C Act Provisions that Apply to Human Drug Compounding. https://www.fda.gov/drugs/human-drug-compounding/fdc-act-provisions-apply-human-drug-compounding. Accessed 2026-09-19.
11. 21 CFR §207.13. https://www.ecfr.gov/current/title-21/chapter-I/subchapter-C/part-207/subpart-A/section-207.13. Accessed 2026-09-19.
12. TSBP. Class C Application Checklist. https://www.pharmacy.texas.gov/files_pdf/INSTRUCTIONS_CLASS_C_PHCY.pdf. Accessed 2026-09-19.
13. CMS. How to Apply (NPI). https://www.cms.gov/medicare/regulations-guidance/administrative-simplification/how-apply. Accessed 2026-09-19.
14. TSBP. Class D note (not physician office). Same as [1]. Accessed 2026-09-19.
15. TSBP. Class G note (no bulk/dispense). Same as [1]. Accessed 2026-09-19.
16. SBA. Calculate your startup costs. https://www.sba.gov/business-guide/plan-your-business/calculate-your-startup-costs. Accessed 2026-09-19.
17. SBA. 7(a) loans. https://www.sba.gov/loans/7a-loans/. Accessed 2026-09-19.
18. Berenbrok LA et al. Access to community pharmacies… *J Am Pharm Assoc*. 2022. PMID:35965233. https://pubmed.ncbi.nlm.nih.gov/35965233/. Accessed 2026-09-19.
19. Guadamuz JS et al. More US Pharmacies Closed Than Opened In 2018–21… *Health Aff*. 2024. doi:10.1377/hlthaff.2024.00192. Accessed 2026-09-19.
20. Payment models and the sustainability of community pharmacy practice. PMC11730775. PMID:39811824. Accessed 2026-09-19.

*Rights: link + cite only. No licensed full text pasted.*


## Unresolved / held

Do **not** promote held claims to supported status without primary confirmation and reviewer sign-off.

| Claim ID | Held statement | Why held | Reviewer |
|----------|----------------|----------|----------|
| 01-C016 | Fixed cash runway $X / payback Y months | Invented ROI forbidden | CPA + owner |
| 01-C017 | All US states use identical ownership/facility rules | False generalization | Counsel |
| 01-C018 | NCPDP ID issued automatically with NPI | Unverified commercial path | Revenue cycle |
| 01-C019 | Class C before HHSC substantially complete | Contradicts checklist indication | Counsel + ASC admin |
| — | Live TSBP fee amounts; remote TX packet; USP chapters; PBM timelines | See UNRESOLVED.md | Ops / PIC |

