### 下载启动consul包
下载 https://www.consul.io/downloads <br>
执行
```
consul agent -dev
```
查看Web UI: http://localhost:8500

### 启动provider服务
前台查看services是否注册成功

### 启动consumer服务
访问 localhost:8521/services 查询注册的consumer
