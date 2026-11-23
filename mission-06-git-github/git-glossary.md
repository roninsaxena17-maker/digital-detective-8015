# Git Command Glossary

| Git operation | Command | Explanation |
|---|---|---|
| Initialise a repository | `git init` | Creates a new Git repository in the current folder. |
| Check status | `git status` | Shows which files are modified, staged or untracked. |
| Stage changes | `git add filename` | Selects changes to include in the next commit. |
| Commit changes | `git commit -m "message"` | Saves staged changes as a checkpoint in the repository history. |
| View history | `git log --oneline` | Displays previous commits in a compact format. |
| Create or list branches | `git branch` / `git branch name` | Lists existing branches or creates a new branch. |
| Switch branches | `git switch branch-name` | Changes the current working branch. |
| Publish changes | `git push` | Sends local commits to a remote repository such as GitHub. |
| Retrieve remote changes | `git pull` | Downloads and integrates changes from a remote repository into the current branch. |

## Additional concepts

### Difference between add and commit
`git add` stages selected changes for the next commit, while `git commit` records the staged changes as a checkpoint in the repository history.

### Branch
A branch is a separate line of development that lets me work on changes without directly affecting the main branch.

### Pull Request
A Pull Request is a request to review and merge changes from one branch into another. It helps collaborators check changes before they are added to the main branch.

## Mission 6 status
- Branch created: update-about
- Root README updated with My Learning section.
- Pull Request created from update-about into main.
- Pull Request status: Open (not merged).

