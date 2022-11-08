# mtbl for go

This cgo module wraps [libmtbl](https://github.com/farsightsec/mtbl) (prefer 1.3.0+). 

Value merging may still not work as expected and we recommend pre-merging values before creating mtbls with this wrapper.

Install the libmtbl dependencies on Ubuntu 22.04+ with:
```
sudo apt install libmtbl-dev
```

The mtbl utilities are useful for verification as well:
```
sudo apt install mtbl-bin
```

The original [golang-mtbl](https://github.com/edmonds/golang-mtbl) package did not have an explicit license and was forked under the same license as mtbl itself ([Apache License 2.0](https://github.com/farsightsec/mtbl/blob/master/LICENSE)).
