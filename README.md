# SqueekWatch

SqueekWatch is a community project for the Squeekchain Buildooooor badge.

SqueekWatch — https://aikbani.github.io/ — Squeekchain account & merge desk by @anehnihorang (repo: https://github.com/aikbani/aikbani.github.io)

## What it is

A read-only, single-file static web app for Squeekchain on Sepolia testnet:

- **Live wheel** — current round, core block height, merge/staking state from the public Squeekchain API.
- **Account lookup** — paste any wallet address to see its Squeeks (token, level, custody, base power, merge state), NFT + SQK power, claimable SQK, lifetime paid SQK, and earnings for the last 7 days. It also warns when a Squeek sits in the wallet earning nothing.
- **Merge planner** — base power per level (level 1 = 1,000, ×2.2 per level, max level 10), how many level-1 Squeeks each level needs, and how far a given stack of level-1 Squeeks can merge.

## What it is not

- No wallet connection, no signing, no private keys, no seed phrases — it only reads the public API (`api.squeekchain.com`).
- No backend, no build step, no tracking. One static `index.html`.
- Testnet only: Sepolia SQK and test Squeeks have no monetary value, and the real $SQK token has not launched.
- Not affiliated with the Squeekchain team. It does not promise a badge, a whitelist spot, or any token.

## How to run

Open `index.html` in any browser, or visit the hosted copy at https://aikbani.github.io/ — no install needed.

## Genesis verification

Ownership is verified through the Genesis `/code` flow: a DNS TXT record issued by Genesis for the domain, a verification page tag issued by Genesis pasted into this page's `<head>`, and this README line. The DNS value and page tag come from the owner's own Genesis session only — they are never generated here. Verified records are rechecked daily; removing them revokes the badge.

## Links

- Squeekchain: https://squeekchain.com/
- Genesis: https://squeekchain.com/genesis
- Docs: https://docs.squeekchain.com/
- Sepolia app: https://sepolia.squeekchain.com/
- Public API status: https://api.squeekchain.com/v1/status
