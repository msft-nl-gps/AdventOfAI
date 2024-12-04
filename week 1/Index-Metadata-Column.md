## Can you query a VectorDB with additional where-clauses?
Yes you can!! And tbh You SHOULD. 😎

In VectorDBs one can store additional metadata along with the vectors.
This metadata can be used to filter out the results of the query, thus increase performance, security and relevancy/similarity.

Example, storing page no., title, topic etc. along with the chunks of a document. Or, in case of implementing RBAC (Role Based Access Control), you can store the role/group info.

In #Langchain:
```python
vectorstore.similarity_search(
    "revenue details on Q1 2024",
    k=2,
    filter={"role": "hr"},
)
```
And in Azure AI Search: https://learn.microsoft.com/en-us/azure/search/vector-store

#AdventOfAI

(Throughout the month of december, we will post facts, usecases & solutions related to AI, you can find the book of records here: https://github.com/msft-nl-gps/AdventOfAI)