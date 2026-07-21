# Calf Rehab

A tolerance-gated recovery tracker for a grade-1 gastrocnemius strain — the
"back to the trail" plan. Rather than advancing on a fixed calendar, it gates
each phase on how the calf actually responded: you log pain and load, and the
next phase unlocks only when your tolerance says it should.

## What it is

- **A single self-contained static page.** Everything — markup, styles, logic —
  lives in `index.html`. No build step, no dependencies, no server, no network
  calls at runtime.
- **Progress is stored in the browser, per device.** State is kept in
  `localStorage`, so your log lives on whichever phone or laptop you used. It is
  never uploaded anywhere, and it does not sync between devices. Clearing site
  data (or using a private window) wipes it.
- **Built for the iPhone home screen.** `apple-touch-icon.png` is served from the
  site root, so "Add to Home Screen" gives it a proper icon.

## Live URL

**https://dandunbar.github.io/calf-rehab/**

Open it on your iPhone, then Share → Add to Home Screen.

## Running it locally

Open `index.html` in any browser. That's the whole thing.

## License

MIT — see [LICENSE](LICENSE).
