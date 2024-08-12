# kv-projects

kv类项目

# 列表

## kv存储引擎（单机kv/嵌入式/库)

|    项目名称    |                                    项目地址 | 是否生产可用 | 主要开发语言 |                     说明 | 
|:----------:|----------------------------------------:|-------:|-------:|-----------------------:|
|  leveldb   |       https://github.com/google/leveldb |      是 |    c++ |               lsm-tree |
|  rocksdb   |     https://github.com/facebook/rocksdb |      是 |    c++ |  lsm-tree，fork自leveldb |
| toplingdb  |    https://github.com/topling/toplingdb |      是 |    c++ |    lsm-tree，上游为rocksdb |
|    lmdb    |            https://github.com/LMDB/lmdb |        |      c |                 bwtree |
|    sled    |        https://github.com/spacejam/sled |        |   rust |                 bwtree |
|    redb    |         https://github.com/cberner/redb |        |   rust |               lsm-tree |
| leveldb-rs | https://github.com/dermesser/leveldb-rs |        |   rust |               lsm-tree |
|  mini-lsm  |       https://github.com/skyzh/mini-lsm |      否 |   rust |               lsm-tree |
|   rosedb   |    https://github.com/rosedblabs/rosedb |        |     go |                bitmask |
|   FASTER   |     https://github.com/microsoft/FASTER |      是 | c#/c++ | 包括FASTER Log和FASTER KV |
|  lotusdb   |  https://github.com/lotusdblabs/lotusdb |        |     go |       lsm-tree和b+ tree |


## 分布式kv

|   项目名称    |                                   项目地址 | 是否生产可用 | 主要开发语言 |               说明 |
|:---------:|---------------------------------------:|-------:|-------:|-----------------:|
|   tikv    |           https://github.com/tikv/tikv |      是 |   rust | 基于rocksdb + raft |
|   hbase   |        https://github.com/apache/hbase |      是 |   java |           基于hdfs |
| cassandra |    https://github.com/apache/cassandra |      是 |   java |                  |
|   obkv    | https://github.com/oceanbase/oceanbase |      是 |    c++ |                  |

## 兼容redis协议

|   项目名称    |                                     项目地址 | 是否生产可用 | 主要开发语言 |                                            说明 |
|:---------:|-----------------------------------------:|-------:|-------:|----------------------------------------------:|
|   redis   |           https://github.com/redis/redis |      是 |      c |                                         redis |
|  valkey   |      https://github.com/valkey-io/valkey |      是 |      c |                                    fork自redis |
|   keydb   |        https://github.com/Snapchat/KeyDB |      是 |    c++ |                                      多线程redis |
| dragonfly | https://github.com/dragonflydb/dragonfly |      是 |    c++ |                                      多线程redis |
|  garnet   |      https://github.com/microsoft/garnet |      是 |     c# |                                               |
|   ssdb    |           https://github.com/ideawu/ssdb |      是 |    c++ |                            磁盘型redis，基于leveldb |
|   pika    |          https://github.com/apache/hbase |      是 |    c++ |                            磁盘型redis，基于rocksdb |
|  kvrocks  |        https://github.com/apache/kvrocks |      是 |    c++ |                            磁盘型redis，基于rocksdb |
|  tendis   |        https://github.com/Tencent/Tendis |      是 |    c++ |                            磁盘型redis，基于rocksdb |
|   todis   |         https://github.com/topling/todis |      是 |    c++ |                磁盘型redis，基于toplingdb，fork自pika |
|   tidis   |         https://github.com/yongman/tidis |        |     go |                  proxy层协议转换，后端为tikv，proxy层纯转发 |
|  tidis2   |  https://github.com/tidb-incubator/tidis |        |   rust |                  proxy层协议转换，后端为tikv，proxy层纯转发 |
|   titea   |    https://github.com/gengmei-tech/titea |        |     go |                  proxy层协议转换，后端为tikv，proxy层纯转发 |
|   titan   |   https://github.com/distributedio/titan |        |     go |                  proxy层协议转换，后端为tikv，proxy层纯转发 |
|   modis   |       https://github.com/oceanbase/modis |        |     go |                  proxy层协议转换，后端为obkv，proxy层纯转发 |
| camellia  |   https://github.com/netease-im/camellia |        |   java | proxy层协议转换，后端支持hbase/tikv/obkv，proxy层有cache逻辑 |
