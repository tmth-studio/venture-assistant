# Prime Commercial Opportunity (PCO) — Methodology

Source: IVE Venture Training Studio, July 2025 (Half-Solved + Cornell University + INCOSE)

---

## Definition

> The **broadest possible use case** for a core functionality, OR the **broadest possible impact case** for a pervasive societal problem — that can most credibly generate the at-scale cash flows needed to **pay back all required investment capital at a competitive rate of return.**

The PCO is the starting point for the entire Design & Validate phase. Getting it wrong wastes everything that follows.

---

## Why PCO, Not a Beachhead Market

The beachhead market approach starts where the founder has contacts or familiarity — early adopters and low-hanging fruit. The problem: early adopters are not representative of the wider market. The venture ends up **trapped in a niche** — this is what *creates* the Geoffrey Moore chasm.

PCO inverts this. Start with the broadest credible opportunity, then design for it. Don't start narrow and hope to cross over.

**The key distinction:** Use/impact cases are not segments. A use case is the broadest application of the core functionality that shares the same core value. A segment is a subset of people within that case.

---

## Two Common PCO Traps

**Trap 1 — Import a solution:** Starting with "an app for X" or "a platform for Y." This bounds both the problem AND the solution before any design work. You lose the option space.

*Example of what NOT to do:* "Protective gear for firefighters" — that's already a solution form.
*Correct:* "People who face acute bodily risk in high-heat environments" — broadens the case.

**Trap 2 — Wrong level of specificity:** Use cases that are too narrow (effectively segments) or too broad (no shared enabling context). Looking for the highest level case where the **same core value holds**.

*Example:* "Parents looking for child-care on short notice" — this is right-sized. "Parents" is too broad. "Single mothers in Brooklyn looking for emergency child-care on Saturdays" is too narrow.

**Rule:** Not about precision at this stage — it's about directionality. There isn't a "right answer" — there are robust answers and limiting ones.

---

## The 4-Step PCO Process

### Step 1 — Define Investment Parameters

Before evaluating any use case, set the financial constraints. These define what "credible" means for the financial evaluation.

| Parameter | Definition |
|-----------|-----------|
| **Investment Period** | The time frame over which a return must be delivered on invested capital |
| **Target IRR** | The annualized return on investment over the investment period expected by investors |
| **At-scale Geography** | Territory or customer base to be served by the end of the investment period |
| **Relevant Industry** | General classification of goods/services to which the offering must belong |

These four inputs produce two outputs: At-scale Revenue Estimate, and At-scale Customer Base Estimate. These anchor everything in Step 4.

---

### Step 2 — Define the Core Functionality / Level the Societal Problem

Two paths depending on venture type:

**Path A (Technology / Product ventures):**
- **Core Functionality:** What the technology does (output) and how it does it (mechanism) at its most basic level
- **Key Attributes:** Qualities and features derived from the core functionality

*Example — Kitemill (airborne wind energy):*
- Core Functionality: Generates 70kW of energy by capturing high-altitude wind currents using an airborne kite the size of a truck
- Key Attributes: Stable/consistent energy supply, "green" energy, equivalent to 70 homes, highly mobile

The key attributes are what make different use cases valuable — they link to different customer pain points.

**Path B (Social / Impact ventures):**
- **Pervasive Societal Problem:** A persistent negative social or environmental condition experienced by a person or organization
- **Level-up:** Broaden the category of person and/or problem to increase the scope

*Example:*
- Too narrow: "Low-income black families suffer high rates of bankruptcy triggered by medical debt"
- Better: "Low-income families suffer high rates of bankruptcy triggered by medical debt"
- Better still: "Low-income families suffer high rates of bankruptcy"

Keep levelling up until you reach the broadest version where the core functionality can still credibly make an impact.

---

### Step 3 — Define Use Cases / Impact Cases

**Use Cases (Path A):** Broad application of the core functionality common to a group of people or organizations. Each use case provides **different core value** and/or presents **different enabling context**.

They are **not segments.** Segments are subsets within a use case.

