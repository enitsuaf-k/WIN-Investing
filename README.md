# 📊 WIN Stock Analysis Framework Dashboard

Hey girls! 👋

Welcome to the **WIN Stock Analysis Framework** — a structured, step-by-step approach to researching any stock using Claude AI. This repo has everything you need to run your own professional-grade equity research and get a beautiful interactive dashboard at the end of it.
Credit: This framework is adapted from SG Budget Babe's proprietary Millionaire Accelerator Program (MAP), with further enhancements I have added.

No finance degree needed. Just curiosity and a Claude account. 💪

---

## What is this?

The WIN framework walks you through 4 steps of stock analysis — from a quick qualitative gut-check all the way to a full valuation deep-dive. At the end, Claude builds you a live, interactive research dashboard (like the SPGI example below) that you can open in any browser, bookmark, and revisit anytime.

Think of it as having a personal Wall Street analyst in your pocket — one that explains everything in plain English and stops at each step to ask if you want to continue.

**What you get at the end:**

- 📋 A qualitative scorecard (does this stock pass the basics?)
- 📈 10-year financial history across 8 key metrics
- 🏰 Deep-dive on the business model, moat, and leadership
- 💰 Full valuation with peer comparison and scenario modelling
- 📰 Latest news and earnings call highlights — all in one dashboard

---

## Live example

Here's what a finished dashboard looks like — this one is for **S&P Global (SPGI)**:

🔗 [Open SPGI Dashboard](https://claude.ai/artifact/N1zmzeKhMdp8k4mfgchKFb)

You can use this as your reference for what to expect when you run the framework on your own stock.

---

## What's in this repo

| File | What it is |
|---|---|
| `stock-analysis-dash.skill` | The Claude skill — install this first |
| `SPGI_dashboard.html` | The SPGI example dashboard (open in any browser) |
| `quick-start-prompts.md` | Copy-paste prompts to get started immediately |

---

## How to get started

### Step 1 — Make sure you have Claude Cowork
You'll need access to **Claude Cowork** (claude.ai). A Pro or Team plan works best since the analysis runs across multiple steps and generates a large HTML file at the end.

### Step 2 — Install the skill
1. Download `stock-analysis-dash.skill` from this repo (click the file → click the download button)
2. Open Claude Cowork
3. Drag and drop the `.skill` file into Claude — or go to **Skills → Add skill → Upload**
4. Done! The skill is now installed in your Claude profile

### Step 3 — Pick your stock and go
In Claude, type:

```
/StockAnalysisDash NVDA
```

Replace `NVDA` with any ticker you want to research. Singapore stocks work too:

```
/StockAnalysisDash DBS.SI
/StockAnalysisDash 9988.HK
```

### Step 4 — Follow the gates
The framework stops after each step and waits for you to say **yes** before continuing. This is intentional — it gives you time to read, question, and decide if you want to go deeper.

```
Step 1 → Qualitative scorecard     → Claude stops, you review
Step 2 → 8-point financials        → Claude stops, you review  
Step 3 → Business model deep-dive  → Claude stops, you review
Step 4 → Full valuation + dashboard → Final output 🎉
```

You can also run individual steps if you just want a quick check:

```
Run Step 1 on OCBC.SI
Run Step 2 on MSCI
Do the valuation for Netflix
```

### Step 5 — Refresh your dashboard anytime
Once your dashboard is built, you can update it with the latest prices and news anytime:

```
Refresh the dashboard with latest data
```

Claude will pull current prices, update all the valuation multiples, refresh the peer comparison, and republish the dashboard to the same link — no new link needed.

---

## The 4-step framework

| Step | What it covers | Output |
|---|---|---|
| **Step 1** | Large market? Growing? Liquid? Fair valuation? Well covered? | Traffic-light scorecard |
| **Step 2** | 10-year history: margins, profitability, debt, cash flow, EPS | 8-point pass/fail scorecard with charts |
| **Step 3** | Business model, moat, leadership, TAM, competition | Collapsible deep-dive cards |
| **Step 4** | Current multiples, peer comparison, scenarios, multi-bagger test | Interactive dashboard + verdict |

---

## Tips from the community

💡 **Start with stocks you already own or are curious about** — the analysis is much more interesting when you have skin in the game.

💡 **Don't skip Step 3** — the qualitative deep-dive is where you'll find the real edge. Margins and P/E ratios are public information. Understanding *why* a business has pricing power isn't.

💡 **The verdict is a starting point, not a buy signal** — always cross-reference with your own risk tolerance, portfolio allocation, and investment horizon.

💡 **Save your dashboard link** — each dashboard gets a permanent URL. Bookmark it and check back after each quarterly earnings.

💡 **Singapore stocks work great** — the framework handles SGX, HKEX, and NYSE/NASDAQ tickers. Just add `.SI` for SGX stocks (e.g. `DBS.SI`) and `.HK` for HKEX.

---

## Questions or improvements?

Maintained by **Faustine** — drop me a message in the group if something doesn't work or if you have ideas to make this better. This is a living tool and will get updated as the framework evolves. 🙌

---

*Built with Claude AI · WIN Women Investors Network*
