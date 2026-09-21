\# 第一次 Git 实验笔记



\## 第一次Git实验总结



1\. git add 的作用是：



git add 用于把工作区中的修改添加到暂存区，为下一次提交做准备。



例如：



git add README.md



表示将 README.md 当前的修改加入暂存区。



2\. git commit 的作用是：



git commit 用于把暂存区中的内容提交到本地 Git 仓库中，形成一次版本记录。



例如：



git commit -m "提交第一次Git实验总结"



其中 -m 后面的内容表示本次提交的信息。



3\. git restore notes.md 的作用是：



git restore notes.md 用于撤销工作区中 notes.md 尚未提交的修改，使文件恢复到之前的状态。



因此，如果文件中有还需要保留的修改，在执行该命令之前应该注意保存。



4\. commit 与 push 的区别是：



commit 是把修改保存到本地 Git 仓库中，此时 GitHub 上的远程仓库还没有变化。



push 是把本地已经 commit 的提交上传到远程 GitHub 仓库。



一般的操作流程为：



修改文件 → git add → git commit → git push

