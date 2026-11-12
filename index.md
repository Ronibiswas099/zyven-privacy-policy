# Zyven Privacy Policy

**Effective date: November 12, 2026**  
**Maintained by: Soulhuiyaar**

Zyven is a Discord bot maintained by Soulhuiyaar. This policy explains what data Zyven accesses, why it uses it, where it may be stored or sent, how long it is kept, and how to request deletion.

## Data Zyven accesses

Depending on server features, Zyven may access or store:

- Discord user, server, channel, role, and message IDs needed for commands and features. Display names may appear in replies and logs.
- Server configuration, including command prefix, selected channels and roles, welcome settings, moderation and security settings, and feature preferences.
- Moderation and security records such as warnings, timed actions, role or channel recovery data, and configured event logs.
- Message text to recognize prefix commands and run enabled AutoMod, anti-spam, link filters, or autoresponders. Zyven does not keep a general archive of all server messages. If event logging is configured, edited or deleted message content may be posted to the selected Discord log channel.
- Current presence or activity for status commands, presence counts, and optional custom-status role features. This is not saved as a presence history.
- AI prompts and limited conversation context only when an administrator enables the AI feature or a user invokes an AI command. Users can clear saved context with the ?ai clear command in the relevant server and channel.

Zyven does not need Discord passwords, payment card details, or home addresses.

## Use and sharing

Zyven uses data to respond to commands, apply administrator-configured features, protect and moderate servers, maintain settings and records, and troubleshoot reliability or abuse. Message content is not used by Zyven to train or fine-tune AI models. When AI is used, the relevant prompt and limited context are sent to Groq. Groq says prompts and outputs are not retained by default, but may be temporarily logged for reliability or abuse monitoring for up to 30 days unless Zero Data Retention is enabled. See [Groq data retention](https://console.groq.com/docs/your-data).

## Storage and providers

Zyven uses local SQLite storage. A deployment may also mirror data to MongoDB for persistence and recovery, and may keep compressed database snapshots there. Deleted data may remain in a snapshot until it is replaced. Discord processes data under its own terms and privacy policy. Groq receives AI prompts only when AI is used. Optional music or other integrations may receive the relevant search query or URL.

## Retention and deletion

There is no single automatic expiry period for every record. Data is kept while needed for the feature or server configuration that created it. Warning records remain until removed by a moderator; AI context remains until cleared; settings remain until reset or removed. Backups may retain deleted records until the next snapshot replaces them.

To clear AI context, run ?ai clear in the same server and channel. To request access to or deletion of other Zyven data, contact **Soulhuiyaar** in the [Zyven Support Server](https://discord.gg/gm6pAGpNGu). Include the relevant server ID, your Discord user ID, and the data type. Requests will be handled as promptly as storage and backups allow. A server administrator may need to remove server settings or moderation records. To stop using Zyven, ask an administrator to remove the bot. Presence features have no individual opt-out; an administrator can disable the feature or remove the bot.

## Security

Zyven limits access to data needed by its features and uses administrative and technical safeguards. The source uses standard SQLite and does not itself encrypt database files. Encryption at rest depends on hosting and database configuration. **The maintainer has not verified encryption at rest for every active storage location and backup.** This policy does not claim that the current deployment is encrypted at rest.

For a suspected unauthorized access or disclosure, contact Soulhuiyaar through the [Zyven Support Server](https://discord.gg/gm6pAGpNGu).

## Changes and contact

This policy may change when Zyven's features, storage, or providers change. The current version remains available here. For privacy questions or requests, contact Soulhuiyaar through the [Zyven Support Server](https://discord.gg/gm6pAGpNGu).

Zyven is independent and is not affiliated with or endorsed by Discord or Groq.
