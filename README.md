# Springcloud-config
springcloud-config 的配置中心

访问：
    http://127.0.0.1:3344/master/config-dev.yml

修改配置后，运维人员需要刷新：
    curl -X POST "http://localhost:3355/actuator/refresh"