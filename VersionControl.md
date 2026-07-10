# Note: Use Ctrl+Shift+V to see formatted version

## First time setting up a project
```bash
Make new repo in GitHub           
git clone https://github.com/USERNAME/REPONAME.git  # start tracking a new project
Note: We do not manually create a local vscode folder
```

## Daily workflow
```bash
cd into new project
git add .                       # stage all changes
git commit -m "what you did"    # save checkpoint
git push                        # back up to GitHub
```

## Check your history
```bash
git log    # see all commits + their hashes
```

## Undo a commit (keep file changes)
```bash
git reset --soft HEAD~1
```

## Undo a commit (wipe file changes too)
```bash
git reset --hard HEAD~1
```

## Go back to a specific commit
```bash
git reset --hard a3f2c1d    # replace with hash from git log
```

## Throw away uncommitted changes
```bash
git restore .
```

## Get latest changes from GitHub
```bash
git pull
```

## Rules of thumb
- Commit whenever you finish something meaningful
- Soft reset = safe, hard reset = permanent
- `git restore .` and `--hard` are irreversible — be sure before running them
