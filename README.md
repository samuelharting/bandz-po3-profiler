# Bandz Po3 Profiler

Free, open-source Pine Script v6 overlay for HTF candles, C1-C4 sequence context, T-Spots, CISD, STDV, SMT / SSMT, PSP, entry FVGs and key levels.

[Use on TradingView](https://www.tradingview.com/script/i0RzxXU7-Bandz-Po3-Profiler/) | [Complete source](Bandz_Po3_Profiler.pine) | [All Bandz indicators](https://github.com/samuelharting/bandz-indicators)

## Features

- Three automatic or manual HTF candle lanes; default 30m / 90m / 6H ladder on lower intervals.
- C1-C4 profiling, sweep lines and configurable T-Spots with Open / Easy / Medium / Hard / Max filters.
- Chart, 3m or 5m sequence CISD, configurable STDV projections and paired level shading.
- Correlated-asset SMT / SSMT with automatic asset groups or manual comparison symbols.
- HTF PSP highlights, FVGs, volume imbalances, midpoints and liquidity levels.
- Displacement entry FVGs and FVGs within qualifying T-Spots with configurable expiry.
- Previous-day levels, daily / weekly opens, five custom opens and vertical open lines.
- Quick toggles, saved color / opacity defaults, and configurable text / timezone.

## Installation

Use the TradingView link above and select **Use on chart**. To customize a local copy:

1. Open `Bandz_Po3_Profiler.pine`, select **Raw**, and copy the entire file.
2. In TradingView's Pine Editor, create a new indicator and replace the starter code.
3. Save and select **Add to chart**.
4. Start with Auto HTF / Auto count on a 1m or 5m chart, then choose comparison assets and the T-Spot filter.

The 3m / 5m CISD source is intended for chart intervals below that timeframe; otherwise chart CISD is used. No subscription or invite-only access is required.

## Source and live behavior

This release preserves the owner's TradingView source captured on October 8, 2026, including its current input defaults. Developing candles and their sequence / divergence marks may change before closing; invalidated or expired drawings can disappear. This is a visual chart tool, not an automated strategy or a performance claim.

## License

Mozilla Public License 2.0. See [LICENSE](LICENSE). Original source comments are preserved.
