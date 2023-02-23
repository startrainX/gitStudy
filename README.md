```shell
# git初始化
git init
# git 添加文件到暂存
git add fileName……
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
```

