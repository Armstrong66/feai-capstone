# CLAUDE.md

Guidance for Claude Code (or any AI assistant) working in this repository.

## Stack
- Framework: [e.g. Nodejs + React 18 + Vite]
- Language: [e.g. TypeScript, strict mode]
- Styling: [e.g. Tailwind CSS]
- Package manager: [npm / pnpm / yarn]

## Conventions
- Commit messages follow Conventional Commits (feat, fix, docs, chore, refactor, test, etc.)
- Use functional components and hooks (no class components)
- Prefer named exports over default exports
- Run `npm run lint` and `npm test` before committing
- Keep components in `src/components/`, one component per file

## What the assistant should do
- Ask before adding new dependencies
- Explain non-trivial changes before applying them
- Flag any accessibility issues in UI code