# VTS Requirements R1–R3 — Reference Guide

Source: IVE Venture Training Studio, July–August 2025 (Half-Solved + Cornell Market Creators Lab)

Covers the three requirements of Function 1 (Catalyze Value Surplus) in the Business Architecture Logic Model (BALM). These are the architectural foundation — if any of these are unresolved, nothing downstream holds.

---

## Architecture Hierarchy

Three nested levels, each more specific than the last:

**Core Business Architecture (CBA)**
Deep strategy that solves for the commercial viability of an industry. Sets the cost curve and the value curve — and their position relative to one another. Does not belong to any single company; it's the underlying logic that makes the industry work.

**Business Form Factor (BFF)**
The essential shape the product (product form factor) and operations (operational form factor) take, given a CBA. Shared by all companies competing in a market — this is the "default way" the product is made, sold, delivered, and paid for.

**Business Model**
A company's unique strategy for outcompeting other companies *within* a BFF. This is where differentiation lives — but only once the BFF is sound.

**The trap:** Most founders jump straight to business model thinking — "how do we compete?" — before diagnosing whether the default BFF is even viable for their context. If the BFF is broken, no business model can fix it.

---

## The Core Problem IVE Solves

**The Cost-to-Value Barrier**

> The current/default core business architecture/s cannot make, sell, deliver, and get paid for a core functionality or solve the social problem at a unit cost that is lower than the value the customer gets.

This is the structural reason new markets don't form. It's not about product quality or marketing. It's that the default way of doing things is too expensive for the target customer — even if the value is real.

The solution is to shift the cost curve *and* the value curve simultaneously by innovating a new CBA, which manifests as a new BFF.

**The design goal:** Create maximum "headroom" between the floor of the cost curve and the ceiling of the value curve. The greater the net customer value (value surplus), the faster the adoption rate. The greater the headroom, the more margin of safety to absorb higher-than-expected costs and lower-than-expected demand.

---

## IVE's 5 Design Principles

1. **Isolate the Prime Commercial Opportunity** — Reduce the venture search space to the broad use case that can most credibly generate at-scale revenues to pay back all required investment capital at a competitive rate of return.

2. **Architect for Factor-10 Performance Improvements** — Drive down the cost curve of the CBA by productizing solutions to 10 "first principles" commercial requirements codified in the BALM.

