# Lone Wolf VWAP & EMA

A Pine Script v6 chart indicator combining an anchored Volume Weighted Average Price (VWAP), configurable deviation bands, an EMA, and optional moving-average smoothing with Bollinger Bands.

## Features

- VWAP anchors for sessions, weeks, months, quarters, years, decades, centuries, earnings, dividends, and splits.
- Optional VWAP bands using standard deviation or percentage distance, with up to three configurable multipliers.
- EMA length and plot offset controls.
- Optional smoothing with SMA, EMA, RMA, WMA, VWMA, or SMA Bollinger Bands.
- Option to hide VWAP on daily and higher timeframes.

## Use in TradingView

1. Open the Pine Editor.
2. Copy the contents of [lone-wolf-vwap-ema.pine](lone-wolf-vwap-ema.pine) into a new script.
3. Save it and select **Add to chart**.

A data feed without volume may not produce a valid VWAP.

## Source and licensing

The VWAP and band portions follow code available in TradingView built-in scripts. TradingView's [script publishing rules](https://www.tradingview.com/support/solutions/43000590599-script-publishing-rules/) classify code from its built-in scripts and documentation as public domain. The MIT license in this repository applies to original contributions and does not limit the rights that apply to that underlying material.

This indicator is provided as-is, without warranty, and is not financial advice.
