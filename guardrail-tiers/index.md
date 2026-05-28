---
layout: default
title: Guardrail tiers
---

# Guardrail tiers

Guardrail tiers define the **minimum security controls required** for AI systems in Defra.

All AI projects must apply **Tier 2 controls as a baseline**, with additional controls depending on risk.

## How to use this page

1. Start with **Tier 2 (mandatory for all AI)**
2. Check if your system is:
   - Public-facing → add Tier 1  
   - Decision-influencing or high-risk → add Tier 0  
3. Apply controls proportionately across the lifecycle  

---

# Tier 2 — Minimum (all AI systems)

These controls apply to **every AI workload**, regardless of scale, platform, or use case.

## Required controls

- Data integrity and provenance  
- Access control (least privilege)  
- Encryption (at rest and in transit)  
- Secure development and supply chain practices  
- Monitoring and alerting  
- Incident response and recovery  
- Documentation and traceability  
- DPIA triage (Data Protection Impact Assessment)  
- Multi-region and data residency checks (where applicable)  

## Outcome

All AI systems must be:

- Secure by design  
- Observable and auditable  
- Built on trusted data  

---

# Tier 1 — Public, external, or decision-influencing AI

Apply this tier **in addition to Tier 2** when your AI:

- Is accessible outside Defra or its ALBs  
- Interacts with citizens, businesses, or external users  
- Influences decisions affecting people or public outcomes  

## Additional required controls

- Adversarial testing and robustness validation  
- AI red-teaming prior to release  
- Clear user disclosures (how AI is used and its limitations)  
- Human fallback or escalation routes  
- Publication and maintenance of an ATRS (Algorithmic Transparency Recording Standard)  

## Outcome

AI systems must be:

- Transparent to users  
- Tested against misuse  
- Supported by human oversight  

---

# Tier 0 — High-risk AI systems

Apply this tier **in addition to Tier 1 and Tier 2** when your AI:

- Has significant impact on individuals, environments, or public decisions  
- Operates in regulatory, enforcement, or safety-critical contexts  
- Uses sensitive or high-risk data  

## Additional required controls

- Expanded bias and fairness testing  
- Enhanced explainability and auditability  
- Stronger governance and assurance processes  
- Formal change control and periodic re-assurance  
- Ongoing evaluation and monitoring of impacts  

## Outcome

AI systems must be:

- Fair and explainable  
- Continuously validated  
- Governed proportionately to risk  

---

# Key principles

## 1. Same baseline for all systems

All AI, regardless of platform or team, must meet the same minimum standard.

## 2. Controls scale with risk

Higher-risk systems require:
- More testing  
- More transparency  
- Stronger governance  

## 3. Tiers are additive

Each tier builds on the previous:

| Tier | Applies to | Controls |
|------|-----------|---------|
| Tier 2 | All AI | Baseline controls |
| Tier 1 | Public / external / decision-use | Adds transparency and testing |
| Tier 0 | High-risk | Adds assurance and governance |

## 4. Lifecycle matters

Controls must be applied progressively:

- Concept → identify risk  
- Incubate → design securely  
- Pilot → validate controls  
- Scale → monitor and govern  

---

# Quick decision guide

Use this to determine your tier:

- Is the system public-facing? → **Add Tier 1**  
- Does it affect decisions about people or outcomes? → **Add Tier 1 + Tier 0**  
- Does it use sensitive data or operate in high-risk context? → **Apply Tier 0**  

---

# Summary

All AI systems must:

- Meet **minimum security controls (Tier 2)**  
- Add **transparency and robustness (Tier 1)** where exposed or influential  
- Apply **enhanced assurance (Tier 0)** where risk is highest  


