# Pulse Intelligence · PulseHQ

> _(one-line pitch: what Pulse Intelligence does, for whom, in one sentence)_

_Your name · cohort · date_

This repo is my final project for the **AI Product Management Certification**. I'm the Senior Product Manager at **PulseHQ**, building **Pulse Intelligence**: an AI-powered customer intelligence platform that helps Customer Success teams turn fragmented customer data into actionable insight. Read the full scenario in [`PROJECT-BRIEF.md`](PROJECT-BRIEF.md).

**How to use this template:** click **Use this template → Create a new repository**, name it `pulsehq`, and commit each module's artifacts as you complete them. Each module's outputs inform the next. In Module 8, you bring everything together into your final product specification and presentation.

> **The central question:** How can we use AI to help Customer Success teams identify customer risk earlier, understand the evidence, and take the right action before it becomes churn?

**Signals → Insights → Risk → Recommendation → Action**

---

## Module artifacts

### 01 · Prompting
_Define and shape how Pulse Intelligence behaves._
- **Skill file**, [`01-prompting/skill-file.md`](01-prompting/skill-file.md)
- **Working prototype and debrief**, [`01-prompting/prototype.md`](01-prompting/prototype.md)

### 02 · Opportunity & Feasibility
_Decide which AI opportunity to pursue and how to approach it._
- **Decision matrix**, [`02-opportunity-feasibility/decision-matrix.md`](02-opportunity-feasibility/decision-matrix.md)
- **Strategy one-pager**, [`02-opportunity-feasibility/strategy-one-pager.md`](02-opportunity-feasibility/strategy-one-pager.md)

### 03 · RAG & AI Requirements
_Define the information architecture and requirements that ground AI outputs in relevant evidence._
- **AI PRD**, [`03-rag-ai-requirements/prd.md`](03-rag-ai-requirements/prd.md)
- **RAG architecture specification**, [`03-rag-ai-requirements/rag-architecture.md`](03-rag-ai-requirements/rag-architecture.md)

### 04 · AI-Native UX
_Design how CSMs interact with, question and act on AI insights._
- **User flow**, [`04-ai-native-ux/user-flow.md`](04-ai-native-ux/user-flow.md)
- **Prototype**, [`04-ai-native-ux/prototype.md`](04-ai-native-ux/prototype.md)
- **Trust-gap analysis**, [`04-ai-native-ux/trust-gap-analysis.md`](04-ai-native-ux/trust-gap-analysis.md)

### 05 · Agentic Workflows
_Design how AI investigates customer risk and carries out approved tasks._
- **Agent workflow specification**, [`05-agentic-workflows/agent-workflow-spec.md`](05-agentic-workflows/agent-workflow-spec.md)
- **Agent Control Panel**, [`05-agentic-workflows/agent-control-panel.md`](05-agentic-workflows/agent-control-panel.md)

### 06 · Evals & Guardrails
_Test whether the system is accurate, reliable and safe enough to trust._
- **Evaluation dataset**, [`06-evals-guardrails/eval-dataset.md`](06-evals-guardrails/eval-dataset.md)
- **Human eval rubric**, [`06-evals-guardrails/human-rubric.md`](06-evals-guardrails/human-rubric.md)
- **Guardrails**, [`06-evals-guardrails/guardrails.md`](06-evals-guardrails/guardrails.md)

### 07 · Launch & Scale
_Plan production operations, monitoring, adoption and commercialisation._
- **Production plan**, [`07-launch-scale/production-plan.md`](07-launch-scale/production-plan.md)
- **Go-to-market plan**, [`07-launch-scale/go-to-market-plan.md`](07-launch-scale/go-to-market-plan.md)
- **Deployed prototype**, [`07-launch-scale/deployed-prototype.md`](07-launch-scale/deployed-prototype.md)

### 08 · Capstone
_Bring everything together into a complete product proposal._
- **Comprehensive AI product specification**, [`08-capstone/ai-product-specification.md`](08-capstone/ai-product-specification.md)
- **Final presentation**, [`08-capstone/final-presentation.md`](08-capstone/final-presentation.md). Link or commit your presentation here, then submit this repo's URL and the presentation on the Learning Platform.

---

## Repo structure

```
pulsehq/
├── README.md                              ← this overview
├── PROJECT-BRIEF.md                       ← the Pulse Intelligence scenario
├── 01-prompting/
│   ├── skill-file.md                      ← skill file (Role/Task/Constraints/Format)
│   └── prototype.md                       ← working prototype + debrief
├── 02-opportunity-feasibility/
│   ├── decision-matrix.md                 ← which AI opportunity to pursue
│   └── strategy-one-pager.md              ← how to approach it
├── 03-rag-ai-requirements/
│   ├── prd.md                             ← AI PRD
│   └── rag-architecture.md                ← RAG architecture specification
├── 04-ai-native-ux/
│   ├── user-flow.md                       ← how CSMs move through the product
│   ├── prototype.md                       ← UX prototype link + debrief
│   └── trust-gap-analysis.md              ← where trust breaks, and the fix
├── 05-agentic-workflows/
│   ├── agent-workflow-spec.md             ← how the agent investigates and acts
│   └── agent-control-panel.md             ← levers and rules of engagement
├── 06-evals-guardrails/
│   ├── eval-dataset.md                    ← realistic test cases
│   ├── human-rubric.md                    ← human evaluation rubric
│   └── guardrails.md                      ← what the system must never do
├── 07-launch-scale/
│   ├── production-plan.md                 ← operations, monitoring, adoption
│   ├── go-to-market-plan.md               ← commercialisation
│   └── deployed-prototype.md              ← live prototype link
└── 08-capstone/
    ├── ai-product-specification.md        ← the complete product proposal
    └── final-presentation.md              ← final presentation link
```

---

_Certification submission, AI Product Management Certification._
