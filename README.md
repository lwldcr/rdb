# rdb [![Build Status](https://travis-ci.org/cupcake/rdb.png?branch=master)](https://travis-ci.org/cupcake/rdb)

## fork updates
modify checkHeader for higher version of rdb files to avoid such error:
> Fatal error: rdb: invalid RDB version number 8

the following is mainly from the **original README**

rdb is a Go package that implements parsing and encoding of the
[Redis](http://redis.io) [RDB file
format](https://github.com/sripathikrishnan/redis-rdb-tools/blob/master/docs/RDB_File_Format.textile).

This package was heavily inspired by
[redis-rdb-tools](https://github.com/sripathikrishnan/redis-rdb-tools) by
[Sripathi Krishnan](https://github.com/sripathikrishnan).

[**Documentation**](http://godoc.org/github.com/cupcake/rdb)

## Installation

```
go get github.com/lwldcr/rdb
```
