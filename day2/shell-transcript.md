cd git-training
git tag -l
git tag -h
git tag -a baseline_day1
git push --tags
git log -p
env TERM=dumb git log -p
vim notes.md
git branch feature1
git status
git branch
wget -O pictures/git_init.gif http://25.media.tumblr.com/tumblr_m447mrJjKn1qze5g2o1_500.gif
git checkout master
git checkout -b refactor
git bisect --help
cat ~/.gitconfig | g '\s+l'
git log --graph --pretty=oneline
git log --graph --pretty=oneline --abbrev-commit
git commit gitconfig
git checkout feature1
touch bunny
git add bunny
git ci
git lg master
git lg master feature1
git rebase feature1
git reflog
git reset --hard 7b1088e
git log --graph --pretty=oneline --abbrev-commit --decorate
git add -p
git add -i
git reset pictures
git co -b hello
git checkout -b hello-from-the-past origin/master
git ci gitconfig
git co master
git branch -d hello
git lg master hello-from-the-past
git merge hello-from-the-past
git mergetool
vim gitconfig
git add gitconfig
git st
git commit -v
git branch -d hello-from-the-past
git branch -D hello-from-the-past
git push
git branch -v
git branch -a
cat .git/config
git branch master --set-upstream origin/master
git pull
git lg
