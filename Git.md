# Git

This document outlines various personal Git conventions to help maintain a consistent Git history.

## Git Rules

To maintain manageable repositories, the following rules must be applied:

- Create a new branch for every new feature
- Never push to the `main` or `develop` branch directly, make a pull request instead
- Always work and merge from a feature branch to `develop`
- Only the `develop` branch may be merged to the `main` branch
- Keep commit messages short but descriptive
- Keep commits small whenever possible

### Branch Naming

A git branch should start with a category. Pick one of these: `feature`, `bugfix`, `hotfix` or `test`.

- `feature` is for adding, refactoring or removing a feature
- `bugfix` is for fixing a bug
- `hotfix` is for changing code with a temporary solution and/or without following the usual process (usually because of an emergency)
- `test` is for experimenting outside an issue/ticket

After the category, there should be a `/` followed by the reference of the issue/ticket you are working on. If there's no reference, just add `no-ref`.
After the reference, there should be another `/` followed by a description that sums up the purpose of this specific branch using kebab case.

Below are a few examples:

- `feature/issue-42/create-new-button-component`
- `bugfix/issue-342/button-overlap-form-on-mobile`
- `hotfix/no-ref/registration-form-not-working`
- `test/no-ref/refactor-components-with-atomic-design`

### Pull requests

A pull request should have a descriptive title that reflects the branch category.
It should also include a description with bullet points outlining the most important changes.
Finally, you should assign yourself to the pull request, at a minimum.
