# git-cli

git config --global user.name "My Name"

git config --global user.email myemail@xyz.com

git config --global init.defaultBranch main

git config --list

git config -h
git help config

git log
git log --oneline

echo "# repoName" >> README.md

git init

git add fileName.ext 
git add --all | git add . | git add -A

git restore --staged fileName.ext

git rm --cached fileName.ext

git commit -m "first commit"
git commit -a -m "first commit"
git commit -m "first commit" --amend

git restore --staged fileName.ext

git rm "fileName.ext"

git restore "fileName.ext"

git mv "fileName.ext" "fileName2.ext"

git log
git log -p

git remote add origin https://github.com/username/ripoName.git
git remote rm origin

git branch -M main | git branch -M master

git push -u origin main | git push -u origin master
git push --all

git reset --hard $SHA1
git push origin -f

git ls-remote
git show-branch -r

git config --global http.postBuffer 157286400

