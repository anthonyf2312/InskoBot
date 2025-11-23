# Privacy Policy

**Last Updated:** November 2025

## 1. Introduction

This Privacy Policy explains how INSKO Bot ("the Bot", "we", "us") collects, uses, stores, and protects information when you are a member of Insko's Discord server.

**Note:** This is a private bot developed exclusively for Insko's Discord community and is not available for public use or invitation to other servers.

By being a member of Insko's Discord server and interacting with the Bot, you consent to the data practices described in this policy.

## 2. Information We Collect

### 2.1 Automatically Collected Information

The Bot automatically collects:

- **Server ID**: Unique identifier for Insko's Discord server
- **Server Name**: Name of the Discord server (for display purposes only)
- **Channel IDs**: IDs of channels where the Bot is configured to operate
- **Role IDs**: IDs of roles mentioned in Bot configurations
- **User IDs**: Discord user IDs for logging and moderation purposes

### 2.2 Configuration Data

Server administrators configure the Bot, which stores:

- Welcome and farewell message templates
- Auto-moderation settings (spam thresholds, link filters, action types)
- Log channel preferences and enabled log types
- Starboard settings (emoji, threshold, channel)
- Server statistics channel IDs
- YouTube notification channel settings
- Report system configuration

### 2.3 Message Data (Optional - Only if Logging is Enabled)

If server administrators enable logging features, the Bot stores:

- **Message Content**: Original and edited message content for edit/deletion logs
- **Message IDs**: Unique identifiers for messages
- **Author IDs**: User IDs of message authors
- **Channel IDs**: IDs of channels where messages were sent
- **Timestamps**: When messages were created, edited, or deleted
- **Attachment URLs**: Links to images and files (not the files themselves)

**Note**: The Bot does NOT log messages in channels where logging is disabled. Logging is opt-in and must be explicitly enabled by server administrators.

### 2.4 Starboard Data

When users react with star emojis to messages:

- Message ID, content, and author ID
- Number of stars received
- Starboard message ID (the message posted in the starboard channel)
- Timestamp when the message was first starred

### 2.5 Moderation Data (Temporary)

For auto-moderation functionality:

- **Recent Message History**: Temporarily stored in memory (RAM) to detect spam patterns; automatically cleared after a few minutes
- **Automod Deleted Messages**: Message IDs stored temporarily in memory to prevent duplicate logs; cleared on Bot restart
- **Channel Update Times**: Timestamps for rate limiting; stored in memory only

**Important**: This data is NOT stored in the database and is automatically cleared when the Bot restarts.

### 2.6 AI Analysis Data

When a message contains a flagged word from the configured word list:

- **Message Content Only**: The text content of the message is sent to Google Gemini AI for context analysis
- **NO Personal Information**: User IDs, usernames, server names, or any identifying information is NOT sent to the AI
- **Analysis Results**: The AI's context analysis is logged to your configured log channel for moderator review

The AI does not store or retain your messages according to Google's API terms for non-training usage.

## 3. How We Use Your Information

### 3.1 Core Functionality

We use collected data to:

- Provide Bot functionality (welcome messages, auto-moderation, logging, etc.)
- Respond to user commands and interactions
- Display server statistics in voice channels
- Send YouTube notifications when configured
- Highlight community-favorite messages in starboard

### 3.2 Moderation and Safety

We use data to:

- Detect and prevent spam, abuse, and rule violations
- Log moderation actions for accountability and transparency
- Analyze flagged content with AI to assist moderators
- Track message edits and deletions for transparency

### 3.3 Service Improvement

We may use aggregated, anonymized data to:

- Monitor Bot performance and uptime
- Identify and fix bugs
- Improve features and functionality

We do NOT sell, rent, or share your data with third parties for marketing purposes.

## 4. Data Storage and Security

### 4.1 Database Storage

- All persistent data is stored in a secure MongoDB database
- Access to the database is restricted to authorized personnel only
- Database connections use encryption and secure credentials

### 4.2 Data Location

- Database may be hosted on MongoDB Atlas or a private server
- Data is stored in compliance with applicable data protection regulations

### 4.3 Security Measures

We implement reasonable security measures including:

- Encrypted database connections
- Secure credential storage (environment variables)
- Regular security updates and patches
- Access controls and authentication

However, no method of transmission or storage is 100% secure. We cannot guarantee absolute security.

## 5. Third-Party Services

The Bot integrates with third-party services that may collect and process data:

### 5.1 Discord

