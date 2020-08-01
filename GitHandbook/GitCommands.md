# Git Commands

### Syncing a fork

Sync a fork of a repository to keep it up-to-date with the upstream repository

Firstly, you have to use `git remote -v` for managing set of tracked repositories. You have to add a new remote `git remote add upstream https://github.com/orginal_owner/original_repo.git`. Retype `git remote -v` to check the new upstream repository. Then, you have to use commands:

```git fetch upstream```

```git checkout master```

```git rebase upstream/master```

```git push -f origin master```

### Cleaning up commit history

```git checkout --orphan latest_branch```

```git add -A```

```git commit -am "Initial commit"```

```git branch -D master```

```git branch -m master```

```git push -f origin master```
