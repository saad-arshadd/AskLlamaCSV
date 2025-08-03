# 🧠 AskLlamaCSV — Conversational Q&A from CSV using Local LLaMA3

AskLlamaCSV is a lightweight, blazing-fast LangChain + RAG project that enables users to **upload a CSV (e.g., restaurant reviews)** and **ask natural language questions**, powered by **LLaMA3** running locally via **Ollama**.

> 🦙 100% local inference — no API keys, no cloud costs.

---

## 🚀 Features

- 🗂️ Upload CSV (e.g., customer reviews, product feedback, etc.)
- 🧠 Asks questions using **LLaMA 3 locally**
- 📚 Retrieves the most relevant data using **Chroma vector DB**
- 🔗 Uses **LangChain** to combine Retrieval-Augmented Generation (RAG) with LLMs
- ⚡ Real-time Q&A from structured data

---
## ISNTALL REQUIREMENETS :
pip install -r requirements.txt


## 📦 Tech Stack

- [LangChain](https://www.langchain.com/)
- [Ollama](https://ollama.com/)
- [LLaMA 3](https://ollama.com/library/llama3)
- [ChromaDB](https://www.trychroma.com/)
- [Pandas](https://pandas.pydata.org/) (for CSV parsing)

---

## 🛠️ Setup Instructions

### ✅ 1. Install Ollama

First, you need to install **Ollama** (used to run LLaMA3 locally):

```bash
curl -fsSL https://ollama.com/install.sh | sh

## Then Pull the required models
ollama pull llama3
ollama pull mxbai-embed-large


