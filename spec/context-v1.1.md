# Context and Rationale: Protocol v1.1

This document provides the theoretical foundation for the Relative Architecture protocol. It explains *why* the rules and structures exist, not just *what* they are. Agents MUST read this document before performing diagnostics or designing interventions to preserve interpretive fidelity.

**Version:** 1.1  
**Compatibility:** Atlas and rules unchanged from v1.0  
**Key addition:** Structural analogy with spin glass physics (§4.7)

---

## 1. Ontology: Three Properties of Hierarchical Systems

Hierarchical systems are not flat networks. They possess three structural properties that determine all subsequent rules. These are observed regularities, not metaphors.

### 1.1 Non-additivity
The distance between levels is NOT equal to the sum of small steps. One cannot reach level N+1 by accumulating N touches at level N. A transition requires an **event** — a qualitative shift that opens access to another level. Small steps maintain; events transition. This follows from the ultrametric nature of hierarchical spaces.

### 1.2 Discreteness
Between levels there are NO intermediate states. Trust is either formal (level 1) or expert (level 2). Access either exists or does not. The system is in one phase or another. There is no "2.5" or "70% strategic partner." Levels 0–4 describe **phase states**, not degrees on a continuous scale. Transitions are jumps, not smooth movements.

### 1.3 Weak Link Determines Ceiling
If a system has elements at different levels, the system as a whole operates at the level of the **lowest** element. The lagging element does not pull down — it prevents rising higher. Until it is strengthened, the system will not move. This is NOT an arithmetic mean. The minimum determines the maximum possible.

> **Rationale for rules:** All diagnostic and intervention rules derive from these three properties. Ignoring them leads to systematic errors: attempting growth through small steps (violates non-additivity), assigning intermediate levels (violates discreteness), prioritizing strong dimensions (violates weak link).

---

## 2. Phase Logic: Qualitative States, Not Degrees

Levels 0–4 are **phases**, analogous to phases of matter (solid, liquid, gas, plasma). Each phase is qualitatively distinct from others.

| Level | Phase | Key Property | Transition Trigger |
|-------|-------|--------------|-------------------|
| 0 | Absence | No interaction | First event |
| 1 | Formal structure | Form exists, no movement | Event creating interest |
| 2 | Development | Movement exists, form adapts | Event changing perception |
| 3 | Stable state | Self-reproduction without external impulse | Event changing role |
| 4 | Self-reproduction | System generates quality independently | — |

### 2.1 Spin Glass Analogy (v1.1 Addition)
The phase structure has a direct parallel in spin glass models (Sherrington–Kirkpatrick, p-spin):
- **Metastable states** ↔ Phases 0–4. Transitions require overcoming energy barriers, not accumulating fluctuations.
- **Energy (W)** ↔ Functional of configuration, not independent control parameter. Cannot change W without synchronizing Z, Y, X. Confirms rule "do not manage W directly."
- **Frustration** ↔ Desynchronization (spread ≥ 2). Conflicting interactions prevent stable state. Prioritizing lagging dimension = relieving frustration = lowering energy barrier for system-wide transition.

> **Rationale:** This analogy confirms that protocol properties are not arbitrary conventions but reflect universal regularities of complex systems with ultrametric structure. Agents must treat levels as discrete basins of attraction, not points on a continuum.

---

## 3. Rule Rationale

Each rule in `rules-v1.1.yaml` derives from ontology. Below is the explicit rationale for every rule.

### 3.1 Synchronization Rules
- **Spread within axis ≤ 1 → Synchronized.** Rationale: Weak link property. If spread ≥ 2, the axis operates at the minimum level, not the mean. Mean is misleading. Priority goes to lagging dimension because strengthening strong dimensions yields no result until weak link is reinforced.
- **Spread between axes ≤ 1 → Synchronized.** Rationale: Same weak link logic applied at system level. Inter-axis desynchronization indicates structural instability. Priority to lagging axis prevents cascade.

