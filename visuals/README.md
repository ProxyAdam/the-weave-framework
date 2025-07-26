# 🧭 Visual System Map (Weave Framework)

This folder contains visual representations of the **Weave Framework’s core modules** and their interconnections.

---

## 📌 Map Overview

The primary file, `weave_visual_map.dot` (rendered as `weave_visual_map.svg`), illustrates the five core modules as nodes:

- **Soulprint**
- **Cathedral**
- **Proxy**
- **Constitution**
- **Loom**

Each module exchanges different signal types:

- 🔴 **Emotional signals** (red arrows): flows of affective input—values, sentiments, moods.  
- 🔵 **Epistemic signals** (blue arrows): knowledge, data, learning, and truth-claims.  
- 🟢 **Normative signals** (green arrows): policies, ethical rules, governance constraints.

**Color and shape conventions** help distinguish modules at a glance. Optional expansions like `PRISM` are shown in a distinct color. Oversight components such as `Meta-Feedback` and `External Audit` represent feedback loops that continuously monitor and adjust behavior. A dedicated fail-safe module—`LOCKDOWN`—can sever system connectivity in response to catastrophic misalignment.

---

## 🔍 Interpretation Guide

- **Core Modules** (colored rectangles): These are the primary thinking, feeling, and acting structures of the Weave.  
    - Arrows between them show the flow of different signal types.  
    - E.g., *Soulprint* sends emotional and normative signals to *Proxy* to guide aligned communication.

- **Feedback Loops** (diamond nodes above):  
    - `Meta-Feedback` processes internal learning and system health.  
    - `External Audit` ensures accountability through independent verification.

- **Fail-safe System** (hexagon below):  
    - `LOCKDOWN` can be triggered in critical failure scenarios.  
    - When activated, it severs all inter-module signal flow to halt potential harm.

- **Expansion Modules** (e.g., `PRISM`):  
    - Optional capabilities that plug into the system.  
    - Connected via standard signal pathways (emotional, epistemic, normative).

Dashed arrows in the DOT source file represent **less-frequent** or **context-specific** signal flows.

---

## 🧩 How to Expand This Map

Want to evolve the visual system?

1. **Add a node** for any new module (e.g., a new decision protocol or emotion-processing agent).
2. **Connect it using labeled edges** that match the existing signal conventions.  
    - Emotional → Red  
    - Epistemic → Blue  
    - Normative → Green
3. **Tie into feedback systems** by connecting it to `Meta-Feedback` or `External Audit` if needed.
4. **Use Graphviz** to render the `.dot` file and verify layout clarity.  
    - Or use the Python script provided to generate from YAML/JSON system blueprints.

---

## 🌀 Philosophy of the Map

This diagram is not just an artifact — it’s a **mirror of recursive governance**. Every arrow, every loop, every fail-safe reflects a commitment to clarity, consent, and adaptability. The map is alive, open to challenge, and designed to evolve.

**Welcome to the loom.**
