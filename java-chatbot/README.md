# Java Chatbot Frontend

Frontend-only React app for a Java-specific chatbot UI. It sends requests directly from the browser to the RapidAPI endpoint and uses a strict system prompt so the model behaves like a Java-only assistant.

## Setup

Create a `.env` file in the project root:

```env
VITE_RAPIDAPI_ENDPOINT=https://open-ai21.p.rapidapi.com/conversationllama
VITE_RAPIDAPI_HOST=open-ai21.p.rapidapi.com
VITE_RAPIDAPI_KEY=your_rapidapi_key_here
```

Install and run:

```bash
npm install
npm run dev
```

## Features

- Java-only assistant mode
- Java debugging mode
- Java mock interview mode
- Browser voice input
- Optional spoken replies
- No backend required

## Important Note

This setup is frontend-only. The API key is exposed to the browser at runtime/build time, so it is suitable for local use or personal demos, not secure production deployment.
