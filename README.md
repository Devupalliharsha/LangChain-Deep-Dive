# 🦜🔗 LangChain Internship Assignment – Innomatics Research Labs, Feb 2026

> **My LangChain assignment code. Run on Google Colab and install the right dependencies.**

---

## 👤 Author
**Harsha Devupalli** | Gen AI Intern | Innomatics Research Labs  
Assignment: *GenAI – LangChain Deep Technical Blog*


## 🚀 How to Run

### Option 1: Google Colab (Recommended)
1. Open [Google Colab](https://colab.research.google.com/)
2. Go to **File → Upload notebook**
3. Upload `LangChain_Assignment.ipynb`
4. Get your **free** Groq API key at [console.groq.com](https://console.groq.com)
5. Run all cells top to bottom

### Option 2: Local Setup
```bash
clone my git and run it manually
```

---

## 📖 What's Covered in the Notebook

| Section | Component | Description |
|---------|-----------|-------------|
| 1 | Installation | All required libraries |
| 2 | API Key Setup | Secure getpass approach |
| 3 | LLM / ChatGroq | Basic invoke + streaming |
| 4 | PromptTemplates | Reusable prompt design |
| 5 | Chains (LCEL) | Pipe operator composition |
| 6 | Memory | Multi-turn conversation |
| 7 | Agents + Tools | Dynamic tool calling |
| 8 | RAG Pipeline | Document Q&A with Chroma |
| 9 | Architecture | ASCII diagram |
| 10 | Summary | All components overview |

---

## 🛠️ Tech Stack

- **LLM**: Groq API → Llama 3.3-70B-Versatile (free tier)
- **Framework**: LangChain (LCEL)
- **Vector DB**: ChromaDB
- **Embeddings**: HuggingFace `all-MiniLM-L6-v2` (free, local)
- **Runtime**: Google Colab

---

## 📝 Blog Post

Read the full technical blog post on Medium:  
**[My Deep Dive into LangChain: From Zero to Building LLM Apps] :https://medium.com/@devupalliharsha/my-deep-dive-into-langchain-from-zero-to-building-llm-apps-1aceeaa1a9be **

---

## 📌 Key Concepts Demonstrated

- **LCEL (LangChain Expression Language)**: The pipe `|` operator for chaining Runnables
- **RAG**: Retrieval-Augmented Generation for document Q&A
- **Agents**: Dynamic tool selection using Llama3.3
- **Memory**: Per-session conversation history with `RunnableWithMessageHistory`

---

*Submitted as part of Innomatics Research Labs – GenAI Internship, February 2026*

---

⭐ Star this repo if it helped you learn LangChain!
