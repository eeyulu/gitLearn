1：git clone——复制一个项目
2：git status——查看项目的状态
3：git add——将项目从工作区提交到暂存区
4：git commit——将项目从暂存区提交到分支
5：git reset——恢复某个提交
6：git pull——拉取项目
7：git push——推送项目
8：git log——查看日志
9：git --help——查看帮助（这个非常的重要，可以通过此命令学习许许多多的命令的使用方式）
10：git --version——查看版本



版本回滚操作步骤:
1. 命令: git log // 显示所有提交记录.
2. 在所有提交记录中,选择需要回退到的commit ID(一个长字符串),复制.
3. 命令: git reset --hard XXYYZCCRERR // 最后一串是commit ID.完成回滚操作.
4. 命令: git log // 显示新的提交记录.

这里 利用 git reset 命令,可以任意回滚到过去,同时也可以穿越到未来.
很方便.
(回到未来 （fast -forward)
git reflog查看该用户的所有操作
