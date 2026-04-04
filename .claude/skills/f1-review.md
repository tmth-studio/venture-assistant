# /f1-review

Review the founder's current F1 progress. Read their saved work, surface what's verified, what's weak, and what needs redesign before proceeding.

---

## Step 1: Read Existing Work

Read all of the following that exist:

- `01-Venture_Thesis/PCO.md`
- `02-Requirements/R1/R1-Verification.md`
- `02-Requirements/R2/R2-Verification.md`
- `02-Requirements/R3/R3-Verification.md`
- `03-Business_Architecture/CTM/CTM.md`
- `03-Business_Architecture/AOM/AOM.md`
- `03-Business_Architecture/ARM/ARM.md`
- `04-Financial_Simulation/Simulation.md`
- `03-Business_Architecture/Venture_Design_Progress.md`

If a file doesn't exist, note that stage as not yet started.

---

## Step 2: Assess Each Stage

For each completed stage, assess against its gate criteria:

### PCO
- Is there a clear one-sentence PCO statement in the format: [Population] experiencing [cost] — addressable at scale because [reason]?
- Is the Required Annual Revenue per Customer calculated?
- Is it a plausible fraction of the customer's annual loss?

**Status:** Verified / Weak / Not started

### R1
- Is the CLO in the conventional model clearly identified?
- Is there a specific design choice that eliminates it (not optimises it)?
- Is there an order-of-magnitude cost estimate?
- Is there a theorem — a chain of logic grounded in evidence?
- Is the critical assumption named?

**Status:** Verified / Weak (specify what's missing) / Not started

### R2
- Is the Key Monetisable Cost specific and quantified?
- Is the target price calculated (20–30% of KMC)?
- Does the target price cover the Required Annual Revenue per Customer?
- Is there a theorem for why customers will pay?
- Is the critical assumption named?

**Status:** Verified / Weak (specify) / Not started

### R3
- Is the scaling cost bottleneck clearly identified?
- Is there a design choice that addresses the timing gap?
- Is there a working capital estimate at 50–100 customers?
- Is there a theorem for why the design choice holds at scale?

**Status:** Verified / Weak (specify) / Not started

### CTM
- Is there a complete CTM for the primary customer type?
- Are all four phases covered (becoming, using, paying, returning)?
- Is each phase transition assigned to a 4-D product?

**Status:** Verified / Weak / Not started

### AOM
- Are all People, Places, and Flows mapped?
- Are Operating Unit levels defined with at-scale volumes?

**Status:** Verified / Weak / Not started

### ARM
- Is the structure defined for LMU, Territory, and Head Office?
- Is each product component assigned direct personnel, activities, support HR, and resources?

**Status:** Verified / Weak / Not started

### Logic Stress-Test
- Have all three theorems (R1, R2, R3) been stated and challenged?
- Is each critical assumption named and defensible?

**Status:** Verified / Weak / Not started

### Financial Simulation
- Have costs been applied to the ARM?
- Is the required price calculated?
- Is FMOS ≥ 60%?

**Status:** Passed (FMOS: X%) / Failed (FMOS: X%) / Not started

---

## Step 3: Produce the Review

Present findings in this format:

```
## F1 Review — [date]

### What's solid
[List verified stages with one sentence on why they hold]

### What needs work
[List weak stages with specific gaps — e.g., "R1 theorem is missing the critical assumption"]

### What to do next
[The single most important thing to address before proceeding]

### Overall status
[Ready to proceed to F2 / F1 nearly complete — address X first / Significant redesign needed — start with Y]
```

---

## Step 4: Offer to Work on the Weakest Point

Once the review is presented:

> "Want to work on [the weakest point] now? Or is there a specific stage you want to revisit?"

If the founder wants to proceed: pick up from the appropriate stage in `/venture-design`.

---

## What This Is Not

- Not a validation exercise — if something is weak, say so directly
- Not a summary of what the founder said — assess it against the gate criteria
- Not a reason to skip ahead — a weak R1 theorem means R1 is not complete, regardless of how much work has been done

The gate criteria exist for a reason. Soft-passing them just moves the structural problem downstream.
