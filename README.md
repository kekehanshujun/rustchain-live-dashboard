# RustChain Live Dashboard

Single-file live dashboard for RustChain bounty #1600.

## Features

- Live `/epoch`, `/health`, `/api/miners`, and `/wallet/balance` data from `https://rustchain.org`
- Auto-refresh every 30 seconds with manual refresh
- Active miner balance table with hardware family and multiplier
- Balance distribution canvas chart
- Public endpoint checks for `/api/stats` and `/api/transactions`
- Mobile responsive layout

## Network status page

`status.html` is a dedicated RustChain network status page for bounty #38:

- Browser checks for public attestation-node `/health` endpoints
- Current epoch and settlement progress from `/epoch`
- Active miner count and hardware-family chart from `/api/miners`
- Incident log, status feed line, and README badge snippet
- 60-second auto-refresh and mobile responsive layout

## Bounty

- Bounty: https://github.com/Scottcjn/rustchain-bounties/issues/1600
- Status page bounty: https://github.com/Scottcjn/rustchain-bounties/issues/38
- RTC wallet: `RTC02811ff5e2bb4bb4b95eee44c5429cd9525496e7`

## Local preview

Open `index.html` directly in a browser or serve the folder with any static file server.
