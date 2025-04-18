# AI-health-bot-

![Uploading PHOTO-2025-04-18-18-52-16.jpg…]()


# 🧠 Medical AI Chatbot

This is a simple AI chatbot built for the **medical domain**, leveraging powerful NLP tools like **Sentence Transformers**, **LangChain**, **Pinecone**, and **Flask** for a seamless user experience. It can read and understand medical PDFs, store their embeddings in Pinecone, and respond to user queries in real-time.

---

## 🚀 Features

- ✅ Extract text from medical PDFs using `pypdf`
- ✅ Generate semantic embeddings using `sentence-transformers`
- ✅ Store and retrieve embeddings via `Pinecone`
- ✅ Query handling and chain management using `LangChain`
- ✅ Lightweight web interface with `Flask`
- ✅ Environment management with `.env` using `python-dotenv`

---

## 🧰 Tech Stack

- `sentence-transformers==2.2.2` – For generating high-quality embeddings.
- `langchain` – For managing prompts and chaining tools together.
- `flask` – Web framework to serve the chatbot.
- `pypdf` – Extract text from PDFs.
- `python-dotenv` – Manage environment variables.
- `pinecone[grpc]` – Vector database to store & search embeddings.
- `langchain-pinecone` – Pinecone integration for LangChain.
- `langchain_community` – Tools and wrappers for community integrations.
- `langchain_openai` – LLM integration for question answering.
- `langchain_experimental` – Experimental utilities and chains.

---
