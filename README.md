# Enhancing-Small-Language-Models(SLM)-for-Co-Creative-Mathematical-Storytelling-using-RAG
# 🧮 SLM Math Storyteller — RAG Enhanced

An offline, co-creative math adventure application powered by a Small Language Model (SLM) integrated with Retrieval-Augmented Generation (RAG).

## 🚀 Key Features
* **Local SLM:** Powered completely offline by Qwen-2.5-1.5B via `llama-cpp`.
* **RAG Engine:** Uses a localized FAISS vector database to retrieve syllabus-specific math contexts from the `Math_Project` folder.
* **Math Verification Layer:** Integrates SymPy to automatically parse, evaluate, and verify mathematical logic in AI-generated stories.
* **Entity Tracking & Coherence:** Employs spaCy for real-time character and place consistency metrics.

## 🛠️ Setup Instructions
1. Clone this repository.
2. Create a virtual environment: `python -m venv venv`
3. Activate the environment: `.\venv\Scripts\activate`
4. Create a folder named `models` and place `qwen2.5-1.5b-instruct-q4_k_m.gguf` inside it.
5. Build the vector database: `python create_index.py`
6. Launch the application UI: `python app.py`
