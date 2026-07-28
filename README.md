# Alex Bouchard

### AI-native full-stack product engineer shipping consumer AI across web and iOS

I build character-driven products that survive contact with real users: responsive interfaces, persistent personality, model reliability, safety boundaries, cost controls, analytics, and the unglamorous production machinery that keeps the magic alive.

Founder of **[MidnightDev](https://midnightdev.dev)**. TypeScript, React, Python, Supabase, PostgreSQL, Neo4j, Docker, and Vercel.

## Shipped consumer AI

- **[Yapword](https://yapword.com)** · [App Store](https://apps.apple.com/us/app/yapword-ai-word-game/id6774829903)  
  A daily word game where Yapoleon, a reactive AI character, watches each guess, responds in real time, offers contextual hints, and turns the player’s actual game into a personalized performance. Three daily difficulty modes, themed games, challenge duels, subscriptions/IAP, PostHog instrumentation, and production regression monitoring.

- **[That’s My Best](https://thatsmybest.com)** · [App Store](https://apps.apple.com/us/app/thats-my-best-ai-friend-quiz/id6788340469)  
  An AI-native social game that converts a creator’s photo-grid screenshots into a playable friend quiz with generated questions, answer-specific reactions, sharing, and group reveal loops. Shipped on web and iOS with multimodal generation, safety gating, analytics, and cost controls.

## Production systems extracted into open source

- **[yapoleons-court](https://github.com/abouchard11/yapoleons-court)** — character-driven AI game architecture with deterministic server-owned scoring, prompt-injection isolation, anti-sycophancy boundaries, safety filtering, observability, and spend protection.
- **[llm-safety-gate](https://github.com/abouchard11/llm-safety-gate)** — fail-closed, classifier-agnostic content-safety state machine with quorum voting, refusal/noise separation, and per-item degradation.
- **[gemini-reliability-proxy](https://github.com/abouchard11/gemini-reliability-proxy)** — model fallback, 429/5xx-aware routing, attempt and chain budgets, output-budget protection, and denial-of-wallet limits.
- **[graphiti-neo4j-ops](https://github.com/abouchard11/graphiti-neo4j-ops)** — production-minded Graphiti/Neo4j operations with health-driven recovery, safe Community Edition backups, and local-only networking.

## Upstream open-source work

- **[getzep/graphiti #1698](https://github.com/getzep/graphiti/pull/1698)** — open PR adding explicit MCP reranker-provider configuration while preserving automatic provider matching; includes test-first coverage for parsing, provider overrides, and service wiring.
- **[getzep/graphiti #1669](https://github.com/getzep/graphiti/pull/1669)** — original provider-dependency diagnosis and focused proposal; closed after production-testing the broader fix in #1637, then followed with #1698.
- **[rarelygoeshere/WordleWeb #8](https://github.com/rarelygoeshere/WordleWeb/pull/8)** — merged contribution adding Yapword and Yapoleon’s Court to the community word-game directory.

## Stack

`TypeScript` · `React` · `Next.js` · `Capacitor` · `Python` · `Supabase` · `PostgreSQL` · `Neo4j` · `Docker` · `Stripe` · `Tailwind CSS` · `Vercel` · `PostHog`

## Location

Houston, Texas · Willing to relocate to the Bay Area and work hybrid in Redwood City.

## Contact

[midnightdev.dev](https://midnightdev.dev) · alex@midnightdev.dev
