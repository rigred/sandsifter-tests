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

* AM4
    1. R7 1700x

### Intel (To Add)

#### Socket 775
* Celeron
    * Celeron 330
* Pentium 4
    * Pentium 631
    * Pentium 530/531
* Core 2 Duo
    * E8500
    * E7500
    * E5700
* Core 2 Quad
    * Core 2 Quad Q8200
    * Core 2 Quad Q9400

#### Socket 988/1150/1151/1155
* Core i5
    * i5-2500
    * i5-3220M
    * i5-3450
* Core i7
    * i7-3740QM
    * i7-4770

#### HEDT

#### Xeon

### Opteron
