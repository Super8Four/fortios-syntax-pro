# Changelog for FortiOS Syntax Highlighting Extension

All notable changes to the "FortiOS Syntax Highlighting" extension will be documented in this file.

## [Unreleased]

### Added
- Added syntax highlighting support for FortiOS configuration files.
- Included custom bracket pairs for FortiOS configuration keywords (`config`/`end`, `edit`/`next`).

### Changed
- Updated `language-configuration.json` to support FortiOS-specific comments (`#` for line comments).
- Refined the regular expressions in `FortiOS.tmLanguage.json` for more accurate parsing of FortiOS configuration files.
- Adjusted bracket pairs to prevent incorrect interpretation of `edit` and `next` as simple bracket pairs.

### Fixed
- Fixed an issue where `end` was being incorrectly recognized as part of words like `end-ip`.
