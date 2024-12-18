## How do we assess if our retrieval system is picking the right information? 
 
Many LLM-based applications use RAG (Retrieval-Augmented Generation) to generate responses from private data. This implies the quality of the answer is highly dependent on the retrieval system - many companies are opting for vector databases, hybrid search, and re-rankers to enhance results.

To address retrieval quality, precision and recall metrics from #RAGAS are commonly used. These metrics assess how accurately the system retrieves relevant context based on the user’s input. However, they rely on the assumption that we already know which chunk of information is the “right” one for each question. In practice, the method we use to determine relevance can lead to variations in the final evaluation results.

So, how can we determine if a chunk is truly relevant? **See 4 possible methodologies in the file retrieval-evaluation.png**

How do you evaluate your retrieval systems? Do you have other methods or favourite approaches? 🤔
