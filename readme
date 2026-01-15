# CareerSense AI

> **CV-Aware Career Advisory Platform (RAG-Based)**  
> Modular backend for personalised career guidance applications.

---

## Overview

CareerSense AI is a modular career advisory system that enables applications to deliver **personalised, CV-aware career guidance**.  
It grounds large language model (LLM) responses in **user-uploaded CVs** and **external knowledge sources** using retrieval-augmented generation (RAG).

The project is designed to be used **as a foundation for real applications**, including career coaching tools, HR platforms, and AI assistants.

---

## What This Solves

Most LLM-based career tools generate generic advice because they lack access to user-specific context. CareerSense AI addresses this by:

- Conditioning responses on uploaded CVs  
- Grounding advice using semantic retrieval  
- Separating CV analysis from advisory generation  

This results in **more relevant, structured, and actionable guidance**.

---

## How It Works

### 1. CV Ingestion & Analysis
- Users upload a CV (PDF or text)
- The CV is parsed and analysed by an LLM
- Key information and feedback are extracted in structured form

### 2. Context Retrieval
- Relevant documents are retrieved from a vector database
- Retrieval is based on semantic similarity

### 3. Career Advisory
- Career guidance is generated using:
  - CV-derived insights
  - Retrieved contextual documents

---

## Core Features

### CV Analysis
- PDF and text CV support  
- Structured information extraction  
- Strengths, weaknesses, and improvement suggestions  

### CV-Aware Chatbot
- Interactive advisory interface  
- Retrieval-augmented responses  
- Context-aware recommendations  

### Modular Architecture
- Components reusable in isolation  
- Easy integration into existing systems  
- Swappable LLM backends  

---

## Tech Stack

- **Frontend:** Streamlit  
- **Backend:** Python  
- **LLM Orchestration:** LangChain  
- **LLM Inference:** Ollama (local models)  
- **Vector Store:** LangChain-compatible database  
- **Architecture:** Retrieval-Augmented Generation (RAG)  

---

## Installation

### Prerequisites
- Python 3.9+
- Ollama installed locally

Install Ollama from:
https://ollama.com/download

### Setup
```bash
git clone <repository-url>
cd careersense-ai
pip install -r requirements.txt
