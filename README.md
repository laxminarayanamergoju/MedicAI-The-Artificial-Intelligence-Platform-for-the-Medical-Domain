# 🧠 MedicAI – The Artificial Intelligence Platform for the Medical Domain

**MedicAI** is an AI-powered healthcare assistant designed to assist with **disease prediction**, **medical data analysis**, and **retrieval-based question answering** using Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG).

---

## 📌 Features

- 🧠 Multi-agent architecture for tasks like diagnosis support, SQL querying, and medical literature search
- 📊 Disease prediction using ML models (Cancer, Parkinson’s, Heart Disease)
- 🔍 Hybrid information retrieval using BM25, ChromaDB (vector DB), and Neo4j (graph DB)
- 📈 Model tracking and evaluation using **MLflow**
- 🧪 Literature-based insights and RAG-enhanced contextual answers (non-chat UI)

---

## 🛠️ Tech Stack

| Layer            | Tools & Libraries                                     |
|------------------|--------------------------------------------------------|
| 💡 LLMs          | Google Gemma, Phi-3, LLaMA 3, Gemini (offline references) |
| 🔍 Retrieval     | Langchain, ChromaDB, Neo4j, LangGraph                  |
| 💻 ML/Models     | Scikit-learn, Huggingface, Gradient Descent, KNN, SVM |
| 📊 Monitoring    | MLFlow, Evidently AI                                   |
| 🖥️ UI/Backend    | Streamlit (basic UI), Python                           |

---

## 🧪 Disease Prediction Models

- **Cancer Detection** – Gradient Descent (AUC: 0.86)
- **Parkinson’s Detection** – K-Nearest Neighbors (balanced performance)
- **Heart Disease Classification** – Support Vector Machine (Recall: 0.97)

---

## 📂 How to Run

1. Clone the repository:
```bash
git clone https://github.com/laxminarayanamergoju/MedicAI-The-Artificial-Intelligence-Platform-for-the-Medical-Domain.git
cd MedicAI-The-Artificial-Intelligence-Platform-for-the-Medical-Domain

python cancer_model.py
python parkinsons_model.py
python heart_model.py
