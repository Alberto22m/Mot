# Motivator quotes database

Static files served by GitHub Pages for the Motivator iOS app.

- `manifest.json` — version, sha256 and number of quotes per language.
- `quotes_en.json`, `quotes_ru.json`, `quotes_es.json`, `quotes_fr.json` — the same quotes in four languages.

How to publish an update: see `docs/QUOTES_DB.md` in the app project. Upload the quote files first, the manifest last.
Sources of every quote are in the `source` and `sourceUrl` fields. Translations marked `"translator": "own"` are our own.
