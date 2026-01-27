# 🚀 GenAI – Large Language Models & RAG (Retrieval-Augmented Generation)

This repository contains **hands-on implementations of Generative AI concepts**, focusing on **Large Language Models (LLMs)**, **Prompt Engineering**, **Embeddings**, and a **complete RAG (Retrieval-Augmented Generation) pipeline**.

The project is designed as a **learning-by-building journey**, where each script demonstrates a core GenAI concept — from basic OpenAI API usage to a full production-style RAG pipeline.

---

## 📌 What You’ll Learn from This Repo

- How LLMs work using OpenAI APIs  
- Prompt engineering techniques (system, role-based, few-shot)  
- Streaming responses from LLMs  
- Embeddings and vector similarity search  
- Building an **end-to-end RAG pipeline**  
- Using LangChain for GenAI applications  
- Structuring GenAI projects professionally for GitHub  

---

## 🗂️ Project Structure

```text
GenAI/
│
├── ch_1(chat_completions).py      # Basic chat completion using LLMs
├── ch_1(openai).py                # OpenAI API fundamentals
├── ch_2(system_vs_user).py        # System vs User prompts
├── ch_3(chain_of_thought).py      # Chain-of-thought prompting
├── ch_4(output_formatting).py     # Structured & formatted outputs
├── ch_5(role_based_prompt).py     # Role-based prompt engineering
├── ch_6(few_shot).py              # Few-shot prompting
├── ch_7(table_output).py          # Tabular outputs from LLMs
├── ch_8(streaming_response).py    # Streaming responses
├── ch_9(embedding).py             # Text embeddings
├── ch_10(full_RAG_pipeline).py    # Complete RAG pipeline
├── ch_11(langchain).py            # LangChain integration
│
├── sales_data_sample.csv          # Sample dataset for RAG demo
└── README.md
```
## 🧠 Key Concepts Covered

**🔹 Prompt Engineering**

- System vs user instructions
- Role-based prompts
- Few-shot learning
- Chain-of-thought reasoning

**🔹 Embeddings**

- Convert text into vectors
- Semantic similarity search
- Foundation of RAG systems

**🔹 RAG (Retrieval-Augmented Generation)**

- Retrieve relevant context from data
- Inject retrieved knowledge into prompts
- Reduce hallucinations
- Improve factual accuracy

**🔹 LangChain**

- Chains and prompt templates
- LLM orchestration
- RAG workflows using LangChain

## 🔁 What is RAG & Why It Matters?

<br>Retrieval-Augmented Generation (RAG) combines:<br>
- 🔍 Information Retrieval (searching documents)
- 🧠 Generation (LLMs)

<br>Instead of relying only on model memory, RAG:<br>
- Pulls relevant external data
- Feeds it into the LLM
- Produces more accurate, up-to-date answers

<br>This approach is widely used in:<br>
- Chatbots
- PDF Q&A systems
- Customer support bots
- Internal knowledge assistants

## ⚙️ Requirements

**Create a virtual environment (recommended):**
```
python -m venv venv
source venv/bin/activate   # macOS/Linux
```
**Install dependencies:**
```
pip install openai langchain pandas numpy
```
## 🔑 Environment Setup

**Create a .env file (do NOT push to GitHub):**
```
OPENAI_API_KEY=your_api_key_here
```
## ▶️ How to Run

Run a basic chat completion:
```
python ch_1(chat_completions).py
```
Run the full RAG pipeline:
```
python ch_10(full_RAG_pipeline).py
```
