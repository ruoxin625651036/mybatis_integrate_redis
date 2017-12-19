# mybatis整合redis，实现redis作为二级缓存的操作

   一级缓存：mybatis默认开启，生命周期和SqlSession一样，即：从openSession()到session.close()。
   
   二级缓存：需要自行开启，生命周期与整个应用的生命周期一样。

### 缓存与读写锁之间的关系？



