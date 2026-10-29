# Task 4: Version-Controlled DevOps Project with Git

## Objective
To manage a DevOps project using Git and GitHub best practices.

## Tools Used
- Git
- GitHub
- Windows Command Prompt

## Work Completed
- Created a GitHub repository for Task 4.
- Created and used `main`, `dev`, and `feature/add-project-docs` branches.
- Created a `.gitignore` file to exclude temporary files, log files, and environment files.
- Committed changes with a meaningful commit message.
- Pushed branches to GitHub.
- Created and merged Pull Requests.
- Merged the feature branch into `dev` and `dev` into `main`.
- Created and pushed the Git version tag `v1.0.0`.

## Git Workflow
1. Create a feature branch.
2. Make changes and commit them.
3. Push the branch to GitHub.
4. Create a Pull Request.
5. Review and merge changes into `dev`.
6. Merge `dev` into `main`.
7. Create a version tag.

## Useful Git Commands
```bash
git status
git switch -c dev
git switch -c feature/add-project-docs
git add .gitignore
git commit -m "Add gitignore file"
git push -u origin feature/add-project-docs
git tag -a v1.0.0 -m "Task 4 initial release"
git push origin v1.0.0
```

## Conclusion
This task demonstrates basic Git version control, branching, commits, GitHub Pull Requests, merging, `.gitignore`, and version tagging.
