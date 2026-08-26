# Relative Architecture Protocol v1.1

> The Language of Hierarchical Systems: Space. Rules. Dynamics. Diagnostics.

A protocol for observing, diagnosing, and navigating hierarchical systems through 4 axes, 12 dimensions, and 5 discrete phase levels. Applicable to organizations, cities, products, teams, partnerships — any system with at least two levels of access or influence.

---

## For Humans

- **Book PDF v1.1:** [Academy] | [GitHub Release v1.1](https://github.com/Relative-Arch/protocol/releases/tag/v1.1)
- **Changelog:** [CHANGELOG.md](./CHANGELOG.md)
- **Examples:** See Part V of the book (M&A, Urban Management, Startup, Architecture Firm, Political Party)

The book contains the full theoretical foundation, diagnostic atlas, rules, dynamics, and five worked examples across domains.

---

## For AI Agents

This repository contains machine-readable specifications of the Relative Architecture Protocol v1.1. All files are structured for programmatic use.

### Entry Point
- **[llms.txt](./llms.txt)** — Start here. Version, license, links to all spec files, quick reference.

### Canonical Specification Files
| File | Description |
|------|-------------|
| [`spec/context-v1.1.md`](./spec/context-v1.1.md) | Theoretical rationale: ontology, phase logic, rule justification, spin glass analogy |
| [`atlas/atlas.json`](./atlas/atlas.json) | Diagnostic atlas: 60 observable criteria (12 dimensions × 5 levels) |
| [`atlas/atlas.schema.json`](./atlas/atlas.schema.json) | JSON Schema for validating atlas.json |
| [`spec/rules-v1.1.yaml`](./spec/rules-v1.1.yaml) | Formalized rules with rationale references |
| [`spec/glossary-v1.1.json`](./spec/glossary-v1.1.json) | 60 terms structured for RAG systems |
| [`spec/golden-dataset.json`](./spec/golden-dataset.json) | 5 canonical snapshots with expected diagnoses for agent verification |

### Key Constraints for Agents
Before diagnosing or designing interventions, read [`spec/context-v1.1.md`](./spec/context-v1.1.md). All rules derive from structural properties described there. Do not deviate from these invariants:

- Levels 0–4 are **discrete phase states**, not degrees on a continuous scale. No intermediate values.
- **Small steps maintain. Events transition.** Small steps do not accumulate into transitions.
- **Do not manage W directly.** W is a projection of Z/Y/X state, not an independent parameter.
- **Weak link determines ceiling.** Priority goes to the lagging dimension/axis, not the strongest.
- **Presumption of unconfirmed.** No observable event → no level confirmed. Burden of proof on asserter.
- **Monitoring on Z, Y, X — not W.** W is a lagging indicator of danger during reverse transitions.

### Version & Compatibility
- **Protocol version:** 1.1
- **Spec compatibility:** 1.0 (data format unchanged from v1.0)
- **Canonical release:** https://github.com/Relative-Arch/protocol/releases/tag/v1.1
- **License:** CC BY-NC-SA 4.0

---

## Repository Structure
/
├── llms.txt # AI agent entry point
├── README.md # This file
├── CHANGELOG.md # Version history
├── atlas/
│ ├── atlas.json # Diagnostic atlas (machine-readable)
│ └── atlas.schema.json # JSON Schema for atlas validation
└── spec/
    ├── context-v1.1.md # Theoretical rationale
    ├── rules-v1.1.yaml # Formalized rules
    ├── glossary-v1.1.json # Structured glossary
    └── golden-dataset.json # Test dataset for agent verification

---

*Protocol v1.1 · Roman Strokov · 2026*
