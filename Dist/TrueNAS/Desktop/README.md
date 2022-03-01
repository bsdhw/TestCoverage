TrueNAS - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for TrueNAS.

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
| Supermicro    | X9DRD-7LN4F                 | [ea62f49750](https://bsd-hardware.info/?probe=ea62f49750) | Feb 15, 2022 |
| Supermicro    | X8STi                       | [970e2c91ec](https://bsd-hardware.info/?probe=970e2c91ec) | Feb 15, 2022 |
| Supermicro    | X9DRD-7LN4F                 | [74dffd5c4f](https://bsd-hardware.info/?probe=74dffd5c4f) | Feb 15, 2022 |
| Unknown       | Unknown                     | [bd78c2db3d](https://bsd-hardware.info/?probe=bd78c2db3d) | Jan 16, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [8c3181ee8d](https://bsd-hardware.info/?probe=8c3181ee8d) | Dec 29, 2021 |
| HP            | ProLiant ML150 G6           | [06b8fc5c06](https://bsd-hardware.info/?probe=06b8fc5c06) | Oct 18, 2021 |
| Supermicro    | X8SIE 0001                  | [fbd2abda35](https://bsd-hardware.info/?probe=fbd2abda35) | Oct 17, 2021 |
| ASRock        | B560M Pro4/ac               | [1b057f3b7d](https://bsd-hardware.info/?probe=1b057f3b7d) | Sep 23, 2021 |
| ASRock        | B560M Pro4/ac               | [fcf75fc410](https://bsd-hardware.info/?probe=fcf75fc410) | Sep 23, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [b00f275d35](https://bsd-hardware.info/?probe=b00f275d35) | Sep 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | [1038e3314d](https://bsd-hardware.info/?probe=1038e3314d) | Sep 21, 2021 |
| Supermicro    | X8SIE 0001                  | [f679c0bf61](https://bsd-hardware.info/?probe=f679c0bf61) | Jul 22, 2021 |
| Supermicro    | X8SIE 0001                  | [d739af226b](https://bsd-hardware.info/?probe=d739af226b) | Jul 20, 2021 |
| ASUSTek       | TUF Z270 MARK 2             | [fd0f333074](https://bsd-hardware.info/?probe=fd0f333074) | Jul 15, 2021 |
| Unknown       | Unknown                     | [df39a39ec7](https://bsd-hardware.info/?probe=df39a39ec7) | Jul 15, 2021 |
| Unknown       | Unknown                     | [968859e99d](https://bsd-hardware.info/?probe=968859e99d) | Jun 03, 2021 |
| ASRock        | C2750D4I                    | [e08a5e6f7c](https://bsd-hardware.info/?probe=e08a5e6f7c) | May 31, 2021 |
| ASRock        | C2750D4I                    | [9bd610c0ea](https://bsd-hardware.info/?probe=9bd610c0ea) | May 31, 2021 |
| Supermicro    | X9SCL/X9SCMA                | [e308becda4](https://bsd-hardware.info/?probe=e308becda4) | May 29, 2021 |
| Lenovo        | ThinkServer TS440           | [6390c16543](https://bsd-hardware.info/?probe=6390c16543) | May 28, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | [cec3cb521d](https://bsd-hardware.info/?probe=cec3cb521d) | May 20, 2021 |
| Unknown       | Unknown                     | [6b724a36cd](https://bsd-hardware.info/?probe=6b724a36cd) | Feb 19, 2021 |
| Unknown       | Unknown                     | [760e148164](https://bsd-hardware.info/?probe=760e148164) | Feb 19, 2021 |
| Unknown       | Unknown                     | [baf854930a](https://bsd-hardware.info/?probe=baf854930a) | Feb 19, 2021 |
| TYAN Compu... | S5512                       | [6a6164af73](https://bsd-hardware.info/?probe=6a6164af73) | Jan 27, 2021 |
| Unknown       | Unknown                     | [96ca836be9](https://bsd-hardware.info/?probe=96ca836be9) | Jan 19, 2021 |
| HP            | ProLiant MicroServer Gen... | [415023d5a1](https://bsd-hardware.info/?probe=415023d5a1) | Jan 10, 2021 |
| Gigabyte      | GA-A75-UD4H                 | [98fdc2713d](https://bsd-hardware.info/?probe=98fdc2713d) | Dec 18, 2020 |
| Gigabyte      | GA-A75-UD4H                 | [fb58243913](https://bsd-hardware.info/?probe=fb58243913) | Dec 18, 2020 |
| HP            | 3397                        | [3d51aa7204](https://bsd-hardware.info/?probe=3d51aa7204) | Dec 18, 2020 |
| Unknown       | Unknown                     | [aa113d54a8](https://bsd-hardware.info/?probe=aa113d54a8) | Dec 16, 2020 |
| Supermicro    | X9SPV-F/LN4F                | [24031a56b9](https://bsd-hardware.info/?probe=24031a56b9) | Dec 16, 2020 |
| Gigabyte      | H97-D3H-CF                  | [4d6f6bb683](https://bsd-hardware.info/?probe=4d6f6bb683) | Dec 16, 2020 |
| ASRock        | C2750D4I                    | [8328ebb73d](https://bsd-hardware.info/?probe=8328ebb73d) | Dec 16, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [714b6539cf](https://bsd-hardware.info/?probe=714b6539cf) | Nov 07, 2020 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 27       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 24       | 88.89%  |
| helloDesktop | 2        | 7.41%   |
| TWM          | 1        | 3.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 26       | 96.3%   |
| X11     | 1        | 3.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 27       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 27       | 100%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 17       | 62.96%  |
| EFI  | 10       | 37.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Zfs     | 24       | 88.89%  |
| XXX     | 2        | 7.41%   |
| Unknown | 1        | 3.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 27       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 6        | 22.22%  |
| Supermicro          | 5        | 18.52%  |
| Gigabyte Technology | 4        | 14.81%  |
| ASUSTek Computer    | 4        | 14.81%  |
| Hewlett-Packard     | 3        | 11.11%  |
| ASRock              | 3        | 11.11%  |
| TYAN Computer       | 1        | 3.7%    |
| Lenovo              | 1        | 3.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown                             | 6        | 22.22%  |
| TYAN S5512                          | 1        | 3.7%    |
| Supermicro X9SPV-F/LN4F             | 1        | 3.7%    |
| Supermicro X9SCL/X9SCM              | 1        | 3.7%    |
| Supermicro X9DRD-7LN4F              | 1        | 3.7%    |
| Supermicro X8STi                    | 1        | 3.7%    |
| Supermicro ReadyDATA 5200           | 1        | 3.7%    |
| Lenovo 70AQ0009UX ThinkServer TS440 | 1        | 3.7%    |
| HP ProLiant ML150 G6                | 1        | 3.7%    |
| HP ProLiant MicroServer Gen8        | 1        | 3.7%    |
| HP Compaq Elite 8300 SFF            | 1        | 3.7%    |
| Gigabyte H97-D3H                    | 1        | 3.7%    |
| Gigabyte GA-A75-UD4H                | 1        | 3.7%    |
| Gigabyte B550I AORUS PRO AX         | 1        | 3.7%    |
| Gigabyte B450M DS3H                 | 1        | 3.7%    |
| ASUS TUF Z270 MARK 2                | 1        | 3.7%    |
| ASUS M5A99X EVO R2.0                | 1        | 3.7%    |
| ASUS M5A78L-M/USB3                  | 1        | 3.7%    |
| ASUS M5A78L-M PLUS/USB3             | 1        | 3.7%    |
| ASRock FREENAS-MINI-XL-24TB-IXN     | 1        | 3.7%    |
| ASRock C2750D4I                     | 1        | 3.7%    |
| ASRock B560M Pro4/ac                | 1        | 3.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 6        | 22.22%  |
| HP ProLiant                     | 2        | 7.41%   |
| ASUS M5A78L-M                   | 2        | 7.41%   |
| TYAN S5512                      | 1        | 3.7%    |
| Supermicro X9SPV-F              | 1        | 3.7%    |
| Supermicro X9SCL                | 1        | 3.7%    |
| Supermicro X9DRD-7LN4F          | 1        | 3.7%    |
| Supermicro X8STi                | 1        | 3.7%    |
| Supermicro ReadyDATA            | 1        | 3.7%    |
| Lenovo 70AQ0009UX               | 1        | 3.7%    |
| HP Compaq                       | 1        | 3.7%    |
| Gigabyte H97-D3H                | 1        | 3.7%    |
| Gigabyte GA-A75-UD4H            | 1        | 3.7%    |
| Gigabyte B550I                  | 1        | 3.7%    |
| Gigabyte B450M                  | 1        | 3.7%    |
| ASUS TUF                        | 1        | 3.7%    |
| ASUS M5A99X                     | 1        | 3.7%    |
| ASRock FREENAS-MINI-XL-24TB-IXN | 1        | 3.7%    |
| ASRock C2750D4I                 | 1        | 3.7%    |
| ASRock B560M                    | 1        | 3.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 6        | 22.22%  |
| 2014    | 4        | 14.81%  |
| 2016    | 3        | 11.11%  |
| 2012    | 3        | 11.11%  |
| 2018    | 2        | 7.41%   |
| 2013    | 2        | 7.41%   |
| 2011    | 2        | 7.41%   |
| 2021    | 1        | 3.7%    |
| 2020    | 1        | 3.7%    |
| 2019    | 1        | 3.7%    |
| 2010    | 1        | 3.7%    |
| 2009    | 1        | 3.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 27       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 27       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 10       | 37.04%  |
| 16.01-24.0  | 7        | 25.93%  |
| 24.01-32.0  | 3        | 11.11%  |
| 64.01-256.0 | 3        | 11.11%  |
| 8.01-16.0   | 3        | 11.11%  |
| 4.01-8.0    | 1        | 3.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 9        | 33.33%  |
| 0.51-1.0   | 9        | 33.33%  |
| 2.01-3.0   | 2        | 7.41%   |
| 16.01-24.0 | 2        | 7.41%   |
| 4.01-8.0   | 1        | 3.7%    |
| 32.01-64.0 | 1        | 3.7%    |
| 3.01-4.0   | 1        | 3.7%    |
| 8.01-16.0  | 1        | 3.7%    |
| 0.01-0.5   | 1        | 3.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 0      | 6        | 21.43%  |
| 3      | 4        | 14.29%  |
| 17     | 2        | 7.14%   |
| 9      | 2        | 7.14%   |
| 6      | 2        | 7.14%   |
| 5      | 2        | 7.14%   |
| 4      | 2        | 7.14%   |
| 27     | 1        | 3.57%   |
| 21     | 1        | 3.57%   |
| 19     | 1        | 3.57%   |
| 12     | 1        | 3.57%   |
| 11     | 1        | 3.57%   |
| 10     | 1        | 3.57%   |
| 8      | 1        | 3.57%   |
| 2      | 1        | 3.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 96.43%  |
| Yes       | 1        | 3.57%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 27       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 92.59%  |
| Yes       | 2        | 7.41%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 92.59%  |
| Yes       | 2        | 7.41%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 9        | 33.33%  |
| Australia   | 3        | 11.11%  |
| Thailand    | 2        | 7.41%   |
| Czechia     | 2        | 7.41%   |
| Switzerland | 1        | 3.7%    |
| Spain       | 1        | 3.7%    |
| Norway      | 1        | 3.7%    |
| Nicaragua   | 1        | 3.7%    |
| Greece      | 1        | 3.7%    |
| Germany     | 1        | 3.7%    |
| France      | 1        | 3.7%    |
| Estonia     | 1        | 3.7%    |
| Canada      | 1        | 3.7%    |
| Brazil      | 1        | 3.7%    |
| Belgium     | 1        | 3.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Springfield       | 2        | 7.41%   |
| Melbourne         | 2        | 7.41%   |
| Brno              | 2        | 7.41%   |
| Bangkok           | 2        | 7.41%   |
| Yverdon-les-Bains | 1        | 3.7%    |
| Tartu             | 1        | 3.7%    |
| Sydney            | 1        | 3.7%    |
| Skiptvet          | 1        | 3.7%    |
| Raleigh           | 1        | 3.7%    |
| Perry Hall        | 1        | 3.7%    |
| Ougree            | 1        | 3.7%    |
| Northville        | 1        | 3.7%    |
| Managua           | 1        | 3.7%    |
| Lubbock           | 1        | 3.7%    |
| JaraguÃ¡ do Sul | 1        | 3.7%    |
| Fontaine-le-Comte | 1        | 3.7%    |
| Fayetteville      | 1        | 3.7%    |
| East Granby       | 1        | 3.7%    |
| Dresden           | 1        | 3.7%    |
| Clare             | 1        | 3.7%    |
| Calgary           | 1        | 3.7%    |
| Athens            | 1        | 3.7%    |
| Algete            | 1        | 3.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 63     | 21.05%  |
| Seagate             | 10       | 47     | 17.54%  |
| Hitachi             | 5        | 16     | 8.77%   |
| Toshiba             | 4        | 7      | 7.02%   |
| Samsung Electronics | 4        | 7      | 7.02%   |
| Kingston            | 4        | 9      | 7.02%   |
| Crucial             | 4        | 5      | 7.02%   |
| SanDisk             | 3        | 3      | 5.26%   |
| Hewlett-Packard     | 2        | 8      | 3.51%   |
| WD MediaMax         | 1        | 3      | 1.75%   |
| SPCC                | 1        | 1      | 1.75%   |
| PNY                 | 1        | 1      | 1.75%   |
| Mushkin             | 1        | 1      | 1.75%   |
| Intel               | 1        | 2      | 1.75%   |
| HPT                 | 1        | 16     | 1.75%   |
| HGST                | 1        | 10     | 1.75%   |
| Apacer              | 1        | 1      | 1.75%   |
| AMD                 | 1        | 2      | 1.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| WDC WD30EFRX-68EUZN0 3TB            | 4        | 3.39%   |
| WDC WD40EFRX-68N32N0 4TB            | 3        | 2.54%   |
| WDC WD60EFRX-68MYMN1 6TB            | 2        | 1.69%   |
| WDC WD40EFRX-68WT0N0 4TB            | 2        | 1.69%   |
| WDC WD30EFRX-68AX9N0 3TB            | 2        | 1.69%   |
| WDC WD20EFRX-68AX9N0 2TB            | 2        | 1.69%   |
| Seagate ST500DM002-1BD142 500GB     | 2        | 1.69%   |
| Samsung SSD 860 EVO 250GB           | 2        | 1.69%   |
| Kingston SA400S37120G 120GB         | 2        | 1.69%   |
| WDC WD8004FRYZ-01VAEB0 8TB          | 1        | 0.85%   |
| WDC WD5000LPLX-08ZNTT0 500GB        | 1        | 0.85%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1        | 0.85%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 1        | 0.85%   |
| WDC WD30PURX-64P6ZY0 3TB            | 1        | 0.85%   |
| WDC WD30EZRX-00MMMB0 3TB            | 1        | 0.85%   |
| WDC WD30EFRX-68N32N0 3TB            | 1        | 0.85%   |
| WDC WD3003FZEX-00Z4SA0 3TB          | 1        | 0.85%   |
| WDC WD3001FFSX-68JNUN0 3TB          | 1        | 0.85%   |
| WDC WD3000F9YZ-09N20L1 3TB          | 1        | 0.85%   |
| WDC WD3000F9YZ-09N20L0 3TB          | 1        | 0.85%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1        | 0.85%   |
| WDC WD2002FFSX-68PF8N0 2TB          | 1        | 0.85%   |
| WDC WD10PURX-64E5EY0 1TB            | 1        | 0.85%   |
| WDC WD10JPVX-80JC3T0 1TB            | 1        | 0.85%   |
| WDC WD10EZEX-00RKKA0 1TB            | 1        | 0.85%   |
| WDC WD10EURX-61C57Y0 1TB            | 1        | 0.85%   |
| WDC WD100EMAZ-00WJTA0 10TB          | 1        | 0.85%   |
| WD MediaMax WL2000GSA6454 2TB       | 1        | 0.85%   |
| Toshiba THNSNX032GTNT M.2 2242 32GB | 1        | 0.85%   |
| Toshiba THNSNX032GTNT 32GB          | 1        | 0.85%   |
| Toshiba HDWN180 8TB                 | 1        | 0.85%   |
| Toshiba HDWD130 3TB                 | 1        | 0.85%   |
| Toshiba DT01ACA300 3TB              | 1        | 0.85%   |
| Toshiba DT01ACA100 1TB              | 1        | 0.85%   |
| SPCC SPCCSolidStateDisk 256GB       | 1        | 0.85%   |
| Seagate ST980310AS 80GB             | 1        | 0.85%   |
| Seagate ST9320421AS 320GB           | 1        | 0.85%   |
| Seagate ST9320325AS 320GB           | 1        | 0.85%   |
| Seagate ST8000VN0022-2EL112 8TB     | 1        | 0.85%   |
| Seagate ST500DL001 HD503HI 500GB    | 1        | 0.85%   |
| Seagate ST4000DM005-2DP166 4TB      | 1        | 0.85%   |
| Seagate ST4000DM004-2CV104 4TB      | 1        | 0.85%   |
| Seagate ST4000DM000-1F2168 4TB      | 1        | 0.85%   |
| Seagate ST3320311CS 320GB           | 1        | 0.85%   |
| Seagate ST32000542AS 2TB            | 1        | 0.85%   |
| Seagate ST31500341AS 1.5TB          | 1        | 0.85%   |
| Seagate ST3000VN007-2E4166 3TB      | 1        | 0.85%   |
| Seagate ST3000VN000-1HJ166 3TB      | 1        | 0.85%   |
| Seagate ST3000DM008-2DM166 3TB      | 1        | 0.85%   |
| Seagate ST3000DM001-1ER166 3TB      | 1        | 0.85%   |
| Seagate ST3000DM001-1CH166 3TB      | 1        | 0.85%   |
| Seagate ST2000DM001-1ER164 2TB      | 1        | 0.85%   |
| Seagate ST2000DM001-1CH164 2TB      | 1        | 0.85%   |
| Seagate ST2000DL004 HD204UI 2TB     | 1        | 0.85%   |
| Seagate ST2000DL003-9VT166 2TB      | 1        | 0.85%   |
| Seagate ST2000DL001-9VT156 2TB      | 1        | 0.85%   |
| Seagate ST1000VM002-1SD102 1TB      | 1        | 0.85%   |
| Seagate ST1000NM0001 1TB            | 1        | 0.85%   |
| Seagate DKS2D-H3R0SS 3TB            | 1        | 0.85%   |
| SanDisk SDSSDHII120G 120GB          | 1        | 0.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 63     | 32.43%  |
| Seagate             | 10       | 47     | 27.03%  |
| Hitachi             | 5        | 16     | 13.51%  |
| Toshiba             | 4        | 5      | 10.81%  |
| Hewlett-Packard     | 2        | 8      | 5.41%   |
| WD MediaMax         | 1        | 3      | 2.7%    |
| Samsung Electronics | 1        | 3      | 2.7%    |
| HPT                 | 1        | 16     | 2.7%    |
| HGST                | 1        | 10     | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 4        | 7      | 21.05%  |
| SanDisk             | 3        | 3      | 15.79%  |
| Samsung Electronics | 3        | 4      | 15.79%  |
| Crucial             | 2        | 3      | 10.53%  |
| Toshiba             | 1        | 2      | 5.26%   |
| SPCC                | 1        | 1      | 5.26%   |
| PNY                 | 1        | 1      | 5.26%   |
| Mushkin             | 1        | 1      | 5.26%   |
| Intel               | 1        | 2      | 5.26%   |
| Apacer              | 1        | 1      | 5.26%   |
| AMD                 | 1        | 2      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 21       | 171    | 53.85%  |
| SSD  | 15       | 27     | 38.46%  |
| NVMe | 3        | 4      | 7.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 21       | 198    | 87.5%   |
| NVMe | 3        | 4      | 12.5%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 19       | 53     | 35.85%  |
| 2.01-3.0   | 10       | 57     | 18.87%  |
| 1.01-2.0   | 9        | 31     | 16.98%  |
| 3.01-4.0   | 6        | 23     | 11.32%  |
| 4.01-10.0  | 5        | 12     | 9.43%   |
| 0.51-1.0   | 3        | 19     | 5.66%   |
| 10.01-20.0 | 1        | 3      | 1.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 8        | 29.63%  |
| 101-250        | 6        | 22.22%  |
| 251-500        | 5        | 18.52%  |
| 21-50          | 2        | 7.41%   |
| 51-100         | 2        | 7.41%   |
| Unknown        | 2        | 7.41%   |
| More than 3000 | 1        | 3.7%    |
| 501-1000       | 1        | 3.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 25       | 92.59%  |
| Unknown | 2        | 7.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD30EFRX-68AX9N0 3TB       | 2        | 5      | 8.7%    |
| WDC WD60EFRX-68MYMN1 6TB       | 1        | 1      | 4.35%   |
| WDC WD5000AAKX-00U6AA0 500GB   | 1        | 1      | 4.35%   |
| WDC WD30PURX-64P6ZY0 3TB       | 1        | 1      | 4.35%   |
| WDC WD30EZRX-00MMMB0 3TB       | 1        | 2      | 4.35%   |
| WDC WD20EFRX-68AX9N0 2TB       | 1        | 1      | 4.35%   |
| WDC WD10PURX-64E5EY0 1TB       | 1        | 1      | 4.35%   |
| WDC WD10EZEX-00RKKA0 1TB       | 1        | 1      | 4.35%   |
| WD MediaMax WL2000GSA6454 2TB  | 1        | 3      | 4.35%   |
| Toshiba HDWD130 3TB            | 1        | 2      | 4.35%   |
| Seagate ST980310AS 80GB        | 1        | 1      | 4.35%   |
| Seagate ST9320325AS 320GB      | 1        | 1      | 4.35%   |
| Seagate ST4000DM000-1F2168 4TB | 1        | 1      | 4.35%   |
| Seagate ST3320311CS 320GB      | 1        | 2      | 4.35%   |
| Seagate ST31500341AS 1.5TB     | 1        | 1      | 4.35%   |
| Seagate ST3000VN007-2E4166 3TB | 1        | 1      | 4.35%   |
| Seagate ST2000DL003-9VT166 2TB | 1        | 1      | 4.35%   |
| Seagate ST2000DL001-9VT156 2TB | 1        | 1      | 4.35%   |
| Seagate ST1000VM002-1SD102 1TB | 1        | 2      | 4.35%   |
| Hitachi HTS725032A9A364 320GB  | 1        | 1      | 4.35%   |
| Hitachi HTS723232A7A364 320GB  | 1        | 1      | 4.35%   |
| Hitachi HDS723020BLA642 2TB    | 1        | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor      | Desktops | Drives | Percent |
|-------------|----------|--------|---------|
| Seagate     | 5        | 11     | 38.46%  |
| WDC         | 4        | 13     | 30.77%  |
| Hitachi     | 2        | 3      | 15.38%  |
| WD MediaMax | 1        | 3      | 7.69%   |
| Toshiba     | 1        | 2      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor      | Desktops | Drives | Percent |
|-------------|----------|--------|---------|
| Seagate     | 5        | 11     | 38.46%  |
| WDC         | 4        | 13     | 30.77%  |
| Hitachi     | 2        | 3      | 15.38%  |
| WD MediaMax | 1        | 3      | 7.69%   |
| Toshiba     | 1        | 2      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 32     | 100%    |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 21       | 149    | 65.63%  |
| Malfunc  | 9        | 32     | 28.13%  |
| Detected | 2        | 21     | 6.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 20       | 35.71%  |
| Broadcom / LSI              | 7        | 12.5%   |
| AMD                         | 7        | 12.5%   |
| Marvell Technology Group    | 6        | 10.71%  |
| Silicon Image               | 2        | 3.57%   |
| Micron/Crucial Technology   | 2        | 3.57%   |
| Kingston Technology Company | 2        | 3.57%   |
| JMicron Technology          | 2        | 3.57%   |
| Hewlett-Packard             | 2        | 3.57%   |
| ASMedia Technology          | 2        | 3.57%   |
| Silicon Motion              | 1        | 1.79%   |
| QLogic                      | 1        | 1.79%   |
| HighPoint Technologies      | 1        | 1.79%   |
| Areca Technology            | 1        | 1.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 6        | 9.23%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 4        | 6.15%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller          | 2        | 3.08%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2        | 3.08%   |
| Kingston Company A2000 NVMe SSD                                                | 2        | 3.08%   |
| JMicron JMB58x AHCI SATA controller                                            | 2        | 3.08%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                               | 2        | 3.08%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                               | 2        | 3.08%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2        | 3.08%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 2        | 3.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 3.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2        | 3.08%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2        | 3.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 3.08%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 3.08%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2        | 3.08%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 1.54%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 1.54%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller               | 1        | 1.54%   |
| QLogic QLA2100 64-bit Fibre Channel Adapter                                    | 1        | 1.54%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1        | 1.54%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 1.54%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1        | 1.54%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 1        | 1.54%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1        | 1.54%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1        | 1.54%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1        | 1.54%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1        | 1.54%   |
| Intel 6 Series/C200 Series Desktop SATA RAID Controller                        | 1        | 1.54%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 1.54%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1        | 1.54%   |
| HighPoint RocketRAID 2760 SAS Controller                                       | 1        | 1.54%   |
| HP Smart Array G6 controllers                                                  | 1        | 1.54%   |
| HP Smart Array Controller                                                      | 1        | 1.54%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                            | 1        | 1.54%   |
| Areca ARC-188x series PCIe 2.0/3.0 to SAS/SATA 6/12Gb RAID Controller          | 1        | 1.54%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 1        | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1        | 1.54%   |
| AMD FCH IDE Controller                                                         | 1        | 1.54%   |
| AMD 400 Series Chipset SATA Controller                                         | 1        | 1.54%   |
| Unknown                                                                        | 1        | 1.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 24       | 48%     |
| RAID | 9        | 18%     |
| SAS  | 6        | 12%     |
| NVMe | 5        | 10%     |
| IDE  | 5        | 10%     |
| SCSI | 1        | 2%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 20       | 74.07%  |
| AMD    | 7        | 25.93%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Intel Xeon CPU E5504 @ 2.00GHz           | 2        | 7.41%   |
| Intel Core i5-7500 CPU @ 3.40GHz         | 2        | 7.41%   |
| Intel Atom CPU C2750 @ 2.40GHz           | 2        | 7.41%   |
| Intel Xeon E-2224 CPU @ 3.40GHz          | 1        | 3.7%    |
| Intel Xeon CPU X3450 @ 2.67GHz           | 1        | 3.7%    |
| Intel Xeon CPU E5506 @ 2.13GHz           | 1        | 3.7%    |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz       | 1        | 3.7%    |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz      | 1        | 3.7%    |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz      | 1        | 3.7%    |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz      | 1        | 3.7%    |
| Intel Xeon CPU D-1518 @ 2.20GHz          | 1        | 3.7%    |
| Intel Core i7-3555LE CPU @ 2.50GHz       | 1        | 3.7%    |
| Intel Core i5-4590 CPU @ 3.30GHz         | 1        | 3.7%    |
| Intel Core i5-3470 CPU @ 3.20GHz         | 1        | 3.7%    |
| Intel Core i3-4330 CPU @ 3.50GHz         | 1        | 3.7%    |
| Intel Core i3-10100 CPU @ 3.60GHz        | 1        | 3.7%    |
| Intel Celeron CPU G1610T @ 2.30GHz       | 1        | 3.7%    |
| AMD Ryzen 7 1800X Eight-Core Processor   | 1        | 3.7%    |
| AMD Ryzen 5 3600 6-Core Processor        | 1        | 3.7%    |
| AMD FX-8320E Eight-Core Processor        | 1        | 3.7%    |
| AMD FX-8300 Eight-Core Processor         | 1        | 3.7%    |
| AMD FX-6300 Six-Core Processor           | 1        | 3.7%    |
| AMD E1-2500 APU with Radeon HD Graphics  | 1        | 3.7%    |
| AMD A8-3870 APU with Radeon HD Graphics  | 1        | 3.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| Intel Xeon    | 10       | 37.04%  |
| Intel Core i5 | 4        | 14.81%  |
| AMD FX        | 3        | 11.11%  |
| Intel Core i3 | 2        | 7.41%   |
| Intel Atom    | 2        | 7.41%   |
| Intel Core i7 | 1        | 3.7%    |
| Intel Celeron | 1        | 3.7%    |
| AMD Ryzen 7   | 1        | 3.7%    |
| AMD Ryzen 5   | 1        | 3.7%    |
| AMD E1        | 1        | 3.7%    |
| AMD A8        | 1        | 3.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 12       | 44.44%  |
| 8       | 7        | 25.93%  |
| 2       | 4        | 14.81%  |
| 16      | 1        | 3.7%    |
| 12      | 1        | 3.7%    |
| 6       | 1        | 3.7%    |
| Unknown | 1        | 3.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 24       | 88.89%  |
| 2      | 3        | 11.11%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 20       | 74.07%  |
| 2       | 6        | 22.22%  |
| Unknown | 1        | 3.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| IvyBridge   | 5        | 18.52%  |
| Nehalem     | 4        | 14.81%  |
| Piledriver  | 3        | 11.11%  |
| KabyLake    | 3        | 11.11%  |
| Haswell     | 3        | 11.11%  |
| Silvermont  | 2        | 7.41%   |
| Zen 2       | 1        | 3.7%    |
| Zen         | 1        | 3.7%    |
| SandyBridge | 1        | 3.7%    |
| K10 Llano   | 1        | 3.7%    |
| Jaguar      | 1        | 3.7%    |
| CometLake   | 1        | 3.7%    |
| Broadwell   | 1        | 3.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Matrox Electronics Systems | 9        | 34.62%  |
| Intel                      | 6        | 23.08%  |
| AMD                        | 6        | 23.08%  |
| ASPEED Technology          | 4        | 15.38%  |
| Nvidia                     | 1        | 3.85%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Matrox Electronics Systems MGA G200eW WPCM450                               | 5        | 19.23%  |
| ASPEED Technology ASPEED Graphics Family                                    | 4        | 15.38%  |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)           | 2        | 7.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 7.69%   |
| Intel HD Graphics 630                                                       | 2        | 7.69%   |
| AMD RS780L [Radeon 3000]                                                    | 2        | 7.69%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 3.85%   |
| Matrox Electronics Systems MGA G200eH3                                      | 1        | 3.85%   |
| Matrox Electronics Systems MGA G200EH                                       | 1        | 3.85%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 1        | 3.85%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 3.85%   |
| AMD Sumo [Radeon HD 6550D]                                                  | 1        | 3.85%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                     | 1        | 3.85%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 1        | 3.85%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 1        | 3.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Matrox | 9        | 33.33%  |
| 1 x Intel  | 6        | 22.22%  |
| 1 x AMD    | 6        | 22.22%  |
| 1 x ASPEED | 4        | 14.81%  |
| Other      | 1        | 3.7%    |
| 1 x Nvidia | 1        | 3.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 26       | 96.3%   |
| Unknown | 1        | 3.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 27       | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

Zero info for selected period =(

Monitor Model
-------------

Monitor models

Zero info for selected period =(

Monitor Resolution
------------------

Monitor screen resolution

Zero info for selected period =(

Monitor Diagonal
----------------

Diagonal size in inches

Zero info for selected period =(

Monitor Width
-------------

Physical width

Zero info for selected period =(

Aspect Ratio
------------

Proportional relationship between the width and the height

Zero info for selected period =(

Monitor Area
------------

Area in inch²

Zero info for selected period =(

Pixel Density
-------------

Pixels per inch

Zero info for selected period =(

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 27       | 100%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 21       | 65.63%  |
| Realtek Semiconductor | 7        | 21.88%  |
| Broadcom              | 3        | 9.38%   |
| QLogic                | 1        | 3.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 5        | 12.82%  |
| Intel 82574L Gigabit Network Connection                                       | 4        | 10.26%  |
| Intel I350 Gigabit Network Connection                                         | 3        | 7.69%   |
| Intel I210 Gigabit Network Connection                                         | 2        | 5.13%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 5.13%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 5.13%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 5.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 5.13%   |
| Intel 82576 Gigabit Network Connection                                        | 2        | 5.13%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 2        | 5.13%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 2.56%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 2.56%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1        | 2.56%   |
| Intel Wi-Fi 6 AX200                                                           | 1        | 2.56%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1        | 2.56%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 1        | 2.56%   |
| Intel Ethernet Connection I217-V                                              | 1        | 2.56%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 2.56%   |
| Intel 82580 Gigabit Network Connection                                        | 1        | 2.56%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 2.56%   |
| Intel 82571EB Gigabit Ethernet Controller                                     | 1        | 2.56%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1        | 2.56%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1        | 2.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 2        | 100%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                          | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200            | 1        | 50%     |
| Intel Tiger Lake PCH CNVi WiFi | 1        | 50%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 20       | 64.52%  |
| Realtek Semiconductor | 7        | 22.58%  |
| Broadcom              | 3        | 9.68%   |
| QLogic                | 1        | 3.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 5        | 13.51%  |
| Intel 82574L Gigabit Network Connection                                       | 4        | 10.81%  |
| Intel I350 Gigabit Network Connection                                         | 3        | 8.11%   |
| Intel I210 Gigabit Network Connection                                         | 2        | 5.41%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 5.41%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 5.41%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 5.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 5.41%   |
| Intel 82576 Gigabit Network Connection                                        | 2        | 5.41%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 2        | 5.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 2.7%    |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 2.7%    |
| QLogic cLOM8214 1/10GbE Controller                                            | 1        | 2.7%    |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 1        | 2.7%    |
| Intel Ethernet Connection I217-V                                              | 1        | 2.7%    |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 2.7%    |
| Intel 82580 Gigabit Network Connection                                        | 1        | 2.7%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 2.7%    |
| Intel 82571EB Gigabit Ethernet Controller                                     | 1        | 2.7%    |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1        | 2.7%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1        | 2.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 27       | 93.1%   |
| WiFi     | 2        | 6.9%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 27       | 100%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 9        | 33.33%  |
| 1     | 8        | 29.63%  |
| 5     | 4        | 14.81%  |
| 4     | 3        | 11.11%  |
| 6     | 2        | 7.41%   |
| 3     | 1        | 3.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 27       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 2        | 100%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1        | 50%     |
| Intel AX200 Bluetooth                          | 1        | 50%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 5        | 55.56%  |
| Intel  | 3        | 33.33%  |
| Nvidia | 1        | 11.11%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 15.38%  |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1        | 7.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1        | 7.69%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 1        | 7.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 1        | 7.69%   |
| AMD Starship/Matisse HD Audio Controller                                          | 1        | 7.69%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1        | 7.69%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 1        | 7.69%   |
| AMD FCH Azalia Controller                                                         | 1        | 7.69%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1        | 7.69%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]               | 1        | 7.69%   |
| Unknown                                                                           | 1        | 7.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 5        | 18.52%  |
| Samsung Electronics | 5        | 18.52%  |
| Micron Technology   | 5        | 18.52%  |
| Kingston            | 4        | 14.81%  |
| Toshiba             | 1        | 3.7%    |
| Team                | 1        | 3.7%    |
| SK Hynix            | 1        | 3.7%    |
| PNY                 | 1        | 3.7%    |
| Patriot             | 1        | 3.7%    |
| Hewlett-Packard     | 1        | 3.7%    |
| Crucial             | 1        | 3.7%    |
| Corsair             | 1        | 3.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s             | 1        | 3.45%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                   | 1        | 3.45%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                  | 1        | 3.45%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s             | 1        | 3.45%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 1        | 3.45%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 3.45%   |
| Toshiba RAM 9965525-138.A00LF 8192MB DIMM DDR3 1600MT/s  | 1        | 3.45%   |
| Team RAM Vulcan-2400 8192MB DIMM DDR3 1333MT/s           | 1        | 3.45%   |
| SK Hynix RAM HMT351R7CFR8A-H9 4096MB DIMM DDR3 800MT/s   | 1        | 3.45%   |
| Samsung RAM Module 8192MB DIMM DDR3 1600MT/s             | 1        | 3.45%   |
| Samsung RAM M393B2G70BH0-CH9 16384MB DIMM DDR3 1066MT/s  | 1        | 3.45%   |
| Samsung RAM M393B1K70DH0-CH9 8192MB DIMM DDR3 800MT/s    | 1        | 3.45%   |
| Samsung RAM M391B5173QH0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 3.45%   |
| Samsung RAM M391B1G73BH0-YH9 8192MB DIMM DDR3 1333MT/s   | 1        | 3.45%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8192MB DIMM DDR4 2133MT/s   | 1        | 3.45%   |
| Patriot RAM PSD416G26662 16384MB DIMM DDR4 2667MT/s      | 1        | 3.45%   |
| Micron RAM F7251U64F9333G 4096MB DIMM DDR3 1333MT/s      | 1        | 3.45%   |
| Micron RAM 18KSF1G72AZ-1G6P1 8GB DIMM DDR3 1600MT/s      | 1        | 3.45%   |
| Micron RAM 18KSF1G72AZ-1G4E1 8192MB DIMM DDR3 1333MT/s   | 1        | 3.45%   |
| Micron RAM 18JSF25672PDZ1G4F1 2048MB DIMM DDR3 1333MT/s  | 1        | 3.45%   |
| Micron RAM 18JDF25672PZ-1G4F1 2048MB DIMM DDR3 800MT/s   | 1        | 3.45%   |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1600MT/s      | 1        | 3.45%   |
| Kingston RAM 9965527-026.A00LF 8192MB DIMM DDR3 1333MT/s | 1        | 3.45%   |
| Kingston RAM 9965525-140.A00LF 8GB DIMM DDR3 1333MT/s    | 1        | 3.45%   |
| Kingston RAM 9965525-037.A00LF 8GB DIMM DDR3 1333MT/s    | 1        | 3.45%   |
| Kingston RAM 9965516-057.A00LF 8192MB DIMM DDR3 1066MT/s | 1        | 3.45%   |
| HP RAM Module 4096MB DIMM DDR3 1600MT/s                  | 1        | 3.45%   |
| Crucial RAM BL16G32C16U4B.16FE 16GB DIMM DDR4 3200MT/s   | 1        | 3.45%   |
| Corsair RAM CMD16GX4M2B3000C15 8192MB DIMM DDR4 2133MT/s | 1        | 3.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 14       | 66.67%  |
| DDR4    | 4        | 19.05%  |
| Unknown | 3        | 14.29%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 21       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 16       | 59.26%  |
| 4096  | 5        | 18.52%  |
| 16384 | 3        | 11.11%  |
| 2048  | 3        | 11.11%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1333  | 8        | 36.36%  |
| 1600  | 6        | 27.27%  |
| 2133  | 2        | 9.09%   |
| 800   | 2        | 9.09%   |
| 3200  | 1        | 4.55%   |
| 2667  | 1        | 4.55%   |
| 1066  | 1        | 4.55%   |
| 667   | 1        | 4.55%   |

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

Zero info for selected period =(

Camera Model
------------

Camera device models

Zero info for selected period =(

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

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


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 15       | 55.56%  |
| 2     | 4        | 14.81%  |
| 1     | 4        | 14.81%  |
| 3     | 3        | 11.11%  |
| 5     | 1        | 3.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Sound                    | 8        | 40%     |
| Communication controller | 7        | 35%     |
| Net/wireless             | 2        | 10%     |
| Bluetooth                | 2        | 10%     |
| Firewire controller      | 1        | 5%      |
