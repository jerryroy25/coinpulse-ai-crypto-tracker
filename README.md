# CoinPulse AI — Crypto Price & Volatility Tracker
### Watching the Markets So You Don't Have To

> **Built once. Used forever.** — Built by [JeRoy | The Instructional Architect](https://linkedin.com/in/jerryogahroy)

---

## Overview

CoinPulse AI is a precision-built crypto monitoring and alert automation for traders and teams who want instant insight without constantly watching charts. It continuously tracks selected assets, fires alerts when price thresholds are hit, logs every event to Google Sheets and Supabase, and displays everything on a real-time dashboard powered by Lovable UI.

**Category:** Finance & Accounting / Financial Forecasting
**Platform:** Make.com + CoinGecko API + Google Sheets + Supabase + Lovable UI + Slack/Telegram
**Version:** v1.0

---

## The Problem

Crypto markets move fast — 24/7. Traders who manually monitor prices miss moves, react late, and spend hours staring at charts when they should be focused on strategy. Missed alerts cost real money.

---

## How It Works

1. **Price Monitoring** — Pulls current market data every few minutes via CoinGecko API for each asset on your watch-list
2. **Smart Alert Logic** — Detects price crosses, dips, spikes, and volatility beyond defined limits (above / below / both directions)
3. **Multi-Channel Alerts** — Sends instant notifications to Slack, Telegram, or Email when thresholds are triggered
4. **Cool-Down Logic** — Prevents duplicate alerts for the same event
5. **Data Logging** — Every alert logged to Google Sheets and Supabase with asset, price, condition, and timestamp
6. **Live Dashboard (Lovable UI):**
   - Alerts feed — real-time stream of triggered events
   - Top movers table — highest % gainers/losers
   - Filters & sorting by asset or movement direction
   - Responsive design (desktop + mobile)

**Watch-list managed via Google Sheets** — no backend changes needed to add or remove assets.

---

## Demo

📹 [Watch the Demo Video](https://drive.google.com/file/d/1W2yt3TyFoUBzfPhJW1wweR-F7MDeHHXz/view?usp=drive_link)

---

## Tools Required

| Tool | Purpose | Cost |
|------|---------|------|
| Make.com | Workflow automation | Free / paid tiers |
| CoinGecko API | Live crypto price data | Free tier available |
| Google Sheets | Watch-list & logging | Free |
| Supabase | Data storage & API backend | Free tier available |
| Lovable UI | Dashboard front-end | Paid workspace |
| Slack / Telegram / Email | Alert delivery | Free |

**Estimated monthly cost:** ~$70

---

## Setup Requirements

- Make.com account with active scenarios
- CoinGecko API key (or similar crypto data provider)
- Google Sheets account — watch-list with symbols and thresholds
- Supabase project with alerts table configured
- Lovable UI workspace connected to Supabase
- Slack or Telegram account for alert delivery

---

## Deployment Time

| Scenario | Time |
|----------|------|
| Standard deployment | 1–2 days |
| With custom assets and integrations | 3–5 days |

---

## Value Proposition

| Metric | Value |
|--------|-------|
| Average time saved per week | 10 hours |
| Average cost saved per month | ~$700 |
| Agent value for ICP | ~$1,000 |
| Subscription cost | ~$70/month |

**Example:** A trading group tracking BTC, ETH, and SOL saved ~6 hours per week in manual monitoring after deployment.

---

## Pricing

| Model | Price |
|-------|-------|
| One-time deployment | $100 |
| Retainer / upgrades | Custom |

---

## Key Capabilities

- Continuous crypto price monitoring across multiple assets
- Threshold-based alerts (upper/lower limits or volatility triggers)
- Multi-channel notifications (Slack, Telegram, Email)
- Logging to Google Sheets and Supabase
- Real-time dashboard visualization via Lovable UI
- Watch-list configuration from Google Sheets
- Cool-down logic to prevent duplicate alerts

---

## Known Limitations

- CoinGecko free tier has rate limits — high-frequency polling may require paid plan
- Dashboard requires Supabase and Lovable UI setup (not plug-and-play)
- No on-chain data in v1.0 — price data only
- Make.com execution limits apply on free plan

---

## Repo Structure

```
coinpulse-ai-crypto-tracker/
├── workflow/        # Make.com workflow export
├── screenshots/     # Dashboard and workflow screenshots
├── demo/            # Demo video link
└── README.md
```

---

## Version History

| Version | Notes |
|---------|-------|
| v1.0 | Initial release — CoinGecko monitoring, threshold alerts, Sheets + Supabase logging, Lovable UI dashboard |
| Planned | Exchange API connections, on-chain data, multi-dashboard setup |

---

*Built by [JeRoy | The Instructional Architect](https://linkedin.com/in/jerryogahroy) — Complex in. Simple out.*
