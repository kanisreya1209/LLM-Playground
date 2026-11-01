# 🚀 LLM Playground – No API Key Required

### An Interactive Platform for Experimenting with Large Language Models

## 📌 Project Overview
LLM Playground is an interactive web application built using Streamlit that allows users to experiment with prompts, compare responses from different Large Language Models (LLMs), and explore AI-powered use cases.

The application uses **Ollama's local API**, allowing users to run AI models locally without requiring an OpenAI API key.

## ✨ Key Features

- **Prompt Studio:** Create, edit, and test custom prompts.
- **Model Comparison:** Compare two local AI models side by side.
- **Temperature Control:** Experiment with response creativity.
- **Token Configuration:** Adjust maximum output tokens.
- **Response Analytics:** View token usage and response time.
- **Five Practical Use Cases:**
  1. Text Summarizer
  2. Professional Email Writer
  3. Code Explainer
  4. Sentiment Analyzer
  5. Interview Coach

## 🛠️ Technologies Used

- Python
- Streamlit
- Ollama
- Requests
- Large Language Models (LLMs)

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/kanisreya1209/LLM-Playground.git
cd LLM-Playground
```

### 2. Install Ollama
Download Ollama from:
https://ollama.com/download

### 3. Download an AI Model
```bash
ollama pull llama3.2
```

Optional second model:
```bash
ollama pull qwen2.5:3b
```

### 4. Install Dependencies
```bash
pip install -r requirements.txt
```

### 5. Run the Application
```bash
streamlit run app.py
```

Open your browser at:
http://localhost:8501

## 🎯 Project Objective

To provide a simple and interactive environment for understanding LLM behavior, testing prompt engineering techniques, comparing model outputs, and exploring practical AI applications.

## 🔒 Privacy & Security

- No OpenAI API key required.
- Models run locally through Ollama.
- Prompts are processed using the configured local model runtime.

## 👩‍💻 Developer

**Kani Sreya Raam Chander**

GitHub: https://github.com/kanisreya1209

## ⭐ Acknowledgement

Developed as part of the Beginner Level Task 2 at Nexlevr.

---

⭐ If you find this project interesting, consider giving this repository a star!
