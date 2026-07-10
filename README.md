#AI Document Chatbot

A modular, document-aware AI chatbot designed to ingest custom data and provide contextually accurate answers. Built with Python, this project uses a Retrieval-Augmented Generation (RAG) pipeline, allowing you to easily process your own documents and chat with them in real-time.

#Features

Custom Knowledge Base: Drop your reference files into the docs/ folder and chat directly with your data.

Automated Data Ingestion: A dedicated pipeline (ingest.py) to chunk, embed, and store your documents efficiently.

Blazing Fast Setup: Powered by uv for lightning-fast Python dependency management and reproducible builds.

Highly Configurable: Easily tweak model parameters, vector database settings, and prompts via config.py.

Experimental Sandbox: Includes a colab notebook/ directory for prototyping, testing embeddings, and model experimentation.

#Tech Stack

Language: Python
Dependency Management: uv
Architecture: Retrieval-Augmented Generation (RAG)
