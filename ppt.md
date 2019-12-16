# Git的使用技巧

## Why Git?

## 一般场景
> ### 入职第一天
> 1. 安装Git、环境变量
> 2. 申请Git远程仓库（GitLab）权限
> 3. git clone @ProjectUrl
> 4. 生成SSH公钥
> 5. 一切就绪，开始搞事情
> 
> 具体步骤：
> 1. 开新分支
> 2. 编写代码
> 3. add、commit、添加远程分支
> 4. GitLab合并申请

> ### 一次commit，没有完成工作。
> 1. 编码，接着commit -m
> 2. 编码，commit -amend
> 3. git reset HEAD^，编码，commit -m
> 4. git commit -m * 很多次, 最后git rebase -i

> ### 合并申请，有人提问题
> 同上

> ### 合并请求挂者，突然冲突
> 首先，主分支更新
> 
> git checkout webui-dev
> 
> git pull
> 
> git checkout 原来的分支
> 
> 然后
> 1. git merge webui-dev  //todo
> 2. git rebase webui-dev
>  


>  ### 工作到一半，需要到别的分支工作
> 1. git commit -m
> 2. git commit --amend
> 3. git stash (save 'msg')

>  ### 误删commit，万恶的reset --hard
> 1. git commit -m
> 2. git commit --amend
> 3. git stash (save 'msg')
> 



