# AI Resume Assistant

A chat-based AI agent that:
- Generates tailored cover letters
- Suggests resume optimizations
- Prepares interview Q&A from a job description

## 🚀 Getting Started

### Backend
```bash
cd backend
npm install
cp .env.example .env   # Add your OPENAI_API_KEY
node server.js
```

### Frontend
```bash
cd frontend
npm install
npm run dev
```

Visit `http://localhost:5173`.

## 🔐 Environment Variables
In `backend/.env`:
```
OPENAI_API_KEY=your_api_key_here
```

## Deployment
- Host backend on **Render / Railway / Vercel Functions**.
- Host frontend on **Vercel / Netlify**.
- Point frontend API calls to your backend’s URL.
