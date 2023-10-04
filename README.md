# tgstate

原版README: <https://github.com/csznet/tgState/blob/main/README.md>

美化来自 https://blog.xcnya.cn/

此版本更改了上传的大小限制，并不设置后缀名限制，还进行了css字体与背景美化，From <https://blog.xcnya.cn/>

可以当正常网盘使用

---------------分割线---------------

使用方法等均与原版相同

如需部署到Vercel，请点击[这里](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FGenshinMinecraft%2FtgState-Unlimited&env=token&env=channel&project-name=tgState-Unlimited&repository-name=tgState-Unlimited)

不知为何，Vercel所部署的服务不支持5MB以上文件上传，没有必要的话请部署与自己服务器上！

暂不支持Docker部署，以后也不会支持

在自己机器上的使用方法：（自行保活）
```
git clone https://github.com/GenshinMinecraft/tgState-Unlimited.git #克隆项目
cd tgState-Unlimited
go build #编译

./tgState-Unlimited -token Bot的Token -channel 用户uid/@频道 -port 端口 #启动命令
```
