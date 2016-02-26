# openresty-study
A demo program to learn openresty myself

实例功能要求：

1. 使用openresty实现一个服务端程序，接收终端的web请求，获取uri中的mid和ip，根据mid去redis库中查找相应的ip，如果存在返回命中， 不存在则添加到redis和mysql中。
注：uri中含有mid和ip，mid和ip的值以key-value的形式缓存于redis库中，并存于mysql数据库中。

2. 测试服务程序的QPS。

