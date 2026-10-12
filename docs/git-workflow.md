Git Workflow Documentation

1. Repository Initialization

The project is initialized using git init -b main.

2. Branching

main stores the stable version.

dev integrates development changes.

feature/readme contains README improvements.

3. Commit Workflow

Use git add to stage changes and git commit to save them in the repository history.

4. Remote Repository

The local repository is connected to GitHub using git remote add origin.

5. Pull Requests

Changes are proposed through pull requests and reviewed before merging into the target branch.

6. Git Ignore

The .gitignore file excludes selected temporary files, environment files, and credentials.

7. Git Tags

A version tag such as v1.0.0 identifies a project release.

8. Verification

Use git status, git log --oneline --graph --all, and git branch -a to inspect the repository.
