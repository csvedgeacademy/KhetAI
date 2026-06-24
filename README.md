# 🌾 KhetAI — Precision Agriculture for Maharashtra Farmers

AI-powered farm management dashboard for Vidarbha farmers. Built with React + Claude AI.

## Features

- **🏡 Dashboard** — Farm overview, crop health, weather, alerts
- **🔬 Crop Doctor** — AI disease diagnosis from symptom description
- **🤖 Khet Mitra** — AI chat advisor (Marathi, Hindi, English)
- **🌾 My Farm** — Farm map, soil health, upcoming activities
- **🌤 Weather** — 7-day forecast + smart spray advisory
- **📊 Analytics** — Yield history, P&L, cost breakdown

## Quick Start

### 1. Clone the repo
```bash
git clone https://github.com/YOUR_USERNAME/khetai.git
cd khetai
```

### 2. Install dependencies
```bash
npm install
```

### 3. Add your API key
```bash
cp .env.example .env
# Edit .env and add your Anthropic API key
# Get one free at: https://console.anthropic.com/
```

### 4. Run locally
```bash
npm start
# Opens at http://localhost:3000
```

## Deploy to Vercel (Recommended — Free)

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → Import project
3. Add environment variable: `REACT_APP_ANTHROPIC_API_KEY` = your key
4. Click Deploy → get your live URL in 2 minutes!

## Tech Stack

- React 18
- Recharts (charts)
- Claude claude-sonnet-4-6 (AI features)
- Deployed on Vercel

## ⚠️ Important

- Never commit your `.env` file — it's in `.gitignore`
- The AI features (Crop Doctor & Khet Mitra) require an Anthropic API key
- Dashboard, Weather, Farm Map, and Analytics work without a key

---

Built for farmers of Vidarbha, Maharashtra 🇮🇳
