# sentinel
write some code demo while learning Sentinel

## 学习资料      
   - [官网](https://cloud.spring.io/spring-cloud-gateway/reference/html)
   - [教程1](https://blog.csdn.net/noaman_wgs/article/details/103328793)
   - [教程2](https://www.jianshu.com/p/c47dfd25eeee)
   
###教程   
####1.下载可执行 jar 包
   [下载地址](https://github.com/alibaba/Sentinel/releases)
    
####2.引入 transport 依赖
    <dependency>
        <groupId>com.alibaba.csp</groupId>
        <artifactId>sentinel-transport-simple-http</artifactId>
        <version>x.y.z</version>
    </dependency>
    
####3.配置 JVM 启动参数：
    -Dproject.name=sentinel-demo -Dcsp.sentinel.dashboard.server=127.0.0.1:8080 -Dcsp.sentinel.api.port=8719
    


