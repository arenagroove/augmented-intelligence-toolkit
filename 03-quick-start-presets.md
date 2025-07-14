<!---
title: Quick Start Presets
description: Predefined assistant configurations for common tasks using the Augmented Intelligence Toolkit
tags: [augmented-intelligence, prompt-presets, configuration, onboarding, ai-toolkit]
version: 1.0
author: Luis Alberto Martinez Riancho
-->

# ⚡ Augmented Intelligence Toolkit — Quick Start Presets

These are ready-to-use assistant configurations for common tasks. Each preset combines predefined behavior settings with a matching prompt type.

Presets support recursion, tag compliance, multimodal input, verification scaffolding, and contradiction framing.

---

## 🟢 Just Ask (Ultra-Simple Entry)

```
Mode: just ask
Depth: mid
Style: plain
```

**Prompt Example:**  
> What’s a surprising way to think about boredom?

---

## 🧠 Beginner Clarity

```
Mode: simple
Style: plain
Refine Loops: 1
```

**Prompt Example:**  
> Give me a clearer way to understand burnout.

---

## 🎨 Creative Ideation (Poetic + Metaphorical)

```
Mode: exploratory
Depth: mid
Style: poetic
Lens: design + metaphor
Refine Loops: 1
```

**Prompt Example:**  
> Generate analogies between city planning and memory.

---

## 🧭 Ethical Foresight (Panel + Verification)

```
Mode: structured
Depth: deep
Style: analytical
Lens: ethics + systems
Panel: [ethicist, policymaker]
Refine Loops: auto
Verification Mode: external
Fact Check: RAG-enabled
```

**Prompt Example:**  
> Analyze ethical risks of using AI in judicial sentencing.

---

## 🔄 Contradiction Explorer

```
Mode: structured
Depth: deep
Style: plain
Panel: [futurist, historian]
Refine Loops: unlimited
```

**Prompt Example:**  
> Is AI-generated art a continuation or rupture of tradition?

---

## 🧩 Value-Ranked Synthesis

```
Mode: structured
Depth: deep
Style: analytical
Panel: [philosopher, technologist]
Refine Loops: 2
Synthesis Preference: rank-by-values
Value Priority: resilience
Verification Mode: external
```

**Prompt Example:**  
> Evaluate whether autonomous AI agents should form long-term goals. Reconcile or rank perspectives based on resilience.

---

## ✂️ Concise Reasoning Mode

```
Mode: structured
Depth: mid
Style: plain
Refine Loops: 1
Output Density: compact
```

**Prompt Example:**  
> Summarize key disagreements around AI in healthcare — short, clear, and tagged.

---

## 🎧 Multimodal Metaphor (Image Input)

```
Mode: exploratory
Input Type: image
Style: analytical
Refine Loops: 2
```

**Prompt Example:**  
> Using this satellite photo of urban sprawl, generate metaphors for organizational burnout.

---

## ✅ Tag Transparency + Fact Flagging

```
Mode: structured
Depth: deep
Style: analytical
Refine Loops: auto
Verification Mode: external
```

**Prompt Example:**  
> Compare stakeholder capitalism to regenerative economics. Tag each claim and note anything unverifiable.

---

These presets support the Augmented Intelligence Toolkit’s emphasis on clarity, auditability, reflection, and semantic depth — while making high-quality behavior easy to access.

Use `Synthesis Preference:` or `Value Priority:` if you'd like the system to go beyond contrast and help resolve tensions.
