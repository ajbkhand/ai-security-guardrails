---
layout: default
title: Understand AI risks
---

# Understand AI risks

Use this page to identify and manage the **key security risks in AI systems**.

AI systems can be manipulated in ways that traditional systems cannot.

---

## What you must do

You must:

- ✅ Identify relevant attack vectors early  
- ✅ Design controls during Incubate  
- ✅ Test systems before release  
- ✅ Monitor for misuse in production  

➡️ {{ '/checklists/lifecycle-checklists/' | relative_url }}Follow the lifecycle  

---

# Identify the main risks

All AI systems must consider these attack vectors:

- Data poisoning  
- Adversarial inputs  
- Prompt injection  
- Model misuse  

---

# Understand when risks occur

Different risks appear at different stages:

| Stage | Key risk |
|------|---------|
| Incubate | Data poisoning |
| Pilot | Prompt injection and adversarial inputs |
| Scale | Model misuse and drift |

➡️ {{ '/lifecycle/' | relative_url }}Follow the lifecycle  

---

# Data poisoning

Malicious or incorrect data is introduced into training datasets.

This can:

- Corrupt model behaviour  
- Introduce bias  
- Reduce reliability  

---

## You must

- ✅ Validate data sources and provenance  
- ✅ Restrict write access to datasets  
- ✅ Version datasets and maintain lineage  
- ✅ Detect anomalies and outliers  
- ✅ Verify labels and annotations  

---

⚠️ Do not train models on untrusted or unverified data  

---

# Adversarial inputs

Inputs are designed to cause incorrect outputs.

This is common in:

- Computer vision  
- NLP and classification systems  

---

## You must

- ✅ Perform adversarial testing  
- ✅ Validate and sanitise inputs  
- ✅ Add human review for high-risk outputs  
- ✅ Test edge cases and variations  

---

⚠️ Do not assume models behave correctly under all inputs  

---

# Prompt injection (LLMs)

Malicious prompts are used to override system instructions.

This is a critical risk for LLM-based systems.

---

## You must

- ✅ Protect system prompts  
- ✅ Apply input sanitisation  
- ✅ Use content safety filters  
- ✅ Monitor prompt behaviour  
- ✅ Restrict access to sensitive data  

---

⚠️ Do not expose sensitive data to untrusted inputs  

---

# Model misuse or repurposing

Models are used outside their intended purpose.

This can lead to:

- Incorrect decisions  
- Ethical or compliance risks  
- Loss of trust  

---

## You must

- ✅ Define intended use clearly (model cards)  
- ✅ Restrict access using RBAC  
- ✅ Monitor usage patterns  
- ✅ Detect unusual or unauthorised use  

---

⚠️ Do not allow models to be used beyond approved scope  

---

# Apply controls across the lifecycle

You must:

- Identify risks at Concept  
- Design controls at Incubate  
- Test at Pilot  
- Monitor at Scale  

---

# Do

- ✅ Treat attack vectors as core design requirements  
- ✅ Test systems under adversarial conditions  
- ✅ Monitor continuously after deployment  

---

# Do not

- ❌ Assume AI systems are safe by default  
- ❌ Skip adversarial testing  
- ❌ Ignore misuse or drift  

---

# What good looks like

An AI system in Defra:

- Is robust against manipulation  
- Detects misuse early  
- Protects sensitive data  
- Maintains performance under attack  

---

# Summary

You must:

1. Identify attack vectors early  
2. Apply controls during design  
3. Test before release  
4. Monitor and respond in production  

> AI systems must be resilient to manipulation and misuse.
``
