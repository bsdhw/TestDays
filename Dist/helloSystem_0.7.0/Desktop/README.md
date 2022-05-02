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

Total: 158

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| amd64 | 113      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 112      | 99.12%  |
| GNOME        | 1        | 0.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 113      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 113      | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 108      | 95.58%  |
| es_ES | 2        | 1.77%   |
| fr_FR | 1        | 0.88%   |
| de_DE | 1        | 0.88%   |
| C     | 1        | 0.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 109      | 96.46%  |
| BIOS | 4        | 3.54%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Cd9660 | 72       | 61.54%  |
| Zfs    | 45       | 38.46%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 109      | 96.46%  |
| MBR  | 4        | 3.54%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 36       | 31.86%  |
| Gigabyte Technology | 20       | 17.7%   |
| ASRock              | 12       | 10.62%  |
| Hewlett-Packard     | 9        | 7.96%   |
| Dell                | 9        | 7.96%   |
| MSI                 | 6        | 5.31%   |
| Intel               | 6        | 5.31%   |
| Pegatron            | 3        | 2.65%   |
| Unknown             | 2        | 1.77%   |
| Supermicro          | 1        | 0.88%   |
| Quanta              | 1        | 0.88%   |
| Medion              | 1        | 0.88%   |
| Lenovo              | 1        | 0.88%   |
| Koloe               | 1        | 0.88%   |
| Fujitsu             | 1        | 0.88%   |
| ECS                 | 1        | 0.88%   |
| BESSTAR Tech        | 1        | 0.88%   |
| Apple               | 1        | 0.88%   |
| Acer                | 1        | 0.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| HP EliteDesk 700 G1 SFF             | 2        | 1.77%   |
| ASUS TUF GAMING X570-PLUS           | 2        | 1.77%   |
| ASUS P8Z77-V LX                     | 2        | 1.77%   |
| ASRock X570 Phantom Gaming 4        | 2        | 1.77%   |
| Unknown                             | 2        | 1.77%   |
| Supermicro X9DAL                    | 1        | 0.88%   |
| Quanta 120-1135                     | 1        | 0.88%   |
| Pegatron IPM41-D3                   | 1        | 0.88%   |
| Pegatron Compaq 505B Microtower PC  | 1        | 0.88%   |
| Pegatron AY627AA-ABA a4313w         | 1        | 0.88%   |
| MSI MS-7D25                         | 1        | 0.88%   |
| MSI MS-7B86                         | 1        | 0.88%   |
| MSI MS-7A33                         | 1        | 0.88%   |
| MSI MS-7816                         | 1        | 0.88%   |
| MSI MS-7758                         | 1        | 0.88%   |
| MSI MS-7369                         | 1        | 0.88%   |
| Medion H61H2-LM3                    | 1        | 0.88%   |
| Lenovo IdeaCentre B545 10100        | 1        | 0.88%   |
| Koloe Thurley                       | 1        | 0.88%   |
| Intel X58                           | 1        | 0.88%   |
| Intel H81                           | 1        | 0.88%   |
| Intel H55                           | 1        | 0.88%   |
| Intel DH77EB AAG39073-400           | 1        | 0.88%   |
| Intel DG41TY AAE47335-300           | 1        | 0.88%   |
| Intel DCP847SKE G80890-107          | 1        | 0.88%   |
| HP Z230 Tower Workstation           | 1        | 0.88%   |
| HP ProDesk 600 G2 DM                | 1        | 0.88%   |
| HP Pavilion Gaming Desktop 690-00xx | 1        | 0.88%   |
| HP EliteDesk 800 G2 SFF             | 1        | 0.88%   |
| HP EliteDesk 800 G1 DM              | 1        | 0.88%   |
| HP Compaq dc7800p Small Form Factor | 1        | 0.88%   |
| HP 844C                             | 1        | 0.88%   |
| Gigabyte Z77X-UD3H                  | 1        | 0.88%   |
| Gigabyte Z77N-WIFI                  | 1        | 0.88%   |
| Gigabyte Z390 GAMING X              | 1        | 0.88%   |
| Gigabyte X58A-UD5                   | 1        | 0.88%   |
| Gigabyte X570 AORUS ELITE           | 1        | 0.88%   |
| Gigabyte P41T-D3                    | 1        | 0.88%   |
| Gigabyte OPTIMA B0307               | 1        | 0.88%   |
| Gigabyte H61M-S2PV                  | 1        | 0.88%   |
| Gigabyte H270M-DS3H                 | 1        | 0.88%   |
| Gigabyte H270-Gaming 3              | 1        | 0.88%   |
| Gigabyte H170-D3HP                  | 1        | 0.88%   |
| Gigabyte H110N-CF                   | 1        | 0.88%   |
| Gigabyte G31M-ES2C                  | 1        | 0.88%   |
| Gigabyte E3000N                     | 1        | 0.88%   |
| Gigabyte C246M-WU4                  | 1        | 0.88%   |
| Gigabyte B450M S2H                  | 1        | 0.88%   |
| Gigabyte B450 I AORUS PRO WIFI      | 1        | 0.88%   |
| Gigabyte B450 AORUS M               | 1        | 0.88%   |
| Gigabyte B365 HD3                   | 1        | 0.88%   |
| Gigabyte 970A-DS3P                  | 1        | 0.88%   |
| Fujitsu ESPRIMO E710                | 1        | 0.88%   |
| ECS G41T-M9                         | 1        | 0.88%   |
| Dell Vostro 3667                    | 1        | 0.88%   |
| Dell Precision T1700                | 1        | 0.88%   |
| Dell PowerEdge T20                  | 1        | 0.88%   |
| Dell OptiPlex 990                   | 1        | 0.88%   |
| Dell OptiPlex 9020                  | 1        | 0.88%   |
| Dell OptiPlex 9010                  | 1        | 0.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 8        | 7.08%   |
| Dell OptiPlex        | 5        | 4.42%   |
| ASUS ROG             | 5        | 4.42%   |
| HP EliteDesk         | 4        | 3.54%   |
| ASUS TUF             | 3        | 2.65%   |
| Gigabyte B450        | 2        | 1.77%   |
| ASUS P8Z77-V         | 2        | 1.77%   |
| ASRock X570          | 2        | 1.77%   |
| Unknown              | 2        | 1.77%   |
| Supermicro X9DAL     | 1        | 0.88%   |
| Quanta 120-1135      | 1        | 0.88%   |
| Pegatron IPM41-D3    | 1        | 0.88%   |
| Pegatron Compaq      | 1        | 0.88%   |
| Pegatron AY627AA-ABA | 1        | 0.88%   |
| MSI MS-7D25          | 1        | 0.88%   |
| MSI MS-7B86          | 1        | 0.88%   |
| MSI MS-7A33          | 1        | 0.88%   |
| MSI MS-7816          | 1        | 0.88%   |
| MSI MS-7758          | 1        | 0.88%   |
| MSI MS-7369          | 1        | 0.88%   |
| Medion H61H2-LM3     | 1        | 0.88%   |
| Lenovo IdeaCentre    | 1        | 0.88%   |
| Koloe Thurley        | 1        | 0.88%   |
| Intel X58            | 1        | 0.88%   |
| Intel H81            | 1        | 0.88%   |
| Intel H55            | 1        | 0.88%   |
| Intel DH77EB         | 1        | 0.88%   |
| Intel DG41TY         | 1        | 0.88%   |
| Intel DCP847SKE      | 1        | 0.88%   |
| HP Z230              | 1        | 0.88%   |
| HP ProDesk           | 1        | 0.88%   |
| HP Pavilion          | 1        | 0.88%   |
| HP Compaq            | 1        | 0.88%   |
| HP 844C              | 1        | 0.88%   |
| Gigabyte Z77X-UD3H   | 1        | 0.88%   |
| Gigabyte Z77N-WIFI   | 1        | 0.88%   |
| Gigabyte Z390        | 1        | 0.88%   |
| Gigabyte X58A-UD5    | 1        | 0.88%   |
| Gigabyte X570        | 1        | 0.88%   |
| Gigabyte P41T-D3     | 1        | 0.88%   |
| Gigabyte OPTIMA      | 1        | 0.88%   |
| Gigabyte H61M-S2PV   | 1        | 0.88%   |
| Gigabyte H270M-DS3H  | 1        | 0.88%   |
| Gigabyte H270-Gaming | 1        | 0.88%   |
| Gigabyte H170-D3HP   | 1        | 0.88%   |
| Gigabyte H110N-CF    | 1        | 0.88%   |
| Gigabyte G31M-ES2C   | 1        | 0.88%   |
| Gigabyte E3000N      | 1        | 0.88%   |
| Gigabyte C246M-WU4   | 1        | 0.88%   |
| Gigabyte B450M       | 1        | 0.88%   |
| Gigabyte B365        | 1        | 0.88%   |
| Gigabyte 970A-DS3P   | 1        | 0.88%   |
| Fujitsu ESPRIMO      | 1        | 0.88%   |
| ECS G41T-M9          | 1        | 0.88%   |
| Dell Vostro          | 1        | 0.88%   |
| Dell Precision       | 1        | 0.88%   |
| Dell PowerEdge       | 1        | 0.88%   |
| Dell Inspiron        | 1        | 0.88%   |
| BESSTAR Tech UM250   | 1        | 0.88%   |
| ASUS Z170-P          | 1        | 0.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 18       | 15.93%  |
| 2021 | 15       | 13.27%  |
| 2018 | 10       | 8.85%   |
| 2012 | 10       | 8.85%   |
| 2010 | 9        | 7.96%   |
| 2016 | 8        | 7.08%   |
| 2014 | 8        | 7.08%   |
| 2013 | 8        | 7.08%   |
| 2017 | 7        | 6.19%   |
| 2009 | 5        | 4.42%   |
| 2020 | 4        | 3.54%   |
| 2011 | 4        | 3.54%   |
| 2015 | 3        | 2.65%   |
| 2007 | 3        | 2.65%   |
| 2008 | 1        | 0.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 113      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 113      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 31       | 27.43%  |
| 8.01-16.0   | 29       | 25.66%  |
| 4.01-8.0    | 20       | 17.7%   |
| 32.01-64.0  | 19       | 16.81%  |
| 64.01-256.0 | 6        | 5.31%   |
| 24.01-32.0  | 3        | 2.65%   |
| 2.01-3.0    | 3        | 2.65%   |
| 1.01-2.0    | 1        | 0.88%   |
| 0.51-1.0    | 1        | 0.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 45       | 39.47%  |
| 0.51-1.0  | 36       | 31.58%  |
| 1.01-2.0  | 28       | 24.56%  |
| 2.01-3.0  | 3        | 2.63%   |
| 3.01-4.0  | 1        | 0.88%   |
| 8.01-16.0 | 1        | 0.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 48       | 41.74%  |
| 2      | 32       | 27.83%  |
| 4      | 11       | 9.57%   |
| 3      | 10       | 8.7%    |
| 0      | 6        | 5.22%   |
| 5      | 4        | 3.48%   |
| 6      | 2        | 1.74%   |
| 9      | 1        | 0.87%   |
| 7      | 1        | 0.87%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 76       | 67.26%  |
| Yes       | 37       | 32.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 111      | 98.23%  |
| No        | 2        | 1.77%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 78       | 69.03%  |
| Yes       | 35       | 30.97%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 79       | 69.91%  |
| Yes       | 34       | 30.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 19       | 16.81%  |
| Russia      | 17       | 15.04%  |
| Hungary     | 7        | 6.19%   |
| Ukraine     | 6        | 5.31%   |
| Spain       | 6        | 5.31%   |
| Germany     | 6        | 5.31%   |
| Poland      | 5        | 4.42%   |
| Brazil      | 5        | 4.42%   |
| Italy       | 4        | 3.54%   |
| India       | 4        | 3.54%   |
| Canada      | 4        | 3.54%   |
| France      | 3        | 2.65%   |
| China       | 3        | 2.65%   |
| UK          | 2        | 1.77%   |
| Turkey      | 2        | 1.77%   |
| South Korea | 2        | 1.77%   |
| Romania     | 2        | 1.77%   |
| Australia   | 2        | 1.77%   |
| Vietnam     | 1        | 0.88%   |
| Thailand    | 1        | 0.88%   |
| Taiwan      | 1        | 0.88%   |
| Portugal    | 1        | 0.88%   |
| Philippines | 1        | 0.88%   |
| Peru        | 1        | 0.88%   |
| Panama      | 1        | 0.88%   |
| Norway      | 1        | 0.88%   |
| Kazakhstan  | 1        | 0.88%   |
| Iceland     | 1        | 0.88%   |
| Greece      | 1        | 0.88%   |
| Finland     | 1        | 0.88%   |
| Denmark     | 1        | 0.88%   |
| Argentina   | 1        | 0.88%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                          | Desktops | Percent |
|-------------------------------|----------|---------|
| St Petersburg                 | 4        | 3.39%   |
| Surgut                        | 2        | 1.69%   |
| Myrtle Beach                  | 2        | 1.69%   |
| Kharkiv                       | 2        | 1.69%   |
| Curitiba                      | 2        | 1.69%   |
| Castilleja de la Cuesta       | 2        | 1.69%   |
| Barnaul                       | 2        | 1.69%   |
| Yunlin                        | 1        | 0.85%   |
| Warsaw                        | 1        | 0.85%   |
| Tiruchi                       | 1        | 0.85%   |
| Tampa                         | 1        | 0.85%   |
| Szombathely                   | 1        | 0.85%   |
| Szeged                        | 1        | 0.85%   |
| SzÃ©kesfehÃ©rvÃ¡r       | 1        | 0.85%   |
| Suceava                       | 1        | 0.85%   |
| Stavropol                     | 1        | 0.85%   |
| Sparta                        | 1        | 0.85%   |
| Spalice                       | 1        | 0.85%   |
| Sopron                        | 1        | 0.85%   |
| Songpa-gu                     | 1        | 0.85%   |
| Smiths Falls                  | 1        | 0.85%   |
| Seville                       | 1        | 0.85%   |
| Santa Maria                   | 1        | 0.85%   |
| San SebastiÃ¡n de los Reyes | 1        | 0.85%   |
| Rio de Janeiro                | 1        | 0.85%   |
| Reykjavik                     | 1        | 0.85%   |
| Renfrew                       | 1        | 0.85%   |
| Pilica                        | 1        | 0.85%   |
| Pforzheim                     | 1        | 0.85%   |
| Pflugerville                  | 1        | 0.85%   |
| Perm                          | 1        | 0.85%   |
| Penza                         | 1        | 0.85%   |
| Paso Robles                   | 1        | 0.85%   |
| Panama City                   | 1        | 0.85%   |
| Paju                          | 1        | 0.85%   |
| Ourense                       | 1        | 0.85%   |
| Ormond Beach                  | 1        | 0.85%   |
| Novosibirsk                   | 1        | 0.85%   |
| New Delhi                     | 1        | 0.85%   |
| Myski                         | 1        | 0.85%   |
| Moscow                        | 1        | 0.85%   |
| Montreal                      | 1        | 0.85%   |
| Midlothian                    | 1        | 0.85%   |
| Melbourne                     | 1        | 0.85%   |
| Malonikolayevka               | 1        | 0.85%   |
| Maglod                        | 1        | 0.85%   |
| Luton                         | 1        | 0.85%   |
| Lima                          | 1        | 0.85%   |
| Lehrte                        | 1        | 0.85%   |
| Kyiv                          | 1        | 0.85%   |
| Kremenchug                    | 1        | 0.85%   |
| Kozani                        | 1        | 0.85%   |
| Kostroma                      | 1        | 0.85%   |
| Kiselëvsk                    | 1        | 0.85%   |
| Katowice                      | 1        | 0.85%   |
| Junction City                 | 1        | 0.85%   |
| Jelenia Góra                 | 1        | 0.85%   |
| Jelenia GÃ³ra               | 1        | 0.85%   |
| Istanbul                      | 1        | 0.85%   |
| Independence                  | 1        | 0.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 39       | 56     | 20%     |
| WDC                 | 34       | 50     | 17.44%  |
| Samsung Electronics | 30       | 36     | 15.38%  |
| Toshiba             | 15       | 18     | 7.69%   |
| Crucial             | 13       | 19     | 6.67%   |
| Kingston            | 11       | 14     | 5.64%   |
| A-DATA Technology   | 7        | 8      | 3.59%   |
| SK Hynix            | 4        | 6      | 2.05%   |
| SanDisk             | 4        | 4      | 2.05%   |
| Phison              | 4        | 4      | 2.05%   |
| Hitachi             | 4        | 5      | 2.05%   |
| GOODRAM             | 4        | 4      | 2.05%   |
| Patriot             | 3        | 3      | 1.54%   |
| Intel               | 3        | 3      | 1.54%   |
| HGST                | 3        | 3      | 1.54%   |
| XPG                 | 2        | 2      | 1.03%   |
| PNY                 | 2        | 2      | 1.03%   |
| OCZ                 | 2        | 2      | 1.03%   |
| Gigabyte Technology | 2        | 3      | 1.03%   |
| SPCC                | 1        | 1      | 0.51%   |
| PLEXTOR             | 1        | 1      | 0.51%   |
| Mushkin             | 1        | 1      | 0.51%   |
| LITEON              | 1        | 1      | 0.51%   |
| Lite-On             | 1        | 1      | 0.51%   |
| KingSpec            | 1        | 1      | 0.51%   |
| Intenso             | 1        | 1      | 0.51%   |
| EMTEC               | 1        | 1      | 0.51%   |
| Apacer              | 1        | 1      | 0.51%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB          | 4        | 1.8%    |
| Kingston SA400S37120G 120GB             | 4        | 1.8%    |
| Toshiba HDWD110 1TB                     | 3        | 1.35%   |
| Seagate ST4000DM004-2CV104 4TB          | 3        | 1.35%   |
| Seagate ST2000DM008-2FR102 2TB          | 3        | 1.35%   |
| Seagate ST1000DM003-1ER162 1TB          | 3        | 1.35%   |
| Samsung SSD 850 EVO 250GB               | 3        | 1.35%   |
| Crucial CT500MX500SSD1 500GB            | 3        | 1.35%   |
| XPG GAMMIX S11 Pro 256GB                | 2        | 0.9%    |
| WDC WDS240G2G0A-00JH30 240GB            | 2        | 0.9%    |
| WDC WDS100T2B0C-00PXH0 1TB              | 2        | 0.9%    |
| WDC WD5000LPVX-22V0TT0 500GB            | 2        | 0.9%    |
| WDC WD20PURZ-85GU6Y0 2TB                | 2        | 0.9%    |
| Toshiba DT01ACA050 500GB                | 2        | 0.9%    |
| SK Hynix BC501 HFM128GDJTNG-8310A 128GB | 2        | 0.9%    |
| Seagate ST3500418AS 500GB               | 2        | 0.9%    |
| Seagate ST3500413AS 500GB               | 2        | 0.9%    |
| Seagate ST3320418AS 320GB               | 2        | 0.9%    |
| Seagate ST31000528AS 1TB                | 2        | 0.9%    |
| SanDisk SDSSDA120G 120GB                | 2        | 0.9%    |
| Samsung SSD 980 PRO 1TB                 | 2        | 0.9%    |
| Samsung SSD 970 EVO Plus 1TB            | 2        | 0.9%    |
| Samsung SSD 970 EVO 250GB               | 2        | 0.9%    |
| Samsung SSD 860 EVO 500GB               | 2        | 0.9%    |
| Samsung SSD 860 EVO 250GB               | 2        | 0.9%    |
| Samsung HD322HJ 320GB                   | 2        | 0.9%    |
| GOODRAM SSDPR-CL100-120-G2 120GB        | 2        | 0.9%    |
| Crucial CT256MX100SSD1 256GB            | 2        | 0.9%    |
| Crucial CT240BX500SSD1 240GB            | 2        | 0.9%    |
| Crucial CT120BX500SSD1 120GB            | 2        | 0.9%    |
| WDC WDS500G2B0C-00PXH0 500GB            | 1        | 0.45%   |
| WDC WDS500G2B0B-00YS70 500GB            | 1        | 0.45%   |
| WDC WDS500G2B0A-00SM50 500GB            | 1        | 0.45%   |
| WDC WDS250G1B0A-00H9H0 250GB            | 1        | 0.45%   |
| WDC WDS200T2B0C-00PXH0 2TB              | 1        | 0.45%   |
| WDC WDS120G2G0A-00JH30 120GB            | 1        | 0.45%   |
| WDC WDS100T2B0A-00SM50 1TB              | 1        | 0.45%   |
| WDC WDBA3V0010BNC-WRSN 1TB              | 1        | 0.45%   |
| WDC WD60EZRZ-00RWYB1 6TB                | 1        | 0.45%   |
| WDC WD5000LPLX-66ZNTT0 500GB            | 1        | 0.45%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1        | 0.45%   |
| WDC WD5000AZLX-00CL5A0 500GB            | 1        | 0.45%   |
| WDC WD5000AAKX-75U6AA0 500GB            | 1        | 0.45%   |
| WDC WD5000AAKS-22A7B0 500GB             | 1        | 0.45%   |
| WDC WD40EZRZ-00GXCB0 4TB                | 1        | 0.45%   |
| WDC WD40EFRX-68N32N0 4TB                | 1        | 0.45%   |
| WDC WD400JB-00ENA0 40GB                 | 1        | 0.45%   |
| WDC WD4004FZWX-00GBGB0 4TB              | 1        | 0.45%   |
| WDC WD3200BPVT-22ZEST0 320GB            | 1        | 0.45%   |
| WDC WD3200AAJS-22B4A0 320GB             | 1        | 0.45%   |
| WDC WD3200AAJS-00YZCA0 320GB            | 1        | 0.45%   |
| WDC WD3003FZEX-00Z4SA0 3TB              | 1        | 0.45%   |
| WDC WD2500AAKX-75U6AA0 250GB            | 1        | 0.45%   |
| WDC WD2500AAKX-073CA1 250GB             | 1        | 0.45%   |
| WDC WD1600BEVT-75ZCT2 160GB             | 1        | 0.45%   |
| WDC WD1600BEVT-22ZCT0 160GB             | 1        | 0.45%   |
| WDC WD10EZEX-60ZF5A0 1TB                | 1        | 0.45%   |
| WDC WD10EZEX-60WN4A0 1TB                | 1        | 0.45%   |
| WDC WD10EZEX-08M2NA0 1TB                | 1        | 0.45%   |
| WDC WD10EZEX-00KUWA0 1TB                | 1        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 39       | 53     | 42.86%  |
| WDC                 | 25       | 31     | 27.47%  |
| Toshiba             | 14       | 17     | 15.38%  |
| Samsung Electronics | 6        | 6      | 6.59%   |
| Hitachi             | 4        | 5      | 4.4%    |
| HGST                | 3        | 3      | 3.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 17       | 18     | 21.25%  |
| Crucial             | 13       | 18     | 16.25%  |
| Kingston            | 9        | 11     | 11.25%  |
| WDC                 | 6        | 10     | 7.5%    |
| A-DATA Technology   | 6        | 6      | 7.5%    |
| SanDisk             | 4        | 4      | 5%      |
| GOODRAM             | 4        | 4      | 5%      |
| Patriot             | 3        | 3      | 3.75%   |
| PNY                 | 2        | 2      | 2.5%    |
| OCZ                 | 2        | 2      | 2.5%    |
| Intel               | 2        | 2      | 2.5%    |
| Gigabyte Technology | 2        | 3      | 2.5%    |
| Toshiba             | 1        | 1      | 1.25%   |
| SPCC                | 1        | 1      | 1.25%   |
| SK Hynix            | 1        | 1      | 1.25%   |
| PLEXTOR             | 1        | 1      | 1.25%   |
| LITEON              | 1        | 1      | 1.25%   |
| Lite-On             | 1        | 1      | 1.25%   |
| KingSpec            | 1        | 1      | 1.25%   |
| Intenso             | 1        | 1      | 1.25%   |
| EMTEC               | 1        | 1      | 1.25%   |
| Apacer              | 1        | 1      | 1.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 73       | 115    | 44.51%  |
| SSD  | 63       | 93     | 38.41%  |
| NVMe | 28       | 43     | 17.07%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 101      | 208    | 78.29%  |
| NVMe | 28       | 43     | 21.71%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 87       | 134    | 60.84%  |
| 0.51-1.0   | 26       | 34     | 18.18%  |
| 1.01-2.0   | 14       | 15     | 9.79%   |
| 3.01-4.0   | 9        | 16     | 6.29%   |
| 2.01-3.0   | 4        | 5      | 2.8%    |
| 4.01-10.0  | 2        | 3      | 1.4%    |
| 10.01-20.0 | 1        | 1      | 0.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 70       | 59.83%  |
| 101-250    | 26       | 22.22%  |
| 251-500    | 12       | 10.26%  |
| 501-1000   | 5        | 4.27%   |
| 51-100     | 3        | 2.56%   |
| 21-50      | 1        | 0.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 112      | 99.12%  |
| 21-50   | 1        | 0.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST3500413AS 500GB           | 2        | 3      | 5.88%   |
| Seagate ST3320418AS 320GB           | 2        | 2      | 5.88%   |
| Seagate ST31000528AS 1TB            | 2        | 3      | 5.88%   |
| WDC WD60EZRZ-00RWYB1 6TB            | 1        | 1      | 2.94%   |
| WDC WD5000AZLX-00CL5A0 500GB        | 1        | 1      | 2.94%   |
| WDC WD5000AAKS-22A7B0 500GB         | 1        | 1      | 2.94%   |
| WDC WD400JB-00ENA0 40GB             | 1        | 1      | 2.94%   |
| WDC WD3200AAJS-22B4A0 320GB         | 1        | 1      | 2.94%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 1        | 1      | 2.94%   |
| WDC WD10EZEX-08M2NA0 1TB            | 1        | 1      | 2.94%   |
| WDC WD10EARS-003BB1 1TB             | 1        | 1      | 2.94%   |
| Toshiba MD04ACA400 4TB              | 1        | 1      | 2.94%   |
| Toshiba DT01ACA100 1TB              | 1        | 3      | 2.94%   |
| Toshiba DT01ABA300 3TB              | 1        | 1      | 2.94%   |
| Seagate ST8000NM0055-1RM112 8TB     | 1        | 1      | 2.94%   |
| Seagate ST380211AS 80GB             | 1        | 1      | 2.94%   |
| Seagate ST3500418AS 500GB           | 1        | 1      | 2.94%   |
| Seagate ST3250310AS 250GB           | 1        | 1      | 2.94%   |
| Seagate ST3160812AS 160GB           | 1        | 1      | 2.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1        | 1      | 2.94%   |
| Seagate ST1000DM003-1ER162 1TB      | 1        | 1      | 2.94%   |
| Samsung Electronics SSD 870 EVO 1TB | 1        | 1      | 2.94%   |
| Samsung Electronics HD322HJ 320GB   | 1        | 1      | 2.94%   |
| Samsung Electronics HD250HJ 250GB   | 1        | 1      | 2.94%   |
| Kingston SV200S3128G 128GB          | 1        | 1      | 2.94%   |
| Kingston SMS200S3120G 120GB         | 1        | 1      | 2.94%   |
| Hitachi HTS541680J9SA00 80GB        | 1        | 2      | 2.94%   |
| Hitachi HDT721010SLA360 1TB         | 1        | 1      | 2.94%   |
| Crucial CT240M500SSD1 240GB         | 1        | 1      | 2.94%   |
| Crucial CT1050MX300SSD1 1TB         | 1        | 1      | 2.94%   |
| A-DATA Technology SX8200PNP 512GB   | 1        | 1      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 15     | 37.5%   |
| WDC                 | 8        | 8      | 25%     |
| Samsung Electronics | 3        | 3      | 9.38%   |
| Toshiba             | 2        | 5      | 6.25%   |
| Kingston            | 2        | 2      | 6.25%   |
| Hitachi             | 2        | 3      | 6.25%   |
| Crucial             | 2        | 2      | 6.25%   |
| A-DATA Technology   | 1        | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 15     | 46.15%  |
| WDC                 | 8        | 8      | 30.77%  |
| Toshiba             | 2        | 5      | 7.69%   |
| Samsung Electronics | 2        | 2      | 7.69%   |
| Hitachi             | 2        | 3      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 23       | 33     | 79.31%  |
| SSD  | 5        | 5      | 17.24%  |
| NVMe | 1        | 1      | 3.45%   |

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
| Works    | 96       | 210    | 76.8%   |
| Malfunc  | 27       | 39     | 21.6%   |
| Detected | 1        | 1      | 0.8%    |
| Failed   | 1        | 1      | 0.8%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 76       | 49.35%  |
| AMD                         | 32       | 20.78%  |
| Samsung Electronics         | 10       | 6.49%   |
| Sandisk                     | 5        | 3.25%   |
| Phison Electronics          | 4        | 2.6%    |
| SK Hynix                    | 3        | 1.95%   |
| Nvidia                      | 3        | 1.95%   |
| Marvell Technology Group    | 3        | 1.95%   |
| JMicron Technology          | 3        | 1.95%   |
| ASMedia Technology          | 3        | 1.95%   |
| ADATA Technology            | 3        | 1.95%   |
| Kingston Technology Company | 2        | 1.3%    |
| Broadcom / LSI              | 2        | 1.3%    |
| VIA Technologies            | 1        | 0.65%   |
| Silicon Motion              | 1        | 0.65%   |
| Seagate Technology          | 1        | 0.65%   |
| Realtek Semiconductor       | 1        | 0.65%   |
| Micron/Crucial Technology   | 1        | 0.65%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 25       | 13.59%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10       | 5.43%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 9        | 4.89%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 4.35%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 4.35%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 3.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 3.26%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 3.26%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 3.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6        | 3.26%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 3.26%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 4        | 2.17%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 4        | 2.17%   |
| Phison E12 NVMe Controller                                                              | 3        | 1.63%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 1.63%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 1.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 1.63%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 1.63%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 2        | 1.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 1.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 1.09%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 1.09%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 1.09%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 1.09%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 1.09%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 1.09%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.09%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.09%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 1.09%   |
| Unknown                                                                                 | 2        | 1.09%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.54%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 1        | 0.54%   |
| SK Hynix Gold P31 SSD                                                                   | 1        | 0.54%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.54%   |
| Seagate FireCuda 520 SSD                                                                | 1        | 0.54%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.54%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.54%   |
| Nvidia MCP65 AHCI Controller                                                            | 1        | 0.54%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.54%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1        | 0.54%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1        | 0.54%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.54%   |
| JMicron JMB361 AHCI/IDE                                                                 | 1        | 0.54%   |
| Intel SSD 660P Series                                                                   | 1        | 0.54%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 0.54%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 0.54%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 0.54%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 1        | 0.54%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 1        | 0.54%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 1        | 0.54%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 0.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 1        | 0.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1        | 0.54%   |
| Intel 82801HB (ICH8) 4 port SATA Controller [AHCI mode]                                 | 1        | 0.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 1        | 0.54%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 0.54%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 0.54%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 86       | 58.5%   |
| NVMe | 28       | 19.05%  |
| IDE  | 23       | 15.65%  |
| RAID | 8        | 5.44%   |
| SAS  | 1        | 0.68%   |
| SCSI | 1        | 0.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 77       | 68.14%  |
| AMD    | 36       | 31.86%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 2.65%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 2.65%   |
| Intel Pentium CPU G860 @ 3.00GHz            | 2        | 1.77%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 1.77%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 1.77%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 1.77%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 2        | 1.77%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 1.77%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 2        | 1.77%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 1.77%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 1.77%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 1.77%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.77%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2        | 1.77%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 1.77%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 1.77%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 1.77%   |
| Intel Xeon E-2136 CPU @ 3.30GHz             | 1        | 0.88%   |
| Intel Xeon CPU X5647 @ 2.93GHz              | 1        | 0.88%   |
| Intel Xeon CPU X3470 @ 2.93GHz              | 1        | 0.88%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 0.88%   |
| Intel Xeon CPU E5504 @ 2.00GHz              | 1        | 0.88%   |
| Intel Xeon CPU E5-2403 v2 @ 1.80GHz         | 1        | 0.88%   |
| Intel Xeon CPU E31245 @ 3.30GHz             | 1        | 0.88%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz         | 1        | 0.88%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz        | 1        | 0.88%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1        | 0.88%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 0.88%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1        | 0.88%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1        | 0.88%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 1        | 0.88%   |
| Intel Pentium Dual-Core CPU E6500 @         | 1        | 0.88%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.88%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.88%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1        | 0.88%   |
| Intel Core i9-9900 CPU @ 3.10GHz            | 1        | 0.88%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 0.88%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.88%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.88%   |
| Intel Core i7-6700T CPU @ 2.80GHz           | 1        | 0.88%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.88%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 0.88%   |
| Intel Core i7 CPU                           | 1        | 0.88%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 0.88%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.88%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 0.88%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 0.88%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 0.88%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 0.88%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 0.88%   |
| Intel Core i5-3475S CPU @ 2.90GHz           | 1        | 0.88%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 0.88%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 0.88%   |
| Intel Core i5-2405S CPU @ 2.50GHz           | 1        | 0.88%   |
| Intel Core i5-2400S CPU @ 2.50GH            | 1        | 0.88%   |
| Intel Core i5-10500 CPU @ 3.10GHz           | 1        | 0.88%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 0.88%   |
| Intel Core i3-6320 CPU @ 3.90GHz            | 1        | 0.88%   |
| Intel Core i3-6300 CPU @ 3.80GHz            | 1        | 0.88%   |
| Intel Core i3-5010U CPU @ 2.10GHz           | 1        | 0.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 23       | 20.35%  |
| Intel Xeon              | 12       | 10.62%  |
| Intel Core i7           | 12       | 10.62%  |
| AMD Ryzen 5             | 9        | 7.96%   |
| AMD Ryzen 7             | 8        | 7.08%   |
| Intel Core i3           | 6        | 5.31%   |
| Intel Core 2 Quad       | 5        | 4.42%   |
| Intel Pentium Dual-Core | 4        | 3.54%   |
| Intel Core 2 Duo        | 4        | 3.54%   |
| AMD Ryzen 9             | 4        | 3.54%   |
| Intel Pentium           | 3        | 2.65%   |
| Other                   | 2        | 1.77%   |
| Intel Celeron           | 2        | 1.77%   |
| AMD Ryzen Threadripper  | 2        | 1.77%   |
| AMD Ryzen 3             | 2        | 1.77%   |
| AMD Phenom II X4        | 2        | 1.77%   |
| AMD FX                  | 2        | 1.77%   |
| Intel Pentium Dual      | 1        | 0.88%   |
| Intel Core i9           | 1        | 0.88%   |
| Intel Core 2            | 1        | 0.88%   |
| Intel Atom              | 1        | 0.88%   |
| AMD Ryzen 5 PRO         | 1        | 0.88%   |
| AMD E2                  | 1        | 0.88%   |
| AMD E                   | 1        | 0.88%   |
| AMD Athlon II X4        | 1        | 0.88%   |
| AMD Athlon II X2        | 1        | 0.88%   |
| AMD Athlon Dual Core    | 1        | 0.88%   |
| AMD A10                 | 1        | 0.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 44       | 38.94%  |
| 2       | 22       | 19.47%  |
| 6       | 11       | 9.73%   |
| 8       | 9        | 7.96%   |
| 16      | 7        | 6.19%   |
| Unknown | 7        | 6.19%   |
| 12      | 6        | 5.31%   |
| 24      | 3        | 2.65%   |
| 64      | 1        | 0.88%   |
| 48      | 1        | 0.88%   |
| 32      | 1        | 0.88%   |
| 14      | 1        | 0.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 112      | 99.12%  |
| 2      | 1        | 0.88%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 74       | 65.49%  |
| 2       | 32       | 28.32%  |
| Unknown | 7        | 6.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 12       | 10.62%  |
| Skylake     | 11       | 9.73%   |
| Penryn      | 10       | 8.85%   |
| KabyLake    | 10       | 8.85%   |
| IvyBridge   | 10       | 8.85%   |
| Zen 2       | 9        | 7.96%   |
| SandyBridge | 8        | 7.08%   |
| Zen+        | 6        | 5.31%   |
| Zen         | 6        | 5.31%   |
| Zen 3       | 5        | 4.42%   |
| Core        | 5        | 4.42%   |
| K10         | 4        | 3.54%   |
| Westmere    | 3        | 2.65%   |
| Piledriver  | 3        | 2.65%   |
| Nehalem     | 3        | 2.65%   |
| Unknown     | 2        | 1.77%   |
| K8 Hammer   | 1        | 0.88%   |
| Jaguar      | 1        | 0.88%   |
| CometLake   | 1        | 0.88%   |
| Broadwell   | 1        | 0.88%   |
| Bonnell     | 1        | 0.88%   |
| Bobcat      | 1        | 0.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 45       | 38.46%  |
| Intel  | 40       | 34.19%  |
| AMD    | 32       | 27.35%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 5.93%   |
| Intel HD Graphics 530                                                       | 7        | 5.93%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 5.93%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 3.39%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 2.54%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 2.54%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 2.54%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 2.54%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 2.54%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 2.54%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 2.54%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 2.54%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.69%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 1.69%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 1.69%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.69%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 1.69%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 2        | 1.69%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 1.69%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 1.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1.69%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 1.69%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 2        | 1.69%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.85%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.85%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 0.85%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.85%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.85%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 0.85%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.85%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.85%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.85%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 0.85%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 0.85%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 0.85%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 0.85%   |
| Nvidia GF119 [GeForce GT 625 OEM]                                           | 1        | 0.85%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.85%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 0.85%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 0.85%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 0.85%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 0.85%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 0.85%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 1        | 0.85%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 1        | 0.85%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 1        | 0.85%   |
| Nvidia G72 [GeForce 7300 LE]                                                | 1        | 0.85%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 1        | 0.85%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 0.85%   |
| Intel HD Graphics 630                                                       | 1        | 0.85%   |
| Intel HD Graphics 5500                                                      | 1        | 0.85%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 0.85%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 0.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 0.85%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 1        | 0.85%   |
| Intel AlderLake-S GT1                                                       | 1        | 0.85%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1        | 0.85%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 0.85%   |
| AMD Wrestler [Radeon HD 6320]                                               | 1        | 0.85%   |
| AMD Trinity [Radeon HD 7660D]                                               | 1        | 0.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 44       | 38.26%  |
| 1 x Intel      | 34       | 29.57%  |
| 1 x AMD        | 30       | 26.09%  |
| 2 x Intel      | 3        | 2.61%   |
| Intel + Nvidia | 2        | 1.74%   |
| 2 x AMD        | 1        | 0.87%   |
| Intel + AMD    | 1        | 0.87%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 74       | 64.91%  |
| Proprietary | 37       | 32.46%  |
| Unknown     | 3        | 2.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 52       | 45.22%  |
| 3.01-4.0   | 15       | 13.04%  |
| 1.01-2.0   | 13       | 11.3%   |
| 0.51-1.0   | 13       | 11.3%   |
| 7.01-8.0   | 10       | 8.7%    |
| 0.01-0.5   | 8        | 6.96%   |
| 5.01-6.0   | 4        | 3.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 15       | 15.15%  |
| Samsung Electronics  | 13       | 13.13%  |
| Dell                 | 12       | 12.12%  |
| BenQ                 | 9        | 9.09%   |
| AOC                  | 8        | 8.08%   |
| Acer                 | 7        | 7.07%   |
| Hewlett-Packard      | 6        | 6.06%   |
| Philips              | 5        | 5.05%   |
| Ancor Communications | 5        | 5.05%   |
| Sony                 | 3        | 3.03%   |
| ASUSTek Computer     | 3        | 3.03%   |
| ViewSonic            | 2        | 2.02%   |
| Lenovo               | 2        | 2.02%   |
| Fujitsu Siemens      | 2        | 2.02%   |
| Westinghouse         | 1        | 1.01%   |
| Vestel Elektronik    | 1        | 1.01%   |
| SGT                  | 1        | 1.01%   |
| NEC Computers        | 1        | 1.01%   |
| Iiyama               | 1        | 1.01%   |
| FND                  | 1        | 1.01%   |
| Denver               | 1        | 1.01%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2        | 1.92%   |
| AOC 24G2W1G4 AOC2402 1920x1080 530x300mm 24.0-inch                     | 2        | 1.92%   |
| Ancor Communications MX27AQ ACI27A5 2560x1440 600x340mm 27.2-inch      | 2        | 1.92%   |
| Westinghouse LCM-19w4 WDE1904 1440x900 410x260mm 19.1-inch             | 1        | 0.96%   |
| ViewSonic VX1940w VSC6A20 1680x1050 410x260mm 19.1-inch                | 1        | 0.96%   |
| ViewSonic LCD Monitor VSCBD2B 1920x1080 480x270mm 21.7-inch            | 1        | 0.96%   |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 530x300mm 24.0-inch     | 1        | 0.96%   |
| Sony TV SNYEE01 1920x1080                                              | 1        | 0.96%   |
| Sony TV SNY9C01 1360x768                                               | 1        | 0.96%   |
| Sony SDM-S75D/F/N SNY3800 1280x1024 340x270mm 17.1-inch                | 1        | 0.96%   |
| SGT YSD SGT1700 1280x1024 380x210mm 17.1-inch                          | 1        | 0.96%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch      | 1        | 0.96%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 520x290mm 23.4-inch      | 1        | 0.96%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                        | 1        | 0.96%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch    | 1        | 0.96%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                       | 1        | 0.96%   |
| Samsung Electronics SyncMaster SAM0373 1680x1050 440x300mm 21.0-inch   | 1        | 0.96%   |
| Samsung Electronics SyncMaster SAM027D 1680x1050 430x270mm 20.0-inch   | 1        | 0.96%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 280x210mm 13.8-inch    | 1        | 0.96%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 480x270mm 21.7-inch     | 1        | 0.96%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch      | 1        | 0.96%   |
| Samsung Electronics S24C450 SAM09CB 1920x1080 530x300mm 24.0-inch      | 1        | 0.96%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch       | 1        | 0.96%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 1110x620mm 50.1-inch | 1        | 0.96%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 530x300mm 24.0-inch     | 1        | 0.96%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 700x390mm 31.5-inch      | 1        | 0.96%   |
| Samsung Electronics C24FG7x SAM0E44 1920x1080 530x300mm 24.0-inch      | 1        | 0.96%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 1        | 0.96%   |
| Philips PHL 278E1 PHLC217 3840x2160 600x340mm 27.2-inch                | 1        | 0.96%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                 | 1        | 0.96%   |
| Philips 248CLH PHLC088 1920x1080 520x290mm 23.4-inch                   | 1        | 0.96%   |
| Philips 220E PHLC02E 1920x1080 470x260mm 21.1-inch                     | 1        | 0.96%   |
| Philips 190V PHL0081 1440x900 400x250mm 18.6-inch                      | 1        | 0.96%   |
| NEC Computers LCD1770VX NEC6696 1280x1024 340x270mm 17.1-inch          | 1        | 0.96%   |
| Lenovo LEN T22i-10 LEN61A9 1920x1080 480x270mm 21.7-inch               | 1        | 0.96%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch                | 1        | 0.96%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch                | 1        | 0.96%   |
| Hewlett-Packard Z24n G2 HPN3485 1920x1200 520x320mm 24.0-inch          | 1        | 0.96%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch       | 1        | 0.96%   |
| Hewlett-Packard LCD Monitor HPN351A 1920x1080 700x390mm 31.5-inch      | 1        | 0.96%   |
| Hewlett-Packard LCD Monitor HPN3425 1920x1080 540x300mm 24.3-inch      | 1        | 0.96%   |
| Hewlett-Packard 27f HPN354A 1920x1080 600x340mm 27.2-inch              | 1        | 0.96%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch             | 1        | 0.96%   |
| Goldstar W2361 GSM56FB 1920x1080 510x290mm 23.1-inch                   | 1        | 0.96%   |
| Goldstar W2043 GSM4E9D 1600x900 450x250mm 20.3-inch                    | 1        | 0.96%   |
| Goldstar W1942 GSM4B6F 1440x900 410x260mm 19.1-inch                    | 1        | 0.96%   |
| Goldstar M2280D GSM57B9 1920x1080 480x270mm 21.7-inch                  | 1        | 0.96%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 1        | 0.96%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch             | 1        | 0.96%   |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch               | 1        | 0.96%   |
| Goldstar LCD Monitor GSM5AB7 1920x1080 480x270mm 21.7-inch             | 1        | 0.96%   |
| Goldstar LCD Monitor GSM5AB6 1920x1080 480x270mm 21.7-inch             | 1        | 0.96%   |
| Goldstar LCD Monitor GSM5807 1920x1080 480x270mm 21.7-inch             | 1        | 0.96%   |
| Goldstar 700E GSM4317 1280x1024 330x250mm 16.3-inch                    | 1        | 0.96%   |
| Goldstar 2D FHD LG TV GSM59C6 1920x1080 510x290mm 23.1-inch            | 1        | 0.96%   |
| Goldstar 19MB35 GSM4C23 1280x1024 380x300mm 19.1-inch                  | 1        | 0.96%   |
| Fujitsu Siemens L19-8 FUS075B 1280x1024 380x300mm 19.1-inch            | 1        | 0.96%   |
| Fujitsu Siemens A17-2 DVI FUS0620 1280x1024 340x270mm 17.1-inch        | 1        | 0.96%   |
| FND F191WL FND02B8 1440x900 410x260mm 19.1-inch                        | 1        | 0.96%   |
| Denver UXGA-100-C LHC2900 2560x1080 680x280mm 29.0-inch                | 1        | 0.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 45       | 45%     |
| 1280x1024 (SXGA)   | 11       | 11%     |
| 2560x1440 (QHD)    | 8        | 8%      |
| 1600x900 (HD+)     | 7        | 7%      |
| 1440x900 (WXGA+)   | 6        | 6%      |
| 3840x2160 (4K)     | 5        | 5%      |
| 1920x1200 (WUXGA)  | 5        | 5%      |
| 1680x1050 (WSXGA+) | 4        | 4%      |
| 1366x768 (WXGA)    | 3        | 3%      |
| 2560x1080          | 2        | 2%      |
| 3440x1440          | 1        | 1%      |
| 1920x540           | 1        | 1%      |
| 1360x768           | 1        | 1%      |
| 1024x768 (XGA)     | 1        | 1%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 21       | 20.79%  |
| 21      | 14       | 13.86%  |
| 19      | 14       | 13.86%  |
| 27      | 12       | 11.88%  |
| 23      | 10       | 9.9%    |
| 17      | 7        | 6.93%   |
| 18      | 5        | 4.95%   |
| 31      | 4        | 3.96%   |
| Unknown | 4        | 3.96%   |
| 34      | 2        | 1.98%   |
| 20      | 2        | 1.98%   |
| 50      | 1        | 0.99%   |
| 42      | 1        | 0.99%   |
| 33      | 1        | 0.99%   |
| 29      | 1        | 0.99%   |
| 16      | 1        | 0.99%   |
| 13      | 1        | 0.99%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 39       | 40.21%  |
| 401-500     | 28       | 28.87%  |
| 351-400     | 7        | 7.22%   |
| 301-350     | 7        | 7.22%   |
| 601-700     | 6        | 6.19%   |
| Unknown     | 4        | 4.12%   |
| 701-800     | 3        | 3.09%   |
| 201-300     | 1        | 1.03%   |
| 1001-1500   | 1        | 1.03%   |
| 901-1000    | 1        | 1.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 66       | 68.75%  |
| 16/10 | 15       | 15.63%  |
| 5/4   | 9        | 9.38%   |
| 21/9  | 3        | 3.13%   |
| 4/3   | 2        | 2.08%   |
| 3/2   | 1        | 1.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 36       | 36%     |
| 151-200        | 20       | 20%     |
| 301-350        | 12       | 12%     |
| 251-300        | 8        | 8%      |
| 141-150        | 8        | 8%      |
| 351-500        | 7        | 7%      |
| Unknown        | 4        | 4%      |
| 121-130        | 2        | 2%      |
| More than 1000 | 1        | 1%      |
| 501-1000       | 1        | 1%      |
| 91-100         | 1        | 1%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 66       | 66%     |
| 101-120 | 23       | 23%     |
| Unknown | 4        | 4%      |
| 161-240 | 3        | 3%      |
| 121-160 | 3        | 3%      |
| 1-50    | 1        | 1%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 88       | 77.19%  |
| 0     | 14       | 12.28%  |
| 2     | 11       | 9.65%   |
| 3     | 1        | 0.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 69       | 49.29%  |
| Intel                    | 47       | 33.57%  |
| Qualcomm Atheros         | 10       | 7.14%   |
| Broadcom                 | 4        | 2.86%   |
| Ralink Technology        | 2        | 1.43%   |
| Ralink                   | 2        | 1.43%   |
| TP-Link                  | 1        | 0.71%   |
| NetGear                  | 1        | 0.71%   |
| Microchip Technology     | 1        | 0.71%   |
| MediaTek                 | 1        | 0.71%   |
| Marvell Technology Group | 1        | 0.71%   |
| D-Link System            | 1        | 0.71%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 54       | 34.39%  |
| Intel I211 Gigabit Network Connection                                         | 11       | 7.01%   |
| Intel Ethernet Connection I217-LM                                             | 7        | 4.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5        | 3.18%   |
| Intel Wi-Fi 6 AX200                                                           | 5        | 3.18%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4        | 2.55%   |
| Intel 82579V Gigabit Network Connection                                       | 4        | 2.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 3        | 1.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3        | 1.91%   |
| Intel Ethernet Connection (7) I219-V                                          | 3        | 1.91%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 1.91%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2        | 1.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 1.27%   |
| Ralink RT5370 Wireless Adapter                                                | 2        | 1.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 1.27%   |
| Intel Wireless-AC 9260                                                        | 2        | 1.27%   |
| Intel Wireless 7265                                                           | 2        | 1.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 1.27%   |
| Intel 82574L Gigabit Network Connection                                       | 2        | 1.27%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 2        | 1.27%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 1        | 0.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.64%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1        | 0.64%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.64%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 0.64%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1        | 0.64%   |
| Ralink RT2500 Wireless 802.11bg                                               | 1        | 0.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 0.64%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 0.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 0.64%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1        | 0.64%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 0.64%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 0.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 0.64%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.64%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]              | 1        | 0.64%   |
| Microchip HTC Hub Controller                                                  | 1        | 0.64%   |
| MediaTek 802.11ac Wireless LAN Card                                           | 1        | 0.64%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.64%   |
| Intel Wireless 7260                                                           | 1        | 0.64%   |
| Intel I210 Gigabit Network Connection                                         | 1        | 0.64%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.64%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 0.64%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1        | 0.64%   |
| Intel Centrino Wireless-N 2230                                                | 1        | 0.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 0.64%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 1        | 0.64%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 0.64%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.64%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.64%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1        | 0.64%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 1        | 0.64%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 0.64%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 1        | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 14       | 36.84%  |
| Realtek Semiconductor | 12       | 31.58%  |
| Broadcom              | 3        | 7.89%   |
| Ralink Technology     | 2        | 5.26%   |
| Ralink                | 2        | 5.26%   |
| Qualcomm Atheros      | 2        | 5.26%   |
| TP-Link               | 1        | 2.63%   |
| NetGear               | 1        | 2.63%   |
| MediaTek              | 1        | 2.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                              | 5        | 13.16%  |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 3        | 7.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter              | 3        | 7.89%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                           | 2        | 5.26%   |
| Ralink RT5370 Wireless Adapter                                   | 2        | 5.26%   |
| Intel Wireless-AC 9260                                           | 2        | 5.26%   |
| Intel Wireless 7265                                              | 2        | 5.26%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter               | 2        | 5.26%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                              | 1        | 2.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 1        | 2.63%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter         | 1        | 2.63%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                          | 1        | 2.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                       | 1        | 2.63%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                        | 1        | 2.63%   |
| Ralink RT2500 Wireless 802.11bg                                  | 1        | 2.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 1        | 2.63%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                 | 1        | 2.63%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101] | 1        | 2.63%   |
| MediaTek 802.11ac Wireless LAN Card                              | 1        | 2.63%   |
| Intel Wireless 7260                                              | 1        | 2.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                 | 1        | 2.63%   |
| Intel Centrino Wireless-N 2230                                   | 1        | 2.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 1        | 2.63%   |
| Intel Alder Lake-S PCH CNVi WiFi                                 | 1        | 2.63%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller           | 1        | 2.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 63       | 54.31%  |
| Intel                    | 42       | 36.21%  |
| Qualcomm Atheros         | 8        | 6.9%    |
| Marvell Technology Group | 1        | 0.86%   |
| D-Link System            | 1        | 0.86%   |
| Broadcom                 | 1        | 0.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 54       | 45.76%  |
| Intel I211 Gigabit Network Connection                                         | 11       | 9.32%   |
| Intel Ethernet Connection I217-LM                                             | 7        | 5.93%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5        | 4.24%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4        | 3.39%   |
| Intel 82579V Gigabit Network Connection                                       | 4        | 3.39%   |
| Intel Ethernet Connection (7) I219-V                                          | 3        | 2.54%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 2.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 1.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 1.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 1.69%   |
| Intel 82574L Gigabit Network Connection                                       | 2        | 1.69%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.85%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 0.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 0.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 0.85%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1        | 0.85%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 0.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 0.85%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.85%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.85%   |
| Intel I210 Gigabit Network Connection                                         | 1        | 0.85%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.85%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 0.85%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 0.85%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 0.85%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.85%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.85%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1        | 0.85%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 1        | 0.85%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 0.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 111      | 75.51%  |
| WiFi     | 35       | 23.81%  |
| Modem    | 1        | 0.68%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 106      | 84.8%   |
| WiFi     | 19       | 15.2%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 79       | 69.91%  |
| 2     | 24       | 21.24%  |
| 3     | 5        | 4.42%   |
| 4     | 3        | 2.65%   |
| 0     | 2        | 1.77%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 108      | 93.1%   |
| Yes  | 8        | 6.9%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 15       | 42.86%  |
| Cambridge Silicon Radio         | 7        | 20%     |
| Apple                           | 3        | 8.57%   |
| Realtek Semiconductor           | 2        | 5.71%   |
| Integrated System Solution      | 2        | 5.71%   |
| IMC Networks                    | 2        | 5.71%   |
| ASUSTek Computer                | 2        | 5.71%   |
| Qualcomm Atheros Communications | 1        | 2.86%   |
| HTC (High Tech Computer)        | 1        | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 7        | 20%     |
| Intel AX200 Bluetooth                                                | 5        | 14.29%  |
| Intel Bluetooth wireless interface                                   | 3        | 8.57%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 2        | 5.71%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2        | 5.71%   |
| Intel AX201 Bluetooth                                                | 2        | 5.71%   |
| Apple Apple Broadcom Built-in Bluetooth                              | 2        | 5.71%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device          | 1        | 2.86%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 1        | 2.86%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 2.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 1        | 2.86%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1        | 2.86%   |
| Integrated System Solution Bluetooth Device                          | 1        | 2.86%   |
| IMC Networks Realtek Bluetooth Adapter                               | 1        | 2.86%   |
| IMC Networks Realtek Bluetooth 4.0 Adapter                           | 1        | 2.86%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 2.86%   |
| ASUS Bluetooth Controller                                            | 1        | 2.86%   |
| ASUS ASUS USB-BT500                                                  | 1        | 2.86%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 1        | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 73       | 38.83%  |
| AMD                         | 45       | 23.94%  |
| Nvidia                      | 43       | 22.87%  |
| C-Media Electronics         | 5        | 2.66%   |
| Texas Instruments           | 3        | 1.6%    |
| Logitech                    | 3        | 1.6%    |
| JMTek                       | 2        | 1.06%   |
| GN Netcom                   | 2        | 1.06%   |
| Yamaha                      | 1        | 0.53%   |
| VIA Technologies            | 1        | 0.53%   |
| SteelSeries ApS             | 1        | 0.53%   |
| Nektar                      | 1        | 0.53%   |
| KORG                        | 1        | 0.53%   |
| Kingston Technology         | 1        | 0.53%   |
| Focusrite-Novation          | 1        | 0.53%   |
| FiiO Electronics Technology | 1        | 0.53%   |
| Creative Labs               | 1        | 0.53%   |
| Corsair                     | 1        | 0.53%   |
| Cambridge Silicon Radio     | 1        | 0.53%   |
| ASUSTek Computer            | 1        | 0.53%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 13       | 6.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12       | 5.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10       | 4.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10       | 4.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9        | 4.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7        | 3.24%   |
| AMD Family 17h/19h HD Audio Controller                                     | 7        | 3.24%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7        | 3.24%   |
| Intel Cannon Lake PCH cAVS                                                 | 6        | 2.78%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6        | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6        | 2.78%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 2.78%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 2.31%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 2.31%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 1.85%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 1.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 1.85%   |
| Intel 200 Series PCH HD Audio                                              | 4        | 1.85%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 1.85%   |
| Nvidia High Definition Audio Controller                                    | 3        | 1.39%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 1.39%   |
| Nvidia GA104 High Definition Audio Controller                              | 3        | 1.39%   |
| AMD Navi 10 HDMI Audio                                                     | 3        | 1.39%   |
| Texas Instruments PCM2902 Audio Codec                                      | 2        | 0.93%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 0.93%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.93%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 0.93%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 0.93%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 0.93%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.93%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 0.93%   |
| JMTek USB PnP Audio Device                                                 | 2        | 0.93%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 0.93%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 2        | 0.93%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2        | 0.93%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 2        | 0.93%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 0.93%   |
| AMD FCH Azalia Controller                                                  | 2        | 0.93%   |
| Yamaha Steinberg UR12                                                      | 1        | 0.46%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 0.46%   |
| Texas Instruments PCM2902C Audio CODEC                                     | 1        | 0.46%   |
| SteelSeries ApS SteelSeries Arctis 5 Arctis 5 Chat Arctis 5 Game           | 1        | 0.46%   |
| Nvidia MCP65 High Definition Audio                                         | 1        | 0.46%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 0.46%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.46%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 0.46%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.46%   |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 0.46%   |
| Nektar Impact GX61                                                         | 1        | 0.46%   |
| Logitech Headset H390                                                      | 1        | 0.46%   |
| Logitech HD Webcam C510                                                    | 1        | 0.46%   |
| Logitech G560 Gaming Speaker                                               | 1        | 0.46%   |
| KORG microKEY-25                                                           | 1        | 0.46%   |
| Kingston Technology HyperX QuadCast                                        | 1        | 0.46%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1        | 0.46%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 0.46%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 0.46%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 0.46%   |
| Intel Broadwell-U Audio Controller                                         | 1        | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 26       | 20.63%  |
| Unknown             | 22       | 17.46%  |
| Corsair             | 12       | 9.52%   |
| Crucial             | 10       | 7.94%   |
| SK Hynix            | 9        | 7.14%   |
| G.Skill             | 9        | 7.14%   |
| Samsung Electronics | 8        | 6.35%   |
| Micron Technology   | 7        | 5.56%   |
| Team                | 4        | 3.17%   |
| Patriot             | 3        | 2.38%   |
| Nanya Technology    | 2        | 1.59%   |
| AMD                 | 2        | 1.59%   |
| A-DATA Technology   | 2        | 1.59%   |
| Unknown             | 2        | 1.59%   |
| Unifosa             | 1        | 0.79%   |
| Transcend           | 1        | 0.79%   |
| TakeMS              | 1        | 0.79%   |
| Super Talent        | 1        | 0.79%   |
| Hikvision           | 1        | 0.79%   |
| GOODRAM             | 1        | 0.79%   |
| Goldkey             | 1        | 0.79%   |
| Atermiter           | 1        | 0.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s   | 3        | 2.13%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 2        | 1.42%   |
| Unknown RAM Module 2GB DIMM DDR2                       | 2        | 1.42%   |
| Unknown RAM Module 2GB DIMM 400MT/s                    | 2        | 1.42%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 2        | 1.42%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 2        | 1.42%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s    | 2        | 1.42%   |
| Micron RAM 18KSF51272AZ-1G4M1 4GB DIMM DDR3 1333MT/s   | 2        | 1.42%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s | 2        | 1.42%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s  | 2        | 1.42%   |
| Crucial RAM BL16G32C16U4B.16FE 16GB DIMM DDR4 3200MT/s | 2        | 1.42%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s  | 2        | 1.42%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 2667MT/s  | 2        | 1.42%   |
| Unknown                                                | 2        | 1.42%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 1        | 0.71%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 1        | 0.71%   |
| Unknown RAM Module 4GB SODIMM DDR3 800MT/s             | 1        | 0.71%   |
| Unknown RAM Module 4GB DIMM SDRAM                      | 1        | 0.71%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                   | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM SDRAM 533MT/s              | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s               | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s               | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 1        | 0.71%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s               | 1        | 0.71%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s               | 1        | 0.71%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s      | 1        | 0.71%   |
| Transcend RAM TS128MLQ64V8U 1GB DIMM DDR2 800MT/s      | 1        | 0.71%   |
| Team RAM TEAMGROUP-UD4-2133 8GB DIMM DDR4 2133MT/s     | 1        | 0.71%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s     | 1        | 0.71%   |
| TakeMS RAM TMS1GB264C081665QI 1GB DIMM DDR2 667MT/s    | 1        | 0.71%   |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1333MT/s  | 1        | 0.71%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s           | 1        | 0.71%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1333MT/s             | 1        | 0.71%   |
| SK Hynix RAM HMT451U7BFR8A-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.71%   |
| SK Hynix RAM HMT451S6BCFR8A-PB 4GB DIMM DDR3 1600MT/s  | 1        | 0.71%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s | 1        | 0.71%   |
| SK Hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s   | 1        | 0.71%   |
| SK Hynix RAM HMAA1GU6CJR6N-XN 8GB DIMM DDR4 3200MT/s   | 1        | 0.71%   |
| SK Hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s   | 1        | 0.71%   |
| SK Hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2133MT/s   | 1        | 0.71%   |
| Samsung RAM Module 4GB SODIMM DDR4 2133MT/s            | 1        | 0.71%   |
| Samsung RAM M471B5273DH0-CH9 4GB DIMM DDR3 1333MT/s    | 1        | 0.71%   |
| Samsung RAM M393B1G70QH0 8GB DIMM DDR3 1333MT/s        | 1        | 0.71%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s    | 1        | 0.71%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 1        | 0.71%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 2666MT/s    | 1        | 0.71%   |
| Samsung RAM M378A5143EB1-CPB 4GB DIMM DDR4 2133MT/s    | 1        | 0.71%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s    | 1        | 0.71%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s         | 1        | 0.71%   |
| Patriot RAM PSD34G16002 4GB DIMM DDR3 1600MT/s         | 1        | 0.71%   |
| Patriot RAM 1600 CL9 Series 8GB DIMM DDR3 1600MT/s     | 1        | 0.71%   |
| Nanya RAM NT2GC64B88B0NF-CG 2GB DIMM DDR3 1333MT/s     | 1        | 0.71%   |
| Nanya RAM M2F4G64CB8HG5N-CG 4GB DIMM DDR3 1333MT/s     | 1        | 0.71%   |
| Nanya RAM M2F2G64CB88G7N-CG 2GB DIMM DDR3 1333MT/s     | 1        | 0.71%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s               | 1        | 0.71%   |
| Micron RAM 4ATF51264AZ-3G2J1 4GB DIMM DDR4 3200MT/s    | 1        | 0.71%   |
| Micron RAM 18ASF4G72AZ-3G2B1 32GB DIMM DDR4 3200MT/s   | 1        | 0.71%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s | 1        | 0.71%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s  | 1        | 0.71%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 50       | 45.45%  |
| DDR3    | 39       | 35.45%  |
| DDR2    | 8        | 7.27%   |
| Unknown | 8        | 7.27%   |
| SDRAM   | 4        | 3.64%   |
| DDR     | 1        | 0.91%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 101      | 92.66%  |
| SODIMM | 8        | 7.34%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 40       | 33.33%  |
| 4096  | 32       | 26.67%  |
| 2048  | 22       | 18.33%  |
| 16384 | 18       | 15%     |
| 1024  | 6        | 5%      |
| 32768 | 2        | 1.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 22       | 18.49%  |
| 1333    | 21       | 17.65%  |
| 3200    | 14       | 11.76%  |
| 2133    | 13       | 10.92%  |
| 2400    | 10       | 8.4%    |
| 2667    | 7        | 5.88%   |
| 2666    | 6        | 5.04%   |
| 800     | 6        | 5.04%   |
| Unknown | 5        | 4.2%    |
| 3600    | 3        | 2.52%   |
| 667     | 3        | 2.52%   |
| 1066    | 2        | 1.68%   |
| 400     | 2        | 1.68%   |
| 3733    | 1        | 0.84%   |
| 3400    | 1        | 0.84%   |
| 1867    | 1        | 0.84%   |
| 533     | 1        | 0.84%   |
| 333     | 1        | 0.84%   |

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
| Logitech                | 5        | 45.45%  |
| Z-Star Microelectronics | 1        | 9.09%   |
| IMC Networks            | 1        | 9.09%   |
| Hewlett-Packard         | 1        | 9.09%   |
| Genesys Logic           | 1        | 9.09%   |
| Chicony Electronics     | 1        | 9.09%   |
| Arkmicro Technologies   | 1        | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Z-Star Lenovo USB2.0 UVC Camera  | 1        | 9.09%   |
| Logitech Webcam C930e            | 1        | 9.09%   |
| Logitech Webcam C310             | 1        | 9.09%   |
| Logitech Webcam C270             | 1        | 9.09%   |
| Logitech C922 Pro Stream Webcam  | 1        | 9.09%   |
| Logitech BRIO Ultra HD Webcam    | 1        | 9.09%   |
| IMC Networks XHC Camera          | 1        | 9.09%   |
| HP Realtek PC Camera             | 1        | 9.09%   |
| Genesys Logic Digital Microscope | 1        | 9.09%   |
| Chicony HP 0.3MP Webcam          | 1        | 9.09%   |
| Arkmicro USB2.0 PC CAMERA        | 1        | 9.09%   |

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
| 1     | 46       | 40.71%  |
| 0     | 46       | 40.71%  |
| 2     | 16       | 14.16%  |
| 3     | 3        | 2.65%   |
| 4     | 2        | 1.77%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 58       | 67.44%  |
| Net/wireless             | 18       | 20.93%  |
| Bluetooth                | 4        | 4.65%   |
| Sound                    | 3        | 3.49%   |
| Network                  | 1        | 1.16%   |
| Net/ethernet             | 1        | 1.16%   |
| Card reader              | 1        | 1.16%   |

