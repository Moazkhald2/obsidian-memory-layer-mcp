# Contributing to Obsidian Memory Layer MCP

Thanks for your interest! This is a small project, so contributions are welcome.

## Getting Started

1. Fork the repo
2. Clone your fork
3. `npm install`
4. `npm run build` — verify it compiles
5. Test the server: `node dist/index.js /path/to/obsidian/vault`

## Development

- The server entry is `src/index.ts` — MCP tool definitions
- Storage logic is `src/vault.ts` — markdown file operations
- Follow the existing code style (single quotes, 2-space indent, trailing commas)
- Keep files focused and under 300 lines where possible

## Pull Request Process

1. Run `npm run lint` before committing — fix any issues
2. Update `CHANGELOG.md` with your change under the `[Unreleased]` section
3. Fill out the pull request template completely
4. Keep PRs small and focused (one change per PR)

## Reporting Issues

Use the [Bug Report template](.github/ISSUE_TEMPLATE/bug_report.md) and include:
- What you did
- What happened
- What you expected
- Your environment (OS, Node version, AI client)

## Code Style

- TypeScript with strict types
- No `any` unless absolutely necessary
- Async/await over callbacks
- Descriptive variable names — avoid abbreviations
