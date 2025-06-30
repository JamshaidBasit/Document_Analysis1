# 🇵🇰 Pakistan Content Review System 🇵🇰

## AI-Powered Review for National Narratives

![GitHub Workflow Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Python Version](https://img.shields.io/badge/Python-3.9%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🚀 Overview

This project provides an **AI-powered system designed to review content, particularly from books on Pakistan's history and politics.** Its primary goal is to identify text segments that may not align with official Pakistani policies, national narratives, or cultural sensitivities.

Leveraging advanced Large Language Models (LLMs), LangChain, LangGraph, and a robust MongoDB/ChromaDB backend, this system automates the preliminary review process, highlighting potentially problematic content for further human examination.

### ✨ Key Features:

* **Dynamic Agent-Based Review:** Customizable review agents (e.g., historical accuracy, cultural sensitivity) loaded dynamically from MongoDB.
* **LLM-Powered Analysis:** Utilizes powerful LLMs (Groq, Llama) for in-depth content evaluation.
* **Vector-Based Knowledge Base:** Integrates a ChromaDB knowledge base to provide contextual information and official narratives to agents.
* **PDF Processing:** Extracts and chunks text from PDF documents for systematic review.
* **Zero-Shot Text Classification:** Categorizes text segments (e.g., military events, historical figures) using a transformer-based classifier to route to relevant agents.
* **Comprehensive Reporting:** Generates detailed reports on identified issues, confidence scores, and recommendations (delete, rephrase, fact-check, human review).
* **Persistent Data Storage:** Uses MongoDB for storing PDF data, agent configurations, knowledge base information, and final analysis results.

---

## 🛠️ Technologies Used

* **Python:** Core programming language.
* **LangChain:** Framework for developing LLM-powered applications.
* **LangGraph:** For building stateful, multi-actor applications with LLMs (agent orchestration).
* **MongoDB:** NoSQL database for storing application data (PDF chunks, agent configs, knowledge base, results).
* **ChromaDB:** Vector database for semantic search and knowledge retrieval.
* **Hugging Face Transformers:** For the zero-shot text classification pipeline.
* **FastEmbed:** Lightweight library for generating embeddings.
* **PyMongo:** Python driver for MongoDB.
* **python-dotenv:** For managing environment variables.
* **pdfplumber:** For extracting text from PDF files.
* **Groq API:** For high-performance LLM inference.

---

## 📋 Setup Instructions

Follow these steps to get your project up and running locally.

### 1. Clone the Repository

First, clone this repository to your local machine:

```bash
git clone [https://github.com/JamshaidBasit/Document_Analysis.git](https://github.com/JamshaidBasit/Document_Analysis.git)
cd Document_Analysis # Navigate into your project directory