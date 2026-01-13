--- paste below into evaluation_dataset.md ---
# RAG Evaluation Dataset (Week 7) — 30 questions

Each question below lists the expected source document (if known). Mark "Not documented" where the KB does not contain the info.

1. Q: What type of documents are used as the knowledge base?  
   Expected Source: BASELINE.md

2. Q: Where are the knowledge base documents stored?  
   Expected Source: Not documented

3. Q: Does the system return a refusal when no supporting evidence is found?  
   Expected Source: evaluation_results.md

4. Q: How does the system handle queries with empty input?  
   Expected Source: Not documented

5. Q: What retrieval method does the system use?  
   Expected Source: BASELINE.md

6. Q: How does the system log failed retrievals?  
   Expected Source: Not documented

7. Q: Does the system block answers that lack sources?  
   Expected Source: Not documented

8. Q: What specific logging is performed when a query fails?  
   Expected Source: Not documented

9. Q: Does the system add a source citation for every answer?  
   Expected Source: evaluation_results.md

10. Q: What is the expected failure message when there is no evidence?  
    Expected Source: evaluation_results.md

11. Q: How does the system limit answer length for long retrievals?  
    Expected Source: Not documented

12. Q: Is input query length validated (max tokens/characters)?  
    Expected Source: Not documented

13. Q: What happens if retrieval returns irrelevant documents?  
    Expected Source: evaluation_dataset.md

14. Q: Which documents were cited for Question 3 in the evaluation run?  
    Expected Source: evaluation_results.md

15. Q: Are there examples in the dataset where the system refused correctly?  
    Expected Source: evaluation_results.md

16. Q: Is there an explicit system prompt in the project?  
    Expected Source: BASELINE.md

17. Q: What are the known issues listed for the system baseline?  
    Expected Source: BASELINE.md

18. Q: How are document chunks created (size / overlap)?  
    Expected Source: Not documented

19. Q: Is there a fallback answer template described?  
    Expected Source: evaluation_report.md

20. Q: Does the evaluation dataset cover retrieval errors?  
    Expected Source: evaluation_dataset.md

21. Q: What behavior is expected if multiple documents disagree?  
    Expected Source: Not documented

22. Q: Are there examples of hallucinated answers in the results?  
    Expected Source: evaluation_results.md

23. Q: Is there a designated log file location described?  
    Expected Source: Not documented

24. Q: What was the system's result for the question "What type of documents are used..."?  
    Expected Source: evaluation_results.md

25. Q: Are there tests for empty or whitespace-only queries?  
    Expected Source: Not documented

26. Q: Does the evaluation include questions about retrieval latency?  
    Expected Source: Not documented

27. Q: Were any guardrails added to the system this week (documented)?  
    Expected Source: evaluation_report.md

28. Q: What format should source citations use in answers?  
    Expected Source: Not documented

29. Q: Does the system require answers to include the file name as source?  
    Expected Source: evaluation_results.md

30. Q: If no document matches, what string should the system return?  
    Expected Source: evaluation_results.md

--- end file ---
