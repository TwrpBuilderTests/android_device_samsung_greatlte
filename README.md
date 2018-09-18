# TWRP device tree for Samsung Note8 aka greatlte
Kernel source available at 
https://github.com/devkingsteam/android_kernel_samsung_universal8895/tree/twrp-se9.0
```
export CROSS_COMPILE=../toolchains/aarch64-linux-android-4.9/bin/aarch64-linux-android-
make clean

export ARCH=arm64
export ANDROID_MAJOR_VERSION=o
export LOCALVERSION=-twrp

make ARCH=arm64 exynos8895-greatlte_defconfig
make ARCH=arm64 -j128
```
