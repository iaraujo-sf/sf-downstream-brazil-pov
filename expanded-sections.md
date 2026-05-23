# Oil&Gas Downstream POV — Expanded Sections
## v1.0 — Content for Google Slides expansion

---

# SECTION 1: PRICING EXCELLENCE (Slides 29+)

---

## Slide: Section Divider
**Title:** Margin Through Pricing Excellence
**Subtitle:** How leading distributors protect profitability while remaining competitive across channels and regions.

---

## Slide: Why Pricing Is Different in Brazil
**Title:** Pricing in Brazil: A Multi-Variable Equation Unlike Any Other Market

| Factor | Impact |
|--------|--------|
| PPI Abandonment (2022) | Petrobras no longer follows International Parity Price — creates opacity and unpredictability in cost basis |
| FX Exposure | BRL/USD volatility directly impacts import costs, with distributors absorbing timing risk between purchase and resale |
| Tax Labyrinth | ICMS monofásico + PIS/COFINS + CIDE + state substituição tributária — each product/state combination has different tax treatment |
| Biofuel Mandates | Ethanol (27%) and Biodiesel (15%) blend ratios shift effective cost per liter — pricing must reflect blend economics |
| Competitive Pressure | White-flag stations undercut branded networks on price — forcing constant trade-off between volume and margin |

**Key Insight:** In Brazil, pricing is not a commercial function — it's a treasury, tax, and supply function that happens to determine what the customer pays.

---

## Slide: The Pricing Operating Model
**Title:** The Pricing Decision Architecture
**Subtitle:** Five interconnected layers that determine margin capture — or margin leakage.

### Layer 1: Cost Basis Construction
- Petrobras gate price (or import landed cost)
- Biofuel blending cost (ethanol + biodiesel spot)
- Freight to terminal + storage costs
- Tax burden per state/product/regime

### Layer 2: Market Intelligence
- Competitor pricing monitoring (pump price surveys, ANP data)
- Regional demand elasticity
- Channel-specific willingness to pay (B2B vs. retail vs. TRR)

### Layer 3: Margin Rules Engine
- Floor margin by product/region/channel
- Target margin bands by customer tier
- Escalation triggers when margin drops below threshold

### Layer 4: Dynamic Pricing Execution
- B2B contract pricing (indexed to Petrobras + FX + freight)
- Spot pricing for TRR and uncontracted volume
- Promotional pricing for retail network (volume incentives)

### Layer 5: Performance Monitoring
- Realized margin vs. target margin (daily)
- Price-volume trade-off analysis
- Competitor response tracking

---

## Slide: The Pricing Operating Gap
**Title:** The Gap: World-Class Complexity, Spreadsheet-Grade Tools

| Layer | Current Reality | Risk Level |
|-------|----------------|------------|
| Cost Basis Construction | SAP extract + manual FX lookup + tax team email | 🟠 MARGIN EROSION — 24-48h delay in cost visibility |
| Market Intelligence | Manual pump surveys + weekly ANP reports + WhatsApp groups | 🟠 BLIND SPOTS — competitors react faster |
| Margin Rules Engine | Pricing committee meets weekly + Excel guardrails | 🔴 MARGIN LEAKAGE — deals close below floor without visibility |
| Dynamic Pricing Execution | Sales rep discretion + email approval chains | 🔴 SPEED LOSS — B2B deals take days instead of hours |
| Performance Monitoring | Monthly P&L analysis + ad-hoc reports | 🔴 LATE DETECTION — margin problems found weeks after the fact |

**The Core Problem:** Pricing decisions are made with yesterday's data in a market that changes hourly. The gap between cost movement and price adjustment is where margin disappears.

---

## Slide: Salesforce Pricing Solution Architecture
**Title:** The Five Pricing Layers — Salesforce Mapping

