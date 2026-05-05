# Example: Customer Support RAG Assistant

## System Purpose
A customer support assistant answers user questions by retrieving internal support documents and generating responses using an LLM.

## Data Flow

```text
Customer
  ↓
Web App
  ↓
Input Guard
  ↓
RAG Retriever
  ↓
Vector Database
  ↓
LLM Runtime
  ↓
Output Guard
  ↓
Customer Response
