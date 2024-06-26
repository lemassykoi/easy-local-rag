# SuperEasy 100% Local RAG with Ollama + Email RAG

### Setup
1. Install Ollama : https://ollama.com/download // This can be done on another computer
2. ```ollama pull llama3``` (or any model you want to chat with)
3. ```ollama pull mxbai-embed-large``` (model needed for embedding)
4. ```git clone```
5. ```cd dir```
6. ```pip install -r requirements.txt```
7. run ```upload.py``` (.pdf, .txt, or JSON) to upload some documents to local RAG
8. run ```localrag.py``` (with query re-write)
9. run ```localrag_no_rewrite.py``` (no query re-write)

### His YouTube Channel
forked from https://www.youtube.com/c/AllAboutAI

### What is RAG?
RAG is a way to enhance the capabilities of LLMs by combining their powerful language understanding with targeted retrieval of relevant information from external sources often with using embeddings in vector databases, leading to more accurate, trustworthy, and versatile AI-powered applications

### What is Ollama?
Ollama is an open-source platform that simplifies the process of running powerful LLMs locally on your own machine, giving users more control and flexibility in their AI projects. https://www.ollama.com
