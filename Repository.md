# Repository

This document outlines a personal standard for organizing a new repository.
A template repository may be used instead in the future.

## License

Each repository should include an MIT License in a file named LICENSE.

## Details

The Details section should include a brief description of the application and list topics such as the coding language and framework.
The Packages and Deployments sections should be disabled for each repository.

## Settings

Various settings should be changed for each new repository.

### General -> Features

Wikis and Projects should be disabled unless they are actively used.

### General -> Pull Requests

Only squash merging should be enabled. Additionally, the default commit message should be set to the pull request title only.

### Branches

The repository should include both a `main` branch and a `develop` branch. For each branch, the following default settings should be adjusted:

- Require a pull request before merging should be enabled, while require approvals should be disabled
- Require status checks to pass before merging, along with require branches to be up to date before merging, should be enabled

## README

The README of the repository should have the following elements:

- It should start with the name of the repository
- It should contain a features chapter
- It should contain a requirements chapter
- It should contain a recommended IDE setup chapter with highly recommended extensions
- It should contain a chapter with useful documentation and links
- It should contain a installation chapter
- It should contain a chapter with development information
- It should contain a chapter with deployment information
- It may contain a chapter with useful commands and debugging information
