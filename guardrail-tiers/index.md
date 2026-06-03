---
layout: default
title: Apply guardrail tiers
---

# Apply guardrail tiers

Use this page to apply the **correct level of security controls** to your AI system.

All AI systems must apply **minimum controls**, then add more controls based on risk.

---

# Identify the required tier

You must decide which tiers apply to your system.

---

## Always apply Tier 2 (minimum controls)

✅ This applies to **all AI systems**

You must:

- Protect data integrity and provenance  
- Apply least privilege access  
- Encrypt data at rest and in transit  
- Log all activity  
- Monitor and alert on issues  
- Prepare incident response  

➡️ All systems start here  

---

## Add Tier 1 if the system is public or externally used

Apply Tier 1 if:

- External users interact with the system  
- The system is publicly accessible  
- The system provides advice or outputs to users  

---

### You must:

- ✅ Provide clear user disclosures  
- ✅ Enable human fallback or escalation  
- ✅ Perform robustness testing  
- ✅ Conduct AI red-teaming  

---

⚠️ Do not publish a system externally without these controls

---

## Add Tier 0 if the system affects decisions or outcomes

Apply Tier 0 if:

- The system influences decisions about people  
- The system affects public outcomes  
- The system operates in a high-risk context  

---

### You must:

- ✅ Complete a high-risk DPIA  
- ✅ Publish and maintain an ATRS  
- ✅ Test for bias and fairness  
- ✅ Improve explainability  
- ✅ Apply stronger governance and assurance  

---

⚠️ Do not use AI for decisions without these controls

---

# Understand how tiers work

Tiers are **additive**.

You must apply all relevant tiers.

---

## Example

| Scenario | Required tiers |
|---------|---------------|
| Internal tool | Tier 2 |
| Public chatbot | Tier 2 + Tier 1 |
| Decision-support system | Tier 2 + Tier 1 + Tier 0 |

---

# Apply tiers across the lifecycle

You must apply controls at every stage:

- Concept → identify risk level  
- Incubate → design controls  
- Pilot → test controls  
- Scale → monitor and maintain controls  

➡️ {{ '/lifecycle/' | relative_url }}Follow the lifecycle  

---

# Do

- ✅ Start with Tier 2 for all systems  
- ✅ Add Tier 1 for external use  
- ✅ Add Tier 0 for decision impact  
- ✅ Apply controls early in design  

---

# Do not

- ❌ Treat all systems the same  
- ❌ Skip controls for “low-risk” systems  
- ❌ Deploy externally without testing  
- ❌ Use AI in decisions without assurance  

---

# What good looks like

An AI system in Defra:

- Applies controls proportionate to risk  
- Is tested before release  
- Is transparent to users  
- Is monitored continuously  

---

# Summary

You must:

1. Apply Tier 2 controls to all systems  
2. Add Tier 1 if the system is external  
3. Add Tier 0 if the system affects decisions  
4. Apply controls across the lifecycle  

> Higher risk requires stronger controls.

