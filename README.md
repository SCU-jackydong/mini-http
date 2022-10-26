# mini-http
![image](https://github.com/SCU-jackydong/mini-http/blob/master/3.png)

一个迷你的服务器，保持监听客户端的请求，每当有一个客户端请求访问服务器时，服务器执行对该请求的处理，首先解析客户端传送的数据，以浏览器为例，传输一个http报文，运用字符串分割算法以报文格式解析该数据，判断请求的方法是GET/POST，请求路径，若请求方法为GET，路径为/index，则返回相应的http报文格式给客户端，报文的正文为一段html。如下图：
![image](https://github.com/SCU-jackydong/mini-http/blob/master/1.jpg)
