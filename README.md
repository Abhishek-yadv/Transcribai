# Transcribai - AI-Powered Social Media Insights 🚀

**Transcribai** is a powerful SaaS tool that transforms lengthy videos from YouTube, Instagram, LinkedIn, and TikTok into concise, actionable insights using AI.

![Transcribai Demo](https://via.placeholder.com/800x400?text=Transcribai+Interface+Preview)

## ✨ Features

- **Multi-Platform Support**: Fetch transcripts from YouTube, Instagram, LinkedIn, and TikTok.
- **AI-Powered Insights**: Uses Groq (Llama 3 70B) to extract key takeaways and summaries.
- **Premium UI**: Stunning dark-mode interface built with Next.js, Framer Motion, and Tailwind CSS.
- **One-Click Downloads**: Export insights as professionally styled PDFs or shareable Images.
- **Dynamic Adaptation**: The interface adapts its colors and icons based on the selected platform.

## 🛠️ Tech Stack

### Frontend
- **Next.js 15** (App Router)
- **TypeScript**
- **Tailwind CSS v4** + **Framer Motion**
- **Lucide React** (Icons)

### Backend
- **FastAPI** (Python)
- **LangChain + Groq** (AI Logic)
- **YouTube Transcript API**
- **xhtml2pdf** & **PyMuPDF** (PDF/Image Generation)

## 🚀 Getting Started

### Prerequisites
- Node.js & npm
- Python 3.9+
- Groq API Key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/USER/Transcribai.git
   cd Transcribai
   ```

2. **Backend Setup**
   ```bash
   cd backend
   pip install -r requirements.txt
   uvicorn main:app --reload
   # Backend runs on http://localhost:8000
   ```

3. **Frontend Setup**
   ```bash
   cd frontend
   npm install
   npm run dev
   # Frontend runs on http://localhost:3000
   ```

4. **Environment Variables**
   - Create a `.env` in `backend/` and add:
     ```env
     GROQ_API_KEY=your_groq_api_key_here
     ```

## 📝 API Endpoints

- `POST /api/transcript` - Fetch transcript from URL
- `POST /api/generate` - Generate insights from transcript
- `POST /api/download` - Download insight as PDF/Image

## 🤝 Contributing

Contributions are welcome! Please fork the repo and submit a PR.

## 📄 License

MIT License © 2026 Transcribai
