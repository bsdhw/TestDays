helloSystem - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for helloSystem.

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

Total: 517

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | 0AA8h                       | [f9b906ea47](https://bsd-hardware.info/?probe=f9b906ea47) | Apr 30, 2022 |
| Supermicro    | X9DAL                       | [ef1f3da3ce](https://bsd-hardware.info/?probe=ef1f3da3ce) | Apr 26, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [271f1aa4d1](https://bsd-hardware.info/?probe=271f1aa4d1) | Apr 24, 2022 |
| Gigabyte      | B450 AORUS M                | [427cf12b45](https://bsd-hardware.info/?probe=427cf12b45) | Apr 22, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [f7a3f1dfd3](https://bsd-hardware.info/?probe=f7a3f1dfd3) | Apr 21, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [2fd6d176ce](https://bsd-hardware.info/?probe=2fd6d176ce) | Apr 21, 2022 |
| Intel         | H55                         | [1478e4af73](https://bsd-hardware.info/?probe=1478e4af73) | Apr 20, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [ab8aea2f5c](https://bsd-hardware.info/?probe=ab8aea2f5c) | Apr 17, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | [680303f943](https://bsd-hardware.info/?probe=680303f943) | Apr 16, 2022 |
| Dell          | 0Y7WYT A00                  | [399a4fb92e](https://bsd-hardware.info/?probe=399a4fb92e) | Apr 15, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | [47d17d48a7](https://bsd-hardware.info/?probe=47d17d48a7) | Apr 15, 2022 |
| Gigabyte      | B85M-D3H                    | [5502c7fd2f](https://bsd-hardware.info/?probe=5502c7fd2f) | Apr 15, 2022 |
| ASUSTek       | PRIME X399-A                | [3d26c05fda](https://bsd-hardware.info/?probe=3d26c05fda) | Apr 14, 2022 |
| ASUSTek       | P8Z77-V LX                  | [562a4d0421](https://bsd-hardware.info/?probe=562a4d0421) | Apr 14, 2022 |
| ASUSTek       | P8Z77-V LX                  | [9f70756cb2](https://bsd-hardware.info/?probe=9f70756cb2) | Apr 14, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [11ec99d4b7](https://bsd-hardware.info/?probe=11ec99d4b7) | Apr 11, 2022 |
| HP            | 1998                        | [06f0a28858](https://bsd-hardware.info/?probe=06f0a28858) | Apr 10, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [844323ad2d](https://bsd-hardware.info/?probe=844323ad2d) | Apr 09, 2022 |
| ASUSTek       | P5G41T-M LX3                | [ded0d1a114](https://bsd-hardware.info/?probe=ded0d1a114) | Apr 09, 2022 |
| ASUSTek       | P5G41T-M LX3                | [14a6449380](https://bsd-hardware.info/?probe=14a6449380) | Apr 09, 2022 |
| ASUSTek       | M4A88T-M                    | [9d1a8b4886](https://bsd-hardware.info/?probe=9d1a8b4886) | Apr 09, 2022 |
| ASRock        | X570 Steel Legend WiFi a... | [703e042cfe](https://bsd-hardware.info/?probe=703e042cfe) | Apr 09, 2022 |
| Dell          | 0D6H9T A00                  | [e58bc4937d](https://bsd-hardware.info/?probe=e58bc4937d) | Apr 09, 2022 |
| Gigabyte      | E3000N                      | [7169c296cc](https://bsd-hardware.info/?probe=7169c296cc) | Apr 08, 2022 |
| MSI           | MS-7369                     | [25f2161cac](https://bsd-hardware.info/?probe=25f2161cac) | Apr 08, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [964ceb3616](https://bsd-hardware.info/?probe=964ceb3616) | Apr 03, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [5038186437](https://bsd-hardware.info/?probe=5038186437) | Apr 02, 2022 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | [9b6f9eac6f](https://bsd-hardware.info/?probe=9b6f9eac6f) | Apr 01, 2022 |
| ASUSTek       | P8Z77-V LX                  | [42419abab8](https://bsd-hardware.info/?probe=42419abab8) | Apr 01, 2022 |
| Dell          | 0D6H9T A00                  | [7daab72741](https://bsd-hardware.info/?probe=7daab72741) | Apr 01, 2022 |
| ASUSTek       | P8Z77-V LX                  | [49627775f3](https://bsd-hardware.info/?probe=49627775f3) | Mar 31, 2022 |
| ASUSTek       | P6-P8H61E                   | [11664cd9d7](https://bsd-hardware.info/?probe=11664cd9d7) | Mar 30, 2022 |
| ASUSTek       | M4A88T-M                    | [6a615f6be5](https://bsd-hardware.info/?probe=6a615f6be5) | Mar 30, 2022 |
| ASUSTek       | P6-P8H61E                   | [540f66f678](https://bsd-hardware.info/?probe=540f66f678) | Mar 29, 2022 |
| ASUSTek       | M5A78L-M LX3                | [0906d116eb](https://bsd-hardware.info/?probe=0906d116eb) | Mar 29, 2022 |
| Gigabyte      | H110N-CF                    | [89593af061](https://bsd-hardware.info/?probe=89593af061) | Mar 29, 2022 |
| Gigabyte      | H61M-S2PV                   | [553f2beb91](https://bsd-hardware.info/?probe=553f2beb91) | Mar 27, 2022 |
| ASRock        | A320M-HDV R4.0              | [8c89faeb24](https://bsd-hardware.info/?probe=8c89faeb24) | Mar 26, 2022 |
| ASRock        | A320M-HDV R4.0              | [ae1fa6cbce](https://bsd-hardware.info/?probe=ae1fa6cbce) | Mar 26, 2022 |
| ASUSTek       | P8Z77-V LX                  | [70d10ce47c](https://bsd-hardware.info/?probe=70d10ce47c) | Mar 25, 2022 |
| MSI           | B85-G43                     | [f0a919c35f](https://bsd-hardware.info/?probe=f0a919c35f) | Mar 25, 2022 |
| ASUSTek       | P8Z77-V LX                  | [99d079bd5a](https://bsd-hardware.info/?probe=99d079bd5a) | Mar 25, 2022 |
| MSI           | B85-G43                     | [7bd545fda8](https://bsd-hardware.info/?probe=7bd545fda8) | Mar 25, 2022 |
| ASUSTek       | P8Z77-V LX                  | [c76aa38baf](https://bsd-hardware.info/?probe=c76aa38baf) | Mar 24, 2022 |
| ASUSTek       | P8Z77-V LX                  | [8696405d09](https://bsd-hardware.info/?probe=8696405d09) | Mar 24, 2022 |
| ECS           | G41T-M9                     | [9ef50c47da](https://bsd-hardware.info/?probe=9ef50c47da) | Mar 21, 2022 |
| Gigabyte      | H270-Gaming 3               | [2727a8e439](https://bsd-hardware.info/?probe=2727a8e439) | Mar 15, 2022 |
| Gigabyte      | G31M-S2C                    | [5a22bb6991](https://bsd-hardware.info/?probe=5a22bb6991) | Mar 12, 2022 |
| Lenovo        | IdeaCentre B545 10100       | [2f13d4a946](https://bsd-hardware.info/?probe=2f13d4a946) | Mar 12, 2022 |
| MSI           | B350M BAZOOKA               | [bac8d0bdb7](https://bsd-hardware.info/?probe=bac8d0bdb7) | Mar 11, 2022 |
| ASUSTek       | P5Q DELUXE                  | [b4234170e8](https://bsd-hardware.info/?probe=b4234170e8) | Mar 10, 2022 |
| Pegatron      | IPM41-D3                    | [a58b9a4f8f](https://bsd-hardware.info/?probe=a58b9a4f8f) | Mar 09, 2022 |
| Koloe         | X58                         | [58e098eca2](https://bsd-hardware.info/?probe=58e098eca2) | Mar 09, 2022 |
| HP            | 8054                        | [86b6b8373c](https://bsd-hardware.info/?probe=86b6b8373c) | Mar 08, 2022 |
| HP            | 8054                        | [00078554d2](https://bsd-hardware.info/?probe=00078554d2) | Mar 08, 2022 |
| Koloe         | X58                         | [c501dfa5c8](https://bsd-hardware.info/?probe=c501dfa5c8) | Mar 07, 2022 |
| Dell          | 0GXM1W A00                  | [c4d10a26fd](https://bsd-hardware.info/?probe=c4d10a26fd) | Mar 04, 2022 |
| ASRock        | G41C-VS                     | [a9a1b1a493](https://bsd-hardware.info/?probe=a9a1b1a493) | Mar 03, 2022 |
| Intel         | DN2800MT AAG23738-600       | [8ecf2d023f](https://bsd-hardware.info/?probe=8ecf2d023f) | Mar 02, 2022 |
| HP            | 1905                        | [e271589365](https://bsd-hardware.info/?probe=e271589365) | Mar 01, 2022 |
| Gigabyte      | B450M S2H                   | [78f79fab6f](https://bsd-hardware.info/?probe=78f79fab6f) | Feb 28, 2022 |
| Dell          | 0KV62T A00                  | [0541a207c7](https://bsd-hardware.info/?probe=0541a207c7) | Feb 28, 2022 |
| HP            | 1905                        | [aa010e00f2](https://bsd-hardware.info/?probe=aa010e00f2) | Feb 28, 2022 |
| ASRock        | TRX40 Taichi                | [a2df68e1d1](https://bsd-hardware.info/?probe=a2df68e1d1) | Feb 26, 2022 |
| Intel         | H81                         | [dd19abd47d](https://bsd-hardware.info/?probe=dd19abd47d) | Feb 25, 2022 |
| Intel         | H81                         | [04d2739bdc](https://bsd-hardware.info/?probe=04d2739bdc) | Feb 25, 2022 |
| Intel         | DCP847SKE G80890-107        | [f9d33f1ab1](https://bsd-hardware.info/?probe=f9d33f1ab1) | Feb 23, 2022 |
| Medion        | H61H2-LM3                   | [beb12f2884](https://bsd-hardware.info/?probe=beb12f2884) | Feb 23, 2022 |
| ASRock        | H81M-DG4                    | [e20db6ad83](https://bsd-hardware.info/?probe=e20db6ad83) | Feb 23, 2022 |
| HP            | 1998                        | [485d417a2e](https://bsd-hardware.info/?probe=485d417a2e) | Feb 23, 2022 |
| Dell          | 0VD5HY A07                  | [bb86fb3e67](https://bsd-hardware.info/?probe=bb86fb3e67) | Feb 22, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [1e6ff84e5d](https://bsd-hardware.info/?probe=1e6ff84e5d) | Feb 21, 2022 |
| Gigabyte      | P41T-D3                     | [e5417931a7](https://bsd-hardware.info/?probe=e5417931a7) | Feb 18, 2022 |
| ASRock        | B460M Pro4                  | [7a2781344f](https://bsd-hardware.info/?probe=7a2781344f) | Feb 17, 2022 |
| ASUSTek       | PRIME Z390-P                | [3a72227408](https://bsd-hardware.info/?probe=3a72227408) | Feb 16, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | [64999a24c1](https://bsd-hardware.info/?probe=64999a24c1) | Feb 16, 2022 |
| Gigabyte      | C246M-WU4-CF                | [4b6c6d8bde](https://bsd-hardware.info/?probe=4b6c6d8bde) | Feb 15, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [df6278638e](https://bsd-hardware.info/?probe=df6278638e) | Feb 15, 2022 |
| AMD           | X64                         | [e5a9ff1138](https://bsd-hardware.info/?probe=e5a9ff1138) | Feb 15, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [eddeb5c246](https://bsd-hardware.info/?probe=eddeb5c246) | Feb 13, 2022 |
| ASRock        | H61M/U3S3                   | [257e13f206](https://bsd-hardware.info/?probe=257e13f206) | Feb 12, 2022 |
| ASUSTek       | PRIME Z390-P                | [abf34bbc7e](https://bsd-hardware.info/?probe=abf34bbc7e) | Feb 12, 2022 |
| ASRock        | H61M/U3S3                   | [34dac4c0cd](https://bsd-hardware.info/?probe=34dac4c0cd) | Feb 11, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [6997de25f9](https://bsd-hardware.info/?probe=6997de25f9) | Feb 11, 2022 |
| MACHINIST     | X99-k9 V2.0                 | [0a36d71db1](https://bsd-hardware.info/?probe=0a36d71db1) | Feb 10, 2022 |
| Intel         | X58                         | [f7075908f6](https://bsd-hardware.info/?probe=f7075908f6) | Feb 09, 2022 |
| ASUSTek       | PRIME Z390-P                | [b1931633be](https://bsd-hardware.info/?probe=b1931633be) | Feb 09, 2022 |
| ASUSTek       | PRIME Z390-P                | [f9c1e787a9](https://bsd-hardware.info/?probe=f9c1e787a9) | Feb 09, 2022 |
| MSI           | B75A-G43                    | [8e445eb2d4](https://bsd-hardware.info/?probe=8e445eb2d4) | Feb 08, 2022 |
| ASUSTek       | P6-P8H61E                   | [e838981914](https://bsd-hardware.info/?probe=e838981914) | Feb 06, 2022 |
| ASRock        | H81M-VG4 R2.0               | [8af8b5270e](https://bsd-hardware.info/?probe=8af8b5270e) | Feb 04, 2022 |
| Apple         | Mac-F221BEC8                | [e5043f0af4](https://bsd-hardware.info/?probe=e5043f0af4) | Feb 04, 2022 |
| Pegatron      | NARRA5                      | [64d4fb9b97](https://bsd-hardware.info/?probe=64d4fb9b97) | Feb 02, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | [ee05643521](https://bsd-hardware.info/?probe=ee05643521) | Feb 01, 2022 |
| ASUSTek       | P5P43TD PRO                 | [5999e0ebfb](https://bsd-hardware.info/?probe=5999e0ebfb) | Jan 31, 2022 |
| Intel         | H81                         | [c2f3025900](https://bsd-hardware.info/?probe=c2f3025900) | Jan 31, 2022 |
| Pegatron      | 2A99h                       | [e34b6118a2](https://bsd-hardware.info/?probe=e34b6118a2) | Jan 30, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [58ea01e4e6](https://bsd-hardware.info/?probe=58ea01e4e6) | Jan 29, 2022 |
| Intel         | DH77EB AAG39073-400         | [bfe6ef301b](https://bsd-hardware.info/?probe=bfe6ef301b) | Jan 29, 2022 |
| Dell          | 014GRG A03                  | [8e0a22c065](https://bsd-hardware.info/?probe=8e0a22c065) | Jan 28, 2022 |
| Pegatron      | IPPPV-D3G                   | [d5e44ccf6b](https://bsd-hardware.info/?probe=d5e44ccf6b) | Jan 28, 2022 |
| Dell          | 014GRG A03                  | [5996ba19b1](https://bsd-hardware.info/?probe=5996ba19b1) | Jan 27, 2022 |
| ASUSTek       | P5GC-MX                     | [372749f9d7](https://bsd-hardware.info/?probe=372749f9d7) | Jan 27, 2022 |
| Unknown       | Unknown                     | [a9d799ca71](https://bsd-hardware.info/?probe=a9d799ca71) | Jan 27, 2022 |
| ASUSTek       | P5B SE                      | [f97fba19c1](https://bsd-hardware.info/?probe=f97fba19c1) | Jan 26, 2022 |
| Dell          | 014GRG A03                  | [223d955a90](https://bsd-hardware.info/?probe=223d955a90) | Jan 26, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [9f0a000ceb](https://bsd-hardware.info/?probe=9f0a000ceb) | Jan 25, 2022 |
| ASUSTek       | P5B SE                      | [e3332e7b94](https://bsd-hardware.info/?probe=e3332e7b94) | Jan 25, 2022 |
| ASRock        | B460M Pro4                  | [107a1e59f5](https://bsd-hardware.info/?probe=107a1e59f5) | Jan 25, 2022 |
| ASRock        | A300M-STX                   | [8edf072b67](https://bsd-hardware.info/?probe=8edf072b67) | Jan 25, 2022 |
| Intel         | MAHOBAY                     | [2036093b68](https://bsd-hardware.info/?probe=2036093b68) | Jan 25, 2022 |
| ASUSTek       | BM6835_BM6635_BP6335        | [73562aa169](https://bsd-hardware.info/?probe=73562aa169) | Jan 25, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [df08e2e8f0](https://bsd-hardware.info/?probe=df08e2e8f0) | Jan 24, 2022 |
| Dell          | 05DN3X A00                  | [e0e63e69ef](https://bsd-hardware.info/?probe=e0e63e69ef) | Jan 23, 2022 |
| ASUSTek       | P7H55-M                     | [fb73c2f7dc](https://bsd-hardware.info/?probe=fb73c2f7dc) | Jan 23, 2022 |
| HP            | 8648                        | [b0adf55067](https://bsd-hardware.info/?probe=b0adf55067) | Jan 23, 2022 |
| HP            | 1998                        | [b59dbcdc9c](https://bsd-hardware.info/?probe=b59dbcdc9c) | Jan 23, 2022 |
| Dell          | 05DN3X A00                  | [460ea5c41d](https://bsd-hardware.info/?probe=460ea5c41d) | Jan 23, 2022 |
| Dell          | 0593VH A00                  | [484d14dbef](https://bsd-hardware.info/?probe=484d14dbef) | Jan 22, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [670e41ed41](https://bsd-hardware.info/?probe=670e41ed41) | Jan 21, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [04abd226f3](https://bsd-hardware.info/?probe=04abd226f3) | Jan 21, 2022 |
| ASUSTek       | Maximus VIII HERO           | [a780a7bab2](https://bsd-hardware.info/?probe=a780a7bab2) | Jan 18, 2022 |
| ASRock        | B365M Pro4                  | [8449bd20c1](https://bsd-hardware.info/?probe=8449bd20c1) | Jan 18, 2022 |
| Dell          | 0YF8P5 A00                  | [913b2a7483](https://bsd-hardware.info/?probe=913b2a7483) | Jan 18, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | [9cd2758a5f](https://bsd-hardware.info/?probe=9cd2758a5f) | Jan 18, 2022 |
| ASUSTek       | PRIME X570-P                | [3dead218e1](https://bsd-hardware.info/?probe=3dead218e1) | Jan 16, 2022 |
| Gigabyte      | B365 HD3                    | [62fc48bd99](https://bsd-hardware.info/?probe=62fc48bd99) | Jan 15, 2022 |
| Dell          | 0XCR8D A03                  | [48e9447b37](https://bsd-hardware.info/?probe=48e9447b37) | Jan 15, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [d377e06101](https://bsd-hardware.info/?probe=d377e06101) | Jan 15, 2022 |
| Gigabyte      | Z77N-WIFI                   | [459bb6486d](https://bsd-hardware.info/?probe=459bb6486d) | Jan 13, 2022 |
| Dell          | 0X4N41 A01                  | [87000234dc](https://bsd-hardware.info/?probe=87000234dc) | Jan 11, 2022 |
| ASUSTek       | P8Z68-M PRO                 | [a0885f4f44](https://bsd-hardware.info/?probe=a0885f4f44) | Jan 10, 2022 |
| HP            | 8169                        | [85e0cf058c](https://bsd-hardware.info/?probe=85e0cf058c) | Jan 10, 2022 |
| ASUSTek       | GA35DX                      | [eccb947ae4](https://bsd-hardware.info/?probe=eccb947ae4) | Jan 05, 2022 |
| Unknown       | G31T-M7                     | [ed7d80e01a](https://bsd-hardware.info/?probe=ed7d80e01a) | Jan 03, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | [a671e3eb04](https://bsd-hardware.info/?probe=a671e3eb04) | Dec 31, 2021 |
| ASUSTek       | M5A78L/USB3                 | [f1fe3fe225](https://bsd-hardware.info/?probe=f1fe3fe225) | Dec 30, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [15211db056](https://bsd-hardware.info/?probe=15211db056) | Dec 28, 2021 |
| Dell          | 0200DY A01                  | [fb37dcbb93](https://bsd-hardware.info/?probe=fb37dcbb93) | Dec 28, 2021 |
| Pegatron      | IPM41-D3                    | [6829928dad](https://bsd-hardware.info/?probe=6829928dad) | Dec 28, 2021 |
| Dell          | 0H9KW5 A00                  | [e962ca25b3](https://bsd-hardware.info/?probe=e962ca25b3) | Dec 28, 2021 |
| Gigabyte      | 970A-DS3P                   | [0918f0a5b9](https://bsd-hardware.info/?probe=0918f0a5b9) | Dec 25, 2021 |
| ASUSTek       | PRIME B350M-A               | [b0aa3885bb](https://bsd-hardware.info/?probe=b0aa3885bb) | Dec 25, 2021 |
| ASUSTek       | Z170-P                      | [bde74629f9](https://bsd-hardware.info/?probe=bde74629f9) | Dec 25, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [8ac48ba9c3](https://bsd-hardware.info/?probe=8ac48ba9c3) | Dec 23, 2021 |
| Gigabyte      | E3000N                      | [eb0ba1b296](https://bsd-hardware.info/?probe=eb0ba1b296) | Dec 22, 2021 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [936afa4de3](https://bsd-hardware.info/?probe=936afa4de3) | Dec 21, 2021 |
| ASUSTek       | PRIME A320M-K               | [42599b554e](https://bsd-hardware.info/?probe=42599b554e) | Dec 21, 2021 |
| Gigabyte      | X58A-UD5                    | [62b94dd372](https://bsd-hardware.info/?probe=62b94dd372) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [5cc62c68f9](https://bsd-hardware.info/?probe=5cc62c68f9) | Dec 21, 2021 |
| Gigabyte      | H170-D3HP-CF                | [a490614a39](https://bsd-hardware.info/?probe=a490614a39) | Dec 21, 2021 |
| ASRock        | H110M-DGS                   | [40c4553adb](https://bsd-hardware.info/?probe=40c4553adb) | Dec 21, 2021 |
| ASUSTek       | P5VD2-VM                    | [7e8f3cf783](https://bsd-hardware.info/?probe=7e8f3cf783) | Dec 20, 2021 |
| ASUSTek       | Q170M-C                     | [7f9e35a31c](https://bsd-hardware.info/?probe=7f9e35a31c) | Dec 20, 2021 |
| Dell          | 0TDG4V A00                  | [3ce808c135](https://bsd-hardware.info/?probe=3ce808c135) | Dec 20, 2021 |
| Dell          | 0TDG4V A00                  | [5292ad64ef](https://bsd-hardware.info/?probe=5292ad64ef) | Dec 20, 2021 |
| ASUSTek       | P8Z77-V LX                  | [3c71a8ba4e](https://bsd-hardware.info/?probe=3c71a8ba4e) | Dec 20, 2021 |
| MSI           | X370 SLI PLUS               | [73853f1fc2](https://bsd-hardware.info/?probe=73853f1fc2) | Dec 19, 2021 |
| Quanta        | 2AC7 011                    | [1a831a1d34](https://bsd-hardware.info/?probe=1a831a1d34) | Dec 18, 2021 |
| Gigabyte      | Z77X-UD3H                   | [759ce775c9](https://bsd-hardware.info/?probe=759ce775c9) | Dec 15, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [32d20b9b8e](https://bsd-hardware.info/?probe=32d20b9b8e) | Dec 14, 2021 |
| HP            | 843B                        | [f0d279747f](https://bsd-hardware.info/?probe=f0d279747f) | Dec 13, 2021 |
| HP            | 843B                        | [56400d3999](https://bsd-hardware.info/?probe=56400d3999) | Dec 13, 2021 |
| ASUSTek       | PRIME B450M-A               | [aea4a33dee](https://bsd-hardware.info/?probe=aea4a33dee) | Dec 13, 2021 |
| ASUSTek       | H110M-K                     | [2921401f70](https://bsd-hardware.info/?probe=2921401f70) | Dec 12, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [50fba6deda](https://bsd-hardware.info/?probe=50fba6deda) | Dec 11, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [6a1100cfdb](https://bsd-hardware.info/?probe=6a1100cfdb) | Dec 11, 2021 |
| Acer          | RevoOne RL85                | [a1e32de7da](https://bsd-hardware.info/?probe=a1e32de7da) | Dec 10, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [b900b364f6](https://bsd-hardware.info/?probe=b900b364f6) | Dec 10, 2021 |
| HP            | 8054                        | [de953100f6](https://bsd-hardware.info/?probe=de953100f6) | Dec 10, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [a9423b3232](https://bsd-hardware.info/?probe=a9423b3232) | Dec 09, 2021 |
| Dell          | 0YF8P5 A00                  | [0f03a66475](https://bsd-hardware.info/?probe=0f03a66475) | Dec 09, 2021 |
| Dell          | 0YF8P5 A00                  | [83b36f7c3d](https://bsd-hardware.info/?probe=83b36f7c3d) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [a084ff48c2](https://bsd-hardware.info/?probe=a084ff48c2) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [17b557d792](https://bsd-hardware.info/?probe=17b557d792) | Dec 08, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [35b01f0f56](https://bsd-hardware.info/?probe=35b01f0f56) | Dec 05, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [14f1956220](https://bsd-hardware.info/?probe=14f1956220) | Dec 04, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [8cfe11fe93](https://bsd-hardware.info/?probe=8cfe11fe93) | Nov 30, 2021 |
| HP            | 843B                        | [376e006a40](https://bsd-hardware.info/?probe=376e006a40) | Nov 30, 2021 |
| Intel         | DG41TY AAE47335-300         | [dd357bcaa5](https://bsd-hardware.info/?probe=dd357bcaa5) | Nov 30, 2021 |
| HP            | 843B                        | [404224439d](https://bsd-hardware.info/?probe=404224439d) | Nov 29, 2021 |
| HP            | 843B                        | [a8ac0e9efb](https://bsd-hardware.info/?probe=a8ac0e9efb) | Nov 29, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [bc3b65334e](https://bsd-hardware.info/?probe=bc3b65334e) | Nov 29, 2021 |
| HP            | 1825                        | [32f07d2ba3](https://bsd-hardware.info/?probe=32f07d2ba3) | Nov 28, 2021 |
| Dell          | 0DR845                      | [4d07453a93](https://bsd-hardware.info/?probe=4d07453a93) | Nov 27, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [4cd5e5166a](https://bsd-hardware.info/?probe=4cd5e5166a) | Nov 27, 2021 |
| ASRock        | 775i945GZ                   | [16fc4ee10d](https://bsd-hardware.info/?probe=16fc4ee10d) | Nov 26, 2021 |
| ASRock        | AB350 Pro4                  | [ef35dd084e](https://bsd-hardware.info/?probe=ef35dd084e) | Nov 26, 2021 |
| HP            | 0A80h                       | [1e1153ee69](https://bsd-hardware.info/?probe=1e1153ee69) | Nov 22, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [afd0cf45c6](https://bsd-hardware.info/?probe=afd0cf45c6) | Nov 21, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [12a360ddd1](https://bsd-hardware.info/?probe=12a360ddd1) | Nov 14, 2021 |
| T-bao         | MINI PC V1.0                | [4ee7de3597](https://bsd-hardware.info/?probe=4ee7de3597) | Nov 12, 2021 |
| Biostar       | B365MHC                     | [0c059bab3f](https://bsd-hardware.info/?probe=0c059bab3f) | Nov 11, 2021 |
| Itautec       | ST 4344 ST-4344 Padrao 0... | [ec13cb0829](https://bsd-hardware.info/?probe=ec13cb0829) | Nov 07, 2021 |
| Shuttle       | FH61R                       | [a231590743](https://bsd-hardware.info/?probe=a231590743) | Nov 07, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [7e27b1bc46](https://bsd-hardware.info/?probe=7e27b1bc46) | Nov 07, 2021 |
| Intel         | H81                         | [7f07aecffc](https://bsd-hardware.info/?probe=7f07aecffc) | Nov 07, 2021 |
| HP            | 844C                        | [fb7d8eaf5d](https://bsd-hardware.info/?probe=fb7d8eaf5d) | Nov 06, 2021 |
| Unknown       | X79                         | [ef88cbc606](https://bsd-hardware.info/?probe=ef88cbc606) | Nov 05, 2021 |
| ASRock        | X370 Gaming X               | [2a874a33dd](https://bsd-hardware.info/?probe=2a874a33dd) | Nov 05, 2021 |
| Lenovo        | SHARKBAY No DPK             | [b9ad64f354](https://bsd-hardware.info/?probe=b9ad64f354) | Nov 04, 2021 |
| Gigabyte      | F2A78M-DS2                  | [45576fddfa](https://bsd-hardware.info/?probe=45576fddfa) | Nov 02, 2021 |
| Dell          | 0M5DCD A02                  | [4ff4198768](https://bsd-hardware.info/?probe=4ff4198768) | Nov 02, 2021 |
| Gateway       | DX4840                      | [1d2e9e175c](https://bsd-hardware.info/?probe=1d2e9e175c) | Nov 01, 2021 |
| ASRock        | X300M-STX                   | [e25f042400](https://bsd-hardware.info/?probe=e25f042400) | Oct 30, 2021 |
| Unknown       | Intel X79                   | [044908e7c3](https://bsd-hardware.info/?probe=044908e7c3) | Oct 30, 2021 |
| HP            | 843B                        | [9761f29b5e](https://bsd-hardware.info/?probe=9761f29b5e) | Oct 25, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [9f8010bdbe](https://bsd-hardware.info/?probe=9f8010bdbe) | Oct 25, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | [9959c0900a](https://bsd-hardware.info/?probe=9959c0900a) | Oct 23, 2021 |
| Gigabyte      | H410M S2 V2                 | [b106820e47](https://bsd-hardware.info/?probe=b106820e47) | Oct 21, 2021 |
| Acer          | RS880M05                    | [4718f0cb0c](https://bsd-hardware.info/?probe=4718f0cb0c) | Oct 21, 2021 |
| Apple         | Mac-F221BEC8                | [cb2cc35e6c](https://bsd-hardware.info/?probe=cb2cc35e6c) | Oct 19, 2021 |
| Gigabyte      | 990FXA-UD3                  | [3cf20ca77c](https://bsd-hardware.info/?probe=3cf20ca77c) | Oct 19, 2021 |
| Dell          | 0VRWRC A00                  | [9b4defb194](https://bsd-hardware.info/?probe=9b4defb194) | Oct 19, 2021 |
| HP            | 3398                        | [892f19c9bd](https://bsd-hardware.info/?probe=892f19c9bd) | Oct 18, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [0cdd3497f6](https://bsd-hardware.info/?probe=0cdd3497f6) | Oct 18, 2021 |
| Gigabyte      | G41MT-S2                    | [2847d63db0](https://bsd-hardware.info/?probe=2847d63db0) | Oct 18, 2021 |
| ASUSTek       | P5P43TD PRO                 | [2870e26de1](https://bsd-hardware.info/?probe=2870e26de1) | Oct 17, 2021 |
| ASUSTek       | F2A85-M                     | [b4e3f33e5c](https://bsd-hardware.info/?probe=b4e3f33e5c) | Oct 14, 2021 |
| Lenovo        | SHARKBAY No DPK             | [14dcd924b5](https://bsd-hardware.info/?probe=14dcd924b5) | Oct 13, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [b3b31d25b0](https://bsd-hardware.info/?probe=b3b31d25b0) | Oct 13, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [5a7c1871b1](https://bsd-hardware.info/?probe=5a7c1871b1) | Oct 11, 2021 |
| Acer          | Aspire TC-780               | [77101a00b3](https://bsd-hardware.info/?probe=77101a00b3) | Oct 11, 2021 |
| Acer          | Aspire TC-780               | [3ce8481842](https://bsd-hardware.info/?probe=3ce8481842) | Oct 10, 2021 |
| ASUSTek       | D940MX                      | [4e798f3ef0](https://bsd-hardware.info/?probe=4e798f3ef0) | Oct 10, 2021 |
| Medion        | H61H2-LM3                   | [67ed0f639c](https://bsd-hardware.info/?probe=67ed0f639c) | Oct 10, 2021 |
| ASUSTek       | H81M-K                      | [e24f67a603](https://bsd-hardware.info/?probe=e24f67a603) | Oct 08, 2021 |
| MSI           | G41M-P25                    | [21eec496b4](https://bsd-hardware.info/?probe=21eec496b4) | Oct 08, 2021 |
| ASRock        | A320M-DGS                   | [11cf5c923a](https://bsd-hardware.info/?probe=11cf5c923a) | Oct 08, 2021 |
| Gigabyte      | B450 AORUS M                | [d09f63f257](https://bsd-hardware.info/?probe=d09f63f257) | Oct 07, 2021 |
| Intel         | H61                         | [6ce71c1b9e](https://bsd-hardware.info/?probe=6ce71c1b9e) | Oct 06, 2021 |
| HP            | 3397                        | [4c71aae5bf](https://bsd-hardware.info/?probe=4c71aae5bf) | Oct 05, 2021 |
| ASRock        | B365M-ITX/ac                | [1c8820a6d0](https://bsd-hardware.info/?probe=1c8820a6d0) | Oct 04, 2021 |
| MSI           | B450I GAMING PLUS AC        | [43388a27a4](https://bsd-hardware.info/?probe=43388a27a4) | Oct 04, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | [bd312d1c88](https://bsd-hardware.info/?probe=bd312d1c88) | Oct 03, 2021 |
| HP            | ProLiant ML350 G5           | [4d525cba3e](https://bsd-hardware.info/?probe=4d525cba3e) | Oct 03, 2021 |
| HP            | 87D6 SMVB                   | [90d91bc113](https://bsd-hardware.info/?probe=90d91bc113) | Sep 26, 2021 |
| Gigabyte      | H61M-D2P-B3                 | [c6da80d54b](https://bsd-hardware.info/?probe=c6da80d54b) | Sep 25, 2021 |
| ASUSTek       | M5A78L-M LX3                | [f336d13e01](https://bsd-hardware.info/?probe=f336d13e01) | Sep 24, 2021 |
| Gigabyte      | H61M-D2P-B3                 | [6ed62a3798](https://bsd-hardware.info/?probe=6ed62a3798) | Sep 23, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [9b14548c15](https://bsd-hardware.info/?probe=9b14548c15) | Sep 21, 2021 |
| Sapphire      | EDGE-FT1M1 E450 1AOVU044    | [ea8fefdf4e](https://bsd-hardware.info/?probe=ea8fefdf4e) | Sep 20, 2021 |
| Dell          | 0MGK50 A02                  | [9d2959b4f1](https://bsd-hardware.info/?probe=9d2959b4f1) | Sep 20, 2021 |
| HP            | 81B4 01                     | [179504116d](https://bsd-hardware.info/?probe=179504116d) | Sep 20, 2021 |
| HP            | 81B4 01                     | [5b28c9bb75](https://bsd-hardware.info/?probe=5b28c9bb75) | Sep 20, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [790d020ebe](https://bsd-hardware.info/?probe=790d020ebe) | Sep 19, 2021 |
| Foxconn       | A88GMX FAB                  | [b46845b69f](https://bsd-hardware.info/?probe=b46845b69f) | Sep 19, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [9b046b157e](https://bsd-hardware.info/?probe=9b046b157e) | Sep 17, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [bc2a287495](https://bsd-hardware.info/?probe=bc2a287495) | Sep 13, 2021 |
| HP            | 87D6 SMVB                   | [61fc69edfe](https://bsd-hardware.info/?probe=61fc69edfe) | Sep 13, 2021 |
| ASUSTek       | P8H77-I                     | [1feb22dc52](https://bsd-hardware.info/?probe=1feb22dc52) | Sep 12, 2021 |
| Sapphire      | EDGE-FT1M1 E450 1AOVU044    | [85ed325446](https://bsd-hardware.info/?probe=85ed325446) | Sep 11, 2021 |
| ASUSTek       | PRIME B360M-C               | [0f6e7e26fc](https://bsd-hardware.info/?probe=0f6e7e26fc) | Sep 11, 2021 |
| ASRock        | B460M Pro4                  | [cfc7818691](https://bsd-hardware.info/?probe=cfc7818691) | Sep 10, 2021 |
| ASUSTek       | H110M-PLUS                  | [08b4825275](https://bsd-hardware.info/?probe=08b4825275) | Sep 09, 2021 |
| ASRock        | B550M Pro4                  | [dc582ea4d3](https://bsd-hardware.info/?probe=dc582ea4d3) | Sep 09, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [c729f82f4c](https://bsd-hardware.info/?probe=c729f82f4c) | Sep 08, 2021 |
| Packard Be... | imedia S2110A               | [d62a38660c](https://bsd-hardware.info/?probe=d62a38660c) | Sep 08, 2021 |
| Lenovo        | Board                       | [685abcc739](https://bsd-hardware.info/?probe=685abcc739) | Sep 07, 2021 |
| HP            | 3397                        | [5d95b75768](https://bsd-hardware.info/?probe=5d95b75768) | Sep 06, 2021 |
| Medion        | H61H2-LM3                   | [7a42009a08](https://bsd-hardware.info/?probe=7a42009a08) | Sep 02, 2021 |
| Medion        | H61H2-LM3                   | [eb81abe401](https://bsd-hardware.info/?probe=eb81abe401) | Sep 02, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [9e13729a12](https://bsd-hardware.info/?probe=9e13729a12) | Sep 02, 2021 |
| ASRock        | Z390 Pro4                   | [ecbf097bc5](https://bsd-hardware.info/?probe=ecbf097bc5) | Sep 02, 2021 |
| ASUSTek       | TUF B360M-PLUS GAMING S     | [33ba0b7c38](https://bsd-hardware.info/?probe=33ba0b7c38) | Aug 29, 2021 |
| HP            | 0A60h                       | [0f28538e3d](https://bsd-hardware.info/?probe=0f28538e3d) | Aug 25, 2021 |
| HP            | 1589                        | [4d51cc9c4b](https://bsd-hardware.info/?probe=4d51cc9c4b) | Aug 24, 2021 |
| Acer          | Aspire TC-895 V:1.0         | [da3e8986a3](https://bsd-hardware.info/?probe=da3e8986a3) | Aug 22, 2021 |
| EVGA          | X299 MICRO                  | [d04b55d1f6](https://bsd-hardware.info/?probe=d04b55d1f6) | Aug 19, 2021 |
| ASRock        | Z390 Pro4                   | [aca402061b](https://bsd-hardware.info/?probe=aca402061b) | Aug 18, 2021 |
| Foxconn       | 2ADA                        | [e96976b2cc](https://bsd-hardware.info/?probe=e96976b2cc) | Aug 18, 2021 |
| Dell          | 0MGK50 A02                  | [2468e9d0ba](https://bsd-hardware.info/?probe=2468e9d0ba) | Aug 17, 2021 |
| HC            | HCAR357-MI V1.0             | [3293b7bad9](https://bsd-hardware.info/?probe=3293b7bad9) | Aug 17, 2021 |
| ASUSTek       | P7H55-M LX                  | [5fe1a9e521](https://bsd-hardware.info/?probe=5fe1a9e521) | Aug 16, 2021 |
| Gigabyte      | HA65M-D2H-B3                | [fc9b50bb85](https://bsd-hardware.info/?probe=fc9b50bb85) | Aug 16, 2021 |
| Gigabyte      | B360M D3H-CF                | [1c88ce5779](https://bsd-hardware.info/?probe=1c88ce5779) | Aug 10, 2021 |
| Pegatron      | IPPCR-SS                    | [8a7fc2689b](https://bsd-hardware.info/?probe=8a7fc2689b) | Aug 09, 2021 |
| Gigabyte      | A75M-DS2                    | [2010fe5fab](https://bsd-hardware.info/?probe=2010fe5fab) | Aug 09, 2021 |
| ASUSTek       | P7H55-M LX                  | [df393cc673](https://bsd-hardware.info/?probe=df393cc673) | Aug 08, 2021 |
| Intel         | D54250WYK H13922-304        | [45c86d174e](https://bsd-hardware.info/?probe=45c86d174e) | Aug 08, 2021 |
| ASUSTek       | M5A78L LE                   | [7a1d31be72](https://bsd-hardware.info/?probe=7a1d31be72) | Aug 07, 2021 |
| ASUSTek       | H81M-A                      | [bb65c30be3](https://bsd-hardware.info/?probe=bb65c30be3) | Aug 07, 2021 |
| ASUSTek       | H81M-A                      | [9e0c8e8024](https://bsd-hardware.info/?probe=9e0c8e8024) | Aug 07, 2021 |
| ASUSTek       | Crosshair V Formula         | [90c27497d9](https://bsd-hardware.info/?probe=90c27497d9) | Aug 05, 2021 |
| PCPartner     | MILANO-P Rev.00             | [526390c559](https://bsd-hardware.info/?probe=526390c559) | Aug 04, 2021 |
| PCPartner     | MILANO-P Rev.00             | [071eac9b1b](https://bsd-hardware.info/?probe=071eac9b1b) | Aug 04, 2021 |
| Biostar       | A770E3                      | [4d0ac19b8e](https://bsd-hardware.info/?probe=4d0ac19b8e) | Aug 03, 2021 |
| Dell          | 0RY007                      | [c67ccf8bc6](https://bsd-hardware.info/?probe=c67ccf8bc6) | Aug 01, 2021 |
| PCPartner     | MILANO-P Rev.00             | [ef8217ac30](https://bsd-hardware.info/?probe=ef8217ac30) | Aug 01, 2021 |
| PCPartner     | MILANO-P Rev.00             | [ef40df391b](https://bsd-hardware.info/?probe=ef40df391b) | Aug 01, 2021 |
| Gigabyte      | H110-D3A-CF                 | [7923f57fbe](https://bsd-hardware.info/?probe=7923f57fbe) | Aug 01, 2021 |
| ASUSTek       | A58M-A/USB3                 | [9ffd4220e8](https://bsd-hardware.info/?probe=9ffd4220e8) | Aug 01, 2021 |
| Biostar       | N68S3+                      | [528c9d6eab](https://bsd-hardware.info/?probe=528c9d6eab) | Jul 26, 2021 |
| Gigabyte      | PH67A-D3-B3                 | [73dff53f04](https://bsd-hardware.info/?probe=73dff53f04) | Jul 23, 2021 |
| ASUSTek       | H110M-PLUS                  | [d0f2da9c41](https://bsd-hardware.info/?probe=d0f2da9c41) | Jul 21, 2021 |
| Gigabyte      | H110-D3A-CF                 | [58e49f458e](https://bsd-hardware.info/?probe=58e49f458e) | Jul 19, 2021 |
| PCPartner     | MILANO-P Rev.00             | [f20ac8df75](https://bsd-hardware.info/?probe=f20ac8df75) | Jul 19, 2021 |
| MSI           | IONA                        | [bb2c6b383b](https://bsd-hardware.info/?probe=bb2c6b383b) | Jul 17, 2021 |
| ASRock        | N68C-GS FX                  | [012356047f](https://bsd-hardware.info/?probe=012356047f) | Jul 17, 2021 |
| ASRock        | N68C-GS FX                  | [e1f439def9](https://bsd-hardware.info/?probe=e1f439def9) | Jul 17, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [20fc88018b](https://bsd-hardware.info/?probe=20fc88018b) | Jul 16, 2021 |
| HP            | 0AE8h C                     | [23df6b2e94](https://bsd-hardware.info/?probe=23df6b2e94) | Jul 12, 2021 |
| Gigabyte      | H110-D3A-CF                 | [2c390b4301](https://bsd-hardware.info/?probe=2c390b4301) | Jul 09, 2021 |
| Gigabyte      | H110-D3A-CF                 | [aea3a11daf](https://bsd-hardware.info/?probe=aea3a11daf) | Jul 08, 2021 |
| Dell          | 0GXM1W A02                  | [269edf2dcf](https://bsd-hardware.info/?probe=269edf2dcf) | Jul 06, 2021 |
| ASRock        | B450M-HDV                   | [dca41aa10a](https://bsd-hardware.info/?probe=dca41aa10a) | Jul 05, 2021 |
| ASRock        | X99 Taichi                  | [149d7abd05](https://bsd-hardware.info/?probe=149d7abd05) | Jul 04, 2021 |
| ASUSTek       | PRIME Z390-P                | [4060cdec72](https://bsd-hardware.info/?probe=4060cdec72) | Jul 04, 2021 |
| ASRock        | Z390 Pro4                   | [dc4eb674ea](https://bsd-hardware.info/?probe=dc4eb674ea) | Jul 03, 2021 |
| Shuttle       | NC10U                       | [5d2d20dd04](https://bsd-hardware.info/?probe=5d2d20dd04) | Jul 02, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [6cf3337855](https://bsd-hardware.info/?probe=6cf3337855) | Jul 01, 2021 |
| Protectli     | FW2B Ver                    | [7b6f704247](https://bsd-hardware.info/?probe=7b6f704247) | Jun 30, 2021 |
| HP            | 0B4Ch D                     | [b56bd19073](https://bsd-hardware.info/?probe=b56bd19073) | Jun 30, 2021 |
| Biostar       | B450MH                      | [167f09a25c](https://bsd-hardware.info/?probe=167f09a25c) | Jun 29, 2021 |
| ASUSTek       | M5A97 R2.0                  | [e7a0dfcecf](https://bsd-hardware.info/?probe=e7a0dfcecf) | Jun 28, 2021 |
| Huanan        | X99-8M-F V1.2               | [6477b9ef24](https://bsd-hardware.info/?probe=6477b9ef24) | Jun 28, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [f0e80b0788](https://bsd-hardware.info/?probe=f0e80b0788) | Jun 28, 2021 |
| ASUSTek       | H110M-E/M.2                 | [f3b0bb0930](https://bsd-hardware.info/?probe=f3b0bb0930) | Jun 28, 2021 |
| ASUSTek       | H81M-K                      | [1a35d2f6ab](https://bsd-hardware.info/?probe=1a35d2f6ab) | Jun 26, 2021 |
| ASUSTek       | PRIME H410M-D               | [8ea103b783](https://bsd-hardware.info/?probe=8ea103b783) | Jun 26, 2021 |
| MSI           | G41M-P25                    | [5cc75b4df0](https://bsd-hardware.info/?probe=5cc75b4df0) | Jun 25, 2021 |
| Dell          | 0P03DX A03                  | [b2f0c90d79](https://bsd-hardware.info/?probe=b2f0c90d79) | Jun 24, 2021 |
| ASUSTek       | P7H55                       | [c33ec074f8](https://bsd-hardware.info/?probe=c33ec074f8) | Jun 22, 2021 |
| ASUSTek       | P8H67-M PRO                 | [616c7043bd](https://bsd-hardware.info/?probe=616c7043bd) | Jun 22, 2021 |
| ASUSTek       | CP5141                      | [73c62835c1](https://bsd-hardware.info/?probe=73c62835c1) | Jun 21, 2021 |
| Foxconn       | 2ABF                        | [d30b2629eb](https://bsd-hardware.info/?probe=d30b2629eb) | Jun 21, 2021 |
| Intel         | DH67CL AAG10212-206         | [f2367a4249](https://bsd-hardware.info/?probe=f2367a4249) | Jun 21, 2021 |
| Gigabyte      | H97-D3H-CF                  | [a326fd4061](https://bsd-hardware.info/?probe=a326fd4061) | Jun 20, 2021 |
| Dell          | 0PGKWF A01                  | [9f09d62462](https://bsd-hardware.info/?probe=9f09d62462) | Jun 20, 2021 |
| MSI           | H110M PRO-VH PLUS           | [45b842180e](https://bsd-hardware.info/?probe=45b842180e) | Jun 20, 2021 |
| ASUSTek       | ROG STRIX H370-I GAMING     | [d2dd261a2a](https://bsd-hardware.info/?probe=d2dd261a2a) | Jun 20, 2021 |
| MSI           | B450M PRO-M2 MAX            | [edcbaf755f](https://bsd-hardware.info/?probe=edcbaf755f) | Jun 19, 2021 |
| Dell          | 0XPDFK A01                  | [631dbb841b](https://bsd-hardware.info/?probe=631dbb841b) | Jun 19, 2021 |
| Lenovo        | ThinkServer RS140           | [0f5d669e9f](https://bsd-hardware.info/?probe=0f5d669e9f) | Jun 18, 2021 |
| Lenovo        | ThinkServer RS140           | [63ba615299](https://bsd-hardware.info/?probe=63ba615299) | Jun 18, 2021 |
| Gigabyte      | AX370-Gaming-CF             | [d77be09267](https://bsd-hardware.info/?probe=d77be09267) | Jun 18, 2021 |
| Dell          | 0XPDFK A01                  | [7a1c26edeb](https://bsd-hardware.info/?probe=7a1c26edeb) | Jun 18, 2021 |
| ASUSTek       | H110I-PLUS                  | [0cb30b464d](https://bsd-hardware.info/?probe=0cb30b464d) | Jun 17, 2021 |
| ASUSTek       | H110M-E/M.2                 | [b0b67667d3](https://bsd-hardware.info/?probe=b0b67667d3) | Jun 16, 2021 |
| HP            | 3397                        | [3dd97c60ca](https://bsd-hardware.info/?probe=3dd97c60ca) | Jun 16, 2021 |
| Lenovo        | Board                       | [c981ffdff7](https://bsd-hardware.info/?probe=c981ffdff7) | Jun 15, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [5f9b56c8ae](https://bsd-hardware.info/?probe=5f9b56c8ae) | Jun 15, 2021 |
| ASUSTek       | M4A78LT-M                   | [0c8d6cd661](https://bsd-hardware.info/?probe=0c8d6cd661) | Jun 14, 2021 |
| ASUSTek       | PRIME A320M-K               | [fea57181b5](https://bsd-hardware.info/?probe=fea57181b5) | Jun 14, 2021 |
| ASRock        | G31M-VS2                    | [f2f5b95f4b](https://bsd-hardware.info/?probe=f2f5b95f4b) | Jun 14, 2021 |
| Intel         | X79 V2.72A                  | [88173bcf06](https://bsd-hardware.info/?probe=88173bcf06) | Jun 14, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [eeb4489d2f](https://bsd-hardware.info/?probe=eeb4489d2f) | Jun 13, 2021 |
| Gigabyte      | H470M DS3H                  | [7c37a0319b](https://bsd-hardware.info/?probe=7c37a0319b) | Jun 13, 2021 |
| ASRock        | FM2A68M-HD+                 | [8bb0d23eb4](https://bsd-hardware.info/?probe=8bb0d23eb4) | Jun 13, 2021 |
| ASUSTek       | Z97-A-USB31                 | [7fe10badbb](https://bsd-hardware.info/?probe=7fe10badbb) | Jun 11, 2021 |
| Lenovo        | Board                       | [1d6f23a5de](https://bsd-hardware.info/?probe=1d6f23a5de) | May 24, 2021 |
| Apple         | Mac-F221BEC8                | [869f003493](https://bsd-hardware.info/?probe=869f003493) | May 17, 2021 |
| MSI           | B450M-A PRO MAX             | [6317bd7dbd](https://bsd-hardware.info/?probe=6317bd7dbd) | May 05, 2021 |
| MSI           | B450-A PRO                  | [ed656e816f](https://bsd-hardware.info/?probe=ed656e816f) | May 01, 2021 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [6e874538cb](https://bsd-hardware.info/?probe=6e874538cb) | Apr 20, 2021 |
| HP            | 18E7                        | [e6354de524](https://bsd-hardware.info/?probe=e6354de524) | Apr 20, 2021 |
| ASUSTek       | P5G41T-M LX3                | [1759329ae3](https://bsd-hardware.info/?probe=1759329ae3) | Apr 12, 2021 |
| Dell          | 0RW199                      | [e78392bc4c](https://bsd-hardware.info/?probe=e78392bc4c) | Apr 02, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [62376c16a4](https://bsd-hardware.info/?probe=62376c16a4) | Mar 31, 2021 |
| Medion        | H61H2-LM3                   | [6483c8390f](https://bsd-hardware.info/?probe=6483c8390f) | Mar 31, 2021 |
| Pegatron      | IPM41-D3                    | [687047b3d2](https://bsd-hardware.info/?probe=687047b3d2) | Mar 30, 2021 |
| Gigabyte      | Z77X-UD5H                   | [d3742d3898](https://bsd-hardware.info/?probe=d3742d3898) | Mar 29, 2021 |
| Dell          | 0NW6H5 A00                  | [1499695aae](https://bsd-hardware.info/?probe=1499695aae) | Mar 25, 2021 |
| HP            | 18E7                        | [0e835b61ff](https://bsd-hardware.info/?probe=0e835b61ff) | Mar 24, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [78a7c7b8cb](https://bsd-hardware.info/?probe=78a7c7b8cb) | Mar 23, 2021 |
| ASRock        | H71M-DGS                    | [d05d6281d3](https://bsd-hardware.info/?probe=d05d6281d3) | Mar 21, 2021 |
| HP            | 1825                        | [15e822a4dc](https://bsd-hardware.info/?probe=15e822a4dc) | Mar 20, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [f9c3fc3b84](https://bsd-hardware.info/?probe=f9c3fc3b84) | Mar 19, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [5ae508dfa8](https://bsd-hardware.info/?probe=5ae508dfa8) | Mar 19, 2021 |
| Pegatron      | IPM41-D3                    | [fdfc8e2b9b](https://bsd-hardware.info/?probe=fdfc8e2b9b) | Mar 17, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [9f780aff14](https://bsd-hardware.info/?probe=9f780aff14) | Mar 16, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [83aacceb4c](https://bsd-hardware.info/?probe=83aacceb4c) | Mar 16, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [adb0e59aa1](https://bsd-hardware.info/?probe=adb0e59aa1) | Mar 15, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [8964a02114](https://bsd-hardware.info/?probe=8964a02114) | Mar 15, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [0a3b290f9f](https://bsd-hardware.info/?probe=0a3b290f9f) | Mar 15, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [1c30f7523f](https://bsd-hardware.info/?probe=1c30f7523f) | Mar 15, 2021 |
| ASUSTek       | PRIME B350M-A               | [416039a620](https://bsd-hardware.info/?probe=416039a620) | Mar 13, 2021 |
| ASUSTek       | BM6AD_BM1AD_BP1AD           | [60dedd3dcc](https://bsd-hardware.info/?probe=60dedd3dcc) | Mar 13, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [436706f322](https://bsd-hardware.info/?probe=436706f322) | Mar 12, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [002e54c256](https://bsd-hardware.info/?probe=002e54c256) | Mar 12, 2021 |
| Dell          | 0HN7XN A01                  | [3339a68c44](https://bsd-hardware.info/?probe=3339a68c44) | Mar 12, 2021 |
| ASUSTek       | H110M-PLUS                  | [80e7c230d7](https://bsd-hardware.info/?probe=80e7c230d7) | Mar 12, 2021 |
| Dell          | 0W2PJY A01                  | [f162510a27](https://bsd-hardware.info/?probe=f162510a27) | Mar 12, 2021 |
| MSI           | B150M PRO-VDH               | [bc75a3ab13](https://bsd-hardware.info/?probe=bc75a3ab13) | Mar 11, 2021 |
| ASUSTek       | H110M-PLUS                  | [cf00023cef](https://bsd-hardware.info/?probe=cf00023cef) | Mar 11, 2021 |
| ASRock        | B450M Pro4                  | [e9ca160a2d](https://bsd-hardware.info/?probe=e9ca160a2d) | Mar 11, 2021 |
| ASUSTek       | M4A78                       | [00dc46f0a1](https://bsd-hardware.info/?probe=00dc46f0a1) | Mar 10, 2021 |
| Gigabyte      | 970A-DS3P                   | [47d17e6983](https://bsd-hardware.info/?probe=47d17e6983) | Mar 10, 2021 |
| Dell          | 0JP3NX A01                  | [fc94b8c422](https://bsd-hardware.info/?probe=fc94b8c422) | Mar 09, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [66a223add9](https://bsd-hardware.info/?probe=66a223add9) | Mar 08, 2021 |
| ASUSTek       | PRIME B350M-A               | [b79872a08e](https://bsd-hardware.info/?probe=b79872a08e) | Mar 07, 2021 |
| ASUSTek       | P8Z77-V                     | [88ee81b089](https://bsd-hardware.info/?probe=88ee81b089) | Mar 06, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | [a03927cc2e](https://bsd-hardware.info/?probe=a03927cc2e) | Mar 06, 2021 |
| Medion        | H61H2-LM3                   | [01df19257a](https://bsd-hardware.info/?probe=01df19257a) | Mar 05, 2021 |
| Gigabyte      | Z77M-D3H                    | [2f1e8f315f](https://bsd-hardware.info/?probe=2f1e8f315f) | Mar 05, 2021 |
| VeryPC        | S400                        | [77b744169b](https://bsd-hardware.info/?probe=77b744169b) | Mar 04, 2021 |
| ASRock        | 970A-G                      | [3e474f93cf](https://bsd-hardware.info/?probe=3e474f93cf) | Mar 04, 2021 |
| Dell          | 0W2PJY A01                  | [d8c2f0b19f](https://bsd-hardware.info/?probe=d8c2f0b19f) | Mar 04, 2021 |
| Gigabyte      | Z87-D3HP-CF                 | [4c2d7f9b3b](https://bsd-hardware.info/?probe=4c2d7f9b3b) | Mar 03, 2021 |
| Foxconn       | 2ADA                        | [10d02d0982](https://bsd-hardware.info/?probe=10d02d0982) | Mar 03, 2021 |
| HP            | 339A                        | [6b1072ee33](https://bsd-hardware.info/?probe=6b1072ee33) | Mar 01, 2021 |
| HP            | 18E7                        | [091b80c404](https://bsd-hardware.info/?probe=091b80c404) | Mar 01, 2021 |
| Gigabyte      | Z87-D3HP-CF                 | [2af4fda964](https://bsd-hardware.info/?probe=2af4fda964) | Feb 27, 2021 |
| ASRock        | AB350 Pro4                  | [8e0afc66b5](https://bsd-hardware.info/?probe=8e0afc66b5) | Feb 26, 2021 |
| ASRock        | H61M-VG3                    | [68d5d3c6cd](https://bsd-hardware.info/?probe=68d5d3c6cd) | Feb 26, 2021 |
| ASUSTek       | P8Z77-V LX2                 | [0aeea0fec9](https://bsd-hardware.info/?probe=0aeea0fec9) | Feb 23, 2021 |
| ASUSTek       | P5Q                         | [22fa0d8178](https://bsd-hardware.info/?probe=22fa0d8178) | Feb 23, 2021 |
| Intel         | H61                         | [a8ae96a0ab](https://bsd-hardware.info/?probe=a8ae96a0ab) | Feb 23, 2021 |
| ASUSTek       | P8Z77-V LX                  | [8390039d0b](https://bsd-hardware.info/?probe=8390039d0b) | Feb 22, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [58c6bf426e](https://bsd-hardware.info/?probe=58c6bf426e) | Feb 22, 2021 |
| MSI           | A78M-E35                    | [0a1462e4a7](https://bsd-hardware.info/?probe=0a1462e4a7) | Feb 22, 2021 |
| Dell          | 0M863N A01                  | [8dd5cd14a9](https://bsd-hardware.info/?probe=8dd5cd14a9) | Feb 22, 2021 |
| Biostar       | B365MHC                     | [adb029c65f](https://bsd-hardware.info/?probe=adb029c65f) | Feb 22, 2021 |
| Gigabyte      | Z77M-D3H                    | [d0b9e29aed](https://bsd-hardware.info/?probe=d0b9e29aed) | Feb 21, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [405b36b911](https://bsd-hardware.info/?probe=405b36b911) | Feb 21, 2021 |
| Dell          | 0RW199                      | [e0ecb4caa7](https://bsd-hardware.info/?probe=e0ecb4caa7) | Feb 21, 2021 |
| ASUSTek       | P5B-Deluxe                  | [a471763f19](https://bsd-hardware.info/?probe=a471763f19) | Feb 20, 2021 |
| ASUSTek       | PRIME H310M-A               | [cda0bac40d](https://bsd-hardware.info/?probe=cda0bac40d) | Feb 20, 2021 |
| Gigabyte      | GA-870-UD3P                 | [e228db2983](https://bsd-hardware.info/?probe=e228db2983) | Feb 20, 2021 |
| Dell          | 0M863N A01                  | [94f2627d79](https://bsd-hardware.info/?probe=94f2627d79) | Feb 20, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [d60f06a51d](https://bsd-hardware.info/?probe=d60f06a51d) | Feb 20, 2021 |
| ASRock        | 970 Extreme3                | [daa7afc688](https://bsd-hardware.info/?probe=daa7afc688) | Feb 19, 2021 |
| ASUSTek       | PRIME H270-PLUS             | [0b5194e68e](https://bsd-hardware.info/?probe=0b5194e68e) | Feb 19, 2021 |
| ASRock        | Z170 Pro4/D3                | [7df0653726](https://bsd-hardware.info/?probe=7df0653726) | Feb 19, 2021 |
| Unknown       | Unknown                     | [22af66ce96](https://bsd-hardware.info/?probe=22af66ce96) | Feb 18, 2021 |
| ASRock        | B365M Pro4                  | [1c438d977e](https://bsd-hardware.info/?probe=1c438d977e) | Feb 18, 2021 |
| HARDKERNEL    | ODROID-H2                   | [6fe9279f1f](https://bsd-hardware.info/?probe=6fe9279f1f) | Feb 18, 2021 |
| Fujitsu       | D3517-A1 S26361-D3517-A1    | [8891e427e1](https://bsd-hardware.info/?probe=8891e427e1) | Feb 17, 2021 |
| Dell          | 0GM819                      | [836d0f9057](https://bsd-hardware.info/?probe=836d0f9057) | Feb 17, 2021 |
| ASUSTek       | P8H61-MX R2.0               | [e601d28f5e](https://bsd-hardware.info/?probe=e601d28f5e) | Feb 17, 2021 |
| Lenovo        | NO DPK                      | [1ec71f814b](https://bsd-hardware.info/?probe=1ec71f814b) | Feb 17, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [b087324f05](https://bsd-hardware.info/?probe=b087324f05) | Feb 17, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [d03a5bbea5](https://bsd-hardware.info/?probe=d03a5bbea5) | Feb 17, 2021 |
| Lenovo        | ThinkServer TS140           | [29fb200d1a](https://bsd-hardware.info/?probe=29fb200d1a) | Feb 17, 2021 |
| Pegatron      | IPM41-D3                    | [ffc1292c18](https://bsd-hardware.info/?probe=ffc1292c18) | Feb 16, 2021 |
| Lenovo        | Board                       | [966a037b6d](https://bsd-hardware.info/?probe=966a037b6d) | Feb 16, 2021 |
| Gigabyte      | F2A88XM-D3H                 | [c112c8a9fe](https://bsd-hardware.info/?probe=c112c8a9fe) | Feb 16, 2021 |
| MSI           | G41M-P25                    | [3e037419d7](https://bsd-hardware.info/?probe=3e037419d7) | Feb 16, 2021 |
| Pegatron      | IPM41-D3                    | [6e5c330c9c](https://bsd-hardware.info/?probe=6e5c330c9c) | Feb 16, 2021 |
| ASUSTek       | VM62                        | [4d02a33fec](https://bsd-hardware.info/?probe=4d02a33fec) | Feb 16, 2021 |
| Gigabyte      | B360N WIFI-CF               | [0a48ee3b16](https://bsd-hardware.info/?probe=0a48ee3b16) | Feb 16, 2021 |
| Google        | Guado                       | [f6473eeb71](https://bsd-hardware.info/?probe=f6473eeb71) | Feb 16, 2021 |
| ASUSTek       | P5B SE                      | [425210021c](https://bsd-hardware.info/?probe=425210021c) | Feb 16, 2021 |
| HP            | 8768 A                      | [f2be4b7b65](https://bsd-hardware.info/?probe=f2be4b7b65) | Feb 16, 2021 |
| ASUSTek       | P5E-VM SE                   | [89fbf4a403](https://bsd-hardware.info/?probe=89fbf4a403) | Feb 16, 2021 |
| Dell          | 0HY9JP A00                  | [ddabefae47](https://bsd-hardware.info/?probe=ddabefae47) | Feb 15, 2021 |
| HP            | 304Bh                       | [ebd3736a78](https://bsd-hardware.info/?probe=ebd3736a78) | Feb 15, 2021 |
| Intel         | DN2820FYK H24582-201        | [be56203e79](https://bsd-hardware.info/?probe=be56203e79) | Feb 15, 2021 |
| Gigabyte      | B450M DS3H-CF               | [9181a2479b](https://bsd-hardware.info/?probe=9181a2479b) | Feb 15, 2021 |
| HP            | 2B3C                        | [6c628d33ab](https://bsd-hardware.info/?probe=6c628d33ab) | Feb 15, 2021 |
| ASUSTek       | EX-B85M-V                   | [54c319f2c0](https://bsd-hardware.info/?probe=54c319f2c0) | Feb 15, 2021 |
| ASRock        | B450M Pro4                  | [ef29c46355](https://bsd-hardware.info/?probe=ef29c46355) | Feb 15, 2021 |
| HP            | 81B4 01                     | [1bf2cb9506](https://bsd-hardware.info/?probe=1bf2cb9506) | Feb 15, 2021 |
| ASRock        | A300M-STX                   | [9d7266ffc2](https://bsd-hardware.info/?probe=9d7266ffc2) | Feb 15, 2021 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | [02f241b7d7](https://bsd-hardware.info/?probe=02f241b7d7) | Feb 14, 2021 |
| Gigabyte      | Z68X-UD3H-B3                | [290991af1f](https://bsd-hardware.info/?probe=290991af1f) | Feb 14, 2021 |
| ASRock        | B550M Pro4                  | [61a5641019](https://bsd-hardware.info/?probe=61a5641019) | Feb 14, 2021 |
| Gigabyte      | Z97M-D3H                    | [a335917871](https://bsd-hardware.info/?probe=a335917871) | Feb 14, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [c996e74ebc](https://bsd-hardware.info/?probe=c996e74ebc) | Feb 14, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [8082fefc2e](https://bsd-hardware.info/?probe=8082fefc2e) | Feb 14, 2021 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [94167310ae](https://bsd-hardware.info/?probe=94167310ae) | Feb 14, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [565ceb36f0](https://bsd-hardware.info/?probe=565ceb36f0) | Feb 14, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [694204751b](https://bsd-hardware.info/?probe=694204751b) | Feb 13, 2021 |
| Dell          | 0PC5F7 A01                  | [f1e8c08e31](https://bsd-hardware.info/?probe=f1e8c08e31) | Feb 13, 2021 |
| ASUSTek       | Z170-K                      | [aa525de283](https://bsd-hardware.info/?probe=aa525de283) | Feb 13, 2021 |
| Gigabyte      | Z68X-UD3H-B3                | [a2040528cc](https://bsd-hardware.info/?probe=a2040528cc) | Feb 13, 2021 |
| Dell          | 06NWYK A00                  | [32acfb4467](https://bsd-hardware.info/?probe=32acfb4467) | Feb 13, 2021 |
| ASUSTek       | H61M-E                      | [98b498ddb0](https://bsd-hardware.info/?probe=98b498ddb0) | Feb 13, 2021 |
| ASUSTek       | P8H61-M LE                  | [b861820636](https://bsd-hardware.info/?probe=b861820636) | Feb 13, 2021 |
| Dell          | 0KWVT8 A03                  | [289b3114ec](https://bsd-hardware.info/?probe=289b3114ec) | Feb 13, 2021 |
| Dell          | 06NWYK A00                  | [2ff05af403](https://bsd-hardware.info/?probe=2ff05af403) | Feb 13, 2021 |
| ASUSTek       | P8H61-M LE                  | [3a3d7d0701](https://bsd-hardware.info/?probe=3a3d7d0701) | Feb 12, 2021 |
| Google        | Panther                     | [1d1512889f](https://bsd-hardware.info/?probe=1d1512889f) | Feb 12, 2021 |
| HP            | 339A                        | [18b86b645a](https://bsd-hardware.info/?probe=18b86b645a) | Feb 12, 2021 |
| Gigabyte      | Z87-D3HP-CF                 | [64551b8203](https://bsd-hardware.info/?probe=64551b8203) | Feb 12, 2021 |
| HP            | 2B17                        | [572bf634a8](https://bsd-hardware.info/?probe=572bf634a8) | Feb 12, 2021 |
| HP            | 8055                        | [8ecc5bbb55](https://bsd-hardware.info/?probe=8ecc5bbb55) | Feb 12, 2021 |
| ASUSTek       | PRIME B450M-A               | [ac6b550ff4](https://bsd-hardware.info/?probe=ac6b550ff4) | Feb 12, 2021 |
| Lenovo        | MAHOBAY                     | [bacae1ddbb](https://bsd-hardware.info/?probe=bacae1ddbb) | Feb 12, 2021 |
| ASUSTek       | P8H77-V                     | [aaaffba650](https://bsd-hardware.info/?probe=aaaffba650) | Feb 11, 2021 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | [5965bc8a1d](https://bsd-hardware.info/?probe=5965bc8a1d) | Feb 11, 2021 |
| MSI           | PRESTIGE X570 CREATION      | [261aa9d7ab](https://bsd-hardware.info/?probe=261aa9d7ab) | Feb 11, 2021 |
| Intel         | DG41RQ AAE54511-203         | [e0f72bc85e](https://bsd-hardware.info/?probe=e0f72bc85e) | Feb 11, 2021 |
| Intel         | DG41RQ AAE54511-203         | [3030d78460](https://bsd-hardware.info/?probe=3030d78460) | Feb 11, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | [3a6a5a66f7](https://bsd-hardware.info/?probe=3a6a5a66f7) | Feb 11, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [a49ff2b77a](https://bsd-hardware.info/?probe=a49ff2b77a) | Feb 11, 2021 |
| ASUSTek       | M5A78L-M LX PLUS            | [f19ced0784](https://bsd-hardware.info/?probe=f19ced0784) | Feb 11, 2021 |
| Medion        | H81H3-EM2 H81EM2W08.308     | [9958f514c9](https://bsd-hardware.info/?probe=9958f514c9) | Feb 10, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [b507d43de5](https://bsd-hardware.info/?probe=b507d43de5) | Feb 10, 2021 |
| Gigabyte      | B150M-D3H-CF                | [cba616392a](https://bsd-hardware.info/?probe=cba616392a) | Feb 10, 2021 |
| ASRock        | H270M Pro4                  | [37af53e334](https://bsd-hardware.info/?probe=37af53e334) | Feb 10, 2021 |
| Acer          | Aspire X1700                | [06dc1753ef](https://bsd-hardware.info/?probe=06dc1753ef) | Feb 10, 2021 |
| Acer          | Aspire X1700                | [6886acf351](https://bsd-hardware.info/?probe=6886acf351) | Feb 10, 2021 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | [6fdcef7c9e](https://bsd-hardware.info/?probe=6fdcef7c9e) | Feb 10, 2021 |
| MSI           | Z87-G41 PC Mate             | [23fc631dec](https://bsd-hardware.info/?probe=23fc631dec) | Feb 10, 2021 |
| Gigabyte      | Z97P-D3                     | [a3bd8f5772](https://bsd-hardware.info/?probe=a3bd8f5772) | Feb 10, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [9517fd0273](https://bsd-hardware.info/?probe=9517fd0273) | Feb 10, 2021 |
| Dell          | 0PC5F7 A01                  | [f045556287](https://bsd-hardware.info/?probe=f045556287) | Feb 09, 2021 |
| ASUSTek       | PRIME X470-PRO              | [a77e980850](https://bsd-hardware.info/?probe=a77e980850) | Feb 09, 2021 |
| ASRock        | A320M-DGS                   | [7c179e0033](https://bsd-hardware.info/?probe=7c179e0033) | Feb 06, 2021 |
| Dell          | 096JG8 A00                  | [e73a728a76](https://bsd-hardware.info/?probe=e73a728a76) | Feb 03, 2021 |
| Dell          | 096JG8 A00                  | [612272e598](https://bsd-hardware.info/?probe=612272e598) | Feb 03, 2021 |
| Acer          | EM61SM/EM61PM               | [b82613052e](https://bsd-hardware.info/?probe=b82613052e) | Jan 27, 2021 |
| ASRock        | X399 Taichi                 | [875e6714ca](https://bsd-hardware.info/?probe=875e6714ca) | Jan 27, 2021 |
| Acer          | RevoOne RL85                | [6cbf99ef86](https://bsd-hardware.info/?probe=6cbf99ef86) | Jan 26, 2021 |
| Acer          | RevoOne RL85                | [c51b959fcc](https://bsd-hardware.info/?probe=c51b959fcc) | Jan 26, 2021 |
| Acer          | RevoOne RL85                | [ce03b7b713](https://bsd-hardware.info/?probe=ce03b7b713) | Jan 23, 2021 |
| Dell          | 088DT1 A01                  | [fcc759e013](https://bsd-hardware.info/?probe=fcc759e013) | Jan 21, 2021 |
| ASUSTek       | VM40B                       | [58b6a3291e](https://bsd-hardware.info/?probe=58b6a3291e) | Jan 21, 2021 |
| Dell          | 0Y7WYT A00                  | [4af9b92154](https://bsd-hardware.info/?probe=4af9b92154) | Jan 19, 2021 |
| MSI           | Boston                      | [aa9d7bae21](https://bsd-hardware.info/?probe=aa9d7bae21) | Jan 17, 2021 |
| MSI           | Boston                      | [f21954fa35](https://bsd-hardware.info/?probe=f21954fa35) | Jan 17, 2021 |
| Gigabyte      | TRX40 DESIGNARE             | [f506b21449](https://bsd-hardware.info/?probe=f506b21449) | Jan 17, 2021 |
| Dell          | 0M863N A01                  | [4feae8b20d](https://bsd-hardware.info/?probe=4feae8b20d) | Jan 15, 2021 |
| ASUSTek       | Z170-A                      | [271f2c1186](https://bsd-hardware.info/?probe=271f2c1186) | Jan 12, 2021 |
| Acer          | RevoOne RL85                | [e419e4c937](https://bsd-hardware.info/?probe=e419e4c937) | Jan 03, 2021 |
| Acer          | RevoOne RL85                | [259c54d264](https://bsd-hardware.info/?probe=259c54d264) | Jan 02, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| helloSystem 0.5.0 | 114      | 28.43%  |
| helloSystem 0.7.0 | 113      | 28.18%  |
| helloSystem 0.4.0 | 90       | 22.44%  |
| helloSystem 0.6.0 | 60       | 14.96%  |
| helloSystem 0.8.0 | 15       | 3.74%   |
| helloSystem 0.3.0 | 9        | 2.24%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| helloSystem | 377      | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 377      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 376      | 99.47%  |
| GNOME        | 2        | 0.53%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 377      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 377      | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 368      | 97.35%  |
| es_ES | 4        | 1.06%   |
| fr_FR | 2        | 0.53%   |
| it_IT | 1        | 0.26%   |
| es_AR | 1        | 0.26%   |
| de_DE | 1        | 0.26%   |
| C     | 1        | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 334      | 88.13%  |
| BIOS | 45       | 11.87%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Zfs    | 308      | 79.38%  |
| Cd9660 | 80       | 20.62%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 372      | 98.67%  |
| MBR  | 5        | 1.33%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 107      | 28.38%  |
| Gigabyte Technology | 49       | 13%     |
| ASRock              | 41       | 10.88%  |
| Dell                | 37       | 9.81%   |
| Hewlett-Packard     | 33       | 8.75%   |
| MSI                 | 23       | 6.1%    |
| Lenovo              | 15       | 3.98%   |
| Intel               | 15       | 3.98%   |
| Acer                | 6        | 1.59%   |
| Pegatron            | 5        | 1.33%   |
| Biostar             | 5        | 1.33%   |
| Foxconn             | 4        | 1.06%   |
| Apple               | 4        | 1.06%   |
| Unknown             | 4        | 1.06%   |
| Fujitsu             | 3        | 0.8%    |
| Shuttle             | 2        | 0.53%   |
| Medion              | 2        | 0.53%   |
| Google              | 2        | 0.53%   |
| VeryPC              | 1        | 0.27%   |
| T-bao               | 1        | 0.27%   |
| Supermicro          | 1        | 0.27%   |
| Sapphire            | 1        | 0.27%   |
| Quanta              | 1        | 0.27%   |
| Protectli           | 1        | 0.27%   |
| PCPartner           | 1        | 0.27%   |
| Packard Bell        | 1        | 0.27%   |
| MACHINIST           | 1        | 0.27%   |
| Koloe               | 1        | 0.27%   |
| Itautec             | 1        | 0.27%   |
| Huanan              | 1        | 0.27%   |
| HC                  | 1        | 0.27%   |
| HARDKERNEL          | 1        | 0.27%   |
| Gateway             | 1        | 0.27%   |
| EVGA                | 1        | 0.27%   |
| ECS                 | 1        | 0.27%   |
| BESSTAR Tech        | 1        | 0.27%   |
| AMD                 | 1        | 0.27%   |
| Acidanthera         | 1        | 0.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 5        | 1.33%   |
| Unknown                            | 4        | 1.06%   |
| Dell OptiPlex 9020                 | 3        | 0.8%    |
| ASUS P8Z77-V LX                    | 3        | 0.8%    |
| ASUS M5A78L-M/USB3                 | 3        | 0.8%    |
| Apple MacPro5,1                    | 3        | 0.8%    |
| MSI MS-7B86                        | 2        | 0.53%   |
| MSI MS-7592                        | 2        | 0.53%   |
| Intel H61                          | 2        | 0.53%   |
| HP ProDesk 600 G1 SFF              | 2        | 0.53%   |
| HP EliteDesk 800 G2 SFF            | 2        | 0.53%   |
| HP EliteDesk 800 G1 DM             | 2        | 0.53%   |
| HP EliteDesk 700 G1 SFF            | 2        | 0.53%   |
| HP Compaq Elite 8300 SFF           | 2        | 0.53%   |
| Gigabyte X570 AORUS ELITE          | 2        | 0.53%   |
| Gigabyte B450 AORUS M              | 2        | 0.53%   |
| Gigabyte 970A-DS3P                 | 2        | 0.53%   |
| Dell OptiPlex 990                  | 2        | 0.53%   |
| Dell OptiPlex 760                  | 2        | 0.53%   |
| Dell OptiPlex 755                  | 2        | 0.53%   |
| Dell OptiPlex 7040                 | 2        | 0.53%   |
| Dell OptiPlex 7010                 | 2        | 0.53%   |
| Biostar B365MHC                    | 2        | 0.53%   |
| ASUS TUF GAMING X570-PLUS          | 2        | 0.53%   |
| ASUS ROG STRIX B450-F GAMING       | 2        | 0.53%   |
| ASUS PRIME B450M-A                 | 2        | 0.53%   |
| ASUS PRIME B350M-A                 | 2        | 0.53%   |
| ASUS PRIME A320M-K                 | 2        | 0.53%   |
| ASUS P5P43TD PRO                   | 2        | 0.53%   |
| ASUS P5B SE                        | 2        | 0.53%   |
| ASUS CROSSHAIR V FORMULA-Z         | 2        | 0.53%   |
| ASRock X570 Phantom Gaming 4       | 2        | 0.53%   |
| ASRock B550M Pro4                  | 2        | 0.53%   |
| ASRock B460M Pro4                  | 2        | 0.53%   |
| ASRock B450M Pro4                  | 2        | 0.53%   |
| ASRock B365M Pro4                  | 2        | 0.53%   |
| ASRock A300M-STX                   | 2        | 0.53%   |
| VeryPC S400-K7-N-O                 | 1        | 0.27%   |
| T-bao MINI PC                      | 1        | 0.27%   |
| Supermicro X9DAL                   | 1        | 0.27%   |
| Shuttle SH61R                      | 1        | 0.27%   |
| Shuttle NC10U                      | 1        | 0.27%   |
| Sapphire EDGE-FT1M1 E450 1AOVU044  | 1        | 0.27%   |
| Quanta 120-1135                    | 1        | 0.27%   |
| Protectli FW2B                     | 1        | 0.27%   |
| Pegatron SAISHIAT2                 | 1        | 0.27%   |
| Pegatron IPPPV-D3G                 | 1        | 0.27%   |
| Pegatron IPM41-D3                  | 1        | 0.27%   |
| Pegatron Compaq 505B Microtower PC | 1        | 0.27%   |
| Pegatron AY627AA-ABA a4313w        | 1        | 0.27%   |
| PCPartner DREAMSYS                 | 1        | 0.27%   |
| Packard Bell imedia S2110          | 1        | 0.27%   |
| MSI WC791AA-UUW HPE-119sc          | 1        | 0.27%   |
| MSI NR074AA-ABZ CQ5125IT           | 1        | 0.27%   |
| MSI MS-7D25                        | 1        | 0.27%   |
| MSI MS-7C91                        | 1        | 0.27%   |
| MSI MS-7C52                        | 1        | 0.27%   |
| MSI MS-7C37                        | 1        | 0.27%   |
| MSI MS-7C02                        | 1        | 0.27%   |
| MSI MS-7B93                        | 1        | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 23       | 6.1%    |
| ASUS PRIME           | 16       | 4.24%   |
| Lenovo ThinkCentre   | 11       | 2.92%   |
| ASUS ROG             | 11       | 2.92%   |
| HP Compaq            | 8        | 2.12%   |
| HP EliteDesk         | 7        | 1.86%   |
| Dell Precision       | 6        | 1.59%   |
| ASUS P8Z77-V         | 6        | 1.59%   |
| ASUS M5A78L-M        | 6        | 1.59%   |
| ASUS TUF             | 5        | 1.33%   |
| ASUS All             | 5        | 1.33%   |
| HP ProDesk           | 4        | 1.06%   |
| Gigabyte B450        | 4        | 1.06%   |
| Dell Inspiron        | 4        | 1.06%   |
| ASUS Crosshair       | 4        | 1.06%   |
| Unknown              | 4        | 1.06%   |
| Apple MacPro5        | 3        | 0.8%    |
| Acer Aspire          | 3        | 0.8%    |
| MSI MS-7B86          | 2        | 0.53%   |
| MSI MS-7592          | 2        | 0.53%   |
| Intel H61            | 2        | 0.53%   |
| HP Slim              | 2        | 0.53%   |
| Gigabyte X570        | 2        | 0.53%   |
| Gigabyte B450M       | 2        | 0.53%   |
| Gigabyte 970A-DS3P   | 2        | 0.53%   |
| Biostar B365MHC      | 2        | 0.53%   |
| ASUS P8H61-M         | 2        | 0.53%   |
| ASUS P7H55-M         | 2        | 0.53%   |
| ASUS P5Q             | 2        | 0.53%   |
| ASUS P5P43TD         | 2        | 0.53%   |
| ASUS P5B             | 2        | 0.53%   |
| ASUS M5A97           | 2        | 0.53%   |
| ASUS M5A78L          | 2        | 0.53%   |
| ASRock X570          | 2        | 0.53%   |
| ASRock B550M         | 2        | 0.53%   |
| ASRock B460M         | 2        | 0.53%   |
| ASRock B450M         | 2        | 0.53%   |
| ASRock B365M         | 2        | 0.53%   |
| ASRock AB350         | 2        | 0.53%   |
| ASRock A300M-STX     | 2        | 0.53%   |
| VeryPC S400-K7-N-O   | 1        | 0.27%   |
| T-bao MINI           | 1        | 0.27%   |
| Supermicro X9DAL     | 1        | 0.27%   |
| Shuttle SH61R        | 1        | 0.27%   |
| Shuttle NC10U        | 1        | 0.27%   |
| Sapphire EDGE-FT1M1  | 1        | 0.27%   |
| Quanta 120-1135      | 1        | 0.27%   |
| Protectli FW2B       | 1        | 0.27%   |
| Pegatron SAISHIAT2   | 1        | 0.27%   |
| Pegatron IPPPV-D3G   | 1        | 0.27%   |
| Pegatron IPM41-D3    | 1        | 0.27%   |
| Pegatron Compaq      | 1        | 0.27%   |
| Pegatron AY627AA-ABA | 1        | 0.27%   |
| PCPartner DREAMSYS   | 1        | 0.27%   |
| Packard Bell imedia  | 1        | 0.27%   |
| MSI WC791AA-UUW      | 1        | 0.27%   |
| MSI NR074AA-ABZ      | 1        | 0.27%   |
| MSI MS-7D25          | 1        | 0.27%   |
| MSI MS-7C91          | 1        | 0.27%   |
| MSI MS-7C52          | 1        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 46       | 12.2%   |
| 2018 | 41       | 10.88%  |
| 2020 | 35       | 9.28%   |
| 2013 | 35       | 9.28%   |
| 2012 | 34       | 9.02%   |
| 2021 | 31       | 8.22%   |
| 2014 | 31       | 8.22%   |
| 2010 | 24       | 6.37%   |
| 2016 | 22       | 5.84%   |
| 2011 | 20       | 5.31%   |
| 2017 | 16       | 4.24%   |
| 2015 | 15       | 3.98%   |
| 2009 | 13       | 3.45%   |
| 2008 | 8        | 2.12%   |
| 2007 | 6        | 1.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 377      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 375      | 99.47%  |
| Yes  | 2        | 0.53%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 114      | 30.16%  |
| 8.01-16.0   | 107      | 28.31%  |
| 4.01-8.0    | 80       | 21.16%  |
| 32.01-64.0  | 50       | 13.23%  |
| 64.01-256.0 | 13       | 3.44%   |
| 24.01-32.0  | 6        | 1.59%   |
| 2.01-3.0    | 6        | 1.59%   |
| 1.01-2.0    | 1        | 0.26%   |
| 0.51-1.0    | 1        | 0.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 167      | 43.83%  |
| 0.51-1.0  | 133      | 34.91%  |
| 1.01-2.0  | 67       | 17.59%  |
| 2.01-3.0  | 9        | 2.36%   |
| 3.01-4.0  | 3        | 0.79%   |
| 4.01-8.0  | 1        | 0.26%   |
| 8.01-16.0 | 1        | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 170      | 43.81%  |
| 2      | 98       | 25.26%  |
| 3      | 48       | 12.37%  |
| 4      | 35       | 9.02%   |
| 0      | 15       | 3.87%   |
| 5      | 10       | 2.58%   |
| 6      | 7        | 1.8%    |
| 7      | 2        | 0.52%   |
| 10     | 1        | 0.26%   |
| 9      | 1        | 0.26%   |
| 8      | 1        | 0.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 232      | 61.54%  |
| Yes       | 145      | 38.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 372      | 98.67%  |
| No        | 5        | 1.33%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 259      | 68.52%  |
| Yes       | 119      | 31.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 276      | 72.82%  |
| Yes       | 103      | 27.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 55       | 14.59%  |
| Russia       | 42       | 11.14%  |
| Germany      | 38       | 10.08%  |
| UK           | 18       | 4.77%   |
| Spain        | 16       | 4.24%   |
| Italy        | 16       | 4.24%   |
| Brazil       | 16       | 4.24%   |
| Canada       | 15       | 3.98%   |
| Ukraine      | 14       | 3.71%   |
| France       | 14       | 3.71%   |
| Poland       | 11       | 2.92%   |
| China        | 11       | 2.92%   |
| Hungary      | 10       | 2.65%   |
| Australia    | 9        | 2.39%   |
| India        | 8        | 2.12%   |
| Taiwan       | 6        | 1.59%   |
| Mexico       | 6        | 1.59%   |
| South Korea  | 5        | 1.33%   |
| Turkey       | 4        | 1.06%   |
| Finland      | 4        | 1.06%   |
| Peru         | 3        | 0.8%    |
| Guatemala    | 3        | 0.8%    |
| Greece       | 3        | 0.8%    |
| Chile        | 3        | 0.8%    |
| Argentina    | 3        | 0.8%    |
| Thailand     | 2        | 0.53%   |
| Switzerland  | 2        | 0.53%   |
| South Africa | 2        | 0.53%   |
| Romania      | 2        | 0.53%   |
| Portugal     | 2        | 0.53%   |
| Norway       | 2        | 0.53%   |
| Netherlands  | 2        | 0.53%   |
| Egypt        | 2        | 0.53%   |
| Denmark      | 2        | 0.53%   |
| Bulgaria     | 2        | 0.53%   |
| Vietnam      | 1        | 0.27%   |
| Venezuela    | 1        | 0.27%   |
| Uruguay      | 1        | 0.27%   |
| Sweden       | 1        | 0.27%   |
| Slovenia     | 1        | 0.27%   |
| Slovakia     | 1        | 0.27%   |
| Philippines  | 1        | 0.27%   |
| Panama       | 1        | 0.27%   |
| New Zealand  | 1        | 0.27%   |
| Macao        | 1        | 0.27%   |
| Lithuania    | 1        | 0.27%   |
| Kazakhstan   | 1        | 0.27%   |
| Japan        | 1        | 0.27%   |
| Ireland      | 1        | 0.27%   |
| Indonesia    | 1        | 0.27%   |
| Iceland      | 1        | 0.27%   |
| Hong Kong    | 1        | 0.27%   |
| Eswatini     | 1        | 0.27%   |
| Estonia      | 1        | 0.27%   |
| Ecuador      | 1        | 0.27%   |
| Croatia      | 1        | 0.27%   |
| Colombia     | 1        | 0.27%   |
| Belgium      | 1        | 0.27%   |
| Belarus      | 1        | 0.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| St Petersburg           | 6        | 1.52%   |
| Paris                   | 5        | 1.27%   |
| Moscow                  | 5        | 1.27%   |
| Kyiv                    | 4        | 1.01%   |
| SГЈo Paulo            | 3        | 0.76%   |
| Munich                  | 3        | 0.76%   |
| Guatemala City          | 3        | 0.76%   |
| Chelyabinsk             | 3        | 0.76%   |
| Brisbane                | 3        | 0.76%   |
| Barnaul                 | 3        | 0.76%   |
| Yekaterinburg           | 2        | 0.51%   |
| Voronezh                | 2        | 0.51%   |
| Ufa                     | 2        | 0.51%   |
| Surgut                  | 2        | 0.51%   |
| Stuttgart               | 2        | 0.51%   |
| Stourbridge             | 2        | 0.51%   |
| Sheffield               | 2        | 0.51%   |
| Sevastopol              | 2        | 0.51%   |
| Santiago                | 2        | 0.51%   |
| Rudersberg              | 2        | 0.51%   |
| Pflugerville            | 2        | 0.51%   |
| Myrtle Beach            | 2        | 0.51%   |
| Melbourne               | 2        | 0.51%   |
| Marlborough             | 2        | 0.51%   |
| Lima                    | 2        | 0.51%   |
| Kitchener               | 2        | 0.51%   |
| Kharkiv                 | 2        | 0.51%   |
| Independence            | 2        | 0.51%   |
| Hsinchu                 | 2        | 0.51%   |
| Hobart                  | 2        | 0.51%   |
| Helsinki                | 2        | 0.51%   |
| Greater Sudbury         | 2        | 0.51%   |
| Ernakulam               | 2        | 0.51%   |
| Dnipropetrovsk          | 2        | 0.51%   |
| Curitiba                | 2        | 0.51%   |
| Chennai                 | 2        | 0.51%   |
| Castilleja de la Cuesta | 2        | 0.51%   |
| Calgary                 | 2        | 0.51%   |
| Buenos Aires            | 2        | 0.51%   |
| Е iauliai             | 1        | 0.25%   |
| Zhongshan               | 1        | 0.25%   |
| Zaragoza                | 1        | 0.25%   |
| Zajaczki Pierwsze       | 1        | 0.25%   |
| Yunlin                  | 1        | 0.25%   |
| York                    | 1        | 0.25%   |
| Yarang                  | 1        | 0.25%   |
| Xiamen                  | 1        | 0.25%   |
| Wolgast                 | 1        | 0.25%   |
| Winnipeg                | 1        | 0.25%   |
| Wesley Chapel           | 1        | 0.25%   |
| Watford                 | 1        | 0.25%   |
| Warsaw                  | 1        | 0.25%   |
| Warrenton               | 1        | 0.25%   |
| Ware                    | 1        | 0.25%   |
| Volgograd               | 1        | 0.25%   |
| Vladivostok             | 1        | 0.25%   |
| Villeurbanne            | 1        | 0.25%   |
| Vereeniging             | 1        | 0.25%   |
| Vawkavysk               | 1        | 0.25%   |
| Valencia                | 1        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 125      | 185    | 19.75%  |
| Seagate             | 118      | 183    | 18.64%  |
| Samsung Electronics | 96       | 145    | 15.17%  |
| Kingston            | 41       | 50     | 6.48%   |
| Toshiba             | 38       | 45     | 6%      |
| Crucial             | 32       | 50     | 5.06%   |
| SanDisk             | 23       | 26     | 3.63%   |
| Hitachi             | 23       | 29     | 3.63%   |
| A-DATA Technology   | 14       | 22     | 2.21%   |
| Intel               | 12       | 12     | 1.9%    |
| SPCC                | 9        | 10     | 1.42%   |
| HGST                | 9        | 9      | 1.42%   |
| SK Hynix            | 7        | 10     | 1.11%   |
| Phison              | 7        | 10     | 1.11%   |
| GOODRAM             | 7        | 7      | 1.11%   |
| Gigabyte Technology | 6        | 8      | 0.95%   |
| PNY                 | 5        | 15     | 0.79%   |
| Patriot             | 4        | 4      | 0.63%   |
| Apacer              | 4        | 4      | 0.63%   |
| Silicon Motion      | 3        | 3      | 0.47%   |
| OCZ                 | 3        | 4      | 0.47%   |
| Micron Technology   | 3        | 3      | 0.47%   |
| KingSpec            | 3        | 5      | 0.47%   |
| Hewlett-Packard     | 3        | 3      | 0.47%   |
| Corsair             | 3        | 3      | 0.47%   |
| Apple               | 3        | 3      | 0.47%   |
| XPG                 | 2        | 2      | 0.32%   |
| Transcend           | 2        | 2      | 0.32%   |
| Smartbuy            | 2        | 2      | 0.32%   |
| PLEXTOR             | 2        | 2      | 0.32%   |
| LITEON              | 2        | 2      | 0.32%   |
| Intenso             | 2        | 3      | 0.32%   |
| Fujitsu             | 2        | 3      | 0.32%   |
| EMTEC               | 2        | 3      | 0.32%   |
| China               | 2        | 2      | 0.32%   |
| Verbatim            | 1        | 1      | 0.16%   |
| ORICO               | 1        | 2      | 0.16%   |
| Mushkin             | 1        | 1      | 0.16%   |
| MAXTOR              | 1        | 1      | 0.16%   |
| LSI                 | 1        | 1      | 0.16%   |
| LITEONIT            | 1        | 1      | 0.16%   |
| Lite-On             | 1        | 1      | 0.16%   |
| Lexar               | 1        | 2      | 0.16%   |
| Leven               | 1        | 2      | 0.16%   |
| Lenovo              | 1        | 1      | 0.16%   |
| LDLC                | 1        | 1      | 0.16%   |
| Hoodisk             | 1        | 1      | 0.16%   |
| Enmotus             | 1        | 1      | 0.16%   |
| CLOVER              | 1        | 1      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB               | 10       | 1.36%   |
| Samsung SSD 850 EVO 250GB               | 10       | 1.36%   |
| Seagate ST1000DM003-1ER162 1TB          | 9        | 1.22%   |
| Toshiba DT01ACA100 1TB                  | 8        | 1.08%   |
| Seagate ST500DM002-1BD142 500GB         | 8        | 1.08%   |
| Samsung SSD 860 EVO 250GB               | 7        | 0.95%   |
| Kingston SA400S37240G 240GB             | 7        | 0.95%   |
| Kingston SA400S37120G 120GB             | 7        | 0.95%   |
| Crucial CT500MX500SSD1 500GB            | 7        | 0.95%   |
| Seagate ST2000DM008-2FR102 2TB          | 6        | 0.81%   |
| Seagate ST1000DM010-2EP102 1TB          | 6        | 0.81%   |
| Samsung HD322HJ 320GB                   | 6        | 0.81%   |
| Samsung HD103SI 1TB                     | 5        | 0.68%   |
| WDC WDS100T2B0A-00SM50 1TB              | 4        | 0.54%   |
| Toshiba HDWD110 1TB                     | 4        | 0.54%   |
| Seagate ST4000DM004-2CV104 4TB          | 4        | 0.54%   |
| Seagate ST3500312CS 500GB               | 4        | 0.54%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 4        | 0.54%   |
| SanDisk SDSSDA240G 240GB                | 4        | 0.54%   |
| Samsung SSD 970 EVO Plus 500GB          | 4        | 0.54%   |
| Samsung SSD 970 EVO 250GB               | 4        | 0.54%   |
| Samsung SSD 860 EVO 1TB                 | 4        | 0.54%   |
| Kingston SV300S37A120G 120GB            | 4        | 0.54%   |
| Kingston SA2000M8250G 250GB             | 4        | 0.54%   |
| A-DATA SU650 120GB                      | 4        | 0.54%   |
| WDC WDS500G2B0A-00SM50 500GB            | 3        | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB            | 3        | 0.41%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 3        | 0.41%   |
| WDC WD5000AAKX-00ERMA0 500GB            | 3        | 0.41%   |
| WDC WD10EZEX-08WN4A0 1TB                | 3        | 0.41%   |
| Toshiba DT01ACA050 500GB                | 3        | 0.41%   |
| SPCC Solid State Disk 512GB             | 3        | 0.41%   |
| SK Hynix BC501 HFM128GDJTNG-8310A 128GB | 3        | 0.41%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 3        | 0.41%   |
| Seagate ST3500413AS 500GB               | 3        | 0.41%   |
| Seagate ST3320418AS 320GB               | 3        | 0.41%   |
| Seagate ST3250410AS 250GB               | 3        | 0.41%   |
| Seagate ST31000528AS 1TB                | 3        | 0.41%   |
| Seagate ST2000DM006-2DM164 2TB          | 3        | 0.41%   |
| Seagate ST2000DM001-1CH164 2TB          | 3        | 0.41%   |
| Seagate ST1000LM035-1RK172 1TB          | 3        | 0.41%   |
| Seagate ST1000DM003-1CH162 1TB          | 3        | 0.41%   |
| SanDisk SDSSDA120G 120GB                | 3        | 0.41%   |
| Samsung SSD 960 EVO 500GB               | 3        | 0.41%   |
| Samsung SSD 840 EVO 250GB               | 3        | 0.41%   |
| Samsung HD502HJ 500GB                   | 3        | 0.41%   |
| Kingston SA2000M8500G 500GB             | 3        | 0.41%   |
| Hitachi HDS721050CLA362 500GB           | 3        | 0.41%   |
| HGST HTS725050A7E630 500GB              | 3        | 0.41%   |
| HGST HTS545032A7E380 320GB              | 3        | 0.41%   |
| Crucial CT256MX100SSD1 256GB            | 3        | 0.41%   |
| Crucial CT250MX500SSD1 250GB            | 3        | 0.41%   |
| Crucial CT240BX500SSD1 240GB            | 3        | 0.41%   |
| Crucial CT120BX500SSD1 120GB            | 3        | 0.41%   |
| XPG GAMMIX S11 Pro 256GB                | 2        | 0.27%   |
| WDC WDS250G1B0A-00H9H0 250GB            | 2        | 0.27%   |
| WDC WDS120G2G0A-00JH30 120GB            | 2        | 0.27%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 2        | 0.27%   |
| WDC WD40EFRX-68WT0N0 4TB                | 2        | 0.27%   |
| WDC WD40EFRX-68N32N0 4TB                | 2        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 118      | 180    | 36.76%  |
| WDC                 | 108      | 149    | 33.64%  |
| Toshiba             | 31       | 36     | 9.66%   |
| Samsung Electronics | 28       | 39     | 8.72%   |
| Hitachi             | 23       | 29     | 7.17%   |
| HGST                | 9        | 9      | 2.8%    |
| Fujitsu             | 2        | 3      | 0.62%   |
| MAXTOR              | 1        | 1      | 0.31%   |
| CLOVER              | 1        | 1      | 0.31%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 49       | 69     | 20.25%  |
| Kingston            | 34       | 41     | 14.05%  |
| Crucial             | 30       | 47     | 12.4%   |
| SanDisk             | 23       | 26     | 9.5%    |
| WDC                 | 15       | 22     | 6.2%    |
| A-DATA Technology   | 11       | 12     | 4.55%   |
| SPCC                | 7        | 8      | 2.89%   |
| Intel               | 7        | 7      | 2.89%   |
| GOODRAM             | 7        | 7      | 2.89%   |
| Toshiba             | 6        | 8      | 2.48%   |
| PNY                 | 5        | 13     | 2.07%   |
| Patriot             | 4        | 4      | 1.65%   |
| Apacer              | 4        | 4      | 1.65%   |
| OCZ                 | 3        | 4      | 1.24%   |
| Micron Technology   | 3        | 3      | 1.24%   |
| KingSpec            | 3        | 5      | 1.24%   |
| Gigabyte Technology | 3        | 4      | 1.24%   |
| Apple               | 3        | 3      | 1.24%   |
| Transcend           | 2        | 2      | 0.83%   |
| Smartbuy            | 2        | 2      | 0.83%   |
| PLEXTOR             | 2        | 2      | 0.83%   |
| LITEON              | 2        | 2      | 0.83%   |
| Intenso             | 2        | 3      | 0.83%   |
| EMTEC               | 2        | 3      | 0.83%   |
| China               | 2        | 2      | 0.83%   |
| Verbatim            | 1        | 1      | 0.41%   |
| SK Hynix            | 1        | 1      | 0.41%   |
| ORICO               | 1        | 2      | 0.41%   |
| LSI                 | 1        | 1      | 0.41%   |
| LITEONIT            | 1        | 1      | 0.41%   |
| Lite-On             | 1        | 1      | 0.41%   |
| Lexar               | 1        | 1      | 0.41%   |
| Leven               | 1        | 2      | 0.41%   |
| Lenovo              | 1        | 1      | 0.41%   |
| Hoodisk             | 1        | 1      | 0.41%   |
| Hewlett-Packard     | 1        | 1      | 0.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 250      | 447    | 47.35%  |
| SSD  | 192      | 316    | 36.36%  |
| NVMe | 86       | 123    | 16.29%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 344      | 763    | 80%     |
| NVMe | 86       | 123    | 20%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 290      | 492    | 60.92%  |
| 0.51-1.0   | 111      | 158    | 23.32%  |
| 1.01-2.0   | 38       | 51     | 7.98%   |
| 3.01-4.0   | 17       | 28     | 3.57%   |
| 2.01-3.0   | 10       | 21     | 2.1%    |
| 4.01-10.0  | 9        | 12     | 1.89%   |
| 10.01-20.0 | 1        | 1      | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 263      | 67.78%  |
| 101-250    | 62       | 15.98%  |
| 251-500    | 32       | 8.25%   |
| 501-1000   | 17       | 4.38%   |
| 51-100     | 8        | 2.06%   |
| 21-50      | 5        | 1.29%   |
| 1001-2000  | 1        | 0.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 376      | 99.73%  |
| 21-50   | 1        | 0.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 3        | 4      | 2.48%   |
| Seagate ST3250410AS 250GB           | 3        | 3      | 2.48%   |
| Samsung Electronics HD322HJ 320GB   | 3        | 3      | 2.48%   |
| HGST HTS545032A7E380 320GB          | 3        | 3      | 2.48%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 2        | 2      | 1.65%   |
| Toshiba DT01ACA100 1TB              | 2        | 5      | 1.65%   |
| Seagate ST9320325AS 320GB           | 2        | 2      | 1.65%   |
| Seagate ST380815AS 80GB             | 2        | 2      | 1.65%   |
| Seagate ST3500413AS 500GB           | 2        | 5      | 1.65%   |
| Seagate ST3320418AS 320GB           | 2        | 2      | 1.65%   |
| Seagate ST31000528AS 1TB            | 2        | 3      | 1.65%   |
| Samsung Electronics HD161HJ 160GB   | 2        | 2      | 1.65%   |
| WDC WDS240G2G0A-00JH30 240GB        | 1        | 1      | 0.83%   |
| WDC WD800JD-55MUA1 80GB             | 1        | 1      | 0.83%   |
| WDC WD6400AAKS-22A7B0 640GB         | 1        | 1      | 0.83%   |
| WDC WD60EZRZ-00RWYB1 6TB            | 1        | 1      | 0.83%   |
| WDC WD5000AZLX-00CL5A0 500GB        | 1        | 1      | 0.83%   |
| WDC WD5000AVCS-632DY1 500GB         | 1        | 1      | 0.83%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 1        | 1      | 0.83%   |
| WDC WD5000AAKX-08ERMA0 500GB        | 1        | 1      | 0.83%   |
| WDC WD5000AAKS-22A7B0 500GB         | 1        | 1      | 0.83%   |
| WDC WD5000AAKS-08V0A0 500GB         | 1        | 1      | 0.83%   |
| WDC WD5000AAKS-00V1A0 500GB         | 1        | 1      | 0.83%   |
| WDC WD5000AAKS-00E4A0 500GB         | 1        | 1      | 0.83%   |
| WDC WD40EFRX-68WT0N0 4TB            | 1        | 1      | 0.83%   |
| WDC WD400JB-00ENA0 40GB             | 1        | 1      | 0.83%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 1        | 1      | 0.83%   |
| WDC WD3200BEVT-00A0RT0 233GB        | 1        | 1      | 0.83%   |
| WDC WD3200AAKS-00UU3A0 320GB        | 1        | 1      | 0.83%   |
| WDC WD3200AAJS-22B4A0 320GB         | 1        | 1      | 0.83%   |
| WDC WD3200AAJS-00L7A0 320GB         | 1        | 1      | 0.83%   |
| WDC WD30EZRX-22D8PB0 3TB            | 1        | 1      | 0.83%   |
| WDC WD2500AAKX-083CA1 250GB         | 1        | 2      | 0.83%   |
| WDC WD20EVDS-63T3B0 2TB             | 1        | 1      | 0.83%   |
| WDC WD20EARX-00PASB0 2TB            | 1        | 1      | 0.83%   |
| WDC WD20EARS-00MVWB0 2TB            | 1        | 1      | 0.83%   |
| WDC WD2002FYPS-01U1B1 2TB           | 1        | 1      | 0.83%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 1        | 1      | 0.83%   |
| WDC WD1600AAJS-60WAA0 160GB         | 1        | 1      | 0.83%   |
| WDC WD1600AAJS-00WAA0 160GB         | 1        | 1      | 0.83%   |
| WDC WD10JMVW-11AJGS0 1TB            | 1        | 1      | 0.83%   |
| WDC WD10EZEX-08M2NA0 1TB            | 1        | 1      | 0.83%   |
| WDC WD10EZEX-00RKKA0 1TB            | 1        | 1      | 0.83%   |
| WDC WD10EAVS-00D7B0 1TB             | 1        | 1      | 0.83%   |
| WDC WD10EARS-00Y5B1 1TB             | 1        | 1      | 0.83%   |
| WDC WD10EARS-003BB1 1TB             | 1        | 1      | 0.83%   |
| Toshiba THNSNK128GCS8 SATA 128GB    | 1        | 1      | 0.83%   |
| Toshiba MQ01UBD100 1TB              | 1        | 1      | 0.83%   |
| Toshiba MK3276GSX 320GB             | 1        | 1      | 0.83%   |
| Toshiba MD04ACA400 4TB              | 1        | 1      | 0.83%   |
| Toshiba DT01ABA300 3TB              | 1        | 1      | 0.83%   |
| Seagate ST9500325AS 500GB           | 1        | 1      | 0.83%   |
| Seagate ST9160314AS 160GB           | 1        | 1      | 0.83%   |
| Seagate ST8000NM0055-1RM112 8TB     | 1        | 1      | 0.83%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1        | 1      | 0.83%   |
| Seagate ST500VT000-1DK142 500GB     | 1        | 1      | 0.83%   |
| Seagate ST380211AS 80GB             | 1        | 1      | 0.83%   |
| Seagate ST3750640AS 752GB           | 1        | 1      | 0.83%   |
| Seagate ST3500418AS 500GB           | 1        | 1      | 0.83%   |
| Seagate ST3250318AS 250GB           | 1        | 1      | 0.83%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 36       | 37     | 31.58%  |
| Seagate             | 33       | 41     | 28.95%  |
| Samsung Electronics | 14       | 17     | 12.28%  |
| Hitachi             | 10       | 11     | 8.77%   |
| Toshiba             | 6        | 10     | 5.26%   |
| HGST                | 5        | 5      | 4.39%   |
| Crucial             | 3        | 4      | 2.63%   |
| SanDisk             | 2        | 2      | 1.75%   |
| Kingston            | 2        | 2      | 1.75%   |
| Intel               | 1        | 1      | 0.88%   |
| Fujitsu             | 1        | 1      | 0.88%   |
| A-DATA Technology   | 1        | 1      | 0.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 35       | 36     | 34.65%  |
| Seagate             | 33       | 41     | 32.67%  |
| Samsung Electronics | 12       | 15     | 11.88%  |
| Hitachi             | 10       | 11     | 9.9%    |
| Toshiba             | 5        | 9      | 4.95%   |
| HGST                | 5        | 5      | 4.95%   |
| Fujitsu             | 1        | 1      | 0.99%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 88       | 118    | 87.13%  |
| SSD  | 12       | 13     | 11.88%  |
| NVMe | 1        | 1      | 0.99%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                        | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC WD3200AAJS-00YZCA0 320GB | 1        | 1      | 50%     |
| HGST HTS725050A7E630 500GB   | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 50%     |
| HGST   | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 314      | 736    | 74.06%  |
| Malfunc  | 98       | 132    | 23.11%  |
| Detected | 10       | 16     | 2.36%   |
| Failed   | 2        | 2      | 0.47%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 259      | 50.68%  |
| AMD                          | 108      | 21.14%  |
| Samsung Electronics          | 33       | 6.46%   |
| ASMedia Technology           | 17       | 3.33%   |
| Phison Electronics           | 15       | 2.94%   |
| Sandisk                      | 9        | 1.76%   |
| Kingston Technology Company  | 8        | 1.57%   |
| Silicon Motion               | 7        | 1.37%   |
| Nvidia                       | 7        | 1.37%   |
| JMicron Technology           | 7        | 1.37%   |
| Broadcom / LSI               | 7        | 1.37%   |
| SK Hynix                     | 6        | 1.17%   |
| Marvell Technology Group     | 6        | 1.17%   |
| ADATA Technology             | 5        | 0.98%   |
| VIA Technologies             | 4        | 0.78%   |
| Micron/Crucial Technology    | 3        | 0.59%   |
| Adaptec                      | 2        | 0.39%   |
| Toshiba                      | 1        | 0.2%    |
| Silicon Image                | 1        | 0.2%    |
| Shenzhen Longsys Electronics | 1        | 0.2%    |
| Seagate Technology           | 1        | 0.2%    |
| Realtek Semiconductor        | 1        | 0.2%    |
| Lite-On IT Corp. / Plextor   | 1        | 0.2%    |
| Hewlett-Packard              | 1        | 0.2%    |
| Enmotus                      | 1        | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 65       | 10.38%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 31       | 4.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 28       | 4.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 26       | 4.15%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 25       | 3.99%   |
| AMD 400 Series Chipset SATA Controller                                                  | 24       | 3.83%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 20       | 3.19%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 19       | 3.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 17       | 2.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 17       | 2.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 17       | 2.72%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 16       | 2.56%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 14       | 2.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 14       | 2.24%   |
| Intel SATA Controller [RAID mode]                                                       | 13       | 2.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 13       | 2.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 10       | 1.6%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 10       | 1.6%    |
| Phison E12 NVMe Controller                                                              | 8        | 1.28%   |
| Kingston Company A2000 NVMe SSD                                                         | 8        | 1.28%   |
| AMD 300 Series Chipset SATA Controller                                                  | 7        | 1.12%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 6        | 0.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6        | 0.96%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 5        | 0.8%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 5        | 0.8%    |
| Nvidia MCP61 SATA Controller                                                            | 5        | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 0.8%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 5        | 0.8%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 0.64%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 4        | 0.64%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 0.64%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4        | 0.64%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 4        | 0.64%   |
| AMD X370 Series Chipset SATA Controller                                                 | 4        | 0.64%   |
| AMD FCH SATA Controller D                                                               | 4        | 0.64%   |
| Unknown                                                                                 | 4        | 0.64%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 3        | 0.48%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 3        | 0.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 0.48%   |
| Phison PS5013 E13 NVMe Controller                                                       | 3        | 0.48%   |
| Nvidia MCP61 IDE                                                                        | 3        | 0.48%   |
| Intel SSD 660P Series                                                                   | 3        | 0.48%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3        | 0.48%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 3        | 0.48%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 3        | 0.48%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 3        | 0.48%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 0.48%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 0.48%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3        | 0.48%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 3        | 0.48%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 3        | 0.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3        | 0.48%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3        | 0.48%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 3        | 0.48%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 0.48%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 0.48%   |
| SK Hynix Gold P31 SSD                                                                   | 2        | 0.32%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2        | 0.32%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 2        | 0.32%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 294      | 59.04%  |
| IDE  | 86       | 17.27%  |
| NVMe | 85       | 17.07%  |
| RAID | 22       | 4.42%   |
| SAS  | 7        | 1.41%   |
| SCSI | 4        | 0.8%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 260      | 68.97%  |
| AMD    | 117      | 31.03%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo                            | 6        | 1.59%   |
| AMD Ryzen 5 3600 6-Core Processor           | 6        | 1.59%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 6        | 1.59%   |
| Intel Xeon                                  | 5        | 1.32%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 5        | 1.32%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 5        | 1.32%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 5        | 1.32%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 4        | 1.06%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 4        | 1.06%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 1.06%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 1.06%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 1.06%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 4        | 1.06%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 4        | 1.06%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 4        | 1.06%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 3        | 0.79%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 3        | 0.79%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 0.79%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 3        | 0.79%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 3        | 0.79%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 3        | 0.79%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 3        | 0.79%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 0.79%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 3        | 0.79%   |
| Intel Core i3-6100T CPU @ 3.20GHz           | 3        | 0.79%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 3        | 0.79%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 3        | 0.79%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 0.79%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 3        | 0.79%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 0.79%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 3        | 0.79%   |
| AMD Phenom II X4 965 Processor              | 3        | 0.79%   |
| AMD FX-8350 Eight-Core Processor            | 3        | 0.79%   |
| AMD FX-8320 Eight-Core Processor            | 3        | 0.79%   |
| AMD FX-6300 Six-Core Processor              | 3        | 0.79%   |
| AMD FX-6100 Six-Core Processor              | 3        | 0.79%   |
| AMD A10-5700 APU with Radeon HD Graphics    | 3        | 0.79%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 2        | 0.53%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 2        | 0.53%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 2        | 0.53%   |
| Intel Pentium CPU G860 @ 3.00GHz            | 2        | 0.53%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 2        | 0.53%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 0.53%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 0.53%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2        | 0.53%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 0.53%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 2        | 0.53%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 0.53%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 2        | 0.53%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 2        | 0.53%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 0.53%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 0.53%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2        | 0.53%   |
| Intel Core i5-2400S CPU @ 2.50GH            | 2        | 0.53%   |
| Intel Core i3-6300 CPU @ 3.80GHz            | 2        | 0.53%   |
| Intel Core i3-5010U CPU @ 2.10GHz           | 2        | 0.53%   |
| Intel Core i3-4360 CPU @ 3.70GHz            | 2        | 0.53%   |
| Intel Core i3-3225 CPU @ 3.30GHz            | 2        | 0.53%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 0.53%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 74       | 19.58%  |
| Intel Core i7           | 42       | 11.11%  |
| Intel Core i3           | 38       | 10.05%  |
| Intel Xeon              | 34       | 8.99%   |
| AMD Ryzen 5             | 29       | 7.67%   |
| AMD FX                  | 18       | 4.76%   |
| Intel Core 2 Duo        | 16       | 4.23%   |
| AMD Ryzen 7             | 16       | 4.23%   |
| Intel Celeron           | 13       | 3.44%   |
| Intel Pentium           | 12       | 3.17%   |
| Intel Pentium Dual-Core | 10       | 2.65%   |
| AMD Ryzen 3             | 9        | 2.38%   |
| AMD Phenom II X4        | 8        | 2.12%   |
| Intel Core 2 Quad       | 7        | 1.85%   |
| AMD Ryzen 9             | 6        | 1.59%   |
| AMD Ryzen Threadripper  | 5        | 1.32%   |
| Other                   | 3        | 0.79%   |
| Intel Atom              | 3        | 0.79%   |
| AMD Athlon II X4        | 3        | 0.79%   |
| AMD A8                  | 3        | 0.79%   |
| AMD A10                 | 3        | 0.79%   |
| Intel Genuine           | 2        | 0.53%   |
| Intel Core i9           | 2        | 0.53%   |
| AMD Ryzen 5 PRO         | 2        | 0.53%   |
| AMD Phenom II X6        | 2        | 0.53%   |
| AMD E                   | 2        | 0.53%   |
| AMD Athlon II X2        | 2        | 0.53%   |
| Intel Pentium Silver    | 1        | 0.26%   |
| Intel Pentium Gold      | 1        | 0.26%   |
| Intel Pentium Dual      | 1        | 0.26%   |
| Intel Pentium 4         | 1        | 0.26%   |
| Intel Core 2            | 1        | 0.26%   |
| AMD Sempron             | 1        | 0.26%   |
| AMD E2                  | 1        | 0.26%   |
| AMD E1                  | 1        | 0.26%   |
| AMD Athlon II X3        | 1        | 0.26%   |
| AMD Athlon Dual Core    | 1        | 0.26%   |
| AMD Athlon 64 X2        | 1        | 0.26%   |
| AMD Athlon              | 1        | 0.26%   |
| AMD A6                  | 1        | 0.26%   |
| AMD A4                  | 1        | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 144      | 38.1%   |
| 2       | 96       | 25.4%   |
| 6       | 37       | 9.79%   |
| 8       | 34       | 8.99%   |
| 12      | 22       | 5.82%   |
| 16      | 15       | 3.97%   |
| Unknown | 14       | 3.7%    |
| 24      | 6        | 1.59%   |
| 64      | 2        | 0.53%   |
| 48      | 2        | 0.53%   |
| 1       | 2        | 0.53%   |
| 32      | 1        | 0.26%   |
| 14      | 1        | 0.26%   |
| 10      | 1        | 0.26%   |
| 3       | 1        | 0.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 370      | 98.14%  |
| 2      | 6        | 1.59%   |
| 8      | 1        | 0.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 243      | 64.46%  |
| 2       | 120      | 31.83%  |
| Unknown | 14       | 3.71%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 46       | 12.2%   |
| KabyLake      | 40       | 10.61%  |
| IvyBridge     | 35       | 9.28%   |
| SandyBridge   | 31       | 8.22%   |
| Penryn        | 31       | 8.22%   |
| Skylake       | 26       | 6.9%    |
| Zen 2         | 23       | 6.1%    |
| Piledriver    | 21       | 5.57%   |
| Zen+          | 19       | 5.04%   |
| Zen           | 19       | 5.04%   |
| K10           | 15       | 3.98%   |
| Westmere      | 11       | 2.92%   |
| Core          | 9        | 2.39%   |
| Nehalem       | 8        | 2.12%   |
| CometLake     | 8        | 2.12%   |
| Zen 3         | 7        | 1.86%   |
| Bulldozer     | 4        | 1.06%   |
| Broadwell     | 4        | 1.06%   |
| Goldmont plus | 3        | 0.8%    |
| Bonnell       | 3        | 0.8%    |
| Bobcat        | 3        | 0.8%    |
| Unknown       | 3        | 0.8%    |
| Silvermont    | 2        | 0.53%   |
| K8 Hammer     | 2        | 0.53%   |
| NetBurst      | 1        | 0.27%   |
| K10 Llano     | 1        | 0.27%   |
| Jaguar        | 1        | 0.27%   |
| Excavator     | 1        | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 165      | 41.15%  |
| Intel  | 130      | 32.42%  |
| AMD    | 106      | 26.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 21       | 5.21%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 20       | 4.96%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 16       | 3.97%   |
| Nvidia GK208B [GeForce GT 710]                                              | 13       | 3.23%   |
| Intel HD Graphics 530                                                       | 11       | 2.73%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 10       | 2.48%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 10       | 2.48%   |
| Nvidia GT218 [GeForce 210]                                                  | 9        | 2.23%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 9        | 2.23%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 9        | 2.23%   |
| Nvidia GF119 [GeForce GT 610]                                               | 9        | 2.23%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 7        | 1.74%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 7        | 1.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 7        | 1.74%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 7        | 1.74%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 6        | 1.49%   |
| Intel HD Graphics 630                                                       | 6        | 1.49%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 5        | 1.24%   |
| Nvidia GK208B [GeForce GT 730]                                              | 5        | 1.24%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 1.24%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5        | 1.24%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 4        | 0.99%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 0.99%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 0.99%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 4        | 0.99%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 0.99%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 4        | 0.99%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 3        | 0.74%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 3        | 0.74%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 3        | 0.74%   |
| Nvidia GK107 [GeForce GT 740]                                               | 3        | 0.74%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 3        | 0.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3        | 0.74%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 0.74%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 3        | 0.74%   |
| AMD RS780L [Radeon 3000]                                                    | 3        | 0.74%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 3        | 0.74%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 0.74%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 3        | 0.74%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 0.74%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.5%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 0.5%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 0.5%    |
| Nvidia GK208B [GeForce GT 720]                                              | 2        | 0.5%    |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 0.5%    |
| Nvidia GK104 [GeForce GTX 770]                                              | 2        | 0.5%    |
| Nvidia GK104 [GeForce GTX 760]                                              | 2        | 0.5%    |
| Nvidia GF108 [GeForce GT 630]                                               | 2        | 0.5%    |
| Nvidia GF108 [GeForce GT 430]                                               | 2        | 0.5%    |
| Nvidia GF106 [GeForce GTS 450]                                              | 2        | 0.5%    |
| Nvidia GA104 [GeForce RTX 3070]                                             | 2        | 0.5%    |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 0.5%    |
| Nvidia G92 [GeForce GTS 250]                                                | 2        | 0.5%    |
| Nvidia G92 [GeForce 9800 GT]                                                | 2        | 0.5%    |
| Nvidia G72 [GeForce 7300 LE]                                                | 2        | 0.5%    |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 2        | 0.5%    |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 2        | 0.5%    |
| Intel HD Graphics 5500                                                      | 2        | 0.5%    |
| Intel GeminiLake [UHD Graphics 600]                                         | 2        | 0.5%    |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 152      | 39.58%  |
| 1 x Intel      | 103      | 26.82%  |
| 1 x AMD        | 98       | 25.52%  |
| Intel + Nvidia | 11       | 2.86%   |
| 2 x Intel      | 9        | 2.34%   |
| Intel + AMD    | 7        | 1.82%   |
| AMD + Nvidia   | 2        | 0.52%   |
| 2 x Nvidia     | 1        | 0.26%   |
| 2 x AMD        | 1        | 0.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 248      | 65.26%  |
| Proprietary | 114      | 30%     |
| Unknown     | 18       | 4.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 191      | 49.74%  |
| 1.01-2.0   | 61       | 15.89%  |
| 3.01-4.0   | 37       | 9.64%   |
| 0.51-1.0   | 35       | 9.11%   |
| 7.01-8.0   | 22       | 5.73%   |
| 0.01-0.5   | 20       | 5.21%   |
| 5.01-6.0   | 15       | 3.91%   |
| 2.01-3.0   | 3        | 0.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 44       | 14.81%  |
| Goldstar             | 43       | 14.48%  |
| Dell                 | 36       | 12.12%  |
| Hewlett-Packard      | 26       | 8.75%   |
| Acer                 | 20       | 6.73%   |
| BenQ                 | 18       | 6.06%   |
| AOC                  | 17       | 5.72%   |
| Ancor Communications | 13       | 4.38%   |
| Philips              | 10       | 3.37%   |
| ViewSonic            | 7        | 2.36%   |
| Lenovo               | 7        | 2.36%   |
| Iiyama               | 7        | 2.36%   |
| ASUSTek Computer     | 6        | 2.02%   |
| Sony                 | 5        | 1.68%   |
| Toshiba              | 3        | 1.01%   |
| Packard Bell         | 3        | 1.01%   |
| Fujitsu Siemens      | 3        | 1.01%   |
| Eizo                 | 3        | 1.01%   |
| Vizio                | 2        | 0.67%   |
| Vestel Elektronik    | 2        | 0.67%   |
| Insignia             | 2        | 0.67%   |
| Westinghouse         | 1        | 0.34%   |
| VIE                  | 1        | 0.34%   |
| Videoseven           | 1        | 0.34%   |
| Sun                  | 1        | 0.34%   |
| SGT                  | 1        | 0.34%   |
| RS                   | 1        | 0.34%   |
| PRI                  | 1        | 0.34%   |
| NEC Computers        | 1        | 0.34%   |
| Medion               | 1        | 0.34%   |
| LED                  | 1        | 0.34%   |
| KJT                  | 1        | 0.34%   |
| HannStar             | 1        | 0.34%   |
| Haier                | 1        | 0.34%   |
| Gateway              | 1        | 0.34%   |
| FND                  | 1        | 0.34%   |
| Denver               | 1        | 0.34%   |
| CVT                  | 1        | 0.34%   |
| CAN                  | 1        | 0.34%   |
| AVX                  | 1        | 0.34%   |
| ALP                  | 1        | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| ViewSonic VX1940w VSC6A20 1680x1050 410x260mm 19.1-inch                | 2        | 0.66%   |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 530x300mm 24.0-inch     | 2        | 0.66%   |
| Sony TV SNY9C01 1360x768                                               | 2        | 0.66%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                       | 2        | 0.66%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 1110x620mm 50.1-inch | 2        | 0.66%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                 | 2        | 0.66%   |
| Philips LCD Monitor PHLC0B1 1920x1080 480x270mm 21.7-inch              | 2        | 0.66%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch                | 2        | 0.66%   |
| Hewlett-Packard 27f HPN354A 1920x1080 600x340mm 27.2-inch              | 2        | 0.66%   |
| Hewlett-Packard 27er HWP3325 1920x1080 600x340mm 27.2-inch             | 2        | 0.66%   |
| Goldstar W1942 GSM4B6F 1440x900 410x260mm 19.1-inch                    | 2        | 0.66%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch             | 2        | 0.66%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2        | 0.66%   |
| Goldstar E2441 GSM581F 1920x1080 530x300mm 24.0-inch                   | 2        | 0.66%   |
| Dell U3415W DELA0A6 3440x1440 800x330mm 34.1-inch                      | 2        | 0.66%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                      | 2        | 0.66%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                      | 2        | 0.66%   |
| Dell S2418HN/NX DEL4123 1920x1080 530x300mm 24.0-inch                  | 2        | 0.66%   |
| BenQ GW2260 BNQ78C4 1920x1080 480x270mm 21.7-inch                      | 2        | 0.66%   |
| BenQ GL2460 BNQ78CE 1920x1080 530x300mm 24.0-inch                      | 2        | 0.66%   |
| BenQ GL2450 BNQ78A4 1920x1080 530x300mm 24.0-inch                      | 2        | 0.66%   |
| ASUSTek Computer VP228 AUS22A1 1920x1080 480x270mm 21.7-inch           | 2        | 0.66%   |
| AOC 24G2W1G4 AOC2402 1920x1080 530x300mm 24.0-inch                     | 2        | 0.66%   |
| AOC 22V2WG5 AOC2202 1920x1080 480x270mm 21.7-inch                      | 2        | 0.66%   |
| Ancor Communications MX27AQ ACI27A5 2560x1440 600x340mm 27.2-inch      | 2        | 0.66%   |
| Westinghouse LCM-19w4 WDE1904 1440x900 410x260mm 19.1-inch             | 1        | 0.33%   |
| Vizio LCD Monitor VIZ0022 1920x540 480x270mm 21.7-inch                 | 1        | 0.33%   |
| Vizio D32f-F1 VIZ1027 1920x1080 700x390mm 31.5-inch                    | 1        | 0.33%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 520x290mm 23.4-inch             | 1        | 0.33%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch               | 1        | 0.33%   |
| ViewSonic LCD Monitor VSCD824 1920x1080 520x290mm 23.4-inch            | 1        | 0.33%   |
| ViewSonic LCD Monitor VSCBD2B 1920x1080 480x270mm 21.7-inch            | 1        | 0.33%   |
| ViewSonic LCD Monitor VSC8724 1440x900 410x260mm 19.1-inch             | 1        | 0.33%   |
| VIE A/G2356 VIE2300 1920x1080 500x300mm 23.0-inch                      | 1        | 0.33%   |
| Videoseven WL19A IGM1908 1280x1024 380x300mm 19.1-inch                 | 1        | 0.33%   |
| Toshiba TV TSB0218 3840x2160                                           | 1        | 0.33%   |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                      | 1        | 0.33%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                        | 1        | 0.33%   |
| Sun X7202A SUN0595 1280x1024 380x300mm 19.1-inch                       | 1        | 0.33%   |
| Sony TV SNYEE01 1920x1080                                              | 1        | 0.33%   |
| Sony TV SNYC901 1920x1080                                              | 1        | 0.33%   |
| Sony SDM-S75D/F/N SNY3800 1280x1024 340x270mm 17.1-inch                | 1        | 0.33%   |
| SGT YSD SGT1700 1280x1024 380x210mm 17.1-inch                          | 1        | 0.33%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 700x390mm 31.5-inch      | 1        | 0.33%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch      | 1        | 0.33%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 610x350mm 27.7-inch      | 1        | 0.33%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 520x290mm 23.4-inch      | 1        | 0.33%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch      | 1        | 0.33%   |
| Samsung Electronics T22D390 SAM0B69 1920x1080 480x270mm 21.7-inch      | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                        | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM0600 1600x900 440x250mm 19.9-inch    | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch    | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                       | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x260mm 19.1-inch    | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM03D7 1680x1050 470x300mm 22.0-inch   | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM0373 1680x1050 440x300mm 21.0-inch   | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM036C 1920x1200 550x340mm 25.5-inch   | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 340x190mm 15.3-inch    | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM0320 1680x1050 470x300mm 22.0-inch   | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch   | 1        | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 134      | 45.73%  |
| 1280x1024 (SXGA)   | 25       | 8.53%   |
| 3840x2160 (4K)     | 19       | 6.48%   |
| 2560x1440 (QHD)    | 19       | 6.48%   |
| 1680x1050 (WSXGA+) | 19       | 6.48%   |
| 1440x900 (WXGA+)   | 15       | 5.12%   |
| 1366x768 (WXGA)    | 15       | 5.12%   |
| 1920x1200 (WUXGA)  | 11       | 3.75%   |
| 1600x900 (HD+)     | 10       | 3.41%   |
| 2560x1080          | 7        | 2.39%   |
| 3440x1440          | 5        | 1.71%   |
| 1920x540           | 4        | 1.37%   |
| 1360x768           | 4        | 1.37%   |
| 1024x768 (XGA)     | 3        | 1.02%   |
| 2048x1152          | 2        | 0.68%   |
| 1600x1200          | 1        | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 49       | 16.44%  |
| 21      | 45       | 15.1%   |
| 23      | 38       | 12.75%  |
| 19      | 38       | 12.75%  |
| 27      | 35       | 11.74%  |
| 18      | 18       | 6.04%   |
| 31      | 12       | 4.03%   |
| 17      | 11       | 3.69%   |
| Unknown | 9        | 3.02%   |
| 34      | 7        | 2.35%   |
| 22      | 7        | 2.35%   |
| 20      | 6        | 2.01%   |
| 50      | 3        | 1.01%   |
| 42      | 3        | 1.01%   |
| 28      | 2        | 0.67%   |
| 16      | 2        | 0.67%   |
| 14      | 2        | 0.67%   |
| 64      | 1        | 0.34%   |
| 54      | 1        | 0.34%   |
| 52      | 1        | 0.34%   |
| 40      | 1        | 0.34%   |
| 39      | 1        | 0.34%   |
| 33      | 1        | 0.34%   |
| 30      | 1        | 0.34%   |
| 29      | 1        | 0.34%   |
| 25      | 1        | 0.34%   |
| 15      | 1        | 0.34%   |
| 13      | 1        | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 113      | 38.83%  |
| 401-500     | 98       | 33.68%  |
| 601-700     | 19       | 6.53%   |
| 351-400     | 18       | 6.19%   |
| 301-350     | 12       | 4.12%   |
| Unknown     | 9        | 3.09%   |
| 701-800     | 8        | 2.75%   |
| 1001-1500   | 6        | 2.06%   |
| 201-300     | 3        | 1.03%   |
| 901-1000    | 3        | 1.03%   |
| 801-900     | 2        | 0.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 202      | 70.38%  |
| 16/10 | 43       | 14.98%  |
| 5/4   | 23       | 8.01%   |
| 21/9  | 12       | 4.18%   |
| 4/3   | 5        | 1.74%   |
| 3/2   | 2        | 0.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 118      | 40.41%  |
| 151-200        | 48       | 16.44%  |
| 301-350        | 36       | 12.33%  |
| 141-150        | 24       | 8.22%   |
| 351-500        | 20       | 6.85%   |
| 251-300        | 19       | 6.51%   |
| Unknown        | 9        | 3.08%   |
| More than 1000 | 6        | 2.05%   |
| 501-1000       | 5        | 1.71%   |
| 121-130        | 2        | 0.68%   |
| 101-110        | 2        | 0.68%   |
| 91-100         | 2        | 0.68%   |
| 111-120        | 1        | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 193      | 66.32%  |
| 101-120 | 73       | 25.09%  |
| Unknown | 9        | 3.09%   |
| 161-240 | 7        | 2.41%   |
| 121-160 | 6        | 2.06%   |
| 1-50    | 3        | 1.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 269      | 70.42%  |
| 0     | 90       | 23.56%  |
| 2     | 22       | 5.76%   |
| 3     | 1        | 0.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 223      | 46.85%  |
| Intel                           | 157      | 32.98%  |
| Qualcomm Atheros                | 29       | 6.09%   |
| Broadcom                        | 22       | 4.62%   |
| Ralink                          | 9        | 1.89%   |
| Ralink Technology               | 8        | 1.68%   |
| Marvell Technology Group        | 4        | 0.84%   |
| D-Link System                   | 3        | 0.63%   |
| TP-Link                         | 2        | 0.42%   |
| MediaTek                        | 2        | 0.42%   |
| IMC Networks                    | 2        | 0.42%   |
| VIA Technologies                | 1        | 0.21%   |
| Samsung Electronics             | 1        | 0.21%   |
| Qualcomm Atheros Communications | 1        | 0.21%   |
| Nvidia                          | 1        | 0.21%   |
| NetGear                         | 1        | 0.21%   |
| Microchip Technology            | 1        | 0.21%   |
| Mellanox Technologies           | 1        | 0.21%   |
| Google                          | 1        | 0.21%   |
| Edimax Technology               | 1        | 0.21%   |
| D-Link                          | 1        | 0.21%   |
| Bluegiga Technologies           | 1        | 0.21%   |
| Belkin Components               | 1        | 0.21%   |
| ASUSTek Computer                | 1        | 0.21%   |
| Aquantia                        | 1        | 0.21%   |
| 3Com                            | 1        | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 190      | 35.78%  |
| Intel I211 Gigabit Network Connection                                         | 26       | 4.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 20       | 3.77%   |
| Intel Ethernet Connection I217-LM                                             | 17       | 3.2%    |
| Intel Wi-Fi 6 AX200                                                           | 14       | 2.64%   |
| Intel Ethernet Connection (7) I219-V                                          | 12       | 2.26%   |
| Intel Ethernet Connection (2) I219-V                                          | 10       | 1.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 9        | 1.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 8        | 1.51%   |
| Intel Ethernet Connection (2) I219-LM                                         | 8        | 1.51%   |
| Intel 82579V Gigabit Network Connection                                       | 8        | 1.51%   |
| Intel Ethernet Connection I217-V                                              | 6        | 1.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 6        | 1.13%   |
| Intel 82574L Gigabit Network Connection                                       | 6        | 1.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 5        | 0.94%   |
| Intel Wireless 7260                                                           | 5        | 0.94%   |
| Realtek RTL8125 2.5GbE Controller                                             | 4        | 0.75%   |
| Ralink RT5370 Wireless Adapter                                                | 4        | 0.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 4        | 0.75%   |
| Intel Wireless 7265                                                           | 4        | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 3        | 0.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 3        | 0.56%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 3        | 0.56%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 3        | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3        | 0.56%   |
| Ralink MT7601U Wireless Adapter                                               | 3        | 0.56%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 3        | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 3        | 0.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 3        | 0.56%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 3        | 0.56%   |
| Intel Wireless-AC 9260                                                        | 3        | 0.56%   |
| Intel Ethernet Connection (2) I218-V                                          | 3        | 0.56%   |
| Intel 82583V Gigabit Network Connection                                       | 3        | 0.56%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 0.56%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 3        | 0.56%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 3        | 0.56%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 3        | 0.56%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 3        | 0.56%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 2        | 0.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 2        | 0.38%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2        | 0.38%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2        | 0.38%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 2        | 0.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2        | 0.38%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2        | 0.38%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 2        | 0.38%   |
| Intel Wireless 3165                                                           | 2        | 0.38%   |
| Intel I210 Gigabit Network Connection                                         | 2        | 0.38%   |
| Intel Ethernet Connection (12) I219-V                                         | 2        | 0.38%   |
| Intel Ethernet Connection (11) I219-V                                         | 2        | 0.38%   |
| Intel Centrino Wireless-N 2230                                                | 2        | 0.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2        | 0.38%   |
| Intel 82578DM Gigabit Network Connection                                      | 2        | 0.38%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 0.38%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 2        | 0.38%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter   | 2        | 0.38%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 2        | 0.38%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2        | 0.38%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 2        | 0.38%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 2        | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 44       | 33.85%  |
| Realtek Semiconductor           | 34       | 26.15%  |
| Qualcomm Atheros                | 13       | 10%     |
| Broadcom                        | 10       | 7.69%   |
| Ralink                          | 9        | 6.92%   |
| Ralink Technology               | 8        | 6.15%   |
| TP-Link                         | 2        | 1.54%   |
| IMC Networks                    | 2        | 1.54%   |
| Qualcomm Atheros Communications | 1        | 0.77%   |
| NetGear                         | 1        | 0.77%   |
| MediaTek                        | 1        | 0.77%   |
| Edimax Technology               | 1        | 0.77%   |
| D-Link System                   | 1        | 0.77%   |
| D-Link                          | 1        | 0.77%   |
| Belkin Components               | 1        | 0.77%   |
| ASUSTek Computer                | 1        | 0.77%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                   | 14       | 10.61%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 8        | 6.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 6        | 4.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 5        | 3.79%   |
| Intel Wireless 7260                                                                   | 5        | 3.79%   |
| Ralink RT5370 Wireless Adapter                                                        | 4        | 3.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4        | 3.03%   |
| Intel Wireless 7265                                                                   | 4        | 3.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 3        | 2.27%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 3        | 2.27%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 3        | 2.27%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 3        | 2.27%   |
| Ralink MT7601U Wireless Adapter                                                       | 3        | 2.27%   |
| Intel Wireless-AC 9260                                                                | 3        | 2.27%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 3        | 2.27%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 3        | 2.27%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                   | 2        | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 2        | 1.52%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 2        | 1.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 2        | 1.52%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 2        | 1.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2        | 1.52%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 2        | 1.52%   |
| Intel Wireless 3165                                                                   | 2        | 1.52%   |
| Intel Centrino Wireless-N 2230                                                        | 2        | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2        | 1.52%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter           | 2        | 1.52%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                    | 2        | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 0.76%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1        | 0.76%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1        | 0.76%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                | 1        | 0.76%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 0.76%   |
| Ralink RT3072 Wireless Adapter                                                        | 1        | 0.76%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                           | 1        | 0.76%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                                  | 1        | 0.76%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                             | 1        | 0.76%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                  | 1        | 0.76%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1        | 0.76%   |
| Ralink RT2561/RT61 rev B 802.11g                                                      | 1        | 0.76%   |
| Ralink RT2500 Wireless 802.11bg                                                       | 1        | 0.76%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1        | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1        | 0.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1        | 0.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1        | 0.76%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 0.76%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]                | 1        | 0.76%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]                      | 1        | 0.76%   |
| MediaTek 802.11ac Wireless LAN Card                                                   | 1        | 0.76%   |
| Intel Wireless 8265 / 8275                                                            | 1        | 0.76%   |
| Intel Wireless 3160                                                                   | 1        | 0.76%   |
| Intel Centrino Wireless-N 105                                                         | 1        | 0.76%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                         | 1        | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 1        | 0.76%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                      | 1        | 0.76%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]                     | 1        | 0.76%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]            | 1        | 0.76%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.B1) [Ralink RT5370]                         | 1        | 0.76%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 1        | 0.76%   |
| Broadcom 802.11ac Network Adapter                                                     | 1        | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 206      | 53.51%  |
| Intel                    | 139      | 36.1%   |
| Qualcomm Atheros         | 16       | 4.16%   |
| Broadcom                 | 12       | 3.12%   |
| Marvell Technology Group | 4        | 1.04%   |
| D-Link System            | 2        | 0.52%   |
| VIA Technologies         | 1        | 0.26%   |
| Samsung Electronics      | 1        | 0.26%   |
| Nvidia                   | 1        | 0.26%   |
| MediaTek                 | 1        | 0.26%   |
| Google                   | 1        | 0.26%   |
| Aquantia                 | 1        | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 190      | 48.35%  |
| Intel I211 Gigabit Network Connection                                          | 26       | 6.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 20       | 5.09%   |
| Intel Ethernet Connection I217-LM                                              | 17       | 4.33%   |
| Intel Ethernet Connection (7) I219-V                                           | 12       | 3.05%   |
| Intel Ethernet Connection (2) I219-V                                           | 10       | 2.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 9        | 2.29%   |
| Intel Ethernet Connection (2) I219-LM                                          | 8        | 2.04%   |
| Intel 82579V Gigabit Network Connection                                        | 8        | 2.04%   |
| Intel Ethernet Connection I217-V                                               | 6        | 1.53%   |
| Intel 82574L Gigabit Network Connection                                        | 6        | 1.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3        | 0.76%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 3        | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3        | 0.76%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 3        | 0.76%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 3        | 0.76%   |
| Intel Ethernet Connection (2) I218-V                                           | 3        | 0.76%   |
| Intel 82583V Gigabit Network Connection                                        | 3        | 0.76%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 3        | 0.76%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 3        | 0.76%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 3        | 0.76%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2        | 0.51%   |
| Intel I210 Gigabit Network Connection                                          | 2        | 0.51%   |
| Intel Ethernet Connection (12) I219-V                                          | 2        | 0.51%   |
| Intel Ethernet Connection (11) I219-V                                          | 2        | 0.51%   |
| Intel 82578DM Gigabit Network Connection                                       | 2        | 0.51%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 2        | 0.51%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                           | 2        | 0.51%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                | 2        | 0.51%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2        | 0.51%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                        | 2        | 0.51%   |
| VIA VT6105/VT6106S [Rhine-III]                                                 | 1        | 0.25%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1        | 0.25%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 0.25%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1        | 0.25%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1        | 0.25%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1        | 0.25%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1        | 0.25%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1        | 0.25%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1        | 0.25%   |
| Nvidia MCP73 Ethernet                                                          | 1        | 0.25%   |
| MediaTek USB Ethernet-RNDIS                                                    | 1        | 0.25%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 0.25%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 1        | 0.25%   |
| Intel Ethernet Controller I225-V                                               | 1        | 0.25%   |
| Intel Ethernet Connection I219-LM                                              | 1        | 0.25%   |
| Intel Ethernet Connection I218-V                                               | 1        | 0.25%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1        | 0.25%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1        | 0.25%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1        | 0.25%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                             | 1        | 0.25%   |
| Intel 82562V-2 10/100 Network Connection                                       | 1        | 0.25%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                         | 1        | 0.25%   |
| Google Nexus/Pixel Device (charging + debug)                                   | 1        | 0.25%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                 | 1        | 0.25%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                               | 1        | 0.25%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                        | 1        | 0.25%   |
| Broadcom NetXtreme BCM5705_2 Gigabit Ethernet                                  | 1        | 0.25%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1        | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 372      | 74.85%  |
| WiFi     | 119      | 23.94%  |
| Unknown  | 4        | 0.8%    |
| Modem    | 2        | 0.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 367      | 82.29%  |
| WiFi     | 77       | 17.26%  |
| Unknown  | 2        | 0.45%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 261      | 69.05%  |
| 2     | 94       | 24.87%  |
| 3     | 17       | 4.5%    |
| 4     | 3        | 0.79%   |
| 0     | 3        | 0.79%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 371      | 97.12%  |
| Yes  | 11       | 2.88%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 39       | 36.45%  |
| Cambridge Silicon Radio         | 25       | 23.36%  |
| Realtek Semiconductor           | 11       | 10.28%  |
| ASUSTek Computer                | 8        | 7.48%   |
| Broadcom                        | 7        | 6.54%   |
| Apple                           | 6        | 5.61%   |
| Integrated System Solution      | 3        | 2.8%    |
| IMC Networks                    | 3        | 2.8%    |
| Qualcomm Atheros Communications | 2        | 1.87%   |
| HTC (High Tech Computer)        | 1        | 0.93%   |
| Foxconn / Hon Hai               | 1        | 0.93%   |
| Edimax Technology               | 1        | 0.93%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 25       | 23.36%  |
| Intel AX200 Bluetooth                                                | 13       | 12.15%  |
| Intel Bluetooth wireless interface                                   | 11       | 10.28%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 6        | 5.61%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 5        | 4.67%   |
| Realtek  Bluetooth Adapter                                           | 3        | 2.8%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 3        | 2.8%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 3        | 2.8%    |
| ASUS ASUS USB-BT500                                                  | 3        | 2.8%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 3        | 2.8%    |
| Apple Apple Broadcom Built-in Bluetooth                              | 3        | 2.8%    |
| Intel Centrino Bluetooth Wireless Transceiver                        | 2        | 1.87%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 2        | 1.87%   |
| Intel AX201 Bluetooth                                                | 2        | 1.87%   |
| Integrated System Solution Bluetooth Device                          | 2        | 1.87%   |
| ASUS Realtek Bluetooth 4.0 + High Speed Chip                         | 2        | 1.87%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2        | 1.87%   |
| Realtek  Bluetooth 4.0 Adapter                                       | 1        | 0.93%   |
| Realtek Dell Wireless 1801 Bluetooth 4.0 LE                          | 1        | 0.93%   |
| Realtek Bluetooth Radio                                              | 1        | 0.93%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device          | 1        | 0.93%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 1        | 0.93%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1        | 0.93%   |
| IMC Networks Realtek Bluetooth Adapter                               | 1        | 0.93%   |
| IMC Networks Realtek Bluetooth 4.0 Adapter                           | 1        | 0.93%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0 + HS              | 1        | 0.93%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.93%   |
| Foxconn / Hon Hai Broadcom Bluetooth 4.0 USB                         | 1        | 0.93%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter              | 1        | 0.93%   |
| Broadcom Broadcom 4371 Bluetooth 4.1 Adapter                         | 1        | 0.93%   |
| Broadcom Bluetooth Device                                            | 1        | 0.93%   |
| Broadcom Bluetooth 2.0+eDR dongle                                    | 1        | 0.93%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 1        | 0.93%   |
| ASUS Bluetooth Controller                                            | 1        | 0.93%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 250      | 40.58%  |
| Nvidia                      | 151      | 24.51%  |
| AMD                         | 145      | 23.54%  |
| C-Media Electronics         | 20       | 3.25%   |
| Texas Instruments           | 7        | 1.14%   |
| Creative Labs               | 6        | 0.97%   |
| Logitech                    | 4        | 0.65%   |
| GN Netcom                   | 3        | 0.49%   |
| Yamaha                      | 2        | 0.32%   |
| SteelSeries ApS             | 2        | 0.32%   |
| Kingston Technology         | 2        | 0.32%   |
| JMTek                       | 2        | 0.32%   |
| Creative Technology         | 2        | 0.32%   |
| ZOOM                        | 1        | 0.16%   |
| XMOS                        | 1        | 0.16%   |
| VIA Technologies            | 1        | 0.16%   |
| Steinberg Soft-und Hardware | 1        | 0.16%   |
| Realtek Semiconductor       | 1        | 0.16%   |
| Plantronics                 | 1        | 0.16%   |
| Nektar                      | 1        | 0.16%   |
| KORG                        | 1        | 0.16%   |
| Hewlett-Packard             | 1        | 0.16%   |
| Griffin Technology          | 1        | 0.16%   |
| Giga-Byte Technology        | 1        | 0.16%   |
| Focusrite-Novation          | 1        | 0.16%   |
| FiiO Electronics Technology | 1        | 0.16%   |
| Ensoniq                     | 1        | 0.16%   |
| Elgato Systems              | 1        | 0.16%   |
| Corsair                     | 1        | 0.16%   |
| Cambridge Silicon Radio     | 1        | 0.16%   |
| Bose                        | 1        | 0.16%   |
| BEHRINGER International     | 1        | 0.16%   |
| ASUSTek Computer            | 1        | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 37       | 5.19%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 31       | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 30       | 4.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 29       | 4.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 27       | 3.79%   |
| AMD Starship/Matisse HD Audio Controller                                          | 25       | 3.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 23       | 3.23%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 22       | 3.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 22       | 3.09%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 21       | 2.95%   |
| AMD Family 17h/19h HD Audio Controller                                            | 20       | 2.81%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 20       | 2.81%   |
| Intel Cannon Lake PCH cAVS                                                        | 17       | 2.38%   |
| Intel 200 Series PCH HD Audio                                                     | 17       | 2.38%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 14       | 1.96%   |
| Nvidia TU116 High Definition Audio Controller                                     | 12       | 1.68%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 12       | 1.68%   |
| Nvidia GF119 HDMI Audio Controller                                                | 11       | 1.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 11       | 1.54%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 10       | 1.4%    |
| AMD FCH Azalia Controller                                                         | 10       | 1.4%    |
| Nvidia High Definition Audio Controller                                           | 9        | 1.26%   |
| Nvidia GP108 High Definition Audio Controller                                     | 9        | 1.26%   |
| Nvidia GK107 HDMI Audio Controller                                                | 8        | 1.12%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 8        | 1.12%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 8        | 1.12%   |
| AMD Navi 10 HDMI Audio                                                            | 8        | 1.12%   |
| Nvidia GP106 High Definition Audio Controller                                     | 7        | 0.98%   |
| Nvidia GM206 High Definition Audio Controller                                     | 7        | 0.98%   |
| Nvidia GF108 High Definition Audio Controller                                     | 7        | 0.98%   |
| Nvidia GP104 High Definition Audio Controller                                     | 6        | 0.84%   |
| Nvidia GM204 High Definition Audio Controller                                     | 6        | 0.84%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 6        | 0.84%   |
| Nvidia MCP61 High Definition Audio                                                | 5        | 0.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 5        | 0.7%    |
| Nvidia GK104 HDMI Audio Controller                                                | 5        | 0.7%    |
| Intel Comet Lake PCH-V cAVS                                                       | 5        | 0.7%    |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 5        | 0.7%    |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 5        | 0.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 5        | 0.7%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 5        | 0.7%    |
| Texas Instruments PCM2902 Audio Codec                                             | 4        | 0.56%   |
| Nvidia GK106 HDMI Audio Controller                                                | 4        | 0.56%   |
| Nvidia GA104 High Definition Audio Controller                                     | 4        | 0.56%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 4        | 0.56%   |
| C-Media Electronics Audio Adapter                                                 | 4        | 0.56%   |
| AMD Trinity HDMI Audio Controller                                                 | 4        | 0.56%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 4        | 0.56%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 4        | 0.56%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4        | 0.56%   |
| Nvidia GF106 High Definition Audio Controller                                     | 3        | 0.42%   |
| Intel Haswell-ULT HD Audio Controller                                             | 3        | 0.42%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 3        | 0.42%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 3        | 0.42%   |
| Intel 8 Series HD Audio Controller                                                | 3        | 0.42%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 3        | 0.42%   |
| C-Media Electronics CM108 Audio Controller                                        | 3        | 0.42%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 3        | 0.42%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                    | 3        | 0.42%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 2        | 0.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Kingston                   | 87       | 19.82%  |
| Unknown                    | 65       | 14.81%  |
| Crucial                    | 46       | 10.48%  |
| Samsung Electronics        | 43       | 9.79%   |
| SK Hynix                   | 34       | 7.74%   |
| Corsair                    | 34       | 7.74%   |
| Micron Technology          | 29       | 6.61%   |
| G.Skill                    | 28       | 6.38%   |
| Nanya Technology           | 10       | 2.28%   |
| Team                       | 9        | 2.05%   |
| Patriot                    | 6        | 1.37%   |
| A-DATA Technology          | 6        | 1.37%   |
| Unknown                    | 6        | 1.37%   |
| Transcend                  | 5        | 1.14%   |
| Avant                      | 4        | 0.91%   |
| AMD                        | 4        | 0.91%   |
| Ramaxel Technology         | 3        | 0.68%   |
| Elpida                     | 3        | 0.68%   |
| PNY                        | 2        | 0.46%   |
| Goldkey                    | 2        | 0.46%   |
| Unknown (ABCD)             | 1        | 0.23%   |
| Unknown (7F7F7F94FFFFFFFF) | 1        | 0.23%   |
| Unknown (09A4)             | 1        | 0.23%   |
| Unifosa                    | 1        | 0.23%   |
| TakeMS                     | 1        | 0.23%   |
| Super Talent               | 1        | 0.23%   |
| Silicon Power              | 1        | 0.23%   |
| Ramos Technology           | 1        | 0.23%   |
| KomputerBay                | 1        | 0.23%   |
| Hikvision                  | 1        | 0.23%   |
| GOODRAM                    | 1        | 0.23%   |
| Atermiter                  | 1        | 0.23%   |
| Apacer                     | 1        | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 6        | 1.24%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s     | 6        | 1.24%   |
| Unknown                                                  | 6        | 1.24%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 4        | 0.82%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 4        | 0.82%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s      | 4        | 0.82%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s      | 4        | 0.82%   |
| Unknown RAM Module 1GB DIMM SDRAM                        | 3        | 0.62%   |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s             | 3        | 0.62%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s        | 3        | 0.62%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1333MT/s    | 3        | 0.62%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s     | 3        | 0.62%   |
| Crucial RAM CT8G4DFD8213.C16FAR1 8GB DIMM DDR4 2133MT/s  | 3        | 0.62%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s      | 3        | 0.62%   |
| Corsair RAM CMX8GX3M2A1333C9 4GB DIMM 1333MT/s           | 3        | 0.62%   |
| Corsair RAM CMK16GX4M2A2400C16 8GB DIMM DDR4 2400MT/s    | 3        | 0.62%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 2        | 0.41%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                 | 2        | 0.41%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 2        | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 2        | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR2                         | 2        | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                 | 2        | 0.41%   |
| Unknown RAM Module 2GB DIMM 400MT/s                      | 2        | 0.41%   |
| SK Hynix RAM HMT451U7BFR8A-PB 4GB DIMM DDR3 1600MT/s     | 2        | 0.41%   |
| SK Hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s     | 2        | 0.41%   |
| SK Hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s     | 2        | 0.41%   |
| SK Hynix RAM HMT451S6BCFR8A-PB 4GB DIMM DDR3 1600MT/s    | 2        | 0.41%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s     | 2        | 0.41%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s     | 2        | 0.41%   |
| SK Hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s     | 2        | 0.41%   |
| SK Hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s     | 2        | 0.41%   |
| SK Hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s     | 2        | 0.41%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s      | 2        | 0.41%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1333MT/s      | 2        | 0.41%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 1333MT/s      | 2        | 0.41%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s      | 2        | 0.41%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 2        | 0.41%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 2666MT/s      | 2        | 0.41%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s      | 2        | 0.41%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s    | 2        | 0.41%   |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s       | 2        | 0.41%   |
| Micron RAM 8JTF25664AZ-1G6M1 2GB DIMM DDR3 1600MT/s      | 2        | 0.41%   |
| Micron RAM 18KSF51272AZ-1G4M1 4GB DIMM DDR3 1333MT/s     | 2        | 0.41%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s    | 2        | 0.41%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s      | 2        | 0.41%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s      | 2        | 0.41%   |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 2667MT/s     | 2        | 0.41%   |
| Kingston RAM 99U5584-010.A00LF 4096MB DIMM DDR3 1866MT/s | 2        | 0.41%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s    | 2        | 0.41%   |
| Kingston RAM 99U5471-025.A00LF 4GB DIMM DDR3 1333MT/s    | 2        | 0.41%   |
| Kingston RAM 99U5471-002.A01LF 2GB DIMM DDR3 1333MT/s    | 2        | 0.41%   |
| Kingston RAM 99U5471-002.A00LF 2GB DIMM DDR3 1333MT/s    | 2        | 0.41%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s   | 2        | 0.41%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 2400MT/s       | 2        | 0.41%   |
| G.Skill RAM F4-2666C19-8GNT 8GB DIMM DDR4 2666MT/s       | 2        | 0.41%   |
| G.Skill RAM F4-2400C15-8GFT 8GB DIMM DDR4 2400MT/s       | 2        | 0.41%   |
| G.Skill RAM F3-1600C9-4GAO 4GB DIMM DDR3 1600MT/s        | 2        | 0.41%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s    | 2        | 0.41%   |
| Crucial RAM CT16G4DFRA266.C8FE 16GB DIMM DDR4 2667MT/s   | 2        | 0.41%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s    | 2        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 160      | 43.01%  |
| DDR4    | 146      | 39.25%  |
| Unknown | 27       | 7.26%   |
| DDR2    | 25       | 6.72%   |
| SDRAM   | 10       | 2.69%   |
| DDR     | 3        | 0.81%   |
| LPDDR4  | 1        | 0.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 333      | 90%     |
| SODIMM  | 33       | 8.92%   |
| FB-DIMM | 3        | 0.81%   |
| Unknown | 1        | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 137      | 32.54%  |
| 8192  | 135      | 32.07%  |
| 2048  | 83       | 19.71%  |
| 16384 | 47       | 11.16%  |
| 1024  | 14       | 3.33%   |
| 32768 | 5        | 1.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 92       | 22.77%  |
| 1333    | 78       | 19.31%  |
| 2400    | 41       | 10.15%  |
| 2133    | 33       | 8.17%   |
| 2667    | 32       | 7.92%   |
| 3200    | 29       | 7.18%   |
| 800     | 22       | 5.45%   |
| 2666    | 14       | 3.47%   |
| 667     | 12       | 2.97%   |
| 1066    | 8        | 1.98%   |
| Unknown | 8        | 1.98%   |
| 533     | 5        | 1.24%   |
| 3600    | 4        | 0.99%   |
| 1867    | 4        | 0.99%   |
| 1866    | 4        | 0.99%   |
| 400     | 4        | 0.99%   |
| 2933    | 3        | 0.74%   |
| 1067    | 2        | 0.5%    |
| 3733    | 1        | 0.25%   |
| 3400    | 1        | 0.25%   |
| 3000    | 1        | 0.25%   |
| 2800    | 1        | 0.25%   |
| 1800    | 1        | 0.25%   |
| 1400    | 1        | 0.25%   |
| 1334    | 1        | 0.25%   |
| 1200    | 1        | 0.25%   |
| 333     | 1        | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 6        | 37.5%   |
| Brother Industries    | 5        | 31.25%  |
| Lexmark International | 2        | 12.5%   |
| Seiko Epson           | 1        | 6.25%   |
| Ricoh                 | 1        | 6.25%   |
| Kyocera               | 1        | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                                             | Desktops | Percent |
|-------------------------------------------------------------------------------------------------------------------|----------|---------|
| Seiko Epson USB2.0 Printer (Hi-speed)                                                                             | 1        | 5.88%   |
| Ricoh SP 112                                                                                                      | 1        | 5.88%   |
| Lexmark International SINDOH A603_A608 Print                                                                      | 1        | 5.88%   |
| Lexmark International Lexmark MS710 Print                                                                         | 1        | 5.88%   |
| Kyocera FS-1025MFP                                                                                                | 1        | 5.88%   |
| HP LaserJet P3005                                                                                                 | 1        | 5.88%   |
| HP LaserJet 2200                                                                                                  | 1        | 5.88%   |
| HP LaserJet 1200                                                                                                  | 1        | 5.88%   |
| HP HP LaserJet P2035 HP Print                                                                                     | 1        | 5.88%   |
| HP HP LaserJet MFP E52645 LaserJet 0 LaserJet 0 LaserJet 1 LaserJet 1 LaserJet 2 LaserJet 2 LaserJet 3 LaserJet 3 | 1        | 5.88%   |
| HP DeskJet 5850c                                                                                                  | 1        | 5.88%   |
| HP Color LaserJet CP1215                                                                                          | 1        | 5.88%   |
| Brother MFC-J200                                                                                                  | 1        | 5.88%   |
| Brother MFC-7360N                                                                                                 | 1        | 5.88%   |
| Brother HL-L2310D series                                                                                          | 1        | 5.88%   |
| Brother HL-1430 Laser Printer                                                                                     | 1        | 5.88%   |
| Brother DCP-J100                                                                                                  | 1        | 5.88%   |

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
| Logitech                      | 11       | 28.95%  |
| Z-Star Microelectronics       | 5        | 13.16%  |
| Chicony Electronics           | 3        | 7.89%   |
| Microdia                      | 2        | 5.26%   |
| IMC Networks                  | 2        | 5.26%   |
| Hewlett-Packard               | 2        | 5.26%   |
| Generalplus Technology        | 2        | 5.26%   |
| ARC International             | 2        | 5.26%   |
| Sunplus Innovation Technology | 1        | 2.63%   |
| Linux Foundation              | 1        | 2.63%   |
| KYE Systems (Mouse Systems)   | 1        | 2.63%   |
| HD WEBCAM                     | 1        | 2.63%   |
| Genesys Logic                 | 1        | 2.63%   |
| GEMBIRD                       | 1        | 2.63%   |
| Arkmicro Technologies         | 1        | 2.63%   |
| Alcor Micro                   | 1        | 2.63%   |
| A4Tech                        | 1        | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 3        | 7.89%   |
| Logitech Webcam C310                              | 2        | 5.26%   |
| Logitech HD Pro Webcam C920                       | 2        | 5.26%   |
| Logitech C922 Pro Stream Webcam                   | 2        | 5.26%   |
| IMC Networks XHC Camera                           | 2        | 5.26%   |
| Generalplus GENERAL WEBCAM                        | 2        | 5.26%   |
| ARC International Camera                          | 2        | 5.26%   |
| Z-Star Venus USB2.0 Camera                        | 1        | 2.63%   |
| Z-Star Vega USB 2.0 Camera                        | 1        | 2.63%   |
| Z-Star Lenovo USB2.0 UVC Camera                   | 1        | 2.63%   |
| Z-Star Integrated Camera                          | 1        | 2.63%   |
| Z-Star A4 TECH USB2.0 PC Camera J                 | 1        | 2.63%   |
| Sunplus Aukey-PC-LM1E Camera                      | 1        | 2.63%   |
| Microdia Webcam Vitade AF                         | 1        | 2.63%   |
| Microdia ASUS USB2.0 Webcam                       | 1        | 2.63%   |
| Logitech Webcam C930e                             | 1        | 2.63%   |
| Logitech BRIO Ultra HD Webcam                     | 1        | 2.63%   |
| Linux Foundation HD Camera                        | 1        | 2.63%   |
| KYE Systems (Mouse Systems) AUKEY PC-LM1E Camera  | 1        | 2.63%   |
| HP Realtek PC Camera                              | 1        | 2.63%   |
| HP Premium Starter Webcam                         | 1        | 2.63%   |
| HD WEBCAM HD WEBCAM                               | 1        | 2.63%   |
| Genesys Logic Digital Microscope                  | 1        | 2.63%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 2.63%   |
| Chicony HP Integrated Webcam                      | 1        | 2.63%   |
| Chicony HP Display Camera                         | 1        | 2.63%   |
| Chicony HP 0.3MP Webcam                           | 1        | 2.63%   |
| Arkmicro USB2.0 PC CAMERA                         | 1        | 2.63%   |
| Alcor Micro PC Camera                             | 1        | 2.63%   |
| A4Tech A4tech FHD 1080P PC Camera                 | 1        | 2.63%   |

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
| 1     | 180      | 47.37%  |
| 0     | 138      | 36.32%  |
| 2     | 50       | 13.16%  |
| 3     | 9        | 2.37%   |
| 4     | 3        | 0.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 198      | 66.22%  |
| Net/wireless             | 50       | 16.72%  |
| Sound                    | 17       | 5.69%   |
| Firewire controller      | 9        | 3.01%   |
| Bluetooth                | 9        | 3.01%   |
| Card reader              | 7        | 2.34%   |
| Network                  | 4        | 1.34%   |
| Net/ethernet             | 4        | 1.34%   |
| Storage/raid             | 1        | 0.33%   |
