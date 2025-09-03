# Hugo + GitHub Pages (Minimal)

Tento projekt je minimálny Hugo web, ktorý môžeš spravovať výhradne cez GitHub web UI.

## Deploy
Každý push na `main` spustí GitHub Actions workflow (`.github/workflows/gh-pages.yml`) a nasadí web na Pages.

## baseURL
Projektové repo (napr. `hugo-web`):
```
baseURL = "https://USERNAME.github.io/hugo-web/"
```
User/Org repo (ak sa volá `USERNAME.github.io`):
```
baseURL = "https://USERNAME.github.io/"
```

## Nový článok
Vytvor nový súbor v `content/posts/`:
```
---
title: "Názov"
date: 2025-09-03T12:00:00+02:00
draft: false
summary: "1–2 vety."
tags: ["tag"]
---
Obsah...
```

## Tipy
- Nezabudni `draft: false`
- Ak pridáš custom doménu, uprav `baseURL`