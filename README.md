# NSE MarketMatrix Web Portal

[![Live Web Portal][badge-live]][url-live]
[![Equities Tracked][badge-eq]]()
[![Indices Tracked][badge-idx]]()

[badge-live]: https://img.shields.io/badge/Portal-Live-brightgreen.svg
[url-live]: https://omkarsav.github.io/nse-marketmatrix-web/
[badge-eq]: https://img.shields.io/badge/Equities-2%2C578-blue.svg
[badge-idx]: https://img.shields.io/badge/Indices-87%20(77%20live)-teal.svg

An institutional-grade stock intelligence platform, constituent database,
and TradingView watchlist suite for National Stock Exchange of India (NSE)
equities.

---

## 🌐 Live Web Portal
Launch the live portal directly in your browser:
**<https://omkarsav.github.io/nse-marketmatrix-web/>**

---

## ⚡ Core Capabilities

1. **Full NSE Universe Coverage**:
   - Tracks all **2,578 active listed equities** on the National Stock
     Exchange.
   - Comprehensive constituent mappings across **87 official indices**
     (Broad-Based, Sectoral, Thematic, and Quantitative Strategy /
     Smart Beta).

2. **Multi-Timeframe Benchmark Opens (W · M · Q · Y)**:
   - Tracks whether current price trades above or below benchmark opens:
     - **Weekly Open (W)**: First trading session of the calendar week.
     - **Monthly Open (M)**: First trading session of the calendar month.
     - **Quarterly Open (Q)**: First trading session of the calendar
       quarter.
     - **Yearly Open (Y)**: First trading session of the calendar year.
   - Real-time visual direction chips (🟢 `▲ Above` / 🔴 `▼ Below`) with
     interactive tooltips displaying exact open levels and distance %.

3. **50 vs 200 SMA Cross Regime**:
   - Identifies macro trend alignment:
     - 🟢 **`▲ 50 > 200 SMA`** (Golden Cross / Bullish structural regime).
     - 🔴 **`▼ 50 < 200 SMA`** (Death Cross / Bearish structural regime).

4. **Granular Screening & Filtering**:
   - **Market Cap**: Custom valuation ranges (from Micro to Mega Cap).
   - **Listing Date**: Multi-decade IPO age and vintage filters.
   - **50-Day SMA Distance**: Fine % distance filters with 1-click presets
     (Near Support, Trend Momentum, Pullback, Deep Discount).
   - **Open Benchmarks**: Individually selectable W, M, Q, Y filters plus
     multi-open presets (`Above All`, `Below All`, `HTF: Q & Y`, etc.).
   - **50 vs 200 Cross**: One-click screening for Golden/Death crosses.

5. **TradingView Watchlist Export**:
   - Filter-aware export box generating comma-separated `NSE:SYMBOL`
     strings ready for 1-click import into TradingView.

6. **100% Client-Side Architecture**:
   - Self-contained, zero-latency desktop engine with responsive navigation
     and instant search autocomplete.
