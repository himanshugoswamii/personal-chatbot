# Build Your Own Chatbot with LangChain & RAG

This project demonstrates how to build an intelligent chatbot from scratch using LangChain, OpenAI's LLMs, and Retrieval-Augmented Generation (RAG). It allows the chatbot to interact with users and provide context-rich responses based on content extracted from uploaded PDFs.

🧠 Features
📄 PDF document ingestion and chunking

🔍 Contextual retrieval using vector stores (ChromaDB)

💬 Natural language responses powered by OpenAI models

🧱 LangChain integration for structured RAG pipeline

🎛️ Interactive Gradio user interface

🛠️ Tech Stack

Python

LangChain & langchain-community

OpenAI API

Gradio

ChromaDB

PyPDF2 / pypdf

📚 What It Does

Library Installation:
Installs all required packages including LangChain, OpenAI, and PDF libraries.

Dataset Setup:
Downloads and extracts PDF files used to simulate a knowledge base.

Document Chunking:
Splits large PDF documents into manageable text chunks for effective retrieval.

RAG Initialization:
Uses ChromaDB to store and retrieve embeddings, then combines this with an LLM to create a context-aware chatbot.

Custom Response Function:
Generates answers based on retrieved text and user query.

User Interface:
Uses Gradio to launch a simple chatbot interface in the browser.
