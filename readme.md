# Git Guide


### 1.Config user
```
git config --global user.name "Iker Casado Moreno"
git config --global user.email "15583592.clot@fje.edu
git config --list
```

### 2.Init git
```
mkdir "Gut Guide"
cd ".\Git Guide"
git init
dir -hidden
```

### 3.First commit
```
git status
git add <file>
git status
git commit -m "Commit message: brief description"
git status
git log
```

### 4.Create branch
```
git branch dir/branch-name
git branch
```

### 5.Chekout branch 
```
git checkout dir/branch-name
git status
```

### 6.Merge to master
```
git checkout master
git status
git merge dir/branch-name
git status
git log
```

### 7.Create stash
```
git status
git stash
git status
```

### 8.Apply stash
```
git stash list
git stash apply
git status
```

### 9.Delete stash
```
git stash list
git stash drop 1
git stash list
```

### 10.Pop stash
```
git stash list
git stash pop
git stash list
```
