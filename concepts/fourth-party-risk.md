---
title: Fourth Party Risk
created: 2026-04-10
updated: 2026-04-10
type: concept
tags: [fourth-party-risk, supply-chain-risk, tprm]
sources: []
---

# Fourth Party Risk

## Definition

Fourth party risk (also called Nth-party risk) is the risk arising from an organisation's vendors' own vendors, subcontractors, and sub-processors — the organisations in the supply chain beyond the direct contractual relationship.

## The Problem

Most TPRM programs focus on direct (Tier 1) vendors. However:

> **82% of Australian companies do not extend risk assessments beyond Tier 1 suppliers** — McGrathNicol/YouGov, August 2024

This creates massive blind spots because:
- Tier 1 vendors often outsource critical functions to sub-processors
- A disruption at a fourth party can cascade up through multiple tiers
- [[oaic-notifiable-data-breaches]] obligations apply to data handled by any processor, including sub-processors

## Practical Examples

- A bank uses a cloud provider (Tier 1) → the cloud provider uses a specific data centre (fourth party) → if the data centre fails, the bank's service is disrupted
- A company uses a SaaS HR system (Tier 1) → the SaaS uses a background check provider (fourth party) → personal data is processed beyond the company's visibility

## Managing Fourth Party Risk

1. **Contractual requirements** — require Tier 1 vendors to flow down data protection and audit obligations
2. **Sub-processor disclosure** — require vendors to disclose their sub-processors
3. **Automated discovery** — some TPRM tools (e.g., BitSight) can identify fourth-party relationships
4. **Concentration analysis** — identify when multiple Tier 1 vendors use the same fourth party

## Australian Regulatory Context

- [[apra-cps-230]] requires assessment of risks from service providers including their sub-processors
- [[oaic-notifiable-data-breaches]] — entities liable for breaches through any sub-processor
- [[soci-act]] — supply chain risk management must cover sub-processors

## Related

- [[supply-chain-risk-concept]] — the broader risk domain
- [[tprm-concept]] — the management discipline
- [[vendor-tiering]] — classification approach that often neglects fourth parties
