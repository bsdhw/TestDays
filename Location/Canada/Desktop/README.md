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

Total: 338

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| Lenovo        | SHARKBAY 0B98401 PRO        | [36a5bc62bf](https://bsd-hardware.info/?probe=36a5bc62bf) | Sep 27, 2021 |
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
| Lenovo        | 30D9 No DPK                 | [061ad76c0e](https://bsd-hardware.info/?probe=061ad76c0e) | Mar 20, 2021 |
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

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| OPNsense 22.7.10  | 14       | 5.04%   |
| helloSystem 0.7.0 | 9        | 3.24%   |
| OPNsense 22.7.8   | 8        | 2.88%   |
| OPNsense 22.1.8   | 8        | 2.88%   |
| OPNsense 22.1.10  | 8        | 2.88%   |
| OPNsense 21.1.4   | 8        | 2.88%   |
| helloSystem 0.5.0 | 8        | 2.88%   |
| OPNsense 22.1.7   | 7        | 2.52%   |
| OPNsense 22.1     | 7        | 2.52%   |
| OPNsense 21.7     | 7        | 2.52%   |
| OPNsense 21.1.3   | 7        | 2.52%   |
| OPNsense 21.1     | 7        | 2.52%   |
| OPNsense 22.7.4   | 6        | 2.16%   |
| OPNsense 22.1.6   | 6        | 2.16%   |
| OPNsense 21.1.5   | 6        | 2.16%   |
| OPNsense 20.7.8   | 6        | 2.16%   |
| OPNsense 22.7.11  | 5        | 1.8%    |
| OPNsense 22.7     | 5        | 1.8%    |
| OPNsense 21.7.7   | 5        | 1.8%    |
| OPNsense 21.7.3   | 5        | 1.8%    |
| OPNsense 21.7.1   | 5        | 1.8%    |
| OPNsense 21.1.6   | 5        | 1.8%    |
| OPNsense 21.1.1   | 5        | 1.8%    |
| FreeBSD 13.1-p5   | 5        | 1.8%    |
| FreeBSD 13.1      | 5        | 1.8%    |
| FreeBSD 12.2      | 5        | 1.8%    |
| OPNsense 23.1     | 4        | 1.44%   |
| OPNsense 22.7.9   | 4        | 1.44%   |
| OPNsense 22.7.7   | 4        | 1.44%   |
| OPNsense 22.1.3   | 4        | 1.44%   |
| OPNsense 21.7.8   | 4        | 1.44%   |
| OPNsense 21.7.4   | 4        | 1.44%   |
| OPNsense 22.7.6   | 3        | 1.08%   |
| OPNsense 22.7.3   | 3        | 1.08%   |
| OPNsense 22.7.2   | 3        | 1.08%   |
| OPNsense 22.1.9   | 3        | 1.08%   |
| OPNsense 21.1.8   | 3        | 1.08%   |
| OPNsense 21.1.7   | 3        | 1.08%   |
| OPNsense 21.1.2   | 3        | 1.08%   |
| OpenBSD 7.1       | 3        | 1.08%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 141      | 65.28%  |
| FreeBSD     | 41       | 18.98%  |
| helloSystem | 21       | 9.72%   |
| OpenBSD     | 5        | 2.31%   |
| GhostBSD    | 3        | 1.39%   |
| FreeNAS     | 3        | 1.39%   |
| TrueNAS     | 1        | 0.46%   |
| pfSense     | 1        | 0.46%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 212      | 99.53%  |
| i386  | 1        | 0.47%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 160      | 74.07%  |
| helloDesktop | 24       | 11.11%  |
| KDE5         | 9        | 4.17%   |
| XFCE         | 8        | 3.7%    |
| MATE         | 6        | 2.78%   |
| GNOME        | 2        | 0.93%   |
| Cinnamon     | 2        | 0.93%   |
| X-Cinnamon   | 1        | 0.46%   |
| Window Maker | 1        | 0.46%   |
| Openbox      | 1        | 0.46%   |
| LXDE         | 1        | 0.46%   |
| DWM          | 1        | 0.46%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 161      | 75.59%  |
| X11     | 51       | 23.94%  |
| Wayland | 1        | 0.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 170      | 78.7%   |
| SLiM    | 25       | 11.57%  |
| SDDM    | 12       | 5.56%   |
| LightDM | 4        | 1.85%   |
| XDM     | 3        | 1.39%   |
| Ly      | 1        | 0.46%   |
| GDM     | 1        | 0.46%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 156      | 72.9%   |
| en_US   | 33       | 15.42%  |
| C       | 17       | 7.94%   |
| en_CA   | 5        | 2.34%   |
| fr_FR   | 2        | 0.93%   |
| en      | 1        | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 180      | 82.95%  |
| BIOS | 37       | 17.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 118      | 53.64%  |
| Zfs    | 90       | 40.91%  |
| Cd9660 | 7        | 3.18%   |
| Ffs    | 5        | 2.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 197      | 92.49%  |
| MBR     | 15       | 7.04%   |
| Unknown | 1        | 0.47%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 27       | 12.68%  |
| Dell                       | 26       | 12.21%  |
| Hewlett-Packard            | 25       | 11.74%  |
| Lenovo                     | 16       | 7.51%   |
| Unknown                    | 16       | 7.51%   |
| Protectli                  | 14       | 6.57%   |
| Intel                      | 13       | 6.1%    |
| Gigabyte Technology        | 13       | 6.1%    |
| ASRock                     | 12       | 5.63%   |
| Supermicro                 | 11       | 5.16%   |
| MSI                        | 9        | 4.23%   |
| PC Engines                 | 5        | 2.35%   |
| Techvision                 | 4        | 1.88%   |
| Acer                       | 4        | 1.88%   |
| AZW                        | 2        | 0.94%   |
| Yanling                    | 1        | 0.47%   |
| Shuttle                    | 1        | 0.47%   |
| ShenZhen MinWin Technology | 1        | 0.47%   |
| SeeedStudio                | 1        | 0.47%   |
| Quanta                     | 1        | 0.47%   |
| Pegatron                   | 1        | 0.47%   |
| IBM                        | 1        | 0.47%   |
| HARDKERNEL                 | 1        | 0.47%   |
| Datto                      | 1        | 0.47%   |
| CncTion                    | 1        | 0.47%   |
| Cisco                      | 1        | 0.47%   |
| Biostar                    | 1        | 0.47%   |
| ASRockRack                 | 1        | 0.47%   |
| Apple                      | 1        | 0.47%   |
| AMI                        | 1        | 0.47%   |
| ADI Engineering            | 1        | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 16       | 7.51%   |
| Protectli FW4B                     | 7        | 3.29%   |
| Protectli FW6                      | 5        | 2.35%   |
| Intel Q3XXG4-P V1.0                | 5        | 2.35%   |
| Techvision TVI7309X                | 4        | 1.88%   |
| Intel NDISB533                     | 4        | 1.88%   |
| HP EliteDesk 800 G1 SFF            | 3        | 1.41%   |
| Dell OptiPlex 9010                 | 3        | 1.41%   |
| Dell OptiPlex 7010                 | 3        | 1.41%   |
| Dell G5 5090                       | 3        | 1.41%   |
| ASUS All Series                    | 3        | 1.41%   |
| Supermicro X8STi                   | 2        | 0.94%   |
| PC Engines apu4                    | 2        | 0.94%   |
| PC Engines APU2                    | 2        | 0.94%   |
| Lenovo ThinkCentre M93p 10A8S16X0J | 2        | 0.94%   |
| HP Z440 Workstation                | 2        | 0.94%   |
| HP Compaq Elite 8300 SFF           | 2        | 0.94%   |
| HP Compaq 8200 Elite SFF PC        | 2        | 0.94%   |
| Dell Precision WorkStation T3500   | 2        | 0.94%   |
| Dell Precision Tower 5810          | 2        | 0.94%   |
| Dell OptiPlex 7020                 | 2        | 0.94%   |
| Dell OptiPlex 3020                 | 2        | 0.94%   |
| ASUS P8H77-I                       | 2        | 0.94%   |
| ASUS M5A97 PLUS                    | 2        | 0.94%   |
| ASRock H110M-DGS R3.0              | 2        | 0.94%   |
| ASRock B450M Pro4                  | 2        | 0.94%   |
| Yanling YL-KBR6L                   | 1        | 0.47%   |
| Supermicro X9SCL/X9SCM             | 1        | 0.47%   |
| Supermicro X9DR3-F                 | 1        | 0.47%   |
| Supermicro X7SPA-HF                | 1        | 0.47%   |
| Supermicro X7SLA                   | 1        | 0.47%   |
| Supermicro SYS-E300-9A             | 1        | 0.47%   |
| Supermicro SYS-5019S-ML            | 1        | 0.47%   |
| Supermicro SYS-5019D-FN8TP         | 1        | 0.47%   |
| Supermicro SYS-5019A-FTN4          | 1        | 0.47%   |
| Supermicro AS -5019D-FTN4          | 1        | 0.47%   |
| Shuttle DH110                      | 1        | 0.47%   |
| ShenZhen MinWin MW-GMLK-2.5G6L     | 1        | 0.47%   |
| SeeedStudio ODYSSEY-X86J4105       | 1        | 0.47%   |
| Quanta 120-1135                    | 1        | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Dell OptiPlex                  | 18       | 8.45%   |
| Unknown                        | 16       | 7.51%   |
| Lenovo ThinkCentre             | 14       | 6.57%   |
| Protectli FW4B                 | 7        | 3.29%   |
| HP ProDesk                     | 7        | 3.29%   |
| ASUS PRIME                     | 6        | 2.82%   |
| Protectli FW6                  | 5        | 2.35%   |
| Intel Q3XXG4-P                 | 5        | 2.35%   |
| HP EliteDesk                   | 5        | 2.35%   |
| HP Compaq                      | 5        | 2.35%   |
| Dell Precision                 | 5        | 2.35%   |
| Techvision TVI7309X            | 4        | 1.88%   |
| Intel NDISB533                 | 4        | 1.88%   |
| ASUS ROG                       | 4        | 1.88%   |
| Acer Aspire                    | 4        | 1.88%   |
| Dell G5                        | 3        | 1.41%   |
| ASUS All                       | 3        | 1.41%   |
| ASRock B450M                   | 3        | 1.41%   |
| Supermicro X8STi               | 2        | 0.94%   |
| PC Engines apu4                | 2        | 0.94%   |
| PC Engines APU2                | 2        | 0.94%   |
| HP Z440                        | 2        | 0.94%   |
| ASUS TUF                       | 2        | 0.94%   |
| ASUS P8H77-I                   | 2        | 0.94%   |
| ASUS M5A97                     | 2        | 0.94%   |
| ASRock H110M-DGS               | 2        | 0.94%   |
| Yanling YL-KBR6L               | 1        | 0.47%   |
| Supermicro X9SCL               | 1        | 0.47%   |
| Supermicro X9DR3-F             | 1        | 0.47%   |
| Supermicro X7SPA-HF            | 1        | 0.47%   |
| Supermicro X7SLA               | 1        | 0.47%   |
| Supermicro SYS-E300-9A         | 1        | 0.47%   |
| Supermicro SYS-5019S-ML        | 1        | 0.47%   |
| Supermicro SYS-5019D-FN8TP     | 1        | 0.47%   |
| Supermicro SYS-5019A-FTN4      | 1        | 0.47%   |
| Supermicro AS                  | 1        | 0.47%   |
| Shuttle DH110                  | 1        | 0.47%   |
| ShenZhen MinWin MW-GMLK-2.5G6L | 1        | 0.47%   |
| SeeedStudio ODYSSEY-X86J4105   | 1        | 0.47%   |
| Quanta 120-1135                | 1        | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 36       | 16.9%   |
| 2020    | 23       | 10.8%   |
| 2014    | 23       | 10.8%   |
| 2022    | 19       | 8.92%   |
| 2013    | 17       | 7.98%   |
| 2016    | 16       | 7.51%   |
| 2019    | 15       | 7.04%   |
| 2021    | 11       | 5.16%   |
| 2010    | 10       | 4.69%   |
| 2011    | 9        | 4.23%   |
| 2017    | 8        | 3.76%   |
| 2015    | 7        | 3.29%   |
| 2012    | 7        | 3.29%   |
| 2009    | 6        | 2.82%   |
| 2008    | 3        | 1.41%   |
| 2007    | 1        | 0.47%   |
| 2006    | 1        | 0.47%   |
| Unknown | 1        | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 213      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 206      | 96.71%  |
| Yes  | 7        | 3.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 84       | 38.36%  |
| 16.01-24.0  | 50       | 22.83%  |
| 4.01-8.0    | 36       | 16.44%  |
| 32.01-64.0  | 25       | 11.42%  |
| 64.01-256.0 | 10       | 4.57%   |
| 24.01-32.0  | 5        | 2.28%   |
| 2.01-3.0    | 5        | 2.28%   |
| 1.01-2.0    | 2        | 0.91%   |
| 3.01-4.0    | 1        | 0.46%   |
| 0.51-1.0    | 1        | 0.46%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.01-0.5    | 108      | 49.32%  |
| 0.51-1.0    | 64       | 29.22%  |
| 1.01-2.0    | 31       | 14.16%  |
| 4.01-8.0    | 4        | 1.83%   |
| 3.01-4.0    | 4        | 1.83%   |
| 2.01-3.0    | 4        | 1.83%   |
| 32.01-64.0  | 1        | 0.46%   |
| 64.01-256.0 | 1        | 0.46%   |
| 8.01-16.0   | 1        | 0.46%   |
| 0           | 1        | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 148      | 68.84%  |
| 2      | 32       | 14.88%  |
| 3      | 14       | 6.51%   |
| 0      | 11       | 5.12%   |
| 4      | 6        | 2.79%   |
| 13     | 1        | 0.47%   |
| 10     | 1        | 0.47%   |
| 7      | 1        | 0.47%   |
| 5      | 1        | 0.47%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 169      | 77.88%  |
| Yes       | 48       | 22.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 211      | 99.06%  |
| No        | 2        | 0.94%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 173      | 80.47%  |
| Yes       | 42       | 19.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 185      | 86.85%  |
| Yes       | 28       | 13.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Canada  | 213      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                       | Desktops | Percent |
|----------------------------|----------|---------|
| Toronto                    | 19       | 8.44%   |
| Ottawa                     | 14       | 6.22%   |
| Montreal                   | 14       | 6.22%   |
| Calgary                    | 11       | 4.89%   |
| Edmonton                   | 10       | 4.44%   |
| Victoria                   | 9        | 4%      |
| Winnipeg                   | 8        | 3.56%   |
| Kitchener                  | 7        | 3.11%   |
| Vancouver                  | 5        | 2.22%   |
| Surrey                     | 5        | 2.22%   |
| Brampton                   | 5        | 2.22%   |
| Windsor                    | 3        | 1.33%   |
| St. Albert                 | 3        | 1.33%   |
| Sarnia                     | 3        | 1.33%   |
| Regina                     | 3        | 1.33%   |
| Moncton                    | 3        | 1.33%   |
| London                     | 3        | 1.33%   |
| Laval                      | 3        | 1.33%   |
| Terrebonne                 | 2        | 0.89%   |
| St. Jean Baptiste          | 2        | 0.89%   |
| Saskatoon                  | 2        | 0.89%   |
| Sainte-Julie               | 2        | 0.89%   |
| Saint-Bruno-de-Montarville | 2        | 0.89%   |
| Richmond                   | 2        | 0.89%   |
| Québec                    | 2        | 0.89%   |
| Peterborough               | 2        | 0.89%   |
| Oakville                   | 2        | 0.89%   |
| Nanaimo                    | 2        | 0.89%   |
| Lamont                     | 2        | 0.89%   |
| Kingston                   | 2        | 0.89%   |
| Kanata                     | 2        | 0.89%   |
| Hamilton                   | 2        | 0.89%   |
| Guelph                     | 2        | 0.89%   |
| Greater Sudbury            | 2        | 0.89%   |
| Cambridge                  | 2        | 0.89%   |
| Burnaby                    | 2        | 0.89%   |
| Burlington                 | 2        | 0.89%   |
| Wetaskiwin                 | 1        | 0.44%   |
| West Kelowna               | 1        | 0.44%   |
| Wallaceburg                | 1        | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 39       | 54     | 14.89%  |
| WDC                 | 37       | 79     | 14.12%  |
| Seagate             | 37       | 66     | 14.12%  |
| Kingston            | 32       | 42     | 12.21%  |
| Crucial             | 13       | 17     | 4.96%   |
| Intel               | 10       | 12     | 3.82%   |
| A-DATA Technology   | 10       | 16     | 3.82%   |
| SanDisk             | 8        | 10     | 3.05%   |
| Toshiba             | 7        | 11     | 2.67%   |
| SPCC                | 4        | 4      | 1.53%   |
| OCZ                 | 4        | 5      | 1.53%   |
| Mushkin             | 4        | 4      | 1.53%   |
| Hitachi             | 4        | 4      | 1.53%   |
| Dogfish             | 4        | 7      | 1.53%   |
| BIWIN               | 4        | 5      | 1.53%   |
| PNY                 | 3        | 4      | 1.15%   |
| Micron Technology   | 3        | 6      | 1.15%   |
| Hoodisk             | 3        | 4      | 1.15%   |
| HGST                | 3        | 5      | 1.15%   |
| Hewlett-Packard     | 3        | 3      | 1.15%   |
| VisionTek           | 2        | 6      | 0.76%   |
| Transcend           | 2        | 3      | 0.76%   |
| Timetec             | 2        | 2      | 0.76%   |
| SK hynix            | 2        | 4      | 0.76%   |
| Phison              | 2        | 3      | 0.76%   |
| NVMe                | 2        | 2      | 0.76%   |
| FORESEE             | 2        | 2      | 0.76%   |
| Corsair             | 2        | 4      | 0.76%   |
| China               | 2        | 3      | 0.76%   |
| Team                | 1        | 1      | 0.38%   |
| Silicon Motion      | 1        | 1      | 0.38%   |
| SATADOM             | 1        | 2      | 0.38%   |
| Protectli           | 1        | 2      | 0.38%   |
| Patriot             | 1        | 1      | 0.38%   |
| OPENBSD             | 1        | 1      | 0.38%   |
| Netac               | 1        | 1      | 0.38%   |
| Innodisk            | 1        | 1      | 0.38%   |
| HPE                 | 1        | 4      | 0.38%   |
| Fujitsu             | 1        | 1      | 0.38%   |
| EAGET               | 1        | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Kingston SA400S37240G 240GB     | 11       | 3.93%   |
| Kingston SA400S37120G 120GB     | 7        | 2.5%    |
| Seagate ST1000DM010-2EP102 1TB  | 5        | 1.79%   |
| Samsung SSD 850 EVO 250GB       | 5        | 1.79%   |
| Samsung SSD 860 EVO 500GB       | 4        | 1.43%   |
| BIWIN SSD 128GB                 | 4        | 1.43%   |
| WDC WD20EZRX-00DC0B0 2TB        | 3        | 1.07%   |
| Toshiba DT01ACA100 1TB          | 3        | 1.07%   |
| Seagate ST500DM002-1BD142 500GB | 3        | 1.07%   |
| Seagate ST3500413AS 500GB       | 3        | 1.07%   |
| Seagate ST2000DM008-2FR102 2TB  | 3        | 1.07%   |
| SanDisk SD6SB1M064G1022I 64GB   | 3        | 1.07%   |
| Samsung SSD 840 EVO 120GB       | 3        | 1.07%   |
| Crucial CT240BX500SSD1 240GB    | 3        | 1.07%   |
| WDC WD40EFRX-68WT0N0 4TB        | 2        | 0.71%   |
| WDC WD10EZEX-22MFCA0 1TB        | 2        | 0.71%   |
| WDC WD10EZEX-08WN4A0 1TB        | 2        | 0.71%   |
| WDC PC SN520 NVMe 256GB         | 2        | 0.71%   |
| VisionTek mSATA 120GB           | 2        | 0.71%   |
| Transcend TS256GMSA230S 256GB   | 2        | 0.71%   |
| Toshiba MQ01ABD075 752GB        | 2        | 0.71%   |
| Seagate ST1000DM003-1CH162 1TB  | 2        | 0.71%   |
| Samsung SSD 980 PRO 1TB         | 2        | 0.71%   |
| Samsung SSD 980 1TB             | 2        | 0.71%   |
| Samsung SSD 970 EVO Plus 1TB    | 2        | 0.71%   |
| Samsung SSD 850 EVO mSATA 250GB | 2        | 0.71%   |
| Samsung SSD 840 EVO 250GB       | 2        | 0.71%   |
| PNY CS1311 120GB SSD            | 2        | 0.71%   |
| Mushkin MKNSSDEC60GB 64GB       | 2        | 0.71%   |
| Kingston SUV500MS120G 120GB     | 2        | 0.71%   |
| Intel SSDSC2BB080G4 80GB        | 2        | 0.71%   |
| Crucial CT1000MX500SSD1 1TB     | 2        | 0.71%   |
| A-DATA SU650 120GB              | 2        | 0.71%   |
| A-DATA SU630 240GB              | 2        | 0.71%   |
| WDC WDS500G2B0B-00YS70 500GB    | 1        | 0.36%   |
| WDC WDS500G2B0A-00SM50 500GB    | 1        | 0.36%   |
| WDC WDS250G3X0C-00SJG0 250GB    | 1        | 0.36%   |
| WDC WDS250G2B0B-00YS70 250GB    | 1        | 0.36%   |
| WDC WDS250G2B0A 250GB           | 1        | 0.36%   |
| WDC WDS200T1XHE-00AFY0 2TB      | 1        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 35       | 64     | 44.87%  |
| WDC     | 28       | 65     | 35.9%   |
| Toshiba | 6        | 8      | 7.69%   |
| Hitachi | 4        | 4      | 5.13%   |
| HGST    | 3        | 5      | 3.85%   |
| OPENBSD | 1        | 1      | 1.28%   |
| Fujitsu | 1        | 1      | 1.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 32       | 43     | 20%     |
| Kingston            | 31       | 37     | 19.38%  |
| Crucial             | 12       | 15     | 7.5%    |
| A-DATA Technology   | 10       | 16     | 6.25%   |
| Intel               | 9        | 11     | 5.63%   |
| SanDisk             | 8        | 10     | 5%      |
| WDC                 | 6        | 8      | 3.75%   |
| OCZ                 | 4        | 5      | 2.5%    |
| Mushkin             | 4        | 4      | 2.5%    |
| Dogfish             | 4        | 7      | 2.5%    |
| BIWIN               | 4        | 5      | 2.5%    |
| SPCC                | 3        | 3      | 1.88%   |
| PNY                 | 3        | 4      | 1.88%   |
| Micron Technology   | 3        | 6      | 1.88%   |
| Hoodisk             | 3        | 4      | 1.88%   |
| VisionTek           | 2        | 6      | 1.25%   |
| Transcend           | 2        | 3      | 1.25%   |
| Seagate             | 2        | 2      | 1.25%   |
| FORESEE             | 2        | 2      | 1.25%   |
| Corsair             | 2        | 4      | 1.25%   |
| China               | 2        | 3      | 1.25%   |
| Timetec             | 1        | 1      | 0.63%   |
| SATADOM             | 1        | 2      | 0.63%   |
| Protectli           | 1        | 2      | 0.63%   |
| Phison              | 1        | 1      | 0.63%   |
| Patriot             | 1        | 1      | 0.63%   |
| NVMe                | 1        | 1      | 0.63%   |
| Netac               | 1        | 1      | 0.63%   |
| Innodisk            | 1        | 1      | 0.63%   |
| HPE                 | 1        | 4      | 0.63%   |
| Hewlett-Packard     | 1        | 1      | 0.63%   |
| EAGET               | 1        | 1      | 0.63%   |
| AVEXIR              | 1        | 2      | 0.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 145      | 216    | 61.7%   |
| HDD  | 64       | 148    | 27.23%  |
| NVMe | 26       | 41     | 11.06%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 190      | 364    | 87.96%  |
| NVMe | 26       | 41     | 12.04%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 158      | 231    | 70.85%  |
| 0.51-1.0   | 36       | 60     | 16.14%  |
| 1.01-2.0   | 12       | 21     | 5.38%   |
| 3.01-4.0   | 6        | 17     | 2.69%   |
| 4.01-10.0  | 5        | 23     | 2.24%   |
| 2.01-3.0   | 4        | 9      | 1.79%   |
| 10.01-20.0 | 2        | 3      | 0.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 96       | 43.44%  |
| 251-500        | 37       | 16.74%  |
| 51-100         | 26       | 11.76%  |
| 1-20           | 22       | 9.95%   |
| 21-50          | 18       | 8.14%   |
| 501-1000       | 12       | 5.43%   |
| 1001-2000      | 6        | 2.71%   |
| More than 3000 | 2        | 0.9%    |
| Unknown        | 2        | 0.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 196      | 87.89%  |
| 21-50     | 17       | 7.62%   |
| 51-100    | 4        | 1.79%   |
| 101-250   | 2        | 0.9%    |
| Unknown   | 2        | 0.9%    |
| 1001-2000 | 1        | 0.45%   |
| 501-1000  | 1        | 0.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Desktops | Drives | Percent |
|--------------------------------------------|----------|--------|---------|
| VisionTek mSATA 120GB                      | 2        | 6      | 5.71%   |
| Toshiba MQ01ABD075 752GB                   | 2        | 2      | 5.71%   |
| Seagate ST500DM002-1BD142 500GB            | 2        | 4      | 5.71%   |
| Seagate ST3500413AS 500GB                  | 2        | 4      | 5.71%   |
| WDC WD6400AAKS-22A7B2 640GB                | 1        | 5      | 2.86%   |
| WDC WD50EFRX-68L0BN1 5TB                   | 1        | 1      | 2.86%   |
| WDC WD40EFRX-68WT0N0 4TB                   | 1        | 2      | 2.86%   |
| WDC WD30EZRX-22D8PB0 3TB                   | 1        | 1      | 2.86%   |
| WDC WD2500AAKX-001CA0 250GB                | 1        | 1      | 2.86%   |
| WDC WD1600AAJS-60Z0A0 160GB                | 1        | 1      | 2.86%   |
| Toshiba DT01ACA100 1TB                     | 1        | 3      | 2.86%   |
| Seagate ST500LM021-1KJ152 500GB            | 1        | 1      | 2.86%   |
| Seagate ST3250318AS 250GB                  | 1        | 1      | 2.86%   |
| Seagate ST3200822AS 200GB                  | 1        | 1      | 2.86%   |
| Seagate ST3160815AS 160GB                  | 1        | 1      | 2.86%   |
| Seagate ST31500341AS 1.5TB                 | 1        | 2      | 2.86%   |
| Seagate ST3120026A 120GB                   | 1        | 1      | 2.86%   |
| Seagate ST31000520AS 1TB                   | 1        | 1      | 2.86%   |
| Seagate ST1000DM003-1CH162 1TB             | 1        | 2      | 2.86%   |
| Samsung Electronics SSD 870 EVO 250GB      | 1        | 2      | 2.86%   |
| Mushkin MKNSSDEC512GB                      | 1        | 1      | 2.86%   |
| Micron Technology M500_MTFDDAK960MAV 960GB | 1        | 4      | 2.86%   |
| Kingston SV300S37A120G 120GB               | 1        | 1      | 2.86%   |
| Intel SSDSC2BB480G4 480GB                  | 1        | 1      | 2.86%   |
| Intel SSDSA2M080G2GC 80GB                  | 1        | 1      | 2.86%   |
| Hitachi HTS542520K9A300 200GB              | 1        | 1      | 2.86%   |
| Hitachi HDT721010SLA360 1TB                | 1        | 1      | 2.86%   |
| HGST HTS725050A7E630 500GB                 | 1        | 2      | 2.86%   |
| HGST HTS541010A9E680 1TB                   | 1        | 1      | 2.86%   |
| Crucial CT240M500SSD1 240GB                | 1        | 1      | 2.86%   |
| A-DATA Technology SU800 1TB                | 1        | 1      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 18     | 32.35%  |
| WDC                 | 6        | 11     | 17.65%  |
| Toshiba             | 3        | 5      | 8.82%   |
| VisionTek           | 2        | 6      | 5.88%   |
| Intel               | 2        | 2      | 5.88%   |
| Hitachi             | 2        | 2      | 5.88%   |
| HGST                | 2        | 3      | 5.88%   |
| Samsung Electronics | 1        | 2      | 2.94%   |
| Mushkin             | 1        | 1      | 2.94%   |
| Micron Technology   | 1        | 4      | 2.94%   |
| Kingston            | 1        | 1      | 2.94%   |
| Crucial             | 1        | 1      | 2.94%   |
| A-DATA Technology   | 1        | 1      | 2.94%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 11       | 18     | 45.83%  |
| WDC     | 6        | 11     | 25%     |
| Toshiba | 3        | 5      | 12.5%   |
| Hitachi | 2        | 2      | 8.33%   |
| HGST    | 2        | 3      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 22       | 39     | 68.75%  |
| SSD  | 10       | 18     | 31.25%  |

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
| Works    | 184      | 341    | 82.88%  |
| Malfunc  | 31       | 57     | 13.96%  |
| Detected | 6        | 6      | 2.7%    |
| Failed   | 1        | 1      | 0.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 174      | 66.67%  |
| AMD                         | 37       | 14.18%  |
| Samsung Electronics         | 9        | 3.45%   |
| SanDisk                     | 7        | 2.68%   |
| Silicon Motion              | 5        | 1.92%   |
| Nvidia                      | 5        | 1.92%   |
| ASMedia Technology          | 5        | 1.92%   |
| Broadcom / LSI              | 3        | 1.15%   |
| SK hynix                    | 2        | 0.77%   |
| Silicon Image               | 2        | 0.77%   |
| Micron/Crucial Technology   | 2        | 0.77%   |
| Kingston Technology Company | 2        | 0.77%   |
| JMicron Technology          | 2        | 0.77%   |
| Chelsio Communications      | 2        | 0.77%   |
| Toshiba                     | 1        | 0.38%   |
| Phison Electronics          | 1        | 0.38%   |
| MAXIO Technology (Hangzhou) | 1        | 0.38%   |
| Marvell Technology Group    | 1        | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 27       | 8.91%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 16       | 5.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 14       | 4.62%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 13       | 4.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 12       | 3.96%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 10       | 3.3%    |
| AMD 400 Series Chipset SATA Controller                                           | 10       | 3.3%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 9        | 2.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 8        | 2.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 8        | 2.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8        | 2.64%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7        | 2.31%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 7        | 2.31%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 6        | 1.98%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 4        | 1.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4        | 1.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4        | 1.32%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4        | 1.32%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 4        | 1.32%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4        | 1.32%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4        | 1.32%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 4        | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 4        | 1.32%   |
| AMD FCH SATA Controller [IDE mode]                                               | 4        | 1.32%   |
| SanDisk PC SN520 NVMe SSD                                                        | 3        | 0.99%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3        | 0.99%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3        | 0.99%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 3        | 0.99%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 3        | 0.99%   |
| Unknown                                                                          | 3        | 0.99%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 2        | 0.66%   |
| SanDisk WD Blue SN570 NVMe SSD                                                   | 2        | 0.66%   |
| Samsung NVMe SSD Controller 980                                                  | 2        | 0.66%   |
| Nvidia MCP61 SATA Controller                                                     | 2        | 0.66%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2        | 0.66%   |
| JMicron JMB363 SATA/IDE Controller                                               | 2        | 0.66%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2        | 0.66%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2        | 0.66%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2        | 0.66%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 2        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 189      | 72.14%  |
| IDE  | 30       | 11.45%  |
| NVMe | 29       | 11.07%  |
| RAID | 7        | 2.67%   |
| SAS  | 4        | 1.53%   |
| SCSI | 3        | 1.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 175      | 81.02%  |
| AMD    | 41       | 18.98%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Intel Celeron N5105 @ 2.00GHz       | 8        | 3.67%   |
| Intel Core i5-4570 CPU @ 3.20GHz    | 7        | 3.21%   |
| Intel Core i5-3570 CPU @ 3.40GHz    | 7        | 3.21%   |
| Intel Celeron CPU J3160 @ 1.60GHz   | 7        | 3.21%   |
| Intel Core i5-6500 CPU @ 3.20GHz    | 6        | 2.75%   |
| Intel Celeron J4125 CPU @ 2.00GHz   | 6        | 2.75%   |
| Intel Core i5-4590 CPU @ 3.30GHz    | 5        | 2.29%   |
| Intel Core i5-4570TE CPU @ 2.70GHz  | 4        | 1.83%   |
| AMD GX-412TC SOC                    | 4        | 1.83%   |
| Intel Xeon                          | 3        | 1.38%   |
| Intel Pentium CPU G4560 @ 3.50GHz   | 3        | 1.38%   |
| Intel Core i7-9700K CPU @ 3.60GHz   | 3        | 1.38%   |
| Intel Core i7-3770 CPU @ 3.40GHz    | 3        | 1.38%   |
| Intel Core i5-7200U CPU @ 2.50GHz   | 3        | 1.38%   |
| AMD Ryzen 5 2600 Six-Core Processor | 3        | 1.38%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz | 2        | 0.92%   |
| Intel Core i7-8550U CPU @ 1.80GHz   | 2        | 0.92%   |
| Intel Core i7-7700 CPU @ 3.60GHz    | 2        | 0.92%   |
| Intel Core i7-4790K CPU @ 4.00GHz   | 2        | 0.92%   |
| Intel Core i5-8400 CPU @ 2.80GHz    | 2        | 0.92%   |
| Intel Core i5-4670 CPU @ 3.40GHz    | 2        | 0.92%   |
| Intel Core i5-4460 CPU @ 3.20GHz    | 2        | 0.92%   |
| Intel Core i5-3470T CPU @ 2.90GHz   | 2        | 0.92%   |
| Intel Core i5-3470 CPU @ 3.20GHz    | 2        | 0.92%   |
| Intel Core i5-2500 CPU @ 3.30GHz    | 2        | 0.92%   |
| Intel Core i3-6100T CPU @ 3.20GHz   | 2        | 0.92%   |
| Intel Core i3-4030U CPU @ 1.90GHz   | 2        | 0.92%   |
| Intel Celeron J4105 CPU @ 1.50GHz   | 2        | 0.92%   |
| Intel Celeron CPU J3455 @ 1.50GHz   | 2        | 0.92%   |
| Intel Celeron CPU J1900 @ 1.99GHz   | 2        | 0.92%   |
| AMD FX-8350 Eight-Core Processor    | 2        | 0.92%   |
| AMD FX-8320E Eight-Core Processor   | 2        | 0.92%   |
| AMD FX-4350 Quad-Core Processor     | 2        | 0.92%   |
| Intel Xeon D-2146NT CPU @ 2.30GHz   | 1        | 0.46%   |
| Intel Xeon CPU X5660 @ 2.80GHz      | 1        | 0.46%   |
| Intel Xeon CPU W3530 @ 2.80GHz      | 1        | 0.46%   |
| Intel Xeon CPU L5640 @ 2.27GHz      | 1        | 0.46%   |
| Intel Xeon CPU E5645 @ 2.40GHz      | 1        | 0.46%   |
| Intel Xeon CPU E5506 @ 2.13GHz      | 1        | 0.46%   |
| Intel Xeon CPU E5-2697 v2 @ 2.70GHz | 1        | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 62       | 28.57%  |
| Intel Celeron           | 33       | 15.21%  |
| Intel Xeon              | 20       | 9.22%   |
| Intel Core i7           | 19       | 8.76%   |
| Intel Core i3           | 17       | 7.83%   |
| Intel Atom              | 7        | 3.23%   |
| Intel Pentium           | 6        | 2.76%   |
| AMD FX                  | 6        | 2.76%   |
| Other                   | 5        | 2.3%    |
| AMD Ryzen 5             | 5        | 2.3%    |
| AMD GX                  | 5        | 2.3%    |
| AMD Ryzen 9             | 4        | 1.84%   |
| AMD Ryzen 7             | 3        | 1.38%   |
| AMD Athlon 64 X2        | 3        | 1.38%   |
| Intel Pentium Dual-Core | 2        | 0.92%   |
| Intel Core 2 Quad       | 2        | 0.92%   |
| Intel Core 2 Duo        | 2        | 0.92%   |
| AMD Ryzen 3             | 2        | 0.92%   |
| Intel Pentium Silver    | 1        | 0.46%   |
| Intel Pentium 4         | 1        | 0.46%   |
| AMD Ryzen Embedded      | 1        | 0.46%   |
| AMD Ryzen 5 PRO         | 1        | 0.46%   |
| AMD Phenom II X6        | 1        | 0.46%   |
| AMD Phenom              | 1        | 0.46%   |
| AMD G                   | 1        | 0.46%   |
| AMD EPYC                | 1        | 0.46%   |
| AMD E                   | 1        | 0.46%   |
| AMD Athlon Dual Core    | 1        | 0.46%   |
| AMD Athlon              | 1        | 0.46%   |
| AMD A6                  | 1        | 0.46%   |
| AMD A4                  | 1        | 0.46%   |
| AMD A10                 | 1        | 0.46%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 117      | 54.17%  |
| 2       | 47       | 21.76%  |
| 6       | 15       | 6.94%   |
| 8       | 14       | 6.48%   |
| 12      | 7        | 3.24%   |
| 16      | 4        | 1.85%   |
| 32      | 3        | 1.39%   |
| 10      | 3        | 1.39%   |
| 24      | 2        | 0.93%   |
| Unknown | 2        | 0.93%   |
| 11      | 1        | 0.46%   |
| 3       | 1        | 0.46%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 210      | 98.59%  |
| 2       | 2        | 0.94%   |
| Unknown | 1        | 0.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 140      | 65.42%  |
| 2       | 72       | 33.64%  |
| Unknown | 2        | 0.93%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 39       | 17.89%  |
| KabyLake      | 23       | 10.55%  |
| IvyBridge     | 20       | 9.17%   |
| Unknown       | 15       | 6.88%   |
| Skylake       | 14       | 6.42%   |
| Silvermont    | 12       | 5.5%    |
| SandyBridge   | 10       | 4.59%   |
| Goldmont plus | 9        | 4.13%   |
| Piledriver    | 8        | 3.67%   |
| Zen+          | 7        | 3.21%   |
| Westmere      | 6        | 2.75%   |
| Penryn        | 6        | 2.75%   |
| Goldmont      | 6        | 2.75%   |
| Broadwell     | 5        | 2.29%   |
| Zen           | 4        | 1.83%   |
| Puma          | 4        | 1.83%   |
| K8 Hammer     | 4        | 1.83%   |
| CometLake     | 4        | 1.83%   |
| Zen 3         | 3        | 1.38%   |
| Nehalem       | 3        | 1.38%   |
| K10           | 3        | 1.38%   |
| Jaguar        | 3        | 1.38%   |
| Bonnell       | 3        | 1.38%   |
| Zen 2         | 2        | 0.92%   |
| Bobcat        | 2        | 0.92%   |
| TigerLake     | 1        | 0.46%   |
| NetBurst      | 1        | 0.46%   |
| Core          | 1        | 0.46%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 134      | 63.81%  |
| Nvidia                     | 36       | 17.14%  |
| AMD                        | 28       | 13.33%  |
| ASPEED Technology          | 7        | 3.33%   |
| Matrox Electronics Systems | 5        | 2.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 27       | 12.74%  |
| Intel HD Graphics 530                                                                    | 11       | 5.19%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 10       | 4.72%   |
| Intel JasperLake [UHD Graphics]                                                          | 10       | 4.72%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9        | 4.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9        | 4.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7        | 3.3%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 7        | 3.3%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 5        | 2.36%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 1.89%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 4        | 1.89%   |
| Intel HD Graphics 630                                                                    | 4        | 1.89%   |
| Intel HD Graphics 610                                                                    | 4        | 1.89%   |
| Intel HD Graphics 500                                                                    | 4        | 1.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4        | 1.89%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4        | 1.89%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4        | 1.89%   |
| Intel UHD Graphics 620                                                                   | 3        | 1.42%   |
| Intel HD Graphics 620                                                                    | 3        | 1.42%   |
| Intel HD Graphics 5500                                                                   | 3        | 1.42%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 2        | 0.94%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 0.94%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 0.94%   |
| Nvidia GM107GL [Quadro K620]                                                             | 2        | 0.94%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 2        | 0.94%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 2        | 0.94%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 0.94%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 0.94%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 0.94%   |
| AMD RS780L [Radeon 3000]                                                                 | 2        | 0.94%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 0.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2        | 0.94%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 2        | 0.94%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2        | 0.94%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1        | 0.47%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1        | 0.47%   |
| Nvidia GT218 [GeForce 310]                                                               | 1        | 0.47%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 0.47%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 129      | 59.72%  |
| 1 x Nvidia     | 34       | 15.74%  |
| 1 x AMD        | 27       | 12.5%   |
| Other          | 9        | 4.17%   |
| 1 x ASPEED     | 7        | 3.24%   |
| 1 x Matrox     | 5        | 2.31%   |
| 2 x Intel      | 2        | 0.93%   |
| Intel + Nvidia | 2        | 0.93%   |
| 2 x AMD        | 1        | 0.46%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 184      | 85.58%  |
| Proprietary | 21       | 9.77%   |
| Unknown     | 10       | 4.65%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 184      | 85.98%  |
| 0.51-1.0   | 8        | 3.74%   |
| 1.01-2.0   | 7        | 3.27%   |
| 7.01-8.0   | 4        | 1.87%   |
| 3.01-4.0   | 4        | 1.87%   |
| 5.01-6.0   | 3        | 1.4%    |
| 8.01-16.0  | 2        | 0.93%   |
| 2.01-3.0   | 1        | 0.47%   |
| 0.01-0.5   | 1        | 0.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 9        | 18.75%  |
| Dell                 | 6        | 12.5%   |
| BenQ                 | 6        | 12.5%   |
| Sony                 | 3        | 6.25%   |
| Samsung Electronics  | 3        | 6.25%   |
| Lenovo               | 3        | 6.25%   |
| ASUSTek Computer     | 3        | 6.25%   |
| Acer                 | 3        | 6.25%   |
| LG Electronics       | 2        | 4.17%   |
| Hewlett-Packard      | 2        | 4.17%   |
| AOC                  | 2        | 4.17%   |
| ViewSonic            | 1        | 2.08%   |
| Videoseven           | 1        | 2.08%   |
| Toshiba              | 1        | 2.08%   |
| LTV                  | 1        | 2.08%   |
| Insignia             | 1        | 2.08%   |
| Ancor Communications | 1        | 2.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Sony LCD Monitor TV XV 1920x1080                                       | 2        | 3.85%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 2        | 3.85%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch               | 2        | 3.85%   |
| ViewSonic LCD Monitor VSCFA2B 1920x1080 510x290mm 23.1-inch            | 1        | 1.92%   |
| Videoseven WL19A IGM1908 1280x1024 380x300mm 19.1-inch                 | 1        | 1.92%   |
| Toshiba TV TSB0200 1920x1080 530x300mm 24.0-inch                       | 1        | 1.92%   |
| Sony TV  *30 SNY05D1 3840x2160 1660x930mm 74.9-inch                    | 1        | 1.92%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1210x680mm 54.6-inch | 1        | 1.92%   |
| LTV LTV1280M1A LTV0A3C 1024x768 800x450mm 36.1-inch                    | 1        | 1.92%   |
| LG Electronics LCD Monitor LG ULTRAGEAR 2560x1440                      | 1        | 1.92%   |
| LG Electronics LCD Monitor LG Ultra HD 7680x2160                       | 1        | 1.92%   |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1        | 1.92%   |
| Lenovo LEN-M93z-B  LEN0093 1920x1080 510x290mm 23.1-inch               | 1        | 1.92%   |
| Insignia LCD Monitor BBY0050 1920x1080 700x400mm 31.7-inch             | 1        | 1.92%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch       | 1        | 1.92%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch             | 1        | 1.92%   |
| Goldstar W2442 GSM56D9 1920x1080 530x300mm 24.0-inch                   | 1        | 1.92%   |
| Goldstar W2052 GSM4E88 1680x1050 470x300mm 22.0-inch                   | 1        | 1.92%   |
| Goldstar MP59G GSM5B35 1920x1080 600x340mm 27.2-inch                   | 1        | 1.92%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                   | 1        | 1.92%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch            | 1        | 1.92%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch            | 1        | 1.92%   |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch               | 1        | 1.92%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 1        | 1.92%   |
| Goldstar LG FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch              | 1        | 1.92%   |
| Goldstar LCD Monitor GSM76F5 1920x1080 700x390mm 31.5-inch             | 1        | 1.92%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 600x340mm 27.2-inch                 | 1        | 1.92%   |
| Dell SE2722H DELD116 1920x1080 600x340mm 27.2-inch                     | 1        | 1.92%   |
| Dell P3222QE DEL4246 3840x2160 700x390mm 31.5-inch                     | 1        | 1.92%   |
| Dell P2311H DEL4067 1920x1080 510x290mm 23.1-inch                      | 1        | 1.92%   |
| Dell P2219H DELA114 1920x1080 480x270mm 21.7-inch                      | 1        | 1.92%   |
| Dell LCD Monitor DELF003 1440x900 410x260mm 19.1-inch                  | 1        | 1.92%   |
| Dell 2001FP DELA008 1600x1200 410x310mm 20.2-inch                      | 1        | 1.92%   |
| BenQ XL2430T BNQ7F3D 1920x1080 530x300mm 24.0-inch                     | 1        | 1.92%   |
| BenQ LCD Monitor PD3200Q                                               | 1        | 1.92%   |
| BenQ LCD Monitor GW2765                                                | 1        | 1.92%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                      | 1        | 1.92%   |
| BenQ GL2460 BNQ78CE 1920x1080 530x300mm 24.0-inch                      | 1        | 1.92%   |
| BenQ G900HD BNQ7816 1366x768 410x230mm 18.5-inch                       | 1        | 1.92%   |
| BenQ BL2780 BNQ802B 1920x1080 600x340mm 27.2-inch                      | 1        | 1.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 25       | 53.19%  |
| 3840x2160 (4K)     | 6        | 12.77%  |
| 2560x1440 (QHD)    | 2        | 4.26%   |
| 1680x1050 (WSXGA+) | 2        | 4.26%   |
| 1440x900 (WXGA+)   | 2        | 4.26%   |
| Unknown            | 2        | 4.26%   |
| 7680x2160          | 1        | 2.13%   |
| 3440x1440          | 1        | 2.13%   |
| 2560x1080          | 1        | 2.13%   |
| 1600x900 (HD+)     | 1        | 2.13%   |
| 1600x1200          | 1        | 2.13%   |
| 1366x768 (WXGA)    | 1        | 2.13%   |
| 1280x1024 (SXGA)   | 1        | 2.13%   |
| 1024x768 (XGA)     | 1        | 2.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 12       | 24.49%  |
| 27      | 6        | 12.24%  |
| 21      | 6        | 12.24%  |
| Unknown | 5        | 10.2%   |
| 19      | 4        | 8.16%   |
| 54      | 3        | 6.12%   |
| 23      | 3        | 6.12%   |
| 34      | 2        | 4.08%   |
| 31      | 2        | 4.08%   |
| 22      | 2        | 4.08%   |
| 74      | 1        | 2.04%   |
| 36      | 1        | 2.04%   |
| 20      | 1        | 2.04%   |
| 18      | 1        | 2.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 20       | 41.67%  |
| 401-500     | 13       | 27.08%  |
| Unknown     | 5        | 10.42%  |
| 701-800     | 3        | 6.25%   |
| 1001-1500   | 3        | 6.25%   |
| 601-700     | 2        | 4.17%   |
| 351-400     | 1        | 2.08%   |
| 1501-2000   | 1        | 2.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 33       | 71.74%  |
| Unknown | 5        | 10.87%  |
| 16/10   | 4        | 8.7%    |
| 21/9    | 2        | 4.35%   |
| 5/4     | 1        | 2.17%   |
| 4/3     | 1        | 2.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 20       | 41.67%  |
| 301-350        | 6        | 12.5%   |
| 151-200        | 5        | 10.42%  |
| Unknown        | 5        | 10.42%  |
| More than 1000 | 4        | 8.33%   |
| 351-500        | 4        | 8.33%   |
| 251-300        | 2        | 4.17%   |
| 141-150        | 1        | 2.08%   |
| 501-1000       | 1        | 2.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 33       | 67.35%  |
| 101-120 | 8        | 16.33%  |
| Unknown | 5        | 10.2%   |
| 1-50    | 1        | 2.04%   |
| 161-240 | 1        | 2.04%   |
| 121-160 | 1        | 2.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 165      | 76.74%  |
| 1     | 42       | 19.53%  |
| 2     | 8        | 3.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 166      | 56.85%  |
| Realtek Semiconductor           | 84       | 28.77%  |
| Broadcom                        | 13       | 4.45%   |
| Qualcomm Atheros                | 8        | 2.74%   |
| Solarflare Communications       | 3        | 1.03%   |
| Ralink                          | 2        | 0.68%   |
| Mellanox Technologies           | 2        | 0.68%   |
| MediaTek                        | 2        | 0.68%   |
| Marvell Technology Group        | 2        | 0.68%   |
| Chelsio Communications          | 2        | 0.68%   |
| 3Com                            | 2        | 0.68%   |
| Qualcomm Atheros Communications | 1        | 0.34%   |
| NetGear                         | 1        | 0.34%   |
| IMC Networks                    | 1        | 0.34%   |
| Google                          | 1        | 0.34%   |
| D-Link System                   | 1        | 0.34%   |
| Aquantia                        | 1        | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 72       | 19.83%  |
| Intel I211 Gigabit Network Connection                                         | 27       | 7.44%   |
| Intel 82574L Gigabit Network Connection                                       | 22       | 6.06%   |
| Intel Ethernet Connection I217-LM                                             | 21       | 5.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 17       | 4.68%   |
| Intel I350 Gigabit Network Connection                                         | 12       | 3.31%   |
| Intel Ethernet Controller I225-V                                              | 10       | 2.75%   |
| Intel 82583V Gigabit Network Connection                                       | 9        | 2.48%   |
| Realtek RTL8125 2.5GbE Controller                                             | 8        | 2.2%    |
| Intel 82580 Gigabit Network Connection                                        | 8        | 2.2%    |
| Intel Wi-Fi 6 AX200                                                           | 7        | 1.93%   |
| Intel I210 Gigabit Network Connection                                         | 7        | 1.93%   |
| Intel 82576 Gigabit Network Connection                                        | 7        | 1.93%   |
| Intel Ethernet Controller I226-V                                              | 6        | 1.65%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6        | 1.65%   |
| Intel Ethernet Connection (2) I219-LM                                         | 5        | 1.38%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 5        | 1.38%   |
| Intel Ethernet Connection (2) I219-V                                          | 4        | 1.1%    |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 4        | 1.1%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3        | 0.83%   |
| Intel Wireless 7260                                                           | 3        | 0.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3        | 0.83%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 3        | 0.83%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3        | 0.83%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 3        | 0.83%   |
| Solarflare SFC9020 10G Ethernet Controller                                    | 2        | 0.55%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 2        | 0.55%   |
| Intel Wireless 3165                                                           | 2        | 0.55%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 2        | 0.55%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2        | 0.55%   |
| Intel Ethernet Connection I217-V                                              | 2        | 0.55%   |
| Intel Ethernet Connection (5) I219-LM                                         | 2        | 0.55%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 0.55%   |
| Intel Ethernet Connection (2) I218-LM                                         | 2        | 0.55%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 0.55%   |
| Intel 82599 10 Gigabit Network Connection                                     | 2        | 0.55%   |
| Intel 82575GB Gigabit Network Connection                                      | 2        | 0.55%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 2        | 0.55%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                                 | 2        | 0.55%   |
| Solarflare SFC9120 10G Ethernet Controller                                    | 1        | 0.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 23       | 53.49%  |
| Qualcomm Atheros                | 6        | 13.95%  |
| Realtek Semiconductor           | 5        | 11.63%  |
| Ralink                          | 2        | 4.65%   |
| MediaTek                        | 2        | 4.65%   |
| Broadcom                        | 2        | 4.65%   |
| Qualcomm Atheros Communications | 1        | 2.33%   |
| NetGear                         | 1        | 2.33%   |
| IMC Networks                    | 1        | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 7        | 15.91%  |
| Intel Wireless 7260                                                     | 3        | 6.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3        | 6.82%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 3        | 6.82%   |
| Intel Wireless 3165                                                     | 2        | 4.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1        | 2.27%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1        | 2.27%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 2.27%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1        | 2.27%   |
| Realtek Realtek Bluetooth Adapter                                       | 1        | 2.27%   |
| Ralink RT5592 PCIe Wireless Network Adapter                             | 1        | 2.27%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                    | 1        | 2.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1        | 2.27%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 2.27%   |
| Qualcomm Atheros AR958x 802.11abgn Wireless Network Adapter             | 1        | 2.27%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1        | 2.27%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1        | 2.27%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1        | 2.27%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 2.27%   |
| NetGear A6200 802.11a/b/g/n/ac Wireless Adapter [Broadcom BCM43526]     | 1        | 2.27%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1        | 2.27%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1        | 2.27%   |
| Intel Wireless 8260                                                     | 1        | 2.27%   |
| Intel Wireless 7265                                                     | 1        | 2.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1        | 2.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1        | 2.27%   |
| Intel Centrino Wireless-N 105                                           | 1        | 2.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1        | 2.27%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 1        | 2.27%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1        | 2.27%   |
| Broadcom BCM4321 802.11b/g/n                                            | 1        | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 156      | 59.09%  |
| Realtek Semiconductor     | 83       | 31.44%  |
| Broadcom                  | 11       | 4.17%   |
| Solarflare Communications | 3        | 1.14%   |
| Qualcomm Atheros          | 2        | 0.76%   |
| Marvell Technology Group  | 2        | 0.76%   |
| Chelsio Communications    | 2        | 0.76%   |
| 3Com                      | 2        | 0.76%   |
| Google                    | 1        | 0.38%   |
| D-Link System             | 1        | 0.38%   |
| Aquantia                  | 1        | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 72       | 22.78%  |
| Intel I211 Gigabit Network Connection                                         | 27       | 8.54%   |
| Intel 82574L Gigabit Network Connection                                       | 22       | 6.96%   |
| Intel Ethernet Connection I217-LM                                             | 21       | 6.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 17       | 5.38%   |
| Intel I350 Gigabit Network Connection                                         | 12       | 3.8%    |
| Intel Ethernet Controller I225-V                                              | 10       | 3.16%   |
| Intel 82583V Gigabit Network Connection                                       | 9        | 2.85%   |
| Realtek RTL8125 2.5GbE Controller                                             | 8        | 2.53%   |
| Intel 82580 Gigabit Network Connection                                        | 8        | 2.53%   |
| Intel I210 Gigabit Network Connection                                         | 7        | 2.22%   |
| Intel 82576 Gigabit Network Connection                                        | 7        | 2.22%   |
| Intel Ethernet Controller I226-V                                              | 6        | 1.9%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6        | 1.9%    |
| Intel Ethernet Connection (2) I219-LM                                         | 5        | 1.58%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 5        | 1.58%   |
| Intel Ethernet Connection (2) I219-V                                          | 4        | 1.27%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 4        | 1.27%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3        | 0.95%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3        | 0.95%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 3        | 0.95%   |
| Solarflare SFC9020 10G Ethernet Controller                                    | 2        | 0.63%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 2        | 0.63%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2        | 0.63%   |
| Intel Ethernet Connection I217-V                                              | 2        | 0.63%   |
| Intel Ethernet Connection (5) I219-LM                                         | 2        | 0.63%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 0.63%   |
| Intel Ethernet Connection (2) I218-LM                                         | 2        | 0.63%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 0.63%   |
| Intel 82599 10 Gigabit Network Connection                                     | 2        | 0.63%   |
| Intel 82575GB Gigabit Network Connection                                      | 2        | 0.63%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 2        | 0.63%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                                 | 2        | 0.63%   |
| Solarflare SFC9120 10G Ethernet Controller                                    | 1        | 0.32%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.32%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1        | 0.32%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.32%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.32%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                       | 1        | 0.32%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 211      | 82.42%  |
| WiFi     | 42       | 16.41%  |
| Unknown  | 3        | 1.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 207      | 95.83%  |
| WiFi     | 9        | 4.17%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 51       | 23.5%   |
| 4     | 41       | 18.89%  |
| 3     | 39       | 17.97%  |
| 1     | 39       | 17.97%  |
| 5     | 21       | 9.68%   |
| 6     | 16       | 7.37%   |
| 7     | 4        | 1.84%   |
| 8     | 2        | 0.92%   |
| 0     | 2        | 0.92%   |
| 10    | 1        | 0.46%   |
| 9     | 1        | 0.46%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 188      | 86.24%  |
| Yes  | 30       | 13.76%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 18       | 62.07%  |
| Cambridge Silicon Radio         | 5        | 17.24%  |
| Realtek Semiconductor           | 1        | 3.45%   |
| Qualcomm Atheros Communications | 1        | 3.45%   |
| MediaTek                        | 1        | 3.45%   |
| IMC Networks                    | 1        | 3.45%   |
| Foxconn / Hon Hai               | 1        | 3.45%   |
| Apple                           | 1        | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                | 6        | 20.69%  |
| Intel Bluetooth wireless interface                   | 5        | 17.24%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 5        | 17.24%  |
| Intel Wireless-AC 3168 Bluetooth                     | 3        | 10.34%  |
| Intel AX201 Bluetooth                                | 2        | 6.9%    |
| Realtek  Bluetooth 4.2 Adapter                       | 1        | 3.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                | 1        | 3.45%   |
| MediaTek Wireless_Device                             | 1        | 3.45%   |
| Intel Intel Wireless Bluetooth                       | 1        | 3.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 1        | 3.45%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip | 1        | 3.45%   |
| Foxconn / Hon Hai Bluetooth USB Module               | 1        | 3.45%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                 | 1        | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 130      | 60.75%  |
| AMD                      | 37       | 17.29%  |
| Nvidia                   | 34       | 15.89%  |
| Logitech                 | 3        | 1.4%    |
| C-Media Electronics      | 2        | 0.93%   |
| Yamaha                   | 1        | 0.47%   |
| Texas Instruments        | 1        | 0.47%   |
| SteelSeries ApS          | 1        | 0.47%   |
| Micro Star International | 1        | 0.47%   |
| KTMicro                  | 1        | 0.47%   |
| Elgato Systems           | 1        | 0.47%   |
| Creative Labs            | 1        | 0.47%   |
| ASUSTek Computer         | 1        | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 25       | 9.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 25       | 9.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11       | 4.25%   |
| Intel Jasper Lake HD Audio                                                                        | 10       | 3.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9        | 3.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9        | 3.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8        | 3.09%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8        | 3.09%   |
| Intel 200 Series PCH HD Audio                                                                     | 7        | 2.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6        | 2.32%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6        | 2.32%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 6        | 2.32%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5        | 1.93%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5        | 1.93%   |
| AMD FCH Azalia Controller                                                                         | 5        | 1.93%   |
| Nvidia High Definition Audio Controller                                                           | 4        | 1.54%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4        | 1.54%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 4        | 1.54%   |
| Intel Broadwell-U Audio Controller                                                                | 4        | 1.54%   |
| Intel 8 Series HD Audio Controller                                                                | 4        | 1.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4        | 1.54%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3        | 1.16%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3        | 1.16%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3        | 1.16%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3        | 1.16%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 3        | 1.16%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3        | 1.16%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3        | 1.16%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3        | 1.16%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3        | 1.16%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2        | 0.77%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2        | 0.77%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2        | 0.77%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2        | 0.77%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2        | 0.77%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2        | 0.77%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2        | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2        | 0.77%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 2        | 0.77%   |
| AMD Navi 10 HDMI Audio                                                                            | 2        | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 38       | 15.7%   |
| Kingston            | 38       | 15.7%   |
| SK hynix            | 35       | 14.46%  |
| Unknown             | 22       | 9.09%   |
| Corsair             | 21       | 8.68%   |
| Crucial             | 20       | 8.26%   |
| G.Skill             | 16       | 6.61%   |
| Micron Technology   | 10       | 4.13%   |
| Apacer              | 5        | 2.07%   |
| Unknown             | 5        | 2.07%   |
| Team                | 4        | 1.65%   |
| Ramaxel Technology  | 4        | 1.65%   |
| Unknown (0x0C26)    | 3        | 1.24%   |
| Patriot             | 3        | 1.24%   |
| Nanya Technology    | 3        | 1.24%   |
| A-DATA Technology   | 3        | 1.24%   |
| Timetec             | 2        | 0.83%   |
| OCZ                 | 2        | 0.83%   |
| V-Color             | 1        | 0.41%   |
| Unknown (ABCD)      | 1        | 0.41%   |
| Unknown (0x0DD5)    | 1        | 0.41%   |
| Transcend           | 1        | 0.41%   |
| Toshiba             | 1        | 0.41%   |
| PNY                 | 1        | 0.41%   |
| Cors                | 1        | 0.41%   |
| Avant               | 1        | 0.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s      | 5        | 1.92%   |
| Unknown                                                  | 5        | 1.92%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 4        | 1.53%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 1600MT/s      | 4        | 1.53%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s  | 4        | 1.53%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s     | 3        | 1.15%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s     | 3        | 1.15%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s      | 3        | 1.15%   |
| Kingston RAM KHX1600C10D3/8G 4GB DIMM DDR3 1600MT/s      | 3        | 1.15%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s              | 2        | 0.77%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 2        | 0.77%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 2        | 0.77%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 2        | 0.77%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s       | 2        | 0.77%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s     | 2        | 0.77%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s     | 2        | 0.77%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB RIMM DDR4 2133MT/s     | 2        | 0.77%   |
| SK hynix RAM HMA451R7AFR8N-TF 4GB RIMM DDR4 2133MT/s     | 2        | 0.77%   |
| Samsung RAM M471B5173DB0-YK0 4GB DIMM DDR3 1600MT/s      | 2        | 0.77%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s | 2        | 0.77%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s      | 2        | 0.77%   |
| Micron RAM 9ASF51272PZ-2G1A2 4GB RIMM DDR4 2133MT/s      | 2        | 0.77%   |
| G.Skill RAM F4-2666C19-8GNT 8GB DIMM DDR4 2666MT/s       | 2        | 0.77%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM 1600MT/s           | 2        | 0.77%   |
| Corsair RAM CMV8GX3M1A1333C9 8GB DIMM DDR3 1333MT/s      | 2        | 0.77%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1333MT/s      | 2        | 0.77%   |
| Corsair RAM CML16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s    | 2        | 0.77%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s   | 2        | 0.77%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3000MT/s   | 2        | 0.77%   |
| V-Color RAM VCOLOR-TD2G16C9-H8 2GB DIMM 1333MT/s         | 1        | 0.38%   |
| Unknown RAM Module 8GB DIMM DDR4 2666MT/s                | 1        | 0.38%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s                | 1        | 0.38%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 0.38%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                     | 1        | 0.38%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                   | 1        | 0.38%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                | 1        | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s               | 1        | 0.38%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 1        | 0.38%   |
| Unknown RAM Module 2GB DIMM DDR 1066MT/s                 | 1        | 0.38%   |
| Unknown RAM Module 2GB DIMM 400MT/s                      | 1        | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 99       | 48.06%  |
| DDR4    | 82       | 39.81%  |
| Unknown | 9        | 4.37%   |
| DDR2    | 7        | 3.4%    |
| SDRAM   | 4        | 1.94%   |
| DDR5    | 2        | 0.97%   |
| DDR     | 2        | 0.97%   |
| LPDDR4  | 1        | 0.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 143      | 71.14%  |
| SODIMM | 55       | 27.36%  |
| RIMM   | 3        | 1.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 81       | 36%     |
| 8192  | 76       | 33.78%  |
| 16384 | 30       | 13.33%  |
| 2048  | 27       | 12%     |
| 1024  | 7        | 3.11%   |
| 32768 | 3        | 1.33%   |
| 512   | 1        | 0.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 74       | 33.04%  |
| 1333    | 31       | 13.84%  |
| 2400    | 23       | 10.27%  |
| 2133    | 19       | 8.48%   |
| 3200    | 18       | 8.04%   |
| 2667    | 17       | 7.59%   |
| 800     | 7        | 3.13%   |
| 2666    | 6        | 2.68%   |
| 667     | 4        | 1.79%   |
| Unknown | 4        | 1.79%   |
| 3600    | 3        | 1.34%   |
| 3000    | 3        | 1.34%   |
| 1066    | 3        | 1.34%   |
| 1866    | 2        | 0.89%   |
| 1067    | 2        | 0.89%   |
| 400     | 2        | 0.89%   |
| 6400    | 1        | 0.45%   |
| 5200    | 1        | 0.45%   |
| 4800    | 1        | 0.45%   |
| 3400    | 1        | 0.45%   |
| 1334    | 1        | 0.45%   |
| 333     | 1        | 0.45%   |

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
| Canon CanoScan LiDE 220 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 3        | 60%     |
| Microdia            | 1        | 20%     |
| Chicony Electronics | 1        | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Microdia JOYACCESS JA-Webcam  | 1        | 20%     |
| Logitech Webcam C310          | 1        | 20%     |
| Logitech HD Pro Webcam C920   | 1        | 20%     |
| Logitech BRIO Ultra HD Webcam | 1        | 20%     |
| Chicony HP 0.3MP Webcam       | 1        | 20%     |

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
| 1     | 126      | 57.53%  |
| 0     | 63       | 28.77%  |
| 2     | 23       | 10.5%   |
| 3     | 4        | 1.83%   |
| 4     | 3        | 1.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 139      | 76.37%  |
| Net/wireless             | 14       | 7.69%   |
| Bluetooth                | 9        | 4.95%   |
| Sound                    | 5        | 2.75%   |
| Net/ethernet             | 4        | 2.2%    |
| Firewire controller      | 4        | 2.2%    |
| Card reader              | 3        | 1.65%   |
| Network                  | 2        | 1.1%    |
| Storage/raid             | 1        | 0.55%   |
| Graphics card            | 1        | 0.55%   |

