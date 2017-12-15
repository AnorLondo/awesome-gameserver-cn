# 游戏服务器资源大全
***
### 目录
- [游戏服务器资源大全]()
    - [网络](#网络)
    - [协议](#协议)
    - [持久化](#持久化)
    - [Log](#Log)
    - [游戏AI](#游戏AI)
    - [开源服务器](#开源服务器)

### 网络
*网络相关的库和工具*
* Java
    * [Netty](https://github.com/netty/netty) - Netty是一个高性能、异步事件驱动的NIO框架，它提供了对TCP、UDP和文件传输的支持
    * [Mina](https://github.com/apache/mina) - Apache Mina是一个能够帮助用户开发高性能和高伸缩性网络应用程序的框架
* C++
    * [libevent](http://libevent.org/) - libevent是一个轻量级的基于事件驱动的高性能的开源网络库,并且支持多个平台
    * [libev](http://software.schmorp.de/pkg/libev.html) - 较libevent而言，设计更简练，性能更好，但对Windows支持不够好
    * [libuv](https://github.com/libuv/libuv) - libuv 是 Node 的新跨平台抽象层,用于抽象 Windows 的 IOCP 及 Unix 的 libev
* Python
    * [Twisted](http://twistedmatrix.com/) - Twisted是用Python实现的基于事件驱动的网络引擎框架
    * [Gevent](http://www.gevent.org/) - Gevent是一种基于协程的Python网络库，它用到Greenlet提供的，封装了libevent事件循环的高层同步API
* Erlang
    * [ranch](https://github.com/ninenines/ranch) - cowboy 项目下的Tcp网络库
* C#
    * [DotNetty](https://github.com/Azure/DotNetty) - netty 的C#版

### 协议
*协议*
* [protobuf](https://github.com/google/protobuf) - 大家都知道的protobuf
* [FlatBuffers](https://github.com/google/flatbuffers) - Google出品，专门为游戏开发或其他性能敏感的应用程序需求而创建
* [Json](http://www.json.org/) - 这个算凑数吗？
* [MessagePack](https://msgpack.org/) - It's like JSON. but fast and small.

### 持久化
*持久化框架*
* Java
    * [MyBatis](https://github.com/mybatis/mybatis-3) - 一个支持普通SQL查询,存储过程和高级映射的优秀持久层框架
* C#
    * [Dapper](https://github.com/StackExchange/Dapper) - 是一款轻量级ORM框架
* Erlang
    * [mysql-otp](https://github.com/mysql-otp/mysql-otp) -  MySQL driver for Erlang/OTP

### Log
*Log*
* C#
    * [NLog](https://github.com/NLog/NLog) - 支持多平台的C# log库
* Erlang 
    * [Lager](https://github.com/erlang-lager/lager) - A logging framework for Erlang/OTP

### 游戏AI 
*游戏AI*
* [gdx-ai](https://github.com/libgdx/gdx-ai) - libgdx下的一个ai系统（非常适合参考学习） 
* [recastnavigation](https://github.com/recastnavigation/recastnavigation) - 非常高效的寻路系统，和Unity的寻路算法几乎一样
* [Serpent.AI](https://github.com/SerpentAI/SerpentAI) - 游戏代理框架，适合写外挂
* [https://github.com/Tencent/behaviac/](https://github.com/Tencent/behaviac/) - 腾讯开源的行为树框架

### 开源服务器
*各种开源游戏服务器*
* [pomelo](https://github.com/NetEase/pomelo) - 网易出品的Node.js游戏服务器框架
* [skynet](https://github.com/cloudwu/skynet) - 云风大神出品Lua游戏服务器框架
* [Scut](https://github.com/ScutGame/Scut) - support C#/Python/Lua 可惜两年没有更新了
* [NoahGameFrame](https://github.com/ketoo/NoahGameFrame) - 一个支持分布式的C++游戏服务器框架
* [TrinityCore](https://github.com/TrinityCore/TrinityCore) - MMO游戏服务器框架,开源的魔兽服务器
* [ryzomcore](https://github.com/ryzom/ryzomcore) - 分布式的游戏服务器，ryzom 的官方开源
* [kbengine](https://github.com/kbengine/kbengine) - 一款开源的MMOG游戏服务端引擎， 仅Python脚本即可简单高效的完成任何游戏逻辑(支持热更新)
* [mqant](https://github.com/liangdas/mqant) - mqant是一款基于Golang语言的简洁,高效,高性能的分布式游戏服务器框架
* [MaNGOS](https://github.com/mangos/MaNGOS) - 开源的魔兽服务器
