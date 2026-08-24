# Provenance

This directory makes `research-clean/` verifiable rather than asserted.

- `source-file-list.txt` — all 211 markdown files under `research/` (209 lesson/article files + 2 index files), the denominator for coverage.
- `inventory/` — the flat index built by the inventory pass (2026-08-05): every named term, claim, procedure, and criterion in the corpus, with source path and stage. 11 chunk files covering the whole corpus. This was the raw material for basis selection; kept as a permanent work product.
- `coverage-map.md` — every source file → where its content landed in `research-clean/`
  (211/211 accounted: 185 placed, 16 dropped with rationale, 8 locked/unpublished, 2 indexes).
- `dropped.md` — everything removed as pedagogical scaffolding, with rationale per removal.
- `not-captured-register.md` — the complete register of content that does not exist in the
  capture: 28 locked Supplementary sub-pages, 3 unpublished pages, inaccessible external
  resources.
- `synthesis-plan.md` — the controlling record of the synthesis judgment: basis selection
  rationale, dedup decisions, writer placement plan.

Source corpus: `../research/` (read-only, gitignored, paid ICS material — internal reference only).
Every entry in `01-logic/`, `02-concepts/`, `03-details/` carries a `sources:` list of the files it was derived from.
