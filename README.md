# ucore\_Operating\_System
INTRODUCTION
============
ucore os labs was used as OS Experiments in OS Course Of Dept. of Computer Science & Technology, Tsinghua University.



CONTENTS
========

labs info
----------------
```
lab0: preparing
lab1: boot/protect mode/stack/interrupt
lab2: physical memory management
lab3: virtual memory management
lab4: kernel thread management
lab5: user process management
lab6: scheduling
lab7: mutex/sync
lab8: filesystem
```

TESTED ENVIRONMENT
==================
```
UBUNTU 14.04+: GCC-4.8.2+ CLANG-3.5+
FEDORA 20+: GCC-4.8.2+
```

EXERCISE STEPS
==============
```
0 Get the newest os lab src codes/docs.(Insure you can connect to github in ubuntu running on VrtualBox)
0.1 If you try to get all codes
  $rm -rf ucore_lab
  $git clone git://github.com/chyyuu/ucore_os_lab.git
  $cd ucore_lab
0.2 If you gloned ucore_lab and only try to get the updated codes
  $cd ucore_os_lab
  $git pull
1 $cd labX  
2 read codes (specially the modified or added files)
3 add your code
4 compile your code
  $make
5 check your code
  $make qemu
OR
  $make grade

6 debug your code
  $make debug

7 handin your code
  $make handin
```

OPTION
==============
Now, ucore suuport LLVM/Clang-3.5 + 
in step4:
  $ USELLVM=1 make
then you will use clang to compile ucore

 
RESOURCE REPOSITORY
===================
```
Basic OS labs (for students who learn OS course)
The newest lab codes and docs is in https://github.com/chyyuu/ucore_os_lab

Advanced OS labs (for OS geeks or hackers or guys with Superman/Master Rank)
The newest lab codes and docs is in https://github.com/chyyuu/ucore_plus
```




OTHER INFO
==========
ucore is a teaching OS which is derived from xv6&jos in MIT, OS161 in Harvard and Linux.

ucore was developed and used in Department of Computer Science & Technology, Institute for Interdisciplinary Information Sciences, Tsinghua University.

The codes in the files that constitute xv6&jos are Copyright (2006-Current) Frans Kaashoek, Robert Morris, and Russ Cox and uses MIT License.

The codes in the files that constitute OS/161 are written by David A. Holland.

The codes in the files that constitute ucore are Copyright (2010-Current) Yu Chen, Naizheng Wang, Yong Xiang and uses GPL License.

The documents in the files that constitute ucore are Copyright (2010-Current) Yu Chen, Yong Xiang and uses Creative Commons Attribution/Share-Alike (CC-BY-SA) License. 


