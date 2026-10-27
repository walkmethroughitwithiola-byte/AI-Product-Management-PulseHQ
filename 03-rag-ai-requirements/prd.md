# AI PRD · Pulse Intelligence

> Module 03 · RAG & AI Requirements. The AI product requirements doc for Pulse Intelligence, specifying all six harness surfaces, built with the **M3 · AI PRD Builder** (archetype and starting settings from the **M3 · Harness Architecture Decider**). Paste the tool's markdown over this file. The retrieval design behind surface 01 lives in [`rag-architecture.md`](rag-architecture.md).

## Problem & user

_The Customer Success problem and which CSMs have it._

_____

## The harness

| Surface | Specification |
|---|---|
| 01 Context | _what Pulse Intelligence gets to see_ |
| 02 Tools | _the verb list_ |
| 03 Loop | _turn ceiling and escalation_ |
| 04 Memory | _what persists, at what scope_ |
| 05 Permissions | _read … · draft … · write … · send …_ |
| 06 Verification | _the check before output ships_ |

## 01 Context · Data Requirements

- **Required sources:** _name actual systems: CRM, product usage, support tickets, customer conversations, renewal data. Not "internal docs."_
- **Deliberate exclusions:** _what you left out, and why._
- **SLA of truth:** _how fast a change in a source becomes a change in the answer._
- **When a source is unreachable:** _fail loudly, or degrade how?_

## 02 Tools · System Capabilities

- **The verb list:** _every function Pulse Intelligence may call, with its side-effect class (read / draft / write / send)._
- **Deliberate omissions:** _the tools you did not build, and why. Name at least one._

## 03 Loop · AI Costs & Latency

- **Turn ceiling:** _e.g. 5 turns per request._
- **Escalation trigger:** _what makes it stop and hand back to a CSM._
- **Latency and cost target:** _e.g. p95 under 8s, under $0.12 per account review._

## 04 Memory · Data Requirements

- **What persists, at what scope:** _turn, session, CSM, account, or team._
- **Expiry:** _TTL per fact._
- **Write rules:** _who outranks the model when a CSM disagrees._

## 05 Permissions · AI Risks & Mitigations

| Side-effect class | Tier |
|---|---|
| read | _auto / confirm / blocked_ |
| draft | _auto / confirm / blocked_ |
| write | _auto / confirm / blocked_ |
| send | _auto / confirm / blocked_ |

**Justification:** _blast radius and recoverability for each non-obvious tier (e.g. emailing a customer, changing a CRM record)._

## 06 Verification · AI Testing & Measurement

- **The check before output ships:** _what is checked, against what bar. E.g. every risk claim cites retrieved evidence._
- **Failure behaviour:** _what happens when the check fails. Silently dropping the output is never the answer._

## Eval plan

_Stub. Module 06 fills this in: the evaluation dataset, human rubric and guardrails in `06-evals-guardrails/`._

## Out of scope

_Any capability not in the verb list, and any action tiered `blocked`. Both are decisions on the record, not omissions._