| Layer | Salesforce Product | Capability |
|-------|-------------------|------------|
| Cost Basis Construction | **Data Cloud + MuleSoft** | Real-time SAP cost ingestion + FX feeds + tax engine integration. Single cost-per-liter view updated continuously |
| Market Intelligence | **Tableau + Data Cloud** | ANP data integration, competitor monitoring dashboards, regional elasticity models. AI-detected pricing anomalies |
| Margin Rules Engine | **Revenue Cloud (CPQ) + Flow** | Automated floor/ceiling guardrails per product/region/channel. No deal closes below threshold without VP override |
| Dynamic Pricing Execution | **Revenue Cloud + Agentforce** | AI agent recommends optimal price per B2B opportunity. Auto-generates indexed contract terms. Sub-hour response time |
| Performance Monitoring | **CRM Analytics + Tableau** | Daily realized margin dashboards. Automated alerts when margin drifts. Price-volume elasticity tracking |

---

## Slide: Pricing — Agentforce in Action
**Title:** Autonomous Pricing Intelligence with Agentforce

**Agent 1: Cost Monitor Agent**
- Watches Petrobras gate price changes, FX movements, biofuel spot prices
- Calculates new landed cost within minutes of market move
- Triggers pricing review alert to commercial team with recommended new price bands

**Agent 2: Deal Margin Guardian**
- Reviews every B2B deal before approval
- Validates margin against floor rules
- Auto-approves deals within guardrails, escalates exceptions with context

**Agent 3: Competitive Response Agent**
- Monitors regional price movements from ANP data and field intelligence
- Detects when competitor undercuts in specific regions
- Recommends targeted response (match, hold, or differentiate) based on account stickiness

**Quote:** "The goal is not to replace the pricing committee — it's to give them real-time ammunition instead of last week's spreadsheet."

---

# SECTION 2: LOGISTICS EXCELLENCE (Slides 31+)

---

## Slide: Section Divider
**Title:** Scale Through Logistics Excellence
**Subtitle:** How leading players turn network efficiency and service reliability into commercial advantage.

---

## Slide: Why Logistics Is the Hidden Margin in Brazil
**Title:** Logistics in Brazil: Where Continental Scale Meets Operational Reality

| Factor | Brazil Context |
|--------|----------------|
| Continental Distances | Average delivery route: 300-800km. São Paulo to Manaus: 3,900km by road |
| Modal Dependence | 65% of fuel transported by road (tanker trucks) — highest cost modal |
| Infrastructure Gaps | Limited pipeline coverage outside Southeast. Rail underinvested. Port congestion |
| Fleet Complexity | Mix of owned, contracted, and third-party carriers with different SLAs and cost structures |
| Delivery Precision | 44,000+ stations expect delivery within tight windows — stockout = lost sales + customer churn |

**Key Insight:** Logistics cost represents 8-12% of total fuel cost in Brazil. Every 1% efficiency gain = R$500M+ industry savings annually.

---

## Slide: The Logistics Operating Model
**Title:** The Logistics Decision Architecture
**Subtitle:** From terminal to station — five layers that determine cost, reliability, and competitive advantage.

### Layer 1: Network Design & Infrastructure
- Terminal location strategy (proximity to demand centers + supply sources)
- Pipeline access contracts
- Import terminal capacity (strategic for import-dependent regions)

### Layer 2: Primary Transport (Terminal-to-Base)
- Pipeline scheduling
- Cabotage (coastal shipping)
- Rail movements
- Long-haul road transport

### Layer 3: Secondary Transport (Base-to-Station / B2B)
- Route optimization per delivery window
- Fleet mix allocation (owned vs. contracted)
- Compartment optimization (multi-product loads)

### Layer 4: Last-Mile Execution
- Delivery scheduling aligned to station tank levels
- Driver safety & compliance
- Proof of delivery & volume reconciliation

### Layer 5: Performance & Cost Management
- Cost per liter delivered by route/modal/region
- Fleet utilization rate
- Delivery SLA compliance
- Empty-mile reduction

---

## Slide: The Logistics Operating Gap
**Title:** The Gap: Millions of Kilometers Managed on Calls and Spreadsheets

