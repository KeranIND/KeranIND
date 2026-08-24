# Kiran Indugula

**Founder, Chanamill | Software / Solutions Architect | Commerce, Data, Integration & Applied AI**

I build systems that connect **identity, decisioning, workflow, transactions, and real-world outcomes**.

I’m currently building **[Chanamill](https://chanamill.com)** — a personalized apparel platform centered on **FitID**, a reusable fit identity that connects body measurements, fit preferences, garment specifications, purchase decisions, manufacturing, and delivered-fit feedback.

My background spans enterprise CRM/data architecture, Salesforce/Apex/LWC, MuleSoft/REST integrations, large-volume deduplication and routing workflows, and consumer product engineering across Flutter and Next.js.

## Start here

If you are reviewing my work quickly, these four repositories show the progression from enterprise systems to Chanamill:

1. **[Chanamill FitID Personalization Engine](https://github.com/KeranIND/adaptive-personalization-engine)** — versioned FitID, garment-spec matching, explainable fit assessment, measurement provenance, and delivered-fit feedback.
2. **[Enterprise CRM Entity Resolution Engine](https://github.com/KeranIND/entity-resolution-engine)** — multi-million-record identity resolution patterns, normalization, candidate generation, scoring, merge lineage, and downstream-safe routing.
3. **[Chanamill Made-to-Measure Order Orchestrator](https://github.com/KeranIND/distributed-order-orchestrator)** — FitID snapshot locking, payment, production, QC, fulfillment, creator attribution, and fit-feedback capture.
4. **[Engineering Architecture Notes](https://github.com/KeranIND/engineering-architecture-notes)** — architecture decisions across CRM integrations, idempotency, FitID versioning, 3D visualization boundaries, manufacturing, and closed-loop systems.

These are **clean-room public implementations of problem classes I have actually worked on**. They use synthetic/public-safe abstractions and contain no employer code, private schemas, credentials, or Chanamill production IP.

## Chanamill / FitID

The core product loop:

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
- garment visualization and 3D avatar / garment workflows
- configurable and made-to-measure commerce flows
- Flutter mobile prototypes
- Next.js web product development
- image / scanning experiments
- creator/storefront concepts
- India manufacturing / fulfillment workflow design
- phone-based body-capture work in development

## Enterprise architecture background

My enterprise work has included:

- Salesforce architecture with Apex and Lightning Web Components
- MuleSoft and REST integrations
- large-volume Lead / Contact / Account data workflows
- deduplication and merge automation
- onboarding and ownership workflows
- opportunity and sales process automation
- Omni-Channel / routing-related workflows
- integration-safe data mutation and retry-aware workflows

A recurring lesson from that work is that **correct local code is not enough**. Data mutations have downstream consequences, workflow state must be explicit, and integrations must be designed for retries, partial failure, and auditability.

One public reference implementation is based on a CRM identity-resolution problem class I worked on across approximately **600K Leads and 2.4M Contacts**.

## The common engineering pattern

```text
Identity / context
        ↓
Decision logic
        ↓
Workflow orchestration
        ↓
Operational execution
        ↓
Observed outcome
        ↺
```

That same pattern links my enterprise systems work to Chanamill: establish trustworthy identity, make explicit decisions, orchestrate the workflow, observe what happened in the real world, and improve the next decision.

## Technical focus

- **Enterprise platforms:** Salesforce, Apex, LWC, MuleSoft, REST APIs
- **Architecture:** workflow orchestration, integration boundaries, failure recovery, idempotency
- **Data:** entity resolution, normalization, deduplication, merge lineage, data quality
- **Commerce:** customer, product, cart, order, ownership, sales, manufacturing and fulfillment workflows
- **Product engineering:** Flutter, Dart, Next.js, TypeScript
- **Personalization:** FitID, measurement state, garment specifications, explainable matching, feedback loops

## Links

- **Chanamill:** https://chanamill.com
- **Product demo:** https://youtu.be/Ucau6x7gyYk
- **Android prototype demo:** https://youtu.be/bJX550iU4-A
- **LinkedIn:** https://www.linkedin.com/in/kiran-indugula-314325171/

---

**Building software that connects enterprise-scale systems thinking with real-world commerce, personalization, and manufacturing.**