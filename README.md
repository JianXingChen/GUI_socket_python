# GUI_socket_python
通过wifi监听多机器人状态的服务器端程序

pyqt和twisted模块都是事件驱动型，都一直在run然后监听动作并响应。因此，它俩要同时运行，有两种方式:

一是开俩线程

二是使用专门针对qt和twisted的qt4reactor。到网上下载qt4reactor的相关文件，在将主程序中将调用qt4reactor模块。

在我们的程序中，使用了qt4reactor模块
