# At-Scale Operational Model (AOM) — Guide

Source: IVE Systems / reflect.site AOM guide (more recent than operational-model-guide.md)

---

## What It Is

The AOM is an operations-centric view of a scaled, functioning venture. It illustrates the journey the 4-D Products take to get to the customer — showing origination points and all key intermediaries involved in delivery.

The AOM is **unitized**: it delineates operational levels from the last-mile unit (serving end users) back to the head office, clarifying what must be pilot-tested before replication.

---

## Step 1: Identify Key People and Places

### People

Three customer-side stakeholder categories:

| Category | Definition |
|----------|-----------|
| **Customers** | The people who pay for the product |
| **Users** | The people who use the product |
| **Enablers** | People whose buy-in or support is required by the customer or user |

These roles can overlap or be distinct depending on the venture. A consumer product may have unified customer-users with no enablers. An educational product may have principals, teachers, students, parents — all separate roles.

### Places

Places span four functional categories:

| Category | What Happens Here | Examples |
|----------|------------------|---------|
| **Making** | Coordination, manufacturing, assembly, packaging, storage | Head office, factories, fulfilment centres, call centres |
| **Selling** | Distribution channels | Distributors, wholesalers, retailers, online platforms, payment systems |
| **Marketing** | Message dissemination and consumption | Media, homes, conferences, markets |
| **Using** | Where the user accesses the product | Homes, workplaces, organisational settings |

---

## Step 2: List 4-D Products

Copy the four product types directly from the Customer Transformation Model (CTM) without modification. This maintains traceability between the customer view and the operations view.

**Colour coding convention:**
- 🔴 Red — Working Products
- 🔵 Blue — Communications Products
- 🟢 Green — Payment Products
- 🟣 Purple — Partner Products

---

## Step 3: Map Business Flows and Bracket Operating Units

### Starting Positions

Anchor the map:
- **Left:** Venture head office
- **Right:** End-user home, with all associated people positioned adjacent

### Mapping Process — Work Backward (Right to Left)

Work from end user back to head office, in this order:

1. Working Products
2. Communications Products
3. Payment Products
4. Partner Products

**Layout convention:**
- Middle horizontal third: core working products
- Upper third: communications products
- Lower third: support products (payment, partner)

### Flow Visualisation

- Draw coloured arrows matching product colour, pointing toward the receiving entity
- When customers physically travel to a location: black arrow to place, then coloured arrow from place
- **Dashed lines** = digital flows
- **Solid lines** = physical movement
- Maintain spacing for clarity and flexibility

### Tracing Working Product Movement

For each working product component, trace in sequence:
1. Where it is **Used**
2. Where it is **Sold**
3. Where it is **Made**

For sequential movement, position new places adjacent to prior ones. Stack alternative channels vertically.

### Tracing Communications Product Movement

Identify where users encounter marketing messages and the technologies required (phone, TV, etc.). Consider distinct information needs at every intermediary place and for every person type. Connect with coloured arrows.

### Payment and Partner Products

Map after working and communications products are placed. Follow the same right-to-left logic.

---

## Step 4: Bracket Operating Units

### The Bracketing Process

Work right to left. Draw black boxes around operating units at each level.

**Last-Mile Unit (LMU) — start here:**
- Minimally includes: end-user home + the sales transaction entity
- Consider whether repair, after-sales, or local media operate at equivalent local scale
- Note area size and end-user count where possible

**Territory / Regional Unit:**
- Move upstream to the next product-flow participant
- Determine the territorial scope or quantity of LMUs supported
- Ensure box contains all subordinate units and indicates their quantity

**Head Office:**
- Continue until all people/places are bracketed

### How Many Levels?

The number of hierarchical levels depends on:

| Factor | More levels | Fewer levels |
|--------|------------|--------------|
| Geography | Large territory | Small / concentrated |
| Product type | Physical delivery | Digital |
| End-user interaction | Face-to-face intensive | Self-serve |

---

## Relationship to Other Tools

| Tool | View | Direction |
|------|------|-----------|
| **CTM** | Customer state changes | Outside-in (customer perspective) |
| **AOM** | Product delivery flows | Inside-out (operations perspective) |
| **Financial Model** | Cost and revenue | Derived from AOM resourcing |

**The AOM is built from the CTM:** products listed in the CTM become the products mapped in the AOM. Each flow in the AOM implies resources. Each resource has a cost. The AOM is the bridge between product design and the financial model.

