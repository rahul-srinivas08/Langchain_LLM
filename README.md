# Langchain_LLM, https://learn.deeplearning.ai/courses/langchain-chat-with-your-data/lesson/1/introduction https://learn.deeplearning.ai/courses/langchain-chat-with-your-data/lesson/3/document-splitting
# notebooks on using langchain :
- model, prompt template , formate prompt template passing variable wrt to template style and others  ,  output parser schema and structure the response or completion of llms using
- the memory of conversation buffer memory, window memory (how many exchanges to save), token max limit to save memory and summarization memory used to track history or save conversation exchange.
-  example code of using chain on llms, prompt together and simple sequential chains and sequential chain on passing input to chain 1 o/p  output key to input to next chain 2 and route chain having multiple prompts and ask chain to use prompt template depend on user input for completion.
-  different used cases use Q and A on documents on vector stores and embedding, query on retrieval, methods like stuff , map-reduce, map rerank on retrievalqa(llm, vectordb.as retrival) on query .
-  an example to do evaluation using QA evaluation llms  on chains created with retrieval docs.
-  Agents , simple lang chain agents using tools to create chain and llms to have  external knowledge, maths wiki, custom tool and add in your llm chain .
-  Langchain loader , with different sorces of data tob load like URL, pdf, notion db and youtube.
-  document text spliter with chunk size and overlap, on token, characters , header and other methods .
-  vectorstore and embeddings. after splitting the documents are converted into embedding built-in  and stored as vectorstoredb. have built-in an  option and cloud platform
-  retrieval query response more relevant methods, like compression method, llm aid retrieval , mmr max marginal relevance and non vectorbasestore like tf idf svm retriver
-  qanda using retrivaldb follow methods like map reduce, stuff ,refine , map rerank . cons is with no histroy of conversation.
