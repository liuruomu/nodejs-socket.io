# nodejs-socket.io
Nodejs中socket.io的简单应用，方便理解。加深之后，在这基础上进行扩展

1、安装socket.io

npm install socket.io

2、创建服务端代码server.js
3、创建客户端代码 index.html
4、执行结果

启动服务端：

node  server.js

在浏览器输入 http://localhost:8080/index.html

浏览器打印出： world

命令行打印出：{ my: 'data' }

通过修改data中的值，直观看socket是如何客户端与服务器端进行通信的。

