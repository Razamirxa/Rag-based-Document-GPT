# Rag-based-Document-GPT


DocumentGPT is a Streamlit application that allows users to upload files (PDF, DOCX, CSV) and ask questions about their contents using a conversational retrieval model. The app leverages LangChain, Hugging Face, and Google Generative AI for document processing and natural language understanding.

## Features

- Upload and process multiple file types (PDF, DOCX, CSV)
- Extract text from uploaded documents
- Split text into manageable chunks
- Generate embeddings using Hugging Face
- Create a vector store for efficient document retrieval
- Use a conversational retrieval model to answer questions based on document content

## Installation

### Prerequisites

- Python 3.8 or higher
- Streamlit
- Required Python packages (listed in `requirements.txt`)

### Clone the Repository


conda create -n env_name python=3.11
conda activate env

## Install Dependencies
pip install -r requirements.txt

### .streamlit/secrets.toml
google_api_key = "YOUR_GOOGLE_API_KEY"

### RUN
streamlit run app.py


