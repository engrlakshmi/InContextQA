
# 🧠 InContext QA

**InContext QA** is a lightweight NLP tool that:
- Extracts content from any URL
- Summarizes the content using a Hugging Face transformer
- Lets you ask questions about that content — all within a simple interface

Perfect for quickly understanding news articles, blog posts, or research summaries.

---

## 🚀 Demo

> Paste a URL → Get a summary → Ask a question about the page

---

## 🔧 Tech Stack

- 🤗 Hugging Face Transformers (`distilbart` for summarization, `distilBERT` for QA)
- 📰 `newspaper3k` for article extraction
- 🧪 Gradio for the UI (can be swapped for Streamlit)
- 🔐 Secure API key management using environment variables

---

## 📦 Requirements

Install dependencies:

```bash
pip install -r requirements.txt
