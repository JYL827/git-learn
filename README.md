来聊聊git的进阶功能

git is free software distributed under the GPL

git reset --hard HEAD^ 版本回退
git 
git reflog 显示所有操作日志
复制操作编号，执行git reset --hard 编号  撤销操作
git log --pretty=oneline 日志显示为一行
git checkout 分支名 切换到某分支
git checkout -b dev 创建一个新的本地分支dev并转到dev分支
git branch 查看所有分支
git branch -b 分支名 删除某分支