# Contributing

Thank you for your interest in contributing to i9va projects. This guide applies to all repositories under this organization.

## Getting Started

1. Fork the repository and create your branch from `main`.
2. Follow the repository's setup instructions in its own `README.md`.
3. Make your changes following the conventions below.
4. Open a pull request.

## Branch Naming

Use a short, descriptive name prefixed by type:

```
feat/add-payment-integration
fix/null-pointer-on-checkout
chore/upgrade-go-1.22
docs/update-api-reference
```

## Commits

We follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).

**Format:** `<type>(<optional scope>): <description>`

| Type       | When to use                                      |
|------------|--------------------------------------------------|
| `feat`     | A new feature                                    |
| `fix`      | A bug fix                                        |
| `docs`     | Documentation changes only                       |
| `refactor` | Code change that neither fixes a bug nor adds a feature |
| `test`     | Adding or updating tests                         |
| `chore`    | Build process, tooling, or dependency updates    |
| `perf`     | Performance improvement                          |
| `ci`       | CI/CD configuration changes                      |

**Examples:**
```
feat(auth): add OAuth2 login with Google
fix(api): handle empty response from upstream service
chore: upgrade Next.js to 14.2
```

Breaking changes must include a `BREAKING CHANGE:` footer or a `!` after the type:
```
feat!: remove deprecated v1 endpoints
```

## Pull Requests

- PRs must target `main`.
- At least **1 approval** is required before merging.
- We use **squash merge** — your commit history will be squashed into a single commit on `main`.
- The PR title must follow Conventional Commits format (it becomes the squash commit message).
- Keep PRs focused. One concern per PR whenever possible.
- Fill out the PR template completely.

## Code Review

- Reviewers should respond within 2 business days.
- Address all comments before requesting a re-review.
- Prefer resolving discussions in the PR thread so context is preserved.

## Reporting Issues

Use the appropriate issue template:
- **Bug Report** — for unexpected behavior or errors.
- **Feature Request** — for new ideas or improvements.

## Code of Conduct

All contributors are expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md).
