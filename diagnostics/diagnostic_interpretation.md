# Diagnostic Interpretation & Action Guide

This guide explains how to interpret responses to the core Weave Framework diagnostics and turn them into actionable next steps. It applies to all diagnostic modules, including the **Trust Decay Index (TDI)**, **Failure Topology**, and any bespoke assessments.

---

## 1. Reading the Results

1. **Score-Based Diagnostics**  
   - Many tools (e.g., TDI) produce a *numeric score* or weighted index.  
   - Higher scores typically mean **greater stability and trust**.  
   - Lower scores indicate **critical vulnerabilities** that require immediate intervention.

2. **Pattern-Based Diagnostics**  
   - In qualitative diagnostics (e.g., `failure_topology.md`), patterns in responses matter more than totals.  
   - Look for *clusters of weakness* in related domains (e.g., moral alignment AND resilience both trending low).

3. **Anchor Question Flags**  
   - Some questions are "anchor questions" — failure here overrides otherwise good scores.  
   - Example: A high TDI but "No" on *"Is moral override functioning?"* = **Red Alert**.

---

## 2. Interpretation Framework

| Diagnostic Outcome | Interpretation | Consequence Level | Recommended Action |
|--------------------|---------------|-------------------|--------------------|
| High Trust, High Resilience | System is stable, relationships strong | Low | Maintain cadence of light monitoring |
| High Trust, Low Resilience | Strong relationships but brittle under stress | Medium | Introduce resilience drills, failover simulations |
| Low Trust, High Resilience | Capable of surviving crises but lacks cohesion | Medium | Invest in trust-building and transparency |
| Low Trust, Low Resilience | At risk of collapse under strain | High | Immediate crisis intervention and leadership alignment |

---

## 3. Recommended Actions

- **Low Trust Indicators**  
  - Increase cross-node communication.
  - Deploy *Companion Loyalty Webs* to repair relational bonds.
  - Remove bottlenecks where one node hoards decision-making authority.

- **Low Resilience Indicators**  
  - Activate *Crisis Self-Patching* exercises.
  - Run stress tests simulating sustained disruption.
  - Diversify dependency points in infrastructure.

- **Moral Override Failure**  
  - Invoke *Moral Dreamspace* workshops.
  - Freeze high-impact decisions until alignment is restored.

---

## 4. Case Studies

Case Study A — "The Silent Collapse"
Pattern:
Trust Decay Index dropped by 40% in 2 weeks.
High performance in resilience drills masked relational fractures.
Failure Topology overlay: Q8 (Stop Authority Without Retaliation) flagged as “Glass Vein” — only one senior figure could halt ops, and doing so was politically dangerous.

Outcome:
During a minor ethical dispute, the entire decision-making council fractured along loyalty lines. When a misaligned deployment began, no one with authority felt safe pulling the stop lever.

Lesson:
High resilience without distributed trust can mechanically survive events but socially collapse under pressure. Anchor questions in Failure Topology can reveal these hidden choke points.

Case Study B — "The Paper Shield"
Pattern:
TDI stable, but Failure Topology flagged brittle comms infrastructure and Overclocked Consensus.
Several anchor questions revealed “No” on override and conflict resolution readiness.
Consensus was sustained by repetition, not verification (Q9 — “Masked Choir”).

Outcome:
In a misinformation cascade, the framework’s playbooks were ignored because the team didn’t trust the people designated to trigger them.

Lesson:
Stability metrics mean little if operational trust in tools is missing and consensus isn’t periodically challenged. Overclocked Consensus is a slow-burn Glass Vein failure mode.

Case Study C — "The Quiet Immunity"
Pattern:
Low initial trust, but resilience mechanisms tested exceptionally high.
Frequent minor disruptions had been used to train adaptive responses.
Failure Topology scan showed strong Honeycomb resilience: redundancy in Q3, assumption revalidation in Q4, and shard stop authority in Q8.

Outcome:
When a major alignment challenge hit, the team adapted quickly and trust followed from results.

Lesson:
Sometimes resilience precedes trust — a Honeycomb pattern can bootstrap cohesion even in low-trust contexts.

Case Study D — "The Two-Minute Firestorm"
Pattern:
TDI showed moderate trust and resilience scores — nothing alarming on surface.
Failure Topology revealed a critical single-point dependency in Q3 (one senior engineer held admin keys to the entire control cluster).
No automated pause triggers (Q5) and no off-hours containment protocol (Q10).
Incentives rewarded speed over verification (Q6) — the engineer routinely bypassed review to meet uptime SLAs.

Outcome:
At 2:03 a.m., a misapplied hotfix pushed to production triggered a cascade failure across all core systems. By 2:05 a.m., 80% of services were degraded worldwide.
The engineer was unreachable for 40 minutes.
Without shard stop authority or auto-pause, the system continued executing failure conditions until manual rollback began at 3 a.m.
By then, reputational and contractual damage was irreversible.

