# ESP8266-iRobot
[iRobot开发前期准备](https://blog.csdn.net/zuoliwu/article/details/81257811)
# 使用方法
* 1.事先建立好TCP server ，准备好服务器IP地址、端口号。
* 2.在给单片机上电前配置好ESP8266模块，确保模块连入服务器。
* 3.数据格式
最好使用16进制发送，格式为： 发送数据+‘+’  
例：Foward：80 82 89 00 C8 80 00 2B(以16进制发送)  
    Left：  80 82 89 00 C8 00 00 2B  
    Back：  80 82 89 FF 38 80 00 2B  
    具体指令详解见数据手册
