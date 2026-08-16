[CHANGELOG.md](https://github.com/user-attachments/files/31110999/CHANGELOG.md)
# Changelog

## 5.1.0 — Foundry VTT 14.365 / PF2e 8.4.0

- Added Foundry VTT v14.365 compatibility.
- Updated the package manifest to target Foundry v14.365 and PF2e 8.4.0.
- Normalized legacy JournalEntry `permission` data to v14 `ownership`.
- Normalized legacy Folder `parent` source data to v14 `folder`.
- Fixed tiled Scene grid data to use v14 `grid.type`.
- Raised the PF2e minimum version check from 6.2.1 to 8.4.0.
- Kept the existing PDF parsing and adventure-specific importer intact.
- Added a small v14 compatibility layer so future document-schema fixes can be isolated from the parser.
