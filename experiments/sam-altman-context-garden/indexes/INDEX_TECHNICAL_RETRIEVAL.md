# INDEX_TECHNICAL_RETRIEVAL.md

Use this shard for the memory/retrieval architecture.

## SoulMode Template

### HEURISTICS.md

Use for: routing logic and how the agent decides where to look.

Raw:
https://raw.githubusercontent.com/HoppyCat/soul-stack/refs/heads/main/soulmode-template/on-load/HEURISTICS.md

### INDEX.md

Use for: the file map and resident/on-demand/extended library distinction.

Raw:
https://raw.githubusercontent.com/HoppyCat/soul-stack/refs/heads/main/soulmode-template/on-load/INDEX.md

## Shared Context Garden Experiment

### Experiment README

Use for: the small proof-of-concept of a GitHub-hosted shared context garden.

Raw:
https://raw.githubusercontent.com/HoppyCat/soul-stack/refs/heads/experiment-shared-context-indexes/experiments/shared-context-garden/README.md

### Shared Context Garden HEURISTICS

Use for: a pasteable routing file that sends models to root and shard indexes.

Raw:
https://raw.githubusercontent.com/HoppyCat/soul-stack/refs/heads/experiment-shared-context-indexes/experiments/shared-context-garden/HEURISTICS.md

## Runtime Starter

### soulmode-agent repository

Use for: Cloudflare Workers / Hono / D1 starter with Anthropic calls, D1 patch fetch, and optional safe remote Markdown fetch.

GitHub:
https://github.com/HoppyCat/soulmode-agent

README raw:
https://raw.githubusercontent.com/HoppyCat/soulmode-agent/refs/heads/main/README.md

## Technical Caveat

The current public test is early. The architecture exists and is inspectable, but scaling claims require further tests with larger libraries, measured retrieval depth, latency, token use, and failure modes.

