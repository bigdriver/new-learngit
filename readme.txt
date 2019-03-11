git stash  藏匿工作内容
git stash list  查看藏匿工作内容列表
git stash apply stash{0}  恢复藏匿内容stash{0}
git stash drop 删除藏匿内容列表
git stash pop 恢复并删除藏匿内容

issue-101  bug分支
feature-101  新功能分支
git branch -D dev 强制删除dev分支

git merge --no-ff -m "**" dev  使用-no-ff模式合并dev分支到当前分支
平时在dev issue-101 feature-101 分支上工作，最后合并至master分支
git remote  查看远程库信息
git remote -v   查看远程库详细信息

git push origin dev  推送dev分支到远程库origin的dev分支上

git pull  拉取远程库分支到本地

git checkout -b branch-name origin/branch-name  在本地创建和远程库同名的分支

git branch --set-upstream branck-name origin/branch-name  |
git branch --set-upstream-to=origin/<branch> <branch>  关联远程库<branch>分支与本地<branch>分支

git merge 发生冲突后，用git status 查看冲突，用vi <file> 修改冲突

