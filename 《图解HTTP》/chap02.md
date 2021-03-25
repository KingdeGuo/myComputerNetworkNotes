# 简单的HTTP协议

- TCP
  
  - 字节流
  - 以报文段为单位
  - 可靠传输
  
- HTTP
  
  - 无状态
  
- HTTP方法
  - GET：获取资源
  - POST：传输实体主体
  - PUT：传输文件
  - HEAD：获取报文首部
  - DELETE：删除文件
  - OPTIONS：询问支持的方法
  - TRACE：追踪路径
  - CONNECT：要求用隧道协议连接代理
  
- 三次握手

  - ->  syn
  - syn/ack  <-
  - ->  ack

- 四次挥手

  - fin  <-
  - ->  ack
  - ->  fin
  - ack  <-

- 持久化连接

  - 持久连接
  - 管线化

  
