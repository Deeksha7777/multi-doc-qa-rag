# multi-doc-qa-rag

A Retrieval-Augmented Generation (RAG)-based Question Answering system that processes multiple PDF documents and provides accurate answers using NLP and vector similarity search.

## Features

- Upload and process multiple PDF documents  
- Uses RAG architecture for contextual and relevant responses  
- Performs vector search using FAISS or Chroma  
- Built using LangChain, Groq/OpenAI APIs, and Streamlit

## Tech Stack

Python  
LangChain  
FAISS / ChromaDB  
Groq API / OpenAI API / Hugging Face Transformers  
PyPDF2  
Streamlit

## How to Run

1. Clone the repository  
   `git clone https://github.com/your-username/your-repo-name.git`

2. Navigate to the project directory  
   `cd your-repo-name`

3. Create a virtual environment  
   `python -m venv venv`

4. Activate the virtual environment  
   On Windows: `venv\Scripts\activate`  
   On Mac/Linux: `source venv/bin/activate`

5. Install dependencies  
   `pip install -r requirements.txt`

6. Set your Groq API key  
   Open `config.json` and update it like this:  
   {
     "api_key": "your_groq_api_key"
   }

7. Run the application    
   `streamlit run app.py`