| Layer | Current Reality | Risk Level |
|-------|----------------|------------|
| Network Design | Annual planning cycle + static models | 🟠 SUBOPTIMAL CAPEX — infrastructure decisions lag demand shifts |
| Primary Transport | TMS for scheduling, but disconnected from commercial demand | 🟠 EXCESS COST — over/under positioning at bases |
| Secondary Transport | Manual route planning + driver experience | 🔴 COST LEAKAGE — 15-25% empty miles industry average |
| Last-Mile Execution | Phone calls to stations + driver judgment on sequence | 🔴 STOCKOUT RISK — reactive delivery triggers emergency runs |
| Cost Management | Monthly reports from TMS + manual freight audit | 🟠 LATE VISIBILITY — cost overruns detected after the fact |

**The Core Problem:** Logistics decisions are made independently from commercial priorities. The delivery that's cheapest to execute may not serve the highest-value customer.

---

## Slide: Salesforce Logistics Solution Architecture
**Title:** The Five Logistics Layers — Salesforce Mapping

| Layer | Salesforce Product | Capability |
|-------|-------------------|------------|
| Network Design | **Tableau + Data Cloud** | Demand heat maps overlaid with infrastructure. AI-driven capacity planning. Investment case generation |
| Primary Transport | **MuleSoft + Data Cloud** | TMS integration. Real-time pipeline/vessel tracking. Demand-triggered positioning recommendations |
| Secondary Transport | **Field Service + Agentforce** | AI-optimized routing. Dynamic scheduling based on tank telemetry. Fleet allocation by priority |
| Last-Mile Execution | **Field Service + Mobile** | Real-time delivery tracking. Automated proof of delivery. Driver task management. Customer notifications |
| Cost Management | **Tableau + CRM Analytics** | Cost-per-liter dashboards by route/region/customer. Freight audit automation. SLA compliance tracking |

---

## Slide: Logistics — Connected Intelligence
**Title:** From Reactive Delivery to Predictive Logistics

**Scenario: Station Tank Telemetry → Autonomous Delivery Scheduling**

```
[IoT Sensor at Station] → Tank level drops below 40%
        ↓
[Data Cloud] → Ingests telemetry + correlates with historical consumption pattern
        ↓
[Agentforce] → Predicts stockout in 36 hours. Checks delivery schedule.
        ↓
[Field Service] → Auto-schedules delivery. Optimizes route with nearby stations.
        ↓
[Experience Cloud] → Dealer notified: "Delivery confirmed for tomorrow 8-10am"
        ↓
[CRM Analytics] → Updates cost-per-delivery and SLA metrics in real time
```

**Impact:** Shift from "station calls when tank is empty" to "delivery arrives before station knows they need it."

---

## Slide: Logistics — The MuleSoft Integration Layer
**Title:** MuleSoft: Connecting the Physical and Digital Supply Chain

**Integrations Required:**
- **TMS (Transport Management System)** — route scheduling, fleet allocation, freight costs
- **IoT/Telemetry platforms** — tank levels, GPS tracking, fuel quality sensors
- **SAP MM/WM** — inventory at terminals and bases, goods movement
- **ANP regulatory systems** — nota fiscal eletrônica, SEFAZ compliance
- **Third-party carriers** — EDI integration for contracted fleet scheduling and billing

**Key Value:** MuleSoft creates the unified data bus that connects physical logistics assets (trucks, tanks, terminals) to commercial decision-making (which customer, which margin, which priority).

---

# SECTION 3: COMMERCIAL EXCELLENCE (Slides 33+)

---

## Slide: Section Divider
**Title:** Growth Through Commercial Excellence
**Subtitle:** How leading distributors turn disciplined execution into higher volume, stronger retention, and profitable growth.

---

## Slide: The Two Commercial Battlefields
**Title:** Retail (B2C2B) vs. Direct B2B: Two Models, One Platform

### RETAIL (B2C2B) — The Branded Network
| Dimension | Challenge |
|-----------|-----------|
| 44,000+ stations | Network management at continental scale |
| 49% white-flag | Constant conversion + retention battle |
| Dealer relationship | Complex: financial support, training, brand compliance, volume incentives |
| Consumer loyalty | Programs competing for share of wallet at the pump |
| Convenience retail | C-stores becoming margin differentiator (AmPm, Shell Select, Jet Oil) |

