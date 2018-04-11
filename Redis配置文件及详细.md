# Redis配置文件及详细  
## 配置redis.properties

redis.host=127.0.0.1
redis.port=6379
redis.pass=123456
redis.maxIdle=300
redis.maxActive=600
redis.maxWait=1000
redis.testOnBorrow=true

maxIdle，最大空闲数，数据库连接的最大空闲时间。超过空闲时间，数据库连接将被标记为不可用，然后被释放。设为0表示无限制。
MaxActive，连接池的最大数据库连接数。设为0表示无限制。
maxWait ，最大建立连接等待时间。如果超过此时间将接到异常。设为-1表示无限制。