3. **Continually Assess for Robustness** — Use the "market creation margin" (the venture's margin of safety) to continuously assess ability to absorb higher-than-expected costs and lower-than-expected demand.

4. **Stress Test via Modelling and Simulation** — Use at-scale modelling to construct a financial simulation that stress tests the CBA, avoids dead-end traps, and prioritises experiments by impact.

5. **Bake in Design Synergies** — Solve for the high-level system form factor holistically so it solves all critical functional requirements as elegantly (as simply) as possible. Synergies at the system level eliminate big chunks of parts at once — lowering cost, improving performance, and increasing reliability.

**Why synergies matter:** Baking design synergies into the high-level form factor exerts an oversized impact on a system's effectiveness and efficiency because it eliminates parts all at once rather than one at a time.

---

## Function 1: Catalyze Value Surplus

**Value Surplus:** The "money" (monetizable value) left in the customer's pocket above and beyond the price they must pay for the product (to cover full unit costs, including competitive return on capital).

Function 1 sets the baseline for both the cost curve and the value curve, and their position relative to one another. It solves:
- The problem responsible for the *greatest share of at-scale costs* (R1)
- The problem responsible for the *greatest working capital requirement during scaling* (R3)
- The problem responsible for the *main source of value to the customer* (R2)

These are mathematical axioms: there is no possibility of surplus value if any of Function 1's requirements remain unresolved.

---

## Requirement 1: Circumvent At-scale Cost Bottleneck

**Definition:** Replace or bypass the operation in the "default" business form factor that contributes the greatest share of costs once the venture is operating at-scale. Its impact shows up on the *profit-and-loss statement* — it is an operating cost problem, not a capital problem.

This is an architectural-level intervention, not an efficiency improvement. "We'll be more efficient than the incumbent" is not a solution to R1.

---

### How to Solve R1 (4 Inputs)

**Input 1 — Conventional Business Form Factor**

The way a core functionality would typically be productized and made, sold, delivered, and paid for. It's inescapable that early ideas for solutions naturally re-purpose existing BFFs — this is the starting point for diagnosis, not the answer.

*Questions to surface the conventional BFF:*
- What industry classification would this innovation land in?
- How is this functionality typically packaged and sold?
- What's the gold standard way this problem would typically be solved?
- How would this be solved if money were no object?

**Input 2 — Critical Limiting Operation (CLO)**

An essential operation in the conventional BFF that disproportionately drives up cost and creates a cost threshold that exceeds target customers' ability or willingness to pay. It sits at the *architectural level* — a workflow or workstream made of multiple activities. It is tightly coupled: if you can eliminate or change it without affecting adjacent operations, it's not the CLO.

*Questions to surface the CLO:*
- What's different about the nature of this problem compared to the default case?
- What boundary conditions are being violated (competence, capacity, infrastructure)?
- Map the operational model: where is cost concentrated in Making, Selling, Delivering, or Getting Paid?

*Chunking the operational model:*
- **Making the product** (e.g., designer gown rental — large, rapidly depreciating inventory)
- **Selling the product** (e.g., fortified snack foods — high cost of changing customer evaluation/consumption patterns)
- **Delivering the product** (e.g., meal subscription boxes — overnight delivery drives up unit price)
- **Getting paid** (e.g., installment payment infrastructure)

**Input 3 — Workaround Theory of Change (ToC)**

The class of problem the CLO represents, and the theory most effective in explaining how to solve that class of problem. Abstracting the nature of the problem is essential — anchoring in a theory base supplies the logical criteria needed to evaluate solutions.

*Questions to surface the ToC:*
- Why does this operation exist?
- Why is it so costly?
- Who else deals with similar problems? How have they managed it?

**Input 4 — Workaround Strategy**

The best way to operationalise the Workaround ToC to neutralise or eliminate the need for the CLO. It should be framed as a *strategy* (not a specific product feature) — the next step is to productize it.

---

### Case Study: Lending to Informal Businesses

**Conventional BFF:** Small business banking loan (branch visit, agent evaluates creditworthiness via FICO + tax returns, loan priced to reflect default risk, monthly repayments).

**CLO:** Evaluating credit risk without FICO scores or tax returns dramatically increases the time and cost of due diligence — *and* the smaller loan sizes make this cost structure unworkable.

**Class of Problem:** Information asymmetry and individual-level risk.

**Workaround ToC:** Behaviour change theory — peer pressure and peer support alter people's repayment behaviour.

**Workaround Strategy:** Harness peer pressure/peer support to get people to practice good repayment behaviours.

**Productized R1:** Joint liability peer group loan.

---

### The Henry Ford Example (from Erik's notes)

Automotive technology was already being sold before Ford — but only to the wealthy, at ~$1,500. The conventional BFF (hand-crafted manufacture) created a cost floor that excluded the mass market.

Ford didn't improve the existing BFF — he invented a new one (assembly line manufacturing) that shifted both the cost curve and the production scale, bringing the price to ~$300. That's the R1 intervention: not "more efficient horse-drawn carriage building," but a new architecture.

---

## Requirement 2: Eliminate Customers' Value Bottleneck

**Definition:** Eliminate the target customers' biggest cost — measured in money (expended or foregone), fear (of failing to achieve the outcome), or stress (in managing current routines) — from their current routines for achieving the outcome of greatest importance that can be measurably impacted.

Sets the *height* of the customer value curve. Its impact shows up in the price customers will pay. Also sets the size of the addressable market. The two together determine the market creation margin.

**Prerequisite:** R1 must be productized first. The workaround strategy from R1 gives initial shape to the solution — this shape provides the first "handhold" for working through R2.

---

### Research Clusters (Before Starting R2 Research)

Before gathering customer data, define research clusters: broad groupings within the PCO that likely have different routines within the use case. They are *not* customer segments.

**Why:** Variables like urban/rural, grid access, org size, family type create "noise" in research. Clusters ensure representativeness across the PCO with the least amount of research — getting good quality data with least money and time.

*Key factors to consider:*
- Place profile: Urban / Rural / Peri-urban; Grid access; Coastal / Landlocked
- Profile: Org class (Micro / SME / Enterprise); Family type; Regulatory status; Age band

---

### Input 1 — High-Import Outcome + Attendant Routines

**High-Import Outcome (HIO):** The "job" that holds the greatest importance to the greatest number of actors in the PCO that can be meaningfully impacted and credibly delivered.

**The right way to state an outcome:** Clinical statement of *what* change the actor targets. No "how" or "why" — no adverbs, no adjectives (one exception: "X is Y").

- Wrong: "I hire high-quality employees efficiently" — imports a value proposition
- Right: "I hire employees" or "I fill employee vacancies"

**Why this matters:** Stating the outcome with adverbs or adjectives creates a circular argument — you're already claiming your solution is the answer before diagnosing the problem.

**Levels of outcome:** Routines making up an outcome can themselves become outcomes. Work top-down: start with a deliberately "too high" grand outcome, then isolate routines and costs until you reach the highest level where you can meaningfully move the needle.

**Attendant Routines:** What actors currently do, use, think, and feel to achieve success on the outcome. Four components:
- **DO** — the sequence of activities/actions
- **USE/BUY** — the tools and products deployed
- **THINK** — the concepts and ideas applied
- **FEEL** — the emotions that accompany the activities

**The challenge:** Routines are "routine" — people are in autopilot and unaware of most of what they do. The customer cannot tell you their routines directly. You have to observe and reconstruct.

---

### Input 2 — Key Monetizable Cost

**Definition:** The single greatest monetizable cost — in terms of money, fear, or stress — that the solution eliminates for the target customer.

Three types of cost/suffering:
- **Money Cost** — cash spent or foregone to achieve the outcome
- **Fear Cost** — the worry of failing to achieve the outcome given current routines
- **Stress Cost** — the difficulty of managing and executing current routines

**Monetizability varies:** Objective + outcome-fungible costs (extra cash the customer can spend on anything) are easiest to monetize. Subjective + outcome-neutral costs (relief from stress that doesn't improve performance) are hardest.

**Critical principle: benefits and "gain points" are not enough.**

"Better quality / faster / more convenient" makes a routine better but doesn't eliminate cost or suffering. Focusing on benefits works once a market exists and you're competing for position — but for new market creation, if you're not eliminating significant cost/suffering, you are not building a viable venture.

> "If I had asked people what they wanted, they would have said faster horses."

The customer CANNOT tell you their Key Monetizable Cost directly. They have already normalized the cost in their heads — they've built the best routine they can and don't have a view of what else is possible. What they *do* tell you is likely a small cost, not the key one.

**There should be a single key cost, not a basket.** At the architectural level, one focal cost per customer. Targeting multiple costs increases uncertainty, creates fuzzy KPIs, and diffuses the value proposition.

**Sizing the cost:** Benchmark against comparables. Calculate total dollar value assuming the solution is free.

---

### Input 3 — Efficacy ToC + Efficacy Strategy

**Efficacy ToC:** The parameter on which reduction/elimination of the key cost rests, and the theory most effective in explaining how to solve for that parameter.

**Efficacy Strategy:** The best way to operationalise the Efficacy ToC to achieve meaningful reduction in the key cost.

*Example (farmer revenues):*
- Money cost: Revenues 50% lower because farmers lack upfront cash for fertilizer and seeds
- Parameter: Repayment rates on loans dictate interest rate paid
- A $200 loan for fertilizer doubles farm output from $1,000 to $2,000; at 40% gross margin, an annual interest rate of 100% erodes all gains — so the efficacy problem is reducing the interest rate by improving repayment rates

---

### Research Methods for R2

Customer insights for R2 require multiple methods — you cannot get all necessary data from interviews alone. The bigger the problem targeted, the more embedded it is in current life, and the less visible it is to the customer.

| Data Type | Best Method |
|-----------|-------------|
| Basic facts | Survey / questionnaire |
| Simple activities | Phone/video interview |
| Feelings | In-depth 1:1 interview |
| Complex routines | Ethnographic observation, focus groups |

**Bad questions to avoid:**
- Leading questions: "Do you find that...?", "Is X important to you?", "Would you like...?"
- Yes/no questions: "Is it hard to...?", "Would you buy...?"
- Questions that can be answered by guessing what you want to hear

---

## Requirement 3: Circumvent Scaling Cost Bottleneck

**Definition:** Replace or bypass the operational procedure in the interim business form factor that commands the greatest amount of working capital as the venture scales. Its impact shows up on the *balance sheet* (cash flow timing), not the P&L.

Involves thinking through the timing of expenditures relative to the timing of revenue those expenditures generate. Goal: reduce significant expenditures that must be made long before they generate revenue.

This is distinct from R1 (which is about at-scale operating costs). R3 is specifically about the cash timing problem during the growth phase.

---

### What Is Working Capital?

Working capital is a "cash bridge." It covers shortfalls caused by a mismatch in the *timing* of expenditures and the revenue those expenditures enable.

It is **not** cash used to cover losses of an unprofitable business model searching for profitability. If the model is unprofitable, working capital doesn't fix it — that's an R1/R2 problem.

Working capital is expensive for new ventures: 25–40% APR because of higher risk. Because interest compounds, the cost of working capital can become very significant and quietly destroy margin of safety.

**Case study — off-grid rural solar:** Cost of working capital needed to cover the time lag between paying the OEM supplier for solar home systems and recouping money from customers over installment payments *increased the required price needed for profitability by over 50%.*

---

### How to Solve R3 (2 Inputs)

**Input 1 — Interim Scaling Cash Flows**

The broad staging of investments in resources needed to grow the venture's capacity and footprint to its at-scale level of activity.

Working backwards: What are the key resources needed to perform at-scale operations? What's involved in getting them up and running?

**The Operating Unit:** Scaling involves replicating a coherent bundle of activities and their commensurate resources needed to make and deliver four key products:
- **Working Product** — the core product/service
- **Communication Product** — how the venture sells and communicates
- **Payment Product** — how the venture gets paid
- **Partner Product** — how the venture works with partners

Every activity uses three kinds of resources:
- **Personnel** — people that perform activities
- **Durables** — resources that depreciate over a long period
- **Consumables** — resources used up at once

**Input 2 — Critical Limiting Operation II (Working Capital)**

The operational procedure that commands the greatest amount of working capital as the venture scales — i.e., requires significant upfront investment and time before it "pays for itself."

**Scaling ToC + Scaling Strategy:** The class of problem the Critical Working Capital Operation represents, and the best way to operationalise the Scaling ToC to circumvent or eliminate it.

*Quick diagnostic — map key activities and resources for each:*

| | Make (Working Product) | Sell (Comms Product) | Deliver (Partner Product) | Get Paid (Payment Product) |
|--|------------------------|---------------------|--------------------------|---------------------------|
| Key Activities | | | | |
| Key Resources | | | | |

---

## Diagnostic Summary: F1 Failure Signals

| Requirement | Strong Signal of Failure |
|-------------|--------------------------|
| R1 | "We'll be more efficient than the incumbent" — haven't identified the CLO, just optimising the existing BFF |
| R2 | Targeting a "basket of problems" or benefits/features, not a single key cost/suffering |
| R2 | Customer told you their key cost directly — it's likely a small cost, not the real one |
| R2 | Outcome statement contains adverbs or adjectives — you've imported a value proposition |
| R3 | Financial model shows profitability but ignores working capital cost — the gap erodes margin |
| All | "We've solved this on paper" without constructing the at-scale financial simulation |
