## Think and talk with me in English.

## Repository maintenance

- Find a venue through [CATALOG.md](CATALOG.md) and [catalog.json](catalog.json); then read that pack's README and local instructions. Do not load every venue pack for one task.
- Shared classification and catalog tooling: [tools/README.md](tools/README.md). It distinguishes failing gates, report-only audits, generators and network-dependent checks.
- Venue-specific sources and examples stay in their owning pack; keep the source versus generated-output distinction documented by the tooling. Existing local edits in a pack belong to that work.
- For document-only changes, check references and preserved contracts. Choose the affected checks from the tooling guide; an audit report is not a passing gate unless the tool's exit contract says so.
Read relevant [lessons](lessons.md) before implementation, review, or acceptance; update the matching entry after an observed correction or missed case.
