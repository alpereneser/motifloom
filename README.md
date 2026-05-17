<p align="center">
  <a href="https://motifloom.com">
    <img src="https://motifloom.com/favicon.svg" width="56" height="56" alt="MotifLoom" />
  </a>
</p>

<h1 align="center">MotifLoom</h1>

<p align="center">
  <b>Visual knowledge mapping.</b><br/>
  Connect books, films, podcasts, games, articles, and notes into interactive graph-based maps.
</p>

<p align="center">
  <a href="https://motifloom.com">Website</a> &nbsp;·&nbsp;
  <a href="https://motifloom.com/explore">Explore Maps</a> &nbsp;·&nbsp;
  <a href="https://motifloom.com/sign-up">Get Started</a> &nbsp;·&nbsp;
  <a href="https://x.com/motifloom">Twitter</a> &nbsp;·&nbsp;
  <a href="https://bsky.app/profile/motifloom.com">Bluesky</a>
</p>

<p align="center">
  <a href="https://www.producthunt.com/posts/motifloom"><img src="https://img.shields.io/badge/Product%20Hunt-Launch%20June%203-ff6154?style=flat-square&logo=producthunt&logoColor=white" alt="Product Hunt" /></a>
  <img src="https://img.shields.io/badge/status-live-22c55e?style=flat-square" />
  <img src="https://img.shields.io/badge/price-free-6366f1?style=flat-square" />
  <img src="https://img.shields.io/badge/platform-web%20·%20PWA-f59e0b?style=flat-square" />
</p>

---

## The Problem

Knowledge is scattered. Books in Goodreads, films in Letterboxd, podcasts in Apple, articles in bookmarks, notes in Notion. **None of them talk to each other.** The brain works in networks — our tools work in lists.

## The Solution

MotifLoom lets you create **motifs** — interactive force-directed graphs centered around any topic. Add books, films, podcasts, games, articles, links, and notes as nodes. Draw connections between them. See how ideas relate.

**The relationships ARE the knowledge, not the individual items.**

<p align="center">
  <img src="https://motifloom.com/social-preview.png" width="640" alt="MotifLoom — Visual Knowledge Mapping" />
</p>

## Features

| | Feature | Description |
|---|---|---|
| 🗺️ | **Graph-first** | Interactive force-directed visualization — drag, zoom, explore |
| 📚 | **7 node types** | Books, films, podcasts, games, articles, links, notes |
| 🔍 | **Auto metadata** | Covers & info from TMDB, Open Library, RAWG, Podcast Index |
| 🔀 | **Fork & remix** | Take any public map and make it yours |
| 🌐 | **Social discovery** | Explore how others mapped the same topic |
| ⚡ | **Quick-add** | URL detection, one-keystroke entry |
| 📱 | **PWA** | Installable, mobile-optimized, works offline |
| 🔄 | **Real-time** | WebSocket collaboration |
| 🏷️ | **Tags & search** | Full-text search powered by Meilisearch |

## How It Compares

| | MotifLoom | Obsidian | Notion | Roam | Goodreads |
|---|:---:|:---:|:---:|:---:|:---:|
| Graph is primary interface | ✅ | ❌ | ❌ | ❌ | ❌ |
| Multi-media (7 types) | ✅ | ❌ | ❌ | ❌ | ❌ |
| Auto-fetched metadata | ✅ | ❌ | ❌ | ❌ | Partial |
| Social (public, fork) | ✅ | ❌ | Partial | ❌ | ✅ |
| No setup required | ✅ | ❌ | ✅ | ✅ | ✅ |
| Free | ✅ | ✅ | Freemium | $15/mo | ✅ |

→ [Detailed comparison with Obsidian](https://motifloom.com/compare/motifloom-vs-obsidian)  
→ [Detailed comparison with Notion](https://motifloom.com/compare/motifloom-vs-notion)  
→ [Detailed comparison with Roam](https://motifloom.com/compare/motifloom-vs-roam)

## Use Cases

- 📖 **[Book mapping](https://motifloom.com/use-cases/book-mapping)** — Connect your reading journey by theme, author, or influence
- 🧠 **[Research](https://motifloom.com/use-cases/research)** — Map papers, articles, and ideas visually
- 🎬 **[Film curation](https://motifloom.com/use-cases/film-curation)** — Connect films by director, genre, or mood
- 🎙️ **[Podcast tracking](https://motifloom.com/use-cases/podcast-tracking)** — Map your podcast universe
- 🧩 **[Second brain](https://motifloom.com/use-cases/second-brain)** — Visual personal knowledge management

## Tech Stack

```
Frontend    SvelteKit 2 · Svelte 5 · Tailwind CSS v4
Backend     Ruby on Rails 8 (API mode) · GraphQL
Database    PostgreSQL + pgvector
Search      Meilisearch
Real-time   ActionCable (WebSocket)
Cache       Redis
Hosting     Hetzner Cloud 🇩🇪
```

## Links

| | |
|---|---|
| 🌐 Website | [motifloom.com](https://motifloom.com) |
| 🗺️ Explore | [motifloom.com/explore](https://motifloom.com/explore) |
| 🐦 Twitter/X | [@motifloom](https://x.com/motifloom) |
| 🦋 Bluesky | [@motifloom.com](https://bsky.app/profile/motifloom.com) |
| 💼 LinkedIn | [MotifLoom](https://www.linkedin.com/company/motifloomhq) |
| 📸 Instagram | [@motifloom](https://www.instagram.com/motifloom/) |
| 🎯 Product Hunt | [MotifLoom](https://www.producthunt.com/products/motifloom) |
| 📧 Contact | alperen@motifloom.com |

## About

Built by **Alperen Eser** — solo founder, full-stack developer.

MotifLoom is a closed-source SaaS product. This repository serves as the public project page.

---

<p align="center">
  <a href="https://motifloom.com/sign-up">
    <img src="https://img.shields.io/badge/Start%20Mapping%20→-Free-6366f1?style=for-the-badge&logoColor=white" alt="Start Mapping" />
  </a>
</p>
