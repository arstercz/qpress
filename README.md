# qpress


This repo is a branch of the [qpress source](http://www.quicklz.com/) bringing some extra features.

Pull requests are welcome.

## features

#### delete input file with `-n` option:

```
# qpress -vnfL1K4096T4 st_test.ibd st_test.ibd.qp  
    st_test.ibd                                            
unlink st_test.ibd ok                                      
Compressed 52,711,719 bytes in 1 file(s) into 29,606,487 bytes

## error checks:
$ qpress -vnfL1K4096T4 st_test.ibd st_test.ibd.qp
    st_test.ibd     
unlink st_test.ibd error: Permission denied
```
