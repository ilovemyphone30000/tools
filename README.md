# AI tools site

One static page listing the five AI tools: A&R Superplaylist, the show list and announcements page,
the itinerary builder, the AXS resale scan and the label map.

- `index.html` — the whole site. No build step, no dependencies, no network calls. Open it in a browser.

## Rules for this page

- Public-safe only: no client names, no agent names, no passwords, no numbers from the client sheet.
- Tool descriptions stay general. Links go only to pages that are already published
  (the Superplaylist dashboard and the label map, both on GitHub Pages).
- Look follows the `clean-web` skill: system sans, off-white background, one accent, 1px rules, no cards.
- The footer carries the "as of" date. Update it when the tool list changes.

## Publishing

Repo: github.com/ilovemyphone30000/tools (the local folder keeps the longer name).
GitHub Pages serves `index.html` from `main` / root, so a push to `main` deploys within about a minute:
https://ilovemyphone30000.github.io/tools/

Ask Jonah before pushing.
