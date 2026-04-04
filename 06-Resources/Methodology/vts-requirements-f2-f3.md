# VTS Requirements F2 & F3 — Reference Guide

Source: IVE Venture Training Studio (Half-Solved + Cornell MCL + INCOSE), July–November 2025. Primary sources: INCOSE Webinar (May 2025, BALM table), WAVE Ventures Studio (Nov 2025, updated terminology).

Covers Function 2 (Normalize Customer Routines, R4–R7) and Function 3 (Dictate Competitive Landscape, R8–R10) in the Business Architecture Logic Model (BALM). These requirements are solved after Function 1 (R1–R3) and are addressed through the Core Business Outputs (Communications Product, Payment Product, Partner Product) and by shaping the competitive environment.

For R1–R3, see `vts-requirements-r1-r3.md`.

---

## Why F2 and F3 Are Non-Negotiable

**Function 2 (Normalize Customer Routines)** solves an inescapable problem: customers and gateway partners will not have the routines, mindsets, or purchasing behaviors needed to value, use, and buy a new-to-world product. This is not a marketing problem. It is an architectural one — the solution must be embedded in the product form factor.

**Function 3 (Dictate Competitive Landscape)** shapes the market's competitive dynamics on terms the venture is poised to win — before competitors arrive. This is not about out-executing competitors; it is about designing the rules of the game.

Both functions operate on the same principle as F1: the solution must be **productized** — built into the product form factor so that the operational cost of addressing it is eliminated or minimized.

---

## Function 2: Normalize Customer Routines

Function 2 has four requirements. Their strategies are named: Attraction Strategy (R4), Adoption Strategy (R5), Amortization Strategy (R6), Integration Strategy (R7).

---

### Requirement 4: Eliminate Customers' Want Block

**Definition:** Eliminate the greatest barrier preventing target customers from *wanting* the new functionality — even before they have tried it. The Want Block is the gap between what customers currently want (based on existing routines) and wanting what the new product offers.

This operates at the level of awareness and desire, not usage. Customers who have never experienced the functionality cannot know they want it — and may actively resist it because it conflicts with current routines or beliefs.

**Strategy name:** Attraction Strategy

---

#### How to Solve R4

**Input 1 — Key Customer Want Block**

The most significant barrier to target customers wanting to engage with the new functionality. Common forms:
- **Ignorance** — customers don't know the problem is solvable (or that the problem exists at its real scale)
- **Skepticism** — customers don't believe the claimed outcome is achievable
- **Identity conflict** — the product conflicts with how customers see themselves or their current practices
- **Inertia** — customers are locked into current routines by habit, social norms, or sunk cost

*Questions to surface the Want Block:*
- Why do people in this segment *not* want what you're offering, even if they have the problem?
- What would someone in this segment have to believe to find this offer compelling?
- What's the biggest single thing standing between a customer and wanting to try this?

**Input 2 — Attraction Theory of Change + Strategy**

The Attraction ToC identifies the class of problem the Want Block represents and the theory explaining how to address it. The Attraction Strategy is the best operationalisation of that ToC, productized into the Communications Product.

*Common ToC categories for Want Blocks:*
- Behavior change theory (if the block is habit or inertia)
- Social proof / diffusion of innovation theory (if the block is skepticism in a community)
- Education and awareness theory (if the block is ignorance)

**Productization:** The Attraction Strategy must be embedded in the Communications Product — not addressed through ongoing sales or marketing spend. If the venture needs a continuous sales effort to overcome the Want Block, the architecture is not yet solved.

---

### Requirement 5: Eliminate Customers' Use Block

**Definition:** Eliminate the greatest barrier preventing target customers from *using* the new product successfully and consistently after they have decided to try it. The Use Block is the gap between a customer's decision to try and their ability to derive the promised value.

Customers often fail to derive value from new products not because the product is broken, but because their existing routines, skills, or contexts are incompatible with the product's requirements.

**Strategy name:** Adoption Strategy

---

#### How to Solve R5

**Input 1 — Key Customer Use Block**

