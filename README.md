```markdown
# 🦜🔗 LangChain Deep Technical Tutorial  
**Python • LangChain • Open In Colab**

Innomatics Research Labs — Data Science Internship (February 2026)  
A complete hands-on deep dive into LangChain — from fundamentals to a production-style RAG pipeline. Uses Groq (free) for the LLM and HuggingFace for embeddings — no paid API needed.

---

## 📋 What's in This Repository

```

langchain-deep-technical-blog/
│
├── LangChain_Groq_Tutorial.ipynb     # Main Colab notebook (run this!)
├── LangChain_Deep_Technical_Blog.md  # Full blog post
├── requirements.txt                  # Python dependencies
└── README.md                         # This file

````

---

## 🎯 What You'll Learn

| Component | Description |
|----------|------------|
| LLMs & Chat Models | Connect to Groq's Llama 3.3 70B via LangChain |
| Prompt Templates | Build reusable, parameterized prompts with LCEL |
| Chains | Compose pipelines using the \| pipe operator |
| Memory | Add conversation history to make stateful chatbots |
| Agents | Build dynamic reasoning systems that pick tools |
| Custom Tools | Create @tool functions agents can call |
| Vector Stores | Index documents with ChromaDB for semantic search |
| RAG Pipeline | Build a complete document Q&A system |

---

## 🚀 Quick Start

### Option 1: Google Colab (Recommended — No Setup Required)

- Click the **"Open in Colab"** badge above  
- Click **Runtime → Run All**  
- When prompted, enter your free Groq API key  
- Watch it run!  

---

### Option 2: Run Locally in VS Code

```bash
# 1. Clone the repository

# 2. Install dependencies

# 3. Open the notebook
# upload the ipynb file
````

---

## 🔑 API Key Setup — 100% Free

This project uses Groq (free tier, no credit card):

* Go to **console.groq.com**
* Sign up with Google (one click)
* Click **API Keys → Create API Key**
* Paste it when the notebook prompts you

Free limits: **14,400 requests/day** — more than enough for this tutorial.

> ⚠️ Never hardcode your API key in code or commit it to GitHub!

---

## 📦 Key Dependencies

| Package               | Purpose                                |
| --------------------- | -------------------------------------- |
| langchain             | Core framework                         |
| langchain-groq        | Groq LLM integration (free)            |
| langchain-community   | Tools, loaders, HuggingFace embeddings |
| chromadb              | Local vector database for RAG          |
| sentence-transformers | Free local embeddings (no API key)     |

---

## 🏗️ Architecture

```
User Query
    │
    ├──→ Embed (HuggingFace, local) → ChromaDB → Top-K Chunks
    │                                                  │
    └──────────────────────────────────────────────────┤
                                                       ▼
                                              RAG Prompt Template
                                                       │
                                                       ▼
                                              LLM — Groq Llama 3.3
                                                       │
                                                       ▼
                                                 Final Answer ✅
```

---

## 🤝 About

Created for the Innomatics Research Labs Data Science Internship (February 2026).

---

## 📜 License

MIT License — free to use as a learning reference.

```
```

