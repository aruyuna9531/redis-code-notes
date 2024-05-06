# redis 源码阅读笔记（基于redis 7.2.4版本）

## [（1）数据结构篇](1.data_structures.md)

## [（2）持久化相关](2.persistence.md)：RDB/AOF

## [（3）集群](3.clusters.md)：主从/哨兵/cluster

## [（4）Redis是单线程模型？](4.single_thread.md)

## [（5）过期键回收](5.free.md)

## [（6）事务 ](6.transaction.md)：multi VS eval

主程序main入口：[server.c:6889](https://github.com/redis/redis/blob/unstable/src/server.c)