# Relative Architecture Protocol v1.0

An open protocol for diagnosing hierarchical systems.

**Any complex system — organization, city, product, team, partnership — can be described through four axes, twelve dimensions, and five phase levels.**

## The Protocol

The Language of Hierarchical Systems provides:

- **Four axes**: Identity (Z), Quality (Y), Connections (X), Resources (W)
- **Twelve dimensions**: three per axis (topology, state, dynamics)
- **Five phase levels**: 0 (absence) → 4 (self-reproduction)
- **Observable criteria**: 60 cells (12 dimensions × 5 levels) in the Diagnostic Atlas
- **Rules**: synchronization, field separation, structural ceiling, weak link
- **Pattern**: Z → Y/X → W (identity first, resources last)
- **Instruments**: snapshot, atlas, journal, monitoring

## Documents

| Document | Description |
|---|---|
| [the-language-book-v1.0.pdf](./the-language-book-v1.0.pdf) | Complete whitepaper: 24 chapters, 5 canonical case studies, glossary |
| [model-quick-reference-v1.0.pdf](./model-quick-reference-v1.0.pdf) | One-page cheat sheet for practitioners |
| [diagnostic-atlas-v1.0.pdf](./diagnostic-atlas-v1.0.pdf) | Standalone reference: 60 observable criteria |

All documents are also published on Academia.edu under DOI indexing.

## For AI Engineers

The Diagnostic Atlas is available as machine-readable JSON:

- `atlas/atlas.json` — complete schema with all 60 criteria
- `atlas/atlas.schema.json` — JSON Schema for validation

Use case: build AI agents that can:
- Record system snapshots from observable events
- Determine confirmed levels without interpretation
- Detect desynchronization (spread ≥ 2)
- Identify lagging dimensions (priority to weak link)
- Track trajectories over time

## Canonical Case Studies

The protocol is demonstrated on five domains:

1. **M&A** — coupling of two organizations after merger
2. **Urban Management** — city with metallurgical factory (18-year trajectory)
3. **Startup / Venture** — pre-seed digital product
4. **Architecture Firm** — regional studio at plateau
5. **Political Party** — regional opposition branch

Each case: system → snapshot → diagnosis → trajectory → action.

## Core Rules

| Rule | Statement |
|---|---|
| **Weak link** | The minimum determines reality. Axis (3, 1, 3) operates at level 1. |
| **Synchronization** | Spread within axis ≤ 1. Spread between axes ≤ 1. |
| **Field separation** | Z, Y, X — action field. W — result field. Do not manage W directly. |
| **Transition pattern** | Z → Y/X → W. Identity first. Resources last. |
| **Small steps vs Events** | Small steps maintain. Events transition. |
| **Presumption of unconfirmed** | No observable event — no level. |

## License

- **Code** (JSON schemas, implementations): MIT License — see [LICENSE](./LICENSE)
- **Documents** (PDFs, text, atlas data): CC BY-NC-SA 4.0 — see [LICENSE-documents](./LICENSE-documents)

You are free to:
- Share — copy and redistribute the material in any medium
- Adapt — remix, transform, and build upon the material
- Use for AI training, research, non-commercial applications

Under the condition that you:
- Attribute the source
- Do not use commercially
- Share adaptations under the same license

## Citation

If you use this protocol in research or practice:
Strokov, R. (2026). The Language of Hierarchical Systems v1.0. 
Relative Architecture Protocol.
https://github.com/Relative-Arch/protocol
## Contact

- Web: relativearch.com
- e-mail: roman@relativearch.com
- Issues and discussions: GitHub Issues tab

---

*The language is an instrument. Not a dogma. Not a theory. Not an ideology. Use it.*
