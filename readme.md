## Git简介

Git是目前世界上最先进的分布式版本控制系统（没有之一）。

## Git的作用
1. 防止代码丢失
2. 远程同步代码
3. 团队合作利器
4. 代码还原
5. 记录代码版本

## Git常用的操作命令

```
#用户配置
git config --global user.name "xxx"
git config --global user.email "xxx"

git init #初始化git仓库
git status #查看状态
git add #将文件添加到git创库的暂存区
git commit #将添加到暂存区的文件提交到git仓库（本地）
git log #查看日志
git branch #查看当前仓库的分支
git branch xxx #创建xxx分支
git checkout xxx #切换分支到xxx
git branch -d xxx #删除xxx分支
```

## Github
1. 代码托管
2. 协同开发
3. 个人博客
4. 个人简历

## 使用Github
- star 收藏
- fork “复制”
- repository 仓库
- watch 关注动态
- gist 代码片段
- clon 克隆项目

```
git clone 地址
git push origin master #origin远程 master分支
git pull origin master
```

**SSH授权认证**

```
#生成公钥和私钥
ssh-keygen -t rsa

#验证是否授权成功
ssh -T git@github.com
```
