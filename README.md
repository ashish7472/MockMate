# MockMate

A simple AI-powered mock interview app built with Next.js, Firebase, Tailwind CSS, and Vapi voice agents.

## Features

- Email/password auth (Firebase)
- Generate interview questions (Gemini)
- Voice interview via Vapi workflow
- AI feedback with scores and breakdown

## Setup

1. Install

```bash
npm install
```

2. Environment (.env.local)

```env
NEXT_PUBLIC_VAPI_WEB_TOKEN=
NEXT_PUBLIC_VAPI_WORKFLOW_ID=

GOOGLE_GENERATIVE_AI_API_KEY=

NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
NEXT_PUBLIC_FIREBASE_PROJECT_ID=
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=
NEXT_PUBLIC_FIREBASE_APP_ID=

FIREBASE_PROJECT_ID=
FIREBASE_CLIENT_EMAIL=
FIREBASE_PRIVATE_KEY=
```

3. Run

```bash
npm run dev
```

Open http://localhost:3000

## Scripts

- `npm run dev` – start dev server
- `npm run build` – build
- `npm run start` – production
- `npm run lint` – lint

## Tech

Next.js · Firebase · Tailwind CSS · Vapi · Zod
