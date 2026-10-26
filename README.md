# Timothy Moswa

Senior software engineer — Java · Spring Boot · payments, lending, core banking and integrations.

Harare, Zimbabwe · [LinkedIn](https://linkedin.com/in/timothy-moswa-b63944105)

## What I work on

Nine years building backend systems for regulated finance. I'm currently a Lead Developer at a retail bank, where I build and run the Java/Spring Boot services behind card switching, digital lending, core banking integration and financial batch processing.

Before and alongside that, I built payment and enterprise integrations for Dutch and UK companies: Stripe and GoCardless, ABN AMRO's PSD2 open-banking APIs, SAP, Microsoft Dynamics 365 and Sage, shipped as microservices on Kubernetes on AWS.

Most of my work sits on money-movement paths, which shapes how I build: idempotent operations, explicit retry and compensation semantics, reconciliation between systems that disagree, audit trails and approval controls. Correctness over velocity.

I like the diagnostic end of the job — the defects that survive years in production because monitoring never surfaces them.

## Stack

- **Backend:** Java (8 · 17 · 21 · 25) · Spring Boot 2.3 → 3.5 · Spring Data JPA / Hibernate · Spring Security (JWT, OAuth2) · Spring Batch · Spring Cloud Config · Flyway · MapStruct · Maven
- **Payments & banking:** ISO 8583 (jPOS) · ISO 20022 · POS/ATM acquiring and issuing · reversals · settlement and reconciliation · RTGS straight-through processing · Finastra Fusion Essence · Temenos T24 · Apache Fineract · ESB integration · API Manager
- **Integrations:** Stripe · GoCardless · PSD2 open banking (ABN AMRO) · SAP · Microsoft Dynamics 365 · Sage · WhatsApp Business · Vonage
- **Lending:** origination workflows · credit scoring and affordability · bureau, AML and sanctions screening · disbursement · repayments and arrears
- **Data & platform:** PostgreSQL · MySQL · Redis · Hazelcast · RabbitMQ · Kafka · Keycloak · Docker · Kubernetes (EKS) · AWS · Nginx · GitLab CI · Prometheus · Grafana
- **Testing:** JUnit 5 · Mockito · Testcontainers
- **AI engineering:** Claude Code (hooks, skills, subagents) · spec-driven development · context engineering · agent guardrails
- **Frontend & other:** TypeScript · Next.js / React · TanStack Query · Tailwind · CakePHP 5 · Laravel · Flutter

## Currently

- Building **ai-context** — shared memory and guardrails for coding agents: hook-enforced rules, hash-checked journaled writes, and planner/reviewer subagents that must pass work against written acceptance criteria
- Building a multi-tenant microfinance platform on Apache Fineract — service decomposition, Keycloak identity, credit bureau integration

## Interested in

Payments infrastructure · core banking · open banking · regulated systems engineering · distributed-system correctness · the ISO 8583 → ISO 20022 migration · AI agents held to production controls

<sub>Employer work lives in private repositories. Public repos here are personal projects and experiments.</sub>
