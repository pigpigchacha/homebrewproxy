# 直接上干货
1. 下载pigcha加速器,[下载地址点我](http://pigcha.com?from=gitbrew)，注册登录后，点开始按钮
2. 最重要的来了！！！在托盘图标点代理控制台，如图
![img](https://cdn.processon.com/605b3a0b6376897007792fd3)
3. 此时在弹出的来控制台，然后我们输入一个测试命令brew search go，效果非常好
![img](https://cdn.processon.com/605b3d136376897007793825)

# 原理
通过 export http_proxy和 export https_proxy来实现http代理协议，先将代理转到127.0.0.1上，然后再通过你选的节点，通过节点去帮你代理请求。。速度就上去了
