# 💪 CalixOlympics

AI-powered fitness and nutrition coach with photo-based food analysis, macro tracking, activity logging, voice interaction, and personalized goal recommendations.

Built at **UTRAHacks**.

## ✨ Features

- Photo-based food and nutrition analysis
- Automatic calorie and macro estimation
- Diet and activity tracking
- Personalized AI fitness and nutrition coaching
- Voice interaction and spoken summaries
- Daily calorie, protein, and activity goals
- Optional MongoDB data persistence
- Optional Solana wallet and achievement functionality

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express.js
- **AI:** OpenRouter
- **Voice:** ElevenLabs
- **Database:** MongoDB, LocalStorage
- **Web3:** Solana Web3.js

## 🧠 How It Works

Users can log meals, workouts, and goals manually or through voice. Meal photos can be analyzed using a vision-capable AI model to estimate nutritional information. The AI coach uses the user's current diet, activity, and goals to provide personalized recommendations and summaries.

## 🚀 Getting Started

1. Clone the repository.
2. Install dependencies:

```bash
npm install
```

3. Create a `.env` file using `.env.example` and add the required API keys.
4. Start the server:

```bash
npm start
```

5. Open:

```text
http://localhost:3000
```

## 🔑 Environment Variables

See `.env.example` for configuration options, including:

- `OPENROUTER_API_KEY`
- `ELEVENLABS_API_KEY`
- `MONGODB_URI`
- `SOLANA_RPC_URL`
- `SOLANA_MINT_KEYPAIR`
- `PORT`

## 🏆 Project Context

CalixOlympics was developed at **UTRAHacks** to explore how AI, computer vision, voice interaction, fitness tracking, and Web3 functionality can be combined into an interactive fitness coaching application.