### DIRECT B2B — The Volume Engine
| Dimension | Challenge |
|-----------|-----------|
| Agribusiness | Seasonal demand, barter contracts, on-farm delivery infrastructure |
| Mining & Industry | Long-term contracts, dedicated storage (PAVs), high-volume SLAs |
| Transport fleets | Fleet cards, multi-site delivery, real-time consumption monitoring |
| Thermal power plants | Massive spot volumes during hydro shortage — timing critical |
| Government & public | Tender processes, compliance, payment terms |

---

## Slide: The Commercial Operating Model — Retail
**Title:** Retail Network Management: The Five Disciplines

### 1. Network Planning & Expansion
- Whitespace analysis: where to add branded stations
- Competitive mapping: flag risk zones
- Investment prioritization: CAPEX allocation for station upgrades

### 2. Dealer Acquisition & Onboarding
- Prospect scoring (location, volume potential, financial health)
- Contract negotiation (exclusivity terms, investment packages)
- Onboarding workflow (branding, equipment, training)

### 3. Relationship Management & Development
- Territory management (segmentation by volume, potential, risk)
- Visit cadence and execution (structured agendas, action items)
- Performance reviews and business plans per station

### 4. Volume & Margin Management
- Volume forecasting per station
- Incentive programs (rebates, volume bonuses)
- Product mix optimization (premium fuels, lubricants, additives)

### 5. Retention & Churn Prevention
- Early warning signals (volume drop, payment delays, competitor contact)
- Proactive intervention programs
- Contract renewal management

---

## Slide: The Commercial Operating Model — B2B
**Title:** B2B Sales Machine: The Five Disciplines

### 1. Market Intelligence & Prospecting
- Sector mapping (agribusiness harvest calendar, mining CAPEX cycles)
- Account identification and sizing
- Competitive displacement opportunities

### 2. Complex Sales Execution
- Multi-stakeholder selling (procurement, operations, finance, sustainability)
- Solution design (logistics + credit + pricing + compliance package)
- Proposal automation and contract management

### 3. Account Development & Expansion
- Share-of-wallet growth (fuel + lubricants + services)
- Cross-sell opportunities (fleet cards, carbon credits, EV charging)
- Strategic account planning

### 4. Service Delivery Alignment
- SLA definition and monitoring
- Dedicated infrastructure management (PAVs, on-site tanks)
- Proactive issue resolution

### 5. Renewal & Retention
- Contract lifecycle management
- Price renegotiation triggers (market shifts, volume changes)
- Competitor defense strategies

---

## Slide: The Commercial Operating Gap
**Title:** The Gap: Two Worlds That Don't Talk to Each Other

| Dimension | Retail Reality | B2B Reality | Risk |
|-----------|---------------|-------------|------|
| Customer Data | Dealer info in one system, consumer loyalty in another | Account data in SAP, interactions in email | 🔴 NO 360° VIEW |
| Pipeline | Volume forecasts in Excel by territory | Opportunities in spreadsheets or basic CRM | 🔴 NO PREDICTABILITY |
| Visit/Activity | Paper forms or disconnected apps | Meeting notes in email, no activity tracking | 🟠 NO EXECUTION VISIBILITY |
| Performance | Monthly volume reports from SAP | Quarterly reviews with incomplete data | 🟠 LATE REACTION |
| Churn Signals | Discovered when station unbrands | Discovered when contract is lost | 🔴 PREVENTABLE LOSSES |

**The Core Problem:** Commercial teams operate on instinct and relationships (which matter), but without data and process to scale what the best reps do naturally.

---

## Slide: Salesforce Commercial Solution — Retail Network
**Title:** Sales Cloud + Experience Cloud: The Retail Network Platform

