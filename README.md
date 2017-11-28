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
> Log data is compressed With xz -9 and will uncompress to a good bit larger size
Special attention is needed with the Ryzen CPU test data. The dump files for those are near 1.4Gb total when uncompressed. 
Running this through the analysis tool will consume a substantial amount of RAM.

## CPU's tested:

### AMD

* Zen
    * [R7 1700x](https://github.com/rigred/sandsifter-tests/blob/master/amd/Zen/ryzen-1700x.tar.xz)
    * [R7 1700](https://github.com/rigred/sandsifter-tests/blob/master/amd/Zen/amd_ryzen-1700.tar.xz)

    > *Warning:* The Zen CPU logs are LARGE. Processing these with the summarizer requires a substantial amount of RAM and CPU time.

### Intel

* Prescott
    * [Intel Pentium 4 630](https://github.com/rigred/sandsifter-tests/blob/master/intel/intel_pentium_4-630.tar.xz)

* Penryn
    * [Core2Duo P8400](https://github.com/rigred/sandsifter-tests/blob/master/intel/intel_core2duo-P8400.tar.xz)

* Sandy Bridge
    * [Pentium B970](https://github.com/rigred/sandsifter-tests/blob/master/intel/intel_pentium-B970.tar.xz) //Incomplete Data. Retesting required.
    * [Core i5-2540M](https://github.com/rigred/sandsifter-tests/blob/master/intel/intel_i5-2540M.tar.xz)

* Ivy Bridge
    * [Core i3-3120m](https://github.com/rigred/sandsifter-tests/blob/master/intel/intel_i3-3120M.tar.xz)
    * [Core i5-3210m](https://github.com/rigred/sandsifter-tests/blob/master/intel/intel_i5-3210m.tar.xz)
    
* Haswell
    * [i3-4130T](https://github.com/rigred/sandsifter-tests/blob/master/intel/intel_i3-4130T.tar.xz) 
    * [i7-4700MQ](https://github.com/rigred/sandsifter-tests/blob/master/intel/i7-4700mq.tar.xz)
    * [E3-1225 v3](https://github.com/rigred/sandsifter-tests/blob/master/intel/intel_xeon-E3-1225-v3.tar.xz) Test performed in a Ubuntu VM on an ESXI host
* Devil's Canyon
    * [i7-4790k](https://github.com/rigred/sandsifter-tests/blob/master/intel/i7-4790k.tar.xz)

    
## Credits for CPU test submissions to:

* [Lewiscowles1986](https://github.com/Lewiscowles1986)
* [jotebe](https://github.com/jotebe)
* [killerkalamari](https://github.com/killerkalamari)
* [helospark](https://github.com/helospark)
* [Maxzor](https://github.com/Maxzor)

Submissions always welcome!
