# 🚀 ResumeCoach AI

ResumeCoach AI is a professional, AI-powered career assistant designed to provide instant, high-quality feedback on resumes. Using advanced Large Language Models (LLM) and Vector Search (RAG), it analyzes your experience and skills to provide actionable career coaching.

![Design Preview](https://i.imgur.com/your-image-placeholder.png) *(Note: Add your own screenshot here after deployment!)*

## ✨ Features

- **Instant Resume Analysis**: Upload a PDF resume and get a comprehensive breakdown of your career trajectory.
- **Interactive AI Coaching**: Ask follow-up questions about your specific resume (e.g., "How can I improve my leadership section?" or "What jobs do I qualify for?").
- **Modern UI/UX**: A stunning, responsive interface featuring glassmorphism, animated gradients, and staggered micro-animations.
- **Privacy First**: Data is processed securely and is not stored permanently.
- **RAG Powered**: Uses Retrieval-Augmented Generation to ensure the AI stays contextually aware of *your* specific resume details.

## 🛠️ Tech Stack

- **Frontend**: HTML5, Tailwind CSS, JavaScript (Vanilla), Outfit Google Fonts.
- **Backend**: Flask (Python).
- **AI/LLM**: Groq (Llama-3.3-70b-versatile).
- **Vector Database**: FAISS (Facebook AI Similarity Search).
- **Embeddings**: HuggingFace Sentence-Transformers.
- **Orchestration**: LangChain.

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- A [Groq Cloud API Key](https://console.groq.com/) (Free)

### Local Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Resume-Coach-AI.git
   cd Resume-Coach-AI
   ```

2. **Create a virtual environment**:
   ```bash
   python -m venv myenv
   source myenv/bin/activate  # On Windows: myenv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Set your Environment Variables**:
   Create a `.env` file or set it in your terminal:
   ```bash
   # Windows (PowerShell)
   $env:GROQ_API_KEY="your_actual_api_key_here"
   ```

5. **Run the app**:
   ```bash
   python app.py
   ```
   Open `http://127.0.0.1:5000` in your browser.

## 🌐 Deployment

This project is optimized for deployment on **Render**.

1. **GitHub**: Push your code to a GitHub repository.
2. **Render**: Create a new Web Service and link your repository.
3. **Configuration**:
   - **Build Command**: `pip install -r requirements.txt`
   - **Start Command**: `gunicorn app:app`
   - **Environment Variable**: Add `GROQ_API_KEY`.

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---
Built with ❤️ by [Your Name]
