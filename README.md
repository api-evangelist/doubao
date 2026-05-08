# ByteDance Doubao (doubao)

Doubao is ByteDance's foundation model family, served via the Volcano Engine Ark platform. Offers chat completions, deep reasoning, multimodal vision, embeddings, image generation (Seedream), video generation (Seedance), 3D generation, and TTS through OpenAI-compatible and native endpoints.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/doubao/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=doubao-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## Tags
- AI, LLM, Inference, ByteDance, Multimodal, Volcano Engine

## APIs
- **Volcano Engine Ark API** — OpenAI-compatible chat/responses/embeddings/batch/image/video/3D/TTS. Base URL `https://ark.cn-beijing.volces.com/api/v3`. [Docs](https://www.volcengine.com/docs/82379) · [Console](https://console.volcengine.com/ark/)

### Models
Doubao-Pro, Doubao-Lite, Doubao-Seed, Doubao-Seed-Code, deep-reasoning variants. Image: Seedream. Video: Seedance. Plus 3D generation, TTS, ASR.

## Plans, Rate Limits, FinOps
- [Plans](plans/doubao-plans-pricing.yml) — PAYG per-token/per-call (CNY); reserved-capacity for enterprises.
- [RateLimits](rate-limits/doubao-rate-limits.yml) — Per-endpoint RPM/TPM/concurrency configurable in Ark console.
- [FinOps](finops/doubao-finops.yml) — FOCUS-aligned, billed via Volcano Engine cloud invoice.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://www.volcengine.com/product/doubao)
- [Documentation](https://www.volcengine.com/docs/82379)

## Notes
- Volcano Engine documentation is primarily Chinese-language; CNY-denominated pricing.
- No public OpenAPI spec was discovered at the time of profiling; OpenAI-compatible surface follows the standard OpenAI shape.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
