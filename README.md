# 🌱 Agri-Genie Pro: AI Diagnostic Center

Agri-Genie Pro aik jadeed Agriculture AI system hai jo kisanon ko unki faslo ki hifazat, beemariyon ki jald tashkhees (diagnosis), aur barwaqt mausam ki ittalat faraham karne ke liye banaya gaya hai. 

This is a **Zero-Blink production-ready** full-stack AI dashboard optimized for high-performance telemetry mapping and real-time farmer assistance.

## 🚀 Key Features

* **📸 Computer Vision Diagnostic:** Uses a fine-tuned Vision Transformer (`malifiahm/plant_disease_classification`) to detect crop leaves diseases with high confidence scores.
* **🧠 RAG (Retrieval-Augmented Generation):** Local context searching using **FAISS** vector database and Sentence Transformers to pull precise agricultural treatment guidelines.
* **🌤️ Climate Resilience (Weather Bridge):** Syncs live weather parameters via WeatherAPI to automatically alter and filter AI precautions (e.g., stopping chemical spray recommendations during rain telemetry).
* **🎙️ Multimodal Inputs:** Built-in native voice recorder supporting Urdu voice queries processed instantly through **Groq Whisper-Large-v3**.
* **🔊 Client-Side Speech Synthesis:** Seamless multilingual voice support leveraging the HTML5 Web Speech API to bypass cloud rate limits (`429 Errors`).
* **⚡ Modern UI Architecture:** Implemented Streamlit `@st.fragment` rendering states to ensure absolute zero-page blinking and seamless state preservation.

## 🛠️ Tech Stack & Architecture

* **Frontend & Dashboard:** Streamlit (Python)
* **LLM & Orchestration:** Llama 3.1 (8B/70B) via Groq Cloud API
* **Vector Database:** FAISS (Facebook AI Similarity Search)
* **Embeddings Model:** `sentence-transformers/all-MiniLM-L6-v2`
* **Voice-to-Text:** OpenAI Whisper via Groq Telemetry
* **Data Pipelines:** REST APIs (WeatherAPI)

## 📦 Local Installation & Deployment

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/agri-genie-pro.git](https://github.com/IqraBatoolAbbas/agri-genie-pro.git)
   cd agri-genie-pro
