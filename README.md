# gateway

LLM gateway: tier-aware routing, streaming, rate limits and failover in front of mock LLM providers.

## Run

```bash
uv sync
uv run uvicorn gateway.main:app --reload
```

## Test

```bash
uv run pytest
```
