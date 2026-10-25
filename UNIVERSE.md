# Investigation Universe

An index fund publishes explicit rules for what counts as a constituent: market cap bands, liquidity minimums, sector weights. This document does the same thing for this repo, defining what counts as in scope to investigate and why, rather than adding asset classes one at a time as they come to mind.

## Inclusion Criteria

An asset or instrument qualifies for investigation here if it has no continuous, visible market price: no daily quote, no public order book, no transparent bid-ask spread. Instead, its value comes from a periodic mark, a model output, manager judgment, or (for newer instrument types) no established methodology at all yet. That last case is its own category below, not an edge case to exclude.

## Coverage

| Category | Niche | Status | What's hard about pricing it |
|---|---|---|---|
| Private markets | Private Equity (buyout) | Complete | Infrequent marks, conflicted reporting party; see [private-equity-valuation.md](investigations/private-equity-valuation.md) |
| Private markets | Venture Capital | Not started | Pre-revenue, no comparable multiples, value is almost entirely narrative until an exit event |
| Private markets | Private Credit / Direct Lending | Not started | No secondary market; value depends on credit quality that's rarely re-rated between originations |
| Real assets | Unlisted Infrastructure | Not started | Long-duration cash flows, regulatory/concession risk baked into the discount rate rather than observable |
| Real assets | Direct / Unlisted Property | Not started | Appraisal-based valuation, comparable sales can be months stale, illiquidity discount is judgment-heavy |
| Environmental markets | Carbon Credits & Related Instruments | Not started | Fragmented registries, credit quality varies hugely by project type, no single reference price |
| Event-driven & synthetic markets | Prediction Markets | Not started | Probability-implied pricing rather than DCF/multiples; a genuinely different mechanism from the rest of this list |
| Event-driven & synthetic markets | Layered / referential markets (a market betting on another market's outcome, rather than the underlying event itself) | Not started | Some of these barely exist as formalised instruments yet; the pricing problem here isn't just "no market data," it's "no established methodology to start from" |

## A Note on the Last Category

The synthetic CDO trade in *The Big Short* is the clean illustration: instead of owning mortgage bonds, you can construct an instrument that just references the performance of other mortgage bonds, and in principle that referencing can stack again on top of itself. Prediction markets sit on the near edge of this same idea; a market whose contract pays out based on the price or outcome of *another* prediction market would sit further out on it. Most of what would fall in this category doesn't exist yet in a standardised, tradeable form, which makes it a deliberately open-ended slot in this universe rather than a queued investigation with a clear methodology waiting to be applied.

---
*Maintained by Cohen Pikari ([github.com/cohen-pikari](https://github.com/cohen-pikari))*
