开发不易维护不易，代码很垃圾，希望对你有帮助
===

支持功能

 * 主动发消息 
   目前 效果：发一条消息能 发送出多条自定义消息。最后可以实现给任意好友群发消息
 * 防撤回 
    防撤回的难点 是 接收到撤回命令，拦截，然后给用户提示出谁撤回了消息。我hook了他 数据库，直接调用 sql命令
 * 抢红包 
    我hook了他 数据库的插入操作，所以红包来时的 消息我能拦截到。同理，只要是操作数据库的其他事件都能拦截到（比如自动回复）
 * 骰子作弊  
     这个难点是。其他人的骰子作弊设置骰子点数的地方都在外面。我这个是仿照fzhang大神的样子，仍骰子的时候。设置发几点
 * 模拟位置 
     这个是整合了好几个apk的功能。从主界面能加载 高德地图，然后设置位置。修改的位置，在发送时时位置，和附近人都生效
 * 步数最高
   这个是反编译别人的apk，直接拿的源码。他是修改的传感器。


畅玩微信 xposed模块(只支持微信6.6.1)
====




ScreenShots
====
![image](https://github.com/skyun1314/AesTest/blob/master/screenshots/1.jpg)
![image](https://github.com/skyun1314/AesTest/blob/master/screenshots/chehui.jpg)
![image](https://github.com/skyun1314/AesTest/blob/master/screenshots/3.jpg)
![image](https://github.com/skyun1314/AesTest/blob/master/screenshots/4.jpg)
![image](https://github.com/skyun1314/AesTest/blob/master/screenshots/5.jpg)
![image](https://github.com/skyun1314/AesTest/blob/master/screenshots/6.jpg)
![image](https://github.com/skyun1314/AesTest/blob/master/screenshots/7.jpg)
![image](https://github.com/skyun1314/AesTest/blob/master/screenshots/setp.png)
![image](https://github.com/skyun1314/AesTest/blob/master/screenshots/9.jpg)
 


Hope
==== 
如果觉得有用，欢迎star
如果使用发现问题，欢迎issue

支持作者
==== 
开发插件占用了我个人大量的私人时间，如果你觉得对你有所帮助，不妨请我喝杯☕️以鼓励我开发出更优秀的插件
 ![image](https://github.com/skyun1314/AesTest/blob/master/screenshots/alipay.jpg)
![image](https://github.com/skyun1314/AesTest/blob/master/screenshots/mm_pay.png)
