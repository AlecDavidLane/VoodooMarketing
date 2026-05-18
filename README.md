# Voodoo Immersive — Engineering Deck

Static HTML slide deck for Voodoo Immersive × Production Bureau, hosted via GitHub Pages.

## View

Once GitHub Pages is enabled, the deck will be available at:

**https://alecdavidlane.github.io/VoodooMarketing/**

## Run locally

Any static file server will do:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Controls

- `→` / `Space` / `PgDn` — next slide
- `←` / `PgUp` — previous slide
- `Home` / `End` — first / last
- `1`–`9`, `0` — jump to slide
- `R` — reset to slide 1
- Touch: tap left/right thirds to navigate

Slides are sized for a 1920×1080 canvas and auto-scale to any viewport.

## Print to PDF

`File → Print` (or `Cmd/Ctrl + P`) → `Save as PDF`. The deck stylesheet
emits one slide per page at the design size, with no chrome.

## Files

- `index.html` — the deck
- `deck.css` — slide styling
- `deck-stage.js` — `<deck-stage>` web component (navigation, scaling, print)
- `assets/` — images and logo
- `.nojekyll` — disables Jekyll on Pages so all assets are served as-is
