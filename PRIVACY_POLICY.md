# Privacy Policy

**Last Updated:** July 2026

## 1. Introduction

This Privacy Policy explains how INSKO Bot ("the Bot", "we", "us") collects, uses, stores, and protects information when you are a member of a server where the Bot operates.

**Note:** This is a private bot developed exclusively for Insko's Discord community. It operates only in approved servers and is not available for public use.

By being a member of a server where the Bot operates and interacting with it, you consent to the data practices described in this policy.

## 2. Information We Collect

### 2.1 Automatically Collected Information

The Bot automatically collects:

- **Server ID and Name**: Identifiers for the servers where the Bot operates
- **Channel IDs**: IDs of channels where the Bot is configured to operate
- **Role IDs**: IDs of roles referenced in Bot configuration
- **User IDs**: Discord user IDs for leveling, moderation, and logging purposes

### 2.2 Configuration Data

Server administrators configure the Bot, which stores:

- Moderation, auto-moderation, and logging settings
- Welcome message templates
- Verification, starboard, leveling, and music settings
- YouTube subscription and notification channel settings
- Server statistics channel IDs
- Bot presence settings

### 2.3 Leveling & Passport Data

To provide the leveling system and passport cards, the Bot stores:

- **XP and Levels**: Per-member XP totals, levels, and message activity timestamps
- **Passport Customisation**: Each member's saved card settings (layout, theme, colours, fonts, effects, and similar preferences)
- **Uploaded Backgrounds**: Background images members choose to upload through the passport editor, stored on the Bot's server

### 2.4 Moderation Data

- **Cases**: Each moderation action (ban, kick, mute, warn, and staff actions taken from alert cards) is stored as a numbered case with the user ID, moderator ID, action type, reason, and timestamp

### 2.5 Message Data (Only if Logging is Enabled)

If server administrators enable message logging, the Bot stores recently seen message content in memory so that edits and deletions can be logged:

- **Message Content**: Original and edited content for edit/deletion log cards
- **Message, Author, and Channel IDs** and timestamps
- **Attachment URLs**: Links to images and files (not the files themselves)

Logging is opt-in per category and must be explicitly enabled by server administrators.

### 2.6 Starboard Data

When messages reach the starboard threshold:

- Message ID, content, and author ID
- Number of reactions received
- Starboard post ID and timestamps

### 2.7 Temporary In-Memory Data

- **Recent message history** for spam and flood detection — cleared automatically after a short window
- **Music queues** — per-server queues exist only in memory
- **Rate-limiting timestamps**

This data is not written to the database and is cleared when the Bot restarts.

### 2.8 Access Request Data

When server access is requested through the website, or when the Bot joins an unapproved server, it records the server ID, server name, the requester's Discord username, and any optional message provided, together with the approval status.

### 2.9 Web Dashboard Data

When you log in to the web dashboard or passport editor with Discord:

- Your Discord account ID, username, and avatar are obtained through Discord OAuth2
- A signed, httpOnly **session cookie** keeps you logged in; it contains no tracking identifiers and expires automatically
- Dashboard access is limited to servers where you hold the Manage Server permission; the passport editor is limited to your own profile in servers you are a member of

## 3. How We Use Your Information

### 3.1 Core Functionality

Collected data is used to:

- Provide Bot features (leveling, passports, music, moderation, logging, starboard, alerts, statistics)
- Respond to commands and component interactions
- Render passport cards and level-up announcements
- Send YouTube notifications when configured
- Power the web dashboard and passport editor

### 3.2 Moderation and Safety

Data is used to:

- Detect spam, flooding, and rule violations for staff review
- Maintain an accountable record of moderation actions
- Track message edits and deletions for transparency

We do NOT sell, rent, or share your data with third parties.

## 4. Data Storage and Security

### 4.1 Database Storage

- All persistent data is stored in a **self-hosted PostgreSQL database** operated privately by the Bot's operator
- Access is restricted to the Bot and its operator; the database is not exposed to the public internet

### 4.2 Security Measures

- Credentials are stored in environment variables, never in code
- The web dashboard uses Discord OAuth2 with signed, httpOnly session cookies
- The dashboard and website are served through an encrypted tunnel with no ports opened to the internet
- Per-server isolation is enforced on every dashboard API call

No method of transmission or storage is 100% secure, and absolute security cannot be guaranteed.

## 5. Third-Party Services

### 5.1 Discord

