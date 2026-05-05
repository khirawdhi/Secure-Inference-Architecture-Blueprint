# Output Guard Controls

## Objective

Prevent sensitive or harmful information from reaching users.

---

## Key Risks

* Data leakage
* Toxic or unsafe content
* Policy violations

---

## Controls

### 1. Output Filtering

* Apply regex + classifier-based filters
* Remove sensitive data patterns

---

### 2. Content Moderation

* Use moderation APIs or classifiers
* Block unsafe responses

---

### 3. Response Validation

* Ensure output aligns with allowed formats
* Reject unexpected outputs

---

### 4. Redaction

* Mask sensitive fields (PII, credentials)

---

## Design Principle

> Never expose raw model output directly to users.
