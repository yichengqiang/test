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


ESP8266_OLED网络时钟

用到的库文件：
ESP8266_DYWiFiConfig.zip
Time.rar
Timezone.rar
U8g2.rar
