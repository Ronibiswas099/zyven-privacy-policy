# Zyven Privacy Policy

**Effective date: November 21, 2026**

Zyven is a multipurpose Discord bot developed by Zyven Development. This policy describes information the bot may process when it is added to a Discord server, how that information is used and stored, and how to ask questions or request deletion. Features vary by server configuration.

## Information Zyven processes

Depending on the features a server enables, Zyven may process:

- **Discord and server information:** Discord user, server, channel, role, and message IDs; usernames and display names; avatars; member roles and join times; and server configuration.
- **Member and presence information:** join, leave, role, and moderation events, and member or server counts. If a server enables custom-status or vanity-role features, Zyven reads a member's custom status or presence as needed to apply or remove the configured role. Presence information is not needed for every feature.
- **Message information:** message text to recognize prefix commands and provide configured features such as AutoMod, anti-spam, autoresponders, autoreactions, leveling, and AI chat. If a server enables message event logging, edited or deleted message text and available attachment links may be sent to that server's configured log channel. Server administrators choose those channels and manage their access.
- **Feature records:** moderation actions and warnings, audit and security events, server settings, trusted-member lists, leveling records, tickets, voice or music settings, and other preferences needed for enabled features.
- **AI conversations:** when AI features are enabled and used, prompts and relevant recent conversation context are sent to Groq's API to generate replies. Zyven stores a limited recent conversation history and AI preferences so a conversation can continue with context. Users can clear saved AI conversation data using the available AI clear command. Server administrators can disable automatic AI replies.

## How information is used

Zyven uses this information to respond to commands, provide configured server features, apply administrator-selected moderation and security rules, manage roles, preserve settings and progress, operate music and AI features, troubleshoot errors, and prevent abuse.

## Storage and service providers

Zyven stores feature settings and records in SQLite on the bot operator's host. When configured, it also mirrors records to MongoDB for persistence and recovery. The operator may keep database snapshots for recovery. The bot operator and the hosting and database providers may process stored information.

Zyven communicates with Discord to receive permitted events and perform bot actions. AI prompts are sent to Groq when AI features are used. Music searches or playback requests may be sent to the Lavalink service configured by the operator. Other external services may process information needed for a feature when that feature is enabled; those services have their own terms and privacy practices.

## Retention and deletion

There is no single retention period for every kind of information. Feature settings and records may remain while needed to provide the feature or until a user, server administrator, or bot operator clears them. A deleted record may remain in a recovery snapshot until that snapshot is replaced or removed. Message logs posted to a Discord channel are controlled by that server's administrators and Discord's own features.

For questions or a deletion request about information stored by Zyven, contact the operators in the [Zyven support server](https://discord.gg/gm6pAGpNGu). Include the relevant Discord user or server ID and identify the feature or record. For message logs in a server channel, contact that server's administrators. Limited information may need to be retained for security, abuse prevention, backup recovery, or legal obligations.

## Security

The bot's SQLite database files are not encrypted by Zyven itself. Encryption may depend on the host or database provider's configuration, and the operator has not verified encryption at rest for every active storage location and backup. The operator uses measures intended to protect bot data, but no online service or data transmission can be guaranteed completely secure.

## Changes and contact

This policy may change when Zyven's features or data practices change. The current version will be available at this page. For privacy questions, contact the Zyven operators through the [support server](https://discord.gg/gm6pAGpNGu).

This notice describes Zyven's current source code and configured integrations as reviewed on November 21, 2026. Third-party providers are governed by their own policies and terms. This notice is not legal advice.
