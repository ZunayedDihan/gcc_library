# GCC Library-Manifest
* Commands/Guide:

```bash
gcc -v
```
```bash
sudo apt update
```
```bash
sudo apt install build-essential
```
```bash
sudo apt-get install manpages-dev
```
```bash
sudo apt install software-properties-common
```
```bash
sudo add-apt-repository ppa:ubuntu-toolchain-r/test
```
```bash
sudo apt install gcc-7 g++-7 gcc-8 g++-8 gcc-9 g++-9
```
```bash
sudo apt-get update
```
```bash
sudo apt install gcc-10
```
```bash
sudo apt install g++-10
```
```bash
sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-9 90 --slave /usr/bin/g++ g++ /usr/bin/g++-9 --slave /usr/bin/gcov gcov /usr/bin/gcov-9
```
```bash
sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-8 80 --slave /usr/bin/g++ g++ /usr/bin/g++-8 --slave /usr/bin/gcov gcov /usr/bin/gcov-8
```
```bash
sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-7 70 --slave /usr/bin/g++ g++ /usr/bin/g++-7 --slave /usr/bin/gcov gcov /usr/bin/gcov-7
```
```bash
sudo update-alternatives — install /usr/bin/gcc gcc /usr/bin/gcc-4.9 100 --slave /usr/bin/g++ g++ /usr/bin/g++-4.9 --slave /usr/bin/gcov gcov /usr/bin/gcov-4.9
```
```bash
sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-4.9 100 --slave /usr/bin/g++ g++ /usr/bin/g++-4.9
```

From this point forward, the only thing required when switching compilers is this (relatively) simple command:
```bash
sudo update-alternatives --config gcc
```

Install app eddy: https://github.com/donadigo/eddy  

https://appcenter.elementary.io/com.github.donadigo.eddy/  

https://linoxide.com/linux-how-to/eddy-install-debian-packages-elementary/


Sources: https://medium.com/@orhanakal/install-gcc-4-9-and-g-4-9-on-ubuntu-18-04-6888b92e5bab

https://linuxize.com/post/how-to-install-gcc-compiler-on-ubuntu-18-04/

http://charette.no-ip.com:81/programming/2011-12-24_GCCv47/

https://medium.com/@orhanakal/install-gcc-4-9-and-g-4-9-on-ubuntu-18-04-6888b92e5bab

# GCC Linaro

```bash
sudo apt-get install aptitude
```
```bash
sudo apt-get install gcc-multilib
```
```bash
nano ~/.bashrc
```
```bash
PATH=$PATH:/home/user/bin/android_prebuilts_gcc_linux-
x86_aarch64_aarch64-linux-gnu-4.9.4-9.0/bin/
```

```bash
nano ~/.bashrc
```
```bash
PATH=$PATH:/home/user/bin/gcc-arm-none-eabi-4_9-2015q3/bin/
```

Sources:
https://www.linaro.org/downloads/

https://snapshots.linaro.org/components/toolchain/gcc-linaro/

https://launchpad.net/gcc-arm-embedded

https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm

http://gcc.gnu.org/

https://gcc.gnu.org/onlinedocs/

https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm/downloads

https://launchpad.net/gcc-arm-embedded/+series

https://launchpad.net/gcc-arm-embedded/4.9/4.9-2015-q3-update

https://launchpad.net/gcc-arm-embedded/4.9

https://github.com/crdroidmod/android_prebuilts_gcc_linux-x86_aarch64_aarch64-linux-gnu-4.9.4






