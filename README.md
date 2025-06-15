# ChatGPT Clone – AI Chat App 🤖💬

This is the main root repo that links both frontend and backend of the ChatGPT clone. It mimics OpenAI's ChatGPT flow using Next.js (Frontend) and NestJS (Backend) with OpenAI API integration.

![ChatGPT Clone Demo](screenshots/chatbot.png)

## 🔗 Sub-Repos

| Repo | Description |
|------|-------------|
| [chatgpt-clone-backend](https://github.com/ZiadGamalDev/chatgpt-clone-backend) | NestJS backend that handles OpenAI API requests |
| [chatgpt-clone-frontend](https://github.com/ZiadGamalDev/chatgpt-clone-frontend) | Next.js frontend with modern UI for chatting |

## 🧠 Features

- Chat interface for AI conversations
- User input chat box (no login needed)
- Backend powered by NestJS
- Frontend built with Next.js for server-side rendering
- Sends real-time requests to OpenAI's GPT
- Displays AI responses smoothly
- Serverless-friendly frontend deployment
- API integration for AI responses

## 🚀 Deployed Links

- Frontend: [chatgpt-clone-frontend](https://chatgpt-clone-frontend-alpha.vercel.app/)
- Backend: [chatgpt-clone-backend](https://chatgpt-clone-backend-production.up.railway.app/)

## 🛠️ Tech Stack

- **Frontend:** Next.js 14, TypeScript, TailwindCSS
- **Backend:** NestJS, OpenAI SDK

## Installation

1. Clone the repository:
  ```bash
  git clone https://github.com/ZiadGamalDev/chatgpt-clone.git
  cd chatgpt-clone
  ```

2. Navigate to the backend directory and install dependencies:
  ```bash
  cd chatgpt-clone-backend
  npm install
  ```

3. Navigate to the frontend directory and install dependencies:
  ```bash
  cd ../chatgpt-clone-frontend
  npm install
  ```

4. Start the development server:
  ```bash
  npm run dev
  ```

## Usage

- Open your browser and navigate to `http://localhost:3000`.
- Start chatting with the AI!

## License

This project is licensed under the MIT License.