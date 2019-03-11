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

