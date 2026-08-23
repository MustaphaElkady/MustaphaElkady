# Hi, I'm Mustafa 👋

AI/ML Engineer & Teaching Assistant focused on **Arabic OCR & Document AI**, **LLM Fine-Tuning**, and **Retrieval-Augmented Generation (RAG)**.

I build complete AI systems end-to-end — from dataset engineering and model fine-tuning to retrieval pipelines, backend APIs, and production deployment.

## Areas of Interest

- Arabic OCR & Document AI
- Fine-Tuning Large Language Models (SFT, LoRA, QLoRA)
- Retrieval-Augmented Generation (RAG)
- Arabic NLP & Dialect Processing
- LLM Evaluation & Error Analysis
- AI Backend Systems

## Current Projects

### 📚 Safha – Arabic OCR Dataset Engineering Platform *(Ongoing)*

An open-source pipeline for building high-quality Arabic OCR training data by pairing scanned pages from digitized historical books with human-verified transcriptions.

- Designed a modular FastAPI backend with SQLAlchemy metadata management, Alembic migrations, SQLite, and S3-compatible object storage.
- Integrated Arabic Wikisource and MediaWiki APIs to retrieve page-level transcriptions, revision metadata, and source-quality/provenance information.
- Built a 4-stage data lifecycle (raw → interim → processed → curated) with UUID entity IDs and SHA-256 asset fingerprints for reproducibility.
- Currently building PDF extraction, image-text alignment, and validation stages.

**Tech:** Python, FastAPI, SQLAlchemy, SQLite, Alembic, AWS S3, MediaWiki API, Arabic Wikisource

---

### 🔎 Historical Arabic OCR & Knowledge Model Fine-Tuning

Fine-tuning Qwen-family vision-language and language models for OCR and knowledge extraction from historical Arabic documents, with a live interactive demo.

- Prepared structured supervised fine-tuning datasets for OCR, transcription, and information-extraction tasks.
- Applied and compared three fine-tuning approaches — SFT, LoRA, and QLoRA — using LLaMA-Factory training/inference workflows.
- Evaluated checkpoints against reference outputs with qualitative and quantitative error analysis on difficult historical documents.
- Covered the full lifecycle: dataset → fine-tuning → inference → evaluation.

