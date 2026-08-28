# AgentDiagnosticResponse Schema

Standalone JSON Schema (draft 2020-12) defining the structured diagnostic output contract for autonomous agent execution.

## Schema Location

[`schemas/agent-diagnostic-response/v3.json`](./schemas/agent-diagnostic-response/v3.json)

## Purpose

Hardened production-observability schema for agent diagnostics. Required fields enforce complete diagnostic narratives, root-cause identification, recommendations, trade-offs, next steps, quantitative metrics, canonical source attribution, cache status, and timestamp.

Optional `circuit_breaker_state` supports resilience patterns.

## Validation

Compatible with any draft-2020-12 JSON Schema validator.

## License

Released as standalone reference artifact.
