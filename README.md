# Monofin Docs

Public documentation for [Monofin](https://docs.monofin.xyz) — the social trading app for prediction markets, crypto perps, and real-world assets.

Built with [Mintlify](https://mintlify.com).

## Develop locally

```bash
npm i -g mint
mint dev        # local preview on http://localhost:3000
```

Run from the repo root (where `docs.json` lives).

## Deploy

1. Push this repo to GitHub.
2. Install the [Mintlify GitHub app](https://dashboard.mintlify.com) on the repo — every push to `main` deploys automatically.
3. In the Mintlify dashboard, set the custom domain to **docs.monofin.xyz**. DNS is already configured (CNAME → `cname.mintlify.app`).

## Structure

| Section | Content |
|---|---|
| About Monofin | What Monofin is, quickstart, funding |
| Markets | Event markets, perpetual futures, real-world assets |
| Trading | How trading works, order types, leverage/funding/liquidations, fees |
| Social | Leaderboard, profiles & feed, chat, referrals |
| Earn | Curated yield vaults and the three risk tiers |
| Account | Wallet & security, availability, FAQ |
