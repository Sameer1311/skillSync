# SkillSync – AI-Powered Career Platform

SkillSync helps developers prepare for jobs in one place: build a resume, practise interviews with AI, and test their skills with generated quizzes.

**Live demo:** https://skillsync106.netlify.app

## Features
- **AI resume builder** with a multi-step form, live preview and PDF export
- **AI interview prep** that asks role-specific questions and gives feedback (OpenAI / Gemini)
- **AI quiz generator** for any tech topic
- **Accounts** with sign-up and login (NextAuth, hashed passwords, MongoDB)
- **Dark and light mode**, responsive on mobile

## Tech stack
Next.js (App Router) · React · Tailwind CSS · MongoDB + Mongoose · NextAuth · OpenAI API · Google Gemini · LangChain · Framer Motion

## Project structure
```
app/
  Resume_Builder/        resume form + preview
  Aiprep/                AI interview practice
  api/ai-interview/      interview API route
  api/generate-quiz/     quiz API route
  api/auth/              NextAuth
```

## Run locally
```bash
git clone https://github.com/Sameer1311/skillSync.git
cd skillSync
npm install
# add your MongoDB URI, NextAuth secret and OpenAI / Gemini keys to .env.local
npm run dev
```

## Author
**Sameer Negi** – Full-stack developer · [negisameer.live](https://negisameer.live) · [LinkedIn](https://linkedin.com/in/Sameer1311)
