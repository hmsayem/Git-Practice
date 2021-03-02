

> Viewing Staged and Unstaged Changes
```
git diff 
git diff --cached

```

> Stage all and Commit
```
git commit -a -m "C2:main Commit README.md"

```
> Remove file from tracked files
```
git rm delete.txt
git -f rm delete.txt

```

> Remove file from tracked files
```
git rm delete.txt
git -f rm delete.txt

```
> Remove file 
```
git mv file0.txt file1.txt

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
git restore --staged file1.txt
git restore  file1.txt

```