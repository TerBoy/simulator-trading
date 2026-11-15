
# 📈 SIM·MARKET INSTITUTIONAL
> **Play Live in Browser (Desktop Recommended):** [https://terboy.github.io/simulator-trading/](https://terboy.github.io/simulator-trading/)

An institutional-grade financial terminal and stock market simulator built inside a single self-contained HTML file (3,374+ lines of code) with zero external API dependencies.

# USER GUIDE & OPERATION MANUAL · SIM·MARKET INSTITUTIONAL

Welcome to **SIM·MARKET INSTITUTIONAL**, your high-frequency corporate financial terminal! This guide details step-by-step how each module, market, investment tool, and ranking system works.

---

## 1. Main Interface & Global Controls (Header)

At the top of the screen is the master control panel:
* **Language Selector (ES / EN):** Instantly switch all terminal text between Spanish and English.
* **Live Ticker:** Displays real-time quotes and percentage changes for all assets. Click any ticker to instantly select it.
* **Speed Control:**
  * `⏸ (Pause):` Freezes simulator time.
  * `1x`, `3x`, `10x`: Accelerate market simulation speed.
  * `+1D`: Advances exactly one full trading session instantly.
* **Available Cash & Net Equity:** Displays your total net worth and liquid cash available for trading. Click your capital to open the quick fund selector to reset or inject liquidity.
* **Save (`💾`):** Exports a `.json` file containing your complete game state to back up your progress.

---

## 2. Central Block: Candlestick Charts & Indicators

When selecting a company or asset, the central panel displays high-precision institutional charts:
* **Candles / Area:** Toggle price chart visualization styles.
* **Technical Indicators (SMA, EMA, BB, RSI, MACD):** Enable or disable them with a click to analyze trend strength and momentum.
* **Drawing Mode (+ Level):** Allows you to plot support and resistance lines directly on the chart.
* **Trading Panel (Right of chart):**
  * **Equities:** Buy (Long) or Sell/Short with leverage up to 10x or 20x (if upgrades are unlocked). Trade by share quantity or by entering an exact USD amount.
  * **Call / Put Options:** Buy financial option contracts with custom strike prices and 1, 3, 5, or 10-day expirations.
  * **Blitz (Fast Binary Options):** Bet on price direction (Higher ↗ / Lower ↘) over 15s, 30s, 1m, or 2m with a fixed **+92%** payout.

---

## 3. Management Tabs (Bottom-Left and Right Panels)

* **Portfolio:** Displays your open equity positions (with leverage, entry price, mark price, unrealized P&L, and ROI) and active Call/Put contracts.
* **Top 100 Forbes:** Real-time global billionaire ranking. Your goal as lead manager is to surpass their net worth and climb to rank #1!
* **Tycoon & Alerts:** Displays Institutional Assets Under Management (AUM) attracted by outperforming the S&P 500 (earning daily fees), terminal upgrades (like the TWAP algorithm or Insider Radar), upcoming earnings calendars, price alert configurations, and institutional milestones.
* **Heatmap:** Sectoral visualization of all market assets colored by daily performance. Clicking any block takes you straight to trading it.
* **Limit Orders:** Lists pending limit buy or sell orders that execute automatically when the market hits your target price.
* **Institutional Bank:** Invest in Treasury Bonds with compounding overnight interest or manage corporate credit lines.
* **vs S&P 500:** Comparative Alpha performance chart between your investment fund and the global benchmark index.
* **History:** Detailed log of every executed trade, fees paid, and results achieved.

---

## 4. News, Rumors & Black Swans

* **Financial Wire / News Portal:** Receive breaking dispatches from Bloomberg, Reuters, Financial Times, WSJ, and CNBC directly impacting asset prices.
* **Insider Radar:** If unlocked, intercept leaked market rumors 45 seconds before official news breaks.
* **Black Swans:** Extreme systemic macroeconomic events (such as subsea cable blackouts or banking crises) that violently shock prices across all markets.
