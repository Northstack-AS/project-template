# Northstack Project Template

This is the official project template for Northstack-AS. It includes pre-configured GitHub Actions for autonomous issue resolution and automated merging to staging.

## Workflows

- **OpenHands Resolver**: Triggered by the `fix-me` label or comments. Resolves issues autonomously using OpenHands and PRs to `staging`.
- **Auto-merge Staging**: Automatically squash-merges PRs targeting the `staging` branch once CI checks (Build, Lint, Typecheck) pass.

## Setup

1. Create a repository using this template.
2. Ensure the `fix-me` label exists.
3. Ensure branch protection rules are set for `staging` to require status checks.
