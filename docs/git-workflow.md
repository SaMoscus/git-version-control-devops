# Git Workflow Documentation

## 1. Repository Initialization

Initialize the project using:

git init

## 2. Branching Strategy

- main: Production-ready code.
- dev: Development and testing.
- feature/*: New features.

## 3. Feature Development

Create a feature branch:

git checkout -b feature/project-documentation

## 4. Commit Changes

Stage changes:

git add .

Commit changes:

git commit -m "Add project documentation"

## 5. Push Changes

git push -u origin feature/project-documentation

## 6. Pull Requests

Create a Pull Request from the feature branch
into the dev branch.

After reviewing and merging, create another
Pull Request from dev into main.

## 7. Version Management

Use Git tags to identify project releases.

Example:

git tag -a v1.0.0 -m "First release"
