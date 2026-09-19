# Prepare a specialty team and interoperable records
**Collection:** LIB-15 Specialty pharmacy business and access services  
**Document type:** implementation  
**Audience:** Specialty pharmacy leaders; access specialists; REMS-trained pharmacists; healthcare counsel  
**Jurisdiction:** US FDA REMS; CMS Part D network/access orientation; Texas pharmacy licensure; HIPAA  
**Risk tier:** L2  
**Version:** 0.3-final-draft  
**Last verified:** 2026-09-19  
**Not:** legal advice, product REMS copy, network-acceptance guarantee, or therapy-availability promise

## What this helps you decide or do
Plan roles, evidence retrieval, and synthetic service drills (PA denial, REMS block, cold-chain exception).

## Who should use it / who else to involve
Ops manager; IT; REMS pharmacist; training.

## How to use the companion tools
| Companion | Use |
|-----------|-----|
| `LIB15-01__introduction.md` | Specialty dependency map |
| `LIB15-02__business_workbook.md` | Access-delay & cost model |
| `LIB15-03__authority_map.md` | Network/REMS evidence matrix |
| `LIB15-04__workflow.md` | Referral→dispense handoffs |
| `LIB15-05__template_pack.md` | Access case tools |
| `LIB15-06__implementation.md` | Team & records readiness |
| `LIB15-07__quality_toolkit.md` | Time-to-access measures |
| `LIB15-08__client_development.md` | Referrer factsheet |

## Core content
| Role | Core duties | Systems |
|------|-------------|---------|---|---|
| Access specialist | BI/PA tracking | CRM / hub |
| REMS pharmacist | Product gates | Sponsor portals |
| Verifying RPh | Final check | PMS |
| Shipment | Cold chain | Courier API |

Exception drill set: missing REMS enrollment; payer network reject; temperature excursion.

## Setting branches
Skip any branch that does not apply to your operation. Synthetic examples only — no real patient or facility identifiers.

### Community (independent / retail)
Independent pharmacies may dispense many specialty-tier drugs if licensed and REMS-capable; Part D plans generally may not restrict solely for specialty-tier placement [3]. Limited-distribution and REMS still apply product-by-product [1][2].

### ASC / consulting pharmacy
Periop specialty agents rare; do not conflate ASC med consulting with specialty access hubs.

### Clinic-embedded
Health-system specialty pharmacies face payer/manufacturer network limits — ASHP HSSP survey reports many sites dispense ≤50% of internal prescriptions due to restrictions [4].

### Specialty / infusion / compounding
Primary setting. Separate REMS enrollment, cold-chain, PA, and financial assistance workflows. Never paste REMS full text — link FDA/sponsor [1][2].

### Telepharmacy / delivery
Shipment and remote counseling support access but do not replace product REMS or state shipping rules. Track delivery exceptions separately in the dashboard.

## Local adaptation — Texas verification checklist
- [ ] Confirm Texas pharmacy license class supports the specialty services offered.
- [ ] Product REMS: pull current FDA REMS@FDA + sponsor pharmacy requirements before go-live [1][2] (U15-01).
- [ ] DEA registration if controlled specialty products.
- [ ] Part D / commercial network contracts reviewed by counsel — CMS Q&A is orientation not a contract [3].
- [ ] BAA with hubs, hubs-with-prescribers, and manufacturers’ portals as applicable [5].
- [ ] Cold-chain and DSCSA processes documented (link LIB08) without inventing pedigree rules.
- [ ] Marketing: no promise of therapy start dates or network acceptance.

## Sources
1. FDA. What's in a REMS? https://www.fda.gov/drugs/risk-evaluation-and-mitigation-strategies-rems/whats-rems. Accessed 2026-09-19.
2. FDA. Roles of Different Participants in REMS. https://www.fda.gov/drugs/risk-evaluation-and-mitigation-strategies-rems/roles-different-participants-rems. Accessed 2026-09-19.
3. CMS. Specialty Pharmacy Access Q&A. https://www.cms.gov/Medicare/Prescription-Drug-Coverage/PrescriptionDrugCovContra/Downloads/QASpecialtyAccess_051706.pdf. Accessed 2026-09-19.
4. ASHP Survey of Health-System Specialty Pharmacy Practice 2022. PMID:37742303. https://pubmed.ncbi.nlm.nih.gov/37742303/. Accessed 2026-09-19.
5. HHS OCR. Covered Entities and Business Associates. Accessed 2026-09-19.
6. 42 CFR §423.120 Access to covered Part D drugs (eCFR). Accessed 2026-09-19.
7. ASHP National Survey … Operations and Technology—2023. PMID:38780002. Accessed 2026-09-19.
8. ASHP guidelines: Minimum standard for ambulatory care pharmacy practice. PMID:26150573. Accessed 2026-09-19.
9. DEA Diversion Control. Registration. Accessed 2026-09-19.

## Unresolved / held

Do **not** promote held claims without primary confirmation.

| Claim ID | Held statement | Why held | Reviewer |
|----------|----------------|----------|----------|
| C15-006 | Product-specific REMS steps without product ID | Must use current FDA/sponsor materials | REMS RPh |
| U15-02 | Manufacturer limited-distribution contracts | Confidential held | Counsel |
| C15-004 | Stage-split cycle time metrics | tom_original KPI design | Ops |
