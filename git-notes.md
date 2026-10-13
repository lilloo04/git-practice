# Basic Git Notes

## What Is Git?

Git is a distributed version control system that records project history.

## Basic Commands

| Command | Purpose |
| --- | --- |
| `git init` | Initialize a repository |
| `git status` | Check the working tree and staging area |
| `git add filename` | Stage changes in a file |
| `git commit -m "message"` | Record staged changes |
| `git log --oneline` | Display a compact commit history |
| `git push` | Send local commits to a remote repository |

## Basic Workflow

1. Create or modify a file.
2. Check changes with `git status`.
3. Stage changes with `git add`.
4. Record changes with `git commit`.
5. Upload commits with `git push`.

## Important Points

- Saving a file is different from committing it.
- A commit records staged changes.
- A push sends commits to a remote repository.
- Never commit passwords or API keys.
