启动Nginx 服务。sudo systemctl start nginx
. 开机自动启动nginx 服务
sudo systemctl enable nginx
. 关闭开机自动启动nginx 服务
sudo systemctl disable nginx

. 也可以用Nginx 命令去测试
sudo nginx -t
Tip: 当每次修改完nginx 配置后, 也可使用此语句先查看配置是否正确.


sudo passwd root

netstat -ntlp 查看端口

git remote add origin 远程仓库地址

git push -u origin 分支

git clone 远程仓库地址

git checkout 分支



1、往github上上传首先要在本地生成版本 
git init  初始化文件夹
git status查看当前文件的状态
git add .  管理文件夹下的所有文件
git add filename.html 管理单个文件
git config --global user.email 'youremail@email.com'  添加一个邮箱和用户名
git config --global user.name ''yourname
git commit -m '描述信息'

2、回滚到之前的版本
git log 查看版本情况
git reset --hard 版本号     回滚到某一个版本

3、回滚到之后的版本
git reflog
git reset --hard 版本号     回到后滚后的版本

4、分支相关的操作
git branch 列出所有的本地分支
git branch -r  列出所有的远程分支
git branch dev 创建一个叫做dev的分支
git checkout dev  切换到dev分支上

回到master分支上合并bug分支的内容
git checkout master
git merge bug
删除多余的分支 
git branch -d bug分支
删除之前的origin 
git remote rm origin

touch xiaoqiang.py 在git上创建一个新文件

5、github远程方面的操作
git remote add origin https:github.com/xiaoqiang.git
相当于是为远程的仓库地址起了 一个  origin的别名
git push -u origin master  把本地的master分支推送到 origin
git push -u origin dev 把Dev分支推送到origin

git remote add origin    https://github.com/yichengqiang/test.git
git remote set-url origin https://ghp_ElVEZfzJ8UAjDzk8pzo30Xcqpo@github.com/yichengqiang/test.git
https://github.com/yichengqiang/test.git

git remote set-url origin  https://<your_token>@github.com/<USERNAME>/<REPO>.git
<your_token>你的令牌
<USERNAME> 你的GitHub名
<REPO> 本仓库项目名称


ESP8266_OLED网络时钟
用到的库文件：
ESP8266_DYWiFiConfig.zip
Time.rar
Timezone.rar
U8g2.rar
