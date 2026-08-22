# Nscale (nscale)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
