# 📚 Mini RAG Studio

Mini RAG Studio is a lightweight Retrieval-Augmented Generation (RAG) application that enables users to upload PDF documents and ask context-aware questions using Google's Gemini Large Language Model (LLM). The project combines document retrieval with generative AI to provide accurate answers based on the uploaded content.

---

## 🚀 Features

- 📄 Upload PDF documents
- ✂️ Automatic document loading and text splitting
- 🧠 Generate embeddings using HuggingFace models
- 🔍 Fast semantic search with FAISS
- 🤖 AI-powered responses using Google Gemini
- 💬 Interactive Streamlit web interface
- ⚡ Lightweight and modular RAG architecture

---

## 🛠️ Technologies Used

- Python
- Streamlit
- LangChain
- Google Gemini API
- HuggingFace Embeddings
- FAISS Vector Database
- PyPDF
- Python Dotenv

---

## 📂 Project Structure

```
Mini_RAG_Studio/
│
├── app.py
├── loader.py
├── splitter.py
├── embeddings.py
├── vectorstore.py
├── rag_chain.py
├── requirements.txt
├── .gitignore
├── data/
├── database/
├── utils/
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/MehakSharma030/C-DAC-Training.git
```

### 2. Navigate to the Project

```bash
cd C-DAC-Training/Mini_RAG_Studio
```

### 3. Create a Virtual Environment

```bash
python -m venv .venv
```

### 4. Activate the Virtual Environment

#### Windows

```bash
.venv\Scripts\activate
```

#### Linux / macOS

```bash
source .venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file inside the project directory.

```env
GOOGLE_API_KEY=YOUR_GOOGLE_GEMINI_API_KEY
```

> **Note:** Do not upload your `.env` file to GitHub.

---

## ▶️ Running the Application

```bash
streamlit run app.py
```

The application will launch in your default web browser.

---

## 🔄 Workflow

1. Upload a PDF document.
2. The document is loaded and split into chunks.
3. HuggingFace generates embeddings.
4. FAISS stores the embeddings.
5. User enters a query.
6. Relevant chunks are retrieved.
7. Google Gemini generates a context-aware answer.

---

## 📦 Major Dependencies

- streamlit
- langchain
- langchain-community
- langchain-google-genai
- langchain-huggingface
- faiss-cpu
- pypdf
- sentence-transformers
- python-dotenv

---

## 🎯 Future Enhancements

- Support for multiple PDF uploads
- Chat history
- ChromaDB integration
- Multiple LLM support (Gemini, Ollama, OpenAI)
- Citation-aware responses
- Deployment on Streamlit Cloud

---

## 👩‍💻 Author

**Mehak Sharma**

Developed during the **C-DAC Training Program**.

---

## 📜 License

This project is intended for educational and learning purposes.
