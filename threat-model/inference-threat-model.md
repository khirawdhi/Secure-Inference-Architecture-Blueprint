# Threat Model: AI Inference System

## Assets

* User input
* Retrieved data (RAG context)
* Model prompts and outputs
* Tool execution capabilities
* Internal APIs and systems

## Adversaries

* Malicious users
* Prompt injection attackers
* Data poisoning actors
* Insider threats

## Key Threats

### 1. Prompt Injection

User manipulates model behavior via crafted input.

### 2. Retrieval Poisoning

Malicious data influences RAG results.

### 3. Tool Abuse

LLM triggers unauthorized or harmful actions.

### 4. Data Leakage

Sensitive information exposed in output.

## Security Objective

Prevent untrusted input from influencing:

* System behavior
* Data access
* External actions