The most significant barrier to consistent, successful use. Common forms:
- **Skill gap** — customers lack the knowledge or skill to use the product correctly
- **Routine incompatibility** — the product requires behavior changes that conflict with deeply embedded routines
- **Infrastructure gap** — customers lack the supporting resources the product assumes (internet, electricity, time)
- **Trust gap** — customers don't yet trust the product enough to rely on it for the outcome

*Questions to surface the Use Block:*
- What would cause a customer who wants to try the product to fail in the first 30 days?
- What does the product assume about customers' current capabilities, infrastructure, or routines that may be wrong?
- Where in the use cycle is the drop-off — and what does that tell you about the barrier?

**Input 2 — Adoption Theory of Change + Strategy**

The Adoption ToC identifies the class of problem the Use Block represents. The Adoption Strategy eliminates or reduces the Use Block through product design, not ongoing customer support.

*Examples:*
- If the Use Block is skill gap: design the product to make the skill unnecessary (automate it), or make the learning curve negligible
- If the block is routine incompatibility: redesign the product form factor to slot into existing routines rather than replacing them
- If the block is trust gap: design the product to deliver a quick, visible, unambiguous win early in the customer journey

**Productization:** An Adoption Strategy that requires expensive onboarding, training, or hand-holding is not solved at the architectural level. The product form factor must eliminate the need for these.

---

### Requirement 6: Eliminate Customers' Buy Block

**Definition:** Eliminate the greatest barrier preventing target customers from *paying* for the product at the price required for commercial viability. The Buy Block is distinct from the Want Block and Use Block — a customer can want the product and use it successfully but still be unable or unwilling to pay for it.

