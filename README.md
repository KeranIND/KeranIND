# Kiran Indugula

**Founder, Chanamill | Software / Solutions Architect | Enterprise Data, Commerce Systems & Applied Personalization**

I build systems across two domains I know firsthand:

1. **enterprise CRM / commerce architecture** — large-volume customer data, deduplication, workflow automation, ownership/routing, APIs and downstream integrations
2. **Chanamill** — FitID, measurement workflows, garment-spec matching, made-to-measure commerce, visualization, manufacturing orchestration and delivered-fit feedback

My public repositories are not generic interview projects. They are clean-room implementations of problem classes I have actually worked on, rewritten with synthetic data and public-safe abstractions so I can show the architecture without publishing employer or Chanamill proprietary code.

## Public engineering work

### [Enterprise CRM Entity Resolution Engine](https://github.com/KeranIND/entity-resolution-engine)

Directly based on the problem domain behind my large-scale CRM deduplication work. My enterprise work included deduplication/merge systems across approximately **600K Leads and 2.4M Contacts**. The public implementation models Lead/Contact/Account adaptation, normalization, candidate generation, explainable scoring, canonical identity, merge survivorship and lineage.

```text
CRM records → normalization → candidate generation → evidence scoring
            → review/decision → canonical identity → safe merge lineage
```

### [Chanamill Made-to-Measure Order Orchestrator](https://github.com/KeranIND/distributed-order-orchestrator)

Models Chanamill's measurement-to-production workflow as an explicit distributed state machine: freeze a FitID/spec snapshot, authorize payment, create the production job, record QC, hand off fulfillment, deliver, and capture fit feedback.

```text
FitID + garment spec → order → production → QC → fulfillment
                     → delivery → fit feedback
```

The important engineering problem is failure recovery across software and physical-world operations.

### [Chanamill FitID Personalization Engine](https://github.com/KeranIND/adaptive-personalization-engine)

Directly models the core Chanamill system boundary: versioned body measurements and fit preferences on one side, versioned garment specifications on the other, with explainable region-level fit assessment and post-delivery feedback evidence.

```text
body + fit preference → FitID
FitID + garment spec → fit assessment
fit assessment + outcome → future evidence
```

The repository deliberately keeps fit intelligence separate from generic behavioral recommendation signals.

### [Engineering Architecture Notes](https://github.com/KeranIND/engineering-architecture-notes)

Architecture notes drawn from the systems I work on: downstream-safe CRM merges, ownership/routing state machines, idempotent integrations, FitID versioning, made-to-measure orchestration, entity resolution and physical-world feedback loops.

## Enterprise architecture background

My enterprise engineering work has included:

- Salesforce architecture with Apex and Lightning Web Components
- MuleSoft and REST integrations
- large-volume Lead / Contact / Account data workflows
- deduplication and merge automation
- onboarding and ownership workflows
- opportunity and sales process automation
- Omni-Channel / routing-related workflows
- integration-safe data mutation
- systems supporting business-critical commerce operations at significant scale

The engineering lesson I took from that work is that **correct local code is not enough**. Data mutations have downstream consequences, workflow state must be explicit, and integrations must be designed for retries and partial failure.

## Chanamill

I’m building **[Chanamill](https://chanamill.com)**, a personalized apparel platform centered on **FitID** — a reusable fit identity connecting body measurements, fit preferences, garment specifications, purchase decisions and delivered-fit outcomes.

```text
Measurement capture
        ↓
      FitID
        ↓
Garment specification
        ↓
Explainable fit guidance
        ↓
Visualization / configuration
        ↓
Made-to-measure order
        ↓
Manufacturing + fulfillment
        ↓
Delivered-fit feedback
        ↓
Better future decisions
```

Current and prototype work across Chanamill has included:

- measurement onboarding and FitID creation
- explainable shirt / pant recommendations
- garment visualization
- configurable and made-to-measure flows
- Flutter mobile product prototypes
- Next.js web product development
- image / scanning experiments
- 3D avatar and garment workflows
- creator-commerce concepts and storefront flows
- India manufacturing / fulfillment workflow design
- phone-based body-capture work in development

Some systems remain private because they contain current product code, manufacturing details, measurement methods, or IP-sensitive logic.

## Technical focus

- **Enterprise platforms:** Salesforce, Apex, LWC, MuleSoft, REST APIs
- **Architecture:** workflow orchestration, integration boundaries, failure recovery, idempotency
- **Data:** entity resolution, normalization, deduplication, merge lineage, data quality
- **Commerce:** customer, product, cart, order, ownership, sales and fulfillment workflows
- **Product engineering:** Flutter, Dart, Next.js, TypeScript
- **Personalization:** FitID, measurement state, garment specifications, explainable matching, feedback loops

## Engineering philosophy

I prefer systems that preserve business context, make state explicit, treat external systems as independently failing, and make important decisions reproducible later.

The patterns I keep returning to are:

- preserve provenance before destructive changes
- make retries idempotent
- version inputs used for irreversible decisions
- separate observations from derived state
- expose why a system made a decision
- design for downstream effects, not only local correctness
- use human review when automation confidence is not high enough

## Links

- **Chanamill:** https://chanamill.com
- **Product demo:** https://youtu.be/Ucau6x7gyYk
- **Android prototype demo:** https://youtu.be/bJX550iU4-A
- **LinkedIn:** https://www.linkedin.com/in/kiran-indugula-314325171/

---

**Building software that connects enterprise-scale systems thinking with real-world commerce and manufacturing.**