# Git Essential

## Git initialization

- Only one time need to initialization

```
git init
```

## Git add and Git status

- Add single file or folder or all changes made
- See all changes made `git status`

```
git add filename
```

- Add a folder `git add folder_name`
- Add single file `git add file_name`
- Add all file `git add .`

## Git commit

- Commit message should be meaningful sentence

```
git commit -m "commit message"
```

- Want to commit all changes `git commit -am "commit message"`

## Edit Git commit

- Edit committed message `git commit --amend`

## Git remote

- Add a remote `git remote add origin repository URL`
- See Current remote URL or Verify new remote URL `git remote -v`
- Change Current remote URL `git remote set-url origin repository URL`

## Git push

- Push Changes into remote URL

```
git push
```

## Git clone

```
git clone repository
```

- Git clone with customize folder name `git clone repository folder_name`

## Git pull

```
git pull
```

- Git pull from a branch name `git pull origin branch_name`

## Git checkout

- Reset all into previous pull code `git checkout .`
- Checkout a single file or folder `git checkout file_name` or `git checkout folder`
- Change a branch `git checkout branch_name`

## Git diff

- Want to see what you haven't git added yet `git diff file_name`
- Want to see already added changes `git diff --cached file_name`

## Git stash

- Hide changes without commit

```
git stash
```

- See list with hidden changes `git stash list`

```See example:
stash@{0}: WIP on something
stash@{1}: Fixed something
```

- Apply last changes from stash list `git stash apply`
- Choose what stash will apply `git stash apply stash@{1}`
- Remove from stash list `git stash drop stash@{0}`

## Git branch

- Show current branch `git branch`
- Show all branch list `git branch -a`
- Change a branch `git checkout branch_name`

## Git log

- See all committed log `git log`

## Git show

- Show current committed code `git show`
- Show specific commit from log `git log` and use four digit of any commit ID `git show commit_ID`

```
commit bbb00beb1e5a8aef2ce494aa9b98074e21d790c3
git show bbb0
```
