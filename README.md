# SpringCloud Demo

A micro-service demo by spring cloud.

### eureka-server

服务注册中心

port: 8761


### eureka-client

服务提供者

port: 8762

通过修改 `application.yml` 中的 `server port` 并重启服务可以模拟一个集群环境

### service-ribbon

`Ribbon + RestTemplate` 实现服务间内部的 rpc 调用

port: 8764

### service-feign

`Feign` 实现服务间内部的 rpc 调用

port: 8765

### service-zuul

api网关 zuul

port: 8769

### Wiki

查看具体[Wiki](https://github.com/Sidfate/springcloud-demo/wiki)