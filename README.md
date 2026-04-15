# Surrendered Entrepreneurship — Venture Design Assistant

An AI-powered venture design tool that guides you through the engineering of a structurally viable business — before you spend a penny building it.

Built on the Integrated Venture Engineering (IVE) methodology — a systems engineering-based approach to venture design developed at Cornell University, the University of Oxford, and the University of Cambridge, in collaboration with Barclays, BMW, Disney, P&G, DuPont, Mars, and the International Finance Corporation. Combines engineering rigour with a contemplative approach to decision-making.

---

## What This Does

Most ventures fail not because of bad execution, but because of broken architecture — a structural flaw baked in at the design stage that no amount of effort can fix.

This assistant guides you through three foundational requirements that every viable venture must satisfy:

- **R1:** Can you make, sell, and deliver your product at a cost below what customers will pay?
- **R2:** Does your product remove the single biggest cost your customer is carrying?
- **R3:** Can you reach scale without running out of cash first?

If all three hold — verified through operational modelling and financial simulation — you have a venture worth building.

---

## Setup

### 1. Install Claude Code

Download from [claude.ai/download](https://claude.ai/download). You'll need a Claude Pro account ($20/mo).

### 2. Clone this repo

```bash
git clone https://github.com/tmth-studio/venture-assistant.git
cd venture-assistant
```

### 3. Open in Claude Code

```bash
claude .
```

That's it. The assistant is ready.

---

## Getting Started

Once you're in Claude Code, you have two paths:

**If you have a venture idea:**
```
/venture-design
```

**If you don't have an idea yet:**
```
/find-your-venture
```

**If you've completed the design and are ready to build:**
```
/venture-prototype
```

**Once the MVV is ready and you're starting sales:**
```
/venture-pilot
```

**To review your current progress:**
```
/f1-review
```

---

## How It Works

Your work is saved as real files in this folder — not trapped in a chat window. Every session picks up exactly where the last one left off.

**Design phase** (`/venture-design`) — 11 stages:

1. **PCO** — Define the Prime Commercial Opportunity
2. **Required Annual Revenue per Customer** — Calculate the reference point for all downstream cost testing
3. **R1** — Circumvent the at-scale cost bottleneck
4. **R2** — Eliminate the customer's value bottleneck
5. **R3** — Circumvent the scaling cash bottleneck
6. **R4–R10** — Solve the remaining seven requirements (adoption, retention, scaling, competition)
7. **CTM** — Map the Customer Transformation Model
8. **AOM** — Build the At-Scale Operational Model
9. **ARM** — Build the At-Scale Resourcing Model
10. **Logic Stress-Test** — Pre-simulation ratio summary, then challenge the three theorems
11. **Financial Simulation** — Calculate required price vs target price and FMOS

Each stage has a gate. Work doesn't progress until the gate is passed. If the financial simulation fails, the assistant routes you back to the specific requirement that's under-solved — not to the beginning.

**Prototype phase** (`/venture-prototype`) — Build the Minimum Viable Venture:

1. **Pre-work** — Assign team roles (Field Lead, accounting, sales), set up PM infrastructure
2. **Customer Journey** — Full experience from awareness through use, payment, return (co-creation, rapid prototyping, simulation)
3. **Brand** — Positioning, name, collateral, sales pitches
4. **Value Chain** — Suppliers, production, distribution, back office (minimum cap-ex)
5. **Management Systems** — KPI dashboard, financial tracking, reporting cadence
6. **HR** — Hire and train salespeople, run sales simulations
7. **Market Seeding** — Build first wave of customers during prototyping via seed groups

Gate: MVV systematised across all five components. Ready to start pilot sales.

**Pilot phase** (`/venture-pilot`) — Prove the operating unit works:

1. **Pilot Design** — Geography, configuration, timeline, monthly sales targets
2. **Launch** — First sales with the MVV
3. **Tracking** — Monthly operational, financial, and customer indicators vs. projections
4. **Model Evolution** — Test and iterate operational activities as you learn
5. **Go/No-Go Decision** — Scale / Pivot / Close Down, based on FMOS recalculated with real data

---

## Your Work

Everything you produce is saved here:

```
01-Venture_Thesis/        Your PCO and investment thesis
02-Requirements/          R1–R10 verification documents
03-Business_Architecture/ CTM, AOM, ARM
04-Financial_Simulation/  Financial model outputs
05-Ventures/              Active venture overview pages
06-Resources/             Methodology guides (read-only reference)
```

---

## The Methodology

This tool is built on the Integrated Venture Engineering (IVE) methodology, developed at the Built2Hold Program, Center for Global Sustainable Enterprise at Cornell University — and documented in academic and practitioner research including:

- *Engineering New Market Ventures for Profitability* (Simanis)
- *The Market Creator's Dilemma* (Simanis & Donohue, MIT Sloan Management Review)
- *Built to Hold* (Simanis, under review)

The contemplative dimension draws on Dethmer, Singer, Rubin, Cameron, and others in the tradition of presence-based work.

---

## Questions

This tool is part of the Surrendered Entrepreneurship programme. For support, contact tom@toughmindstenderhearts.com
