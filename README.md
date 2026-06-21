# Nscale (nscale)

Nscale is an AI/GPU cloud that pairs serverless, OpenAI-compatible inference with on-demand GPU compute. The Serverless Inference API serves open models (Llama, Qwen, DeepSeek, GPT OSS, Mistral, Flux) at https://inference.api.nscale.com/v1 with pay-per-token billing, while the platform API provisions GPU clusters, compute instances, networks, and storage.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/nscale/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/nscale/refs/heads/main/apis.yml)

## Tags

- AI
- GPU
- Inference
- Serverless
- Cloud Compute

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Nscale Serverless Chat Completions API

OpenAI-compatible chat completions across Llama, Qwen, DeepSeek, GPT OSS, and Mistral models, with streaming (SSE), tool use, and multimodal vision inputs, served from Nscale serverless inference.

- **Human URL:** [https://docs.nscale.com/docs/inference/serverless-models/overview](https://docs.nscale.com/docs/inference/serverless-models/overview)
- **Base URL:** `https://inference.api.nscale.com/v1`

#### Tags

- Chat
- Completions
- LLM

#### Properties

- [Documentation](https://docs.nscale.com/docs/inference/serverless-models/overview)
- [API Reference](https://docs.nscale.com/api-reference)
- [OpenAPI](openapi/nscale-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](asyncapi/nscale-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/nscale.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nscale.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nscale Serverless Completions API

OpenAI-compatible legacy text completions endpoint that generates a continuation for a supplied prompt against a selected serverless model.

- **Human URL:** [https://docs.nscale.com/api-reference](https://docs.nscale.com/api-reference)
- **Base URL:** `https://inference.api.nscale.com/v1`

#### Tags

- Completions
- Text Generation

#### Properties

- [Documentation](https://docs.nscale.com/docs/inference/serverless-models/overview)
- [API Reference](https://docs.nscale.com/api-reference)
- [OpenAPI](openapi/nscale-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nscale.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nscale.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nscale Serverless Embeddings API

OpenAI-compatible embeddings endpoint returning vector representations of text for retrieval, clustering, and semantic search, served by models such as Qwen3 Embedding.

- **Human URL:** [https://docs.nscale.com/api-reference](https://docs.nscale.com/api-reference)
- **Base URL:** `https://inference.api.nscale.com/v1`

#### Tags

- Embeddings
- Vectors
- Semantic Search

#### Properties

- [Documentation](https://docs.nscale.com/docs/inference/serverless-models/overview)
- [API Reference](https://docs.nscale.com/api-reference)
- [OpenAPI](openapi/nscale-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nscale.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nscale.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nscale Serverless Image Generation API

OpenAI-compatible text-to-image endpoint creating images from prompts using diffusion models such as Flux.1 [schnell], billed per megapixel.

- **Human URL:** [https://docs.nscale.com/api-reference](https://docs.nscale.com/api-reference)
- **Base URL:** `https://inference.api.nscale.com/v1`

#### Tags

- Image Generation
- Text to Image
- Diffusion

#### Properties

- [Documentation](https://docs.nscale.com/docs/inference/serverless-models/overview)
- [API Reference](https://docs.nscale.com/api-reference)
- [OpenAPI](openapi/nscale-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nscale.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nscale.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nscale Models API

Lists serverless models available for inference with identifiers, context length, and per-token pricing metadata via the OpenAI-compatible models endpoint.

- **Human URL:** [https://docs.nscale.com/api-reference](https://docs.nscale.com/api-reference)
- **Base URL:** `https://inference.api.nscale.com/v1`

#### Tags

- Models
- Catalog

#### Properties

- [Documentation](https://docs.nscale.com/docs/inference/serverless-models/overview)
- [API Reference](https://docs.nscale.com/api-reference)
- [OpenAPI](openapi/nscale-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nscale.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nscale.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nscale GPU Compute and Clusters API

Platform API for provisioning and managing GPU compute instances, networks, security groups, object storage, organizations, and projects on the Nscale AI cloud.

- **Human URL:** [https://docs.nscale.com/api-reference](https://docs.nscale.com/api-reference)
- **Base URL:** `https://api.nscale.com`

#### Tags

- GPU
- Compute
- Clusters
- Infrastructure

#### Properties

- [Documentation](https://docs.nscale.com/docs/compute/overview)
- [API Reference](https://docs.nscale.com/api-reference)
- [OpenAPI](openapi/nscale-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nscale.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nscale.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/nscale)
- [Website](https://www.nscale.com)
- [Documentation](https://docs.nscale.com)
- [Plans](plans/nscale-plans-pricing.yml)
- [Rate Limits](rate-limits/nscale-rate-limits.yml)
- [Fin Ops](finops/nscale-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