| Capability | Salesforce Product | What It Does |
|------------|-------------------|--------------|
| Dealer 360° Profile | **Sales Cloud** | Unified view: contract, volume, financials, visits, cases, loyalty performance — one screen |
| Territory Intelligence | **Maps + Tableau** | Geo-visualization of network, whitespace, competitor proximity, risk zones |
| Visit Execution | **Sales Cloud (Mobile)** | Structured visit plans, offline-capable checklists, photo capture, GPS confirmation |
| Dealer Portal | **Experience Cloud** | Self-service: order tracking, financial statements, marketing materials, support cases |
| Churn Prediction | **Einstein + Data Cloud** | AI model trained on historical churn patterns (volume drop + payment delay + low engagement) |
| Incentive Management | **Revenue Cloud** | Automated volume rebate calculations, tiered incentive programs, transparent dealer dashboards |

---

## Slide: Salesforce Commercial Solution — B2B
**Title:** Sales Cloud + Revenue Cloud: The B2B Growth Engine

| Capability | Salesforce Product | What It Does |
|------------|-------------------|--------------|
| Account Planning | **Sales Cloud** | Strategic account plans with share-of-wallet, growth targets, stakeholder mapping |
| Pipeline Management | **Sales Cloud** | Stage-gated opportunity process with probability-weighted forecasting |
| CPQ & Proposals | **Revenue Cloud** | Dynamic pricing within guardrails, auto-generated proposals with indexed contract terms |
| Complex Approvals | **Flow + Agentforce** | Multi-level deal approval with margin validation, escalation, and audit trail |
| Contract Lifecycle | **Revenue Cloud** | Renewal alerts, price adjustment triggers, automated amendment workflows |
| Forecast Accuracy | **Einstein Analytics** | AI-powered forecast with consumption patterns, seasonality, and macro signals |

---

## Slide: Commercial — Agentforce in Action
**Title:** Autonomous Commercial Intelligence with Agentforce

**Agent 1: Churn Prevention Agent (Retail)**
- Monitors 44,000 stations daily for early warning signals
- Detects: volume decline >10%, payment delays, reduced product mix, low engagement score
- Auto-triggers intervention: alerts territory manager + recommends specific action based on pattern

**Agent 2: Opportunity Spotter Agent (B2B)**
- Scans market signals: harvest forecasts, mining CAPEX announcements, fleet expansion news
- Identifies new accounts or expansion opportunities for existing accounts
- Creates qualified leads with context: "Agribusiness X expanding 20% in MT — estimated 5M liters/year diesel"

**Agent 3: Deal Desk Agent**
- Reviews B2B proposals against margin rules, credit limits, and logistics feasibility
- Auto-approves standard deals within policy
- Escalates exceptions with full context: margin analysis, competitor comparison, strategic value assessment

---

# SECTION 4: CUSTOMER OPERATIONS (Slides 35+)

---

## Slide: Section Divider
**Title:** Loyalty Through Customer Operations Excellence
**Subtitle:** How distributors create stickiness, differentiate beyond the commodity, and build recurring revenue streams.

---

## Slide: Why Customer Operations Is the Defensive Moat
**Title:** Beyond the Commodity: The Four Pillars of Customer Stickiness

| Pillar | What It Does | Why It Matters |
|--------|-------------|----------------|
| **Credit & Financial Services** | Working capital for dealers, flexible payment for B2B | In a 14% interest rate environment, credit = volume lock-in |
| **Loyalty & Rewards** | Consumer programs (Premmia, Shell Box, Km de Vantagens) | 40M+ enrolled consumers create recurring traffic + behavioral data |
| **Fleet Management** | Integrated fuel + toll + maintenance cards | High switching costs for transport companies — guarantees volume |
| **TRR Operations** | Last-mile delivery to farms, small industries, generators | Serves the fragmented middle-market that major players can't reach efficiently |

**Key Insight:** Fuel is a commodity. Customer operations transforms it into a relationship business with recurring revenue streams and defensible switching costs.

---

## Slide: Credit & Financial Services Operating Model
**Title:** Credit as a Competitive Weapon in a High-Interest Economy

