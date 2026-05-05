# Customer Support RAG Assistant — Architecture

## Overview

AI assistant that:

* Answers customer queries
* Retrieves internal knowledge base
* Executes actions (refunds, updates)

---

## Pipeline

```text
User → Input Guard → RAG → LLM → Tool Execution → Output Guard → Response
```

---

## Trust Boundaries

* User → System
* Retrieval → Model
* Model → Tools
* System → User

---

## Key Design Decisions

* Separate retrieval from reasoning
* Enforce strict tool execution controls
* Apply output filtering before response
