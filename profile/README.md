<p align="center">
  <strong>AEGIS / AION</strong><br />
  <em>Pre-execution governance infrastructure for autonomous systems.</em>
</p>

<p align="center">
  <a href="https://github.com/VerifywithAION/aion-guard-lite"><img alt="Wallet Guard Lite" src="https://img.shields.io/badge/Wallet%20Guard-Lite-0f172a?style=for-the-badge" /></a>
  <a href="https://github.com/VerifywithAION/aion-icli"><img alt="AION ICLI" src="https://img.shields.io/badge/AION-ICLI-111827?style=for-the-badge" /></a>
  <a href="https://github.com/VerifywithAION/aion-proof-lab"><img alt="Proof Lab" src="https://img.shields.io/badge/Proof-Lab-1f2937?style=for-the-badge" /></a>
</p>

<p align="center">
  <img alt="AEGIS primitive" src="https://img.shields.io/badge/Primitive-Intent%20%E2%86%92%20Preview%20%E2%86%92%20Policy%20%E2%86%92%20Receipt-065f46?style=flat-square" />
  <img alt="Decision model" src="https://img.shields.io/badge/Decision-ALLOW%20%2F%20WARN%20%2F%20BLOCK-b45309?style=flat-square" />
  <img alt="Execution posture" src="https://img.shields.io/badge/Posture-Proof%20Before%20Trust-7f1d1d?style=flat-square" />
</p>

---

## What AION is building

AION builds **governed execution primitives** for wallets, AI agents, automation, and runtime safety.

The core thesis is simple:

> Every autonomous execution system needs governance before consequence.

Modern systems can move money, approve permissions, mutate files, call APIs, deploy code, trigger trades, submit reports, and execute agent plans. The central question is no longer only whether a system *can* execute. The central question is whether it *should* execute.

AEGIS exists to answer that question before harm occurs.

---

## The execution firewall

Traditional firewalls inspect network traffic before it crosses a boundary.

AION inspects **execution intent** before it crosses a consequence boundary.

It asks:

- What is trying to execute?
- Who or what requested it?
- What authority does it use?
- What consequence could follow?
- Which policy applies?
- Should this be allowed, warned, or blocked?
- What receipt proves the decision?

Network Firewall:
Packet -> Inspect -> Policy -> Allow / Deny -> Log

AION Execution Firewall:
Intent -> Preview -> Policy -> Allow / Warn / Block -> Receipt

---

## The execution problem

Autonomous systems are gaining execution authority faster than their governance layers are maturing.

They can already:

- approve wallet permissions;
- move funds;
- call APIs;
- mutate files;
- deploy code;
- submit reports;
- trigger automation;
- act on behalf of users, teams, and agents.

AION treats execution as a governed event, not a blind command.

---

## The AEGIS primitive

Intent
  -> Preview
  -> Consequence Modeling
  -> Policy Evaluation
  -> ALLOW / WARN / BLOCK
  -> Receipt
  -> Execution Gate

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

## The AION decision surface

| Decision | Meaning | Execution posture |
|---|---|---|
| **ALLOW** | The action appears acceptable under current policy and context. | Permit or continue. |
| **WARN** | The action is ambiguous, risky, unusual, or needs explicit attention. | Add friction and explain consequence. |
| **BLOCK** | The action violates policy, red lines, or known safety constraints. | Stop before consequence. |

Every serious decision should produce a reason code, a consequence explanation, and an evidence receipt.

---

## First product beachhead: Wallet Guard

**Wallet Guard protects users before dangerous wallet actions are signed.**

Powered by **AION Governance OS**.

Wallet Guard is the first consumer-facing AEGIS product: wallet execution safety before approval, signing, or irreversible consequence.

Connect wallet
  -> Inspect session
  -> Preview consequence
  -> Apply policy profile
  -> ALLOW / WARN / BLOCK
  -> Generate receipt


---

## Repository map

| Repository | Domain | AEGIS function |
|---|---|---|
| [`aion-guard-lite`](https://github.com/VerifywithAION/aion-guard-lite) | Wallets | Govern wallet actions before approval or signing. |
| [`aion-guard-ui`](https://github.com/VerifywithAION/aion-guard-ui) | SaaS / beta dashboard | User-facing and admin-facing control surface for Wallet Guard. |
| [`aion-icli`](https://github.com/VerifywithAION/aion-icli) | Local AI tooling | Proof-before-trust governed AI CLI. |
| [`aion-proof-lab`](https://github.com/VerifywithAION/aion-proof-lab) | Proof systems | Evidence, verification, and proof infrastructure. |
| [`aion-counterfactual-engine`](https://github.com/VerifywithAION/aion-counterfactual-engine) | Simulation | Counterfactual reasoning before execution. |
| [`aion-finops-guard-lite`](https://github.com/VerifywithAION/aion-finops-guard-lite) | FinOps | Guard cost, cloud, and operational execution before spend. |
| [`aion-research-guard-lite`](https://github.com/VerifywithAION/aion-research-guard-lite) | Research | Govern claims, evidence, and research outputs before publication. |
| [`aion-quantum-guard-lite`](https://github.com/VerifywithAION/aion-quantum-guard-lite) | Quantum / advanced systems | Govern experimental execution under proof-first constraints. |
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

## What makes AION different

Most automation tools optimize for execution.

AION optimizes for governed execution.

That means the system asks:

1. What is the intent?
2. What context surrounds it?
3. What consequence could happen?
4. Which policy applies?
5. Should this be allowed, warned, or blocked?
6. What evidence proves the decision?

---

## Canonical one-liners

**AEGIS:** pre-execution governance infrastructure for autonomous systems.

**AION Governance OS:** the runtime layer for policy, preview, receipts, and governed execution.

**Wallet Guard:** protects users before dangerous wallet actions are signed.

**AION Execution Firewall:** an execution firewall for autonomous systems.

---

<p align="center">
  <strong>Before execution, prove consequence.</strong><br />
  <em>Govern the action before the action governs the outcome.</em>
</p>
