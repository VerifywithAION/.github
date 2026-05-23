<p align="center">
  <strong>AEGIS / AION</strong><br />
  <em>Pre-execution governance infrastructure for autonomous systems.</em>
</p>

<p align="center">
  <a href="https://github.com/VerifywithAION/aion-guard-lite"><img alt="Wallet Guard Lite" src="https://img.shields.io/badge/Wallet%20Guard-Lite-0f172a?style=for-the-badge" /></a>
  <a href="https://github.com/VerifywithAION/aion-icli"><img alt="AION ICLI" src="https://img.shields.io/badge/AION-ICLI-111827?style=for-the-badge" /></a>
  <a href="https://github.com/VerifywithAION/aion-proof-lab"><img alt="Proof Lab" src="https://img.shields.io/badge/Proof-Lab-1f2937?style=for-the-badge" /></a>
</p>

---

## What AION is building

AION builds **governed execution primitives** for wallets, AI agents, automation, and runtime safety.

The core thesis is simple:

> Every autonomous execution system needs governance before consequence.

Modern systems can move money, approve permissions, mutate files, call APIs, deploy code, trigger trades, submit reports, and execute agent plans. The central question is no longer only whether a system *can* execute. The central question is whether it *should* execute.

AEGIS exists to answer that question before harm occurs.

---

## The AEGIS primitive

```text
Intent
  -> Preview
  -> Consequence Modeling
  -> Policy Evaluation
  -> ALLOW / WARN / BLOCK
  -> Receipt
  -> Execution Gate
```

No meaningful execution should happen before the system can explain consequence, apply policy, and produce evidence.

---

## AION Governance OS

AION Governance OS is the infrastructure layer behind the AEGIS primitive.

It is designed around:

- **Pre-execution preview** — inspect intent before consequence.
- **Policy evaluation** — apply explicit governance rules.
- **Runtime boundaries** — separate safe observation from dangerous authority.
- **Session intelligence** — classify context before trust.
- **Consequence modeling** — explain what could happen if execution proceeds.
- **ALLOW / WARN / BLOCK decisions** — turn governance into action.
- **Receipts and evidence trails** — make execution auditable.
- **Operator/admin governance** — keep sensitive controls separated from public users.

---

## First product beachhead: Wallet Guard

**Wallet Guard protects users before dangerous wallet actions are signed.**

Powered by **AION Governance OS**.

Wallet Guard is the first consumer-facing AEGIS product: wallet execution safety before approval, signing, or irreversible consequence.

---

## Repository map

| Repository | Domain | AEGIS function |
|---|---|---|
| [`aion-guard-lite`](https://github.com/VerifywithAION/aion-guard-lite) | Wallets | Govern wallet actions before approval or signing. |
| [`aion-guard-ui`](https://github.com/VerifywithAION/aion-guard-ui) | SaaS / beta dashboard | User-facing and admin-facing control surface for Wallet Guard. |
| [`aion-icli`](https://github.com/VerifywithAION/aion-icli) | Local AI tooling | Proof-before-trust governed AI CLI. |
| [`aion-proof-lab`](https://github.com/VerifywithAION/aion-proof-lab) | Proof systems | Evidence, verification, and proof infrastructure. |
| [`aion-counterfactual-engine`](https://github.com/VerifywithAION/aion-counterfactual-engine) | Simulation | Counterfactual reasoning before execution. |
| `aion-control-plane` | Orchestration | Execution governance coordination and admissibility gates. |
| `aion-bounty-engine` | Security research | Governed autonomous vulnerability discovery and reporting. |
| `aion-creator-rights-office` | Creative/IP | Receipts and evidence for creative rights and ownership workflows. |

---

## Open-core boundary

AION follows an open-core strategy.

### Public layer

The public layer exists to build trust, credibility, and community protection:

- Lite runtimes.
- Public demos.
- Basic local protection.
- Documentation.
- Proof artifacts.
- Example schemas.
- Education around pre-execution governance.

### Commercial layer

The paid layer operationalizes the infrastructure:

- Hosted Wallet Guard dashboard.
- Live monitoring and alerts.
- Receipt vault.
- Risk intelligence.
- Policy profile persistence.
- Admin controls.
- Enterprise APIs.
- Agent governance integrations.

---

## Canonical one-liners

**AEGIS:** pre-execution governance infrastructure for autonomous systems.

**AION Governance OS:** the runtime layer for policy, preview, receipts, and governed execution.

**Wallet Guard:** protects users before dangerous wallet actions are signed.

---

<p align="center">
  <strong>Before execution, prove consequence.</strong>
</p>
