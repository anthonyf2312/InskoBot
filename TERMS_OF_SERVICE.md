# Terms of Service

**Last Updated:** July 2026

## 1. Acceptance of Terms

By using INSKO Bot ("the Bot") in a server where it operates, you agree to be bound by these Terms of Service. If you do not agree to these terms, please leave the server or do not interact with the Bot.

**Note:** This is a private bot developed exclusively for Insko's Discord community. It operates only in approved servers and is not available for public use or self-hosting.

## 2. Description of Service

INSKO Bot provides the following services:

- **Passports & Leveling**: XP tracking, rendered profile cards, a web-based passport editor, and level-based role rewards
- **Music Playback**: YouTube audio playback in voice channels
- **Moderation**: Ban, kick, timeout, warn, and purge commands with a numbered case system
- **Auto-Moderation**: Detection of blocked words, invite links, mass mentions, flooding, and repeated messages, with alerts for staff review
- **Verification**: An optional challenge gate for new members
- **Logging System**: Message edit/deletion tracking, member event logging, moderation action logging, and role/nickname change logging
- **Starboard**: Community-curated message highlighting
- **Welcome Messages**: Automated greetings for new members
- **YouTube Alerts**: Notifications for live streams and video uploads
- **Server Statistics**: Live server statistics displayed in voice channels
- **Report System**: User-initiated content reporting
- **Web Dashboard**: Browser-based configuration and a public passport editor, secured with Discord login

## 3. Server Administrator Responsibilities

Server administrators and moderators agree to:

- Configure the Bot in accordance with Discord's Terms of Service and Community Guidelines
- Not use the Bot to harass, abuse, or harm other users
- Not use the Bot to collect, store, or distribute personal information without consent
- Review auto-moderation alerts and reports in a timely and fair manner
- Ensure that any logged data is used only for legitimate moderation purposes
- Handle user data responsibly and in accordance with the Privacy Policy

## 4. User Responsibilities

By being a member of a server where the Bot operates and interacting with it, you agree to:

- Comply with Discord's Terms of Service and Community Guidelines
- Accept that your messages may be logged if the server has enabled logging features
- Not attempt to exploit, damage, or interfere with the Bot's functionality
- Not use the report system to submit false or malicious reports
- Only upload passport background images you have the right to use, and no unlawful or inappropriate content

## 5. Data Collection and Usage

The Bot collects and stores the following data:

### Server Configuration Data

- Server ID and per-module settings configured by administrators
- Channel IDs (for logs, welcomes, starboard, notifications, etc.)
- Role IDs (for rewards, pings, verification, and DJ/exempt roles)
- Custom messages and templates

### Leveling & Passport Data

- User IDs with XP totals, levels, and activity timestamps
- Passport customisation settings and optional uploaded background images

### Moderation Data

- Numbered moderation cases: user ID, moderator ID, action type, reason, and timestamp

### Message Data (when logging is enabled)

- Message content for edit/deletion logs, message IDs, author IDs, channel IDs, timestamps, and attachment URLs

### Starboard Data

- Message ID, content, and author ID of starred messages, star counts, and starboard post IDs

### Access Requests

- Server ID, server name, requester's Discord username, and an optional message, submitted via the website or recorded when the Bot joins an unapproved server

### Web Dashboard Data

- Discord account ID and username obtained through Discord OAuth2 login, held in a signed session cookie

All data is stored in a self-hosted PostgreSQL database accessible only to the Bot and its operator.

## 6. Data Retention

- **Server configuration, cases, levels, and passports**: Retained until modified or deleted by administrators, or until the server's access is removed
- **Message logs and starboard data**: Retained until manually deleted by administrators
- **Music queues and auto-moderation tracking**: Held in memory only and cleared when the Bot restarts
- **Dashboard sessions**: Expire automatically

Users who leave the server may request deletion of their data by contacting the server administrators.

## 7. Third-Party Services

The Bot integrates with the following third-party services:

- **Discord**: All functionality operates through Discord's API and infrastructure
- **YouTube**: Public channel feeds and video pages are read for alerts and music playback; no YouTube account data is accessed
- **Cloudflare**: The web dashboard and landing page are served through Cloudflare's network

Your data may be processed by these services according to their respective privacy policies. No personally identifiable information is shared with these services beyond what is necessary for the Bot's functionality.

## 8. Limitation of Liability

The Bot is provided "as is" without any warranties. The Bot operator is not liable for:

- Any damages resulting from the use or inability to use the Bot
- Data loss or corruption
- Missed notifications or delayed responses
- Actions taken by server moderators based on Bot-provided information
- Downtime, errors, or bugs in the Bot's functionality

## 9. Service Availability

- The Bot may be temporarily unavailable for maintenance
- Features may be added, modified, or removed at any time
- Service may be terminated for any server or user that violates these terms

## 10. Modifications to Terms

These Terms of Service may be modified at any time. Changes are effective immediately upon posting. Continued use of the Bot after changes constitutes acceptance of the modified terms.

## 11. Termination and User Removal

The Bot operator reserves the right to:

- Terminate Bot service at any time, for any reason
- Revoke a server's access approval
- Restrict Bot functionality for users who violate these Terms or Discord's Terms of Service

If you wish to stop using the Bot, you may leave the server at any time.

## 12. Discord Terms and Guidelines

Use of the Bot is subject to Discord's:

- [Terms of Service](https://discord.com/terms)
- [Community Guidelines](https://discord.com/guidelines)
- [Developer Terms of Service](https://discord.com/developers/docs/policies-and-agreements/developer-terms-of-service)

Violations of Discord's terms may result in termination of Bot access.

## 13. Intellectual Property

The Bot, its code, and documentation are the proprietary property of Insko (see the LICENSE file). No part may be copied, distributed, or reused without explicit written permission.

## 14. Age Requirements

Users must meet Discord's minimum age requirement (13+ or higher depending on jurisdiction) to use servers with the Bot.

## 15. Governing Law

These Terms of Service shall be governed by and construed in accordance with applicable laws. Any disputes shall be resolved in accordance with Discord's dispute resolution procedures.

## 16. Contact

For questions, concerns, or to request data deletion, please contact:

- **Insko** (Server Owner): via Discord DM or server channels
- **Server Moderators**: via Discord modmail or support channels in the server

Inquiries will be answered within a reasonable timeframe.

## 17. Severability

If any provision of these Terms is found to be unenforceable or invalid, that provision will be limited or eliminated to the minimum extent necessary, and the remaining provisions will remain in full force and effect.

## 18. Acknowledgment

By using INSKO Bot, you acknowledge that you have read, understood, and agree to be bound by these Terms of Service.

---

**Made with ❤️ for Insko**
