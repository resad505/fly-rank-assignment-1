# Claude Code project guidance

## Project context

FlyRank Assignment 1 is a Node.js/TypeScript capstone project. Keep the
repository ready for incremental implementation and AI-assisted development.

## Technical conventions

- Use TypeScript with strict mode enabled.
- Use npm for dependency management and scripts.
- Prefer small, composable modules with explicit types.
- Keep environment-specific values in environment variables; never commit
  secrets.
- Add or update tests when behavior changes.

## Git conventions

- Use Conventional Commits: `type(scope): description`.
- Keep commits focused and use imperative descriptions.
- Do not commit generated output, dependencies, logs, or local environment
  files.

## Change workflow

1. Inspect existing patterns before adding new code.
2. Make the smallest complete change.
3. Run the relevant tests, type checks, and lint checks.
4. Update the README when setup or user-facing behavior changes.
