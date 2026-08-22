# Cleanlab (cleanlab)

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

Cleanlab is a data-and-AI trust platform. Its Trustworthy Language Model (TLM) wraps any LLM with a real-time trustworthiness score to catch hallucinations, Cleanlab Studio curates and labels training data and deploys reliable ML models, and Codex adds a safety, guardrail, and remediation layer for AI assistants and RAG. The open-source cleanlab library underpins it all with data-centric AI.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cleanlab/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cleanlab/refs/heads/main/apis.yml)

## Tags

- AI
- LLM
- Trustworthiness
- Data Quality
- Guardrails

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Trustworthy Language Model (TLM)

Wraps any base LLM (GPT, Claude, Gemini, Llama, and more) with a real-time 0-1 trustworthiness score to detect hallucinations and unreliable answers. Exposed via an OpenAI-compatible Chat Completions endpoint (trustworthiness returned in tlm_metadata) and via prompt / get_trustworthiness_score operations.

- **Human URL:** [https://help.cleanlab.ai/tlm/](https://help.cleanlab.ai/tlm/)
- **Base URL:** `https://api.cleanlab.ai/api/v1/openai_trustworthy_llm`

#### Tags

- TLM
- Trustworthiness
- Hallucination Detection
- LLM

#### Properties

- [Documentation](https://help.cleanlab.ai/tlm/)
- [API Reference](https://help.cleanlab.ai/tlm/api/python/tlm/)
- [OpenAPI](openapi/cleanlab-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](asyncapi/cleanlab-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/cleanlab.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cleanlab.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/cleanlab/cleanlab-tlm)

### Cleanlab Studio

Cloud platform for data-centric AI - upload datasets, run automated data curation and error detection, train AutoML models, and deploy them for real-time REST inference. Driven by the cleanlab-studio Python client and a REST inference API.

- **Human URL:** [https://help.cleanlab.ai/studio/](https://help.cleanlab.ai/studio/)
- **Base URL:** `https://api.cleanlab.ai`

#### Tags

- Data Curation
- Labeling
- AutoML
- Inference

#### Properties

- [Documentation](https://help.cleanlab.ai/studio/quickstart/api/)
- [API Reference](https://help.cleanlab.ai/studio/api/python/studio/)
- [OpenAPI](openapi/cleanlab-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cleanlab.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cleanlab.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/cleanlab/cleanlab-studio)

### Codex

Safety and reliability layer for AI assistants and RAG. Validates every AI response, decides whether to guardrail it, scores it across multiple eval criteria, escalates to subject-matter experts, and returns expert answers to remediate bad responses. Integrated via project access keys.

- **Human URL:** [https://help.cleanlab.ai/codex/](https://help.cleanlab.ai/codex/)
- **Base URL:** `https://api.cleanlab.ai`

#### Tags

- Guardrails
- Validation
- Remediation
- RAG

#### Properties

- [Documentation](https://help.cleanlab.ai/codex/)
- [API Reference](https://help.cleanlab.ai/codex/api/python/project/)
- [OpenAPI](openapi/cleanlab-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cleanlab.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cleanlab.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/cleanlab/cleanlab-codex)

### Open-Source Library

The original open-source cleanlab Python library for data-centric AI - finds and fixes label errors, outliers, and other data issues using confident learning. Runs locally (pip install cleanlab); free, not a hosted API.

- **Human URL:** [https://docs.cleanlab.ai/](https://docs.cleanlab.ai/)
- **Base URL:** `https://github.com/cleanlab/cleanlab`

#### Tags

- Open Source
- Confident Learning
- Data-Centric AI

#### Properties

- [Documentation](https://docs.cleanlab.ai/)
- [GitHub](https://github.com/cleanlab/cleanlab)

## Common Properties

- [GitHub Organization](https://github.com/cleanlab)
- [LinkedIn](https://www.linkedin.com/company/cleanlab)
- [Website](https://cleanlab.ai)
- [Documentation](https://help.cleanlab.ai)
- [Plans](plans/cleanlab-plans-pricing.yml)
- [Rate Limits](rate-limits/cleanlab-rate-limits.yml)
- [Fin Ops](finops/cleanlab-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
