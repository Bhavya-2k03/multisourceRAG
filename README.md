# multisourceRAG
A LangChain-powered multi-source Retrieval-Augmented Generation (RAG) system that can answer queries using:  
1. Wikipedia -> for general knowledge  
2. arXiv –> for research papers  
3. LangSmith documentation (via FAISS retriever) –> for project-specific knowledge   
Built with Ollama & Gemma3    

## ⚙️ Installation
1. **Clone the repository**
```bash
git clone https://github.com/yourusername/multisourceRAG.git
cd multisourceRAG
```
2. **Install Dependencies**
```bash
pip install -r requirements.txt
```
3. Install Ollama from https://ollama.ai/download
4. Pull the Gemma3 model
```bash
ollama pull gemma3:4b
```
5. You are ready to go :)
