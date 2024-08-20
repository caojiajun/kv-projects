# kv-projects

kv类项目

# 列表

## kv存储引擎（单机kv/嵌入式/库)

|     项目名称     |                                    项目地址 | 主要开发语言 |                     说明 | 
|:------------:|----------------------------------------:|-------:|-----------------------:|
|   leveldb    |       https://github.com/google/leveldb |    c++ |               lsm-tree |
|   rocksdb    |     https://github.com/facebook/rocksdb |    c++ |  lsm-tree，fork自leveldb |
|  toplingdb   |    https://github.com/topling/toplingdb |    c++ |    lsm-tree，上游为rocksdb |
|    FASTER    |     https://github.com/microsoft/FASTER | c#/c++ | 包括FASTER Log和FASTER KV |
|     lmdb     |            https://github.com/LMDB/lmdb |      c |                 bwtree |
|     sled     |        https://github.com/spacejam/sled |   rust |                 bwtree |
|     redb     |         https://github.com/cberner/redb |   rust |               lsm-tree |
|  leveldb-rs  | https://github.com/dermesser/leveldb-rs |   rust |               lsm-tree |
|   mini-lsm   |       https://github.com/skyzh/mini-lsm |   rust |               lsm-tree |
|    rosedb    |    https://github.com/rosedblabs/rosedb |     go |                bitmask |
|   lotusdb    |  https://github.com/lotusdblabs/lotusdb |     go |       lsm-tree和b+ tree |
|   heftydb    |        https://github.com/jordw/heftydb |   java |               lsm-tree |
|   lsmtree    |    https://github.com/indeedeng/lsmtree |   java |               lsm-tree |
| leveldb-java |         https://github.com/dain/leveldb |   java |               lsm-tree |
|    tonbo     |       https://github.com/tonbo-io/tonbo |   rust |    using Apache Arrow. |
|    pebble    |   https://github.com/cockroachdb/pebble |     go |            CockroachDB |
|    badger    |     https://github.com/dgraph-io/badger |     go |            CockroachDB |


## 分布式kv

|   项目名称    |                                   项目地址 | 主要开发语言 |               说明 |
|:---------:|---------------------------------------:|-------:|-----------------:|
|   tikv    |           https://github.com/tikv/tikv |   rust | 基于rocksdb + raft |
|   hbase   |        https://github.com/apache/hbase |   java |           基于hdfs |
| cassandra |    https://github.com/apache/cassandra |   java |                  |
|   obkv    | https://github.com/oceanbase/oceanbase |    c++ |                  |

## 兼容redis协议

|   项目名称    |                                     项目地址 | 主要开发语言 |                                            说明 |
|:---------:|-----------------------------------------:|-------:|----------------------------------------------:|
|   redis   |           https://github.com/redis/redis |      c |                                         redis |
|  valkey   |      https://github.com/valkey-io/valkey |      c |                                    fork自redis |
|   keydb   |        https://github.com/Snapchat/KeyDB |    c++ |                                      多线程redis |
| dragonfly | https://github.com/dragonflydb/dragonfly |    c++ |                                      多线程redis |
|  garnet   |      https://github.com/microsoft/garnet |     c# |                                               |
|   ssdb    |           https://github.com/ideawu/ssdb |    c++ |                            磁盘型redis，基于leveldb |
|   pika    |          https://github.com/apache/hbase |    c++ |                            磁盘型redis，基于rocksdb |
|  kvrocks  |        https://github.com/apache/kvrocks |    c++ |                            磁盘型redis，基于rocksdb |
|  tendis   |        https://github.com/Tencent/Tendis |    c++ |                            磁盘型redis，基于rocksdb |
|   todis   |         https://github.com/topling/todis |    c++ |                磁盘型redis，基于toplingdb，fork自pika |
|   tidis   |         https://github.com/yongman/tidis |     go |                  proxy层协议转换，后端为tikv，proxy层纯转发 |
|  tidis2   |  https://github.com/tidb-incubator/tidis |   rust |                  proxy层协议转换，后端为tikv，proxy层纯转发 |
|   titea   |    https://github.com/gengmei-tech/titea |     go |                  proxy层协议转换，后端为tikv，proxy层纯转发 |
|   titan   |   https://github.com/distributedio/titan |     go |                  proxy层协议转换，后端为tikv，proxy层纯转发 |
|   modis   |       https://github.com/oceanbase/modis |     go |                  proxy层协议转换，后端为obkv，proxy层纯转发 |
| camellia  |   https://github.com/netease-im/camellia |   java | proxy层协议转换，后端支持hbase/tikv/obkv，proxy层有cache逻辑 |
