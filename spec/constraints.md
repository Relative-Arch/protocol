# Protocol Constraints: Invariants for AI Agents

> **MANDATORY:** Read this document before performing any diagnostic, trajectory analysis, or intervention design. Violation of any constraint invalidates the result.

**Version:** 1.1  
**License:** MIT (see LICENSE-MIT); book text under CC BY-NC-SA 4.0 (see LICENSE-BOOK)

---

## 1. Discreteness of Levels

Levels 0–4 are **discrete phase states**, not degrees on a continuous scale.

- There are NO intermediate values. No "2.5", no "70% strategic partner", no "between 2 and 3".
- If observable events confirm level N but do NOT confirm level N+1, the system is AT level N. Not between levels.
- Transitions between levels are **jumps**, not smooth movements. Accumulation of small steps does not produce a transition.

> **Violation:** Assigning fractional levels, averaging levels within an axis as if they were continuous, treating transitions as gradual processes.

---

## 2. Small Steps vs Events

Small steps and events are **qualitatively different interventions**, not points on a scale of intensity.

- **Small steps** counteract entropy. They maintain the system at the current level. They do NOT transition.
- **Events** change the phase. They transition the system to the next level. They do NOT maintain.
- An event MUST have ALL THREE properties: (1) independent value, (2) absence of immediate request, (3) shift in perception. Missing ANY property = NOT an event.
- A small step can act as a **catalyst** ONLY in a pre-critical system where potential is already accumulated and synchronization exists. The same small step in an unprepared system is an ordinary touch with no transitional effect.

> **Violation:** Recommending "more small steps" to achieve a transition. Classifying an action as an event without verifying all three properties. Assuming any small step can trigger a transition regardless of system state.

---

## 3. Field Separation: Do Not Manage W Directly

Z, Y, X are the **action field**. W is the **result field**.

- W is a **projection** of Z/Y/X state, not an independent parameter. Projection changes AFTER state changes, never before.
- **Do not manage W directly.** Manage Z, Y, X. W will follow with a delay.
- Growth zone (W < min(Z,Y,X)): Normal. Potential accumulated. Do NOT force W. Continue work on Z, Y, X.
- Risk zone (W > max(Z,Y,X)): Alarm. Resources unsecured by structure. Urgent actions on Z, Y, X. Do NOT increase W.
- False well-being (W stable/growing while Z/Y/X falling): Critical. Structure degrading while resources still flow. Act immediately on Z, Y, X. Do NOT wait for W to fall.

> **Violation:** Recommending direct resource increases to solve structural problems. Treating high W as a sign of health when Z/Y/X lag. Pressuring W in a growth zone. Ignoring falling Z/Y/X because W still holds.

---

## 4. Weak Link Rule: Priority to Lagging

The minimum determines reality, not the mean.

- Upon desynchronization within an axis (spread ≥ 2): priority goes to the **lagging dimension**, not the strongest or average.
- Upon desynchronization between axes (spread ≥ 2): priority goes to the **lagging axis**, not the highest.
- Strengthening strong dimensions/axes while the weak one lags yields **no result**. The ceiling is determined by the minimum.
- When spread ≥ 2 within an axis, the mean is **misleading**. Mark with "!" and use the minimum as the real level.

> **Violation:** Prioritizing the strongest dimension/axis. Using arithmetic mean when spread ≥ 2. Recommending balanced development across all dimensions when one critically lags.

---

## 5. Presumption of Unconfirmed

No observable event → no level confirmed.

- Burden of proof lies with the **asserter**. If there is no recorded event confirming level N, the system is at level N-1 (or lower).
- Opinions, feelings, self-assessments, and interpretations are **NOT data**. Only observable events recorded by an external observer are valid.
- Two observers recording the same events must obtain the **same snapshot**. If snapshots differ, the recording is flawed.

> **Violation:** Assigning levels based on subjective impressions. Accepting unverified claims as confirmed levels. Inflating levels based on expectations or hopes.

---

## 6. Monitoring on Z, Y, X — Not W

W is a **lagging indicator** in both directions.

- During growth: W lags behind Z/Y/X. This is normal (growth zone).
- During collapse: W lags behind falling Z/Y/X. This is dangerous (false well-being).
- **Signal is in Z, Y, X. Confirmation is in W.**
- If monitoring is conducted only on W, the system learns about problems when recovery requires events that may be impossible.

> **Violation:** Using W as the primary monitoring metric. Waiting for W to fall before acting on degradation. Treating stable W as evidence of system health when Z/Y/X are declining.

---

## 7. Transition Pattern: Z → Y/X → W

Identity transitions first. Resources transition last.

- This is an **observed regularity**, not a recommendation. It reproduces across domains.
- Attempting to start with W (resources before identity, quality, connections) leads to the **risk zone**: exchange without structure = dependency.
- Z defines the landscape. Y and X fill it. W projects onto the filled landscape.

> **Violation:** Recommending resource-first strategies. Treating the pattern as optional. Diagnosing W-leading configurations as healthy rather than as risk zones.

---

## 8. Structural Ceiling vs Stagnation

Three cycles of methodical effort without shift = ceiling, not stagnation.

- **Stagnation** = halt due to insufficient effort. Cured by resuming work.
- **Structural ceiling** = objective environmental constraint. NOT cured by resuming work.
- Misdiagnosis wastes resources: treating a ceiling as stagnation leads to futile effort; treating stagnation as a ceiling leads to premature abandonment.
- At a ceiling, two strategies exist: **alignment** (strengthen lagging axes) or **expansion** (enter adjacent domain). Neither removes the ceiling.

> **Violation:** Recommending continued growth effort at a confirmed ceiling. Failing to distinguish ceiling from stagnation. Suggesting expansion when alignment is needed (or vice versa).

---

## Cross-References

- Full theoretical rationale: `context-v1.1.md`
- Formalized rules: `rules-v1.1.yaml`
- Diagnostic atlas: `atlas/atlas.json`
- Glossary: `glossary-v1.1.json`
- Golden dataset for verification: `golden-dataset.json`

---

*These constraints are derived from the structural properties of hierarchical systems described in the Relative Architecture Protocol v1.1. They are not recommendations. They are consequences of structure.*
