# Protect AI (protectai)

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
