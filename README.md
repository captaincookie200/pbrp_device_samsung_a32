## Recovery Device Tree for the Samsung Galaxy A32 4G (MTK)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch omni_a32-eng
make recoveryimage
```

Blobs version:
> Kernel base: A325FXXU2BVD6

> Ramdisk, DTB, DTBO base: A325FXXU2BVD6

Kernel source:
> https://github.com/long266/android_kernel_samsung_a32/tree/s
