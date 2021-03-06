BSD in France - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for BSD in France.

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

Total: 234

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Intel         | Q3XXG4-P V1.0               | [ab2f42b567](https://bsd-hardware.info/?probe=ab2f42b567) | Jun 26, 2022 |
| Intel         | D945GCLF2 AAE46416-104      | [84f2afeff4](https://bsd-hardware.info/?probe=84f2afeff4) | Jun 21, 2022 |
| HP            | 86E9 A                      | [1d1ac2dd90](https://bsd-hardware.info/?probe=1d1ac2dd90) | Jun 16, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [4e0a906acb](https://bsd-hardware.info/?probe=4e0a906acb) | Jun 11, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | [776a4892d0](https://bsd-hardware.info/?probe=776a4892d0) | Jun 10, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | [9bacfc2b0e](https://bsd-hardware.info/?probe=9bacfc2b0e) | May 29, 2022 |
| Intel         | DH67BL AAG10189-213         | [e8d2744812](https://bsd-hardware.info/?probe=e8d2744812) | May 12, 2022 |
| ASRock        | A320M Pro4-F                | [f307756ddf](https://bsd-hardware.info/?probe=f307756ddf) | May 11, 2022 |
| Unknown       | Unknown                     | [6cf944b0ef](https://bsd-hardware.info/?probe=6cf944b0ef) | May 10, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [cf58c679ef](https://bsd-hardware.info/?probe=cf58c679ef) | May 08, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [5f9e266167](https://bsd-hardware.info/?probe=5f9e266167) | May 04, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [7d4dd8ba29](https://bsd-hardware.info/?probe=7d4dd8ba29) | May 04, 2022 |
| Dell          | 0782GW A00                  | [3481513b0f](https://bsd-hardware.info/?probe=3481513b0f) | May 03, 2022 |
| ASUSTek       | AM1I-A                      | [8fce57c9e4](https://bsd-hardware.info/?probe=8fce57c9e4) | Apr 25, 2022 |
| ASUSTek       | P5KR                        | [cf745ca0da](https://bsd-hardware.info/?probe=cf745ca0da) | Apr 23, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [875d6b2da3](https://bsd-hardware.info/?probe=875d6b2da3) | Apr 22, 2022 |
| Intel         | Q3XXG4-P V1.0               | [a278852381](https://bsd-hardware.info/?probe=a278852381) | Apr 21, 2022 |
| Dell          | 06JWJY A01                  | [16f4cc5d53](https://bsd-hardware.info/?probe=16f4cc5d53) | Apr 20, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [ab8aea2f5c](https://bsd-hardware.info/?probe=ab8aea2f5c) | Apr 17, 2022 |
| Deciso        | Netboard A10                | [6e0b916230](https://bsd-hardware.info/?probe=6e0b916230) | Apr 16, 2022 |
| HP            | 86E9 A                      | [be43a8efde](https://bsd-hardware.info/?probe=be43a8efde) | Apr 14, 2022 |
| Unknown       | J3160-4L                    | [4b981630d7](https://bsd-hardware.info/?probe=4b981630d7) | Apr 13, 2022 |
| Dell          | 0T10XW A02                  | [06720f3c57](https://bsd-hardware.info/?probe=06720f3c57) | Apr 13, 2022 |
| Unknown       | Unknown                     | [e6ba291c2d](https://bsd-hardware.info/?probe=e6ba291c2d) | Apr 12, 2022 |
| Jetway        | 1.0                         | [ac2ab09363](https://bsd-hardware.info/?probe=ac2ab09363) | Apr 11, 2022 |
| Unknown       | Unknown                     | [4e208e9425](https://bsd-hardware.info/?probe=4e208e9425) | Apr 10, 2022 |
| ASUSTek       | P5G41T-M LX3                | [ded0d1a114](https://bsd-hardware.info/?probe=ded0d1a114) | Apr 09, 2022 |
| ASUSTek       | P5G41T-M LX3                | [14a6449380](https://bsd-hardware.info/?probe=14a6449380) | Apr 09, 2022 |
| Unknown       | Unknown                     | [50833ab257](https://bsd-hardware.info/?probe=50833ab257) | Apr 07, 2022 |
| Intel         | Q3XXG4-P V1.0               | [e44ebcb340](https://bsd-hardware.info/?probe=e44ebcb340) | Apr 06, 2022 |
| ASRock        | H110M-ITX                   | [946c8fd467](https://bsd-hardware.info/?probe=946c8fd467) | Apr 04, 2022 |
| PC Engines    | APU2                        | [5eb2e04d11](https://bsd-hardware.info/?probe=5eb2e04d11) | Apr 02, 2022 |
| Dell          | 0782GW A00                  | [c83fab9193](https://bsd-hardware.info/?probe=c83fab9193) | Apr 01, 2022 |
| HP            | ProLiant MicroServer Gen... | [7a991e2f31](https://bsd-hardware.info/?probe=7a991e2f31) | Mar 24, 2022 |
| Dell          | 0782GW A00                  | [acb99d63ce](https://bsd-hardware.info/?probe=acb99d63ce) | Mar 23, 2022 |
| Unknown       | Unknown                     | [05a81cb5d5](https://bsd-hardware.info/?probe=05a81cb5d5) | Mar 22, 2022 |
| Protectli     | FW6 Ver                     | [483cf54bfc](https://bsd-hardware.info/?probe=483cf54bfc) | Mar 21, 2022 |
| ASUSTek       | PRIME B550M-A               | [d0946bc53f](https://bsd-hardware.info/?probe=d0946bc53f) | Mar 21, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [d2ecb6259c](https://bsd-hardware.info/?probe=d2ecb6259c) | Mar 20, 2022 |
| ASUSTek       | PRIME B550M-A               | [40cd6d1472](https://bsd-hardware.info/?probe=40cd6d1472) | Mar 19, 2022 |
| Protectli     | FW6 Ver                     | [a4a1c8e5ca](https://bsd-hardware.info/?probe=a4a1c8e5ca) | Mar 18, 2022 |
| ASUSTek       | PRIME B550M-A               | [b23ab09f52](https://bsd-hardware.info/?probe=b23ab09f52) | Mar 18, 2022 |
| ASUSTek       | PRIME B550M-A               | [545e5ebfc9](https://bsd-hardware.info/?probe=545e5ebfc9) | Mar 18, 2022 |
| HP            | ProLiant MicroServer Gen... | [b652261bda](https://bsd-hardware.info/?probe=b652261bda) | Mar 14, 2022 |
| HP            | ProLiant MicroServer Gen... | [0a2a94839d](https://bsd-hardware.info/?probe=0a2a94839d) | Mar 13, 2022 |
| CNCTION-IA... | Unknown                     | [0051c86e4c](https://bsd-hardware.info/?probe=0051c86e4c) | Mar 07, 2022 |
| AAEON         | UP-CHT01 V0.4               | [9aaa7c7a32](https://bsd-hardware.info/?probe=9aaa7c7a32) | Mar 05, 2022 |
| Protectli     | VP2410                      | [1f650fc994](https://bsd-hardware.info/?probe=1f650fc994) | Mar 05, 2022 |
| PC Engines    | apu1                        | [177dc1fbc8](https://bsd-hardware.info/?probe=177dc1fbc8) | Mar 03, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [43bfceb19d](https://bsd-hardware.info/?probe=43bfceb19d) | Mar 02, 2022 |
| Dell          | 0782GW A00                  | [7b19f71ce1](https://bsd-hardware.info/?probe=7b19f71ce1) | Feb 26, 2022 |
| PC Engines    | apu1                        | [d904aa7790](https://bsd-hardware.info/?probe=d904aa7790) | Feb 24, 2022 |
| Intel         | CARLOW                      | [d46b68cc28](https://bsd-hardware.info/?probe=d46b68cc28) | Feb 23, 2022 |
| HP            | 8169                        | [f449b4cd6c](https://bsd-hardware.info/?probe=f449b4cd6c) | Feb 23, 2022 |
| Intel         | CARLOW                      | [b64bf97293](https://bsd-hardware.info/?probe=b64bf97293) | Feb 19, 2022 |
| Dell          | 0782GW A00                  | [ef5cc6be72](https://bsd-hardware.info/?probe=ef5cc6be72) | Feb 17, 2022 |
| Supermicro    | X11SDV-8C-TP8F              | [18576ef86c](https://bsd-hardware.info/?probe=18576ef86c) | Feb 17, 2022 |
| Intel         | Q3XXG4-P V1.0               | [fbc24f90e5](https://bsd-hardware.info/?probe=fbc24f90e5) | Feb 17, 2022 |
| MSI           | MS-7253                     | [c4e971ea82](https://bsd-hardware.info/?probe=c4e971ea82) | Feb 16, 2022 |
| Intel         | Q3XXG4-P V1.0               | [df529a84b9](https://bsd-hardware.info/?probe=df529a84b9) | Feb 16, 2022 |
| AMD           | X64                         | [e5a9ff1138](https://bsd-hardware.info/?probe=e5a9ff1138) | Feb 15, 2022 |
| Supermicro    | X11SDV-8C-TP8F              | [09a6920a4f](https://bsd-hardware.info/?probe=09a6920a4f) | Feb 12, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [91b1ec3b93](https://bsd-hardware.info/?probe=91b1ec3b93) | Feb 06, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [2accc42e21](https://bsd-hardware.info/?probe=2accc42e21) | Feb 06, 2022 |
| Dell          | 0T10XW A02                  | [9213769810](https://bsd-hardware.info/?probe=9213769810) | Feb 05, 2022 |
| Intel         | SKYBAY                      | [95c3231a3a](https://bsd-hardware.info/?probe=95c3231a3a) | Feb 03, 2022 |
| MSI           | MS-9A45 0A                  | [cfbfdf0e55](https://bsd-hardware.info/?probe=cfbfdf0e55) | Jan 31, 2022 |
| Unknown       | J3160-4L                    | [9dc53740a9](https://bsd-hardware.info/?probe=9dc53740a9) | Jan 29, 2022 |
| AMD           | Larne CRB                   | [c6a85da1d5](https://bsd-hardware.info/?probe=c6a85da1d5) | Jan 28, 2022 |
| Dell          | 0PC5F7 A03                  | [7a5d842d33](https://bsd-hardware.info/?probe=7a5d842d33) | Jan 27, 2022 |
| Intel         | SKYBAY                      | [f1c7ee0712](https://bsd-hardware.info/?probe=f1c7ee0712) | Jan 26, 2022 |
| ASRock        | H110M-ITX                   | [5c58d01f2d](https://bsd-hardware.info/?probe=5c58d01f2d) | Jan 25, 2022 |
| RUNING        | B75M INTEL H3V              | [9a060df0a2](https://bsd-hardware.info/?probe=9a060df0a2) | Jan 23, 2022 |
| AMD           | Larne CRB                   | [6c37b91111](https://bsd-hardware.info/?probe=6c37b91111) | Jan 22, 2022 |
| Dell          | 0T10XW A02                  | [b01e6eb706](https://bsd-hardware.info/?probe=b01e6eb706) | Jan 22, 2022 |
| ASRock        | B365M Pro4                  | [8449bd20c1](https://bsd-hardware.info/?probe=8449bd20c1) | Jan 18, 2022 |
| ASUSTek       | PRIME X570-P                | [3dead218e1](https://bsd-hardware.info/?probe=3dead218e1) | Jan 16, 2022 |
| Unknown       | Unknown                     | [6baaab27fd](https://bsd-hardware.info/?probe=6baaab27fd) | Jan 15, 2022 |
| MSI           | MS-98C8                     | [0102557f05](https://bsd-hardware.info/?probe=0102557f05) | Jan 15, 2022 |
| PC Engines    | APU2                        | [7062b84459](https://bsd-hardware.info/?probe=7062b84459) | Jan 14, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [6aeb9adadb](https://bsd-hardware.info/?probe=6aeb9adadb) | Dec 31, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [8c3181ee8d](https://bsd-hardware.info/?probe=8c3181ee8d) | Dec 29, 2021 |
| Intel         | Q3XXG4-P V1.0               | [cdb5578df8](https://bsd-hardware.info/?probe=cdb5578df8) | Dec 27, 2021 |
| Gigabyte      | X58A-UD5                    | [62b94dd372](https://bsd-hardware.info/?probe=62b94dd372) | Dec 21, 2021 |
| ASRock        | Z590M-ITX/ax                | [124ac672b0](https://bsd-hardware.info/?probe=124ac672b0) | Dec 20, 2021 |
| Unknown       | Unknown                     | [225298bcd6](https://bsd-hardware.info/?probe=225298bcd6) | Dec 12, 2021 |
| RUNING        | B75M INTEL H3V              | [61312aa506](https://bsd-hardware.info/?probe=61312aa506) | Nov 30, 2021 |
| Dell          | VEP-4600-V930 034R2CA03     | [313d1b7032](https://bsd-hardware.info/?probe=313d1b7032) | Nov 25, 2021 |
| Gigabyte      | MZBSWBP-00                  | [9e7a72d920](https://bsd-hardware.info/?probe=9e7a72d920) | Nov 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | [16206960c4](https://bsd-hardware.info/?probe=16206960c4) | Nov 24, 2021 |
| HP            | 3031h                       | [056352a663](https://bsd-hardware.info/?probe=056352a663) | Nov 21, 2021 |
| RUNING        | B75M INTEL H3V              | [5cfcc8c5f8](https://bsd-hardware.info/?probe=5cfcc8c5f8) | Nov 13, 2021 |
| HP            | 3031h                       | [d63bbcfceb](https://bsd-hardware.info/?probe=d63bbcfceb) | Oct 31, 2021 |
| HP            | 3031h                       | [c5e39a5e6d](https://bsd-hardware.info/?probe=c5e39a5e6d) | Oct 31, 2021 |
| MSI           | MS-9A45 0A                  | [e2db09bacb](https://bsd-hardware.info/?probe=e2db09bacb) | Oct 30, 2021 |
| ASRockRack    | C3558D4I-4L                 | [dfba84ce5a](https://bsd-hardware.info/?probe=dfba84ce5a) | Oct 29, 2021 |
| Intel         | Q3XXG4-P V1.0               | [e2167afc3b](https://bsd-hardware.info/?probe=e2167afc3b) | Oct 25, 2021 |
| Intel         | Q3XXG4-P V1.0               | [3f5b148e23](https://bsd-hardware.info/?probe=3f5b148e23) | Oct 22, 2021 |
| Intel         | Q3XXG4-P V1.0               | [6f019f05b6](https://bsd-hardware.info/?probe=6f019f05b6) | Oct 20, 2021 |
| PC Engines    | APU2                        | [4b8fb7992f](https://bsd-hardware.info/?probe=4b8fb7992f) | Oct 16, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | [e53866a5d9](https://bsd-hardware.info/?probe=e53866a5d9) | Oct 11, 2021 |
| ASUSTek       | P9X79                       | [be9d90602d](https://bsd-hardware.info/?probe=be9d90602d) | Oct 11, 2021 |
| Unknown       | Unknown                     | [2fd62acb45](https://bsd-hardware.info/?probe=2fd62acb45) | Oct 10, 2021 |
| Lenovo        | 3138                        | [8b5cf892d0](https://bsd-hardware.info/?probe=8b5cf892d0) | Oct 04, 2021 |
| ASUSTek       | F2A85-M                     | [5b7623f03b](https://bsd-hardware.info/?probe=5b7623f03b) | Sep 21, 2021 |
| Unknown       | Unknown                     | [1b8ce81945](https://bsd-hardware.info/?probe=1b8ce81945) | Sep 19, 2021 |
| ASRock        | B460M Pro4                  | [cfc7818691](https://bsd-hardware.info/?probe=cfc7818691) | Sep 10, 2021 |
| Gigabyte      | F2A88XM-D3H                 | [d5750a95a4](https://bsd-hardware.info/?probe=d5750a95a4) | Sep 08, 2021 |
| Packard Be... | imedia S2110A               | [d62a38660c](https://bsd-hardware.info/?probe=d62a38660c) | Sep 08, 2021 |
| ASUSTek       | P8Z68-V LX                  | [29cfd33c5e](https://bsd-hardware.info/?probe=29cfd33c5e) | Sep 06, 2021 |
| ASRockRack    | X470D4U                     | [827c50f77b](https://bsd-hardware.info/?probe=827c50f77b) | Aug 28, 2021 |
| Dell          | 0G3HR7 A00                  | [7f75f30b75](https://bsd-hardware.info/?probe=7f75f30b75) | Aug 27, 2021 |
| PC Engines    | APU2                        | [0a35da2af7](https://bsd-hardware.info/?probe=0a35da2af7) | Aug 24, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [3e088c942b](https://bsd-hardware.info/?probe=3e088c942b) | Aug 22, 2021 |
| Unknown       | Unknown                     | [1dd499d54c](https://bsd-hardware.info/?probe=1dd499d54c) | Aug 12, 2021 |
| Dell          | 0XCR8D A03                  | [11526a150b](https://bsd-hardware.info/?probe=11526a150b) | Aug 10, 2021 |
| Shuttle       | FS61                        | [b1fbaa8a6b](https://bsd-hardware.info/?probe=b1fbaa8a6b) | Aug 09, 2021 |
| ASUSTek       | H81M-A                      | [bb65c30be3](https://bsd-hardware.info/?probe=bb65c30be3) | Aug 07, 2021 |
| ASUSTek       | H81M-A                      | [9e0c8e8024](https://bsd-hardware.info/?probe=9e0c8e8024) | Aug 07, 2021 |
| Unknown       | YL-SKUL6-7 Series           | [b9ef180b73](https://bsd-hardware.info/?probe=b9ef180b73) | Aug 04, 2021 |
| MSI           | H310M PRO-VDH PLUS          | [3ff984316b](https://bsd-hardware.info/?probe=3ff984316b) | Aug 04, 2021 |
| Dell          | 0G261D A00                  | [2ce00e9f6b](https://bsd-hardware.info/?probe=2ce00e9f6b) | Aug 02, 2021 |
| Unknown       | Unknown                     | [34d448e1d1](https://bsd-hardware.info/?probe=34d448e1d1) | Jul 30, 2021 |
| Unknown       | Unknown                     | [846b6cca20](https://bsd-hardware.info/?probe=846b6cca20) | Jul 30, 2021 |
| Unknown       | Unknown                     | [8aaf18daa1](https://bsd-hardware.info/?probe=8aaf18daa1) | Jul 28, 2021 |
| ASRock        | D1800B-ITX                  | [4831cc5183](https://bsd-hardware.info/?probe=4831cc5183) | Jul 21, 2021 |
| HP            | 2B4B                        | [456625c82f](https://bsd-hardware.info/?probe=456625c82f) | Jul 04, 2021 |
| Dell          | 0XR1GT A00                  | [1e66c42238](https://bsd-hardware.info/?probe=1e66c42238) | Jul 02, 2021 |
| Shuttle       | NC10U                       | [5d2d20dd04](https://bsd-hardware.info/?probe=5d2d20dd04) | Jul 02, 2021 |
| ASUSTek       | PRIME B350M-E               | [bde8057846](https://bsd-hardware.info/?probe=bde8057846) | Jun 29, 2021 |
| Wistron       | ProLiant ML110 G6           | [8f336c0fa3](https://bsd-hardware.info/?probe=8f336c0fa3) | Jun 19, 2021 |
| Wistron       | ProLiant ML110 G6           | [dc619f203f](https://bsd-hardware.info/?probe=dc619f203f) | Jun 19, 2021 |
| ASRock        | H110M-ITX                   | [124c75ba7c](https://bsd-hardware.info/?probe=124c75ba7c) | Jun 17, 2021 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | [e6cbfc417b](https://bsd-hardware.info/?probe=e6cbfc417b) | Jun 10, 2021 |
| Supermicro    | X10SLH-N6-ST031             | [e54175f99f](https://bsd-hardware.info/?probe=e54175f99f) | Jun 06, 2021 |
| Unknown       | YL-J3160L4                  | [24f3dbd372](https://bsd-hardware.info/?probe=24f3dbd372) | Jun 04, 2021 |
| Dell          | 0T10XW A02                  | [cec18015ba](https://bsd-hardware.info/?probe=cec18015ba) | May 30, 2021 |
| Dell          | 0T10XW A02                  | [16f36a045f](https://bsd-hardware.info/?probe=16f36a045f) | May 26, 2021 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | [3e650be93d](https://bsd-hardware.info/?probe=3e650be93d) | May 24, 2021 |
| ASUSTek       | AM1I-A                      | [aafc52d6a1](https://bsd-hardware.info/?probe=aafc52d6a1) | May 24, 2021 |
| Google        | Guado                       | [54f01f821d](https://bsd-hardware.info/?probe=54f01f821d) | May 21, 2021 |
| MSI           | Z77A-G41                    | [c471a8f2fe](https://bsd-hardware.info/?probe=c471a8f2fe) | May 16, 2021 |
| Unknown       | YL-J3160L4                  | [3468faf656](https://bsd-hardware.info/?probe=3468faf656) | May 07, 2021 |
| ASRockRack    | X470D4U                     | [421da89770](https://bsd-hardware.info/?probe=421da89770) | May 06, 2021 |
| ASUSTek       | P8H77-M PRO                 | [87e5651fd1](https://bsd-hardware.info/?probe=87e5651fd1) | May 06, 2021 |
| PC Engines    | APU2                        | [c99a0b0e4d](https://bsd-hardware.info/?probe=c99a0b0e4d) | May 05, 2021 |
| MSI           | MS-9A45 0A                  | [e930fac60b](https://bsd-hardware.info/?probe=e930fac60b) | May 05, 2021 |
| Supermicro    | X8STi                       | [c615ef1edf](https://bsd-hardware.info/?probe=c615ef1edf) | May 04, 2021 |
| ASUSTek       | Rampage II GENE             | [4eac97c85c](https://bsd-hardware.info/?probe=4eac97c85c) | May 04, 2021 |
| Unknown       | Unknown                     | [4368de8d34](https://bsd-hardware.info/?probe=4368de8d34) | Apr 28, 2021 |
| PC Engines    | APU3                        | [1d6ca07c5a](https://bsd-hardware.info/?probe=1d6ca07c5a) | Apr 27, 2021 |
| PC Engines    | APU3                        | [8fc426b107](https://bsd-hardware.info/?probe=8fc426b107) | Apr 22, 2021 |
| Dell          | 0PC5F7 A03                  | [e262812b4d](https://bsd-hardware.info/?probe=e262812b4d) | Apr 21, 2021 |
| Unknown       | J3160-4L                    | [354dc80671](https://bsd-hardware.info/?probe=354dc80671) | Apr 07, 2021 |
| PC Engines    | apu4                        | [160a01d9e1](https://bsd-hardware.info/?probe=160a01d9e1) | Apr 03, 2021 |
| Supermicro    | X7SPA-HF                    | [f3b6d4d5c4](https://bsd-hardware.info/?probe=f3b6d4d5c4) | Apr 03, 2021 |
| PC Engines    | APU2                        | [97554df75d](https://bsd-hardware.info/?probe=97554df75d) | Mar 30, 2021 |
| ASUSTek       | P8Z68-V LX                  | [0263b0e32e](https://bsd-hardware.info/?probe=0263b0e32e) | Mar 26, 2021 |
| Lenovo        | 3138                        | [f12dd68efb](https://bsd-hardware.info/?probe=f12dd68efb) | Mar 25, 2021 |
| Dell          | 0KRC95 A02                  | [68354c00cf](https://bsd-hardware.info/?probe=68354c00cf) | Mar 25, 2021 |
| Dell          | 0NW6H5 A00                  | [1499695aae](https://bsd-hardware.info/?probe=1499695aae) | Mar 25, 2021 |
| Dell          | 0NW6H5 A00                  | [650cd9b653](https://bsd-hardware.info/?probe=650cd9b653) | Mar 24, 2021 |
| Dell          | 0D28YY A00                  | [bef38bd379](https://bsd-hardware.info/?probe=bef38bd379) | Mar 23, 2021 |
| ASRock        | Z490M Pro4                  | [c0df245c1b](https://bsd-hardware.info/?probe=c0df245c1b) | Mar 13, 2021 |
| Dell          | 0PC5F7 A03                  | [24b657e7ba](https://bsd-hardware.info/?probe=24b657e7ba) | Mar 12, 2021 |
| MSI           | B360M BAZOOKA               | [17a763a917](https://bsd-hardware.info/?probe=17a763a917) | Mar 11, 2021 |
| ASUSTek       | AM1I-A                      | [835842d361](https://bsd-hardware.info/?probe=835842d361) | Mar 10, 2021 |
| ASRock        | Z490M Pro4                  | [348d592fab](https://bsd-hardware.info/?probe=348d592fab) | Mar 05, 2021 |
| VeryPC        | S400                        | [77b744169b](https://bsd-hardware.info/?probe=77b744169b) | Mar 04, 2021 |
| VeryPC        | S400                        | [edcea11cb7](https://bsd-hardware.info/?probe=edcea11cb7) | Mar 04, 2021 |
| HP            | 86E9 A                      | [215398b88f](https://bsd-hardware.info/?probe=215398b88f) | Feb 28, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [b1f1b3cd82](https://bsd-hardware.info/?probe=b1f1b3cd82) | Feb 22, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [929bda8001](https://bsd-hardware.info/?probe=929bda8001) | Feb 22, 2021 |
| Acer          | EG43M                       | [22552918ee](https://bsd-hardware.info/?probe=22552918ee) | Feb 21, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [ade306695d](https://bsd-hardware.info/?probe=ade306695d) | Feb 20, 2021 |
| ASRock        | H370M-ITX/ac                | [5d39657098](https://bsd-hardware.info/?probe=5d39657098) | Feb 14, 2021 |
| ASUSTek       | PRIME B450M-A               | [ba7f82b343](https://bsd-hardware.info/?probe=ba7f82b343) | Feb 12, 2021 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | [5965bc8a1d](https://bsd-hardware.info/?probe=5965bc8a1d) | Feb 11, 2021 |
| PC Engines    | APU                         | [282a9596c6](https://bsd-hardware.info/?probe=282a9596c6) | Feb 11, 2021 |
| Dell          | 030VXY A01                  | [23e7163f58](https://bsd-hardware.info/?probe=23e7163f58) | Feb 10, 2021 |
| Gigabyte      | Z97P-D3                     | [a3bd8f5772](https://bsd-hardware.info/?probe=a3bd8f5772) | Feb 10, 2021 |
| Dell          | 0PC5F7 A03                  | [94bcab24a8](https://bsd-hardware.info/?probe=94bcab24a8) | Feb 09, 2021 |
| PC Engines    | APU3                        | [e21438c3cc](https://bsd-hardware.info/?probe=e21438c3cc) | Feb 07, 2021 |
| MSI           | Z77A-G41                    | [35bae50659](https://bsd-hardware.info/?probe=35bae50659) | Feb 06, 2021 |
| Unknown       | Unknown                     | [8ef7071a3f](https://bsd-hardware.info/?probe=8ef7071a3f) | Feb 04, 2021 |
| Unknown       | YL-J3160L4                  | [857c5aade9](https://bsd-hardware.info/?probe=857c5aade9) | Feb 04, 2021 |
| MSI           | MS-9A45 0A                  | [f66ccf2f33](https://bsd-hardware.info/?probe=f66ccf2f33) | Feb 03, 2021 |
| MSI           | MS-9A45 0A                  | [c384535b6f](https://bsd-hardware.info/?probe=c384535b6f) | Feb 02, 2021 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | [c8af335c01](https://bsd-hardware.info/?probe=c8af335c01) | Jan 29, 2021 |
| ASUSTek       | M2NPV-MX                    | [dae16641bb](https://bsd-hardware.info/?probe=dae16641bb) | Jan 23, 2021 |
| ASUSTek       | M2NPV-MX                    | [45e53e33d8](https://bsd-hardware.info/?probe=45e53e33d8) | Jan 23, 2021 |
| Unknown       | Unknown                     | [4c4d549584](https://bsd-hardware.info/?probe=4c4d549584) | Jan 22, 2021 |
| ASUSTek       | M2NPV-MX                    | [ae29fe5691](https://bsd-hardware.info/?probe=ae29fe5691) | Jan 22, 2021 |
| ASUSTek       | M2NPV-MX                    | [bdd89d655d](https://bsd-hardware.info/?probe=bdd89d655d) | Jan 22, 2021 |
| ASUSTek       | M2NPV-MX                    | [006cafaa6b](https://bsd-hardware.info/?probe=006cafaa6b) | Jan 22, 2021 |
| ASUSTek       | M2NPV-MX                    | [80edc8dae6](https://bsd-hardware.info/?probe=80edc8dae6) | Jan 22, 2021 |
| PC Engines    | apu4                        | [3507544d2e](https://bsd-hardware.info/?probe=3507544d2e) | Jan 20, 2021 |
| Dell          | 0NW6H5 A00                  | [f6df3820b5](https://bsd-hardware.info/?probe=f6df3820b5) | Jan 18, 2021 |
| Dell          | 0KC9NP A01                  | [a9228fa7c3](https://bsd-hardware.info/?probe=a9228fa7c3) | Jan 15, 2021 |
| Dell          | 030VXY A01                  | [5af442bf61](https://bsd-hardware.info/?probe=5af442bf61) | Jan 15, 2021 |
| HP            | 3399                        | [b11946a41a](https://bsd-hardware.info/?probe=b11946a41a) | Jan 13, 2021 |
| Pegatron      | 2AB5                        | [8093f75ea2](https://bsd-hardware.info/?probe=8093f75ea2) | Jan 13, 2021 |
| Dell          | 0NW6H5 A00                  | [d54f451ea5](https://bsd-hardware.info/?probe=d54f451ea5) | Jan 07, 2021 |
| HP            | 3032h                       | [13648fd22d](https://bsd-hardware.info/?probe=13648fd22d) | Jan 07, 2021 |
| Dell          | 0KC9NP A01                  | [ee2d5f3289](https://bsd-hardware.info/?probe=ee2d5f3289) | Jan 07, 2021 |
| Dell          | 030VXY A01                  | [c117ffdc98](https://bsd-hardware.info/?probe=c117ffdc98) | Jan 07, 2021 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | [36ef631bfe](https://bsd-hardware.info/?probe=36ef631bfe) | Jan 05, 2021 |
| Gigabyte      | X79-UD3                     | [a8baf509d9](https://bsd-hardware.info/?probe=a8baf509d9) | Dec 26, 2020 |
| ASUSTek       | PRIME B450M-A               | [d13e0a1749](https://bsd-hardware.info/?probe=d13e0a1749) | Dec 15, 2020 |
| ASRock        | J3455-ITX                   | [1d5bd18d14](https://bsd-hardware.info/?probe=1d5bd18d14) | Oct 29, 2020 |
| Supermicro    | X8STi                       | [1b64902781](https://bsd-hardware.info/?probe=1b64902781) | Oct 26, 2020 |
| AZW           | Z83 II                      | [9416876f20](https://bsd-hardware.info/?probe=9416876f20) | Oct 24, 2020 |
| AZW           | Z83 II                      | [19b1b4d85d](https://bsd-hardware.info/?probe=19b1b4d85d) | Oct 24, 2020 |
| Intel         | D2500HN                     | [6dbc4dfa33](https://bsd-hardware.info/?probe=6dbc4dfa33) | Oct 21, 2020 |
| PC Engines    | APU2                        | [d1ca549fe7](https://bsd-hardware.info/?probe=d1ca549fe7) | Oct 21, 2020 |
| ZOTAC         | XXXXXX                      | [0f8960bdd3](https://bsd-hardware.info/?probe=0f8960bdd3) | Oct 21, 2020 |
| Intel         | D2500HN                     | [4b432dcb3d](https://bsd-hardware.info/?probe=4b432dcb3d) | Oct 20, 2020 |
| PC Engines    | APU2                        | [b95ef9962d](https://bsd-hardware.info/?probe=b95ef9962d) | Oct 20, 2020 |
| PC Engines    | APU2                        | [aecf376503](https://bsd-hardware.info/?probe=aecf376503) | Oct 20, 2020 |
| HP            | ProLiant MicroServer Gen... | [88f2d98930](https://bsd-hardware.info/?probe=88f2d98930) | Sep 12, 2020 |
| Intel         | DH61AG AAG23736-505         | [3f99489a19](https://bsd-hardware.info/?probe=3f99489a19) | Aug 19, 2020 |
| ASUSTek       | Maximus VIII RANGER         | [42de38c478](https://bsd-hardware.info/?probe=42de38c478) | Aug 19, 2020 |
| Intel         | DN2800MT AAG81515-900       | [bcfec367a9](https://bsd-hardware.info/?probe=bcfec367a9) | Aug 14, 2020 |
| Gigabyte      | P35-DS3R                    | [4ed0c89a67](https://bsd-hardware.info/?probe=4ed0c89a67) | Aug 07, 2020 |
| ASUSTek       | Z170-P D3                   | [7b8885caf3](https://bsd-hardware.info/?probe=7b8885caf3) | Aug 07, 2020 |
| ASUSTek       | Z170-P D3                   | [2e9821f90f](https://bsd-hardware.info/?probe=2e9821f90f) | Aug 07, 2020 |
| Gigabyte      | EP45-DS4                    | [a56a9c50fc](https://bsd-hardware.info/?probe=a56a9c50fc) | Aug 07, 2020 |
| Gigabyte      | P35-DS3R                    | [0b111b137c](https://bsd-hardware.info/?probe=0b111b137c) | Aug 07, 2020 |
| Intel         | DH61AGL G71256-202          | [666757a826](https://bsd-hardware.info/?probe=666757a826) | Jun 14, 2020 |
| PC Engines    | APU2                        | [dc1c86095f](https://bsd-hardware.info/?probe=dc1c86095f) | Jun 14, 2020 |
| Gigabyte      | H77N-WIFI                   | [48dd406069](https://bsd-hardware.info/?probe=48dd406069) | May 30, 2020 |
| ASUSTek       | P8H61 PRO                   | [94c4617d4e](https://bsd-hardware.info/?probe=94c4617d4e) | May 27, 2020 |
| MSI           | Z87I GAMING AC              | [5d38b05178](https://bsd-hardware.info/?probe=5d38b05178) | May 25, 2020 |
| Unknown       | Unknown                     | [3bcdac5d97](https://bsd-hardware.info/?probe=3bcdac5d97) | May 24, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| OPNsense 21.1.5              | 13       | 6.84%   |
| OPNsense 21.7.7              | 10       | 5.26%   |
| OpenBSD 6.8                  | 9        | 4.74%   |
| OPNsense 22.1.6              | 8        | 4.21%   |
| OPNsense 22.1.1              | 6        | 3.16%   |
| OPNsense 22.1                | 6        | 3.16%   |
| OPNsense 21.7.1              | 6        | 3.16%   |
| OPNsense 21.1.3              | 6        | 3.16%   |
| OPNsense 21.1                | 6        | 3.16%   |
| OPNsense 22.1.2              | 5        | 2.63%   |
| helloSystem 0.5.0            | 5        | 2.63%   |
| GhostBSD 20.04.02            | 5        | 2.63%   |
| OPNsense 22.1.3              | 4        | 2.11%   |
| OPNsense 21.7.5              | 4        | 2.11%   |
| OPNsense 21.7.3              | 4        | 2.11%   |
| OPNsense 21.7                | 4        | 2.11%   |
| OPNsense 20.7.8              | 4        | 2.11%   |
| helloSystem 0.4.0            | 4        | 2.11%   |
| FreeBSD 12.1-p8              | 4        | 2.11%   |
| OPNsense 22.1.5              | 3        | 1.58%   |
| OPNsense 21.7.8              | 3        | 1.58%   |
| OPNsense 21.7.4              | 3        | 1.58%   |
| OPNsense 21.1.7              | 3        | 1.58%   |
| OPNsense 21.1.4              | 3        | 1.58%   |
| OpenBSD 6.9                  | 3        | 1.58%   |
| NomadBSD 1.3.2               | 3        | 1.58%   |
| helloSystem 0.7.0            | 3        | 1.58%   |
| FreeBSD 13.0-p4              | 3        | 1.58%   |
| FreeBSD 13.0-p11             | 3        | 1.58%   |
| FreeBSD 13.0                 | 3        | 1.58%   |
| FreeBSD 12.1-STABLE          | 3        | 1.58%   |
| OPNsense 22.1.4              | 2        | 1.05%   |
| OPNsense 21.1.6              | 2        | 1.05%   |
| OPNsense 21.1.1              | 2        | 1.05%   |
| helloSystem 0.8.0            | 2        | 1.05%   |
| FreeBSD 13.1-BETA2           | 2        | 1.05%   |
| FreeBSD 13.1                 | 2        | 1.05%   |
| FreeBSD 12.2-p4              | 2        | 1.05%   |
| TrueNAS 12.2-p11             | 1        | 0.53%   |
| OPNsense 22.7                | 1        | 0.53%   |
| OPNsense 22.1.9              | 1        | 0.53%   |
| OPNsense 22.1.8              | 1        | 0.53%   |
| OPNsense 21.7.6              | 1        | 0.53%   |
| OPNsense 21.7.2              | 1        | 0.53%   |
| OPNsense 21.1.8              | 1        | 0.53%   |
| OPNsense 20.7.5              | 1        | 0.53%   |
| OpenBSD 7.0                  | 1        | 0.53%   |
| HardenedBSD 13.0-STABLE-HBSD | 1        | 0.53%   |
| FreeNAS 11.3-p7              | 1        | 0.53%   |
| FreeBSD 14.0-CURRENT         | 1        | 0.53%   |
| FreeBSD 13.1-STABLE          | 1        | 0.53%   |
| FreeBSD 13.1-RC6             | 1        | 0.53%   |
| FreeBSD 13.0-STABLE          | 1        | 0.53%   |
| FreeBSD 13.0-p5              | 1        | 0.53%   |
| FreeBSD 12.2-p3              | 1        | 0.53%   |
| FreeBSD 12.2-p2              | 1        | 0.53%   |
| FreeBSD 12.2-p10             | 1        | 0.53%   |
| FreeBSD 12.2                 | 1        | 0.53%   |
| FreeBSD 12.1-p9              | 1        | 0.53%   |
| FreeBSD 12.1-p7              | 1        | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 82       | 53.25%  |
| FreeBSD     | 36       | 23.38%  |
| helloSystem | 14       | 9.09%   |
| OpenBSD     | 11       | 7.14%   |
| GhostBSD    | 5        | 3.25%   |
| NomadBSD    | 3        | 1.95%   |
| TrueNAS     | 1        | 0.65%   |
| HardenedBSD | 1        | 0.65%   |
| FreeNAS     | 1        | 0.65%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 152      | 99.35%  |
| i386  | 1        | 0.65%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 111      | 71.61%  |
| helloDesktop | 14       | 9.03%   |
| XFCE         | 11       | 7.1%    |
| MATE         | 5        | 3.23%   |
| Openbox      | 3        | 1.94%   |
| KDE5         | 3        | 1.94%   |
| fvwm         | 3        | 1.94%   |
| GNOME        | 2        | 1.29%   |
| TWM          | 1        | 0.65%   |
| Cinnamon     | 1        | 0.65%   |
| AwesomeWM    | 1        | 0.65%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 113      | 73.86%  |
| X11     | 39       | 25.49%  |
| Wayland | 1        | 0.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 119      | 77.27%  |
| SLiM    | 20       | 12.99%  |
| LightDM | 8        | 5.19%   |
| SDDM    | 4        | 2.6%    |
| XDM     | 2        | 1.3%    |
| GDM     | 1        | 0.65%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 109      | 70.78%  |
| en_US          | 21       | 13.64%  |
| C              | 12       | 7.79%   |
| fr_FR          | 11       | 7.14%   |
| fr_FR.US-ASCII | 1        | 0.65%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 114      | 74.03%  |
| BIOS | 40       | 25.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 81       | 52.94%  |
| Zfs    | 58       | 37.91%  |
| Ffs    | 11       | 7.19%   |
| Cd9660 | 3        | 1.96%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 131      | 85.06%  |
| MBR     | 22       | 14.29%  |
| Unknown | 1        | 0.65%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 27       | 17.65%  |
| PC Engines          | 16       | 10.46%  |
| Intel               | 15       | 9.8%    |
| Dell                | 14       | 9.15%   |
| Gigabyte Technology | 13       | 8.5%    |
| Unknown             | 12       | 7.84%   |
| ASRock              | 9        | 5.88%   |
| MSI                 | 8        | 5.23%   |
| Hewlett-Packard     | 8        | 5.23%   |
| Supermicro          | 5        | 3.27%   |
| Shuttle             | 2        | 1.31%   |
| RUNING              | 2        | 1.31%   |
| Protectli           | 2        | 1.31%   |
| Lenovo              | 2        | 1.31%   |
| Fujitsu             | 2        | 1.31%   |
| ASRockRack          | 2        | 1.31%   |
| AMD                 | 2        | 1.31%   |
| ZOTAC               | 1        | 0.65%   |
| Wistron             | 1        | 0.65%   |
| VeryPC              | 1        | 0.65%   |
| Pegatron            | 1        | 0.65%   |
| Packard Bell        | 1        | 0.65%   |
| Jetway              | 1        | 0.65%   |
| Google              | 1        | 0.65%   |
| Deciso              | 1        | 0.65%   |
| CNCTION-IAF-E3845   | 1        | 0.65%   |
| AZW                 | 1        | 0.65%   |
| Acer                | 1        | 0.65%   |
| AAEON               | 1        | 0.65%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| Unknown                                  | 13       | 8.5%    |
| PC Engines APU2                          | 9        | 5.88%   |
| Intel Q3XXG4-P V1.0                      | 7        | 4.58%   |
| PC Engines APU3                          | 3        | 1.96%   |
| Dell OptiPlex 9020                       | 3        | 1.96%   |
| ASUS All Series                          | 3        | 1.96%   |
| RUNING B75M INTEL H3V                    | 2        | 1.31%   |
| PC Engines apu4                          | 2        | 1.31%   |
| HP ProLiant MicroServer Gen8             | 2        | 1.31%   |
| Gigabyte X570 I AORUS PRO WIFI           | 2        | 1.31%   |
| ASUS Z170-P D3                           | 2        | 1.31%   |
| ASUS PRIME B450M-A                       | 2        | 1.31%   |
| ASUS P8Z68-V LX                          | 2        | 1.31%   |
| ZOTAC XXXXXX                             | 1        | 0.65%   |
| Wistron ProLiant ML110 G6                | 1        | 0.65%   |
| VeryPC S400-K7-N-O                       | 1        | 0.65%   |
| Supermicro X8STi                         | 1        | 0.65%   |
| Supermicro X7SPA-HF                      | 1        | 0.65%   |
| Supermicro X10SLH-N6-ST031               | 1        | 0.65%   |
| Supermicro SYS-E300-9D-8CN8TP            | 1        | 0.65%   |
| Supermicro SYS-5019A-FTN4                | 1        | 0.65%   |
| Shuttle NC10U                            | 1        | 0.65%   |
| Shuttle DS61                             | 1        | 0.65%   |
| Protectli VP2410                         | 1        | 0.65%   |
| Protectli FW6                            | 1        | 0.65%   |
| Pegatron Elite 7300 Series MT            | 1        | 0.65%   |
| PC Engines apu1                          | 1        | 0.65%   |
| PC Engines APU                           | 1        | 0.65%   |
| Packard Bell imedia S2110                | 1        | 0.65%   |
| MSI MS-9A68                              | 1        | 0.65%   |
| MSI MS-9A45                              | 1        | 0.65%   |
| MSI MS-7C09                              | 1        | 0.65%   |
| MSI MS-7C02                              | 1        | 0.65%   |
| MSI MS-7B24                              | 1        | 0.65%   |
| MSI MS-7887                              | 1        | 0.65%   |
| MSI MS-7758                              | 1        | 0.65%   |
| MSI MS-7253                              | 1        | 0.65%   |
| Lenovo ThinkSystem ST50 7Y48CTO1WW       | 1        | 0.65%   |
| Lenovo ThinkCentre M93p 10A8S0CE09       | 1        | 0.65%   |
| Jetway 1.0                               | 1        | 0.65%   |
| Intel SKYBAY                             | 1        | 0.65%   |
| Intel DN2800MT AAG81515-900              | 1        | 0.65%   |
| Intel DH67BL AAG10189-213                | 1        | 0.65%   |
| Intel DH61AGL                            | 1        | 0.65%   |
| Intel DH61AG AAG23736-505                | 1        | 0.65%   |
| Intel D945GCLF2 AAE46416-104             | 1        | 0.65%   |
| Intel D2500HN                            | 1        | 0.65%   |
| Intel CARLOW                             | 1        | 0.65%   |
| HP ProDesk 600 G2 DM                     | 1        | 0.65%   |
| HP Desktop M01-F0xxx                     | 1        | 0.65%   |
| HP Compaq Elite 8300 Touch All-in-One PC | 1        | 0.65%   |
| HP Compaq dc7900 Small Form Factor       | 1        | 0.65%   |
| HP Compaq dc7900 Convertible Minitower   | 1        | 0.65%   |
| HP 860-012nf                             | 1        | 0.65%   |
| Google Guado                             | 1        | 0.65%   |
| Gigabyte Z97P-D3                         | 1        | 0.65%   |
| Gigabyte Z690I AORUS ULTRA               | 1        | 0.65%   |
| Gigabyte X79-UD3                         | 1        | 0.65%   |
| Gigabyte X58A-UD5                        | 1        | 0.65%   |
| Gigabyte P35-DS3R                        | 1        | 0.65%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Unknown                       | 13       | 8.5%    |
| Dell OptiPlex                 | 10       | 6.54%   |
| PC Engines APU2               | 9        | 5.88%   |
| Intel Q3XXG4-P                | 7        | 4.58%   |
| ASUS PRIME                    | 6        | 3.92%   |
| PC Engines APU3               | 3        | 1.96%   |
| HP Compaq                     | 3        | 1.96%   |
| ASUS All                      | 3        | 1.96%   |
| RUNING B75M                   | 2        | 1.31%   |
| PC Engines apu4               | 2        | 1.31%   |
| HP ProLiant                   | 2        | 1.31%   |
| Gigabyte X570                 | 2        | 1.31%   |
| ASUS Z170-P                   | 2        | 1.31%   |
| ASUS P8Z68-V                  | 2        | 1.31%   |
| ZOTAC XXXXXX                  | 1        | 0.65%   |
| Wistron ProLiant              | 1        | 0.65%   |
| VeryPC S400-K7-N-O            | 1        | 0.65%   |
| Supermicro X8STi              | 1        | 0.65%   |
| Supermicro X7SPA-HF           | 1        | 0.65%   |
| Supermicro X10SLH-N6-ST031    | 1        | 0.65%   |
| Supermicro SYS-E300-9D-8CN8TP | 1        | 0.65%   |
| Supermicro SYS-5019A-FTN4     | 1        | 0.65%   |
| Shuttle NC10U                 | 1        | 0.65%   |
| Shuttle DS61                  | 1        | 0.65%   |
| Protectli VP2410              | 1        | 0.65%   |
| Protectli FW6                 | 1        | 0.65%   |
| Pegatron Elite                | 1        | 0.65%   |
| PC Engines apu1               | 1        | 0.65%   |
| PC Engines APU                | 1        | 0.65%   |
| Packard Bell imedia           | 1        | 0.65%   |
| MSI MS-9A68                   | 1        | 0.65%   |
| MSI MS-9A45                   | 1        | 0.65%   |
| MSI MS-7C09                   | 1        | 0.65%   |
| MSI MS-7C02                   | 1        | 0.65%   |
| MSI MS-7B24                   | 1        | 0.65%   |
| MSI MS-7887                   | 1        | 0.65%   |
| MSI MS-7758                   | 1        | 0.65%   |
| MSI MS-7253                   | 1        | 0.65%   |
| Lenovo ThinkSystem            | 1        | 0.65%   |
| Lenovo ThinkCentre            | 1        | 0.65%   |
| Jetway 1.0                    | 1        | 0.65%   |
| Intel SKYBAY                  | 1        | 0.65%   |
| Intel DN2800MT                | 1        | 0.65%   |
| Intel DH67BL                  | 1        | 0.65%   |
| Intel DH61AGL                 | 1        | 0.65%   |
| Intel DH61AG                  | 1        | 0.65%   |
| Intel D945GCLF2               | 1        | 0.65%   |
| Intel D2500HN                 | 1        | 0.65%   |
| Intel CARLOW                  | 1        | 0.65%   |
| HP ProDesk                    | 1        | 0.65%   |
| HP Desktop                    | 1        | 0.65%   |
| HP 860-012nf                  | 1        | 0.65%   |
| Google Guado                  | 1        | 0.65%   |
| Gigabyte Z97P-D3              | 1        | 0.65%   |
| Gigabyte Z690I                | 1        | 0.65%   |
| Gigabyte X79-UD3              | 1        | 0.65%   |
| Gigabyte X58A-UD5             | 1        | 0.65%   |
| Gigabyte P35-DS3R             | 1        | 0.65%   |
| Gigabyte H77N-WIFI            | 1        | 0.65%   |
| Gigabyte GB-BACE-3150         | 1        | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2016    | 27       | 17.65%  |
| 2019    | 20       | 13.07%  |
| 2018    | 17       | 11.11%  |
| 2012    | 13       | 8.5%    |
| 2020    | 12       | 7.84%   |
| 2013    | 12       | 7.84%   |
| 2015    | 8        | 5.23%   |
| 2014    | 8        | 5.23%   |
| 2021    | 7        | 4.58%   |
| 2017    | 7        | 4.58%   |
| 2010    | 6        | 3.92%   |
| 2011    | 4        | 2.61%   |
| 2009    | 4        | 2.61%   |
| 2008    | 3        | 1.96%   |
| 2007    | 2        | 1.31%   |
| 2022    | 1        | 0.65%   |
| 2006    | 1        | 0.65%   |
| Unknown | 1        | 0.65%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 153      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 135      | 88.24%  |
| Yes  | 18       | 11.76%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 48       | 31.37%  |
| 4.01-8.0    | 44       | 28.76%  |
| 16.01-24.0  | 35       | 22.88%  |
| 32.01-64.0  | 9        | 5.88%   |
| 2.01-3.0    | 8        | 5.23%   |
| 64.01-256.0 | 5        | 3.27%   |
| 1.01-2.0    | 3        | 1.96%   |
| 3.01-4.0    | 1        | 0.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 85       | 55.19%  |
| 0.51-1.0   | 42       | 27.27%  |
| 1.01-2.0   | 14       | 9.09%   |
| 2.01-3.0   | 5        | 3.25%   |
| 4.01-8.0   | 4        | 2.6%    |
| 3.01-4.0   | 2        | 1.3%    |
| 16.01-24.0 | 1        | 0.65%   |
| 8.01-16.0  | 1        | 0.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 97       | 62.58%  |
| 2      | 19       | 12.26%  |
| 3      | 16       | 10.32%  |
| 0      | 12       | 7.74%   |
| 5      | 4        | 2.58%   |
| 4      | 4        | 2.58%   |
| 6      | 2        | 1.29%   |
| 10     | 1        | 0.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 131      | 84.52%  |
| Yes       | 24       | 15.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 152      | 99.35%  |
| No        | 1        | 0.65%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 114      | 74.51%  |
| Yes       | 39       | 25.49%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 133      | 86.93%  |
| Yes       | 20       | 13.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| France  | 153      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                         | Desktops | Percent |
|------------------------------|----------|---------|
| Paris                        | 36       | 21.43%  |
| Toulouse                     | 5        | 2.98%   |
| Roubaix                      | 5        | 2.98%   |
| Soisy-sur-Seine              | 4        | 2.38%   |
| Vaulx-en-Velin               | 3        | 1.79%   |
| Montfermeil                  | 3        | 1.79%   |
| Lyon                         | 3        | 1.79%   |
| Agen                         | 3        | 1.79%   |
| ?????chirolles               | 2        | 1.19%   |
| Villeurbanne                 | 2        | 1.19%   |
| Seyssinet-Pariset            | 2        | 1.19%   |
| Saint-Martin-d'H????res      | 2        | 1.19%   |
| Saint-Denis                  | 2        | 1.19%   |
| Rennes                       | 2        | 1.19%   |
| Pau                          | 2        | 1.19%   |
| ?????tampes                  | 2        | 1.19%   |
| Yerres                       | 1        | 0.6%    |
| Villaz                       | 1        | 0.6%    |
| Vichy                        | 1        | 0.6%    |
| V??nissieux                  | 1        | 0.6%    |
| Vauvillers                   | 1        | 0.6%    |
| Vauclerc                     | 1        | 0.6%    |
| Thionville                   | 1        | 0.6%    |
| Teteghem                     | 1        | 0.6%    |
| Strasbourg                   | 1        | 0.6%    |
| Schiltigheim                 | 1        | 0.6%    |
| Sallanches                   | 1        | 0.6%    |
| Salagnon                     | 1        | 0.6%    |
| Sainte-Foy-les-Lyon          | 1        | 0.6%    |
| Saint-?????tienne-du-Rouvray | 1        | 0.6%    |
| Saint-Martin-sur-Oust        | 1        | 0.6%    |
| Saint-Mande                  | 1        | 0.6%    |
| Saint-Laurent-de-Ceris       | 1        | 0.6%    |
| Saint-Herblain               | 1        | 0.6%    |
| Saint-Denis-de-Pile          | 1        | 0.6%    |
| Sable-sur-Sarthe             | 1        | 0.6%    |
| Roissy-en-Brie               | 1        | 0.6%    |
| Rochefort                    | 1        | 0.6%    |
| Rillieux-la-Pape             | 1        | 0.6%    |
| Rez????                      | 1        | 0.6%    |
| Quevert                      | 1        | 0.6%    |
| Puisieulx                    | 1        | 0.6%    |
| Pluvigner                    | 1        | 0.6%    |
| Plouzane                     | 1        | 0.6%    |
| Plougonven                   | 1        | 0.6%    |
| Paray-sous-Briailles         | 1        | 0.6%    |
| Orl????ans                   | 1        | 0.6%    |
| N????rac                     | 1        | 0.6%    |
| Novillars                    | 1        | 0.6%    |
| Noisy-le-Grand               | 1        | 0.6%    |
| Nice                         | 1        | 0.6%    |
| Neuve-Maison                 | 1        | 0.6%    |
| Nantes                       | 1        | 0.6%    |
| Monts                        | 1        | 0.6%    |
| Montpellier                  | 1        | 0.6%    |
| Montlu????on                 | 1        | 0.6%    |
| Metz                         | 1        | 0.6%    |
| Messimy                      | 1        | 0.6%    |
| M????rignac                  | 1        | 0.6%    |
| Maysel                       | 1        | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 32       | 42     | 17.02%  |
| WDC                 | 26       | 47     | 13.83%  |
| Samsung Electronics | 20       | 29     | 10.64%  |
| Crucial             | 16       | 20     | 8.51%   |
| Kingston            | 13       | 23     | 6.91%   |
| Transcend           | 10       | 11     | 5.32%   |
| Phison              | 9        | 10     | 4.79%   |
| Toshiba             | 7        | 13     | 3.72%   |
| SanDisk             | 5        | 11     | 2.66%   |
| Intel               | 4        | 7      | 2.13%   |
| Hoodisk             | 4        | 4      | 2.13%   |
| HGST                | 4        | 7      | 2.13%   |
| China               | 4        | 9      | 2.13%   |
| PNY                 | 3        | 4      | 1.6%    |
| OCZ                 | 3        | 4      | 1.6%    |
| LDLC                | 3        | 3      | 1.6%    |
| Hitachi             | 3        | 3      | 1.6%    |
| Corsair             | 3        | 4      | 1.6%    |
| Apple               | 3        | 5      | 1.6%    |
| Micron Technology   | 2        | 3      | 1.06%   |
| SPCC                | 1        | 1      | 0.53%   |
| Silicon Power       | 1        | 1      | 0.53%   |
| ShiJi               | 1        | 2      | 0.53%   |
| SABRENT             | 1        | 1      | 0.53%   |
| Pccooler            | 1        | 1      | 0.53%   |
| NVMe                | 1        | 1      | 0.53%   |
| Maxtor              | 1        | 2      | 0.53%   |
| LITEON              | 1        | 2      | 0.53%   |
| Kingchuxing         | 1        | 2      | 0.53%   |
| Innodisk            | 1        | 1      | 0.53%   |
| Indilinx            | 1        | 5      | 0.53%   |
| Generic             | 1        | 1      | 0.53%   |
| Fujitsu             | 1        | 1      | 0.53%   |
| FORESEE             | 1        | 2      | 0.53%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Phison SATA SSD 16GB               | 8        | 3.88%   |
| Crucial CT120BX500SSD1 120GB       | 4        | 1.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3        | 1.46%   |
| SanDisk SSD PLUS 120GB             | 3        | 1.46%   |
| Samsung SSD 850 EVO 250GB          | 3        | 1.46%   |
| HGST HUS724020ALA640 2TB           | 3        | 1.46%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2        | 0.97%   |
| Transcend TS128GSSD420K 128GB      | 2        | 0.97%   |
| Seagate ST3500418AS 500GB          | 2        | 0.97%   |
| Seagate ST31000524AS 1TB           | 2        | 0.97%   |
| Seagate ST1000DM010-2EP102 1TB     | 2        | 0.97%   |
| Seagate ST1000DM003-1SB102 1TB     | 2        | 0.97%   |
| Seagate ST1000DM003-1ER162 1TB     | 2        | 0.97%   |
| Samsung HD501LJ 500GB              | 2        | 0.97%   |
| LDLC F8+M.2 240 240GB              | 2        | 0.97%   |
| Kingston SV300S37A120G 120GB       | 2        | 0.97%   |
| Kingston SUV500MS120G 120GB        | 2        | 0.97%   |
| Kingston SUV400S37240G 240GB       | 2        | 0.97%   |
| Kingston SA400S37120G 120GB        | 2        | 0.97%   |
| HGST HUS726020ALA610 2TB           | 2        | 0.97%   |
| Crucial CT250P2SSD8 250GB          | 2        | 0.97%   |
| Crucial CT240BX500SSD1 240GB       | 2        | 0.97%   |
| Crucial CT1000P1SSD8 1TB           | 2        | 0.97%   |
| Crucial CT1000BX500SSD1 1TB        | 2        | 0.97%   |
| Apple SSD SM256E 256GB             | 2        | 0.97%   |
| WDC WDS240G2G0A-00JH30 240GB       | 1        | 0.49%   |
| WDC WDS100T2G0A-00JH30 1TB         | 1        | 0.49%   |
| WDC WD80EZAZ-11TDBA0 8TB           | 1        | 0.49%   |
| WDC WD800BEVT-75ZCT2 80GB          | 1        | 0.49%   |
| WDC WD6400AAKS-22A7B0 640GB        | 1        | 0.49%   |
| WDC WD6003FFBX-68MU3N0 6TB         | 1        | 0.49%   |
| WDC WD5002ABYS-18B1B0 500GB        | 1        | 0.49%   |
| WDC WD5000LPLX-75ZNTT0 500GB       | 1        | 0.49%   |
| WDC WD40EFRX-68N32N0 4TB           | 1        | 0.49%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1        | 0.49%   |
| WDC WD30EZRX-00D8PB0 3TB           | 1        | 0.49%   |
| WDC WD30EFRX-68AX9N0 3TB           | 1        | 0.49%   |
| WDC WD3000GLFS-01F8U0 304GB        | 1        | 0.49%   |
| WDC WD2503ABYX-01WERA1 256GB       | 1        | 0.49%   |
| WDC WD2500JS-75NCB3 250GB          | 1        | 0.49%   |
| WDC WD2500BEVS-60UST0 250GB        | 1        | 0.49%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 1        | 0.49%   |
| WDC WD20EZRX-00D8PB0 2TB           | 1        | 0.49%   |
| WDC WD20EARX-00PASB0 2TB           | 1        | 0.49%   |
| WDC WD2002FYPS-02W3B0 2TB          | 1        | 0.49%   |
| WDC WD2002FFSX-68PF8N0 2TB         | 1        | 0.49%   |
| WDC WD15EADS-00P8B0 1.5TB          | 1        | 0.49%   |
| WDC WD1500HLFS-01G6U4 150GB        | 1        | 0.49%   |
| WDC WD10EZEX-22MFCA0 1TB           | 1        | 0.49%   |
| WDC WD10EZEX-00UD2A0 1TB           | 1        | 0.49%   |
| WDC WD10EAVS-00D7B0 1TB            | 1        | 0.49%   |
| WDC WD10EARS-00Y5B1 1TB            | 1        | 0.49%   |
| WDC WD1001FAES-75W7A0 1TB          | 1        | 0.49%   |
| WDC WD Elements 25A1 4TB           | 1        | 0.49%   |
| Transcend TS64GSSD340 64GB         | 1        | 0.49%   |
| Transcend TS64GMSA230S 64GB        | 1        | 0.49%   |
| Transcend TS500GMTE240S 500GB      | 1        | 0.49%   |
| Transcend TS32GMTS400S 32GB        | 1        | 0.49%   |
| Transcend TS32GMSA370 32GB         | 1        | 0.49%   |
| Transcend TS16GMTS400 16GB         | 1        | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 32       | 42     | 40%     |
| WDC                 | 24       | 45     | 30%     |
| Toshiba             | 6        | 12     | 7.5%    |
| Samsung Electronics | 6        | 12     | 7.5%    |
| HGST                | 4        | 7      | 5%      |
| Hitachi             | 3        | 3      | 3.75%   |
| SABRENT             | 1        | 1      | 1.25%   |
| Maxtor              | 1        | 2      | 1.25%   |
| Generic             | 1        | 1      | 1.25%   |
| Fujitsu             | 1        | 1      | 1.25%   |
| Apple               | 1        | 3      | 1.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 13       | 23     | 14.13%  |
| Crucial             | 11       | 14     | 11.96%  |
| Samsung Electronics | 10       | 11     | 10.87%  |
| Transcend           | 9        | 9      | 9.78%   |
| Phison              | 8        | 9      | 8.7%    |
| SanDisk             | 5        | 11     | 5.43%   |
| Hoodisk             | 4        | 4      | 4.35%   |
| China               | 4        | 9      | 4.35%   |
| PNY                 | 3        | 4      | 3.26%   |
| OCZ                 | 3        | 4      | 3.26%   |
| Intel               | 3        | 4      | 3.26%   |
| Corsair             | 3        | 4      | 3.26%   |
| WDC                 | 2        | 2      | 2.17%   |
| Apple               | 2        | 2      | 2.17%   |
| Toshiba             | 1        | 1      | 1.09%   |
| SPCC                | 1        | 1      | 1.09%   |
| Silicon Power       | 1        | 1      | 1.09%   |
| ShiJi               | 1        | 2      | 1.09%   |
| Pccooler            | 1        | 1      | 1.09%   |
| NVMe                | 1        | 1      | 1.09%   |
| Micron Technology   | 1        | 2      | 1.09%   |
| LITEON              | 1        | 2      | 1.09%   |
| Kingchuxing         | 1        | 2      | 1.09%   |
| Innodisk            | 1        | 1      | 1.09%   |
| Indilinx            | 1        | 5      | 1.09%   |
| FORESEE             | 1        | 2      | 1.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 87       | 131    | 52.1%   |
| HDD  | 63       | 129    | 37.72%  |
| NVMe | 17       | 22     | 10.18%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 131      | 260    | 88.51%  |
| NVMe | 17       | 22     | 11.49%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 108      | 167    | 68.35%  |
| 0.51-1.0   | 24       | 41     | 15.19%  |
| 1.01-2.0   | 16       | 31     | 10.13%  |
| 2.01-3.0   | 4        | 9      | 2.53%   |
| 4.01-10.0  | 4        | 7      | 2.53%   |
| 3.01-4.0   | 2        | 5      | 1.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 44       | 28.76%  |
| 1-20           | 33       | 21.57%  |
| 21-50          | 18       | 11.76%  |
| 251-500        | 17       | 11.11%  |
| 51-100         | 17       | 11.11%  |
| 501-1000       | 16       | 10.46%  |
| 1001-2000      | 4        | 2.61%   |
| More than 3000 | 2        | 1.31%   |
| 2001-3000      | 2        | 1.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 126      | 81.29%  |
| 21-50     | 14       | 9.03%   |
| 251-500   | 6        | 3.87%   |
| 101-250   | 4        | 2.58%   |
| 51-100    | 3        | 1.94%   |
| 1001-2000 | 1        | 0.65%   |
| 501-1000  | 1        | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Samsung Electronics HD501LJ 500GB  | 2        | 2      | 6.67%   |
| WDC WD6400AAKS-22A7B0 640GB        | 1        | 1      | 3.33%   |
| WDC WD5002ABYS-18B1B0 500GB        | 1        | 1      | 3.33%   |
| WDC WD30EFRX-68AX9N0 3TB           | 1        | 4      | 3.33%   |
| WDC WD2500BEVS-60UST0 250GB        | 1        | 1      | 3.33%   |
| WDC WD2002FYPS-02W3B0 2TB          | 1        | 1      | 3.33%   |
| WDC WD15EADS-00P8B0 1.5TB          | 1        | 1      | 3.33%   |
| WDC WD10EZEX-08WN4A0 1TB           | 1        | 1      | 3.33%   |
| WDC WD10EAVS-00D7B0 1TB            | 1        | 1      | 3.33%   |
| WDC WD10EARS-00Y5B1 1TB            | 1        | 1      | 3.33%   |
| WDC WD1001FAES-75W7A0 1TB          | 1        | 1      | 3.33%   |
| Seagate ST9500325AS 500GB          | 1        | 1      | 3.33%   |
| Seagate ST500VT000-1DK142 500GB    | 1        | 1      | 3.33%   |
| Seagate ST500LM000-SSHD-8GB        | 1        | 2      | 3.33%   |
| Seagate ST500DM002-1BD142 500GB    | 1        | 1      | 3.33%   |
| Seagate ST380013AS 80GB            | 1        | 2      | 3.33%   |
| Seagate ST3250620AS 250GB          | 1        | 1      | 3.33%   |
| Seagate ST3160023AS 160GB          | 1        | 1      | 3.33%   |
| Seagate ST31000524AS 1TB           | 1        | 1      | 3.33%   |
| Seagate ST1000NM0011 1TB           | 1        | 1      | 3.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 3.33%   |
| Samsung Electronics HD322GJ 320GB  | 1        | 1      | 3.33%   |
| Samsung Electronics HD256GJ 250GB  | 1        | 1      | 3.33%   |
| Samsung Electronics HD103UJ 1TB    | 1        | 1      | 3.33%   |
| OCZ VERTEX-TURBO 32GB              | 1        | 2      | 3.33%   |
| Kingston SV300S37A120G 120GB       | 1        | 1      | 3.33%   |
| Intel SSDSA2M080G2GN 80GB          | 1        | 1      | 3.33%   |
| Hitachi HTS542525K9SA00 250GB      | 1        | 1      | 3.33%   |
| Corsair Force 3 SSD 120GB          | 1        | 2      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 13     | 37.04%  |
| Seagate             | 9        | 12     | 33.33%  |
| Samsung Electronics | 3        | 5      | 11.11%  |
| OCZ                 | 1        | 2      | 3.7%    |
| Kingston            | 1        | 1      | 3.7%    |
| Intel               | 1        | 1      | 3.7%    |
| Hitachi             | 1        | 1      | 3.7%    |
| Corsair             | 1        | 2      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 13     | 43.48%  |
| Seagate             | 9        | 12     | 39.13%  |
| Samsung Electronics | 3        | 5      | 13.04%  |
| Hitachi             | 1        | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 20       | 31     | 83.33%  |
| SSD  | 4        | 6      | 16.67%  |

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
| Works    | 130      | 240    | 82.8%   |
| Malfunc  | 23       | 37     | 14.65%  |
| Detected | 4        | 5      | 2.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 107      | 56.61%  |
| AMD                           | 42       | 22.22%  |
| Micron/Crucial Technology     | 6        | 3.17%   |
| ASMedia Technology            | 6        | 3.17%   |
| Samsung Electronics           | 5        | 2.65%   |
| Silicon Motion                | 3        | 1.59%   |
| Marvell Technology Group      | 3        | 1.59%   |
| JMicron Technology            | 3        | 1.59%   |
| Broadcom / LSI                | 3        | 1.59%   |
| VIA Technologies              | 2        | 1.06%   |
| Chelsio Communications        | 2        | 1.06%   |
| Silicon Image                 | 1        | 0.53%   |
| Phison Electronics            | 1        | 0.53%   |
| Nvidia                        | 1        | 0.53%   |
| Micron Technology             | 1        | 0.53%   |
| Integrated Technology Express | 1        | 0.53%   |
| Hewlett-Packard               | 1        | 0.53%   |
| Unknown                       | 1        | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 25       | 11.47%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 14       | 6.42%   |
| AMD FCH SATA Controller [IDE mode]                                               | 9        | 4.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 8        | 3.67%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 7        | 3.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 6        | 2.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6        | 2.75%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 6        | 2.75%   |
| AMD 400 Series Chipset SATA Controller                                           | 6        | 2.75%   |
| Intel SATA Controller [RAID mode]                                                | 5        | 2.29%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 5        | 2.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 5        | 2.29%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4        | 1.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4        | 1.83%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 4        | 1.83%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4        | 1.83%   |
| Unknown                                                                          | 4        | 1.83%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 3        | 1.38%   |
| JMicron JMB363 SATA/IDE Controller                                               | 3        | 1.38%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3        | 1.38%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3        | 1.38%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3        | 1.38%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 3        | 1.38%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 3        | 1.38%   |
| AMD 500 Series Chipset SATA Controller                                           | 3        | 1.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2        | 0.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2        | 0.92%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2        | 0.92%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 2        | 0.92%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2        | 0.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2        | 0.92%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 2        | 0.92%   |
| Intel C600/X79 series chipset SATA RAID Controller                               | 2        | 0.92%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 2        | 0.92%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 2        | 0.92%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 2        | 0.92%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 2        | 0.92%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 2        | 0.92%   |
| AMD FCH SATA Controller D                                                        | 2        | 0.92%   |
| AMD 300 Series Chipset SATA Controller                                           | 2        | 0.92%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1        | 0.46%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1        | 0.46%   |
| VIA VT6415 PATA IDE Host Controller                                              | 1        | 0.46%   |
| Silicon Image SiI 3124 PCI-X Serial ATA Controller                               | 1        | 0.46%   |
| Samsung NVMe SSD Controller 980                                                  | 1        | 0.46%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1        | 0.46%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1        | 0.46%   |
| Nvidia MCP51 IDE                                                                 | 1        | 0.46%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1        | 0.46%   |
| Micron/Crucial NVMe Controller                                                   | 1        | 0.46%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                          | 1        | 0.46%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1        | 0.46%   |
| Intel SSD 660P Series                                                            | 1        | 0.46%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1        | 0.46%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1        | 0.46%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 1        | 0.46%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 1        | 0.46%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 1        | 0.46%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 1        | 0.46%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1        | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 129      | 68.25%  |
| IDE  | 28       | 14.81%  |
| NVMe | 18       | 9.52%   |
| RAID | 9        | 4.76%   |
| SCSI | 3        | 1.59%   |
| SAS  | 2        | 1.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 109      | 71.24%  |
| AMD    | 44       | 28.76%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD GX-412TC SOC                            | 14       | 9.03%   |
| Intel Core i5-4300Y CPU @ 1.60GHz           | 3        | 1.94%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 3        | 1.94%   |
| Intel Core i3-3225 CPU @ 3.30GHz            | 3        | 1.94%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 3        | 1.94%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 1.94%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 1.94%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz         | 2        | 1.29%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.29%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 1.29%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 1.29%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 2        | 1.29%   |
| Intel Core 2 Quad CPU                       | 2        | 1.29%   |
| Intel Celeron CPU J3160 @ 1.60GHz           | 2        | 1.29%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2        | 1.29%   |
| Intel Atom CPU D525 @ 1.80GHz               | 2        | 1.29%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 1.29%   |
| AMD G-T40E Processor                        | 2        | 1.29%   |
| AMD Athlon 5350 APU with Radeon R3          | 2        | 1.29%   |
| Intel Xeon W-2255 CPU @ 3.70GHz             | 1        | 0.65%   |
| Intel Xeon E-2124G CPU @ 3.40GHz            | 1        | 0.65%   |
| Intel Xeon D-2187NT CPU @ 2.00GHz           | 1        | 0.65%   |
| Intel Xeon D-2146NT CPU @ 2.30GHz           | 1        | 0.65%   |
| Intel Xeon CPU W3530 @ 2.80GHz              | 1        | 0.65%   |
| Intel Xeon CPU E31260L @ 2.40GHz            | 1        | 0.65%   |
| Intel Xeon CPU E3-1275 V2 @ 3.50GHz         | 1        | 0.65%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz         | 1        | 0.65%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz        | 1        | 0.65%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz         | 1        | 0.65%   |
| Intel Xeon CPU E3-1225 V2 @ 3.20GHz         | 1        | 0.65%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1        | 0.65%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.65%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.65%   |
| Intel Pentium CPU G630T @ 2.30GHz           | 1        | 0.65%   |
| Intel Pentium CPU G4400T @ 2.90GHz          | 1        | 0.65%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.65%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 0.65%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.65%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.65%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1        | 0.65%   |
| Intel Core i7-4770R CPU @ 3.20GHz           | 1        | 0.65%   |
| Intel Core i7-3930K CPU @ 3.20GHz           | 1        | 0.65%   |
| Intel Core i7-3820 CPU @ 3.60GHz            | 1        | 0.65%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 0.65%   |
| Intel Core i7-2700K CPU @ 3.50GHz           | 1        | 0.65%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 0.65%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 1        | 0.65%   |
| Intel Core i7 CPU                           | 1        | 0.65%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.65%   |
| Intel Core i5-8400T CPU @ 1.70GHz           | 1        | 0.65%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 0.65%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 0.65%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1        | 0.65%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1        | 0.65%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 0.65%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1        | 0.65%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 1        | 0.65%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 1        | 0.65%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1        | 0.65%   |
| Intel Core i5-3570S CPU @ 3.10GHz           | 1        | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 29       | 18.71%  |
| Intel Celeron           | 17       | 10.97%  |
| AMD GX                  | 16       | 10.32%  |
| Intel Xeon              | 13       | 8.39%   |
| Intel Core i3           | 13       | 8.39%   |
| Intel Core i7           | 11       | 7.1%    |
| Intel Atom              | 11       | 7.1%    |
| AMD Ryzen 5             | 7        | 4.52%   |
| Intel Core 2 Quad       | 6        | 3.87%   |
| AMD Ryzen 7             | 6        | 3.87%   |
| Other                   | 4        | 2.58%   |
| Intel Pentium           | 4        | 2.58%   |
| Intel Pentium Gold      | 2        | 1.29%   |
| AMD G                   | 2        | 1.29%   |
| AMD Athlon 64 X2        | 2        | 1.29%   |
| AMD Athlon              | 2        | 1.29%   |
| AMD A8                  | 2        | 1.29%   |
| Intel Pentium Dual-Core | 1        | 0.65%   |
| Intel Core 2 Duo        | 1        | 0.65%   |
| AMD Ryzen 9             | 1        | 0.65%   |
| AMD Ryzen 3             | 1        | 0.65%   |
| AMD Phenom II X4        | 1        | 0.65%   |
| AMD FX                  | 1        | 0.65%   |
| AMD E1                  | 1        | 0.65%   |
| AMD A10                 | 1        | 0.65%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 71       | 46.1%   |
| 2       | 47       | 30.52%  |
| 6       | 8        | 5.19%   |
| 16      | 7        | 4.55%   |
| 8       | 7        | 4.55%   |
| 12      | 6        | 3.9%    |
| Unknown | 6        | 3.9%    |
| 32      | 1        | 0.65%   |
| 10      | 1        | 0.65%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 151      | 98.69%  |
| Unknown | 2        | 1.31%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 100      | 65.36%  |
| 2       | 47       | 30.72%  |
| Unknown | 6        | 3.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Puma          | 15       | 9.74%   |
| Skylake       | 14       | 9.09%   |
| KabyLake      | 14       | 9.09%   |
| Haswell       | 14       | 9.09%   |
| SandyBridge   | 13       | 8.44%   |
| IvyBridge     | 13       | 8.44%   |
| Silvermont    | 9        | 5.84%   |
| Zen 2         | 6        | 3.9%    |
| Penryn        | 6        | 3.9%    |
| Bonnell       | 6        | 3.9%    |
| Unknown       | 5        | 3.25%   |
| Zen+          | 4        | 2.6%    |
| Broadwell     | 4        | 2.6%    |
| Zen 3         | 3        | 1.95%   |
| Nehalem       | 3        | 1.95%   |
| Jaguar        | 3        | 1.95%   |
| Goldmont plus | 3        | 1.95%   |
| Goldmont      | 3        | 1.95%   |
| Bobcat        | 3        | 1.95%   |
| Zen           | 2        | 1.3%    |
| Westmere      | 2        | 1.3%    |
| Piledriver    | 2        | 1.3%    |
| Core          | 2        | 1.3%    |
| Steamroller   | 1        | 0.65%   |
| K8 Hammer     | 1        | 0.65%   |
| K10           | 1        | 0.65%   |
| Excavator     | 1        | 0.65%   |
| CometLake     | 1        | 0.65%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 78       | 59.09%  |
| Nvidia                     | 22       | 16.67%  |
| AMD                        | 22       | 16.67%  |
| Matrox Electronics Systems | 5        | 3.79%   |
| ASPEED Technology          | 5        | 3.79%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6        | 4.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6        | 4.51%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6        | 4.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5        | 3.76%   |
| Intel HD Graphics 530                                                                    | 5        | 3.76%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 5        | 3.76%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4        | 3.01%   |
| Intel HD Graphics 510                                                                    | 4        | 3.01%   |
| Nvidia GT218 [GeForce 210]                                                               | 3        | 2.26%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3        | 2.26%   |
| Intel HD Graphics 620                                                                    | 3        | 2.26%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 3        | 2.26%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3        | 2.26%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 2.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3        | 2.26%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 3        | 2.26%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3        | 2.26%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 2        | 1.5%    |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2        | 1.5%    |
| Matrox Electronics Systems MGA G200EH                                                    | 2        | 1.5%    |
| Intel HD Graphics 5500                                                                   | 2        | 1.5%    |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 2        | 1.5%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2        | 1.5%    |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                                  | 2        | 1.5%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 1.5%    |
| AMD Cezanne                                                                              | 2        | 1.5%    |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1        | 0.75%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 0.75%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 0.75%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1        | 0.75%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1        | 0.75%   |
| Nvidia GF114 [GeForce GTX 560]                                                           | 1        | 0.75%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                                        | 1        | 0.75%   |
| Nvidia GF110 [GeForce GTX 570]                                                           | 1        | 0.75%   |
| Nvidia GA106 [RTX A2000 12GB]                                                            | 1        | 0.75%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                                           | 1        | 0.75%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 1        | 0.75%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 1        | 0.75%   |
| Nvidia C51PV [GeForce 6150]                                                              | 1        | 0.75%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1        | 0.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1        | 0.75%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1        | 0.75%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 1        | 0.75%   |
| Intel HD Graphics P530                                                                   | 1        | 0.75%   |
| Intel HD Graphics 630                                                                    | 1        | 0.75%   |
| Intel HD Graphics 6000                                                                   | 1        | 0.75%   |
| Intel HD Graphics 500                                                                    | 1        | 0.75%   |
| Intel HD Graphics                                                                        | 1        | 0.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1        | 0.75%   |
| Intel Crystal Well Integrated Iris Pro Graphics 5200                                     | 1        | 0.75%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 0.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics P630]                                               | 1        | 0.75%   |
| Intel Coffee Lake UHD 610 Graphics Controller                                            | 1        | 0.75%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1        | 0.75%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1        | 0.75%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1        | 0.75%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1        | 0.75%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1        | 0.75%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1        | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 74       | 48.05%  |
| Other      | 22       | 14.29%  |
| 1 x Nvidia | 22       | 14.29%  |
| 1 x AMD    | 22       | 14.29%  |
| 1 x Matrox | 5        | 3.25%   |
| 1 x ASPEED | 5        | 3.25%   |
| 2 x Intel  | 4        | 2.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 114      | 74.03%  |
| Unknown     | 25       | 16.23%  |
| Proprietary | 15       | 9.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 127      | 83.01%  |
| 1.01-2.0   | 7        | 4.58%   |
| 7.01-8.0   | 6        | 3.92%   |
| 0.51-1.0   | 6        | 3.92%   |
| 0.01-0.5   | 4        | 2.61%   |
| 5.01-6.0   | 2        | 1.31%   |
| 8.01-16.0  | 1        | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 7        | 20.59%  |
| Hewlett-Packard      | 4        | 11.76%  |
| Samsung Electronics  | 3        | 8.82%   |
| Iiyama               | 3        | 8.82%   |
| Idek Iiyama          | 3        | 8.82%   |
| Goldstar             | 3        | 8.82%   |
| Ancor Communications | 3        | 8.82%   |
| Sony                 | 1        | 2.94%   |
| PRI                  | 1        | 2.94%   |
| Philips              | 1        | 2.94%   |
| Packard Bell         | 1        | 2.94%   |
| LG Electronics       | 1        | 2.94%   |
| CKL                  | 1        | 2.94%   |
| BenQ                 | 1        | 2.94%   |
| AOC                  | 1        | 2.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Sony TV  *00 SNYF903 3840x2160 950x540mm 43.0-inch                    | 1        | 2.94%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 410x260mm 19.1-inch   | 1        | 2.94%   |
| Samsung Electronics LCD Monitor SyncMaster 3520x1200                  | 1        | 2.94%   |
| Samsung Electronics LCD Monitor S24R35x 1920x1080                     | 1        | 2.94%   |
| PRI LED-MONITOR PRI0828 3840x2160 1150x650mm 52.0-inch                | 1        | 2.94%   |
| Philips LCD Monitor PHLC00B 1280x1024 340x270mm 17.1-inch             | 1        | 2.94%   |
| Packard Bell Viseo 200Ws PKB00C2 1600x900 440x250mm 19.9-inch         | 1        | 2.94%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 1        | 2.94%   |
| Iiyama PLX2483H IVM6114 1920x1080 530x300mm 24.0-inch                 | 1        | 2.94%   |
| Iiyama PL2783Q IVM661F 2560x1440 600x340mm 27.2-inch                  | 1        | 2.94%   |
| Iiyama PL2474H IVM6137 1920x1080 520x290mm 23.4-inch                  | 1        | 2.94%   |
| Idek Iiyama LCD Monitor PLX2783H 1920x1080                            | 1        | 2.94%   |
| Idek Iiyama LCD Monitor PL2409HD 1920x1080                            | 1        | 2.94%   |
| Idek Iiyama LCD Monitor PL2206W 1680x1050                             | 1        | 2.94%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 470x300mm 22.0-inch           | 1        | 2.94%   |
| Hewlett-Packard HPQ 8300 AiO HWP4212 1920x1080 510x290mm 23.1-inch    | 1        | 2.94%   |
| Hewlett-Packard 2310e HWP2909 1920x1080 510x290mm 23.1-inch           | 1        | 2.94%   |
| Hewlett-Packard 2211 HWP2938 1920x1080 480x270mm 21.7-inch            | 1        | 2.94%   |
| Goldstar L1730S GSM438D 1280x1024 340x270mm 17.1-inch                 | 1        | 2.94%   |
| Goldstar 27GK750F GSM770F 1920x1080 600x340mm 27.2-inch               | 1        | 2.94%   |
| Goldstar 19MB35 GSM4C23 1280x1024 380x300mm 19.1-inch                 | 1        | 2.94%   |
| Dell P2418D DELD0C2 2560x1440 530x300mm 24.0-inch                     | 1        | 2.94%   |
| Dell P1917S DELD092 1280x1024 380x300mm 19.1-inch                     | 1        | 2.94%   |
| Dell P1917S DELD091 1280x1024 380x300mm 19.1-inch                     | 1        | 2.94%   |
| Dell P1911 DELA073 1440x900 410x260mm 19.1-inch                       | 1        | 2.94%   |
| Dell LCD Monitor U2414H                                               | 1        | 2.94%   |
| Dell E2014H DELD03B 1600x900 430x240mm 19.4-inch                      | 1        | 2.94%   |
| Dell E1715S DELD062 1280x1024 340x270mm 17.1-inch                     | 1        | 2.94%   |
| CKL LCD Monitor CKL0001 1920x1200 1150x650mm 52.0-inch                | 1        | 2.94%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                     | 1        | 2.94%   |
| AOC Q2577W AOC2577 2560x1440 550x310mm 24.9-inch                      | 1        | 2.94%   |
| Ancor Communications ASUS VN247 ACI24C3 1920x1080 520x290mm 23.4-inch | 1        | 2.94%   |
| Ancor Communications ASUS PB238 ACI23A2 1920x1080 510x290mm 23.1-inch | 1        | 2.94%   |
| Ancor Communications ASUS MG278 ACI27A8 2560x1440 600x340mm 27.2-inch | 1        | 2.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 12       | 35.29%  |
| 1280x1024 (SXGA)   | 6        | 17.65%  |
| 2560x1440 (QHD)    | 4        | 11.76%  |
| 3840x2160 (4K)     | 2        | 5.88%   |
| 1680x1050 (WSXGA+) | 2        | 5.88%   |
| 1600x900 (HD+)     | 2        | 5.88%   |
| 1440x900 (WXGA+)   | 2        | 5.88%   |
| 3520x1200          | 1        | 2.94%   |
| 2560x1080          | 1        | 2.94%   |
| 1920x1200 (WUXGA)  | 1        | 2.94%   |
| Unknown            | 1        | 2.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 19      | 7        | 21.21%  |
| Unknown | 6        | 18.18%  |
| 23      | 5        | 15.15%  |
| 27      | 3        | 9.09%   |
| 24      | 3        | 9.09%   |
| 17      | 3        | 9.09%   |
| 52      | 2        | 6.06%   |
| 21      | 2        | 6.06%   |
| 43      | 1        | 3.03%   |
| 22      | 1        | 3.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 11       | 33.33%  |
| 401-500     | 7        | 21.21%  |
| Unknown     | 6        | 18.18%  |
| 351-400     | 3        | 9.09%   |
| 301-350     | 3        | 9.09%   |
| 1001-1500   | 2        | 6.06%   |
| 901-1000    | 1        | 3.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 18       | 54.55%  |
| 5/4     | 6        | 18.18%  |
| Unknown | 6        | 18.18%  |
| 16/10   | 3        | 9.09%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch?? | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 10       | 30.3%   |
| 151-200        | 7        | 21.21%  |
| Unknown        | 6        | 18.18%  |
| 301-350        | 3        | 9.09%   |
| 141-150        | 3        | 9.09%   |
| More than 1000 | 2        | 6.06%   |
| 251-300        | 1        | 3.03%   |
| 501-1000       | 1        | 3.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 19       | 57.58%  |
| 101-120 | 6        | 18.18%  |
| Unknown | 6        | 18.18%  |
| 1-50    | 1        | 3.03%   |
| 121-160 | 1        | 3.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 120      | 77.92%  |
| 1     | 33       | 21.43%  |
| 2     | 1        | 0.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 111      | 52.36%  |
| Realtek Semiconductor           | 64       | 30.19%  |
| Qualcomm Atheros                | 12       | 5.66%   |
| Broadcom                        | 7        | 3.3%    |
| Ralink Technology               | 2        | 0.94%   |
| Qualcomm                        | 2        | 0.94%   |
| D-Link System                   | 2        | 0.94%   |
| Chelsio Communications          | 2        | 0.94%   |
| VIA Technologies                | 1        | 0.47%   |
| TP-Link                         | 1        | 0.47%   |
| Qualcomm Atheros Communications | 1        | 0.47%   |
| Microchip Technology            | 1        | 0.47%   |
| MediaTek                        | 1        | 0.47%   |
| Huawei Technologies             | 1        | 0.47%   |
| Edimax Technology               | 1        | 0.47%   |
| American Megatrends             | 1        | 0.47%   |
| AMD                             | 1        | 0.47%   |
| 3Com                            | 1        | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 58       | 22.22%  |
| Intel I211 Gigabit Network Connection                                         | 27       | 10.34%  |
| Intel I210 Gigabit Network Connection                                         | 16       | 6.13%   |
| Intel 82574L Gigabit Network Connection                                       | 16       | 6.13%   |
| Intel Wi-Fi 6 AX200                                                           | 7        | 2.68%   |
| Intel I350 Gigabit Network Connection                                         | 7        | 2.68%   |
| Realtek RTL8125 2.5GbE Controller                                             | 6        | 2.3%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 6        | 2.3%    |
| Intel Ethernet Connection I217-LM                                             | 5        | 1.92%   |
| Intel 82579V Gigabit Network Connection                                       | 5        | 1.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 1.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 4        | 1.53%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 3        | 1.15%   |
| Intel Ethernet Controller I225-V                                              | 3        | 1.15%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 1.15%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 1.15%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 1.15%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2        | 0.77%   |
| Ralink RT5370 Wireless Adapter                                                | 2        | 0.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 0.77%   |
| Qualcomm ALCATEL Composite RNDIS Interface                                    | 2        | 0.77%   |
| Intel Wireless 7260                                                           | 2        | 0.77%   |
| Intel Wireless 3165                                                           | 2        | 0.77%   |
| Intel Ethernet Controller X550                                                | 2        | 0.77%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 2        | 0.77%   |
| Intel Ethernet Connection X553 1GbE                                           | 2        | 0.77%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 0.77%   |
| Intel Ethernet Connection (5) I219-LM                                         | 2        | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2        | 0.77%   |
| Intel 82583V Gigabit Network Connection                                       | 2        | 0.77%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 0.77%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 2        | 0.77%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 0.77%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1        | 0.38%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 0.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1        | 0.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.38%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.38%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                        | 1        | 0.38%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                   | 1        | 0.38%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1        | 0.38%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 1        | 0.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.38%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 0.38%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 0.38%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 0.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1        | 0.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.38%   |
| Microchip HTC Hub Controller                                                  | 1        | 0.38%   |
| MediaTek 802.11ac Wireless LAN Card                                           | 1        | 0.38%   |
| Intel Wireless-AC 9260                                                        | 1        | 0.38%   |
| Intel Wireless 7265                                                           | 1        | 0.38%   |
| Intel Wireless 3160                                                           | 1        | 0.38%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 1        | 0.38%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 1        | 0.38%   |
| Intel Ethernet Controller I225-LM                                             | 1        | 0.38%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1        | 0.38%   |
| Intel Ethernet Connection X722 for 10GbE backplane                            | 1        | 0.38%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 1        | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 19       | 47.5%   |
| Qualcomm Atheros                | 9        | 22.5%   |
| Realtek Semiconductor           | 6        | 15%     |
| Ralink Technology               | 2        | 5%      |
| TP-Link                         | 1        | 2.5%    |
| Qualcomm Atheros Communications | 1        | 2.5%    |
| MediaTek                        | 1        | 2.5%    |
| Edimax Technology               | 1        | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                             | 7        | 17.5%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 4        | 10%     |
| Ralink RT5370 Wireless Adapter                                  | 2        | 5%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 2        | 5%      |
| Intel Wireless 7260                                             | 2        | 5%      |
| Intel Wireless 3165                                             | 2        | 5%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 2        | 5%      |
| TP-Link Archer T3U [Realtek RTL8812BU]                          | 1        | 2.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                              | 1        | 2.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 1        | 2.5%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter        | 1        | 2.5%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                          | 1        | 2.5%    |
| Realtek RTL8191SEvA Wireless LAN Controller                     | 1        | 2.5%    |
| Realtek RTL8188EE Wireless Network Adapter                      | 1        | 2.5%    |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1        | 2.5%    |
| Qualcomm Atheros AR9271 802.11n                                 | 1        | 2.5%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 1        | 2.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 1        | 2.5%    |
| MediaTek 802.11ac Wireless LAN Card                             | 1        | 2.5%    |
| Intel Wireless-AC 9260                                          | 1        | 2.5%    |
| Intel Wireless 7265                                             | 1        | 2.5%    |
| Intel Wireless 3160                                             | 1        | 2.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                          | 1        | 2.5%    |
| Intel Centrino Advanced-N 6235                                  | 1        | 2.5%    |
| Intel Alder Lake-S PCH CNVi WiFi                                | 1        | 2.5%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]  | 1        | 2.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 104      | 55.91%  |
| Realtek Semiconductor  | 62       | 33.33%  |
| Broadcom               | 7        | 3.76%   |
| Qualcomm Atheros       | 3        | 1.61%   |
| Qualcomm               | 2        | 1.08%   |
| D-Link System          | 2        | 1.08%   |
| Chelsio Communications | 2        | 1.08%   |
| VIA Technologies       | 1        | 0.54%   |
| American Megatrends    | 1        | 0.54%   |
| AMD                    | 1        | 0.54%   |
| 3Com                   | 1        | 0.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 58       | 26.61%  |
| Intel I211 Gigabit Network Connection                                         | 27       | 12.39%  |
| Intel I210 Gigabit Network Connection                                         | 16       | 7.34%   |
| Intel 82574L Gigabit Network Connection                                       | 16       | 7.34%   |
| Intel I350 Gigabit Network Connection                                         | 7        | 3.21%   |
| Realtek RTL8125 2.5GbE Controller                                             | 6        | 2.75%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 6        | 2.75%   |
| Intel Ethernet Connection I217-LM                                             | 5        | 2.29%   |
| Intel 82579V Gigabit Network Connection                                       | 5        | 2.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 2.29%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 3        | 1.38%   |
| Intel Ethernet Controller I225-V                                              | 3        | 1.38%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 1.38%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 1.38%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 1.38%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2        | 0.92%   |
| Qualcomm ALCATEL Composite RNDIS Interface                                    | 2        | 0.92%   |
| Intel Ethernet Controller X550                                                | 2        | 0.92%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 2        | 0.92%   |
| Intel Ethernet Connection X553 1GbE                                           | 2        | 0.92%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 0.92%   |
| Intel Ethernet Connection (5) I219-LM                                         | 2        | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 0.92%   |
| Intel 82583V Gigabit Network Connection                                       | 2        | 0.92%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 0.92%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 2        | 0.92%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 0.92%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1        | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.46%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 0.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.46%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 1        | 0.46%   |
| Intel Ethernet Controller I225-LM                                             | 1        | 0.46%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1        | 0.46%   |
| Intel Ethernet Connection X722 for 10GbE backplane                            | 1        | 0.46%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 1        | 0.46%   |
| Intel Ethernet Connection I219-LM                                             | 1        | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 0.46%   |
| Intel Ethernet Connection (5) I219-V                                          | 1        | 0.46%   |
| Intel Ethernet Connection (14) I219-V                                         | 1        | 0.46%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 0.46%   |
| Intel 82575GB Gigabit Network Connection                                      | 1        | 0.46%   |
| Intel 82567V-2 Gigabit Network Connection                                     | 1        | 0.46%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1        | 0.46%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1        | 0.46%   |
| Chelsio T6425-CR Unified Wire Ethernet Controller                             | 1        | 0.46%   |
| Chelsio T520-CR Unified Wire Ethernet Controller                              | 1        | 0.46%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 1        | 0.46%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 0.46%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 1        | 0.46%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 1        | 0.46%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 1        | 0.46%   |
| American Megatrends Virtual Ethernet                                          | 1        | 0.46%   |
| AMD 79c970 [PCnet32 LANCE]                                                    | 1        | 0.46%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                                 | 1        | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 152      | 78.35%  |
| WiFi     | 39       | 20.1%   |
| Unknown  | 2        | 1.03%   |
| Modem    | 1        | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 143      | 97.95%  |
| WiFi     | 3        | 2.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 42       | 27.27%  |
| 2     | 35       | 22.73%  |
| 4     | 26       | 16.88%  |
| 3     | 25       | 16.23%  |
| 5     | 8        | 5.19%   |
| 6     | 5        | 3.25%   |
| 8     | 4        | 2.6%    |
| 7     | 4        | 2.6%    |
| 13    | 1        | 0.65%   |
| 12    | 1        | 0.65%   |
| 11    | 1        | 0.65%   |
| 10    | 1        | 0.65%   |
| 0     | 1        | 0.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 124      | 77.99%  |
| Yes  | 35       | 22.01%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 14       | 70%     |
| Cambridge Silicon Radio  | 2        | 10%     |
| Broadcom                 | 2        | 10%     |
| Realtek Semiconductor    | 1        | 5%      |
| HTC (High Tech Computer) | 1        | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 5        | 25%     |
| Intel Bluetooth wireless interface                                   | 4        | 20%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 2        | 10%     |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 10%     |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 5%      |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 1        | 5%      |
| Intel Wireless-AC 3168 Bluetooth                                     | 1        | 5%      |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 5%      |
| Intel AX210 Bluetooth                                                | 1        | 5%      |
| Intel AX201 Bluetooth                                                | 1        | 5%      |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 73       | 54.48%  |
| AMD                                          | 27       | 20.15%  |
| Nvidia                                       | 20       | 14.93%  |
| Focusrite-Novation                           | 2        | 1.49%   |
| Creative Labs                                | 2        | 1.49%   |
| C-Media Electronics                          | 2        | 1.49%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.75%   |
| VIA Technologies                             | 1        | 0.75%   |
| Texas Instruments                            | 1        | 0.75%   |
| Sony                                         | 1        | 0.75%   |
| Micronas                                     | 1        | 0.75%   |
| Kingston Technology                          | 1        | 0.75%   |
| iCreate Technologies                         | 1        | 0.75%   |
| Giga-Byte Technology                         | 1        | 0.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10       | 6.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9        | 5.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7        | 4.32%   |
| Intel 200 Series PCH HD Audio                                                                     | 7        | 4.32%   |
| AMD FCH Azalia Controller                                                                         | 7        | 4.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6        | 3.7%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 6        | 3.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5        | 3.09%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4        | 2.47%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4        | 2.47%   |
| Nvidia High Definition Audio Controller                                                           | 3        | 1.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3        | 1.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3        | 1.85%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3        | 1.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3        | 1.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3        | 1.85%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3        | 1.85%   |
| Intel Broadwell-U Audio Controller                                                                | 3        | 1.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3        | 1.85%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3        | 1.85%   |
| Intel 8 Series HD Audio Controller                                                                | 3        | 1.85%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3        | 1.85%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3        | 1.85%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2        | 1.23%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 2        | 1.23%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2        | 1.23%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2        | 1.23%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2        | 1.23%   |
| AMD Navi 10 HDMI Audio                                                                            | 2        | 1.23%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2        | 1.23%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2        | 1.23%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2        | 1.23%   |
| Unknown                                                                                           | 2        | 1.23%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1        | 0.62%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1        | 0.62%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1        | 0.62%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1        | 0.62%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1        | 0.62%   |
| Nvidia MCP51 High Definition Audio                                                                | 1        | 0.62%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1        | 0.62%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1        | 0.62%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1        | 0.62%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1        | 0.62%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1        | 0.62%   |
| Nvidia GF110 High Definition Audio Controller                                                     | 1        | 0.62%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1        | 0.62%   |
| Micronas Blue USB Audio 2.0                                                                       | 1        | 0.62%   |
| Kingston Technology HyperX 7.1 Audio                                                              | 1        | 0.62%   |
| Intel Crystal Well HD Audio Controller                                                            | 1        | 0.62%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1        | 0.62%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1        | 0.62%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1        | 0.62%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1        | 0.62%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1        | 0.62%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1        | 0.62%   |
| iCreate Technologies ASUS Xonar U7 Audio Device                                                   | 1        | 0.62%   |
| Giga-Byte Technology USB Audio                                                                    | 1        | 0.62%   |
| Focusrite-Novation Scarlett Solo USB                                                              | 1        | 0.62%   |
| Focusrite-Novation Scarlett Solo (3rd Gen.)                                                       | 1        | 0.62%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]                         | 1        | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 21       | 14.79%  |
| Samsung Electronics | 20       | 14.08%  |
| Kingston            | 19       | 13.38%  |
| Corsair             | 19       | 13.38%  |
| SK hynix            | 15       | 10.56%  |
| G.Skill             | 13       | 9.15%   |
| Crucial             | 12       | 8.45%   |
| Micron Technology   | 7        | 4.93%   |
| Transcend           | 3        | 2.11%   |
| Nanya Technology    | 3        | 2.11%   |
| Atermiter           | 2        | 1.41%   |
| Teikon              | 1        | 0.7%    |
| Patriot             | 1        | 0.7%    |
| OCZ                 | 1        | 0.7%    |
| Kimtigo             | 1        | 0.7%    |
| Hewlett-Packard     | 1        | 0.7%    |
| Goldenmars          | 1        | 0.7%    |
| Elpida              | 1        | 0.7%    |
| Apacer              | 1        | 0.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown                                                 | 21       | 13.91%  |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s   | 4        | 2.65%   |
| Samsung RAM M393A4K40CB2-CTD 32GB DIMM DDR4 2667MT/s    | 2        | 1.32%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 1600MT/s     | 2        | 1.32%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s     | 2        | 1.32%   |
| Micron RAM 8HTF12864AZ-800H1 1GB DIMM DDR2 800MT/s      | 2        | 1.32%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s     | 2        | 1.32%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s   | 2        | 1.32%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3200MT/s    | 2        | 1.32%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s | 2        | 1.32%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s     | 2        | 1.32%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1333MT/s     | 2        | 1.32%   |
| Atermiter RAM Module 8GB DIMM DDR3 800MT/s              | 2        | 1.32%   |
| Transcend RAM TS512MSK64V3H 4GB SODIMM DDR3 667MT/s     | 1        | 0.66%   |
| Transcend RAM TS1GLK72V6H 8GB DIMM DDR3 1600MT/s        | 1        | 0.66%   |
| Transcend RAM TS1GLH64V1H 8GB DIMM DDR4 2133MT/s        | 1        | 0.66%   |
| Teikon RAM TMTS8G58DFRBFIR-16 8GB SODIMM DDR3 1600MT/s  | 1        | 0.66%   |
| SK hynix RAM Module 4GB DIMM DDR3 1066MT/s              | 1        | 0.66%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 0.66%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 0.66%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB DDR3 1600MT/s         | 1        | 0.66%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 1        | 0.66%   |
| SK hynix RAM HMT351U7BFR8A-H9 4GB DIMM DDR3 1333MT/s    | 1        | 0.66%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 0.66%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s  | 1        | 0.66%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s  | 1        | 0.66%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s    | 1        | 0.66%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s    | 1        | 0.66%   |
| SK hynix RAM HMP125U6EFR8C-S6 2GB DIMM DDR2 800MT/s     | 1        | 0.66%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 2400MT/s  | 1        | 0.66%   |
| SK hynix RAM HMA82GR7DJR8N-XN 16GB DIMM DDR4 3200MT/s   | 1        | 0.66%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s    | 1        | 0.66%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s  | 1        | 0.66%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s             | 1        | 0.66%   |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s               | 1        | 0.66%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s   | 1        | 0.66%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s   | 1        | 0.66%   |
| Samsung RAM M471B2873FHS-CH9 4GB DIMM DDR3 1600MT/s     | 1        | 0.66%   |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s   | 1        | 0.66%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s  | 1        | 0.66%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s   | 1        | 0.66%   |
| Samsung RAM M393A2K40CB1-CRC 16GB DIMM DDR4 2400MT/s    | 1        | 0.66%   |
| Samsung RAM M391B5673DZ1-CH9 2GB DIMM 1333MT/s          | 1        | 0.66%   |
| Samsung RAM M391A1K43BB2-CTD 8GB DIMM DDR4 2667MT/s     | 1        | 0.66%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1333MT/s     | 1        | 0.66%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s     | 1        | 0.66%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s     | 1        | 0.66%   |
| Samsung RAM M378A5143EB1-CPB 4GB DIMM DDR4 2133MT/s     | 1        | 0.66%   |
| Samsung RAM M378A5143DB0-CPB 4GB DIMM DDR4 2133MT/s     | 1        | 0.66%   |
| Patriot RAM 3200 C16 Series 32GB DIMM DDR4 2667MT/s     | 1        | 0.66%   |
| OCZ RAM OCZ3G13331G 1GB DIMM DDR3 1333MT/s              | 1        | 0.66%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM 1334MT/s         | 1        | 0.66%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 800MT/s       | 1        | 0.66%   |
| Nanya RAM NT2GC64B88B0NF-CG 2GB DIMM DDR3 1333MT/s      | 1        | 0.66%   |
| Micron RAM MT8KTF51264HZ-1G 4GB DIMM DDR3 1600MT/s      | 1        | 0.66%   |
| Micron RAM MT41K512M16VRN-107 4GB DIMM DDR3 1600MT/s    | 1        | 0.66%   |
| Micron RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s  | 1        | 0.66%   |
| Micron RAM 8JTF25664AZ-1G4D1 2GB DIMM DDR3 1333MT/s     | 1        | 0.66%   |
| Micron RAM 16JTF51264AZ-1G4M1 4GB DIMM DDR3 1333MT/s    | 1        | 0.66%   |
| Kingston RAM KHX3600C17D4/16GX 16GB DIMM DDR4 2400MT/s  | 1        | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 70       | 53.85%  |
| DDR4    | 45       | 34.62%  |
| Unknown | 10       | 7.69%   |
| DDR2    | 5        | 3.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 96       | 74.42%  |
| SODIMM  | 32       | 24.81%  |
| Unknown | 1        | 0.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 50       | 36.23%  |
| 8192  | 43       | 31.16%  |
| 2048  | 23       | 16.67%  |
| 16384 | 12       | 8.7%    |
| 1024  | 6        | 4.35%   |
| 32768 | 4        | 2.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 39       | 29.32%  |
| 1333  | 26       | 19.55%  |
| 2667  | 12       | 9.02%   |
| 2400  | 12       | 9.02%   |
| 800   | 10       | 7.52%   |
| 3200  | 9        | 6.77%   |
| 2133  | 8        | 6.02%   |
| 1066  | 4        | 3.01%   |
| 2666  | 3        | 2.26%   |
| 1334  | 2        | 1.5%    |
| 667   | 2        | 1.5%    |
| 5200  | 1        | 0.75%   |
| 2933  | 1        | 0.75%   |
| 1400  | 1        | 0.75%   |
| 1332  | 1        | 0.75%   |
| 533   | 1        | 0.75%   |
| 400   | 1        | 0.75%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model               | Desktops | Percent |
|---------------------|----------|---------|
| Seiko Epson Printer | 1        | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Canon CanoScan LIDE 25 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Logitech                 | 2        | 50%     |
| Novatek Microelectronics | 1        | 25%     |
| Linux Foundation         | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Novatek HP High Definition 2MP Webcam | 1        | 25%     |
| Logitech Webcam C270                  | 1        | 25%     |
| Logitech C922 Pro Stream Webcam       | 1        | 25%     |
| Linux Foundation HD Camera            | 1        | 25%     |

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
| 1     | 75       | 48.39%  |
| 0     | 56       | 36.13%  |
| 2     | 17       | 10.97%  |
| 3     | 6        | 3.87%   |
| 4     | 1        | 0.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 81       | 67.5%   |
| Net/wireless             | 15       | 12.5%   |
| Bluetooth                | 9        | 7.5%    |
| Firewire controller      | 6        | 5%      |
| Sound                    | 3        | 2.5%    |
| Net/ethernet             | 2        | 1.67%   |
| Network                  | 1        | 0.83%   |
| Modem                    | 1        | 0.83%   |
| Graphics card            | 1        | 0.83%   |
| Card reader              | 1        | 0.83%   |

