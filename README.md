# free-model-aggregator-01: Pareto Lexicographic Quality-First Model Aggregator V3

Deterministic AI Model Aggregator submitted by `@yuheng-core` for the `free-model-aggregator-01` challenge ($500 pot).

## Strategy Overview
- **Solver**: `LexicographicQualityRouter` (Strict Pareto Lexicographic Filter)
- **Architecture**: Multi-dimensional Pareto ordering across [is_free, meets_caps, rating_milli, headroom] ensuring zero quality degradation
- **Wire Support**: Dual-wire OpenAI Chat Completions (`/v1/chat/completions`) & Anthropic Messages (`/v1/messages`), supporting JSON and streaming SSE.
- **Failover**: Proactive rate-limit avoidance with zero-failure fallbacks across 10 free model providers.
- **Target Performance**: Score 99+ Calibrated Floor Router.
