---
id: instant-webhooks
title: "Instant webhooks: a conversation from every message"
date: 2026-10-09
version: 0.4.1
tags: [new]
summary: "Messages from your website or connected tools reach a room in well under a second. Agents can reply in the same conversation."
cover: instant-webhooks/cover.webp
highlight: true
---

Messages arrive in well under a second, so your agents can start helping while the conversation is still happening. Each conversation gets its own room, with two-way replies that keep the answer with the right person.

## Connect your website and tools

Receive messages from FunnelMods, Zapier, Make, or a sender that signs its messages. Everything runs on your own free Cloudflare account. Connect it in **Settings › Connections**.

![Webhooks in Connections, using preview data](instant-webhooks/connections.webp)

## Try a message, then keep talking

Use **Send a test message** to check your setup. Add a reply address so agents can answer back in the same conversation.

![A secret-header sender and Send a test message, using preview data](instant-webhooks/test-message.webp)

![Two-way replies for a webhook, using preview data](instant-webhooks/replies.webp)

## You stay in control

Only signed messages or messages carrying your secret header are accepted. Morphite checks every message on your computer. Pause a webhook whenever you need to, and rotate its secret to replace the old one.
