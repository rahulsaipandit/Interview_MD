# Additional Resume Details — Grouped by Company

## Amazon

- **SLIs/SLOs, formal on-call, incident management** — experience spans this and the two other most recent roles (Visible, Augment Me).
- **Manager of managers** — led multi-level engineering orgs; scaled multiple teams.
- **Team building / hiring** — recruited and built engineering teams from scratch, growing to 40+ engineers.
- **Test automation leadership** — led Engineering, QA/Test Automation, and Product orgs, driving automated testing practices.
- **Reliability** — four-nines (99.99%) reliability standard.
- **Manager-of-managers across multiple teams/locations** — explicit at Alexa and Rentals orgs (also Augment Me, Visible).
- **Corporate-level influence** — "unlock roadblocks at corporate level" reflected at Rentals (30+ teams, senior leadership alignment).
- **Customer/third-party facing work**:
  - Rentals — delivered directly to end customers.
  - Alexa AI — public API consumed by third-party developers.
- **Succession planning / mentoring**:
  - Rentals — succession planning and documented feedback loops.
  - Alexa — mentoring.
- **Enterprise-grade caching** — used Redis and Kafka.
- **N-tier architecture / BRMS** — experience with N-tier architecture and Business Rules Management Systems (also at Visible).
- **Multi-cloud** — AWS.

## Visible

- **Security & privacy** — hands-on with authentication, authorization, least-privilege access, encryption at rest and in transit, and audit logging (explicitly demonstrated here).
- **Manager of managers** — led multi-level engineering org.
- **Cloud infrastructure** — cloud-provider-specific compute services, operational excellence practices.
- **Test automation leadership** — led Engineering, QA/Test Automation, and Product orgs.
- **Documentation & compliance standards** — established/maintained documentation processes supporting FDA, HIPAA, SOC 2, and U.S. telecom compliance.
- **Compliance frameworks** — SOC 2.
- **Team building / hiring** — grew org to 75+ engineers.
- **Multi-cloud** — AWS and GCP.
- **Tech stack** — PostgreSQL, Node.js, MongoDB.
- **Multi-year technical roadmap / vision & strategy** — explicit.
- **Succession planning, coaching, mentoring, retention** — succession planning and feedback loops documented; "retention strategies" specifically **not verified** — flag before adding.
- **Enterprise-grade caching** — Redis and Kafka.
- **BRMS (Pega)** — used for:
  - Next Best Action
  - Dynamic pricing & promotions — region-specific discounts, family bundle rules, loyalty rewards at checkout
  - Offer & product configuration — validating complex multi-play bundles (mobile, fiber, streaming TV) for conflicts
  - Fraud detection & prevention — flagging unusual call spikes, SIM-swap patterns, data usage anomalies
- **Architecture** — standard web-tier / app-tier / data-tier separation (presentation, business logic, data as distinct deployable tiers); N-tier architecture.
- **Vendor management** — directly managed vendor SLAs / performance scorecards, including SLA negotiation.
- **Distributed teams** — teams spread across multiple cities in the US and India.
- **Reliability** — four-nines (99.99%) standard.
- **AI-driven automation** — drove AI automation for DevOps and chat automation, with explicit SDLC-wide adoption.
- **Docker** — experience.
- **P&L ownership** — documented (relevant to "large product budget" language in some JDs — exact budget phrasing not verbatim confirmed; consider adding if accurate).

## Augment Me

- **Manager of managers** — led multi-level engineering org.
- **Early-stage startup experience** — led engineering in a zero-to-one, privately funded startup environment.
- **Multi-year technical roadmap / vision & strategy** — explicit.
- **Manager-of-managers across multiple teams/locations** — explicit.
- **Compliance frameworks** — HIPAA, SOC 2, HITRUST.
- **Tech stack** — PostgreSQL, Node.js.
- **Enterprise-grade caching** — Redis and Kafka.

## Cross-Company / General

- **Education** — B.S. Computer Science, YCCE, India.
- **Build-vs-buy decisions** — evaluated and selected third-party vs. in-house solutions, including security and authentication tooling.
- **EHR/FHIR integrations** — no direct experience with Epic, Cerner, FHIR, or payer/provider system integrations — intentionally left off unless specifically applicable.

### Possible Misses (flag/confirm before submitting)
- "Retention strategies for key talent" — not explicitly verified in source material (Visible succession planning is verified; retention specifically is not).
- "Attract great talent internally and externally" / active recruiting — team-building scale is documented (Amazon 40+, Visible 75+), but active recruiting itself isn't explicitly confirmed.
- "Large product budget" (explicit budget language) — P&L ownership is documented at Visible, but JD's specific "budget" phrasing isn't mirrored verbatim.

### Legitimate Omissions (correctly excluded)
- Google Cloud (GCP) as an enterprise/customer-facing product — only used as internal infrastructure (Visible, Augment Me).
- Direct experience with planet-scale compute/storage resource management (data center capacity, workload placement) — not supported by source material.

---

## Reference: What is CPNI (Customer Proprietary Network Information)
Not company-specific — general regulatory background relevant to telecom compliance work (e.g., at Visible).

- **Definition** — CPNI compliance is the set of FCC-regulated rules telecom/VoIP providers must follow to protect privacy/security of a consumer's call logs, billing details, and network usage data.
- **Included in CPNI** — call times, dates, durations, destination numbers, types of service, billing patterns.
- **Not included** — public directory info (names, addresses, primary phone numbers), financial/credit card data.
- **Core compliance requirements**:
  - Customer consent (opt-in/opt-out) before using/sharing CPNI for marketing outside the current service category.
  - Authentication protocols — verify customer identity (passwords, PINs, photo IDs) before account access.
  - Data safeguards & breach reporting — internal security controls, law enforcement/customer breach notification, incident response plans.
  - Employee training on data protection and authentication procedures.
  - Annual certification filed with the FCC documenting security practices.