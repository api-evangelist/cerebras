# Cerebras (cerebras)

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

Cerebras Systems designs the wafer-scale WSE-3 chip and the CS-2/CS-3 AI systems built around it, and operates Cerebras Inference, a high-throughput cloud platform for running open-source large language models including Llama, Qwen, and DeepSeek families. Cerebras Inference is positioned as one of the fastest token-generation services in the market, with OpenAI-compatible REST endpoints, first-party Python and Node.js SDKs, and dedicated and on-prem deployment options for enterprise customers. The company partners with OpenAI, AWS, GSK, Mayo Clinic, and Notion, and maintains an active open source presence including its model garden and inference cookbook on GitHub.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cerebras/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cerebras/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- AI Inference
- Large Language Models
- Wafer Scale
- Hardware
- Cloud
- OpenAI Compatible
- LLM
- SDK
- Accelerator
- High Performance Computing

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Cerebras Inference API

The Cerebras Inference API exposes ultra-low-latency inference for open-weight large language models including Llama 3.1, Llama 4, Qwen, and other frontier open models. The API is OpenAI-compatible at the chat completions surface, supports streaming, and is consumed via first-party Python and Node.js SDKs as well as raw HTTP. Dedicated and on-prem deployments are available for production workloads.

- **Human URL:** [https://inference-docs.cerebras.ai](https://inference-docs.cerebras.ai)
- **Base URL:** `https://api.cerebras.ai/v1`

#### Tags

- Inference
- LLM
- Chat Completions
- OpenAI Compatible
- Streaming
- REST

#### Properties

- [Documentation](https://inference-docs.cerebras.ai)
- [Getting Started](https://inference-docs.cerebras.ai/quickstart)
- [SDK](https://github.com/Cerebras/cerebras-cloud-sdk-python)
- [SDK](https://github.com/Cerebras/cerebras-cloud-sdk-node)
- [Cookbook](https://github.com/Cerebras/Cerebras-Inference-Cookbook)
- [V S Code Extension](https://github.com/Cerebras/vscode-cerebras-chat)
- [M C P](https://github.com/Cerebras/cerebras-code-mcp)
- [Postman Collection](collections/cerebras.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cerebras.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://cerebras.ai)
- [Documentation](https://inference-docs.cerebras.ai)
- [Developer  Portal](https://cloud.cerebras.ai)
- [Pricing](https://www.cerebras.ai/inference)
- [GitHub Organization](https://github.com/Cerebras)
- [Model Zoo](https://github.com/Cerebras/modelzoo)
- [Blog](https://www.cerebras.ai/blog)
- [LinkedIn](https://www.linkedin.com/company/cerebras-systems)
- [Twitter](https://twitter.com/CerebrasSystems)
- [Status](https://status.cerebras.ai)
- [L L Ms Txt](https://inference-docs.cerebras.ai/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
