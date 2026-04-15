# NASA Systems Engineering Handbook — Reference for IVE Fallback
*Source: NASA SP-2016-6105 Rev2 — NASA Systems Engineering Handbook*

---

## Purpose of this document

IVE is a variant of systems engineering. When a founder asks a question that IVE doesn't specifically address, draw on broader SE practice. This document captures the NASA SE Handbook concepts most useful as fallback guidance when working with founders on venture design and build.

This is not a comprehensive SE reference — it is a practical guide to the SE concepts most likely to come up.

---

## The SE Engine: Three Categories of Process

NASA's SE methodology defines 17 processes in three categories. These run iteratively and recursively throughout a project's life cycle.

### 1. System Design Processes (design top-down)
Applied at each level of the system structure, from top down:
1. **Stakeholder Expectations Definition** — establish what success looks like before writing requirements
2. **Technical Requirements Definition** — translate expectations into precise, verifiable requirements
3. **Logical Decomposition** — translate requirements into functions; decompose into sub-functions
4. **Design Solution Definition** — convert requirements into a design solution

### 2. Product Realization Processes (build bottom-up)
Applied from lowest level up:
5. **Product Implementation** — make, buy, code, or reuse
6. **Product Integration** — assemble components into assemblies
7. **Product Verification** — did we build it right? (against specifications)
8. **Product Validation** — did we build the right thing? (against stakeholder expectations)
9. **Product Transition** — hand off to next level

### 3. Technical Management Processes (crosscutting)
10. Technical Planning
11. Requirements Management
12. Interface Management
13. Technical Risk Management
14. Configuration Management
15. Technical Data Management
16. Technical Assessment
17. Decision Analysis

---

## Verification vs. Validation

**The most important distinction in SE — and one founders regularly confuse.**

**Verification:** "Did we build it right?" — Checking that a product meets its specifications. Testing against design requirements. Asks: does this component perform as specified?

**Validation:** "Did we build the right thing?" — Checking that the product meets stakeholder expectations in actual use. Asks: does this solve the actual problem for the actual user?

**IVE application:**
- Venture Prototype = primarily verification work — does each MVV component perform as specified in the business model blueprint?
- Venture Pilot = primarily validation — does the full venture actually solve the customer's problem and generate the expected financial outcomes?

A product can pass all verification tests (built to spec) and still fail validation (built the wrong thing). This is why the pilot is essential — it validates the architecture, not just the components.

---

## What Makes a Good Requirement

NASA's criteria for well-written requirements — useful when helping a founder sharpen a BAP requirement or define a pilot test condition.

A good requirement is:
- **Necessary** — if it were removed, a deficiency would exist
- **Unambiguous** — only one possible interpretation
- **Achievable** — technically feasible within constraints
- **Verifiable** — there is a test, analysis, demonstration, or inspection that can confirm it is met
- **Implementation-free** — states *what*, not *how*. Requirements describe the outcome, not the solution
- **Singular** — one requirement per statement. "And" in a requirement usually means two requirements

