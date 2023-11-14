BSD in Germany - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for BSD in Germany.

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

Total: 1894

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [b4c8864cef](https://bsd-hardware.info/?probe=b4c8864cef) | Nov 06, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [456fe0a275](https://bsd-hardware.info/?probe=456fe0a275) | Nov 06, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [ea78913e4c](https://bsd-hardware.info/?probe=ea78913e4c) | Nov 05, 2023 |
| Gigabyte      | B360N WIFI-CF               | [38b5f3b9ad](https://bsd-hardware.info/?probe=38b5f3b9ad) | Nov 04, 2023 |
| CncTion       | N5105-4L B0                 | [86aa07c0ae](https://bsd-hardware.info/?probe=86aa07c0ae) | Nov 04, 2023 |
| ASRock        | B365M-HDV                   | [368366454f](https://bsd-hardware.info/?probe=368366454f) | Nov 03, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [e6927b5eb8](https://bsd-hardware.info/?probe=e6927b5eb8) | Nov 03, 2023 |
| Protectli     | FW6 Ver                     | [13eb07060d](https://bsd-hardware.info/?probe=13eb07060d) | Nov 03, 2023 |
| PC Engines    | apu4                        | [b85acbe43d](https://bsd-hardware.info/?probe=b85acbe43d) | Nov 03, 2023 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | [d4298a293f](https://bsd-hardware.info/?probe=d4298a293f) | Nov 02, 2023 |
| Techvision    | TVI7309X B0                 | [b038d8a95d](https://bsd-hardware.info/?probe=b038d8a95d) | Nov 02, 2023 |
| Unknown       | Unknown                     | [691338cb44](https://bsd-hardware.info/?probe=691338cb44) | Nov 02, 2023 |
| Unknown       | Unknown                     | [c6610a58ac](https://bsd-hardware.info/?probe=c6610a58ac) | Nov 02, 2023 |
| PICO PC       | MNHO-113                    | [a4175476a0](https://bsd-hardware.info/?probe=a4175476a0) | Nov 02, 2023 |
| Fujitsu       | D3544-A1 S26361-D3544-A1... | [2fcac7d927](https://bsd-hardware.info/?probe=2fcac7d927) | Nov 01, 2023 |
| Hardkernel    | ODROID-H2                   | [41c4097002](https://bsd-hardware.info/?probe=41c4097002) | Oct 30, 2023 |
| AZW           | EQ                          | [034b060507](https://bsd-hardware.info/?probe=034b060507) | Oct 30, 2023 |
| MW            | GMLK-2_5G4L                 | [ec852f7037](https://bsd-hardware.info/?probe=ec852f7037) | Oct 29, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | [fc42f6db17](https://bsd-hardware.info/?probe=fc42f6db17) | Oct 28, 2023 |
| HP            | 1825                        | [8a0a258efc](https://bsd-hardware.info/?probe=8a0a258efc) | Oct 28, 2023 |
| Gigabyte      | J3455N-D3H                  | [6448ed1b12](https://bsd-hardware.info/?probe=6448ed1b12) | Oct 28, 2023 |
| IGEL Techn... | D220                        | [3478db91ef](https://bsd-hardware.info/?probe=3478db91ef) | Oct 28, 2023 |
| Supermicro    | X11SSH-F                    | [73160cea1d](https://bsd-hardware.info/?probe=73160cea1d) | Oct 28, 2023 |
| Protectli     | FW4B                        | [23c31e7f9f](https://bsd-hardware.info/?probe=23c31e7f9f) | Oct 27, 2023 |
| Intel         | DB75EN AAG39650-302         | [5d64d42233](https://bsd-hardware.info/?probe=5d64d42233) | Oct 27, 2023 |
| Fujitsu       | D3314-E1 S26361-D3314-E1    | [2cde7906c1](https://bsd-hardware.info/?probe=2cde7906c1) | Oct 27, 2023 |
| Fujitsu       | D3314-A1 S26361-D3314-A1    | [d005339b5f](https://bsd-hardware.info/?probe=d005339b5f) | Oct 27, 2023 |
| Gigabyte      | X570S UD                    | [fe3d35aef8](https://bsd-hardware.info/?probe=fe3d35aef8) | Oct 27, 2023 |
| PC Engines    | apu4                        | [7bbd252741](https://bsd-hardware.info/?probe=7bbd252741) | Oct 27, 2023 |
| Acer          | Veriton X4620G v1.0         | [bc374cdc01](https://bsd-hardware.info/?probe=bc374cdc01) | Oct 26, 2023 |
| Protectli     | FW4B Ver                    | [0d97ba1ab0](https://bsd-hardware.info/?probe=0d97ba1ab0) | Oct 24, 2023 |
| Gigabyte      | MZGLKBP-00                  | [dcd8b6e432](https://bsd-hardware.info/?probe=dcd8b6e432) | Oct 24, 2023 |
| Gigabyte      | X570S UD                    | [dea9eee8a4](https://bsd-hardware.info/?probe=dea9eee8a4) | Oct 24, 2023 |
| Techvision    | TVI7309X B0                 | [38b1931562](https://bsd-hardware.info/?probe=38b1931562) | Oct 24, 2023 |
| AZW           | EQ                          | [8cb6ac80d2](https://bsd-hardware.info/?probe=8cb6ac80d2) | Oct 23, 2023 |
| Unknown       | YL-J3160L4                  | [3192ead8b5](https://bsd-hardware.info/?probe=3192ead8b5) | Oct 22, 2023 |
| Unknown       | J3160-4L                    | [d69749afe5](https://bsd-hardware.info/?probe=d69749afe5) | Oct 18, 2023 |
| PC Engines    | APU2                        | [7fb59a92f0](https://bsd-hardware.info/?probe=7fb59a92f0) | Oct 16, 2023 |
| ASRock        | H110M-DVS R3.0              | [abe8593d6e](https://bsd-hardware.info/?probe=abe8593d6e) | Oct 15, 2023 |
| MW            | GMLK-2_5G4L                 | [eb383d6f22](https://bsd-hardware.info/?probe=eb383d6f22) | Oct 15, 2023 |
| MW            | GMLK-2_5G4L                 | [248c73db22](https://bsd-hardware.info/?probe=248c73db22) | Oct 14, 2023 |
| Unknown       | Unknown                     | [77a827631b](https://bsd-hardware.info/?probe=77a827631b) | Oct 13, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | [8b0d009cc4](https://bsd-hardware.info/?probe=8b0d009cc4) | Oct 13, 2023 |
| Unknown       | YL-J3160L4                  | [65acf27cad](https://bsd-hardware.info/?probe=65acf27cad) | Oct 13, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [516eda52f0](https://bsd-hardware.info/?probe=516eda52f0) | Oct 12, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | [bb82c13e39](https://bsd-hardware.info/?probe=bb82c13e39) | Oct 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [418d78095d](https://bsd-hardware.info/?probe=418d78095d) | Oct 12, 2023 |
| Yanling       | YL-CLU6L-V1                 | [f3b384d87a](https://bsd-hardware.info/?probe=f3b384d87a) | Oct 12, 2023 |
| Unknown       | Unknown                     | [30ec824cf5](https://bsd-hardware.info/?probe=30ec824cf5) | Oct 11, 2023 |
| Unknown       | Unknown                     | [3d5abb3996](https://bsd-hardware.info/?probe=3d5abb3996) | Oct 11, 2023 |
| Unknown       | Unknown                     | [e4faecc5e8](https://bsd-hardware.info/?probe=e4faecc5e8) | Oct 10, 2023 |
| Unknown       | Unknown                     | [5031b0a5a7](https://bsd-hardware.info/?probe=5031b0a5a7) | Oct 10, 2023 |
| Yanling       | YL-CLU6L-V1                 | [cf15e11738](https://bsd-hardware.info/?probe=cf15e11738) | Oct 10, 2023 |
| Unknown       | QD-CMU01                    | [8637821e57](https://bsd-hardware.info/?probe=8637821e57) | Oct 09, 2023 |
| ASRock        | A75M-HVS                    | [93709074ae](https://bsd-hardware.info/?probe=93709074ae) | Oct 09, 2023 |
| Intel         | DENLOW_WS                   | [11b0d7b64f](https://bsd-hardware.info/?probe=11b0d7b64f) | Oct 07, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [d7a7e7338f](https://bsd-hardware.info/?probe=d7a7e7338f) | Oct 07, 2023 |
| ASRock        | J5040-ITX                   | [dffb96790c](https://bsd-hardware.info/?probe=dffb96790c) | Oct 06, 2023 |
| GoWin Solu... | R86S                        | [91b63fa5c7](https://bsd-hardware.info/?probe=91b63fa5c7) | Oct 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [31c7e1d3f3](https://bsd-hardware.info/?probe=31c7e1d3f3) | Oct 06, 2023 |
| Deciso        | Netboard A8                 | [cf3b678212](https://bsd-hardware.info/?probe=cf3b678212) | Oct 06, 2023 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | [5b33d7b22e](https://bsd-hardware.info/?probe=5b33d7b22e) | Oct 04, 2023 |
| PC Engines    | APU2                        | [626d74b530](https://bsd-hardware.info/?probe=626d74b530) | Oct 04, 2023 |
| PC Engines    | apu4                        | [0e813a0050](https://bsd-hardware.info/?probe=0e813a0050) | Oct 04, 2023 |
| Unknown       | Unknown                     | [f5e7677e76](https://bsd-hardware.info/?probe=f5e7677e76) | Oct 01, 2023 |
| PC Engines    | APU2                        | [064fd13617](https://bsd-hardware.info/?probe=064fd13617) | Oct 01, 2023 |
| Unknown       | Unknown                     | [716f9b28ab](https://bsd-hardware.info/?probe=716f9b28ab) | Sep 30, 2023 |
| Unknown       | Unknown                     | [fb21a44f71](https://bsd-hardware.info/?probe=fb21a44f71) | Sep 29, 2023 |
| Techvision    | TVI7309X B0                 | [f50d617197](https://bsd-hardware.info/?probe=f50d617197) | Sep 28, 2023 |
| Gigabyte      | B450M S2H V2                | [31da8655d1](https://bsd-hardware.info/?probe=31da8655d1) | Sep 28, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [b3f0a784ab](https://bsd-hardware.info/?probe=b3f0a784ab) | Sep 28, 2023 |
| Unknown       | YL-J1900L4-V2               | [c186f8b50c](https://bsd-hardware.info/?probe=c186f8b50c) | Sep 25, 2023 |
| Unknown       | Unknown                     | [1ba135fef1](https://bsd-hardware.info/?probe=1ba135fef1) | Sep 24, 2023 |
| Unknown       | Unknown                     | [9c8516c8a8](https://bsd-hardware.info/?probe=9c8516c8a8) | Sep 24, 2023 |
| ASUSTek       | PRIME X470-PRO              | [6a2ce1e29f](https://bsd-hardware.info/?probe=6a2ce1e29f) | Sep 24, 2023 |
| NU591         | 1.0                         | [99f3260ee0](https://bsd-hardware.info/?probe=99f3260ee0) | Sep 24, 2023 |
| PC Engines    | APU2                        | [3c7bd005ef](https://bsd-hardware.info/?probe=3c7bd005ef) | Sep 23, 2023 |
| Yanling       | YL-CLU6L-V1                 | [06d8f02eb7](https://bsd-hardware.info/?probe=06d8f02eb7) | Sep 22, 2023 |
| Unknown       | Unknown                     | [16640c7f04](https://bsd-hardware.info/?probe=16640c7f04) | Sep 22, 2023 |
| Unknown       | Unknown                     | [fcde651e99](https://bsd-hardware.info/?probe=fcde651e99) | Sep 21, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [e046bd9405](https://bsd-hardware.info/?probe=e046bd9405) | Sep 21, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [90f89eea16](https://bsd-hardware.info/?probe=90f89eea16) | Sep 21, 2023 |
| ASRock        | J3455B-ITX                  | [c5a2093552](https://bsd-hardware.info/?probe=c5a2093552) | Sep 21, 2023 |
| Unknown       | Unknown                     | [3c479d7824](https://bsd-hardware.info/?probe=3c479d7824) | Sep 20, 2023 |
| Unknown       | Unknown                     | [13ba11c952](https://bsd-hardware.info/?probe=13ba11c952) | Sep 20, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [92da10b93b](https://bsd-hardware.info/?probe=92da10b93b) | Sep 20, 2023 |
| Unknown       | SKYBAY                      | [95286f41d9](https://bsd-hardware.info/?probe=95286f41d9) | Sep 19, 2023 |
| Intel         | DENLOW_WS                   | [029b3cdd58](https://bsd-hardware.info/?probe=029b3cdd58) | Sep 16, 2023 |
| Unknown       | MANIFOLD 2-C                | [80707f8712](https://bsd-hardware.info/?probe=80707f8712) | Sep 16, 2023 |
| Techvision    | TVI7309X B0                 | [9a30d2d88c](https://bsd-hardware.info/?probe=9a30d2d88c) | Sep 16, 2023 |
| Unknown       | Unknown                     | [1808e7891c](https://bsd-hardware.info/?probe=1808e7891c) | Sep 16, 2023 |
| Unknown       | Unknown                     | [d6acb378a1](https://bsd-hardware.info/?probe=d6acb378a1) | Sep 15, 2023 |
| Unknown       | Unknown                     | [fe010506e6](https://bsd-hardware.info/?probe=fe010506e6) | Sep 15, 2023 |
| Dell          | 0NW6H5 A00                  | [227062e965](https://bsd-hardware.info/?probe=227062e965) | Sep 13, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [5c89a7a1f1](https://bsd-hardware.info/?probe=5c89a7a1f1) | Sep 13, 2023 |
| Unknown       | Unknown                     | [fd131bd648](https://bsd-hardware.info/?probe=fd131bd648) | Sep 11, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [0797783a1c](https://bsd-hardware.info/?probe=0797783a1c) | Sep 10, 2023 |
| Unknown       | Unknown                     | [3c85271913](https://bsd-hardware.info/?probe=3c85271913) | Sep 10, 2023 |
| Apple         | PowerMac3,6                 | [36daf7ce75](https://bsd-hardware.info/?probe=36daf7ce75) | Sep 09, 2023 |
| Unknown       | Unknown                     | [3bc1fc9c7b](https://bsd-hardware.info/?probe=3bc1fc9c7b) | Sep 09, 2023 |
| Unknown       | Unknown                     | [68a0e23945](https://bsd-hardware.info/?probe=68a0e23945) | Sep 09, 2023 |
| Techvision    | TVI7309X B0                 | [fe6bcbc332](https://bsd-hardware.info/?probe=fe6bcbc332) | Sep 08, 2023 |
| Techvision    | TVI7309X B0                 | [37e25cbcec](https://bsd-hardware.info/?probe=37e25cbcec) | Sep 08, 2023 |
| Lex           | Pineview-D                  | [351aabdb80](https://bsd-hardware.info/?probe=351aabdb80) | Sep 08, 2023 |
| PC Engines    | APU3                        | [ad38dcf54a](https://bsd-hardware.info/?probe=ad38dcf54a) | Sep 07, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | [451cfdf64f](https://bsd-hardware.info/?probe=451cfdf64f) | Sep 06, 2023 |
| Unknown       | Unknown                     | [6361addd62](https://bsd-hardware.info/?probe=6361addd62) | Sep 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [48ca84af37](https://bsd-hardware.info/?probe=48ca84af37) | Sep 06, 2023 |
| PC Engines    | APU2                        | [d582e62190](https://bsd-hardware.info/?probe=d582e62190) | Sep 06, 2023 |
| Unknown       | Unknown                     | [f757c58686](https://bsd-hardware.info/?probe=f757c58686) | Sep 05, 2023 |
| PC Engines    | APU2                        | [c9d2cfe6fa](https://bsd-hardware.info/?probe=c9d2cfe6fa) | Sep 03, 2023 |
| Unknown       | Unknown                     | [53cee3b3c8](https://bsd-hardware.info/?probe=53cee3b3c8) | Sep 03, 2023 |
| Biostar       | J4105NHU                    | [2ac770aa55](https://bsd-hardware.info/?probe=2ac770aa55) | Sep 03, 2023 |
| Inventec      | Z CLASS A02                 | [1f4bf47cab](https://bsd-hardware.info/?probe=1f4bf47cab) | Sep 01, 2023 |
| Unknown       | Unknown                     | [b59ce07b49](https://bsd-hardware.info/?probe=b59ce07b49) | Aug 30, 2023 |
| MW            | GMLK-2_5G4L                 | [56ac0149f8](https://bsd-hardware.info/?probe=56ac0149f8) | Aug 30, 2023 |
| CncTion       | N6000-4L B0                 | [81cbfbffca](https://bsd-hardware.info/?probe=81cbfbffca) | Aug 29, 2023 |
| Unknown       | Unknown                     | [fc384f5de7](https://bsd-hardware.info/?probe=fc384f5de7) | Aug 28, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | [a47cd8ee32](https://bsd-hardware.info/?probe=a47cd8ee32) | Aug 27, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [a684024d8e](https://bsd-hardware.info/?probe=a684024d8e) | Aug 27, 2023 |
| PC Engines    | APU                         | [3b29671556](https://bsd-hardware.info/?probe=3b29671556) | Aug 26, 2023 |
| Gigabyte      | X570S UD                    | [ed6162710b](https://bsd-hardware.info/?probe=ed6162710b) | Aug 26, 2023 |
| ASUSTek       | H110I-PLUS                  | [a487121854](https://bsd-hardware.info/?probe=a487121854) | Aug 26, 2023 |
| IGEL Techn... | D220                        | [a7686520e1](https://bsd-hardware.info/?probe=a7686520e1) | Aug 26, 2023 |
| Techvision    | TVI7309X B0                 | [662ce63a50](https://bsd-hardware.info/?probe=662ce63a50) | Aug 25, 2023 |
| MW            | GMLK-2_5G4L                 | [8c6f7098f9](https://bsd-hardware.info/?probe=8c6f7098f9) | Aug 25, 2023 |
| CncTion       | N6000-4L B0                 | [d8a9af2435](https://bsd-hardware.info/?probe=d8a9af2435) | Aug 24, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [a8fa821e5e](https://bsd-hardware.info/?probe=a8fa821e5e) | Aug 24, 2023 |
| Unknown       | Unknown                     | [74a7137090](https://bsd-hardware.info/?probe=74a7137090) | Aug 22, 2023 |
| ASRock        | A520M-ITX/ac                | [8622d78a7c](https://bsd-hardware.info/?probe=8622d78a7c) | Aug 22, 2023 |
| Gigabyte      | H610I DDR4                  | [f4310832c2](https://bsd-hardware.info/?probe=f4310832c2) | Aug 22, 2023 |
| Intel         | JSL MRD                     | [56165c654b](https://bsd-hardware.info/?probe=56165c654b) | Aug 22, 2023 |
| Unknown       | Unknown                     | [03da20b37e](https://bsd-hardware.info/?probe=03da20b37e) | Aug 22, 2023 |
| Unknown       | MANIFOLD 2-C                | [71e00307ae](https://bsd-hardware.info/?probe=71e00307ae) | Aug 22, 2023 |
| PC Engines    | APU2                        | [3e32acfdc4](https://bsd-hardware.info/?probe=3e32acfdc4) | Aug 22, 2023 |
| Gigabyte      | H110M-D2P-WG-CF             | [a91c61e3e3](https://bsd-hardware.info/?probe=a91c61e3e3) | Aug 21, 2023 |
| Intel         | Q3XXG4-P V1.0               | [ef28836f5c](https://bsd-hardware.info/?probe=ef28836f5c) | Aug 20, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [01d58784e6](https://bsd-hardware.info/?probe=01d58784e6) | Aug 20, 2023 |
| HP            | 8594                        | [b3e5652c1b](https://bsd-hardware.info/?probe=b3e5652c1b) | Aug 20, 2023 |
| HP            | 8594                        | [77d6ac3f77](https://bsd-hardware.info/?probe=77d6ac3f77) | Aug 20, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [b3625ada4b](https://bsd-hardware.info/?probe=b3625ada4b) | Aug 18, 2023 |
| Unknown       | Unknown                     | [de9a146c44](https://bsd-hardware.info/?probe=de9a146c44) | Aug 16, 2023 |
| Unknown       | Q2XX V1.0                   | [be1252b2ff](https://bsd-hardware.info/?probe=be1252b2ff) | Aug 16, 2023 |
| Unknown       | MANIFOLD 2-C                | [18559e2fde](https://bsd-hardware.info/?probe=18559e2fde) | Aug 15, 2023 |
| Unknown       | MANIFOLD 2-C                | [73c35b0a8a](https://bsd-hardware.info/?probe=73c35b0a8a) | Aug 15, 2023 |
| Intel         | SKYBAY                      | [77fbc82e41](https://bsd-hardware.info/?probe=77fbc82e41) | Aug 15, 2023 |
| Protectli     | VP4620                      | [0f0695d190](https://bsd-hardware.info/?probe=0f0695d190) | Aug 15, 2023 |
| PC Engines    | APU2                        | [bdd3050b5f](https://bsd-hardware.info/?probe=bdd3050b5f) | Aug 14, 2023 |
| CncTion       | N5105-4L B0                 | [6c4364fe15](https://bsd-hardware.info/?probe=6c4364fe15) | Aug 13, 2023 |
| PC Engines    | apu4                        | [24e025662c](https://bsd-hardware.info/?probe=24e025662c) | Aug 12, 2023 |
| CncTion       | J4125-4L-I225               | [983bbef1fb](https://bsd-hardware.info/?probe=983bbef1fb) | Aug 12, 2023 |
| WeiBu         | ADL-N Prod                  | [26bbe26e7c](https://bsd-hardware.info/?probe=26bbe26e7c) | Aug 12, 2023 |
| CncTion       | N5105-4L B0                 | [27f84c75b5](https://bsd-hardware.info/?probe=27f84c75b5) | Aug 11, 2023 |
| PC Engines    | APU2                        | [2e9106fc92](https://bsd-hardware.info/?probe=2e9106fc92) | Aug 11, 2023 |
| Gigabyte      | AX370M-DS3H-CF              | [7b00ddd0a1](https://bsd-hardware.info/?probe=7b00ddd0a1) | Aug 11, 2023 |
| PC Engines    | apu1                        | [0b3594d9a3](https://bsd-hardware.info/?probe=0b3594d9a3) | Aug 11, 2023 |
| PC Engines    | apu4                        | [b81f51408d](https://bsd-hardware.info/?probe=b81f51408d) | Aug 10, 2023 |
| PC Engines    | APU2                        | [be0e8bf959](https://bsd-hardware.info/?probe=be0e8bf959) | Aug 09, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [fac2fa5cbe](https://bsd-hardware.info/?probe=fac2fa5cbe) | Aug 08, 2023 |
| Acer          | Veriton N2620G              | [2acf1e4557](https://bsd-hardware.info/?probe=2acf1e4557) | Aug 08, 2023 |
| Techvision    | TVI7309X B0                 | [aeccb6e70c](https://bsd-hardware.info/?probe=aeccb6e70c) | Aug 07, 2023 |
| Lanner        | FW-7543 B-GA                | [dadf592128](https://bsd-hardware.info/?probe=dadf592128) | Aug 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [eceed9eb7a](https://bsd-hardware.info/?probe=eceed9eb7a) | Aug 05, 2023 |
| Unknown       | Unknown                     | [9c4dbcfd67](https://bsd-hardware.info/?probe=9c4dbcfd67) | Aug 05, 2023 |
| Lanner        | FW-7543 B-GA                | [6236e692de](https://bsd-hardware.info/?probe=6236e692de) | Aug 05, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [283fce4c68](https://bsd-hardware.info/?probe=283fce4c68) | Aug 05, 2023 |
| CWWK          | MINIPC-G12                  | [c449203453](https://bsd-hardware.info/?probe=c449203453) | Aug 04, 2023 |
| Lenovo        | SHARKBAY NO DPK             | [62ed2f59f6](https://bsd-hardware.info/?probe=62ed2f59f6) | Aug 04, 2023 |
| PC Engines    | APU2                        | [78c8ed6a89](https://bsd-hardware.info/?probe=78c8ed6a89) | Aug 03, 2023 |
| Shuttle       | DH610                       | [bbdd78fe4b](https://bsd-hardware.info/?probe=bbdd78fe4b) | Aug 01, 2023 |
| Unknown       | Unknown                     | [42c65b8b8b](https://bsd-hardware.info/?probe=42c65b8b8b) | Aug 01, 2023 |
| Hardkernel    | ODROID-H3                   | [aa708122cf](https://bsd-hardware.info/?probe=aa708122cf) | Aug 01, 2023 |
| Shuttle       | DH610                       | [e7c63c97d3](https://bsd-hardware.info/?probe=e7c63c97d3) | Aug 01, 2023 |
| Shuttle       | DH370                       | [a3ab1c6344](https://bsd-hardware.info/?probe=a3ab1c6344) | Jul 31, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [64137e0eec](https://bsd-hardware.info/?probe=64137e0eec) | Jul 29, 2023 |
| PC Engines    | APU2                        | [5eddd5369a](https://bsd-hardware.info/?probe=5eddd5369a) | Jul 28, 2023 |
| Hardkernel    | ODROID-H3                   | [0bb6b16689](https://bsd-hardware.info/?probe=0bb6b16689) | Jul 28, 2023 |
| Unknown       | Unknown                     | [1c6ab6b999](https://bsd-hardware.info/?probe=1c6ab6b999) | Jul 28, 2023 |
| PC Engines    | apu1                        | [8bc97daada](https://bsd-hardware.info/?probe=8bc97daada) | Jul 27, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [64b577cd8e](https://bsd-hardware.info/?probe=64b577cd8e) | Jul 27, 2023 |
| NF541         | 1.0                         | [ba959613a5](https://bsd-hardware.info/?probe=ba959613a5) | Jul 26, 2023 |
| Cisco         | ASA5525 A0                  | [f4409bdc8f](https://bsd-hardware.info/?probe=f4409bdc8f) | Jul 26, 2023 |
| Unknown       | Unknown                     | [f7728cee03](https://bsd-hardware.info/?probe=f7728cee03) | Jul 25, 2023 |
| Unknown       | MANIFOLD 2-C                | [8aa3f5491e](https://bsd-hardware.info/?probe=8aa3f5491e) | Jul 25, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [af215ad226](https://bsd-hardware.info/?probe=af215ad226) | Jul 24, 2023 |
| PC Engines    | apu4                        | [0aa9951131](https://bsd-hardware.info/?probe=0aa9951131) | Jul 24, 2023 |
| PC Engines    | apu4                        | [514dc1e9f9](https://bsd-hardware.info/?probe=514dc1e9f9) | Jul 24, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [dec2c34899](https://bsd-hardware.info/?probe=dec2c34899) | Jul 24, 2023 |
| Unknown       | Unknown                     | [aab49bd228](https://bsd-hardware.info/?probe=aab49bd228) | Jul 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [438424a9d9](https://bsd-hardware.info/?probe=438424a9d9) | Jul 23, 2023 |
| PC Engines    | apu4                        | [ea9a81b423](https://bsd-hardware.info/?probe=ea9a81b423) | Jul 23, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [3b16dab962](https://bsd-hardware.info/?probe=3b16dab962) | Jul 22, 2023 |
| Protectli     | FW6 Ver                     | [7e1b416d09](https://bsd-hardware.info/?probe=7e1b416d09) | Jul 21, 2023 |
| Yanling       | YL-CLU6L-V1                 | [489c685ec4](https://bsd-hardware.info/?probe=489c685ec4) | Jul 21, 2023 |
| AZW           | EQ                          | [9883a89b8d](https://bsd-hardware.info/?probe=9883a89b8d) | Jul 21, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [efe49f9e5d](https://bsd-hardware.info/?probe=efe49f9e5d) | Jul 20, 2023 |
| Unknown       | Unknown                     | [cce6d65dfb](https://bsd-hardware.info/?probe=cce6d65dfb) | Jul 20, 2023 |
| Unknown       | Unknown                     | [e487955dea](https://bsd-hardware.info/?probe=e487955dea) | Jul 18, 2023 |
| ASUSTek       | Maximus VIII HERO           | [35ab9e002d](https://bsd-hardware.info/?probe=35ab9e002d) | Jul 17, 2023 |
| Unknown       | Unknown                     | [8d82f25df2](https://bsd-hardware.info/?probe=8d82f25df2) | Jul 16, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [a2602b7fbf](https://bsd-hardware.info/?probe=a2602b7fbf) | Jul 16, 2023 |
| Gigabyte      | GB-BSi7-1165G7              | [c5f92a4c5e](https://bsd-hardware.info/?probe=c5f92a4c5e) | Jul 14, 2023 |
| MW            | GMLK-2_5G4L                 | [0b90f241cd](https://bsd-hardware.info/?probe=0b90f241cd) | Jul 13, 2023 |
| PICO PC       | JSL-4L                      | [d93e338744](https://bsd-hardware.info/?probe=d93e338744) | Jul 13, 2023 |
| Gigabyte      | B450M H                     | [c2cb1e21fa](https://bsd-hardware.info/?probe=c2cb1e21fa) | Jul 11, 2023 |
| ASRock        | A520M-ITX/ac                | [96bda9f774](https://bsd-hardware.info/?probe=96bda9f774) | Jul 11, 2023 |
| Unknown       | Unknown                     | [5625dd24f6](https://bsd-hardware.info/?probe=5625dd24f6) | Jul 11, 2023 |
| PICO PC       | JSL-4L                      | [d8c9a61dcf](https://bsd-hardware.info/?probe=d8c9a61dcf) | Jul 10, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [3a544928aa](https://bsd-hardware.info/?probe=3a544928aa) | Jul 09, 2023 |
| MiTAC         | PH13CMI                     | [6d0cd37fce](https://bsd-hardware.info/?probe=6d0cd37fce) | Jul 09, 2023 |
| Biostar       | A68N-2100K                  | [20cb208208](https://bsd-hardware.info/?probe=20cb208208) | Jul 09, 2023 |
| Lex           | Pineview-D                  | [290c53a822](https://bsd-hardware.info/?probe=290c53a822) | Jul 09, 2023 |
| Yanling       | YL-ELU3L                    | [0a3c74b25c](https://bsd-hardware.info/?probe=0a3c74b25c) | Jul 07, 2023 |
| ASRock        | A300M-STX                   | [5d896a607e](https://bsd-hardware.info/?probe=5d896a607e) | Jul 06, 2023 |
| Unknown       | Unknown                     | [3644875d54](https://bsd-hardware.info/?probe=3644875d54) | Jul 03, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [2053dbb697](https://bsd-hardware.info/?probe=2053dbb697) | Jul 03, 2023 |
| PC Engines    | apu4                        | [62f0b60653](https://bsd-hardware.info/?probe=62f0b60653) | Jun 30, 2023 |
| Dell          | 00V62H A01                  | [d60c967edb](https://bsd-hardware.info/?probe=d60c967edb) | Jun 29, 2023 |
| Unknown       | Unknown                     | [075deef24f](https://bsd-hardware.info/?probe=075deef24f) | Jun 28, 2023 |
| CncTion       | J4125-4L-I225               | [1785cb2fa3](https://bsd-hardware.info/?probe=1785cb2fa3) | Jun 28, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [bcad942162](https://bsd-hardware.info/?probe=bcad942162) | Jun 26, 2023 |
| Unknown       | YL-SKUL6                    | [1512f63972](https://bsd-hardware.info/?probe=1512f63972) | Jun 26, 2023 |
| Protectli     | FW6 Ver                     | [fa177a2538](https://bsd-hardware.info/?probe=fa177a2538) | Jun 26, 2023 |
| Protectli     | FW6 Ver                     | [54ef7dc131](https://bsd-hardware.info/?probe=54ef7dc131) | Jun 26, 2023 |
| Protectli     | FW6 Ver                     | [b056cd0426](https://bsd-hardware.info/?probe=b056cd0426) | Jun 26, 2023 |
| Unknown       | J3160-4L                    | [5ad411cd6b](https://bsd-hardware.info/?probe=5ad411cd6b) | Jun 25, 2023 |
| Hardkernel    | ODROID-H3                   | [8a2ea60929](https://bsd-hardware.info/?probe=8a2ea60929) | Jun 25, 2023 |
| Techvision    | TVI7309X B0                 | [18cf91f3a4](https://bsd-hardware.info/?probe=18cf91f3a4) | Jun 23, 2023 |
| Intel         | Q3XXG4-P V1.0               | [bb4dc2b1a2](https://bsd-hardware.info/?probe=bb4dc2b1a2) | Jun 23, 2023 |
| Unknown       | Unknown                     | [16ceade742](https://bsd-hardware.info/?probe=16ceade742) | Jun 23, 2023 |
| Unknown       | Unknown                     | [508aa0bdb4](https://bsd-hardware.info/?probe=508aa0bdb4) | Jun 23, 2023 |
| Yanling       | YL-KBRL2 Series Ver:1.02    | [9e8d6110f4](https://bsd-hardware.info/?probe=9e8d6110f4) | Jun 19, 2023 |
| LANCOM Sys... | UF-60                       | [96904b8bdd](https://bsd-hardware.info/?probe=96904b8bdd) | Jun 19, 2023 |
| Unknown       | Unknown                     | [5fc629699d](https://bsd-hardware.info/?probe=5fc629699d) | Jun 18, 2023 |
| ASRock        | Z97 Professional            | [c978ddda86](https://bsd-hardware.info/?probe=c978ddda86) | Jun 18, 2023 |
| AMD           | Kabini CRB                  | [b774a8b586](https://bsd-hardware.info/?probe=b774a8b586) | Jun 16, 2023 |
| CncTion       | N5105-4L B0                 | [b9c5b6ec05](https://bsd-hardware.info/?probe=b9c5b6ec05) | Jun 15, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | [70b0e8172d](https://bsd-hardware.info/?probe=70b0e8172d) | Jun 14, 2023 |
| PC Engines    | apu4                        | [ea036662ca](https://bsd-hardware.info/?probe=ea036662ca) | Jun 14, 2023 |
| Unknown       | J3160-4L                    | [4a6667249e](https://bsd-hardware.info/?probe=4a6667249e) | Jun 13, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [015a5d839a](https://bsd-hardware.info/?probe=015a5d839a) | Jun 13, 2023 |
| Unknown       | Unknown                     | [27617e1ca6](https://bsd-hardware.info/?probe=27617e1ca6) | Jun 13, 2023 |
| HP            | 3397                        | [a918ce0c4b](https://bsd-hardware.info/?probe=a918ce0c4b) | Jun 12, 2023 |
| CWWK          | MINIPC-G12                  | [04ae7435e5](https://bsd-hardware.info/?probe=04ae7435e5) | Jun 12, 2023 |
| MSI           | A320M GRENADE               | [6e0b1f598f](https://bsd-hardware.info/?probe=6e0b1f598f) | Jun 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [02509df772](https://bsd-hardware.info/?probe=02509df772) | Jun 12, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [2d2052de27](https://bsd-hardware.info/?probe=2d2052de27) | Jun 11, 2023 |
| Unknown       | Unknown                     | [8988baa83b](https://bsd-hardware.info/?probe=8988baa83b) | Jun 10, 2023 |
| Unknown       | Unknown                     | [40bb474319](https://bsd-hardware.info/?probe=40bb474319) | Jun 10, 2023 |
| ASRock        | B85M-HDS                    | [09a4700a14](https://bsd-hardware.info/?probe=09a4700a14) | Jun 09, 2023 |
| Wortmann      | terra Nettop 2700           | [e4a90ea530](https://bsd-hardware.info/?probe=e4a90ea530) | Jun 08, 2023 |
| Intel         | Q3XXG4-P V1.0               | [1ae49c4706](https://bsd-hardware.info/?probe=1ae49c4706) | Jun 08, 2023 |
| Intel         | SKYBAY                      | [f1b649ed11](https://bsd-hardware.info/?probe=f1b649ed11) | Jun 08, 2023 |
| Lanner        | FW-7543 B-GA                | [ee85efd1c0](https://bsd-hardware.info/?probe=ee85efd1c0) | Jun 08, 2023 |
| LANCOM Sys... | UF-60                       | [204f10b60f](https://bsd-hardware.info/?probe=204f10b60f) | Jun 07, 2023 |
| Intel         | Q3XXG4-P V1.0               | [4e57bbcdb5](https://bsd-hardware.info/?probe=4e57bbcdb5) | Jun 06, 2023 |
| Intel         | DENLOW_WS                   | [ce3bef7b5a](https://bsd-hardware.info/?probe=ce3bef7b5a) | Jun 06, 2023 |
| CncTion       | N6000-4L B0                 | [c9ec51aa84](https://bsd-hardware.info/?probe=c9ec51aa84) | Jun 05, 2023 |
| HP            | 3397                        | [6783902b93](https://bsd-hardware.info/?probe=6783902b93) | Jun 05, 2023 |
| Hardkernel    | ODROID-H3                   | [42e80f8003](https://bsd-hardware.info/?probe=42e80f8003) | Jun 05, 2023 |
| Dell          | 0PC5F7 A03                  | [23bd5ef252](https://bsd-hardware.info/?probe=23bd5ef252) | Jun 04, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [56a9981ff3](https://bsd-hardware.info/?probe=56a9981ff3) | Jun 03, 2023 |
| PC Engines    | APU2                        | [31c697459b](https://bsd-hardware.info/?probe=31c697459b) | Jun 02, 2023 |
| HP            | 3397                        | [1f8a9a4f27](https://bsd-hardware.info/?probe=1f8a9a4f27) | May 29, 2023 |
| ASRock        | H410M/ac                    | [d3e3d20cc4](https://bsd-hardware.info/?probe=d3e3d20cc4) | May 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | [2827d90215](https://bsd-hardware.info/?probe=2827d90215) | May 28, 2023 |
| HP            | 3397                        | [036d4e087c](https://bsd-hardware.info/?probe=036d4e087c) | May 27, 2023 |
| HP            | 3397                        | [19abd8768e](https://bsd-hardware.info/?probe=19abd8768e) | May 27, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [81775d5ca1](https://bsd-hardware.info/?probe=81775d5ca1) | May 26, 2023 |
| Nitrokey      | NitroWall                   | [1b3b451dee](https://bsd-hardware.info/?probe=1b3b451dee) | May 24, 2023 |
| Unknown       | Unknown                     | [4c7e1d476d](https://bsd-hardware.info/?probe=4c7e1d476d) | May 23, 2023 |
| Nitrokey      | NitroWall                   | [ef701f3991](https://bsd-hardware.info/?probe=ef701f3991) | May 23, 2023 |
| Unknown       | QD-WHLU01                   | [700bcad7cc](https://bsd-hardware.info/?probe=700bcad7cc) | May 22, 2023 |
| HP            | 158B                        | [1ef3762103](https://bsd-hardware.info/?probe=1ef3762103) | May 20, 2023 |
| HP            | 158B                        | [a9c63041a6](https://bsd-hardware.info/?probe=a9c63041a6) | May 20, 2023 |
| ZOTAC         | Unknown                     | [8156e3fede](https://bsd-hardware.info/?probe=8156e3fede) | May 19, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [612e3a21d4](https://bsd-hardware.info/?probe=612e3a21d4) | May 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [8f3c5de741](https://bsd-hardware.info/?probe=8f3c5de741) | May 19, 2023 |
| VIA Techno... | VT82C597                    | [d73db58e48](https://bsd-hardware.info/?probe=d73db58e48) | May 19, 2023 |
| ASUSTek       | PRO B460M-C                 | [9350bb37db](https://bsd-hardware.info/?probe=9350bb37db) | May 18, 2023 |
| Medion        | MS-7633                     | [c01f7b9894](https://bsd-hardware.info/?probe=c01f7b9894) | May 18, 2023 |
| Supermicro    | H8DM8-2                     | [68c51b6006](https://bsd-hardware.info/?probe=68c51b6006) | May 18, 2023 |
| CncTion       | N5105-4L-I226 B0            | [75f5674d44](https://bsd-hardware.info/?probe=75f5674d44) | May 18, 2023 |
| HP            | 3397                        | [d405f14bb9](https://bsd-hardware.info/?probe=d405f14bb9) | May 18, 2023 |
| Unknown       | Unknown                     | [fff8127c3f](https://bsd-hardware.info/?probe=fff8127c3f) | May 17, 2023 |
| Unknown       | Unknown                     | [cc27c738be](https://bsd-hardware.info/?probe=cc27c738be) | May 17, 2023 |
| PC Engines    | apu4                        | [7fe2bf9ad6](https://bsd-hardware.info/?probe=7fe2bf9ad6) | May 16, 2023 |
| PC Engines    | apu4                        | [7723fe0a0a](https://bsd-hardware.info/?probe=7723fe0a0a) | May 16, 2023 |
| ASUSTek       | H110I-PLUS                  | [37922a69a6](https://bsd-hardware.info/?probe=37922a69a6) | May 15, 2023 |
| Lenovo        | SHARKBAY NOK                | [2b4ece70c9](https://bsd-hardware.info/?probe=2b4ece70c9) | May 15, 2023 |
| ASRock        | AM1B-ITX                    | [8ad16a1805](https://bsd-hardware.info/?probe=8ad16a1805) | May 15, 2023 |
| PC Engines    | APU2                        | [62fef2616b](https://bsd-hardware.info/?probe=62fef2616b) | May 15, 2023 |
| MSI           | B85M-G43                    | [6d2160dcee](https://bsd-hardware.info/?probe=6d2160dcee) | May 14, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [7332aba586](https://bsd-hardware.info/?probe=7332aba586) | May 14, 2023 |
| Fujitsu       | D3823-A2 S26361-D3823-Ax... | [2528087de1](https://bsd-hardware.info/?probe=2528087de1) | May 11, 2023 |
| Unknown       | Unknown                     | [eee23dec87](https://bsd-hardware.info/?probe=eee23dec87) | May 11, 2023 |
| ASUSTek       | H110I-PLUS                  | [2543ed83b9](https://bsd-hardware.info/?probe=2543ed83b9) | May 10, 2023 |
| Fujitsu       | D3644-B1 S26361-D3644-B1    | [b2e52b5677](https://bsd-hardware.info/?probe=b2e52b5677) | May 10, 2023 |
| Techvision    | TVI7309X B0                 | [fbf3fde510](https://bsd-hardware.info/?probe=fbf3fde510) | May 09, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [96abd89bab](https://bsd-hardware.info/?probe=96abd89bab) | May 09, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [38243e0313](https://bsd-hardware.info/?probe=38243e0313) | May 09, 2023 |
| PC Engines    | APU2                        | [6aff35010a](https://bsd-hardware.info/?probe=6aff35010a) | May 08, 2023 |
| Hardkernel    | ODROID-H3                   | [5b669f261f](https://bsd-hardware.info/?probe=5b669f261f) | May 08, 2023 |
| Unknown       | T100                        | [fb9c6bff7b](https://bsd-hardware.info/?probe=fb9c6bff7b) | May 07, 2023 |
| Supermicro    | X12STN-C-WOHS               | [d8cf344aee](https://bsd-hardware.info/?probe=d8cf344aee) | May 06, 2023 |
| Unknown       | Unknown                     | [349e1709cd](https://bsd-hardware.info/?probe=349e1709cd) | May 06, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [c29d140ee6](https://bsd-hardware.info/?probe=c29d140ee6) | May 06, 2023 |
| Lanner        | FW-7543 B-GA                | [8346fdf608](https://bsd-hardware.info/?probe=8346fdf608) | May 03, 2023 |
| HP            | 1589                        | [4aee1909c8](https://bsd-hardware.info/?probe=4aee1909c8) | May 03, 2023 |
| ASRock        | A520M-ITX/ac                | [70b09db335](https://bsd-hardware.info/?probe=70b09db335) | May 02, 2023 |
| ASRock        | A520M-ITX/ac                | [eb61af55d5](https://bsd-hardware.info/?probe=eb61af55d5) | May 01, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [8227d6d32c](https://bsd-hardware.info/?probe=8227d6d32c) | Apr 30, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [f86a94eb66](https://bsd-hardware.info/?probe=f86a94eb66) | Apr 30, 2023 |
| Protectli     | VP2420                      | [4ea8453453](https://bsd-hardware.info/?probe=4ea8453453) | Apr 30, 2023 |
| Protectli     | VP2420                      | [46a00b21d9](https://bsd-hardware.info/?probe=46a00b21d9) | Apr 30, 2023 |
| Protectli     | FW4B                        | [048da71e18](https://bsd-hardware.info/?probe=048da71e18) | Apr 29, 2023 |
| PC Engines    | apu1                        | [1a37e9d978](https://bsd-hardware.info/?probe=1a37e9d978) | Apr 27, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [989f3b44bf](https://bsd-hardware.info/?probe=989f3b44bf) | Apr 26, 2023 |
| Supermicro    | X11SDW-8C-TP13F             | [94316d20c8](https://bsd-hardware.info/?probe=94316d20c8) | Apr 26, 2023 |
| MiTAC         | PH13CMI                     | [5d3e954049](https://bsd-hardware.info/?probe=5d3e954049) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [0c8a0100c5](https://bsd-hardware.info/?probe=0c8a0100c5) | Apr 23, 2023 |
| Techvision    | TVI7309X B0                 | [ad73cda832](https://bsd-hardware.info/?probe=ad73cda832) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [775424cbff](https://bsd-hardware.info/?probe=775424cbff) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [c26c1111c6](https://bsd-hardware.info/?probe=c26c1111c6) | Apr 21, 2023 |
| Techvision    | TVI7309X B0                 | [215364d870](https://bsd-hardware.info/?probe=215364d870) | Apr 21, 2023 |
| Techvision    | TVI7309X B0                 | [fdbbde509c](https://bsd-hardware.info/?probe=fdbbde509c) | Apr 20, 2023 |
| PC Engines    | APU2                        | [59b3a3eebf](https://bsd-hardware.info/?probe=59b3a3eebf) | Apr 19, 2023 |
| ASUSTek       | Pro B560M-C                 | [b341a9c9c9](https://bsd-hardware.info/?probe=b341a9c9c9) | Apr 19, 2023 |
| Unknown       | Unknown                     | [311e89be7a](https://bsd-hardware.info/?probe=311e89be7a) | Apr 18, 2023 |
| CncTion       | J4125-4L-I225               | [b4fd4e35b2](https://bsd-hardware.info/?probe=b4fd4e35b2) | Apr 18, 2023 |
| Supermicro    | X11SDW-8C-TP13F             | [20fac0b7a5](https://bsd-hardware.info/?probe=20fac0b7a5) | Apr 18, 2023 |
| Unknown       | Unknown                     | [f5153e1b18](https://bsd-hardware.info/?probe=f5153e1b18) | Apr 17, 2023 |
| CncTion       | N5105-4L B0                 | [6de7890035](https://bsd-hardware.info/?probe=6de7890035) | Apr 17, 2023 |
| Unknown       | Unknown                     | [56505e8956](https://bsd-hardware.info/?probe=56505e8956) | Apr 16, 2023 |
| Intel         | Q3XXG4-P V1.0               | [4fbc5291d9](https://bsd-hardware.info/?probe=4fbc5291d9) | Apr 16, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [a29966f9ee](https://bsd-hardware.info/?probe=a29966f9ee) | Apr 16, 2023 |
| Unknown       | Unknown                     | [94151c41f1](https://bsd-hardware.info/?probe=94151c41f1) | Apr 14, 2023 |
| Unknown       | YL-SKUL6-7 Series           | [627e7a86c6](https://bsd-hardware.info/?probe=627e7a86c6) | Apr 13, 2023 |
| CncTion       | N5105-4L-I226 B0            | [0c7855ee11](https://bsd-hardware.info/?probe=0c7855ee11) | Apr 13, 2023 |
| Advantech     | UNO-2271G_V2                | [23e4b8d9b1](https://bsd-hardware.info/?probe=23e4b8d9b1) | Apr 12, 2023 |
| ASUSTek       | P10S-M Series               | [0b060edc48](https://bsd-hardware.info/?probe=0b060edc48) | Apr 12, 2023 |
| MW            | GMLK-2_5G4L                 | [9b1dbe0b9a](https://bsd-hardware.info/?probe=9b1dbe0b9a) | Apr 11, 2023 |
| Unknown       | Unknown                     | [cfa755bf6d](https://bsd-hardware.info/?probe=cfa755bf6d) | Apr 11, 2023 |
| CncTion       | N5105-4L-I226 B0            | [65d80d8aeb](https://bsd-hardware.info/?probe=65d80d8aeb) | Apr 09, 2023 |
| Gigabyte      | H610I DDR4                  | [59d65282c3](https://bsd-hardware.info/?probe=59d65282c3) | Apr 08, 2023 |
| ASRock        | A520M-ITX/ac                | [7a0ca560df](https://bsd-hardware.info/?probe=7a0ca560df) | Apr 08, 2023 |
| Unknown       | MANIFOLD 2-C                | [8fb3cbee23](https://bsd-hardware.info/?probe=8fb3cbee23) | Apr 07, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [f1cabdb067](https://bsd-hardware.info/?probe=f1cabdb067) | Apr 06, 2023 |
| Dell          | 04Y8V0 A02                  | [b4dab62ac2](https://bsd-hardware.info/?probe=b4dab62ac2) | Apr 05, 2023 |
| Dell          | 04Y8V0 A02                  | [24d7b97629](https://bsd-hardware.info/?probe=24d7b97629) | Apr 05, 2023 |
| Lanner        | FW-8771 C-GA                | [90d7028263](https://bsd-hardware.info/?probe=90d7028263) | Apr 05, 2023 |
| PC Engines    | apu4                        | [e91a75d782](https://bsd-hardware.info/?probe=e91a75d782) | Apr 05, 2023 |
| Intel         | SKYBAY                      | [81655c4fd5](https://bsd-hardware.info/?probe=81655c4fd5) | Apr 05, 2023 |
| maiyunda      | www.maiyunda.com            | [7cf52a3977](https://bsd-hardware.info/?probe=7cf52a3977) | Apr 03, 2023 |
| Techvision    | TVI7309X B0                 | [ca1360b939](https://bsd-hardware.info/?probe=ca1360b939) | Apr 03, 2023 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [bea5641594](https://bsd-hardware.info/?probe=bea5641594) | Apr 02, 2023 |
| MSI           | B450M MORTAR MAX            | [01bf5e8678](https://bsd-hardware.info/?probe=01bf5e8678) | Apr 02, 2023 |
| Gigabyte      | H55M-S2H                    | [60c66c5066](https://bsd-hardware.info/?probe=60c66c5066) | Mar 30, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [bde9fd671b](https://bsd-hardware.info/?probe=bde9fd671b) | Mar 30, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [a160027cc2](https://bsd-hardware.info/?probe=a160027cc2) | Mar 30, 2023 |
| Dell          | 0VG93V A00                  | [1f3e086401](https://bsd-hardware.info/?probe=1f3e086401) | Mar 30, 2023 |
| Intel         | JSL MRD                     | [07adf23a3d](https://bsd-hardware.info/?probe=07adf23a3d) | Mar 28, 2023 |
| CncTion       | N5105-4L B0                 | [b6fd7cd6ae](https://bsd-hardware.info/?probe=b6fd7cd6ae) | Mar 27, 2023 |
| Shuttle       | FS81                        | [b80626e045](https://bsd-hardware.info/?probe=b80626e045) | Mar 26, 2023 |
| Lanner        | FW-7543 B-GA                | [3ed4cfc9c8](https://bsd-hardware.info/?probe=3ed4cfc9c8) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [15e452d25d](https://bsd-hardware.info/?probe=15e452d25d) | Mar 26, 2023 |
| Intel         | Q3XXG4-P V1.0               | [2f16e29f78](https://bsd-hardware.info/?probe=2f16e29f78) | Mar 26, 2023 |
| Protectli     | FW4B Ver                    | [fc5ab682fc](https://bsd-hardware.info/?probe=fc5ab682fc) | Mar 26, 2023 |
| Protectli     | FW4B Ver                    | [5082d62025](https://bsd-hardware.info/?probe=5082d62025) | Mar 25, 2023 |
| MW            | GMLK-2_5G4L                 | [41fa3f51d3](https://bsd-hardware.info/?probe=41fa3f51d3) | Mar 25, 2023 |
| Unknown       | Unknown                     | [387c27f1d7](https://bsd-hardware.info/?probe=387c27f1d7) | Mar 25, 2023 |
| PC Engines    | APU2                        | [4e4a81e456](https://bsd-hardware.info/?probe=4e4a81e456) | Mar 24, 2023 |
| Lex           | Pineview-D                  | [ca2fbb614d](https://bsd-hardware.info/?probe=ca2fbb614d) | Mar 24, 2023 |
| CncTion       | N5105-4L B0                 | [9561c72b9c](https://bsd-hardware.info/?probe=9561c72b9c) | Mar 24, 2023 |
| Intel         | Q3XXG4-P V1.0               | [083d2e65da](https://bsd-hardware.info/?probe=083d2e65da) | Mar 24, 2023 |
| ASRock        | A520M-ITX/ac                | [18877701a6](https://bsd-hardware.info/?probe=18877701a6) | Mar 24, 2023 |
| Protectli     | VP2420                      | [f07553b02c](https://bsd-hardware.info/?probe=f07553b02c) | Mar 23, 2023 |
| Protectli     | VP2420                      | [dfad78899e](https://bsd-hardware.info/?probe=dfad78899e) | Mar 23, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | [720f15a1ce](https://bsd-hardware.info/?probe=720f15a1ce) | Mar 23, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [491c0ca78a](https://bsd-hardware.info/?probe=491c0ca78a) | Mar 22, 2023 |
| Intel         | Q3XXG4-P V1.0               | [680002292e](https://bsd-hardware.info/?probe=680002292e) | Mar 22, 2023 |
| MW            | GMLK-2_5G4L                 | [b3f0879ebf](https://bsd-hardware.info/?probe=b3f0879ebf) | Mar 22, 2023 |
| Intel         | SKYBAY                      | [83ea0b27b1](https://bsd-hardware.info/?probe=83ea0b27b1) | Mar 21, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [bcada44b09](https://bsd-hardware.info/?probe=bcada44b09) | Mar 21, 2023 |
| Supermicro    | X11SDV-8C-TP8F              | [7ae004c035](https://bsd-hardware.info/?probe=7ae004c035) | Mar 21, 2023 |
| Unknown       | Unknown                     | [e4365dfa60](https://bsd-hardware.info/?probe=e4365dfa60) | Mar 20, 2023 |
| ASRock        | B550M Pro4                  | [4dc54510d2](https://bsd-hardware.info/?probe=4dc54510d2) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | [cab50cddd5](https://bsd-hardware.info/?probe=cab50cddd5) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | [ff4dda40eb](https://bsd-hardware.info/?probe=ff4dda40eb) | Mar 19, 2023 |
| Intel         | SKYBAY                      | [7bd7f393b1](https://bsd-hardware.info/?probe=7bd7f393b1) | Mar 18, 2023 |
| Intel         | SKYBAY                      | [a8f1d29e24](https://bsd-hardware.info/?probe=a8f1d29e24) | Mar 18, 2023 |
| MSI           | X299 PRO                    | [a26d096ecb](https://bsd-hardware.info/?probe=a26d096ecb) | Mar 18, 2023 |
| Fujitsu       | D3313-S3 S26361-D3313-S3    | [1bf34a929a](https://bsd-hardware.info/?probe=1bf34a929a) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2ceda5b586](https://bsd-hardware.info/?probe=2ceda5b586) | Mar 17, 2023 |
| ASRock        | J5040-ITX                   | [435dc7ee7b](https://bsd-hardware.info/?probe=435dc7ee7b) | Mar 15, 2023 |
| Unknown       | Unknown                     | [68b45d5083](https://bsd-hardware.info/?probe=68b45d5083) | Mar 15, 2023 |
| ASRock        | A520M-ITX/ac                | [1ccc8081fd](https://bsd-hardware.info/?probe=1ccc8081fd) | Mar 15, 2023 |
| Foxconn       | H61M/H61M-S                 | [865fbff42a](https://bsd-hardware.info/?probe=865fbff42a) | Mar 14, 2023 |
| ASRock        | Q1900M                      | [9570525d52](https://bsd-hardware.info/?probe=9570525d52) | Mar 14, 2023 |
| MW            | GMLK-2_5G4L                 | [5211185a2a](https://bsd-hardware.info/?probe=5211185a2a) | Mar 14, 2023 |
| HP            | 8056                        | [e1d2423153](https://bsd-hardware.info/?probe=e1d2423153) | Mar 13, 2023 |
| HP            | 8056                        | [d89b45ea6d](https://bsd-hardware.info/?probe=d89b45ea6d) | Mar 13, 2023 |
| Dell          | 0W0CHX A00                  | [85a9fddd44](https://bsd-hardware.info/?probe=85a9fddd44) | Mar 12, 2023 |
| MW            | GMLK-2_5G4L                 | [fee0ff7804](https://bsd-hardware.info/?probe=fee0ff7804) | Mar 12, 2023 |
| Acer          | Veriton N2620G              | [fa57448331](https://bsd-hardware.info/?probe=fa57448331) | Mar 12, 2023 |
| ASUSTek       | P8Z68-V                     | [3d8ef63e18](https://bsd-hardware.info/?probe=3d8ef63e18) | Mar 11, 2023 |
| ASUSTek       | H110I-PLUS                  | [8736b12c9a](https://bsd-hardware.info/?probe=8736b12c9a) | Mar 11, 2023 |
| MSI           | X299 PRO                    | [0cebc094ca](https://bsd-hardware.info/?probe=0cebc094ca) | Mar 10, 2023 |
| Unknown       | Unknown                     | [2a55137e71](https://bsd-hardware.info/?probe=2a55137e71) | Mar 10, 2023 |
| CheckPoint    | PH-30-00                    | [ec7a5f05fd](https://bsd-hardware.info/?probe=ec7a5f05fd) | Mar 09, 2023 |
| Unknown       | Unknown                     | [d7b171d0bb](https://bsd-hardware.info/?probe=d7b171d0bb) | Mar 09, 2023 |
| Protectli     | VP2420                      | [21d2214da6](https://bsd-hardware.info/?probe=21d2214da6) | Mar 08, 2023 |
| Unknown       | Unknown                     | [86c132c242](https://bsd-hardware.info/?probe=86c132c242) | Mar 07, 2023 |
| MW            | GMLK-2_5G4L                 | [b91b7cf52d](https://bsd-hardware.info/?probe=b91b7cf52d) | Mar 06, 2023 |
| Techvision    | TVI7309X B0                 | [789ae683f7](https://bsd-hardware.info/?probe=789ae683f7) | Mar 05, 2023 |
| ASUSTek       | PRO B460M-C                 | [a3f77b82cc](https://bsd-hardware.info/?probe=a3f77b82cc) | Mar 05, 2023 |
| Dell          | VEP-4600-V910 0PDG1JA02     | [5070c11c54](https://bsd-hardware.info/?probe=5070c11c54) | Mar 05, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [3d912f92aa](https://bsd-hardware.info/?probe=3d912f92aa) | Mar 05, 2023 |
| ASRock        | E350M1                      | [461f8cca23](https://bsd-hardware.info/?probe=461f8cca23) | Mar 04, 2023 |
| Techvision    | TVI7309X B0                 | [6067b3f58d](https://bsd-hardware.info/?probe=6067b3f58d) | Mar 03, 2023 |
| Techvision    | TVI7309X B0                 | [bbbd05a4c3](https://bsd-hardware.info/?probe=bbbd05a4c3) | Mar 03, 2023 |
| Techvision    | TVI7309X B0                 | [9ab07ae7f1](https://bsd-hardware.info/?probe=9ab07ae7f1) | Mar 03, 2023 |
| Techvision    | TVI7309X B0                 | [228816d44e](https://bsd-hardware.info/?probe=228816d44e) | Mar 03, 2023 |
| Unknown       | Unknown                     | [81bf3cf726](https://bsd-hardware.info/?probe=81bf3cf726) | Mar 03, 2023 |
| Intel         | DENLOW_WS                   | [2b70fdb96a](https://bsd-hardware.info/?probe=2b70fdb96a) | Mar 02, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [29290b1b9c](https://bsd-hardware.info/?probe=29290b1b9c) | Mar 01, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [5eb87a21db](https://bsd-hardware.info/?probe=5eb87a21db) | Mar 01, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [39d5f658ce](https://bsd-hardware.info/?probe=39d5f658ce) | Feb 28, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [dcf3f03ddc](https://bsd-hardware.info/?probe=dcf3f03ddc) | Feb 28, 2023 |
| Supermicro    | PDSBM                       | [1dea83dd64](https://bsd-hardware.info/?probe=1dea83dd64) | Feb 26, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [27e756f63d](https://bsd-hardware.info/?probe=27e756f63d) | Feb 26, 2023 |
| Foxconn       | 2A8Ch                       | [96a8673b26](https://bsd-hardware.info/?probe=96a8673b26) | Feb 26, 2023 |
| NF541         | 1.0                         | [863e6235d4](https://bsd-hardware.info/?probe=863e6235d4) | Feb 26, 2023 |
| Unknown       | YL-J3160L4                  | [b774e80761](https://bsd-hardware.info/?probe=b774e80761) | Feb 25, 2023 |
| ASRock        | X470 Gaming K4              | [fbff29a62a](https://bsd-hardware.info/?probe=fbff29a62a) | Feb 25, 2023 |
| Unknown       | Unknown                     | [87ad08a144](https://bsd-hardware.info/?probe=87ad08a144) | Feb 25, 2023 |
| Lenovo        | ThinkCentre M91p 7033A2G    | [25528a00f3](https://bsd-hardware.info/?probe=25528a00f3) | Feb 24, 2023 |
| MSI           | X299 PRO                    | [3ca12f88d9](https://bsd-hardware.info/?probe=3ca12f88d9) | Feb 24, 2023 |
| Unknown       | Unknown                     | [efab6dedba](https://bsd-hardware.info/?probe=efab6dedba) | Feb 24, 2023 |
| Protectli     | VP2420                      | [ac2228fa2b](https://bsd-hardware.info/?probe=ac2228fa2b) | Feb 24, 2023 |
| Dell          | 0C27VV A02                  | [5899533edd](https://bsd-hardware.info/?probe=5899533edd) | Feb 23, 2023 |
| Fujitsu       | D3543-A2 S26361-D3543-A2... | [68165a639f](https://bsd-hardware.info/?probe=68165a639f) | Feb 22, 2023 |
| PC Engines    | APU2                        | [05966fb4dc](https://bsd-hardware.info/?probe=05966fb4dc) | Feb 22, 2023 |
| Protectli     | VP2420                      | [541c13b778](https://bsd-hardware.info/?probe=541c13b778) | Feb 22, 2023 |
| Dell          | 0C27VV A02                  | [a10df954b7](https://bsd-hardware.info/?probe=a10df954b7) | Feb 22, 2023 |
| Intel         | QHSW02                      | [6bec4024a8](https://bsd-hardware.info/?probe=6bec4024a8) | Feb 22, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | [3f78b1a6c7](https://bsd-hardware.info/?probe=3f78b1a6c7) | Feb 20, 2023 |
| Protectli     | VP2420                      | [5d8285d184](https://bsd-hardware.info/?probe=5d8285d184) | Feb 19, 2023 |
| CncTion       | J4125-4L-I225               | [6d2c693305](https://bsd-hardware.info/?probe=6d2c693305) | Feb 19, 2023 |
| Yanling       | YL-CLU6L-V1                 | [8d1fa6606b](https://bsd-hardware.info/?probe=8d1fa6606b) | Feb 19, 2023 |
| Unknown       | Unknown                     | [1478bc453d](https://bsd-hardware.info/?probe=1478bc453d) | Feb 17, 2023 |
| Unknown       | Unknown                     | [ac4b0186ff](https://bsd-hardware.info/?probe=ac4b0186ff) | Feb 17, 2023 |
| ZOTAC         | Unknown                     | [0adf0ca671](https://bsd-hardware.info/?probe=0adf0ca671) | Feb 17, 2023 |
| ASUSTek       | N3050M-E                    | [7d6e696fb4](https://bsd-hardware.info/?probe=7d6e696fb4) | Feb 17, 2023 |
| Unknown       | Unknown                     | [71cc084a9c](https://bsd-hardware.info/?probe=71cc084a9c) | Feb 16, 2023 |
| PC Engines    | APU                         | [1162545537](https://bsd-hardware.info/?probe=1162545537) | Feb 15, 2023 |
| ASUSTek       | PRIME A320M-K               | [35aa7d7f04](https://bsd-hardware.info/?probe=35aa7d7f04) | Feb 15, 2023 |
| Supermicro    | X7SPA-HF                    | [6a91635684](https://bsd-hardware.info/?probe=6a91635684) | Feb 14, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [a9d6421d3c](https://bsd-hardware.info/?probe=a9d6421d3c) | Feb 14, 2023 |
| Yanling       | YL-CLU6L-V1                 | [9c12ee263f](https://bsd-hardware.info/?probe=9c12ee263f) | Feb 14, 2023 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | [d69aba5432](https://bsd-hardware.info/?probe=d69aba5432) | Feb 14, 2023 |
| Unknown       | Unknown                     | [98819b1db5](https://bsd-hardware.info/?probe=98819b1db5) | Feb 13, 2023 |
| Unknown       | Unknown                     | [dbe1c51575](https://bsd-hardware.info/?probe=dbe1c51575) | Feb 12, 2023 |
| ASUSTek       | P8Z68-V                     | [74ebc950e2](https://bsd-hardware.info/?probe=74ebc950e2) | Feb 11, 2023 |
| Yanling       | YL-KBR6L Ver:1.00           | [516c778d65](https://bsd-hardware.info/?probe=516c778d65) | Feb 11, 2023 |
| Foxconn       | 2A8Ch                       | [2874f7a7fa](https://bsd-hardware.info/?probe=2874f7a7fa) | Feb 11, 2023 |
| Gigabyte      | Z490 VISION G               | [6f8ad1a8b9](https://bsd-hardware.info/?probe=6f8ad1a8b9) | Feb 11, 2023 |
| Techvision    | TVI7309X B0                 | [c4c07aec07](https://bsd-hardware.info/?probe=c4c07aec07) | Feb 11, 2023 |
| Unknown       | Unknown                     | [18362d0f11](https://bsd-hardware.info/?probe=18362d0f11) | Feb 10, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [12e4e26e40](https://bsd-hardware.info/?probe=12e4e26e40) | Feb 10, 2023 |
| Foxconn       | 2A8Ch                       | [84c0208f8d](https://bsd-hardware.info/?probe=84c0208f8d) | Feb 10, 2023 |
| ASUSTek       | P7P55D DELUXE               | [dd9685a909](https://bsd-hardware.info/?probe=dd9685a909) | Feb 09, 2023 |
| ASUSTek       | H110I-PLUS                  | [4347c8c716](https://bsd-hardware.info/?probe=4347c8c716) | Feb 09, 2023 |
| ASRock        | A520M-ITX/ac                | [e5b2e1bb9d](https://bsd-hardware.info/?probe=e5b2e1bb9d) | Feb 09, 2023 |
| ASRock        | A520M-ITX/ac                | [f66883c5c2](https://bsd-hardware.info/?probe=f66883c5c2) | Feb 09, 2023 |
| ASUSTek       | P10S-M Series               | [78975e45b7](https://bsd-hardware.info/?probe=78975e45b7) | Feb 09, 2023 |
| Unknown       | MANIFOLD 2-C                | [1a23b05eca](https://bsd-hardware.info/?probe=1a23b05eca) | Feb 07, 2023 |
| Unknown       | Unknown                     | [f4978c3575](https://bsd-hardware.info/?probe=f4978c3575) | Feb 07, 2023 |
| ASUSTek       | P10S-M Series               | [24b74b8ce3](https://bsd-hardware.info/?probe=24b74b8ce3) | Feb 07, 2023 |
| MW            | GMLK-2_5G4L                 | [39fa7db109](https://bsd-hardware.info/?probe=39fa7db109) | Feb 07, 2023 |
| Unknown       | MANIFOLD 2-C                | [923b6d85fd](https://bsd-hardware.info/?probe=923b6d85fd) | Feb 06, 2023 |
| PC Engines    | APU2                        | [e4e00e259c](https://bsd-hardware.info/?probe=e4e00e259c) | Feb 06, 2023 |
| ASUSTek       | P8Z77-M                     | [627bdfafb7](https://bsd-hardware.info/?probe=627bdfafb7) | Feb 06, 2023 |
| MSI           | B450M MORTAR MAX            | [ec37957aed](https://bsd-hardware.info/?probe=ec37957aed) | Feb 05, 2023 |
| Intel         | QHSW02                      | [16722b7429](https://bsd-hardware.info/?probe=16722b7429) | Feb 04, 2023 |
| Unknown       | Unknown                     | [8fdace282e](https://bsd-hardware.info/?probe=8fdace282e) | Feb 04, 2023 |
| ASUSTek       | P10S-M Series               | [c6fc0a639d](https://bsd-hardware.info/?probe=c6fc0a639d) | Feb 03, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [77c7c36f87](https://bsd-hardware.info/?probe=77c7c36f87) | Feb 03, 2023 |
| Unknown       | Unknown                     | [433e29e7bd](https://bsd-hardware.info/?probe=433e29e7bd) | Feb 01, 2023 |
| Supermicro    | X7SPA-HF                    | [2d410c6882](https://bsd-hardware.info/?probe=2d410c6882) | Feb 01, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [9fa25e53f1](https://bsd-hardware.info/?probe=9fa25e53f1) | Feb 01, 2023 |
| PC Engines    | apu4                        | [0d1561fea9](https://bsd-hardware.info/?probe=0d1561fea9) | Jan 31, 2023 |
| Intel         | Q3XXG4-P V1.0               | [418694e14d](https://bsd-hardware.info/?probe=418694e14d) | Jan 31, 2023 |
| Lanner        | FW-7543 B-GA                | [149345d14c](https://bsd-hardware.info/?probe=149345d14c) | Jan 30, 2023 |
| HP            | 1825                        | [717279c19f](https://bsd-hardware.info/?probe=717279c19f) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [4c25e80924](https://bsd-hardware.info/?probe=4c25e80924) | Jan 29, 2023 |
| Shenzhen M... | F4BHD                       | [b2540f3beb](https://bsd-hardware.info/?probe=b2540f3beb) | Jan 29, 2023 |
| HP            | 21B4 A01                    | [8df824afd4](https://bsd-hardware.info/?probe=8df824afd4) | Jan 28, 2023 |
| Gigabyte      | B550 AORUS PRO              | [8fd7f80256](https://bsd-hardware.info/?probe=8fd7f80256) | Jan 28, 2023 |
| ASUSTek       | M4A89TD PRO USB3            | [1328d01296](https://bsd-hardware.info/?probe=1328d01296) | Jan 28, 2023 |
| Techvision    | TVI7309X B0                 | [937a255571](https://bsd-hardware.info/?probe=937a255571) | Jan 28, 2023 |
| CncTion       | N5105-4L B0                 | [a7fe868f42](https://bsd-hardware.info/?probe=a7fe868f42) | Jan 27, 2023 |
| Unknown       | Unknown                     | [d3750005c2](https://bsd-hardware.info/?probe=d3750005c2) | Jan 27, 2023 |
| ASUSTek       | PRIME X570-P                | [232a81d2ed](https://bsd-hardware.info/?probe=232a81d2ed) | Jan 27, 2023 |
| ASRock        | H570M-ITX/ac                | [4ebeac2699](https://bsd-hardware.info/?probe=4ebeac2699) | Jan 26, 2023 |
| PC Engines    | APU2                        | [436e596f40](https://bsd-hardware.info/?probe=436e596f40) | Jan 26, 2023 |
| ASUSTek       | PRIME A320M-K               | [cdad2f0001](https://bsd-hardware.info/?probe=cdad2f0001) | Jan 23, 2023 |
| AWOW          | AK50                        | [8c983f91e4](https://bsd-hardware.info/?probe=8c983f91e4) | Jan 22, 2023 |
| PC Engines    | APU2                        | [658569ae16](https://bsd-hardware.info/?probe=658569ae16) | Jan 22, 2023 |
| HP            | 1825                        | [2705218636](https://bsd-hardware.info/?probe=2705218636) | Jan 21, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [59c83cb9ee](https://bsd-hardware.info/?probe=59c83cb9ee) | Jan 21, 2023 |
| Fujitsu       | D3243-S1 S26361-D3243-S1    | [d69c3cae4c](https://bsd-hardware.info/?probe=d69c3cae4c) | Jan 21, 2023 |
| ASRock        | A520M-ITX/ac                | [e6873fe42f](https://bsd-hardware.info/?probe=e6873fe42f) | Jan 21, 2023 |
| Techvision    | TVI7309X B0                 | [495563926c](https://bsd-hardware.info/?probe=495563926c) | Jan 21, 2023 |
| ASRock        | A520M-ITX/ac                | [f862df1689](https://bsd-hardware.info/?probe=f862df1689) | Jan 20, 2023 |
| Techvision    | TVI7309X B0                 | [d4018ae0f3](https://bsd-hardware.info/?probe=d4018ae0f3) | Jan 20, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | [4bcc8752f4](https://bsd-hardware.info/?probe=4bcc8752f4) | Jan 20, 2023 |
| ShenZhen M... | MW-NANO-APL-4L              | [48206a7d4a](https://bsd-hardware.info/?probe=48206a7d4a) | Jan 19, 2023 |
| Unknown       | Unknown                     | [35e269ef1c](https://bsd-hardware.info/?probe=35e269ef1c) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [b528c0bbe3](https://bsd-hardware.info/?probe=b528c0bbe3) | Jan 18, 2023 |
| BESSTAR Te... | TH50                        | [b9de543167](https://bsd-hardware.info/?probe=b9de543167) | Jan 18, 2023 |
| CncTion       | N5105-4L B0                 | [11948a0ab1](https://bsd-hardware.info/?probe=11948a0ab1) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | [f7de27b0ca](https://bsd-hardware.info/?probe=f7de27b0ca) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | [9eee9cc526](https://bsd-hardware.info/?probe=9eee9cc526) | Jan 18, 2023 |
| CncTion       | N5105-4L B0                 | [46178567ff](https://bsd-hardware.info/?probe=46178567ff) | Jan 18, 2023 |
| Wortmann      | terra MiniPC                | [be22193265](https://bsd-hardware.info/?probe=be22193265) | Jan 17, 2023 |
| MSI           | MS-9897                     | [8aa91d17fa](https://bsd-hardware.info/?probe=8aa91d17fa) | Jan 17, 2023 |
| MSI           | MS-9897                     | [0ccc361bd9](https://bsd-hardware.info/?probe=0ccc361bd9) | Jan 17, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [1ef7026e21](https://bsd-hardware.info/?probe=1ef7026e21) | Jan 15, 2023 |
| Techvision    | TVI7309X B0                 | [8aebf3b22a](https://bsd-hardware.info/?probe=8aebf3b22a) | Jan 15, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [17d73c4d40](https://bsd-hardware.info/?probe=17d73c4d40) | Jan 14, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [ad7329411a](https://bsd-hardware.info/?probe=ad7329411a) | Jan 14, 2023 |
| Unknown       | Unknown                     | [fba3e00878](https://bsd-hardware.info/?probe=fba3e00878) | Jan 13, 2023 |
| HP            | 82A1                        | [567894a0bb](https://bsd-hardware.info/?probe=567894a0bb) | Jan 12, 2023 |
| PC Engines    | APU3                        | [b080710198](https://bsd-hardware.info/?probe=b080710198) | Jan 12, 2023 |
| ASRockRack    | X470D4U2/1N1                | [07f15d0014](https://bsd-hardware.info/?probe=07f15d0014) | Jan 11, 2023 |
| CncTion       | J4125-4L-I225               | [56a5c0de6e](https://bsd-hardware.info/?probe=56a5c0de6e) | Jan 11, 2023 |
| PC Engines    | APU2                        | [1e65573dfa](https://bsd-hardware.info/?probe=1e65573dfa) | Jan 10, 2023 |
| Unknown       | Unknown                     | [e870cfc473](https://bsd-hardware.info/?probe=e870cfc473) | Jan 10, 2023 |
| MW            | GMLK-2_5G4L                 | [55bd6297fa](https://bsd-hardware.info/?probe=55bd6297fa) | Jan 10, 2023 |
| MSI           | X299 PRO                    | [a1f37f69d9](https://bsd-hardware.info/?probe=a1f37f69d9) | Jan 08, 2023 |
| Dell          | 0YNVJG A01                  | [8bb9472e6b](https://bsd-hardware.info/?probe=8bb9472e6b) | Jan 08, 2023 |
| Unknown       | Unknown                     | [7b5333020a](https://bsd-hardware.info/?probe=7b5333020a) | Jan 08, 2023 |
| Unknown       | Unknown                     | [1e3ebde983](https://bsd-hardware.info/?probe=1e3ebde983) | Jan 07, 2023 |
| ASUSTek       | F2A85-M                     | [e25da8b10a](https://bsd-hardware.info/?probe=e25da8b10a) | Jan 06, 2023 |
| ASUSTek       | PRIME X470-PRO              | [fa12ea67eb](https://bsd-hardware.info/?probe=fa12ea67eb) | Jan 06, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | [92c2e73bd4](https://bsd-hardware.info/?probe=92c2e73bd4) | Jan 06, 2023 |
| Unknown       | Unknown                     | [cc8588d977](https://bsd-hardware.info/?probe=cc8588d977) | Jan 05, 2023 |
| MW            | GMLK-2_5G4L                 | [39149acdbd](https://bsd-hardware.info/?probe=39149acdbd) | Jan 04, 2023 |
| Unknown       | J3160-4L                    | [849af12174](https://bsd-hardware.info/?probe=849af12174) | Jan 02, 2023 |
| CncTion       | N5105-4L B0                 | [70b1ca485d](https://bsd-hardware.info/?probe=70b1ca485d) | Jan 02, 2023 |
| ASRock        | E350M1                      | [6a7e5c8d0c](https://bsd-hardware.info/?probe=6a7e5c8d0c) | Jan 01, 2023 |
| HP            | 1825                        | [f7e94decd0](https://bsd-hardware.info/?probe=f7e94decd0) | Dec 31, 2022 |
| HP            | 1825                        | [afc1259508](https://bsd-hardware.info/?probe=afc1259508) | Dec 31, 2022 |
| CncTion       | N5105-4L B0                 | [cd3e4f7122](https://bsd-hardware.info/?probe=cd3e4f7122) | Dec 30, 2022 |
| Protectli     | FW4B                        | [406fe72c22](https://bsd-hardware.info/?probe=406fe72c22) | Dec 30, 2022 |
| PC Engines    | APU2                        | [7aaf2d91ba](https://bsd-hardware.info/?probe=7aaf2d91ba) | Dec 29, 2022 |
| Lanner        | FW-7543 B-GA                | [6c145361a3](https://bsd-hardware.info/?probe=6c145361a3) | Dec 29, 2022 |
| Unknown       | Unknown                     | [5b8ad02694](https://bsd-hardware.info/?probe=5b8ad02694) | Dec 28, 2022 |
| Unknown       | Unknown                     | [c3b95220d7](https://bsd-hardware.info/?probe=c3b95220d7) | Dec 28, 2022 |
| ASUSTek       | H97-PLUS                    | [f2a248dcfe](https://bsd-hardware.info/?probe=f2a248dcfe) | Dec 26, 2022 |
| HP            | 8062                        | [f4d3eb024d](https://bsd-hardware.info/?probe=f4d3eb024d) | Dec 25, 2022 |
| Biostar       | A10N-8800E                  | [d3d1107f77](https://bsd-hardware.info/?probe=d3d1107f77) | Dec 23, 2022 |
| Intel         | Q3XXG4-P V1.0               | [58b47341c9](https://bsd-hardware.info/?probe=58b47341c9) | Dec 23, 2022 |
| ASRock        | B75M R2.0                   | [3a8d5c61b6](https://bsd-hardware.info/?probe=3a8d5c61b6) | Dec 23, 2022 |
| Unknown       | QD-WHLU01                   | [a0fb185069](https://bsd-hardware.info/?probe=a0fb185069) | Dec 23, 2022 |
| Unknown       | MANIFOLD 2-C                | [bc2c536004](https://bsd-hardware.info/?probe=bc2c536004) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | [daaad6a386](https://bsd-hardware.info/?probe=daaad6a386) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | [67bc182d1d](https://bsd-hardware.info/?probe=67bc182d1d) | Dec 23, 2022 |
| CncTion       | N5105-4L B0                 | [78bcccda01](https://bsd-hardware.info/?probe=78bcccda01) | Dec 22, 2022 |
| ASRock        | A75M-HVS                    | [01d8e43ee1](https://bsd-hardware.info/?probe=01d8e43ee1) | Dec 22, 2022 |
| AAEON         | FWS-2251 V1.0               | [a4ff0a7ec5](https://bsd-hardware.info/?probe=a4ff0a7ec5) | Dec 22, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [2ac107df0f](https://bsd-hardware.info/?probe=2ac107df0f) | Dec 22, 2022 |
| Dell          | 0WR7PY A02                  | [0c3fea5eb0](https://bsd-hardware.info/?probe=0c3fea5eb0) | Dec 22, 2022 |
| ASRock        | 4X4-4000 Series             | [009ef73bd1](https://bsd-hardware.info/?probe=009ef73bd1) | Dec 20, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [2ea413db31](https://bsd-hardware.info/?probe=2ea413db31) | Dec 20, 2022 |
| HP            | ProLiant MicroServer Gen... | [8de4ff8626](https://bsd-hardware.info/?probe=8de4ff8626) | Dec 20, 2022 |
| Unknown       | Unknown                     | [5d37a0669c](https://bsd-hardware.info/?probe=5d37a0669c) | Dec 19, 2022 |
| Dell          | 0WR7PY A02                  | [67baacfc7d](https://bsd-hardware.info/?probe=67baacfc7d) | Dec 19, 2022 |
| ASUSTek       | H97-PLUS                    | [c9de65beeb](https://bsd-hardware.info/?probe=c9de65beeb) | Dec 19, 2022 |
| PC Engines    | APU2                        | [5de84cb508](https://bsd-hardware.info/?probe=5de84cb508) | Dec 19, 2022 |
| Gigabyte      | J3455N-D3H                  | [fc7928dfe9](https://bsd-hardware.info/?probe=fc7928dfe9) | Dec 18, 2022 |
| MSI           | X299 PRO                    | [beec8001a1](https://bsd-hardware.info/?probe=beec8001a1) | Dec 17, 2022 |
| Intel         | CRESCENTBAY                 | [7981529337](https://bsd-hardware.info/?probe=7981529337) | Dec 17, 2022 |
| ASRock        | Q2900M                      | [42a53e5201](https://bsd-hardware.info/?probe=42a53e5201) | Dec 16, 2022 |
| ASRock        | A75M-HVS                    | [fa8c102cfd](https://bsd-hardware.info/?probe=fa8c102cfd) | Dec 16, 2022 |
| ASUSTek       | PRIME X470-PRO              | [3faaaa8209](https://bsd-hardware.info/?probe=3faaaa8209) | Dec 16, 2022 |
| Unknown       | Unknown                     | [01e26ec145](https://bsd-hardware.info/?probe=01e26ec145) | Dec 15, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [40911b66e2](https://bsd-hardware.info/?probe=40911b66e2) | Dec 15, 2022 |
| Unknown       | Unknown                     | [e3508ce360](https://bsd-hardware.info/?probe=e3508ce360) | Dec 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [35ecaf0406](https://bsd-hardware.info/?probe=35ecaf0406) | Dec 15, 2022 |
| Unknown       | Unknown                     | [210418cc84](https://bsd-hardware.info/?probe=210418cc84) | Dec 15, 2022 |
| MW            | GMLK-2_5G4L                 | [cb16bb9431](https://bsd-hardware.info/?probe=cb16bb9431) | Dec 14, 2022 |
| NF541         | 1.0                         | [b0644bada6](https://bsd-hardware.info/?probe=b0644bada6) | Dec 14, 2022 |
| Unknown       | Unknown                     | [ec6827e543](https://bsd-hardware.info/?probe=ec6827e543) | Dec 13, 2022 |
| Techvision    | TVI7309X B0                 | [af9df0d2c9](https://bsd-hardware.info/?probe=af9df0d2c9) | Dec 13, 2022 |
| Unknown       | Unknown                     | [9ee8d1082b](https://bsd-hardware.info/?probe=9ee8d1082b) | Dec 12, 2022 |
| Shuttle       | DH370                       | [1b938aa1a4](https://bsd-hardware.info/?probe=1b938aa1a4) | Dec 12, 2022 |
| Unknown       | MANIFOLD 2-C                | [ba191bd994](https://bsd-hardware.info/?probe=ba191bd994) | Dec 12, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [3124aaaf95](https://bsd-hardware.info/?probe=3124aaaf95) | Dec 11, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [b1bd01549a](https://bsd-hardware.info/?probe=b1bd01549a) | Dec 11, 2022 |
| Unknown       | Unknown                     | [def65f518e](https://bsd-hardware.info/?probe=def65f518e) | Dec 10, 2022 |
| MSI           | B450M MORTAR MAX            | [d8d6af9e56](https://bsd-hardware.info/?probe=d8d6af9e56) | Dec 10, 2022 |
| Protectli     | FW4B Ver                    | [33395e819a](https://bsd-hardware.info/?probe=33395e819a) | Dec 10, 2022 |
| Hardkernel    | ODROID-H3                   | [cd6aa62212](https://bsd-hardware.info/?probe=cd6aa62212) | Dec 09, 2022 |
| Unknown       | Unknown                     | [493df1f529](https://bsd-hardware.info/?probe=493df1f529) | Dec 09, 2022 |
| PC Engines    | apu4                        | [3e3ab7f196](https://bsd-hardware.info/?probe=3e3ab7f196) | Dec 09, 2022 |
| MW            | GMLK-2_5G4L                 | [84f8198c18](https://bsd-hardware.info/?probe=84f8198c18) | Dec 08, 2022 |
| Dell          | 0G261D A00                  | [24b9490c77](https://bsd-hardware.info/?probe=24b9490c77) | Dec 06, 2022 |
| Protectli     | FW4B Ver                    | [eaa3b9783e](https://bsd-hardware.info/?probe=eaa3b9783e) | Dec 05, 2022 |
| PC Engines    | apu4                        | [72061eb254](https://bsd-hardware.info/?probe=72061eb254) | Dec 05, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [aa9482884f](https://bsd-hardware.info/?probe=aa9482884f) | Dec 05, 2022 |
| Shuttle       | FS77U                       | [4172b79cfc](https://bsd-hardware.info/?probe=4172b79cfc) | Dec 04, 2022 |
| Unknown       | Unknown                     | [af4f0984ae](https://bsd-hardware.info/?probe=af4f0984ae) | Dec 04, 2022 |
| ASUSTek       | E35M1-I DELUXE              | [1a183385c7](https://bsd-hardware.info/?probe=1a183385c7) | Dec 04, 2022 |
| Unknown       | Unknown                     | [d9113585f0](https://bsd-hardware.info/?probe=d9113585f0) | Dec 04, 2022 |
| Intel         | D33217CK G76541-300         | [545a39b1e4](https://bsd-hardware.info/?probe=545a39b1e4) | Dec 02, 2022 |
| Intel         | D33217CK G76541-300         | [bbdd9a1b98](https://bsd-hardware.info/?probe=bbdd9a1b98) | Nov 30, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [ae55a799e8](https://bsd-hardware.info/?probe=ae55a799e8) | Nov 28, 2022 |
| PC Engines    | apu6                        | [13dcbe5748](https://bsd-hardware.info/?probe=13dcbe5748) | Nov 27, 2022 |
| Unknown       | Unknown                     | [d4246caa0f](https://bsd-hardware.info/?probe=d4246caa0f) | Nov 24, 2022 |
| MW            | GMLK-2_5G4L                 | [b6bbaa13e8](https://bsd-hardware.info/?probe=b6bbaa13e8) | Nov 24, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [1860d18e39](https://bsd-hardware.info/?probe=1860d18e39) | Nov 23, 2022 |
| PC Engines    | apu6                        | [bc334caa03](https://bsd-hardware.info/?probe=bc334caa03) | Nov 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d893e02d90](https://bsd-hardware.info/?probe=d893e02d90) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [7518e4f06a](https://bsd-hardware.info/?probe=7518e4f06a) | Nov 21, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [298fde4e33](https://bsd-hardware.info/?probe=298fde4e33) | Nov 21, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [f6491f1950](https://bsd-hardware.info/?probe=f6491f1950) | Nov 20, 2022 |
| Dell          | 0YNVJG A01                  | [15d32e1e36](https://bsd-hardware.info/?probe=15d32e1e36) | Nov 20, 2022 |
| PC Engines    | apu6                        | [1e9acc3ae6](https://bsd-hardware.info/?probe=1e9acc3ae6) | Nov 18, 2022 |
| Fujitsu       | D3289-A1 S26361-D3289-A1... | [dae7027898](https://bsd-hardware.info/?probe=dae7027898) | Nov 18, 2022 |
| ASRock        | N3150M                      | [d3b3be7936](https://bsd-hardware.info/?probe=d3b3be7936) | Nov 17, 2022 |
| ASUSTek       | H110I-PLUS                  | [f1f56fe86c](https://bsd-hardware.info/?probe=f1f56fe86c) | Nov 17, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [64d8291a91](https://bsd-hardware.info/?probe=64d8291a91) | Nov 17, 2022 |
| PC Engines    | apu4                        | [212f27d85a](https://bsd-hardware.info/?probe=212f27d85a) | Nov 17, 2022 |
| MSI           | X299 PRO                    | [d615157be7](https://bsd-hardware.info/?probe=d615157be7) | Nov 16, 2022 |
| ASRock        | J5040-ITX                   | [753c68cfb9](https://bsd-hardware.info/?probe=753c68cfb9) | Nov 16, 2022 |
| MSI           | B450M MORTAR MAX            | [15657b37e2](https://bsd-hardware.info/?probe=15657b37e2) | Nov 15, 2022 |
| MSI           | B450M MORTAR MAX            | [f4a8c42773](https://bsd-hardware.info/?probe=f4a8c42773) | Nov 15, 2022 |
| PC Engines    | apu4                        | [589dec199e](https://bsd-hardware.info/?probe=589dec199e) | Nov 15, 2022 |
| Shuttle       | FH61V                       | [012a5c0fcc](https://bsd-hardware.info/?probe=012a5c0fcc) | Nov 14, 2022 |
| ASUSTek       | H110I-PLUS                  | [0079838512](https://bsd-hardware.info/?probe=0079838512) | Nov 13, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [ee16ad1ffb](https://bsd-hardware.info/?probe=ee16ad1ffb) | Nov 12, 2022 |
| PC Engines    | APU2                        | [34960ed27c](https://bsd-hardware.info/?probe=34960ed27c) | Nov 12, 2022 |
| ASUSTek       | H110I-PLUS                  | [e3161d12c5](https://bsd-hardware.info/?probe=e3161d12c5) | Nov 11, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [0fcbc68304](https://bsd-hardware.info/?probe=0fcbc68304) | Nov 11, 2022 |
| HP            | 18E9                        | [b9df70f7eb](https://bsd-hardware.info/?probe=b9df70f7eb) | Nov 11, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [569d5b0cca](https://bsd-hardware.info/?probe=569d5b0cca) | Nov 10, 2022 |
| CheckPoint    | PH-30-00                    | [e42768cd01](https://bsd-hardware.info/?probe=e42768cd01) | Nov 10, 2022 |
| HP            | 21B4 A01                    | [c064c50fea](https://bsd-hardware.info/?probe=c064c50fea) | Nov 09, 2022 |
| HP            | 21B4 A01                    | [e5c599dfab](https://bsd-hardware.info/?probe=e5c599dfab) | Nov 09, 2022 |
| HP            | 21B4 A01                    | [0a3ba5478b](https://bsd-hardware.info/?probe=0a3ba5478b) | Nov 09, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [c32a7b407d](https://bsd-hardware.info/?probe=c32a7b407d) | Nov 09, 2022 |
| ASRock        | H570M-ITX/ac                | [8addd09aa7](https://bsd-hardware.info/?probe=8addd09aa7) | Nov 09, 2022 |
| HP            | 1632                        | [96d60382b7](https://bsd-hardware.info/?probe=96d60382b7) | Nov 09, 2022 |
| Dell          | 0G261D A00                  | [c3eb1a6caf](https://bsd-hardware.info/?probe=c3eb1a6caf) | Nov 08, 2022 |
| HP            | ProLiant ML310e Gen8        | [cb5bb2c3b5](https://bsd-hardware.info/?probe=cb5bb2c3b5) | Nov 07, 2022 |
| ASUSTek       | A88XM-E                     | [fde1fa45b8](https://bsd-hardware.info/?probe=fde1fa45b8) | Nov 07, 2022 |
| Unknown       | Unknown                     | [659ec0b365](https://bsd-hardware.info/?probe=659ec0b365) | Nov 07, 2022 |
| PC Engines    | APU2                        | [2a913e7a43](https://bsd-hardware.info/?probe=2a913e7a43) | Nov 06, 2022 |
| Protectli     | VP2410                      | [de5de1ca21](https://bsd-hardware.info/?probe=de5de1ca21) | Nov 06, 2022 |
| ASUSTek       | PRIME B560M-A               | [95d5580fd7](https://bsd-hardware.info/?probe=95d5580fd7) | Nov 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d27fd3b1a7](https://bsd-hardware.info/?probe=d27fd3b1a7) | Nov 04, 2022 |
| MW            | GMLK-2_5G4L                 | [73230496b2](https://bsd-hardware.info/?probe=73230496b2) | Nov 04, 2022 |
| Unknown       | 1.0                         | [9fe6ac4e68](https://bsd-hardware.info/?probe=9fe6ac4e68) | Nov 03, 2022 |
| Hardkernel    | ODROID-H2                   | [f0e3f3177a](https://bsd-hardware.info/?probe=f0e3f3177a) | Nov 02, 2022 |
| Protectli     | FW6 Ver                     | [6f21c02bba](https://bsd-hardware.info/?probe=6f21c02bba) | Oct 31, 2022 |
| Unknown       | Unknown                     | [9737a80a1c](https://bsd-hardware.info/?probe=9737a80a1c) | Oct 31, 2022 |
| Protectli     | FW6 Ver                     | [a52d7dda08](https://bsd-hardware.info/?probe=a52d7dda08) | Oct 30, 2022 |
| Protectli     | FW6 Ver                     | [4aecc55dcc](https://bsd-hardware.info/?probe=4aecc55dcc) | Oct 30, 2022 |
| Thomas-Kre... | LES network 6L              | [0816f2da97](https://bsd-hardware.info/?probe=0816f2da97) | Oct 30, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [85be4177d6](https://bsd-hardware.info/?probe=85be4177d6) | Oct 29, 2022 |
| Unknown       | Unknown                     | [c483de83a9](https://bsd-hardware.info/?probe=c483de83a9) | Oct 28, 2022 |
| Unknown       | Unknown                     | [c03e63a0a8](https://bsd-hardware.info/?probe=c03e63a0a8) | Oct 28, 2022 |
| ASUSTek       | P5BV-M                      | [c5277ae3cd](https://bsd-hardware.info/?probe=c5277ae3cd) | Oct 27, 2022 |
| CncTion       | N5105-4L B0                 | [d2adcc8230](https://bsd-hardware.info/?probe=d2adcc8230) | Oct 26, 2022 |
| PC Engines    | apu1                        | [b8643f364d](https://bsd-hardware.info/?probe=b8643f364d) | Oct 25, 2022 |
| Gigabyte      | B450M DS3H-CF               | [51ec4ce710](https://bsd-hardware.info/?probe=51ec4ce710) | Oct 24, 2022 |
| ASUSTek       | P5BV-M                      | [f7bfa3deed](https://bsd-hardware.info/?probe=f7bfa3deed) | Oct 23, 2022 |
| CncTion       | N5105-4L B0                 | [6f0d5a7497](https://bsd-hardware.info/?probe=6f0d5a7497) | Oct 23, 2022 |
| CncTion       | N5105-4L B0                 | [d7829c8f35](https://bsd-hardware.info/?probe=d7829c8f35) | Oct 22, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [a1b0ef3b39](https://bsd-hardware.info/?probe=a1b0ef3b39) | Oct 22, 2022 |
| Unknown       | Unknown                     | [410283dd4f](https://bsd-hardware.info/?probe=410283dd4f) | Oct 22, 2022 |
| Protectli     | FW6 Ver                     | [d04ef8c45b](https://bsd-hardware.info/?probe=d04ef8c45b) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [7ecffc1ca3](https://bsd-hardware.info/?probe=7ecffc1ca3) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [eb6eda641d](https://bsd-hardware.info/?probe=eb6eda641d) | Oct 20, 2022 |
| Hardkernel    | ODROID-H3                   | [304db9bbbf](https://bsd-hardware.info/?probe=304db9bbbf) | Oct 20, 2022 |
| PC Engines    | APU2                        | [c2e7b76bdf](https://bsd-hardware.info/?probe=c2e7b76bdf) | Oct 20, 2022 |
| PC Engines    | APU2                        | [ade8432e80](https://bsd-hardware.info/?probe=ade8432e80) | Oct 20, 2022 |
| Protectli     | FW6                         | [a7dabc97b0](https://bsd-hardware.info/?probe=a7dabc97b0) | Oct 19, 2022 |
| Protectli     | FW4B                        | [0acd6e1143](https://bsd-hardware.info/?probe=0acd6e1143) | Oct 19, 2022 |
| Unknown       | MANIFOLD 2-C                | [a6c8096599](https://bsd-hardware.info/?probe=a6c8096599) | Oct 19, 2022 |
| Lenovo        | 30D0 NOK                    | [d1fab8bd54](https://bsd-hardware.info/?probe=d1fab8bd54) | Oct 18, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [c7971db0b8](https://bsd-hardware.info/?probe=c7971db0b8) | Oct 18, 2022 |
| NF541         | 1.0                         | [6f4f72398d](https://bsd-hardware.info/?probe=6f4f72398d) | Oct 17, 2022 |
| Unknown       | Unknown                     | [83ceb2fb33](https://bsd-hardware.info/?probe=83ceb2fb33) | Oct 15, 2022 |
| PC Engines    | apu4                        | [cefbafec73](https://bsd-hardware.info/?probe=cefbafec73) | Oct 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [a8bdbe4d1b](https://bsd-hardware.info/?probe=a8bdbe4d1b) | Oct 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | [5a56504b92](https://bsd-hardware.info/?probe=5a56504b92) | Oct 15, 2022 |
| Dell          | 0WMJ54 A01                  | [5acdcd628d](https://bsd-hardware.info/?probe=5acdcd628d) | Oct 14, 2022 |
| PC Engines    | APU2                        | [0e09ac984a](https://bsd-hardware.info/?probe=0e09ac984a) | Oct 14, 2022 |
| PC Engines    | APU2                        | [a06a344954](https://bsd-hardware.info/?probe=a06a344954) | Oct 12, 2022 |
| ASUSTek       | P8Z68-V                     | [6674bbf7f3](https://bsd-hardware.info/?probe=6674bbf7f3) | Oct 11, 2022 |
| maiyunda      | www.maiyunda.com            | [869687f6f0](https://bsd-hardware.info/?probe=869687f6f0) | Oct 11, 2022 |
| maiyunda      | www.maiyunda.com            | [f4b5bf9026](https://bsd-hardware.info/?probe=f4b5bf9026) | Oct 11, 2022 |
| CncTion       | Jasper-4L B0                | [53c643dc95](https://bsd-hardware.info/?probe=53c643dc95) | Oct 10, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | [5d929362ca](https://bsd-hardware.info/?probe=5d929362ca) | Oct 09, 2022 |
| Hardkernel    | ODROID-H2                   | [73c9bfe38b](https://bsd-hardware.info/?probe=73c9bfe38b) | Oct 09, 2022 |
| Unknown       | Unknown                     | [d6396a74dd](https://bsd-hardware.info/?probe=d6396a74dd) | Oct 08, 2022 |
| Unknown       | Unknown                     | [d25832111e](https://bsd-hardware.info/?probe=d25832111e) | Oct 07, 2022 |
| Unknown       | Unknown                     | [a34c1b8ccd](https://bsd-hardware.info/?probe=a34c1b8ccd) | Oct 07, 2022 |
| Unknown       | Unknown                     | [7658e5e20d](https://bsd-hardware.info/?probe=7658e5e20d) | Oct 06, 2022 |
| PC Engines    | APU2                        | [02416f3157](https://bsd-hardware.info/?probe=02416f3157) | Oct 06, 2022 |
| CncTion       | J4125-4L-I225               | [eb746dc4a1](https://bsd-hardware.info/?probe=eb746dc4a1) | Oct 05, 2022 |
| ASRock        | Z77 Extreme4                | [459c674b3b](https://bsd-hardware.info/?probe=459c674b3b) | Oct 04, 2022 |
| Protectli     | FW4B                        | [36c62d7ffe](https://bsd-hardware.info/?probe=36c62d7ffe) | Oct 03, 2022 |
| Unknown       | Unknown                     | [dac9b93a46](https://bsd-hardware.info/?probe=dac9b93a46) | Oct 03, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [bb4a59dd43](https://bsd-hardware.info/?probe=bb4a59dd43) | Oct 03, 2022 |
| Protectli     | FW6 Ver                     | [23450789e4](https://bsd-hardware.info/?probe=23450789e4) | Oct 01, 2022 |
| AMI           | PICO PC                     | [ab45092607](https://bsd-hardware.info/?probe=ab45092607) | Oct 01, 2022 |
| Unknown       | Unknown                     | [c4e771c07c](https://bsd-hardware.info/?probe=c4e771c07c) | Oct 01, 2022 |
| BESSTAR Te... | IB9                         | [0cb7bacc88](https://bsd-hardware.info/?probe=0cb7bacc88) | Oct 01, 2022 |
| BESSTAR Te... | IB9                         | [eb0e449150](https://bsd-hardware.info/?probe=eb0e449150) | Sep 29, 2022 |
| AMI           | MNHO-048                    | [2ec6e55a75](https://bsd-hardware.info/?probe=2ec6e55a75) | Sep 28, 2022 |
| ASRock        | Z97 Professional            | [8936497eed](https://bsd-hardware.info/?probe=8936497eed) | Sep 27, 2022 |
| MSI           | A520M-A PRO                 | [7e75a1888b](https://bsd-hardware.info/?probe=7e75a1888b) | Sep 27, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [a605b4582c](https://bsd-hardware.info/?probe=a605b4582c) | Sep 27, 2022 |
| CncTion       | Jasper-4L B0                | [2998faa879](https://bsd-hardware.info/?probe=2998faa879) | Sep 25, 2022 |
| Pegatron      | H81-X1                      | [a27c76c490](https://bsd-hardware.info/?probe=a27c76c490) | Sep 25, 2022 |
| Supermicro    | X7DB8                       | [6ebc173873](https://bsd-hardware.info/?probe=6ebc173873) | Sep 25, 2022 |
| Deciso        | Netboard A10 V2.1           | [8bbf714f6d](https://bsd-hardware.info/?probe=8bbf714f6d) | Sep 25, 2022 |
| Deciso        | Netboard A10 V2.1           | [60d4585ece](https://bsd-hardware.info/?probe=60d4585ece) | Sep 25, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [6e2d053e1c](https://bsd-hardware.info/?probe=6e2d053e1c) | Sep 25, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [8ed018c141](https://bsd-hardware.info/?probe=8ed018c141) | Sep 24, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [a0672c6af1](https://bsd-hardware.info/?probe=a0672c6af1) | Sep 23, 2022 |
| Protectli     | FW4B Ver                    | [036004bbfe](https://bsd-hardware.info/?probe=036004bbfe) | Sep 22, 2022 |
| PC Engines    | APU                         | [a65b17ba04](https://bsd-hardware.info/?probe=a65b17ba04) | Sep 21, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [3c74fc1690](https://bsd-hardware.info/?probe=3c74fc1690) | Sep 20, 2022 |
| Gigabyte      | Z590I AORUS ULTRA           | [c057b7ab09](https://bsd-hardware.info/?probe=c057b7ab09) | Sep 20, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [393da0c00c](https://bsd-hardware.info/?probe=393da0c00c) | Sep 19, 2022 |
| ASUSTek       | PRIME X570-P                | [a2f56848a9](https://bsd-hardware.info/?probe=a2f56848a9) | Sep 19, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [cad2b5fd02](https://bsd-hardware.info/?probe=cad2b5fd02) | Sep 18, 2022 |
| BESSTAR Te... | TH50                        | [d027a503a5](https://bsd-hardware.info/?probe=d027a503a5) | Sep 18, 2022 |
| Unknown       | Unknown                     | [af8f180c2c](https://bsd-hardware.info/?probe=af8f180c2c) | Sep 17, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [a9da12dec0](https://bsd-hardware.info/?probe=a9da12dec0) | Sep 17, 2022 |
| ASUSTek       | PRIME X570-P                | [9fc1f66fcc](https://bsd-hardware.info/?probe=9fc1f66fcc) | Sep 16, 2022 |
| Fujitsu       | D3544-A1 S26361-D3544-A1... | [eb09d789de](https://bsd-hardware.info/?probe=eb09d789de) | Sep 16, 2022 |
| Unknown       | Unknown                     | [3b66741f97](https://bsd-hardware.info/?probe=3b66741f97) | Sep 16, 2022 |
| Unknown       | Unknown                     | [83e48aa232](https://bsd-hardware.info/?probe=83e48aa232) | Sep 16, 2022 |
| Intel         | ChiefRiver                  | [5361453e6a](https://bsd-hardware.info/?probe=5361453e6a) | Sep 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | [e8848edf41](https://bsd-hardware.info/?probe=e8848edf41) | Sep 13, 2022 |
| HP            | 18E7                        | [f09635a7ee](https://bsd-hardware.info/?probe=f09635a7ee) | Sep 12, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [2b4e2212dc](https://bsd-hardware.info/?probe=2b4e2212dc) | Sep 12, 2022 |
| BESSTAR Te... | TH50                        | [71e53af7f9](https://bsd-hardware.info/?probe=71e53af7f9) | Sep 12, 2022 |
| Unknown       | Unknown                     | [37588a8565](https://bsd-hardware.info/?probe=37588a8565) | Sep 11, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [836927cf63](https://bsd-hardware.info/?probe=836927cf63) | Sep 10, 2022 |
| ASUSTek       | PRIME X570-P                | [8eb8bf52d4](https://bsd-hardware.info/?probe=8eb8bf52d4) | Sep 10, 2022 |
| ASRock        | H81M-DGS                    | [3c2b784001](https://bsd-hardware.info/?probe=3c2b784001) | Sep 09, 2022 |
| ASRock        | H81M-DGS                    | [581219cbc5](https://bsd-hardware.info/?probe=581219cbc5) | Sep 09, 2022 |
| ASRockRack    | X470D4U2/1N1                | [f91afdb2f3](https://bsd-hardware.info/?probe=f91afdb2f3) | Sep 09, 2022 |
| ASRockRack    | X470D4U2/1N1                | [b0965df7e1](https://bsd-hardware.info/?probe=b0965df7e1) | Sep 08, 2022 |
| Techvision    | TVI7309X B0                 | [1d81b77310](https://bsd-hardware.info/?probe=1d81b77310) | Sep 07, 2022 |
| Intel         | SYS-2USM03-6M01E            | [d4f98f18b9](https://bsd-hardware.info/?probe=d4f98f18b9) | Sep 07, 2022 |
| Techvision    | TVI7309X B0                 | [b803a767af](https://bsd-hardware.info/?probe=b803a767af) | Sep 06, 2022 |
| CncTion       | N5105-4L                    | [2a34dc3fe0](https://bsd-hardware.info/?probe=2a34dc3fe0) | Sep 05, 2022 |
| BESSTAR Te... | TH50                        | [734a8e61c4](https://bsd-hardware.info/?probe=734a8e61c4) | Sep 05, 2022 |
| Unknown       | Unknown                     | [c1967c7cf8](https://bsd-hardware.info/?probe=c1967c7cf8) | Sep 04, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [72cdc4123c](https://bsd-hardware.info/?probe=72cdc4123c) | Sep 03, 2022 |
| Lenovo        | ThinkCentre M70e 0833A29    | [b7c5b9a51d](https://bsd-hardware.info/?probe=b7c5b9a51d) | Sep 03, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [1e05b51bf1](https://bsd-hardware.info/?probe=1e05b51bf1) | Sep 02, 2022 |
| Intel         | QHSW02                      | [b0ad128162](https://bsd-hardware.info/?probe=b0ad128162) | Sep 02, 2022 |
| Dell          | 0G261D A00                  | [c77b23d1a7](https://bsd-hardware.info/?probe=c77b23d1a7) | Aug 31, 2022 |
| Intel         | DENLOW_WS                   | [067a217959](https://bsd-hardware.info/?probe=067a217959) | Aug 30, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [df3df2855b](https://bsd-hardware.info/?probe=df3df2855b) | Aug 28, 2022 |
| ASUSTek       | PRIME X570-P                | [0f1eabf01e](https://bsd-hardware.info/?probe=0f1eabf01e) | Aug 27, 2022 |
| Intel         | QHSW02                      | [184a8697e9](https://bsd-hardware.info/?probe=184a8697e9) | Aug 27, 2022 |
| Intel         | QHSW02                      | [1765bd0426](https://bsd-hardware.info/?probe=1765bd0426) | Aug 27, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [3465c46b7d](https://bsd-hardware.info/?probe=3465c46b7d) | Aug 26, 2022 |
| PC Engines    | APU2                        | [97da53ff14](https://bsd-hardware.info/?probe=97da53ff14) | Aug 25, 2022 |
| ASRock        | AD2550-ITX                  | [43d0101ac4](https://bsd-hardware.info/?probe=43d0101ac4) | Aug 24, 2022 |
| HP            | 82B4                        | [5e07fc9831](https://bsd-hardware.info/?probe=5e07fc9831) | Aug 22, 2022 |
| Unknown       | Unknown                     | [7d059d1d0a](https://bsd-hardware.info/?probe=7d059d1d0a) | Aug 22, 2022 |
| Gigabyte      | H310M S2H                   | [b32f197fe9](https://bsd-hardware.info/?probe=b32f197fe9) | Aug 21, 2022 |
| PC Engines    | APU2                        | [92bff81bb5](https://bsd-hardware.info/?probe=92bff81bb5) | Aug 20, 2022 |
| PC Engines    | APU2                        | [ccdff6fbea](https://bsd-hardware.info/?probe=ccdff6fbea) | Aug 20, 2022 |
| Protectli     | FW4B                        | [8eb0c6ffbe](https://bsd-hardware.info/?probe=8eb0c6ffbe) | Aug 19, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [fb02323793](https://bsd-hardware.info/?probe=fb02323793) | Aug 19, 2022 |
| Inventec      | Z CLASS A02                 | [290a94a907](https://bsd-hardware.info/?probe=290a94a907) | Aug 18, 2022 |
| Dell          | 0VG93V A00                  | [8de9fa2319](https://bsd-hardware.info/?probe=8de9fa2319) | Aug 18, 2022 |
| Dell          | 0FDY5C A00                  | [2c0bb11a7b](https://bsd-hardware.info/?probe=2c0bb11a7b) | Aug 17, 2022 |
| Dell          | 042P49 A00                  | [7130975fe3](https://bsd-hardware.info/?probe=7130975fe3) | Aug 17, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [e67200aee1](https://bsd-hardware.info/?probe=e67200aee1) | Aug 15, 2022 |
| Unknown       | Unknown                     | [ef2a61855a](https://bsd-hardware.info/?probe=ef2a61855a) | Aug 15, 2022 |
| Unknown       | Unknown                     | [e23ed854ed](https://bsd-hardware.info/?probe=e23ed854ed) | Aug 14, 2022 |
| Fujitsu       | PRIMERGY RX200 S6           | [9267873961](https://bsd-hardware.info/?probe=9267873961) | Aug 13, 2022 |
| Supermicro    | X9SCI/X9SCA                 | [6e7e782b00](https://bsd-hardware.info/?probe=6e7e782b00) | Aug 13, 2022 |
| Fujitsu       | PRIMERGY RX200 S6           | [6884e940a1](https://bsd-hardware.info/?probe=6884e940a1) | Aug 13, 2022 |
| Dell          | 0T7D40 A01                  | [d06e05c67a](https://bsd-hardware.info/?probe=d06e05c67a) | Aug 12, 2022 |
| HP            | 82B4                        | [d3fd85a7b6](https://bsd-hardware.info/?probe=d3fd85a7b6) | Aug 12, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [fe8deedda3](https://bsd-hardware.info/?probe=fe8deedda3) | Aug 11, 2022 |
| Intel         | Q3XXG4-P V1.0               | [d3f51a01b1](https://bsd-hardware.info/?probe=d3f51a01b1) | Aug 11, 2022 |
| Unknown       | Unknown                     | [80e867e04c](https://bsd-hardware.info/?probe=80e867e04c) | Aug 10, 2022 |
| BESSTAR Te... | TH50                        | [afca16a0bd](https://bsd-hardware.info/?probe=afca16a0bd) | Aug 09, 2022 |
| NF541         | 1.0                         | [dcde0e7a44](https://bsd-hardware.info/?probe=dcde0e7a44) | Aug 09, 2022 |
| Dell          | 042P49 A00                  | [a38375fa97](https://bsd-hardware.info/?probe=a38375fa97) | Aug 08, 2022 |
| Dell          | 042P49 A00                  | [81a5e313cd](https://bsd-hardware.info/?probe=81a5e313cd) | Aug 08, 2022 |
| Unknown       | Unknown                     | [64768cfe88](https://bsd-hardware.info/?probe=64768cfe88) | Aug 07, 2022 |
| BESSTAR Te... | DMAF5 V1.0                  | [75ffbbae85](https://bsd-hardware.info/?probe=75ffbbae85) | Aug 07, 2022 |
| HP            | 18E4                        | [7408fe969c](https://bsd-hardware.info/?probe=7408fe969c) | Aug 07, 2022 |
| HP            | 213D A01                    | [383712cf94](https://bsd-hardware.info/?probe=383712cf94) | Aug 06, 2022 |
| HP            | 213D A01                    | [e28886f86e](https://bsd-hardware.info/?probe=e28886f86e) | Aug 06, 2022 |
| Gigabyte      | H97M-HD3                    | [4a7705414f](https://bsd-hardware.info/?probe=4a7705414f) | Aug 06, 2022 |
| BESSTAR Te... | TH50                        | [9e69d3a39f](https://bsd-hardware.info/?probe=9e69d3a39f) | Aug 06, 2022 |
| BESSTAR Te... | TH50                        | [e68fb8c88e](https://bsd-hardware.info/?probe=e68fb8c88e) | Aug 06, 2022 |
| Unknown       | Unknown                     | [ae62a89080](https://bsd-hardware.info/?probe=ae62a89080) | Aug 05, 2022 |
| ASUSTek       | PRIME Z270-A                | [69214b0c79](https://bsd-hardware.info/?probe=69214b0c79) | Aug 04, 2022 |
| PC Engines    | apu4                        | [2ae838d489](https://bsd-hardware.info/?probe=2ae838d489) | Aug 02, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [f2590dea4b](https://bsd-hardware.info/?probe=f2590dea4b) | Aug 01, 2022 |
| Gigabyte      | H610I DDR4                  | [d50ffab1cc](https://bsd-hardware.info/?probe=d50ffab1cc) | Aug 01, 2022 |
| ASUSTek       | P5W64 WS Pro                | [f05a901a30](https://bsd-hardware.info/?probe=f05a901a30) | Aug 01, 2022 |
| Unknown       | Unknown                     | [f891511390](https://bsd-hardware.info/?probe=f891511390) | Jul 30, 2022 |
| AMD           | Inagua CRB                  | [0d0b0c3f9e](https://bsd-hardware.info/?probe=0d0b0c3f9e) | Jul 29, 2022 |
| Dell          | 0PC5F7 A03                  | [7cc4f8754f](https://bsd-hardware.info/?probe=7cc4f8754f) | Jul 27, 2022 |
| CNCTION-IA... | Unknown                     | [91165a8899](https://bsd-hardware.info/?probe=91165a8899) | Jul 27, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [9df3c644b9](https://bsd-hardware.info/?probe=9df3c644b9) | Jul 27, 2022 |
| MW            | GMLK-2_5G4L                 | [fd67eb14ae](https://bsd-hardware.info/?probe=fd67eb14ae) | Jul 26, 2022 |
| ZOTAC         | Unknown                     | [2f701b55fc](https://bsd-hardware.info/?probe=2f701b55fc) | Jul 25, 2022 |
| Unknown       | Unknown                     | [8830b5ba19](https://bsd-hardware.info/?probe=8830b5ba19) | Jul 24, 2022 |
| ASRock        | J3455B-ITX                  | [37ce098399](https://bsd-hardware.info/?probe=37ce098399) | Jul 23, 2022 |
| Intel         | DH77KC AAG39641-400         | [df31840a7e](https://bsd-hardware.info/?probe=df31840a7e) | Jul 22, 2022 |
| Intel         | QHSW02                      | [8f910e599b](https://bsd-hardware.info/?probe=8f910e599b) | Jul 21, 2022 |
| ASRock        | A520M-ITX/ac                | [48854ed05e](https://bsd-hardware.info/?probe=48854ed05e) | Jul 21, 2022 |
| Biostar       | J4105NHU                    | [1b6748d4f7](https://bsd-hardware.info/?probe=1b6748d4f7) | Jul 19, 2022 |
| ASRock        | H570M-ITX/ac                | [4b0bdf58dd](https://bsd-hardware.info/?probe=4b0bdf58dd) | Jul 18, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [e3461d0ff8](https://bsd-hardware.info/?probe=e3461d0ff8) | Jul 17, 2022 |
| Supermicro    | A2SAP-HA                    | [27c6228555](https://bsd-hardware.info/?probe=27c6228555) | Jul 17, 2022 |
| YANYU         | H87SL VER:1.3               | [fda62409ee](https://bsd-hardware.info/?probe=fda62409ee) | Jul 17, 2022 |
| MSI           | B85M-E45                    | [80f2d74d1a](https://bsd-hardware.info/?probe=80f2d74d1a) | Jul 16, 2022 |
| PC Engines    | APU3                        | [2b20f47024](https://bsd-hardware.info/?probe=2b20f47024) | Jul 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [2a52f27ffe](https://bsd-hardware.info/?probe=2a52f27ffe) | Jul 13, 2022 |
| ASRock        | A520M-ITX/ac                | [be86d81d29](https://bsd-hardware.info/?probe=be86d81d29) | Jul 13, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [75132f9078](https://bsd-hardware.info/?probe=75132f9078) | Jul 13, 2022 |
| ASRock        | Z97 Professional            | [c1c177fbb0](https://bsd-hardware.info/?probe=c1c177fbb0) | Jul 12, 2022 |
| HP            | 1790                        | [bc5988d764](https://bsd-hardware.info/?probe=bc5988d764) | Jul 11, 2022 |
| NF541         | 1.0                         | [00cab93f40](https://bsd-hardware.info/?probe=00cab93f40) | Jul 10, 2022 |
| Unknown       | Unknown                     | [947d413e10](https://bsd-hardware.info/?probe=947d413e10) | Jul 09, 2022 |
| Unknown       | Unknown                     | [e42f50fe0f](https://bsd-hardware.info/?probe=e42f50fe0f) | Jul 09, 2022 |
| Unknown       | Unknown                     | [b0380fb22c](https://bsd-hardware.info/?probe=b0380fb22c) | Jul 09, 2022 |
| Intel         | QHSW02                      | [e7d923f138](https://bsd-hardware.info/?probe=e7d923f138) | Jul 07, 2022 |
| Intel         | CRESCENTBAY                 | [71efa2b0b9](https://bsd-hardware.info/?probe=71efa2b0b9) | Jul 06, 2022 |
| ASUSTek       | H110I-PLUS                  | [342ef61cdc](https://bsd-hardware.info/?probe=342ef61cdc) | Jul 05, 2022 |
| NF541S        | 1.0                         | [937fe3af39](https://bsd-hardware.info/?probe=937fe3af39) | Jul 04, 2022 |
| ASUSTek       | PRIME X570-P                | [c8a69b3805](https://bsd-hardware.info/?probe=c8a69b3805) | Jul 04, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [aeee3a91e6](https://bsd-hardware.info/?probe=aeee3a91e6) | Jul 03, 2022 |
| ASRock        | H310CM-DVS                  | [907e22dbb6](https://bsd-hardware.info/?probe=907e22dbb6) | Jul 03, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [40c8fdfafa](https://bsd-hardware.info/?probe=40c8fdfafa) | Jul 02, 2022 |
| HP            | 213D A01                    | [21af8c270f](https://bsd-hardware.info/?probe=21af8c270f) | Jul 01, 2022 |
| Unknown       | J3160-4L                    | [adaa197bf6](https://bsd-hardware.info/?probe=adaa197bf6) | Jul 01, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [77acc9f5cf](https://bsd-hardware.info/?probe=77acc9f5cf) | Jul 01, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ffa0086c70](https://bsd-hardware.info/?probe=ffa0086c70) | Jul 01, 2022 |
| Unknown       | Unknown                     | [35f24d802a](https://bsd-hardware.info/?probe=35f24d802a) | Jun 30, 2022 |
| ASUSTek       | H110I-PLUS                  | [e8f496791d](https://bsd-hardware.info/?probe=e8f496791d) | Jun 30, 2022 |
| Unknown       | Unknown                     | [8e6519f26f](https://bsd-hardware.info/?probe=8e6519f26f) | Jun 30, 2022 |
| Unknown       | Unknown                     | [85c0c08d91](https://bsd-hardware.info/?probe=85c0c08d91) | Jun 29, 2022 |
| ASRock        | N3700M                      | [3896fd5bc2](https://bsd-hardware.info/?probe=3896fd5bc2) | Jun 29, 2022 |
| Intel         | QHSW02                      | [28928d9ad4](https://bsd-hardware.info/?probe=28928d9ad4) | Jun 28, 2022 |
| Intel         | Q3XXG4-P V1.0               | [7fcdb93a4b](https://bsd-hardware.info/?probe=7fcdb93a4b) | Jun 27, 2022 |
| Unknown       | Unknown                     | [8ab4302d97](https://bsd-hardware.info/?probe=8ab4302d97) | Jun 26, 2022 |
| PC Engines    | APU2                        | [3e4fbe09f1](https://bsd-hardware.info/?probe=3e4fbe09f1) | Jun 26, 2022 |
| Biostar       | J4105NHU                    | [9419973ba0](https://bsd-hardware.info/?probe=9419973ba0) | Jun 25, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [6c72a0dca7](https://bsd-hardware.info/?probe=6c72a0dca7) | Jun 24, 2022 |
| Gigabyte      | H610I DDR4                  | [bfcc8f1f66](https://bsd-hardware.info/?probe=bfcc8f1f66) | Jun 24, 2022 |
| ASUSTek       | PRIME X570-P                | [18f9e5bf9c](https://bsd-hardware.info/?probe=18f9e5bf9c) | Jun 23, 2022 |
| PC Engines    | APU2                        | [de9163945f](https://bsd-hardware.info/?probe=de9163945f) | Jun 23, 2022 |
| PC Engines    | apu4                        | [d7e6f088d0](https://bsd-hardware.info/?probe=d7e6f088d0) | Jun 22, 2022 |
| Supermicro    | A2SDi-LN4F                  | [72860a723c](https://bsd-hardware.info/?probe=72860a723c) | Jun 22, 2022 |
| Unknown       | Unknown                     | [62a2455a8b](https://bsd-hardware.info/?probe=62a2455a8b) | Jun 22, 2022 |
| Unknown       | Unknown                     | [fb1ffe9c0d](https://bsd-hardware.info/?probe=fb1ffe9c0d) | Jun 22, 2022 |
| Unknown       | Unknown                     | [24b47422c7](https://bsd-hardware.info/?probe=24b47422c7) | Jun 22, 2022 |
| MSI           | B85M-E45                    | [d9cc6cee6b](https://bsd-hardware.info/?probe=d9cc6cee6b) | Jun 21, 2022 |
| ASUSTek       | H110T                       | [a4a51d110b](https://bsd-hardware.info/?probe=a4a51d110b) | Jun 20, 2022 |
| Unknown       | Unknown                     | [c9303dab91](https://bsd-hardware.info/?probe=c9303dab91) | Jun 19, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [b576f09eec](https://bsd-hardware.info/?probe=b576f09eec) | Jun 17, 2022 |
| Biostar       | A10N-8800E                  | [60df3db3ab](https://bsd-hardware.info/?probe=60df3db3ab) | Jun 16, 2022 |
| Unknown       | Unknown                     | [b7540c1e4a](https://bsd-hardware.info/?probe=b7540c1e4a) | Jun 14, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [7626993227](https://bsd-hardware.info/?probe=7626993227) | Jun 13, 2022 |
| Unknown       | Unknown                     | [1cc180ad27](https://bsd-hardware.info/?probe=1cc180ad27) | Jun 13, 2022 |
| Unknown       | Unknown                     | [36f6b6f077](https://bsd-hardware.info/?probe=36f6b6f077) | Jun 11, 2022 |
| Lanner        | FW-7543 B-GA                | [bf1e373f8a](https://bsd-hardware.info/?probe=bf1e373f8a) | Jun 10, 2022 |
| HP            | 806A                        | [c3051ac63e](https://bsd-hardware.info/?probe=c3051ac63e) | Jun 10, 2022 |
| Unknown       | Unknown                     | [23d5c4d92d](https://bsd-hardware.info/?probe=23d5c4d92d) | Jun 10, 2022 |
| Intel         | MAHOBAY                     | [cf146946d3](https://bsd-hardware.info/?probe=cf146946d3) | Jun 09, 2022 |
| ASUSTek       | TUF B360M-E GAMING          | [26375bae48](https://bsd-hardware.info/?probe=26375bae48) | Jun 08, 2022 |
| ASRock        | J4125B-ITX                  | [fd96faf8aa](https://bsd-hardware.info/?probe=fd96faf8aa) | Jun 08, 2022 |
| HP            | 18E4                        | [d63cd86fb5](https://bsd-hardware.info/?probe=d63cd86fb5) | Jun 08, 2022 |
| Supermicro    | X7SPA-HF                    | [37a918bd43](https://bsd-hardware.info/?probe=37a918bd43) | Jun 08, 2022 |
| MSI           | B85M-E45                    | [10e7bbf38a](https://bsd-hardware.info/?probe=10e7bbf38a) | Jun 08, 2022 |
| MW            | GMLK-2_5G4L                 | [6c9ccc6963](https://bsd-hardware.info/?probe=6c9ccc6963) | Jun 06, 2022 |
| PC Engines    | APU2                        | [ad2b0dd980](https://bsd-hardware.info/?probe=ad2b0dd980) | Jun 06, 2022 |
| Unknown       | Unknown                     | [d8cd85e3d7](https://bsd-hardware.info/?probe=d8cd85e3d7) | Jun 05, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [b98e41f6a4](https://bsd-hardware.info/?probe=b98e41f6a4) | Jun 05, 2022 |
| Thomas-Kre... | LES network 6L              | [a3023b3f39](https://bsd-hardware.info/?probe=a3023b3f39) | Jun 04, 2022 |
| HP            | 806A                        | [cc091ee2e2](https://bsd-hardware.info/?probe=cc091ee2e2) | Jun 03, 2022 |
| Unknown       | Unknown                     | [4294ad5419](https://bsd-hardware.info/?probe=4294ad5419) | Jun 01, 2022 |
| Unknown       | Unknown                     | [2da72109a6](https://bsd-hardware.info/?probe=2da72109a6) | Jun 01, 2022 |
| Unknown       | Unknown                     | [9ad9772ac7](https://bsd-hardware.info/?probe=9ad9772ac7) | May 31, 2022 |
| ASUSTek       | PRIME X570-P                | [fa3ea36bad](https://bsd-hardware.info/?probe=fa3ea36bad) | May 31, 2022 |
| Deciso        | Netboard A10 V2.1           | [6beacad396](https://bsd-hardware.info/?probe=6beacad396) | May 31, 2022 |
| Unknown       | Unknown                     | [ef87e699fb](https://bsd-hardware.info/?probe=ef87e699fb) | May 30, 2022 |
| Intel         | Q3XXG4-P V1.0               | [95234abead](https://bsd-hardware.info/?probe=95234abead) | May 28, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [cdddbb5d23](https://bsd-hardware.info/?probe=cdddbb5d23) | May 27, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [7a47fcd920](https://bsd-hardware.info/?probe=7a47fcd920) | May 27, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [a5446262b3](https://bsd-hardware.info/?probe=a5446262b3) | May 27, 2022 |
| ASRock        | B660M-HDV                   | [fadb382a5a](https://bsd-hardware.info/?probe=fadb382a5a) | May 26, 2022 |
| ASRockRack    | E3C242D4U2-2T               | [d35f1fb7e0](https://bsd-hardware.info/?probe=d35f1fb7e0) | May 25, 2022 |
| ASRockRack    | E3C242D4U2-2T               | [66f9070856](https://bsd-hardware.info/?probe=66f9070856) | May 23, 2022 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | [e9e497fc7b](https://bsd-hardware.info/?probe=e9e497fc7b) | May 22, 2022 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | [b05a8f6ed8](https://bsd-hardware.info/?probe=b05a8f6ed8) | May 22, 2022 |
| Biostar       | J4105NHU                    | [88b74aaf3b](https://bsd-hardware.info/?probe=88b74aaf3b) | May 22, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [e9524e612d](https://bsd-hardware.info/?probe=e9524e612d) | May 22, 2022 |
| HP            | 339A                        | [e6a9b68262](https://bsd-hardware.info/?probe=e6a9b68262) | May 20, 2022 |
| Intel         | Q3XXG4-P V1.0               | [24d2bf3524](https://bsd-hardware.info/?probe=24d2bf3524) | May 19, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [ea6146e013](https://bsd-hardware.info/?probe=ea6146e013) | May 19, 2022 |
| Supermicro    | A2SDi-LN4F                  | [acc4101dc1](https://bsd-hardware.info/?probe=acc4101dc1) | May 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | [edcd612c83](https://bsd-hardware.info/?probe=edcd612c83) | May 18, 2022 |
| Biostar       | H410MH S2                   | [1b218204b8](https://bsd-hardware.info/?probe=1b218204b8) | May 18, 2022 |
| MSI           | B85M-E45                    | [83ab25156c](https://bsd-hardware.info/?probe=83ab25156c) | May 18, 2022 |
| Unknown       | Unknown                     | [e13c8baa2d](https://bsd-hardware.info/?probe=e13c8baa2d) | May 17, 2022 |
| Unknown       | Unknown                     | [b8579c7f84](https://bsd-hardware.info/?probe=b8579c7f84) | May 17, 2022 |
| Unknown       | Unknown                     | [98b4dea15a](https://bsd-hardware.info/?probe=98b4dea15a) | May 17, 2022 |
| Intel         | Q3XXG4-P V1.0               | [8c2f853975](https://bsd-hardware.info/?probe=8c2f853975) | May 17, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [b87692aeb4](https://bsd-hardware.info/?probe=b87692aeb4) | May 15, 2022 |
| MSI           | MS-7C82                     | [2ad883afec](https://bsd-hardware.info/?probe=2ad883afec) | May 15, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [6974f0958e](https://bsd-hardware.info/?probe=6974f0958e) | May 15, 2022 |
| Unknown       | Unknown                     | [4fad520626](https://bsd-hardware.info/?probe=4fad520626) | May 14, 2022 |
| ASRock        | E350M1                      | [1850fa38e0](https://bsd-hardware.info/?probe=1850fa38e0) | May 14, 2022 |
| ASRock        | E350M1                      | [4520b5034e](https://bsd-hardware.info/?probe=4520b5034e) | May 13, 2022 |
| HP            | 213D A01                    | [89955ba84f](https://bsd-hardware.info/?probe=89955ba84f) | May 11, 2022 |
| HP            | 82A1                        | [34cb091e26](https://bsd-hardware.info/?probe=34cb091e26) | May 08, 2022 |
| BESSTAR Te... | DMAF5 V1.0                  | [dc534266df](https://bsd-hardware.info/?probe=dc534266df) | May 06, 2022 |
| BESSTAR Te... | IB9                         | [4a4e45585d](https://bsd-hardware.info/?probe=4a4e45585d) | May 06, 2022 |
| friendlyel... | nanopi-r4s                  | [3db2ec8973](https://bsd-hardware.info/?probe=3db2ec8973) | May 04, 2022 |
| Unknown       | Unknown                     | [b96fd74ab0](https://bsd-hardware.info/?probe=b96fd74ab0) | May 03, 2022 |
| ASRock        | J4125B-ITX                  | [14d02a8209](https://bsd-hardware.info/?probe=14d02a8209) | May 03, 2022 |
| Intel         | QHSW02                      | [e4c8d6c787](https://bsd-hardware.info/?probe=e4c8d6c787) | May 01, 2022 |
| MSI           | MEG X570 UNIFY              | [5e8168a980](https://bsd-hardware.info/?probe=5e8168a980) | Apr 30, 2022 |
| OEM           | 1.0                         | [36e78ab638](https://bsd-hardware.info/?probe=36e78ab638) | Apr 29, 2022 |
| Unknown       | YL-J1900-V1                 | [54fe9e7529](https://bsd-hardware.info/?probe=54fe9e7529) | Apr 29, 2022 |
| MSI           | A520M-A PRO                 | [336add4fcb](https://bsd-hardware.info/?probe=336add4fcb) | Apr 28, 2022 |
| MSI           | A520M-A PRO                 | [34f2ba40e7](https://bsd-hardware.info/?probe=34f2ba40e7) | Apr 27, 2022 |
| PC Engines    | APU2                        | [920eae6f2e](https://bsd-hardware.info/?probe=920eae6f2e) | Apr 27, 2022 |
| MSI           | 970A GAMING PRO CARBON      | [c36f9d6c1d](https://bsd-hardware.info/?probe=c36f9d6c1d) | Apr 26, 2022 |
| Unknown       | MANIFOLD 2-C                | [637c28d728](https://bsd-hardware.info/?probe=637c28d728) | Apr 25, 2022 |
| MSI           | X399 GAMING PRO CARBON A... | [86c4af7ca4](https://bsd-hardware.info/?probe=86c4af7ca4) | Apr 25, 2022 |
| MSI           | MEG X570 UNIFY              | [6afa33e8f8](https://bsd-hardware.info/?probe=6afa33e8f8) | Apr 24, 2022 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [1ce660f88e](https://bsd-hardware.info/?probe=1ce660f88e) | Apr 24, 2022 |
| PC Engines    | apu4                        | [ae39e5adc0](https://bsd-hardware.info/?probe=ae39e5adc0) | Apr 22, 2022 |
| ASRock        | X79 Extreme6/GB             | [cd85d68dcd](https://bsd-hardware.info/?probe=cd85d68dcd) | Apr 21, 2022 |
| CheckPoint    | T-140-00                    | [8e2c861ecf](https://bsd-hardware.info/?probe=8e2c861ecf) | Apr 19, 2022 |
| CheckPoint    | T-140-00                    | [8f0c5b5334](https://bsd-hardware.info/?probe=8f0c5b5334) | Apr 19, 2022 |
| PC Engines    | APU2                        | [47ddf6b2bd](https://bsd-hardware.info/?probe=47ddf6b2bd) | Apr 19, 2022 |
| Gigabyte      | B85M-D3H                    | [8d7236247d](https://bsd-hardware.info/?probe=8d7236247d) | Apr 18, 2022 |
| ASRock        | B85M Pro3                   | [9ff2cbdcf1](https://bsd-hardware.info/?probe=9ff2cbdcf1) | Apr 18, 2022 |
| Unknown       | Unknown                     | [0914d63c72](https://bsd-hardware.info/?probe=0914d63c72) | Apr 16, 2022 |
| Biostar       | H410MH S2                   | [d045a4acad](https://bsd-hardware.info/?probe=d045a4acad) | Apr 14, 2022 |
| Gigabyte      | B85M-D3H                    | [3365444265](https://bsd-hardware.info/?probe=3365444265) | Apr 14, 2022 |
| Unknown       | Unknown                     | [4ec1e3548c](https://bsd-hardware.info/?probe=4ec1e3548c) | Apr 14, 2022 |
| Intel         | Q3XXG4-P V1.0               | [efb76ec7fe](https://bsd-hardware.info/?probe=efb76ec7fe) | Apr 13, 2022 |
| Unknown       | Unknown                     | [ad14582532](https://bsd-hardware.info/?probe=ad14582532) | Apr 13, 2022 |
| Intel         | D53427RKE G87971-403        | [1a1de076c7](https://bsd-hardware.info/?probe=1a1de076c7) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [5f2a882529](https://bsd-hardware.info/?probe=5f2a882529) | Apr 11, 2022 |
| Gigabyte      | MZBSWAP-K4                  | [752f962123](https://bsd-hardware.info/?probe=752f962123) | Apr 10, 2022 |
| PC Engines    | APU2                        | [ae2d120c7c](https://bsd-hardware.info/?probe=ae2d120c7c) | Apr 10, 2022 |
| Shuttle       | DS10U                       | [7d5919eb2b](https://bsd-hardware.info/?probe=7d5919eb2b) | Apr 10, 2022 |
| Unknown       | Unknown                     | [6835aa43e3](https://bsd-hardware.info/?probe=6835aa43e3) | Apr 09, 2022 |
| Intel         | MAHOBAY                     | [8b21109cd4](https://bsd-hardware.info/?probe=8b21109cd4) | Apr 08, 2022 |
| MSI           | MS-7369                     | [25f2161cac](https://bsd-hardware.info/?probe=25f2161cac) | Apr 08, 2022 |
| ASRock        | H570M-ITX/ac                | [44327ad768](https://bsd-hardware.info/?probe=44327ad768) | Apr 07, 2022 |
| HP            | 213D A01                    | [3f6e05c14d](https://bsd-hardware.info/?probe=3f6e05c14d) | Apr 07, 2022 |
| ASRock        | B660M-HDV                   | [9ffa0cc352](https://bsd-hardware.info/?probe=9ffa0cc352) | Apr 06, 2022 |
| PC Engines    | APU2                        | [69304a74cc](https://bsd-hardware.info/?probe=69304a74cc) | Apr 06, 2022 |
| Unknown       | Unknown                     | [4cf896e25a](https://bsd-hardware.info/?probe=4cf896e25a) | Apr 06, 2022 |
| ASUSTek       | PRIME B360M-A               | [90663f7aa0](https://bsd-hardware.info/?probe=90663f7aa0) | Apr 05, 2022 |
| HP            | 213D A01                    | [238d8bbcde](https://bsd-hardware.info/?probe=238d8bbcde) | Apr 04, 2022 |
| PC Engines    | APU2                        | [69cb42c07b](https://bsd-hardware.info/?probe=69cb42c07b) | Apr 02, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [1bdaf4bb77](https://bsd-hardware.info/?probe=1bdaf4bb77) | Apr 01, 2022 |
| HP            | 3396                        | [7a60daeaef](https://bsd-hardware.info/?probe=7a60daeaef) | Apr 01, 2022 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | [9b6f9eac6f](https://bsd-hardware.info/?probe=9b6f9eac6f) | Apr 01, 2022 |
| PC Engines    | APU                         | [c71152505f](https://bsd-hardware.info/?probe=c71152505f) | Apr 01, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [3df6a01030](https://bsd-hardware.info/?probe=3df6a01030) | Mar 31, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [b5ea7eaeb0](https://bsd-hardware.info/?probe=b5ea7eaeb0) | Mar 31, 2022 |
| ASUSTek       | PRO B460M-C                 | [0542f7a16d](https://bsd-hardware.info/?probe=0542f7a16d) | Mar 29, 2022 |
| Unknown       | Unknown                     | [4383e28183](https://bsd-hardware.info/?probe=4383e28183) | Mar 29, 2022 |
| Intel         | DENLOW_REFRESH_WS           | [36896a719d](https://bsd-hardware.info/?probe=36896a719d) | Mar 29, 2022 |
| ASRock        | X79 Extreme6/GB             | [0646607953](https://bsd-hardware.info/?probe=0646607953) | Mar 28, 2022 |
| PC Engines    | apu4                        | [a35c56ca36](https://bsd-hardware.info/?probe=a35c56ca36) | Mar 28, 2022 |
| Protectli     | FW6 Ver                     | [f09a26de6f](https://bsd-hardware.info/?probe=f09a26de6f) | Mar 27, 2022 |
| Gigabyte      | MZBSWBP-00                  | [9e5d1c9daa](https://bsd-hardware.info/?probe=9e5d1c9daa) | Mar 26, 2022 |
| Unknown       | Unknown                     | [da94141898](https://bsd-hardware.info/?probe=da94141898) | Mar 26, 2022 |
| PC Engines    | apu4                        | [d95599aa97](https://bsd-hardware.info/?probe=d95599aa97) | Mar 25, 2022 |
| ASUSTek       | P10S-I Series               | [190fe4d13f](https://bsd-hardware.info/?probe=190fe4d13f) | Mar 24, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Germany/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| OPNsense 21.7.7   | 43       | 2.74%   |
| OPNsense 21.1     | 42       | 2.68%   |
| OPNsense 22.7.10  | 40       | 2.55%   |
| OPNsense 21.7.1   | 38       | 2.42%   |
| OPNsense 21.1.5   | 38       | 2.42%   |
| OPNsense 22.1     | 36       | 2.3%    |
| OPNsense 23.1.11  | 34       | 2.17%   |
| OPNsense 20.7.8   | 34       | 2.17%   |
| OPNsense 21.7.3   | 33       | 2.1%    |
| OPNsense 21.1.3   | 32       | 2.04%   |
| OPNsense 22.7.9   | 31       | 1.98%   |
| OPNsense 21.1.4   | 31       | 1.98%   |
| OPNsense 22.1.8   | 30       | 1.91%   |
| OPNsense 21.7.6   | 30       | 1.91%   |
| OPNsense 22.7.4   | 29       | 1.85%   |
| OPNsense 21.1.2   | 29       | 1.85%   |
| OPNsense 21.1.1   | 29       | 1.85%   |
| OPNsense 23.1.5   | 28       | 1.79%   |
| OPNsense 23.1.1   | 28       | 1.79%   |
| OPNsense 22.7.6   | 28       | 1.79%   |
| OPNsense 23.1     | 26       | 1.66%   |
| OPNsense 23.1.7   | 24       | 1.53%   |
| OPNsense 22.1.6   | 24       | 1.53%   |
| OPNsense 21.7.5   | 24       | 1.53%   |
| OPNsense 23.1.9   | 23       | 1.47%   |
| OPNsense 23.7.7   | 22       | 1.4%    |
| OPNsense 23.7.1   | 22       | 1.4%    |
| OPNsense 22.1.10  | 21       | 1.34%   |
| OPNsense 23.7.5   | 18       | 1.15%   |
| OPNsense 23.7.3   | 18       | 1.15%   |
| OPNsense 22.1.2   | 18       | 1.15%   |
| helloSystem 0.4.0 | 18       | 1.15%   |
| OPNsense 22.7.7   | 17       | 1.08%   |
| OPNsense 22.7.11  | 17       | 1.08%   |
| OPNsense 22.7     | 17       | 1.08%   |
| OPNsense 22.1.4   | 17       | 1.08%   |
| OPNsense 22.1.1   | 17       | 1.08%   |
| OPNsense 23.7.6   | 16       | 1.02%   |
| OPNsense 23.1.4   | 16       | 1.02%   |
| OPNsense 23.7.4   | 15       | 0.96%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 932      | 78.98%  |
| FreeBSD     | 115      | 9.75%   |
| helloSystem | 58       | 4.92%   |
| OpenBSD     | 35       | 2.97%   |
| GhostBSD    | 15       | 1.27%   |
| NomadBSD    | 8        | 0.68%   |
| NetBSD      | 5        | 0.42%   |
| TrueNAS     | 3        | 0.25%   |
| pfSense     | 2        | 0.17%   |
| MyBee       | 2        | 0.17%   |
| PC-BSD      | 1        | 0.08%   |
| HardenedBSD | 1        | 0.08%   |
| FreeNAS     | 1        | 0.08%   |
| DragonFly   | 1        | 0.08%   |
| ClonOS      | 1        | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 1160     | 98.98%  |
| arm64   | 4        | 0.34%   |
| arm     | 4        | 0.34%   |
| i386    | 2        | 0.17%   |
| sparc64 | 1        | 0.09%   |
| macppc  | 1        | 0.09%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 1016     | 85.81%  |
| helloDesktop  | 69       | 5.83%   |
| MATE          | 19       | 1.6%    |
| KDE5          | 19       | 1.6%    |
| XFCE          | 13       | 1.1%    |
| fvwm          | 12       | 1.01%   |
| TWM           | 8        | 0.68%   |
| AwesomeWM     | 7        | 0.59%   |
| GNOME         | 6        | 0.51%   |
| Openbox       | 4        | 0.34%   |
| i3            | 3        | 0.25%   |
| LXQt          | 1        | 0.08%   |
| LXDE          | 1        | 0.08%   |
| GNUstep       | 1        | 0.08%   |
| Fluxbox       | 1        | 0.08%   |
| filer         | 1        | 0.08%   |
| Enlightenment | 1        | 0.08%   |
| Compton       | 1        | 0.08%   |
| Cinnamon      | 1        | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 1026     | 87.39%  |
| X11     | 147      | 12.52%  |
| Tty     | 1        | 0.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 1055     | 89.26%  |
| SLiM    | 73       | 6.18%   |
| SDDM    | 18       | 1.52%   |
| LightDM | 17       | 1.44%   |
| XDM     | 11       | 0.93%   |
| GDM     | 6        | 0.51%   |
| Ly      | 2        | 0.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Desktops | Percent |
|-----------------|----------|---------|
| Unknown         | 995      | 83.9%   |
| C               | 67       | 5.65%   |
| en_US           | 64       | 5.4%    |
| de_DE           | 45       | 3.79%   |
| fr_FR           | 4        | 0.34%   |
| en              | 3        | 0.25%   |
| en_GB           | 2        | 0.17%   |
| ru_RU           | 1        | 0.08%   |
| ISO8859-15      | 1        | 0.08%   |
| fr              | 1        | 0.08%   |
| en_DE           | 1        | 0.08%   |
| de_DE.ISO8859-1 | 1        | 0.08%   |
| de              | 1        | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 1014     | 86.08%  |
| BIOS | 164      | 13.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ufs     | 754      | 62.73%  |
| Zfs     | 393      | 32.7%   |
| Ffs     | 35       | 2.91%   |
| Cd9660  | 19       | 1.58%   |
| Hammer2 | 1        | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1078     | 91.51%  |
| MBR     | 77       | 6.54%   |
| Unknown | 22       | 1.87%   |
| BSD     | 1        | 0.08%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 203      | 17.32%  |
| PC Engines                 | 128      | 10.92%  |
| Fujitsu                    | 100      | 8.53%   |
| ASUSTek Computer           | 76       | 6.48%   |
| ASRock                     | 71       | 6.06%   |
| Hewlett-Packard            | 62       | 5.29%   |
| Intel                      | 56       | 4.78%   |
| Gigabyte Technology        | 56       | 4.78%   |
| Dell                       | 41       | 3.5%    |
| MSI                        | 40       | 3.41%   |
| Supermicro                 | 30       | 2.56%   |
| Protectli                  | 29       | 2.47%   |
| Techvision                 | 20       | 1.71%   |
| CncTion                    | 20       | 1.71%   |
| BESSTAR Tech               | 19       | 1.62%   |
| Shuttle                    | 18       | 1.54%   |
| Lenovo                     | 18       | 1.54%   |
| Hardkernel                 | 14       | 1.19%   |
| MW                         | 11       | 0.94%   |
| Thomas-Krenn.AG            | 9        | 0.77%   |
| NF541                      | 8        | 0.68%   |
| CheckPoint                 | 8        | 0.68%   |
| ASRockRack                 | 8        | 0.68%   |
| Yanling                    | 7        | 0.6%    |
| IceWhale Technology        | 7        | 0.6%    |
| Biostar                    | 7        | 0.6%    |
| Deciso                     | 6        | 0.51%   |
| Lanner                     | 5        | 0.43%   |
| Beckhoff Automation        | 5        | 0.43%   |
| Acer                       | 5        | 0.43%   |
| NEXCOM                     | 4        | 0.34%   |
| Lex                        | 4        | 0.34%   |
| Foxconn                    | 4        | 0.34%   |
| Advantech                  | 4        | 0.34%   |
| ZOTAC                      | 3        | 0.26%   |
| ShenZhen MinWin Technology | 3        | 0.26%   |
| NU591                      | 3        | 0.26%   |
| Medion                     | 3        | 0.26%   |
| Fujitsu Siemens            | 3        | 0.26%   |
| YANYU                      | 2        | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 207      | 17.66%  |
| PC Engines APU2                | 64       | 5.46%   |
| Fujitsu FUTRO S920             | 49       | 4.18%   |
| PC Engines apu4                | 40       | 3.41%   |
| Techvision TVI7309X            | 20       | 1.71%   |
| Intel Q3XXG4-P V1.0            | 18       | 1.54%   |
| HARDKERNEL ODROID-H2           | 13       | 1.11%   |
| Protectli FW4B                 | 11       | 0.94%   |
| MW GMLK-2_5G4L                 | 11       | 0.94%   |
| Protectli FW6                  | 10       | 0.85%   |
| PC Engines APU                 | 10       | 0.85%   |
| CncTion N5105-4L               | 10       | 0.85%   |
| PC Engines APU3                | 9        | 0.77%   |
| HP ProLiant MicroServer Gen8   | 9        | 0.77%   |
| BESSTAR Tech X35G              | 9        | 0.77%   |
| Fujitsu FUTRO S930             | 8        | 0.68%   |
| NF541 1.0                      | 7        | 0.6%    |
| HP t620 PLUS Quad Core TC      | 6        | 0.51%   |
| Thomas-Krenn.AG LES network+   | 5        | 0.43%   |
| Intel DENLOW_WS                | 5        | 0.43%   |
| IceWhale ZimaBoard 832 ZMB     | 5        | 0.43%   |
| CncTion J4125-4L-I225          | 5        | 0.43%   |
| ASUS All Series                | 5        | 0.43%   |
| Supermicro X7SPA-HF            | 4        | 0.34%   |
| Protectli VP2420               | 4        | 0.34%   |
| PC Engines apu1                | 4        | 0.34%   |
| NEXCOM ASG                     | 4        | 0.34%   |
| MSI MS-7816                    | 4        | 0.34%   |
| Lex Pineview-D                 | 4        | 0.34%   |
| Lanner GP-7543                 | 4        | 0.34%   |
| HP t620 Quad Core TC           | 4        | 0.34%   |
| HP Compaq Elite 8300 SFF       | 4        | 0.34%   |
| Dell OptiPlex 9020             | 4        | 0.34%   |
| Dell OptiPlex 7010             | 4        | 0.34%   |
| Deciso Netboard A10 V2         | 4        | 0.34%   |
| ASUS M5A78L-M/USB3             | 4        | 0.34%   |
| Yanling LES network 6L         | 3        | 0.26%   |
| Thomas-Krenn.AG LES network 6L | 3        | 0.26%   |
| Supermicro X8SIL               | 3        | 0.26%   |
| NU591 LES v3                   | 3        | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Unknown               | 207      | 17.66%  |
| Fujitsu FUTRO         | 70       | 5.97%   |
| PC Engines APU2       | 64       | 5.46%   |
| PC Engines apu4       | 40       | 3.41%   |
| Dell OptiPlex         | 33       | 2.82%   |
| Techvision TVI7309X   | 20       | 1.71%   |
| Intel Q3XXG4-P        | 18       | 1.54%   |
| Lenovo ThinkCentre    | 14       | 1.19%   |
| HP ProLiant           | 14       | 1.19%   |
| Fujitsu ESPRIMO       | 14       | 1.19%   |
| HARDKERNEL ODROID-H2  | 13       | 1.11%   |
| HP Compaq             | 12       | 1.02%   |
| Protectli FW4B        | 11       | 0.94%   |
| MW GMLK-2             | 11       | 0.94%   |
| HP t620               | 11       | 0.94%   |
| HP ProDesk            | 11       | 0.94%   |
| Protectli FW6         | 10       | 0.85%   |
| PC Engines APU        | 10       | 0.85%   |
| CncTion N5105-4L      | 10       | 0.85%   |
| ASUS PRIME            | 10       | 0.85%   |
| PC Engines APU3       | 9        | 0.77%   |
| BESSTAR Tech X35G     | 9        | 0.77%   |
| ASUS TUF              | 9        | 0.77%   |
| Thomas-Krenn.AG LES   | 8        | 0.68%   |
| NF541 1.0             | 7        | 0.6%    |
| IceWhale ZimaBoard    | 7        | 0.6%    |
| HP EliteDesk          | 7        | 0.6%    |
| Deciso Netboard       | 6        | 0.51%   |
| Yanling LES           | 5        | 0.43%   |
| Intel DENLOW          | 5        | 0.43%   |
| CncTion J4125-4L-I225 | 5        | 0.43%   |
| ASUS ROG              | 5        | 0.43%   |
| ASUS PRO              | 5        | 0.43%   |
| ASUS All              | 5        | 0.43%   |
| Supermicro X7SPA-HF   | 4        | 0.34%   |
| Protectli VP2420      | 4        | 0.34%   |
| PC Engines apu1       | 4        | 0.34%   |
| NEXCOM ASG            | 4        | 0.34%   |
| MSI MS-7816           | 4        | 0.34%   |
| Lex Pineview-D        | 4        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 146      | 12.46%  |
| 2016    | 131      | 11.18%  |
| 2022    | 122      | 10.41%  |
| 2020    | 116      | 9.9%    |
| 2021    | 114      | 9.73%   |
| 2019    | 104      | 8.87%   |
| 2014    | 99       | 8.45%   |
| 2017    | 71       | 6.06%   |
| 2013    | 56       | 4.78%   |
| 2012    | 53       | 4.52%   |
| 2011    | 40       | 3.41%   |
| 2010    | 27       | 2.3%    |
| 2023    | 23       | 1.96%   |
| 2015    | 22       | 1.88%   |
| 2009    | 21       | 1.79%   |
| Unknown | 12       | 1.02%   |
| 2008    | 9        | 0.77%   |
| 2007    | 4        | 0.34%   |
| 2006    | 2        | 0.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1172     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1029     | 87.8%   |
| Yes  | 143      | 12.2%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 437      | 36.54%  |
| 4.01-8.0        | 303      | 25.33%  |
| 16.01-24.0      | 249      | 20.82%  |
| 32.01-64.0      | 96       | 8.03%   |
| 2.01-3.0        | 46       | 3.85%   |
| 64.01-256.0     | 35       | 2.93%   |
| 24.01-32.0      | 9        | 0.75%   |
| 3.01-4.0        | 7        | 0.59%   |
| 0.01-0.5        | 5        | 0.42%   |
| 1.01-2.0        | 4        | 0.33%   |
| 0.51-1.0        | 3        | 0.25%   |
| More than 256.0 | 2        | 0.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.01-0.5    | 634      | 52.18%  |
| 0.51-1.0    | 405      | 33.33%  |
| 1.01-2.0    | 103      | 8.48%   |
| 2.01-3.0    | 24       | 1.98%   |
| 3.01-4.0    | 13       | 1.07%   |
| 4.01-8.0    | 12       | 0.99%   |
| 0           | 7        | 0.58%   |
| Unknown     | 5        | 0.41%   |
| 16.01-24.0  | 4        | 0.33%   |
| 8.01-16.0   | 3        | 0.25%   |
| 24.01-32.0  | 2        | 0.16%   |
| 64.01-256.0 | 2        | 0.16%   |
| 32.01-64.0  | 1        | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 892      | 74.15%  |
| 2      | 116      | 9.64%   |
| 0      | 96       | 7.98%   |
| 3      | 43       | 3.57%   |
| 4      | 28       | 2.33%   |
| 5      | 13       | 1.08%   |
| 6      | 7        | 0.58%   |
| 7      | 5        | 0.42%   |
| 8      | 2        | 0.17%   |
| 9      | 1        | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1033     | 87.54%  |
| Yes       | 147      | 12.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1162     | 99.15%  |
| No        | 10       | 0.85%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 960      | 81.08%  |
| Yes       | 224      | 18.92%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1054     | 89.55%  |
| Yes       | 123      | 10.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Germany | 1172     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Berlin            | 106      | 7.98%   |
| Munich            | 52       | 3.92%   |
| Hamburg           | 46       | 3.46%   |
| Frankfurt am Main | 35       | 2.64%   |
| Cologne           | 32       | 2.41%   |
| Stuttgart         | 21       | 1.58%   |
| Ludwigsburg       | 19       | 1.43%   |
| Karlsruhe         | 17       | 1.28%   |
| Hanover           | 13       | 0.98%   |
| Nuremberg         | 12       | 0.9%    |
| Falkenstein       | 11       | 0.83%   |
| Mannheim          | 10       | 0.75%   |
| Dresden           | 10       | 0.75%   |
| Dortmund          | 10       | 0.75%   |
| Bochum            | 10       | 0.75%   |
| Wuppertal         | 9        | 0.68%   |
| Wiesbaden         | 9        | 0.68%   |
| Bonn              | 9        | 0.68%   |
| Heidelberg        | 8        | 0.6%    |
| Duisburg          | 8        | 0.6%    |
| Darmstadt         | 8        | 0.6%    |
| Braunschweig      | 8        | 0.6%    |
| Bielefeld         | 8        | 0.6%    |
| Ulm               | 7        | 0.53%   |
| Reutlingen        | 7        | 0.53%   |
| Magdeburg         | 7        | 0.53%   |
| Leipzig           | 7        | 0.53%   |
| Jena              | 7        | 0.53%   |
| Chemnitz          | 7        | 0.53%   |
| Paderborn         | 6        | 0.45%   |
| Mainz             | 6        | 0.45%   |
| Kiel              | 6        | 0.45%   |
| Kassel            | 6        | 0.45%   |
| Heilbronn         | 6        | 0.45%   |
| Bremen            | 6        | 0.45%   |
| Augsburg          | 6        | 0.45%   |
| Siegen            | 5        | 0.38%   |
| Oldenburg         | 5        | 0.38%   |
| Münster          | 5        | 0.38%   |
| Hamm              | 5        | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 207      | 342    | 15.69%  |
| Transcend           | 117      | 169    | 8.87%   |
| WDC                 | 111      | 192    | 8.42%   |
| Kingston            | 109      | 180    | 8.26%   |
| Crucial             | 75       | 113    | 5.69%   |
| SanDisk             | 71       | 103    | 5.38%   |
| Seagate             | 64       | 103    | 4.85%   |
| Intel               | 56       | 84     | 4.25%   |
| China               | 52       | 60     | 3.94%   |
| Toshiba             | 45       | 78     | 3.41%   |
| Phison              | 40       | 56     | 3.03%   |
| Intenso             | 31       | 49     | 2.35%   |
| Hoodisk             | 30       | 55     | 2.27%   |
| Innodisk            | 25       | 29     | 1.9%    |
| Hitachi             | 22       | 42     | 1.67%   |
| HGST                | 20       | 37     | 1.52%   |
| Micron Technology   | 17       | 33     | 1.29%   |
| FORESEE             | 13       | 18     | 0.99%   |
| A-DATA Technology   | 13       | 16     | 0.99%   |
| OCZ                 | 10       | 14     | 0.76%   |
| NVMe                | 9        | 15     | 0.68%   |
| SPCC                | 8        | 12     | 0.61%   |
| Protectli           | 8        | 10     | 0.61%   |
| ATP                 | 8        | 8      | 0.61%   |
| Apacer              | 8        | 14     | 0.61%   |
| Patriot             | 7        | 9      | 0.53%   |
| LITEONIT            | 6        | 8      | 0.45%   |
| Dogfish             | 6        | 7      | 0.45%   |
| Corsair             | 6        | 10     | 0.45%   |
| TCSUNBOW            | 5        | 6      | 0.38%   |
| SK hynix            | 5        | 5      | 0.38%   |
| ShiJi               | 5        | 6      | 0.38%   |
| KIOXIA-EXCERIA      | 5        | 11     | 0.38%   |
| KIOXIA              | 5        | 6      | 0.38%   |
| Gigabyte Technology | 5        | 6      | 0.38%   |
| Vaseky              | 4        | 4      | 0.3%    |
| PNY                 | 4        | 4      | 0.3%    |
| Lexar               | 4        | 4      | 0.3%    |
| Leven               | 4        | 6      | 0.3%    |
| KingDian            | 4        | 10     | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Phison SATA SSD 16GB            | 31       | 2.23%   |
| Transcend TS128GMSA230S 128GB   | 29       | 2.09%   |
| China SATA SSD 16GB             | 24       | 1.73%   |
| Transcend TS64GMSA230S 64GB     | 14       | 1.01%   |
| Samsung SSD 850 EVO 250GB       | 14       | 1.01%   |
| Samsung SSD 860 EVO 500GB       | 13       | 0.94%   |
| Crucial CT240BX500SSD1 240GB    | 13       | 0.94%   |
| Transcend TS256GMSA230S 256GB   | 12       | 0.86%   |
| Kingston SUV500MS120G 120GB     | 12       | 0.86%   |
| Innodisk DEMSR- 08GB mSATA 3ME3 | 12       | 0.86%   |
| Samsung SSD 870 EVO 250GB       | 11       | 0.79%   |
| Hoodisk SSD 64GB                | 11       | 0.79%   |
| Kingston SA400S37240G 240GB     | 9        | 0.65%   |
| Kingston SA400S37120G 120GB     | 9        | 0.65%   |
| Transcend TS32GMSA370 32GB      | 8        | 0.58%   |
| Samsung SSD 970 EVO Plus 500GB  | 8        | 0.58%   |
| Samsung SSD 840 EVO 250GB       | 8        | 0.58%   |
| Intenso SSD 120GB               | 8        | 0.58%   |
| Transcend TS64GMSA370 64GB      | 7        | 0.5%    |
| Transcend TS32GSSD370S 32GB     | 7        | 0.5%    |
| Transcend TS128GMSA370 128GB    | 7        | 0.5%    |
| Samsung SSD 860 EVO 250GB       | 7        | 0.5%    |
| Kingston SV300S37A120G 120GB    | 7        | 0.5%    |
| Kingston OM8PDP3512B-A01 512GB  | 7        | 0.5%    |
| Hoodisk SSD 256GB               | 7        | 0.5%    |
| Hoodisk SSD 128GB               | 7        | 0.5%    |
| Crucial CT500MX500SSD1 500GB    | 7        | 0.5%    |
| WDC WD40EFRX-68N32N0 4TB        | 6        | 0.43%   |
| SanDisk SSD PLUS 120GB          | 6        | 0.43%   |
| SanDisk SDSSDA120G 120GB        | 6        | 0.43%   |
| Samsung SSD 860 EVO mSATA 250GB | 6        | 0.43%   |
| Samsung SSD 850 PRO 256GB       | 6        | 0.43%   |
| Samsung SSD 840 EVO 120GB       | 6        | 0.43%   |
| Kingston SV300S37A60G 64GB      | 6        | 0.43%   |
| Kingston SKC600MS256G 256GB     | 6        | 0.43%   |
| Intenso SSD 128GB               | 6        | 0.43%   |
| FORESEE 64GB SSD                | 6        | 0.43%   |
| Crucial CT120BX500SSD1 120GB    | 6        | 0.43%   |
| Toshiba DT01ACA050 500GB        | 5        | 0.36%   |
| SanDisk SSD PLUS 240GB          | 5        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 84       | 153    | 32.68%  |
| Seagate             | 60       | 95     | 23.35%  |
| Toshiba             | 30       | 59     | 11.67%  |
| Hitachi             | 22       | 42     | 8.56%   |
| HGST                | 20       | 37     | 7.78%   |
| Samsung Electronics | 15       | 19     | 5.84%   |
| NVMe                | 6        | 7      | 2.33%   |
| OPENBSD             | 3        | 5      | 1.17%   |
| JetFlash            | 2        | 2      | 0.78%   |
| Hewlett-Packard     | 2        | 2      | 0.78%   |
| Fujitsu             | 2        | 2      | 0.78%   |
| WD MediaMax         | 1        | 2      | 0.39%   |
| Product:            | 1        | 1      | 0.39%   |
| Maxtor              | 1        | 1      | 0.39%   |
| LSI                 | 1        | 1      | 0.39%   |
| Intenso             | 1        | 1      | 0.39%   |
| IBM/Hitachi         | 1        | 1      | 0.39%   |
| IBM                 | 1        | 1      | 0.39%   |
| Generic             | 1        | 1      | 0.39%   |
| General             | 1        | 1      | 0.39%   |
| ASMT                | 1        | 1      | 0.39%   |
| Apple               | 1        | 1      | 0.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 156      | 248    | 17.09%  |
| Transcend           | 114      | 165    | 12.49%  |
| Kingston            | 82       | 134    | 8.98%   |
| SanDisk             | 71       | 103    | 7.78%   |
| Crucial             | 67       | 98     | 7.34%   |
| China               | 52       | 60     | 5.7%    |
| Intel               | 48       | 73     | 5.26%   |
| Phison              | 35       | 50     | 3.83%   |
| Intenso             | 30       | 48     | 3.29%   |
| Hoodisk             | 30       | 55     | 3.29%   |
| Innodisk            | 25       | 29     | 2.74%   |
| WDC                 | 16       | 17     | 1.75%   |
| Micron Technology   | 13       | 25     | 1.42%   |
| A-DATA Technology   | 13       | 16     | 1.42%   |
| Toshiba             | 12       | 15     | 1.31%   |
| FORESEE             | 11       | 15     | 1.2%    |
| OCZ                 | 10       | 14     | 1.1%    |
| Protectli           | 8        | 10     | 0.88%   |
| ATP                 | 8        | 8      | 0.88%   |
| Apacer              | 8        | 14     | 0.88%   |
| LITEONIT            | 6        | 8      | 0.66%   |
| Dogfish             | 6        | 7      | 0.66%   |
| TCSUNBOW            | 5        | 6      | 0.55%   |
| SPCC                | 5        | 9      | 0.55%   |
| ShiJi               | 5        | 6      | 0.55%   |
| Patriot             | 5        | 7      | 0.55%   |
| NVMe                | 5        | 8      | 0.55%   |
| Vaseky              | 4        | 4      | 0.44%   |
| Leven               | 4        | 6      | 0.44%   |
| KingDian            | 4        | 10     | 0.44%   |
| Verbatim            | 3        | 4      | 0.33%   |
| Team                | 3        | 3      | 0.33%   |
| Seagate             | 3        | 7      | 0.33%   |
| PNY                 | 3        | 3      | 0.33%   |
| MEMXPRO             | 3        | 4      | 0.33%   |
| LITEON              | 3        | 4      | 0.33%   |
| KingSpec            | 3        | 3      | 0.33%   |
| Corsair             | 3        | 7      | 0.33%   |
| BORY                | 3        | 6      | 0.33%   |
| Advantech           | 3        | 5      | 0.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 845      | 1344   | 69.66%  |
| HDD  | 208      | 435    | 17.15%  |
| NVMe | 160      | 251    | 13.19%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 969      | 1779   | 85.83%  |
| NVMe | 160      | 251    | 14.17%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 890      | 1393   | 82.33%  |
| 0.51-1.0        | 100      | 162    | 9.25%   |
| 1.01-2.0        | 42       | 104    | 3.89%   |
| 3.01-4.0        | 21       | 52     | 1.94%   |
| 2.01-3.0        | 12       | 33     | 1.11%   |
| 4.01-10.0       | 12       | 23     | 1.11%   |
| 10.01-20.0      | 3        | 11     | 0.28%   |
| More than 100.0 | 1        | 1      | 0.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 506      | 42.06%  |
| 1-20           | 170      | 14.13%  |
| 251-500        | 158      | 13.13%  |
| 21-50          | 152      | 12.64%  |
| 51-100         | 124      | 10.31%  |
| 501-1000       | 58       | 4.82%   |
| 1001-2000      | 12       | 1%      |
| More than 3000 | 11       | 0.91%   |
| 2001-3000      | 6        | 0.5%    |
| Unknown        | 6        | 0.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1119     | 92.48%  |
| 21-50          | 50       | 4.13%   |
| 51-100         | 13       | 1.07%   |
| 101-250        | 6        | 0.5%    |
| Unknown        | 6        | 0.5%    |
| 251-500        | 4        | 0.33%   |
| 1001-2000      | 4        | 0.33%   |
| 501-1000       | 4        | 0.33%   |
| More than 3000 | 2        | 0.17%   |
| 2001-3000      | 2        | 0.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| Kingston SV300S37A60G 64GB                   | 4        | 6      | 3.74%   |
| WDC WD2000FYYZ-01UL1B2 2TB                   | 3        | 5      | 2.8%    |
| Kingston SMS200S360G 64GB                    | 3        | 3      | 2.8%    |
| WDC WDS240G2G0A-00JH30 240GB                 | 2        | 3      | 1.87%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 2        | 7      | 1.87%   |
| WDC WD2000FYYZ-01UL1B1 2TB                   | 2        | 4      | 1.87%   |
| WDC WD1600AAJS-75M0A0 160GB                  | 2        | 2      | 1.87%   |
| Toshiba THNSNK128GCS8 SATA 128GB             | 2        | 2      | 1.87%   |
| Seagate ST3160318AS 160GB                    | 2        | 2      | 1.87%   |
| Seagate ST1000DX001-1CM162 1TB               | 2        | 2      | 1.87%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 2        | 4      | 1.87%   |
| Samsung Electronics HD501LJ 500GB            | 2        | 2      | 1.87%   |
| Micron Technology 1100_MTFDDAK512TBN 512GB   | 2        | 4      | 1.87%   |
| Kingston SMS200S3120G 120GB                  | 2        | 3      | 1.87%   |
| Intenso SSD SATAIII 256GB                    | 2        | 2      | 1.87%   |
| Intel SSDSC2CT120A3 120GB                    | 2        | 2      | 1.87%   |
| HGST HTS541010A7E630 1TB                     | 2        | 4      | 1.87%   |
| Crucial CT275MX300SSD1 275GB                 | 2        | 2      | 1.87%   |
| WDC WD60EFRX-68TGBN1 6TB                     | 1        | 3      | 0.93%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1        | 1      | 0.93%   |
| WDC WD2503ABYX-01WERA0 256GB                 | 1        | 2      | 0.93%   |
| WDC WD1600AAJS-08L7A0 160GB                  | 1        | 1      | 0.93%   |
| WDC WD1600AABS-00PRA0 160GB                  | 1        | 1      | 0.93%   |
| WDC WD10EZEX-60WN4A0 1TB                     | 1        | 1      | 0.93%   |
| WDC WD10EAVS-00D7B0 1TB                      | 1        | 1      | 0.93%   |
| WDC WD10EACS-00D6B1 1TB                      | 1        | 2      | 0.93%   |
| Transcend TS8GMSM610 8GB                     | 1        | 1      | 0.93%   |
| Toshiba MQ02ABD100H 1TB                      | 1        | 4      | 0.93%   |
| SPCC M.2 PCIe SSD 256GB                      | 1        | 1      | 0.93%   |
| SMI SSD DISK 120GB                           | 1        | 1      | 0.93%   |
| Seagate ST9500620NS 500GB                    | 1        | 1      | 0.93%   |
| Seagate ST9500325AS 500GB                    | 1        | 1      | 0.93%   |
| Seagate ST9320325AS 320GB                    | 1        | 1      | 0.93%   |
| Seagate ST9250827AS 250GB                    | 1        | 2      | 0.93%   |
| Seagate ST9160310AS 160GB                    | 1        | 2      | 0.93%   |
| Seagate ST500DM002-1BD142 500GB              | 1        | 2      | 0.93%   |
| Seagate ST4000NM0033-9ZM170 4TB              | 1        | 2      | 0.93%   |
| Seagate ST4000DM004-2CV104 4TB               | 1        | 1      | 0.93%   |
| Seagate ST380013AS 80GB                      | 1        | 1      | 0.93%   |
| Seagate ST3250410AS 250GB                    | 1        | 1      | 0.93%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 19       | 33     | 17.92%  |
| Seagate             | 19       | 25     | 17.92%  |
| Samsung Electronics | 11       | 14     | 10.38%  |
| Kingston            | 11       | 15     | 10.38%  |
| Intel               | 9        | 10     | 8.49%   |
| Crucial             | 7        | 18     | 6.6%    |
| Micron Technology   | 4        | 6      | 3.77%   |
| HGST                | 4        | 6      | 3.77%   |
| Toshiba             | 3        | 6      | 2.83%   |
| Hitachi             | 3        | 3      | 2.83%   |
| SanDisk             | 2        | 3      | 1.89%   |
| OCZ                 | 2        | 2      | 1.89%   |
| Intenso             | 2        | 2      | 1.89%   |
| Transcend           | 1        | 1      | 0.94%   |
| SPCC                | 1        | 1      | 0.94%   |
| SMI                 | 1        | 1      | 0.94%   |
| Maxtor              | 1        | 1      | 0.94%   |
| KingSpec            | 1        | 1      | 0.94%   |
| KingDian            | 1        | 3      | 0.94%   |
| Corsair             | 1        | 3      | 0.94%   |
| China               | 1        | 1      | 0.94%   |
| Apacer              | 1        | 1      | 0.94%   |
| A-DATA Technology   | 1        | 2      | 0.94%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 19       | 25     | 38.78%  |
| WDC                 | 17       | 30     | 34.69%  |
| Samsung Electronics | 4        | 5      | 8.16%   |
| HGST                | 4        | 6      | 8.16%   |
| Hitachi             | 3        | 3      | 6.12%   |
| Toshiba             | 1        | 4      | 2.04%   |
| Maxtor              | 1        | 1      | 2.04%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 55       | 82     | 52.88%  |
| HDD  | 47       | 74     | 45.19%  |
| NVMe | 2        | 2      | 1.92%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD3200BPVT-16JJ5T0 320GB      | 1        | 1      | 25%     |
| Transcend TS32GSSD370S 32GB       | 1        | 2      | 25%     |
| Samsung Electronics SSD 980 250GB | 1        | 2      | 25%     |
| Kingston SV300S37A60G 64GB        | 1        | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 25%     |
| Transcend           | 1        | 2      | 25%     |
| Samsung Electronics | 1        | 2      | 25%     |
| Kingston            | 1        | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 1003     | 1812   | 87.91%  |
| Malfunc  | 102      | 158    | 8.94%   |
| Detected | 32       | 54     | 2.8%    |
| Failed   | 4        | 6      | 0.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 814      | 58.6%   |
| AMD                            | 323      | 23.25%  |
| Samsung Electronics            | 53       | 3.82%   |
| Kingston Technology Company    | 26       | 1.87%   |
| SanDisk                        | 25       | 1.8%    |
| ASMedia Technology             | 25       | 1.8%    |
| Phison Electronics             | 19       | 1.37%   |
| Silicon Motion                 | 10       | 0.72%   |
| MAXIO Technology (Hangzhou)    | 10       | 0.72%   |
| Micron/Crucial Technology      | 9        | 0.65%   |
| Marvell Technology Group       | 9        | 0.65%   |
| Broadcom / LSI                 | 9        | 0.65%   |
| KIOXIA                         | 6        | 0.43%   |
| VIA Technologies               | 5        | 0.36%   |
| Toshiba                        | 5        | 0.36%   |
| Micron Technology              | 4        | 0.29%   |
| JMicron Technology             | 4        | 0.29%   |
| SK hynix                       | 3        | 0.22%   |
| Silicon Image                  | 3        | 0.22%   |
| Shenzhen Longsys Electronics   | 3        | 0.22%   |
| Nvidia                         | 3        | 0.22%   |
| Hewlett-Packard                | 3        | 0.22%   |
| Yangtze Memory Technologies    | 2        | 0.14%   |
| Realtek Semiconductor          | 2        | 0.14%   |
| Hosin Global Electronics       | 2        | 0.14%   |
| Adaptec                        | 2        | 0.14%   |
| ULi Electronics                | 1        | 0.07%   |
| Transcend                      | 1        | 0.07%   |
| Solid State Storage Technology | 1        | 0.07%   |
| Seagate Technology             | 1        | 0.07%   |
| Integrated Technology Express  | 1        | 0.07%   |
| Enmotus                        | 1        | 0.07%   |
| Chelsio Communications         | 1        | 0.07%   |
| Artop Electronic               | 1        | 0.07%   |
| 3ware                          | 1        | 0.07%   |
| Unknown                        | 1        | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 209      | 13.31%  |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 85       | 5.41%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 74       | 4.71%   |
| AMD FCH SATA Controller [IDE mode]                                               | 59       | 3.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 54       | 3.44%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 48       | 3.06%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 47       | 2.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 46       | 2.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 42       | 2.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 39       | 2.48%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 32       | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 32       | 2.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 31       | 1.97%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 28       | 1.78%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 26       | 1.66%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 24       | 1.53%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 24       | 1.53%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 23       | 1.46%   |
| AMD 400 Series Chipset SATA Controller                                           | 22       | 1.4%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 20       | 1.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 20       | 1.27%   |
| Intel Comet Lake SATA AHCI Controller                                            | 18       | 1.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 17       | 1.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 17       | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 17       | 1.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 14       | 0.89%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 14       | 0.89%   |
| Intel SATA Controller [RAID mode]                                                | 13       | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 13       | 0.83%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 11       | 0.7%    |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 11       | 0.7%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 10       | 0.64%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                     | 10       | 0.64%   |
| Intel Tiger Lake-LP SATA Controller                                              | 10       | 0.64%   |
| Intel Elkhart Lake SATA AHCI                                                     | 10       | 0.64%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10       | 0.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 10       | 0.64%   |
| Unknown                                                                          | 10       | 0.64%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 9        | 0.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 9        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1036     | 73.95%  |
| NVMe | 185      | 13.2%   |
| IDE  | 124      | 8.85%   |
| RAID | 43       | 3.07%   |
| SCSI | 8        | 0.57%   |
| SAS  | 5        | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 836      | 71.09%  |
| AMD     | 328      | 27.89%  |
| ARM     | 8        | 0.68%   |
| VIA     | 2        | 0.17%   |
| Sun     | 1        | 0.09%   |
| Unknown | 1        | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| AMD GX-412TC SOC                          | 114      | 9.64%   |
| Intel Celeron J4125 CPU @ 2.00GHz         | 54       | 4.56%   |
| Intel Celeron N5105 @ 2.00GHz             | 41       | 3.47%   |
| AMD GX-415GA SOC with Radeon HD Graphics  | 32       | 2.7%    |
| Intel Celeron CPU J3160 @ 1.60GHz         | 27       | 2.28%   |
| Intel Celeron CPU J1900 @ 1.99GHz         | 25       | 2.11%   |
| AMD GX-222GC SOC with Radeon R5E Graphics | 22       | 1.86%   |
| Intel Atom CPU D525 @ 1.80GHz             | 16       | 1.35%   |
| Intel Core i5-6500 CPU @ 3.20GHz          | 14       | 1.18%   |
| AMD G-T40E Processor                      | 14       | 1.18%   |
| Intel Core i5-7200U CPU @ 2.50GHz         | 13       | 1.1%    |
| Intel Celeron J4105 CPU @ 1.50GHz         | 12       | 1.01%   |
| Intel Core i7-7500U CPU @ 2.70GHz         | 11       | 0.93%   |
| Intel Celeron CPU J3455 @ 1.50GHz         | 11       | 0.93%   |
| Intel Core i5-3470 CPU @ 3.20GHz          | 10       | 0.85%   |
| AMD GX-424CC SOC with Radeon R5E Graphics | 10       | 0.85%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz        | 9        | 0.76%   |
| Intel Celeron J4115 CPU @ 1.80GHz         | 9        | 0.76%   |
| Intel Celeron CPU N3150 @ 1.60GHz         | 9        | 0.76%   |
| Intel N100                                | 8        | 0.68%   |
| Intel Core i5-8365U CPU @ 1.60GHz         | 8        | 0.68%   |
| Intel Core i5-8250U CPU @ 1.60GHz         | 8        | 0.68%   |
| Intel Atom CPU C3558 @ 2.20GHz            | 8        | 0.68%   |
| AMD GX-420CA SOC with Radeon HD Graphics  | 8        | 0.68%   |
| Intel Core i7-7700 CPU @ 3.60GHz          | 7        | 0.59%   |
| Intel Core i3-7100U CPU @ 2.40GHz         | 7        | 0.59%   |
| Intel Celeron J6412 @ 2.00GHz             | 7        | 0.59%   |
| Intel Celeron CPU N3450 @ 1.10GHz         | 7        | 0.59%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz   | 7        | 0.59%   |
| Intel Pentium Silver N6005 @ 2.00GHz      | 6        | 0.51%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz  | 6        | 0.51%   |
| Intel Core i7-8550U CPU @ 1.80GHz         | 6        | 0.51%   |
| Intel Celeron CPU N3160 @ 1.60GHz         | 6        | 0.51%   |
| Intel Celeron CPU 3865U @ 1.80GHz         | 6        | 0.51%   |
| Intel Atom CPU E3845 @ 1.91GHz            | 6        | 0.51%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz       | 5        | 0.42%   |
| Intel Core i7-4770 CPU @ 3.40GHz          | 5        | 0.42%   |
| Intel Core i7-3770 CPU @ 3.40GHz          | 5        | 0.42%   |
| Intel Core i5-8265U CPU @ 1.60GHz         | 5        | 0.42%   |
| Intel Core i5-6500T CPU @ 2.50GHz         | 5        | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 271      | 22.93%  |
| AMD GX                  | 197      | 16.67%  |
| Intel Core i5           | 180      | 15.23%  |
| Intel Core i3           | 91       | 7.7%    |
| Intel Core i7           | 73       | 6.18%   |
| Intel Xeon              | 67       | 5.67%   |
| Intel Atom              | 57       | 4.82%   |
| Other                   | 42       | 3.55%   |
| AMD Ryzen 7             | 25       | 2.12%   |
| AMD Ryzen 5             | 21       | 1.78%   |
| AMD G                   | 19       | 1.61%   |
| Intel Pentium Silver    | 18       | 1.52%   |
| Intel Pentium           | 15       | 1.27%   |
| AMD FX                  | 15       | 1.27%   |
| Intel Core 2 Quad       | 10       | 0.85%   |
| Intel Core 2 Duo        | 7        | 0.59%   |
| Intel Pentium Dual-Core | 6        | 0.51%   |
| AMD Ryzen 5 PRO         | 6        | 0.51%   |
| Intel Pentium Gold      | 5        | 0.42%   |
| AMD Ryzen 9             | 5        | 0.42%   |
| AMD Ryzen 3             | 5        | 0.42%   |
| ARM Cortex              | 4        | 0.34%   |
| AMD E                   | 4        | 0.34%   |
| Intel Core i9           | 3        | 0.25%   |
| AMD Turion II Neo       | 3        | 0.25%   |
| AMD Ryzen Embedded      | 3        | 0.25%   |
| AMD Ryzen 7 PRO         | 3        | 0.25%   |
| AMD Athlon 64 X2        | 3        | 0.25%   |
| AMD Athlon              | 3        | 0.25%   |
| AMD A10                 | 3        | 0.25%   |
| AMD Ryzen Threadripper  | 2        | 0.17%   |
| AMD Athlon Dual Core    | 2        | 0.17%   |
| AMD A8                  | 2        | 0.17%   |
| AMD A4                  | 2        | 0.17%   |
| Intel Xeon Gold         | 1        | 0.08%   |
| Intel Pentium Dual      | 1        | 0.08%   |
| Intel Pentium 4         | 1        | 0.08%   |
| Intel Core 2            | 1        | 0.08%   |
| Intel 686-class         | 1        | 0.08%   |
| AMD Phenom II X4        | 1        | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 700      | 59.22%  |
| 2       | 301      | 25.47%  |
| 6       | 45       | 3.81%   |
| 8       | 41       | 3.47%   |
| 16      | 32       | 2.71%   |
| Unknown | 27       | 2.28%   |
| 12      | 19       | 1.61%   |
| 1       | 10       | 0.85%   |
| 32      | 5        | 0.42%   |
| 36      | 1        | 0.08%   |
| 10      | 1        | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1147     | 97.78%  |
| Unknown | 15       | 1.28%   |
| 2       | 11       | 0.94%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 810      | 68.99%  |
| 2       | 336      | 28.62%  |
| Unknown | 28       | 2.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Puma          | 152      | 12.87%  |
| KabyLake      | 152      | 12.87%  |
| Unknown       | 107      | 9.06%   |
| Silvermont    | 89       | 7.54%   |
| Goldmont plus | 87       | 7.37%   |
| Haswell       | 80       | 6.77%   |
| Skylake       | 64       | 5.42%   |
| IvyBridge     | 58       | 4.91%   |
| Jaguar        | 48       | 4.06%   |
| Goldmont      | 35       | 2.96%   |
| Bonnell       | 35       | 2.96%   |
| SandyBridge   | 28       | 2.37%   |
| Penryn        | 28       | 2.37%   |
| Bobcat        | 23       | 1.95%   |
| Zen+          | 21       | 1.78%   |
| Zen 2         | 20       | 1.69%   |
| Zen           | 19       | 1.61%   |
| CometLake     | 18       | 1.52%   |
| Piledriver    | 15       | 1.27%   |
| Core          | 14       | 1.19%   |
| Westmere      | 12       | 1.02%   |
| TigerLake     | 12       | 1.02%   |
| Broadwell     | 12       | 1.02%   |
| Zen 3         | 11       | 0.93%   |
| Nehalem       | 11       | 0.93%   |
| IceLake       | 9        | 0.76%   |
| K8 Hammer     | 6        | 0.51%   |
| K10           | 5        | 0.42%   |
| Bulldozer     | 4        | 0.34%   |
| Excavator     | 2        | 0.17%   |
| Steamroller   | 1        | 0.08%   |
| NetBurst      | 1        | 0.08%   |
| K10 Llano     | 1        | 0.08%   |
| Geode         | 1        | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 706      | 69.35%  |
| AMD                                          | 174      | 17.09%  |
| Nvidia                                       | 77       | 7.56%   |
| ASPEED Technology                            | 34       | 3.34%   |
| Matrox Electronics Systems                   | 24       | 2.36%   |
| VIA Technologies                             | 2        | 0.2%    |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel GeminiLake [UHD Graphics 600]                                                      | 77       | 7.49%   |
| Intel JasperLake [UHD Graphics]                                                          | 57       | 5.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 47       | 4.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 41       | 3.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 37       | 3.6%    |
| Intel HD Graphics 620                                                                    | 34       | 3.31%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 34       | 3.31%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 32       | 3.11%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 32       | 3.11%   |
| Intel HD Graphics 530                                                                    | 29       | 2.82%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 24       | 2.33%   |
| Intel HD Graphics 500                                                                    | 23       | 2.24%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 22       | 2.14%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 21       | 2.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 18       | 1.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17       | 1.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15       | 1.46%   |
| Intel UHD Graphics 620                                                                   | 14       | 1.36%   |
| Intel HD Graphics 630                                                                    | 13       | 1.26%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 13       | 1.26%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 13       | 1.26%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 12       | 1.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11       | 1.07%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11       | 1.07%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 10       | 0.97%   |
| Matrox Electronics Systems MGA G200EH                                                    | 10       | 0.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10       | 0.97%   |
| Intel HD Graphics 610                                                                    | 10       | 0.97%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 10       | 0.97%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 10       | 0.97%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 10       | 0.97%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 9        | 0.88%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9        | 0.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9        | 0.88%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9        | 0.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9        | 0.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8        | 0.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8        | 0.78%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 8        | 0.78%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 7        | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 665      | 56.5%   |
| Other          | 172      | 14.61%  |
| 1 x AMD        | 172      | 14.61%  |
| 1 x Nvidia     | 69       | 5.86%   |
| 1 x ASPEED     | 31       | 2.63%   |
| 2 x Intel      | 28       | 2.38%   |
| 1 x Matrox     | 23       | 1.95%   |
| Intel + Nvidia | 8        | 0.68%   |
| Intel + ASPEED | 3        | 0.25%   |
| 1 x VIA        | 2        | 0.17%   |
| 2 x AMD        | 1        | 0.08%   |
| 1 x XGI        | 1        | 0.08%   |
| Intel + Matrox | 1        | 0.08%   |
| Intel + AMD    | 1        | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 944      | 80.41%  |
| Unknown     | 179      | 15.25%  |
| Proprietary | 51       | 4.34%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1096     | 92.72%  |
| 1.01-2.0   | 29       | 2.45%   |
| 3.01-4.0   | 14       | 1.18%   |
| 0.01-0.5   | 11       | 0.93%   |
| 0.51-1.0   | 10       | 0.85%   |
| 7.01-8.0   | 9        | 0.76%   |
| 5.01-6.0   | 9        | 0.76%   |
| 2.01-3.0   | 4        | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 20       | 15.63%  |
| Goldstar             | 13       | 10.16%  |
| Dell                 | 12       | 9.38%   |
| BenQ                 | 12       | 9.38%   |
| Acer                 | 10       | 7.81%   |
| Hewlett-Packard      | 8        | 6.25%   |
| Eizo                 | 7        | 5.47%   |
| Ancor Communications | 7        | 5.47%   |
| LG Electronics       | 6        | 4.69%   |
| Iiyama               | 6        | 4.69%   |
| Fujitsu Siemens      | 5        | 3.91%   |
| NEC Computers        | 4        | 3.13%   |
| Philips              | 3        | 2.34%   |
| Idek Iiyama          | 3        | 2.34%   |
| HannStar             | 2        | 1.56%   |
| ASUSTek Computer     | 2        | 1.56%   |
| AOC                  | 2        | 1.56%   |
| WYT                  | 1        | 0.78%   |
| Mi                   | 1        | 0.78%   |
| LG Display           | 1        | 0.78%   |
| Lenovo               | 1        | 0.78%   |
| CHD                  | 1        | 0.78%   |
| Belinea              | 1        | 0.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch            | 3        | 2.13%   |
| Fujitsu Siemens B24-9 WE FUS08C3 1920x1200 520x320mm 24.0-inch        | 3        | 2.13%   |
| Samsung Electronics C32JG5x SAM0FDE 2560x1440 700x390mm 31.5-inch     | 2        | 1.42%   |
| Hewlett-Packard LP2475w HWP26F9 1920x1200 540x350mm 25.3-inch         | 2        | 1.42%   |
| Hewlett-Packard LP2475w HWP26F8 1920x1200 540x350mm 25.3-inch         | 2        | 1.42%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 520x320mm 24.0-inch          | 2        | 1.42%   |
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch              | 2        | 1.42%   |
| Goldstar E2441 GSM581F 1920x1080 530x300mm 24.0-inch                  | 2        | 1.42%   |
| Eizo EV2450 ENC2530 1920x1080 530x300mm 24.0-inch                     | 2        | 1.42%   |
| Dell LCD Monitor U2412M 3840x1200                                     | 2        | 1.42%   |
| Dell LCD Monitor U2412M                                               | 2        | 1.42%   |
| BenQ GW2260 BNQ78C4 1920x1080 480x270mm 21.7-inch                     | 2        | 1.42%   |
| BenQ GL2760 BNQ78D5 1920x1080 600x340mm 27.2-inch                     | 2        | 1.42%   |
| BenQ GL2450H BNQ78A6 1920x1080 530x300mm 24.0-inch                    | 2        | 1.42%   |
| Ancor Communications MX27AQ ACI27A5 2560x1440 600x340mm 27.2-inch     | 2        | 1.42%   |
| WYT MNT-ANALOG WYT0323 1280x1024 330x270mm 16.8-inch                  | 1        | 0.71%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 1        | 0.71%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                      | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM036C 1920x1200 550x340mm 25.5-inch  | 1        | 0.71%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 600x340mm 27.2-inch   | 1        | 0.71%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 520x320mm 24.0-inch   | 1        | 0.71%   |
| Samsung Electronics SAMTRON STN0028 1280x1024 380x300mm 19.1-inch     | 1        | 0.71%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 480x270mm 21.7-inch | 1        | 0.71%   |
| Samsung Electronics S24C650 SAM09E9 1920x1080 520x290mm 23.4-inch     | 1        | 0.71%   |
| Samsung Electronics S24C650 SAM09E8 1920x1080 520x290mm 23.4-inch     | 1        | 0.71%   |
| Samsung Electronics S24C650 SAM09E7 1920x1080 520x290mm 23.4-inch     | 1        | 0.71%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 480x270mm 21.7-inch     | 1        | 0.71%   |
| Samsung Electronics LCD Monitor T27C370 1920x1080                     | 1        | 0.71%   |
| Samsung Electronics LCD Monitor SMB2430L 1920x1080                    | 1        | 0.71%   |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 890x500mm 40.2-inch | 1        | 0.71%   |
| Samsung Electronics LCD Monitor S22C300 1920x1080                     | 1        | 0.71%   |
| Samsung Electronics LCD Monitor CF791 3440x1440                       | 1        | 0.71%   |
| Samsung Electronics CF791 SAM0DC3 3440x1440 800x330mm 34.1-inch       | 1        | 0.71%   |
| Samsung Electronics C27FG7x SAM0E42 1920x1080 600x340mm 27.2-inch     | 1        | 0.71%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 600x340mm 27.2-inch     | 1        | 0.71%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 1        | 0.71%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch               | 1        | 0.71%   |
| Philips LCD Monitor PHL086D 1440x900 400x250mm 18.6-inch              | 1        | 0.71%   |
| Philips LCD Monitor PHL 243V7 3840x1080                               | 1        | 0.71%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 54       | 41.86%  |
| 2560x1440 (QHD)    | 17       | 13.18%  |
| 3840x2160 (4K)     | 15       | 11.63%  |
| 1920x1200 (WUXGA)  | 15       | 11.63%  |
| 1280x1024 (SXGA)   | 8        | 6.2%    |
| 3440x1440          | 4        | 3.1%    |
| 1680x1050 (WSXGA+) | 4        | 3.1%    |
| Unknown            | 3        | 2.33%   |
| 3840x1200          | 2        | 1.55%   |
| 2560x1080          | 2        | 1.55%   |
| 1440x900 (WXGA+)   | 2        | 1.55%   |
| 3840x1080          | 1        | 0.78%   |
| 3600x1080          | 1        | 0.78%   |
| 1366x768 (WXGA)    | 1        | 0.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 31       | 24.22%  |
| 24      | 28       | 21.88%  |
| Unknown | 19       | 14.84%  |
| 23      | 12       | 9.38%   |
| 21      | 12       | 9.38%   |
| 19      | 6        | 4.69%   |
| 34      | 4        | 3.13%   |
| 22      | 4        | 3.13%   |
| 31      | 3        | 2.34%   |
| 25      | 3        | 2.34%   |
| 46      | 1        | 0.78%   |
| 32      | 1        | 0.78%   |
| 18      | 1        | 0.78%   |
| 17      | 1        | 0.78%   |
| 16      | 1        | 0.78%   |
| 13      | 1        | 0.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 70       | 55.12%  |
| Unknown     | 19       | 14.96%  |
| 401-500     | 16       | 12.6%   |
| 601-700     | 7        | 5.51%   |
| 351-400     | 6        | 4.72%   |
| 701-800     | 5        | 3.94%   |
| 301-350     | 3        | 2.36%   |
| 1001-1500   | 1        | 0.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 75       | 60%     |
| 16/10   | 19       | 15.2%   |
| Unknown | 18       | 14.4%   |
| 5/4     | 6        | 4.8%    |
| 21/9    | 4        | 3.2%    |
| 3/2     | 2        | 1.6%    |
| 6/5     | 1        | 0.8%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 42       | 33.07%  |
| 301-350        | 31       | 24.41%  |
| Unknown        | 19       | 14.96%  |
| 251-300        | 16       | 12.6%   |
| 351-500        | 8        | 6.3%    |
| 151-200        | 7        | 5.51%   |
| 81-90          | 1        | 0.79%   |
| 141-150        | 1        | 0.79%   |
| 131-140        | 1        | 0.79%   |
| 501-1000       | 1        | 0.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 71       | 55.47%  |
| 101-120 | 24       | 18.75%  |
| Unknown | 19       | 14.84%  |
| 161-240 | 8        | 6.25%   |
| 121-160 | 5        | 3.91%   |
| 1-50    | 1        | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1047     | 89.03%  |
| 1     | 115      | 9.78%   |
| 2     | 13       | 1.11%   |
| 3     | 1        | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 932      | 59.9%   |
| Realtek Semiconductor             | 402      | 25.84%  |
| Qualcomm Atheros                  | 64       | 4.11%   |
| Broadcom                          | 53       | 3.41%   |
| IMC Networks                      | 14       | 0.9%    |
| Mellanox Technologies             | 11       | 0.71%   |
| TP-Link                           | 7        | 0.45%   |
| American Megatrends               | 7        | 0.45%   |
| U-Blox                            | 6        | 0.39%   |
| D-Link System                     | 6        | 0.39%   |
| Marvell Technology Group          | 5        | 0.32%   |
| Ralink Technology                 | 4        | 0.26%   |
| Ralink                            | 4        | 0.26%   |
| MediaTek                          | 4        | 0.26%   |
| Edimax Technology                 | 4        | 0.26%   |
| Chelsio Communications            | 3        | 0.19%   |
| Aquantia                          | 3        | 0.19%   |
| ICS Advent                        | 2        | 0.13%   |
| Emulex                            | 2        | 0.13%   |
| Dresden Elektronik                | 2        | 0.13%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.06%   |
| Xiaomi                            | 1        | 0.06%   |
| T & A Mobile Phones               | 1        | 0.06%   |
| SysKonnect                        | 1        | 0.06%   |
| Standard Microsystems [SMC]       | 1        | 0.06%   |
| Samsung Electronics               | 1        | 0.06%   |
| Qualcomm Atheros Communications   | 1        | 0.06%   |
| QLogic                            | 1        | 0.06%   |
| Oculus VR                         | 1        | 0.06%   |
| NetXen Incorporated               | 1        | 0.06%   |
| Motorola                          | 1        | 0.06%   |
| Huawei Technologies               | 1        | 0.06%   |
| Ericsson Business Mobile Networks | 1        | 0.06%   |
| Digium                            | 1        | 0.06%   |
| Digital Equipment                 | 1        | 0.06%   |
| Dell                              | 1        | 0.06%   |
| Davicom Semiconductor             | 1        | 0.06%   |
| AVM                               | 1        | 0.06%   |
| ASUSTek Computer                  | 1        | 0.06%   |
| Apple                             | 1        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 352      | 19.02%  |
| Intel I211 Gigabit Network Connection                                         | 242      | 13.07%  |
| Intel I210 Gigabit Network Connection                                         | 147      | 7.94%   |
| Intel Ethernet Controller I225-V                                              | 89       | 4.81%   |
| Intel I350 Gigabit Network Connection                                         | 66       | 3.57%   |
| Intel 82574L Gigabit Network Connection                                       | 60       | 3.24%   |
| Intel Ethernet Controller I226-V                                              | 46       | 2.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 35       | 1.89%   |
| Intel 82580 Gigabit Network Connection                                        | 34       | 1.84%   |
| Realtek RTL8125 2.5GbE Controller                                             | 29       | 1.57%   |
| Intel 82576 Gigabit Network Connection                                        | 29       | 1.57%   |
| Intel 82583V Gigabit Network Connection                                       | 26       | 1.4%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 25       | 1.35%   |
| Intel Ethernet Connection (2) I219-V                                          | 20       | 1.08%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 20       | 1.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 18       | 0.97%   |
| Intel Wi-Fi 6 AX200                                                           | 18       | 0.97%   |
| Intel Ethernet Connection I217-LM                                             | 17       | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                                         | 14       | 0.76%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 13       | 0.7%    |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 13       | 0.7%    |
| Intel I210 Gigabit Fiber Network Connection                                   | 11       | 0.59%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 11       | 0.59%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 11       | 0.59%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 10       | 0.54%   |
| Intel Ethernet Connection (7) I219-V                                          | 10       | 0.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 9        | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 9        | 0.49%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 9        | 0.49%   |
| Intel Ethernet Controller X550                                                | 9        | 0.49%   |
| Intel Ethernet Connection X553 1GbE                                           | 9        | 0.49%   |
| Intel Ethernet Connection I219-LM                                             | 9        | 0.49%   |
| Intel Ethernet Connection I217-V                                              | 9        | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                                         | 9        | 0.49%   |
| Intel Centrino Advanced-N 6235                                                | 9        | 0.49%   |
| Intel 82579V Gigabit Network Connection                                       | 9        | 0.49%   |
| Intel Wireless-AC 9260                                                        | 7        | 0.38%   |
| American Megatrends Virtual Ethernet                                          | 7        | 0.38%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 6        | 0.32%   |
| Intel Wireless 7265                                                           | 6        | 0.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 87       | 36.86%  |
| Qualcomm Atheros                | 55       | 23.31%  |
| Realtek Semiconductor           | 42       | 17.8%   |
| IMC Networks                    | 14       | 5.93%   |
| Broadcom                        | 11       | 4.66%   |
| TP-Link                         | 7        | 2.97%   |
| Ralink Technology               | 4        | 1.69%   |
| Ralink                          | 4        | 1.69%   |
| MediaTek                        | 4        | 1.69%   |
| Edimax Technology               | 4        | 1.69%   |
| Qualcomm Atheros Communications | 1        | 0.42%   |
| Dell                            | 1        | 0.42%   |
| ASUSTek Computer                | 1        | 0.42%   |
| Accton Technology               | 1        | 0.42%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 18       | 7.53%   |
| Intel Wi-Fi 6 AX200                                                     | 18       | 7.53%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 13       | 5.44%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 10       | 4.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9        | 3.77%   |
| Intel Centrino Advanced-N 6235                                          | 9        | 3.77%   |
| Intel Wireless-AC 9260                                                  | 7        | 2.93%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 6        | 2.51%   |
| Intel Wireless 7265                                                     | 6        | 2.51%   |
| Intel Wireless 7260                                                     | 6        | 2.51%   |
| Intel Wireless 3160                                                     | 6        | 2.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6        | 2.51%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 4        | 1.67%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter         | 4        | 1.67%   |
| Intel Wireless 3165                                                     | 4        | 1.67%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 3        | 1.26%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                         | 3        | 1.26%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3        | 1.26%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 3        | 1.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3        | 1.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3        | 1.26%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3        | 1.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3        | 1.26%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 3        | 1.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3        | 1.26%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 3        | 1.26%   |
| Intel CNVi: Wi-Fi                                                       | 3        | 1.26%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter            | 3        | 1.26%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2        | 0.84%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 2        | 0.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2        | 0.84%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                  | 2        | 0.84%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2        | 0.84%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 2        | 0.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2        | 0.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2        | 0.84%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 2        | 0.84%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2        | 0.84%   |
| Intel Wireless 8265 / 8275                                              | 2        | 0.84%   |
| Intel Wireless 8260                                                     | 2        | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 891      | 65.47%  |
| Realtek Semiconductor       | 386      | 28.36%  |
| Broadcom                    | 43       | 3.16%   |
| Qualcomm Atheros            | 9        | 0.66%   |
| American Megatrends         | 7        | 0.51%   |
| Marvell Technology Group    | 5        | 0.37%   |
| D-Link System               | 4        | 0.29%   |
| Aquantia                    | 3        | 0.22%   |
| ICS Advent                  | 2        | 0.15%   |
| Xiaomi                      | 1        | 0.07%   |
| T & A Mobile Phones         | 1        | 0.07%   |
| SysKonnect                  | 1        | 0.07%   |
| Standard Microsystems [SMC] | 1        | 0.07%   |
| Samsung Electronics         | 1        | 0.07%   |
| QLogic                      | 1        | 0.07%   |
| Emulex                      | 1        | 0.07%   |
| Digital Equipment           | 1        | 0.07%   |
| Davicom Semiconductor       | 1        | 0.07%   |
| Chelsio Communications      | 1        | 0.07%   |
| Apple                       | 1        | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 352      | 22.42%  |
| Intel I211 Gigabit Network Connection                                         | 242      | 15.41%  |
| Intel I210 Gigabit Network Connection                                         | 147      | 9.36%   |
| Intel Ethernet Controller I225-V                                              | 89       | 5.67%   |
| Intel I350 Gigabit Network Connection                                         | 66       | 4.2%    |
| Intel 82574L Gigabit Network Connection                                       | 60       | 3.82%   |
| Intel Ethernet Controller I226-V                                              | 46       | 2.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 35       | 2.23%   |
| Intel 82580 Gigabit Network Connection                                        | 34       | 2.17%   |
| Intel 82576 Gigabit Network Connection                                        | 29       | 1.85%   |
| Realtek RTL8125 2.5GbE Controller                                             | 28       | 1.78%   |
| Intel 82583V Gigabit Network Connection                                       | 26       | 1.66%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 25       | 1.59%   |
| Intel Ethernet Connection (2) I219-V                                          | 20       | 1.27%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 20       | 1.27%   |
| Intel Ethernet Connection I217-LM                                             | 17       | 1.08%   |
| Intel Ethernet Connection (2) I219-LM                                         | 14       | 0.89%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 13       | 0.83%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 11       | 0.7%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 11       | 0.7%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 11       | 0.7%    |
| Intel Ethernet Connection (7) I219-V                                          | 10       | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 9        | 0.57%   |
| Intel Ethernet Controller X550                                                | 9        | 0.57%   |
| Intel Ethernet Connection X553 1GbE                                           | 9        | 0.57%   |
| Intel Ethernet Connection I219-LM                                             | 9        | 0.57%   |
| Intel Ethernet Connection I217-V                                              | 9        | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                                         | 9        | 0.57%   |
| Intel 82579V Gigabit Network Connection                                       | 9        | 0.57%   |
| American Megatrends Virtual Ethernet                                          | 7        | 0.45%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 6        | 0.38%   |
| Intel Ethernet Connection (14) I219-V                                         | 6        | 0.38%   |
| Intel 82575EB Gigabit Network Connection                                      | 6        | 0.38%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 5        | 0.32%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 5        | 0.32%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 5        | 0.32%   |
| Intel 82578DM Gigabit Network Connection                                      | 5        | 0.32%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 4        | 0.25%   |
| Intel Ethernet Connection (5) I219-LM                                         | 4        | 0.25%   |
| Intel Ethernet Connection (17) I219-V                                         | 4        | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1162     | 81.54%  |
| WiFi     | 224      | 15.72%  |
| Unknown  | 27       | 1.89%   |
| Modem    | 12       | 0.84%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1143     | 98.11%  |
| WiFi     | 21       | 1.8%    |
| Unknown  | 1        | 0.09%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 4     | 266      | 22.28%  |
| 3     | 215      | 18.01%  |
| 2     | 177      | 14.82%  |
| 1     | 171      | 14.32%  |
| 6     | 155      | 12.98%  |
| 5     | 122      | 10.22%  |
| 8     | 24       | 2.01%   |
| 7     | 21       | 1.76%   |
| 10    | 14       | 1.17%   |
| 9     | 12       | 1.01%   |
| 0     | 10       | 0.84%   |
| 12    | 2        | 0.17%   |
| 11    | 2        | 0.17%   |
| 20    | 1        | 0.08%   |
| 17    | 1        | 0.08%   |
| 14    | 1        | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 939      | 76.22%  |
| Yes  | 293      | 23.78%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 78       | 61.42%  |
| Qualcomm Atheros Communications | 11       | 8.66%   |
| Realtek Semiconductor           | 10       | 7.87%   |
| IMC Networks                    | 9        | 7.09%   |
| ASUSTek Computer                | 5        | 3.94%   |
| Broadcom                        | 4        | 3.15%   |
| Apple                           | 4        | 3.15%   |
| MediaTek                        | 3        | 2.36%   |
| Micro Star International        | 1        | 0.79%   |
| Foxconn / Hon Hai               | 1        | 0.79%   |
| Cambridge Silicon Radio         | 1        | 0.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                          | 23       | 17.97%  |
| Intel AX200 Bluetooth                                       | 19       | 14.84%  |
| Intel Centrino Bluetooth Wireless Transceiver               | 11       | 8.59%   |
| Realtek Bluetooth Adapter                                   | 8        | 6.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 7        | 5.47%   |
| Intel Wireless-AC 3168 Bluetooth                            | 6        | 4.69%   |
| Intel AX201 Bluetooth                                       | 6        | 4.69%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 6        | 4.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5        | 3.91%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 4        | 3.13%   |
| MediaTek RZ608 Bluetooth Adapter                            | 3        | 2.34%   |
| Apple Bluetooth Host Controller                             | 3        | 2.34%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 2        | 1.56%   |
| Intel AX210 Bluetooth                                       | 2        | 1.56%   |
| Broadcom BCM2045 Bluetooth                                  | 2        | 1.56%   |
| ASUS USB-BT500                                              | 2        | 1.56%   |
| Realtek RTL8723A Bluetooth                                  | 1        | 0.78%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1        | 0.78%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1        | 0.78%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1        | 0.78%   |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1        | 0.78%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1        | 0.78%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1        | 0.78%   |
| Micro Star International MS-6970 BToes Bluetooth adapter    | 1        | 0.78%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1        | 0.78%   |
| IMC Networks Realtek Bluetooth 4.0 Adapter                  | 1        | 0.78%   |
| IMC Networks Bluetooth                                      | 1        | 0.78%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1        | 0.78%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1        | 0.78%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 1        | 0.78%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                        | 1        | 0.78%   |
| ASUS Realtek Bluetooth 4.0 + High Speed Chip                | 1        | 0.78%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1        | 0.78%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE       | 1        | 0.78%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1        | 0.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 614      | 65.67%  |
| AMD                                          | 198      | 21.18%  |
| Nvidia                                       | 69       | 7.38%   |
| C-Media Electronics                          | 13       | 1.39%   |
| Logitech                                     | 5        | 0.53%   |
| Zoran Co. Personal Media Division (Nogatech) | 4        | 0.43%   |
| JMTek                                        | 4        | 0.43%   |
| VIA Technologies                             | 3        | 0.32%   |
| Tenx Technology                              | 3        | 0.32%   |
| Creative Labs                                | 3        | 0.32%   |
| Texas Instruments                            | 2        | 0.21%   |
| Kingston Technology                          | 2        | 0.21%   |
| GN Netcom                                    | 2        | 0.21%   |
| ZOOM                                         | 1        | 0.11%   |
| Yamaha                                       | 1        | 0.11%   |
| Trust                                        | 1        | 0.11%   |
| RME                                          | 1        | 0.11%   |
| Native Instruments                           | 1        | 0.11%   |
| M-Audio                                      | 1        | 0.11%   |
| Generalplus Technology                       | 1        | 0.11%   |
| DSEA A/S                                     | 1        | 0.11%   |
| Creative Technology                          | 1        | 0.11%   |
| Corsair                                      | 1        | 0.11%   |
| Blue Microphones                             | 1        | 0.11%   |
| AudioQuest                                   | 1        | 0.11%   |
| Audient                                      | 1        | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| AMD Kabini HDMI/DP Audio                                                                          | 79       | 7.16%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 72       | 6.53%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 60       | 5.44%   |
| AMD FCH Azalia Controller                                                                         | 59       | 5.35%   |
| Intel Jasper Lake HD Audio                                                                        | 57       | 5.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 42       | 3.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 39       | 3.54%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 36       | 3.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 31       | 2.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 30       | 2.72%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 26       | 2.36%   |
| Intel Cannon Lake PCH cAVS                                                                        | 24       | 2.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 22       | 1.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 22       | 1.99%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 21       | 1.9%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 19       | 1.72%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 18       | 1.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 18       | 1.63%   |
| Intel 200 Series PCH HD Audio                                                                     | 18       | 1.63%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 18       | 1.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 18       | 1.63%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 17       | 1.54%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14       | 1.27%   |
| Intel 8 Series HD Audio Controller                                                                | 13       | 1.18%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 12       | 1.09%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12       | 1.09%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 11       | 1%      |
| Intel Alder Lake-N HD Graphics SGPC                                                               | 11       | 1%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11       | 1%      |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10       | 0.91%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10       | 0.91%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 10       | 0.91%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 9        | 0.82%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 9        | 0.82%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 9        | 0.82%   |
| Intel Broadwell-U Audio Controller                                                                | 9        | 0.82%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9        | 0.82%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7        | 0.63%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 7        | 0.63%   |
| AMD Wrestler HDMI Audio                                                                           | 7        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Samsung Electronics        | 202      | 17.18%  |
| Unknown                    | 176      | 14.97%  |
| Crucial                    | 159      | 13.52%  |
| Kingston                   | 133      | 11.31%  |
| SK hynix                   | 104      | 8.84%   |
| Micron Technology          | 91       | 7.74%   |
| G.Skill                    | 73       | 6.21%   |
| Corsair                    | 51       | 4.34%   |
| Unknown                    | 36       | 3.06%   |
| ATP                        | 19       | 1.62%   |
| Unknown (ABCD)             | 17       | 1.45%   |
| Nanya Technology           | 16       | 1.36%   |
| Transcend                  | 11       | 0.94%   |
| A-DATA Technology          | 10       | 0.85%   |
| Apacer                     | 9        | 0.77%   |
| Ramaxel Technology         | 7        | 0.6%    |
| Kimtigo                    | 6        | 0.51%   |
| Hewlett-Packard            | 5        | 0.43%   |
| Shenzhen Jinge Information | 4        | 0.34%   |
| Patriot                    | 4        | 0.34%   |
| Wodposit                   | 3        | 0.26%   |
| Avant                      | 3        | 0.26%   |
| Unknown (AB)               | 2        | 0.17%   |
| Unknown (09C7)             | 2        | 0.17%   |
| Teikon                     | 2        | 0.17%   |
| Innodisk                   | 2        | 0.17%   |
| GeIL                       | 2        | 0.17%   |
| Elpida                     | 2        | 0.17%   |
| Vasekey                    | 1        | 0.09%   |
| Unknown (8A5D)             | 1        | 0.09%   |
| Unknown (8A02)             | 1        | 0.09%   |
| Unknown (89EC)             | 1        | 0.09%   |
| Unknown (7F7F7F94FFFFFFFF) | 1        | 0.09%   |
| Unknown (0x1636)           | 1        | 0.09%   |
| Unknown (0x0C26)           | 1        | 0.09%   |
| Unknown (0B38)             | 1        | 0.09%   |
| Unknown (07FB)             | 1        | 0.09%   |
| Timetec                    | 1        | 0.09%   |
| Tigo                       | 1        | 0.09%   |
| TakeMS                     | 1        | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 48       | 3.86%   |
| Unknown                                                        | 36       | 2.89%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 17       | 1.37%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 16       | 1.29%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 12       | 0.96%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s          | 11       | 0.88%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 10       | 0.8%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 10       | 0.8%    |
| Micron RAM Module 8GB Row Of Chips LPDDR4 3200MT/s             | 10       | 0.8%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s          | 9        | 0.72%   |
| ATP RAM X4G08QA8BNWESO-7-TO1 8GB SODIMM DDR4 3200MT/s          | 9        | 0.72%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 8        | 0.64%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 8        | 0.64%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                     | 7        | 0.56%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 7        | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 7        | 0.56%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1333MT/s            | 7        | 0.56%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s           | 7        | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                     | 6        | 0.48%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 6        | 0.48%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 6        | 0.48%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 3200MT/s           | 6        | 0.48%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 6        | 0.48%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s              | 6        | 0.48%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s          | 6        | 0.48%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 5        | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                     | 5        | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                    | 5        | 0.4%    |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 5        | 0.4%    |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 5        | 0.4%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 5        | 0.4%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s          | 5        | 0.4%    |
| Kingston RAM KHX2400C14S4/8G 8GB SODIMM DDR4 2400MT/s          | 5        | 0.4%    |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                 | 5        | 0.4%    |
| G.Skill RAM F4-2400C16-8GRS 8GB SODIMM DDR4 2400MT/s           | 5        | 0.4%    |
| Crucial RAM CT32G4SFD832A.M16FF 32GB SODIMM DDR4 3200MT/s      | 5        | 0.4%    |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s          | 5        | 0.4%    |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s          | 5        | 0.4%    |
| ATP RAM AW12P6438BLK0S 4GB DIMM DDR3 1600MT/s                  | 5        | 0.4%    |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 4        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 469      | 43.67%  |
| DDR4    | 463      | 43.11%  |
| DDR2    | 42       | 3.91%   |
| LPDDR4  | 31       | 2.89%   |
| Unknown | 29       | 2.7%    |
| SDRAM   | 23       | 2.14%   |
| DDR5    | 7        | 0.65%   |
| LPDDR5  | 5        | 0.47%   |
| DDR     | 5        | 0.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 524      | 49.25%  |
| SODIMM       | 512      | 48.12%  |
| Row Of Chips | 19       | 1.79%   |
| Unknown      | 8        | 0.75%   |
| FB-DIMM      | 1        | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 421      | 37.26%  |
| 4096  | 373      | 33.01%  |
| 16384 | 157      | 13.89%  |
| 2048  | 129      | 11.42%  |
| 32768 | 31       | 2.74%   |
| 1024  | 17       | 1.5%    |
| 512   | 2        | 0.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 287      | 25.69%  |
| 2400    | 165      | 14.77%  |
| 1333    | 157      | 14.06%  |
| 3200    | 135      | 12.09%  |
| 2667    | 124      | 11.1%   |
| 2133    | 50       | 4.48%   |
| 800     | 38       | 3.4%    |
| 667     | 35       | 3.13%   |
| Unknown | 24       | 2.15%   |
| 1867    | 18       | 1.61%   |
| 2666    | 15       | 1.34%   |
| 1066    | 14       | 1.25%   |
| 3000    | 9        | 0.81%   |
| 1866    | 9        | 0.81%   |
| 2933    | 6        | 0.54%   |
| 6400    | 5        | 0.45%   |
| 4800    | 5        | 0.45%   |
| 3600    | 5        | 0.45%   |
| 1334    | 3        | 0.27%   |
| 5600    | 2        | 0.18%   |
| 1067    | 2        | 0.18%   |
| 533     | 2        | 0.18%   |
| 333     | 2        | 0.18%   |
| 65535   | 1        | 0.09%   |
| 3534    | 1        | 0.09%   |
| 3500    | 1        | 0.09%   |
| 1419    | 1        | 0.09%   |
| 1033    | 1        | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 3        | 50%     |
| Ricoh               | 1        | 16.67%  |
| QinHeng Electronics | 1        | 16.67%  |
| Hewlett-Packard     | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Brother MFC-7360N             | 2        | 33.33%  |
| Ricoh SP 112                  | 1        | 16.67%  |
| QinHeng CH340S                | 1        | 16.67%  |
| HP HP LaserJet P2035 HP Print | 1        | 16.67%  |
| Brother HL-L2310D series      | 1        | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Canon       | 2        | 66.67%  |
| Seiko Epson | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Desktops | Percent |
|-------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                             | 2        | 66.67%  |
| Seiko Epson WF-2860 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 8        | 57.14%  |
| ARC International             | 2        | 14.29%  |
| Z-Star Microelectronics       | 1        | 7.14%   |
| Trust                         | 1        | 7.14%   |
| Sunplus Innovation Technology | 1        | 7.14%   |
| Chicony Electronics           | 1        | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech Webcam C270          | 2        | 14.29%  |
| Logitech C920 PRO HD Webcam   | 2        | 14.29%  |
| Logitech C920 HD Pro Webcam   | 2        | 14.29%  |
| ARC International Camera      | 2        | 14.29%  |
| Z-Star Venus USB2.0 Camera    | 1        | 7.14%   |
| Trust Trust USB Camera        | 1        | 7.14%   |
| Sunplus hama C-600 Pro Webcam | 1        | 7.14%   |
| Logitech HD Webcam C525       | 1        | 7.14%   |
| Logitech HD Pro Webcam C920   | 1        | 7.14%   |
| Chicony HP HD Webcam [Fixed]  | 1        | 7.14%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| DigitalPersona | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| DigitalPersona Fingerprint Reader | 1        | 100%    |

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
| 1     | 559      | 46.51%  |
| 0     | 469      | 39.02%  |
| 2     | 116      | 9.65%   |
| 3     | 34       | 2.83%   |
| 4     | 14       | 1.16%   |
| 5     | 9        | 0.75%   |
| 6     | 1        | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 632      | 71.9%   |
| Net/wireless             | 77       | 8.76%   |
| Bluetooth                | 66       | 7.51%   |
| Card reader              | 34       | 3.87%   |
| Firewire controller      | 18       | 2.05%   |
| Net/ethernet             | 17       | 1.93%   |
| Network                  | 15       | 1.71%   |
| Sound                    | 9        | 1.02%   |
| Graphics card            | 4        | 0.46%   |
| Storage/raid             | 1        | 0.11%   |
| Storage/ide              | 1        | 0.11%   |
| Storage/ata              | 1        | 0.11%   |
| Storage                  | 1        | 0.11%   |
| Modem                    | 1        | 0.11%   |
| Fingerprint reader       | 1        | 0.11%   |
| Dvb card                 | 1        | 0.11%   |