### The Credit Value Chain:
1. **Risk Assessment** — Financial analysis, credit scoring, collateral evaluation
2. **Limit Setting** — Dynamic limits based on volume, history, and market conditions
3. **Disbursement** — Working capital lines, product financing, investment packages
4. **Monitoring** — Real-time exposure tracking, early warning signals
5. **Collection** — Automated dunning, renegotiation workflows, legal escalation

### Brazil-Specific Complexity:
- **Dealer credit** — Upfront investment packages (R$1-5M per station) tied to exclusivity contracts
- **B2B seasonal credit** — Agribusiness barter operations (grain-for-fuel) with crop cycle timing
- **Consigned inventory** — Product on dealer premises that remains distributor's asset until sold
- **Receivables anticipation** — Factoring dealer card receivables at preferential rates

---

## Slide: Loyalty Ecosystem Operating Model
**Title:** Consumer Loyalty in Fuel Retail: Data Is the New Fuel

### Major Programs in Brazil:
| Program | Distributor | Members | Key Mechanism |
|---------|------------|---------|---------------|
| Premmia | Vibra (BR) | 30M+ | Points → marketplace redemption |
| Shell Box | Raízen | 15M+ | Cashback + digital payments |
| Km de Vantagens | Ipiranga | 40M+ | Points → airline miles + partners |
| Abastece Aí | Vibra | 10M+ | Digital payments + cashback |

### The Loyalty Operating Model:
1. **Enrollment & Activation** — Multi-channel acquisition (app, station, web)
2. **Earn Mechanics** — Points/cashback per liter + partner multipliers
3. **Redemption Experience** — Marketplace, miles, discounts, partner offers
4. **Personalization** — AI-driven offers based on behavior (frequency, product, location)
5. **Dealer Integration** — Station-level performance visibility + promotional execution

---

## Slide: Fleet Management Operating Model
**Title:** Fleet Cards: The High-Switching-Cost Volume Guarantor

### What Fleet Management Includes:
- **Fuel cards** — Branded acceptance network, per-driver controls, real-time authorization
- **Toll integration** — Single card for fuel + tolls (Vale Pedágio obrigatório for freight)
- **Maintenance** — Preventive maintenance scheduling tied to mileage/fuel consumption
- **Analytics** — Consumption per vehicle, route efficiency, driver behavior
- **Compliance** — ANTT regulatory compliance, environmental reporting

### Why It Creates Lock-In:
- Transport companies integrate fleet cards into their operational systems (TMS, payroll, cost allocation)
- Driver management rules (limits per day, per transaction, per product) are configured per company
- Migration means reconfiguring 100s-1000s of drivers + changing operational processes
- Volume contracts tied to fleet commitment guarantee minimum monthly purchases

---

## Slide: The Customer Operations Gap
**Title:** The Gap: Four Pillars Operating in Silos

| Pillar | Current Reality | Risk Level |
|--------|----------------|------------|
| Credit | SAP FI for accounting + Excel for analysis + email for approvals | 🔴 SLOW DECISIONS — credit approval takes 5-10 days, competitors respond in 24h |
| Loyalty | Separate platform (often outsourced) disconnected from CRM and commercial data | 🔴 NO PERSONALIZATION — generic offers, low redemption rates, declining engagement |
| Fleet | Dedicated system with limited integration to commercial or service teams | 🟠 MISSED CROSS-SELL — fleet data not used for account expansion or renewal insights |
| TRR | Separate operation, often managed as cost center with basic tools | 🟠 UNDER-MONETIZED — serving small clients without understanding their full potential |

**The Core Problem:** Each pillar generates valuable data about customer behavior, but that data never flows into commercial decisions or proactive service actions.

---

## Slide: Salesforce Customer Operations Solution
**Title:** The Four Customer Operations Pillars — Salesforce Mapping

