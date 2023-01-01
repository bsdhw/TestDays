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

Total: 308

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| helloSystem 0.7.0 | 9        | 3.5%    |
| OPNsense 22.7.8   | 8        | 3.11%   |
| OPNsense 22.1.8   | 8        | 3.11%   |
| OPNsense 22.1.10  | 8        | 3.11%   |
| OPNsense 21.1.4   | 8        | 3.11%   |
| helloSystem 0.5.0 | 8        | 3.11%   |
| OPNsense 22.1.7   | 7        | 2.72%   |
| OPNsense 22.1     | 7        | 2.72%   |
| OPNsense 21.7     | 7        | 2.72%   |
| OPNsense 21.1.3   | 7        | 2.72%   |
| OPNsense 21.1     | 7        | 2.72%   |
| OPNsense 22.7.4   | 6        | 2.33%   |
| OPNsense 22.1.6   | 6        | 2.33%   |
| OPNsense 21.1.5   | 6        | 2.33%   |
| OPNsense 20.7.8   | 6        | 2.33%   |
| OPNsense 22.7.10  | 5        | 1.95%   |
| OPNsense 22.7     | 5        | 1.95%   |
| OPNsense 21.7.7   | 5        | 1.95%   |
| OPNsense 21.7.3   | 5        | 1.95%   |
| OPNsense 21.7.1   | 5        | 1.95%   |
| OPNsense 21.1.6   | 5        | 1.95%   |
| OPNsense 21.1.1   | 5        | 1.95%   |
| FreeBSD 13.1      | 5        | 1.95%   |
| FreeBSD 12.2      | 5        | 1.95%   |
| OPNsense 22.7.9   | 4        | 1.56%   |
| OPNsense 22.7.7   | 4        | 1.56%   |
| OPNsense 22.1.3   | 4        | 1.56%   |
| OPNsense 21.7.8   | 4        | 1.56%   |
| OPNsense 21.7.4   | 4        | 1.56%   |
| OPNsense 22.7.6   | 3        | 1.17%   |
| OPNsense 22.7.3   | 3        | 1.17%   |
| OPNsense 22.7.2   | 3        | 1.17%   |
| OPNsense 22.1.9   | 3        | 1.17%   |
| OPNsense 21.1.8   | 3        | 1.17%   |
| OPNsense 21.1.7   | 3        | 1.17%   |
| OPNsense 21.1.2   | 3        | 1.17%   |
| OpenBSD 7.1       | 3        | 1.17%   |
| FreeBSD 13.0      | 3        | 1.17%   |
| OPNsense 23.1     | 2        | 0.78%   |
| OPNsense 22.7.5   | 2        | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 130      | 65%     |
| FreeBSD     | 37       | 18.5%   |
| helloSystem | 20       | 10%     |
| OpenBSD     | 5        | 2.5%    |
| GhostBSD    | 3        | 1.5%    |
| FreeNAS     | 3        | 1.5%    |
| TrueNAS     | 1        | 0.5%    |
| pfSense     | 1        | 0.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 196      | 99.49%  |
| i386  | 1        | 0.51%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 148      | 74%     |
| helloDesktop | 23       | 11.5%   |
| XFCE         | 8        | 4%      |
| KDE5         | 8        | 4%      |
| MATE         | 6        | 3%      |
| GNOME        | 2        | 1%      |
| Cinnamon     | 2        | 1%      |
| X-Cinnamon   | 1        | 0.5%    |
| Window Maker | 1        | 0.5%    |
| LXDE         | 1        | 0.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 149      | 75.63%  |
| X11     | 47       | 23.86%  |
| Wayland | 1        | 0.51%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 158      | 79%     |
| SLiM    | 23       | 11.5%   |
| SDDM    | 11       | 5.5%    |
| LightDM | 4        | 2%      |
| XDM     | 3        | 1.5%    |
| GDM     | 1        | 0.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 145      | 73.23%  |
| en_US   | 33       | 16.67%  |
| C       | 15       | 7.58%   |
| en_CA   | 3        | 1.52%   |
| fr_FR   | 2        | 1.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 165      | 82.09%  |
| BIOS | 36       | 17.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 113      | 55.39%  |
| Zfs    | 80       | 39.22%  |
| Cd9660 | 6        | 2.94%   |
| Ffs    | 5        | 2.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 181      | 91.88%  |
| MBR     | 15       | 7.61%   |
| Unknown | 1        | 0.51%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 25       | 12.69%  |
| Hewlett-Packard            | 24       | 12.18%  |
| Dell                       | 24       | 12.18%  |
| Lenovo                     | 15       | 7.61%   |
| Protectli                  | 13       | 6.6%    |
| Intel                      | 13       | 6.6%    |
| Gigabyte Technology        | 12       | 6.09%   |
| ASRock                     | 12       | 6.09%   |
| Unknown                    | 12       | 6.09%   |
| Supermicro                 | 10       | 5.08%   |
| MSI                        | 8        | 4.06%   |
| PC Engines                 | 5        | 2.54%   |
| Acer                       | 4        | 2.03%   |
| Techvision                 | 2        | 1.02%   |
| AZW                        | 2        | 1.02%   |
| Yanling                    | 1        | 0.51%   |
| Shuttle                    | 1        | 0.51%   |
| ShenZhen MinWin Technology | 1        | 0.51%   |
| SeeedStudio                | 1        | 0.51%   |
| Quanta                     | 1        | 0.51%   |
| Pegatron                   | 1        | 0.51%   |
| IBM                        | 1        | 0.51%   |
| HARDKERNEL                 | 1        | 0.51%   |
| Datto                      | 1        | 0.51%   |
| CncTion                    | 1        | 0.51%   |
| Cisco                      | 1        | 0.51%   |
| Biostar                    | 1        | 0.51%   |
| ASRockRack                 | 1        | 0.51%   |
| Apple                      | 1        | 0.51%   |
| AMI                        | 1        | 0.51%   |
| ADI Engineering            | 1        | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 12       | 6.09%   |
| Protectli FW4B                     | 7        | 3.55%   |
| Protectli FW6                      | 5        | 2.54%   |
| Intel Q3XXG4-P V1.0                | 5        | 2.54%   |
| Intel NDISB533                     | 4        | 2.03%   |
| HP EliteDesk 800 G1 SFF            | 3        | 1.52%   |
| Dell OptiPlex 9010                 | 3        | 1.52%   |
| Dell OptiPlex 7010                 | 3        | 1.52%   |
| Dell G5 5090                       | 3        | 1.52%   |
| ASUS All Series                    | 3        | 1.52%   |
| Techvision TVI7309X                | 2        | 1.02%   |
| Supermicro X8STi                   | 2        | 1.02%   |
| PC Engines apu4                    | 2        | 1.02%   |
| PC Engines APU2                    | 2        | 1.02%   |
| Lenovo ThinkCentre M93p 10A8S16X0J | 2        | 1.02%   |
| HP Z440 Workstation                | 2        | 1.02%   |
| HP Compaq Elite 8300 SFF           | 2        | 1.02%   |
| HP Compaq 8200 Elite SFF PC        | 2        | 1.02%   |
| Dell Precision WorkStation T3500   | 2        | 1.02%   |
| Dell Precision Tower 5810          | 2        | 1.02%   |
| Dell OptiPlex 3020                 | 2        | 1.02%   |
| ASUS P8H77-I                       | 2        | 1.02%   |
| ASUS M5A97 PLUS                    | 2        | 1.02%   |
| ASRock H110M-DGS R3.0              | 2        | 1.02%   |
| ASRock B450M Pro4                  | 2        | 1.02%   |
| Yanling YL-KBR6L                   | 1        | 0.51%   |
| Supermicro X9DR3-F                 | 1        | 0.51%   |
| Supermicro X7SPA-HF                | 1        | 0.51%   |
| Supermicro X7SLA                   | 1        | 0.51%   |
| Supermicro SYS-E300-9A             | 1        | 0.51%   |
| Supermicro SYS-5019S-ML            | 1        | 0.51%   |
| Supermicro SYS-5019D-FN8TP         | 1        | 0.51%   |
| Supermicro SYS-5019A-FTN4          | 1        | 0.51%   |
| Supermicro AS -5019D-FTN4          | 1        | 0.51%   |
| Shuttle DH110                      | 1        | 0.51%   |
| ShenZhen MinWin MW-GMLK-2.5G6L     | 1        | 0.51%   |
| SeeedStudio ODYSSEY-X86J4105       | 1        | 0.51%   |
| Quanta 120-1135                    | 1        | 0.51%   |
| Protectli FW6E                     | 1        | 0.51%   |
| Pegatron Compaq dx2450 Microtower  | 1        | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Dell OptiPlex                  | 16       | 8.12%   |
| Lenovo ThinkCentre             | 13       | 6.6%    |
| Unknown                        | 12       | 6.09%   |
| Protectli FW4B                 | 7        | 3.55%   |
| HP ProDesk                     | 6        | 3.05%   |
| ASUS PRIME                     | 6        | 3.05%   |
| Protectli FW6                  | 5        | 2.54%   |
| Intel Q3XXG4-P                 | 5        | 2.54%   |
| HP EliteDesk                   | 5        | 2.54%   |
| HP Compaq                      | 5        | 2.54%   |
| Dell Precision                 | 5        | 2.54%   |
| Intel NDISB533                 | 4        | 2.03%   |
| Acer Aspire                    | 4        | 2.03%   |
| Dell G5                        | 3        | 1.52%   |
| ASUS ROG                       | 3        | 1.52%   |
| ASUS All                       | 3        | 1.52%   |
| ASRock B450M                   | 3        | 1.52%   |
| Techvision TVI7309X            | 2        | 1.02%   |
| Supermicro X8STi               | 2        | 1.02%   |
| PC Engines apu4                | 2        | 1.02%   |
| PC Engines APU2                | 2        | 1.02%   |
| HP Z440                        | 2        | 1.02%   |
| ASUS P8H77-I                   | 2        | 1.02%   |
| ASUS M5A97                     | 2        | 1.02%   |
| ASRock H110M-DGS               | 2        | 1.02%   |
| Yanling YL-KBR6L               | 1        | 0.51%   |
| Supermicro X9DR3-F             | 1        | 0.51%   |
| Supermicro X7SPA-HF            | 1        | 0.51%   |
| Supermicro X7SLA               | 1        | 0.51%   |
| Supermicro SYS-E300-9A         | 1        | 0.51%   |
| Supermicro SYS-5019S-ML        | 1        | 0.51%   |
| Supermicro SYS-5019D-FN8TP     | 1        | 0.51%   |
| Supermicro SYS-5019A-FTN4      | 1        | 0.51%   |
| Supermicro AS                  | 1        | 0.51%   |
| Shuttle DH110                  | 1        | 0.51%   |
| ShenZhen MinWin MW-GMLK-2.5G6L | 1        | 0.51%   |
| SeeedStudio ODYSSEY-X86J4105   | 1        | 0.51%   |
| Quanta 120-1135                | 1        | 0.51%   |
| Protectli FW6E                 | 1        | 0.51%   |
| Pegatron Compaq                | 1        | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 35       | 17.77%  |
| 2020    | 26       | 13.2%   |
| 2014    | 21       | 10.66%  |
| 2013    | 17       | 8.63%   |
| 2016    | 15       | 7.61%   |
| 2019    | 14       | 7.11%   |
| 2022    | 11       | 5.58%   |
| 2010    | 10       | 5.08%   |
| 2011    | 9        | 4.57%   |
| 2017    | 7        | 3.55%   |
| 2015    | 7        | 3.55%   |
| 2012    | 7        | 3.55%   |
| 2021    | 6        | 3.05%   |
| 2009    | 6        | 3.05%   |
| 2008    | 3        | 1.52%   |
| 2007    | 1        | 0.51%   |
| 2006    | 1        | 0.51%   |
| Unknown | 1        | 0.51%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 197      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 190      | 96.45%  |
| Yes  | 7        | 3.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 79       | 39.11%  |
| 16.01-24.0  | 46       | 22.77%  |
| 4.01-8.0    | 33       | 16.34%  |
| 32.01-64.0  | 21       | 10.4%   |
| 64.01-256.0 | 9        | 4.46%   |
| 24.01-32.0  | 5        | 2.48%   |
| 2.01-3.0    | 5        | 2.48%   |
| 1.01-2.0    | 2        | 0.99%   |
| 3.01-4.0    | 1        | 0.5%    |
| 0.51-1.0    | 1        | 0.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.01-0.5    | 100      | 49.5%   |
| 0.51-1.0    | 60       | 29.7%   |
| 1.01-2.0    | 26       | 12.87%  |
| 4.01-8.0    | 4        | 1.98%   |
| 3.01-4.0    | 4        | 1.98%   |
| 2.01-3.0    | 4        | 1.98%   |
| 32.01-64.0  | 1        | 0.5%    |
| 64.01-256.0 | 1        | 0.5%    |
| 8.01-16.0   | 1        | 0.5%    |
| 0           | 1        | 0.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 139      | 69.85%  |
| 2      | 30       | 15.08%  |
| 3      | 11       | 5.53%   |
| 0      | 10       | 5.03%   |
| 4      | 5        | 2.51%   |
| 13     | 1        | 0.5%    |
| 10     | 1        | 0.5%    |
| 7      | 1        | 0.5%    |
| 5      | 1        | 0.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 155      | 77.11%  |
| Yes       | 46       | 22.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 195      | 98.98%  |
| No        | 2        | 1.02%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 160      | 80.4%   |
| Yes       | 39       | 19.6%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 172      | 87.31%  |
| Yes       | 25       | 12.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Canada  | 197      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                       | Desktops | Percent |
|----------------------------|----------|---------|
| Toronto                    | 19       | 9.09%   |
| Ottawa                     | 14       | 6.7%    |
| Montreal                   | 13       | 6.22%   |
| Edmonton                   | 10       | 4.78%   |
| Calgary                    | 9        | 4.31%   |
| Victoria                   | 8        | 3.83%   |
| Winnipeg                   | 7        | 3.35%   |
| Kitchener                  | 7        | 3.35%   |
| Vancouver                  | 5        | 2.39%   |
| Surrey                     | 5        | 2.39%   |
| Brampton                   | 4        | 1.91%   |
| Windsor                    | 3        | 1.44%   |
| St. Albert                 | 3        | 1.44%   |
| Sarnia                     | 3        | 1.44%   |
| Regina                     | 3        | 1.44%   |
| Moncton                    | 3        | 1.44%   |
| London                     | 3        | 1.44%   |
| Terrebonne                 | 2        | 0.96%   |
| St. Jean Baptiste          | 2        | 0.96%   |
| Saskatoon                  | 2        | 0.96%   |
| Sainte-Julie               | 2        | 0.96%   |
| Saint-Bruno-de-Montarville | 2        | 0.96%   |
| Richmond                   | 2        | 0.96%   |
| Québec                    | 2        | 0.96%   |
| Peterborough               | 2        | 0.96%   |
| Oakville                   | 2        | 0.96%   |
| Nanaimo                    | 2        | 0.96%   |
| Laval                      | 2        | 0.96%   |
| Kingston                   | 2        | 0.96%   |
| Kanata                     | 2        | 0.96%   |
| Hamilton                   | 2        | 0.96%   |
| Guelph                     | 2        | 0.96%   |
| Greater Sudbury            | 2        | 0.96%   |
| Cambridge                  | 2        | 0.96%   |
| Burnaby                    | 2        | 0.96%   |
| Burlington                 | 2        | 0.96%   |
| West Kelowna               | 1        | 0.48%   |
| Wallaceburg                | 1        | 0.48%   |
| Vaughan                    | 1        | 0.48%   |
| Uxbridge                   | 1        | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 37       | 50     | 15.23%  |
| Seagate             | 35       | 63     | 14.4%   |
| WDC                 | 34       | 74     | 13.99%  |
| Kingston            | 28       | 34     | 11.52%  |
| Crucial             | 12       | 15     | 4.94%   |
| Intel               | 10       | 12     | 4.12%   |
| SanDisk             | 8        | 10     | 3.29%   |
| A-DATA Technology   | 8        | 14     | 3.29%   |
| Toshiba             | 7        | 11     | 2.88%   |
| SPCC                | 4        | 4      | 1.65%   |
| OCZ                 | 4        | 5      | 1.65%   |
| Mushkin             | 4        | 4      | 1.65%   |
| Hitachi             | 4        | 4      | 1.65%   |
| Dogfish             | 4        | 7      | 1.65%   |
| BIWIN               | 4        | 5      | 1.65%   |
| PNY                 | 3        | 4      | 1.23%   |
| Micron Technology   | 3        | 6      | 1.23%   |
| Hoodisk             | 3        | 4      | 1.23%   |
| HGST                | 3        | 5      | 1.23%   |
| Hewlett-Packard     | 3        | 3      | 1.23%   |
| VisionTek           | 2        | 6      | 0.82%   |
| Transcend           | 2        | 3      | 0.82%   |
| SK hynix            | 2        | 4      | 0.82%   |
| NVMe                | 2        | 2      | 0.82%   |
| FORESEE             | 2        | 2      | 0.82%   |
| Corsair             | 2        | 4      | 0.82%   |
| China               | 2        | 3      | 0.82%   |
| Timetec             | 1        | 1      | 0.41%   |
| Team                | 1        | 1      | 0.41%   |
| SATADOM             | 1        | 2      | 0.41%   |
| Protectli           | 1        | 2      | 0.41%   |
| Phison              | 1        | 1      | 0.41%   |
| OPENBSD             | 1        | 1      | 0.41%   |
| Innodisk            | 1        | 1      | 0.41%   |
| HPE                 | 1        | 4      | 0.41%   |
| Fujitsu             | 1        | 1      | 0.41%   |
| EAGET               | 1        | 1      | 0.41%   |
| AVEXIR              | 1        | 2      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Kingston SA400S37240G 240GB     | 10       | 3.88%   |
| Kingston SA400S37120G 120GB     | 7        | 2.71%   |
| Seagate ST1000DM010-2EP102 1TB  | 5        | 1.94%   |
| Samsung SSD 850 EVO 250GB       | 5        | 1.94%   |
| Samsung SSD 860 EVO 500GB       | 4        | 1.55%   |
| BIWIN SSD 128GB                 | 4        | 1.55%   |
| WDC WD20EZRX-00DC0B0 2TB        | 3        | 1.16%   |
| Toshiba DT01ACA100 1TB          | 3        | 1.16%   |
| Seagate ST500DM002-1BD142 500GB | 3        | 1.16%   |
| Seagate ST3500413AS 500GB       | 3        | 1.16%   |
| SanDisk SD6SB1M064G1022I 64GB   | 3        | 1.16%   |
| Samsung SSD 840 EVO 120GB       | 3        | 1.16%   |
| Crucial CT240BX500SSD1 240GB    | 3        | 1.16%   |
| WDC WD40EFRX-68WT0N0 4TB        | 2        | 0.78%   |
| WDC WD10EZEX-22MFCA0 1TB        | 2        | 0.78%   |
| WDC WD10EZEX-08WN4A0 1TB        | 2        | 0.78%   |
| WDC PC SN520 NVMe 256GB         | 2        | 0.78%   |
| VisionTek mSATA 120GB           | 2        | 0.78%   |
| Transcend TS256GMSA230S 256GB   | 2        | 0.78%   |
| Toshiba MQ01ABD075 752GB        | 2        | 0.78%   |
| Seagate ST2000DM008-2FR102 2TB  | 2        | 0.78%   |
| Seagate ST1000DM003-1CH162 1TB  | 2        | 0.78%   |
| Samsung SSD 980 PRO 1TB         | 2        | 0.78%   |
| Samsung SSD 850 EVO mSATA 250GB | 2        | 0.78%   |
| Samsung SSD 840 EVO 250GB       | 2        | 0.78%   |
| PNY CS1311 120GB SSD            | 2        | 0.78%   |
| Mushkin MKNSSDEC60GB 64GB       | 2        | 0.78%   |
| Kingston SUV500MS120G 120GB     | 2        | 0.78%   |
| Intel SSDSC2BB080G4 80GB        | 2        | 0.78%   |
| Crucial CT1000MX500SSD1 1TB     | 2        | 0.78%   |
| A-DATA SU650 120GB              | 2        | 0.78%   |
| A-DATA SU630 240GB              | 2        | 0.78%   |
| WDC WDS500G2B0B-00YS70 500GB    | 1        | 0.39%   |
| WDC WDS500G2B0A-00SM50 500GB    | 1        | 0.39%   |
| WDC WDS250G3X0C-00SJG0 250GB    | 1        | 0.39%   |
| WDC WDS250G2B0A 250GB           | 1        | 0.39%   |
| WDC WDS120G2G0A-00JH30 120GB    | 1        | 0.39%   |
| WDC WDS100T2B0A-00SM50 1TB      | 1        | 0.39%   |
| WDC WD6400AAKS-22A7B2 640GB     | 1        | 0.39%   |
| WDC WD6003FZBX-00K5WB0 6TB      | 1        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 33       | 61     | 44%     |
| WDC     | 27       | 63     | 36%     |
| Toshiba | 6        | 8      | 8%      |
| Hitachi | 4        | 4      | 5.33%   |
| HGST    | 3        | 5      | 4%      |
| OPENBSD | 1        | 1      | 1.33%   |
| Fujitsu | 1        | 1      | 1.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 31       | 41     | 20.81%  |
| Kingston            | 28       | 33     | 18.79%  |
| Crucial             | 11       | 14     | 7.38%   |
| Intel               | 9        | 11     | 6.04%   |
| SanDisk             | 8        | 10     | 5.37%   |
| A-DATA Technology   | 8        | 14     | 5.37%   |
| WDC                 | 5        | 7      | 3.36%   |
| OCZ                 | 4        | 5      | 2.68%   |
| Mushkin             | 4        | 4      | 2.68%   |
| Dogfish             | 4        | 7      | 2.68%   |
| BIWIN               | 4        | 5      | 2.68%   |
| SPCC                | 3        | 3      | 2.01%   |
| PNY                 | 3        | 4      | 2.01%   |
| Micron Technology   | 3        | 6      | 2.01%   |
| Hoodisk             | 3        | 4      | 2.01%   |
| VisionTek           | 2        | 6      | 1.34%   |
| Transcend           | 2        | 3      | 1.34%   |
| Seagate             | 2        | 2      | 1.34%   |
| FORESEE             | 2        | 2      | 1.34%   |
| Corsair             | 2        | 4      | 1.34%   |
| China               | 2        | 3      | 1.34%   |
| SATADOM             | 1        | 2      | 0.67%   |
| Protectli           | 1        | 2      | 0.67%   |
| Phison              | 1        | 1      | 0.67%   |
| NVMe                | 1        | 1      | 0.67%   |
| Innodisk            | 1        | 1      | 0.67%   |
| HPE                 | 1        | 4      | 0.67%   |
| Hewlett-Packard     | 1        | 1      | 0.67%   |
| EAGET               | 1        | 1      | 0.67%   |
| AVEXIR              | 1        | 2      | 0.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 135      | 203    | 62.5%   |
| HDD  | 61       | 143    | 28.24%  |
| NVMe | 20       | 29     | 9.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 178      | 346    | 89.9%   |
| NVMe | 20       | 29     | 10.1%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 149      | 218    | 70.95%  |
| 0.51-1.0   | 33       | 56     | 15.71%  |
| 1.01-2.0   | 12       | 21     | 5.71%   |
| 3.01-4.0   | 6        | 17     | 2.86%   |
| 2.01-3.0   | 4        | 9      | 1.9%    |
| 4.01-10.0  | 4        | 22     | 1.9%    |
| 10.01-20.0 | 2        | 3      | 0.95%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 86       | 41.95%  |
| 251-500        | 35       | 17.07%  |
| 51-100         | 25       | 12.2%   |
| 1-20           | 22       | 10.73%  |
| 21-50          | 18       | 8.78%   |
| 501-1000       | 10       | 4.88%   |
| 1001-2000      | 5        | 2.44%   |
| More than 3000 | 2        | 0.98%   |
| Unknown        | 2        | 0.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 182      | 87.92%  |
| 21-50     | 17       | 8.21%   |
| 51-100    | 4        | 1.93%   |
| Unknown   | 2        | 0.97%   |
| 1001-2000 | 1        | 0.48%   |
| 501-1000  | 1        | 0.48%   |

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
| WDC WD6400AAKS-22A7B2 640GB                | 1        | 4      | 2.86%   |
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
| WDC                 | 6        | 10     | 17.65%  |
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
| WDC     | 6        | 10     | 25%     |
| Toshiba | 3        | 5      | 12.5%   |
| Hitachi | 2        | 2      | 8.33%   |
| HGST    | 2        | 3      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 22       | 38     | 68.75%  |
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
| Works    | 169      | 312    | 81.64%  |
| Malfunc  | 31       | 56     | 14.98%  |
| Detected | 6        | 6      | 2.9%    |
| Failed   | 1        | 1      | 0.48%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 160      | 67.51%  |
| AMD                         | 35       | 14.77%  |
| Samsung Electronics         | 8        | 3.38%   |
| SanDisk                     | 5        | 2.11%   |
| Nvidia                      | 5        | 2.11%   |
| Silicon Motion              | 4        | 1.69%   |
| ASMedia Technology          | 4        | 1.69%   |
| Broadcom / LSI              | 3        | 1.27%   |
| SK hynix                    | 2        | 0.84%   |
| Silicon Image               | 2        | 0.84%   |
| JMicron Technology          | 2        | 0.84%   |
| Chelsio Communications      | 2        | 0.84%   |
| Toshiba                     | 1        | 0.42%   |
| Micron/Crucial Technology   | 1        | 0.42%   |
| MAXIO Technology (Hangzhou) | 1        | 0.42%   |
| Marvell Technology Group    | 1        | 0.42%   |
| Kingston Technology Company | 1        | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 26       | 9.42%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 14       | 5.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 13       | 4.71%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 13       | 4.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 10       | 3.62%   |
| AMD 400 Series Chipset SATA Controller                                           | 10       | 3.62%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 8        | 2.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 8        | 2.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8        | 2.9%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7        | 2.54%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 7        | 2.54%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 7        | 2.54%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 6        | 2.17%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 5        | 1.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4        | 1.45%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4        | 1.45%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 4        | 1.45%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4        | 1.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4        | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 4        | 1.45%   |
| AMD FCH SATA Controller [IDE mode]                                               | 4        | 1.45%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 3        | 1.09%   |
| SanDisk PC SN520 NVMe SSD                                                        | 3        | 1.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3        | 1.09%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3        | 1.09%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3        | 1.09%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 3        | 1.09%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3        | 1.09%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 2        | 0.72%   |
| Nvidia MCP61 SATA Controller                                                     | 2        | 0.72%   |
| JMicron JMB363 SATA/IDE Controller                                               | 2        | 0.72%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2        | 0.72%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2        | 0.72%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 2        | 0.72%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 2        | 0.72%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2        | 0.72%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 2        | 0.72%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2        | 0.72%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2        | 0.72%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 2        | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 173      | 72.69%  |
| IDE  | 30       | 12.61%  |
| NVMe | 22       | 9.24%   |
| RAID | 6        | 2.52%   |
| SAS  | 4        | 1.68%   |
| SCSI | 3        | 1.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 161      | 80.5%   |
| AMD    | 39       | 19.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Intel Core i5-4570 CPU @ 3.20GHz    | 7        | 3.47%   |
| Intel Core i5-3570 CPU @ 3.40GHz    | 7        | 3.47%   |
| Intel Celeron CPU J3160 @ 1.60GHz   | 7        | 3.47%   |
| Intel Core i5-6500 CPU @ 3.20GHz    | 6        | 2.97%   |
| Intel Celeron N5105 @ 2.00GHz       | 5        | 2.48%   |
| Intel Celeron J4125 CPU @ 2.00GHz   | 5        | 2.48%   |
| Intel Core i5-4590 CPU @ 3.30GHz    | 4        | 1.98%   |
| Intel Core i5-4570TE CPU @ 2.70GHz  | 4        | 1.98%   |
| AMD GX-412TC SOC                    | 4        | 1.98%   |
| Intel Xeon                          | 3        | 1.49%   |
| Intel Pentium CPU G4560 @ 3.50GHz   | 3        | 1.49%   |
| Intel Core i7-9700K CPU @ 3.60GHz   | 3        | 1.49%   |
| Intel Core i7-3770 CPU @ 3.40GHz    | 3        | 1.49%   |
| Intel Core i5-7200U CPU @ 2.50GHz   | 3        | 1.49%   |
| AMD Ryzen 5 2600 Six-Core Processor | 3        | 1.49%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz | 2        | 0.99%   |
| Intel Core i7-8550U CPU @ 1.80GHz   | 2        | 0.99%   |
| Intel Core i7-7700 CPU @ 3.60GHz    | 2        | 0.99%   |
| Intel Core i7-4790K CPU @ 4.00GHz   | 2        | 0.99%   |
| Intel Core i5-8400 CPU @ 2.80GHz    | 2        | 0.99%   |
| Intel Core i5-4670 CPU @ 3.40GHz    | 2        | 0.99%   |
| Intel Core i5-4460 CPU @ 3.20GHz    | 2        | 0.99%   |
| Intel Core i5-3470T CPU @ 2.90GHz   | 2        | 0.99%   |
| Intel Core i5-3470 CPU @ 3.20GHz    | 2        | 0.99%   |
| Intel Core i5-2500 CPU @ 3.30GHz    | 2        | 0.99%   |
| Intel Core i3-4030U CPU @ 1.90GHz   | 2        | 0.99%   |
| Intel Celeron J4105 CPU @ 1.50GHz   | 2        | 0.99%   |
| Intel Celeron CPU J3455 @ 1.50GHz   | 2        | 0.99%   |
| Intel Celeron CPU J1900 @ 1.99GHz   | 2        | 0.99%   |
| AMD FX-8350 Eight-Core Processor    | 2        | 0.99%   |
| AMD FX-8320E Eight-Core Processor   | 2        | 0.99%   |
| AMD FX-4350 Quad-Core Processor     | 2        | 0.99%   |
| Intel Xeon D-2146NT CPU @ 2.30GHz   | 1        | 0.5%    |
| Intel Xeon CPU X5660 @ 2.80GHz      | 1        | 0.5%    |
| Intel Xeon CPU W3530 @ 2.80GHz      | 1        | 0.5%    |
| Intel Xeon CPU L5640 @ 2.27GHz      | 1        | 0.5%    |
| Intel Xeon CPU E5645 @ 2.40GHz      | 1        | 0.5%    |
| Intel Xeon CPU E5506 @ 2.13GHz      | 1        | 0.5%    |
| Intel Xeon CPU E5-2697 v2 @ 2.70GHz | 1        | 0.5%    |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz | 1        | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 61       | 30.35%  |
| Intel Celeron           | 27       | 13.43%  |
| Intel Xeon              | 19       | 9.45%   |
| Intel Core i7           | 17       | 8.46%   |
| Intel Core i3           | 16       | 7.96%   |
| Intel Atom              | 7        | 3.48%   |
| Intel Pentium           | 6        | 2.99%   |
| AMD FX                  | 6        | 2.99%   |
| AMD Ryzen 5             | 5        | 2.49%   |
| AMD GX                  | 5        | 2.49%   |
| Other                   | 3        | 1.49%   |
| AMD Ryzen 9             | 3        | 1.49%   |
| AMD Ryzen 7             | 3        | 1.49%   |
| AMD Athlon 64 X2        | 3        | 1.49%   |
| Intel Pentium Dual-Core | 2        | 1%      |
| Intel Core 2 Quad       | 2        | 1%      |
| Intel Core 2 Duo        | 2        | 1%      |
| AMD Ryzen 3             | 2        | 1%      |
| Intel Pentium 4         | 1        | 0.5%    |
| AMD Ryzen Embedded      | 1        | 0.5%    |
| AMD Ryzen 5 PRO         | 1        | 0.5%    |
| AMD Phenom II X6        | 1        | 0.5%    |
| AMD Phenom              | 1        | 0.5%    |
| AMD G                   | 1        | 0.5%    |
| AMD EPYC                | 1        | 0.5%    |
| AMD E                   | 1        | 0.5%    |
| AMD Athlon Dual Core    | 1        | 0.5%    |
| AMD Athlon              | 1        | 0.5%    |
| AMD A6                  | 1        | 0.5%    |
| AMD A4                  | 1        | 0.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 106      | 53%     |
| 2       | 46       | 23%     |
| 8       | 14       | 7%      |
| 6       | 14       | 7%      |
| 12      | 6        | 3%      |
| 16      | 4        | 2%      |
| 32      | 2        | 1%      |
| 24      | 2        | 1%      |
| 10      | 2        | 1%      |
| Unknown | 2        | 1%      |
| 11      | 1        | 0.5%    |
| 3       | 1        | 0.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 194      | 98.48%  |
| 2       | 2        | 1.02%   |
| Unknown | 1        | 0.51%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 129      | 65.15%  |
| 2       | 67       | 33.84%  |
| Unknown | 2        | 1.01%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 38       | 18.81%  |
| KabyLake      | 22       | 10.89%  |
| IvyBridge     | 20       | 9.9%    |
| Skylake       | 13       | 6.44%   |
| Silvermont    | 12       | 5.94%   |
| SandyBridge   | 8        | 3.96%   |
| Goldmont plus | 8        | 3.96%   |
| Zen+          | 7        | 3.47%   |
| Piledriver    | 7        | 3.47%   |
| Unknown       | 7        | 3.47%   |
| Westmere      | 6        | 2.97%   |
| Penryn        | 6        | 2.97%   |
| Goldmont      | 6        | 2.97%   |
| Broadwell     | 5        | 2.48%   |
| Zen           | 4        | 1.98%   |
| Puma          | 4        | 1.98%   |
| K8 Hammer     | 4        | 1.98%   |
| CometLake     | 4        | 1.98%   |
| Nehalem       | 3        | 1.49%   |
| K10           | 3        | 1.49%   |
| Jaguar        | 3        | 1.49%   |
| Bonnell       | 3        | 1.49%   |
| Zen 3         | 2        | 0.99%   |
| Zen 2         | 2        | 0.99%   |
| Bobcat        | 2        | 0.99%   |
| TigerLake     | 1        | 0.5%    |
| NetBurst      | 1        | 0.5%    |
| Core          | 1        | 0.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 122      | 63.21%  |
| Nvidia                     | 32       | 16.58%  |
| AMD                        | 28       | 14.51%  |
| ASPEED Technology          | 7        | 3.63%   |
| Matrox Electronics Systems | 4        | 2.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 26       | 13.33%  |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 10       | 5.13%   |
| Intel HD Graphics 530                                                                    | 10       | 5.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9        | 4.62%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8        | 4.1%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 7        | 3.59%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6        | 3.08%   |
| Intel JasperLake [UHD Graphics]                                                          | 5        | 2.56%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 5        | 2.56%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 2.05%   |
| Intel HD Graphics 630                                                                    | 4        | 2.05%   |
| Intel HD Graphics 610                                                                    | 4        | 2.05%   |
| Intel HD Graphics 500                                                                    | 4        | 2.05%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4        | 2.05%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4        | 2.05%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 3        | 1.54%   |
| Intel UHD Graphics 620                                                                   | 3        | 1.54%   |
| Intel HD Graphics 620                                                                    | 3        | 1.54%   |
| Intel HD Graphics 5500                                                                   | 3        | 1.54%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 1.54%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 2        | 1.03%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 1.03%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 1.03%   |
| Nvidia GM107GL [Quadro K620]                                                             | 2        | 1.03%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 1.03%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 1.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 1.03%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 1.03%   |
| AMD RS780L [Radeon 3000]                                                                 | 2        | 1.03%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 1.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2        | 1.03%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 2        | 1.03%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2        | 1.03%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1        | 0.51%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1        | 0.51%   |
| Nvidia GT218 [GeForce 310]                                                               | 1        | 0.51%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 0.51%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 0.51%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                                        | 1        | 0.51%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 118      | 59%     |
| 1 x Nvidia     | 30       | 15%     |
| 1 x AMD        | 27       | 13.5%   |
| Other          | 9        | 4.5%    |
| 1 x ASPEED     | 7        | 3.5%    |
| 1 x Matrox     | 4        | 2%      |
| 2 x Intel      | 2        | 1%      |
| Intel + Nvidia | 2        | 1%      |
| 2 x AMD        | 1        | 0.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 171      | 85.93%  |
| Proprietary | 19       | 9.55%   |
| Unknown     | 9        | 4.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 170      | 85.86%  |
| 0.51-1.0   | 8        | 4.04%   |
| 1.01-2.0   | 7        | 3.54%   |
| 7.01-8.0   | 4        | 2.02%   |
| 3.01-4.0   | 4        | 2.02%   |
| 5.01-6.0   | 3        | 1.52%   |
| 2.01-3.0   | 1        | 0.51%   |
| 0.01-0.5   | 1        | 0.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 9        | 20%     |
| BenQ                 | 6        | 13.33%  |
| Dell                 | 5        | 11.11%  |
| Samsung Electronics  | 3        | 6.67%   |
| Lenovo               | 3        | 6.67%   |
| ASUSTek Computer     | 3        | 6.67%   |
| Acer                 | 3        | 6.67%   |
| Sony                 | 2        | 4.44%   |
| Hewlett-Packard      | 2        | 4.44%   |
| AOC                  | 2        | 4.44%   |
| ViewSonic            | 1        | 2.22%   |
| Videoseven           | 1        | 2.22%   |
| Toshiba              | 1        | 2.22%   |
| LTV                  | 1        | 2.22%   |
| LG Electronics       | 1        | 2.22%   |
| Insignia             | 1        | 2.22%   |
| Ancor Communications | 1        | 2.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Sony LCD Monitor TV XV 1920x1080                                       | 2        | 4.08%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 2        | 4.08%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch               | 2        | 4.08%   |
| ViewSonic LCD Monitor VSCFA2B 1920x1080 510x290mm 23.1-inch            | 1        | 2.04%   |
| Videoseven WL19A IGM1908 1280x1024 380x300mm 19.1-inch                 | 1        | 2.04%   |
| Toshiba TV TSB0200 1920x1080 530x300mm 24.0-inch                       | 1        | 2.04%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1210x680mm 54.6-inch | 1        | 2.04%   |
| LTV LTV1280M1A LTV0A3C 1024x768 800x450mm 36.1-inch                    | 1        | 2.04%   |
| LG Electronics LCD Monitor LG Ultra HD 7680x2160                       | 1        | 2.04%   |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1        | 2.04%   |
| Lenovo LEN-M93z-B  LEN0093 1920x1080 510x290mm 23.1-inch               | 1        | 2.04%   |
| Insignia LCD Monitor BBY0050 1920x1080 700x400mm 31.7-inch             | 1        | 2.04%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch       | 1        | 2.04%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch             | 1        | 2.04%   |
| Goldstar W2442 GSM56D9 1920x1080 530x300mm 24.0-inch                   | 1        | 2.04%   |
| Goldstar W2052 GSM4E88 1680x1050 470x300mm 22.0-inch                   | 1        | 2.04%   |
| Goldstar MP59G GSM5B35 1920x1080 600x340mm 27.2-inch                   | 1        | 2.04%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                   | 1        | 2.04%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch            | 1        | 2.04%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch            | 1        | 2.04%   |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch               | 1        | 2.04%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 1        | 2.04%   |
| Goldstar LG FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch              | 1        | 2.04%   |
| Goldstar LCD Monitor GSM76F5 1920x1080 700x390mm 31.5-inch             | 1        | 2.04%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 600x340mm 27.2-inch                 | 1        | 2.04%   |
| Dell P3222QE DEL4246 3840x2160 700x390mm 31.5-inch                     | 1        | 2.04%   |
| Dell P2311H DEL4067 1920x1080 510x290mm 23.1-inch                      | 1        | 2.04%   |
| Dell P2219H DELA114 1920x1080 480x270mm 21.7-inch                      | 1        | 2.04%   |
| Dell LCD Monitor DELF003 1440x900 410x260mm 19.1-inch                  | 1        | 2.04%   |
| Dell 2001FP DELA008 1600x1200 410x310mm 20.2-inch                      | 1        | 2.04%   |
| BenQ XL2430T BNQ7F3D 1920x1080 530x300mm 24.0-inch                     | 1        | 2.04%   |
| BenQ LCD Monitor PD3200Q                                               | 1        | 2.04%   |
| BenQ LCD Monitor GW2765                                                | 1        | 2.04%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                      | 1        | 2.04%   |
| BenQ GL2460 BNQ78CE 1920x1080 530x300mm 24.0-inch                      | 1        | 2.04%   |
| BenQ G900HD BNQ7816 1366x768 410x230mm 18.5-inch                       | 1        | 2.04%   |
| BenQ BL2780 BNQ802B 1920x1080 600x340mm 27.2-inch                      | 1        | 2.04%   |
| ASUSTek Computer VP228 AUS22A1 1920x1080 480x270mm 21.7-inch           | 1        | 2.04%   |
| ASUSTek Computer ROG PG259QN AUS25B5 1920x1080 540x300mm 24.3-inch     | 1        | 2.04%   |
| ASUSTek Computer ROG PG259QN AUS25B4 1920x1080 540x300mm 24.3-inch     | 1        | 2.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 24       | 54.55%  |
| 3840x2160 (4K)     | 5        | 11.36%  |
| 1680x1050 (WSXGA+) | 2        | 4.55%   |
| 1440x900 (WXGA+)   | 2        | 4.55%   |
| Unknown            | 2        | 4.55%   |
| 7680x2160          | 1        | 2.27%   |
| 3440x1440          | 1        | 2.27%   |
| 2560x1440 (QHD)    | 1        | 2.27%   |
| 2560x1080          | 1        | 2.27%   |
| 1600x900 (HD+)     | 1        | 2.27%   |
| 1600x1200          | 1        | 2.27%   |
| 1366x768 (WXGA)    | 1        | 2.27%   |
| 1280x1024 (SXGA)   | 1        | 2.27%   |
| 1024x768 (XGA)     | 1        | 2.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 12       | 26.09%  |
| 21      | 6        | 13.04%  |
| 27      | 5        | 10.87%  |
| 19      | 4        | 8.7%    |
| Unknown | 4        | 8.7%    |
| 54      | 3        | 6.52%   |
| 23      | 3        | 6.52%   |
| 34      | 2        | 4.35%   |
| 31      | 2        | 4.35%   |
| 22      | 2        | 4.35%   |
| 36      | 1        | 2.17%   |
| 20      | 1        | 2.17%   |
| 18      | 1        | 2.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 19       | 42.22%  |
| 401-500     | 13       | 28.89%  |
| Unknown     | 4        | 8.89%   |
| 701-800     | 3        | 6.67%   |
| 1001-1500   | 3        | 6.67%   |
| 601-700     | 2        | 4.44%   |
| 351-400     | 1        | 2.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 31       | 72.09%  |
| 16/10   | 4        | 9.3%    |
| Unknown | 4        | 9.3%    |
| 21/9    | 2        | 4.65%   |
| 5/4     | 1        | 2.33%   |
| 4/3     | 1        | 2.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 20       | 44.44%  |
| 301-350        | 5        | 11.11%  |
| 151-200        | 5        | 11.11%  |
| 351-500        | 4        | 8.89%   |
| Unknown        | 4        | 8.89%   |
| More than 1000 | 3        | 6.67%   |
| 251-300        | 2        | 4.44%   |
| 141-150        | 1        | 2.22%   |
| 501-1000       | 1        | 2.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 31       | 67.39%  |
| 101-120 | 8        | 17.39%  |
| Unknown | 4        | 8.7%    |
| 1-50    | 1        | 2.17%   |
| 161-240 | 1        | 2.17%   |
| 121-160 | 1        | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 152      | 76.38%  |
| 1     | 39       | 19.6%   |
| 2     | 8        | 4.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 152      | 56.3%   |
| Realtek Semiconductor           | 79       | 29.26%  |
| Broadcom                        | 12       | 4.44%   |
| Qualcomm Atheros                | 8        | 2.96%   |
| Solarflare Communications       | 3        | 1.11%   |
| Ralink                          | 2        | 0.74%   |
| MediaTek                        | 2        | 0.74%   |
| Marvell Technology Group        | 2        | 0.74%   |
| Chelsio Communications          | 2        | 0.74%   |
| 3Com                            | 2        | 0.74%   |
| Qualcomm Atheros Communications | 1        | 0.37%   |
| NetGear                         | 1        | 0.37%   |
| Mellanox Technologies           | 1        | 0.37%   |
| IMC Networks                    | 1        | 0.37%   |
| Google                          | 1        | 0.37%   |
| D-Link System                   | 1        | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 68       | 20.3%   |
| Intel I211 Gigabit Network Connection                                         | 25       | 7.46%   |
| Intel 82574L Gigabit Network Connection                                       | 21       | 6.27%   |
| Intel Ethernet Connection I217-LM                                             | 20       | 5.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 15       | 4.48%   |
| Intel I350 Gigabit Network Connection                                         | 12       | 3.58%   |
| Intel 82583V Gigabit Network Connection                                       | 9        | 2.69%   |
| Intel 82580 Gigabit Network Connection                                        | 8        | 2.39%   |
| Intel I210 Gigabit Network Connection                                         | 7        | 2.09%   |
| Intel Ethernet Controller I225-V                                              | 7        | 2.09%   |
| Intel 82576 Gigabit Network Connection                                        | 7        | 2.09%   |
| Realtek RTL8125 2.5GbE Controller                                             | 6        | 1.79%   |
| Intel Wi-Fi 6 AX200                                                           | 6        | 1.79%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6        | 1.79%   |
| Intel Ethernet Connection (2) I219-LM                                         | 5        | 1.49%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 4        | 1.19%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 4        | 1.19%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3        | 0.9%    |
| Intel Wireless 7260                                                           | 3        | 0.9%    |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3        | 0.9%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3        | 0.9%    |
| Intel 82541PI Gigabit Ethernet Controller                                     | 3        | 0.9%    |
| Solarflare SFC9020 10G Ethernet Controller                                    | 2        | 0.6%    |
| Intel Wireless 3165                                                           | 2        | 0.6%    |
| Intel NM10/ICH7 Family LAN Controller                                         | 2        | 0.6%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2        | 0.6%    |
| Intel Ethernet Connection I217-V                                              | 2        | 0.6%    |
| Intel Ethernet Connection (5) I219-LM                                         | 2        | 0.6%    |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 0.6%    |
| Intel Ethernet Connection (2) I218-LM                                         | 2        | 0.6%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 0.6%    |
| Intel 82599 10 Gigabit Network Connection                                     | 2        | 0.6%    |
| Intel 82575GB Gigabit Network Connection                                      | 2        | 0.6%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 2        | 0.6%    |
| 3Com 3c905C-TX/TX-M [Tornado]                                                 | 2        | 0.6%    |
| Solarflare SFC9120 10G Ethernet Controller                                    | 1        | 0.3%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1        | 0.3%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.3%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 20       | 50%     |
| Qualcomm Atheros                | 6        | 15%     |
| Realtek Semiconductor           | 5        | 12.5%   |
| Ralink                          | 2        | 5%      |
| MediaTek                        | 2        | 5%      |
| Broadcom                        | 2        | 5%      |
| Qualcomm Atheros Communications | 1        | 2.5%    |
| NetGear                         | 1        | 2.5%    |
| IMC Networks                    | 1        | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 6        | 14.63%  |
| Intel Wireless 7260                                                     | 3        | 7.32%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3        | 7.32%   |
| Intel Wireless 3165                                                     | 2        | 4.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1        | 2.44%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1        | 2.44%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 2.44%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1        | 2.44%   |
| Realtek Realtek Bluetooth Adapter                                       | 1        | 2.44%   |
| Ralink RT5592 PCIe Wireless Network Adapter                             | 1        | 2.44%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                    | 1        | 2.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1        | 2.44%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 2.44%   |
| Qualcomm Atheros AR958x 802.11abgn Wireless Network Adapter             | 1        | 2.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1        | 2.44%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1        | 2.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1        | 2.44%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 2.44%   |
| NetGear A6200 802.11a/b/g/n/ac Wireless Adapter [Broadcom BCM43526]     | 1        | 2.44%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1        | 2.44%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1        | 2.44%   |
| Intel Wireless 8260                                                     | 1        | 2.44%   |
| Intel Wireless 7265                                                     | 1        | 2.44%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1        | 2.44%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1        | 2.44%   |
| Intel Centrino Wireless-N 105                                           | 1        | 2.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1        | 2.44%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 1        | 2.44%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 1        | 2.44%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1        | 2.44%   |
| Broadcom BCM4321 802.11b/g/n                                            | 1        | 2.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 142      | 58.44%  |
| Realtek Semiconductor     | 78       | 32.1%   |
| Broadcom                  | 10       | 4.12%   |
| Solarflare Communications | 3        | 1.23%   |
| Qualcomm Atheros          | 2        | 0.82%   |
| Marvell Technology Group  | 2        | 0.82%   |
| Chelsio Communications    | 2        | 0.82%   |
| 3Com                      | 2        | 0.82%   |
| Google                    | 1        | 0.41%   |
| D-Link System             | 1        | 0.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 68       | 23.29%  |
| Intel I211 Gigabit Network Connection                                         | 25       | 8.56%   |
| Intel 82574L Gigabit Network Connection                                       | 21       | 7.19%   |
| Intel Ethernet Connection I217-LM                                             | 20       | 6.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 15       | 5.14%   |
| Intel I350 Gigabit Network Connection                                         | 12       | 4.11%   |
| Intel 82583V Gigabit Network Connection                                       | 9        | 3.08%   |
| Intel 82580 Gigabit Network Connection                                        | 8        | 2.74%   |
| Intel I210 Gigabit Network Connection                                         | 7        | 2.4%    |
| Intel Ethernet Controller I225-V                                              | 7        | 2.4%    |
| Intel 82576 Gigabit Network Connection                                        | 7        | 2.4%    |
| Realtek RTL8125 2.5GbE Controller                                             | 6        | 2.05%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6        | 2.05%   |
| Intel Ethernet Connection (2) I219-LM                                         | 5        | 1.71%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 4        | 1.37%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 4        | 1.37%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3        | 1.03%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 1.03%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3        | 1.03%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 3        | 1.03%   |
| Solarflare SFC9020 10G Ethernet Controller                                    | 2        | 0.68%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 2        | 0.68%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2        | 0.68%   |
| Intel Ethernet Connection I217-V                                              | 2        | 0.68%   |
| Intel Ethernet Connection (5) I219-LM                                         | 2        | 0.68%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 0.68%   |
| Intel Ethernet Connection (2) I218-LM                                         | 2        | 0.68%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 0.68%   |
| Intel 82599 10 Gigabit Network Connection                                     | 2        | 0.68%   |
| Intel 82575GB Gigabit Network Connection                                      | 2        | 0.68%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 2        | 0.68%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                                 | 2        | 0.68%   |
| Solarflare SFC9120 10G Ethernet Controller                                    | 1        | 0.34%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1        | 0.34%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.34%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.34%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                       | 1        | 0.34%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.34%   |
| Intel Ethernet Controller X550                                                | 1        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 195      | 82.63%  |
| WiFi     | 39       | 16.53%  |
| Unknown  | 2        | 0.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 191      | 95.5%   |
| WiFi     | 9        | 4.5%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 50       | 25%     |
| 1     | 37       | 18.5%   |
| 3     | 34       | 17%     |
| 4     | 33       | 16.5%   |
| 5     | 21       | 10.5%   |
| 6     | 15       | 7.5%    |
| 7     | 4        | 2%      |
| 8     | 2        | 1%      |
| 0     | 2        | 1%      |
| 10    | 1        | 0.5%    |
| 9     | 1        | 0.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 174      | 86.14%  |
| Yes  | 28       | 13.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 15       | 60%     |
| Cambridge Silicon Radio         | 4        | 16%     |
| Realtek Semiconductor           | 1        | 4%      |
| Qualcomm Atheros Communications | 1        | 4%      |
| MediaTek                        | 1        | 4%      |
| IMC Networks                    | 1        | 4%      |
| Foxconn / Hon Hai               | 1        | 4%      |
| Apple                           | 1        | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                   | 5        | 20%     |
| Intel AX200 Bluetooth                                | 5        | 20%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 4        | 16%     |
| Intel Wireless-AC 3168 Bluetooth                     | 3        | 12%     |
| Realtek  Bluetooth 4.2 Adapter                       | 1        | 4%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                | 1        | 4%      |
| MediaTek Wireless_Device                             | 1        | 4%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 1        | 4%      |
| Intel AX201 Bluetooth                                | 1        | 4%      |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip | 1        | 4%      |
| Foxconn / Hon Hai Bluetooth USB Module               | 1        | 4%      |
| Apple Built-in Bluetooth 2.0+EDR HCI                 | 1        | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 118      | 60.2%   |
| AMD                 | 36       | 18.37%  |
| Nvidia              | 30       | 15.31%  |
| Logitech            | 3        | 1.53%   |
| C-Media Electronics | 2        | 1.02%   |
| Yamaha              | 1        | 0.51%   |
| Texas Instruments   | 1        | 0.51%   |
| SteelSeries ApS     | 1        | 0.51%   |
| KTMicro             | 1        | 0.51%   |
| Elgato Systems      | 1        | 0.51%   |
| Creative Labs       | 1        | 0.51%   |
| ASUSTek Computer    | 1        | 0.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 24       | 10%     |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 24       | 10%     |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11       | 4.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8        | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8        | 3.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8        | 3.33%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8        | 3.33%   |
| Intel 200 Series PCH HD Audio                                                                     | 7        | 2.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6        | 2.5%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 6        | 2.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5        | 2.08%   |
| Intel Jasper Lake HD Audio                                                                        | 5        | 2.08%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5        | 2.08%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5        | 2.08%   |
| Nvidia High Definition Audio Controller                                                           | 4        | 1.67%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4        | 1.67%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 4        | 1.67%   |
| Intel Broadwell-U Audio Controller                                                                | 4        | 1.67%   |
| Intel 8 Series HD Audio Controller                                                                | 4        | 1.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4        | 1.67%   |
| AMD FCH Azalia Controller                                                                         | 4        | 1.67%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3        | 1.25%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3        | 1.25%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3        | 1.25%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3        | 1.25%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3        | 1.25%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3        | 1.25%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3        | 1.25%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2        | 0.83%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2        | 0.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2        | 0.83%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2        | 0.83%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2        | 0.83%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2        | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2        | 0.83%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 2        | 0.83%   |
| AMD Navi 10 HDMI Audio                                                                            | 2        | 0.83%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 2        | 0.83%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2        | 0.83%   |
| Yamaha Steinberg UR22mkII                                                                         | 1        | 0.42%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 35       | 15.63%  |
| SK hynix            | 34       | 15.18%  |
| Samsung Electronics | 34       | 15.18%  |
| Unknown             | 21       | 9.38%   |
| Corsair             | 20       | 8.93%   |
| Crucial             | 16       | 7.14%   |
| G.Skill             | 14       | 6.25%   |
| Micron Technology   | 10       | 4.46%   |
| Apacer              | 5        | 2.23%   |
| Team                | 4        | 1.79%   |
| Ramaxel Technology  | 4        | 1.79%   |
| Unknown (0x0C26)    | 3        | 1.34%   |
| Patriot             | 3        | 1.34%   |
| Nanya Technology    | 3        | 1.34%   |
| A-DATA Technology   | 3        | 1.34%   |
| Unknown             | 3        | 1.34%   |
| TIMETEC             | 2        | 0.89%   |
| OCZ                 | 2        | 0.89%   |
| V-Color             | 1        | 0.45%   |
| Unknown (ABCD)      | 1        | 0.45%   |
| Unknown (0x0DD5)    | 1        | 0.45%   |
| Transcend           | 1        | 0.45%   |
| Toshiba             | 1        | 0.45%   |
| PNY                 | 1        | 0.45%   |
| Cors                | 1        | 0.45%   |
| Avant               | 1        | 0.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s     | 5        | 2.07%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 4        | 1.65%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 1600MT/s     | 4        | 1.65%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s | 4        | 1.65%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s     | 3        | 1.24%   |
| Kingston RAM KHX1600C10D3/8G 4GB DIMM DDR3 1600MT/s     | 3        | 1.24%   |
| Unknown                                                 | 3        | 1.24%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 2        | 0.83%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 2        | 0.83%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 2        | 0.83%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 2        | 0.83%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s    | 2        | 0.83%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s    | 2        | 0.83%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s    | 2        | 0.83%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s    | 2        | 0.83%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB RIMM DDR4 2133MT/s    | 2        | 0.83%   |
| SK hynix RAM HMA451R7AFR8N-TF 4GB RIMM DDR4 2133MT/s    | 2        | 0.83%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 2        | 0.83%   |
| Samsung RAM M471B5173DB0-YK0 4GB DIMM DDR3 1600MT/s     | 2        | 0.83%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s     | 2        | 0.83%   |
| Micron RAM 9ASF51272PZ-2G1A2 4GB RIMM DDR4 2133MT/s     | 2        | 0.83%   |
| G.Skill RAM F4-2666C19-8GNT 8GB DIMM DDR4 2666MT/s      | 2        | 0.83%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s     | 2        | 0.83%   |
| Corsair RAM CMV8GX3M1A1333C9 8GB DIMM DDR3 1333MT/s     | 2        | 0.83%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1333MT/s     | 2        | 0.83%   |
| Corsair RAM CML16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s   | 2        | 0.83%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s  | 2        | 0.83%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3000MT/s  | 2        | 0.83%   |
| V-Color RAM VCOLOR-TD2G16C9-H8 2GB DIMM 1333MT/s        | 1        | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR4 2666MT/s               | 1        | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s               | 1        | 0.41%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 1        | 0.41%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                  | 1        | 0.41%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s               | 1        | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s              | 1        | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 1        | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR 1066MT/s                | 1        | 0.41%   |
| Unknown RAM Module 2GB DIMM 400MT/s                     | 1        | 0.41%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s             | 1        | 0.41%   |
| Unknown RAM Module 1GB DIMM SDRAM 667MT/s               | 1        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 95       | 50%     |
| DDR4    | 71       | 37.37%  |
| Unknown | 9        | 4.74%   |
| DDR2    | 7        | 3.68%   |
| SDRAM   | 4        | 2.11%   |
| DDR     | 2        | 1.05%   |
| LPDDR4  | 1        | 0.53%   |
| DDR5    | 1        | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 135      | 72.97%  |
| SODIMM | 47       | 25.41%  |
| RIMM   | 3        | 1.62%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 76       | 36.54%  |
| 8192  | 70       | 33.65%  |
| 16384 | 26       | 12.5%   |
| 2048  | 26       | 12.5%   |
| 1024  | 7        | 3.37%   |
| 32768 | 2        | 0.96%   |
| 512   | 1        | 0.48%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 71       | 34.47%  |
| 1333    | 29       | 14.08%  |
| 2400    | 21       | 10.19%  |
| 2133    | 19       | 9.22%   |
| 2667    | 13       | 6.31%   |
| 3200    | 12       | 5.83%   |
| 800     | 7        | 3.4%    |
| 2666    | 6        | 2.91%   |
| 667     | 4        | 1.94%   |
| Unknown | 4        | 1.94%   |
| 3600    | 3        | 1.46%   |
| 3000    | 3        | 1.46%   |
| 1066    | 3        | 1.46%   |
| 1866    | 2        | 0.97%   |
| 1067    | 2        | 0.97%   |
| 400     | 2        | 0.97%   |
| 5200    | 1        | 0.49%   |
| 4800    | 1        | 0.49%   |
| 3400    | 1        | 0.49%   |
| 1334    | 1        | 0.49%   |
| 333     | 1        | 0.49%   |

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
| Logitech            | 2        | 50%     |
| Microdia            | 1        | 25%     |
| Chicony Electronics | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Microdia JOYACCESS JA-Webcam | 1        | 25%     |
| Logitech Webcam C310         | 1        | 25%     |
| Logitech HD Pro Webcam C920  | 1        | 25%     |
| Chicony HP 0.3MP Webcam      | 1        | 25%     |

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
| 1     | 115      | 56.65%  |
| 0     | 60       | 29.56%  |
| 2     | 22       | 10.84%  |
| 4     | 3        | 1.48%   |
| 3     | 3        | 1.48%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 126      | 75.9%   |
| Net/wireless             | 14       | 8.43%   |
| Bluetooth                | 7        | 4.22%   |
| Sound                    | 5        | 3.01%   |
| Firewire controller      | 4        | 2.41%   |
| Net/ethernet             | 3        | 1.81%   |
| Card reader              | 3        | 1.81%   |
| Network                  | 2        | 1.2%    |
| Storage/raid             | 1        | 0.6%    |
| Graphics card            | 1        | 0.6%    |

