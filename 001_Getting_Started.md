# Git使用快速入门

## 创建仓库

### 创建一个本地仓库

```
# git初始化，初始化成功之后，目录下出现一个.git文件夹
git init

# 配置git，用户名和email必须要配置
git config user.name "username"
git config user.email "username@user.email.com"

# 将文件添加到版本库
git add index.html

# 提交到本地仓库
git commit -m "commit message"

# 本地仓库是远程仓库的一个副本，本地仓库的提交需要同步到远程仓库
# 将本地仓库连接到远程仓库
git remote add origin https://github.com/username/mytest.git

# 提交到远程仓库
git push -u origin master
```

### 克隆一个仓库
已经存在一个仓库，使用clone命令在本地创建该仓库的本地副本

```
# 克隆一个仓库
git clone https://github.com/username/mytest.git

# 配置git，用户名和email必须要配置
git config user.name "username"
git config user.email "username@user.email.com"

# 将文件添加到版本库
git add index.html

# 提交到本地仓库
git commit -m "commit message"

# 提交到远程仓库
git push origin master
```
