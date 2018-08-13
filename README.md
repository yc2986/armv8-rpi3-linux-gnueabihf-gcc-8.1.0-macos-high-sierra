# GCC 8.1.0 armv8-rpi3-linux-gnueabihf cross compiler for macOS High Sierra

## Host Info
Info retrieved from ```Apple -> About This Mac```
- **Model**: MacBook Pro (Retina, 15-inch, Mid 2015)
- **CPU**: 2.5 GHz Intel Core i7
- **Memory**: 6 GB 1600 MHz DDR3
- **OS**: macOS High Sierra 10.13.6 (17G65)

## Target Info
- **Model**: Raspberry Pi 3 Model B
- **CPU**  
  Info retreived from ```cat /proc/cpuinfo```
  - **Processor**: 4
  - **Hardware**: BCM2835
  - **Revision**: a02082
  - **Model name**: ARMv7 Processor rev4 (v7l)
- **Memory**  
  Info retreived from ```free -m```
  - **Total RAM**: 927MB
  - **Package List RAM**: 1GB
- **OS**  
  Info retrieved from ```cat /etc/os-release``` and ```cat /proc/version```
  - **Distro**: Raspbian GNU/Linux 9 (stretch)
  - **Linux version**: Linux version 4.14.52-v7+ (dc4@dc4-XPS13-9333) (gcc version 4.9.3 (crosstool-NG crosstool-ng-1.22.0-88-g8460611)) #1123 SMP

## Generated toolchain
- **gcc/g++**: 8.1.0
- **gdb**: 8.1

## Build environment
- **Volume for build**: */Volumes/xtool-build-env/* *APFS Volume • APFS (Case-sensitive)*
- **Volume for install**: */Volumes/xtool-build-env/* *APFS Volume • APFS (Case-sensitive)*
- **Patches directory**: */Volumes/xtool-build-env/packages/* All patches pulled from [HERE](https://github.com/crosstool-ng/crosstool-ng/tree/master/packages)
- **ct-ng config file**: [.config](https://github.com/yc2986/armv8-rpi3-linux-gnueabihf-gcc-8.1.0-macos-high-sierra/blob/master/.config)