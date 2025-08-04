# RAG-Powered Research Paper Q&A Using Groq and Llama3

This project builds a Retrieval-Augmented Generation (RAG) system using Llama3-8B via Groq. It allows users to ask natural language questions about research papers in PDF format. The system uses LangChain, FAISS, and Ollama embeddings to provide relevant, context-aware answers based on uploaded documents.

## Features

- Ask questions about research papers (PDFs)
- Embeds documents using OllamaEmbeddings
- Powered by Llama3-8B-8192 via Groq’s LPU backend
- Uses FAISS for vector-based document retrieval
- Context-aware answers with LangChain's retrieval chain
- Simple user interface built with Streamlit

## Tech Stack

- LangChain
- FAISS (vector database)
- OllamaEmbeddings
- ChatGroq (Llama3-8B)
- Streamlit
- PyPDFDirectoryLoader

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/repo-name.git
   cd repo-name

2. Install dependencies:
   pip install -r requirements.txt

3. set up your environment variables:
   Create a .env file:
   echo "GROQ_API_KEY=your_api_key_here" > .env

4. Prepare your PDFs:
   Put all your research papers (PDFs) into a folder named research_papers.

5. Run the app:
   streamlit run abhi.py