*Example — Kitemill use cases:*
- B2B: Companies that operate temporary events or have moving job sites
- B2C: Rural villages with no/limited grid access
- B2G: Government military outposts and operations

**Impact Cases (Path B):** Broad group of people or organizations that experience knock-on effects emanating from the consequences of the social problem.

*Example — medical debt bankruptcy:*
- B2B: Companies who employ low-income people that go through bankruptcy (drop in employee performance)
- B2C: People/families that go through bankruptcy (money pressure)
- B2G: Schools serving children of families that go through bankruptcy (behaviour problems, low performance)

---

### Step 4 — Estimate & Evaluate

For each use case, run the PCO financial model:

**Customer Base Calculation:**
1. User Group TAM (total addressable market for this use case)
2. At-Scale Net Penetration Rate = Market Share × Industry Penetration Rate
3. At-Scale Customer Base = TAM × Net Pen Rate

**Required Price Calculation:**
1. Convert required investment capital to future value at end of investment period (FV = Investment × (1 + IRR)^years)
2. This future value = required company valuation
3. 90% of company value typically comes from terminal value; apply terminal discount rate (8%) to get terminal value
4. Free cash flow at end of investment period = Terminal Value × discount rate
5. Required Revenue = Free Cash Flow / Net Profit Margin (use 10% as default)
6. **Required Annual Price = Required Revenue / At-Scale Customer Base**

**The evaluation question:**
> "How does the urgency and importance of the use/impact case compare with the amount of money that users must spend? Are there value equivalents that can serve as comparisons?"

---

## The Evaluation Grid

Run the model across all use cases simultaneously and compare:

| | Use Case 1 | Use Case 2 | Use Case 3 |
|--|-----------|-----------|-----------|
| TAM | 100,000 | 600,000 | 5,000 |
| Net Pen Rate | 2.5% | 2.5% | 2.5% |
| At-Scale Customer Base | 2,500 | 15,000 | 125 |
| Required Annual Price (avg) | $12,469 | $1,039 | $623,427 |

Then ask: Given the nature of the use case, is this required price credible? Is there urgency/pain that could justify it? What are the value equivalents?

Use Case 3 above ($623k/year) is almost certainly non-viable — the required price far exceeds any plausible WTP. Use Case 2 ($1,039/year) may be viable if the customer pain is real.

The PCO is the use case with the **most credible gap between required price and target price** — i.e., the highest potential market creation margin.

---

## Gate: Market Creation Margin > 30%

The PCO exercise is complete when you've identified a use case where:
- The required annual price is credibly below what customers would pay
- The gap (market creation margin) is >30%

This is the "Market Potential > Required Investment Capital" gate in the overall process diagram.

A case that fails this screen should be dropped before any design work begins. No amount of clever architecture can save a use case where the required price structurally exceeds WTP.

---

## PCO in the Overall Process

```
Screen Opportunity Landscape
  → [Gate: Market Potential > Required Investment Capital]

Solve Cost-to-Value Barrier (BAP / Business Form Factor design)
  → Simulate At-scale Operations
  → Assess Financial Margin of Safety
  → [Gate: Market Creation Margin > 30%]

Build & Test Key Components
  → Integrate & Test Key Operations
  → Simulate At-scale Operations
  → [Gate: NPV > Hurdle Rate]
```

The PCO defines the "broadest credible" starting point. The Business Form Factor (all 13 BAP requirements) then designs around the PCO to solve the cost-to-value barrier. The financial model then proves the margin of safety.

---

## Diagnostic Questions

When a founder presents their target market or customer segment, run the PCO test:

1. "Is this a use case or a segment? What's the broadest version of this use case where the same core value holds?"
2. "What are the investment parameters? What IRR do you need to hit, and over what period?"
3. "Have you modelled the required price for this use case? Is that credible given the pain?"
4. "Have you compared 3+ use cases against each other? Why is this one the PCO?"
5. "Is this a beachhead choice — familiar, easy, close to your network — or is it actually the broadest credible opportunity?"

**The beachhead trap question:** "Would you stay in this use case forever, or is it 'just a starting point'? If just a starting point — are you designing yourself into a niche?"