- All Discord-related data is subject to [Discord's Privacy Policy](https://discord.com/privacy)
- The Bot operates within Discord's infrastructure and uses Discord's API

### 5.2 YouTube

- YouTube alerts read **public channel feeds and video pages** only
- Music playback streams publicly available YouTube content
- No YouTube account data is collected or accessed

### 5.3 Cloudflare

- The web dashboard and landing page are served through Cloudflare's network, subject to [Cloudflare's Privacy Policy](https://www.cloudflare.com/privacypolicy/)

## 6. Data Retention

### 6.1 Retention Periods

- **Server configuration**: Retained until modified or removed by administrators
- **XP, levels, cases, and passport data**: Retained while the Bot serves the server
- **Message logs and starboard posts**: Retained until manually deleted
- **In-memory data** (spam tracking, music queues): Cleared automatically on restart
- **Dashboard sessions**: Expire automatically

### 6.2 Data Deletion

You can request data deletion by:

1. **Contacting server administrators** to request deletion of data associated with your user ID
2. **Contacting Insko** (the server owner) directly

Administrators can reset passports and clear cases directly through the Bot's admin tools. Deletion requests will be processed within 30 days.

## 7. Your Rights and Choices

### 7.1 Server Administrator Rights

Server administrators can:

- **Access** all stored configuration via `/config`, `/admin`, and the web dashboard
- **Modify** settings at any time
- **Delete** cases, reset passports, and clear configuration
- **Opt out** of features by disabling them (logging, leveling, AutoMod, etc.)

### 7.2 User Rights

Individual users have the right to:

- **Access**: Request a copy of data associated with your user ID
- **Erasure**: Request deletion of your data
- **Customisation control**: Edit or clear your own passport at any time through the editor

### 7.3 Exercising Your Rights

To exercise these rights, contact:

- **Insko** (Server Owner): via Discord DM or server channels
- **Server Moderators**: via Discord modmail or support channels

## 8. Children's Privacy

Discord requires users to be at least 13 years old (or older depending on jurisdiction). We do not knowingly collect personal information from children under 13. If we become aware of such data, it will be deleted promptly.

## 9. International Users

Server members may be located in any country. Data may be transferred to and processed in the country where the Bot is hosted. By using the Bot, you consent to such transfer and processing. Reasonable steps are taken to treat data securely and in accordance with this policy.

## 10. Data Breach Notification

In the event of a data breach affecting personal information:

- Server administrators and affected users will be notified within 72 hours of discovery
- Information about the nature of the breach and remedial steps will be provided
- Authorities will be cooperated with as required by law

## 11. Cookies and Tracking

### 11.1 The Bot (in Discord)

The Bot itself does not use cookies, tracking pixels, IP address tracking, cross-server behaviour tracking, or third-party analytics.

### 11.2 The Web Dashboard

The dashboard and passport editor use a **single essential session cookie** to keep you logged in after Discord authentication. No advertising, analytics, or tracking cookies are used.

### 11.3 Internal Metrics

Only operational data is tracked: uptime, error logs, and rate-limit counters — none of it tied to individual browsing behaviour.

## 12. Changes to This Privacy Policy

This Privacy Policy may be updated from time to time. Changes are effective immediately upon posting. Material changes will be communicated through updates to this document (with a revised "Last Updated" date) and announcements in the server. Continued use of the Bot after changes constitutes acceptance of the updated policy.

## 13. Legal Basis for Processing (GDPR)

For users in the European Economic Area, the legal basis for processing is:

- **Consent**: By using the Bot and its web pages, you consent to the data practices described here
- **Legitimate Interests**: Processing necessary to provide Bot functionality, security, and moderation
- **Legal Obligation**: Compliance with applicable laws

You may withdraw consent at any time by leaving the server and requesting data deletion.

## 14. California Privacy Rights (CCPA)

California residents have the right to:

- Know what personal information is collected
- Know whether personal information is sold or disclosed (we do NOT sell data)
- Request deletion of personal information
- Non-discrimination for exercising these rights

To exercise these rights, contact Insko (server owner) or the server moderators.

## 15. Contact Information

For questions, concerns, or data requests regarding this Privacy Policy, please contact:

- **Insko** (Server Owner): via Discord DM or server channels
- **Server Moderators**: via Discord modmail or support channels

Privacy inquiries will be answered within 30 days.

## 16. Acceptance of This Policy

By using INSKO Bot, you acknowledge that you have read, understood, and agree to be bound by this Privacy Policy.

---

**Made with ❤️ for Insko**
