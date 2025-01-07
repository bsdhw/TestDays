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

Total: 818

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | 04Y8V0 A02                  | [1d20d5fd79](https://bsd-hardware.info/?probe=1d20d5fd79) | Jan 05, 2025 |
| Dell          | 0FDY5C A00                  | [f0d39986e9](https://bsd-hardware.info/?probe=f0d39986e9) | Jan 04, 2025 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [686b424a28](https://bsd-hardware.info/?probe=686b424a28) | Jan 02, 2025 |
| Unknown       | Unknown                     | [d06ccdd495](https://bsd-hardware.info/?probe=d06ccdd495) | Dec 31, 2024 |
| Intel         | DQ77KB AAG40294-402         | [9db11dd0c9](https://bsd-hardware.info/?probe=9db11dd0c9) | Dec 28, 2024 |
| Gigabyte      | Z790 AORUS MASTER X         | [d8022a2734](https://bsd-hardware.info/?probe=d8022a2734) | Dec 24, 2024 |
| Dell          | 0D28YY A00                  | [97d068af1e](https://bsd-hardware.info/?probe=97d068af1e) | Dec 21, 2024 |
| Unknown       | Unknown                     | [e79ae3cc67](https://bsd-hardware.info/?probe=e79ae3cc67) | Dec 19, 2024 |
| Unknown       | Unknown                     | [b4adf727f6](https://bsd-hardware.info/?probe=b4adf727f6) | Dec 16, 2024 |
| Unknown       | Unknown                     | [e2839ab569](https://bsd-hardware.info/?probe=e2839ab569) | Dec 16, 2024 |
| Unknown       | Unknown                     | [db147012b7](https://bsd-hardware.info/?probe=db147012b7) | Dec 15, 2024 |
| Protectli     | FW6 Ver                     | [f6adfa6006](https://bsd-hardware.info/?probe=f6adfa6006) | Dec 15, 2024 |
| Gigabyte      | M68MT-S2                    | [87ce6d4615](https://bsd-hardware.info/?probe=87ce6d4615) | Dec 13, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [2fb19b27c9](https://bsd-hardware.info/?probe=2fb19b27c9) | Dec 13, 2024 |
| Dell          | 0D28YY A00                  | [bd7757d88d](https://bsd-hardware.info/?probe=bd7757d88d) | Dec 08, 2024 |
| ASUSTek       | ROG STRIX X870E-E GAMING... | [4edaabd936](https://bsd-hardware.info/?probe=4edaabd936) | Dec 07, 2024 |
| Protectli     | VP2410 10                   | [0d08c971b8](https://bsd-hardware.info/?probe=0d08c971b8) | Dec 07, 2024 |
| Gigabyte      | 2AC8                        | [c18b3da04b](https://bsd-hardware.info/?probe=c18b3da04b) | Dec 04, 2024 |
| Gigabyte      | H81M-HD2                    | [2c74776cf6](https://bsd-hardware.info/?probe=2c74776cf6) | Dec 04, 2024 |
| AZW           | EQ                          | [8f20d42e6e](https://bsd-hardware.info/?probe=8f20d42e6e) | Dec 04, 2024 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [e3cc180fdd](https://bsd-hardware.info/?probe=e3cc180fdd) | Dec 02, 2024 |
| MSI           | H61M-P21                    | [55ae602922](https://bsd-hardware.info/?probe=55ae602922) | Dec 02, 2024 |
| Unknown       | Unknown                     | [c3a9c1cbc8](https://bsd-hardware.info/?probe=c3a9c1cbc8) | Dec 02, 2024 |
| Intel         | DCP847SKE G80890-105        | [29d05d280a](https://bsd-hardware.info/?probe=29d05d280a) | Dec 02, 2024 |
| Protectli     | FW6                         | [3d8bb2e6ef](https://bsd-hardware.info/?probe=3d8bb2e6ef) | Dec 01, 2024 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [ee30758c43](https://bsd-hardware.info/?probe=ee30758c43) | Nov 30, 2024 |
| Yanling       | YL-KBR6L Ver:1.00           | [2af8f99a1c](https://bsd-hardware.info/?probe=2af8f99a1c) | Nov 29, 2024 |
| Deciso        | Netboard A8                 | [5b1cde4aac](https://bsd-hardware.info/?probe=5b1cde4aac) | Nov 24, 2024 |
| Intel         | DG45ID AAE27729-307         | [14f367aa0a](https://bsd-hardware.info/?probe=14f367aa0a) | Nov 23, 2024 |
| Intel         | CARLOW                      | [b58da7d85d](https://bsd-hardware.info/?probe=b58da7d85d) | Nov 21, 2024 |
| Dell          | 00V62H A00                  | [22f8452e6d](https://bsd-hardware.info/?probe=22f8452e6d) | Nov 20, 2024 |
| ASRockRack    | X470D4U2-2T                 | [638b70ebe3](https://bsd-hardware.info/?probe=638b70ebe3) | Nov 20, 2024 |
| Unknown       | Unknown                     | [5c3daa7361](https://bsd-hardware.info/?probe=5c3daa7361) | Nov 20, 2024 |
| ASUSTek       | M5A97 LE R2.0               | [7aae707db6](https://bsd-hardware.info/?probe=7aae707db6) | Nov 17, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [e337ee0494](https://bsd-hardware.info/?probe=e337ee0494) | Nov 14, 2024 |
| Unknown       | Unknown                     | [63da6bf4a3](https://bsd-hardware.info/?probe=63da6bf4a3) | Nov 13, 2024 |
| Gigabyte      | 2AC8                        | [0866ab9c03](https://bsd-hardware.info/?probe=0866ab9c03) | Nov 12, 2024 |
| CWWK          | MINIPC-G12                  | [95728c8f3f](https://bsd-hardware.info/?probe=95728c8f3f) | Nov 12, 2024 |
| Unknown       | Unknown                     | [66f4c037b4](https://bsd-hardware.info/?probe=66f4c037b4) | Nov 11, 2024 |
| HP            | 805D                        | [eee32d882b](https://bsd-hardware.info/?probe=eee32d882b) | Nov 07, 2024 |
| CheckPoint    | T-180-00                    | [0d54372aff](https://bsd-hardware.info/?probe=0d54372aff) | Nov 05, 2024 |
| Unknown       | Unknown                     | [e2322b3441](https://bsd-hardware.info/?probe=e2322b3441) | Nov 03, 2024 |
| AZW           | Green G1                    | [e7ca5d5578](https://bsd-hardware.info/?probe=e7ca5d5578) | Nov 02, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [0c3e394182](https://bsd-hardware.info/?probe=0c3e394182) | Oct 30, 2024 |
| Unknown       | Unknown                     | [44c67eed86](https://bsd-hardware.info/?probe=44c67eed86) | Oct 30, 2024 |
| Protectli     | VP2410 10                   | [c8fd0713b0](https://bsd-hardware.info/?probe=c8fd0713b0) | Oct 30, 2024 |
| CncTion       | N5105-4L B0                 | [a95688132e](https://bsd-hardware.info/?probe=a95688132e) | Oct 28, 2024 |
| Protectli     | VP4670                      | [72007dc0a7](https://bsd-hardware.info/?probe=72007dc0a7) | Oct 18, 2024 |
| MSI           | PRO B660-A DDR4             | [688de382ec](https://bsd-hardware.info/?probe=688de382ec) | Oct 16, 2024 |
| Unknown       | Unknown                     | [eba06a275d](https://bsd-hardware.info/?probe=eba06a275d) | Oct 16, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [65db357b67](https://bsd-hardware.info/?probe=65db357b67) | Oct 15, 2024 |
| Shenzhen M... | AHBNB OEM                   | [cb7d2d44d9](https://bsd-hardware.info/?probe=cb7d2d44d9) | Oct 14, 2024 |
| HP            | 1998                        | [b2ca3db39f](https://bsd-hardware.info/?probe=b2ca3db39f) | Oct 14, 2024 |
| Unknown       | Unknown                     | [4a3c08470e](https://bsd-hardware.info/?probe=4a3c08470e) | Oct 13, 2024 |
| MSI           | PRO B660-A DDR4             | [79ae56ffec](https://bsd-hardware.info/?probe=79ae56ffec) | Oct 13, 2024 |
| HP            | 240 G3                      | [7e732aa2d4](https://bsd-hardware.info/?probe=7e732aa2d4) | Oct 13, 2024 |
| ASUSTek       | PRIME Z590-A                | [f9dd56fa54](https://bsd-hardware.info/?probe=f9dd56fa54) | Oct 12, 2024 |
| Supermicro    | X10DRD-LT                   | [124b8be193](https://bsd-hardware.info/?probe=124b8be193) | Oct 06, 2024 |
| Unknown       | Unknown                     | [179c36772d](https://bsd-hardware.info/?probe=179c36772d) | Oct 05, 2024 |
| ASRockRack    | X570D4U                     | [9c5e0a312a](https://bsd-hardware.info/?probe=9c5e0a312a) | Oct 03, 2024 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [491f4e42ef](https://bsd-hardware.info/?probe=491f4e42ef) | Oct 01, 2024 |
| Unknown       | Unknown                     | [1a39c09b41](https://bsd-hardware.info/?probe=1a39c09b41) | Sep 30, 2024 |
| nAppliance... | 1500                        | [09b957c33b](https://bsd-hardware.info/?probe=09b957c33b) | Sep 30, 2024 |
| Unknown       | Unknown                     | [3a36dded75](https://bsd-hardware.info/?probe=3a36dded75) | Sep 28, 2024 |
| HP            | 8299                        | [1bd8f99ada](https://bsd-hardware.info/?probe=1bd8f99ada) | Sep 21, 2024 |
| Yanling       | YL-KBR6L Ver:1.00           | [31b6fbf3df](https://bsd-hardware.info/?probe=31b6fbf3df) | Sep 20, 2024 |
| Gigabyte      | F2A78M-D3H                  | [0cf99b87da](https://bsd-hardware.info/?probe=0cf99b87da) | Sep 17, 2024 |
| Protectli     | FW4C                        | [959268ffd3](https://bsd-hardware.info/?probe=959268ffd3) | Sep 17, 2024 |
| Unknown       | QDNV01                      | [cecbc2b072](https://bsd-hardware.info/?probe=cecbc2b072) | Sep 16, 2024 |
| Unknown       | QDNV01                      | [3690166a22](https://bsd-hardware.info/?probe=3690166a22) | Sep 16, 2024 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [0582bbb64f](https://bsd-hardware.info/?probe=0582bbb64f) | Sep 15, 2024 |
| Dell          | 0FDY5C A00                  | [3b04a04ea7](https://bsd-hardware.info/?probe=3b04a04ea7) | Sep 15, 2024 |
| Unknown       | QDNV01                      | [1fef412ac2](https://bsd-hardware.info/?probe=1fef412ac2) | Sep 14, 2024 |
| CWWK          | CW-AD4L-N V1                | [bebc6c82cd](https://bsd-hardware.info/?probe=bebc6c82cd) | Sep 14, 2024 |
| Dell          | 02YYK5 A01                  | [dca469e6a8](https://bsd-hardware.info/?probe=dca469e6a8) | Sep 12, 2024 |
| Intel         | CRESCENTBAY                 | [6920ef8277](https://bsd-hardware.info/?probe=6920ef8277) | Sep 12, 2024 |
| Unknown       | QDNV01                      | [67fec8010a](https://bsd-hardware.info/?probe=67fec8010a) | Sep 11, 2024 |
| Intel         | Q3XXG4-P V1.0               | [065ecd509b](https://bsd-hardware.info/?probe=065ecd509b) | Sep 11, 2024 |
| Unknown       | Unknown                     | [550a7b1162](https://bsd-hardware.info/?probe=550a7b1162) | Sep 10, 2024 |
| Protectli     | FW6 Ver                     | [3caa9e2046](https://bsd-hardware.info/?probe=3caa9e2046) | Sep 06, 2024 |
| Protectli     | FW4C Ver                    | [d50fb2efa3](https://bsd-hardware.info/?probe=d50fb2efa3) | Sep 03, 2024 |
| Unknown       | Unknown                     | [05b9eebec0](https://bsd-hardware.info/?probe=05b9eebec0) | Sep 02, 2024 |
| ASRock        | B660M Pro RS                | [290b2fa373](https://bsd-hardware.info/?probe=290b2fa373) | Sep 02, 2024 |
| AZW           | EQ                          | [bf99b0daf6](https://bsd-hardware.info/?probe=bf99b0daf6) | Sep 01, 2024 |
| Dell          | 00F82W A00                  | [9ba9a303ed](https://bsd-hardware.info/?probe=9ba9a303ed) | Aug 31, 2024 |
| Dell          | 00F82W A00                  | [224b9c1027](https://bsd-hardware.info/?probe=224b9c1027) | Aug 31, 2024 |
| Protectli     | VP2410 10                   | [eb4b450cda](https://bsd-hardware.info/?probe=eb4b450cda) | Aug 28, 2024 |
| Unknown       | Unknown                     | [4d56543ca0](https://bsd-hardware.info/?probe=4d56543ca0) | Aug 25, 2024 |
| ASUSTek       | A88XM-PLUS                  | [e09941d59e](https://bsd-hardware.info/?probe=e09941d59e) | Aug 24, 2024 |
| Techvision    | TVI7309X B0                 | [78040fb9e3](https://bsd-hardware.info/?probe=78040fb9e3) | Aug 22, 2024 |
| HP            | 2AF7                        | [2cd08252ea](https://bsd-hardware.info/?probe=2cd08252ea) | Aug 21, 2024 |
| HP            | 8299                        | [92de0abc13](https://bsd-hardware.info/?probe=92de0abc13) | Aug 17, 2024 |
| ASRock        | B660M Pro RS                | [d8e37c5b01](https://bsd-hardware.info/?probe=d8e37c5b01) | Aug 17, 2024 |
| Gigabyte      | F2A78M-D3H                  | [041e97bc1e](https://bsd-hardware.info/?probe=041e97bc1e) | Aug 16, 2024 |
| Unknown       | Unknown                     | [8f13dfe7cb](https://bsd-hardware.info/?probe=8f13dfe7cb) | Aug 15, 2024 |
| Unknown       | Unknown                     | [6777197334](https://bsd-hardware.info/?probe=6777197334) | Aug 14, 2024 |
| Datto         | SSD                         | [f8c1a103c0](https://bsd-hardware.info/?probe=f8c1a103c0) | Aug 11, 2024 |
| Protectli     | FW4C Ver                    | [e09858028f](https://bsd-hardware.info/?probe=e09858028f) | Aug 10, 2024 |
| Protectli     | FW4C Ver                    | [67ec9dc201](https://bsd-hardware.info/?probe=67ec9dc201) | Aug 10, 2024 |
| Unknown       | Unknown                     | [a5f82b5dbd](https://bsd-hardware.info/?probe=a5f82b5dbd) | Aug 09, 2024 |
| Intel         | HURONRIVER                  | [bf7f6c304a](https://bsd-hardware.info/?probe=bf7f6c304a) | Aug 09, 2024 |
| Unknown       | Unknown                     | [fc78b1147f](https://bsd-hardware.info/?probe=fc78b1147f) | Aug 09, 2024 |
| Unknown       | Unknown                     | [7670afb841](https://bsd-hardware.info/?probe=7670afb841) | Aug 08, 2024 |
| HP            | 8299                        | [e5e9cc0df6](https://bsd-hardware.info/?probe=e5e9cc0df6) | Aug 07, 2024 |
| Unknown       | Unknown                     | [a1528cb0d3](https://bsd-hardware.info/?probe=a1528cb0d3) | Aug 07, 2024 |
| Dell          | 096JG8 A01                  | [d682fa48c5](https://bsd-hardware.info/?probe=d682fa48c5) | Aug 04, 2024 |
| Dell          | 02YYK5 A01                  | [7f6a56bf08](https://bsd-hardware.info/?probe=7f6a56bf08) | Aug 03, 2024 |
| HP            | 3397                        | [05fd710abe](https://bsd-hardware.info/?probe=05fd710abe) | Aug 03, 2024 |
| Protectli     | VP2410 10                   | [d266c08b53](https://bsd-hardware.info/?probe=d266c08b53) | Aug 01, 2024 |
| IceWhale T... | ZBB001-BK10032 ZMB          | [8aaf3047a9](https://bsd-hardware.info/?probe=8aaf3047a9) | Jul 29, 2024 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | [f9686c6fff](https://bsd-hardware.info/?probe=f9686c6fff) | Jul 29, 2024 |
| Dell          | 0NC2VH A01                  | [8c5515b98f](https://bsd-hardware.info/?probe=8c5515b98f) | Jul 28, 2024 |
| Advantech     | NAMB-3250 A102-1            | [44174e94ec](https://bsd-hardware.info/?probe=44174e94ec) | Jul 26, 2024 |
| AAEON         | FWS-7360 V1.0               | [0550dd921d](https://bsd-hardware.info/?probe=0550dd921d) | Jul 26, 2024 |
| Unknown       | Unknown                     | [fb0dbec868](https://bsd-hardware.info/?probe=fb0dbec868) | Jul 26, 2024 |
| Intel         | ARA_101                     | [ebd6211ff3](https://bsd-hardware.info/?probe=ebd6211ff3) | Jul 24, 2024 |
| Unknown       | Unknown                     | [c69b8e10b9](https://bsd-hardware.info/?probe=c69b8e10b9) | Jul 24, 2024 |
| Intel         | ARA_101                     | [85b713b3d2](https://bsd-hardware.info/?probe=85b713b3d2) | Jul 23, 2024 |
| HP            | 8299                        | [b9cd300007](https://bsd-hardware.info/?probe=b9cd300007) | Jul 20, 2024 |
| Supermicro    | X7DVL-3                     | [cee10ef296](https://bsd-hardware.info/?probe=cee10ef296) | Jul 17, 2024 |
| Gigabyte      | H170N-WIFI-CF               | [bd67f35ccd](https://bsd-hardware.info/?probe=bd67f35ccd) | Jul 15, 2024 |
| Unknown       | Unknown                     | [256823a6ee](https://bsd-hardware.info/?probe=256823a6ee) | Jul 14, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [e3a2fdff4a](https://bsd-hardware.info/?probe=e3a2fdff4a) | Jul 10, 2024 |
| Datto         | SSD                         | [389294c8b0](https://bsd-hardware.info/?probe=389294c8b0) | Jul 06, 2024 |
| Unknown       | Unknown                     | [5d2f9d8d66](https://bsd-hardware.info/?probe=5d2f9d8d66) | Jul 03, 2024 |
| Unknown       | Unknown                     | [f0d9518c45](https://bsd-hardware.info/?probe=f0d9518c45) | Jul 01, 2024 |
| Dell          | 0D6H9T A01                  | [23a9feeec7](https://bsd-hardware.info/?probe=23a9feeec7) | Jul 01, 2024 |
| Techvision    | TVI7309X B0                 | [546a2d07dc](https://bsd-hardware.info/?probe=546a2d07dc) | Jun 29, 2024 |
| Techvision    | TVI7309X B0                 | [14cd6d199d](https://bsd-hardware.info/?probe=14cd6d199d) | Jun 29, 2024 |
| Unknown       | Unknown                     | [adce45c28b](https://bsd-hardware.info/?probe=adce45c28b) | Jun 25, 2024 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [cd04d52df4](https://bsd-hardware.info/?probe=cd04d52df4) | Jun 22, 2024 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [c77c97d1e0](https://bsd-hardware.info/?probe=c77c97d1e0) | Jun 21, 2024 |
| Unknown       | Unknown                     | [2be3311d23](https://bsd-hardware.info/?probe=2be3311d23) | Jun 19, 2024 |
| Dell          | 04Y8V0 A02                  | [21542709fd](https://bsd-hardware.info/?probe=21542709fd) | Jun 14, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [be25e51018](https://bsd-hardware.info/?probe=be25e51018) | Jun 14, 2024 |
| CWWK          | CW-J6-6L                    | [4e9a5be822](https://bsd-hardware.info/?probe=4e9a5be822) | Jun 10, 2024 |
| Dell          | 0FDY5C A00                  | [2e262904ee](https://bsd-hardware.info/?probe=2e262904ee) | Jun 09, 2024 |
| HP            | 2820h                       | [34b9baaaa3](https://bsd-hardware.info/?probe=34b9baaaa3) | Jun 09, 2024 |
| Protectli     | VP2420                      | [583f5de601](https://bsd-hardware.info/?probe=583f5de601) | Jun 05, 2024 |
| ASRock        | B760M Pro RS/D4 WiFi        | [17ac843fe5](https://bsd-hardware.info/?probe=17ac843fe5) | Jun 04, 2024 |
| Protectli     | VP2420                      | [8681165799](https://bsd-hardware.info/?probe=8681165799) | Jun 04, 2024 |
| Intel         | HURONRIVER                  | [4db21a39c8](https://bsd-hardware.info/?probe=4db21a39c8) | May 28, 2024 |
| Unknown       | Unknown                     | [6b699387d2](https://bsd-hardware.info/?probe=6b699387d2) | May 28, 2024 |
| Protectli     | FW6 Ver                     | [aeb484129d](https://bsd-hardware.info/?probe=aeb484129d) | May 26, 2024 |
| Gowin Solu... | GW-MB-U01                   | [13a7e9c09f](https://bsd-hardware.info/?probe=13a7e9c09f) | May 26, 2024 |
| Unknown       | Unknown                     | [69cbba291d](https://bsd-hardware.info/?probe=69cbba291d) | May 25, 2024 |
| Intel         | DH77DF AAG40293-301         | [b2a233b34e](https://bsd-hardware.info/?probe=b2a233b34e) | May 24, 2024 |
| HP            | 83EF                        | [6fc0e78390](https://bsd-hardware.info/?probe=6fc0e78390) | May 22, 2024 |
| HP            | 83EF                        | [a384093aeb](https://bsd-hardware.info/?probe=a384093aeb) | May 21, 2024 |
| Cisco         | ASA5515 A0                  | [499d1312aa](https://bsd-hardware.info/?probe=499d1312aa) | May 21, 2024 |
| ShenZhen M... | MW-GMLK-2.5G6L              | [0dd5cac794](https://bsd-hardware.info/?probe=0dd5cac794) | May 21, 2024 |
| Unknown       | Unknown                     | [9f15ecc28d](https://bsd-hardware.info/?probe=9f15ecc28d) | May 20, 2024 |
| Protectli     | VP2420                      | [60008a53d6](https://bsd-hardware.info/?probe=60008a53d6) | May 20, 2024 |
| Unknown       | Unknown                     | [a1ae165075](https://bsd-hardware.info/?probe=a1ae165075) | May 19, 2024 |
| Dell          | 0YNVJG A02                  | [b18650cbc1](https://bsd-hardware.info/?probe=b18650cbc1) | May 18, 2024 |
| Protectli     | FW4C Ver                    | [42351e9058](https://bsd-hardware.info/?probe=42351e9058) | May 18, 2024 |
| Unknown       | Unknown                     | [f5dc64a018](https://bsd-hardware.info/?probe=f5dc64a018) | May 17, 2024 |
| HP            | 83EC                        | [d7d695a59b](https://bsd-hardware.info/?probe=d7d695a59b) | May 16, 2024 |
| Acer          | Aspire XC-603               | [0d17afb0ea](https://bsd-hardware.info/?probe=0d17afb0ea) | May 13, 2024 |
| Unknown       | Unknown                     | [6e55254e9e](https://bsd-hardware.info/?probe=6e55254e9e) | May 11, 2024 |
| Unknown       | QDNV01                      | [8442a13927](https://bsd-hardware.info/?probe=8442a13927) | May 11, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [aaf0e5f12e](https://bsd-hardware.info/?probe=aaf0e5f12e) | May 10, 2024 |
| Unknown       | Unknown                     | [d6164af1c4](https://bsd-hardware.info/?probe=d6164af1c4) | May 08, 2024 |
| Protectli     | VP2420                      | [9c20710e0a](https://bsd-hardware.info/?probe=9c20710e0a) | May 07, 2024 |
| Dell          | 0GU083 A00                  | [fbb75b4cfd](https://bsd-hardware.info/?probe=fbb75b4cfd) | May 07, 2024 |
| Lenovo        | ThinkCentre M58 7360EUU     | [f84d111995](https://bsd-hardware.info/?probe=f84d111995) | May 07, 2024 |
| HP            | 82F2                        | [7ae2683f3b](https://bsd-hardware.info/?probe=7ae2683f3b) | May 06, 2024 |
| HP            | 83EC                        | [85d2a6764b](https://bsd-hardware.info/?probe=85d2a6764b) | May 06, 2024 |
| Protectli     | VP2420                      | [dd7edbac6d](https://bsd-hardware.info/?probe=dd7edbac6d) | May 05, 2024 |
| Techvision    | TVI7309X B0                 | [bfab3dbc5c](https://bsd-hardware.info/?probe=bfab3dbc5c) | May 05, 2024 |
| Techvision    | TVI7309X B0                 | [9dc1dd8248](https://bsd-hardware.info/?probe=9dc1dd8248) | May 04, 2024 |
| Intel         | Q3XXG4-P V1.0               | [ae53040229](https://bsd-hardware.info/?probe=ae53040229) | May 01, 2024 |
| Dell          | 04Y8V0 A02                  | [09a2e96ee1](https://bsd-hardware.info/?probe=09a2e96ee1) | Apr 30, 2024 |
| ASUSTek       | VM62N                       | [d2ff0c5dcb](https://bsd-hardware.info/?probe=d2ff0c5dcb) | Apr 30, 2024 |
| ASUSTek       | VM62N                       | [fbff6f23c7](https://bsd-hardware.info/?probe=fbff6f23c7) | Apr 30, 2024 |
| Unknown       | Unknown                     | [db28c45bdd](https://bsd-hardware.info/?probe=db28c45bdd) | Apr 29, 2024 |
| Dell          | 0D28YY A00                  | [5245da0f7d](https://bsd-hardware.info/?probe=5245da0f7d) | Apr 25, 2024 |
| HP            | 83EF                        | [200bba9baa](https://bsd-hardware.info/?probe=200bba9baa) | Apr 24, 2024 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [f5683de21a](https://bsd-hardware.info/?probe=f5683de21a) | Apr 24, 2024 |
| Gigabyte      | F2A78M-D3H                  | [418bc2727b](https://bsd-hardware.info/?probe=418bc2727b) | Apr 21, 2024 |
| HP            | 8054                        | [a9b96ce9cb](https://bsd-hardware.info/?probe=a9b96ce9cb) | Apr 20, 2024 |
| Intel         | QHSW02                      | [a8a19b8f54](https://bsd-hardware.info/?probe=a8a19b8f54) | Apr 19, 2024 |
| ASUSTek       | PRIME B450M-A               | [967017eda5](https://bsd-hardware.info/?probe=967017eda5) | Apr 17, 2024 |
| ASUSTek       | PRIME B450M-A               | [106f715843](https://bsd-hardware.info/?probe=106f715843) | Apr 17, 2024 |
| HP            | 83EF                        | [2ee23055a9](https://bsd-hardware.info/?probe=2ee23055a9) | Apr 17, 2024 |
| ASUSTek       | Q170M-CM-B                  | [a17c3fa36c](https://bsd-hardware.info/?probe=a17c3fa36c) | Apr 15, 2024 |
| Protectli     | FW6 Ver                     | [857b4091b4](https://bsd-hardware.info/?probe=857b4091b4) | Apr 13, 2024 |
| Gigabyte      | M61SME-S2                   | [f81dc4e9cf](https://bsd-hardware.info/?probe=f81dc4e9cf) | Apr 13, 2024 |
| Protectli     | FW6 Ver                     | [2d1eb66a62](https://bsd-hardware.info/?probe=2d1eb66a62) | Apr 12, 2024 |
| Intel         | CRESCENTBAY                 | [d1624d1e25](https://bsd-hardware.info/?probe=d1624d1e25) | Apr 12, 2024 |
| HP            | 8054                        | [58d6764238](https://bsd-hardware.info/?probe=58d6764238) | Apr 12, 2024 |
| Unknown       | Unknown                     | [34cacdab39](https://bsd-hardware.info/?probe=34cacdab39) | Apr 10, 2024 |
| Intel         | CRESCENTBAY                 | [90b2cd042b](https://bsd-hardware.info/?probe=90b2cd042b) | Apr 09, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [1785ba496b](https://bsd-hardware.info/?probe=1785ba496b) | Apr 06, 2024 |
| Unknown       | Unknown                     | [e8d785de8b](https://bsd-hardware.info/?probe=e8d785de8b) | Apr 05, 2024 |
| Unknown       | Unknown                     | [62068b1ed4](https://bsd-hardware.info/?probe=62068b1ed4) | Apr 04, 2024 |
| Unknown       | Unknown                     | [d5e41d1ea4](https://bsd-hardware.info/?probe=d5e41d1ea4) | Apr 01, 2024 |
| HP            | 2AF7                        | [8cb13ba2dd](https://bsd-hardware.info/?probe=8cb13ba2dd) | Apr 01, 2024 |
| Intel         | Q3XXG4-P V1.0               | [2b4a16ed09](https://bsd-hardware.info/?probe=2b4a16ed09) | Mar 31, 2024 |
| Dell          | 02YYK5 A00                  | [71b7891c15](https://bsd-hardware.info/?probe=71b7891c15) | Mar 30, 2024 |
| Intel         | HURONRIVER                  | [ffb33037f0](https://bsd-hardware.info/?probe=ffb33037f0) | Mar 30, 2024 |
| CWWK          | CW-J6-6L                    | [6a580f72b7](https://bsd-hardware.info/?probe=6a580f72b7) | Mar 29, 2024 |
| Cisco         | ASA5515 A0                  | [388651c40c](https://bsd-hardware.info/?probe=388651c40c) | Mar 25, 2024 |
| Unknown       | Unknown                     | [279f43500b](https://bsd-hardware.info/?probe=279f43500b) | Mar 24, 2024 |
| Intel         | HURONRIVER                  | [9f0e110842](https://bsd-hardware.info/?probe=9f0e110842) | Mar 23, 2024 |
| AZW           | U59                         | [29801da3e0](https://bsd-hardware.info/?probe=29801da3e0) | Mar 23, 2024 |
| Shuttle       | FS110                       | [aa28a08ad7](https://bsd-hardware.info/?probe=aa28a08ad7) | Mar 22, 2024 |
| HP            | 8463                        | [456e0b53f4](https://bsd-hardware.info/?probe=456e0b53f4) | Mar 20, 2024 |
| HP            | 8463                        | [d67894bfa4](https://bsd-hardware.info/?probe=d67894bfa4) | Mar 19, 2024 |
| Unknown       | QDNV01                      | [4124e1bef1](https://bsd-hardware.info/?probe=4124e1bef1) | Mar 10, 2024 |
| CWWK          | CW-AD4L-N V1                | [e91479e465](https://bsd-hardware.info/?probe=e91479e465) | Mar 09, 2024 |
| Unknown       | Unknown                     | [141c3789a2](https://bsd-hardware.info/?probe=141c3789a2) | Mar 08, 2024 |
| Dell          | 0DR845                      | [a3804072b5](https://bsd-hardware.info/?probe=a3804072b5) | Mar 07, 2024 |
| Unknown       | Unknown                     | [c9ebb09276](https://bsd-hardware.info/?probe=c9ebb09276) | Mar 05, 2024 |
| Protectli     | FW4B Ver                    | [dad601a64c](https://bsd-hardware.info/?probe=dad601a64c) | Mar 04, 2024 |
| Dell          | 042P49 A01                  | [b24a497ab1](https://bsd-hardware.info/?probe=b24a497ab1) | Mar 03, 2024 |
| Dell          | 042P49 A02                  | [d62bbe129d](https://bsd-hardware.info/?probe=d62bbe129d) | Mar 02, 2024 |
| ASUSTek       | PRIME B450M-A II            | [135b118253](https://bsd-hardware.info/?probe=135b118253) | Feb 29, 2024 |
| AAEON         | FWS-7360 V1.0               | [4daf0c2235](https://bsd-hardware.info/?probe=4daf0c2235) | Feb 28, 2024 |
| Unknown       | Unknown                     | [7812ced225](https://bsd-hardware.info/?probe=7812ced225) | Feb 28, 2024 |
| PC Engines    | APU                         | [c9d3a23102](https://bsd-hardware.info/?probe=c9d3a23102) | Feb 26, 2024 |
| ASUSTek       | M2R32-MVP                   | [2005a04811](https://bsd-hardware.info/?probe=2005a04811) | Feb 24, 2024 |
| ASUSTek       | M2R32-MVP                   | [ba4b5e4ca2](https://bsd-hardware.info/?probe=ba4b5e4ca2) | Feb 24, 2024 |
| Unknown       | QGLK03                      | [60754462ad](https://bsd-hardware.info/?probe=60754462ad) | Feb 23, 2024 |
| nAppliance... | 1500                        | [4949e2f018](https://bsd-hardware.info/?probe=4949e2f018) | Feb 22, 2024 |
| nAppliance... | 1500                        | [7b02cef314](https://bsd-hardware.info/?probe=7b02cef314) | Feb 22, 2024 |
| Dell          | 02YYK5 A01                  | [2d6e76f00a](https://bsd-hardware.info/?probe=2d6e76f00a) | Feb 22, 2024 |
| Unknown       | Unknown                     | [a0d3a7768a](https://bsd-hardware.info/?probe=a0d3a7768a) | Feb 20, 2024 |
| Dell          | 0FDY5C A00                  | [bf127b1a87](https://bsd-hardware.info/?probe=bf127b1a87) | Feb 19, 2024 |
| Trigkey       | Green G5                    | [1885276907](https://bsd-hardware.info/?probe=1885276907) | Feb 18, 2024 |
| Unknown       | Unknown                     | [f538dbde64](https://bsd-hardware.info/?probe=f538dbde64) | Feb 18, 2024 |
| Unknown       | Unknown                     | [253de9e3cc](https://bsd-hardware.info/?probe=253de9e3cc) | Feb 18, 2024 |
| CWWK          | CW-AD4L-N V1                | [6f933374c6](https://bsd-hardware.info/?probe=6f933374c6) | Feb 18, 2024 |
| CWWK          | CW-AD4L-N V1                | [45450ec330](https://bsd-hardware.info/?probe=45450ec330) | Feb 18, 2024 |
| ASRock        | B450M Pro4 R2.0             | [007b93e5c0](https://bsd-hardware.info/?probe=007b93e5c0) | Feb 18, 2024 |
| Unknown       | Unknown                     | [2926d6511f](https://bsd-hardware.info/?probe=2926d6511f) | Feb 17, 2024 |
| Lenovo        | 30D9 No DPK                 | [9c3c1f4f5d](https://bsd-hardware.info/?probe=9c3c1f4f5d) | Feb 16, 2024 |
| HP            | 304Bh                       | [d121a7198f](https://bsd-hardware.info/?probe=d121a7198f) | Feb 16, 2024 |
| BOSGAME       | DNB10M                      | [58f2362bf1](https://bsd-hardware.info/?probe=58f2362bf1) | Feb 16, 2024 |
| Unknown       | Unknown                     | [c2a87f002c](https://bsd-hardware.info/?probe=c2a87f002c) | Feb 14, 2024 |
| AZW           | EQ                          | [1f6f07cd11](https://bsd-hardware.info/?probe=1f6f07cd11) | Feb 12, 2024 |
| Intel         | HURONRIVER                  | [fd049a80db](https://bsd-hardware.info/?probe=fd049a80db) | Feb 10, 2024 |
| CWWK          | CW-J6-6L                    | [d859437053](https://bsd-hardware.info/?probe=d859437053) | Feb 10, 2024 |
| Intel         | Q3XXG4-P V1.0               | [34d8f9b987](https://bsd-hardware.info/?probe=34d8f9b987) | Feb 08, 2024 |
| Lenovo        | ThinkCentre M90p 3853RN9    | [c0395ca728](https://bsd-hardware.info/?probe=c0395ca728) | Feb 05, 2024 |
| Intel         | MAHOBAY                     | [e2eba982ad](https://bsd-hardware.info/?probe=e2eba982ad) | Feb 04, 2024 |
| Dell          | 00V62H A01                  | [dc3e12bf24](https://bsd-hardware.info/?probe=dc3e12bf24) | Feb 02, 2024 |
| Unknown       | Unknown                     | [925a562542](https://bsd-hardware.info/?probe=925a562542) | Feb 01, 2024 |
| ASRock        | B450M Pro4                  | [6d300ab2b6](https://bsd-hardware.info/?probe=6d300ab2b6) | Jan 31, 2024 |
| Unknown       | Unknown                     | [85ef70c2a7](https://bsd-hardware.info/?probe=85ef70c2a7) | Jan 30, 2024 |
| AZW           | EQ                          | [d278cdacc7](https://bsd-hardware.info/?probe=d278cdacc7) | Jan 26, 2024 |
| HP            | 8054                        | [1c2827051e](https://bsd-hardware.info/?probe=1c2827051e) | Jan 25, 2024 |
| ASUSTek       | M5A97 PLUS                  | [d4b4d2b0a5](https://bsd-hardware.info/?probe=d4b4d2b0a5) | Jan 23, 2024 |
| Lenovo        | 30D9 No DPK                 | [96a7f8e15d](https://bsd-hardware.info/?probe=96a7f8e15d) | Jan 23, 2024 |
| HP            | 2AF7                        | [b1eaa55d6c](https://bsd-hardware.info/?probe=b1eaa55d6c) | Jan 23, 2024 |
| Lenovo        | SHARKBAY NOK                | [504b40ca9a](https://bsd-hardware.info/?probe=504b40ca9a) | Jan 22, 2024 |
| Gigabyte      | H87-D3H-CF                  | [60fb8ff088](https://bsd-hardware.info/?probe=60fb8ff088) | Jan 21, 2024 |
| Dell          | 0YNVJG A02                  | [7c9f213d88](https://bsd-hardware.info/?probe=7c9f213d88) | Jan 20, 2024 |
| MSI           | PRO Z790-A WIFI DDR4        | [e52e1e182e](https://bsd-hardware.info/?probe=e52e1e182e) | Jan 20, 2024 |
| Supermicro    | A2SDi-4C-HLN4F              | [4f4dd028ff](https://bsd-hardware.info/?probe=4f4dd028ff) | Jan 19, 2024 |
| MSI           | PRO B660-A DDR4             | [494e5ac9b0](https://bsd-hardware.info/?probe=494e5ac9b0) | Jan 19, 2024 |
| Unknown       | Unknown                     | [3d15f64540](https://bsd-hardware.info/?probe=3d15f64540) | Jan 16, 2024 |
| HP            | 8054                        | [b9a3ce8513](https://bsd-hardware.info/?probe=b9a3ce8513) | Jan 15, 2024 |
| ASUSTek       | Q87M-E                      | [47ef5800dc](https://bsd-hardware.info/?probe=47ef5800dc) | Jan 11, 2024 |
| ASUSTek       | Q87M-E                      | [330076d1ca](https://bsd-hardware.info/?probe=330076d1ca) | Jan 10, 2024 |
| Yanling       | YL-KBR6L Ver:1.00           | [f94d6ea323](https://bsd-hardware.info/?probe=f94d6ea323) | Jan 08, 2024 |
| Yanling       | YL-KBR6L Ver:1.00           | [b594cce427](https://bsd-hardware.info/?probe=b594cce427) | Jan 07, 2024 |
| Unknown       | Unknown                     | [0ebacb4707](https://bsd-hardware.info/?probe=0ebacb4707) | Jan 07, 2024 |
| HP            | 304Bh                       | [08b5bc9dc7](https://bsd-hardware.info/?probe=08b5bc9dc7) | Jan 05, 2024 |
| ASUSTek       | PRIME B450M-A               | [1c7bbcc0ca](https://bsd-hardware.info/?probe=1c7bbcc0ca) | Jan 01, 2024 |
| ASUSTek       | PRIME B450M-A               | [6f996518f6](https://bsd-hardware.info/?probe=6f996518f6) | Dec 30, 2023 |
| Dell          | 0F3KHR A02                  | [572ad429ae](https://bsd-hardware.info/?probe=572ad429ae) | Dec 30, 2023 |
| Dell          | 0GU083 A00                  | [caaa806343](https://bsd-hardware.info/?probe=caaa806343) | Dec 28, 2023 |
| AZW           | Green G1                    | [c5bd9604b5](https://bsd-hardware.info/?probe=c5bd9604b5) | Dec 28, 2023 |
| HP            | 304Bh                       | [52ee1947b1](https://bsd-hardware.info/?probe=52ee1947b1) | Dec 27, 2023 |
| ASUSTek       | B150M-A D3                  | [d416ce02f1](https://bsd-hardware.info/?probe=d416ce02f1) | Dec 26, 2023 |
| Intel         | SHARKBAY                    | [0ec70893dd](https://bsd-hardware.info/?probe=0ec70893dd) | Dec 24, 2023 |
| Unknown       | Unknown                     | [4f79ea6f3a](https://bsd-hardware.info/?probe=4f79ea6f3a) | Dec 23, 2023 |
| Unknown       | Unknown                     | [684d183b51](https://bsd-hardware.info/?probe=684d183b51) | Dec 23, 2023 |
| Gigabyte      | MRZNVMS-00                  | [7c9af3e3cd](https://bsd-hardware.info/?probe=7c9af3e3cd) | Dec 23, 2023 |
| Unknown       | Unknown                     | [1a68705919](https://bsd-hardware.info/?probe=1a68705919) | Dec 23, 2023 |
| ASUSTek       | PRIME A320M-K               | [cfe1ed1212](https://bsd-hardware.info/?probe=cfe1ed1212) | Dec 22, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [dbcb26f795](https://bsd-hardware.info/?probe=dbcb26f795) | Dec 22, 2023 |
| HP            | 83F2                        | [858392467f](https://bsd-hardware.info/?probe=858392467f) | Dec 19, 2023 |
| HP            | 83F2                        | [8b1e24b86c](https://bsd-hardware.info/?probe=8b1e24b86c) | Dec 19, 2023 |
| Intel         | JSL MRD                     | [af718ee605](https://bsd-hardware.info/?probe=af718ee605) | Dec 17, 2023 |
| Unknown       | Unknown                     | [be79d227b2](https://bsd-hardware.info/?probe=be79d227b2) | Dec 15, 2023 |
| Gigabyte      | B75N                        | [dad5d14cf7](https://bsd-hardware.info/?probe=dad5d14cf7) | Dec 15, 2023 |
| Protectli     | FW4B Ver                    | [da6ac13ef2](https://bsd-hardware.info/?probe=da6ac13ef2) | Dec 15, 2023 |
| AZW           | EQ                          | [d83e11a7dc](https://bsd-hardware.info/?probe=d83e11a7dc) | Dec 13, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [67f5c9c912](https://bsd-hardware.info/?probe=67f5c9c912) | Dec 13, 2023 |
| Unknown       | Unknown                     | [5597d71956](https://bsd-hardware.info/?probe=5597d71956) | Dec 09, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [25f4e4ce18](https://bsd-hardware.info/?probe=25f4e4ce18) | Dec 09, 2023 |
| Protectli     | FW4B Ver                    | [55c513d023](https://bsd-hardware.info/?probe=55c513d023) | Dec 08, 2023 |
| ADI Engine... | RCC-VE                      | [b362c84d66](https://bsd-hardware.info/?probe=b362c84d66) | Dec 07, 2023 |
| Unknown       | Unknown                     | [d837d27d35](https://bsd-hardware.info/?probe=d837d27d35) | Dec 02, 2023 |
| AZW           | EQ                          | [e4b294ddda](https://bsd-hardware.info/?probe=e4b294ddda) | Nov 29, 2023 |
| Dell          | 0NC2VH A01                  | [938720f5a3](https://bsd-hardware.info/?probe=938720f5a3) | Nov 26, 2023 |
| Dell          | 0NC2VH A01                  | [5e87df1001](https://bsd-hardware.info/?probe=5e87df1001) | Nov 25, 2023 |
| ADI Engine... | RCC-VE                      | [437a91ad78](https://bsd-hardware.info/?probe=437a91ad78) | Nov 25, 2023 |
| Lenovo        | ThinkCentre M90n-1 11AHS... | [eca5b59407](https://bsd-hardware.info/?probe=eca5b59407) | Nov 23, 2023 |
| HP            | 0B40h                       | [035db0e1c5](https://bsd-hardware.info/?probe=035db0e1c5) | Nov 23, 2023 |
| HP            | 0B40h                       | [559cfb4b40](https://bsd-hardware.info/?probe=559cfb4b40) | Nov 23, 2023 |
| Protectli     | FW4B Ver                    | [3738ed9dd2](https://bsd-hardware.info/?probe=3738ed9dd2) | Nov 21, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [fe1688477a](https://bsd-hardware.info/?probe=fe1688477a) | Nov 21, 2023 |
| PC Engines    | APU                         | [53fd63efac](https://bsd-hardware.info/?probe=53fd63efac) | Nov 21, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [95d2a9f59c](https://bsd-hardware.info/?probe=95d2a9f59c) | Nov 21, 2023 |
| Unknown       | Unknown                     | [a3d67285a6](https://bsd-hardware.info/?probe=a3d67285a6) | Nov 19, 2023 |
| Dell          | 0NC2VH A01                  | [83673368b9](https://bsd-hardware.info/?probe=83673368b9) | Nov 17, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [2bc7167601](https://bsd-hardware.info/?probe=2bc7167601) | Nov 17, 2023 |
| Unknown       | Unknown                     | [7c541b6943](https://bsd-hardware.info/?probe=7c541b6943) | Nov 13, 2023 |
| Techvision    | TVI7309X B0                 | [c5d3028f45](https://bsd-hardware.info/?probe=c5d3028f45) | Nov 12, 2023 |
| Techvision    | TVI7309X B0                 | [10dadfc527](https://bsd-hardware.info/?probe=10dadfc527) | Nov 12, 2023 |
| Dell          | 0HHV7N A00                  | [a1f74c50b5](https://bsd-hardware.info/?probe=a1f74c50b5) | Nov 12, 2023 |
| CheckPoint    | T-180-00                    | [9ee64c3012](https://bsd-hardware.info/?probe=9ee64c3012) | Nov 11, 2023 |
| Protectli     | VP2420                      | [607a661b45](https://bsd-hardware.info/?probe=607a661b45) | Nov 08, 2023 |
| Dell          | 0NC2VH A01                  | [0d6203b7c9](https://bsd-hardware.info/?probe=0d6203b7c9) | Nov 07, 2023 |
| MW            | GMLK-2_5G4L                 | [4fe0f6ef5e](https://bsd-hardware.info/?probe=4fe0f6ef5e) | Nov 05, 2023 |
| Unknown       | Unknown                     | [1a820d6364](https://bsd-hardware.info/?probe=1a820d6364) | Nov 05, 2023 |
| Unknown       | Unknown                     | [25d85a53af](https://bsd-hardware.info/?probe=25d85a53af) | Nov 03, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [ade254cf11](https://bsd-hardware.info/?probe=ade254cf11) | Nov 01, 2023 |
| Dell          | 0NC2VH A01                  | [db40304707](https://bsd-hardware.info/?probe=db40304707) | Oct 31, 2023 |
| Dell          | 0XHGV1 A00                  | [a688954dd5](https://bsd-hardware.info/?probe=a688954dd5) | Oct 31, 2023 |
| Dell          | 0NC2VH A01                  | [e69fadd7a8](https://bsd-hardware.info/?probe=e69fadd7a8) | Oct 29, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [558a8a885e](https://bsd-hardware.info/?probe=558a8a885e) | Oct 22, 2023 |
| Dell          | 0WR7PY A01                  | [7e2e07f641](https://bsd-hardware.info/?probe=7e2e07f641) | Oct 20, 2023 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [a12be87189](https://bsd-hardware.info/?probe=a12be87189) | Oct 17, 2023 |
| Intel         | B75                         | [baead94277](https://bsd-hardware.info/?probe=baead94277) | Oct 14, 2023 |
| Dell          | 0NC2VH A01                  | [916de10c11](https://bsd-hardware.info/?probe=916de10c11) | Oct 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | [c07dd3b911](https://bsd-hardware.info/?probe=c07dd3b911) | Oct 09, 2023 |
| Unknown       | Unknown                     | [a2a905898b](https://bsd-hardware.info/?probe=a2a905898b) | Oct 08, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [39894be424](https://bsd-hardware.info/?probe=39894be424) | Oct 07, 2023 |
| Unknown       | Unknown                     | [04dbabbf69](https://bsd-hardware.info/?probe=04dbabbf69) | Oct 06, 2023 |
| Techvision    | TVI7309X B0                 | [febaed1e4e](https://bsd-hardware.info/?probe=febaed1e4e) | Oct 03, 2023 |
| Dell          | 0NC2VH A01                  | [b957ce880e](https://bsd-hardware.info/?probe=b957ce880e) | Oct 01, 2023 |
| Dell          | 0GU083 A00                  | [1286478dc2](https://bsd-hardware.info/?probe=1286478dc2) | Oct 01, 2023 |
| Supermicro    | A2SDi-TP8F                  | [9a73be8c9c](https://bsd-hardware.info/?probe=9a73be8c9c) | Sep 30, 2023 |
| HP            | 82B4                        | [60d259ab3f](https://bsd-hardware.info/?probe=60d259ab3f) | Sep 29, 2023 |
| Unknown       | Unknown                     | [df07570acc](https://bsd-hardware.info/?probe=df07570acc) | Sep 28, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [0f20928f2d](https://bsd-hardware.info/?probe=0f20928f2d) | Sep 28, 2023 |
| HP            | 18E5                        | [9c21b6e355](https://bsd-hardware.info/?probe=9c21b6e355) | Sep 25, 2023 |
| Unknown       | Unknown                     | [05f45ba264](https://bsd-hardware.info/?probe=05f45ba264) | Sep 25, 2023 |
| HP            | 18E5                        | [02b94adef6](https://bsd-hardware.info/?probe=02b94adef6) | Sep 22, 2023 |
| ASRockRack    | X470D4U2-2T                 | [5a0b8eb786](https://bsd-hardware.info/?probe=5a0b8eb786) | Sep 21, 2023 |
| ASRock        | B450 Pro4                   | [211b0f3e9c](https://bsd-hardware.info/?probe=211b0f3e9c) | Sep 19, 2023 |
| CncTion       | Jasper-4L B0                | [96f81e84f6](https://bsd-hardware.info/?probe=96f81e84f6) | Sep 18, 2023 |
| Techvision    | TVI7309X B0                 | [7b6014f65f](https://bsd-hardware.info/?probe=7b6014f65f) | Sep 18, 2023 |
| CncTion       | Jasper-4L B0                | [4254b5eac8](https://bsd-hardware.info/?probe=4254b5eac8) | Sep 17, 2023 |
| ASRock        | B450M Pro4-F                | [b6763a8d49](https://bsd-hardware.info/?probe=b6763a8d49) | Sep 17, 2023 |
| Unknown       | Unknown                     | [0fccf590d4](https://bsd-hardware.info/?probe=0fccf590d4) | Sep 12, 2023 |
| Unknown       | Unknown                     | [7c53ad8bea](https://bsd-hardware.info/?probe=7c53ad8bea) | Sep 10, 2023 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | [5695984890](https://bsd-hardware.info/?probe=5695984890) | Sep 10, 2023 |
| ASUSTek       | P8H67-M PRO                 | [7e4ea56868](https://bsd-hardware.info/?probe=7e4ea56868) | Sep 10, 2023 |
| ASUSTek       | P8H67-M PRO                 | [ee34cb0b60](https://bsd-hardware.info/?probe=ee34cb0b60) | Sep 10, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [93234978cf](https://bsd-hardware.info/?probe=93234978cf) | Sep 09, 2023 |
| Dell          | 0NC2VH A01                  | [34a855cc56](https://bsd-hardware.info/?probe=34a855cc56) | Sep 06, 2023 |
| Unknown       | Unknown                     | [19711ca08b](https://bsd-hardware.info/?probe=19711ca08b) | Sep 06, 2023 |
| ASUSTek       | P8H67-M PRO                 | [c06ec95a55](https://bsd-hardware.info/?probe=c06ec95a55) | Sep 06, 2023 |
| Dell          | 0NC2VH A01                  | [7209f86fed](https://bsd-hardware.info/?probe=7209f86fed) | Sep 04, 2023 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | [a1c29072ea](https://bsd-hardware.info/?probe=a1c29072ea) | Sep 03, 2023 |
| Protectli     | FW6 Ver                     | [70992eb19b](https://bsd-hardware.info/?probe=70992eb19b) | Sep 02, 2023 |
| ASUSTek       | M5A97 PLUS                  | [77b461d3ad](https://bsd-hardware.info/?probe=77b461d3ad) | Sep 02, 2023 |
| Dell          | 042P49 A01                  | [383445ee26](https://bsd-hardware.info/?probe=383445ee26) | Sep 01, 2023 |
| Protectli     | FW6 Ver                     | [04de7aa059](https://bsd-hardware.info/?probe=04de7aa059) | Sep 01, 2023 |
| Dell          | 042P49 A01                  | [a06ab2449f](https://bsd-hardware.info/?probe=a06ab2449f) | Aug 26, 2023 |
| PC Engines    | APU2                        | [ed6839f08c](https://bsd-hardware.info/?probe=ed6839f08c) | Aug 26, 2023 |
| Dell          | 0NC2VH A01                  | [46499d5075](https://bsd-hardware.info/?probe=46499d5075) | Aug 26, 2023 |
| Unknown       | Unknown                     | [6619af0a29](https://bsd-hardware.info/?probe=6619af0a29) | Aug 26, 2023 |
| Unknown       | Unknown                     | [aad81c60fa](https://bsd-hardware.info/?probe=aad81c60fa) | Aug 25, 2023 |
| Dell          | 0KHP4K A03                  | [c54db98574](https://bsd-hardware.info/?probe=c54db98574) | Aug 22, 2023 |
| Dell          | 0KHP4K A03                  | [dd1ad7af32](https://bsd-hardware.info/?probe=dd1ad7af32) | Aug 22, 2023 |
| Protectli     | VP2420                      | [c033157bb2](https://bsd-hardware.info/?probe=c033157bb2) | Aug 22, 2023 |
| Lenovo        | ThinkCentre M90p 3853RN9    | [818c1b5f31](https://bsd-hardware.info/?probe=818c1b5f31) | Aug 20, 2023 |
| Dell          | 04Y8V0 A02                  | [8f26de2199](https://bsd-hardware.info/?probe=8f26de2199) | Aug 19, 2023 |
| Dell          | 0NC2VH A01                  | [7ea90d38d1](https://bsd-hardware.info/?probe=7ea90d38d1) | Aug 18, 2023 |
| ASRock        | B450 Pro4                   | [c12a76c083](https://bsd-hardware.info/?probe=c12a76c083) | Aug 16, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [08061905f7](https://bsd-hardware.info/?probe=08061905f7) | Aug 15, 2023 |
| Dell          | 00VTMF A01                  | [399fe2224c](https://bsd-hardware.info/?probe=399fe2224c) | Aug 13, 2023 |
| Dell          | 0NC2VH A01                  | [0fd996a147](https://bsd-hardware.info/?probe=0fd996a147) | Aug 10, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [a22e406f7c](https://bsd-hardware.info/?probe=a22e406f7c) | Aug 10, 2023 |
| Dell          | 04Y8V0 A02                  | [c693116826](https://bsd-hardware.info/?probe=c693116826) | Aug 09, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [0c9251a971](https://bsd-hardware.info/?probe=0c9251a971) | Aug 09, 2023 |
| ASUSTek       | M4A88TD-M/USB3              | [ce95634a53](https://bsd-hardware.info/?probe=ce95634a53) | Aug 06, 2023 |
| Protectli     | VP2420                      | [2ec2033d58](https://bsd-hardware.info/?probe=2ec2033d58) | Aug 01, 2023 |
| HP            | 2AF7                        | [fc495dc6c7](https://bsd-hardware.info/?probe=fc495dc6c7) | Jul 29, 2023 |
| AZW           | U59                         | [1862cfda96](https://bsd-hardware.info/?probe=1862cfda96) | Jul 23, 2023 |
| Dell          | 0F3KHR A02                  | [8c9dfc9396](https://bsd-hardware.info/?probe=8c9dfc9396) | Jul 23, 2023 |
| AZW           | EQ                          | [b96b847399](https://bsd-hardware.info/?probe=b96b847399) | Jul 20, 2023 |
| Techvision    | TVI7309X B0                 | [3e853472dc](https://bsd-hardware.info/?probe=3e853472dc) | Jul 19, 2023 |
| Dell          | 04Y8V0 A02                  | [738b473ab6](https://bsd-hardware.info/?probe=738b473ab6) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [f58fdceed1](https://bsd-hardware.info/?probe=f58fdceed1) | Jul 18, 2023 |
| Unknown       | Unknown                     | [cfdbed124e](https://bsd-hardware.info/?probe=cfdbed124e) | Jul 17, 2023 |
| Dell          | 0F3KHR A02                  | [e1647604a7](https://bsd-hardware.info/?probe=e1647604a7) | Jul 15, 2023 |
| ASUSTek       | Rampage III Extreme         | [499e5b7941](https://bsd-hardware.info/?probe=499e5b7941) | Jul 14, 2023 |
| HP            | 2AF7                        | [a983dd41d6](https://bsd-hardware.info/?probe=a983dd41d6) | Jul 13, 2023 |
| Techvision    | TVI7309X B0                 | [6db56ee0ef](https://bsd-hardware.info/?probe=6db56ee0ef) | Jul 13, 2023 |
| AZW           | U59                         | [20a3b64ecd](https://bsd-hardware.info/?probe=20a3b64ecd) | Jul 10, 2023 |
| MW            | GMLK-2_5G4L                 | [bbef95a882](https://bsd-hardware.info/?probe=bbef95a882) | Jul 08, 2023 |
| Intel         | CRESCENTBAY                 | [933187d501](https://bsd-hardware.info/?probe=933187d501) | Jul 08, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [76cfc2c80e](https://bsd-hardware.info/?probe=76cfc2c80e) | Jul 07, 2023 |
| Intel         | DQ67SW AAG12527-310         | [e36e748937](https://bsd-hardware.info/?probe=e36e748937) | Jul 06, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [9d6fef9445](https://bsd-hardware.info/?probe=9d6fef9445) | Jul 04, 2023 |
| MW            | GMLK-2_5G4L                 | [1ef9818928](https://bsd-hardware.info/?probe=1ef9818928) | Jun 27, 2023 |
| HP            | 1495                        | [564ff2ef77](https://bsd-hardware.info/?probe=564ff2ef77) | Jun 26, 2023 |
| Lenovo        | ThinkCentre M55 880894U     | [e406083f25](https://bsd-hardware.info/?probe=e406083f25) | Jun 22, 2023 |
| Techvision    | TVI7309X B0                 | [0b667bc4e7](https://bsd-hardware.info/?probe=0b667bc4e7) | Jun 22, 2023 |
| ASUSTek       | M5A97 PLUS                  | [39e7195baf](https://bsd-hardware.info/?probe=39e7195baf) | Jun 15, 2023 |
| Protectli     | FW4B Ver                    | [3484cbbf9f](https://bsd-hardware.info/?probe=3484cbbf9f) | Jun 14, 2023 |
| Techvision    | TVI7309X B0                 | [080be9d6f5](https://bsd-hardware.info/?probe=080be9d6f5) | Jun 13, 2023 |
| Unknown       | Unknown                     | [88a421e275](https://bsd-hardware.info/?probe=88a421e275) | Jun 10, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [48833ba1a3](https://bsd-hardware.info/?probe=48833ba1a3) | Jun 08, 2023 |
| Protectli     | VP2420                      | [45e550e09f](https://bsd-hardware.info/?probe=45e550e09f) | Jun 07, 2023 |
| Intel         | Q3XXG4-P V1.0               | [f0f13f5cea](https://bsd-hardware.info/?probe=f0f13f5cea) | Jun 06, 2023 |
| HP            | 1495                        | [a7a24624d7](https://bsd-hardware.info/?probe=a7a24624d7) | Jun 05, 2023 |
| Protectli     | FW4B Ver                    | [5fc38b17d3](https://bsd-hardware.info/?probe=5fc38b17d3) | Jun 04, 2023 |
| Techvision    | TVI7309X B0                 | [5be94420c2](https://bsd-hardware.info/?probe=5be94420c2) | Jun 02, 2023 |
| Techvision    | TVI7309X B0                 | [ed0c6cf73c](https://bsd-hardware.info/?probe=ed0c6cf73c) | May 31, 2023 |
| Unknown       | Unknown                     | [88e6cd10c6](https://bsd-hardware.info/?probe=88e6cd10c6) | May 27, 2023 |
| Protectli     | FW4B                        | [c5c9276f48](https://bsd-hardware.info/?probe=c5c9276f48) | May 27, 2023 |
| ASRockRack    | X470D4U2-2T                 | [e782ceaea8](https://bsd-hardware.info/?probe=e782ceaea8) | May 19, 2023 |
| MSI           | B450I GAMING PLUS AC        | [cc4c36977f](https://bsd-hardware.info/?probe=cc4c36977f) | May 18, 2023 |
| MSI           | B450I GAMING PLUS AC        | [432b2a27c3](https://bsd-hardware.info/?probe=432b2a27c3) | May 13, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [dcea67b6a6](https://bsd-hardware.info/?probe=dcea67b6a6) | May 08, 2023 |
| Lenovo        | ThinkCentre M58 7360EUU     | [b0c462fbd5](https://bsd-hardware.info/?probe=b0c462fbd5) | May 02, 2023 |
| Unknown       | Unknown                     | [73f9fac4f8](https://bsd-hardware.info/?probe=73f9fac4f8) | May 01, 2023 |
| iBASE         | Mi956                       | [e2c1e52a68](https://bsd-hardware.info/?probe=e2c1e52a68) | Apr 29, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [8acf41eb6b](https://bsd-hardware.info/?probe=8acf41eb6b) | Apr 28, 2023 |
| iBASE         | Mi956                       | [cb08976732](https://bsd-hardware.info/?probe=cb08976732) | Apr 27, 2023 |
| Intel         | CRESCENTBAY                 | [b32c8cbec8](https://bsd-hardware.info/?probe=b32c8cbec8) | Apr 27, 2023 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [8476daf227](https://bsd-hardware.info/?probe=8476daf227) | Apr 27, 2023 |
| Techvision    | TVI7309X B0                 | [dcacaf8c50](https://bsd-hardware.info/?probe=dcacaf8c50) | Apr 26, 2023 |
| HP            | 1998                        | [41b5bbe52c](https://bsd-hardware.info/?probe=41b5bbe52c) | Apr 26, 2023 |
| Protectli     | FW4B                        | [111e2f7b3b](https://bsd-hardware.info/?probe=111e2f7b3b) | Apr 25, 2023 |
| Unknown       | Unknown                     | [389267d68d](https://bsd-hardware.info/?probe=389267d68d) | Apr 24, 2023 |
| Lenovo        | ThinkCentre M57p 6073ATU    | [b1e7583e6b](https://bsd-hardware.info/?probe=b1e7583e6b) | Apr 24, 2023 |
| Dell          | 04Y8V0 A02                  | [24379ebf10](https://bsd-hardware.info/?probe=24379ebf10) | Apr 20, 2023 |
| Dell          | 09KPNV A01                  | [cf533da9bf](https://bsd-hardware.info/?probe=cf533da9bf) | Apr 16, 2023 |
| Pegatron      | 2A72h                       | [142340aed4](https://bsd-hardware.info/?probe=142340aed4) | Apr 15, 2023 |
| iBASE         | Mi956                       | [0d4d63b29b](https://bsd-hardware.info/?probe=0d4d63b29b) | Apr 14, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [8e77aee0e0](https://bsd-hardware.info/?probe=8e77aee0e0) | Apr 14, 2023 |
| Protectli     | FW4B Ver                    | [d2f19cb660](https://bsd-hardware.info/?probe=d2f19cb660) | Apr 13, 2023 |
| HP            | 3397                        | [cf2d152bee](https://bsd-hardware.info/?probe=cf2d152bee) | Apr 13, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [e6c9c37b02](https://bsd-hardware.info/?probe=e6c9c37b02) | Apr 13, 2023 |
| AMI           | Cherry Trail CR             | [ce3072c27a](https://bsd-hardware.info/?probe=ce3072c27a) | Apr 05, 2023 |
| ASUSTek       | M5A97 PLUS                  | [9418e51f7e](https://bsd-hardware.info/?probe=9418e51f7e) | Apr 03, 2023 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | [3bb60897ff](https://bsd-hardware.info/?probe=3bb60897ff) | Apr 01, 2023 |
| Alienware     | 049PDM A00                  | [139d115cdb](https://bsd-hardware.info/?probe=139d115cdb) | Mar 29, 2023 |
| Lenovo        | ThinkCentre M58 7360EUU     | [b86ffef220](https://bsd-hardware.info/?probe=b86ffef220) | Mar 28, 2023 |
| Acer          | WG43M                       | [c8f2a03a08](https://bsd-hardware.info/?probe=c8f2a03a08) | Mar 27, 2023 |
| Acer          | WG43M                       | [5e154dc7cf](https://bsd-hardware.info/?probe=5e154dc7cf) | Mar 26, 2023 |
| MSI           | PRO B660-A DDR4             | [735a5cc6a2](https://bsd-hardware.info/?probe=735a5cc6a2) | Mar 26, 2023 |
| HP            | 1497                        | [08daaf3be1](https://bsd-hardware.info/?probe=08daaf3be1) | Mar 25, 2023 |
| HP            | 21B4 A01                    | [8de4b8231a](https://bsd-hardware.info/?probe=8de4b8231a) | Mar 25, 2023 |
| HP            | 1497                        | [fc6a7ebc91](https://bsd-hardware.info/?probe=fc6a7ebc91) | Mar 25, 2023 |
| HP            | 1497                        | [e98b5284d9](https://bsd-hardware.info/?probe=e98b5284d9) | Mar 25, 2023 |
| Unknown       | Unknown                     | [55c708e91a](https://bsd-hardware.info/?probe=55c708e91a) | Mar 24, 2023 |
| HP            | 1632                        | [8f3bb99bb4](https://bsd-hardware.info/?probe=8f3bb99bb4) | Mar 17, 2023 |
| Lenovo        | ThinkCentre M58p 6138DK1    | [293de8b0fd](https://bsd-hardware.info/?probe=293de8b0fd) | Mar 14, 2023 |
| Unknown       | Unknown                     | [898095b140](https://bsd-hardware.info/?probe=898095b140) | Mar 09, 2023 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | [6a15f7d4a1](https://bsd-hardware.info/?probe=6a15f7d4a1) | Mar 09, 2023 |
| Arctic Wol... | AWN101                      | [e0f187e449](https://bsd-hardware.info/?probe=e0f187e449) | Mar 01, 2023 |
| Dell          | 0D24M8 A01                  | [22a1b812f8](https://bsd-hardware.info/?probe=22a1b812f8) | Mar 01, 2023 |
| Lenovo        | 3098 0B98401 PRO            | [40d63fc1f7](https://bsd-hardware.info/?probe=40d63fc1f7) | Feb 27, 2023 |
| Dell          | 01TKCC A01                  | [42da900d88](https://bsd-hardware.info/?probe=42da900d88) | Feb 26, 2023 |
| Lenovo        | 30D9 No DPK                 | [c3864d9d51](https://bsd-hardware.info/?probe=c3864d9d51) | Feb 26, 2023 |
| AZW           | U59                         | [a4e906c608](https://bsd-hardware.info/?probe=a4e906c608) | Feb 26, 2023 |
| Unknown       | Unknown                     | [d690aee80e](https://bsd-hardware.info/?probe=d690aee80e) | Feb 26, 2023 |
| AZW           | U59                         | [4dad05a05a](https://bsd-hardware.info/?probe=4dad05a05a) | Feb 24, 2023 |
| AZW           | U59                         | [638aa3ff8e](https://bsd-hardware.info/?probe=638aa3ff8e) | Feb 24, 2023 |
| Dell          | 0HHV7N A00                  | [50f39ca7e0](https://bsd-hardware.info/?probe=50f39ca7e0) | Feb 20, 2023 |
| Apple         | PowerMac3,6                 | [f31181f95c](https://bsd-hardware.info/?probe=f31181f95c) | Feb 20, 2023 |
| Dell          | 0HHV7N A00                  | [fd90fc5154](https://bsd-hardware.info/?probe=fd90fc5154) | Feb 18, 2023 |
| ASUSTek       | PRIME H310M-C R2.0          | [9761fb446b](https://bsd-hardware.info/?probe=9761fb446b) | Feb 18, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [f3c3e6ecb5](https://bsd-hardware.info/?probe=f3c3e6ecb5) | Feb 16, 2023 |
| MiTAC         | UltraPoint                  | [00e52df710](https://bsd-hardware.info/?probe=00e52df710) | Feb 15, 2023 |
| HP            | 212B                        | [0e13beb9f6](https://bsd-hardware.info/?probe=0e13beb9f6) | Feb 12, 2023 |
| Dell          | 0F3KHR A02                  | [f69bff2d41](https://bsd-hardware.info/?probe=f69bff2d41) | Feb 12, 2023 |
| Dell          | 0F3KHR A02                  | [c9c53f2141](https://bsd-hardware.info/?probe=c9c53f2141) | Feb 12, 2023 |
| iBASE         | Mi956                       | [86d20c1bc0](https://bsd-hardware.info/?probe=86d20c1bc0) | Feb 10, 2023 |
| Unknown       | Unknown                     | [3f0d4c3ced](https://bsd-hardware.info/?probe=3f0d4c3ced) | Feb 10, 2023 |
| ASUSTek       | PRIME B450M-A II            | [0587338e57](https://bsd-hardware.info/?probe=0587338e57) | Feb 08, 2023 |
| Dell          | 0F3KHR A02                  | [98c9324352](https://bsd-hardware.info/?probe=98c9324352) | Feb 05, 2023 |
| Supermicro    | X9SCL/X9SCM                 | [1022faa668](https://bsd-hardware.info/?probe=1022faa668) | Feb 01, 2023 |
| Dell          | 0J3C2F A01                  | [93a87b6106](https://bsd-hardware.info/?probe=93a87b6106) | Jan 30, 2023 |
| Unknown       | Unknown                     | [b8efd7453b](https://bsd-hardware.info/?probe=b8efd7453b) | Jan 29, 2023 |
| ASUSTek       | M5A97 PLUS                  | [e00d33f978](https://bsd-hardware.info/?probe=e00d33f978) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [87e25e2abd](https://bsd-hardware.info/?probe=87e25e2abd) | Jan 26, 2023 |
| Unknown       | Unknown                     | [cde064f460](https://bsd-hardware.info/?probe=cde064f460) | Jan 26, 2023 |
| Techvision    | TVI7309X B0                 | [76840aba40](https://bsd-hardware.info/?probe=76840aba40) | Jan 22, 2023 |
| Unknown       | Unknown                     | [14089c4ab4](https://bsd-hardware.info/?probe=14089c4ab4) | Jan 21, 2023 |
| Dell          | 02YYK5 A01                  | [b0fe0783d5](https://bsd-hardware.info/?probe=b0fe0783d5) | Jan 21, 2023 |
| Unknown       | Unknown                     | [32ebc1c99d](https://bsd-hardware.info/?probe=32ebc1c99d) | Jan 20, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [c3281eb186](https://bsd-hardware.info/?probe=c3281eb186) | Jan 18, 2023 |
| HP            | 83F2                        | [a7230c1af5](https://bsd-hardware.info/?probe=a7230c1af5) | Jan 18, 2023 |
| Unknown       | Unknown                     | [0049fd4cfc](https://bsd-hardware.info/?probe=0049fd4cfc) | Jan 17, 2023 |
| HP            | 83F2                        | [912de3c81d](https://bsd-hardware.info/?probe=912de3c81d) | Jan 16, 2023 |
| ASUSTek       | PRIME B450M-A II            | [23d2c64af3](https://bsd-hardware.info/?probe=23d2c64af3) | Jan 16, 2023 |
| Unknown       | Unknown                     | [429659b071](https://bsd-hardware.info/?probe=429659b071) | Jan 13, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [7ba28d1e6b](https://bsd-hardware.info/?probe=7ba28d1e6b) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [917972b6ae](https://bsd-hardware.info/?probe=917972b6ae) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [bd60eadfc4](https://bsd-hardware.info/?probe=bd60eadfc4) | Jan 12, 2023 |
| Unknown       | Unknown                     | [a21b21b82f](https://bsd-hardware.info/?probe=a21b21b82f) | Jan 12, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | [2372c973c8](https://bsd-hardware.info/?probe=2372c973c8) | Jan 11, 2023 |
| Unknown       | Unknown                     | [b19ed4597a](https://bsd-hardware.info/?probe=b19ed4597a) | Jan 07, 2023 |
| Unknown       | Unknown                     | [6347de602a](https://bsd-hardware.info/?probe=6347de602a) | Jan 07, 2023 |
| Unknown       | Unknown                     | [4e8b83804d](https://bsd-hardware.info/?probe=4e8b83804d) | Jan 06, 2023 |
| MSI           | MEG Z690 UNIFY-X            | [e70cd80d11](https://bsd-hardware.info/?probe=e70cd80d11) | Jan 05, 2023 |
| Protectli     | VP2410 10                   | [81c02d080f](https://bsd-hardware.info/?probe=81c02d080f) | Jan 05, 2023 |
| Dell          | 02YYK5 A01                  | [219200b0b6](https://bsd-hardware.info/?probe=219200b0b6) | Jan 05, 2023 |
| Techvision    | TVI7309X B0                 | [4730790da9](https://bsd-hardware.info/?probe=4730790da9) | Jan 04, 2023 |
| Unknown       | Unknown                     | [3d2465f9f9](https://bsd-hardware.info/?probe=3d2465f9f9) | Jan 03, 2023 |
| Techvision    | TVI7309X B0                 | [9dd29daa88](https://bsd-hardware.info/?probe=9dd29daa88) | Jan 02, 2023 |
| Dell          | 0WR7PY A03                  | [b6ec2e7e28](https://bsd-hardware.info/?probe=b6ec2e7e28) | Dec 31, 2022 |
| Dell          | 02YYK5 A01                  | [910c2bba4a](https://bsd-hardware.info/?probe=910c2bba4a) | Dec 31, 2022 |
| Gigabyte      | MBHM87P-00                  | [5d287163c9](https://bsd-hardware.info/?probe=5d287163c9) | Dec 29, 2022 |
| HP            | 1998                        | [afc7de60e3](https://bsd-hardware.info/?probe=afc7de60e3) | Dec 28, 2022 |
| ASRock        | N3710-NUC IPC               | [80c809e992](https://bsd-hardware.info/?probe=80c809e992) | Dec 24, 2022 |
| Protectli     | FW4B Ver                    | [cde7bad6c3](https://bsd-hardware.info/?probe=cde7bad6c3) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | [b8c89bdca8](https://bsd-hardware.info/?probe=b8c89bdca8) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | [b0d1792185](https://bsd-hardware.info/?probe=b0d1792185) | Dec 21, 2022 |
| Dell          | 09KPNV A01                  | [0eea35e069](https://bsd-hardware.info/?probe=0eea35e069) | Dec 19, 2022 |
| Unknown       | Unknown                     | [f876d5d5b1](https://bsd-hardware.info/?probe=f876d5d5b1) | Dec 19, 2022 |
| Unknown       | Unknown                     | [3d77f833b0](https://bsd-hardware.info/?probe=3d77f833b0) | Dec 19, 2022 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [1f1de1d49c](https://bsd-hardware.info/?probe=1f1de1d49c) | Dec 18, 2022 |
| PC Engines    | APU                         | [19786edc61](https://bsd-hardware.info/?probe=19786edc61) | Dec 17, 2022 |
| ASUSTek       | PRIME B450M-A II            | [d9376f2f63](https://bsd-hardware.info/?probe=d9376f2f63) | Dec 16, 2022 |
| HP            | 1495                        | [04bd0455f2](https://bsd-hardware.info/?probe=04bd0455f2) | Dec 14, 2022 |
| HP            | 1495                        | [23f8aeada7](https://bsd-hardware.info/?probe=23f8aeada7) | Dec 14, 2022 |
| HP            | 1495                        | [3eab39d89f](https://bsd-hardware.info/?probe=3eab39d89f) | Dec 09, 2022 |
| HP            | 3397                        | [bc9e5c3ab7](https://bsd-hardware.info/?probe=bc9e5c3ab7) | Dec 09, 2022 |
| Pegatron      | 2A72h                       | [87e76fd095](https://bsd-hardware.info/?probe=87e76fd095) | Dec 09, 2022 |
| Protectli     | FW4B Ver                    | [27dea9bcb5](https://bsd-hardware.info/?probe=27dea9bcb5) | Dec 07, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [15b2363325](https://bsd-hardware.info/?probe=15b2363325) | Dec 05, 2022 |
| Acer          | Aspire XC-105               | [250b12c3f2](https://bsd-hardware.info/?probe=250b12c3f2) | Dec 05, 2022 |
| Protectli     | FW4B Ver                    | [cfaeaeb2f2](https://bsd-hardware.info/?probe=cfaeaeb2f2) | Nov 29, 2022 |
| Protectli     | FW4B Ver                    | [e8e158f783](https://bsd-hardware.info/?probe=e8e158f783) | Nov 27, 2022 |
| Unknown       | Unknown                     | [512a05eefb](https://bsd-hardware.info/?probe=512a05eefb) | Nov 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [5f0b8df8d0](https://bsd-hardware.info/?probe=5f0b8df8d0) | Nov 27, 2022 |
| Unknown       | Unknown                     | [222e69ff59](https://bsd-hardware.info/?probe=222e69ff59) | Nov 26, 2022 |
| Protectli     | FW6                         | [74510f3177](https://bsd-hardware.info/?probe=74510f3177) | Nov 25, 2022 |
| HP            | 8055                        | [ace4570d15](https://bsd-hardware.info/?probe=ace4570d15) | Nov 25, 2022 |
| Techvision    | TVI7309X B0                 | [7258992b77](https://bsd-hardware.info/?probe=7258992b77) | Nov 24, 2022 |
| ASUSTek       | M5A97 PLUS                  | [7c7a121711](https://bsd-hardware.info/?probe=7c7a121711) | Nov 18, 2022 |
| Intel         | SHARKBAY                    | [5875ecec9f](https://bsd-hardware.info/?probe=5875ecec9f) | Nov 18, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [0d37f1878b](https://bsd-hardware.info/?probe=0d37f1878b) | Nov 17, 2022 |
| AZW           | U59                         | [25e1349c5f](https://bsd-hardware.info/?probe=25e1349c5f) | Nov 17, 2022 |
| Lenovo        | 30D9 No DPK                 | [bb9cf416c4](https://bsd-hardware.info/?probe=bb9cf416c4) | Nov 11, 2022 |
| ASUSTek       | P8H77-I                     | [04ea3cc97d](https://bsd-hardware.info/?probe=04ea3cc97d) | Nov 09, 2022 |
| Dell          | 09KPNV A01                  | [32331d772c](https://bsd-hardware.info/?probe=32331d772c) | Nov 08, 2022 |
| Datto         | SSD                         | [235483110d](https://bsd-hardware.info/?probe=235483110d) | Nov 05, 2022 |
| Cisco         | ASA5512 A0                  | [871a5c449f](https://bsd-hardware.info/?probe=871a5c449f) | Nov 01, 2022 |
| Cisco         | ASA5512 A0                  | [5758027775](https://bsd-hardware.info/?probe=5758027775) | Oct 31, 2022 |
| Protectli     | FW4B Ver                    | [6dda683e10](https://bsd-hardware.info/?probe=6dda683e10) | Oct 28, 2022 |
| HP            | 18E4                        | [d66ffbbf6d](https://bsd-hardware.info/?probe=d66ffbbf6d) | Oct 21, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | [c3f0ae254e](https://bsd-hardware.info/?probe=c3f0ae254e) | Oct 17, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | [b4e02e3f51](https://bsd-hardware.info/?probe=b4e02e3f51) | Oct 16, 2022 |
| Unknown       | Unknown                     | [00b5fa7a4e](https://bsd-hardware.info/?probe=00b5fa7a4e) | Oct 13, 2022 |
| ASRock        | B450M Pro4-F                | [edead8a3ae](https://bsd-hardware.info/?probe=edead8a3ae) | Oct 11, 2022 |
| Dell          | 04YP6J A01                  | [ce728798a1](https://bsd-hardware.info/?probe=ce728798a1) | Oct 07, 2022 |
| ASUSTek       | P8B75-M                     | [2620fd3511](https://bsd-hardware.info/?probe=2620fd3511) | Oct 04, 2022 |
| Unknown       | Unknown                     | [79060c241b](https://bsd-hardware.info/?probe=79060c241b) | Oct 03, 2022 |
| Techvision    | TVI7309X B0                 | [33b252016c](https://bsd-hardware.info/?probe=33b252016c) | Sep 26, 2022 |
| ShenZhen M... | MW-GMLK-2.5G6L              | [a1a2cbc6c9](https://bsd-hardware.info/?probe=a1a2cbc6c9) | Sep 20, 2022 |
| CncTion       | N5105-4L B0                 | [22f23ccfa5](https://bsd-hardware.info/?probe=22f23ccfa5) | Sep 17, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | [21e7190ff2](https://bsd-hardware.info/?probe=21e7190ff2) | Sep 11, 2022 |
| ASUSTek       | M5A97 PLUS                  | [3c152ae7bd](https://bsd-hardware.info/?probe=3c152ae7bd) | Sep 11, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | [89b185547b](https://bsd-hardware.info/?probe=89b185547b) | Sep 10, 2022 |
| Intel         | MAHOBAY                     | [a854e50942](https://bsd-hardware.info/?probe=a854e50942) | Sep 06, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [860518eb18](https://bsd-hardware.info/?probe=860518eb18) | Sep 04, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | [b53e1d28cd](https://bsd-hardware.info/?probe=b53e1d28cd) | Sep 04, 2022 |
| Intel         | DQ67EP AAG12529-307         | [1fb1fd6705](https://bsd-hardware.info/?probe=1fb1fd6705) | Sep 03, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | [2e4b87acd2](https://bsd-hardware.info/?probe=2e4b87acd2) | Sep 03, 2022 |
| Protectli     | FW4B Ver                    | [b3a1456bb4](https://bsd-hardware.info/?probe=b3a1456bb4) | Aug 29, 2022 |
| Gigabyte      | MBHM87P-00                  | [9fa5160871](https://bsd-hardware.info/?probe=9fa5160871) | Aug 22, 2022 |
| Dell          | 04Y8V0 A02                  | [9fc4b3c63e](https://bsd-hardware.info/?probe=9fc4b3c63e) | Aug 17, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [753f277d5c](https://bsd-hardware.info/?probe=753f277d5c) | Aug 16, 2022 |
| AZW           | Green G1                    | [4bccb24702](https://bsd-hardware.info/?probe=4bccb24702) | Aug 15, 2022 |
| Dell          | 04Y8V0 A02                  | [a21172360d](https://bsd-hardware.info/?probe=a21172360d) | Aug 15, 2022 |
| Dell          | 04Y8V0 A02                  | [6acccc63ff](https://bsd-hardware.info/?probe=6acccc63ff) | Aug 15, 2022 |
| Lenovo        | 3111 SDK0J40705 WIN 3425... | [6927813b1d](https://bsd-hardware.info/?probe=6927813b1d) | Aug 13, 2022 |
| Lenovo        | SDK0E50510 WIN              | [a45977c76b](https://bsd-hardware.info/?probe=a45977c76b) | Aug 10, 2022 |
| Dell          | 09KPNV A01                  | [236cd1ee65](https://bsd-hardware.info/?probe=236cd1ee65) | Aug 08, 2022 |
| Biostar       | TA880GU3+                   | [8b0c8541b3](https://bsd-hardware.info/?probe=8b0c8541b3) | Aug 06, 2022 |
| MSI           | 785GT-E63                   | [8c307fb033](https://bsd-hardware.info/?probe=8c307fb033) | Aug 03, 2022 |
| Dell          | 0XHGV1 A00                  | [860b06cb6b](https://bsd-hardware.info/?probe=860b06cb6b) | Aug 01, 2022 |
| HP            | 8055                        | [6a8a361dae](https://bsd-hardware.info/?probe=6a8a361dae) | Jul 31, 2022 |
| Dell          | 0TTDMJ A00                  | [900c62c2ba](https://bsd-hardware.info/?probe=900c62c2ba) | Jul 30, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [27b986a422](https://bsd-hardware.info/?probe=27b986a422) | Jul 30, 2022 |
| HP            | 8055                        | [41d802a80a](https://bsd-hardware.info/?probe=41d802a80a) | Jul 29, 2022 |
| ASUSTek       | M5A97 PLUS                  | [7be6ba0021](https://bsd-hardware.info/?probe=7be6ba0021) | Jul 29, 2022 |
| HP            | 18E9                        | [56460b095e](https://bsd-hardware.info/?probe=56460b095e) | Jul 27, 2022 |
| Lenovo        | SHARKBAY NOK                | [1ed99ad502](https://bsd-hardware.info/?probe=1ed99ad502) | Jul 20, 2022 |
| Dell          | 0WR7PY A03                  | [46a6f4e8f3](https://bsd-hardware.info/?probe=46a6f4e8f3) | Jul 19, 2022 |
| Lenovo        | ThinkCentre M91 4518E4U     | [8dd1034cfa](https://bsd-hardware.info/?probe=8dd1034cfa) | Jul 16, 2022 |
| AZW           | Green G1                    | [9a2120ae5a](https://bsd-hardware.info/?probe=9a2120ae5a) | Jul 14, 2022 |
| Datto         | SSD                         | [639d28d449](https://bsd-hardware.info/?probe=639d28d449) | Jul 08, 2022 |
| Protectli     | FW6                         | [e82838534b](https://bsd-hardware.info/?probe=e82838534b) | Jul 06, 2022 |
| Protectli     | FW6 Ver                     | [ac861b1ee3](https://bsd-hardware.info/?probe=ac861b1ee3) | Jun 25, 2022 |
| Protectli     | FW6 Ver                     | [598ecb5457](https://bsd-hardware.info/?probe=598ecb5457) | Jun 25, 2022 |
| HP            | 82A2                        | [77c244bd43](https://bsd-hardware.info/?probe=77c244bd43) | Jun 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | [a57a2f609c](https://bsd-hardware.info/?probe=a57a2f609c) | Jun 13, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [1febab0774](https://bsd-hardware.info/?probe=1febab0774) | Jun 12, 2022 |
| HP            | 1998                        | [1bb67075dd](https://bsd-hardware.info/?probe=1bb67075dd) | Jun 12, 2022 |
| Apple         | Mac-F221BEC8                | [5054729300](https://bsd-hardware.info/?probe=5054729300) | Jun 11, 2022 |
| HP            | 1998                        | [54a6daf0a6](https://bsd-hardware.info/?probe=54a6daf0a6) | Jun 11, 2022 |
| Acer          | EM61SM/EM61PM               | [3b8d6cb36e](https://bsd-hardware.info/?probe=3b8d6cb36e) | Jun 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | [26cd129290](https://bsd-hardware.info/?probe=26cd129290) | Jun 06, 2022 |
| Dell          | 0HHV7N A00                  | [f3c197bdfb](https://bsd-hardware.info/?probe=f3c197bdfb) | Jun 04, 2022 |
| ASUSTek       | M5A97 PLUS                  | [8e8ef96421](https://bsd-hardware.info/?probe=8e8ef96421) | Jun 04, 2022 |
| Dell          | 02YYK5 A01                  | [dce99bec81](https://bsd-hardware.info/?probe=dce99bec81) | Jun 03, 2022 |
| ASUSTek       | M5A97 PLUS                  | [8ca71ddf4d](https://bsd-hardware.info/?probe=8ca71ddf4d) | Jun 02, 2022 |
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
| Alienware     | 049PDM A00                  | [6dac56f3bb](https://bsd-hardware.info/?probe=6dac56f3bb) | Apr 11, 2022 |
| Dell          | 0WR7PY A03                  | [641d1574ce](https://bsd-hardware.info/?probe=641d1574ce) | Apr 11, 2022 |
| PC Engines    | APU                         | [e266947055](https://bsd-hardware.info/?probe=e266947055) | Mar 29, 2022 |
| Unknown       | Unknown                     | [ef1a743845](https://bsd-hardware.info/?probe=ef1a743845) | Mar 28, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [1176fca4ab](https://bsd-hardware.info/?probe=1176fca4ab) | Mar 27, 2022 |
| Unknown       | Unknown                     | [d0e7b62eda](https://bsd-hardware.info/?probe=d0e7b62eda) | Mar 25, 2022 |
| Protectli     | FW4B Ver                    | [cf576c571d](https://bsd-hardware.info/?probe=cf576c571d) | Mar 22, 2022 |
| HP            | 213D A01                    | [6baba4f9c1](https://bsd-hardware.info/?probe=6baba4f9c1) | Mar 20, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [3727ba82af](https://bsd-hardware.info/?probe=3727ba82af) | Mar 19, 2022 |
| Intel         | SHARKBAY                    | [f22a45488b](https://bsd-hardware.info/?probe=f22a45488b) | Mar 15, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [a5fd383c40](https://bsd-hardware.info/?probe=a5fd383c40) | Mar 14, 2022 |
| MSI           | MS-7388                     | [ad8209dbdb](https://bsd-hardware.info/?probe=ad8209dbdb) | Mar 05, 2022 |
| MSI           | MS-7388                     | [a59bca8bde](https://bsd-hardware.info/?probe=a59bca8bde) | Mar 05, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [a6abb45607](https://bsd-hardware.info/?probe=a6abb45607) | Mar 04, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [6b2550968e](https://bsd-hardware.info/?probe=6b2550968e) | Feb 23, 2022 |
| Intel         | Q3XXG4-P V1.0               | [b69015f0e0](https://bsd-hardware.info/?probe=b69015f0e0) | Feb 16, 2022 |
| PC Engines    | apu4                        | [09f27a0f23](https://bsd-hardware.info/?probe=09f27a0f23) | Feb 14, 2022 |
| Protectli     | FW6                         | [d33b2f1244](https://bsd-hardware.info/?probe=d33b2f1244) | Feb 13, 2022 |
| Dell          | 0XHGV1 A00                  | [12ccb8699b](https://bsd-hardware.info/?probe=12ccb8699b) | Feb 08, 2022 |
| Dell          | 0XHGV1 A00                  | [0d3b560aad](https://bsd-hardware.info/?probe=0d3b560aad) | Feb 08, 2022 |
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
| Gigabyte      | M68MT-S2                    | [c183bdd5af](https://bsd-hardware.info/?probe=c183bdd5af) | Jan 01, 2022 |
| Gigabyte      | M68MT-S2                    | [4848e4009f](https://bsd-hardware.info/?probe=4848e4009f) | Jan 01, 2022 |
| AMI           | Cherry Trail CR             | [7d47d0db05](https://bsd-hardware.info/?probe=7d47d0db05) | Dec 30, 2021 |
| ASUSTek       | P8B75-M                     | [c3884fac44](https://bsd-hardware.info/?probe=c3884fac44) | Dec 30, 2021 |
| ASUSTek       | Z170-P                      | [bde74629f9](https://bsd-hardware.info/?probe=bde74629f9) | Dec 25, 2021 |
| ASRock        | J3355B-ITX                  | [f4648747b0](https://bsd-hardware.info/?probe=f4648747b0) | Dec 22, 2021 |
| Quanta        | 2AC7 011                    | [1a831a1d34](https://bsd-hardware.info/?probe=1a831a1d34) | Dec 18, 2021 |
| HP            | 843B                        | [f0d279747f](https://bsd-hardware.info/?probe=f0d279747f) | Dec 13, 2021 |
| HP            | 843B                        | [56400d3999](https://bsd-hardware.info/?probe=56400d3999) | Dec 13, 2021 |
| AMI           | Cherry Trail CR             | [624041b5db](https://bsd-hardware.info/?probe=624041b5db) | Dec 09, 2021 |
| Dell          | 051FJ8 A01                  | [ccfb8336a0](https://bsd-hardware.info/?probe=ccfb8336a0) | Dec 01, 2021 |
| HP            | 843B                        | [404224439d](https://bsd-hardware.info/?probe=404224439d) | Nov 29, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | [dc9d060c7f](https://bsd-hardware.info/?probe=dc9d060c7f) | Nov 27, 2021 |
| ASUSTek       | M5A97 PLUS                  | [a26bc8f2b3](https://bsd-hardware.info/?probe=a26bc8f2b3) | Nov 14, 2021 |
| Gigabyte      | MRZNVMS-00                  | [817cb3e603](https://bsd-hardware.info/?probe=817cb3e603) | Nov 12, 2021 |
| ASUSTek       | M5A97 PLUS                  | [970387f9d9](https://bsd-hardware.info/?probe=970387f9d9) | Nov 09, 2021 |
| Protectli     | FW6E                        | [ebe5b24dee](https://bsd-hardware.info/?probe=ebe5b24dee) | Nov 08, 2021 |
| Protectli     | FW6E                        | [6c12084410](https://bsd-hardware.info/?probe=6c12084410) | Nov 07, 2021 |
| ASUSTek       | M5A97 PLUS                  | [99b5ab3e42](https://bsd-hardware.info/?probe=99b5ab3e42) | Nov 04, 2021 |
| ASRock        | H370M-ITX/ac                | [bf37ad85e7](https://bsd-hardware.info/?probe=bf37ad85e7) | Nov 03, 2021 |
| Unknown       | Unknown                     | [579cf2ac1a](https://bsd-hardware.info/?probe=579cf2ac1a) | Oct 31, 2021 |
| Intel         | Q3XXG4-P V1.0               | [7abc8386ec](https://bsd-hardware.info/?probe=7abc8386ec) | Oct 31, 2021 |
| HP            | 843B                        | [9761f29b5e](https://bsd-hardware.info/?probe=9761f29b5e) | Oct 25, 2021 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | [c3d6cddf87](https://bsd-hardware.info/?probe=c3d6cddf87) | Oct 25, 2021 |
| Intel         | CRESCENTBAY                 | [5c8f3708b1](https://bsd-hardware.info/?probe=5c8f3708b1) | Oct 21, 2021 |
| Acer          | Aspire TC-780               | [77101a00b3](https://bsd-hardware.info/?probe=77101a00b3) | Oct 11, 2021 |
| Acer          | Aspire TC-780               | [3ce8481842](https://bsd-hardware.info/?probe=3ce8481842) | Oct 10, 2021 |
| ASUSTek       | M5A97 PLUS                  | [cc419789f8](https://bsd-hardware.info/?probe=cc419789f8) | Oct 08, 2021 |
| MSI           | B450I GAMING PLUS AC        | [43388a27a4](https://bsd-hardware.info/?probe=43388a27a4) | Oct 04, 2021 |
| Lenovo        | ThinkCentre M58e 7268A9U    | [00bafc5f7c](https://bsd-hardware.info/?probe=00bafc5f7c) | Oct 03, 2021 |
| ASUSTek       | H81M-E                      | [0cc0d2dcb1](https://bsd-hardware.info/?probe=0cc0d2dcb1) | Oct 01, 2021 |
| HP            | 1495                        | [36a5bc62bf](https://bsd-hardware.info/?probe=36a5bc62bf) | Sep 27, 2021 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | [01e33c8399](https://bsd-hardware.info/?probe=01e33c8399) | Sep 26, 2021 |
| ASUSTek       | H81M-E                      | [dec23f7ff8](https://bsd-hardware.info/?probe=dec23f7ff8) | Sep 23, 2021 |
| AMI           | Cherry Trail CR             | [3b709e37c2](https://bsd-hardware.info/?probe=3b709e37c2) | Sep 12, 2021 |
| ASUSTek       | P8H77-I                     | [1feb22dc52](https://bsd-hardware.info/?probe=1feb22dc52) | Sep 12, 2021 |
| HP            | 212B                        | [d3894b9f37](https://bsd-hardware.info/?probe=d3894b9f37) | Sep 10, 2021 |
| ASRock        | H110M-DGS R3.0              | [df08c4e6d3](https://bsd-hardware.info/?probe=df08c4e6d3) | Sep 09, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | [c64c51359c](https://bsd-hardware.info/?probe=c64c51359c) | Sep 09, 2021 |
| Dell          | 09KPNV A01                  | [e960bc2548](https://bsd-hardware.info/?probe=e960bc2548) | Sep 01, 2021 |
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
| HP            | 1495                        | [5aca6c03c1](https://bsd-hardware.info/?probe=5aca6c03c1) | Apr 09, 2021 |
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
| Lenovo        | 30D9 No DPK                 | [061ad76c0e](https://bsd-hardware.info/?probe=061ad76c0e) | Mar 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | [03935b2745](https://bsd-hardware.info/?probe=03935b2745) | Mar 20, 2021 |
| Dell          | 00V62H A00                  | [27cb6a75c8](https://bsd-hardware.info/?probe=27cb6a75c8) | Mar 19, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [8964a02114](https://bsd-hardware.info/?probe=8964a02114) | Mar 15, 2021 |
| ASRock        | B450M Pro4                  | [e9ca160a2d](https://bsd-hardware.info/?probe=e9ca160a2d) | Mar 11, 2021 |
| Shuttle       | FS110                       | [fc31311d01](https://bsd-hardware.info/?probe=fc31311d01) | Mar 10, 2021 |
| Supermicro    | A2SDi-TP8F                  | [c30d805062](https://bsd-hardware.info/?probe=c30d805062) | Mar 05, 2021 |
| ASUSTek       | PRIME H410M-A               | [c7b0539b99](https://bsd-hardware.info/?probe=c7b0539b99) | Mar 02, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | [11d6c98009](https://bsd-hardware.info/?probe=11d6c98009) | Feb 21, 2021 |
| Protectli     | FW6                         | [b656792690](https://bsd-hardware.info/?probe=b656792690) | Feb 20, 2021 |
| ASUSTek       | PRIME H410M-A               | [cfd1824b40](https://bsd-hardware.info/?probe=cfd1824b40) | Feb 18, 2021 |
| Gigabyte      | MRZNVMS-00                  | [b51cb672a4](https://bsd-hardware.info/?probe=b51cb672a4) | Feb 12, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [3402eabdbf](https://bsd-hardware.info/?probe=3402eabdbf) | Feb 09, 2021 |
| ASRock        | Z270M-ITX/ac                | [9b50d422e3](https://bsd-hardware.info/?probe=9b50d422e3) | Feb 04, 2021 |
| HP            | 0AECh D                     | [6dde87584c](https://bsd-hardware.info/?probe=6dde87584c) | Feb 04, 2021 |
| PC Engines    | apu4                        | [18dfb34a97](https://bsd-hardware.info/?probe=18dfb34a97) | Feb 04, 2021 |
| HP            | 3397                        | [cda4af23ee](https://bsd-hardware.info/?probe=cda4af23ee) | Feb 03, 2021 |
| HP            | 3397                        | [65f1db2a70](https://bsd-hardware.info/?probe=65f1db2a70) | Feb 03, 2021 |
| HP            | 82B4                        | [faf58d8f87](https://bsd-hardware.info/?probe=faf58d8f87) | Jan 30, 2021 |
| Lenovo        | 30D9 No DPK                 | [12056c71ad](https://bsd-hardware.info/?probe=12056c71ad) | Jan 30, 2021 |
| PC Engines    | APU2                        | [7e96c61bf9](https://bsd-hardware.info/?probe=7e96c61bf9) | Jan 30, 2021 |
| ASRock        | J3455-ITX                   | [65bde09c13](https://bsd-hardware.info/?probe=65bde09c13) | Jan 26, 2021 |
| ASRock        | J3455-ITX                   | [0a4d4fc896](https://bsd-hardware.info/?probe=0a4d4fc896) | Jan 25, 2021 |
| ASRock        | J3355B-ITX                  | [e8496a6202](https://bsd-hardware.info/?probe=e8496a6202) | Jan 24, 2021 |
| PC Engines    | APU2                        | [da6e3cd1a6](https://bsd-hardware.info/?probe=da6e3cd1a6) | Jan 23, 2021 |
| PC Engines    | APU2                        | [3d536a42eb](https://bsd-hardware.info/?probe=3d536a42eb) | Jan 21, 2021 |
| PC Engines    | APU2                        | [043446a653](https://bsd-hardware.info/?probe=043446a653) | Jan 21, 2021 |
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

...

See full list of test cases in the file [Test_Cases.md](</Location/Canada/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| OPNsense 23.1.11  | 17       | 2.56%   |
| OPNsense 23.7.10  | 16       | 2.41%   |
| OPNsense 24.7     | 15       | 2.26%   |
| OPNsense 24.1.6   | 15       | 2.26%   |
| OPNsense 24.1.7   | 14       | 2.11%   |
| OPNsense 22.7.10  | 14       | 2.11%   |
| OPNsense 24.1.5   | 12       | 1.8%    |
| OPNsense 24.1.1   | 11       | 1.65%   |
| OPNsense 23.7.12  | 11       | 1.65%   |
| OPNsense 24.1.4   | 10       | 1.5%    |
| OPNsense 24.1.2   | 10       | 1.5%    |
| OPNsense 23.7.3   | 10       | 1.5%    |
| OPNsense 23.1.6   | 10       | 1.5%    |
| OPNsense 23.7.8   | 9        | 1.35%   |
| OPNsense 23.7.1   | 9        | 1.35%   |
| OPNsense 23.1.1   | 9        | 1.35%   |
| OPNsense 22.1.10  | 9        | 1.35%   |
| helloSystem 0.8.1 | 9        | 1.35%   |
| helloSystem 0.7.0 | 9        | 1.35%   |
| OPNsense 24.7.8   | 8        | 1.2%    |
| OPNsense 24.7.4   | 8        | 1.2%    |
| OPNsense 24.7.3   | 8        | 1.2%    |
| OPNsense 24.7.10  | 8        | 1.2%    |
| OPNsense 23.1.9   | 8        | 1.2%    |
| OPNsense 22.7.8   | 8        | 1.2%    |
| OPNsense 22.1.8   | 8        | 1.2%    |
| OPNsense 21.1.4   | 8        | 1.2%    |
| helloSystem 0.5.0 | 8        | 1.2%    |
| OPNsense 24.7.9   | 7        | 1.05%   |
| OPNsense 24.7.11  | 7        | 1.05%   |
| OPNsense 24.7.1   | 7        | 1.05%   |
| OPNsense 24.1     | 7        | 1.05%   |
| OPNsense 23.1     | 7        | 1.05%   |
| OPNsense 22.1.7   | 7        | 1.05%   |
| OPNsense 22.1     | 7        | 1.05%   |
| OPNsense 21.7     | 7        | 1.05%   |
| OPNsense 21.1.3   | 7        | 1.05%   |
| OPNsense 24.7.7   | 6        | 0.9%    |
| OPNsense 24.7.6   | 6        | 0.9%    |
| OPNsense 24.1.9   | 6        | 0.9%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 348      | 76.32%  |
| FreeBSD     | 59       | 12.94%  |
| helloSystem | 31       | 6.8%    |
| OpenBSD     | 8        | 1.75%   |
| GhostBSD    | 3        | 0.66%   |
| FreeNAS     | 3        | 0.66%   |
| XigmaNAS    | 1        | 0.22%   |
| TrueNAS     | 1        | 0.22%   |
| pfSense     | 1        | 0.22%   |
| MyBee       | 1        | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| amd64  | 450      | 99.56%  |
| macppc | 1        | 0.22%   |
| i386   | 1        | 0.22%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 380      | 82.97%  |
| helloDesktop | 36       | 7.86%   |
| KDE5         | 12       | 2.62%   |
| XFCE         | 10       | 2.18%   |
| MATE         | 6        | 1.31%   |
| GNOME        | 5        | 1.09%   |
| openbox      | 3        | 0.66%   |
| Cinnamon     | 2        | 0.44%   |
| X-Cinnamon   | 1        | 0.22%   |
| Window Maker | 1        | 0.22%   |
| LXDE         | 1        | 0.22%   |
| DWM          | 1        | 0.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 383      | 84.55%  |
| X11     | 67       | 14.79%  |
| Wayland | 3        | 0.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 396      | 86.46%  |
| SLiM    | 35       | 7.64%   |
| SDDM    | 15       | 3.28%   |
| LightDM | 6        | 1.31%   |
| XDM     | 3        | 0.66%   |
| GDM     | 2        | 0.44%   |
| Ly      | 1        | 0.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 364      | 79.82%  |
| en_US   | 45       | 9.87%   |
| C       | 37       | 8.11%   |
| en_CA   | 5        | 1.1%    |
| fr_FR   | 3        | 0.66%   |
| fr      | 1        | 0.22%   |
| en      | 1        | 0.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 406      | 89.04%  |
| BIOS | 50       | 10.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Zfs    | 236      | 50.43%  |
| Ufs    | 210      | 44.87%  |
| Cd9660 | 14       | 2.99%   |
| Ffs    | 8        | 1.71%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 432      | 95.58%  |
| MBR     | 18       | 3.98%   |
| Unknown | 2        | 0.44%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Hewlett-Packard                      | 53       | 11.73%  |
| Unknown                              | 53       | 11.73%  |
| Dell                                 | 50       | 11.06%  |
| ASUSTek Computer                     | 49       | 10.84%  |
| Lenovo                               | 34       | 7.52%   |
| Intel                                | 32       | 7.08%   |
| Protectli                            | 29       | 6.42%   |
| Gigabyte Technology                  | 21       | 4.65%   |
| ASRock                               | 17       | 3.76%   |
| Supermicro                           | 15       | 3.32%   |
| MSI                                  | 15       | 3.32%   |
| Techvision                           | 14       | 3.1%    |
| AZW                                  | 11       | 2.43%   |
| PC Engines                           | 6        | 1.33%   |
| Acer                                 | 6        | 1.33%   |
| ASRockRack                           | 4        | 0.88%   |
| MW                                   | 3        | 0.66%   |
| CWWK                                 | 3        | 0.66%   |
| CncTion                              | 3        | 0.66%   |
| ShenZhen MinWin Technology           | 2        | 0.44%   |
| Datto                                | 2        | 0.44%   |
| Cisco                                | 2        | 0.44%   |
| Apple                                | 2        | 0.44%   |
| ADI Engineering                      | 2        | 0.44%   |
| Yanling                              | 1        | 0.22%   |
| Trigkey                              | 1        | 0.22%   |
| Shuttle                              | 1        | 0.22%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.22%   |
| SeeedStudio                          | 1        | 0.22%   |
| Seeed Studio                         | 1        | 0.22%   |
| Quanta                               | 1        | 0.22%   |
| Pegatron                             | 1        | 0.22%   |
| nAppliance Networks                  | 1        | 0.22%   |
| MiTAC                                | 1        | 0.22%   |
| IceWhale Technology                  | 1        | 0.22%   |
| IBM                                  | 1        | 0.22%   |
| iBASE                                | 1        | 0.22%   |
| HARDKERNEL                           | 1        | 0.22%   |
| Gowin Solution                       | 1        | 0.22%   |
| Deciso                               | 1        | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 53       | 11.73%  |
| Techvision TVI7309X                | 14       | 3.1%    |
| Protectli FW4B                     | 12       | 2.65%   |
| Intel Q3XXG4-P V1.0                | 7        | 1.55%   |
| Protectli FW6                      | 6        | 1.33%   |
| Protectli VP2420                   | 5        | 1.11%   |
| Intel NDISB533                     | 5        | 1.11%   |
| Dell OptiPlex 9010                 | 5        | 1.11%   |
| AZW EQ                             | 5        | 1.11%   |
| Intel CRESCENTBAY                  | 4        | 0.88%   |
| HP EliteDesk 800 G1 SFF            | 4        | 0.88%   |
| Dell OptiPlex 7020                 | 4        | 0.88%   |
| Dell OptiPlex 7010                 | 4        | 0.88%   |
| AZW U59                            | 4        | 0.88%   |
| PC Engines APU2                    | 3        | 0.66%   |
| MW GMLK-2_5G4L                     | 3        | 0.66%   |
| HP Z440 Workstation                | 3        | 0.66%   |
| HP Compaq Elite 8300 SFF           | 3        | 0.66%   |
| HP Compaq 8200 Elite SFF PC        | 3        | 0.66%   |
| HP Compaq 6200 Pro MT PC           | 3        | 0.66%   |
| HP 500-459                         | 3        | 0.66%   |
| Dell OptiPlex 9020                 | 3        | 0.66%   |
| Dell OptiPlex 7060                 | 3        | 0.66%   |
| Dell OptiPlex 3060                 | 3        | 0.66%   |
| Dell OptiPlex 3010                 | 3        | 0.66%   |
| ASUS All Series                    | 3        | 0.66%   |
| ASRock B450M Pro4                  | 3        | 0.66%   |
| Supermicro X8STi                   | 2        | 0.44%   |
| Supermicro SYS-E300-9A             | 2        | 0.44%   |
| ShenZhen MinWin MW-GMLK-2.5G6L     | 2        | 0.44%   |
| Protectli VP2410                   | 2        | 0.44%   |
| Protectli FW4C                     | 2        | 0.44%   |
| PC Engines apu4                    | 2        | 0.44%   |
| MSI MS-7D59                        | 2        | 0.44%   |
| MSI MS-7A40                        | 2        | 0.44%   |
| Lenovo ThinkCentre M93p 10A8S16X0J | 2        | 0.44%   |
| Lenovo ThinkCentre M93p 10A8S08J01 | 2        | 0.44%   |
| HP ProDesk 600 G2 SFF              | 2        | 0.44%   |
| HP ProDesk 400 G5 SFF              | 2        | 0.44%   |
| HP EliteDesk 800 G3 SFF            | 2        | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 53       | 11.73%  |
| Dell OptiPlex                  | 41       | 9.07%   |
| Lenovo ThinkCentre             | 31       | 6.86%   |
| Techvision TVI7309X            | 14       | 3.1%    |
| Protectli FW4B                 | 12       | 2.65%   |
| HP EliteDesk                   | 12       | 2.65%   |
| HP Compaq                      | 12       | 2.65%   |
| ASUS PRIME                     | 12       | 2.65%   |
| HP ProDesk                     | 11       | 2.43%   |
| ASUS ROG                       | 8        | 1.77%   |
| Intel Q3XXG4-P                 | 7        | 1.55%   |
| Protectli FW6                  | 6        | 1.33%   |
| Dell Precision                 | 6        | 1.33%   |
| Acer Aspire                    | 6        | 1.33%   |
| Protectli VP2420               | 5        | 1.11%   |
| Intel NDISB533                 | 5        | 1.11%   |
| AZW EQ                         | 5        | 1.11%   |
| ASRock B450M                   | 5        | 1.11%   |
| Intel CRESCENTBAY              | 4        | 0.88%   |
| AZW U59                        | 4        | 0.88%   |
| PC Engines APU2                | 3        | 0.66%   |
| MW GMLK-2                      | 3        | 0.66%   |
| HP Z440                        | 3        | 0.66%   |
| HP 500-459                     | 3        | 0.66%   |
| ASUS M5A97                     | 3        | 0.66%   |
| ASUS All                       | 3        | 0.66%   |
| Supermicro X8STi               | 2        | 0.44%   |
| Supermicro SYS-E300-9A         | 2        | 0.44%   |
| ShenZhen MinWin MW-GMLK-2.5G6L | 2        | 0.44%   |
| Protectli VP2410               | 2        | 0.44%   |
| Protectli FW4C                 | 2        | 0.44%   |
| PC Engines apu4                | 2        | 0.44%   |
| MSI MS-7D59                    | 2        | 0.44%   |
| MSI MS-7A40                    | 2        | 0.44%   |
| Lenovo SHARKBAY                | 2        | 0.44%   |
| Intel X79                      | 2        | 0.44%   |
| HP t620                        | 2        | 0.44%   |
| HP Pavilion                    | 2        | 0.44%   |
| HP 500-409                     | 2        | 0.44%   |
| Dell G5                        | 2        | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2022    | 56       | 12.39%  |
| 2018    | 48       | 10.62%  |
| 2023    | 45       | 9.96%   |
| 2014    | 37       | 8.19%   |
| 2021    | 30       | 6.64%   |
| 2020    | 28       | 6.19%   |
| 2013    | 26       | 5.75%   |
| 2017    | 25       | 5.53%   |
| 2016    | 25       | 5.53%   |
| 2011    | 23       | 5.09%   |
| 2019    | 21       | 4.65%   |
| 2012    | 21       | 4.65%   |
| 2015    | 18       | 3.98%   |
| 2010    | 18       | 3.98%   |
| 2008    | 11       | 2.43%   |
| 2009    | 6        | 1.33%   |
| 2024    | 5        | 1.11%   |
| 2007    | 5        | 1.11%   |
| Unknown | 3        | 0.66%   |
| 2006    | 1        | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 452      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 439      | 97.12%  |
| Yes  | 13       | 2.88%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 183      | 39.44%  |
| 16.01-24.0  | 127      | 27.37%  |
| 4.01-8.0    | 59       | 12.72%  |
| 32.01-64.0  | 47       | 10.13%  |
| 64.01-256.0 | 22       | 4.74%   |
| 24.01-32.0  | 9        | 1.94%   |
| 2.01-3.0    | 8        | 1.72%   |
| 3.01-4.0    | 6        | 1.29%   |
| 1.01-2.0    | 2        | 0.43%   |
| 0.51-1.0    | 1        | 0.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.01-0.5    | 209      | 45.04%  |
| 0.51-1.0    | 166      | 35.78%  |
| 1.01-2.0    | 62       | 13.36%  |
| 2.01-3.0    | 14       | 3.02%   |
| 3.01-4.0    | 5        | 1.08%   |
| 4.01-8.0    | 4        | 0.86%   |
| 32.01-64.0  | 1        | 0.22%   |
| 64.01-256.0 | 1        | 0.22%   |
| 8.01-16.0   | 1        | 0.22%   |
| 0           | 1        | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 317      | 67.3%   |
| 2      | 64       | 13.59%  |
| 0      | 56       | 11.89%  |
| 3      | 19       | 4.03%   |
| 4      | 9        | 1.91%   |
| 13     | 2        | 0.42%   |
| 5      | 2        | 0.42%   |
| 10     | 1        | 0.21%   |
| 7      | 1        | 0.21%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 364      | 79.13%  |
| Yes       | 96       | 20.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 450      | 99.34%  |
| No        | 3        | 0.66%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 365      | 79.87%  |
| Yes       | 92       | 20.13%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 388      | 85.84%  |
| Yes       | 64       | 14.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Canada  | 452      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Montreal                 | 45       | 9.11%   |
| Toronto                  | 42       | 8.5%    |
| Calgary                  | 27       | 5.47%   |
| Edmonton                 | 23       | 4.66%   |
| Ottawa                   | 22       | 4.45%   |
| Winnipeg                 | 21       | 4.25%   |
| Victoria                 | 14       | 2.83%   |
| Vancouver                | 11       | 2.23%   |
| Scarborough              | 10       | 2.02%   |
| Kitchener                | 10       | 2.02%   |
| Surrey                   | 8        | 1.62%   |
| Regina                   | 8        | 1.62%   |
| North Vancouver          | 8        | 1.62%   |
| London                   | 7        | 1.42%   |
| Laval                    | 7        | 1.42%   |
| Brampton                 | 7        | 1.42%   |
| Québec                  | 5        | 1.01%   |
| Longueuil                | 5        | 1.01%   |
| Cambridge                | 5        | 1.01%   |
| Barrie                   | 5        | 1.01%   |
| Windsor                  | 4        | 0.81%   |
| St. Albert               | 4        | 0.81%   |
| Saskatoon                | 4        | 0.81%   |
| Sainte-Marthe-sur-le-Lac | 4        | 0.81%   |
| Moncton                  | 4        | 0.81%   |
| Mississauga              | 4        | 0.81%   |
| Kingston                 | 4        | 0.81%   |
| Burnaby                  | 4        | 0.81%   |
| Burlington               | 4        | 0.81%   |
| St. Jean Baptiste        | 3        | 0.61%   |
| Sarnia                   | 3        | 0.61%   |
| Peterborough             | 3        | 0.61%   |
| Oakville                 | 3        | 0.61%   |
| Nanaimo                  | 3        | 0.61%   |
| Lethbridge               | 3        | 0.61%   |
| Guelph                   | 3        | 0.61%   |
| Greater Sudbury          | 3        | 0.61%   |
| Gatineau                 | 3        | 0.61%   |
| Wetaskiwin               | 2        | 0.4%    |
| West Kelowna             | 2        | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 75       | 122    | 14.97%  |
| WDC                 | 62       | 127    | 12.38%  |
| Kingston            | 60       | 91     | 11.98%  |
| Seagate             | 55       | 114    | 10.98%  |
| Intel               | 25       | 36     | 4.99%   |
| Crucial             | 20       | 33     | 3.99%   |
| Patriot             | 19       | 29     | 3.79%   |
| A-DATA Technology   | 18       | 30     | 3.59%   |
| SanDisk             | 13       | 17     | 2.59%   |
| SPCC                | 10       | 13     | 2%      |
| Toshiba             | 8        | 12     | 1.6%    |
| Phison              | 8        | 9      | 1.6%    |
| Micron Technology   | 8        | 16     | 1.6%    |
| Protectli           | 7        | 15     | 1.4%    |
| OCZ                 | 7        | 9      | 1.4%    |
| Hitachi             | 7        | 7      | 1.4%    |
| Dogfish             | 7        | 15     | 1.4%    |
| China               | 7        | 11     | 1.4%    |
| Hoodisk             | 6        | 9      | 1.2%    |
| HGST                | 6        | 10     | 1.2%    |
| Mushkin             | 5        | 6      | 1%      |
| Transcend           | 4        | 7      | 0.8%    |
| SK hynix            | 4        | 6      | 0.8%    |
| PNY                 | 4        | 5      | 0.8%    |
| Hewlett-Packard     | 4        | 4      | 0.8%    |
| BIWIN               | 4        | 8      | 0.8%    |
| Timetec             | 3        | 5      | 0.6%    |
| Team                | 3        | 8      | 0.6%    |
| NVMe                | 3        | 3      | 0.6%    |
| LITEONIT            | 3        | 4      | 0.6%    |
| Lexar               | 3        | 4      | 0.6%    |
| FORESEE             | 3        | 7      | 0.6%    |
| Corsair             | 3        | 5      | 0.6%    |
| Netac               | 2        | 2      | 0.4%    |
| Zheino              | 1        | 1      | 0.2%    |
| YMTC                | 1        | 1      | 0.2%    |
| XPG                 | 1        | 2      | 0.2%    |
| walram              | 1        | 1      | 0.2%    |
| VisionTek           | 1        | 5      | 0.2%    |
| TEXTORM             | 1        | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Kingston SA400S37240G 240GB     | 18       | 3.36%   |
| Kingston SA400S37120G 120GB     | 12       | 2.24%   |
| Seagate ST500DM002-1BD142 500GB | 8        | 1.49%   |
| Seagate ST1000DM010-2EP102 1TB  | 6        | 1.12%   |
| Samsung SSD 850 EVO 250GB       | 6        | 1.12%   |
| Samsung SSD 840 EVO 120GB       | 5        | 0.93%   |
| Seagate ST2000DM008-2FR102 2TB  | 4        | 0.75%   |
| SanDisk SD6SB1M064G1022I 64GB   | 4        | 0.75%   |
| Samsung SSD 970 EVO Plus 1TB    | 4        | 0.75%   |
| Samsung SSD 870 EVO 250GB       | 4        | 0.75%   |
| Samsung SSD 860 EVO 500GB       | 4        | 0.75%   |
| Samsung SSD 840 EVO 250GB       | 4        | 0.75%   |
| Patriot M.2 P310 240GB          | 4        | 0.75%   |
| Patriot Burst Elite 120GB       | 4        | 0.75%   |
| Dogfish SSD 128GB               | 4        | 0.75%   |
| Crucial CT240BX500SSD1 240GB    | 4        | 0.75%   |
| BIWIN SSD 128GB                 | 4        | 0.75%   |
| WDC WD40EFRX-68WT0N0 4TB        | 3        | 0.56%   |
| WDC WD20EZRX-00DC0B0 2TB        | 3        | 0.56%   |
| Transcend TS256GMSA230S 256GB   | 3        | 0.56%   |
| Toshiba DT01ACA100 1TB          | 3        | 0.56%   |
| SPCC Solid State Disk 256GB     | 3        | 0.56%   |
| Seagate ST500LM021-1KJ152 500GB | 3        | 0.56%   |
| Seagate ST3500413AS 500GB       | 3        | 0.56%   |
| Samsung SSD 980 250GB           | 3        | 0.56%   |
| Samsung SSD 980 1TB             | 3        | 0.56%   |
| Samsung SSD 850 PRO 256GB       | 3        | 0.56%   |
| Phison Sabrent 512GB            | 3        | 0.56%   |
| Kingston SV300S37A120G 120GB    | 3        | 0.56%   |
| Kingston SUV500MS120G 120GB     | 3        | 0.56%   |
| Kingston SKC600MS256G 256GB     | 3        | 0.56%   |
| Kingston SA400S37480G 480GB     | 3        | 0.56%   |
| Intel SSDSC2BB080G4 80GB        | 3        | 0.56%   |
| Crucial CT1000MX500SSD1 1TB     | 3        | 0.56%   |
| A-DATA SU655 120GB              | 3        | 0.56%   |
| WDC WDS500G2B0A-00SM50 500GB    | 2        | 0.37%   |
| WDC WD6400AAKS-22A7B2 640GB     | 2        | 0.37%   |
| WDC WD5000AAKX-75U6AA0 500GB    | 2        | 0.37%   |
| WDC WD40EFRX-68N32N0 4TB        | 2        | 0.37%   |
| WDC WD10JPVX-22JC3T0 1TB        | 2        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Seagate  | 52       | 111    | 41.94%  |
| WDC      | 47       | 103    | 37.9%   |
| Toshiba  | 7        | 9      | 5.65%   |
| Hitachi  | 7        | 7      | 5.65%   |
| HGST     | 6        | 10     | 4.84%   |
| Synology | 1        | 1      | 0.81%   |
| OPENBSD  | 1        | 1      | 0.81%   |
| NVMe     | 1        | 1      | 0.81%   |
| HPT      | 1        | 1      | 0.81%   |
| Fujitsu  | 1        | 1      | 0.81%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 56       | 92     | 18.12%  |
| Kingston            | 55       | 78     | 17.8%   |
| Intel               | 22       | 31     | 7.12%   |
| Crucial             | 19       | 27     | 6.15%   |
| A-DATA Technology   | 16       | 28     | 5.18%   |
| SanDisk             | 13       | 17     | 4.21%   |
| Patriot             | 13       | 21     | 4.21%   |
| WDC                 | 9        | 12     | 2.91%   |
| SPCC                | 7        | 9      | 2.27%   |
| Protectli           | 7        | 15     | 2.27%   |
| OCZ                 | 7        | 9      | 2.27%   |
| Micron Technology   | 7        | 15     | 2.27%   |
| Dogfish             | 7        | 15     | 2.27%   |
| China               | 7        | 11     | 2.27%   |
| Hoodisk             | 6        | 9      | 1.94%   |
| Mushkin             | 5        | 6      | 1.62%   |
| Transcend           | 4        | 7      | 1.29%   |
| PNY                 | 4        | 5      | 1.29%   |
| BIWIN               | 4        | 8      | 1.29%   |
| Seagate             | 3        | 3      | 0.97%   |
| LITEONIT            | 3        | 4      | 0.97%   |
| Lexar               | 3        | 4      | 0.97%   |
| FORESEE             | 3        | 7      | 0.97%   |
| Corsair             | 3        | 5      | 0.97%   |
| Timetec             | 2        | 3      | 0.65%   |
| Netac               | 2        | 2      | 0.65%   |
| Hewlett-Packard     | 2        | 2      | 0.65%   |
| Zheino              | 1        | 1      | 0.32%   |
| walram              | 1        | 1      | 0.32%   |
| VisionTek           | 1        | 5      | 0.32%   |
| TEXTORM             | 1        | 1      | 0.32%   |
| Team                | 1        | 1      | 0.32%   |
| Silicon Power       | 1        | 1      | 0.32%   |
| SATADOM             | 1        | 2      | 0.32%   |
| Phison              | 1        | 1      | 0.32%   |
| NVMe                | 1        | 1      | 0.32%   |
| LITEON              | 1        | 1      | 0.32%   |
| KingSpec            | 1        | 1      | 0.32%   |
| Kingsand            | 1        | 3      | 0.32%   |
| Innodisk            | 1        | 1      | 0.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 284      | 489    | 62.01%  |
| HDD  | 105      | 245    | 22.93%  |
| NVMe | 69       | 116    | 15.07%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 359      | 734    | 83.88%  |
| NVMe | 69       | 116    | 16.12%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 300      | 499    | 73.71%  |
| 0.51-1.0   | 56       | 107    | 13.76%  |
| 1.01-2.0   | 23       | 46     | 5.65%   |
| 3.01-4.0   | 15       | 34     | 3.69%   |
| 4.01-10.0  | 7        | 35     | 1.72%   |
| 2.01-3.0   | 4        | 10     | 0.98%   |
| 10.01-20.0 | 2        | 3      | 0.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 204      | 43.13%  |
| 251-500        | 89       | 18.82%  |
| 51-100         | 48       | 10.15%  |
| 21-50          | 38       | 8.03%   |
| 501-1000       | 36       | 7.61%   |
| 1-20           | 34       | 7.19%   |
| 1001-2000      | 15       | 3.17%   |
| More than 3000 | 6        | 1.27%   |
| Unknown        | 3        | 0.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 424      | 89.83%  |
| 21-50          | 25       | 5.3%    |
| 51-100         | 9        | 1.91%   |
| 101-250        | 5        | 1.06%   |
| Unknown        | 3        | 0.64%   |
| 1001-2000      | 2        | 0.42%   |
| 501-1000       | 2        | 0.42%   |
| More than 3000 | 1        | 0.21%   |
| 251-500        | 1        | 0.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Desktops | Drives | Percent |
|--------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB            | 4        | 7      | 5.63%   |
| Seagate ST500LM021-1KJ152 500GB            | 3        | 5      | 4.23%   |
| Patriot Burst Elite 120GB                  | 3        | 4      | 4.23%   |
| WDC WD6400AAKS-22A7B2 640GB                | 2        | 9      | 2.82%   |
| WDC WD40EFRX-68WT0N0 4TB                   | 2        | 3      | 2.82%   |
| Toshiba MQ01ABD075 752GB                   | 2        | 2      | 2.82%   |
| Seagate ST3500413AS 500GB                  | 2        | 4      | 2.82%   |
| Patriot Pyro SE 120GB                      | 2        | 4      | 2.82%   |
| WDC WD800JD-08MSA1 80GB                    | 1        | 2      | 1.41%   |
| WDC WD60EZRZ-00RWYB1 6TB                   | 1        | 2      | 1.41%   |
| WDC WD50EFRX-68L0BN1 5TB                   | 1        | 1      | 1.41%   |
| WDC WD5003AZEX-00K1GA0 500GB               | 1        | 1      | 1.41%   |
| WDC WD40EZRZ-00WN9B0 4TB                   | 1        | 1      | 1.41%   |
| WDC WD3200AAKS-75L9A0 320GB                | 1        | 1      | 1.41%   |
| WDC WD30EZRX-22D8PB0 3TB                   | 1        | 1      | 1.41%   |
| WDC WD2500AAKX-001CA0 250GB                | 1        | 1      | 1.41%   |
| WDC WD1600AAJS-60Z0A0 160GB                | 1        | 2      | 1.41%   |
| WDC WD15EARS-00Z5B1 1.5TB                  | 1        | 1      | 1.41%   |
| WDC WD1200SD-01KCB0 120GB                  | 1        | 1      | 1.41%   |
| walram SSD 120G                            | 1        | 1      | 1.41%   |
| VisionTek mSATA 120GB                      | 1        | 5      | 1.41%   |
| Toshiba MQ01ABD100 1TB                     | 1        | 1      | 1.41%   |
| Toshiba DT01ACA100 1TB                     | 1        | 3      | 1.41%   |
| TEXTORM B5 240GB                           | 1        | 1      | 1.41%   |
| SPCC Solid State Disk 128GB                | 1        | 1      | 1.41%   |
| Seagate ST3250318AS 250GB                  | 1        | 1      | 1.41%   |
| Seagate ST3200822AS 200GB                  | 1        | 1      | 1.41%   |
| Seagate ST3160815AS 160GB                  | 1        | 2      | 1.41%   |
| Seagate ST31500341AS 1.5TB                 | 1        | 2      | 1.41%   |
| Seagate ST3120026A 120GB                   | 1        | 1      | 1.41%   |
| Seagate ST31000520AS 1TB                   | 1        | 1      | 1.41%   |
| Seagate ST1000DM003-1CH162 1TB             | 1        | 2      | 1.41%   |
| Samsung Electronics SSD 870 EVO 250GB      | 1        | 9      | 1.41%   |
| Mushkin MKNSSDSR250GB                      | 1        | 1      | 1.41%   |
| Mushkin MKNSSDEC512GB                      | 1        | 2      | 1.41%   |
| Micron Technology M500_MTFDDAK960MAV 960GB | 1        | 4      | 1.41%   |
| Kingston SV300S37A120G 120GB               | 1        | 1      | 1.41%   |
| Kingston SNS4151S316GD 16GB                | 1        | 3      | 1.41%   |
| Kingston SKC600MS256G 256GB                | 1        | 1      | 1.41%   |
| Kingston SA400S37240G 240GB                | 1        | 1      | 1.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 26     | 21.74%  |
| Seagate             | 14       | 26     | 20.29%  |
| Patriot             | 5        | 8      | 7.25%   |
| Toshiba             | 4        | 6      | 5.8%    |
| Kingston            | 4        | 6      | 5.8%    |
| Intel               | 4        | 5      | 5.8%    |
| Hitachi             | 4        | 4      | 5.8%    |
| HGST                | 3        | 5      | 4.35%   |
| Mushkin             | 2        | 3      | 2.9%    |
| Crucial             | 2        | 2      | 2.9%    |
| A-DATA Technology   | 2        | 3      | 2.9%    |
| walram              | 1        | 1      | 1.45%   |
| VisionTek           | 1        | 5      | 1.45%   |
| TEXTORM             | 1        | 1      | 1.45%   |
| SPCC                | 1        | 1      | 1.45%   |
| Samsung Electronics | 1        | 9      | 1.45%   |
| Micron Technology   | 1        | 4      | 1.45%   |
| KingSpec            | 1        | 1      | 1.45%   |
| Hewlett-Packard     | 1        | 1      | 1.45%   |
| Dogfish             | 1        | 3      | 1.45%   |
| AMD                 | 1        | 3      | 1.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 15       | 26     | 37.5%   |
| Seagate | 14       | 26     | 35%     |
| Toshiba | 4        | 6      | 10%     |
| Hitachi | 4        | 4      | 10%     |
| HGST    | 3        | 5      | 7.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 37       | 67     | 56.06%  |
| SSD  | 29       | 56     | 43.94%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| WDC WD10SPZX-00Z10T0 1TB                         | 1        | 1      | 33.33%  |
| Seagate ST3250310AS 250GB                        | 1        | 1      | 33.33%  |
| Samsung Electronics SSD PM830 2.5-inch 7mm 256GB | 1        | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 33.33%  |
| Seagate             | 1        | 1      | 33.33%  |
| Samsung Electronics | 1        | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 361      | 715    | 82.8%   |
| Malfunc  | 64       | 123    | 14.68%  |
| Detected | 8        | 9      | 1.83%   |
| Failed   | 3        | 3      | 0.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 375      | 64.1%   |
| AMD                         | 63       | 10.77%  |
| Samsung Electronics         | 28       | 4.79%   |
| SanDisk                     | 17       | 2.91%   |
| MAXIO Technology (Hangzhou) | 15       | 2.56%   |
| Silicon Motion              | 13       | 2.22%   |
| Phison Electronics          | 10       | 1.71%   |
| Kingston Technology Company | 9        | 1.54%   |
| ASMedia Technology          | 8        | 1.37%   |
| SK hynix                    | 6        | 1.03%   |
| Nvidia                      | 6        | 1.03%   |
| Marvell Technology Group    | 4        | 0.68%   |
| JMicron Technology          | 4        | 0.68%   |
| VIA Technologies            | 3        | 0.51%   |
| Realtek Semiconductor       | 3        | 0.51%   |
| Micron/Crucial Technology   | 3        | 0.51%   |
| Chelsio Communications      | 3        | 0.51%   |
| Broadcom / LSI              | 3        | 0.51%   |
| Silicon Image               | 2        | 0.34%   |
| Micron Technology           | 2        | 0.34%   |
| Hosin Global Electronics    | 2        | 0.34%   |
| ADATA Technology            | 2        | 0.34%   |
| Yangtze Memory Technologies | 1        | 0.17%   |
| Toshiba                     | 1        | 0.17%   |
| HighPoint Technologies      | 1        | 0.17%   |
| Unknown                     | 1        | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 45       | 6.64%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 31       | 4.57%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 28       | 4.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 26       | 3.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 25       | 3.69%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 22       | 3.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 20       | 2.95%   |
| AMD 400 Series Chipset SATA Controller                                           | 19       | 2.8%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 18       | 2.65%   |
| Intel Alder Lake-N SATA AHCI Controller                                          | 18       | 2.65%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 16       | 2.36%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 15       | 2.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 15       | 2.21%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 12       | 1.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 11       | 1.62%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 11       | 1.62%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 11       | 1.62%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 10       | 1.47%   |
| Intel Elkhart Lake SATA AHCI                                                     | 9        | 1.33%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 9        | 1.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8        | 1.18%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 8        | 1.18%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 7        | 1.03%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 7        | 1.03%   |
| Intel SATA Controller [RAID mode]                                                | 7        | 1.03%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 7        | 1.03%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 7        | 1.03%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 7        | 1.03%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 6        | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 6        | 0.88%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 6        | 0.88%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5        | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 5        | 0.74%   |
| AMD FCH SATA Controller [IDE mode]                                               | 5        | 0.74%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                            | 4        | 0.59%   |
| Phison E12 NVMe Controller                                                       | 4        | 0.59%   |
| Nvidia MCP61 SATA Controller                                                     | 4        | 0.59%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4        | 0.59%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4        | 0.59%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 4        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 394      | 67.93%  |
| NVMe | 107      | 18.45%  |
| IDE  | 55       | 9.48%   |
| RAID | 15       | 2.59%   |
| SCSI | 5        | 0.86%   |
| SAS  | 4        | 0.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 388      | 84.9%   |
| AMD     | 68       | 14.88%  |
| Unknown | 1        | 0.22%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Celeron N5105 @ 2.00GHz          | 26       | 5.6%    |
| Intel N100                             | 22       | 4.74%   |
| Intel Celeron J4125 CPU @ 2.00GHz      | 16       | 3.45%   |
| Intel Core i5-6500 CPU @ 3.20GHz       | 14       | 3.02%   |
| Intel Celeron CPU J3160 @ 1.60GHz      | 12       | 2.59%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 11       | 2.37%   |
| Intel Core i5-3570 CPU @ 3.40GHz       | 9        | 1.94%   |
| Intel Core i5-8500 CPU @ 3.00GHz       | 8        | 1.72%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 7        | 1.51%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 7        | 1.51%   |
| Intel Core i5-4570TE CPU @ 2.70GHz     | 5        | 1.08%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 5        | 1.08%   |
| Intel Core i3-4030U CPU @ 1.90GHz      | 5        | 1.08%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz   | 5        | 1.08%   |
| Intel Celeron J6412 @ 2.00GHz          | 5        | 1.08%   |
| AMD GX-412TC SOC                       | 5        | 1.08%   |
| Intel Xeon                             | 4        | 0.86%   |
| Intel Core i5-7200U CPU @ 2.50GHz      | 4        | 0.86%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 4        | 0.86%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 4        | 0.86%   |
| Intel Core i3-2100 CPU @ 3.10GHz       | 4        | 0.86%   |
| Intel Celeron J6413 @ 1.80GHz          | 4        | 0.86%   |
| Intel Celeron J4105 CPU @ 1.50GHz      | 4        | 0.86%   |
| AMD Ryzen 5 2600 Six-Core Processor    | 4        | 0.86%   |
| Intel Pentium Silver N6005 @ 2.00GHz   | 3        | 0.65%   |
| Intel Pentium CPU G4560 @ 3.50GHz      | 3        | 0.65%   |
| Intel Core i7-9700K CPU @ 3.60GHz      | 3        | 0.65%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 3        | 0.65%   |
| Intel Core i5-6500T CPU @ 2.50GHz      | 3        | 0.65%   |
| Intel Core i5-4670 CPU @ 3.40GHz       | 3        | 0.65%   |
| Intel Core i5-4430 CPU @ 3.00GHz       | 3        | 0.65%   |
| Intel Core i5-3470T CPU @ 2.90GHz      | 3        | 0.65%   |
| Intel Core i5 CPU 650 @ 3.20GHz        | 3        | 0.65%   |
| Intel Core i3-6100 CPU @ 3.70GHz       | 3        | 0.65%   |
| Intel Core i3-4005U CPU @ 1.70GHz      | 3        | 0.65%   |
| Intel Celeron N5100 @ 1.10GHz          | 3        | 0.65%   |
| Intel Celeron CPU J1900 @ 1.99GHz      | 3        | 0.65%   |
| Intel 12th Gen Core i5-12400           | 3        | 0.65%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 3        | 0.65%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz    | 2        | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 115      | 24.84%  |
| Intel Celeron           | 83       | 17.93%  |
| Intel Core i3           | 46       | 9.94%   |
| Other                   | 39       | 8.42%   |
| Intel Core i7           | 34       | 7.34%   |
| Intel Xeon              | 29       | 6.26%   |
| Intel Atom              | 16       | 3.46%   |
| AMD Ryzen 5             | 14       | 3.02%   |
| Intel Pentium           | 10       | 2.16%   |
| AMD FX                  | 9        | 1.94%   |
| Intel Core 2 Duo        | 8        | 1.73%   |
| AMD GX                  | 8        | 1.73%   |
| AMD Ryzen 9             | 6        | 1.3%    |
| AMD Ryzen 7             | 5        | 1.08%   |
| AMD Athlon 64 X2        | 5        | 1.08%   |
| Intel Core 2 Quad       | 4        | 0.86%   |
| Intel Pentium Silver    | 3        | 0.65%   |
| Intel Pentium Dual-Core | 3        | 0.65%   |
| AMD Ryzen 3             | 3        | 0.65%   |
| AMD Phenom II X6        | 2        | 0.43%   |
| AMD Athlon II X2        | 2        | 0.43%   |
| AMD Athlon              | 2        | 0.43%   |
| AMD A10                 | 2        | 0.43%   |
| Intel Pentium Gold      | 1        | 0.22%   |
| Intel Pentium 4         | 1        | 0.22%   |
| Intel Core i9           | 1        | 0.22%   |
| Intel Core 2            | 1        | 0.22%   |
| AMD Ryzen Embedded      | 1        | 0.22%   |
| AMD Ryzen 5 PRO         | 1        | 0.22%   |
| AMD PRO A10             | 1        | 0.22%   |
| AMD Phenom              | 1        | 0.22%   |
| AMD G                   | 1        | 0.22%   |
| AMD EPYC                | 1        | 0.22%   |
| AMD E                   | 1        | 0.22%   |
| AMD Athlon Dual Core    | 1        | 0.22%   |
| AMD A8                  | 1        | 0.22%   |
| AMD A6                  | 1        | 0.22%   |
| AMD A4                  | 1        | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 263      | 56.8%   |
| 2       | 93       | 20.09%  |
| 6       | 38       | 8.21%   |
| 8       | 25       | 5.4%    |
| 12      | 13       | 2.81%   |
| 16      | 9        | 1.94%   |
| 32      | 5        | 1.08%   |
| Unknown | 5        | 1.08%   |
| 10      | 3        | 0.65%   |
| 3       | 3        | 0.65%   |
| 24      | 2        | 0.43%   |
| 20      | 2        | 0.43%   |
| 11      | 1        | 0.22%   |
| 5       | 1        | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 446      | 98.67%  |
| 2       | 4        | 0.88%   |
| Unknown | 2        | 0.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 312      | 68.12%  |
| 2       | 141      | 30.79%  |
| Unknown | 5        | 1.09%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Unknown       | 85       | 18.32%  |
| Haswell       | 66       | 14.22%  |
| KabyLake      | 42       | 9.05%   |
| IvyBridge     | 35       | 7.54%   |
| Skylake       | 28       | 6.03%   |
| SandyBridge   | 27       | 5.82%   |
| Goldmont plus | 22       | 4.74%   |
| Silvermont    | 21       | 4.53%   |
| Penryn        | 16       | 3.45%   |
| Goldmont      | 16       | 3.45%   |
| Westmere      | 11       | 2.37%   |
| Zen+          | 10       | 2.16%   |
| Zen 3         | 10       | 2.16%   |
| Piledriver    | 8        | 1.72%   |
| Broadwell     | 8        | 1.72%   |
| CometLake     | 7        | 1.51%   |
| Zen           | 6        | 1.29%   |
| Puma          | 6        | 1.29%   |
| K8 Hammer     | 6        | 1.29%   |
| K10           | 6        | 1.29%   |
| Nehalem       | 4        | 0.86%   |
| Jaguar        | 4        | 0.86%   |
| Core          | 4        | 0.86%   |
| Zen 2         | 3        | 0.65%   |
| Bulldozer     | 3        | 0.65%   |
| Bonnell       | 3        | 0.65%   |
| Steamroller   | 2        | 0.43%   |
| Bobcat        | 2        | 0.43%   |
| TigerLake     | 1        | 0.22%   |
| NetBurst      | 1        | 0.22%   |
| Excavator     | 1        | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 324      | 72%     |
| AMD                                          | 50       | 11.11%  |
| Nvidia                                       | 48       | 10.67%  |
| ASPEED Technology                            | 20       | 4.44%   |
| Matrox Electronics Systems                   | 6        | 1.33%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.22%   |
| Silicon Motion                               | 1        | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 43       | 9.37%   |
| Intel JasperLake [UHD Graphics]                                                          | 32       | 6.97%   |
| Intel HD Graphics 530                                                                    | 25       | 5.45%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 25       | 5.45%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 22       | 4.79%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 22       | 4.79%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 20       | 4.36%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 19       | 4.14%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 16       | 3.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 16       | 3.49%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 11       | 2.4%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10       | 2.18%   |
| Intel HD Graphics 630                                                                    | 9        | 1.96%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 9        | 1.96%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 8        | 1.74%   |
| Intel HD Graphics 500                                                                    | 6        | 1.31%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 5        | 1.09%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 0.87%   |
| Intel HD Graphics 620                                                                    | 4        | 0.87%   |
| Intel HD Graphics 610                                                                    | 4        | 0.87%   |
| Intel HD Graphics 5500                                                                   | 4        | 0.87%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 4        | 0.87%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4        | 0.87%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4        | 0.87%   |
| Nvidia GT218 [GeForce 210]                                                               | 3        | 0.65%   |
| Nvidia GM107GL [Quadro K620]                                                             | 3        | 0.65%   |
| Intel UHD Graphics 620                                                                   | 3        | 0.65%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3        | 0.65%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3        | 0.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3        | 0.65%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 3        | 0.65%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 0.65%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3        | 0.65%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 3        | 0.65%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 2        | 0.44%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 0.44%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 0.44%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2        | 0.44%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 2        | 0.44%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 2        | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Intel          | 308      | 66.81%  |
| 1 x AMD            | 47       | 10.2%   |
| 1 x Nvidia         | 44       | 9.54%   |
| 1 x ASPEED         | 18       | 3.9%    |
| Other              | 17       | 3.69%   |
| 2 x Intel          | 9        | 1.95%   |
| 1 x Matrox         | 6        | 1.3%    |
| 2 x AMD            | 3        | 0.65%   |
| Intel + Nvidia     | 3        | 0.65%   |
| Intel + ASPEED     | 2        | 0.43%   |
| 1 x XGI            | 1        | 0.22%   |
| 1 x Silicon Motion | 1        | 0.22%   |
| Intel + AMD        | 1        | 0.22%   |
| AMD + Nvidia       | 1        | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 416      | 91.03%  |
| Proprietary | 23       | 5.03%   |
| Unknown     | 18       | 3.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 419      | 92.09%  |
| 1.01-2.0   | 9        | 1.98%   |
| 0.51-1.0   | 9        | 1.98%   |
| 7.01-8.0   | 5        | 1.1%    |
| 3.01-4.0   | 5        | 1.1%    |
| 5.01-6.0   | 3        | 0.66%   |
| 8.01-16.0  | 2        | 0.44%   |
| 2.01-3.0   | 1        | 0.22%   |
| 16.01-24.0 | 1        | 0.22%   |
| 0.01-0.5   | 1        | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 9        | 16.07%  |
| Dell                 | 7        | 12.5%   |
| Samsung Electronics  | 6        | 10.71%  |
| BenQ                 | 6        | 10.71%  |
| Sony                 | 3        | 5.36%   |
| LG Electronics       | 3        | 5.36%   |
| Lenovo               | 3        | 5.36%   |
| Hewlett-Packard      | 3        | 5.36%   |
| ASUSTek Computer     | 3        | 5.36%   |
| AOC                  | 3        | 5.36%   |
| Acer                 | 3        | 5.36%   |
| ViewSonic            | 1        | 1.79%   |
| Videoseven           | 1        | 1.79%   |
| Toshiba              | 1        | 1.79%   |
| LTV                  | 1        | 1.79%   |
| Insignia             | 1        | 1.79%   |
| AU Optronics         | 1        | 1.79%   |
| Ancor Communications | 1        | 1.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Sony LCD Monitor TV XV 1920x1080                                       | 2        | 3.33%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 2        | 3.33%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch               | 2        | 3.33%   |
| ViewSonic VA2342 SERIES VSCFA2B 1920x1080 510x290mm 23.1-inch          | 1        | 1.67%   |
| Videoseven WL19A IGM1908 1280x1024 380x300mm 19.1-inch                 | 1        | 1.67%   |
| Toshiba TV TSB0200 1920x1080 530x300mm 24.0-inch                       | 1        | 1.67%   |
| Sony TV  *30 SNY05D1 3840x2160 1660x930mm 74.9-inch                    | 1        | 1.67%   |
| Samsung Electronics Odyssey G8 SAM7256 3840x2160 700x400mm 31.7-inch   | 1        | 1.67%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                   | 1        | 1.67%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1210x680mm 54.6-inch | 1        | 1.67%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1110x620mm 50.1-inch | 1        | 1.67%   |
| LTV LTV1280M1A LTV0A3C 1024x768 800x450mm 36.1-inch                    | 1        | 1.67%   |
| LG Electronics LCD Monitor LG ULTRAGEAR 2560x1440                      | 1        | 1.67%   |
| LG Electronics LCD Monitor LG Ultra HD 7680x2160                       | 1        | 1.67%   |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1        | 1.67%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 1        | 1.67%   |
| Lenovo LEN-M93z-B  LEN0093 1920x1080 510x290mm 23.1-inch               | 1        | 1.67%   |
| Insignia LCD Monitor BBY0050 1920x1080 700x400mm 31.7-inch             | 1        | 1.67%   |
| Hewlett-Packard E241i HWP3123 1920x1200 520x320mm 24.0-inch            | 1        | 1.67%   |
| Hewlett-Packard All-in-One HWP4218 1600x900 440x250mm 19.9-inch        | 1        | 1.67%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch             | 1        | 1.67%   |
| Goldstar W2442 GSM56D9 1920x1080 530x300mm 24.0-inch                   | 1        | 1.67%   |
| Goldstar W2052 GSM4E88 1680x1050 470x300mm 22.0-inch                   | 1        | 1.67%   |
| Goldstar MP59G GSM5B35 1920x1080 600x340mm 27.2-inch                   | 1        | 1.67%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                   | 1        | 1.67%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch            | 1        | 1.67%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 580x240mm 24.7-inch            | 1        | 1.67%   |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch            | 1        | 1.67%   |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch               | 1        | 1.67%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 1        | 1.67%   |
| Goldstar LG FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch              | 1        | 1.67%   |
| Goldstar LCD Monitor GSM76F5 1920x1080 700x390mm 31.5-inch             | 1        | 1.67%   |
| Dell U2722D DEL422F 2560x1440 600x340mm 27.2-inch                      | 1        | 1.67%   |
| Dell SE2722H DELD116 1920x1080 600x340mm 27.2-inch                     | 1        | 1.67%   |
| Dell P3222QE DEL4246 3840x2160 700x390mm 31.5-inch                     | 1        | 1.67%   |
| Dell P2311H DEL4067 1920x1080 510x290mm 23.1-inch                      | 1        | 1.67%   |
| Dell P2219H DELA114 1920x1080 480x270mm 21.7-inch                      | 1        | 1.67%   |
| Dell LCD Monitor DELF003 1440x900 410x260mm 19.1-inch                  | 1        | 1.67%   |
| Dell 2001FP DELA008 1600x1200 410x310mm 20.2-inch                      | 1        | 1.67%   |
| BenQ XL2430T BNQ7F3D 1920x1080 530x300mm 24.0-inch                     | 1        | 1.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 27       | 49.09%  |
| 3840x2160 (4K)     | 8        | 14.55%  |
| 2560x1440 (QHD)    | 3        | 5.45%   |
| 1920x1200 (WUXGA)  | 2        | 3.64%   |
| 1680x1050 (WSXGA+) | 2        | 3.64%   |
| 1440x900 (WXGA+)   | 2        | 3.64%   |
| 1366x768 (WXGA)    | 2        | 3.64%   |
| Unknown            | 2        | 3.64%   |
| 7680x2160          | 1        | 1.82%   |
| 3440x1440          | 1        | 1.82%   |
| 2560x1080          | 1        | 1.82%   |
| 1600x900 (HD+)     | 1        | 1.82%   |
| 1600x1200          | 1        | 1.82%   |
| 1280x1024 (SXGA)   | 1        | 1.82%   |
| 1024x768 (XGA)     | 1        | 1.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 13       | 22.81%  |
| 27      | 7        | 12.28%  |
| 21      | 7        | 12.28%  |
| Unknown | 7        | 12.28%  |
| 19      | 4        | 7.02%   |
| 54      | 3        | 5.26%   |
| 31      | 3        | 5.26%   |
| 23      | 3        | 5.26%   |
| 34      | 2        | 3.51%   |
| 22      | 2        | 3.51%   |
| 74      | 1        | 1.75%   |
| 50      | 1        | 1.75%   |
| 36      | 1        | 1.75%   |
| 20      | 1        | 1.75%   |
| 18      | 1        | 1.75%   |
| 13      | 1        | 1.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 22       | 39.29%  |
| 401-500     | 14       | 25%     |
| Unknown     | 7        | 12.5%   |
| 1001-1500   | 4        | 7.14%   |
| 701-800     | 3        | 5.36%   |
| 601-700     | 3        | 5.36%   |
| 351-400     | 1        | 1.79%   |
| 301-350     | 1        | 1.79%   |
| 1501-2000   | 1        | 1.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 38       | 70.37%  |
| Unknown | 7        | 12.96%  |
| 16/10   | 5        | 9.26%   |
| 21/9    | 2        | 3.7%    |
| 5/4     | 1        | 1.85%   |
| 4/3     | 1        | 1.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 21       | 37.5%   |
| 301-350        | 7        | 12.5%   |
| Unknown        | 7        | 12.5%   |
| More than 1000 | 5        | 8.93%   |
| 351-500        | 5        | 8.93%   |
| 151-200        | 5        | 8.93%   |
| 251-300        | 3        | 5.36%   |
| 81-90          | 1        | 1.79%   |
| 141-150        | 1        | 1.79%   |
| 501-1000       | 1        | 1.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 35       | 61.4%   |
| 101-120 | 11       | 19.3%   |
| Unknown | 7        | 12.28%  |
| 121-160 | 2        | 3.51%   |
| 1-50    | 1        | 1.75%   |
| 161-240 | 1        | 1.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 394      | 86.03%  |
| 1     | 55       | 12.01%  |
| 2     | 9        | 1.97%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 376      | 60.45%  |
| Realtek Semiconductor           | 164      | 26.37%  |
| Broadcom                        | 21       | 3.38%   |
| Qualcomm Atheros                | 13       | 2.09%   |
| Mellanox Technologies           | 6        | 0.96%   |
| MediaTek                        | 5        | 0.8%    |
| IMC Networks                    | 4        | 0.64%   |
| Solarflare Communications       | 3        | 0.48%   |
| Ralink                          | 3        | 0.48%   |
| Marvell Technology Group        | 3        | 0.48%   |
| Chelsio Communications          | 3        | 0.48%   |
| D-Link                          | 2        | 0.32%   |
| Aquantia                        | 2        | 0.32%   |
| American Megatrends             | 2        | 0.32%   |
| 3Com                            | 2        | 0.32%   |
| U-Blox                          | 1        | 0.16%   |
| TP-Link                         | 1        | 0.16%   |
| Seeed Technology                | 1        | 0.16%   |
| Qualcomm Technologies           | 1        | 0.16%   |
| Qualcomm Atheros Communications | 1        | 0.16%   |
| QLogic                          | 1        | 0.16%   |
| NetGear                         | 1        | 0.16%   |
| Linksys                         | 1        | 0.16%   |
| Hewlett-Packard                 | 1        | 0.16%   |
| Google                          | 1        | 0.16%   |
| D-Link System                   | 1        | 0.16%   |
| Apple                           | 1        | 0.16%   |
| Accton Technology               | 1        | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 132      | 16.67%  |
| Intel Ethernet Controller I226-V                                              | 47       | 5.93%   |
| Intel Ethernet Controller I225-V                                              | 47       | 5.93%   |
| Intel I211 Gigabit Network Connection                                         | 45       | 5.68%   |
| Intel 82574L Gigabit Network Connection                                       | 40       | 5.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 34       | 4.29%   |
| Intel Ethernet Connection I217-LM                                             | 30       | 3.79%   |
| Intel I350 Gigabit Network Connection                                         | 22       | 2.78%   |
| Intel I210 Gigabit Network Connection                                         | 20       | 2.53%   |
| Intel 82576 Gigabit Network Connection                                        | 19       | 2.4%    |
| Realtek RTL8125 2.5GbE Controller                                             | 17       | 2.15%   |
| Intel Ethernet Connection (2) I219-LM                                         | 13       | 1.64%   |
| Intel 82583V Gigabit Network Connection                                       | 12       | 1.52%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 11       | 1.39%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 10       | 1.26%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 8        | 1.01%   |
| Intel Ethernet Connection (2) I219-V                                          | 8        | 1.01%   |
| Intel 82580 Gigabit Network Connection                                        | 8        | 1.01%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 8        | 1.01%   |
| Intel Wi-Fi 6 AX200                                                           | 7        | 0.88%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 7        | 0.88%   |
| Intel Ethernet Connection (5) I219-LM                                         | 6        | 0.76%   |
| Intel CNVi: Wi-Fi                                                             | 6        | 0.76%   |
| Intel 82575EB Gigabit Network Connection                                      | 6        | 0.76%   |
| Intel Ethernet Connection (7) I219-LM                                         | 5        | 0.63%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 5        | 0.63%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 5        | 0.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 4        | 0.51%   |
| Intel Wireless 7260                                                           | 4        | 0.51%   |
| Intel Wireless 3165                                                           | 4        | 0.51%   |
| Intel Ethernet Controller X550                                                | 4        | 0.51%   |
| Intel Ethernet Connection X553 1GbE                                           | 4        | 0.51%   |
| Intel Ethernet Connection I217-V                                              | 4        | 0.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 4        | 0.51%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 4        | 0.51%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 4        | 0.51%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 4        | 0.51%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 4        | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3        | 0.38%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 3        | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 45       | 48.39%  |
| Realtek Semiconductor           | 17       | 18.28%  |
| Qualcomm Atheros                | 10       | 10.75%  |
| MediaTek                        | 4        | 4.3%    |
| IMC Networks                    | 4        | 4.3%    |
| Ralink                          | 3        | 3.23%   |
| Broadcom                        | 3        | 3.23%   |
| D-Link                          | 2        | 2.15%   |
| TP-Link                         | 1        | 1.08%   |
| Qualcomm Technologies           | 1        | 1.08%   |
| Qualcomm Atheros Communications | 1        | 1.08%   |
| NetGear                         | 1        | 1.08%   |
| Linksys                         | 1        | 1.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 7        | 7.37%   |
| Intel CNVi: Wi-Fi                                                       | 6        | 6.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4        | 4.21%   |
| Intel Wireless 7260                                                     | 4        | 4.21%   |
| Intel Wireless 3165                                                     | 4        | 4.21%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4        | 4.21%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 4        | 4.21%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 4        | 4.21%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3        | 3.16%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3        | 3.16%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 3        | 3.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3        | 3.16%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2        | 2.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2        | 2.11%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 2        | 2.11%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2        | 2.11%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2        | 2.11%   |
| Intel Wireless 7265                                                     | 2        | 2.11%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2        | 2.11%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2        | 2.11%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1        | 1.05%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1        | 1.05%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 1.05%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1        | 1.05%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1        | 1.05%   |
| Realtek Bluetooth Adapter                                               | 1        | 1.05%   |
| Ralink RT5592 PCIe Wireless Network Adapter                             | 1        | 1.05%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1        | 1.05%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                    | 1        | 1.05%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]        | 1        | 1.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1        | 1.05%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 1.05%   |
| Qualcomm Atheros AR958x 802.11abgn Wireless Network Adapter             | 1        | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1        | 1.05%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 1.05%   |
| NetGear A6200 802.11a/b/g/n/ac Wireless Adapter [Broadcom BCM43526]     | 1        | 1.05%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1        | 1.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1        | 1.05%   |
| Linksys WUSB54G v4 802.11g Adapter [Ralink RT2500USB]                   | 1        | 1.05%   |
| Intel Wireless 8260                                                     | 1        | 1.05%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 356      | 64.03%  |
| Realtek Semiconductor     | 159      | 28.6%   |
| Broadcom                  | 18       | 3.24%   |
| Solarflare Communications | 3        | 0.54%   |
| Qualcomm Atheros          | 3        | 0.54%   |
| Marvell Technology Group  | 3        | 0.54%   |
| Chelsio Communications    | 3        | 0.54%   |
| Aquantia                  | 2        | 0.36%   |
| American Megatrends       | 2        | 0.36%   |
| 3Com                      | 2        | 0.36%   |
| QLogic                    | 1        | 0.18%   |
| Google                    | 1        | 0.18%   |
| D-Link System             | 1        | 0.18%   |
| Apple                     | 1        | 0.18%   |
| Accton Technology         | 1        | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 132      | 19.33%  |
| Intel Ethernet Controller I226-V                                              | 47       | 6.88%   |
| Intel Ethernet Controller I225-V                                              | 47       | 6.88%   |
| Intel I211 Gigabit Network Connection                                         | 45       | 6.59%   |
| Intel 82574L Gigabit Network Connection                                       | 40       | 5.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 34       | 4.98%   |
| Intel Ethernet Connection I217-LM                                             | 30       | 4.39%   |
| Intel I350 Gigabit Network Connection                                         | 22       | 3.22%   |
| Intel I210 Gigabit Network Connection                                         | 20       | 2.93%   |
| Intel 82576 Gigabit Network Connection                                        | 19       | 2.78%   |
| Realtek RTL8125 2.5GbE Controller                                             | 17       | 2.49%   |
| Intel Ethernet Connection (2) I219-LM                                         | 13       | 1.9%    |
| Intel 82583V Gigabit Network Connection                                       | 12       | 1.76%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 11       | 1.61%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 10       | 1.46%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 8        | 1.17%   |
| Intel Ethernet Connection (2) I219-V                                          | 8        | 1.17%   |
| Intel 82580 Gigabit Network Connection                                        | 8        | 1.17%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 8        | 1.17%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 7        | 1.02%   |
| Intel Ethernet Connection (5) I219-LM                                         | 6        | 0.88%   |
| Intel 82575EB Gigabit Network Connection                                      | 6        | 0.88%   |
| Intel Ethernet Connection (7) I219-LM                                         | 5        | 0.73%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 5        | 0.73%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 5        | 0.73%   |
| Intel Ethernet Controller X550                                                | 4        | 0.59%   |
| Intel Ethernet Connection X553 1GbE                                           | 4        | 0.59%   |
| Intel Ethernet Connection I217-V                                              | 4        | 0.59%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 4        | 0.59%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 4        | 0.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3        | 0.44%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3        | 0.44%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 3        | 0.44%   |
| Intel Ethernet Connection (2) I218-LM                                         | 3        | 0.44%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 0.44%   |
| Intel 82578DM Gigabit Network Connection                                      | 3        | 0.44%   |
| Intel 82575GB Gigabit Network Connection                                      | 3        | 0.44%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 0.44%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 3        | 0.44%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 3        | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 450      | 81.08%  |
| WiFi     | 91       | 16.4%   |
| Unknown  | 11       | 1.98%   |
| Modem    | 3        | 0.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 435      | 97.53%  |
| WiFi     | 11       | 2.47%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 4     | 111      | 24.13%  |
| 2     | 105      | 22.83%  |
| 3     | 91       | 19.78%  |
| 1     | 56       | 12.17%  |
| 6     | 34       | 7.39%   |
| 5     | 34       | 7.39%   |
| 7     | 10       | 2.17%   |
| 8     | 6        | 1.3%    |
| 9     | 5        | 1.09%   |
| 10    | 3        | 0.65%   |
| 0     | 3        | 0.65%   |
| 15    | 1        | 0.22%   |
| 12    | 1        | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 390      | 83.16%  |
| Yes  | 79       | 16.84%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 39       | 60%     |
| Cambridge Silicon Radio         | 6        | 9.23%   |
| Foxconn / Hon Hai               | 5        | 7.69%   |
| Realtek Semiconductor           | 4        | 6.15%   |
| IMC Networks                    | 3        | 4.62%   |
| MediaTek                        | 2        | 3.08%   |
| Ralink                          | 1        | 1.54%   |
| Qualcomm Atheros Communications | 1        | 1.54%   |
| Lite-On Technology              | 1        | 1.54%   |
| Broadcom                        | 1        | 1.54%   |
| ASUSTek Computer                | 1        | 1.54%   |
| Apple                           | 1        | 1.54%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Intel AX201 Bluetooth                                | 11       | 16.67%  |
| Intel Bluetooth wireless interface                   | 8        | 12.12%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 6        | 9.09%   |
| Intel AX200 Bluetooth                                | 6        | 9.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 6        | 9.09%   |
| Intel Wireless-AC 3168 Bluetooth                     | 4        | 6.06%   |
| Realtek Bluetooth Adapter                            | 3        | 4.55%   |
| Intel AX211 Bluetooth                                | 2        | 3.03%   |
| Intel AX210 Bluetooth                                | 2        | 3.03%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter            | 2        | 3.03%   |
| Realtek  Bluetooth 4.2 Adapter                       | 1        | 1.52%   |
| Ralink RT3290 Bluetooth                              | 1        | 1.52%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                | 1        | 1.52%   |
| MediaTek RZ608 Bluetooth Adapter                     | 1        | 1.52%   |
| MediaTek Bluetooth Adapter                           | 1        | 1.52%   |
| Lite-On Bluetooth USB Module                         | 1        | 1.52%   |
| Intel Centrino Bluetooth Wireless Transceiver        | 1        | 1.52%   |
| IMC Networks Realtek Bluetooth Adapter               | 1        | 1.52%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip | 1        | 1.52%   |
| IMC Networks MediaTek Bluetooth Adapter              | 1        | 1.52%   |
| Foxconn / Hon Hai Wireless_Device                    | 1        | 1.52%   |
| Foxconn / Hon Hai Bluetooth USB Module               | 1        | 1.52%   |
| Foxconn / Hon Hai Android ADB Interface              | 1        | 1.52%   |
| Broadcom HP Bluethunder                              | 1        | 1.52%   |
| ASUS Realtek Bluetooth 4.0 + High Speed Chip         | 1        | 1.52%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                 | 1        | 1.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 303      | 69.34%  |
| AMD                                          | 63       | 14.42%  |
| Nvidia                                       | 45       | 10.3%   |
| C-Media Electronics                          | 5        | 1.14%   |
| KTMicro                                      | 4        | 0.92%   |
| Logitech                                     | 3        | 0.69%   |
| ASUSTek Computer                             | 3        | 0.69%   |
| Plantronics                                  | 2        | 0.46%   |
| Micro Star International                     | 2        | 0.46%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.23%   |
| Yamaha                                       | 1        | 0.23%   |
| Texas Instruments                            | 1        | 0.23%   |
| SteelSeries ApS                              | 1        | 0.23%   |
| Sony                                         | 1        | 0.23%   |
| Elgato Systems                               | 1        | 0.23%   |
| Creative Labs                                | 1        | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 40       | 7.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 40       | 7.69%   |
| Intel Jasper Lake HD Audio                                                                        | 32       | 6.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 24       | 4.62%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 23       | 4.42%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 21       | 4.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 19       | 3.65%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 18       | 3.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 15       | 2.88%   |
| Intel 200 Series PCH HD Audio                                                                     | 15       | 2.88%   |
| Intel Cannon Lake PCH cAVS                                                                        | 13       | 2.5%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 13       | 2.5%    |
| Intel 8 Series HD Audio Controller                                                                | 11       | 2.12%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10       | 1.92%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 9        | 1.73%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 9        | 1.73%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 7        | 1.35%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 7        | 1.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7        | 1.35%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7        | 1.35%   |
| Nvidia High Definition Audio Controller                                                           | 6        | 1.15%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 6        | 1.15%   |
| AMD FCH Azalia Controller                                                                         | 6        | 1.15%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5        | 0.96%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5        | 0.96%   |
| Intel Broadwell-U Audio Controller                                                                | 5        | 0.96%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5        | 0.96%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5        | 0.96%   |
| Nvidia MCP61 High Definition Audio                                                                | 4        | 0.77%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4        | 0.77%   |
| KTMicro KT USB Audio                                                                              | 4        | 0.77%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4        | 0.77%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 4        | 0.77%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3        | 0.58%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3        | 0.58%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3        | 0.58%   |
| Intel Raptor Lake High Definition Audio Controller                                                | 3        | 0.58%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3        | 0.58%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3        | 0.58%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3        | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Samsung Electronics          | 79       | 15.74%  |
| Kingston                     | 72       | 14.34%  |
| SK hynix                     | 62       | 12.35%  |
| Crucial                      | 46       | 9.16%   |
| Unknown                      | 41       | 8.17%   |
| Corsair                      | 37       | 7.37%   |
| Micron Technology            | 33       | 6.57%   |
| G.Skill                      | 32       | 6.37%   |
| Unknown                      | 18       | 3.59%   |
| A-DATA Technology            | 10       | 1.99%   |
| Ramaxel Technology           | 9        | 1.79%   |
| Team                         | 7        | 1.39%   |
| Apacer                       | 6        | 1.2%    |
| Patriot                      | 5        | 1%      |
| Unknown (0x0C26)             | 4        | 0.8%    |
| Timetec                      | 4        | 0.8%    |
| Unknown (ABCD)               | 3        | 0.6%    |
| Transcend                    | 3        | 0.6%    |
| Patriot Memory (PDP Systems) | 3        | 0.6%    |
| OCZ                          | 3        | 0.6%    |
| Nanya Technology             | 3        | 0.6%    |
| Wodposit                     | 2        | 0.4%    |
| Unknown (0x0C6E)             | 2        | 0.4%    |
| Elpida                       | 2        | 0.4%    |
| AMD                          | 2        | 0.4%    |
| V-Color                      | 1        | 0.2%    |
| Unknown (AB)                 | 1        | 0.2%    |
| Unknown (0x7FFF)             | 1        | 0.2%    |
| Unknown (0x0DD5)             | 1        | 0.2%    |
| Unknown (0x0B45)             | 1        | 0.2%    |
| Toshiba                      | 1        | 0.2%    |
| Smart Modular                | 1        | 0.2%    |
| SK_Hynix                     | 1        | 0.2%    |
| Silicon Power                | 1        | 0.2%    |
| PNY                          | 1        | 0.2%    |
| Lexar Co Limited             | 1        | 0.2%    |
| Cors                         | 1        | 0.2%    |
| Avant                        | 1        | 0.2%    |
| ATP                          | 1        | 0.2%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown                                                        | 18       | 3.36%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s           | 6        | 1.12%   |
| Crucial RAM CT16G56C46S5.M8G1 16GB SODIMM DDR5 5600MT/s        | 6        | 1.12%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 5        | 0.93%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 5        | 0.93%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s        | 5        | 0.93%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s            | 5        | 0.93%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 5        | 0.93%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s        | 5        | 0.93%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s             | 4        | 0.75%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 4        | 0.75%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s           | 4        | 0.75%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 4        | 0.75%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 1600MT/s            | 4        | 0.75%   |
| Micron RAM 8ATF1G64AZ-2G6E1 8GB DIMM DDR4 2667MT/s             | 4        | 0.75%   |
| Unknown RAM Module 8GB 1600MT/s                                | 3        | 0.56%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 3        | 0.56%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 3        | 0.56%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s | 3        | 0.56%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 3        | 0.56%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s            | 3        | 0.56%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 2667MT/s            | 3        | 0.56%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 3        | 0.56%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s            | 3        | 0.56%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s           | 3        | 0.56%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s         | 3        | 0.56%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3000MT/s         | 3        | 0.56%   |
| Wodposit RAM WPBH26D408SWA-8G 8GB SODIMM DDR4 2400MT/s         | 2        | 0.37%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                    | 2        | 0.37%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s                      | 2        | 0.37%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 2        | 0.37%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 2        | 0.37%   |
| Unknown (0x0C6E) RAM Module 16GB SODIMM DDR4 3200MT/s          | 2        | 0.37%   |
| SK hynix RAM Module 4GB DIMM DDR4 2133MT/s                     | 2        | 0.37%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                     | 2        | 0.37%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2        | 0.37%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s           | 2        | 0.37%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s           | 2        | 0.37%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB RIMM DDR4 2133MT/s           | 2        | 0.37%   |
| SK hynix RAM HMA451R7AFR8N-TF 4GB RIMM DDR4 2133MT/s           | 2        | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 190      | 43.08%  |
| DDR3    | 175      | 39.68%  |
| DDR5    | 26       | 5.9%    |
| DDR2    | 17       | 3.85%   |
| Unknown | 16       | 3.63%   |
| SDRAM   | 7        | 1.59%   |
| LPDDR4  | 6        | 1.36%   |
| LPDDR5  | 2        | 0.45%   |
| DDR     | 2        | 0.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 274      | 63.43%  |
| SODIMM       | 148      | 34.26%  |
| Row Of Chips | 3        | 0.69%   |
| RIMM         | 3        | 0.69%   |
| Unknown      | 3        | 0.69%   |
| FB-DIMM      | 1        | 0.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 173      | 36.58%  |
| 4096  | 140      | 29.6%   |
| 16384 | 77       | 16.28%  |
| 2048  | 49       | 10.36%  |
| 32768 | 18       | 3.81%   |
| 1024  | 14       | 2.96%   |
| 512   | 2        | 0.42%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 131      | 27.7%   |
| 3200    | 60       | 12.68%  |
| 1333    | 57       | 12.05%  |
| 2400    | 47       | 9.94%   |
| 2667    | 45       | 9.51%   |
| 2133    | 34       | 7.19%   |
| 4800    | 18       | 3.81%   |
| 800     | 16       | 3.38%   |
| 2666    | 8        | 1.69%   |
| 667     | 8        | 1.69%   |
| 5600    | 7        | 1.48%   |
| Unknown | 6        | 1.27%   |
| 3600    | 5        | 1.06%   |
| 3000    | 5        | 1.06%   |
| 1067    | 4        | 0.85%   |
| 1066    | 4        | 0.85%   |
| 6400    | 3        | 0.63%   |
| 1866    | 3        | 0.63%   |
| 2933    | 2        | 0.42%   |
| 400     | 2        | 0.42%   |
| 5200    | 1        | 0.21%   |
| 3733    | 1        | 0.21%   |
| 3400    | 1        | 0.21%   |
| 2800    | 1        | 0.21%   |
| 1334    | 1        | 0.21%   |
| 1088    | 1        | 0.21%   |
| 533     | 1        | 0.21%   |
| 333     | 1        | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 2        | 50%     |
| Brother Industries | 2        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| HP LaserJet 2200          | 1        | 25%     |
| HP Color LaserJet CP1215  | 1        | 25%     |
| Brother HL-L5200DW series | 1        | 25%     |
| Brother HL-L2300D series  | 1        | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 50%     |
| Canon       | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seiko Epson PX-501A [Stylus NX400] | 1        | 50%     |
| Canon CanoScan LiDE 220            | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 4        | 66.67%  |
| Microdia            | 1        | 16.67%  |
| Chicony Electronics | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Microdia JOYACCESS JA-Webcam  | 1        | 16.67%  |
| Logitech Webcam C310          | 1        | 16.67%  |
| Logitech HD Pro Webcam C920   | 1        | 16.67%  |
| Logitech C920 HD Pro Webcam   | 1        | 16.67%  |
| Logitech BRIO Ultra HD Webcam | 1        | 16.67%  |
| Chicony HP 0.3MP Webcam       | 1        | 16.67%  |

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
| 1     | 275      | 58.89%  |
| 0     | 110      | 23.55%  |
| 2     | 59       | 12.63%  |
| 3     | 16       | 3.43%   |
| 4     | 7        | 1.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 324      | 77.14%  |
| Bluetooth                | 32       | 7.62%   |
| Net/wireless             | 26       | 6.19%   |
| Firewire controller      | 10       | 2.38%   |
| Net/ethernet             | 8        | 1.9%    |
| Sound                    | 6        | 1.43%   |
| Network                  | 6        | 1.43%   |
| Card reader              | 5        | 1.19%   |
| Storage/raid             | 2        | 0.48%   |
| Graphics card            | 1        | 0.24%   |

