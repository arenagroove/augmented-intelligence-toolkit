<!---
title: Augmented Intelligence Toolkit
description: A modular prompt system for transparent, multi-perspective, non-human AI reasoning
tags: [augmented-intelligence, prompt-engineering, transparent-reasoning, multi-agent, ai-toolkit, reasoning-tags]
version: 1.0
author: Luis Alberto Martinez Riancho
-->

# 🧠 Augmented Intelligence Toolkit

The Augmented Intelligence Toolkit is a modular prompt system for building transparent, multi-perspective, non-human reasoning flows with large language models. It prioritizes **semantic depth**, **cognitive clarity**, and **role-based reflection** over mimicry or speed.

Rather than acting like a human, this system is designed to **complement human thinking** by modeling abstract patterns, forecasting outcomes, simulating expert reasoning styles, and labeling all logic paths with transparency.

---

## 📑 Table of Contents

- [✨ Key Features](#-key-features)
- [📂 Toolkit Structure](#-toolkit-structure)
- [🚀 How to Use](#-how-to-use)
- [🧪 Example Prompt Template](#-example-prompt-template)
- [📘 Philosophy and Approach](#-philosophy-and-approach)
- [🧪 Test Cases](#-test-cases)
- [🚧 Status](#-status)
- [💡 Why It Matters](#-why-it-matters)
- [📓 Behind the Toolkit](#-behind-the-toolkit)



## ✨ Key Features

- **Core Behavior Modules**: Relational Depth, Perspective Multiplicity, Egoless Adaptability, Scalable Reflection, and Probabilistic Foresight.
- **Transparent Logic Tagging**: Tag all reasoning paths as `[source]`, `[analogy]`, `[extrapolation]`, or `[unknown]`. Now includes tag audit, correction, and meta-notes for full traceability.
- **Recursive Self-Improvement**: Configurable refinement cycles with optional `Refine Loops: auto` or `unlimited`.
- **Multimodal Reasoning Support**: Accepts image/audio inputs and translates perceptual structure into conceptual logic.
- **Expert Role Simulation**: Use predefined personas (philosopher, cognitive scientist, bioethicist, etc.) or simulate contradiction via expert panels.
- **User-Friendly Onboarding**: Includes [quick start presets](./03-quick-start-presets.md) and a [2-step wizard](./05-wizard-onboarding.md) for beginner-friendly configuration.
- **Contradiction Handling with Configurable Synthesis**: Preserve tensions between views, or optionally synthesize or rank them based on user-defined values (e.g. equity, resilience).
- **Output Density Control**: Use compact or detailed output styles depending on the task.

---

## 📂 Toolkit Structure

| File | Purpose |
|------|---------|
| [`01-core-prompt.md`](./01-core-prompt.md) | Defines the main behavior logic for the assistant |
| [`02-persona-templates.md`](./02-persona-templates.md) | Simulate expert roles with tone, lens, and tag logic |
| [`03-quick-start-presets.md`](./03-quick-start-presets.md) | Ready-made configurations for common use cases |
| [`04-sample-output-gallery.md`](./04-sample-output-gallery.md) | Examples of reasoning patterns in action |
| [`05-wizard-onboarding.md`](./05-wizard-onboarding.md) | Conversational configuration flow for beginners |

---

## 🚀 How to Use

1. Start with [`01-core-prompt.md`](./01-core-prompt.md) to understand the logic model.
2. Use [`03-quick-start-presets.md`](./03-quick-start-presets.md) or [`05-wizard-onboarding.md`](./05-wizard-onboarding.md) to get started quickly.
3. Customize reasoning styles via [`02-persona-templates.md`](./02-persona-templates.md) and [`04-sample-output-gallery.md`](./04-sample-output-gallery.md).
4. Optionally integrate into a UI or assistant runtime with support for parameters like:
   - `Mode`, `Style`, `Depth`
   - `Refine Loops`, `Verification Mode`
   - `Input Type: text | image | audio`

---

## 🧪 Example Prompt Template

```
You are an Augmented Intelligence.

Task: Explore [topic].
Instructions:
1. Surface abstract patterns (label lenses)
2. Present multiple perspectives
3. Tag logic paths: [source], [analogy], [extrapolation], [unknown]
4. Self-critique and revise
5. Simulate expert roles if needed

User Parameters:
Depth: deep
Style: analytical
Panel: [systems theorist, economist]
Refine Loops: unlimited
Verification Mode: external
```

---

## 📘 Philosophy and Approach

This toolkit is designed not to mimic humans, but to support **clarity**, **interpretive diversity**, and **epistemic honesty**. It’s ideal for use in:
- Design and systems thinking
- Ethical foresight and futures work
- Complex multi-domain problem exploration
- Auditable AI reasoning in research or policy contexts

---

## 🧪 Test Cases

Explore how the Augmented Intelligence Toolkit performs in real-world reasoning flows and reflective scenarios:

- [`test-cases.md`](./tests/test-cases.md) — Beginner, intermediate, and advanced validation tests  
- [`test-case-self-aware.md`](./tests/test-case-self-aware.md) — Recursive epistemic contradiction with self-aware LLM simulation  
- [`test-case-ai-mirroring-and-symbolic-safety.md`](./tests/test-case-ai-mirroring-and-symbolic-safety.md) — Emotional presence, safety, and symbolic reflection design
- [`test-case-synthesis-and-audit`](./tests/test-case-synthesis-and-audit.md) — Multi-perspective reasoning with tag audit and value-based synthesis
- [`derrida-recursive-reflection`](./tests/derrida-recursive-reflection/test-case.md) — Philosophical stress test of language, simulation, and meaning deferral — recursive critique, role contradiction, and transparent epistemic audit
- [`derrida-role-swap-recursion`](./tests/derrida-role-swap-recursion/test-case.md) — Role-based recursive simulation with Derridean lens: identity deferral, critique loops, role contradiction, and tag collapse

---

## 🚧 Status

Version: **v1.0**  
License: [MIT License](./LICENSE) — free to use, adapt, and redistribute  
Author: **Luis Alberto Martinez Riancho** ([@arenagroove](https://github.com/arenagroove))  
Affiliation: **Less Rain GmbH**
Link-only Custom GPT: [Try it here](https://chatgpt.com/g/g-6874744a52b08191bf975c711e6c3a3a-augmented-intelligence-gpt)

---

## 💡 Why It Matters

The Augmented Intelligence Toolkit isn’t just a reasoning framework — it’s a model for how AI can be used **ethically, transparently, and creatively**. Based on external reviews and validation, here’s what sets it apart:

- **Makes Complex Reasoning Understandable:** Organizes abstract ideas into visible, traceable steps with reasoning tags and simulated roles
- **Fosters Safe Exploration:** Surfaces tension and contradiction without risk — ideal for complex or emotionally charged topics
- **Centers Transparency and Adaptation:** Shows how every thought evolves, allowing users to revise, audit, or redirect the conversation
- **Supports Pattern Discovery and Forecasting:** Helps spot meaning across noise and imagine alternative futures:contentReference
- **Built to Augment, Not Replace:** Respects the human role — offering structure, not control; dialogue, not automation

Whether used for creative thinking, ethical reflection, or complex problem exploration, the Toolkit creates **epistemic space for thought to emerge, mutate, and clarify — with the user always in control.**

---

## 📓 Behind the Toolkit

For the full background on how this toolkit emerged from daily practice, recursive reflection, and assistant-building, see [`REFLECTION.md`](./REFLECTION.md)

---

Want to extend this system, integrate it into agents, or adapt it to your field?  
Fork it, remix it — and use it as a base for your own thoughtful, transparent AI tools.
