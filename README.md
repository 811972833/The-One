# The-One
1. SimScenario类构造函数中读取Setting中的配置信息.
2. Setting 中的 getCsvInts(String, length)获得配置文件中的一组信息,长度为length.
3. Setting 中的setNameSpace(String)是改变配置文件要读取的命名空间.
4. SimScenario中createHosts函数创建了host, 非常重要.
5. 有两种接口, 一种是蓝牙接口, 一种的高速接口, 可查看setting.txt文件,两者默认只有传输速度不一样
6. NetworkInterface 中定义了获得邻居节点的方法
