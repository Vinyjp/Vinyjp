
# Vinyjp
主人，以下是常用的 Git 命令大全，分为初始化、版本控制、分支管理、远程操作等场景，帮助您高效使用 Git：

1. 初始化和基本设置

命令	作用
git init	初始化一个新的 Git 仓库。
git config --global user.name "用户名"	设置全局用户名（需与 GitHub 用户名一致）。
git config --global user.email "邮箱"	设置全局邮箱（需与 GitHub 注册邮箱一致）。
git status	查看当前仓库状态，包括未提交的更改和新增文件。
git log	查看提交历史记录。
git show	显示最近一次提交的详细信息。

2. 添加和提交更改

命令	作用
git add <文件名>	将指定文件添加到暂存区。
git add .	添加所有修改和新增文件到暂存区。
git commit -m "提交说明"	提交暂存区内容到本地仓库，并附加提交说明。
git commit -am "提交说明"	跳过 git add，直接提交所有已跟踪的文件修改。

3. 分支管理

命令	作用
git branch	查看当前分支列表。
git branch <分支名>	创建一个新分支。
git checkout <分支名>	切换到指定分支。
git checkout -b <分支名>	创建并切换到新分支。
git merge <分支名>	将指定分支合并到当前分支。
git branch -d <分支名>	删除指定分支（本地）。

4. 远程操作

命令	作用
git remote add origin <远程仓库地址>	添加远程仓库。
git remote -v	查看远程仓库地址。
git pull origin <分支名>	拉取远程分支的最新更改并合并到本地分支。
git push origin <分支名>	推送本地分支到远程仓库。
git clone <远程仓库地址>	克隆远程仓库到本地。

5. 冲突解决

命令	作用
git status	查看冲突文件的状态。
手动编辑冲突文件	删除冲突标记（如 <<<<<<< 和 >>>>>>>），并调整内容。
git add <冲突文件>	标记冲突已解决。
git commit -m "解决冲突说明"	提交解决冲突后的更改。

6. 恢复和回退

命令	作用
git checkout -- <文件名>	放弃对指定文件的本地修改。
git reset HEAD <文件名>	取消已添加到暂存区的文件。
git reset --soft HEAD~1	回退到上一个提交，保留修改内容在暂存区。
git reset --hard HEAD~1	回退到上一个提交，丢弃所有修改。

7. 查看和调试

命令	作用
git diff	查看工作目录

Git 常用命令总结

Git 是一个强大的版本控制工具，以下是按场景整理的常用命令，帮助您快速上手和高效使用。

1. 初始化与基本设置
	•	git init
初始化一个新的 Git 仓库。
	•	git config --global user.name "用户名"
设置全局用户名（需与 GitHub 用户名一致）。
	•	git config --global user.email "邮箱"
设置全局邮箱（需与 GitHub 注册邮箱一致）。
	•	git status
查看当前仓库状态，包括未提交的更改和新增文件。
	•	git log
查看提交历史记录。
	•	git show
显示最近一次提交的详细信息。

2. 添加和提交更改
	•	git add <文件名>
将指定文件添加到暂存区。
	•	git add .
添加所有修改和新增文件到暂存区。
	•	git commit -m "提交说明"
提交暂存区内容到本地仓库，并附加提交说明。
	•	git commit -am "提交说明"
跳过 git add，直接提交所有已跟踪的文件修改。

3. 分支管理
	•	git branch
查看当前分支列表。
	•	git branch <分支名>
创建一个新分支。
	•	git checkout <分支名>
切换到指定分支。
	•	git checkout -b <分支名>
创建并切换到新分支。
	•	git merge <分支名>
将指定分支合并到当前分支。
	•	git branch -d <分支名>
删除指定分支（本地）。

4. 远程操作
	•	git remote add origin <远程仓库地址>
添加远程仓库。
	•	git remote -v
查看远程仓库地址。
	•	git pull origin <分支名>
拉取远程分支的最新更改并合并到本地分支。
	•	git push origin <分支名>
推送本地分支到远程仓库。
	•	git clone <远程仓库地址>
克隆远程仓库到本地。

5. 冲突解决
	•	git status
查看冲突文件的状态。
	•	手动编辑冲突文件
删除冲突标记（如 <<<<<<< 和 >>>>>>>），并调整内容。
	•	git add <冲突文件>
标记冲突已解决。
	•	git commit -m "解决冲突说明"
提交解决冲突后的更改。

6. 恢复与回退
	•	git checkout -- <文件名>
放弃对指定文件的本地修改。
	•	git reset HEAD <文件名>
取消已添加到暂存区的文件。
	•	git reset --soft HEAD~1
回退到上一个提交，保留修改内容在暂存区。
	•	git reset --hard HEAD~1
回退到上一个提交，丢弃所有修改。

7. 查看与调试
	•	git diff
查看工作目录和暂存区之间的区别。
	•	git diff HEAD
查看工作目录与最新提交之间的区别。
	•	git log --oneline
简洁查看提交历史。

总结

使用 Git 时，常见操作包括初始化仓库、添加文件、提交更改、管理分支和与远程仓库交互。掌握以上命令，您可以轻松管理代码和协作开发。主人，Git 是非常强大的工具，如果需要深入了解某条命令，随时告诉我哦！ 💖

