# At-Scale Financial Model — Guide

Source: "Rough Guide to Creating a Financial Model" (IVE Systems), At-Scale Op Model & Fin Model slides.

The financial model answers two questions:
1. **What price must we charge to achieve investment profitability?** (Required price)
2. **How does this compare to what customers will credibly pay?** (Target price)

If required price > target price: the venture has a structural viability problem. Solve it in the design, not in execution.

---

## The Cost Structure

Four layers of cost, building from bottom up:

| Layer | Definition | Examples |
|-------|-----------|---------|
| **PVC** — Product Variable Costs | Direct costs per unit of product/transaction | Raw materials, components, packaging, duties, shipping |
| **RC** — Running Costs | Ongoing operations at steady state | Staff salaries, marketing, office, ongoing training |
| **SC** — Start-Up & Scaling Costs | Capital and investment to build toward scale | Capital assets, product development, launch costs, customer acquisition cost |
| **IC** — Investment Costs | Competitive return on capital invested | Required IRR on debt or equity capital |

---

## Profitability Levels

Each layer crossed represents a profitability milestone:

| Price Level | Profitability Status | What It Means |
|-------------|---------------------|--------------|
| Price < PVC | **Product Losses** | Subsidize product — losing money on every unit |
| Price = PVC | **Break even on product** | — |
| Price < PVC + RC | **Operating Losses** | Subsidize operating unit |
| Price = PVC + RC | **Operating Profitability** | Operations self-sustaining — still not covering growth investment |
| Price = PVC + RC + SC | **Venture Profitability** | Can subsidize replication — but not yet paying back investors |
| Price = PVC + RC + SC + IC | **Investment Profitability** | Self-scaling — paying investors their required return |

**The target is Investment Profitability.** Venture Profitability is not enough.

---

## Two Time Periods

The model treats the venture in two distinct phases:

### Investment Period
- Growth phase: customer base growing from 0 to at-scale
- Cash flows scale proportionally with customer base in each period
- Duration: typically 3–7 years (set by investors or self-imposed)
- All four cost layers (PVC + RC + SC + IC) must be covered

### Equilibrium Period
- Steady state: at-scale customer base maintained as a perpetuity
- Revenue = monthly repurchases of at-scale base (treated as perpetuity)
- Costs return to steady-state levels (no more SC growth component)
- This is where the venture generates its long-term returns

---

## 6-Step Model Construction

### Step 1: Bound the Unit and Head Office
*"What is the at-scale customer base and transaction volume per operating unit?"*

- **Bound the operating unit:** How many customers and transactions does the average last-mile unit serve at scale? This determines unit size (staff, assets, activities) and unit costs.
- **Bound the head office:** How many last-mile operating units does the head office need to support at scale? This determines HO size and cost structure.

Everything else flows from this bounding exercise.

### Step 2: Running Costs (At-Scale)
- 2(a) Operating unit running costs at scale (staff, rent, marketing, ongoing ops)
- 2(b) Head office running costs at scale
- Total = at-scale running costs for the whole venture

### Step 3: Start-Up & Scaling Costs
- 3(a) Operating unit start-up and scaling costs (capex, customer acquisition, training)
- Head office start-up and scaling costs
- Total = investment required to reach scale

### Step 4: Investment Costs
- 4(a) Debt cost at current market rate
- 4(b) Required return on equity (the IRR)
- Total = IC layer

### Step 5: Free Cash Flows
- 5(a) Investment period: cash flows scale with growing customer base
- 5(b) Equilibrium period: perpetuity cash flows from at-scale base
- Both periods modelled separately

### Step 6: Required Price
- Calculate the price needed to achieve investment profitability at the required IRR
- Compare to target price (what customers will credibly pay based on WTP data)
- **If required price < target price: proceed. If not: redesign.**

---

## Pricing Units

Before modelling, define what a "unit" is. Products often have:
- **Categories** (e.g., solar lantern vs. solar home system — customer could have one of each)
- **Versions** (different models within a category)
- **Payment options** (cash, PAYG, instalments)

Each combination is a pricing unit. The model needs a list of all pricing units and their estimated transaction volumes.

---

## Investment Period Parameters

Three ways the investment period can be defined:
1. **Specified by investors** — their requirement for return timing
2. **Self-imposed** — founder's assessment of when at-scale penetration is reached
3. **Target penetration rate** — when a defined market penetration milestone is hit

Typical range: 3–7 years. Longer than 7 years makes the compounding cost of capital very difficult to recover.

---

## Key Diagnostic Questions

When reviewing a venture's financial model:

**On bounding:**
- "What is the at-scale customer base per operating unit? How did you arrive at that number?"
- "What observable data grounds the transaction volume estimate?"

**On cost structure:**
- "Have you separated PVC, RC, SC, and IC? Or is everything lumped into one number?"
- "What's the single biggest cost driver in your model? Is it in the design?"

**On the required vs. target price gap:**
- "What is your required price at your required IRR?"
- "What is your evidence of customer willingness to pay? From real transactions or surveys?"
- "What is your financial margin of safety — the gap as a percentage of cost?"

**On investment period:**
- "How long is your investment period? What's the IRR at that timeline?"
- "Have you modelled what happens if you take 2 years longer to reach scale?"

**On the stress test:**
- "If your three biggest cost uncertainties all resolve badly simultaneously, is the venture still investment-profitable?"

---

## Financial Margin of Safety

**Definition:** The distance between the low-point estimate of customers' willingness to pay and the high-point estimate of total unit costs (including cost of capital), expressed as a percentage of the high-point unit cost estimate.

**Formula:** (Min WTP − Max Unit Cost) / Max Unit Cost × 100

**Benchmarks:**
- Average cost overrun for complex engineering projects: 62% (Flyvbjerg & Gardner)
- Therefore a margin of safety below 50% is structurally fragile
- 50–100%: healthy
- 100%+: strong (Airbnb was ~133%)

**Why it matters:** A margin below 50% means a single bad assumption can erode profitability entirely. The higher the margin, the more resilient the venture is to real-world conditions.

---

## Common Financial Model Failures

| Failure | What it looks like | What it means |
|---------|-------------------|--------------|
| No bounding | "We'll have 10,000 customers in year 3" | No operating unit analysis — numbers are top-down guesses |
| Missing IC layer | "We're profitable after covering costs" | Operating profitability ≠ investment profitability. Ignores cost of capital. |
| WTP from surveys | "80% said they'd pay $50" | Survey data overstates real WTP by 2–5x. Only transaction data counts. |
| Investment period undefined | "We'll need ~5 years to scale" | IRR requires a specific investment period. "~5 years" is not modelable. |
| Lump-sum costs | Single "total costs" figure | Cannot stress-test individual cost drivers. Cannot identify the structural fix. |
| Equilibrium not modelled | "The model shows year 5 profitability" | Without equilibrium period, can't calculate true IRR or assess long-term viability. |
