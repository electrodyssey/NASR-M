# NASR-M



SYZYGY carrier board powered by ZYNQ7000 SOC


Work in progress.

[Project goals and short design description](https://electrodyssey.net/nasr-m-syzygy-carrier-board.html)


[PDF schema is in schema-export folder](schema-export/NASR.pdf)


[Please watch ERRATA.txt for issues discovered during the board bringup](ERRATA.txt)


Version D 0.9.5 0b79528 (commit eba317391af35e6ee1b4c2de4c383aa31be21669) was submitted to production for a first prototype.

Things that worked so far:

+power distribution

+base controller (mostly works, but the ethernet circuit isn't soldered in yet). [The Zephyr firmware is here](https://github.com/electrodyssey/NASR-M-ZFW)

+clock generator is configured with 33.333MHz signal

+CPU can run bare metal applications via JTAG

+DDR3 subsystem passes Zynq DDR tests with no errors

+PS Ethernet works

+Linux boots of SD card


Watch [the blog](https://electrodyssey.net/tag_nasr-m.html) for an immersive soap opera experience.


The project is distributed under [Permissive OSHW License version 2](cern_ohl_p_v2.txt).

![board photo](https://github.com/electrodyssey/NASR-M/blob/main/lib/img/NASR-M_IMG_20260324.jpg "NASR-M")

![Linux boot in console](https://github.com/electrodyssey/NASR-M/blob/main/lib/img/nasr-m-first-sd-boot.png "NASR-M Linux boot")

![Peripherals map](https://github.com/electrodyssey/NASR-M/blob/main/lib/img/NASR-peripherals.png "Perhipherals map")


