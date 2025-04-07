🤖 AI Chatbot with PDF-based RAG
This project is an AI-powered chatbot that uses Retrieval-Augmented Generation (RAG) to answer user queries based on the content of uploaded PDF files. It combines Document Intelligence with LLM-based natural language understanding to provide contextual, document-aware conversations.

🚀 Features
🔍 PDF Upload: Upload a PDF file as the knowledge base.
🧠 RAG Pipeline: Combines document retrieval with LLM response generation.
💬 Chat Interface: Interactive chat to ask questions based on the uploaded PDF.
⚡ Fast & Accurate: Retrieves the most relevant sections and generates coherent responses.
🧾 Chunking & Embeddings: Splits PDF into manageable chunks and converts them into vector embeddings for semantic search.

🛠️ Tech Stack
Frontend: Streamlit
Backend: Python, LangChain
Embedding Models: GoogleGenerativeAIEmbeddings 
Vector Store: FAISS 
PDF Parsing: PdfReader
LLM: Gemini AI

🧪 How It Works
PDF Upload: User uploads a PDF document.
Text Extraction: The PDF is parsed and converted into text.
Chunking: Text is split into overlapping chunks to preserve context.
Embeddings: Chunks are embedded using a transformer model.
Vector Search: On user query, relevant chunks are retrieved via semantic search.
LLM Response: Retrieved context and query are passed to an LLM to generate a natural response.


🖥️ Getting Started
1. Clone the Repo
git clone https://github.com/jaypatel14399/rag-pdf-chatbot.git
cd rag-pdf-chatbot
2. Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate
3. Install Dependencies
pip install -r requirements.txt
4. Run the Application
streamlit run app.py
