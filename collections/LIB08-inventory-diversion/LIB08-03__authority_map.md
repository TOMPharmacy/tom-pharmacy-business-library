# Trading partner tracing and controlled stock duties
**Collection:** LIB-08 Inventory as service capacity and cash exposure (Topic 06: Inventory, purchasing & diversion)  
**Document type:** authority_map  
**Audience:** Owners, PICs, inventory leads, consultant pharmacists, ASC medication ops leads  
**Jurisdiction:** US-wide DEA/FDA DSCSA; Texas Class C (and Class A discovery) verification worksheet  
**Risk tier:** L3  
**Version:** 0.3-final-draft  
**Last verified:** 2026-09-19  
**Not:** legal advice or complete regulatory encyclopedia

**L3 review warning:** This is a private research draft. Do **not** treat ChatGPT (or any LLM) output as legal advice, board interpretation, or a compliance guarantee. Before operational use, have a Texas-licensed pharmacist and qualified counsel review L3 claims against current primary sources.

## What this helps you decide or do
Locate **controlling** instruments for CS security/records, theft/loss reporting, DSCSA dispenser duties, and Texas Class C inventory/receiving shalls. Reference-only matrix—counsel confirms applicability to your entity and state.

## Who should use it / who else to involve
PIC + counsel (required for L3); owner; consultant pharmacist for ASC Class C.

## How to use the companion tools
Use before changing receiving SOPs or DSCSA software. Cross-check every “shall” against live eCFR / TSBP PDF dates.

## Core content — authority matrix
| Layer | Instrument | Why it matters | Link | Risk |
|-------|------------|----------------|------|------|
| Federal security | 21 CFR §1301.71 | Effective controls **shall**; evaluation factors | eCFR [1] | L3 |
| Federal records | 21 CFR Part 1304 / §1304.04(h) | Inventories; I/II separate; III–V separate or readily retrievable | eCFR [3] | L3 |
| Theft/loss | 21 CFR §1301.76(b) via DEA TLR page | 1 business-day Field Division notice + Form 106 | DEA [2] | L2 |
| Orientation | DEA Pharmacist's Manual | Registration, security, recordkeeping business controls | DEA PDF [4] | L3 |
| Supply chain | FDA DSCSA pharmacist overview | ATP; suspect/illegitimate quarantine & notify | FDA [5] | L2 |
| Tracing FAQ | FDA DSCSA tracing FAQ | Patient-need transfer vs stock replenishment | FDA [6] | L2 |
| Texas Class C | 22 TAC §§291.73–291.75 (May 2024 PDF) | PIC diversion system; perpetual C-II; invoice initialing | TSBP [7] | L2–L3 |
| Practice (not shall) | ASHP diversion guidelines | CSDPP framework | PMID:36208462 [8] | L2 |
| Discovery | HRSA 340B hub | Clinic/specialty purchasing models | HRSA [12] | L3 **ops HELD** |

**Do not cite as law:** wholesaler marketing emails, blog “DIR calculators,” unverified secondary summaries.

### Decision prompts (synthetic)
1. Is this site a DEA registrant pharmacy? → 1301.71 + 1304 apply [1][3].  
2. Is product suspect under DSCSA? → quarantine/investigate path [5].  
3. Texas Class C? → perpetual C-II + invoice initials [7].  
4. 340B covered entity? → stop and escalate to counsel; no ops how-to here [12].

### Evidence discipline
Every “shall” in operational SOPs must trace to a supported ledger row (DEA, FDA DSCSA, or TSBP Class C) before training staff [1][2][3][5][7]. ASHP diversion guidelines and survey literature inform **how teams organize** controls; they do not rewrite CFR text [8][9]. Machine-learning diversion analytics are discovery-only for the quality toolkit [11]. Synthetic examples in worksheets use fictional NDCs and site names — never paste real patient or DEA registration numbers into shared Basecamp drafts.

## Setting branches
Skip any branch that does not apply. Synthetic examples only — no real patient or facility identifiers.

### Community (independent / retail)
Treat CS cabinet culture, cycle counts, and wholesaler ATP checks as everyday controls—not annual paperwork [1][5]. Shrink and book-to-physical variance are cash problems as well as diversion signals; use the workbook blanks rather than invented industry shrink percentages. Class A PIC diversion duties need a current Class A PDF line-audit before stating community-specific shalls (see Unresolved). Synthetic tip only: many community teams reconcile high-risk CS counts before close on days the pharmacy dispenses CS — this is **editorial**, not a federal shall.

### ASC / consulting pharmacy
Floor stock and automated dispensing cabinets need restock verification, perpetual Schedule II inventory under Texas Class C, and pharmacist initials on CS invoices [7]. Pair this pack with LIB11 for consultant visit cadence and written agreements. ADC downtime recovery and Board notice triggers sit in the quality/continuity pack (LIB09) but inventory evidence still lives here.

