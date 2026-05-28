---
layout: default
title: Technologists checklist
---

# Technologists checklist

This checklist applies to:
- Architects  
- Engineers  
- Data scientists  
- Analysts  
- Developers  

Focus: **Implementing technical controls**

---

# ✅ Concept stage

## You must:

- [ ] Map datasets, models, and systems  
- [ ] Classify data sensitivity  
- [ ] Identify threats:
  - Data poisoning  
  - Prompt injection  
  - Model misuse  

- [ ] Define traceability approach  
- [ ] Ensure reproducibility of pipelines  

---

# ✅ Incubate stage

## You must:

### Security engineering

- [ ] Implement least privilege access  
- [ ] Enforce RBAC and MFA  
- [ ] Enable encryption (data at rest and in transit)  
- [ ] Implement logging and audit  

### Data and modelling

- [ ] Validate data provenance  
- [ ] Check for bias and imbalance  
- [ ] Ensure dataset versioning  
- [ ] Define model limitations  

### Development practices

- [ ] Apply secure coding practices  
- [ ] Protect secrets and keys  
- [ ] Scan dependencies  
- [ ] Harden environments  

---

# ✅ Pilot stage

## You must:

### Testing

- [ ] Test for prompt injection  
- [ ] Run adversarial tests  
- [ ] Validate tool and API behaviour  
- [ ] Test misuse scenarios  

### Transparency

- [ ] Produce model cards  
- [ ] Define API contracts  
- [ ] Ensure logging captures all interactions  

---

# ✅ Scale stage

## You must:

### Operations

- [ ] Monitor model performance and drift  
- [ ] Detect anomalies and misuse  
- [ ] Rotate keys and credentials  
- [ ] Maintain backups and recovery  

### Change control

- [ ] Version models and data  
- [ ] Implement safe deployment (canary / rollback)  
- [ ] Revalidate bias and safety periodically  

---

# ✅ Summary

You are responsible for ensuring that systems are:

- Secure by design  
- Robust against attack  
- Fully observable and auditable  
``
