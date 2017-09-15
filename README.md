# sandsifter-tests
A repository of result for runs of sandsifter on various x86 CPU's

## Pull Requests with your logs welcome!

Make sure your submissions are compressed with
```
tar c data/log | xz -9 > brand_model-modelnumber.tar.xz
```
## Source code with fixes

https://github.com/rigred/sandsifter


### Test command:
```
./sifter.py --unk --dis --len --sync --tick -- -P1 -t
```

### Compression
> Log data is compressed With xz -9 and will uncompress to ~1.4Gb

## CPU's tested:

### AMD

* Zen
    * [R7 1700x](https://github.com/rigred/sandsifter-tests/blob/master/amd/Zen/ryzen-1700x.tar.xz) *dirty data as of now

### Intel

* Penryn
    * [Core2Duo P8400](https://github.com/rigred/sandsifter-tests/blob/master/intel/intel_core2duo-P8400.tar.xz)

* Haswell
    * [i3-4130T](https://github.com/rigred/sandsifter-tests/blob/master/intel/intel_i3-4130T.tar.xz) 
    * [i7-4700MQ](https://github.com/rigred/sandsifter-tests/blob/master/intel/i7-4700mq.tar.xz)
    * [E3-1225 v3](https://github.com/rigred/sandsifter-tests/blob/master/intel/intel_xeon-E3-1225-v3.tar.xz)

    
## Credits for CPU test submissions to:

[Lewiscowles1986](https://github.com/Lewiscowles1986)
[jotebe](https://github.com/jotebe)

More CPU tests incoming soon.

Submissions always welcome!
