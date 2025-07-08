🔗 👉 **[Watch the Demo on YouTube](https://www.youtube.com/watch?v=e6-uXlkQFQc&list=PLe-YIIlt-fbO3hXVoaPK56ikWRT0A9Gzr&index=5&ab_channel=Jatin)**
# 🧾 Conversational RAG PDF Q&A App | LLMs + Memory + Chroma

This project allows you to **chat with your PDFs** using a Retrieval-Augmented Generation (RAG) pipeline.  
Built using **LangChain**, **Groq's Gemma2-9B**, **HuggingFace Embeddings**, and **Chroma DB**, the app supports real-time conversation with memory using uploaded research papers.

🧠 Powered by `RunnableWithMessageHistory` and context-aware question reformulation.

---

## 📌 Use Case

Upload a paper like _“Self-Attention for Generative Models”_ and interactively ask questions while preserving chat memory — similar to ChatGPT browsing mode, but local and focused on your documents.

---

## 🧩 Stack Overview

| Component        | Tech Used                        |
|------------------|----------------------------------|
| 🔥 LLM            | Groq’s `gemma2-9b-it`             |
| 🧠 Embeddings     | HuggingFace `all-MiniLM-L6-v2`    |
| 📦 Vector Store   | ChromaDB                          |
| 💬 Memory         | LangChain Runnable + History      |
| 🌐 Frontend       | Streamlit                         |

---

## 📁 Folder Structure

```bash
.
├── app.py                # Main Streamlit app
├── .env                  # Secrets like HF token
├── requirements.txt      # Dependencies
├── temp.pdf              # Placeholder for uploaded files
└── README.md             # You're reading it
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/jatinydav557/RAG-QnA-conv-app.git
cd RAG-QnA-conv-app
```

### 2️⃣ Set up Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Add Your `.env` File

```env
HF_TOKEN=your_huggingface_token
```

🟡 Note: Your Groq API key is securely entered at runtime via Streamlit input — not saved in `.env`.

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

I’m **Jatin**, a final-year MCA student passionate about building real-world apps using **GenAI**, **LLMs**, and **RAG pipelines**.  
This project showcases my skills in **embedding-based search**, **contextual memory**, and **LLM chaining** for PDF-based Q&A.

📌 Actively looking for:

* 📊 Data Science Roles  
* 🧠 LLM / GenAI Engineering  
* 🤖 NLP & RAG Systems  
* ⚙️ MLOps / Research Engineering

---

## 📞 Let's Connect

- **💼 LinkedIn:** [linkedin.com/in/jatin557](https://www.linkedin.com/in/jatin557)
- **📦 GitHub:** [github.com/jatinydav557](https://github.com/jatinydav557)
- **📬 Email:** [jatinydav557@gmail.com](mailto:jatinydav557@gmail.com)
- **📱 Phone:** [+91-7340386035](tel:+917340386035)
- **🎥 YouTube:** [Watch Other Projects](https://www.youtube.com/@jatinML/playlists)

---

## 🧭 Future Plans

* 🌍 Deploy on Streamlit Cloud / Hugging Face Spaces  
* 💾 Save chat history per user to local DB  
* 🔗 Support multi-PDF chaining and automatic summarization  

---

⭐ If this project inspired you, **give it a star** and feel free to fork and customize it!

> “Build assistants *you* control — not just use ones built by others.”

