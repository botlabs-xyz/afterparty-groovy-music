---
layout: default
title: Troubleshooting
description: Common Afterparty Groovy Music issues and fixes.
permalink: /troubleshooting/
---

## Troubleshooting

### Bot does not join voice channel

- Confirm **Connect** permission in that voice channel.
- Confirm channel is visible to bot role.
- Retry `/join` then `/play`.

### Bot joins but no audio plays

- Confirm **Speak** permission.
- Check server mute/deafen status for bot.
- Try `/stop` then `/play` again.

### Search commands fail

- Retry with more specific query (artist + track).
- Test a direct URL in `/play` to isolate search issue.

### Queue behaves unexpectedly

- Check `/queue` state after each control command.
- Clear queue with `/clear` and retest from clean state.

### Premium sources unavailable

- Confirm entitlement/deployment access for premium sources.
- Run non-premium playback command as baseline control test.

## What to send support

- server name
- command used
- expected result
- actual result
- screenshot of role/channel permissions if relevant

Support: [Support Server](https://discord.gg/BusuZp2G8w)
