# okcoinBTCRobot
https://www.okcoin.com/about/ws_api.do

okcoin比特币交易平台机器人代码。代码使用websocket接口。写了一个多线程的https请求类。用这个类可以在价格达到交易要求时使用reset接口发送比特币交易请求。

写了一个多线程定时器。可以设置定时器触发方法。来对接收到的交易行情数据进行分析。
