# Kiran Indugula

**Founder, Chanamill | Software / Solutions Architect | Commerce, Data & Applied AI**

I design and build systems where business workflows, data models, APIs, and product experiences have to work together reliably.

I’m currently building **[Chanamill](https://chanamill.com)** — a personalized apparel platform centered on **FitID**, a reusable fit profile designed to connect body measurements, fit preferences, garment specifications, purchase decisions, and delivered-fit feedback into one learning loop.

My background combines enterprise commerce engineering in the U.S. with firsthand exposure to a multi-generation retail business in India. That combination shaped how I think about Chanamill: not as another fashion storefront, but as a systems problem spanning customer data, product data, fit logic, manufacturing, and post-purchase outcomes.

## Selected public engineering work

### [Entity Resolution Engine](https://github.com/KeranIND/entity-resolution-engine)

An explainable record-linkage pipeline for noisy customer data with normalization, blocking, weighted feature scoring, and union-find clustering. Built to show how I approach data quality, entity matching, false-positive control, and scalable comparison strategies.

### [Distributed Order Orchestrator](https://github.com/KeranIND/distributed-order-orchestrator)

A reference saga orchestrator for multi-step commerce workflows. Models idempotency, explicit state transitions, retries, compensation, and failure recovery across inventory, payment, and fulfillment boundaries.

### [Adaptive Personalization Engine](https://github.com/KeranIND/adaptive-personalization-engine)

An event-driven recommendation reference implementation that derives user preference state from behavior and produces transparent ranking explanations. Designed around reproducible feedback loops rather than opaque scoring.

### [Engineering Architecture Notes](https://github.com/KeranIND/engineering-architecture-notes)

Architecture decision records and design notes on idempotency, distributed workflows, entity resolution, integration boundaries, and reliability trade-offs.

## Chanamill / FitID

The core product thesis:

```text
Customer body + fit preferences
            ↓
          FitID
            ↓
   Garment specifications
            ↓
 Fit guidance + visualization
            ↓
         Purchase
            ↓
     Delivered fit result
            ↓
      Better future FitID
```

The initial wedge is Chanamill-owned personalized apparel, where we can control the product and measurement loop end to end. Over time, the same fit-intelligence layer can extend into creator commerce and retailer integrations.

## Technical focus

- **Software architecture** — system design, workflow orchestration, API integrations
- **Commerce systems** — product, cart, order, customer, and sales workflows
- **Data systems** — deduplication, normalization, entity matching, data quality
- **Enterprise platforms** — Salesforce, Apex, Lightning Web Components, MuleSoft, REST APIs
- **Product engineering** — Flutter, Next.js, TypeScript, user-facing commerce flows
- **Applied personalization** — recommendation logic, measurement workflows, feedback systems

## Engineering philosophy

I prefer systems that are observable rather than opaque, modular rather than tightly coupled, explicit about state and failure modes, and easy to reason about long after the first implementation.

I care about:

- clear domain boundaries
- idempotent operations
- measurable failure modes
- reproducible decisions
- maintainable abstractions
- architecture that survives operational reality

## Product links

- **Chanamill:** https://chanamill.com
- **Product demo:** https://youtu.be/Ucau6x7gyYk
- **Android prototype demo:** https://youtu.be/bJX550iU4-A
- **LinkedIn:** https://www.linkedin.com/in/kiran-indugula-314325171/

## Founder perspective

I’m especially interested in problems where software has to cross the boundary into the physical world — where the hard part is not just building an interface, but capturing enough real-world ground truth to make the system improve over time.

That is the approach behind Chanamill: start with real measurements, real garments, real manufacturing constraints, and real fit outcomes — then use software and data to make the loop progressively smarter.

---

**Currently building Chanamill in New York.**