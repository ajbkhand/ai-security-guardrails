---
layout: default
title: Choose a platform
---

# Choose a platform

Use this page to understand **how your delivery platform affects implementation**.

Platforms provide some controls by default, but **you are still responsible for securing your AI system**.

---

## What you must do

You must:

- ✅ Choose an approved delivery platform  
- ✅ Understand what the platform provides  
- ✅ Implement additional AI-specific controls  
- ✅ Apply guardrails regardless of platform  

➡️ {{ '/guardrail-tiers/' | relative_url }}Apply guardrail tiers  

---

# Understand the key rule

> The platform changes how controls are implemented — not whether they apply.

All AI systems must meet the same security requirements.

---

# Choose your platform

You must use one of the following:

- DASH (Databricks)  
- CDP (Core Delivery Platform)  
- CCoE (cloud platforms)  
- Supplier-hosted infrastructure  
- Other approved environments (for example HPC or geospatial platforms)  

---

# Understand what the platform provides

Platforms typically provide:

- Identity and access management  
- Networking and environment isolation  
- Encryption and key management  
- Logging and monitoring  
- Baseline governance controls  

✅ These are inherited controls  

## Platform responsibilities

Use this diagram to understand what the platform provides and what you must implement.

{{ "/images/platform-offerings.png" | relative_url }}

*Figure: Platform-provided controls vs team responsibilities*

---

# Understand what you must still do

You must implement AI-specific controls yourself.

---

## Data and model controls

You must:

- ✅ Validate data quality and provenance  
- ✅ Check datasets for bias and imbalance  
- ✅ Maintain data and model lineage  
- ✅ Define model purpose and limitations  

---

## Security controls

You must:

- ✅ Apply least privilege access  
- ✅ Protect sensitive data  
- ✅ Secure APIs and integrations  
- ✅ Monitor system behaviour  

---

## AI risk controls

You must:

- ✅ Test for prompt injection  
- ✅ Test for adversarial inputs  
- ✅ Prevent model misuse  
- ✅ Apply content safety controls  

➡️ {{ '/attack-vectors/' | relative_url }}Understand AI risks  

---

## Governance and transparency

You must:

- ✅ Complete a DPIA where required  
- ✅ Publish an ATRS (if applicable)  
- ✅ Provide user disclosures  
- ✅ Maintain audit logs  

---

# Apply additional controls based on risk

You must:

- Apply Tier 2 controls for all systems  
- Add Tier 1 for external systems  
- Add Tier 0 for decision-impact systems  

➡️ {{ '/guardrail-tiers/' | relative_url }}Apply guardrail tiers  

---

# Example

## Scenario: AI model on DASH

The platform provides:

- Identity management  
- Logging and monitoring  

You must still:

- ✅ Validate training data  
- ✅ Test for bias and robustness  
- ✅ Document model behaviour  
- ✅ Perform red-teaming (if required)  

---

# Do

- ✅ Use approved platforms  
- ✅ Understand inherited controls  
- ✅ Implement missing controls  
- ✅ Apply guardrails consistently  

---

# Do not

- ❌ Assume the platform makes your system secure  
- ❌ Rely only on default controls  
- ❌ Skip AI-specific risk controls  
- ❌ Treat different platforms as different standards  

---

# What good looks like

An AI system in Defra:

- Uses a secure, approved platform  
- Applies both inherited and additional controls  
- Is consistent with all guardrails  
- Is secure regardless of platform choice  

---

# Summary

You must:

1. Choose an approved platform  
2. Understand what controls are provided  
3. Implement additional AI-specific controls  
4. Apply guardrails consistently  

> Your team is responsible for the security of the AI system — not the platform alone.
