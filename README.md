# Offline Notes Lab

A beginner-friendly offline-first Progressive Web App (PWA) for creating and storing notes locally in the browser.

**Student:** <span style="font-size: 1.2em; font-weight: bold;">OLAJIDE AYOMIDE EVIDENCE</span>

**Matric Number:** <span style="font-size: 1.2em; font-weight: bold;">2024/1/94964ET</span>
**Node.js version:** v22.14.0
**Package manager:** npm 10.9.2

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

Test performed against the production preview (and again at the live URL after deploy):

1. Open the preview/URL in a normal browser window (not incognito)
2. Wait for the service worker to register
3. Open Developer Tools > Application > Manifest to confirm no errors (both icons return 200)
4. Switch Network to Offline in Developer Tools
5. Reload the page - it loads from the cached shell (service worker)
6. Create a note - it persists in localStorage
7. Reload again - the note remains

## Tech Stack

- React 19 with TypeScript
- Vite 8
- localStorage for data persistence
- Service Worker for offline caching
- Web App Manifest for installability

## Git repository

- Repo: https://github.com/debugAyo/swep_project_ayomide_pwa

## Deployment

Deployed to Vercel (production) from the `main` branch.

- Production URL: https://swepprojectayomidepwa.vercel.app/
