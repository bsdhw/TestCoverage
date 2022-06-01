BSD in Netherlands - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for BSD in Netherlands.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
  - [ Arch                     ](#arch)
  - [ DE                       ](#de)
  - [ Display Server           ](#display-server)
  - [ Display Manager          ](#display-manager)
  - [ OS Lang                  ](#os-lang)
  - [ Boot Mode                ](#boot-mode)
  - [ Filesystem               ](#filesystem)
  - [ Part. scheme             ](#part-scheme)

* [ Board ](#board)
  - [ Vendor                   ](#vendor)
  - [ Model                    ](#model)
  - [ Model Family             ](#model-family)
  - [ MFG Year                 ](#mfg-year)
  - [ Form Factor              ](#form-factor)
  - [ Coreboot                 ](#coreboot)
  - [ RAM Size                 ](#ram-size)
  - [ RAM Used                 ](#ram-used)
  - [ Total Drives             ](#total-drives)
  - [ Has CD-ROM               ](#has-cd-rom)
  - [ Has Ethernet             ](#has-ethernet)
  - [ Has WiFi                 ](#has-wifi)
  - [ Has Bluetooth            ](#has-bluetooth)

* [ Location ](#location)
  - [ Country                  ](#country)
  - [ City                     ](#city)

* [ Drives ](#drives)
  - [ Drive Vendor             ](#drive-vendor)
  - [ Drive Model              ](#drive-model)
  - [ HDD Vendor               ](#hdd-vendor)
  - [ SSD Vendor               ](#ssd-vendor)
  - [ Drive Kind               ](#drive-kind)
  - [ Drive Connector          ](#drive-connector)
  - [ Drive Size               ](#drive-size)
  - [ Space Total              ](#space-total)
  - [ Space Used               ](#space-used)
  - [ Malfunc. Drives          ](#malfunc-drives)
  - [ Malfunc. Drive Vendor    ](#malfunc-drive-vendor)
  - [ Malfunc. HDD Vendor      ](#malfunc-hdd-vendor)
  - [ Malfunc. Drive Kind      ](#malfunc-drive-kind)
  - [ Failed Drives            ](#failed-drives)
  - [ Failed Drive Vendor      ](#failed-drive-vendor)
  - [ Drive Status             ](#drive-status)

* [ Storage controller ](#storage-controller)
  - [ Storage Vendor           ](#storage-vendor)
  - [ Storage Model            ](#storage-model)
  - [ Storage Kind             ](#storage-kind)

* [ Processor ](#processor)
  - [ CPU Vendor               ](#cpu-vendor)
  - [ CPU Model                ](#cpu-model)
  - [ CPU Model Family         ](#cpu-model-family)
  - [ CPU Cores                ](#cpu-cores)
  - [ CPU Sockets              ](#cpu-sockets)
  - [ CPU Threads              ](#cpu-threads)
  - [ CPU Microarch            ](#cpu-microarch)

* [ Graphics ](#graphics)
  - [ GPU Vendor               ](#gpu-vendor)
  - [ GPU Model                ](#gpu-model)
  - [ GPU Combo                ](#gpu-combo)
  - [ GPU Driver               ](#gpu-driver)
  - [ GPU Memory               ](#gpu-memory)

* [ Monitor ](#monitor)
  - [ Monitor Vendor           ](#monitor-vendor)
  - [ Monitor Model            ](#monitor-model)
  - [ Monitor Resolution       ](#monitor-resolution)
  - [ Monitor Diagonal         ](#monitor-diagonal)
  - [ Monitor Width            ](#monitor-width)
  - [ Aspect Ratio             ](#aspect-ratio)
  - [ Monitor Area             ](#monitor-area)
  - [ Pixel Density            ](#pixel-density)
  - [ Multiple Monitors        ](#multiple-monitors)

* [ Network ](#network)
  - [ Net Controller Vendor    ](#net-controller-vendor)
  - [ Net Controller Model     ](#net-controller-model)
  - [ Wireless Vendor          ](#wireless-vendor)
  - [ Wireless Model           ](#wireless-model)
  - [ Ethernet Vendor          ](#ethernet-vendor)
  - [ Ethernet Model           ](#ethernet-model)
  - [ Net Controller Kind      ](#net-controller-kind)
  - [ Used Controller          ](#used-controller)
  - [ NICs                     ](#nics)
  - [ IPv6                     ](#ipv6)

* [ Bluetooth ](#bluetooth)
  - [ Bluetooth Vendor         ](#bluetooth-vendor)
  - [ Bluetooth Model          ](#bluetooth-model)

* [ Sound ](#sound)
  - [ Sound Vendor             ](#sound-vendor)
  - [ Sound Model              ](#sound-model)

* [ Memory ](#memory)
  - [ Memory Vendor            ](#memory-vendor)
  - [ Memory Model             ](#memory-model)
  - [ Memory Kind              ](#memory-kind)
  - [ Memory Form Factor       ](#memory-form-factor)
  - [ Memory Size              ](#memory-size)
  - [ Memory Speed             ](#memory-speed)

* [ Printers & scanners ](#printers--scanners)
  - [ Printer Vendor           ](#printer-vendor)
  - [ Printer Model            ](#printer-model)
  - [ Scanner Vendor           ](#scanner-vendor)
  - [ Scanner Model            ](#scanner-model)

* [ Camera ](#camera)
  - [ Camera Vendor            ](#camera-vendor)
  - [ Camera Model             ](#camera-model)

* [ Security ](#security)
  - [ Fingerprint Vendor       ](#fingerprint-vendor)
  - [ Fingerprint Model        ](#fingerprint-model)
  - [ Chipcard Vendor          ](#chipcard-vendor)
  - [ Chipcard Model           ](#chipcard-model)

* [ Unsupported ](#unsupported)
  - [ Unsupported Devices      ](#unsupported-devices)
  - [ Unsupported Device Types ](#unsupported-device-types)


Test Cases
----------

Total: 53

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | Latitude E7240              | [970234b430](https://bsd-hardware.info/?probe=970234b430) | May 22, 2022 |
| HP            | EliteBook 8460p             | [b9350aeb55](https://bsd-hardware.info/?probe=b9350aeb55) | May 21, 2022 |
| Deciso        | OPNsense Appliance          | [c78d18300d](https://bsd-hardware.info/?probe=c78d18300d) | Apr 18, 2022 |
| Sony          | SVZ1311C5E                  | [c1c429a7e6](https://bsd-hardware.info/?probe=c1c429a7e6) | Apr 15, 2022 |
| Apple         | MacBookPro10,1              | [64ccf1e6a0](https://bsd-hardware.info/?probe=64ccf1e6a0) | Feb 18, 2022 |
| Lenovo        | ThinkPad X250 20CLS59400    | [92333ad60b](https://bsd-hardware.info/?probe=92333ad60b) | Feb 17, 2022 |
| HP            | EliteBook 840 G3            | [f259f73c17](https://bsd-hardware.info/?probe=f259f73c17) | Feb 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [e795c7ec91](https://bsd-hardware.info/?probe=e795c7ec91) | Jan 17, 2022 |
| Dell          | Latitude E5430 non-vPro     | [877bb1b29f](https://bsd-hardware.info/?probe=877bb1b29f) | Jan 10, 2022 |
| Unknown       | Unknown                     | [974e1f4e5e](https://bsd-hardware.info/?probe=974e1f4e5e) | Jan 07, 2022 |
| Toshiba       | Satellite C50-B             | [6b03a2c4c2](https://bsd-hardware.info/?probe=6b03a2c4c2) | Dec 22, 2021 |
| TOXIC by B... | 15CL872 1050TI              | [0a1683170a](https://bsd-hardware.info/?probe=0a1683170a) | Dec 20, 2021 |
| Lenovo        | ThinkPad A285 20MW000JMH    | [ff53f0763c](https://bsd-hardware.info/?probe=ff53f0763c) | Dec 12, 2021 |
| Apple         | MacBookAir1,1               | [61c7028e83](https://bsd-hardware.info/?probe=61c7028e83) | Dec 07, 2021 |
| TOXIC by B... | 15CL872 1050TI              | [4fbb430947](https://bsd-hardware.info/?probe=4fbb430947) | Dec 05, 2021 |
| Lenovo        | ThinkPad T430 2347G7G       | [66c64c1af9](https://bsd-hardware.info/?probe=66c64c1af9) | Nov 23, 2021 |
| Apple         | MacBookPro9,2               | [04cc56305c](https://bsd-hardware.info/?probe=04cc56305c) | Nov 11, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [6f779d5170](https://bsd-hardware.info/?probe=6f779d5170) | Nov 03, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [72f0937505](https://bsd-hardware.info/?probe=72f0937505) | Nov 02, 2021 |
| HP            | 625                         | [606d75e6a1](https://bsd-hardware.info/?probe=606d75e6a1) | Aug 11, 2021 |
| Unknown       | Unknown                     | [d4122c5eb0](https://bsd-hardware.info/?probe=d4122c5eb0) | Aug 03, 2021 |
| Lenovo        | ThinkPad X230 2325IG2       | [158ecc5e0b](https://bsd-hardware.info/?probe=158ecc5e0b) | Jul 14, 2021 |
| Lenovo        | Yoga 500-14IBD 80N4         | [9fda78d739](https://bsd-hardware.info/?probe=9fda78d739) | Jun 23, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [46dca136f6](https://bsd-hardware.info/?probe=46dca136f6) | Jun 21, 2021 |
| WYSE          | Z CLASS                     | [571fdbf390](https://bsd-hardware.info/?probe=571fdbf390) | Jun 19, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [9ae8146589](https://bsd-hardware.info/?probe=9ae8146589) | Jun 15, 2021 |
| Dell          | Latitude E4300              | [7855973957](https://bsd-hardware.info/?probe=7855973957) | Jun 12, 2021 |
| SLIMBOOK      | Unknown                     | [80a9ba918e](https://bsd-hardware.info/?probe=80a9ba918e) | Jun 11, 2021 |
| Notebook      | NL5xRU                      | [792fb07dd9](https://bsd-hardware.info/?probe=792fb07dd9) | May 10, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [b644ed3914](https://bsd-hardware.info/?probe=b644ed3914) | Mar 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [4376accb5e](https://bsd-hardware.info/?probe=4376accb5e) | Mar 29, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [a5b9f5e79d](https://bsd-hardware.info/?probe=a5b9f5e79d) | Mar 27, 2021 |
| Lenovo        | ThinkPad X230 23255Y4       | [ab871769f0](https://bsd-hardware.info/?probe=ab871769f0) | Mar 27, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [d856b5bf95](https://bsd-hardware.info/?probe=d856b5bf95) | Mar 23, 2021 |
| Dell          | Latitude E7270              | [5ba79f9aa5](https://bsd-hardware.info/?probe=5ba79f9aa5) | Mar 19, 2021 |
| Lenovo        | ThinkPad X280 20KESA000B    | [e2b586d597](https://bsd-hardware.info/?probe=e2b586d597) | Mar 17, 2021 |
| Lenovo        | ThinkPad X200s 7470W1V      | [926fe13d8f](https://bsd-hardware.info/?probe=926fe13d8f) | Mar 09, 2021 |
| ASUSTek       | X556UA                      | [57018edd10](https://bsd-hardware.info/?probe=57018edd10) | Mar 07, 2021 |
| Dell          | Latitude E4300              | [d5051ef185](https://bsd-hardware.info/?probe=d5051ef185) | Feb 16, 2021 |
| Lenovo        | G505s 20255                 | [8bfcff9039](https://bsd-hardware.info/?probe=8bfcff9039) | Feb 16, 2021 |
| Dell          | Latitude E4300              | [981de7fd20](https://bsd-hardware.info/?probe=981de7fd20) | Feb 14, 2021 |
| Apple         | MacBookPro8,1               | [8f93b4146d](https://bsd-hardware.info/?probe=8f93b4146d) | Feb 12, 2021 |
| Apple         | MacBookPro8,1               | [e74d76ecb3](https://bsd-hardware.info/?probe=e74d76ecb3) | Feb 12, 2021 |
| Dell          | Latitude 7280               | [defaee0e5c](https://bsd-hardware.info/?probe=defaee0e5c) | Feb 12, 2021 |
| Dell          | Latitude 7280               | [1e243253d1](https://bsd-hardware.info/?probe=1e243253d1) | Feb 12, 2021 |
| Dell          | Latitude 7280               | [1ba418a5e6](https://bsd-hardware.info/?probe=1ba418a5e6) | Feb 12, 2021 |
| Dell          | XPS 15 9560                 | [687008da4f](https://bsd-hardware.info/?probe=687008da4f) | Feb 11, 2021 |
| Dell          | Latitude 7280               | [d62b7120c8](https://bsd-hardware.info/?probe=d62b7120c8) | Feb 11, 2021 |
| Dell          | Latitude 7370               | [8ec8d28024](https://bsd-hardware.info/?probe=8ec8d28024) | Feb 08, 2021 |
| Dell          | Latitude E4300              | [84925c014a](https://bsd-hardware.info/?probe=84925c014a) | Feb 01, 2021 |
| HP            | EliteBook 2530p             | [1fd927e2cd](https://bsd-hardware.info/?probe=1fd927e2cd) | Jan 11, 2021 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | [2808d1dd6a](https://bsd-hardware.info/?probe=2808d1dd6a) | Oct 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [bee732e516](https://bsd-hardware.info/?probe=bee732e516) | Oct 19, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.5.0    | 6         | 14.63%  |
| FreeBSD 13.0-STABLE  | 5         | 12.2%   |
| helloSystem 0.7.0    | 4         | 9.76%   |
| helloSystem 0.3.0    | 3         | 7.32%   |
| OpenBSD 6.9          | 2         | 4.88%   |
| OpenBSD 6.8          | 2         | 4.88%   |
| helloSystem 0.6.0    | 2         | 4.88%   |
| helloSystem 0.4.0    | 2         | 4.88%   |
| FreeBSD 13.0-p5      | 2         | 4.88%   |
| OPNsense 22.1.7      | 1         | 2.44%   |
| OPNsense 22.1.6      | 1         | 2.44%   |
| OPNsense 22.1        | 1         | 2.44%   |
| OPNsense 21.7.7      | 1         | 2.44%   |
| OPNsense 21.1.9      | 1         | 2.44%   |
| OpenBSD 7.0          | 1         | 2.44%   |
| FreeBSD 14.0-CURRENT | 1         | 2.44%   |
| FreeBSD 13.1         | 1         | 2.44%   |
| FreeBSD 13.0-p2      | 1         | 2.44%   |
| FreeBSD 13.0-BETA1   | 1         | 2.44%   |
| FreeBSD 13.0         | 1         | 2.44%   |
| FreeBSD 12.2-p2      | 1         | 2.44%   |
| FreeBSD 12.2         | 1         | 2.44%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 16        | 41.03%  |
| FreeBSD     | 14        | 35.9%   |
| OpenBSD     | 5         | 12.82%  |
| OPNsense    | 4         | 10.26%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 39        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 16        | 41.03%  |
| Console      | 6         | 15.38%  |
| fvwm         | 5         | 12.82%  |
| MATE         | 2         | 5.13%   |
| KDE5         | 2         | 5.13%   |
| GNOME        | 2         | 5.13%   |
| XFCE         | 1         | 2.56%   |
| TWM          | 1         | 2.56%   |
| LXQt         | 1         | 2.56%   |
| i3           | 1         | 2.56%   |
| GNUstep      | 1         | 2.56%   |
| AwesomeWM    | 1         | 2.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 33        | 84.62%  |
| Console | 5         | 12.82%  |
| Wayland | 1         | 2.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 19        | 48.72%  |
| Console | 12        | 30.77%  |
| XDM     | 3         | 7.69%   |
| SDDM    | 2         | 5.13%   |
| GDM     | 2         | 5.13%   |
| LightDM | 1         | 2.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 21        | 53.85%  |
| C       | 9         | 23.08%  |
| Unknown | 8         | 20.51%  |
| nl_NL   | 1         | 2.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 31        | 77.5%   |
| BIOS | 9         | 22.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 24        | 61.54%  |
| Ufs    | 7         | 17.95%  |
| Ffs    | 5         | 12.82%  |
| Cd9660 | 3         | 7.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 36        | 92.31%  |
| MBR  | 3         | 7.69%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 13        | 33.33%  |
| Dell             | 8         | 20.51%  |
| Hewlett-Packard  | 4         | 10.26%  |
| Apple            | 4         | 10.26%  |
| WYSE             | 1         | 2.56%   |
| TUXEDO           | 1         | 2.56%   |
| TOXIC by BTO     | 1         | 2.56%   |
| Toshiba          | 1         | 2.56%   |
| Sony             | 1         | 2.56%   |
| SLIMBOOK         | 1         | 2.56%   |
| Notebook         | 1         | 2.56%   |
| Deciso           | 1         | 2.56%   |
| ASUSTek Computer | 1         | 2.56%   |
| Unknown          | 1         | 2.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Latitude E4300                      | 2         | 5.13%   |
| Unknown                                  | 2         | 5.13%   |
| WYSE Z CLASS                             | 1         | 2.56%   |
| TUXEDO Pulse 15 Gen1                     | 1         | 2.56%   |
| TOXIC by BTO 15CL872 1050TI              | 1         | 2.56%   |
| Toshiba Satellite C50-B                  | 1         | 2.56%   |
| Sony SVZ1311C5E                          | 1         | 2.56%   |
| Notebook NL5xRU                          | 1         | 2.56%   |
| Lenovo Yoga 500-14IBD 80N4               | 1         | 2.56%   |
| Lenovo ThinkPad X280 20KESA000B          | 1         | 2.56%   |
| Lenovo ThinkPad X250 20CLS59400          | 1         | 2.56%   |
| Lenovo ThinkPad X250 20CLS4WV08          | 1         | 2.56%   |
| Lenovo ThinkPad X230 2325IG2             | 1         | 2.56%   |
| Lenovo ThinkPad X230 23255Y4             | 1         | 2.56%   |
| Lenovo ThinkPad X200s 7470W1V            | 1         | 2.56%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDCTO1WW | 1         | 2.56%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW | 1         | 2.56%   |
| Lenovo ThinkPad T440s 20ARS1B704         | 1         | 2.56%   |
| Lenovo ThinkPad T430 2347G7G             | 1         | 2.56%   |
| Lenovo ThinkPad A285 20MW000JMH          | 1         | 2.56%   |
| Lenovo G505s 20255                       | 1         | 2.56%   |
| HP EliteBook 8460p                       | 1         | 2.56%   |
| HP EliteBook 840 G3                      | 1         | 2.56%   |
| HP EliteBook 2530p                       | 1         | 2.56%   |
| HP 625                                   | 1         | 2.56%   |
| Dell XPS 15 9560                         | 1         | 2.56%   |
| Dell Latitude E7270                      | 1         | 2.56%   |
| Dell Latitude E7240                      | 1         | 2.56%   |
| Dell Latitude E5430 non-vPro             | 1         | 2.56%   |
| Dell Latitude 7370                       | 1         | 2.56%   |
| Dell Latitude 7280                       | 1         | 2.56%   |
| Deciso OPNsense Appliance                | 1         | 2.56%   |
| ASUS X556UA                              | 1         | 2.56%   |
| Apple MacBookPro9,2                      | 1         | 2.56%   |
| Apple MacBookPro8,1                      | 1         | 2.56%   |
| Apple MacBookPro10,1                     | 1         | 2.56%   |
| Apple MacBookAir1,1                      | 1         | 2.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 11        | 28.21%  |
| Dell Latitude        | 7         | 17.95%  |
| HP EliteBook         | 3         | 7.69%   |
| Unknown              | 2         | 5.13%   |
| WYSE Z               | 1         | 2.56%   |
| TUXEDO Pulse         | 1         | 2.56%   |
| TOXIC by BTO 15CL872 | 1         | 2.56%   |
| Toshiba Satellite    | 1         | 2.56%   |
| Sony SVZ1311C5E      | 1         | 2.56%   |
| Notebook NL5xRU      | 1         | 2.56%   |
| Lenovo Yoga          | 1         | 2.56%   |
| Lenovo G505s         | 1         | 2.56%   |
| HP 625               | 1         | 2.56%   |
| Dell XPS             | 1         | 2.56%   |
| Deciso OPNsense      | 1         | 2.56%   |
| ASUS X556UA          | 1         | 2.56%   |
| Apple MacBookPro9    | 1         | 2.56%   |
| Apple MacBookPro8    | 1         | 2.56%   |
| Apple MacBookPro10   | 1         | 2.56%   |
| Apple MacBookAir1    | 1         | 2.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 5         | 12.82%  |
| 2019 | 5         | 12.82%  |
| 2015 | 5         | 12.82%  |
| 2012 | 5         | 12.82%  |
| 2016 | 3         | 7.69%   |
| 2021 | 2         | 5.13%   |
| 2018 | 2         | 5.13%   |
| 2017 | 2         | 5.13%   |
| 2014 | 2         | 5.13%   |
| 2011 | 2         | 5.13%   |
| 2009 | 2         | 5.13%   |
| 2022 | 1         | 2.56%   |
| 2013 | 1         | 2.56%   |
| 2010 | 1         | 2.56%   |
| 2008 | 1         | 2.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 39        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 39        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 17        | 43.59%  |
| 4.01-8.0    | 9         | 23.08%  |
| 16.01-24.0  | 8         | 20.51%  |
| 32.01-64.0  | 3         | 7.69%   |
| 2.01-3.0    | 1         | 2.56%   |
| 64.01-256.0 | 1         | 2.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 24        | 60%     |
| 0.51-1.0 | 7         | 17.5%   |
| 1.01-2.0 | 6         | 15%     |
| 3.01-4.0 | 2         | 5%      |
| 2.01-3.0 | 1         | 2.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 25        | 62.5%   |
| 2      | 10        | 25%     |
| 3      | 3         | 7.5%    |
| 0      | 2         | 5%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 79.49%  |
| Yes       | 8         | 20.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 89.74%  |
| No        | 4         | 10.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 87.18%  |
| No        | 5         | 12.82%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 64.1%   |
| No        | 14        | 35.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Netherlands | 39        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Amsterdam           | 10        | 25%     |
| Utrecht             | 4         | 10%     |
| Eindhoven           | 3         | 7.5%    |
| The Hague           | 2         | 5%      |
| Hoogeveen           | 2         | 5%      |
| 's-Hertogenbosch    | 2         | 5%      |
| Woerdense Verlaat   | 1         | 2.5%    |
| Warmond             | 1         | 2.5%    |
| Tilburg             | 1         | 2.5%    |
| Roosendaal          | 1         | 2.5%    |
| Oosterhout          | 1         | 2.5%    |
| Oegstgeest          | 1         | 2.5%    |
| Munnikens-Vinkel    | 1         | 2.5%    |
| Lent                | 1         | 2.5%    |
| Leiden              | 1         | 2.5%    |
| Hoek van Holland    | 1         | 2.5%    |
| Groningen           | 1         | 2.5%    |
| Deventer            | 1         | 2.5%    |
| Den Dolder          | 1         | 2.5%    |
| De Lutte            | 1         | 2.5%    |
| Cuijk               | 1         | 2.5%    |
| Bergambacht         | 1         | 2.5%    |
| Alphen aan den Rijn | 1         | 2.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 18     | 31.82%  |
| WDC                 | 4         | 4      | 9.09%   |
| Seagate             | 4         | 5      | 9.09%   |
| Crucial             | 4         | 4      | 9.09%   |
| SanDisk             | 3         | 3      | 6.82%   |
| Transcend           | 2         | 3      | 4.55%   |
| Toshiba             | 2         | 2      | 4.55%   |
| NVMe                | 2         | 2      | 4.55%   |
| Apple               | 2         | 2      | 4.55%   |
| SK Hynix            | 1         | 1      | 2.27%   |
| OCZ                 | 1         | 1      | 2.27%   |
| LITEON              | 1         | 1      | 2.27%   |
| Kingston            | 1         | 1      | 2.27%   |
| HPE                 | 1         | 1      | 2.27%   |
| Hoodisk             | 1         | 2      | 2.27%   |
| Hitachi             | 1         | 1      | 2.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Seagate ST500LM000-SSHD-8GB      | 2         | 4.44%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1         | 2.22%   |
| WDC WDS100T2B0B-00YS70 1TB       | 1         | 2.22%   |
| WDC WD15EARS-00Z5B1 1.5TB        | 1         | 2.22%   |
| WDC WD10SPZX-24Z10 1TB           | 1         | 2.22%   |
| Transcend TS512GMTS430S 512GB    | 1         | 2.22%   |
| Transcend TS128GMTE110S 128GB    | 1         | 2.22%   |
| Toshiba THNSN5512GPUK NVMe 512GB | 1         | 2.22%   |
| Toshiba THNSFJ256GCSU 256GB      | 1         | 2.22%   |
| SK Hynix SC311 SATA 256GB        | 1         | 2.22%   |
| Seagate ST9250410AS 250GB        | 1         | 2.22%   |
| Seagate ST9160412ASG 160GB       | 1         | 2.22%   |
| SanDisk SD8SBAT256G1002 256GB    | 1         | 2.22%   |
| SanDisk SD7UB3Q256G1001 256GB    | 1         | 2.22%   |
| SanDisk SD6SB1M064G 64GB         | 1         | 2.22%   |
| Samsung SSD PM851 mSATA 512GB    | 1         | 2.22%   |
| Samsung SSD 980 PRO 1TB          | 1         | 2.22%   |
| Samsung SSD 970 PRO 512GB        | 1         | 2.22%   |
| Samsung SSD 970 EVO 500GB        | 1         | 2.22%   |
| Samsung SSD 870 QVO 1TB          | 1         | 2.22%   |
| Samsung SSD 860 EVO 1TB          | 1         | 2.22%   |
| Samsung SSD 850 EVO 500GB        | 1         | 2.22%   |
| Samsung SSD 850 EVO 250GB        | 1         | 2.22%   |
| Samsung SSD 840 EVO 250GB        | 1         | 2.22%   |
| Samsung SSD 840 EVO 120GB        | 1         | 2.22%   |
| Samsung SSD 830 Series 64GB      | 1         | 2.22%   |
| Samsung MZVLB1T0HBLR-000L7 1TB   | 1         | 2.22%   |
| Samsung MZRPC256HADR-000SO 128GB | 1         | 2.22%   |
| Samsung MZNLN256HCHP-000H1 256GB | 1         | 2.22%   |
| Samsung HS082HB 80GB             | 1         | 2.22%   |
| OCZ VERTEX PLUS 64GB             | 1         | 2.22%   |
| NVMe Samsung SSD 970 250GB       | 1         | 2.22%   |
| NVMe INTEL SSDPEKKF25 256GB      | 1         | 2.22%   |
| LITEON IT LCS-128L9S-HP 128GB    | 1         | 2.22%   |
| Kingston SA2000M8250G 250GB      | 1         | 2.22%   |
| HPE MK000480GWUGF 480GB          | 1         | 2.22%   |
| Hoodisk SSD 64GB                 | 1         | 2.22%   |
| Hitachi HTS545032B9A300 320GB    | 1         | 2.22%   |
| Crucial CT960BX500SSD1 960GB     | 1         | 2.22%   |
| Crucial CT500MX500SSD1 500GB     | 1         | 2.22%   |
| Crucial CT250MX500SSD1 250GB     | 1         | 2.22%   |
| Crucial CT120M500SSD1 120GB      | 1         | 2.22%   |
| Apple SSD TS128C 121GB           | 1         | 2.22%   |
| Apple SSD SM256E 256GB           | 1         | 2.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 5      | 50%     |
| WDC                 | 2         | 2      | 25%     |
| Samsung Electronics | 1         | 1      | 12.5%   |
| Hitachi             | 1         | 1      | 12.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 12     | 32.14%  |
| Crucial             | 4         | 4      | 14.29%  |
| SanDisk             | 3         | 3      | 10.71%  |
| NVMe                | 2         | 2      | 7.14%   |
| Apple               | 2         | 2      | 7.14%   |
| WDC                 | 1         | 1      | 3.57%   |
| Transcend           | 1         | 2      | 3.57%   |
| Toshiba             | 1         | 1      | 3.57%   |
| SK Hynix            | 1         | 1      | 3.57%   |
| OCZ                 | 1         | 1      | 3.57%   |
| LITEON              | 1         | 1      | 3.57%   |
| HPE                 | 1         | 1      | 3.57%   |
| Hoodisk             | 1         | 2      | 3.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 25        | 33     | 60.98%  |
| NVMe | 8         | 9      | 19.51%  |
| HDD  | 8         | 9      | 19.51%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 32        | 42     | 80%     |
| NVMe | 8         | 9      | 20%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 33     | 78.79%  |
| 0.51-1.0   | 6         | 8      | 18.18%  |
| 1.01-2.0   | 1         | 1      | 3.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 11        | 27.5%   |
| 101-250    | 9         | 22.5%   |
| 1-20       | 9         | 22.5%   |
| 51-100     | 5         | 12.5%   |
| 501-1000   | 4         | 10%     |
| 21-50      | 1         | 2.5%    |
| 1001-2000  | 1         | 2.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 33        | 84.62%  |
| 21-50    | 2         | 5.13%   |
| 51-100   | 2         | 5.13%   |
| 101-250  | 1         | 2.56%   |
| 501-1000 | 1         | 2.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD15EARS-00Z5B1 1.5TB        | 1         | 1      | 25%     |
| SanDisk SD7UB3Q256G1001 256GB    | 1         | 1      | 25%     |
| Samsung Electronics HS082HB 80GB | 1         | 1      | 25%     |
| Hitachi HTS545032B9A300 320GB    | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 25%     |
| SanDisk             | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |
| Hitachi             | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| Hitachi             | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 75%     |
| SSD  | 1         | 1      | 25%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                   | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| HPE MK000480GWUGF 480GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| HPE    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 32        | 44     | 82.05%  |
| Malfunc  | 4         | 4      | 10.26%  |
| Detected | 2         | 2      | 5.13%   |
| Failed   | 1         | 1      | 2.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 29        | 65.91%  |
| AMD                         | 6         | 13.64%  |
| Samsung Electronics         | 5         | 11.36%  |
| Toshiba                     | 1         | 2.27%   |
| Sandisk                     | 1         | 2.27%   |
| Kingston Technology Company | 1         | 2.27%   |
| Unknown                     | 1         | 2.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 6         | 12.5%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 5         | 10.42%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 4         | 8.33%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 4         | 8.33%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 3         | 6.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 3         | 6.25%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 3         | 6.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 2         | 4.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 2         | 4.17%   |
| Toshiba XG4 NVMe SSD Controller                                              | 1         | 2.08%   |
| Sandisk WD Blue SN550 NVMe SSD                                               | 1         | 2.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 1         | 2.08%   |
| Kingston Company A2000 NVMe SSD                                              | 1         | 2.08%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                      | 1         | 2.08%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                             | 1         | 2.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 2.08%   |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 2.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 2.08%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 1         | 2.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]         | 1         | 2.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 1         | 2.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 1         | 2.08%   |
| Unknown                                                                      | 1         | 2.08%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 29        | 60.42%  |
| NVMe | 10        | 20.83%  |
| RAID | 6         | 12.5%   |
| IDE  | 3         | 6.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 32        | 82.05%  |
| AMD    | 7         | 17.95%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-7600U CPU @ 2.80GHz               | 2         | 5.13%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 2         | 5.13%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 2         | 5.13%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 2         | 5.13%   |
| Intel Core 2 Duo                                | 2         | 5.13%   |
| Intel Pentium CPU N3530 @ 2.16GHz               | 1         | 2.56%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz                | 1         | 2.56%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 2.56%   |
| Intel Core i7-8665U CPU @ 1.90GHz               | 1         | 2.56%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 2.56%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 1         | 2.56%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 2.56%   |
| Intel Core i7-3615QM CPU @ 2.30GHz              | 1         | 2.56%   |
| Intel Core i7-3612QM CPU @ 2.10GHz              | 1         | 2.56%   |
| Intel Core i5-8350U CPU @ 1.70GHz               | 1         | 2.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 1         | 2.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 1         | 2.56%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 1         | 2.56%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 2.56%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 1         | 2.56%   |
| Intel Core i5-2435M CPU @ 2.40GHz               | 1         | 2.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 1         | 2.56%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 1         | 2.56%   |
| Intel Core 2 Duo CPU P7500 @ 1.60GHz            | 1         | 2.56%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz            | 1         | 2.56%   |
| Intel Core 2 Duo CPU L9300 @ 1.60GHz            | 1         | 2.56%   |
| Intel Celeron 2955U @ 1.40GHz                   | 1         | 2.56%   |
| AMD Ryzen Embedded V1500B                       | 1         | 2.56%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 1         | 2.56%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 1         | 2.56%   |
| AMD Ryzen 5 PRO 2500U w/ Radeon Vega Mobile Gfx | 1         | 2.56%   |
| AMD G-T56N Processor                            | 1         | 2.56%   |
| AMD Athlon II P320 Dual-Core Processor          | 1         | 2.56%   |
| AMD A8-4500M APU with Radeon HD Graphics        | 1         | 2.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 13        | 33.33%  |
| Intel Core i5      | 10        | 25.64%  |
| Intel Core 2 Duo   | 5         | 12.82%  |
| AMD Ryzen 7        | 2         | 5.13%   |
| Intel Pentium      | 1         | 2.56%   |
| Intel Core m7      | 1         | 2.56%   |
| Intel Core i3      | 1         | 2.56%   |
| Intel Celeron      | 1         | 2.56%   |
| AMD Ryzen Embedded | 1         | 2.56%   |
| AMD Ryzen 5 PRO    | 1         | 2.56%   |
| AMD G              | 1         | 2.56%   |
| AMD Athlon II      | 1         | 2.56%   |
| AMD A8             | 1         | 2.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 23        | 58.97%  |
| 4       | 8         | 20.51%  |
| 8       | 3         | 7.69%   |
| Unknown | 3         | 7.69%   |
| 16      | 1         | 2.56%   |
| 6       | 1         | 2.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 38        | 97.44%  |
| 2      | 1         | 2.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 25        | 64.1%   |
| 1       | 11        | 28.21%  |
| Unknown | 3         | 7.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 7         | 17.95%  |
| IvyBridge   | 7         | 17.95%  |
| Skylake     | 4         | 10.26%  |
| Penryn      | 4         | 10.26%  |
| Haswell     | 3         | 7.69%   |
| Broadwell   | 3         | 7.69%   |
| Zen 2       | 2         | 5.13%   |
| Zen         | 2         | 5.13%   |
| SandyBridge | 2         | 5.13%   |
| Silvermont  | 1         | 2.56%   |
| Piledriver  | 1         | 2.56%   |
| K10         | 1         | 2.56%   |
| Core        | 1         | 2.56%   |
| Bobcat      | 1         | 2.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 30        | 73.17%  |
| AMD    | 7         | 17.07%  |
| Nvidia | 4         | 9.76%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 6         | 13.95%  |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 4         | 9.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                       | 3         | 6.98%   |
| Intel HD Graphics 5500                                                    | 3         | 6.98%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 6.98%   |
| Intel HD Graphics 620                                                     | 2         | 4.65%   |
| AMD Renoir                                                                | 2         | 4.65%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 2.33%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 2.33%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                               | 1         | 2.33%   |
| Nvidia GF108M [NVS 5400M]                                                 | 1         | 2.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 2.33%   |
| Intel UHD Graphics 620                                                    | 1         | 2.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 2.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 2.33%   |
| Intel HD Graphics 630                                                     | 1         | 2.33%   |
| Intel HD Graphics 515                                                     | 1         | 2.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 2.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 2.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1         | 2.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1         | 2.33%   |
| AMD Wrestler [Radeon HD 6310]                                             | 1         | 2.33%   |
| AMD Trinity [Radeon HD 7640G]                                             | 1         | 2.33%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                       | 1         | 2.33%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 1         | 2.33%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                 | 1         | 2.33%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 2.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 22        | 56.41%  |
| 1 x AMD        | 6         | 15.38%  |
| 2 x Intel      | 5         | 12.82%  |
| Intel + Nvidia | 3         | 7.69%   |
| Other          | 1         | 2.56%   |
| 2 x AMD        | 1         | 2.56%   |
| 1 x Nvidia     | 1         | 2.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 36        | 92.31%  |
| Proprietary | 2         | 5.13%   |
| Unknown     | 1         | 2.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 84.62%  |
| 0.01-0.5   | 3         | 7.69%   |
| 0.51-1.0   | 2         | 5.13%   |
| 1.01-2.0   | 1         | 2.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 9         | 29.03%  |
| Samsung Electronics | 4         | 12.9%   |
| Chimei Innolux      | 3         | 9.68%   |
| BOE                 | 3         | 9.68%   |
| AU Optronics        | 3         | 9.68%   |
| Apple               | 3         | 9.68%   |
| Sharp               | 2         | 6.45%   |
| Sony                | 1         | 3.23%   |
| Philips             | 1         | 3.23%   |
| Lenovo              | 1         | 3.23%   |
| AOC                 | 1         | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch          | 2         | 6.45%   |
| Sony LCD SNY06FA 1600x900 290x160mm 13.0-inch                        | 1         | 3.23%   |
| Sharp LCD Monitor SHP1461 3200x1800 290x170mm 13.2-inch              | 1         | 3.23%   |
| Sharp LCD Monitor SHP1453 1920x1080 350x190mm 15.7-inch              | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SEC4541 1280x800 260x160mm 12.0-inch | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 340x190mm 15.3-inch | 1         | 3.23%   |
| Philips PHL 328E1 PHLC204 3840x2160 700x390mm 31.5-inch              | 1         | 3.23%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch         | 1         | 3.23%   |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch         | 1         | 3.23%   |
| LG Display LCD Monitor LGD0450 1366x768 280x160mm 12.7-inch          | 1         | 3.23%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 1         | 3.23%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch         | 1         | 3.23%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 1         | 3.23%   |
| LG Display LCD Monitor LGD02AD 1366x768 340x190mm 15.3-inch          | 1         | 3.23%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch              | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN15B5 1366x768 340x190mm 15.3-inch      | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 310x170mm 13.9-inch     | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch     | 1         | 3.23%   |
| BOE LCD Monitor BOE07F7 1920x1080 310x170mm 13.9-inch                | 1         | 3.23%   |
| BOE LCD Monitor BOE07C8 3840x2160 310x170mm 13.9-inch                | 1         | 3.23%   |
| BOE LCD Monitor BOE06BF 1920x1080 280x160mm 12.7-inch                | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch       | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO313E 1600x900 310x170mm 13.9-inch        | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 1         | 3.23%   |
| Apple LCD Monitor APP9CC3 1280x800 290x180mm 13.4-inch               | 1         | 3.23%   |
| Apple Color LCD APP9CC7 1280x800 290x180mm 13.4-inch                 | 1         | 3.23%   |
| Apple Color LCD APP9C6F 1280x800 290x190mm 13.6-inch                 | 1         | 3.23%   |
| AOC U2868 AOC2868 3840x2160 620x340mm 27.8-inch                      | 1         | 3.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 9         | 29.03%  |
| 1366x768 (WXGA)  | 7         | 22.58%  |
| 1280x800 (WXGA)  | 7         | 22.58%  |
| 3840x2160 (4K)   | 3         | 9.68%   |
| 1600x900 (HD+)   | 3         | 9.68%   |
| 3200x1800 (QHD+) | 1         | 3.23%   |
| 2560x1440 (QHD)  | 1         | 3.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 13        | 41.94%  |
| 12     | 10        | 32.26%  |
| 15     | 6         | 19.35%  |
| 31     | 1         | 3.23%   |
| 27     | 1         | 3.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 201-300     | 17        | 54.84%  |
| 301-350     | 12        | 38.71%  |
| 601-700     | 2         | 6.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 23        | 76.67%  |
| 16/10 | 6         | 20%     |
| 3/2   | 1         | 3.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 11        | 35.48%  |
| 61-70          | 10        | 32.26%  |
| 91-100         | 4         | 12.9%   |
| 71-80          | 2         | 6.45%   |
| 101-110        | 2         | 6.45%   |
| 351-500        | 1         | 3.23%   |
| 301-350        | 1         | 3.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 15        | 50%     |
| 101-120       | 8         | 26.67%  |
| 161-240       | 5         | 16.67%  |
| More than 240 | 2         | 6.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 30        | 76.92%  |
| 0     | 8         | 20.51%  |
| 2     | 1         | 2.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 30        | 48.39%  |
| Realtek Semiconductor             | 15        | 24.19%  |
| Broadcom                          | 6         | 9.68%   |
| Qualcomm Atheros                  | 3         | 4.84%   |
| TP-Link                           | 2         | 3.23%   |
| Sierra Wireless                   | 1         | 1.61%   |
| Ralink Technology                 | 1         | 1.61%   |
| Hewlett-Packard                   | 1         | 1.61%   |
| Fibocom                           | 1         | 1.61%   |
| Ericsson Business Mobile Networks | 1         | 1.61%   |
| AMD                               | 1         | 1.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 9         | 10.98%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                | 4         | 4.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 4         | 4.88%   |
| Intel 82567LM Gigabit Network Connection                           | 4         | 4.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 3         | 3.66%   |
| Intel Wireless 8265 / 8275                                         | 3         | 3.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 3         | 3.66%   |
| Broadcom BCM4331 802.11a/b/g/n                                     | 3         | 3.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 2         | 2.44%   |
| Intel Wireless-AC 9260                                             | 2         | 2.44%   |
| Intel Wireless 8260                                                | 2         | 2.44%   |
| Intel Wireless 7265                                                | 2         | 2.44%   |
| Intel Wireless 7260                                                | 2         | 2.44%   |
| Intel WiFi Link 5100                                               | 2         | 2.44%   |
| Intel Wi-Fi 6 AX200                                                | 2         | 2.44%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection            | 2         | 2.44%   |
| Intel Ethernet Connection I218-LM                                  | 2         | 2.44%   |
| Intel Ethernet Connection (4) I219-LM                              | 2         | 2.44%   |
| Intel Ethernet Connection (3) I218-LM                              | 2         | 2.44%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                  | 2         | 2.44%   |
| TP-Link TP-LINK Wireless USB Adapter                               | 1         | 1.22%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]         | 1         | 1.22%   |
| Sierra Wireless EM7455                                             | 1         | 1.22%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                            | 1         | 1.22%   |
| Ralink RT5370 Wireless Adapter                                     | 1         | 1.22%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                             | 1         | 1.22%   |
| Intel Wireless 3160                                                | 1         | 1.22%   |
| Intel I211 Gigabit Network Connection                              | 1         | 1.22%   |
| Intel I210 Gigabit Network Connection                              | 1         | 1.22%   |
| Intel Ethernet Connection I219-V                                   | 1         | 1.22%   |
| Intel Ethernet Connection I219-LM                                  | 1         | 1.22%   |
| Intel Ethernet Connection (6) I219-LM                              | 1         | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 1         | 1.22%   |
| Intel Centrino Ultimate-N 6300                                     | 1         | 1.22%   |
| Intel Centrino Advanced-N 6235                                     | 1         | 1.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 1         | 1.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 1         | 1.22%   |
| HP un2400 Gobi Wireless Modem (QDL mode)                           | 1         | 1.22%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                  | 1         | 1.22%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 1         | 1.22%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                  | 1         | 1.22%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                   | 1         | 1.22%   |
| Broadcom BCM4321 802.11a/b/g/n                                     | 1         | 1.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                | 1         | 1.22%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0          | 1         | 1.22%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 60.47%  |
| Realtek Semiconductor | 5         | 11.63%  |
| Broadcom              | 5         | 11.63%  |
| Qualcomm Atheros      | 3         | 6.98%   |
| TP-Link               | 2         | 4.65%   |
| Sierra Wireless       | 1         | 2.33%   |
| Ralink Technology     | 1         | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 4         | 9.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 3         | 6.98%   |
| Intel Wireless 8265 / 8275                                 | 3         | 6.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 3         | 6.98%   |
| Broadcom BCM4331 802.11a/b/g/n                             | 3         | 6.98%   |
| Intel Wireless-AC 9260                                     | 2         | 4.65%   |
| Intel Wireless 8260                                        | 2         | 4.65%   |
| Intel Wireless 7265                                        | 2         | 4.65%   |
| Intel Wireless 7260                                        | 2         | 4.65%   |
| Intel WiFi Link 5100                                       | 2         | 4.65%   |
| Intel Wi-Fi 6 AX200                                        | 2         | 4.65%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection    | 2         | 4.65%   |
| TP-Link TP-LINK Wireless USB Adapter                       | 1         | 2.33%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano] | 1         | 2.33%   |
| Sierra Wireless EM7455                                     | 1         | 2.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                    | 1         | 2.33%   |
| Ralink RT5370 Wireless Adapter                             | 1         | 2.33%   |
| Intel Wireless 3160                                        | 1         | 2.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 1         | 2.33%   |
| Intel Centrino Ultimate-N 6300                             | 1         | 2.33%   |
| Intel Centrino Advanced-N 6235                             | 1         | 2.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 1         | 2.33%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 1         | 2.33%   |
| Broadcom BCM4321 802.11a/b/g/n                             | 1         | 2.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 1         | 2.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 52.78%  |
| Realtek Semiconductor | 11        | 30.56%  |
| Broadcom              | 4         | 11.11%  |
| Qualcomm Atheros      | 1         | 2.78%   |
| AMD                   | 1         | 2.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 25%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 11.11%  |
| Intel 82567LM Gigabit Network Connection                          | 4         | 11.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 5.56%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 5.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 5.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 5.56%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 5.56%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 2.78%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.78%   |
| Intel I210 Gigabit Network Connection                             | 1         | 2.78%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.78%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.78%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 2.78%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 2.78%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 2.78%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 1         | 2.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 35        | 48.61%  |
| WiFi     | 34        | 47.22%  |
| Modem    | 2         | 2.78%   |
| Unknown  | 1         | 1.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 31        | 53.45%  |
| Ethernet | 27        | 46.55%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 30        | 76.92%  |
| 1     | 7         | 17.95%  |
| 6     | 1         | 2.56%   |
| 5     | 1         | 2.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 31        | 77.5%   |
| Yes  | 9         | 22.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel           | 15        | 60%     |
| Apple           | 4         | 16%     |
| Broadcom        | 3         | 12%     |
| IMC Networks    | 1         | 4%      |
| Hewlett-Packard | 1         | 4%      |
| Dell            | 1         | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 7         | 28%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 3         | 12%     |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 2         | 8%      |
| Intel AX200 Bluetooth                          | 2         | 8%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 2         | 8%      |
| Apple Bluetooth Host Controller                | 2         | 8%      |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 4%      |
| IMC Networks Qualcomm Atheros Bluetooth 4.0    | 1         | 4%      |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]  | 1         | 4%      |
| Dell Dell Wireless 380 Bluetooth 4.0 Module    | 1         | 4%      |
| Broadcom BCM2070 Bluetooth 2.1 + EDR           | 1         | 4%      |
| Apple Broadcom Bluetooth 2.1 module            | 1         | 4%      |
| Apple Apple Broadcom Built-in Bluetooth        | 1         | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 31        | 75.61%  |
| AMD    | 8         | 19.51%  |
| Nvidia | 2         | 4.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 7         | 13.21%  |
| Intel Sunrise Point-LP HD Audio                                                   | 6         | 11.32%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 4         | 7.55%   |
| AMD Family 17h/19h HD Audio Controller                                            | 4         | 7.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 3         | 5.66%   |
| Intel Haswell-ULT HD Audio Controller                                             | 3         | 5.66%   |
| Intel Broadwell-U Audio Controller                                                | 3         | 5.66%   |
| Intel 8 Series HD Audio Controller                                                | 3         | 5.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 2         | 3.77%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2         | 3.77%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2         | 3.77%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 1.89%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1         | 1.89%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 1         | 1.89%   |
| Intel CM238 HD Audio Controller                                                   | 1         | 1.89%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 1         | 1.89%   |
| Intel Cannon Lake PCH cAVS                                                        | 1         | 1.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1         | 1.89%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 1         | 1.89%   |
| AMD Wrestler HDMI Audio                                                           | 1         | 1.89%   |
| AMD Trinity HDMI Audio Controller                                                 | 1         | 1.89%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 1         | 1.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 1.89%   |
| AMD FCH Azalia Controller                                                         | 1         | 1.89%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 1.89%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 9         | 21.95%  |
| SK Hynix            | 6         | 14.63%  |
| Micron Technology   | 6         | 14.63%  |
| Crucial             | 4         | 9.76%   |
| Unknown             | 3         | 7.32%   |
| Elpida              | 3         | 7.32%   |
| Ramaxel Technology  | 2         | 4.88%   |
| Kingston            | 2         | 4.88%   |
| Apacer              | 2         | 4.88%   |
| Transcend           | 1         | 2.44%   |
| Nanya Technology    | 1         | 2.44%   |
| G.Skill             | 1         | 2.44%   |
| Corsair             | 1         | 2.44%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 4.88%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1333MT/s     | 2         | 4.88%   |
| Unknown RAM Module 8GB SODIMM LPDDR3 1867MT/s             | 1         | 2.44%   |
| Unknown RAM Module 4GB SODIMM DDR3                        | 1         | 2.44%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                | 1         | 2.44%   |
| Transcend RAM TS512MLH64V6HL 4GB SODIMM DDR4 2667MT/s     | 1         | 2.44%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s              | 1         | 2.44%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1333MT/s           | 1         | 2.44%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 2.44%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 2.44%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 2.44%   |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1333MT/s    | 1         | 2.44%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s               | 1         | 2.44%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s       | 1         | 2.44%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1333MT/s     | 1         | 2.44%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 1         | 2.44%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 1         | 2.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s     | 1         | 2.44%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s    | 1         | 2.44%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s   | 1         | 2.44%   |
| Ramaxel RAM RMT3020EF48E8W1333 2GB SODIMM DDR3 1334MT/s   | 1         | 2.44%   |
| Nanya RAM NT2GC64B8HA1NS-BE 2GB SODIMM DDR3 1067MT/s      | 1         | 2.44%   |
| Micron RAM MT41K512M16TNA-125 4GB Chip DDR3 1600MT/s      | 1         | 2.44%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s    | 1         | 2.44%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s    | 1         | 2.44%   |
| Micron RAM 16KTF1G64HZ-1G9P1 8GB SODIMM DDR3 1777MT/s     | 1         | 2.44%   |
| Micron RAM 16HTF51264HZ-800C1 4GB SODIMM DDR2 800MT/s     | 1         | 2.44%   |
| Micron RAM 16ATF2G64HZ-2G3H1 16GB SODIMM DDR4 2400MT/s    | 1         | 2.44%   |
| Kingston RAM 99U5663-007.A00G 16GB SODIMM DDR4 2667MT/s   | 1         | 2.44%   |
| Kingston RAM 393930353437312D 4GB SODIMM DDR3 1333MT/s    | 1         | 2.44%   |
| G.Skill RAM F4-3000C16-16GRS 16GB SODIMM DDR4 2400MT/s    | 1         | 2.44%   |
| Elpida RAM EBJ20UF8BDU0-GN-F 2GB SODIMM DDR3 1600MT/s     | 1         | 2.44%   |
| Crucial RAM Module 8GB SODIMM DDR3 1600MT/s               | 1         | 2.44%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s   | 1         | 2.44%   |
| Crucial RAM CT16G4SFD832A.C16FP 16GB SODIMM DDR4 2400MT/s | 1         | 2.44%   |
| Crucial RAM CT16G4SFD8266.M16FJ 16GB SODIMM DDR4 2667MT/s | 1         | 2.44%   |
| Corsair RAM CMSX8GX3M1A1600C10 8GB SODIMM DDR3 1333MT/s   | 1         | 2.44%   |
| Apacer RAM 76.A305G.C5G0B 2048MB SODIMM DDR3 1600MT/s     | 1         | 2.44%   |
| Apacer RAM 37352E4138334331 2GB SODIMM DDR3 1333MT/s      | 1         | 2.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 21        | 61.76%  |
| DDR4   | 9         | 26.47%  |
| LPDDR3 | 2         | 5.88%   |
| DDR2   | 2         | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 33        | 94.29%  |
| Row Of Chips | 1         | 2.86%   |
| Chip         | 1         | 2.86%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 17        | 43.59%  |
| 8192  | 9         | 23.08%  |
| 2048  | 6         | 15.38%  |
| 16384 | 5         | 12.82%  |
| 32768 | 1         | 2.56%   |
| 1024  | 1         | 2.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 12        | 32.43%  |
| 1333    | 7         | 18.92%  |
| 2667    | 4         | 10.81%  |
| 2400    | 3         | 8.11%   |
| 2133    | 2         | 5.41%   |
| 1334    | 2         | 5.41%   |
| 3200    | 1         | 2.7%    |
| 1867    | 1         | 2.7%    |
| 1777    | 1         | 2.7%    |
| 1067    | 1         | 2.7%    |
| 800     | 1         | 2.7%    |
| 667     | 1         | 2.7%    |
| Unknown | 1         | 2.7%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 8         | 30.77%  |
| Realtek Semiconductor                  | 4         | 15.38%  |
| Lite-On Technology                     | 3         | 11.54%  |
| Apple                                  | 3         | 11.54%  |
| Microdia                               | 2         | 7.69%   |
| Acer                                   | 2         | 7.69%   |
| Sunplus Innovation Technology          | 1         | 3.85%   |
| Ricoh                                  | 1         | 3.85%   |
| IMC Networks                           | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                  | 2         | 7.69%   |
| Lite-On Integrated Camera                     | 2         | 7.69%   |
| Chicony Integrated Camera                     | 2         | 7.69%   |
| Chicony HD Webcam                             | 2         | 7.69%   |
| Apple FaceTime HD Camera                      | 2         | 7.69%   |
| Sunplus Laptop Integrated Webcam HD           | 1         | 3.85%   |
| Ricoh USB2.0 Camera                           | 1         | 3.85%   |
| Realtek Lenovo EasyCamera                     | 1         | 3.85%   |
| Realtek Integrated Webcam HD                  | 1         | 3.85%   |
| Microdia Integrated_Webcam_HD                 | 1         | 3.85%   |
| Microdia Dell Integrated HD Webcam            | 1         | 3.85%   |
| Lite-On TOSHIBA Web Camera - HD               | 1         | 3.85%   |
| IMC Networks Integrated Camera                | 1         | 3.85%   |
| Chicony thinkpad t430s camera                 | 1         | 3.85%   |
| Chicony Integrated Camera (1280x720@30)       | 1         | 3.85%   |
| Chicony HP Webcam [2 MP]                      | 1         | 3.85%   |
| Chicony Chicony USB2.0 Camera                 | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 1         | 3.85%   |
| Apple FaceTime HD Camera (Built-in)           | 1         | 3.85%   |
| Acer Lenovo EasyCamera                        | 1         | 3.85%   |
| Acer Integrated Camera                        | 1         | 3.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 33.33%  |
| Synaptics        | 2         | 33.33%  |
| AuthenTec        | 2         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 16.67%  |
| Validity Sensors Synaptics WBDI                   | 1         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 16.67%  |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 16.67%  |
| AuthenTec AES2810                                 | 1         | 16.67%  |
| AuthenTec AES1660 Fingerprint Sensor              | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart_bsd/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 19        | 47.5%   |
| 2     | 7         | 17.5%   |
| 3     | 5         | 12.5%   |
| 0     | 5         | 12.5%   |
| 4     | 4         | 10%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 29        | 50.88%  |
| Card reader              | 8         | 14.04%  |
| Net/wireless             | 6         | 10.53%  |
| Fingerprint reader       | 5         | 8.77%   |
| Bluetooth                | 5         | 8.77%   |
| Firewire controller      | 2         | 3.51%   |
| Sound                    | 1         | 1.75%   |
| Net/ethernet             | 1         | 1.75%   |
