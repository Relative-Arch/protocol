# Relative Architecture Protocol v1.0

**An open protocol for diagnosing hierarchical systems.**

Any complex system — organization, city, product, team, partnership, political party — can be described through four axes, twelve dimensions, and five phase levels. This repository contains the complete specification, diagnostic instruments, and machine-readable schemas.

> *"The language is an instrument. Not a dogma. Not a theory. Not an ideology. Use it."*

**Author:** Roman Strokov  
**Version:** 1.0 · 2026  
**Web:** [relativearch.com](https://relativearch.com)  
**Contact:** [roman@relativearch.com](mailto:roman@relativearch.com)  
**Academia:** [Roman Ziegel](https://independent.academia.edu/RomanZiegel)

---

## What Is This

The Language of Hierarchical Systems is not a methodology, not a framework, not a set of recommendations. It is a **language for describing the state and dynamics of any system with hierarchy** — where elements are organized by levels of access, influence, or decision-making.

### Four Axes

| Axis | Name | Dimensions |
|---|---|---|
| **Z** | Identity | Z₁ Language · Z₂ Agency · Z₃ Vision |
| **Y** | Quality | Y₁ Embeddedness · Y₂ Adaptation · Y₃ Innovation |
| **X** | Connections | X₁ Breadth · X₂ Depth · X₃ Density |
| **W** | Resources | W₁ Share · W₂ Resilience · W₃ Duration |

### Five Phase Levels

| Level | Phase | Key Property |
|---|---|---|
| 0 | Absence | No interaction |
| 1 | Formal structure | Form exists, no movement |
| 2 | Development | Form adapts, exchange is substantive |
| 3 | Stable state | Self-reproduction without external impulse |
| 4 | Self-reproduction | The system generates quality itself |

### Core Rules

- **Weak link rule.** The minimum determines reality. Axis (3, 1, 3) operates at level 1.
- **Synchronization.** Spread within axis ≤ 1. Spread between axes ≤ 1.
- **Field separation.** Z, Y, X — action field. W — result field. Do not manage W directly.
- **Transition pattern.** Z → Y/X → W. Identity first. Resources last.
- **Small steps vs events.** Small steps maintain. Events transition.
- **Presumption of unconfirmed.** No observable event — no level.

---

## Documents

The protocol is published as three standalone documents, available in this repository and on [Academia.edu](https://independent.academia.edu/RomanZiegel):

| Document | Description | File |
|---|---|---|
| **The Language Book** | Complete whitepaper: 24 chapters, 5 canonical case studies, glossary | [`the-language-book-v1.0.pdf`](./the-language-book-v1.0.pdf) |
| **Model Quick Reference** | One-page cheat sheet for practitioners | [`model-quick-reference-v1.0.pdf`](./model-quick-reference-v1.0.pdf) |
| **Diagnostic Atlas** | Standalone reference: 60 observable criteria (12 × 5) | [`diagnostic-atlas-v1.0.pdf`](./diagnostic-atlas-v1.0.pdf) |

All documents are indexed on Academia.edu under DOI.

---

## For AI Engineers

The Diagnostic Atlas is available as **machine-readable JSON** in the `atlas/` directory:

- [`atlas/atlas.json`](./atlas/atlas.json) — complete schema with all 60 criteria, rules, and phase definitions
- [`atlas/atlas.schema.json`](./atlas/atlas.schema.json) — JSON Schema for validation

### Use Cases

Build AI agents that can:
- Record system snapshots from observable events
- Determine confirmed levels without interpretation (presumption of unconfirmed)
- Detect desynchronization (spread ≥ 2) and identify lagging dimensions
- Track trajectories over time and forecast transition points
- Generate diagnostic reports with priority recommendations

### Example Integration

```python
import json

with open('atlas/atlas.json') as f:
    atlas = json.load(f)

# Get criteria for Z₂ (Agency) at level 3
z2_level3 = atlas['axes']['Z']['dimensions']['Z2']['levels'][3]
print(z2_level3['criterion'])
# → "Independent decision-making. The element acts as a subject, not an object."
```

---

## Canonical Case Studies

The protocol is demonstrated on five domains in Part V of the whitepaper:

| # | Domain | Key Diagnosis | Priority |
|---|---|---|---|
| 1 | **M&A** | Z and X lead Y. W lags. Growth zone. | Y. Quality is not embedded. |
| 2 | **Urban Management** | All axes at 0–1. Y at zero. Early stage. | Z. Identity first. |
| 3 | **Startup / Venture** | Z leads Y, X, W. Spread = 1.67. Growth zone. | Y. Feedback does not influence product. |
| 4 | **Architecture Firm** | Z lags. Agency in one person. Plateau. | Z. Distribution of agency. |
| 5 | **Political Party** | All axes at 0–1. Early stage. | Z. Language does not extend beyond activists. |

Each case follows the same structure: **system → snapshot → diagnosis → trajectory → action**.

---

## Repository Structure
protocol/
├── README.md                          # This file

├── LICENSE                            # MIT License (for code)

├── LICENSE-documents                  # CC BY-NC-SA 4.0 (for documents)

├── the-language-book-v1.0.pdf         # Main whitepaper

├── model-quick-reference-v1.0.pdf     # Cheat sheet

├── diagnostic-atlas-v1.0.pdf          # Atlas PDF

└── atlas/

    ├── atlas.json                     # Machine-readable atlas
    
    └── atlas.schema.json              # JSON Schema for validation
    
---

## How to Use This Protocol

### For Practitioners
1. Read the **Model Quick Reference** (1 page)
2. Study the **Diagnostic Atlas** (60 criteria)
3. Record a **snapshot** of your system (12 dimensions, observable events)
4. Determine levels using the atlas (do not interpret — record)
5. Analyze spread, zones, and priorities
6. Plan actions: small steps (maintenance) or events (transition)

### For Researchers
1. Read the complete **whitepaper**
2. Apply the protocol to your domain
3. Publish case studies with snapshots and trajectories
4. Contribute domain-specific criteria to the atlas

### For AI Engineers
1. Parse `atlas/atlas.json`
2. Build snapshot recording interfaces
3. Implement spread calculation and zone detection
4. Create trajectory visualization and forecasting
5. Share your implementations as open source

---

## License

**Dual licensing:**

- **Code** (JSON schemas, scripts, implementations): **MIT License** — see [`LICENSE`](./LICENSE)
- **Documents** (PDFs, text, atlas data): **CC BY-NC-SA 4.0** — see [`LICENSE-documents`](./LICENSE-documents)

You are free to:
- **Share** — copy and redistribute the material in any medium
- **Adapt** — remix, transform, and build upon the material
- **Use** for AI training, research, non-commercial applications

Under the condition that you:
- **Attribute** the source (cite the protocol)
- **NonCommercial** — do not use for commercial purposes without separate license
- **ShareAlike** — distribute adaptations under the same license

For commercial licensing inquiries: [roman@relativearch.com](mailto:roman@relativearch.com)

---

## Citation

If you use this protocol in research or practice:
Strokov, R. (2026). The Language of Hierarchical Systems v1.0.
Relative Architecture Protocol.
https://github.com/Relative-Arch/protocol
```
**BibTeX:**

```bibtex
@misc{strokov2026relative,
  author = {Strokov, Roman},
  title = {The Language of Hierarchical Systems v1.0},
  year = {2026},
  publisher = {Relative Architecture},
  url = {https://github.com/Relative-Arch/protocol}
}
```

---

## Contributing

This is an open protocol. Contributions are welcome:

- **Domain-specific criteria** — extend the atlas for your field (healthcare, education, military, etc.)
- **Case studies** — publish snapshots and trajectories from real systems
- **Tool implementations** — build diagnostic tools, visualization, AI agents
- **Translations** — translate the protocol to other languages

Open an issue or submit a pull request.

---

## Contact

- **Web:** [relativearch.com](https://relativearch.com)
- **Email:** [roman@relativearch.com](mailto:roman@relativearch.com)
- **Academia:** [Roman Ziegel](https://independent.academia.edu/RomanZiegel)
- **GitHub:** [Relative-Arch](https://github.com/Relative-Arch)
- **Issues:** [GitHub Issues tab](https://github.com/Relative-Arch/protocol/issues)

---

*Take a system. Any. Make a snapshot. Twelve dimensions. Levels from 0 to 4. Confirming events. Not opinions. Events. Look at the spread. Build a trajectory. Determine priority. Act.*
