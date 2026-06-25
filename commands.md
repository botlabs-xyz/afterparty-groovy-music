---
layout: default
title: Commands
description: Slash command reference for Afterparty Groovy Music.
permalink: /commands/
---

## Commands

| Command | Description | Required Permission | Example Usage |
| --- | --- | --- | --- |
| `/play` | Play music from a search term or direct URL. | Send Messages, Use Application Commands | `/play never gonna give you up` |
| `/search` | Search tracks before adding to queue. | Send Messages, Use Application Commands | `/search daft punk harder better` |
| `/pause` | Pause the current song. | Send Messages, Use Application Commands | `/pause` |
| `/resume` | Resume paused playback. | Send Messages, Use Application Commands | `/resume` |
| `/skip` | Skip the current song. | Send Messages, Use Application Commands | `/skip` |
| `/previous` | Go back to the previous track. | Send Messages, Use Application Commands | `/previous` |
| `/replay` | Restart the current song from the beginning. | Send Messages, Use Application Commands | `/replay` |
| `/stop` | Stop playback and end the active session. | Send Messages, Use Application Commands | `/stop` |
| `/join` | Have the bot join your voice channel. | Connect, View Channels, Use Application Commands | `/join` |
| `/disconnect` | Have the bot leave voice chat. | Connect, View Channels, Use Application Commands | `/disconnect` |
| `/queue` | Show the current queue and playback status. | Send Messages, Use Application Commands | `/queue` |
| `/move` | Move a queued track to a new position. | Send Messages, Use Application Commands | `/move from:5 to:2` |
| `/remove` | Remove a song from queue. | Send Messages, Use Application Commands | `/remove position:3` |
| `/shuffle` | Shuffle the current queue order. | Send Messages, Use Application Commands | `/shuffle` |
| `/loop` | Set repeat mode for track or queue. | Send Messages, Use Application Commands | `/loop mode:queue` |
| `/clear` | Clear upcoming songs in queue. | Send Messages, Use Application Commands | `/clear` |
| `/volume` | Change playback volume. | Send Messages, Use Application Commands | `/volume level:50` |
| `/seek` | Jump to a time in the current track. | Send Messages, Use Application Commands | `/seek time:01:30` |
| `/filters` | Apply audio filter presets. | Send Messages, Use Application Commands | `/filters preset:bassboost` |
| `/equalizers` | Apply equalizer profile settings. | Send Messages, Use Application Commands | `/equalizers preset:rock` |
| `/autoplay` | Toggle or configure automatic follow-up playback. | Send Messages, Use Application Commands | `/autoplay mode:on` |
| `/247` | Keep the player connected in supported setups. | Connect, Speak, Use Application Commands | `/247 mode:on` |
| `/help` | Show help and command tips. | Send Messages, Use Application Commands | `/help` |
| `/support` | Get support links. | Send Messages, Use Application Commands | `/support` |
| `/invite` | Get the invite link. | Send Messages, Use Application Commands | `/invite` |

## Tips

- If commands are missing, wait a minute and reopen Discord.
- If music is silent, check **Server Settings ? Roles ? Afterparty Groovy Music ? Permissions** for **Connect** and **Speak**.
- If a command fails in one channel, test the same command in another text channel to check channel-level overrides.
