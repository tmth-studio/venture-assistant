# At-Scale Resourcing Model (ARM) — Guide

Source: IVE Systems / reflect.site ARM guide

**Note on naming:** The ARM replaces "financial model" as the term for this stage of work. "Financial model" implies a standard P&L — the ARM is distinct: it is a personnel-and-resource-centric view of the venture at scale, from which cost structure is derived. The financial simulation (required price vs. target price) is downstream of the ARM, not synonymous with it.

---

## What It Is

The ARM is a personnel-centric view of the venture once it's scaled and operating as a going concern. It maps:

- The direct activities needed to produce and distribute each 4-D Product
- The personnel responsible for each activity
- The resources required (people, depreciable assets, consumables)
- The supporting and managerial labour connected to direct labour

The ARM provides clarity on cost structure drivers and makes resourcing assumptions explicit and testable.

---

## What the ARM Contains

| Element | Description |
|---------|-------------|
| **Personnel** | Every category of person directly responsible for a 4-D Product component |
| **Key activities** | The specific activities needed to make and move each product to its recipient |
| **Resources** | Computers, transport, software, sales aids — everything needed to perform activities |
| **Support HR** | People who assist task execution (admin, assistants) |
| **Managerial HR** | People who provide strategic direction and oversight |

Greater analysis detail surfaces key business constraints and pinch points. Complete detail of every activity isn't practical or necessary — focus on what drives cost and what creates constraints.

---

## Five-Step Development Process

### Step 1: List 4-D Products

Copy working, communications, payment, and partner products directly from the CTM. Maintain colour coding and traceability — do not modify at this stage.

- 🔴 Red — Working Products
- 🔵 Blue — Communications Products
- 🟢 Green — Payment Products
- 🟣 Purple — Partner Products

### Step 2: Define Direct Personnel

Identify a single position directly responsible for each 4-D product component.

*Example (dispute resolution):* Law students producing dispute reports are the direct producers, despite management oversight above them.

Place position labels on the left side of the workspace with corresponding products on the right. Maintain significant spacing — the activities go between them in Step 3.

### Step 3: List Key Activities

Map the activities needed to move each flow to/from its receiving entity.

*Example activities:*
- Visiting distributors biweekly for stock checks and orders
- Warehouse shipping to facilities
- Recruiting visits to replace distributor turnover

Position activity labels between the responsible personnel (left) and the products (right), reflecting natural ordering where applicable.

### Step 4: Map Indirect Support Chains

Two types of indirect HR:

| Type | Role |
|------|------|
| **Support HR** | Assists task execution (admin, graphic designers, copywriters) |
| **Managerial HR** | Provides strategic direction and oversight (team leads, heads of function) |

*Example structure:*
- Account managers → supported by admin assistants → reporting to sales managers
- Marketing managers → supported by graphic designers and copywriters → reporting to Head of Marketing

Position support roles **above** direct positions; management positions **below**.

#### What Drives Staffing at Each Level

| Driver | What it means | Example roles |
|--------|--------------|--------------|
| **Activities** | Volume of specified, tightly-bound activities at scale — always drives direct labour | Sales executives, customer service executives |
| **Employees** | Number of people managed by the position | Sales manager, customer service team lead |
| **Geographical offices / segments** | Coverage area or customer segments | Country GM, Head of Marketing |
| **Venture** | Positions required venture-wide — C-suite only | CEO, COO, CFO |

When managerial or support positions are activity-driven (clearly defined, bounded activities comprising the majority of their role), include those activities in the chain.

*Example — dispute resolution operations executives have four main activities:*
1. Intervention for problems
2. Recruitment and training addressing turnover
3. Monitoring of performance
4. Upskilling / training for performance improvement

Activities appear between "Student Case Manager" and "Operations Executive" labels. Remaining management extends below without activity detail.

### Step 5: Define Required Resources

Three resource categories:

| Category | Examples |
|----------|---------|
| **HR cost** | Salary, stipend, contractor rate — per role |
| **Depreciable assets** | Laptops, IT equipment, proprietary digital platforms, vehicles, machinery |
| **Consumable resources** | Software subscriptions, office supplies, raw materials |

**Values are not entered at this stage** — they are stored and calculated in the financial simulation downstream.

#### For Activity-Driven Positions
Include resources next to each activity box, specifying:
- Time at scale (hours per week / month)
- Wage per hour

Office costs are included as a consumable resource across all activities as standard. Remote-first companies incur equivalent costs through supplies, retreats, and software subscriptions.

#### For Non-Activity-Driven Positions
Include HR cost, depreciable assets, and consumable resources for the position overall (not per-activity).

#### On Depreciable Assets
Capture "big ticket, critical items without which the role couldn't be performed." Do not exhaustively capture every piece of software or IT equipment.

---

## ARM → Financial Simulation

The ARM feeds the financial simulation. Once the ARM is complete:

1. Apply costs to each resource (wages, asset depreciation, consumable unit costs)
2. Multiply by volume (transactions per LMU at scale, number of LMUs)
3. Build the cost layers: PVC → RC → SC → IC
4. Calculate required price
5. Compare to target price (what customers will credibly pay)
6. Calculate FMOS

The ARM makes the cost structure derivable from first principles rather than estimated from the top down.

---

## Relationship to Other Tools

| Tool | What it shows | Feeds into |
|------|--------------|------------|
| **CTM** | Customer state changes and which products drive them | AOM, ARM |
| **AOM** | How products flow from production to customer | ARM |
| **ARM** | Who does what with what resources to produce the flows | Financial simulation |
| **Financial simulation** | Required price vs. target price, FMOS | Go/no-go decision |

---

## Common ARM Failures

| Failure | Signal |
|---------|--------|
| Products not traced from CTM | ARM components disconnected from customer need — hard to challenge or validate |
| No distinction between direct and support/managerial HR | Indirect costs invisible until late; understates true cost per unit |
| Activity-driven roles listed without activities | Cannot estimate time at scale; labour cost becomes a guess |
| Resources not categorised (HR / depreciable / consumable) | Cannot build PVC/RC/SC/IC layers correctly |
| Values entered at ARM stage | Premature — values belong in financial simulation, not ARM |
