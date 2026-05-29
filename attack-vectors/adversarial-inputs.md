---
layout: default
title: Adversarial inputs
---

# Adversarial inputs

## What it is

Inputs deliberately designed to cause incorrect model outputs.

This is common in:

- Computer vision  
- NLP systems  
- Classification models  

## Defra example

Small changes to satellite imagery cause a vegetation model to misclassify land use.

## When it occurs

Primarily at:

- Pilot stage  
- Scale stage  

---

## Required controls

You must:

- Conduct adversarial testing  
- Apply input validation and sanitisation  
- Add human review for high-risk decisions  
- Test model robustness under variation  

---

## What good looks like

- Model performance is stable under variation  
- Edge cases are understood and tested  
