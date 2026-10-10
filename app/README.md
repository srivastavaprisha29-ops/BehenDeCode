# Behen DeCode

A scrapbook-inspired home for a YouTube channel about culture, ideas, and life. Cream paper, espresso typography, pink accents, and supplied moodboard imagery.

## Run locally

From this folder, run `python3 -m http.server 8000 --directory dist`, then open http://localhost:8000.

## What works

- Responsive homepage and section navigation
- Topic filters for episode concepts
- Accessible reading dialogs (including Escape to close)
- Mood-based coffee-break notes
- Reduced-motion preferences

## Files

- `dist/index.html` — content and page structure
- `dist/style.css` — visual design and responsive layout
- `dist/app.js` — filters, dialogs, and coffee-break interactions
- `dist/assets/` — supplied reference images used for this first draft

The episode cards are clearly marked concepts. Add verified YouTube links when episodes exist. Confirm permission to use supplied imagery before making the site public. No accounts, analytics, or mailing list are configured.

## Next

1. Connect the actual channel URL and published episodes.
2. Review copy and image choices.
3. Expand Watch and Read as the content grows.

No build step or npm packages are required. Sites hosting metadata is separate from the site assets; it should not be copied into a different hosting account.
