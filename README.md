# copenhagensynergy.github.io

Landing page for Copenhagen Capacity's Copenhagen Synergy pages: https://copenhagensynergy.github.io/

A single static `index.html` (no build step), served by GitHub Pages from `main`.

## Adding a page

Copy a card inside `<div class="grid">` in `index.html`:

- Live page: `<a class="card" href="URL">` with a `Live` tag and an "Open … →" line.
- Coming page: `<div class="card soon">` with a `Coming soon` tag.

Everything on this site is public. Internal pages (deal data, leads) must live behind sign-in elsewhere; this site should only link to them.

## Related

- Events calendar: https://github.com/CopenhagenSynergy/copcap-events (served at `/copcap-events/`)
