---
title: Vendor Tiering
created: 2026-04-10
updated: 2026-04-10
type: concept
tags: [vendor-tiering, tprm, risk-assessment, due-diligence]
sources: []
---

# Vendor Tiering

## Definition

Vendor tiering (or supplier classification) is the process of categorising third-party relationships by their criticality and risk exposure to determine the appropriate level of due diligence, monitoring, and contractual control.

## Typical Tier Structure

| Tier | Description | Examples | Due Diligence |
|------|-------------|----------|---------------|
| **Tier 1 (Critical)** | Direct, material impact on operations or data | Core banking platform, cloud provider | Full assessment, Board-approved, ongoing monitoring |
| **Tier 2 (Important)** | Moderate impact if disrupted | Payroll provider, IT support | Standard assessment, periodic review |
| **Tier 3 (Standard)** | Low impact if disrupted | Office supplies, casual vendors | Basic questionnaire or none |
| **Tier 4 (One-off)** | Sporadic, low value | Conference vendors | Minimal or none |

## Key Classification Criteria

- **Criticality** — what happens to your operations if this vendor fails?
- **Data sensitivity** — does the vendor handle personal, financial, or confidential data?
- **Access** — does the vendor have network/system access to your environment?
- **Concentration** — is this a sole-source for a critical function?
- **Geopolitical exposure** — foreign ownership, offshore delivery?

## Fourth-Party Visibility Problem

McGrathNicol/YouGov (Aug 2024): **82% of Australian companies do not extend risk assessments beyond Tier 1 suppliers**

This creates a significant blind spot — most supply chain risk is actually in Tier 2+ relationships and their sub-processors.

## Relationship to CPS 230

[[apra-cps-230]] requires identification of **critical service providers** specifically — effectively mandating a Tier 1 classification process. The standard requires ongoing monitoring of these critical providers and contractual exit provisions.

## Related

- [[tprm-concept]] — the broader discipline
- [[fourth-party-risk]] — the risk tiering attempts to manage
- [[apra-cps-230]] — regulatory driver for critical provider identification
