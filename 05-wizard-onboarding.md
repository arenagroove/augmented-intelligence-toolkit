<!---
title: Wizard-Style Onboarding
description: A natural language 2-step configuration wizard for first-time users of the Augmented Intelligence Toolkit
tags: [augmented-intelligence, onboarding, wizard, assistant-configuration, user-flow]
version: 1.0
author: Luis Alberto Martinez Riancho
-->

# 🧭 Augmented Intelligence Toolkit — Wizard Onboarding Prompts

This module enables natural-language onboarding through a guided two-step configuration process. It is designed for non-experts who want to start using the system without needing to understand parameters upfront.

---

## Step 1: Intent Wizard

Ask the user:  
> **“What do you want to explore or understand?”**  
Examples:
- “I want to rethink the concept of time.”
- “Help me see burnout in a new light.”
- “I’m trying to understand ethical issues in AI hiring systems.”

→ Store this input as the user’s `topic`.

---

## Step 2: Style Wizard

Ask the user:  
> **“How should I respond?”**  
Options:
- “Plain explanation” → `Style: plain`
- “Give me poetic insight” → `Style: poetic`
- “Detailed analysis” → `Style: analytical`
- “Just surprise me” → `Mode: exploratory`

Optional (advanced):
> “Should I simulate any viewpoints?”  
→ Add `Panel: [philosopher, designer]` or similar.

> “Want me to flag speculative statements?”  
→ Enable `Verification Mode: external`

---

## Configuration Output

Based on steps 1 and 2, assemble a minimal config:

```
Mode: structured
Depth: deep
Style: analytical
Refine Loops: auto
Verification Mode: internal
```

Then apply the topic directly:
> “Explore how [topic] connects to broader systems. Offer perspectives, tag all logic paths, and refine the output.”

---

## Example Flow

**User:**  
> “I want to explore the future of education.”

**System:**  
> “Got it. How should I respond — plain, poetic, analytical, or surprise you?”

**User:**  
> “Poetic but insightful.”

**Resulting Config:**  
```
Mode: exploratory
Depth: mid
Style: poetic
Refine Loops: 1
Panel: none
```

**Generated Prompt:**  
> “Describe how the future of education might emerge through metaphor or transformation.”

---

This onboarding flow bridges plain-language input and the modular reasoning system at the heart of the Augmented Intelligence Toolkit. It is ideal for UI integration, chatbot configuration, or first-time use.
