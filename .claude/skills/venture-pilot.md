# /venture-pilot

Guide a founder through the Venture Pilot — launching sales with the MVV, tracking whether the operating unit can meet the targets required for profitability, and reaching a Go/No-Go decision.

**What this phase is:** A soft launch. You are starting sales in a limited area to demonstrate that the business can grow and hit the key operational assumptions required for profitability. The challenge is that the business is live — big changes, particularly those that affect what customers get, pay, or hear, are often not possible mid-pilot.

**What this phase is not:** A finished business. The operational model will not work out exactly as planned. Clear-cut signals of what's working will not always be available. Expect to finish the pilot with a business that works, not one that is ready to simply cut and paste into another area.

---

## Before You Begin

Confirm the MVV is complete — all five components systematised and the MVV Readiness Check passed. If not, redirect to `/venture-prototype`.

Load the key reference numbers from the design:
- Required ARPC
- Target Price
- PVC (direct unit cost)
- FMOS score
- Key operational assumptions from the financial model (conversion rate, cost per acquisition, retention rate, etc.)

**Ask:**
> "Have you started any pilot sales, or are we launching now?"

Establish current position and resume from there.

**Folder setup:** `05-Ventures/[Venture Name]/Pilot/`

---

## STAGE 1: Pilot Design

**Teach this:**
> "Before you start sales, you need to design the pilot. This means choosing where you will sell, deciding whether you are running one configuration or testing two in parallel, and setting the targets you will track. The pilot is designed around the operating unit — the LMU. It may be a full unit, or a proportionally scaled subset."

**Work through:**

1. **Pilot geography** — Where, specifically, are you launching? One area or multiple? If multiple: is it to test market diversity, or to run two different customer journey configurations in parallel?

2. **Configuration choice** — Are you running one version of the customer journey, or do you have two equally plausible configurations (e.g., two price structures, two delivery models) that need to be tested in separate sites? If two: they must be geographically separated — you cannot test competing configurations in the same community.

3. **Pilot scope** — Is this a full LMU or a proportionally scaled subset? If a subset, scale all operational and financial targets proportionately.

