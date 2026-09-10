# TrustCore AI Systems Oy

**Control before consequence.**

TrustCore is a Finnish AI infrastructure company developing runtime governance and action-boundary controls for agentic systems.

> A recommendation is not permission. A correct answer is not authority to act.

As AI systems gain access to tools, files, APIs and operational workflows, output quality is only part of the problem. Identity, delegated authority, current policy, evidence and consequence must be evaluated before a proposed action becomes an external effect.

[Website](https://trustcore.fi) · [Company](https://trustcore.fi/company.html) · [Public architecture](https://trustcore.fi/architecture.html) · [Evidence approach](https://trustcore.fi/proof.html) · [Governance Before Decision](https://trustcore.fi/book.html)

## Company

### Built in Finland. Focused on the boundary.

**TrustCore AI Systems Oy** is a founder-led AI infrastructure company developing runtime governance, controlled execution and evidence before consequence.

Our focus is the transition from recommendation to action. As AI systems become capable of changing files, calling tools, sending messages, deploying code or affecting customers, they need more than good instructions. They need explicit authority, bounded scope and a meaningful opportunity to refuse before an external effect.

TrustCore develops control patterns and technical infrastructure that keep identity, delegated authority, policy, human approval and evidence explicit at that boundary.

### Development focus

- **Runtime governance** — observe relevant state, evaluate acceptability and enforce the decision before execution.
- **Action-boundary control** — separate a useful recommendation from permission to create an external effect.
- **Identity and policy** — bind authorization to the actor, action, target, scope and current conditions.
- **Deterministic routing** — make continuation, verification, escalation and refusal visible and reviewable.
- **Human final gates** — preserve a named human's ability to approve, refuse or defer consequential action.
- **Evidence discipline** — connect public claims to identifiable scope, conditions, outcomes and limitations.

### How we work

We begin with one consequential workflow small enough to inspect and meaningful enough to matter:

1. **Name the action** — where can AI output become an external effect?
2. **Name the authority** — who may approve it, in which role and scope?
3. **Define refusal** — what missing, stale or conflicting condition must stop it?
4. **Agree the evidence** — what record and observed outcome would demonstrate control?

Prototype development and scoped pilot discussions are underway. Technical details are shared only within an appropriate agreed scope.

### Founder

**Kari “Gary” Hyötylä — Founder & AI Architect**

Gary is a hands-on systems builder whose background spans decades of work across hardware, software and AI. TrustCore grows from a practical engineering question: how do we keep authority and human control explicit as systems become more capable?

He is also the author of *[Governance Before Decision](https://trustcore.fi/book.html)*, a field guide exploring proof, permission and human-controlled AI execution.

| Company detail | Information |
| --- | --- |
| Legal name | TrustCore AI Systems Oy |
| Business ID / Y-tunnus | 3618251-2 |
| Country | Finland |
| Founder & AI Architect | Kari “Gary” Hyötylä |
| Business and partnerships | [kari.hyotyla@trustcore.fi](mailto:kari.hyotyla@trustcore.fi) |
| Phone | [+358 41 711 1611](tel:+358417111611) |
| Security reports | [security@trustcore.fi](mailto:security@trustcore.fi) |

## The execution boundary

Our public design direction follows a simple control flow:

**Observe → Decide → Enforce → Execute**

Execution proceeds only when the required authority, scope and current conditions support it. Refusal, verification and escalation are valid control outcomes.

| Control concern | Boundary question |
| --- | --- |
| Identity-bound authorization | Who is requesting the action, in what role and within what scope? |
| Policy-bound routing | Which route is permitted under the current policy and environment state? |
| Fail-closed enforcement | What happens when authority, evidence or context is missing, stale or ambiguous? |
| Human final gate | Who can still approve, refuse or defer before consequence? |
| Reviewable evidence | What decision was made, why, and what effect actually followed? |

## Public work

- **[Public architecture brief](https://trustcore.fi/architecture.html)** — a conceptual view of the boundary between a proposed action and controlled execution.
- **[Evidence discipline](https://trustcore.fi/proof.html)** — how claims should remain attached to test scope, conditions and limitations.
- **[Governance Before Decision](https://trustcore.fi/book.html)** — a public field-guide preview about proof, permission and human-controlled AI execution.
- **[Scoped pilot tracks](https://trustcore.fi/pilots.html)** — narrowly defined workflows for evaluating authority, refusal and evidence before action.

## Repository status

This repository is TrustCore's public GitHub entry point. It will contain public-safe documentation and selected, scoped artifacts as they are ready for review.

Prototype development continues primarily in private repositories. This public repository does not claim certification, regulatory approval, independent validation, production deployment or completed customer deployments.

See [Public repository boundary](docs/PUBLIC-REPOSITORY-BOUNDARY.md) for what publication here does and does not mean.

For sensitive security matters, please follow our [security policy](SECURITY.md).

---

© 2026 TrustCore AI Systems Oy. All rights reserved.
