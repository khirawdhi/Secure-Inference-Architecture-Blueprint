# RAG Retrieval Controls

## Goal
Prevent unsafe or unauthorized data from entering model context.

## Controls
- Restrict retrieval scope by user authorization
- Validate document sources before indexing
- Filter sensitive data from retrieved context
- Detect poisoned or untrusted documents
- Log retrieved documents used for each response

## Review Questions
- Can users retrieve data they should not access?
- Are retrieved documents traceable?
- Can poisoned content influence responses?
