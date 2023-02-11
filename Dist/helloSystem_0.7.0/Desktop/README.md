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

Total: 241

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Gigabyte      | Z390 AORUS ELITE-CF         | [161dad9f5d](https://bsd-hardware.info/?probe=161dad9f5d) | Jan 31, 2023 |
| MACHINIST     | X99-K9 V2.0                 | [eb8a6cb004](https://bsd-hardware.info/?probe=eb8a6cb004) | Jan 30, 2023 |
| ASRock        | X299E-ITX/ac                | [0b7dacf902](https://bsd-hardware.info/?probe=0b7dacf902) | Jan 25, 2023 |
| ASUSTek       | P7P55D LE                   | [5da1e71837](https://bsd-hardware.info/?probe=5da1e71837) | Jan 25, 2023 |
| Dell          | 0D02VH A01                  | [ad7dd00eeb](https://bsd-hardware.info/?probe=ad7dd00eeb) | Jan 25, 2023 |
| Biostar       | TB250-BTC+                  | [0a39ffa716](https://bsd-hardware.info/?probe=0a39ffa716) | Jan 24, 2023 |
| Apple         | Mac-F221BEC8                | [556e872ffe](https://bsd-hardware.info/?probe=556e872ffe) | Jan 24, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [d03f9c19f8](https://bsd-hardware.info/?probe=d03f9c19f8) | Jan 23, 2023 |
| Dell          | 0HHV7N A00                  | [771f2c4d96](https://bsd-hardware.info/?probe=771f2c4d96) | Jan 23, 2023 |
| Intel         | H61                         | [7faeca8300](https://bsd-hardware.info/?probe=7faeca8300) | Jan 22, 2023 |
| Dell          | 0K240Y A01                  | [d9f16ef94b](https://bsd-hardware.info/?probe=d9f16ef94b) | Jan 18, 2023 |
| Dell          | 0UW457 A03                  | [47b66a0d86](https://bsd-hardware.info/?probe=47b66a0d86) | Dec 21, 2022 |
| Gigabyte      | H81M-DS2                    | [29ad5ee336](https://bsd-hardware.info/?probe=29ad5ee336) | Dec 19, 2022 |
| Apple         | Mac-F221BEC8                | [bc15367e9f](https://bsd-hardware.info/?probe=bc15367e9f) | Dec 14, 2022 |
| HP            | 3397                        | [bc9e5c3ab7](https://bsd-hardware.info/?probe=bc9e5c3ab7) | Dec 09, 2022 |
| Pegatron      | 2A72h                       | [87e76fd095](https://bsd-hardware.info/?probe=87e76fd095) | Dec 09, 2022 |
| Dell          | 0WMJ54 A01                  | [5441995e7b](https://bsd-hardware.info/?probe=5441995e7b) | Dec 05, 2022 |
| Gigabyte      | M68MT-S2P                   | [2fe00838c3](https://bsd-hardware.info/?probe=2fe00838c3) | Dec 05, 2022 |
| Gigabyte      | M68MT-S2P                   | [71f95dafb4](https://bsd-hardware.info/?probe=71f95dafb4) | Dec 05, 2022 |
| Intel         | X99                         | [c21a466fc1](https://bsd-hardware.info/?probe=c21a466fc1) | Dec 01, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [43163b0170](https://bsd-hardware.info/?probe=43163b0170) | Nov 28, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [d00aa0021e](https://bsd-hardware.info/?probe=d00aa0021e) | Nov 28, 2022 |
| Dell          | 09M8Y8 A02                  | [2299b7c270](https://bsd-hardware.info/?probe=2299b7c270) | Nov 27, 2022 |
| ASRock        | N68-S                       | [3813c8856e](https://bsd-hardware.info/?probe=3813c8856e) | Nov 27, 2022 |
| Lenovo        | ThinkStation S30 0569A93    | [dd545fb588](https://bsd-hardware.info/?probe=dd545fb588) | Nov 25, 2022 |
| Pegatron      | IPM41-D3                    | [898f645e32](https://bsd-hardware.info/?probe=898f645e32) | Nov 25, 2022 |
| MSI           | Z170A GAMING M5             | [5740972ddc](https://bsd-hardware.info/?probe=5740972ddc) | Nov 25, 2022 |
| MSI           | A320M-A PRO                 | [fc71b97d90](https://bsd-hardware.info/?probe=fc71b97d90) | Nov 24, 2022 |
| Gigabyte      | E2500N                      | [64b937b551](https://bsd-hardware.info/?probe=64b937b551) | Nov 23, 2022 |
| Gigabyte      | G31M-S2L                    | [d376385d80](https://bsd-hardware.info/?probe=d376385d80) | Nov 23, 2022 |
| ASUSTek       | A55BM-K                     | [dc487b5779](https://bsd-hardware.info/?probe=dc487b5779) | Nov 23, 2022 |
| ASUSTek       | PRIME A320M-K               | [9701222998](https://bsd-hardware.info/?probe=9701222998) | Nov 23, 2022 |
| Intel         | H61                         | [689ebf0e57](https://bsd-hardware.info/?probe=689ebf0e57) | Nov 22, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [92eab8d065](https://bsd-hardware.info/?probe=92eab8d065) | Nov 19, 2022 |
| ASUSTek       | P5E-VM SE                   | [910dc6412e](https://bsd-hardware.info/?probe=910dc6412e) | Nov 10, 2022 |
| MSI           | Z370I GAMING PRO CARBON ... | [dd9f7679b5](https://bsd-hardware.info/?probe=dd9f7679b5) | Nov 09, 2022 |
| Dell          | 0F428D A00                  | [0a9ca655d3](https://bsd-hardware.info/?probe=0a9ca655d3) | Nov 08, 2022 |
| ASUSTek       | Z97-A                       | [6a2b1c8105](https://bsd-hardware.info/?probe=6a2b1c8105) | Nov 05, 2022 |
| HP            | 8053                        | [92583639f6](https://bsd-hardware.info/?probe=92583639f6) | Nov 02, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [c6ee09790d](https://bsd-hardware.info/?probe=c6ee09790d) | Oct 20, 2022 |
| ASUSTek       | N3050I-C                    | [4a83b0953e](https://bsd-hardware.info/?probe=4a83b0953e) | Oct 18, 2022 |
| HP            | 8169                        | [86b1fbf917](https://bsd-hardware.info/?probe=86b1fbf917) | Oct 15, 2022 |
| Lenovo        | ThinkCentre M57p 6078AJ6    | [a808a7360d](https://bsd-hardware.info/?probe=a808a7360d) | Oct 14, 2022 |
| ASRock        | A320M-HD                    | [6418fd0b23](https://bsd-hardware.info/?probe=6418fd0b23) | Sep 28, 2022 |
| Apple         | Mac-7BA5B2D9E42DDD94        | [d2e169b8ad](https://bsd-hardware.info/?probe=d2e169b8ad) | Sep 13, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | [7c9c1db9d7](https://bsd-hardware.info/?probe=7c9c1db9d7) | Sep 10, 2022 |
| Pegatron      | IPM41-D3                    | [2d3a5a5260](https://bsd-hardware.info/?probe=2d3a5a5260) | Sep 06, 2022 |
| ASUSTek       | H81M-A                      | [11ac5a7932](https://bsd-hardware.info/?probe=11ac5a7932) | Sep 02, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [17f4ac1979](https://bsd-hardware.info/?probe=17f4ac1979) | Aug 23, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [5ea9441653](https://bsd-hardware.info/?probe=5ea9441653) | Aug 19, 2022 |
| Lenovo        | SDK0E50510 WIN              | [a45977c76b](https://bsd-hardware.info/?probe=a45977c76b) | Aug 10, 2022 |
| ASRock        | Z370 Pro4                   | [038c5f8763](https://bsd-hardware.info/?probe=038c5f8763) | Aug 10, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [af241a5384](https://bsd-hardware.info/?probe=af241a5384) | Aug 06, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | [d61693dffb](https://bsd-hardware.info/?probe=d61693dffb) | Aug 05, 2022 |
| ASUSTek       | K30AM-J                     | [e032724bc2](https://bsd-hardware.info/?probe=e032724bc2) | Aug 05, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [850198c512](https://bsd-hardware.info/?probe=850198c512) | Aug 05, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [cddf42b097](https://bsd-hardware.info/?probe=cddf42b097) | Aug 05, 2022 |
| HP            | 1497                        | [c6f6ddf728](https://bsd-hardware.info/?probe=c6f6ddf728) | Aug 04, 2022 |
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
| Dell          | 0D6H9T A00                  | [7daab72741](https://bsd-hardware.info/?probe=7daab72741) | Apr 01, 2022 |
| ASUSTek       | P6-P8H61E                   | [11664cd9d7](https://bsd-hardware.info/?probe=11664cd9d7) | Mar 30, 2022 |
| ASUSTek       | M4A88T-M                    | [6a615f6be5](https://bsd-hardware.info/?probe=6a615f6be5) | Mar 30, 2022 |
| ASUSTek       | M5A78L-M LX3                | [0906d116eb](https://bsd-hardware.info/?probe=0906d116eb) | Mar 29, 2022 |
| Gigabyte      | H110N-CF                    | [89593af061](https://bsd-hardware.info/?probe=89593af061) | Mar 29, 2022 |
| Gigabyte      | H61M-S2PV                   | [553f2beb91](https://bsd-hardware.info/?probe=553f2beb91) | Mar 27, 2022 |
| ASRock        | A320M-HDV R4.0              | [8c89faeb24](https://bsd-hardware.info/?probe=8c89faeb24) | Mar 26, 2022 |
| ASRock        | A320M-HDV R4.0              | [ae1fa6cbce](https://bsd-hardware.info/?probe=ae1fa6cbce) | Mar 26, 2022 |
| MSI           | B85-G43                     | [f0a919c35f](https://bsd-hardware.info/?probe=f0a919c35f) | Mar 25, 2022 |
| MSI           | B85-G43                     | [7bd545fda8](https://bsd-hardware.info/?probe=7bd545fda8) | Mar 25, 2022 |
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
| Dell          | 0YF8P5 A00                  | [0f03a66475](https://bsd-hardware.info/?probe=0f03a66475) | Dec 09, 2021 |
| Dell          | 0YF8P5 A00                  | [83b36f7c3d](https://bsd-hardware.info/?probe=83b36f7c3d) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [a084ff48c2](https://bsd-hardware.info/?probe=a084ff48c2) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [17b557d792](https://bsd-hardware.info/?probe=17b557d792) | Dec 08, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [8cfe11fe93](https://bsd-hardware.info/?probe=8cfe11fe93) | Nov 30, 2021 |
| Intel         | DG41TY AAE47335-300         | [dd357bcaa5](https://bsd-hardware.info/?probe=dd357bcaa5) | Nov 30, 2021 |
| HP            | 843B                        | [404224439d](https://bsd-hardware.info/?probe=404224439d) | Nov 29, 2021 |
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
| amd64 | 192      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 191      | 99.48%  |
| GNOME        | 1        | 0.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 192      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 192      | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 186      | 96.88%  |
| es_ES | 3        | 1.56%   |
| fr_FR | 1        | 0.52%   |
| de_DE | 1        | 0.52%   |
| C     | 1        | 0.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 187      | 97.4%   |
| BIOS | 5        | 2.6%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Cd9660 | 125      | 63.13%  |
| Zfs    | 73       | 36.87%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 188      | 97.92%  |
| MBR  | 4        | 2.08%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 53       | 27.6%   |
| Gigabyte Technology | 36       | 18.75%  |
| Dell                | 18       | 9.38%   |
| ASRock              | 16       | 8.33%   |
| Hewlett-Packard     | 15       | 7.81%   |
| MSI                 | 9        | 4.69%   |
| Intel               | 9        | 4.69%   |
| Lenovo              | 7        | 3.65%   |
| Pegatron            | 5        | 2.6%    |
| Apple               | 3        | 1.56%   |
| Fujitsu             | 2        | 1.04%   |
| Acer                | 2        | 1.04%   |
| Unknown             | 2        | 1.04%   |
| T-bao               | 1        | 0.52%   |
| Supermicro          | 1        | 0.52%   |
| Shuttle             | 1        | 0.52%   |
| Quanta              | 1        | 0.52%   |
| QIYIDA              | 1        | 0.52%   |
| Positivo            | 1        | 0.52%   |
| OEM                 | 1        | 0.52%   |
| Medion              | 1        | 0.52%   |
| MAXSUN              | 1        | 0.52%   |
| MACHINIST           | 1        | 0.52%   |
| Koloe               | 1        | 0.52%   |
| ECS                 | 1        | 0.52%   |
| Biostar             | 1        | 0.52%   |
| BESSTAR Tech        | 1        | 0.52%   |
| ALLEGIANCE GAMING   | 1        | 0.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 3        | 1.56%   |
| Apple MacPro5,1                    | 3        | 1.56%   |
| Pegatron IPM41-D3                  | 2        | 1.04%   |
| Intel H61                          | 2        | 1.04%   |
| HP ProDesk 600 G2 DM               | 2        | 1.04%   |
| HP EliteDesk 700 G1 SFF            | 2        | 1.04%   |
| Dell Precision Tower 5810          | 2        | 1.04%   |
| Dell Precision T1700               | 2        | 1.04%   |
| Dell OptiPlex 960                  | 2        | 1.04%   |
| ASUS TUF GAMING X570-PLUS          | 2        | 1.04%   |
| ASUS PRIME X570-P                  | 2        | 1.04%   |
| ASUS PRIME A320M-K                 | 2        | 1.04%   |
| ASUS P8Z77-V LX                    | 2        | 1.04%   |
| ASRock X570 Phantom Gaming 4       | 2        | 1.04%   |
| Unknown                            | 2        | 1.04%   |
| T-bao MINI PC                      | 1        | 0.52%   |
| Supermicro X9DAL                   | 1        | 0.52%   |
| Shuttle XH170                      | 1        | 0.52%   |
| Quanta 120-1135                    | 1        | 0.52%   |
| QIYIDA X99-H9 V2.0                 | 1        | 0.52%   |
| Positivo POS-PIQ77CL               | 1        | 0.52%   |
| Pegatron Compaq dx2450 Microtower  | 1        | 0.52%   |
| Pegatron Compaq 505B Microtower PC | 1        | 0.52%   |
| Pegatron AY627AA-ABA a4313w        | 1        | 0.52%   |
| OEM B85 JHS359                     | 1        | 0.52%   |
| MSI MS-7D25                        | 1        | 0.52%   |
| MSI MS-7C51                        | 1        | 0.52%   |
| MSI MS-7B86                        | 1        | 0.52%   |
| MSI MS-7B43                        | 1        | 0.52%   |
| MSI MS-7A33                        | 1        | 0.52%   |
| MSI MS-7977                        | 1        | 0.52%   |
| MSI MS-7816                        | 1        | 0.52%   |
| MSI MS-7758                        | 1        | 0.52%   |
| MSI MS-7369                        | 1        | 0.52%   |
| Medion H61H2-LM3                   | 1        | 0.52%   |
| MAXSUN MS-H110D4L FS M.2           | 1        | 0.52%   |
| MACHINIST X99-K9 V2.0              | 1        | 0.52%   |
| Lenovo YangTianA8800T              | 1        | 0.52%   |
| Lenovo ThinkStation S30 0569A93    | 1        | 0.52%   |
| Lenovo ThinkCentre XXXX Y          | 1        | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 10       | 5.21%   |
| Dell OptiPlex        | 8        | 4.17%   |
| ASUS ROG             | 7        | 3.65%   |
| HP EliteDesk         | 6        | 3.13%   |
| Dell Precision       | 5        | 2.6%    |
| ASUS TUF             | 5        | 2.6%    |
| Lenovo ThinkCentre   | 4        | 2.08%   |
| HP Compaq            | 4        | 2.08%   |
| Gigabyte X570        | 3        | 1.56%   |
| Gigabyte B450        | 3        | 1.56%   |
| ASUS All             | 3        | 1.56%   |
| Apple MacPro5        | 3        | 1.56%   |
| Pegatron IPM41-D3    | 2        | 1.04%   |
| Pegatron Compaq      | 2        | 1.04%   |
| Intel H61            | 2        | 1.04%   |
| HP ProDesk           | 2        | 1.04%   |
| Gigabyte Z390        | 2        | 1.04%   |
| Fujitsu ESPRIMO      | 2        | 1.04%   |
| Dell Inspiron        | 2        | 1.04%   |
| ASUS P8Z77-V         | 2        | 1.04%   |
| ASUS P5GC-MX         | 2        | 1.04%   |
| ASUS Maximus         | 2        | 1.04%   |
| ASRock X570          | 2        | 1.04%   |
| Unknown              | 2        | 1.04%   |
| T-bao MINI           | 1        | 0.52%   |
| Supermicro X9DAL     | 1        | 0.52%   |
| Shuttle XH170        | 1        | 0.52%   |
| Quanta 120-1135      | 1        | 0.52%   |
| QIYIDA X99-H9        | 1        | 0.52%   |
| Positivo POS-PIQ77CL | 1        | 0.52%   |
| Pegatron AY627AA-ABA | 1        | 0.52%   |
| OEM B85              | 1        | 0.52%   |
| MSI MS-7D25          | 1        | 0.52%   |
| MSI MS-7C51          | 1        | 0.52%   |
| MSI MS-7B86          | 1        | 0.52%   |
| MSI MS-7B43          | 1        | 0.52%   |
| MSI MS-7A33          | 1        | 0.52%   |
| MSI MS-7977          | 1        | 0.52%   |
| MSI MS-7816          | 1        | 0.52%   |
| MSI MS-7758          | 1        | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 24       | 12.5%   |
| 2021 | 23       | 11.98%  |
| 2018 | 22       | 11.46%  |
| 2012 | 20       | 10.42%  |
| 2014 | 15       | 7.81%   |
| 2010 | 15       | 7.81%   |
| 2013 | 12       | 6.25%   |
| 2017 | 11       | 5.73%   |
| 2020 | 10       | 5.21%   |
| 2016 | 10       | 5.21%   |
| 2009 | 9        | 4.69%   |
| 2007 | 6        | 3.13%   |
| 2015 | 5        | 2.6%    |
| 2011 | 5        | 2.6%    |
| 2008 | 4        | 2.08%   |
| 2022 | 1        | 0.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 192      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 192      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 53       | 27.6%   |
| 16.01-24.0  | 51       | 26.56%  |
| 4.01-8.0    | 38       | 19.79%  |
| 32.01-64.0  | 31       | 16.15%  |
| 64.01-256.0 | 8        | 4.17%   |
| 2.01-3.0    | 4        | 2.08%   |
| 24.01-32.0  | 3        | 1.56%   |
| 0.51-1.0    | 2        | 1.04%   |
| 3.01-4.0    | 1        | 0.52%   |
| 1.01-2.0    | 1        | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 79       | 40.72%  |
| 0.51-1.0  | 65       | 33.51%  |
| 1.01-2.0  | 41       | 21.13%  |
| 2.01-3.0  | 6        | 3.09%   |
| 3.01-4.0  | 2        | 1.03%   |
| 8.01-16.0 | 1        | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 86       | 43.88%  |
| 2      | 52       | 26.53%  |
| 3      | 23       | 11.73%  |
| 4      | 14       | 7.14%   |
| 0      | 11       | 5.61%   |
| 6      | 4        | 2.04%   |
| 5      | 4        | 2.04%   |
| 9      | 1        | 0.51%   |
| 7      | 1        | 0.51%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 132      | 68.75%  |
| Yes       | 60       | 31.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 187      | 97.4%   |
| No        | 5        | 2.6%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 136      | 70.83%  |
| Yes       | 56       | 29.17%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 140      | 72.92%  |
| Yes       | 52       | 27.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 28       | 14.58%  |
| Russia       | 26       | 13.54%  |
| Brazil       | 13       | 6.77%   |
| Spain        | 11       | 5.73%   |
| China        | 9        | 4.69%   |
| Canada       | 9        | 4.69%   |
| Poland       | 8        | 4.17%   |
| Hungary      | 7        | 3.65%   |
| Ukraine      | 6        | 3.13%   |
| Italy        | 6        | 3.13%   |
| India        | 6        | 3.13%   |
| Germany      | 6        | 3.13%   |
| UK           | 4        | 2.08%   |
| France       | 4        | 2.08%   |
| Australia    | 4        | 2.08%   |
| Venezuela    | 3        | 1.56%   |
| Turkey       | 3        | 1.56%   |
| South Korea  | 3        | 1.56%   |
| Romania      | 3        | 1.56%   |
| Mexico       | 3        | 1.56%   |
| Argentina    | 3        | 1.56%   |
| Portugal     | 2        | 1.04%   |
| Peru         | 2        | 1.04%   |
| Norway       | 2        | 1.04%   |
| Netherlands  | 2        | 1.04%   |
| Vietnam      | 1        | 0.52%   |
| Thailand     | 1        | 0.52%   |
| Taiwan       | 1        | 0.52%   |
| Switzerland  | 1        | 0.52%   |
| Sweden       | 1        | 0.52%   |
| South Africa | 1        | 0.52%   |
| Slovenia     | 1        | 0.52%   |
| Serbia       | 1        | 0.52%   |
| Philippines  | 1        | 0.52%   |
| Panama       | 1        | 0.52%   |
| New Zealand  | 1        | 0.52%   |
| Kazakhstan   | 1        | 0.52%   |
| Indonesia    | 1        | 0.52%   |
| Iceland      | 1        | 0.52%   |
| Greece       | 1        | 0.52%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| St Petersburg           | 4        | 2.02%   |
| Moscow                  | 3        | 1.52%   |
| Surgut                  | 2        | 1.01%   |
| Stavropol               | 2        | 1.01%   |
| St. Jean Baptiste       | 2        | 1.01%   |
| Sao Paulo               | 2        | 1.01%   |
| Perth                   | 2        | 1.01%   |
| Myrtle Beach            | 2        | 1.01%   |
| Lima                    | 2        | 1.01%   |
| Kharkiv                 | 2        | 1.01%   |
| Istanbul                | 2        | 1.01%   |
| Guangzhou               | 2        | 1.01%   |
| Curitiba                | 2        | 1.01%   |
| Chelyabinsk             | 2        | 1.01%   |
| Castilleja de la Cuesta | 2        | 1.01%   |
| Caracas                 | 2        | 1.01%   |
| Barnaul                 | 2        | 1.01%   |
| Zhengzhou               | 1        | 0.51%   |
| Yunlin                  | 1        | 0.51%   |
| Yancheng                | 1        | 0.51%   |
| Xicheng District        | 1        | 0.51%   |
| Warsaw                  | 1        | 0.51%   |
| Vancouver               | 1        | 0.51%   |
| Tver                    | 1        | 0.51%   |
| Tromsø                 | 1        | 0.51%   |
| Tiruchi                 | 1        | 0.51%   |
| Temple                  | 1        | 0.51%   |
| Tegal                   | 1        | 0.51%   |
| Tampa                   | 1        | 0.51%   |
| Szombathely             | 1        | 0.51%   |
| Szeged                  | 1        | 0.51%   |
| SzÃ©kesfehÃ©rvÃ¡r | 1        | 0.51%   |
| Suceava                 | 1        | 0.51%   |
| Stockbridge             | 1        | 0.51%   |
| Sparta                  | 1        | 0.51%   |
| Spalice                 | 1        | 0.51%   |
| Sopron                  | 1        | 0.51%   |
| Songpa-gu               | 1        | 0.51%   |
| Somerset West           | 1        | 0.51%   |
| Smiths Falls            | 1        | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 62       | 81     | 19.75%  |
| WDC                 | 57       | 79     | 18.15%  |
| Samsung Electronics | 49       | 67     | 15.61%  |
| Toshiba             | 22       | 27     | 7.01%   |
| Crucial             | 20       | 27     | 6.37%   |
| Kingston            | 16       | 21     | 5.1%    |
| A-DATA Technology   | 8        | 9      | 2.55%   |
| Hitachi             | 7        | 9      | 2.23%   |
| SanDisk             | 6        | 6      | 1.91%   |
| Phison              | 6        | 7      | 1.91%   |
| Intel               | 6        | 6      | 1.91%   |
| Goodram             | 5        | 6      | 1.59%   |
| SK hynix            | 4        | 6      | 1.27%   |
| PNY                 | 4        | 4      | 1.27%   |
| Patriot             | 4        | 4      | 1.27%   |
| XPG                 | 3        | 3      | 0.96%   |
| Team                | 3        | 3      | 0.96%   |
| OCZ                 | 3        | 3      | 0.96%   |
| KingSpec            | 3        | 3      | 0.96%   |
| HGST                | 3        | 3      | 0.96%   |
| Plextor             | 2        | 2      | 0.64%   |
| Gigabyte Technology | 2        | 3      | 0.64%   |
| Corsair             | 2        | 2      | 0.64%   |
| XrayDisk            | 1        | 1      | 0.32%   |
| tigo                | 1        | 1      | 0.32%   |
| SPCC                | 1        | 1      | 0.32%   |
| Silicon Motion      | 1        | 1      | 0.32%   |
| Nfortec             | 1        | 1      | 0.32%   |
| Mushkin             | 1        | 1      | 0.32%   |
| LITEONIT            | 1        | 1      | 0.32%   |
| LITEON              | 1        | 2      | 0.32%   |
| Lite-On             | 1        | 1      | 0.32%   |
| Kingchuxing         | 1        | 1      | 0.32%   |
| Kimtigo             | 1        | 1      | 0.32%   |
| Intenso             | 1        | 1      | 0.32%   |
| Hewlett-Packard     | 1        | 1      | 0.32%   |
| Emtec               | 1        | 1      | 0.32%   |
| China               | 1        | 1      | 0.32%   |
| Apple               | 1        | 4      | 0.32%   |
| Apacer              | 1        | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Crucial CT500MX500SSD1 500GB            | 6        | 1.71%   |
| Seagate ST1000DM010-2EP102 1TB          | 5        | 1.42%   |
| Seagate ST1000DM003-1ER162 1TB          | 5        | 1.42%   |
| Samsung SSD 980 PRO 1TB                 | 4        | 1.14%   |
| Kingston SA400S37120G 120GB             | 4        | 1.14%   |
| XPG GAMMIX S11 Pro 256GB                | 3        | 0.85%   |
| Toshiba HDWD110 1TB                     | 3        | 0.85%   |
| Toshiba DT01ACA100 1TB                  | 3        | 0.85%   |
| Seagate ST4000DM004-2CV104 4TB          | 3        | 0.85%   |
| Seagate ST3500418AS 500GB               | 3        | 0.85%   |
| Seagate ST31000528AS 1TB                | 3        | 0.85%   |
| Seagate ST2000DM008-2FR102 2TB          | 3        | 0.85%   |
| Samsung SSD 970 EVO Plus 500GB          | 3        | 0.85%   |
| Samsung SSD 970 EVO Plus 1TB            | 3        | 0.85%   |
| Samsung SSD 850 EVO 250GB               | 3        | 0.85%   |
| Samsung HD322HJ 320GB                   | 3        | 0.85%   |
| Kingston SA400S37240G 240GB             | 3        | 0.85%   |
| Crucial CT240BX500SSD1 240GB            | 3        | 0.85%   |
| WDC WDS240G2G0A-00JH30 240GB            | 2        | 0.57%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 2        | 0.57%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 2        | 0.57%   |
| WDC WD5000AAKX-75U6AA0 500GB            | 2        | 0.57%   |
| WDC WD5000AAKX-00ERMA0 500GB            | 2        | 0.57%   |
| WDC WD3200AAJS-00YZCA0 320GB            | 2        | 0.57%   |
| WDC WD20PURZ-85GU6Y0 2TB                | 2        | 0.57%   |
| Toshiba DT01ACA050 500GB                | 2        | 0.57%   |
| SK hynix BC501 HFM128GDJTNG-8310A 128GB | 2        | 0.57%   |
| Seagate ST9500325AS 500GB               | 2        | 0.57%   |
| Seagate ST3500413AS 500GB               | 2        | 0.57%   |
| Seagate ST3320418AS 320GB               | 2        | 0.57%   |
| Seagate ST3160812AS 160GB               | 2        | 0.57%   |
| Seagate ST1000DM003-1CH162 1TB          | 2        | 0.57%   |
| SanDisk SDSSDA120G 120GB                | 2        | 0.57%   |
| Samsung SSD 980 1TB                     | 2        | 0.57%   |
| Samsung SSD 970 EVO 250GB               | 2        | 0.57%   |
| Samsung SSD 860 EVO 500GB               | 2        | 0.57%   |
| Samsung SSD 860 EVO 250GB               | 2        | 0.57%   |
| Samsung SSD 860 EVO 1TB                 | 2        | 0.57%   |
| Samsung SSD 850 EVO 500GB               | 2        | 0.57%   |
| Samsung SSD 750 EVO 120GB               | 2        | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 62       | 78     | 41.33%  |
| WDC                 | 48       | 59     | 32%     |
| Toshiba             | 20       | 24     | 13.33%  |
| Samsung Electronics | 10       | 11     | 6.67%   |
| Hitachi             | 7        | 9      | 4.67%   |
| HGST                | 3        | 3      | 2%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 28       | 30     | 22.22%  |
| Crucial             | 19       | 25     | 15.08%  |
| Kingston            | 13       | 17     | 10.32%  |
| A-DATA Technology   | 7        | 7      | 5.56%   |
| WDC                 | 6        | 10     | 4.76%   |
| SanDisk             | 6        | 6      | 4.76%   |
| Intel               | 5        | 5      | 3.97%   |
| Goodram             | 5        | 6      | 3.97%   |
| PNY                 | 4        | 4      | 3.17%   |
| Patriot             | 4        | 4      | 3.17%   |
| OCZ                 | 3        | 3      | 2.38%   |
| KingSpec            | 3        | 3      | 2.38%   |
| Toshiba             | 2        | 3      | 1.59%   |
| Plextor             | 2        | 2      | 1.59%   |
| Gigabyte Technology | 2        | 3      | 1.59%   |
| Corsair             | 2        | 2      | 1.59%   |
| XrayDisk            | 1        | 1      | 0.79%   |
| tigo                | 1        | 1      | 0.79%   |
| Team                | 1        | 1      | 0.79%   |
| SPCC                | 1        | 1      | 0.79%   |
| SK hynix            | 1        | 1      | 0.79%   |
| LITEONIT            | 1        | 1      | 0.79%   |
| LITEON              | 1        | 2      | 0.79%   |
| Lite-On             | 1        | 1      | 0.79%   |
| Kingchuxing         | 1        | 1      | 0.79%   |
| Intenso             | 1        | 1      | 0.79%   |
| Hewlett-Packard     | 1        | 1      | 0.79%   |
| Emtec               | 1        | 1      | 0.79%   |
| China               | 1        | 1      | 0.79%   |
| Apple               | 1        | 4      | 0.79%   |
| Apacer              | 1        | 1      | 0.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 122      | 184    | 45.35%  |
| SSD  | 102      | 149    | 37.92%  |
| NVMe | 45       | 69     | 16.73%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 172      | 333    | 79.26%  |
| NVMe | 45       | 69     | 20.74%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 149      | 224    | 64.22%  |
| 0.51-1.0   | 45       | 59     | 19.4%   |
| 1.01-2.0   | 17       | 19     | 7.33%   |
| 3.01-4.0   | 11       | 19     | 4.74%   |
| 2.01-3.0   | 5        | 6      | 2.16%   |
| 4.01-10.0  | 4        | 5      | 1.72%   |
| 10.01-20.0 | 1        | 1      | 0.43%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 121      | 61.11%  |
| 101-250        | 41       | 20.71%  |
| 251-500        | 22       | 11.11%  |
| 501-1000       | 8        | 4.04%   |
| 51-100         | 4        | 2.02%   |
| More than 3000 | 1        | 0.51%   |
| 21-50          | 1        | 0.51%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 190      | 98.96%  |
| 21-50   | 2        | 1.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Toshiba DT01ACA100 1TB                | 2        | 4      | 3.45%   |
| Seagate ST3500418AS 500GB             | 2        | 2      | 3.45%   |
| Seagate ST3500413AS 500GB             | 2        | 3      | 3.45%   |
| Seagate ST3320418AS 320GB             | 2        | 2      | 3.45%   |
| Seagate ST31000528AS 1TB              | 2        | 3      | 3.45%   |
| XrayDisk SSD 240GB                    | 1        | 1      | 1.72%   |
| WDC WD60EZRZ-00RWYB1 6TB              | 1        | 1      | 1.72%   |
| WDC WD5000AZLX-00CL5A0 500GB          | 1        | 1      | 1.72%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1        | 1      | 1.72%   |
| WDC WD5000AAKX-001CA0 500GB           | 1        | 1      | 1.72%   |
| WDC WD5000AAKS-22A7B0 500GB           | 1        | 1      | 1.72%   |
| WDC WD400JB-00ENA0 40GB               | 1        | 1      | 1.72%   |
| WDC WD3200AAKS-75L9A0 320GB           | 1        | 1      | 1.72%   |
| WDC WD3200AAJS-22B4A0 320GB           | 1        | 1      | 1.72%   |
| WDC WD3200AAJS-00YZCA0 320GB          | 1        | 1      | 1.72%   |
| WDC WD20EURS-63S48Y0 2TB              | 1        | 1      | 1.72%   |
| WDC WD1600BEVT-22ZCT0 160GB           | 1        | 1      | 1.72%   |
| WDC WD1600AAJS-60Z0A0 160GB           | 1        | 1      | 1.72%   |
| WDC WD10EZEX-08M2NA0 1TB              | 1        | 1      | 1.72%   |
| WDC WD10EARS-003BB1 1TB               | 1        | 1      | 1.72%   |
| Toshiba MQ01UBD100 1TB                | 1        | 1      | 1.72%   |
| Toshiba MQ01ABD025 250GB              | 1        | 1      | 1.72%   |
| Toshiba MK1255GSX H 120GB             | 1        | 1      | 1.72%   |
| Toshiba MD04ACA400 4TB                | 1        | 1      | 1.72%   |
| Toshiba DT01ABA300 3TB                | 1        | 1      | 1.72%   |
| Seagate ST8000NM0055-1RM112 8TB       | 1        | 1      | 1.72%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1        | 1      | 1.72%   |
| Seagate ST380211AS 80GB               | 1        | 1      | 1.72%   |
| Seagate ST3500414CS 500GB             | 1        | 1      | 1.72%   |
| Seagate ST3250310AS 250GB             | 1        | 1      | 1.72%   |
| Seagate ST320LM000 HM321HI 320GB      | 1        | 2      | 1.72%   |
| Seagate ST3160812AS 160GB             | 1        | 1      | 1.72%   |
| Seagate ST3160211AS 160GB             | 1        | 1      | 1.72%   |
| Seagate ST31000520AS 1TB              | 1        | 1      | 1.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1        | 1      | 1.72%   |
| Seagate ST1000DM003-1ER162 1TB        | 1        | 1      | 1.72%   |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 1.72%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1        | 1      | 1.72%   |
| Samsung Electronics HD322HJ 320GB     | 1        | 1      | 1.72%   |
| Samsung Electronics HD250HJ 250GB     | 1        | 1      | 1.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 22     | 32.14%  |
| WDC                 | 14       | 14     | 25%     |
| Toshiba             | 6        | 9      | 10.71%  |
| Samsung Electronics | 5        | 5      | 8.93%   |
| Hitachi             | 4        | 6      | 7.14%   |
| Kingston            | 2        | 2      | 3.57%   |
| Crucial             | 2        | 2      | 3.57%   |
| XrayDisk            | 1        | 1      | 1.79%   |
| KingSpec            | 1        | 1      | 1.79%   |
| Intel               | 1        | 1      | 1.79%   |
| Corsair             | 1        | 1      | 1.79%   |
| A-DATA Technology   | 1        | 1      | 1.79%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 22     | 40%     |
| WDC                 | 14       | 14     | 31.11%  |
| Toshiba             | 6        | 9      | 13.33%  |
| Hitachi             | 4        | 6      | 8.89%   |
| Samsung Electronics | 3        | 3      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 40       | 54     | 78.43%  |
| SSD  | 9        | 9      | 17.65%  |
| NVMe | 2        | 2      | 3.92%   |

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
| Works    | 156      | 332    | 74.64%  |
| Malfunc  | 49       | 65     | 23.44%  |
| Detected | 3        | 4      | 1.44%   |
| Failed   | 1        | 1      | 0.48%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 128      | 50.59%  |
| AMD                          | 52       | 20.55%  |
| Samsung Electronics          | 18       | 7.11%   |
| Nvidia                       | 8        | 3.16%   |
| Phison Electronics           | 7        | 2.77%   |
| SanDisk                      | 5        | 1.98%   |
| JMicron Technology           | 5        | 1.98%   |
| Marvell Technology Group     | 4        | 1.58%   |
| ADATA Technology             | 4        | 1.58%   |
| SK hynix                     | 3        | 1.19%   |
| Silicon Motion               | 3        | 1.19%   |
| Kingston Technology Company  | 3        | 1.19%   |
| Broadcom / LSI               | 3        | 1.19%   |
| ASMedia Technology           | 3        | 1.19%   |
| Shenzhen Longsys Electronics | 2        | 0.79%   |
| Micron/Crucial Technology    | 2        | 0.79%   |
| VIA Technologies             | 1        | 0.4%    |
| Seagate Technology           | 1        | 0.4%    |
| Realtek Semiconductor        | 1        | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 39       | 12.75%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 16       | 5.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 13       | 4.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 13       | 4.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 13       | 4.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 11       | 3.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10       | 3.27%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 10       | 3.27%   |
| AMD 400 Series Chipset SATA Controller                                         | 10       | 3.27%   |
| Intel SATA Controller [RAID mode]                                              | 9        | 2.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 8        | 2.61%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7        | 2.29%   |
| Nvidia MCP61 SATA Controller                                                   | 6        | 1.96%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 6        | 1.96%   |
| AMD FCH SATA Controller D                                                      | 6        | 1.96%   |
| Phison E12 NVMe Controller                                                     | 5        | 1.63%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4        | 1.31%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4        | 1.31%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4        | 1.31%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 4        | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4        | 1.31%   |
| AMD 300 Series Chipset SATA Controller                                         | 4        | 1.31%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 4        | 1.31%   |
| Samsung NVMe SSD Controller 980                                                | 3        | 0.98%   |
| Kingston Company A2000 NVMe SSD                                                | 3        | 0.98%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 3        | 0.98%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 3        | 0.98%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3        | 0.98%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3        | 0.98%   |
| Unknown                                                                        | 3        | 0.98%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2        | 0.65%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2        | 0.65%   |
| Nvidia MCP61 IDE                                                               | 2        | 0.65%   |
| JMicron JMB363 SATA/IDE Controller                                             | 2        | 0.65%   |
| JMicron JMB361 AHCI/IDE                                                        | 2        | 0.65%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2        | 0.65%   |
| Intel 82Q35 Express PT IDER Controller                                         | 2        | 0.65%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 2        | 0.65%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 2        | 0.65%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                     | 2        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 146      | 58.17%  |
| NVMe | 45       | 17.93%  |
| IDE  | 42       | 16.73%  |
| RAID | 15       | 5.98%   |
| SAS  | 2        | 0.8%    |
| SCSI | 1        | 0.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 131      | 68.23%  |
| AMD    | 61       | 31.77%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 5        | 2.6%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 2.08%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 2.08%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 3        | 1.56%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 1.56%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3        | 1.56%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3        | 1.56%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 1.56%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 1.56%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 1.56%   |
| Intel Xeon CPU X3470 @ 2.93GHz              | 2        | 1.04%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 2        | 1.04%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz         | 2        | 1.04%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 2        | 1.04%   |
| Intel Pentium CPU G860 @ 3.00GHz            | 2        | 1.04%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 1.04%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.04%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 2        | 1.04%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 1.04%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 2        | 1.04%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 1.04%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 1.04%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 2        | 1.04%   |
| Intel Core 2 Quad CPU                       | 2        | 1.04%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2        | 1.04%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz        | 2        | 1.04%   |
| Intel Core 2 Duo                            | 2        | 1.04%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 1.04%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 1.04%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2        | 1.04%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 1.04%   |
| AMD Athlon 64 X2 Dual Core Processor 3600+  | 2        | 1.04%   |
| Intel Xeon E-2136 CPU @ 3.30GHz             | 1        | 0.52%   |
| Intel Xeon CPU X5647 @ 2.93GHz              | 1        | 0.52%   |
| Intel Xeon CPU X5550 @ 2.67GHz              | 1        | 0.52%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 0.52%   |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 0.52%   |
| Intel Xeon CPU E5504 @ 2.00GHz              | 1        | 0.52%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 0.52%   |
| Intel Xeon CPU E5-2676 v3 @ 2.40GHz         | 1        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 35       | 18.23%  |
| Intel Xeon              | 27       | 14.06%  |
| Intel Core i7           | 18       | 9.38%   |
| AMD Ryzen 5             | 15       | 7.81%   |
| Intel Core i3           | 12       | 6.25%   |
| AMD Ryzen 7             | 12       | 6.25%   |
| Intel Core 2 Quad       | 9        | 4.69%   |
| Intel Core 2 Duo        | 9        | 4.69%   |
| Intel Pentium           | 6        | 3.13%   |
| AMD Ryzen 3             | 5        | 2.6%    |
| Intel Pentium Dual-Core | 4        | 2.08%   |
| AMD Ryzen 9             | 4        | 2.08%   |
| AMD Phenom II X4        | 4        | 2.08%   |
| Intel Celeron           | 3        | 1.56%   |
| Other                   | 2        | 1.04%   |
| Intel Core i9           | 2        | 1.04%   |
| AMD Ryzen Threadripper  | 2        | 1.04%   |
| AMD FX                  | 2        | 1.04%   |
| AMD Athlon II X2        | 2        | 1.04%   |
| AMD Athlon Dual Core    | 2        | 1.04%   |
| AMD Athlon 64 X2        | 2        | 1.04%   |
| AMD A10                 | 2        | 1.04%   |
| Intel Pentium Dual      | 1        | 0.52%   |
| Intel Pentium D         | 1        | 0.52%   |
| Intel Core 2            | 1        | 0.52%   |
| Intel Atom              | 1        | 0.52%   |
| AMD Ryzen 5 PRO         | 1        | 0.52%   |
| AMD E2                  | 1        | 0.52%   |
| AMD E1                  | 1        | 0.52%   |
| AMD E                   | 1        | 0.52%   |
| AMD Athlon II X4        | 1        | 0.52%   |
| AMD Athlon              | 1        | 0.52%   |
| AMD A8                  | 1        | 0.52%   |
| AMD A6                  | 1        | 0.52%   |
| AMD A4                  | 1        | 0.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 77       | 40.1%   |
| 2       | 41       | 21.35%  |
| 8       | 16       | 8.33%   |
| 6       | 16       | 8.33%   |
| 12      | 12       | 6.25%   |
| 16      | 11       | 5.73%   |
| Unknown | 11       | 5.73%   |
| 24      | 3        | 1.56%   |
| 64      | 1        | 0.52%   |
| 48      | 1        | 0.52%   |
| 32      | 1        | 0.52%   |
| 18      | 1        | 0.52%   |
| 14      | 1        | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 190      | 98.96%  |
| 2      | 2        | 1.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 123      | 64.06%  |
| 2       | 58       | 30.21%  |
| Unknown | 11       | 5.73%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 24       | 12.5%   |
| IvyBridge   | 19       | 9.9%    |
| KabyLake    | 18       | 9.38%   |
| Skylake     | 17       | 8.85%   |
| Penryn      | 15       | 7.81%   |
| Zen 2       | 14       | 7.29%   |
| Zen+        | 12       | 6.25%   |
| SandyBridge | 12       | 6.25%   |
| Core        | 9        | 4.69%   |
| Zen         | 8        | 4.17%   |
| Piledriver  | 7        | 3.65%   |
| Nehalem     | 7        | 3.65%   |
| K10         | 7        | 3.65%   |
| Zen 3       | 6        | 3.13%   |
| K8 Hammer   | 4        | 2.08%   |
| Westmere    | 3        | 1.56%   |
| Jaguar      | 2        | 1.04%   |
| Unknown     | 2        | 1.04%   |
| Silvermont  | 1        | 0.52%   |
| NetBurst    | 1        | 0.52%   |
| CometLake   | 1        | 0.52%   |
| Broadwell   | 1        | 0.52%   |
| Bonnell     | 1        | 0.52%   |
| Bobcat      | 1        | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 81       | 40.7%   |
| Intel  | 67       | 33.67%  |
| AMD    | 51       | 25.63%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11       | 5.47%   |
| Intel HD Graphics 530                                                       | 11       | 5.47%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 9        | 4.48%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 3.48%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6        | 2.99%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 2.99%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 2.99%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5        | 2.49%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 4        | 1.99%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 1.99%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 1.99%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 1.99%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 1.99%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 1.99%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 1.49%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.49%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 1.49%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 1.49%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 3        | 1.49%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 1%      |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 1%      |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1%      |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 1%      |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1%      |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 1%      |
| Nvidia GK107GL [Quadro K2000]                                               | 2        | 1%      |
| Nvidia GF108 [GeForce GT 730]                                               | 2        | 1%      |
| Nvidia GF108 [GeForce GT 430]                                               | 2        | 1%      |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 1%      |
| Nvidia G72 [GeForce 7300 LE]                                                | 2        | 1%      |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 2        | 1%      |
| Intel HD Graphics 630                                                       | 2        | 1%      |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 1%      |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 1%      |
| AMD RV710 [Radeon HD 4350/4550]                                             | 2        | 1%      |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 2        | 1%      |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 1%      |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 2        | 1%      |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.5%    |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 79       | 40.51%  |
| 1 x Intel      | 57       | 29.23%  |
| 1 x AMD        | 48       | 24.62%  |
| 2 x Intel      | 5        | 2.56%   |
| Intel + Nvidia | 3        | 1.54%   |
| Intel + AMD    | 2        | 1.03%   |
| 2 x AMD        | 1        | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 122      | 62.89%  |
| Proprietary | 69       | 35.57%  |
| Unknown     | 3        | 1.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 85       | 43.37%  |
| 3.01-4.0   | 24       | 12.24%  |
| 1.01-2.0   | 24       | 12.24%  |
| 0.51-1.0   | 24       | 12.24%  |
| 7.01-8.0   | 17       | 8.67%   |
| 0.01-0.5   | 10       | 5.1%    |
| 5.01-6.0   | 7        | 3.57%   |
| 2.01-3.0   | 3        | 1.53%   |
| 8.01-16.0  | 2        | 1.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 23       | 13.77%  |
| Samsung Electronics  | 22       | 13.17%  |
| Dell                 | 20       | 11.98%  |
| BenQ                 | 13       | 7.78%   |
| AOC                  | 13       | 7.78%   |
| Acer                 | 12       | 7.19%   |
| Philips              | 11       | 6.59%   |
| Hewlett-Packard      | 11       | 6.59%   |
| Ancor Communications | 6        | 3.59%   |
| Fujitsu Siemens      | 5        | 2.99%   |
| ASUSTek Computer     | 5        | 2.99%   |
| Sony                 | 4        | 2.4%    |
| Lenovo               | 4        | 2.4%    |
| Iiyama               | 3        | 1.8%    |
| ViewSonic            | 2        | 1.2%    |
| NEC Computers        | 2        | 1.2%    |
| MSI                  | 2        | 1.2%    |
| ZL_                  | 1        | 0.6%    |
| Westinghouse         | 1        | 0.6%    |
| Vestel Elektronik    | 1        | 0.6%    |
| SGT                  | 1        | 0.6%    |
| LTV                  | 1        | 0.6%    |
| GRR                  | 1        | 0.6%    |
| FND                  | 1        | 0.6%    |
| Denver               | 1        | 0.6%    |
| Apple                | 1        | 0.6%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0601 1600x900                        | 2        | 1.16%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2        | 1.16%   |
| BenQ GW2780 BNQ78E6 1920x1080 600x340mm 27.2-inch                      | 2        | 1.16%   |
| ASUSTek Computer ROG XG279Q AUS278D 2560x1440 600x340mm 27.2-inch      | 2        | 1.16%   |
| AOC 24G2W1G4 AOC2402 1920x1080 530x300mm 24.0-inch                     | 2        | 1.16%   |
| Ancor Communications MX27AQ ACI27A5 2560x1440 600x340mm 27.2-inch      | 2        | 1.16%   |
| Acer S240HL ACR0289 1920x1080 530x300mm 24.0-inch                      | 2        | 1.16%   |
| ZL_ zhuoyue-HDMI ZL_2716 2560x1440 600x330mm 27.0-inch                 | 1        | 0.58%   |
| Westinghouse LCM-19w4 WDE1904 1440x900 410x260mm 19.1-inch             | 1        | 0.58%   |
| ViewSonic VX1940w VSC6A20 1680x1050 410x260mm 19.1-inch                | 1        | 0.58%   |
| ViewSonic LCD Monitor VSCBD2B 1920x1080 480x270mm 21.7-inch            | 1        | 0.58%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch     | 1        | 0.58%   |
| Sony TV SNYEE01 1920x1080                                              | 1        | 0.58%   |
| Sony TV SNY9C01 1360x768                                               | 1        | 0.58%   |
| Sony SDM-S75D/F/N SNY3800 1280x1024 340x270mm 17.1-inch                | 1        | 0.58%   |
| Sony SDM-E76D SNYB200 1280x1024 340x270mm 17.1-inch                    | 1        | 0.58%   |
| SGT YSD SGT1700 1280x1024 380x210mm 17.1-inch                          | 1        | 0.58%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch      | 1        | 0.58%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch      | 1        | 0.58%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 520x290mm 23.4-inch      | 1        | 0.58%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch    | 1        | 0.58%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                       | 1        | 0.58%   |
| Samsung Electronics SyncMaster SAM05B0 1920x1080                       | 1        | 0.58%   |
| Samsung Electronics SyncMaster SAM0373 1680x1050 440x300mm 21.0-inch   | 1        | 0.58%   |
| Samsung Electronics SyncMaster SAM02FA 1440x900 410x260mm 19.1-inch    | 1        | 0.58%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 370x230mm 17.2-inch    | 1        | 0.58%   |
| Samsung Electronics SyncMaster SAM027D 1680x1050 430x270mm 20.0-inch   | 1        | 0.58%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 280x210mm 13.8-inch    | 1        | 0.58%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 480x270mm 21.7-inch    | 1        | 0.58%   |
| Samsung Electronics SME2020 SAM06A0 1600x900 440x250mm 19.9-inch       | 1        | 0.58%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 480x270mm 21.7-inch     | 1        | 0.58%   |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 440x250mm 19.9-inch   | 1        | 0.58%   |
| Samsung Electronics S24H85x SAM0E0C 2560x1440 530x300mm 24.0-inch      | 1        | 0.58%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch      | 1        | 0.58%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 530x300mm 24.0-inch      | 1        | 0.58%   |
| Samsung Electronics S24C450 SAM09CB 1920x1080 530x300mm 24.0-inch      | 1        | 0.58%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch       | 1        | 0.58%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 1110x620mm 50.1-inch | 1        | 0.58%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 530x300mm 24.0-inch     | 1        | 0.58%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 700x390mm 31.5-inch      | 1        | 0.58%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 73       | 43.71%  |
| 2560x1440 (QHD)    | 16       | 9.58%   |
| 1280x1024 (SXGA)   | 16       | 9.58%   |
| 1600x900 (HD+)     | 12       | 7.19%   |
| 1440x900 (WXGA+)   | 11       | 6.59%   |
| 1680x1050 (WSXGA+) | 9        | 5.39%   |
| 1366x768 (WXGA)    | 7        | 4.19%   |
| 3840x2160 (4K)     | 6        | 3.59%   |
| 1920x1200 (WUXGA)  | 5        | 2.99%   |
| 2560x1080          | 3        | 1.8%    |
| 1024x768 (XGA)     | 3        | 1.8%    |
| 1360x768           | 2        | 1.2%    |
| 3440x1440          | 1        | 0.6%    |
| 2560x1600          | 1        | 0.6%    |
| 1920x540           | 1        | 0.6%    |
| 1600x1200          | 1        | 0.6%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 31       | 18.34%  |
| 19      | 26       | 15.38%  |
| 27      | 21       | 12.43%  |
| 21      | 21       | 12.43%  |
| 23      | 16       | 9.47%   |
| 17      | 10       | 5.92%   |
| 18      | 8        | 4.73%   |
| 31      | 7        | 4.14%   |
| Unknown | 6        | 3.55%   |
| 20      | 4        | 2.37%   |
| 22      | 3        | 1.78%   |
| 34      | 2        | 1.18%   |
| 29      | 2        | 1.18%   |
| 28      | 2        | 1.18%   |
| 15      | 2        | 1.18%   |
| 50      | 1        | 0.59%   |
| 42      | 1        | 0.59%   |
| 36      | 1        | 0.59%   |
| 33      | 1        | 0.59%   |
| 32      | 1        | 0.59%   |
| 16      | 1        | 0.59%   |
| 14      | 1        | 0.59%   |
| 13      | 1        | 0.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 63       | 38.18%  |
| 401-500     | 53       | 32.12%  |
| 601-700     | 12       | 7.27%   |
| 351-400     | 11       | 6.67%   |
| 301-350     | 11       | 6.67%   |
| Unknown     | 6        | 3.64%   |
| 701-800     | 5        | 3.03%   |
| 201-300     | 2        | 1.21%   |
| 1001-1500   | 1        | 0.61%   |
| 901-1000    | 1        | 0.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 114      | 69.94%  |
| 16/10 | 25       | 15.34%  |
| 5/4   | 14       | 8.59%   |
| 4/3   | 4        | 2.45%   |
| 21/9  | 4        | 2.45%   |
| 3/2   | 2        | 1.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 61       | 36.31%  |
| 151-200        | 35       | 20.83%  |
| 301-350        | 21       | 12.5%   |
| 351-500        | 13       | 7.74%   |
| 141-150        | 13       | 7.74%   |
| 251-300        | 9        | 5.36%   |
| Unknown        | 6        | 3.57%   |
| 91-100         | 3        | 1.79%   |
| 121-130        | 2        | 1.19%   |
| 501-1000       | 2        | 1.19%   |
| More than 1000 | 1        | 0.6%    |
| 131-140        | 1        | 0.6%    |
| 101-110        | 1        | 0.6%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 114      | 67.86%  |
| 101-120 | 38       | 22.62%  |
| Unknown | 6        | 3.57%   |
| 121-160 | 5        | 2.98%   |
| 161-240 | 3        | 1.79%   |
| 1-50    | 2        | 1.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 161      | 83.42%  |
| 0     | 19       | 9.84%   |
| 2     | 12       | 6.22%   |
| 3     | 1        | 0.52%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 110      | 47.83%  |
| Intel                    | 84       | 36.52%  |
| Qualcomm Atheros         | 14       | 6.09%   |
| Broadcom                 | 7        | 3.04%   |
| Marvell Technology Group | 3        | 1.3%    |
| Ralink Technology        | 2        | 0.87%   |
| Ralink                   | 2        | 0.87%   |
| Xiaomi                   | 1        | 0.43%   |
| TP-Link                  | 1        | 0.43%   |
| NetGear                  | 1        | 0.43%   |
| Microchip Technology     | 1        | 0.43%   |
| Mellanox Technologies    | 1        | 0.43%   |
| MediaTek                 | 1        | 0.43%   |
| Edimax Technology        | 1        | 0.43%   |
| D-Link System            | 1        | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 88       | 33.72%  |
| Intel I211 Gigabit Network Connection                                         | 16       | 6.13%   |
| Intel Ethernet Connection I217-LM                                             | 11       | 4.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 8        | 3.07%   |
| Intel Ethernet Connection (2) I219-LM                                         | 8        | 3.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 8        | 3.07%   |
| Intel Ethernet Connection (2) I219-V                                          | 7        | 2.68%   |
| Intel Wi-Fi 6 AX200                                                           | 6        | 2.3%    |
| Intel 82574L Gigabit Network Connection                                       | 6        | 2.3%    |
| Intel Ethernet Connection (7) I219-V                                          | 5        | 1.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 4        | 1.53%   |
| Intel 82579V Gigabit Network Connection                                       | 4        | 1.53%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 4        | 1.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 3        | 1.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3        | 1.15%   |
| Intel Wireless 7265                                                           | 3        | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3        | 1.15%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 2        | 0.77%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2        | 0.77%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2        | 0.77%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2        | 0.77%   |
| Ralink RT5370 Wireless Adapter                                                | 2        | 0.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2        | 0.77%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 2        | 0.77%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 2        | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 0.77%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 2        | 0.77%   |
| Intel Wireless-AC 9260                                                        | 2        | 0.77%   |
| Intel Wireless 8265 / 8275                                                    | 2        | 0.77%   |
| Intel Wireless 7260                                                           | 2        | 0.77%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 0.77%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2        | 0.77%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 2        | 0.77%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 2        | 0.77%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1        | 0.38%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 1        | 0.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1        | 0.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.38%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 22       | 36.67%  |
| Realtek Semiconductor | 21       | 35%     |
| Broadcom              | 5        | 8.33%   |
| Qualcomm Atheros      | 4        | 6.67%   |
| Ralink Technology     | 2        | 3.33%   |
| Ralink                | 2        | 3.33%   |
| TP-Link               | 1        | 1.67%   |
| NetGear               | 1        | 1.67%   |
| MediaTek              | 1        | 1.67%   |
| Edimax Technology     | 1        | 1.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 6        | 9.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 4        | 6.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 3        | 4.92%   |
| Intel Wireless 7265                                                 | 3        | 4.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 3        | 4.92%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 2        | 3.28%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2        | 3.28%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 2        | 3.28%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                          | 2        | 3.28%   |
| Ralink RT5370 Wireless Adapter                                      | 2        | 3.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 2        | 3.28%   |
| Intel Wireless-AC 9260                                              | 2        | 3.28%   |
| Intel Wireless 8265 / 8275                                          | 2        | 3.28%   |
| Intel Wireless 7260                                                 | 2        | 3.28%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 2        | 3.28%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller              | 2        | 3.28%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                 | 1        | 1.64%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1        | 1.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 1        | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1        | 1.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter            | 1        | 1.64%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                              | 1        | 1.64%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter               | 1        | 1.64%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 1        | 1.64%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                           | 1        | 1.64%   |
| Ralink RT2500 Wireless 802.11bg                                     | 1        | 1.64%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 1        | 1.64%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 1        | 1.64%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]    | 1        | 1.64%   |
| MediaTek 802.11ac Wireless LAN Card                                 | 1        | 1.64%   |
| Intel Wireless 3165                                                 | 1        | 1.64%   |
| Intel Centrino Wireless-N 2230                                      | 1        | 1.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 1        | 1.64%   |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 1        | 1.64%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]   | 1        | 1.64%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1        | 1.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 101      | 51.79%  |
| Intel                    | 77       | 39.49%  |
| Qualcomm Atheros         | 10       | 5.13%   |
| Marvell Technology Group | 3        | 1.54%   |
| Broadcom                 | 2        | 1.03%   |
| Xiaomi                   | 1        | 0.51%   |
| D-Link System            | 1        | 0.51%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 88       | 44.44%  |
| Intel I211 Gigabit Network Connection                                         | 16       | 8.08%   |
| Intel Ethernet Connection I217-LM                                             | 11       | 5.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 8        | 4.04%   |
| Intel Ethernet Connection (2) I219-LM                                         | 8        | 4.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 8        | 4.04%   |
| Intel Ethernet Connection (2) I219-V                                          | 7        | 3.54%   |
| Intel 82574L Gigabit Network Connection                                       | 6        | 3.03%   |
| Intel Ethernet Connection (7) I219-V                                          | 5        | 2.53%   |
| Intel 82579V Gigabit Network Connection                                       | 4        | 2.02%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 4        | 2.02%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3        | 1.52%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 2        | 1.01%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 2        | 1.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 1.01%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 2        | 1.01%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 1.01%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2        | 1.01%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1        | 0.51%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.51%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.51%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1        | 0.51%   |
| Intel I210 Gigabit Network Connection                                         | 1        | 0.51%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.51%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 0.51%   |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 0.51%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 0.51%   |
| Intel 82578DM Gigabit Network Connection                                      | 1        | 0.51%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 0.51%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 1        | 0.51%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 0.51%   |
| Broadcom BCM4401-B0 100Base-TX                                                | 1        | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 187      | 76.33%  |
| WiFi     | 56       | 22.86%  |
| Modem    | 1        | 0.41%   |
| Unknown  | 1        | 0.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 176      | 90.26%  |
| WiFi     | 19       | 9.74%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 134      | 69.79%  |
| 2     | 41       | 21.35%  |
| 3     | 8        | 4.17%   |
| 0     | 5        | 2.6%    |
| 4     | 4        | 2.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 187      | 95.41%  |
| Yes  | 9        | 4.59%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 22       | 41.51%  |
| Cambridge Silicon Radio         | 11       | 20.75%  |
| Realtek Semiconductor           | 5        | 9.43%   |
| Apple                           | 5        | 9.43%   |
| Qualcomm Atheros Communications | 2        | 3.77%   |
| Integrated System Solution      | 2        | 3.77%   |
| IMC Networks                    | 2        | 3.77%   |
| ASUSTek Computer                | 2        | 3.77%   |
| TP-Link                         | 1        | 1.89%   |
| HTC (High Tech Computer)        | 1        | 1.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 11       | 20.75%  |
| Intel Bluetooth wireless interface                                   | 7        | 13.21%  |
| Intel AX200 Bluetooth                                                | 6        | 11.32%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 3        | 5.66%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 3        | 5.66%   |
| Realtek  Bluetooth Adapter                                           | 2        | 3.77%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 2        | 3.77%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device          | 2        | 3.77%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2        | 3.77%   |
| Intel AX201 Bluetooth                                                | 2        | 3.77%   |
| Apple Apple Broadcom Built-in Bluetooth                              | 2        | 3.77%   |
| TP-Link TP-Link UB500 Adapter                                        | 1        | 1.89%   |
| Realtek  Bluetooth 4.0 Adapter                                       | 1        | 1.89%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 1.89%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 1        | 1.89%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1        | 1.89%   |
| Integrated System Solution Bluetooth Device                          | 1        | 1.89%   |
| IMC Networks Realtek Bluetooth Adapter                               | 1        | 1.89%   |
| IMC Networks Realtek Bluetooth 4.0 Adapter                           | 1        | 1.89%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 1.89%   |
| ASUS Bluetooth Controller                                            | 1        | 1.89%   |
| ASUS ASUS USB-BT500                                                  | 1        | 1.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 126      | 40.38%  |
| Nvidia                      | 77       | 24.68%  |
| AMD                         | 72       | 23.08%  |
| C-Media Electronics         | 7        | 2.24%   |
| Texas Instruments           | 3        | 0.96%   |
| Logitech                    | 3        | 0.96%   |
| JMTek                       | 3        | 0.96%   |
| SteelSeries ApS             | 2        | 0.64%   |
| GN Netcom                   | 2        | 0.64%   |
| Generalplus Technology      | 2        | 0.64%   |
| Focusrite-Novation          | 2        | 0.64%   |
| BEHRINGER International     | 2        | 0.64%   |
| Yamaha                      | 1        | 0.32%   |
| VIA Technologies            | 1        | 0.32%   |
| Nektar                      | 1        | 0.32%   |
| KORG                        | 1        | 0.32%   |
| Kingston Technology         | 1        | 0.32%   |
| FiiO Electronics Technology | 1        | 0.32%   |
| Creative Labs               | 1        | 0.32%   |
| Corsair                     | 1        | 0.32%   |
| Cambridge Silicon Radio     | 1        | 0.32%   |
| ASUSTek Computer            | 1        | 0.32%   |
| Astro Gaming                | 1        | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 19       | 5.32%   |
| AMD Starship/Matisse HD Audio Controller                                   | 19       | 5.32%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 16       | 4.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15       | 4.2%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 14       | 3.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11       | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11       | 3.08%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11       | 3.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 2.8%    |
| Intel Cannon Lake PCH cAVS                                                 | 9        | 2.52%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 9        | 2.52%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8        | 2.24%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 8        | 2.24%   |
| Intel 200 Series PCH HD Audio                                              | 8        | 2.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8        | 2.24%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 1.96%   |
| AMD FCH Azalia Controller                                                  | 7        | 1.96%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 1.68%   |
| AMD Navi 10 HDMI Audio                                                     | 6        | 1.68%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 1.4%    |
| Nvidia MCP61 High Definition Audio                                         | 5        | 1.4%    |
| Nvidia GK107 HDMI Audio Controller                                         | 5        | 1.4%    |
| Nvidia GP106 High Definition Audio Controller                              | 4        | 1.12%   |
| Nvidia GM206 High Definition Audio Controller                              | 4        | 1.12%   |
| Nvidia GM204 High Definition Audio Controller                              | 4        | 1.12%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 1.12%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 4        | 1.12%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 1.12%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 4        | 1.12%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 1.12%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 1.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3        | 0.84%   |
| Nvidia High Definition Audio Controller                                    | 3        | 0.84%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 0.84%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3        | 0.84%   |
| Nvidia GA104 High Definition Audio Controller                              | 3        | 0.84%   |
| JMTek USB PnP Audio Device                                                 | 3        | 0.84%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 0.84%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 3        | 0.84%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 3        | 0.84%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 46       | 20.91%  |
| Unknown             | 30       | 13.64%  |
| Samsung Electronics | 20       | 9.09%   |
| SK hynix            | 18       | 8.18%   |
| Corsair             | 18       | 8.18%   |
| Crucial             | 14       | 6.36%   |
| Unknown             | 14       | 6.36%   |
| Micron Technology   | 13       | 5.91%   |
| G.Skill             | 13       | 5.91%   |
| Team                | 6        | 2.73%   |
| Patriot             | 3        | 1.36%   |
| Nanya Technology    | 3        | 1.36%   |
| A-DATA Technology   | 3        | 1.36%   |
| Transcend           | 2        | 0.91%   |
| Atermiter           | 2        | 0.91%   |
| AMD                 | 2        | 0.91%   |
| Unknown (D386)      | 1        | 0.45%   |
| Unifosa             | 1        | 0.45%   |
| TakeMS              | 1        | 0.45%   |
| Super Talent        | 1        | 0.45%   |
| Strontium           | 1        | 0.45%   |
| Smart               | 1        | 0.45%   |
| Ramaxel Technology  | 1        | 0.45%   |
| Kllisre             | 1        | 0.45%   |
| Hikvision           | 1        | 0.45%   |
| Goodram             | 1        | 0.45%   |
| Goldkey             | 1        | 0.45%   |
| Elpida              | 1        | 0.45%   |
| Avant               | 1        | 0.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown                                                | 14       | 5.76%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s   | 5        | 2.06%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s     | 4        | 1.65%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 3        | 1.23%   |
| Unknown RAM Module 2GB DIMM DDR2                       | 3        | 1.23%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3             | 3        | 1.23%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3200MT/s    | 3        | 1.23%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s  | 3        | 1.23%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s               | 2        | 0.82%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 2        | 0.82%   |
| Unknown RAM Module 2GB DIMM 400MT/s                    | 2        | 0.82%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 2        | 0.82%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 2        | 0.82%   |
| Samsung RAM Module 4GB SODIMM DDR4 2133MT/s            | 2        | 0.82%   |
| Micron RAM 18KSF51272AZ-1G4M1 4GB DIMM DDR3 1333MT/s   | 2        | 0.82%   |
| Kingston RAM Module 1GB DIMM DDR2 667MT/s              | 2        | 0.82%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1600MT/s    | 2        | 0.82%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s | 2        | 0.82%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s  | 2        | 0.82%   |
| Crucial RAM BL16G32C16U4B.16FE 16GB DIMM DDR4 3200MT/s | 2        | 0.82%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 2667MT/s  | 2        | 0.82%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 1        | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 1        | 0.41%   |
| Unknown RAM Module 512MB DIMM SDRAM                    | 1        | 0.41%   |
| Unknown RAM Module 4GB SODIMM DDR3 800MT/s             | 1        | 0.41%   |
| Unknown RAM Module 4GB DIMM SDRAM                      | 1        | 0.41%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s              | 1        | 0.41%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                   | 1        | 0.41%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 1        | 0.41%   |
| Unknown RAM Module 2GB DIMM SDRAM 533MT/s              | 1        | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 1        | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s               | 1        | 0.41%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                   | 1        | 0.41%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s               | 1        | 0.41%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s               | 1        | 0.41%   |
| Unknown (D386) RAM Module 16GB DIMM DDR4 2133MT/s      | 1        | 0.41%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s      | 1        | 0.41%   |
| Transcend RAM TS128MLQ64V8U 1GB DIMM DDR2 800MT/s      | 1        | 0.41%   |
| Transcend RAM JM1333KLN-2G 2GB DIMM DDR3 1333MT/s      | 1        | 0.41%   |
| Team RAM TEAMGROUP-UD4-2133 8GB DIMM DDR4 2133MT/s     | 1        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 82       | 43.62%  |
| DDR3    | 68       | 36.17%  |
| DDR2    | 19       | 10.11%  |
| Unknown | 12       | 6.38%   |
| SDRAM   | 5        | 2.66%   |
| DDR     | 2        | 1.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 172      | 91.49%  |
| SODIMM | 14       | 7.45%   |
| RIMM   | 2        | 1.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 71       | 33.81%  |
| 4096  | 62       | 29.52%  |
| 2048  | 35       | 16.67%  |
| 16384 | 28       | 13.33%  |
| 1024  | 10       | 4.76%   |
| 32768 | 2        | 0.95%   |
| 512   | 2        | 0.95%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 40       | 19.9%   |
| 1333    | 30       | 14.93%  |
| 3200    | 26       | 12.94%  |
| 2133    | 23       | 11.44%  |
| 2400    | 12       | 5.97%   |
| 2667    | 11       | 5.47%   |
| 800     | 11       | 5.47%   |
| Unknown | 9        | 4.48%   |
| 2666    | 8        | 3.98%   |
| 1066    | 6        | 2.99%   |
| 667     | 6        | 2.99%   |
| 3600    | 4        | 1.99%   |
| 400     | 3        | 1.49%   |
| 1867    | 2        | 1%      |
| 1866    | 2        | 1%      |
| 1067    | 2        | 1%      |
| 333     | 2        | 1%      |
| 3733    | 1        | 0.5%    |
| 3400    | 1        | 0.5%    |
| 1200    | 1        | 0.5%    |
| 533     | 1        | 0.5%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 2        | 66.67%  |
| Hewlett-Packard    | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                                             | Desktops | Percent |
|-------------------------------------------------------------------------------------------------------------------|----------|---------|
| HP HP LaserJet MFP E52645 LaserJet 0 LaserJet 0 LaserJet 1 LaserJet 1 LaserJet 2 LaserJet 2 LaserJet 3 LaserJet 3 | 1        | 33.33%  |
| Brother MFC-L2685DW                                                                                               | 1        | 33.33%  |
| Brother HL-1430 Laser Printer                                                                                     | 1        | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 100 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 10       | 47.62%  |
| Microdia                | 2        | 9.52%   |
| Arkmicro Technologies   | 2        | 9.52%   |
| Z-Star Microelectronics | 1        | 4.76%   |
| IMC Networks            | 1        | 4.76%   |
| Hewlett-Packard         | 1        | 4.76%   |
| Genesys Logic           | 1        | 4.76%   |
| Creative Technology     | 1        | 4.76%   |
| Chicony Electronics     | 1        | 4.76%   |
| Aveo Technology         | 1        | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Logitech Webcam C270             | 3        | 14.29%  |
| Arkmicro USB2.0 PC CAMERA        | 2        | 9.52%   |
| Z-Star Lenovo USB2.0 UVC Camera  | 1        | 4.76%   |
| Microdia USB 2.0 Camera          | 1        | 4.76%   |
| Microdia ASUS USB2.0 Webcam      | 1        | 4.76%   |
| Logitech Webcam C930e            | 1        | 4.76%   |
| Logitech Webcam C310             | 1        | 4.76%   |
| Logitech Webcam C170             | 1        | 4.76%   |
| Logitech HD Pro Webcam C920      | 1        | 4.76%   |
| Logitech C922 Pro Stream Webcam  | 1        | 4.76%   |
| Logitech C670i FHD Webcam        | 1        | 4.76%   |
| Logitech BRIO Ultra HD Webcam    | 1        | 4.76%   |
| IMC Networks XHC Camera          | 1        | 4.76%   |
| HP Realtek PC Camera             | 1        | 4.76%   |
| Genesys Logic Digital Microscope | 1        | 4.76%   |
| Creative Webcam Instant          | 1        | 4.76%   |
| Chicony HP 0.3MP Webcam          | 1        | 4.76%   |
| Aveo Camera                      | 1        | 4.76%   |

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
| 1     | 82       | 42.71%  |
| 0     | 79       | 41.15%  |
| 2     | 26       | 13.54%  |
| 3     | 3        | 1.56%   |
| 4     | 2        | 1.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 96       | 69.57%  |
| Net/wireless             | 25       | 18.12%  |
| Sound                    | 6        | 4.35%   |
| Bluetooth                | 5        | 3.62%   |
| Card reader              | 3        | 2.17%   |
| Network                  | 2        | 1.45%   |
| Net/ethernet             | 1        | 0.72%   |

