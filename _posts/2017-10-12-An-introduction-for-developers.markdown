---
layout: post
title: An introduction for developers
source: https://core.telegram.org/bots
category: HackerNews
description: SiteLog - Bots are third-party applications that run inside Telegram. Users can interact with bots by sending them messages, commands…
numwords: 2881
---

Bots are third-party applications that run inside Telegram. Users can interact with bots by sending them messages, commands and inline requests. You control your bots using HTTPS requests to our bot API.

To name just a few things, you could use bots to:

At the core, Telegram Bots are special accounts that do not require an additional phone number to set up. Users can interact with bots in two ways:

* Send messages and commands to bots by opening a chat with them or by adding them to groups. This is useful for chat bots or news bots like the official TechCrunch bot.

* Send requests directly from the input field by typing the bot's @username and a query. This allows sending content from inline bots directly into any chat, group or channel.

Messages, commands and requests sent by users are passed to the software running on your servers. Our intermediary server handles all encryption and communication with the Telegram API for you. You communicate with this server via a simple HTTPS-i...

![](https://core.telegram.org/file/811140663/1/uHVzwsRJz3Y/a499733c59840694ca)
<!--description-->