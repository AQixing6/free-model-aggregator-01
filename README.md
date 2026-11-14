# free-model-aggregator-01: Lexicographic Quality-First Aggregator V2

Deterministic AI Model Aggregator submitted by `@aqixing6` for the `free-model-aggregator-01` challenge ($500 pot).

## Strategy Overview
- **Solver**: `LexicographicQualityRouter` (Pure Lexicographic Rating Maximizer)
- **Architecture**: Strict order by rating_milli descending with instantaneous boundary saturation bypass
- **Wire Support**: Dual-wire OpenAI Chat Completions (`/v1/chat/completions`) & Anthropic Messages (`/v1/messages`), supporting JSON and streaming SSE.
- **Failover**: Proactive rate-limit avoidance with zero-failure fallbacks across 10 free model providers.
