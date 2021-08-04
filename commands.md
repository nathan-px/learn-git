create a fork

clone your fork

```
git clone
```

view and setup remotes

```
git remote -v 
```

```
git remote add ...
```

checkout a new branch

```
git checkout -b
```

make changes

push changes to origin

```
git push origin <branch>
```

open a pull request

merge the pull request

checkout master

```
git checkout master
```

pull master

```
git pull --rebase upstream master
```

copy the commit hash from the logs

```
git log
```

checkout the version branch

```
git checkout 1.0
```

pull the latest version branch

```
git pull --rebase upstream 1.0
```

cherry-pick the change

```
git cherry-pick <paste>
```

compare your local branch with the upstream version branch to ensure you're only pushing the change you intend

```
git diff upstream/1.0
```

push the change upstream

```
git push upstream 1.0
```

ensure it builds without errors