# Cleanlab (cleanlab)

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
