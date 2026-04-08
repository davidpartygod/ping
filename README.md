# Ping

Decentralized P2P encrypted messaging. No servers. No tracking.

## Features

- **Real P2P messaging** — messages go directly between devices via WebRTC
- **End-to-end encrypted** — only you and your friend can read messages
- **Zero cost** — no servers to pay for, uses free PeerJS signaling
- **Persistent** — data saved in IndexedDB, survives refreshes
- **Works everywhere** — single HTML file, any browser, any device

## How to use

1. Open the app → Create identity → Get your Ping ID
2. Share your Ping ID with a friend
3. Both of you add each other's ID
4. When both online → direct P2P connection → real-time chat

## Tech

- PeerJS (WebRTC) for peer-to-peer connections
- IndexedDB for local data persistence
- Web Crypto API for key generation
- Single HTML file, zero build tools

## License

MIT
