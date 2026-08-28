# Changelog

All notable changes to the "Rapikan" extension will be documented in this file.

## [1.1.0] - 2026-08-28

### Added

- **New Language Support:** Added zero-config formatting support for **GDScript** (Godot Engine) using `gdscript-formatter`.
- **New Language Support:** Added support for **Protocol Buffers** (`.proto`).

### Fixed

- Excluded stray internal text files (`Hi HN.txt` and `reddit.txt`) from the published VSIX package to keep the extension clean and lightweight.

## [1.0.3] - 2026-08-12

### Added

- Added `CHANGELOG.md` to display version history directly in the VS Code Marketplace tab.

## [1.0.2] - 2026-08-12

### Fixed

- Updated End User License Agreement (EULA) with correct legal entity name and pricing details.
- Fixed markdown formatting rendering issue on the Marketplace License page.

## [1.0.1] - 2026-08-12

### Fixed

- Fixed an issue where the inline `// rapikan-ignore` magic comment would incorrectly delete the code line.
- Fixed a typo in the Ko-fi donation link in the README documentation.

## [1.0.0] - 2026-08-11

### Added

- Initial public release of Rapikan - Universal Code Formatter.
- Support for zero-config, auto-downloading formatting across 50+ programming languages.
- Introduced Universal Magic Comments (`rapikan-ignore`, `rapikan-off`, `rapikan-on`).
