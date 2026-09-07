# sundaze-watch-playlists

Approved video playlists and rotating watch inventory for **The Sundaze Gazette** `/watch/` experience.

## Live consumers

Ghost HTML loads:

```
https://cdn.jsdelivr.net/gh/RockSoupTV/sundaze-watch-playlists@main/watch-playlists.json
```

This repo is **intentionally public** so jsDelivr can serve the JSON. Do not put private editorial notes, credentials, or unpublished story drafts here.

## Contents

- `watch-playlists.json` — playlist inventory consumed by the Ghost theme
- `images/` — supporting artwork referenced by the inventory

## Edit rules

1. Keep JSON valid; validate before pushing to `main` (jsDelivr caches by commit).
2. Prefer additive, reviewed changes — bad JSON breaks the public `/watch/` rails.
3. No secrets, no private newsroom content, no personal data.

## Related

- Public site: https://www.sundazegazette.com
- Newsroom desk: `RockSoupTV/-sundaze-gazette` (private)
