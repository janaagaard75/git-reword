# git-reword

Git command for bulk rewording all the commit messages on the current branch in a single file.

Opens all commits on the current branch (`<base>`..HEAD) in your editor, where `<base>` is the first of `dev`, `main` or `master` that exists locally. Merge commits are skipped. Refuses to run on the base branch itself.

Installation: put the `git-reword` script in your PATH.

Usage: `git reword` from a folder in a git repository.
