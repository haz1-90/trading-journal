# Hazwan · Trading Journal 2026

A single-file, offline-first trading journal for **prop-firm crude-oil tick scalping**,
modelled on the Notion "Journal 2026" layout and the Crude/InvestorPoint templates.

## Open it
Just open `index.html` in any browser — no build, no server, no account.
All data is stored locally in the browser (`localStorage`).

### Host it as a website (optional)
Enable **GitHub Pages** for this repo (Settings → Pages → deploy from `main`, root)
and the journal will be live at `https://haz1-90.github.io/trading-journal/`.

## Features
- **Dashboard** — Net P&L, Win Rate, **NPR** (Net Profit Ratio), Expectancy, account
  equity curve, weekly discipline tracker (5 trades / 1 per day, Mon–Fri), withdrawal-goal
  progress, monthly P&L, win/loss donut, and your trading mantra.
- **Trades** — log every trade with the Notion fields: Prop Firm · Instrument · Date ·
  Session · Setup · TF · TP/SL (ticks) · Result ticks · RRR · Grade (A+/A/B/C) · P&L ·
  emotion · rating · chart-before/after screenshots · notes. Filter & search.
- **Ticks-first P&L** — enter result in ticks; P&L auto-computes from `ticks × contracts ×
  tick value`. R-multiple = result ÷ SL ticks.
- **Calendar** — monthly heatmap of daily P&L.
- **Analytics** — performance by setup, session, grade, day-of-week, instrument, and
  R-multiple distribution; avg win/loss, best/worst, streaks, total ticks.
- **Playbook** — editable **Methodology** reference table (Methodology · Quality ·
  Playbook · Condition · TP/SL) and **Monthly Lessons** (Keep / Quit) per month,
  mirroring the Crude template.
- **Settings** — starting balance, currency, tick value, targets, playbook lists
  (prop firms / setups / sessions / grades / timeframes), editable mantra.
- **Data** — export/import JSON, export CSV, load sample data, dark/light theme.

Keyboard: `N` = new trade · `Esc` = close.

> Personal use for Hazwan. Not financial advice.