- All Discord-related data is subject to [Discord's Privacy Policy](https://discord.com/privacy)
- The Bot operates within Discord's infrastructure and uses Discord's API

### 5.2 Google Gemini AI

- Flagged message content is sent to Google's Gemini AI for analysis
- Google's Privacy Policy applies: [Google Privacy Policy](https://policies.google.com/privacy)
- According to Google's API terms, data sent for analysis is not used for training models
- Only message content is sent; no personal identifiers are included

### 5.3 YouTube Data API v3

- YouTube channel IDs and video information are fetched via YouTube's API
- Subject to [Google's Privacy Policy](https://policies.google.com/privacy)
- Only public YouTube data is accessed (no personal YouTube account data)

### 5.4 PubSubHubbub

- Used to receive real-time push notifications for YouTube uploads
- Only YouTube channel subscription data is shared
- Subject to PubSubHubbub's terms and the hub provider's policies

## 6. Data Retention

### 6.1 Retention Periods

- **Server Configuration**: Retained indefinitely or until manually modified by server administrators
- **Message Logs**: Retained indefinitely until manually deleted by server administrators
- **Starboard Messages**: Retained indefinitely or until manually removed
- **Temporary Data**: Cleared automatically on Bot restart (RAM-only storage)

### 6.2 Data Deletion

You can request data deletion by:

1. **Leave the Server**: If you leave Insko's Discord server, you may request deletion of your logged data
2. **Contact Server Administrators**: Request deletion of specific data associated with your User ID
3. **Contact Insko**: Directly request data deletion from the server owner

Data deletion requests will be processed within 30 days.

## 7. Your Rights and Choices

### 7.1 Server Administrator Rights

Server administrators have the right to:

- **Access**: View all stored configuration data via Bot commands
- **Modify**: Update or change Bot settings at any time
- **Delete**: Remove specific logged data or clear configurations
- **Opt-Out**: Disable specific features (e.g., logging, AI flagging)

### 7.2 User Rights

Individual Discord users have the right to:

- **Data Portability**: Request a copy of data associated with your User ID
- **Erasure**: Request deletion of your data from the database
- **Objection**: Object to AI analysis by asking server admins to disable the feature

### 7.3 Exercising Your Rights

To exercise these rights, contact:

- **Insko** (Server Owner): via Discord DM or server channels
- **Server Moderators**: via Discord modmail or support channels in the server

## 8. Children's Privacy

The Bot is intended for use in Discord servers. Discord requires users to be at least 13 years old (or older depending on jurisdiction). We do not knowingly collect personal information from children under 13.

If we become aware that we have collected data from a child under 13, we will take steps to delete that information promptly.

## 9. International Users

Insko's Discord server may have members from any country. If you are located outside the country where the database is hosted:

- Your data may be transferred to and processed in a different country
- By being a member of the server, you consent to such transfer and processing
- We will take reasonable steps to ensure data is treated securely and in accordance with this Privacy Policy

## 10. Data Breach Notification

In the event of a data breach that affects personal information:

- We will notify server administrators and affected users within 72 hours of discovery
- We will provide information about the nature of the breach and steps being taken
- We will cooperate with authorities as required by law
- Notifications will be posted in the server and/or sent via Discord DMs

## 11. Analytics and Tracking

### 11.1 No User Tracking

The Bot does NOT use:

- Cookies
- Web beacons or tracking pixels
- IP address tracking
- Cross-server user behavior tracking
- Third-party analytics services (e.g., Google Analytics)

### 11.2 Internal Metrics Only

We only track:

- Bot uptime and error logs (for debugging)
- Command usage statistics (aggregated, not per-user)
- API quota usage (for rate limiting)

## 12. AI and Automated Decision Making

### 12.1 AI Usage Transparency

The Bot uses Google Gemini AI for:

- **Content Moderation**: Analyzing flagged messages to provide context to human moderators
- **Not for Automated Actions**: AI does not automatically ban, kick, or timeout users
- **Human Review Required**: All AI findings are sent to human moderators for review and action

### 12.2 AI Limitations

- AI may produce false positives or false negatives
- AI analysis is advisory only; moderators make final decisions
- AI does not replace human judgment

## 13. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Changes will be effective immediately upon posting. We encourage you to review this policy periodically.

Material changes will be communicated through:

- Updates to this document (with updated "Last Updated" date)
- Announcements in Insko's Discord server

Continued membership in the server and use of the Bot after changes constitutes acceptance of the updated policy.

## 14. Legal Basis for Processing (GDPR Compliance)

For users in the European Economic Area (EEA), our legal basis for processing personal data is:

- **Consent**: By being a member of the server and using the Bot, you consent to data collection and processing
- **Legitimate Interests**: Processing necessary to provide Bot functionality, security, and service improvement
- **Legal Obligation**: Compliance with applicable laws and regulations

You may withdraw consent at any time by leaving Insko's Discord server and requesting data deletion.

## 15. California Privacy Rights (CCPA)

If you are a California resident, you have the right to:

- Know what personal information is collected
- Know whether your personal information is sold or disclosed (we do NOT sell data)
- Request deletion of your personal information
- Opt-out of the sale of personal information (not applicable - we don't sell data)
- Non-discrimination for exercising your rights

To exercise these rights, contact Insko (server owner) or the server moderators.

## 16. Contact Information

For questions, concerns, or data requests regarding this Privacy Policy, please contact:

- **Insko** (Server Owner): via Discord DM or server channels
- **Server Moderators**: via Discord modmail or support channels in the server

We will respond to privacy inquiries within 30 days.

## 17. Acceptance of This Policy

By using INSKO Bot, you acknowledge that you have read, understood, and agree to be bound by this Privacy Policy.

---

**Made with ❤️ for Discord Communities**

**Note**: This Privacy Policy is designed to be transparent and comprehensive. We are committed to protecting your privacy and handling your data responsibly.
