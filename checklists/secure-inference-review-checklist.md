# Secure Inference Review Checklist

## Input Layer

* [ ] Input validation enforced
* [ ] Prompt injection patterns filtered
* [ ] Rate limiting applied

## Retrieval (RAG)

* [ ] Data sources trusted and validated
* [ ] Retrieval scope restricted
* [ ] Sensitive data access controlled

## LLM Layer

* [ ] System prompts protected
* [ ] Model behavior constrained
* [ ] Output variability controlled

## Tool Execution

* [ ] Explicit allowlist for tools
* [ ] Authorization enforced
* [ ] Actions logged and monitored

## Output Layer

* [ ] Sensitive data filtering
* [ ] Output validation rules applied
* [ ] User-visible content sanitized
