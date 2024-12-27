# RAG-based QA with LangChain and Google Generative AI

This repository contains a Jupyter notebook for performing Retrieval-Augmented Generation (RAG) based Question Answering (QA) using LangChain and Google Generative AI. The notebook demonstrates how to load documents, split them into chunks, generate embeddings, and perform similarity search to generate responses to queries.

## Contents

- `RAG_QA.ipynb`: The main Jupyter notebook containing the code for the RAG-based QA.
- `dataset/`: A directory containing the sample documents used in the notebook.

## Requirements

To run the notebook, you need to install the following libraries:

- `langchain_community`
- `langchain_openai`
- `unstructured`
- `chromadb`
- `sentence-transformers`
- `langchain_google_genai`
- `nltk`

## Usage
- Install Required Libraries: Install the necessary libraries using pip.
- Import Required Libraries: Import the necessary libraries, including LangChain, NLTK, and Google Generative AI.
- Load Documents: Load documents from a specified directory using DirectoryLoader.
- Split Documents into Chunks: Split the loaded documents into smaller chunks using RecursiveCharacterTextSplitter.
- Generate Embeddings: Generate embeddings for the document chunks using HuggingFaceEmbeddings.
- Save Chunks to Chroma: Save the document chunks and their embeddings to a Chroma vector store.
- Create Prompt Template: Create a prompt template for the QA task.
- Perform Similarity Search: Perform a similarity search on the document chunks using the query text.
- Generate Response using Google Generative AI: Generate a response to the query using Google Generative AI.
- Format and Display Response: Format and display the generated response along with the sources.

## Dataset
The dataset/ directory contains sample documents used in the notebook. You can replace these with your own documents for custom QA tasks.
