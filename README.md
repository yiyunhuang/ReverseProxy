# ReverseProxy
ReverseProxy in golang

## Use:

	./ReverseProxy_[OS]_[ARCH] -h
	
	Usage of ReverseProxy_[OS]_[ARCH]:
	  -l string
	        listen on ip:port (default "0.0.0.0:8888")
	  -r string
	        reverse proxy addr (default "http://idea.lanyus.com:80")


	./ReverseProxy_windows_amd64.exe -l "0.0.0.0:8081" -r "https://www.baidu.com"

	Listening on 0.0.0.0:8081, forwarding to https://www.baidu.com




### 使用说明

Jrebel 实现本地激活
下载激活文件
前往 Jrebel License Server 下载 ReverseProxy_darwin_amd64 该文件是 mac 可使用的
为文件添加权限并运行
chmod 777 ./ReverseProxy_darwin_amd64
$bash ./ReverseProxy_darwin_amd64

运行成功后显示如下内容


前往 Jrebel 配置界面按如下输入
地址后面需要跟一串 GUID 验证
邮箱可随意输入

输入成功显示激活后要立即将 Jrebel 设置为离线模式，可确保 180 有效性
180 天后重复上述操作即可
如果不设置为离线模式，终端运行的程序就不能退出，一旦退出激活就会失效
————————————————
版权声明：本文为CSDN博主「asing1elife」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/asing1elife/java/article/details/82696822
