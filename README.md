
![engine.so](http://engine.so/logo.svg)

#Embeddable data storage engines.

Tracking, Benchmarking and Sharing Information about an open source [embedded data storage engines](https://en.wikipedia.org/wiki/Embedded_database),
internals, architectures, data storage and transaction processing.

If you would like to share a material or make a correction, please use [GitHub](http://github.com/pmwkaa/engine.so) or contact me
by [Email](mailto:pmwkaa@gmail.com).

##Storage Engines

| name | language | storage | description |
|---|---|---|---|
| [Berkeley DB](http://www.oracle.com/technetwork/database/database-technologies/berkeleydb/overview/index.html) | C | B-Tree, Hash | Berkeley DB (BDB) is a software library that provides a high-performance embedded database for key/value data. |
| [SQLite](https://sqlite.org/) | C | B-Tree, LSM | SQLite is a relational database management system contained in a C programming library. |
| [UnQLite](http://unqlite.org/) | C | Hash | UnQLite is a in-process software library which implements a self-contained, serverless, zero-configuration, transactional NoSQL database engine. |
| [LevelDB](https://github.com/google/leveldb) | C++ | LSM | LevelDB is an open source on-disk key-value store written by Google. |
| [LevelDB by Basho](https://github.com/basho/leveldb) | C++ | LSM | A fork of LevelDB modified to benefit the Riak environment. |
| [LevelDB by HyperDex](https://github.com/rescrv/HyperLevelDB) | C++ | LSM | A fork of LevelDB intended to meet the needs of HyperDex while remaining compatible with LevelDB. |
| [RocksDB](https://rocksdb.org) | C++ | LSM | RocksDB is an embeddable persistent key-value store for fast storage from Facebook. (LevelDB by Facebook) |
| [Sophia](http://sphia.org) | C | Sophia | Modern embeddable transactional key-value storage. |
| [WiredTiger](http://wiredtiger.com) | C | B-Tree, LSM | WiredTiger is a high performance, scalable, production quality, NoSQL, Open Source extensible platform for data management. |
| [Percona/TokuFT](https://github.com/percona/perconaft) | C++ | Fractal Tree | PerconaFT is a high-performance, transactional key-value store. |
| [ForestDB](https://github.com/couchbase/forestdb) | C++ | HB+-Trie | Forestdb - A Fast Key-Value Storage Engine Based on Hierarchical B+-Tree Trie. |
| [Tokyo/Kyoto Cabinet](http://fallabs.com/kyotocabinet/) | C++ | B-Tree, Hash | Tokyo Cabinet and Kyoto Cabinet are two libraries of routines for managing key-value databases. |
| [LMDB](http://symas.com/mdb) | C | B-Tree | Lightning Memory-Mapped Database (LMDB) is a software library that provides a high-performance embedded transactional database in the form of a key-value store. |
| [MDBX](https://github.com/ReOpen/libmdbx) | C | B-Tree | Modified version of LMDB (Symas Lightning Memory-Mapped Database) |
| [NessDB](https://github.com/bohutang/nessdb) | C | Buffered-Tree | A very fast transactional key-value, embedded database storage engine. |
| [Vedis](http://vedis.symisc.net/) | C | Hash | Vedis is an embeddable datastore C library built with over 70 commands similar in concept to Redis but without the networking layer. |
| [Rlite](https://github.com/seppo0010/rlite) | C | Self-contained, serverless, zero-configuration, transactional Redis-compatible database engine. |
| [EJDB](http://ejdb.org) | C | B-Tree, Hash | Embedded JSON Database engine C library. |
| [UpscaleDB](http://upscaledb.org) | C | B-Tree | A very fast lightweight embedded database engine with built-in analytic functions. |
| [Eblob](http://reverbrain.com/eblob/) | C | | Eblob is an append-only low-level IO library, which saves data in blob files. |
| [WhiteDB](http://whitedb.org) | C | Hash | WhiteDB is a lightweight NoSQL database library written in C, operating fully in main memory. |

##Benchmarking

| name | description |
|---|---|
| [IOArena](http://github.com/pmwkaa/ioarena.git) | IOArena is an utility designed for evaluating performance of embedded databases. |

##Papers

| name | year | description |
|---|---|---|
| [Organization and maintenance of large ordered indexes](http://www.minet.uni-jena.de/dbis/lehre/ws2005/dbs1/Bayer_hist.pdf) | 1972 | Organization and maintenance of an index for a dynamic random access file is considered. The pages of the index are organized in a special data-structure, so-called B-trees. |
| [The Log-Structured Merge-Tree (LSM-Tree)](http://www.cs.umb.edu/~poneil/lsmtree.pdf) | 1996 | The LSM tree is a data structure with performance characteristics that make it attractive for providing indexed access to files with high insert volume, such as transactional log data. |
| [The Buffer Tree: A Technique for Designing Batched External Data Structures](http://cs.au.dk/~large/Papers/bufferalgo.pdf) | 2003 | A technique for designing external memory data structures that support batched operations I/O efficiently. |
| [Stratified B-trees and Versioned Dictionaries](https://www.usenix.org/legacy/event/hotstorage11/tech/final_files/Twigg.pdf) | 2011 | The 'Stratified B-tree' is the first versioned dictionary offering fast updates and an optimal tradeoff between space, query and update costs. |
| [Anti-Caching: A New Approach to Database Management System Architecture](http://www.vldb.org/pvldb/vol6/p1942-debrabant.pdf) | 2013 | To overcome the restriction that all data fit in main memory, we propose a new technique, called anti-caching, where cold data is moved to disk in a transactionally-safe manner as the database grows in size. |
| [A Comparison of Fractal Trees to Log-Structured Merge (LSM) Trees](http://insideanalysis.com/wp-content/uploads/2014/08/Tokutek_lsm-vs-fractal.pdf) | 2014 | This paper explains the advantages of Fractal-Tree (R) indexing compared to Log-Structured Merge (LSM) trees. |
| [Log-structured Memory for DRAM-based Storage](https://www.usenix.org/system/files/conference/fast14/fast14-paper_rumble.pdf) | 2014 | A log-structured approach to memory management allows 80-90% memory utilization while offering high performance. |
| [Rethinking SIMD Vectorization for In-Memory Databases](http://www.cs.columbia.edu/~orestis/sigmod15.pdf) | 2015 | In this paper, we present novel vectorized designs and implementations of database operators, based on advanced SIMD operations, such as gathers and scatters, study selections, hash tables, and partitioning. |
