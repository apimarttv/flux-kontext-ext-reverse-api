# FLUX Kontext Max — reverse-engineered route (English)

> **1K $0.064** · model ID `flux-kontext-max` · **reverse-engineered/reverse engineering** route.

**[See live pricing](https://go.apimart.ai/k-6f06e1)** · **[Get an API key](https://go.apimart.ai/k-345b60)**

flux-kontext-ext-reverse-api is a **reverse-engineered** route for FLUX Kontext Max: callable ID `flux-kontext-max`, running in parallel with the official route (`—（平台直连）`) at a lower unit price.

## Pricing (snapshot 2026-09-28)

| Tier | Price |
| --- | --- |
| `1K` | $0.064 |

Prices are per delivered image; `n` in the request multiplies the total. Snapshot date **2026-09-28** — the live pricing page is authoritative.

## Quickstart

```bash
curl -X POST https://api.apimart.ai/v1/images/generations \
  -H 'Authorization: Bearer $APIMART_KEY' \
  -H 'Content-Type: application/json' \
  -d '{"model":"flux-kontext-max","prompt":"cozy reading nook, warm lamp, cinematic","size":"1:1","resolution":"1K","n":1}'
```

Async: submit → get `task_id` → poll `GET https://api.apimart.ai/v1/tasks/<task_id>` → read `cost` / `credits_cost` from the result. Parameter tables, `version`/`resolution`/`size` options and idempotency headers are documented on the model page reachable from the pricing link above.

## Reverse vs official route

| Route | Callable ID | Price |
| --- | --- | --- |
| **reverse-engineered** | `flux-kontext-max` | 1K $0.064 |
| official-routed | `—（平台直连）` | official list price, billed at ×0.8 group ratio |


## Keywords

`flux-kontext-ext` · `flux-kontext-max` · `reverse-engineered` · `reverse engineering` · `ai api gateway` · `ai-api-gateway` · `api relay` · `中转站` · `nano banana 2 api` · `gpt-image-2.5 api` · `ai api pricing` · `pay-as-you-go`

## Platform facts

- USD settlement, pay-as-you-go, **$1 minimum top-up**, no subscription.
- Operating since last year; ~100,000 registered users, mostly enterprise accounts.
- International invoices available on request.
- 307 models online (live `/v1/models`) as of 2026-09-28.

## Disclosure

This repository documents **APIMart**, a third-party API aggregator/gateway. It is **not affiliated with, endorsed by, or sponsored by** OpenAI, Google, Anthropic, xAI, ByteDance or any model vendor. Model names and trademarks belong to their owners. Prices are a point-in-time snapshot and may change; the vendor's console billing is authoritative.

