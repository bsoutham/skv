This is a fork of [SKV](https://godoc.org/github.com/rapidloop/skv)

This has been modified to move from [BoltDB] (https://github.com/boltdb/bolt) which has been deprecated to [BBoltDB] (https://github.com/etcd-io/bbolt)
It has a new method "GetKeys" added that returns a list of keys stored in the DB.

It also has been modified to use go modules.


# skv

`skv` is a Simple Key-Value store for Go.

Check the [blog
post](https://www.opsdash.com/blog/persistent-key-value-store-golang.html)
for a description of skv internals.

Package documentation is available [here](https://godoc.org/github.com/rapidloop/skv).



