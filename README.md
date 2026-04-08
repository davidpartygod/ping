# ping
Decentralized P2P encrypted messaging. No servers. No tracking. Just you and your people.
Features
End-to-end encrypted — messages encrypted before they leave your device
Fully decentralized — peer-to-peer, no central server
Zero tracking — no analytics, no telemetry, no data collection
No phone number required — your identity is a cryptographic keypair
Works everywhere — single HTML file, runs in any browser
Persistent — data saved locally in IndexedDB, survives refreshes
Responsive — optimized for both mobile and desktop
Quick Start
Open https://yourusername.github.io/ping on any device.
How It Works
Create identity — generates a cryptographic keypair in your browser
Set a PIN — encrypts your private key locally
Share your Ping ID — 8-character public identifier
Add friends — enter their Ping ID to connect
Chat — messages sent directly peer-to-peer
Data Storage
All data is stored locally in your browser's IndexedDB:
Your keypair (encrypted with your PIN)
Your contacts
Your message history
Nothing is ever sent to any server.
Tech Stack
Vanilla JavaScript + React (CDN)
Web Crypto API for key generation
IndexedDB for persistent local storage
Zero dependencies, zero build tools
License
MIT