### 3.2 Field Separation
- **Z, Y, X = action field. W = result field.** Rationale: W is a projection of Z/Y/X state, not an independent parameter. Projection changes AFTER state changes, never before. Managing W directly violates causality and destroys non-financial axes (see §6.5 violation scenarios).
- **Growth zone (Z,Y,X > W):** Normal. Potential accumulated. Do not force W.
- **Risk zone (W > Z,Y,X):** Alarm. Resources unsecured by structure. Urgent work on Z,Y,X.

### 3.3 Structural Ceiling
- **Three cycles without shift despite methodical effort = ceiling, not stagnation.** Rationale: Distinguishes objective environmental constraint from insufficient effort. Stagnation is cured by resuming work; ceiling is not. Misdiagnosis wastes resources.
- **Strategies: alignment or expansion.** Alignment increases stability at current ceiling. Expansion bypasses ceiling through adjacent domain growth. Neither removes ceiling.

### 3.4 Small Steps vs Events
- **Small steps counteract entropy. Events change phase.** Rationale: Non-additivity. Small steps operate WITHIN current phase. Events CROSS phase boundary. Confusing them = spending resources on impossible (growth via small steps) or risking accumulated capital (no maintenance between events).
- **Catalyst paradox resolved:** Small step triggers transition ONLY in pre-critical system where potential is already accumulated. Same step in unprepared system = ordinary touch. Effect depends on system state, not action magnitude.

### 3.5 Entropy and Maintenance
- **Without maintenance, degradation is inevitable.** Rationale: Second law analog. Entropy is continuous; maintenance must be regular and proportional to level. Higher levels require MORE substantial small steps (non-additivity again).
- **Antifragility:** Stress transitions READY system (potential accumulated, synchronized). Stress DESTROYS unready system. Difference is state, not stress magnitude.

---

## 4. Intervention Typology

| Type | Function | Condition | Result |
|------|----------|-----------|--------|
| Small step | Counteract entropy | Regular, proportional to level | System remains at current phase |
| Event | Change phase | Independent value + no immediate request + perception shift | System transitions to next phase |
| Catalyst | Trigger transition | Small step in PRE-CRITICAL system only | System transitions to next phase |

> **Critical distinction:** Events have THREE required properties (independent value, absence of immediate request, shift in perception). Missing any one = not an event. Agents must verify all three before classifying intervention as event.

---

## 5. Presumption of Unconfirmed

**No observable event → no level confirmed.** Burden of proof lies with the asserter. If level 3 criteria are not met by recorded event, system is at level 2. NOT "between 2 and 3." At 2.

> **Rationale:** Removes subjectivity. Ensures reproducibility: two observers recording same events obtain same snapshot. Two observers interpreting same events obtain different snapshots. Protocol works with recordings, not interpretations.

---

## 6. Boundaries and Limitations

- Protocol describes **direction** of movement, not exact events or timing. Like thermodynamics: predicts gas expansion, not molecular trajectory.
- Protocol does NOT replace expert judgment. Structures observation; does not substitute for context, history, intonation, hidden motives.
- Protocol does NOT give ready-made solutions. Shows WHERE system is. Action determined by human context.
- Applicability: any system with at least two levels of access/influence. Does NOT apply to purely flat networks (rare in practice).

---

## Cross-References

- Full atlas criteria: `atlas.json`
- Formalized rules: `rules-v1.1.yaml`
- Glossary: `glossary-v1.1.json`
- Book chapters: §1.1 (properties), §4.5–4.7 (phases + spin glasses), §5–9 (rules), §14 (presumption of unconfirmed)
- Constraints for agents: `/spec/constraints.md`

---

*This document is part of Protocol v1.1. Canonical source: https://github.com/Relative-Arch/protocol/releases/tag/v1.1*

**License** "MIT (see LICENSE-MIT); book text under CC BY-NC-SA 4.0 (see LICENSE-BOOK)"
