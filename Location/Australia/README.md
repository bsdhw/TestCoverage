BSD in Australia - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for BSD in Australia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Australia/Desktop/README.md) and [notebooks](/Location/Australia/Notebook/README.md).

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

Total: 233

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Protectli     | FW4B Ver                    | Desktop     | [f1838b29ff](https://bsd-hardware.info/?probe=f1838b29ff) | Jun 01, 2022 |
| Dell          | G5 5590                     | Notebook    | [86bac52410](https://bsd-hardware.info/?probe=86bac52410) | May 29, 2022 |
| Intel         | NUC9i7QNB K49245-402        | Mini pc     | [92881489e1](https://bsd-hardware.info/?probe=92881489e1) | May 22, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [fdab123532](https://bsd-hardware.info/?probe=fdab123532) | May 07, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [59083ac5ac](https://bsd-hardware.info/?probe=59083ac5ac) | May 06, 2022 |
| MSI           | 2A9C                        | Desktop     | [506b970279](https://bsd-hardware.info/?probe=506b970279) | May 03, 2022 |
| HP            | ZBook 14                    | Notebook    | [a646255b51](https://bsd-hardware.info/?probe=a646255b51) | May 02, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [3f170bdee6](https://bsd-hardware.info/?probe=3f170bdee6) | May 01, 2022 |
| Lenovo        | ThinkPad T470 20HES0ES1F    | Notebook    | [f1f0676663](https://bsd-hardware.info/?probe=f1f0676663) | Apr 28, 2022 |
| HP            | Notebook                    | Notebook    | [eea4cff90b](https://bsd-hardware.info/?probe=eea4cff90b) | Apr 27, 2022 |
| ASUSTek       | P9D-C Series                | Server      | [ac16999995](https://bsd-hardware.info/?probe=ac16999995) | Apr 22, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [76a2d4f148](https://bsd-hardware.info/?probe=76a2d4f148) | Apr 22, 2022 |
| HP            | Notebook                    | Notebook    | [eaff4f0fbf](https://bsd-hardware.info/?probe=eaff4f0fbf) | Apr 19, 2022 |
| MSI           | 2A9C                        | Desktop     | [9417bdd744](https://bsd-hardware.info/?probe=9417bdd744) | Apr 18, 2022 |
| MSI           | 2A9C                        | Desktop     | [595c9a1da2](https://bsd-hardware.info/?probe=595c9a1da2) | Apr 18, 2022 |
| MSI           | 2A9C                        | Desktop     | [7f44d30f83](https://bsd-hardware.info/?probe=7f44d30f83) | Apr 15, 2022 |
| HP            | Notebook                    | Notebook    | [6a112cfe6c](https://bsd-hardware.info/?probe=6a112cfe6c) | Apr 11, 2022 |
| HP            | Notebook                    | Notebook    | [a31dd5f48d](https://bsd-hardware.info/?probe=a31dd5f48d) | Apr 11, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [e32f0f2130](https://bsd-hardware.info/?probe=e32f0f2130) | Apr 08, 2022 |
| Lenovo        | 7X08CTO1WW                  | Server      | [46c59d0de8](https://bsd-hardware.info/?probe=46c59d0de8) | Apr 08, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [c807e1d8eb](https://bsd-hardware.info/?probe=c807e1d8eb) | Apr 07, 2022 |
| Protectli     | FW4B                        | Desktop     | [a2f902524b](https://bsd-hardware.info/?probe=a2f902524b) | Apr 06, 2022 |
| Protectli     | FW4B                        | Desktop     | [af9f2d81b5](https://bsd-hardware.info/?probe=af9f2d81b5) | Apr 06, 2022 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [1800a41f61](https://bsd-hardware.info/?probe=1800a41f61) | Mar 28, 2022 |
| Inventec      | D CLASS A02                 | Desktop     | [2ea328c95d](https://bsd-hardware.info/?probe=2ea328c95d) | Mar 28, 2022 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [8f20a3214b](https://bsd-hardware.info/?probe=8f20a3214b) | Mar 25, 2022 |
| Dell          | 0F0XJ6 A06                  | Server      | [e0599f5c69](https://bsd-hardware.info/?probe=e0599f5c69) | Mar 21, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [1e9ea7cdbc](https://bsd-hardware.info/?probe=1e9ea7cdbc) | Mar 19, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [8da46f8dd0](https://bsd-hardware.info/?probe=8da46f8dd0) | Mar 18, 2022 |
| Gigabyte      | 970A-D3P                    | Desktop     | [fa03bdabb6](https://bsd-hardware.info/?probe=fa03bdabb6) | Mar 15, 2022 |
| MSI           | MS-B1831                    | Desktop     | [346c445c21](https://bsd-hardware.info/?probe=346c445c21) | Mar 12, 2022 |
| HP            | 8103 A01                    | Mini pc     | [23b35e5b18](https://bsd-hardware.info/?probe=23b35e5b18) | Mar 10, 2022 |
| Dell          | G5 5590                     | Notebook    | [0871c1269b](https://bsd-hardware.info/?probe=0871c1269b) | Mar 07, 2022 |
| MSI           | MS-B1831                    | Desktop     | [572bb2c98c](https://bsd-hardware.info/?probe=572bb2c98c) | Mar 02, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [8d5986c1f4](https://bsd-hardware.info/?probe=8d5986c1f4) | Feb 26, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [68f6eb4328](https://bsd-hardware.info/?probe=68f6eb4328) | Feb 23, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [c1397b851e](https://bsd-hardware.info/?probe=c1397b851e) | Feb 22, 2022 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [51b0a953b5](https://bsd-hardware.info/?probe=51b0a953b5) | Feb 22, 2022 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [85441a65a9](https://bsd-hardware.info/?probe=85441a65a9) | Feb 21, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [1d9eaaaf62](https://bsd-hardware.info/?probe=1d9eaaaf62) | Feb 18, 2022 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [adcfe67709](https://bsd-hardware.info/?probe=adcfe67709) | Feb 16, 2022 |
| HP            | 8103 A01                    | Mini pc     | [d9222c59e5](https://bsd-hardware.info/?probe=d9222c59e5) | Feb 12, 2022 |
| MSI           | MS-B1831                    | Desktop     | [5bdc589f33](https://bsd-hardware.info/?probe=5bdc589f33) | Feb 10, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [0cc80ca4ec](https://bsd-hardware.info/?probe=0cc80ca4ec) | Feb 07, 2022 |
| MSI           | MS-B1831                    | Desktop     | [c8072d090e](https://bsd-hardware.info/?probe=c8072d090e) | Feb 06, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [6eecbfde04](https://bsd-hardware.info/?probe=6eecbfde04) | Feb 05, 2022 |
| Dell          | Latitude E7450              | Notebook    | [8a3867f171](https://bsd-hardware.info/?probe=8a3867f171) | Feb 03, 2022 |
| Lenovo        | ThinkCentre M58 7360BB6     | Desktop     | [8751a2776e](https://bsd-hardware.info/?probe=8751a2776e) | Jan 31, 2022 |
| Dell          | 0CN7CM A09                  | Server      | [3ec53e21df](https://bsd-hardware.info/?probe=3ec53e21df) | Jan 29, 2022 |
| Dell          | 0NC2VH A01                  | Desktop     | [21e1806645](https://bsd-hardware.info/?probe=21e1806645) | Jan 29, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [50b7edb511](https://bsd-hardware.info/?probe=50b7edb511) | Jan 29, 2022 |
| Dell          | 0NC2VH A01                  | Desktop     | [8587a16b51](https://bsd-hardware.info/?probe=8587a16b51) | Jan 29, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [6ea3284f28](https://bsd-hardware.info/?probe=6ea3284f28) | Jan 29, 2022 |
| Lenovo        | ThinkCentre M58 7360BB6     | Desktop     | [f53622f02b](https://bsd-hardware.info/?probe=f53622f02b) | Jan 27, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [b62251041b](https://bsd-hardware.info/?probe=b62251041b) | Jan 26, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [d180b0d394](https://bsd-hardware.info/?probe=d180b0d394) | Jan 25, 2022 |
| HP            | 8103 A01                    | Mini pc     | [147f49ca42](https://bsd-hardware.info/?probe=147f49ca42) | Jan 22, 2022 |
| Toshiba       | Satellite L50-A             | Notebook    | [94b87158aa](https://bsd-hardware.info/?probe=94b87158aa) | Jan 21, 2022 |
| Cisco         | ASA5512 A0                  | Desktop     | [99d276f574](https://bsd-hardware.info/?probe=99d276f574) | Jan 18, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [53b106bbb6](https://bsd-hardware.info/?probe=53b106bbb6) | Jan 16, 2022 |
| Dell          | 0XCR8D A03                  | Desktop     | [48e9447b37](https://bsd-hardware.info/?probe=48e9447b37) | Jan 15, 2022 |
| Gigabyte      | Z77N-WIFI                   | Desktop     | [459bb6486d](https://bsd-hardware.info/?probe=459bb6486d) | Jan 13, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [e0eb7a3239](https://bsd-hardware.info/?probe=e0eb7a3239) | Jan 13, 2022 |
| HP            | 8103 A01                    | Mini pc     | [2f22679aa6](https://bsd-hardware.info/?probe=2f22679aa6) | Jan 10, 2022 |
| HP            | 1998                        | Desktop     | [1d46974005](https://bsd-hardware.info/?probe=1d46974005) | Jan 03, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [d641a4bea9](https://bsd-hardware.info/?probe=d641a4bea9) | Dec 30, 2021 |
| ASUSTek       | X99-E-10G WS                | Desktop     | [dacf7f604c](https://bsd-hardware.info/?probe=dacf7f604c) | Dec 20, 2021 |
| Intel         | SKYBAY                      | Desktop     | [40d8768e52](https://bsd-hardware.info/?probe=40d8768e52) | Dec 20, 2021 |
| Protectli     | FW6 Ver                     | Desktop     | [52ba0807f9](https://bsd-hardware.info/?probe=52ba0807f9) | Dec 17, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [bc910b229a](https://bsd-hardware.info/?probe=bc910b229a) | Dec 12, 2021 |
| Intel         | NUC7JYB J67970-400          | Mini pc     | [c55f468566](https://bsd-hardware.info/?probe=c55f468566) | Dec 12, 2021 |
| Intel         | NUC7JYB J67970-400          | Mini pc     | [82c010f13c](https://bsd-hardware.info/?probe=82c010f13c) | Dec 09, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ab56e6eca2](https://bsd-hardware.info/?probe=ab56e6eca2) | Nov 23, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [645f845f43](https://bsd-hardware.info/?probe=645f845f43) | Nov 21, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [8a8efba0b3](https://bsd-hardware.info/?probe=8a8efba0b3) | Nov 19, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [8ebeac18ca](https://bsd-hardware.info/?probe=8ebeac18ca) | Nov 19, 2021 |
| HP            | 8103 A01                    | Mini pc     | [12763190f5](https://bsd-hardware.info/?probe=12763190f5) | Nov 16, 2021 |
| HP            | 8103 A01                    | Mini pc     | [8e779b15f3](https://bsd-hardware.info/?probe=8e779b15f3) | Nov 15, 2021 |
| Dell          | 0T10XW A01                  | Desktop     | [ae2203b146](https://bsd-hardware.info/?probe=ae2203b146) | Nov 12, 2021 |
| AAEON         | EMB-H61A V1.0               | Desktop     | [f13f63617f](https://bsd-hardware.info/?probe=f13f63617f) | Nov 11, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [fc32ac51e4](https://bsd-hardware.info/?probe=fc32ac51e4) | Nov 10, 2021 |
| HP            | 8103 A01                    | Mini pc     | [a6c494cc8f](https://bsd-hardware.info/?probe=a6c494cc8f) | Nov 08, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [4d9532acfa](https://bsd-hardware.info/?probe=4d9532acfa) | Nov 07, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [2a874a33dd](https://bsd-hardware.info/?probe=2a874a33dd) | Nov 05, 2021 |
| Gateway       | DX4840                      | Desktop     | [1d2e9e175c](https://bsd-hardware.info/?probe=1d2e9e175c) | Nov 01, 2021 |
| Dell          | 0NC2VH A01                  | Desktop     | [1f3657128e](https://bsd-hardware.info/?probe=1f3657128e) | Oct 30, 2021 |
| ADI Engine... | RCC-VE                      | Desktop     | [9744b5eca0](https://bsd-hardware.info/?probe=9744b5eca0) | Oct 29, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d2ffea0e21](https://bsd-hardware.info/?probe=d2ffea0e21) | Oct 29, 2021 |
| Supermicro    | X11SSH-F                    | Server      | [06db2a9c2f](https://bsd-hardware.info/?probe=06db2a9c2f) | Oct 29, 2021 |
| HP            | 18E9                        | Desktop     | [9c9a3a0297](https://bsd-hardware.info/?probe=9c9a3a0297) | Oct 27, 2021 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [ced0819a8e](https://bsd-hardware.info/?probe=ced0819a8e) | Oct 24, 2021 |
| ASUSTek       | P10S WS                     | Desktop     | [e2d86f8c45](https://bsd-hardware.info/?probe=e2d86f8c45) | Oct 23, 2021 |
| HP            | ProLiant ML150 G6           | Desktop     | [06b8fc5c06](https://bsd-hardware.info/?probe=06b8fc5c06) | Oct 18, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [63850e668d](https://bsd-hardware.info/?probe=63850e668d) | Oct 16, 2021 |
| Protectli     | FW4B                        | Desktop     | [e20e889703](https://bsd-hardware.info/?probe=e20e889703) | Oct 16, 2021 |
| Acer          | Veriton X4610G              | Desktop     | [2ca4d093d3](https://bsd-hardware.info/?probe=2ca4d093d3) | Oct 01, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [3fafbcecc5](https://bsd-hardware.info/?probe=3fafbcecc5) | Sep 30, 2021 |
| Dell          | 0NRF6V A01                  | Server      | [c08c97aacc](https://bsd-hardware.info/?probe=c08c97aacc) | Sep 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [2494d9d2db](https://bsd-hardware.info/?probe=2494d9d2db) | Sep 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [28bbeb8b2e](https://bsd-hardware.info/?probe=28bbeb8b2e) | Sep 26, 2021 |
| ASRock        | B560M Pro4/ac               | Desktop     | [1b057f3b7d](https://bsd-hardware.info/?probe=1b057f3b7d) | Sep 23, 2021 |
| ASRock        | B560M Pro4/ac               | Desktop     | [fcf75fc410](https://bsd-hardware.info/?probe=fcf75fc410) | Sep 23, 2021 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [be32d2981b](https://bsd-hardware.info/?probe=be32d2981b) | Sep 19, 2021 |
| Lenovo        | G40-70 20369                | Notebook    | [ef8eafa662](https://bsd-hardware.info/?probe=ef8eafa662) | Sep 18, 2021 |
| Gigabyte      | EP45-UD3R                   | Desktop     | [21e4a40d62](https://bsd-hardware.info/?probe=21e4a40d62) | Sep 18, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [49f080ea2e](https://bsd-hardware.info/?probe=49f080ea2e) | Sep 12, 2021 |
| Dell          | 0NC2VH A01                  | Desktop     | [8125c50b2a](https://bsd-hardware.info/?probe=8125c50b2a) | Sep 11, 2021 |
| Protectli     | FW4B                        | Desktop     | [941392a0bb](https://bsd-hardware.info/?probe=941392a0bb) | Sep 11, 2021 |
| HP            | 8103 A01                    | Mini pc     | [341ca2f887](https://bsd-hardware.info/?probe=341ca2f887) | Sep 03, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [fa4da2509b](https://bsd-hardware.info/?probe=fa4da2509b) | Sep 03, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [97035edd33](https://bsd-hardware.info/?probe=97035edd33) | Sep 03, 2021 |
| Intel         | SandyBridge Platform        | Notebook    | [f0aaf635c3](https://bsd-hardware.info/?probe=f0aaf635c3) | Sep 02, 2021 |
| ASRock        | Z390 Pro4                   | Desktop     | [ecbf097bc5](https://bsd-hardware.info/?probe=ecbf097bc5) | Sep 02, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [114ef9a519](https://bsd-hardware.info/?probe=114ef9a519) | Aug 30, 2021 |
| ASRock        | 990FX Killer                | Desktop     | [9f6f8fe218](https://bsd-hardware.info/?probe=9f6f8fe218) | Aug 22, 2021 |
| ASRock        | Z390 Pro4                   | Desktop     | [aca402061b](https://bsd-hardware.info/?probe=aca402061b) | Aug 18, 2021 |
| HP            | 8103 A01                    | Mini pc     | [f02d97dbeb](https://bsd-hardware.info/?probe=f02d97dbeb) | Aug 18, 2021 |
| Foxconn       | 2ADA                        | Desktop     | [e96976b2cc](https://bsd-hardware.info/?probe=e96976b2cc) | Aug 18, 2021 |
| HP            | 1825                        | Desktop     | [970bb6f787](https://bsd-hardware.info/?probe=970bb6f787) | Aug 17, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [7b20265c8e](https://bsd-hardware.info/?probe=7b20265c8e) | Aug 14, 2021 |
| Acer          | Veriton X4610G              | Desktop     | [619dedc13e](https://bsd-hardware.info/?probe=619dedc13e) | Aug 11, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [97781253f2](https://bsd-hardware.info/?probe=97781253f2) | Aug 03, 2021 |
| Microsoft     | Surface Go                  | Tablet      | [1dfbc72509](https://bsd-hardware.info/?probe=1dfbc72509) | Jul 30, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [8e67b63c6a](https://bsd-hardware.info/?probe=8e67b63c6a) | Jul 19, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [cfb68fd411](https://bsd-hardware.info/?probe=cfb68fd411) | Jul 14, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [519168441f](https://bsd-hardware.info/?probe=519168441f) | Jul 10, 2021 |
| Dell          | 0NC2VH A01                  | Desktop     | [d713cecb20](https://bsd-hardware.info/?probe=d713cecb20) | Jul 10, 2021 |
| ASRock        | Z390 Pro4                   | Desktop     | [dc4eb674ea](https://bsd-hardware.info/?probe=dc4eb674ea) | Jul 03, 2021 |
| Protectli     | FW2B Ver                    | Desktop     | [7b6f704247](https://bsd-hardware.info/?probe=7b6f704247) | Jun 30, 2021 |
| Dell          | 0NRF6V A01                  | Server      | [70fffc6930](https://bsd-hardware.info/?probe=70fffc6930) | Jun 22, 2021 |
| Dell          | 0GTK4K A02                  | Desktop     | [53f4f785ba](https://bsd-hardware.info/?probe=53f4f785ba) | Jun 22, 2021 |
| Dell          | 0GTK4K A02                  | Desktop     | [bb610333d0](https://bsd-hardware.info/?probe=bb610333d0) | Jun 22, 2021 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [cb7cbd17d0](https://bsd-hardware.info/?probe=cb7cbd17d0) | Jun 20, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [2a6f8cdb64](https://bsd-hardware.info/?probe=2a6f8cdb64) | Jun 20, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [c2cdbdb012](https://bsd-hardware.info/?probe=c2cdbdb012) | Jun 15, 2021 |
| HP            | 8103 A01                    | Mini pc     | [ffd1dd6fb1](https://bsd-hardware.info/?probe=ffd1dd6fb1) | Jun 14, 2021 |
| Protectli     | VP2410 10                   | Desktop     | [27a4d07d70](https://bsd-hardware.info/?probe=27a4d07d70) | Jun 12, 2021 |
| Protectli     | VP2410 10                   | Desktop     | [5dd0792386](https://bsd-hardware.info/?probe=5dd0792386) | Jun 12, 2021 |
| HP            | 8103 A01                    | Mini pc     | [8549e8b3c4](https://bsd-hardware.info/?probe=8549e8b3c4) | Jun 09, 2021 |
| Unknown       | J3160-4L                    | Desktop     | [3e773132b3](https://bsd-hardware.info/?probe=3e773132b3) | Jun 06, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [700ba3f063](https://bsd-hardware.info/?probe=700ba3f063) | May 31, 2021 |
| HP            | 8103 A01                    | Mini pc     | [1b26a44944](https://bsd-hardware.info/?probe=1b26a44944) | May 31, 2021 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [10d9e99990](https://bsd-hardware.info/?probe=10d9e99990) | May 31, 2021 |
| Dell          | 0CN7CM A09                  | Server      | [92a93d51c5](https://bsd-hardware.info/?probe=92a93d51c5) | May 23, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [33b86a7df2](https://bsd-hardware.info/?probe=33b86a7df2) | May 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [7ea373882a](https://bsd-hardware.info/?probe=7ea373882a) | May 19, 2021 |
| Intel         | NUC10i5FNB K61361-305       | Mini pc     | [a09fbe5fcc](https://bsd-hardware.info/?probe=a09fbe5fcc) | May 12, 2021 |
| Unknown       | Unknown                     | Desktop     | [72eb276213](https://bsd-hardware.info/?probe=72eb276213) | May 05, 2021 |
| Shuttle       | DH370                       | Desktop     | [ad380cb985](https://bsd-hardware.info/?probe=ad380cb985) | May 04, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [1c9feef8e7](https://bsd-hardware.info/?probe=1c9feef8e7) | May 03, 2021 |
| Lenovo        | SHARKBAY SDK0J40705 WIN     | Desktop     | [6a62687665](https://bsd-hardware.info/?probe=6a62687665) | May 03, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [3e211c52ea](https://bsd-hardware.info/?probe=3e211c52ea) | Apr 21, 2021 |
| Sophos        | SG                          | Firewall    | [88ea908224](https://bsd-hardware.info/?probe=88ea908224) | Apr 14, 2021 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [cb97f230b8](https://bsd-hardware.info/?probe=cb97f230b8) | Apr 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [821c81e652](https://bsd-hardware.info/?probe=821c81e652) | Apr 09, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [bc3913fead](https://bsd-hardware.info/?probe=bc3913fead) | Apr 06, 2021 |
| ASUSTek       | TP500LNG                    | Notebook    | [6501322932](https://bsd-hardware.info/?probe=6501322932) | Apr 06, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [bcaa207f9b](https://bsd-hardware.info/?probe=bcaa207f9b) | Apr 05, 2021 |
| Dell          | G5 5590                     | Notebook    | [18863bc535](https://bsd-hardware.info/?probe=18863bc535) | Apr 05, 2021 |
| Sophos        | SG                          | Firewall    | [76a33ea7ea](https://bsd-hardware.info/?probe=76a33ea7ea) | Mar 28, 2021 |
| Sophos        | SG                          | Firewall    | [487e450695](https://bsd-hardware.info/?probe=487e450695) | Mar 23, 2021 |
| HP            | ProBook 430 G3              | Notebook    | [32dfd5e52a](https://bsd-hardware.info/?probe=32dfd5e52a) | Mar 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [e66fe7a153](https://bsd-hardware.info/?probe=e66fe7a153) | Mar 21, 2021 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [bf9f69e68b](https://bsd-hardware.info/?probe=bf9f69e68b) | Mar 11, 2021 |
| Unknown       | Unknown                     | Notebook    | [70304f9c5d](https://bsd-hardware.info/?probe=70304f9c5d) | Mar 11, 2021 |
| Dell          | 0NC2VH A01                  | Desktop     | [bb7f6e1db9](https://bsd-hardware.info/?probe=bb7f6e1db9) | Mar 10, 2021 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [c88b021c05](https://bsd-hardware.info/?probe=c88b021c05) | Mar 09, 2021 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [7201058b50](https://bsd-hardware.info/?probe=7201058b50) | Mar 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [635419dc18](https://bsd-hardware.info/?probe=635419dc18) | Mar 07, 2021 |
| ASUSTek       | X99-E-10G WS                | Desktop     | [4e73497945](https://bsd-hardware.info/?probe=4e73497945) | Mar 06, 2021 |
| Intel         | NUC10i5FNB K61361-305       | Mini pc     | [953b768755](https://bsd-hardware.info/?probe=953b768755) | Mar 03, 2021 |
| PC Engines    | apu4                        | Desktop     | [2a3c8a81d5](https://bsd-hardware.info/?probe=2a3c8a81d5) | Mar 02, 2021 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [0951c73dba](https://bsd-hardware.info/?probe=0951c73dba) | Mar 01, 2021 |
| Dell          | 0NC2VH A01                  | Desktop     | [ec20bc7cea](https://bsd-hardware.info/?probe=ec20bc7cea) | Feb 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [950cf51db1](https://bsd-hardware.info/?probe=950cf51db1) | Feb 28, 2021 |
| HP            | 8103 A01                    | Mini pc     | [d436c0a897](https://bsd-hardware.info/?probe=d436c0a897) | Feb 27, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [8fda503f16](https://bsd-hardware.info/?probe=8fda503f16) | Feb 27, 2021 |
| ASUSTek       | B75M-PLUS                   | Desktop     | [8379cc790c](https://bsd-hardware.info/?probe=8379cc790c) | Feb 25, 2021 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [13c1f72630](https://bsd-hardware.info/?probe=13c1f72630) | Feb 24, 2021 |
| Dell          | 0XCR8D A03                  | Desktop     | [8aa33e35ad](https://bsd-hardware.info/?probe=8aa33e35ad) | Feb 21, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [1f25ddeb54](https://bsd-hardware.info/?probe=1f25ddeb54) | Feb 20, 2021 |
| Unknown       | Unknown                     | Desktop     | [6b724a36cd](https://bsd-hardware.info/?probe=6b724a36cd) | Feb 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [760e148164](https://bsd-hardware.info/?probe=760e148164) | Feb 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [baf854930a](https://bsd-hardware.info/?probe=baf854930a) | Feb 19, 2021 |
| ASRock        | B365M Pro4                  | Desktop     | [1c438d977e](https://bsd-hardware.info/?probe=1c438d977e) | Feb 18, 2021 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [be56203e79](https://bsd-hardware.info/?probe=be56203e79) | Feb 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [a2833c6695](https://bsd-hardware.info/?probe=a2833c6695) | Feb 08, 2021 |
| ASUSTek       | P5E3                        | Desktop     | [1d1edd3551](https://bsd-hardware.info/?probe=1d1edd3551) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | Notebook    | [a201c5f713](https://bsd-hardware.info/?probe=a201c5f713) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | Notebook    | [d0a5d1cb86](https://bsd-hardware.info/?probe=d0a5d1cb86) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | Notebook    | [a51cf81e58](https://bsd-hardware.info/?probe=a51cf81e58) | Feb 06, 2021 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [98e358b324](https://bsd-hardware.info/?probe=98e358b324) | Feb 05, 2021 |
| Radxa         | ROCK Pi X v1.4              | Desktop     | [688c95bda6](https://bsd-hardware.info/?probe=688c95bda6) | Feb 05, 2021 |
| HP            | 802E                        | Desktop     | [a7b2c5457c](https://bsd-hardware.info/?probe=a7b2c5457c) | Jan 29, 2021 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [40793aaedb](https://bsd-hardware.info/?probe=40793aaedb) | Jan 26, 2021 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [a2c7bfe3a1](https://bsd-hardware.info/?probe=a2c7bfe3a1) | Jan 26, 2021 |
| Lenovo        | 312D SDK0J40700 WIN 3258... | Mini pc     | [d15116d2eb](https://bsd-hardware.info/?probe=d15116d2eb) | Jan 25, 2021 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [a344f83f2e](https://bsd-hardware.info/?probe=a344f83f2e) | Jan 25, 2021 |
| Acer          | Veriton S6610G              | Desktop     | [64587ce287](https://bsd-hardware.info/?probe=64587ce287) | Jan 23, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [a78907417f](https://bsd-hardware.info/?probe=a78907417f) | Jan 22, 2021 |
| Dell          | 0NC2VH A01                  | Desktop     | [4afdd92b10](https://bsd-hardware.info/?probe=4afdd92b10) | Jan 20, 2021 |
| Toshiba       | KIRA                        | Notebook    | [1ee77fde0b](https://bsd-hardware.info/?probe=1ee77fde0b) | Jan 18, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [f51f3873ce](https://bsd-hardware.info/?probe=f51f3873ce) | Dec 25, 2020 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [5e8506d20e](https://bsd-hardware.info/?probe=5e8506d20e) | Dec 24, 2020 |
| HP            | 0B4Ch D                     | Desktop     | [bf0d7fe4f1](https://bsd-hardware.info/?probe=bf0d7fe4f1) | Dec 22, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [de7d8622aa](https://bsd-hardware.info/?probe=de7d8622aa) | Dec 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [7f6ebffad8](https://bsd-hardware.info/?probe=7f6ebffad8) | Dec 18, 2020 |
| Lenovo        | ThinkPad T460p 20FXCTO1W... | Notebook    | [ddc907ccf4](https://bsd-hardware.info/?probe=ddc907ccf4) | Dec 17, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [1414d7ae80](https://bsd-hardware.info/?probe=1414d7ae80) | Dec 16, 2020 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [4e217288fe](https://bsd-hardware.info/?probe=4e217288fe) | Dec 16, 2020 |
| ASUSTek       | K72F                        | Notebook    | [321cd9d139](https://bsd-hardware.info/?probe=321cd9d139) | Dec 08, 2020 |
| ASUSTek       | K72F                        | Notebook    | [b36ff0b052](https://bsd-hardware.info/?probe=b36ff0b052) | Dec 08, 2020 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [33724c243d](https://bsd-hardware.info/?probe=33724c243d) | Dec 06, 2020 |
| HP            | Setzer                      | Notebook    | [da7914cdd5](https://bsd-hardware.info/?probe=da7914cdd5) | Nov 22, 2020 |
| Lenovo        | ThinkPad T450 20BVA020AU    | Notebook    | [5d8bce59e8](https://bsd-hardware.info/?probe=5d8bce59e8) | Nov 16, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [ec13cfdd0d](https://bsd-hardware.info/?probe=ec13cfdd0d) | Oct 29, 2020 |
| Dell          | 0TW856 A02                  | Server      | [f181777604](https://bsd-hardware.info/?probe=f181777604) | Oct 29, 2020 |
| Dell          | 042P49 A02                  | Desktop     | [c34a9c7091](https://bsd-hardware.info/?probe=c34a9c7091) | Oct 29, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [c1c3ffb720](https://bsd-hardware.info/?probe=c1c3ffb720) | Oct 29, 2020 |
| Lenovo        | ThinkPad X230 2320JXM       | Notebook    | [cdbf62a168](https://bsd-hardware.info/?probe=cdbf62a168) | Oct 29, 2020 |
| Lenovo        | ThinkPad X60s 17033JM       | Notebook    | [67e701adb7](https://bsd-hardware.info/?probe=67e701adb7) | Oct 21, 2020 |
| Unknown       | Unknown                     | Desktop     | [a28ef1d2b8](https://bsd-hardware.info/?probe=a28ef1d2b8) | Oct 20, 2020 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [af179a268f](https://bsd-hardware.info/?probe=af179a268f) | Oct 19, 2020 |
| Acer          | Peppy                       | Notebook    | [d68bd5cbb5](https://bsd-hardware.info/?probe=d68bd5cbb5) | Oct 02, 2020 |
| Acer          | Peppy                       | Notebook    | [26058cddbf](https://bsd-hardware.info/?probe=26058cddbf) | Oct 02, 2020 |
| Unknown       | Unknown                     | Desktop     | [864589fce0](https://bsd-hardware.info/?probe=864589fce0) | Oct 02, 2020 |
| Apple         | MacBookAir5,1               | Notebook    | [6cced6fcf0](https://bsd-hardware.info/?probe=6cced6fcf0) | Sep 23, 2020 |
| Lenovo        | ThinkPad T460p 20FXCTO1W... | Notebook    | [b62876dd94](https://bsd-hardware.info/?probe=b62876dd94) | Aug 04, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [e4d2dcda5b](https://bsd-hardware.info/?probe=e4d2dcda5b) | Jul 31, 2020 |
| Dell          | 0D6H9T A00                  | Desktop     | [764aaaa200](https://bsd-hardware.info/?probe=764aaaa200) | Jun 04, 2020 |
| Dell          | 0D6H9T A00                  | Desktop     | [158ff0f1b6](https://bsd-hardware.info/?probe=158ff0f1b6) | Jun 04, 2020 |
| Lenovo        | ThinkPad X220 4291C35       | Notebook    | [f22c83f68b](https://bsd-hardware.info/?probe=f22c83f68b) | May 31, 2020 |
| HP            | ProLiant ML10 v2            | Desktop     | [aea3696f41](https://bsd-hardware.info/?probe=aea3696f41) | May 24, 2020 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| OPNsense 22.1       | 9         | 4.74%   |
| OPNsense 21.7.7     | 8         | 4.21%   |
| OPNsense 22.1.6     | 7         | 3.68%   |
| helloSystem 0.5.0   | 7         | 3.68%   |
| OPNsense 21.7.1     | 6         | 3.16%   |
| OPNsense 21.1.5     | 6         | 3.16%   |
| OPNsense 21.1.4     | 6         | 3.16%   |
| OPNsense 21.1.3     | 6         | 3.16%   |
| OPNsense 20.7.8     | 6         | 3.16%   |
| helloSystem 0.4.0   | 6         | 3.16%   |
| OPNsense 21.7.3     | 5         | 2.63%   |
| OPNsense 21.7.2     | 5         | 2.63%   |
| OPNsense 21.1.6     | 5         | 2.63%   |
| OPNsense 21.1.2     | 5         | 2.63%   |
| helloSystem 0.6.0   | 5         | 2.63%   |
| FreeBSD 13.0        | 5         | 2.63%   |
| FreeBSD 12.2        | 5         | 2.63%   |
| FreeBSD 12.1-p10    | 5         | 2.63%   |
| OPNsense 22.1.4     | 4         | 2.11%   |
| OPNsense 21.1.1     | 4         | 2.11%   |
| OPNsense 21.1       | 4         | 2.11%   |
| OpenBSD 6.8         | 4         | 2.11%   |
| OPNsense 21.7.5     | 3         | 1.58%   |
| OPNsense 21.7.4     | 3         | 1.58%   |
| OPNsense 21.1.8     | 3         | 1.58%   |
| FreeBSD 13.0-p4     | 3         | 1.58%   |
| OPNsense 22.1.5     | 2         | 1.05%   |
| OPNsense 22.1.3     | 2         | 1.05%   |
| OPNsense 22.1.2     | 2         | 1.05%   |
| OPNsense 22.1.1     | 2         | 1.05%   |
| OPNsense 21.7       | 2         | 1.05%   |
| OPNsense 20.7       | 2         | 1.05%   |
| helloSystem 0.7.0   | 2         | 1.05%   |
| GhostBSD 20.04.02   | 2         | 1.05%   |
| FreeBSD 13.1        | 2         | 1.05%   |
| FreeBSD 13.0-STABLE | 2         | 1.05%   |
| FreeBSD 12.1        | 2         | 1.05%   |
| TrueNAS 12.2-p9     | 1         | 0.53%   |
| TrueNAS 12.2-p3     | 1         | 0.53%   |
| TrueNAS 12.2-p10    | 1         | 0.53%   |
| OPNsense 22.1.7     | 1         | 0.53%   |
| OPNsense 21.7.8     | 1         | 0.53%   |
| OPNsense 21.7.6     | 1         | 0.53%   |
| OPNsense 21.1.9     | 1         | 0.53%   |
| OPNsense 21.1.7     | 1         | 0.53%   |
| OPNsense 20.1.7     | 1         | 0.53%   |
| OpenBSD 6.7         | 1         | 0.53%   |
| NomadBSD 5806f915   | 1         | 0.53%   |
| NomadBSD 1.4        | 1         | 0.53%   |
| NetBSD 9.99.94      | 1         | 0.53%   |
| GhostBSD 22.04.22   | 1         | 0.53%   |
| FreeNAS 11.4-p4     | 1         | 0.53%   |
| FreeNAS 11.3-p9     | 1         | 0.53%   |
| FreeBSD 13.0-RC5    | 1         | 0.53%   |
| FreeBSD 13.0-RC1    | 1         | 0.53%   |
| FreeBSD 13.0-p7     | 1         | 0.53%   |
| FreeBSD 13.0-p6     | 1         | 0.53%   |
| FreeBSD 13.0-p5     | 1         | 0.53%   |
| FreeBSD 13.0-p3     | 1         | 0.53%   |
| FreeBSD 13.0-BETA1  | 1         | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 82        | 54.3%   |
| FreeBSD     | 35        | 23.18%  |
| helloSystem | 19        | 12.58%  |
| OpenBSD     | 5         | 3.31%   |
| TrueNAS     | 3         | 1.99%   |
| NomadBSD    | 2         | 1.32%   |
| GhostBSD    | 2         | 1.32%   |
| FreeNAS     | 2         | 1.32%   |
| NetBSD      | 1         | 0.66%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 149       | 98.68%  |
| i386  | 1         | 0.66%   |
| arm64 | 1         | 0.66%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 99        | 64.29%  |
| helloDesktop | 20        | 12.99%  |
| KDE5         | 7         | 4.55%   |
| XFCE         | 6         | 3.9%    |
| GNOME        | 6         | 3.9%    |
| fvwm         | 4         | 2.6%    |
| TWM          | 3         | 1.95%   |
| i3           | 3         | 1.95%   |
| Openbox      | 2         | 1.3%    |
| MATE         | 1         | 0.65%   |
| Lumina       | 1         | 0.65%   |
| Fluxbox      | 1         | 0.65%   |
| AwesomeWM    | 1         | 0.65%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 103       | 68.21%  |
| X11     | 46        | 30.46%  |
| Wayland | 2         | 1.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 113       | 74.34%  |
| SLiM    | 22        | 14.47%  |
| SDDM    | 7         | 4.61%   |
| XDM     | 3         | 1.97%   |
| LightDM | 3         | 1.97%   |
| Ly      | 2         | 1.32%   |
| PCDM    | 1         | 0.66%   |
| GDM     | 1         | 0.66%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 99        | 63.87%  |
| en_US           | 28        | 18.06%  |
| C               | 14        | 9.03%   |
| en_AU           | 12        | 7.74%   |
| en_AU.US-ASCII  | 1         | 0.65%   |
| en_AU.ISO8859-1 | 1         | 0.65%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 115       | 76.16%  |
| BIOS | 36        | 23.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 83        | 54.25%  |
| Zfs    | 63        | 41.18%  |
| Ffs    | 5         | 3.27%   |
| Cd9660 | 2         | 1.31%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 133       | 88.08%  |
| MBR     | 17        | 11.26%  |
| Unknown | 1         | 0.66%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Hewlett-Packard            | 24        | 15.89%  |
| Lenovo                     | 21        | 13.91%  |
| Dell                       | 17        | 11.26%  |
| ASUSTek Computer           | 11        | 7.28%   |
| Protectli                  | 10        | 6.62%   |
| Intel                      | 9         | 5.96%   |
| ASRock                     | 8         | 5.3%    |
| Gigabyte Technology        | 7         | 4.64%   |
| Apple                      | 6         | 3.97%   |
| Unknown                    | 6         | 3.97%   |
| Toshiba                    | 3         | 1.99%   |
| MSI                        | 3         | 1.99%   |
| Acer                       | 3         | 1.99%   |
| MW                         | 2         | 1.32%   |
| AMI                        | 2         | 1.32%   |
| Yanling                    | 1         | 0.66%   |
| Unknown                    | 1         | 0.66%   |
| Supermicro                 | 1         | 0.66%   |
| Sophos                     | 1         | 0.66%   |
| Shuttle                    | 1         | 0.66%   |
| ShenZhen MinWin Technology | 1         | 0.66%   |
| SeeedStudio                | 1         | 0.66%   |
| Samsung Electronics        | 1         | 0.66%   |
| Raspberry Pi Foundation    | 1         | 0.66%   |
| Radxa                      | 1         | 0.66%   |
| PC Engines                 | 1         | 0.66%   |
| Microsoft                  | 1         | 0.66%   |
| Inventec                   | 1         | 0.66%   |
| HARDKERNEL                 | 1         | 0.66%   |
| Gateway                    | 1         | 0.66%   |
| Foxconn                    | 1         | 0.66%   |
| Cisco                      | 1         | 0.66%   |
| ADI Engineering            | 1         | 0.66%   |
| AAEON                      | 1         | 0.66%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Protectli FW4B                                                                           | 7         | 4.64%   |
| HP t730 Thin Client                                                                      | 7         | 4.64%   |
| Unknown                                                                                  | 7         | 4.64%   |
| HP ProLiant MicroServer                                                                  | 3         | 1.99%   |
| Dell OptiPlex 9020                                                                       | 3         | 1.99%   |
| MW GMLK-2_5G4L                                                                           | 2         | 1.32%   |
| Intel NUC10i5FNH                                                                         | 2         | 1.32%   |
| HP ProLiant MicroServer Gen8                                                             | 2         | 1.32%   |
| Dell OptiPlex 3010                                                                       | 2         | 1.32%   |
| ASUS All Series                                                                          | 2         | 1.32%   |
| Yanling YL-KBR6L                                                                         | 1         | 0.66%   |
| Toshiba Satellite L50-A                                                                  | 1         | 0.66%   |
| Toshiba PORTEGE Z10t-A                                                                   | 1         | 0.66%   |
| Toshiba KIRA                                                                             | 1         | 0.66%   |
| Supermicro Super Server                                                                  | 1         | 0.66%   |
| Sophos SG                                                                                | 1         | 0.66%   |
| Shuttle DH370                                                                            | 1         | 0.66%   |
| ShenZhen MinWin MW-NANO-APL-4L                                                           | 1         | 0.66%   |
| SeeedStudio ODYSSEY-X86J4125                                                             | 1         | 0.66%   |
| Samsung 350V5C/350V5X/350V4C/350V4X/351V5C/351V5X/351V4C/351V4X/3540VC/3540VX/3440VC/344 | 1         | 0.66%   |
| RPi Raspberry Pi                                                                         | 1         | 0.66%   |
| Radxa ROCK Pi X                                                                          | 1         | 0.66%   |
| Protectli VP2410                                                                         | 1         | 0.66%   |
| Protectli FW6                                                                            | 1         | 0.66%   |
| Protectli FW2B                                                                           | 1         | 0.66%   |
| PC Engines apu4                                                                          | 1         | 0.66%   |
| MSI Pro 3130 Small Form Factor PC                                                        | 1         | 0.66%   |
| MSI MS-7C95                                                                              | 1         | 0.66%   |
| MSI CML-U PRO Cubi 5 (MS-B183)                                                           | 1         | 0.66%   |
| Microsoft Surface Go                                                                     | 1         | 0.66%   |
| Lenovo ThinkSystem SR530 -[7X08CTO1WW]-                                                  | 1         | 0.66%   |
| Lenovo ThinkPad X60s 17033JM                                                             | 1         | 0.66%   |
| Lenovo ThinkPad X230 2320JXM                                                             | 1         | 0.66%   |
| Lenovo ThinkPad X220 4291C35                                                             | 1         | 0.66%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS02100                                                 | 1         | 0.66%   |
| Lenovo ThinkPad X1 Carbon 4th 20FC0019AU                                                 | 1         | 0.66%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB001XAU                                                 | 1         | 0.66%   |
| Lenovo ThinkPad X1 Carbon 3443CTO                                                        | 1         | 0.66%   |
| Lenovo ThinkPad T470 W10DG 20JM000BUS                                                    | 1         | 0.66%   |
| Lenovo ThinkPad T470 20HES0ES1F                                                          | 1         | 0.66%   |
| Lenovo ThinkPad T460p 20FXCTO1WW                                                         | 1         | 0.66%   |
| Lenovo ThinkPad T450 20BVA020AU                                                          | 1         | 0.66%   |
| Lenovo ThinkPad Mini10 3507A31                                                           | 1         | 0.66%   |
| Lenovo ThinkPad E420 1141CTO                                                             | 1         | 0.66%   |
| Lenovo ThinkCentre M93p 10AAS3UM00                                                       | 1         | 0.66%   |
| Lenovo ThinkCentre M92p 3238CE1                                                          | 1         | 0.66%   |
| Lenovo ThinkCentre M73 10AY009MAU                                                        | 1         | 0.66%   |
| Lenovo ThinkCentre M720q 10T7CTO1WW                                                      | 1         | 0.66%   |
| Lenovo ThinkCentre M700 10HY002XAU                                                       | 1         | 0.66%   |
| Lenovo ThinkCentre M58 7360BB6                                                           | 1         | 0.66%   |
| Lenovo G40-70 20369                                                                      | 1         | 0.66%   |
| Inventec D CLASS                                                                         | 1         | 0.66%   |
| Intel SandyBridge Platform                                                               | 1         | 0.66%   |
| Intel Q3XXG4-P V1.0                                                                      | 1         | 0.66%   |
| Intel NUC9i7QNX                                                                          | 1         | 0.66%   |
| Intel NUC8i3BEH                                                                          | 1         | 0.66%   |
| Intel NUC7CJYS                                                                           | 1         | 0.66%   |
| Intel NCB-4210WG                                                                         | 1         | 0.66%   |
| Intel DN2820FYK H24582-201                                                               | 1         | 0.66%   |
| HP ZBook 14                                                                              | 1         | 0.66%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo ThinkPad                | 13        | 8.61%   |
| Dell OptiPlex                  | 9         | 5.96%   |
| Protectli FW4B                 | 7         | 4.64%   |
| HP t730                        | 7         | 4.64%   |
| HP ProLiant                    | 7         | 4.64%   |
| Unknown                        | 7         | 4.64%   |
| Lenovo ThinkCentre             | 6         | 3.97%   |
| Dell PowerEdge                 | 5         | 3.31%   |
| MW GMLK-2                      | 2         | 1.32%   |
| Intel NUC10i5FNH               | 2         | 1.32%   |
| HP EliteDesk                   | 2         | 1.32%   |
| ASUS PRIME                     | 2         | 1.32%   |
| ASUS All                       | 2         | 1.32%   |
| ASRock X370                    | 2         | 1.32%   |
| Acer Veriton                   | 2         | 1.32%   |
| Yanling YL-KBR6L               | 1         | 0.66%   |
| Toshiba Satellite              | 1         | 0.66%   |
| Toshiba PORTEGE                | 1         | 0.66%   |
| Toshiba KIRA                   | 1         | 0.66%   |
| Supermicro Super               | 1         | 0.66%   |
| Sophos SG                      | 1         | 0.66%   |
| Shuttle DH370                  | 1         | 0.66%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1         | 0.66%   |
| SeeedStudio ODYSSEY-X86J4125   | 1         | 0.66%   |
| Samsung 350V5C                 | 1         | 0.66%   |
| RPi Raspberry                  | 1         | 0.66%   |
| Radxa ROCK                     | 1         | 0.66%   |
| Protectli VP2410               | 1         | 0.66%   |
| Protectli FW6                  | 1         | 0.66%   |
| Protectli FW2B                 | 1         | 0.66%   |
| PC Engines apu4                | 1         | 0.66%   |
| MSI Pro                        | 1         | 0.66%   |
| MSI MS-7C95                    | 1         | 0.66%   |
| MSI CML-U                      | 1         | 0.66%   |
| Microsoft Surface              | 1         | 0.66%   |
| Lenovo ThinkSystem             | 1         | 0.66%   |
| Lenovo G40-70                  | 1         | 0.66%   |
| Inventec D                     | 1         | 0.66%   |
| Intel SandyBridge              | 1         | 0.66%   |
| Intel Q3XXG4-P                 | 1         | 0.66%   |
| Intel NUC9i7QNX                | 1         | 0.66%   |
| Intel NUC8i3BEH                | 1         | 0.66%   |
| Intel NUC7CJYS                 | 1         | 0.66%   |
| Intel NCB-4210WG               | 1         | 0.66%   |
| Intel DN2820FYK                | 1         | 0.66%   |
| HP ZBook                       | 1         | 0.66%   |
| HP Z400                        | 1         | 0.66%   |
| HP Z240                        | 1         | 0.66%   |
| HP Setzer                      | 1         | 0.66%   |
| HP prodesk                     | 1         | 0.66%   |
| HP ProBook                     | 1         | 0.66%   |
| HP Notebook                    | 1         | 0.66%   |
| HP Laptop                      | 1         | 0.66%   |
| HARDKERNEL ODROID-H2           | 1         | 0.66%   |
| Gigabyte Z87N-WIFI             | 1         | 0.66%   |
| Gigabyte Z77N-WIFI             | 1         | 0.66%   |
| Gigabyte Z68MA-D2H-B3          | 1         | 0.66%   |
| Gigabyte J1900N-D3V            | 1         | 0.66%   |
| Gigabyte H270N-WIFI            | 1         | 0.66%   |
| Gigabyte EP45-UD3R             | 1         | 0.66%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 21        | 13.91%  |
| 2020    | 17        | 11.26%  |
| 2015    | 15        | 9.93%   |
| 2013    | 14        | 9.27%   |
| 2021    | 12        | 7.95%   |
| 2018    | 11        | 7.28%   |
| 2017    | 11        | 7.28%   |
| 2014    | 10        | 6.62%   |
| 2012    | 10        | 6.62%   |
| 2011    | 9         | 5.96%   |
| 2016    | 7         | 4.64%   |
| 2009    | 5         | 3.31%   |
| 2010    | 4         | 2.65%   |
| Unknown | 3         | 1.99%   |
| 2007    | 2         | 1.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 90        | 59.6%   |
| Notebook       | 33        | 21.85%  |
| Mini pc        | 16        | 10.6%   |
| Server         | 7         | 4.64%   |
| All in one     | 2         | 1.32%   |
| System on chip | 1         | 0.66%   |
| Tablet         | 1         | 0.66%   |
| Firewall       | 1         | 0.66%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 144       | 95.36%  |
| Yes  | 7         | 4.64%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 74        | 47.44%  |
| 16.01-24.0  | 33        | 21.15%  |
| 4.01-8.0    | 22        | 14.1%   |
| 32.01-64.0  | 10        | 6.41%   |
| 64.01-256.0 | 6         | 3.85%   |
| 2.01-3.0    | 4         | 2.56%   |
| 24.01-32.0  | 3         | 1.92%   |
| 3.01-4.0    | 2         | 1.28%   |
| 1.01-2.0    | 2         | 1.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 74        | 46.25%  |
| 0.51-1.0   | 47        | 29.38%  |
| 1.01-2.0   | 16        | 10%     |
| 4.01-8.0   | 8         | 5%      |
| 2.01-3.0   | 5         | 3.13%   |
| 8.01-16.0  | 3         | 1.88%   |
| 16.01-24.0 | 2         | 1.25%   |
| 32.01-64.0 | 1         | 0.63%   |
| 3.01-4.0   | 1         | 0.63%   |
| 24.01-32.0 | 1         | 0.63%   |
| 0          | 1         | 0.63%   |
| Unknown    | 1         | 0.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 106       | 69.74%  |
| 2      | 18        | 11.84%  |
| 0      | 11        | 7.24%   |
| 3      | 7         | 4.61%   |
| 4      | 6         | 3.95%   |
| 5      | 2         | 1.32%   |
| 7      | 1         | 0.66%   |
| 6      | 1         | 0.66%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 119       | 78.81%  |
| Yes       | 32        | 21.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 143       | 94.7%   |
| No        | 8         | 5.3%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 92        | 60.53%  |
| Yes       | 60        | 39.47%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 111       | 73.03%  |
| Yes       | 41        | 26.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Australia | 151       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sydney         | 37        | 22.84%  |
| Melbourne      | 23        | 14.2%   |
| Brisbane       | 22        | 13.58%  |
| Perth          | 18        | 11.11%  |
| Canberra       | 5         | 3.09%   |
| Adelaide       | 4         | 2.47%   |
| Hobart         | 3         | 1.85%   |
| Blackburn      | 3         | 1.85%   |
| Southport      | 2         | 1.23%   |
| Ryde           | 2         | 1.23%   |
| Morwell        | 2         | 1.23%   |
| Marrickville   | 2         | 1.23%   |
| Kellyville     | 2         | 1.23%   |
| East Malvern   | 2         | 1.23%   |
| Burwood        | 2         | 1.23%   |
| Wollongong     | 1         | 0.62%   |
| Wheelers Hill  | 1         | 0.62%   |
| Townsville     | 1         | 0.62%   |
| South Yarra    | 1         | 0.62%   |
| Shell Cove     | 1         | 0.62%   |
| Rosanna        | 1         | 0.62%   |
| Ringwood       | 1         | 0.62%   |
| Northcote      | 1         | 0.62%   |
| North Shore    | 1         | 0.62%   |
| Noble Park     | 1         | 0.62%   |
| Mount Waverley | 1         | 0.62%   |
| Mount Eliza    | 1         | 0.62%   |
| Mooroolbark    | 1         | 0.62%   |
| Mandurah       | 1         | 0.62%   |
| Malvern        | 1         | 0.62%   |
| Kurunjang      | 1         | 0.62%   |
| Ipswich        | 1         | 0.62%   |
| Gold Coast     | 1         | 0.62%   |
| Geelong        | 1         | 0.62%   |
| Engadine       | 1         | 0.62%   |
| Dowerin        | 1         | 0.62%   |
| Darlinghurst   | 1         | 0.62%   |
| Dandenong      | 1         | 0.62%   |
| Croydon        | 1         | 0.62%   |
| Corio          | 1         | 0.62%   |
| Busselton      | 1         | 0.62%   |
| Brunswick      | 1         | 0.62%   |
| Bayswater      | 1         | 0.62%   |
| Balwyn North   | 1         | 0.62%   |
| Ashfield       | 1         | 0.62%   |
| Ascot Vale     | 1         | 0.62%   |
| Alexandria     | 1         | 0.62%   |
| Adelaide CBD   | 1         | 0.62%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 28        | 37     | 16.37%  |
| Seagate             | 25        | 29     | 14.62%  |
| WDC                 | 22        | 56     | 12.87%  |
| Kingston            | 14        | 21     | 8.19%   |
| Toshiba             | 13        | 19     | 7.6%    |
| Intel               | 11        | 16     | 6.43%   |
| SanDisk             | 8         | 15     | 4.68%   |
| Crucial             | 7         | 9      | 4.09%   |
| Hoodisk             | 5         | 9      | 2.92%   |
| Protectli           | 3         | 3      | 1.75%   |
| Hewlett-Packard     | 3         | 6      | 1.75%   |
| Transcend           | 2         | 2      | 1.17%   |
| Phison              | 2         | 2      | 1.17%   |
| Micron Technology   | 2         | 4      | 1.17%   |
| Hitachi             | 2         | 5      | 1.17%   |
| HGST                | 2         | 2      | 1.17%   |
| Gigabyte Technology | 2         | 2      | 1.17%   |
| Apple               | 2         | 2      | 1.17%   |
| A-DATA Technology   | 2         | 7      | 1.17%   |
| XUNZHE              | 1         | 1      | 0.58%   |
| Vaseky              | 1         | 1      | 0.58%   |
| Union Memory        | 1         | 1      | 0.58%   |
| SPCC                | 1         | 5      | 0.58%   |
| SK Hynix            | 1         | 3      | 0.58%   |
| Silicon Motion      | 1         | 1      | 0.58%   |
| MAXTOR              | 1         | 1      | 0.58%   |
| Lenovo              | 1         | 1      | 0.58%   |
| KingSpec            | 1         | 1      | 0.58%   |
| KingDian            | 1         | 1      | 0.58%   |
| Fujitsu             | 1         | 1      | 0.58%   |
| Fordisk             | 1         | 1      | 0.58%   |
| Dogfish             | 1         | 1      | 0.58%   |
| China               | 1         | 1      | 0.58%   |
| Biwin               | 1         | 1      | 0.58%   |
| Apacer              | 1         | 1      | 0.58%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Hoodisk SSD 128GB                               | 5         | 2.72%   |
| Samsung SSD 840 EVO 250GB                       | 3         | 1.63%   |
| Kingston SA400S37480G 480GB                     | 3         | 1.63%   |
| Kingston SA400S37120G 120GB                     | 3         | 1.63%   |
| WDC WDS120G2G0B-00EPW0 120GB                    | 2         | 1.09%   |
| WDC WD40EFRX-68N32N0 4TB                        | 2         | 1.09%   |
| WDC WD20EZRX-00D8PB0 2TB                        | 2         | 1.09%   |
| WDC WD20EZAZ-00GGJB0 2TB                        | 2         | 1.09%   |
| Toshiba THNSF5256GPUK 256GB                     | 2         | 1.09%   |
| Toshiba MQ01ABD100 1TB                          | 2         | 1.09%   |
| Seagate ST9500325AS 500GB                       | 2         | 1.09%   |
| Seagate ST500LM021-1KJ152 500GB                 | 2         | 1.09%   |
| Seagate FireCuda 520 SSD ZP500GM30002 500GB     | 2         | 1.09%   |
| SanDisk SDSA6MM-032G-1006 32GB                  | 2         | 1.09%   |
| Samsung SSD 860 EVO 500GB                       | 2         | 1.09%   |
| Samsung SSD 850 EVO 500GB                       | 2         | 1.09%   |
| Samsung SSD 840 EVO 120GB                       | 2         | 1.09%   |
| Samsung MZ7LN128HCHP-000H1 128GB                | 2         | 1.09%   |
| Protectli 120GB mSATA                           | 2         | 1.09%   |
| Micron MTFDDAK256MAM-1K1 256GB                  | 2         | 1.09%   |
| Kingston SA400S37240G 240GB                     | 2         | 1.09%   |
| Intel SSDSCKKW240H6 240GB                       | 2         | 1.09%   |
| Crucial CT250MX500SSD1 250GB                    | 2         | 1.09%   |
| XUNZHE MSATA 128GB                              | 1         | 0.54%   |
| WDC WDS500G2B0B-00YS70 500GB                    | 1         | 0.54%   |
| WDC WDS500G1R0B-68A4Z0 500GB                    | 1         | 0.54%   |
| WDC WDS480G2G0A-00JH30 480GB                    | 1         | 0.54%   |
| WDC WDS250G2B0C-00PXH0 250GB                    | 1         | 0.54%   |
| WDC WDS250G2B0A-00SM50 250GB                    | 1         | 0.54%   |
| WDC WDS240G2G0B-00EPW0 240GB                    | 1         | 0.54%   |
| WDC WDS240G2G0A-00JH30 240GB                    | 1         | 0.54%   |
| WDC WD80EFAX-68KNBN0 8TB                        | 1         | 0.54%   |
| WDC WD7500BPKX-00HPJT0 752GB                    | 1         | 0.54%   |
| WDC WD5000BPKT-00PK4T0 500GB                    | 1         | 0.54%   |
| WDC WD5000AAKX-60U6AA0 500GB                    | 1         | 0.54%   |
| WDC WD40EFRX-68WT0N0 4TB                        | 1         | 0.54%   |
| WDC WD4000AAKS-00TMA0 400GB                     | 1         | 0.54%   |
| WDC WD30EFRX-68EUZN0 3TB                        | 1         | 0.54%   |
| WDC WD20EARX-00PASB0 2TB                        | 1         | 0.54%   |
| WDC WD20EARX-008FB0 2TB                         | 1         | 0.54%   |
| WDC WD20EARS-00MVWB0 2TB                        | 1         | 0.54%   |
| WDC WD10JPVX-60JC3T0 1TB                        | 1         | 0.54%   |
| WDC WD10EZEX-08WN4A0 1TB                        | 1         | 0.54%   |
| WDC WD10EZEX-00BN5A0 1TB                        | 1         | 0.54%   |
| WDC WD10EARX-00N0YB0 1TB                        | 1         | 0.54%   |
| WDC WD10EADS-00P8B0 1TB                         | 1         | 0.54%   |
| Vaseky V850-64G                                 | 1         | 0.54%   |
| Union Memory UMIS LENSE40256GMSP34MESTB3A 256GB | 1         | 0.54%   |
| Transcend TS64GSSD420K 64GB                     | 1         | 0.54%   |
| Transcend TS16EPTMM1600L 16GB                   | 1         | 0.54%   |
| Toshiba THNSNJ128GMCU 128GB                     | 1         | 0.54%   |
| Toshiba THNSNF256GMCS 256GB                     | 1         | 0.54%   |
| Toshiba THNSNF128GCSS 128GB                     | 1         | 0.54%   |
| Toshiba THNSF5256GCJ7 256GB                     | 1         | 0.54%   |
| Toshiba MQ04UBF100 1TB                          | 1         | 0.54%   |
| Toshiba MQ04UBD200 2TB                          | 1         | 0.54%   |
| Toshiba MQ03UBB200 2TB                          | 1         | 0.54%   |
| Toshiba MQ01UBB200 2TB                          | 1         | 0.54%   |
| Toshiba MQ01ABF050 500GB                        | 1         | 0.54%   |
| Toshiba KBG30ZPZ128G 128GB                      | 1         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 27     | 41.07%  |
| WDC                 | 15        | 45     | 26.79%  |
| Toshiba             | 6         | 8      | 10.71%  |
| Samsung Electronics | 3         | 5      | 5.36%   |
| Hewlett-Packard     | 3         | 6      | 5.36%   |
| Hitachi             | 2         | 5      | 3.57%   |
| HGST                | 2         | 2      | 3.57%   |
| MAXTOR              | 1         | 1      | 1.79%   |
| Fujitsu             | 1         | 1      | 1.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 29     | 23.91%  |
| Kingston            | 14        | 21     | 15.22%  |
| Intel               | 9         | 14     | 9.78%   |
| SanDisk             | 8         | 15     | 8.7%    |
| WDC                 | 7         | 10     | 7.61%   |
| Hoodisk             | 5         | 9      | 5.43%   |
| Crucial             | 5         | 5      | 5.43%   |
| Toshiba             | 3         | 6      | 3.26%   |
| Protectli           | 3         | 3      | 3.26%   |
| Transcend           | 2         | 2      | 2.17%   |
| Phison              | 2         | 2      | 2.17%   |
| Micron Technology   | 2         | 4      | 2.17%   |
| XUNZHE              | 1         | 1      | 1.09%   |
| Vaseky              | 1         | 1      | 1.09%   |
| Lenovo              | 1         | 1      | 1.09%   |
| KingSpec            | 1         | 1      | 1.09%   |
| KingDian            | 1         | 1      | 1.09%   |
| Fordisk             | 1         | 1      | 1.09%   |
| Dogfish             | 1         | 1      | 1.09%   |
| China               | 1         | 1      | 1.09%   |
| Apple               | 1         | 1      | 1.09%   |
| Apacer              | 1         | 1      | 1.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 84        | 130    | 54.19%  |
| HDD  | 47        | 100    | 30.32%  |
| NVMe | 24        | 38     | 15.48%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 121       | 230    | 83.45%  |
| NVMe | 24        | 38     | 16.55%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 104       | 165    | 77.04%  |
| 0.51-1.0   | 14        | 21     | 10.37%  |
| 1.01-2.0   | 12        | 31     | 8.89%   |
| 3.01-4.0   | 3         | 7      | 2.22%   |
| 2.01-3.0   | 1         | 2      | 0.74%   |
| 4.01-10.0  | 1         | 4      | 0.74%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 65        | 43.05%  |
| 251-500        | 26        | 17.22%  |
| 1-20           | 20        | 13.25%  |
| 501-1000       | 12        | 7.95%   |
| 51-100         | 12        | 7.95%   |
| 21-50          | 10        | 6.62%   |
| 1001-2000      | 3         | 1.99%   |
| 2001-3000      | 2         | 1.32%   |
| More than 3000 | 1         | 0.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 140       | 89.74%  |
| 21-50     | 10        | 6.41%   |
| 51-100    | 3         | 1.92%   |
| 101-250   | 2         | 1.28%   |
| 1001-2000 | 1         | 0.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB      | 1         | 1      | 5%      |
| WDC WD20EZRX-00D8PB0 2TB          | 1         | 2      | 5%      |
| WDC WD20EARX-008FB0 2TB           | 1         | 3      | 5%      |
| WDC WD20EARS-00MVWB0 2TB          | 1         | 1      | 5%      |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 5%      |
| Seagate ST500LM021-1KJ152 500GB   | 1         | 1      | 5%      |
| Seagate ST3250310AS 250GB         | 1         | 1      | 5%      |
| Seagate ST2000DL003-9VT166 2TB    | 1         | 1      | 5%      |
| SanDisk SDSSDA240G 240GB          | 1         | 1      | 5%      |
| Samsung Electronics HM500LI 500GB | 1         | 2      | 5%      |
| Phison SATA SSD 32GB              | 1         | 1      | 5%      |
| Kingston SNS4151S316G 16GB        | 1         | 1      | 5%      |
| Kingston SA400S37480G 480GB       | 1         | 1      | 5%      |
| Intel SSDSC2BF180A4L 180GB        | 1         | 1      | 5%      |
| Hitachi HDS721010KLA330 1TB       | 1         | 1      | 5%      |
| HGST HTS725050A7E630 500GB        | 1         | 1      | 5%      |
| Hewlett-Packard VB0250EAVER 250GB | 1         | 1      | 5%      |
| Crucial CT275MX300SSD4 275GB      | 1         | 1      | 5%      |
| Apple SSD SM256E 256GB            | 1         | 1      | 5%      |
| Apacer AS330 240GB                | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 21.05%  |
| WDC                 | 3         | 7      | 15.79%  |
| Kingston            | 2         | 2      | 10.53%  |
| SanDisk             | 1         | 1      | 5.26%   |
| Samsung Electronics | 1         | 2      | 5.26%   |
| Phison              | 1         | 1      | 5.26%   |
| Intel               | 1         | 1      | 5.26%   |
| Hitachi             | 1         | 1      | 5.26%   |
| HGST                | 1         | 1      | 5.26%   |
| Hewlett-Packard     | 1         | 1      | 5.26%   |
| Crucial             | 1         | 1      | 5.26%   |
| Apple               | 1         | 1      | 5.26%   |
| Apacer              | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 40%     |
| WDC                 | 2         | 6      | 20%     |
| Samsung Electronics | 1         | 2      | 10%     |
| Hitachi             | 1         | 1      | 10%     |
| HGST                | 1         | 1      | 10%     |
| Hewlett-Packard     | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 15     | 52.63%  |
| SSD  | 9         | 9      | 47.37%  |

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

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 125       | 243    | 86.21%  |
| Malfunc  | 19        | 24     | 13.1%   |
| Detected | 1         | 1      | 0.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 117       | 67.63%  |
| AMD                       | 23        | 13.29%  |
| Broadcom / LSI            | 6         | 3.47%   |
| Toshiba                   | 4         | 2.31%   |
| Samsung Electronics       | 4         | 2.31%   |
| Phison Electronics        | 3         | 1.73%   |
| Silicon Motion            | 2         | 1.16%   |
| Seagate Technology        | 2         | 1.16%   |
| Union Memory (Shenzhen)   | 1         | 0.58%   |
| Silicon Image             | 1         | 0.58%   |
| Sandisk                   | 1         | 0.58%   |
| Realtek Semiconductor     | 1         | 0.58%   |
| QLogic                    | 1         | 0.58%   |
| Nvidia                    | 1         | 0.58%   |
| Micron/Crucial Technology | 1         | 0.58%   |
| Micron Technology         | 1         | 0.58%   |
| JMicron Technology        | 1         | 0.58%   |
| Hewlett-Packard           | 1         | 0.58%   |
| ADATA Technology          | 1         | 0.58%   |
| Adaptec                   | 1         | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14        | 6.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13        | 6.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12        | 5.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 10        | 4.98%   |
| AMD FCH IDE Controller                                                                  | 8         | 3.98%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 7         | 3.48%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 7         | 3.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7         | 3.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6         | 2.99%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 6         | 2.99%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6         | 2.99%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 2.49%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5         | 2.49%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4         | 1.99%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.49%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 1.49%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 1.49%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3         | 1.49%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 1.49%   |
| Toshiba XG4 NVMe SSD Controller                                                         | 2         | 1%      |
| Seagate FireCuda 520 SSD                                                                | 2         | 1%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 1%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1%      |
| Phison PS5013 E13 NVMe Controller                                                       | 2         | 1%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 1%      |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 2         | 1%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2         | 1%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 1%      |
| AMD X370 Series Chipset SATA Controller                                                 | 2         | 1%      |
| AMD FCH SATA Controller D                                                               | 2         | 1%      |
| Unknown                                                                                 | 2         | 1%      |
| Union Memory (Shenzhen) NVMe 256G SSD device                                            | 1         | 0.5%    |
| Toshiba NVMe Controller                                                                 | 1         | 0.5%    |
| Toshiba BG3 NVMe SSD Controller                                                         | 1         | 0.5%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 0.5%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1         | 0.5%    |
| Silicon Image AAR-1220SA Serial ATA HostRAID Controller                                 | 1         | 0.5%    |
| Sandisk unknown                                                                         | 1         | 0.5%    |
| QLogic QLA2100 64-bit Fibre Channel Adapter                                             | 1         | 0.5%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.5%    |
| Nvidia MCP79 AHCI Controller                                                            | 1         | 0.5%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1         | 0.5%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 1         | 0.5%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 1         | 0.5%    |
| Intel SSD 660P Series                                                                   | 1         | 0.5%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1         | 0.5%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 1         | 0.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 0.5%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 0.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 0.5%    |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 1         | 0.5%    |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 1         | 0.5%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1         | 0.5%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1         | 0.5%    |
| Intel Atom processor C2000 AHCI SATA3 Controller                                        | 1         | 0.5%    |
| Intel Atom processor C2000 AHCI SATA2 Controller                                        | 1         | 0.5%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1         | 0.5%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1         | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 129       | 67.89%  |
| NVMe | 23        | 12.11%  |
| IDE  | 23        | 12.11%  |
| RAID | 10        | 5.26%   |
| SCSI | 3         | 1.58%   |
| SAS  | 2         | 1.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 127       | 84.11%  |
| AMD    | 23        | 15.23%  |
| ARM    | 1         | 0.66%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron CPU J3160 @ 1.60GHz           | 8         | 5.26%   |
| AMD RX-427BB with AMD Radeon R7 Graphics    | 7         | 4.61%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 4         | 2.63%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3         | 1.97%   |
| Intel Xeon CPU E5504 @ 2.00GHz              | 2         | 1.32%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 1.32%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2         | 1.32%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 2         | 1.32%   |
| Intel Core i7-3667U CPU @ 2.00GHz           | 2         | 1.32%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 2         | 1.32%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 2         | 1.32%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2         | 1.32%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 1.32%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2         | 1.32%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 1.32%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 2         | 1.32%   |
| AMD Turion II Neo N54L Dual-Core Processor  | 2         | 1.32%   |
| AMD FX-8350 Eight-Core Processor            | 2         | 1.32%   |
| Intel Xeon Silver 4208 CPU @ 2.10GHz        | 1         | 0.66%   |
| Intel Xeon E-2224G CPU @ 3.50GHz            | 1         | 0.66%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1         | 0.66%   |
| Intel Xeon CPU E5506 @ 2.13GHz              | 1         | 0.66%   |
| Intel Xeon CPU E5310 @ 1.60GHz              | 1         | 0.66%   |
| Intel Xeon CPU E5-2430L v2 @ 2.40GHz        | 1         | 0.66%   |
| Intel Xeon CPU E5-2430 v2 @ 2.50GHz         | 1         | 0.66%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz          | 1         | 0.66%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz         | 1         | 0.66%   |
| Intel Xeon CPU E31230 @ 3.20GHz             | 1         | 0.66%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz        | 1         | 0.66%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz         | 1         | 0.66%   |
| Intel Xeon CPU E3-1240 v5 @ 3.50GHz         | 1         | 0.66%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz         | 1         | 0.66%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz         | 1         | 0.66%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1         | 0.66%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GH          | 1         | 0.66%   |
| Intel Xeon                                  | 1         | 0.66%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1         | 0.66%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.66%   |
| Intel Pentium CPU G6950 @ 2.80GHz           | 1         | 0.66%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1         | 0.66%   |
| Intel Pentium CPU G4400T @ 2.90GHz          | 1         | 0.66%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1         | 0.66%   |
| Intel Pentium CPU 4415Y @ 1.60GHz           | 1         | 0.66%   |
| Intel CPU Version                           | 1         | 0.66%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1         | 0.66%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.66%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.66%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.66%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 0.66%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.66%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.66%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz          | 1         | 0.66%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.66%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 0.66%   |
| Intel Core i7-3615QM CPU @ 2.30GHz          | 1         | 0.66%   |
| Intel Core i7-3537U CPU @ 2.00GHz           | 1         | 0.66%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.66%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1         | 0.66%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 0.66%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 34        | 22.52%  |
| Intel Celeron           | 24        | 15.89%  |
| Intel Core i7           | 21        | 13.91%  |
| Intel Xeon              | 18        | 11.92%  |
| Intel Core i3           | 14        | 9.27%   |
| Other                   | 8         | 5.3%    |
| Intel Pentium           | 6         | 3.97%   |
| Intel Atom              | 3         | 1.99%   |
| AMD Turion II Neo       | 3         | 1.99%   |
| AMD Ryzen 5             | 3         | 1.99%   |
| AMD FX                  | 3         | 1.99%   |
| Intel Core 2 Quad       | 2         | 1.32%   |
| AMD Ryzen 3             | 2         | 1.32%   |
| Intel Xeon Silver       | 1         | 0.66%   |
| Intel Pentium Dual-Core | 1         | 0.66%   |
| Intel Core Duo          | 1         | 0.66%   |
| Intel Core 2 Duo        | 1         | 0.66%   |
| ARM Cortex              | 1         | 0.66%   |
| AMD GX                  | 1         | 0.66%   |
| AMD G                   | 1         | 0.66%   |
| AMD E2                  | 1         | 0.66%   |
| AMD Athlon              | 1         | 0.66%   |
| AMD A6                  | 1         | 0.66%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 72        | 47.68%  |
| 2       | 53        | 35.1%   |
| 8       | 9         | 5.96%   |
| 6       | 9         | 5.96%   |
| Unknown | 5         | 3.31%   |
| 12      | 2         | 1.32%   |
| 1       | 1         | 0.66%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 144       | 95.36%  |
| 2       | 5         | 3.31%   |
| Unknown | 2         | 1.32%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 86        | 56.95%  |
| 2       | 60        | 39.74%  |
| Unknown | 5         | 3.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 21        | 13.91%  |
| Haswell       | 20        | 13.25%  |
| IvyBridge     | 19        | 12.58%  |
| Silvermont    | 16        | 10.6%   |
| Skylake       | 12        | 7.95%   |
| SandyBridge   | 11        | 7.28%   |
| Steamroller   | 7         | 4.64%   |
| Goldmont plus | 6         | 3.97%   |
| Nehalem       | 5         | 3.31%   |
| Westmere      | 4         | 2.65%   |
| Broadwell     | 4         | 2.65%   |
| Piledriver    | 3         | 1.99%   |
| Penryn        | 3         | 1.99%   |
| K10           | 3         | 1.99%   |
| Zen           | 2         | 1.32%   |
| Puma          | 2         | 1.32%   |
| Core          | 2         | 1.32%   |
| Bobcat        | 2         | 1.32%   |
| Zen+          | 1         | 0.66%   |
| Zen 3         | 1         | 0.66%   |
| Zen 2         | 1         | 0.66%   |
| P6            | 1         | 0.66%   |
| Jaguar        | 1         | 0.66%   |
| Goldmont      | 1         | 0.66%   |
| CometLake     | 1         | 0.66%   |
| Bonnell       | 1         | 0.66%   |
| Unknown       | 1         | 0.66%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 95        | 59.75%  |
| AMD                        | 28        | 17.61%  |
| Nvidia                     | 22        | 13.84%  |
| Matrox Electronics Systems | 9         | 5.66%   |
| ASPEED Technology          | 3         | 1.89%   |
| Tseng Labs                 | 1         | 0.63%   |
| Silicon Motion             | 1         | 0.63%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 7.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 4.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 4.94%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 4.32%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 7         | 4.32%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 3.7%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6         | 3.7%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 3.09%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 3.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 2.47%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 2.47%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 3         | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.85%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 3         | 1.85%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 3         | 1.85%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 1.23%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2         | 1.23%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 1.23%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2         | 1.23%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 1.23%   |
| Matrox Electronics Systems G200eR2                                                       | 2         | 1.23%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.23%   |
| Intel HD Graphics 620                                                                    | 2         | 1.23%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.23%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.23%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2         | 1.23%   |
| Tseng Labs ET4000/W32p rev C                                                             | 1         | 0.62%   |
| Silicon Motion SM712 LynxEM+                                                             | 1         | 0.62%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.62%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.62%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.62%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1         | 0.62%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.62%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 0.62%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 0.62%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.62%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.62%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.62%   |
| Nvidia GK107M [GeForce GTX 660M Mac Edition]                                             | 1         | 0.62%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 1         | 0.62%   |
| Nvidia GF100GL [Quadro 4000]                                                             | 1         | 0.62%   |
| Nvidia G92 [GeForce GT 330]                                                              | 1         | 0.62%   |
| Nvidia G73 [GeForce 7600 GS]                                                             | 1         | 0.62%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 0.62%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 1         | 0.62%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.62%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.62%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 0.62%   |
| Intel Iris Plus Graphics 650                                                             | 1         | 0.62%   |
| Intel HD Graphics P530                                                                   | 1         | 0.62%   |
| Intel HD Graphics 615                                                                    | 1         | 0.62%   |
| Intel HD Graphics 610                                                                    | 1         | 0.62%   |
| Intel HD Graphics 530                                                                    | 1         | 0.62%   |
| Intel HD Graphics 510                                                                    | 1         | 0.62%   |
| Intel HD Graphics 500                                                                    | 1         | 0.62%   |
| Intel HD Graphics                                                                        | 1         | 0.62%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 1         | 0.62%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 1         | 0.62%   |
| Intel CoffeeLake-S GT2 [UHD Graphics P630]                                               | 1         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 81        | 52.94%  |
| 1 x AMD            | 24        | 15.69%  |
| 1 x Nvidia         | 15        | 9.8%    |
| 1 x Matrox         | 9         | 5.88%   |
| Intel + Nvidia     | 7         | 4.58%   |
| Other              | 4         | 2.61%   |
| Intel + AMD        | 4         | 2.61%   |
| 2 x Intel          | 3         | 1.96%   |
| 1 x ASPEED         | 3         | 1.96%   |
| 2 x AMD            | 1         | 0.65%   |
| 1 x Tseng Labs     | 1         | 0.65%   |
| 1 x Silicon Motion | 1         | 0.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 139       | 91.45%  |
| Proprietary | 8         | 5.26%   |
| Unknown     | 5         | 3.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 139       | 91.45%  |
| 1.01-2.0   | 7         | 4.61%   |
| 7.01-8.0   | 2         | 1.32%   |
| 0.51-1.0   | 2         | 1.32%   |
| 3.01-4.0   | 1         | 0.66%   |
| 0.01-0.5   | 1         | 0.66%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| LG Display          | 5         | 11.9%   |
| AU Optronics        | 5         | 11.9%   |
| Samsung Electronics | 4         | 9.52%   |
| Dell                | 4         | 9.52%   |
| Hewlett-Packard     | 3         | 7.14%   |
| Acer                | 3         | 7.14%   |
| ViewSonic           | 2         | 4.76%   |
| Sharp               | 2         | 4.76%   |
| Philips             | 2         | 4.76%   |
| Chimei Innolux      | 2         | 4.76%   |
| AOC                 | 2         | 4.76%   |
| ___                 | 1         | 2.38%   |
| Toshiba             | 1         | 2.38%   |
| Panasonic           | 1         | 2.38%   |
| Lenovo              | 1         | 2.38%   |
| Goldstar            | 1         | 2.38%   |
| BOE                 | 1         | 2.38%   |
| BenQ                | 1         | 2.38%   |
| Apple               | 1         | 2.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| ___ MY TV LED TV ___0101 1920x1080                                   | 1         | 2.33%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 700x390mm 31.5-inch            | 1         | 2.33%   |
| ViewSonic VA2026w VSC5020 1680x1050 430x270mm 20.0-inch              | 1         | 2.33%   |
| Toshiba TV TSB010E 1920x1080 1040x590mm 47.1-inch                    | 1         | 2.33%   |
| Sharp LQ133T1JX03 SHP140F 2560x1440 290x170mm 13.2-inch              | 1         | 2.33%   |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 210x140mm 9.9-inch               | 1         | 2.33%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch | 1         | 2.33%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch    | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SDC4445 1366x768 340x190mm 15.3-inch | 1         | 2.33%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch              | 1         | 2.33%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch              | 1         | 2.33%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch         | 1         | 2.33%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 1         | 2.33%   |
| LG Display LCD Monitor LGD04A9 1920x1080 310x170mm 13.9-inch         | 1         | 2.33%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x170mm 13.9-inch         | 1         | 2.33%   |
| LG Display LCD Monitor LGD046D 1920x1080 310x170mm 13.9-inch         | 1         | 2.33%   |
| LG Display LCD Monitor LGD01DD 1600x900 380x210mm 17.1-inch          | 1         | 2.33%   |
| Lenovo LCD Monitor LEN40C1 1280x720 220x130mm 10.1-inch              | 1         | 2.33%   |
| Hewlett-Packard W2072a HWP299F 1600x900 440x250mm 19.9-inch          | 1         | 2.33%   |
| Hewlett-Packard LCD Monitor HWP2915 1920x1080 510x290mm 23.1-inch    | 1         | 2.33%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 470x300mm 22.0-inch         | 1         | 2.33%   |
| Goldstar LG HDR WQHD GSM7716 3840x1600 880x370mm 37.6-inch           | 1         | 2.33%   |
| Dell U2212HM DELD048 1920x1080 480x270mm 21.7-inch                   | 1         | 2.33%   |
| Dell SP2309W DELD01C 2048x1152 510x290mm 23.1-inch                   | 1         | 2.33%   |
| Dell P2414H DELA09B 1920x1080 530x300mm 24.0-inch                    | 1         | 2.33%   |
| Dell E248WFP DELA02D 1920x1200 520x320mm 24.0-inch                   | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch      | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 1         | 2.33%   |
| BOE LCD Monitor BOE05F0 1366x768 310x170mm 13.9-inch                 | 1         | 2.33%   |
| BenQ GW2255 BNQ78CD 1920x1080 480x270mm 21.7-inch                    | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch       | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 260x140mm 11.6-inch       | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 310x170mm 13.9-inch       | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO103D 1920x1080 310x170mm 13.9-inch       | 1         | 2.33%   |
| Apple iMac APPB005 2560x1440 600x340mm 27.2-inch                     | 1         | 2.33%   |
| AOC 2963 AOC2963 2560x1080 670x280mm 28.6-inch                       | 1         | 2.33%   |
| AOC 2236 AOC2236 1920x1080 480x270mm 21.7-inch                       | 1         | 2.33%   |
| Acer V233H ACR0090 1920x1080 510x290mm 23.1-inch                     | 1         | 2.33%   |
| Acer KA220HQ ACR0467 1920x1080 480x270mm 21.7-inch                   | 1         | 2.33%   |
| Acer K272HL ACR0523 1920x1080 600x340mm 27.2-inch                    | 1         | 2.33%   |
| Acer B276HL ACR0332 1920x1080 600x340mm 27.2-inch                    | 1         | 2.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 21        | 50%     |
| 1366x768 (WXGA)    | 6         | 14.29%  |
| 2560x1440 (QHD)    | 4         | 9.52%   |
| 1680x1050 (WSXGA+) | 2         | 4.76%   |
| 1600x900 (HD+)     | 2         | 4.76%   |
| 3840x1600          | 1         | 2.38%   |
| 2880x1620          | 1         | 2.38%   |
| 2560x1080          | 1         | 2.38%   |
| 2048x1152          | 1         | 2.38%   |
| 1920x1200 (WUXGA)  | 1         | 2.38%   |
| 1800x1200          | 1         | 2.38%   |
| 1280x720 (HD)      | 1         | 2.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 8         | 19.05%  |
| 27      | 4         | 9.52%   |
| 24      | 4         | 9.52%   |
| 21      | 4         | 9.52%   |
| 15      | 4         | 9.52%   |
| 23      | 3         | 7.14%   |
| 12      | 2         | 4.76%   |
| 11      | 2         | 4.76%   |
| 47      | 1         | 2.38%   |
| 37      | 1         | 2.38%   |
| 31      | 1         | 2.38%   |
| 28      | 1         | 2.38%   |
| 22      | 1         | 2.38%   |
| 20      | 1         | 2.38%   |
| 19      | 1         | 2.38%   |
| 17      | 1         | 2.38%   |
| 10      | 1         | 2.38%   |
| 9       | 1         | 2.38%   |
| Unknown | 1         | 2.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 11        | 26.19%  |
| 301-350     | 11        | 26.19%  |
| 401-500     | 7         | 16.67%  |
| 201-300     | 7         | 16.67%  |
| 601-700     | 2         | 4.76%   |
| 801-900     | 1         | 2.38%   |
| 351-400     | 1         | 2.38%   |
| 1001-1500   | 1         | 2.38%   |
| Unknown     | 1         | 2.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 35        | 85.37%  |
| 16/10 | 3         | 7.32%   |
| 21/9  | 2         | 4.88%   |
| 3/2   | 1         | 2.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 11        | 26.19%  |
| 81-90          | 7         | 16.67%  |
| 301-350        | 4         | 9.52%   |
| 91-100         | 3         | 7.14%   |
| 61-70          | 2         | 4.76%   |
| 51-60          | 2         | 4.76%   |
| 41-50          | 2         | 4.76%   |
| 251-300        | 2         | 4.76%   |
| 151-200        | 2         | 4.76%   |
| 501-1000       | 2         | 4.76%   |
| 71-80          | 1         | 2.38%   |
| 351-500        | 1         | 2.38%   |
| 121-130        | 1         | 2.38%   |
| 101-110        | 1         | 2.38%   |
| Unknown        | 1         | 2.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 15        | 36.59%  |
| 121-160 | 10        | 24.39%  |
| 101-120 | 9         | 21.95%  |
| 161-240 | 5         | 12.2%   |
| 1-50    | 1         | 2.44%   |
| Unknown | 1         | 2.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 110       | 72.37%  |
| 1     | 40        | 26.32%  |
| 2     | 2         | 1.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 103       | 50.49%  |
| Realtek Semiconductor             | 53        | 25.98%  |
| Broadcom                          | 25        | 12.25%  |
| Qualcomm Atheros                  | 9         | 4.41%   |
| U-Blox                            | 2         | 0.98%   |
| Ericsson Business Mobile Networks | 2         | 0.98%   |
| TP-Link                           | 1         | 0.49%   |
| Sierra Wireless                   | 1         | 0.49%   |
| Seeed Technology                  | 1         | 0.49%   |
| Ralink                            | 1         | 0.49%   |
| Nvidia                            | 1         | 0.49%   |
| Microsoft                         | 1         | 0.49%   |
| Marvell Technology Group          | 1         | 0.49%   |
| IMC Networks                      | 1         | 0.49%   |
| Emulex                            | 1         | 0.49%   |
| D-Link System                     | 1         | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 46        | 17.76%  |
| Intel I211 Gigabit Network Connection                                         | 18        | 6.95%   |
| Intel I210 Gigabit Network Connection                                         | 12        | 4.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 9         | 3.47%   |
| Intel 82574L Gigabit Network Connection                                       | 7         | 2.7%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 7         | 2.7%    |
| Intel Wireless 8260                                                           | 6         | 2.32%   |
| Intel Ethernet Connection I217-LM                                             | 6         | 2.32%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 1.93%   |
| Intel Wireless 7260                                                           | 5         | 1.93%   |
| Intel 82576 Gigabit Network Connection                                        | 5         | 1.93%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 5         | 1.93%   |
| Intel 82580 Gigabit Network Connection                                        | 4         | 1.54%   |
| Intel Wireless 7265                                                           | 3         | 1.16%   |
| Intel I350 Gigabit Network Connection                                         | 3         | 1.16%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3         | 1.16%   |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 1.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 3         | 1.16%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3         | 1.16%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 3         | 1.16%   |
| U-Blox [u-blox 7]                                                             | 2         | 0.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2         | 0.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2         | 0.77%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 2         | 0.77%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 2         | 0.77%   |
| Intel Ethernet Controller I225-V                                              | 2         | 0.77%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 0.77%   |
| Intel Ethernet Connection I217-V                                              | 2         | 0.77%   |
| Intel Ethernet Connection (7) I219-V                                          | 2         | 0.77%   |
| Intel Ethernet Connection (6) I219-V                                          | 2         | 0.77%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2         | 0.77%   |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 0.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 2         | 0.77%   |
| Intel Centrino Wireless-N 2230                                                | 2         | 0.77%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2         | 0.77%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module            | 2         | 0.77%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2         | 0.77%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 2         | 0.77%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 0.77%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1         | 0.39%   |
| Sierra Wireless EM7455                                                        | 1         | 0.39%   |
| Seeed Seeeduino_Cortex_M0+                                                    | 1         | 0.39%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 0.39%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 0.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.39%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1         | 0.39%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.39%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1         | 0.39%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.39%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 0.39%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1         | 0.39%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                   | 1         | 0.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 0.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 0.39%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 0.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 0.39%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 0.39%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1         | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 37        | 58.73%  |
| Qualcomm Atheros      | 8         | 12.7%   |
| Realtek Semiconductor | 7         | 11.11%  |
| Broadcom              | 7         | 11.11%  |
| TP-Link               | 1         | 1.59%   |
| Sierra Wireless       | 1         | 1.59%   |
| Ralink                | 1         | 1.59%   |
| IMC Networks          | 1         | 1.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 6         | 9.38%   |
| Intel Wireless 8265 / 8275                                     | 5         | 7.81%   |
| Intel Wireless 7260                                            | 5         | 7.81%   |
| Intel Wireless 7265                                            | 3         | 4.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 4.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 3.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 3.13%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 3.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 3.13%   |
| Intel Centrino Wireless-N 2230                                 | 2         | 3.13%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 2         | 3.13%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 3.13%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1         | 1.56%   |
| Sierra Wireless EM7455                                         | 1         | 1.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 1.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.56%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 1.56%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.56%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1         | 1.56%   |
| Ralink RT5392 PCIe Wireless Network Adapter                    | 1         | 1.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.56%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 1.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.56%   |
| Intel Wireless 3165                                            | 1         | 1.56%   |
| Intel WiFi Link 5100                                           | 1         | 1.56%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 1.56%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.56%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 1.56%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.56%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card           | 1         | 1.56%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 1         | 1.56%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 1         | 1.56%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1         | 1.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 90        | 52.63%  |
| Realtek Semiconductor    | 50        | 29.24%  |
| Broadcom                 | 22        | 12.87%  |
| Qualcomm Atheros         | 4         | 2.34%   |
| Nvidia                   | 1         | 0.58%   |
| Microsoft                | 1         | 0.58%   |
| Marvell Technology Group | 1         | 0.58%   |
| Emulex                   | 1         | 0.58%   |
| D-Link System            | 1         | 0.58%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 46        | 24.34%  |
| Intel I211 Gigabit Network Connection                                         | 18        | 9.52%   |
| Intel I210 Gigabit Network Connection                                         | 12        | 6.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 9         | 4.76%   |
| Intel 82574L Gigabit Network Connection                                       | 7         | 3.7%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 7         | 3.7%    |
| Intel Ethernet Connection I217-LM                                             | 6         | 3.17%   |
| Intel 82576 Gigabit Network Connection                                        | 5         | 2.65%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 5         | 2.65%   |
| Intel 82580 Gigabit Network Connection                                        | 4         | 2.12%   |
| Intel I350 Gigabit Network Connection                                         | 3         | 1.59%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3         | 1.59%   |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 1.59%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3         | 1.59%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 3         | 1.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 2         | 1.06%   |
| Intel Ethernet Controller I225-V                                              | 2         | 1.06%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 1.06%   |
| Intel Ethernet Connection I217-V                                              | 2         | 1.06%   |
| Intel Ethernet Connection (7) I219-V                                          | 2         | 1.06%   |
| Intel Ethernet Connection (6) I219-V                                          | 2         | 1.06%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 1.06%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2         | 1.06%   |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 1.06%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2         | 1.06%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2         | 1.06%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.53%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.53%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 0.53%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1         | 0.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1         | 0.53%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.53%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                            | 1         | 0.53%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 0.53%   |
| Intel Ethernet Controller X550                                                | 1         | 0.53%   |
| Intel Ethernet Connection X722 for 1GbE                                       | 1         | 0.53%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 1         | 0.53%   |
| Intel Ethernet Connection I354                                                | 1         | 0.53%   |
| Intel Ethernet Connection I219-V                                              | 1         | 0.53%   |
| Intel Ethernet Connection I218-V                                              | 1         | 0.53%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.53%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 0.53%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 0.53%   |
| Intel Ethernet Connection (11) I219-V                                         | 1         | 0.53%   |
| Intel Ethernet 10G 2P X520 Adapter                                            | 1         | 0.53%   |
| Intel 82576NS Gigabit Network Connection                                      | 1         | 0.53%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1         | 0.53%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1         | 0.53%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1         | 0.53%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1         | 0.53%   |
| Emulex OneConnect 10Gb NIC (be3)                                              | 1         | 0.53%   |
| D-Link System DGE-530T Gigabit Ethernet Adapter (rev 11)                      | 1         | 0.53%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 0.53%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                             | 1         | 0.53%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1         | 0.53%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1         | 0.53%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                       | 1         | 0.53%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 143       | 68.42%  |
| WiFi     | 60        | 28.71%  |
| Modem    | 5         | 2.39%   |
| Unknown  | 1         | 0.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 136       | 78.61%  |
| WiFi     | 36        | 20.81%  |
| Modem    | 1         | 0.58%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 64        | 42.11%  |
| 1     | 29        | 19.08%  |
| 4     | 21        | 13.82%  |
| 3     | 15        | 9.87%   |
| 6     | 10        | 6.58%   |
| 5     | 7         | 4.61%   |
| 7     | 3         | 1.97%   |
| 9     | 2         | 1.32%   |
| 0     | 1         | 0.66%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 135       | 87.1%   |
| Yes  | 20        | 12.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 60.98%  |
| Apple                           | 6         | 14.63%  |
| Broadcom                        | 3         | 7.32%   |
| Realtek Semiconductor           | 2         | 4.88%   |
| Qualcomm Atheros Communications | 2         | 4.88%   |
| Cambridge Silicon Radio         | 2         | 4.88%   |
| Foxconn / Hon Hai               | 1         | 2.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 15        | 36.59%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 12.2%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 4.88%   |
| Intel AX201 Bluetooth                               | 2         | 4.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 4.88%   |
| Apple Bluetooth Host Controller                     | 2         | 4.88%   |
| Apple Apple Broadcom Built-in Bluetooth             | 2         | 4.88%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 2.44%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.44%   |
| Qualcomm Atheros  QCA61x4 Bluetooth 4.1             | 1         | 2.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.44%   |
| Intel AX200 Bluetooth                               | 1         | 2.44%   |
| Foxconn / Hon Hai Bluetooth USB Module              | 1         | 2.44%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.44%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.44%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 2.44%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 2.44%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 97        | 69.29%  |
| AMD                         | 24        | 17.14%  |
| Nvidia                      | 16        | 11.43%  |
| Texas Instruments           | 1         | 0.71%   |
| Logitech                    | 1         | 0.71%   |
| FiiO Electronics Technology | 1         | 0.71%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 6.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 6.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 5.75%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 5.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 5.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 5.17%   |
| AMD FCH Azalia Controller                                                                         | 9         | 5.17%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 4.02%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 7         | 4.02%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 3.45%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 2.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 2.87%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 2.3%    |
| Intel 8 Series HD Audio Controller                                                                | 4         | 2.3%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 2.3%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.72%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 1.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.72%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 1.72%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 1.72%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2         | 1.15%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 1.15%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.15%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.15%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.15%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 1.15%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.15%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 1.15%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.15%   |
| Texas Instruments SMSL Q5 AMP                                                                     | 1         | 0.57%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.57%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.57%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.57%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.57%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.57%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.57%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.57%   |
| Nvidia GF100 High Definition Audio Controller                                                     | 1         | 0.57%   |
| Logitech Headset H390                                                                             | 1         | 0.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.57%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.57%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1         | 0.57%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1         | 0.57%   |
| FiiO Electronics Technology K3                                                                    | 1         | 0.57%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 0.57%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 0.57%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 1         | 0.57%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                                             | 1         | 0.57%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 0.57%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 1         | 0.57%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 1         | 0.57%   |
| Unknown                                                                                           | 1         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 42        | 25.61%  |
| Kingston            | 22        | 13.41%  |
| Micron Technology   | 19        | 11.59%  |
| SK Hynix            | 18        | 10.98%  |
| Unknown             | 14        | 8.54%   |
| Corsair             | 11        | 6.71%   |
| Crucial             | 9         | 5.49%   |
| G.Skill             | 4         | 2.44%   |
| Transcend           | 3         | 1.83%   |
| Unknown             | 3         | 1.83%   |
| TIMETEC             | 2         | 1.22%   |
| Team                | 2         | 1.22%   |
| Ramaxel Technology  | 2         | 1.22%   |
| Elpida              | 2         | 1.22%   |
| Unknown (ABCD)      | 1         | 0.61%   |
| Smart Modular       | 1         | 0.61%   |
| PNY                 | 1         | 0.61%   |
| Patriot             | 1         | 0.61%   |
| Nanya Technology    | 1         | 0.61%   |
| Kingmax             | 1         | 0.61%   |
| Innodisk            | 1         | 0.61%   |
| Hewlett-Packard     | 1         | 0.61%   |
| GeIL                | 1         | 0.61%   |
| Apacer              | 1         | 0.61%   |
| A-DATA Technology   | 1         | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 5         | 2.89%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 3         | 1.73%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s            | 3         | 1.73%   |
| Unknown                                                        | 3         | 1.73%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 2         | 1.16%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 2         | 1.16%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                | 2         | 1.16%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 2         | 1.16%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 1.16%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 1.16%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s          | 2         | 1.16%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 2         | 1.16%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 2         | 1.16%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 2         | 1.16%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s              | 2         | 1.16%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s           | 2         | 1.16%   |
| Corsair RAM CMSX64GX4M2A2666C18 32GB SODIMM DDR4 2667MT/s      | 2         | 1.16%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s        | 2         | 1.16%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.58%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1         | 0.58%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 1         | 0.58%   |
| Unknown RAM Module 8GB 1600MT/s                                | 1         | 0.58%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                 | 1         | 0.58%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                   | 1         | 0.58%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 1         | 0.58%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 1         | 0.58%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1         | 0.58%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 1         | 0.58%   |
| Unknown RAM Module 1GB DIMM DDR 59392MT/s                      | 1         | 0.58%   |
| Unknown RAM Module 1GB DIMM 800MT/s                            | 1         | 0.58%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1         | 0.58%   |
| Transcend RAM TS512MLH72V1H 4GB DIMM DDR4 2133MT/s             | 1         | 0.58%   |
| Transcend RAM TS256MSK64W6X 2GB DIMM DDR3 1066MT/s             | 1         | 0.58%   |
| Transcend RAM Module 2GB DIMM DDR3 1333MT/s                    | 1         | 0.58%   |
| TIMETEC RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                  | 1         | 0.58%   |
| TIMETEC RAM SD3-1600 8GB DIMM DDR3 1600MT/s                    | 1         | 0.58%   |
| Team RAM Vulcan-1600 8GB DIMM DDR3 1600MT/s                    | 1         | 0.58%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s             | 1         | 0.58%   |
| Smart Modular RAM Module 2GB DIMM DDR3 1066MT/s                | 1         | 0.58%   |
| SK Hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                | 1         | 0.58%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1067MT/s                   | 1         | 0.58%   |
| SK Hynix RAM Module 2GB DIMM DDR3 1600MT/s                     | 1         | 0.58%   |
| SK Hynix RAM Module 2GB DDR3 1600MT/s                          | 1         | 0.58%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 1         | 0.58%   |
| SK Hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s           | 1         | 0.58%   |
| SK Hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s           | 1         | 0.58%   |
| SK Hynix RAM HMA82GR7DJR8N-XN 16GB DIMM DDR4 3200MT/s          | 1         | 0.58%   |
| SK Hynix RAM HMA81GU7DJR8N-VK 8GB DIMM DDR4 2666MT/s           | 1         | 0.58%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 0.58%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s         | 1         | 0.58%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.58%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                    | 1         | 0.58%   |
| Samsung RAM Module 2GB SODIMM 667MT/s                          | 1         | 0.58%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s          | 1         | 0.58%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s          | 1         | 0.58%   |
| Samsung RAM M471B5174BM0-YH9 4GB Chip DDR3 1333MT/s            | 1         | 0.58%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 0.58%   |
| Samsung RAM M471B5173BH0-CK0 4GB DDR3 1333MT/s                 | 1         | 0.58%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 0.58%   |
| Samsung RAM M471B1G73DH0-YK0 8GB DIMM DDR3 1600MT/s            | 1         | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 84        | 60.43%  |
| DDR4    | 40        | 28.78%  |
| Unknown | 8         | 5.76%   |
| LPDDR3  | 4         | 2.88%   |
| LPDDR4  | 1         | 0.72%   |
| DDR2    | 1         | 0.72%   |
| DDR     | 1         | 0.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 70        | 50%     |
| SODIMM       | 58        | 41.43%  |
| Unknown      | 5         | 3.57%   |
| Chip         | 4         | 2.86%   |
| Row Of Chips | 2         | 1.43%   |
| RIMM         | 1         | 0.71%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 58        | 38.93%  |
| 4096  | 54        | 36.24%  |
| 2048  | 18        | 12.08%  |
| 16384 | 13        | 8.72%   |
| 32768 | 4         | 2.68%   |
| 1024  | 2         | 1.34%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 57        | 39.31%  |
| 1333  | 26        | 17.93%  |
| 2400  | 16        | 11.03%  |
| 2667  | 14        | 9.66%   |
| 2133  | 10        | 6.9%    |
| 1867  | 7         | 4.83%   |
| 1066  | 5         | 3.45%   |
| 800   | 4         | 2.76%   |
| 2666  | 2         | 1.38%   |
| 59392 | 1         | 0.69%   |
| 3200  | 1         | 0.69%   |
| 1067  | 1         | 0.69%   |
| 667   | 1         | 0.69%   |

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

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 9         | 39.13%  |
| Apple                         | 3         | 13.04%  |
| Acer                          | 3         | 13.04%  |
| Sunplus Innovation Technology | 2         | 8.7%    |
| IMC Networks                  | 2         | 8.7%    |
| Z-Star Microelectronics       | 1         | 4.35%   |
| Suyin                         | 1         | 4.35%   |
| Microdia                      | 1         | 4.35%   |
| Luxvisions Innotech Limited   | 1         | 4.35%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 5         | 20.83%  |
| Apple FaceTime HD Camera (Built-in)                 | 3         | 12.5%   |
| Acer Integrated Camera                              | 2         | 8.33%   |
| Z-Star WebCam SC-03FFL11739P                        | 1         | 4.17%   |
| Suyin Lenovo Integrated Webcam                      | 1         | 4.17%   |
| Sunplus Laptop Integrated Webcam HD                 | 1         | 4.17%   |
| Sunplus HD WebCam                                   | 1         | 4.17%   |
| Microdia Integrated_Webcam_HD                       | 1         | 4.17%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 4.17%   |
| IMC Networks Integrated Webcam                      | 1         | 4.17%   |
| IMC Networks EasyCamera                             | 1         | 4.17%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 4.17%   |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 4.17%   |
| Chicony TOSHIBA Web Camera - 3M                     | 1         | 4.17%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 1         | 4.17%   |
| Chicony Lenovo Integrated Camera                    | 1         | 4.17%   |
| Acer Lenovo EasyCamera                              | 1         | 4.17%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 7         | 87.5%   |
| Upek             | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 3         | 37.5%   |
| Validity Sensors Synaptics WBDI                        | 3         | 37.5%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 12.5%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 12.5%   |

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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 65        | 42.48%  |
| 0     | 49        | 32.03%  |
| 2     | 19        | 12.42%  |
| 3     | 15        | 9.8%    |
| 5     | 2         | 1.31%   |
| 4     | 2         | 1.31%   |
| 6     | 1         | 0.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 90        | 58.06%  |
| Bluetooth                | 17        | 10.97%  |
| Net/wireless             | 13        | 8.39%   |
| Card reader              | 13        | 8.39%   |
| Firewire controller      | 6         | 3.87%   |
| Fingerprint reader       | 6         | 3.87%   |
| Sound                    | 3         | 1.94%   |
| Network                  | 2         | 1.29%   |
| Net/ethernet             | 2         | 1.29%   |
| Graphics card            | 2         | 1.29%   |
| Dvb card                 | 1         | 0.65%   |
