NomadBSD - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for NomadBSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://bsd-hardware.info/?view=trends

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | Latitude D630               | [ae56d2cedd](https://bsd-hardware.info/?probe=ae56d2cedd) | Feb 28, 2022 |
| HP            | Pavilion Notebook           | [e27a6f46fc](https://bsd-hardware.info/?probe=e27a6f46fc) | Feb 26, 2022 |
| HP            | Laptop 15-db0xxx            | [766e62f699](https://bsd-hardware.info/?probe=766e62f699) | Feb 12, 2022 |
| HP            | Notebook                    | [1758596e26](https://bsd-hardware.info/?probe=1758596e26) | Feb 12, 2022 |
| HP            | Pavilion Notebook           | [24f3a7da57](https://bsd-hardware.info/?probe=24f3a7da57) | Feb 07, 2022 |
| ASUSTek       | 1000                        | [da8689c840](https://bsd-hardware.info/?probe=da8689c840) | Dec 08, 2021 |
| Acer          | Aspire 3810T                | [86782a69be](https://bsd-hardware.info/?probe=86782a69be) | Nov 13, 2021 |
| Acer          | Aspire 3810T                | [608e43163d](https://bsd-hardware.info/?probe=608e43163d) | Nov 12, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [1d261120d3](https://bsd-hardware.info/?probe=1d261120d3) | Nov 06, 2021 |
| HP            | ZBook Studio G3             | [767b44a6ae](https://bsd-hardware.info/?probe=767b44a6ae) | Oct 30, 2021 |
| ASUSTek       | X202E                       | [54259ac9a1](https://bsd-hardware.info/?probe=54259ac9a1) | Oct 29, 2021 |
| Sony          | VJS121C11N                  | [d86c621ef0](https://bsd-hardware.info/?probe=d86c621ef0) | Oct 25, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [2d72b6939d](https://bsd-hardware.info/?probe=2d72b6939d) | Oct 24, 2021 |
| ASUSTek       | X540YA                      | [c5751c736c](https://bsd-hardware.info/?probe=c5751c736c) | Sep 19, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [d8f8901ae7](https://bsd-hardware.info/?probe=d8f8901ae7) | Sep 19, 2021 |
| HP            | OMEN by HP Laptop 17-cb1... | [b00c8e76e8](https://bsd-hardware.info/?probe=b00c8e76e8) | Aug 23, 2021 |
| HP            | Pavilion g6                 | [f1dc5150c2](https://bsd-hardware.info/?probe=f1dc5150c2) | Aug 13, 2021 |
| HP            | 2000                        | [d2240a960b](https://bsd-hardware.info/?probe=d2240a960b) | Aug 05, 2021 |
| HP            | 2000                        | [65d183fe41](https://bsd-hardware.info/?probe=65d183fe41) | Aug 05, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0M... | [39ef89f214](https://bsd-hardware.info/?probe=39ef89f214) | Aug 05, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0M... | [4e7ace8a39](https://bsd-hardware.info/?probe=4e7ace8a39) | Aug 04, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [3348992bef](https://bsd-hardware.info/?probe=3348992bef) | Jul 23, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | [77676fbcfc](https://bsd-hardware.info/?probe=77676fbcfc) | Jul 18, 2021 |
| Lenovo        | ThinkPad T510 4384FF3       | [25e208721d](https://bsd-hardware.info/?probe=25e208721d) | Jul 02, 2021 |
| Dell          | Inspiron 15-5568            | [3ed52ae70d](https://bsd-hardware.info/?probe=3ed52ae70d) | Jul 01, 2021 |
| Apple         | MacBookAir6,1               | [46bf9edc63](https://bsd-hardware.info/?probe=46bf9edc63) | Jun 17, 2021 |
| Apple         | MacBookAir6,1               | [dbda48cff7](https://bsd-hardware.info/?probe=dbda48cff7) | Jun 17, 2021 |
| Acer          | Aspire E5-551               | [c9ab1cb207](https://bsd-hardware.info/?probe=c9ab1cb207) | Apr 29, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0M... | [e9155d12c7](https://bsd-hardware.info/?probe=e9155d12c7) | Apr 27, 2021 |
| Apple         | MacBookPro8,1               | [d1aaeaad42](https://bsd-hardware.info/?probe=d1aaeaad42) | Apr 26, 2021 |
| Lenovo        | ThinkPad W541 20EGS04800    | [91d2cd471c](https://bsd-hardware.info/?probe=91d2cd471c) | Apr 16, 2021 |
| Apple         | MacBookPro8,1               | [0621acab4e](https://bsd-hardware.info/?probe=0621acab4e) | Apr 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [821c81e652](https://bsd-hardware.info/?probe=821c81e652) | Apr 09, 2021 |
| HP            | ProBook 640 G1              | [6bc6c5b2bf](https://bsd-hardware.info/?probe=6bc6c5b2bf) | Mar 31, 2021 |
| TUXEDO        | Unknown                     | [35aa6590c6](https://bsd-hardware.info/?probe=35aa6590c6) | Mar 29, 2021 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [c5e824b558](https://bsd-hardware.info/?probe=c5e824b558) | Mar 29, 2021 |
| Toshiba       | Satellite C660              | [7d64801e2b](https://bsd-hardware.info/?probe=7d64801e2b) | Mar 21, 2021 |
| MSI           | MS-N033                     | [650f6a1b70](https://bsd-hardware.info/?probe=650f6a1b70) | Mar 21, 2021 |
| Samsung       | N145P/N250P/N260P           | [eff02dafe1](https://bsd-hardware.info/?probe=eff02dafe1) | Mar 18, 2021 |
| Toshiba       | Satellite C660              | [83f9d05407](https://bsd-hardware.info/?probe=83f9d05407) | Mar 14, 2021 |
| Notebook      | N650DU                      | [90d705dd1e](https://bsd-hardware.info/?probe=90d705dd1e) | Mar 14, 2021 |
| HP            | Pavilion dv6000 (RP981EA... | [733c5edb74](https://bsd-hardware.info/?probe=733c5edb74) | Mar 08, 2021 |
| HP            | Pavilion dv6000 (RP981EA... | [56844725d1](https://bsd-hardware.info/?probe=56844725d1) | Mar 08, 2021 |
| HP            | Laptop 15-da0xxx            | [bf572bc102](https://bsd-hardware.info/?probe=bf572bc102) | Mar 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [be2ad24d1b](https://bsd-hardware.info/?probe=be2ad24d1b) | Mar 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0e06b5f17f](https://bsd-hardware.info/?probe=0e06b5f17f) | Mar 06, 2021 |
| Dell          | Latitude 5280               | [b84364959d](https://bsd-hardware.info/?probe=b84364959d) | Mar 04, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [1f226262cc](https://bsd-hardware.info/?probe=1f226262cc) | Mar 04, 2021 |
| ASUSTek       | X550LC                      | [e056f1c77c](https://bsd-hardware.info/?probe=e056f1c77c) | Mar 03, 2021 |
| Fujitsu       | LIFEBOOK E754               | [d3d033f879](https://bsd-hardware.info/?probe=d3d033f879) | Mar 03, 2021 |
| Fujitsu       | LIFEBOOK E736               | [845c584693](https://bsd-hardware.info/?probe=845c584693) | Mar 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [eb7d8c3502](https://bsd-hardware.info/?probe=eb7d8c3502) | Mar 02, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [0dc468c860](https://bsd-hardware.info/?probe=0dc468c860) | Feb 22, 2021 |
| ASUSTek       | X751LN                      | [fe7d72b06a](https://bsd-hardware.info/?probe=fe7d72b06a) | Feb 21, 2021 |
| GEO           | GeoBook3                    | [ba18b9bf80](https://bsd-hardware.info/?probe=ba18b9bf80) | Feb 19, 2021 |
| Clevo         | W55xEU                      | [a66041bae0](https://bsd-hardware.info/?probe=a66041bae0) | Feb 17, 2021 |
| Pegatron      | T12Ah                       | [a5ab7068dc](https://bsd-hardware.info/?probe=a5ab7068dc) | Feb 14, 2021 |
| Clevo         | W55xEU                      | [796ad51947](https://bsd-hardware.info/?probe=796ad51947) | Feb 11, 2021 |
| Clevo         | W55xEU                      | [c28a6397b5](https://bsd-hardware.info/?probe=c28a6397b5) | Feb 11, 2021 |
| Alienware     | M18xR1                      | [67a336fac6](https://bsd-hardware.info/?probe=67a336fac6) | Feb 08, 2021 |
| Dell          | Latitude 3410               | [f81c1e338f](https://bsd-hardware.info/?probe=f81c1e338f) | Feb 07, 2021 |
| Dell          | Latitude E4300              | [84925c014a](https://bsd-hardware.info/?probe=84925c014a) | Feb 01, 2021 |
| Pegatron      | T12Ah                       | [4bda74f229](https://bsd-hardware.info/?probe=4bda74f229) | Jan 31, 2021 |
| Dell          | Latitude 5400               | [f242897c33](https://bsd-hardware.info/?probe=f242897c33) | Jan 13, 2021 |
| Dell          | Latitude 5490               | [3fba47b07f](https://bsd-hardware.info/?probe=3fba47b07f) | Jan 12, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [ba45e27f88](https://bsd-hardware.info/?probe=ba45e27f88) | Jan 12, 2021 |
| ASUSTek       | N75SF                       | [7efb6557a2](https://bsd-hardware.info/?probe=7efb6557a2) | Jan 10, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [9ccf63e228](https://bsd-hardware.info/?probe=9ccf63e228) | Jan 09, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [e18df4623a](https://bsd-hardware.info/?probe=e18df4623a) | Jan 09, 2021 |
| Sony          | VPCM13M1R                   | [30bb4fc23c](https://bsd-hardware.info/?probe=30bb4fc23c) | Jan 06, 2021 |
| NEC Comput... | PC-GL186Y3AZ                | [b9f8e78467](https://bsd-hardware.info/?probe=b9f8e78467) | Jan 05, 2021 |
| Dell          | Latitude 5280               | [1ae6e6ee2d](https://bsd-hardware.info/?probe=1ae6e6ee2d) | Jan 05, 2021 |
| Lenovo        | ThinkPad X201 Tablet 311... | [df9318dcea](https://bsd-hardware.info/?probe=df9318dcea) | Dec 27, 2020 |
| Dell          | Inspiron 5758               | [51ed7b02c2](https://bsd-hardware.info/?probe=51ed7b02c2) | Dec 21, 2020 |
| Acer          | Aspire V5-122               | [ce0c079fd5](https://bsd-hardware.info/?probe=ce0c079fd5) | Dec 14, 2020 |
| Apple         | MacBookPro11,3              | [26f15a2838](https://bsd-hardware.info/?probe=26f15a2838) | Dec 07, 2020 |
| Lenovo        | ThinkPad T490 20RYS06R00    | [21d88f733e](https://bsd-hardware.info/?probe=21d88f733e) | Dec 07, 2020 |
| Lenovo        | ThinkPad T490 20RYS06R00    | [cdfcd11f7b](https://bsd-hardware.info/?probe=cdfcd11f7b) | Dec 07, 2020 |
| IBM           | 2647NG8                     | [a0f38de52f](https://bsd-hardware.info/?probe=a0f38de52f) | Nov 22, 2020 |
| HP            | ProBook 640 G1              | [bf763e72ad](https://bsd-hardware.info/?probe=bf763e72ad) | Nov 13, 2020 |
| Acer          | Aspire E5-432               | [39fb05c049](https://bsd-hardware.info/?probe=39fb05c049) | Nov 01, 2020 |
| Acer          | Aspire V3-575G              | [1ff0e90d9d](https://bsd-hardware.info/?probe=1ff0e90d9d) | Oct 24, 2020 |
| Google        | Chell                       | [4ffe68c199](https://bsd-hardware.info/?probe=4ffe68c199) | Oct 21, 2020 |
| Apple         | MacBookAir7,2               | [36d0d99aa6](https://bsd-hardware.info/?probe=36d0d99aa6) | Oct 04, 2020 |
| Lenovo        | G50-45 80E3                 | [1d227a9cd2](https://bsd-hardware.info/?probe=1d227a9cd2) | Oct 04, 2020 |
| Dell          | Precision 7530              | [717309ee39](https://bsd-hardware.info/?probe=717309ee39) | Sep 28, 2020 |
| Dell          | Precision 7530              | [6a2635237f](https://bsd-hardware.info/?probe=6a2635237f) | Sep 28, 2020 |
| Lenovo        | ThinkPad T530 24295VU       | [f7d13e4696](https://bsd-hardware.info/?probe=f7d13e4696) | Sep 23, 2020 |
| Lenovo        | ThinkPad T530 24295VU       | [45f410f4e4](https://bsd-hardware.info/?probe=45f410f4e4) | Sep 23, 2020 |
| Lenovo        | ThinkPad T430 2347C32       | [339c63a941](https://bsd-hardware.info/?probe=339c63a941) | Sep 22, 2020 |
| Apple         | MacBookPro8,1               | [89bb299f1e](https://bsd-hardware.info/?probe=89bb299f1e) | Sep 22, 2020 |
| Dell          | Vostro 3750                 | [587a9276bb](https://bsd-hardware.info/?probe=587a9276bb) | Sep 06, 2020 |
| Panasonic     | CF-C1BD06EFG                | [3e876bada1](https://bsd-hardware.info/?probe=3e876bada1) | Sep 02, 2020 |
| Dell          | Inspiron 15-3567            | [4d1897ed1f](https://bsd-hardware.info/?probe=4d1897ed1f) | Aug 29, 2020 |
| Lenovo        | ThinkPad T460 20FMS78014    | [d78837860f](https://bsd-hardware.info/?probe=d78837860f) | Aug 23, 2020 |
| Dell          | Inspiron 5567               | [5ef34cd40f](https://bsd-hardware.info/?probe=5ef34cd40f) | Aug 20, 2020 |
| Acer          | Aspire 5735                 | [6ca9384f34](https://bsd-hardware.info/?probe=6ca9384f34) | Aug 20, 2020 |
| ASUSTek       | X71SL                       | [a2ee0c9edb](https://bsd-hardware.info/?probe=a2ee0c9edb) | Aug 15, 2020 |
| HP            | ProBook 640 G1              | [4b7eaf5a6a](https://bsd-hardware.info/?probe=4b7eaf5a6a) | Aug 12, 2020 |
| Dell          | Latitude 5480               | [907e0da9a4](https://bsd-hardware.info/?probe=907e0da9a4) | Aug 08, 2020 |
| HP            | EliteBook 820 G1            | [12ac8fc96f](https://bsd-hardware.info/?probe=12ac8fc96f) | Aug 07, 2020 |
| Google        | Lulu                        | [64aef60e6b](https://bsd-hardware.info/?probe=64aef60e6b) | Aug 02, 2020 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [0919d8936f](https://bsd-hardware.info/?probe=0919d8936f) | Jul 27, 2020 |
| Lenovo        | G570 20079                  | [15e87049a7](https://bsd-hardware.info/?probe=15e87049a7) | Jul 27, 2020 |
| Lenovo        | ThinkPad T450 20BUS06B00    | [f437a3b5ab](https://bsd-hardware.info/?probe=f437a3b5ab) | Jul 06, 2020 |
| Unknown       | Unknown                     | [f9ed1dce06](https://bsd-hardware.info/?probe=f9ed1dce06) | Jul 05, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0VK0... | [b726c4536b](https://bsd-hardware.info/?probe=b726c4536b) | Jul 04, 2020 |
| Dell          | Latitude E7240              | [1de87c0000](https://bsd-hardware.info/?probe=1de87c0000) | May 30, 2020 |
| ASUSTek       | X71SL                       | [adf290251e](https://bsd-hardware.info/?probe=adf290251e) | May 09, 2020 |
| Sony          | SVE1713S1RW                 | [9a751ddfd8](https://bsd-hardware.info/?probe=9a751ddfd8) | May 08, 2020 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 76        | 91.57%  |
| i386  | 7         | 8.43%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Openbox | 74        | 90.24%  |
| GNOME   | 6         | 7.32%   |
| XFCE    | 1         | 1.22%   |
| KDE5    | 1         | 1.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 82        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 82        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 32        | 38.55%  |
| Unknown | 15        | 18.07%  |
| de_DE   | 10        | 12.05%  |
| en_GB   | 6         | 7.23%   |
| ru_RU   | 4         | 4.82%   |
| it_IT   | 3         | 3.61%   |
| pl_PL   | 2         | 2.41%   |
| hu_HU   | 2         | 2.41%   |
| es_ES   | 2         | 2.41%   |
| zh_CN   | 1         | 1.2%    |
| tr_TR   | 1         | 1.2%    |
| ko_KR   | 1         | 1.2%    |
| fr_FR   | 1         | 1.2%    |
| en_AU   | 1         | 1.2%    |
| cs_CZ   | 1         | 1.2%    |
| bg_BG   | 1         | 1.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 77        | 92.77%  |
| BIOS | 6         | 7.23%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ufs  | 75        | 91.46%  |
| Zfs  | 7         | 8.54%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 56        | 67.47%  |
| MBR  | 27        | 32.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 18        | 21.95%  |
| Dell                | 12        | 14.63%  |
| Hewlett-Packard     | 11        | 13.41%  |
| ASUSTek Computer    | 9         | 10.98%  |
| Acer                | 6         | 7.32%   |
| Apple               | 4         | 4.88%   |
| Sony                | 3         | 3.66%   |
| Samsung Electronics | 2         | 2.44%   |
| Google              | 2         | 2.44%   |
| Fujitsu             | 2         | 2.44%   |
| TUXEDO              | 1         | 1.22%   |
| Toshiba             | 1         | 1.22%   |
| Pegatron            | 1         | 1.22%   |
| Panasonic           | 1         | 1.22%   |
| Notebook            | 1         | 1.22%   |
| NEC Computers       | 1         | 1.22%   |
| MSI                 | 1         | 1.22%   |
| IBM                 | 1         | 1.22%   |
| GEO                 | 1         | 1.22%   |
| Fujitsu Siemens     | 1         | 1.22%   |
| Clevo               | 1         | 1.22%   |
| Alienware           | 1         | 1.22%   |
| Unknown             | 1         | 1.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 2         | 2.44%   |
| Toshiba Satellite C660                   | 1         | 1.22%   |
| Sony VPCM13M1R                           | 1         | 1.22%   |
| Sony VJS121C11N                          | 1         | 1.22%   |
| Sony SVE1713S1RW                         | 1         | 1.22%   |
| Samsung N145P/N250P/N260P                | 1         | 1.22%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV  | 1         | 1.22%   |
| Pegatron T12Ah                           | 1         | 1.22%   |
| Panasonic CF-C1BD06EFG                   | 1         | 1.22%   |
| Notebook N650DU                          | 1         | 1.22%   |
| NEC Computers PC-GL186Y3AZ               | 1         | 1.22%   |
| MSI MS-N033                              | 1         | 1.22%   |
| Lenovo ThinkPad X201 Tablet 311396U      | 1         | 1.22%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB001XAU | 1         | 1.22%   |
| Lenovo ThinkPad W541 20EGS04800          | 1         | 1.22%   |
| Lenovo ThinkPad T530 24295VU             | 1         | 1.22%   |
| Lenovo ThinkPad T510 4384FF3             | 1         | 1.22%   |
| Lenovo ThinkPad T490s 20NX000DRT         | 1         | 1.22%   |
| Lenovo ThinkPad T490 20RYS06R00          | 1         | 1.22%   |
| Lenovo ThinkPad T470s W10DG 20JS001FGE   | 1         | 1.22%   |
| Lenovo ThinkPad T460 20FMS78014          | 1         | 1.22%   |
| Lenovo ThinkPad T450 20BUS06B00          | 1         | 1.22%   |
| Lenovo ThinkPad T440p 20AWS0VK00         | 1         | 1.22%   |
| Lenovo ThinkPad T430 2347C32             | 1         | 1.22%   |
| Lenovo ThinkPad S1 Yoga 20C0S0M300       | 1         | 1.22%   |
| Lenovo Legion Y7000 2019 PG0 81T0        | 1         | 1.22%   |
| Lenovo IdeaPad S145-15API 81UT           | 1         | 1.22%   |
| Lenovo IdeaPad 110-15IBR 80T7            | 1         | 1.22%   |
| Lenovo G570 20079                        | 1         | 1.22%   |
| Lenovo G50-45 80E3                       | 1         | 1.22%   |
| IBM 2647NG8                              | 1         | 1.22%   |
| HP ZBook Studio G3                       | 1         | 1.22%   |
| HP ProBook 640 G1                        | 1         | 1.22%   |
| HP Pavilion Notebook                     | 1         | 1.22%   |
| HP Pavilion g6                           | 1         | 1.22%   |
| HP Pavilion dv6000 (RP981EA#AB8)         | 1         | 1.22%   |
| HP OMEN by HP Laptop 17-cb1xxx           | 1         | 1.22%   |
| HP Notebook                              | 1         | 1.22%   |
| HP Laptop 15-db0xxx                      | 1         | 1.22%   |
| HP Laptop 15-da0xxx                      | 1         | 1.22%   |
| HP EliteBook 820 G1                      | 1         | 1.22%   |
| HP 2000                                  | 1         | 1.22%   |
| Google Lulu                              | 1         | 1.22%   |
| Google Chell                             | 1         | 1.22%   |
| GEO GeoBook3                             | 1         | 1.22%   |
| Fujitsu Siemens AMILO PRO V3515          | 1         | 1.22%   |
| Fujitsu LIFEBOOK E754                    | 1         | 1.22%   |
| Fujitsu LIFEBOOK E736                    | 1         | 1.22%   |
| Dell Vostro 3750                         | 1         | 1.22%   |
| Dell Precision 7530                      | 1         | 1.22%   |
| Dell Latitude E7240                      | 1         | 1.22%   |
| Dell Latitude D630                       | 1         | 1.22%   |
| Dell Latitude 5490                       | 1         | 1.22%   |
| Dell Latitude 5480                       | 1         | 1.22%   |
| Dell Latitude 5400                       | 1         | 1.22%   |
| Dell Latitude 5280                       | 1         | 1.22%   |
| Dell Latitude 3410                       | 1         | 1.22%   |
| Dell Inspiron 5567                       | 1         | 1.22%   |
| Dell Inspiron 15-5568                    | 1         | 1.22%   |
| Dell Inspiron 15-3567                    | 1         | 1.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 13        | 15.85%  |
| Dell Latitude              | 7         | 8.54%   |
| Acer Aspire                | 6         | 7.32%   |
| HP Pavilion                | 3         | 3.66%   |
| Dell Inspiron              | 3         | 3.66%   |
| Lenovo IdeaPad             | 2         | 2.44%   |
| HP Laptop                  | 2         | 2.44%   |
| Fujitsu LIFEBOOK           | 2         | 2.44%   |
| Unknown                    | 2         | 2.44%   |
| Toshiba Satellite          | 1         | 1.22%   |
| Sony VPCM13M1R             | 1         | 1.22%   |
| Sony VJS121C11N            | 1         | 1.22%   |
| Sony SVE1713S1RW           | 1         | 1.22%   |
| Samsung N145P              | 1         | 1.22%   |
| Samsung 300E5EV            | 1         | 1.22%   |
| Pegatron T12Ah             | 1         | 1.22%   |
| Panasonic CF-C1BD06EFG     | 1         | 1.22%   |
| Notebook N650DU            | 1         | 1.22%   |
| NEC Computers PC-GL186Y3AZ | 1         | 1.22%   |
| MSI MS-N033                | 1         | 1.22%   |
| Lenovo Legion              | 1         | 1.22%   |
| Lenovo G570                | 1         | 1.22%   |
| Lenovo G50-45              | 1         | 1.22%   |
| IBM 2647NG8                | 1         | 1.22%   |
| HP ZBook                   | 1         | 1.22%   |
| HP ProBook                 | 1         | 1.22%   |
| HP OMEN                    | 1         | 1.22%   |
| HP Notebook                | 1         | 1.22%   |
| HP EliteBook               | 1         | 1.22%   |
| HP 2000                    | 1         | 1.22%   |
| Google Lulu                | 1         | 1.22%   |
| Google Chell               | 1         | 1.22%   |
| GEO GeoBook3               | 1         | 1.22%   |
| Fujitsu Siemens AMILO      | 1         | 1.22%   |
| Dell Vostro                | 1         | 1.22%   |
| Dell Precision             | 1         | 1.22%   |
| Clevo W55xEU               | 1         | 1.22%   |
| ASUS X751LN                | 1         | 1.22%   |
| ASUS X71SL                 | 1         | 1.22%   |
| ASUS X550LC                | 1         | 1.22%   |
| ASUS X540YA                | 1         | 1.22%   |
| ASUS X202E                 | 1         | 1.22%   |
| ASUS VivoBook              | 1         | 1.22%   |
| ASUS TUF                   | 1         | 1.22%   |
| ASUS N75SF                 | 1         | 1.22%   |
| ASUS 1000                  | 1         | 1.22%   |
| Apple MacBookPro8          | 1         | 1.22%   |
| Apple MacBookPro11         | 1         | 1.22%   |
| Apple MacBookAir7          | 1         | 1.22%   |
| Apple MacBookAir6          | 1         | 1.22%   |
| Alienware M18xR1           | 1         | 1.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 13        | 15.85%  |
| 2020 | 10        | 12.2%   |
| 2017 | 6         | 7.32%   |
| 2015 | 6         | 7.32%   |
| 2014 | 6         | 7.32%   |
| 2011 | 6         | 7.32%   |
| 2016 | 5         | 6.1%    |
| 2012 | 5         | 6.1%    |
| 2010 | 5         | 6.1%    |
| 2008 | 5         | 6.1%    |
| 2018 | 4         | 4.88%   |
| 2013 | 4         | 4.88%   |
| 2021 | 3         | 3.66%   |
| 2006 | 2         | 2.44%   |
| 2009 | 1         | 1.22%   |
| 2004 | 1         | 1.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 82        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 80        | 97.56%  |
| Yes  | 2         | 2.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 37        | 44.58%  |
| 4.01-8.0    | 20        | 24.1%   |
| 16.01-24.0  | 13        | 15.66%  |
| 32.01-64.0  | 4         | 4.82%   |
| 2.01-3.0    | 3         | 3.61%   |
| 0.51-1.0    | 3         | 3.61%   |
| 3.01-4.0    | 2         | 2.41%   |
| 64.01-256.0 | 1         | 1.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 47        | 55.95%  |
| 0.51-1.0  | 23        | 27.38%  |
| 1.01-2.0  | 7         | 8.33%   |
| 2.01-3.0  | 3         | 3.57%   |
| 4.01-8.0  | 2         | 2.38%   |
| 3.01-4.0  | 1         | 1.19%   |
| 8.01-16.0 | 1         | 1.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 64        | 78.05%  |
| 2      | 10        | 12.2%   |
| 0      | 6         | 7.32%   |
| 3      | 2         | 2.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 50        | 60.24%  |
| Yes       | 33        | 39.76%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 87.95%  |
| No        | 10        | 12.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 98.78%  |
| No        | 1         | 1.22%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 70.73%  |
| No        | 24        | 29.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 12        | 14.63%  |
| Germany     | 11        | 13.41%  |
| Russia      | 10        | 12.2%   |
| France      | 9         | 10.98%  |
| UK          | 7         | 8.54%   |
| Italy       | 5         | 6.1%    |
| Mexico      | 3         | 3.66%   |
| Turkey      | 2         | 2.44%   |
| Romania     | 2         | 2.44%   |
| Poland      | 2         | 2.44%   |
| Norway      | 2         | 2.44%   |
| Japan       | 2         | 2.44%   |
| Hungary     | 2         | 2.44%   |
| Colombia    | 2         | 2.44%   |
| Ukraine     | 1         | 1.22%   |
| Spain       | 1         | 1.22%   |
| South Korea | 1         | 1.22%   |
| Philippines | 1         | 1.22%   |
| Hong Kong   | 1         | 1.22%   |
| Denmark     | 1         | 1.22%   |
| Czechia     | 1         | 1.22%   |
| China       | 1         | 1.22%   |
| Bulgaria    | 1         | 1.22%   |
| Australia   | 1         | 1.22%   |
| Argentina   | 1         | 1.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Moscow                | 7         | 8.33%   |
| Franconville          | 6         | 7.14%   |
| Whittier              | 3         | 3.57%   |
| Tijuana               | 3         | 3.57%   |
| Markt Indersdorf      | 3         | 3.57%   |
| Zwingenberg           | 2         | 2.38%   |
| Setagaya-ku           | 2         | 2.38%   |
| Rome                  | 2         | 2.38%   |
| New Braunfels         | 2         | 2.38%   |
| Los Angeles           | 2         | 2.38%   |
| Istanbul              | 2         | 2.38%   |
| Hodmezovasarhely      | 2         | 2.38%   |
| Greenwich             | 2         | 2.38%   |
| Drobeta-Turnu Severin | 2         | 2.38%   |
| Woodland              | 1         | 1.19%   |
| Wloszczowa            | 1         | 1.19%   |
| Wissen                | 1         | 1.19%   |
| Wilhelmshaven         | 1         | 1.19%   |
| Warsaw                | 1         | 1.19%   |
| Vollen                | 1         | 1.19%   |
| Vladimir              | 1         | 1.19%   |
| Vertou                | 1         | 1.19%   |
| Trieste               | 1         | 1.19%   |
| Swindon               | 1         | 1.19%   |
| Suwon                 | 1         | 1.19%   |
| St Petersburg         | 1         | 1.19%   |
| Southampton           | 1         | 1.19%   |
| Sofia                 | 1         | 1.19%   |
| Shanghai              | 1         | 1.19%   |
| Sedavi                | 1         | 1.19%   |
| San Bernardino        | 1         | 1.19%   |
| Saint-Denis           | 1         | 1.19%   |
| Rionegro              | 1         | 1.19%   |
| Pasig                 | 1         | 1.19%   |
| Paris                 | 1         | 1.19%   |
| Palmer                | 1         | 1.19%   |
| Oslo                  | 1         | 1.19%   |
| Nueve de Julio        | 1         | 1.19%   |
| Novosibirsk           | 1         | 1.19%   |
| Munich                | 1         | 1.19%   |
| Milan                 | 1         | 1.19%   |
| McDonough             | 1         | 1.19%   |
| Malton                | 1         | 1.19%   |
| London                | 1         | 1.19%   |
| Kyiv                  | 1         | 1.19%   |
| Kowloon               | 1         | 1.19%   |
| Hranice               | 1         | 1.19%   |
| Greifswald            | 1         | 1.19%   |
| Grafing bei Munchen   | 1         | 1.19%   |
| Glasgow               | 1         | 1.19%   |
| DÃ¼sseldorf         | 1         | 1.19%   |
| Copenhagen            | 1         | 1.19%   |
| Chino Hills           | 1         | 1.19%   |
| Brisbane              | 1         | 1.19%   |
| Brighton              | 1         | 1.19%   |
| Bologna               | 1         | 1.19%   |
| BogotГЎ             | 1         | 1.19%   |
| Atlanta               | 1         | 1.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 18     | 18.39%  |
| Samsung Electronics | 16        | 20     | 18.39%  |
| Toshiba             | 10        | 10     | 11.49%  |
| Seagate             | 10        | 11     | 11.49%  |
| Apple               | 5         | 6      | 5.75%   |
| SanDisk             | 3         | 3      | 3.45%   |
| Hitachi             | 3         | 3      | 3.45%   |
| Crucial             | 3         | 3      | 3.45%   |
| OCZ                 | 2         | 2      | 2.3%    |
| Micron Technology   | 2         | 2      | 2.3%    |
| Kingston            | 2         | 2      | 2.3%    |
| Intel               | 2         | 2      | 2.3%    |
| Fujitsu             | 2         | 3      | 2.3%    |
| Transcend           | 1         | 1      | 1.15%   |
| SPCC                | 1         | 1      | 1.15%   |
| SK Hynix            | 1         | 1      | 1.15%   |
| PNY                 | 1         | 1      | 1.15%   |
| LITEONIT            | 1         | 1      | 1.15%   |
| KingDian            | 1         | 1      | 1.15%   |
| Intenso             | 1         | 1      | 1.15%   |
| HGST                | 1         | 1      | 1.15%   |
| Gigabyte Technology | 1         | 1      | 1.15%   |
| Corsair             | 1         | 1      | 1.15%   |
| ASUSTek Computer    | 1         | 2      | 1.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                    | 3         | 3.3%    |
| Toshiba MQ01ABF050 500GB                  | 2         | 2.2%    |
| Seagate ST95005620AS 500GB                | 2         | 2.2%    |
| SanDisk pSSD 256GB                        | 2         | 2.2%    |
| Crucial CT500MX500SSD1 500GB              | 2         | 2.2%    |
| Apple SSD SM0512F 500GB                   | 2         | 2.2%    |
| WDC WDS240G2G0A-00JH30 240GB              | 1         | 1.1%    |
| WDC WDS120G2G0B-00EPW0 120GB              | 1         | 1.1%    |
| WDC WDS120G1G0A-00SS50 120GB              | 1         | 1.1%    |
| WDC WD7500BPKT-75PK4T0 752GB              | 1         | 1.1%    |
| WDC WD3200BEKT-60PVMT0 320GB              | 1         | 1.1%    |
| WDC WD2500LPCX-24C6HT0 250GB              | 1         | 1.1%    |
| WDC WD2500BEVT-80A23T0 250GB              | 1         | 1.1%    |
| WDC WD1200BEVS-07LAT0 120GB               | 1         | 1.1%    |
| WDC WD10SPZX-60Z10T0 1TB                  | 1         | 1.1%    |
| WDC WD10SPZX-00Z10T0 1TB                  | 1         | 1.1%    |
| WDC WD10SMRW-11Y43S0 1TB                  | 1         | 1.1%    |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 1.1%    |
| WDC WD10JPVX-60JC3T0 1TB                  | 1         | 1.1%    |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 1.1%    |
| WDC PC SN720 SDAPNTW-1T00-1006 1TB        | 1         | 1.1%    |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB      | 1         | 1.1%    |
| WDC PC SN520 SDAPNUW-256G-1002 256GB      | 1         | 1.1%    |
| WDC PC SN520 SDAPMUW-128G-1101 128GB      | 1         | 1.1%    |
| Transcend TS512GSSD370S 512GB             | 1         | 1.1%    |
| Toshiba TR200 240GB                       | 1         | 1.1%    |
| Toshiba THNSNC128GBSJ                     | 1         | 1.1%    |
| Toshiba MQ04ABF100 1TB                    | 1         | 1.1%    |
| Toshiba MK7575GSX 752GB                   | 1         | 1.1%    |
| Toshiba KSG60ZMV256G M.2 2280 256GB       | 1         | 1.1%    |
| SPCC Solid State Disk 240GB               | 1         | 1.1%    |
| SK Hynix SKHynix_HFS512GD9TNG-L5B0B 512GB | 1         | 1.1%    |
| Seagate ST9750423AS 752GB                 | 1         | 1.1%    |
| Seagate ST9500325AS 500GB                 | 1         | 1.1%    |
| Seagate ST500LT012-9WS142 500GB           | 1         | 1.1%    |
| Seagate ST500LM021-1KJ152 500GB           | 1         | 1.1%    |
| Seagate ST2000LM015-2E8174 2TB            | 1         | 1.1%    |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 1.1%    |
| Seagate ST1000LM035-1RK172 1TB            | 1         | 1.1%    |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 1.1%    |
| SanDisk SD9SN8W-128G-1006 128GB           | 1         | 1.1%    |
| Samsung SSD PM810 2.5-inch 7mm 256GB      | 1         | 1.1%    |
| Samsung SSD 970 PRO 1TB                   | 1         | 1.1%    |
| Samsung SSD 970 EVO Plus 500GB            | 1         | 1.1%    |
| Samsung SSD 970 EVO Plus 1TB              | 1         | 1.1%    |
| Samsung SSD 860 EVO 250GB                 | 1         | 1.1%    |
| Samsung SSD 850 PRO 512GB                 | 1         | 1.1%    |
| Samsung SSD 850 EVO 250GB                 | 1         | 1.1%    |
| Samsung SSD 840 EVO 250GB                 | 1         | 1.1%    |
| Samsung PM981 NVMe 256GB                  | 1         | 1.1%    |
| Samsung MZVLB256HBHQ-000L7 256GB          | 1         | 1.1%    |
| Samsung MZVLB256HBHQ-000L2 256GB          | 1         | 1.1%    |
| Samsung MZVLB256HAHQ-00000 256GB          | 1         | 1.1%    |
| Samsung MZVKW512HMJP-000H1 512GB          | 1         | 1.1%    |
| Samsung MZNLN256HCHP-000L7 256GB          | 1         | 1.1%    |
| Samsung MZMTD256HAGM-000L1 256GB          | 1         | 1.1%    |
| Samsung MZ7TY128HDHP-00000 128GB          | 1         | 1.1%    |
| Samsung MZ7TE128HMGR-00004 128GB          | 1         | 1.1%    |
| Samsung MZ7TD128HAFV-000L1 128GB          | 1         | 1.1%    |
| PNY CS1311 120GB SSD                      | 1         | 1.1%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 11        | 11     | 31.43%  |
| Seagate | 10        | 11     | 28.57%  |
| Toshiba | 7         | 7      | 20%     |
| Hitachi | 3         | 3      | 8.57%   |
| Fujitsu | 2         | 3      | 5.71%   |
| HGST    | 1         | 1      | 2.86%   |
| Apple   | 1         | 1      | 2.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 11     | 22.5%   |
| Apple               | 4         | 5      | 10%     |
| Toshiba             | 3         | 3      | 7.5%    |
| SanDisk             | 3         | 3      | 7.5%    |
| WDC                 | 2         | 3      | 5%      |
| OCZ                 | 2         | 2      | 5%      |
| Micron Technology   | 2         | 2      | 5%      |
| Kingston            | 2         | 2      | 5%      |
| Intel               | 2         | 2      | 5%      |
| Crucial             | 2         | 2      | 5%      |
| Transcend           | 1         | 1      | 2.5%    |
| SPCC                | 1         | 1      | 2.5%    |
| PNY                 | 1         | 1      | 2.5%    |
| LITEONIT            | 1         | 1      | 2.5%    |
| KingDian            | 1         | 1      | 2.5%    |
| Intenso             | 1         | 1      | 2.5%    |
| Gigabyte Technology | 1         | 1      | 2.5%    |
| Corsair             | 1         | 1      | 2.5%    |
| ASUSTek Computer    | 1         | 2      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 38        | 45     | 44.19%  |
| HDD  | 35        | 37     | 40.7%   |
| NVMe | 13        | 15     | 15.12%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 68        | 82     | 83.95%  |
| NVMe | 13        | 15     | 16.05%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 51        | 61     | 71.83%  |
| 0.51-1.0   | 19        | 20     | 26.76%  |
| 1.01-2.0   | 1         | 1      | 1.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 68        | 82.93%  |
| 101-250    | 6         | 7.32%   |
| 51-100     | 3         | 3.66%   |
| 251-500    | 2         | 2.44%   |
| 21-50      | 2         | 2.44%   |
| 501-1000   | 1         | 1.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 80        | 96.39%  |
| 21-50   | 2         | 2.41%   |
| 51-100  | 1         | 1.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPKT-75PK4T0 752GB                     | 1         | 1      | 5.26%   |
| WDC WD2500BEVT-80A23T0 250GB                     | 1         | 1      | 5.26%   |
| WDC WD1200BEVS-07LAT0 120GB                      | 1         | 1      | 5.26%   |
| WDC WD10JPVX-75JC3T0 1TB                         | 1         | 1      | 5.26%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 5.26%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 5.26%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 5.26%   |
| Toshiba MK7575GSX 752GB                          | 1         | 1      | 5.26%   |
| Seagate ST95005620AS 500GB                       | 1         | 1      | 5.26%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 5.26%   |
| Seagate ST500LM021-1KJ152 500GB                  | 1         | 1      | 5.26%   |
| SanDisk SD9SN8W-128G-1006 128GB                  | 1         | 1      | 5.26%   |
| Samsung Electronics SSD PM810 2.5-inch 7mm 256GB | 1         | 1      | 5.26%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB       | 1         | 1      | 5.26%   |
| Intel SSDSC2CW060A3 64GB                         | 1         | 1      | 5.26%   |
| Hitachi HTS545032B9A302 320GB                    | 1         | 1      | 5.26%   |
| Hitachi HTS545032B9A300 320GB                    | 1         | 1      | 5.26%   |
| HGST HTS725050A7E630 500GB                       | 1         | 1      | 5.26%   |
| Corsair Neutron GTX SSD 120GB                    | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 26.32%  |
| Toshiba             | 3         | 3      | 15.79%  |
| Seagate             | 3         | 3      | 15.79%  |
| Hitachi             | 2         | 2      | 10.53%  |
| SanDisk             | 1         | 1      | 5.26%   |
| Samsung Electronics | 1         | 1      | 5.26%   |
| Micron Technology   | 1         | 1      | 5.26%   |
| Intel               | 1         | 1      | 5.26%   |
| HGST                | 1         | 1      | 5.26%   |
| Corsair             | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 35.71%  |
| Toshiba | 3         | 3      | 21.43%  |
| Seagate | 3         | 3      | 21.43%  |
| Hitachi | 2         | 2      | 14.29%  |
| HGST    | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 14     | 73.68%  |
| SSD  | 5         | 5      | 26.32%  |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 61        | 76     | 75.31%  |
| Malfunc  | 19        | 19     | 23.46%  |
| Detected | 1         | 2      | 1.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 62        | 67.39%  |
| Samsung Electronics              | 11        | 11.96%  |
| AMD                              | 11        | 11.96%  |
| Sandisk                          | 4         | 4.35%   |
| VIA Technologies                 | 1         | 1.09%   |
| SK Hynix                         | 1         | 1.09%   |
| Silicon Integrated Systems [SiS] | 1         | 1.09%   |
| Micron/Crucial Technology        | 1         | 1.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 10        | 10%     |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 9         | 9%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 6         | 6%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 6         | 6%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 6         | 6%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 5         | 5%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 5         | 5%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 3%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 3%      |
| Samsung SM951 AHCI                                                                     | 2         | 2%      |
| Samsung Apple PCIe SSD                                                                 | 2         | 2%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 2         | 2%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 2%      |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 2%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 2         | 2%      |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 2         | 2%      |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 2         | 2%      |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 2         | 2%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 2%      |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                            | 1         | 1%      |
| VIA VT8237A SATA 2-Port Controller                                                     | 1         | 1%      |
| SK Hynix hynix unknown                                                                 | 1         | 1%      |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 1         | 1%      |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 1         | 1%      |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 1         | 1%      |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 1         | 1%      |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 1         | 1%      |
| Sandisk PC SN520 NVMe SSD                                                              | 1         | 1%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 1%      |
| Micron/Crucial NVMe Controller                                                         | 1         | 1%      |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 1         | 1%      |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 1         | 1%      |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 1%      |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                                   | 1         | 1%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 1%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 1         | 1%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 1         | 1%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 1%      |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1%      |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 1%      |
| Intel 82801CAM IDE U100 Controller                                                     | 1         | 1%      |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]          | 1         | 1%      |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile             | 1         | 1%      |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1%      |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1%      |
| AMD FCH SATA Controller [IDE mode]                                                     | 1         | 1%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 60        | 64.52%  |
| NVMe | 13        | 13.98%  |
| IDE  | 13        | 13.98%  |
| RAID | 7         | 7.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 72        | 86.75%  |
| AMD    | 11        | 13.25%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 4.82%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 2         | 2.41%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 2         | 2.41%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 2.41%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 2.41%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 2.41%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 2.41%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 2         | 2.41%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 2.41%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz        | 1         | 1.2%    |
| Intel Pentium III                           | 1         | 1.2%    |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 1.2%    |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 1.2%    |
| Intel Pentium CPU 2117U @ 1.80GHz           | 1         | 1.2%    |
| Intel Genuine CPU U7300 @ 1.30GHz           | 1         | 1.2%    |
| Intel CPU Version                           | 1         | 1.2%    |
| Intel Core m5-6Y57 CPU @ 1.10GHz            | 1         | 1.2%    |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 1.2%    |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 1.2%    |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.2%    |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 1.2%    |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 1.2%    |
| Intel Core i7-4900MQ CPU @ 2.80GHz          | 1         | 1.2%    |
| Intel Core i7-4850HQ CPU @ 2.30GHz          | 1         | 1.2%    |
| Intel Core i7-4770HQ CPU @ 2.20GHz          | 1         | 1.2%    |
| Intel Core i7-4650U CPU @ 1.70GHz           | 1         | 1.2%    |
| Intel Core i7-4610M CPU @ 3.00GHz           | 1         | 1.2%    |
| Intel Core i7-4510U CPU @ 2.00GHz           | 1         | 1.2%    |
| Intel Core i7-4500U CPU @ 1.80GHz           | 1         | 1.2%    |
| Intel Core i7-4500U CPU                     | 1         | 1.2%    |
| Intel Core i7-3537U CPU @ 2.00GHz           | 1         | 1.2%    |
| Intel Core i7-2820QM CPU @ 2.30GHz          | 1         | 1.2%    |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.2%    |
| Intel Core i7 CPU L 640 @ 2.13GHz           | 1         | 1.2%    |
| Intel Core i5-9300HF CPU @ 2.40GHz          | 1         | 1.2%    |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.2%    |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.2%    |
| Intel Core i5-5350U CPU @ 1.80GHz           | 1         | 1.2%    |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 1.2%    |
| Intel Core i5-4310M CPU @ 2.70GHz           | 1         | 1.2%    |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.2%    |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.2%    |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 1.2%    |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.2%    |
| Intel Core i5-10310U CPU @ 1.70GHz          | 1         | 1.2%    |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 1.2%    |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 1         | 1.2%    |
| Intel Core i3-7020U CPU @ 2.30GHz           | 1         | 1.2%    |
| Intel Core i3-6006U CPU @ 2.00GHz           | 1         | 1.2%    |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1         | 1.2%    |
| Intel Core i3-3120M CPU @ 2.50GHz           | 1         | 1.2%    |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 1.2%    |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 1         | 1.2%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 1         | 1.2%    |
| Intel Core 2 Duo                            | 1         | 1.2%    |
| Intel Core 2 CPU T7200                      | 1         | 1.2%    |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.2%    |
| Intel Celeron M CPU                         | 1         | 1.2%    |
| Intel Celeron CPU 3215U @ 1.70GHz           | 1         | 1.2%    |
| Intel C1                                    | 1         | 1.2%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 25        | 30.12%  |
| Intel Core i7     | 22        | 26.51%  |
| Intel Core i3     | 5         | 6.02%   |
| Other             | 3         | 3.61%   |
| Intel Pentium     | 3         | 3.61%   |
| Intel Core 2 Duo  | 3         | 3.61%   |
| Intel Atom        | 3         | 3.61%   |
| AMD A6            | 3         | 3.61%   |
| Intel Celeron     | 2         | 2.41%   |
| AMD Ryzen 7       | 2         | 2.41%   |
| AMD A8            | 2         | 2.41%   |
| Intel Xeon        | 1         | 1.2%    |
| Intel Pentium III | 1         | 1.2%    |
| Intel Genuine     | 1         | 1.2%    |
| Intel Core m5     | 1         | 1.2%    |
| Intel Core i9     | 1         | 1.2%    |
| Intel Core 2      | 1         | 1.2%    |
| Intel Celeron M   | 1         | 1.2%    |
| AMD Ryzen 5       | 1         | 1.2%    |
| AMD E1            | 1         | 1.2%    |
| AMD A10           | 1         | 1.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 43        | 51.81%  |
| 4       | 25        | 30.12%  |
| Unknown | 7         | 8.43%   |
| 8       | 3         | 3.61%   |
| 1       | 3         | 3.61%   |
| 6       | 2         | 2.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 82        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 56        | 67.47%  |
| 1       | 18        | 21.69%  |
| Unknown | 9         | 10.84%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 14        | 16.87%  |
| Haswell       | 13        | 15.66%  |
| Skylake       | 10        | 12.05%  |
| IvyBridge     | 8         | 9.64%   |
| SandyBridge   | 6         | 7.23%   |
| Puma          | 4         | 4.82%   |
| Bonnell       | 4         | 4.82%   |
| Zen+          | 3         | 3.61%   |
| Penryn        | 3         | 3.61%   |
| Core          | 3         | 3.61%   |
| Broadwell     | 3         | 3.61%   |
| Westmere      | 2         | 2.41%   |
| Silvermont    | 2         | 2.41%   |
| P6            | 2         | 2.41%   |
| Steamroller   | 1         | 1.2%    |
| K10 Llano     | 1         | 1.2%    |
| Jaguar        | 1         | 1.2%    |
| Goldmont plus | 1         | 1.2%    |
| Excavator     | 1         | 1.2%    |
| CometLake     | 1         | 1.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 61        | 67.03%  |
| AMD              | 15        | 16.48%  |
| Nvidia           | 13        | 14.29%  |
| VIA Technologies | 1         | 1.1%    |
| S3 Graphics      | 1         | 1.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 8.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 7.37%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 7.37%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 6.32%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 4.21%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 3.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 3.16%   |
| Intel HD Graphics 620                                                                    | 3         | 3.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 3.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 3.16%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 3.16%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 2.11%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 2.11%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 2.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.11%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 2.11%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 1.05%   |
| S3 Graphics SuperSavage IX/C SDR                                                         | 1         | 1.05%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.05%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.05%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 1.05%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 1.05%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.05%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 1         | 1.05%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 1.05%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.05%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                                     | 1         | 1.05%   |
| Nvidia GF114M [GeForce GTX 580M]                                                         | 1         | 1.05%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 1.05%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 1.05%   |
| Nvidia G72M [GeForce Go 7400]                                                            | 1         | 1.05%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.05%   |
| Intel HD Graphics P530                                                                   | 1         | 1.05%   |
| Intel HD Graphics 630                                                                    | 1         | 1.05%   |
| Intel HD Graphics 6000                                                                   | 1         | 1.05%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.05%   |
| Intel HD Graphics 515                                                                    | 1         | 1.05%   |
| Intel HD Graphics                                                                        | 1         | 1.05%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.05%   |
| Intel Crystal Well Integrated Graphics Controller                                        | 1         | 1.05%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.05%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 1.05%   |
| AMD Temash [Radeon HD 8250/8280G]                                                        | 1         | 1.05%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 1.05%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 1.05%   |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                                        | 1         | 1.05%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 1         | 1.05%   |
| AMD Kaveri [Radeon R6 Graphics]                                                          | 1         | 1.05%   |
| AMD Baffin [Radeon Pro WX 4130/4150]                                                     | 1         | 1.05%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 47        | 56.63%  |
| 1 x AMD         | 13        | 15.66%  |
| 2 x Intel       | 7         | 8.43%   |
| 1 x Nvidia      | 6         | 7.23%   |
| Intel + Nvidia  | 6         | 7.23%   |
| 1 x VIA         | 1         | 1.2%    |
| 1 x S3 Graphics | 1         | 1.2%    |
| Intel + AMD     | 1         | 1.2%    |
| AMD + Nvidia    | 1         | 1.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 67        | 81.71%  |
| Unknown     | 12        | 14.63%  |
| Proprietary | 3         | 3.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 71        | 85.54%  |
| 0.01-0.5   | 5         | 6.02%   |
| 0.51-1.0   | 4         | 4.82%   |
| 1.01-2.0   | 3         | 3.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 11        | 15.94%  |
| AU Optronics            | 11        | 15.94%  |
| BOE                     | 10        | 14.49%  |
| Samsung Electronics     | 9         | 13.04%  |
| Chimei Innolux          | 5         | 7.25%   |
| Sharp                   | 3         | 4.35%   |
| Lenovo                  | 3         | 4.35%   |
| Chi Mei Optoelectronics | 3         | 4.35%   |
| Apple                   | 3         | 4.35%   |
| Panasonic               | 2         | 2.9%    |
| HannStar                | 2         | 2.9%    |
| LG Philips              | 1         | 1.45%   |
| Hewlett-Packard         | 1         | 1.45%   |
| Goldstar                | 1         | 1.45%   |
| CPT                     | 1         | 1.45%   |
| BenQ                    | 1         | 1.45%   |
| AOC                     | 1         | 1.45%   |
| Acer                    | 1         | 1.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch              | 2         | 2.86%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch               | 2         | 2.86%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                 | 2         | 2.86%   |
| BOE LCD Monitor BOE0671 1366x768 340x190mm 15.3-inch                      | 2         | 2.86%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch             | 2         | 2.86%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch                   | 1         | 1.43%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                   | 1         | 1.43%   |
| Sharp LCD Monitor SHP140E 2560x1440 290x170mm 13.2-inch                   | 1         | 1.43%   |
| Samsung Electronics LF24T450F SAM7094 1920x1080 530x300mm 24.0-inch       | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch     | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch      | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch      | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 220x130mm 10.1-inch      | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 290x160mm 13.0-inch     | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 310x170mm 13.9-inch      | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 290x160mm 13.0-inch     | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch      | 1         | 1.43%   |
| LG Philips LCD Monitor LPLA101 1440x900 370x230mm 17.2-inch               | 1         | 1.43%   |
| LG Display LCD Monitor LGD6301 1366x768 340x190mm 15.3-inch               | 1         | 1.43%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch              | 1         | 1.43%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch               | 1         | 1.43%   |
| LG Display LCD Monitor LGD0414 1920x1080 280x160mm 12.7-inch              | 1         | 1.43%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch              | 1         | 1.43%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch               | 1         | 1.43%   |
| LG Display LCD Monitor LGD034D 1366x768 340x190mm 15.3-inch               | 1         | 1.43%   |
| LG Display LCD Monitor LGD0303 1600x900 380x210mm 17.1-inch               | 1         | 1.43%   |
| LG Display LCD Monitor LGD01F7 1366x768 290x160mm 13.0-inch               | 1         | 1.43%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                   | 1         | 1.43%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch                   | 1         | 1.43%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                   | 1         | 1.43%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch                | 1         | 1.43%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 1         | 1.43%   |
| CPT LCD Monitor CPT04C4 1024x600 230x140mm 10.6-inch                      | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 380x210mm 17.1-inch           | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 340x190mm 15.3-inch           | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch          | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 310x170mm 13.9-inch           | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN1471 1366x768 310x170mm 13.9-inch           | 1         | 1.43%   |
| Chi Mei Optoelectronics LCD Monitor CMO1726 1920x1080 380x210mm 17.1-inch | 1         | 1.43%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 380x210mm 17.1-inch | 1         | 1.43%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 350x190mm 15.7-inch  | 1         | 1.43%   |
| BOE LCD Monitor BOE0812 1920x1080 340x190mm 15.3-inch                     | 1         | 1.43%   |
| BOE LCD Monitor BOE07E8 1366x768 310x170mm 13.9-inch                      | 1         | 1.43%   |
| BOE LCD Monitor BOE070D 1366x768 310x170mm 13.9-inch                      | 1         | 1.43%   |
| BOE LCD Monitor BOE06A4 1366x768 340x190mm 15.3-inch                      | 1         | 1.43%   |
| BOE LCD Monitor BOE069B 1600x900 380x210mm 17.1-inch                      | 1         | 1.43%   |
| BOE LCD Monitor BOE0691 1920x1080 280x160mm 12.7-inch                     | 1         | 1.43%   |
| BOE LCD Monitor BOE0690 1920x1080 340x190mm 15.3-inch                     | 1         | 1.43%   |
| BOE LCD Monitor BOE05F5 1366x768 280x160mm 12.7-inch                      | 1         | 1.43%   |
| BenQ FP71V+ BNQ76A1 1280x1024 340x270mm 17.1-inch                         | 1         | 1.43%   |
| AU Optronics LCD Monitor AUO8174 1280x800 330x210mm 15.4-inch             | 1         | 1.43%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 340x190mm 15.3-inch             | 1         | 1.43%   |
| AU Optronics LCD Monitor AUO305C 1366x768 260x140mm 11.6-inch             | 1         | 1.43%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch            | 1         | 1.43%   |
| AU Optronics LCD Monitor AUO233E 1600x900 310x170mm 13.9-inch             | 1         | 1.43%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch            | 1         | 1.43%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 340x190mm 15.3-inch            | 1         | 1.43%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 340x190mm 15.3-inch             | 1         | 1.43%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch             | 1         | 1.43%   |
| Apple LCD Monitor APP9CCB 1280x800 290x180mm 13.4-inch                    | 1         | 1.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 28        | 40.58%  |
| 1920x1080 (FHD)  | 18        | 26.09%  |
| 1600x900 (HD+)   | 5         | 7.25%   |
| 1024x600         | 4         | 5.8%    |
| 1440x900 (WXGA+) | 3         | 4.35%   |
| 1280x800 (WXGA)  | 3         | 4.35%   |
| 3840x2160 (4K)   | 2         | 2.9%    |
| 2880x1620        | 2         | 2.9%    |
| 3200x1800 (QHD+) | 1         | 1.45%   |
| 2880x1800        | 1         | 1.45%   |
| 2560x1440 (QHD)  | 1         | 1.45%   |
| 1280x1024 (SXGA) | 1         | 1.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 28        | 40%     |
| 13     | 16        | 22.86%  |
| 17     | 7         | 10%     |
| 12     | 6         | 8.57%   |
| 10     | 4         | 5.71%   |
| 24     | 3         | 4.29%   |
| 27     | 2         | 2.86%   |
| 11     | 2         | 2.86%   |
| 18     | 1         | 1.43%   |
| 14     | 1         | 1.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 38        | 54.29%  |
| 201-300     | 20        | 28.57%  |
| 351-400     | 6         | 8.57%   |
| 501-600     | 4         | 5.71%   |
| 601-700     | 1         | 1.43%   |
| 401-500     | 1         | 1.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 56        | 87.5%   |
| 16/10 | 7         | 10.94%  |
| 5/4   | 1         | 1.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 22        | 31.43%  |
| 81-90          | 12        | 17.14%  |
| 61-70          | 6         | 8.57%   |
| 101-110        | 6         | 8.57%   |
| 71-80          | 5         | 7.14%   |
| 121-130        | 5         | 7.14%   |
| 41-50          | 4         | 5.71%   |
| 201-250        | 3         | 4.29%   |
| 51-60          | 2         | 2.86%   |
| 301-350        | 2         | 2.86%   |
| 141-150        | 2         | 2.86%   |
| 131-140        | 1         | 1.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 31        | 44.93%  |
| 121-160       | 19        | 27.54%  |
| 161-240       | 9         | 13.04%  |
| 51-100        | 8         | 11.59%  |
| More than 240 | 2         | 2.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 64        | 76.19%  |
| 0     | 16        | 19.05%  |
| 2     | 3         | 3.57%   |
| 3     | 1         | 1.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 46        | 38.02%  |
| Realtek Semiconductor             | 32        | 26.45%  |
| Qualcomm Atheros                  | 22        | 18.18%  |
| Broadcom                          | 7         | 5.79%   |
| Ralink                            | 3         | 2.48%   |
| Marvell Technology Group          | 2         | 1.65%   |
| VIA Technologies                  | 1         | 0.83%   |
| TP-Link                           | 1         | 0.83%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.83%   |
| Sierra Wireless                   | 1         | 0.83%   |
| Qualcomm                          | 1         | 0.83%   |
| JMicron Technology                | 1         | 0.83%   |
| Fibocom                           | 1         | 0.83%   |
| Ericsson Business Mobile Networks | 1         | 0.83%   |
| Atheros                           | 1         | 0.83%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 11.52%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 7.27%   |
| Intel Wireless 7260                                               | 9         | 5.45%   |
| Intel Wireless 8260                                               | 6         | 3.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 3.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 2.42%   |
| Intel Wireless 3165                                               | 4         | 2.42%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 2.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 1.82%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.82%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.82%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 1.82%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3         | 1.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 1.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 1.21%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 1.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 1.21%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.21%   |
| Intel Wireless 7265                                               | 2         | 1.21%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.21%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.21%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 1.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.21%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.21%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.61%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.61%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.61%   |
| Sierra Wireless EM7455                                            | 1         | 0.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.61%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.61%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.61%   |
| Realtek Realtek Bluetooth 4.2 Adapter                             | 1         | 0.61%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 0.61%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.61%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.61%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.61%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.61%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 0.61%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.61%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.61%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.61%   |
| Intel Wireless-AC 9260                                            | 1         | 0.61%   |
| Intel WiMAX/WiFi Link 5150                                        | 1         | 0.61%   |
| Intel WiFi Link 5100                                              | 1         | 0.61%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 1         | 0.61%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 0.61%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.61%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.61%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 44        | 51.16%  |
| Qualcomm Atheros      | 18        | 20.93%  |
| Realtek Semiconductor | 12        | 13.95%  |
| Broadcom              | 6         | 6.98%   |
| Ralink                | 3         | 3.49%   |
| TP-Link               | 1         | 1.16%   |
| Sierra Wireless       | 1         | 1.16%   |
| Atheros               | 1         | 1.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                  | 9         | 10.11%  |
| Intel Wireless 8260                                                  | 6         | 6.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 5         | 5.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 4         | 4.49%   |
| Intel Wireless 3165                                                  | 4         | 4.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 3         | 3.37%   |
| Intel Wireless 8265 / 8275                                           | 3         | 3.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 3         | 3.37%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 3         | 3.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 2.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 2         | 2.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 2         | 2.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2         | 2.25%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 2         | 2.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 2         | 2.25%   |
| Intel Wireless 7265                                                  | 2         | 2.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 2.25%   |
| Intel Centrino Advanced-N 6200                                       | 2         | 2.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 2         | 2.25%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1         | 1.12%   |
| Sierra Wireless EM7455                                               | 1         | 1.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.12%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.12%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 1.12%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 1.12%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1         | 1.12%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                | 1         | 1.12%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter               | 1         | 1.12%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 1         | 1.12%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 1         | 1.12%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 1         | 1.12%   |
| Intel Wireless-AC 9260                                               | 1         | 1.12%   |
| Intel WiMAX/WiFi Link 5150                                           | 1         | 1.12%   |
| Intel WiFi Link 5100                                                 | 1         | 1.12%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection        | 1         | 1.12%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 1         | 1.12%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 1         | 1.12%   |
| Intel Centrino Wireless-N 6150                                       | 1         | 1.12%   |
| Intel Centrino Wireless-N 135                                        | 1         | 1.12%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                        | 1         | 1.12%   |
| Intel Centrino WiMAX 6150                                            | 1         | 1.12%   |
| Intel Centrino Ultimate-N 6300                                       | 1         | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 1.12%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 1         | 1.12%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 1         | 1.12%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller  | 1         | 1.12%   |
| Broadcom BCM43142 802.11b/g/n                                        | 1         | 1.12%   |
| Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.12%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 31        | 42.47%  |
| Intel                            | 26        | 35.62%  |
| Qualcomm Atheros                 | 6         | 8.22%   |
| Broadcom                         | 4         | 5.48%   |
| Marvell Technology Group         | 2         | 2.74%   |
| VIA Technologies                 | 1         | 1.37%   |
| Silicon Integrated Systems [SiS] | 1         | 1.37%   |
| Qualcomm                         | 1         | 1.37%   |
| JMicron Technology               | 1         | 1.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 25.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 16.22%  |
| Intel Ethernet Connection I217-LM                                 | 4         | 5.41%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 4.05%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 4.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4.05%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 4.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 2.7%    |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.7%    |
| Intel Ethernet Connection (6) I219-V                              | 2         | 2.7%    |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.7%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 1.35%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.35%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.35%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.35%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.35%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 1.35%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 1.35%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.35%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 1.35%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.35%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.35%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.35%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.35%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.35%   |
| Intel 82801CAM (ICH3) PRO/100 VE (LOM) Ethernet Controller        | 1         | 1.35%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.35%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.35%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 1.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 81        | 52.26%  |
| Ethernet | 72        | 46.45%  |
| Unknown  | 2         | 1.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 69        | 51.11%  |
| WiFi     | 64        | 47.41%  |
| Unknown  | 2         | 1.48%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 72        | 86.75%  |
| 1     | 11        | 13.25%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 77        | 92.77%  |
| Yes  | 6         | 7.23%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 45%     |
| Lite-On Technology              | 5         | 8.33%   |
| Realtek Semiconductor           | 4         | 6.67%   |
| Qualcomm Atheros Communications | 4         | 6.67%   |
| Broadcom                        | 4         | 6.67%   |
| Apple                           | 4         | 6.67%   |
| IMC Networks                    | 3         | 5%      |
| ASUSTek Computer                | 3         | 5%      |
| Foxconn / Hon Hai               | 2         | 3.33%   |
| Hewlett-Packard                 | 1         | 1.67%   |
| Dell                            | 1         | 1.67%   |
| Cambridge Silicon Radio         | 1         | 1.67%   |
| Alps Electric                   | 1         | 1.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 19        | 31.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3         | 5%      |
| Intel AX201 Bluetooth                                       | 3         | 5%      |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 3.33%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 3.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 3.33%   |
| ASUS BT-253 Bluetooth Adapter                               | 2         | 3.33%   |
| Apple Bluetooth Host Controller                             | 2         | 3.33%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 2         | 3.33%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 1.67%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 1.67%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.67%   |
| Realtek  Bluetooth 4.0 Adapter                              | 1         | 1.67%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 1         | 1.67%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.67%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device        | 1         | 1.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.67%   |
| Lite-On Bluetooth USB Module                                | 1         | 1.67%   |
| Lite-On Atheros Bluetooth                                   | 1         | 1.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.67%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 1.67%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 1.67%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.67%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 1.67%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 1.67%   |
| Dell DW375 Bluetooth Module                                 | 1         | 1.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 1.67%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 1         | 1.67%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.67%   |
| ASUS ASUS USB-BT500                                         | 1         | 1.67%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 1.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 69        | 75%     |
| AMD                              | 14        | 15.22%  |
| Nvidia                           | 5         | 5.43%   |
| VIA Technologies                 | 1         | 1.09%   |
| Silicon Integrated Systems [SiS] | 1         | 1.09%   |
| Realtek Semiconductor            | 1         | 1.09%   |
| Blue Microphones                 | 1         | 1.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 13        | 11.02%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 6.78%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 5.93%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 5.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 5.93%   |
| AMD FCH Azalia Controller                                                                         | 7         | 5.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 5.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 4.24%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 4.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 3.39%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 2.54%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 2.54%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.54%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.54%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 2.54%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 2.54%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.69%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.69%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.85%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.85%   |
| Realtek Semiconductor Realtek USB Audio                                                           | 1         | 0.85%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.85%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.85%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.85%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.85%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.85%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.85%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.85%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                                          | 1         | 0.85%   |
| Blue Microphones Yeti Stereo Microphone                                                           | 1         | 0.85%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.85%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.85%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 0.85%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.85%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 0.85%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 1         | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 31        | 31.63%  |
| SK Hynix            | 22        | 22.45%  |
| Micron Technology   | 10        | 10.2%   |
| Unknown             | 9         | 9.18%   |
| Kingston            | 5         | 5.1%    |
| Elpida              | 4         | 4.08%   |
| Crucial             | 4         | 4.08%   |
| Transcend           | 2         | 2.04%   |
| A-DATA Technology   | 2         | 2.04%   |
| Unknown             | 2         | 2.04%   |
| Unknown (ABCD)      | 1         | 1.02%   |
| Unknown (09D5)      | 1         | 1.02%   |
| Nanya Technology    | 1         | 1.02%   |
| Magnum Tech         | 1         | 1.02%   |
| G.Skill             | 1         | 1.02%   |
| Corsair             | 1         | 1.02%   |
| 48spaces            | 1         | 1.02%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s              | 6         | 5.61%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 4         | 3.74%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 2.8%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 3         | 2.8%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s               | 3         | 2.8%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 2.8%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 2         | 1.87%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.87%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.87%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.87%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                       | 2         | 1.87%   |
| Unknown                                                             | 2         | 1.87%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                           | 1         | 0.93%   |
| Unknown SODIMM 1024MB SODIMM DDR2 667MT/s                           | 1         | 0.93%   |
| Unknown RAM Module 512MB SODIMM SDRAM                               | 1         | 0.93%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                      | 1         | 0.93%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 1         | 0.93%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                              | 1         | 0.93%   |
| Unknown RAM Module 1GB SODIMM DRAM 533MT/s                          | 1         | 0.93%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 1         | 0.93%   |
| Unknown RAM Module 128MB SODIMM SDRAM                               | 1         | 0.93%   |
| Unknown RAM Module 1024MB SODIMM RAM                                | 1         | 0.93%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB SODIMM LPDDR4 2133MT/s | 1         | 0.93%   |
| Unknown (09D5) RAM Module 16GB SODIMM DDR4 2400MT/s                 | 1         | 0.93%   |
| Transcend RAM TS512MSK64V1N 4GB SODIMM 800MT/s                      | 1         | 0.93%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR 667MT/s                    | 1         | 0.93%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 1         | 0.93%   |
| SK Hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s                | 1         | 0.93%   |
| SK Hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s                | 1         | 0.93%   |
| SK Hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.93%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.93%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1333MT/s              | 1         | 0.93%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.93%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 1         | 0.93%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s          | 1         | 0.93%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 1         | 0.93%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 0.93%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.93%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s              | 1         | 0.93%   |
| SK Hynix RAM H9CCNNNBJTMLAR-NUD 4096MB SODIMM LPDDR3 1867MT/s       | 1         | 0.93%   |
| SK Hynix RAM H5TC8G63AMR-PBA 4096MB 1600MT/s                        | 1         | 0.93%   |
| Samsung RAM Module 16GB SODIMM DDR4 2133MT/s                        | 1         | 0.93%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s               | 1         | 0.93%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s               | 1         | 0.93%   |
| Samsung RAM M471B5273DH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 0.93%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.93%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 0.93%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.93%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.93%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.93%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.93%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.93%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 0.93%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 1         | 0.93%   |
| Samsung RAM M08GD04P1600C1 8192MB SODIMM DDR3 1333MT/s              | 1         | 0.93%   |
| Samsung RAM K4E6E304EE-EGCF 4GB SODIMM LPDDR3 1867MT/s              | 1         | 0.93%   |
| Samsung RAM K4E6E304EE-EGCF 4GB Chip LPDDR3 1867MT/s                | 1         | 0.93%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                | 1         | 0.93%   |
| Micron RAM Module 8192MB SODIMM DDR3 1600MT/s                       | 1         | 0.93%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s               | 1         | 0.93%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 42        | 50.6%   |
| DDR4    | 23        | 27.71%  |
| DDR2    | 6         | 7.23%   |
| SDRAM   | 3         | 3.61%   |
| LPDDR3  | 3         | 3.61%   |
| Unknown | 2         | 2.41%   |
| RAM     | 1         | 1.2%    |
| LPDDR4  | 1         | 1.2%    |
| DRAM    | 1         | 1.2%    |
| DDR     | 1         | 1.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SODIMM  | 79        | 95.18%  |
| Chip    | 2         | 2.41%   |
| Unknown | 2         | 2.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 42        | 43.75%  |
| 8192  | 26        | 27.08%  |
| 2048  | 14        | 14.58%  |
| 16384 | 7         | 7.29%   |
| 1024  | 4         | 4.17%   |
| 32768 | 1         | 1.04%   |
| 512   | 1         | 1.04%   |
| 128   | 1         | 1.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 32        | 35.96%  |
| 2667    | 10        | 11.24%  |
| 2400    | 10        | 11.24%  |
| 2133    | 6         | 6.74%   |
| 1334    | 6         | 6.74%   |
| 1333    | 5         | 5.62%   |
| 667     | 5         | 5.62%   |
| Unknown | 5         | 5.62%   |
| 3200    | 3         | 3.37%   |
| 1867    | 2         | 2.25%   |
| 800     | 2         | 2.25%   |
| 1866    | 1         | 1.12%   |
| 1067    | 1         | 1.12%   |
| 533     | 1         | 1.12%   |

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
| Chicony Electronics                    | 15        | 23.81%  |
| Acer                                   | 8         | 12.7%   |
| Sunplus Innovation Technology          | 7         | 11.11%  |
| Realtek Semiconductor                  | 7         | 11.11%  |
| Suyin                                  | 5         | 7.94%   |
| Silicon Motion                         | 3         | 4.76%   |
| Microdia                               | 3         | 4.76%   |
| IMC Networks                           | 3         | 4.76%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.76%   |
| Quanta                                 | 2         | 3.17%   |
| Lite-On Technology                     | 2         | 3.17%   |
| Logitech                               | 1         | 1.59%   |
| Intel                                  | 1         | 1.59%   |
| Genesys Logic                          | 1         | 1.59%   |
| Apple                                  | 1         | 1.59%   |
| Alcor Micro                            | 1         | 1.59%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 6         | 9.52%   |
| Sunplus Integrated_Webcam_HD                                   | 4         | 6.35%   |
| Acer Integrated Camera                                         | 4         | 6.35%   |
| Suyin Acer Crystal Eye webcam                                  | 2         | 3.17%   |
| Realtek Realtek USB2.0 PC Camera                               | 2         | 3.17%   |
| Chicony HD WebCam                                              | 2         | 3.17%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam            | 2         | 3.17%   |
| Suyin Laptop_Integrated_Webcam_3M                              | 1         | 1.59%   |
| Suyin HD WebCam                                                | 1         | 1.59%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 1         | 1.59%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 1.59%   |
| Sunplus Integrated Webcam                                      | 1         | 1.59%   |
| Sunplus Asus Webcam                                            | 1         | 1.59%   |
| Silicon Motion WebCam SCX Series                               | 1         | 1.59%   |
| Silicon Motion Realtek USB2.0 PC Camera                        | 1         | 1.59%   |
| Silicon Motion 300k Pixel Camera                               | 1         | 1.59%   |
| Realtek USB2.0 VGA UVC WebCam                                  | 1         | 1.59%   |
| Realtek USB Camera                                             | 1         | 1.59%   |
| Realtek Lenovo EasyCamera                                      | 1         | 1.59%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 1.59%   |
| Realtek HD Webcam - Realtek                                    | 1         | 1.59%   |
| Quanta Realtek DMFT - RGB                                      | 1         | 1.59%   |
| Quanta Front camera                                            | 1         | 1.59%   |
| Microdia Sonix USB 2.0 Camera                                  | 1         | 1.59%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 1.59%   |
| Microdia Integrated Webcam                                     | 1         | 1.59%   |
| Logitech HD Pro Webcam C920                                    | 1         | 1.59%   |
| Lite-On Integrated Camera                                      | 1         | 1.59%   |
| Lite-On HP Universal Camera                                    | 1         | 1.59%   |
| Intel WiMAX Connection 2400m                                   | 1         | 1.59%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 1         | 1.59%   |
| IMC Networks USB2.0 UVC HD Webcam                              | 1         | 1.59%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 1.59%   |
| Genesys Logic Camera                                           | 1         | 1.59%   |
| Chicony Webcam                                                 | 1         | 1.59%   |
| Chicony USB2.0 HD UVC WebCam                                   | 1         | 1.59%   |
| Chicony Thinkpad T430 camera                                   | 1         | 1.59%   |
| Chicony Lenovo EasyCamera                                      | 1         | 1.59%   |
| Chicony Integrated Camera [ThinkPad]                           | 1         | 1.59%   |
| Chicony HP TrueVision HD Camera                                | 1         | 1.59%   |
| Chicony FJ Camera                                              | 1         | 1.59%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.59%   |
| Apple FaceTime HD Camera                                       | 1         | 1.59%   |
| Alcor Micro HP WebCam-101                                      | 1         | 1.59%   |
| Acer USB2.0 Camera                                             | 1         | 1.59%   |
| Acer NEC HD WebCam                                             | 1         | 1.59%   |
| Acer Lenovo EasyCamera                                         | 1         | 1.59%   |
| Acer EasyCamera                                                | 1         | 1.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 8         | 66.67%  |
| Synaptics        | 2         | 16.67%  |
| Upek             | 1         | 8.33%   |
| Broadcom         | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 2         | 16.67%  |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 16.67%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 8.33%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 8.33%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 8.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 8.33%   |
| Unknown                                                                      | 1         | 8.33%   |

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
| 1     | 27        | 32.14%  |
| 2     | 23        | 27.38%  |
| 0     | 14        | 16.67%  |
| 3     | 13        | 15.48%  |
| 4     | 4         | 4.76%   |
| 7     | 1         | 1.19%   |
| 6     | 1         | 1.19%   |
| 5     | 1         | 1.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 56        | 42.75%  |
| Net/wireless             | 22        | 16.79%  |
| Card reader              | 16        | 12.21%  |
| Bluetooth                | 16        | 12.21%  |
| Fingerprint reader       | 12        | 9.16%   |
| Firewire controller      | 6         | 4.58%   |
| Storage/raid             | 1         | 0.76%   |
| Sound                    | 1         | 0.76%   |
| Network                  | 1         | 0.76%   |
