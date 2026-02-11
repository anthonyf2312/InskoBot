<div align="center">

![INSKO Bot Banner](public/banner.png?v=2)

# INSKO Bot

[![Discord.js](https://img.shields.io/badge/discord.js-v14.25-5865F2.svg?style=for-the-badge&logo=discord&logoColor=white)](https://discord.js.org/)
[![Sapphire](https://img.shields.io/badge/Sapphire-v5.4-7c3aed.svg?style=for-the-badge)](https://www.sapphirejs.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.7-3178C6.svg?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-9.0-47A248.svg?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Node.js](https://img.shields.io/badge/Node.js-20+-339933.svg?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![License](https://img.shields.io/badge/License-Proprietary-E34F26.svg?style=for-the-badge)](LICENSE)

**A feature-rich, all-in-one Discord bot built exclusively for Insko's community.**

Passport profiles · XP & leveling · Last.fm · Music ratings · Starboard · YouTube alerts · QOTD · and more — all with beautiful **Components V2** designs.

</div>

---

## Features

### 🆔 Passport & Profiles

Every member builds a personalised passport card through activity — displaying level, XP, badges, stats, reputation, and more rendered as server-side images.

- **Customisable themes** — Default, Midnight, Gold, Forest, Ocean, Sunset
- **Custom colours & backgrounds** — Unlocked at Level 5 and Level 15 respectively
- **Badge showcase** — Earned badges with tier-specific icons
- **Leaderboard** — Top 10 users ranked by level and XP
- **Privacy controls** — Toggle visibility of safety rating, join date, and reputation

### 📊 XP & Leveling System

Earn XP from messages, voice activity, and reactions with built-in anti-exploit protections.

- **Messages** — 15–25 XP per message (60s cooldown)
- **Voice channels** — 5 XP per minute (120 min cap per session)
- **Reactions** — 2 XP given, 5 XP received (5s cooldown)
- **Anti-abuse** — Spam detection, similarity checks, rate limiting, minimum message length
- **100 levels** with progressive titles from Newcomer to Legendary
- **Level rewards** — Profile customisation, custom backgrounds, reaction boost, extended badge showcase, animated borders, particle effects, and Legendary status

### 🏆 Badges

12 badges with 5 tiers each, automatically awarded based on activity thresholds.

| Badge | Earned By |
|-------|-----------|
| ⭐ Stargazer | Messages reaching the starboard |
| 🛡️ Guardian | Long-term membership with clean record |
| 🎨 Artist | Images reaching 10+ stars |
| 💬 Chatterbox | Total messages sent |
| 🔥 Dedicated | Longest messaging streak |
| 🦋 Social Butterfly | Stars received on messages |
| 🤝 Helping Hand | Reactions given to others |
| 📅 Consistent | Current active messaging streak |
| 🎙️ Voice Active | Hours spent in voice channels |
| ⚡ Reactor | Reactions received |
| 🎭 Sko | Having "sko" in your display name |
| 👑 Legendary | Reaching Level 100 |

### 🎧 Last.fm Integration

Full Last.fm integration with OAuth account linking, inspired by .fmbot.

- **Now Playing** — Current track with play count, genre tags, and album art
- **Top lists** — Top tracks, artists, albums, and genres with time period filters
- **Who Knows** — Server leaderboards for artists, tracks, and albums
- **Taste comparison** — Compatibility percentage with shared artist breakdown
- **Listening streaks** — Consecutive plays of the same artist, album, or track
- **Weekly overview** — Now playing + top 3 artists, tracks, and albums

### 🎵 Music Ratings

Rate songs, albums, and EPs on a 1.0–10.0 scale with Spotify-powered search.

- **Community ratings** — Browse recent, top-rated, and most popular
- **Song versions** — Separate tracking for Original, Remix, Cover, Live, and Acoustic
- **Filter by type** — Songs, Albums, or EPs
- **Edit ratings** — Update your 25 most recent ratings anytime

### 🎵 Reaction Box

Community song submissions for Insko to react to on YouTube, running in 7-day cycles.

- **Submit songs** — Spotify search via modal
- **Community voting** — Upvote and downvote buttons on submissions
- **Auto-approval** — Songs meeting the upvote threshold are moved to an approved channel
- **Configurable** — Set channels, thresholds, and cycle limits

### ⭐ Starboard

Highlight the best content in the community with real-time star tracking.

- **Configurable threshold** — 1–50 stars required
- **Live updates** — Star count updates as reactions change
- **Media support** — Images and attachments displayed in starboard posts
- **Components V2** — Modern Discord message styling

### 👋 Welcome & Farewell

Custom greetings and goodbye messages with placeholder support.

- **Placeholders** — `{user}`, `{server}`, `{memberCount}`
- **Separate channels** — Independent configuration for welcomes and farewells
- **Test mode** — Preview messages before going live

### 🎭 Auto-Role

Automatically assign a role to new members on join with hierarchy and permission validation.

### ❓ Question of the Day

Automated daily questions posted on a schedule — AI-generated via Google Gemini or manually queued.

- **Scheduled posting** — Configurable time (UTC) and channel
- **Queue system** — Add, list, and remove custom questions
- **AI fallback** — Auto-generates a question when the queue is empty
- **Optional ping role** — Notify members of new questions

### 📺 YouTube Integration

Real-time YouTube notifications using PubSubHubbub push webhooks.

- **Live stream alerts** — Notified within seconds when going live
- **Video upload notifications** — Instant alerts for new uploads
- **Stream end detection** — Automatic status updates
- **Bot presence** — Shows "Live" status in Discord during streams
- **Quota efficient** — Push-based, not polling (~3 API units per notification)

### 📊 Server Statistics

Auto-updating voice channels displaying live server stats.

- **Member count** — Updates every 10 minutes
- **Bot status** — Shows online/offline with watchdog monitoring

### 🔨 Moderation & Reports

- **Purge** — Bulk delete up to 100 messages, optionally filtered by user
- **Report system** — Right-click context menu to report messages to moderators

### 🔒 Privacy & Data Management

GDPR/CCPA-compliant data tools — view, export, and delete personal data.

### 📚 Help System

Interactive, permission-aware help menu with dropdown navigation and Components V2 styling. Only shows commands and categories the user has access to.

---

## Permission System

| Level | Who | Access |
|-------|-----|--------|
| **Everyone** | All members | Passport, Level, Rewards, Last.fm, Music Ratings, Reaction Box, Privacy, Report, Help |
| **Staff** | Manage Guild / Messages | + Welcome, Farewell, Autorole, Starboard, Stats, Report Config, Badge Admin, XP Admin |
| **Owner** | `OWNER_IDS` env var | + YouTube, QOTD, Dev, Shutdown, Backfill, Maintenance |

---

## Tech Stack

<div align="center">

| Technology | Purpose |
|:----------:|:--------|
| ![Discord.js](https://img.shields.io/badge/discord.js-5865F2?style=flat-square&logo=discord&logoColor=white) | Discord API with Components V2 |
| ![Sapphire](https://img.shields.io/badge/Sapphire_Framework-7c3aed?style=flat-square) | Command handling, listeners, preconditions |
| ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) | Type-safe codebase |
| ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) | Database for all guild configs, profiles, and ratings |
| ![Spotify](https://img.shields.io/badge/Spotify_API-1DB954?style=flat-square&logo=spotify&logoColor=white) | Song and album search for ratings and Reaction Box |
| ![Last.fm](https://img.shields.io/badge/Last.fm_API-D51007?style=flat-square&logo=lastdotfm&logoColor=white) | Scrobble data, listening stats, and leaderboards |
| ![YouTube](https://img.shields.io/badge/YouTube_Data_API-FF0000?style=flat-square&logo=youtube&logoColor=white) | Real-time push notifications via PubSubHubbub |
| ![Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=flat-square&logo=google&logoColor=white) | AI-generated QOTD questions |
| ![Canvas](https://img.shields.io/badge/@napi--rs/canvas-000000?style=flat-square) | Server-side image rendering for passport and level cards |

</div>

---

## Legal & Privacy

- [Terms of Service](TERMS_OF_SERVICE.md)
- [Privacy Policy](PRIVACY_POLICY.md)
- [License](LICENSE) — Proprietary software

> This is a **private bot** developed exclusively for Insko's Discord community. It is not available for public use, self-hosting, or invitation to other servers.

---

<div align="center">

**Made with ❤️ for Insko**

</div>

