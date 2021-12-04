# Instant

时间线上的一个瞬时点 可能被用来记录应用程序中的时间时间戳



## 实例化

* now()    
  * 静态方法 返回默认UTC时区的Instant类的对象
* ofEpochMilli
  * 静态方法，返回在1970-01-01 00:00:00 基础上加上指定毫秒数之后的Instant的对象



## 其他

* atOffset()
  * 结合即时的偏移来创建一个OffsetDateTime
* toEpochMilli
  * 返回1970-01-01 00:00:00到当前时间的毫秒数 ，即时间戳