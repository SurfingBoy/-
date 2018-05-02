## Redis安装
1.  解压redis安装包,解压之后如图所示：
  
      ![image text](/redis-windows/img/tu1.PNG)

2. 先运行redis-server.exe启动服务,双击即可(不可关闭，关了就停止了服务),安装成功会显示这样：

    ![image text](/redis-windows/img/tu2.PNG)
    
>当然我们可以将redis-server注册为windows服务，这样方便以后打开:
>
>1. 运行cmd ,定位到我们的安装路径，输入
> redis-server --service-install redis.windows.conf --loglevel verbose ,这样redis服务就注册到了Windows里。
>2. 然后启动redis服务,输入 redis-server --service-start
>
>![image text](/redis-windows/img/tu5.PNG)
>
   
3. 然后运行redis-cli.exe，可以在这里插入数据了

  ```
  set example "Hello World" #设置键‘example’的值为‘Hello World’
  get example               #获取键‘example’的值
  ```
  
  ![image text](/redis-windows/img/3.PNG)
  
>这样获取数据不方便，可以安装一个图形化界面来管理数据 RedisReact

## 安装RedisReact

windows平台直接下载安装包，双击即可运行

   ![image text](/redis-windows/img/4.PNG)
