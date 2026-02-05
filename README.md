A Retrieval-Augmented Generation (RAG) based medical chatbot that answers user queries by retrieving relevant medical documents and generating accurate, context-aware responses using Large Language Models (LLMs).

medicalchatbot-RAG/
│
├── app.py                 # Flask application entry point
├── store_index.py         # Script to create vector embeddings
├── requirements.txt       # Project dependencies
├── Procfile               # Deployment configuration (for Heroku/Render)
├── setup.py               # Package setup
│
├── src/
│   ├── helper.py          # Utility functions (embedding download)
│   ├── main.py            # Core RAG implementation
│   ├── prompt.py          # Custom prompt templates
│   └── __init__.py
│
├── templates/
│   └── chat.html          # Front-end Chat UI
│
├── static/
│   └── style.css          # CSS Styling
│
└── data/                  # Folder containing your PDF data

    
<img width="1212" height="805" alt="Screenshot 2026-02-06 at 12 19 46 AM" src="https://github.com/user-attachments/assets/8facea22-2ae4-4d44-906c-9eb3e51cf40a" />
