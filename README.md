# 🌱 Agri-Genie Pro: AI Diagnostic Center

Agri-Genie Pro aik jadeed Agriculture AI system hai jo kisanon ko unki faslo ki hifazat, beemariyon ki jald tashkhees (diagnosis), aur barwaqt mausam ki ittalat faraham karne ke liye banaya gaya hai. 

This is a **High-Stability production-ready** full-stack AI dashboard optimized for zero-latency telemetry mapping, strict leaf-validation checks, and real-time farmer assistance.

## 🚀 Key Features

* **📸 Computer Vision Diagnostic:** Uses a fine-tuned Vision Transformer (`malifiahm/plant_disease_classification`) with strict leaf-only input validation to accurately detect crop disease boundaries.
* **📈 Visual Confidence Engine:** Tracks model output accuracy with integrated live structural progress bars for unambiguous risk metrics.
* **🧠 Expert Farming Bridge:** Powered by **Groq Cloud API (Llama 3.1)** acting as a Senior Agricultural Officer to provide direct, actionable advice in localized Roman Urdu and Urdu scripts.
* **🌤️ Climate Resilience (Weather Bridge):** Syncs live weather parameters via WeatherAPI to automatically alter and filter AI precautions (e.g., modifying irrigation or chemical spray recommendations based on temperature and sky telemetry).
* **🎙️ Multimodal Input System:** Built-in native voice recorder supporting Urdu voice queries processed instantly through **Groq Whisper-Large-v3** for seamless query generation.
* **⚡ Modern UI Architecture:** Features an upgraded elegant agricultural backdrop theme with balanced layout overlays for maximum field readability without data friction or background interference.

## 🛠️ Tech Stack & Architecture

* **Frontend & Dashboard:** Streamlit (Python)
* **LLM & Orchestration:** Llama 3.1 (8B/70B-Instant) via Groq Cloud API
* **Computer Vision Model:** Plant Disease ViT via Hugging Face Inference API
* **Voice-to-Text:** OpenAI Whisper via Groq Telemetry
* **Data Pipelines:** REST APIs (WeatherAPI)

## 📦 Local Installation & Deployment

### 1. Clone the Repository
```bash
git clone [https://github.com/IqraBatoolAbbas/agri-genie-pro.git](https://github.com/IqraBatoolAbbas/agri-genie-pro.git)
cd agri-genie-pro
