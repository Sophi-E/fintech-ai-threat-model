# Threat Modelling an LLM-Powered Customer Support Agent (Fintech)

A threat model applying **OWASP Top 10 for LLM Applications** and **MITRE ATLAS** to an AI-powered customer support assistant in a financial services context — the kind of
feature increasingly common across fintech products.

I built this as a practical exercise in security thinking about AI-integrated systems: mapping
architecture and trust boundaries, identifying realistic threats, and reasoning through
mitigations the way a security team would need to before shipping a feature like this in
production.

## Scope

This threat model is **hypothetical and illustrative**. The system, its architecture, and its
data flows are not based on any real company's actual implementation. Any resemblance to a real
product is coincidental — the point is to demonstrate the threat modelling process against a
realistic-shaped system, not to assess any specific organisation.

## What's covered

- **System description** — what the assistant does, what data and tools it has access to, and
  who can realistically reach it (including the gap between intended and actual users)
- **Architecture diagram** — with explicit trust boundaries marked
- **Threat table** — 8 threats mapped to OWASP LLM Top 10 and MITRE ATLAS
- **Deep dives** — two threats explored in detail: an illustrative attack narrative, why the
  naive/common defence fails, and what an actual mitigation looks like
- **Mitigation recommendations** — organized by architecture layer
- **Future work** — what dynamic/hands-on testing would look like beyond this modelling exercise

Full write-up: [`threat-model.md`](./threat-model.md)
Diagram: [`/diagrams`](./diagrams)

## Frameworks used

- [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
- [MITRE ATLAS](https://atlas.mitre.org/) — adversarial threat landscape for AI systems

## About

Software engineer and security professional, currently deepening AI security expertise. This project is part of a broader effort to apply traditional
security fundamentals to AI-integrated systems, with a focus on the financial services sector.

Connect on [LinkedIn](https://linkedin.com/in/sophia-enakpoya/) — happy to talk threat modelling, AI security, or fintech risk.

## License

MIT — feel free to adapt this threat modelling structure for your own AI feature reviews.
