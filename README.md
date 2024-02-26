# Overeview

![image](https://github.com/matrix215/Retrieval-augmented-generation-Evalution/assets/101815603/099f0cf7-44bc-4729-96bf-433af06bbb13)

LlamaIndex (GPT Index) offers an interface to connect your Large Language Models (LLMs) with external data. LlamaIndex provides various data structures to index your data, such as the list index, vector index, keyword index, and tree index. It offers both a high-level API and low-level API — the high-level API allows you to build a Question-Answering (QA) system in just five lines of code, whereas the lower-level API allows you to customize various aspects of retrieval and synthesis.

However, taking these systems into production requires careful evaluation of the performance of the overall system — the quality of the outputs given the inputs. Evaluation of retrieval-augmented generation can be challenging because the user would need to come up with a dataset of relevant questions for a given context. To overcome these obstacles, LlamaIndex provides Question Generation and label-free Evaluation modules.

1. Question Generation from the document
2. Generate answers/source nodes for questions using LlamaIndex QueryEngine abstractions, which manage the interaction between the LLM and data indices.
3. Evaluate if the question (query), answer, and source nodes are matching/inline


# Reference
- https://blog.llamaindex.ai/building-and-evaluating-a-qa-system-with-llamaindex-3f02e9d87ce1
- https://betterprogramming.pub/llamaindex-how-to-evaluate-your-rag-retrieval-augmented-generation-applications-2c83490f489
- https://www.usefulparadigm.com/2023/09/05/llamaindex%F0%9F%A6%99%EC%99%80-rag%EC%9D%98-%EA%B8%B0%EB%B3%B8-%EA%B0%9C%EB%85%90/
