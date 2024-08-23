# Contributing to Celsira

Thank you for your interest in contributing to Celsira. To ensure a smooth contribution process and maintain the quality of our codebase, we have established specific guidelines, particularly for commit messages and versioning.

## Semantic Release and Commit Message Guidelines

We use semantic release for automated version management and changelog generation. This requires commit messages to adhere to a specific format, enabling the automatic determination of version numbers and the generation of meaningful changelogs.

### Commit Message Format

Every commit message should be structured as follows:

1. **Type**: This describes the nature of the change. Common types include:

- `feat` (new feature)
- `fix` (bug fix)
- `docs` (changes in documentation)
- `style` (formatting, missing semicolons, etc.; no code change)
- `refactor` (refactoring production code)
- `test` (adding tests, refactoring tests; no production code change)
- `chore` (updating build tasks, package manager configs, etc.; no production code change)
- `...` (in some repositories, there may be additional types)

2. **Scope** (optional): This refers to the part of the codebase affected by the change:

This could be anything specifying the place of the commit change. For example, `auth`, `users`, `permissions`, `roles`, `admin`, `frontend`, `backend`, etc. based on the project structure and repository.

3. **Subject**: A brief description of the change, in the imperative mood.

4. **Body** (optional): A more detailed explanation of the changes. This is where you should explain the reasoning behind the changes if necessary.

5. **Footer** (optional): This should contain any information about Breaking Changes and is also the place to reference GitHub issues that this commit closes.

Example:
```bash
feat(auth): add user authentication

- Add user authentication using JWT
- Implement user registration and login
- Add user profile management

Closes #123
```
