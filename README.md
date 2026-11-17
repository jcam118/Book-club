# Upward Facing Thots — Book Club

A book club app for Jess, Mandy & Beatriz, named after the group chat.

- **The Shelf** — every book we've read, as spines on a shelf (Little Bee → Many Lives, Many Masters → Men Are from Mars, Women Are from Venus).
- **A world per book** — its own colors, plus tabs for discussion **Questions** (everyone posts their take), **Activities**, a **Notes** wall (notes, quotes, hot takes, page numbers), and **Goals & reminders** with due dates and the next meetup.
- **Thot-o-meter** — each of us rates every book out of 5.
- **Copy for the chat** — a ready-to-paste update for the group chat.
- **Have Claude build this world** — new books get questions, activities and a reading plan generated on demand.

## Files
- `index.html` — the whole app. Published as a Claude artifact, it syncs through the artifact's shared database. Opened directly in a browser, it runs as a local copy saved in that browser.
- `starter.js` — the starter shelf used by the local copy.
- `data/build-starter.mjs` — single source for the curated book worlds; run `node data/build-starter.mjs` to regenerate `starter.js` and `data/seed-batch.json` (the shared-database seed).
