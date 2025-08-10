# 🧠 Mental Health Therapist Chatbot

An **AI-powered conversational assistant** designed to provide mental health support, active listening, and wellness resources.  
This project combines **Natural Language Processing (NLP)**, **sentiment analysis**, and **context-aware conversation flow** to create an empathetic chatbot experience.

---

## 📌 Features

- **24/7 Mental Health Support** – Always available for users in need.
- **Sentiment & Tone Analysis** – Detects user mood and adapts responses accordingly.
- **Context-Aware Conversations** – Remembers recent messages for coherent replies.
- **Resource Suggestions** – Recommends relevant exercises, helplines, and self-care tips.
- **Crisis Detection** – Identifies urgent cases and provides helpline information.
- **Multi-Platform Support** – Can be integrated into web, mobile, or messaging apps.

---

## 🏗️ Architecture


flowchart TD
    A[User Input] --> B[Frontend UI]
    B --> C[API Gateway]
    C --> D[NLU Module - NLP Model]
    D --> E[Sentiment & Tone Analysis]
    E --> F[Response Generator]
    F --> G[Resource & Crisis Management Module]
    G --> H[Frontend UI]


## ⚙️ Tech Stack

Frontend:
React.js / HTML / CSS / JavaScript
Tailwind CSS for styling

Backend:
Node.js + Express.js
REST API endpoints for message handling

AI/NLP:
OpenAI GPT API (or alternative NLP models)
Sentiment Analysis (VADER/TextBlob/Custom ML model)

Database:
MongoDB (storing conversation history & user data)

Other Tools:
Axios for API calls
dotenv for environment variables
Helmet & CORS for security
