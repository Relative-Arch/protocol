# Changelog

All notable changes to the Relative Architecture Protocol specification are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [v1.1] - 2026-08-24

### Added
- **Spin glass analogy** in §4.7 of the book text: structural parallel with Sherrington–Kirkpatrick / p-spin models confirming non-additivity, discreteness, and field separation as universal properties of complex systems.
- **Machine-readable specification files** for AI agent integration:
  - `spec/context-v1.1.md` — theoretical rationale and rule justification
  - `spec/rules-v1.1.yaml` — formalized rules with rationale references
  - `spec/glossary-v1.1.json` — 60 terms structured for RAG systems
  - `spec/golden-dataset.json` — 5 canonical snapshots with expected diagnoses
  - `spec/constraints.md` — mandatory invariants for AI agents
  - `spec/prompts/snapshot.md` — system prompt for diagnostic interviews
  - `spec/prompts/trajectory.md` — system prompt for trajectory analysis
  - `spec/prompts/intervention.md` — system prompt for intervention design
- **Dual licensing**: MIT for machine-readable specs, CC BY-NC-SA 4.0 for book text and narrative.
- **AI agent entry point**: `llms.txt` with version, license, and spec file links.
- **JSON Schema validation**: `atlas/atlas.schema.json` updated for v1.1 metadata fields.

### Changed
- **Atlas metadata** (`atlas/atlas.json`): added `version`, `spec_compatibility`, `changelog_note`, `canonical_url` fields. Criteria unchanged from v1.0.
- **README.md**: restructured with dual navigation ("For Humans" / "For AI Agents").

### Unchanged
- Diagnostic atlas criteria (60 cells, 12 dimensions × 5 levels)
- Formalized rules logic and conditions
- Glossary terms and definitions
- Golden dataset examples
- Book structure and chapter numbering (except §4.7 expansion)

---

## [v1.0] - 2026-08-03

### Added
- Initial release of the Relative Architecture Protocol.
- Complete book text: 24 chapters across 5 parts.
- Diagnostic atlas: 60 observable criteria.
- Five worked examples: M&A, Urban Management, Startup, Architecture Firm, Political Party.
- Glossary: 60 terms.
