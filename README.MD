# FileDeli

Secure peer-to-peer file transfer with end-to-end encryption, inspired by Wormhole.app.

## What is FileDeli?

FileDeli enables direct browser-to-browser file transfers using WebRTC. Files are encrypted client-side and never touch our servers - they go straight from sender to receiver.

## Key Features

- **P2P Transfer** - Direct connection between browsers
- **End-to-End Encrypted** - Files encrypted using RFC 8188 streaming encryption
- **No Signup** - Just create a link and share
- **Real-time Progress** - See transfer speed and progress live

## Tech Stack

**Frontend:** React, TypeScript, WebRTC, wormhole-crypto  
**Backend:** Bun, Elysia, PostgreSQL, Redis, coturn

## How It Works

1. Sender creates room and uploads file
2. Receiver opens link
3. WebRTC connects directly between browsers
4. Encrypted file chunks stream peer-to-peer

**Live:** https://filedeli.com