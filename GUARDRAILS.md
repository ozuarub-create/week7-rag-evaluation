# Guardrails and Failure Handling (Week 7)

This document describes the guardrails added to improve the reliability and trustworthiness of the RAG system.

## Input Validation
- Empty queries are rejected before retrieval.
- Queries consisting only of whitespace are rejected.
- Maximum query length should be enforced to prevent prompt abuse or excessive context usage.

## Source Enforcement
- Every generated answer must include at least one valid source citation.
- If no valid source is available, the system refuses to answer.
- Answers without sources are considered invalid and should be blocked.

## Fallback Behavior
- When retrieval returns no relevant documents, the system responds exactly with:
  "I cannot answer from the provided documents."

## Failure Logging
- Failed queries (empty input, no retrieval results, missing sources) should be logged.
- Logs should include:
  - Timestamp
  - User query
  - Failure reason (e.g., no documents retrieved)
- Logging enables later analysis of failure patterns and system weaknesses.

These guardrails ensure the system avoids hallucinations, fails safely, and remains trustworthy.
