# Document-Based RAG Chatbot – PDF and TXT Question Answering System

## About the Project
This project is a document-based Retrieval-Augmented Generation (RAG) chatbot that allows users to upload PDF and TXT documents and ask questions based on their content.

It uses Google Gemini to generate answers from the information retrieved from uploaded documents.

## Features
- Upload PDF and TXT documents
- Extract and split document text into chunks
- Generate embeddings using Google Gemini
- Store document embeddings in ChromaDB
- Retrieve relevant information using semantic search
- Generate context-based answers using Gemini
- Interactive question-answering system

## Technologies Used
- Python
- Google Gemini API
- LangChain
- ChromaDB
- Google Colab

## Project Architecture

1. Upload PDF or TXT document
2. Extract text from the document
3. Split text into smaller chunks
4. Generate embeddings
5. Store embeddings in ChromaDB
6. Retrieve relevant chunks for the question
7. Pass retrieved context to Gemini
8. Generate the final answer

## How to Run

1. Open `Document-Based RAG Chatbot – PDF and TXT Question Answering System` in Google Colab.
2. Install the required libraries.
3. Enter your Google Gemini API key when prompted.
4. Run the notebook cells.
5. Upload a PDF or TXT document.
6. Ask questions about the uploaded document.

## Learning Outcomes
- Understanding Retrieval-Augmented Generation (RAG)
- Working with document loaders and text splitters
- Understanding embeddings and vector databases
- Implementing semantic search
- Integrating an LLM with retrieved document context

## Author
Shikha Gour

B.Tech – Artificial Intelligence and Data Science
