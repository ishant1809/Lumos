# Lumos - AI Companion SaaS

A modern SaaS application that allows users to discover, create, and interact with AI companions tailored for various subjects, topics, and styles. 

## 🌟 Features

- **AI Companions**: Create personalized AI companions to help with specific subjects and topics.
- **Voice Interactions**: Interact with companions using distinct voices (Male/Female) and conversational styles (Formal/Casual).
- **Session Tracking**: Keep track of recently completed sessions with your AI companions.
- **Bookmarks**: Save your favorite companions for quick access.
- **Authentication**: Secure user authentication and session management powered by Clerk.
- **Modern UI**: A beautiful, responsive interface built with Tailwind CSS, Shadcn UI, and Radix UI primitives.

## 🛠️ Tech Stack

- **Framework**: [Next.js 16](https://nextjs.org/) (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS & [shadcn/ui](https://ui.shadcn.com/)
- **Authentication**: [Clerk](https://clerk.dev/)
- **Database / Backend**: [Supabase](https://supabase.com/)
- **AI/Voice Integration**: [Vapi AI](https://vapi.ai/)
- **Forms**: React Hook Form with Zod validation
- **Error Tracking**: Sentry

## 🚀 Getting Started

### Prerequisites

Ensure you have Node.js and npm/yarn/pnpm installed on your machine.

### Installation

1. Clone the repository and install dependencies:

```bash
npm install
```

2. Set up your environment variables. Create a `.env.local` file and add the necessary keys for:
   - Clerk (Authentication)
   - Supabase (Database)
   - Vapi AI (Voice/AI)
   - Sentry (Error tracking)

3. Start the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 📜 Scripts

- `npm run dev`: Starts the development server.
- `npm run build`: Builds the application for production.
- `npm run start`: Starts the production server.
- `npm run lint`: Runs ESLint to catch formatting and linting errors.
