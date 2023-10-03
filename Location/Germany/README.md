BSD in Germany - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for BSD in Germany.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Germany/Desktop/README.md) and [notebooks](/Location/Germany/Notebook/README.md).

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

Total: 2924

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | Notebook    | [7cfd3d40eb](https://bsd-hardware.info/?probe=7cfd3d40eb) | Sep 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [716f9b28ab](https://bsd-hardware.info/?probe=716f9b28ab) | Sep 30, 2023 |
| Sophos        | SG                          | Firewall    | [c46ccbd5b9](https://bsd-hardware.info/?probe=c46ccbd5b9) | Sep 30, 2023 |
| Sophos        | SG                          | Firewall    | [1429a7de9a](https://bsd-hardware.info/?probe=1429a7de9a) | Sep 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [fb21a44f71](https://bsd-hardware.info/?probe=fb21a44f71) | Sep 29, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [f50d617197](https://bsd-hardware.info/?probe=f50d617197) | Sep 28, 2023 |
| Gigabyte      | B450M S2H V2                | Desktop     | [31da8655d1](https://bsd-hardware.info/?probe=31da8655d1) | Sep 28, 2023 |
| Dell          | Latitude 5591               | Notebook    | [c30943def8](https://bsd-hardware.info/?probe=c30943def8) | Sep 28, 2023 |
| Sophos        | SG                          | Firewall    | [e6a4159f0c](https://bsd-hardware.info/?probe=e6a4159f0c) | Sep 28, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [b3f0a784ab](https://bsd-hardware.info/?probe=b3f0a784ab) | Sep 28, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [0b2b7195c1](https://bsd-hardware.info/?probe=0b2b7195c1) | Sep 26, 2023 |
| Unknown       | YL-J1900L4-V2               | Desktop     | [c186f8b50c](https://bsd-hardware.info/?probe=c186f8b50c) | Sep 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [1ba135fef1](https://bsd-hardware.info/?probe=1ba135fef1) | Sep 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [9c8516c8a8](https://bsd-hardware.info/?probe=9c8516c8a8) | Sep 24, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [6a2ce1e29f](https://bsd-hardware.info/?probe=6a2ce1e29f) | Sep 24, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [b31f8c12f8](https://bsd-hardware.info/?probe=b31f8c12f8) | Sep 24, 2023 |
| NU591         | 1.0                         | Desktop     | [99f3260ee0](https://bsd-hardware.info/?probe=99f3260ee0) | Sep 24, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [d99ed8ecd0](https://bsd-hardware.info/?probe=d99ed8ecd0) | Sep 23, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [80f0800cee](https://bsd-hardware.info/?probe=80f0800cee) | Sep 23, 2023 |
| PC Engines    | APU2                        | Desktop     | [3c7bd005ef](https://bsd-hardware.info/?probe=3c7bd005ef) | Sep 23, 2023 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [06d8f02eb7](https://bsd-hardware.info/?probe=06d8f02eb7) | Sep 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [16640c7f04](https://bsd-hardware.info/?probe=16640c7f04) | Sep 22, 2023 |
| Sophos        | SG                          | Firewall    | [54ff756b5b](https://bsd-hardware.info/?probe=54ff756b5b) | Sep 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [fcde651e99](https://bsd-hardware.info/?probe=fcde651e99) | Sep 21, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [e046bd9405](https://bsd-hardware.info/?probe=e046bd9405) | Sep 21, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [90f89eea16](https://bsd-hardware.info/?probe=90f89eea16) | Sep 21, 2023 |
| ASRock        | J3455B-ITX                  | Desktop     | [c5a2093552](https://bsd-hardware.info/?probe=c5a2093552) | Sep 21, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [de1bdf0601](https://bsd-hardware.info/?probe=de1bdf0601) | Sep 21, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [e84cddfaaf](https://bsd-hardware.info/?probe=e84cddfaaf) | Sep 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [3c479d7824](https://bsd-hardware.info/?probe=3c479d7824) | Sep 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [13ba11c952](https://bsd-hardware.info/?probe=13ba11c952) | Sep 20, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [92da10b93b](https://bsd-hardware.info/?probe=92da10b93b) | Sep 20, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [95286f41d9](https://bsd-hardware.info/?probe=95286f41d9) | Sep 19, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [3950a0580d](https://bsd-hardware.info/?probe=3950a0580d) | Sep 16, 2023 |
| Intel         | DENLOW_WS                   | Desktop     | [029b3cdd58](https://bsd-hardware.info/?probe=029b3cdd58) | Sep 16, 2023 |
| Dell          | 0R5KP9 A09                  | Server      | [54ff0b9d41](https://bsd-hardware.info/?probe=54ff0b9d41) | Sep 16, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [80707f8712](https://bsd-hardware.info/?probe=80707f8712) | Sep 16, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [9a30d2d88c](https://bsd-hardware.info/?probe=9a30d2d88c) | Sep 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [1808e7891c](https://bsd-hardware.info/?probe=1808e7891c) | Sep 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [d6acb378a1](https://bsd-hardware.info/?probe=d6acb378a1) | Sep 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [fe010506e6](https://bsd-hardware.info/?probe=fe010506e6) | Sep 15, 2023 |
| Alienware     | m15                         | Notebook    | [609d2ce1ce](https://bsd-hardware.info/?probe=609d2ce1ce) | Sep 14, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [227062e965](https://bsd-hardware.info/?probe=227062e965) | Sep 13, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [0068732d33](https://bsd-hardware.info/?probe=0068732d33) | Sep 13, 2023 |
| Dell          | 0KM5PX A02                  | Server      | [2028895de0](https://bsd-hardware.info/?probe=2028895de0) | Sep 13, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [5c89a7a1f1](https://bsd-hardware.info/?probe=5c89a7a1f1) | Sep 13, 2023 |
| HP            | ProBook 4530s               | Notebook    | [0b47c15c42](https://bsd-hardware.info/?probe=0b47c15c42) | Sep 12, 2023 |
| HP            | ProBook 4530s               | Notebook    | [4b6daa1f1c](https://bsd-hardware.info/?probe=4b6daa1f1c) | Sep 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [fd131bd648](https://bsd-hardware.info/?probe=fd131bd648) | Sep 11, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [0797783a1c](https://bsd-hardware.info/?probe=0797783a1c) | Sep 10, 2023 |
| Supermicro    | A1SRi-2558F                 | Mini pc     | [04e0638cca](https://bsd-hardware.info/?probe=04e0638cca) | Sep 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [3c85271913](https://bsd-hardware.info/?probe=3c85271913) | Sep 10, 2023 |
| HP            | 8103 A01                    | Mini pc     | [ff26b688eb](https://bsd-hardware.info/?probe=ff26b688eb) | Sep 09, 2023 |
| Apple         | PowerMac3,6                 | Desktop     | [36daf7ce75](https://bsd-hardware.info/?probe=36daf7ce75) | Sep 09, 2023 |
| Lenovo        | ThinkPad SL 2746N8G         | Notebook    | [07eda65608](https://bsd-hardware.info/?probe=07eda65608) | Sep 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [3bc1fc9c7b](https://bsd-hardware.info/?probe=3bc1fc9c7b) | Sep 09, 2023 |
| Sophos        | XG                          | Firewall    | [01ed655ea2](https://bsd-hardware.info/?probe=01ed655ea2) | Sep 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [68a0e23945](https://bsd-hardware.info/?probe=68a0e23945) | Sep 09, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [1d5aff2e2a](https://bsd-hardware.info/?probe=1d5aff2e2a) | Sep 08, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [fe6bcbc332](https://bsd-hardware.info/?probe=fe6bcbc332) | Sep 08, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [37e25cbcec](https://bsd-hardware.info/?probe=37e25cbcec) | Sep 08, 2023 |
| Lex           | Pineview-D                  | Desktop     | [351aabdb80](https://bsd-hardware.info/?probe=351aabdb80) | Sep 08, 2023 |
| PC Engines    | APU3                        | Desktop     | [ad38dcf54a](https://bsd-hardware.info/?probe=ad38dcf54a) | Sep 07, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | Desktop     | [451cfdf64f](https://bsd-hardware.info/?probe=451cfdf64f) | Sep 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [6361addd62](https://bsd-hardware.info/?probe=6361addd62) | Sep 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [48ca84af37](https://bsd-hardware.info/?probe=48ca84af37) | Sep 06, 2023 |
| PC Engines    | APU2                        | Desktop     | [d582e62190](https://bsd-hardware.info/?probe=d582e62190) | Sep 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [f757c58686](https://bsd-hardware.info/?probe=f757c58686) | Sep 05, 2023 |
| Dell          | 0PRWNC A05                  | Server      | [ded67b8cd6](https://bsd-hardware.info/?probe=ded67b8cd6) | Sep 04, 2023 |
| Dell          | 03X6X0 A02                  | Server      | [8d9b81f936](https://bsd-hardware.info/?probe=8d9b81f936) | Sep 04, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [25cc035e73](https://bsd-hardware.info/?probe=25cc035e73) | Sep 03, 2023 |
| PC Engines    | APU2                        | Desktop     | [c9d2cfe6fa](https://bsd-hardware.info/?probe=c9d2cfe6fa) | Sep 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [53cee3b3c8](https://bsd-hardware.info/?probe=53cee3b3c8) | Sep 03, 2023 |
| Biostar       | J4105NHU                    | Desktop     | [2ac770aa55](https://bsd-hardware.info/?probe=2ac770aa55) | Sep 03, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [f95d1da00c](https://bsd-hardware.info/?probe=f95d1da00c) | Sep 01, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [1f4bf47cab](https://bsd-hardware.info/?probe=1f4bf47cab) | Sep 01, 2023 |
| Sophos        | UTM                         | Firewall    | [01a7eea7b9](https://bsd-hardware.info/?probe=01a7eea7b9) | Aug 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [b59ce07b49](https://bsd-hardware.info/?probe=b59ce07b49) | Aug 30, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [56ac0149f8](https://bsd-hardware.info/?probe=56ac0149f8) | Aug 30, 2023 |
| CncTion       | N6000-4L B0                 | Desktop     | [81cbfbffca](https://bsd-hardware.info/?probe=81cbfbffca) | Aug 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [fc384f5de7](https://bsd-hardware.info/?probe=fc384f5de7) | Aug 28, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | Desktop     | [a47cd8ee32](https://bsd-hardware.info/?probe=a47cd8ee32) | Aug 27, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [5025d5adb6](https://bsd-hardware.info/?probe=5025d5adb6) | Aug 27, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [a684024d8e](https://bsd-hardware.info/?probe=a684024d8e) | Aug 27, 2023 |
| PC Engines    | APU                         | Desktop     | [3b29671556](https://bsd-hardware.info/?probe=3b29671556) | Aug 26, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [ed6162710b](https://bsd-hardware.info/?probe=ed6162710b) | Aug 26, 2023 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [a487121854](https://bsd-hardware.info/?probe=a487121854) | Aug 26, 2023 |
| IGEL Techn... | D220                        | Desktop     | [a7686520e1](https://bsd-hardware.info/?probe=a7686520e1) | Aug 26, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [662ce63a50](https://bsd-hardware.info/?probe=662ce63a50) | Aug 25, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [8c6f7098f9](https://bsd-hardware.info/?probe=8c6f7098f9) | Aug 25, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [b8f1609842](https://bsd-hardware.info/?probe=b8f1609842) | Aug 25, 2023 |
| CncTion       | N6000-4L B0                 | Desktop     | [d8a9af2435](https://bsd-hardware.info/?probe=d8a9af2435) | Aug 24, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [a8fa821e5e](https://bsd-hardware.info/?probe=a8fa821e5e) | Aug 24, 2023 |
| Supermicro    | H12SSW-iN                   | Server      | [d0be592303](https://bsd-hardware.info/?probe=d0be592303) | Aug 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [74a7137090](https://bsd-hardware.info/?probe=74a7137090) | Aug 22, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [8622d78a7c](https://bsd-hardware.info/?probe=8622d78a7c) | Aug 22, 2023 |
| Gigabyte      | H610I DDR4                  | Desktop     | [f4310832c2](https://bsd-hardware.info/?probe=f4310832c2) | Aug 22, 2023 |
| Intel         | JSL MRD                     | Desktop     | [56165c654b](https://bsd-hardware.info/?probe=56165c654b) | Aug 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [03da20b37e](https://bsd-hardware.info/?probe=03da20b37e) | Aug 22, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [71e00307ae](https://bsd-hardware.info/?probe=71e00307ae) | Aug 22, 2023 |
| PC Engines    | APU2                        | Desktop     | [3e32acfdc4](https://bsd-hardware.info/?probe=3e32acfdc4) | Aug 22, 2023 |
| Gigabyte      | H110M-D2P-WG-CF             | Desktop     | [a91c61e3e3](https://bsd-hardware.info/?probe=a91c61e3e3) | Aug 21, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ef28836f5c](https://bsd-hardware.info/?probe=ef28836f5c) | Aug 20, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [01d58784e6](https://bsd-hardware.info/?probe=01d58784e6) | Aug 20, 2023 |
| HP            | 8594                        | Desktop     | [b3e5652c1b](https://bsd-hardware.info/?probe=b3e5652c1b) | Aug 20, 2023 |
| HP            | 8594                        | Desktop     | [77d6ac3f77](https://bsd-hardware.info/?probe=77d6ac3f77) | Aug 20, 2023 |
| Sophos        | XG                          | Firewall    | [2f35580968](https://bsd-hardware.info/?probe=2f35580968) | Aug 19, 2023 |
| Sophos        | SG                          | Firewall    | [30708a275a](https://bsd-hardware.info/?probe=30708a275a) | Aug 18, 2023 |
| Dell          | Latitude 5591               | Notebook    | [972da999fb](https://bsd-hardware.info/?probe=972da999fb) | Aug 18, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [b3625ada4b](https://bsd-hardware.info/?probe=b3625ada4b) | Aug 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [de9a146c44](https://bsd-hardware.info/?probe=de9a146c44) | Aug 16, 2023 |
| Unknown       | Q2XX V1.0                   | Desktop     | [be1252b2ff](https://bsd-hardware.info/?probe=be1252b2ff) | Aug 16, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [18559e2fde](https://bsd-hardware.info/?probe=18559e2fde) | Aug 15, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [73c35b0a8a](https://bsd-hardware.info/?probe=73c35b0a8a) | Aug 15, 2023 |
| Intel         | SKYBAY                      | Desktop     | [77fbc82e41](https://bsd-hardware.info/?probe=77fbc82e41) | Aug 15, 2023 |
| Protectli     | VP4620                      | Desktop     | [0f0695d190](https://bsd-hardware.info/?probe=0f0695d190) | Aug 15, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [680fdcd4f6](https://bsd-hardware.info/?probe=680fdcd4f6) | Aug 14, 2023 |
| PC Engines    | APU2                        | Desktop     | [bdd3050b5f](https://bsd-hardware.info/?probe=bdd3050b5f) | Aug 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [b8e7299136](https://bsd-hardware.info/?probe=b8e7299136) | Aug 13, 2023 |
| Dell          | Latitude 5591               | Notebook    | [a599361016](https://bsd-hardware.info/?probe=a599361016) | Aug 13, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [6c4364fe15](https://bsd-hardware.info/?probe=6c4364fe15) | Aug 13, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [b978121948](https://bsd-hardware.info/?probe=b978121948) | Aug 13, 2023 |
| PC Engines    | apu4                        | Desktop     | [24e025662c](https://bsd-hardware.info/?probe=24e025662c) | Aug 12, 2023 |
| CncTion       | J4125-4L-I225               | Desktop     | [983bbef1fb](https://bsd-hardware.info/?probe=983bbef1fb) | Aug 12, 2023 |
| WeiBu         | ADL-N Prod                  | Desktop     | [26bbe26e7c](https://bsd-hardware.info/?probe=26bbe26e7c) | Aug 12, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [27f84c75b5](https://bsd-hardware.info/?probe=27f84c75b5) | Aug 11, 2023 |
| PC Engines    | APU2                        | Desktop     | [2e9106fc92](https://bsd-hardware.info/?probe=2e9106fc92) | Aug 11, 2023 |
| Gigabyte      | AX370M-DS3H-CF              | Desktop     | [7b00ddd0a1](https://bsd-hardware.info/?probe=7b00ddd0a1) | Aug 11, 2023 |
| PC Engines    | apu1                        | Desktop     | [0b3594d9a3](https://bsd-hardware.info/?probe=0b3594d9a3) | Aug 11, 2023 |
| PC Engines    | apu4                        | Desktop     | [b81f51408d](https://bsd-hardware.info/?probe=b81f51408d) | Aug 10, 2023 |
| Sophos        | SG                          | Firewall    | [ee7cfb0c22](https://bsd-hardware.info/?probe=ee7cfb0c22) | Aug 10, 2023 |
| Sophos        | UTM                         | Firewall    | [e7e8344a31](https://bsd-hardware.info/?probe=e7e8344a31) | Aug 09, 2023 |
| PC Engines    | APU2                        | Desktop     | [be0e8bf959](https://bsd-hardware.info/?probe=be0e8bf959) | Aug 09, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [fac2fa5cbe](https://bsd-hardware.info/?probe=fac2fa5cbe) | Aug 08, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [8720a76ea8](https://bsd-hardware.info/?probe=8720a76ea8) | Aug 08, 2023 |
| Fujitsu       | D3049-A1 S26361-D3049-A1... | Server      | [322b24ffa1](https://bsd-hardware.info/?probe=322b24ffa1) | Aug 08, 2023 |
| Acer          | Veriton N2620G              | Desktop     | [2acf1e4557](https://bsd-hardware.info/?probe=2acf1e4557) | Aug 08, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [aeccb6e70c](https://bsd-hardware.info/?probe=aeccb6e70c) | Aug 07, 2023 |
| Lanner        | FW-7543 B-GA                | Desktop     | [dadf592128](https://bsd-hardware.info/?probe=dadf592128) | Aug 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [eceed9eb7a](https://bsd-hardware.info/?probe=eceed9eb7a) | Aug 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [9c4dbcfd67](https://bsd-hardware.info/?probe=9c4dbcfd67) | Aug 05, 2023 |
| Lanner        | FW-7543 B-GA                | Desktop     | [6236e692de](https://bsd-hardware.info/?probe=6236e692de) | Aug 05, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [283fce4c68](https://bsd-hardware.info/?probe=283fce4c68) | Aug 05, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [c449203453](https://bsd-hardware.info/?probe=c449203453) | Aug 04, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [ea7a6fba73](https://bsd-hardware.info/?probe=ea7a6fba73) | Aug 04, 2023 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [62ed2f59f6](https://bsd-hardware.info/?probe=62ed2f59f6) | Aug 04, 2023 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [b6aafbefd3](https://bsd-hardware.info/?probe=b6aafbefd3) | Aug 04, 2023 |
| PC Engines    | APU2                        | Desktop     | [78c8ed6a89](https://bsd-hardware.info/?probe=78c8ed6a89) | Aug 03, 2023 |
| Dell          | 045M96 A02                  | Server      | [17cf8cd2f0](https://bsd-hardware.info/?probe=17cf8cd2f0) | Aug 03, 2023 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [b3fd8251db](https://bsd-hardware.info/?probe=b3fd8251db) | Aug 02, 2023 |
| Shuttle       | DH610                       | Desktop     | [bbdd78fe4b](https://bsd-hardware.info/?probe=bbdd78fe4b) | Aug 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [42c65b8b8b](https://bsd-hardware.info/?probe=42c65b8b8b) | Aug 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [09d17597cf](https://bsd-hardware.info/?probe=09d17597cf) | Aug 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [2a2e7a98e3](https://bsd-hardware.info/?probe=2a2e7a98e3) | Aug 01, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [65667b2f29](https://bsd-hardware.info/?probe=65667b2f29) | Aug 01, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [aa708122cf](https://bsd-hardware.info/?probe=aa708122cf) | Aug 01, 2023 |
| Shuttle       | DH610                       | Desktop     | [e7c63c97d3](https://bsd-hardware.info/?probe=e7c63c97d3) | Aug 01, 2023 |
| Shuttle       | DH370                       | Desktop     | [a3ab1c6344](https://bsd-hardware.info/?probe=a3ab1c6344) | Jul 31, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [9bd5d8fd54](https://bsd-hardware.info/?probe=9bd5d8fd54) | Jul 31, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [42fcdacbf7](https://bsd-hardware.info/?probe=42fcdacbf7) | Jul 31, 2023 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [f8ade878ce](https://bsd-hardware.info/?probe=f8ade878ce) | Jul 30, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [64137e0eec](https://bsd-hardware.info/?probe=64137e0eec) | Jul 29, 2023 |
| HP            | Notebook                    | Notebook    | [360790274a](https://bsd-hardware.info/?probe=360790274a) | Jul 29, 2023 |
| AWOW          | AK34Pro                     | Mini pc     | [7c8e0ac36d](https://bsd-hardware.info/?probe=7c8e0ac36d) | Jul 29, 2023 |
| PC Engines    | APU2                        | Desktop     | [5eddd5369a](https://bsd-hardware.info/?probe=5eddd5369a) | Jul 28, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [0bb6b16689](https://bsd-hardware.info/?probe=0bb6b16689) | Jul 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [1c6ab6b999](https://bsd-hardware.info/?probe=1c6ab6b999) | Jul 28, 2023 |
| Sophos        | UTM                         | Firewall    | [c33c212896](https://bsd-hardware.info/?probe=c33c212896) | Jul 28, 2023 |
| PC Engines    | apu1                        | Desktop     | [8bc97daada](https://bsd-hardware.info/?probe=8bc97daada) | Jul 27, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [64b577cd8e](https://bsd-hardware.info/?probe=64b577cd8e) | Jul 27, 2023 |
| NF541         | 1.0                         | Desktop     | [ba959613a5](https://bsd-hardware.info/?probe=ba959613a5) | Jul 26, 2023 |
| Cisco         | ASA5525 A0                  | Desktop     | [f4409bdc8f](https://bsd-hardware.info/?probe=f4409bdc8f) | Jul 26, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [d9c7f4173a](https://bsd-hardware.info/?probe=d9c7f4173a) | Jul 25, 2023 |
| Sophos        | XG                          | Firewall    | [bcf0e85fdc](https://bsd-hardware.info/?probe=bcf0e85fdc) | Jul 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [f7728cee03](https://bsd-hardware.info/?probe=f7728cee03) | Jul 25, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [8aa3f5491e](https://bsd-hardware.info/?probe=8aa3f5491e) | Jul 25, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [af215ad226](https://bsd-hardware.info/?probe=af215ad226) | Jul 24, 2023 |
| PC Engines    | apu4                        | Desktop     | [0aa9951131](https://bsd-hardware.info/?probe=0aa9951131) | Jul 24, 2023 |
| PC Engines    | apu4                        | Desktop     | [514dc1e9f9](https://bsd-hardware.info/?probe=514dc1e9f9) | Jul 24, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [dec2c34899](https://bsd-hardware.info/?probe=dec2c34899) | Jul 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [aab49bd228](https://bsd-hardware.info/?probe=aab49bd228) | Jul 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [438424a9d9](https://bsd-hardware.info/?probe=438424a9d9) | Jul 23, 2023 |
| PC Engines    | apu4                        | Desktop     | [ea9a81b423](https://bsd-hardware.info/?probe=ea9a81b423) | Jul 23, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [3b16dab962](https://bsd-hardware.info/?probe=3b16dab962) | Jul 22, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [7e1b416d09](https://bsd-hardware.info/?probe=7e1b416d09) | Jul 21, 2023 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [489c685ec4](https://bsd-hardware.info/?probe=489c685ec4) | Jul 21, 2023 |
| AZW           | EQ                          | Desktop     | [9883a89b8d](https://bsd-hardware.info/?probe=9883a89b8d) | Jul 21, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [efe49f9e5d](https://bsd-hardware.info/?probe=efe49f9e5d) | Jul 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [cce6d65dfb](https://bsd-hardware.info/?probe=cce6d65dfb) | Jul 20, 2023 |
| Lenovo        | ThinkPad T520 42435GG       | Notebook    | [f3aa06579e](https://bsd-hardware.info/?probe=f3aa06579e) | Jul 20, 2023 |
| Dell          | 08CYF7 A03                  | Server      | [67e68a4ad9](https://bsd-hardware.info/?probe=67e68a4ad9) | Jul 19, 2023 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [cbb13789d2](https://bsd-hardware.info/?probe=cbb13789d2) | Jul 19, 2023 |
| Dell          | 0MD99X A12                  | Server      | [eaabbf3ff3](https://bsd-hardware.info/?probe=eaabbf3ff3) | Jul 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [e487955dea](https://bsd-hardware.info/?probe=e487955dea) | Jul 18, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [35ab9e002d](https://bsd-hardware.info/?probe=35ab9e002d) | Jul 17, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [b76e5e8a87](https://bsd-hardware.info/?probe=b76e5e8a87) | Jul 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [8d82f25df2](https://bsd-hardware.info/?probe=8d82f25df2) | Jul 16, 2023 |
| Unknown       | Unknown                     | Firewall    | [af05859a76](https://bsd-hardware.info/?probe=af05859a76) | Jul 16, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [a2602b7fbf](https://bsd-hardware.info/?probe=a2602b7fbf) | Jul 16, 2023 |
| Gigabyte      | GB-BSi7-1165G7              | Desktop     | [c5f92a4c5e](https://bsd-hardware.info/?probe=c5f92a4c5e) | Jul 14, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [0b90f241cd](https://bsd-hardware.info/?probe=0b90f241cd) | Jul 13, 2023 |
| PICO PC       | JSL-4L                      | Desktop     | [d93e338744](https://bsd-hardware.info/?probe=d93e338744) | Jul 13, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [535720220a](https://bsd-hardware.info/?probe=535720220a) | Jul 13, 2023 |
| Supermicro    | X11SCH-F                    | Server      | [8f25848f38](https://bsd-hardware.info/?probe=8f25848f38) | Jul 13, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [c2cb1e21fa](https://bsd-hardware.info/?probe=c2cb1e21fa) | Jul 11, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [96bda9f774](https://bsd-hardware.info/?probe=96bda9f774) | Jul 11, 2023 |
| Tactus        | GeoBook 140                 | Notebook    | [4b7383c876](https://bsd-hardware.info/?probe=4b7383c876) | Jul 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [5625dd24f6](https://bsd-hardware.info/?probe=5625dd24f6) | Jul 11, 2023 |
| PICO PC       | JSL-4L                      | Desktop     | [d8c9a61dcf](https://bsd-hardware.info/?probe=d8c9a61dcf) | Jul 10, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [3a544928aa](https://bsd-hardware.info/?probe=3a544928aa) | Jul 09, 2023 |
| MiTAC         | PH13CMI                     | Desktop     | [6d0cd37fce](https://bsd-hardware.info/?probe=6d0cd37fce) | Jul 09, 2023 |
| Biostar       | A68N-2100K                  | Desktop     | [20cb208208](https://bsd-hardware.info/?probe=20cb208208) | Jul 09, 2023 |
| Lex           | Pineview-D                  | Desktop     | [290c53a822](https://bsd-hardware.info/?probe=290c53a822) | Jul 09, 2023 |
| Lenovo        | ThinkPad X250 20CLS13Q06    | Notebook    | [c318ab3cc7](https://bsd-hardware.info/?probe=c318ab3cc7) | Jul 09, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [9cd5d7878b](https://bsd-hardware.info/?probe=9cd5d7878b) | Jul 07, 2023 |
| Yanling       | YL-ELU3L                    | Desktop     | [0a3c74b25c](https://bsd-hardware.info/?probe=0a3c74b25c) | Jul 07, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [5d896a607e](https://bsd-hardware.info/?probe=5d896a607e) | Jul 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [3644875d54](https://bsd-hardware.info/?probe=3644875d54) | Jul 03, 2023 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [877c048c7d](https://bsd-hardware.info/?probe=877c048c7d) | Jul 03, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [2053dbb697](https://bsd-hardware.info/?probe=2053dbb697) | Jul 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [3725d44c33](https://bsd-hardware.info/?probe=3725d44c33) | Jul 01, 2023 |
| Supermicro    | X11SCL-IF                   | Server      | [0f9a1dc60c](https://bsd-hardware.info/?probe=0f9a1dc60c) | Jul 01, 2023 |
| PC Engines    | apu4                        | Desktop     | [62f0b60653](https://bsd-hardware.info/?probe=62f0b60653) | Jun 30, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [d60c967edb](https://bsd-hardware.info/?probe=d60c967edb) | Jun 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [075deef24f](https://bsd-hardware.info/?probe=075deef24f) | Jun 28, 2023 |
| CncTion       | J4125-4L-I225               | Desktop     | [1785cb2fa3](https://bsd-hardware.info/?probe=1785cb2fa3) | Jun 28, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [2eff359d8f](https://bsd-hardware.info/?probe=2eff359d8f) | Jun 28, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [bcad942162](https://bsd-hardware.info/?probe=bcad942162) | Jun 26, 2023 |
| Unknown       | YL-SKUL6                    | Desktop     | [1512f63972](https://bsd-hardware.info/?probe=1512f63972) | Jun 26, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [fa177a2538](https://bsd-hardware.info/?probe=fa177a2538) | Jun 26, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [54ef7dc131](https://bsd-hardware.info/?probe=54ef7dc131) | Jun 26, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [b056cd0426](https://bsd-hardware.info/?probe=b056cd0426) | Jun 26, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [5ad411cd6b](https://bsd-hardware.info/?probe=5ad411cd6b) | Jun 25, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [8a2ea60929](https://bsd-hardware.info/?probe=8a2ea60929) | Jun 25, 2023 |
| Sophos        | SG                          | Firewall    | [11e1176b5e](https://bsd-hardware.info/?probe=11e1176b5e) | Jun 24, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [18cf91f3a4](https://bsd-hardware.info/?probe=18cf91f3a4) | Jun 23, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [bb4dc2b1a2](https://bsd-hardware.info/?probe=bb4dc2b1a2) | Jun 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [16ceade742](https://bsd-hardware.info/?probe=16ceade742) | Jun 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [508aa0bdb4](https://bsd-hardware.info/?probe=508aa0bdb4) | Jun 23, 2023 |
| Sophos        | SG                          | Firewall    | [6763145000](https://bsd-hardware.info/?probe=6763145000) | Jun 22, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [4f80d81bbe](https://bsd-hardware.info/?probe=4f80d81bbe) | Jun 20, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | Notebook    | [6969cd9e1a](https://bsd-hardware.info/?probe=6969cd9e1a) | Jun 20, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | Notebook    | [461a92a1a2](https://bsd-hardware.info/?probe=461a92a1a2) | Jun 20, 2023 |
| Yanling       | YL-KBRL2 Series Ver:1.02    | Desktop     | [9e8d6110f4](https://bsd-hardware.info/?probe=9e8d6110f4) | Jun 19, 2023 |
| LANCOM Sys... | UF-60                       | Desktop     | [96904b8bdd](https://bsd-hardware.info/?probe=96904b8bdd) | Jun 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [5fc629699d](https://bsd-hardware.info/?probe=5fc629699d) | Jun 18, 2023 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [9f41fa4740](https://bsd-hardware.info/?probe=9f41fa4740) | Jun 18, 2023 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [8eb0be633d](https://bsd-hardware.info/?probe=8eb0be633d) | Jun 18, 2023 |
| Dell          | Latitude E6520              | Notebook    | [98868960d5](https://bsd-hardware.info/?probe=98868960d5) | Jun 18, 2023 |
| ASRock        | Z97 Professional            | Desktop     | [c978ddda86](https://bsd-hardware.info/?probe=c978ddda86) | Jun 18, 2023 |
| Sophos        | SG                          | Firewall    | [94a6b615cb](https://bsd-hardware.info/?probe=94a6b615cb) | Jun 17, 2023 |
| Samsung       | NC210/NC110                 | Notebook    | [06f5a9210b](https://bsd-hardware.info/?probe=06f5a9210b) | Jun 17, 2023 |
| Apple         | MacBook7,1                  | Notebook    | [6412e6fb23](https://bsd-hardware.info/?probe=6412e6fb23) | Jun 16, 2023 |
| AMD           | Kabini CRB                  | Desktop     | [b774a8b586](https://bsd-hardware.info/?probe=b774a8b586) | Jun 16, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [b9c5b6ec05](https://bsd-hardware.info/?probe=b9c5b6ec05) | Jun 15, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [70b0e8172d](https://bsd-hardware.info/?probe=70b0e8172d) | Jun 14, 2023 |
| PC Engines    | apu4                        | Desktop     | [ea036662ca](https://bsd-hardware.info/?probe=ea036662ca) | Jun 14, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [4a6667249e](https://bsd-hardware.info/?probe=4a6667249e) | Jun 13, 2023 |
| Lenovo        | ThinkPad T530 2429AP0       | Notebook    | [ddf37e7b17](https://bsd-hardware.info/?probe=ddf37e7b17) | Jun 13, 2023 |
| Samsung       | NC210/NC110                 | Notebook    | [dad27d6099](https://bsd-hardware.info/?probe=dad27d6099) | Jun 13, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [015a5d839a](https://bsd-hardware.info/?probe=015a5d839a) | Jun 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [27617e1ca6](https://bsd-hardware.info/?probe=27617e1ca6) | Jun 13, 2023 |
| HP            | 3397                        | Desktop     | [a918ce0c4b](https://bsd-hardware.info/?probe=a918ce0c4b) | Jun 12, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [04ae7435e5](https://bsd-hardware.info/?probe=04ae7435e5) | Jun 12, 2023 |
| MSI           | A320M GRENADE               | Desktop     | [6e0b1f598f](https://bsd-hardware.info/?probe=6e0b1f598f) | Jun 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [02509df772](https://bsd-hardware.info/?probe=02509df772) | Jun 12, 2023 |
| Sophos        | UTM                         | Firewall    | [d4856d7798](https://bsd-hardware.info/?probe=d4856d7798) | Jun 11, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [2d2052de27](https://bsd-hardware.info/?probe=2d2052de27) | Jun 11, 2023 |
| HP            | 15                          | Notebook    | [4664b4c93f](https://bsd-hardware.info/?probe=4664b4c93f) | Jun 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [8988baa83b](https://bsd-hardware.info/?probe=8988baa83b) | Jun 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [40bb474319](https://bsd-hardware.info/?probe=40bb474319) | Jun 10, 2023 |
| ASRock        | B85M-HDS                    | Desktop     | [09a4700a14](https://bsd-hardware.info/?probe=09a4700a14) | Jun 09, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [d21bdf0cdb](https://bsd-hardware.info/?probe=d21bdf0cdb) | Jun 09, 2023 |
| Wortmann      | terra Nettop 2700           | Desktop     | [e4a90ea530](https://bsd-hardware.info/?probe=e4a90ea530) | Jun 08, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [1ae49c4706](https://bsd-hardware.info/?probe=1ae49c4706) | Jun 08, 2023 |
| Sophos        | SG                          | Firewall    | [6cf087f800](https://bsd-hardware.info/?probe=6cf087f800) | Jun 08, 2023 |
| Intel         | SKYBAY                      | Desktop     | [f1b649ed11](https://bsd-hardware.info/?probe=f1b649ed11) | Jun 08, 2023 |
| Lanner        | FW-7543 B-GA                | Desktop     | [ee85efd1c0](https://bsd-hardware.info/?probe=ee85efd1c0) | Jun 08, 2023 |
| LANCOM Sys... | UF-60                       | Desktop     | [204f10b60f](https://bsd-hardware.info/?probe=204f10b60f) | Jun 07, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [4e57bbcdb5](https://bsd-hardware.info/?probe=4e57bbcdb5) | Jun 06, 2023 |
| Intel         | DENLOW_WS                   | Desktop     | [ce3bef7b5a](https://bsd-hardware.info/?probe=ce3bef7b5a) | Jun 06, 2023 |
| CncTion       | N6000-4L B0                 | Desktop     | [c9ec51aa84](https://bsd-hardware.info/?probe=c9ec51aa84) | Jun 05, 2023 |
| HP            | 3397                        | Desktop     | [6783902b93](https://bsd-hardware.info/?probe=6783902b93) | Jun 05, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [cf9ed85e65](https://bsd-hardware.info/?probe=cf9ed85e65) | Jun 05, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [fc66ebba25](https://bsd-hardware.info/?probe=fc66ebba25) | Jun 05, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [42e80f8003](https://bsd-hardware.info/?probe=42e80f8003) | Jun 05, 2023 |
| Sophos        | UTM                         | Firewall    | [05ee8903b5](https://bsd-hardware.info/?probe=05ee8903b5) | Jun 04, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [ab3919bc32](https://bsd-hardware.info/?probe=ab3919bc32) | Jun 04, 2023 |
| Dell          | 0PC5F7 A03                  | Desktop     | [23bd5ef252](https://bsd-hardware.info/?probe=23bd5ef252) | Jun 04, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [56a9981ff3](https://bsd-hardware.info/?probe=56a9981ff3) | Jun 03, 2023 |
| PC Engines    | APU2                        | Desktop     | [31c697459b](https://bsd-hardware.info/?probe=31c697459b) | Jun 02, 2023 |
| HP            | ProLiant DL360p Gen8        | Server      | [300b958d60](https://bsd-hardware.info/?probe=300b958d60) | May 30, 2023 |
| HP            | 3397                        | Desktop     | [1f8a9a4f27](https://bsd-hardware.info/?probe=1f8a9a4f27) | May 29, 2023 |
| ASRock        | H410M/ac                    | Desktop     | [d3e3d20cc4](https://bsd-hardware.info/?probe=d3e3d20cc4) | May 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [2827d90215](https://bsd-hardware.info/?probe=2827d90215) | May 28, 2023 |
| Tactus        | GeoFlex 110                 | Notebook    | [df93ad7e83](https://bsd-hardware.info/?probe=df93ad7e83) | May 27, 2023 |
| HP            | 3397                        | Desktop     | [036d4e087c](https://bsd-hardware.info/?probe=036d4e087c) | May 27, 2023 |
| HP            | 3397                        | Desktop     | [19abd8768e](https://bsd-hardware.info/?probe=19abd8768e) | May 27, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [81775d5ca1](https://bsd-hardware.info/?probe=81775d5ca1) | May 26, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [aad8268158](https://bsd-hardware.info/?probe=aad8268158) | May 24, 2023 |
| Nitrokey      | NitroWall                   | Desktop     | [1b3b451dee](https://bsd-hardware.info/?probe=1b3b451dee) | May 24, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [fff8a7a86f](https://bsd-hardware.info/?probe=fff8a7a86f) | May 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [4c7e1d476d](https://bsd-hardware.info/?probe=4c7e1d476d) | May 23, 2023 |
| Nitrokey      | NitroWall                   | Desktop     | [ef701f3991](https://bsd-hardware.info/?probe=ef701f3991) | May 23, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [14583f30e3](https://bsd-hardware.info/?probe=14583f30e3) | May 22, 2023 |
| Unknown       | QD-WHLU01                   | Desktop     | [700bcad7cc](https://bsd-hardware.info/?probe=700bcad7cc) | May 22, 2023 |
| HP            | 158B                        | Desktop     | [1ef3762103](https://bsd-hardware.info/?probe=1ef3762103) | May 20, 2023 |
| HP            | 158B                        | Desktop     | [a9c63041a6](https://bsd-hardware.info/?probe=a9c63041a6) | May 20, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [8156e3fede](https://bsd-hardware.info/?probe=8156e3fede) | May 19, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [612e3a21d4](https://bsd-hardware.info/?probe=612e3a21d4) | May 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8f3c5de741](https://bsd-hardware.info/?probe=8f3c5de741) | May 19, 2023 |
| VIA Techno... | VT82C597                    | Desktop     | [d73db58e48](https://bsd-hardware.info/?probe=d73db58e48) | May 19, 2023 |
| Sophos        | SG                          | Firewall    | [a27da0f165](https://bsd-hardware.info/?probe=a27da0f165) | May 19, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [9350bb37db](https://bsd-hardware.info/?probe=9350bb37db) | May 18, 2023 |
| Medion        | MS-7633                     | Desktop     | [c01f7b9894](https://bsd-hardware.info/?probe=c01f7b9894) | May 18, 2023 |
| Lenovo        | ThinkPad T560 20FJS03Q00    | Notebook    | [a2110471aa](https://bsd-hardware.info/?probe=a2110471aa) | May 18, 2023 |
| Supermicro    | H8DM8-2                     | Desktop     | [68c51b6006](https://bsd-hardware.info/?probe=68c51b6006) | May 18, 2023 |
| CncTion       | N5105-4L-I226 B0            | Desktop     | [75f5674d44](https://bsd-hardware.info/?probe=75f5674d44) | May 18, 2023 |
| HP            | 3397                        | Desktop     | [d405f14bb9](https://bsd-hardware.info/?probe=d405f14bb9) | May 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [fff8127c3f](https://bsd-hardware.info/?probe=fff8127c3f) | May 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [cc27c738be](https://bsd-hardware.info/?probe=cc27c738be) | May 17, 2023 |
| PC Engines    | apu4                        | Desktop     | [7fe2bf9ad6](https://bsd-hardware.info/?probe=7fe2bf9ad6) | May 16, 2023 |
| PC Engines    | apu4                        | Desktop     | [7723fe0a0a](https://bsd-hardware.info/?probe=7723fe0a0a) | May 16, 2023 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [37922a69a6](https://bsd-hardware.info/?probe=37922a69a6) | May 15, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [2b4ece70c9](https://bsd-hardware.info/?probe=2b4ece70c9) | May 15, 2023 |
| ASRock        | AM1B-ITX                    | Desktop     | [8ad16a1805](https://bsd-hardware.info/?probe=8ad16a1805) | May 15, 2023 |
| Supermicro    | X10SDV-6C-TLN4F             | Server      | [acf561c8dd](https://bsd-hardware.info/?probe=acf561c8dd) | May 15, 2023 |
| PC Engines    | APU2                        | Desktop     | [62fef2616b](https://bsd-hardware.info/?probe=62fef2616b) | May 15, 2023 |
| MSI           | B85M-G43                    | Desktop     | [6d2160dcee](https://bsd-hardware.info/?probe=6d2160dcee) | May 14, 2023 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [31beba4f9c](https://bsd-hardware.info/?probe=31beba4f9c) | May 14, 2023 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [41cf5e3d74](https://bsd-hardware.info/?probe=41cf5e3d74) | May 14, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [7332aba586](https://bsd-hardware.info/?probe=7332aba586) | May 14, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [2eb7679f0a](https://bsd-hardware.info/?probe=2eb7679f0a) | May 13, 2023 |
| Supermicro    | X10SDV-6C-TLN4F             | Server      | [bced2662cd](https://bsd-hardware.info/?probe=bced2662cd) | May 13, 2023 |
| Supermicro    | X10SDV-6C-TLN4F             | Server      | [819210fd5f](https://bsd-hardware.info/?probe=819210fd5f) | May 12, 2023 |
| Supermicro    | X11SBA-LN4FA                | Server      | [66569d2c7d](https://bsd-hardware.info/?probe=66569d2c7d) | May 12, 2023 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [4eea72e4a6](https://bsd-hardware.info/?probe=4eea72e4a6) | May 11, 2023 |
| Fujitsu       | D3823-A2 S26361-D3823-Ax... | Desktop     | [2528087de1](https://bsd-hardware.info/?probe=2528087de1) | May 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [eee23dec87](https://bsd-hardware.info/?probe=eee23dec87) | May 11, 2023 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [2543ed83b9](https://bsd-hardware.info/?probe=2543ed83b9) | May 10, 2023 |
| Sophos        | SG                          | Firewall    | [420ac95a25](https://bsd-hardware.info/?probe=420ac95a25) | May 10, 2023 |
| Fujitsu       | D3644-B1 S26361-D3644-B1    | Desktop     | [b2e52b5677](https://bsd-hardware.info/?probe=b2e52b5677) | May 10, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [fbf3fde510](https://bsd-hardware.info/?probe=fbf3fde510) | May 09, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [96abd89bab](https://bsd-hardware.info/?probe=96abd89bab) | May 09, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [37ee98e0b6](https://bsd-hardware.info/?probe=37ee98e0b6) | May 09, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [38243e0313](https://bsd-hardware.info/?probe=38243e0313) | May 09, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [da07885adb](https://bsd-hardware.info/?probe=da07885adb) | May 09, 2023 |
| PC Engines    | APU2                        | Desktop     | [6aff35010a](https://bsd-hardware.info/?probe=6aff35010a) | May 08, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [5b669f261f](https://bsd-hardware.info/?probe=5b669f261f) | May 08, 2023 |
| Unknown       | T100                        | Desktop     | [fb9c6bff7b](https://bsd-hardware.info/?probe=fb9c6bff7b) | May 07, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [45a1c497b6](https://bsd-hardware.info/?probe=45a1c497b6) | May 07, 2023 |
| Supermicro    | X12STN-C-WOHS               | Desktop     | [d8cf344aee](https://bsd-hardware.info/?probe=d8cf344aee) | May 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [349e1709cd](https://bsd-hardware.info/?probe=349e1709cd) | May 06, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [c29d140ee6](https://bsd-hardware.info/?probe=c29d140ee6) | May 06, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [deeed22abd](https://bsd-hardware.info/?probe=deeed22abd) | May 04, 2023 |
| Lanner        | FW-7543 B-GA                | Desktop     | [8346fdf608](https://bsd-hardware.info/?probe=8346fdf608) | May 03, 2023 |
| HP            | 1589                        | Desktop     | [4aee1909c8](https://bsd-hardware.info/?probe=4aee1909c8) | May 03, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [a5a1ca2ee6](https://bsd-hardware.info/?probe=a5a1ca2ee6) | May 02, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [70b09db335](https://bsd-hardware.info/?probe=70b09db335) | May 02, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [eb61af55d5](https://bsd-hardware.info/?probe=eb61af55d5) | May 01, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [8227d6d32c](https://bsd-hardware.info/?probe=8227d6d32c) | Apr 30, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [f86a94eb66](https://bsd-hardware.info/?probe=f86a94eb66) | Apr 30, 2023 |
| Protectli     | VP2420                      | Desktop     | [4ea8453453](https://bsd-hardware.info/?probe=4ea8453453) | Apr 30, 2023 |
| Protectli     | VP2420                      | Desktop     | [46a00b21d9](https://bsd-hardware.info/?probe=46a00b21d9) | Apr 30, 2023 |
| Supermicro    | A1SAi 123456789             | Mini pc     | [38dc0b126e](https://bsd-hardware.info/?probe=38dc0b126e) | Apr 29, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [ec520be044](https://bsd-hardware.info/?probe=ec520be044) | Apr 29, 2023 |
| Supermicro    | A2SDi-H-TF                  | Server      | [cae933d56e](https://bsd-hardware.info/?probe=cae933d56e) | Apr 29, 2023 |
| Protectli     | FW4B                        | Desktop     | [048da71e18](https://bsd-hardware.info/?probe=048da71e18) | Apr 29, 2023 |
| Sophos        | SG                          | Firewall    | [b0c4592563](https://bsd-hardware.info/?probe=b0c4592563) | Apr 29, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [79c36f752c](https://bsd-hardware.info/?probe=79c36f752c) | Apr 28, 2023 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [9dc9ca0768](https://bsd-hardware.info/?probe=9dc9ca0768) | Apr 28, 2023 |
| PC Engines    | apu1                        | Desktop     | [1a37e9d978](https://bsd-hardware.info/?probe=1a37e9d978) | Apr 27, 2023 |
| Supermicro    | X11SCM-LN8F                 | Server      | [32afb6ef58](https://bsd-hardware.info/?probe=32afb6ef58) | Apr 27, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [52174cc0ba](https://bsd-hardware.info/?probe=52174cc0ba) | Apr 27, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [989f3b44bf](https://bsd-hardware.info/?probe=989f3b44bf) | Apr 26, 2023 |
| Supermicro    | X11SDW-8C-TP13F             | Desktop     | [94316d20c8](https://bsd-hardware.info/?probe=94316d20c8) | Apr 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [4c7f33d6a9](https://bsd-hardware.info/?probe=4c7f33d6a9) | Apr 25, 2023 |
| MiTAC         | PH13CMI                     | Desktop     | [5d3e954049](https://bsd-hardware.info/?probe=5d3e954049) | Apr 24, 2023 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [c452485a00](https://bsd-hardware.info/?probe=c452485a00) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [0c8a0100c5](https://bsd-hardware.info/?probe=0c8a0100c5) | Apr 23, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [ad73cda832](https://bsd-hardware.info/?probe=ad73cda832) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [775424cbff](https://bsd-hardware.info/?probe=775424cbff) | Apr 22, 2023 |
| HP            | 8103 A01                    | Mini pc     | [e9c239c897](https://bsd-hardware.info/?probe=e9c239c897) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [c26c1111c6](https://bsd-hardware.info/?probe=c26c1111c6) | Apr 21, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [215364d870](https://bsd-hardware.info/?probe=215364d870) | Apr 21, 2023 |
| Dell          | Latitude 7280               | Notebook    | [254acb5df8](https://bsd-hardware.info/?probe=254acb5df8) | Apr 20, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [fdbbde509c](https://bsd-hardware.info/?probe=fdbbde509c) | Apr 20, 2023 |
| Sophos        | SG                          | Firewall    | [c05ad03e84](https://bsd-hardware.info/?probe=c05ad03e84) | Apr 19, 2023 |
| Lenovo        | ThinkPad X201 3626WNP       | Notebook    | [d642970071](https://bsd-hardware.info/?probe=d642970071) | Apr 19, 2023 |
| PC Engines    | APU2                        | Desktop     | [59b3a3eebf](https://bsd-hardware.info/?probe=59b3a3eebf) | Apr 19, 2023 |
| Sophos        | UTM                         | Firewall    | [d45ac19cd1](https://bsd-hardware.info/?probe=d45ac19cd1) | Apr 19, 2023 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [b341a9c9c9](https://bsd-hardware.info/?probe=b341a9c9c9) | Apr 19, 2023 |
| Dell          | 060J9C A00                  | Mini pc     | [1cec8655b7](https://bsd-hardware.info/?probe=1cec8655b7) | Apr 19, 2023 |
| Dell          | 060J9C A00                  | Mini pc     | [92b99c6f08](https://bsd-hardware.info/?probe=92b99c6f08) | Apr 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [311e89be7a](https://bsd-hardware.info/?probe=311e89be7a) | Apr 18, 2023 |
| CncTion       | J4125-4L-I225               | Desktop     | [b4fd4e35b2](https://bsd-hardware.info/?probe=b4fd4e35b2) | Apr 18, 2023 |
| Supermicro    | X11SDW-8C-TP13F             | Desktop     | [20fac0b7a5](https://bsd-hardware.info/?probe=20fac0b7a5) | Apr 18, 2023 |
| Sophos        | SG                          | Firewall    | [fa6f321ece](https://bsd-hardware.info/?probe=fa6f321ece) | Apr 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [f5153e1b18](https://bsd-hardware.info/?probe=f5153e1b18) | Apr 17, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [6de7890035](https://bsd-hardware.info/?probe=6de7890035) | Apr 17, 2023 |
| Sophos        | SG                          | Firewall    | [4280767cdb](https://bsd-hardware.info/?probe=4280767cdb) | Apr 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [56505e8956](https://bsd-hardware.info/?probe=56505e8956) | Apr 16, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [4fbc5291d9](https://bsd-hardware.info/?probe=4fbc5291d9) | Apr 16, 2023 |
| Lenovo        | Larne CRB 31900002 WIN      | All in one  | [1f18ec4466](https://bsd-hardware.info/?probe=1f18ec4466) | Apr 16, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [a29966f9ee](https://bsd-hardware.info/?probe=a29966f9ee) | Apr 16, 2023 |
| Unknown       | Unknown                     | Notebook    | [c221bccd5d](https://bsd-hardware.info/?probe=c221bccd5d) | Apr 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [94151c41f1](https://bsd-hardware.info/?probe=94151c41f1) | Apr 14, 2023 |
| Unknown       | YL-SKUL6-7 Series           | Desktop     | [627e7a86c6](https://bsd-hardware.info/?probe=627e7a86c6) | Apr 13, 2023 |
| CncTion       | N5105-4L-I226 B0            | Desktop     | [0c7855ee11](https://bsd-hardware.info/?probe=0c7855ee11) | Apr 13, 2023 |
| Intel         | S3420GP E51974-403          | Server      | [e65290edd3](https://bsd-hardware.info/?probe=e65290edd3) | Apr 12, 2023 |
| Intel         | S3420GP E51974-403          | Server      | [00c76c0db0](https://bsd-hardware.info/?probe=00c76c0db0) | Apr 12, 2023 |
| Advantech     | UNO-2271G_V2                | Desktop     | [23e4b8d9b1](https://bsd-hardware.info/?probe=23e4b8d9b1) | Apr 12, 2023 |
| ASUSTek       | P10S-M Series               | Desktop     | [0b060edc48](https://bsd-hardware.info/?probe=0b060edc48) | Apr 12, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [9b1dbe0b9a](https://bsd-hardware.info/?probe=9b1dbe0b9a) | Apr 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [cfa755bf6d](https://bsd-hardware.info/?probe=cfa755bf6d) | Apr 11, 2023 |
| Sophos        | SG                          | Firewall    | [3a2796626e](https://bsd-hardware.info/?probe=3a2796626e) | Apr 11, 2023 |
| CncTion       | N5105-4L-I226 B0            | Desktop     | [65d80d8aeb](https://bsd-hardware.info/?probe=65d80d8aeb) | Apr 09, 2023 |
| Gigabyte      | H610I DDR4                  | Desktop     | [59d65282c3](https://bsd-hardware.info/?probe=59d65282c3) | Apr 08, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [7a0ca560df](https://bsd-hardware.info/?probe=7a0ca560df) | Apr 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 34487... | Notebook    | [cec90ddd1b](https://bsd-hardware.info/?probe=cec90ddd1b) | Apr 08, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [f3ac765863](https://bsd-hardware.info/?probe=f3ac765863) | Apr 08, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [8fb3cbee23](https://bsd-hardware.info/?probe=8fb3cbee23) | Apr 07, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [f1cabdb067](https://bsd-hardware.info/?probe=f1cabdb067) | Apr 06, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [b4dab62ac2](https://bsd-hardware.info/?probe=b4dab62ac2) | Apr 05, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [24d7b97629](https://bsd-hardware.info/?probe=24d7b97629) | Apr 05, 2023 |
| Lanner        | FW-8771 C-GA                | Desktop     | [90d7028263](https://bsd-hardware.info/?probe=90d7028263) | Apr 05, 2023 |
| IGEL Techn... | M340C                       | Notebook    | [6c8b2b7af7](https://bsd-hardware.info/?probe=6c8b2b7af7) | Apr 05, 2023 |
| PC Engines    | apu4                        | Desktop     | [e91a75d782](https://bsd-hardware.info/?probe=e91a75d782) | Apr 05, 2023 |
| Intel         | SKYBAY                      | Desktop     | [81655c4fd5](https://bsd-hardware.info/?probe=81655c4fd5) | Apr 05, 2023 |
| Sophos        | SG                          | Firewall    | [c2a2d9d6c9](https://bsd-hardware.info/?probe=c2a2d9d6c9) | Apr 04, 2023 |
| maiyunda      | www.maiyunda.com            | Desktop     | [7cf52a3977](https://bsd-hardware.info/?probe=7cf52a3977) | Apr 03, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [70a4d74b1a](https://bsd-hardware.info/?probe=70a4d74b1a) | Apr 03, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [828e914b59](https://bsd-hardware.info/?probe=828e914b59) | Apr 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [ca1360b939](https://bsd-hardware.info/?probe=ca1360b939) | Apr 03, 2023 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | Desktop     | [bea5641594](https://bsd-hardware.info/?probe=bea5641594) | Apr 02, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [01bf5e8678](https://bsd-hardware.info/?probe=01bf5e8678) | Apr 02, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [6ef5047d5a](https://bsd-hardware.info/?probe=6ef5047d5a) | Apr 01, 2023 |
| Sophos        | SG                          | Firewall    | [de22e4dd72](https://bsd-hardware.info/?probe=de22e4dd72) | Apr 01, 2023 |
| ZOTAC         | ZBOX-ID91                   | Mini pc     | [d7bb801369](https://bsd-hardware.info/?probe=d7bb801369) | Mar 31, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [60c66c5066](https://bsd-hardware.info/?probe=60c66c5066) | Mar 30, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [bde9fd671b](https://bsd-hardware.info/?probe=bde9fd671b) | Mar 30, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [a160027cc2](https://bsd-hardware.info/?probe=a160027cc2) | Mar 30, 2023 |
| Dell          | 0VG93V A00                  | Desktop     | [1f3e086401](https://bsd-hardware.info/?probe=1f3e086401) | Mar 30, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [3a5111c467](https://bsd-hardware.info/?probe=3a5111c467) | Mar 29, 2023 |
| Intel         | S2600GZ G29051-355          | Server      | [6bc00cde60](https://bsd-hardware.info/?probe=6bc00cde60) | Mar 28, 2023 |
| Intel         | JSL MRD                     | Desktop     | [07adf23a3d](https://bsd-hardware.info/?probe=07adf23a3d) | Mar 28, 2023 |
| Sophos        | SG                          | Firewall    | [b3346fe828](https://bsd-hardware.info/?probe=b3346fe828) | Mar 27, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [b6fd7cd6ae](https://bsd-hardware.info/?probe=b6fd7cd6ae) | Mar 27, 2023 |
| Shuttle       | FS81                        | Desktop     | [b80626e045](https://bsd-hardware.info/?probe=b80626e045) | Mar 26, 2023 |
| Lanner        | FW-7543 B-GA                | Desktop     | [3ed4cfc9c8](https://bsd-hardware.info/?probe=3ed4cfc9c8) | Mar 26, 2023 |
| Sophos        | UTM                         | Firewall    | [99af1f0a15](https://bsd-hardware.info/?probe=99af1f0a15) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [15e452d25d](https://bsd-hardware.info/?probe=15e452d25d) | Mar 26, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [2f16e29f78](https://bsd-hardware.info/?probe=2f16e29f78) | Mar 26, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [fc5ab682fc](https://bsd-hardware.info/?probe=fc5ab682fc) | Mar 26, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [5082d62025](https://bsd-hardware.info/?probe=5082d62025) | Mar 25, 2023 |
| Lenovo        | ThinkPad X220 4291AN9       | Notebook    | [1646bb53ab](https://bsd-hardware.info/?probe=1646bb53ab) | Mar 25, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [41fa3f51d3](https://bsd-hardware.info/?probe=41fa3f51d3) | Mar 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [387c27f1d7](https://bsd-hardware.info/?probe=387c27f1d7) | Mar 25, 2023 |
| PC Engines    | APU2                        | Desktop     | [4e4a81e456](https://bsd-hardware.info/?probe=4e4a81e456) | Mar 24, 2023 |
| Lex           | Pineview-D                  | Desktop     | [ca2fbb614d](https://bsd-hardware.info/?probe=ca2fbb614d) | Mar 24, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [9561c72b9c](https://bsd-hardware.info/?probe=9561c72b9c) | Mar 24, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [083d2e65da](https://bsd-hardware.info/?probe=083d2e65da) | Mar 24, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [18877701a6](https://bsd-hardware.info/?probe=18877701a6) | Mar 24, 2023 |
| HP            | 8103 A01                    | Mini pc     | [23f893285e](https://bsd-hardware.info/?probe=23f893285e) | Mar 24, 2023 |
| Protectli     | VP2420                      | Desktop     | [f07553b02c](https://bsd-hardware.info/?probe=f07553b02c) | Mar 23, 2023 |
| Protectli     | VP2420                      | Desktop     | [dfad78899e](https://bsd-hardware.info/?probe=dfad78899e) | Mar 23, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [720f15a1ce](https://bsd-hardware.info/?probe=720f15a1ce) | Mar 23, 2023 |
| Sony          | VAIO                        | All in one  | [ef7c622d8d](https://bsd-hardware.info/?probe=ef7c622d8d) | Mar 23, 2023 |
| Sony          | VAIO                        | All in one  | [ededfcfd39](https://bsd-hardware.info/?probe=ededfcfd39) | Mar 23, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [491c0ca78a](https://bsd-hardware.info/?probe=491c0ca78a) | Mar 22, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [680002292e](https://bsd-hardware.info/?probe=680002292e) | Mar 22, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [b3f0879ebf](https://bsd-hardware.info/?probe=b3f0879ebf) | Mar 22, 2023 |
| Intel         | SKYBAY                      | Desktop     | [83ea0b27b1](https://bsd-hardware.info/?probe=83ea0b27b1) | Mar 21, 2023 |
| Sophos        | SG                          | Firewall    | [4f818307ff](https://bsd-hardware.info/?probe=4f818307ff) | Mar 21, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [bcada44b09](https://bsd-hardware.info/?probe=bcada44b09) | Mar 21, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [edf47cb2d4](https://bsd-hardware.info/?probe=edf47cb2d4) | Mar 21, 2023 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [7ae004c035](https://bsd-hardware.info/?probe=7ae004c035) | Mar 21, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [5193764df7](https://bsd-hardware.info/?probe=5193764df7) | Mar 20, 2023 |
| Lenovo        | ThinkPad T61 7659CA1        | Notebook    | [bba228ddc9](https://bsd-hardware.info/?probe=bba228ddc9) | Mar 20, 2023 |
| Sophos        | SG                          | Firewall    | [e0ac090471](https://bsd-hardware.info/?probe=e0ac090471) | Mar 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [e4365dfa60](https://bsd-hardware.info/?probe=e4365dfa60) | Mar 20, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [4dc54510d2](https://bsd-hardware.info/?probe=4dc54510d2) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [cab50cddd5](https://bsd-hardware.info/?probe=cab50cddd5) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [ff4dda40eb](https://bsd-hardware.info/?probe=ff4dda40eb) | Mar 19, 2023 |
| ASUSTek       | G750JS                      | Notebook    | [bb6117addd](https://bsd-hardware.info/?probe=bb6117addd) | Mar 19, 2023 |
| Intel         | SKYBAY                      | Desktop     | [7bd7f393b1](https://bsd-hardware.info/?probe=7bd7f393b1) | Mar 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e726d886c8](https://bsd-hardware.info/?probe=e726d886c8) | Mar 18, 2023 |
| Intel         | SKYBAY                      | Desktop     | [a8f1d29e24](https://bsd-hardware.info/?probe=a8f1d29e24) | Mar 18, 2023 |
| MSI           | X299 PRO                    | Desktop     | [a26d096ecb](https://bsd-hardware.info/?probe=a26d096ecb) | Mar 18, 2023 |
| ZOTAC         | ZBOX-ID91                   | Mini pc     | [4bbec4b82a](https://bsd-hardware.info/?probe=4bbec4b82a) | Mar 18, 2023 |
| Fujitsu       | D3313-S3 S26361-D3313-S3    | Desktop     | [1bf34a929a](https://bsd-hardware.info/?probe=1bf34a929a) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2ceda5b586](https://bsd-hardware.info/?probe=2ceda5b586) | Mar 17, 2023 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [17516fffcf](https://bsd-hardware.info/?probe=17516fffcf) | Mar 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [6d9c564a33](https://bsd-hardware.info/?probe=6d9c564a33) | Mar 17, 2023 |
| Lenovo        | ThinkPad X61s 7667WQS       | Notebook    | [f1351003d1](https://bsd-hardware.info/?probe=f1351003d1) | Mar 17, 2023 |
| ASRock        | J5040-ITX                   | Desktop     | [435dc7ee7b](https://bsd-hardware.info/?probe=435dc7ee7b) | Mar 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [68b45d5083](https://bsd-hardware.info/?probe=68b45d5083) | Mar 15, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [1ccc8081fd](https://bsd-hardware.info/?probe=1ccc8081fd) | Mar 15, 2023 |
| Acer          | Aspire V3-112P              | Notebook    | [104c10f9b0](https://bsd-hardware.info/?probe=104c10f9b0) | Mar 14, 2023 |
| Foxconn       | H61M/H61M-S                 | Desktop     | [865fbff42a](https://bsd-hardware.info/?probe=865fbff42a) | Mar 14, 2023 |
| ASRock        | Q1900M                      | Desktop     | [9570525d52](https://bsd-hardware.info/?probe=9570525d52) | Mar 14, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [5211185a2a](https://bsd-hardware.info/?probe=5211185a2a) | Mar 14, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | Notebook    | [d9d7368322](https://bsd-hardware.info/?probe=d9d7368322) | Mar 13, 2023 |
| Sophos        | SG                          | Firewall    | [77db75effb](https://bsd-hardware.info/?probe=77db75effb) | Mar 13, 2023 |
| HP            | 8056                        | Desktop     | [e1d2423153](https://bsd-hardware.info/?probe=e1d2423153) | Mar 13, 2023 |
| HP            | 8056                        | Desktop     | [d89b45ea6d](https://bsd-hardware.info/?probe=d89b45ea6d) | Mar 13, 2023 |
| Dell          | 0W0CHX A00                  | Desktop     | [85a9fddd44](https://bsd-hardware.info/?probe=85a9fddd44) | Mar 12, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [fee0ff7804](https://bsd-hardware.info/?probe=fee0ff7804) | Mar 12, 2023 |
| Lenovo        | ZIUS6                       | Notebook    | [d387825f01](https://bsd-hardware.info/?probe=d387825f01) | Mar 12, 2023 |
| Dell          | Latitude E6330              | Notebook    | [5c60cd3d04](https://bsd-hardware.info/?probe=5c60cd3d04) | Mar 12, 2023 |
| Acer          | Veriton N2620G              | Desktop     | [fa57448331](https://bsd-hardware.info/?probe=fa57448331) | Mar 12, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2BR0... | Notebook    | [56fa0d4656](https://bsd-hardware.info/?probe=56fa0d4656) | Mar 11, 2023 |
| ASUSTek       | P8Z68-V                     | Desktop     | [3d8ef63e18](https://bsd-hardware.info/?probe=3d8ef63e18) | Mar 11, 2023 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [8736b12c9a](https://bsd-hardware.info/?probe=8736b12c9a) | Mar 11, 2023 |
| MSI           | X299 PRO                    | Desktop     | [0cebc094ca](https://bsd-hardware.info/?probe=0cebc094ca) | Mar 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [2a55137e71](https://bsd-hardware.info/?probe=2a55137e71) | Mar 10, 2023 |
| CheckPoint    | PH-30-00                    | Desktop     | [ec7a5f05fd](https://bsd-hardware.info/?probe=ec7a5f05fd) | Mar 09, 2023 |
| CompuLab      | fitlet2                     | Mini pc     | [2e616f1ad4](https://bsd-hardware.info/?probe=2e616f1ad4) | Mar 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [d7b171d0bb](https://bsd-hardware.info/?probe=d7b171d0bb) | Mar 09, 2023 |
| Protectli     | VP2420                      | Desktop     | [21d2214da6](https://bsd-hardware.info/?probe=21d2214da6) | Mar 08, 2023 |
| Fujitsu       | D3544-Sx S26361-D3544-Sx... | Mini pc     | [3ad95b9444](https://bsd-hardware.info/?probe=3ad95b9444) | Mar 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [86c132c242](https://bsd-hardware.info/?probe=86c132c242) | Mar 07, 2023 |
| Fujitsu       | D3049-A1 S26361-D3049-A1... | Server      | [b077e8e71a](https://bsd-hardware.info/?probe=b077e8e71a) | Mar 06, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [1a2543f92f](https://bsd-hardware.info/?probe=1a2543f92f) | Mar 06, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [b91b7cf52d](https://bsd-hardware.info/?probe=b91b7cf52d) | Mar 06, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [789ae683f7](https://bsd-hardware.info/?probe=789ae683f7) | Mar 05, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [2ba0e18863](https://bsd-hardware.info/?probe=2ba0e18863) | Mar 05, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [a3f77b82cc](https://bsd-hardware.info/?probe=a3f77b82cc) | Mar 05, 2023 |
| Dell          | VEP-4600-V910 0PDG1JA02     | Desktop     | [5070c11c54](https://bsd-hardware.info/?probe=5070c11c54) | Mar 05, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [3d912f92aa](https://bsd-hardware.info/?probe=3d912f92aa) | Mar 05, 2023 |
| ASRock        | E350M1                      | Desktop     | [461f8cca23](https://bsd-hardware.info/?probe=461f8cca23) | Mar 04, 2023 |
| HP            | 8158 A01                    | Mini pc     | [021f9a6e74](https://bsd-hardware.info/?probe=021f9a6e74) | Mar 04, 2023 |
| Fujitsu       | D3049-A1 S26361-D3049-A1... | Server      | [5416a8e0b5](https://bsd-hardware.info/?probe=5416a8e0b5) | Mar 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [6067b3f58d](https://bsd-hardware.info/?probe=6067b3f58d) | Mar 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [bbbd05a4c3](https://bsd-hardware.info/?probe=bbbd05a4c3) | Mar 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [9ab07ae7f1](https://bsd-hardware.info/?probe=9ab07ae7f1) | Mar 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [228816d44e](https://bsd-hardware.info/?probe=228816d44e) | Mar 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [81bf3cf726](https://bsd-hardware.info/?probe=81bf3cf726) | Mar 03, 2023 |
| Intel         | DENLOW_WS                   | Desktop     | [2b70fdb96a](https://bsd-hardware.info/?probe=2b70fdb96a) | Mar 02, 2023 |
| Sophos        | SG                          | Firewall    | [19b95b3238](https://bsd-hardware.info/?probe=19b95b3238) | Mar 01, 2023 |
| Sophos        | SG                          | Firewall    | [26cd20e559](https://bsd-hardware.info/?probe=26cd20e559) | Mar 01, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [29290b1b9c](https://bsd-hardware.info/?probe=29290b1b9c) | Mar 01, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [5eb87a21db](https://bsd-hardware.info/?probe=5eb87a21db) | Mar 01, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [39d5f658ce](https://bsd-hardware.info/?probe=39d5f658ce) | Feb 28, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [ca59a5e6f4](https://bsd-hardware.info/?probe=ca59a5e6f4) | Feb 28, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [dcf3f03ddc](https://bsd-hardware.info/?probe=dcf3f03ddc) | Feb 28, 2023 |
| Intel         | NUC7i3BNB J22859-307        | Mini pc     | [aca9e2885d](https://bsd-hardware.info/?probe=aca9e2885d) | Feb 28, 2023 |
| Supermicro    | PDSBM                       | Desktop     | [1dea83dd64](https://bsd-hardware.info/?probe=1dea83dd64) | Feb 26, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [27e756f63d](https://bsd-hardware.info/?probe=27e756f63d) | Feb 26, 2023 |
| Foxconn       | 2A8Ch                       | Desktop     | [96a8673b26](https://bsd-hardware.info/?probe=96a8673b26) | Feb 26, 2023 |
| Sophos        | SG                          | Firewall    | [6f8d299ffb](https://bsd-hardware.info/?probe=6f8d299ffb) | Feb 26, 2023 |
| NF541         | 1.0                         | Desktop     | [863e6235d4](https://bsd-hardware.info/?probe=863e6235d4) | Feb 26, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | Notebook    | [59e609fbb2](https://bsd-hardware.info/?probe=59e609fbb2) | Feb 26, 2023 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [33330ade31](https://bsd-hardware.info/?probe=33330ade31) | Feb 25, 2023 |
| Unknown       | YL-J3160L4                  | Desktop     | [b774e80761](https://bsd-hardware.info/?probe=b774e80761) | Feb 25, 2023 |
| Sophos        | SG                          | Firewall    | [7e05fcaf2b](https://bsd-hardware.info/?probe=7e05fcaf2b) | Feb 25, 2023 |
| AWOW          | PC BOX                      | Mini pc     | [54d8b7446b](https://bsd-hardware.info/?probe=54d8b7446b) | Feb 25, 2023 |
| ASRock        | X470 Gaming K4              | Desktop     | [fbff29a62a](https://bsd-hardware.info/?probe=fbff29a62a) | Feb 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [87ad08a144](https://bsd-hardware.info/?probe=87ad08a144) | Feb 25, 2023 |
| Lenovo        | ThinkCentre M91p 7033A2G    | Desktop     | [25528a00f3](https://bsd-hardware.info/?probe=25528a00f3) | Feb 24, 2023 |
| MSI           | X299 PRO                    | Desktop     | [3ca12f88d9](https://bsd-hardware.info/?probe=3ca12f88d9) | Feb 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [efab6dedba](https://bsd-hardware.info/?probe=efab6dedba) | Feb 24, 2023 |
| Protectli     | VP2420                      | Desktop     | [ac2228fa2b](https://bsd-hardware.info/?probe=ac2228fa2b) | Feb 24, 2023 |
| Supermicro    | X10SBAA                     | Server      | [d22806833a](https://bsd-hardware.info/?probe=d22806833a) | Feb 23, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [5899533edd](https://bsd-hardware.info/?probe=5899533edd) | Feb 23, 2023 |
| Fujitsu       | D3543-A2 S26361-D3543-A2... | Desktop     | [68165a639f](https://bsd-hardware.info/?probe=68165a639f) | Feb 22, 2023 |
| PC Engines    | APU2                        | Desktop     | [05966fb4dc](https://bsd-hardware.info/?probe=05966fb4dc) | Feb 22, 2023 |
| Protectli     | VP2420                      | Desktop     | [541c13b778](https://bsd-hardware.info/?probe=541c13b778) | Feb 22, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [a10df954b7](https://bsd-hardware.info/?probe=a10df954b7) | Feb 22, 2023 |
| Intel         | QHSW02                      | Desktop     | [6bec4024a8](https://bsd-hardware.info/?probe=6bec4024a8) | Feb 22, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [3f78b1a6c7](https://bsd-hardware.info/?probe=3f78b1a6c7) | Feb 20, 2023 |
| Protectli     | VP2420                      | Desktop     | [5d8285d184](https://bsd-hardware.info/?probe=5d8285d184) | Feb 19, 2023 |
| CncTion       | J4125-4L-I225               | Desktop     | [6d2c693305](https://bsd-hardware.info/?probe=6d2c693305) | Feb 19, 2023 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [8d1fa6606b](https://bsd-hardware.info/?probe=8d1fa6606b) | Feb 19, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | Notebook    | [d8ba5b3157](https://bsd-hardware.info/?probe=d8ba5b3157) | Feb 19, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | Notebook    | [820596f359](https://bsd-hardware.info/?probe=820596f359) | Feb 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [63b73012e6](https://bsd-hardware.info/?probe=63b73012e6) | Feb 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [cffec30b6b](https://bsd-hardware.info/?probe=cffec30b6b) | Feb 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [1478bc453d](https://bsd-hardware.info/?probe=1478bc453d) | Feb 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [ac4b0186ff](https://bsd-hardware.info/?probe=ac4b0186ff) | Feb 17, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [0adf0ca671](https://bsd-hardware.info/?probe=0adf0ca671) | Feb 17, 2023 |
| ASUSTek       | N3050M-E                    | Desktop     | [7d6e696fb4](https://bsd-hardware.info/?probe=7d6e696fb4) | Feb 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [71cc084a9c](https://bsd-hardware.info/?probe=71cc084a9c) | Feb 16, 2023 |
| PC Engines    | APU                         | Desktop     | [1162545537](https://bsd-hardware.info/?probe=1162545537) | Feb 15, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [35aa7d7f04](https://bsd-hardware.info/?probe=35aa7d7f04) | Feb 15, 2023 |
| Intel         | S3420GP E51974-403          | Server      | [c7b82f8e59](https://bsd-hardware.info/?probe=c7b82f8e59) | Feb 14, 2023 |
| Intel         | S3420GP E51974-403          | Server      | [9d0765df2e](https://bsd-hardware.info/?probe=9d0765df2e) | Feb 14, 2023 |
| Supermicro    | X7SPA-HF                    | Desktop     | [6a91635684](https://bsd-hardware.info/?probe=6a91635684) | Feb 14, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [a9d6421d3c](https://bsd-hardware.info/?probe=a9d6421d3c) | Feb 14, 2023 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [9c12ee263f](https://bsd-hardware.info/?probe=9c12ee263f) | Feb 14, 2023 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | Desktop     | [d69aba5432](https://bsd-hardware.info/?probe=d69aba5432) | Feb 14, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [c258b4972c](https://bsd-hardware.info/?probe=c258b4972c) | Feb 13, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d7080f05ef](https://bsd-hardware.info/?probe=d7080f05ef) | Feb 13, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | Notebook    | [9137c7933c](https://bsd-hardware.info/?probe=9137c7933c) | Feb 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [98819b1db5](https://bsd-hardware.info/?probe=98819b1db5) | Feb 13, 2023 |
| ZOTAC         | ZBOX-ID88/ID89/ID90         | Mini pc     | [cb4c316a05](https://bsd-hardware.info/?probe=cb4c316a05) | Feb 13, 2023 |
| Shuttle       | DS437T                      | Notebook    | [9a16ad9fec](https://bsd-hardware.info/?probe=9a16ad9fec) | Feb 12, 2023 |
| Alienware     | m15                         | Notebook    | [3ab3e4b671](https://bsd-hardware.info/?probe=3ab3e4b671) | Feb 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [dbe1c51575](https://bsd-hardware.info/?probe=dbe1c51575) | Feb 12, 2023 |
| IBM           | 00AL980                     | Server      | [80fa278909](https://bsd-hardware.info/?probe=80fa278909) | Feb 11, 2023 |
| ASUSTek       | P8Z68-V                     | Desktop     | [74ebc950e2](https://bsd-hardware.info/?probe=74ebc950e2) | Feb 11, 2023 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [516c778d65](https://bsd-hardware.info/?probe=516c778d65) | Feb 11, 2023 |
| Foxconn       | 2A8Ch                       | Desktop     | [2874f7a7fa](https://bsd-hardware.info/?probe=2874f7a7fa) | Feb 11, 2023 |
| Sophos        | UTM                         | Firewall    | [806a078730](https://bsd-hardware.info/?probe=806a078730) | Feb 11, 2023 |
| Gigabyte      | Z490 VISION G               | Desktop     | [6f8ad1a8b9](https://bsd-hardware.info/?probe=6f8ad1a8b9) | Feb 11, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [c4c07aec07](https://bsd-hardware.info/?probe=c4c07aec07) | Feb 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [18362d0f11](https://bsd-hardware.info/?probe=18362d0f11) | Feb 10, 2023 |
| Sophos        | SG                          | Firewall    | [643f5cb10f](https://bsd-hardware.info/?probe=643f5cb10f) | Feb 10, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [12e4e26e40](https://bsd-hardware.info/?probe=12e4e26e40) | Feb 10, 2023 |
| Foxconn       | 2A8Ch                       | Desktop     | [84c0208f8d](https://bsd-hardware.info/?probe=84c0208f8d) | Feb 10, 2023 |
| MSI           | GF76 12UE                   | Notebook    | [371f734e07](https://bsd-hardware.info/?probe=371f734e07) | Feb 10, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [ef0a4a4744](https://bsd-hardware.info/?probe=ef0a4a4744) | Feb 10, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [c1b4617895](https://bsd-hardware.info/?probe=c1b4617895) | Feb 10, 2023 |
| ASUSTek       | P7P55D DELUXE               | Desktop     | [dd9685a909](https://bsd-hardware.info/?probe=dd9685a909) | Feb 09, 2023 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [4347c8c716](https://bsd-hardware.info/?probe=4347c8c716) | Feb 09, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [e5b2e1bb9d](https://bsd-hardware.info/?probe=e5b2e1bb9d) | Feb 09, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [f66883c5c2](https://bsd-hardware.info/?probe=f66883c5c2) | Feb 09, 2023 |
| ASUSTek       | P10S-M Series               | Desktop     | [78975e45b7](https://bsd-hardware.info/?probe=78975e45b7) | Feb 09, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [1a23b05eca](https://bsd-hardware.info/?probe=1a23b05eca) | Feb 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [f4978c3575](https://bsd-hardware.info/?probe=f4978c3575) | Feb 07, 2023 |
| ASUSTek       | P10S-M Series               | Desktop     | [24b74b8ce3](https://bsd-hardware.info/?probe=24b74b8ce3) | Feb 07, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [39fa7db109](https://bsd-hardware.info/?probe=39fa7db109) | Feb 07, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [923b6d85fd](https://bsd-hardware.info/?probe=923b6d85fd) | Feb 06, 2023 |
| PC Engines    | APU2                        | Desktop     | [e4e00e259c](https://bsd-hardware.info/?probe=e4e00e259c) | Feb 06, 2023 |
| ASUSTek       | P8Z77-M                     | Desktop     | [627bdfafb7](https://bsd-hardware.info/?probe=627bdfafb7) | Feb 06, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [ec37957aed](https://bsd-hardware.info/?probe=ec37957aed) | Feb 05, 2023 |
| Sophos        | SG                          | Firewall    | [0b353acc9f](https://bsd-hardware.info/?probe=0b353acc9f) | Feb 05, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [8a2bba8635](https://bsd-hardware.info/?probe=8a2bba8635) | Feb 05, 2023 |
| Intel         | QHSW02                      | Desktop     | [16722b7429](https://bsd-hardware.info/?probe=16722b7429) | Feb 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [8fdace282e](https://bsd-hardware.info/?probe=8fdace282e) | Feb 04, 2023 |
| Lenovo        | ThinkPad P50 20EN0008GE     | Notebook    | [8cb09e34ec](https://bsd-hardware.info/?probe=8cb09e34ec) | Feb 04, 2023 |
| Lenovo        | G70-70 80HW006AGE           | Notebook    | [a52e13cf4e](https://bsd-hardware.info/?probe=a52e13cf4e) | Feb 04, 2023 |
| Supermicro    | X10SDV-2C-TP4F              | Server      | [e766835ab5](https://bsd-hardware.info/?probe=e766835ab5) | Feb 04, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | Notebook    | [c0a6490fc8](https://bsd-hardware.info/?probe=c0a6490fc8) | Feb 03, 2023 |
| ASUSTek       | P10S-M Series               | Desktop     | [c6fc0a639d](https://bsd-hardware.info/?probe=c6fc0a639d) | Feb 03, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [77c7c36f87](https://bsd-hardware.info/?probe=77c7c36f87) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS04200    | Notebook    | [3178015cd3](https://bsd-hardware.info/?probe=3178015cd3) | Feb 02, 2023 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [b2784f4025](https://bsd-hardware.info/?probe=b2784f4025) | Feb 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [433e29e7bd](https://bsd-hardware.info/?probe=433e29e7bd) | Feb 01, 2023 |
| Supermicro    | X7SPA-HF                    | Desktop     | [2d410c6882](https://bsd-hardware.info/?probe=2d410c6882) | Feb 01, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [9fa25e53f1](https://bsd-hardware.info/?probe=9fa25e53f1) | Feb 01, 2023 |
| PC Engines    | apu4                        | Desktop     | [0d1561fea9](https://bsd-hardware.info/?probe=0d1561fea9) | Jan 31, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [418694e14d](https://bsd-hardware.info/?probe=418694e14d) | Jan 31, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [6ed22671aa](https://bsd-hardware.info/?probe=6ed22671aa) | Jan 31, 2023 |
| Lanner        | FW-7543 B-GA                | Desktop     | [149345d14c](https://bsd-hardware.info/?probe=149345d14c) | Jan 30, 2023 |
| HP            | 1825                        | Desktop     | [717279c19f](https://bsd-hardware.info/?probe=717279c19f) | Jan 29, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [eeed92ab62](https://bsd-hardware.info/?probe=eeed92ab62) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [4c25e80924](https://bsd-hardware.info/?probe=4c25e80924) | Jan 29, 2023 |
| Shenzhen M... | F4BHD                       | Desktop     | [b2540f3beb](https://bsd-hardware.info/?probe=b2540f3beb) | Jan 29, 2023 |
| HP            | 21B4 A01                    | Desktop     | [8df824afd4](https://bsd-hardware.info/?probe=8df824afd4) | Jan 28, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [8fd7f80256](https://bsd-hardware.info/?probe=8fd7f80256) | Jan 28, 2023 |
| HP            | ProLiant DL160 Gen9         | Server      | [3797cbf278](https://bsd-hardware.info/?probe=3797cbf278) | Jan 28, 2023 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [1603f38c4c](https://bsd-hardware.info/?probe=1603f38c4c) | Jan 28, 2023 |
| ZOTAC         | ZBOX-CI321NANO              | Mini pc     | [47bbed6ae7](https://bsd-hardware.info/?probe=47bbed6ae7) | Jan 28, 2023 |
| ASUSTek       | M4A89TD PRO USB3            | Desktop     | [1328d01296](https://bsd-hardware.info/?probe=1328d01296) | Jan 28, 2023 |
| Dell          | 03X6X0 A07                  | Server      | [e93b47ed87](https://bsd-hardware.info/?probe=e93b47ed87) | Jan 28, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [937a255571](https://bsd-hardware.info/?probe=937a255571) | Jan 28, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [a7fe868f42](https://bsd-hardware.info/?probe=a7fe868f42) | Jan 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [d3750005c2](https://bsd-hardware.info/?probe=d3750005c2) | Jan 27, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [232a81d2ed](https://bsd-hardware.info/?probe=232a81d2ed) | Jan 27, 2023 |
| ASRock        | H570M-ITX/ac                | Desktop     | [4ebeac2699](https://bsd-hardware.info/?probe=4ebeac2699) | Jan 26, 2023 |
| PC Engines    | APU2                        | Desktop     | [436e596f40](https://bsd-hardware.info/?probe=436e596f40) | Jan 26, 2023 |
| Sophos        | SG                          | Firewall    | [f21b92f971](https://bsd-hardware.info/?probe=f21b92f971) | Jan 25, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [8ba06cd5d3](https://bsd-hardware.info/?probe=8ba06cd5d3) | Jan 24, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [3698389ce4](https://bsd-hardware.info/?probe=3698389ce4) | Jan 24, 2023 |
| Fujitsu       | LIFEBOOK S935               | Notebook    | [5c07c1a47e](https://bsd-hardware.info/?probe=5c07c1a47e) | Jan 24, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [7319560506](https://bsd-hardware.info/?probe=7319560506) | Jan 24, 2023 |
| Medion        | S14409                      | Notebook    | [9a44efb64c](https://bsd-hardware.info/?probe=9a44efb64c) | Jan 23, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [cdad2f0001](https://bsd-hardware.info/?probe=cdad2f0001) | Jan 23, 2023 |
| AWOW          | AK50                        | Desktop     | [8c983f91e4](https://bsd-hardware.info/?probe=8c983f91e4) | Jan 22, 2023 |
| Lenovo        | ThinkPad T440p 20AN007FG... | Notebook    | [0883806434](https://bsd-hardware.info/?probe=0883806434) | Jan 22, 2023 |
| PC Engines    | APU2                        | Desktop     | [658569ae16](https://bsd-hardware.info/?probe=658569ae16) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | Notebook    | [ab38c51298](https://bsd-hardware.info/?probe=ab38c51298) | Jan 22, 2023 |
| HP            | 1825                        | Desktop     | [2705218636](https://bsd-hardware.info/?probe=2705218636) | Jan 21, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [59c83cb9ee](https://bsd-hardware.info/?probe=59c83cb9ee) | Jan 21, 2023 |
| Fujitsu       | D3243-S1 S26361-D3243-S1    | Desktop     | [d69c3cae4c](https://bsd-hardware.info/?probe=d69c3cae4c) | Jan 21, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [e6873fe42f](https://bsd-hardware.info/?probe=e6873fe42f) | Jan 21, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [495563926c](https://bsd-hardware.info/?probe=495563926c) | Jan 21, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [f862df1689](https://bsd-hardware.info/?probe=f862df1689) | Jan 20, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [d4018ae0f3](https://bsd-hardware.info/?probe=d4018ae0f3) | Jan 20, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [4bcc8752f4](https://bsd-hardware.info/?probe=4bcc8752f4) | Jan 20, 2023 |
| Sophos        | SG                          | Firewall    | [324882f1d6](https://bsd-hardware.info/?probe=324882f1d6) | Jan 20, 2023 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [48206a7d4a](https://bsd-hardware.info/?probe=48206a7d4a) | Jan 19, 2023 |
| Sophos        | SG                          | Firewall    | [f10f04a5b1](https://bsd-hardware.info/?probe=f10f04a5b1) | Jan 19, 2023 |
| Sophos        | SG                          | Firewall    | [9275bbae4e](https://bsd-hardware.info/?probe=9275bbae4e) | Jan 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [35e269ef1c](https://bsd-hardware.info/?probe=35e269ef1c) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [b528c0bbe3](https://bsd-hardware.info/?probe=b528c0bbe3) | Jan 18, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [b9de543167](https://bsd-hardware.info/?probe=b9de543167) | Jan 18, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [11948a0ab1](https://bsd-hardware.info/?probe=11948a0ab1) | Jan 18, 2023 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [ed566c9a5c](https://bsd-hardware.info/?probe=ed566c9a5c) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [f7de27b0ca](https://bsd-hardware.info/?probe=f7de27b0ca) | Jan 18, 2023 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [cfb839082b](https://bsd-hardware.info/?probe=cfb839082b) | Jan 18, 2023 |
| Sophos        | UTM                         | Firewall    | [4b0eace553](https://bsd-hardware.info/?probe=4b0eace553) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [9eee9cc526](https://bsd-hardware.info/?probe=9eee9cc526) | Jan 18, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [46178567ff](https://bsd-hardware.info/?probe=46178567ff) | Jan 18, 2023 |
| Wortmann      | terra MiniPC                | Desktop     | [be22193265](https://bsd-hardware.info/?probe=be22193265) | Jan 17, 2023 |
| MSI           | MS-9897                     | Desktop     | [8aa91d17fa](https://bsd-hardware.info/?probe=8aa91d17fa) | Jan 17, 2023 |
| MSI           | MS-9897                     | Desktop     | [0ccc361bd9](https://bsd-hardware.info/?probe=0ccc361bd9) | Jan 17, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [1ef7026e21](https://bsd-hardware.info/?probe=1ef7026e21) | Jan 15, 2023 |
| Supermicro    | X11SCM-LN8F                 | Server      | [9e102da483](https://bsd-hardware.info/?probe=9e102da483) | Jan 15, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [624bfd62b5](https://bsd-hardware.info/?probe=624bfd62b5) | Jan 15, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [8aebf3b22a](https://bsd-hardware.info/?probe=8aebf3b22a) | Jan 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [ced6c29193](https://bsd-hardware.info/?probe=ced6c29193) | Jan 14, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [17d73c4d40](https://bsd-hardware.info/?probe=17d73c4d40) | Jan 14, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [ad7329411a](https://bsd-hardware.info/?probe=ad7329411a) | Jan 14, 2023 |
| HP            | ProLiant DL160 Gen9         | Server      | [f8a84dbf0c](https://bsd-hardware.info/?probe=f8a84dbf0c) | Jan 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [fba3e00878](https://bsd-hardware.info/?probe=fba3e00878) | Jan 13, 2023 |
| HP            | 82A1                        | Desktop     | [567894a0bb](https://bsd-hardware.info/?probe=567894a0bb) | Jan 12, 2023 |
| PC Engines    | APU3                        | Desktop     | [b080710198](https://bsd-hardware.info/?probe=b080710198) | Jan 12, 2023 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [07f15d0014](https://bsd-hardware.info/?probe=07f15d0014) | Jan 11, 2023 |
| CncTion       | J4125-4L-I225               | Desktop     | [56a5c0de6e](https://bsd-hardware.info/?probe=56a5c0de6e) | Jan 11, 2023 |
| PC Engines    | APU2                        | Desktop     | [1e65573dfa](https://bsd-hardware.info/?probe=1e65573dfa) | Jan 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [e870cfc473](https://bsd-hardware.info/?probe=e870cfc473) | Jan 10, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [55bd6297fa](https://bsd-hardware.info/?probe=55bd6297fa) | Jan 10, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [76ce0f8e69](https://bsd-hardware.info/?probe=76ce0f8e69) | Jan 09, 2023 |
| MSI           | X299 PRO                    | Desktop     | [a1f37f69d9](https://bsd-hardware.info/?probe=a1f37f69d9) | Jan 08, 2023 |
| Dell          | 03X6X0 A07                  | Server      | [dea6b95d26](https://bsd-hardware.info/?probe=dea6b95d26) | Jan 08, 2023 |
| Dell          | 0YNVJG A01                  | Desktop     | [8bb9472e6b](https://bsd-hardware.info/?probe=8bb9472e6b) | Jan 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [7b5333020a](https://bsd-hardware.info/?probe=7b5333020a) | Jan 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [1e3ebde983](https://bsd-hardware.info/?probe=1e3ebde983) | Jan 07, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [e25da8b10a](https://bsd-hardware.info/?probe=e25da8b10a) | Jan 06, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [fa12ea67eb](https://bsd-hardware.info/?probe=fa12ea67eb) | Jan 06, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [92c2e73bd4](https://bsd-hardware.info/?probe=92c2e73bd4) | Jan 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [cc8588d977](https://bsd-hardware.info/?probe=cc8588d977) | Jan 05, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [39149acdbd](https://bsd-hardware.info/?probe=39149acdbd) | Jan 04, 2023 |
| Sophos        | SG                          | Firewall    | [4f105d12b8](https://bsd-hardware.info/?probe=4f105d12b8) | Jan 03, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [849af12174](https://bsd-hardware.info/?probe=849af12174) | Jan 02, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [70b1ca485d](https://bsd-hardware.info/?probe=70b1ca485d) | Jan 02, 2023 |
| ASRock        | E350M1                      | Desktop     | [6a7e5c8d0c](https://bsd-hardware.info/?probe=6a7e5c8d0c) | Jan 01, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [b3ac391a7e](https://bsd-hardware.info/?probe=b3ac391a7e) | Jan 01, 2023 |
| Supermicro    | A1SAi 123456789             | Mini pc     | [d179977442](https://bsd-hardware.info/?probe=d179977442) | Jan 01, 2023 |
| HP            | 1825                        | Desktop     | [f7e94decd0](https://bsd-hardware.info/?probe=f7e94decd0) | Dec 31, 2022 |
| HP            | 1825                        | Desktop     | [afc1259508](https://bsd-hardware.info/?probe=afc1259508) | Dec 31, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [16daca3076](https://bsd-hardware.info/?probe=16daca3076) | Dec 31, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [5967766127](https://bsd-hardware.info/?probe=5967766127) | Dec 30, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [cd3e4f7122](https://bsd-hardware.info/?probe=cd3e4f7122) | Dec 30, 2022 |
| Protectli     | FW4B                        | Desktop     | [406fe72c22](https://bsd-hardware.info/?probe=406fe72c22) | Dec 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [126bde2444](https://bsd-hardware.info/?probe=126bde2444) | Dec 30, 2022 |
| PC Engines    | APU2                        | Desktop     | [7aaf2d91ba](https://bsd-hardware.info/?probe=7aaf2d91ba) | Dec 29, 2022 |
| Lanner        | FW-7543 B-GA                | Desktop     | [6c145361a3](https://bsd-hardware.info/?probe=6c145361a3) | Dec 29, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [d3b1e89901](https://bsd-hardware.info/?probe=d3b1e89901) | Dec 29, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [fa3c5f6504](https://bsd-hardware.info/?probe=fa3c5f6504) | Dec 28, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [9954c0abee](https://bsd-hardware.info/?probe=9954c0abee) | Dec 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [5b8ad02694](https://bsd-hardware.info/?probe=5b8ad02694) | Dec 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c3b95220d7](https://bsd-hardware.info/?probe=c3b95220d7) | Dec 28, 2022 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [79d8b1477f](https://bsd-hardware.info/?probe=79d8b1477f) | Dec 28, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [0d398d5c59](https://bsd-hardware.info/?probe=0d398d5c59) | Dec 27, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [b09ff8826c](https://bsd-hardware.info/?probe=b09ff8826c) | Dec 26, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [f2a248dcfe](https://bsd-hardware.info/?probe=f2a248dcfe) | Dec 26, 2022 |
| HP            | 8062                        | Desktop     | [f4d3eb024d](https://bsd-hardware.info/?probe=f4d3eb024d) | Dec 25, 2022 |
| Tactus        | GeoFlex 110                 | Notebook    | [955c355b47](https://bsd-hardware.info/?probe=955c355b47) | Dec 23, 2022 |
| Biostar       | A10N-8800E                  | Desktop     | [d3d1107f77](https://bsd-hardware.info/?probe=d3d1107f77) | Dec 23, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [58b47341c9](https://bsd-hardware.info/?probe=58b47341c9) | Dec 23, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [b38d32b139](https://bsd-hardware.info/?probe=b38d32b139) | Dec 23, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [3a8d5c61b6](https://bsd-hardware.info/?probe=3a8d5c61b6) | Dec 23, 2022 |
| Unknown       | QD-WHLU01                   | Desktop     | [a0fb185069](https://bsd-hardware.info/?probe=a0fb185069) | Dec 23, 2022 |
| Acer          | Aspire ES1-533              | Notebook    | [570b96d0f7](https://bsd-hardware.info/?probe=570b96d0f7) | Dec 23, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [91a89db2ab](https://bsd-hardware.info/?probe=91a89db2ab) | Dec 23, 2022 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [bc2c536004](https://bsd-hardware.info/?probe=bc2c536004) | Dec 23, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [58ca7ca7d4](https://bsd-hardware.info/?probe=58ca7ca7d4) | Dec 23, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [dfd3e7acb1](https://bsd-hardware.info/?probe=dfd3e7acb1) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [daaad6a386](https://bsd-hardware.info/?probe=daaad6a386) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [67bc182d1d](https://bsd-hardware.info/?probe=67bc182d1d) | Dec 23, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [78bcccda01](https://bsd-hardware.info/?probe=78bcccda01) | Dec 22, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [01d8e43ee1](https://bsd-hardware.info/?probe=01d8e43ee1) | Dec 22, 2022 |
| AAEON         | FWS-2251 V1.0               | Desktop     | [a4ff0a7ec5](https://bsd-hardware.info/?probe=a4ff0a7ec5) | Dec 22, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [9e817a9114](https://bsd-hardware.info/?probe=9e817a9114) | Dec 22, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [90dfe8ee6b](https://bsd-hardware.info/?probe=90dfe8ee6b) | Dec 22, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [2ac107df0f](https://bsd-hardware.info/?probe=2ac107df0f) | Dec 22, 2022 |
| AMI           | Cherry Trail CR             | Mini pc     | [cc9eb40ce1](https://bsd-hardware.info/?probe=cc9eb40ce1) | Dec 22, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [0c3fea5eb0](https://bsd-hardware.info/?probe=0c3fea5eb0) | Dec 22, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [16589e2878](https://bsd-hardware.info/?probe=16589e2878) | Dec 21, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [009ef73bd1](https://bsd-hardware.info/?probe=009ef73bd1) | Dec 20, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | Desktop     | [2ea413db31](https://bsd-hardware.info/?probe=2ea413db31) | Dec 20, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [8de4ff8626](https://bsd-hardware.info/?probe=8de4ff8626) | Dec 20, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [af2a9d1a42](https://bsd-hardware.info/?probe=af2a9d1a42) | Dec 20, 2022 |
| Unknown       | Unknown                     | Notebook    | [364b3758b6](https://bsd-hardware.info/?probe=364b3758b6) | Dec 20, 2022 |
| Sophos        | SG                          | Firewall    | [5536740301](https://bsd-hardware.info/?probe=5536740301) | Dec 20, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [3c36f8db41](https://bsd-hardware.info/?probe=3c36f8db41) | Dec 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [5d37a0669c](https://bsd-hardware.info/?probe=5d37a0669c) | Dec 19, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [67baacfc7d](https://bsd-hardware.info/?probe=67baacfc7d) | Dec 19, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [c9de65beeb](https://bsd-hardware.info/?probe=c9de65beeb) | Dec 19, 2022 |
| PC Engines    | APU2                        | Desktop     | [5de84cb508](https://bsd-hardware.info/?probe=5de84cb508) | Dec 19, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [fc7928dfe9](https://bsd-hardware.info/?probe=fc7928dfe9) | Dec 18, 2022 |
| MSI           | X299 PRO                    | Desktop     | [beec8001a1](https://bsd-hardware.info/?probe=beec8001a1) | Dec 17, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [7981529337](https://bsd-hardware.info/?probe=7981529337) | Dec 17, 2022 |
| ASRock        | Q2900M                      | Desktop     | [42a53e5201](https://bsd-hardware.info/?probe=42a53e5201) | Dec 16, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [fa8c102cfd](https://bsd-hardware.info/?probe=fa8c102cfd) | Dec 16, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [3faaaa8209](https://bsd-hardware.info/?probe=3faaaa8209) | Dec 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [01e26ec145](https://bsd-hardware.info/?probe=01e26ec145) | Dec 15, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [40911b66e2](https://bsd-hardware.info/?probe=40911b66e2) | Dec 15, 2022 |
| Supermicro    | X11SBA-LN4F                 | Server      | [649d525fdb](https://bsd-hardware.info/?probe=649d525fdb) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [e3508ce360](https://bsd-hardware.info/?probe=e3508ce360) | Dec 15, 2022 |
| Sophos        | SG                          | Firewall    | [16753b9090](https://bsd-hardware.info/?probe=16753b9090) | Dec 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [35ecaf0406](https://bsd-hardware.info/?probe=35ecaf0406) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [9d71e35375](https://bsd-hardware.info/?probe=9d71e35375) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [98621b669c](https://bsd-hardware.info/?probe=98621b669c) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [b0639c3d01](https://bsd-hardware.info/?probe=b0639c3d01) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [52fbc8ccf7](https://bsd-hardware.info/?probe=52fbc8ccf7) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [210418cc84](https://bsd-hardware.info/?probe=210418cc84) | Dec 15, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [cb16bb9431](https://bsd-hardware.info/?probe=cb16bb9431) | Dec 14, 2022 |
| NF541         | 1.0                         | Desktop     | [b0644bada6](https://bsd-hardware.info/?probe=b0644bada6) | Dec 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [ec6827e543](https://bsd-hardware.info/?probe=ec6827e543) | Dec 13, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [af9df0d2c9](https://bsd-hardware.info/?probe=af9df0d2c9) | Dec 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [9ee8d1082b](https://bsd-hardware.info/?probe=9ee8d1082b) | Dec 12, 2022 |
| Shuttle       | DH370                       | Desktop     | [1b938aa1a4](https://bsd-hardware.info/?probe=1b938aa1a4) | Dec 12, 2022 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [ba191bd994](https://bsd-hardware.info/?probe=ba191bd994) | Dec 12, 2022 |
| Sophos        | XG                          | Firewall    | [e35b3151a3](https://bsd-hardware.info/?probe=e35b3151a3) | Dec 11, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [0be43b76d1](https://bsd-hardware.info/?probe=0be43b76d1) | Dec 11, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [3124aaaf95](https://bsd-hardware.info/?probe=3124aaaf95) | Dec 11, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [b1bd01549a](https://bsd-hardware.info/?probe=b1bd01549a) | Dec 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [def65f518e](https://bsd-hardware.info/?probe=def65f518e) | Dec 10, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [d8d6af9e56](https://bsd-hardware.info/?probe=d8d6af9e56) | Dec 10, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [33395e819a](https://bsd-hardware.info/?probe=33395e819a) | Dec 10, 2022 |
| Hardkernel    | ODROID-H3                   | Desktop     | [cd6aa62212](https://bsd-hardware.info/?probe=cd6aa62212) | Dec 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [493df1f529](https://bsd-hardware.info/?probe=493df1f529) | Dec 09, 2022 |
| PC Engines    | apu4                        | Desktop     | [3e3ab7f196](https://bsd-hardware.info/?probe=3e3ab7f196) | Dec 09, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [84f8198c18](https://bsd-hardware.info/?probe=84f8198c18) | Dec 08, 2022 |
| Dell          | 0G261D A00                  | Desktop     | [24b9490c77](https://bsd-hardware.info/?probe=24b9490c77) | Dec 06, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [eaa3b9783e](https://bsd-hardware.info/?probe=eaa3b9783e) | Dec 05, 2022 |
| PC Engines    | apu4                        | Desktop     | [72061eb254](https://bsd-hardware.info/?probe=72061eb254) | Dec 05, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [aa9482884f](https://bsd-hardware.info/?probe=aa9482884f) | Dec 05, 2022 |
| Shuttle       | FS77U                       | Desktop     | [4172b79cfc](https://bsd-hardware.info/?probe=4172b79cfc) | Dec 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [af4f0984ae](https://bsd-hardware.info/?probe=af4f0984ae) | Dec 04, 2022 |
| ASUSTek       | E35M1-I DELUXE              | Desktop     | [1a183385c7](https://bsd-hardware.info/?probe=1a183385c7) | Dec 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [d9113585f0](https://bsd-hardware.info/?probe=d9113585f0) | Dec 04, 2022 |
| Intel         | D33217CK G76541-300         | Desktop     | [545a39b1e4](https://bsd-hardware.info/?probe=545a39b1e4) | Dec 02, 2022 |
| Thomas-Kre... | P9A-I/2550/4L               | Firewall    | [6bec1ec37d](https://bsd-hardware.info/?probe=6bec1ec37d) | Dec 01, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [a7c2e16f5c](https://bsd-hardware.info/?probe=a7c2e16f5c) | Dec 01, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [ac4f4b181a](https://bsd-hardware.info/?probe=ac4f4b181a) | Nov 30, 2022 |
| Intel         | D33217CK G76541-300         | Desktop     | [bbdd9a1b98](https://bsd-hardware.info/?probe=bbdd9a1b98) | Nov 30, 2022 |
| Sophos        | SG                          | Firewall    | [357c380b7c](https://bsd-hardware.info/?probe=357c380b7c) | Nov 29, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [ae55a799e8](https://bsd-hardware.info/?probe=ae55a799e8) | Nov 28, 2022 |
| PC Engines    | apu6                        | Desktop     | [13dcbe5748](https://bsd-hardware.info/?probe=13dcbe5748) | Nov 27, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [a5514d3f4b](https://bsd-hardware.info/?probe=a5514d3f4b) | Nov 26, 2022 |
| Sophos        | SG                          | Firewall    | [d0fc510660](https://bsd-hardware.info/?probe=d0fc510660) | Nov 26, 2022 |
| Dell          | 0F0XJ6 A13                  | Server      | [1d71d3c9e7](https://bsd-hardware.info/?probe=1d71d3c9e7) | Nov 25, 2022 |
| Dell          | 0F0XJ6 A13                  | Server      | [1fb28aaef2](https://bsd-hardware.info/?probe=1fb28aaef2) | Nov 25, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [7bb8186465](https://bsd-hardware.info/?probe=7bb8186465) | Nov 25, 2022 |
| Dell          | Latitude D610               | Notebook    | [6ef8d8137b](https://bsd-hardware.info/?probe=6ef8d8137b) | Nov 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [d4246caa0f](https://bsd-hardware.info/?probe=d4246caa0f) | Nov 24, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [b6bbaa13e8](https://bsd-hardware.info/?probe=b6bbaa13e8) | Nov 24, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [1860d18e39](https://bsd-hardware.info/?probe=1860d18e39) | Nov 23, 2022 |
| PC Engines    | apu6                        | Desktop     | [bc334caa03](https://bsd-hardware.info/?probe=bc334caa03) | Nov 23, 2022 |
| Sophos        | UTM                         | Firewall    | [1c0805f9ae](https://bsd-hardware.info/?probe=1c0805f9ae) | Nov 23, 2022 |
| HP            | ProLiant DL360 G7           | Server      | [b666129e73](https://bsd-hardware.info/?probe=b666129e73) | Nov 22, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d893e02d90](https://bsd-hardware.info/?probe=d893e02d90) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7518e4f06a](https://bsd-hardware.info/?probe=7518e4f06a) | Nov 21, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [298fde4e33](https://bsd-hardware.info/?probe=298fde4e33) | Nov 21, 2022 |
| HP            | ProLiant DL380 G6           | Server      | [3e3b056cdf](https://bsd-hardware.info/?probe=3e3b056cdf) | Nov 20, 2022 |
| Sophos        | XG                          | Firewall    | [3868856b34](https://bsd-hardware.info/?probe=3868856b34) | Nov 20, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [f6491f1950](https://bsd-hardware.info/?probe=f6491f1950) | Nov 20, 2022 |
| Dell          | 0YNVJG A01                  | Desktop     | [15d32e1e36](https://bsd-hardware.info/?probe=15d32e1e36) | Nov 20, 2022 |
| Dell          | 060J9C A00                  | Mini pc     | [efcae22b58](https://bsd-hardware.info/?probe=efcae22b58) | Nov 19, 2022 |
| PC Engines    | apu6                        | Desktop     | [1e9acc3ae6](https://bsd-hardware.info/?probe=1e9acc3ae6) | Nov 18, 2022 |
| Fujitsu       | D3289-A1 S26361-D3289-A1... | Desktop     | [dae7027898](https://bsd-hardware.info/?probe=dae7027898) | Nov 18, 2022 |
| ASRock        | N3150M                      | Desktop     | [d3b3be7936](https://bsd-hardware.info/?probe=d3b3be7936) | Nov 17, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [f1f56fe86c](https://bsd-hardware.info/?probe=f1f56fe86c) | Nov 17, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [64d8291a91](https://bsd-hardware.info/?probe=64d8291a91) | Nov 17, 2022 |
| PC Engines    | apu4                        | Desktop     | [212f27d85a](https://bsd-hardware.info/?probe=212f27d85a) | Nov 17, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [f362b4c2ea](https://bsd-hardware.info/?probe=f362b4c2ea) | Nov 17, 2022 |
| MSI           | X299 PRO                    | Desktop     | [d615157be7](https://bsd-hardware.info/?probe=d615157be7) | Nov 16, 2022 |
| ASRock        | J5040-ITX                   | Desktop     | [753c68cfb9](https://bsd-hardware.info/?probe=753c68cfb9) | Nov 16, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [15657b37e2](https://bsd-hardware.info/?probe=15657b37e2) | Nov 15, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f4a8c42773](https://bsd-hardware.info/?probe=f4a8c42773) | Nov 15, 2022 |
| PC Engines    | apu4                        | Desktop     | [589dec199e](https://bsd-hardware.info/?probe=589dec199e) | Nov 15, 2022 |
| Shuttle       | FH61V                       | Desktop     | [012a5c0fcc](https://bsd-hardware.info/?probe=012a5c0fcc) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [4c83122cc0](https://bsd-hardware.info/?probe=4c83122cc0) | Nov 14, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [0079838512](https://bsd-hardware.info/?probe=0079838512) | Nov 13, 2022 |
| Sophos        | SG                          | Firewall    | [3d17d672bd](https://bsd-hardware.info/?probe=3d17d672bd) | Nov 13, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [ee16ad1ffb](https://bsd-hardware.info/?probe=ee16ad1ffb) | Nov 12, 2022 |
| PC Engines    | APU2                        | Desktop     | [34960ed27c](https://bsd-hardware.info/?probe=34960ed27c) | Nov 12, 2022 |
| Google        | Akemi                       | Notebook    | [2d8e99f0c2](https://bsd-hardware.info/?probe=2d8e99f0c2) | Nov 12, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [cb88c3311a](https://bsd-hardware.info/?probe=cb88c3311a) | Nov 12, 2022 |
| Unknown       | Unknown                     | Firewall    | [2d2b5ee614](https://bsd-hardware.info/?probe=2d2b5ee614) | Nov 12, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [863c472910](https://bsd-hardware.info/?probe=863c472910) | Nov 12, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e3161d12c5](https://bsd-hardware.info/?probe=e3161d12c5) | Nov 11, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [0fcbc68304](https://bsd-hardware.info/?probe=0fcbc68304) | Nov 11, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [5a5e24fdf7](https://bsd-hardware.info/?probe=5a5e24fdf7) | Nov 11, 2022 |
| HP            | 18E9                        | Desktop     | [b9df70f7eb](https://bsd-hardware.info/?probe=b9df70f7eb) | Nov 11, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [569d5b0cca](https://bsd-hardware.info/?probe=569d5b0cca) | Nov 10, 2022 |
| CheckPoint    | PH-30-00                    | Desktop     | [e42768cd01](https://bsd-hardware.info/?probe=e42768cd01) | Nov 10, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [c741b2fbfa](https://bsd-hardware.info/?probe=c741b2fbfa) | Nov 10, 2022 |
| Deciso        | NetBoard-A20                | Notebook    | [61157ac2b6](https://bsd-hardware.info/?probe=61157ac2b6) | Nov 10, 2022 |
| HP            | 21B4 A01                    | Desktop     | [c064c50fea](https://bsd-hardware.info/?probe=c064c50fea) | Nov 09, 2022 |
| HP            | 21B4 A01                    | Desktop     | [e5c599dfab](https://bsd-hardware.info/?probe=e5c599dfab) | Nov 09, 2022 |
| HP            | 21B4 A01                    | Desktop     | [0a3ba5478b](https://bsd-hardware.info/?probe=0a3ba5478b) | Nov 09, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [c32a7b407d](https://bsd-hardware.info/?probe=c32a7b407d) | Nov 09, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [8addd09aa7](https://bsd-hardware.info/?probe=8addd09aa7) | Nov 09, 2022 |
| Sophos        | SG                          | Firewall    | [04b1bf9b24](https://bsd-hardware.info/?probe=04b1bf9b24) | Nov 09, 2022 |
| HP            | 1632                        | Desktop     | [96d60382b7](https://bsd-hardware.info/?probe=96d60382b7) | Nov 09, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [1fc6403341](https://bsd-hardware.info/?probe=1fc6403341) | Nov 08, 2022 |
| Thomas-Kre... | P9A-I/2550/4L               | Firewall    | [d63fd6f7bd](https://bsd-hardware.info/?probe=d63fd6f7bd) | Nov 08, 2022 |
| Dell          | 0G261D A00                  | Desktop     | [c3eb1a6caf](https://bsd-hardware.info/?probe=c3eb1a6caf) | Nov 08, 2022 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [cb5bb2c3b5](https://bsd-hardware.info/?probe=cb5bb2c3b5) | Nov 07, 2022 |
| ASUSTek       | A88XM-E                     | Desktop     | [fde1fa45b8](https://bsd-hardware.info/?probe=fde1fa45b8) | Nov 07, 2022 |
| Sophos        | SG                          | Firewall    | [4547062398](https://bsd-hardware.info/?probe=4547062398) | Nov 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [659ec0b365](https://bsd-hardware.info/?probe=659ec0b365) | Nov 07, 2022 |
| PC Engines    | APU2                        | Desktop     | [2a913e7a43](https://bsd-hardware.info/?probe=2a913e7a43) | Nov 06, 2022 |
| Protectli     | VP2410                      | Desktop     | [de5de1ca21](https://bsd-hardware.info/?probe=de5de1ca21) | Nov 06, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [95d5580fd7](https://bsd-hardware.info/?probe=95d5580fd7) | Nov 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d27fd3b1a7](https://bsd-hardware.info/?probe=d27fd3b1a7) | Nov 04, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [73230496b2](https://bsd-hardware.info/?probe=73230496b2) | Nov 04, 2022 |
| Fujitsu       | D3049-A1 S26361-D3049-A1... | Server      | [1b27159e27](https://bsd-hardware.info/?probe=1b27159e27) | Nov 04, 2022 |
| Unknown       | 1.0                         | Desktop     | [9fe6ac4e68](https://bsd-hardware.info/?probe=9fe6ac4e68) | Nov 03, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [f0e3f3177a](https://bsd-hardware.info/?probe=f0e3f3177a) | Nov 02, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [09cb46f6bf](https://bsd-hardware.info/?probe=09cb46f6bf) | Oct 31, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [6f21c02bba](https://bsd-hardware.info/?probe=6f21c02bba) | Oct 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [9737a80a1c](https://bsd-hardware.info/?probe=9737a80a1c) | Oct 31, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [a52d7dda08](https://bsd-hardware.info/?probe=a52d7dda08) | Oct 30, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [af6807035f](https://bsd-hardware.info/?probe=af6807035f) | Oct 30, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [4aecc55dcc](https://bsd-hardware.info/?probe=4aecc55dcc) | Oct 30, 2022 |
| Thomas-Kre... | LES network 6L              | Desktop     | [0816f2da97](https://bsd-hardware.info/?probe=0816f2da97) | Oct 30, 2022 |
| Sophos        | SG                          | Firewall    | [03633cdc2e](https://bsd-hardware.info/?probe=03633cdc2e) | Oct 29, 2022 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [85be4177d6](https://bsd-hardware.info/?probe=85be4177d6) | Oct 29, 2022 |
| Acer          | JM11-MS                     | Notebook    | [3ff8b20107](https://bsd-hardware.info/?probe=3ff8b20107) | Oct 29, 2022 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [484e5520b7](https://bsd-hardware.info/?probe=484e5520b7) | Oct 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c483de83a9](https://bsd-hardware.info/?probe=c483de83a9) | Oct 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c03e63a0a8](https://bsd-hardware.info/?probe=c03e63a0a8) | Oct 28, 2022 |
| ASUSTek       | P5BV-M                      | Desktop     | [c5277ae3cd](https://bsd-hardware.info/?probe=c5277ae3cd) | Oct 27, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [d2adcc8230](https://bsd-hardware.info/?probe=d2adcc8230) | Oct 26, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [06e6c07e90](https://bsd-hardware.info/?probe=06e6c07e90) | Oct 25, 2022 |
| PC Engines    | apu1                        | Desktop     | [b8643f364d](https://bsd-hardware.info/?probe=b8643f364d) | Oct 25, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [0e2cd201d0](https://bsd-hardware.info/?probe=0e2cd201d0) | Oct 24, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [51ec4ce710](https://bsd-hardware.info/?probe=51ec4ce710) | Oct 24, 2022 |
| ZOTAC         | ZBOX-MI522NANO/MI542NANO    | Mini pc     | [0d6e868d9c](https://bsd-hardware.info/?probe=0d6e868d9c) | Oct 24, 2022 |
| Sophos        | SG                          | Firewall    | [bb50acf083](https://bsd-hardware.info/?probe=bb50acf083) | Oct 24, 2022 |
| ASUSTek       | P5BV-M                      | Desktop     | [f7bfa3deed](https://bsd-hardware.info/?probe=f7bfa3deed) | Oct 23, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [6f0d5a7497](https://bsd-hardware.info/?probe=6f0d5a7497) | Oct 23, 2022 |
| Dell          | Latitude 5591               | Notebook    | [58b577382a](https://bsd-hardware.info/?probe=58b577382a) | Oct 23, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [d7829c8f35](https://bsd-hardware.info/?probe=d7829c8f35) | Oct 22, 2022 |
| Alienware     | m15                         | Notebook    | [3304a767ba](https://bsd-hardware.info/?probe=3304a767ba) | Oct 22, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [a1b0ef3b39](https://bsd-hardware.info/?probe=a1b0ef3b39) | Oct 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [410283dd4f](https://bsd-hardware.info/?probe=410283dd4f) | Oct 22, 2022 |
| Sophos        | UTM                         | Firewall    | [bae9180e3f](https://bsd-hardware.info/?probe=bae9180e3f) | Oct 22, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [d04ef8c45b](https://bsd-hardware.info/?probe=d04ef8c45b) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [7ecffc1ca3](https://bsd-hardware.info/?probe=7ecffc1ca3) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [eb6eda641d](https://bsd-hardware.info/?probe=eb6eda641d) | Oct 20, 2022 |
| Hardkernel    | ODROID-H3                   | Desktop     | [304db9bbbf](https://bsd-hardware.info/?probe=304db9bbbf) | Oct 20, 2022 |
| Sophos        | SG                          | Firewall    | [a8593e1424](https://bsd-hardware.info/?probe=a8593e1424) | Oct 20, 2022 |
| PC Engines    | APU2                        | Desktop     | [c2e7b76bdf](https://bsd-hardware.info/?probe=c2e7b76bdf) | Oct 20, 2022 |
| PC Engines    | APU2                        | Desktop     | [ade8432e80](https://bsd-hardware.info/?probe=ade8432e80) | Oct 20, 2022 |
| Protectli     | FW6                         | Desktop     | [a7dabc97b0](https://bsd-hardware.info/?probe=a7dabc97b0) | Oct 19, 2022 |
| Protectli     | FW4B                        | Desktop     | [0acd6e1143](https://bsd-hardware.info/?probe=0acd6e1143) | Oct 19, 2022 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [a6c8096599](https://bsd-hardware.info/?probe=a6c8096599) | Oct 19, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [8c6555d6be](https://bsd-hardware.info/?probe=8c6555d6be) | Oct 18, 2022 |
| Lenovo        | 30D0 NOK                    | Desktop     | [d1fab8bd54](https://bsd-hardware.info/?probe=d1fab8bd54) | Oct 18, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [c7971db0b8](https://bsd-hardware.info/?probe=c7971db0b8) | Oct 18, 2022 |
| Dell          | 03X6X0 A00                  | Server      | [7024873a21](https://bsd-hardware.info/?probe=7024873a21) | Oct 17, 2022 |
| NF541         | 1.0                         | Desktop     | [6f4f72398d](https://bsd-hardware.info/?probe=6f4f72398d) | Oct 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [83ceb2fb33](https://bsd-hardware.info/?probe=83ceb2fb33) | Oct 15, 2022 |
| PC Engines    | apu4                        | Desktop     | [cefbafec73](https://bsd-hardware.info/?probe=cefbafec73) | Oct 15, 2022 |
| Sophos        | SG                          | Firewall    | [885bf4ef1e](https://bsd-hardware.info/?probe=885bf4ef1e) | Oct 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [a8bdbe4d1b](https://bsd-hardware.info/?probe=a8bdbe4d1b) | Oct 15, 2022 |
| Sophos        | SG                          | Firewall    | [4fbe0156a8](https://bsd-hardware.info/?probe=4fbe0156a8) | Oct 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5a56504b92](https://bsd-hardware.info/?probe=5a56504b92) | Oct 15, 2022 |
| Sophos        | XG                          | Firewall    | [e80ccac6ff](https://bsd-hardware.info/?probe=e80ccac6ff) | Oct 15, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [27d7eb468e](https://bsd-hardware.info/?probe=27d7eb468e) | Oct 14, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [5acdcd628d](https://bsd-hardware.info/?probe=5acdcd628d) | Oct 14, 2022 |
| PC Engines    | APU2                        | Desktop     | [0e09ac984a](https://bsd-hardware.info/?probe=0e09ac984a) | Oct 14, 2022 |
| PC Engines    | APU2                        | Desktop     | [a06a344954](https://bsd-hardware.info/?probe=a06a344954) | Oct 12, 2022 |
| ASUSTek       | P8Z68-V                     | Desktop     | [6674bbf7f3](https://bsd-hardware.info/?probe=6674bbf7f3) | Oct 11, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [869687f6f0](https://bsd-hardware.info/?probe=869687f6f0) | Oct 11, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [f4b5bf9026](https://bsd-hardware.info/?probe=f4b5bf9026) | Oct 11, 2022 |
| CncTion       | Jasper-4L B0                | Desktop     | [53c643dc95](https://bsd-hardware.info/?probe=53c643dc95) | Oct 10, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [5d929362ca](https://bsd-hardware.info/?probe=5d929362ca) | Oct 09, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [73c9bfe38b](https://bsd-hardware.info/?probe=73c9bfe38b) | Oct 09, 2022 |
| HP            | 84F5                        | Mini pc     | [99c0387102](https://bsd-hardware.info/?probe=99c0387102) | Oct 09, 2022 |
| HP            | 84F5                        | Mini pc     | [ecdab22807](https://bsd-hardware.info/?probe=ecdab22807) | Oct 08, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [17d766d55a](https://bsd-hardware.info/?probe=17d766d55a) | Oct 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [d6396a74dd](https://bsd-hardware.info/?probe=d6396a74dd) | Oct 08, 2022 |
| ZOTAC         | ZBOX-CI527/CI547            | Mini pc     | [231a0f9ce0](https://bsd-hardware.info/?probe=231a0f9ce0) | Oct 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [d25832111e](https://bsd-hardware.info/?probe=d25832111e) | Oct 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [a34c1b8ccd](https://bsd-hardware.info/?probe=a34c1b8ccd) | Oct 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [7658e5e20d](https://bsd-hardware.info/?probe=7658e5e20d) | Oct 06, 2022 |
| PC Engines    | APU2                        | Desktop     | [02416f3157](https://bsd-hardware.info/?probe=02416f3157) | Oct 06, 2022 |
| CncTion       | J4125-4L-I225               | Desktop     | [eb746dc4a1](https://bsd-hardware.info/?probe=eb746dc4a1) | Oct 05, 2022 |
| Sophos        | SG                          | Firewall    | [44ca915943](https://bsd-hardware.info/?probe=44ca915943) | Oct 05, 2022 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [724c70cfa3](https://bsd-hardware.info/?probe=724c70cfa3) | Oct 04, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [459c674b3b](https://bsd-hardware.info/?probe=459c674b3b) | Oct 04, 2022 |
| Neousys Te... | NVS-5000 Rev. A3            | Server      | [49d9f0e06a](https://bsd-hardware.info/?probe=49d9f0e06a) | Oct 04, 2022 |
| Sophos        | XG                          | Firewall    | [4b62b03461](https://bsd-hardware.info/?probe=4b62b03461) | Oct 03, 2022 |
| Protectli     | FW4B                        | Desktop     | [36c62d7ffe](https://bsd-hardware.info/?probe=36c62d7ffe) | Oct 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [dac9b93a46](https://bsd-hardware.info/?probe=dac9b93a46) | Oct 03, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [bb4a59dd43](https://bsd-hardware.info/?probe=bb4a59dd43) | Oct 03, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [f9851a3257](https://bsd-hardware.info/?probe=f9851a3257) | Oct 01, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [23450789e4](https://bsd-hardware.info/?probe=23450789e4) | Oct 01, 2022 |
| AMI           | PICO PC                     | Desktop     | [ab45092607](https://bsd-hardware.info/?probe=ab45092607) | Oct 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [c4e771c07c](https://bsd-hardware.info/?probe=c4e771c07c) | Oct 01, 2022 |
| BESSTAR Te... | IB9                         | Desktop     | [0cb7bacc88](https://bsd-hardware.info/?probe=0cb7bacc88) | Oct 01, 2022 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [6f95477df3](https://bsd-hardware.info/?probe=6f95477df3) | Sep 30, 2022 |
| BESSTAR Te... | IB9                         | Desktop     | [eb0e449150](https://bsd-hardware.info/?probe=eb0e449150) | Sep 29, 2022 |
| Tactus        | GeoFlex 110                 | Notebook    | [0b93b5f915](https://bsd-hardware.info/?probe=0b93b5f915) | Sep 28, 2022 |
| AMI           | MNHO-048                    | Desktop     | [2ec6e55a75](https://bsd-hardware.info/?probe=2ec6e55a75) | Sep 28, 2022 |
| Sophos        | SG                          | Firewall    | [6511e9620b](https://bsd-hardware.info/?probe=6511e9620b) | Sep 28, 2022 |
| ASRock        | Z97 Professional            | Desktop     | [8936497eed](https://bsd-hardware.info/?probe=8936497eed) | Sep 27, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [7e75a1888b](https://bsd-hardware.info/?probe=7e75a1888b) | Sep 27, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [a605b4582c](https://bsd-hardware.info/?probe=a605b4582c) | Sep 27, 2022 |
| Sophos        | SG                          | Firewall    | [fdd950a5e8](https://bsd-hardware.info/?probe=fdd950a5e8) | Sep 26, 2022 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | Notebook    | [b2024820d1](https://bsd-hardware.info/?probe=b2024820d1) | Sep 26, 2022 |
| CncTion       | Jasper-4L B0                | Desktop     | [2998faa879](https://bsd-hardware.info/?probe=2998faa879) | Sep 25, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Germany/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| OPNsense 21.7.7   | 65        | 2.68%   |
| OPNsense 21.1     | 64        | 2.64%   |
| OPNsense 22.7.10  | 59        | 2.44%   |
| OPNsense 21.1.5   | 56        | 2.31%   |
| OPNsense 22.1     | 54        | 2.23%   |
| OPNsense 20.7.8   | 54        | 2.23%   |
| OPNsense 21.7.3   | 52        | 2.15%   |
| OPNsense 21.7.1   | 51        | 2.11%   |
| OPNsense 23.1.11  | 49        | 2.02%   |
| OPNsense 21.1.3   | 45        | 1.86%   |
| OPNsense 21.7.6   | 43        | 1.78%   |
| OPNsense 21.1.2   | 43        | 1.78%   |
| OPNsense 23.1     | 42        | 1.73%   |
| OPNsense 22.7.6   | 42        | 1.73%   |
| OPNsense 22.7.4   | 42        | 1.73%   |
| OPNsense 22.1.8   | 42        | 1.73%   |
| OPNsense 21.1.1   | 42        | 1.73%   |
| OPNsense 23.1.5   | 40        | 1.65%   |
| OPNsense 22.1.6   | 40        | 1.65%   |
| OPNsense 21.1.4   | 39        | 1.61%   |
| OPNsense 22.7.9   | 38        | 1.57%   |
| OPNsense 23.1.1   | 35        | 1.45%   |
| helloSystem 0.4.0 | 34        | 1.4%    |
| OPNsense 23.1.7   | 33        | 1.36%   |
| OPNsense 23.1.9   | 31        | 1.28%   |
| OPNsense 23.7.1   | 30        | 1.24%   |
| helloSystem 0.8.1 | 30        | 1.24%   |
| OPNsense 22.1.10  | 29        | 1.2%    |
| OpenBSD 6.8       | 28        | 1.16%   |
| OPNsense 23.7.3   | 27        | 1.12%   |
| OPNsense 22.7.7   | 26        | 1.07%   |
| OPNsense 22.7.11  | 26        | 1.07%   |
| OPNsense 22.1.9   | 26        | 1.07%   |
| OPNsense 22.1.1   | 26        | 1.07%   |
| OPNsense 21.7.5   | 26        | 1.07%   |
| OPNsense 21.1.7   | 26        | 1.07%   |
| helloSystem 0.7.0 | 25        | 1.03%   |
| OPNsense 22.1.4   | 24        | 0.99%   |
| OPNsense 22.1.2   | 24        | 0.99%   |
| OPNsense 22.7.8   | 23        | 0.95%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 1335      | 71.54%  |
| FreeBSD     | 238       | 12.75%  |
| helloSystem | 141       | 7.56%   |
| OpenBSD     | 70        | 3.75%   |
| GhostBSD    | 36        | 1.93%   |
| NomadBSD    | 21        | 1.13%   |
| NetBSD      | 7         | 0.38%   |
| TrueNAS     | 5         | 0.27%   |
| MyBee       | 3         | 0.16%   |
| pfSense     | 2         | 0.11%   |
| HardenedBSD | 2         | 0.11%   |
| PC-BSD      | 1         | 0.05%   |
| MidnightBSD | 1         | 0.05%   |
| FuryBSD     | 1         | 0.05%   |
| FreeNAS     | 1         | 0.05%   |
| DragonFly   | 1         | 0.05%   |
| ClonOS      | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 1818      | 98.43%  |
| i386    | 12        | 0.65%   |
| arm64   | 9         | 0.49%   |
| arm     | 5         | 0.27%   |
| macppc  | 2         | 0.11%   |
| sparc64 | 1         | 0.05%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 1459      | 77.69%  |
| helloDesktop  | 156       | 8.31%   |
| MATE          | 51        | 2.72%   |
| XFCE          | 39        | 2.08%   |
| fvwm          | 38        | 2.02%   |
| KDE5          | 36        | 1.92%   |
| GNOME         | 23        | 1.22%   |
| TWM           | 19        | 1.01%   |
| Openbox       | 19        | 1.01%   |
| AwesomeWM     | 11        | 0.59%   |
| i3            | 7         | 0.37%   |
| LXQt          | 3         | 0.16%   |
| Enlightenment | 3         | 0.16%   |
| Cinnamon      | 3         | 0.16%   |
| LXDE          | 2         | 0.11%   |
| Fluxbox       | 2         | 0.11%   |
| Picom         | 1         | 0.05%   |
| JWM           | 1         | 0.05%   |
| iwm           | 1         | 0.05%   |
| IceWM         | 1         | 0.05%   |
| GNUstep       | 1         | 0.05%   |
| filer         | 1         | 0.05%   |
| Compton       | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 1475      | 79.56%  |
| X11     | 376       | 20.28%  |
| Wayland | 2         | 0.11%   |
| Tty     | 1         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 1552      | 82.77%  |
| SLiM    | 187       | 9.97%   |
| LightDM | 48        | 2.56%   |
| SDDM    | 39        | 2.08%   |
| XDM     | 25        | 1.33%   |
| GDM     | 19        | 1.01%   |
| Ly      | 5         | 0.27%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 1464      | 77.83%  |
| en_US            | 140       | 7.44%   |
| C                | 131       | 6.96%   |
| de_DE            | 107       | 5.69%   |
| en_GB            | 8         | 0.43%   |
| de               | 8         | 0.43%   |
| fr_FR            | 7         | 0.37%   |
| en               | 4         | 0.21%   |
| de_DE.ISO8859-1  | 3         | 0.16%   |
| ru_RU            | 1         | 0.05%   |
| pl_PL            | 1         | 0.05%   |
| ISO8859-15       | 1         | 0.05%   |
| fr               | 1         | 0.05%   |
| en_IE            | 1         | 0.05%   |
| en_GB.ISO8859-1  | 1         | 0.05%   |
| en_DE            | 1         | 0.05%   |
| en_CA            | 1         | 0.05%   |
| de_DE.ISO8859-15 | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1606      | 86.25%  |
| BIOS | 256       | 13.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 1113      | 58.86%  |
| Zfs     | 660       | 34.9%   |
| Ffs     | 70        | 3.7%    |
| Cd9660  | 47        | 2.49%   |
| Hammer2 | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1715      | 92.25%  |
| MBR     | 119       | 6.4%    |
| Unknown | 24        | 1.29%   |
| BSD     | 1         | 0.05%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 215       | 11.64%  |
| Lenovo              | 139       | 7.53%   |
| PC Engines          | 123       | 6.66%   |
| Supermicro          | 119       | 6.44%   |
| Fujitsu             | 109       | 5.9%    |
| Hewlett-Packard     | 102       | 5.52%   |
| Dell                | 101       | 5.47%   |
| Sophos              | 88        | 4.76%   |
| ASUSTek Computer    | 86        | 4.66%   |
| Intel               | 82        | 4.44%   |
| ASRock              | 68        | 3.68%   |
| Gigabyte Technology | 57        | 3.09%   |
| ZOTAC               | 51        | 2.76%   |
| MSI                 | 44        | 2.38%   |
| AMI                 | 39        | 2.11%   |
| BESSTAR Tech        | 35        | 1.89%   |
| Apple               | 28        | 1.52%   |
| Deciso              | 27        | 1.46%   |
| Protectli           | 26        | 1.41%   |
| Shuttle             | 21        | 1.14%   |
| CncTion             | 20        | 1.08%   |
| Techvision          | 19        | 1.03%   |
| Acer                | 18        | 0.97%   |
| HARDKERNEL          | 13        | 0.7%    |
| AWOW                | 13        | 0.7%    |
| Thomas-Krenn.AG     | 11        | 0.6%    |
| MW                  | 9         | 0.49%   |
| CheckPoint          | 9         | 0.49%   |
| TUXEDO              | 8         | 0.43%   |
| NF541               | 8         | 0.43%   |
| ASRockRack          | 8         | 0.43%   |
| IceWhale Technology | 7         | 0.38%   |
| IBM                 | 7         | 0.38%   |
| Biostar             | 7         | 0.38%   |
| Yanling             | 6         | 0.32%   |
| Medion              | 5         | 0.27%   |
| Lanner              | 5         | 0.27%   |
| Beckhoff Automation | 5         | 0.27%   |
| Sony                | 4         | 0.22%   |
| Notebook            | 4         | 0.22%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                             | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Unknown                                          | 221       | 11.97%  |
| PC Engines APU2                                  | 61        | 3.3%    |
| Sophos SG                                        | 53        | 2.87%   |
| Fujitsu FUTRO S920                               | 45        | 2.44%   |
| Supermicro Super Server                          | 40        | 2.17%   |
| PC Engines apu4                                  | 38        | 2.06%   |
| AMI Aptio CRB                                    | 21        | 1.14%   |
| Techvision TVI7309X                              | 19        | 1.03%   |
| Sophos UTM                                       | 18        | 0.97%   |
| Intel Q3XXG4-P V1.0                              | 18        | 0.97%   |
| Sophos XG                                        | 17        | 0.92%   |
| ZOTAC ZBOX-CI329NANO                             | 12        | 0.65%   |
| HARDKERNEL ODROID-H2                             | 12        | 0.65%   |
| Deciso NetBoard-A10                              | 12        | 0.65%   |
| ZOTAC ZBOX-CI327NANO-GS-01                       | 10        | 0.54%   |
| PC Engines APU                                   | 10        | 0.54%   |
| CncTion N5105-4L                                 | 10        | 0.54%   |
| Supermicro A1SAi                                 | 9         | 0.49%   |
| Protectli FW6                                    | 9         | 0.49%   |
| Protectli FW4B                                   | 9         | 0.49%   |
| PC Engines APU3                                  | 9         | 0.49%   |
| MW GMLK-2_5G4L                                   | 9         | 0.49%   |
| HP ProLiant MicroServer Gen8                     | 9         | 0.49%   |
| Dell PowerEdge R210 II                           | 9         | 0.49%   |
| BESSTAR Tech X35G                                | 9         | 0.49%   |
| BESSTAR Tech GK41                                | 9         | 0.49%   |
| Supermicro 1HE Intel Single-CPU RI1102D-F Server | 7         | 0.38%   |
| NF541 1.0                                        | 7         | 0.38%   |
| Fujitsu FUTRO S930                               | 7         | 0.38%   |
| AWOW PC BOX                                      | 7         | 0.38%   |
| AMI SG                                           | 7         | 0.38%   |
| HP t620 PLUS Quad Core TC                        | 6         | 0.32%   |
| ZOTAC ZBOX-MI640/MI660/MI620NANO                 | 5         | 0.27%   |
| Thomas-Krenn.AG LES network+                     | 5         | 0.27%   |
| IceWhale ZimaBoard 832 ZMB                       | 5         | 0.27%   |
| Deciso Netboard A20                              | 5         | 0.27%   |
| CncTion J4125-4L-I225                            | 5         | 0.27%   |
| ASUS All Series                                  | 5         | 0.27%   |
| ZOTAC ZBOX-CI323NANO                             | 4         | 0.22%   |
| Supermicro X7SPA-HF                              | 4         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 221       | 11.97%  |
| Lenovo ThinkPad            | 90        | 4.87%   |
| PC Engines APU2            | 61        | 3.3%    |
| Fujitsu FUTRO              | 61        | 3.3%    |
| Sophos SG                  | 53        | 2.87%   |
| Supermicro Super           | 40        | 2.17%   |
| PC Engines apu4            | 38        | 2.06%   |
| Dell OptiPlex              | 33        | 1.79%   |
| HP ProLiant                | 30        | 1.62%   |
| Dell PowerEdge             | 28        | 1.52%   |
| Lenovo ThinkCentre         | 21        | 1.14%   |
| Dell Latitude              | 21        | 1.14%   |
| AMI Aptio                  | 21        | 1.14%   |
| Techvision TVI7309X        | 19        | 1.03%   |
| Supermicro 1HE             | 18        | 0.97%   |
| Sophos UTM                 | 18        | 0.97%   |
| Intel Q3XXG4-P             | 18        | 0.97%   |
| Sophos XG                  | 17        | 0.92%   |
| Fujitsu ESPRIMO            | 14        | 0.76%   |
| HP Compaq                  | 13        | 0.7%    |
| ZOTAC ZBOX-CI329NANO       | 12        | 0.65%   |
| HARDKERNEL ODROID-H2       | 12        | 0.65%   |
| Deciso NetBoard-A10        | 12        | 0.65%   |
| HP t620                    | 11        | 0.6%    |
| HP ProDesk                 | 11        | 0.6%    |
| ASUS TUF                   | 11        | 0.6%    |
| ZOTAC ZBOX-CI327NANO-GS-01 | 10        | 0.54%   |
| PC Engines APU             | 10        | 0.54%   |
| Fujitsu PRIMERGY           | 10        | 0.54%   |
| Fujitsu LIFEBOOK           | 10        | 0.54%   |
| Deciso Netboard            | 10        | 0.54%   |
| CncTion N5105-4L           | 10        | 0.54%   |
| ASUS PRIME                 | 10        | 0.54%   |
| Supermicro A1SAi           | 9         | 0.49%   |
| Protectli FW6              | 9         | 0.49%   |
| Protectli FW4B             | 9         | 0.49%   |
| PC Engines APU3            | 9         | 0.49%   |
| MW GMLK-2                  | 9         | 0.49%   |
| BESSTAR Tech X35G          | 9         | 0.49%   |
| BESSTAR Tech GK41          | 9         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 223       | 12.07%  |
| 2020    | 196       | 10.61%  |
| 2021    | 180       | 9.75%   |
| 2016    | 175       | 9.47%   |
| 2019    | 166       | 8.99%   |
| 2014    | 152       | 8.23%   |
| 2022    | 146       | 7.9%    |
| 2017    | 126       | 6.82%   |
| 2013    | 99        | 5.36%   |
| 2012    | 77        | 4.17%   |
| 2011    | 76        | 4.11%   |
| 2015    | 66        | 3.57%   |
| 2010    | 48        | 2.6%    |
| 2009    | 34        | 1.84%   |
| 2023    | 25        | 1.35%   |
| 2008    | 20        | 1.08%   |
| Unknown | 20        | 1.08%   |
| 2007    | 9         | 0.49%   |
| 2006    | 5         | 0.27%   |
| 2003    | 2         | 0.11%   |
| 2005    | 1         | 0.05%   |
| 2002    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 1129      | 61.13%  |
| Notebook       | 285       | 15.43%  |
| Mini pc        | 167       | 9.04%   |
| Server         | 149       | 8.07%   |
| Firewall       | 93        | 5.04%   |
| All in one     | 11        | 0.6%    |
| Convertible    | 7         | 0.38%   |
| System on chip | 6         | 0.32%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1709      | 92.53%  |
| Yes  | 138       | 7.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 693       | 36.84%  |
| 4.01-8.0        | 451       | 23.98%  |
| 16.01-24.0      | 399       | 21.21%  |
| 32.01-64.0      | 153       | 8.13%   |
| 2.01-3.0        | 76        | 4.04%   |
| 64.01-256.0     | 56        | 2.98%   |
| 3.01-4.0        | 14        | 0.74%   |
| 24.01-32.0      | 12        | 0.64%   |
| 0.51-1.0        | 9         | 0.48%   |
| 1.01-2.0        | 7         | 0.37%   |
| 0.01-0.5        | 7         | 0.37%   |
| More than 256.0 | 3         | 0.16%   |
| 0               | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 1050      | 55%     |
| 0.51-1.0    | 574       | 30.07%  |
| 1.01-2.0    | 159       | 8.33%   |
| 2.01-3.0    | 44        | 2.3%    |
| 4.01-8.0    | 22        | 1.15%   |
| 3.01-4.0    | 19        | 1%      |
| 0           | 12        | 0.63%   |
| Unknown     | 9         | 0.47%   |
| 8.01-16.0   | 8         | 0.42%   |
| 16.01-24.0  | 6         | 0.31%   |
| 24.01-32.0  | 3         | 0.16%   |
| 64.01-256.0 | 2         | 0.1%    |
| 32.01-64.0  | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1401      | 73.97%  |
| 2      | 218       | 11.51%  |
| 0      | 151       | 7.97%   |
| 3      | 52        | 2.75%   |
| 4      | 34        | 1.8%    |
| 5      | 13        | 0.69%   |
| 6      | 9         | 0.48%   |
| 8      | 6         | 0.32%   |
| 7      | 5         | 0.26%   |
| 9      | 2         | 0.11%   |
| 14     | 1         | 0.05%   |
| 11     | 1         | 0.05%   |
| 10     | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1583      | 85.2%   |
| Yes       | 275       | 14.8%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1802      | 97.56%  |
| No        | 45        | 2.44%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1281      | 68.76%  |
| Yes       | 582       | 31.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1489      | 80.1%   |
| Yes       | 370       | 19.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Germany | 1847      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 162       | 7.85%   |
| Munich            | 75        | 3.64%   |
| Hamburg           | 73        | 3.54%   |
| Cologne           | 48        | 2.33%   |
| Frankfurt am Main | 46        | 2.23%   |
| Stuttgart         | 35        | 1.7%    |
| Ludwigsburg       | 25        | 1.21%   |
| Karlsruhe         | 25        | 1.21%   |
| Hanover           | 20        | 0.97%   |
| Bonn              | 19        | 0.92%   |
| Dresden           | 18        | 0.87%   |
| Nuremberg         | 17        | 0.82%   |
| Dortmund          | 16        | 0.78%   |
| Bochum            | 15        | 0.73%   |
| Leipzig           | 13        | 0.63%   |
| Falkenstein       | 13        | 0.63%   |
| Bielefeld         | 13        | 0.63%   |
| Mannheim          | 12        | 0.58%   |
| Darmstadt         | 12        | 0.58%   |
| Wiesbaden         | 11        | 0.53%   |
| Wuppertal         | 10        | 0.48%   |
| Mainz             | 10        | 0.48%   |
| Heidelberg        | 10        | 0.48%   |
| Chemnitz          | 10        | 0.48%   |
| Reutlingen        | 9         | 0.44%   |
| Kassel            | 9         | 0.44%   |
| Halle             | 9         | 0.44%   |
| Essen             | 9         | 0.44%   |
| Erlangen          | 9         | 0.44%   |
| Düsseldorf       | 9         | 0.44%   |
| Braunschweig      | 9         | 0.44%   |
| Aachen            | 9         | 0.44%   |
| Ulm               | 8         | 0.39%   |
| Tamm              | 8         | 0.39%   |
| Potsdam           | 8         | 0.39%   |
| Paderborn         | 8         | 0.39%   |
| Magdeburg         | 8         | 0.39%   |
| Lingen            | 8         | 0.39%   |
| Hamm              | 8         | 0.39%   |
| Gifhorn           | 8         | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 354       | 545    | 17.47%  |
| Transcend           | 180       | 244    | 8.88%   |
| WDC                 | 164       | 280    | 8.09%   |
| Kingston            | 143       | 234    | 7.06%   |
| SanDisk             | 117       | 158    | 5.77%   |
| Intel               | 114       | 182    | 5.63%   |
| Crucial             | 111       | 163    | 5.48%   |
| Seagate             | 104       | 176    | 5.13%   |
| Toshiba             | 67        | 123    | 3.31%   |
| China               | 48        | 58     | 2.37%   |
| Intenso             | 44        | 66     | 2.17%   |
| Phison              | 40        | 57     | 1.97%   |
| Hitachi             | 38        | 68     | 1.88%   |
| A-DATA Technology   | 38        | 45     | 1.88%   |
| HGST                | 34        | 67     | 1.68%   |
| Hoodisk             | 33        | 58     | 1.63%   |
| Micron Technology   | 30        | 46     | 1.48%   |
| NVMe                | 24        | 41     | 1.18%   |
| FORESEE             | 24        | 33     | 1.18%   |
| Innodisk            | 23        | 26     | 1.14%   |
| ATP                 | 18        | 21     | 0.89%   |
| OCZ                 | 15        | 23     | 0.74%   |
| Hewlett-Packard     | 15        | 21     | 0.74%   |
| SPCC                | 14        | 20     | 0.69%   |
| Apacer              | 12        | 19     | 0.59%   |
| Corsair             | 11        | 17     | 0.54%   |
| Apple               | 11        | 11     | 0.54%   |
| SK hynix            | 10        | 11     | 0.49%   |
| Patriot             | 10        | 12     | 0.49%   |
| KIOXIA              | 10        | 11     | 0.49%   |
| Dogfish             | 8         | 10     | 0.39%   |
| Verbatim            | 7         | 13     | 0.35%   |
| LITEON              | 7         | 8      | 0.35%   |
| TCSUNBOW            | 6         | 7      | 0.3%    |
| Protectli           | 6         | 8      | 0.3%    |
| Gigabyte Technology | 6         | 7      | 0.3%    |
| Fujitsu             | 6         | 6      | 0.3%    |
| ShiJi               | 5         | 6      | 0.25%   |
| LITEONIT            | 5         | 7      | 0.25%   |
| KIOXIA-EXCERIA      | 5         | 11     | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Phison SATA SSD 16GB             | 31        | 1.46%   |
| Transcend TS128GMSA230S 128GB    | 28        | 1.32%   |
| Samsung SSD 850 EVO 250GB        | 21        | 0.99%   |
| China SATA SSD 16GB              | 21        | 0.99%   |
| Kingston SA400S37120G 120GB      | 19        | 0.9%    |
| Samsung SSD 860 EVO 500GB        | 18        | 0.85%   |
| Crucial CT240BX500SSD1 240GB     | 18        | 0.85%   |
| Transcend TS256GMSA230S 256GB    | 15        | 0.71%   |
| Samsung SSD 840 EVO 250GB        | 15        | 0.71%   |
| Transcend TS64GMSA230S 64GB      | 14        | 0.66%   |
| Crucial CT120BX500SSD1 120GB     | 14        | 0.66%   |
| A-DATA IM2S3134N-064GM 64GB      | 14        | 0.66%   |
| Samsung SSD 870 EVO 250GB        | 13        | 0.61%   |
| Samsung SSD 840 EVO 120GB        | 13        | 0.61%   |
| Kingston SUV500MS120G 120GB      | 13        | 0.61%   |
| FORESEE 128GB SSD                | 13        | 0.61%   |
| Transcend TS64GSSD370 64GB       | 12        | 0.57%   |
| SanDisk SSD PLUS 120GB           | 12        | 0.57%   |
| Innodisk DEMSR- 08GB mSATA 3ME3  | 12        | 0.57%   |
| SanDisk SSD PLUS 240GB           | 11        | 0.52%   |
| Samsung SSD 860 EVO 250GB        | 11        | 0.52%   |
| Kingston SA400S37240G 240GB      | 11        | 0.52%   |
| SanDisk SDSSDA120G 120GB         | 10        | 0.47%   |
| Intenso SSD 120GB                | 10        | 0.47%   |
| Hoodisk SSD 64GB                 | 10        | 0.47%   |
| Hoodisk SSD 128GB                | 10        | 0.47%   |
| Crucial CT500MX500SSD1 500GB     | 10        | 0.47%   |
| Transcend TS32GSSD370S 32GB      | 9         | 0.42%   |
| Transcend TS32GMSA370 32GB       | 9         | 0.42%   |
| Transcend TS128GMSA370 128GB     | 9         | 0.42%   |
| Samsung SSD 850 EVO 500GB        | 9         | 0.42%   |
| Kingston SV300S37A120G 120GB     | 9         | 0.42%   |
| Intel SSDSC2BB120G4 120GB        | 9         | 0.42%   |
| WDC WD40EFRX-68N32N0 4TB         | 8         | 0.38%   |
| Samsung SSD 970 EVO Plus 500GB   | 8         | 0.38%   |
| Samsung SSD 850 PRO 256GB        | 8         | 0.38%   |
| Samsung SSD 850 EVO 120GB        | 8         | 0.38%   |
| Samsung SSD 840 PRO Series 256GB | 8         | 0.38%   |
| Intenso SSD 128GB                | 8         | 0.38%   |
| HP RAID 1(1+0) 1.8TB             | 8         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 119       | 218    | 29.6%   |
| Seagate             | 99        | 166    | 24.63%  |
| Toshiba             | 41        | 72     | 10.2%   |
| Hitachi             | 36        | 63     | 8.96%   |
| HGST                | 34        | 67     | 8.46%   |
| Samsung Electronics | 19        | 24     | 4.73%   |
| NVMe                | 16        | 27     | 3.98%   |
| Hewlett-Packard     | 13        | 18     | 3.23%   |
| Fujitsu             | 6         | 6      | 1.49%   |
| OPENBSD             | 3         | 5      | 0.75%   |
| LSILOGIC            | 2         | 5      | 0.5%    |
| JetFlash            | 2         | 2      | 0.5%    |
| Apple               | 2         | 2      | 0.5%    |
| WD MediaMax         | 1         | 2      | 0.25%   |
| Product:            | 1         | 1      | 0.25%   |
| Maxtor              | 1         | 1      | 0.25%   |
| LSI                 | 1         | 1      | 0.25%   |
| Intenso             | 1         | 1      | 0.25%   |
| IBM/Hitachi         | 1         | 1      | 0.25%   |
| IBM                 | 1         | 1      | 0.25%   |
| Generic             | 1         | 1      | 0.25%   |
| General             | 1         | 1      | 0.25%   |
| ASMT                | 1         | 1      | 0.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 259       | 387    | 18.85%  |
| Transcend           | 162       | 223    | 11.79%  |
| SanDisk             | 116       | 157    | 8.44%   |
| Kingston            | 113       | 185    | 8.22%   |
| Intel               | 103       | 166    | 7.5%    |
| Crucial             | 100       | 146    | 7.28%   |
| China               | 48        | 58     | 3.49%   |
| Intenso             | 43        | 65     | 3.13%   |
| A-DATA Technology   | 37        | 43     | 2.69%   |
| Phison              | 36        | 52     | 2.62%   |
| Hoodisk             | 33        | 58     | 2.4%    |
| WDC                 | 27        | 30     | 1.97%   |
| Innodisk            | 23        | 26     | 1.67%   |
| FORESEE             | 22        | 30     | 1.6%    |
| Micron Technology   | 21        | 34     | 1.53%   |
| Toshiba             | 17        | 25     | 1.24%   |
| ATP                 | 16        | 16     | 1.16%   |
| OCZ                 | 15        | 23     | 1.09%   |
| Apacer              | 12        | 19     | 0.87%   |
| SPCC                | 10        | 15     | 0.73%   |
| NVMe                | 9         | 12     | 0.66%   |
| Apple               | 9         | 9      | 0.66%   |
| Dogfish             | 8         | 10     | 0.58%   |
| Verbatim            | 7         | 13     | 0.51%   |
| Patriot             | 7         | 9      | 0.51%   |
| LITEON              | 7         | 8      | 0.51%   |
| TCSUNBOW            | 6         | 7      | 0.44%   |
| Protectli           | 6         | 8      | 0.44%   |
| Corsair             | 6         | 10     | 0.44%   |
| SK hynix            | 5         | 6      | 0.36%   |
| ShiJi               | 5         | 6      | 0.36%   |
| LITEONIT            | 5         | 7      | 0.36%   |
| Vaseky              | 4         | 4      | 0.29%   |
| Seagate             | 4         | 9      | 0.29%   |
| Leven               | 4         | 6      | 0.29%   |
| Kston               | 4         | 5      | 0.29%   |
| KingSpec            | 4         | 5      | 0.29%   |
| KingDian            | 4         | 10     | 0.29%   |
| BAITITON            | 4         | 5      | 0.29%   |
| VICKTER             | 3         | 3      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1279      | 1977   | 67.92%  |
| HDD  | 342       | 686    | 18.16%  |
| NVMe | 262       | 400    | 13.91%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1509      | 2663   | 85.21%  |
| NVMe | 262       | 400    | 14.79%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 1371      | 2109   | 83.14%  |
| 0.51-1.0        | 146       | 235    | 8.85%   |
| 1.01-2.0        | 71        | 153    | 4.31%   |
| 3.01-4.0        | 28        | 89     | 1.7%    |
| 4.01-10.0       | 15        | 27     | 0.91%   |
| 2.01-3.0        | 14        | 38     | 0.85%   |
| 10.01-20.0      | 3         | 11     | 0.18%   |
| More than 100.0 | 1         | 1      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 815       | 42.85%  |
| 251-500        | 259       | 13.62%  |
| 1-20           | 259       | 13.62%  |
| 51-100         | 224       | 11.78%  |
| 21-50          | 202       | 10.62%  |
| 501-1000       | 91        | 4.78%   |
| 1001-2000      | 19        | 1%      |
| More than 3000 | 16        | 0.84%   |
| Unknown        | 11        | 0.58%   |
| 2001-3000      | 6         | 0.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1733      | 90.88%  |
| 21-50          | 84        | 4.4%    |
| 51-100         | 32        | 1.68%   |
| 101-250        | 24        | 1.26%   |
| Unknown        | 11        | 0.58%   |
| 251-500        | 8         | 0.42%   |
| 1001-2000      | 5         | 0.26%   |
| 501-1000       | 5         | 0.26%   |
| More than 3000 | 3         | 0.16%   |
| 2001-3000      | 2         | 0.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Kingston SV300S37A60G 64GB                   | 4         | 6      | 2.37%   |
| WDC WD2000FYYZ-01UL1B2 2TB                   | 3         | 5      | 1.78%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 3         | 5      | 1.78%   |
| Kingston SMS200S360G 64GB                    | 3         | 3      | 1.78%   |
| WDC WDS240G2G0A-00JH30 240GB                 | 2         | 3      | 1.18%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 2         | 7      | 1.18%   |
| WDC WD2000FYYZ-01UL1B1 2TB                   | 2         | 4      | 1.18%   |
| WDC WD1600AAJS-75M0A0 160GB                  | 2         | 2      | 1.18%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB         | 2         | 7      | 1.18%   |
| Toshiba THNSNK128GCS8 SATA 128GB             | 2         | 2      | 1.18%   |
| Seagate ST9320325AS 320GB                    | 2         | 2      | 1.18%   |
| Seagate ST3160318AS 160GB                    | 2         | 2      | 1.18%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 2         | 2      | 1.18%   |
| Seagate ST1000DX001-1CM162 1TB               | 2         | 2      | 1.18%   |
| SanDisk SSD PLUS 240GB                       | 2         | 2      | 1.18%   |
| Samsung Electronics HD501LJ 500GB            | 2         | 2      | 1.18%   |
| Micron Technology 1100_MTFDDAK512TBN 512GB   | 2         | 4      | 1.18%   |
| Micron Technology 1100 SATA 256GB            | 2         | 2      | 1.18%   |
| Kingston SMS200S3120G 120GB                  | 2         | 3      | 1.18%   |
| Kingston SHFS37A120G 120GB                   | 2         | 3      | 1.18%   |
| Intenso SSD SATAIII 120GB                    | 2         | 2      | 1.18%   |
| Intel SSDSC2CT180A3 180GB                    | 2         | 2      | 1.18%   |
| Intel SSDSC2CT120A3 120GB                    | 2         | 2      | 1.18%   |
| Intel SSDSC2BF180A4L 180GB                   | 2         | 2      | 1.18%   |
| Hitachi HTS545032B9A300 320GB                | 2         | 4      | 1.18%   |
| Hitachi HTS543232L9SA02 320GB                | 2         | 3      | 1.18%   |
| Hitachi HTS543225L9A300 250GB                | 2         | 2      | 1.18%   |
| HGST HTS541010A9E680 1TB                     | 2         | 3      | 1.18%   |
| HGST HTS541010A7E630 1TB                     | 2         | 4      | 1.18%   |
| Crucial CT275MX300SSD1 275GB                 | 2         | 2      | 1.18%   |
| Apacer 8GB SATA Flash Drive                  | 2         | 2      | 1.18%   |
| WDC WD60EFRX-68TGBN1 6TB                     | 1         | 3      | 0.59%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 0.59%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 0.59%   |
| WDC WD3000BLFS-60YBU2 304GB                  | 1         | 2      | 0.59%   |
| WDC WD2503ABYX-01WERA1 256GB                 | 1         | 4      | 0.59%   |
| WDC WD2503ABYX-01WERA0 256GB                 | 1         | 2      | 0.59%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 1         | 2      | 0.59%   |
| WDC WD1600BEVS-07RST0 160GB                  | 1         | 1      | 0.59%   |
| WDC WD1600AAJS-08L7A0 160GB                  | 1         | 1      | 0.59%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 33     | 16.07%  |
| WDC                 | 25        | 44     | 14.88%  |
| Kingston            | 17        | 22     | 10.12%  |
| Samsung Electronics | 15        | 19     | 8.93%   |
| Intel               | 15        | 17     | 8.93%   |
| Hitachi             | 13        | 18     | 7.74%   |
| Crucial             | 9         | 21     | 5.36%   |
| HGST                | 8         | 12     | 4.76%   |
| SanDisk             | 7         | 10     | 4.17%   |
| Toshiba             | 6         | 14     | 3.57%   |
| Micron Technology   | 6         | 8      | 3.57%   |
| Apacer              | 4         | 4      | 2.38%   |
| Intenso             | 3         | 3      | 1.79%   |
| A-DATA Technology   | 3         | 4      | 1.79%   |
| OCZ                 | 2         | 2      | 1.19%   |
| Corsair             | 2         | 4      | 1.19%   |
| SPCC                | 1         | 1      | 0.6%    |
| SMI                 | 1         | 1      | 0.6%    |
| Maxtor              | 1         | 1      | 0.6%    |
| KingSpec            | 1         | 1      | 0.6%    |
| KingDian            | 1         | 3      | 0.6%    |
| Fujitsu             | 1         | 1      | 0.6%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 33     | 33.75%  |
| WDC                 | 23        | 41     | 28.75%  |
| Hitachi             | 13        | 18     | 16.25%  |
| HGST                | 8         | 12     | 10%     |
| Samsung Electronics | 5         | 6      | 6.25%   |
| Toshiba             | 2         | 5      | 2.5%    |
| Maxtor              | 1         | 1      | 1.25%   |
| Fujitsu             | 1         | 1      | 1.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 85        | 123    | 51.2%   |
| HDD  | 78        | 117    | 46.99%  |
| NVMe | 3         | 3      | 1.81%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-16JJ5T0 320GB              | 1         | 1      | 16.67%  |
| Transcend TS32GSSD370S 32GB               | 1         | 2      | 16.67%  |
| Samsung Electronics SSD 980 250GB         | 1         | 2      | 16.67%  |
| Micron Technology 1100_MTFDDAV256TBN 64GB | 1         | 1      | 16.67%  |
| Kingston SV300S37A60G 64GB                | 1         | 1      | 16.67%  |
| Intel SSDSC2BW120H6 120GB                 | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 16.67%  |
| Transcend           | 1         | 2      | 16.67%  |
| Samsung Electronics | 1         | 2      | 16.67%  |
| Micron Technology   | 1         | 1      | 16.67%  |
| Kingston            | 1         | 1      | 16.67%  |
| Intel               | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1561      | 2713   | 87.16%  |
| Malfunc  | 164       | 243    | 9.16%   |
| Detected | 60        | 99     | 3.35%   |
| Failed   | 6         | 8      | 0.34%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1380      | 63.54%  |
| AMD                              | 345       | 15.88%  |
| Samsung Electronics              | 110       | 5.06%   |
| Broadcom / LSI                   | 47        | 2.16%   |
| SanDisk                          | 38        | 1.75%   |
| Kingston Technology Company      | 29        | 1.34%   |
| ASMedia Technology               | 26        | 1.2%    |
| Phison Electronics               | 22        | 1.01%   |
| Transcend                        | 15        | 0.69%   |
| Nvidia                           | 14        | 0.64%   |
| Hewlett-Packard                  | 14        | 0.64%   |
| Silicon Motion                   | 13        | 0.6%    |
| Toshiba                          | 12        | 0.55%   |
| Micron/Crucial Technology        | 12        | 0.55%   |
| Marvell Technology Group         | 12        | 0.55%   |
| MAXIO Technology (Hangzhou)      | 11        | 0.51%   |
| Micron Technology                | 10        | 0.46%   |
| KIOXIA                           | 10        | 0.46%   |
| SK hynix                         | 6         | 0.28%   |
| VIA Technologies                 | 5         | 0.23%   |
| Adaptec                          | 5         | 0.23%   |
| JMicron Technology               | 4         | 0.18%   |
| ATP ELECTRONICS                  | 4         | 0.18%   |
| Silicon Image                    | 3         | 0.14%   |
| Shenzhen Longsys Electronics     | 3         | 0.14%   |
| 3ware                            | 3         | 0.14%   |
| Yangtze Memory Technologies      | 2         | 0.09%   |
| ULi Electronics                  | 2         | 0.09%   |
| Realtek Semiconductor            | 2         | 0.09%   |
| Hosin Global Electronics         | 2         | 0.09%   |
| ADATA Technology                 | 2         | 0.09%   |
| Solid State Storage Technology   | 1         | 0.05%   |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |
| Seagate Technology               | 1         | 0.05%   |
| Lenovo                           | 1         | 0.05%   |
| Integrated Technology Express    | 1         | 0.05%   |
| Enmotus                          | 1         | 0.05%   |
| Chelsio Communications           | 1         | 0.05%   |
| Artop Electronic                 | 1         | 0.05%   |
| Unknown                          | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 235       | 9.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 126       | 5.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 120       | 4.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 115       | 4.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 72        | 2.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 70        | 2.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 64        | 2.62%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 64        | 2.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 57        | 2.34%   |
| AMD FCH SATA Controller [IDE mode]                                               | 54        | 2.21%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 47        | 1.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 46        | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 46        | 1.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 43        | 1.76%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 40        | 1.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 40        | 1.64%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 38        | 1.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 33        | 1.35%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 27        | 1.11%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 27        | 1.11%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 26        | 1.07%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 26        | 1.07%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 26        | 1.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 26        | 1.07%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 25        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 24        | 0.98%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 24        | 0.98%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 22        | 0.9%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 22        | 0.9%    |
| AMD 400 Series Chipset SATA Controller                                           | 22        | 0.9%    |
| Unknown                                                                          | 20        | 0.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 19        | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 19        | 0.78%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 19        | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                            | 18        | 0.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 17        | 0.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 17        | 0.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 17        | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 15        | 0.62%   |
| Intel SATA Controller [RAID mode]                                                | 14        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1554      | 69.94%  |
| NVMe | 301       | 13.55%  |
| IDE  | 236       | 10.62%  |
| RAID | 97        | 4.37%   |
| SAS  | 18        | 0.81%   |
| SCSI | 16        | 0.72%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 1456      | 78.66%  |
| AMD     | 375       | 20.26%  |
| ARM     | 14        | 0.76%   |
| VIA     | 2         | 0.11%   |
| Unknown | 2         | 0.11%   |
| Sun     | 1         | 0.05%   |
| PowerPC | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                          | 109       | 5.85%   |
| Intel Celeron J4125 CPU @ 2.00GHz         | 61        | 3.27%   |
| Intel Celeron N5105 @ 2.00GHz             | 39        | 2.09%   |
| Intel Celeron CPU J1900 @ 1.99GHz         | 37        | 1.98%   |
| Intel Celeron CPU J3160 @ 1.60GHz         | 30        | 1.61%   |
| AMD GX-415GA SOC with Radeon HD Graphics  | 30        | 1.61%   |
| Intel Celeron CPU N3450 @ 1.10GHz         | 27        | 1.45%   |
| AMD GX-222GC SOC with Radeon R5E Graphics | 21        | 1.13%   |
| Intel Core i5-6500 CPU @ 3.20GHz          | 18        | 0.97%   |
| Intel Atom CPU C3558 @ 2.20GHz            | 18        | 0.97%   |
| Intel Xeon CPU D-1518 @ 2.20GHz           | 16        | 0.86%   |
| Intel Core i5-7200U CPU @ 2.50GHz         | 16        | 0.86%   |
| Intel Atom CPU D525 @ 1.80GHz             | 16        | 0.86%   |
| Intel Celeron J4105 CPU @ 1.50GHz         | 15        | 0.8%    |
| Intel Celeron CPU J3455 @ 1.50GHz         | 15        | 0.8%    |
| AMD Ryzen Embedded V1500B                 | 15        | 0.8%    |
| Intel Core i7-8550U CPU @ 1.80GHz         | 14        | 0.75%   |
| Intel Core i7-7500U CPU @ 2.70GHz         | 14        | 0.75%   |
| Intel Celeron N4100 CPU @ 1.10GHz         | 14        | 0.75%   |
| Intel Celeron CPU N3150 @ 1.60GHz         | 14        | 0.75%   |
| Intel Atom CPU C2558 @ 2.40GHz            | 14        | 0.75%   |
| AMD G-T40E Processor                      | 14        | 0.75%   |
| Intel Core i5-8250U CPU @ 1.60GHz         | 11        | 0.59%   |
| Intel Core i5-6300U CPU @ 2.40GHz         | 11        | 0.59%   |
| Intel Core i3-7100U CPU @ 2.40GHz         | 11        | 0.59%   |
| Intel Core i5-6200U CPU @ 2.30GHz         | 10        | 0.54%   |
| Intel Core i5-2520M CPU @ 2.50GHz         | 10        | 0.54%   |
| Intel Celeron CPU N3160 @ 1.60GHz         | 10        | 0.54%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz  | 9         | 0.48%   |
| Intel Core i5-3470 CPU @ 3.20GHz          | 9         | 0.48%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz        | 9         | 0.48%   |
| Intel Celeron                             | 9         | 0.48%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz   | 9         | 0.48%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz       | 8         | 0.43%   |
| Intel Core i5-8365U CPU @ 1.60GHz         | 8         | 0.43%   |
| Intel Core i5-5300U CPU @ 2.30GHz         | 8         | 0.43%   |
| Intel Celeron J4115 CPU @ 1.80GHz         | 8         | 0.43%   |
| Intel Atom CPU N450 @ 1.66GHz             | 8         | 0.43%   |
| Intel Atom CPU E3827 @ 1.74GHz            | 8         | 0.43%   |
| AMD GX-424CC SOC with Radeon R5E Graphics | 8         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 374       | 20.12%  |
| Intel Core i5           | 296       | 15.92%  |
| AMD GX                  | 185       | 9.95%   |
| Intel Xeon              | 175       | 9.41%   |
| Intel Core i3           | 138       | 7.42%   |
| Intel Core i7           | 137       | 7.37%   |
| Intel Atom              | 135       | 7.26%   |
| Other                   | 69        | 3.71%   |
| Intel Pentium           | 44        | 2.37%   |
| AMD Ryzen 7             | 34        | 1.83%   |
| Intel Core 2 Duo        | 30        | 1.61%   |
| AMD Ryzen 5             | 28        | 1.51%   |
| Intel Pentium Silver    | 24        | 1.29%   |
| AMD G                   | 20        | 1.08%   |
| AMD Ryzen Embedded      | 18        | 0.97%   |
| AMD FX                  | 15        | 0.81%   |
| AMD EPYC                | 12        | 0.65%   |
| Intel Pentium Dual-Core | 11        | 0.59%   |
| Intel Core 2 Quad       | 10        | 0.54%   |
| ARM Cortex              | 10        | 0.54%   |
| Intel Pentium Gold      | 8         | 0.43%   |
| AMD Ryzen 3             | 7         | 0.38%   |
| AMD Ryzen 5 PRO         | 6         | 0.32%   |
| AMD Ryzen 9             | 5         | 0.27%   |
| Intel Xeon Silver       | 4         | 0.22%   |
| AMD Ryzen 7 PRO         | 4         | 0.22%   |
| AMD E                   | 4         | 0.22%   |
| Intel Xeon Gold         | 3         | 0.16%   |
| Intel Pentium M         | 3         | 0.16%   |
| Intel Pentium Dual      | 3         | 0.16%   |
| Intel Genuine           | 3         | 0.16%   |
| Intel Core i9           | 3         | 0.16%   |
| Intel Core 2            | 3         | 0.16%   |
| AMD Turion II Neo       | 3         | 0.16%   |
| AMD Athlon 64 X2        | 3         | 0.16%   |
| AMD Athlon              | 3         | 0.16%   |
| AMD A4                  | 3         | 0.16%   |
| AMD A10                 | 3         | 0.16%   |
| Intel Pentium 4         | 2         | 0.11%   |
| AMD Ryzen Threadripper  | 2         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 984       | 52.9%   |
| 2       | 537       | 28.87%  |
| 8       | 92        | 4.95%   |
| Unknown | 64        | 3.44%   |
| 6       | 62        | 3.33%   |
| 16      | 45        | 2.42%   |
| 12      | 38        | 2.04%   |
| 1       | 26        | 1.4%    |
| 32      | 5         | 0.27%   |
| 10      | 3         | 0.16%   |
| 128     | 1         | 0.05%   |
| 36      | 1         | 0.05%   |
| 24      | 1         | 0.05%   |
| 20      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1772      | 95.73%  |
| 2       | 52        | 2.81%   |
| Unknown | 27        | 1.46%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1131      | 61.04%  |
| 2       | 649       | 35.02%  |
| Unknown | 73        | 3.94%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 233       | 12.55%  |
| Silvermont    | 168       | 9.05%   |
| Haswell       | 163       | 8.78%   |
| Puma          | 146       | 7.87%   |
| Unknown       | 124       | 6.68%   |
| Goldmont plus | 121       | 6.52%   |
| Skylake       | 111       | 5.98%   |
| IvyBridge     | 100       | 5.39%   |
| Goldmont      | 93        | 5.01%   |
| SandyBridge   | 73        | 3.93%   |
| Penryn        | 59        | 3.18%   |
| Broadwell     | 55        | 2.96%   |
| Bonnell       | 46        | 2.48%   |
| Jaguar        | 45        | 2.42%   |
| Zen           | 44        | 2.37%   |
| Westmere      | 33        | 1.78%   |
| Core          | 29        | 1.56%   |
| Zen 2         | 28        | 1.51%   |
| Zen+          | 26        | 1.4%    |
| Bobcat        | 25        | 1.35%   |
| TigerLake     | 21        | 1.13%   |
| CometLake     | 20        | 1.08%   |
| Nehalem       | 18        | 0.97%   |
| Piledriver    | 16        | 0.86%   |
| Zen 3         | 14        | 0.75%   |
| IceLake       | 10        | 0.54%   |
| K8 Hammer     | 7         | 0.38%   |
| Steamroller   | 5         | 0.27%   |
| K10           | 5         | 0.27%   |
| P6            | 4         | 0.22%   |
| NetBurst      | 4         | 0.22%   |
| Bulldozer     | 4         | 0.22%   |
| Excavator     | 3         | 0.16%   |
| Geode         | 2         | 0.11%   |
| K10 Llano     | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1131      | 65.87%  |
| AMD                                          | 214       | 12.46%  |
| ASPEED Technology                            | 146       | 8.5%    |
| Nvidia                                       | 138       | 8.04%   |
| Matrox Electronics Systems                   | 83        | 4.83%   |
| VIA Technologies                             | 2         | 0.12%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.06%   |
| Trident Microsystems                         | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 146       | 8.38%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 105       | 6.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 72        | 4.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 68        | 3.9%    |
| Intel HD Graphics 500                                                                    | 63        | 3.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 59        | 3.39%   |
| Intel JasperLake [UHD Graphics]                                                          | 57        | 3.27%   |
| Intel HD Graphics 620                                                                    | 46        | 2.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 44        | 2.53%   |
| Intel HD Graphics 530                                                                    | 40        | 2.3%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 39        | 2.24%   |
| Intel UHD Graphics 620                                                                   | 34        | 1.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 33        | 1.89%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 33        | 1.89%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 31        | 1.78%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 30        | 1.72%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 30        | 1.72%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 29        | 1.66%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 27        | 1.55%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 27        | 1.55%   |
| Intel HD Graphics 5500                                                                   | 22        | 1.26%   |
| Matrox Electronics Systems MGA G200EH                                                    | 21        | 1.21%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 20        | 1.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 20        | 1.15%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 18        | 1.03%   |
| Intel Core Processor Integrated Graphics Controller                                      | 17        | 0.98%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 16        | 0.92%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 16        | 0.92%   |
| Intel HD Graphics 630                                                                    | 15        | 0.86%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 15        | 0.86%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 14        | 0.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 0.8%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 13        | 0.75%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 13        | 0.75%   |
| Intel HD Graphics 510                                                                    | 12        | 0.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 0.63%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 0.63%   |
| AMD Renoir                                                                               | 11        | 0.63%   |
| AMD ES1000                                                                               | 11        | 0.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1005      | 54.21%  |
| 1 x AMD                  | 203       | 10.95%  |
| Other                    | 198       | 10.68%  |
| 1 x ASPEED               | 134       | 7.23%   |
| 1 x Nvidia               | 97        | 5.23%   |
| 1 x Matrox               | 81        | 4.37%   |
| 2 x Intel                | 68        | 3.67%   |
| Intel + Nvidia           | 38        | 2.05%   |
| Intel + ASPEED           | 11        | 0.59%   |
| Intel + AMD              | 7         | 0.38%   |
| AMD + Nvidia             | 3         | 0.16%   |
| 1 x VIA                  | 2         | 0.11%   |
| Intel + Matrox           | 2         | 0.11%   |
| 2 x AMD                  | 1         | 0.05%   |
| 1 x XGI                  | 1         | 0.05%   |
| 1 x Trident Microsystems | 1         | 0.05%   |
| 1 x SiS                  | 1         | 0.05%   |
| Nvidia + ASPEED          | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1562      | 84.2%   |
| Unknown     | 219       | 11.81%  |
| Proprietary | 74        | 3.99%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1749      | 93.88%  |
| 1.01-2.0   | 34        | 1.83%   |
| 0.01-0.5   | 28        | 1.5%    |
| 3.01-4.0   | 17        | 0.91%   |
| 7.01-8.0   | 12        | 0.64%   |
| 0.51-1.0   | 10        | 0.54%   |
| 5.01-6.0   | 9         | 0.48%   |
| 2.01-3.0   | 4         | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 36        | 10.98%  |
| LG Display              | 35        | 10.67%  |
| Samsung Electronics     | 34        | 10.37%  |
| Dell                    | 22        | 6.71%   |
| Apple                   | 19        | 5.79%   |
| Goldstar                | 18        | 5.49%   |
| Chimei Innolux          | 18        | 5.49%   |
| BenQ                    | 16        | 4.88%   |
| Lenovo                  | 15        | 4.57%   |
| BOE                     | 14        | 4.27%   |
| Ancor Communications    | 10        | 3.05%   |
| Acer                    | 10        | 3.05%   |
| Iiyama                  | 8         | 2.44%   |
| Hewlett-Packard         | 8         | 2.44%   |
| Eizo                    | 8         | 2.44%   |
| Sharp                   | 6         | 1.83%   |
| LG Electronics          | 6         | 1.83%   |
| NEC Computers           | 5         | 1.52%   |
| AOC                     | 5         | 1.52%   |
| InfoVision              | 4         | 1.22%   |
| Philips                 | 3         | 0.91%   |
| PANDA                   | 3         | 0.91%   |
| Idek Iiyama             | 3         | 0.91%   |
| HannStar                | 2         | 0.61%   |
| Fujitsu Siemens         | 2         | 0.61%   |
| Belinea                 | 2         | 0.61%   |
| ASUSTek Computer        | 2         | 0.61%   |
| Unknown                 | 2         | 0.61%   |
| WYT                     | 1         | 0.3%    |
| TRU                     | 1         | 0.3%    |
| Toshiba                 | 1         | 0.3%    |
| Panasonic               | 1         | 0.3%    |
| Mi                      | 1         | 0.3%    |
| Medion                  | 1         | 0.3%    |
| LTM                     | 1         | 0.3%    |
| LG Philips              | 1         | 0.3%    |
| JDI                     | 1         | 0.3%    |
| CSO                     | 1         | 0.3%    |
| Chi Mei Optoelectronics | 1         | 0.3%    |
| CHD                     | 1         | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 5         | 1.46%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 4         | 1.17%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 3         | 0.88%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 3         | 0.88%   |
| BOE LCD Monitor BOE05E0 1366x768 280x160mm 12.7-inch                 | 3         | 0.88%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch       | 3         | 0.88%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch        | 3         | 0.88%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 3         | 0.88%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch              | 2         | 0.58%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch    | 2         | 0.58%   |
| Samsung Electronics C32JG5x SAM0FDE 2560x1440 700x390mm 31.5-inch    | 2         | 0.58%   |
| PANDA LCD Monitor NCP002D 1920x1080 340x190mm 15.3-inch              | 2         | 0.58%   |
| LG Display LCD Monitor LGD057E 1920x1080 340x190mm 15.3-inch         | 2         | 0.58%   |
| LG Display LCD Monitor LGD04A3 1366x768 280x160mm 12.7-inch          | 2         | 0.58%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch          | 2         | 0.58%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 2         | 0.58%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 2         | 0.58%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch          | 2         | 0.58%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 2         | 0.58%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch             | 2         | 0.58%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch              | 2         | 0.58%   |
| Hewlett-Packard LP2475w HWP26F9 1920x1200 540x350mm 25.3-inch        | 2         | 0.58%   |
| Hewlett-Packard LP2475w HWP26F8 1920x1200 540x350mm 25.3-inch        | 2         | 0.58%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 520x320mm 24.0-inch         | 2         | 0.58%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                 | 2         | 0.58%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 2         | 0.58%   |
| Goldstar E2441 GSM581F 1920x1080 530x300mm 24.0-inch                 | 2         | 0.58%   |
| Eizo EV2450 ENC2530 1920x1080 530x300mm 24.0-inch                    | 2         | 0.58%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                    | 2         | 0.58%   |
| Dell LCD Monitor U2412M 3840x1200                                    | 2         | 0.58%   |
| Dell LCD Monitor U2412M                                              | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 2         | 0.58%   |
| BenQ GW2765 BNQ78D6 2560x1440 600x340mm 27.2-inch                    | 2         | 0.58%   |
| BenQ GW2260 BNQ78C4 1920x1080 480x270mm 21.7-inch                    | 2         | 0.58%   |
| BenQ GL2760 BNQ78D5 1920x1080 600x340mm 27.2-inch                    | 2         | 0.58%   |
| BenQ GL2450H BNQ78A6 1920x1080 530x300mm 24.0-inch                   | 2         | 0.58%   |
| BenQ BL2405 BNQ8016 1920x1080 530x300mm 24.0-inch                    | 2         | 0.58%   |
| Belinea LCD Monitor MAX0776 1280x1024 380x300mm 19.1-inch            | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO8074 1280x800 330x210mm 15.4-inch        | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 2         | 0.58%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 119       | 36.39%  |
| 1366x768 (WXGA)    | 54        | 16.51%  |
| 2560x1440 (QHD)    | 30        | 9.17%   |
| 3840x2160 (4K)     | 25        | 7.65%   |
| 1920x1200 (WUXGA)  | 21        | 6.42%   |
| 1680x1050 (WSXGA+) | 11        | 3.36%   |
| 1280x800 (WXGA)    | 11        | 3.36%   |
| 1280x1024 (SXGA)   | 11        | 3.36%   |
| 1600x900 (HD+)     | 10        | 3.06%   |
| 1440x900 (WXGA+)   | 7         | 2.14%   |
| 3440x1440          | 4         | 1.22%   |
| 2560x1600          | 3         | 0.92%   |
| 2560x1080          | 3         | 0.92%   |
| Unknown            | 3         | 0.92%   |
| 3840x1200          | 2         | 0.61%   |
| 3200x1800 (QHD+)   | 2         | 0.61%   |
| 2880x1800          | 2         | 0.61%   |
| 1024x768 (XGA)     | 2         | 0.61%   |
| 9600x2160          | 1         | 0.31%   |
| 720x1280           | 1         | 0.31%   |
| 3840x1080          | 1         | 0.31%   |
| 3600x1080          | 1         | 0.31%   |
| 3000x2000          | 1         | 0.31%   |
| 2880x1620          | 1         | 0.31%   |
| 1920x540           | 1         | 0.31%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 61        | 18.6%   |
| 15      | 49        | 14.94%  |
| 27      | 38        | 11.59%  |
| 24      | 38        | 11.59%  |
| Unknown | 26        | 7.93%   |
| 12      | 25        | 7.62%   |
| 23      | 16        | 4.88%   |
| 21      | 14        | 4.27%   |
| 17      | 8         | 2.44%   |
| 11      | 8         | 2.44%   |
| 22      | 7         | 2.13%   |
| 19      | 7         | 2.13%   |
| 14      | 7         | 2.13%   |
| 34      | 5         | 1.52%   |
| 31      | 4         | 1.22%   |
| 25      | 3         | 0.91%   |
| 20      | 3         | 0.91%   |
| 32      | 2         | 0.61%   |
| 46      | 1         | 0.3%    |
| 39      | 1         | 0.3%    |
| 29      | 1         | 0.3%    |
| 26      | 1         | 0.3%    |
| 18      | 1         | 0.3%    |
| 16      | 1         | 0.3%    |
| 6       | 1         | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 91        | 27.83%  |
| 501-600     | 90        | 27.52%  |
| 201-300     | 62        | 18.96%  |
| Unknown     | 26        | 7.95%   |
| 401-500     | 25        | 7.65%   |
| 351-400     | 13        | 3.98%   |
| 601-700     | 10        | 3.06%   |
| 701-800     | 7         | 2.14%   |
| 801-900     | 1         | 0.31%   |
| 101-200     | 1         | 0.31%   |
| 1001-1500   | 1         | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 218       | 69.21%  |
| 16/10   | 51        | 16.19%  |
| Unknown | 25        | 7.94%   |
| 5/4     | 8         | 2.54%   |
| 21/9    | 5         | 1.59%   |
| 3/2     | 4         | 1.27%   |
| 4/3     | 3         | 0.95%   |
| 6/5     | 1         | 0.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 57        | 17.38%  |
| 81-90          | 54        | 16.46%  |
| 301-350        | 39        | 11.89%  |
| 91-100         | 35        | 10.67%  |
| Unknown        | 26        | 7.93%   |
| 61-70          | 25        | 7.62%   |
| 251-300        | 20        | 6.1%    |
| 101-110        | 15        | 4.57%   |
| 71-80          | 13        | 3.96%   |
| 351-500        | 12        | 3.66%   |
| 151-200        | 12        | 3.66%   |
| 51-60          | 8         | 2.44%   |
| 121-130        | 6         | 1.83%   |
| 141-150        | 2         | 0.61%   |
| 501-1000       | 2         | 0.61%   |
| 1-40           | 1         | 0.3%    |
| 131-140        | 1         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 102       | 31.68%  |
| 121-160       | 88        | 27.33%  |
| 101-120       | 65        | 20.19%  |
| 161-240       | 30        | 9.32%   |
| Unknown       | 26        | 8.07%   |
| More than 240 | 10        | 3.11%   |
| 1-50          | 1         | 0.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1528      | 82.11%  |
| 1     | 299       | 16.07%  |
| 2     | 32        | 1.72%   |
| 3     | 2         | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1472      | 58.14%  |
| Realtek Semiconductor             | 582       | 22.99%  |
| Broadcom                          | 142       | 5.61%   |
| Qualcomm Atheros                  | 118       | 4.66%   |
| AMD                               | 22        | 0.87%   |
| IMC Networks                      | 15        | 0.59%   |
| Ericsson Business Mobile Networks | 13        | 0.51%   |
| Ralink Technology                 | 12        | 0.47%   |
| Mellanox Technologies             | 12        | 0.47%   |
| Marvell Technology Group          | 11        | 0.43%   |
| TP-Link                           | 10        | 0.39%   |
| Edimax Technology                 | 10        | 0.39%   |
| Nvidia                            | 9         | 0.36%   |
| Ralink                            | 8         | 0.32%   |
| D-Link System                     | 7         | 0.28%   |
| American Megatrends               | 7         | 0.28%   |
| U-Blox                            | 6         | 0.24%   |
| MediaTek                          | 6         | 0.24%   |
| Sierra Wireless                   | 5         | 0.2%    |
| Google                            | 5         | 0.2%    |
| Emulex                            | 5         | 0.2%    |
| IBM                               | 4         | 0.16%   |
| Dell                              | 4         | 0.16%   |
| Chelsio Communications            | 4         | 0.16%   |
| ASUSTek Computer                  | 4         | 0.16%   |
| Aquantia                          | 3         | 0.12%   |
| Samsung Electronics               | 2         | 0.08%   |
| Qualcomm Atheros Communications   | 2         | 0.08%   |
| NetXen Incorporated               | 2         | 0.08%   |
| ICS Advent                        | 2         | 0.08%   |
| Huawei Technologies               | 2         | 0.08%   |
| Hewlett-Packard                   | 2         | 0.08%   |
| Dresden Elektronik                | 2         | 0.08%   |
| Apple                             | 2         | 0.08%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.04%   |
| Xiaomi                            | 1         | 0.04%   |
| ULi Electronics                   | 1         | 0.04%   |
| T & A Mobile Phones               | 1         | 0.04%   |
| SysKonnect                        | 1         | 0.04%   |
| Standard Microsystems [SMC]       | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 511       | 16.27%  |
| Intel I211 Gigabit Network Connection                                         | 316       | 10.06%  |
| Intel I210 Gigabit Network Connection                                         | 251       | 7.99%   |
| Intel I350 Gigabit Network Connection                                         | 127       | 4.04%   |
| Intel Ethernet Controller I225-V                                              | 85        | 2.71%   |
| Intel 82574L Gigabit Network Connection                                       | 79        | 2.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 71        | 2.26%   |
| Intel 82580 Gigabit Network Connection                                        | 45        | 1.43%   |
| Intel Ethernet Controller I226-V                                              | 43        | 1.37%   |
| Intel 82576 Gigabit Network Connection                                        | 37        | 1.18%   |
| Intel 82583V Gigabit Network Connection                                       | 35        | 1.11%   |
| Intel Wireless 3165                                                           | 34        | 1.08%   |
| Intel Wi-Fi 6 AX200                                                           | 32        | 1.02%   |
| Intel Wireless 7265                                                           | 30        | 0.96%   |
| Intel Ethernet Connection I217-LM                                             | 30        | 0.96%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 30        | 0.96%   |
| Realtek RTL8125 2.5GbE Controller                                             | 29        | 0.92%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 29        | 0.92%   |
| Intel Ethernet Connection I354                                                | 27        | 0.86%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 27        | 0.86%   |
| Intel Ethernet Connection X553 1GbE                                           | 26        | 0.83%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 26        | 0.83%   |
| Intel Wireless 8265 / 8275                                                    | 24        | 0.76%   |
| Intel Ethernet Connection I219-LM                                             | 22        | 0.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 22        | 0.7%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 22        | 0.7%    |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 22        | 0.7%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 21        | 0.67%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 20        | 0.64%   |
| Intel Wireless 8260                                                           | 19        | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                                         | 19        | 0.61%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 19        | 0.61%   |
| Intel Ethernet Connection (2) I219-V                                          | 18        | 0.57%   |
| Intel Wireless 7260                                                           | 17        | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                                         | 17        | 0.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 16        | 0.51%   |
| Intel Wireless 3160                                                           | 16        | 0.51%   |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 16        | 0.51%   |
| Intel Centrino Ultimate-N 6300                                                | 15        | 0.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 14        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 333       | 53.37%  |
| Qualcomm Atheros                | 105       | 16.83%  |
| Realtek Semiconductor           | 68        | 10.9%   |
| Broadcom                        | 43        | 6.89%   |
| IMC Networks                    | 15        | 2.4%    |
| Ralink Technology               | 12        | 1.92%   |
| TP-Link                         | 10        | 1.6%    |
| Edimax Technology               | 10        | 1.6%    |
| Ralink                          | 8         | 1.28%   |
| MediaTek                        | 6         | 0.96%   |
| Sierra Wireless                 | 5         | 0.8%    |
| ASUSTek Computer                | 4         | 0.64%   |
| Qualcomm Atheros Communications | 2         | 0.32%   |
| Micro Star International        | 1         | 0.16%   |
| Dell                            | 1         | 0.16%   |
| Accton Technology               | 1         | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                             | 34        | 5.41%   |
| Intel Wi-Fi 6 AX200                                             | 32        | 5.1%    |
| Intel Wireless 7265                                             | 30        | 4.78%   |
| Intel Wireless 8265 / 8275                                      | 24        | 3.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                    | 22        | 3.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 21        | 3.34%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 20        | 3.18%   |
| Intel Wireless 8260                                             | 19        | 3.03%   |
| Intel Wireless 7260                                             | 17        | 2.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 16        | 2.55%   |
| Intel Wireless 3160                                             | 16        | 2.55%   |
| Intel Centrino Ultimate-N 6300                                  | 15        | 2.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 14        | 2.23%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card            | 14        | 2.23%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 12        | 1.91%   |
| Intel Wireless-AC 9260                                          | 12        | 1.91%   |
| Intel Centrino Advanced-N 6235                                  | 11        | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 10        | 1.59%   |
| Broadcom BCM43224 802.11a/b/g/n                                 | 10        | 1.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 9         | 1.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 9         | 1.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                          | 9         | 1.43%   |
| Intel Wi-Fi 6 AX201                                             | 9         | 1.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 9         | 1.43%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 8         | 1.27%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter        | 7         | 1.11%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                      | 7         | 1.11%   |
| Broadcom BCM4321 802.11a/b/g/n                                  | 7         | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 6         | 0.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 6         | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 6         | 0.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter        | 5         | 0.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 5         | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection           | 5         | 0.8%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]  | 5         | 0.8%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter              | 5         | 0.8%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller          | 5         | 0.8%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                             | 4         | 0.64%   |
| Sierra Wireless EM7455                                          | 4         | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                 | 4         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 1300      | 62.95%  |
| Realtek Semiconductor       | 559       | 27.07%  |
| Broadcom                    | 108       | 5.23%   |
| AMD                         | 22        | 1.07%   |
| Qualcomm Atheros            | 16        | 0.77%   |
| Marvell Technology Group    | 11        | 0.53%   |
| Nvidia                      | 9         | 0.44%   |
| American Megatrends         | 7         | 0.34%   |
| Google                      | 5         | 0.24%   |
| Emulex                      | 4         | 0.19%   |
| D-Link System               | 4         | 0.19%   |
| Aquantia                    | 3         | 0.15%   |
| Samsung Electronics         | 2         | 0.1%    |
| ICS Advent                  | 2         | 0.1%    |
| Apple                       | 2         | 0.1%    |
| Xiaomi                      | 1         | 0.05%   |
| T & A Mobile Phones         | 1         | 0.05%   |
| SysKonnect                  | 1         | 0.05%   |
| Standard Microsystems [SMC] | 1         | 0.05%   |
| QLogic                      | 1         | 0.05%   |
| National Semiconductor      | 1         | 0.05%   |
| JMicron Technology          | 1         | 0.05%   |
| Insyde Software             | 1         | 0.05%   |
| Digital Equipment           | 1         | 0.05%   |
| Davicom Semiconductor       | 1         | 0.05%   |
| Chelsio Communications      | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 511       | 20.95%  |
| Intel I211 Gigabit Network Connection                                         | 316       | 12.96%  |
| Intel I210 Gigabit Network Connection                                         | 251       | 10.29%  |
| Intel I350 Gigabit Network Connection                                         | 127       | 5.21%   |
| Intel Ethernet Controller I225-V                                              | 85        | 3.49%   |
| Intel 82574L Gigabit Network Connection                                       | 79        | 3.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 71        | 2.91%   |
| Intel 82580 Gigabit Network Connection                                        | 45        | 1.85%   |
| Intel Ethernet Controller I226-V                                              | 43        | 1.76%   |
| Intel 82576 Gigabit Network Connection                                        | 37        | 1.52%   |
| Intel 82583V Gigabit Network Connection                                       | 35        | 1.44%   |
| Intel Ethernet Connection I217-LM                                             | 30        | 1.23%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 30        | 1.23%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 29        | 1.19%   |
| Realtek RTL8125 2.5GbE Controller                                             | 28        | 1.15%   |
| Intel Ethernet Connection I354                                                | 27        | 1.11%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 27        | 1.11%   |
| Intel Ethernet Connection X553 1GbE                                           | 26        | 1.07%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 26        | 1.07%   |
| Intel Ethernet Connection I219-LM                                             | 22        | 0.9%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 22        | 0.9%    |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 22        | 0.9%    |
| Intel Ethernet Connection (2) I219-LM                                         | 19        | 0.78%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 19        | 0.78%   |
| Intel Ethernet Connection (2) I219-V                                          | 18        | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                                         | 17        | 0.7%    |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 16        | 0.66%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 14        | 0.57%   |
| Intel Ethernet Controller X550                                                | 14        | 0.57%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 14        | 0.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 13        | 0.53%   |
| Intel Ethernet Connection (7) I219-V                                          | 13        | 0.53%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 13        | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 12        | 0.49%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 11        | 0.45%   |
| Intel Ethernet Connection (4) I219-V                                          | 11        | 0.45%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 11        | 0.45%   |
| Intel Ethernet Connection I217-V                                              | 10        | 0.41%   |
| Intel 82577LM Gigabit Network Connection                                      | 10        | 0.41%   |
| Intel 82579V Gigabit Network Connection                                       | 9         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1802      | 73.43%  |
| WiFi     | 582       | 23.72%  |
| Unknown  | 43        | 1.75%   |
| Modem    | 27        | 1.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1723      | 89.41%  |
| WiFi     | 193       | 10.02%  |
| Unknown  | 10        | 0.52%   |
| Modem    | 1         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 445       | 23.75%  |
| 4     | 358       | 19.1%   |
| 3     | 295       | 15.74%  |
| 1     | 222       | 11.85%  |
| 6     | 213       | 11.37%  |
| 5     | 151       | 8.06%   |
| 8     | 82        | 4.38%   |
| 10    | 31        | 1.65%   |
| 7     | 23        | 1.23%   |
| 0     | 19        | 1.01%   |
| 9     | 17        | 0.91%   |
| 12    | 9         | 0.48%   |
| 14    | 4         | 0.21%   |
| 11    | 2         | 0.11%   |
| 20    | 1         | 0.05%   |
| 17    | 1         | 0.05%   |
| 16    | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1510      | 78.28%  |
| Yes  | 419       | 21.72%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 219       | 58.24%  |
| Apple                           | 27        | 7.18%   |
| IMC Networks                    | 26        | 6.91%   |
| Qualcomm Atheros Communications | 25        | 6.65%   |
| Broadcom                        | 24        | 6.38%   |
| Realtek Semiconductor           | 22        | 5.85%   |
| Foxconn / Hon Hai               | 8         | 2.13%   |
| ASUSTek Computer                | 7         | 1.86%   |
| Cambridge Silicon Radio         | 4         | 1.06%   |
| MediaTek                        | 3         | 0.8%    |
| Lite-On Technology              | 3         | 0.8%    |
| Dell                            | 3         | 0.8%    |
| Hewlett-Packard                 | 2         | 0.53%   |
| Alps Electric                   | 2         | 0.53%   |
| Micro Star International        | 1         | 0.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 99        | 26.26%  |
| Intel AX200 Bluetooth                                       | 34        | 9.02%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 28        | 7.43%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 15        | 3.98%   |
| Intel AX201 Bluetooth                                       | 15        | 3.98%   |
| Realtek Bluetooth Adapter                                   | 12        | 3.18%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 12        | 3.18%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 12        | 3.18%   |
| Apple Bluetooth Host Controller                             | 11        | 2.92%   |
| Intel Wireless-AC 3168 Bluetooth                            | 9         | 2.39%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 9         | 2.39%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 9         | 2.39%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 8         | 2.12%   |
| Intel AX210 Bluetooth                                       | 7         | 1.86%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 7         | 1.86%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 6         | 1.59%   |
| IMC Networks Realtek Bluetooth Adapter                      | 4         | 1.06%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 4         | 1.06%   |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 0.8%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 3         | 0.8%    |
| Qualcomm Atheros AR9462 Bluetooth                           | 3         | 0.8%    |
| MediaTek RZ608 Bluetooth Adapter                            | 3         | 0.8%    |
| Lite-On Atheros AR3012 Bluetooth                            | 3         | 0.8%    |
| ASUS USB-BT500                                              | 3         | 0.8%    |
| Realtek Bluetooth 4.2 Adapter                               | 2         | 0.53%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 2         | 0.53%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 2         | 0.53%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 2         | 0.53%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 2         | 0.53%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 2         | 0.53%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 2         | 0.53%   |
| Broadcom BCM2045 Bluetooth                                  | 2         | 0.53%   |
| Apple Broadcom Built-in Bluetooth                           | 2         | 0.53%   |
| Apple Bluetooth USB Host Controller                         | 2         | 0.53%   |
| Apple Bluetooth HCI                                         | 2         | 0.53%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 0.27%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.27%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.27%   |
| Realtek RTL8723A Bluetooth                                  | 1         | 0.27%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 997       | 70.86%  |
| AMD                                          | 242       | 17.2%   |
| Nvidia                                       | 97        | 6.89%   |
| C-Media Electronics                          | 14        | 1%      |
| Logitech                                     | 6         | 0.43%   |
| Zoran Co. Personal Media Division (Nogatech) | 5         | 0.36%   |
| GN Netcom                                    | 5         | 0.36%   |
| Texas Instruments                            | 4         | 0.28%   |
| JMTek                                        | 4         | 0.28%   |
| VIA Technologies                             | 3         | 0.21%   |
| Tenx Technology                              | 3         | 0.21%   |
| Creative Labs                                | 3         | 0.21%   |
| Realtek Semiconductor                        | 2         | 0.14%   |
| Kingston Technology                          | 2         | 0.14%   |
| Corsair                                      | 2         | 0.14%   |
| ZOOM                                         | 1         | 0.07%   |
| Yamaha                                       | 1         | 0.07%   |
| ULi Electronics                              | 1         | 0.07%   |
| Trust                                        | 1         | 0.07%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.07%   |
| RME                                          | 1         | 0.07%   |
| Phison Electronics                           | 1         | 0.07%   |
| Native Instruments                           | 1         | 0.07%   |
| M-Audio                                      | 1         | 0.07%   |
| Lenovo                                       | 1         | 0.07%   |
| Hewlett-Packard                              | 1         | 0.07%   |
| Generalplus Technology                       | 1         | 0.07%   |
| ESS Technology                               | 1         | 0.07%   |
| DSEA A/S                                     | 1         | 0.07%   |
| Creative Technology                          | 1         | 0.07%   |
| Blue Microphones                             | 1         | 0.07%   |
| AudioQuest                                   | 1         | 0.07%   |
| Audient                                      | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 109       | 6.61%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 105       | 6.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 79        | 4.79%   |
| AMD Kabini HDMI/DP Audio                                                                          | 76        | 4.61%   |
| AMD FCH Azalia Controller                                                                         | 64        | 3.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 62        | 3.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 60        | 3.64%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 60        | 3.64%   |
| Intel Jasper Lake HD Audio                                                                        | 57        | 3.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 49        | 2.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 49        | 2.97%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 45        | 2.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 45        | 2.73%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 37        | 2.24%   |
| Intel Cannon Lake PCH cAVS                                                                        | 37        | 2.24%   |
| Intel 8 Series HD Audio Controller                                                                | 37        | 2.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 36        | 2.18%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 29        | 1.76%   |
| Intel Broadwell-U Audio Controller                                                                | 28        | 1.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 28        | 1.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 26        | 1.58%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 26        | 1.58%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 22        | 1.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 21        | 1.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 21        | 1.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 21        | 1.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 21        | 1.27%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 18        | 1.09%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 18        | 1.09%   |
| Intel 200 Series PCH HD Audio                                                                     | 17        | 1.03%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 15        | 0.91%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 14        | 0.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 12        | 0.73%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 10        | 0.61%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 9         | 0.55%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 9         | 0.55%   |
| Intel Alder Lake-N HD Graphics SGPC                                                               | 9         | 0.55%   |
| AMD Wrestler HDMI Audio                                                                           | 9         | 0.55%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 9         | 0.55%   |
| Nvidia MCP79 High Definition Audio                                                                | 8         | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 341       | 18.45%  |
| Unknown                      | 255       | 13.8%   |
| Kingston                     | 210       | 11.36%  |
| Crucial                      | 206       | 11.15%  |
| SK hynix                     | 188       | 10.17%  |
| Micron Technology            | 144       | 7.79%   |
| G.Skill                      | 89        | 4.82%   |
| Unknown                      | 62        | 3.35%   |
| Corsair                      | 59        | 3.19%   |
| Transcend                    | 45        | 2.44%   |
| Unknown (ABCD)               | 42        | 2.27%   |
| A-DATA Technology            | 35        | 1.89%   |
| ATP                          | 24        | 1.3%    |
| Nanya Technology             | 23        | 1.24%   |
| Ramaxel Technology           | 15        | 0.81%   |
| Hewlett-Packard              | 14        | 0.76%   |
| Apacer                       | 11        | 0.6%    |
| Elpida                       | 8         | 0.43%   |
| Toshiba                      | 6         | 0.32%   |
| Kimtigo                      | 6         | 0.32%   |
| Patriot                      | 5         | 0.27%   |
| Shenzhen Jinge Information   | 4         | 0.22%   |
| Innodisk                     | 4         | 0.22%   |
| Avant                        | 3         | 0.16%   |
| Wodposit                     | 2         | 0.11%   |
| Unknown (AB)                 | 2         | 0.11%   |
| Unknown (0x7F7F7F94FFFFFFFF) | 2         | 0.11%   |
| Unknown (09C7)               | 2         | 0.11%   |
| Timetec                      | 2         | 0.11%   |
| Tigo                         | 2         | 0.11%   |
| Teikon                       | 2         | 0.11%   |
| SK_Hynix                     | 2         | 0.11%   |
| PNY                          | 2         | 0.11%   |
| HPE                          | 2         | 0.11%   |
| GeIL                         | 2         | 0.11%   |
| 019400B300CE                 | 2         | 0.11%   |
| Vasekey                      | 1         | 0.05%   |
| Unknown (8A5D)               | 1         | 0.05%   |
| Unknown (8A02)               | 1         | 0.05%   |
| Unknown (89EC)               | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 62        | 3.18%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 49        | 2.52%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 42        | 2.16%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 19        | 0.98%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 16        | 0.82%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 15        | 0.77%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s          | 13        | 0.67%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 12        | 0.62%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 12        | 0.62%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s        | 12        | 0.62%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 11        | 0.56%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 10        | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 10        | 0.51%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 10        | 0.51%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 10        | 0.51%   |
| G.Skill RAM F4-2400C16-8GRS 8GB SODIMM DDR4 2400MT/s         | 10        | 0.51%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 9         | 0.46%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 9         | 0.46%   |
| Micron RAM Module 8GB Row Of Chips LPDDR4 3200MT/s           | 9         | 0.46%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s      | 9         | 0.46%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s        | 9         | 0.46%   |
| ATP RAM X4G08QA8BNWESO-7-TO1 8GB SODIMM DDR4 3200MT/s        | 9         | 0.46%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 8         | 0.41%   |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s        | 8         | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 7         | 0.36%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                   | 7         | 0.36%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                     | 7         | 0.36%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                   | 7         | 0.36%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 7         | 0.36%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 7         | 0.36%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 7         | 0.36%   |
| Samsung RAM M391B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s          | 7         | 0.36%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 3200MT/s         | 7         | 0.36%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s         | 7         | 0.36%   |
| G.Skill RAM F4-2400C16-4GRS 4GB SODIMM DDR4 2400MT/s         | 7         | 0.36%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s        | 7         | 0.36%   |
| ATP RAM AW12P6438BLK0S 4GB DIMM DDR3 1600MT/s                | 7         | 0.36%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                    | 6         | 0.31%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 6         | 0.31%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                 | 6         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 779       | 46.23%  |
| DDR4    | 677       | 40.18%  |
| DDR2    | 80        | 4.75%   |
| LPDDR4  | 60        | 3.56%   |
| Unknown | 36        | 2.14%   |
| SDRAM   | 24        | 1.42%   |
| DDR     | 10        | 0.59%   |
| LPDDR3  | 7         | 0.42%   |
| DDR5    | 6         | 0.36%   |
| LPDDR5  | 4         | 0.24%   |
| RAM     | 1         | 0.06%   |
| DRAM    | 1         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 860       | 51.37%  |
| DIMM         | 769       | 45.94%  |
| Row Of Chips | 31        | 1.85%   |
| Unknown      | 7         | 0.42%   |
| Chip         | 6         | 0.36%   |
| FB-DIMM      | 1         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 657       | 36.97%  |
| 4096  | 571       | 32.13%  |
| 16384 | 249       | 14.01%  |
| 2048  | 224       | 12.61%  |
| 32768 | 36        | 2.03%   |
| 1024  | 33        | 1.86%   |
| 512   | 4         | 0.23%   |
| 256   | 2         | 0.11%   |
| 65536 | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 493       | 28.08%  |
| 2400    | 243       | 13.84%  |
| 1333    | 226       | 12.87%  |
| 2667    | 197       | 11.22%  |
| 3200    | 169       | 9.62%   |
| 2133    | 94        | 5.35%   |
| 667     | 58        | 3.3%    |
| 800     | 55        | 3.13%   |
| Unknown | 33        | 1.88%   |
| 1867    | 32        | 1.82%   |
| 2666    | 22        | 1.25%   |
| 1066    | 21        | 1.2%    |
| 1334    | 20        | 1.14%   |
| 1067    | 19        | 1.08%   |
| 1866    | 18        | 1.03%   |
| 3000    | 11        | 0.63%   |
| 2933    | 10        | 0.57%   |
| 4800    | 5         | 0.28%   |
| 4267    | 5         | 0.28%   |
| 3600    | 5         | 0.28%   |
| 6400    | 4         | 0.23%   |
| 533     | 4         | 0.23%   |
| 1033    | 2         | 0.11%   |
| 333     | 2         | 0.11%   |
| 65535   | 1         | 0.06%   |
| 5600    | 1         | 0.06%   |
| 3534    | 1         | 0.06%   |
| 3500    | 1         | 0.06%   |
| 2600    | 1         | 0.06%   |
| 1419    | 1         | 0.06%   |
| 975     | 1         | 0.06%   |
| 400     | 1         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 3         | 42.86%  |
| Ricoh               | 1         | 14.29%  |
| QinHeng Electronics | 1         | 14.29%  |
| Prolific Technology | 1         | 14.29%  |
| Hewlett-Packard     | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Brother MFC-7360N             | 2         | 28.57%  |
| Ricoh SP 112                  | 1         | 14.29%  |
| QinHeng CH340S                | 1         | 14.29%  |
| Prolific PL2305 Parallel Port | 1         | 14.29%  |
| HP HP LaserJet P2035 HP Print | 1         | 14.29%  |
| Brother HL-L2310D series      | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart_bsd/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 3         | 75%     |
| Seiko Epson | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                             | 2         | 50%     |
| Seiko Epson WF-2860 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1         | 25%     |
| Canon CanoScan LiDE 120                                                             | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 62        | 32.63%  |
| Bison Electronics                      | 20        | 10.53%  |
| Microdia                               | 12        | 6.32%   |
| Realtek Semiconductor                  | 11        | 5.79%   |
| IMC Networks                           | 11        | 5.79%   |
| Logitech                               | 10        | 5.26%   |
| Suyin                                  | 9         | 4.74%   |
| Lite-On Technology                     | 9         | 4.74%   |
| Sunplus Innovation Technology          | 7         | 3.68%   |
| Syntek                                 | 6         | 3.16%   |
| Apple                                  | 6         | 3.16%   |
| Lenovo                                 | 5         | 2.63%   |
| Alcor Micro                            | 4         | 2.11%   |
| Z-Star Microelectronics                | 2         | 1.05%   |
| Silicon Motion                         | 2         | 1.05%   |
| Quanta                                 | 2         | 1.05%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.05%   |
| ARC International                      | 2         | 1.05%   |
| Trust                                  | 1         | 0.53%   |
| Tripath Technology                     | 1         | 0.53%   |
| SunplusIT                              | 1         | 0.53%   |
| Ricoh                                  | 1         | 0.53%   |
| Pixart Imaging                         | 1         | 0.53%   |
| Luxvisions Innotech Limited            | 1         | 0.53%   |
| Intel                                  | 1         | 0.53%   |
| Cubeternet                             | 1         | 0.53%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 27        | 14.14%  |
| Bison Integrated Camera                  | 9         | 4.71%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 7         | 3.66%   |
| Lite-On Integrated Camera                | 6         | 3.14%   |
| IMC Networks Integrated Camera           | 6         | 3.14%   |
| Microdia Integrated Webcam               | 5         | 2.62%   |
| Chicony FJ Camera                        | 5         | 2.62%   |
| Chicony HD Webcam                        | 4         | 2.09%   |
| Apple FaceTime HD Camera (Built-in)      | 4         | 2.09%   |
| Syntek Integrated Camera                 | 3         | 1.57%   |
| Suyin RGBIR Camera                       | 3         | 1.57%   |
| Realtek USB 2.0 PC Camera                | 3         | 1.57%   |
| Chicony Integrated Camera [ThinkPad]     | 3         | 1.57%   |
| Alcor Micro USB 2.0 Camera               | 3         | 1.57%   |
| Syntek Lenovo EasyCamera                 | 2         | 1.05%   |
| Realtek Integrated_Webcam_HD             | 2         | 1.05%   |
| Quanta HP TrueVision HD Camera           | 2         | 1.05%   |
| Microdia Integrated_Webcam_HD            | 2         | 1.05%   |
| Logitech Webcam C270                     | 2         | 1.05%   |
| Logitech HD Pro Webcam C920              | 2         | 1.05%   |
| Logitech C920 PRO HD Webcam              | 2         | 1.05%   |
| Logitech C920 HD Pro Webcam              | 2         | 1.05%   |
| Lite-On Realtek PC Camera                | 2         | 1.05%   |
| Lenovo Integrated Webcam [R5U877]        | 2         | 1.05%   |
| Lenovo Integrated Camera                 | 2         | 1.05%   |
| IMC Networks Realtek PC Camera           | 2         | 1.05%   |
| Chicony HP HD Webcam [Fixed]             | 2         | 1.05%   |
| Chicony HD WebCam (Acer)                 | 2         | 1.05%   |
| Chicony Chicony USB2.0 Camera            | 2         | 1.05%   |
| Bison ThinkPad Integrated Camera         | 2         | 1.05%   |
| Bison SunplusIT Integrated Camera        | 2         | 1.05%   |
| Bison SunplusIT INC. Integrated Camera   | 2         | 1.05%   |
| Bison Lenovo EasyCamera                  | 2         | 1.05%   |
| ARC International Camera                 | 2         | 1.05%   |
| Z-Star Venus USB2.0 Camera               | 1         | 0.52%   |
| Z-Star Lenovo USB 2.0 UVC Camera         | 1         | 0.52%   |
| Trust Trust USB Camera                   | 1         | 0.52%   |
| Tripath USB Camera                       | 1         | 0.52%   |
| Syntek EasyCamera                        | 1         | 0.52%   |
| Suyin Sony Visual Communication Camera   | 1         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 24        | 35.29%  |
| Upek                       | 11        | 16.18%  |
| Synaptics                  | 11        | 16.18%  |
| AuthenTec                  | 5         | 7.35%   |
| Shenzhen Goodix Technology | 4         | 5.88%   |
| LighTuning Technology      | 4         | 5.88%   |
| Broadcom                   | 3         | 4.41%   |
| STMicroelectronics         | 2         | 2.94%   |
| Elan Microelectronics      | 2         | 2.94%   |
| Next Biometrics            | 1         | 1.47%   |
| DigitalPersona             | 1         | 1.47%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 10        | 14.71%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 9         | 13.24%  |
| Validity Sensors Synaptics WBDI                                              | 7         | 10.29%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 5         | 7.35%   |
| Shenzhen Goodix Fingerprint Reader                                           | 3         | 4.41%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 4.41%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 2.94%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 2         | 2.94%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 2.94%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 2         | 2.94%   |
| STMicroelectronics Fingerprint Reader                                        | 2         | 2.94%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 2         | 2.94%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 2         | 2.94%   |
| Elan Fingerprint Sensor                                                      | 2         | 2.94%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 1.47%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 1.47%   |
| Upek TCS5B Fingerprint sensor                                                | 1         | 1.47%   |
| Synaptics WBDI                                                               | 1         | 1.47%   |
| Synaptics UWP WBDI                                                           | 1         | 1.47%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 1.47%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 1         | 1.47%   |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 1.47%   |
| DigitalPersona Fingerprint Reader                                            | 1         | 1.47%   |
| AuthenTec AES2660                                                            | 1         | 1.47%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 1         | 1.47%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 1.47%   |
| AuthenTec AES1660                                                            | 1         | 1.47%   |
| AuthenTec AES1600                                                            | 1         | 1.47%   |
| Unknown                                                                      | 1         | 1.47%   |

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
| 1     | 715       | 37.65%  |
| 0     | 700       | 36.86%  |
| 2     | 280       | 14.74%  |
| 3     | 132       | 6.95%   |
| 4     | 52        | 2.74%   |
| 5     | 16        | 0.84%   |
| 6     | 3         | 0.16%   |
| 7     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 1030      | 61.6%   |
| Bluetooth                | 171       | 10.23%  |
| Net/wireless             | 155       | 9.27%   |
| Card reader              | 112       | 6.7%    |
| Fingerprint reader       | 59        | 3.53%   |
| Firewire controller      | 41        | 2.45%   |
| Network                  | 26        | 1.56%   |
| Net/ethernet             | 25        | 1.5%    |
| Sound                    | 24        | 1.44%   |
| Graphics card            | 13        | 0.78%   |
| Modem                    | 5         | 0.3%    |
| Storage                  | 4         | 0.24%   |
| Storage/ide              | 2         | 0.12%   |
| Storage/ata              | 2         | 0.12%   |
| Storage/raid             | 1         | 0.06%   |
| Storage/nvme             | 1         | 0.06%   |
| Dvb card                 | 1         | 0.06%   |

