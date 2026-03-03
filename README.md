# Grindset

**Live app:** https://glaseagle.github.io/grindset/

A satirical wellness tracker for your vaping and drinking habits — gamified, socially pressured, and completely unserious.

## What it does

Grindset applies hustle-culture gamification to the least productive behaviors imaginable. Log your vapes and drinks, track your BAC, climb a leaderboard, and earn XP for staying on your grind.

- **Feed** — activity timeline of your logged sessions
- **Record** — log a vape or drink and earn XP
- **BAC Logger** — track your blood alcohol content with a graph over time
- **Leaderboard** — see how your habits stack up against your friends
- **Achievements** — unlock badges for consistent (bad) behavior
- **Streak tracking** — keep the streak alive, don't skip a day
- **Nudge Modal** — get peer-pressured by a random friend when you haven't logged in a while
- **Shop** — spend your hard-earned XP

All data is stored locally in `localStorage` — no account, no server, no judgment (from us).

## Tech stack

- React 19
- Vite
- Recharts (BAC graphs)
- Tesseract.js (OCR for photo uploads)

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```
