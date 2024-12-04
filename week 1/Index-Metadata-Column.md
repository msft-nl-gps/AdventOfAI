## Can you query a Vector DB with additional where-clauses?
Yes you can!! And tbh You should.

In Vector DBs one can store additional metadata along with the vectors. 
This metadata can be used to filter out the results of the query.

For example, storing page no., title, topic etc. along with the chunks of a document.
Or, in case of implementing RBAC (Role Based Access Control), you can store the role/group info.

In Langchain:
```python
vectorstore.similarity_search(
    "revenue details on Q1 2024",
    k=2,
    filter={"role": "hr"},
)
```