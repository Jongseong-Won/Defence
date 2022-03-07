# Defence

IP & MAC Address
--
|ID|TYPE| MAC Add | IP | Target IP | FPGA | Firmware | UI(Body) |  ETC |
|---|---|---|---|---|---|---|---|---|
|1|SPLUS-M| 0x86u | 230 | 100 |7CH 100k||SPLUS-M|Portable|
|2|SPLUS-M| 0x86u | 230 | 100 |7CH 100k||SPLUS-M|ENV Test|
|3|SODA-V(1)| 0x88u | 231 | 101 |7CH 100k |SODA|SODA-V||
|4|SODA-V(2)| 0x87u| 232 | 102 |7CH 100k |SODA|SODA-V||
|5|SODA-V(3)| 0x85u | 233 | 103 |7CH 100k |SPLUS-M|SPLUS-M| SW Only |
|5|SODA-V(4)|  |  |  |7CH 100k ||SODA-V| X10 |
|6|SPLUS-S| | 234 | 103 |7CH 100k  || SPLUS-M | 6CH |

---
### Firmware
* SODA    : D:\MUV_lhs  
* SPLUS-M : D:\JS-SPLUSM

***
### Settings
* Mac Address : net_interface.c   (Line 78)
* Target IP   : net_interface.c   (Line 532)
* Base IP     : common.h          (Line 100)
* TCP Port    : common.h          (Line 102)
* Check Time  : fpga_intf.c       (Line 2028)
