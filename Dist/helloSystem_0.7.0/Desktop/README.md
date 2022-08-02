helloSystem 0.7.0 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.7.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 196

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Gigabyte      | X570 AORUS PRO              | [ad56307789](https://bsd-hardware.info/?probe=ad56307789) | Aug 01, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [6d5bfb02a0](https://bsd-hardware.info/?probe=6d5bfb02a0) | Jul 28, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [f50526a6d6](https://bsd-hardware.info/?probe=f50526a6d6) | Jul 27, 2022 |
| MAXSUN        | MS-H110D4L FS M.2           | [39d06b12fd](https://bsd-hardware.info/?probe=39d06b12fd) | Jul 25, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [a96e41f99e](https://bsd-hardware.info/?probe=a96e41f99e) | Jul 20, 2022 |
| ASUSTek       | P8B WS                      | [dd7f8123d2](https://bsd-hardware.info/?probe=dd7f8123d2) | Jul 19, 2022 |
| HP            | 8055                        | [269b4f3210](https://bsd-hardware.info/?probe=269b4f3210) | Jul 17, 2022 |
| Shuttle       | FH170                       | [a156048964](https://bsd-hardware.info/?probe=a156048964) | Jul 16, 2022 |
| Shuttle       | FH170                       | [81b62c2839](https://bsd-hardware.info/?probe=81b62c2839) | Jul 16, 2022 |
| ASUSTek       | Maximus IX HERO             | [ea2f21a15f](https://bsd-hardware.info/?probe=ea2f21a15f) | Jul 12, 2022 |
| ASUSTek       | Maximus IX HERO             | [81668557c6](https://bsd-hardware.info/?probe=81668557c6) | Jul 08, 2022 |
| Lenovo        | NO DPK                      | [2c79a92fc4](https://bsd-hardware.info/?probe=2c79a92fc4) | Jul 06, 2022 |
| Pegatron      | IPM41-D3                    | [1cd93cd5d3](https://bsd-hardware.info/?probe=1cd93cd5d3) | Jul 04, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [4d4993a732](https://bsd-hardware.info/?probe=4d4993a732) | Jun 24, 2022 |
| ALLEGIANCE... | X79 V3.3F                   | [190560a4f4](https://bsd-hardware.info/?probe=190560a4f4) | Jun 23, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | [346bc6f0ae](https://bsd-hardware.info/?probe=346bc6f0ae) | Jun 20, 2022 |
| Gigabyte      | GA-970A-UD3                 | [a094c1c53b](https://bsd-hardware.info/?probe=a094c1c53b) | Jun 20, 2022 |
| HP            | 304Bh                       | [8a3151b3cd](https://bsd-hardware.info/?probe=8a3151b3cd) | Jun 16, 2022 |
| Lenovo        | ThinkCentre XXXX Y          | [162bbe4eac](https://bsd-hardware.info/?probe=162bbe4eac) | Jun 10, 2022 |
| Acer          | EM61SM/EM61PM               | [3b8d6cb36e](https://bsd-hardware.info/?probe=3b8d6cb36e) | Jun 07, 2022 |
| Positivo      | POS-PIQ77CL POSITIVO        | [848361c724](https://bsd-hardware.info/?probe=848361c724) | May 31, 2022 |
| Gigabyte      | F2A88XM-HD3                 | [c734325ede](https://bsd-hardware.info/?probe=c734325ede) | May 31, 2022 |
| Dell          | 048DY8 A00                  | [7d1c59b392](https://bsd-hardware.info/?probe=7d1c59b392) | May 29, 2022 |
| ASUSTek       | P5LD2                       | [64208afa2c](https://bsd-hardware.info/?probe=64208afa2c) | May 25, 2022 |
| T-bao         | MINI PC V1.0                | [a89b2081bb](https://bsd-hardware.info/?probe=a89b2081bb) | May 25, 2022 |
| Gigabyte      | B75M-D3H                    | [d0565222dc](https://bsd-hardware.info/?probe=d0565222dc) | May 24, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [ee8ba76de5](https://bsd-hardware.info/?probe=ee8ba76de5) | May 22, 2022 |
| ASUSTek       | P8Z77-V LX                  | [e7055d83e2](https://bsd-hardware.info/?probe=e7055d83e2) | May 20, 2022 |
| Dell          | 0G261D A00                  | [c0fafdb905](https://bsd-hardware.info/?probe=c0fafdb905) | May 14, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [d9c28e14df](https://bsd-hardware.info/?probe=d9c28e14df) | May 13, 2022 |
| ASUSTek       | PRIME X570-P                | [aad86a8b8e](https://bsd-hardware.info/?probe=aad86a8b8e) | May 10, 2022 |
| Lenovo        | MAHOBAY                     | [b54df77b59](https://bsd-hardware.info/?probe=b54df77b59) | May 07, 2022 |
| Gigabyte      | F2A68HM-H                   | [daed3f9401](https://bsd-hardware.info/?probe=daed3f9401) | May 06, 2022 |
| ASUSTek       | P8Z77-V LX                  | [bf3d4941a2](https://bsd-hardware.info/?probe=bf3d4941a2) | May 06, 2022 |
| ASUSTek       | P8Z77-V LX                  | [dd3afff7f0](https://bsd-hardware.info/?probe=dd3afff7f0) | May 06, 2022 |
| Dell          | 0Y7WYT A00                  | [76674e4d62](https://bsd-hardware.info/?probe=76674e4d62) | May 06, 2022 |
| OEM           | B85 JHS359                  | [c5d29cc6b3](https://bsd-hardware.info/?probe=c5d29cc6b3) | May 03, 2022 |
| Gigabyte      | A320M-H-CF                  | [24d308754b](https://bsd-hardware.info/?probe=24d308754b) | May 02, 2022 |
| HP            | 0AA8h                       | [f9b906ea47](https://bsd-hardware.info/?probe=f9b906ea47) | Apr 30, 2022 |
| Supermicro    | X9DAL                       | [ef1f3da3ce](https://bsd-hardware.info/?probe=ef1f3da3ce) | Apr 26, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [271f1aa4d1](https://bsd-hardware.info/?probe=271f1aa4d1) | Apr 24, 2022 |
| Gigabyte      | B450 AORUS M                | [427cf12b45](https://bsd-hardware.info/?probe=427cf12b45) | Apr 22, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [f7a3f1dfd3](https://bsd-hardware.info/?probe=f7a3f1dfd3) | Apr 21, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [2fd6d176ce](https://bsd-hardware.info/?probe=2fd6d176ce) | Apr 21, 2022 |
| Intel         | H55                         | [1478e4af73](https://bsd-hardware.info/?probe=1478e4af73) | Apr 20, 2022 |
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
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [5038186437](https://bsd-hardware.info/?probe=5038186437) | Apr 02, 2022 |
| ASUSTek       | P8Z77-V LX                  | [42419abab8](https://bsd-hardware.info/?probe=42419abab8) | Apr 01, 2022 |
| Dell          | 0D6H9T A00                  | [7daab72741](https://bsd-hardware.info/?probe=7daab72741) | Apr 01, 2022 |
| ASUSTek       | P8Z77-V LX                  | [49627775f3](https://bsd-hardware.info/?probe=49627775f3) | Mar 31, 2022 |
| ASUSTek       | P6-P8H61E                   | [11664cd9d7](https://bsd-hardware.info/?probe=11664cd9d7) | Mar 30, 2022 |
| ASUSTek       | M4A88T-M                    | [6a615f6be5](https://bsd-hardware.info/?probe=6a615f6be5) | Mar 30, 2022 |
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
| ASUSTek       | P5Q DELUXE                  | [b4234170e8](https://bsd-hardware.info/?probe=b4234170e8) | Mar 10, 2022 |
| Pegatron      | IPM41-D3                    | [a58b9a4f8f](https://bsd-hardware.info/?probe=a58b9a4f8f) | Mar 09, 2022 |
| Koloe         | X58                         | [58e098eca2](https://bsd-hardware.info/?probe=58e098eca2) | Mar 09, 2022 |
| HP            | 8054                        | [86b6b8373c](https://bsd-hardware.info/?probe=86b6b8373c) | Mar 08, 2022 |
| HP            | 8054                        | [00078554d2](https://bsd-hardware.info/?probe=00078554d2) | Mar 08, 2022 |
| Koloe         | X58                         | [c501dfa5c8](https://bsd-hardware.info/?probe=c501dfa5c8) | Mar 07, 2022 |
| HP            | 1905                        | [e271589365](https://bsd-hardware.info/?probe=e271589365) | Mar 01, 2022 |
| Gigabyte      | B450M S2H                   | [78f79fab6f](https://bsd-hardware.info/?probe=78f79fab6f) | Feb 28, 2022 |
| Dell          | 0KV62T A00                  | [0541a207c7](https://bsd-hardware.info/?probe=0541a207c7) | Feb 28, 2022 |
| HP            | 1905                        | [aa010e00f2](https://bsd-hardware.info/?probe=aa010e00f2) | Feb 28, 2022 |
| ASRock        | TRX40 Taichi                | [a2df68e1d1](https://bsd-hardware.info/?probe=a2df68e1d1) | Feb 26, 2022 |
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
| Gigabyte      | C246M-WU4-CF                | [4b6c6d8bde](https://bsd-hardware.info/?probe=4b6c6d8bde) | Feb 15, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [df6278638e](https://bsd-hardware.info/?probe=df6278638e) | Feb 15, 2022 |
| ASRock        | H61M/U3S3                   | [257e13f206](https://bsd-hardware.info/?probe=257e13f206) | Feb 12, 2022 |
| ASUSTek       | PRIME Z390-P                | [abf34bbc7e](https://bsd-hardware.info/?probe=abf34bbc7e) | Feb 12, 2022 |
| ASRock        | H61M/U3S3                   | [34dac4c0cd](https://bsd-hardware.info/?probe=34dac4c0cd) | Feb 11, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [6997de25f9](https://bsd-hardware.info/?probe=6997de25f9) | Feb 11, 2022 |
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
| ASUSTek       | P5GC-MX                     | [372749f9d7](https://bsd-hardware.info/?probe=372749f9d7) | Jan 27, 2022 |
| Unknown       | Unknown                     | [a9d799ca71](https://bsd-hardware.info/?probe=a9d799ca71) | Jan 27, 2022 |
| ASUSTek       | P5B SE                      | [f97fba19c1](https://bsd-hardware.info/?probe=f97fba19c1) | Jan 26, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [9f0a000ceb](https://bsd-hardware.info/?probe=9f0a000ceb) | Jan 25, 2022 |
| ASUSTek       | P5B SE                      | [e3332e7b94](https://bsd-hardware.info/?probe=e3332e7b94) | Jan 25, 2022 |
| ASRock        | B460M Pro4                  | [107a1e59f5](https://bsd-hardware.info/?probe=107a1e59f5) | Jan 25, 2022 |
| ASRock        | A300M-STX                   | [8edf072b67](https://bsd-hardware.info/?probe=8edf072b67) | Jan 25, 2022 |
| ASUSTek       | BM6835_BM6635_BP6335        | [73562aa169](https://bsd-hardware.info/?probe=73562aa169) | Jan 25, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [df08e2e8f0](https://bsd-hardware.info/?probe=df08e2e8f0) | Jan 24, 2022 |
| ASUSTek       | P7H55-M                     | [fb73c2f7dc](https://bsd-hardware.info/?probe=fb73c2f7dc) | Jan 23, 2022 |
| HP            | 1998                        | [b59dbcdc9c](https://bsd-hardware.info/?probe=b59dbcdc9c) | Jan 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [670e41ed41](https://bsd-hardware.info/?probe=670e41ed41) | Jan 21, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [04abd226f3](https://bsd-hardware.info/?probe=04abd226f3) | Jan 21, 2022 |
| ASUSTek       | Maximus VIII HERO           | [a780a7bab2](https://bsd-hardware.info/?probe=a780a7bab2) | Jan 18, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | [9cd2758a5f](https://bsd-hardware.info/?probe=9cd2758a5f) | Jan 18, 2022 |
| ASUSTek       | PRIME X570-P                | [3dead218e1](https://bsd-hardware.info/?probe=3dead218e1) | Jan 16, 2022 |
| Gigabyte      | B365 HD3                    | [62fc48bd99](https://bsd-hardware.info/?probe=62fc48bd99) | Jan 15, 2022 |
| Dell          | 0XCR8D A03                  | [48e9447b37](https://bsd-hardware.info/?probe=48e9447b37) | Jan 15, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [d377e06101](https://bsd-hardware.info/?probe=d377e06101) | Jan 15, 2022 |
| Gigabyte      | Z77N-WIFI                   | [459bb6486d](https://bsd-hardware.info/?probe=459bb6486d) | Jan 13, 2022 |
| ASUSTek       | P8Z68-M PRO                 | [a0885f4f44](https://bsd-hardware.info/?probe=a0885f4f44) | Jan 10, 2022 |
| HP            | 8169                        | [85e0cf058c](https://bsd-hardware.info/?probe=85e0cf058c) | Jan 10, 2022 |
| ASUSTek       | GA35DX                      | [eccb947ae4](https://bsd-hardware.info/?probe=eccb947ae4) | Jan 05, 2022 |
| Unknown       | G31T-M7                     | [ed7d80e01a](https://bsd-hardware.info/?probe=ed7d80e01a) | Jan 03, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | [a671e3eb04](https://bsd-hardware.info/?probe=a671e3eb04) | Dec 31, 2021 |
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
| Gigabyte      | H270M-DS3H-CF               | [50fba6deda](https://bsd-hardware.info/?probe=50fba6deda) | Dec 11, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [6a1100cfdb](https://bsd-hardware.info/?probe=6a1100cfdb) | Dec 11, 2021 |
| Acer          | RevoOne RL85                | [a1e32de7da](https://bsd-hardware.info/?probe=a1e32de7da) | Dec 10, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [b900b364f6](https://bsd-hardware.info/?probe=b900b364f6) | Dec 10, 2021 |
| Dell          | 0YF8P5 A00                  | [0f03a66475](https://bsd-hardware.info/?probe=0f03a66475) | Dec 09, 2021 |
| Dell          | 0YF8P5 A00                  | [83b36f7c3d](https://bsd-hardware.info/?probe=83b36f7c3d) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [a084ff48c2](https://bsd-hardware.info/?probe=a084ff48c2) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [17b557d792](https://bsd-hardware.info/?probe=17b557d792) | Dec 08, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [8cfe11fe93](https://bsd-hardware.info/?probe=8cfe11fe93) | Nov 30, 2021 |
| HP            | 843B                        | [376e006a40](https://bsd-hardware.info/?probe=376e006a40) | Nov 30, 2021 |
| Intel         | DG41TY AAE47335-300         | [dd357bcaa5](https://bsd-hardware.info/?probe=dd357bcaa5) | Nov 30, 2021 |
| HP            | 843B                        | [404224439d](https://bsd-hardware.info/?probe=404224439d) | Nov 29, 2021 |
| HP            | 843B                        | [a8ac0e9efb](https://bsd-hardware.info/?probe=a8ac0e9efb) | Nov 29, 2021 |
| HP            | 1825                        | [32f07d2ba3](https://bsd-hardware.info/?probe=32f07d2ba3) | Nov 28, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [4cd5e5166a](https://bsd-hardware.info/?probe=4cd5e5166a) | Nov 27, 2021 |
| ASRock        | 775i945GZ                   | [16fc4ee10d](https://bsd-hardware.info/?probe=16fc4ee10d) | Nov 26, 2021 |
| HP            | 844C                        | [fb7d8eaf5d](https://bsd-hardware.info/?probe=fb7d8eaf5d) | Nov 06, 2021 |
| Unknown       | X79                         | [ef88cbc606](https://bsd-hardware.info/?probe=ef88cbc606) | Nov 05, 2021 |
| HP            | 843B                        | [9761f29b5e](https://bsd-hardware.info/?probe=9761f29b5e) | Oct 25, 2021 |
| Acer          | Aspire TC-780               | [3ce8481842](https://bsd-hardware.info/?probe=3ce8481842) | Oct 10, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 143      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 142      | 99.3%   |
| GNOME        | 1        | 0.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 143      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 143      | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 138      | 96.5%   |
| es_ES | 2        | 1.4%    |
| fr_FR | 1        | 0.7%    |
| de_DE | 1        | 0.7%    |
| C     | 1        | 0.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 138      | 96.5%   |
| BIOS | 5        | 3.5%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Cd9660 | 91       | 61.9%   |
| Zfs    | 56       | 38.1%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 139      | 97.2%   |
| MBR  | 4        | 2.8%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 43       | 30.07%  |
| Gigabyte Technology | 29       | 20.28%  |
| ASRock              | 12       | 8.39%   |
| Hewlett-Packard     | 11       | 7.69%   |
| Dell                | 11       | 7.69%   |
| MSI                 | 6        | 4.2%    |
| Intel               | 6        | 4.2%    |
| Lenovo              | 4        | 2.8%    |
| Pegatron            | 3        | 2.1%    |
| Acer                | 2        | 1.4%    |
| Unknown             | 2        | 1.4%    |
| T-bao               | 1        | 0.7%    |
| Supermicro          | 1        | 0.7%    |
| Shuttle             | 1        | 0.7%    |
| Quanta              | 1        | 0.7%    |
| Positivo            | 1        | 0.7%    |
| OEM                 | 1        | 0.7%    |
| Medion              | 1        | 0.7%    |
| MAXSUN              | 1        | 0.7%    |
| Koloe               | 1        | 0.7%    |
| Fujitsu             | 1        | 0.7%    |
| ECS                 | 1        | 0.7%    |
| BESSTAR Tech        | 1        | 0.7%    |
| Apple               | 1        | 0.7%    |
| ALLEGIANCE GAMING   | 1        | 0.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| HP EliteDesk 700 G1 SFF             | 2        | 1.4%    |
| Dell Precision T1700                | 2        | 1.4%    |
| ASUS TUF GAMING X570-PLUS           | 2        | 1.4%    |
| ASUS PRIME X570-P                   | 2        | 1.4%    |
| ASUS P8Z77-V LX                     | 2        | 1.4%    |
| ASRock X570 Phantom Gaming 4        | 2        | 1.4%    |
| Unknown                             | 2        | 1.4%    |
| T-bao MINI PC                       | 1        | 0.7%    |
| Supermicro X9DAL                    | 1        | 0.7%    |
| Shuttle XH170                       | 1        | 0.7%    |
| Quanta 120-1135                     | 1        | 0.7%    |
| Positivo POS-PIQ77CL                | 1        | 0.7%    |
| Pegatron IPM41-D3                   | 1        | 0.7%    |
| Pegatron Compaq 505B Microtower PC  | 1        | 0.7%    |
| Pegatron AY627AA-ABA a4313w         | 1        | 0.7%    |
| OEM B85 JHS359                      | 1        | 0.7%    |
| MSI MS-7D25                         | 1        | 0.7%    |
| MSI MS-7B86                         | 1        | 0.7%    |
| MSI MS-7A33                         | 1        | 0.7%    |
| MSI MS-7816                         | 1        | 0.7%    |
| MSI MS-7758                         | 1        | 0.7%    |
| MSI MS-7369                         | 1        | 0.7%    |
| Medion H61H2-LM3                    | 1        | 0.7%    |
| MAXSUN MS-H110D4L FS M.2            | 1        | 0.7%    |
| Lenovo YangTianA8800T               | 1        | 0.7%    |
| Lenovo ThinkCentre XXXX Y           | 1        | 0.7%    |
| Lenovo ThinkCentre M72e m72e        | 1        | 0.7%    |
| Lenovo IdeaCentre B545 10100        | 1        | 0.7%    |
| Koloe Thurley                       | 1        | 0.7%    |
| Intel X58                           | 1        | 0.7%    |
| Intel H81                           | 1        | 0.7%    |
| Intel H55                           | 1        | 0.7%    |
| Intel DH77EB AAG39073-400           | 1        | 0.7%    |
| Intel DG41TY AAE47335-300           | 1        | 0.7%    |
| Intel DCP847SKE G80890-107          | 1        | 0.7%    |
| HP Z230 Tower Workstation           | 1        | 0.7%    |
| HP ProDesk 600 G2 DM                | 1        | 0.7%    |
| HP Pavilion Gaming Desktop 690-00xx | 1        | 0.7%    |
| HP EliteDesk 800 G2 SFF             | 1        | 0.7%    |
| HP EliteDesk 800 G2 DM 35W          | 1        | 0.7%    |
| HP EliteDesk 800 G1 DM              | 1        | 0.7%    |
| HP Compaq dc7800p Small Form Factor | 1        | 0.7%    |
| HP Compaq 8100 Elite CMT PC         | 1        | 0.7%    |
| HP 844C                             | 1        | 0.7%    |
| Gigabyte Z77X-UD3H                  | 1        | 0.7%    |
| Gigabyte Z77N-WIFI                  | 1        | 0.7%    |
| Gigabyte Z390 GAMING X              | 1        | 0.7%    |
| Gigabyte X58A-UD5                   | 1        | 0.7%    |
| Gigabyte X570 AORUS PRO             | 1        | 0.7%    |
| Gigabyte X570 AORUS ELITE           | 1        | 0.7%    |
| Gigabyte P41T-D3                    | 1        | 0.7%    |
| Gigabyte OPTIMA B0307               | 1        | 0.7%    |
| Gigabyte H61M-S2PV                  | 1        | 0.7%    |
| Gigabyte H270M-DS3H                 | 1        | 0.7%    |
| Gigabyte H270-Gaming 3              | 1        | 0.7%    |
| Gigabyte H170-D3HP                  | 1        | 0.7%    |
| Gigabyte H110N-CF                   | 1        | 0.7%    |
| Gigabyte GA-970A-UD3                | 1        | 0.7%    |
| Gigabyte G31M-ES2C                  | 1        | 0.7%    |
| Gigabyte F2A88XM-HD3                | 1        | 0.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 9        | 6.29%   |
| Dell OptiPlex         | 6        | 4.2%    |
| ASUS ROG              | 6        | 4.2%    |
| HP EliteDesk          | 5        | 3.5%    |
| ASUS TUF              | 4        | 2.8%    |
| Lenovo ThinkCentre    | 2        | 1.4%    |
| HP Compaq             | 2        | 1.4%    |
| Gigabyte X570         | 2        | 1.4%    |
| Gigabyte B450         | 2        | 1.4%    |
| Dell Precision        | 2        | 1.4%    |
| ASUS P8Z77-V          | 2        | 1.4%    |
| ASUS Maximus          | 2        | 1.4%    |
| ASRock X570           | 2        | 1.4%    |
| Unknown               | 2        | 1.4%    |
| T-bao MINI            | 1        | 0.7%    |
| Supermicro X9DAL      | 1        | 0.7%    |
| Shuttle XH170         | 1        | 0.7%    |
| Quanta 120-1135       | 1        | 0.7%    |
| Positivo POS-PIQ77CL  | 1        | 0.7%    |
| Pegatron IPM41-D3     | 1        | 0.7%    |
| Pegatron Compaq       | 1        | 0.7%    |
| Pegatron AY627AA-ABA  | 1        | 0.7%    |
| OEM B85               | 1        | 0.7%    |
| MSI MS-7D25           | 1        | 0.7%    |
| MSI MS-7B86           | 1        | 0.7%    |
| MSI MS-7A33           | 1        | 0.7%    |
| MSI MS-7816           | 1        | 0.7%    |
| MSI MS-7758           | 1        | 0.7%    |
| MSI MS-7369           | 1        | 0.7%    |
| Medion H61H2-LM3      | 1        | 0.7%    |
| MAXSUN MS-H110D4L     | 1        | 0.7%    |
| Lenovo YangTianA8800T | 1        | 0.7%    |
| Lenovo IdeaCentre     | 1        | 0.7%    |
| Koloe Thurley         | 1        | 0.7%    |
| Intel X58             | 1        | 0.7%    |
| Intel H81             | 1        | 0.7%    |
| Intel H55             | 1        | 0.7%    |
| Intel DH77EB          | 1        | 0.7%    |
| Intel DG41TY          | 1        | 0.7%    |
| Intel DCP847SKE       | 1        | 0.7%    |
| HP Z230               | 1        | 0.7%    |
| HP ProDesk            | 1        | 0.7%    |
| HP Pavilion           | 1        | 0.7%    |
| HP 844C               | 1        | 0.7%    |
| Gigabyte Z77X-UD3H    | 1        | 0.7%    |
| Gigabyte Z77N-WIFI    | 1        | 0.7%    |
| Gigabyte Z390         | 1        | 0.7%    |
| Gigabyte X58A-UD5     | 1        | 0.7%    |
| Gigabyte P41T-D3      | 1        | 0.7%    |
| Gigabyte OPTIMA       | 1        | 0.7%    |
| Gigabyte H61M-S2PV    | 1        | 0.7%    |
| Gigabyte H270M-DS3H   | 1        | 0.7%    |
| Gigabyte H270-Gaming  | 1        | 0.7%    |
| Gigabyte H170-D3HP    | 1        | 0.7%    |
| Gigabyte H110N-CF     | 1        | 0.7%    |
| Gigabyte GA-970A-UD3  | 1        | 0.7%    |
| Gigabyte G31M-ES2C    | 1        | 0.7%    |
| Gigabyte F2A88XM-HD3  | 1        | 0.7%    |
| Gigabyte F2A88XM-D3H  | 1        | 0.7%    |
| Gigabyte F2A68HM-H    | 1        | 0.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 20       | 13.99%  |
| 2021 | 17       | 11.89%  |
| 2012 | 15       | 10.49%  |
| 2018 | 14       | 9.79%   |
| 2014 | 12       | 8.39%   |
| 2017 | 9        | 6.29%   |
| 2013 | 9        | 6.29%   |
| 2009 | 9        | 6.29%   |
| 2020 | 8        | 5.59%   |
| 2016 | 8        | 5.59%   |
| 2010 | 8        | 5.59%   |
| 2015 | 5        | 3.5%    |
| 2011 | 4        | 2.8%    |
| 2007 | 4        | 2.8%    |
| 2008 | 1        | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 143      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 143      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 40       | 27.97%  |
| 8.01-16.0   | 40       | 27.97%  |
| 4.01-8.0    | 24       | 16.78%  |
| 32.01-64.0  | 24       | 16.78%  |
| 64.01-256.0 | 6        | 4.2%    |
| 2.01-3.0    | 4        | 2.8%    |
| 24.01-32.0  | 3        | 2.1%    |
| 1.01-2.0    | 1        | 0.7%    |
| 0.51-1.0    | 1        | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 56       | 38.89%  |
| 0.51-1.0  | 49       | 34.03%  |
| 1.01-2.0  | 33       | 22.92%  |
| 2.01-3.0  | 4        | 2.78%   |
| 3.01-4.0  | 1        | 0.69%   |
| 8.01-16.0 | 1        | 0.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 64       | 43.84%  |
| 2      | 41       | 28.08%  |
| 3      | 13       | 8.9%    |
| 4      | 12       | 8.22%   |
| 0      | 8        | 5.48%   |
| 5      | 4        | 2.74%   |
| 6      | 2        | 1.37%   |
| 9      | 1        | 0.68%   |
| 7      | 1        | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 96       | 67.13%  |
| Yes       | 47       | 32.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 141      | 98.6%   |
| No        | 2        | 1.4%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 100      | 69.93%  |
| Yes       | 43       | 30.07%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 103      | 72.03%  |
| Yes       | 40       | 27.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 20       | 13.99%  |
| Russia       | 20       | 13.99%  |
| China        | 8        | 5.59%   |
| Spain        | 7        | 4.9%    |
| Poland       | 7        | 4.9%    |
| Hungary      | 7        | 4.9%    |
| Brazil       | 7        | 4.9%    |
| Ukraine      | 6        | 4.2%    |
| Italy        | 6        | 4.2%    |
| Germany      | 6        | 4.2%    |
| Canada       | 6        | 4.2%    |
| India        | 4        | 2.8%    |
| Australia    | 4        | 2.8%    |
| UK           | 3        | 2.1%    |
| Turkey       | 3        | 2.1%    |
| Romania      | 3        | 2.1%    |
| France       | 3        | 2.1%    |
| South Korea  | 2        | 1.4%    |
| Peru         | 2        | 1.4%    |
| Norway       | 2        | 1.4%    |
| Vietnam      | 1        | 0.7%    |
| Thailand     | 1        | 0.7%    |
| Taiwan       | 1        | 0.7%    |
| South Africa | 1        | 0.7%    |
| Serbia       | 1        | 0.7%    |
| Portugal     | 1        | 0.7%    |
| Philippines  | 1        | 0.7%    |
| Panama       | 1        | 0.7%    |
| New Zealand  | 1        | 0.7%    |
| Netherlands  | 1        | 0.7%    |
| Mexico       | 1        | 0.7%    |
| Kazakhstan   | 1        | 0.7%    |
| Iceland      | 1        | 0.7%    |
| Greece       | 1        | 0.7%    |
| Finland      | 1        | 0.7%    |
| Denmark      | 1        | 0.7%    |
| Argentina    | 1        | 0.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                          | Desktops | Percent |
|-------------------------------|----------|---------|
| St Petersburg                 | 4        | 2.68%   |
| Moscow                        | 3        | 2.01%   |
| Surgut                        | 2        | 1.34%   |
| Perth                         | 2        | 1.34%   |
| Myrtle Beach                  | 2        | 1.34%   |
| Lima                          | 2        | 1.34%   |
| Kharkiv                       | 2        | 1.34%   |
| Istanbul                      | 2        | 1.34%   |
| Guangzhou                     | 2        | 1.34%   |
| Curitiba                      | 2        | 1.34%   |
| Castilleja de la Cuesta       | 2        | 1.34%   |
| Barnaul                       | 2        | 1.34%   |
| Zhengzhou                     | 1        | 0.67%   |
| Yunlin                        | 1        | 0.67%   |
| Xicheng District              | 1        | 0.67%   |
| Warsaw                        | 1        | 0.67%   |
| Tromsø                       | 1        | 0.67%   |
| Tiruchi                       | 1        | 0.67%   |
| Tampa                         | 1        | 0.67%   |
| Szombathely                   | 1        | 0.67%   |
| Szeged                        | 1        | 0.67%   |
| SzÃ©kesfehÃ©rvÃ¡r       | 1        | 0.67%   |
| Suceava                       | 1        | 0.67%   |
| Stavropol                     | 1        | 0.67%   |
| Sparta                        | 1        | 0.67%   |
| Spalice                       | 1        | 0.67%   |
| Sopron                        | 1        | 0.67%   |
| Songpa-gu                     | 1        | 0.67%   |
| Somerset West                 | 1        | 0.67%   |
| Smiths Falls                  | 1        | 0.67%   |
| Seville                       | 1        | 0.67%   |
| Sao Paulo                     | 1        | 0.67%   |
| Santa Maria                   | 1        | 0.67%   |
| San SebastiÃ¡n de los Reyes | 1        | 0.67%   |
| San Luis Potosí City         | 1        | 0.67%   |
| Saint-Colomban                | 1        | 0.67%   |
| Rio de Janeiro                | 1        | 0.67%   |
| Reykjavik                     | 1        | 0.67%   |
| Renfrew                       | 1        | 0.67%   |
| Poznan                        | 1        | 0.67%   |
| Pilica                        | 1        | 0.67%   |
| Pforzheim                     | 1        | 0.67%   |
| Pflugerville                  | 1        | 0.67%   |
| Perm                          | 1        | 0.67%   |
| Penza                         | 1        | 0.67%   |
| Paso Robles                   | 1        | 0.67%   |
| Panama City                   | 1        | 0.67%   |
| Paju                          | 1        | 0.67%   |
| Ourense                       | 1        | 0.67%   |
| Ormond Beach                  | 1        | 0.67%   |
| Novosibirsk                   | 1        | 0.67%   |
| New Plymouth                  | 1        | 0.67%   |
| New Delhi                     | 1        | 0.67%   |
| Myski                         | 1        | 0.67%   |
| Montreal                      | 1        | 0.67%   |
| Monteleone di Fermo           | 1        | 0.67%   |
| Mladenovac                    | 1        | 0.67%   |
| Midlothian                    | 1        | 0.67%   |
| Melbourne                     | 1        | 0.67%   |
| Malonikolayevka               | 1        | 0.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 51       | 69     | 21.25%  |
| WDC                 | 41       | 57     | 17.08%  |
| Samsung Electronics | 37       | 48     | 15.42%  |
| Toshiba             | 17       | 20     | 7.08%   |
| Crucial             | 15       | 21     | 6.25%   |
| Kingston            | 13       | 17     | 5.42%   |
| A-DATA Technology   | 7        | 8      | 2.92%   |
| SanDisk             | 6        | 6      | 2.5%    |
| Intel               | 6        | 6      | 2.5%    |
| Phison              | 5        | 5      | 2.08%   |
| Hitachi             | 5        | 6      | 2.08%   |
| SK hynix            | 4        | 6      | 1.67%   |
| Goodram             | 4        | 4      | 1.67%   |
| XPG                 | 3        | 3      | 1.25%   |
| Patriot             | 3        | 3      | 1.25%   |
| OCZ                 | 3        | 3      | 1.25%   |
| HGST                | 3        | 3      | 1.25%   |
| PNY                 | 2        | 2      | 0.83%   |
| KingSpec            | 2        | 2      | 0.83%   |
| Gigabyte Technology | 2        | 3      | 0.83%   |
| tigo                | 1        | 1      | 0.42%   |
| Team                | 1        | 1      | 0.42%   |
| SPCC                | 1        | 1      | 0.42%   |
| Silicon Motion      | 1        | 1      | 0.42%   |
| Plextor             | 1        | 1      | 0.42%   |
| Mushkin             | 1        | 1      | 0.42%   |
| LITEON              | 1        | 2      | 0.42%   |
| Lite-On             | 1        | 1      | 0.42%   |
| Intenso             | 1        | 1      | 0.42%   |
| EMTEC               | 1        | 1      | 0.42%   |
| Apacer              | 1        | 1      | 0.42%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB          | 5        | 1.87%   |
| Seagate ST1000DM003-1ER162 1TB          | 4        | 1.49%   |
| Kingston SA400S37120G 120GB             | 4        | 1.49%   |
| XPG GAMMIX S11 Pro 256GB                | 3        | 1.12%   |
| Toshiba HDWD110 1TB                     | 3        | 1.12%   |
| Seagate ST4000DM004-2CV104 4TB          | 3        | 1.12%   |
| Seagate ST31000528AS 1TB                | 3        | 1.12%   |
| Seagate ST2000DM008-2FR102 2TB          | 3        | 1.12%   |
| Samsung SSD 980 PRO 1TB                 | 3        | 1.12%   |
| Samsung SSD 850 EVO 250GB               | 3        | 1.12%   |
| Crucial CT500MX500SSD1 500GB            | 3        | 1.12%   |
| WDC WDS240G2G0A-00JH30 240GB            | 2        | 0.75%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 2        | 0.75%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 2        | 0.75%   |
| WDC WD20PURZ-85GU6Y0 2TB                | 2        | 0.75%   |
| Toshiba DT01ACA100 1TB                  | 2        | 0.75%   |
| Toshiba DT01ACA050 500GB                | 2        | 0.75%   |
| SK hynix BC501 HFM128GDJTNG-8310A 128GB | 2        | 0.75%   |
| Seagate ST3500418AS 500GB               | 2        | 0.75%   |
| Seagate ST3500413AS 500GB               | 2        | 0.75%   |
| Seagate ST3320418AS 320GB               | 2        | 0.75%   |
| Seagate ST3160812AS 160GB               | 2        | 0.75%   |
| SanDisk SDSSDA120G 120GB                | 2        | 0.75%   |
| Samsung SSD 970 EVO Plus 1TB            | 2        | 0.75%   |
| Samsung SSD 970 EVO 250GB               | 2        | 0.75%   |
| Samsung SSD 860 EVO 500GB               | 2        | 0.75%   |
| Samsung SSD 860 EVO 250GB               | 2        | 0.75%   |
| Samsung SSD 750 EVO 120GB               | 2        | 0.75%   |
| Samsung HD322HJ 320GB                   | 2        | 0.75%   |
| Kingston SA2000M81000G 1TB              | 2        | 0.75%   |
| Intel SSDSC2CW120A3 120GB               | 2        | 0.75%   |
| Goodram SSDPR-CL100-120-G2 120GB        | 2        | 0.75%   |
| Crucial CT275MX300SSD1 275GB            | 2        | 0.75%   |
| Crucial CT256MX100SSD1 256GB            | 2        | 0.75%   |
| Crucial CT240BX500SSD1 240GB            | 2        | 0.75%   |
| Crucial CT120BX500SSD1 120GB            | 2        | 0.75%   |
| WDC WDS500G2B0C-00PXH0 500GB            | 1        | 0.37%   |
| WDC WDS500G2B0B-00YS70 500GB            | 1        | 0.37%   |
| WDC WDS500G2B0A-00SM50 500GB            | 1        | 0.37%   |
| WDC WDS250G1B0A-00H9H0 250GB            | 1        | 0.37%   |
| WDC WDS200T2B0C-00PXH0 2TB              | 1        | 0.37%   |
| WDC WDS120G2G0A-00JH30 120GB            | 1        | 0.37%   |
| WDC WDS100T2B0A-00SM50 1TB              | 1        | 0.37%   |
| WDC WDBA3V0010BNC-WRSN 1TB              | 1        | 0.37%   |
| WDC WD60EZRZ-00RWYB1 6TB                | 1        | 0.37%   |
| WDC WD5000LPLX-66ZNTT0 500GB            | 1        | 0.37%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1        | 0.37%   |
| WDC WD5000AZLX-00K2TA0 500GB            | 1        | 0.37%   |
| WDC WD5000AZLX-00CL5A0 500GB            | 1        | 0.37%   |
| WDC WD5000AAKX-75U6AA0 500GB            | 1        | 0.37%   |
| WDC WD5000AAKX-00ERMA0 500GB            | 1        | 0.37%   |
| WDC WD5000AAKS-22A7B0 500GB             | 1        | 0.37%   |
| WDC WD40EZRZ-00GXCB0 4TB                | 1        | 0.37%   |
| WDC WD40EFRX-68N32N0 4TB                | 1        | 0.37%   |
| WDC WD400JB-00ENA0 40GB                 | 1        | 0.37%   |
| WDC WD4004FZWX-00GBGB0 4TB              | 1        | 0.37%   |
| WDC WD3200BPVT-22ZEST0 320GB            | 1        | 0.37%   |
| WDC WD3200AAJS-60Z0A0 320GB             | 1        | 0.37%   |
| WDC WD3200AAJS-22B4A0 320GB             | 1        | 0.37%   |
| WDC WD3200AAJS-00YZCA0 320GB            | 1        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 51       | 66     | 44.74%  |
| WDC                 | 32       | 38     | 28.07%  |
| Toshiba             | 16       | 19     | 14.04%  |
| Samsung Electronics | 7        | 7      | 6.14%   |
| Hitachi             | 5        | 6      | 4.39%   |
| HGST                | 3        | 3      | 2.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 21       | 23     | 22.11%  |
| Crucial             | 14       | 19     | 14.74%  |
| Kingston            | 10       | 13     | 10.53%  |
| WDC                 | 6        | 10     | 6.32%   |
| SanDisk             | 6        | 6      | 6.32%   |
| A-DATA Technology   | 6        | 6      | 6.32%   |
| Intel               | 5        | 5      | 5.26%   |
| Goodram             | 4        | 4      | 4.21%   |
| Patriot             | 3        | 3      | 3.16%   |
| OCZ                 | 3        | 3      | 3.16%   |
| PNY                 | 2        | 2      | 2.11%   |
| KingSpec            | 2        | 2      | 2.11%   |
| Gigabyte Technology | 2        | 3      | 2.11%   |
| Toshiba             | 1        | 1      | 1.05%   |
| tigo                | 1        | 1      | 1.05%   |
| Team                | 1        | 1      | 1.05%   |
| SPCC                | 1        | 1      | 1.05%   |
| SK hynix            | 1        | 1      | 1.05%   |
| Plextor             | 1        | 1      | 1.05%   |
| LITEON              | 1        | 2      | 1.05%   |
| Lite-On             | 1        | 1      | 1.05%   |
| Intenso             | 1        | 1      | 1.05%   |
| EMTEC               | 1        | 1      | 1.05%   |
| Apacer              | 1        | 1      | 1.05%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 91       | 139    | 45.05%  |
| SSD  | 76       | 111    | 37.62%  |
| NVMe | 35       | 54     | 17.33%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 126      | 250    | 78.26%  |
| NVMe | 35       | 54     | 21.74%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 108      | 164    | 62.07%  |
| 0.51-1.0   | 33       | 42     | 18.97%  |
| 1.01-2.0   | 15       | 17     | 8.62%   |
| 3.01-4.0   | 9        | 16     | 5.17%   |
| 2.01-3.0   | 5        | 6      | 2.87%   |
| 4.01-10.0  | 3        | 4      | 1.72%   |
| 10.01-20.0 | 1        | 1      | 0.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 89       | 60.54%  |
| 101-250    | 32       | 21.77%  |
| 251-500    | 16       | 10.88%  |
| 501-1000   | 6        | 4.08%   |
| 51-100     | 3        | 2.04%   |
| 21-50      | 1        | 0.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 142      | 99.3%   |
| 21-50   | 1        | 0.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST3500413AS 500GB           | 2        | 3      | 5%      |
| Seagate ST3320418AS 320GB           | 2        | 2      | 5%      |
| Seagate ST31000528AS 1TB            | 2        | 3      | 5%      |
| WDC WD60EZRZ-00RWYB1 6TB            | 1        | 1      | 2.5%    |
| WDC WD5000AZLX-00CL5A0 500GB        | 1        | 1      | 2.5%    |
| WDC WD5000AAKX-00ERMA0 500GB        | 1        | 1      | 2.5%    |
| WDC WD5000AAKS-22A7B0 500GB         | 1        | 1      | 2.5%    |
| WDC WD400JB-00ENA0 40GB             | 1        | 1      | 2.5%    |
| WDC WD3200AAJS-22B4A0 320GB         | 1        | 1      | 2.5%    |
| WDC WD20EURS-63S48Y0 2TB            | 1        | 1      | 2.5%    |
| WDC WD1600BEVT-22ZCT0 160GB         | 1        | 1      | 2.5%    |
| WDC WD10EZEX-08M2NA0 1TB            | 1        | 1      | 2.5%    |
| WDC WD10EARS-003BB1 1TB             | 1        | 1      | 2.5%    |
| Toshiba MD04ACA400 4TB              | 1        | 1      | 2.5%    |
| Toshiba DT01ACA100 1TB              | 1        | 3      | 2.5%    |
| Toshiba DT01ABA300 3TB              | 1        | 1      | 2.5%    |
| Seagate ST8000NM0055-1RM112 8TB     | 1        | 1      | 2.5%    |
| Seagate ST380211AS 80GB             | 1        | 1      | 2.5%    |
| Seagate ST3500418AS 500GB           | 1        | 1      | 2.5%    |
| Seagate ST3250310AS 250GB           | 1        | 1      | 2.5%    |
| Seagate ST320LM000 HM321HI 320GB    | 1        | 1      | 2.5%    |
| Seagate ST3160812AS 160GB           | 1        | 1      | 2.5%    |
| Seagate ST31000520AS 1TB            | 1        | 1      | 2.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1        | 1      | 2.5%    |
| Seagate ST1000DM003-1ER162 1TB      | 1        | 1      | 2.5%    |
| Samsung Electronics SSD 870 EVO 1TB | 1        | 1      | 2.5%    |
| Samsung Electronics HD322HJ 320GB   | 1        | 1      | 2.5%    |
| Samsung Electronics HD250HJ 250GB   | 1        | 1      | 2.5%    |
| Kingston SV200S3128G 128GB          | 1        | 1      | 2.5%    |
| Kingston SMS200S3120G 120GB         | 1        | 1      | 2.5%    |
| KingSpec P3-128 128GB               | 1        | 1      | 2.5%    |
| Intel SSDSC2CT080A4 80GB            | 1        | 1      | 2.5%    |
| Hitachi HTS541680J9SA00 80GB        | 1        | 2      | 2.5%    |
| Hitachi HDT721010SLA360 1TB         | 1        | 1      | 2.5%    |
| Crucial CT240M500SSD1 240GB         | 1        | 1      | 2.5%    |
| Crucial CT1050MX300SSD1 1TB         | 1        | 1      | 2.5%    |
| A-DATA Technology SX8200PNP 512GB   | 1        | 1      | 2.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 17     | 36.84%  |
| WDC                 | 10       | 10     | 26.32%  |
| Samsung Electronics | 3        | 3      | 7.89%   |
| Toshiba             | 2        | 5      | 5.26%   |
| Kingston            | 2        | 2      | 5.26%   |
| Hitachi             | 2        | 3      | 5.26%   |
| Crucial             | 2        | 2      | 5.26%   |
| KingSpec            | 1        | 1      | 2.63%   |
| Intel               | 1        | 1      | 2.63%   |
| A-DATA Technology   | 1        | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 17     | 46.67%  |
| WDC                 | 10       | 10     | 33.33%  |
| Toshiba             | 2        | 5      | 6.67%   |
| Samsung Electronics | 2        | 2      | 6.67%   |
| Hitachi             | 2        | 3      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 27       | 37     | 77.14%  |
| SSD  | 7        | 7      | 20%     |
| NVMe | 1        | 1      | 2.86%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                        | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC WD3200AAJS-00YZCA0 320GB | 1        | 1      | 100%    |

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
| Works    | 121      | 257    | 77.56%  |
| Malfunc  | 33       | 45     | 21.15%  |
| Detected | 1        | 1      | 0.64%   |
| Failed   | 1        | 1      | 0.64%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 93       | 48.19%  |
| AMD                         | 43       | 22.28%  |
| Samsung Electronics         | 13       | 6.74%   |
| SanDisk                     | 5        | 2.59%   |
| Phison Electronics          | 5        | 2.59%   |
| Nvidia                      | 4        | 2.07%   |
| Marvell Technology Group    | 4        | 2.07%   |
| ADATA Technology            | 4        | 2.07%   |
| SK hynix                    | 3        | 1.55%   |
| Kingston Technology Company | 3        | 1.55%   |
| JMicron Technology          | 3        | 1.55%   |
| Broadcom / LSI              | 3        | 1.55%   |
| ASMedia Technology          | 3        | 1.55%   |
| Silicon Motion              | 2        | 1.04%   |
| Micron/Crucial Technology   | 2        | 1.04%   |
| VIA Technologies            | 1        | 0.52%   |
| Seagate Technology          | 1        | 0.52%   |
| Realtek Semiconductor       | 1        | 0.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 33       | 14.22%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 13       | 5.6%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 12       | 5.17%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 9        | 3.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 9        | 3.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 8        | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 8        | 3.45%   |
| Intel SATA Controller [RAID mode]                                              | 7        | 3.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7        | 3.02%   |
| AMD 400 Series Chipset SATA Controller                                         | 7        | 3.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6        | 2.59%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4        | 1.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4        | 1.72%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 4        | 1.72%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4        | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4        | 1.72%   |
| AMD 300 Series Chipset SATA Controller                                         | 4        | 1.72%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 4        | 1.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3        | 1.29%   |
| Phison E12 NVMe Controller                                                     | 3        | 1.29%   |
| Nvidia MCP61 SATA Controller                                                   | 3        | 1.29%   |
| Kingston Company A2000 NVMe SSD                                                | 3        | 1.29%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 3        | 1.29%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3        | 1.29%   |
| AMD FCH SATA Controller D                                                      | 3        | 1.29%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2        | 0.86%   |
| JMicron JMB363 SATA/IDE Controller                                             | 2        | 0.86%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 2        | 0.86%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 2        | 0.86%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 2        | 0.86%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                     | 2        | 0.86%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                     | 2        | 0.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2        | 0.86%   |
| AMD X370 Series Chipset SATA Controller                                        | 2        | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 2        | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 0.86%   |
| Unknown                                                                        | 2        | 0.86%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1        | 0.43%   |
| VIA VT8237A SATA 2-Port Controller                                             | 1        | 0.43%   |
| SK hynix Gold P31 SSD                                                          | 1        | 0.43%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 0.43%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1        | 0.43%   |
| Seagate FireCuda 520 SSD                                                       | 1        | 0.43%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 0.43%   |
| Phison NVMe Storage Controller                                                 | 1        | 0.43%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 0.43%   |
| Nvidia MCP65 AHCI Controller                                                   | 1        | 0.43%   |
| Nvidia MCP61 IDE                                                               | 1        | 0.43%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1        | 0.43%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1        | 0.43%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1        | 0.43%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 0.43%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                        | 1        | 0.43%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                          | 1        | 0.43%   |
| JMicron JMB361 AHCI/IDE                                                        | 1        | 0.43%   |
| Intel SSD 660P Series                                                          | 1        | 0.43%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1        | 0.43%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 1        | 0.43%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1        | 0.43%   |
| Intel 82Q35 Express PT IDER Controller                                         | 1        | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 112      | 59.89%  |
| NVMe | 35       | 18.72%  |
| IDE  | 28       | 14.97%  |
| RAID | 10       | 5.35%   |
| SAS  | 1        | 0.53%   |
| SCSI | 1        | 0.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 95       | 66.43%  |
| AMD    | 48       | 33.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 5        | 3.5%    |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 2.1%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 2.1%    |
| Intel Xeon CPU X3470 @ 2.93GHz              | 2        | 1.4%    |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz         | 2        | 1.4%    |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 2        | 1.4%    |
| Intel Pentium CPU G860 @ 3.00GHz            | 2        | 1.4%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 1.4%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.4%    |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 1.4%    |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 1.4%    |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 1.4%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.4%    |
| Intel Core i5-3450 CPU @ 3.10GHz            | 2        | 1.4%    |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 1.4%    |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 2        | 1.4%    |
| Intel Core 2 Duo                            | 2        | 1.4%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 1.4%    |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 1.4%    |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.4%    |
| AMD Ryzen 5 3600X 6-Core Processor          | 2        | 1.4%    |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 1.4%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 1.4%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 1.4%    |
| Intel Xeon E-2136 CPU @ 3.30GHz             | 1        | 0.7%    |
| Intel Xeon CPU X5647 @ 2.93GHz              | 1        | 0.7%    |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 0.7%    |
| Intel Xeon CPU E5504 @ 2.00GHz              | 1        | 0.7%    |
| Intel Xeon CPU E5-2630L 0 @ 2.00GHz         | 1        | 0.7%    |
| Intel Xeon CPU E5-2403 v2 @ 1.80GHz         | 1        | 0.7%    |
| Intel Xeon CPU E31245 @ 3.30GHz             | 1        | 0.7%    |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz        | 1        | 0.7%    |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1        | 0.7%    |
| Intel Xeon CPU E3-1240 V2 @ 3.40GHz         | 1        | 0.7%    |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1        | 0.7%    |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1        | 0.7%    |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 1        | 0.7%    |
| Intel Pentium Dual-Core CPU E6500 @         | 1        | 0.7%    |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.7%    |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.7%    |
| Intel Pentium D CPU 3.00GHz                 | 1        | 0.7%    |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 0.7%    |
| Intel Pentium CPU G3460T @ 3.00GHz          | 1        | 0.7%    |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1        | 0.7%    |
| Intel Core i9-9900 CPU @ 3.10GHz            | 1        | 0.7%    |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 0.7%    |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 0.7%    |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.7%    |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 0.7%    |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.7%    |
| Intel Core i7-6700T CPU @ 2.80GHz           | 1        | 0.7%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.7%    |
| Intel Core i7 CPU                           | 1        | 0.7%    |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 0.7%    |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.7%    |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 0.7%    |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 0.7%    |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1        | 0.7%    |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 0.7%    |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 26       | 18.18%  |
| Intel Xeon              | 17       | 11.89%  |
| Intel Core i7           | 15       | 10.49%  |
| AMD Ryzen 7             | 11       | 7.69%   |
| AMD Ryzen 5             | 11       | 7.69%   |
| Intel Core i3           | 8        | 5.59%   |
| Intel Core 2 Quad       | 6        | 4.2%    |
| Intel Pentium           | 5        | 3.5%    |
| Intel Core 2 Duo        | 5        | 3.5%    |
| Intel Pentium Dual-Core | 4        | 2.8%    |
| AMD Ryzen 9             | 4        | 2.8%    |
| AMD Ryzen 3             | 4        | 2.8%    |
| AMD Phenom II X4        | 3        | 2.1%    |
| Other                   | 2        | 1.4%    |
| Intel Celeron           | 2        | 1.4%    |
| AMD Ryzen Threadripper  | 2        | 1.4%    |
| AMD FX                  | 2        | 1.4%    |
| AMD A10                 | 2        | 1.4%    |
| Intel Pentium Dual      | 1        | 0.7%    |
| Intel Pentium D         | 1        | 0.7%    |
| Intel Core i9           | 1        | 0.7%    |
| Intel Core 2            | 1        | 0.7%    |
| Intel Atom              | 1        | 0.7%    |
| AMD Ryzen 5 PRO         | 1        | 0.7%    |
| AMD E2                  | 1        | 0.7%    |
| AMD E                   | 1        | 0.7%    |
| AMD Athlon II X4        | 1        | 0.7%    |
| AMD Athlon II X2        | 1        | 0.7%    |
| AMD Athlon Dual Core    | 1        | 0.7%    |
| AMD Athlon 64 X2        | 1        | 0.7%    |
| AMD A6                  | 1        | 0.7%    |
| AMD A4                  | 1        | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 58       | 40.56%  |
| 2       | 30       | 20.98%  |
| 6       | 12       | 8.39%   |
| 16      | 10       | 6.99%   |
| 8       | 10       | 6.99%   |
| 12      | 8        | 5.59%   |
| Unknown | 8        | 5.59%   |
| 24      | 3        | 2.1%    |
| 64      | 1        | 0.7%    |
| 48      | 1        | 0.7%    |
| 32      | 1        | 0.7%    |
| 14      | 1        | 0.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 142      | 99.3%   |
| 2      | 1        | 0.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 93       | 65.03%  |
| 2       | 42       | 29.37%  |
| Unknown | 8        | 5.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| IvyBridge   | 16       | 11.19%  |
| Haswell     | 14       | 9.79%   |
| Skylake     | 13       | 9.09%   |
| KabyLake    | 13       | 9.09%   |
| Zen 2       | 12       | 8.39%   |
| Penryn      | 12       | 8.39%   |
| SandyBridge | 9        | 6.29%   |
| Zen+        | 8        | 5.59%   |
| Zen         | 8        | 5.59%   |
| Piledriver  | 6        | 4.2%    |
| Zen 3       | 5        | 3.5%    |
| K10         | 5        | 3.5%    |
| Core        | 5        | 3.5%    |
| Nehalem     | 4        | 2.8%    |
| Westmere    | 3        | 2.1%    |
| K8 Hammer   | 2        | 1.4%    |
| Unknown     | 2        | 1.4%    |
| NetBurst    | 1        | 0.7%    |
| Jaguar      | 1        | 0.7%    |
| CometLake   | 1        | 0.7%    |
| Broadwell   | 1        | 0.7%    |
| Bonnell     | 1        | 0.7%    |
| Bobcat      | 1        | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 59       | 39.6%   |
| Intel  | 49       | 32.89%  |
| AMD    | 41       | 27.52%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 530                                                       | 9        | 6%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 5.33%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 8        | 5.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 3.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 5        | 3.33%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 2.67%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 2.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 2.67%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 2.67%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 2.67%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 2%      |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 2%      |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 2%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 2%      |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.33%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 1.33%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.33%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 1.33%   |
| Nvidia GK107GL [Quadro K2000]                                               | 2        | 1.33%   |
| Nvidia GF108 [GeForce GT 430]                                               | 2        | 1.33%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 1.33%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 2        | 1.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 1.33%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 1.33%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 1.33%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 1.33%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 2        | 1.33%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 2        | 1.33%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.67%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.67%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.67%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 0.67%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 0.67%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.67%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.67%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 0.67%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.67%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.67%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.67%   |
| Nvidia GM206GL [Quadro M2000]                                               | 1        | 0.67%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.67%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.67%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.67%   |
| Nvidia GK208 [GeForce GT 635]                                               | 1        | 0.67%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 0.67%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 0.67%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 0.67%   |
| Nvidia GF119 [GeForce GT 625 OEM]                                           | 1        | 0.67%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.67%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 0.67%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 0.67%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 0.67%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 0.67%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 1        | 0.67%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 1        | 0.67%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 1        | 0.67%   |
| Nvidia G73 [GeForce 7600 GS]                                                | 1        | 0.67%   |
| Nvidia G72 [GeForce 7300 LE]                                                | 1        | 0.67%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 1        | 0.67%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 57       | 39.04%  |
| 1 x Intel      | 40       | 27.4%   |
| 1 x AMD        | 39       | 26.71%  |
| 2 x Intel      | 5        | 3.42%   |
| Intel + Nvidia | 3        | 2.05%   |
| 2 x AMD        | 1        | 0.68%   |
| Intel + AMD    | 1        | 0.68%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 93       | 64.14%  |
| Proprietary | 49       | 33.79%  |
| Unknown     | 3        | 2.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 63       | 43.15%  |
| 1.01-2.0   | 20       | 13.7%   |
| 3.01-4.0   | 18       | 12.33%  |
| 0.51-1.0   | 16       | 10.96%  |
| 7.01-8.0   | 14       | 9.59%   |
| 0.01-0.5   | 9        | 6.16%   |
| 5.01-6.0   | 4        | 2.74%   |
| 2.01-3.0   | 1        | 0.68%   |
| 8.01-16.0  | 1        | 0.68%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 19       | 14.73%  |
| Goldstar             | 18       | 13.95%  |
| Dell                 | 15       | 11.63%  |
| AOC                  | 10       | 7.75%   |
| BenQ                 | 9        | 6.98%   |
| Acer                 | 8        | 6.2%    |
| Philips              | 7        | 5.43%   |
| Hewlett-Packard      | 7        | 5.43%   |
| Ancor Communications | 6        | 4.65%   |
| ASUSTek Computer     | 5        | 3.88%   |
| Fujitsu Siemens      | 4        | 3.1%    |
| Sony                 | 3        | 2.33%   |
| Lenovo               | 3        | 2.33%   |
| ViewSonic            | 2        | 1.55%   |
| NEC Computers        | 2        | 1.55%   |
| Iiyama               | 2        | 1.55%   |
| ZL_                  | 1        | 0.78%   |
| Westinghouse         | 1        | 0.78%   |
| Vestel Elektronik    | 1        | 0.78%   |
| SGT                  | 1        | 0.78%   |
| MSI                  | 1        | 0.78%   |
| LTV                  | 1        | 0.78%   |
| GRR                  | 1        | 0.78%   |
| FND                  | 1        | 0.78%   |
| Denver               | 1        | 0.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2        | 1.49%   |
| ASUSTek Computer ROG XG279Q AUS278D 2560x1440 600x340mm 27.2-inch      | 2        | 1.49%   |
| AOC 24G2W1G4 AOC2402 1920x1080 530x300mm 24.0-inch                     | 2        | 1.49%   |
| Ancor Communications MX27AQ ACI27A5 2560x1440 600x340mm 27.2-inch      | 2        | 1.49%   |
| ZL_ zhuoyue-HDMI ZL_2716 2560x1440 600x330mm 27.0-inch                 | 1        | 0.75%   |
| Westinghouse LCM-19w4 WDE1904 1440x900 410x260mm 19.1-inch             | 1        | 0.75%   |
| ViewSonic VX1940w VSC6A20 1680x1050 410x260mm 19.1-inch                | 1        | 0.75%   |
| ViewSonic LCD Monitor VSCBD2B 1920x1080 480x270mm 21.7-inch            | 1        | 0.75%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch     | 1        | 0.75%   |
| Sony TV SNYEE01 1920x1080                                              | 1        | 0.75%   |
| Sony TV SNY9C01 1360x768                                               | 1        | 0.75%   |
| Sony SDM-S75D/F/N SNY3800 1280x1024 340x270mm 17.1-inch                | 1        | 0.75%   |
| SGT YSD SGT1700 1280x1024 380x210mm 17.1-inch                          | 1        | 0.75%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch      | 1        | 0.75%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 520x290mm 23.4-inch      | 1        | 0.75%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                        | 1        | 0.75%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch    | 1        | 0.75%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                       | 1        | 0.75%   |
| Samsung Electronics SyncMaster SAM05B0 1920x1080                       | 1        | 0.75%   |
| Samsung Electronics SyncMaster SAM0373 1680x1050 440x300mm 21.0-inch   | 1        | 0.75%   |
| Samsung Electronics SyncMaster SAM02FA 1440x900 410x260mm 19.1-inch    | 1        | 0.75%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 370x230mm 17.2-inch    | 1        | 0.75%   |
| Samsung Electronics SyncMaster SAM027D 1680x1050 430x270mm 20.0-inch   | 1        | 0.75%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 280x210mm 13.8-inch    | 1        | 0.75%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 480x270mm 21.7-inch     | 1        | 0.75%   |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 440x250mm 19.9-inch   | 1        | 0.75%   |
| Samsung Electronics S24H85x SAM0E0C 2560x1440 530x300mm 24.0-inch      | 1        | 0.75%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch      | 1        | 0.75%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 530x300mm 24.0-inch      | 1        | 0.75%   |
| Samsung Electronics S24C450 SAM09CB 1920x1080 530x300mm 24.0-inch      | 1        | 0.75%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch       | 1        | 0.75%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 1110x620mm 50.1-inch | 1        | 0.75%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 530x300mm 24.0-inch     | 1        | 0.75%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 700x390mm 31.5-inch      | 1        | 0.75%   |
| Samsung Electronics C24FG7x SAM0E44 1920x1080 530x300mm 24.0-inch      | 1        | 0.75%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 1        | 0.75%   |
| Philips PHL 278E1 PHLC217 3840x2160 600x340mm 27.2-inch                | 1        | 0.75%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                 | 1        | 0.75%   |
| Philips LCD Monitor PHLC01A 1680x1050 470x300mm 22.0-inch              | 1        | 0.75%   |
| Philips 248CLH PHLC088 1920x1080 520x290mm 23.4-inch                   | 1        | 0.75%   |
| Philips 22PFL3404D PHLD05D 1920x1080 640x360mm 28.9-inch               | 1        | 0.75%   |
| Philips 220E PHLC02E 1920x1080 470x260mm 21.1-inch                     | 1        | 0.75%   |
| Philips 190V PHL0081 1440x900 400x250mm 18.6-inch                      | 1        | 0.75%   |
| NEC Computers LCD1770VX NEC6696 1280x1024 340x270mm 17.1-inch          | 1        | 0.75%   |
| NEC Computers EA223WM NEC6891 1680x1050 470x300mm 22.0-inch            | 1        | 0.75%   |
| MSI MAG271C MSI3FA6 1920x1080 600x340mm 27.2-inch                      | 1        | 0.75%   |
| LTV LTV1280M1A LTV0A3C 1024x768 800x450mm 36.1-inch                    | 1        | 0.75%   |
| Lenovo LEN T22i-10 LEN61A9 1920x1080 480x270mm 21.7-inch               | 1        | 0.75%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch                | 1        | 0.75%   |
| Lenovo G27q-20 LEN66C3 2560x1440 600x340mm 27.2-inch                   | 1        | 0.75%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch                | 1        | 0.75%   |
| Iiyama PL2390 IVM562D 1920x1080 510x290mm 23.1-inch                    | 1        | 0.75%   |
| Hewlett-Packard Z24n G2 HPN3485 1920x1200 520x320mm 24.0-inch          | 1        | 0.75%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch       | 1        | 0.75%   |
| Hewlett-Packard LCD Monitor HPN351A 1920x1080 700x390mm 31.5-inch      | 1        | 0.75%   |
| Hewlett-Packard LCD Monitor HPN3425 1920x1080 540x300mm 24.3-inch      | 1        | 0.75%   |
| Hewlett-Packard 27f HPN354A 1920x1080 600x340mm 27.2-inch              | 1        | 0.75%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch             | 1        | 0.75%   |
| Hewlett-Packard 23xw HWP318A 1920x1080 510x290mm 23.1-inch             | 1        | 0.75%   |
| GRR GRC GRR2400 1920x1080 520x310mm 23.8-inch                          | 1        | 0.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 58       | 44.96%  |
| 2560x1440 (QHD)    | 13       | 10.08%  |
| 1280x1024 (SXGA)   | 12       | 9.3%    |
| 1440x900 (WXGA+)   | 9        | 6.98%   |
| 1600x900 (HD+)     | 8        | 6.2%    |
| 1680x1050 (WSXGA+) | 6        | 4.65%   |
| 3840x2160 (4K)     | 5        | 3.88%   |
| 1920x1200 (WUXGA)  | 5        | 3.88%   |
| 1366x768 (WXGA)    | 5        | 3.88%   |
| 2560x1080          | 2        | 1.55%   |
| 1024x768 (XGA)     | 2        | 1.55%   |
| 3440x1440          | 1        | 0.78%   |
| 1920x540           | 1        | 0.78%   |
| 1600x1200          | 1        | 0.78%   |
| 1360x768           | 1        | 0.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 26       | 20%     |
| 27      | 18       | 13.85%  |
| 19      | 18       | 13.85%  |
| 21      | 16       | 12.31%  |
| 23      | 13       | 10%     |
| 17      | 8        | 6.15%   |
| 18      | 7        | 5.38%   |
| Unknown | 5        | 3.85%   |
| 31      | 4        | 3.08%   |
| 20      | 3        | 2.31%   |
| 34      | 2        | 1.54%   |
| 22      | 2        | 1.54%   |
| 50      | 1        | 0.77%   |
| 42      | 1        | 0.77%   |
| 36      | 1        | 0.77%   |
| 33      | 1        | 0.77%   |
| 29      | 1        | 0.77%   |
| 28      | 1        | 0.77%   |
| 16      | 1        | 0.77%   |
| 13      | 1        | 0.77%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 53       | 42.06%  |
| 401-500     | 38       | 30.16%  |
| 351-400     | 9        | 7.14%   |
| 601-700     | 7        | 5.56%   |
| 301-350     | 7        | 5.56%   |
| Unknown     | 5        | 3.97%   |
| 701-800     | 4        | 3.17%   |
| 201-300     | 1        | 0.79%   |
| 1001-1500   | 1        | 0.79%   |
| 901-1000    | 1        | 0.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 88       | 70.4%   |
| 16/10 | 20       | 16%     |
| 5/4   | 10       | 8%      |
| 4/3   | 3        | 2.4%    |
| 21/9  | 3        | 2.4%    |
| 3/2   | 1        | 0.8%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 48       | 37.21%  |
| 151-200        | 25       | 19.38%  |
| 301-350        | 18       | 13.95%  |
| 141-150        | 10       | 7.75%   |
| 351-500        | 8        | 6.2%    |
| 251-300        | 8        | 6.2%    |
| Unknown        | 5        | 3.88%   |
| 121-130        | 2        | 1.55%   |
| 501-1000       | 2        | 1.55%   |
| More than 1000 | 1        | 0.78%   |
| 131-140        | 1        | 0.78%   |
| 91-100         | 1        | 0.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 86       | 66.67%  |
| 101-120 | 29       | 22.48%  |
| Unknown | 5        | 3.88%   |
| 121-160 | 4        | 3.1%    |
| 161-240 | 3        | 2.33%   |
| 1-50    | 2        | 1.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 116      | 80.56%  |
| 0     | 15       | 10.42%  |
| 2     | 12       | 8.33%   |
| 3     | 1        | 0.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 87       | 49.15%  |
| Intel                    | 61       | 34.46%  |
| Qualcomm Atheros         | 10       | 5.65%   |
| Broadcom                 | 4        | 2.26%   |
| Marvell Technology Group | 3        | 1.69%   |
| Ralink Technology        | 2        | 1.13%   |
| Ralink                   | 2        | 1.13%   |
| Xiaomi                   | 1        | 0.56%   |
| TP-Link                  | 1        | 0.56%   |
| NetGear                  | 1        | 0.56%   |
| Microchip Technology     | 1        | 0.56%   |
| Mellanox Technologies    | 1        | 0.56%   |
| MediaTek                 | 1        | 0.56%   |
| Edimax Technology        | 1        | 0.56%   |
| D-Link System            | 1        | 0.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 69       | 34.67%  |
| Intel I211 Gigabit Network Connection                             | 12       | 6.03%   |
| Intel Ethernet Connection I217-LM                                 | 8        | 4.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6        | 3.02%   |
| Intel Wi-Fi 6 AX200                                               | 6        | 3.02%   |
| Intel Ethernet Connection (2) I219-LM                             | 6        | 3.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4        | 2.01%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 2.01%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 2.01%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 2.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 2.01%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3        | 1.51%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.51%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 1.51%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.01%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2        | 1.01%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2        | 1.01%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 1.01%   |
| Ralink RT5370 Wireless Adapter                                    | 2        | 1.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 1.01%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.01%   |
| Intel Wireless-AC 9260                                            | 2        | 1.01%   |
| Intel Wireless 7265                                               | 2        | 1.01%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2        | 1.01%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.5%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1        | 0.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 0.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.5%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.5%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.5%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.5%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.5%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1        | 0.5%    |
| Ralink RT2500 Wireless 802.11bg                                   | 1        | 0.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.5%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.5%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.5%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.5%    |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]  | 1        | 0.5%    |
| Microchip HTC Hub Controller                                      | 1        | 0.5%    |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1        | 0.5%    |
| MediaTek 802.11ac Wireless LAN Card                               | 1        | 0.5%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.5%    |
| Intel Wireless 7260                                               | 1        | 0.5%    |
| Intel Wireless 3165                                               | 1        | 0.5%    |
| Intel I210 Gigabit Network Connection                             | 1        | 0.5%    |
| Intel Ethernet Controller I225-V                                  | 1        | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.5%    |
| Intel Ethernet Connection (12) I219-V                             | 1        | 0.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 0.5%    |
| Intel Centrino Wireless-N 2230                                    | 1        | 0.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 0.5%    |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 1        | 0.5%    |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 18       | 38.3%   |
| Intel                 | 16       | 34.04%  |
| Broadcom              | 3        | 6.38%   |
| Ralink Technology     | 2        | 4.26%   |
| Ralink                | 2        | 4.26%   |
| Qualcomm Atheros      | 2        | 4.26%   |
| TP-Link               | 1        | 2.13%   |
| NetGear               | 1        | 2.13%   |
| MediaTek              | 1        | 2.13%   |
| Edimax Technology     | 1        | 2.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                               | 6        | 12.5%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4        | 8.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3        | 6.25%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 2        | 4.17%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2        | 4.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2        | 4.17%   |
| Ralink RT5370 Wireless Adapter                                    | 2        | 4.17%   |
| Intel Wireless-AC 9260                                            | 2        | 4.17%   |
| Intel Wireless 7265                                               | 2        | 4.17%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2        | 4.17%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1        | 2.08%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 2.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1        | 2.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 2.08%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 2.08%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 2.08%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 2.08%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1        | 2.08%   |
| Ralink RT2500 Wireless 802.11bg                                   | 1        | 2.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 2.08%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 2.08%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]  | 1        | 2.08%   |
| MediaTek 802.11ac Wireless LAN Card                               | 1        | 2.08%   |
| Intel Wireless 7260                                               | 1        | 2.08%   |
| Intel Wireless 3165                                               | 1        | 2.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 2.08%   |
| Intel Centrino Wireless-N 2230                                    | 1        | 2.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 2.08%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 1        | 2.08%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU] | 1        | 2.08%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 1        | 2.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 79       | 53.74%  |
| Intel                    | 54       | 36.73%  |
| Qualcomm Atheros         | 8        | 5.44%   |
| Marvell Technology Group | 3        | 2.04%   |
| Xiaomi                   | 1        | 0.68%   |
| D-Link System            | 1        | 0.68%   |
| Broadcom                 | 1        | 0.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 69       | 46.31%  |
| Intel I211 Gigabit Network Connection                                         | 12       | 8.05%   |
| Intel Ethernet Connection I217-LM                                             | 8        | 5.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 6        | 4.03%   |
| Intel Ethernet Connection (2) I219-LM                                         | 6        | 4.03%   |
| Intel Ethernet Connection (7) I219-V                                          | 4        | 2.68%   |
| Intel Ethernet Connection (2) I219-V                                          | 4        | 2.68%   |
| Intel 82579V Gigabit Network Connection                                       | 4        | 2.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4        | 2.68%   |
| Intel 82574L Gigabit Network Connection                                       | 3        | 2.01%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 2.01%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 1.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 1.34%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 2        | 1.34%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1        | 0.67%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.67%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 0.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 0.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 0.67%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1        | 0.67%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 0.67%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.67%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1        | 0.67%   |
| Intel I210 Gigabit Network Connection                                         | 1        | 0.67%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.67%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 0.67%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 0.67%   |
| Intel 82578DM Gigabit Network Connection                                      | 1        | 0.67%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 0.67%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.67%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1        | 0.67%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 1        | 0.67%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 0.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 141      | 75.81%  |
| WiFi     | 43       | 23.12%  |
| Modem    | 1        | 0.54%   |
| Unknown  | 1        | 0.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 133      | 87.5%   |
| WiFi     | 19       | 12.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 100      | 69.93%  |
| 2     | 32       | 22.38%  |
| 3     | 6        | 4.2%    |
| 4     | 3        | 2.1%    |
| 0     | 2        | 1.4%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 138      | 93.88%  |
| Yes  | 9        | 6.12%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 17       | 41.46%  |
| Cambridge Silicon Radio         | 8        | 19.51%  |
| Realtek Semiconductor           | 4        | 9.76%   |
| Apple                           | 3        | 7.32%   |
| Integrated System Solution      | 2        | 4.88%   |
| IMC Networks                    | 2        | 4.88%   |
| ASUSTek Computer                | 2        | 4.88%   |
| TP-Link                         | 1        | 2.44%   |
| Qualcomm Atheros Communications | 1        | 2.44%   |
| HTC (High Tech Computer)        | 1        | 2.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 8        | 19.51%  |
| Intel AX200 Bluetooth                                                | 6        | 14.63%  |
| Intel Bluetooth wireless interface                                   | 4        | 9.76%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 2        | 4.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2        | 4.88%   |
| Intel AX201 Bluetooth                                                | 2        | 4.88%   |
| Apple Apple Broadcom Built-in Bluetooth                              | 2        | 4.88%   |
| TP-Link TP-Link UB500 Adapter                                        | 1        | 2.44%   |
| Realtek  Bluetooth Adapter                                           | 1        | 2.44%   |
| Realtek  Bluetooth 4.0 Adapter                                       | 1        | 2.44%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device          | 1        | 2.44%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 1        | 2.44%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 2.44%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 1        | 2.44%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1        | 2.44%   |
| Integrated System Solution Bluetooth Device                          | 1        | 2.44%   |
| IMC Networks Realtek Bluetooth Adapter                               | 1        | 2.44%   |
| IMC Networks Realtek Bluetooth 4.0 Adapter                           | 1        | 2.44%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 2.44%   |
| ASUS Bluetooth Controller                                            | 1        | 2.44%   |
| ASUS ASUS USB-BT500                                                  | 1        | 2.44%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 1        | 2.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 91       | 38.72%  |
| AMD                         | 58       | 24.68%  |
| Nvidia                      | 56       | 23.83%  |
| C-Media Electronics         | 5        | 2.13%   |
| Texas Instruments           | 3        | 1.28%   |
| Logitech                    | 3        | 1.28%   |
| JMTek                       | 2        | 0.85%   |
| GN Netcom                   | 2        | 0.85%   |
| Focusrite-Novation          | 2        | 0.85%   |
| Yamaha                      | 1        | 0.43%   |
| VIA Technologies            | 1        | 0.43%   |
| SteelSeries ApS             | 1        | 0.43%   |
| Nektar                      | 1        | 0.43%   |
| KORG                        | 1        | 0.43%   |
| Kingston Technology         | 1        | 0.43%   |
| Generalplus Technology      | 1        | 0.43%   |
| FiiO Electronics Technology | 1        | 0.43%   |
| Creative Labs               | 1        | 0.43%   |
| Corsair                     | 1        | 0.43%   |
| Cambridge Silicon Radio     | 1        | 0.43%   |
| ASUSTek Computer            | 1        | 0.43%   |
| Astro Gaming                | 1        | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 16       | 5.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 14       | 5.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 14       | 5.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 13       | 4.78%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 10       | 3.68%   |
| AMD Family 17h/19h HD Audio Controller                                     | 9        | 3.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8        | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8        | 2.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 8        | 2.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 8        | 2.94%   |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 2.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7        | 2.57%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6        | 2.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6        | 2.21%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6        | 2.21%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 2.21%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 1.84%   |
| AMD FCH Azalia Controller                                                  | 5        | 1.84%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 1.47%   |
| AMD Navi 10 HDMI Audio                                                     | 4        | 1.47%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 1.47%   |
| Nvidia MCP61 High Definition Audio                                         | 3        | 1.1%    |
| Nvidia High Definition Audio Controller                                    | 3        | 1.1%    |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 1.1%    |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 1.1%    |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 1.1%    |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 1.1%    |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 1.1%    |
| Nvidia GA104 High Definition Audio Controller                              | 3        | 1.1%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 1.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.1%    |
| Texas Instruments PCM2902 Audio Codec                                      | 2        | 0.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 0.74%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.74%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 0.74%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 0.74%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 0.74%   |
| JMTek USB PnP Audio Device                                                 | 2        | 0.74%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 0.74%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 2        | 0.74%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2        | 0.74%   |
| AMD Trinity HDMI Audio Controller                                          | 2        | 0.74%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2        | 0.74%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 2        | 0.74%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 0.74%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 0.74%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 2        | 0.74%   |
| Yamaha Steinberg UR12                                                      | 1        | 0.37%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 0.37%   |
| Texas Instruments PCM2902C Audio CODEC                                     | 1        | 0.37%   |
| SteelSeries ApS SteelSeries Arctis 5 Arctis 5 Chat Arctis 5 Game           | 1        | 0.37%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.37%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 0.37%   |
| Nvidia MCP65 High Definition Audio                                         | 1        | 0.37%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 0.37%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.37%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.37%   |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 0.37%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 0.37%   |
| Nektar Impact GX61                                                         | 1        | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 36       | 22.36%  |
| Unknown             | 25       | 15.53%  |
| Corsair             | 15       | 9.32%   |
| SK hynix            | 11       | 6.83%   |
| G.Skill             | 11       | 6.83%   |
| Crucial             | 11       | 6.83%   |
| Samsung Electronics | 10       | 6.21%   |
| Micron Technology   | 10       | 6.21%   |
| Team                | 5        | 3.11%   |
| Unknown             | 5        | 3.11%   |
| Patriot             | 3        | 1.86%   |
| A-DATA Technology   | 3        | 1.86%   |
| Transcend           | 2        | 1.24%   |
| Nanya Technology    | 2        | 1.24%   |
| AMD                 | 2        | 1.24%   |
| Unifosa             | 1        | 0.62%   |
| TakeMS              | 1        | 0.62%   |
| Super Talent        | 1        | 0.62%   |
| Strontium           | 1        | 0.62%   |
| Ramaxel Technology  | 1        | 0.62%   |
| Hikvision           | 1        | 0.62%   |
| Goodram             | 1        | 0.62%   |
| Goldkey             | 1        | 0.62%   |
| Elpida              | 1        | 0.62%   |
| Atermiter           | 1        | 0.62%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown                                                | 5        | 2.81%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s   | 3        | 1.69%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 2        | 1.12%   |
| Unknown RAM Module 2GB DIMM DDR2                       | 2        | 1.12%   |
| Unknown RAM Module 2GB DIMM 400MT/s                    | 2        | 1.12%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 2        | 1.12%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 2        | 1.12%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s     | 2        | 1.12%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 2        | 1.12%   |
| Micron RAM 18KSF51272AZ-1G4M1 4GB DIMM DDR3 1333MT/s   | 2        | 1.12%   |
| Kingston RAM Module 1GB DIMM DDR2 667MT/s              | 2        | 1.12%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 2400MT/s    | 2        | 1.12%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s | 2        | 1.12%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s  | 2        | 1.12%   |
| Crucial RAM BL16G32C16U4B.16FE 16GB DIMM DDR4 3200MT/s | 2        | 1.12%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s  | 2        | 1.12%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 2667MT/s  | 2        | 1.12%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 1        | 0.56%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 1        | 0.56%   |
| Unknown RAM Module 512MB DIMM SDRAM                    | 1        | 0.56%   |
| Unknown RAM Module 4GB SODIMM DDR3 800MT/s             | 1        | 0.56%   |
| Unknown RAM Module 4GB DIMM SDRAM                      | 1        | 0.56%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s              | 1        | 0.56%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                   | 1        | 0.56%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM SDRAM 533MT/s              | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s               | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s               | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 1        | 0.56%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s               | 1        | 0.56%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s               | 1        | 0.56%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s      | 1        | 0.56%   |
| Transcend RAM TS128MLQ64V8U 1GB DIMM DDR2 800MT/s      | 1        | 0.56%   |
| Transcend RAM JM1333KLN-2G 2GB DIMM DDR3 1333MT/s      | 1        | 0.56%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s    | 1        | 0.56%   |
| Team RAM TEAMGROUP-UD4-2133 8GB DIMM DDR4 2133MT/s     | 1        | 0.56%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s     | 1        | 0.56%   |
| TakeMS RAM TMS1GB264C081665QI 1GB DIMM DDR2 667MT/s    | 1        | 0.56%   |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s  | 1        | 0.56%   |
| Strontium RAM EVMT2G1333U88S 2GB DIMM DDR3 1333MT/s    | 1        | 0.56%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s           | 1        | 0.56%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s             | 1        | 0.56%   |
| SK hynix RAM HMT451U7BFR8A-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.56%   |
| SK hynix RAM HMT451S6BCFR8A-PB 4GB DIMM DDR3 1600MT/s  | 1        | 0.56%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s   | 1        | 0.56%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s | 1        | 0.56%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s   | 1        | 0.56%   |
| SK hynix RAM HMAA1GU6CJR6N-XN 8GB DIMM DDR4 3200MT/s   | 1        | 0.56%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s   | 1        | 0.56%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2133MT/s   | 1        | 0.56%   |
| SK hynix RAM 8ATF1G64HZ-2G3A1 8GB DIMM DDR4 2400MT/s   | 1        | 0.56%   |
| Samsung RAM Module 4GB SODIMM DDR4 2133MT/s            | 1        | 0.56%   |
| Samsung RAM M471B5273DH0-CH9 4GB DIMM DDR3 1333MT/s    | 1        | 0.56%   |
| Samsung RAM M393B1G70QH0 8GB DIMM DDR3 1333MT/s        | 1        | 0.56%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s    | 1        | 0.56%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 1        | 0.56%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 2666MT/s    | 1        | 0.56%   |
| Samsung RAM M378A5143EB1-CPB 4GB DIMM DDR4 2133MT/s    | 1        | 0.56%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s    | 1        | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 61       | 43.88%  |
| DDR3    | 52       | 37.41%  |
| DDR2    | 10       | 7.19%   |
| Unknown | 10       | 7.19%   |
| SDRAM   | 5        | 3.6%    |
| DDR     | 1        | 0.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 127      | 91.37%  |
| SODIMM | 12       | 8.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 52       | 34.21%  |
| 4096  | 42       | 27.63%  |
| 2048  | 25       | 16.45%  |
| 16384 | 22       | 14.47%  |
| 1024  | 8        | 5.26%   |
| 32768 | 2        | 1.32%   |
| 512   | 1        | 0.66%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 31       | 20.39%  |
| 1333    | 26       | 17.11%  |
| 3200    | 17       | 11.18%  |
| 2133    | 17       | 11.18%  |
| 2400    | 12       | 7.89%   |
| 2667    | 8        | 5.26%   |
| 800     | 7        | 4.61%   |
| Unknown | 7        | 4.61%   |
| 2666    | 6        | 3.95%   |
| 3600    | 4        | 2.63%   |
| 667     | 4        | 2.63%   |
| 1867    | 2        | 1.32%   |
| 1066    | 2        | 1.32%   |
| 400     | 2        | 1.32%   |
| 3733    | 1        | 0.66%   |
| 3400    | 1        | 0.66%   |
| 1866    | 1        | 0.66%   |
| 1200    | 1        | 0.66%   |
| 1067    | 1        | 0.66%   |
| 533     | 1        | 0.66%   |
| 333     | 1        | 0.66%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 1        | 50%     |
| Brother Industries | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                                             | Desktops | Percent |
|-------------------------------------------------------------------------------------------------------------------|----------|---------|
| HP HP LaserJet MFP E52645 LaserJet 0 LaserJet 0 LaserJet 1 LaserJet 1 LaserJet 2 LaserJet 2 LaserJet 3 LaserJet 3 | 1        | 50%     |
| Brother HL-1430 Laser Printer                                                                                     | 1        | 50%     |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 7        | 43.75%  |
| Microdia                | 2        | 12.5%   |
| Z-Star Microelectronics | 1        | 6.25%   |
| IMC Networks            | 1        | 6.25%   |
| Hewlett-Packard         | 1        | 6.25%   |
| Genesys Logic           | 1        | 6.25%   |
| Chicony Electronics     | 1        | 6.25%   |
| Aveo Technology         | 1        | 6.25%   |
| Arkmicro Technologies   | 1        | 6.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Z-Star Lenovo USB2.0 UVC Camera  | 1        | 6.25%   |
| Microdia USB 2.0 Camera          | 1        | 6.25%   |
| Microdia ASUS USB2.0 Webcam      | 1        | 6.25%   |
| Logitech Webcam C930e            | 1        | 6.25%   |
| Logitech Webcam C310             | 1        | 6.25%   |
| Logitech Webcam C270             | 1        | 6.25%   |
| Logitech Webcam C170             | 1        | 6.25%   |
| Logitech C922 Pro Stream Webcam  | 1        | 6.25%   |
| Logitech C670i FHD Webcam        | 1        | 6.25%   |
| Logitech BRIO Ultra HD Webcam    | 1        | 6.25%   |
| IMC Networks XHC Camera          | 1        | 6.25%   |
| HP Realtek PC Camera             | 1        | 6.25%   |
| Genesys Logic Digital Microscope | 1        | 6.25%   |
| Chicony HP 0.3MP Webcam          | 1        | 6.25%   |
| Aveo Camera                      | 1        | 6.25%   |
| Arkmicro USB2.0 PC CAMERA        | 1        | 6.25%   |

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
| 1     | 64       | 44.76%  |
| 0     | 54       | 37.76%  |
| 2     | 20       | 13.99%  |
| 3     | 3        | 2.1%    |
| 4     | 2        | 1.4%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 74       | 66.67%  |
| Net/wireless             | 23       | 20.72%  |
| Sound                    | 6        | 5.41%   |
| Bluetooth                | 4        | 3.6%    |
| Network                  | 2        | 1.8%    |
| Net/ethernet             | 1        | 0.9%    |
| Card reader              | 1        | 0.9%    |

