# 🚀 RAG Zero to Hero: 10-Day Mastery Roadmap
## Official AI Training Track | Pakistan Cyber Security Defense Foundation (PCSDF)

[![PCSDF](https://img.shields.io/badge/Organization-PCSDF-green)](https://github.com/pcsdf)
[![Track](https://img.shields.io/badge/Track-Generative%20AI-blue)](#-roadmap-overview)
[![Duration](https://img.shields.io/badge/Duration-10%20Days-orange)](#-how-to-use-this-repository)

> **A comprehensive, zero-to-hero journey into Retrieval-Augmented Generation (RAG). This repository is designed to take you from Python fundamentals to deploying production-ready AI agents in just 10 days.**

---

## 📖 Curriculum Description

This roadmap systematically builds your skills, ensuring a solid foundation before tackling advanced AI architectures. By the end of this course, you will have built a portfolio-worthy RAG system capable of "chatting" with your own data.

**You will master:**
* 🐍 **Python for AI:** Data structures, API integration, and async handling.
* 🧠 **LLM Fundamentals:** Prompt Engineering and Chain-of-Thought reasoning.
* 📚 **Data Pipelines:** PDF extraction, chunking strategies, and cleaning.
* 🔎 **Vector Search:** Embeddings, ChromaDB, and semantic similarity.
* ⚙️ **RAG Frameworks:** LangChain, LlamaIndex, and Hybrid Search.
* 🚀 **Deployment:** Building APIs with FastAPI and UIs with Streamlit.

---

## 📚 Roadmap Overview

| Day | Module Title | Focus Area |
| :--- | :--- | :--- |
| **01** | [**Python Foundations**](./Day-01%20Python%20Foundations%20for%20GenAI) | Python basics, data structures, file handling, APIs |
| **02** | [**GenAI & LLM Basics**](./Day-02) | Understanding LLMs, OpenAI API, model capabilities |
| **03** | [**Prompt Engineering**](./Day-03) | Chain-of-Thought, Few-Shot, and System Prompts |
| **04** | [**Data Extraction**](./Day-04) | PDF parsing, Web Scraping, Chunking Strategies |
| **05** | [**Vector Databases**](./Day-05) | Embeddings, Cosine Similarity, ChromaDB Setup |
| **06** | [**RAG Fundamentals**](./Day-06) | The Retrieval → Augmentation → Generation Loop |
| **07** | [**RAG from Scratch**](./Day-07) | Building a RAG system without frameworks (Pure Python) |
| **08** | [**LangChain & LlamaIndex**](./Day-08) | Mastering the industry-standard frameworks |
| **09** | [**Advanced RAG**](./Day-09) | Reranking, Query Rewriting, Fusion Retrieval |
| **10** | [**Deployment**](./Day-10) | FastAPI, Streamlit, and Production Best Practices |

---

## 🎯 How to Use This Repository

1.  **Sequential Learning:** Start with [Day 01](./Day01) and move forward. Do not skip days.
2.  **Daily Routine:**
    * 📖 **Read:** Open the `README.md` in each day's folder.
    * 💻 **Code:** Type out the examples yourself (don't just copy-paste!).
    * 🛠️ **Build:** Complete the `assignment.md` tasks to verify your skills.
3.  **Time Commitment:** Expect to spend **2-4 hours per day**.

---

## 🛠️ Technical Requirements

### 1. Prerequisites
* **Python 3.10+** installed.
* Basic familiarity with the Command Line (Terminal/Git Bash).
* **OpenAI API Key** (Required for Day 02+). [Get one here](https://platform.openai.com).

### 2. Environment Setup
Create a virtual environment and install the core dependencies:

```bash
## Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
## Install core libraries
```bash
pip install openai langchain llama-index chromadb sentence-transformers pypdf fastapi streamlit
```
## 3. Secure Your Keys
Create a .env file in the root directory to keep your secrets safe:

## Code snippet
```bash
OPENAI_API_KEY=sk-proj-your-key-here
```
## 🗂️ Repository Structure
```bash
Advanced-RAG-Architecture/
│
├── Day01/ (Python Foundations)
│   ├── README.md   <-- Start Here
│   └── assignment.md
│
├── Day02/ (GenAI Basics)
│   ├── README.md
│   └── assignment.md
│
... (Days 03-09) ...
│
├── Day10/ (Deployment)
│   ├── README.md
│   └── assignment.md
│
└── README.md (This File)
``` 
## 🎓 Tips for Success
Code Along: The only way to learn AI engineering is by typing the code.

Break Things: Try changing the prompt or the chunk size. See what breaks. That's how you learn.

Join the Community: Share your progress with other PCSDF members.

## ⚖️ License & Credits
Developed by: PCSDF AI Education Division

Original Concept: Adapted from open-source community roadmaps.

Motto: Defending Digital Borders through Intelligence.


### 💡 Pro Tip:
In the "Roadmap Overview" table, I made the "Module Title" clickable links (e.g., `[Python Foundations](./Day01)`).
* **Make sure** you actually create folders named `Day01`, `Day02`, etc., inside your repo.
* If you don't create the folders, the links won't work yet (but they will work automatically once you add the folders later!).

**Would you like me to generate the content for Day 2 ("Generative AI & LLM Basics")
