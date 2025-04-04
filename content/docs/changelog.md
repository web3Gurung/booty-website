---
title: Changelog
type: docs
weight: 7
prev: /developer
next: /changelog
---

## changelog from Booty V3:

- Mobile optimization: messages are formatted differently when the slash command user is on a mobile device when writing the command (this only works when a user is not invisible).

- Booty is now verified for the privileged guild presence intent. This allows him to see user status and Discord client type being used (app/mobile/browser). However, he doesn't store or display this info to users, only to adjust displayed messages.
The content sent by Booty was spell-checked and edited by native speakers, resulting in polished and error-free content.

- The help command now includes information about /diagnose.

- The /diagnose command now works correctly with forum channels and their permission settings. This wasn't the case in V2 because the permissions for sending messages are named differently for forum channels, meaning it displayed missing permissions for those even when working correctly.

- The code was optimized and reorganized. Database queries are now handled with a connection pool, making it more responsive with decreased delay and increased reliability.
