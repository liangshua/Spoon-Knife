
# GitHub Fork Collaboration Practice

This document introduces the basic GitHub collaboration workflow.

## Workflow
Fork -> Clone -> Branch -> Commit -> Push -> Pull Request -> Review -> Merge

## Remote Repositories

### origin
- origin refers to my personal fork on GitHub.
- I use origin to push my local branches and commits.
- Example: `git push origin feature-fork-review`

### upstream
- upstream refers to the original repository maintained by the project owner.
- I use upstream to fetch updates from the original project.
- Example: `git fetch upstream`

### Key Difference
- origin is my personal remote repository.
- upstream is the original remote repository.
- Fetching from upstream does not automatically merge changes into my local branch.
