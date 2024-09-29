# RAG-based-chat-application

# Chat Application with Retrieval-Augmented Generation (RAG) using Pinecone and Gemini Model

## Overview

This chat application is built using Pinecone for vector storage and retrieval, and Google's Gemini model for generating conversational responses. The system implements Retrieval-Augmented Generation (RAG), which allows the model to reference relevant historical conversation context to generate accurate and context-aware responses.

The main components of the application are:
- **Pinecone**: Used to store and retrieve conversation history based on vector embeddings.
- **Gemini Model**: Used for both generating embeddings of conversation history and generating responses based on combined historical context and user queries.

## Features

- **Contextual Awareness**: Retrieves relevant historical context from conversation history to provide more accurate responses.
- **RAG Mechanism**: Utilizes the Retrieval-Augmented Generation mechanism to reference past conversations when responding to new user queries.
- **Embeddings**: Uses embeddings to represent conversation history in vector space and query them using cosine similarity for relevance.

## Setup

### Prerequisites

1. **Python 3.8+**
2. **Pinecone API Key**
3. **Google Gemini Model API Key**

### Install Required Libraries

First, install the required libraries by running:

```bash
pip install pinecone-client google-generativeai
