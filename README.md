# GIT-hook
Git Hook (commit-msg)

## Requirements
Commit message hook filter that allow commit messages only starting with words ticket number.
Format like "TKT-1" or words "feat", "minor", "major", "add", "chore" (conventional `feat:` / `feat(scope):` also pass).
To use it, copy it into the repository's hooks folder and make it executable:

```sh
cp commit-msg .git/hooks/commit-msg
chmod +x .git/hooks/commit-msg
```