4. **Timeline** — Minimum pilot duration to observe:
   - Repeat purchasing (for products that aren't one-time use)
   - Customer satisfaction over time
   - New customers from positive word of mouth
   - Seasonality effects
   
   Typically 9–18 months. Set the minimum upfront — not as a constraint, but as a commitment to run the test long enough to be meaningful.

5. **Sales targets** — Monthly sales and revenue targets that form a credible path to the steady-state penetration rate from the financial model. Don't set targets after you've seen the first month's results.

**Gate:** Pilot geography defined, configuration(s) confirmed, scope and timeline set, monthly sales targets set before launch.

Save to `05-Ventures/[Venture Name]/Pilot/01-Pilot-Design.md`.

---

## STAGE 2: Launch

**Teach this:**
> "Launch is not an event. It is the first day of a live business. The seed groups are warm. The team is trained. The MVV is ready. The dashboard is built. Now you sell."

**At launch, confirm:**
- Seed group has been contacted and invited to purchase
- Sales team is in field with collateral and trained pitches
- Management systems are live — dashboard, reporting, cash account
- Everyone on the team knows what success looks like in week one

**Contemplative prompt:**
> "Before you launch — sit with the moment. This is the transition from designing a venture to running one. What do you need to let go of to operate from here?"

**Gate:** First sales call made. Dashboard recording. Pilot is live.

Save to `05-Ventures/[Venture Name]/Pilot/02-Launch.md`.

---

## STAGE 3: Tracking

**Teach this:**
> "The pilot is a test of your operational and financial assumptions. Not your product. Not your team. The assumptions you made in the design — about conversion rates, retention, cost per unit at scale, repeat purchase frequency — these are what the pilot is testing. Your job is to measure relentlessly and diagnose honestly."

**Track monthly:**

**Operational indicators:**
- Are marketing activities generating the expected number of sales follow-ups?
- Are the frequency and duration of customer touchpoints consistent with projections?
- Can salespeople support the required number of clients?
- Are customer conversion and retention rates consistent with steady-state projections?

**Financial indicators:**
- Actual PVC vs. modelled PVC
- Actual RC vs. modelled RC
- Monthly P&L: revenue, direct costs, gross margin
- Cash flow: when money comes in vs. when it goes out

**Customer indicators:**
- Do customers match the profile of who you expected to attract?
- Are customers using the product as envisioned?
- What do customers think about the product? (Structured feedback, not impressions)
- Are new customers coming in from word of mouth?

**Reporting format — update monthly:**
```
## [Month] — [date]

### Operational
- Conversion rate: [actual] vs. [target]
- Retention rate: [actual] vs. [target]
- [Other KPIs]: [actual] vs. [target]

### Financial
- Revenue: [actual] vs. [target]
- PVC: [actual] vs. [modelled]
- Gross margin: [actual] vs. [modelled]
- Cash position: [actual]

### Customer
- Customer profile match: [yes/partial/no] — notes
- Usage as envisioned: [yes/partial/no] — notes
- Word of mouth signals: [notes]

### Key finding this month
[One sentence: what did you learn that matters most?]

### Action for next month
[One specific operational change being tested]
```

Save each month to `05-Ventures/[Venture Name]/Pilot/03-Monthly-Tracking.md`.

---

## STAGE 4: Evolving the Model

**Teach this:**
> "The pilot is a soft launch, not a locked deployment. Operational activities — how you acquire customers, how you deliver, how you handle payment — should be constantly monitored and tested as you learn what works. What you cannot significantly change mid-pilot are the things that directly affect what customers get, pay, or hear. Those were set in the MVV. Everything behind the customer experience can be evolved."

**What can be adjusted mid-pilot:**
- Sales tactics and acquisition strategies
- Supplier choices
- Internal production and distribution processes
- Back-office systems
- Team structure and roles

**What cannot be significantly changed without stopping and re-starting:**
- What the customer receives
- What the customer pays
- What the customer is told (brand, pitch, positioning)

**Each operational change should be tracked:**
```
## Operational Change — [date]
What changed: 
Why: 
Expected effect: 
Measured effect (update after 4 weeks): 
```

**Contemplative prompt:**
> "When you get a result you didn't expect — resist the urge to explain it away. Sit with it. What is it telling you about an assumption you were carrying?"

Save to `05-Ventures/[Venture Name]/Pilot/04-Model-Evolution.md`.

---

## STAGE 5: Go/No-Go Decision

**Teach this:**
> "At the end of the pilot, one question determines everything: did the operating unit demonstrate that it can meet the key operational and financial targets required for profitability? Not perfection. Not exactly as modelled. Demonstrated movement toward those targets with a credible path to reaching them at steady state."

**Before making the decision, recalculate FMOS with actual pilot data:**
- Actual PVC
- Actual RC (extrapolated to steady state)
- SC (actual pre-launch and scaling costs)
- FMOS = (Target Price − Required Price) / Required Price × 100

**The three outcomes:**

---

### Scale
**Condition:** FMOS ≥ 60% with actual data. Operational indicators trending toward steady-state targets. Customer satisfaction and retention demonstrated.

> "The business works. The next step is expanding across the target geography. This requires a replication plan — how do you add operating units without founder dependency? Run `/venture-build` to begin."

Save decision and rationale to `05-Ventures/[Venture Name]/Pilot/05-GoNoGo-Decision.md`.

---

### Pivot
**Condition:** FMOS < 60% or key operational assumptions not met — but a specific, diagnosable root cause exists and a restructured model is plausible.

**Diagnose before deciding:**
- PVC higher than modelled → CLO not fully eliminated → return to R1 and rebuild Customer Journey and Value Chain
- Conversion rate too low → adoption barriers not addressed → return to R5 and rebuild sales approach
- Retention lower than expected → switching cost not accumulating → return to R6 and rebuild product
- Target price not holding → KMC smaller than modelled or willingness to pay lower → return to R2

> "The pilot has not demonstrated viability — but there is a diagnosable path to restructuring. The next step is: return to the specific requirement that's broken, redesign the working concept, rebuild the MVV, and launch a new pilot. This is not starting over. It is a targeted correction based on real data."

**A pivot is only valid if:**
1. The root cause is specific — not "the model didn't work overall"
2. A restructured design can plausibly close the gap
3. There is appetite (investment, team, time) to run a second pilot

Save pivot rationale and redesign plan to `05-Ventures/[Venture Name]/Pilot/05-GoNoGo-Decision.md`.

---

### Close Down
**Condition:** FMOS < 60%, no diagnosable restructuring path — or the root cause is structural and cannot be addressed without rebuilding from the PCO.

> "The pilot has not demonstrated viability, and there is no credible path to restructuring the concept within the current framing. This is not failure of execution. It is the design process working as intended — surfacing a structural flaw before significant capital was deployed at scale."

Save close-down rationale to `05-Ventures/[Venture Name]/Pilot/05-GoNoGo-Decision.md`.

---

## Progress Tracking

After each stage, append to `05-Ventures/[Venture Name]/Pilot/Pilot-Progress.md`:

```markdown
## [Stage name] — [date]
[One sentence: the key finding or decision reached]
[FMOS: ___% (actual / projected)]
```

---

## The Surrender Lens

At any stage, if the founder is:
- Changing what customers get, pay, or hear mid-pilot without stopping → name what this does to the data
- Interpreting mixed signals as success → press for the specific metric that isn't moving
- Running the pilot too short to observe repeat purchasing or seasonality → hold the timeline gate
- Making the Go/No-Go decision on instinct rather than data → return to the monthly tracking
- Diagnosing "the team didn't execute" when the model may be broken → separate execution variance from structural variance
- Pivoting without a specific, diagnosable root cause → a vague pivot is not a pivot, it is an avoidance of the real question
- Reluctant to close down when the data is clear → name what continuing costs: capital, time, and the opportunity it forecloses

The pilot ends when the data says what it says. Not when it says what was hoped for.
