kaiv 1.0 CHANGELOG
==================

[1.0 RC5] - 2026-03-24
----------------------

### Changed

- Project renamed from "Kv Format" to "kaiv"
  - All references to "Kv Format" and "Kv" changed to "kaiv" throughout the spec

- Section 2.7 extended from "Parser" to "Parser and Application"

- Formal grammar edited for clarity

- Copyright attribution changed to "the kaiv authors"


### Changed

[1.0 RC4] - 2026-03-21
----------------------

### Changed

- Added footnote in Section 2.2 about valid keys
  (valid POSIX variable names with no reservations).


[1.0 RC3] - 2026-03-16
----------------------

### Changed

- Section 6.2 (MIME Types) completely rewritten, allowing both
  application/ and text/ MIME types


[1.0 RC2] - 2026-03-16
----------------------

### Changed

- Removed the "line number zero" requirement for shebang lines.

- Relaxed the implementation versioning scheme requirement
  (from MUST to SHOULD)

- Added rationale why this versioning scheme may be desired
  even with languages supporting feature gates (e.g., Rust)

- Added footnote with rationale on EOLs on final line

- Added an edge case clarifying error to raise in case a key consists
  of whitespace characters only
