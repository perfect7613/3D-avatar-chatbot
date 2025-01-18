# 3D Avatar Chatbot

A real-time interactive 3D avatar chatbot built with React Three Fiber, powered by Google's Gemini API for natural conversations and ElevenLabs for lifelike text-to-speech.

## 🌟 Features

- Real-time 3D character animation
- Natural language processing with Gemini API
- High-quality text-to-speech with ElevenLabs
- Automated lip-sync using Rhubarb Lip Sync
- Dynamic facial expressions and animations
- Clean, modern UI with Tailwind CSS
- Green screen mode for streaming/recording

## 🛠️ Tech Stack

- **Frontend**:
  - React
  - Three.js
  - React Three Fiber
  - Tailwind CSS
  - Vite

- **Backend**:
  - Node.js
  - Express
  - Gemini API
  - ElevenLabs API
  - Rhubarb Lip Sync

## 🚀 Getting Started

### Prerequisites

1. Install [Rhubarb Lip Sync](https://github.com/DanielSWolf/rhubarb-lip-sync/releases)
2. Get API keys for:
   - Google Gemini
   - ElevenLabs

### Installation

1. Clone the repository
2. Set up the backend:
```sh
cd backend
npm install
# Create .env and add your API keys
npm run dev
```

3. Set up the frontend:
```sh
cd frontend
npm install
npm run dev
```

## 💬 Usage

1. Open `http://localhost:5173` in your browser
2. Type your message in the chat input
3. The 3D avatar will respond with:
   - Voice output
   - Facial expressions
   - Lip-sync animation
   - Body gestures
