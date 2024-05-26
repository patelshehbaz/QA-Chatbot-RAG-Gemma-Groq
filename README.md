# QA-Chatbot-RAG-Gemma-Groq

This project is designed to demonstrate a Retrieval-Augmented Generation (RAG) system that answers questions based on provided documents. The application uses advanced language models, vector embeddings, and document processing tools to provide accurate responses to user queries. The core functionality revolves around leveraging the Gemma model and integrating various libraries for efficient document retrieval and question answering.

## Tech Stack

- **Programming Language:** Python
- **Libraries:**
  - `faiss-cpu`: A library for efficient similarity search and clustering of dense vectors.
  - `groq`: A library for Groq chip integration.
  - `langchain-groq`: Integration of LangChain with Groq.
  - `PyPDF2`: A pure Python library for PDF file handling.
  - `langchain_google_genai`: LangChain integration with Google Generative AI.
  - `langchain`: A framework for developing applications with large language models.
  - `streamlit`: An app framework for Machine Learning and Data Science projects.
  - `langchain_community`: Community-driven extensions for LangChain.
  - `python-dotenv`: Reads key-value pairs from a `.env` file and can set them as environment variables.
  - `pypdf`: A library for PDF file handling.
  - `google-cloud-aiplatform` (>=1.38): A library for interacting with Google Cloud AI Platform.

## How to Run

### Prerequisites

Ensure you have Python installed on your system. It's recommended to use a virtual environment to manage your dependencies.

### Installation

1. Clone the repository:

   ```
   git clone https://github.com/patelshehbaz/QA-Chatbot-RAG-Gemma-Groq.git

   ```

2. Create a virtual environment:

   ```bash
   conda create -p venv python=3.12 -y
   ```

3. Activate the virtual environment:

   ```
   conda activate venv
   ```

4. Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```
