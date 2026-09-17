# Kauan Borges — Software Engineer

I'm a software engineer at Bradesco, focused on backend development, with experience across web applications and distributed systems. I care about what software enables for its users, the constraints it needs to work within, and the evidence behind engineering decisions.

My main stack is Java and Spring Boot. My projects also include TypeScript, Angular, and Python.

## Selected work

### [Instant Payment System](https://github.com/borgeskauan/instant-payment-system)

A Pix-inspired inter-institution payment core exploring how to move money reliably under concurrent requests, duplicate messages, and failures. Built with Java, Spring Boot, Kafka, and PostgreSQL.

Two local benchmark runs sustained over **2,000 payments/s**, with **p99 completion latency below one second** and **no missing or contradictory results observed**. Completion was measured through confirmations received by the paying institution, rather than HTTP acceptance alone.

The [design](https://github.com/borgeskauan/instant-payment-system/blob/master/docs/design.md), [engineering evolution](https://github.com/borgeskauan/instant-payment-system/blob/master/docs/engineering-evolution.md), and [benchmark methodology](https://github.com/borgeskauan/instant-payment-system/blob/master/docs/performance.md) explain the decisions, tradeoffs, and scope of those results.

### Other recent work

- **[Valora](https://github.com/borgeskauan/valora)** — A WhatsApp-based expense tracker for recording income and expenses, managing recurring transactions, and querying financial records in natural language.
- **[SupportAI](https://github.com/borgeskauan/SupportAI)** — A local prototype that turns resolved support cases into FAQ drafts, with source cases alongside each draft for human review, editing, approval, or rejection.

[More projects](https://github.com/borgeskauan/personal-projects-aggregator) · [LinkedIn](https://www.linkedin.com/in/kauanborges/)
