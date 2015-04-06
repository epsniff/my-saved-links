

### Go Embeddable DBs
- https://github.com/customerio/esdb esdb - Event-stream flat file database - Immutable storage for timestamped event streams
- https://github.com/benbjohnson/bolt - Bolt is good for read intensive workloads. Sequential write performance is also fast but random writes can be slow. 
   - example of using boltdb and bloomfilter as a database : https://github.com/AndreasBriese/ipLocator/blob/master/ipLocator.go 
- RocksDB - https://github.com/facebook/rocksdb 
   - example: https://github.com/cockroachdb/cockroach/blob/8a4f06a6d04825a683b86bbd361ddb9094691629/storage/engine/rocksdb.go
- https://code.google.com/p/leveldb-go/source/checkout - leveldb
- https://github.com/HouzuoGuo/tiedot 
- https://github.com/couchbase/forestdb 
- https://github.com/cznic/ql - pure go embedded sql
- https://github.com/siddontang/go-tokuft/tree/master/tokuft
   - http://highscalability.com/blog/2014/8/6/tokutek-white-paper-a-comparison-of-log-structured-merge-lsm.html
   - https://github.com/Tokutek
   - http://www.tokutek.com/mongodb-performance/
   - https://github.com/Tokutek/ft-index

###  File Formats 
http://www.semantikoz.com/blog/orc-intelligent-big-data-file-format-hadoop-hive/  - ORC files used by hive for fast indexing.
