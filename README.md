# Local RAG Agent with LLaMA3 Demo

This repository contains a demonstration of how to build a Local Retriever-Augmented Generation (RAG) agent using LLaMA3. This specific demo indexes a team page from the Transform UK website. It allows users to ask relevant questions to the LLM, receiving answers based on the indexed page's content.

## Features

- **Local Indexing:** Indexes content directly from the Transform UK team page.
- **Question Answering:** Utilizes LLaMA3 to answer queries based on the indexed content.
- **Web Search Integration:** If the query cannot be answered using the indexed page, the agent fetches results from a web search to provide the necessary information.

## How It Works

1. **Indexing**: The demo first indexes the specified team page from Transform UK, creating a searchable database of its content.
2. **Query Processing**: Users can then input questions related to the content of the indexed page.
3. **Answer Retrieval**: The LLaMA3 model processes these questions and retrieves answers based on the local index.
4. **Fallback to Web Search**: If the model determines that the answer is not contained within the indexed content, it automatically extends the search to the web, ensuring comprehensive responses.


## Reference

The original code for a similar implementation can be found [here](https://github.com/langchain-ai/langgraph/blob/main/examples/rag/langgraph_rag_agent_llama3_local.ipynb).

## Additional Resources

- **TransformDemo.ipynb**: A Jupyter notebook file, `TransformDemo.ipynb`, will be provided in this repository to demonstrate the usage of the Local RAG agent specifically tailored to the Transform UK website.