| Pillar | Salesforce Product | Capability |
|--------|-------------------|------------|
| Credit & Financial Services | **Financial Services Cloud + Flow** | Automated credit scoring, dynamic limit management, approval workflows, portfolio monitoring dashboards, early warning alerts |
| Loyalty & Rewards | **Marketing Cloud + Data Cloud + Loyalty Management** | Unified member profiles, AI-driven personalization, real-time offer triggers, multi-channel engagement (app, SMS, email, pump screen) |
| Fleet Management | **Service Cloud + Experience Cloud + Data Cloud** | Fleet portal for transport companies, real-time consumption dashboards, predictive maintenance alerts, automated compliance reporting |
| TRR Operations | **Field Service + Sales Cloud** | Route optimization for last-mile delivery, customer microsegmentation, upsell recommendations based on consumption patterns |

---

## Slide: Customer Operations — The Data Cloud Unification
**Title:** Data Cloud: One Customer, One Truth, All Signals Connected

```
┌─────────────────────────────────────────────────────────────┐
│                      DATA CLOUD                              │
│                                                             │
│  ┌──────────┐  ┌──────────┐  ┌──────────┐  ┌──────────┐   │
│  │  Credit  │  │ Loyalty  │  │  Fleet   │  │   TRR    │   │
│  │  History │  │ Behavior │  │   Data   │  │ Delivery │   │
│  └────┬─────┘  └────┬─────┘  └────┬─────┘  └────┬─────┘   │
│       │              │              │              │         │
│       └──────────────┴──────────────┴──────────────┘         │
│                          │                                   │
│              ┌───────────┴───────────┐                       │
│              │  UNIFIED CUSTOMER     │                       │
│              │  IDENTITY GRAPH       │                       │
│              └───────────┬───────────┘                       │
│                          │                                   │
│       ┌──────────────────┼──────────────────┐               │
│       ▼                  ▼                  ▼               │
│  ┌─────────┐      ┌─────────────┐    ┌──────────┐          │
│  │Einstein │      │ Agentforce  │    │ Tableau  │          │
│  │ Scoring │      │   Agents    │    │Dashboards│          │
│  └─────────┘      └─────────────┘    └──────────┘          │
└─────────────────────────────────────────────────────────────┘
```

**Use Cases Enabled:**
- Loyalty member shows declining visit frequency → Trigger personalized win-back offer
- Fleet customer increasing consumption → Sales alerted to expansion opportunity
- Dealer credit utilization at 90% + volume growing → Auto-recommend limit increase
- TRR customer ordering more frequently → Qualify for direct commercial relationship

---

## Slide: Customer Operations — Agentforce in Action
**Title:** Autonomous Customer Operations with Agentforce

**Agent 1: Credit Risk Monitor**
- Continuously evaluates portfolio exposure
- Detects early warning: Serasa score drop, payment pattern change, volume decline + high balance
- Recommends action: reduce limit, pause new orders, trigger collection workflow

**Agent 2: Loyalty Engagement Agent**
- Identifies members at risk of disengagement (no visit in 30 days, points expiring)
- Generates personalized re-engagement offer based on historical behavior
- Delivers via preferred channel (push notification, SMS, email)
- Measures response and adjusts strategy

**Agent 3: Fleet Expansion Agent**
- Monitors fleet customer consumption patterns
- Detects fleet growth signals (new drivers registering, new routes, increased daily consumption)
- Alerts account manager with expansion recommendation + estimated additional volume
- Auto-generates proposal for expanded contract

**Agent 4: TRR Graduation Agent**
- Identifies TRR customers with consistent growth above threshold
- Recommends "graduation" to direct commercial relationship
- Triggers prospecting workflow with full consumption history and credit profile

---

# SECTION 5: UNIFIED ARCHITECTURE (New — ties all pillars together)

---

## Slide: The Complete Salesforce Architecture
**Title:** One Platform, Five Engines, Connected Intelligence

