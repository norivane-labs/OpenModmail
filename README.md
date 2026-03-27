# OpenModmail
![OpenModmail Banner](.github/OpenModmail-readme.png)

<div align="center">

  [![Discord Invite](https://img.shields.io/badge/discord_invite-OpenModmail-%235865F2)](https://labs.norivane.de/openmodmail/invite)
  [![License](https://img.shields.io/badge/license-GPL--3.0-red)](https://opensource.org/license/gpl-3.0)

  <span>[Request feature](https://github.com/norivane-labs/OpenModmail/issues/new?title=%5BFeature%5D&labels=feature)</span> <span>·</span> <span>[Report bug](https://github.com/norivane-labs/OpenModmail/issues/new?title=%5BBug%5D&labels=bug)</span>
  
</div>

A open-source and self-hosted Modmail bot for Discord. It allows your community to contact your team privately through DM'ing your bot, ensuring organized and efficient communication. Messages from users are forwarded directly to your staff.

## Installation

### 🥤 Self-hosted bot
Requirements:

- a running server
  - ✅ Major Linux distros such as Debian, Ubuntu and ArchLinux..
  - ✅ A server running Node.js
  - ❌ FreeBSD / NetBSD / OpenBSD
- [Node.js](https://nodejs.org/en/download/) >= ??
- wget
- [pm2](https://pm2.keymetrics.io/) (optional, runs OpenModmail in the background)

You can download the bot, when we are ready for open-source release. For now, you can use the official **OpenModmail App** on Discord.

### 🌪️ Discord App
Our official discord app is now live 🎉

Requirements:

- a discord server
  - ✅ With the [Discord App](https://discord.com/discovery/applications/1486728345826758781)

You can set the category with `/modmail-setcategory` and select your category where the modmail tickets will be created.
You also need to set the staff roles with `/modmail-setstaff` that can see / answer the modmail tickets.
