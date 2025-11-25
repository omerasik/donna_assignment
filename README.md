## Project Summary
Donna is a chat assistant that answers meeting questions, surfaces upcoming meetings, and walks you through logging meeting notes. Built with React Router v7 (Framework Mode) and Server-Sent Events for streaming replies.

## How to Run the App
```bash
npm install
npm run dev
```
This project uses Vite and React Router v7 Framework Mode.

## How to Add an API Key (Gemini or OpenAI)
Create a `.env` file in the project root and add:
```
GEMINI_API_KEY=your_key_here
OPENAI_API_KEY=your_key_here
AI_PROVIDER=gemini | openai | none
```
If no key is provided, Donna automatically falls back to the built-in rule-based logic.

## Folder Structure
```
.
├── app
│   ├── components
│   ├── lib
│   ├── routes
│   └── styles
├── .env.example
├── react-router.config.ts
├── tsconfig.json
└── vite.config.ts
```

## Author

Omer Asik
