# 下载
* windows版： [https://github.com/MSOpenTech/redis/releases](https://github.com/MSOpenTech/redis/releases)

# 安装-启动
## 解压
下载完成后，在C盘【Program Files】目录下新建文件夹【Redis】，右键解压Redis ZIP包，把所有文件解压到redis文件夹中。

## 文件介绍
* redis-benchmark.exe #基准测试
* redis-check-aof.exe # aof Append-only file 
* redischeck-dump.exe # dump
* redis-cli.exe # 客户端
* redis-server.exe # 服务器
* redis.windows.conf # 配置文件

## 启动Redis
使用命令`redis-server.exe redis.windows.conf`，启动redis 服务。

## 测试
新打开一个doc窗口，用自带的客户端工具进行测试命令`redis-cli.exe`。


