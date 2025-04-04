---
title: Note about /update_db
type: docs
weight: 2
prev: /quickstart
next: /kick
---


Use the `/update_db` command as a backup solution. When Booty is invited to a server, he will automatically record the events (activities by server members) and try to include the server in its database.


When should you use this command?

Lets assume that some non-talking lurker joined while the bot was offline for maintenance. In this situation, `update_db` can fix it and record that lurker's presens.