### Clinic-embedded
Purchasing-channel segregation (e.g., GPO vs 340B) is **discovery only** in this pack. HRSA 340B operational diversion / duplicate-discount how-to remains **HELD** pending counsel and live HRSA primary detail [12]. Do not invent split-inventory SOPs from secondary blogs.

### Specialty / infusion / compounding
High-value and cold-chain products create parallel quarantine tracks: diversion suspicion versus temperature excursion. Both need labeled hold bins and documentary evidence; do not release to dispense until the owning PIC clears the hold. Synthetic editorial only for treating cold-chain quarantine as parallel to diversion quarantine.

### Telepharmacy / delivery
Document chain-of-custody for CS packages separately from non-CS when delivery or remote stock rooms are in scope (editorial practice tip; confirm with counsel/PIC policy). Remote access to stock areas still falls under DEA effective-controls evaluation factors [1]. Delivery seal numbers and receiver identity belong in the receiving/discrepancy templates.


## Local adaptation — Texas verification checklist

Complete with PIC (and counsel for L3 rows) against **live** primary pages on the day you rely on them. Forms and PDF revisions change.

- [ ] Confirm whether the site is Class A (community) vs Class C (institutional/ASC) before applying Class C-only shalls [7].
- [ ] For Class C: PIC diversion-control system; Schedule II **perpetual** inventory; pharmacist initials + receipt date on CS supplier invoices [7].
- [ ] Confirm Form 106 / TLR account ownership and Field Division contact path [2].
- [ ] Biennial CS inventory timing and Schedule I/II vs III–V record separation under 21 CFR 1304 [3].
- [ ] DSCSA authorized trading partner (ATP) check cadence with wholesaler/switch [5].
- [ ] Class A PIC diversion duties: pull current Class A PDF from TSBP before stating community-specific shalls (**unresolved depth**).
- [ ] 340B: do **not** invent diversion/duplicate-discount how-to — counsel + HRSA primary [12].


## Sources
1. 21 CFR §1301.71. eCFR. https://www.ecfr.gov/current/title-21/chapter-II/part-1301/subject-group-ECFRa7ff8142033a7a2/section-1301.71. Accessed 2026-09-19.
2. DEA Diversion Control. Theft/Loss Reporting (Form 106 / TLR). https://www.deadiversion.usdoj.gov/21cfr_reports/theft/theft-loss.html. Accessed 2026-09-19.
3. 21 CFR Part 1304 (incl. §1304.04(h)). eCFR. https://www.ecfr.gov/current/title-21/chapter-II/part-1304. Accessed 2026-09-19.
4. DEA Diversion Control. Pharmacist's Manual (PDF). https://www.deadiversion.usdoj.gov/GDP/(DEA-DC-046R1)(EO-DEA154R1)_Pharmacist's_Manual_DEA.pdf. Accessed 2026-09-19. Rights: link-only.
5. FDA. Pharmacists: Utilize DSCSA Requirements to Protect Your Patients. https://www.fda.gov/drugs/drug-supply-chain-security-act-dscsa/pharmacists-utilize-dscsa-requirements-protect-your-patients. Accessed 2026-09-19.
6. FDA. DSCSA Product Tracing Requirements FAQ. https://www.fda.gov/drugs/drug-supply-chain-security-act-dscsa/drug-supply-chain-security-act-product-tracing-requirements-frequently-asked-questions. Accessed 2026-09-19.
7. Texas State Board of Pharmacy. Class C Pharmacy Rules (May 2024 PDF). https://www.pharmacy.texas.gov/files_pdf/BN/May24/C.3.2.1.pdf. Accessed 2026-09-19.
8. Clark J et al. ASHP Guidelines on Preventing Diversion of Controlled Substances. *Am J Health Syst Pharm*. 2022. doi:10.1093/ajhp/zxac246. PMID:36208462. Accessed 2026-09-19.
9. Insights from a National Survey on Controlled Substance Diversion Practices. *Pharmacy (Basel)*. 2024;12(6):183. PMID:39728848. doi:10.3390/pharmacy12060183. Accessed 2026-09-19.
10. Brechtelsbauer ED et al. Review of the 2015 Drug Supply Chain Security Act. *Hosp Pharm*. 2016;51(6):493-500. PMID:27354753. Accessed 2026-09-19.
11. Knight T et al. Detecting drug diversion using ML/analytics. PMC9353695. https://pmc.ncbi.nlm.nih.gov/articles/PMC9353695/. Accessed 2026-09-19. Discovery only.
12. HRSA. Office of Pharmacy Affairs / 340B. https://www.hrsa.gov/opa. Accessed 2026-09-19. Discovery hub only; ops detail **HELD**.


## Unresolved / held
- **HELD:** HRSA 340B operational diversion / duplicate-discount how-to (CDN blocks; discovery URL only) [12].
- **HELD (editorial):** Daily CS cycle-count before close; cold-chain quarantine parallel track; telepharmacy CS custody docs — synthetic practice tips, not shalls.
- Class A (community) PIC diversion duties need deeper Class A PDF line-audit before COM-specific shall claims.
- No invented inspection-pass or “DEA-approved” product claims.
