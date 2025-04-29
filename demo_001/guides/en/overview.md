# Build a Minimal Vector Search App

## Overview

AI is currently a cutting-edge field, attracting many developers eager to learn about it. However, several obstacles often hinder their learning process, such as:

- A lack of foundational AI knowledge;
- Overly complex underlying infrastructures;
- The absence of comprehensive, step-by-step documentation for AI applications.

To address these issues, we have developed this lab, through which you will learn:

- How to use **TiDB Serverless** as a data storage layer for AI applications to accelerate your AI development process.
- What Embedding is and its capabilities.
- How to utilize Embedding vectors after they have been obtained.
- How to employ RAG / GraphRAG for data retrieval when dealing with large volumes of data.
- How to use **DSPy** to extract text into graphs, store these graphs in TiDB Serverless, and subsequently use graph retrieval to enhance RAG capabilities.

### Tasks

- **Text Similarity Search**

  - Use OpenAI Embedding model and API for text embedding.
  - Store Embedding vectors and the original text in TiDB Serverless.
  - Utilize SQL of TiDB to perform vector similarity searches and retrieve text data most relevant to user queries.

- **Image Search**

  - Use the CLIP pre-trained model for feature extraction on images to obtain Embeddings.
  - Store Embedding vectors and original image IDs in TiDB Serverless.
  - Utilize SQL of TiDB to perform vector similarity searches and retrieve images that are most similar in features to the given image.

- **GraphRAG Retrieval**

  - Conduct searches on graphs preconstructed in TiDB Serverless.
  - Retrieve text data most relevant to user queries using the graph.

- **Build to Read: A Complete GraphRAG Tutorial**

  - Use DSPy to extract entities and relationships from text into a graph.
  - Perform Embedding vectorization on entities.
  - Store entities and relationships in TiDB Serverless.
  - Query the graph within TiDB Serverless to boost RAG performance.

### Duration

- This lab should take you approximately 1.5 hour to complete.