```
┌─────────────────────────────────────────────────────────────────┐
│                    AGENTFORCE LAYER                              │
│  Supply Agent │ Pricing Agent │ Logistics Agent │ Commercial    │
│               │               │                 │ Agent         │
├─────────────────────────────────────────────────────────────────┤
│                    APPLICATION LAYER                             │
│                                                                 │
│  Sales Cloud  │ Revenue Cloud │ Service Cloud  │ Field Service  │
│  Experience   │ Marketing     │ Financial      │ Loyalty        │
│  Cloud        │ Cloud         │ Services Cloud │ Management     │
├─────────────────────────────────────────────────────────────────┤
│                    INTELLIGENCE LAYER                            │
│                                                                 │
│        Tableau          │         CRM Analytics                 │
│        Einstein AI      │         Predictive Models             │
├─────────────────────────────────────────────────────────────────┤
│                    DATA LAYER                                    │
│                                                                 │
│                      DATA CLOUD                                 │
│   Unified Customer │ Supply Signals │ Market Data │ IoT/Telemetry│
├─────────────────────────────────────────────────────────────────┤
│                    INTEGRATION LAYER                             │
│                                                                 │
│                       MULESOFT                                  │
│   SAP ERP │ TMS │ IoT Platform │ ANP/Tax │ Petrobras │ FX Feeds │
└─────────────────────────────────────────────────────────────────┘
```

---

## Slide: Value Realization Roadmap
**Title:** Implementation Roadmap: Quick Wins to Full Transformation

### Phase 1: Foundation (0-6 months)
- MuleSoft integration layer (SAP + core systems)
- Data Cloud deployment (customer + commercial data unification)
- Sales Cloud for retail network management (dealer 360)
- **Quick Win:** Churn prediction model reduces dealer losses by 15-20%

### Phase 2: Commercial Acceleration (6-12 months)
- Revenue Cloud (CPQ) for B2B pricing automation
- Experience Cloud dealer portal
- Tableau dashboards for supply + pricing visibility
- **Quick Win:** B2B deal cycle reduction from 10 days to 3 days

### Phase 3: Operational Intelligence (12-18 months)
- Field Service for logistics orchestration
- Loyalty Management platform migration
- Financial Services Cloud for credit operations
- **Quick Win:** Predictive delivery reduces stockouts by 30%

### Phase 4: Autonomous Operations (18-24 months)
- Agentforce deployment across all five engines
- Full AI-driven decision automation
- End-to-end process optimization
- **Quick Win:** Autonomous agents handle 60% of routine decisions without human intervention

---

## Slide: Expected Business Impact
**Title:** The Value of Connected Operations

| KPI | Current State | With Salesforce | Impact |
|-----|--------------|-----------------|--------|
| Dealer Churn Rate | 8-12% annually | 4-6% annually | ~R$200M volume retention |
| B2B Deal Cycle | 10-15 days average | 2-3 days average | 4x pipeline velocity |
| Pricing Response Time | 24-48 hours | < 1 hour | Margin protection in volatile market |
| Delivery SLA Compliance | 85-90% | 97%+ | Customer satisfaction + retention |
| Credit Approval Time | 5-10 days | Same-day | Win deals before competition |
| Loyalty Redemption Rate | 15-20% | 35-45% | Higher engagement + repeat visits |
| Commercial Productivity | 8-10 meaningful interactions/week | 20-25/week | 2.5x rep effectiveness |

---

## Slide: Why Salesforce — Competitive Differentiation
**Title:** Why This Transformation Requires Salesforce

| Requirement | Why Not Just ERP? | Salesforce Advantage |
|-------------|-------------------|---------------------|
| Customer 360° | ERP is transaction-centric, not customer-centric | Built for relationships, interactions, and lifecycle |
| Speed of Change | ERP changes are expensive, slow, and risky | Low-code platform: weeks not months |
| AI at Scale | ERP AI is limited to historical patterns in structured data | Einstein + Agentforce: multi-source data, autonomous action |
| Channel Unification | ERP doesn't serve portals, mobile, or self-service | Experience Cloud, Mobile, Marketing Cloud — native |
| Ecosystem | ERP is closed | AppExchange + MuleSoft: 1000s of pre-built connectors |
| Time to Value | ERP projects: 18-36 months | Phase 1 live in 6 months with measurable ROI |

**Key Message:** SAP stays as the system of record. Salesforce becomes the system of intelligence and engagement — the layer where humans and AI make decisions and take action.
