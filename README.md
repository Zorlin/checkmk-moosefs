# checkmk-moosefs
MooseFS checks for CheckMK.

## TODO
* Check number of missing chunks (CRIT if > 0)
* Check number of endangered chunks (WARN if > 0, CRIT if > 100000)
* Check number of chunkservers matches the expected number
* Check number of masters matches the expected number
* Check that master name is resolvable
