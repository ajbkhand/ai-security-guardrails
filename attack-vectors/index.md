---
layout: default
title: Attack vectors
---

# AI attack vectors

AI systems introduce **new classes of security risk** beyond traditional systems.

These risks must be understood and mitigated **at each stage of the lifecycle**.

## Key principle

> The risk is not what the AI says — it is what the AI can be made to do.

---

# Core attack vectors

All AI systems must consider the following threats:

- Data poisoning  
- Adversarial inputs  
- Prompt injection  
- Model misuse or repurposing  

Each occurs at different lifecycle stages.

---

# Lifecycle view of risk

| Stage | Primary risk |
|------|--------------|
| Incubate | Data poisoning |
| Pilot | Prompt injection and adversarial inputs |
| Scale | Model misuse and drift |

➡️ Go to Lifecycle  

---

# Attack vector overview

## Data poisoning

Malicious or incorrect data introduced during training can corrupt the model.

➡️ data-poisoning/

---

## Adversarial inputs

Carefully crafted inputs designed to cause model errors.

➡️ adversarial-inputs/

---

## Prompt injection (LLMs)

Malicious prompts override system instructions or expose data.

➡️ prompt-injection/

---

## Model misuse or repurposing

Models used outside their intended purpose.

➡️ model-misuse/

---

# What you must do

All projects must:

- Identify relevant attack vectors early  
- Apply controls during design (Incubate stage)  
- Test for attacks during Pilot (red-teaming)  
- Monitor for misuse in Scale  

➡️ See: Red teaming  
➡️ See: Lifecycle checklists  

---

# Summary

AI systems must be designed to:

- Prevent manipulation  
- Detect misuse  
- Remain robust under attack  

> Attack vectors must be treated as core design concerns, not afterthoughts.
``
