<<<<<<< HEAD
git config -global user.name 设置全局用户名
git config -global user.emal 设置全局邮箱
git init 初始化一个git仓库
git add [./*xx] 跟踪文件
git status 显示文件状态
git commit xx -m 提交缓存区文件
git clone [url] 从指定url克隆项目
git branch 列出所有本地分支
git branch [branch-name] 创建新分支
git checkout [branch-name] 切换到指定分支
git log 查看当前分支的版本历史
git fetch [remote] 拉取远程仓库
git remote -v 查看所有远程仓库
git merge [branch-name] 将某个指定分支覆盖到当前分支
=======
<<<<<<< HEAD
git init：初始化本地库

git status：查看工作区、暂存区的状态

git add <file name>：将工作区的“新建/修改”添加到暂存区

git rm --cached <file name>：移除暂存区的修改

git commit -m "提交日志" <file name>：文件从暂存区到本地库

git log：查看历史提交

git reset --hard 简洁/完整哈希索引值：回到指定哈希值所对应的版本

git diff：比较工作区和暂存区的所有文件差异

git branch -v：查看所有分支

git branch -d <分支名>：删除本地分支

git branch <分支名>：新建分支

git checkout <分支名>：切换分支

git merge <被合并分支名>：合并分支

git clone <远程库地址>：克隆远程库

git remote -v：查看远程库地址别名

git remote add <别名> <远程库地址>：新建远程库地址别名

git remote rm <别名>：删除本地中远程库别名

git push <别名> <分支名>：本地库某个分支推送到远程库，分支必须指定

git pull <别名> <分支名>：把远程库的修改拉取到本地

=======
git add
>>>>>>> 9ef942af6982d6cd96cdf584ac805f0850de14dc
>>>>>>> dev_hdp
