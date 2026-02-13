# Branching and Repository Conventions

## Branch Model
- **main**: The production-ready branch. All stable, tested, and reviewed code is merged into this branch.
- **develop**: The development branch. All feature work is merged into this branch before being merged into `main`.
- **feature/* branches**: Feature branches should be created for each new feature or task. After work is completed, it should be merged into `develop`.

## Pull Request Guidelines
- All changes should be made via pull requests (PRs).
- A **review** is required before merging to ensure code quality.
- **Code owners** may be assigned to review certain parts of the codebase.
- **Status checks** should be run before merging to ensure no errors are present.

## Merging
- Merges into `develop` should always be done via PR.
- Merges into `main` should only occur once a PR is fully reviewed and approved.
