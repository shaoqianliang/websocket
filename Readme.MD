websocket协议是基于Tcp的一种新的协议,实现浏览器和服务器的全双工(full-duplex)通信,
基本保持TCp连接
websocket和Http协议的区别:
	1.websocket可以主动推送消息给客户端,解决http同步延时的问题
	2.websocket只需要一次连接,长连接,需要客户端主动关闭请求