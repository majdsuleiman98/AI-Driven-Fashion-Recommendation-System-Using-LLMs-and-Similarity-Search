# AI-Driven Fashion Recommendation System Using Large Language Models and Similarity Search

This project is an AI-driven fashion product recommendation system that leverages large language models (LLMs) and similarity search techniques to provide tailored product suggestions. It uses a fashion dataset to retrieve product descriptions, indexes them using FAISS for efficient retrieval, and uses the **google/flan-t5-large** LLM to generate the most relevant product recommendations based on user queries.

## Project Overview

The goal of this project is to create a personalized fashion product recommender system. The system works by:
1. Using a fashion dataset to obtain detailed product descriptions.
2. Generating product descriptions to enhance the available information.
3. Indexing the product descriptions using **FAISS** (Facebook AI Similarity Search) for fast and efficient similarity search.
4. Retrieving the most relevant products based on a user's query using FAISS similarity search.
5. Using the **google/flan-t5-large** LLM to recommend the most suitable products from the retrieved results.

## Features

- **Product Description Indexing**: FAISS is used to index product descriptions for fast retrieval based on user queries.
- **Relevance-Based Recommendations**: The system ranks products by relevance using both semantic search and LLM-based recommendations.
- **Fashion-Specific Dataset**: The system uses a dataset of fashion products, ensuring the recommendations are tailored for clothing and apparel.
- **AI-Driven Matching**: The **google/flan-t5-large** LLM is fine-tuned to process user queries and return the most relevant product recommendations.

## Technologies Used

- **Python**: Programming language used to develop the entire system.
- **FAISS**: A library for efficient similarity search, used to index and retrieve product descriptions based on similarity to the user query.
- **Google FLAN-T5-Large**: A pre-trained large language model used to generate product recommendations based on the query and retrieved products.
- **Transformers**: A library from HuggingFace for integrating pre-trained models and pipelines like **google/flan-t5-large**.
- **LangChain**: A framework for working with language models, used to integrate **FLAN-T5** with the recommendation logic.
