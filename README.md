# Question-Paper-Generator
A web-based Question Paper Generator that uses the Gemini API to automatically create customizable questions from lecture plans and academic content. Supports PDF, PPTX, and TXT formats with keyword extraction and semantic search for relevance.
---

## 🚀 Features

- 🔐 Secure Gemini API integration
- 📂 Supports `.pdf`, `.txt`, and `.pptx` files
- 🧠 Uses RAKE and FAISS for keyword extraction and semantic similarity
- 📝 Customizable input: university, department, subject, semester, number of questions, difficulty level
- 📤 Exports questions in JSON format
- 🌐 Built using Flask, Bootstrap 4, and modern NLP tools

---

## 🛠️ Tech Stack

- **Backend**: Python (Flask)
- **Frontend**: HTML5, Bootstrap 4
- **NLP**: `rake_nltk`, `faiss`, `nltk`
- **File Handling**: PyPDF2, python-pptx
- **Embeddings & Querying**: Google Gemini API (user-provided key)

---
pip install -r requirements.txt
----
Run the app
python app.py
----
