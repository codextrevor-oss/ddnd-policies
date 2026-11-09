# DDND Privacy Policy

Last updated: November 9, 2026

Published policy repository: [DDND policies](https://github.com/codextrevor-oss/ddnd-policies)

Related document: [DDND Terms of Service](https://github.com/codextrevor-oss/ddnd-policies/blob/main/DDND-Terms-of-Service.md)

## About DDND

DDND is a privately operated Discord game bot for a small group of friends. It uses voice, text, and AI services to run shared games and maintain saved game worlds. Trevor operates DDND and can be contacted through Discord in the server where it is used. DDND is independent of Discord and OpenAI.

DDND is in development. This policy describes its intended operation as features become available. Voice transcription will not be enabled for participant use until the opt-in and opt-out protections below are implemented and verified.

## Information DDND processes

Depending on the features used, DDND processes:

- Discord user IDs and display names to identify participants and their characters.
- Server/channel IDs, voice-channel membership, permissions, and connection metadata needed to operate in the selected channels.
- Commands, confirmation selections, deliberately submitted text actions and questions, private game-master submissions and replies, and other information submitted directly to the bot, including voice opt-in status. If direct messages to the bot are enabled, their submitted game content is included.
- Microphone audio from accounts that explicitly opt in, including background sounds captured by those microphones.
- Speech transcripts, game actions, character information, dice results, summaries, and saved game state.
- Technical information such as timestamps, errors, connection events, and usage estimates needed to operate and troubleshoot the bot.

The initial version is not designed to continuously read ordinary text conversations across the server. Any future expansion of message access will be explained before it is enabled.

## Text input and private game-master messages

Planned text features let you submit game actions, dialogue, and questions without speaking or enabling voice processing. Deliberately submitted text is processed like a finalized voice transcript: DDND may send it with relevant game context to the configured AI provider, interpret it, apply game rules after any required confirmation, respond, and retain it in game history. Text does not require speech recognition, and submitting it does not opt your microphone in. Turning off voice processing does not stop processing text you deliberately submit afterward.

The planned private game-master form will identify the submission as private before you send it and provide a private acknowledgment and response. Public game submissions and their replies can be visible in the selected shared channels. Direct messages to the bot are a possible additional route; support and session-selection instructions will be explained before that route is enabled.

Private submissions and replies are intended to be hidden from other players in DDND's output. They may still be accessible to Trevor as operator, Discord, and the configured AI provider, and may be stored with access restrictions in game saves and operator-managed backups. A private reply is not automatically temporary merely because Discord displays it only to you. The same retention and deletion rules below apply to submitted text and associated replies.

A private game action may cause observable changes in the shared world. DDND will explain this before commitment and share only consequences permitted by the scenario's visibility rules or your explicit sharing choice. Other players may infer an action from those consequences. The private request and reply will not automatically be quoted in shared chat, recaps, or spoken narration.

Do not post a secret as an ordinary public channel message expecting DDND to hide it afterward. Deleting a public message cannot undo earlier views, notifications, or copies. Use the designated private submission route once it is available.

## Voice is off until you opt in

Joining a voice channel, joining a game, or being assigned a character does not authorize DDND to transcribe you.

The planned `/ddnd listen` command will show a private notice explaining the active services, transcript visibility, and retention, with a link to this policy. You must explicitly confirm for your own Discord account while in the selected active voice channel. The operator cannot opt you in on your behalf.

DDND will select audio streams by Discord user ID. Account streams without active permission will not be subscribed to for transcription, decoded or buffered for that purpose, sent to AI providers, or retained by DDND. Discord and the voice library may still deliver and inspect voice packets and connection metadata to route streams; this is not a promise that no network packets from other members reach the bot.

You can remain in the channel and hear narration without opting in. Use `/ddnd privacy` to review the notice and your status, and `/ddnd unlisten` to withdraw permission.

Permission ends when you opt out, leave or move out of the selected voice channel, the session ends, or the bot disconnects or restarts. Fresh confirmation is also required after a change to the processing providers or data-handling notice. Loading a saved game does not restore permission to listen.

Opting out stops new processing of your stream, discards pending audio and uncommitted transcript buffers, and cancels associated pending work where supported. Late results will not be published or applied to the game. Information already transmitted to a provider cannot be recalled. Previously saved or published information is handled through a separate deletion request.

Opt-in applies to your microphone stream. It cannot distinguish you from someone else speaking near your microphone or audio played through your speakers. Side conversations within an opted-in stream may still be transcribed even when not treated as game actions. Avoid sensitive information and use a headset where practical.

DDND temporarily buffers opted-in audio for recognition. Raw audio recordings are not retained by default. Diagnostic recording requires separate advance notice and agreement from the people being recorded, including its purpose and retention period. Transcripts may be retained even when raw audio is not.

## How information is used and shared

DDND uses information to identify speakers, interpret requests, generate narration, apply rules, save and resume games, diagnose problems, manage costs, and protect access. DDND does not sell personal information, use it for advertising, or use participant content to train its own AI models.

Discord carries interactions, audio, messages, and narration. When OpenAI features are enabled, opted-in audio is sent to OpenAI for transcription; relevant transcripts, deliberately submitted public or private text, game context, and requests are sent for response generation; public narration text may be sent for speech synthesis. Private game-master replies will stay in private text rather than being played into shared voice. Providers process information on their systems under their applicable terms, policies, and service settings. DDND's local retention settings do not determine provider retention.

Trevor can access locally stored data while operating and maintaining DDND. Messages, transcripts, rolls, and narration posted to Discord can be seen or heard by people with access to the relevant channels, including people who have not opted into voice processing. Participants may retain their own copies.

DDND does not otherwise share participant information except when directed by the participant or required by law. Provider changes will be disclosed before participant data is sent to them.

Provider policies:

- Discord: https://discord.com/privacy
- OpenAI: https://openai.com/policies/privacy-policy/

## Storage and retention

DDND stores its own saved games, retained transcripts, submitted text and replies (including private game-master exchanges), configuration, and diagnostic information on the operator's computer and any operator-managed backups. Active voice permission is temporary and is not restored from saved games.

Saved games and associated information are retained while needed to continue the game. Diagnostic information and test reports are retained only while needed for their stated purpose. Information is deleted promptly when no longer needed, when DDND stops operating, or following a valid deletion request, unless retention is required by law.

Deletion requests also address operator-managed backups so deleted information is not restored into active use. Messages stored by Discord and information held by providers remain subject to those services' controls and retention practices.

## Your choices and requests

You may stop participating or withdraw voice permission at any time. To ask what information is retained about you, request a correction, or request deletion, contact Trevor through Discord in the server where DDND is used. If direct messages are unavailable, ask a server administrator to connect you with the operator. Do not post sensitive information in a public request.

Identify your Discord account and, if possible, the affected game or session. Never provide your password or account credentials. Trevor will respond and handle requests promptly. Deletion may require removing or revising associated transcripts, summaries, or portions of a shared saved game.

Opting out, leaving voice, or leaving the server does not automatically delete existing data. DDND cannot guarantee removal of copies independently retained by other participants. Requests about information independently held by Discord or another provider may also need to be submitted to that service.

## Security and changes

Protective measures will include restricted access, encrypted storage, and keeping credentials out of source code, public documents, and game exports. No system guarantees absolute security.

This policy will be updated as information-handling practices change. Material changes will be announced in the server before affected processing begins. Changes to the voice-processing notice require fresh opt-in. The date above identifies the latest revision.

## Contact

Contact Trevor, the DDND operator, through Discord in the server where you use the bot. If necessary, ask a server administrator to connect you with the operator.
