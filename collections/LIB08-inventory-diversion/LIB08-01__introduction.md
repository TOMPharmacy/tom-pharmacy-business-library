# Inventory as service capacity and cash exposure
**Collection:** LIB-08 Inventory as service capacity and cash exposure (Topic 06: Inventory, purchasing & diversion)  
**Document type:** introduction  
**Audience:** Owners, PICs, inventory leads, consultant pharmacists, ASC medication ops leads  
**Jurisdiction:** US-wide DEA/FDA DSCSA; Texas Class C (and Class A discovery) verification worksheet  
**Risk tier:** L1 (map) / L3 (shall clusters)  
**Version:** 0.3-final-draft  
**Last verified:** 2026-09-19  
**Not:** legal advice, clinical protocol, diversion how-to for illicit purposes, 340B ops playbook, or guarantee of inspection outcomes

**L3 review warning:** This is a private research draft. Do **not** treat ChatGPT (or any LLM) output as legal advice, board interpretation, or a compliance guarantee. Before operational use, have a Texas-licensed pharmacist and qualified counsel review L3 claims against current primary sources.

## What this helps you decide or do
Inventory integrity is both **service capacity** (can you fill the next prescription or ASC case?) and **cash exposure** (turns, shrink, CS variance, specialty COGS float). This introduction maps why DEA effective-controls duties [1], theft/loss clocks [2], DSCSA dispenser ATP/suspect-product duties [5], and Texas Class C perpetual/receiving controls [7] belong in the same business conversation. Use companion tools to design purchasing, receiving, and discrepancy workflows. Diversion and DSCSA failures are continuity events—not only checkboxes.

## Who should use it / who else to involve
- **Primary:** PIC and inventory lead.
- **Owner:** capital for cabinets, cameras, perpetual modules, DSCSA tooling.
- **Counsel:** L3 shall interpretations; 340B (held).
- **Consultant pharmacist:** ASC / Class C models (see Topic 10 / LIB11).
- **Quality lead:** wire Form 106 and suspect-product events into incident learning (Topic 08 / LIB09).

## How to use the companion tools
| Companion | Use |
|-----------|-----|
| `LIB08-02__business_workbook.md` | Turns, shrink, CS variance, Form 106 discovery clock (blank $) |
| `LIB08-03__authority_map.md` | Federal vs Texas shall map with live URLs |
| `LIB08-04__workflow.md` | Purchase → receive → stock → count → report |
| `LIB08-05__template_pack.md` | Receiving, ATP log, dual-control, theft/loss cover sheet |
| `LIB08-06__implementation.md` | Badge, camera, perpetual, DSCSA inbox roles |
| `LIB08-07__quality_toolkit.md` | Variance metrics, mock Form 106 drill, CAPA |
| `LIB08-08__client_development.md` | ASC/clinic inventory diagnostic offer (synthetic B2B) |
| `../CLAIM-LEDGER.csv` | Claim status (supported / held) |

## Core content
### Why inventory is a license and trust asset
Registrants **shall** provide effective controls against theft and diversion [1]. DEA evaluates security systems against 21 CFR 1301.72–1301.76 factors; substantial compliance may be deemed sufficient after overall evaluation [1]. Pharmacies must keep Schedule I/II inventories and records separate; III–V separately or readily retrievable [3]. Theft or **significant loss** triggers written Field Division notice within **one business day** of discovery plus Form 106 via TLR [2].

### DSCSA as inventory integrity
Dispensers confirm trading partners are licensed/registered; quarantine and investigate suspect prescription drugs; notify FDA and trading partners if illegitimate [5]. Product-tracing FAQ distinguishes transfer for a **specific patient need** from stock replenishment transfers [6]. Peer-reviewed DSCSA review orients health-system leaders to dispenser roles [10]—prefer FDA primary for must claims.

### Practice frameworks (not federal shall)
ASHP controlled-substance diversion prevention guidelines provide a system-based CSDPP framework (perpetual inventory, chain-of-custody, surveillance) [8]. A 2024 hospital survey found variation and gaps in PAR monitoring, cameras, receiving validation, and stocking witness verification [9]. ML analytics may flag high-risk movements earlier—**discovery** for quality toolkit, not a mandated method [11].

### Synthetic vignette (fictional)
“Riverbend Rx” (COM) finds a C-II bottle short at closing cycle count. PIC opens variance log, secures remaining stock, reviews camera window, and—if significant loss—starts Field Division notice clock [2]. No patient names in shared worksheets.

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
