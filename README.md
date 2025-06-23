# Google AI Assistant for Data Tasks using Gemma

This project showcases an AI-driven assistant built using **Google's Gemma LLM** for data science and Python automation. The assistant performs enhanced **Q&A, summarization, and explanation tasks** relevant to data workflows, leveraging both **fine-tuning** and **RAG (Retrieval-Augmented Generation)** techniques.

---

## 🚀 Project Highlights

### 1️⃣ Fine-Tuning with Keras and KerasNLP

- Applied **LoRA (Low-Rank Adaptation)** to fine-tune **Gemma** efficiently on 10,000+ real-world data-related queries.
- Enhanced the assistant’s ability to:
  - Explain Python code and ML concepts
  - Answer data science interview questions
  - Summarize Kaggle solutions
- Achieved noticeable improvements in accuracy and domain relevance.

### 2️⃣ Retrieval-Augmented Generation (RAG) with LangChain

- Integrated **LangChain**'s **retriever-generator architecture** with **ChromaDB** to enhance factual correctness.
- Reduced LLM hallucinations and improved precision of answers.
- RAG setup ensures the assistant can reference external documents during response generation.

---

## 🧪 Technologies Used

| Component         | Tool/Library           |
|------------------|------------------------|
| Language Model    | Google Gemma (via KerasNLP) |
| Fine-tuning       | Keras, LoRA            |
| RAG Pipeline      | LangChain              |
| Vector DB         | ChromaDB               |
| Frameworks        | Python, HuggingFace, KerasNLP |

---

## 📁 Repository Structure

```
├── notebooks/
│ ├── gemma-finetune.ipynb # Fine-tuning Gemma using LoRA
│ └── gemma-rag.ipynb # RAG pipeline with LangChain & ChromaDB
├── README.md
```


