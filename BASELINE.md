# RAG System Baseline (Week 7)

## 1. Current Capabilities
- The system accepts a user question and returns a generated answer using retrieved documents.
- The system can sometimes answer incorrectly or incompletely.

## 2. Knowledge Base
- The knowledge base consists of text documents used for retrieval.
- Documents are stored in a local folder in the project.

## 3. Retrieval
- The system uses vector-based retrieval with embeddings.
- A basic similarity search is used to retrieve relevant document chunks.

## 4. Generation
- The system uses a large language model (LLM) to generate answers.
- A basic system prompt is used, but it does not strictly prevent hallucinations.

## 5. Known Issues (if any)
- The system may hallucinate when retrieved context is weak or missing.
- The system may return answers without strong grounding.
- The system does not clearly refuse when no relevant information is found.
