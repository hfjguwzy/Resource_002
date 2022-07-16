prectise02文件夹中存放着我的个人网站
前端使用vue3和element—plus框架，希望可以做出一个较好的网页

本文件夹是和github库中的https://github.com/hfjguwzy/Resource_002.git是相连的 
1.把GitHub库中的文件拉取到本地
$ git clone +库的路径
2.将文件夹下的所有文件添加到暂存修改
$ git add .
3.给git提交并备注
$ git commit -m "+提交备注+"
4.将本地修改上传到GitHub云端库
$ git push -u origin main
$ git push origin main

其他git命令
从远程获取代码并合并本地的版本
$ git pull origin main
配置用户名
$ git config --global user.name "+用户名+"
配置邮箱
$ git config --global user.email test@runoob.com
添加远程版本库
$ git remote add origin +github地址
查看仓库当前的状态，显示有变更的文件
$ git status
查看历史提交记录
$ git log
历史提交记录在一行显示
$ git log --pretty=oneline
版本转跳
$ git reset --hard +唯一版本号
查看所有操作
$ git reflog

Git分支操作
查看本地和远程分支
$ git branch -a
新建并转到新建分支
$ git checkout -b + " +新建分支的名字+ "
创建分支
$ git branch +新建分支的名字
删除分支
$ git branch -d +分支名字
分支重命名
$ git branch -m +旧名字 +新名字
切换分支
$ git checkout +分支名字
合并分支（必须要在主分支下输入）
$ git merge +需要合并的分支名字

github远程分支相关命令
将本地分支推送到GitHub云端库
$ git push origin +分支名字
删除GitHub云端库中的分支
$ git push origin : +分支名字
获取远程仓库最新状态
$ git fetch
获取远程分支并在本地创建分支
$ git checkout -b +本地创建分支名 +远程分支名

git标签相关命令
查看本地所有标签
$ git tag
新建标签
$ git tag +新建标签名 +唯一版本号
添加标签并添加描述信息
$ git tag -a +新建标签名 -m '+描述信息+' +唯一版本号
删除本地标签
$ git tag -d +标签名
删除一个远程标签
$ git push origin :refs/tags/+标签名
推送本地标签到远程
$ git push origin +标签名
推送全部未推送过的本地标签到远程
$ git push origin --tags


vscode 快捷键
ctrl + d 选择下一个相同字符
alt + 鼠标左键 添加光标
alt + shift + 上/下键 复制一行

/* TODO:2022/7/11 第10次修改 */