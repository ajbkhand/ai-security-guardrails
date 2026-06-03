---
layout: default
title: Start here
---

# Start here

Use this page to:

- Decide if you should use AI  
- Identify the required controls  
- Choose what to do next  

This should take **less than 5 minutes**.

---

## Decide if you should use AI

Ask:

- Is the problem complex or unpredictable?  
- Does it require judgement or pattern recognition?  

### If no

➡️ Use a non-AI solution  
✅ Stop here  

---

### If yes

➡️ Continue  

---

## Check if the system is public-facing

Ask:

- Will external users interact with this system?  

### If yes

✅ You must:

- Apply **Tier 1 controls**  
- Provide clear user disclosures  
- Enable human fallback  
- Perform red-teaming  

➡️ Continue  

---

### If no

➡️ Continue  

---

## Check if the system affects decisions

Ask:

- Does this system influence decisions about people or public outcomes?  

### If yes

✅ You must:

- Apply **Tier 0 controls**  
- Complete a DPIA (high risk)  
- Publish an ATRS  
- Test for bias and fairness  

➡️ Continue  

---

### If no

✅ Apply Tier 2 minimum controls  

➡️ Continue  

---

## Choose how you will build it

Select your delivery route:

- DASH  
- CDP  
- CCoE  
- Supplier  

✅ This affects implementation, not requirements  

---

## Follow the lifecycle

You must:

- Define risks (Concept)  
- Design securely (Incubate)  
- Test before release (Pilot)  
- Monitor in production (Scale)  

👉 {{ '/lifecycle/' | relative_url }}Follow the lifecycle

---

## Apply required controls

All systems must:

- Apply Tier 2 controls  
- Add Tier 1 or Tier 0 where required  

👉 {{ '/guardrail-tiers/' | relative_url }}Apply guardrail tiers

---

## Complete your role checklist

You must follow the checklist for your role:

👉 {{ '/personas/' | relative_url }}Go to personas

---

## Do

- ✅ Start with a clear problem  
- ✅ Apply controls based on risk  
- ✅ Test before release  

## Do not

- ❌ Proceed without understanding risks  
- ❌ Skip governance or testing  
- ❌ Deploy without monitoring  

---

## Summary

You must:

1. Decide if AI is appropriate  
2. Identify the risk level  
3. Apply the correct controls  
4. Test before release  
5. Monitor continuously  

> Do not proceed unless risks are understood and controlled.