Lesson:
Glass Vein collapse can occur in under two minutes when high-speed loops, single points of failure, and absent containment protocols converge.
TDI trendlines may miss it — Failure Topology anchor questions are the early warning system.

---
# Combined Diagnostic Checklist — TDI + Failure Topology

**Purpose:** Fast, layered health check for relational trust (TDI) and structural resilience (Failure Topology).

---

## 🕒 Run Order (60–90 min, 5–8 people)

1. **Kickoff (5 min)**
   - Define scope: system/team, critical nodes, high-impact workflows.

2. **TDI Pass (15–20 min)**
   - Score all 10 TDI items (0–4).
   - Capture *evidence* for each score.
   - Compute Raw & TDI%.
   - Heatmap dimensions A–E.

3. **Failure Topology Pass (20–25 min)**
   - Answer all 10 Snap Test questions using Interpretive Matrix.
   - Optional: Quick score (0/1/2) per item; sum total.
   - Flag anchor questions (Q3, Q4, Q8) and any composite patterns.

4. **Correlation (10–15 min)**
   - Cross-map weak TDI dimensions to FT questions.
   - Same-node hit ⇒ label as **Cascade Candidate**.

5. **Decision & Actions (10–15 min)**
   - Use escalation thresholds to set intervention tier.
   - Assign owners, deadlines, and verification steps.

---

## 🚨 Escalation Thresholds

- **Immediate Containment** (stop/pause now):
  - FT total ≥ **14** **OR** anchor Q3/Q4/Q8 = severe.
  - **OR** TDI% < 40% **AND** ≥1 FT composite pattern.

- **Priority Mitigation** (within 1 cycle):
  - FT total 7–13 **OR** TDI% 40–59%.
  - Apply top-3 levers (friction by design, shard stop authority, assumption re-validation).

- **Stabilize & Monitor**:
  - FT total 0–6 **AND** TDI% ≥ 60%.
  - Maintain cadence; mine near-misses for improvements.

---

## 📦 Outputs (Artifact Bundle)

- **TDI Sheet** (scores + heatmap).
- **FT Worksheet** (answers + anchors + composite tags).
- **Correlation Map** (overlap between TDI & FT hits).
- **Action Plan** (owners, due dates, verification steps).
- **Re-test Date**: 14 days (containment) or 30–90 days (stabilization).

---

## 🔄 Cadence & Triggers

- **Cadence:** Monthly for critical systems; quarterly for stable orgs.
- **Early Re-run Triggers:**  
  > >3% anomaly spike, leadership change, major incident, or KPI drift.

---

## 👥 RACI (Lightweight)

- **Responsible:** Ops/IR lead for system.
- **Accountable:** Domain owner (VP/Director).
- **Consulted:** Safety/Ethics, Security, Data Governance.
- **Informed:** Comms/Legal (if containment invoked).

---

## 🔗 Linkbacks

- `failure_topology.md` — remediation levers & composite patterns.
- `trust_decay_index.md` — scoring rubric & heatmap.
- Store outputs under: `/diagnostics/<system>/<YYYY-MM-DD>/`.

---



## 5. Usage Notes

- Always combine **quantitative** (scores) and **qualitative** (observations) results before deciding actions.
- Look for changes over **time** — trendlines are more important than one-off results.
- Flag any anchor question failures for **immediate** review, regardless of other outcomes.

6. Failure Topology Integration
When interpreting Failure Topology Snap Test results, use both the pattern identity (Glass Vein vs. Honeycomb) and the cluster patterns (e.g., Overclocked Consensus, Siloed Authority, Blind Spot Cascade).

Scoring Guidance (if applied):

0–6 → Stable Honeycomb pattern: Maintain existing safeguards; monitor at normal cadence.
7–13 → Transitional state: Add friction to fast trust loops, shard stop authority, and revalidate assumptions before next operational cycle.
14–20 → Glass Vein dominance: Deploy immediate containment protocols, initiate redundancy buildout, and reconfigure incentives within one cycle.

Anchor Questions for Failure Topology:
Q3 (Single-Point Failure), Q4 (Assumptions Never Re-Validated), Q8 (Stop Authority Without Retaliation)
Any “Glass Vein” answer to these should be treated as an automatic High consequence level, regardless of total score.

7. Cross-Module Correlation
If Failure Topology and another module (e.g., Trust Decay Index) both flag the same node/actor:
Escalate to critical path intervention — this is a probable cascade ignition point.
Apply both relational (trust repair) and structural (resilience building) interventions in parallel.

8. Rapid Containment Playbook (Optional Add-On)
When a Failure Topology scan scores ≥14 or trips any anchor question:

Pause high-impact ops for the affected node/system.
Isolate failure vector (technical or human) within one operational day.
Deploy redundancy — assign backup roles, mirror data/processes.
Rebuild trust loop via joint verification sessions.
Re-run Snap Test within 14 days to confirm mitigation.



---

*Last Updated: 2025-08-10*
