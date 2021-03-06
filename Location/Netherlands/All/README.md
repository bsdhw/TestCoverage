BSD in Netherlands - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for BSD in Netherlands.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Netherlands/Desktop/README.md) and [notebooks](/Location/Netherlands/Notebook/README.md).

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

Total: 302

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| ASRock        | X300M-STX                   | Desktop     | [a76b64487b](https://bsd-hardware.info/?probe=a76b64487b) | Jul 01, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [9f33082ffa](https://bsd-hardware.info/?probe=9f33082ffa) | Jun 08, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [ff3865e01f](https://bsd-hardware.info/?probe=ff3865e01f) | Jun 05, 2022 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [4be827d8fe](https://bsd-hardware.info/?probe=4be827d8fe) | Jun 01, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [5893942a80](https://bsd-hardware.info/?probe=5893942a80) | May 30, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [ade09344b8](https://bsd-hardware.info/?probe=ade09344b8) | May 26, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [cc37ea1b7d](https://bsd-hardware.info/?probe=cc37ea1b7d) | May 26, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [abacee12a9](https://bsd-hardware.info/?probe=abacee12a9) | May 26, 2022 |
| Unknown       | Raspberry Pi 3 Model B P... | Desktop     | [21fa41e4c1](https://bsd-hardware.info/?probe=21fa41e4c1) | May 26, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [3dc5a6f7d2](https://bsd-hardware.info/?probe=3dc5a6f7d2) | May 24, 2022 |
| Dell          | Latitude E7240              | Notebook    | [970234b430](https://bsd-hardware.info/?probe=970234b430) | May 22, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [b9350aeb55](https://bsd-hardware.info/?probe=b9350aeb55) | May 21, 2022 |
| Pegatron      | 2AB5                        | Desktop     | [5cc0eb3e94](https://bsd-hardware.info/?probe=5cc0eb3e94) | May 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [66432302a4](https://bsd-hardware.info/?probe=66432302a4) | May 07, 2022 |
| PC Engines    | APU2                        | Desktop     | [26be7dfcb8](https://bsd-hardware.info/?probe=26be7dfcb8) | Apr 28, 2022 |
| PC Engines    | APU2                        | Desktop     | [4405a65be4](https://bsd-hardware.info/?probe=4405a65be4) | Apr 28, 2022 |
| PC Engines    | APU2                        | Desktop     | [5d79f85176](https://bsd-hardware.info/?probe=5d79f85176) | Apr 27, 2022 |
| PC Engines    | APU2                        | Desktop     | [3fe99889aa](https://bsd-hardware.info/?probe=3fe99889aa) | Apr 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [095a279c7b](https://bsd-hardware.info/?probe=095a279c7b) | Apr 25, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [4e7d57df3b](https://bsd-hardware.info/?probe=4e7d57df3b) | Apr 18, 2022 |
| HP            | 1998                        | Desktop     | [4f15447536](https://bsd-hardware.info/?probe=4f15447536) | Apr 18, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [c78d18300d](https://bsd-hardware.info/?probe=c78d18300d) | Apr 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [f58e088df2](https://bsd-hardware.info/?probe=f58e088df2) | Apr 16, 2022 |
| Sony          | SVZ1311C5E                  | Notebook    | [c1c429a7e6](https://bsd-hardware.info/?probe=c1c429a7e6) | Apr 15, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [87306109c8](https://bsd-hardware.info/?probe=87306109c8) | Apr 11, 2022 |
| Protectli     | FW6D                        | Desktop     | [e79304e1dc](https://bsd-hardware.info/?probe=e79304e1dc) | Apr 07, 2022 |
| Gigabyte      | B560M D3H                   | Desktop     | [99343fc0da](https://bsd-hardware.info/?probe=99343fc0da) | Apr 06, 2022 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [7db1501c5c](https://bsd-hardware.info/?probe=7db1501c5c) | Apr 06, 2022 |
| ASRock        | H61DE/S3                    | Desktop     | [00183a69ec](https://bsd-hardware.info/?probe=00183a69ec) | Apr 05, 2022 |
| Lenovo        | 319E SEK0T35577 IOT 4247... | Mini pc     | [634f184200](https://bsd-hardware.info/?probe=634f184200) | Apr 05, 2022 |
| Biostar       | H61MGV3                     | Desktop     | [1ef10e5e36](https://bsd-hardware.info/?probe=1ef10e5e36) | Apr 03, 2022 |
| Supermicro    | X12STL-IF                   | Server      | [87912d52e4](https://bsd-hardware.info/?probe=87912d52e4) | Mar 28, 2022 |
| PC Engines    | apu4                        | Desktop     | [618b2c7955](https://bsd-hardware.info/?probe=618b2c7955) | Mar 27, 2022 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [a1700b0347](https://bsd-hardware.info/?probe=a1700b0347) | Mar 21, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [671c66ca19](https://bsd-hardware.info/?probe=671c66ca19) | Mar 21, 2022 |
| Protectli     | FW4B                        | Desktop     | [5323027ba0](https://bsd-hardware.info/?probe=5323027ba0) | Mar 13, 2022 |
| Dell          | 03X6X0 A01                  | Server      | [00ccb7abb3](https://bsd-hardware.info/?probe=00ccb7abb3) | Mar 08, 2022 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [ec336ddab4](https://bsd-hardware.info/?probe=ec336ddab4) | Mar 08, 2022 |
| Supermicro    | X12STL-IF                   | Server      | [5054f03888](https://bsd-hardware.info/?probe=5054f03888) | Mar 06, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [19ed08c39c](https://bsd-hardware.info/?probe=19ed08c39c) | Mar 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [c91c5fe588](https://bsd-hardware.info/?probe=c91c5fe588) | Mar 03, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [c6caefebe6](https://bsd-hardware.info/?probe=c6caefebe6) | Feb 28, 2022 |
| Supermicro    | M11SDV-8C-LN4F              | Desktop     | [e4f7f31828](https://bsd-hardware.info/?probe=e4f7f31828) | Feb 28, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [74f28d34fd](https://bsd-hardware.info/?probe=74f28d34fd) | Feb 27, 2022 |
| Sophos        | XG                          | Firewall    | [44c92baffd](https://bsd-hardware.info/?probe=44c92baffd) | Feb 22, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [a5a8c71167](https://bsd-hardware.info/?probe=a5a8c71167) | Feb 18, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [64ccf1e6a0](https://bsd-hardware.info/?probe=64ccf1e6a0) | Feb 18, 2022 |
| Dell          | 05KX61 A02                  | Server      | [5e72ec3104](https://bsd-hardware.info/?probe=5e72ec3104) | Feb 17, 2022 |
| Dell          | 0R230R A00                  | Desktop     | [f3444924fd](https://bsd-hardware.info/?probe=f3444924fd) | Feb 17, 2022 |
| Lenovo        | ThinkPad X250 20CLS59400    | Notebook    | [92333ad60b](https://bsd-hardware.info/?probe=92333ad60b) | Feb 17, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [f259f73c17](https://bsd-hardware.info/?probe=f259f73c17) | Feb 14, 2022 |
| CompuLab      | uSVR                        | Mini pc     | [9afa228b2a](https://bsd-hardware.info/?probe=9afa228b2a) | Feb 12, 2022 |
| Dell          | 0R230R A00                  | Desktop     | [91870de9fe](https://bsd-hardware.info/?probe=91870de9fe) | Feb 06, 2022 |
| MSI           | H81I                        | Desktop     | [fe3a834f0b](https://bsd-hardware.info/?probe=fe3a834f0b) | Feb 05, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [f785bcb17a](https://bsd-hardware.info/?probe=f785bcb17a) | Feb 04, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [96436a1882](https://bsd-hardware.info/?probe=96436a1882) | Feb 03, 2022 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [f13e7340b1](https://bsd-hardware.info/?probe=f13e7340b1) | Jan 30, 2022 |
| Dell          | 0R230R A00                  | Desktop     | [cb50949dca](https://bsd-hardware.info/?probe=cb50949dca) | Jan 28, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [c7ef0e518f](https://bsd-hardware.info/?probe=c7ef0e518f) | Jan 27, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [c2d7238521](https://bsd-hardware.info/?probe=c2d7238521) | Jan 27, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [04afa3aa4f](https://bsd-hardware.info/?probe=04afa3aa4f) | Jan 23, 2022 |
| Dell          | 03X6X0 A01                  | Server      | [1c3abdddf5](https://bsd-hardware.info/?probe=1c3abdddf5) | Jan 19, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [e795c7ec91](https://bsd-hardware.info/?probe=e795c7ec91) | Jan 17, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [625c8f0f2c](https://bsd-hardware.info/?probe=625c8f0f2c) | Jan 14, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [d09cf2e0a7](https://bsd-hardware.info/?probe=d09cf2e0a7) | Jan 14, 2022 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [462b721778](https://bsd-hardware.info/?probe=462b721778) | Jan 11, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [877bb1b29f](https://bsd-hardware.info/?probe=877bb1b29f) | Jan 10, 2022 |
| Unknown       | Unknown                     | Notebook    | [974e1f4e5e](https://bsd-hardware.info/?probe=974e1f4e5e) | Jan 07, 2022 |
| MSI           | H61I-E35 V2/W8              | Desktop     | [8ae05f9d72](https://bsd-hardware.info/?probe=8ae05f9d72) | Jan 05, 2022 |
| XtReAmEr      | Unknown                     | Desktop     | [bd1315aa70](https://bsd-hardware.info/?probe=bd1315aa70) | Jan 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [0efa2c0531](https://bsd-hardware.info/?probe=0efa2c0531) | Dec 31, 2021 |
| Dell          | 0F9NPY A02                  | Server      | [1e0e3c3739](https://bsd-hardware.info/?probe=1e0e3c3739) | Dec 29, 2021 |
| Unknown       | Unknown                     | Desktop     | [79370c33df](https://bsd-hardware.info/?probe=79370c33df) | Dec 28, 2021 |
| Dell          | 03X6X0 A03                  | Server      | [2a59c1bfa2](https://bsd-hardware.info/?probe=2a59c1bfa2) | Dec 28, 2021 |
| Unknown       | Unknown                     | Desktop     | [c5e31aaf52](https://bsd-hardware.info/?probe=c5e31aaf52) | Dec 28, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [30aab74fbc](https://bsd-hardware.info/?probe=30aab74fbc) | Dec 24, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [6b03a2c4c2](https://bsd-hardware.info/?probe=6b03a2c4c2) | Dec 22, 2021 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [6529da52dc](https://bsd-hardware.info/?probe=6529da52dc) | Dec 21, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [69bf80f0c6](https://bsd-hardware.info/?probe=69bf80f0c6) | Dec 20, 2021 |
| Unknown       | Raspberry Pi 3 Model B P... | Desktop     | [ef0dcfaccf](https://bsd-hardware.info/?probe=ef0dcfaccf) | Dec 20, 2021 |
| TOXIC by B... | 15CL872 1050TI              | Notebook    | [0a1683170a](https://bsd-hardware.info/?probe=0a1683170a) | Dec 20, 2021 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [b099f26b73](https://bsd-hardware.info/?probe=b099f26b73) | Dec 20, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [17cad87a0d](https://bsd-hardware.info/?probe=17cad87a0d) | Dec 19, 2021 |
| PC Engines    | apu4                        | Desktop     | [f72343bec1](https://bsd-hardware.info/?probe=f72343bec1) | Dec 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [cd27dd3e2b](https://bsd-hardware.info/?probe=cd27dd3e2b) | Dec 17, 2021 |
| Lenovo        | ThinkPad A285 20MW000JMH    | Notebook    | [ff53f0763c](https://bsd-hardware.info/?probe=ff53f0763c) | Dec 12, 2021 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [fd05f5bf41](https://bsd-hardware.info/?probe=fd05f5bf41) | Dec 11, 2021 |
| HP            | 8105                        | Desktop     | [e38c91e91e](https://bsd-hardware.info/?probe=e38c91e91e) | Dec 11, 2021 |
| HP            | 8105                        | Desktop     | [0b923d55bc](https://bsd-hardware.info/?probe=0b923d55bc) | Dec 11, 2021 |
| Sophos        | XG                          | Firewall    | [59485a80e1](https://bsd-hardware.info/?probe=59485a80e1) | Dec 11, 2021 |
| Protectli     | FW6D                        | Desktop     | [33731d5933](https://bsd-hardware.info/?probe=33731d5933) | Dec 11, 2021 |
| Apple         | MacBookAir1,1               | Notebook    | [61c7028e83](https://bsd-hardware.info/?probe=61c7028e83) | Dec 07, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [5dbff17614](https://bsd-hardware.info/?probe=5dbff17614) | Dec 06, 2021 |
| Unknown       | Raspberry Pi 3 Model B P... | Desktop     | [646ca92a69](https://bsd-hardware.info/?probe=646ca92a69) | Dec 06, 2021 |
| Alienware     | 01NYPT A00                  | Desktop     | [75aa0c00fb](https://bsd-hardware.info/?probe=75aa0c00fb) | Dec 06, 2021 |
| TOXIC by B... | 15CL872 1050TI              | Notebook    | [4fbb430947](https://bsd-hardware.info/?probe=4fbb430947) | Dec 05, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [b77016bee5](https://bsd-hardware.info/?probe=b77016bee5) | Nov 25, 2021 |
| Dell          | 01V648 A04                  | Server      | [0f0265d958](https://bsd-hardware.info/?probe=0f0265d958) | Nov 25, 2021 |
| ASRock        | IMB-195                     | Desktop     | [58e7426808](https://bsd-hardware.info/?probe=58e7426808) | Nov 24, 2021 |
| Lenovo        | ThinkPad T430 2347G7G       | Notebook    | [66c64c1af9](https://bsd-hardware.info/?probe=66c64c1af9) | Nov 23, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [2276cb5406](https://bsd-hardware.info/?probe=2276cb5406) | Nov 20, 2021 |
| HP            | 339A                        | Desktop     | [a123d76249](https://bsd-hardware.info/?probe=a123d76249) | Nov 19, 2021 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [1486dc195e](https://bsd-hardware.info/?probe=1486dc195e) | Nov 17, 2021 |
| HP            | 1497                        | Desktop     | [24a8d1bb7a](https://bsd-hardware.info/?probe=24a8d1bb7a) | Nov 17, 2021 |
| PC Engines    | APU                         | Desktop     | [ca05f41685](https://bsd-hardware.info/?probe=ca05f41685) | Nov 16, 2021 |
| Dell          | 0R230R A00                  | Desktop     | [c2c6cf4b4d](https://bsd-hardware.info/?probe=c2c6cf4b4d) | Nov 16, 2021 |
| Unknown       | Unknown                     | Desktop     | [c473c704a9](https://bsd-hardware.info/?probe=c473c704a9) | Nov 14, 2021 |
| Unknown       | Unknown                     | Desktop     | [ec7dfabb51](https://bsd-hardware.info/?probe=ec7dfabb51) | Nov 12, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [04cc56305c](https://bsd-hardware.info/?probe=04cc56305c) | Nov 11, 2021 |
| Protectli     | FW4B                        | Desktop     | [cb7b87cd57](https://bsd-hardware.info/?probe=cb7b87cd57) | Nov 09, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [6f779d5170](https://bsd-hardware.info/?probe=6f779d5170) | Nov 03, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [72f0937505](https://bsd-hardware.info/?probe=72f0937505) | Nov 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [f80c884b6f](https://bsd-hardware.info/?probe=f80c884b6f) | Oct 31, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [e4958e59b0](https://bsd-hardware.info/?probe=e4958e59b0) | Oct 29, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [70da799fd0](https://bsd-hardware.info/?probe=70da799fd0) | Oct 25, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [bc4b7f33d5](https://bsd-hardware.info/?probe=bc4b7f33d5) | Oct 25, 2021 |
| Supermicro    | M11SDV-8C-LN4F              | Desktop     | [54c792ac8a](https://bsd-hardware.info/?probe=54c792ac8a) | Oct 20, 2021 |
| Barracuda ... | Barracuda NG Firewall F1... | Firewall    | [9ed491d56a](https://bsd-hardware.info/?probe=9ed491d56a) | Oct 16, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [67e62d9dd3](https://bsd-hardware.info/?probe=67e62d9dd3) | Oct 11, 2021 |
| Unknown       | Unknown                     | Desktop     | [b3b0308132](https://bsd-hardware.info/?probe=b3b0308132) | Oct 02, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [712bbd0635](https://bsd-hardware.info/?probe=712bbd0635) | Sep 29, 2021 |
| Protectli     | FW6D                        | Desktop     | [ee70d4b2fe](https://bsd-hardware.info/?probe=ee70d4b2fe) | Sep 25, 2021 |
| MSI           | H61I-E35 V2/W8              | Desktop     | [359cb66936](https://bsd-hardware.info/?probe=359cb66936) | Sep 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [1afa203e69](https://bsd-hardware.info/?probe=1afa203e69) | Sep 22, 2021 |
| Sapphire      | EDGE-FT1M1 E450 1AOVU044    | Desktop     | [ea8fefdf4e](https://bsd-hardware.info/?probe=ea8fefdf4e) | Sep 20, 2021 |
| Shuttle       | XH310V2                     | Desktop     | [f37b485384](https://bsd-hardware.info/?probe=f37b485384) | Sep 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [ba40cc9f75](https://bsd-hardware.info/?probe=ba40cc9f75) | Sep 17, 2021 |
| HP            | 8103 A01                    | Mini pc     | [860e4a3d12](https://bsd-hardware.info/?probe=860e4a3d12) | Sep 16, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [70d35afae8](https://bsd-hardware.info/?probe=70d35afae8) | Sep 15, 2021 |
| Sapphire      | EDGE-FT1M1 E450 1AOVU044    | Desktop     | [85ed325446](https://bsd-hardware.info/?probe=85ed325446) | Sep 11, 2021 |
| Fujitsu       | D3003-S2 S26361-D3003-S2    | Desktop     | [0510213747](https://bsd-hardware.info/?probe=0510213747) | Aug 30, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [b3a20bafca](https://bsd-hardware.info/?probe=b3a20bafca) | Aug 29, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [03e08762a6](https://bsd-hardware.info/?probe=03e08762a6) | Aug 27, 2021 |
| HP            | ProLiant DL380 G7           | Server      | [36e36edb7a](https://bsd-hardware.info/?probe=36e36edb7a) | Aug 24, 2021 |
| Shuttle       | DH370                       | Desktop     | [dea088a5bd](https://bsd-hardware.info/?probe=dea088a5bd) | Aug 20, 2021 |
| HP            | ProLiant DL380 G7           | Server      | [ad6b718b92](https://bsd-hardware.info/?probe=ad6b718b92) | Aug 20, 2021 |
| Protectli     | FW4B                        | Desktop     | [ab6695bb0b](https://bsd-hardware.info/?probe=ab6695bb0b) | Aug 18, 2021 |
| Intel         | NUC6i3SYB H81132-505        | Mini pc     | [e057495ca3](https://bsd-hardware.info/?probe=e057495ca3) | Aug 14, 2021 |
| HP            | ProLiant DL380 G7           | Server      | [fcf09dfbe5](https://bsd-hardware.info/?probe=fcf09dfbe5) | Aug 13, 2021 |
| HP            | ProLiant DL380 G7           | Server      | [e9335d8295](https://bsd-hardware.info/?probe=e9335d8295) | Aug 13, 2021 |
| HP            | 625                         | Notebook    | [606d75e6a1](https://bsd-hardware.info/?probe=606d75e6a1) | Aug 11, 2021 |
| HP            | 213D A01                    | Desktop     | [6e52020062](https://bsd-hardware.info/?probe=6e52020062) | Aug 10, 2021 |
| Shuttle       | DH370                       | Desktop     | [6d81fef4fb](https://bsd-hardware.info/?probe=6d81fef4fb) | Aug 09, 2021 |
| Unknown       | Unknown                     | Desktop     | [164b888dbe](https://bsd-hardware.info/?probe=164b888dbe) | Aug 08, 2021 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [0ad676c6a9](https://bsd-hardware.info/?probe=0ad676c6a9) | Aug 06, 2021 |
| Unknown       | Unknown                     | Notebook    | [d4122c5eb0](https://bsd-hardware.info/?probe=d4122c5eb0) | Aug 03, 2021 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [4253ffb8fb](https://bsd-hardware.info/?probe=4253ffb8fb) | Aug 02, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [a6de85de91](https://bsd-hardware.info/?probe=a6de85de91) | Jul 29, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [1e337fe131](https://bsd-hardware.info/?probe=1e337fe131) | Jul 29, 2021 |
| Unknown       | Unknown                     | Desktop     | [dd66bc21f6](https://bsd-hardware.info/?probe=dd66bc21f6) | Jul 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [b7edcfabb6](https://bsd-hardware.info/?probe=b7edcfabb6) | Jul 25, 2021 |
| Lenovo        | ThinkPad X230 2325IG2       | Notebook    | [158ecc5e0b](https://bsd-hardware.info/?probe=158ecc5e0b) | Jul 14, 2021 |
| PC Engines    | apu4                        | Desktop     | [027bbc5028](https://bsd-hardware.info/?probe=027bbc5028) | Jul 14, 2021 |
| HP            | 18E9                        | Desktop     | [7bac3be335](https://bsd-hardware.info/?probe=7bac3be335) | Jun 29, 2021 |
| Dell EMC      | VEP1425-V210-CPU A00        | Desktop     | [ad34d48259](https://bsd-hardware.info/?probe=ad34d48259) | Jun 27, 2021 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [5f46ba6832](https://bsd-hardware.info/?probe=5f46ba6832) | Jun 26, 2021 |
| Dell          | 0WR7PY A02                  | Desktop     | [ad5db0563f](https://bsd-hardware.info/?probe=ad5db0563f) | Jun 26, 2021 |
| Lenovo        | Yoga 500-14IBD 80N4         | Notebook    | [9fda78d739](https://bsd-hardware.info/?probe=9fda78d739) | Jun 23, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | Notebook    | [46dca136f6](https://bsd-hardware.info/?probe=46dca136f6) | Jun 21, 2021 |
| WYSE          | Z CLASS                     | Notebook    | [571fdbf390](https://bsd-hardware.info/?probe=571fdbf390) | Jun 19, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ee8a47b051](https://bsd-hardware.info/?probe=ee8a47b051) | Jun 17, 2021 |
| HP            | 3397                        | Desktop     | [3dd97c60ca](https://bsd-hardware.info/?probe=3dd97c60ca) | Jun 16, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | Notebook    | [9ae8146589](https://bsd-hardware.info/?probe=9ae8146589) | Jun 15, 2021 |
| Dell          | Latitude E4300              | Notebook    | [7855973957](https://bsd-hardware.info/?probe=7855973957) | Jun 12, 2021 |
| SLIMBOOK      | Unknown                     | Notebook    | [80a9ba918e](https://bsd-hardware.info/?probe=80a9ba918e) | Jun 11, 2021 |
| MSI           | B85M-P33 V2                 | Desktop     | [0633d1c78e](https://bsd-hardware.info/?probe=0633d1c78e) | Jun 10, 2021 |
| Dell          | 03X6X0 A02                  | Server      | [deb193d10f](https://bsd-hardware.info/?probe=deb193d10f) | Jun 10, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [db12a78352](https://bsd-hardware.info/?probe=db12a78352) | Jun 08, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [9a7adb8860](https://bsd-hardware.info/?probe=9a7adb8860) | Jun 06, 2021 |
| Intel         | NUC6i3SYB H81132-505        | Mini pc     | [4607d1410c](https://bsd-hardware.info/?probe=4607d1410c) | May 31, 2021 |
| Inventec      | R CLASS A02                 | Desktop     | [b621aeaac3](https://bsd-hardware.info/?probe=b621aeaac3) | May 30, 2021 |
| Gigabyte      | B85-HD3                     | Desktop     | [331da3091c](https://bsd-hardware.info/?probe=331da3091c) | May 28, 2021 |
| Dell          | 0200DY A02                  | Desktop     | [fcbfbc2dfa](https://bsd-hardware.info/?probe=fcbfbc2dfa) | May 25, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [8448df79cd](https://bsd-hardware.info/?probe=8448df79cd) | May 21, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [594c0438a0](https://bsd-hardware.info/?probe=594c0438a0) | May 21, 2021 |
| Notebook      | NL5xRU                      | Notebook    | [792fb07dd9](https://bsd-hardware.info/?probe=792fb07dd9) | May 10, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [add2c1bcba](https://bsd-hardware.info/?probe=add2c1bcba) | May 09, 2021 |
| Dell          | 03X6X0 A03                  | Server      | [d6312ecf58](https://bsd-hardware.info/?probe=d6312ecf58) | May 09, 2021 |
| Shuttle       | FH87                        | Desktop     | [bf5457ff02](https://bsd-hardware.info/?probe=bf5457ff02) | May 09, 2021 |
| Dell          | 0FJ030                      | Desktop     | [91418a4965](https://bsd-hardware.info/?probe=91418a4965) | Apr 30, 2021 |
| Dell          | 0FJ030                      | Desktop     | [7bee24ee8a](https://bsd-hardware.info/?probe=7bee24ee8a) | Apr 30, 2021 |
| Dell          | 0FJ030                      | Desktop     | [d5277ad9e1](https://bsd-hardware.info/?probe=d5277ad9e1) | Apr 30, 2021 |
| Dell          | 0FJ030                      | Desktop     | [63b1980830](https://bsd-hardware.info/?probe=63b1980830) | Apr 30, 2021 |
| HP            | 1998                        | Desktop     | [f6b53096d4](https://bsd-hardware.info/?probe=f6b53096d4) | Apr 28, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [a90eea4001](https://bsd-hardware.info/?probe=a90eea4001) | Apr 27, 2021 |
| HP            | 1497                        | Desktop     | [26724735db](https://bsd-hardware.info/?probe=26724735db) | Apr 24, 2021 |
| HP            | 1998                        | Desktop     | [051c63e153](https://bsd-hardware.info/?probe=051c63e153) | Apr 24, 2021 |
| ASRock        | J4105-ITX                   | Desktop     | [66eee76b50](https://bsd-hardware.info/?probe=66eee76b50) | Apr 21, 2021 |
| Dell          | 0F9NPY A02                  | Server      | [4ebcbdc297](https://bsd-hardware.info/?probe=4ebcbdc297) | Apr 20, 2021 |
| HP            | 1998                        | Desktop     | [7207f742d6](https://bsd-hardware.info/?probe=7207f742d6) | Apr 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [634521b082](https://bsd-hardware.info/?probe=634521b082) | Apr 07, 2021 |
| Barracuda ... | Barracuda NG Firewall F1... | Firewall    | [31caab92cf](https://bsd-hardware.info/?probe=31caab92cf) | Apr 07, 2021 |
| Unknown       | Unknown                     | Desktop     | [15e5f7932e](https://bsd-hardware.info/?probe=15e5f7932e) | Apr 06, 2021 |
| PC Engines    | apu4                        | Desktop     | [06a59860a8](https://bsd-hardware.info/?probe=06a59860a8) | Apr 04, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | Notebook    | [b644ed3914](https://bsd-hardware.info/?probe=b644ed3914) | Mar 31, 2021 |
| Dell          | 0200DY A02                  | Desktop     | [060ebba6d2](https://bsd-hardware.info/?probe=060ebba6d2) | Mar 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [4376accb5e](https://bsd-hardware.info/?probe=4376accb5e) | Mar 29, 2021 |
| MSI           | H410M-A PRO                 | Desktop     | [88f2766975](https://bsd-hardware.info/?probe=88f2766975) | Mar 27, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | Notebook    | [a5b9f5e79d](https://bsd-hardware.info/?probe=a5b9f5e79d) | Mar 27, 2021 |
| Lenovo        | ThinkPad X230 23255Y4       | Notebook    | [ab871769f0](https://bsd-hardware.info/?probe=ab871769f0) | Mar 27, 2021 |
| Dell          | 0DRR0P A00                  | Server      | [ebc09e92eb](https://bsd-hardware.info/?probe=ebc09e92eb) | Mar 26, 2021 |
| Shuttle       | FS310                       | Desktop     | [6514807d96](https://bsd-hardware.info/?probe=6514807d96) | Mar 25, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | Notebook    | [d856b5bf95](https://bsd-hardware.info/?probe=d856b5bf95) | Mar 23, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [4c06c1a897](https://bsd-hardware.info/?probe=4c06c1a897) | Mar 23, 2021 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [b8f568202d](https://bsd-hardware.info/?probe=b8f568202d) | Mar 22, 2021 |
| Dell          | Latitude E7270              | Notebook    | [5ba79f9aa5](https://bsd-hardware.info/?probe=5ba79f9aa5) | Mar 19, 2021 |
| HP            | ProLiant DL360 Gen9         | Desktop     | [b283b34881](https://bsd-hardware.info/?probe=b283b34881) | Mar 17, 2021 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [d5a1acb61b](https://bsd-hardware.info/?probe=d5a1acb61b) | Mar 17, 2021 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [21d6db75f5](https://bsd-hardware.info/?probe=21d6db75f5) | Mar 17, 2021 |
| HP            | ProLiant DL120 Gen9         | Server      | [533b1e078e](https://bsd-hardware.info/?probe=533b1e078e) | Mar 17, 2021 |
| Fujitsu       | D3279-H1 S26361-D3279-H1... | Server      | [7a9d95b303](https://bsd-hardware.info/?probe=7a9d95b303) | Mar 17, 2021 |
| Supermicro    | Super Server                | Server      | [ec1e532ea9](https://bsd-hardware.info/?probe=ec1e532ea9) | Mar 17, 2021 |
| Lenovo        | ThinkPad X280 20KESA000B    | Notebook    | [e2b586d597](https://bsd-hardware.info/?probe=e2b586d597) | Mar 17, 2021 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [fa0e0228a3](https://bsd-hardware.info/?probe=fa0e0228a3) | Mar 17, 2021 |
| iEi           | E452 V1.00                  | Desktop     | [b5665d0df2](https://bsd-hardware.info/?probe=b5665d0df2) | Mar 17, 2021 |
| HP            | ProLiant DL360 Gen9         | Desktop     | [bf440e72a1](https://bsd-hardware.info/?probe=bf440e72a1) | Mar 17, 2021 |
| HP            | EliteDesk 800 G5 SFF        | Desktop     | [aaf9bc1c12](https://bsd-hardware.info/?probe=aaf9bc1c12) | Mar 17, 2021 |
| ASRock        | Z490M Pro4                  | Desktop     | [6e0891ce80](https://bsd-hardware.info/?probe=6e0891ce80) | Mar 17, 2021 |
| Dell          | 0F9NPY A02                  | Server      | [ff4d8d8eca](https://bsd-hardware.info/?probe=ff4d8d8eca) | Mar 16, 2021 |
| Dell          | 0F9NPY A02                  | Server      | [cb3c1ad90e](https://bsd-hardware.info/?probe=cb3c1ad90e) | Mar 16, 2021 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [ee59c99fe4](https://bsd-hardware.info/?probe=ee59c99fe4) | Mar 15, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [359c03f28d](https://bsd-hardware.info/?probe=359c03f28d) | Mar 12, 2021 |
| HP            | 18E9                        | Desktop     | [cc435f4cd1](https://bsd-hardware.info/?probe=cc435f4cd1) | Mar 10, 2021 |
| Unknown       | Unknown                     | Desktop     | [2093895427](https://bsd-hardware.info/?probe=2093895427) | Mar 10, 2021 |
| Lenovo        | ThinkPad X200s 7470W1V      | Notebook    | [926fe13d8f](https://bsd-hardware.info/?probe=926fe13d8f) | Mar 09, 2021 |
| ASUSTek       | X556UA                      | Notebook    | [57018edd10](https://bsd-hardware.info/?probe=57018edd10) | Mar 07, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [f30a9505dd](https://bsd-hardware.info/?probe=f30a9505dd) | Mar 07, 2021 |
| Unknown       | Unknown                     | Desktop     | [2abc226441](https://bsd-hardware.info/?probe=2abc226441) | Mar 05, 2021 |
| Unknown       | Unknown                     | Desktop     | [60e0b1d346](https://bsd-hardware.info/?probe=60e0b1d346) | Mar 04, 2021 |
| Unknown       | Unknown                     | Desktop     | [db37dfcbf3](https://bsd-hardware.info/?probe=db37dfcbf3) | Mar 02, 2021 |
| MSI           | H410M-A PRO                 | Desktop     | [64bf9eb4cf](https://bsd-hardware.info/?probe=64bf9eb4cf) | Mar 01, 2021 |
| MSI           | H410M-A PRO                 | Desktop     | [eacaff1fff](https://bsd-hardware.info/?probe=eacaff1fff) | Feb 28, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [47c08e3817](https://bsd-hardware.info/?probe=47c08e3817) | Feb 27, 2021 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [9901302790](https://bsd-hardware.info/?probe=9901302790) | Feb 27, 2021 |
| Dell          | 00V62H A00                  | Desktop     | [441133db7f](https://bsd-hardware.info/?probe=441133db7f) | Feb 24, 2021 |
| Unknown       | Unknown                     | Desktop     | [1008505c8a](https://bsd-hardware.info/?probe=1008505c8a) | Feb 23, 2021 |
| MSI           | H410M-A PRO                 | Desktop     | [7d9e05b2fd](https://bsd-hardware.info/?probe=7d9e05b2fd) | Feb 21, 2021 |
| MSI           | H410M-A PRO                 | Desktop     | [408ba48f1f](https://bsd-hardware.info/?probe=408ba48f1f) | Feb 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [6c0a1e1154](https://bsd-hardware.info/?probe=6c0a1e1154) | Feb 20, 2021 |
| Supermicro    | X8SIL                       | Desktop     | [6318953f01](https://bsd-hardware.info/?probe=6318953f01) | Feb 18, 2021 |
| Dell          | Latitude E4300              | Notebook    | [d5051ef185](https://bsd-hardware.info/?probe=d5051ef185) | Feb 16, 2021 |
| Supermicro    | X9SCL/X9SCM                 | Desktop     | [a57dba0cb2](https://bsd-hardware.info/?probe=a57dba0cb2) | Feb 16, 2021 |
| Lenovo        | G505s 20255                 | Notebook    | [8bfcff9039](https://bsd-hardware.info/?probe=8bfcff9039) | Feb 16, 2021 |
| Dell          | 0T7D40 A01                  | Desktop     | [301fc86371](https://bsd-hardware.info/?probe=301fc86371) | Feb 15, 2021 |
| Protectli     | FW2B Ver                    | Desktop     | [57ca4c3cac](https://bsd-hardware.info/?probe=57ca4c3cac) | Feb 15, 2021 |
| Dell          | Latitude E4300              | Notebook    | [981de7fd20](https://bsd-hardware.info/?probe=981de7fd20) | Feb 14, 2021 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [d7cca96f72](https://bsd-hardware.info/?probe=d7cca96f72) | Feb 13, 2021 |
| Unknown       | Unknown                     | Desktop     | [994b94b7f5](https://bsd-hardware.info/?probe=994b94b7f5) | Feb 13, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [8f93b4146d](https://bsd-hardware.info/?probe=8f93b4146d) | Feb 12, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e74d76ecb3](https://bsd-hardware.info/?probe=e74d76ecb3) | Feb 12, 2021 |
| Dell          | Latitude 7280               | Notebook    | [defaee0e5c](https://bsd-hardware.info/?probe=defaee0e5c) | Feb 12, 2021 |
| Dell          | Latitude 7280               | Notebook    | [1e243253d1](https://bsd-hardware.info/?probe=1e243253d1) | Feb 12, 2021 |
| Dell          | Latitude 7280               | Notebook    | [1ba418a5e6](https://bsd-hardware.info/?probe=1ba418a5e6) | Feb 12, 2021 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [9ff4167171](https://bsd-hardware.info/?probe=9ff4167171) | Feb 12, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [687008da4f](https://bsd-hardware.info/?probe=687008da4f) | Feb 11, 2021 |
| Dell          | Latitude 7280               | Notebook    | [d62b7120c8](https://bsd-hardware.info/?probe=d62b7120c8) | Feb 11, 2021 |
| Dell          | 0DRR0P A00                  | Server      | [0b9292a0a4](https://bsd-hardware.info/?probe=0b9292a0a4) | Feb 11, 2021 |
| Dell          | Latitude 7370               | Notebook    | [8ec8d28024](https://bsd-hardware.info/?probe=8ec8d28024) | Feb 08, 2021 |
| PC Engines    | apu4                        | Desktop     | [67e0b30093](https://bsd-hardware.info/?probe=67e0b30093) | Feb 05, 2021 |
| PC Engines    | apu4                        | Desktop     | [d4b1d0ae99](https://bsd-hardware.info/?probe=d4b1d0ae99) | Feb 03, 2021 |
| PC Engines    | APU                         | Desktop     | [91da54ca8c](https://bsd-hardware.info/?probe=91da54ca8c) | Feb 02, 2021 |
| Dell          | Latitude E4300              | Notebook    | [84925c014a](https://bsd-hardware.info/?probe=84925c014a) | Feb 01, 2021 |
| Dell          | 0T7D40 A01                  | Desktop     | [1f5bf7092c](https://bsd-hardware.info/?probe=1f5bf7092c) | Feb 01, 2021 |
| Inventec      | VXC Class A02               | Desktop     | [22d0861af3](https://bsd-hardware.info/?probe=22d0861af3) | Jan 29, 2021 |
| Sophos        | SG                          | Firewall    | [d11e60890a](https://bsd-hardware.info/?probe=d11e60890a) | Jan 28, 2021 |
| Unknown       | Unknown                     | Desktop     | [f4b460a5e4](https://bsd-hardware.info/?probe=f4b460a5e4) | Jan 28, 2021 |
| Inventec      | VXC Class A02               | Desktop     | [8c298fa5bf](https://bsd-hardware.info/?probe=8c298fa5bf) | Jan 28, 2021 |
| Inventec      | VXC Class A02               | Desktop     | [6127d635de](https://bsd-hardware.info/?probe=6127d635de) | Jan 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [f76df86f03](https://bsd-hardware.info/?probe=f76df86f03) | Jan 26, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [881d50fc9e](https://bsd-hardware.info/?probe=881d50fc9e) | Jan 26, 2021 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [97fd3d11e8](https://bsd-hardware.info/?probe=97fd3d11e8) | Jan 25, 2021 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [2577292fe1](https://bsd-hardware.info/?probe=2577292fe1) | Jan 25, 2021 |
| Inventec      | R CLASS A02                 | Desktop     | [545854fcfd](https://bsd-hardware.info/?probe=545854fcfd) | Jan 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5b00abed29](https://bsd-hardware.info/?probe=5b00abed29) | Jan 23, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [f8e3f072fc](https://bsd-hardware.info/?probe=f8e3f072fc) | Jan 23, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [3c0683ff11](https://bsd-hardware.info/?probe=3c0683ff11) | Jan 22, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5d556cc47f](https://bsd-hardware.info/?probe=5d556cc47f) | Jan 22, 2021 |
| Barracuda ... | Barracuda NG Firewall F1... | Firewall    | [6a1974bebd](https://bsd-hardware.info/?probe=6a1974bebd) | Jan 22, 2021 |
| AMI           | PEISIA E3845 VER1.0         | Desktop     | [4b2e64662e](https://bsd-hardware.info/?probe=4b2e64662e) | Jan 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [951a898a3f](https://bsd-hardware.info/?probe=951a898a3f) | Jan 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [a1b0841493](https://bsd-hardware.info/?probe=a1b0841493) | Jan 21, 2021 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [064e82b131](https://bsd-hardware.info/?probe=064e82b131) | Jan 21, 2021 |
| HP            | EliteBook 2530p             | Notebook    | [1fd927e2cd](https://bsd-hardware.info/?probe=1fd927e2cd) | Jan 11, 2021 |
| ASRockRack    | EPC612D4U-8R                | Desktop     | [617694f591](https://bsd-hardware.info/?probe=617694f591) | Dec 19, 2020 |
| Supermicro    | X10SAE                      | Server      | [d29048ae5d](https://bsd-hardware.info/?probe=d29048ae5d) | Oct 29, 2020 |
| ASRock        | B360 Pro4                   | Desktop     | [05d3ab8d4b](https://bsd-hardware.info/?probe=05d3ab8d4b) | Oct 29, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [57ecc0c410](https://bsd-hardware.info/?probe=57ecc0c410) | Oct 29, 2020 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [3cebf4d7db](https://bsd-hardware.info/?probe=3cebf4d7db) | Oct 29, 2020 |
| ASRockRack    | EPC612D4U-8R                | Desktop     | [b9ecd0e2b3](https://bsd-hardware.info/?probe=b9ecd0e2b3) | Oct 29, 2020 |
| Dell          | Precision WorkStation T7... | Desktop     | [c01ce9ec81](https://bsd-hardware.info/?probe=c01ce9ec81) | Oct 24, 2020 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [dc33c84287](https://bsd-hardware.info/?probe=dc33c84287) | Oct 22, 2020 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | Notebook    | [2808d1dd6a](https://bsd-hardware.info/?probe=2808d1dd6a) | Oct 20, 2020 |
| Apple         | Macmini7,1                  | Mini pc     | [5caa1e1c7b](https://bsd-hardware.info/?probe=5caa1e1c7b) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | Desktop     | [7671a495d1](https://bsd-hardware.info/?probe=7671a495d1) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | Desktop     | [c1a2bc7a51](https://bsd-hardware.info/?probe=c1a2bc7a51) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | Desktop     | [c1c5ee566c](https://bsd-hardware.info/?probe=c1c5ee566c) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | Desktop     | [af87ddbbaa](https://bsd-hardware.info/?probe=af87ddbbaa) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [bee732e516](https://bsd-hardware.info/?probe=bee732e516) | Oct 19, 2020 |
| Intel         | S1200RP G62253-405          | Server      | [2793b07b38](https://bsd-hardware.info/?probe=2793b07b38) | May 30, 2020 |
| Gigabyte      | MQLP7AP-00                  | Desktop     | [07036eab43](https://bsd-hardware.info/?probe=07036eab43) | May 28, 2020 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [85bebeaea0](https://bsd-hardware.info/?probe=85bebeaea0) | May 25, 2020 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [9fea968a19](https://bsd-hardware.info/?probe=9fea968a19) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| OPNsense 21.7.7              | 13        | 5.37%   |
| OPNsense 21.7.5              | 9         | 3.72%   |
| OPNsense 21.1.3              | 9         | 3.72%   |
| OPNsense 21.7.3              | 8         | 3.31%   |
| OPNsense 21.7.1              | 8         | 3.31%   |
| OPNsense 21.1.1              | 8         | 3.31%   |
| OPNsense 20.7.8              | 8         | 3.31%   |
| OpenBSD 6.8                  | 8         | 3.31%   |
| OPNsense 21.7.2              | 7         | 2.89%   |
| helloSystem 0.5.0            | 7         | 2.89%   |
| FreeBSD 13.0                 | 7         | 2.89%   |
| OPNsense 22.1.6              | 6         | 2.48%   |
| OPNsense 22.1.4              | 6         | 2.48%   |
| OPNsense 22.1.1              | 6         | 2.48%   |
| OPNsense 22.1                | 6         | 2.48%   |
| OPNsense 21.1.2              | 6         | 2.48%   |
| OPNsense 21.1                | 6         | 2.48%   |
| OPNsense 21.1.7              | 5         | 2.07%   |
| OPNsense 21.1.4              | 5         | 2.07%   |
| OpenBSD 6.9                  | 5         | 2.07%   |
| FreeBSD 13.0-STABLE          | 5         | 2.07%   |
| FreeBSD 13.0-p5              | 5         | 2.07%   |
| OPNsense 21.7.6              | 4         | 1.65%   |
| OPNsense 21.1.6              | 4         | 1.65%   |
| OPNsense 21.1.5              | 4         | 1.65%   |
| OpenBSD 7.1                  | 4         | 1.65%   |
| helloSystem 0.7.0            | 4         | 1.65%   |
| helloSystem 0.3.0            | 4         | 1.65%   |
| FreeBSD 13.1                 | 4         | 1.65%   |
| OPNsense 22.1.2              | 3         | 1.24%   |
| OPNsense 21.7.8              | 3         | 1.24%   |
| OPNsense 21.7.4              | 3         | 1.24%   |
| OPNsense 21.1.9              | 3         | 1.24%   |
| helloSystem 0.6.0            | 3         | 1.24%   |
| HardenedBSD 12.2--HBSD       | 3         | 1.24%   |
| FreeBSD 13.0-p2              | 3         | 1.24%   |
| FreeBSD 12.2-p2              | 3         | 1.24%   |
| FreeBSD 12.2                 | 3         | 1.24%   |
| FreeBSD 12.1-p10             | 3         | 1.24%   |
| OPNsense 22.1.8              | 2         | 0.83%   |
| OPNsense 22.1.7              | 2         | 0.83%   |
| OPNsense 20.7.7              | 2         | 0.83%   |
| helloSystem 0.4.0            | 2         | 0.83%   |
| FreeBSD 14.0-CURRENT         | 2         | 0.83%   |
| FreeBSD 12.1-p5              | 2         | 0.83%   |
| pfSense 12.2-STABLE          | 1         | 0.41%   |
| OPNsense 22.1.5              | 1         | 0.41%   |
| OPNsense 22.1.3              | 1         | 0.41%   |
| OPNsense 21.7                | 1         | 0.41%   |
| OPNsense 21.1.8              | 1         | 0.41%   |
| OPNsense 20.7                | 1         | 0.41%   |
| OpenBSD 7.0                  | 1         | 0.41%   |
| NetBSD 9.99.94               | 1         | 0.41%   |
| HardenedBSD 13.0-STABLE-HBSD | 1         | 0.41%   |
| GhostBSD 21.08.27            | 1         | 0.41%   |
| GhostBSD 20.04.02            | 1         | 0.41%   |
| FreeBSD 13.0-RC2             | 1         | 0.41%   |
| FreeBSD 13.0-p6              | 1         | 0.41%   |
| FreeBSD 13.0-p11             | 1         | 0.41%   |
| FreeBSD 13.0-p10             | 1         | 0.41%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 104       | 54.74%  |
| FreeBSD     | 41        | 21.58%  |
| helloSystem | 19        | 10%     |
| OpenBSD     | 18        | 9.47%   |
| HardenedBSD | 4         | 2.11%   |
| GhostBSD    | 2         | 1.05%   |
| pfSense     | 1         | 0.53%   |
| NetBSD      | 1         | 0.53%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 181       | 96.28%  |
| arm64 | 6         | 3.19%   |
| i386  | 1         | 0.53%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 133       | 70%     |
| helloDesktop | 24        | 12.63%  |
| KDE5         | 7         | 3.68%   |
| fvwm         | 7         | 3.68%   |
| GNOME        | 5         | 2.63%   |
| XFCE         | 3         | 1.58%   |
| MATE         | 3         | 1.58%   |
| TWM          | 2         | 1.05%   |
| LXQt         | 2         | 1.05%   |
| i3           | 2         | 1.05%   |
| GNUstep      | 1         | 0.53%   |
| AwesomeWM    | 1         | 0.53%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 134       | 71.28%  |
| X11     | 52        | 27.66%  |
| Wayland | 2         | 1.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 144       | 76.6%   |
| SLiM    | 23        | 12.23%  |
| XDM     | 7         | 3.72%   |
| SDDM    | 6         | 3.19%   |
| LightDM | 4         | 2.13%   |
| GDM     | 4         | 2.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 129       | 67.54%  |
| en_US   | 36        | 18.85%  |
| C       | 24        | 12.57%  |
| nl_NL   | 2         | 1.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 151       | 79.47%  |
| BIOS | 39        | 20.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 98        | 51.31%  |
| Zfs    | 72        | 37.7%   |
| Ffs    | 18        | 9.42%   |
| Cd9660 | 3         | 1.57%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 164       | 86.77%  |
| MBR  | 25        | 13.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 27        | 14.36%  |
| Unknown             | 21        | 11.17%  |
| Hewlett-Packard     | 17        | 9.04%   |
| Lenovo              | 16        | 8.51%   |
| Supermicro          | 10        | 5.32%   |
| Intel               | 10        | 5.32%   |
| ASRock              | 10        | 5.32%   |
| Gigabyte Technology | 8         | 4.26%   |
| PC Engines          | 7         | 3.72%   |
| Apple               | 7         | 3.72%   |
| AMI                 | 6         | 3.19%   |
| ASUSTek Computer    | 5         | 2.66%   |
| Shuttle             | 4         | 2.13%   |
| MSI                 | 4         | 2.13%   |
| Sophos              | 3         | 1.6%    |
| Protectli           | 3         | 1.6%    |
| Inventec            | 3         | 1.6%    |
| Fujitsu             | 3         | 1.6%    |
| Deciso              | 2         | 1.06%   |
| Barracuda Networks  | 2         | 1.06%   |
| ZOTAC               | 1         | 0.53%   |
| XtReAmEr            | 1         | 0.53%   |
| WYSE                | 1         | 0.53%   |
| TUXEDO              | 1         | 0.53%   |
| TOXIC by BTO        | 1         | 0.53%   |
| Toshiba             | 1         | 0.53%   |
| Sony                | 1         | 0.53%   |
| SLIMBOOK            | 1         | 0.53%   |
| Sapphire            | 1         | 0.53%   |
| Pegatron            | 1         | 0.53%   |
| Notebook            | 1         | 0.53%   |
| MW                  | 1         | 0.53%   |
| iEi                 | 1         | 0.53%   |
| HPE                 | 1         | 0.53%   |
| HARDKERNEL          | 1         | 0.53%   |
| Dell EMC            | 1         | 0.53%   |
| CompuLab            | 1         | 0.53%   |
| Biostar             | 1         | 0.53%   |
| ASRockRack          | 1         | 0.53%   |
| Alienware           | 1         | 0.53%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 23        | 12.23%  |
| Intel Q3XXG4-P V1.0                      | 5         | 2.66%   |
| Dell PowerEdge R210 II                   | 5         | 2.66%   |
| AMI Aptio CRB                            | 5         | 2.66%   |
| Supermicro Super Server                  | 4         | 2.13%   |
| Dell PowerEdge R620                      | 4         | 2.13%   |
| PC Engines apu4                          | 3         | 1.6%    |
| Sophos XG                                | 2         | 1.06%   |
| PC Engines APU2                          | 2         | 1.06%   |
| PC Engines APU                           | 2         | 1.06%   |
| Inventec VXC Class                       | 2         | 1.06%   |
| HP EliteDesk 800 G1 SFF                  | 2         | 1.06%   |
| Gigabyte X570 AORUS PRO                  | 2         | 1.06%   |
| Dell Latitude E4300                      | 2         | 1.06%   |
| ZOTAC ZBOX-CI327NANO-GS-01               | 1         | 0.53%   |
| WYSE Z CLASS                             | 1         | 0.53%   |
| TUXEDO Pulse 15 Gen1                     | 1         | 0.53%   |
| TOXIC by BTO 15CL872 1050TI              | 1         | 0.53%   |
| Toshiba Satellite C50-B                  | 1         | 0.53%   |
| Supermicro X9SCL/X9SCM                   | 1         | 0.53%   |
| Supermicro X8SIL                         | 1         | 0.53%   |
| Supermicro X10SAE                        | 1         | 0.53%   |
| Supermicro AS -E301-9D-8CN4              | 1         | 0.53%   |
| Supermicro AS -5019D-FTN4                | 1         | 0.53%   |
| Supermicro A1SAi                         | 1         | 0.53%   |
| Sophos SG                                | 1         | 0.53%   |
| Sony SVZ1311C5E                          | 1         | 0.53%   |
| Shuttle XH310V2                          | 1         | 0.53%   |
| Shuttle SH87R                            | 1         | 0.53%   |
| Shuttle DH370                            | 1         | 0.53%   |
| Shuttle DH310                            | 1         | 0.53%   |
| Sapphire EDGE-FT1M1 E450 1AOVU044        | 1         | 0.53%   |
| Protectli FW6D                           | 1         | 0.53%   |
| Protectli FW4B                           | 1         | 0.53%   |
| Protectli FW2B                           | 1         | 0.53%   |
| Pegatron h8-1102nl                       | 1         | 0.53%   |
| Notebook NL5xRU                          | 1         | 0.53%   |
| MW GMLK-2_5G4L                           | 1         | 0.53%   |
| MSI MS-7C89                              | 1         | 0.53%   |
| MSI MS-7851                              | 1         | 0.53%   |
| MSI MS-7846                              | 1         | 0.53%   |
| MSI MS-7677                              | 1         | 0.53%   |
| Lenovo Yoga 500-14IBD 80N4               | 1         | 0.53%   |
| Lenovo ThinkStation E31 255526G          | 1         | 0.53%   |
| Lenovo ThinkPad X280 20KESA000B          | 1         | 0.53%   |
| Lenovo ThinkPad X250 20CLS59400          | 1         | 0.53%   |
| Lenovo ThinkPad X250 20CLS4WV08          | 1         | 0.53%   |
| Lenovo ThinkPad X230 2325IG2             | 1         | 0.53%   |
| Lenovo ThinkPad X230 23255Y4             | 1         | 0.53%   |
| Lenovo ThinkPad X200s 7470W1V            | 1         | 0.53%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDCTO1WW | 1         | 0.53%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW | 1         | 0.53%   |
| Lenovo ThinkPad T440s 20ARS1B704         | 1         | 0.53%   |
| Lenovo ThinkPad T430 2347G7G             | 1         | 0.53%   |
| Lenovo ThinkPad A285 20MW000JMH          | 1         | 0.53%   |
| Lenovo ThinkEdge SE30 11NA0005UK         | 1         | 0.53%   |
| Lenovo IdeaPad 130-15AST 81H5            | 1         | 0.53%   |
| Lenovo G505s 20255                       | 1         | 0.53%   |
| Inventec R CLASS                         | 1         | 0.53%   |
| Intel SHARKBAY                           | 1         | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 23        | 12.23%  |
| Dell PowerEdge               | 12        | 6.38%   |
| Lenovo ThinkPad              | 11        | 5.85%   |
| Dell Latitude                | 7         | 3.72%   |
| Intel Q3XXG4-P               | 5         | 2.66%   |
| Dell OptiPlex                | 5         | 2.66%   |
| AMI Aptio                    | 5         | 2.66%   |
| Supermicro Super             | 4         | 2.13%   |
| PC Engines apu4              | 3         | 1.6%    |
| HP ProLiant                  | 3         | 1.6%    |
| HP EliteDesk                 | 3         | 1.6%    |
| HP EliteBook                 | 3         | 1.6%    |
| HP Compaq                    | 3         | 1.6%    |
| Supermicro AS                | 2         | 1.06%   |
| Sophos XG                    | 2         | 1.06%   |
| PC Engines APU2              | 2         | 1.06%   |
| PC Engines APU               | 2         | 1.06%   |
| Inventec VXC                 | 2         | 1.06%   |
| HP ProDesk                   | 2         | 1.06%   |
| Gigabyte X570                | 2         | 1.06%   |
| Barracuda Networks Barracuda | 2         | 1.06%   |
| ASUS PRIME                   | 2         | 1.06%   |
| ZOTAC ZBOX-CI327NANO-GS-01   | 1         | 0.53%   |
| WYSE Z                       | 1         | 0.53%   |
| TUXEDO Pulse                 | 1         | 0.53%   |
| TOXIC by BTO 15CL872         | 1         | 0.53%   |
| Toshiba Satellite            | 1         | 0.53%   |
| Supermicro X9SCL             | 1         | 0.53%   |
| Supermicro X8SIL             | 1         | 0.53%   |
| Supermicro X10SAE            | 1         | 0.53%   |
| Supermicro A1SAi             | 1         | 0.53%   |
| Sophos SG                    | 1         | 0.53%   |
| Sony SVZ1311C5E              | 1         | 0.53%   |
| Shuttle XH310V2              | 1         | 0.53%   |
| Shuttle SH87R                | 1         | 0.53%   |
| Shuttle DH370                | 1         | 0.53%   |
| Shuttle DH310                | 1         | 0.53%   |
| Sapphire EDGE-FT1M1          | 1         | 0.53%   |
| Protectli FW6D               | 1         | 0.53%   |
| Protectli FW4B               | 1         | 0.53%   |
| Protectli FW2B               | 1         | 0.53%   |
| Pegatron h8-1102nl           | 1         | 0.53%   |
| Notebook NL5xRU              | 1         | 0.53%   |
| MW GMLK-2                    | 1         | 0.53%   |
| MSI MS-7C89                  | 1         | 0.53%   |
| MSI MS-7851                  | 1         | 0.53%   |
| MSI MS-7846                  | 1         | 0.53%   |
| MSI MS-7677                  | 1         | 0.53%   |
| Lenovo Yoga                  | 1         | 0.53%   |
| Lenovo ThinkStation          | 1         | 0.53%   |
| Lenovo ThinkEdge             | 1         | 0.53%   |
| Lenovo IdeaPad               | 1         | 0.53%   |
| Lenovo G505s                 | 1         | 0.53%   |
| Inventec R                   | 1         | 0.53%   |
| Intel SHARKBAY               | 1         | 0.53%   |
| Intel S1200RP                | 1         | 0.53%   |
| Intel NUC6i3SYB              | 1         | 0.53%   |
| Intel NUC5i3RYB              | 1         | 0.53%   |
| Intel CRESCENTBAY            | 1         | 0.53%   |
| iEi E452                     | 1         | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 25        | 13.3%   |
| 2020    | 22        | 11.7%   |
| 2019    | 21        | 11.17%  |
| 2014    | 17        | 9.04%   |
| 2015    | 15        | 7.98%   |
| 2016    | 14        | 7.45%   |
| 2017    | 12        | 6.38%   |
| 2013    | 12        | 6.38%   |
| 2012    | 11        | 5.85%   |
| 2011    | 11        | 5.85%   |
| 2021    | 10        | 5.32%   |
| 2009    | 6         | 3.19%   |
| Unknown | 6         | 3.19%   |
| 2010    | 2         | 1.06%   |
| 2022    | 1         | 0.53%   |
| 2008    | 1         | 0.53%   |
| 2007    | 1         | 0.53%   |
| 2006    | 1         | 0.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 110       | 58.51%  |
| Notebook       | 40        | 21.28%  |
| Server         | 17        | 9.04%   |
| Mini pc        | 13        | 6.91%   |
| Firewall       | 5         | 2.66%   |
| All in one     | 2         | 1.06%   |
| System on chip | 1         | 0.53%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 179       | 95.21%  |
| Yes  | 9         | 4.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 67        | 35.45%  |
| 4.01-8.0        | 45        | 23.81%  |
| 16.01-24.0      | 34        | 17.99%  |
| 32.01-64.0      | 19        | 10.05%  |
| 2.01-3.0        | 7         | 3.7%    |
| 64.01-256.0     | 7         | 3.7%    |
| 3.01-4.0        | 5         | 2.65%   |
| 1.01-2.0        | 2         | 1.06%   |
| More than 256.0 | 1         | 0.53%   |
| 24.01-32.0      | 1         | 0.53%   |
| 0.51-1.0        | 1         | 0.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 106       | 54.92%  |
| 0.51-1.0   | 45        | 23.32%  |
| 1.01-2.0   | 19        | 9.84%   |
| 4.01-8.0   | 6         | 3.11%   |
| 2.01-3.0   | 4         | 2.07%   |
| 3.01-4.0   | 3         | 1.55%   |
| 8.01-16.0  | 3         | 1.55%   |
| 32.01-64.0 | 2         | 1.04%   |
| 24.01-32.0 | 2         | 1.04%   |
| 16.01-24.0 | 1         | 0.52%   |
| 0          | 1         | 0.52%   |
| Unknown    | 1         | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 126       | 66.67%  |
| 2      | 29        | 15.34%  |
| 3      | 10        | 5.29%   |
| 0      | 9         | 4.76%   |
| 4      | 6         | 3.17%   |
| 5      | 4         | 2.12%   |
| 15     | 1         | 0.53%   |
| 12     | 1         | 0.53%   |
| 10     | 1         | 0.53%   |
| 7      | 1         | 0.53%   |
| 6      | 1         | 0.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 162       | 86.17%  |
| Yes       | 26        | 13.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 179       | 95.21%  |
| No        | 9         | 4.79%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 122       | 64.55%  |
| Yes       | 67        | 35.45%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 145       | 77.13%  |
| Yes       | 43        | 22.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Netherlands | 188       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Amsterdam               | 40        | 19.05%  |
| Utrecht                 | 5         | 2.38%   |
| Groningen               | 5         | 2.38%   |
| Vlaardingen             | 4         | 1.9%    |
| The Hague               | 4         | 1.9%    |
| Rotterdam               | 4         | 1.9%    |
| Poortugaal              | 4         | 1.9%    |
| Eindhoven               | 4         | 1.9%    |
| Barneveld               | 4         | 1.9%    |
| Alphen aan den Rijn     | 4         | 1.9%    |
| Almere Stad             | 4         | 1.9%    |
| Zaandam                 | 3         | 1.43%   |
| Hoogeveen               | 3         | 1.43%   |
| Amersfoort              | 3         | 1.43%   |
| Almere Poort            | 3         | 1.43%   |
| Zoetermeer              | 2         | 0.95%   |
| Zeist                   | 2         | 0.95%   |
| Veenendaal              | 2         | 0.95%   |
| Tilburg                 | 2         | 0.95%   |
| Soest                   | 2         | 0.95%   |
| Ospel                   | 2         | 0.95%   |
| Nieuwegein              | 2         | 0.95%   |
| Naaldwijk               | 2         | 0.95%   |
| Maastricht              | 2         | 0.95%   |
| Leiden                  | 2         | 0.95%   |
| IJsselstein             | 2         | 0.95%   |
| Hengelo                 | 2         | 0.95%   |
| Deventer                | 2         | 0.95%   |
| Delft                   | 2         | 0.95%   |
| Breda                   | 2         | 0.95%   |
| Beekbergen              | 2         | 0.95%   |
| Almelo                  | 2         | 0.95%   |
| Aalsmeer                | 2         | 0.95%   |
| 's-Hertogenbosch        | 2         | 0.95%   |
| Zutphen                 | 1         | 0.48%   |
| Zuidhorn                | 1         | 0.48%   |
| Zetten                  | 1         | 0.48%   |
| Zaltbommel              | 1         | 0.48%   |
| Woerdense Verlaat       | 1         | 0.48%   |
| Well                    | 1         | 0.48%   |
| Wassenaar               | 1         | 0.48%   |
| Warmond                 | 1         | 0.48%   |
| Vleuten                 | 1         | 0.48%   |
| Valkenswaard            | 1         | 0.48%   |
| Tiel                    | 1         | 0.48%   |
| Teteringen              | 1         | 0.48%   |
| Ten Boer                | 1         | 0.48%   |
| Swalmen                 | 1         | 0.48%   |
| Steenbergen             | 1         | 0.48%   |
| Spaubeek                | 1         | 0.48%   |
| Sneek                   | 1         | 0.48%   |
| Sittard                 | 1         | 0.48%   |
| Schalkhaar              | 1         | 0.48%   |
| Ruurlo                  | 1         | 0.48%   |
| Rozenburg               | 1         | 0.48%   |
| Roosendaal              | 1         | 0.48%   |
| Ridderkerk              | 1         | 0.48%   |
| Pijnacker               | 1         | 0.48%   |
| Oudheusden              | 1         | 0.48%   |
| Ouderkerk aan de Amstel | 1         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 43        | 59     | 19.37%  |
| WDC                 | 25        | 65     | 11.26%  |
| Crucial             | 21        | 34     | 9.46%   |
| Kingston            | 14        | 18     | 6.31%   |
| Seagate             | 13        | 43     | 5.86%   |
| Transcend           | 10        | 15     | 4.5%    |
| SanDisk             | 8         | 8      | 3.6%    |
| Toshiba             | 7         | 18     | 3.15%   |
| Hoodisk             | 6         | 10     | 2.7%    |
| Hitachi             | 5         | 6      | 2.25%   |
| Hewlett-Packard     | 5         | 10     | 2.25%   |
| LITEON              | 4         | 5      | 1.8%    |
| Intel               | 4         | 7      | 1.8%    |
| HGST                | 4         | 6      | 1.8%    |
| Gigabyte Technology | 4         | 4      | 1.8%    |
| Dell                | 4         | 8      | 1.8%    |
| China               | 4         | 9      | 1.8%    |
| UDinfo              | 3         | 3      | 1.35%   |
| Phison              | 3         | 3      | 1.35%   |
| NVMe                | 3         | 3      | 1.35%   |
| FORESEE             | 3         | 6      | 1.35%   |
| Apple               | 3         | 3      | 1.35%   |
| OCZ                 | 2         | 2      | 0.9%    |
| NETAPP              | 2         | 7      | 0.9%    |
| Kston               | 2         | 5      | 0.9%    |
| A-DATA Technology   | 2         | 2      | 0.9%    |
| StoreJet            | 1         | 1      | 0.45%   |
| SK hynix            | 1         | 1      | 0.45%   |
| Silicon Motion      | 1         | 1      | 0.45%   |
| Protectli           | 1         | 3      | 0.45%   |
| PNY                 | 1         | 1      | 0.45%   |
| Plextor             | 1         | 1      | 0.45%   |
| OWC                 | 1         | 1      | 0.45%   |
| ORICO               | 1         | 1      | 0.45%   |
| Mushkin             | 1         | 2      | 0.45%   |
| Micron Technology   | 1         | 1      | 0.45%   |
| Lenovo              | 1         | 2      | 0.45%   |
| Intenso             | 1         | 1      | 0.45%   |
| Innodisk            | 1         | 1      | 0.45%   |
| Indilinx            | 1         | 1      | 0.45%   |
| HPE                 | 1         | 1      | 0.45%   |
| Corsair             | 1         | 2      | 0.45%   |
| BAITITON            | 1         | 2      | 0.45%   |
| Apacer              | 1         | 2      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB        | 7         | 2.93%   |
| Kingston SUV500MS120G 120GB      | 4         | 1.67%   |
| Hoodisk SSD 128GB                | 4         | 1.67%   |
| Dell PERC H710 282GB             | 4         | 1.67%   |
| Crucial CT250MX500SSD1 250GB     | 4         | 1.67%   |
| UDinfo M2S 120GB                 | 3         | 1.26%   |
| Samsung SSD 850 EVO 500GB        | 3         | 1.26%   |
| Crucial CT240BX500SSD1 240GB     | 3         | 1.26%   |
| WDC WD80EFAX-68KNBN0 8TB         | 2         | 0.84%   |
| WDC WD60EFRX-68L0BN1 6TB         | 2         | 0.84%   |
| WDC WD40EFRX-68WT0N0 4TB         | 2         | 0.84%   |
| WDC WD40EFRX-68N32N0 4TB         | 2         | 0.84%   |
| Transcend TS32GSSD370S 32GB      | 2         | 0.84%   |
| Transcend TS128GMTE110S 128GB    | 2         | 0.84%   |
| Toshiba MQ04ABF100 1TB           | 2         | 0.84%   |
| Seagate ST500LM000-SSHD-8GB      | 2         | 0.84%   |
| Samsung SSD 970 EVO 1TB          | 2         | 0.84%   |
| Samsung SSD 840 Series 120GB     | 2         | 0.84%   |
| Samsung SSD 840 EVO 120GB        | 2         | 0.84%   |
| NETAPP X446_RALS200MCHT 200GB    | 2         | 0.84%   |
| LITEON IT LCS-128L9S-HP 128GB    | 2         | 0.84%   |
| LITEON CS1-SP16-11 M.2 2242 16GB | 2         | 0.84%   |
| Kston SSD 128GB                  | 2         | 0.84%   |
| Hoodisk SSD 64GB                 | 2         | 0.84%   |
| HGST HTS725050A7E630 500GB       | 2         | 0.84%   |
| Crucial CT500MX500SSD1 500GB     | 2         | 0.84%   |
| Crucial CT500MX200SSD1 500GB     | 2         | 0.84%   |
| Crucial CT480M500SSD1 480GB      | 2         | 0.84%   |
| Crucial CT120BX500SSD1 120GB     | 2         | 0.84%   |
| China SATA SSD 16GB              | 2         | 0.84%   |
| A-DATA IM2S3134N-064GM 64GB      | 2         | 0.84%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1         | 0.42%   |
| WDC WDS500G1X0E-00AFY0 500GB     | 1         | 0.42%   |
| WDC WDS240G2G0B-00EPW0 240GB     | 1         | 0.42%   |
| WDC WDS120G2G0A-00JH30 120GB     | 1         | 0.42%   |
| WDC WDS100T3X0C-00SJG0 1TB       | 1         | 0.42%   |
| WDC WDS100T2B0B-00YS70 1TB       | 1         | 0.42%   |
| WDC WD8003FFBX-68B9AN0 8TB       | 1         | 0.42%   |
| WDC WD7500AYYS-01RCA0 752GB      | 1         | 0.42%   |
| WDC WD5003ABYX-18WERA0 500GB     | 1         | 0.42%   |
| WDC WD5000AAKS-00A7B0 500GB      | 1         | 0.42%   |
| WDC WD5000AACS-00ZUB0 500GB      | 1         | 0.42%   |
| WDC WD4004FZWX-00GBGB0 4TB       | 1         | 0.42%   |
| WDC WD3200JS-22PDB0 320GB        | 1         | 0.42%   |
| WDC WD3200BPVT-22JJ5T0 320GB     | 1         | 0.42%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1         | 0.42%   |
| WDC WD20EFRX-68EUZN0 2TB         | 1         | 0.42%   |
| WDC WD15EARS-00Z5B1 1.5TB        | 1         | 0.42%   |
| WDC WD10SPZX-24Z10 1TB           | 1         | 0.42%   |
| WDC WD10JFCX-68N6GN0 1TB         | 1         | 0.42%   |
| WDC WD10EZEX-08WN4A0 1TB         | 1         | 0.42%   |
| WDC WD10EFRX-68PJCN0 1TB         | 1         | 0.42%   |
| WDC WD10EADS-00L5B1 1TB          | 1         | 0.42%   |
| WDC WD1001FALS-00J7B0 1TB        | 1         | 0.42%   |
| Transcend TS64GMSA230S 64GB      | 1         | 0.42%   |
| Transcend TS512GMTS430S 512GB    | 1         | 0.42%   |
| Transcend TS256GMSA452T2 256GB   | 1         | 0.42%   |
| Transcend TS128GMSA230S 128GB    | 1         | 0.42%   |
| Transcend TS120GMTS420S 120GB    | 1         | 0.42%   |
| Transcend TS120GESD240C 120GB    | 1         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 21        | 56     | 33.33%  |
| Seagate             | 13        | 43     | 20.63%  |
| Samsung Electronics | 5         | 8      | 7.94%   |
| Hitachi             | 5         | 6      | 7.94%   |
| HGST                | 4         | 6      | 6.35%   |
| Hewlett-Packard     | 4         | 9      | 6.35%   |
| Dell                | 4         | 8      | 6.35%   |
| Toshiba             | 3         | 11     | 4.76%   |
| StoreJet            | 1         | 1      | 1.59%   |
| NVMe                | 1         | 1      | 1.59%   |
| Lenovo              | 1         | 2      | 1.59%   |
| Apple               | 1         | 1      | 1.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 32        | 41     | 23.02%  |
| Crucial             | 21        | 30     | 15.11%  |
| Kingston            | 10        | 14     | 7.19%   |
| Transcend           | 8         | 13     | 5.76%   |
| SanDisk             | 8         | 8      | 5.76%   |
| Hoodisk             | 6         | 10     | 4.32%   |
| LITEON              | 4         | 5      | 2.88%   |
| Intel               | 4         | 7      | 2.88%   |
| China               | 4         | 9      | 2.88%   |
| WDC                 | 3         | 5      | 2.16%   |
| UDinfo              | 3         | 3      | 2.16%   |
| Phison              | 3         | 3      | 2.16%   |
| FORESEE             | 3         | 6      | 2.16%   |
| Toshiba             | 2         | 4      | 1.44%   |
| OCZ                 | 2         | 2      | 1.44%   |
| NVMe                | 2         | 2      | 1.44%   |
| NETAPP              | 2         | 7      | 1.44%   |
| Kston               | 2         | 5      | 1.44%   |
| Apple               | 2         | 2      | 1.44%   |
| A-DATA Technology   | 2         | 2      | 1.44%   |
| SK hynix            | 1         | 1      | 0.72%   |
| Protectli           | 1         | 3      | 0.72%   |
| PNY                 | 1         | 1      | 0.72%   |
| OWC                 | 1         | 1      | 0.72%   |
| ORICO               | 1         | 1      | 0.72%   |
| Mushkin             | 1         | 2      | 0.72%   |
| Micron Technology   | 1         | 1      | 0.72%   |
| Intenso             | 1         | 1      | 0.72%   |
| Innodisk            | 1         | 1      | 0.72%   |
| Indilinx            | 1         | 1      | 0.72%   |
| HPE                 | 1         | 1      | 0.72%   |
| Hewlett-Packard     | 1         | 1      | 0.72%   |
| Gigabyte Technology | 1         | 1      | 0.72%   |
| Corsair             | 1         | 2      | 0.72%   |
| BAITITON            | 1         | 2      | 0.72%   |
| Apacer              | 1         | 2      | 0.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 130       | 200    | 62.2%   |
| HDD  | 56        | 152    | 26.79%  |
| NVMe | 23        | 32     | 11%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 165       | 352    | 87.77%  |
| NVMe | 23        | 32     | 12.23%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 146       | 227    | 76.04%  |
| 0.51-1.0   | 21        | 44     | 10.94%  |
| 1.01-2.0   | 10        | 15     | 5.21%   |
| 3.01-4.0   | 7         | 18     | 3.65%   |
| 4.01-10.0  | 7         | 44     | 3.65%   |
| 2.01-3.0   | 1         | 4      | 0.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 70        | 36.08%  |
| 51-100         | 35        | 18.04%  |
| 251-500        | 31        | 15.98%  |
| 1-20           | 25        | 12.89%  |
| 21-50          | 13        | 6.7%    |
| 501-1000       | 9         | 4.64%   |
| 1001-2000      | 6         | 3.09%   |
| More than 3000 | 2         | 1.03%   |
| 2001-3000      | 2         | 1.03%   |
| Unknown        | 1         | 0.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 165       | 86.84%  |
| 21-50    | 9         | 4.74%   |
| 101-250  | 5         | 2.63%   |
| 51-100   | 5         | 2.63%   |
| 501-1000 | 3         | 1.58%   |
| 251-500  | 2         | 1.05%   |
| Unknown  | 1         | 0.53%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Crucial CT480M500SSD1 480GB               | 2         | 3      | 8%      |
| WDC WD15EARS-00Z5B1 1.5TB                 | 1         | 1      | 4%      |
| Seagate ST500LT012-9WS142 500GB           | 1         | 2      | 4%      |
| Seagate ST500LM021-1KJ152 500GB           | 1         | 1      | 4%      |
| Seagate ST3160318AS 160GB                 | 1         | 3      | 4%      |
| SanDisk SD7UB3Q256G1001 256GB             | 1         | 1      | 4%      |
| Samsung Electronics SSD 870 EVO 1TB       | 1         | 1      | 4%      |
| Samsung Electronics SSD 850 EVO mSATA 1TB | 1         | 1      | 4%      |
| Samsung Electronics SSD 850 EVO 1TB       | 1         | 1      | 4%      |
| Samsung Electronics SSD 840 Series 120GB  | 1         | 1      | 4%      |
| Samsung Electronics SSD 840 EVO 120GB     | 1         | 1      | 4%      |
| Samsung Electronics HS082HB 80GB          | 1         | 1      | 4%      |
| Samsung Electronics HD322HJ 320GB         | 1         | 1      | 4%      |
| Samsung Electronics HD103SJ 1TB           | 1         | 2      | 4%      |
| Kingston SMS200S3120G 120GB               | 1         | 1      | 4%      |
| Intel SSDSC2BA200G3T 200GB                | 1         | 4      | 4%      |
| Hitachi HTS545032B9A300 320GB             | 1         | 1      | 4%      |
| Hitachi HTS543232A7A384 320GB             | 1         | 1      | 4%      |
| Hitachi HDS723015BLA642 1.5TB             | 1         | 2      | 4%      |
| HGST HTS725050A7E630 500GB                | 1         | 1      | 4%      |
| HGST HDN726060ALE614 6TB                  | 1         | 2      | 4%      |
| Hewlett-Packard FB160C4081 160GB          | 1         | 2      | 4%      |
| Crucial CT128MX100SSD1 128GB              | 1         | 2      | 4%      |
| Corsair Force LS SSD 64GB                 | 1         | 2      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 9      | 29.17%  |
| Seagate             | 3         | 6      | 12.5%   |
| Hitachi             | 3         | 4      | 12.5%   |
| Crucial             | 3         | 5      | 12.5%   |
| HGST                | 2         | 3      | 8.33%   |
| WDC                 | 1         | 1      | 4.17%   |
| SanDisk             | 1         | 1      | 4.17%   |
| Kingston            | 1         | 1      | 4.17%   |
| Intel               | 1         | 4      | 4.17%   |
| Hewlett-Packard     | 1         | 2      | 4.17%   |
| Corsair             | 1         | 2      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 6      | 23.08%  |
| Samsung Electronics | 3         | 4      | 23.08%  |
| Hitachi             | 3         | 4      | 23.08%  |
| HGST                | 2         | 3      | 15.38%  |
| WDC                 | 1         | 1      | 7.69%   |
| Hewlett-Packard     | 1         | 2      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 20     | 56.52%  |
| SSD  | 10        | 18     | 43.48%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 960 EVO 250GB | 1         | 1      | 50%     |
| HPE MK000480GWUGF 480GB               | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| HPE                 | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 155       | 326    | 81.58%  |
| Malfunc  | 23        | 38     | 12.11%  |
| Detected | 10        | 18     | 5.26%   |
| Failed   | 2         | 2      | 1.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 144       | 65.45%  |
| AMD                         | 29        | 13.18%  |
| Samsung Electronics         | 10        | 4.55%   |
| Broadcom / LSI              | 7         | 3.18%   |
| ASMedia Technology          | 6         | 2.73%   |
| Phison Electronics          | 5         | 2.27%   |
| Kingston Technology Company | 3         | 1.36%   |
| Hewlett-Packard             | 3         | 1.36%   |
| Toshiba                     | 2         | 0.91%   |
| SanDisk                     | 2         | 0.91%   |
| Silicon Motion              | 1         | 0.45%   |
| Micron/Crucial Technology   | 1         | 0.45%   |
| Micron Technology           | 1         | 0.45%   |
| Marvell Technology Group    | 1         | 0.45%   |
| Lite-On Technology          | 1         | 0.45%   |
| JMicron Technology          | 1         | 0.45%   |
| Dell                        | 1         | 0.45%   |
| Chelsio Communications      | 1         | 0.45%   |
| Unknown                     | 1         | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 18        | 7.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 16        | 6.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 12        | 5.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 10        | 4.24%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 4.24%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 8         | 3.39%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8         | 3.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 2.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 2.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 2.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 6         | 2.54%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 5         | 2.12%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 2.12%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 5         | 2.12%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 1.69%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                   | 4         | 1.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.27%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 1.27%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3         | 1.27%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 3         | 1.27%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 3         | 1.27%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 3         | 1.27%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 3         | 1.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 1.27%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 3         | 1.27%   |
| Unknown                                                                          | 3         | 1.27%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 0.85%   |
| Kingston Company A2000 NVMe SSD                                                  | 2         | 0.85%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 0.85%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.85%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2         | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 0.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 0.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 0.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 0.85%   |
| HP Smart Array Gen9 Controllers                                                  | 2         | 0.85%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 2         | 0.85%   |
| Toshiba XG4 NVMe SSD Controller                                                  | 1         | 0.42%   |
| Toshiba BG3 NVMe SSD Controller                                                  | 1         | 0.42%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.42%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.42%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.42%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.42%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.42%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.42%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.42%   |
| Phison NVMe Storage Controller                                                   | 1         | 0.42%   |
| Phison E7 NVMe Controller                                                        | 1         | 0.42%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.42%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.42%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 1         | 0.42%   |
| Lite-On M8Pe Series NVMe SSD                                                     | 1         | 0.42%   |
| JMicron JMB360 AHCI Controller                                                   | 1         | 0.42%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 0.42%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 0.42%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.42%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 158       | 72.48%  |
| NVMe | 27        | 12.39%  |
| RAID | 19        | 8.72%   |
| IDE  | 10        | 4.59%   |
| SAS  | 3         | 1.38%   |
| SCSI | 1         | 0.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 150       | 79.79%  |
| AMD    | 32        | 17.02%  |
| ARM    | 6         | 3.19%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel Celeron CPU J3160 @ 1.60GHz      | 5         | 2.66%   |
| Intel Celeron CPU J1900 @ 1.99GHz      | 5         | 2.66%   |
| AMD GX-412TC SOC                       | 5         | 2.66%   |
| Intel Core 2 Duo                       | 4         | 2.13%   |
| ARM Cortex-A72 r0p3                    | 4         | 2.13%   |
| AMD G-T56N Processor                   | 4         | 2.13%   |
| Intel Xeon CPU D-1521 @ 2.40GHz        | 3         | 1.6%    |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz     | 2         | 1.06%   |
| Intel Core i7-7600U CPU @ 2.80GHz      | 2         | 1.06%   |
| Intel Core i7-4600U CPU @ 2.10GHz      | 2         | 1.06%   |
| Intel Core i7-3520M CPU @ 2.90GHz      | 2         | 1.06%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 2         | 1.06%   |
| Intel Core i5-8600 CPU @ 3.10GHz       | 2         | 1.06%   |
| Intel Core i5-6200U CPU @ 2.30GHz      | 2         | 1.06%   |
| Intel Core i5-5250U CPU @ 1.60GHz      | 2         | 1.06%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 2         | 1.06%   |
| Intel Core i5-4690 CPU @ 3.50GHz       | 2         | 1.06%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 2         | 1.06%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 2         | 1.06%   |
| Intel Core i5-3210M CPU @ 2.50GHz      | 2         | 1.06%   |
| Intel Core i5-10400 CPU @ 2.90GHz      | 2         | 1.06%   |
| Intel Atom CPU C3558 @ 2.20GHz         | 2         | 1.06%   |
| Intel Atom CPU C2358 @ 1.74GHz         | 2         | 1.06%   |
| ARM Cortex-A53 r0p4                    | 2         | 1.06%   |
| AMD G-T40E Processor                   | 2         | 1.06%   |
| AMD EPYC 3251 8-Core Processor         | 2         | 1.06%   |
| Intel Xeon E-2314 CPU @ 2.80GHz        | 1         | 0.53%   |
| Intel Xeon E-2274G CPU @ 4.00GHz       | 1         | 0.53%   |
| Intel Xeon E-2224 CPU @ 3.40GHz        | 1         | 0.53%   |
| Intel Xeon CPU X5680 @ 3.33GHz         | 1         | 0.53%   |
| Intel Xeon CPU X3430 @ 2.40GHz         | 1         | 0.53%   |
| Intel Xeon CPU E5606 @ 2.13GHz         | 1         | 0.53%   |
| Intel Xeon CPU E5520 @ 2.27GHz         | 1         | 0.53%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz     | 1         | 0.53%   |
| Intel Xeon CPU E5-2650L v3 @ 1.80GHz   | 1         | 0.53%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz     | 1         | 0.53%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz    | 1         | 0.53%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz    | 1         | 0.53%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz    | 1         | 0.53%   |
| Intel Xeon CPU E31270 @ 3.40GHz        | 1         | 0.53%   |
| Intel Xeon CPU E31260L @ 2.40GHz       | 1         | 0.53%   |
| Intel Xeon CPU E31220 @ 3.10GHz        | 1         | 0.53%   |
| Intel Xeon CPU E3-1285L v4 @ 3.40GHz   | 1         | 0.53%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GH     | 1         | 0.53%   |
| Intel Xeon CPU E3-1240 V2 @ 3.40GHz    | 1         | 0.53%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz    | 1         | 0.53%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz    | 1         | 0.53%   |
| Intel Pentium Gold G6500 CPU @ 4.10GHz | 1         | 0.53%   |
| Intel Pentium Gold G5600 CPU @ 3.90GHz | 1         | 0.53%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz | 1         | 0.53%   |
| Intel Pentium CPU N3530 @ 2.16GHz      | 1         | 0.53%   |
| Intel Pentium CPU G850 @ 2.90GHz       | 1         | 0.53%   |
| Intel Pentium CPU G4560 @ 3.50GHz      | 1         | 0.53%   |
| Intel Pentium CPU G3420 @ 3.20GHz      | 1         | 0.53%   |
| Intel Pentium CPU G3220 @ 3.00GHz      | 1         | 0.53%   |
| Intel Pentium CPU 5405U @ 2.30GHz      | 1         | 0.53%   |
| Intel Pentium 4                        | 1         | 0.53%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz       | 1         | 0.53%   |
| Intel Core i7-8750H CPU @ 2.20GHz      | 1         | 0.53%   |
| Intel Core i7-8665U CPU @ 1.90GHz      | 1         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 43        | 22.87%  |
| Intel Xeon         | 26        | 13.83%  |
| Intel Core i7      | 23        | 12.23%  |
| Intel Celeron      | 20        | 10.64%  |
| Intel Atom         | 10        | 5.32%   |
| AMD GX             | 9         | 4.79%   |
| Intel Core 2 Duo   | 8         | 4.26%   |
| Intel Pentium      | 6         | 3.19%   |
| Intel Core i3      | 6         | 3.19%   |
| ARM Cortex         | 6         | 3.19%   |
| AMD G              | 6         | 3.19%   |
| Other              | 4         | 2.13%   |
| Intel Pentium Gold | 3         | 1.6%    |
| AMD Ryzen 7        | 3         | 1.6%    |
| AMD Ryzen 5        | 2         | 1.06%   |
| AMD EPYC           | 2         | 1.06%   |
| Intel Pentium 4    | 1         | 0.53%   |
| Intel Core m7      | 1         | 0.53%   |
| Intel Core 2       | 1         | 0.53%   |
| AMD Ryzen Embedded | 1         | 0.53%   |
| AMD Ryzen 9        | 1         | 0.53%   |
| AMD Ryzen 7 PRO    | 1         | 0.53%   |
| AMD Ryzen 5 PRO    | 1         | 0.53%   |
| AMD E2             | 1         | 0.53%   |
| AMD E              | 1         | 0.53%   |
| AMD Athlon II      | 1         | 0.53%   |
| AMD A8             | 1         | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 76        | 40.43%  |
| 2       | 68        | 36.17%  |
| 8       | 11        | 5.85%   |
| Unknown | 11        | 5.85%   |
| 6       | 10        | 5.32%   |
| 12      | 6         | 3.19%   |
| 16      | 4         | 2.13%   |
| 1       | 2         | 1.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 176       | 93.62%  |
| 2       | 6         | 3.19%   |
| Unknown | 6         | 3.19%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 93        | 49.47%  |
| 2       | 84        | 44.68%  |
| Unknown | 11        | 5.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 23        | 12.23%  |
| Haswell       | 21        | 11.17%  |
| Silvermont    | 18        | 9.57%   |
| IvyBridge     | 17        | 9.04%   |
| Broadwell     | 15        | 7.98%   |
| SandyBridge   | 14        | 7.45%   |
| Skylake       | 9         | 4.79%   |
| Unknown       | 8         | 4.26%   |
| Penryn        | 7         | 3.72%   |
| Bobcat        | 7         | 3.72%   |
| Puma          | 6         | 3.19%   |
| Zen 2         | 5         | 2.66%   |
| Zen           | 5         | 2.66%   |
| CometLake     | 5         | 2.66%   |
| Goldmont      | 4         | 2.13%   |
| Westmere      | 3         | 1.6%    |
| Nehalem       | 3         | 1.6%    |
| Jaguar        | 3         | 1.6%    |
| Goldmont plus | 3         | 1.6%    |
| Core          | 2         | 1.06%   |
| Bonnell       | 2         | 1.06%   |
| Zen 3         | 1         | 0.53%   |
| TigerLake     | 1         | 0.53%   |
| Steamroller   | 1         | 0.53%   |
| Piledriver    | 1         | 0.53%   |
| NetBurst      | 1         | 0.53%   |
| K8 Hammer     | 1         | 0.53%   |
| K10           | 1         | 0.53%   |
| Excavator     | 1         | 0.53%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 104       | 59.09%  |
| AMD                        | 27        | 15.34%  |
| Matrox Electronics Systems | 19        | 10.8%   |
| Nvidia                     | 14        | 7.95%   |
| ASPEED Technology          | 12        | 6.82%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 12        | 6.74%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 9         | 5.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 5.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 4.49%   |
| Intel HD Graphics 5500                                                                   | 7         | 3.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 3.93%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 3.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.81%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 2.81%   |
| Matrox Electronics Systems G200eR2                                                       | 4         | 2.25%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 2.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 2.25%   |
| Intel HD Graphics 620                                                                    | 4         | 2.25%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4         | 2.25%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 2.25%   |
| Intel HD Graphics 6000                                                                   | 3         | 1.69%   |
| Intel HD Graphics 530                                                                    | 3         | 1.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 1.69%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 3         | 1.69%   |
| AMD Renoir                                                                               | 3         | 1.69%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 1.69%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 1.12%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2         | 1.12%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.12%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.12%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 2         | 1.12%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.12%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2         | 1.12%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.12%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.56%   |
| Nvidia GT218 [ION]                                                                       | 1         | 0.56%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.56%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.56%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.56%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.56%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 0.56%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 0.56%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.56%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 1         | 0.56%   |
| Nvidia GF108M [NVS 5400M]                                                                | 1         | 0.56%   |
| Nvidia GF108 [GeForce GT 530]                                                            | 1         | 0.56%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 1         | 0.56%   |
| Nvidia G72 [GeForce 7300 LE]                                                             | 1         | 0.56%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 1         | 0.56%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1         | 0.56%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 1         | 0.56%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 0.56%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1         | 0.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.56%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 0.56%   |
| Intel Iris Pro Graphics P6300                                                            | 1         | 0.56%   |
| Intel Iris Plus Graphics 650                                                             | 1         | 0.56%   |
| Intel HD Graphics 630                                                                    | 1         | 0.56%   |
| Intel HD Graphics 610                                                                    | 1         | 0.56%   |
| Intel HD Graphics 515                                                                    | 1         | 0.56%   |
| Intel HD Graphics 500                                                                    | 1         | 0.56%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 0.56%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 91        | 48.4%   |
| 1 x AMD        | 26        | 13.83%  |
| 1 x Matrox     | 19        | 10.11%  |
| Other          | 17        | 9.04%   |
| 1 x ASPEED     | 12        | 6.38%   |
| 1 x Nvidia     | 9         | 4.79%   |
| 2 x Intel      | 8         | 4.26%   |
| Intel + Nvidia | 5         | 2.66%   |
| 2 x AMD        | 1         | 0.53%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 162       | 86.17%  |
| Unknown     | 19        | 10.11%  |
| Proprietary | 7         | 3.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 171       | 90.96%  |
| 0.01-0.5   | 6         | 3.19%   |
| 1.01-2.0   | 5         | 2.66%   |
| 0.51-1.0   | 3         | 1.6%    |
| 7.01-8.0   | 2         | 1.06%   |
| 3.01-4.0   | 1         | 0.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| LG Display          | 9         | 18.37%  |
| Samsung Electronics | 7         | 14.29%  |
| Apple               | 5         | 10.2%   |
| Iiyama              | 4         | 8.16%   |
| BOE                 | 4         | 8.16%   |
| Chimei Innolux      | 3         | 6.12%   |
| AU Optronics        | 3         | 6.12%   |
| Sony                | 2         | 4.08%   |
| Sharp               | 2         | 4.08%   |
| Philips             | 2         | 4.08%   |
| Goldstar            | 2         | 4.08%   |
| Dell                | 2         | 4.08%   |
| ViewSonic           | 1         | 2.04%   |
| Lenovo              | 1         | 2.04%   |
| ASUSTek Computer    | 1         | 2.04%   |
| AOC                 | 1         | 2.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Philips PHL 328E1 PHLC204 3840x2160 700x390mm 31.5-inch              | 2         | 4.08%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch          | 2         | 4.08%   |
| ViewSonic LCD Monitor VX3276-QHD 2560x1440                           | 1         | 2.04%   |
| Sony TV SNYC901 1920x1080                                            | 1         | 2.04%   |
| Sony LCD SNY06FA 1600x900 290x160mm 13.0-inch                        | 1         | 2.04%   |
| Sharp LCD Monitor SHP1461 3200x1800 290x170mm 13.2-inch              | 1         | 2.04%   |
| Sharp LCD Monitor SHP1453 1920x1080 350x190mm 15.7-inch              | 1         | 2.04%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 470x300mm 22.0-inch | 1         | 2.04%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 410x310mm 20.2-inch | 1         | 2.04%   |
| Samsung Electronics S24H85x SAM0E0C 2560x1440 530x300mm 24.0-inch    | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SEC4541 1280x800 260x160mm 12.0-inch | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 340x190mm 15.3-inch | 1         | 2.04%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch         | 1         | 2.04%   |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch         | 1         | 2.04%   |
| LG Display LCD Monitor LGD0450 1366x768 280x160mm 12.7-inch          | 1         | 2.04%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 1         | 2.04%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch         | 1         | 2.04%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 1         | 2.04%   |
| LG Display LCD Monitor LGD02AD 1366x768 340x190mm 15.3-inch          | 1         | 2.04%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch              | 1         | 2.04%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch              | 1         | 2.04%   |
| Iiyama PL2740HS IVM6662 1920x1080 600x340mm 27.2-inch                | 1         | 2.04%   |
| Iiyama PL2492H IVM612F 1920x1080 530x300mm 24.0-inch                 | 1         | 2.04%   |
| Iiyama PL2209HD IVM560B 1920x1080 480x270mm 21.7-inch                | 1         | 2.04%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch          | 1         | 2.04%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 1         | 2.04%   |
| Dell UP2716D DEL40DD 2560x1440 600x340mm 27.2-inch                   | 1         | 2.04%   |
| Dell U2715H DELD065 2560x1440 600x340mm 27.2-inch                    | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN15B5 1366x768 340x190mm 15.3-inch      | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 310x170mm 13.9-inch     | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch     | 1         | 2.04%   |
| BOE LCD Monitor BOE07F7 1920x1080 310x170mm 13.9-inch                | 1         | 2.04%   |
| BOE LCD Monitor BOE07C8 3840x2160 310x170mm 13.9-inch                | 1         | 2.04%   |
| BOE LCD Monitor BOE06BF 1920x1080 280x160mm 12.7-inch                | 1         | 2.04%   |
| BOE LCD Monitor BOE0675 1366x768 340x190mm 15.3-inch                 | 1         | 2.04%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch       | 1         | 2.04%   |
| AU Optronics LCD Monitor AUO313E 1600x900 310x170mm 13.9-inch        | 1         | 2.04%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 1         | 2.04%   |
| ASUSTek Computer VG259 AUS25A6 1920x1080 540x300mm 24.3-inch         | 1         | 2.04%   |
| Apple LCD Monitor APP9CC3 1280x800 290x180mm 13.4-inch               | 1         | 2.04%   |
| Apple Color LCD APP9CD6 2560x1440 600x340mm 27.2-inch                | 1         | 2.04%   |
| Apple Color LCD APP9CC7 1280x800 290x180mm 13.4-inch                 | 1         | 2.04%   |
| Apple Color LCD APP9C6F 1280x800 290x190mm 13.6-inch                 | 1         | 2.04%   |
| Apple Color LCD APP9C5A 1680x1050 430x270mm 20.0-inch                | 1         | 2.04%   |
| AOC U2868 AOC2868 3840x2160 620x340mm 27.8-inch                      | 1         | 2.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 15        | 30.61%  |
| 1366x768 (WXGA)    | 8         | 16.33%  |
| 1280x800 (WXGA)    | 7         | 14.29%  |
| 2560x1440 (QHD)    | 6         | 12.24%  |
| 3840x2160 (4K)     | 5         | 10.2%   |
| 1600x900 (HD+)     | 3         | 6.12%   |
| 1680x1050 (WSXGA+) | 2         | 4.08%   |
| 3440x1440          | 1         | 2.04%   |
| 3200x1800 (QHD+)   | 1         | 2.04%   |
| 1600x1200          | 1         | 2.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 13        | 26.53%  |
| 12      | 10        | 20.41%  |
| 15      | 7         | 14.29%  |
| 27      | 6         | 12.24%  |
| 24      | 3         | 6.12%   |
| 31      | 2         | 4.08%   |
| 20      | 2         | 4.08%   |
| Unknown | 2         | 4.08%   |
| 34      | 1         | 2.04%   |
| 23      | 1         | 2.04%   |
| 22      | 1         | 2.04%   |
| 21      | 1         | 2.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 201-300     | 17        | 34.69%  |
| 301-350     | 13        | 26.53%  |
| 501-600     | 9         | 18.37%  |
| 401-500     | 4         | 8.16%   |
| 601-700     | 3         | 6.12%   |
| Unknown     | 2         | 4.08%   |
| 701-800     | 1         | 2.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 36        | 75%     |
| 16/10   | 8         | 16.67%  |
| 4/3     | 1         | 2.08%   |
| 3/2     | 1         | 2.08%   |
| 21/9    | 1         | 2.08%   |
| Unknown | 1         | 2.08%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch?? | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 11        | 22.45%  |
| 61-70          | 10        | 20.41%  |
| 301-350        | 6         | 12.24%  |
| 201-250        | 5         | 10.2%   |
| 91-100         | 5         | 10.2%   |
| 351-500        | 3         | 6.12%   |
| 71-80          | 2         | 4.08%   |
| 151-200        | 2         | 4.08%   |
| 101-110        | 2         | 4.08%   |
| Unknown        | 2         | 4.08%   |
| 251-300        | 1         | 2.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 17        | 35.42%  |
| 101-120       | 14        | 29.17%  |
| 51-100        | 7         | 14.58%  |
| 161-240       | 6         | 12.5%   |
| More than 240 | 2         | 4.17%   |
| Unknown       | 2         | 4.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 139       | 73.94%  |
| 1     | 47        | 25%     |
| 2     | 2         | 1.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 148       | 56.49%  |
| Realtek Semiconductor             | 53        | 20.23%  |
| Broadcom                          | 23        | 8.78%   |
| Qualcomm Atheros                  | 13        | 4.96%   |
| IMC Networks                      | 4         | 1.53%   |
| Ralink Technology                 | 3         | 1.15%   |
| TP-Link                           | 2         | 0.76%   |
| Marvell Technology Group          | 2         | 0.76%   |
| Hewlett-Packard                   | 2         | 0.76%   |
| Edimax Technology                 | 2         | 0.76%   |
| Sierra Wireless                   | 1         | 0.38%   |
| Ralink                            | 1         | 0.38%   |
| Mellanox Technologies             | 1         | 0.38%   |
| Insyde Software                   | 1         | 0.38%   |
| HMD Global                        | 1         | 0.38%   |
| Fibocom                           | 1         | 0.38%   |
| Ericsson Business Mobile Networks | 1         | 0.38%   |
| Chelsio Communications            | 1         | 0.38%   |
| AMD                               | 1         | 0.38%   |
| ADMtek                            | 1         | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 41        | 12.85%  |
| Intel I211 Gigabit Network Connection                                         | 28        | 8.78%   |
| Intel I210 Gigabit Network Connection                                         | 21        | 6.58%   |
| Intel I350 Gigabit Network Connection                                         | 18        | 5.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 11        | 3.45%   |
| Intel 82574L Gigabit Network Connection                                       | 11        | 3.45%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 7         | 2.19%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6         | 1.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 5         | 1.57%   |
| Intel Wi-Fi 6 AX200                                                           | 5         | 1.57%   |
| Intel Ethernet Connection I217-LM                                             | 4         | 1.25%   |
| Intel 82567LM Gigabit Network Connection                                      | 4         | 1.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 0.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 0.94%   |
| Intel Wireless-AC 9260                                                        | 3         | 0.94%   |
| Intel Wireless 8265 / 8275                                                    | 3         | 0.94%   |
| Intel Wireless 8260                                                           | 3         | 0.94%   |
| Intel Wireless 7265                                                           | 3         | 0.94%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 3         | 0.94%   |
| Intel Ethernet Connection X553 1GbE                                           | 3         | 0.94%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 3         | 0.94%   |
| Intel Ethernet Connection I354                                                | 3         | 0.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 3         | 0.94%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 3         | 0.94%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 3         | 0.94%   |
| Ralink RT5370 Wireless Adapter                                                | 2         | 0.63%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 2         | 0.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 2         | 0.63%   |
| Intel Wireless 7260                                                           | 2         | 0.63%   |
| Intel Wireless 3165                                                           | 2         | 0.63%   |
| Intel Wireless 3160                                                           | 2         | 0.63%   |
| Intel WiFi Link 5100                                                          | 2         | 0.63%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 2         | 0.63%   |
| Intel Ethernet Controller I225-V                                              | 2         | 0.63%   |
| Intel Ethernet Connection I219-V                                              | 2         | 0.63%   |
| Intel Ethernet Connection I218-LM                                             | 2         | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 0.63%   |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 0.63%   |
| Intel Ethernet Connection (14) I219-V                                         | 2         | 0.63%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2         | 0.63%   |
| Intel 82583V Gigabit Network Connection                                       | 2         | 0.63%   |
| Intel 82576 Gigabit Network Connection                                        | 2         | 0.63%   |
| Intel 82575GB Gigabit Network Connection                                      | 2         | 0.63%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 2         | 0.63%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2         | 0.63%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 2         | 0.63%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 2         | 0.63%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 2         | 0.63%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 2         | 0.63%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2         | 0.63%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 2         | 0.63%   |
| Broadcom BCM4321 802.11a/b/g/n                                                | 2         | 0.63%   |
| TP-Link TP-LINK Wireless USB Adapter                                          | 1         | 0.31%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1         | 0.31%   |
| Sierra Wireless EM7455                                                        | 1         | 0.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.31%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 1         | 0.31%   |
| Realtek RTL8192SU 802.11n WLAN Adapter                                        | 1         | 0.31%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1         | 0.31%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 48.1%   |
| Qualcomm Atheros      | 10        | 12.66%  |
| Realtek Semiconductor | 9         | 11.39%  |
| Broadcom              | 9         | 11.39%  |
| IMC Networks          | 4         | 5.06%   |
| Ralink Technology     | 3         | 3.8%    |
| TP-Link               | 2         | 2.53%   |
| Edimax Technology     | 2         | 2.53%   |
| Sierra Wireless       | 1         | 1.27%   |
| Ralink                | 1         | 1.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 5         | 6.33%   |
| Intel Wi-Fi 6 AX200                                                         | 5         | 6.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 3         | 3.8%    |
| Intel Wireless-AC 9260                                                      | 3         | 3.8%    |
| Intel Wireless 8265 / 8275                                                  | 3         | 3.8%    |
| Intel Wireless 8260                                                         | 3         | 3.8%    |
| Intel Wireless 7265                                                         | 3         | 3.8%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                     | 3         | 3.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 3         | 3.8%    |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                        | 3         | 3.8%    |
| Broadcom BCM4331 802.11a/b/g/n                                              | 3         | 3.8%    |
| Ralink RT5370 Wireless Adapter                                              | 2         | 2.53%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter             | 2         | 2.53%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 2         | 2.53%   |
| Intel Wireless 7260                                                         | 2         | 2.53%   |
| Intel Wireless 3165                                                         | 2         | 2.53%   |
| Intel Wireless 3160                                                         | 2         | 2.53%   |
| Intel WiFi Link 5100                                                        | 2         | 2.53%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]              | 2         | 2.53%   |
| Broadcom BCM43228 802.11a/b/g/n                                             | 2         | 2.53%   |
| Broadcom BCM4321 802.11a/b/g/n                                              | 2         | 2.53%   |
| TP-Link TP-LINK Wireless USB Adapter                                        | 1         | 1.27%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                  | 1         | 1.27%   |
| Sierra Wireless EM7455                                                      | 1         | 1.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 1.27%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                             | 1         | 1.27%   |
| Realtek RTL8192SU 802.11n WLAN Adapter                                      | 1         | 1.27%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 1         | 1.27%   |
| Ralink RT3572 Wireless Adapter                                              | 1         | 1.27%   |
| Ralink RT2500 Wireless 802.11bg                                             | 1         | 1.27%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                            | 1         | 1.27%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 1         | 1.27%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 1         | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 1         | 1.27%   |
| Intel Centrino Ultimate-N 6300                                              | 1         | 1.27%   |
| Intel Centrino Advanced-N 6235                                              | 1         | 1.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 1         | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                             | 1         | 1.27%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 1         | 1.27%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 1         | 1.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 1.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 132       | 63.77%  |
| Realtek Semiconductor    | 46        | 22.22%  |
| Broadcom                 | 18        | 8.7%    |
| Qualcomm Atheros         | 4         | 1.93%   |
| Marvell Technology Group | 2         | 0.97%   |
| Insyde Software          | 1         | 0.48%   |
| HMD Global               | 1         | 0.48%   |
| Chelsio Communications   | 1         | 0.48%   |
| AMD                      | 1         | 0.48%   |
| ADMtek                   | 1         | 0.48%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 41        | 17.45%  |
| Intel I211 Gigabit Network Connection                                          | 28        | 11.91%  |
| Intel I210 Gigabit Network Connection                                          | 21        | 8.94%   |
| Intel I350 Gigabit Network Connection                                          | 18        | 7.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 11        | 4.68%   |
| Intel 82574L Gigabit Network Connection                                        | 11        | 4.68%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                 | 7         | 2.98%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 6         | 2.55%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 1.7%    |
| Intel 82567LM Gigabit Network Connection                                       | 4         | 1.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3         | 1.28%   |
| Intel Ethernet Connection X553 1GbE                                            | 3         | 1.28%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                               | 3         | 1.28%   |
| Intel Ethernet Connection I354                                                 | 3         | 1.28%   |
| Intel I210 Gigabit Fiber Network Connection                                    | 2         | 0.85%   |
| Intel Ethernet Controller I225-V                                               | 2         | 0.85%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.85%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 0.85%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.85%   |
| Intel Ethernet Connection (2) I219-V                                           | 2         | 0.85%   |
| Intel Ethernet Connection (14) I219-V                                          | 2         | 0.85%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 2         | 0.85%   |
| Intel 82583V Gigabit Network Connection                                        | 2         | 0.85%   |
| Intel 82576 Gigabit Network Connection                                         | 2         | 0.85%   |
| Intel 82575GB Gigabit Network Connection                                       | 2         | 0.85%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                             | 2         | 0.85%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2         | 0.85%   |
| Intel 82541PI Gigabit Ethernet Controller                                      | 2         | 0.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 0.85%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 2         | 0.85%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 2         | 0.85%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.43%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1         | 0.43%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.43%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.43%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.43%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1         | 0.43%   |
| Intel Ethernet Controller X550                                                 | 1         | 0.43%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 1         | 0.43%   |
| Intel Ethernet Controller (2) I225-IT                                          | 1         | 0.43%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                     | 1         | 0.43%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.43%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.43%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.43%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.43%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.43%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.43%   |
| Intel Ethernet Connection (12) I219-V                                          | 1         | 0.43%   |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 0.43%   |
| Intel 82580 Gigabit Network Connection                                         | 1         | 0.43%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.43%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                     | 1         | 0.43%   |
| Intel 82567V-3 Gigabit Network Connection                                      | 1         | 0.43%   |
| Intel 82545GM Gigabit Ethernet Controller                                      | 1         | 0.43%   |
| Intel 82541GI Gigabit Ethernet Controller                                      | 1         | 0.43%   |
| Insyde Software RNDIS/Ethernet Gadget                                          | 1         | 0.43%   |
| HMD Global Nokia 5.3 RNDIS Control RNDIS Ethernet Data                         | 1         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 179       | 71.31%  |
| WiFi     | 67        | 26.69%  |
| Unknown  | 3         | 1.2%    |
| Modem    | 2         | 0.8%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 162       | 81.41%  |
| WiFi     | 37        | 18.59%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 76        | 40.43%  |
| 4     | 39        | 20.74%  |
| 1     | 23        | 12.23%  |
| 6     | 14        | 7.45%   |
| 3     | 12        | 6.38%   |
| 5     | 11        | 5.85%   |
| 0     | 5         | 2.66%   |
| 9     | 4         | 2.13%   |
| 8     | 2         | 1.06%   |
| 12    | 1         | 0.53%   |
| 7     | 1         | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 162       | 83.08%  |
| Yes  | 33        | 16.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 23        | 53.49%  |
| Apple                   | 7         | 16.28%  |
| Cambridge Silicon Radio | 5         | 11.63%  |
| Broadcom                | 3         | 6.98%   |
| Realtek Semiconductor   | 2         | 4.65%   |
| IMC Networks            | 1         | 2.33%   |
| Hewlett-Packard         | 1         | 2.33%   |
| Dell                    | 1         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 9         | 20.93%  |
| Intel AX200 Bluetooth                               | 5         | 11.63%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 11.63%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 9.3%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 6.98%   |
| Apple Bluetooth Host Controller                     | 3         | 6.98%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 4.65%   |
| Realtek RTL8723A Bluetooth                          | 1         | 2.33%   |
| Realtek  Bluetooth Adapter                          | 1         | 2.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.33%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.33%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0         | 1         | 2.33%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 2.33%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module         | 1         | 2.33%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 2.33%   |
| Apple Built-in iSight (no firmware loaded)          | 1         | 2.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 2.33%   |
| Apple Broadcom Bluetooth 2.1 module                 | 1         | 2.33%   |
| Apple Apple Broadcom Built-in Bluetooth             | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 103       | 71.53%  |
| AMD                         | 27        | 18.75%  |
| Nvidia                      | 10        | 6.94%   |
| VIA Technologies            | 1         | 0.69%   |
| Steinberg Soft-und Hardware | 1         | 0.69%   |
| Creative Labs               | 1         | 0.69%   |
| Corsair                     | 1         | 0.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 7.22%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 6.67%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 5%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 5%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 4.44%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 4.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 3.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 3.89%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 3.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 3.33%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 3.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 2.78%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 2.78%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 2.78%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 2.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.22%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 2.22%   |
| AMD FCH Azalia Controller                                                                         | 4         | 2.22%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.67%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.67%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 1.67%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.11%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.11%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.11%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 1.11%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 1.11%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.11%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 1.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.11%   |
| VIA Technologies USB Audio Device                                                                 | 1         | 0.56%   |
| Steinberg Soft-und Hardware MI4                                                                   | 1         | 0.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.56%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.56%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.56%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.56%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 0.56%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.56%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.56%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 0.56%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 1         | 0.56%   |
| Corsair Corsair VOID PRO Wireless Gaming Headset                                                  | 1         | 0.56%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.56%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.56%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 0.56%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 1         | 0.56%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.56%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.56%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.56%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 34        | 18.99%  |
| Kingston              | 29        | 16.2%   |
| Unknown               | 19        | 10.61%  |
| SK hynix              | 18        | 10.06%  |
| Micron Technology     | 16        | 8.94%   |
| Corsair               | 16        | 8.94%   |
| Crucial               | 11        | 6.15%   |
| Transcend             | 4         | 2.23%   |
| Apacer                | 4         | 2.23%   |
| Ramaxel Technology    | 3         | 1.68%   |
| Nanya Technology      | 3         | 1.68%   |
| Kimtigo               | 3         | 1.68%   |
| G.Skill               | 3         | 1.68%   |
| Elpida                | 3         | 1.68%   |
| A-DATA Technology     | 3         | 1.68%   |
| Unknown (ABCD)        | 1         | 0.56%   |
| Unknown (07FB)        | 1         | 0.56%   |
| Toshiba               | 1         | 0.56%   |
| Tigo                  | 1         | 0.56%   |
| Team                  | 1         | 0.56%   |
| Patriot               | 1         | 0.56%   |
| Kingmax Semiconductor | 1         | 0.56%   |
| HPE                   | 1         | 0.56%   |
| Hewlett-Packard       | 1         | 0.56%   |
| Avant                 | 1         | 0.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown                                                           | 19        | 10.05%  |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 4         | 2.12%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s             | 3         | 1.59%   |
| Apacer RAM 37352E4138334331 2GB SODIMM DDR3 1333MT/s              | 3         | 1.59%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 2         | 1.06%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s              | 2         | 1.06%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s               | 2         | 1.06%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 2         | 1.06%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1333MT/s               | 2         | 1.06%   |
| Kingston RAM 9965669-031.A00G 16GB DIMM DDR4 2400MT/s             | 2         | 1.06%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1333MT/s             | 2         | 1.06%   |
| Corsair RAM CMSO8GX4M1A2133C15 8GB SODIMM DDR4 2133MT/s           | 2         | 1.06%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s | 1         | 0.53%   |
| Unknown (07FB) RAM GSA8G4SCL156P-21 8GB SODIMM DDR4 2133MT/s      | 1         | 0.53%   |
| Transcend RAM TS512MLH64V6HL 4GB SODIMM DDR4 2667MT/s             | 1         | 0.53%   |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s               | 1         | 0.53%   |
| Transcend RAM JM1600KLN-4G 4GB DIMM DDR3 1600MT/s                 | 1         | 0.53%   |
| Transcend RAM JM1333KSN-4G 4GB DIMM DDR3 1333MT/s                 | 1         | 0.53%   |
| Toshiba RAM 9965527-025.A00LF 8GB SODIMM DDR3 1600MT/s            | 1         | 0.53%   |
| Tigo RAM 1600Mhz-8G 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.53%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 2400MT/s              | 1         | 0.53%   |
| SK hynix RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 0.53%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.53%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.53%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 1         | 0.53%   |
| SK hynix RAM HMT351U7EFR8A-PB 4GB DIMM DDR3 1600MT/s              | 1         | 0.53%   |
| SK hynix RAM HMT351U7CFR8A-H9 4GB DIMM DDR3 1333MT/s              | 1         | 0.53%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 1         | 0.53%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 0.53%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1333MT/s            | 1         | 0.53%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s              | 1         | 0.53%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s              | 1         | 0.53%   |
| SK hynix RAM HMA81GU7CJR8N-VK 8GB DIMM DDR4 2666MT/s              | 1         | 0.53%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 1         | 0.53%   |
| SK hynix RAM HMA81GR7MFR8N-UH 8GB DIMM DDR4 2400MT/s              | 1         | 0.53%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                       | 1         | 0.53%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s               | 1         | 0.53%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                         | 1         | 0.53%   |
| Samsung RAM Module 2GB DIMM DDR2 667MT/s                          | 1         | 0.53%   |
| Samsung RAM Module 2048MB SODIMM DDR3 1333MT/s                    | 1         | 0.53%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s             | 1         | 0.53%   |
| Samsung RAM M471B5273DH0-CH9 4GB DIMM DDR3 1333MT/s               | 1         | 0.53%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s             | 1         | 0.53%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 1         | 0.53%   |
| Samsung RAM M471B5173EB0-YK0 4GB DIMM DDR3 1600MT/s               | 1         | 0.53%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 1         | 0.53%   |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s               | 1         | 0.53%   |
| Samsung RAM M471B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s               | 1         | 0.53%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s             | 1         | 0.53%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s             | 1         | 0.53%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s             | 1         | 0.53%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s            | 1         | 0.53%   |
| Samsung RAM M391B5773DH0-YK0 2GB DIMM DDR3 1600MT/s               | 1         | 0.53%   |
| Samsung RAM M391B5773CH0-CH9 2GB DIMM DDR3 1333MT/s               | 1         | 0.53%   |
| Samsung RAM M391B5273DH0-CH9 4GB DIMM DDR3 1333MT/s               | 1         | 0.53%   |
| Samsung RAM M391B1G73BH0-YK0 8GB DIMM DDR3 1600MT/s               | 1         | 0.53%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s               | 1         | 0.53%   |
| Samsung RAM M378B1G73BH0-CK0 8GB DIMM DDR3 1333MT/s               | 1         | 0.53%   |
| Samsung RAM M378A1K43BB1-CPB 8GB DIMM DDR4 3000MT/s               | 1         | 0.53%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s           | 1         | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 94        | 58.75%  |
| DDR4    | 52        | 32.5%   |
| DDR2    | 8         | 5%      |
| LPDDR3  | 2         | 1.25%   |
| Unknown | 2         | 1.25%   |
| LPDDR4  | 1         | 0.63%   |
| DDR     | 1         | 0.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 84        | 52.17%  |
| SODIMM       | 74        | 45.96%  |
| Row Of Chips | 1         | 0.62%   |
| Chip         | 1         | 0.62%   |
| Unknown      | 1         | 0.62%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 65        | 37.36%  |
| 8192  | 60        | 34.48%  |
| 2048  | 27        | 15.52%  |
| 16384 | 15        | 8.62%   |
| 1024  | 4         | 2.3%    |
| 32768 | 3         | 1.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 57        | 34.13%  |
| 1333    | 37        | 22.16%  |
| 2400    | 15        | 8.98%   |
| 2133    | 14        | 8.38%   |
| 2667    | 11        | 6.59%   |
| 3200    | 6         | 3.59%   |
| 800     | 4         | 2.4%    |
| 667     | 4         | 2.4%    |
| 2666    | 3         | 1.8%    |
| 1334    | 3         | 1.8%    |
| 1866    | 2         | 1.2%    |
| 1067    | 2         | 1.2%    |
| Unknown | 2         | 1.2%    |
| 3400    | 1         | 0.6%    |
| 3000    | 1         | 0.6%    |
| 2933    | 1         | 0.6%    |
| 2134    | 1         | 0.6%    |
| 1867    | 1         | 0.6%    |
| 1777    | 1         | 0.6%    |
| 533     | 1         | 0.6%    |

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

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 8         | 27.59%  |
| Realtek Semiconductor                  | 4         | 13.79%  |
| Lite-On Technology                     | 3         | 10.34%  |
| Apple                                  | 3         | 10.34%  |
| Microdia                               | 2         | 6.9%    |
| IMC Networks                           | 2         | 6.9%    |
| Acer                                   | 2         | 6.9%    |
| Sunplus Innovation Technology          | 1         | 3.45%   |
| Sonix Technology                       | 1         | 3.45%   |
| Ricoh                                  | 1         | 3.45%   |
| Logitech                               | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                  | 2         | 6.9%    |
| Lite-On Integrated Camera                     | 2         | 6.9%    |
| Chicony Integrated Camera                     | 2         | 6.9%    |
| Chicony HD Webcam                             | 2         | 6.9%    |
| Apple FaceTime HD Camera                      | 2         | 6.9%    |
| Sunplus Laptop Integrated Webcam HD           | 1         | 3.45%   |
| Sonix FHD Webcam                              | 1         | 3.45%   |
| Ricoh USB2.0 Camera                           | 1         | 3.45%   |
| Realtek Lenovo EasyCamera                     | 1         | 3.45%   |
| Realtek Integrated Webcam HD                  | 1         | 3.45%   |
| Microdia Integrated_Webcam_HD                 | 1         | 3.45%   |
| Microdia Dell Integrated HD Webcam            | 1         | 3.45%   |
| Logitech HD Pro Webcam C920                   | 1         | 3.45%   |
| Lite-On TOSHIBA Web Camera - HD               | 1         | 3.45%   |
| IMC Networks Integrated Camera                | 1         | 3.45%   |
| IMC Networks EasyCamera                       | 1         | 3.45%   |
| Chicony thinkpad t430s camera                 | 1         | 3.45%   |
| Chicony Integrated Camera (1280x720@30)       | 1         | 3.45%   |
| Chicony HP Webcam [2 MP]                      | 1         | 3.45%   |
| Chicony Chicony USB2.0 Camera                 | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 1         | 3.45%   |
| Apple FaceTime HD Camera (Built-in)           | 1         | 3.45%   |
| Acer Lenovo EasyCamera                        | 1         | 3.45%   |
| Acer Integrated Camera                        | 1         | 3.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 33.33%  |
| Synaptics        | 2         | 33.33%  |
| AuthenTec        | 2         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                             | Computers | Percent |
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


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 80        | 42.11%  |
| 0     | 65        | 34.21%  |
| 2     | 30        | 15.79%  |
| 3     | 10        | 5.26%   |
| 4     | 5         | 2.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 107       | 63.69%  |
| Net/wireless             | 18        | 10.71%  |
| Bluetooth                | 13        | 7.74%   |
| Card reader              | 10        | 5.95%   |
| Firewire controller      | 5         | 2.98%   |
| Fingerprint reader       | 5         | 2.98%   |
| Net/ethernet             | 3         | 1.79%   |
| Storage/ata              | 2         | 1.19%   |
| Graphics card            | 2         | 1.19%   |
| Storage/raid             | 1         | 0.6%    |
| Storage                  | 1         | 0.6%    |
| Sound                    | 1         | 0.6%    |

