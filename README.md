# DeepSeek RAGenius 🕵️♂️🧠

*A Localized Retrieval-Augmented Generation System for Intelligent PDF Q&A Using DeepSeek and Ollama*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Python 3.11+](https://img.shields.io/badge/Python-3.11%2B-blue?style=for-the-badge&logo=python)](https://www.python.org/)

![DeepSeek Logo](https://raw.githubusercontent.com/PranayS676/DeepSeek-RAGenius/main/deepseek.webp)

![Demo Screenshot](https://github.com/PranayS676/DeepSeek-RAGenius/blob/main/Screenshot%202025-01-27%20164816.png) 

## 🌟 Overview
An offline RAG system that enables natural language questioning of PDF documents using:
- **DeepSeek's Reasoning Model** for step-by-step answers
- **Ollama** for local LLM execution
- **Streamlit** for intuitive chat interface

Works entirely on your machine - no API keys or cloud dependencies!

## 🚀 Key Features
| Feature | Description |
|---------|-------------|
| 📁 Local Processing | Full data privacy - PDFs never leave your computer |
| 🧠 Deep Reasoning | Answers in DeepSeek's signature analytical style |
| ⚡ Instant Indexing | Automatic document chunking & vectorization |
| 💻 Offline Operation | Zero internet required after setup |
| 🎯 Precision Retrieval | Context-aware document chunk selection |

## 🛠️ Installation

### Prerequisites
- Python 3.11+
- Ollama installed ([Download](https://ollama.ai/))

```bash
# Pull DeepSeek model
ollama pull deepseek-r1:14b

## Setup
### Clone repository:

git clone https://github.com/PranayS676/DeepSeek-RAGenius.git
Install dependencies:
pip install -r requirements.txt
Create PDF directory:
mkdir -p pdf
streamlit run main.py
