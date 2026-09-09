# Offline Notes Lab

A beginner-friendly offline-first Progressive Web App (PWA) for creating and storing notes locally in the browser.

**Student:** OLAJIDE AYOMIDE EVIDENCE
**Matric Number:** 2024/1/94964ET

## Run locally

```bash
npm install
npm run dev
```

## Verify the build

```bash
npm run check
npm run build
npm run preview
```

## PWA test

1. Open the preview URL in a normal browser window (not incognito)
2. Wait for the service worker to register
3. Open Developer Tools > Application > Manifest to confirm no errors
4. Switch Network to Offline in Developer Tools
5. Reload the page - it should load from cache
6. Create a note - it should persist in localStorage
7. Reload again - the note should remain

## Tech Stack

- React 19 with TypeScript
- Vite 8
- localStorage for data persistence
- Service Worker for offline caching
- Web App Manifest for installability

## Deployment

Deployed via Vercel from the `main` branch.