---

## The Two-Pass Approach (C1 → C2)

Build the AOM in two passes. Do not label with product codes on the first pass.

**Pass 1 (C1) — plain language activities:**
Draw the diagram with activity descriptions in plain language on each flow:
- "Attracting claimants who are at the end of their rope"
- "Case analysis and valuation for claimant"
- "Cash payment for claim"

This forces clarity about what is actually happening before the formal labelling is applied. It also makes the diagram readable to people who don't know the IVE notation.

**Pass 2 (C2) — apply product labels:**
Replace plain language descriptions with formal product codes (WP1, CP2, PP1, etc.) that trace back to the CTM. The diagram structure does not change — only the labelling.

**Why two passes:** Founders who label first tend to design around the notation rather than around the actual operation. The activity description forces operational thinking first.

---

## Spatial Layout Conventions (from Calmly example)

### Horizontal axis — distance from head office
```
[HQ / Country Office] ←————————————————→ [Customer home]
       Far left                                  Far right
```

- Head office and central infrastructure: far left
- Intermediary platforms and channels: centre
- End users (customers, users): far right
- Third-party actors (courts, banks, partners): positioned by functional relationship

### Vertical axis — product type layer
```
Upper third:    Communications flows (blue dashed)
Middle third:   Working product flows (red dashed/solid)
Lower third:    Payment and partner flows (green/purple)
```

### Flow line conventions
- **Dashed lines** = digital flows (platform-mediated, remote)
- **Solid lines** = physical movement (person travels, physical product moves)
- **Arrow direction** = direction of product delivery (not always left-to-right — cash flows right-to-left)
- **Colour** = product type (red=WP, blue=CP, green=PP, purple=Partner)

### Operating unit boundary
- **Dashed rectangle** = LMU boundary. Everything inside replicates when you scale.
- HQ and central bank/infrastructure sit **outside** the LMU boundary
- Label the LMU boundary with: unit count at scale + TRM (target reachable market) per unit

**Calmly example:**
> "Last-Mile Operating Unit: 170 units (bounded around Country Courts), each with a TRM of 51,370 disputes"

This single label communicates the scaling logic: 170 replications of the same LMU = national coverage.

---

## Worked Example — Calmly (Debt Collection)

**Places:**
| Place | Position | Role |
|-------|----------|------|
| Calmly Country HQ + Debt Collection | Far left | Making: case management, legal ops |
| Calmly Digital Platform | Centre-left | Selling + Making: interface for all flows |
| Marketing Site | Top centre | Marketing: TV campaign, targeted comms |
| Calmly Bank | Bottom left | Payment: holds claim funds |
| Claimant Home | Right | Using: where claimant accesses the product |
| Defendant Home | Right (below claimant) | Using: where defendant receives comms |
| Small Claims Court | Bottom right | Using: legal escalation point |

**Flows (C2 labels):**
- CP1 (blue, upper): Marketing site → Claimant — attracting claimants at end of their rope
- WP1 (red): Platform → Claimant — case analysis and valuation
- WP2 (red): Platform → Claimant — contract for claim
- WP3 (red): Bank → Claimant — cash payment for claim
- CP2 (blue): Platform → Defendant — communication that claim is owned by a claim fund
- WP4 (red): Platform → Defendant — settlement offer
- WP5 (red): HQ → Court — legal escalation
- WP6 (red): HQ → Defendant — increasing settlement offer
- PP1 (green): Defendant → Calmly Bank — invoice for settlement

**Note on anti-customers:** Calmly has two customer tracks — Claimant (primary customer) and Defendant (anti-customer). The AOM shows both. Maximising value for the claimant requires reducing value for the defendant — this tension is made visible in the diagram by showing both flows simultaneously.

**Erik Simanis note (from working session):** "Show any flow of cash out of Calmly and cash into Calmly separately from the payment product." Cash flows (operational costs going out, revenue coming in) should be traceable independently of the product delivery flows.

---

## Common AOM Failures

| Failure | Signal |
|---------|--------|
| Left-to-right design | Built around what the venture can produce, not what the customer needs |
| Enablers treated as part of the venture | Hides partner friction and partner product costs |
| No operating unit brackets | Cannot identify what needs to be piloted or what replicates |
| Products not traced from CTM | Breaks traceability — operational components disconnected from customer need |
| Digital/physical flows not distinguished | Obscures cost structure and replication logic |
