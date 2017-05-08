Misc utilities for gathering data about directory trees

The gendirstat script can be used to create a cache file for viewing by
[qdirstat](https://github.com/shundhammer/qdirstat) or as in input to 
[parsync](http://moo.nac.uci.edu/~hjm/parsync/) for data movement.  

An infomative way to run it is:
```
gendirstat dir1 dir2... > gencache.log 2>&1
```

This gives you a log file that list the time it took to create the cache.
That is the time it took to walk the directory tree.
