# Contributing Guide

First off, thank you for considering contributing to ["Awesome Q Developer"](https://github.com/cremich/awesome-q-developer). It’s people like you that make a difference. Pull requests are welcome. For major changes, please open an [issue](https://github.com/cremich/awesome-codewhisperer/issues) first to discuss what you would like to change.

## Pull Requests

We use the [GitHub flow](https://guides.github.com/introduction/flow/) as main workflow. In a nutshell:

1. Fork this repository
2. Create a new branch for each feature, fix or improvement
3. Send a pull request from each feature branch to the **main** branch

## Git Commit Guidelines

We have rules over how our git commit messages must be formatted. Please ensure to
[squash](https://help.github.com/articles/about-git-rebase/#commands-available-while-rebasing) unnecessary commits so that your commit history is clean.

All commits SHOULD adhere to the [Conventional Commits specification](https://conventionalcommits.org/). Depending on the type of your change, please choose one of the following to give your commit some more semantic context:

- **feat:** A new piece of content that you want to feature in this awesome list
- **fix:** A bug fix
- **docs:**: Documentation only changes
- **style:** Changes that do not affect the meaning of content (white-space, formatting, missing semi-colons, etc)
- **build:** Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
- **ci:** Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs)
- **chore:** Other changes that don't fit into the other types
- **revert:** Reverts a previous commit

In addition to the specification we use tooling to ensure the proper use.

- [Commitlint](https://commitlint.js.org)
- [Husky](https://typicode.github.io/husky)
