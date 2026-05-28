---
layout: default
title: Lifecycle checklists
---

# Lifecycle checklists

These checklists define the **minimum required actions** at each stage of AI delivery in Defra.

They support:
- Governance assurance  
- Delivery planning  
- Security compliance  

## How to use this page

For each stage:

1. Complete all items before progressing  
2. Record evidence where required  
3. Align with Guardrail tiers (Tier 2 → Tier 1 → Tier 0)  

---

# ✅ Concept stage checklist

Focus: **Should we build this AI system?**

## You must:

- [ ] Define the user need and expected outcome  
- [ ] Identify potential harms and risks  
- [ ] Confirm whether AI is the right solution  
- [ ] Identify if decisions affect people or public outcomes  
- [ ] Determine if personal or sensitive data is used  
- [ ] Trigger DPIA if required  
- [ ] Register the project in the AI inventory  
- [ ] Select the simplest viable model (prefer SLM over LLM)  

## Evidence required

- Problem statement  
- Initial risk assessment  
- DPIA trigger decision  
- Model selection rationale  

## STOP conditions

Do not proceed if:

- Use case is unclear  
- Risks are not understood  
- AI is not necessary  

---

# ✅ Incubate stage checklist

Focus: **Design a secure and workable solution**

## You must:

### Data and model

- [ ] Validate data quality and provenance  
- [ ] Ensure datasets are versioned and traceable  
- [ ] Check for bias, imbalance, or poor labelling  
- [ ] Define model purpose and limitations  

### Security design

- [ ] Apply least privilege access controls  
- [ ] Implement encryption (at rest and in transit)  
- [ ] Enable logging and audit capability  
- [ ] Perform supply chain checks  

### Architecture

- [ ] Apply zero-trust principles  
- [ ] Define identity model (user vs service)  
- [ ] Document data flows and regions  
- [ ] Confirm legal/DPO position on data movement  

## Evidence required

- Data quality assessment  
- Security architecture design  
- Data flow and residency documentation  
- Initial threat model  

## Key risks

- Data poisoning  
- Poor data quality leading to biased outcomes  

---

# ✅ Pilot stage checklist

Focus: **Validate the system safely before release**

## You must:

### Governance and compliance

- [ ] Complete DPIA  
- [ ] Implement human-in-the-loop controls  
- [ ] Define escalation and override processes  

### Transparency

- [ ] Provide user disclosures (AI usage, limitations)  
- [ ] Provide human fallback option  
- [ ] Publish ATRS (if public or decision-influencing)  

### Testing

- [ ] Conduct red-teaming  
- [ ] Test for prompt injection  
- [ ] Test for bias and fairness  
- [ ] Validate robustness under misuse scenarios  

### Operational readiness

- [ ] Define runbooks and SLAs  
- [ ] Define monitoring and alert thresholds  
- [ ] Prepare incident response plan  

## Evidence required

- Completed DPIA  
- ATRS (if applicable)  
- Test results (security, bias, robustness)  
- Operational readiness documentation  

## STOP conditions

Do not go live if:

- Testing is incomplete  
- Risks are not mitigated  
- Human controls are not in place  

---

# ✅ Scale stage checklist

Focus: **Operate safely at scale**

## You must:

### Monitoring and performance

- [ ] Monitor model accuracy and drift  
- [ ] Track bias and fairness over time  
- [ ] Monitor system usage and anomalies  

### Security and operations

- [ ] Maintain logging and audit trails  
- [ ] Operate incident response processes  
- [ ] Rotate credentials and keys regularly  
- [ ] Maintain backup and recovery capability  

### Governance

- [ ] Update ATRS and disclosures regularly  
- [ ] Maintain model documentation (model cards)  
- [ ] Apply change control for retraining and updates  

### Continuous assurance

- [ ] Re-run red-teaming periodically  
- [ ] Revalidate bias and fairness  
- [ ] Review system purpose and usage  

## Evidence required

- Monitoring dashboards  
- Incident logs and response records  
- Updated ATRS and documentation  
- Change control records  

## Key risks

- Model drift  
- Misuse or repurposing  
- Undetected bias over time  

---

# 🔁 Lifecycle principles

## 1. Controls increase over time

| Stage | Focus | Control level |
|------|------|--------------|
| Concept | Define and assess | Low |
| Incubate | Design securely | Medium |
| Pilot | Validate and test | High |
| Scale | Monitor and govern | Continuous |

---

## 2. Evidence is mandatory

All stages must produce:
- Documentation  
- Logs  
- Decisions  

## 3. Human oversight is required throughout

Human control must exist at:
- Design  
- Testing  
- Operation  

---

# ✅ Summary

All AI projects must:

- Start with clear outcomes and risk understanding  
- Be designed securely and transparently  
- Be tested rigorously before release  
- Be monitored and governed continuously  

> AI systems must remain observable, controllable, and accountable throughout their lifecycle.
