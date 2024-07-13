# AWS-Case-Studies-and-Blogs-RAG-Application

This repository contains the code and resources for a Retrieval Augmented Generation (RAG) application using AWS Case Studies and Blogs dataset. The application leverages LangChain, FAISS vector store, Gemini large language model, and the all-distilroberta-v1 embedding model.

## Overview
This project aims to demonstrate the use of Retrieval Augmented Generation with Large Language Models (LLMs). The dataset comprises AWS case studies and blog articles, focusing primarily on Generative AI and LLMs. The application is built to fetch relevant information from the dataset and generate contextually appropriate responses.

## Dataset
The dataset used in this project is a collection of text files containing AWS case studies and blog articles. The primary characteristics of the dataset are:

- Content: 90% case studies and 10% blog articles.
- Source: HTML source of AWS Case Study webpage.
- Extraction: Relevant text extracted using BeautifulSoup Python library.
- Cleaning: HTML removed to keep only the text context related to the case study or blog article.

## Architecture
The application utilizes the following components:

- LangChain: A framework for building applications with LLMs.
- FAISS Vector Store: A library for efficient similarity search and clustering of dense vectors.
- Gemini Large Language Model: A powerful LLM for generating human-like text.
- all-distilroberta-v1 Embedding Model: A lightweight, fast, and efficient embedding model.

## Contribution
Contributions are welcome! Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements
[LangChain](https://www.langchain.com/)
[FAISS](https://faiss.ai/index.html)
[Hugging Face](https://huggingface.co/)
