来聊聊git的进阶功能

git is free software distributed under the GPL

git reset --hard HEAD^ 版本回退，HEAD表示当前版本，HEAD^表示上个版本
git merge dev 合并分支到master
git reflog 显示所有操作日志
复制操作编号，执行git reset --hard 编号  撤销操作
git log --pretty=oneline 日志显示为一行
git checkout 分支名 切换到某分支
git checkout -b dev 创建一个新的本地分支dev并转到dev分支
git branch 查看所有分支
git branch -d 分支名 删除某分支

git add ./文件名 提交文件