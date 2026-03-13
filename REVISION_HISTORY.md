# Revision History

## 2026-03-13
- Recorded and prepared local enhancements for publication.
- Updated repository documentation to reflect current operational and integration changes.
- CI hardening: dependency install now falls back from `npm ci` to `npm install` when lockfile drift is present.
- Docker hardening: runtime `data/` directory is tracked via `.gitkeep`, and image build tolerates missing pre-bundled `data/nodes.db`.
- Railway Docker hardening: builder dependency install now falls back from `npm ci` to `npm install` to avoid lockfile-drift build failures.
