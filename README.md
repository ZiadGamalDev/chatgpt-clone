# ChatGPT Clone – AI Chat App 🤖💬

This is the main guide repository that provides documentation and links to the ChatGPT clone project. The project mimics OpenAI's ChatGPT flow using Next.js (Frontend) and NestJS (Backend) with OpenAI API integration.

![ChatGPT Clone Demo](screenshots/chatbot.png)

## 🔗 Project Repositories

| Repo | Description | Link |
|------|-------------|------|
| **Backend** | NestJS backend that handles OpenAI API requests | [chatgpt-clone-backend](https://github.com/ZiadGamalDev/chatgpt-clone-backend) |
| **Frontend** | Next.js frontend with modern UI for chatting | [chatgpt-clone-frontend](https://github.com/ZiadGamalDev/chatgpt-clone-frontend) |

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

- Frontend: [chatgpt-clone.ziadgamal.com](https://chatgpt-clone.ziadgamal.com/)
- Backend API: [chatgpt-clone-api.ziadgamal.com](https://chatgpt-clone-api.ziadgamal.com/)

## 🛠️ Tech Stack

- **Frontend:** Next.js 15.5.6, React 19, TypeScript, TailwindCSS 4
- **Backend:** NestJS 11, MongoDB, OpenAI SDK

## 🚀 Quick Start

To set up this project locally, you'll need to clone all three repositories:

### Clone All Repositories
```bash
# Main documentation repo (this one)
git clone git@github.com:ZiadGamalDev/chatgpt-clone.git root

# Backend
git clone git@github.com:ZiadGamalDev/chatgpt-clone-backend.git backend

# Frontend
git clone git@github.com:ZiadGamalDev/chatgpt-clone-frontend.git frontend
```

### Backend Setup
```bash
cd backend
npm install

# Create .env file with:
# OPENAI_API_KEY=your_openai_api_key_here
# MONGO_URI=mongodb://localhost:27017/chatgpt-clone
# PORT=3001
# FRONTEND_URL=http://localhost:3000

npm run start:dev  # Runs on http://localhost:3001
```

### Frontend Setup  
```bash
cd frontend
npm install

# Create .env.local file with:
# NEXT_PUBLIC_API_URL=http://localhost:3001

npm run dev  # or npm run start:dev (runs on http://localhost:3000)
```

## 📋 Prerequisites

- Node.js v20 or higher
- MongoDB (local or Atlas)
  - **For local MongoDB:** Make sure MongoDB is running: `brew services start mongodb-community`
- OpenAI API Key

## 📝 Development Notes

This guide repository serves as documentation and project overview. The actual source code is maintained in separate repositories to avoid duplication and maintain clean project structure.

## License

This project is licensed under the MIT License.