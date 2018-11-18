# 关于使用Git远程仓库：
全局配置
```shell
$ git config --global user.name 'myUserName'
$ git config --global user.email 'myEmail'
```
进入目标文件夹根目录，初始化git仓库
```shell
$ git init # 创建一个git的初始化文件.git，这个文件中的config文件为git仓库的配置项
```
添加欲上传的文件
```shell
$ git add file.txt
$ git add .
$ git add *.html
```
查看状态
```
$ git status
```
提交
```shell
$ git commit -m 'xxxxxx'
```
忽略某文件
```shell
1.根目录创建.gitignore文件
$  xxxx.txt  # 忽略xxxx.txt文件
$  /dev  # 忽略dev文件夹
$  /configs/xxx.txt 
```
分支操作
```shell
1.创建分支
$ git branch login # 创建login分支
2.切换分支
$ git checkout login # 切换进login分支
$ git checkout master # 切换主线
3.主线与分支合并
  >> $ git checkout master # 如果处于分支，先进入主线
     $ git merge login
```

