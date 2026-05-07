---
layout: default
title: Troubleshooting
description: Common Afterparty Groovy Music issues and fixes.
permalink: /troubleshooting/
---

## Troubleshooting

### Bot does not join voice channel

1. Open **Server Settings ? Roles ? Afterparty Groovy Music**.
2. Make sure **View Channels** and **Connect** are enabled.
3. Open the specific voice channel settings and confirm the bot role is still allowed there.
4. Join the voice channel yourself, then run `/join` and `/play` again.

### Bot joins but no audio plays

1. Open **Server Settings ? Roles ? Afterparty Groovy Music** and enable **Speak**.
2. In the voice channel user list, check that the bot is not server-muted.
3. Run `/stop` and then `/play` to start a fresh playback session.
4. Try a different song name or direct link in case the original source is unavailable.

### Search commands fail

1. Try a more specific search (song + artist).
2. Test `/play` with a direct track URL.
3. If direct URLs work but search does not, it is usually a source lookup issue and not a server permission issue.

### Queue behaves unexpectedly

1. Run `/queue` first to confirm the current order.
2. If the list looks incorrect, run `/clear` once.
3. Add 1 to 2 tracks and test `/skip`, `/remove`, and `/move` again.
4. This helps confirm whether the issue is with one old queue item or the full queue.

### Premium sources unavailable

1. Test with a normal non-premium song source first.
2. If regular playback works, your server or account likely does not have premium source access enabled yet.
3. Use the Support Server for access checks.

## What to send support

- server name
- command used
- what you expected
- what happened instead
- screenshot of roles or permissions if relevant

Support: [Support Server](https://discord.gg/BusuZp2G8w)