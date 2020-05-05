# MonadFail

This branch fixes an error while compiling distributed-process with GHC 8.8.3:

```
Could not deduce (MonadFail Process) arising from a use of ‘fail’
```

Fixed by applying the suggestion as seen here:
https://github.com/haskell-distributed/distributed-process/issues/345

# distributed-process
[![travis](https://secure.travis-ci.org/haskell-distributed/distributed-process.png)](http://travis-ci.org/haskell-distributed/distributed-process)
[![Release](https://img.shields.io/hackage/v/distributed-process.svg)](https://hackage.haskell.org/package/distributed-process)

This repository is part of Cloud Haskell.

See http://haskell-distributed.github.com for documentation, user guides,
tutorials and assistance.

## Getting Help / Raising Issues

Please visit the [bug tracker](https://github.com/haskell-distributed/distributed-process/issues) to submit issues. You can contact the distributed-haskell@googlegroups.com mailing list for help and comments.

## License

This package is made available under a 3-clause BSD-style license.
