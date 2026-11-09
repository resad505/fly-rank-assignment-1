# FlyRank Assignment 1

Starter repository for the FlyRank capstone project and its
AI-assisted development workflow.

## Current status

This repository currently contains the project documentation and development
conventions. Application code, package metadata, and automated checks will be
added in subsequent implementation phases.

## Technology

- Node.js 22 LTS
- TypeScript
- npm
- Git and GitHub

## Getting started

### Prerequisites

Install the following tools:

- [Node.js 22 LTS](https://nodejs.org/)
- [Git](https://git-scm.com/)

### Clone the repository

```bash
git clone https://github.com/resad505/fly-rank-assignment-1.git
cd fly-rank-assignment-1
```

Once the application manifest is added, install dependencies with:

```bash
npm install
```

The available build, test, and lint commands will be documented here as the
application is implemented.

## Repository structure

```text
.
├── .gitignore
├── CLAUDE.md
├── LICENSE
└── readme.md
```

See [`CLAUDE.md`](CLAUDE.md) for project-specific development guidance.

## Development conventions

- Use TypeScript with strict type checking.
- Keep environment-specific values in environment variables.
- Never commit secrets, dependencies, generated output, or local environment
  files.
- Prefer small, composable modules with explicit types.
- Add or update tests when behavior changes.
- Use [Conventional Commits](https://www.conventionalcommits.org/), such as
  `feat: add search endpoint`.
- Run the relevant tests, type checks, and lint checks before opening a pull
  request.

## License

This project is distributed under the license in [`LICENSE`](LICENSE).