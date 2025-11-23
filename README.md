# INSKO Bot

[![Discord.js](https://img.shields.io/badge/discord.js-v14.25.0-blue.svg?logo=discord&logoColor=white)](https://discord.js.org/)
[![Node.js](https://img.shields.io/badge/node.js-16+-green.svg?logo=node.js&logoColor=white)](https://nodejs.org/)
[![Sapphire Framework](https://img.shields.io/badge/Sapphire-v5.4.0-7c3aed.svg)](https://www.sapphirejs.dev/)
[![License](https://img.shields.io/badge/license-MIT-orange.svg)](LICENSE)
[![MongoDB](https://img.shields.io/badge/MongoDB-v9.0.0-47A248.svg?logo=mongodb&logoColor=white)](https://www.mongodb.com/)

A powerful, all-in-one Discord bot designed for Insko. Built with Discord.js v14 and Sapphire Framework, featuring beautiful **Components V2** message designs.

## ✨ Features

### 📺 YouTube Integration

Real-time notifications for your YouTube channel using push-based webhooks (PubSubHubbub):

- **Live Stream Alerts** - Get notified within seconds when you go live
- **Video Upload Notifications** - Instant alerts for new video uploads
- **Stream End Detection** - Automatically updates when streams end
- **Bot Presence Updates** - Shows "Live" status in Discord during streams
- **Quota Efficient** - Uses minimal API quota (push-based, not polling)

### 👋 Welcome & Farewell Messages

Create custom greetings for new members and farewells for those who leave:

- **Custom Messages** - Use placeholders like `{user}`, `{server}`, `{memberCount}`
- **Separate Channels** - Configure different channels for welcomes and farewells
- **Test Mode** - Preview your messages before going live

### 🛡️ Auto-Moderation

Keep your server clean with automated moderation:

- **Anti-Spam Protection** - Detects message/mention spam with configurable thresholds
- **Link Filtering** - Block unwanted links with whitelist support
- **Bad Word Filter** - Automatic profanity filtering with custom wordlists
- **Flexible Actions** - Choose from warn, timeout, kick, or ban
- **AI-Powered Flagging** - Google Gemini AI analyzes suspicious content for review

### 📝 Advanced Logging

Comprehensive server activity logging:

- **Message Edits & Deletions** - Track all message changes with before/after content
- **Member Events** - Log joins and leaves
- **Moderation Actions** - Automatic logging of all auto-mod actions
- **Media Preservation** - Images and attachments displayed in logs

### ⭐ Starboard

Highlight the best content in your community:

- **Community-Curated** - Members star their favorite messages
- **Customizable** - Set your own emoji and star threshold
- **Media Support** - Images from starred messages displayed in starboard
- **Live Updates** - Star counts update in real-time

### 📊 Server Statistics

Auto-updating voice channels showing server stats:

- **Live Member Count** - Updates every 10 minutes
- **Bot Online Status** - Shows if bot is online/offline
- **Voice Channel Display** - Clean, organized stat channels

### 📚 Interactive Help System

User-friendly help menu with dropdown navigation:

- **Permission-Aware** - Shows only commands you can use
- **Ephemeral Responses** - Private help messages
- **Beautiful Design** - Modern Components V2 styling

## 🎯 Getting Started

Use `/help` in Discord to see all available commands and start configuring the bot for your server!

## 🎮 Commands & Features

### 📚 Help

- `/help` - Interactive help menu with dropdown navigation

### 👋 Welcome & Farewell

Greet new members and say goodbye to those who leave:

- `/welcome` - Configure welcome messages and channels
- `/farewell` - Configure farewell messages and channels
- Test mode available to preview messages

### 🛡️ Auto-Moderation

Protect your server from spam, unwanted links, and bad words:

- `/automod` - Configure spam detection, link filtering, and bad word filters
- Set custom actions: warn, timeout, kick, or ban
- Configure thresholds and whitelists

### 📝 Logging

Track all server activity:

- `/logs` - Set logging channel and toggle log types
- Logs message edits, deletions, member events, and moderation actions
- Media preservation for deleted images

### ⭐ Starboard

Highlight community favorites:

- `/starboard` - Configure starboard channel, emoji, and threshold
- Members react with stars to feature messages
- Automatic updates when star counts change

### 📊 Server Statistics

Display live server stats in voice channels:

- `/stats` - Setup or remove statistics channels
- Shows member count and bot status
- Auto-updates every 10 minutes

### 📺 YouTube Integration _(Owner Only)_

Get notified about YouTube content:

- `/notification` - Set channels for live streams and video uploads
- `/youtube` - Manage YouTube channel subscriptions
- Real-time push notifications via webhooks

### 🔧 Report System

Allow users to report content:

- Right-click message → Apps → Report Message
- Reports sent to configured report channel

## 🔑 Permission System

Commands automatically adjust based on user permissions:

- **Everyone** - Help menu, report system, and starboard reactions
- **Staff** (Manage Guild/Messages) - Moderation, logging, welcomes, stats
- **Bot Owner** - YouTube integration and advanced settings

## 💬 Message Placeholders

Use these in welcome and farewell messages:

- `{user}` - Mentions the user (@Username)
- `{server}` - Server name
- `{memberCount}` - Total member count

**Example**: `Welcome {user} to {server}! You are member #{memberCount}!`

## 🛠️ Tech Stack

Built with modern technologies:

- **Discord.js v14** - Latest Discord API with Components V2
- **Sapphire Framework** - Command handling and bot structure
- **MongoDB** - Database for server configurations
- **Google Gemini AI** - AI-powered content moderation
- **YouTube Data API v3** - Official YouTube integration
- **PubSubHubbub** - Real-time push notifications

## 📄 License

This project is provided as-is for educational and personal use.

---

**Made with ❤️ for Insko**
