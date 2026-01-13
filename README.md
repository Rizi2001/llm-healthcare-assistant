#  🩺 LLM Healthcare Assistant (DSPy)

An AI-driven healthcare assistant built with **DSPy** that answers health-related questions and suggests **safe home remedies for common conditions** using modern LLM pipelines.

## 🚀 Highlights

- Zero-shot & optimized prompting using **DSPy**
- Retrieval-Augmented Generation (**RAG**) with ChromaDB
- **Chain-of-Thought reasoning** for improved response quality
- Fine-tuning workflow on a custom healthcare dataset

## 🧠 What This Project Demonstrates

- Designing LLM programs beyond simple prompts
- Combining **RAG + reasoning + fine-tuning**
- Building domain-specific AI assistants
- Structuring and evaluating LLM pipelines

## 🛠️ Tech Stack

- Python  
- DSPy  
- Large Language Models (API-based)  
- ChromaDB  
- Retrieval-Augmented Generation (RAG)

## ⚙️ How to Run

```bash
pip install -r requirements.txt
```

Create api_keys.env:
```bash
GOOGLE_API_KEY=AI...
```

Index knowledge base:
```bash
python index_healthcare_db.py
```

Run assistant:
```bash
python health_advisor.py
```

---

```md
## ⚠️ Disclaimer

For educational and experimental purposes only.  
Not intended for real-world medical diagnosis or treatment.
```

