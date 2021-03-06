# hackintosh-efi
# GitHub经常打不开，转[Gitee](https://gitee.com/cheukfungho/hackintosh-intel-i7-8700-k-gigabyte-z370-aorus-gaming5-vega56)和[pcbeta](https://bbs.pcbeta.com/viewthread-1880071-1-1.html)更新了
## 配置
+ 主板：技嘉Z370 AROUS Gaming5(BIOS版本:F7,已解锁CFG)
+ CPU：Intel® Core™ i7-8700K Processor
+ 显卡：蓝宝石 Radeon RX Vega 56 8G HBM2 白金版 OC
+ 内存：威刚ADATA XPG-Z1 3000Hz 8GB * 4
+ 固态硬盘：Intel 545S 512G | LITEON T11 256GB
+ 机械硬盘：TOSHIBA DT01ACA050 500G
+ 蓝牙&无线网卡：Broadcom BCM943602CS

## 更新
+ macOS Big Sur 11.1(20C69)
+ [OpenCore](https://github.com/acidanthera/OpenCorePkg/releases) v0.6.5
+ [Lilu](https://github.com/acidanthera/Lilu/releases) v1.5.0
+ [WhateverGreen](https://github.com/acidanthera/WhateverGreen/releases) v1.4.6
+ [AppleALC](https://github.com/acidanthera/AppleALC/releases) v1.5.6
+ [VirtualSMC](https://github.com/acidanthera/VirtualSMC/releases) v1.1.9
+ [IntelMausiEthernet](https://github.com/acidanthera/IntelMausi/release) v1.0.5
+ [CPUFriend](https://github.com/acidanthera/CPUFriend/releases) v1.2.3

## 备注
+ 这款主板在BIOS不能直接关闭CFG，关闭方法在[这里](https://blog.xjn819.com),直接在网页搜索【解锁BIOS中的CFG功能】就能看到。
+ 一旦解锁了CFG,需要在Kernel -> Quirks下，关闭AppleCpuPmCfgLock 以及 AppleXcpmCfgLock

![硬件解码](./snapshot/VideoProc.png)
![USB定制](./snapshot/usb.png)
![变频](./snapshot/pw.png)
