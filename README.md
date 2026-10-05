# 🎓 Learnexa

**Learnexa** is an AI-assisted study companion built with modern full-stack technologies.

The project explores how LLMs, document processing, personalized learning workflows and structured study tools can be combined into one learning platform.

## ✨ Current capabilities

The current codebase includes work around:

- AI-assisted chat and explanations
- Document ingestion and conversion workflows
- Quiz generation and submission
- Flashcards and spaced-repetition workflows
- Summarization
- Text-to-speech
- Image generation
- Weakness / learning analytics
- Authentication
- Prisma-backed application data

## 🧰 Tech Stack

- **Next.js 16**
- **React 19**
- **TypeScript**
- **Prisma**
- **NextAuth**
- **AI SDK / Google AI**
- **OpenAI SDK**
- **LangChain**
- **Tailwind CSS**
- **PostgreSQL/Prisma-compatible data layer**

## 🏗️ Architecture

```
User
 │
 ▼
Next.js App Router
 │
 ├── Dashboard / Learning UI
 ├── Authentication
 ├── AI API routes
 │      ├── Chat
 │      ├── Quiz generation
 │      ├── Summarization
 │      ├── Flashcards
 │      ├── TTS
 │      └── Document processing
 │
 ├── LangChain / AI SDK integrations
 │
 └── Prisma
        │
        ▼
     Database
```

## ▶️ Local Development

The main application lives in **GenAI project progress/**.

```bash
cd "GenAI project progress"
npm install
npm run dev
```

Create the required environment variables locally. **Never commit API keys or production credentials.**

## 🔐 Security

The repository intentionally excludes generated build directories, dependency folders, macOS metadata and local database artifacts.

Keep these local:

- `.env` / `.env.*`
- API keys
- OAuth secrets
- Database credentials
- Local development databases

## 📌 Project Status

Learnexa is an evolving project rather than a finished production SaaS. The repository is being developed as a practical exploration of **AI engineering + full-stack application architecture**.

## 🔭 Planned Improvements

- Better evaluation of AI-generated content
- Retrieval-augmented learning workflows
- Stronger observability and error handling
- Automated tests
- Production database/deployment configuration
- More personalized learning analytics
