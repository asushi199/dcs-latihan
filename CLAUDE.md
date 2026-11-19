# CLAUDE.md

Static single-page site published with GitHub Pages from the `main` branch root.

- `index.html` holds everything (HTML, CSS, JS). No build step, no dependencies.
- Page text is bilingual, written as `"中文 || Bahasa Melayu"` and split by the `T()` helper. Keep both languages in every new string.
- Levels live in the `LEVELS` array; each step has `ask` and `make` (returns `{ check, reveal }`).
- External requests: Google Fonts only. Do not add trackers or other third-party scripts.
- Pushing to `main` redeploys the public site, so confirm with the owner before pushing.
