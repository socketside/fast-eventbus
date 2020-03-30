# Netty-Sockets

Socket接入侧框架模型，支持多种协议（SocketIO、NativeTCP、UDP、UDT协议）

根据不同的客户端使用不同的协议进行接入控制，服务器对于协议可选并封装出统一的接入SideCard模型。

在不改动业务逻辑和模型接口情况下，无缝对接多种协议。

- 支持多种内置或者自定义的插件化开发，更多的协议支持
- 支持内置的责任链相关拦截器，支持更多扩展类型，比如限流、黑名单、熔断逻辑
- 支持多种SSL安全类型，或者OptionalSSL
- 支持标准及丰富的Metrics埋点和输出逻辑，默认提供Prometheus输出
- 提供Springboot-starter约定化一步集成socket模型


## Samples

- Socket-Server
- Static-web
- Socket-Client

