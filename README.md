## RAG on GCP — Experiment 🚀

**Concept:**  
Retrieve ➝ Augment ➝ Generate 🤖  

**Flow:**  
User Query → Embedding → Vector Search → Context Retrieval → LLM (Gemini) → Answer ✨  

**Core Steps:**  
- 📚 Chunk documents  
- 🧮 Create embeddings (Vertex AI)  
- 🔍 Store in Vector Search  
- ❓ Embed user query  
- 📥 Retrieve top-k relevant chunks  
- 🧠 Generate grounded response  
