# Persian Typing Practice — Vercel

This version embeds the Persian passage source directly in `app.js`.
It does not fetch `data/Persian_Passage_Source.txt` at runtime, so Vercel
cannot fail because of a missing/static-file path.

## Vercel settings

- Framework Preset: Other
- Root Directory: leave blank if these files are at the repository root
- Build Command: leave blank
- Output Directory: leave blank

The repository root should contain:
- index.html
- app.js
- style.css
- vercel.json

Deploy and open `/`.
