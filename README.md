# Amazon Reviews Chatbot (RAG)

## Overview

This project builds a Retrieval-Augmented Generation (RAG) chatbot using Amazon product reviews as knowledge base. It uses LangChain with Groq LLM, Sentence Transformers for embeddings, and FAISS for vector search.

## Setup

1. Install dependencies: `pip install -r requirements.txt`
2. Place the dataset CSV in `data/`
3. Set your Groq API key in a `.env` file or enter it in the Streamlit app.
4. Run the Streamlit app: `streamlit run src/chatbot_app.py`

## Project Structure

- `src/`: Source Python modules
- `data/`: Dataset CSV
- `.gitignore`: To ignore `.env` and cache files
- `requirements.txt`: Python dependencies
- `chatbot_responses.txt`: Sample QA outputs

## License & Citation

...
