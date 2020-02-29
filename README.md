# Web服务器

#### 一个运行于Linux平台上的Web服务器,使用C++11编写，实现了对GET,POST等基本请求的解析和响应

## 技术点
#### 异步Reactor架构，基于事件驱动和回调
#### 设置套接字选项SO_REUSEPORT使用多线程接受连接
#### 使用线程池管理线程
#### 设置读写缓冲区，注册相应的回调函数处理数据
#### 使用智能指针管理对象避免内存泄露

## 使用说明
#### 本项目使用cmake编译,确保你能够使用它
```
cd src
cmake .
make
./WebServer
```