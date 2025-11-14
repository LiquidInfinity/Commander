# Changelog

All notable changes to Commander will be documented in this file.

## [Unreleased]

### Added
- Added explicit alias support for options and flags (`CommanderName.aliasLong` / `aliasShort`) so compatibility spellings remain usable without cluttering CLI help output. Includes parser + help renderer integration and the ability to hide camelCase forms like `--jsonOutput` while keeping primary shorthands such as `-j` / `--json` visible.
