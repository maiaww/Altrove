# ALTROVE — a collective for those who wander

Maia's travel blog. A fast, self-contained static website with a built-in
visual editor. No monthly fees.

## Editing your site
Go to **/admin/** on your live site (e.g. https://altrovetravel.com/admin/),
log in with GitHub, and add or edit stories visually. Save → Publish, and the
live site updates in about a minute.

## Structure
- `index.html` — the whole website (design + logic, self-contained)
- `content/stories.json` — your stories (managed by the editor)
- `admin/` — the visual editor (Sveltia CMS)
- `assets/uploads/` — photos you upload through the editor

## One-time setup
In `admin/config.yml`, set the `repo:` line to your GitHub `username/repository`.
See the setup guide that came with this site.
