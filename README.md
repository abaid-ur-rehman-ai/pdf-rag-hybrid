# PDF RAG with Hybrid Search + Re-ranking

RAG system on documents with:
- Semantic search (Chroma + Gemini embeddings)
- Keyword search (BM25)
- Hybrid retrieval (Ensemble)
- Cross-encoder re-ranking
- Grounded answers with page citations

## Features
- Hybrid retrieval (BM25 + vector)
- Re-ranking with CrossEncoder
- Page-cited answers
- Works on PDF documents

## Tech Stack
- LangChain
- ChromaDB
- Gemini embeddings + LLM
- BM25
- sentence-transformers (CrossEncoder)

## How to Run
1. Add `GOOGLE_API_KEY`
2. Upload a PDF
3. Run the notebook cells in order
4. Ask questions in the chat loop

## Example
Q: What is the purpose of this roadmap?  
A: (answer with page citation)
