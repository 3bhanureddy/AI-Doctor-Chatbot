# AI Doctor Chatbot 🤖🩺

An AI-powered chatbot that integrates both text and image analysis to deliver comprehensive and personalized medical assistance.

## 🧠 Abstract

This project presents an AI-powered doctor chatbot designed to support users with health-related concerns through both image uploads and natural language queries. Users can submit images (e.g., skin conditions like allergies or pimples) along with symptom-based questions to receive tailored explanations and suggested remedies.

Leveraging the **multimodal capabilities of LLaMA models** (text + vision), the chatbot provides deep, context-aware solutions rather than generic replies.

## 🛠️ Tech Stack

- **Python** – core development
- **FastAPI** – backend web framework
- **Groq API** – AI acceleration
- **LLaMA (multimodal LLMs)** – text & image understanding
- **HTML/CSS** – frontend interface

## 🚀 Features

- 🩺 Text-based symptom input
- 🖼️ Image upload & medical analysis
- 🧠 LLM-based response reasoning
- ⚡ Fast API response via Groq backend
- 🌐 Lightweight frontend

## 📦 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/3bhanureddy/AI-Doctor-Chatbot.git
cd AI-Doctor-Chatbot

# 2. Install dependencies
pip install -r requirements.txt

# 3. Add your Groq API key to a .env file
# .env
# GROQ_API_KEY=your_key_here

# 4. Run the app
uvicorn main:app --reload
