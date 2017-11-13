# Legacy-MEI
Legacy Intel MEI driver for Kernel 2.6.32
<br />

## Compilation
<br />
To compile, type:<br />

$ cd src <br />
$ make -C /path/to/linux-2.6.32-src M=&#96;pwd&#96; modules <br />
$ depmod -a <br />
<br />
### or
<br />

$ cd src <br />
$ make -C /lib/modules/&#96;uname -r&#96;/build M=&#96;pwd&#96; modules <br />
$ depmod -a <br />

## Installation
<br />
1. Transfer mei.ko and mei-me.ko to the target system if the compilation is done in a host machine <br />
2. Add mei in /etc/modules, or <br />
3. Execute the following command in shell <code>$ modprobe mei</code> 


