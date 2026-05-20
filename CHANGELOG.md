# Changelog

All notable changes to the CurriculumMD specification are documented here.

Format follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).
Versioning follows [Semantic Versioning](https://semver.org/).

---

## [Unreleased]

### Added
- `description` optional frontmatter field — short plain-text summary (typically 1–3 sentences) for catalogues, alignment tools, and link previews. Distinct from the structured `level` / `domain` / `version` fields — particularly useful for CurriculumMD whose primary function is to be referenced and aligned against. Backward-compatible: existing files remain valid; no `spec_version` bump.

---

## [0.1] — 2026-05-16

### Added
- Initial draft of the CurriculumMD specification as part of the LearnSpec suite.

### Changed
- Level 2 per-objective attributes moved from a leading `[id:…]` square-bracket group to a trailing `{id:…}` curly-brace group, for cleaner graceful degradation: the objective text comes first, and `{…}` avoids the link-reference and task-list collisions of `[…]`.
