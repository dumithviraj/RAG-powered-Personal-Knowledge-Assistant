# 🧠 Personal Knowledge Assistant using RAG (Retrieval-Augmented Generation)

This is a custom-built **Personal Knowledge Assistant** designed specifically for **Material and Nanoscience Technology students**. It leverages the power of **OpenAI's GPT-3.5 Turbo** and **`text-embedding-3-small`** embedding model to interact with a private knowledge base created from semester lab experiment handouts (PDFs).

### 🎯 Project Objective

As students, we often receive lab manuals and experiment handouts in PDF format throughout the semester. Finding specific information from these documents quickly—especially during exam prep or lab report writing—can be time-consuming.

This assistant solves that problem by enabling **natural language querying** of these documents. Ask a question like “What is the procedure for the titration of KMnO₄?” and get an accurate, relevant answer instantly from your own materials.

---

### 🔧 Tech Stack

* **Language Model:** OpenAI GPT-3.5 Turbo (via API)
* **Embedding Model:** `text-embedding-3-small`
* **Document Handling:** PDF parsing with `PyMuPDF`
* **Vector Store:** FAISS
* **RAG Pipeline:** Custom Python script integrating embedding + retrieval + generation

---

### 🚀 Features

* Upload and convert multiple PDF lab handouts into vector embeddings.
* Ask natural language questions and receive accurate responses sourced directly from your own documents.
* Ideal for students in science and engineering fields needing quick access to technical procedures, equations, or definitions.

---

### 📚 Use Case

Currently optimized for **Material and Nanoscience Technology lab handouts**, but can be adapted for any academic discipline or document collection.

---

### 🔗 Get Started

1. Clone the repo
2. Add your PDF documents
3. Run the script and start asking questions!
.
