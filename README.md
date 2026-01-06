# Starlight Retail — Public Product Roadmap

**Last updated:** 2026-01-06
**Maintained by:** Product Strategy (product@starlightretail.ltd) — for executive questions contact mammon@starlightretail.ltd

---

## Purpose
This repository documents Starlight Retail’s public product roadmap: what we are planning, the expected delivery phases, and how customers, partners and contributors can engage. The roadmap is a transparency vehicle — not a contractual commitment — intended to align engineering, partners, and commercial teams.

---

## Vision
Deliver enterprise-grade AI productivity and cloud security products that empower global teams to collaborate securely and efficiently. Our product family (including MeeTaker AI and companion offerings) prioritizes secure, scalable cloud-native services integrated with strategic partners (Google Cloud, Microsoft, IBM, AWS).

---

## Scope & Audience
- **Audience:** Customers, partners, ecosystem engineers, and internal stakeholders (Product, Engineering, GTM, Legal, Security).  
- **Scope:** Public product direction, feature areas, release phases, and contribution guidelines. Operational details, proprietary roadmaps, pricing and contractual commitments remain in internal systems.

---

## How to read this roadmap
- **Roadmap items** are represented as GitHub issues. Each issue includes:
  - Owner (team & product manager)
  - Target phase and quarter (when applicable)
  - Success criteria & dependencies (technical, compliance, GTM)
  - Partner impact assessment (if applicable)
- **Labels** summarize state and impact: `release-phase:preview`, `release-phase:ga`, `feature-area:<name>`, `partner-impact`, `security`, `compliance:gdpr`, `compliance:soc2`.

---

## Release phases
We use a four-tier release model:

- **Exploring / In design** — Conceptual work, feasibility studies; no timeline guaranteed.  
- **Preview** — Publicly available in full or limited capacity. Documentation and timelines published. No SLA.  
- **GA (Generally Available)** — Production-ready with SLAs and support. Typically 1–2 quarters after Preview.  
- **Delivered / Shipped** — Feature is released and the issue is closed with changelog links.

---

## Feature areas
Key product domains (labels used in issues):

- `planning` — Workflow and collaboration tools  
- `ai-productivity` — AI assistants, transcriptions, meeting automation (MeeTaker AI + portfolio)  
- `security-compliance` — Cloud security, identity, encryption, compliance workflows  
- `code-to-cloud` — DevOps & platform integrations  
- `ecosystem` — Partner APIs, connectors, and integrations  
- `insights` — Analytics, usage, and ROI measurement

---

## Product strategy & prioritization
We prioritize initiatives that:
1. Deliver measurable customer ROI and reduce time-to-value.  
2. Strengthen our partner ecosystem (Google Cloud, Microsoft, IBM, AWS).  
3. Reduce risk and cost of adoption (security & compliance).  
4. Unlock scalable enterprise revenue across our multinational footprint.

Decisions are driven by a weighted decision matrix capturing revenue potential, strategic fit, technical risk, and compliance overhead.

---

## Partner impact & GTM alignment
- Any roadmap item with partner dependencies must include a `partner-impact` section describing:
  - Partner(s) affected and API/contract dependencies  
  - GTM implications and joint enablement requirements  
  - Owner for partner liaison  
- Product and GTM must jointly sign off before Preview for partner-facing features.

---

## Compliance & security
- All features touching customer data must document compliance posture (GDPR, SOC2, and any regional requirements).  
- Security reviews (threat model, pen test plan) are required for Preview signoff. Tag issues with `security` and link the Security Policy.  
- See `SECURITY.md` and `PRIVACY.md` for process and reporting.

---

## Contribution & maintenance
- **How to propose a roadmap item:** Open an issue using the `roadmap-item` template with owner, scope, and success criteria.  
- **Labeling:** PMO will apply canonical labels; contributors should propose labels in the issue body.  
- **Review cadence:** Monthly triage for new requests; quarterly executive review for prioritization and resourcing.  
- **Issue lifecycle:** `exploring` → `in-design` → `preview` → `ga` → `shipped/closed`.

---

## Issue templates & PR guidance
- Use `roadmap-item` template for new roadmap proposals.  
- PRs that change roadmap text should include a one-paragraph executive summary and the implication for GTM and compliance.

---

## Security & reporting
Report security issues per `SECURITY.md`. For vulnerabilities exposing customer data, follow the incident response process and notify Legal & Security immediately.

---

## License
This repository is licensed under **CC-BY-4.0**. See `LICENSE` for details.

---

## Contact & governance
- Product Strategy: product@starlightretail.ltd  
- GTM & Partnerships: partners@starlightretail.ltd  
- Security & Privacy: security@starlightretail.ltd  
- Executive contact: mammon@starlightretail.ltd

---

## Change log & disclaimers
This public roadmap conveys direction and intent. Dates and plans are subject to change. For formal commitments and beyond-public details, contact Product Strategy.

