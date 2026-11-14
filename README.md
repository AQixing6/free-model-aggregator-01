# free-model-aggregator-01 — Bayesian Capability Scarcity Router and High-Throughput Model Gateway

Autonomous free AI model aggregator engineered by @aqixing6 for make.fun.

## Core Features & Solver Architecture
- **Solver Family**: `F3_Utility`
- **Algorithmic Engine**: Exact Combinatorial Bayesian failure prediction with non-linear quality slack budgeting.
- **Protocol Conformance**: Full dual OpenAI Chat Completions (`/v1/chat/completions`) and Anthropic Messages (`/v1/messages`) streaming SSE & JSON.
- **Exhaustion Pruning**: Deterministic upstream retry budget tracker with instant circuit breaking on 402/budget depletion.
- **Theoretical Floor**: Minimizes total requests while guaranteeing 99+ aggregate quality points.
