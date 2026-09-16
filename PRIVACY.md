# music — Privacy Policy

Effective date: September 17, 2026

This policy describes the Discord application **music**, application ID **1549821395603554455**, operated by **Devesh Shrivas (Deveshshrivas on GitHub)**.

## Information processed and why

- **Discord interaction and connection information:** Discord provides user and server identifiers, channel information, permissions, voice-channel membership, and command inputs. The bot uses this information to respond to commands, connect to the correct voice channel, maintain separate server queues, and enforce access controls. The Discord library may temporarily cache server and member information needed for its connection.
- **Playback information:** YouTube links submitted to commands, track titles and identifiers, temporary audio-stream URLs, queue position, and volume settings are processed to prepare and play requested audio. Track titles and queue details may appear in bot messages visible to people with access to the text channel.
- **Operational diagnostics:** Connection events, errors, extraction warnings, track identifiers and technical details may appear in application or hosting logs. Some third-party diagnostic messages may include media URLs or connection metadata. Logs are used to troubleshoot failures and operate the service.
- **Support requests:** If you open a GitHub issue, your GitHub account name and the information you submit are visible in the public issue and used to handle your request.

The bot has no feature for recording users' voice audio, building advertising profiles, or selling personal information. It does not intentionally collect ordinary message content; it uses slash commands and does not enable Discord's privileged Message Content intent. It has no application database or saved listening-history feature.

## Service providers and disclosure

**Discord** handles commands, bot messages, server information, and voice delivery. **Railway** hosts the running bot and its operational logs. **YouTube and its media infrastructure** receive requests for the links you submit, including the hosting server's network information; the bot does not intentionally attach your Discord identity to those requests. **GitHub** hosts these policy pages and support issues and processes visits and support activity under its own policies.

These providers process information under their own terms and privacy policies: [Discord](https://discord.com/privacy), [Railway](https://railway.com/legal/privacy), [Google/YouTube](https://policies.google.com/privacy), and [GitHub](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). Information may be processed outside your country depending on their infrastructure. The operator may also disclose information where required by law or necessary to investigate abuse and protect the service.

## Retention

Playback queues, prepared stream references, and volume settings are held in process memory. `/stop` clears the active queue and its stream cache; process restarts clear in-memory session state. Some Discord library caches and server identifiers can remain in memory until the process restarts. The current bot does not deliberately save complete songs to disk.

Bot messages and your command interactions remain subject to Discord's retention and deletion controls; `/stop` does not delete text-channel messages. Hosting diagnostics follow the host's configured log retention, which is separate from the playback queue. No fixed hosting-log deletion period is represented here. Public support issues remain on GitHub until removed, subject to GitHub's own retention rules.

## Your choices and requests

Use `/stop` from the bot's voice channel to clear the active playback queue. Server administrators can remove the bot to prevent further service in their server and can manage bot messages using Discord's controls.

To request access, correction, or deletion of information under the operator's control, [open a privacy support request](https://github.com/Deveshshrivas/music-bot-policies/issues/new). State the type of request without posting personal identifiers, credentials, private URLs, or sensitive details. Issues are public; ask for a private follow-up if identifying information is needed. The operator may need to verify that a request relates to you before acting. Requests concerning data retained independently by Discord, GitHub, or another provider may also need to be directed to that provider.

## Security and children

Access to bot credentials and hosting administration is intended for the operator. Do not submit passwords or tokens to the bot or support issues. No system can guarantee complete security. The service is intended only for people eligible to use Discord under its applicable age requirements.

## Changes

Updates to this policy will be posted here with a revised effective date. Contact the operator through the support link above with questions about the bot's handling of information.
