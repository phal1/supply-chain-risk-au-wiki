---
title: Wiki Schema
created: 2026-04-10
updated: 2026-04-10
type: meta
tags: [wiki-schema, meta]
---

# Wiki Schema: Supply Chain & Third Party Risk Management — Australia

## Domain

This wiki covers the Australian supply chain and third-party risk management (TPRM) market — including government regulation, compliance frameworks, key regulators, market size, vendors, and risk trends. Focus is on Australia but includes relevant international context where it shapes local practice.

## Conventions

- File names: lowercase, hyphens, no spaces (e.g., `apra-cps-230.md`, `soci-act.md`)
- Every wiki page starts with YAML frontmatter (see below)
- Use `[[wikilinks]]` to link between pages (minimum 2 outbound links per page)
- When updating a page, always bump the `updated` date
- Every new page must be added to `index.md` under the correct section
- Every action must be appended to `log.md`

## Frontmatter

```yaml
---
title: Page Title
created: YYYY-MM-DD
updated: YYYY-MM-DD
type: entity | concept | comparison | query | summary | regulation
tags: [from taxonomy below]
sources: [raw/articles/source-name.md]
---
```

## Tag Taxonomy

- **Regulation/Compliance:** regulation, standard, compliance, directive
- **Regulators:** regulator, apra, oaic, accc, cisc, asd
- **Risk Types:** cyber-risk, operational-risk, supply-chain-risk, data-risk, concentration-risk
- **Frameworks:** tprm, framework, bcm, business-continuity, incident-response
- **Sectors:** financial-services, healthcare, energy, telecommunications, food, transport, government
- **Concepts:** risk-assessment, vendor-tiering, fourth-party-risk, due-diligence, monitoring
- **Market:** vendor, market-size, trend, tender, contract
- **Incidents:** data-breach, outage, supply-disruption, cyber-incident
- **Meta:** wiki-schema, meta

## Page Thresholds

- **Create a page** when an entity/concept appears in 2+ sources OR is central to one source
- **Add to existing page** when a source mentions something already covered
- **DON'T create a page** for passing mentions, minor details, or things outside the domain
- **Split a page** when it exceeds ~200 lines — break into sub-topics with cross-links
- **Archive a page** when its content is fully superseded — move to `_archive/`, remove from index

## Entity Pages

One page per notable entity. Include:
- Overview / what it is
- Key facts and dates
- Relationships to other entities ([[wikilinks]])
- Source references

## Concept Pages

One page per concept or topic. Include:
- Definition / explanation
- Current state of knowledge
- Open questions or debates
- Related concepts ([[wikilinks]])

## Regulation Pages

One page per regulation/standard. Include:
- Full name and governing body
- Effective date and scope/applicability
- Key requirements
- Penalties / enforcement
- Related regulations ([[wikilinks]])

## Comparison Pages

Side-by-side analyses. Include:
- What is being compared and why
- Dimensions of comparison (table format preferred)
- Verdict or synthesis
- Sources

## Update Policy

When new information conflicts with existing content:
1. Check the dates — newer sources generally supersede older ones
2. If genuinely contradictory, note both positions with dates and sources
3. Mark the contradiction in frontmatter: `contradictions: [page-name]`
4. Flag for user review in the lint report
