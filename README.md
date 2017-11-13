# Legacy-MEI
Legacy Intel MEI driver for Kernel 2.6.32
<br />
To compile, type:<br />
<br />
$ cd src <br />
$ make -C /path/to/linux-2.6.32-src M=`pwd` modules <br />
$ depmod -a `uname -r` <br />
<br />
or
<br />
<br />
$ cd src <br />
$ make -C /lib/modules/$(uname -r)/build M=`pwd` modules <br />
$ depmod -a <br />
