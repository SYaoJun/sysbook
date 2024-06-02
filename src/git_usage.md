# 第一章 GIT
一些不常用的git命令
```c
# 应用某个patch
git am 0001-xxx.patch
# 将最新一次提交打patch
git format-patch -1 HEAD
# 删除远端分支
git push origin :2023spring 
# 本地分支改名
git branch -m 2023spring main 
# 删除本地分支
git branch -d branch_name
# 修改作者
git commit --amend --reset-author
# 添加追加文件，但不修改log信息
git commit --amend --no-edit
# 显示最近2次提交的补丁
git log -p -2
# 查看每次提交涉及的文件
git show --stat commit-id
git log --stat -1
# 切换到远程代码分支
git checkout -b local_dev remotes/og/dev
```
