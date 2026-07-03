# 🩺 AI Medico Bot

An AI-powered medical assistant that enables users to upload medical reports in PDF format and ask questions about their health reports using Retrieval-Augmented Generation (RAG). The application leverages Google's Gemini LLM, LangChain, and FAISS to provide context-aware responses.

---

## 📌 Features

- 📄 Upload medical reports in PDF format
- ✂️ Automatic document splitting and preprocessing
- 🔍 Semantic search using FAISS vector database
- 🤖 AI-powered question answering using Google Gemini
- 💬 Interactive Streamlit user interface
- ⚡ Fast retrieval with Retrieval-Augmented Generation (RAG)

---

## 🛠️ Tech Stack

- Python
- Streamlit
- LangChain
- Google Gemini API
- FAISS
- PyPDF
- HuggingFace Embeddings

---

## 📂 Project Structure

```
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
├── data/
├── database/
├── assets/
└── .streamlit/
```

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/MehakSharma030/C-DAC-Training.git
```

### 2. Navigate to the project

```bash
cd C-DAC-Training/AI_Medico_Bot
```

### 3. Create a virtual environment

```bash
python -m venv medico_env
```

Activate it:

**Windows**

```bash
medico_env\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file inside the project directory.

Example:

```env
GOOGLE_API_KEY=YOUR_GEMINI_API_KEY
```

> **Note:** Never upload your `.env` file to GitHub.

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will open in your default browser.

---

## 📖 How It Works

1. Upload a medical report (PDF).
2. The report is processed and split into smaller chunks.
3. Text embeddings are generated.
4. Embeddings are stored in a FAISS vector database.
5. User questions retrieve the most relevant document chunks.
6. Google Gemini generates answers based on the retrieved context.

---

## 📷 Sample Workflow

- Upload Medical Report
- Process PDF
- Ask Questions
- Receive AI-generated responses

---

## 📦 Dependencies

Major libraries used:

- Streamlit
- LangChain
- Google Generative AI
- FAISS
- PyPDF
- python-dotenv
- HuggingFace Embeddings

Install them using:

```bash
pip install -r requirements.txt
```

---

## 🎯 Future Enhancements

- Multi-PDF support
- Chat history
- Voice-based interaction
- Medical image analysis
- Patient authentication
- Cloud deployment

---

## 👩‍💻 Author

**Mehak Sharma**

Developed as part of the **C-DAC Training Program**.

---

## 📄 License

This project is intended for educational and learning purposes.
