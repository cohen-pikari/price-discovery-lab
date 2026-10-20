# Price Discovery Lab

Investigating how hard-to-value, illiquid, and non-market-priced assets actually get priced — one asset class at a time.

## Purpose

Some of the most interesting pricing happens away from the exchanges everyone already watches — private equity and venture stakes, unlisted real assets, private credit, prediction markets, and other uncommon or unlabelled engagements that don't trade on a continuous, visible market. There's no ticker to check, so the price has to be built: from models, comparable deals, manager judgment, or signals borrowed from related markets.

This repository investigates how that actually happens for each asset class — what the real methodology is, how it holds up against a concrete example, and where it leans on judgment rather than hard data. It's separate from [investment-research-vault](https://github.com/cohen-pikari/investment-research-vault), which tracks live, ongoing theses on listed securities — this repo is about the pricing mechanics themselves, not a tracked portfolio.

## Repository Structure

```
investigations/     one write-up per asset class
README.md           this file
```

Each investigation in `investigations/` follows the same format:

1. **Why it's hard to price** — what's actually missing (continuous trading, comparable transactions, transparent order flow, etc.)
2. **Standard methodology** — how practitioners actually derive a value, and why
3. **Worked example** — a concrete, numbers-based walkthrough
4. **Limitations & open questions** — where the methodology breaks down or relies on judgment

## Current Investigations

| Asset Class | Status | Core Method |
|---|---|---|
| [Private Equity](investigations/private-equity-valuation.md) | Complete | DCF + comparable transactions, illiquidity discount |

More asset classes (private credit, unlisted real assets, prediction markets) to follow.

## ⚖️ Disclaimer

This repository documents investigative research into asset pricing and valuation methodology, for educational and career-development purposes only. Nothing here constitutes financial advice, a recommendation, or a solicitation to buy or sell any security or interest. Worked examples use publicly available information and are not current or complete valuations of any asset.

Do your own research and consult a licensed financial adviser before making investment decisions.

Maintained by Cohen Pikari (github.com/cohen-pikari)
