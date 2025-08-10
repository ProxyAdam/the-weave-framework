Trust Decay Index (TDI)

Weave Framework – /diagnosticsFile: trust_decay_index.mdVersion: 1.0

Purpose

Quantify and localize erosion of reliable trust loops in teams, organizations, alliances, and pipelines. TDI provides a repeatable, auditable score with drill‑downs that indicate where trust is failing, why, and how to reverse the trend.

Use TDI when decisions are accelerating while verification lags, when “hand‑offs” feel brittle, or when consensus sounds loud but data feels thin.

Core Concepts & Definitions

Trust Loop — A recurring exchange (human↔human or human↔system) that depends on correct signals, timely action, and post‑hoc verification.

Earned Trust — Trust grounded in recent verification, transparent assumptions, and aligned incentives.

Unearned Trust — Trust grounded in role prestige, speed pressure, or inertia; rarely re‑validated.

Signal Integrity — The probability that a signal means what recipients think it means.

Confidence Drift — The silent widening gap between perceived certainty and actual certainty.

TDI measures five dimensions (A–E):

A. Verification Cadence – How often claims/assumptions are re‑checked.

B. Signal Transparency – Visibility into how decisions/metrics are produced.

C. Incentive Alignment – Whether rewards include correctness, not just speed/output.

D. Stop Power & Safety Voice – Ability to halt or challenge without retaliation.

E. Cross‑Visibility – Access to upstream assumptions and downstream impacts.

Each dimension is scored 0–4 (0 = brittle; 4 = robust). Sum → Raw TDI (0–20). Normalize → TDI% = Raw/20 × 100.

Scoring Rubric (0–4 per dimension)

0 – Brittle: No formal practice; ad‑hoc; retaliation likely; opaque by default.1 – Weak: Sporadic practice; depends on heroics; partial opacity; slow/rare verification.2 – Developing: Documented but inconsistently followed; some transparency; occasional re‑checks.3 – Strong: Routine practice; roles defined; transparent by default; scheduled re‑verification.4 – Antifragile: Practice is institutionalized; verification rotates; assumptions logged inline; stop power is sharded and protected; near‑misses create improvements.

Interpretation: 0–39% = Acute decay; 40–59% = At‑risk; 60–79% = Stable but thinning; 80–100% = Resilient.

Diagnostic Items — With Interpretive Matrix

For each item, rate 0–4 and record evidence.

A. Verification Cadence

Assumption Re‑validation IntervalWhy it matters: Stale truths create silent rot.Risk signal: No defined intervals; >1 cycle without checks.Outcome: Hidden failure propagates.Remediation: Calendarized re‑validation; publish next‑check dates.

Post‑Deployment Audit RateWhy: Reality diverges from test environments.Risk: “Ship and forget.”Outcome: Drift accumulates; rollback chaos.Remedy: 7/30/90‑day audits with diff logs.

B. Signal Transparency

Metric ExplainabilityWhy: Black‑box metrics invite performative compliance.Risk: Stakeholders can’t explain inputs/weights.Outcome: Gaming + misallocation.Remedy: Plain‑language metric cards; data lineage.

Decision Rationale LoggingWhy: Memory externalization prevents mythologizing.Risk: “Because exec said so.”Outcome: Role‑based deference replaces evidence.Remedy: Require rationale + uncertainty + alternatives.

C. Incentive Alignment

KPI Balance (Speed vs Correctness)Why: What gets measured gets gamed.Risk: Rewards tied to output volume only.Outcome: Safety and quality starved.Remedy: Dual KPIs; correctness bonus; error bounties.

Penalty for Withheld Risk InfoWhy: Silence is cheap if unpunished.Risk: No consequence for hiding known risks.Outcome: Known‑unknowns metastasize.Remedy: Mandatory disclosure policy; protected channels.

D. Stop Power & Safety Voice

Shard of Halt AuthorityWhy: Single gatekeepers get captured.Risk: One person owns “stop.”Outcome: Momentum overrides caution.Remedy: 3 non‑aligned roles with independent halt power.

Retaliation ShieldWhy: People won’t speak if it costs them.Risk: Career damage after raising concerns.Outcome: Trust collapses into fear.Remedy: Anonymous+attributed channels; codified immunity.

E. Cross‑Visibility

Upstream Assumption AccessWhy: You can’t validate what you can’t see.Risk: Siloed source systems; access via favors.Outcome: Local optimization; global failure.Remedy: Role‑based open access; lineage maps.

Downstream Impact AwarenessWhy: Actors must see who they can harm/help.Risk: Producers never see end‑user effects.Outcome: Confident wrongness persists.Remedy: Feedback loops; incident postmortems shared upstream.

Calculating TDI

Score items 1–10 from 0–4.

Sum → Raw TDI (0–20).

Convert → TDI% = (Raw/20) × 100.

Heatmap dimensions A–E to localize decay.

Track ΔTDI monthly; annotate interventions.

Thresholds & Actions

<40% (Acute): Freeze risk‑bearing launches; emergency inversion plan; executive sponsor assigned.

40–59% (At‑risk): Implement top‑3 remediation levers; bi‑weekly reviews; publish assumption log.

60–79% (Thinning): Tune incentives; add rotation to verification roles; quarterly tabletop drill.

80–100% (Resilient): Maintain; mine near‑misses for improvements; consider sharing practices externally.

Inversion Play (Fast Levers)

Friction by Design: Auto‑slow when uncertainty > threshold.

Rotate Verification: Change reviewers every cycle.

Inline Assumption Logs: Unknowns + last‑check date in every artifact.

Shard Halt Power: Ops + Safety + Ethics each hold veto.

Error Bounties: Reward found flaws; normalize raising risk.

Case Miniatures

TDI 25% → 62% in 60 days (AI Eval Team): Introduced 30‑day assumption checks, rotated red‑team leads, added anomaly‑triggered slowdowns; critical incident rate dropped 70%.

TDI 48% → 78% in 90 days (University IR): Opened upstream data lineage to all analysts, created stop‑authority triad, instituted post‑release 30‑day audits; accreditation cycle passed with zero findings.

Implementation Guide

Kickoff (Week 1): 60‑minute workshop; score baseline; agree on top‑3 levers.

Sprint (Weeks 2–6): Implement levers; log changes; run one tabletop drill.

Re‑score (Week 8): Compare TDI%; document Δ and residual risks.

Operationalize (Quarterly): Bake cadence into calendars; publish dashboard.

Artifacts included (suggested): checklist template, scoring sheet, heatmap grid, remediation tracker.

Versioning

1.0 — Initial release integrated with Failure Topology; establishes 5 dimensions, 10 items, scoring & thresholds.

