# Wiki Log

> Chronological record of all wiki actions. Append-only.
> Format: `## [YYYY-MM-DD] action | subject`
> Actions: ingest, update, query, lint, create, archive, delete

## [2026-04-10] create | Wiki initialized
- Domain: Supply Chain & Third Party Risk Management — Australia
- Structure created with SCHEMA.md, index.md, log.md
- Directory tree: raw/articles, raw/papers, entities/, concepts/, comparisons/, queries/

## [2026-04-10] ingest | APRA CPS 230
- Sources: handbook.apra.gov.au, APRA PDF CPS 230 clean
- Created: raw/articles/apra-cps-230.md, entities/apra-cps-230.md, entities/apra.md
- Key finding: CPS 230 effective 1 July 2025, consolidates 5 prior standards, mandates Board-approved service provider management policy

## [2026-04-10] ingest | SOCI Act
- Source: CISC website + supplementary research
- Created: raw/articles/soci-act.md, entities/soci-act.md, entities/cisc.md
- Key finding: 11 critical infrastructure sectors, supply chain as standalone risk domain in 2022 amendments

## [2026-04-10] ingest | OAIC Notifiable Data Breaches
- Source: OAIC website, quarterly reports
- Created: raw/articles/oaic-notifiable-data-breaches.md, entities/oaic.md, entities/privacy-act.md
- Key finding: H2 2024 = 595 breaches (+15%), H1 2025 = 532, ~67% malicious

## [2026-04-10] create | Core concepts
- Created: concepts/tprm.md, concepts/supply-chain-risk.md, concepts/vendor-tiering.md, concepts/fourth-party-risk.md, concepts/regulatory-map.md
- Created: entities/asic.md, entities/upguard.md, entities/bitsight.md

## [2026-04-10] ingest | AICD Supply Chain Risk Article
- Source: AICD website, Megan Bonny, 11 April 2025
- Created: raw/articles/aicd-supply-chain-risk.md
- Key stats: ASIC survey — 44% manage third-party risk poorly, 69% small orgs minimal/no capabilities, ~58% don't test supplier cyber incident responses

## [2026-04-10] ingest | IIA Third Party Requirements
- Source: InConsult / IIA, September 2025
- Created: raw/articles/iia-third-party-requirements.md
- Key finding: IIA new mandatory Topical Requirements, effective September 2026, ~90% lack formal risk management

## [2026-04-10] ingest | McGrathNicol Supply Chain Study
- Source: McGrathNicol/YouGov, August 2024
- Created: raw/articles/mcgrat-nicol-supply-chain-audit.md
- Key finding: 82% of Australian companies do not extend risk assessments beyond Tier 1 suppliers

## [2026-04-10] create | Comparisons
- Created: comparisons/apra-cps-230-vs-soci-act.md

## [2026-04-10] update | index.md and log.md
- Updated index.md with all pages created

## [2026-04-10] update | Australian TPRM market overview (vendor landscape)
- Replaced queries/australian-tprm-market-overview.md with comprehensive vendor landscape
- 25+ software vendors covered across Tier 1, 2, 3
- Big 4 consulting firms added
- Boutique/specialist advisors added
- Market segmentation by buyer size

## [2026-04-10] create | Full vendor entity pages (19 new)
- Global: Black Kite, Riskonnect, ProcessUnity, Interos, ServiceNow TPRM, OneTrust, SecurityScorecard, Panorays, Dun & Bradstreet, MetricStream
- Australian: TPRM360, VendorInsight
- Consulting: Deloitte, PwC, KPMG, EY, McKinsey, Kroll, McGrathNicol, Cliffside Cybersecurity
- Updated index.md (now 44 pages total) and log.md

## [2026-04-10] push | GitHub
- Created GitHub repo: phal1/supply-chain-risk-au-wiki
- All 44 pages pushed to master
