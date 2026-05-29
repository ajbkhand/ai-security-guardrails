---
layout: default
title: Prompt injection
---

# Prompt injection

## What it is

A user attempts to manipulate the input prompt to override system instructions.

This is a key risk for LLM-based systems.

## Risks

- Exposure of sensitive information  
- Execution of unsafe actions  
- Loss of control over system behaviour  

## Defra example

A public chatbot is tricked into revealing confidential internal information.

## When it occurs

Primarily at:

- Pilot stage  
- Scale stage  

---

## Required controls

You must:

- Protect system prompts (cannot be overwritten)  
- Apply input sanitisation  
- Use content safety filters  
- Monitor for suspicious prompt patterns  
- Limit access to sensitive data  

---

## What good looks like

- System instructions cannot be bypassed  
- Sensitive data is not exposed  
- Malicious prompts are detected and blocked  
``
