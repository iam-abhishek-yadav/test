# test
git config --global user.email "something@c.com"
git config --global user.name "Jack mama"

git branch -a
git checkout branchName
git checkout -b newBranch

git status
git diff
git add . OR git add fileName
git commit -m 'commit message'

git reset  // move changes from staged to changes
git log
git reset --hard commitId   // move back specific commit
git show 7076a5e752d69c41d91bdcf0da9cc43084cac46f // show in detail