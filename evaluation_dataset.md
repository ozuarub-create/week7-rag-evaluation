# RAG Evaluation Dataset

## Instructions
Each question below is designed to test whether the RAG system retrieves the correct source
and produces a grounded, faithful answer.

---

## Question 1
**Question:**  
What does the RAG system do when no relevant information is found in the knowledge base?

**Expected Source:**  
Not documented

---

## Question 2
**Question:**  
What type of retrieval method does the RAG system use?

**Expected Source:**  
BASELINE.md — Retrieval section

---

## Question 3
**Question:**  
What type of documents are used as the knowledge base?

**Expected Source:**  
BASELINE.md — Knowledge Base section

---

## Question 4
**Question:**  
Where are the knowledge base documents stored?

**Expected Source:**  
BASELINE.md — Knowledge Base section

---

## Question 5
**Question:**  
Does the system use a system prompt to control generation?

**Expected Source:**  
BASELINE.md — Generation section

---

## Question 6
**Question:**  
Can the system hallucinate when retrieved context is weak?

**Expected Source:**  
BASELINE.md — Known Issues section

---

## Question 7
**Question:**  
What happens if the user submits an empty query?

**Expected Source:**  
Not documented

---

## Question 8
**Question:**  
What specific logging is performed when a query fails?

**Expected Source:**  
Not documented

---

## Question 9
**Question:**  
Does the system block responses that lack valid sources?

**Expected Source:**  
Not documented

---

## Question 10
**Question:**  
What is the maximum allowed length of a user query?

**Expected Source:**  
Not documented

---

## Question 11
**Question:**  
What happens when the retrieval step returns irrelevant documents?

**Expected Source:**  
Not documented

---

## Question 12
**Question:**  
Does the system return a refusal when it cannot find supporting evidence?

**Expected Source:**  
Not documented
