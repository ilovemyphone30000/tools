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

Not published yet. To serve it from GitHub Pages, push to a repo and point Pages at `main` / root;
Pages serves `index.html` from the root. Ask Jonah before creating the remote or pushing.

A claude.ai artifact copy of this page also exists (private): https://claude.ai/artifact/JgfgRUBCmhRLyh6bkySH8p
