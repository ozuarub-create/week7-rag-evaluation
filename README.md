# Week 7 – RAG System Evaluation & Reliability

This repository contains the Week 7 work focused on improving the **quality, reliability, and trustworthiness** of a Retrieval-Augmented Generation (RAG) system.  
The emphasis this week is on **evaluation, hallucination control, and guardrails**, not on adding new features.

---

## Week 7 Goals

- Evaluate the RAG system’s **accuracy and faithfulness**
- Reduce **hallucinations and unsupported answers**
- Add **basic guardrails and failure handling**
- Ensure the system **fails safely** when information is missing

---

## Repository Contents

| File | Description |
|------|-------------|
| `BASELINE.md` | System baseline: capabilities, knowledge base, retrieval, generation, and known issues |
| `evaluation_dataset.md` | 30 evaluation questions with expected sources |
| `evaluation_results.md` | System answers, retrieved sources, and refusal cases |
| `evaluation_report.md` | Summary of evaluation results and issues found |
| `SYSTEM_PROMPT.md` | Prompt enforcing strict grounding and refusal behavior |
| `GUARDRAILS.md` | Documented input validation, source enforcement, and logging |

---

## Evaluation Dataset

- **30 realistic questions** based on the current knowledge base
- Each question includes an **expected source** or is marked **Not documented**
- Covers:
  - Knowledge coverage
  - Retrieval behavior
  - Hallucination risk
  - Guardrails and refusal behavior

See: `evaluation_dataset.md`

---

## System Evaluation

- All questions were run through the RAG pipeline
- Answers were checked for:
  - Correctness
  - Grounding in retrieved content
  - Valid source citations
- Failure cases were identified and documented:
  - Missing documentation
  - No relevant retrieval results
  - Safe refusal scenarios

See: `evaluation_results.md`

---

## Hallucination Control

The system prompt enforces strict grounding rules:

- Answers must use **only retrieved context**
- If no relevant information is found, the system responds exactly with:

