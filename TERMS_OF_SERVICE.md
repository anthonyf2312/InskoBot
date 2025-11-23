# Terms of Service

**Last Updated:** November 2025

## 1. Acceptance of Terms

By using INSKO Bot ("the Bot") in Insko's Discord server, you agree to be bound by these Terms of Service. If you do not agree to these terms, please leave the server or do not interact with the Bot.

**Note:** This is a private bot developed exclusively for Insko's Discord community and is not available for public use or invitation to other servers.

## 2. Description of Service

INSKO Bot is a Discord bot that provides the following services:

- **YouTube Integration**: Real-time notifications for YouTube live streams and video uploads
- **Welcome & Farewell Messages**: Automated greeting and farewell messages for server members
- **Auto-Moderation**: Automated spam detection, link filtering, and content moderation with AI-powered flagging
- **Logging System**: Message edit/deletion tracking, member event logging, and moderation action logging
- **Starboard**: Community-curated message highlighting system
- **Server Statistics**: Live server statistics displayed in voice channels
- **Report System**: User-initiated content reporting functionality

## 3. Server Administrator Responsibilities

The server administrators and moderators of Insko's Discord server agree to:

- Configure the Bot in accordance with Discord's Terms of Service and Community Guidelines
- Not use the Bot to harass, abuse, or harm other users
- Not use the Bot to collect, store, or distribute personal information without consent
- Review and moderate any AI-flagged content in a timely and fair manner
- Ensure that any logged data is used only for legitimate moderation purposes
- Handle user data responsibly and in accordance with this Privacy Policy

## 4. User Responsibilities

By being a member of Insko's Discord server and interacting with the Bot, you agree to:

- Comply with Discord's Terms of Service and Community Guidelines
- Accept that your messages may be logged if the server has enabled logging features
- Accept that your messages may be analyzed by AI if they contain flagged words
- Not attempt to exploit, damage, or interfere with the Bot's functionality
- Not use the report system to submit false or malicious reports

## 5. Data Collection and Usage

The Bot collects and stores the following data:

### Server Configuration Data

- Server ID
- Channel IDs (for welcomes, farewells, logs, starboard, notifications, etc.)
- Role IDs (for reports and mentions)
- Custom messages and settings configured by server administrators

### Message Data (when logging is enabled)

- Message content (for edit/deletion logs)
- Message IDs
- Author IDs
- Channel IDs
- Timestamps
- Attachments (URLs only, not the files themselves)

### Starboard Data

- Message ID, content, and author ID of starred messages
- Star counts
- Starboard message IDs

### Moderation Data (temporary, in-memory only)

- Message IDs of automod-deleted messages (automatically cleared)
- Recent message history for spam detection (temporary, not stored in database)
- Channel update timestamps for rate limiting (temporary, in-memory only)

### AI Analysis

- Messages containing flagged words are sent to Google Gemini AI for context analysis
- Only the message content is sent; no user IDs or personal information is included in AI requests
- AI responses are logged to the configured log channel for staff review

All data is stored securely in a MongoDB database and is only accessible to the Bot and its operator.

## 6. Data Retention

- **Server Configuration**: Retained indefinitely or until modified by server administrators
- **Message Logs**: Retained indefinitely or until manually deleted by server administrators
- **Starboard Data**: Retained indefinitely or until the starboard message is removed
- **Temporary Data**: Automod tracking data and rate limit data are stored in-memory only and are cleared when the Bot restarts

Users who leave Insko's Discord server may request deletion of their logged data by contacting the server administrators.

## 7. Third-Party Services

The Bot integrates with the following third-party services:

- **YouTube Data API v3**: For fetching video information and managing channel subscriptions
- **Google Gemini AI**: For analyzing message context when flagged words are detected
- **PubSubHubbub**: For receiving real-time YouTube notifications
- **MongoDB Atlas**: For database hosting (if applicable)

Your data may be processed by these services according to their respective privacy policies. We do not share any personally identifiable information with these services beyond what is necessary for the Bot's functionality.

## 8. AI-Powered Moderation

The Bot uses Google Gemini AI to analyze messages containing potentially problematic words. By using the Bot:

- You acknowledge that flagged messages may be sent to Google's AI service for analysis
- The AI provides context and recommendations, but all moderation decisions are made by human moderators
- The AI does not store or train on your server's messages (according to Google's API terms)
- AI flagging can be disabled by not configuring a log channel or by removing flagged words from the word list

## 9. Limitation of Liability

The Bot is provided "as is" without any warranties. The Bot operator is not liable for:

- Any damages resulting from the use or inability to use the Bot
- Data loss or corruption
- Missed notifications or delayed responses
- False positives or negatives from AI moderation
- Actions taken by server moderators based on Bot-provided information
- Downtime, errors, or bugs in the Bot's functionality

## 10. Service Availability

We strive to maintain 99% uptime, but:

- The Bot may be temporarily unavailable for maintenance or updates
- Features may be added, modified, or removed at any time
- We reserve the right to terminate service for any server or user that violates these terms

## 11. Modifications to Terms

We reserve the right to modify these Terms of Service at any time. Changes will be effective immediately upon posting. Continued use of the Bot after changes constitutes acceptance of the modified terms.

## 12. Termination and User Removal

We reserve the right to:

- Terminate Bot service at any time, for any reason
- Restrict Bot functionality for users who violate these Terms or Discord's Terms of Service

Users who violate these Terms, Discord's Terms of Service, or server rules may be:

- Warned by the Bot's auto-moderation system
- Timed out, kicked, or banned from the server
- Have their access to Bot features restricted

If you wish to stop using the Bot, you may leave Insko's Discord server at any time.

## 13. Discord Terms and Guidelines

Use of the Bot is subject to Discord's:

- [Terms of Service](https://discord.com/terms)
- [Community Guidelines](https://discord.com/guidelines)
- [Developer Terms of Service](https://discord.com/developers/docs/policies-and-agreements/developer-terms-of-service)

Violations of Discord's terms may result in termination of Bot access.

## 14. Intellectual Property

The Bot, its code, and documentation are provided for use as-is. The Bot is open-source under the MIT License (see LICENSE file).

## 15. Age Requirements

Users must meet Discord's minimum age requirement (13+ or higher depending on jurisdiction) to use servers with the Bot.

## 16. Governing Law

These Terms of Service shall be governed by and construed in accordance with applicable laws. Any disputes shall be resolved in accordance with Discord's dispute resolution procedures.

## 17. Contact

For questions, concerns, or to request data deletion, please contact:

- **Insko** (Server Owner): via Discord DM or server channels
- **Server Moderators**: via Discord modmail or support channels in the server

We will respond to inquiries within a reasonable timeframe.

## 18. Severability

If any provision of these Terms is found to be unenforceable or invalid, that provision will be limited or eliminated to the minimum extent necessary, and the remaining provisions will remain in full force and effect.

## 19. Acknowledgment

By using INSKO Bot, you acknowledge that you have read, understood, and agree to be bound by these Terms of Service.

---

**Made with ❤️ for Discord Communities**
