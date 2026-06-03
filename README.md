# 🤖 ai-pdf-chat-pipeline

> An AI-powered pipeline to chat with your PDFs, right in the browser.

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-Frontend-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/Status-Active-2ea043?style=flat-square)

---

## 📌 Overview

**ai-pdf-chat-pipeline** is a final year project that combines a lightweight browser-based PDF chat interface with a Jupyter notebook AI pipeline. Upload any PDF and interact with its content conversationally — no complex server setup needed to get started.

---

## 🧠 Technology Stack

| Layer | Technology | Purpose |
|-------|------------|---------|
| Frontend | HTML5, CSS3, JavaScript | PDF chat UI in browser |
| Backend | Python 3.8+, Flask / FastAPI | API + request handling |
| AI / ML | LangChain, FAISS, LLM APIs | PDF parsing + chat logic |
| Notebook | Jupyter / JupyterLab | Pipeline exploration |
| Vector Store | FAISS | Semantic search over PDF chunks |
| LLM | Groq / OpenAI API | Language model responses |

---

## 📁 Project Structure

```
ai-pdf-chat-pipeline/
│
├── pdf_chat.html                   # Browser-based PDF chat interface
├── pipeline_with_backend.ipynb     # AI pipeline + backend integration
├── requirements.txt                # Python dependencies
└── README.md
```

---

## 🚀 Quick Start

### 1 — Clone the repo

```bash
git clone https://github.com/your-username/ai-pdf-chat-pipeline.git
cd ai-pdf-chat-pipeline
```

### 2 — Open the HTML interface

```bash
python -m http.server 8000
# open → http://localhost:8000/pdf_chat.html
```

### 3 — Run the notebook

```bash
# create virtual environment
python -m venv .venv
.\.venv\Scripts\Activate        # Windows
source .venv/bin/activate       # macOS / Linux

# install dependencies
pip install -r requirements.txt

# launch
jupyter notebook
# open pipeline_with_backend.ipynb
```

---

## ⚙️ How It Works

```
User uploads PDF
      ↓
PDF parsed into chunks
      ↓
Chunks embedded → stored in FAISS vector store
      ↓
User asks a question
      ↓
Relevant chunks retrieved via semantic search
      ↓
LLM generates answer using retrieved context
      ↓
Response shown in browser UI
```

---

## 🔐 Important Notes

- Add your API keys in a `.env` file — never commit them to GitHub
- If a backend server is needed, run `python app.py` or check the notebook startup cell
- Use `.gitignore` to exclude `.env`, `__pycache__`, and `.venv`

---

## 👨‍💻 Author

**Ummeed** — B.E. Final Year Student  
KLE Technological University, Hubballi | Batch 2027  
*Published researcher in AI/ML*

---

<p align="center">Made with ☕ at KLE Technological University</p>
