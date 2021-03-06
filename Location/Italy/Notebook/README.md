BSD in Italy - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for BSD in Italy.

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

Total: 71

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Acer          | AOD260                      | [08dc464d1b](https://bsd-hardware.info/?probe=08dc464d1b) | Jun 30, 2022 |
| Lenovo        | ThinkPad L530 24812TG       | [5b66684c4a](https://bsd-hardware.info/?probe=5b66684c4a) | Jun 05, 2022 |
| Lenovo        | ThinkPad X250 20CMS0FA00    | [5afeac632d](https://bsd-hardware.info/?probe=5afeac632d) | May 28, 2022 |
| ASUSTek       | F50SL                       | [e26b522868](https://bsd-hardware.info/?probe=e26b522868) | May 22, 2022 |
| Acer          | Aspire E1-522               | [23396b461f](https://bsd-hardware.info/?probe=23396b461f) | May 18, 2022 |
| Acer          | Aspire E1-522               | [55cda59c51](https://bsd-hardware.info/?probe=55cda59c51) | May 17, 2022 |
| ASUSTek       | K52F                        | [6e86ce2a12](https://bsd-hardware.info/?probe=6e86ce2a12) | May 15, 2022 |
| ASUSTek       | K52F                        | [4c12c55177](https://bsd-hardware.info/?probe=4c12c55177) | May 15, 2022 |
| Dell          | Inspiron 15-3552            | [5e781a451d](https://bsd-hardware.info/?probe=5e781a451d) | May 12, 2022 |
| Deciso        | OPNsense Appliance          | [8a8db12cf2](https://bsd-hardware.info/?probe=8a8db12cf2) | May 02, 2022 |
| Lenovo        | ThinkPad T420 4236BD5       | [867ed989e2](https://bsd-hardware.info/?probe=867ed989e2) | Apr 27, 2022 |
| MSI           | GF65 Thin 10SER             | [cedf98c955](https://bsd-hardware.info/?probe=cedf98c955) | Apr 26, 2022 |
| ASUSTek       | X555LJ                      | [6bf51cc915](https://bsd-hardware.info/?probe=6bf51cc915) | Mar 28, 2022 |
| Acer          | V5-131                      | [2d5bfae3b4](https://bsd-hardware.info/?probe=2d5bfae3b4) | Feb 15, 2022 |
| HP            | EliteBook 6930p             | [d8fb34de12](https://bsd-hardware.info/?probe=d8fb34de12) | Feb 04, 2022 |
| HP            | Mini 210-1000               | [8a8bfdaee1](https://bsd-hardware.info/?probe=8a8bfdaee1) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cf360a6098](https://bsd-hardware.info/?probe=cf360a6098) | Jan 16, 2022 |
| Acer          | Extensa 5635Z               | [d76873c5dd](https://bsd-hardware.info/?probe=d76873c5dd) | Jan 16, 2022 |
| TUXEDO        | N14xWU                      | [4ac0707c49](https://bsd-hardware.info/?probe=4ac0707c49) | Jan 06, 2022 |
| Unknown       | Unknown                     | [341401bb02](https://bsd-hardware.info/?probe=341401bb02) | Jan 04, 2022 |
| Unknown       | Unknown                     | [46e5f9b021](https://bsd-hardware.info/?probe=46e5f9b021) | Dec 29, 2021 |
| Packard Be... | EasyNote_MX61-B-038         | [235d60060d](https://bsd-hardware.info/?probe=235d60060d) | Dec 12, 2021 |
| Acer          | Aspire 5749Z                | [60a25af38c](https://bsd-hardware.info/?probe=60a25af38c) | Dec 09, 2021 |
| ASUSTek       | 1000                        | [da8689c840](https://bsd-hardware.info/?probe=da8689c840) | Dec 08, 2021 |
| Toshiba       | Satellite C855-1U4          | [4107fc9eee](https://bsd-hardware.info/?probe=4107fc9eee) | Nov 14, 2021 |
| Toshiba       | PORTEGE M780                | [2ac9bea1e6](https://bsd-hardware.info/?probe=2ac9bea1e6) | Nov 13, 2021 |
| HP            | ProBook 470 G4              | [5f026ff3a2](https://bsd-hardware.info/?probe=5f026ff3a2) | Oct 17, 2021 |
| HP            | ProBook 470 G4              | [40c180238f](https://bsd-hardware.info/?probe=40c180238f) | Oct 17, 2021 |
| HP            | ProBook 470 G4              | [a9c135bf27](https://bsd-hardware.info/?probe=a9c135bf27) | Oct 10, 2021 |
| ASUSTek       | X555LJ                      | [81dd2ba2f0](https://bsd-hardware.info/?probe=81dd2ba2f0) | Oct 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0b73df29bf](https://bsd-hardware.info/?probe=0b73df29bf) | Sep 15, 2021 |
| Lenovo        | G505 20240                  | [16e6ec4054](https://bsd-hardware.info/?probe=16e6ec4054) | Aug 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [9c9d4cc782](https://bsd-hardware.info/?probe=9c9d4cc782) | Jul 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3d5e512e18](https://bsd-hardware.info/?probe=3d5e512e18) | Jul 18, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [31d42f4469](https://bsd-hardware.info/?probe=31d42f4469) | Jul 05, 2021 |
| Lenovo        | B590 62743PG                | [2400297995](https://bsd-hardware.info/?probe=2400297995) | Jul 03, 2021 |
| HP            | Laptop 15-da0xxx            | [cb09a1b771](https://bsd-hardware.info/?probe=cb09a1b771) | Apr 08, 2021 |
| Lenovo        | ThinkPad L530 24812TG       | [520982317e](https://bsd-hardware.info/?probe=520982317e) | Mar 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S82N00    | [aa3deadedd](https://bsd-hardware.info/?probe=aa3deadedd) | Mar 19, 2021 |
| HP            | Laptop 15-da0xxx            | [a7a25be087](https://bsd-hardware.info/?probe=a7a25be087) | Mar 16, 2021 |
| HP            | Laptop 15-da0xxx            | [bf572bc102](https://bsd-hardware.info/?probe=bf572bc102) | Mar 06, 2021 |
| ASUSTek       | G1S                         | [593c12aa06](https://bsd-hardware.info/?probe=593c12aa06) | Feb 28, 2021 |
| Acer          | Extensa 5635Z               | [837c6f28b4](https://bsd-hardware.info/?probe=837c6f28b4) | Feb 19, 2021 |
| eMachines     | eME732ZG                    | [d0c0433452](https://bsd-hardware.info/?probe=d0c0433452) | Feb 16, 2021 |
| ASUSTek       | X555LD                      | [74d43ccd10](https://bsd-hardware.info/?probe=74d43ccd10) | Feb 16, 2021 |
| HP            | ProBook 470 G4              | [f808e6bb4a](https://bsd-hardware.info/?probe=f808e6bb4a) | Feb 13, 2021 |
| eMachines     | eME732ZG                    | [c51678397d](https://bsd-hardware.info/?probe=c51678397d) | Feb 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [37e4e7c85c](https://bsd-hardware.info/?probe=37e4e7c85c) | Feb 12, 2021 |
| HP            | Laptop 15-da0xxx            | [d6bc2b2c1d](https://bsd-hardware.info/?probe=d6bc2b2c1d) | Feb 08, 2021 |
| ASUSTek       | X502CA                      | [5e15d06a9b](https://bsd-hardware.info/?probe=5e15d06a9b) | Feb 06, 2021 |
| ASUSTek       | X502CA                      | [1a2df26f19](https://bsd-hardware.info/?probe=1a2df26f19) | Feb 06, 2021 |
| HP            | Laptop 15-da0xxx            | [869d894f4f](https://bsd-hardware.info/?probe=869d894f4f) | Jan 30, 2021 |
| HP            | Laptop 15-da0xxx            | [3e37c56f14](https://bsd-hardware.info/?probe=3e37c56f14) | Jan 23, 2021 |
| Apple         | MacBook4,1                  | [9eca3b0463](https://bsd-hardware.info/?probe=9eca3b0463) | Jan 22, 2021 |
| Apple         | MacBook4,1                  | [539b95f535](https://bsd-hardware.info/?probe=539b95f535) | Jan 20, 2021 |
| HP            | ProBook 470 G4              | [bc4bca1e5e](https://bsd-hardware.info/?probe=bc4bca1e5e) | Jan 18, 2021 |
| HP            | ProBook 470 G4              | [e39a46cadf](https://bsd-hardware.info/?probe=e39a46cadf) | Jan 17, 2021 |
| HP            | ProBook 470 G4              | [55c762d22e](https://bsd-hardware.info/?probe=55c762d22e) | Jan 17, 2021 |
| HP            | ProBook 470 G4              | [c4eecdac67](https://bsd-hardware.info/?probe=c4eecdac67) | Jan 14, 2021 |
| IBM           | ThinkPad R51 2887AVG        | [289177c624](https://bsd-hardware.info/?probe=289177c624) | Jan 02, 2021 |
| IBM           | ThinkPad R51 2887AVG        | [88d4fc2693](https://bsd-hardware.info/?probe=88d4fc2693) | Dec 30, 2020 |
| Lenovo        | ThinkPad T495 20NJS0KP00    | [7a706e46de](https://bsd-hardware.info/?probe=7a706e46de) | Oct 31, 2020 |
| Lenovo        | ThinkPad T430 23501B3       | [53233cc736](https://bsd-hardware.info/?probe=53233cc736) | Oct 31, 2020 |
| Dell          | Precision 3510              | [85a55ab7c3](https://bsd-hardware.info/?probe=85a55ab7c3) | Oct 22, 2020 |
| HP            | Laptop 15-da0xxx            | [7faf1699d6](https://bsd-hardware.info/?probe=7faf1699d6) | Oct 04, 2020 |
| Apple         | MacBookAir7,2               | [36d0d99aa6](https://bsd-hardware.info/?probe=36d0d99aa6) | Oct 04, 2020 |
| Lenovo        | G50-45 80E3                 | [1d227a9cd2](https://bsd-hardware.info/?probe=1d227a9cd2) | Oct 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2f119a81b4](https://bsd-hardware.info/?probe=2f119a81b4) | Aug 13, 2020 |
| Lenovo        | ThinkPad T450 20BUS06B00    | [f437a3b5ab](https://bsd-hardware.info/?probe=f437a3b5ab) | Jul 06, 2020 |
| Lenovo        | ThinkPad T440 20B7S1C600    | [a4a62cb85e](https://bsd-hardware.info/?probe=a4a62cb85e) | May 24, 2020 |
| Lenovo        | ThinkPad X240 20AMS0J01N    | [4df07718d1](https://bsd-hardware.info/?probe=4df07718d1) | May 23, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 9         | 17.31%  |
| helloSystem 0.5.0    | 5         | 9.62%   |
| helloSystem 0.4.0    | 5         | 9.62%   |
| helloSystem 0.6.0    | 3         | 5.77%   |
| NomadBSD 1.3.2       | 2         | 3.85%   |
| helloSystem 0.3.0    | 2         | 3.85%   |
| GhostBSD 21.08.27    | 2         | 3.85%   |
| GhostBSD 20.04.02    | 2         | 3.85%   |
| OPNsense 22.1.9      | 1         | 1.92%   |
| OPNsense 22.1.6      | 1         | 1.92%   |
| OPNsense 21.7.7      | 1         | 1.92%   |
| OpenBSD 7.1          | 1         | 1.92%   |
| OpenBSD 6.8          | 1         | 1.92%   |
| OpenBSD 6.7          | 1         | 1.92%   |
| NomadBSD 5806f915    | 1         | 1.92%   |
| NomadBSD 1.4         | 1         | 1.92%   |
| NomadBSD 1.3.1       | 1         | 1.92%   |
| NetBSD 9.2_STABLE    | 1         | 1.92%   |
| NetBSD 9.2           | 1         | 1.92%   |
| NetBSD 9.1           | 1         | 1.92%   |
| NetBSD 9.0           | 1         | 1.92%   |
| FreeBSD 14.0-CURRENT | 1         | 1.92%   |
| FreeBSD 13.1         | 1         | 1.92%   |
| FreeBSD 13.0-p4      | 1         | 1.92%   |
| FreeBSD 13.0-CURRENT | 1         | 1.92%   |
| FreeBSD 13.0         | 1         | 1.92%   |
| FreeBSD 12.2-p4      | 1         | 1.92%   |
| FreeBSD 12.2-p2      | 1         | 1.92%   |
| FreeBSD 12.1-p10     | 1         | 1.92%   |
| FreeBSD 12.0-p13     | 1         | 1.92%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 22        | 44.9%   |
| FreeBSD     | 9         | 18.37%  |
| NomadBSD    | 5         | 10.2%   |
| GhostBSD    | 4         | 8.16%   |
| OPNsense    | 3         | 6.12%   |
| OpenBSD     | 3         | 6.12%   |
| NetBSD      | 3         | 6.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 46        | 95.83%  |
| i386  | 2         | 4.17%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 22        | 44%     |
| Openbox      | 5         | 10%     |
| Console      | 5         | 10%     |
| i3           | 3         | 6%      |
| Cinnamon     | 3         | 6%      |
| XFCE         | 2         | 4%      |
| KDE5         | 2         | 4%      |
| fvwm         | 2         | 4%      |
| ctwm         | 2         | 4%      |
| TWM          | 1         | 2%      |
| MATE         | 1         | 2%      |
| LXQt         | 1         | 2%      |
| Fluxbox      | 1         | 2%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 45        | 93.75%  |
| Console | 3         | 6.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 29        | 60.42%  |
| Console | 12        | 25%     |
| LightDM | 4         | 8.33%   |
| SDDM    | 2         | 4.17%   |
| XDM     | 1         | 2.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Notebooks | Percent |
|------------------|-----------|---------|
| en_US            | 29        | 59.18%  |
| it_IT            | 8         | 16.33%  |
| Unknown          | 6         | 12.24%  |
| C                | 2         | 4.08%   |
| ru_RU            | 1         | 2.04%   |
| it_IT.ISO8859-15 | 1         | 2.04%   |
| it_IT.ISO8859-1  | 1         | 2.04%   |
| en_GB            | 1         | 2.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 40        | 83.33%  |
| BIOS | 8         | 16.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 28        | 57.14%  |
| Ufs    | 14        | 28.57%  |
| Cd9660 | 4         | 8.16%   |
| Ffs    | 3         | 6.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 42        | 87.5%   |
| MBR     | 4         | 8.33%   |
| Unknown | 2         | 4.17%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 13        | 27.08%  |
| ASUSTek Computer    | 10        | 20.83%  |
| Hewlett-Packard     | 5         | 10.42%  |
| Acer                | 5         | 10.42%  |
| Apple               | 3         | 6.25%   |
| Toshiba             | 2         | 4.17%   |
| Dell                | 2         | 4.17%   |
| TUXEDO              | 1         | 2.08%   |
| Samsung Electronics | 1         | 2.08%   |
| Packard Bell        | 1         | 2.08%   |
| MSI                 | 1         | 2.08%   |
| IBM                 | 1         | 2.08%   |
| eMachines           | 1         | 2.08%   |
| Deciso              | 1         | 2.08%   |
| Unknown             | 1         | 2.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| HP Laptop 15-da0xxx                      | 2         | 4.17%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA   | 2         | 4.17%   |
| Apple MacBook4,1                         | 2         | 4.17%   |
| TUXEDO N14xWU                            | 1         | 2.08%   |
| Toshiba Satellite C855-1U4               | 1         | 2.08%   |
| Toshiba PORTEGE M780                     | 1         | 2.08%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV | 1         | 2.08%   |
| Packard Bell EasyNote_MX61-B-038         | 1         | 2.08%   |
| MSI GF65 Thin 10SER                      | 1         | 2.08%   |
| Lenovo ThinkPad X260 20F5S82N00          | 1         | 2.08%   |
| Lenovo ThinkPad X250 20CMS0FA00          | 1         | 2.08%   |
| Lenovo ThinkPad X240 20AMS0J01N          | 1         | 2.08%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS6PC00 | 1         | 2.08%   |
| Lenovo ThinkPad T495 20NJS0KP00          | 1         | 2.08%   |
| Lenovo ThinkPad T450 20BUS06B00          | 1         | 2.08%   |
| Lenovo ThinkPad T440 20B7S1C600          | 1         | 2.08%   |
| Lenovo ThinkPad T430 23501B3             | 1         | 2.08%   |
| Lenovo ThinkPad T420 4236BD5             | 1         | 2.08%   |
| Lenovo ThinkPad L530 24812TG             | 1         | 2.08%   |
| Lenovo G505 20240                        | 1         | 2.08%   |
| Lenovo G50-45 80E3                       | 1         | 2.08%   |
| Lenovo B590 62743PG                      | 1         | 2.08%   |
| IBM ThinkPad R51 2887AVG                 | 1         | 2.08%   |
| HP ProBook 470 G4                        | 1         | 2.08%   |
| HP Mini 210-1000                         | 1         | 2.08%   |
| HP EliteBook 6930p                       | 1         | 2.08%   |
| eMachines eME732ZG                       | 1         | 2.08%   |
| Dell Precision 3510                      | 1         | 2.08%   |
| Dell Inspiron 15-3552                    | 1         | 2.08%   |
| Deciso OPNsense Appliance                | 1         | 2.08%   |
| ASUS X555LJ                              | 1         | 2.08%   |
| ASUS X555LD                              | 1         | 2.08%   |
| ASUS X502CA                              | 1         | 2.08%   |
| ASUS VivoBook_ASUSLaptop X515UA_M515UA   | 1         | 2.08%   |
| ASUS K52F                                | 1         | 2.08%   |
| ASUS G1S                                 | 1         | 2.08%   |
| ASUS F50SL                               | 1         | 2.08%   |
| ASUS 1000                                | 1         | 2.08%   |
| Apple MacBookAir7,2                      | 1         | 2.08%   |
| Acer V5-131                              | 1         | 2.08%   |
| Acer Extensa 5635Z                       | 1         | 2.08%   |
| Acer Aspire E1-522                       | 1         | 2.08%   |
| Acer Aspire 5749Z                        | 1         | 2.08%   |
| Acer AOD260                              | 1         | 2.08%   |
| Unknown                                  | 1         | 2.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 10        | 20.83%  |
| ASUS VivoBook         | 3         | 6.25%   |
| HP Laptop             | 2         | 4.17%   |
| Apple MacBook4        | 2         | 4.17%   |
| Acer Aspire           | 2         | 4.17%   |
| TUXEDO N14xWU         | 1         | 2.08%   |
| Toshiba Satellite     | 1         | 2.08%   |
| Toshiba PORTEGE       | 1         | 2.08%   |
| Samsung 3570R         | 1         | 2.08%   |
| Packard Bell EasyNote | 1         | 2.08%   |
| MSI GF65              | 1         | 2.08%   |
| Lenovo G505           | 1         | 2.08%   |
| Lenovo G50-45         | 1         | 2.08%   |
| Lenovo B590           | 1         | 2.08%   |
| IBM ThinkPad          | 1         | 2.08%   |
| HP ProBook            | 1         | 2.08%   |
| HP Mini               | 1         | 2.08%   |
| HP EliteBook          | 1         | 2.08%   |
| eMachines eME732ZG    | 1         | 2.08%   |
| Dell Precision        | 1         | 2.08%   |
| Dell Inspiron         | 1         | 2.08%   |
| Deciso OPNsense       | 1         | 2.08%   |
| ASUS X555LJ           | 1         | 2.08%   |
| ASUS X555LD           | 1         | 2.08%   |
| ASUS X502CA           | 1         | 2.08%   |
| ASUS K52F             | 1         | 2.08%   |
| ASUS G1S              | 1         | 2.08%   |
| ASUS F50SL            | 1         | 2.08%   |
| ASUS 1000             | 1         | 2.08%   |
| Apple MacBookAir7     | 1         | 2.08%   |
| Acer V5-131           | 1         | 2.08%   |
| Acer Extensa          | 1         | 2.08%   |
| Acer AOD260           | 1         | 2.08%   |
| Unknown               | 1         | 2.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 8         | 16.67%  |
| 2019 | 7         | 14.58%  |
| 2011 | 5         | 10.42%  |
| 2014 | 4         | 8.33%   |
| 2020 | 3         | 6.25%   |
| 2016 | 3         | 6.25%   |
| 2010 | 3         | 6.25%   |
| 2008 | 3         | 6.25%   |
| 2021 | 2         | 4.17%   |
| 2015 | 2         | 4.17%   |
| 2009 | 2         | 4.17%   |
| 2007 | 2         | 4.17%   |
| 2022 | 1         | 2.08%   |
| 2018 | 1         | 2.08%   |
| 2012 | 1         | 2.08%   |
| 2006 | 1         | 2.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 48        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 48        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 18        | 36.73%  |
| 8.01-16.0  | 18        | 36.73%  |
| 2.01-3.0   | 4         | 8.16%   |
| 16.01-24.0 | 4         | 8.16%   |
| 32.01-64.0 | 2         | 4.08%   |
| 3.01-4.0   | 1         | 2.04%   |
| 24.01-32.0 | 1         | 2.04%   |
| 0.01-0.5   | 1         | 2.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 31        | 63.27%  |
| 0.51-1.0  | 8         | 16.33%  |
| 2.01-3.0  | 3         | 6.12%   |
| Unknown   | 3         | 6.12%   |
| 4.01-8.0  | 2         | 4.08%   |
| 1.01-2.0  | 1         | 2.04%   |
| 8.01-16.0 | 1         | 2.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 35        | 71.43%  |
| 2      | 12        | 24.49%  |
| 0      | 2         | 4.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 63.27%  |
| Yes       | 18        | 36.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 89.58%  |
| No        | 5         | 10.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 93.75%  |
| No        | 3         | 6.25%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 59.18%  |
| No        | 20        | 40.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Italy   | 48        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Rome                     | 9         | 16.36%  |
| Milan                    | 5         | 9.09%   |
| Turin                    | 3         | 5.45%   |
| Bologna                  | 3         | 5.45%   |
| Trieste                  | 2         | 3.64%   |
| Monterotondo             | 2         | 3.64%   |
| Brescia                  | 2         | 3.64%   |
| Vigonovo                 | 1         | 1.82%   |
| Udine                    | 1         | 1.82%   |
| Solarino                 | 1         | 1.82%   |
| Saronno                  | 1         | 1.82%   |
| Roncade                  | 1         | 1.82%   |
| Rho                      | 1         | 1.82%   |
| Resana                   | 1         | 1.82%   |
| Piovene Rocchette        | 1         | 1.82%   |
| Passignano sul Trasimeno | 1         | 1.82%   |
| Padova                   | 1         | 1.82%   |
| Nughedu San Nicolo       | 1         | 1.82%   |
| Massa Lombarda           | 1         | 1.82%   |
| Malnate                  | 1         | 1.82%   |
| Macerata                 | 1         | 1.82%   |
| Lurago Marinone          | 1         | 1.82%   |
| Lissone                  | 1         | 1.82%   |
| Genzano di Roma          | 1         | 1.82%   |
| Galliera Veneta          | 1         | 1.82%   |
| Gallarate                | 1         | 1.82%   |
| Fiumicino                | 1         | 1.82%   |
| Farneto                  | 1         | 1.82%   |
| Concesio                 | 1         | 1.82%   |
| Cogolo                   | 1         | 1.82%   |
| Cardito                  | 1         | 1.82%   |
| Brugherio                | 1         | 1.82%   |
| Bergamo                  | 1         | 1.82%   |
| Arezzo                   | 1         | 1.82%   |
| Albano Sant'Alessandro   | 1         | 1.82%   |
| Adelfia                  | 1         | 1.82%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 16     | 16.36%  |
| WDC                 | 6         | 7      | 10.91%  |
| Toshiba             | 5         | 5      | 9.09%   |
| Seagate             | 5         | 9      | 9.09%   |
| Crucial             | 5         | 7      | 9.09%   |
| Kingston            | 4         | 5      | 7.27%   |
| SanDisk             | 3         | 3      | 5.45%   |
| Hitachi             | 3         | 4      | 5.45%   |
| Leven               | 2         | 2      | 3.64%   |
| KingSpec            | 2         | 2      | 3.64%   |
| Union Memory        | 1         | 1      | 1.82%   |
| Transcend           | 1         | 1      | 1.82%   |
| Micron Technology   | 1         | 1      | 1.82%   |
| KingDian            | 1         | 1      | 1.82%   |
| Intenso             | 1         | 1      | 1.82%   |
| Intel               | 1         | 1      | 1.82%   |
| HGST                | 1         | 1      | 1.82%   |
| Fujitsu             | 1         | 1      | 1.82%   |
| FORESEE             | 1         | 2      | 1.82%   |
| ASUSTek Computer    | 1         | 2      | 1.82%   |
| Apple               | 1         | 1      | 1.82%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| WDC WDS240G2G0A-00JH30 240GB                    | 2         | 3.45%   |
| Samsung SSD 860 EVO 250GB                       | 2         | 3.45%   |
| Samsung SSD 850 EVO 500GB                       | 2         | 3.45%   |
| KingSpec Q-720 720GB                            | 2         | 3.45%   |
| WDC WDS120G2G0A-00JH30 120GB                    | 1         | 1.72%   |
| WDC WD5000BPKT-00PK4T0 500GB                    | 1         | 1.72%   |
| WDC WD3200BEKX-60B7WT0 320GB                    | 1         | 1.72%   |
| WDC WD2500LPCX-24C6HT0 250GB                    | 1         | 1.72%   |
| WDC WD2500BEVS-22UST0 250GB                     | 1         | 1.72%   |
| Union Memory UMIS LENSE40512GMSP34MESTB3A 512GB | 1         | 1.72%   |
| Transcend TS256GMTE652T2 256GB                  | 1         | 1.72%   |
| Toshiba TR200 240GB                             | 1         | 1.72%   |
| Toshiba MQ04ABF100 1TB                          | 1         | 1.72%   |
| Toshiba MQ01ABF050 500GB                        | 1         | 1.72%   |
| Toshiba MQ01ABD050 500GB                        | 1         | 1.72%   |
| Toshiba MK2561GSYN 250GB                        | 1         | 1.72%   |
| Seagate ST9320320AS 320GB                       | 1         | 1.72%   |
| Seagate ST9160821AS 160GB                       | 1         | 1.72%   |
| Seagate ST9160411AS 160GB                       | 1         | 1.72%   |
| Seagate ST500LT012-9WS142 500GB                 | 1         | 1.72%   |
| Seagate ST500LM030-1RK17D 500GB                 | 1         | 1.72%   |
| Seagate ST1000LM014-1EJ164 1TB                  | 1         | 1.72%   |
| SanDisk X400 M.2 2280 512GB                     | 1         | 1.72%   |
| SanDisk SDSSDP064G 64GB                         | 1         | 1.72%   |
| SanDisk SD9SN8W-128G-1006 128GB                 | 1         | 1.72%   |
| Samsung SSD 970 EVO 250GB                       | 1         | 1.72%   |
| Samsung SSD 860 QVO 1TB                         | 1         | 1.72%   |
| Samsung SSD 860 EVO 500GB                       | 1         | 1.72%   |
| Samsung SSD 850 EVO 250GB                       | 1         | 1.72%   |
| Samsung MZVLQ512HALU-00000 512GB                | 1         | 1.72%   |
| Samsung MZVLB512HAJQ-000L7 512GB                | 1         | 1.72%   |
| Micron 2210_MTFDHBA512QFD 512GB                 | 1         | 1.72%   |
| Leven JAJS600M512C 512GB                        | 1         | 1.72%   |
| Leven JAJS300M480C 480GB                        | 1         | 1.72%   |
| Kingston SA400S37240G 240GB                     | 1         | 1.72%   |
| Kingston SA400S37120G 120GB                     | 1         | 1.72%   |
| Kingston RBUSNS8154P3256GJ3 256GB               | 1         | 1.72%   |
| Kingston OM8PCP3512F-AB 512GB                   | 1         | 1.72%   |
| KingDian S200 60GB                              | 1         | 1.72%   |
| Intenso SSD Sata III 256GB                      | 1         | 1.72%   |
| Intel SSDSC2BF180A4L 180GB                      | 1         | 1.72%   |
| Hitachi HTS548040M9AT00 40GB                    | 1         | 1.72%   |
| Hitachi HTS545050A7E380 500GB                   | 1         | 1.72%   |
| Hitachi HTS542525K9SA00 250GB                   | 1         | 1.72%   |
| HGST HTS545050A7E680 500GB                      | 1         | 1.72%   |
| Fujitsu MHY2120BH 120GB                         | 1         | 1.72%   |
| FORESEE 128GB SSD                               | 1         | 1.72%   |
| Crucial CT525MX300SSD1 528GB                    | 1         | 1.72%   |
| Crucial CT500MX500SSD1 500GB                    | 1         | 1.72%   |
| Crucial CT240BX500SSD1 240GB                    | 1         | 1.72%   |
| Crucial CT120BX300SSD1 120GB                    | 1         | 1.72%   |
| Crucial CT1000MX500SSD1 1TB                     | 1         | 1.72%   |
| ASUS PHISON SSD 32GB                            | 1         | 1.72%   |
| Apple SSD SM0128G 121GB                         | 1         | 1.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 9      | 29.41%  |
| Toshiba | 4         | 4      | 23.53%  |
| WDC     | 3         | 4      | 17.65%  |
| Hitachi | 3         | 4      | 17.65%  |
| HGST    | 1         | 1      | 5.88%   |
| Fujitsu | 1         | 1      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 13     | 22.58%  |
| Crucial             | 5         | 7      | 16.13%  |
| WDC                 | 3         | 3      | 9.68%   |
| SanDisk             | 3         | 3      | 9.68%   |
| Leven               | 2         | 2      | 6.45%   |
| Kingston            | 2         | 2      | 6.45%   |
| KingSpec            | 2         | 2      | 6.45%   |
| Toshiba             | 1         | 1      | 3.23%   |
| KingDian            | 1         | 1      | 3.23%   |
| Intenso             | 1         | 1      | 3.23%   |
| Intel               | 1         | 1      | 3.23%   |
| FORESEE             | 1         | 2      | 3.23%   |
| ASUSTek Computer    | 1         | 2      | 3.23%   |
| Apple               | 1         | 1      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 28        | 41     | 53.85%  |
| HDD  | 16        | 23     | 30.77%  |
| NVMe | 8         | 9      | 15.38%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 40        | 64     | 83.33%  |
| NVMe | 8         | 9      | 16.67%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 35        | 46     | 83.33%  |
| 0.51-1.0   | 7         | 18     | 16.67%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 24        | 48.98%  |
| 101-250    | 10        | 20.41%  |
| 251-500    | 7         | 14.29%  |
| 21-50      | 4         | 8.16%   |
| 501-1000   | 2         | 4.08%   |
| 51-100     | 2         | 4.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 44        | 86.27%  |
| 21-50   | 6         | 11.76%  |
| 51-100  | 1         | 1.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD050 500GB        | 1         | 1      | 11.11%  |
| Seagate ST9160821AS 160GB       | 1         | 1      | 11.11%  |
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 11.11%  |
| SanDisk SDSSDP064G 64GB         | 1         | 1      | 11.11%  |
| SanDisk SD9SN8W-128G-1006 128GB | 1         | 1      | 11.11%  |
| Intel SSDSC2BF180A4L 180GB      | 1         | 1      | 11.11%  |
| Hitachi HTS548040M9AT00 40GB    | 1         | 2      | 11.11%  |
| Hitachi HTS545050A7E380 500GB   | 1         | 1      | 11.11%  |
| Crucial CT525MX300SSD1 528GB    | 1         | 3      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 22.22%  |
| SanDisk | 2         | 2      | 22.22%  |
| Hitachi | 2         | 3      | 22.22%  |
| Toshiba | 1         | 1      | 11.11%  |
| Intel   | 1         | 1      | 11.11%  |
| Crucial | 1         | 3      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 40%     |
| Hitachi | 2         | 3      | 40%     |
| Toshiba | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 6      | 55.56%  |
| SSD  | 4         | 6      | 44.44%  |

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
| Works    | 38        | 59     | 79.17%  |
| Malfunc  | 9         | 12     | 18.75%  |
| Detected | 1         | 2      | 2.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 35        | 66.04%  |
| AMD                              | 7         | 13.21%  |
| Samsung Electronics              | 4         | 7.55%   |
| Kingston Technology Company      | 2         | 3.77%   |
| Union Memory (Shenzhen)          | 1         | 1.89%   |
| Silicon Integrated Systems [SiS] | 1         | 1.89%   |
| Micron Technology                | 1         | 1.89%   |
| JMicron Technology               | 1         | 1.89%   |
| Unknown                          | 1         | 1.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 7         | 11.29%  |
| AMD FCH SATA Controller [AHCI mode]                                                    | 6         | 9.68%   |
| Unknown                                                                                | 4         | 6.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 3         | 4.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 3         | 4.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 3         | 4.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 3         | 4.84%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 3         | 4.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 3         | 4.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 3.23%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 2         | 3.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 3.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 2         | 3.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 3.23%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 1         | 1.61%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 1         | 1.61%   |
| Samsung SM951 AHCI                                                                     | 1         | 1.61%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 1.61%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 1         | 1.61%   |
| JMicron JMB360 AHCI Controller                                                         | 1         | 1.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 1.61%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 1.61%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.61%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                 | 1         | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 1.61%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 1.61%   |
| AMD SB600 Non-Raid-5 SATA                                                              | 1         | 1.61%   |
| AMD SB600 IDE                                                                          | 1         | 1.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 37        | 64.91%  |
| IDE  | 10        | 17.54%  |
| NVMe | 8         | 14.04%  |
| RAID | 2         | 3.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 39        | 81.25%  |
| AMD    | 9         | 18.75%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz               | 2         | 4.08%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 2         | 4.08%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 2         | 4.08%   |
| Intel Atom CPU N450 @ 1.66GHz                   | 2         | 4.08%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 4.08%   |
| Intel Pentium M processor                       | 1         | 2.04%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz     | 1         | 2.04%   |
| Intel Pentium CPU P6200 @ 2.13GHz               | 1         | 2.04%   |
| Intel Pentium CPU P6200 @ 2.13GH                | 1         | 2.04%   |
| Intel Pentium CPU B960 @ 2.20GHz                | 1         | 2.04%   |
| Intel Pentium CPU 997 @ 1.60GHz                 | 1         | 2.04%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 2.04%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 1         | 2.04%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 1         | 2.04%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 1         | 2.04%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 1         | 2.04%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 1         | 2.04%   |
| Intel Core i5-5350U CPU @ 1.80GHz               | 1         | 2.04%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 1         | 2.04%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 2.04%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 1         | 2.04%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 2.04%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 2.04%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 1         | 2.04%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 1         | 2.04%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 1         | 2.04%   |
| Intel Core i3 CPU M 370 @ 2.40GHz               | 1         | 2.04%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz            | 1         | 2.04%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz            | 1         | 2.04%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz            | 1         | 2.04%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz            | 1         | 2.04%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz            | 1         | 2.04%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 1         | 2.04%   |
| Intel Celeron CPU 847 @ 1.10GHz                 | 1         | 2.04%   |
| Intel Celeron CPU 1017U @ 1.60GHz               | 1         | 2.04%   |
| Intel Atom CPU N270 @ 1.60GHz                   | 1         | 2.04%   |
| Intel 686-class                                 | 1         | 2.04%   |
| AMD Turion 64 X2 Mobile Technology TL-60        | 1         | 2.04%   |
| AMD Ryzen Embedded V1500B                       | 1         | 2.04%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 1         | 2.04%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 1         | 2.04%   |
| AMD E1-6010 APU with AMD Radeon R2 Graphics     | 1         | 2.04%   |
| AMD A6-5200 APU with Radeon HD Graphics         | 1         | 2.04%   |
| AMD A4-5000 APU with Radeon HD Graphics         | 1         | 2.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 13        | 26.53%  |
| Intel Core i7           | 6         | 12.24%  |
| Intel Core 2 Duo        | 5         | 10.2%   |
| Intel Pentium           | 4         | 8.16%   |
| Intel Core i3           | 3         | 6.12%   |
| Intel Celeron           | 3         | 6.12%   |
| Intel Atom              | 3         | 6.12%   |
| AMD Ryzen 5             | 3         | 6.12%   |
| Intel Pentium M         | 1         | 2.04%   |
| Intel Pentium Dual-Core | 1         | 2.04%   |
| Intel 686-class         | 1         | 2.04%   |
| AMD Turion 64 X2 Mobile | 1         | 2.04%   |
| AMD Ryzen Embedded      | 1         | 2.04%   |
| AMD Ryzen 7 PRO         | 1         | 2.04%   |
| AMD E1                  | 1         | 2.04%   |
| AMD A6                  | 1         | 2.04%   |
| AMD A4                  | 1         | 2.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 27        | 55.1%   |
| Unknown | 8         | 16.33%  |
| 4       | 7         | 14.29%  |
| 8       | 4         | 8.16%   |
| 1       | 2         | 4.08%   |
| 12      | 1         | 2.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 46        | 93.88%  |
| 2       | 2         | 4.08%   |
| Unknown | 1         | 2.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 24        | 48.98%  |
| 1       | 17        | 34.69%  |
| Unknown | 8         | 16.33%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| SandyBridge | 5         | 10.2%   |
| Penryn      | 5         | 10.2%   |
| KabyLake    | 5         | 10.2%   |
| IvyBridge   | 5         | 10.2%   |
| Broadwell   | 4         | 8.16%   |
| Zen+        | 3         | 6.12%   |
| Westmere    | 3         | 6.12%   |
| Haswell     | 3         | 6.12%   |
| Bonnell     | 3         | 6.12%   |
| Skylake     | 2         | 4.08%   |
| Jaguar      | 2         | 4.08%   |
| Unknown     | 2         | 4.08%   |
| Zen         | 1         | 2.04%   |
| Silvermont  | 1         | 2.04%   |
| Puma        | 1         | 2.04%   |
| P6          | 1         | 2.04%   |
| K8 Hammer   | 1         | 2.04%   |
| Core        | 1         | 2.04%   |
| CometLake   | 1         | 2.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 34        | 64.15%  |
| AMD    | 13        | 24.53%  |
| Nvidia | 6         | 11.32%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 8.77%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 7.02%   |
| Intel UHD Graphics 620                                                                   | 3         | 5.26%   |
| Intel HD Graphics 5500                                                                   | 3         | 5.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 5.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 5.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 3.51%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 3.51%   |
| Intel HD Graphics 620                                                                    | 2         | 3.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 3.51%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 3.51%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.75%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 1.75%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 1.75%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.75%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.75%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 1         | 1.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.75%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.75%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.75%   |
| Intel HD Graphics 6000                                                                   | 1         | 1.75%   |
| Intel HD Graphics 530                                                                    | 1         | 1.75%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.75%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 1.75%   |
| AMD Whistler LE [Radeon HD 6610M/7610M]                                                  | 1         | 1.75%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                                      | 1         | 1.75%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 1         | 1.75%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 1         | 1.75%   |
| AMD RV610/M72-S [Mobility Radeon HD 2400]                                                | 1         | 1.75%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 1.75%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 1         | 1.75%   |
| AMD Lucienne                                                                             | 1         | 1.75%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                                  | 1         | 1.75%   |
| AMD Kabini [Radeon HD 8330]                                                              | 1         | 1.75%   |
| AMD Cape Verde PRO / Venus LE / Tropo PRO-L [Radeon HD 8830M / R7 250 / R7 M465X]        | 1         | 1.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 22        | 45.83%  |
| 1 x AMD        | 11        | 22.92%  |
| 2 x Intel      | 6         | 12.5%   |
| Intel + Nvidia | 5         | 10.42%  |
| Other          | 1         | 2.08%   |
| 2 x AMD        | 1         | 2.08%   |
| 1 x Nvidia     | 1         | 2.08%   |
| Intel + AMD    | 1         | 2.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 43        | 87.76%  |
| Unknown     | 5         | 10.2%   |
| Proprietary | 1         | 2.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 77.08%  |
| 0.01-0.5   | 7         | 14.58%  |
| 1.01-2.0   | 3         | 6.25%   |
| 3.01-4.0   | 1         | 2.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 11        | 28.95%  |
| LG Display          | 7         | 18.42%  |
| BOE                 | 5         | 13.16%  |
| Chimei Innolux      | 4         | 10.53%  |
| Samsung Electronics | 2         | 5.26%   |
| Lenovo              | 2         | 5.26%   |
| Apple               | 2         | 5.26%   |
| ___                 | 1         | 2.63%   |
| LG Philips          | 1         | 2.63%   |
| Hewlett-Packard     | 1         | 2.63%   |
| HannStar            | 1         | 2.63%   |
| Fujitsu Siemens     | 1         | 2.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| ___ MY TV LED TV ___0101 1920x1080                                   | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 350x200mm 15.9-inch | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch | 1         | 2.63%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch          | 1         | 2.63%   |
| LG Display LCD Monitor LGD049B 1920x1080 340x190mm 15.3-inch         | 1         | 2.63%   |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch          | 1         | 2.63%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 1         | 2.63%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch          | 1         | 2.63%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch          | 1         | 2.63%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch          | 1         | 2.63%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch          | 1         | 2.63%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch              | 1         | 2.63%   |
| Lenovo LCD Monitor LEN40A3 1920x1080 310x170mm 13.9-inch             | 1         | 2.63%   |
| Hewlett-Packard 24fw HPN3605 1920x1080 530x300mm 24.0-inch           | 1         | 2.63%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch            | 1         | 2.63%   |
| Fujitsu Siemens B23T-6 LED FUS07FB 1920x1080 510x290mm 23.1-inch     | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch      | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 340x190mm 15.3-inch      | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch      | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 310x170mm 13.9-inch     | 1         | 2.63%   |
| BOE LCD Monitor BOE07F1 1920x1080 340x190mm 15.3-inch                | 1         | 2.63%   |
| BOE LCD Monitor BOE06D3 1366x768 340x190mm 15.3-inch                 | 1         | 2.63%   |
| BOE LCD Monitor BOE06A4 1366x768 340x190mm 15.3-inch                 | 1         | 2.63%   |
| BOE LCD Monitor BOE0691 1920x1080 280x160mm 12.7-inch                | 1         | 2.63%   |
| BOE LCD Monitor BOE0671 1366x768 340x190mm 15.3-inch                 | 1         | 2.63%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 340x190mm 15.3-inch       | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 310x170mm 13.9-inch       | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch       | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch        | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO31D2 1024x600 220x130mm 10.1-inch        | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 310x170mm 13.9-inch       | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch        | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO2A3C 1366x768 310x170mm 13.9-inch        | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch        | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch        | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO219E 1600x900 380x210mm 17.1-inch        | 1         | 2.63%   |
| Apple Color LCD APPA01B 1440x900 290x180mm 13.4-inch                 | 1         | 2.63%   |
| Apple Color LCD APP9C5C 1280x800 290x180mm 13.4-inch                 | 1         | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 19        | 51.35%  |
| 1920x1080 (FHD)  | 11        | 29.73%  |
| 1600x900 (HD+)   | 2         | 5.41%   |
| 1280x800 (WXGA)  | 2         | 5.41%   |
| 1024x600         | 2         | 5.41%   |
| 1440x900 (WXGA+) | 1         | 2.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 20        | 52.63%  |
| 13      | 9         | 23.68%  |
| 12      | 2         | 5.26%   |
| 10      | 2         | 5.26%   |
| 24      | 1         | 2.63%   |
| 23      | 1         | 2.63%   |
| 17      | 1         | 2.63%   |
| 11      | 1         | 2.63%   |
| Unknown | 1         | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 27        | 71.05%  |
| 201-300     | 7         | 18.42%  |
| 501-600     | 2         | 5.26%   |
| 351-400     | 1         | 2.63%   |
| Unknown     | 1         | 2.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 32        | 91.43%  |
| 16/10 | 3         | 8.57%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch?? | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 13        | 34.21%  |
| 81-90          | 9         | 23.68%  |
| 101-110        | 7         | 18.42%  |
| 61-70          | 2         | 5.26%   |
| 41-50          | 2         | 5.26%   |
| 201-250        | 2         | 5.26%   |
| 51-60          | 1         | 2.63%   |
| 121-130        | 1         | 2.63%   |
| Unknown        | 1         | 2.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 17        | 44.74%  |
| 121-160 | 11        | 28.95%  |
| 51-100  | 8         | 21.05%  |
| 161-240 | 1         | 2.63%   |
| Unknown | 1         | 2.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 37        | 74%     |
| 0     | 10        | 20%     |
| 2     | 3         | 6%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 22        | 28.95%  |
| Realtek Semiconductor            | 17        | 22.37%  |
| Qualcomm Atheros                 | 17        | 22.37%  |
| Broadcom                         | 8         | 10.53%  |
| Marvell Technology Group         | 2         | 2.63%   |
| Huawei Technologies              | 2         | 2.63%   |
| Silicon Integrated Systems [SiS] | 1         | 1.32%   |
| Samsung Electronics              | 1         | 1.32%   |
| OPPO Electronics                 | 1         | 1.32%   |
| NetGear                          | 1         | 1.32%   |
| JMicron Technology               | 1         | 1.32%   |
| Hewlett-Packard                  | 1         | 1.32%   |
| Edimax Technology                | 1         | 1.32%   |
| AMD                              | 1         | 1.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 13        | 13.13%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 5.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 4.04%   |
| Intel Wireless 8265 / 8275                                              | 4         | 4.04%   |
| Intel Wireless 7265                                                     | 4         | 4.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 2         | 2.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 2.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 2.02%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 2         | 2.02%   |
| Intel Wireless 8260                                                     | 2         | 2.02%   |
| Intel Wireless 7260                                                     | 2         | 2.02%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 2.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 2.02%   |
| Broadcom BCM43225 802.11b/g/n                                           | 2         | 2.02%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 2.02%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 1.01%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 1.01%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.01%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 1.01%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.01%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.01%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 1.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.01%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 1.01%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 1.01%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 1.01%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.01%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 1         | 1.01%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 1.01%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 1.01%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 1         | 1.01%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 1         | 1.01%   |
| OPPO SDM720G-IDP _SN:8A58D65F RNDIS Control RNDIS Ethernet Data         | 1         | 1.01%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                         | 1         | 1.01%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 1.01%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.01%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 1.01%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.01%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 1.01%   |
| Intel I210 Gigabit Network Connection                                   | 1         | 1.01%   |
| Intel Ethernet Connection I219-LM                                       | 1         | 1.01%   |
| Intel Ethernet Connection I218-V                                        | 1         | 1.01%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 1.01%   |
| Intel Ethernet Connection (4) I219-V                                    | 1         | 1.01%   |
| Intel Ethernet Connection (2) I219-LM                                   | 1         | 1.01%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.01%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 1         | 1.01%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                      | 1         | 1.01%   |
| Intel 82577LC Gigabit Network Connection                                | 1         | 1.01%   |
| Intel 82574L Gigabit Network Connection                                 | 1         | 1.01%   |
| Intel 82567LM Gigabit Network Connection                                | 1         | 1.01%   |
| Huawei ME936 LTE/HSDPA+ 4G modem                                        | 1         | 1.01%   |
| Huawei E353/E3131                                                       | 1         | 1.01%   |
| HP un2400 Gobi Wireless Modem (QDL mode)                                | 1         | 1.01%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1         | 1.01%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 1         | 1.01%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 1         | 1.01%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1         | 1.01%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 36.73%  |
| Qualcomm Atheros      | 16        | 32.65%  |
| Broadcom              | 7         | 14.29%  |
| Realtek Semiconductor | 6         | 12.24%  |
| NetGear               | 1         | 2.04%   |
| Edimax Technology     | 1         | 2.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 10.2%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 8.16%   |
| Intel Wireless 8265 / 8275                                              | 4         | 8.16%   |
| Intel Wireless 7265                                                     | 4         | 8.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 4.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 4.08%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 4.08%   |
| Intel Wireless 8260                                                     | 2         | 4.08%   |
| Intel Wireless 7260                                                     | 2         | 4.08%   |
| Broadcom BCM43225 802.11b/g/n                                           | 2         | 4.08%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 4.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 2.04%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 2.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 2.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 2.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 2.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 2.04%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 2.04%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                         | 1         | 2.04%   |
| Intel Wireless-AC 9260                                                  | 1         | 2.04%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 2.04%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 2.04%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 2.04%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 2.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 2.04%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1         | 2.04%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1         | 2.04%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 2.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 2.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 16        | 34.78%  |
| Intel                            | 14        | 30.43%  |
| Qualcomm Atheros                 | 7         | 15.22%  |
| Marvell Technology Group         | 2         | 4.35%   |
| Broadcom                         | 2         | 4.35%   |
| Silicon Integrated Systems [SiS] | 1         | 2.17%   |
| Samsung Electronics              | 1         | 2.17%   |
| OPPO Electronics                 | 1         | 2.17%   |
| JMicron Technology               | 1         | 2.17%   |
| AMD                              | 1         | 2.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 28.26%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 4.35%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 4.35%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.35%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 2.17%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2.17%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.17%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 2.17%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.17%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.17%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.17%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2.17%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 2.17%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 2.17%   |
| OPPO SDM720G-IDP _SN:8A58D65F RNDIS Control RNDIS Ethernet Data   | 1         | 2.17%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.17%   |
| Intel I210 Gigabit Network Connection                             | 1         | 2.17%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.17%   |
| Intel Ethernet Connection I218-V                                  | 1         | 2.17%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.17%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.17%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.17%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                | 1         | 2.17%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 2.17%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 2.17%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.17%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.17%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.17%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 1         | 2.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 45        | 48.91%  |
| Ethernet | 43        | 46.74%  |
| Modem    | 3         | 3.26%   |
| Unknown  | 1         | 1.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 35        | 51.47%  |
| Ethernet | 33        | 48.53%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 39        | 81.25%  |
| 1     | 6         | 12.5%   |
| 6     | 1         | 2.08%   |
| 5     | 1         | 2.08%   |
| 3     | 1         | 2.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 48        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 38.71%  |
| Qualcomm Atheros Communications | 4         | 12.9%   |
| Realtek Semiconductor           | 3         | 9.68%   |
| Lite-On Technology              | 2         | 6.45%   |
| IMC Networks                    | 2         | 6.45%   |
| Broadcom                        | 2         | 6.45%   |
| Apple                           | 2         | 6.45%   |
| Toshiba                         | 1         | 3.23%   |
| Hewlett-Packard                 | 1         | 3.23%   |
| Foxconn / Hon Hai               | 1         | 3.23%   |
| ASUSTek Computer                | 1         | 3.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 10        | 32.26%  |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 6.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 6.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 6.45%   |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip             | 1         | 3.23%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 3.23%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 3.23%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter  | 1         | 3.23%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 1         | 3.23%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 3.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 3.23%   |
| Intel AX201 Bluetooth                                       | 1         | 3.23%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 3.23%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 3.23%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 3.23%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 3.23%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                       | 1         | 3.23%   |
| Apple Built-in iSight (no firmware loaded)                  | 1         | 3.23%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 1         | 3.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 38        | 71.7%   |
| AMD                              | 12        | 22.64%  |
| Silicon Integrated Systems [SiS] | 1         | 1.89%   |
| Nvidia                           | 1         | 1.89%   |
| C-Media Electronics              | 1         | 1.89%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 10.29%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 8.82%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 7.35%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 5.88%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 5.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 4.41%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 4.41%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 4.41%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 4.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 4.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 4.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 4.41%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 4.41%   |
| AMD FCH Azalia Controller                                                                         | 3         | 4.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 2.94%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 1.47%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.47%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.47%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 1.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.47%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 1.47%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 1.47%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.47%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 1.47%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]                                 | 1         | 1.47%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.47%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 1.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 19        | 32.76%  |
| SK hynix            | 10        | 17.24%  |
| Unknown             | 8         | 13.79%  |
| Kingston            | 7         | 12.07%  |
| Micron Technology   | 5         | 8.62%   |
| Crucial             | 3         | 5.17%   |
| Nanya Technology    | 2         | 3.45%   |
| Transcend           | 1         | 1.72%   |
| Ramaxel Technology  | 1         | 1.72%   |
| ASint Technology    | 1         | 1.72%   |
| A-DATA Technology   | 1         | 1.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 8         | 12.7%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 4.76%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 3.17%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 3.17%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 3.17%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 3.17%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 2         | 3.17%   |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                      | 2         | 3.17%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s              | 1         | 1.59%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 1         | 1.59%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.59%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.59%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1.59%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.59%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB Chip DDR4 2133MT/s          | 1         | 1.59%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.59%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 1         | 1.59%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 1         | 1.59%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.59%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.59%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.59%   |
| Samsung RAM M471B5273BH1-CF8 4GB SODIMM DDR3 1067MT/s            | 1         | 1.59%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 1.59%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 1         | 1.59%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.59%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.59%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.59%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 667MT/s            | 1         | 1.59%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 1.59%   |
| Nanya RAM NT8GA64D88CX3S-JR 8GB SODIMM DDR4 3200MT/s             | 1         | 1.59%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1067MT/s             | 1         | 1.59%   |
| Micron RAM MT41K512M8RH-125:E 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.59%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                    | 1         | 1.59%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s            | 1         | 1.59%   |
| Micron RAM 8KTF5126 4HZ-1G6D1 4GB SODIMM DDR3 1600MT/s           | 1         | 1.59%   |
| Micron RAM 8JTF25664HZ-1G4H1 2GB SODIMM DDR3 1067MT/s            | 1         | 1.59%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.59%   |
| Kingston RAM HP16D3LS1KBG/4G 4096MB SODIMM DDR3 1600MT/s         | 1         | 1.59%   |
| Kingston RAM ACR16D3LS1NBG/4G 4GB SODIMM DDR3 800MT/s            | 1         | 1.59%   |
| Kingston RAM 99U5469-035.A00LF 4096MB SODIMM DDR3 1333MT/s       | 1         | 1.59%   |
| Kingston RAM 9905469-144.A00LF 4GB SODIMM DDR3 1333MT/s          | 1         | 1.59%   |
| Crucial RAM CT16G4SFRA32A.C8FB 16GB SODIMM DDR4 3200MT/s         | 1         | 1.59%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16GB SODIMM DDR4 2400MT/s       | 1         | 1.59%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 1         | 1.59%   |
| ASint RAM SSZ3128M8-EDJEF 2GB SODIMM DDR3 1067MT/s               | 1         | 1.59%   |
| ASint RAM SSY3128M8-EDJEF 1GB SODIMM DDR3 1067MT/s               | 1         | 1.59%   |
| A-DATA RAM Module 8GB SODIMM DDR4 2133MT/s                       | 1         | 1.59%   |
| A-DATA RAM Module 8192MB SODIMM DDR4 2133MT/s                    | 1         | 1.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 23        | 50%     |
| DDR4    | 11        | 23.91%  |
| DDR2    | 7         | 15.22%  |
| SDRAM   | 2         | 4.35%   |
| LPDDR3  | 1         | 2.17%   |
| DDR     | 1         | 2.17%   |
| Unknown | 1         | 2.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 44        | 95.65%  |
| Row Of Chips | 1         | 2.17%   |
| Chip         | 1         | 2.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 22        | 43.14%  |
| 2048  | 12        | 23.53%  |
| 8192  | 10        | 19.61%  |
| 16384 | 4         | 7.84%   |
| 1024  | 2         | 3.92%   |
| 256   | 1         | 1.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 15        | 28.85%  |
| 2667    | 6         | 11.54%  |
| 667     | 6         | 11.54%  |
| 1067    | 4         | 7.69%   |
| 2400    | 3         | 5.77%   |
| 2133    | 3         | 5.77%   |
| 1334    | 3         | 5.77%   |
| 1333    | 3         | 5.77%   |
| Unknown | 3         | 5.77%   |
| 3200    | 2         | 3.85%   |
| 800     | 2         | 3.85%   |
| 1867    | 1         | 1.92%   |
| 333     | 1         | 1.92%   |

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
| Chicony Electronics                    | 13        | 36.11%  |
| IMC Networks                           | 6         | 16.67%  |
| Realtek Semiconductor                  | 4         | 11.11%  |
| Acer                                   | 4         | 11.11%  |
| Sunplus Innovation Technology          | 2         | 5.56%   |
| Silicon Motion                         | 2         | 5.56%   |
| ALi                                    | 2         | 5.56%   |
| Suyin                                  | 1         | 2.78%   |
| Lite-On Technology                     | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek Lenovo EasyCamera                                  | 2         | 5.56%   |
| IMC Networks USB2.0 HD UVC WebCam                          | 2         | 5.56%   |
| Chicony Integrated Camera                                  | 2         | 5.56%   |
| Chicony HD WebCam (Acer)                                   | 2         | 5.56%   |
| Acer Integrated Camera                                     | 2         | 5.56%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                   | 1         | 2.78%   |
| Sunplus Integrated Camera                                  | 1         | 2.78%   |
| Sunplus Dell E5570 integrated webcam                       | 1         | 2.78%   |
| Silicon Motion Realtek USB2.0 PC Camera                    | 1         | 2.78%   |
| Silicon Motion HP Webcam-50                                | 1         | 2.78%   |
| Realtek USB Camera                                         | 1         | 2.78%   |
| Realtek Integrated_Webcam_HD                               | 1         | 2.78%   |
| Lite-On HP TrueVision HD Camera                            | 1         | 2.78%   |
| IMC Networks USB2.0 VGA UVC WebCam                         | 1         | 2.78%   |
| IMC Networks USB2.0 UVC HD Webcam                          | 1         | 2.78%   |
| IMC Networks Integrated Webcam                             | 1         | 2.78%   |
| IMC Networks Integrated Camera                             | 1         | 2.78%   |
| Chicony WebCam                                             | 1         | 2.78%   |
| Chicony USB2.0 VGA UVC WebCam                              | 1         | 2.78%   |
| Chicony ThinkPad T490 Webcam                               | 1         | 2.78%   |
| Chicony Thinkpad T430 camera                               | 1         | 2.78%   |
| Chicony Integrated Camera [ThinkPad]                       | 1         | 2.78%   |
| Chicony HP TrueVision HD Camera                            | 1         | 2.78%   |
| Chicony 2.0M UVC Webcam / CNF7129                          | 1         | 2.78%   |
| Chicony 1.3M Webcam                                        | 1         | 2.78%   |
| Chicony 1.3 MPixel UVC Webcam                              | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HP Universal Camera | 1         | 2.78%   |
| ALi M5602 Video Camera Controller                          | 1         | 2.78%   |
| ALi Gateway Webcam                                         | 1         | 2.78%   |
| Acer SunplusIT INC. Integrated Camera                      | 1         | 2.78%   |
| Acer HD Webcam                                             | 1         | 2.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| AuthenTec             | 2         | 33.33%  |
| Validity Sensors      | 1         | 16.67%  |
| Upek                  | 1         | 16.67%  |
| Synaptics             | 1         | 16.67%  |
| Elan Microelectronics | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 16.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 16.67%  |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 16.67%  |
| Elan ELAN WBF Fingerprint Sensor                       | 1         | 16.67%  |
| AuthenTec AES2810                                      | 1         | 16.67%  |
| AuthenTec AES1600                                      | 1         | 16.67%  |

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
| 2     | 18        | 36%     |
| 1     | 12        | 24%     |
| 0     | 10        | 20%     |
| 3     | 8         | 16%     |
| 4     | 2         | 4%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 28        | 37.33%  |
| Card reader              | 14        | 18.67%  |
| Net/wireless             | 11        | 14.67%  |
| Bluetooth                | 11        | 14.67%  |
| Fingerprint reader       | 6         | 8%      |
| Graphics card            | 2         | 2.67%   |
| Network                  | 1         | 1.33%   |
| Modem                    | 1         | 1.33%   |
| Firewire controller      | 1         | 1.33%   |

