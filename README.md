
---

````markdown
# 🧾 Conversational RAG PDF Q&A App | LLMs + Memory + Chroma

This project allows you to **chat with your PDFs** using a Retrieval-Augmented Generation (RAG) pipeline.  
Built using **LangChain**, **Groq's Gemma2-9B**, **HuggingFace Embeddings**, and **Chroma DB**, the app supports real-time conversation with memory using uploaded research papers.

🧠 Powered by `RunnableWithMessageHistory` and context-aware question reformulation.

---

## 📌 Use Case

Upload a paper like _“Self-Attention for Generative Models”_ and interactively ask questions while preserving chat memory — similar to ChatGPT browsing mode, but local and focused on your documents.

---

## 🧩 Stack Overview

- 🔥 **LLM**: Groq’s `gemma2-9b-it`
- 🧠 **Embeddings**: HuggingFace `all-MiniLM-L6-v2`
- 📦 **Vector Store**: ChromaDB
- 🧠 **LangChain Features**: Message History, Chaining, Memory-aware Retrieval
- 💬 **Frontend**: Streamlit

---

## 📁 Folder Structure

```bash
.
├── app.py                # Main Streamlit app
├── .env                  # Secrets like GROQ key, HF token
├── requirements.txt      # Dependencies
├── temp.pdf              # Placeholder for uploaded files
└── README.md             # You're reading it
````

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/conversational-rag-pdf.git
cd conversational-rag-pdf
```

### 2️⃣ Set up Virtual Environment

```bash
uv venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Add Your `.env` File

```env
HF_TOKEN=your_huggingface_token
```

Groq API key is entered inside the Streamlit UI at runtime.

---

## 🚀 Running the App

```bash
streamlit run app.py
```

---

## 🛠️ Example Workflow

1. 🔑 Enter your **Groq API key**
2. 📄 Upload PDFs (e.g., *Self-Attention for Generative Models*)
3. 🗣️ Ask questions using natural language
4. 🧠 App reformulates questions based on history
5. 💬 Get contextual answers + chat history

---

## 🧪 Dependencies

```
streamlit
python-dotenv
langchain
langchain-core
langchain-community
langchain-groq
langchain-ollama
langchain-huggingface
langchain-chroma
chromadb
huggingface-hub
faiss-cpu
pypdf
protobuf==3.20.3
```

---

## 🎓 About Me

I'm an **MCA final-year student**, exploring **Applied AI, Generative Models, and LLM RAG systems**.
This project reflects my learning in memory-aware chat systems, embeddings, and real-time vector search.

📌 Open to internships and full-time roles in:

* 📊 Data Science
* 🤖 LLM Engineering
* 🧠 NLP / RAG Systems
* ⚙️ MLOps / AI Research Engineering

🔗 [LinkedIn](https://www.linkedin.com/in/yourname)
🌐 [Portfolio](https://yourwebsite.com)

---

## 🧭 Future Plans

* 🌍 Deploy on Streamlit Cloud / Hugging Face Spaces
* 💾 Save chat history per user to database
* 🔗 Support multi-PDF chaining and chunk summarization

---

⭐ **Star this repo** if it helped you! Fork it to build your own research Q\&A app!

```

---

### ✅ What to Replace:
- `yourusername` in clone URL
- `your_huggingface_token` in `.env`
- LinkedIn and portfolio URLs

Let me know if you'd like:
- A banner for this project (like the others)
- A Hugging Face Spaces deployment guide
- Streamlit Cloud or GCP deployment workflow

Want me to generate a banner for this too?
```
