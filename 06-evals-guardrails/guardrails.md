# Guardrails · Pulse Intelligence

> Module 06 · Evals & Guardrails. What Pulse Intelligence must never do, how each rule is enforced, and what happens when it's triggered.

## Guardrails

| # | Risk | Guardrail | Where it's enforced (input / retrieval / output / action) | What happens when it triggers |
|---|---|---|---|---|
| G1 | _e.g. flags risk with no evidence_ | _every risk claim must cite a source_ | _output_ | _block and show "insufficient evidence"_ |
| G2 | _e.g. contacts a customer without approval_ | _…_ | _action_ | _…_ |
| G3 | _e.g. exposes another customer's data_ | _…_ | _retrieval_ | _…_ |
| G4 | _…_ | _…_ | _…_ | _…_ |

## Human oversight

_Which decisions always stay with a CSM or manager, and why._

_____

## Monitoring

_How you'll know in production that a guardrail is firing too often, or not enough._

_____

## Residual risk

_The risk you're accepting, and why it's acceptable._

_____
