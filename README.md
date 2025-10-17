# MockMate

A lightweight, AI-powered mock interview application built with Next.js, Firebase, Tailwind CSS and Vapi voice agents. Designed for quick setup and iterative development so you can run realistic interview sessions and receive AI-driven feedback.

## Key features

- Email/password authentication (Firebase)
- Generate role-based interview questions (Google Generative AI)
- Voice-driven interview sessions via Vapi workflows
- AI feedback with scores and per-topic breakdowns
- Responsive UI using Tailwind CSS

## Quickstart

1. Install dependencies

```bash
npm install
```

2. Create environment file

Copy `.env.local.example` to `.env.local` (or create `.env.local`) and set the variables:

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

3. Run the app (development)

```bash
npm run dev
```

Open http://localhost:3000

## Scripts

- `npm run dev` — start development server
- `npm run build` — build for production
- `npm run start` — start production server
- `npm run lint` — run linter

## Recommended workflow

- Keep secrets out of source control — use `.env.local` and CI secrets for production.
- Use Firebase service account variables for server-side operations.
- Test voice workflows in Vapi dashboard before connecting to the frontend token.

## Tech stack

Next.js · Firebase · Tailwind CSS · Vapi · Zod · Google Generative AI

## Contributing

- Fork the repo, create a branch, and open a PR.
- Keep changes focused and include tests where applicable.
- Run `npm run lint` and verify the app runs locally before submitting.

## License

Specify a license (e.g., MIT) in `LICENSE` if you plan to open source this project.
