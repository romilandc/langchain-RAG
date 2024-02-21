# Langchain RAG Application
A RAG implementation on Langchain using Chroma as storage.  Take some pdfs (you can either use the test pdfs include in /data or delete and use your own docs), index/embed them in a vdb, use LLM to inference and generate output.

## How to use
- create local path and data subfolder 
- create virtual env using conda or however you choose
- install requirements.txt
- activate Ollama in terminal with "ollama run mistral" or whatever model you pick.  If you're using the new Ollama for Windows then not necessary since it runs in the background (ensure it's active).
- open langchain_RAG.py
- update line 15 and 16 with your local paths #for pdfs and where chroma database will store chunks
- update line 50 with your model of choice
- save and run the script
- observe results similar to:

![Image1](https://github.com/romilan24/langchain-RAG/blob/main/langchain_RAG.JPG)
