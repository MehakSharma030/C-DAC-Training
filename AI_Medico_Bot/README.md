# 🩺 AI Medico Bot

AI Medico Bot is an AI-powered medical report analysis application that enables users to upload medical reports in PDF format and ask context-aware questions using Retrieval-Augmented Generation (RAG). The application leverages Google's Gemini Large Language Model (LLM), LangChain, and FAISS to provide accurate and relevant responses based on the uploaded document.

---

## 🚀 Features

- 📄 Upload medical reports in PDF format
- 🤖 AI-powered medical question answering
- 🔍 Retrieval-Augmented Generation (RAG)
- 🧠 Semantic search using FAISS Vector Database
- 📚 HuggingFace Embeddings for document representation
- 💬 Interactive Streamlit web interface
- ⚡ Fast and context-aware responses

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

```text
AI_Medico_Bot/
│
├── app.py
├── loader.py
├── splitter.py
├── embeddings.py
├── vectorstore.py
├── llm.py
├── prompts.py
├── rag_chain.py
├── requirements.txt
├── .gitignore
├── data/
├── database/
├── assets/
├── .streamlit/
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
cd C-DAC-Training/AI_Medico_Bot
```

### 3. Create a Virtual Environment

```bash
python -m venv .venv
```

### 4. Activate the Virtual Environment

**Windows**

```bash
.venv\Scripts\activate
```

**Linux/macOS**

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

The application will open in your default web browser.

---

## 🔄 Workflow

1. Upload a medical report (PDF).
2. The document is loaded and split into smaller chunks.
3. HuggingFace generates embeddings for each chunk.
4. Embeddings are stored in a FAISS vector database.
5. The user asks a question related to the report.
6. Relevant document chunks are retrieved.
7. Google Gemini generates an answer using the retrieved context.

---

## 📦 Major Dependencies

- streamlit
- langchain
- langchain-community
- langchain-google-genai
- langchain-huggingface
- faiss-cpu
- sentence-transformers
- pypdf
- python-dotenv
- numpy
- pandas

---

## 🎯 Future Enhancements

- Support for multiple medical reports
- Chat history and conversation memory
- Medical image analysis
- Patient authentication and profile management
- Citation-aware responses
- Cloud deployment using Streamlit Cloud

---

## 👩‍💻 Author

**Mehak Sharma**

Developed as part of the **C-DAC Training Program**.

---

## 📜 License

This project is intended for educational and learning purposes.
