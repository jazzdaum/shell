### git常用配置
```sh
git config --global user.name  #"你的姓名，最好由没有符合和空格的英文字母组成"
git config --global user.email #<邮件名>@<邮箱服务商后缀>

git config -l #查看全局配置

git init #初始化

git add . #添加当前目录所有内容：
或 git add <change file>

git status #查看状态

git commit -m "first commit."  #提交到仓库

git push -u origin master #推送数据到master

git diff  #版本对比：在没提交到暂存区之前可以对比
```
