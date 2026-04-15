# SpaceX Systems Engineering Principles — IVE Relevance
*Source: "System Engineering: A Traditional Discipline in a Non-traditional Organization" — John Muratore, SpaceX (2012)*

---

## What this document is

A presentation by SpaceX's launch director explaining how SpaceX adapts systems engineering for a fast, low-cost organisation. Useful as an analogy when explaining IVE to founders or engineers, because SpaceX is a credible, familiar example of systems engineering applied under real constraints.

**Caution when using:** People have different versions of the V-model. Establish which version a person knows before using SpaceX as an analogy — otherwise the mapping will confuse rather than clarify.

---

## The four principles relevant to IVE

### 1. System-level requirements are fixed because of interdependency

SpaceX tracks and verifies top-level requirements but trades everything below them. They don't re-open the top-level architecture once set — because the components are too interdependent.

**IVE mapping:** The BAP (6 functions, 13 requirements) = the system-level requirements. Fixed. The 13 requirements interact: solving R1 (cost structure) affects R3 (adoption), which affects R5 (customer retention), which affects R9 (competitor defence). You cannot trade them independently. The product idea must satisfy all 13 simultaneously — that's why holistic design is required.

Once on the right side of the V, the business model components (sales scripts, delivery mechanisms, supplier choices, pricing structures) = sub-requirements. These are tradeable and can be optimised without touching the core architecture.

---

### 2. The cost-of-iteration argument

SpaceX: *"Because we can design-build-test at low cost, we can afford to learn through experience rather than consuming schedule attempting to anticipate all possible system interactions."*

**IVE mapping:** Working on paper (left side of the V — design and verification) is cheap. Building and testing (right side — prototype and pilot) is expensive. IVE front-loads the cheap work to reduce costly right-side cycles. The FMOS check — verifying the architecture works on paper before a penny is spent building it — is the direct equivalent of SpaceX's simulation and qualification testing before a launch.

Traditional ventures skip the left side entirely and go straight to building. This is equivalent to SpaceX launching a rocket without any upfront simulation, and then iterating based on crashes.

---

### 3. The balance between upfront engineering and rapid prototyping

SpaceX: *"There is an important balance between heavy upfront systems engineering and rapid prototyping to reduce systems risk — tipping point heavily dependent on organisational agility, cost of iteration, and the ability to trade lower-level requirements."*

**IVE mapping:** IVE is designed to sit at this balance point. The left side (design and verify) is rigorous but not bureaucratic — it uses precise requirements and logic models, not committees and approval gates. The right side (prototype and pilot) is deliberately lean: minimum capital expenditure, maximum flexibility, tradeable components.

The skill to explain here: IVE is not "more planning." It is a different kind of upfront work — engineering the architecture before fabricating the components.

---

### 4. Formality increases as the system matures

SpaceX: *"Documentation and process becomes more formal as systems move into later cycles."* Component tests are informal. Final qualification before launch is formal.

**IVE mapping:** The same pattern holds:
- Design phase (left side): exploratory, iterative, logic-driven
- Venture prototyping (right side, early): flexible, minimum cap-ex, constant iteration on components
- Venture pilot (right side, late): more formal — dashboards, monthly P&L, structured Go/No-Go decision

The increasing formality is not bureaucracy. It is what happens when the stakes increase as you move from paper to prototype to live business.

---

### 5. Tools not rules

SpaceX: *"Focus on TOOLS NOT RULES. It is really easy to ruin the creativity and performance by too much organisation, rules and process."*

**IVE mapping:** The BAP is a tool, not a checklist. The at-scale operational model is a tool. The financial simulation is a tool. None of them tell a founder what to build — they create the conditions for the founder to discover the right architecture. The contemplative practice in IVE (listening before answering analytically) is the equivalent of SpaceX's emphasis on engineering judgement over process compliance.

---

## What is NOT relevant from this document

- Specific technical details of Falcon 1/9/Heavy rocket designs
- Hardware testing hierarchy (development/qualification/acceptance)
- SpaceX's organisational structure and headcount
- Any rocket-specific engineering decisions
