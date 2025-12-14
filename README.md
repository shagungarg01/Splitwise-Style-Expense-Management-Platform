Splitwise-Style Expense Management Platform

Full-Stack Web Application

A production-ready, full-stack expense management platform inspired by Splitwise, designed to demonstrate real-world backend architecture, asynchronous workflows, and AI integration using modern web technologies.

This project showcases my ability to design, build, and deploy scalable systems with clean separation of concerns, background processing, and cloud deployment.

**Architecture Overview**

Client (Next.js)
      ↓
Convex Backend (Queries, Mutations, Actions)
      ↓
Inngest (Background Jobs & Cron)
      ↓
Gemini AI + Email Service

**Project Structure**
.
├── app/                 # Next.js App Router
├── convex/              # Backend schema & functions
├── lib/
│   └── inngest/         # Background workflows
├── public/
├── styles/
└── README.md

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
