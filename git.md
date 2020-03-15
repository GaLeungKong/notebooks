# git

## 概念

### 工作区

git init 之后（会产生一个.git隐藏文件夹）的一个directory

### 版本库

就是.git隐藏文件夹

#### stage/index

暂存区，通过git add 将某些文件添加进去

#### 分支

#### 指针HEAD

## 命令

### git add *filename* 

*将某文件* 添加到暂存区

### git commit 

将暂存区内容提交到当前分支

### git status 

查看仓库当前的状态

### git diff *filename* 

查看*某文件* 修改的内容

### git log 

版本控制/提交的历史记录

 --pretty=oneline 单行显示 

### git reset *commit_id* 

版本回退

--hard 

### git reflog 

查看执行的命令的历史

### git restore

--staged

### git rm

可以对比 git add, git add 将一个文件的修改放入暂存区, 而git remove 将一个文件的删除放进了暂存区(添加了一个删除记录)