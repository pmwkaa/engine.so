
### Embeddable data storage engines

Tracking, Benchmarking and Sharing Information about an open source [embedded data storage engines](https://en.wikipedia.org/wiki/Embedded_database),
internals, architectures, data storage and transaction processing.

If you would like to share a material or make a correction, please use [GitHub](http://github.com/pmwkaa/engine.so) or contact me
by [Email](mailto:pmwkaa@gmail.com).

| name | language | storage | description |
|---|---|---|---|
| [Berkeley DB](http://www.oracle.com/technetwork/database/database-technologies/berkeleydb/overview/index.html) | C | B-Tree, Hash | Berkeley DB (BDB) is a software library that provides a high-performance embedded database for key/value data. |
| [Tokyo/Kyoto Cabinet](http://fallabs.com/kyotocabinet/) | C++ | B-Tree, Hash | Tokyo Cabinet and Kyoto Cabinet are two libraries of routines for managing key-value databases. |
| [SQLite](https://sqlite.org/) | C | B-Tree, LSM | SQLite is a relational database management system contained in a C programming library. |
| [UnQLite](http://unqlite.org/) | C | Hash | UnQLite is a in-process software library which implements a self-contained, serverless, zero-configuration, transactional NoSQL database engine. |
| [LevelDB](https://github.com/google/leveldb) | C++ | LSM | LevelDB is an open source on-disk key-value store written by Google. |
| [LevelDB by Basho](https://github.com/basho/leveldb) | C++ | LSM | A fork of LevelDB modified to benefit the Riak environment. |
| [LevelDB by HyperDex](https://github.com/rescrv/HyperLevelDB) | C++ | LSM | A fork of LevelDB intended to meet the needs of HyperDex while remaining compatible with LevelDB. |
| [RocksDB](http://rocksdb.org) | C++ | LSM | RocksDB is an embeddable persistent key-value store for fast storage from Facebook. (LevelDB by Facebook) |
| [Sophia](http://sophia.systems) | C | Sophia | Sophia is an advanced transactional MVCC key-value/row storage library. |
| [WiredTiger](http://wiredtiger.com) | C | B-Tree, LSM | WiredTiger is a high performance, scalable, production quality, NoSQL, Open Source extensible platform for data management. |
| [Percona/TokuFT](https://github.com/percona/perconaft) | C++ | Fractal Tree | PerconaFT is a high-performance, transactional key-value store. |
| [ForestDB](https://github.com/couchbase/forestdb) | C++ | HB+-Trie | Forestdb - A Fast Key-Value Storage Engine Based on Hierarchical B+-Tree Trie. |
| [Sparkey](https://github.com/spotify/sparkey) | C | Hash | Simple constant key/value storage library, for read-heavy systems with infrequent large bulk inserts. |
| [MDBM](https://github.com/timrc-git/mdbm) | C | Hash | MDBM is a fast memory-mapped DBM clone by Yahoo. |
| [LMDB](http://symas.com/mdb) | C | B-Tree | Lightning Memory-Mapped Database (LMDB) is a software library that provides a high-performance embedded transactional database in the form of a key-value store. |
| [MDBX](https://github.com/ReOpen/libmdbx) | C | B-Tree | Modified version of LMDB (Symas Lightning Memory-Mapped Database) |
| [NessDB](https://github.com/bohutang/nessdb) | C | Buffered-Tree | A very fast transactional key-value, embedded database storage engine. |
| [Vedis](http://vedis.symisc.net/) | C | Hash | Vedis is an embeddable datastore C library built with over 70 commands similar in concept to Redis but without the networking layer. |
| [Rlite](https://github.com/seppo0010/rlite) | C | Hash | Self-contained, serverless, zero-configuration, transactional Redis-compatible database engine. |
| [SkipDB](https://github.com/stevedekorte/skipdb) | C | Skip List | Small, portable, ACID, C implemented BDB style database based on skiplists instead of b-trees. |
| [EJDB](http://ejdb.org) | C | B-Tree, Hash | Embedded JSON Database engine C library. |
| [UpscaleDB](http://upscaledb.org) | C | B-Tree | A very fast lightweight embedded database engine with built-in analytic functions. |
| [Eblob](http://reverbrain.com/eblob/) | C | | Eblob is an append-only low-level IO library, which saves data in blob files. |
| [WhiteDB](http://whitedb.org) | C | Hash | WhiteDB is a lightweight NoSQL database library written in C, operating fully in main memory. |
| [Beringei](https://github.com/facebookincubator/beringei) | C++ | TimeSeries | Beringei is a high performance, in-memory storage engine for time series data. |

**Benchmarking**

| name | description |
|---|---|
| [IOArena](http://github.com/pmwkaa/ioarena.git) | IOArena is an utility designed for evaluating performance of embedded databases. |
