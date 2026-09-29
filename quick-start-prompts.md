# ⚡ Quick-start prompts — WIN Stock Analysis Framework

Copy and paste any of these directly into Claude to get started.

---

## Run the full 4-step framework

```
/StockAnalysisDash DBS.SI
```
```
/StockAnalysisDash OCBC.SI
```
```
/StockAnalysisDash NVDA
```
```
/StockAnalysisDash AAPL
```
```
/StockAnalysisDash 9988.HK
```

---

## Run individual steps only

```
Run Step 1 on MSFT
```
```
Run Step 2 on OCBC.SI
```
```
Do the BB Framework deep dive for DBS.SI
```
```
Calculate the latest valuations for GOOGL
```

---

## What to say at each gate

After Step 1 finishes:
```
Yes, continue to Step 2
```

After Step 2 finishes:
```
Yes, continue to Step 3
```

After Step 3, when Claude asks about valuations:
```
Yes, please calculate the latest valuations and build the full dashboard
```

---

## Refresh an existing dashboard

```
Refresh the dashboard with the latest data
```
```
Update the dashboard — stock price and peers have changed
```
```
Please update the peer comparison with the latest prices too
```

---

## If your dashboard is missing sections

If the dashboard doesn't show all 4 tabs or is missing sections, use this:

```
The dashboard is missing some sections. Please rebuild it with ALL mandatory
sections: 4 tabs (Company Overview, Financials, Valuation, Latest News),
the segment dual-bar chart, revenue by type (donut), revenue by geography,
collapsible segment deep-dives, economic moat grid, 8-point PASS/FAIL
scorecard with 10-year charts, peer comparison table with relative bars,
earnings hero card, and news items sorted newest-first. Use the SPGI
dashboard at https://claude.ai/artifact/N1zmzeKhMdp8k4mfgchKFb as the
reference for layout and visual style.
```

---

## Add-ons after the dashboard is built

```
Add the latest earnings call highlights to the Latest News tab
```
```
Update the news items — sort them newest date first
```
```
What is the current analyst consensus and mean price target?
```
```
Compare this stock to its top 3 competitors in the Valuation tab
```

---

## Tickers cheat sheet

| Market | Format | Example |
|---|---|---|
| Singapore (SGX) | TICKER.SI | `DBS.SI`, `OCBC.SI`, `MIT.SI` |
| US (NYSE/NASDAQ) | Just ticker | `NVDA`, `AAPL`, `MSCI` |
| Hong Kong (HKEX) | NUMBER.HK | `9988.HK`, `0700.HK` |
| UK (LSE) | TICKER.L | `SHEL.L`, `HSBA.L` |

---

*WIN Stock Analysis Framework · github.com/enitsuaf-k/WIN-Investing*
