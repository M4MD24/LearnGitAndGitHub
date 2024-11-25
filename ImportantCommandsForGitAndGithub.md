# Important Commands for Git and GitHub

## config

- `git config --global user.name your-username`
- `git config --global user.email your-email`
- `git config --global user.name`
- `git config --global user.email`

## ls

- `ls`
- `ls -Force`

## status

- `git status`

## add

- `git add .`

## commit

- `git commit -m "Comment"`
- `git commit --amend -m "Comment"`

## log

- `git log`
- `git log --oneline`
- `git log --graph`
- `git log --oneline --graph`

## restore

- `git restore --staged .`

## branch

- `git branch`
- `git branch branch-name`
- `git branch -m target-branch-name modified-branch-name`
- `git branch -d branch-name`
- `git branch --v`

## checkout

- `git checkout branch-name`
- `git checkout another-branch-name ; git branch -d old-branch-name`

## merge

- `git merge target-branch-name`

## notepad

- `notepad file-name`

## tag

- `git tag`
- `git tag tag-name`
- `git tag -d tag-name`

## show

- `git show tag-name`

## clone

- `git clone repository-url`

## push

- `git push`
- `git push origin tag-name`
- `git push remote-name`

## fetch

- `git fetch`

## pull

- `git pull`

## remote

- `git remote`
- `git remote -v`
- `git remote remote-name repository-url`
- `git remote rename old-remote-name new-remote-name`
- `git remote rm remote-name`

## rebase

- `git rebase base-branch-name`
- `git rebase base-branch-name from-branch-name`
- `git rebase --onto base-branch-name from-branch-name to-branch-name`
- `git rebase --abort`
- `git rebase --continue`
- `git rebase --skip`