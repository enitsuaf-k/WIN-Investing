# 📊 WIN Stock Analysis Framework Dashboard

Hey girls! 👋

Welcome to the **WIN Stock Analysis Framework** — a structured, step-by-step approach to researching any stock using Claude AI. This repo has everything you need to run your own professional-grade equity research and get a beautiful interactive dashboard at the end.

No finance degree needed. Just curiosity and a Claude account. 💪

---

## What is this?

The WIN framework walks you through 4 steps of stock analysis — from a quick qualitative gut-check all the way to a full valuation deep-dive. At the end, Claude builds you a live, interactive research dashboard that you can open in any browser, bookmark, and revisit anytime.

**What you get at the end — a 4-tab interactive dashboard:**

| Tab | What's inside |
|---|---|
| **Company Overview** | History timeline · Leadership cards · Segment revenue vs margin chart · Revenue by type (donut chart) · Revenue by geography · How each segment makes money (collapsible) · Economic moat by segment · Competitors table |
| **Financials** | 8-point scorecard with PASS/FAIL per metric · 10-year Chart.js charts for each metric · Data notes for distortion years · Total score (X out of 8) |
| **Valuation** | Current P/E, forward P/E, EV/EBITDA snapshot · Peer comparison table · Relative multiple bar charts · Bear/base/bull scenarios · Multi-bagger test · Verdict 🟢🟡🔴 · Risk register |
| **Latest News** | Earnings call hero card · Segment performance · Management Q&A · Recent news items (newest first) · Analyst consensus |

**Live example — SPGI (S&P Global):**
🔗 [Open SPGI Dashboard](https://claude.ai/artifact/N1zmzeKhMdp8k4mfgchKFb)

---

## What's in this repo

| File | What it is |
|---|---|
| `stock-analysis-dash.skill` | The Claude skill — **install this first** |
| `spgi_dashboard_v5.html` | The SPGI reference dashboard (open in any browser) |
| `quick-start-prompts.md` | Copy-paste prompts to get started immediately |
| `README.md` | This guide |

---

## How to get started

### Step 1 — Install the skill into Claude
1. Download `stock-analysis-dash.skill` from this repo
2. Open **claude.ai** in your browser
3. Go to your profile icon (bottom left) → **Settings** → **Skills**
4. Click **Add skill** → upload the `.skill` file
5. The skill is now active in all your Claude conversations ✅

### Step 2 — Pick your stock and type this in a new Claude chat

```
/StockAnalysisDash DBS.SI
```

Replace `DBS.SI` with any ticker. Works for SGX, US, and HK stocks:

```
/StockAnalysisDash OCBC.SI      ← Singapore
/StockAnalysisDash NVDA         ← US
/StockAnalysisDash 0700.HK      ← Hong Kong
```

### Step 3 — Follow the 4 gates

Claude stops after each step and waits for you to say **yes**:

```
You: /StockAnalysisDash DBS.SI

Step 1 → Qualitative scorecard (5 criteria, pass/caution/fail)
         ↳ Claude STOPS — read it, then say "yes" to continue

Step 2 → 8-point financials (10-year charts, PASS/FAIL per metric)
         ↳ Claude STOPS — review, then say "yes" to continue

Step 3 → BB deep dive (business model, moat, leadership, TAM)
         ↳ Claude STOPS — Claude asks "Want me to calculate valuations?"

Step 4 → Full 4-tab dashboard built and published 🎉
```

### Step 4 — Keep it up to date

Once your dashboard is built, refresh it anytime with:

```
Refresh the dashboard with the latest data
```

Claude will update prices, recalculate all peer multiples, add new news items, and republish to the same link.

---

## Tips from the community 💡

**Start with stocks you own or follow** — the analysis hits differently when you have skin in the game.

**Don't skip Step 3** — the qualitative deep dive is where the real edge is. P/E ratios are public. Understanding *why* a business has pricing power isn't.

**The verdict is a starting point** — always cross-reference with your own risk tolerance, portfolio sizing, and time horizon.

**Bookmark your dashboard link** — it's permanent. Check back after each quarterly earnings.

**Test on a stock you already know well** — DBS, OCBC, or a US stock you follow. You'll be able to spot immediately if something looks off.

---

## Tickers cheat sheet

| Market | Format | Examples |
|---|---|---|
| Singapore (SGX) | TICKER.SI | `DBS.SI` `OCBC.SI` `MIT.SI` |
| US (NYSE/NASDAQ) | Just ticker | `NVDA` `AAPL` `MSCI` |
| Hong Kong (HKEX) | NUMBER.HK | `9988.HK` `0700.HK` |
| UK (LSE) | TICKER.L | `SHEL.L` `HSBA.L` |

---

## Questions or issues?

Maintained by **Faustine** — drop me a message in the group if something doesn't look right or you have ideas to make this better. 🙌

The skill will be updated as the framework evolves — just re-download `stock-analysis-dash.skill` from this repo and reinstall it in Claude Settings to get the latest version.

---

*Built with Claude AI · WIN Women Investors Network*
