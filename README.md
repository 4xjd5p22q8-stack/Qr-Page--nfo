# Mobile Itinerary Web App

Mobile-first React + Tailwind app with:
- Welcome screen + Wi-Fi details
- Language selection (English, German, Russian)
- Activity dashboard by selected language
- Activity detail view with full itinerary, what to bring, and what is included

## Run locally

1. Install dependencies:
   - `npm install`
2. Start dev server:
   - `npm run dev`
3. Build for production:
   - `npm run build`

## Translations

All user-facing text is stored in:
- `src/data/content.json`

To add a language, add a new language entry in `languages` and a corresponding object in `translations`.
