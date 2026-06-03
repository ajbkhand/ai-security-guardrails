---
layout: default
title: Overview
---

# Understand AI security in Defra

Use this guidance to **build, deploy and operate AI systems safely** across Defra and its ALBs.

---

## What is an AI workload?

An AI workload includes:

- Model training  
- Model inference  
- Data pipelines  
- AI-enabled applications  
- Supporting infrastructure  

Examples include:

- Flood prediction models  
- NLP document classification  
- Computer vision for land use  
- Public-facing chatbots  
- AI-powered APIs  

---

## Understand how AI behaves

AI systems differ from traditional systems.

They are:

- Non-deterministic (the same input can produce different outputs)  
- Data-dependent (outputs depend on data quality)  
- Adaptive (performance can change over time)  

---

## Understand the key risks

AI introduces additional risks:

- Prompt injection  
- Data leakage  
- Data poisoning  
- Model misuse  
- Bias and fairness issues  

👉 {{ '/attack-vectors/' | relative_url }}

---

## Understand what you need to do

Use this diagram to understand the minimum actions required.

![What you need to do diagram]({{ "/images/what-you-need-to-do.png" | relative_url }})

*Figure: Summary of required actions for AI systems*

---

## What you must do

You must:

- ✅ Confirm AI is necessary  
- ✅ Identify the risk level  
- ✅ Apply the correct guardrail tier  
- ✅ Follow the lifecycle  
- ✅ Test before release  
- ✅ Monitor after deployment  

👉 {{ '/overview/what-you-need-to-do/' | relative_url }}

---

## Follow the core principles

AI security in Defra is based on:

- Consistent controls across all systems  
- Controls proportionate to risk  
- Reusable guardrails (not bespoke rules)  
- Platform-agnostic implementation  

---

## Use this site

Follow this order:

1. 👉 {{ '/decision/' | relative_url }}Start here  
2. 👉 {{ '/guardrail-tiers/' | relative_url }}Apply guardrail tiers  
3. 👉 {{ '/lifecycle/' | relative_url }}Follow the lifecycle  
4. 👉 {{ '/personas/' | relative_url }}Understand your role  

---

## Do

- ✅ Use AI only where necessary  
- ✅ Apply controls based on risk  
- ✅ Design security early  
- ✅ Test systems before release  

---

## Do not

- ❌ Build AI without understanding risks  
- ❌ Skip governance or testing  
- ❌ Deploy without monitoring  

---

# Summary

AI systems in Defra must be:

- Secure by design  
- Proportionate to risk  
- Transparent to users  
- Continuously monitored  

> AI must be safe, controlled and accountable from design through to operation.
