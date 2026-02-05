A Retrieval-Augmented Generation (RAG) based medical chatbot that answers user queries by retrieving relevant medical documents and generating accurate, context-aware responses using Large Language Models (LLMs).

medicalchatbot-RAG/
│
├── app.py                 # Flask application entry point for the web server
├── store_index.py         # Script to process PDFs and create vector embeddings in Pinecone
├── requirements.txt       # List of Python dependencies
├── Procfile               # Heroku/Render deployment configuration (runs Gunicorn)
├── setup.py               # Package installation configuration
├── .env                   # Environment variables (API keys) - Not shared
├── template.sh            # Shell script template (utility)
│
├── src/
│   ├── __init__.py        # Makes src a Python package
│   ├── helper.py          # Helper functions (e.g., loading embedding models)
│   ├── main.py            # Main application logic
│   └── prompt.py          # System prompts for the LLM
│
├── templates/
│   └── chat.html          # Front-end HTML interface for the chatbot
│
├── static/
│   └── style.css          # CSS styles for the chat interface
│
├── google-cloud-sdk/      # Google Cloud SDK tools (if applicable)
├── research/
│   └── trials.ipynb       # Jupyter notebook for experiments and testing
│
└── data/
    └── Medical_book.pdf   # Source medical data for the RAG knowledge base

    
<img width="1212" height="805" alt="Screenshot 2026-02-06 at 12 19 46 AM" src="https://github.com/user-attachments/assets/8facea22-2ae4-4d44-906c-9eb3e51cf40a" />
