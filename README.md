README.md
##hello

Creating a new branch is quick.



git 常用命令：

查看分支：git branch

创建分支：git branch <name>

切换分支：git checkout <name>

创建+切换分支：git checkout -b <name>

合并某分支到当前分支：git merge <name>

删除分支：git branch -d <name>

强制删除未合并的分支：git branch -d <name>

分支管理策略
git merge --no-ff -m "merge with no-ff" dev


issue-001问题修复

用带参数的git log也可以看到分支的合并情况：
git log --graph --pretty=oneline --abbrev-commit
