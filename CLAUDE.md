# Scene Cockpit

A minimal single-page web app for writers to log and reflect on scenes
during a writing session. It does not generate or edit prose.

## Hard Constraints

"THE AI RETURNS QUESTIONS ONLY. It never suggests, rewrites, or
extends prose. This is a hard constraint."

"Scene text is never saved to local storage. Only metadata and
returned questions are persisted. Individual records can be deleted;
there is no bulk history wipe."

"The API key is session-only. It is never saved to local storage
and must never be committed to GitHub."

## Tech

- Plain HTML + vanilla JavaScript, no framework, no build step.
- Single `index.html` file.
- Colour palette: Background `#14181B`, Surface `#1B2124`,
  Accent `#4C7A73`, Text `#EDE6D9`, Muted `#9CA6A3`.
