# Alex Bouchard

### Applied AI product engineer and solo founder shipping consumer AI across web and iOS

> **Generate boldly. Validate cheaply. Kill ruthlessly. Scale what survives.**

I build at the seam between model behavior and production software: character systems, multimodal generation, safety boundaries, deterministic controls, cost protection, analytics, and the product loops that turn an AI capability into something people can actually use.

Founder of **[MidnightDev](https://midnightdev.dev)** in Houston, Texas. My operating rule is simple: models propose and challenge; explicit authority boundaries, human confirmation, and machine-checkable invariants decide what ships.

## Shipped products

- **[Yapword](https://yapword.com)** · [App Store](https://apps.apple.com/us/app/yapword-ai-word-game/id6774829903)  
  A daily word game where Yapoleon reacts to each guess, offers contextual hints, and comments on how the player actually played. Shipped on web and iOS with subscriptions, analytics, and production regression monitoring.

- **[That’s My Best](https://thatsmybest.com)** · [App Store](https://apps.apple.com/us/app/thats-my-best-ai-friend-quiz/id6788340469)  
  A social game that converts photo-grid screenshots into a playable friend quiz with generated questions, creator-confirmed answers, sharing, and group reveals. Shipped on web and iOS with multimodal generation, safety gating, analytics, and spend controls.

- **[Yapoleon’s Court](https://court.yapoleon.com)** · [Engineering case study](https://github.com/abouchard11/yapoleons-court)  
  A competitive character game where players try to earn Yapoleon’s favor. The model supplies bounded taste and personality while deterministic, server-owned code derives every score.

## Featured engineering evidence

- **[That’s My Best: Human-Confirmed Multimodal Quiz System](https://github.com/abouchard11/thats-my-best-engineering-case-study)** — an executable, sanitized reference model for creator-confirmed answers, server-owned truth, immutable sealed state, and deterministic group reveal.
- **[Yapoleon's Court](https://github.com/abouchard11/yapoleons-court)** — a competitive AI game where the model supplies bounded taste and character reactions while server-owned scoring, prompt-injection isolation, safety filters, fallbacks, and spend controls determine what counts.
- **[AI Boardroom Forecast Audit](https://github.com/abouchard11/ai-boardroom-forecast-audit)** — a reproducible case study showing how six synthetic decision lenses cut a roughly $65.9M forecast, then how a source-of-truth audit found a second $3.397M definition gap.
- **[gemini-reliability-proxy](https://github.com/abouchard11/gemini-reliability-proxy)** — model fallback, 429/5xx-aware routing, attempt and chain budgets, output-budget protection, and spend limits.
- **[llm-safety-gate](https://github.com/abouchard11/llm-safety-gate)** — fail-closed, classifier-agnostic content-safety state machine with quorum voting, refusal/noise separation, and per-item degradation.
- **[graphiti-neo4j-ops](https://github.com/abouchard11/graphiti-neo4j-ops)** — production-minded Graphiti/Neo4j operations with health-driven recovery, safe Community Edition backups, and local-only networking.

## Research, IP, and operating systems

- **[AI Citation Patterns](https://github.com/abouchard11/ai-citation-patterns)** — a dated, source-qualified field guide and reproducible benchmark for how AI search systems choose and cite sources.
- **[Midnight SEO Skills](https://github.com/abouchard11/midnight-seo-skills)** — a versioned operating system that turns the citation research into auditable content, structured-data, and technical-SEO workflows.
- **Independent patent development** — completed a provisional patent application package for an independently developed invention, including the specification, prior-art review, examiner brief, and 26 claims, with critique from an Australian patent reviewer.

## Selected commercial systems

- **[Jones Act Calculator](https://www.jonesactcalculator.com)** — an interactive, search-oriented maritime compensation resource with public methodology and explicit legal disclaimers.
- **[HTX Work Injury](https://htxworkinjury.com)** — a guided workplace-injury information system combining qualification logic, calculators, public safety data, and explicit legal disclaimers.

## Upstream contributions

- **[getzep/graphiti #1637](https://github.com/getzep/graphiti/pull/1637#pullrequestreview-4754097201)** — production validation review of the MCP cross-encoder rework, run on Neo4j 5.26 with a Gemini LLM and embedder. Reproduced a silent regression in which a missing optional dependency sent the fallback path back into the exact hard OpenAI dependency the PR set out to remove, masked behind a misleading warning, and flagged an undeclared ~2.3 GB model download on first run. The proposed fail-fast handling ships in [`mcp_server/src/services/factories.py`](https://github.com/getzep/graphiti/blob/main/mcp_server/src/services/factories.py#L436-L452).

- **[aaron-he-zhu/aaron-marketing-skills](https://github.com/aaron-he-zhu/aaron-marketing-skills/commit/2a0d1a9110e9d968d30622763defe6f0354e2be1)** — co-authored the merged commit that brought dated, first-party-sourced 2026 AI citation guidance into the `geo-content-optimizer` skill reference, including the crawler taxonomy across OpenAI (`OAI-SearchBot`, `GPTBot`, `ChatGPT-User`), Perplexity, and Google (`Google-Extended`, Preferred Sources, AI Mode). Upstreamed from [ai-citation-patterns](https://github.com/abouchard11/ai-citation-patterns); the maintainer expanded the evidence boundary before merge.

- **[getzep/graphiti #1698](https://github.com/getzep/graphiti/pull/1698)** — open follow-up PR, offered during the review above and opened once that work landed, adding explicit MCP reranker-provider configuration while preserving automatic provider matching, with test-first coverage for parsing, provider overrides, and service wiring. Scoped in [#1697](https://github.com/getzep/graphiti/issues/1697).

## Stack

`TypeScript` · `React` · `Next.js` · `Capacitor` · `Python` · `Supabase` · `PostgreSQL` · `Neo4j` · `Docker` · `Stripe` · `Tailwind CSS` · `Vercel` · `PostHog`

## Contact

Open to applied-AI product engineering roles and selective collaborations · Willing to relocate · [midnightdev.dev](https://midnightdev.dev) · alex@midnightdev.dev
