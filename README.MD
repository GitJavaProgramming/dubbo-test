# 高效RPC
    快速建立连接
    序列化与反序列化的效率
# Dubbo
    官网： http://dubbo.apache.org/zh-cn/index.html
    
    特性：        
    面向接口代理的高性能RPC调用
    智能负载均衡
    服务自动注册与发现
    高度可扩展能力
    运行期流量调度
    可视化的服务治理与运维
    
    服务提供者和消费者
        抽象出公共的服务接口和数据模型
        
        提供者：应用--注册中心--通信协议--暴露服务接口--暴露服务接口实现 
        消费者：应用--注册中心--引用要消费的接口
        
    springboot与dubbo整合三种方式
        1. dubbo注解形式 @Service、@Reference  依赖IDE编译器检查
        2. xml配置文件形式管理依赖  xml文档校验
        3. javaConfig spring注解扫描 @Bean @Configuration  java代码编译时检查
        
    服务调用示例：
        负载均衡
        熔断降级
        调用检查
        。。。

# 服务管理
    admin
    monitor