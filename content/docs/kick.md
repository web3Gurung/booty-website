---
title: How to kick (or prune) inactive users?
type: docs
weight: 3
prev: /update_db
next: docs/folder/
---



1. `/kick_status + number` -> simulates kicking. It showcases you how many people would be kicked with their usernames and “last seen activity”. It does not remove anyone from the member list.

2. `/kick + number` : same as kick_status but removes people from your server. “number” means the number of days users have to be inactive for the bot to kick them. If a number is not given, then 90 days are assumed.


{{< callout type="info" emoji="ℹ️">}}
  Booty can kick and list people whose highest role is placed the exact same as the Booty role. (a standard in Booty V3)
{{< /callout >}}