# RAG Architecture Specification · Pulse Intelligence

> Module 03 · RAG & AI Requirements. How Pulse Intelligence finds and uses the right evidence, so every risk flag and recommendation is grounded in real customer signals.

## Knowledge sources

| Source | What it contains | Owner | Update frequency | Structured or unstructured |
|---|---|---|---|---|
| CRM records | _…_ | _…_ | _…_ | _…_ |
| Product usage | _…_ | _…_ | _…_ | _…_ |
| Support tickets | _…_ | _…_ | _…_ | _…_ |
| Customer conversations | _…_ | _…_ | _…_ | _…_ |
| Renewal data | _…_ | _…_ | _…_ | _…_ |

## Ingestion and preparation

- **How each source gets in:** _API, export, connector._
- **Chunking:** _how unstructured text (tickets, call notes) is split, and why._
- **Metadata:** _what every chunk carries, e.g. account ID, date, source, sentiment._
- **Freshness:** _how stale data is detected and handled._

## Retrieval

- **Retrieval approach:** _keyword, semantic, hybrid, or structured query, per source._
- **Filtering:** _e.g. scope every retrieval to one account and a time window._
- **Ranking:** _how the most relevant evidence rises to the top._
- **How much context:** _how many pieces of evidence reach the model per request._

## Grounding and citation

- **Citation rule:** _how each claim links back to its evidence so a CSM can check it._
- **When evidence is missing or conflicting:** _what Pulse Intelligence says instead of guessing._

## Access and privacy

_Who can retrieve what. How customer data and personal information are protected._

_____

## Architecture diagram

_Sketch the flow from sources to answer: sources → ingestion → index → retrieval → model → cited output. Link or embed an image._

_____

## Retrieval quality

_How you'll measure whether retrieval finds the right evidence (feeds into Module 06)._

_____
