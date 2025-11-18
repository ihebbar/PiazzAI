# PiazzAI — AI Assistant for Course Forums

PiazzAI is an AI-powered chatbot designed to make course discussion platforms like Piazza easier to navigate.  
Instead of digging through dozens of threads, students can simply *ask a question* and receive an answer grounded in relevant past posts.

This project uses **retrieval-augmented generation (RAG)** to embed course discussion data, perform semantic search, and respond with helpful, context-aware explanations.

---

## 🎯 Project Goals

- Help students quickly find answers hidden in Piazza threads.
- Provide reliable, context-aware responses using real course discussions.
- Preserve privacy by keeping all data stored locally.
- Build a scalable foundation that can later integrate Canvas, Google Search, or a browser extension.
- Learn practical ML/AI skills while creating a resume-ready project.

---

## 🚀 MVP Features

- Upload/import Piazza data (JSON/CSV or manual export)
- Local preprocessing and chunking of posts
- Embeddings + vector search for semantic retrieval
- RAG-powered chatbot that cites relevant Piazza threads
- Minimal frontend chat interface
- All data processed and stored locally for privacy

---

## 🧩 Project Structure

/backend → FastAPI backend, RAG logic, vector store
/frontend → Minimal web UI (HTML/CSS/JS or React)
/data → Example Piazza threads + processed chunks
/scripts → Ingestion + embedding-building scripts


---

## 📚 Tech Stack

**Backend**
- Python  
- FastAPI  
- ChromaDB or custom cosine similarity search  
- OpenAI / local embedding models  

**Frontend**
- Minimal HTML/CSS/JS (MVP)  
- Optional future React UI  

**AI Components**
- Embeddings  
- Semantic search  
- Retrieval-augmented generation (RAG)  

---

## 🔒 Privacy & Security

PiazzAI is built with student data privacy in mind:
- No credentials or scraping required.
- All Piazza data stays **local** on the user’s machine.
- No external storage of course content.

---

## 🌱 Future Enhancements

- Richer chat UI (history, citations, source previews)
- Course-level organization
- Canvas integration
- Web search augmentation
- Browser extension with side panel
- Local LLM support (offline answer generation)
- Weekly Piazza summaries or tag-based topic views

---

## 💡 Why This Project?

Piazza is invaluable—but difficult to search. This project:
- Solves a *real* student pain point,
- Demonstrates practical ML engineering,
- Builds full-stack skills,
- And becomes a standout portfolio piece.

---

## 📬 Contact / Author

Created by **Isha Hebbar**  
Computer Science Student  
University of Wisconsin–Madison

---

## ⭐ Contributing

This project is currently in early development.  
Contributions, issues, and suggestions are welcome as the project grows!



