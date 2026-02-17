🔍 PDF RAG Chatbot

A Retrieval-Augmented Generation (RAG) chatbot that allows users to upload a PDF and ask context-aware questions. The system retrieves relevant document chunks using semantic search and generates grounded responses using a large language model.

🚀 Features

Upload any PDF document

Automatic text chunking and embedding generation

Semantic search using vector database

Context-aware answer generation

Interactive chat interface built with Panel

Supports multiple questions per uploaded document

🧠 How It Works

The project follows a structured RAG pipeline:

Load PDF – Extract text from uploaded document

Chunk Text – Split document into smaller segments

Generate Embeddings – Convert chunks into vector representations

Store in Vector DB – Save embeddings in Chroma

Retrieve Context – Perform similarity search for relevant chunks

Prompt LLM – Inject context + question into structured prompt

Generate Answer – LLM produces grounded response

🛠 Tech Stack

Python

LangChain

Hugging Face Embeddings

Chroma Vector Database

Panel (UI Framework)



📌 Project Goal

This project demonstrates a manually constructed RAG architecture for deeper understanding of retrieval, embedding, and prompt injection workflows, combined with a lightweight interactive UI.
