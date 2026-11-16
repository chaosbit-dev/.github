# Contributing

Thanks for taking an interest. These are small projects maintained in spare time, so a
little coordination up front saves everyone effort.

## Before you start

- **Bugs:** open an issue with steps to reproduce.
- **Features or larger changes:** open an issue first and describe the problem you're
  solving. A PR that arrives without that conversation may be declined, even if it's good.
- **Security issues:** don't open an issue. See [SECURITY.md](SECURITY.md).

## Making a change

1. Fork the repo and branch from `main`.
2. Follow the repo's own README for setup. Most Python projects here use
   [uv](https://docs.astral.sh/uv/): `uv sync`, then `uv run pytest`.
3. Keep the checks green: `ruff check`, `ruff format --check`, `mypy` and the test suite.
4. Add or update tests for the behaviour you change.
5. Use [Conventional Commits](https://www.conventionalcommits.org/) for commit messages
   (`fix:`, `feat:`, `docs:` and so on).
6. Open a PR that explains the *why*, not just the *what*.

## License

By contributing, you agree that your contribution is licensed under the license of the
repository you're contributing to.

## Conduct

Be decent. Participation is covered by our [Code of Conduct](CODE_OF_CONDUCT.md).
