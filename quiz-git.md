# Git 的使用

## Q1

Git 是一个广泛使用的版本管理工具，适合团队开发。  
如果你用过 Git，那么请回忆一下，  
我们在确认开发需求之后，从写代码到提交进团队的代码仓库。  
这个过程中大概会用到哪几条命令？

请直接在这里作答。

答：git checkout -b name
git add .
git commit -m 注释
git checkout master
git pull origin master
git merge name

## Q2

你知道和用过哪些 Git 的方法论和技巧

答：没提交暂缓区，或者没 commit 代码出错，都可以通过撤销操作来回滚
