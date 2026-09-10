# TrustCore AI Systems Oy

**Control before consequence.**

TrustCore is a Finnish AI infrastructure company developing runtime governance and action-boundary controls for agentic systems.

> A recommendation is not permission. A correct answer is not authority to act.

As AI systems gain access to tools, files, APIs and operational workflows, output quality is only part of the problem. Identity, delegated authority, current policy, evidence and consequence must be evaluated before a proposed action becomes an external effect.

[Website](https://trustcore.fi) · [Public architecture](https://trustcore.fi/architecture.html) · [Evidence approach](https://trustcore.fi/proof.html) · [Governance Before Decision](https://trustcore.fi/book.html)

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

## Company

**TrustCore AI Systems Oy**  
Finland · Business ID 3618251-2  
Founder & AI Architect: Kari “Gary” Hyötylä

Business and partnerships: [kari.hyotyla@trustcore.fi](mailto:kari.hyotyla@trustcore.fi)  
Security reports: [security@trustcore.fi](mailto:security@trustcore.fi)

For sensitive security matters, please follow our [security policy](SECURITY.md).

---

© 2026 TrustCore AI Systems Oy. All rights reserved.
