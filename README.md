# Legacy-MEI
Legacy Intel MEI driver for Kernel 2.6.32

To compile, type:

$ cd src
$ make -C /path/to/linux-2.6.32-src M=`pwd` modules 
$ depmod -a `uname -r`
or

$ cd src
$ make -C /lib/modules/$(uname -r)/build M=`pwd` modules 
$ depmod -a
