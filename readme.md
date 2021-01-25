# readme文档
-项目说明文档
-一般与项目放在一起

# git操作

## 初始化版本库
- git init
- 初始化成功后，目录后面有master这个东西。
- 当前目录下有个隐藏文件  .git（不要操作这个文件，默认是隐藏文件）

## 工作区（看到的代码的文件）
- 持有实际文件
- 我们平时增删改查的文件都是工作区的内容
- 

## 提交到暂存区
- 可以理解为我们看不到的一个地方
- 本地仓库的一个主要组成部分

### 本地仓库
- 可以理解为我们看不到的地方
- 也是存在于用户的电脑中的
- 用于存储项目代码及版本相关记录等信息

## 提交到暂存区
- git add 文件名
- 将工作区的变动提交到暂存区
- git add .（或者用all）  
- 将所有变动提交到暂存区

## 查看工作区和暂存区的状态
- git status  （多去用）
- 看的是工作区和暂存区的状态（增删改）

## 提交到本地仓库
- git commit -m '提交注释'
- 将代码从暂存区提交到本地仓库
- git status 查看状态

## 退出配置文件
- ：wq

##  本地操作关键步骤
1. git init（第一次时候初始化就好，后面就不需要了）
2. git add .  （提交到缓存区）
3. get commit -m'注释'  （）

## 查看日志
- git log  完整版日志
- get reflog  简单版日志

## 版本回退
- git reset --hard HEAD^ 回退到上一个版本
- git reset --hard 版本号
- 版本恢复的时候工作区恢复
- 工作区的代码自动恢复

## 查看变动
- git diff 文件名
- 会列出该文件前后的差异

## 创建远程仓库
- 进入里面的github官网
- 创建一个新的远程仓库

## 将本地仓库与远程仓库关联
- git remote add origin 你的远程仓库地址
- git remote -v  查看本地仓库关联的地址

## 将本地仓库提交到远程仓库
- git push -u origin master 第一次提交
- git push 将本地仓库提交到远程仓库
- -u origin master 设置默认的提交地址和分支


## 正常提交（第一次提交）
- git add .
- git commit -m'注释'
- git push 提交到本地仓库

##环境的符合你/
##测试











