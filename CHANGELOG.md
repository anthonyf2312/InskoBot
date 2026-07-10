# Changelog

All notable changes to INSKO Bot will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2026-07-10

### 🎉 Initial Release

INSKO Bot 1.0 — a feature-rich, all-in-one Discord bot built exclusively for Insko's community, with every message styled using Discord's modern **Components V2** design.

### ✨ Features

#### 🛂 Passports & Leveling

- XP earned per message with configurable rates and cooldowns
- `/rank` renders each member's personalised passport as a server-side PNG
- Web-based passport editor with live animated preview and autosave — layouts, themes, fonts, colours, gradients, uploaded backgrounds, avatar borders, progress-bar styling, card shapes, and cosmetic effects
- Customisation unlocks progressively from Level 5 to Level 50
- OG badge for long-standing members
- Role rewards granted automatically at configured levels
- `/leaderboard` — top 10 members by XP
- Level-up announcements featuring the member's own card

#### 🎵 Music

- YouTube playback in voice channels via a dedicated Lavalink v4 node
- `/play` with live search autocomplete, video URLs, and playlist support
- Now-playing card with pause, skip, stop, and queue controls
- `/pause`, `/skip`, `/stop`, `/queue`, `/volume`, `/nowplaying`
- Optional DJ role gating for playback controls
- Automatic disconnect when the voice channel empties or the queue ends

#### 🛡️ Moderation

- `/ban`, `/unban`, `/kick`, `/mute`, `/unmute`, `/warn`, `/purge`
- Numbered cases stored in the database and posted to the mod log as colour-coded cards
- Human-friendly timeout durations (`10m`, `1h30m`, `2d`)
- Role-hierarchy checks on every action

#### 🤖 AutoMod

- Detection for blocked words, invite links, mass mentions, flooding, and repeated messages
- Staff alert cards with one-click Delete / Warn / Mute / Safe actions
- Alert throttling — one alert per incident, not one per message
- Configurable exempt role

#### 🛃 Verification

- Persistent Verify panel granting a configured role
- Three challenge types: one-click button, image captcha, and math question

#### 📜 Server Logging

- Message edits and deletions (with attachments)
- Member joins and leaves
- Manual moderation actions attributed via the audit log
- Role and nickname changes
- Independent per-category toggles

#### ⭐ Starboard

- Configurable trigger emoji and threshold
- Live star-count updates and media support

#### 👋 Welcomer

- Custom greeting templates with `{user}`, `{username}`, `{server}`, and `{memberCount}` placeholders

#### 📺 YouTube Alerts

- Per-channel subscriptions with rich notification cards
- Live streams and uploads distinguished automatically, each routable to its own channel
- Premiere-aware announcements and optional role pings

#### 📊 Server Statistics

- Auto-updating voice-channel counters for members, humans, bots, and boosts

#### 🚨 Reports

- Right-click context menu and `/report message` for reporting content to staff
- Full report cards with staff action buttons and private reporter confirmation

#### ⚙️ Configuration

- `/config` — interactive in-Discord dashboard covering every module
- `/admin` — XP tools, case management, passport resets, and system actions

#### 🌐 Web Dashboard

- Discord OAuth2 login for members with Manage Server
- Every bot setting editable in the browser, applied instantly
- Composer for building and editing Components V2 messages with live preview, drafts, and templates
- Real-time event feed over WebSockets
- Overview page with stat tiles, leaderboard, and recent cases

#### 🔒 Private Access

- Approval-based server allowlist with owner review
- Access-request form on the landing page

---

## 📝 Notes

- This is a private bot for Insko's community
- Built with Discord.js v14, TypeScript, Prisma, and PostgreSQL
