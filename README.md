

> Viewing Staged and Unstaged Changes
```
git diff 
git diff --cached

```
> Stage all and Commit
```
git commit -a -m "message"

```
> Remove file from tracked files
```
git rm <filename>
git -f rm <filename>

```
> Remove file from tracked files
```
git rm <filename>
git -f rm <filename>

```
> Remove file 
```
git mv <oldfilename> <newfilename>

```
> Commit History
```
git log -p 
git log --stat
git log --pretty=oneline
git log --pretty=short
git log --pretty=full
git log --pretty=fuller
git log --pretty=format:"%h - %an, %ar : %s"
git log --pretty=format:"%h %s" --graph
git log --since=2.weeks

```
> Undoing things
```
git restore --staged <filename>
git restore  <filename>

```
> Working with Remotes
```
git remote -v
git remote add <shortname> <url>
git remote rename <oldname> <newname>
git remote remove <name>
```
> Fetching and Pulling
```
git pull
git push

```
> Tagging
```
git tag 
git tag -a <tagname> -m "message"
git tag -a <tagname> <checksum> 
git tag -d <tagname>
git push origin --tags
git push origin --delete <tagname>
```

> Branching
```
git diff <branchname>..<branchname>. (Difference between 2 branches)
git merge <branchname> merge branches (Fast-forward and 3-way merges)
git branch --merged (Show branches merged into the current branch)
git branch -d <branchname>. = (Delete a branch, only if already merged)
git branch -D <branchname>. = (Delete a branch, including if not already merged)
git merge --abort (Abort a merge during a merge conflict situation)

```
> Stashing
```
git stash  (Create a stash point)
git stash list (List stash points)
git stash list -p (List stash points and show diffs per stash)
git stash apply (Apply most recent stash)
git stash pop (Apply most recent stash, and remove it from saved stashes)
git stash apply (Stash reference) (Apply a specific stash point)
git stash save "description" (Create a stash point, be more descriptive)

```
