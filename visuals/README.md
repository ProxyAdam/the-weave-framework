# Visual System Map

This folder contains visual representations of the core modules of the Weave Framework and their interconnections.

## Map Overview

The `weave_visual_map.dot` file (rendered in `weave_visual_map.svg`) depicts the five core modules of the framework—**Soulprint**, **Cathedral**, **Proxy**, **Constitution**, and **Loom**—as nodes. Each module sends and receives different kinds of signals:

- **Emotional signals** (red arrows): flows of affective data such as values, sentiments, and mood.  
- **Epistemic signals** (blue arrows): flows of knowledge, data, learning signals, and truth‑claims.  
- **Normative signals** (green arrows): flows of policy constraints, ethical rules, and governance directives.

Nodes are colour-coded and shaped consistently to help differentiate them. Expansion submodules such as **PRISM** are drawn in a distinct colour to highlight how additional functionality can plug into the framework. **Meta‑Feedback** and **External Audit** represent feedback loops that monitor and adjust system behaviour, while **LOCKDOWN** is a fail‑safe that can sever signal flow if catastrophic misalignment is detected.

## Interpretation

1. **Core modules (blue ovals)** sit at the centre of the diagram. Arrows connecting them show the primary signal routes. For example, **Soulprint** sends normative and emotional signals to **Proxy** to guide decision‑making, while **Constitution** provides normative governance to all modules.
2. **Feedback loops (purple diamonds)** sit above the core and feed into them. Meta‑Feedback monitors internal performance and sends epistemic and normative corrections back into the network. External Audit represents third‑party oversight.
3. **Fail‑safe (orange hexagon)** sits below the core. LOCKDOWN has connections to all modules; it activates if serious misalignment is detected and halts further execution.
4. **Expansion modules (grey rectangles)** reside to the side of the core. These represent optional extensions (e.g., PRISM) that can be connected via the defined signal types.

Dashed arrows in the DOT file represent optional or less‑frequent interactions.

## How to expand this map

To extend the system:

- **Add new nodes** for additional modules under the appropriate clusters (e.g., new expansion features).
- **Define the edges** specifying which types of signals will flow between the new module and existing ones. Use consistent colours and labels for emotional, epistemic, and normative signals.
- **Add or modify feedback mechanisms** by connecting new feedback loops to relevant modules.
- **Render the DOT file** after making changes to ensure the layout remains clear. The provided `.dot` file uses Graphviz clustering and can be edited manually or regenerated using the included Python script.

By following the patterns in this map, you can grow the Weave Framework’s visual architecture while maintaining clarity.
