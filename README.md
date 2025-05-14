# Retrieval-Augmented Generation (RAG) with LLMs

This project implements a **Retrieval-Augmented Generation (RAG)** system that enhances text generation using external knowledge sources. The pipeline combines document chunking, vector-based similarity search, and a large language model to generate precise and contextually relevant responses.

## 🔍 Overview

The goal of this project is to demonstrate how retrieval-based techniques can be paired with modern LLMs to improve the factual accuracy and contextual relevance of generated answers.

### 📌 Key Features
- **Preprocessing Pipeline**: 
  - Sentence chunking of text documents.
  - Embedding of chunks using [Sentence-Transformers](https://www.sbert.net/) to generate high-dimensional vector representations.
  
- **Similarity Search**:
  - Employed **Cosine Similarity** and **Approximate Nearest Neighbor (ANN)** search for retrieving semantically relevant chunks from the vector database.
  
- **Retrieval-Augmented Generation**:
  - Used retrieved chunks as context to formulate enriched prompts.
  - Leveraged the **Google Gemini** LLM for generating high-quality, coherent, and accurate responses.

- **Fine-Tuning**:
  - Fine-tuned the Gemini model on domain-specific data to improve Q&A performance and alignment with project requirements.

## 🧠 Architecture

![Screenshot from 2025-05-14 11-14-46](https://github.com/user-attachments/assets/6ad30571-917d-4641-9556-8a93821b7f1d)

## 🛠️ Technologies Used

- **Python**
- **Sentence-Transformers**
- **Google Gemini (LLM)**
- **Hugging-Face**
- **Embeddings**
- **Tokenization**
