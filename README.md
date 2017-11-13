# Legacy-MEI
Legacy Intel MEI driver for Kernel 2.6.32
<br />
To compile, type:<br />
<br />
$ cd src <br />
$ make -C /path/to/linux-2.6.32-src M=&#96;pwd&#96; modules <br />
$ depmod -a <br />
<br />
or
<br />
<br />
$ cd src <br />
$ make -C /lib/modules/&#96;uname -r&#96;/build M=&#96;pwd&#96; modules <br />
$ depmod -a <br />
