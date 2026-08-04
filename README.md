# Protect AI (protectai)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Protect AI is an AI/ML security platform (now part of Palo Alto Networks) whose products secure the AI lifecycle from model selection to runtime. Its developer surface centers on LLM Guard, an open-source Python toolkit of prompt and output scanners that ships a self-hostable REST API for real-time input/output sanitization. Commercial products - Guardian (model scanning), Recon (LLM red-teaming), and Layer (runtime protection) - are delivered through a portal under sales-led terms.

> **Acquisition note:** Palo Alto Networks completed its acquisition of Protect AI in July 2025. Protect AI's products are being integrated into the Palo Alto Networks Prisma AIRS AI security platform while retaining their existing branding. The open-source projects (LLM Guard, ModelScan) remain Apache 2.0.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/protectai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/protectai/refs/heads/main/apis.yml)

## Tags

- AI
- ML
- Security
- LLM
- Guardrails

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### LLM Guard (Scanners)

Open-source (Apache 2.0) toolkit of input and output scanners that detect, redact, and sanitize LLM prompts and responses for prompt injection, PII, toxicity, secrets, and more. The llm-guard-api service wraps the library in a self-hostable FastAPI app exposing /analyze and /scan endpoints for prompts and outputs.

- **Human URL:** [https://llm-guard.com/api/overview/](https://llm-guard.com/api/overview/)
- **Base URL:** `http://localhost:8000`

#### Tags

- LLM
- Guardrails
- Prompt Injection
- PII

#### Properties

- [Documentation](https://llm-guard.com/)
- [API Reference](https://llm-guard.com/api/overview/)
- [OpenAPI](openapi/protectai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [GitHub](https://github.com/protectai/llm-guard)
- [Postman Collection](collections/protectai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/protectai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Guardian (Model Scanning)

Commercial AI model security product that scans first- and third-party models for serialization attacks, malicious code, and supply-chain threats before they reach production. The open-source ModelScan project (Apache 2.0) provides the underlying model-scanning engine; Guardian itself is a sales-led platform without a documented public REST API.

- **Human URL:** [https://protectai.com/guardian](https://protectai.com/guardian)
- **Base URL:** `https://protectai.com/guardian`

#### Tags

- Model Scanning
- Supply Chain
- MLSecOps

#### Properties

- [Documentation](https://protectai.com/guardian)
- [GitHub](https://github.com/protectai/modelscan)

### Recon (Red-Teaming)

Commercial automated red-teaming product that rigorously tests LLM and GenAI applications for vulnerabilities, jailbreaks, and policy violations. Delivered as a sales-led platform; no public REST API surface is documented.

- **Human URL:** [https://protectai.com/recon](https://protectai.com/recon)
- **Base URL:** `https://protectai.com/recon`

#### Tags

- Red Teaming
- Adversarial Testing
- LLM

#### Properties

- [Documentation](https://protectai.com/recon)

### Layer (Runtime)

Commercial runtime security product that monitors and controls AI applications in production with deep visibility and inline threat prevention. Delivered as a sales-led platform; no public REST API surface is documented.

- **Human URL:** [https://protectai.com/layer](https://protectai.com/layer)
- **Base URL:** `https://protectai.com/layer`

#### Tags

- Runtime Security
- Observability
- Threat Detection

#### Properties

- [Documentation](https://protectai.com/layer)

## Common Properties

- [GitHub Organization](https://github.com/protectai)
- [LinkedIn](https://www.linkedin.com/company/protect-ai)
- [Website](https://protectai.com/)
- [Documentation](https://llm-guard.com/)
- [Plans](plans/protectai-plans-pricing.yml)
- [Rate Limits](rate-limits/protectai-rate-limits.yml)
- [Fin Ops](finops/protectai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
