# Welcome

Thank you for being interested in contributing to this project. Please read the following information before working on any changes.

Ensure you have read the [Code of Conduct](CODE_OF_CONDUCT.md) before committing, as it outlines responsibilities and how we expect your behavior to be while working with us on this project.

## Style Guide

We follow a strict style guide to help our code be manageable and easy to understand to begin work on

- Comments can be used locally, but please remove them before committing
  
- Your code should lint and pass typescript correctly. You can use `as any` and `// @ts-expect-error`, however please do not use `// @ts-ignore` as it suppresses all errors, even when the code will not throw an error

- You should not commit any local files (including but not limited to: `.env`, `./dist`, `./node_modules`, `./vscode`), if you commit these files, your PR is subject to being closed

- Where possible, please make typechecking as strict as possible
  
## Committing

If you notice an issue, create a new issue, and *state in the description that you are working on a PR that resolves it*. If you do not wish to create a PR resolving it, rather wanting to notify other maintainers of the project that there is an issue, please ignore that instruction, and a maintainer can create a PR.

We follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) standard, with a few changes:

- Bug: Fixing a known issue, without adding extra features
- Feat: Adding a feature
- Chore: Non code changes (ci, build, other misc files)
- Refactor: Code changes which neither add features nor fix bugs
- Style: Changing code styles
  
When adjusting the scope, if multiple files are changed, feel free to leave it, otherwise set the scope to be the primary file changed

## Creating a Pull Request

Once your changes are made, create a Pull Request. Make sure to link it to an issue if applicable, and allow maintainer edits to ensure the branch is mergeable.

Your Pull Request is going to require a review from a [Codeowner](CODEOWNERS). When we make changes or comments, apply them directly through the UI. Ensure you mark conversations as resolved, allowing with commenting which commit resolved each conversation in the thread.

## Preparing your development environment

Please review the Wiki to prepare your development environment
