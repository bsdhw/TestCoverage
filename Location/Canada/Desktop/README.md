BSD in Canada - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for BSD in Canada.

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

Total: 215

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| ASUSTek       | M5A97 PLUS                  | [9d5edd9fa9](https://bsd-hardware.info/?probe=9d5edd9fa9) | May 29, 2022 |
| Dell          | 0M3F6C A01                  | [21d45bc75d](https://bsd-hardware.info/?probe=21d45bc75d) | May 23, 2022 |
| ASUSTek       | PRIME B250M-C               | [c956536edd](https://bsd-hardware.info/?probe=c956536edd) | May 23, 2022 |
| Dell          | 0HHV7N A00                  | [6d7475e9c9](https://bsd-hardware.info/?probe=6d7475e9c9) | May 22, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [963fa158b5](https://bsd-hardware.info/?probe=963fa158b5) | May 22, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [1014f7f61c](https://bsd-hardware.info/?probe=1014f7f61c) | May 18, 2022 |
| Dell          | 0DXJD9 A01                  | [be13c9069c](https://bsd-hardware.info/?probe=be13c9069c) | May 18, 2022 |
| ASUSTek       | PRIME B250M-C               | [9ec22ea24c](https://bsd-hardware.info/?probe=9ec22ea24c) | May 17, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [30cfcd5004](https://bsd-hardware.info/?probe=30cfcd5004) | May 15, 2022 |
| Protectli     | FW4B Ver                    | [9af60bd6e4](https://bsd-hardware.info/?probe=9af60bd6e4) | May 14, 2022 |
| ASUSTek       | M5A97 PLUS                  | [fd066b2db9](https://bsd-hardware.info/?probe=fd066b2db9) | May 14, 2022 |
| Unknown       | Unknown                     | [0958a64385](https://bsd-hardware.info/?probe=0958a64385) | May 12, 2022 |
| Unknown       | Unknown                     | [0d62d4e3cd](https://bsd-hardware.info/?probe=0d62d4e3cd) | May 09, 2022 |
| Gigabyte      | F2A68HM-H                   | [daed3f9401](https://bsd-hardware.info/?probe=daed3f9401) | May 06, 2022 |
| ASUSTek       | H81M-E                      | [cf2f288b93](https://bsd-hardware.info/?probe=cf2f288b93) | May 04, 2022 |
| HP            | 1495                        | [6e0f1cc72e](https://bsd-hardware.info/?probe=6e0f1cc72e) | Apr 29, 2022 |
| HP            | 1998                        | [1244e0583b](https://bsd-hardware.info/?probe=1244e0583b) | Apr 27, 2022 |
| Unknown       | Unknown                     | [b3d5defed1](https://bsd-hardware.info/?probe=b3d5defed1) | Apr 26, 2022 |
| Unknown       | Unknown                     | [4166c67369](https://bsd-hardware.info/?probe=4166c67369) | Apr 20, 2022 |
| Dell          | G5 5090                     | [8b24170852](https://bsd-hardware.info/?probe=8b24170852) | Apr 17, 2022 |
| Unknown       | Unknown                     | [979e868c51](https://bsd-hardware.info/?probe=979e868c51) | Apr 16, 2022 |
| Dell          | 0DXJD9 A01                  | [4023d86091](https://bsd-hardware.info/?probe=4023d86091) | Apr 15, 2022 |
| ASRock        | J3455B-ITX                  | [29be552d6a](https://bsd-hardware.info/?probe=29be552d6a) | Apr 15, 2022 |
| Unknown       | Unknown                     | [1173feae11](https://bsd-hardware.info/?probe=1173feae11) | Apr 13, 2022 |
| Dell          | 0DXJD9 A01                  | [6dac56f3bb](https://bsd-hardware.info/?probe=6dac56f3bb) | Apr 11, 2022 |
| Dell          | 0WR7PY A03                  | [641d1574ce](https://bsd-hardware.info/?probe=641d1574ce) | Apr 11, 2022 |
| PC Engines    | APU                         | [e266947055](https://bsd-hardware.info/?probe=e266947055) | Mar 29, 2022 |
| Unknown       | Unknown                     | [ef1a743845](https://bsd-hardware.info/?probe=ef1a743845) | Mar 28, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [1176fca4ab](https://bsd-hardware.info/?probe=1176fca4ab) | Mar 27, 2022 |
| Unknown       | Unknown                     | [d0e7b62eda](https://bsd-hardware.info/?probe=d0e7b62eda) | Mar 25, 2022 |
| Protectli     | FW4B Ver                    | [cf576c571d](https://bsd-hardware.info/?probe=cf576c571d) | Mar 22, 2022 |
| HP            | 213D A01                    | [6baba4f9c1](https://bsd-hardware.info/?probe=6baba4f9c1) | Mar 20, 2022 |
| ASUSTek       | P8Z68-V LE                  | [3727ba82af](https://bsd-hardware.info/?probe=3727ba82af) | Mar 19, 2022 |
| Intel         | SHARKBAY                    | [f22a45488b](https://bsd-hardware.info/?probe=f22a45488b) | Mar 15, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [a5fd383c40](https://bsd-hardware.info/?probe=a5fd383c40) | Mar 14, 2022 |
| MSI           | MS-7388                     | [ad8209dbdb](https://bsd-hardware.info/?probe=ad8209dbdb) | Mar 05, 2022 |
| MSI           | MS-7388                     | [a59bca8bde](https://bsd-hardware.info/?probe=a59bca8bde) | Mar 05, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [a6abb45607](https://bsd-hardware.info/?probe=a6abb45607) | Mar 04, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [6b2550968e](https://bsd-hardware.info/?probe=6b2550968e) | Feb 23, 2022 |
| Intel         | Q3XXG4-P V1.0               | [b69015f0e0](https://bsd-hardware.info/?probe=b69015f0e0) | Feb 16, 2022 |
| PC Engines    | apu4                        | [09f27a0f23](https://bsd-hardware.info/?probe=09f27a0f23) | Feb 14, 2022 |
| Protectli     | FW6                         | [d33b2f1244](https://bsd-hardware.info/?probe=d33b2f1244) | Feb 13, 2022 |
| ASRock        | AM1H-ITX                    | [12ccb8699b](https://bsd-hardware.info/?probe=12ccb8699b) | Feb 08, 2022 |
| ASRock        | AM1H-ITX                    | [0d3b560aad](https://bsd-hardware.info/?probe=0d3b560aad) | Feb 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [3dabf0503d](https://bsd-hardware.info/?probe=3dabf0503d) | Feb 08, 2022 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | [53abdfa3b1](https://bsd-hardware.info/?probe=53abdfa3b1) | Feb 07, 2022 |
| ASUSTek       | PRIME H410M-A               | [1dafdcc71a](https://bsd-hardware.info/?probe=1dafdcc71a) | Feb 05, 2022 |
| ASRock        | J4105M                      | [09b9d104b9](https://bsd-hardware.info/?probe=09b9d104b9) | Feb 03, 2022 |
| Intel         | Q3XXG4-P V1.0               | [07d565ad8c](https://bsd-hardware.info/?probe=07d565ad8c) | Feb 02, 2022 |
| ASRock        | J3455B-ITX                  | [83975bd2b1](https://bsd-hardware.info/?probe=83975bd2b1) | Jan 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | [ff629a490d](https://bsd-hardware.info/?probe=ff629a490d) | Jan 29, 2022 |
| Dell          | 0WMJ54 A01                  | [4b17ef7a18](https://bsd-hardware.info/?probe=4b17ef7a18) | Jan 27, 2022 |
| PC Engines    | APU2                        | [5ea082ddf9](https://bsd-hardware.info/?probe=5ea082ddf9) | Jan 13, 2022 |
| Dell          | 0X4N41 A01                  | [87000234dc](https://bsd-hardware.info/?probe=87000234dc) | Jan 11, 2022 |
| ASUSTek       | P8Z68-M PRO                 | [a0885f4f44](https://bsd-hardware.info/?probe=a0885f4f44) | Jan 10, 2022 |
| Unknown       | Unknown                     | [ded64258b4](https://bsd-hardware.info/?probe=ded64258b4) | Jan 09, 2022 |
| Unknown       | Unknown                     | [8d607c1d19](https://bsd-hardware.info/?probe=8d607c1d19) | Jan 03, 2022 |
| Unknown       | Unknown                     | [c183bdd5af](https://bsd-hardware.info/?probe=c183bdd5af) | Jan 01, 2022 |
| Unknown       | Unknown                     | [4848e4009f](https://bsd-hardware.info/?probe=4848e4009f) | Jan 01, 2022 |
| AMI           | Cherry Trail CR             | [7d47d0db05](https://bsd-hardware.info/?probe=7d47d0db05) | Dec 30, 2021 |
| ASUSTek       | P8B75-M                     | [c3884fac44](https://bsd-hardware.info/?probe=c3884fac44) | Dec 30, 2021 |
| ASUSTek       | Z170-P                      | [bde74629f9](https://bsd-hardware.info/?probe=bde74629f9) | Dec 25, 2021 |
| ASRock        | J3355B-ITX                  | [f4648747b0](https://bsd-hardware.info/?probe=f4648747b0) | Dec 22, 2021 |
| Quanta        | 2AC7 011                    | [1a831a1d34](https://bsd-hardware.info/?probe=1a831a1d34) | Dec 18, 2021 |
| HP            | 843B                        | [f0d279747f](https://bsd-hardware.info/?probe=f0d279747f) | Dec 13, 2021 |
| HP            | 843B                        | [56400d3999](https://bsd-hardware.info/?probe=56400d3999) | Dec 13, 2021 |
| AMI           | Cherry Trail CR             | [624041b5db](https://bsd-hardware.info/?probe=624041b5db) | Dec 09, 2021 |
| Dell          | 051FJ8 A01                  | [ccfb8336a0](https://bsd-hardware.info/?probe=ccfb8336a0) | Dec 01, 2021 |
| HP            | 843B                        | [376e006a40](https://bsd-hardware.info/?probe=376e006a40) | Nov 30, 2021 |
| HP            | 843B                        | [404224439d](https://bsd-hardware.info/?probe=404224439d) | Nov 29, 2021 |
| HP            | 843B                        | [a8ac0e9efb](https://bsd-hardware.info/?probe=a8ac0e9efb) | Nov 29, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | [dc9d060c7f](https://bsd-hardware.info/?probe=dc9d060c7f) | Nov 27, 2021 |
| Acer          | Aspire X1800                | [a26bc8f2b3](https://bsd-hardware.info/?probe=a26bc8f2b3) | Nov 14, 2021 |
| Gigabyte      | MRZNVMS-00                  | [817cb3e603](https://bsd-hardware.info/?probe=817cb3e603) | Nov 12, 2021 |
| Acer          | Aspire X1800                | [970387f9d9](https://bsd-hardware.info/?probe=970387f9d9) | Nov 09, 2021 |
| Protectli     | FW6E                        | [ebe5b24dee](https://bsd-hardware.info/?probe=ebe5b24dee) | Nov 08, 2021 |
| Protectli     | FW6E                        | [6c12084410](https://bsd-hardware.info/?probe=6c12084410) | Nov 07, 2021 |
| Acer          | Aspire X1800                | [99b5ab3e42](https://bsd-hardware.info/?probe=99b5ab3e42) | Nov 04, 2021 |
| ASRock        | H370M-ITX/ac                | [bf37ad85e7](https://bsd-hardware.info/?probe=bf37ad85e7) | Nov 03, 2021 |
| Unknown       | Unknown                     | [579cf2ac1a](https://bsd-hardware.info/?probe=579cf2ac1a) | Oct 31, 2021 |
| Intel         | Q3XXG4-P V1.0               | [7abc8386ec](https://bsd-hardware.info/?probe=7abc8386ec) | Oct 31, 2021 |
| HP            | 843B                        | [9761f29b5e](https://bsd-hardware.info/?probe=9761f29b5e) | Oct 25, 2021 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | [c3d6cddf87](https://bsd-hardware.info/?probe=c3d6cddf87) | Oct 25, 2021 |
| Intel         | CRESCENTBAY                 | [5c8f3708b1](https://bsd-hardware.info/?probe=5c8f3708b1) | Oct 21, 2021 |
| Acer          | Aspire TC-780               | [77101a00b3](https://bsd-hardware.info/?probe=77101a00b3) | Oct 11, 2021 |
| Acer          | Aspire TC-780               | [3ce8481842](https://bsd-hardware.info/?probe=3ce8481842) | Oct 10, 2021 |
| Acer          | Aspire X1800                | [cc419789f8](https://bsd-hardware.info/?probe=cc419789f8) | Oct 08, 2021 |
| MSI           | B450I GAMING PLUS AC        | [43388a27a4](https://bsd-hardware.info/?probe=43388a27a4) | Oct 04, 2021 |
| Lenovo        | ThinkCentre M58e 7268A9U    | [00bafc5f7c](https://bsd-hardware.info/?probe=00bafc5f7c) | Oct 03, 2021 |
| ASUSTek       | H81M-E                      | [0cc0d2dcb1](https://bsd-hardware.info/?probe=0cc0d2dcb1) | Oct 01, 2021 |
| ASUSTek       | H81M-E                      | [76866f2db7](https://bsd-hardware.info/?probe=76866f2db7) | Oct 01, 2021 |
| ASUSTek       | H81M-E                      | [319470ebbd](https://bsd-hardware.info/?probe=319470ebbd) | Oct 01, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [36a5bc62bf](https://bsd-hardware.info/?probe=36a5bc62bf) | Sep 27, 2021 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | [01e33c8399](https://bsd-hardware.info/?probe=01e33c8399) | Sep 26, 2021 |
| ASUSTek       | H81M-E                      | [137654a2f8](https://bsd-hardware.info/?probe=137654a2f8) | Sep 24, 2021 |
| ASUSTek       | H81M-E                      | [dec23f7ff8](https://bsd-hardware.info/?probe=dec23f7ff8) | Sep 23, 2021 |
| AMI           | Cherry Trail CR             | [3b709e37c2](https://bsd-hardware.info/?probe=3b709e37c2) | Sep 12, 2021 |
| ASUSTek       | P8H77-I                     | [1feb22dc52](https://bsd-hardware.info/?probe=1feb22dc52) | Sep 12, 2021 |
| HP            | 212B                        | [d3894b9f37](https://bsd-hardware.info/?probe=d3894b9f37) | Sep 10, 2021 |
| ASRock        | H110M-DGS R3.0              | [df08c4e6d3](https://bsd-hardware.info/?probe=df08c4e6d3) | Sep 09, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | [c64c51359c](https://bsd-hardware.info/?probe=c64c51359c) | Sep 09, 2021 |
| MSI           | CSM-B85M-P32                | [e960bc2548](https://bsd-hardware.info/?probe=e960bc2548) | Sep 01, 2021 |
| Gigabyte      | H61N-USB3                   | [3dca10264a](https://bsd-hardware.info/?probe=3dca10264a) | Aug 29, 2021 |
| ASRock        | B450M Pro4                  | [70dc185964](https://bsd-hardware.info/?probe=70dc185964) | Aug 25, 2021 |
| HP            | 1589                        | [4d51cc9c4b](https://bsd-hardware.info/?probe=4d51cc9c4b) | Aug 24, 2021 |
| Acer          | Aspire TC-895 V:1.0         | [da3e8986a3](https://bsd-hardware.info/?probe=da3e8986a3) | Aug 22, 2021 |
| AMI           | Cherry Trail CR             | [bd94ad09ef](https://bsd-hardware.info/?probe=bd94ad09ef) | Aug 12, 2021 |
| Lenovo        | ThinkCentre M58e 7268A9U    | [94201b7633](https://bsd-hardware.info/?probe=94201b7633) | Aug 10, 2021 |
| Supermicro    | X11SDV-8C-TP8F              | [6da61be169](https://bsd-hardware.info/?probe=6da61be169) | Aug 08, 2021 |
| Intel         | Q3XXG4-P V1.0               | [535b577563](https://bsd-hardware.info/?probe=535b577563) | Aug 03, 2021 |
| HP            | ProLiant ML150 G6           | [783c2ba254](https://bsd-hardware.info/?probe=783c2ba254) | Aug 02, 2021 |
| Protectli     | FW4B Ver                    | [b434d9bfb8](https://bsd-hardware.info/?probe=b434d9bfb8) | Aug 02, 2021 |
| ASUSTek       | P5QL PRO                    | [4d118404a8](https://bsd-hardware.info/?probe=4d118404a8) | Jul 29, 2021 |
| ASRock        | J3455B-ITX                  | [fc13802cd3](https://bsd-hardware.info/?probe=fc13802cd3) | Jul 19, 2021 |
| Intel         | SHARKBAY                    | [5697d53687](https://bsd-hardware.info/?probe=5697d53687) | Jul 19, 2021 |
| ASRock        | J3455B-ITX                  | [c7dbe473bc](https://bsd-hardware.info/?probe=c7dbe473bc) | Jul 17, 2021 |
| Lenovo        | SHARKBAY 0C48431 PRO        | [0a1fa8924e](https://bsd-hardware.info/?probe=0a1fa8924e) | Jul 17, 2021 |
| ASRock        | J3455B-ITX                  | [b86c2cfc99](https://bsd-hardware.info/?probe=b86c2cfc99) | Jul 16, 2021 |
| PC Engines    | apu4                        | [51163b13ef](https://bsd-hardware.info/?probe=51163b13ef) | Jul 11, 2021 |
| Intel         | SHARKBAY                    | [59a1b5f761](https://bsd-hardware.info/?probe=59a1b5f761) | Jul 10, 2021 |
| Gigabyte      | H97-D3H-CF                  | [a326fd4061](https://bsd-hardware.info/?probe=a326fd4061) | Jun 20, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [ef7104e237](https://bsd-hardware.info/?probe=ef7104e237) | Jun 20, 2021 |
| ASUSTek       | ROG STRIX H370-I GAMING     | [d2dd261a2a](https://bsd-hardware.info/?probe=d2dd261a2a) | Jun 20, 2021 |
| Intel         | SHARKBAY                    | [6aa5f8046e](https://bsd-hardware.info/?probe=6aa5f8046e) | Jun 19, 2021 |
| Shuttle       | FS110                       | [9b4093c9a1](https://bsd-hardware.info/?probe=9b4093c9a1) | Jun 17, 2021 |
| Intel         | Q3XXG4-P V1.0               | [459bf008e9](https://bsd-hardware.info/?probe=459bf008e9) | Jun 12, 2021 |
| HP            | 805D                        | [dc4e61ecd4](https://bsd-hardware.info/?probe=dc4e61ecd4) | Jun 07, 2021 |
| HP            | 1998                        | [2806e1e8cf](https://bsd-hardware.info/?probe=2806e1e8cf) | Jun 05, 2021 |
| Intel         | Q3XXG4-P V1.0               | [95a281e2f8](https://bsd-hardware.info/?probe=95a281e2f8) | Jun 04, 2021 |
| Unknown       | Unknown                     | [65dd81d59e](https://bsd-hardware.info/?probe=65dd81d59e) | Jun 02, 2021 |
| Protectli     | FW4B Ver                    | [7e013ea910](https://bsd-hardware.info/?probe=7e013ea910) | May 20, 2021 |
| Unknown       | Unknown                     | [f90e5f9566](https://bsd-hardware.info/?probe=f90e5f9566) | May 16, 2021 |
| Unknown       | Unknown                     | [e67de92cb9](https://bsd-hardware.info/?probe=e67de92cb9) | May 14, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | [273e379d9f](https://bsd-hardware.info/?probe=273e379d9f) | May 14, 2021 |
| Shuttle       | FS110                       | [e39173782f](https://bsd-hardware.info/?probe=e39173782f) | May 08, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | [1f78fbb36c](https://bsd-hardware.info/?probe=1f78fbb36c) | May 08, 2021 |
| Intel         | Q3XXG4-P V1.0               | [5a128dd6a3](https://bsd-hardware.info/?probe=5a128dd6a3) | Apr 22, 2021 |
| HP            | 18E7                        | [e6354de524](https://bsd-hardware.info/?probe=e6354de524) | Apr 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | [7a6f106b0e](https://bsd-hardware.info/?probe=7a6f106b0e) | Apr 18, 2021 |
| Intel         | SHARKBAY                    | [cd0467031a](https://bsd-hardware.info/?probe=cd0467031a) | Apr 17, 2021 |
| HARDKERNEL    | ODROID-H2                   | [5a1a372153](https://bsd-hardware.info/?probe=5a1a372153) | Apr 16, 2021 |
| HARDKERNEL    | ODROID-H2                   | [31a9bf167b](https://bsd-hardware.info/?probe=31a9bf167b) | Apr 16, 2021 |
| Dell          | 051FJ8 A01                  | [351b13fd3b](https://bsd-hardware.info/?probe=351b13fd3b) | Apr 15, 2021 |
| ASRock        | J4105M                      | [69165e1573](https://bsd-hardware.info/?probe=69165e1573) | Apr 13, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [5aca6c03c1](https://bsd-hardware.info/?probe=5aca6c03c1) | Apr 09, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | [0e814e53e9](https://bsd-hardware.info/?probe=0e814e53e9) | Apr 09, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | [817ec0a0da](https://bsd-hardware.info/?probe=817ec0a0da) | Apr 09, 2021 |
| ASUSTek       | PRIME H410M-A               | [6f4f9fb14e](https://bsd-hardware.info/?probe=6f4f9fb14e) | Apr 07, 2021 |
| HP            | 2AF7                        | [acd341147c](https://bsd-hardware.info/?probe=acd341147c) | Apr 03, 2021 |
| Dell          | 0TTDMJ A00                  | [b5c0428c8a](https://bsd-hardware.info/?probe=b5c0428c8a) | Mar 30, 2021 |
| ASRock        | H110M-DGS R3.0              | [6af0a9bc78](https://bsd-hardware.info/?probe=6af0a9bc78) | Mar 30, 2021 |
| ASRock        | H110M-DGS R3.0              | [aaf140005c](https://bsd-hardware.info/?probe=aaf140005c) | Mar 30, 2021 |
| AMI           | Cherry Trail CR             | [636dfb334b](https://bsd-hardware.info/?probe=636dfb334b) | Mar 29, 2021 |
| Gigabyte      | D525TUD                     | [a48a515986](https://bsd-hardware.info/?probe=a48a515986) | Mar 24, 2021 |
| Dell          | 0M9KCM A00                  | [7280d52eff](https://bsd-hardware.info/?probe=7280d52eff) | Mar 23, 2021 |
| Dell          | 04YP6J A02                  | [061ad76c0e](https://bsd-hardware.info/?probe=061ad76c0e) | Mar 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | [03935b2745](https://bsd-hardware.info/?probe=03935b2745) | Mar 20, 2021 |
| Dell          | 00V62H A00                  | [27cb6a75c8](https://bsd-hardware.info/?probe=27cb6a75c8) | Mar 19, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [8964a02114](https://bsd-hardware.info/?probe=8964a02114) | Mar 15, 2021 |
| ASRock        | B450M Pro4                  | [e9ca160a2d](https://bsd-hardware.info/?probe=e9ca160a2d) | Mar 11, 2021 |
| Shuttle       | FS110                       | [fc31311d01](https://bsd-hardware.info/?probe=fc31311d01) | Mar 10, 2021 |
| Supermicro    | A2SDi-TP8F                  | [c30d805062](https://bsd-hardware.info/?probe=c30d805062) | Mar 05, 2021 |
| ASUSTek       | PRIME H410M-A               | [c7b0539b99](https://bsd-hardware.info/?probe=c7b0539b99) | Mar 02, 2021 |
| Gigabyte      | Z77X-UP5 TH-CF              | [9d35f9e853](https://bsd-hardware.info/?probe=9d35f9e853) | Feb 24, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | [11d6c98009](https://bsd-hardware.info/?probe=11d6c98009) | Feb 21, 2021 |
| Protectli     | FW6                         | [b656792690](https://bsd-hardware.info/?probe=b656792690) | Feb 20, 2021 |
| ASUSTek       | PRIME H410M-A               | [cfd1824b40](https://bsd-hardware.info/?probe=cfd1824b40) | Feb 18, 2021 |
| Gigabyte      | MRZNVMS-00                  | [b51cb672a4](https://bsd-hardware.info/?probe=b51cb672a4) | Feb 12, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [3402eabdbf](https://bsd-hardware.info/?probe=3402eabdbf) | Feb 09, 2021 |
| ASRock        | Z270M-ITX/ac                | [9b50d422e3](https://bsd-hardware.info/?probe=9b50d422e3) | Feb 04, 2021 |
| HP            | 0AECh D                     | [6dde87584c](https://bsd-hardware.info/?probe=6dde87584c) | Feb 04, 2021 |
| PC Engines    | apu4                        | [18dfb34a97](https://bsd-hardware.info/?probe=18dfb34a97) | Feb 04, 2021 |
| HP            | 3397                        | [cda4af23ee](https://bsd-hardware.info/?probe=cda4af23ee) | Feb 03, 2021 |
| Gigabyte      | Z77X-UP5 TH-CF              | [0a48224f4b](https://bsd-hardware.info/?probe=0a48224f4b) | Feb 03, 2021 |
| HP            | 3397                        | [65f1db2a70](https://bsd-hardware.info/?probe=65f1db2a70) | Feb 03, 2021 |
| HP            | 82B4                        | [faf58d8f87](https://bsd-hardware.info/?probe=faf58d8f87) | Jan 30, 2021 |
| Dell          | 04YP6J A02                  | [12056c71ad](https://bsd-hardware.info/?probe=12056c71ad) | Jan 30, 2021 |
| PC Engines    | apu2                        | [7e96c61bf9](https://bsd-hardware.info/?probe=7e96c61bf9) | Jan 30, 2021 |
| ASRock        | J3455-ITX                   | [65bde09c13](https://bsd-hardware.info/?probe=65bde09c13) | Jan 26, 2021 |
| ASRock        | J3455-ITX                   | [0a4d4fc896](https://bsd-hardware.info/?probe=0a4d4fc896) | Jan 25, 2021 |
| ASRock        | J3355B-ITX                  | [e8496a6202](https://bsd-hardware.info/?probe=e8496a6202) | Jan 24, 2021 |
| PC Engines    | apu2                        | [da6e3cd1a6](https://bsd-hardware.info/?probe=da6e3cd1a6) | Jan 23, 2021 |
| PC Engines    | apu2                        | [3d536a42eb](https://bsd-hardware.info/?probe=3d536a42eb) | Jan 21, 2021 |
| PC Engines    | apu2                        | [043446a653](https://bsd-hardware.info/?probe=043446a653) | Jan 21, 2021 |
| Shuttle       | FS110                       | [fed17a1f77](https://bsd-hardware.info/?probe=fed17a1f77) | Jan 21, 2021 |
| Supermicro    | X8STi                       | [7cda964f76](https://bsd-hardware.info/?probe=7cda964f76) | Jan 20, 2021 |
| Dell          | 0M9KCM A02                  | [1cc5f6a07b](https://bsd-hardware.info/?probe=1cc5f6a07b) | Jan 20, 2021 |
| ASUSTek       | Z97-A                       | [8c55004504](https://bsd-hardware.info/?probe=8c55004504) | Jan 19, 2021 |
| Supermicro    | X7SLA                       | [2d31f38bf0](https://bsd-hardware.info/?probe=2d31f38bf0) | Jan 10, 2021 |
| Supermicro    | X7SPA-HF                    | [834cb6c68a](https://bsd-hardware.info/?probe=834cb6c68a) | Jan 10, 2021 |
| MSI           | X58 Pro-E                   | [bd108f94d5](https://bsd-hardware.info/?probe=bd108f94d5) | Jan 02, 2021 |
| HP            | 212B                        | [7fe9d2c508](https://bsd-hardware.info/?probe=7fe9d2c508) | Dec 18, 2020 |
| Dell          | 0GM819                      | [adc8eb1931](https://bsd-hardware.info/?probe=adc8eb1931) | Dec 18, 2020 |
| HP            | 805D                        | [dc62857275](https://bsd-hardware.info/?probe=dc62857275) | Dec 17, 2020 |
| Supermicro    | X8STi                       | [80c2762cfb](https://bsd-hardware.info/?probe=80c2762cfb) | Dec 16, 2020 |
| ASRockRack    | D1541D4U-2O8R               | [d59d8a3b6d](https://bsd-hardware.info/?probe=d59d8a3b6d) | Dec 16, 2020 |
| Supermicro    | X11SSH-F                    | [ebb920c0c4](https://bsd-hardware.info/?probe=ebb920c0c4) | Dec 16, 2020 |
| MSI           | X99S SLI PLUS               | [9b2421d9d5](https://bsd-hardware.info/?probe=9b2421d9d5) | Nov 28, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [5d5ecb38cd](https://bsd-hardware.info/?probe=5d5ecb38cd) | Nov 25, 2020 |
| MSI           | 970 GAMING                  | [002b408f7e](https://bsd-hardware.info/?probe=002b408f7e) | Nov 18, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [714b6539cf](https://bsd-hardware.info/?probe=714b6539cf) | Nov 07, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [9f871ab960](https://bsd-hardware.info/?probe=9f871ab960) | Nov 01, 2020 |
| Intel         | X79 V2.81A                  | [d5b4cdf28a](https://bsd-hardware.info/?probe=d5b4cdf28a) | Oct 30, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [59c940d739](https://bsd-hardware.info/?probe=59c940d739) | Oct 30, 2020 |
| Unknown       | Unknown                     | [8552669e76](https://bsd-hardware.info/?probe=8552669e76) | Oct 30, 2020 |
| Unknown       | Unknown                     | [50966c2f83](https://bsd-hardware.info/?probe=50966c2f83) | Oct 30, 2020 |
| ADI Engine... | RCC-VE                      | [30440abc03](https://bsd-hardware.info/?probe=30440abc03) | Oct 29, 2020 |
| IBM           | Board                       | [11b0b7012f](https://bsd-hardware.info/?probe=11b0b7012f) | Oct 21, 2020 |
| IBM           | Board                       | [a92c08a920](https://bsd-hardware.info/?probe=a92c08a920) | Oct 21, 2020 |
| IBM           | Board                       | [80d5f15a63](https://bsd-hardware.info/?probe=80d5f15a63) | Oct 21, 2020 |
| MSI           | MS-7250                     | [41e2d9dab3](https://bsd-hardware.info/?probe=41e2d9dab3) | Sep 04, 2020 |
| HP            | 3031h                       | [1f2695b3a7](https://bsd-hardware.info/?probe=1f2695b3a7) | Aug 25, 2020 |
| ASUSTek       | Z170-P                      | [49e01a949b](https://bsd-hardware.info/?probe=49e01a949b) | Jul 29, 2020 |
| ASUSTek       | P8Z77-V LK                  | [0f7697b73a](https://bsd-hardware.info/?probe=0f7697b73a) | May 28, 2020 |
| Dell          | 0T10XW A02                  | [81f39f3061](https://bsd-hardware.info/?probe=81f39f3061) | May 28, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| OPNsense 21.1.4         | 8        | 4.57%   |
| helloSystem 0.5.0       | 8        | 4.57%   |
| OPNsense 22.1.7         | 7        | 4%      |
| OPNsense 22.1           | 7        | 4%      |
| OPNsense 21.7           | 7        | 4%      |
| OPNsense 21.1.3         | 7        | 4%      |
| OPNsense 21.1           | 7        | 4%      |
| OPNsense 22.1.6         | 6        | 3.43%   |
| OPNsense 21.1.5         | 6        | 3.43%   |
| OPNsense 20.7.8         | 6        | 3.43%   |
| OPNsense 21.7.7         | 5        | 2.86%   |
| OPNsense 21.7.3         | 5        | 2.86%   |
| OPNsense 21.7.1         | 5        | 2.86%   |
| OPNsense 21.1.6         | 5        | 2.86%   |
| OPNsense 21.1.1         | 5        | 2.86%   |
| helloSystem 0.7.0       | 5        | 2.86%   |
| FreeBSD 12.2            | 5        | 2.86%   |
| OPNsense 22.1.3         | 4        | 2.29%   |
| OPNsense 21.7.8         | 4        | 2.29%   |
| OPNsense 21.7.4         | 4        | 2.29%   |
| OPNsense 21.1.8         | 3        | 1.71%   |
| OPNsense 21.1.7         | 3        | 1.71%   |
| OPNsense 21.1.2         | 3        | 1.71%   |
| FreeBSD 13.0            | 3        | 1.71%   |
| OPNsense 22.1.4         | 2        | 1.14%   |
| OPNsense 22.1.2         | 2        | 1.14%   |
| OPNsense 21.7.5         | 2        | 1.14%   |
| OPNsense 21.7.2         | 2        | 1.14%   |
| OPNsense 21.1.9         | 2        | 1.14%   |
| FreeNAS 11.3-p14        | 2        | 1.14%   |
| FreeBSD 13.0-p5         | 2        | 1.14%   |
| FreeBSD 12.2-STABLE     | 2        | 1.14%   |
| FreeBSD 12.1-p9         | 2        | 1.14%   |
| FreeBSD 12.1-p8         | 2        | 1.14%   |
| FreeBSD 12.1-p7         | 2        | 1.14%   |
| FreeBSD 11.4-p6         | 2        | 1.14%   |
| TrueNAS 12.2-RC3        | 1        | 0.57%   |
| OPNsense 22.1.1         | 1        | 0.57%   |
| OPNsense 21.7.6         | 1        | 0.57%   |
| OpenBSD 7.1             | 1        | 0.57%   |
| OpenBSD 6.8             | 1        | 0.57%   |
| helloSystem 0.8.0       | 1        | 0.57%   |
| helloSystem 0.6.0       | 1        | 0.57%   |
| helloSystem 0.4.0       | 1        | 0.57%   |
| GhostBSD 22.05.14       | 1        | 0.57%   |
| GhostBSD 22.04.06       | 1        | 0.57%   |
| GhostBSD 20.04.02       | 1        | 0.57%   |
| FreeNAS 11.4-p4         | 1        | 0.57%   |
| FreeBSD 13.1-RC3        | 1        | 0.57%   |
| FreeBSD 13.1-RC2        | 1        | 0.57%   |
| FreeBSD 13.1-PRERELEASE | 1        | 0.57%   |
| FreeBSD 13.1            | 1        | 0.57%   |
| FreeBSD 13.0-p4         | 1        | 0.57%   |
| FreeBSD 13.0-p11        | 1        | 0.57%   |
| FreeBSD 12.2-p2         | 1        | 0.57%   |
| FreeBSD 12.1-STABLE     | 1        | 0.57%   |
| FreeBSD 12.1-p5         | 1        | 0.57%   |
| FreeBSD 12.1-p4         | 1        | 0.57%   |
| FreeBSD 12.1-p12        | 1        | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 85       | 60.28%  |
| FreeBSD     | 31       | 21.99%  |
| helloSystem | 16       | 11.35%  |
| GhostBSD    | 3        | 2.13%   |
| FreeNAS     | 3        | 2.13%   |
| OpenBSD     | 2        | 1.42%   |
| TrueNAS     | 1        | 0.71%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 137      | 99.28%  |
| i386  | 1        | 0.72%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 102      | 72.86%  |
| helloDesktop | 16       | 11.43%  |
| KDE5         | 6        | 4.29%   |
| MATE         | 5        | 3.57%   |
| XFCE         | 4        | 2.86%   |
| GNOME        | 2        | 1.43%   |
| Cinnamon     | 2        | 1.43%   |
| X-Cinnamon   | 1        | 0.71%   |
| Window Maker | 1        | 0.71%   |
| LXDE         | 1        | 0.71%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 102      | 73.91%  |
| X11     | 35       | 25.36%  |
| Wayland | 1        | 0.72%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 107      | 76.43%  |
| SLiM    | 18       | 12.86%  |
| SDDM    | 9        | 6.43%   |
| LightDM | 3        | 2.14%   |
| XDM     | 2        | 1.43%   |
| GDM     | 1        | 0.71%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 96       | 69.06%  |
| en_US   | 29       | 20.86%  |
| C       | 10       | 7.19%   |
| en_CA   | 3        | 2.16%   |
| fr_FR   | 1        | 0.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 110      | 78.57%  |
| BIOS | 30       | 21.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 79       | 54.86%  |
| Zfs    | 59       | 40.97%  |
| Cd9660 | 4        | 2.78%   |
| Ffs    | 2        | 1.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 126      | 91.3%   |
| MBR     | 11       | 7.97%   |
| Unknown | 1        | 0.72%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 20       | 14.49%  |
| Hewlett-Packard     | 17       | 12.32%  |
| Dell                | 16       | 11.59%  |
| ASRock              | 11       | 7.97%   |
| Intel               | 10       | 7.25%   |
| Gigabyte Technology | 9        | 6.52%   |
| Unknown             | 9        | 6.52%   |
| Supermicro          | 8        | 5.8%    |
| MSI                 | 8        | 5.8%    |
| Protectli           | 7        | 5.07%   |
| Lenovo              | 7        | 5.07%   |
| PC Engines          | 5        | 3.62%   |
| Acer                | 3        | 2.17%   |
| Shuttle             | 1        | 0.72%   |
| SeeedStudio         | 1        | 0.72%   |
| Quanta              | 1        | 0.72%   |
| IBM                 | 1        | 0.72%   |
| HARDKERNEL          | 1        | 0.72%   |
| ASRockRack          | 1        | 0.72%   |
| AMI                 | 1        | 0.72%   |
| ADI Engineering     | 1        | 0.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown                             | 9        | 6.52%   |
| Intel Q3XXG4-P V1.0                 | 5        | 3.62%   |
| Protectli FW4B                      | 4        | 2.9%    |
| Intel NDISB533                      | 3        | 2.17%   |
| Dell OptiPlex 9010                  | 3        | 2.17%   |
| Dell G5 5090                        | 3        | 2.17%   |
| ASUS All Series                     | 3        | 2.17%   |
| Supermicro X8STi                    | 2        | 1.45%   |
| Protectli FW6                       | 2        | 1.45%   |
| PC Engines apu4                     | 2        | 1.45%   |
| PC Engines apu2                     | 2        | 1.45%   |
| Lenovo ThinkCentre M93p 10A8S16X0J  | 2        | 1.45%   |
| HP Z440 Workstation                 | 2        | 1.45%   |
| HP EliteDesk 800 G1 SFF             | 2        | 1.45%   |
| Dell OptiPlex 3020                  | 2        | 1.45%   |
| ASRock H110M-DGS R3.0               | 2        | 1.45%   |
| ASRock B450M Pro4                   | 2        | 1.45%   |
| Supermicro X7SPA-HF                 | 1        | 0.72%   |
| Supermicro X7SLA                    | 1        | 0.72%   |
| Supermicro SYS-E300-9A              | 1        | 0.72%   |
| Supermicro SYS-5019S-ML             | 1        | 0.72%   |
| Supermicro SYS-5019D-FN8TP          | 1        | 0.72%   |
| Supermicro SYS-5019A-FTN4           | 1        | 0.72%   |
| Shuttle DH110                       | 1        | 0.72%   |
| SeeedStudio ODYSSEY-X86J4105        | 1        | 0.72%   |
| Quanta 120-1135                     | 1        | 0.72%   |
| Protectli FW6E                      | 1        | 0.72%   |
| PC Engines APU                      | 1        | 0.72%   |
| MSI MS-7B79                         | 1        | 0.72%   |
| MSI MS-7A40                         | 1        | 0.72%   |
| MSI MS-7885                         | 1        | 0.72%   |
| MSI MS-7846                         | 1        | 0.72%   |
| MSI MS-7693                         | 1        | 0.72%   |
| MSI MS-7522                         | 1        | 0.72%   |
| MSI MS-7388                         | 1        | 0.72%   |
| MSI MS-7250                         | 1        | 0.72%   |
| Lenovo ThinkCentre M93p 10AAS0GN00  | 1        | 0.72%   |
| Lenovo ThinkCentre M92p 2121D5U     | 1        | 0.72%   |
| Lenovo ThinkCentre M83 10AHS0EW00   | 1        | 0.72%   |
| Lenovo ThinkCentre M58e 7268A9U     | 1        | 0.72%   |
| Lenovo SHARKBAY 0B98401 WIN         | 1        | 0.72%   |
| Intel X79 V2.81A                    | 1        | 0.72%   |
| Intel CRESCENTBAY                   | 1        | 0.72%   |
| IBM 8173KUB                         | 1        | 0.72%   |
| HP Z800 Workstation                 | 1        | 0.72%   |
| HP Z420 Workstation                 | 1        | 0.72%   |
| HP t620 PLUS Quad Core TC           | 1        | 0.72%   |
| HP ProLiant ML150 G6                | 1        | 0.72%   |
| HP ProDesk 600 G3 SFF               | 1        | 0.72%   |
| HP ProDesk 600 G2 SFF               | 1        | 0.72%   |
| HP ProDesk 600 G2 MT                | 1        | 0.72%   |
| HP ProDesk 600 G1 SFF               | 1        | 0.72%   |
| HP Pavilion Gaming Desktop 690-00xx | 1        | 0.72%   |
| HP Compaq Elite 8300 SFF            | 1        | 0.72%   |
| HP Compaq dc7900 Small Form Factor  | 1        | 0.72%   |
| HP Compaq 8200 Elite SFF PC         | 1        | 0.72%   |
| HP 500-409                          | 1        | 0.72%   |
| HARDKERNEL ODROID-H2                | 1        | 0.72%   |
| Gigabyte Z97X-SLI                   | 1        | 0.72%   |
| Gigabyte Z77X-UP5 TH-CF             | 1        | 0.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Dell OptiPlex                | 11       | 7.97%   |
| Unknown                      | 9        | 6.52%   |
| Lenovo ThinkCentre           | 6        | 4.35%   |
| Intel Q3XXG4-P               | 5        | 3.62%   |
| Protectli FW4B               | 4        | 2.9%    |
| HP ProDesk                   | 4        | 2.9%    |
| ASUS PRIME                   | 4        | 2.9%    |
| Intel NDISB533               | 3        | 2.17%   |
| HP Compaq                    | 3        | 2.17%   |
| Dell G5                      | 3        | 2.17%   |
| ASUS All                     | 3        | 2.17%   |
| Acer Aspire                  | 3        | 2.17%   |
| Supermicro X8STi             | 2        | 1.45%   |
| Protectli FW6                | 2        | 1.45%   |
| PC Engines apu4              | 2        | 1.45%   |
| PC Engines apu2              | 2        | 1.45%   |
| HP Z440                      | 2        | 1.45%   |
| HP EliteDesk                 | 2        | 1.45%   |
| Dell Precision               | 2        | 1.45%   |
| ASUS ROG                     | 2        | 1.45%   |
| ASRock H110M-DGS             | 2        | 1.45%   |
| ASRock B450M                 | 2        | 1.45%   |
| Supermicro X7SPA-HF          | 1        | 0.72%   |
| Supermicro X7SLA             | 1        | 0.72%   |
| Supermicro SYS-E300-9A       | 1        | 0.72%   |
| Supermicro SYS-5019S-ML      | 1        | 0.72%   |
| Supermicro SYS-5019D-FN8TP   | 1        | 0.72%   |
| Supermicro SYS-5019A-FTN4    | 1        | 0.72%   |
| Shuttle DH110                | 1        | 0.72%   |
| SeeedStudio ODYSSEY-X86J4105 | 1        | 0.72%   |
| Quanta 120-1135              | 1        | 0.72%   |
| Protectli FW6E               | 1        | 0.72%   |
| PC Engines APU               | 1        | 0.72%   |
| MSI MS-7B79                  | 1        | 0.72%   |
| MSI MS-7A40                  | 1        | 0.72%   |
| MSI MS-7885                  | 1        | 0.72%   |
| MSI MS-7846                  | 1        | 0.72%   |
| MSI MS-7693                  | 1        | 0.72%   |
| MSI MS-7522                  | 1        | 0.72%   |
| MSI MS-7388                  | 1        | 0.72%   |
| MSI MS-7250                  | 1        | 0.72%   |
| Lenovo SHARKBAY              | 1        | 0.72%   |
| Intel X79                    | 1        | 0.72%   |
| Intel CRESCENTBAY            | 1        | 0.72%   |
| IBM 8173KUB                  | 1        | 0.72%   |
| HP Z800                      | 1        | 0.72%   |
| HP Z420                      | 1        | 0.72%   |
| HP t620                      | 1        | 0.72%   |
| HP ProLiant                  | 1        | 0.72%   |
| HP Pavilion                  | 1        | 0.72%   |
| HP 500-409                   | 1        | 0.72%   |
| HARDKERNEL ODROID-H2         | 1        | 0.72%   |
| Gigabyte Z97X-SLI            | 1        | 0.72%   |
| Gigabyte Z77X-UP5            | 1        | 0.72%   |
| Gigabyte X470                | 1        | 0.72%   |
| Gigabyte H97-D3H             | 1        | 0.72%   |
| Gigabyte H61N-USB3           | 1        | 0.72%   |
| Gigabyte F2A68HM-H           | 1        | 0.72%   |
| Gigabyte D525TUD             | 1        | 0.72%   |
| Gigabyte BSRE-1605           | 1        | 0.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 30       | 21.74%  |
| 2020    | 19       | 13.77%  |
| 2014    | 18       | 13.04%  |
| 2016    | 12       | 8.7%    |
| 2013    | 9        | 6.52%   |
| 2015    | 7        | 5.07%   |
| 2010    | 7        | 5.07%   |
| 2019    | 6        | 4.35%   |
| 2017    | 5        | 3.62%   |
| 2011    | 5        | 3.62%   |
| 2009    | 5        | 3.62%   |
| 2021    | 4        | 2.9%    |
| 2022    | 3        | 2.17%   |
| 2012    | 3        | 2.17%   |
| 2008    | 3        | 2.17%   |
| 2006    | 1        | 0.72%   |
| Unknown | 1        | 0.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 138      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 131      | 94.93%  |
| Yes  | 7        | 5.07%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 49       | 35%     |
| 16.01-24.0  | 31       | 22.14%  |
| 4.01-8.0    | 25       | 17.86%  |
| 32.01-64.0  | 17       | 12.14%  |
| 64.01-256.0 | 6        | 4.29%   |
| 2.01-3.0    | 5        | 3.57%   |
| 24.01-32.0  | 4        | 2.86%   |
| 3.01-4.0    | 1        | 0.71%   |
| 1.01-2.0    | 1        | 0.71%   |
| 0.51-1.0    | 1        | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.01-0.5    | 65       | 45.77%  |
| 0.51-1.0    | 43       | 30.28%  |
| 1.01-2.0    | 20       | 14.08%  |
| 3.01-4.0    | 4        | 2.82%   |
| 4.01-8.0    | 3        | 2.11%   |
| 2.01-3.0    | 3        | 2.11%   |
| 32.01-64.0  | 1        | 0.7%    |
| 64.01-256.0 | 1        | 0.7%    |
| 8.01-16.0   | 1        | 0.7%    |
| 0           | 1        | 0.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 93       | 66.43%  |
| 2      | 23       | 16.43%  |
| 0      | 8        | 5.71%   |
| 3      | 7        | 5%      |
| 4      | 5        | 3.57%   |
| 13     | 1        | 0.71%   |
| 10     | 1        | 0.71%   |
| 7      | 1        | 0.71%   |
| 5      | 1        | 0.71%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 109      | 77.3%   |
| Yes       | 32       | 22.7%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 137      | 99.28%  |
| No        | 1        | 0.72%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 112      | 80.58%  |
| Yes       | 27       | 19.42%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 121      | 87.68%  |
| Yes       | 17       | 12.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Canada  | 138      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                       | Desktops | Percent |
|----------------------------|----------|---------|
| Toronto                    | 11       | 7.53%   |
| Ottawa                     | 10       | 6.85%   |
| Montreal                   | 10       | 6.85%   |
| Edmonton                   | 7        | 4.79%   |
| Victoria                   | 6        | 4.11%   |
| Kitchener                  | 6        | 4.11%   |
| Calgary                    | 6        | 4.11%   |
| Winnipeg                   | 5        | 3.42%   |
| Surrey                     | 4        | 2.74%   |
| Windsor                    | 3        | 2.05%   |
| St. Albert                 | 3        | 2.05%   |
| Regina                     | 3        | 2.05%   |
| Moncton                    | 3        | 2.05%   |
| Brampton                   | 3        | 2.05%   |
| Vancouver                  | 2        | 1.37%   |
| Terrebonne                 | 2        | 1.37%   |
| Sarnia                     | 2        | 1.37%   |
| Sainte-Julie               | 2        | 1.37%   |
| Saint-Bruno-de-Montarville | 2        | 1.37%   |
| Oakville                   | 2        | 1.37%   |
| Nanaimo                    | 2        | 1.37%   |
| London                     | 2        | 1.37%   |
| Laval                      | 2        | 1.37%   |
| Hamilton                   | 2        | 1.37%   |
| Guelph                     | 2        | 1.37%   |
| Greater Sudbury            | 2        | 1.37%   |
| Burlington                 | 2        | 1.37%   |
| West Kelowna               | 1        | 0.68%   |
| Vaughan                    | 1        | 0.68%   |
| Tobique First Nation       | 1        | 0.68%   |
| St. John's                 | 1        | 0.68%   |
| St. Catharines             | 1        | 0.68%   |
| Smiths Falls               | 1        | 0.68%   |
| Sherwood Park              | 1        | 0.68%   |
| Scarborough                | 1        | 0.68%   |
| Saskatoon                  | 1        | 0.68%   |
| Saint-Colomban             | 1        | 0.68%   |
| Richmond                   | 1        | 0.68%   |
| Renfrew                    | 1        | 0.68%   |
| QuГ©bec                  | 1        | 0.68%   |
| Québec                    | 1        | 0.68%   |
| QuÃ©bec                  | 1        | 0.68%   |
| Pont-Rouge                 | 1        | 0.68%   |
| Pierrefonds                | 1        | 0.68%   |
| Peterborough               | 1        | 0.68%   |
| North Vancouver            | 1        | 0.68%   |
| New-Richmond               | 1        | 0.68%   |
| Mississauga                | 1        | 0.68%   |
| Maple Ridge                | 1        | 0.68%   |
| Lamont                     | 1        | 0.68%   |
| La Prairie                 | 1        | 0.68%   |
| Kingston                   | 1        | 0.68%   |
| Kanata                     | 1        | 0.68%   |
| Glace Bay                  | 1        | 0.68%   |
| Gatineau                   | 1        | 0.68%   |
| East Gwillimbury           | 1        | 0.68%   |
| Drummondville              | 1        | 0.68%   |
| Dieppe                     | 1        | 0.68%   |
| Dartmouth                  | 1        | 0.68%   |
| Cornwall                   | 1        | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 29       | 62     | 16.96%  |
| Samsung Electronics | 27       | 35     | 15.79%  |
| Seagate             | 26       | 51     | 15.2%   |
| Kingston            | 19       | 24     | 11.11%  |
| Crucial             | 7        | 8      | 4.09%   |
| Toshiba             | 6        | 10     | 3.51%   |
| Intel               | 6        | 7      | 3.51%   |
| A-DATA Technology   | 6        | 11     | 3.51%   |
| SanDisk             | 5        | 6      | 2.92%   |
| Dogfish             | 4        | 6      | 2.34%   |
| Micron Technology   | 3        | 6      | 1.75%   |
| BIWIN               | 3        | 3      | 1.75%   |
| VisionTek           | 2        | 6      | 1.17%   |
| SPCC                | 2        | 2      | 1.17%   |
| SK Hynix            | 2        | 4      | 1.17%   |
| PNY                 | 2        | 3      | 1.17%   |
| OCZ                 | 2        | 2      | 1.17%   |
| Mushkin             | 2        | 2      | 1.17%   |
| Hoodisk             | 2        | 3      | 1.17%   |
| Hitachi             | 2        | 2      | 1.17%   |
| HGST                | 2        | 3      | 1.17%   |
| Hewlett-Packard     | 2        | 2      | 1.17%   |
| Transcend           | 1        | 2      | 0.58%   |
| SATADOM             | 1        | 2      | 0.58%   |
| Protectli           | 1        | 1      | 0.58%   |
| Phison              | 1        | 1      | 0.58%   |
| NVMe                | 1        | 1      | 0.58%   |
| HPE                 | 1        | 4      | 0.58%   |
| EAGET               | 1        | 1      | 0.58%   |
| Corsair             | 1        | 3      | 0.58%   |
| China               | 1        | 1      | 0.58%   |
| AVEXIR              | 1        | 2      | 0.58%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB             | 6        | 3.24%   |
| Seagate ST1000DM010-2EP102 1TB          | 5        | 2.7%    |
| Kingston SA400S37120G 120GB             | 5        | 2.7%    |
| Samsung SSD 850 EVO 250GB               | 4        | 2.16%   |
| WDC WD20EZRX-00DC0B0 2TB                | 3        | 1.62%   |
| Toshiba DT01ACA100 1TB                  | 3        | 1.62%   |
| Samsung SSD 860 EVO 500GB               | 3        | 1.62%   |
| BIWIN SSD 128GB                         | 3        | 1.62%   |
| WDC WD40EFRX-68WT0N0 4TB                | 2        | 1.08%   |
| WDC WD10EZEX-22MFCA0 1TB                | 2        | 1.08%   |
| WDC WD10EZEX-08WN4A0 1TB                | 2        | 1.08%   |
| WDC PC SN520 NVMe 256GB                 | 2        | 1.08%   |
| VisionTek mSATA 120GB                   | 2        | 1.08%   |
| Seagate ST500DM002-1BD142 500GB         | 2        | 1.08%   |
| Seagate ST3500413AS 500GB               | 2        | 1.08%   |
| Seagate ST2000DM008-2FR102 2TB          | 2        | 1.08%   |
| SanDisk SD6SB1M064G1022I 64GB           | 2        | 1.08%   |
| Samsung SSD 840 EVO 120GB               | 2        | 1.08%   |
| PNY CS1311 120GB SSD                    | 2        | 1.08%   |
| Mushkin MKNSSDEC60GB 64GB               | 2        | 1.08%   |
| Kingston SUV500MS120G 120GB             | 2        | 1.08%   |
| Crucial CT240BX500SSD1 240GB            | 2        | 1.08%   |
| A-DATA SU650 120GB                      | 2        | 1.08%   |
| WDC WDS500G2B0B-00YS70 500GB            | 1        | 0.54%   |
| WDC WDS500G2B0A-00SM50 500GB            | 1        | 0.54%   |
| WDC WDS250G3X0C-00SJG0 250GB            | 1        | 0.54%   |
| WDC WDS250G2B0A 250GB                   | 1        | 0.54%   |
| WDC WDS120G2G0A-00JH30 120GB            | 1        | 0.54%   |
| WDC WDS100T2B0A-00SM50 1TB              | 1        | 0.54%   |
| WDC WD6003FZBX-00K5WB0 6TB              | 1        | 0.54%   |
| WDC WD50EFRX-68L0BN1 5TB                | 1        | 0.54%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1        | 0.54%   |
| WDC WD5000AAKX-75U6AA0 500GB            | 1        | 0.54%   |
| WDC WD5000AAKX-00ERMA0 500GB            | 1        | 0.54%   |
| WDC WD5000AAKS-75A7B0 500GB             | 1        | 0.54%   |
| WDC WD40EFRX-68N32N0 4TB                | 1        | 0.54%   |
| WDC WD30EZRX-22D8PB0 3TB                | 1        | 0.54%   |
| WDC WD30EFRX-68EUZN0 3TB                | 1        | 0.54%   |
| WDC WD30EFRX-68AX9N0 3TB                | 1        | 0.54%   |
| WDC WD2500KS-00MJB0 250GB               | 1        | 0.54%   |
| WDC WD2500AAKX-001CA0 250GB             | 1        | 0.54%   |
| WDC WD20EFRX-68AX9N0 2TB                | 1        | 0.54%   |
| WDC WD2003FZEX-00Z4SA0 2TB              | 1        | 0.54%   |
| WDC WD181KFGX-68AFPN0 18TB              | 1        | 0.54%   |
| WDC WD10SPZX-00Z10T0 1TB                | 1        | 0.54%   |
| WDC WD10EZEX-07WN4A0 1TB                | 1        | 0.54%   |
| WDC WD10EFRX-68FYTN0 1TB                | 1        | 0.54%   |
| WDC WD102KRYZ-01A5AB0 10TB              | 1        | 0.54%   |
| WDC WD1003FBYX-01Y7B0 1TB               | 1        | 0.54%   |
| WDC AC31600H 2GB                        | 1        | 0.54%   |
| Transcend TS256GMSA230S 256GB           | 1        | 0.54%   |
| Toshiba THNSN5256GPUK NVMe 256GB        | 1        | 0.54%   |
| Toshiba MQ01ACF050 500GB                | 1        | 0.54%   |
| Toshiba MQ01ABD075 752GB                | 1        | 0.54%   |
| SPCC Solid State Disk 64GB              | 1        | 0.54%   |
| SPCC Solid State Disk 128GB             | 1        | 0.54%   |
| SK Hynix PC401 NVMe 256GB               | 1        | 0.54%   |
| SK Hynix BC501 HFM128GDJTNG-8310A 128GB | 1        | 0.54%   |
| Seagate ST980811AS 80GB                 | 1        | 0.54%   |
| Seagate ST6000NM0074 6TB                | 1        | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 26       | 51     | 45.61%  |
| WDC     | 22       | 51     | 38.6%   |
| Toshiba | 5        | 7      | 8.77%   |
| Hitachi | 2        | 2      | 3.51%   |
| HGST    | 2        | 3      | 3.51%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 23       | 29     | 22.77%  |
| Kingston            | 19       | 23     | 18.81%  |
| Intel               | 6        | 7      | 5.94%   |
| Crucial             | 6        | 7      | 5.94%   |
| A-DATA Technology   | 6        | 11     | 5.94%   |
| WDC                 | 5        | 7      | 4.95%   |
| SanDisk             | 5        | 6      | 4.95%   |
| Dogfish             | 4        | 6      | 3.96%   |
| Micron Technology   | 3        | 6      | 2.97%   |
| BIWIN               | 3        | 3      | 2.97%   |
| VisionTek           | 2        | 6      | 1.98%   |
| SPCC                | 2        | 2      | 1.98%   |
| PNY                 | 2        | 3      | 1.98%   |
| OCZ                 | 2        | 2      | 1.98%   |
| Mushkin             | 2        | 2      | 1.98%   |
| Hoodisk             | 2        | 3      | 1.98%   |
| Transcend           | 1        | 2      | 0.99%   |
| SATADOM             | 1        | 2      | 0.99%   |
| Protectli           | 1        | 1      | 0.99%   |
| Phison              | 1        | 1      | 0.99%   |
| HPE                 | 1        | 4      | 0.99%   |
| EAGET               | 1        | 1      | 0.99%   |
| Corsair             | 1        | 3      | 0.99%   |
| China               | 1        | 1      | 0.99%   |
| AVEXIR              | 1        | 2      | 0.99%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 93       | 140    | 60.78%  |
| HDD  | 47       | 114    | 30.72%  |
| NVMe | 13       | 22     | 8.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 125      | 254    | 90.58%  |
| NVMe | 13       | 22     | 9.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 104      | 155    | 69.8%   |
| 0.51-1.0   | 23       | 37     | 15.44%  |
| 1.01-2.0   | 9        | 18     | 6.04%   |
| 3.01-4.0   | 5        | 15     | 3.36%   |
| 4.01-10.0  | 4        | 22     | 2.68%   |
| 2.01-3.0   | 3        | 6      | 2.01%   |
| 10.01-20.0 | 1        | 1      | 0.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 56       | 39.16%  |
| 251-500        | 20       | 13.99%  |
| 1-20           | 20       | 13.99%  |
| 51-100         | 19       | 13.29%  |
| 21-50          | 14       | 9.79%   |
| 501-1000       | 7        | 4.9%    |
| 1001-2000      | 4        | 2.8%    |
| Unknown        | 2        | 1.4%    |
| More than 3000 | 1        | 0.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 128      | 88.28%  |
| 21-50    | 13       | 8.97%   |
| Unknown  | 2        | 1.38%   |
| 501-1000 | 1        | 0.69%   |
| 51-100   | 1        | 0.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Desktops | Drives | Percent |
|--------------------------------------------|----------|--------|---------|
| VisionTek mSATA 120GB                      | 2        | 6      | 8%      |
| Seagate ST500DM002-1BD142 500GB            | 2        | 4      | 8%      |
| Seagate ST3500413AS 500GB                  | 2        | 4      | 8%      |
| WDC WD50EFRX-68L0BN1 5TB                   | 1        | 1      | 4%      |
| WDC WD40EFRX-68WT0N0 4TB                   | 1        | 2      | 4%      |
| WDC WD30EZRX-22D8PB0 3TB                   | 1        | 1      | 4%      |
| WDC WD2500AAKX-001CA0 250GB                | 1        | 1      | 4%      |
| Toshiba MQ01ABD075 752GB                   | 1        | 1      | 4%      |
| Toshiba DT01ACA100 1TB                     | 1        | 3      | 4%      |
| Seagate ST500LM021-1KJ152 500GB            | 1        | 1      | 4%      |
| Seagate ST3250318AS 250GB                  | 1        | 1      | 4%      |
| Seagate ST3200822AS 200GB                  | 1        | 1      | 4%      |
| Seagate ST3160815AS 160GB                  | 1        | 1      | 4%      |
| Seagate ST31500341AS 1.5TB                 | 1        | 2      | 4%      |
| Seagate ST3120026A 120GB                   | 1        | 1      | 4%      |
| Seagate ST31000520AS 1TB                   | 1        | 1      | 4%      |
| Seagate ST1000DM003-1CH162 1TB             | 1        | 1      | 4%      |
| Micron Technology M500_MTFDDAK960MAV 960GB | 1        | 4      | 4%      |
| Intel SSDSA2M080G2GC 80GB                  | 1        | 1      | 4%      |
| Hitachi HDT721010SLA360 1TB                | 1        | 1      | 4%      |
| HGST HTS541010A9E680 1TB                   | 1        | 1      | 4%      |
| Crucial CT240M500SSD1 240GB                | 1        | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| Seagate           | 11       | 17     | 45.83%  |
| WDC               | 4        | 5      | 16.67%  |
| VisionTek         | 2        | 6      | 8.33%   |
| Toshiba           | 2        | 4      | 8.33%   |
| Micron Technology | 1        | 4      | 4.17%   |
| Intel             | 1        | 1      | 4.17%   |
| Hitachi           | 1        | 1      | 4.17%   |
| HGST              | 1        | 1      | 4.17%   |
| Crucial           | 1        | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 11       | 17     | 57.89%  |
| WDC     | 4        | 5      | 21.05%  |
| Toshiba | 2        | 4      | 10.53%  |
| Hitachi | 1        | 1      | 5.26%   |
| HGST    | 1        | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 18       | 28     | 78.26%  |
| SSD  | 5        | 12     | 21.74%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| WDC WD10SPZX-00Z10T0 1TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 115      | 231    | 80.99%  |
| Malfunc  | 22       | 40     | 15.49%  |
| Detected | 4        | 4      | 2.82%   |
| Failed   | 1        | 1      | 0.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 111      | 67.27%  |
| AMD                         | 24       | 14.55%  |
| Sandisk                     | 4        | 2.42%   |
| Samsung Electronics         | 4        | 2.42%   |
| ASMedia Technology          | 4        | 2.42%   |
| Nvidia                      | 3        | 1.82%   |
| SK Hynix                    | 2        | 1.21%   |
| Silicon Motion              | 2        | 1.21%   |
| Silicon Image               | 2        | 1.21%   |
| JMicron Technology          | 2        | 1.21%   |
| Broadcom / LSI              | 2        | 1.21%   |
| Toshiba                     | 1        | 0.61%   |
| Micron/Crucial Technology   | 1        | 0.61%   |
| Marvell Technology Group    | 1        | 0.61%   |
| Kingston Technology Company | 1        | 0.61%   |
| Chelsio Communications      | 1        | 0.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 18       | 9.23%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 11       | 5.64%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 9        | 4.62%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 8        | 4.1%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 6        | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 6        | 3.08%   |
| AMD 400 Series Chipset SATA Controller                                           | 6        | 3.08%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5        | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 5        | 2.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4        | 2.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4        | 2.05%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4        | 2.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4        | 2.05%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 4        | 2.05%   |
| Sandisk PC SN520 NVMe SSD                                                        | 3        | 1.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3        | 1.54%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3        | 1.54%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3        | 1.54%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 3        | 1.54%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 3        | 1.54%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3        | 1.54%   |
| AMD FCH SATA Controller [IDE mode]                                               | 3        | 1.54%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 2        | 1.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2        | 1.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2        | 1.03%   |
| JMicron JMB363 SATA/IDE Controller                                               | 2        | 1.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2        | 1.03%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2        | 1.03%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2        | 1.03%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 2        | 1.03%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2        | 1.03%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2        | 1.03%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 2        | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]      | 2        | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]      | 2        | 1.03%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2        | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 2        | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2        | 1.03%   |
| Toshiba XG4 NVMe SSD Controller                                                  | 1        | 0.51%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 1        | 0.51%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1        | 0.51%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1        | 0.51%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1        | 0.51%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1        | 0.51%   |
| Nvidia MCP73 IDE Controller                                                      | 1        | 0.51%   |
| Nvidia MCP55 IDE                                                                 | 1        | 0.51%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1        | 0.51%   |
| Nvidia MCP51 IDE                                                                 | 1        | 0.51%   |
| Nvidia GeForce 7100/nForce 630i SATA                                             | 1        | 0.51%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1        | 0.51%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 1        | 0.51%   |
| Kingston Company A2000 NVMe SSD                                                  | 1        | 0.51%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1        | 0.51%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1        | 0.51%   |
| Intel SATA Controller [RAID mode]                                                | 1        | 0.51%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1        | 0.51%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 1        | 0.51%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 1        | 0.51%   |
| Intel C610/X99 series chipset sSATA Controller [IDE mode]                        | 1        | 0.51%   |
| Intel C610/X99 series chipset 4-port SATA Controller [IDE mode]                  | 1        | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 117      | 71.34%  |
| IDE  | 24       | 14.63%  |
| NVMe | 13       | 7.93%   |
| RAID | 6        | 3.66%   |
| SAS  | 2        | 1.22%   |
| SCSI | 2        | 1.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 113      | 81.29%  |
| AMD    | 26       | 18.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Intel Core i5-4570 CPU @ 3.20GHz                       | 5        | 3.6%    |
| Intel Core i5-3570 CPU @ 3.40GHz                       | 4        | 2.88%   |
| Intel Celeron CPU J3160 @ 1.60GHz                      | 4        | 2.88%   |
| AMD GX-412TC SOC                                       | 4        | 2.88%   |
| Intel Core i7-9700K CPU @ 3.60GHz                      | 3        | 2.16%   |
| Intel Core i7-3770 CPU @ 3.40GHz                       | 3        | 2.16%   |
| Intel Core i5-6500 CPU @ 3.20GHz                       | 3        | 2.16%   |
| Intel Core i5-4570TE CPU @ 2.70GHz                     | 3        | 2.16%   |
| Intel Pentium CPU G4560 @ 3.50GHz                      | 2        | 1.44%   |
| Intel Core i7-7700 CPU @ 3.60GHz                       | 2        | 1.44%   |
| Intel Core i7-4790K CPU @ 4.00GHz                      | 2        | 1.44%   |
| Intel Core i5-8400 CPU @ 2.80GHz                       | 2        | 1.44%   |
| Intel Core i5-7200U CPU @ 2.50GHz                      | 2        | 1.44%   |
| Intel Core i5-4590 CPU @ 3.30GHz                       | 2        | 1.44%   |
| Intel Core i5-4460 CPU @ 3.20GHz                       | 2        | 1.44%   |
| Intel Core i5-3470T CPU @ 2.90GHz                      | 2        | 1.44%   |
| Intel Core i3-4030U CPU @ 1.90GHz                      | 2        | 1.44%   |
| Intel Celeron J4125 CPU @ 2.00GHz                      | 2        | 1.44%   |
| Intel Celeron J4105 CPU @ 1.50GHz                      | 2        | 1.44%   |
| Intel Celeron CPU J3455 @ 1.50GHz                      | 2        | 1.44%   |
| AMD FX-8350 Eight-Core Processor                       | 2        | 1.44%   |
| AMD FX-8320E Eight-Core Processor                      | 2        | 1.44%   |
| Intel Xeon D-2146NT CPU @ 2.30GHz                      | 1        | 0.72%   |
| Intel Xeon CPU X5660 @ 2.80GHz                         | 1        | 0.72%   |
| Intel Xeon CPU W3530 @ 2.80GHz                         | 1        | 0.72%   |
| Intel Xeon CPU L5640 @ 2.27GHz                         | 1        | 0.72%   |
| Intel Xeon CPU E5506 @ 2.13GHz                         | 1        | 0.72%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz                    | 1        | 0.72%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz                    | 1        | 0.72%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz                    | 1        | 0.72%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz                    | 1        | 0.72%   |
| Intel Xeon CPU E5-1603 @ 2.80GHz                       | 1        | 0.72%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz                    | 1        | 0.72%   |
| Intel Xeon CPU E3-1240L v5 @ 2.10GHz                   | 1        | 0.72%   |
| Intel Xeon CPU D-1541 @ 2.10GHz                        | 1        | 0.72%   |
| Intel Xeon                                             | 1        | 0.72%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz            | 1        | 0.72%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz            | 1        | 0.72%   |
| Intel Pentium CPU G3258 @ 3.20GHz                      | 1        | 0.72%   |
| Intel Pentium CPU G3220 @ 3.00GHz                      | 1        | 0.72%   |
| Intel Pentium 4 CPU 3.20GHz ("GenuineIntel" 686-class) | 1        | 0.72%   |
| Intel Core i7-8550U CPU @ 1.80GHz                      | 1        | 0.72%   |
| Intel Core i7-6700 CPU @ 3.40GHz                       | 1        | 0.72%   |
| Intel Core i7-5820K CPU @ 3.30GHz                      | 1        | 0.72%   |
| Intel Core i7-3770K CPU @ 3.50GHz                      | 1        | 0.72%   |
| Intel Core i7 CPU 930 @ 2.80GHz                        | 1        | 0.72%   |
| Intel Core i5-9400 CPU @ 2.90GHz                       | 1        | 0.72%   |
| Intel Core i5-7400 CPU @ 3.00GHz                       | 1        | 0.72%   |
| Intel Core i5-5300U CPU @ 2.30GHz                      | 1        | 0.72%   |
| Intel Core i5-5200U CPU @ 2.20GHz                      | 1        | 0.72%   |
| Intel Core i5-4570T CPU @ 2.90GHz                      | 1        | 0.72%   |
| Intel Core i5-4570S CPU @ 2.90GHz                      | 1        | 0.72%   |
| Intel Core i5-3475S CPU @ 2.90GHz                      | 1        | 0.72%   |
| Intel Core i5-3470 CPU @ 3.20GHz                       | 1        | 0.72%   |
| Intel Core i5-2500 CPU @ 3.30GHz                       | 1        | 0.72%   |
| Intel Core i5-2405S CPU @ 2.50GHz                      | 1        | 0.72%   |
| Intel Core i5-10500T CPU @ 2.30GHz                     | 1        | 0.72%   |
| Intel Core i5-10400 CPU @ 2.90GHz                      | 1        | 0.72%   |
| Intel Core i3-9100F CPU @ 3.60GHz                      | 1        | 0.72%   |
| Intel Core i3-7300 CPU @ 4.00GHz                       | 1        | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 37       | 26.62%  |
| Intel Core i7           | 15       | 10.79%  |
| Intel Xeon              | 14       | 10.07%  |
| Intel Celeron           | 14       | 10.07%  |
| Intel Core i3           | 13       | 9.35%   |
| Intel Atom              | 7        | 5.04%   |
| AMD GX                  | 5        | 3.6%    |
| AMD FX                  | 5        | 3.6%    |
| Intel Pentium           | 4        | 2.88%   |
| AMD Ryzen 5             | 3        | 2.16%   |
| Other                   | 2        | 1.44%   |
| Intel Pentium Dual-Core | 2        | 1.44%   |
| Intel Core 2 Quad       | 2        | 1.44%   |
| Intel Core 2 Duo        | 2        | 1.44%   |
| AMD Ryzen 7             | 2        | 1.44%   |
| AMD Athlon 64 X2        | 2        | 1.44%   |
| Intel Pentium 4         | 1        | 0.72%   |
| AMD Ryzen Embedded      | 1        | 0.72%   |
| AMD Ryzen 9             | 1        | 0.72%   |
| AMD Ryzen 5 PRO         | 1        | 0.72%   |
| AMD Ryzen 3             | 1        | 0.72%   |
| AMD Phenom II X6        | 1        | 0.72%   |
| AMD G                   | 1        | 0.72%   |
| AMD E                   | 1        | 0.72%   |
| AMD Athlon              | 1        | 0.72%   |
| AMD A6                  | 1        | 0.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 69       | 49.64%  |
| 2       | 36       | 25.9%   |
| 8       | 14       | 10.07%  |
| 6       | 10       | 7.19%   |
| 12      | 3        | 2.16%   |
| 16      | 2        | 1.44%   |
| Unknown | 2        | 1.44%   |
| 32      | 1        | 0.72%   |
| 11      | 1        | 0.72%   |
| 10      | 1        | 0.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 137      | 99.28%  |
| Unknown | 1        | 0.72%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 84       | 60.43%  |
| 2       | 53       | 38.13%  |
| Unknown | 2        | 1.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 29       | 20.86%  |
| KabyLake      | 16       | 11.51%  |
| IvyBridge     | 13       | 9.35%   |
| Skylake       | 7        | 5.04%   |
| Silvermont    | 7        | 5.04%   |
| Piledriver    | 6        | 4.32%   |
| Penryn        | 6        | 4.32%   |
| Goldmont      | 6        | 4.32%   |
| SandyBridge   | 5        | 3.6%    |
| Goldmont plus | 5        | 3.6%    |
| Zen+          | 4        | 2.88%   |
| Puma          | 4        | 2.88%   |
| CometLake     | 4        | 2.88%   |
| Zen           | 3        | 2.16%   |
| Nehalem       | 3        | 2.16%   |
| Broadwell     | 3        | 2.16%   |
| Bonnell       | 3        | 2.16%   |
| Westmere      | 2        | 1.44%   |
| K8 Hammer     | 2        | 1.44%   |
| Jaguar        | 2        | 1.44%   |
| Bobcat        | 2        | 1.44%   |
| Zen 3         | 1        | 0.72%   |
| Zen 2         | 1        | 0.72%   |
| TigerLake     | 1        | 0.72%   |
| NetBurst      | 1        | 0.72%   |
| K10           | 1        | 0.72%   |
| Core          | 1        | 0.72%   |
| Unknown       | 1        | 0.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 81       | 60.9%   |
| Nvidia                     | 25       | 18.8%   |
| AMD                        | 18       | 13.53%  |
| ASPEED Technology          | 5        | 3.76%   |
| Matrox Electronics Systems | 4        | 3.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 18       | 13.53%  |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5        | 3.76%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 5        | 3.76%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5        | 3.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5        | 3.76%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 5        | 3.76%   |
| Intel HD Graphics 630                                                                    | 4        | 3.01%   |
| Intel HD Graphics 530                                                                    | 4        | 3.01%   |
| Intel HD Graphics 500                                                                    | 4        | 3.01%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4        | 3.01%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4        | 3.01%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4        | 3.01%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 3        | 2.26%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 2        | 1.5%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 1.5%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 1.5%    |
| Nvidia GM107GL [Quadro K620]                                                             | 2        | 1.5%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 1.5%    |
| Intel HD Graphics 620                                                                    | 2        | 1.5%    |
| Intel HD Graphics 610                                                                    | 2        | 1.5%    |
| Intel HD Graphics 5500                                                                   | 2        | 1.5%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 1.5%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2        | 1.5%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 1.5%    |
| AMD RS780L [Radeon 3000]                                                                 | 2        | 1.5%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 1.5%    |
| AMD Park [Mobility Radeon HD 5430]                                                       | 2        | 1.5%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2        | 1.5%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1        | 0.75%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1        | 0.75%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 0.75%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 0.75%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                                        | 1        | 0.75%   |
| Nvidia GK106GL [Quadro K4000]                                                            | 1        | 0.75%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 0.75%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1        | 0.75%   |
| Nvidia GF119 [NVS 315]                                                                   | 1        | 0.75%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1        | 0.75%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 1        | 0.75%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 1        | 0.75%   |
| Nvidia G84GL [Quadro FX 1700]                                                            | 1        | 0.75%   |
| Nvidia G72 [GeForce 7500 LE]                                                             | 1        | 0.75%   |
| Nvidia C73 [GeForce 7100 / nForce 630i]                                                  | 1        | 0.75%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1        | 0.75%   |
| Intel UHD Graphics 620                                                                   | 1        | 0.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1        | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1        | 0.75%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1        | 0.75%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1        | 0.75%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1        | 0.75%   |
| Intel 82915G/GV/910GL Integrated Graphics Controller                                     | 1        | 0.75%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 1        | 0.75%   |
| AMD Trinity 2 [Radeon HD 7540D]                                                          | 1        | 0.75%   |
| AMD RV610 [Radeon HD 2400 PRO]                                                           | 1        | 0.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1        | 0.75%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1        | 0.75%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 1        | 0.75%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                                  | 1        | 0.75%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1        | 0.75%   |
| AMD Cezanne                                                                              | 1        | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 77       | 55.8%   |
| 1 x Nvidia     | 23       | 16.67%  |
| 1 x AMD        | 18       | 13.04%  |
| Other          | 7        | 5.07%   |
| 1 x ASPEED     | 5        | 3.62%   |
| 1 x Matrox     | 4        | 2.9%    |
| 2 x Intel      | 2        | 1.45%   |
| Intel + Nvidia | 2        | 1.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 117      | 84.17%  |
| Proprietary | 15       | 10.79%  |
| Unknown     | 7        | 5.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 117      | 84.17%  |
| 1.01-2.0   | 5        | 3.6%    |
| 0.51-1.0   | 5        | 3.6%    |
| 3.01-4.0   | 4        | 2.88%   |
| 7.01-8.0   | 3        | 2.16%   |
| 5.01-6.0   | 3        | 2.16%   |
| 2.01-3.0   | 1        | 0.72%   |
| 0.01-0.5   | 1        | 0.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 9        | 26.47%  |
| BenQ                 | 4        | 11.76%  |
| Samsung Electronics  | 3        | 8.82%   |
| Dell                 | 3        | 8.82%   |
| Sony                 | 2        | 5.88%   |
| Hewlett-Packard      | 2        | 5.88%   |
| Acer                 | 2        | 5.88%   |
| ViewSonic            | 1        | 2.94%   |
| Videoseven           | 1        | 2.94%   |
| LTV                  | 1        | 2.94%   |
| LG Electronics       | 1        | 2.94%   |
| Lenovo               | 1        | 2.94%   |
| Insignia             | 1        | 2.94%   |
| ASUSTek Computer     | 1        | 2.94%   |
| AOC                  | 1        | 2.94%   |
| Ancor Communications | 1        | 2.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Sony LCD Monitor TV XV 1920x1080                                       | 2        | 5.41%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 2        | 5.41%   |
| ViewSonic LCD Monitor VSCFA2B 1920x1080 510x290mm 23.1-inch            | 1        | 2.7%    |
| Videoseven WL19A IGM1908 1280x1024 380x300mm 19.1-inch                 | 1        | 2.7%    |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1210x680mm 54.6-inch | 1        | 2.7%    |
| LTV LTV1280M1A LTV0A3C 1024x768 800x450mm 36.1-inch                    | 1        | 2.7%    |
| LG Electronics LCD Monitor LG Ultra HD 7680x2160                       | 1        | 2.7%    |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1        | 2.7%    |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch               | 1        | 2.7%    |
| Insignia LCD Monitor BBY0050 1920x1080 700x400mm 31.7-inch             | 1        | 2.7%    |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch       | 1        | 2.7%    |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch             | 1        | 2.7%    |
| Goldstar W2442 GSM56D9 1920x1080 530x300mm 24.0-inch                   | 1        | 2.7%    |
| Goldstar W2052 GSM4E88 1680x1050 470x300mm 22.0-inch                   | 1        | 2.7%    |
| Goldstar MP59G GSM5B35 1920x1080 600x340mm 27.2-inch                   | 1        | 2.7%    |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                   | 1        | 2.7%    |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch            | 1        | 2.7%    |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch            | 1        | 2.7%    |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch               | 1        | 2.7%    |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 1        | 2.7%    |
| Goldstar LG FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch              | 1        | 2.7%    |
| Goldstar LCD Monitor GSM76F5 1920x1080 700x390mm 31.5-inch             | 1        | 2.7%    |
| Goldstar 27GL850 GSM5B7F 2560x1440 600x340mm 27.2-inch                 | 1        | 2.7%    |
| Dell P3222QE DEL4246 3840x2160 700x390mm 31.5-inch                     | 1        | 2.7%    |
| Dell P2311H DEL4067 1920x1080 510x290mm 23.1-inch                      | 1        | 2.7%    |
| Dell P2219H DELA114 1920x1080 480x270mm 21.7-inch                      | 1        | 2.7%    |
| BenQ XL2430T BNQ7F3D 1920x1080 530x300mm 24.0-inch                     | 1        | 2.7%    |
| BenQ GL2460 BNQ78CE 1920x1080 530x300mm 24.0-inch                      | 1        | 2.7%    |
| BenQ G900HD BNQ7816 1366x768 410x230mm 18.5-inch                       | 1        | 2.7%    |
| BenQ BL2780 BNQ802B 1920x1080 600x340mm 27.2-inch                      | 1        | 2.7%    |
| ASUSTek Computer VP228 AUS22A1 1920x1080 480x270mm 21.7-inch           | 1        | 2.7%    |
| AOC 24G2W1G4 AOC2402 1920x1080 530x300mm 24.0-inch                     | 1        | 2.7%    |
| Ancor Communications VX279 ACI27E4 1920x1080 600x340mm 27.2-inch       | 1        | 2.7%    |
| Acer SA240Y ACR057F 1920x1080 530x300mm 24.0-inch                      | 1        | 2.7%    |
| Acer AL1916W ACRAD52 1440x900 410x260mm 19.1-inch                      | 1        | 2.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 17       | 51.52%  |
| 3840x2160 (4K)     | 5        | 15.15%  |
| 7680x2160          | 1        | 3.03%   |
| 3440x1440          | 1        | 3.03%   |
| 2560x1440 (QHD)    | 1        | 3.03%   |
| 2560x1080          | 1        | 3.03%   |
| 1680x1050 (WSXGA+) | 1        | 3.03%   |
| 1600x900 (HD+)     | 1        | 3.03%   |
| 1440x900 (WXGA+)   | 1        | 3.03%   |
| 1366x768 (WXGA)    | 1        | 3.03%   |
| 1280x1024 (SXGA)   | 1        | 3.03%   |
| 1024x768 (XGA)     | 1        | 3.03%   |
| Unknown            | 1        | 3.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 7        | 20%     |
| 27      | 5        | 14.29%  |
| 21      | 5        | 14.29%  |
| 54      | 3        | 8.57%   |
| 19      | 3        | 8.57%   |
| Unknown | 3        | 8.57%   |
| 31      | 2        | 5.71%   |
| 23      | 2        | 5.71%   |
| 36      | 1        | 2.86%   |
| 34      | 1        | 2.86%   |
| 28      | 1        | 2.86%   |
| 22      | 1        | 2.86%   |
| 18      | 1        | 2.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 13       | 38.24%  |
| 401-500     | 9        | 26.47%  |
| 601-700     | 3        | 8.82%   |
| 1001-1500   | 3        | 8.82%   |
| Unknown     | 3        | 8.82%   |
| 701-800     | 2        | 5.88%   |
| 351-400     | 1        | 2.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 24       | 75%     |
| Unknown | 3        | 9.38%   |
| 21/9    | 2        | 6.25%   |
| 16/10   | 2        | 6.25%   |
| 5/4     | 1        | 3.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 14       | 41.18%  |
| 301-350        | 5        | 14.71%  |
| More than 1000 | 3        | 8.82%   |
| 351-500        | 3        | 8.82%   |
| 151-200        | 3        | 8.82%   |
| Unknown        | 3        | 8.82%   |
| 251-300        | 1        | 2.94%   |
| 141-150        | 1        | 2.94%   |
| 501-1000       | 1        | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 22       | 62.86%  |
| 101-120 | 7        | 20%     |
| Unknown | 3        | 8.57%   |
| 1-50    | 1        | 2.86%   |
| 161-240 | 1        | 2.86%   |
| 121-160 | 1        | 2.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 105      | 75%     |
| 1     | 28       | 20%     |
| 2     | 7        | 5%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 106      | 55.21%  |
| Realtek Semiconductor           | 59       | 30.73%  |
| Broadcom                        | 9        | 4.69%   |
| Qualcomm Atheros                | 7        | 3.65%   |
| Ralink                          | 2        | 1.04%   |
| Solarflare Communications       | 1        | 0.52%   |
| Qualcomm Atheros Communications | 1        | 0.52%   |
| MEDIATEK                        | 1        | 0.52%   |
| Marvell Technology Group        | 1        | 0.52%   |
| IMC Networks                    | 1        | 0.52%   |
| Google                          | 1        | 0.52%   |
| D-Link System                   | 1        | 0.52%   |
| Chelsio Communications          | 1        | 0.52%   |
| 3Com                            | 1        | 0.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 51       | 21.7%   |
| Intel I211 Gigabit Network Connection                                         | 20       | 8.51%   |
| Intel Ethernet Connection I217-LM                                             | 13       | 5.53%   |
| Intel 82574L Gigabit Network Connection                                       | 13       | 5.53%   |
| Intel I350 Gigabit Network Connection                                         | 10       | 4.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 8        | 3.4%    |
| Intel I210 Gigabit Network Connection                                         | 7        | 2.98%   |
| Intel 82580 Gigabit Network Connection                                        | 7        | 2.98%   |
| Intel Wi-Fi 6 AX200                                                           | 5        | 2.13%   |
| Intel 82583V Gigabit Network Connection                                       | 5        | 2.13%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 5        | 2.13%   |
| Realtek RTL8125 2.5GbE Controller                                             | 4        | 1.7%    |
| Intel 82576 Gigabit Network Connection                                        | 4        | 1.7%    |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 4        | 1.7%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3        | 1.28%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3        | 1.28%   |
| Intel Wireless 7260                                                           | 2        | 0.85%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 2        | 0.85%   |
| Intel Ethernet Connection I217-V                                              | 2        | 0.85%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 0.85%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 0.85%   |
| Intel Ethernet Connection (2) I218-LM                                         | 2        | 0.85%   |
| Intel 82575GB Gigabit Network Connection                                      | 2        | 0.85%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 2        | 0.85%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 2        | 0.85%   |
| Solarflare SFC9020 10G Ethernet Controller                                    | 1        | 0.43%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1        | 0.43%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.43%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 0.43%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1        | 0.43%   |
| Ralink RT5592 PCIe Wireless Network Adapter                                   | 1        | 0.43%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                          | 1        | 0.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1        | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.43%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 0.43%   |
| Qualcomm Atheros AR958x 802.11abgn Wireless Network Adapter                   | 1        | 0.43%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 0.43%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 0.43%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.43%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 1        | 0.43%   |
| MEDIATEK MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 1        | 0.43%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                       | 1        | 0.43%   |
| Intel Ethernet Controller X550                                                | 1        | 0.43%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.43%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1        | 0.43%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 1        | 0.43%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 1        | 0.43%   |
| Intel Ethernet Connection X553/X557-AT 10GBASE-T                              | 1        | 0.43%   |
| Intel Ethernet Connection X553 1GbE                                           | 1        | 0.43%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 1        | 0.43%   |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 1        | 0.43%   |
| Intel Ethernet Connection I354                                                | 1        | 0.43%   |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 0.43%   |
| Intel Ethernet Connection (5) I219-LM                                         | 1        | 0.43%   |
| Intel Ethernet Connection (11) I219-LM                                        | 1        | 0.43%   |
| Intel Centrino Wireless-N 105                                                 | 1        | 0.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 0.43%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 1        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 13       | 48.15%  |
| Qualcomm Atheros                | 5        | 18.52%  |
| Realtek Semiconductor           | 3        | 11.11%  |
| Ralink                          | 2        | 7.41%   |
| Qualcomm Atheros Communications | 1        | 3.7%    |
| MEDIATEK                        | 1        | 3.7%    |
| IMC Networks                    | 1        | 3.7%    |
| Broadcom                        | 1        | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 5        | 18.52%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3        | 11.11%  |
| Intel Wireless 7260                                                     | 2        | 7.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1        | 3.7%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 3.7%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1        | 3.7%    |
| Ralink RT5592 PCIe Wireless Network Adapter                             | 1        | 3.7%    |
| Ralink RT3062 Wireless 802.11n 2T/2R                                    | 1        | 3.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1        | 3.7%    |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 3.7%    |
| Qualcomm Atheros AR958x 802.11abgn Wireless Network Adapter             | 1        | 3.7%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1        | 3.7%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1        | 3.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 3.7%    |
| MEDIATEK MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1        | 3.7%    |
| Intel Centrino Wireless-N 105                                           | 1        | 3.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1        | 3.7%    |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 1        | 3.7%    |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 1        | 3.7%    |
| Broadcom BCM4321 802.11b/g/n                                            | 1        | 3.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 99       | 56.9%   |
| Realtek Semiconductor     | 59       | 33.91%  |
| Broadcom                  | 8        | 4.6%    |
| Qualcomm Atheros          | 2        | 1.15%   |
| Solarflare Communications | 1        | 0.57%   |
| Marvell Technology Group  | 1        | 0.57%   |
| Google                    | 1        | 0.57%   |
| D-Link System             | 1        | 0.57%   |
| Chelsio Communications    | 1        | 0.57%   |
| 3Com                      | 1        | 0.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 51       | 24.64%  |
| Intel I211 Gigabit Network Connection                                         | 20       | 9.66%   |
| Intel Ethernet Connection I217-LM                                             | 13       | 6.28%   |
| Intel 82574L Gigabit Network Connection                                       | 13       | 6.28%   |
| Intel I350 Gigabit Network Connection                                         | 10       | 4.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 8        | 3.86%   |
| Intel I210 Gigabit Network Connection                                         | 7        | 3.38%   |
| Intel 82580 Gigabit Network Connection                                        | 7        | 3.38%   |
| Intel 82583V Gigabit Network Connection                                       | 5        | 2.42%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 5        | 2.42%   |
| Realtek RTL8125 2.5GbE Controller                                             | 4        | 1.93%   |
| Intel 82576 Gigabit Network Connection                                        | 4        | 1.93%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 4        | 1.93%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3        | 1.45%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 1.45%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 2        | 0.97%   |
| Intel Ethernet Connection I217-V                                              | 2        | 0.97%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 0.97%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 0.97%   |
| Intel Ethernet Connection (2) I218-LM                                         | 2        | 0.97%   |
| Intel 82575GB Gigabit Network Connection                                      | 2        | 0.97%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 2        | 0.97%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 2        | 0.97%   |
| Solarflare SFC9020 10G Ethernet Controller                                    | 1        | 0.48%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.48%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1        | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.48%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.48%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                       | 1        | 0.48%   |
| Intel Ethernet Controller X550                                                | 1        | 0.48%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.48%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1        | 0.48%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 1        | 0.48%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 1        | 0.48%   |
| Intel Ethernet Connection X553/X557-AT 10GBASE-T                              | 1        | 0.48%   |
| Intel Ethernet Connection X553 1GbE                                           | 1        | 0.48%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 1        | 0.48%   |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 1        | 0.48%   |
| Intel Ethernet Connection I354                                                | 1        | 0.48%   |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 0.48%   |
| Intel Ethernet Connection (5) I219-LM                                         | 1        | 0.48%   |
| Intel Ethernet Connection (11) I219-LM                                        | 1        | 0.48%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 0.48%   |
| Intel 82599 10 Gigabit Network Connection                                     | 1        | 0.48%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 0.48%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 0.48%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.48%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1        | 0.48%   |
| Google Nexus/Pixel Device (charging + debug)                                  | 1        | 0.48%   |
| D-Link System RTL8139 Ethernet                                                | 1        | 0.48%   |
| Chelsio T420-CR Unified Wire Ethernet Controller                              | 1        | 0.48%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 0.48%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 1        | 0.48%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1        | 0.48%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 1        | 0.48%   |
| Broadcom NetXtreme BCM5705_2 Gigabit Ethernet                                 | 1        | 0.48%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                                 | 1        | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 137      | 83.03%  |
| WiFi     | 27       | 16.36%  |
| Unknown  | 1        | 0.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 135      | 95.74%  |
| WiFi     | 6        | 4.26%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 37       | 26.62%  |
| 1     | 28       | 20.14%  |
| 4     | 21       | 15.11%  |
| 3     | 19       | 13.67%  |
| 5     | 18       | 12.95%  |
| 6     | 8        | 5.76%   |
| 7     | 4        | 2.88%   |
| 8     | 2        | 1.44%   |
| 10    | 1        | 0.72%   |
| 0     | 1        | 0.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 124      | 87.32%  |
| Yes  | 18       | 12.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 11       | 64.71%  |
| Cambridge Silicon Radio | 3        | 17.65%  |
| Realtek Semiconductor   | 1        | 5.88%   |
| MediaTek                | 1        | 5.88%   |
| Foxconn / Hon Hai       | 1        | 5.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 5        | 29.41%  |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 17.65%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 17.65%  |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 5.88%   |
| MediaTek Wireless_Device                            | 1        | 5.88%   |
| Intel Bluetooth wireless interface                  | 1        | 5.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 5.88%   |
| Intel AX201 Bluetooth                               | 1        | 5.88%   |
| Foxconn / Hon Hai Bluetooth USB Module              | 1        | 5.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 80       | 59.26%  |
| Nvidia              | 24       | 17.78%  |
| AMD                 | 23       | 17.04%  |
| Logitech            | 2        | 1.48%   |
| C-Media Electronics | 2        | 1.48%   |
| Yamaha              | 1        | 0.74%   |
| Texas Instruments   | 1        | 0.74%   |
| SteelSeries ApS     | 1        | 0.74%   |
| Creative Labs       | 1        | 0.74%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                                                                                                                      | Desktops | Percent |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                                                                                                           | 17       | 10.24%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                                                                                                                        | 16       | 9.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                                                                                                                        | 7        | 4.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                                                                                                                 | 6        | 3.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                                                                                                            | 6        | 3.61%   |
| AMD SBx00 Azalia (Intel HDA)                                                                                                                                                               | 6        | 3.61%   |
| Intel Cannon Lake PCH cAVS                                                                                                                                                                 | 5        | 3.01%   |
| Intel Haswell-ULT HD Audio Controller                                                                                                                                                      | 4        | 2.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                                                                                                               | 4        | 2.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller                                                                                          | 4        | 2.41%   |
| Intel 8 Series HD Audio Controller                                                                                                                                                         | 4        | 2.41%   |
| Intel 200 Series PCH HD Audio                                                                                                                                                              | 4        | 2.41%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                                                                                                                        | 4        | 2.41%   |
| Nvidia High Definition Audio Controller                                                                                                                                                    | 3        | 1.81%   |
| Intel Comet Lake PCH-V cAVS                                                                                                                                                                | 3        | 1.81%   |
| Intel C610/X99 series chipset HD Audio Controller                                                                                                                                          | 3        | 1.81%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                                                                                                          | 3        | 1.81%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                                                                                                                        | 3        | 1.81%   |
| AMD FCH Azalia Controller                                                                                                                                                                  | 3        | 1.81%   |
| AMD Family 17h/19h HD Audio Controller                                                                                                                                                     | 3        | 1.81%   |
| Nvidia GP108 High Definition Audio Controller                                                                                                                                              | 2        | 1.2%    |
| Nvidia GP107GL High Definition Audio Controller                                                                                                                                            | 2        | 1.2%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                                                                                                              | 2        | 1.2%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                                                                                                                      | 2        | 1.2%    |
| Nvidia GK106 HDMI Audio Controller                                                                                                                                                         | 2        | 1.2%    |
| Nvidia GF119 HDMI Audio Controller                                                                                                                                                         | 2        | 1.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                                                                                                                    | 2        | 1.2%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                                                                                                          | 2        | 1.2%    |
| Intel C600/X79 series chipset High Definition Audio Controller                                                                                                                             | 2        | 1.2%    |
| Intel Broadwell-U Audio Controller                                                                                                                                                         | 2        | 1.2%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                                                                                                           | 2        | 1.2%    |
| AMD Navi 10 HDMI Audio                                                                                                                                                                     | 2        | 1.2%    |
| AMD Kabini HDMI/DP Audio                                                                                                                                                                   | 2        | 1.2%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                                                                                                                     | 2        | 1.2%    |
| Yamaha Steinberg UR22mkII                                                                                                                                                                  | 1        | 0.6%    |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                                                                                                          | 1        | 0.6%    |
| SteelSeries ApS Arctis Pro Wireless Arctis Pro Wireless Chat Arctis Pro Wireless Game Arctis Pro Wireless                                                                                  | 1        | 0.6%    |
| Nvidia TU116 High Definition Audio Controller                                                                                                                                              | 1        | 0.6%    |
| Nvidia TU104 HD Audio Controller                                                                                                                                                           | 1        | 0.6%    |
| Nvidia MCP73 High Definition Audio                                                                                                                                                         | 1        | 0.6%    |
| Nvidia MCP55 High Definition Audio                                                                                                                                                         | 1        | 0.6%    |
| Nvidia MCP51 AC97 Audio Controller                                                                                                                                                         | 1        | 0.6%    |
| Nvidia GP106 High Definition Audio Controller                                                                                                                                              | 1        | 0.6%    |
| Nvidia GM200 High Definition Audio                                                                                                                                                         | 1        | 0.6%    |
| Nvidia GK104 HDMI Audio Controller                                                                                                                                                         | 1        | 0.6%    |
| Nvidia GF108 High Definition Audio Controller                                                                                                                                              | 1        | 0.6%    |
| Logitech H600 [Wireless Headset]                                                                                                                                                           | 1        | 0.6%    |
| Logitech Blue Microphones Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone | 1        | 0.6%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                                                                                                                | 1        | 0.6%    |
| Intel Sunrise Point-LP HD Audio                                                                                                                                                            | 1        | 0.6%    |
| Intel Alder Lake-S HD Audio Controller                                                                                                                                                     | 1        | 0.6%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                                                                                                                        | 1        | 0.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                                                                                                             | 1        | 0.6%    |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                                                                                                         | 1        | 0.6%    |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                                                                                                              | 1        | 0.6%    |
| C-Media Electronics CM102-A+/102S+ Audio Controller                                                                                                                                        | 1        | 0.6%    |
| AMD Trinity HDMI Audio Controller                                                                                                                                                          | 1        | 0.6%    |
| AMD Starship/Matisse HD Audio Controller                                                                                                                                                   | 1        | 0.6%    |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                                                                                                                     | 1        | 0.6%    |
| AMD Renoir Radeon High Definition Audio Controller                                                                                                                                         | 1        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 23       | 15.23%  |
| Samsung Electronics | 22       | 14.57%  |
| SK Hynix            | 21       | 13.91%  |
| Unknown             | 20       | 13.25%  |
| Corsair             | 16       | 10.6%   |
| Crucial             | 12       | 7.95%   |
| G.Skill             | 9        | 5.96%   |
| Micron Technology   | 8        | 5.3%    |
| Apacer              | 4        | 2.65%   |
| Team                | 3        | 1.99%   |
| Patriot             | 3        | 1.99%   |
| Ramaxel Technology  | 2        | 1.32%   |
| A-DATA Technology   | 2        | 1.32%   |
| V-Color             | 1        | 0.66%   |
| Unknown (ABCD)      | 1        | 0.66%   |
| Toshiba             | 1        | 0.66%   |
| TIMETEC             | 1        | 0.66%   |
| Nanya Technology    | 1        | 0.66%   |
| Cors                | 1        | 0.66%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s        | 4        | 2.45%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 3        | 1.84%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 1600MT/s            | 3        | 1.84%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 3        | 1.84%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 2        | 1.23%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 2        | 1.23%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2        | 1.23%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s            | 2        | 1.23%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 2        | 1.23%   |
| SK Hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s           | 2        | 1.23%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s            | 2        | 1.23%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 2        | 1.23%   |
| G.Skill RAM F4-2666C19-8GNT 8GB DIMM DDR4 2666MT/s             | 2        | 1.23%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s            | 2        | 1.23%   |
| Corsair RAM CMV8GX3M1A1333C9 8GB DIMM DDR3 1333MT/s            | 2        | 1.23%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1333MT/s            | 2        | 1.23%   |
| Corsair RAM CML16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s          | 2        | 1.23%   |
| V-Color RAM VCOLOR-TD2G16C9-H8 2GB DIMM 1333MT/s               | 1        | 0.61%   |
| Unknown RAM Module 8GB DIMM DDR4 2666MT/s                      | 1        | 0.61%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s                      | 1        | 0.61%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 1        | 0.61%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                         | 1        | 0.61%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                      | 1        | 0.61%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 1        | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                     | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR 1066MT/s                       | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM 400MT/s                            | 1        | 0.61%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s                    | 1        | 0.61%   |
| Unknown RAM Module 1GB DIMM SDRAM 667MT/s                      | 1        | 0.61%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 1        | 0.61%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s                    | 1        | 0.61%   |
| Unknown RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                 | 1        | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 0.61%   |
| Toshiba RAM 9905678-024.A00G 4GB DIMM DDR4 2133MT/s            | 1        | 0.61%   |
| TIMETEC RAM SD4-2666 16GB SODIMM DDR4 2666MT/s                 | 1        | 0.61%   |
| Team RAM TEAMGROUP-UD4-2400 4GB DIMM DDR4 2400MT/s             | 1        | 0.61%   |
| SK Hynix RAM Module 8GB DIMM DDR4 2133MT/s                     | 1        | 0.61%   |
| SK Hynix RAM Module 4GB DIMM DDR4 2133MT/s                     | 1        | 0.61%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1333MT/s                     | 1        | 0.61%   |
| SK Hynix RAM Module 2GB DIMM DDR3 1066MT/s                     | 1        | 0.61%   |
| SK Hynix RAM HYMP512U64CP8-Y5 1024MB DIMM DDR2 667MT/s         | 1        | 0.61%   |
| SK Hynix RAM HYMP512U64BP8-Y5 1024MB DIMM DDR2 667MT/s         | 1        | 0.61%   |
| SK Hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.61%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.61%   |
| SK Hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s           | 1        | 0.61%   |
| SK Hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s           | 1        | 0.61%   |
| SK Hynix RAM HMT351U7BFR8A-H9 4GB DIMM DDR3 1333MT/s           | 1        | 0.61%   |
| SK Hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s           | 1        | 0.61%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 1        | 0.61%   |
| SK Hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s           | 1        | 0.61%   |
| SK Hynix RAM HMA451R7MFR8N-TF 4GB RIMM DDR4 2133MT/s           | 1        | 0.61%   |
| SK Hynix RAM HMA451R7AFR8N-TF 4GB RIMM DDR4 2133MT/s           | 1        | 0.61%   |
| SK Hynix RAM HMA42GR7MFR4N-TFT1 16GB RIMM 2133MT/s             | 1        | 0.61%   |
| SK Hynix RAM HMA41GR7MFR4N-TF 8192MB DIMM DDR4 2133MT/s        | 1        | 0.61%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                      | 1        | 0.61%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 1        | 0.61%   |
| Samsung RAM M471B5273DH0-CH9 4GB DIMM DDR3 1333MT/s            | 1        | 0.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1        | 0.61%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1        | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 66       | 50.77%  |
| DDR4    | 44       | 33.85%  |
| Unknown | 8        | 6.15%   |
| DDR2    | 5        | 3.85%   |
| SDRAM   | 4        | 3.08%   |
| DDR     | 2        | 1.54%   |
| LPDDR4  | 1        | 0.77%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 97       | 75.78%  |
| SODIMM | 29       | 22.66%  |
| RIMM   | 2        | 1.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 49       | 35.25%  |
| 8192  | 46       | 33.09%  |
| 16384 | 19       | 13.67%  |
| 2048  | 19       | 13.67%  |
| 1024  | 4        | 2.88%   |
| 32768 | 1        | 0.72%   |
| 512   | 1        | 0.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 47       | 33.57%  |
| 1333    | 22       | 15.71%  |
| 2400    | 13       | 9.29%   |
| 2133    | 12       | 8.57%   |
| 3200    | 8        | 5.71%   |
| 2667    | 7        | 5%      |
| 2666    | 7        | 5%      |
| 800     | 5        | 3.57%   |
| 667     | 4        | 2.86%   |
| Unknown | 3        | 2.14%   |
| 3600    | 2        | 1.43%   |
| 1866    | 2        | 1.43%   |
| 1066    | 2        | 1.43%   |
| 400     | 2        | 1.43%   |
| 5200    | 1        | 0.71%   |
| 1400    | 1        | 0.71%   |
| 1334    | 1        | 0.71%   |
| 333     | 1        | 0.71%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 2        | 66.67%  |
| Brother Industries | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| HP LaserJet 2200          | 1        | 33.33%  |
| HP Color LaserJet CP1215  | 1        | 33.33%  |
| Brother HL-L5200DW series | 1        | 33.33%  |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 2        | 66.67%  |
| Chicony Electronics | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech Webcam C310        | 1        | 33.33%  |
| Logitech HD Pro Webcam C920 | 1        | 33.33%  |
| Chicony HP 0.3MP Webcam     | 1        | 33.33%  |

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
| 1     | 77       | 55.4%   |
| 0     | 43       | 30.94%  |
| 2     | 14       | 10.07%  |
| 3     | 3        | 2.16%   |
| 4     | 2        | 1.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 87       | 76.32%  |
| Net/wireless             | 10       | 8.77%   |
| Sound                    | 4        | 3.51%   |
| Firewire controller      | 3        | 2.63%   |
| Bluetooth                | 3        | 2.63%   |
| Network                  | 2        | 1.75%   |
| Net/ethernet             | 2        | 1.75%   |
| Card reader              | 2        | 1.75%   |
| Storage/raid             | 1        | 0.88%   |
