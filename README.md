# Project Template

This template provides a foundation for projects. It includes a boilerplate Nix flake that is easy to extend to your liking.

## Features

- Extendable and declarative Nix flake.
- Manage pre-commit hooks using [pre-commit](https://pre-commit.com/).
- Create meaningful commit messages following the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification.

## Getting Started

1. Press 'Use this template' and create a new repository.
2. Clone your repository and navigate to it.
3. Run `nix develop` or `direnv allow` to activate the development environment.
4. Run `nix flake check` to check codebase using pre-commit.
5. Run `nix build` to build default application to `result`.

## Read More

- [pre-commit](https://pre-commit.com/).
- [git-hooks.nix](https://github.com/cachix/git-hooks.nix).
    - Check out the [available pre-commit hooks](https://devenv.sh/?q=pre-commit.hooks).
- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).
