# Agent Engineering Bootcamp

Welcome to my Agent Engineering Bootcamp repository! This repo contains both TypeScript and Python implementations for building AI-powered applications and agents.

## 🚀 Projects Overview

### 📁 TypeScript Project (`ts-bootcamp-project/`)
- **Framework**: Next.js 14 with App Router
- **AI Integration**: Vercel AI SDK with OpenAI
- **UI Components**: Shadcn UI with Tailwind CSS
- **Features**: AI-powered poem generation with streaming responses

### 📁 Python Project (`python-bootcamp-project/`)
- **Package Manager**: uv (fast modern Python package manager)
- **AI Integration**: LiteLLM (unified interface for 100+ LLMs)
- **Features**: Simple AI chat interface with OpenAI integration

## 🛠️ Setup Instructions

### Prerequisites
- Node.js (v18 or higher)
- Python (v3.8 or higher)
- OpenAI API key

### TypeScript/Next.js Setup

1. Navigate to the TypeScript project:
   ```bash
   cd ts-bootcamp-project
   ```

2. Install dependencies:
   ```bash
   pnpm install
   ```

3. Create `.env.local` file:
   ```bash
   OPENAI_API_KEY=your-actual-api-key-here
   ```

4. Run the development server:
   ```bash
   pnpm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

### Python Setup

1. Navigate to the Python project:
   ```bash
   cd python-bootcamp-project
   ```

2. Create `.env` file:
   ```bash
   OPENAI_API_KEY=your-actual-api-key-here
   ```

3. Run the Python script:
   ```bash
   uv run python main.py
   ```

## 🔑 API Key Setup

1. Sign up at [OpenAI Platform](https://platform.openai.com/)
2. Create an API key at [API Keys page](https://platform.openai.com/api-keys)
3. Add the key to both `.env.local` (TypeScript) and `.env` (Python) files
4. **Important**: Never commit your API keys to version control!

## 📚 Technologies Used

### TypeScript Stack
- **Next.js 14**: React framework with App Router
- **AI SDK**: Vercel's AI SDK for streaming AI responses
- **Shadcn UI**: Modern UI component library
- **Tailwind CSS**: Utility-first CSS framework
- **TypeScript**: Type-safe JavaScript

### Python Stack
- **uv**: Fast Python package manager
- **LiteLLM**: Unified LLM interface
- **python-dotenv**: Environment variable management
- **OpenAI**: Direct OpenAI API integration

## 🎯 Features

### TypeScript App Features
- ✨ AI-powered poem generation
- 🔄 Real-time streaming responses
- 🎨 Beautiful UI with dark/light mode
- 📱 Responsive design
- 🔄 Regenerate and hide poem functionality

### Python App Features
- 🤖 Simple AI chat interface
- 🔗 LiteLLM for multiple AI provider support
- 🔧 Easy configuration and setup
- 📝 Clean, readable code structure

## 🚀 Deployment

### TypeScript (Vercel)
1. Connect your GitHub repo to Vercel
2. Add `OPENAI_API_KEY` to Vercel environment variables
3. Deploy automatically on push to main branch

### Python (Multiple Options)
- **Heroku**: Add Procfile and requirements.txt
- **Railway**: Direct deployment from GitHub
- **AWS Lambda**: Serverless deployment
- **Google Cloud**: Cloud Run deployment

## 📖 Learning Resources

- [Next.js Documentation](https://nextjs.org/docs)
- [Vercel AI SDK](https://sdk.vercel.ai/)
- [LiteLLM Documentation](https://docs.litellm.ai/)
- [OpenAI API Reference](https://platform.openai.com/docs/api-reference)

## 🤝 Contributing

This is a personal learning repository for the Agent Engineering Bootcamp. Feel free to fork and experiment with your own implementations!

## 📄 License

This project is for educational purposes as part of the Agent Engineering Bootcamp.

---

**Happy Coding!** 🎉 Built with ❤️ for the Agent Engineering Bootcamp 