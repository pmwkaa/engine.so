
### Embeddable data storage engines

Tracking, Benchmarking and Sharing Information about an open source [embedded data storage engines](https://en.wikipedia.org/wiki/Embedded_database),
internals, architectures, data storage and transaction processing.

If you would like to share a material or make a correction, please use [GitHub](http://github.com/pmwkaa/engine.so) or contact me
by [Email](mailto:pmwkaa@gmail.com).

| name | language | license | storage | description |
|---|---|---|---|---|
| [Berkeley DB](http://www.oracle.com/technetwork/database/database-technologies/berkeleydb/overview/index.html) | C | AGPLv3 or Proprietary | B-Tree, Hash | Berkeley DB (BDB) is a software library that provides a high-performance embedded database for key/value data. |
| [Tokyo/Kyoto Cabinet](http://fallabs.com/kyotocabinet/) | C++ | GPLv2.1 / GPLv3 w/ compatibility exceptions | B-Tree, Hash | Tokyo Cabinet and Kyoto Cabinet are two libraries of routines for managing key-value databases. |
| [SQLite](https://sqlite.org/) | C | Public Domain | B-Tree, LSM | SQLite is a relational database management system contained in a C programming library. |
| [UnQLite](http://unqlite.org/) | C | 2-Clause BSD (Simplified) | Hash | UnQLite is a in-process software library which implements a self-contained, serverless, zero-configuration, transactional NoSQL database engine. |
| [LevelDB](https://github.com/google/leveldb) | C++ | 3-Clause BSD (New/Revised) | LSM | LevelDB is an open source on-disk key-value store written by Google. |
| [LevelDB by Basho](https://github.com/basho/leveldb) | C++ | 3-Clause BSD (New/Revised) | LSM | A fork of LevelDB modified to benefit the Riak environment. |
| [LevelDB by HyperDex](https://github.com/rescrv/HyperLevelDB) | C++ | 3-Clause BSD (New/Revised) | LSM | A fork of LevelDB intended to meet the needs of HyperDex while remaining compatible with LevelDB. |
| [RocksDB](http://rocksdb.org) | C++ | Apache v2 or GPLv2 | LSM | RocksDB is an embeddable persistent key-value store for fast storage from Facebook. (LevelDB by Facebook) |
| [Sophia](http://sophia.systems) | C | 2-Clause BSD (Simplified) | Sophia | Sophia is an advanced transactional MVCC key-value/row storage library. |
| [WiredTiger](http://wiredtiger.com) | C | GPLv2 or GPLv3 | B-Tree, LSM | WiredTiger is a high performance, scalable, production quality, NoSQL, Open Source extensible platform for data management. |
| [Percona/TokuFT](https://github.com/percona/perconaft) | C++ | GPLv2 or AGPLv3 | Fractal Tree | PerconaFT is a high-performance, transactional key-value store. |
| [ForestDB](https://github.com/couchbase/forestdb) | C++ | Apache v2 | HB+-Trie | Forestdb - A Fast Key-Value Storage Engine Based on Hierarchical B+-Tree Trie. |
| [Sparkey](https://github.com/spotify/sparkey) | C | Apache v2 | Hash | Simple constant key/value storage library, for read-heavy systems with infrequent large bulk inserts. |
| [MDBM](https://github.com/timrc-git/mdbm) | C | 3-Clause BSD (New/Revised) | Hash | MDBM is a fast memory-mapped DBM clone by Yahoo. |
| [LMDB](http://symas.com/mdb) | C | OpenLDAPv2.8 (BSD-style) | B-Tree | Lightning Memory-Mapped Database (LMDB) is a software library that provides a high-performance embedded transactional database in the form of a key-value store. |
| [MDBX](https://github.com/ReOpen/libmdbx) | C | OpenLDAPv2.8 (BSD-style) | B-Tree | Modified version of LMDB (Symas Lightning Memory-Mapped Database) |
| [NessDB](https://github.com/bohutang/nessdb) | C | "BSD" | Buffered-Tree | A very fast transactional key-value, embedded database storage engine. |
| [Vedis](http://vedis.symisc.net/) | C | Sleepycat (GPL-style) or Proprietary | Hash | Vedis is an embeddable datastore C library built with over 70 commands similar in concept to Redis but without the networking layer. |
| [Rlite](https://github.com/seppo0010/rlite) | C | 2-Clause BSD (Simplified) | Hash | Self-contained, serverless, zero-configuration, transactional Redis-compatible database engine. |
| [SkipDB](https://github.com/stevedekorte/skipdb) | C | 3-Clause BSD (New/Revised) | Skip List | Small, portable, ACID, C implemented BDB style database based on skiplists instead of b-trees. |
| [EJDB](http://ejdb.org) | C | LGPLv2.1 | B-Tree, Hash | Embedded JSON Database engine C library. |
| [UpscaleDB](http://upscaledb.org) | C | Apache v2.0 | B-Tree | A very fast lightweight embedded database engine with built-in analytic functions. |
| [Eblob](http://reverbrain.com/eblob/) | C | LGPLv3 | | Eblob is an append-only low-level IO library, which saves data in blob files. |
| [WhiteDB](http://whitedb.org) | C | GPLv3 or Proprietary or Royalty Free w/ Conditions | Hash | WhiteDB is a lightweight NoSQL database library written in C, operating fully in main memory. |
| [Beringei](https://github.com/facebookincubator/beringei) | C++ | 3-Clause BSD (New/Revised) | TimeSeries | Beringei is a high performance, in-memory storage engine for time series data. |

**Benchmarking**

| name | description |
|---|---|
| [IOArena](http://github.com/pmwkaa/ioarena.git) | IOArena is an utility designed for evaluating performance of embedded databases. |
