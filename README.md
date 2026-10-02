# Frontend AI Capstone

A starter repository for a frontend-focused AI capstone project that combines modern web UI patterns with practical AI integration.

## Overview

This project is intended to serve as the foundation for a polished, production-minded application that uses AI to improve user experience, automate tasks, or generate meaningful content in the browser.

## Stack

- React
- TypeScript
- Vite
- Tailwind CSS
- Node.js or serverless API layer for AI calls
- OpenAI / Gemini / Anthropic-compatible APIs
- ESLint + Prettier
- Vitest + React Testing Library

## Goals

- Build a clean, user-centered frontend experience
- Integrate AI capabilities in a thoughtful and accessible way
- Keep the codebase maintainable, testable, and extensible
- Demonstrate real-world engineering decisions for a capstone project

## Project Structure

```text
frontend-ai-capstone/
├── README.md
├── LICENSE
├── .gitignore
├── CLAUDE.md
├── src/
│   ├── app/
│   ├── components/
│   ├── features/
│   ├── lib/
│   ├── services/
│   └── styles/
├── public/
├── tests/
├── package.json
├── vite.config.ts
├── tsconfig.json
└── tailwind.config.js
```

## Getting Started

```bash
npm install
npm run dev
```

## Available Scripts

```bash
npm run dev      # start the local development server
npm run build    # create a production build
npm run preview  # preview the production build
npm run test     # run the test suite
npm run lint     # run ESLint
npm run format   # format code with Prettier
```

## Conventions

- Use TypeScript for all application logic.
- Prefer small, reusable components over large monolithic views.
- Keep business logic separate from UI concerns.
- Validate API and UI behavior with tests.
- Avoid committing secrets or API keys to the repo.
- Follow accessible, responsive design patterns.

## Notes

This repository is intentionally scaffolded as a starting point. The implementation details and final project direction can evolve as the capstone develops.
