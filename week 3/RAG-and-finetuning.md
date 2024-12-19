## RAG and fine-tuning rather than RAG VS fine-tuning

Who is going to get a better grade?
1. A student who is well prepared for a closed-book exam (Fine-tuning)
2. A student who did not prepare much for a open-book exam (RAG)
3. A student who is well prepared for a open-book exam (RAFT)
 
Building LLM apps on company data often involves choosing between Retrieval-Augmented Generation (RAG) and Fine-Tuning. In practice, one does not exclude the other (especially with fine-tuning getting easier and cheaper).
 
The paper "RAFT: Adapting Language Model to Domain Specific RAG" investigates the combination of RAG and fine-tuning in one single approach that leverages the best of both worlds. This approach can be useful for when your retrieval system fails to provide the right context to the LLM, but since the LLM learned the right answer during training, it is not misled by the wrong piece of information. 
 
Ever tried combining RAG and fine-tuning?
 
Read the paper: https://lnkd.in/dxwxcDyS . This post is part of the hashtag#AdventofAI initiative by my team. See previous posts from Emile Verbunt and Soham Dasgupta here: https://lnkd.in/dbrRVCgz
