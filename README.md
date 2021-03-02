

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
git push origin --delZ