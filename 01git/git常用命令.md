# git常用命令

## 1.从远程克隆仓库,添加内容再推送到远程

~~~
git clone xxxx
git add .
git commit -m"xxx"
git push
git status  //看git仓库的状态
git remote -v //看本地仓库和远程仓库的关联
~~~

## 2.版本回退 

~~~
git log 
git reflog
git reset --hard xxx
~~~

## 3.git的全局信息及修改

~~~
git config --global --list  //仓库的全局信息
git config --global user.name xxxx  //更改用户名
git config --global user.email xxxx //更改邮箱
~~~

## 4.分支管理

~~~
git branch <branch-name> //创建分支
git branch //看仓库中有几个分支
git checkout <branch-name> //切换到某个分支
git merge <branch-name>  //合并分支
git checkout -b <branch-name>
git stash  //将工作去内容添加到存储区  --git add.
git stash pop //将存储区的内容回复
~~~

## 5.本地仓库获取远程仓库的信息

~~~
git pull
~~~