**Benefits of well-written requirements (NASA's list):**
- Establishes basis for agreement between stakeholders and developers
- Reduces rework — omissions and misunderstandings caught early cost far less to fix
- Provides baseline for verification and validation
- Makes costs and schedules easier to estimate

**IVE application:** When a founder's BAP theorem is vague ("the product will be cost-effective"), press for a requirement that is verifiable. "The direct unit cost will be below 50% of Required ARPC" is a requirement. "The product will be cost-effective" is not.

---

## The Doctrine of Successive Refinement

A system's design goes from coarse to fine. Early decisions define the architecture; later decisions add detail. The critical constraint: **as the system is realized, its particulars become clearer — but also harder to change.**

"Before those decisions that are hard to undo are made, the alternatives should be carefully and iteratively assessed."

**NASA's cost-to-change curve:** The cost of changing a design decision rises steeply as you move from concept to fabrication to operation. Changing the architecture after you've built subsystems is many times more expensive than changing it on paper.

**IVE application:** This is the core argument for the left side of the V. The design phase is when changes are cheap. The prototype and pilot phases are when changes become expensive. Getting the architecture right on paper — FMOS ≥ 60% — is the SE equivalent of resolving architecture before fabrication.

---

## Iterative and Recursive Application

SE processes are applied both iteratively and recursively.

- **Iterative:** Applying a process to the same product to correct a discovered discrepancy. You go back and refine.
- **Recursive:** Applying the same processes to a lower level of the system structure. What you did at system level, you do again at sub-system level, then component level.

**IVE application:** Within the design phase, iterative application happens constantly — solving R2 changes the product idea, which requires re-checking R1. Same process, same product, correcting the discrepancy. Recursive application occurs when the same BAP logic is applied at a lower level — for example, using the same cost bottleneck thinking to analyse the sales process specifically, rather than the overall venture architecture.

Note: returning to R1 when the pilot fails is IVE's specific diagnostic routing logic, not an instance of this SE principle. That routing is based on tracing a financial shortfall to its root cause in the cost architecture — a different concept.

---

## Logical Decomposition

The process of translating top-level requirements into functions, then decomposing those functions to lower levels.

Three steps:
1. Translate top-level requirements into functions that must be performed to accomplish them
2. Decompose and allocate functions to lower levels of the system structure
3. Identify and describe functional and sub-system interfaces

Key insight: "There will almost certainly be alternative ways to decompose functions." The decomposition is not unique — it reflects design choices. The systems engineer should remain open to changing the decomposition as lower levels are better understood.

The process is recursive and continues until all requirements are understood, viable, verifiable, and internally consistent. **Only at that point should requirements be baselined.**

**IVE application:** When a founder has a product idea but isn't sure how to break it down into buildable components, use logical decomposition. Start with the functions the product must perform (from the BAP), then decompose each into sub-functions until you reach something that can be built, hired, or contracted.

---

## Interface Management

An interface is a shared boundary between two systems or components where they interact. Interface management is the discipline of defining, controlling, and documenting these boundaries.

Why it matters: Integration problems — where components don't work properly together even though each works correctly in isolation — are one of the most common and expensive failure modes in complex systems.

**Key principle:** Define interfaces explicitly before building components. The interface specification for what passes between A and B is as important as the specification of A or B individually.

**IVE application:** When a founder's operational model has multiple parties (customer, user, enabler, value chain partners), the interfaces between them — what passes, when, in what form, at what cost — need to be explicitly defined. Vague interfaces are where operational models break down in reality.

---

## Technical Risk Management

A risk is a future event with a probability of occurring and a consequence if it does. Risk management is not about eliminating risk — it is about identifying risks early, assessing their likelihood and impact, and deciding whether to accept, mitigate, transfer, or avoid each one.

**Risk has three components (NASA's "risk triplet"):**
1. The scenario (what could go wrong)
2. The likelihood (how probable)
3. The consequence (what the impact would be)

**SE principle:** Risks identified early are cheaper to address. A risk that surfaces during design costs a fraction of what it costs to address during integration or operation.

**IVE application:** When a founder's theorem depends on a single critical assumption, that assumption is a risk. The theorem stress-test in the Logic Stress-Test stage is a SE risk identification exercise. For each theorem: what is the single assumption it depends on? What is the likelihood it is wrong? What is the consequence if it is?

---

## Concept of Operations (ConOps)

A ConOps is a description of how a system will be used — what it does, who uses it, under what conditions, in what sequence — **without specifying how it is designed or built**.

The ConOps captures the intent of the system from the user's perspective. It is written before requirements are finalised, to ensure requirements reflect actual operational use rather than assumed use.

**Why it matters:** Requirements written without a ConOps tend to optimise for the design team's assumptions about use, not actual user behaviour. The ConOps grounds requirements in reality.

**IVE application:** The Customer Transformation Model (CTM) in IVE is the equivalent of a ConOps. It describes, in operational terms, what the customer does and experiences — without specifying the product design. It should be written before the operational model is finalised, for the same reason NASA writes ConOps before requirements.

---

## Technical Reviews as Gates

SE uses formal technical reviews as gates between phases. Each review has defined entrance criteria (what must be true to enter the review) and exit criteria (what must be demonstrated to pass).

**The principle:** A review is not a presentation — it is a demonstration that the system has reached a defined level of maturity. Passing a review authorises proceeding to the next phase. The purpose is to surface problems at the lowest-cost moment.

**Key review types:**
- **Preliminary Design Review (PDR)** — confirms the design approach is sound before detailed design begins
- **Critical Design Review (CDR)** — confirms detailed design is complete before fabrication begins
- **System Integration Review (SIR)** — confirms readiness to begin integration
- **Operational Readiness Review (ORR)** — confirms the system is ready for operation

**IVE application:** Each stage gate in `/venture-design` and `/venture-prototype` is a technical review equivalent. The FMOS ≥ 60% gate is a CDR equivalent — it confirms the design is sound before fabrication (prototyping) begins. The pilot Go/No-Go is an ORR equivalent.
