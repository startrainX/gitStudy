```shell
# git初始化
git init
# git 添加文件到暂存
git add fileName……
# 删除暂存文件
git rm --cached fileName
# commit 提交文件到本地仓库
git commit -m message
# commit 将暂存区指定文件提交文件到本地仓库
git commit fileName…… -m message
# push 提交文件到远程仓库
git push origin branchName:remoteBranchName
# push 提交文件到仓库，后续当前分支push时直接git push就可以了
git push --set-upstream origin remoteBranchName
# 创建分支
git branch branchName
# 新增远程仓库地址
git remote add origin gitAddress
# 查看本地分支 加 -a 查看远程分支
git branch
# 拉取远程文件
git pull
# 克隆一个远程仓库
git clone url
# 隐藏名称为message的当前分支的更改
git stash save message
# 查看隐藏的工作信息列表
git stash list
# 恢复指定的隐藏工作信息，但不会删除
git stash apply stashId
# 恢复隐藏的工作信息，同时删除隐藏的工作信息
git stash pop
# 删除隐藏的工作信息
git stash drop
# 合并前n次历史提交，会弹出vim修改信息，修改第二行的pick为s(squash)，然后保存退出
git rebase -i HEAD~n
# 撤回版本到指定commitId上，在此之后的所有提交都被删除
git reset commitId
```

