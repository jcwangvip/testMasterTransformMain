# testMasterTransformMain

本地项目初始化git环境
git init

所有文件加入暂存
git add .

提交
git commit -m '提交描述'

本地项目关联远程仓库
git remote add origin 远程地址

检出远程仓库main 到本地 main
git checkout origin main -b main

合比master分支到main分支
git merge master

推送最新代码,这里需要输入远程仓库登录信息，用的是用户名
git push

删除远程分支master
git push origin --delete master