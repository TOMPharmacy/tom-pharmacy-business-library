# Citation and document format — Basecamp Pharmacy Business Library

**Purpose:** One familiar shape so pharmacists can skim any pack the same way.  
**Date:** 2026-09-19. Private draft standard for first-10 enrich pass.

## 1. Document front matter (every prose artifact)

```markdown
# [Clear task title]
**Collection:** LIB-XX Topic name  
**Document type:** introduction | business_workbook | authority_map | workflow | template_pack | implementation | quality_toolkit | client_development  
**Audience:** …  
**Jurisdiction:** US-wide; Texas verification worksheet attached where needed  
**Risk tier:** L1 | L2 | L3  
**Version:** 0.2-enrich  
**Last verified:** YYYY-MM-DD  
**Not:** legal advice, clinical protocol, or guarantee of payment/compliance
```

## 2. Body order (same every time)

1. **What this helps you decide or do** (3–5 sentences)  
2. **Who should use it / who else to involve**  
3. **How to use the companion tools** (named files)  
4. **Core content** (steps, tables, or worksheets)  
5. **Setting branches** — Community | ASC/consulting | Clinic-embedded | Specialty/infusion/compounding | Telepharmacy (skip what does not apply)  
6. **Local adaptation** — Texas (or other) verification checklist  
7. **Sources** — numbered list in house style  
8. **Unresolved / held** — honest gaps  

## 3. House citation style (pharmacist-familiar)

Numbered citations in text like journals: `... counseling documentation [3].`

**Reference list format (AMA-like, link + ID when available):**

- **Journal article:** Author AA, Author BB. Title. *Journal*. Year;vol(issue):pages. doi:10.… PMID:… URL (accessed YYYY-MM-DD).  
- **Agency webpage / guidance:** Agency. Title. Published/updated date if known. URL. Accessed YYYY-MM-DD.  
- **Regulation:** Title number CFR section (year of retrieval). URL to eCFR. Accessed YYYY-MM-DD.  
- **Statute:** Jurisdiction Code § section. URL. Accessed YYYY-MM-DD.  
- **Book / handbook chapter:** same AMA pattern; no wholesale copying.

**Rules**

- Prefer **controlling** sources for must/shall (statute, regulation, board, CMS, DEA, FDA, OCR).  
- Prefer **peer-reviewed or major professional** sources for “what works in practice,” workforce, quality methods, business outcomes.  
- Secondary blogs/news = discovery only; do not leave as sole support for material claims.  
- Record **retrieval date** and **rights: link-only** (no pasting licensed full text).  
- If not retrieved live → status **unverified** or **held**, never “supported.”

## 4. Claim ledger columns (enriched)

`claim_id, claim_text, status, source_type, citation, url, pmid_or_doi, retrieved, risk_tier, reviewer_needed, notes`

`source_type`: statute | regulation | agency_guidance | journal | professional_org | business_data | tom_original  
`status`: supported | unverified | held

## 5. Proof pass checklist (per claim)

- [ ] URL opens to the cited document (not a search SERP)  
- [ ] Quote/paraphrase matches section actually read  
- [ ] Effective/updated date checked for supersession  
- [ ] Journal claims have PMID or DOI when available  
- [ ] Jurisdiction labeled (federal vs Texas vs other)  
- [ ] Risk tier still correct  

*End format standard.*
