# CLAUDE.md

## Project overview

This repository is the capstone project for a frontend-focused AI application. The goal is to build a polished, usable product that demonstrates modern frontend engineering and practical AI integration.

## Stack

- React + TypeScript
- Vite for local development and production builds
- Tailwind CSS for styling
- Node.js or serverless endpoints for AI API access
- OpenAI, Gemini, or Anthropic-compatible APIs
- ESLint, Prettier, and TypeScript strict mode
- Vitest + React Testing Library for validation

## Core conventions

- Prefer functional React components and hooks.
- Keep components small, readable, and reusable.
- Use TypeScript strictly; avoid `any` unless there is a clear, documented reason.
- Co-locate feature logic when it improves clarity, but avoid over-fragmenting the codebase.
- Keep UI and API concerns separated; do not expose secrets in client code.
- Favor accessible markup, responsive layouts, and keyboard-friendly interactions.
- Use clear, descriptive naming for files, folders, and variables.
- Add tests for meaningful behavior, especially UI flows and API integrations.

## Workflow expectations

- Run the app locally with `npm install` and `npm run dev`.
- Validate before merging with linting and test checks.
- Keep commit messages specific and readable.
- Document env vars and configuration in the README or `.env.example`.
- Treat performance, accessibility, and maintainability as first-class requirements.

## File organization

- `src/components/`: reusable UI building blocks
- `src/features/`: domain-specific features or screens
- `src/lib/`: shared utilities and helpers
- `src/services/`: API and AI integration logic
- `src/styles/`: shared styles and theme configuration
- `tests/`: integration and component tests

## Quality bar

Every significant update should be easy to understand, easy to test, and consistent with the project’s frontend and AI product goals.
