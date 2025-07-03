# CrediTrust Complaint-Answering RAG Chatbot

## Project Overview
This project develops an internal AI tool for CrediTrust Financial, leveraging Retrieval-Augmented Generation (RAG) to provide synthesized, evidence-backed answers to natural language questions about customer complaints from the CFPB database.

## Project Structure
```
creditrust-rag/
├── data/
├── notebooks/
├── src/
├── vector_store/
├── reports/
├── screenshots/
├── .gitignore
├── README.md
└── requirements.txt
```
## Setup and Installation
1.  **Clone the repository:**
    ```bash
    git clone <your-repo-url>
    cd creditrust-rag
    ```
2.  **Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    .\venv\Scripts\activate # On Windows PowerShell
    ```
3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## How to Run
(Detailed instructions will be added here for each task as the project progresses.)

## Key Deliverables & Tasks
- **Task 1: EDA & Preprocessing:** Cleaned dataset (`data/filtered_complaints.csv`).
- **Task 2: Embedding & Vector Store:** Persisted vector index (`vector_store/`).
- **Task 3: RAG Core & Evaluation:** RAG pipeline (`src/rag_pipeline.py`), evaluation table (`reports/evaluation_table.md`).
- **Task 4: Interactive UI:** Gradio/Streamlit app (`src/app.py`), UI screenshots (`screenshots/`).

---
Developed for CrediTrust Financial as a Data & AI Engineer.