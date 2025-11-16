# consensus-engine-RQ
production-ready AI Answer Engine (RAG) built with FastAPI, Docker, and a Chroma vector database to find the consensus on any topic.


# Consensus Engine (RQ) 🤖

This project is a high-performance, AI-powered "Answer Engine" built to find the best, most credible answers from community forums like Reddit and Quora.

It is a full **RAG (Retrieval-Augmented Generation)** pipeline that goes beyond simple keyword search. It understands the *semantic meaning* of a user's question, retrieves the most relevant documents from a vector database, and then uses a custom **"Arbiter of Truth"** algorithm to rank them based on community metrics (like upvotes and author credibility). Finally, it uses an LLM to synthesize a single, accurate, and cited answer.

This entire application is built as a production-ready, containerized microservice, complete with a CI/CD pipeline for automated deployment.

---

## 🛠️ Core Tech Stack

This project is designed to showcase a "T-shaped" engineering profile, demonstrating deep expertise in AI/ML and broad skills in modern backend SDE.

* **Backend:** `FastAPI` (for a high-speed, asynchronous API)
* **AI/NLP:** `RAG Pipeline`, `Sentence-Transformers` (for embeddings), `ChromaDB` (as the vector store)
* **Database:** `SQLite` (for production API logging and performance monitoring)
* **DevOps:** `Docker` (for containerization), `GitHub Actions` (for CI/CD), `Render` (for cloud deployment)