Common sources: cash flow timing (the customer can afford it but not all at once), perceived risk (the customer is uncertain of value and won't pay until proven), or payment infrastructure mismatch (the customer cannot transact in the required way).

**Strategy name:** Amortization Strategy

---

#### How to Solve R6

**Input 1 — Key Customer Buy Block**

The most significant barrier to customers paying the required price. Common forms:
- **Liquidity constraint** — customers have the income to pay but not the cash at the moment of purchase
- **Risk-adjusted value gap** — customers need the product to "prove itself" before committing full price
- **Payment infrastructure gap** — the required payment mechanism doesn't fit customers' existing financial behavior
- **Price perception gap** — the price exceeds customers' reference point even if it represents good value

*Questions to surface the Buy Block:*
- What stops customers from paying the required price *even when they want the product*?
- Is this a cash timing problem, a risk problem, or a structural inability to transact?
- What payment mechanism do customers currently use for similar expenditures?

**Input 2 — Amortization Theory of Change + Strategy**

The Amortization ToC identifies the class of problem the Buy Block represents. The Amortization Strategy eliminates or reduces the Buy Block through the Payment Product design.

*Examples:*
- If the block is liquidity: installment payment, pay-per-use, or subscription models that spread cost over time
- If the block is perceived risk: results-based or try-before-you-buy payment structures
- If the block is payment infrastructure: design payment mechanism to use existing infrastructure (mobile money, community savings groups, employer payroll)

**Productization:** The Payment Product must be designed to eliminate the Buy Block structurally. A payment model that requires constant credit risk assessment or manual collections has not solved R6 at the architectural level.

---

### Requirement 7: Neutralize Gateway Partner / Customer Friction

**Definition:** Eliminate the greatest barrier that key gateway partners (or secondary customer segments) face in integrating the new product into their existing workflows and routines. Gateway partners are actors whose participation is essential for the venture to reach end customers at scale — and who will have their own Want, Use, or Buy Blocks.

This requirement recognizes that most market-creating ventures depend on partners who are neither the end customer nor part of the venture's own operations. These partners must be treated as a second design problem, not an afterthought.

**Strategy name:** Integration Strategy

---

#### How to Solve R7

**Input 1 — Key Gateway Partner + Their Key Friction**

Identify the most important gateway partner and their most significant barrier to integration. Common friction types:
- **Operational disruption** — integrating the product requires changing existing workflows in costly ways
- **Revenue risk** — the partner fears the product will cannibalize existing revenue streams
- **Accountability risk** — the partner is asked to take on risk or responsibility they cannot manage
- **Incentive misalignment** — the partner's current incentives don't reward the behaviors the venture needs

*Questions to surface the Gateway Partner Friction:*
- Who must say "yes" for the venture to reach customers at scale?
- What does that partner currently have to do/give up to integrate the venture's product?
- What does the integration ask the partner to risk or change?
- What would make the integration invisible to the partner's existing operations?

**Input 2 — Integration Theory of Change + Strategy**

The Integration ToC identifies why the friction exists. The Integration Strategy eliminates or neutralizes it through the Partner Product design.

*Examples:*
- If the friction is operational disruption: design the Partner Product to slot into existing workflows without requiring changes
- If the friction is incentive misalignment: design a revenue share or incentive structure that aligns partner behavior with venture success
- If the friction is accountability risk: design accountability mechanisms that protect the partner while maintaining quality standards

**Productization:** The Partner Product must eliminate the friction at the architecture level. A partnership model that requires constant relationship management, renegotiation, or incentive adjustment has not solved R7.

---

## Function 3: Dictate Competitive Landscape

Function 3 has three requirements. Their strategies are named: Lock-in Strategy (R8), Lock-out Strategy (R9), Leverage Strategy (R10).

Function 3 is designed at the same time as the Core Business Outputs, but its solutions operate at a longer time horizon. The goal is to shape the market's competitive structure on terms the venture is positioned to win.

---

### Requirement 8: Create Customer Store of Value

**Definition:** Create a mechanism through which the customer's use of the product generates a growing store of value — financial, relational, or informational — that increases their switching cost and deepens their dependency on the venture over time.

This is not about "loyalty programs." It is about designing the product so that continued use makes the customer progressively more invested in the venture's ecosystem.

**Strategy name:** Lock-in Strategy

---

#### How to Solve R8

**Input 1 — Customer's Highest-Value Transferable Asset**

The resource or outcome of greatest value that customers accumulate through product use, which could in principle be taken elsewhere — and which the Lock-in Strategy aims to make increasingly costly to transfer.

Common forms:
- **Financial store** — savings, credit history, investment returns accumulated through the product
- **Relational store** — network, community, or social capital built through the product
- **Data store** — behavioral data, health records, performance history that has value to the customer
- **Skill store** — capabilities developed through product use that depend on the venture's platform

*Questions to surface the customer asset:*
- What does the customer accumulate over time by using the product?
- What would they lose if they stopped using the product?
- What would they need to rebuild if they switched?

**Input 2 — Lock-in Theory of Change + Strategy**

The Lock-in ToC identifies the mechanism through which switching cost compounds over time. The Lock-in Strategy productizes this mechanism.

*Examples:*
- Credit history built through the venture's loan product (switching means losing history with a new lender)
- Personalization data that makes the product progressively more effective for the individual customer
- Network effects where value increases as the customer's contacts also use the product

---

### Requirement 9: Control a Key Scarce Resource

**Definition:** Establish control over a resource that is essential for competitors to operate in the same market — and that is genuinely scarce, meaning supply cannot easily be expanded by a well-capitalized competitor.

This is the venture's primary Lock-out mechanism. By securing control of the key scarce resource, the venture raises the cost of competitive entry and limits the competitive options available to followers.

**Strategy name:** Lock-out Strategy

---

#### How to Solve R9

**Input 1 — Key Scarce Resource**

The resource that would most constrain a competitor attempting to replicate the venture's model. Common types:
- **Physical scarcity** — land, spectrum, natural resource
- **Regulatory scarcity** — licenses, approvals, accreditations that are limited in number
- **Relational scarcity** — exclusive partnerships, relationships, or community trust that cannot be replicated through capital
- **Data scarcity** — proprietary data sets that would take years to accumulate
- **Talent scarcity** — rare skills or knowledge in short supply

*Questions to surface the scarce resource:*
- What would a well-funded competitor need that it couldn't simply buy or build?
- What takes years or relationships to acquire — not just money?
- What is the single most constraining resource for operating in this market?

**Input 2 — Lock-out Theory of Change + Strategy**

The Lock-out Strategy defines how the venture acquires and maintains control of the scarce resource — and at what point in the venture's development this control is established.

**Critical timing principle:** Control must be established before competitors are motivated to contest it. If the venture waits until the market is proven, the scarce resource may already be contested or captured.

---

### Requirement 10: Eliminate Key Input Replaceability

**Definition:** Structure the venture's supply chain and key input relationships so that switching to alternative suppliers is costly or impossible — either for the venture's inputs or for the venture's customers' inputs to their own operations.

Where R9 is about controlling a resource competitors need, R10 is about controlling the inputs the venture itself depends on — and designing the product so that the value chain cannot easily route around the venture.

**Strategy name:** Leverage Strategy

---

#### How to Solve R10

**Input 1 — Key Input + Current Replaceability**

The most critical input to the venture's operations and how easily it can currently be substituted. Common types:
- **Raw materials or components** with multiple suppliers
- **Technology platforms** where lock-in varies
- **Human capital** — specialized labor or knowledge
- **Distribution channels** — routes to market that are controlled by third parties

*Questions to surface key inputs:*
- What would stop the venture's operations if it disappeared tomorrow?
- Where in the supply chain does the venture have the least control?
- What input is most at risk of being captured by a competitor or redirected by a partner?

**Input 2 — Leverage Theory of Change + Strategy**

The Leverage Strategy designs the venture's relationship with key inputs to minimize replaceability risk — either by locking in preferential access to the best inputs, or by designing the product architecture so that the venture becomes a non-optional node in the value chain.

*Examples:*
- Exclusive offtake agreements with key suppliers before the market scales
- Designing the product architecture so that key input suppliers become dependent on the venture as their primary route to market
- Vertical integration of the most critical and vulnerable input

---

## BALM Requirements Summary: F2 and F3

| Req | Function | Name | Strategy Name | Solves |
|-----|----------|------|---------------|--------|
| R4 | F2 | Eliminate Customers' Want Block | Attraction Strategy | Why customers don't want the product |
| R5 | F2 | Eliminate Customers' Use Block | Adoption Strategy | Why customers fail to use it successfully |
| R6 | F2 | Eliminate Customers' Buy Block | Amortization Strategy | Why customers can't or won't pay |
| R7 | F2 | Neutralize Gateway Partner Friction | Integration Strategy | Why gateway partners won't integrate |
| R8 | F3 | Create Customer Store of Value | Lock-in Strategy | Build switching costs through compounding value |
| R9 | F3 | Control Key Scarce Resource | Lock-out Strategy | Raise barriers to competitive entry |
| R10 | F3 | Eliminate Key Input Replaceability | Leverage Strategy | Control the venture's critical supply chain |

---

## Diagnostic: F2 and F3 Failure Signals

| Requirement | Strong Signal of Failure |
|-------------|--------------------------|
| R4 | "We'll educate the market" — ongoing marketing spend to overcome Want Block, not productized |
| R5 | High churn in pilot despite customers saying they want the product |
| R5 | Adoption requires expensive onboarding or training at scale |
| R6 | Payment model requires individual credit assessment or manual collections |
| R6 | Customers want the product but "can't afford it right now" — structural Buy Block not solved |
| R7 | Partnership agreements require renegotiation every cycle — Integration not productized |
| R7 | Key gateway partner described as "we need to convince them" — not yet designed |
| R8 | Lock-in strategy is "great product/service" — not a compounding store of value |
| R9 | "Competitors could do this too" without identifying what constrains them |
| R10 | Key input supplier has no dependency on the venture — can route around at will |
| All F2 | Functions 2 solutions are described as operational activities, not product features |
| All F3 | Competitive dynamics addressed as "differentiation" rather than structural control |
