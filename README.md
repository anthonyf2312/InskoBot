<div align="center">

![INSKO Bot Banner](public/banner.png?v=2)

# INSKO Bot

[![Version](https://img.shields.io/badge/Version-1.0.0-2ea44f.svg?style=for-the-badge)](CHANGELOG.md)
[![Discord.js](https://img.shields.io/badge/discord.js-v14.26-5865F2.svg?style=for-the-badge&logo=discord&logoColor=white)](https://discord.js.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.9-3178C6.svg?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Prisma](https://img.shields.io/badge/Prisma-6.19-2D3748.svg?style=for-the-badge&logo=prisma&logoColor=white)](https://www.prisma.io/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-4169E1.svg?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Node.js](https://img.shields.io/badge/Node.js-22+-339933.svg?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![License](https://img.shields.io/badge/License-Proprietary-E34F26.svg?style=for-the-badge)](LICENSE)

**A feature-rich, all-in-one Discord bot built exclusively for Insko's community.**

Passport profiles · XP & leveling · Music · Moderation · AutoMod · Verification · Starboard · YouTube alerts · Web dashboard — all with modern **Components V2** designs.

</div>

---

## Features

### 🛂 Passports & Leveling

Every member earns XP through activity and builds a personalised **passport** — a server-rendered PNG profile card shown by `/rank` and in level-up announcements.

- **Web passport editor** — `/passport` links each member to their own editor page with a live animated preview, autosave, and an exact-PNG render button
- **Deep customisation** — 5 layouts, dark/light themes, preset backgrounds (Midnight, Nebula, Aurora, Ember, and more), custom colours, gradients, uploaded background images, 6 fonts, avatar borders, progress-bar styling, card shapes, and cosmetic effects
- **Level-gated unlocks** — customisation options unlock progressively from Level 5 to Level 50, enforced server-side
- **OG badge** — a gold pill on the cards of long-standing members
- **Role rewards** — roles granted automatically at configured levels
- **Leaderboard** — `/leaderboard` ranks the top 10 members by XP

### 🎵 Music

YouTube playback in voice channels, streamed through a dedicated **Lavalink v4** node.

- **`/play`** — search with live autocomplete, or queue a video/playlist URL
- **Now-playing card** — title, author, duration, requester, and thumbnail with pause, skip, stop, and queue buttons
- **Queue management** — paginated `/queue`, `/skip`, `/stop`, `/volume`, `/nowplaying`
- **DJ role** — playback controls can be restricted to a configured role
- **Smart disconnect** — leaves automatically when the channel empties or the queue ends

### 🛡️ Moderation

Every action creates a **numbered case** stored in the database and posted to the mod log as a colour-coded card, with role-hierarchy checks throughout.

- `/ban` (with optional message deletion), `/unban`, `/kick`, `/mute`, `/unmute`, `/warn`, `/purge`
- **Flexible durations** — timeouts accept formats like `10m`, `1h30m`, `2d`
- **Case management** — look up, delete, or clear cases from the admin dashboard

### 🤖 AutoMod

Always-on monitoring that alerts staff rather than punishing automatically.

- **Detects** blocked words, Discord invite links, mass mentions, message flooding, and repeated messages
- **Staff alert cards** with one-click **Delete / Warn / Mute / Safe** actions — every click is stamped with who acted
- **Flood-safe** — a spam burst produces one alert, not ten
- **Applies to everyone**, with a single configurable exempt role

### 🛃 Verification

An optional gate for new joiners: a persistent Verify panel grants the verified role after a challenge — one-click button, image captcha, or math question.

### 📜 Server Logging

Per-category logging with the acting user's avatar on every card.

- **Messages** — edits (before/after) and deletions, including attachments
- **Members** — joins (account age) and leaves (roles held, join date)
- **Mod actions** — manual bans, kicks, and timeouts attributed via the audit log
- **Roles & nicknames** — grants, removals, and name changes

### ⭐ Starboard

Community-curated highlights: messages that reach the reaction threshold are reposted to a hall-of-fame channel with live count updates and media support.

### 👋 Welcomer

Custom greeting messages with `{user}`, `{username}`, `{server}`, and `{memberCount}` placeholders.

### 📺 YouTube Alerts

Channel subscriptions with rich notification cards.

- **Live streams vs uploads** — distinguished automatically, each routable to its own channel
- **Premiere-aware** — scheduled streams announce when they actually go live
- **Optional role ping** and a direct watch button per subscription

### 📊 Server Statistics

Auto-updating locked voice channels displaying live member, human, bot, and boost counts.

### 🚨 Reports

Right-click any message → **Apps → Report to staff** (or use `/report message` with a link or ID). Staff receive a full report card — content, attachments, author, jump link — with Delete/Warn/Safe action buttons, and the reporter gets a private confirmation.

### ⚙️ In-Discord Configuration

- **`/config`** — an interactive Components V2 dashboard covering every module: moderation, AutoMod, logging, verification, welcomer, leveling, starboard, YouTube, server stats, music, and bot presence
- **`/admin`** — admin tools for XP management, case management, passport resets, and system actions

---

## 🌐 Web Dashboard

A React single-page app with Discord OAuth2 login, available to members with **Manage Server**.

- **Every setting** from `/config`, editable in the browser — changes apply to the bot instantly
- **Composer** — build Components V2 messages block by block (styled text, sections, image galleries, buttons, separators, multiple containers) with drag-and-drop reordering, live preview, drafts, templates, and the ability to edit sent messages in place
- **Live feed** — cases, AutoMod alerts, level-ups, and playback events stream to the browser in real time over WebSockets
- **Overview** — stat tiles, XP leaderboard, and recent cases at a glance

A companion **landing page** presents the bot and hosts the access-request form.

---

## 🔒 Private Access

INSKO Bot is private. It only operates in approved servers — joining an unapproved server triggers a polite notice and an approval request to the owner, and the bot leaves until access is granted. Server access can be requested through the website.

---

## Permission Levels

| Level | Who | Access |
|-------|-----|--------|
| **Everyone** | All members | Help, Ping, Rank, Passport, Leaderboard, Music, Reports |
| **Staff** | Moderators | + Moderation commands, alert & log action buttons |
| **Admin** | Manage Server | + `/config`, `/admin`, Web Dashboard |

---

## Tech Stack

<div align="center">

| Technology | Purpose |
|:----------:|:--------|
| ![Discord.js](https://img.shields.io/badge/discord.js-5865F2?style=flat-square&logo=discord&logoColor=white) | Discord API with Components V2 |
| ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) | Type-safe codebase |
| ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) | Type-safe ORM and migrations |
| ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) | Database for configs, cases, levels, and passports |
| ![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white) | Dashboard API, OAuth, and WebSockets |
| ![React](https://img.shields.io/badge/React_+_Vite_+_Tailwind-61DAFB?style=flat-square&logo=react&logoColor=black) | Web dashboard and passport editor |
| ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) | Landing page |
| ![Lavalink](https://img.shields.io/badge/Lavalink_v4-FF6B6B?style=flat-square) | Audio streaming for music playback |
| ![Canvas](https://img.shields.io/badge/@napi--rs/canvas-000000?style=flat-square) | Server-side passport card rendering |
| ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) | Containerised deployment |
| ![Cloudflare](https://img.shields.io/badge/Cloudflare_Tunnel-F38020?style=flat-square&logo=cloudflare&logoColor=white) | Secure public access with no open ports |

</div>

---

## Legal & Privacy

- [Terms of Service](TERMS_OF_SERVICE.md)
- [Privacy Policy](PRIVACY_POLICY.md)
- [License](LICENSE) — Proprietary software

> This is a **private bot** developed exclusively for Insko's Discord community. It operates only in approved servers and is not available for public use or self-hosting.

---

<div align="center">

**Made with ❤️ for Insko**

Developed with the assistance of [Claude Fable](https://www.anthropic.com/claude) by Anthropic.

</div>
