Resume RAG Chatbot

Overview:
A Retrieval-Augmented Generation (RAG) chatbot that answers questions about a resume PDF.

Tech Stack:
- Python
- LangChain
- ChromaDB
- Groq
- Jupyter Notebook

Pipeline:
1. Load Resume PDF
2. Parse Document
3. Split into Chunks
4. Generate Embeddings
5. Store in ChromaDB
6. Retrieve Relevant Chunks
7. Generate Answer using LLM

Sample Questions:
- What are the candidate's skills?
- What projects has the candidate worked on?
- What certifications does the candidate have?
