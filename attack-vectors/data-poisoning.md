---
layout: default
title: Data poisoning
---

# Data poisoning

## What it is

Malicious or incorrect data introduced into training datasets.

This can:

- Corrupt model behaviour  
- Introduce bias  
- Reduce system reliability  

## Defra example

A dataset used for environmental modelling is seeded with incorrect values, leading to wrong predictions about risk or safety.

## When it occurs

Primarily at:

- Incubate stage (data ingestion and training)

---

## Required controls

You must:

- Validate data provenance (know where data comes from)  
- Restrict write access to datasets  
- Version datasets and maintain lineage  
- Detect anomalies and outliers  
- Perform label quality checks  

---

## What good looks like

- All datasets are traceable  
- Data sources are trusted  
- Model behaviour reflects real-world conditions  
