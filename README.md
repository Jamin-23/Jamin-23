### Jamin Al-Schlayan

Full-stack engineer in Germany (CET). I build products end-to-end and then keep them running: requirements, data model, API, interface, deployment, support.

**What I actually shipped**

- **PlatzScout** — therapy-place search & outreach SaaS. Built and operated alone, with paying customers, until it was discontinued: Next.js + Node, PostgreSQL, Keycloak, Stripe, Docker on a single VPS. ~46k lines of my own code. Where money and state had to be right, I kept the logic in pure functions with tests — see [platzscout-patterns](https://github.com/Jamin-23/platzscout-patterns) (refund policy, commission holds, Stripe webhook idempotency).
- **Fahrsense** — driving-school ERP (React, Spring Boot, React Native, PostgreSQL): scheduling, GPS routing, OCR, billing. End-to-end build, handed over.
- **AI scheduling pilot** — an LLM parses multilingual WhatsApp replies (DE/EN/AR), a deterministic engine decides which slots are legal, the instructor confirms. The model never writes a booking.
- **Video pipeline** — Python/Node automation over the Instagram, TikTok and YouTube APIs; 12M+ organic Instagram views on the output.

**How I work**

- Snapshot in, decision out: money and status logic stays testable, the database is a projection.
- Idempotency as a state machine, not a flag — webhooks retry, credits must not double.
- Boring deployment beats clever deployment. Docker, Caddy, as few moving parts as possible.

**Stack:** TypeScript · Node · React · Python · Java/Spring Boot · PostgreSQL · Prisma · Redis · Docker · Keycloak/OIDC · Stripe

Currently: IHK external examination, *Fachinformatiker für Anwendungsentwicklung* (planned 2027). Open to remote product engineering roles.

[Portfolio](https://jamin.al-schlayan.de) · [LinkedIn](https://www.linkedin.com/in/jamin-al-schlayan-5335321a2/) · jamin@al-schlayan.de
