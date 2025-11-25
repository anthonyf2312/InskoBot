# Changelog

All notable changes to INSKO Bot will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.1] - 2025-01-XX

### ✨ Added

#### 🎭 Auto-Role System

- **Automatic Role Assignment** - New members automatically receive a configured role when joining
- **Staff Management** - `/autorole` command with three subcommands:
  - `/autorole set <role>` - Configure which role to assign automatically
  - `/autorole remove` - Disable auto-role assignment
  - `/autorole view` - View current auto-role configuration
- **Smart Validation**:
  - Prevents assigning managed roles (bot roles, integration roles)
  - Validates role hierarchy to ensure bot can assign the role
  - Prevents setting @everyone as auto-role
  - Automatically detects and handles deleted roles
- **Permission-Based** - Only users with "Manage Server" permission can use this command
- **Invisible to Members** - Command is hidden from users without proper permissions

## [1.0.0] - 2025-01-XX

### 🎉 Initial Release

Welcome to INSKO Bot! A powerful, all-in-one Discord bot for content creators and community management.

### ✨ Features Added

#### 📺 YouTube Integration

- Real-time notifications for live streams and video uploads
- Bot status updates to "Live" when streaming
- Stream end detection with automatic message updates
- Instant push notifications (no polling required)

#### 👋 Welcome & Farewell Messages

- Custom greeting messages for new members
- Farewell messages when members leave
- Placeholders: `{user}`, `{server}`, `{memberCount}`
- Test mode to preview messages before enabling

#### 🎭 Auto-Role

- Automatic role assignment for new members
- Staff-only configuration commands
- Smart validation and error handling

#### 🛡️ Auto-Moderation

- **Anti-Spam** - Detect and remove spam messages
- **Link Filter** - Block unwanted links with whitelist support
- **Bad Word Filter** - Automatic profanity detection
- **Custom Actions** - Warn, timeout, kick, or ban offenders
- **AI-Powered** - Google Gemini AI flags suspicious content for review

#### 📝 Advanced Logging

- Message edits and deletions tracked
- Member join and leave events logged
- Moderation actions automatically recorded
- Media preservation for deleted images

#### ⭐ Starboard

- Community-curated content highlights
- Customizable star emoji and threshold
- Real-time star count updates
- Image support in starboard posts

#### 📊 Server Statistics

- Auto-updating voice channels showing server stats
- Live member count display
- Bot online/offline status indicator
- Updates every 10 minutes

#### 📚 Help System

- Interactive help menu with dropdown navigation
- Shows only commands you have permission to use
- Private responses (ephemeral messages)
- Modern, beautiful design

#### 🔧 Report System

- Right-click any message → Apps → Report Message
- Reports sent to configured moderation channel
- Includes message content and user information

### 🎮 Commands Available

- `/help` - View all commands and features
- `/welcome` - Configure welcome messages
- `/farewell` - Configure farewell messages
- `/autorole` - Configure automatic role assignment
- `/automod` - Auto-moderation settings
- `/logs` - Logging configuration
- `/starboard` - Starboard settings
- `/stats` - Server statistics setup
- `/notification` - YouTube notification channels _(Owner Only)_
- `/youtube` - Manage YouTube subscriptions _(Owner Only)_
- `/report` - Report system configuration

### 🎨 Design

All messages use Discord's modern **Components V2** design with:

- Beautiful containers with accent colors
- Visual separators for clean layouts
- Media galleries for images
- Rich markdown formatting

---

## 🔮 Coming Soon

Ideas for future updates:

---

## 📝 Notes

- This is a private bot for Insko
- Optimized for Insko
- Built with Discord.js v14 and Sapphire Framework
