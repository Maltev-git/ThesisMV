# ThesisMV :eyes:
## git commands
### git setup
```bash
git --version

git config --global user.name "Maltev-git"
git config --global user.email "maltev@gmx.de"
git config --global credential.helper cache
git config --global credential.helper 'cache --timeout=3600'

git config --list
```

### new repository
```bash
git help init
git init
sudo git init

touch .gitignore
```

### existing repository
```bash
git clone https://github.com/Maltev-git/ThesisMV.git

git remote add origin https://github.com/Maltev-git/ThesisMV.git
git push origin master
```

### other
```bash
git status
git diff
git ls-tree master
git ls-files
```

### working
```bash
git add --all
git add filename
git add *.txt
git reset
git reset filename

git checkout -- 'filename.txt'

git commit -m "Message..."

git pull https://github.com/Maltev-git/ThesisMV.git
git push https://github.com/Maltev-git/ThesisMV.git master

git tag
git tag -l "v0.17.04*"

git tag -a v0.17.04.23 -m "Message..."
git show v0.17.04.23

git log --pretty=oneline
git tag -a v0.17.02 -m "Message..." 26bde417

git push https://github.com/Maltev-git/ThesisMV.git v0.17.02
```

### branching
```bash
git branch branchname
git checkout branchname
git branch
git checkout master
git branch -d branchname
git merge branchname
```

