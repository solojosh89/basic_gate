# TradeGate

**Trade your plan, not your emotions.**

A single-file trading discipline app — no backend, no accounts, all data stays in your browser (localStorage). Installable on your phone as a PWA.

## Features

- **Gate** — ALLOW / WAIT / BLOCK before every trade: daily loss cap, max trades, consecutive-loss breaker, post-loss cooldown, manual end-of-day lockout with recurring "stay out" notifications.
- **Prop Plan** — enter your prop firm's rules (account size, max daily drawdown %, max total drawdown %, safety buffer) and get your numbers: lots per stop size, risk per trade, action levels (60% reduce size / 80% stop), days survivable. Values sync live with the Gate.
- **Pip-based ticket** — enter SL and TP in pips, get lots sized to your remaining daily budget (counts open-trade floating risk, FundedNext-style).
- **Journal & Stats** — R-multiples, win rate, equity, discipline metrics.

## Run

Open `index.html` in a browser, or host the folder anywhere static
(Netlify Drop, GitHub Pages, Vercel). On a phone: open the hosted URL →
**Add to Home Screen**.
