# Various Bash scripts for git

- `cherry-pick-range` Pass a range of commits to cherry-pick. Oldest commit first.
    1. Start commit (oldest).
    2. End commit (newest).

- `cherry-pick-branch` Given a merge commit, cherry-picks all associated commits.
    1. Merge commit.

- `cherry-pick-author` Cherry-picks all commits for an author within a set of parameters.
    - `--since="10am"`, defaults to `6am`.
    - `--branch="dc1f230"`, defaults to `master`.
    - `--author=colleague`, defaults to `user.email`.

- `merge-branch` Rebase, merge and push a branch to origin/master.
    1. Branch to merge
