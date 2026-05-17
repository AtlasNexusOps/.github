# Contributing to Atlas Nexus

Thanks for contributing! Here's how to get started.

## Before you start

1. **Check existing issues/PRs** — someone may already be working on it
2. **Open an issue first** for feature requests or major changes
3. **Read the repo's README** for project-specific setup

## Development workflow

1. Fork the repository
2. Create a feature branch: `git checkout -b feat/my-feature`
3. Make your changes
4. Run tests if available
5. Commit using conventional commits: `feat:`, `fix:`, `docs:`, `chore:`
6. Push and open a Pull Request against `main`

## PR guidelines

- Keep PRs focused — one feature/fix per PR
- Link related issues with `Closes #N`
- Include a clear description of what changed and why
- Screenshots or demo links for UI changes are appreciated

## Code style

- TypeScript for web/sdk projects
- Solidity 0.8.24+ for smart contracts (Foundry)
- Run `pnpm lint` before committing where available
- Follow existing patterns in the codebase

## AI-assisted contributions

AI-generated PRs are welcome if they:
- Actually compile and pass tests
- Include a human review summary of what was changed
- Don't spam — quality over quantity

## License

By contributing, you agree that your contributions will be licensed under the project's license.
