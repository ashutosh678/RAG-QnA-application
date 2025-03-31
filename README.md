# RAG Application using Gemini Pro

A Retrieval Augmented Generation (RAG) application built with Streamlit and Google's Gemini Pro that allows users to ask questions about PDF documents and receive contextual answers.

## Features

- PDF document loading and processing
- Text chunking for better context retrieval
- Vector storage using ChromaDB
- Question answering using Google's Gemini Pro LLM
- Interactive chat interface using Streamlit

## Prerequisites

- Python 3.10 or higher
- Google AI API key
- Required Python packages (see Installation)

## Installation

1. Clone the repository:
```bash
git clone [<repository-url>](https://github.com/ashutosh678/RAG-QnA-application/tree/main)
cd RAG-QnA-application
```

2. Create and activate a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
```

3. Install the required packages:
```bash
pip install streamlit langchain-community langchain-google-genai chromadb python-dotenv
```

4. Create a `.env` file in the project root and add your Google AI API key:
