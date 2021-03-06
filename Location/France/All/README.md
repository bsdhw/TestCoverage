BSD in France - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for BSD in France.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/France/Desktop/README.md) and [notebooks](/Location/France/Notebook/README.md).

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

Total: 452

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Dell          | Inspiron 5515               | Notebook    | [dca437b993](https://bsd-hardware.info/?probe=dca437b993) | Jul 01, 2022 |
| ASUSTek       | K53TA                       | Notebook    | [6ce39c5e61](https://bsd-hardware.info/?probe=6ce39c5e61) | Jun 27, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ab2f42b567](https://bsd-hardware.info/?probe=ab2f42b567) | Jun 26, 2022 |
| Dell          | 0M877N A02                  | Server      | [c6f1ccfe6d](https://bsd-hardware.info/?probe=c6f1ccfe6d) | Jun 22, 2022 |
| Intel         | D945GCLF2 AAE46416-104      | Desktop     | [84f2afeff4](https://bsd-hardware.info/?probe=84f2afeff4) | Jun 21, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [25d5a77b59](https://bsd-hardware.info/?probe=25d5a77b59) | Jun 17, 2022 |
| HP            | 86E9 A                      | Desktop     | [1d1ac2dd90](https://bsd-hardware.info/?probe=1d1ac2dd90) | Jun 16, 2022 |
| Alienware     | M18xR2                      | Notebook    | [6d55881f6a](https://bsd-hardware.info/?probe=6d55881f6a) | Jun 15, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [8ba77d7208](https://bsd-hardware.info/?probe=8ba77d7208) | Jun 13, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [4be2393c8d](https://bsd-hardware.info/?probe=4be2393c8d) | Jun 11, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [4e0a906acb](https://bsd-hardware.info/?probe=4e0a906acb) | Jun 11, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | Desktop     | [776a4892d0](https://bsd-hardware.info/?probe=776a4892d0) | Jun 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [56111732fd](https://bsd-hardware.info/?probe=56111732fd) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [aeec87e07f](https://bsd-hardware.info/?probe=aeec87e07f) | Jun 06, 2022 |
| Dell          | Latitude 7490               | Notebook    | [18215740d1](https://bsd-hardware.info/?probe=18215740d1) | Jun 05, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [f3ad761457](https://bsd-hardware.info/?probe=f3ad761457) | Jun 04, 2022 |
| Dell          | Latitude 7490               | Notebook    | [22224f46f4](https://bsd-hardware.info/?probe=22224f46f4) | Jun 02, 2022 |
| Acer          | Aspire E5-576               | Notebook    | [138e9fdeb4](https://bsd-hardware.info/?probe=138e9fdeb4) | May 31, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | Desktop     | [9bacfc2b0e](https://bsd-hardware.info/?probe=9bacfc2b0e) | May 29, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [20814a930a](https://bsd-hardware.info/?probe=20814a930a) | May 18, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [115de395dd](https://bsd-hardware.info/?probe=115de395dd) | May 17, 2022 |
| TUXEDO        | InfinityBook13V3            | Notebook    | [fd081a3636](https://bsd-hardware.info/?probe=fd081a3636) | May 17, 2022 |
| Intel         | DH67BL AAG10189-213         | Desktop     | [e8d2744812](https://bsd-hardware.info/?probe=e8d2744812) | May 12, 2022 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | Notebook    | [0419c52079](https://bsd-hardware.info/?probe=0419c52079) | May 11, 2022 |
| ASRock        | A320M Pro4-F                | Desktop     | [f307756ddf](https://bsd-hardware.info/?probe=f307756ddf) | May 11, 2022 |
| Intel         | H81U                        | Notebook    | [550699602e](https://bsd-hardware.info/?probe=550699602e) | May 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [6cf944b0ef](https://bsd-hardware.info/?probe=6cf944b0ef) | May 10, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [cf58c679ef](https://bsd-hardware.info/?probe=cf58c679ef) | May 08, 2022 |
| Intel         | H81U                        | Notebook    | [04646d1cc7](https://bsd-hardware.info/?probe=04646d1cc7) | May 05, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [5f9e266167](https://bsd-hardware.info/?probe=5f9e266167) | May 04, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [7d4dd8ba29](https://bsd-hardware.info/?probe=7d4dd8ba29) | May 04, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [3481513b0f](https://bsd-hardware.info/?probe=3481513b0f) | May 03, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0d5b872ec1](https://bsd-hardware.info/?probe=0d5b872ec1) | May 02, 2022 |
| Dell          | Latitude 7490               | Notebook    | [03c97fe4d9](https://bsd-hardware.info/?probe=03c97fe4d9) | May 02, 2022 |
| Dell          | Precision 7730              | Notebook    | [bdb3e3d4ce](https://bsd-hardware.info/?probe=bdb3e3d4ce) | Apr 30, 2022 |
| Dell          | Latitude 7490               | Notebook    | [1586880dd7](https://bsd-hardware.info/?probe=1586880dd7) | Apr 30, 2022 |
| Intel         | NUC6CAYB J23203-405         | Mini pc     | [86ade7ce4b](https://bsd-hardware.info/?probe=86ade7ce4b) | Apr 30, 2022 |
| ASUSTek       | AM1I-A                      | Desktop     | [8fce57c9e4](https://bsd-hardware.info/?probe=8fce57c9e4) | Apr 25, 2022 |
| ASUSTek       | P5KR                        | Desktop     | [cf745ca0da](https://bsd-hardware.info/?probe=cf745ca0da) | Apr 23, 2022 |
| Dell          | Studio 1555                 | Notebook    | [6da8f97bcd](https://bsd-hardware.info/?probe=6da8f97bcd) | Apr 22, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [875d6b2da3](https://bsd-hardware.info/?probe=875d6b2da3) | Apr 22, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [a278852381](https://bsd-hardware.info/?probe=a278852381) | Apr 21, 2022 |
| Dell          | 06JWJY A01                  | Desktop     | [16f4cc5d53](https://bsd-hardware.info/?probe=16f4cc5d53) | Apr 20, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [ab8aea2f5c](https://bsd-hardware.info/?probe=ab8aea2f5c) | Apr 17, 2022 |
| Dell          | Latitude E5450              | Notebook    | [ca5eb083f9](https://bsd-hardware.info/?probe=ca5eb083f9) | Apr 16, 2022 |
| Deciso        | Netboard A10                | Desktop     | [6e0b916230](https://bsd-hardware.info/?probe=6e0b916230) | Apr 16, 2022 |
| HP            | 86E9 A                      | Desktop     | [be43a8efde](https://bsd-hardware.info/?probe=be43a8efde) | Apr 14, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [4b981630d7](https://bsd-hardware.info/?probe=4b981630d7) | Apr 13, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [06720f3c57](https://bsd-hardware.info/?probe=06720f3c57) | Apr 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [e6ba291c2d](https://bsd-hardware.info/?probe=e6ba291c2d) | Apr 12, 2022 |
| Jetway        | 1.0                         | Desktop     | [ac2ab09363](https://bsd-hardware.info/?probe=ac2ab09363) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e208e9425](https://bsd-hardware.info/?probe=4e208e9425) | Apr 10, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [ded0d1a114](https://bsd-hardware.info/?probe=ded0d1a114) | Apr 09, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [14a6449380](https://bsd-hardware.info/?probe=14a6449380) | Apr 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [50833ab257](https://bsd-hardware.info/?probe=50833ab257) | Apr 07, 2022 |
| Sophos        | XG                          | Firewall    | [c98fff0cf2](https://bsd-hardware.info/?probe=c98fff0cf2) | Apr 06, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [e44ebcb340](https://bsd-hardware.info/?probe=e44ebcb340) | Apr 06, 2022 |
| Deciso        | Netboard A20                | Notebook    | [0829d5a85d](https://bsd-hardware.info/?probe=0829d5a85d) | Apr 06, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [35dcbd74e9](https://bsd-hardware.info/?probe=35dcbd74e9) | Apr 05, 2022 |
| ASRock        | H110M-ITX                   | Desktop     | [946c8fd467](https://bsd-hardware.info/?probe=946c8fd467) | Apr 04, 2022 |
| PC Engines    | APU2                        | Desktop     | [5eb2e04d11](https://bsd-hardware.info/?probe=5eb2e04d11) | Apr 02, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [43cbc2ef2c](https://bsd-hardware.info/?probe=43cbc2ef2c) | Apr 02, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [c83fab9193](https://bsd-hardware.info/?probe=c83fab9193) | Apr 01, 2022 |
| Unknown       | Unknown                     | Firewall    | [b5c3949db8](https://bsd-hardware.info/?probe=b5c3949db8) | Mar 29, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [7a991e2f31](https://bsd-hardware.info/?probe=7a991e2f31) | Mar 24, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [acb99d63ce](https://bsd-hardware.info/?probe=acb99d63ce) | Mar 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [05a81cb5d5](https://bsd-hardware.info/?probe=05a81cb5d5) | Mar 22, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [483cf54bfc](https://bsd-hardware.info/?probe=483cf54bfc) | Mar 21, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d0946bc53f](https://bsd-hardware.info/?probe=d0946bc53f) | Mar 21, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d2ecb6259c](https://bsd-hardware.info/?probe=d2ecb6259c) | Mar 20, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [40cd6d1472](https://bsd-hardware.info/?probe=40cd6d1472) | Mar 19, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [a4a1c8e5ca](https://bsd-hardware.info/?probe=a4a1c8e5ca) | Mar 18, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [b23ab09f52](https://bsd-hardware.info/?probe=b23ab09f52) | Mar 18, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [545e5ebfc9](https://bsd-hardware.info/?probe=545e5ebfc9) | Mar 18, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [b137b25594](https://bsd-hardware.info/?probe=b137b25594) | Mar 15, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [b652261bda](https://bsd-hardware.info/?probe=b652261bda) | Mar 14, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [0a2a94839d](https://bsd-hardware.info/?probe=0a2a94839d) | Mar 13, 2022 |
| HP            | EliteBook 2530p             | Notebook    | [e5c8017afb](https://bsd-hardware.info/?probe=e5c8017afb) | Mar 12, 2022 |
| Supermicro    | X11SDV-8C-TLN2F             | Server      | [e1fceaabc0](https://bsd-hardware.info/?probe=e1fceaabc0) | Mar 08, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [3b77055bd4](https://bsd-hardware.info/?probe=3b77055bd4) | Mar 07, 2022 |
| CNCTION-IA... | Unknown                     | Desktop     | [0051c86e4c](https://bsd-hardware.info/?probe=0051c86e4c) | Mar 07, 2022 |
| AAEON         | UP-CHT01 V0.4               | Desktop     | [9aaa7c7a32](https://bsd-hardware.info/?probe=9aaa7c7a32) | Mar 05, 2022 |
| Protectli     | VP2410                      | Desktop     | [1f650fc994](https://bsd-hardware.info/?probe=1f650fc994) | Mar 05, 2022 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [d73d3760ce](https://bsd-hardware.info/?probe=d73d3760ce) | Mar 04, 2022 |
| HP            | ProLiant DL360 G7           | Server      | [a3611d42bc](https://bsd-hardware.info/?probe=a3611d42bc) | Mar 04, 2022 |
| PC Engines    | apu1                        | Desktop     | [177dc1fbc8](https://bsd-hardware.info/?probe=177dc1fbc8) | Mar 03, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [43bfceb19d](https://bsd-hardware.info/?probe=43bfceb19d) | Mar 02, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [4367711bff](https://bsd-hardware.info/?probe=4367711bff) | Mar 01, 2022 |
| Dell          | Latitude E5440              | Notebook    | [b0314f9200](https://bsd-hardware.info/?probe=b0314f9200) | Feb 26, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [7b19f71ce1](https://bsd-hardware.info/?probe=7b19f71ce1) | Feb 26, 2022 |
| PC Engines    | apu1                        | Desktop     | [d904aa7790](https://bsd-hardware.info/?probe=d904aa7790) | Feb 24, 2022 |
| Intel         | CARLOW                      | Desktop     | [d46b68cc28](https://bsd-hardware.info/?probe=d46b68cc28) | Feb 23, 2022 |
| HP            | 8169                        | Desktop     | [f449b4cd6c](https://bsd-hardware.info/?probe=f449b4cd6c) | Feb 23, 2022 |
| Dell          | 0W13NR A07                  | Server      | [22846d44fb](https://bsd-hardware.info/?probe=22846d44fb) | Feb 22, 2022 |
| Dell          | 0TY019 A00                  | Server      | [5f750e021e](https://bsd-hardware.info/?probe=5f750e021e) | Feb 20, 2022 |
| Intel         | CARLOW                      | Desktop     | [b64bf97293](https://bsd-hardware.info/?probe=b64bf97293) | Feb 19, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [ef5cc6be72](https://bsd-hardware.info/?probe=ef5cc6be72) | Feb 17, 2022 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [18576ef86c](https://bsd-hardware.info/?probe=18576ef86c) | Feb 17, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [fbc24f90e5](https://bsd-hardware.info/?probe=fbc24f90e5) | Feb 17, 2022 |
| MSI           | MS-7253                     | Desktop     | [c4e971ea82](https://bsd-hardware.info/?probe=c4e971ea82) | Feb 16, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [df529a84b9](https://bsd-hardware.info/?probe=df529a84b9) | Feb 16, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [1a13b7bfd1](https://bsd-hardware.info/?probe=1a13b7bfd1) | Feb 16, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [1e8904f4fc](https://bsd-hardware.info/?probe=1e8904f4fc) | Feb 15, 2022 |
| AMD           | X64                         | Desktop     | [e5a9ff1138](https://bsd-hardware.info/?probe=e5a9ff1138) | Feb 15, 2022 |
| HP            | EliteBook 2530p             | Notebook    | [dd52bb1163](https://bsd-hardware.info/?probe=dd52bb1163) | Feb 15, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [ee3a7740ec](https://bsd-hardware.info/?probe=ee3a7740ec) | Feb 13, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [b77b926f9b](https://bsd-hardware.info/?probe=b77b926f9b) | Feb 13, 2022 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [09a6920a4f](https://bsd-hardware.info/?probe=09a6920a4f) | Feb 12, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [61c103f80d](https://bsd-hardware.info/?probe=61c103f80d) | Feb 11, 2022 |
| Deciso        | Netboard A20                | Notebook    | [4d8f19ba12](https://bsd-hardware.info/?probe=4d8f19ba12) | Feb 11, 2022 |
| Sophos        | XG                          | Firewall    | [31a8174933](https://bsd-hardware.info/?probe=31a8174933) | Feb 10, 2022 |
| Sophos        | XG                          | Firewall    | [365e4cfbea](https://bsd-hardware.info/?probe=365e4cfbea) | Feb 08, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [8342bcccf5](https://bsd-hardware.info/?probe=8342bcccf5) | Feb 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [91b1ec3b93](https://bsd-hardware.info/?probe=91b1ec3b93) | Feb 06, 2022 |
| Deciso        | Netboard A20                | Notebook    | [a6b7d2d5e8](https://bsd-hardware.info/?probe=a6b7d2d5e8) | Feb 06, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [2accc42e21](https://bsd-hardware.info/?probe=2accc42e21) | Feb 06, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [9213769810](https://bsd-hardware.info/?probe=9213769810) | Feb 05, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [c0d2abfe5c](https://bsd-hardware.info/?probe=c0d2abfe5c) | Feb 05, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [00cabbe0bf](https://bsd-hardware.info/?probe=00cabbe0bf) | Feb 05, 2022 |
| Dell          | 0W13NR A07                  | Server      | [1582d0700a](https://bsd-hardware.info/?probe=1582d0700a) | Feb 03, 2022 |
| Deciso        | Netboard A20                | Notebook    | [8cd43fcfd1](https://bsd-hardware.info/?probe=8cd43fcfd1) | Feb 03, 2022 |
| Intel         | SKYBAY                      | Desktop     | [95c3231a3a](https://bsd-hardware.info/?probe=95c3231a3a) | Feb 03, 2022 |
| MSI           | MS-9A45 0A                  | Desktop     | [cfbfdf0e55](https://bsd-hardware.info/?probe=cfbfdf0e55) | Jan 31, 2022 |
| ASUSTek       | 1015PEM                     | Notebook    | [efea0efb2b](https://bsd-hardware.info/?probe=efea0efb2b) | Jan 31, 2022 |
| Intel         | NUC8BEB J72688-306          | Mini pc     | [ccda2302cf](https://bsd-hardware.info/?probe=ccda2302cf) | Jan 30, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [9dc53740a9](https://bsd-hardware.info/?probe=9dc53740a9) | Jan 29, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [e89404ebed](https://bsd-hardware.info/?probe=e89404ebed) | Jan 29, 2022 |
| AMD           | Larne CRB                   | Desktop     | [c6a85da1d5](https://bsd-hardware.info/?probe=c6a85da1d5) | Jan 28, 2022 |
| Dell          | 0PC5F7 A03                  | Desktop     | [7a5d842d33](https://bsd-hardware.info/?probe=7a5d842d33) | Jan 27, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f1c7ee0712](https://bsd-hardware.info/?probe=f1c7ee0712) | Jan 26, 2022 |
| ASRock        | H110M-ITX                   | Desktop     | [5c58d01f2d](https://bsd-hardware.info/?probe=5c58d01f2d) | Jan 25, 2022 |
| RUNING        | B75M INTEL H3V              | Desktop     | [9a060df0a2](https://bsd-hardware.info/?probe=9a060df0a2) | Jan 23, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [cd745d6377](https://bsd-hardware.info/?probe=cd745d6377) | Jan 23, 2022 |
| AMD           | Larne CRB                   | Desktop     | [6c37b91111](https://bsd-hardware.info/?probe=6c37b91111) | Jan 22, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [b01e6eb706](https://bsd-hardware.info/?probe=b01e6eb706) | Jan 22, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [384d2f888b](https://bsd-hardware.info/?probe=384d2f888b) | Jan 18, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [8449bd20c1](https://bsd-hardware.info/?probe=8449bd20c1) | Jan 18, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [3dead218e1](https://bsd-hardware.info/?probe=3dead218e1) | Jan 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [6baaab27fd](https://bsd-hardware.info/?probe=6baaab27fd) | Jan 15, 2022 |
| MSI           | MS-98C8                     | Desktop     | [0102557f05](https://bsd-hardware.info/?probe=0102557f05) | Jan 15, 2022 |
| PC Engines    | APU2                        | Desktop     | [7062b84459](https://bsd-hardware.info/?probe=7062b84459) | Jan 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [1ff4a66d03](https://bsd-hardware.info/?probe=1ff4a66d03) | Jan 12, 2022 |
| HP            | EliteBook 2530p             | Notebook    | [42eb986a58](https://bsd-hardware.info/?probe=42eb986a58) | Jan 11, 2022 |
| Dell          | Latitude E5450              | Notebook    | [a05fbe1c26](https://bsd-hardware.info/?probe=a05fbe1c26) | Jan 05, 2022 |
| Dell          | Latitude E5450              | Notebook    | [c2ef231757](https://bsd-hardware.info/?probe=c2ef231757) | Jan 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [6aeb9adadb](https://bsd-hardware.info/?probe=6aeb9adadb) | Dec 31, 2021 |
| Dell          | 0V52N7 A00                  | Server      | [b6139f57b9](https://bsd-hardware.info/?probe=b6139f57b9) | Dec 30, 2021 |
| ASUSTek       | S550CA                      | Notebook    | [1263a5fb37](https://bsd-hardware.info/?probe=1263a5fb37) | Dec 29, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [8c3181ee8d](https://bsd-hardware.info/?probe=8c3181ee8d) | Dec 29, 2021 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [07221fc111](https://bsd-hardware.info/?probe=07221fc111) | Dec 28, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [cdb5578df8](https://bsd-hardware.info/?probe=cdb5578df8) | Dec 27, 2021 |
| Gigabyte      | X58A-UD5                    | Desktop     | [62b94dd372](https://bsd-hardware.info/?probe=62b94dd372) | Dec 21, 2021 |
| Samsung       | R720                        | Notebook    | [620195d4aa](https://bsd-hardware.info/?probe=620195d4aa) | Dec 20, 2021 |
| HP            | Compaq 15                   | Notebook    | [1e8b1ce39b](https://bsd-hardware.info/?probe=1e8b1ce39b) | Dec 20, 2021 |
| Supermicro    | X11SSL-F                    | Server      | [a5a440a7a7](https://bsd-hardware.info/?probe=a5a440a7a7) | Dec 20, 2021 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [124ac672b0](https://bsd-hardware.info/?probe=124ac672b0) | Dec 20, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [350def9eca](https://bsd-hardware.info/?probe=350def9eca) | Dec 19, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [4147a5824d](https://bsd-hardware.info/?probe=4147a5824d) | Dec 16, 2021 |
| HP            | ProBook 650 G5              | Notebook    | [d4ffc24c6f](https://bsd-hardware.info/?probe=d4ffc24c6f) | Dec 15, 2021 |
| Unknown       | Unknown                     | Desktop     | [225298bcd6](https://bsd-hardware.info/?probe=225298bcd6) | Dec 12, 2021 |
| HPE           | ProLiant MicroServer Gen... | Server      | [26220d3f14](https://bsd-hardware.info/?probe=26220d3f14) | Dec 09, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [eb69e83fbf](https://bsd-hardware.info/?probe=eb69e83fbf) | Dec 09, 2021 |
| RUNING        | B75M INTEL H3V              | Desktop     | [61312aa506](https://bsd-hardware.info/?probe=61312aa506) | Nov 30, 2021 |
| Dell          | VEP-4600-V930 034R2CA03     | Desktop     | [313d1b7032](https://bsd-hardware.info/?probe=313d1b7032) | Nov 25, 2021 |
| Gigabyte      | MZBSWBP-00                  | Desktop     | [9e7a72d920](https://bsd-hardware.info/?probe=9e7a72d920) | Nov 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [16206960c4](https://bsd-hardware.info/?probe=16206960c4) | Nov 24, 2021 |
| HP            | 3031h                       | Desktop     | [056352a663](https://bsd-hardware.info/?probe=056352a663) | Nov 21, 2021 |
| RUNING        | B75M INTEL H3V              | Desktop     | [5cfcc8c5f8](https://bsd-hardware.info/?probe=5cfcc8c5f8) | Nov 13, 2021 |
| HP            | 3031h                       | Desktop     | [d63bbcfceb](https://bsd-hardware.info/?probe=d63bbcfceb) | Oct 31, 2021 |
| HP            | 3031h                       | Desktop     | [c5e39a5e6d](https://bsd-hardware.info/?probe=c5e39a5e6d) | Oct 31, 2021 |
| MSI           | MS-9A45 0A                  | Desktop     | [e2db09bacb](https://bsd-hardware.info/?probe=e2db09bacb) | Oct 30, 2021 |
| ASRockRack    | C3558D4I-4L                 | Desktop     | [dfba84ce5a](https://bsd-hardware.info/?probe=dfba84ce5a) | Oct 29, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [e2167afc3b](https://bsd-hardware.info/?probe=e2167afc3b) | Oct 25, 2021 |
| BESSTAR Te... | VB9                         | All in one  | [ac1f5a3339](https://bsd-hardware.info/?probe=ac1f5a3339) | Oct 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [3f5b148e23](https://bsd-hardware.info/?probe=3f5b148e23) | Oct 22, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [6f019f05b6](https://bsd-hardware.info/?probe=6f019f05b6) | Oct 20, 2021 |
| PC Engines    | APU2                        | Desktop     | [4b8fb7992f](https://bsd-hardware.info/?probe=4b8fb7992f) | Oct 16, 2021 |
| Dell          | 0V52N7 A00                  | Server      | [c5226ff226](https://bsd-hardware.info/?probe=c5226ff226) | Oct 13, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [e53866a5d9](https://bsd-hardware.info/?probe=e53866a5d9) | Oct 11, 2021 |
| ASUSTek       | P9X79                       | Desktop     | [be9d90602d](https://bsd-hardware.info/?probe=be9d90602d) | Oct 11, 2021 |
| Dell          | 04JN2K A04                  | Server      | [f529f87cea](https://bsd-hardware.info/?probe=f529f87cea) | Oct 11, 2021 |
| Dell          | 0V52N7 A00                  | Server      | [4ad37c1848](https://bsd-hardware.info/?probe=4ad37c1848) | Oct 10, 2021 |
| Google        | Terra                       | Notebook    | [9ba239a4a3](https://bsd-hardware.info/?probe=9ba239a4a3) | Oct 10, 2021 |
| Unknown       | Unknown                     | Desktop     | [2fd62acb45](https://bsd-hardware.info/?probe=2fd62acb45) | Oct 10, 2021 |
| Lenovo        | 3138                        | Desktop     | [8b5cf892d0](https://bsd-hardware.info/?probe=8b5cf892d0) | Oct 04, 2021 |
| Lenovo        | ThinkPad X220 4290W42       | Notebook    | [8be5183e21](https://bsd-hardware.info/?probe=8be5183e21) | Sep 25, 2021 |
| Lenovo        | ThinkPad T500 2056Y2Z       | Notebook    | [88b86ecf8b](https://bsd-hardware.info/?probe=88b86ecf8b) | Sep 25, 2021 |
| ASUSTek       | F2A85-M                     | Desktop     | [5b7623f03b](https://bsd-hardware.info/?probe=5b7623f03b) | Sep 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [1b8ce81945](https://bsd-hardware.info/?probe=1b8ce81945) | Sep 19, 2021 |
| MSI           | P65 Creator 8RE             | Notebook    | [2684b5021c](https://bsd-hardware.info/?probe=2684b5021c) | Sep 18, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [8611fbfd97](https://bsd-hardware.info/?probe=8611fbfd97) | Sep 14, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [5f78c3411f](https://bsd-hardware.info/?probe=5f78c3411f) | Sep 13, 2021 |
| ASRock        | B460M Pro4                  | Desktop     | [cfc7818691](https://bsd-hardware.info/?probe=cfc7818691) | Sep 10, 2021 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [d5750a95a4](https://bsd-hardware.info/?probe=d5750a95a4) | Sep 08, 2021 |
| Packard Be... | imedia S2110A               | Desktop     | [d62a38660c](https://bsd-hardware.info/?probe=d62a38660c) | Sep 08, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [29cfd33c5e](https://bsd-hardware.info/?probe=29cfd33c5e) | Sep 06, 2021 |
| ASUSTek       | P8B-X series                | Server      | [1e7d58cd40](https://bsd-hardware.info/?probe=1e7d58cd40) | Aug 29, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [d028fc63d4](https://bsd-hardware.info/?probe=d028fc63d4) | Aug 29, 2021 |
| ASRockRack    | X470D4U                     | Desktop     | [827c50f77b](https://bsd-hardware.info/?probe=827c50f77b) | Aug 28, 2021 |
| Dell          | 0G3HR7 A00                  | Desktop     | [7f75f30b75](https://bsd-hardware.info/?probe=7f75f30b75) | Aug 27, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [76f004bd26](https://bsd-hardware.info/?probe=76f004bd26) | Aug 26, 2021 |
| PC Engines    | APU2                        | Desktop     | [0a35da2af7](https://bsd-hardware.info/?probe=0a35da2af7) | Aug 24, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [3e088c942b](https://bsd-hardware.info/?probe=3e088c942b) | Aug 22, 2021 |
| Fujitsu       | LIFEBOOK NH570              | Notebook    | [51b5325c85](https://bsd-hardware.info/?probe=51b5325c85) | Aug 13, 2021 |
| Unknown       | Unknown                     | Desktop     | [1dd499d54c](https://bsd-hardware.info/?probe=1dd499d54c) | Aug 12, 2021 |
| Dell          | 0XCR8D A03                  | Desktop     | [11526a150b](https://bsd-hardware.info/?probe=11526a150b) | Aug 10, 2021 |
| Shuttle       | FS61                        | Desktop     | [b1fbaa8a6b](https://bsd-hardware.info/?probe=b1fbaa8a6b) | Aug 09, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [bb65c30be3](https://bsd-hardware.info/?probe=bb65c30be3) | Aug 07, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [9e0c8e8024](https://bsd-hardware.info/?probe=9e0c8e8024) | Aug 07, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [5f9c53366b](https://bsd-hardware.info/?probe=5f9c53366b) | Aug 05, 2021 |
| Unknown       | YL-SKUL6-7 Series           | Desktop     | [b9ef180b73](https://bsd-hardware.info/?probe=b9ef180b73) | Aug 04, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [3ff984316b](https://bsd-hardware.info/?probe=3ff984316b) | Aug 04, 2021 |
| Dell          | 0G261D A00                  | Desktop     | [2ce00e9f6b](https://bsd-hardware.info/?probe=2ce00e9f6b) | Aug 02, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [2a1251b320](https://bsd-hardware.info/?probe=2a1251b320) | Aug 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [34d448e1d1](https://bsd-hardware.info/?probe=34d448e1d1) | Jul 30, 2021 |
| Unknown       | Unknown                     | Desktop     | [846b6cca20](https://bsd-hardware.info/?probe=846b6cca20) | Jul 30, 2021 |
| Unknown       | Unknown                     | Desktop     | [8aaf18daa1](https://bsd-hardware.info/?probe=8aaf18daa1) | Jul 28, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [d15eff8bcc](https://bsd-hardware.info/?probe=d15eff8bcc) | Jul 21, 2021 |
| ASRock        | D1800B-ITX                  | Desktop     | [4831cc5183](https://bsd-hardware.info/?probe=4831cc5183) | Jul 21, 2021 |
| BESSTAR Te... | GB1B                        | Mini pc     | [2484df8d38](https://bsd-hardware.info/?probe=2484df8d38) | Jul 18, 2021 |
| Lenovo        | ThinkPad T420 42368A3       | Notebook    | [0a3b5c9c27](https://bsd-hardware.info/?probe=0a3b5c9c27) | Jul 12, 2021 |
| HP            | 2B4B                        | Desktop     | [456625c82f](https://bsd-hardware.info/?probe=456625c82f) | Jul 04, 2021 |
| Notebook      | W510LU                      | Notebook    | [3d6de69bda](https://bsd-hardware.info/?probe=3d6de69bda) | Jul 02, 2021 |
| Dell          | 0XR1GT A00                  | Desktop     | [1e66c42238](https://bsd-hardware.info/?probe=1e66c42238) | Jul 02, 2021 |
| Shuttle       | NC10U                       | Desktop     | [5d2d20dd04](https://bsd-hardware.info/?probe=5d2d20dd04) | Jul 02, 2021 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [bde8057846](https://bsd-hardware.info/?probe=bde8057846) | Jun 29, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [6e96d4c26f](https://bsd-hardware.info/?probe=6e96d4c26f) | Jun 28, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [7ae63d4c6c](https://bsd-hardware.info/?probe=7ae63d4c6c) | Jun 27, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [661d3349cb](https://bsd-hardware.info/?probe=661d3349cb) | Jun 26, 2021 |
| Dell          | Vostro 5481                 | Notebook    | [bb318fbc50](https://bsd-hardware.info/?probe=bb318fbc50) | Jun 26, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [95b0c9a6a3](https://bsd-hardware.info/?probe=95b0c9a6a3) | Jun 25, 2021 |
| Lenovo        | ThinkPad T450s 20BWS0L60... | Notebook    | [6ea6f6ffe7](https://bsd-hardware.info/?probe=6ea6f6ffe7) | Jun 20, 2021 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [8f336c0fa3](https://bsd-hardware.info/?probe=8f336c0fa3) | Jun 19, 2021 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [dc619f203f](https://bsd-hardware.info/?probe=dc619f203f) | Jun 19, 2021 |
| ASRock        | H110M-ITX                   | Desktop     | [124c75ba7c](https://bsd-hardware.info/?probe=124c75ba7c) | Jun 17, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [007ce2b6ce](https://bsd-hardware.info/?probe=007ce2b6ce) | Jun 17, 2021 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | Desktop     | [e6cbfc417b](https://bsd-hardware.info/?probe=e6cbfc417b) | Jun 10, 2021 |
| Supermicro    | X10SLH-N6-ST031             | Desktop     | [e54175f99f](https://bsd-hardware.info/?probe=e54175f99f) | Jun 06, 2021 |
| Lenovo        | ThinkPad X250 20CLS7WY04    | Notebook    | [b60f4a19ee](https://bsd-hardware.info/?probe=b60f4a19ee) | Jun 06, 2021 |
| Dell          | 0TY019 A01                  | Server      | [411477e260](https://bsd-hardware.info/?probe=411477e260) | Jun 04, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [24f3dbd372](https://bsd-hardware.info/?probe=24f3dbd372) | Jun 04, 2021 |
| Shuttle       | FS35V5                      | Mini pc     | [bfd71efa3b](https://bsd-hardware.info/?probe=bfd71efa3b) | May 31, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [cec18015ba](https://bsd-hardware.info/?probe=cec18015ba) | May 30, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [193936b5ca](https://bsd-hardware.info/?probe=193936b5ca) | May 30, 2021 |
| Lenovo        | ThinkPad T450s 20BWS0L60... | Notebook    | [ac567bd12d](https://bsd-hardware.info/?probe=ac567bd12d) | May 28, 2021 |
| Lenovo        | ThinkPad A485 20MVS0FD00    | Notebook    | [2f1ba02130](https://bsd-hardware.info/?probe=2f1ba02130) | May 28, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [16f36a045f](https://bsd-hardware.info/?probe=16f36a045f) | May 26, 2021 |
| Acer          | Aspire E5-571P              | Notebook    | [7c8c842fa7](https://bsd-hardware.info/?probe=7c8c842fa7) | May 24, 2021 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | Desktop     | [3e650be93d](https://bsd-hardware.info/?probe=3e650be93d) | May 24, 2021 |
| ASUSTek       | AM1I-A                      | Desktop     | [aafc52d6a1](https://bsd-hardware.info/?probe=aafc52d6a1) | May 24, 2021 |
| Google        | Guado                       | Desktop     | [54f01f821d](https://bsd-hardware.info/?probe=54f01f821d) | May 21, 2021 |
| MSI           | Z77A-G41                    | Desktop     | [c471a8f2fe](https://bsd-hardware.info/?probe=c471a8f2fe) | May 16, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [3468faf656](https://bsd-hardware.info/?probe=3468faf656) | May 07, 2021 |
| ASRockRack    | X470D4U                     | Desktop     | [421da89770](https://bsd-hardware.info/?probe=421da89770) | May 06, 2021 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [87e5651fd1](https://bsd-hardware.info/?probe=87e5651fd1) | May 06, 2021 |
| PC Engines    | APU2                        | Desktop     | [c99a0b0e4d](https://bsd-hardware.info/?probe=c99a0b0e4d) | May 05, 2021 |
| MSI           | MS-9A45 0A                  | Desktop     | [e930fac60b](https://bsd-hardware.info/?probe=e930fac60b) | May 05, 2021 |
| Supermicro    | X8STi                       | Desktop     | [c615ef1edf](https://bsd-hardware.info/?probe=c615ef1edf) | May 04, 2021 |
| ASUSTek       | Rampage II GENE             | Desktop     | [4eac97c85c](https://bsd-hardware.info/?probe=4eac97c85c) | May 04, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [7c642e5e7d](https://bsd-hardware.info/?probe=7c642e5e7d) | Apr 30, 2021 |
| HPE           | ProLiant MicroServer Gen... | Server      | [105c13acca](https://bsd-hardware.info/?probe=105c13acca) | Apr 29, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [2e2e69cb9e](https://bsd-hardware.info/?probe=2e2e69cb9e) | Apr 29, 2021 |
| Unknown       | Unknown                     | Desktop     | [4368de8d34](https://bsd-hardware.info/?probe=4368de8d34) | Apr 28, 2021 |
| PC Engines    | APU3                        | Desktop     | [1d6ca07c5a](https://bsd-hardware.info/?probe=1d6ca07c5a) | Apr 27, 2021 |
| PC Engines    | APU3                        | Desktop     | [8fc426b107](https://bsd-hardware.info/?probe=8fc426b107) | Apr 22, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [e262812b4d](https://bsd-hardware.info/?probe=e262812b4d) | Apr 21, 2021 |
| Lenovo        | ThinkPad T430 23495P8       | Notebook    | [2c985c22ef](https://bsd-hardware.info/?probe=2c985c22ef) | Apr 10, 2021 |
| Lenovo        | ThinkPad T420 4236NUG       | Notebook    | [4ff3fa22ff](https://bsd-hardware.info/?probe=4ff3fa22ff) | Apr 07, 2021 |
| Unknown       | J3160-4L                    | Desktop     | [354dc80671](https://bsd-hardware.info/?probe=354dc80671) | Apr 07, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [7901474a09](https://bsd-hardware.info/?probe=7901474a09) | Apr 07, 2021 |
| PC Engines    | apu4                        | Desktop     | [160a01d9e1](https://bsd-hardware.info/?probe=160a01d9e1) | Apr 03, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [f3b6d4d5c4](https://bsd-hardware.info/?probe=f3b6d4d5c4) | Apr 03, 2021 |
| ASUSTek       | P8B-X series                | Server      | [f60388bf6a](https://bsd-hardware.info/?probe=f60388bf6a) | Apr 03, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [7031b0ed1e](https://bsd-hardware.info/?probe=7031b0ed1e) | Mar 31, 2021 |
| PC Engines    | APU2                        | Desktop     | [97554df75d](https://bsd-hardware.info/?probe=97554df75d) | Mar 30, 2021 |
| Lenovo        | ThinkPad X220 4290EE8       | Notebook    | [f46976d85d](https://bsd-hardware.info/?probe=f46976d85d) | Mar 29, 2021 |
| Lenovo        | ThinkPad T490 20N20009FR    | Notebook    | [e1f691ac78](https://bsd-hardware.info/?probe=e1f691ac78) | Mar 29, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [dec8aa97f5](https://bsd-hardware.info/?probe=dec8aa97f5) | Mar 26, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [83ed58b4d0](https://bsd-hardware.info/?probe=83ed58b4d0) | Mar 26, 2021 |
| HPE           | ProLiant MicroServer Gen... | Server      | [e789c55f2e](https://bsd-hardware.info/?probe=e789c55f2e) | Mar 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3cb0e979f8](https://bsd-hardware.info/?probe=3cb0e979f8) | Mar 26, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [0263b0e32e](https://bsd-hardware.info/?probe=0263b0e32e) | Mar 26, 2021 |
| Lenovo        | 3138                        | Desktop     | [f12dd68efb](https://bsd-hardware.info/?probe=f12dd68efb) | Mar 25, 2021 |
| Dell          | 0KRC95 A02                  | Desktop     | [68354c00cf](https://bsd-hardware.info/?probe=68354c00cf) | Mar 25, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [1499695aae](https://bsd-hardware.info/?probe=1499695aae) | Mar 25, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [650cd9b653](https://bsd-hardware.info/?probe=650cd9b653) | Mar 24, 2021 |
| Dell          | 0D28YY A00                  | Desktop     | [bef38bd379](https://bsd-hardware.info/?probe=bef38bd379) | Mar 23, 2021 |
| MSI           | MS-N033                     | Notebook    | [650f6a1b70](https://bsd-hardware.info/?probe=650f6a1b70) | Mar 21, 2021 |
| Dell          | Inspiron 7566               | Notebook    | [183ac9b791](https://bsd-hardware.info/?probe=183ac9b791) | Mar 17, 2021 |
| Dell          | Inspiron 7566               | Notebook    | [b4a35aa7b0](https://bsd-hardware.info/?probe=b4a35aa7b0) | Mar 17, 2021 |
| ASRock        | Z490M Pro4                  | Desktop     | [c0df245c1b](https://bsd-hardware.info/?probe=c0df245c1b) | Mar 13, 2021 |
| SECO          | UDOO x86                    | Notebook    | [f8310915b6](https://bsd-hardware.info/?probe=f8310915b6) | Mar 13, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [565343b334](https://bsd-hardware.info/?probe=565343b334) | Mar 13, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [24b657e7ba](https://bsd-hardware.info/?probe=24b657e7ba) | Mar 12, 2021 |
| Dell          | 05XKKK A05                  | Server      | [d3fe07511a](https://bsd-hardware.info/?probe=d3fe07511a) | Mar 12, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [bbcc01d2ce](https://bsd-hardware.info/?probe=bbcc01d2ce) | Mar 11, 2021 |
| MSI           | B360M BAZOOKA               | Desktop     | [17a763a917](https://bsd-hardware.info/?probe=17a763a917) | Mar 11, 2021 |
| ASUSTek       | AM1I-A                      | Desktop     | [835842d361](https://bsd-hardware.info/?probe=835842d361) | Mar 10, 2021 |
| Lenovo        | ThinkPad T400 6475P1G       | Notebook    | [6a0907b5e8](https://bsd-hardware.info/?probe=6a0907b5e8) | Mar 06, 2021 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [17ed006376](https://bsd-hardware.info/?probe=17ed006376) | Mar 05, 2021 |
| ASRock        | Z490M Pro4                  | Desktop     | [348d592fab](https://bsd-hardware.info/?probe=348d592fab) | Mar 05, 2021 |
| Dell          | 03CDJK A01                  | All in one  | [9468eeef92](https://bsd-hardware.info/?probe=9468eeef92) | Mar 04, 2021 |
| Dell          | 03CDJK A01                  | All in one  | [fc655524ab](https://bsd-hardware.info/?probe=fc655524ab) | Mar 04, 2021 |
| VeryPC        | S400                        | Desktop     | [77b744169b](https://bsd-hardware.info/?probe=77b744169b) | Mar 04, 2021 |
| VeryPC        | S400                        | Desktop     | [edcea11cb7](https://bsd-hardware.info/?probe=edcea11cb7) | Mar 04, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [de98cd5952](https://bsd-hardware.info/?probe=de98cd5952) | Mar 04, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [03c5808adf](https://bsd-hardware.info/?probe=03c5808adf) | Mar 04, 2021 |
| Dell          | Latitude 5280               | Notebook    | [b84364959d](https://bsd-hardware.info/?probe=b84364959d) | Mar 04, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [1f226262cc](https://bsd-hardware.info/?probe=1f226262cc) | Mar 04, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [e056f1c77c](https://bsd-hardware.info/?probe=e056f1c77c) | Mar 03, 2021 |
| HP            | 86E9 A                      | Desktop     | [215398b88f](https://bsd-hardware.info/?probe=215398b88f) | Feb 28, 2021 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [9bdf9ecec8](https://bsd-hardware.info/?probe=9bdf9ecec8) | Feb 25, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [7def696a61](https://bsd-hardware.info/?probe=7def696a61) | Feb 22, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [0dc468c860](https://bsd-hardware.info/?probe=0dc468c860) | Feb 22, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [b1f1b3cd82](https://bsd-hardware.info/?probe=b1f1b3cd82) | Feb 22, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [929bda8001](https://bsd-hardware.info/?probe=929bda8001) | Feb 22, 2021 |
| ASUSTek       | X751LN                      | Notebook    | [fe7d72b06a](https://bsd-hardware.info/?probe=fe7d72b06a) | Feb 21, 2021 |
| ASUSTek       | X751LN                      | Notebook    | [a88cfd7fdd](https://bsd-hardware.info/?probe=a88cfd7fdd) | Feb 21, 2021 |
| Acer          | EG43M                       | Desktop     | [22552918ee](https://bsd-hardware.info/?probe=22552918ee) | Feb 21, 2021 |
| Gigabyte      | P15FR7                      | Notebook    | [c65b4d297a](https://bsd-hardware.info/?probe=c65b4d297a) | Feb 21, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ade306695d](https://bsd-hardware.info/?probe=ade306695d) | Feb 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [71cfece3a7](https://bsd-hardware.info/?probe=71cfece3a7) | Feb 18, 2021 |
| Supermicro    | X9DRT                       | Server      | [a3bcb2fcf1](https://bsd-hardware.info/?probe=a3bcb2fcf1) | Feb 18, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [5fec969088](https://bsd-hardware.info/?probe=5fec969088) | Feb 17, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [42538553ee](https://bsd-hardware.info/?probe=42538553ee) | Feb 17, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [261756a327](https://bsd-hardware.info/?probe=261756a327) | Feb 17, 2021 |
| ASUSTek       | X75VC                       | Notebook    | [4a0982db2b](https://bsd-hardware.info/?probe=4a0982db2b) | Feb 15, 2021 |
| ASRock        | H370M-ITX/ac                | Desktop     | [5d39657098](https://bsd-hardware.info/?probe=5d39657098) | Feb 14, 2021 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [4f646f53e9](https://bsd-hardware.info/?probe=4f646f53e9) | Feb 14, 2021 |
| Lenovo        | ThinkPad T580 20LAS2TG00    | Notebook    | [d5a1c088b3](https://bsd-hardware.info/?probe=d5a1c088b3) | Feb 13, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [ba7f82b343](https://bsd-hardware.info/?probe=ba7f82b343) | Feb 12, 2021 |
| ASUSTek       | E200HA                      | Notebook    | [5781a8b561](https://bsd-hardware.info/?probe=5781a8b561) | Feb 12, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [9b149fcd68](https://bsd-hardware.info/?probe=9b149fcd68) | Feb 12, 2021 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | Desktop     | [5965bc8a1d](https://bsd-hardware.info/?probe=5965bc8a1d) | Feb 11, 2021 |
| PC Engines    | APU                         | Desktop     | [282a9596c6](https://bsd-hardware.info/?probe=282a9596c6) | Feb 11, 2021 |
| Dell          | Latitude 3410               | Notebook    | [465dd01c0d](https://bsd-hardware.info/?probe=465dd01c0d) | Feb 11, 2021 |
| Dell          | 0H28RR A02                  | Server      | [0bbf4a51bb](https://bsd-hardware.info/?probe=0bbf4a51bb) | Feb 10, 2021 |
| Dell          | 0H28RR A02                  | Server      | [eaac725443](https://bsd-hardware.info/?probe=eaac725443) | Feb 10, 2021 |
| Dell          | 030VXY A01                  | Desktop     | [23e7163f58](https://bsd-hardware.info/?probe=23e7163f58) | Feb 10, 2021 |
| Gigabyte      | Z97P-D3                     | Desktop     | [a3bd8f5772](https://bsd-hardware.info/?probe=a3bd8f5772) | Feb 10, 2021 |
| Dell          | Latitude E6230              | Notebook    | [696e95fc08](https://bsd-hardware.info/?probe=696e95fc08) | Feb 10, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [94bcab24a8](https://bsd-hardware.info/?probe=94bcab24a8) | Feb 09, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [b3cf6f9142](https://bsd-hardware.info/?probe=b3cf6f9142) | Feb 09, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [7e5ce355e7](https://bsd-hardware.info/?probe=7e5ce355e7) | Feb 08, 2021 |
| Dell          | Latitude 5280               | Notebook    | [73fca8b178](https://bsd-hardware.info/?probe=73fca8b178) | Feb 08, 2021 |
| PC Engines    | APU3                        | Desktop     | [e21438c3cc](https://bsd-hardware.info/?probe=e21438c3cc) | Feb 07, 2021 |
| Lenovo        | ThinkPad T420 42368A3       | Notebook    | [5d7840d28e](https://bsd-hardware.info/?probe=5d7840d28e) | Feb 07, 2021 |
| Dell          | Latitude 3410               | Notebook    | [f81c1e338f](https://bsd-hardware.info/?probe=f81c1e338f) | Feb 07, 2021 |
| MSI           | Z77A-G41                    | Desktop     | [35bae50659](https://bsd-hardware.info/?probe=35bae50659) | Feb 06, 2021 |
| Unknown       | Unknown                     | Desktop     | [8ef7071a3f](https://bsd-hardware.info/?probe=8ef7071a3f) | Feb 04, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [857c5aade9](https://bsd-hardware.info/?probe=857c5aade9) | Feb 04, 2021 |
| CompuLab      | fitlet2                     | Mini pc     | [7ff0034c98](https://bsd-hardware.info/?probe=7ff0034c98) | Feb 03, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [b005d61a99](https://bsd-hardware.info/?probe=b005d61a99) | Feb 03, 2021 |
| MSI           | MS-9A45 0A                  | Desktop     | [f66ccf2f33](https://bsd-hardware.info/?probe=f66ccf2f33) | Feb 03, 2021 |
| MSI           | MS-9A45 0A                  | Desktop     | [c384535b6f](https://bsd-hardware.info/?probe=c384535b6f) | Feb 02, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [a7494d60a5](https://bsd-hardware.info/?probe=a7494d60a5) | Jan 31, 2021 |
| Dell          | 0JD6X3 A05                  | Server      | [27a3bb8503](https://bsd-hardware.info/?probe=27a3bb8503) | Jan 31, 2021 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | Desktop     | [c8af335c01](https://bsd-hardware.info/?probe=c8af335c01) | Jan 29, 2021 |
| ASUSTek       | M2NPV-MX                    | Desktop     | [dae16641bb](https://bsd-hardware.info/?probe=dae16641bb) | Jan 23, 2021 |
| ASUSTek       | M2NPV-MX                    | Desktop     | [45e53e33d8](https://bsd-hardware.info/?probe=45e53e33d8) | Jan 23, 2021 |
| Unknown       | Unknown                     | Desktop     | [4c4d549584](https://bsd-hardware.info/?probe=4c4d549584) | Jan 22, 2021 |
| ASUSTek       | M2NPV-MX                    | Desktop     | [ae29fe5691](https://bsd-hardware.info/?probe=ae29fe5691) | Jan 22, 2021 |
| ASUSTek       | M2NPV-MX                    | Desktop     | [bdd89d655d](https://bsd-hardware.info/?probe=bdd89d655d) | Jan 22, 2021 |
| ASUSTek       | M2NPV-MX                    | Desktop     | [006cafaa6b](https://bsd-hardware.info/?probe=006cafaa6b) | Jan 22, 2021 |
| ASUSTek       | M2NPV-MX                    | Desktop     | [80edc8dae6](https://bsd-hardware.info/?probe=80edc8dae6) | Jan 22, 2021 |
| PC Engines    | apu4                        | Desktop     | [3507544d2e](https://bsd-hardware.info/?probe=3507544d2e) | Jan 20, 2021 |
| Lenovo        | ThinkPad P50 20EQS0U60C     | Notebook    | [d8cf9e878e](https://bsd-hardware.info/?probe=d8cf9e878e) | Jan 19, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [f6df3820b5](https://bsd-hardware.info/?probe=f6df3820b5) | Jan 18, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [f7c32488e9](https://bsd-hardware.info/?probe=f7c32488e9) | Jan 15, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [06cbb5cd5f](https://bsd-hardware.info/?probe=06cbb5cd5f) | Jan 15, 2021 |
| Dell          | Latitude 5280               | Notebook    | [c9bfb73262](https://bsd-hardware.info/?probe=c9bfb73262) | Jan 15, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [a9228fa7c3](https://bsd-hardware.info/?probe=a9228fa7c3) | Jan 15, 2021 |
| Dell          | 030VXY A01                  | Desktop     | [5af442bf61](https://bsd-hardware.info/?probe=5af442bf61) | Jan 15, 2021 |
| HP            | 3399                        | Desktop     | [b11946a41a](https://bsd-hardware.info/?probe=b11946a41a) | Jan 13, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [8093f75ea2](https://bsd-hardware.info/?probe=8093f75ea2) | Jan 13, 2021 |
| Dell          | Latitude 5400               | Notebook    | [f242897c33](https://bsd-hardware.info/?probe=f242897c33) | Jan 13, 2021 |
| Dell          | Latitude 5490               | Notebook    | [3fba47b07f](https://bsd-hardware.info/?probe=3fba47b07f) | Jan 12, 2021 |
| ASUSTek       | N75SF                       | Notebook    | [7efb6557a2](https://bsd-hardware.info/?probe=7efb6557a2) | Jan 10, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [9ccf63e228](https://bsd-hardware.info/?probe=9ccf63e228) | Jan 09, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [e18df4623a](https://bsd-hardware.info/?probe=e18df4623a) | Jan 09, 2021 |
| Dell          | 03CDJK A01                  | All in one  | [d894ae5d09](https://bsd-hardware.info/?probe=d894ae5d09) | Jan 07, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d54f451ea5](https://bsd-hardware.info/?probe=d54f451ea5) | Jan 07, 2021 |
| HP            | 3032h                       | Desktop     | [13648fd22d](https://bsd-hardware.info/?probe=13648fd22d) | Jan 07, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [ee2d5f3289](https://bsd-hardware.info/?probe=ee2d5f3289) | Jan 07, 2021 |
| Dell          | 030VXY A01                  | Desktop     | [c117ffdc98](https://bsd-hardware.info/?probe=c117ffdc98) | Jan 07, 2021 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | Desktop     | [36ef631bfe](https://bsd-hardware.info/?probe=36ef631bfe) | Jan 05, 2021 |
| Dell          | Latitude 5280               | Notebook    | [1ae6e6ee2d](https://bsd-hardware.info/?probe=1ae6e6ee2d) | Jan 05, 2021 |
| ASUSTek       | X102BA                      | Notebook    | [893b9111c6](https://bsd-hardware.info/?probe=893b9111c6) | Dec 27, 2020 |
| Gigabyte      | X79-UD3                     | Desktop     | [a8baf509d9](https://bsd-hardware.info/?probe=a8baf509d9) | Dec 26, 2020 |
| Apple         | PowerBook5,8                | Notebook    | [96f550a537](https://bsd-hardware.info/?probe=96f550a537) | Dec 24, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d13e0a1749](https://bsd-hardware.info/?probe=d13e0a1749) | Dec 15, 2020 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [2544123f79](https://bsd-hardware.info/?probe=2544123f79) | Dec 06, 2020 |
| Dell          | Latitude 5280               | Notebook    | [d1be72cc7e](https://bsd-hardware.info/?probe=d1be72cc7e) | Nov 21, 2020 |
| Dell          | Latitude 5280               | Notebook    | [fd4e8756b4](https://bsd-hardware.info/?probe=fd4e8756b4) | Nov 21, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [9b6b24708e](https://bsd-hardware.info/?probe=9b6b24708e) | Nov 03, 2020 |
| ASUSTek       | X102BA                      | Notebook    | [9156250b96](https://bsd-hardware.info/?probe=9156250b96) | Oct 31, 2020 |
| Dell          | 03X6X0 A03                  | Server      | [7d7b8ca054](https://bsd-hardware.info/?probe=7d7b8ca054) | Oct 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [7c8972f650](https://bsd-hardware.info/?probe=7c8972f650) | Oct 29, 2020 |
| ASRock        | J3455-ITX                   | Desktop     | [1d5bd18d14](https://bsd-hardware.info/?probe=1d5bd18d14) | Oct 29, 2020 |
| Supermicro    | X8STi                       | Desktop     | [1b64902781](https://bsd-hardware.info/?probe=1b64902781) | Oct 26, 2020 |
| AZW           | Z83 II                      | Desktop     | [9416876f20](https://bsd-hardware.info/?probe=9416876f20) | Oct 24, 2020 |
| AZW           | Z83 II                      | Desktop     | [19b1b4d85d](https://bsd-hardware.info/?probe=19b1b4d85d) | Oct 24, 2020 |
| Intel         | D2500HN                     | Desktop     | [6dbc4dfa33](https://bsd-hardware.info/?probe=6dbc4dfa33) | Oct 21, 2020 |
| PC Engines    | APU2                        | Desktop     | [d1ca549fe7](https://bsd-hardware.info/?probe=d1ca549fe7) | Oct 21, 2020 |
| Lenovo        | ThinkPad X230 2325AJ9       | Notebook    | [176044b6b8](https://bsd-hardware.info/?probe=176044b6b8) | Oct 21, 2020 |
| Lenovo        | ThinkPad S5-S540 20B3001... | Notebook    | [7e6cb69989](https://bsd-hardware.info/?probe=7e6cb69989) | Oct 21, 2020 |
| ZOTAC         | XXXXXX                      | Desktop     | [0f8960bdd3](https://bsd-hardware.info/?probe=0f8960bdd3) | Oct 21, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [1b1327ac93](https://bsd-hardware.info/?probe=1b1327ac93) | Oct 21, 2020 |
| Intel         | D2500HN                     | Desktop     | [4b432dcb3d](https://bsd-hardware.info/?probe=4b432dcb3d) | Oct 20, 2020 |
| PC Engines    | APU2                        | Desktop     | [b95ef9962d](https://bsd-hardware.info/?probe=b95ef9962d) | Oct 20, 2020 |
| PC Engines    | APU2                        | Desktop     | [aecf376503](https://bsd-hardware.info/?probe=aecf376503) | Oct 20, 2020 |
| ASUSTek       | X102BA                      | Notebook    | [47e04c9378](https://bsd-hardware.info/?probe=47e04c9378) | Oct 19, 2020 |
| ASUSTek       | UX305FA                     | Notebook    | [4ecb1e9cd3](https://bsd-hardware.info/?probe=4ecb1e9cd3) | Sep 25, 2020 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [88f2d98930](https://bsd-hardware.info/?probe=88f2d98930) | Sep 12, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [986575086d](https://bsd-hardware.info/?probe=986575086d) | Sep 05, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [152377b2ea](https://bsd-hardware.info/?probe=152377b2ea) | Sep 05, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [f95de56bcd](https://bsd-hardware.info/?probe=f95de56bcd) | Sep 03, 2020 |
| Intel         | DH61AG AAG23736-505         | Desktop     | [3f99489a19](https://bsd-hardware.info/?probe=3f99489a19) | Aug 19, 2020 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [42de38c478](https://bsd-hardware.info/?probe=42de38c478) | Aug 19, 2020 |
| Intel         | DN2800MT AAG81515-900       | Desktop     | [bcfec367a9](https://bsd-hardware.info/?probe=bcfec367a9) | Aug 14, 2020 |
| TUXEDO        | InfinityBook13V3            | Notebook    | [d508fb472b](https://bsd-hardware.info/?probe=d508fb472b) | Aug 10, 2020 |
| Gigabyte      | P35-DS3R                    | Desktop     | [4ed0c89a67](https://bsd-hardware.info/?probe=4ed0c89a67) | Aug 07, 2020 |
| Dell          | 081N4V A07                  | Server      | [2d835336d9](https://bsd-hardware.info/?probe=2d835336d9) | Aug 07, 2020 |
| Dell          | 081N4V A07                  | Server      | [14a20876f4](https://bsd-hardware.info/?probe=14a20876f4) | Aug 07, 2020 |
| HP            | ProLiant DL120 G7           | Server      | [f873647eb9](https://bsd-hardware.info/?probe=f873647eb9) | Aug 07, 2020 |
| ASUSTek       | Z170-P D3                   | Desktop     | [7b8885caf3](https://bsd-hardware.info/?probe=7b8885caf3) | Aug 07, 2020 |
| ASUSTek       | Z170-P D3                   | Desktop     | [2e9821f90f](https://bsd-hardware.info/?probe=2e9821f90f) | Aug 07, 2020 |
| Gigabyte      | EP45-DS4                    | Desktop     | [a56a9c50fc](https://bsd-hardware.info/?probe=a56a9c50fc) | Aug 07, 2020 |
| Sony          | VGN-AR630E                  | Notebook    | [b417df513f](https://bsd-hardware.info/?probe=b417df513f) | Aug 07, 2020 |
| Gigabyte      | P35-DS3R                    | Desktop     | [0b111b137c](https://bsd-hardware.info/?probe=0b111b137c) | Aug 07, 2020 |
| MSI           | P65 Creator 8RE             | Notebook    | [4031d186c2](https://bsd-hardware.info/?probe=4031d186c2) | Aug 06, 2020 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [82de136ad3](https://bsd-hardware.info/?probe=82de136ad3) | Aug 06, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [f3e2acbb66](https://bsd-hardware.info/?probe=f3e2acbb66) | Jul 31, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [7ae8c247e9](https://bsd-hardware.info/?probe=7ae8c247e9) | Jul 31, 2020 |
| Intel         | DH61AGL G71256-202          | Desktop     | [666757a826](https://bsd-hardware.info/?probe=666757a826) | Jun 14, 2020 |
| PC Engines    | APU2                        | Desktop     | [dc1c86095f](https://bsd-hardware.info/?probe=dc1c86095f) | Jun 14, 2020 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [90e2b57f16](https://bsd-hardware.info/?probe=90e2b57f16) | Jun 14, 2020 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [5b35ada62a](https://bsd-hardware.info/?probe=5b35ada62a) | Jun 14, 2020 |
| HPE           | ProLiant MicroServer Gen... | Server      | [be41b5cd29](https://bsd-hardware.info/?probe=be41b5cd29) | Jun 14, 2020 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [9ad34ffa59](https://bsd-hardware.info/?probe=9ad34ffa59) | Jun 14, 2020 |
| Intel         | NUC7i3DNB J57625-508        | Mini pc     | [06beb9ad2c](https://bsd-hardware.info/?probe=06beb9ad2c) | Jun 12, 2020 |
| CompuLab      | fitlet2                     | Mini pc     | [00c1939eac](https://bsd-hardware.info/?probe=00c1939eac) | Jun 03, 2020 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [48dd406069](https://bsd-hardware.info/?probe=48dd406069) | May 30, 2020 |
| Dell          | 0MD99X A12                  | Server      | [e2ab2682cb](https://bsd-hardware.info/?probe=e2ab2682cb) | May 27, 2020 |
| ASUSTek       | P8H61 PRO                   | Desktop     | [94c4617d4e](https://bsd-hardware.info/?probe=94c4617d4e) | May 27, 2020 |
| Dell          | Latitude E6420              | Notebook    | [7c8a68918a](https://bsd-hardware.info/?probe=7c8a68918a) | May 27, 2020 |
| MSI           | Z87I GAMING AC              | Desktop     | [5d38b05178](https://bsd-hardware.info/?probe=5d38b05178) | May 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [bb2fcf8d92](https://bsd-hardware.info/?probe=bb2fcf8d92) | May 25, 2020 |
| Unknown       | Unknown                     | Desktop     | [3bcdac5d97](https://bsd-hardware.info/?probe=3bcdac5d97) | May 24, 2020 |
| HP            | ZBook 15                    | Notebook    | [3e9076f244](https://bsd-hardware.info/?probe=3e9076f244) | May 23, 2020 |
| HP            | ZBook 15                    | Notebook    | [23ec663f87](https://bsd-hardware.info/?probe=23ec663f87) | May 23, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [fa71e5839a](https://bsd-hardware.info/?probe=fa71e5839a) | May 23, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| OpenBSD 6.8         | 16        | 4.51%   |
| OPNsense 21.1.5     | 14        | 3.94%   |
| OPNsense 21.7.7     | 13        | 3.66%   |
| OPNsense 22.1       | 12        | 3.38%   |
| helloSystem 0.4.0   | 11        | 3.1%    |
| NomadBSD 1.3.2      | 10        | 2.82%   |
| helloSystem 0.7.0   | 10        | 2.82%   |
| GhostBSD 20.04.02   | 10        | 2.82%   |
| OPNsense 22.1.6     | 9         | 2.54%   |
| OPNsense 21.7.1     | 9         | 2.54%   |
| OPNsense 21.1       | 9         | 2.54%   |
| OPNsense 22.1.1     | 8         | 2.25%   |
| OPNsense 21.1.3     | 8         | 2.25%   |
| FreeBSD 12.1-p8     | 8         | 2.25%   |
| FreeBSD 13.0        | 7         | 1.97%   |
| OPNsense 22.1.2     | 6         | 1.69%   |
| OPNsense 21.7.8     | 6         | 1.69%   |
| OPNsense 21.7.3     | 6         | 1.69%   |
| OPNsense 21.1.4     | 6         | 1.69%   |
| OpenBSD 7.0         | 6         | 1.69%   |
| OpenBSD 6.9         | 6         | 1.69%   |
| helloSystem 0.5.0   | 6         | 1.69%   |
| OPNsense 22.1.4     | 5         | 1.41%   |
| OPNsense 21.7       | 5         | 1.41%   |
| OPNsense 21.1.7     | 5         | 1.41%   |
| OPNsense 21.1.6     | 5         | 1.41%   |
| OPNsense 21.1.1     | 5         | 1.41%   |
| OPNsense 20.7.8     | 5         | 1.41%   |
| NomadBSD 1.4        | 5         | 1.41%   |
| FreeBSD 13.1        | 5         | 1.41%   |
| FreeBSD 13.0-STABLE | 5         | 1.41%   |
| FreeBSD 12.2-p4     | 5         | 1.41%   |
| FreeBSD 12.2-p2     | 5         | 1.41%   |
| FreeBSD 12.1-STABLE | 5         | 1.41%   |
| OPNsense 22.1.3     | 4         | 1.13%   |
| OPNsense 21.7.5     | 4         | 1.13%   |
| FreeBSD 12.2        | 4         | 1.13%   |
| FreeBSD 12.1-p10    | 4         | 1.13%   |
| OPNsense 22.1.5     | 3         | 0.85%   |
| OPNsense 21.7.4     | 3         | 0.85%   |
| OpenBSD 7.1         | 3         | 0.85%   |
| helloSystem 0.8.0   | 3         | 0.85%   |
| FreeBSD 13.1-STABLE | 3         | 0.85%   |
| FreeBSD 13.0-p4     | 3         | 0.85%   |
| FreeBSD 13.0-p11    | 3         | 0.85%   |
| OPNsense 22.1.8     | 2         | 0.56%   |
| OPNsense 21.7.2     | 2         | 0.56%   |
| OPNsense 21.1.8     | 2         | 0.56%   |
| OpenBSD 6.7         | 2         | 0.56%   |
| GhostBSD 22.01.12   | 2         | 0.56%   |
| FreeBSD 13.1-BETA2  | 2         | 0.56%   |
| FreeBSD 13.0-RC5    | 2         | 0.56%   |
| FreeBSD 13.0-p6     | 2         | 0.56%   |
| FreeBSD 13.0-p5     | 2         | 0.56%   |
| FreeBSD 13.0-p3     | 2         | 0.56%   |
| FreeBSD 13.0-p1     | 2         | 0.56%   |
| FreeBSD 12.2-p3     | 2         | 0.56%   |
| FreeBSD 12.2-p10    | 2         | 0.56%   |
| FreeBSD 12.1-p9     | 2         | 0.56%   |
| FreeBSD 12.1-p7     | 2         | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 120       | 40.68%  |
| FreeBSD     | 85        | 28.81%  |
| OpenBSD     | 29        | 9.83%   |
| helloSystem | 29        | 9.83%   |
| NomadBSD    | 14        | 4.75%   |
| GhostBSD    | 14        | 4.75%   |
| TrueNAS     | 1         | 0.34%   |
| HardenedBSD | 1         | 0.34%   |
| FuryBSD     | 1         | 0.34%   |
| FreeNAS     | 1         | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 280       | 98.94%  |
| i386   | 2         | 0.71%   |
| macppc | 1         | 0.35%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 159       | 53.36%  |
| helloDesktop | 32        | 10.74%  |
| XFCE         | 26        | 8.72%   |
| fvwm         | 18        | 6.04%   |
| Openbox      | 15        | 5.03%   |
| KDE5         | 15        | 5.03%   |
| MATE         | 11        | 3.69%   |
| TWM          | 6         | 2.01%   |
| GNOME        | 6         | 2.01%   |
| i3           | 4         | 1.34%   |
| AwesomeWM    | 3         | 1.01%   |
| X-Cinnamon   | 1         | 0.34%   |
| LXDE         | 1         | 0.34%   |
| Cinnamon     | 1         | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 164       | 57.54%  |
| X11     | 120       | 42.11%  |
| Wayland | 1         | 0.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 196       | 67.35%  |
| SLiM    | 53        | 18.21%  |
| LightDM | 20        | 6.87%   |
| SDDM    | 10        | 3.44%   |
| XDM     | 7         | 2.41%   |
| GDM     | 5         | 1.72%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 178       | 60.75%  |
| en_US           | 44        | 15.02%  |
| fr_FR           | 37        | 12.63%  |
| C               | 27        | 9.22%   |
| en_GB           | 2         | 0.68%   |
| de_DE           | 2         | 0.68%   |
| fr_FR.US-ASCII  | 1         | 0.34%   |
| es_ES           | 1         | 0.34%   |
| en_US.ISO8859-1 | 1         | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 219       | 76.84%  |
| BIOS | 66        | 23.16%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 136       | 46.9%   |
| Zfs    | 117       | 40.34%  |
| Ffs    | 29        | 10%     |
| Cd9660 | 8         | 2.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 240       | 83.92%  |
| MBR     | 44        | 15.38%  |
| Unknown | 2         | 0.7%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 43        | 15.19%  |
| ASUSTek Computer    | 38        | 13.43%  |
| Lenovo              | 33        | 11.66%  |
| Intel               | 21        | 7.42%   |
| Hewlett-Packard     | 17        | 6.01%   |
| PC Engines          | 16        | 5.65%   |
| Gigabyte Technology | 14        | 4.95%   |
| Unknown             | 13        | 4.59%   |
| MSI                 | 10        | 3.53%   |
| ASRock              | 9         | 3.18%   |
| Supermicro          | 8         | 2.83%   |
| BESSTAR Tech        | 5         | 1.77%   |
| Apple               | 5         | 1.77%   |
| AMI                 | 5         | 1.77%   |
| Deciso              | 4         | 1.41%   |
| Acer                | 4         | 1.41%   |
| Shuttle             | 3         | 1.06%   |
| Fujitsu             | 3         | 1.06%   |
| TUXEDO              | 2         | 0.71%   |
| RUNING              | 2         | 0.71%   |
| Protectli           | 2         | 0.71%   |
| Google              | 2         | 0.71%   |
| AWOW                | 2         | 0.71%   |
| ASRockRack          | 2         | 0.71%   |
| AMD                 | 2         | 0.71%   |
| ZOTAC               | 1         | 0.35%   |
| Wistron             | 1         | 0.35%   |
| VeryPC              | 1         | 0.35%   |
| Sophos              | 1         | 0.35%   |
| Sony                | 1         | 0.35%   |
| SECO                | 1         | 0.35%   |
| Samsung Electronics | 1         | 0.35%   |
| Pegatron            | 1         | 0.35%   |
| Packard Bell        | 1         | 0.35%   |
| Notebook            | 1         | 0.35%   |
| Jetway              | 1         | 0.35%   |
| HPE                 | 1         | 0.35%   |
| CompuLab            | 1         | 0.35%   |
| CNCTION-IAF-E3845   | 1         | 0.35%   |
| Clevo               | 1         | 0.35%   |
| AZW                 | 1         | 0.35%   |
| Alienware           | 1         | 0.35%   |
| AAEON               | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 14        | 4.95%   |
| PC Engines APU2                    | 9         | 3.18%   |
| Intel Q3XXG4-P V1.0                | 7         | 2.47%   |
| AMI Aptio CRB                      | 5         | 1.77%   |
| PC Engines APU3                    | 3         | 1.06%   |
| Dell OptiPlex 9020                 | 3         | 1.06%   |
| Deciso Netboard A20                | 3         | 1.06%   |
| ASUS All Series                    | 3         | 1.06%   |
| TUXEDO InfinityBook13V3            | 2         | 0.71%   |
| Supermicro Super Server            | 2         | 0.71%   |
| RUNING B75M INTEL H3V              | 2         | 0.71%   |
| PC Engines apu4                    | 2         | 0.71%   |
| HP ProLiant MicroServer Gen8       | 2         | 0.71%   |
| Gigabyte X570 I AORUS PRO WIFI     | 2         | 0.71%   |
| Dell PowerEdge R220                | 2         | 0.71%   |
| Dell PowerEdge R200                | 2         | 0.71%   |
| Dell Latitude 3410                 | 2         | 0.71%   |
| BESSTAR Tech N40                   | 2         | 0.71%   |
| BESSTAR Tech GK41                  | 2         | 0.71%   |
| AWOW PC BOX                        | 2         | 0.71%   |
| ASUS Z170-P D3                     | 2         | 0.71%   |
| ASUS PRIME B450M-A                 | 2         | 0.71%   |
| ASUS P8Z68-V LX                    | 2         | 0.71%   |
| ZOTAC XXXXXX                       | 1         | 0.35%   |
| Wistron ProLiant ML110 G6          | 1         | 0.35%   |
| VeryPC S400-K7-N-O                 | 1         | 0.35%   |
| Supermicro X8STi                   | 1         | 0.35%   |
| Supermicro X7SPA-HF                | 1         | 0.35%   |
| Supermicro X10SLH-N6-ST031         | 1         | 0.35%   |
| Supermicro SYS-E300-9D-8CN8TP      | 1         | 0.35%   |
| Supermicro SYS-5019A-FTN4          | 1         | 0.35%   |
| Supermicro bullx                   | 1         | 0.35%   |
| Sophos XG                          | 1         | 0.35%   |
| Sony VGN-AR630E                    | 1         | 0.35%   |
| Shuttle XS35V5                     | 1         | 0.35%   |
| Shuttle NC10U                      | 1         | 0.35%   |
| Shuttle DS61                       | 1         | 0.35%   |
| SECO UDOO x86                      | 1         | 0.35%   |
| Samsung R720                       | 1         | 0.35%   |
| Protectli VP2410                   | 1         | 0.35%   |
| Protectli FW6                      | 1         | 0.35%   |
| Pegatron Elite 7300 Series MT      | 1         | 0.35%   |
| PC Engines apu1                    | 1         | 0.35%   |
| PC Engines APU                     | 1         | 0.35%   |
| Packard Bell imedia S2110          | 1         | 0.35%   |
| Notebook W510LU                    | 1         | 0.35%   |
| MSI P65 Creator 8RE                | 1         | 0.35%   |
| MSI MS-N033                        | 1         | 0.35%   |
| MSI MS-9A68                        | 1         | 0.35%   |
| MSI MS-9A45                        | 1         | 0.35%   |
| MSI MS-7C09                        | 1         | 0.35%   |
| MSI MS-7C02                        | 1         | 0.35%   |
| MSI MS-7B24                        | 1         | 0.35%   |
| MSI MS-7887                        | 1         | 0.35%   |
| MSI MS-7758                        | 1         | 0.35%   |
| MSI MS-7253                        | 1         | 0.35%   |
| Lenovo ThinkSystem ST50 7Y48CTO1WW | 1         | 0.35%   |
| Lenovo ThinkPad X280 20KFCTO1WW    | 1         | 0.35%   |
| Lenovo ThinkPad X250 20CLS7WY04    | 1         | 0.35%   |
| Lenovo ThinkPad X250 20CLS4WV08    | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 26        | 9.19%   |
| Unknown                       | 14        | 4.95%   |
| Dell PowerEdge                | 13        | 4.59%   |
| Dell OptiPlex                 | 11        | 3.89%   |
| Dell Latitude                 | 10        | 3.53%   |
| PC Engines APU2               | 9         | 3.18%   |
| Intel Q3XXG4-P                | 7         | 2.47%   |
| ASUS PRIME                    | 6         | 2.12%   |
| AMI Aptio                     | 5         | 1.77%   |
| HP ProLiant                   | 4         | 1.41%   |
| HP Compaq                     | 4         | 1.41%   |
| Deciso Netboard               | 4         | 1.41%   |
| Acer Aspire                   | 4         | 1.41%   |
| PC Engines APU3               | 3         | 1.06%   |
| HP EliteBook                  | 3         | 1.06%   |
| ASUS All                      | 3         | 1.06%   |
| TUXEDO InfinityBook13V3       | 2         | 0.71%   |
| Supermicro Super              | 2         | 0.71%   |
| RUNING B75M                   | 2         | 0.71%   |
| PC Engines apu4               | 2         | 0.71%   |
| Lenovo Legion                 | 2         | 0.71%   |
| Gigabyte X570                 | 2         | 0.71%   |
| Dell Vostro                   | 2         | 0.71%   |
| Dell Studio                   | 2         | 0.71%   |
| Dell Precision                | 2         | 0.71%   |
| Dell Inspiron                 | 2         | 0.71%   |
| BESSTAR Tech N40              | 2         | 0.71%   |
| BESSTAR Tech GK41             | 2         | 0.71%   |
| AWOW PC                       | 2         | 0.71%   |
| ASUS Z170-P                   | 2         | 0.71%   |
| ASUS P8Z68-V                  | 2         | 0.71%   |
| ZOTAC XXXXXX                  | 1         | 0.35%   |
| Wistron ProLiant              | 1         | 0.35%   |
| VeryPC S400-K7-N-O            | 1         | 0.35%   |
| Supermicro X8STi              | 1         | 0.35%   |
| Supermicro X7SPA-HF           | 1         | 0.35%   |
| Supermicro X10SLH-N6-ST031    | 1         | 0.35%   |
| Supermicro SYS-E300-9D-8CN8TP | 1         | 0.35%   |
| Supermicro SYS-5019A-FTN4     | 1         | 0.35%   |
| Supermicro bullx              | 1         | 0.35%   |
| Sophos XG                     | 1         | 0.35%   |
| Sony VGN-AR630E               | 1         | 0.35%   |
| Shuttle XS35V5                | 1         | 0.35%   |
| Shuttle NC10U                 | 1         | 0.35%   |
| Shuttle DS61                  | 1         | 0.35%   |
| SECO UDOO                     | 1         | 0.35%   |
| Samsung R720                  | 1         | 0.35%   |
| Protectli VP2410              | 1         | 0.35%   |
| Protectli FW6                 | 1         | 0.35%   |
| Pegatron Elite                | 1         | 0.35%   |
| PC Engines apu1               | 1         | 0.35%   |
| PC Engines APU                | 1         | 0.35%   |
| Packard Bell imedia           | 1         | 0.35%   |
| Notebook W510LU               | 1         | 0.35%   |
| MSI P65                       | 1         | 0.35%   |
| MSI MS-N033                   | 1         | 0.35%   |
| MSI MS-9A68                   | 1         | 0.35%   |
| MSI MS-9A45                   | 1         | 0.35%   |
| MSI MS-7C09                   | 1         | 0.35%   |
| MSI MS-7C02                   | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 37        | 13.07%  |
| 2020    | 34        | 12.01%  |
| 2016    | 34        | 12.01%  |
| 2018    | 31        | 10.95%  |
| 2013    | 21        | 7.42%   |
| 2021    | 19        | 6.71%   |
| 2015    | 17        | 6.01%   |
| 2012    | 15        | 5.3%    |
| 2017    | 14        | 4.95%   |
| 2011    | 14        | 4.95%   |
| 2014    | 13        | 4.59%   |
| 2010    | 11        | 3.89%   |
| 2009    | 7         | 2.47%   |
| 2008    | 7         | 2.47%   |
| 2022    | 3         | 1.06%   |
| 2007    | 3         | 1.06%   |
| Unknown | 2         | 0.71%   |
| 2006    | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 153       | 54.06%  |
| Notebook   | 87        | 30.74%  |
| Server     | 20        | 7.07%   |
| Mini pc    | 19        | 6.71%   |
| Firewall   | 2         | 0.71%   |
| All in one | 2         | 0.71%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 263       | 92.93%  |
| Yes  | 20        | 7.07%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 93        | 32.52%  |
| 4.01-8.0        | 71        | 24.83%  |
| 16.01-24.0      | 65        | 22.73%  |
| 32.01-64.0      | 24        | 8.39%   |
| 2.01-3.0        | 14        | 4.9%    |
| 64.01-256.0     | 8         | 2.8%    |
| 1.01-2.0        | 5         | 1.75%   |
| 3.01-4.0        | 4         | 1.4%    |
| More than 256.0 | 1         | 0.35%   |
| 24.01-32.0      | 1         | 0.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 160       | 54.79%  |
| 0.51-1.0    | 78        | 26.71%  |
| 1.01-2.0    | 26        | 8.9%    |
| 2.01-3.0    | 9         | 3.08%   |
| 4.01-8.0    | 5         | 1.71%   |
| 8.01-16.0   | 5         | 1.71%   |
| 32.01-64.0  | 3         | 1.03%   |
| 3.01-4.0    | 3         | 1.03%   |
| 24.01-32.0  | 1         | 0.34%   |
| 64.01-256.0 | 1         | 0.34%   |
| 16.01-24.0  | 1         | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 172       | 59.72%  |
| 2      | 55        | 19.1%   |
| 0      | 26        | 9.03%   |
| 3      | 19        | 6.6%    |
| 4      | 7         | 2.43%   |
| 5      | 5         | 1.74%   |
| 6      | 2         | 0.69%   |
| 25     | 1         | 0.35%   |
| 10     | 1         | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 232       | 80.56%  |
| Yes       | 56        | 19.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 275       | 96.83%  |
| No        | 9         | 3.17%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 148       | 52.3%   |
| Yes       | 135       | 47.7%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 202       | 71.13%  |
| Yes       | 82        | 28.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| France  | 283       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                         | Computers | Percent |
|------------------------------|-----------|---------|
| Paris                        | 64        | 20.19%  |
| Toulouse                     | 8         | 2.52%   |
| Franconville                 | 7         | 2.21%   |
| Bordeaux                     | 7         | 2.21%   |
| Soisy-sur-Seine              | 5         | 1.58%   |
| Saint-Denis                  | 5         | 1.58%   |
| Roubaix                      | 5         | 1.58%   |
| Marseille                    | 4         | 1.26%   |
| Lyon                         | 4         | 1.26%   |
| Agen                         | 4         | 1.26%   |
| Villeurbanne                 | 3         | 0.95%   |
| Vauvillers                   | 3         | 0.95%   |
| Vaulx-en-Velin               | 3         | 0.95%   |
| Rennes                       | 3         | 0.95%   |
| Montfermeil                  | 3         | 0.95%   |
| M??con                       | 3         | 0.95%   |
| Fontenay-sous-Bois           | 3         | 0.95%   |
| Asnieres-sur-Seine           | 3         | 0.95%   |
| ?????chirolles               | 2         | 0.63%   |
| Villeneuve-Saint-Georges     | 2         | 0.63%   |
| Villejuif                    | 2         | 0.63%   |
| Vichy                        | 2         | 0.63%   |
| Stiring-Wendel               | 2         | 0.63%   |
| Seyssinet-Pariset            | 2         | 0.63%   |
| Sallanches                   | 2         | 0.63%   |
| Saint-Martin-d'H????res      | 2         | 0.63%   |
| Saint-Herblain               | 2         | 0.63%   |
| Rosny-sous-Bois              | 2         | 0.63%   |
| Pau                          | 2         | 0.63%   |
| Noisy-le-Grand               | 2         | 0.63%   |
| Nantes                       | 2         | 0.63%   |
| Montgeron                    | 2         | 0.63%   |
| Limonest                     | 2         | 0.63%   |
| Levallois-Perret             | 2         | 0.63%   |
| Le Relecq-Kerhuon            | 2         | 0.63%   |
| Lamothe-Goas                 | 2         | 0.63%   |
| Dijon                        | 2         | 0.63%   |
| Colmar                       | 2         | 0.63%   |
| Cognac                       | 2         | 0.63%   |
| Beaumes-de-Venise            | 2         | 0.63%   |
| ?????tampes                  | 2         | 0.63%   |
| Yerres                       | 1         | 0.32%   |
| Vitry-sur-Seine              | 1         | 0.32%   |
| Villaz                       | 1         | 0.32%   |
| Viarmes                      | 1         | 0.32%   |
| Vertou                       | 1         | 0.32%   |
| V??nissieux                  | 1         | 0.32%   |
| Vauclerc                     | 1         | 0.32%   |
| Tulle                        | 1         | 0.32%   |
| Tournon-sur-Rh????ne         | 1         | 0.32%   |
| Thionville                   | 1         | 0.32%   |
| Teteghem                     | 1         | 0.32%   |
| Strasbourg                   | 1         | 0.32%   |
| St-Malo                      | 1         | 0.32%   |
| Schiltigheim                 | 1         | 0.32%   |
| Salagnon                     | 1         | 0.32%   |
| Sainte-Foy-les-Lyon          | 1         | 0.32%   |
| Saint-?????tienne-du-Rouvray | 1         | 0.32%   |
| Saint-Saulge                 | 1         | 0.32%   |
| Saint-Pee-sur-Nivelle        | 1         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 50        | 71     | 15.15%  |
| Samsung Electronics | 44        | 62     | 13.33%  |
| WDC                 | 37        | 79     | 11.21%  |
| Crucial             | 28        | 34     | 8.48%   |
| Kingston            | 22        | 34     | 6.67%   |
| Transcend           | 19        | 23     | 5.76%   |
| Toshiba             | 18        | 31     | 5.45%   |
| SanDisk             | 15        | 23     | 4.55%   |
| Phison              | 9         | 10     | 2.73%   |
| Intel               | 8         | 14     | 2.42%   |
| HGST                | 8         | 15     | 2.42%   |
| China               | 7         | 12     | 2.12%   |
| Micron Technology   | 5         | 9      | 1.52%   |
| NVMe                | 4         | 4      | 1.21%   |
| Hoodisk             | 4         | 4      | 1.21%   |
| Hitachi             | 4         | 4      | 1.21%   |
| FORESEE             | 4         | 5      | 1.21%   |
| SK hynix            | 3         | 3      | 0.91%   |
| PNY                 | 3         | 4      | 0.91%   |
| OCZ                 | 3         | 4      | 0.91%   |
| LDLC                | 3         | 3      | 0.91%   |
| Corsair             | 3         | 4      | 0.91%   |
| Apple               | 3         | 5      | 0.91%   |
| SPCC                | 2         | 2      | 0.61%   |
| Innodisk            | 2         | 2      | 0.61%   |
| Hewlett-Packard     | 2         | 4      | 0.61%   |
| Generic             | 2         | 2      | 0.61%   |
| Fujitsu             | 2         | 2      | 0.61%   |
| TCSUNBOW            | 1         | 3      | 0.3%    |
| Silicon Power       | 1         | 1      | 0.3%    |
| ShiJi               | 1         | 2      | 0.3%    |
| SABRENT             | 1         | 1      | 0.3%    |
| Pccooler            | 1         | 1      | 0.3%    |
| NETAPP              | 1         | 2      | 0.3%    |
| Maxtor              | 1         | 2      | 0.3%    |
| LITEON              | 1         | 2      | 0.3%    |
| LDLC F6+            | 1         | 1      | 0.3%    |
| Kston               | 1         | 1      | 0.3%    |
| Kingchuxing         | 1         | 2      | 0.3%    |
| Integral            | 1         | 1      | 0.3%    |
| Indilinx            | 1         | 5      | 0.3%    |
| EMTEC               | 1         | 1      | 0.3%    |
| Dell                | 1         | 23     | 0.3%    |
| A-DATA Technology   | 1         | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Phison SATA SSD 16GB                | 8         | 2.27%   |
| Crucial CT1000P1SSD8 1TB            | 5         | 1.42%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 4         | 1.13%   |
| SanDisk SSD PLUS 120GB              | 4         | 1.13%   |
| Samsung SSD 850 EVO 250GB           | 4         | 1.13%   |
| Kingston SV300S37A120G 120GB        | 4         | 1.13%   |
| Kingston SA400S37240G 240GB         | 4         | 1.13%   |
| Crucial CT120BX500SSD1 120GB        | 4         | 1.13%   |
| Transcend TS256GMTS952T2 256GB      | 3         | 0.85%   |
| Seagate ST1000LM049-2GH172 1TB      | 3         | 0.85%   |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 0.85%   |
| HGST HUS724020ALA640 2TB            | 3         | 0.85%   |
| Crucial CT1050MX300SSD1 1TB         | 3         | 0.85%   |
| Crucial CT1000BX500SSD1 1TB         | 3         | 0.85%   |
| WDC WD40EFRX-68N32N0 4TB            | 2         | 0.57%   |
| WDC WD2000FYYX 2TB                  | 2         | 0.57%   |
| WDC WD10EZEX-08WN4A0 1TB            | 2         | 0.57%   |
| Transcend TS128GSSD420K 128GB       | 2         | 0.57%   |
| Transcend TS128GMSA230S 128GB       | 2         | 0.57%   |
| Transcend TS120GMTS420S 120GB       | 2         | 0.57%   |
| Toshiba MK2556GSY 250GB             | 2         | 0.57%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB | 2         | 0.57%   |
| SPCC Solid State Disk 512GB         | 2         | 0.57%   |
| Seagate ST3500418AS 500GB           | 2         | 0.57%   |
| Seagate ST31000524AS 1TB            | 2         | 0.57%   |
| Seagate ST1000NM0011 1TB            | 2         | 0.57%   |
| Seagate ST1000DM010-2EP102 1TB      | 2         | 0.57%   |
| Seagate ST1000DM003-1SB102 1TB      | 2         | 0.57%   |
| Seagate ST1000DM003-1ER162 1TB      | 2         | 0.57%   |
| SanDisk SDSSDA240G 240GB            | 2         | 0.57%   |
| Samsung SSD 950 PRO 512GB           | 2         | 0.57%   |
| Samsung SSD 860 EVO 1TB             | 2         | 0.57%   |
| Samsung SSD 850 EVO 1TB             | 2         | 0.57%   |
| Samsung HD501LJ 500GB               | 2         | 0.57%   |
| Micron 1100 SATA 256GB              | 2         | 0.57%   |
| LDLC F8+M.2 240 240GB               | 2         | 0.57%   |
| Kingston SUV500MS120G 120GB         | 2         | 0.57%   |
| Kingston SUV400S37240G 240GB        | 2         | 0.57%   |
| Kingston SA400S37480G 480GB         | 2         | 0.57%   |
| Kingston SA400S37120G 120GB         | 2         | 0.57%   |
| Intel SSDPEKNW512G8H 512GB          | 2         | 0.57%   |
| Intel SSDPEKKF256G8L 256GB          | 2         | 0.57%   |
| HGST HUS726020ALA610 2TB            | 2         | 0.57%   |
| HP RAID 1(1+0) 2TB                  | 2         | 0.57%   |
| Generic Flash Disk 2GB              | 2         | 0.57%   |
| FORESEE 64GB SSD                    | 2         | 0.57%   |
| FORESEE 128GB SSD                   | 2         | 0.57%   |
| Crucial CT960M500SSD1 960GB         | 2         | 0.57%   |
| Crucial CT500MX500SSD1 500GB        | 2         | 0.57%   |
| Crucial CT250P2SSD8 250GB           | 2         | 0.57%   |
| Crucial CT250MX500SSD1 250GB        | 2         | 0.57%   |
| Crucial CT240BX500SSD1 240GB        | 2         | 0.57%   |
| China SH00M240GB                    | 2         | 0.57%   |
| China MSATA 32GB SSD                | 2         | 0.57%   |
| Apple SSD SM256E 256GB              | 2         | 0.57%   |
| WDC WDS240G2G0B-00EPW0 240GB        | 1         | 0.28%   |
| WDC WDS240G2G0A-00JH30 240GB        | 1         | 0.28%   |
| WDC WDS100T2G0A-00JH30 1TB          | 1         | 0.28%   |
| WDC WD80EZAZ-11TDBA0 8TB            | 1         | 0.28%   |
| WDC WD800BEVT-75ZCT2 80GB           | 1         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 49        | 70     | 37.12%  |
| WDC                 | 33        | 73     | 25%     |
| Toshiba             | 15        | 26     | 11.36%  |
| Samsung Electronics | 8         | 14     | 6.06%   |
| HGST                | 8         | 15     | 6.06%   |
| Hitachi             | 4         | 4      | 3.03%   |
| NVMe                | 3         | 3      | 2.27%   |
| Hewlett-Packard     | 2         | 4      | 1.52%   |
| Generic             | 2         | 2      | 1.52%   |
| Fujitsu             | 2         | 2      | 1.52%   |
| SABRENT             | 1         | 1      | 0.76%   |
| NETAPP              | 1         | 2      | 0.76%   |
| Maxtor              | 1         | 2      | 0.76%   |
| LDLC F6+            | 1         | 1      | 0.76%   |
| Dell                | 1         | 23     | 0.76%   |
| Apple               | 1         | 3      | 0.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 30     | 13.92%  |
| Kingston            | 21        | 32     | 13.29%  |
| Crucial             | 20        | 23     | 12.66%  |
| Transcend           | 18        | 21     | 11.39%  |
| SanDisk             | 15        | 23     | 9.49%   |
| Phison              | 8         | 9      | 5.06%   |
| China               | 7         | 12     | 4.43%   |
| Hoodisk             | 4         | 4      | 2.53%   |
| FORESEE             | 4         | 5      | 2.53%   |
| WDC                 | 3         | 3      | 1.9%    |
| Toshiba             | 3         | 5      | 1.9%    |
| PNY                 | 3         | 4      | 1.9%    |
| OCZ                 | 3         | 4      | 1.9%    |
| Intel               | 3         | 4      | 1.9%    |
| Corsair             | 3         | 4      | 1.9%    |
| SPCC                | 2         | 2      | 1.27%   |
| Micron Technology   | 2         | 6      | 1.27%   |
| Innodisk            | 2         | 2      | 1.27%   |
| Apple               | 2         | 2      | 1.27%   |
| TCSUNBOW            | 1         | 3      | 0.63%   |
| SK hynix            | 1         | 1      | 0.63%   |
| Silicon Power       | 1         | 1      | 0.63%   |
| ShiJi               | 1         | 2      | 0.63%   |
| Pccooler            | 1         | 1      | 0.63%   |
| NVMe                | 1         | 1      | 0.63%   |
| LITEON              | 1         | 2      | 0.63%   |
| Kston               | 1         | 1      | 0.63%   |
| Kingchuxing         | 1         | 2      | 0.63%   |
| Integral            | 1         | 1      | 0.63%   |
| Indilinx            | 1         | 5      | 0.63%   |
| EMTEC               | 1         | 1      | 0.63%   |
| A-DATA Technology   | 1         | 1      | 0.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 146       | 217    | 49.32%  |
| HDD  | 111       | 245    | 37.5%   |
| NVMe | 39        | 56     | 13.18%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 230       | 462    | 85.5%   |
| NVMe | 39        | 56     | 14.5%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 183       | 301    | 67.53%  |
| 0.51-1.0   | 50        | 81     | 18.45%  |
| 1.01-2.0   | 25        | 51     | 9.23%   |
| 4.01-10.0  | 5         | 9      | 1.85%   |
| 3.01-4.0   | 4         | 11     | 1.48%   |
| 2.01-3.0   | 4         | 9      | 1.48%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 89        | 30.58%  |
| 1-20           | 59        | 20.27%  |
| 251-500        | 39        | 13.4%   |
| 21-50          | 33        | 11.34%  |
| 51-100         | 28        | 9.62%   |
| 501-1000       | 27        | 9.28%   |
| 1001-2000      | 9         | 3.09%   |
| More than 3000 | 3         | 1.03%   |
| 2001-3000      | 3         | 1.03%   |
| Unknown        | 1         | 0.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 240       | 83.33%  |
| 21-50     | 22        | 7.64%   |
| 101-250   | 11        | 3.82%   |
| 251-500   | 6         | 2.08%   |
| 51-100    | 5         | 1.74%   |
| 501-1000  | 2         | 0.69%   |
| 1001-2000 | 1         | 0.35%   |
| Unknown   | 1         | 0.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000NM0011 1TB              | 2         | 3      | 4.17%   |
| Samsung Electronics HD501LJ 500GB     | 2         | 2      | 4.17%   |
| Kingston SV300S37A120G 120GB          | 2         | 2      | 4.17%   |
| WDC WD6400AAKS-22A7B0 640GB           | 1         | 1      | 2.08%   |
| WDC WD5002ABYS-18B1B0 500GB           | 1         | 1      | 2.08%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1         | 4      | 2.08%   |
| WDC WD2500BEVS-60UST0 250GB           | 1         | 1      | 2.08%   |
| WDC WD2002FYPS-02W3B0 2TB             | 1         | 1      | 2.08%   |
| WDC WD15EADS-00P8B0 1.5TB             | 1         | 1      | 2.08%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 2.08%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 1      | 2.08%   |
| WDC WD10EAVS-00D7B0 1TB               | 1         | 1      | 2.08%   |
| WDC WD10EARS-00Y5B1 1TB               | 1         | 1      | 2.08%   |
| WDC WD1001FAES-75W7A0 1TB             | 1         | 1      | 2.08%   |
| Toshiba MQ01ABD075 752GB              | 1         | 1      | 2.08%   |
| Toshiba MK1629GSGF 160GB              | 1         | 3      | 2.08%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 2.08%   |
| Seagate ST9320423AS 320GB             | 1         | 1      | 2.08%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 2.08%   |
| Seagate ST500VT000-1DK142 500GB       | 1         | 1      | 2.08%   |
| Seagate ST500LM000-SSHD-8GB           | 1         | 2      | 2.08%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 2.08%   |
| Seagate ST380013AS 80GB               | 1         | 2      | 2.08%   |
| Seagate ST3250620AS 250GB             | 1         | 1      | 2.08%   |
| Seagate ST320LT012-9WS14C 320GB       | 1         | 4      | 2.08%   |
| Seagate ST3160212AS 160GB             | 1         | 1      | 2.08%   |
| Seagate ST3160023AS 160GB             | 1         | 1      | 2.08%   |
| Seagate ST31000524AS 1TB              | 1         | 1      | 2.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 2.08%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 2.08%   |
| SanDisk SDSSDA240G 240GB              | 1         | 1      | 2.08%   |
| SanDisk SD7UB3Q256G1001 256GB         | 1         | 1      | 2.08%   |
| Samsung Electronics SSD 840 EVO 500GB | 1         | 2      | 2.08%   |
| Samsung Electronics HD322GJ 320GB     | 1         | 1      | 2.08%   |
| Samsung Electronics HD256GJ 250GB     | 1         | 1      | 2.08%   |
| Samsung Electronics HD103UJ 1TB       | 1         | 1      | 2.08%   |
| OCZ VERTEX-TURBO 32GB                 | 1         | 2      | 2.08%   |
| Kingston SUV500MS480G 480GB           | 1         | 1      | 2.08%   |
| Intel SSDSA2M080G2GN 80GB             | 1         | 1      | 2.08%   |
| Innodisk 2.5-inch SATA SSD 3ME2 128GB | 1         | 1      | 2.08%   |
| Hitachi HTS542525K9SA00 250GB         | 1         | 1      | 2.08%   |
| HGST HTS545050A7E660 500GB            | 1         | 2      | 2.08%   |
| Crucial CT525MX300SSD1 528GB          | 1         | 1      | 2.08%   |
| Corsair Force 3 SSD 120GB             | 1         | 2      | 2.08%   |
| A-DATA Technology SU650 120GB         | 1         | 1      | 2.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 22     | 33.33%  |
| WDC                 | 11        | 14     | 24.44%  |
| Samsung Electronics | 4         | 7      | 8.89%   |
| Kingston            | 3         | 3      | 6.67%   |
| Toshiba             | 2         | 4      | 4.44%   |
| SanDisk             | 2         | 2      | 4.44%   |
| OCZ                 | 1         | 2      | 2.22%   |
| Intel               | 1         | 1      | 2.22%   |
| Innodisk            | 1         | 1      | 2.22%   |
| Hitachi             | 1         | 1      | 2.22%   |
| HGST                | 1         | 2      | 2.22%   |
| Crucial             | 1         | 1      | 2.22%   |
| Corsair             | 1         | 2      | 2.22%   |
| A-DATA Technology   | 1         | 1      | 2.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 22     | 45.45%  |
| WDC                 | 11        | 14     | 33.33%  |
| Samsung Electronics | 3         | 5      | 9.09%   |
| Toshiba             | 2         | 4      | 6.06%   |
| Hitachi             | 1         | 1      | 3.03%   |
| HGST                | 1         | 2      | 3.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 29        | 48     | 70.73%  |
| SSD  | 12        | 15     | 29.27%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 228       | 444    | 82.61%  |
| Malfunc  | 40        | 63     | 14.49%  |
| Detected | 8         | 11     | 2.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 210       | 61.76%  |
| AMD                           | 54        | 15.88%  |
| Samsung Electronics           | 17        | 5%      |
| Broadcom / LSI                | 11        | 3.24%   |
| Micron/Crucial Technology     | 9         | 2.65%   |
| ASMedia Technology            | 6         | 1.76%   |
| Marvell Technology Group      | 4         | 1.18%   |
| Silicon Motion                | 3         | 0.88%   |
| Micron Technology             | 3         | 0.88%   |
| JMicron Technology            | 3         | 0.88%   |
| Hewlett-Packard               | 3         | 0.88%   |
| VIA Technologies              | 2         | 0.59%   |
| SK hynix                      | 2         | 0.59%   |
| SanDisk                       | 2         | 0.59%   |
| Nvidia                        | 2         | 0.59%   |
| Chelsio Communications        | 2         | 0.59%   |
| Silicon Image                 | 1         | 0.29%   |
| Seagate Technology            | 1         | 0.29%   |
| Phison Electronics            | 1         | 0.29%   |
| KIOXIA                        | 1         | 0.29%   |
| Kingston Technology Company   | 1         | 0.29%   |
| Integrated Technology Express | 1         | 0.29%   |
| Unknown                       | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 36        | 9.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 15        | 3.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 13        | 3.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 12        | 3.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10        | 2.61%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 10        | 2.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10        | 2.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10        | 2.61%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 9         | 2.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 8         | 2.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 8         | 2.09%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 7         | 1.83%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 7         | 1.83%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 7         | 1.83%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 1.83%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 7         | 1.83%   |
| Intel SATA Controller [RAID mode]                                                       | 6         | 1.57%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6         | 1.57%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6         | 1.57%   |
| Unknown                                                                                 | 6         | 1.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 5         | 1.31%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 5         | 1.31%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 5         | 1.31%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 5         | 1.31%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5         | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5         | 1.31%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 4         | 1.04%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 4         | 1.04%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 4         | 1.04%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 4         | 1.04%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 4         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 1.04%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3         | 0.78%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3         | 0.78%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 3         | 0.78%   |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                                    | 3         | 0.78%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3         | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 3         | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 3         | 0.78%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3         | 0.78%   |
| HP Smart Array G6 controllers                                                           | 3         | 0.78%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 3         | 0.78%   |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                                      | 3         | 0.78%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3         | 0.78%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 2         | 0.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 0.52%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 0.52%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2         | 0.52%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2         | 0.52%   |
| Intel SSD 660P Series                                                                   | 2         | 0.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 0.52%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 0.52%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 0.52%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2         | 0.52%   |
| Intel Atom Processor C3000 Series SATA Controller 1                                     | 2         | 0.52%   |
| Intel Atom Processor C3000 Series SATA Controller 0                                     | 2         | 0.52%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2         | 0.52%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2         | 0.52%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2         | 0.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 225       | 65.6%   |
| NVMe | 43        | 12.54%  |
| IDE  | 38        | 11.08%  |
| RAID | 26        | 7.58%   |
| SCSI | 6         | 1.75%   |
| SAS  | 5         | 1.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 224       | 78.87%  |
| AMD     | 59        | 20.77%  |
| PowerPC | 1         | 0.35%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| AMD GX-412TC SOC                      | 14        | 4.9%    |
| Intel Core i5-2520M CPU @ 2.50GHz     | 5         | 1.75%   |
| Intel Celeron J4125 CPU @ 2.00GHz     | 5         | 1.75%   |
| Intel Core i5-5300U CPU @ 2.30GHz     | 4         | 1.4%    |
| Intel Celeron CPU J3455 @ 1.50GHz     | 4         | 1.4%    |
| Intel Celeron CPU J1900 @ 1.99GHz     | 4         | 1.4%    |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz   | 3         | 1.05%   |
| Intel Core i7-7500U CPU @ 2.70GHz     | 3         | 1.05%   |
| Intel Core i5-8265U CPU @ 1.60GHz     | 3         | 1.05%   |
| Intel Core i5-7200U CPU @ 2.50GHz     | 3         | 1.05%   |
| Intel Core i5-4300Y CPU @ 1.60GHz     | 3         | 1.05%   |
| Intel Core i5-2500K CPU @ 3.30GHz     | 3         | 1.05%   |
| Intel Core i3-3225 CPU @ 3.30GHz      | 3         | 1.05%   |
| Intel Celeron CPU N3160 @ 1.60GHz     | 3         | 1.05%   |
| Intel Celeron CPU N3150 @ 1.60GHz     | 3         | 1.05%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz     | 3         | 1.05%   |
| AMD Ryzen 7 3700X 8-Core Processor    | 3         | 1.05%   |
| AMD Ryzen 5 2600 Six-Core Processor   | 3         | 1.05%   |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz   | 2         | 0.7%    |
| Intel Xeon CPU E3-1225 V2 @ 3.20GHz   | 2         | 0.7%    |
| Intel Core i7-8700 CPU @ 3.20GHz      | 2         | 0.7%    |
| Intel Core i7-6500U CPU @ 2.50GHz     | 2         | 0.7%    |
| Intel Core i5-9300H CPU @ 2.40GHz     | 2         | 0.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz     | 2         | 0.7%    |
| Intel Core i5-6500 CPU @ 3.20GHz      | 2         | 0.7%    |
| Intel Core i5-4590 CPU @ 3.30GHz      | 2         | 0.7%    |
| Intel Core i5-4570 CPU @ 3.20GHz      | 2         | 0.7%    |
| Intel Core i5-4200U CPU @ 1.60GHz     | 2         | 0.7%    |
| Intel Core i5-10210U CPU @ 1.60GHz    | 2         | 0.7%    |
| Intel Core i3-7100U CPU @ 2.40GHz     | 2         | 0.7%    |
| Intel Core i3-4010U CPU @ 1.70GHz     | 2         | 0.7%    |
| Intel Core i3-4005U CPU @ 1.70GHz     | 2         | 0.7%    |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz | 2         | 0.7%    |
| Intel Core 2 Quad CPU                 | 2         | 0.7%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz  | 2         | 0.7%    |
| Intel Celeron N4020 CPU @ 1.10GHz     | 2         | 0.7%    |
| Intel Celeron CPU J3160 @ 1.60GHz     | 2         | 0.7%    |
| Intel Atom CPU D525 @ 1.80GHz         | 2         | 0.7%    |
| AMD Ryzen 5 3600 6-Core Processor     | 2         | 0.7%    |
| AMD G-T40E Processor                  | 2         | 0.7%    |
| AMD EPYC 3201 8-Core Processor        | 2         | 0.7%    |
| AMD Athlon 5350 APU with Radeon R3    | 2         | 0.7%    |
| PowerPC 7447A (Revision 0x105)        | 1         | 0.35%   |
| Intel Xeon W-2255 CPU @ 3.70GHz       | 1         | 0.35%   |
| Intel Xeon Silver 4214R CPU @ 2.40GHz | 1         | 0.35%   |
| Intel Xeon Silver 4208 CPU @ 2.10GHz  | 1         | 0.35%   |
| Intel Xeon E-2124G CPU @ 3.40GHz      | 1         | 0.35%   |
| Intel Xeon D-2187NT CPU @ 2.00GHz     | 1         | 0.35%   |
| Intel Xeon D-2146NT CPU @ 2.30GHz     | 1         | 0.35%   |
| Intel Xeon D-2141I CPU @ 2.20GHz      | 1         | 0.35%   |
| Intel Xeon CPU X3430 @ 2.40GHz        | 1         | 0.35%   |
| Intel Xeon CPU X3210 @ 2.13GHz        | 1         | 0.35%   |
| Intel Xeon CPU W3530 @ 2.80GHz        | 1         | 0.35%   |
| Intel Xeon CPU E5504 @ 2.00GHz        | 1         | 0.35%   |
| Intel Xeon CPU E5503 @ 2.00GHz        | 1         | 0.35%   |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz    | 1         | 0.35%   |
| Intel Xeon CPU E5-2430L v2 @ 2.40GHz  | 1         | 0.35%   |
| Intel Xeon CPU E31260L @ 2.40GHz      | 1         | 0.35%   |
| Intel Xeon CPU E31220 @ 3.10GHz       | 1         | 0.35%   |
| Intel Xeon CPU E3-1275 V2 @ 3.50GHz   | 1         | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 61        | 21.33%  |
| Intel Celeron           | 36        | 12.59%  |
| Intel Core i7           | 34        | 11.89%  |
| Intel Xeon              | 26        | 9.09%   |
| Intel Core i3           | 24        | 8.39%   |
| Intel Atom              | 16        | 5.59%   |
| AMD GX                  | 16        | 5.59%   |
| AMD Ryzen 7             | 9         | 3.15%   |
| Intel Core 2 Duo        | 8         | 2.8%    |
| AMD Ryzen 5             | 8         | 2.8%    |
| Other                   | 6         | 2.1%    |
| Intel Core 2 Quad       | 6         | 2.1%    |
| Intel Pentium           | 5         | 1.75%   |
| AMD Ryzen 7 PRO         | 3         | 1.05%   |
| AMD EPYC                | 3         | 1.05%   |
| Intel Xeon Silver       | 2         | 0.7%    |
| Intel Pentium Gold      | 2         | 0.7%    |
| AMD Opteron             | 2         | 0.7%    |
| AMD G                   | 2         | 0.7%    |
| AMD E1                  | 2         | 0.7%    |
| AMD Athlon 64 X2        | 2         | 0.7%    |
| AMD Athlon              | 2         | 0.7%    |
| AMD A8                  | 2         | 0.7%    |
| Intel Pentium Dual-Core | 1         | 0.35%   |
| Intel Core M            | 1         | 0.35%   |
| AMD Ryzen 9             | 1         | 0.35%   |
| AMD Ryzen 3             | 1         | 0.35%   |
| AMD Phenom II X4        | 1         | 0.35%   |
| AMD FX                  | 1         | 0.35%   |
| AMD A6                  | 1         | 0.35%   |
| AMD A4                  | 1         | 0.35%   |
| AMD A10                 | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 123       | 43.16%  |
| 2       | 98        | 34.39%  |
| 8       | 15        | 5.26%   |
| Unknown | 14        | 4.91%   |
| 16      | 11        | 3.86%   |
| 6       | 10        | 3.51%   |
| 12      | 8         | 2.81%   |
| 1       | 2         | 0.7%    |
| 64      | 1         | 0.35%   |
| 32      | 1         | 0.35%   |
| 24      | 1         | 0.35%   |
| 10      | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 270       | 95.41%  |
| 2       | 6         | 2.12%   |
| Unknown | 6         | 2.12%   |
| 4       | 1         | 0.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 146       | 51.41%  |
| 2       | 123       | 43.31%  |
| Unknown | 15        | 5.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 42        | 14.74%  |
| Haswell       | 27        | 9.47%   |
| IvyBridge     | 24        | 8.42%   |
| SandyBridge   | 23        | 8.07%   |
| Skylake       | 22        | 7.72%   |
| Silvermont    | 20        | 7.02%   |
| Puma          | 15        | 5.26%   |
| Penryn        | 13        | 4.56%   |
| Broadwell     | 10        | 3.51%   |
| Zen 2         | 8         | 2.81%   |
| Goldmont      | 8         | 2.81%   |
| Bonnell       | 8         | 2.81%   |
| Unknown       | 8         | 2.81%   |
| Goldmont plus | 7         | 2.46%   |
| Zen+          | 6         | 2.11%   |
| Zen           | 6         | 2.11%   |
| Westmere      | 6         | 2.11%   |
| Nehalem       | 6         | 2.11%   |
| Jaguar        | 5         | 1.75%   |
| Core          | 5         | 1.75%   |
| Zen 3         | 3         | 1.05%   |
| Piledriver    | 3         | 1.05%   |
| Bobcat        | 3         | 1.05%   |
| Excavator     | 2         | 0.7%    |
| Steamroller   | 1         | 0.35%   |
| K8 Hammer     | 1         | 0.35%   |
| K10 Llano     | 1         | 0.35%   |
| K10           | 1         | 0.35%   |
| CometLake     | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 163       | 59.49%  |
| Nvidia                     | 42        | 15.33%  |
| AMD                        | 42        | 15.33%  |
| Matrox Electronics Systems | 18        | 6.57%   |
| ASPEED Technology          | 9         | 3.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 4.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 4.32%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 3.6%    |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 9         | 3.24%   |
| Intel HD Graphics 620                                                                    | 9         | 3.24%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 9         | 3.24%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 2.88%   |
| Intel HD Graphics 530                                                                    | 7         | 2.52%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 2.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 2.52%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 2.16%   |
| Intel HD Graphics 5500                                                                   | 6         | 2.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 1.8%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.8%    |
| Intel HD Graphics 500                                                                    | 5         | 1.8%    |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 1.44%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.44%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4         | 1.44%   |
| Intel HD Graphics 510                                                                    | 4         | 1.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.44%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 1.44%   |
| AMD ES1000                                                                               | 4         | 1.44%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 1.08%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 1.08%   |
| Matrox Electronics Systems MGA G200EH                                                    | 3         | 1.08%   |
| Matrox Electronics Systems G200eR2                                                       | 3         | 1.08%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.08%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 3         | 1.08%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 3         | 1.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.08%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 3         | 1.08%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 1.08%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 3         | 1.08%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 2         | 0.72%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 2         | 0.72%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.72%   |
| Intel HD Graphics 630                                                                    | 2         | 0.72%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 2         | 0.72%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 0.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.72%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.72%   |
| AMD Renoir                                                                               | 2         | 0.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.72%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2         | 0.72%   |
| AMD Lucienne                                                                             | 2         | 0.72%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                                  | 2         | 0.72%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 0.72%   |
| AMD Cezanne                                                                              | 2         | 0.72%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.36%   |
| Nvidia TU117M                                                                            | 1         | 0.36%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.36%   |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1         | 0.36%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.36%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.36%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.36%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 0.36%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.36%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 0.36%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.36%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 141       | 49.47%  |
| 1 x AMD         | 38        | 13.33%  |
| 1 x Nvidia      | 29        | 10.18%  |
| Other           | 26        | 9.12%   |
| 1 x Matrox      | 18        | 6.32%   |
| Intel + Nvidia  | 11        | 3.86%   |
| 2 x Intel       | 9         | 3.16%   |
| 1 x ASPEED      | 8         | 2.81%   |
| Intel + AMD     | 2         | 0.7%    |
| 2 x AMD         | 1         | 0.35%   |
| Nvidia + ASPEED | 1         | 0.35%   |
| AMD + Nvidia    | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 233       | 81.47%  |
| Unknown     | 32        | 11.19%  |
| Proprietary | 21        | 7.34%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 251       | 88.38%  |
| 1.01-2.0   | 7         | 2.46%   |
| 0.51-1.0   | 7         | 2.46%   |
| 0.01-0.5   | 7         | 2.46%   |
| 7.01-8.0   | 6         | 2.11%   |
| 5.01-6.0   | 4         | 1.41%   |
| 3.01-4.0   | 1         | 0.35%   |
| 8.01-16.0  | 1         | 0.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 17        | 14.78%  |
| LG Display              | 13        | 11.3%   |
| Chimei Innolux          | 13        | 11.3%   |
| Dell                    | 9         | 7.83%   |
| Samsung Electronics     | 8         | 6.96%   |
| BOE                     | 7         | 6.09%   |
| Iiyama                  | 6         | 5.22%   |
| Hewlett-Packard         | 5         | 4.35%   |
| Philips                 | 4         | 3.48%   |
| Goldstar                | 4         | 3.48%   |
| Chi Mei Optoelectronics | 4         | 3.48%   |
| Idek Iiyama             | 3         | 2.61%   |
| BenQ                    | 3         | 2.61%   |
| Apple                   | 3         | 2.61%   |
| Ancor Communications    | 3         | 2.61%   |
| Lenovo                  | 2         | 1.74%   |
| Sony                    | 1         | 0.87%   |
| PRI                     | 1         | 0.87%   |
| Packard Bell            | 1         | 0.87%   |
| Nvidia                  | 1         | 0.87%   |
| LG Electronics          | 1         | 0.87%   |
| IBM                     | 1         | 0.87%   |
| CSO                     | 1         | 0.87%   |
| CPT                     | 1         | 0.87%   |
| CKL                     | 1         | 0.87%   |
| AOC                     | 1         | 0.87%   |
| Acer                    | 1         | 0.87%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 3         | 2.61%   |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch                 | 2         | 1.74%   |
| Iiyama PL2474H IVM6137 1920x1080 520x290mm 23.4-inch                     | 2         | 1.74%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 280x160mm 12.7-inch         | 2         | 1.74%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 1.74%   |
| BenQ EW3270U BNQ7950 3840x2160 700x390mm 31.5-inch                       | 2         | 1.74%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch           | 2         | 1.74%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 2         | 1.74%   |
| Sony TV  *00 SNYF903 3840x2160 950x540mm 43.0-inch                       | 1         | 0.87%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 410x260mm 19.1-inch      | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SyncMaster 3520x1200                     | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch    | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch     | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 310x170mm 13.9-inch     | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 0.87%   |
| Samsung Electronics LCD Monitor S24R35x 1920x1080                        | 1         | 0.87%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 1         | 0.87%   |
| PRI LED-MONITOR PRI0828 3840x2160 1150x650mm 52.0-inch                   | 1         | 0.87%   |
| Philips PHL 439P1 PHL0973 3840x2160 940x530mm 42.5-inch                  | 1         | 0.87%   |
| Philips LCD Monitor PHLC00B 1280x1024 340x270mm 17.1-inch                | 1         | 0.87%   |
| Packard Bell Viseo 200Ws PKB00C2 1600x900 440x250mm 19.9-inch            | 1         | 0.87%   |
| Nvidia LCD Monitor Default Flat Panel 1440x900                           | 1         | 0.87%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                        | 1         | 0.87%   |
| LG Display LCD Monitor LGD7001 1366x768 340x190mm 15.3-inch              | 1         | 0.87%   |
| LG Display LCD Monitor LGD063F 1920x1080 380x210mm 17.1-inch             | 1         | 0.87%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 0.87%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch             | 1         | 0.87%   |
| LG Display LCD Monitor LGD0438 1366x768 340x190mm 15.3-inch              | 1         | 0.87%   |
| LG Display LCD Monitor LGD03EE 1366x768 280x160mm 12.7-inch              | 1         | 0.87%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 0.87%   |
| LG Display LCD Monitor LGD03A3 1366x768 280x160mm 12.7-inch              | 1         | 0.87%   |
| LG Display LCD Monitor LGD0390 1600x900 380x210mm 17.1-inch              | 1         | 0.87%   |
| LG Display LCD Monitor LGD036C 1366x768 280x160mm 12.7-inch              | 1         | 0.87%   |
| LG Display LCD Monitor LGD0366 1600x900 310x170mm 13.9-inch              | 1         | 0.87%   |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch              | 1         | 0.87%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 0.87%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 340x190mm 15.3-inch                 | 1         | 0.87%   |
| Lenovo LCD Monitor LEN4031 1280x800 290x180mm 13.4-inch                  | 1         | 0.87%   |
| Iiyama PLX2783H IVM6611 1920x1080 600x340mm 27.2-inch                    | 1         | 0.87%   |
| Iiyama PLX2483H IVM6114 1920x1080 530x300mm 24.0-inch                    | 1         | 0.87%   |
| Iiyama PL2783Q IVM661F 2560x1440 600x340mm 27.2-inch                     | 1         | 0.87%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                     | 1         | 0.87%   |
| Idek Iiyama LCD Monitor PLX2783H 1920x1080                               | 1         | 0.87%   |
| Idek Iiyama LCD Monitor PL2409HD 1920x1080                               | 1         | 0.87%   |
| Idek Iiyama LCD Monitor PL2206W 1680x1050                                | 1         | 0.87%   |
| IBM LCD Monitor IBM2887 1680x1050 330x210mm 15.4-inch                    | 1         | 0.87%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 470x300mm 22.0-inch              | 1         | 0.87%   |
| Hewlett-Packard M27f FHD HPN370A 1920x1080 610x360mm 27.9-inch           | 1         | 0.87%   |
| Hewlett-Packard HPQ 8300 AiO HWP4212 1920x1080 510x290mm 23.1-inch       | 1         | 0.87%   |
| Hewlett-Packard 2310e HWP2909 1920x1080 510x290mm 23.1-inch              | 1         | 0.87%   |
| Hewlett-Packard 2211 HWP2938 1920x1080 480x270mm 21.7-inch               | 1         | 0.87%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 1         | 0.87%   |
| Goldstar L1730S GSM438D 1280x1024 340x270mm 17.1-inch                    | 1         | 0.87%   |
| Goldstar 27GK750F GSM770F 1920x1080 600x340mm 27.2-inch                  | 1         | 0.87%   |
| Goldstar 19MB35 GSM4C23 1280x1024 380x300mm 19.1-inch                    | 1         | 0.87%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                        | 1         | 0.87%   |
| Dell P2418D DELD0C2 2560x1440 530x300mm 24.0-inch                        | 1         | 0.87%   |
| Dell P1917S DELD092 1280x1024 380x300mm 19.1-inch                        | 1         | 0.87%   |
| Dell P1917S DELD091 1280x1024 380x300mm 19.1-inch                        | 1         | 0.87%   |
| Dell P1911 DELA073 1440x900 410x260mm 19.1-inch                          | 1         | 0.87%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 49        | 43.75%  |
| 1366x768 (WXGA)    | 26        | 23.21%  |
| 3840x2160 (4K)     | 7         | 6.25%   |
| 1280x1024 (SXGA)   | 6         | 5.36%   |
| 2560x1440 (QHD)    | 4         | 3.57%   |
| 1600x900 (HD+)     | 4         | 3.57%   |
| 1280x800 (WXGA)    | 4         | 3.57%   |
| 1680x1050 (WSXGA+) | 3         | 2.68%   |
| 1440x900 (WXGA+)   | 3         | 2.68%   |
| 3520x1200          | 1         | 0.89%   |
| 2560x1080          | 1         | 0.89%   |
| 1920x1200 (WUXGA)  | 1         | 0.89%   |
| 1440x960           | 1         | 0.89%   |
| 1024x600           | 1         | 0.89%   |
| Unknown            | 1         | 0.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 24        | 21.05%  |
| 13      | 20        | 17.54%  |
| 12      | 12        | 10.53%  |
| 23      | 8         | 7.02%   |
| 17      | 8         | 7.02%   |
| 19      | 7         | 6.14%   |
| Unknown | 7         | 6.14%   |
| 27      | 6         | 5.26%   |
| 24      | 6         | 5.26%   |
| 21      | 4         | 3.51%   |
| 52      | 2         | 1.75%   |
| 31      | 2         | 1.75%   |
| 10      | 2         | 1.75%   |
| 43      | 1         | 0.88%   |
| 42      | 1         | 0.88%   |
| 22      | 1         | 0.88%   |
| 18      | 1         | 0.88%   |
| 14      | 1         | 0.88%   |
| 11      | 1         | 0.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 44        | 38.6%   |
| 501-600     | 19        | 16.67%  |
| 201-300     | 19        | 16.67%  |
| 401-500     | 10        | 8.77%   |
| 351-400     | 8         | 7.02%   |
| Unknown     | 7         | 6.14%   |
| 601-700     | 3         | 2.63%   |
| 1001-1500   | 2         | 1.75%   |
| 901-1000    | 2         | 1.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 82        | 78.1%   |
| 16/10   | 8         | 7.62%   |
| Unknown | 7         | 6.67%   |
| 5/4     | 6         | 5.71%   |
| 3/2     | 2         | 1.9%    |

Monitor Area
------------

Area in inch??

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch?? | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 20        | 17.54%  |
| 91-100         | 20        | 17.54%  |
| 201-250        | 18        | 15.79%  |
| 61-70          | 12        | 10.53%  |
| 151-200        | 7         | 6.14%   |
| Unknown        | 7         | 6.14%   |
| 301-350        | 6         | 5.26%   |
| 121-130        | 5         | 4.39%   |
| 141-150        | 4         | 3.51%   |
| 101-110        | 4         | 3.51%   |
| More than 1000 | 2         | 1.75%   |
| 351-500        | 2         | 1.75%   |
| 41-50          | 2         | 1.75%   |
| 501-1000       | 2         | 1.75%   |
| 71-80          | 1         | 0.88%   |
| 51-60          | 1         | 0.88%   |
| 251-300        | 1         | 0.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 40        | 35.71%  |
| 101-120       | 30        | 26.79%  |
| 51-100        | 29        | 25.89%  |
| Unknown       | 7         | 6.25%   |
| 161-240       | 4         | 3.57%   |
| More than 240 | 1         | 0.89%   |
| 1-50          | 1         | 0.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 181       | 62.41%  |
| 1     | 98        | 33.79%  |
| 2     | 11        | 3.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 201       | 49.14%  |
| Realtek Semiconductor           | 107       | 26.16%  |
| Qualcomm Atheros                | 35        | 8.56%   |
| Broadcom                        | 29        | 7.09%   |
| AMD                             | 4         | 0.98%   |
| Ralink Technology               | 3         | 0.73%   |
| Qualcomm                        | 3         | 0.73%   |
| Marvell Technology Group        | 3         | 0.73%   |
| Edimax Technology               | 3         | 0.73%   |
| VIA Technologies                | 2         | 0.49%   |
| TP-Link                         | 2         | 0.49%   |
| D-Link System                   | 2         | 0.49%   |
| Chelsio Communications          | 2         | 0.49%   |
| Apple                           | 2         | 0.49%   |
| Xiaomi                          | 1         | 0.24%   |
| Ralink                          | 1         | 0.24%   |
| Qualcomm Atheros Communications | 1         | 0.24%   |
| Nvidia                          | 1         | 0.24%   |
| Microchip Technology            | 1         | 0.24%   |
| MediaTek                        | 1         | 0.24%   |
| IMC Networks                    | 1         | 0.24%   |
| Huawei Technologies             | 1         | 0.24%   |
| Dell                            | 1         | 0.24%   |
| American Megatrends             | 1         | 0.24%   |
| 3Com                            | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 92        | 17.86%  |
| Intel I211 Gigabit Network Connection                                         | 34        | 6.6%    |
| Intel I210 Gigabit Network Connection                                         | 20        | 3.88%   |
| Intel 82574L Gigabit Network Connection                                       | 18        | 3.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 13        | 2.52%   |
| Intel Wi-Fi 6 AX200                                                           | 11        | 2.14%   |
| Intel Wireless 7265                                                           | 9         | 1.75%   |
| Intel I350 Gigabit Network Connection                                         | 9         | 1.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 8         | 1.55%   |
| Intel Wireless 8265 / 8275                                                    | 8         | 1.55%   |
| Realtek RTL8125 2.5GbE Controller                                             | 7         | 1.36%   |
| Intel Ethernet Connection I217-LM                                             | 7         | 1.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 7         | 1.36%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 7         | 1.36%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 7         | 1.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 6         | 1.17%   |
| Intel Wireless 7260                                                           | 6         | 1.17%   |
| Intel Wireless 3165                                                           | 6         | 1.17%   |
| Intel Ethernet Connection (6) I219-V                                          | 6         | 1.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 6         | 1.17%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 6         | 1.17%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 5         | 0.97%   |
| Intel 82579V Gigabit Network Connection                                       | 5         | 0.97%   |
| Intel 82576 Gigabit Network Connection                                        | 5         | 0.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4         | 0.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 4         | 0.78%   |
| Intel Wireless 8260                                                           | 4         | 0.78%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 4         | 0.78%   |
| Intel Ethernet Connection (4) I219-V                                          | 4         | 0.78%   |
| Intel Ethernet Connection (3) I218-LM                                         | 4         | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 4         | 0.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 4         | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 3         | 0.58%   |
| Qualcomm ALCATEL Composite RNDIS Interface                                    | 3         | 0.58%   |
| Intel Wireless-AC 9260                                                        | 3         | 0.58%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 3         | 0.58%   |
| Intel Ethernet Controller I225-V                                              | 3         | 0.58%   |
| Intel Ethernet Connection X553 1GbE                                           | 3         | 0.58%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 0.58%   |
| Intel Ethernet Connection (7) I219-V                                          | 3         | 0.58%   |
| Intel Ethernet Connection (4) I219-LM                                         | 3         | 0.58%   |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3         | 0.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 3         | 0.58%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3         | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3         | 0.58%   |
| Intel 82567LM Gigabit Network Connection                                      | 3         | 0.58%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 3         | 0.58%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 3         | 0.58%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 3         | 0.58%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 2         | 0.39%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2         | 0.39%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2         | 0.39%   |
| Ralink RT5370 Wireless Adapter                                                | 2         | 0.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2         | 0.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 2         | 0.39%   |
| Intel Ethernet Controller X550                                                | 2         | 0.39%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 2         | 0.39%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 2         | 0.39%   |
| Intel Ethernet Connection I218-LM                                             | 2         | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 85        | 58.22%  |
| Qualcomm Atheros                | 30        | 20.55%  |
| Realtek Semiconductor           | 12        | 8.22%   |
| Broadcom                        | 6         | 4.11%   |
| Ralink Technology               | 3         | 2.05%   |
| Edimax Technology               | 3         | 2.05%   |
| TP-Link                         | 2         | 1.37%   |
| Ralink                          | 1         | 0.68%   |
| Qualcomm Atheros Communications | 1         | 0.68%   |
| MediaTek                        | 1         | 0.68%   |
| IMC Networks                    | 1         | 0.68%   |
| Dell                            | 1         | 0.68%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 11        | 7.48%   |
| Intel Wireless 7265                                                     | 9         | 6.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 5.44%   |
| Intel Wireless 8265 / 8275                                              | 8         | 5.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 4.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 4.08%   |
| Intel Wireless 7260                                                     | 6         | 4.08%   |
| Intel Wireless 3165                                                     | 6         | 4.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 4.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 5         | 3.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.72%   |
| Intel Wireless 8260                                                     | 4         | 2.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 2.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 2.72%   |
| Intel Wireless-AC 9260                                                  | 3         | 2.04%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 2.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 2.04%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 3         | 2.04%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 1.36%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 1.36%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 1.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 1.36%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.36%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.36%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.36%   |
| TP-Link TP-Link Wireless MU-MIMO USB Adapter                            | 1         | 0.68%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 0.68%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 0.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.68%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.68%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                  | 1         | 0.68%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.68%   |
| Realtek Realtek 8811CU Wireless LAN 802.11ac USB NIC                    | 1         | 0.68%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.68%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.68%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.68%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter         | 1         | 0.68%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.68%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.68%   |
| MediaTek 802.11ac Wireless LAN Card                                     | 1         | 0.68%   |
| Intel Wireless 3160                                                     | 1         | 0.68%   |
| Intel WiFi Link 5100                                                    | 1         | 0.68%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 0.68%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.68%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 0.68%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 0.68%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 1         | 0.68%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 1         | 0.68%   |
| Dell Hub of E-Port Replicator                                           | 1         | 0.68%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 1         | 0.68%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 0.68%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 1         | 0.68%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 165       | 51.56%  |
| Realtek Semiconductor    | 101       | 31.56%  |
| Broadcom                 | 25        | 7.81%   |
| Qualcomm Atheros         | 8         | 2.5%    |
| AMD                      | 4         | 1.25%   |
| Qualcomm                 | 3         | 0.94%   |
| Marvell Technology Group | 3         | 0.94%   |
| VIA Technologies         | 2         | 0.63%   |
| D-Link System            | 2         | 0.63%   |
| Chelsio Communications   | 2         | 0.63%   |
| Xiaomi                   | 1         | 0.31%   |
| Nvidia                   | 1         | 0.31%   |
| Apple                    | 1         | 0.31%   |
| American Megatrends      | 1         | 0.31%   |
| 3Com                     | 1         | 0.31%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 92        | 25.34%  |
| Intel I211 Gigabit Network Connection                                         | 34        | 9.37%   |
| Intel I210 Gigabit Network Connection                                         | 20        | 5.51%   |
| Intel 82574L Gigabit Network Connection                                       | 18        | 4.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 13        | 3.58%   |
| Intel I350 Gigabit Network Connection                                         | 9         | 2.48%   |
| Realtek RTL8125 2.5GbE Controller                                             | 7         | 1.93%   |
| Intel Ethernet Connection I217-LM                                             | 7         | 1.93%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 7         | 1.93%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 7         | 1.93%   |
| Intel Ethernet Connection (6) I219-V                                          | 6         | 1.65%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 6         | 1.65%   |
| Intel 82579V Gigabit Network Connection                                       | 5         | 1.38%   |
| Intel 82576 Gigabit Network Connection                                        | 5         | 1.38%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4         | 1.1%    |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 4         | 1.1%    |
| Intel Ethernet Connection (4) I219-V                                          | 4         | 1.1%    |
| Intel Ethernet Connection (3) I218-LM                                         | 4         | 1.1%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 3         | 0.83%   |
| Qualcomm ALCATEL Composite RNDIS Interface                                    | 3         | 0.83%   |
| Intel Ethernet Controller I225-V                                              | 3         | 0.83%   |
| Intel Ethernet Connection X553 1GbE                                           | 3         | 0.83%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 0.83%   |
| Intel Ethernet Connection (7) I219-V                                          | 3         | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                                         | 3         | 0.83%   |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3         | 0.83%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3         | 0.83%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3         | 0.83%   |
| Intel 82567LM Gigabit Network Connection                                      | 3         | 0.83%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 3         | 0.83%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 3         | 0.83%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2         | 0.55%   |
| Intel Ethernet Controller X550                                                | 2         | 0.55%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 2         | 0.55%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 2         | 0.55%   |
| Intel Ethernet Connection I218-LM                                             | 2         | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2         | 0.55%   |
| Intel Ethernet Connection (5) I219-LM                                         | 2         | 0.55%   |
| Intel 82583V Gigabit Network Connection                                       | 2         | 0.55%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 2         | 0.55%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 2         | 0.55%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 2         | 0.55%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                       | 2         | 0.55%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 2         | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1         | 0.28%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 1         | 0.28%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1         | 0.28%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.28%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 0.28%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1         | 0.28%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1         | 0.28%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 0.28%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.28%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 1         | 0.28%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                       | 1         | 0.28%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                       | 1         | 0.28%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 1         | 0.28%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 1         | 0.28%   |
| Intel Ethernet Controller I225-LM                                             | 1         | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 275       | 66.27%  |
| WiFi     | 135       | 32.53%  |
| Unknown  | 3         | 0.72%   |
| Modem    | 2         | 0.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 247       | 78.41%  |
| WiFi     | 68        | 21.59%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 124       | 43.51%  |
| 1     | 53        | 18.6%   |
| 4     | 42        | 14.74%  |
| 3     | 33        | 11.58%  |
| 5     | 9         | 3.16%   |
| 6     | 8         | 2.81%   |
| 8     | 4         | 1.4%    |
| 7     | 4         | 1.4%    |
| 12    | 2         | 0.7%    |
| 14    | 1         | 0.35%   |
| 13    | 1         | 0.35%   |
| 11    | 1         | 0.35%   |
| 10    | 1         | 0.35%   |
| 9     | 1         | 0.35%   |
| 0     | 1         | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 239       | 80.2%   |
| Yes  | 59        | 19.8%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 56        | 67.47%  |
| Broadcom                        | 8         | 9.64%   |
| IMC Networks                    | 6         | 7.23%   |
| Apple                           | 4         | 4.82%   |
| Foxconn / Hon Hai               | 2         | 2.41%   |
| Dell                            | 2         | 2.41%   |
| Cambridge Silicon Radio         | 2         | 2.41%   |
| Realtek Semiconductor           | 1         | 1.2%    |
| Qualcomm Atheros Communications | 1         | 1.2%    |
| HTC (High Tech Computer)        | 1         | 1.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 23        | 27.71%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 9         | 10.84%  |
| Intel AX200 Bluetooth                                                | 9         | 10.84%  |
| Intel AX201 Bluetooth                                                | 5         | 6.02%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                          | 4         | 4.82%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 3         | 3.61%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 3         | 3.61%   |
| Apple Bluetooth Host Controller                                      | 3         | 3.61%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2         | 2.41%   |
| Intel AX210 Bluetooth                                                | 2         | 2.41%   |
| Foxconn / Hon Hai Bluetooth USB Module                               | 2         | 2.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 2         | 2.41%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2         | 2.41%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 2         | 2.41%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 2         | 2.41%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1         | 1.2%    |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                              | 1         | 1.2%    |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS                     | 1         | 1.2%    |
| IMC Networks Bluetooth Radio                                         | 1         | 1.2%    |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 1.2%    |
| Dell DW375 Bluetooth Module                                          | 1         | 1.2%    |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                          | 1         | 1.2%    |
| Broadcom BCM43142A0 Bluetooth Module                                 | 1         | 1.2%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                   | 1         | 1.2%    |
| Apple Built-in iSight (no firmware loaded)                           | 1         | 1.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 162       | 63.28%  |
| AMD                                          | 44        | 17.19%  |
| Nvidia                                       | 29        | 11.33%  |
| C-Media Electronics                          | 3         | 1.17%   |
| Lenovo                                       | 2         | 0.78%   |
| GN Netcom                                    | 2         | 0.78%   |
| Focusrite-Novation                           | 2         | 0.78%   |
| Creative Labs                                | 2         | 0.78%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.39%   |
| VIA Technologies                             | 1         | 0.39%   |
| Texas Instruments                            | 1         | 0.39%   |
| Sony                                         | 1         | 0.39%   |
| Micronas                                     | 1         | 0.39%   |
| Logitech                                     | 1         | 0.39%   |
| Kingston Technology                          | 1         | 0.39%   |
| iCreate Technologies                         | 1         | 0.39%   |
| Giga-Byte Technology                         | 1         | 0.39%   |
| DSEA A/S                                     | 1         | 0.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 18        | 5.83%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 5.5%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 4.85%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 4.21%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 3.88%   |
| AMD FCH Azalia Controller                                                                         | 10        | 3.24%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 2.91%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 2.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 2.91%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 2.91%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 2.59%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 2.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 2.27%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 2.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 2.27%   |
| Intel 200 Series PCH HD Audio                                                                     | 7         | 2.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 2.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7         | 2.27%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 1.94%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 1.62%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 1.62%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.62%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 1.62%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.62%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.29%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 1.29%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.97%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 0.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 0.97%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 0.97%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.97%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.97%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 0.97%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.65%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.65%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 2         | 0.65%   |
| Lenovo Realtek USB Audio                                                                          | 2         | 0.65%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.65%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 0.65%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.65%   |
| GN Netcom Jabra Speak 710                                                                         | 2         | 0.65%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 0.65%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 0.65%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 0.65%   |
| Unknown                                                                                           | 2         | 0.65%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1         | 0.32%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.32%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.32%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1         | 0.32%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.32%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.32%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.32%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.32%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.32%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.32%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.32%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.32%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 56        | 20.36%  |
| Unknown             | 36        | 13.09%  |
| SK hynix            | 35        | 12.73%  |
| Kingston            | 29        | 10.55%  |
| Crucial             | 25        | 9.09%   |
| Corsair             | 23        | 8.36%   |
| Micron Technology   | 19        | 6.91%   |
| G.Skill             | 14        | 5.09%   |
| Unknown (ABCD)      | 6         | 2.18%   |
| Transcend           | 6         | 2.18%   |
| Nanya Technology    | 5         | 1.82%   |
| Elpida              | 4         | 1.45%   |
| A-DATA Technology   | 3         | 1.09%   |
| Patriot             | 2         | 0.73%   |
| Atermiter           | 2         | 0.73%   |
| V-Color             | 1         | 0.36%   |
| Teikon              | 1         | 0.36%   |
| SHARETRONIC         | 1         | 0.36%   |
| OCZ                 | 1         | 0.36%   |
| Kimtigo             | 1         | 0.36%   |
| Hewlett-Packard     | 1         | 0.36%   |
| Goldenmars          | 1         | 0.36%   |
| CSX                 | 1         | 0.36%   |
| Avant               | 1         | 0.36%   |
| Apacer              | 1         | 0.36%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown                                                           | 36        | 12.33%  |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s | 6         | 2.05%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s             | 4         | 1.37%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s            | 3         | 1.03%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 3         | 1.03%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s            | 3         | 1.03%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 3         | 1.03%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 3         | 1.03%   |
| Samsung RAM M393A4K40CB2-CTD 32GB DIMM DDR4 2667MT/s              | 3         | 1.03%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s               | 2         | 0.68%   |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s              | 2         | 0.68%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s             | 2         | 0.68%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 2         | 0.68%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s            | 2         | 0.68%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 1600MT/s               | 2         | 0.68%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s               | 2         | 0.68%   |
| Micron RAM 8HTF12864AZ-800H1 1GB DIMM DDR2 800MT/s                | 2         | 0.68%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s               | 2         | 0.68%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s             | 2         | 0.68%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3200MT/s              | 2         | 0.68%   |
| Elpida RAM Module 4096MB SODIMM DDR3 1600MT/s                     | 2         | 0.68%   |
| Crucial RAM CT51264BF160BJ.M8F 4GB DIMM DDR3 1600MT/s             | 2         | 0.68%   |
| Crucial RAM CT204864BF160B.C16 16GB SODIMM DDR3 1600MT/s          | 2         | 0.68%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s           | 2         | 0.68%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s           | 2         | 0.68%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s               | 2         | 0.68%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1333MT/s               | 2         | 0.68%   |
| Atermiter RAM Module 8GB DIMM DDR3 800MT/s                        | 2         | 0.68%   |
| A-DATA RAM AO1P32NCST2-BZ6SHD 16384MB SODIMM DDR4 3200MT/s        | 2         | 0.68%   |
| V-Color RAM TN48G24S817-VHA/R 8GB SODIMM DDR4 2400MT/s            | 1         | 0.34%   |
| Transcend RAM TS512MSK64V3H 4GB SODIMM DDR3 667MT/s               | 1         | 0.34%   |
| Transcend RAM TS1GLK72V6H 8GB DIMM DDR3 1600MT/s                  | 1         | 0.34%   |
| Transcend RAM TS1GLH64V1H 8GB DIMM DDR4 2133MT/s                  | 1         | 0.34%   |
| Transcend RAM TS1GKR72V3H 8GB DIMM DDR3 1333MT/s                  | 1         | 0.34%   |
| Teikon RAM TMTS8G58DFRBFIR-16 8GB SODIMM DDR3 1600MT/s            | 1         | 0.34%   |
| SK hynix RAM Module 4GB DIMM DDR3 1066MT/s                        | 1         | 0.34%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 0.34%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s             | 1         | 0.34%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s              | 1         | 0.34%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s              | 1         | 0.34%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 0.34%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 0.34%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB DDR3 1600MT/s                   | 1         | 0.34%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 1         | 0.34%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 1         | 0.34%   |
| SK hynix RAM HMT351U7CFR8C-H9 4GB DIMM DDR3 1333MT/s              | 1         | 0.34%   |
| SK hynix RAM HMT351U7CFR8A-H9 4GB DIMM DDR3 1333MT/s              | 1         | 0.34%   |
| SK hynix RAM HMT351U7BFR8A-H9 4GB DIMM DDR3 1333MT/s              | 1         | 0.34%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 1         | 0.34%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 0.34%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 1         | 0.34%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s            | 1         | 0.34%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s              | 1         | 0.34%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s              | 1         | 0.34%   |
| SK hynix RAM HMP125U6EFR8C-S6 2GB DIMM DDR2 800MT/s               | 1         | 0.34%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s           | 1         | 0.34%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 1         | 0.34%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 2400MT/s            | 1         | 0.34%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s           | 1         | 0.34%   |
| SK hynix RAM HMA82GR7DJR8N-XN 16GB DIMM DDR4 3200MT/s             | 1         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 126       | 51.85%  |
| DDR4    | 84        | 34.57%  |
| Unknown | 12        | 4.94%   |
| DDR2    | 11        | 4.53%   |
| LPDDR4  | 6         | 2.47%   |
| LPDDR3  | 4         | 1.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 130       | 53.5%   |
| SODIMM       | 109       | 44.86%  |
| Unknown      | 2         | 0.82%   |
| Row Of Chips | 1         | 0.41%   |
| Chip         | 1         | 0.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 90        | 34.88%  |
| 8192  | 83        | 32.17%  |
| 16384 | 37        | 14.34%  |
| 2048  | 33        | 12.79%  |
| 1024  | 8         | 3.1%    |
| 32768 | 6         | 2.33%   |
| 32767 | 1         | 0.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 77        | 30.56%  |
| 1333    | 43        | 17.06%  |
| 2400    | 29        | 11.51%  |
| 2667    | 25        | 9.92%   |
| 3200    | 19        | 7.54%   |
| 2133    | 12        | 4.76%   |
| 800     | 11        | 4.37%   |
| 1334    | 7         | 2.78%   |
| 667     | 5         | 1.98%   |
| 1867    | 4         | 1.59%   |
| 1066    | 4         | 1.59%   |
| 2666    | 3         | 1.19%   |
| 533     | 2         | 0.79%   |
| Unknown | 2         | 0.79%   |
| 5200    | 1         | 0.4%    |
| 2933    | 1         | 0.4%    |
| 1866    | 1         | 0.4%    |
| 1400    | 1         | 0.4%    |
| 1332    | 1         | 0.4%    |
| 1200    | 1         | 0.4%    |
| 1067    | 1         | 0.4%    |
| 975     | 1         | 0.4%    |
| 400     | 1         | 0.4%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Dymo-CoStar | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seiko Epson Printer                  | 1         | 50%     |
| Dymo-CoStar DYMO LabelWriter 450 DUO | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 23        | 32.39%  |
| Sunplus Innovation Technology          | 8         | 11.27%  |
| Realtek Semiconductor                  | 6         | 8.45%   |
| Acer                                   | 6         | 8.45%   |
| IMC Networks                           | 5         | 7.04%   |
| Microdia                               | 4         | 5.63%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.23%   |
| Syntek                                 | 2         | 2.82%   |
| Logitech                               | 2         | 2.82%   |
| Lite-On Technology                     | 2         | 2.82%   |
| ARC International                      | 2         | 2.82%   |
| Alcor Micro                            | 2         | 2.82%   |
| Suyin                                  | 1         | 1.41%   |
| Sonix Technology                       | 1         | 1.41%   |
| Quanta                                 | 1         | 1.41%   |
| Novatek Microelectronics               | 1         | 1.41%   |
| Linux Foundation                       | 1         | 1.41%   |
| Apple                                  | 1         | 1.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 8         | 11.27%  |
| Sunplus Integrated_Webcam_HD                                               | 5         | 7.04%   |
| Acer Integrated Camera                                                     | 3         | 4.23%   |
| Realtek USB Camera                                                         | 2         | 2.82%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 2.82%   |
| Microdia Integrated_Webcam_HD                                              | 2         | 2.82%   |
| IMC Networks EasyCamera                                                    | 2         | 2.82%   |
| Chicony HD WebCam                                                          | 2         | 2.82%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 2         | 2.82%   |
| ARC International Camera                                                   | 2         | 2.82%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.41%   |
| Syntek Integrated Camera                                                   | 1         | 1.41%   |
| Suyin Laptop_Integrated_Webcam_FHD                                         | 1         | 1.41%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 1         | 1.41%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 1.41%   |
| Sunplus Asus Webcam                                                        | 1         | 1.41%   |
| Sonix USB 2.0 Camera                                                       | 1         | 1.41%   |
| Realtek Lenovo EasyCamera                                                  | 1         | 1.41%   |
| Realtek Integrated Webcam HD                                               | 1         | 1.41%   |
| Quanta HD WebCam                                                           | 1         | 1.41%   |
| Novatek HP High Definition 2MP Webcam                                      | 1         | 1.41%   |
| Microdia Integrated Webcam                                                 | 1         | 1.41%   |
| Microdia Dell Integrated HD Webcam                                         | 1         | 1.41%   |
| Logitech Webcam C270                                                       | 1         | 1.41%   |
| Logitech C922 Pro Stream Webcam                                            | 1         | 1.41%   |
| Lite-On Realtek DMFT - RGB                                                 | 1         | 1.41%   |
| Lite-On Integrated Camera                                                  | 1         | 1.41%   |
| Linux Foundation HD Camera                                                 | 1         | 1.41%   |
| IMC Networks UVC VGA Webcam                                                | 1         | 1.41%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.41%   |
| IMC Networks Integrated Camera                                             | 1         | 1.41%   |
| Chicony UVC 1.00 device HD UVC WebCam                                      | 1         | 1.41%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 1         | 1.41%   |
| Chicony USB2.0 HD UVC WebCam                                               | 1         | 1.41%   |
| Chicony ThinkPad T490 Webcam                                               | 1         | 1.41%   |
| Chicony Sonix ST50220 USB Video Camera                                     | 1         | 1.41%   |
| Chicony Ltd., USB2.0 HD UVC WebCam                                         | 1         | 1.41%   |
| Chicony Ltd., Integrated Camera                                            | 1         | 1.41%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 1         | 1.41%   |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 1.41%   |
| Chicony HP Webcam [2 MP]                                                   | 1         | 1.41%   |
| Chicony HP Webcam [2 MP Macro]                                             | 1         | 1.41%   |
| Chicony Chicony USB2.0 Camera                                              | 1         | 1.41%   |
| Chicony Chicony USB 2.0 Camera                                             | 1         | 1.41%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.41%   |
| Apple FaceTime HD Camera                                                   | 1         | 1.41%   |
| Alcor Micro USB 2.0 Camera                                                 | 1         | 1.41%   |
| Alcor Micro ASUS USB2.0 WebCam                                             | 1         | 1.41%   |
| Acer SunplusIT Integrated Camera                                           | 1         | 1.41%   |
| Acer Lenovo EasyCamera                                                     | 1         | 1.41%   |
| Acer HD Webcam                                                             | 1         | 1.41%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 37.5%   |
| Synaptics                  | 3         | 18.75%  |
| AuthenTec                  | 3         | 18.75%  |
| Upek                       | 1         | 6.25%   |
| Shenzhen Goodix Technology | 1         | 6.25%   |
| Elan Microelectronics      | 1         | 6.25%   |
| Broadcom                   | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 3         | 18.75%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 2         | 12.5%   |
| AuthenTec AES2810                                                            | 2         | 12.5%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 6.25%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 6.25%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 6.25%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 6.25%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 6.25%   |
| Elan ELAN WBF Fingerprint Sensor                                             | 1         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.25%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 1         | 6.25%   |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 112       | 37.58%  |
| 0     | 87        | 29.19%  |
| 2     | 52        | 17.45%  |
| 3     | 27        | 9.06%   |
| 4     | 14        | 4.7%    |
| 6     | 4         | 1.34%   |
| 7     | 1         | 0.34%   |
| 5     | 1         | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 168       | 51.22%  |
| Bluetooth                | 40        | 12.2%   |
| Net/wireless             | 38        | 11.59%  |
| Card reader              | 28        | 8.54%   |
| Firewire controller      | 17        | 5.18%   |
| Fingerprint reader       | 13        | 3.96%   |
| Sound                    | 7         | 2.13%   |
| Graphics card            | 5         | 1.52%   |
| Storage/raid             | 3         | 0.91%   |
| Storage                  | 3         | 0.91%   |
| Net/ethernet             | 3         | 0.91%   |
| Network                  | 2         | 0.61%   |
| Modem                    | 1         | 0.3%    |

