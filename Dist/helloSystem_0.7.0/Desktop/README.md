helloSystem 0.7.0 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.7.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://bsd-hardware.info/?view=trends

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

Total: 132

| Vendor   | Model                    | Probe                                                     | Date         |
|----------|--------------------------|-----------------------------------------------------------|--------------|
| Dell     | 0D6H9T A00               | [7daab72741](https://bsd-hardware.info/?probe=7daab72741) | Apr 01, 2022 |
| ASUSTek  | P8Z77-V LX               | [49627775f3](https://bsd-hardware.info/?probe=49627775f3) | Mar 31, 2022 |
| ASUSTek  | P6-P8H61E                | [11664cd9d7](https://bsd-hardware.info/?probe=11664cd9d7) | Mar 30, 2022 |
| ASUSTek  | M4A88T-M                 | [6a615f6be5](https://bsd-hardware.info/?probe=6a615f6be5) | Mar 30, 2022 |
| ASUSTek  | M5A78L-M LX3             | [0906d116eb](https://bsd-hardware.info/?probe=0906d116eb) | Mar 29, 2022 |
| Gigabyte | H110N-CF                 | [89593af061](https://bsd-hardware.info/?probe=89593af061) | Mar 29, 2022 |
| Gigabyte | H61M-S2PV                | [553f2beb91](https://bsd-hardware.info/?probe=553f2beb91) | Mar 27, 2022 |
| ASRock   | A320M-HDV R4.0           | [8c89faeb24](https://bsd-hardware.info/?probe=8c89faeb24) | Mar 26, 2022 |
| ASRock   | A320M-HDV R4.0           | [ae1fa6cbce](https://bsd-hardware.info/?probe=ae1fa6cbce) | Mar 26, 2022 |
| ASUSTek  | P8Z77-V LX               | [70d10ce47c](https://bsd-hardware.info/?probe=70d10ce47c) | Mar 25, 2022 |
| MSI      | B85-G43                  | [f0a919c35f](https://bsd-hardware.info/?probe=f0a919c35f) | Mar 25, 2022 |
| ASUSTek  | P8Z77-V LX               | [99d079bd5a](https://bsd-hardware.info/?probe=99d079bd5a) | Mar 25, 2022 |
| MSI      | B85-G43                  | [7bd545fda8](https://bsd-hardware.info/?probe=7bd545fda8) | Mar 25, 2022 |
| ASUSTek  | P8Z77-V LX               | [c76aa38baf](https://bsd-hardware.info/?probe=c76aa38baf) | Mar 24, 2022 |
| ASUSTek  | P8Z77-V LX               | [8696405d09](https://bsd-hardware.info/?probe=8696405d09) | Mar 24, 2022 |
| ECS      | G41T-M9                  | [9ef50c47da](https://bsd-hardware.info/?probe=9ef50c47da) | Mar 21, 2022 |
| Gigabyte | H270-Gaming 3            | [2727a8e439](https://bsd-hardware.info/?probe=2727a8e439) | Mar 15, 2022 |
| Gigabyte | G31M-S2C                 | [5a22bb6991](https://bsd-hardware.info/?probe=5a22bb6991) | Mar 12, 2022 |
| Lenovo   | IdeaCentre B545 10100    | [2f13d4a946](https://bsd-hardware.info/?probe=2f13d4a946) | Mar 12, 2022 |
| ASUSTek  | P5Q DELUXE               | [b4234170e8](https://bsd-hardware.info/?probe=b4234170e8) | Mar 10, 2022 |
| Pegatron | IPM41-D3                 | [a58b9a4f8f](https://bsd-hardware.info/?probe=a58b9a4f8f) | Mar 09, 2022 |
| Koloe    | X58                      | [58e098eca2](https://bsd-hardware.info/?probe=58e098eca2) | Mar 09, 2022 |
| HP       | 8054                     | [86b6b8373c](https://bsd-hardware.info/?probe=86b6b8373c) | Mar 08, 2022 |
| HP       | 8054                     | [00078554d2](https://bsd-hardware.info/?probe=00078554d2) | Mar 08, 2022 |
| Koloe    | X58                      | [c501dfa5c8](https://bsd-hardware.info/?probe=c501dfa5c8) | Mar 07, 2022 |
| HP       | 1905                     | [e271589365](https://bsd-hardware.info/?probe=e271589365) | Mar 01, 2022 |
| Gigabyte | B450M S2H                | [78f79fab6f](https://bsd-hardware.info/?probe=78f79fab6f) | Feb 28, 2022 |
| Dell     | 0KV62T A00               | [0541a207c7](https://bsd-hardware.info/?probe=0541a207c7) | Feb 28, 2022 |
| HP       | 1905                     | [aa010e00f2](https://bsd-hardware.info/?probe=aa010e00f2) | Feb 28, 2022 |
| ASRock   | TRX40 Taichi             | [a2df68e1d1](https://bsd-hardware.info/?probe=a2df68e1d1) | Feb 26, 2022 |
| Intel    | H81                      | [04d2739bdc](https://bsd-hardware.info/?probe=04d2739bdc) | Feb 25, 2022 |
| Intel    | DCP847SKE G80890-107     | [f9d33f1ab1](https://bsd-hardware.info/?probe=f9d33f1ab1) | Feb 23, 2022 |
| Medion   | H61H2-LM3                | [beb12f2884](https://bsd-hardware.info/?probe=beb12f2884) | Feb 23, 2022 |
| ASRock   | H81M-DG4                 | [e20db6ad83](https://bsd-hardware.info/?probe=e20db6ad83) | Feb 23, 2022 |
| HP       | 1998                     | [485d417a2e](https://bsd-hardware.info/?probe=485d417a2e) | Feb 23, 2022 |
| Dell     | 0VD5HY A07               | [bb86fb3e67](https://bsd-hardware.info/?probe=bb86fb3e67) | Feb 22, 2022 |
| ASUSTek  | CROSSHAIR VI HERO        | [1e6ff84e5d](https://bsd-hardware.info/?probe=1e6ff84e5d) | Feb 21, 2022 |
| Gigabyte | P41T-D3                  | [e5417931a7](https://bsd-hardware.info/?probe=e5417931a7) | Feb 18, 2022 |
| ASRock   | B460M Pro4               | [7a2781344f](https://bsd-hardware.info/?probe=7a2781344f) | Feb 17, 2022 |
| ASUSTek  | PRIME Z390-P             | [3a72227408](https://bsd-hardware.info/?probe=3a72227408) | Feb 16, 2022 |
| Gigabyte | C246M-WU4-CF             | [4b6c6d8bde](https://bsd-hardware.info/?probe=4b6c6d8bde) | Feb 15, 2022 |
| MSI      | B450 GAMING PLUS MAX     | [df6278638e](https://bsd-hardware.info/?probe=df6278638e) | Feb 15, 2022 |
| ASRock   | H61M/U3S3                | [257e13f206](https://bsd-hardware.info/?probe=257e13f206) | Feb 12, 2022 |
| ASUSTek  | PRIME Z390-P             | [abf34bbc7e](https://bsd-hardware.info/?probe=abf34bbc7e) | Feb 12, 2022 |
| ASRock   | H61M/U3S3                | [34dac4c0cd](https://bsd-hardware.info/?probe=34dac4c0cd) | Feb 11, 2022 |
| MSI      | B450 GAMING PLUS MAX     | [6997de25f9](https://bsd-hardware.info/?probe=6997de25f9) | Feb 11, 2022 |
| Intel    | X58                      | [f7075908f6](https://bsd-hardware.info/?probe=f7075908f6) | Feb 09, 2022 |
| ASUSTek  | PRIME Z390-P             | [b1931633be](https://bsd-hardware.info/?probe=b1931633be) | Feb 09, 2022 |
| ASUSTek  | PRIME Z390-P             | [f9c1e787a9](https://bsd-hardware.info/?probe=f9c1e787a9) | Feb 09, 2022 |
| MSI      | B75A-G43                 | [8e445eb2d4](https://bsd-hardware.info/?probe=8e445eb2d4) | Feb 08, 2022 |
| ASUSTek  | P6-P8H61E                | [e838981914](https://bsd-hardware.info/?probe=e838981914) | Feb 06, 2022 |
| ASRock   | H81M-VG4 R2.0            | [8af8b5270e](https://bsd-hardware.info/?probe=8af8b5270e) | Feb 04, 2022 |
| Apple    | Mac-F221BEC8             | [e5043f0af4](https://bsd-hardware.info/?probe=e5043f0af4) | Feb 04, 2022 |
| Pegatron | NARRA5                   | [64d4fb9b97](https://bsd-hardware.info/?probe=64d4fb9b97) | Feb 02, 2022 |
| Gigabyte | Z390 GAMING X-CF         | [ee05643521](https://bsd-hardware.info/?probe=ee05643521) | Feb 01, 2022 |
| ASUSTek  | P5P43TD PRO              | [5999e0ebfb](https://bsd-hardware.info/?probe=5999e0ebfb) | Jan 31, 2022 |
| Intel    | H81                      | [c2f3025900](https://bsd-hardware.info/?probe=c2f3025900) | Jan 31, 2022 |
| Pegatron | 2A99h                    | [e34b6118a2](https://bsd-hardware.info/?probe=e34b6118a2) | Jan 30, 2022 |
| Fujitsu  | D3161-A1 S26361-D3161-A1 | [58ea01e4e6](https://bsd-hardware.info/?probe=58ea01e4e6) | Jan 29, 2022 |
| Intel    | DH77EB AAG39073-400      | [bfe6ef301b](https://bsd-hardware.info/?probe=bfe6ef301b) | Jan 29, 2022 |
| ASUSTek  | P5GC-MX                  | [372749f9d7](https://bsd-hardware.info/?probe=372749f9d7) | Jan 27, 2022 |
| Unknown  | Unknown                  | [a9d799ca71](https://bsd-hardware.info/?probe=a9d799ca71) | Jan 27, 2022 |
| ASUSTek  | P5B SE                   | [f97fba19c1](https://bsd-hardware.info/?probe=f97fba19c1) | Jan 26, 2022 |
| Fujitsu  | D3161-A1 S26361-D3161-A1 | [9f0a000ceb](https://bsd-hardware.info/?probe=9f0a000ceb) | Jan 25, 2022 |
| ASUSTek  | P5B SE                   | [e3332e7b94](https://bsd-hardware.info/?probe=e3332e7b94) | Jan 25, 2022 |
| ASRock   | B460M Pro4               | [107a1e59f5](https://bsd-hardware.info/?probe=107a1e59f5) | Jan 25, 2022 |
| ASRock   | A300M-STX                | [8edf072b67](https://bsd-hardware.info/?probe=8edf072b67) | Jan 25, 2022 |
| ASUSTek  | BM6835_BM6635_BP6335     | [73562aa169](https://bsd-hardware.info/?probe=73562aa169) | Jan 25, 2022 |
| ASUSTek  | P8H61-M LX3 PLUS R2.0    | [df08e2e8f0](https://bsd-hardware.info/?probe=df08e2e8f0) | Jan 24, 2022 |
| ASUSTek  | P7H55-M                  | [fb73c2f7dc](https://bsd-hardware.info/?probe=fb73c2f7dc) | Jan 23, 2022 |
| HP       | 1998                     | [b59dbcdc9c](https://bsd-hardware.info/?probe=b59dbcdc9c) | Jan 23, 2022 |
| ASUSTek  | ROG STRIX B450-F GAMING  | [670e41ed41](https://bsd-hardware.info/?probe=670e41ed41) | Jan 21, 2022 |
| MSI      | PRO Z690-A WIFI DDR4     | [04abd226f3](https://bsd-hardware.info/?probe=04abd226f3) | Jan 21, 2022 |
| ASUSTek  | Maximus VIII HERO        | [a780a7bab2](https://bsd-hardware.info/?probe=a780a7bab2) | Jan 18, 2022 |
| ASUSTek  | TUF GAMING X570-PLUS     | [9cd2758a5f](https://bsd-hardware.info/?probe=9cd2758a5f) | Jan 18, 2022 |
| ASUSTek  | PRIME X570-P             | [3dead218e1](https://bsd-hardware.info/?probe=3dead218e1) | Jan 16, 2022 |
| Gigabyte | B365 HD3                 | [62fc48bd99](https://bsd-hardware.info/?probe=62fc48bd99) | Jan 15, 2022 |
| Dell     | 0XCR8D A03               | [48e9447b37](https://bsd-hardware.info/?probe=48e9447b37) | Jan 15, 2022 |
| ASUSTek  | ROG STRIX Z390-E GAMING  | [d377e06101](https://bsd-hardware.info/?probe=d377e06101) | Jan 15, 2022 |
| Gigabyte | Z77N-WIFI                | [459bb6486d](https://bsd-hardware.info/?probe=459bb6486d) | Jan 13, 2022 |
| ASUSTek  | P8Z68-M PRO              | [a0885f4f44](https://bsd-hardware.info/?probe=a0885f4f44) | Jan 10, 2022 |
| HP       | 8169                     | [85e0cf058c](https://bsd-hardware.info/?probe=85e0cf058c) | Jan 10, 2022 |
| ASUSTek  | GA35DX                   | [eccb947ae4](https://bsd-hardware.info/?probe=eccb947ae4) | Jan 05, 2022 |
| Unknown  | G31T-M7                  | [ed7d80e01a](https://bsd-hardware.info/?probe=ed7d80e01a) | Jan 03, 2022 |
| ASUSTek  | TUF GAMING X570-PLUS     | [a671e3eb04](https://bsd-hardware.info/?probe=a671e3eb04) | Dec 31, 2021 |
| ASRock   | X570 Phantom Gaming 4    | [15211db056](https://bsd-hardware.info/?probe=15211db056) | Dec 28, 2021 |
| Dell     | 0200DY A01               | [fb37dcbb93](https://bsd-hardware.info/?probe=fb37dcbb93) | Dec 28, 2021 |
| Pegatron | IPM41-D3                 | [6829928dad](https://bsd-hardware.info/?probe=6829928dad) | Dec 28, 2021 |
| Dell     | 0H9KW5 A00               | [e962ca25b3](https://bsd-hardware.info/?probe=e962ca25b3) | Dec 28, 2021 |
| Gigabyte | 970A-DS3P                | [0918f0a5b9](https://bsd-hardware.info/?probe=0918f0a5b9) | Dec 25, 2021 |
| ASUSTek  | PRIME B350M-A            | [b0aa3885bb](https://bsd-hardware.info/?probe=b0aa3885bb) | Dec 25, 2021 |
| ASUSTek  | Z170-P                   | [bde74629f9](https://bsd-hardware.info/?probe=bde74629f9) | Dec 25, 2021 |
| ASUSTek  | TUF GAMING X570-PLUS     | [8ac48ba9c3](https://bsd-hardware.info/?probe=8ac48ba9c3) | Dec 23, 2021 |
| Gigabyte | E3000N                   | [eb0ba1b296](https://bsd-hardware.info/?probe=eb0ba1b296) | Dec 22, 2021 |
| ASUSTek  | ROG STRIX Z370-E GAMING  | [936afa4de3](https://bsd-hardware.info/?probe=936afa4de3) | Dec 21, 2021 |
| ASUSTek  | PRIME A320M-K            | [42599b554e](https://bsd-hardware.info/?probe=42599b554e) | Dec 21, 2021 |
| Gigabyte | X58A-UD5                 | [62b94dd372](https://bsd-hardware.info/?probe=62b94dd372) | Dec 21, 2021 |
| ASUSTek  | ROG STRIX X570-E GAMING  | [5cc62c68f9](https://bsd-hardware.info/?probe=5cc62c68f9) | Dec 21, 2021 |
| Gigabyte | H170-D3HP-CF             | [a490614a39](https://bsd-hardware.info/?probe=a490614a39) | Dec 21, 2021 |
| ASRock   | H110M-DGS                | [40c4553adb](https://bsd-hardware.info/?probe=40c4553adb) | Dec 21, 2021 |
| ASUSTek  | P5VD2-VM                 | [7e8f3cf783](https://bsd-hardware.info/?probe=7e8f3cf783) | Dec 20, 2021 |
| ASUSTek  | Q170M-C                  | [7f9e35a31c](https://bsd-hardware.info/?probe=7f9e35a31c) | Dec 20, 2021 |
| Dell     | 0TDG4V A00               | [3ce808c135](https://bsd-hardware.info/?probe=3ce808c135) | Dec 20, 2021 |
| Dell     | 0TDG4V A00               | [5292ad64ef](https://bsd-hardware.info/?probe=5292ad64ef) | Dec 20, 2021 |
| ASUSTek  | P8Z77-V LX               | [3c71a8ba4e](https://bsd-hardware.info/?probe=3c71a8ba4e) | Dec 20, 2021 |
| MSI      | X370 SLI PLUS            | [73853f1fc2](https://bsd-hardware.info/?probe=73853f1fc2) | Dec 19, 2021 |
| Quanta   | 2AC7 011                 | [1a831a1d34](https://bsd-hardware.info/?probe=1a831a1d34) | Dec 18, 2021 |
| Gigabyte | Z77X-UD3H                | [759ce775c9](https://bsd-hardware.info/?probe=759ce775c9) | Dec 15, 2021 |
| ASUSTek  | TUF GAMING X570-PLUS     | [32d20b9b8e](https://bsd-hardware.info/?probe=32d20b9b8e) | Dec 14, 2021 |
| HP       | 843B                     | [f0d279747f](https://bsd-hardware.info/?probe=f0d279747f) | Dec 13, 2021 |
| HP       | 843B                     | [56400d3999](https://bsd-hardware.info/?probe=56400d3999) | Dec 13, 2021 |
| ASUSTek  | PRIME B450M-A            | [aea4a33dee](https://bsd-hardware.info/?probe=aea4a33dee) | Dec 13, 2021 |
| Gigabyte | H270M-DS3H-CF            | [50fba6deda](https://bsd-hardware.info/?probe=50fba6deda) | Dec 11, 2021 |
| Gigabyte | B450 I AORUS PRO WIFI-CF | [6a1100cfdb](https://bsd-hardware.info/?probe=6a1100cfdb) | Dec 11, 2021 |
| Acer     | RevoOne RL85             | [a1e32de7da](https://bsd-hardware.info/?probe=a1e32de7da) | Dec 10, 2021 |
| Gigabyte | B450 I AORUS PRO WIFI-CF | [b900b364f6](https://bsd-hardware.info/?probe=b900b364f6) | Dec 10, 2021 |
| Dell     | 0YF8P5 A00               | [0f03a66475](https://bsd-hardware.info/?probe=0f03a66475) | Dec 09, 2021 |
| Dell     | 0YF8P5 A00               | [83b36f7c3d](https://bsd-hardware.info/?probe=83b36f7c3d) | Dec 09, 2021 |
| Gigabyte | H270M-DS3H-CF            | [a084ff48c2](https://bsd-hardware.info/?probe=a084ff48c2) | Dec 09, 2021 |
| Gigabyte | H270M-DS3H-CF            | [17b557d792](https://bsd-hardware.info/?probe=17b557d792) | Dec 08, 2021 |
| Gigabyte | X570 AORUS ELITE         | [8cfe11fe93](https://bsd-hardware.info/?probe=8cfe11fe93) | Nov 30, 2021 |
| HP       | 843B                     | [376e006a40](https://bsd-hardware.info/?probe=376e006a40) | Nov 30, 2021 |
| Intel    | DG41TY AAE47335-300      | [dd357bcaa5](https://bsd-hardware.info/?probe=dd357bcaa5) | Nov 30, 2021 |
| HP       | 843B                     | [404224439d](https://bsd-hardware.info/?probe=404224439d) | Nov 29, 2021 |
| HP       | 843B                     | [a8ac0e9efb](https://bsd-hardware.info/?probe=a8ac0e9efb) | Nov 29, 2021 |
| HP       | 1825                     | [32f07d2ba3](https://bsd-hardware.info/?probe=32f07d2ba3) | Nov 28, 2021 |
| Gigabyte | B450 I AORUS PRO WIFI-CF | [4cd5e5166a](https://bsd-hardware.info/?probe=4cd5e5166a) | Nov 27, 2021 |
| ASRock   | 775i945GZ                | [16fc4ee10d](https://bsd-hardware.info/?probe=16fc4ee10d) | Nov 26, 2021 |
| HP       | 844C                     | [fb7d8eaf5d](https://bsd-hardware.info/?probe=fb7d8eaf5d) | Nov 06, 2021 |
| Unknown  | X79                      | [ef88cbc606](https://bsd-hardware.info/?probe=ef88cbc606) | Nov 05, 2021 |
| HP       | 843B                     | [9761f29b5e](https://bsd-hardware.info/?probe=9761f29b5e) | Oct 25, 2021 |
| Acer     | Aspire TC-780            | [3ce8481842](https://bsd-hardware.info/?probe=3ce8481842) | Oct 10, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 96       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 95       | 98.96%  |
| GNOME        | 1        | 1.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 96       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 96       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 94       | 97.92%  |
| de_DE | 1        | 1.04%   |
| C     | 1        | 1.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 92       | 95.83%  |
| BIOS | 4        | 4.17%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Cd9660 | 63       | 63.64%  |
| Zfs    | 36       | 36.36%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 92       | 95.83%  |
| MBR  | 4        | 4.17%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 30       | 31.25%  |
| Gigabyte Technology | 18       | 18.75%  |
| ASRock              | 10       | 10.42%  |
| Dell                | 8        | 8.33%   |
| Hewlett-Packard     | 7        | 7.29%   |
| MSI                 | 5        | 5.21%   |
| Intel               | 5        | 5.21%   |
| Pegatron            | 3        | 3.13%   |
| Unknown             | 2        | 2.08%   |
| Quanta              | 1        | 1.04%   |
| Medion              | 1        | 1.04%   |
| Lenovo              | 1        | 1.04%   |
| Koloe               | 1        | 1.04%   |
| Fujitsu             | 1        | 1.04%   |
| ECS                 | 1        | 1.04%   |
| Apple               | 1        | 1.04%   |
| Acer                | 1        | 1.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS TUF GAMING X570-PLUS           | 2        | 2.08%   |
| ASUS P8Z77-V LX                     | 2        | 2.08%   |
| Unknown                             | 2        | 2.08%   |
| Quanta 120-1135                     | 1        | 1.04%   |
| Pegatron IPM41-D3                   | 1        | 1.04%   |
| Pegatron Compaq 505B Microtower PC  | 1        | 1.04%   |
| Pegatron AY627AA-ABA a4313w         | 1        | 1.04%   |
| MSI MS-7D25                         | 1        | 1.04%   |
| MSI MS-7B86                         | 1        | 1.04%   |
| MSI MS-7A33                         | 1        | 1.04%   |
| MSI MS-7816                         | 1        | 1.04%   |
| MSI MS-7758                         | 1        | 1.04%   |
| Medion H61H2-LM3                    | 1        | 1.04%   |
| Lenovo IdeaCentre B545 10100        | 1        | 1.04%   |
| Koloe Thurley                       | 1        | 1.04%   |
| Intel X58                           | 1        | 1.04%   |
| Intel H81                           | 1        | 1.04%   |
| Intel DH77EB AAG39073-400           | 1        | 1.04%   |
| Intel DG41TY AAE47335-300           | 1        | 1.04%   |
| Intel DCP847SKE G80890-107          | 1        | 1.04%   |
| HP Z230 Tower Workstation           | 1        | 1.04%   |
| HP ProDesk 600 G2 DM                | 1        | 1.04%   |
| HP Pavilion Gaming Desktop 690-00xx | 1        | 1.04%   |
| HP EliteDesk 800 G2 SFF             | 1        | 1.04%   |
| HP EliteDesk 800 G1 DM              | 1        | 1.04%   |
| HP EliteDesk 700 G1 SFF             | 1        | 1.04%   |
| HP 844C                             | 1        | 1.04%   |
| Gigabyte Z77X-UD3H                  | 1        | 1.04%   |
| Gigabyte Z77N-WIFI                  | 1        | 1.04%   |
| Gigabyte Z390 GAMING X              | 1        | 1.04%   |
| Gigabyte X58A-UD5                   | 1        | 1.04%   |
| Gigabyte X570 AORUS ELITE           | 1        | 1.04%   |
| Gigabyte P41T-D3                    | 1        | 1.04%   |
| Gigabyte H61M-S2PV                  | 1        | 1.04%   |
| Gigabyte H270M-DS3H                 | 1        | 1.04%   |
| Gigabyte H270-Gaming 3              | 1        | 1.04%   |
| Gigabyte H170-D3HP                  | 1        | 1.04%   |
| Gigabyte H110N-CF                   | 1        | 1.04%   |
| Gigabyte G31M-ES2C                  | 1        | 1.04%   |
| Gigabyte E3000N                     | 1        | 1.04%   |
| Gigabyte C246M-WU4                  | 1        | 1.04%   |
| Gigabyte B450M S2H                  | 1        | 1.04%   |
| Gigabyte B450 I AORUS PRO WIFI      | 1        | 1.04%   |
| Gigabyte B365 HD3                   | 1        | 1.04%   |
| Gigabyte 970A-DS3P                  | 1        | 1.04%   |
| Fujitsu ESPRIMO E710                | 1        | 1.04%   |
| ECS G41T-M9                         | 1        | 1.04%   |
| Dell Vostro 3667                    | 1        | 1.04%   |
| Dell Precision T1700                | 1        | 1.04%   |
| Dell PowerEdge T20                  | 1        | 1.04%   |
| Dell OptiPlex 990                   | 1        | 1.04%   |
| Dell OptiPlex 9020                  | 1        | 1.04%   |
| Dell OptiPlex 9010                  | 1        | 1.04%   |
| Dell OptiPlex 780                   | 1        | 1.04%   |
| Dell Inspiron 3891                  | 1        | 1.04%   |
| ASUS Z170-P                         | 1        | 1.04%   |
| ASUS ROG STRIX Z390-E GAMING        | 1        | 1.04%   |
| ASUS ROG STRIX Z370-E GAMING        | 1        | 1.04%   |
| ASUS ROG STRIX X570-E GAMING        | 1        | 1.04%   |
| ASUS ROG Strix GA35DX_G35DX         | 1        | 1.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS ROG             | 5        | 5.21%   |
| ASUS PRIME           | 5        | 5.21%   |
| Dell OptiPlex        | 4        | 4.17%   |
| HP EliteDesk         | 3        | 3.13%   |
| ASUS TUF             | 2        | 2.08%   |
| ASUS P8Z77-V         | 2        | 2.08%   |
| Unknown              | 2        | 2.08%   |
| Quanta 120-1135      | 1        | 1.04%   |
| Pegatron IPM41-D3    | 1        | 1.04%   |
| Pegatron Compaq      | 1        | 1.04%   |
| Pegatron AY627AA-ABA | 1        | 1.04%   |
| MSI MS-7D25          | 1        | 1.04%   |
| MSI MS-7B86          | 1        | 1.04%   |
| MSI MS-7A33          | 1        | 1.04%   |
| MSI MS-7816          | 1        | 1.04%   |
| MSI MS-7758          | 1        | 1.04%   |
| Medion H61H2-LM3     | 1        | 1.04%   |
| Lenovo IdeaCentre    | 1        | 1.04%   |
| Koloe Thurley        | 1        | 1.04%   |
| Intel X58            | 1        | 1.04%   |
| Intel H81            | 1        | 1.04%   |
| Intel DH77EB         | 1        | 1.04%   |
| Intel DG41TY         | 1        | 1.04%   |
| Intel DCP847SKE      | 1        | 1.04%   |
| HP Z230              | 1        | 1.04%   |
| HP ProDesk           | 1        | 1.04%   |
| HP Pavilion          | 1        | 1.04%   |
| HP 844C              | 1        | 1.04%   |
| Gigabyte Z77X-UD3H   | 1        | 1.04%   |
| Gigabyte Z77N-WIFI   | 1        | 1.04%   |
| Gigabyte Z390        | 1        | 1.04%   |
| Gigabyte X58A-UD5    | 1        | 1.04%   |
| Gigabyte X570        | 1        | 1.04%   |
| Gigabyte P41T-D3     | 1        | 1.04%   |
| Gigabyte H61M-S2PV   | 1        | 1.04%   |
| Gigabyte H270M-DS3H  | 1        | 1.04%   |
| Gigabyte H270-Gaming | 1        | 1.04%   |
| Gigabyte H170-D3HP   | 1        | 1.04%   |
| Gigabyte H110N-CF    | 1        | 1.04%   |
| Gigabyte G31M-ES2C   | 1        | 1.04%   |
| Gigabyte E3000N      | 1        | 1.04%   |
| Gigabyte C246M-WU4   | 1        | 1.04%   |
| Gigabyte B450M       | 1        | 1.04%   |
| Gigabyte B450        | 1        | 1.04%   |
| Gigabyte B365        | 1        | 1.04%   |
| Gigabyte 970A-DS3P   | 1        | 1.04%   |
| Fujitsu ESPRIMO      | 1        | 1.04%   |
| ECS G41T-M9          | 1        | 1.04%   |
| Dell Vostro          | 1        | 1.04%   |
| Dell Precision       | 1        | 1.04%   |
| Dell PowerEdge       | 1        | 1.04%   |
| Dell Inspiron        | 1        | 1.04%   |
| ASUS Z170-P          | 1        | 1.04%   |
| ASUS Q170M-C         | 1        | 1.04%   |
| ASUS P8Z68-M         | 1        | 1.04%   |
| ASUS P8H61-M         | 1        | 1.04%   |
| ASUS P7H55-M         | 1        | 1.04%   |
| ASUS P6-P8H61E       | 1        | 1.04%   |
| ASUS P5VD2-VM        | 1        | 1.04%   |
| ASUS P5Q             | 1        | 1.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 14       | 14.58%  |
| 2021 | 12       | 12.5%   |
| 2012 | 10       | 10.42%  |
| 2017 | 8        | 8.33%   |
| 2013 | 8        | 8.33%   |
| 2018 | 7        | 7.29%   |
| 2010 | 7        | 7.29%   |
| 2016 | 6        | 6.25%   |
| 2014 | 5        | 5.21%   |
| 2009 | 5        | 5.21%   |
| 2020 | 4        | 4.17%   |
| 2015 | 3        | 3.13%   |
| 2011 | 3        | 3.13%   |
| 2007 | 3        | 3.13%   |
| 2008 | 1        | 1.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 96       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 96       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 26       | 27.08%  |
| 16.01-24.0  | 25       | 26.04%  |
| 4.01-8.0    | 17       | 17.71%  |
| 32.01-64.0  | 17       | 17.71%  |
| 64.01-256.0 | 4        | 4.17%   |
| 2.01-3.0    | 3        | 3.13%   |
| 24.01-32.0  | 2        | 2.08%   |
| 1.01-2.0    | 1        | 1.04%   |
| 0.51-1.0    | 1        | 1.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 39       | 40.21%  |
| 0.51-1.0  | 30       | 30.93%  |
| 1.01-2.0  | 23       | 23.71%  |
| 2.01-3.0  | 3        | 3.09%   |
| 3.01-4.0  | 1        | 1.03%   |
| 8.01-16.0 | 1        | 1.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 40       | 40.82%  |
| 2      | 29       | 29.59%  |
| 4      | 9        | 9.18%   |
| 3      | 8        | 8.16%   |
| 0      | 5        | 5.1%    |
| 5      | 4        | 4.08%   |
| 6      | 2        | 2.04%   |
| 7      | 1        | 1.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 63       | 65.63%  |
| Yes       | 33       | 34.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 94       | 97.92%  |
| No        | 2        | 2.08%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 66       | 68.75%  |
| Yes       | 30       | 31.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 66       | 68.75%  |
| Yes       | 30       | 31.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Russia      | 16       | 16.67%  |
| USA         | 15       | 15.63%  |
| Hungary     | 7        | 7.29%   |
| Ukraine     | 5        | 5.21%   |
| Spain       | 5        | 5.21%   |
| Poland      | 5        | 5.21%   |
| Germany     | 5        | 5.21%   |
| India       | 4        | 4.17%   |
| Canada      | 4        | 4.17%   |
| Italy       | 3        | 3.13%   |
| China       | 3        | 3.13%   |
| Brazil      | 3        | 3.13%   |
| UK          | 2        | 2.08%   |
| South Korea | 2        | 2.08%   |
| Romania     | 2        | 2.08%   |
| France      | 2        | 2.08%   |
| Australia   | 2        | 2.08%   |
| Vietnam     | 1        | 1.04%   |
| Turkey      | 1        | 1.04%   |
| Thailand    | 1        | 1.04%   |
| Taiwan      | 1        | 1.04%   |
| Philippines | 1        | 1.04%   |
| Peru        | 1        | 1.04%   |
| Norway      | 1        | 1.04%   |
| Kazakhstan  | 1        | 1.04%   |
| Greece      | 1        | 1.04%   |
| Finland     | 1        | 1.04%   |
| Denmark     | 1        | 1.04%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                          | Desktops | Percent |
|-------------------------------|----------|---------|
| St Petersburg                 | 3        | 3%      |
| Surgut                        | 2        | 2%      |
| Myrtle Beach                  | 2        | 2%      |
| Kharkiv                       | 2        | 2%      |
| Barnaul                       | 2        | 2%      |
| Yunlin                        | 1        | 1%      |
| Warsaw                        | 1        | 1%      |
| Tiruchi                       | 1        | 1%      |
| Szombathely                   | 1        | 1%      |
| Szeged                        | 1        | 1%      |
| SzÃ©kesfehÃ©rvÃ¡r       | 1        | 1%      |
| Suceava                       | 1        | 1%      |
| Stavropol                     | 1        | 1%      |
| Sparta                        | 1        | 1%      |
| Spalice                       | 1        | 1%      |
| Sopron                        | 1        | 1%      |
| Songpa-gu                     | 1        | 1%      |
| Smiths Falls                  | 1        | 1%      |
| Seville                       | 1        | 1%      |
| Santa Maria                   | 1        | 1%      |
| San SebastiÃ¡n de los Reyes | 1        | 1%      |
| Rio de Janeiro                | 1        | 1%      |
| Renfrew                       | 1        | 1%      |
| Pilica                        | 1        | 1%      |
| Pforzheim                     | 1        | 1%      |
| Pflugerville                  | 1        | 1%      |
| Perm                          | 1        | 1%      |
| Penza                         | 1        | 1%      |
| Paso Robles                   | 1        | 1%      |
| Paju                          | 1        | 1%      |
| Ourense                       | 1        | 1%      |
| Ormond Beach                  | 1        | 1%      |
| Novosibirsk                   | 1        | 1%      |
| New Delhi                     | 1        | 1%      |
| Myski                         | 1        | 1%      |
| Moscow                        | 1        | 1%      |
| Montreal                      | 1        | 1%      |
| Midlothian                    | 1        | 1%      |
| Melbourne                     | 1        | 1%      |
| Malonikolayevka               | 1        | 1%      |
| Maglod                        | 1        | 1%      |
| Luton                         | 1        | 1%      |
| Lima                          | 1        | 1%      |
| Lehrte                        | 1        | 1%      |
| Kremenchug                    | 1        | 1%      |
| Kozani                        | 1        | 1%      |
| Kostroma                      | 1        | 1%      |
| Katowice                      | 1        | 1%      |
| Junction City                 | 1        | 1%      |
| Jelenia Góra                 | 1        | 1%      |
| Jelenia GÃ³ra               | 1        | 1%      |
| Imperial                      | 1        | 1%      |
| Helsinki                      | 1        | 1%      |
| Hayfork                       | 1        | 1%      |
| Hanoi                         | 1        | 1%      |
| Hangzhou                      | 1        | 1%      |
| Gyomro                        | 1        | 1%      |
| Guangzhou                     | 1        | 1%      |
| Greater Sudbury               | 1        | 1%      |
| Genille                       | 1        | 1%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 35       | 49     | 21.08%  |
| WDC                 | 29       | 41     | 17.47%  |
| Samsung Electronics | 28       | 33     | 16.87%  |
| Crucial             | 12       | 17     | 7.23%   |
| Toshiba             | 11       | 14     | 6.63%   |
| Kingston            | 9        | 11     | 5.42%   |
| SK Hynix            | 4        | 6      | 2.41%   |
| GOODRAM             | 4        | 4      | 2.41%   |
| A-DATA Technology   | 4        | 4      | 2.41%   |
| Phison              | 3        | 3      | 1.81%   |
| Patriot             | 3        | 3      | 1.81%   |
| Intel               | 3        | 3      | 1.81%   |
| Hitachi             | 3        | 4      | 1.81%   |
| HGST                | 3        | 3      | 1.81%   |
| XPG                 | 2        | 2      | 1.2%    |
| SanDisk             | 2        | 2      | 1.2%    |
| OCZ                 | 2        | 2      | 1.2%    |
| Gigabyte Technology | 2        | 3      | 1.2%    |
| SPCC                | 1        | 1      | 0.6%    |
| PNY                 | 1        | 1      | 0.6%    |
| PLEXTOR             | 1        | 1      | 0.6%    |
| Mushkin             | 1        | 1      | 0.6%    |
| Lite-On             | 1        | 1      | 0.6%    |
| KingSpec            | 1        | 1      | 0.6%    |
| Apacer              | 1        | 1      | 0.6%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Seagate ST4000DM004-2CV104 4TB          | 3        | 1.6%    |
| Seagate ST2000DM008-2FR102 2TB          | 3        | 1.6%    |
| Seagate ST1000DM010-2EP102 1TB          | 3        | 1.6%    |
| Samsung SSD 850 EVO 250GB               | 3        | 1.6%    |
| Kingston SA400S37120G 120GB             | 3        | 1.6%    |
| Crucial CT500MX500SSD1 500GB            | 3        | 1.6%    |
| XPG GAMMIX S11 Pro 256GB                | 2        | 1.06%   |
| WDC WDS240G2G0A-00JH30 240GB            | 2        | 1.06%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 2        | 1.06%   |
| WDC WD20PURZ-85GU6Y0 2TB                | 2        | 1.06%   |
| Toshiba HDWD110 1TB                     | 2        | 1.06%   |
| Toshiba DT01ACA050 500GB                | 2        | 1.06%   |
| SK Hynix BC501 HFM128GDJTNG-8310A 128GB | 2        | 1.06%   |
| Seagate ST3500413AS 500GB               | 2        | 1.06%   |
| Seagate ST3320418AS 320GB               | 2        | 1.06%   |
| Seagate ST31000528AS 1TB                | 2        | 1.06%   |
| Seagate ST1000DM003-1ER162 1TB          | 2        | 1.06%   |
| Samsung SSD 970 EVO Plus 1TB            | 2        | 1.06%   |
| Samsung SSD 970 EVO 250GB               | 2        | 1.06%   |
| Samsung SSD 860 EVO 500GB               | 2        | 1.06%   |
| Samsung HD322HJ 320GB                   | 2        | 1.06%   |
| GOODRAM SSDPR-CL100-120-G2 120GB        | 2        | 1.06%   |
| Crucial CT256MX100SSD1 256GB            | 2        | 1.06%   |
| Crucial CT240BX500SSD1 240GB            | 2        | 1.06%   |
| Crucial CT120BX500SSD1 120GB            | 2        | 1.06%   |
| WDC WDS500G2B0C-00PXH0 500GB            | 1        | 0.53%   |
| WDC WDS500G2B0B-00YS70 500GB            | 1        | 0.53%   |
| WDC WDS500G2B0A-00SM50 500GB            | 1        | 0.53%   |
| WDC WDS250G1B0A-00H9H0 250GB            | 1        | 0.53%   |
| WDC WDS120G2G0A-00JH30 120GB            | 1        | 0.53%   |
| WDC WDS100T2B0A-00SM50 1TB              | 1        | 0.53%   |
| WDC WDBA3V0010BNC-WRSN 1TB              | 1        | 0.53%   |
| WDC WD5000LPLX-66ZNTT0 500GB            | 1        | 0.53%   |
| WDC WD5000AZLX-00CL5A0 500GB            | 1        | 0.53%   |
| WDC WD5000AAKX-75U6AA0 500GB            | 1        | 0.53%   |
| WDC WD5000AAKS-22A7B0 500GB             | 1        | 0.53%   |
| WDC WD40EZRZ-00GXCB0 4TB                | 1        | 0.53%   |
| WDC WD40EFRX-68N32N0 4TB                | 1        | 0.53%   |
| WDC WD400JB-00ENA0 40GB                 | 1        | 0.53%   |
| WDC WD4004FZWX-00GBGB0 4TB              | 1        | 0.53%   |
| WDC WD3200BPVT-22ZEST0 320GB            | 1        | 0.53%   |
| WDC WD3200AAJS-22B4A0 320GB             | 1        | 0.53%   |
| WDC WD3003FZEX-00Z4SA0 3TB              | 1        | 0.53%   |
| WDC WD2500AAKX-75U6AA0 250GB            | 1        | 0.53%   |
| WDC WD2500AAKX-073CA1 250GB             | 1        | 0.53%   |
| WDC WD1600BEVT-75ZCT2 160GB             | 1        | 0.53%   |
| WDC WD1600BEVT-22ZCT0 160GB             | 1        | 0.53%   |
| WDC WD10EZEX-60ZF5A0 1TB                | 1        | 0.53%   |
| WDC WD10EZEX-60WN4A0 1TB                | 1        | 0.53%   |
| WDC WD10EZEX-08M2NA0 1TB                | 1        | 0.53%   |
| WDC WD10EZEX-00KUWA0 1TB                | 1        | 0.53%   |
| WDC WD10EZEX-00BN5A0 1TB                | 1        | 0.53%   |
| WDC WD10EARS-003BB1 1TB                 | 1        | 0.53%   |
| Toshiba Q300 480GB                      | 1        | 0.53%   |
| Toshiba MK1655GSX 160GB                 | 1        | 0.53%   |
| Toshiba MD04ACA400 4TB                  | 1        | 0.53%   |
| Toshiba HDWE160 6TB                     | 1        | 0.53%   |
| Toshiba DT01ACA300 3TB                  | 1        | 0.53%   |
| Toshiba DT01ACA200 2TB                  | 1        | 0.53%   |
| Toshiba DT01ACA100 1TB                  | 1        | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 35       | 46     | 44.3%   |
| WDC                 | 22       | 28     | 27.85%  |
| Toshiba             | 10       | 13     | 12.66%  |
| Samsung Electronics | 6        | 6      | 7.59%   |
| Hitachi             | 3        | 4      | 3.8%    |
| HGST                | 3        | 3      | 3.8%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 16       | 17     | 23.53%  |
| Crucial             | 12       | 16     | 17.65%  |
| Kingston            | 7        | 8      | 10.29%  |
| WDC                 | 6        | 10     | 8.82%   |
| GOODRAM             | 4        | 4      | 5.88%   |
| A-DATA Technology   | 4        | 4      | 5.88%   |
| Patriot             | 3        | 3      | 4.41%   |
| SanDisk             | 2        | 2      | 2.94%   |
| OCZ                 | 2        | 2      | 2.94%   |
| Intel               | 2        | 2      | 2.94%   |
| Gigabyte Technology | 2        | 3      | 2.94%   |
| Toshiba             | 1        | 1      | 1.47%   |
| SPCC                | 1        | 1      | 1.47%   |
| SK Hynix            | 1        | 1      | 1.47%   |
| PNY                 | 1        | 1      | 1.47%   |
| PLEXTOR             | 1        | 1      | 1.47%   |
| Lite-On             | 1        | 1      | 1.47%   |
| KingSpec            | 1        | 1      | 1.47%   |
| Apacer              | 1        | 1      | 1.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 63       | 100    | 45%     |
| SSD  | 55       | 79     | 39.29%  |
| NVMe | 22       | 32     | 15.71%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 86       | 179    | 79.63%  |
| NVMe | 22       | 32     | 20.37%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 73       | 113    | 59.84%  |
| 0.51-1.0   | 23       | 31     | 18.85%  |
| 1.01-2.0   | 14       | 15     | 11.48%  |
| 3.01-4.0   | 7        | 14     | 5.74%   |
| 2.01-3.0   | 4        | 5      | 3.28%   |
| 4.01-10.0  | 1        | 1      | 0.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 61       | 61.62%  |
| 101-250    | 21       | 21.21%  |
| 251-500    | 9        | 9.09%   |
| 501-1000   | 4        | 4.04%   |
| 51-100     | 3        | 3.03%   |
| 21-50      | 1        | 1.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 95       | 98.96%  |
| 21-50   | 1        | 1.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST3500413AS 500GB           | 2        | 2      | 6.67%   |
| Seagate ST3320418AS 320GB           | 2        | 2      | 6.67%   |
| Seagate ST31000528AS 1TB            | 2        | 3      | 6.67%   |
| WDC WD5000AZLX-00CL5A0 500GB        | 1        | 1      | 3.33%   |
| WDC WD5000AAKS-22A7B0 500GB         | 1        | 1      | 3.33%   |
| WDC WD400JB-00ENA0 40GB             | 1        | 1      | 3.33%   |
| WDC WD3200AAJS-22B4A0 320GB         | 1        | 1      | 3.33%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 1        | 1      | 3.33%   |
| WDC WD10EZEX-08M2NA0 1TB            | 1        | 1      | 3.33%   |
| WDC WD10EARS-003BB1 1TB             | 1        | 1      | 3.33%   |
| Toshiba MD04ACA400 4TB              | 1        | 1      | 3.33%   |
| Toshiba DT01ACA100 1TB              | 1        | 3      | 3.33%   |
| Toshiba DT01ABA300 3TB              | 1        | 1      | 3.33%   |
| Seagate ST380211AS 80GB             | 1        | 1      | 3.33%   |
| Seagate ST3500418AS 500GB           | 1        | 1      | 3.33%   |
| Seagate ST3250310AS 250GB           | 1        | 1      | 3.33%   |
| Seagate ST3160812AS 160GB           | 1        | 1      | 3.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1        | 1      | 3.33%   |
| Samsung Electronics SSD 870 EVO 1TB | 1        | 1      | 3.33%   |
| Samsung Electronics HD322HJ 320GB   | 1        | 1      | 3.33%   |
| Samsung Electronics HD250HJ 250GB   | 1        | 1      | 3.33%   |
| Kingston SV200S3128G 128GB          | 1        | 1      | 3.33%   |
| Kingston SMS200S3120G 120GB         | 1        | 1      | 3.33%   |
| Hitachi HTS541680J9SA00 80GB        | 1        | 2      | 3.33%   |
| Hitachi HDT721010SLA360 1TB         | 1        | 1      | 3.33%   |
| Crucial CT240M500SSD1 240GB         | 1        | 1      | 3.33%   |
| Crucial CT1050MX300SSD1 1TB         | 1        | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 12     | 35.71%  |
| WDC                 | 7        | 7      | 25%     |
| Samsung Electronics | 3        | 3      | 10.71%  |
| Toshiba             | 2        | 5      | 7.14%   |
| Kingston            | 2        | 2      | 7.14%   |
| Hitachi             | 2        | 3      | 7.14%   |
| Crucial             | 2        | 2      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 12     | 43.48%  |
| WDC                 | 7        | 7      | 30.43%  |
| Toshiba             | 2        | 5      | 8.7%    |
| Samsung Electronics | 2        | 2      | 8.7%    |
| Hitachi             | 2        | 3      | 8.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 21       | 29     | 80.77%  |
| SSD  | 5        | 5      | 19.23%  |

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
| Works    | 81       | 176    | 75.7%   |
| Malfunc  | 25       | 34     | 23.36%  |
| Detected | 1        | 1      | 0.93%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 69       | 53.49%  |
| AMD                         | 24       | 18.6%   |
| Samsung Electronics         | 8        | 6.2%    |
| SK Hynix                    | 3        | 2.33%   |
| Phison Electronics          | 3        | 2.33%   |
| Marvell Technology Group    | 3        | 2.33%   |
| JMicron Technology          | 3        | 2.33%   |
| ASMedia Technology          | 3        | 2.33%   |
| Sandisk                     | 2        | 1.55%   |
| Nvidia                      | 2        | 1.55%   |
| Kingston Technology Company | 2        | 1.55%   |
| ADATA Technology            | 2        | 1.55%   |
| VIA Technologies            | 1        | 0.78%   |
| Silicon Motion              | 1        | 0.78%   |
| Seagate Technology          | 1        | 0.78%   |
| Micron/Crucial Technology   | 1        | 0.78%   |
| Broadcom / LSI              | 1        | 0.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 19       | 12.42%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9        | 5.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8        | 5.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 5.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7        | 4.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 3.92%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 3.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6        | 3.92%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 3.27%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 4        | 2.61%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 2.61%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 1.96%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 1.96%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 2        | 1.31%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 2        | 1.31%   |
| Phison E12 NVMe Controller                                                              | 2        | 1.31%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 1.31%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 1.31%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 1.31%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 1.31%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 1.31%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.31%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.31%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2        | 1.31%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.65%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 1        | 0.65%   |
| SK Hynix Gold P31 SSD                                                                   | 1        | 0.65%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.65%   |
| Seagate FireCuda 520 SSD                                                                | 1        | 0.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.65%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.65%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.65%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.65%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1        | 0.65%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1        | 0.65%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.65%   |
| JMicron JMB361 AHCI/IDE                                                                 | 1        | 0.65%   |
| Intel SSD 660P Series                                                                   | 1        | 0.65%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 0.65%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 1        | 0.65%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 1        | 0.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 1        | 0.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1        | 0.65%   |
| Intel 82801HB (ICH8) 4 port SATA Controller [AHCI mode]                                 | 1        | 0.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 1        | 0.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 0.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 0.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 0.65%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 0.65%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.65%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 0.65%   |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                                      | 1        | 0.65%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 71       | 58.68%  |
| NVMe | 22       | 18.18%  |
| IDE  | 20       | 16.53%  |
| RAID | 7        | 5.79%   |
| SCSI | 1        | 0.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 69       | 71.88%  |
| AMD    | 27       | 28.13%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 3.13%   |
| Intel Pentium CPU G860 @ 3.00GHz            | 2        | 2.08%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 2.08%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 2.08%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 2        | 2.08%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 2.08%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 2.08%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 2.08%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2        | 2.08%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 2.08%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 2.08%   |
| Intel Xeon E-2136 CPU @ 3.30GHz             | 1        | 1.04%   |
| Intel Xeon CPU X5647 @ 2.93GHz              | 1        | 1.04%   |
| Intel Xeon CPU X3470 @ 2.93GHz              | 1        | 1.04%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 1.04%   |
| Intel Xeon CPU E5504 @ 2.00GHz              | 1        | 1.04%   |
| Intel Xeon CPU E31245 @ 3.30GHz             | 1        | 1.04%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz         | 1        | 1.04%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz        | 1        | 1.04%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1        | 1.04%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 1.04%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1        | 1.04%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1        | 1.04%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 1        | 1.04%   |
| Intel Pentium Dual-Core CPU E6500 @         | 1        | 1.04%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 1.04%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 1.04%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1        | 1.04%   |
| Intel Core i9-9900 CPU @ 3.10GHz            | 1        | 1.04%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 1.04%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 1.04%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.04%   |
| Intel Core i7-6700T CPU @ 2.80GHz           | 1        | 1.04%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 1.04%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.04%   |
| Intel Core i7 CPU                           | 1        | 1.04%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 1.04%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 1.04%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 1.04%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 1.04%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 1.04%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.04%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 1.04%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.04%   |
| Intel Core i5-3475S CPU @ 2.90GHz           | 1        | 1.04%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.04%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 1.04%   |
| Intel Core i5-2405S CPU @ 2.50GHz           | 1        | 1.04%   |
| Intel Core i5-2400S CPU @ 2.50GH            | 1        | 1.04%   |
| Intel Core i5-10500 CPU @ 3.10GHz           | 1        | 1.04%   |
| Intel Core i3-6320 CPU @ 3.90GHz            | 1        | 1.04%   |
| Intel Core i3-6300 CPU @ 3.80GHz            | 1        | 1.04%   |
| Intel Core i3-5010U CPU @ 2.10GHz           | 1        | 1.04%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 1.04%   |
| Intel Core i3-3225 CPU @ 3.30GHz            | 1        | 1.04%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 1.04%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 1        | 1.04%   |
| Intel Core 2 Quad CPU                       | 1        | 1.04%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 1.04%   |
| Intel Core 2 Duo CPU E4700 @ 2.60GHz        | 1        | 1.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 19       | 19.79%  |
| Intel Xeon              | 11       | 11.46%  |
| Intel Core i7           | 11       | 11.46%  |
| AMD Ryzen 7             | 7        | 7.29%   |
| AMD Ryzen 5             | 7        | 7.29%   |
| Intel Core i3           | 6        | 6.25%   |
| Intel Pentium Dual-Core | 4        | 4.17%   |
| Intel Core 2 Quad       | 4        | 4.17%   |
| Intel Pentium           | 3        | 3.13%   |
| Intel Core 2 Duo        | 3        | 3.13%   |
| Other                   | 2        | 2.08%   |
| Intel Celeron           | 2        | 2.08%   |
| AMD Ryzen 9             | 2        | 2.08%   |
| AMD Ryzen 3             | 2        | 2.08%   |
| AMD Phenom II X4        | 2        | 2.08%   |
| Intel Pentium Dual      | 1        | 1.04%   |
| Intel Core i9           | 1        | 1.04%   |
| Intel Core 2            | 1        | 1.04%   |
| Intel Atom              | 1        | 1.04%   |
| AMD Ryzen Threadripper  | 1        | 1.04%   |
| AMD FX                  | 1        | 1.04%   |
| AMD E2                  | 1        | 1.04%   |
| AMD E                   | 1        | 1.04%   |
| AMD Athlon II X4        | 1        | 1.04%   |
| AMD Athlon II X2        | 1        | 1.04%   |
| AMD A10                 | 1        | 1.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 40       | 41.67%  |
| 2       | 19       | 19.79%  |
| 6       | 10       | 10.42%  |
| Unknown | 7        | 7.29%   |
| 16      | 6        | 6.25%   |
| 8       | 6        | 6.25%   |
| 12      | 4        | 4.17%   |
| 24      | 2        | 2.08%   |
| 64      | 1        | 1.04%   |
| 14      | 1        | 1.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 96       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 59       | 61.46%  |
| 2       | 30       | 31.25%  |
| Unknown | 7        | 7.29%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Skylake     | 10       | 10.42%  |
| Haswell     | 10       | 10.42%  |
| Penryn      | 9        | 9.38%   |
| KabyLake    | 9        | 9.38%   |
| IvyBridge   | 9        | 9.38%   |
| SandyBridge | 8        | 8.33%   |
| Zen 2       | 6        | 6.25%   |
| Zen         | 5        | 5.21%   |
| Zen+        | 4        | 4.17%   |
| Zen 3       | 4        | 4.17%   |
| K10         | 4        | 4.17%   |
| Core        | 4        | 4.17%   |
| Nehalem     | 3        | 3.13%   |
| Westmere    | 2        | 2.08%   |
| Piledriver  | 2        | 2.08%   |
| Unknown     | 2        | 2.08%   |
| Jaguar      | 1        | 1.04%   |
| CometLake   | 1        | 1.04%   |
| Broadwell   | 1        | 1.04%   |
| Bonnell     | 1        | 1.04%   |
| Bobcat      | 1        | 1.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 38       | 38%     |
| Intel  | 36       | 36%     |
| AMD    | 26       | 26%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 530                                                       | 6        | 5.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 4.95%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 4.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 3.96%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 2.97%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 2.97%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 2.97%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 2.97%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 2.97%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 2.97%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 1.98%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.98%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 1.98%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 2        | 1.98%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 1.98%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 1.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1.98%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 1.98%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 2        | 1.98%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.99%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.99%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.99%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.99%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 0.99%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.99%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.99%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 0.99%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.99%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.99%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.99%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 0.99%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 0.99%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 0.99%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 0.99%   |
| Nvidia GF119 [GeForce GT 625 OEM]                                           | 1        | 0.99%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.99%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 0.99%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 0.99%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 0.99%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 0.99%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 1        | 0.99%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 1        | 0.99%   |
| Nvidia G72 [GeForce 7300 LE]                                                | 1        | 0.99%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 1        | 0.99%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 0.99%   |
| Intel HD Graphics 630                                                       | 1        | 0.99%   |
| Intel HD Graphics 5500                                                      | 1        | 0.99%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 0.99%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 0.99%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 1        | 0.99%   |
| Intel AlderLake-S GT1                                                       | 1        | 0.99%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1        | 0.99%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 0.99%   |
| AMD Wrestler [Radeon HD 6320]                                               | 1        | 0.99%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 0.99%   |
| AMD Trinity [Radeon HD 7660D]                                               | 1        | 0.99%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 1        | 0.99%   |
| AMD RS880 [Radeon HD 4250]                                                  | 1        | 0.99%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 1        | 0.99%   |
| AMD Redwood PRO [Radeon HD 5550/5570/5630/6510/6610/7570]                   | 1        | 0.99%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 37       | 37.76%  |
| 1 x Intel      | 30       | 30.61%  |
| 1 x AMD        | 24       | 24.49%  |
| 2 x Intel      | 3        | 3.06%   |
| Intel + Nvidia | 2        | 2.04%   |
| 2 x AMD        | 1        | 1.02%   |
| Intel + AMD    | 1        | 1.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 62       | 63.92%  |
| Proprietary | 32       | 32.99%  |
| Unknown     | 3        | 3.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 44       | 44.9%   |
| 3.01-4.0   | 13       | 13.27%  |
| 1.01-2.0   | 13       | 13.27%  |
| 0.51-1.0   | 10       | 10.2%   |
| 7.01-8.0   | 9        | 9.18%   |
| 0.01-0.5   | 7        | 7.14%   |
| 5.01-6.0   | 2        | 2.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 12       | 13.79%  |
| Goldstar             | 11       | 12.64%  |
| Dell                 | 10       | 11.49%  |
| BenQ                 | 9        | 10.34%  |
| AOC                  | 7        | 8.05%   |
| Acer                 | 6        | 6.9%    |
| Philips              | 5        | 5.75%   |
| Hewlett-Packard      | 5        | 5.75%   |
| Ancor Communications | 5        | 5.75%   |
| Sony                 | 3        | 3.45%   |
| ASUSTek Computer     | 3        | 3.45%   |
| Lenovo               | 2        | 2.3%    |
| Fujitsu Siemens      | 2        | 2.3%    |
| Westinghouse         | 1        | 1.15%   |
| Vestel Elektronik    | 1        | 1.15%   |
| SGT                  | 1        | 1.15%   |
| NEC Computers        | 1        | 1.15%   |
| Iiyama               | 1        | 1.15%   |
| FND                  | 1        | 1.15%   |
| Denver               | 1        | 1.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2        | 2.22%   |
| Ancor Communications MX27AQ ACI27A5 2560x1440 600x340mm 27.2-inch      | 2        | 2.22%   |
| Westinghouse LCM-19w4 WDE1904 1440x900 410x260mm 19.1-inch             | 1        | 1.11%   |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 530x300mm 24.0-inch     | 1        | 1.11%   |
| Sony TV SNYEE01 1920x1080                                              | 1        | 1.11%   |
| Sony TV SNY9C01 1360x768                                               | 1        | 1.11%   |
| Sony SDM-S75D/F/N SNY3800 1280x1024 340x270mm 17.1-inch                | 1        | 1.11%   |
| SGT YSD SGT1700 1280x1024 380x210mm 17.1-inch                          | 1        | 1.11%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch      | 1        | 1.11%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 520x290mm 23.4-inch      | 1        | 1.11%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch    | 1        | 1.11%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                       | 1        | 1.11%   |
| Samsung Electronics SyncMaster SAM0373 1680x1050 440x300mm 21.0-inch   | 1        | 1.11%   |
| Samsung Electronics SyncMaster SAM027D 1680x1050 430x270mm 20.0-inch   | 1        | 1.11%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 480x270mm 21.7-inch     | 1        | 1.11%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch      | 1        | 1.11%   |
| Samsung Electronics S24C450 SAM09CB 1920x1080 530x300mm 24.0-inch      | 1        | 1.11%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch       | 1        | 1.11%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 1110x620mm 50.1-inch | 1        | 1.11%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 530x300mm 24.0-inch     | 1        | 1.11%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 700x390mm 31.5-inch      | 1        | 1.11%   |
| Samsung Electronics C24FG7x SAM0E44 1920x1080 530x300mm 24.0-inch      | 1        | 1.11%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 1        | 1.11%   |
| Philips PHL 278E1 PHLC217 3840x2160 600x340mm 27.2-inch                | 1        | 1.11%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                 | 1        | 1.11%   |
| Philips 248CLH PHLC088 1920x1080 520x290mm 23.4-inch                   | 1        | 1.11%   |
| Philips 220E PHLC02E 1920x1080 470x260mm 21.1-inch                     | 1        | 1.11%   |
| Philips 190V PHL0081 1440x900 400x250mm 18.6-inch                      | 1        | 1.11%   |
| NEC Computers LCD1770VX NEC6696 1280x1024 340x270mm 17.1-inch          | 1        | 1.11%   |
| Lenovo LEN T22i-10 LEN61A9 1920x1080 480x270mm 21.7-inch               | 1        | 1.11%   |
| Lenovo LCD Monitor LEN4000 1920x1080 510x290mm 23.1-inch               | 1        | 1.11%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch                | 1        | 1.11%   |
| Hewlett-Packard Z24n G2 HPN3485 1920x1200 520x320mm 24.0-inch          | 1        | 1.11%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch       | 1        | 1.11%   |
| Hewlett-Packard LCD Monitor HPN3425 1920x1080 540x300mm 24.3-inch      | 1        | 1.11%   |
| Hewlett-Packard 27f HPN354A 1920x1080 600x340mm 27.2-inch              | 1        | 1.11%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch             | 1        | 1.11%   |
| Goldstar W2361 GSM56FB 1920x1080 510x290mm 23.1-inch                   | 1        | 1.11%   |
| Goldstar W1942 GSM4B6F 1440x900 410x260mm 19.1-inch                    | 1        | 1.11%   |
| Goldstar M2280D GSM57B9 1920x1080 480x270mm 21.7-inch                  | 1        | 1.11%   |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch               | 1        | 1.11%   |
| Goldstar LCD Monitor GSM5AB6 1920x1080 480x270mm 21.7-inch             | 1        | 1.11%   |
| Goldstar LCD Monitor GSM5807 1920x1080 480x270mm 21.7-inch             | 1        | 1.11%   |
| Goldstar 700E GSM4317 1280x1024 330x250mm 16.3-inch                    | 1        | 1.11%   |
| Goldstar 2D FHD LG TV GSM59C6 1920x1080 510x290mm 23.1-inch            | 1        | 1.11%   |
| Goldstar 19MB35 GSM4C23 1280x1024 380x300mm 19.1-inch                  | 1        | 1.11%   |
| Fujitsu Siemens L19-8 FUS075B 1280x1024 380x300mm 19.1-inch            | 1        | 1.11%   |
| Fujitsu Siemens A17-2 DVI FUS0620 1280x1024 340x270mm 17.1-inch        | 1        | 1.11%   |
| FND F191WL FND02B8 1440x900 410x260mm 19.1-inch                        | 1        | 1.11%   |
| Denver UXGA-100-C LHC2900 2560x1080 680x280mm 29.0-inch                | 1        | 1.11%   |
| Dell U3415W DELA0A6 3440x1440 800x330mm 34.1-inch                      | 1        | 1.11%   |
| Dell U2515H DELD06F 2560x1440 550x310mm 24.9-inch                      | 1        | 1.11%   |
| Dell U2415 DELA0BA 1920x1200 520x320mm 24.0-inch                       | 1        | 1.11%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                      | 1        | 1.11%   |
| Dell P2418D DELD0C2 2560x1440 530x300mm 24.0-inch                      | 1        | 1.11%   |
| Dell P2311H DEL4067 1920x1080 510x290mm 23.1-inch                      | 1        | 1.11%   |
| Dell P1914S DELF04B 1280x1024 380x300mm 19.1-inch                      | 1        | 1.11%   |
| Dell IN2020M DELF029 1600x900 440x250mm 19.9-inch                      | 1        | 1.11%   |
| Dell E248WFP DELA02D 1920x1200 520x320mm 24.0-inch                     | 1        | 1.11%   |
| Dell E173FP DELA00B 1280x1024 340x270mm 17.1-inch                      | 1        | 1.11%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 39       | 44.83%  |
| 1280x1024 (SXGA)   | 11       | 12.64%  |
| 2560x1440 (QHD)    | 8        | 9.2%    |
| 1440x900 (WXGA+)   | 6        | 6.9%    |
| 1600x900 (HD+)     | 5        | 5.75%   |
| 3840x2160 (4K)     | 4        | 4.6%    |
| 1920x1200 (WUXGA)  | 4        | 4.6%    |
| 1680x1050 (WSXGA+) | 3        | 3.45%   |
| 1366x768 (WXGA)    | 3        | 3.45%   |
| 3440x1440          | 1        | 1.15%   |
| 2560x1080          | 1        | 1.15%   |
| 1920x540           | 1        | 1.15%   |
| 1360x768           | 1        | 1.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 17       | 19.32%  |
| 19      | 13       | 14.77%  |
| 21      | 12       | 13.64%  |
| 27      | 11       | 12.5%   |
| 23      | 10       | 11.36%  |
| 17      | 7        | 7.95%   |
| 18      | 5        | 5.68%   |
| 31      | 3        | 3.41%   |
| Unknown | 3        | 3.41%   |
| 50      | 1        | 1.14%   |
| 42      | 1        | 1.14%   |
| 34      | 1        | 1.14%   |
| 33      | 1        | 1.14%   |
| 29      | 1        | 1.14%   |
| 20      | 1        | 1.14%   |
| 16      | 1        | 1.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 34       | 40.48%  |
| 401-500     | 24       | 28.57%  |
| 351-400     | 7        | 8.33%   |
| 301-350     | 7        | 8.33%   |
| 601-700     | 5        | 5.95%   |
| Unknown     | 3        | 3.57%   |
| 701-800     | 2        | 2.38%   |
| 1001-1500   | 1        | 1.19%   |
| 901-1000    | 1        | 1.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 58       | 69.05%  |
| 16/10 | 13       | 15.48%  |
| 5/4   | 9        | 10.71%  |
| 21/9  | 2        | 2.38%   |
| 4/3   | 1        | 1.19%   |
| 3/2   | 1        | 1.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 31       | 35.63%  |
| 151-200        | 18       | 20.69%  |
| 301-350        | 11       | 12.64%  |
| 141-150        | 8        | 9.2%    |
| 251-300        | 7        | 8.05%   |
| 351-500        | 5        | 5.75%   |
| Unknown        | 3        | 3.45%   |
| 121-130        | 2        | 2.3%    |
| More than 1000 | 1        | 1.15%   |
| 501-1000       | 1        | 1.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 58       | 66.67%  |
| 101-120 | 20       | 22.99%  |
| 121-160 | 3        | 3.45%   |
| Unknown | 3        | 3.45%   |
| 161-240 | 2        | 2.3%    |
| 1-50    | 1        | 1.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 78       | 80.41%  |
| 0     | 10       | 10.31%  |
| 2     | 8        | 8.25%   |
| 3     | 1        | 1.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 60       | 50.85%  |
| Intel                    | 38       | 32.2%   |
| Qualcomm Atheros         | 8        | 6.78%   |
| Broadcom                 | 3        | 2.54%   |
| Ralink Technology        | 2        | 1.69%   |
| Ralink                   | 2        | 1.69%   |
| TP-Link                  | 1        | 0.85%   |
| NetGear                  | 1        | 0.85%   |
| Microchip Technology     | 1        | 0.85%   |
| MediaTek                 | 1        | 0.85%   |
| Marvell Technology Group | 1        | 0.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 47       | 35.34%  |
| Intel I211 Gigabit Network Connection                                         | 8        | 6.02%   |
| Intel Ethernet Connection I217-LM                                             | 6        | 4.51%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4        | 3.01%   |
| Intel Wi-Fi 6 AX200                                                           | 4        | 3.01%   |
| Intel 82579V Gigabit Network Connection                                       | 4        | 3.01%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 3        | 2.26%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 2.26%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 2.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 1.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 1.5%    |
| Ralink RT5370 Wireless Adapter                                                | 2        | 1.5%    |
| Intel Wireless-AC 9260                                                        | 2        | 1.5%    |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 1.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 1.5%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 1        | 0.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.75%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.75%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 1        | 0.75%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1        | 0.75%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.75%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 0.75%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1        | 0.75%   |
| Ralink RT2500 Wireless 802.11bg                                               | 1        | 0.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 0.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 0.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 0.75%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1        | 0.75%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 0.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.75%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.75%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]              | 1        | 0.75%   |
| Microchip HTC Hub Controller                                                  | 1        | 0.75%   |
| MediaTek 802.11ac Wireless LAN Card                                           | 1        | 0.75%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.75%   |
| Intel Wireless 7265                                                           | 1        | 0.75%   |
| Intel Wireless 7260                                                           | 1        | 0.75%   |
| Intel I210 Gigabit Network Connection                                         | 1        | 0.75%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.75%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 0.75%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 0.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1        | 0.75%   |
| Intel Centrino Wireless-N 2230                                                | 1        | 0.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 0.75%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 1        | 0.75%   |
| Intel 82574L Gigabit Network Connection                                       | 1        | 0.75%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 0.75%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.75%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.75%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 0.75%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1        | 0.75%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 1        | 0.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 12       | 37.5%   |
| Realtek Semiconductor | 10       | 31.25%  |
| Ralink Technology     | 2        | 6.25%   |
| Ralink                | 2        | 6.25%   |
| Broadcom              | 2        | 6.25%   |
| TP-Link               | 1        | 3.13%   |
| Qualcomm Atheros      | 1        | 3.13%   |
| NetGear               | 1        | 3.13%   |
| MediaTek              | 1        | 3.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                              | 4        | 12.5%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 3        | 9.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter              | 2        | 6.25%   |
| Ralink RT5370 Wireless Adapter                                   | 2        | 6.25%   |
| Intel Wireless-AC 9260                                           | 2        | 6.25%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                              | 1        | 3.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 1        | 3.13%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter         | 1        | 3.13%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                           | 1        | 3.13%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                          | 1        | 3.13%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                       | 1        | 3.13%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                        | 1        | 3.13%   |
| Ralink RT2500 Wireless 802.11bg                                  | 1        | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 1        | 3.13%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101] | 1        | 3.13%   |
| MediaTek 802.11ac Wireless LAN Card                              | 1        | 3.13%   |
| Intel Wireless 7265                                              | 1        | 3.13%   |
| Intel Wireless 7260                                              | 1        | 3.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                 | 1        | 3.13%   |
| Intel Centrino Wireless-N 2230                                   | 1        | 3.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 1        | 3.13%   |
| Intel Alder Lake-S PCH CNVi WiFi                                 | 1        | 3.13%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter               | 1        | 3.13%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller           | 1        | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 55       | 56.12%  |
| Intel                    | 34       | 34.69%  |
| Qualcomm Atheros         | 7        | 7.14%   |
| Marvell Technology Group | 1        | 1.02%   |
| Broadcom                 | 1        | 1.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 47       | 47%     |
| Intel I211 Gigabit Network Connection                                         | 8        | 8%      |
| Intel Ethernet Connection I217-LM                                             | 6        | 6%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4        | 4%      |
| Intel 82579V Gigabit Network Connection                                       | 4        | 4%      |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 3%      |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 3%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 2%      |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 2%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 2%      |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 1%      |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 1%      |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 1%      |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 1%      |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1        | 1%      |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 1%      |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 1%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 1%      |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 1%      |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 1%      |
| Intel I210 Gigabit Network Connection                                         | 1        | 1%      |
| Intel Ethernet Controller I225-V                                              | 1        | 1%      |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 1%      |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 1%      |
| Intel 82574L Gigabit Network Connection                                       | 1        | 1%      |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 1%      |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1%      |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 1%      |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 1%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 94       | 75.2%   |
| WiFi     | 30       | 24%     |
| Modem    | 1        | 0.8%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 91       | 83.49%  |
| WiFi     | 18       | 16.51%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 68       | 70.83%  |
| 2     | 19       | 19.79%  |
| 3     | 4        | 4.17%   |
| 4     | 3        | 3.13%   |
| 0     | 2        | 2.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 94       | 95.92%  |
| Yes  | 4        | 4.08%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 13       | 43.33%  |
| Cambridge Silicon Radio         | 6        | 20%     |
| Realtek Semiconductor           | 2        | 6.67%   |
| IMC Networks                    | 2        | 6.67%   |
| ASUSTek Computer                | 2        | 6.67%   |
| Apple                           | 2        | 6.67%   |
| Qualcomm Atheros Communications | 1        | 3.33%   |
| Integrated System Solution      | 1        | 3.33%   |
| HTC (High Tech Computer)        | 1        | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 6        | 20%     |
| Intel AX200 Bluetooth                                                | 4        | 13.33%  |
| Realtek  Bluetooth 4.2 Adapter                                       | 2        | 6.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2        | 6.67%   |
| Intel Bluetooth wireless interface                                   | 2        | 6.67%   |
| Intel AX201 Bluetooth                                                | 2        | 6.67%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device          | 1        | 3.33%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 1        | 3.33%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 3.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 1        | 3.33%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1        | 3.33%   |
| IMC Networks Realtek Bluetooth Adapter                               | 1        | 3.33%   |
| IMC Networks Realtek Bluetooth 4.0 Adapter                           | 1        | 3.33%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 3.33%   |
| ASUS Bluetooth Controller                                            | 1        | 3.33%   |
| ASUS ASUS USB-BT500                                                  | 1        | 3.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 1        | 3.33%   |
| Apple Apple Broadcom Built-in Bluetooth                              | 1        | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 65       | 40.37%  |
| Nvidia                  | 36       | 22.36%  |
| AMD                     | 36       | 22.36%  |
| C-Media Electronics     | 5        | 3.11%   |
| Texas Instruments       | 3        | 1.86%   |
| Logitech                | 2        | 1.24%   |
| GN Netcom               | 2        | 1.24%   |
| Yamaha                  | 1        | 0.62%   |
| VIA Technologies        | 1        | 0.62%   |
| SteelSeries ApS         | 1        | 0.62%   |
| Nektar                  | 1        | 0.62%   |
| KORG                    | 1        | 0.62%   |
| Kingston Technology     | 1        | 0.62%   |
| JMTek                   | 1        | 0.62%   |
| Focusrite-Novation      | 1        | 0.62%   |
| Creative Labs           | 1        | 0.62%   |
| Corsair                 | 1        | 0.62%   |
| Cambridge Silicon Radio | 1        | 0.62%   |
| ASUSTek Computer        | 1        | 0.62%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10       | 5.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10       | 5.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9        | 4.97%   |
| AMD Starship/Matisse HD Audio Controller                                   | 9        | 4.97%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8        | 4.42%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6        | 3.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6        | 3.31%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6        | 3.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 2.76%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 2.76%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 2.76%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 2.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 2.21%   |
| Intel 200 Series PCH HD Audio                                              | 4        | 2.21%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 2.21%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 2.21%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4        | 2.21%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 2.21%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 1.66%   |
| AMD Navi 10 HDMI Audio                                                     | 3        | 1.66%   |
| Texas Instruments PCM2902 Audio Codec                                      | 2        | 1.1%    |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 1.1%    |
| Nvidia MCP61 High Definition Audio                                         | 2        | 1.1%    |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 1.1%    |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 1.1%    |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 1.1%    |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 1.1%    |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 1.1%    |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 1.1%    |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 2        | 1.1%    |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 2        | 1.1%    |
| AMD FCH Azalia Controller                                                  | 2        | 1.1%    |
| Yamaha Steinberg UR12                                                      | 1        | 0.55%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 0.55%   |
| Texas Instruments PCM2902C Audio CODEC                                     | 1        | 0.55%   |
| SteelSeries ApS SteelSeries Arctis 5 Arctis 5 Chat Arctis 5 Game           | 1        | 0.55%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.55%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.55%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 0.55%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.55%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 0.55%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.55%   |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 0.55%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.55%   |
| Nektar Impact GX61                                                         | 1        | 0.55%   |
| Logitech Headset H390                                                      | 1        | 0.55%   |
| Logitech HD Webcam C510                                                    | 1        | 0.55%   |
| KORG microKEY-25                                                           | 1        | 0.55%   |
| Kingston Technology HyperX QuadCast                                        | 1        | 0.55%   |
| JMTek USB PnP Audio Device                                                 | 1        | 0.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1        | 0.55%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 0.55%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 0.55%   |
| Intel Broadwell-U Audio Controller                                         | 1        | 0.55%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 0.55%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 0.55%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1        | 0.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 0.55%   |
| GN Netcom Jabra SPEAK 510 USB                                              | 1        | 0.55%   |
| GN Netcom Jabra Link 380                                                   | 1        | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 20       | 19.23%  |
| Unknown             | 19       | 18.27%  |
| Crucial             | 10       | 9.62%   |
| Corsair             | 10       | 9.62%   |
| SK Hynix            | 8        | 7.69%   |
| G.Skill             | 8        | 7.69%   |
| Samsung Electronics | 6        | 5.77%   |
| Micron Technology   | 6        | 5.77%   |
| Team                | 3        | 2.88%   |
| Patriot             | 3        | 2.88%   |
| AMD                 | 2        | 1.92%   |
| Unknown             | 2        | 1.92%   |
| Unifosa             | 1        | 0.96%   |
| Nanya Technology    | 1        | 0.96%   |
| Hikvision           | 1        | 0.96%   |
| GOODRAM             | 1        | 0.96%   |
| Goldkey             | 1        | 0.96%   |
| Atermiter           | 1        | 0.96%   |
| A-DATA Technology   | 1        | 0.96%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 2        | 1.75%   |
| Unknown RAM Module 2GB DIMM 400MT/s                    | 2        | 1.75%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 2        | 1.75%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s | 2        | 1.75%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s  | 2        | 1.75%   |
| Crucial RAM BL16G32C16U4B.16FE 16GB DIMM DDR4 3200MT/s | 2        | 1.75%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s  | 2        | 1.75%   |
| Unknown                                                | 2        | 1.75%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 1        | 0.88%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 1        | 0.88%   |
| Unknown RAM Module 4GB SODIMM DDR3 800MT/s             | 1        | 0.88%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                   | 1        | 0.88%   |
| Unknown RAM Module 2GB DIMM SDRAM 533MT/s              | 1        | 0.88%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 1        | 0.88%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s               | 1        | 0.88%   |
| Unknown RAM Module 2GB DIMM DDR2                       | 1        | 0.88%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s               | 1        | 0.88%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 1        | 0.88%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 1        | 0.88%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s               | 1        | 0.88%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s               | 1        | 0.88%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s      | 1        | 0.88%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s    | 1        | 0.88%   |
| Team RAM TEAMGROUP-UD4-2133 8GB DIMM DDR4 2133MT/s     | 1        | 0.88%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s     | 1        | 0.88%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s           | 1        | 0.88%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1333MT/s             | 1        | 0.88%   |
| SK Hynix RAM HMT451U7BFR8A-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.88%   |
| SK Hynix RAM HMT451S6BCFR8A-PB 4GB DIMM DDR3 1600MT/s  | 1        | 0.88%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s | 1        | 0.88%   |
| SK Hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s   | 1        | 0.88%   |
| SK Hynix RAM HMAA1GU6CJR6N-XN 8GB DIMM DDR4 3200MT/s   | 1        | 0.88%   |
| SK Hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s   | 1        | 0.88%   |
| Samsung RAM Module 4GB SODIMM DDR4 2133MT/s            | 1        | 0.88%   |
| Samsung RAM M471B5273DH0-CH9 4GB DIMM DDR3 1333MT/s    | 1        | 0.88%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 1        | 0.88%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 2666MT/s    | 1        | 0.88%   |
| Samsung RAM M378A5143EB1-CPB 4GB DIMM DDR4 2133MT/s    | 1        | 0.88%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s    | 1        | 0.88%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s         | 1        | 0.88%   |
| Patriot RAM PSD34G16002 4GB DIMM DDR3 1600MT/s         | 1        | 0.88%   |
| Patriot RAM 1600 CL9 Series 8GB DIMM DDR3 1600MT/s     | 1        | 0.88%   |
| Nanya RAM M2F4G64CB8HG5N-CG 4GB DIMM DDR3 1333MT/s     | 1        | 0.88%   |
| Nanya RAM M2F2G64CB88G7N-CG 2GB DIMM DDR3 1333MT/s     | 1        | 0.88%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s               | 1        | 0.88%   |
| Micron RAM 4ATF51264AZ-3G2J1 4GB DIMM DDR4 3200MT/s    | 1        | 0.88%   |
| Micron RAM 18KSF51272AZ-1G4M1 4GB DIMM DDR3 1333MT/s   | 1        | 0.88%   |
| Micron RAM 18ASF4G72AZ-3G2B1 32GB DIMM DDR4 3200MT/s   | 1        | 0.88%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s | 1        | 0.88%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s  | 1        | 0.88%   |
| Kingston RAM termiter 4GB DIMM DDR3 1333MT/s           | 1        | 0.88%   |
| Kingston RAM Module 8GB DIMM DDR4 2666MT/s             | 1        | 0.88%   |
| Kingston RAM KHX3733C19D4/16GX 16GB DIMM DDR4 3733MT/s | 1        | 0.88%   |
| Kingston RAM KHX3200C18D4/8G 8GB DIMM DDR4 2400MT/s    | 1        | 0.88%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s   | 1        | 0.88%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3200MT/s | 1        | 0.88%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s      | 1        | 0.88%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 2666MT/s    | 1        | 0.88%   |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s  | 1        | 0.88%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2133MT/s    | 1        | 0.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 41       | 44.09%  |
| DDR3    | 35       | 37.63%  |
| Unknown | 7        | 7.53%   |
| DDR2    | 6        | 6.45%   |
| SDRAM   | 3        | 3.23%   |
| DDR     | 1        | 1.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 85       | 92.39%  |
| SODIMM | 7        | 7.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 31       | 31%     |
| 4096  | 29       | 29%     |
| 2048  | 18       | 18%     |
| 16384 | 15       | 15%     |
| 1024  | 5        | 5%      |
| 32768 | 2        | 2%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 21       | 21.65%  |
| 1333    | 16       | 16.49%  |
| 2133    | 12       | 12.37%  |
| 3200    | 11       | 11.34%  |
| 2400    | 8        | 8.25%   |
| 2666    | 6        | 6.19%   |
| 800     | 5        | 5.15%   |
| 2667    | 3        | 3.09%   |
| Unknown | 3        | 3.09%   |
| 3600    | 2        | 2.06%   |
| 1066    | 2        | 2.06%   |
| 667     | 2        | 2.06%   |
| 400     | 2        | 2.06%   |
| 3733    | 1        | 1.03%   |
| 1867    | 1        | 1.03%   |
| 533     | 1        | 1.03%   |
| 333     | 1        | 1.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Brother HL-1430 Laser Printer | 1        | 100%    |

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
| Logitech                | 4        | 44.44%  |
| Z-Star Microelectronics | 1        | 11.11%  |
| IMC Networks            | 1        | 11.11%  |
| Hewlett-Packard         | 1        | 11.11%  |
| Chicony Electronics     | 1        | 11.11%  |
| Arkmicro Technologies   | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Z-Star Lenovo USB2.0 UVC Camera | 1        | 11.11%  |
| Logitech Webcam C930e           | 1        | 11.11%  |
| Logitech Webcam C310            | 1        | 11.11%  |
| Logitech Webcam C270            | 1        | 11.11%  |
| Logitech BRIO Ultra HD Webcam   | 1        | 11.11%  |
| IMC Networks XHC Camera         | 1        | 11.11%  |
| HP Realtek PC Camera            | 1        | 11.11%  |
| Chicony HP 0.3MP Webcam         | 1        | 11.11%  |
| Arkmicro USB2.0 PC CAMERA       | 1        | 11.11%  |

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
| 1     | 41       | 42.71%  |
| 0     | 37       | 38.54%  |
| 2     | 13       | 13.54%  |
| 3     | 3        | 3.13%   |
| 4     | 2        | 2.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 52       | 66.67%  |
| Net/wireless             | 16       | 20.51%  |
| Bluetooth                | 4        | 5.13%   |
| Sound                    | 3        | 3.85%   |
| Network                  | 1        | 1.28%   |
| Net/ethernet             | 1        | 1.28%   |
| Card reader              | 1        | 1.28%   |

