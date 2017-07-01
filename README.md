# Overview of git command
## init a git repo
git init

git add README.md

git commit -m “first commit”

git remote add origin https://github.com/wanghan1110/exercise.git

git push origin master

## Summary of 进行比较文件的不同
git status （状态比较：比较working dir和staging area的不同)

git diff (文件比较：比较working dir 和 local repo的不同)

git diff HEAD (文件：比较working dir和 remote repo的不同)