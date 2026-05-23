# AEGIS / AION

**Pre-execution governance infrastructure for autonomous systems.**

AION builds governed execution primitives for wallets, AI agents, automation, and runtime safety.

## Core Thesis

Every autonomous execution system needs governance before consequence.

Modern systems can move money, approve permissions, mutate files, call APIs, deploy code, trigger trades, submit reports, and execute agent plans. The central question is not only whether a system can execute. The central question is whether it should execute.

AEGIS exists to answer that question before harm occurs.

## The AEGIS Primitive

```text
Intent
→ Preview
→ Consequence Modeling
→ Policy Evaluation
→ ALLOW / WARN / BLOCK
→ Receipt
→ Execution Gate
```

No meaningful execution should happen before the system can explain consequence, apply policy, and produce evidence.

## AION Governance OS

AION Governance OS is the infrastructure layer for the AEGIS primitive.

It provides:

- Pre-execution preview.
- Policy evaluation.
- Runtime boundaries.
- Session intelligence.
- Consequence modeling.
- ALLOW / WARN / BLOCK decision surfaces.
- Receipts and evidence trails.
- Operator/admin governance.
- Open-core and commercial governance boundaries.

## First Product Beachhead: Wallet Guard

**Wallet Guard protects users before dangerous wallet actions are signed.**

Powered by AION Governance OS.

Wallet Guard is the first clear consumer-facing use case of AEGIS: wallet execution safety before approval, signing, or irreversible consequence.

## Repository Map

| Repository | Domain | AEGIS Function |
|---|---|---|
| `aion-guard-lite` | Wallets | Govern wallet actions before approval/signing. |
| `aion-guard-ui` | SaaS / beta dashboard | User-facing and admin-facing control surface for Wallet Guard. |
| `aion-icli` | Local AI tooling | Proof-before-trust governed AI CLI. |
| `aion-control-plane` | Orchestration | Execution governance coordination and admissibility gates. |
| `aion-bounty-engine` | Security research | Governed autonomous vulnerability discovery and reporting. |
| `aion-creator-rights-office` | Creative/IP | Receipts and evidence for creative rights and ownership workflows. |
| `aion-proof-lab` | Proof systems | Evidence, verification, and proof infrastructure. |
| `aion-counterfactual-engine` | Simulation | Counterfactual reasoning before execution. |

## Public vs Commercial Boundary

AION follows an open-core strategy.

### Public Layer

The public layer exists to build trust, credibility, and community protection:

- Lite runtimes.
- Public demos.
- Basic local protection.
- Documentation.
- Proof artifacts.
- Example schemas.
- Education around pre-execution governance.

### Commercial Layer

The paid layer operationalizes the infrastructure:

- Hosted Wallet Guard dashboard.
- Live monitoring.
- Alerts.
- Receipt vault.
- Risk intelligence.
- Policy profile persistence.
- Admin controls.
- Enterprise APIs.
- Agent governance integrations.

## Canonical One-Liner

**AEGIS is pre-execution governance infrastructure for autonomous systems.**

## Product One-Liner

**Wallet Guard protects users before dangerous wallet actions are signed, powered by AION Governance OS.**
