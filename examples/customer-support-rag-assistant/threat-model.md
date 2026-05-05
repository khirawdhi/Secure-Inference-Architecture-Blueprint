# Threat Model — Customer Support Assistant

## Key Threats

### Prompt Injection

User attempts to override instructions.

### Data Leakage

Sensitive internal data exposed via responses.

### Tool Abuse

LLM triggers unauthorized refund or update.

---

## Attack Paths

1. User injects malicious prompt
2. Model retrieves sensitive data
3. Model calls refund API
4. Unauthorized action executed

---

## Mitigation Strategy

* Input validation
* Retrieval filtering
* Tool authorization
* Output sanitization
