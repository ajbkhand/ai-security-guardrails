---
layout: default
title: Start here
---

# Start here

Use this page to determine:

- Whether you should build an AI system  
- What type of system to build  
- What security controls are required  

This should take **less than 5 minutes**.

---

# Step 1 — Is AI the right solution?

## Ask:

- Is the problem complex or unpredictable?  
- Does it require interpretation, reasoning, or pattern recognition?  

## If NO

➡️ Use:
- Deterministic workflows  
- Traditional automation  
- Search or reporting tools  

✅ Stop here — do not build AI

---

## If YES

➡️ Continue to Step 2

---

# Step 2 — Will this AI be used externally?

## Ask:

- Will anyone outside Defra or its ALBs interact with this system?  

Examples:
- Public chatbot  
- External API  
- Advisory tool  

---

## If YES

✅ You must apply:

- **Tier 1 guardrails**  
- User transparency and disclosures  
- Human fallback  
- Red-teaming and robustness testing  

➡️ Continue to Step 3

---

## If NO

➡️ Continue to Step 3

---

# Step 3 — Does it influence decisions?

## Ask:

- Does this system affect decisions about people, funding, or public outcomes?

Examples:
- Risk scoring  
- Eligibility decisions  
- Policy interpretation  

---

## If YES

✅ You must apply:

- **Tier 1 + Tier 0 guardrails**  
- DPIA (high risk)  
- ATRS (mandatory)  
- Bias and fairness testing  

➡️ Continue to Step 4

---

## If NO

➡️ Continue to Step 4

---

# Step 4 — Choose delivery route

Select your platform:

- DASH (Databricks)  
- CDP (Core Delivery Platform)  
- CCoE (cloud platform)  
- Supplier-hosted  

✅ This determines **how controls are implemented**, not whether they apply

---

# Step 5 — Identify your lifecycle stage

Choose your current stage:

- Concept → defining the problem  
- Incubate → building and validating  
- Pilot → testing before release  
- Scale → operating in production  

➡️ Go to:

- Lifecycle  

---

# Step 6 — Apply required guardrails

All systems must:

- Apply **Tier 2 (minimum controls)**  
- Add Tier 1 or Tier 0 where required  

➡️ Go to:

- Guardrail tiers  

---

# Step 7 — Follow your role checklist

Different roles must complete different tasks.

➡️ Go to:

- Personas  

---

# Summary (decision rules)

## Do not proceed if:

- The use case is unclear  
- AI is not necessary  
- Risks are not understood  

---

## Minimum requirements for all AI

- Defined use case and outcome  
- Security controls applied (Tier 2)  
- Data handled appropriately  
- System is auditable and monitored  

---

## Additional requirements (if applicable)

| Condition | Required controls |
|----------|------------------|
| External users | Tier 1 (transparency + testing) |
| Decision impact | Tier 0 (fairness + governance) |
| High-risk data | Enhanced controls |

---

# What to do next

Once you have completed this:

1. Move to Lifecycle guidance  
2. Apply Guardrail tiers  
3. Complete your role checklist  

---

# Key principle

> Start simple, scale safely, and apply controls proportionate to risk.
>
> ## Decision flow

```mermaid
flowchart TD

A[Start: Define your problem] --> B{Is AI needed?}

B -->|No| C[Use non-AI solution<br/>Stop]
B -->|Yes| D{External users?}

D -->|Yes| E[Apply Tier 1 controls<br/>Transparency + Red-teaming]
D -->|No| F{Influences decisions?}

F -->|Yes| G[Apply Tier 0 controls<br/>ATRS + DPIA + Fairness testing]
F -->|No| H[Apply Tier 2 minimum controls]

E --> I[Choose delivery platform]
G --> I
H --> I

I --> J[Identify lifecycle stage<br/>Concept → Incubate → Pilot → Scale]

J --> K[Apply lifecycle checklist]

K --> L[Implement controls + Test]

L --> M{Ready for release?}

M -->|No| K
M -->|Yes| N[Deploy and monitor]

N --> O[Continuous monitoring<br/>Drift, misuse, incidents]

``
