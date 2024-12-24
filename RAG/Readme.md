# Healthcare RAG Chatbot

## Overview:
The Healthcare RAG Chatbot is a Retrieval-Augmented Generation (RAG) chatbot designed to assist users with healthcare-related queries. It leverages a combination of a large language model (LLM) and a document retriever to provide accurate answers using healthcare-specific documents.

## Features:
Healthcare Document Integration: Processes PDFs containing healthcare guidelines, drug manuals, and other medical resources.
Conversational Memory: Maintains conversation context to answer follow-up questions effectively.
Gradio UI: Provides an easy-to-use web interface for interacting with the chatbot.
Custom Prompting: Tailored to provide accurate healthcare information.

## Tech Stack:
Python
LangChain for document loading, text splitting, embeddings, and chain management.
FAISS for vector database and document retrieval.
Gradio for the user interface.
Groq for the LLM API.

## Prerequisites:
Ensure the following dependencies are installed:
Python 3.8+
Google Colab or a local Python environment with access to the internet.

## Document Preparation:
To provide accurate answers, upload relevant healthcare documents in PDF format. 
For this code, Healthcare1.pdf document available in this folder is to be downloaded and uploaded in Google Collab before running the code.
Place this file in a folder named Project/.

## Disclaimer:
This chatbot is designed to provide general healthcare information. It does not replace professional medical advice. Always consult a qualified healthcare professional for specific medical concerns.

## License:
This project is licensed under the MIT License. See the LICENSE file for details.
