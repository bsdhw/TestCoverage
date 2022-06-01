BSD in Russia - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for BSD in Russia.

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

Total: 175

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [cf5f498572](https://bsd-hardware.info/?probe=cf5f498572) | May 21, 2022 |
| HP            | ProBook 455 G7              | [c6944afe69](https://bsd-hardware.info/?probe=c6944afe69) | May 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [64600e1c24](https://bsd-hardware.info/?probe=64600e1c24) | May 11, 2022 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [89db84f7ec](https://bsd-hardware.info/?probe=89db84f7ec) | May 10, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [3ff916acf7](https://bsd-hardware.info/?probe=3ff916acf7) | May 09, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [33367fe342](https://bsd-hardware.info/?probe=33367fe342) | May 09, 2022 |
| Acer          | Aspire ES1-132              | [18426698ad](https://bsd-hardware.info/?probe=18426698ad) | May 02, 2022 |
| HP            | Pavilion g6                 | [4b8ee6729a](https://bsd-hardware.info/?probe=4b8ee6729a) | May 02, 2022 |
| Lenovo        | B50-30 20382                | [5701dac149](https://bsd-hardware.info/?probe=5701dac149) | Apr 30, 2022 |
| DEXP          | NAVIS P100                  | [a9c8814bf8](https://bsd-hardware.info/?probe=a9c8814bf8) | Apr 22, 2022 |
| Lenovo        | ThinkPad X121e 3053A52      | [68d0bf2a99](https://bsd-hardware.info/?probe=68d0bf2a99) | Apr 22, 2022 |
| DNS           | W9x0LU                      | [8ac57e3b59](https://bsd-hardware.info/?probe=8ac57e3b59) | Apr 06, 2022 |
| Timi          | TM1612                      | [0389c8d487](https://bsd-hardware.info/?probe=0389c8d487) | Apr 05, 2022 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [c052d7cab0](https://bsd-hardware.info/?probe=c052d7cab0) | Apr 01, 2022 |
| HUAWEI        | CREM-WXX9                   | [e750905413](https://bsd-hardware.info/?probe=e750905413) | Mar 29, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [00213ecee9](https://bsd-hardware.info/?probe=00213ecee9) | Mar 25, 2022 |
| Packard Be... | EasyNote TE69HW             | [851eea349f](https://bsd-hardware.info/?probe=851eea349f) | Mar 17, 2022 |
| Acer          | Aspire 4820T                | [1617262a28](https://bsd-hardware.info/?probe=1617262a28) | Mar 16, 2022 |
| Acer          | Aspire A315-23              | [7fb743c654](https://bsd-hardware.info/?probe=7fb743c654) | Mar 15, 2022 |
| ASUSTek       | M51Sr                       | [936a577d1a](https://bsd-hardware.info/?probe=936a577d1a) | Mar 10, 2022 |
| Lenovo        | E31-80 80MX                 | [098afac660](https://bsd-hardware.info/?probe=098afac660) | Feb 16, 2022 |
| HP            | ProBook 445 G7              | [494195b923](https://bsd-hardware.info/?probe=494195b923) | Feb 08, 2022 |
| Dell          | Venue 11 Pro 7140           | [328f9e8d94](https://bsd-hardware.info/?probe=328f9e8d94) | Feb 04, 2022 |
| HP            | Laptop 15-rb0xx             | [8e9a6cff62](https://bsd-hardware.info/?probe=8e9a6cff62) | Jan 31, 2022 |
| MSI           | GE75 Raider 10SFS           | [48b172bfe8](https://bsd-hardware.info/?probe=48b172bfe8) | Jan 25, 2022 |
| MSI           | GE75 Raider 10SFS           | [306f312c47](https://bsd-hardware.info/?probe=306f312c47) | Jan 25, 2022 |
| HP            | Laptop 15-bw0xx             | [1c8f50f7eb](https://bsd-hardware.info/?probe=1c8f50f7eb) | Jan 24, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | [6836fc60f6](https://bsd-hardware.info/?probe=6836fc60f6) | Jan 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [7aea2ccaa7](https://bsd-hardware.info/?probe=7aea2ccaa7) | Jan 08, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [87c8ee9b4c](https://bsd-hardware.info/?probe=87c8ee9b4c) | Dec 31, 2021 |
| HP            | ProBook 655 G1              | [da312d7c14](https://bsd-hardware.info/?probe=da312d7c14) | Dec 30, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [4bb84a33fa](https://bsd-hardware.info/?probe=4bb84a33fa) | Dec 26, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [ade9f77281](https://bsd-hardware.info/?probe=ade9f77281) | Nov 25, 2021 |
| Acer          | Aspire 3810T                | [86782a69be](https://bsd-hardware.info/?probe=86782a69be) | Nov 13, 2021 |
| Acer          | Aspire 3810T                | [608e43163d](https://bsd-hardware.info/?probe=608e43163d) | Nov 12, 2021 |
| Lenovo        | S20-30 Touch 20434          | [141a393d54](https://bsd-hardware.info/?probe=141a393d54) | Oct 08, 2021 |
| ASUSTek       | UX21A                       | [fe08d28d4c](https://bsd-hardware.info/?probe=fe08d28d4c) | Oct 05, 2021 |
| IBM           | ThinkPad H 1846AQG          | [5e5c7247ca](https://bsd-hardware.info/?probe=5e5c7247ca) | Oct 01, 2021 |
| ASUSTek       | VX7SX                       | [6ca36a455d](https://bsd-hardware.info/?probe=6ca36a455d) | Sep 09, 2021 |
| Kraftway      | KW10T                       | [4810842d82](https://bsd-hardware.info/?probe=4810842d82) | Sep 06, 2021 |
| Lenovo        | ThinkPad E590 20NB0012RT    | [98072b8db6](https://bsd-hardware.info/?probe=98072b8db6) | Jul 26, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [3fb09d0402](https://bsd-hardware.info/?probe=3fb09d0402) | Jul 24, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [bef816fe74](https://bsd-hardware.info/?probe=bef816fe74) | Jul 24, 2021 |
| Acer          | Aspire A715-75G             | [f613cb0452](https://bsd-hardware.info/?probe=f613cb0452) | Jul 23, 2021 |
| Dell          | Inspiron 5758               | [7542ae751d](https://bsd-hardware.info/?probe=7542ae751d) | Jul 20, 2021 |
| eMachines     | eM350                       | [94579b896e](https://bsd-hardware.info/?probe=94579b896e) | Jul 04, 2021 |
| eMachines     | eM350                       | [c268dd82de](https://bsd-hardware.info/?probe=c268dd82de) | Jul 04, 2021 |
| eMachines     | eM350                       | [52198cfd80](https://bsd-hardware.info/?probe=52198cfd80) | Jun 22, 2021 |
| eMachines     | eM350                       | [60b4338ace](https://bsd-hardware.info/?probe=60b4338ace) | Jun 22, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [4ac6c9b3eb](https://bsd-hardware.info/?probe=4ac6c9b3eb) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | [62c87cf194](https://bsd-hardware.info/?probe=62c87cf194) | Jun 07, 2021 |
| Acer          | Aspire ES1-132              | [bf95bf607d](https://bsd-hardware.info/?probe=bf95bf607d) | Jun 06, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [8fc867cfae](https://bsd-hardware.info/?probe=8fc867cfae) | Jun 06, 2021 |
| Lenovo        | ThinkPad T430 23511A6       | [89fb2aa493](https://bsd-hardware.info/?probe=89fb2aa493) | Jun 05, 2021 |
| Acer          | Aspire ES1-132              | [bf605b741b](https://bsd-hardware.info/?probe=bf605b741b) | Jun 04, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [84e93d02e1](https://bsd-hardware.info/?probe=84e93d02e1) | Jun 03, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [1bb850edca](https://bsd-hardware.info/?probe=1bb850edca) | Jun 03, 2021 |
| Acer          | Extensa 2540                | [e7d6ece4ba](https://bsd-hardware.info/?probe=e7d6ece4ba) | Apr 11, 2021 |
| ASUSTek       | 1225B                       | [3eff93bfb5](https://bsd-hardware.info/?probe=3eff93bfb5) | Mar 31, 2021 |
| Samsung       | N145P/N250P/N260P           | [a38a620353](https://bsd-hardware.info/?probe=a38a620353) | Mar 29, 2021 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [342e914968](https://bsd-hardware.info/?probe=342e914968) | Mar 29, 2021 |
| HP            | ProBook 455 G7              | [dd877e6c6c](https://bsd-hardware.info/?probe=dd877e6c6c) | Mar 27, 2021 |
| Samsung       | N145P/N250P/N260P           | [eff02dafe1](https://bsd-hardware.info/?probe=eff02dafe1) | Mar 18, 2021 |
| Lenovo        | ThinkPad T480s 20L7001HR... | [ebd44c21d9](https://bsd-hardware.info/?probe=ebd44c21d9) | Mar 17, 2021 |
| Samsung       | N150P                       | [68483fab9d](https://bsd-hardware.info/?probe=68483fab9d) | Mar 14, 2021 |
| Apple         | MacBookAir6,2               | [52584aaa97](https://bsd-hardware.info/?probe=52584aaa97) | Mar 14, 2021 |
| Apple         | MacBookAir6,2               | [fb136a79e7](https://bsd-hardware.info/?probe=fb136a79e7) | Mar 13, 2021 |
| Dell          | Latitude 3410               | [80d7bf959a](https://bsd-hardware.info/?probe=80d7bf959a) | Mar 10, 2021 |
| HP            | 255 G3                      | [861bdc647d](https://bsd-hardware.info/?probe=861bdc647d) | Mar 09, 2021 |
| HP            | ProBook 455 G7              | [1fcde7c0e1](https://bsd-hardware.info/?probe=1fcde7c0e1) | Mar 09, 2021 |
| HP            | 255 G3                      | [bd82ed65e9](https://bsd-hardware.info/?probe=bd82ed65e9) | Mar 07, 2021 |
| HP            | Compaq 6820s                | [f63d65b78c](https://bsd-hardware.info/?probe=f63d65b78c) | Feb 26, 2021 |
| Dell          | Studio 1537                 | [a4c1d361eb](https://bsd-hardware.info/?probe=a4c1d361eb) | Feb 23, 2021 |
| Apple         | MacBook5,1                  | [41ea02c8bc](https://bsd-hardware.info/?probe=41ea02c8bc) | Feb 21, 2021 |
| Apple         | MacBook5,1                  | [1a374f79df](https://bsd-hardware.info/?probe=1a374f79df) | Feb 19, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [ed75b3d15b](https://bsd-hardware.info/?probe=ed75b3d15b) | Feb 18, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [5e4643fe26](https://bsd-hardware.info/?probe=5e4643fe26) | Feb 18, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [3df4abb2e9](https://bsd-hardware.info/?probe=3df4abb2e9) | Feb 16, 2021 |
| HP            | EliteBook 8460p             | [ada1119026](https://bsd-hardware.info/?probe=ada1119026) | Feb 14, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [0e5e228d18](https://bsd-hardware.info/?probe=0e5e228d18) | Feb 13, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [2d93a6bebc](https://bsd-hardware.info/?probe=2d93a6bebc) | Feb 13, 2021 |
| Sony          | VPCX115KX                   | [fef3d94e6c](https://bsd-hardware.info/?probe=fef3d94e6c) | Feb 12, 2021 |
| Acer          | Extensa 5635Z               | [3b4a7e7fc2](https://bsd-hardware.info/?probe=3b4a7e7fc2) | Feb 10, 2021 |
| Lenovo        | ThinkPad E480 20KN005CRT    | [503378cac9](https://bsd-hardware.info/?probe=503378cac9) | Jan 31, 2021 |
| Sony          | VPCM13M1R                   | [30bb4fc23c](https://bsd-hardware.info/?probe=30bb4fc23c) | Jan 06, 2021 |
| ASUSTek       | X101CH                      | [112792b300](https://bsd-hardware.info/?probe=112792b300) | Jan 02, 2021 |
| ASUSTek       | X101CH                      | [8b571cc947](https://bsd-hardware.info/?probe=8b571cc947) | Jan 02, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [0309e4ac24](https://bsd-hardware.info/?probe=0309e4ac24) | Dec 16, 2020 |
| Acer          | Aspire V5-122               | [ce0c079fd5](https://bsd-hardware.info/?probe=ce0c079fd5) | Dec 14, 2020 |
| Panasonic     | CF-19AHNC8FN                | [04a42812bb](https://bsd-hardware.info/?probe=04a42812bb) | Dec 11, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | [3a78e7dc1a](https://bsd-hardware.info/?probe=3a78e7dc1a) | Dec 11, 2020 |
| Samsung       | N145P/N250P/N260P           | [b4cb55c681](https://bsd-hardware.info/?probe=b4cb55c681) | Dec 05, 2020 |
| Sony          | SVP1321V9RB                 | [9cddee6a0a](https://bsd-hardware.info/?probe=9cddee6a0a) | Dec 01, 2020 |
| Sony          | SVP1321V9RB                 | [d4250ef269](https://bsd-hardware.info/?probe=d4250ef269) | Dec 01, 2020 |
| Sony          | VGN-S150(UC)                | [f2f3923ea6](https://bsd-hardware.info/?probe=f2f3923ea6) | Nov 10, 2020 |
| Toshiba       | Satellite M100              | [e6e0a1294c](https://bsd-hardware.info/?probe=e6e0a1294c) | Nov 01, 2020 |
| Sony          | SVP1321V9RB                 | [3f414895be](https://bsd-hardware.info/?probe=3f414895be) | Oct 24, 2020 |
| Acer          | Aspire ES1-132              | [a4e45f3551](https://bsd-hardware.info/?probe=a4e45f3551) | Oct 22, 2020 |
| Dell          | Latitude C400               | [1dcc5e7972](https://bsd-hardware.info/?probe=1dcc5e7972) | Oct 21, 2020 |
| Dell          | Latitude C400               | [8330d23bd7](https://bsd-hardware.info/?probe=8330d23bd7) | Oct 21, 2020 |
| Google        | Chell                       | [4ffe68c199](https://bsd-hardware.info/?probe=4ffe68c199) | Oct 21, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | [b2e65dd4c5](https://bsd-hardware.info/?probe=b2e65dd4c5) | Oct 20, 2020 |
| Lenovo        | ThinkPad X240 20AL00DKRT    | [623801416c](https://bsd-hardware.info/?probe=623801416c) | Oct 20, 2020 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [a3bc7a0c88](https://bsd-hardware.info/?probe=a3bc7a0c88) | Oct 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [4f54c8f399](https://bsd-hardware.info/?probe=4f54c8f399) | Oct 19, 2020 |
| HP            | OmniBook PC                 | [0e0656d228](https://bsd-hardware.info/?probe=0e0656d228) | Oct 19, 2020 |
| HP            | OmniBook PC                 | [60e72f1c10](https://bsd-hardware.info/?probe=60e72f1c10) | Oct 19, 2020 |
| Acer          | Aspire A315-42              | [1ac21e1660](https://bsd-hardware.info/?probe=1ac21e1660) | Oct 08, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | [1f28f1c311](https://bsd-hardware.info/?probe=1f28f1c311) | Aug 30, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | [11a0bbb73f](https://bsd-hardware.info/?probe=11a0bbb73f) | Aug 30, 2020 |
| Dell          | Inspiron 15-3567            | [4d1897ed1f](https://bsd-hardware.info/?probe=4d1897ed1f) | Aug 29, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [0e99e72ec9](https://bsd-hardware.info/?probe=0e99e72ec9) | Aug 26, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [b9477154b9](https://bsd-hardware.info/?probe=b9477154b9) | Aug 26, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [19d1c3d086](https://bsd-hardware.info/?probe=19d1c3d086) | Aug 20, 2020 |
| ASUSTek       | X71SL                       | [a2ee0c9edb](https://bsd-hardware.info/?probe=a2ee0c9edb) | Aug 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [bc97c1c0fa](https://bsd-hardware.info/?probe=bc97c1c0fa) | Aug 13, 2020 |
| Dell          | Inspiron 1501               | [9ee3e7cbc2](https://bsd-hardware.info/?probe=9ee3e7cbc2) | Aug 11, 2020 |
| Dell          | Inspiron 1501               | [807aae7095](https://bsd-hardware.info/?probe=807aae7095) | Aug 11, 2020 |
| Dell          | Inspiron 1525               | [d08ea3542e](https://bsd-hardware.info/?probe=d08ea3542e) | Aug 05, 2020 |
| Dell          | Latitude 7490               | [b1d5e8c619](https://bsd-hardware.info/?probe=b1d5e8c619) | Aug 05, 2020 |
| HP            | ProBook 440 G6              | [0227811abb](https://bsd-hardware.info/?probe=0227811abb) | Aug 05, 2020 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [0919d8936f](https://bsd-hardware.info/?probe=0919d8936f) | Jul 27, 2020 |
| Lenovo        | G570 20079                  | [15e87049a7](https://bsd-hardware.info/?probe=15e87049a7) | Jul 27, 2020 |
| HP            | ProBook 430 G2              | [3a33aa0d8c](https://bsd-hardware.info/?probe=3a33aa0d8c) | Jun 30, 2020 |
| HP            | ProBook 430 G2              | [365ebdaf9c](https://bsd-hardware.info/?probe=365ebdaf9c) | Jun 30, 2020 |
| Lenovo        | G570 20079                  | [220313b249](https://bsd-hardware.info/?probe=220313b249) | Jun 03, 2020 |
| Lenovo        | G570 20079                  | [7042848932](https://bsd-hardware.info/?probe=7042848932) | Jun 03, 2020 |
| Lenovo        | G570 20079                  | [c7f3bf660a](https://bsd-hardware.info/?probe=c7f3bf660a) | Jun 02, 2020 |
| Lenovo        | G570 20079                  | [b84d1b49d8](https://bsd-hardware.info/?probe=b84d1b49d8) | Jun 02, 2020 |
| Lenovo        | G570 20079                  | [0cc3c53651](https://bsd-hardware.info/?probe=0cc3c53651) | Jun 02, 2020 |
| Dell          | Latitude E5400              | [54854343e4](https://bsd-hardware.info/?probe=54854343e4) | Jun 01, 2020 |
| Dell          | Latitude E6420              | [324265fe3f](https://bsd-hardware.info/?probe=324265fe3f) | May 31, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [68840c222b](https://bsd-hardware.info/?probe=68840c222b) | May 28, 2020 |
| Lenovo        | ThinkPad X240 20AMA52RUK    | [c65cdb97de](https://bsd-hardware.info/?probe=c65cdb97de) | May 28, 2020 |
| Acer          | Aspire 4820T                | [239eea83c6](https://bsd-hardware.info/?probe=239eea83c6) | May 26, 2020 |
| ASUSTek       | GL553VE                     | [dc7bb56859](https://bsd-hardware.info/?probe=dc7bb56859) | May 26, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [9728d93191](https://bsd-hardware.info/?probe=9728d93191) | May 25, 2020 |
| IBM           | ThinkPad X41 2525FAG        | [1e849f86cf](https://bsd-hardware.info/?probe=1e849f86cf) | May 25, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [709a3db7de](https://bsd-hardware.info/?probe=709a3db7de) | May 25, 2020 |
| Lenovo        | G570 20079                  | [0b7b4083bd](https://bsd-hardware.info/?probe=0b7b4083bd) | May 22, 2020 |
| Lenovo        | G570 20079                  | [f7cb1aa38d](https://bsd-hardware.info/?probe=f7cb1aa38d) | May 21, 2020 |
| Dell          | Latitude E6530              | [04cd35a77b](https://bsd-hardware.info/?probe=04cd35a77b) | May 21, 2020 |
| Lenovo        | G570 20079                  | [dc3c3cff26](https://bsd-hardware.info/?probe=dc3c3cff26) | May 21, 2020 |
| Lenovo        | G570 20079                  | [807f3398e3](https://bsd-hardware.info/?probe=807f3398e3) | May 20, 2020 |
| Lenovo        | G570 20079                  | [8212868b9f](https://bsd-hardware.info/?probe=8212868b9f) | May 19, 2020 |
| Lenovo        | G570 20079                  | [ab53dfc003](https://bsd-hardware.info/?probe=ab53dfc003) | May 19, 2020 |
| Lenovo        | G570 20079                  | [d3f180e9ef](https://bsd-hardware.info/?probe=d3f180e9ef) | May 17, 2020 |
| Lenovo        | G570 20079                  | [bdd93164cf](https://bsd-hardware.info/?probe=bdd93164cf) | May 17, 2020 |
| Lenovo        | G570 20079                  | [6a1b7867f0](https://bsd-hardware.info/?probe=6a1b7867f0) | May 16, 2020 |
| Lenovo        | G570 20079                  | [112b83a485](https://bsd-hardware.info/?probe=112b83a485) | May 16, 2020 |
| Lenovo        | G570 20079                  | [3258f01592](https://bsd-hardware.info/?probe=3258f01592) | May 16, 2020 |
| Lenovo        | G570 20079                  | [4a419328b8](https://bsd-hardware.info/?probe=4a419328b8) | May 16, 2020 |
| ASUSTek       | A3L                         | [6b65fcf9c1](https://bsd-hardware.info/?probe=6b65fcf9c1) | May 15, 2020 |
| ASUSTek       | A3L                         | [0d292bca2f](https://bsd-hardware.info/?probe=0d292bca2f) | May 15, 2020 |
| ASUSTek       | X71SL                       | [2fd46cb7c7](https://bsd-hardware.info/?probe=2fd46cb7c7) | May 15, 2020 |
| ASUSTek       | X71SL                       | [8a027d0a73](https://bsd-hardware.info/?probe=8a027d0a73) | May 14, 2020 |
| Dell          | Latitude E6530              | [2c5eec6613](https://bsd-hardware.info/?probe=2c5eec6613) | May 09, 2020 |
| Dell          | Latitude E6530              | [1542f8e5a8](https://bsd-hardware.info/?probe=1542f8e5a8) | May 09, 2020 |
| ASUSTek       | X71SL                       | [adf290251e](https://bsd-hardware.info/?probe=adf290251e) | May 09, 2020 |
| ASUSTek       | X71SL                       | [7b4d0958ec](https://bsd-hardware.info/?probe=7b4d0958ec) | May 09, 2020 |
| Sony          | SVE1713S1RW                 | [9a751ddfd8](https://bsd-hardware.info/?probe=9a751ddfd8) | May 08, 2020 |
| Lenovo        | G570 20079                  | [25fd1154c0](https://bsd-hardware.info/?probe=25fd1154c0) | May 08, 2020 |
| ASUSTek       | X71SL                       | [ab5297a63d](https://bsd-hardware.info/?probe=ab5297a63d) | May 07, 2020 |
| ASUSTek       | X71SL                       | [b8e364a2c0](https://bsd-hardware.info/?probe=b8e364a2c0) | May 07, 2020 |
| ASUSTek       | X71SL                       | [2aac4c3564](https://bsd-hardware.info/?probe=2aac4c3564) | May 07, 2020 |
| Lenovo        | G570 20079                  | [4909d93faf](https://bsd-hardware.info/?probe=4909d93faf) | May 06, 2020 |
| Lenovo        | G570 20079                  | [fb9c475d48](https://bsd-hardware.info/?probe=fb9c475d48) | May 06, 2020 |
| Lenovo        | G570 20079                  | [2efd2c4c7a](https://bsd-hardware.info/?probe=2efd2c4c7a) | May 06, 2020 |
| Lenovo        | G570 20079                  | [f1c2bcae9d](https://bsd-hardware.info/?probe=f1c2bcae9d) | May 06, 2020 |
| ASUSTek       | A3L                         | [0c73038abc](https://bsd-hardware.info/?probe=0c73038abc) | May 06, 2020 |
| ASUSTek       | A3L                         | [ff5b6e3024](https://bsd-hardware.info/?probe=ff5b6e3024) | May 06, 2020 |
| Lenovo        | G570 20079                  | [eff0d8a3db](https://bsd-hardware.info/?probe=eff0d8a3db) | May 06, 2020 |
| ASUSTek       | X71SL                       | [b48cb0f2ce](https://bsd-hardware.info/?probe=b48cb0f2ce) | May 05, 2020 |
| Lenovo        | G570 20079                  | [cd45078232](https://bsd-hardware.info/?probe=cd45078232) | May 05, 2020 |
| Lenovo        | G570 20079                  | [0370bc0522](https://bsd-hardware.info/?probe=0370bc0522) | May 02, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 11        | 10.09%  |
| OpenBSD 6.8          | 10        | 9.17%   |
| NomadBSD 1.3.2       | 7         | 6.42%   |
| FreeBSD 13.0         | 6         | 5.5%    |
| FreeBSD 14.0-CURRENT | 5         | 4.59%   |
| FreeBSD 13.0-CURRENT | 5         | 4.59%   |
| helloSystem 0.6.0    | 4         | 3.67%   |
| FreeBSD 12.1-STABLE  | 4         | 3.67%   |
| OpenBSD 7.1          | 3         | 2.75%   |
| OpenBSD 6.9          | 3         | 2.75%   |
| NomadBSD 5806f915    | 3         | 2.75%   |
| GhostBSD 20.04.02    | 3         | 2.75%   |
| FreeBSD 12.2-p4      | 3         | 2.75%   |
| OpenBSD 6.7          | 2         | 1.83%   |
| FreeBSD 13.0-p3      | 2         | 1.83%   |
| FreeBSD 12.2-STABLE  | 2         | 1.83%   |
| FreeBSD 12.2-p3      | 2         | 1.83%   |
| FreeBSD 12.1-p8      | 2         | 1.83%   |
| FreeBSD 12.1-p7      | 2         | 1.83%   |
| FreeBSD 12.1-p5      | 2         | 1.83%   |
| OS108 9.0            | 1         | 0.92%   |
| OpenBSD 7.0          | 1         | 0.92%   |
| NomadBSD 1.4         | 1         | 0.92%   |
| NomadBSD 1.3.1       | 1         | 0.92%   |
| NetBSD 9.1           | 1         | 0.92%   |
| NetBSD 7.2           | 1         | 0.92%   |
| LibertyBSD 6.1       | 1         | 0.92%   |
| helloSystem 0.3.0    | 1         | 0.92%   |
| GhostBSD 21.08.27    | 1         | 0.92%   |
| FreeBSD 8.4          | 1         | 0.92%   |
| FreeBSD 13.1-BETA3   | 1         | 0.92%   |
| FreeBSD 13.1         | 1         | 0.92%   |
| FreeBSD 13.0-STABLE  | 1         | 0.92%   |
| FreeBSD 13.0-RC1     | 1         | 0.92%   |
| FreeBSD 13.0-p7      | 1         | 0.92%   |
| FreeBSD 13.0-p4      | 1         | 0.92%   |
| FreeBSD 13.0-p2      | 1         | 0.92%   |
| FreeBSD 13.0-p10     | 1         | 0.92%   |
| FreeBSD 13.0-BETA1   | 1         | 0.92%   |
| FreeBSD 12.3-STABLE  | 1         | 0.92%   |
| FreeBSD 12.2-p6      | 1         | 0.92%   |
| FreeBSD 12.2-p2      | 1         | 0.92%   |
| FreeBSD 12.2         | 1         | 0.92%   |
| FreeBSD 12.1-p6      | 1         | 0.92%   |
| FreeBSD 12.1-p3      | 1         | 0.92%   |
| FreeBSD 12.1         | 1         | 0.92%   |
| FreeBSD 11.4-p8      | 1         | 0.92%   |
| FreeBSD 11.4-p5      | 1         | 0.92%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 49        | 48.04%  |
| OpenBSD     | 18        | 17.65%  |
| helloSystem | 16        | 15.69%  |
| NomadBSD    | 11        | 10.78%  |
| GhostBSD    | 4         | 3.92%   |
| NetBSD      | 2         | 1.96%   |
| OS108       | 1         | 0.98%   |
| LibertyBSD  | 1         | 0.98%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 85        | 87.63%  |
| i386  | 12        | 12.37%  |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| helloDesktop  | 20        | 19.61%  |
| Console       | 13        | 12.75%  |
| Openbox       | 12        | 11.76%  |
| fvwm          | 12        | 11.76%  |
| XFCE          | 10        | 9.8%    |
| KDE5          | 9         | 8.82%   |
| TWM           | 5         | 4.9%    |
| MATE          | 5         | 4.9%    |
| GNOME         | 3         | 2.94%   |
| LXDE          | 2         | 1.96%   |
| IceWM         | 2         | 1.96%   |
| i3            | 2         | 1.96%   |
| AwesomeWM     | 2         | 1.96%   |
| StumpWM       | 1         | 0.98%   |
| LXQt          | 1         | 0.98%   |
| Lumina        | 1         | 0.98%   |
| Enlightenment | 1         | 0.98%   |
| dwm           | 1         | 0.98%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 85        | 83.33%  |
| Console | 15        | 14.71%  |
| Wayland | 2         | 1.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 42        | 41.58%  |
| SLiM    | 36        | 35.64%  |
| LightDM | 7         | 6.93%   |
| XDM     | 6         | 5.94%   |
| SDDM    | 6         | 5.94%   |
| GDM     | 2         | 1.98%   |
| PCDM    | 1         | 0.99%   |
| Ly      | 1         | 0.99%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| ru_RU   | 33        | 32.35%  |
| en_US   | 27        | 26.47%  |
| Unknown | 27        | 26.47%  |
| C       | 13        | 12.75%  |
| en_GB   | 1         | 0.98%   |
| en_EN   | 1         | 0.98%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 62        | 62%     |
| BIOS | 38        | 38%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Ufs    | 38        | 37.62%  |
| Zfs    | 37        | 36.63%  |
| Ffs    | 19        | 18.81%  |
| Cd9660 | 6         | 5.94%   |
| Xfs    | 1         | 0.99%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 71        | 71.72%  |
| MBR     | 25        | 25.25%  |
| Unknown | 2         | 2.02%   |
| BSD     | 1         | 1.01%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 29        | 29.9%   |
| Dell                | 14        | 14.43%  |
| Hewlett-Packard     | 12        | 12.37%  |
| Acer                | 10        | 10.31%  |
| ASUSTek Computer    | 9         | 9.28%   |
| Sony                | 5         | 5.15%   |
| Samsung Electronics | 3         | 3.09%   |
| IBM                 | 2         | 2.06%   |
| Apple               | 2         | 2.06%   |
| Toshiba             | 1         | 1.03%   |
| Timi                | 1         | 1.03%   |
| Panasonic           | 1         | 1.03%   |
| Packard Bell        | 1         | 1.03%   |
| MSI                 | 1         | 1.03%   |
| Kraftway            | 1         | 1.03%   |
| HUAWEI              | 1         | 1.03%   |
| Google              | 1         | 1.03%   |
| eMachines           | 1         | 1.03%   |
| DNS                 | 1         | 1.03%   |
| DEXP                | 1         | 1.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Samsung N145P/N250P/N260P                | 2         | 2.06%   |
| Lenovo IdeaPad 330-15ARR 81D2            | 2         | 2.06%   |
| Dell Inspiron 15 7000 Gaming             | 2         | 2.06%   |
| Acer Aspire 4820T                        | 2         | 2.06%   |
| Toshiba Satellite M100                   | 1         | 1.03%   |
| Timi TM1612                              | 1         | 1.03%   |
| Sony VPCX115KX                           | 1         | 1.03%   |
| Sony VPCM13M1R                           | 1         | 1.03%   |
| Sony VGN-S150(UC)                        | 1         | 1.03%   |
| Sony SVP1321V9RB                         | 1         | 1.03%   |
| Sony SVE1713S1RW                         | 1         | 1.03%   |
| Samsung N150P                            | 1         | 1.03%   |
| Panasonic CF-19AHNC8FN                   | 1         | 1.03%   |
| Packard Bell EasyNote TE69HW             | 1         | 1.03%   |
| MSI GE75 Raider 10SFS                    | 1         | 1.03%   |
| Lenovo ThinkPad X240 20AMA52RUK          | 1         | 1.03%   |
| Lenovo ThinkPad X240 20AL00DKRT          | 1         | 1.03%   |
| Lenovo ThinkPad X230 2325Y36             | 1         | 1.03%   |
| Lenovo ThinkPad X13 Gen 1 20UF000QRT     | 1         | 1.03%   |
| Lenovo ThinkPad X13 Gen 1 20T2003PRT     | 1         | 1.03%   |
| Lenovo ThinkPad X121e 3053A52            | 1         | 1.03%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRS04C00 | 1         | 1.03%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS1DW00 | 1         | 1.03%   |
| Lenovo ThinkPad T495s 20QKS1812F         | 1         | 1.03%   |
| Lenovo ThinkPad T490s 20NX000DRT         | 1         | 1.03%   |
| Lenovo ThinkPad T480s 20L7001HRT         | 1         | 1.03%   |
| Lenovo ThinkPad T430 23511A6             | 1         | 1.03%   |
| Lenovo ThinkPad P15 Gen 1 20ST005VRT     | 1         | 1.03%   |
| Lenovo ThinkPad E590 20NB0012RT          | 1         | 1.03%   |
| Lenovo ThinkPad E480 20KN005CRT          | 1         | 1.03%   |
| Lenovo ThinkPad E14 Gen 2 20T6003BRT     | 1         | 1.03%   |
| Lenovo ThinkBook 14 G2 ARE 20VF          | 1         | 1.03%   |
| Lenovo S20-30 Touch 20434                | 1         | 1.03%   |
| Lenovo IdeaPad Z570 HuronRiver Platform  | 1         | 1.03%   |
| Lenovo IdeaPad L340-15API 81LW           | 1         | 1.03%   |
| Lenovo IdeaPad 330-15IGM 81D1            | 1         | 1.03%   |
| Lenovo IdeaPad 320-15ISK 80XH            | 1         | 1.03%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 1.03%   |
| Lenovo IdeaPad 100S-14IBR 80R9           | 1         | 1.03%   |
| Lenovo G570 20079                        | 1         | 1.03%   |
| Lenovo E31-80 80MX                       | 1         | 1.03%   |
| Lenovo B50-30 20382                      | 1         | 1.03%   |
| Kraftway KW10T                           | 1         | 1.03%   |
| IBM ThinkPad X41 2525FAG                 | 1         | 1.03%   |
| IBM ThinkPad H 1846AQG                   | 1         | 1.03%   |
| HUAWEI CREM-WXX9                         | 1         | 1.03%   |
| HP ProBook 655 G1                        | 1         | 1.03%   |
| HP ProBook 455 G7                        | 1         | 1.03%   |
| HP ProBook 445 G7                        | 1         | 1.03%   |
| HP ProBook 440 G6                        | 1         | 1.03%   |
| HP ProBook 430 G2                        | 1         | 1.03%   |
| HP Pavilion g6                           | 1         | 1.03%   |
| HP OmniBook PC                           | 1         | 1.03%   |
| HP Laptop 15-rb0xx                       | 1         | 1.03%   |
| HP Laptop 15-bw0xx                       | 1         | 1.03%   |
| HP EliteBook 8460p                       | 1         | 1.03%   |
| HP Compaq 6820s                          | 1         | 1.03%   |
| HP 255 G3                                | 1         | 1.03%   |
| Google Chell                             | 1         | 1.03%   |
| eMachines eM350                          | 1         | 1.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 16        | 16.49%  |
| Lenovo IdeaPad         | 8         | 8.25%   |
| Acer Aspire            | 8         | 8.25%   |
| Dell Latitude          | 6         | 6.19%   |
| Dell Inspiron          | 6         | 6.19%   |
| HP ProBook             | 5         | 5.15%   |
| Samsung N145P          | 2         | 2.06%   |
| IBM ThinkPad           | 2         | 2.06%   |
| HP Laptop              | 2         | 2.06%   |
| Acer Extensa           | 2         | 2.06%   |
| Toshiba Satellite      | 1         | 1.03%   |
| Timi TM1612            | 1         | 1.03%   |
| Sony VPCX115KX         | 1         | 1.03%   |
| Sony VPCM13M1R         | 1         | 1.03%   |
| Sony VGN-S150(UC)      | 1         | 1.03%   |
| Sony SVP1321V9RB       | 1         | 1.03%   |
| Sony SVE1713S1RW       | 1         | 1.03%   |
| Samsung N150P          | 1         | 1.03%   |
| Panasonic CF-19AHNC8FN | 1         | 1.03%   |
| Packard Bell EasyNote  | 1         | 1.03%   |
| MSI GE75               | 1         | 1.03%   |
| Lenovo ThinkBook       | 1         | 1.03%   |
| Lenovo S20-30          | 1         | 1.03%   |
| Lenovo G570            | 1         | 1.03%   |
| Lenovo E31-80          | 1         | 1.03%   |
| Lenovo B50-30          | 1         | 1.03%   |
| Kraftway KW10T         | 1         | 1.03%   |
| HUAWEI CREM-WXX9       | 1         | 1.03%   |
| HP Pavilion            | 1         | 1.03%   |
| HP OmniBook            | 1         | 1.03%   |
| HP EliteBook           | 1         | 1.03%   |
| HP Compaq              | 1         | 1.03%   |
| HP 255                 | 1         | 1.03%   |
| Google Chell           | 1         | 1.03%   |
| eMachines eM350        | 1         | 1.03%   |
| DNS W9x0LU             | 1         | 1.03%   |
| DEXP NAVIS             | 1         | 1.03%   |
| Dell Venue             | 1         | 1.03%   |
| Dell Studio            | 1         | 1.03%   |
| ASUS X71SL             | 1         | 1.03%   |
| ASUS X101CH            | 1         | 1.03%   |
| ASUS VX7SX             | 1         | 1.03%   |
| ASUS VivoBook          | 1         | 1.03%   |
| ASUS UX21A             | 1         | 1.03%   |
| ASUS M51Sr             | 1         | 1.03%   |
| ASUS GL553VE           | 1         | 1.03%   |
| ASUS A3L               | 1         | 1.03%   |
| ASUS 1225B             | 1         | 1.03%   |
| Apple MacBookAir6      | 1         | 1.03%   |
| Apple MacBook5         | 1         | 1.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 14        | 14.43%  |
| 2020 | 12        | 12.37%  |
| 2011 | 11        | 11.34%  |
| 2018 | 9         | 9.28%   |
| 2012 | 6         | 6.19%   |
| 2017 | 5         | 5.15%   |
| 2015 | 5         | 5.15%   |
| 2009 | 5         | 5.15%   |
| 2016 | 4         | 4.12%   |
| 2014 | 4         | 4.12%   |
| 2013 | 4         | 4.12%   |
| 2008 | 4         | 4.12%   |
| 2021 | 3         | 3.09%   |
| 2010 | 3         | 3.09%   |
| 2006 | 2         | 2.06%   |
| 2005 | 2         | 2.06%   |
| 2004 | 2         | 2.06%   |
| 2007 | 1         | 1.03%   |
| 2003 | 1         | 1.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 97        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 96        | 98.97%  |
| Yes  | 1         | 1.03%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 30        | 30.61%  |
| 8.01-16.0   | 28        | 28.57%  |
| 16.01-24.0  | 16        | 16.33%  |
| 2.01-3.0    | 9         | 9.18%   |
| 1.01-2.0    | 4         | 4.08%   |
| 0.51-1.0    | 3         | 3.06%   |
| 0.01-0.5    | 3         | 3.06%   |
| 24.01-32.0  | 2         | 2.04%   |
| 32.01-64.0  | 1         | 1.02%   |
| 3.01-4.0    | 1         | 1.02%   |
| 64.01-256.0 | 1         | 1.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 58        | 56.86%  |
| 0.51-1.0   | 24        | 23.53%  |
| 2.01-3.0   | 5         | 4.9%    |
| 1.01-2.0   | 4         | 3.92%   |
| 0          | 4         | 3.92%   |
| Unknown    | 4         | 3.92%   |
| 4.01-8.0   | 1         | 0.98%   |
| 24.01-32.0 | 1         | 0.98%   |
| 8.01-16.0  | 1         | 0.98%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 67        | 66.34%  |
| 2      | 26        | 25.74%  |
| 4      | 3         | 2.97%   |
| 0      | 3         | 2.97%   |
| 3      | 2         | 1.98%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 79        | 81.44%  |
| Yes       | 18        | 18.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 87.63%  |
| No        | 12        | 12.37%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 94        | 96.91%  |
| No        | 3         | 3.09%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 62.89%  |
| No        | 36        | 37.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Russia  | 97        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 32        | 32.65%  |
| St Petersburg    | 12        | 12.24%  |
| Vladivostok      | 5         | 5.1%    |
| Yekaterinburg    | 4         | 4.08%   |
| Novosibirsk      | 4         | 4.08%   |
| Ulyanovsk        | 3         | 3.06%   |
| Krasnoyarsk      | 3         | 3.06%   |
| Tyumen           | 2         | 2.04%   |
| Tolyatti         | 2         | 2.04%   |
| Kirov            | 2         | 2.04%   |
| Zhukovskiy       | 1         | 1.02%   |
| Yoshkar-Ola      | 1         | 1.02%   |
| Yegorlykskaya    | 1         | 1.02%   |
| Yaroslavl        | 1         | 1.02%   |
| Vorkuta          | 1         | 1.02%   |
| Vladimir         | 1         | 1.02%   |
| Ust'-Luga        | 1         | 1.02%   |
| Ufa              | 1         | 1.02%   |
| Tsarskoye Selo   | 1         | 1.02%   |
| Surgut           | 1         | 1.02%   |
| Sevastopol'      | 1         | 1.02%   |
| Rostov-on-Don    | 1         | 1.02%   |
| Pushkino         | 1         | 1.02%   |
| Penza            | 1         | 1.02%   |
| Oryol            | 1         | 1.02%   |
| Obninsk          | 1         | 1.02%   |
| Nizhniy Novgorod | 1         | 1.02%   |
| Michurinsk       | 1         | 1.02%   |
| Kstovo           | 1         | 1.02%   |
| Krasnokamsk      | 1         | 1.02%   |
| Korolyov         | 1         | 1.02%   |
| Kislovodsk       | 1         | 1.02%   |
| Khabarovsk       | 1         | 1.02%   |
| Kez              | 1         | 1.02%   |
| Kaliningrad      | 1         | 1.02%   |
| Izhevsk          | 1         | 1.02%   |
| Dolgoprudnyy     | 1         | 1.02%   |
| Chelyabinsk      | 1         | 1.02%   |
| Chebarkul'       | 1         | 1.02%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 24        | 29     | 20%     |
| Seagate             | 12        | 15     | 10%     |
| Samsung Electronics | 11        | 14     | 9.17%   |
| Toshiba             | 9         | 9      | 7.5%    |
| SanDisk             | 9         | 11     | 7.5%    |
| Hitachi             | 8         | 10     | 6.67%   |
| SK Hynix            | 7         | 8      | 5.83%   |
| Intel               | 5         | 7      | 4.17%   |
| HGST                | 5         | 6      | 4.17%   |
| SPCC                | 4         | 5      | 3.33%   |
| Kingston            | 4         | 5      | 3.33%   |
| Micron Technology   | 3         | 3      | 2.5%    |
| Transcend           | 2         | 2      | 1.67%   |
| NVMe                | 2         | 2      | 1.67%   |
| Innostor            | 2         | 2      | 1.67%   |
| Gigabyte Technology | 2         | 5      | 1.67%   |
| USB                 | 1         | 1      | 0.83%   |
| UFD 2.0             | 1         | 1      | 0.83%   |
| OCZ                 | 1         | 2      | 0.83%   |
| Netac               | 1         | 1      | 0.83%   |
| KLLISRE             | 1         | 1      | 0.83%   |
| Hewlett-Packard     | 1         | 1      | 0.83%   |
| FORESEE             | 1         | 1      | 0.83%   |
| Apple               | 1         | 1      | 0.83%   |
| Apacer              | 1         | 1      | 0.83%   |
| AMD                 | 1         | 1      | 0.83%   |
| A-DATA Technology   | 1         | 1      | 0.83%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                  | 3         | 2.36%   |
| Kingston SV300S37A120G 120GB              | 3         | 2.36%   |
| HGST HTS721010A9E630 1TB                  | 3         | 2.36%   |
| WDC WDS240G2G0A-00JH30 240GB              | 2         | 1.57%   |
| WDC WD5000LPVX-60V0TT0 500GB              | 2         | 1.57%   |
| WDC WD2500BEVT-22A23T0 250GB              | 2         | 1.57%   |
| Seagate ST9500325AS 500GB                 | 2         | 1.57%   |
| Seagate ST500LT012-1DG142 500GB           | 2         | 1.57%   |
| Seagate ST500LM021-1KJ152 500GB           | 2         | 1.57%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 2         | 1.57%   |
| Micron 1100 SATA 256GB                    | 2         | 1.57%   |
| Innostor SSD 15GB                         | 2         | 1.57%   |
| WDC WDS500G2B0A-00SM50 500GB              | 1         | 0.79%   |
| WDC WDS120G2G0A-00JH30 120GB              | 1         | 0.79%   |
| WDC WDS100T3X0C-00SJG0 1TB                | 1         | 0.79%   |
| WDC WD5000LPLX-60ZNTT1 500GB              | 1         | 0.79%   |
| WDC WD5000LPCX-60VHAT0 500GB              | 1         | 0.79%   |
| WDC WD5000LPCX-24VHAT0 500GB              | 1         | 0.79%   |
| WDC WD5000BPVT-24HXZT3 500GB              | 1         | 0.79%   |
| WDC WD3200BPVT-24JJ5T0 320GB              | 1         | 0.79%   |
| WDC WD20EARX-00PASB0 2TB                  | 1         | 0.79%   |
| WDC WD2000JB-00GVC0 200GB                 | 1         | 0.79%   |
| WDC WD1600BEVT-22ZCT0 160GB               | 1         | 0.79%   |
| WDC WD10SPZX-08Z10 1TB                    | 1         | 0.79%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 0.79%   |
| WDC WD10JPVX-08JC3T5 1TB                  | 1         | 0.79%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB      | 1         | 0.79%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB        | 1         | 0.79%   |
| WDC PC SN730 SDBPNTY-512G                 | 1         | 0.79%   |
| WDC PC SN530 SDBPNPZ-512G-1014 512GB      | 1         | 0.79%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB      | 1         | 0.79%   |
| USB SanDisk 3.2Gen1 64GB                  | 1         | 0.79%   |
| UFD 2.0 Silicon-Power16G 18302PB          | 1         | 0.79%   |
| Transcend TS256GMTS400 256GB              | 1         | 0.79%   |
| Transcend TS240GMTS420S 240GB             | 1         | 0.79%   |
| Toshiba MQ04ABF100 1TB                    | 1         | 0.79%   |
| Toshiba MQ01ABD100 1TB                    | 1         | 0.79%   |
| Toshiba MK7575GSX 752GB                   | 1         | 0.79%   |
| Toshiba MK1637GSX 160GB                   | 1         | 0.79%   |
| Toshiba MK1517GAP 16GB                    | 1         | 0.79%   |
| Toshiba KBG30ZMV512G 512GB                | 1         | 0.79%   |
| SPCC Solid State Disk 64GB                | 1         | 0.79%   |
| SPCC Solid State Disk 240GB               | 1         | 0.79%   |
| SPCC Solid State Disk 128GB               | 1         | 0.79%   |
| SPCC Solid State Disk 120GB               | 1         | 0.79%   |
| SK Hynix SKHynix_HFS512GD9TNG-L5B0B 512GB | 1         | 0.79%   |
| SK Hynix HFS128G32TNF-N3A0A 128GB         | 1         | 0.79%   |
| SK Hynix HFM256GDJTNG-8310A 256GB         | 1         | 0.79%   |
| SK Hynix HFM256GDHTNG-8510B 256GB         | 1         | 0.79%   |
| SK Hynix BC511 NVMe 512GB                 | 1         | 0.79%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB   | 1         | 0.79%   |
| SK Hynix BC501 HFM256GDJTNG-8310A 256GB   | 1         | 0.79%   |
| Seagate ST9250320AS 250GB                 | 1         | 0.79%   |
| Seagate ST500LM030-2E717D 500GB           | 1         | 0.79%   |
| Seagate ST2000LM003 HN-M201RAD 2TB        | 1         | 0.79%   |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 0.79%   |
| Seagate ST1000LM048-2E7172 1TB            | 1         | 0.79%   |
| Seagate ST1000LM035-1RK172 1TB            | 1         | 0.79%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 0.79%   |
| SanDisk X110 M.2 2260 256GB               | 1         | 0.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 15     | 26.92%  |
| Seagate             | 12        | 15     | 23.08%  |
| Toshiba             | 8         | 8      | 15.38%  |
| Hitachi             | 8         | 10     | 15.38%  |
| HGST                | 5         | 6      | 9.62%   |
| NVMe                | 2         | 2      | 3.85%   |
| USB                 | 1         | 1      | 1.92%   |
| UFD 2.0             | 1         | 1      | 1.92%   |
| Samsung Electronics | 1         | 1      | 1.92%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 9         | 11     | 18%     |
| Samsung Electronics | 7         | 8      | 14%     |
| WDC                 | 4         | 5      | 8%      |
| SPCC                | 4         | 5      | 8%      |
| Kingston            | 4         | 5      | 8%      |
| Intel               | 4         | 6      | 8%      |
| Micron Technology   | 3         | 3      | 6%      |
| Transcend           | 2         | 2      | 4%      |
| Innostor            | 2         | 2      | 4%      |
| SK Hynix            | 1         | 1      | 2%      |
| OCZ                 | 1         | 2      | 2%      |
| Netac               | 1         | 1      | 2%      |
| KLLISRE             | 1         | 1      | 2%      |
| Hewlett-Packard     | 1         | 1      | 2%      |
| Gigabyte Technology | 1         | 3      | 2%      |
| FORESEE             | 1         | 1      | 2%      |
| Apple               | 1         | 1      | 2%      |
| Apacer              | 1         | 1      | 2%      |
| AMD                 | 1         | 1      | 2%      |
| A-DATA Technology   | 1         | 1      | 2%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 47        | 59     | 43.12%  |
| SSD  | 44        | 61     | 40.37%  |
| NVMe | 18        | 25     | 16.51%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 80        | 120    | 81.63%  |
| NVMe | 18        | 25     | 18.37%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 70        | 99     | 77.78%  |
| 0.51-1.0        | 17        | 18     | 18.89%  |
| 1.01-2.0        | 2         | 2      | 2.22%   |
| More than 100.0 | 1         | 1      | 1.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 27        | 25.47%  |
| 1-20       | 26        | 24.53%  |
| 251-500    | 21        | 19.81%  |
| 21-50      | 10        | 9.43%   |
| 51-100     | 9         | 8.49%   |
| 501-1000   | 8         | 7.55%   |
| 1001-2000  | 3         | 2.83%   |
| Unknown    | 2         | 1.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 70        | 70.71%  |
| 21-50   | 12        | 12.12%  |
| 101-250 | 9         | 9.09%   |
| 51-100  | 4         | 4.04%   |
| 251-500 | 2         | 2.02%   |
| Unknown | 2         | 2.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB    | 2         | 2      | 7.69%   |
| Micron Technology 1100 SATA 256GB  | 2         | 2      | 7.69%   |
| WDC WD5000LPLX-60ZNTT1 500GB       | 1         | 1      | 3.85%   |
| WDC WD2000JB-00GVC0 200GB          | 1         | 1      | 3.85%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 3.85%   |
| Toshiba MK7575GSX 752GB            | 1         | 1      | 3.85%   |
| Seagate ST9500325AS 500GB          | 1         | 1      | 3.85%   |
| Seagate ST9250320AS 250GB          | 1         | 1      | 3.85%   |
| Seagate ST500LM021-1KJ152 500GB    | 1         | 1      | 3.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 3.85%   |
| Samsung Electronics HM080HI 80GB   | 1         | 1      | 3.85%   |
| Kingston SV300S37A120G 120GB       | 1         | 1      | 3.85%   |
| Intel SSDSC2KW120H6 120GB          | 1         | 1      | 3.85%   |
| Intel SSDSC2CW060A3 64GB           | 1         | 1      | 3.85%   |
| Intel SSDSC2BB480G7 480GB          | 1         | 1      | 3.85%   |
| Hitachi HTS725025A9A364 250GB      | 1         | 1      | 3.85%   |
| Hitachi HTS721060G9AT00 64GB       | 1         | 1      | 3.85%   |
| Hitachi HTS547564A9E384 640GB      | 1         | 1      | 3.85%   |
| Hitachi HTS541612J9SA00 120GB      | 1         | 1      | 3.85%   |
| Hitachi HTC426060G9AT00 64GB       | 1         | 1      | 3.85%   |
| Hitachi DK23AA-12 12GB             | 1         | 1      | 3.85%   |
| HGST HTS541075A7E630 752GB         | 1         | 1      | 3.85%   |
| HGST HTE725032A7E630 320GB         | 1         | 1      | 3.85%   |
| Apple SSD SD0128F 121GB            | 1         | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 23.08%  |
| Hitachi             | 6         | 6      | 23.08%  |
| Intel               | 3         | 3      | 11.54%  |
| WDC                 | 2         | 2      | 7.69%   |
| Toshiba             | 2         | 2      | 7.69%   |
| Micron Technology   | 2         | 2      | 7.69%   |
| HGST                | 2         | 2      | 7.69%   |
| Samsung Electronics | 1         | 1      | 3.85%   |
| Kingston            | 1         | 1      | 3.85%   |
| Apple               | 1         | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 31.58%  |
| Hitachi             | 6         | 6      | 31.58%  |
| WDC                 | 2         | 2      | 10.53%  |
| Toshiba             | 2         | 2      | 10.53%  |
| HGST                | 2         | 2      | 10.53%  |
| Samsung Electronics | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 19     | 73.08%  |
| SSD  | 7         | 7      | 26.92%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Hitachi HTS545025B9A300 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 75        | 114    | 70.75%  |
| Malfunc  | 26        | 26     | 24.53%  |
| Detected | 4         | 4      | 3.77%   |
| Failed   | 1         | 1      | 0.94%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 66        | 61.68%  |
| AMD                              | 18        | 16.82%  |
| SK Hynix                         | 7         | 6.54%   |
| Sandisk                          | 6         | 5.61%   |
| Samsung Electronics              | 4         | 3.74%   |
| Toshiba                          | 1         | 0.93%   |
| Silicon Integrated Systems [SiS] | 1         | 0.93%   |
| Phison Electronics               | 1         | 0.93%   |
| Nvidia                           | 1         | 0.93%   |
| Marvell Technology Group         | 1         | 0.93%   |
| JMicron Technology               | 1         | 0.93%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 15        | 13.39%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8         | 7.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 5.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 5.36%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 5         | 4.46%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 4.46%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 4         | 3.57%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 4         | 3.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 3.57%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 2.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 2.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 2.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 2.68%   |
| SK Hynix BC511                                                                   | 2         | 1.79%   |
| Sandisk PC SN530                                                                 | 2         | 1.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 1.79%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 1.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.79%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 2         | 1.79%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 1.79%   |
| Intel 82801CAM IDE U100 Controller                                               | 2         | 1.79%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.79%   |
| Toshiba BG3 NVMe SSD Controller                                                  | 1         | 0.89%   |
| SK Hynix hynix unknown                                                           | 1         | 0.89%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.89%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.89%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.89%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.89%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.89%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 1         | 0.89%   |
| JMicron JMB360 AHCI Controller                                                   | 1         | 0.89%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 1         | 0.89%   |
| Intel SSD 660P Series                                                            | 1         | 0.89%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 0.89%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 0.89%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.89%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 0.89%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1         | 0.89%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 0.89%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 0.89%   |
| AMD SB600 IDE                                                                    | 1         | 0.89%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 74        | 68.52%  |
| NVMe | 19        | 17.59%  |
| IDE  | 14        | 12.96%  |
| RAID | 1         | 0.93%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 76        | 78.35%  |
| AMD    | 21        | 21.65%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Core i3-6006U CPU @ 2.00GHz                                   | 5         | 5.1%    |
| Intel C1                                                            | 3         | 3.06%   |
| Intel Pentium M processor 1.60GHz                                   | 2         | 2.04%   |
| Intel Core i7-8565U CPU @ 1.80GHz                                   | 2         | 2.04%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz                                  | 2         | 2.04%   |
| Intel Core i5-3320M CPU @ 2.60GHz                                   | 2         | 2.04%   |
| Intel Core i5-2520M CPU @ 2.50GHz                                   | 2         | 2.04%   |
| Intel Core i5-2430M CPU @ 2.40GHz                                   | 2         | 2.04%   |
| Intel Core i3 CPU M 350 @ 2.27GHz                                   | 2         | 2.04%   |
| Intel Core 2 Duo                                                    | 2         | 2.04%   |
| AMD Ryzen 7 4700U with Radeon Graphics                              | 2         | 2.04%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx                       | 2         | 2.04%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx                       | 2         | 2.04%   |
| Intel Xeon W-10885M CPU @ 2.40GHz                                   | 1         | 1.02%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz                            | 1         | 1.02%   |
| Intel Pentium M processor 1.86GHz ("GenuineIntel" 686-class)        | 1         | 1.02%   |
| Intel Pentium M processor                                           | 1         | 1.02%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz                         | 1         | 1.02%   |
| Intel Pentium CPU N4200 @ 1.10GHz                                   | 1         | 1.02%   |
| Intel Pentium CPU N3700 @ 1.60GHz                                   | 1         | 1.02%   |
| Intel Pentium CPU N3530 @ 2.16GHz                                   | 1         | 1.02%   |
| Intel Mobile Pentium III CPU - M 1200MHz ("GenuineIntel" 686-class) | 1         | 1.02%   |
| Intel Mobile Pentium III CPU - M 1000MHz ("GenuineIntel" 686-class) | 1         | 1.02%   |
| Intel Genuine CPU U7300 @ 1.30GHz                                   | 1         | 1.02%   |
| Intel Genuine CPU T2                                                | 1         | 1.02%   |
| Intel CPU Version                                                   | 1         | 1.02%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz                                    | 1         | 1.02%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz                                    | 1         | 1.02%   |
| Intel Core M-5Y71 CPU @ 1.20GHz                                     | 1         | 1.02%   |
| Intel Core i9-10980HK CPU @ 2.40GHz                                 | 1         | 1.02%   |
| Intel Core i7-9750H CPU @ 2.60GHz                                   | 1         | 1.02%   |
| Intel Core i7-8550U CPU @ 1.80GHz                                   | 1         | 1.02%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz                                  | 1         | 1.02%   |
| Intel Core i7-6600U CPU @ 2.60GHz                                   | 1         | 1.02%   |
| Intel Core i7-4600U CPU @ 2.10GHz                                   | 1         | 1.02%   |
| Intel Core i7-3630QM CPU @ 2.40GHz                                  | 1         | 1.02%   |
| Intel Core i7-3517U CPU @ 1.90GHz                                   | 1         | 1.02%   |
| Intel Core i7-2670QM CPU @ 2.20GHz                                  | 1         | 1.02%   |
| Intel Core i7-10510U CPU @ 1.80GHz                                  | 1         | 1.02%   |
| Intel Core i5-8350U CPU @ 1.70GHz                                   | 1         | 1.02%   |
| Intel Core i5-8265U CPU @ 1.60GHz                                   | 1         | 1.02%   |
| Intel Core i5-8250U CPU @ 1.60GHz                                   | 1         | 1.02%   |
| Intel Core i5-7200U CPU @ 2.50GHz                                   | 1         | 1.02%   |
| Intel Core i5-4300U CPU @ 1.90GHz                                   | 1         | 1.02%   |
| Intel Core i5-4250U CPU @ 1.30GHz                                   | 1         | 1.02%   |
| Intel Core i5-4200U CPU @ 1.60GHz                                   | 1         | 1.02%   |
| Intel Core i5-3230M CPU @ 2.60GHz                                   | 1         | 1.02%   |
| Intel Core i5-2520M CPU @ 2.50GH                                    | 1         | 1.02%   |
| Intel Core i5-10310U CPU @ 1.70GHz                                  | 1         | 1.02%   |
| Intel Core i3-5005U CPU @ 2.00GHz                                   | 1         | 1.02%   |
| Intel Core i3-4030U CPU @ 1.90GHz                                   | 1         | 1.02%   |
| Intel Core i3-3120M CPU @ 2.50GHz                                   | 1         | 1.02%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz                                | 1         | 1.02%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz                                | 1         | 1.02%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz                                | 1         | 1.02%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz                                | 1         | 1.02%   |
| Intel Celeron CPU N3350 @ 1.10GHz                                   | 1         | 1.02%   |
| Intel Celeron CPU N3060 @ 1.60GHz                                   | 1         | 1.02%   |
| Intel Celeron CPU N2840 @ 2.16GHz                                   | 1         | 1.02%   |
| Intel Celeron 2957U @ 1.40GHz                                       | 1         | 1.02%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 18        | 18.37%  |
| Intel Core i7           | 11        | 11.22%  |
| Intel Core i3           | 10        | 10.2%   |
| Other                   | 6         | 6.12%   |
| Intel Core 2 Duo        | 6         | 6.12%   |
| Intel Atom              | 5         | 5.1%    |
| AMD Ryzen 3             | 5         | 5.1%    |
| Intel Pentium M         | 4         | 4.08%   |
| Intel Celeron           | 4         | 4.08%   |
| AMD Ryzen 7             | 4         | 4.08%   |
| Intel Pentium           | 3         | 3.06%   |
| AMD E                   | 3         | 3.06%   |
| Intel Genuine           | 2         | 2.04%   |
| AMD Ryzen 7 PRO         | 2         | 2.04%   |
| AMD Ryzen 5             | 2         | 2.04%   |
| AMD A6                  | 2         | 2.04%   |
| Intel Xeon              | 1         | 1.02%   |
| Intel Pentium Silver    | 1         | 1.02%   |
| Intel Pentium Dual-Core | 1         | 1.02%   |
| Intel Core m5           | 1         | 1.02%   |
| Intel Core m3           | 1         | 1.02%   |
| Intel Core M            | 1         | 1.02%   |
| Intel Core i9           | 1         | 1.02%   |
| Intel 686-class         | 1         | 1.02%   |
| AMD E2                  | 1         | 1.02%   |
| AMD E1                  | 1         | 1.02%   |
| AMD A10                 | 1         | 1.02%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 42        | 42.42%  |
| 4       | 24        | 24.24%  |
| Unknown | 13        | 13.13%  |
| 1       | 9         | 9.09%   |
| 8       | 7         | 7.07%   |
| 16      | 2         | 2.02%   |
| 6       | 2         | 2.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 91        | 91.92%  |
| Unknown | 8         | 8.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 46        | 46.46%  |
| 1       | 35        | 35.35%  |
| Unknown | 18        | 18.18%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 13        | 13.27%  |
| Skylake       | 8         | 8.16%   |
| Penryn        | 7         | 7.14%   |
| P6            | 7         | 7.14%   |
| Bonnell       | 7         | 7.14%   |
| SandyBridge   | 6         | 6.12%   |
| IvyBridge     | 6         | 6.12%   |
| Haswell       | 6         | 6.12%   |
| Zen 2         | 5         | 5.1%    |
| Silvermont    | 5         | 5.1%    |
| Zen+          | 4         | 4.08%   |
| Zen           | 3         | 3.06%   |
| Westmere      | 2         | 2.04%   |
| Goldmont      | 2         | 2.04%   |
| Excavator     | 2         | 2.04%   |
| Core          | 2         | 2.04%   |
| CometLake     | 2         | 2.04%   |
| Broadwell     | 2         | 2.04%   |
| Bobcat        | 2         | 2.04%   |
| Zen 3         | 1         | 1.02%   |
| Puma          | 1         | 1.02%   |
| Piledriver    | 1         | 1.02%   |
| K8 Hammer     | 1         | 1.02%   |
| Jaguar        | 1         | 1.02%   |
| Goldmont plus | 1         | 1.02%   |
| Unknown       | 1         | 1.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 65        | 58.04%  |
| AMD    | 33        | 29.46%  |
| Nvidia | 13        | 11.61%  |
| ATI    | 1         | 0.89%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 5.31%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5         | 4.42%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 4.42%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 4.42%   |
| AMD Renoir                                                                               | 5         | 4.42%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 3.54%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 3.54%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 2.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 2.65%   |
| Intel UHD Graphics 620                                                                   | 3         | 2.65%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.65%   |
| Intel HD Graphics 630                                                                    | 3         | 2.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 2.65%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 2.65%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 1.77%   |
| Intel HD Graphics 520                                                                    | 2         | 1.77%   |
| Intel HD Graphics 515                                                                    | 2         | 1.77%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.77%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.77%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.77%   |
| Nvidia TU117M                                                                            | 1         | 0.88%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                    | 1         | 0.88%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                                         | 1         | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.88%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 0.88%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 0.88%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 0.88%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 0.88%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                      | 1         | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.88%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 1         | 0.88%   |
| Intel HD Graphics 620                                                                    | 1         | 0.88%   |
| Intel HD Graphics 5500                                                                   | 1         | 0.88%   |
| Intel HD Graphics 5300                                                                   | 1         | 0.88%   |
| Intel HD Graphics 500                                                                    | 1         | 0.88%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 0.88%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.88%   |
| Intel Comet Lake-H WS GT2 Integrated UHD Graphics Controller                             | 1         | 0.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 1         | 0.88%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 0.88%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 0.88%   |
| Intel 82830M/MG Integrated Graphics Controller                                           | 1         | 0.88%   |
| ATI Robson CE [Radeon HD 6370M/7370M]                                                    | 1         | 0.88%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 1         | 0.88%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 0.88%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 0.88%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 0.88%   |
| AMD Temash [Radeon HD 8250/8280G]                                                        | 1         | 0.88%   |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                                        | 1         | 0.88%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 1         | 0.88%   |
| AMD RV610/M72-S [Mobility Radeon HD 2400]                                                | 1         | 0.88%   |
| AMD RV516/M62-S [Mobility Radeon X1350]                                                  | 1         | 0.88%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 1         | 0.88%   |
| AMD RV370/M22 [Mobility Radeon X300]                                                     | 1         | 0.88%   |
| AMD RV280/M9+ [Mobility Radeon 9200 AGP]                                                 | 1         | 0.88%   |
| AMD RV100/M6 [Rage/Radeon Mobility Series]                                               | 1         | 0.88%   |
| AMD RS482M [Mobility Radeon Xpress 200]                                                  | 1         | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 44        | 44.9%   |
| 1 x AMD        | 29        | 29.59%  |
| 2 x Intel      | 9         | 9.18%   |
| Intel + Nvidia | 9         | 9.18%   |
| 1 x Nvidia     | 3         | 3.06%   |
| Intel + AMD    | 3         | 3.06%   |
| AMD + Nvidia   | 1         | 1.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 89        | 90.82%  |
| Unknown     | 5         | 5.1%    |
| Proprietary | 4         | 4.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 81        | 80.2%   |
| 0.01-0.5   | 13        | 12.87%  |
| 1.01-2.0   | 4         | 3.96%   |
| 0.51-1.0   | 2         | 1.98%   |
| 2.01-3.0   | 1         | 0.99%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 18        | 23.08%  |
| LG Display              | 13        | 16.67%  |
| Samsung Electronics     | 9         | 11.54%  |
| BOE                     | 9         | 11.54%  |
| Chimei Innolux          | 6         | 7.69%   |
| InfoVision              | 4         | 5.13%   |
| PANDA                   | 2         | 2.56%   |
| LG Philips              | 2         | 2.56%   |
| Lenovo                  | 2         | 2.56%   |
| Chi Mei Optoelectronics | 2         | 2.56%   |
| Acer                    | 2         | 2.56%   |
| ViewSonic               | 1         | 1.28%   |
| Toshiba                 | 1         | 1.28%   |
| Panasonic               | 1         | 1.28%   |
| NEC Computers           | 1         | 1.28%   |
| HannStar                | 1         | 1.28%   |
| Goldstar                | 1         | 1.28%   |
| CSO                     | 1         | 1.28%   |
| Apple                   | 1         | 1.28%   |
| Ancor Communications    | 1         | 1.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3030 1024x600 220x130mm 10.1-inch     | 2         | 2.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO1457 1366x768 310x170mm 13.9-inch | 2         | 2.56%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 2         | 2.56%   |
| ViewSonic LCD Monitor VSC6F2E 1920x1080 480x270mm 21.7-inch              | 1         | 1.28%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                          | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SEC5643 1280x800 300x190mm 14.0-inch     | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch     | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 370x230mm 17.2-inch     | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch    | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch    | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 290x160mm 13.0-inch    | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch   | 1         | 1.28%   |
| PANDA LM133LF1L01 NCP13FB 1920x1080 290x170mm 13.2-inch                  | 1         | 1.28%   |
| PANDA LCD Monitor NCP002B 1920x1080 310x170mm 13.9-inch                  | 1         | 1.28%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 1         | 1.28%   |
| NEC Computers LCD1970NX NEC6662 1280x1024 380x300mm 19.1-inch            | 1         | 1.28%   |
| LG Philips LCD Monitor LPLA101 1440x900 370x230mm 17.2-inch              | 1         | 1.28%   |
| LG Philips LCD Monitor LPL0301 1280x800 330x210mm 15.4-inch              | 1         | 1.28%   |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch             | 1         | 1.28%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch             | 1         | 1.28%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 1.28%   |
| LG Display LCD Monitor LGD053F 1920x1080 340x190mm 15.3-inch             | 1         | 1.28%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 1         | 1.28%   |
| LG Display LCD Monitor LGD046B 1366x768 340x190mm 15.3-inch              | 1         | 1.28%   |
| LG Display LCD Monitor LGD0465 1366x768 340x190mm 15.3-inch              | 1         | 1.28%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 1         | 1.28%   |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch              | 1         | 1.28%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 1         | 1.28%   |
| LG Display LCD Monitor LGD034D 1366x768 340x190mm 15.3-inch              | 1         | 1.28%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 1.28%   |
| LG Display LCD Monitor LGD01F7 1366x768 290x160mm 13.0-inch              | 1         | 1.28%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 340x190mm 15.3-inch                 | 1         | 1.28%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch                  | 1         | 1.28%   |
| InfoVision M116NWR1 R0  IVO0489 1366x768 260x140mm 11.6-inch             | 1         | 1.28%   |
| InfoVision LCD Monitor IVO8C5F 1920x1080 310x170mm 13.9-inch             | 1         | 1.28%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch             | 1         | 1.28%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch              | 1         | 1.28%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                | 1         | 1.28%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch               | 1         | 1.28%   |
| CSO LCD Monitor CSO1500 3840x2160 340x190mm 15.3-inch                    | 1         | 1.28%   |
| Chimei Innolux LCD Monitor CMN1731 1600x900 390x220mm 17.6-inch          | 1         | 1.28%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 1         | 1.28%   |
| Chimei Innolux LCD Monitor CMN15D9 1920x1080 340x190mm 15.3-inch         | 1         | 1.28%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch         | 1         | 1.28%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch         | 1         | 1.28%   |
| Chimei Innolux LCD Monitor CMN1124 1920x1080 260x140mm 11.6-inch         | 1         | 1.28%   |
| BOE LCD Monitor BOE0812 1920x1080 340x190mm 15.3-inch                    | 1         | 1.28%   |
| BOE LCD Monitor BOE07A3 1920x1080 340x190mm 15.3-inch                    | 1         | 1.28%   |
| BOE LCD Monitor BOE0742 1920x1080 310x170mm 13.9-inch                    | 1         | 1.28%   |
| BOE LCD Monitor BOE06EE 1920x1080 310x170mm 13.9-inch                    | 1         | 1.28%   |
| BOE LCD Monitor BOE06BA 1920x1080 340x190mm 15.3-inch                    | 1         | 1.28%   |
| BOE LCD Monitor BOE06A5 1366x768 340x190mm 15.3-inch                     | 1         | 1.28%   |
| BOE LCD Monitor BOE0691 1920x1080 280x160mm 12.7-inch                    | 1         | 1.28%   |
| BOE LCD Monitor BOE0671 1366x768 340x190mm 15.3-inch                     | 1         | 1.28%   |
| BOE LCD Monitor BOE0609 1366x768 260x150mm 11.8-inch                     | 1         | 1.28%   |
| AU Optronics LCD Monitor AUOE997 1920x1080 340x190mm 15.3-inch           | 1         | 1.28%   |
| AU Optronics LCD Monitor AUODF87 1920x1080 340x190mm 15.3-inch           | 1         | 1.28%   |
| AU Optronics LCD Monitor AUO8174 1280x800 330x210mm 15.4-inch            | 1         | 1.28%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 1         | 1.28%   |
| AU Optronics LCD Monitor AUO5A2D 1920x1080 290x170mm 13.2-inch           | 1         | 1.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 32        | 41.03%  |
| 1366x768 (WXGA)   | 22        | 28.21%  |
| 1280x800 (WXGA)   | 4         | 5.13%   |
| 1024x600          | 4         | 5.13%   |
| 1440x900 (WXGA+)  | 3         | 3.85%   |
| 3840x2160 (4K)    | 2         | 2.56%   |
| 2560x1440 (QHD)   | 2         | 2.56%   |
| 1600x900 (HD+)    | 2         | 2.56%   |
| 1280x1024 (SXGA)  | 2         | 2.56%   |
| 3200x1800 (QHD+)  | 1         | 1.28%   |
| 2880x1620         | 1         | 1.28%   |
| 2560x1080         | 1         | 1.28%   |
| 1920x540          | 1         | 1.28%   |
| 1920x1200 (WUXGA) | 1         | 1.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 29        | 37.18%  |
| 13     | 21        | 26.92%  |
| 17     | 5         | 6.41%   |
| 11     | 5         | 6.41%   |
| 10     | 5         | 6.41%   |
| 14     | 3         | 3.85%   |
| 12     | 3         | 3.85%   |
| 21     | 2         | 2.56%   |
| 54     | 1         | 1.28%   |
| 34     | 1         | 1.28%   |
| 31     | 1         | 1.28%   |
| 27     | 1         | 1.28%   |
| 19     | 1         | 1.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 44        | 56.41%  |
| 201-300     | 23        | 29.49%  |
| 351-400     | 5         | 6.41%   |
| 401-500     | 2         | 2.56%   |
| 701-800     | 1         | 1.28%   |
| 601-700     | 1         | 1.28%   |
| 501-600     | 1         | 1.28%   |
| 1001-1500   | 1         | 1.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 61        | 83.56%  |
| 16/10 | 9         | 12.33%  |
| 5/4   | 2         | 2.74%   |
| 21/9  | 1         | 1.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 25        | 32.05%  |
| 81-90          | 18        | 23.08%  |
| 71-80          | 6         | 7.69%   |
| 51-60          | 5         | 6.41%   |
| 41-50          | 5         | 6.41%   |
| 101-110        | 4         | 5.13%   |
| 61-70          | 3         | 3.85%   |
| 131-140        | 3         | 3.85%   |
| 351-500        | 2         | 2.56%   |
| 201-250        | 2         | 2.56%   |
| More than 1000 | 1         | 1.28%   |
| 301-350        | 1         | 1.28%   |
| 151-200        | 1         | 1.28%   |
| 141-150        | 1         | 1.28%   |
| 121-130        | 1         | 1.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 33        | 42.31%  |
| 101-120       | 24        | 30.77%  |
| 51-100        | 10        | 12.82%  |
| 161-240       | 9         | 11.54%  |
| More than 240 | 2         | 2.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 73        | 70.87%  |
| 0     | 22        | 21.36%  |
| 2     | 8         | 7.77%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 51        | 30%     |
| Realtek Semiconductor             | 45        | 26.47%  |
| Qualcomm Atheros                  | 31        | 18.24%  |
| Broadcom                          | 12        | 7.06%   |
| Marvell Technology Group          | 5         | 2.94%   |
| TP-Link                           | 4         | 2.35%   |
| Ralink Technology                 | 3         | 1.76%   |
| Ralink                            | 2         | 1.18%   |
| Fibocom                           | 2         | 1.18%   |
| Ericsson Business Mobile Networks | 2         | 1.18%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.59%   |
| Realtek                           | 1         | 0.59%   |
| Nvidia                            | 1         | 0.59%   |
| Mercucys                          | 1         | 0.59%   |
| JMicron Technology                | 1         | 0.59%   |
| Huawei Technologies               | 1         | 0.59%   |
| Dell                              | 1         | 0.59%   |
| D-Link                            | 1         | 0.59%   |
| BUFFALO                           | 1         | 0.59%   |
| Attansic                          | 1         | 0.59%   |
| Atheros                           | 1         | 0.59%   |
| Arduino SA                        | 1         | 0.59%   |
| 3Com                              | 1         | 0.59%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 32        | 15.17%  |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 10        | 4.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 8         | 3.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 6         | 2.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 2.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 5         | 2.37%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 2.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 4         | 1.9%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 4         | 1.9%    |
| Intel Wireless 7265                                                           | 4         | 1.9%    |
| Intel Wi-Fi 6 AX200                                                           | 4         | 1.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 3         | 1.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 1.42%   |
| Intel Wireless 3165                                                           | 3         | 1.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3         | 1.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 3         | 1.42%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 2         | 0.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.95%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 2         | 0.95%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                         | 2         | 0.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 0.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 2         | 0.95%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 2         | 0.95%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 2         | 0.95%   |
| Intel Wireless-AC 9260                                                        | 2         | 0.95%   |
| Intel Wireless 8260                                                           | 2         | 0.95%   |
| Intel Wireless 7260                                                           | 2         | 0.95%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 0.95%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 2         | 0.95%   |
| Intel Ethernet Connection I218-LM                                             | 2         | 0.95%   |
| Intel Ethernet Connection (4) I219-V                                          | 2         | 0.95%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 2         | 0.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 2         | 0.95%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2         | 0.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 2         | 0.95%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                             | 2         | 0.95%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III   | 2         | 0.95%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                      | 2         | 0.95%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1         | 0.47%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]           | 1         | 0.47%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 1         | 0.47%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                               | 1         | 0.47%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1         | 0.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1         | 0.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.47%   |
| Ralink RT3572 Wireless Adapter                                                | 1         | 0.47%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 0.47%   |
| Ralink MT7601U Wireless Adapter                                               | 1         | 0.47%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.47%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 0.47%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1         | 0.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 0.47%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 1         | 0.47%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.47%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.47%   |
| Mercucys MERCUSYS Wireless USB Adapter                                        | 1         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 48        | 43.64%  |
| Qualcomm Atheros      | 26        | 23.64%  |
| Realtek Semiconductor | 16        | 14.55%  |
| Broadcom              | 7         | 6.36%   |
| TP-Link               | 4         | 3.64%   |
| Ralink Technology     | 3         | 2.73%   |
| Ralink                | 2         | 1.82%   |
| Mercucys              | 1         | 0.91%   |
| D-Link                | 1         | 0.91%   |
| BUFFALO               | 1         | 0.91%   |
| Atheros               | 1         | 0.91%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 10        | 8.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 6         | 5.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 5         | 4.39%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 4.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 4         | 3.51%   |
| Intel Wireless 7265                                                           | 4         | 3.51%   |
| Intel Wi-Fi 6 AX200                                                           | 4         | 3.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 3         | 2.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 2.63%   |
| Intel Wireless 3165                                                           | 3         | 2.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3         | 2.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 3         | 2.63%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 2         | 1.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 1.75%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 2         | 1.75%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                         | 2         | 1.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 1.75%   |
| Intel Wireless-AC 9260                                                        | 2         | 1.75%   |
| Intel Wireless 8260                                                           | 2         | 1.75%   |
| Intel Wireless 7260                                                           | 2         | 1.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 1.75%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 2         | 1.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 2         | 1.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 2         | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2         | 1.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 2         | 1.75%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1         | 0.88%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]           | 1         | 0.88%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                               | 1         | 0.88%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1         | 0.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1         | 0.88%   |
| Ralink RT3572 Wireless Adapter                                                | 1         | 0.88%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 0.88%   |
| Ralink MT7601U Wireless Adapter                                               | 1         | 0.88%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.88%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 1         | 0.88%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.88%   |
| Mercucys MERCUSYS Wireless USB Adapter                                        | 1         | 0.88%   |
| Intel WiMAX/WiFi Link 5150                                                    | 1         | 0.88%   |
| Intel WiFi Link 5100                                                          | 1         | 0.88%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 1         | 0.88%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 1         | 0.88%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 0.88%   |
| Intel Centrino Wireless-N 2200                                                | 1         | 0.88%   |
| Intel Centrino WiMAX 6150                                                     | 1         | 0.88%   |
| Intel Centrino Ultimate-N 6300                                                | 1         | 0.88%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 0.88%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.B1) [Ralink RT5370]                 | 1         | 0.88%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                      | 1         | 0.88%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1         | 0.88%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 1         | 0.88%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 1         | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 1         | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 0.88%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 1         | 0.88%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 1         | 0.88%   |
| Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]          | 1         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 41        | 47.13%  |
| Intel                            | 19        | 21.84%  |
| Qualcomm Atheros                 | 10        | 11.49%  |
| Broadcom                         | 6         | 6.9%    |
| Marvell Technology Group         | 5         | 5.75%   |
| Silicon Integrated Systems [SiS] | 1         | 1.15%   |
| Realtek                          | 1         | 1.15%   |
| Nvidia                           | 1         | 1.15%   |
| JMicron Technology               | 1         | 1.15%   |
| Attansic                         | 1         | 1.15%   |
| 3Com                             | 1         | 1.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 36.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 9.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 6.9%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 4         | 4.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 2.3%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 2.3%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 2.3%    |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.3%    |
| Intel Ethernet Connection (4) I219-V                              | 2         | 2.3%    |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 2         | 2.3%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.15%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.15%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 1.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.15%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.15%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.15%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 1.15%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 1.15%   |
| Intel PRO/100 VM Network Connection                               | 1         | 1.15%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.15%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.15%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.15%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.15%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.15%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                | 1         | 1.15%   |
| Intel 82801CAM (ICH3) PRO/100 VM (KM) Ethernet Controller         | 1         | 1.15%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 1.15%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.15%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 1.15%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.15%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.15%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 1.15%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                     | 1         | 1.15%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 94        | 49.74%  |
| Ethernet | 85        | 44.97%  |
| Modem    | 5         | 2.65%   |
| Unknown  | 5         | 2.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 68        | 49.64%  |
| WiFi     | 67        | 48.91%  |
| Unknown  | 2         | 1.46%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 82        | 84.54%  |
| 1     | 15        | 15.46%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 95        | 96.94%  |
| Yes  | 3         | 3.06%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 28        | 45.16%  |
| Realtek Semiconductor           | 7         | 11.29%  |
| Qualcomm Atheros Communications | 7         | 11.29%  |
| Lite-On Technology              | 3         | 4.84%   |
| Broadcom                        | 3         | 4.84%   |
| ASUSTek Computer                | 3         | 4.84%   |
| Hewlett-Packard                 | 2         | 3.23%   |
| Apple                           | 2         | 3.23%   |
| Alps Electric                   | 2         | 3.23%   |
| Realtek                         | 1         | 1.61%   |
| Ralink                          | 1         | 1.61%   |
| IMC Networks                    | 1         | 1.61%   |
| Foxconn / Hon Hai               | 1         | 1.61%   |
| Dell                            | 1         | 1.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 13        | 20.97%  |
| Intel AX201 Bluetooth                                       | 4         | 6.45%   |
| Intel AX200 Bluetooth                                       | 4         | 6.45%   |
| Realtek  Bluetooth Adapter                                  | 3         | 4.84%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 3         | 4.84%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 3         | 4.84%   |
| Intel Wireless-AC 3168 Bluetooth                            | 3         | 4.84%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 3.23%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 2         | 3.23%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 3.23%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 2         | 3.23%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 3.23%   |
| Realtek Bluetooth Radio                                     | 1         | 1.61%   |
| Ralink RT3290 Bluetooth                                     | 1         | 1.61%   |
| Qualcomm Atheros  QCA9565 Bluetooth 4.0 + HS Adapter        | 1         | 1.61%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.61%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.61%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 1.61%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 1.61%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 1.61%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                  | 1         | 1.61%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 1.61%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 1.61%   |
| Broadcom BCM43142A0 Bluetooth Module                        | 1         | 1.61%   |
| ASUS BT-270 Bluetooth Adapter                               | 1         | 1.61%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 1.61%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                       | 1         | 1.61%   |
| Apple Bluetooth Host Controller                             | 1         | 1.61%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 1         | 1.61%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 1.61%   |
| Alps Electric BCM2046 Bluetooth Device                      | 1         | 1.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 73        | 68.22%  |
| AMD                              | 24        | 22.43%  |
| Nvidia                           | 5         | 4.67%   |
| Texas Instruments                | 1         | 0.93%   |
| Silicon Integrated Systems [SiS] | 1         | 0.93%   |
| Lenovo                           | 1         | 0.93%   |
| ESS Technology                   | 1         | 0.93%   |
| Creative Technology              | 1         | 0.93%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 9.7%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 8.96%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 5.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 5.22%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 4.48%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 4.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 4.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 4.48%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 4.48%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.99%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 2.24%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 2.24%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 2.24%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 2.24%   |
| AMD FCH Azalia Controller                                                                         | 3         | 2.24%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 1.49%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.49%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.49%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.49%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.49%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 1.49%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 1.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.49%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.49%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.49%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.49%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.49%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.75%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.75%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.75%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.75%   |
| Lenovo Realtek USB Audio                                                                          | 1         | 0.75%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.75%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 0.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.75%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.75%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                                          | 1         | 0.75%   |
| ESS Technology ES1988 Allegro-1                                                                   | 1         | 0.75%   |
| Creative Technology USB Sound Blaster HD                                                          | 1         | 0.75%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.75%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.75%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.75%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 1         | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 24        | 23.53%  |
| SK Hynix            | 19        | 18.63%  |
| Unknown             | 16        | 15.69%  |
| Kingston            | 13        | 12.75%  |
| Micron Technology   | 11        | 10.78%  |
| Elpida              | 3         | 2.94%   |
| 48spaces            | 3         | 2.94%   |
| Transcend           | 2         | 1.96%   |
| Crucial             | 2         | 1.96%   |
| Corsair             | 2         | 1.96%   |
| A-DATA Technology   | 2         | 1.96%   |
| Silicon Power       | 1         | 0.98%   |
| Ramaxel Technology  | 1         | 0.98%   |
| Apacer              | 1         | 0.98%   |
| AMD                 | 1         | 0.98%   |
| Unknown             | 1         | 0.98%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 4         | 3.64%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 3         | 2.73%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 3         | 2.73%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s                     | 3         | 2.73%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 3         | 2.73%   |
| Unknown RAM Module 512MB SODIMM DDR                                       | 2         | 1.82%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM 1333MT/s                         | 2         | 1.82%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 2         | 1.82%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                      | 2         | 1.82%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                      | 2         | 1.82%   |
| Kingston RAM 9905700-011.A00G 8192MB SODIMM DDR4 2400MT/s                 | 2         | 1.82%   |
| Unknown RAM Module 512MB SODIMM DRAM                                      | 1         | 0.91%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 0.91%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                               | 1         | 0.91%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                                 | 1         | 0.91%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 1         | 0.91%   |
| Unknown RAM Module 256MB SODIMM DRAM                                      | 1         | 0.91%   |
| Unknown RAM Module 256MB SODIMM DDR 100MT/s                               | 1         | 0.91%   |
| Unknown RAM Module 2560MB SODIMM DDR                                      | 1         | 0.91%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                                    | 1         | 0.91%   |
| Unknown RAM Module 2048MB SODIMM DDR3                                     | 1         | 0.91%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                     | 1         | 0.91%   |
| Unknown RAM Module 2048MB SODIMM DDR 800MT/s                              | 1         | 0.91%   |
| Unknown RAM Module 128MB SODIMM DRAM                                      | 1         | 0.91%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266MT/s                            | 1         | 0.91%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266(3.8ns)MT/s                     | 1         | 0.91%   |
| Unknown RAM Module 1024MB SODIMM RAM                                      | 1         | 0.91%   |
| Unknown RAM Module 1024MB SODIMM DRAM                                     | 1         | 0.91%   |
| Unknown RAM Module 1024MB SODIMM DDR                                      | 1         | 0.91%   |
| Transcend RAM TS512MSK64V1N 4GB SODIMM 800MT/s                            | 1         | 0.91%   |
| Transcend RAM JM667QSU-2G 2GB SODIMM DDR2 667MT/s                         | 1         | 0.91%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                              | 1         | 0.91%   |
| SK Hynix RAM Module 1024MB SODIMM DDR3 1067MT/s                           | 1         | 0.91%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s                     | 1         | 0.91%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s                    | 1         | 0.91%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.91%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                    | 1         | 0.91%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s                    | 1         | 0.91%   |
| SK Hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s                    | 1         | 0.91%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 1         | 0.91%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 1         | 0.91%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.91%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.91%   |
| SK Hynix RAM H9CCNNNBJTMLAR-NUD 4096MB SODIMM LPDDR3 1867MT/s             | 1         | 0.91%   |
| SK Hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s          | 1         | 0.91%   |
| SK Hynix RAM 484D543332355336 2GB SODIMM DDR3 1333MT/s                    | 1         | 0.91%   |
| Silicon Power RAM SP004GLSTU160N02 4GB SODIMM DDR3 1600MT/s               | 1         | 0.91%   |
| Samsung RAM Module 2GB SODIMM LPDDR3 1867MT/s                             | 1         | 0.91%   |
| Samsung RAM M474A4G43AB1-CVF 32GB SODIMM DDR4 2933MT/s                    | 1         | 0.91%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s                     | 1         | 0.91%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s                     | 1         | 0.91%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.91%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.91%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                     | 1         | 0.91%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s                     | 1         | 0.91%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 1         | 0.91%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 1         | 0.91%   |
| Samsung RAM M4 70T5663RZ3-CF7 2GB SODIMM DDR2 800MT/s                     | 1         | 0.91%   |
| Samsung RAM M4 70T5663QZ3-CE6 2GB SODIMM DDR2 667MT/s                     | 1         | 0.91%   |
| Samsung RAM M4 70T2864QZ3-CF7 1GB SODIMM DDR2 800MT/s                     | 1         | 0.91%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 31        | 36.05%  |
| DDR3    | 29        | 33.72%  |
| DDR2    | 10        | 11.63%  |
| LPDDR3  | 5         | 5.81%   |
| DDR     | 4         | 4.65%   |
| DRAM    | 3         | 3.49%   |
| SDRAM   | 2         | 2.33%   |
| RAM     | 1         | 1.16%   |
| Unknown | 1         | 1.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 82        | 95.35%  |
| Row Of Chips | 2         | 2.33%   |
| DIMM         | 1         | 1.16%   |
| Chip         | 1         | 1.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 31        | 31%     |
| 4096  | 30        | 30%     |
| 2048  | 22        | 22%     |
| 1024  | 6         | 6%      |
| 16384 | 3         | 3%      |
| 512   | 3         | 3%      |
| 256   | 2         | 2%      |
| 32768 | 1         | 1%      |
| 2560  | 1         | 1%      |
| 128   | 1         | 1%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 16        | 18.18%  |
| 2667    | 12        | 13.64%  |
| 2400    | 9         | 10.23%  |
| 1333    | 9         | 10.23%  |
| Unknown | 9         | 10.23%  |
| 3200    | 8         | 9.09%   |
| 667     | 7         | 7.95%   |
| 1867    | 5         | 5.68%   |
| 800     | 4         | 4.55%   |
| 1067    | 3         | 3.41%   |
| 2133    | 2         | 2.27%   |
| 2933    | 1         | 1.14%   |
| 975     | 1         | 1.14%   |
| 266     | 1         | 1.14%   |
| 100     | 1         | 1.14%   |

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
| Chicony Electronics                    | 19        | 26.03%  |
| Realtek Semiconductor                  | 9         | 12.33%  |
| IMC Networks                           | 9         | 12.33%  |
| Acer                                   | 6         | 8.22%   |
| Microdia                               | 5         | 6.85%   |
| Suyin                                  | 4         | 5.48%   |
| Lite-On Technology                     | 4         | 5.48%   |
| Syntek                                 | 3         | 4.11%   |
| Quanta                                 | 3         | 4.11%   |
| ALi                                    | 3         | 4.11%   |
| Silicon Motion                         | 2         | 2.74%   |
| Z-Star Microelectronics                | 1         | 1.37%   |
| Sunplus Innovation Technology          | 1         | 1.37%   |
| ShineTech                              | 1         | 1.37%   |
| Intel                                  | 1         | 1.37%   |
| Denron                                 | 1         | 1.37%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.37%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 5         | 6.67%   |
| IMC Networks Integrated Camera                      | 3         | 4%      |
| Acer Lenovo EasyCamera                              | 3         | 4%      |
| Syntek EasyCamera                                   | 2         | 2.67%   |
| Silicon Motion WebCam SCX Series                    | 2         | 2.67%   |
| Realtek Realtek USB2.0 PC Camera                    | 2         | 2.67%   |
| Realtek Integrated Webcam                           | 2         | 2.67%   |
| Realtek Acer 640 x 480 laptop camera                | 2         | 2.67%   |
| Quanta VGA WebCam                                   | 2         | 2.67%   |
| Microdia Integrated_Webcam_HD                       | 2         | 2.67%   |
| Microdia Integrated Webcam                          | 2         | 2.67%   |
| Lite-On Integrated Camera                           | 2         | 2.67%   |
| Lite-On HP HD Camera                                | 2         | 2.67%   |
| IMC Networks EasyCamera                             | 2         | 2.67%   |
| ALi Gateway Webcam                                  | 2         | 2.67%   |
| Z-Star Webcam                                       | 1         | 1.33%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.33%   |
| Suyin USB 2.0 UVC 1.3M WebCam                       | 1         | 1.33%   |
| Suyin HP Webcam                                     | 1         | 1.33%   |
| Suyin HD WebCam                                     | 1         | 1.33%   |
| Suyin Acer Crystal Eye webcam                       | 1         | 1.33%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.33%   |
| ShineTech HD Camera                                 | 1         | 1.33%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.33%   |
| Realtek USB Webcam                                  | 1         | 1.33%   |
| Realtek Integrated_Webcam_FHD                       | 1         | 1.33%   |
| Realtek Integrated_Webcam_8M                        | 1         | 1.33%   |
| Quanta Realtek DMFT - RGB                           | 1         | 1.33%   |
| Microdia Integrated Webcam HD                       | 1         | 1.33%   |
| Intel WiMAX Connection 2400m                        | 1         | 1.33%   |
| IMC Networks UVC VGA Webcam                         | 1         | 1.33%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 1.33%   |
| IMC Networks USB2.0 UVC 2M WebCam                   | 1         | 1.33%   |
| IMC Networks SunplusIT Integrated Camera            | 1         | 1.33%   |
| Denron Corp., 2M Front Camera                       | 1         | 1.33%   |
| Chicony XiaoMi USB 2.0 Webcam                       | 1         | 1.33%   |
| Chicony USB2.0 0.3M UVC WebCam                      | 1         | 1.33%   |
| Chicony thinkpad t430s camera                       | 1         | 1.33%   |
| Chicony Ltd., Integrated Camera                     | 1         | 1.33%   |
| Chicony Lenovo Integrated Camera UVC                | 1         | 1.33%   |
| Chicony Lenovo EasyCamera                           | 1         | 1.33%   |
| Chicony Integrated IR Camera                        | 1         | 1.33%   |
| Chicony Integrated HP HD Webcam                     | 1         | 1.33%   |
| Chicony Integrated Camera [ThinkPad]                | 1         | 1.33%   |
| Chicony HP Webcam                                   | 1         | 1.33%   |
| Chicony HP HD Webcam [Fixed]                        | 1         | 1.33%   |
| Chicony HD WebCam                                   | 1         | 1.33%   |
| Chicony EasyCamera                                  | 1         | 1.33%   |
| Chicony Chicony USB 2.0 Camera                      | 1         | 1.33%   |
| Chicony Asus 720p CMOS webcam                       | 1         | 1.33%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 1.33%   |
| ALi WebCam                                          | 1         | 1.33%   |
| Acer USB2.0 Camera                                  | 1         | 1.33%   |
| Acer SunplusIT Integrated Camera                    | 1         | 1.33%   |
| Acer Lenovo Integrated Webcam                       | 1         | 1.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 40%     |
| Synaptics                  | 7         | 35%     |
| STMicroelectronics         | 2         | 10%     |
| Shenzhen Goodix Technology | 1         | 5%      |
| Broadcom                   | 1         | 5%      |
| AuthenTec                  | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 4         | 20%     |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 10%     |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 10%     |
| STMicroelectronics Fingerprint Reader                                        | 2         | 10%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 5%      |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 5%      |
| Validity Sensors Synaptics WBDI                                              | 1         | 5%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 1         | 5%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                    | 1         | 5%      |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 5%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 5%      |
| Shenzhen Goodix  Fingerprint Device                                          | 1         | 5%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5%      |
| AuthenTec AES1600                                                            | 1         | 5%      |

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
| 1     | 32        | 30.48%  |
| 2     | 27        | 25.71%  |
| 4     | 15        | 14.29%  |
| 0     | 14        | 13.33%  |
| 3     | 12        | 11.43%  |
| 9     | 1         | 0.95%   |
| 8     | 1         | 0.95%   |
| 7     | 1         | 0.95%   |
| 6     | 1         | 0.95%   |
| 5     | 1         | 0.95%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 50        | 27.93%  |
| Net/wireless             | 33        | 18.44%  |
| Card reader              | 26        | 14.53%  |
| Bluetooth                | 20        | 11.17%  |
| Fingerprint reader       | 17        | 9.5%    |
| Firewire controller      | 10        | 5.59%   |
| Sound                    | 7         | 3.91%   |
| Graphics card            | 6         | 3.35%   |
| Storage                  | 3         | 1.68%   |
| Network                  | 3         | 1.68%   |
| Modem                    | 3         | 1.68%   |
| Storage/ata              | 1         | 0.56%   |
