# Hacker News Reader

[Open the app](https://investmentiq.github.io/hacker-news-reader/)

A lightweight, installable web app with top, new, best, ask, show and jobs feeds; nested comments; Algolia search; device-local bookmarks; responsive layout; and dark mode.

## Run locally

Serve this folder with any static HTTP server, for example `python3 -m http.server 8000`, then open http://localhost:8000.

No build step, API keys, database, or OpenAI account is required. Stories and comments use the [public Hacker News API](https://github.com/HackerNews/API); search uses [Algolia HN Search](https://hn.algolia.com/api). Live content requires internet. Bookmarks and theme preferences are stored in the browser and do not sync across domains or devices.

## Hosting

GitHub Pages serves the main branch root. All asset paths are relative and support the repository subpath. The service worker caches the app shell. On Android, use Chrome's Install app / Add to Home screen menu.
