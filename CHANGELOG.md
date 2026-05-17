# Changelog

All notable changes to the CurriculumMD specification are documented here.

Format follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).
Versioning follows [Semantic Versioning](https://semver.org/).

---

## [0.1] — 2026-05-16

### Added
- Initial draft of the CurriculumMD specification as part of the LearnSpec suite.

### Changed
- Level 2 per-objective attributes moved from a leading `[id:…]` square-bracket group to a trailing `{id:…}` curly-brace group, for cleaner graceful degradation: the objective text comes first, and `{…}` avoids the link-reference and task-list collisions of `[…]`.