**Tech:** Python, PyTorch, Qwen2.5-VL, Qwen2.5, Hugging Face Transformers, LLaMA-Factory, SFT, LoRA, QLoRA
**Model:** [arabic-historical-ocr-1.0](https://huggingface.co/mustaphaelkady/arabic-historical-ocr-1.0)
**Live demo:** [arabic-historical-ocr-demo](https://huggingface.co/spaces/mustaphaelkady/arabic-historical-ocr-demo)

---

### 📜 Hakaa (حكّاء) – Arabic Historical RAG Platform

A production-deployed, Arabic-first RAG platform for exploring historical books and documents through natural-language conversations.

- Built a full project-based system with a public chat interface and a protected admin dashboard for document upload, chunking config, and indexing.
- Implemented Arabic-aware text preprocessing and recursive chunking with preserved source metadata (file, page number).
- Deployed a production stack with FastAPI, PostgreSQL/pgvector, Nginx (HTTPS + Basic Auth), Docker Compose, and CI/CD via GitHub Actions.
- Added full observability with Prometheus, Grafana, and Loki.
- Currently extending retrieval with hybrid search, Reciprocal Rank Fusion, and reranking (Hakaa v2).

**Tech:** Python, FastAPI, PostgreSQL, pgvector, Qdrant, LangChain, Docker Compose, Nginx, Prometheus, Grafana, Loki
**Live demo:** [hakaa.publicvm.com](https://hakaa.publicvm.com)

---

### 🔎 Mini-RAG

A modular Retrieval-Augmented Generation application for document-based question answering.

- Built a 4-layer route → service → repository → provider architecture separating API, persistence, embedding, retrieval, and generation responsibilities.
- Integrated two complementary data stores — MongoDB for asset metadata and Qdrant for vector search — with Docker-based setup for reproducible workflows.
- Handled document ingestion, chunking, embedding generation, vector indexing, and semantic retrieval.

**Tech:** Python, FastAPI, MongoDB, Qdrant, LangChain, PyMuPDF, Docker
**GitHub:** [mini-rag](https://github.com/MustaphaElkady/mini-rag)

---

### 🗣️ Arabic Dialect Sentiment Swap – LLM/NLP Fine-Tuning

An Arabic dialect sentiment-rewriting pipeline that flips sentiment while preserving meaning, dialect, and writing style.

- Benchmarked three model baselines — AraT5v2, mT0, and Qwen2.5 — and configured LLaMA-Factory supervised fine-tuning with QLoRA.
- Prepared structured JSONL/Excel datasets with validation and model-output review workflows.
- Built a Streamlit inspection tool for evaluation and error analysis.

**Tech:** Python, PyTorch, Hugging Face, Qwen2.5, AraT5v2, mT0, LLaMA-Factory, QLoRA, Streamlit
**GitHub:** [dialect-sentiment-swap](https://github.com/MustaphaElkady/dialect-sentiment-swap)

---

### 🧠 NLP Learning Cycle

An educational NLP project comparing different sequence-modeling architectures.

- Implemented and compared RNN, LSTM, and Transformer models across tokenization, sequence modeling, and language-model training.
- Used WikiText-2 for practical experimentation with NLP architectures.

**Tech:** Python, PyTorch, RNN, LSTM, Transformers, WikiText-2
**GitHub:** [NLP-Learning-Cycle](https://github.com/MustaphaElkady/NLP-Learning-Cycle)

## Additional Projects

### 🔐 Face Verification System

A modular face-verification application with environment configuration, runnable scripts, and a Streamlit interface for demonstration and testing.

**Tech:** Python, OpenCV, FastAPI/Uvicorn, Streamlit
**GitHub:** [face-verification](https://github.com/MustaphaElkady/face-verification)

## Tech Stack

**LLMs & NLP:**
Hugging Face Transformers, LLaMA-Factory, SFT, LoRA, QLoRA, Qwen-family Models, AraT5v2, mT0, Arabic NLP, Multilingual NLP, Prompt Engineering

**OCR & Document AI:**
Arabic OCR, OCR Dataset Engineering, Document Understanding, Dataset Curation, Image-Text Alignment, PDF Processing, Data Provenance

**RAG & Retrieval:**
LangChain, Qdrant, PGVector, Embeddings, Semantic Search, Document Ingestion & Chunking, Vector Indexing

**Machine Learning:**
PyTorch, TensorFlow, Keras, Scikit-learn, CNN, RNN, LSTM, Model Training & Evaluation

**Backend & Data:**
Python, FastAPI, REST APIs, SQLAlchemy, SQLite, MongoDB, Alembic, AWS S3, MediaWiki API, Pandas

**Tools & Deployment:**
Docker, Git, Nginx, Prometheus, Grafana, Streamlit

## Experience

**Teaching Assistant** — Faculty of Computers & AI, Hurghada University *(Jun 2024 – Present)*
Delivering practical labs in Python, data structures, algorithms, AI, and machine learning; mentoring students on ML, NLP, Transformers, and Hugging Face tooling.

## Education

**M.Sc. Computer Science** *(In Progress)* — Faculty of Science, Qena University *(Sep 2025 – Present)*
**B.Sc. Computer Science** — Faculty of Science, South Valley University *(Jun 2022)*

## Contact

- GitHub: [MustaphaElkady](https://github.com/MustaphaElkady)
- LinkedIn: [linkedin.com/in/mustafa-elkady-100533231](https://linkedin.com/in/mustafa-elkady-100533231)
- Email: [mustaphaelkady@gmail.com](mailto:mustaphaelkady@gmail.com)
