BSD in Brazil - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for BSD in Brazil.

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

Total: 119

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | 2820h                       | [d888b8b775](https://bsd-hardware.info/?probe=d888b8b775) | Apr 22, 2022 |
| Intel         | H55                         | [1478e4af73](https://bsd-hardware.info/?probe=1478e4af73) | Apr 20, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [11ec99d4b7](https://bsd-hardware.info/?probe=11ec99d4b7) | Apr 11, 2022 |
| ASUSTek       | P5G41T-M LX V2              | [64de6d6bb9](https://bsd-hardware.info/?probe=64de6d6bb9) | Mar 24, 2022 |
| ASUSTek       | P5G41T-M LX V2              | [99ab8e7989](https://bsd-hardware.info/?probe=99ab8e7989) | Mar 11, 2022 |
| Pegatron      | IPM41-D3                    | [a58b9a4f8f](https://bsd-hardware.info/?probe=a58b9a4f8f) | Mar 09, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [62474001e3](https://bsd-hardware.info/?probe=62474001e3) | Mar 09, 2022 |
| MSI           | U-100 Ver.001               | [50aba1dee8](https://bsd-hardware.info/?probe=50aba1dee8) | Mar 03, 2022 |
| MSI           | U-100 Ver.001               | [6859308aa9](https://bsd-hardware.info/?probe=6859308aa9) | Mar 01, 2022 |
| HP            | 1905                        | [e271589365](https://bsd-hardware.info/?probe=e271589365) | Mar 01, 2022 |
| HP            | 1905                        | [aa010e00f2](https://bsd-hardware.info/?probe=aa010e00f2) | Feb 28, 2022 |
| KLLISRE       | X99-B5 V1.0                 | [5dea1304b9](https://bsd-hardware.info/?probe=5dea1304b9) | Feb 26, 2022 |
| GALAX         | B365M G10b                  | [ceb2291168](https://bsd-hardware.info/?probe=ceb2291168) | Feb 22, 2022 |
| HP            | 83E1                        | [d8e995126f](https://bsd-hardware.info/?probe=d8e995126f) | Feb 10, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [d57de875a6](https://bsd-hardware.info/?probe=d57de875a6) | Feb 07, 2022 |
| Unknown       | YL-E3845L4-V2               | [24e60f4686](https://bsd-hardware.info/?probe=24e60f4686) | Feb 02, 2022 |
| Dell          | 0GDG8Y A02                  | [343129f659](https://bsd-hardware.info/?probe=343129f659) | Feb 01, 2022 |
| Gigabyte      | C847N                       | [0d62b7756c](https://bsd-hardware.info/?probe=0d62b7756c) | Jan 24, 2022 |
| ASUSTek       | J1800I-C/BR                 | [13d6d1ed51](https://bsd-hardware.info/?probe=13d6d1ed51) | Jan 21, 2022 |
| Unknown       | Phitronics G31VS-M          | [820f706b46](https://bsd-hardware.info/?probe=820f706b46) | Jan 06, 2022 |
| Unknown       | G31T-M7                     | [ed7d80e01a](https://bsd-hardware.info/?probe=ed7d80e01a) | Jan 03, 2022 |
| Pegatron      | IPM41-D3                    | [6829928dad](https://bsd-hardware.info/?probe=6829928dad) | Dec 28, 2021 |
| Unknown       | X79                         | [c80b658f36](https://bsd-hardware.info/?probe=c80b658f36) | Nov 09, 2021 |
| Itautec       | ST 4344 ST-4344 Padrao 0... | [ec13cb0829](https://bsd-hardware.info/?probe=ec13cb0829) | Nov 07, 2021 |
| Unknown       | X79                         | [ef88cbc606](https://bsd-hardware.info/?probe=ef88cbc606) | Nov 05, 2021 |
| Dell          | 0M5DCD A02                  | [4ff4198768](https://bsd-hardware.info/?probe=4ff4198768) | Nov 02, 2021 |
| Gigabyte      | G41MT-S2                    | [2847d63db0](https://bsd-hardware.info/?probe=2847d63db0) | Oct 18, 2021 |
| ASRock        | A320M-DGS                   | [11cf5c923a](https://bsd-hardware.info/?probe=11cf5c923a) | Oct 08, 2021 |
| ASUSTek       | J1800I-C/BR                 | [e7395898d8](https://bsd-hardware.info/?probe=e7395898d8) | Sep 25, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [b00f275d35](https://bsd-hardware.info/?probe=b00f275d35) | Sep 23, 2021 |
| ASUSTek       | J1800I-C/BR                 | [91642a928d](https://bsd-hardware.info/?probe=91642a928d) | Sep 20, 2021 |
| PCWare        | PW-945GCX                   | [04bbdf92d6](https://bsd-hardware.info/?probe=04bbdf92d6) | Sep 13, 2021 |
| Unknown       | Phitronics G31VS-M          | [0d13c20ba5](https://bsd-hardware.info/?probe=0d13c20ba5) | Sep 11, 2021 |
| Gigabyte      | H61M-S1                     | [0a1be200c6](https://bsd-hardware.info/?probe=0a1be200c6) | Aug 29, 2021 |
| Gigabyte      | H61M-S1                     | [a129f532bd](https://bsd-hardware.info/?probe=a129f532bd) | Aug 28, 2021 |
| Gigabyte      | H61M-S2-B3                  | [7c9c49f924](https://bsd-hardware.info/?probe=7c9c49f924) | Aug 27, 2021 |
| ECS-USA       | GeForce6100PM-M2            | [f6324966fb](https://bsd-hardware.info/?probe=f6324966fb) | Aug 26, 2021 |
| ASUSTek       | P5Q                         | [01c4a15001](https://bsd-hardware.info/?probe=01c4a15001) | Aug 22, 2021 |
| HC            | HCAR357-MI V1.0             | [3293b7bad9](https://bsd-hardware.info/?probe=3293b7bad9) | Aug 17, 2021 |
| Gigabyte      | C847N                       | [c19601f640](https://bsd-hardware.info/?probe=c19601f640) | Aug 07, 2021 |
| Gigabyte      | H61M-S2-B3                  | [d1790c6aed](https://bsd-hardware.info/?probe=d1790c6aed) | Aug 04, 2021 |
| Intel         | Q3XXG4-P V1.0               | [1aad7a6eab](https://bsd-hardware.info/?probe=1aad7a6eab) | Aug 03, 2021 |
| Intel         | Q3XXG4-P V1.0               | [95573fe387](https://bsd-hardware.info/?probe=95573fe387) | Aug 03, 2021 |
| Pegatron      | IPM41-D3                    | [524215c510](https://bsd-hardware.info/?probe=524215c510) | Aug 03, 2021 |
| ECS           | BAT-I                       | [6741011e07](https://bsd-hardware.info/?probe=6741011e07) | Aug 02, 2021 |
| Yanling       | NS-1U8L                     | [6166362d7a](https://bsd-hardware.info/?probe=6166362d7a) | Jul 27, 2021 |
| ULTRATOP      | C2017-LIVA-ZE               | [d091f171b7](https://bsd-hardware.info/?probe=d091f171b7) | Jun 23, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [5f9b56c8ae](https://bsd-hardware.info/?probe=5f9b56c8ae) | Jun 15, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [edebe87739](https://bsd-hardware.info/?probe=edebe87739) | Jun 04, 2021 |
| Dell          | 0GDG8Y A02                  | [5b44835ac1](https://bsd-hardware.info/?probe=5b44835ac1) | Jun 03, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [c44be632d3](https://bsd-hardware.info/?probe=c44be632d3) | May 28, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [5675cca325](https://bsd-hardware.info/?probe=5675cca325) | May 28, 2021 |
| Gigabyte      | H61M-S2-B3                  | [b73e45e0df](https://bsd-hardware.info/?probe=b73e45e0df) | May 27, 2021 |
| Toshiba       | STI 005492G                 | [9a8e4a1328](https://bsd-hardware.info/?probe=9a8e4a1328) | May 17, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [e69be420df](https://bsd-hardware.info/?probe=e69be420df) | May 16, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [01cc3a3802](https://bsd-hardware.info/?probe=01cc3a3802) | Apr 11, 2021 |
| Gigabyte      | C847N                       | [1d9e74caab](https://bsd-hardware.info/?probe=1d9e74caab) | Apr 08, 2021 |
| Dell          | 04YP6J A03                  | [779e2e4d2d](https://bsd-hardware.info/?probe=779e2e4d2d) | Apr 05, 2021 |
| Pegatron      | IPM41-D3                    | [687047b3d2](https://bsd-hardware.info/?probe=687047b3d2) | Mar 30, 2021 |
| Dell          | 04YP6J A03                  | [59efed23b2](https://bsd-hardware.info/?probe=59efed23b2) | Mar 30, 2021 |
| Dell          | 0P301D A01                  | [bd0c36fe70](https://bsd-hardware.info/?probe=bd0c36fe70) | Mar 26, 2021 |
| ECS           | H55H-CM                     | [a2808d49c9](https://bsd-hardware.info/?probe=a2808d49c9) | Mar 25, 2021 |
| ECS           | H55H-CM                     | [3b13b3a934](https://bsd-hardware.info/?probe=3b13b3a934) | Mar 25, 2021 |
| ECS           | H55H-CM                     | [5df8692ddd](https://bsd-hardware.info/?probe=5df8692ddd) | Mar 18, 2021 |
| ECS           | H55H-CM                     | [6a10af558b](https://bsd-hardware.info/?probe=6a10af558b) | Mar 18, 2021 |
| Pegatron      | IPM41-D3                    | [fdfc8e2b9b](https://bsd-hardware.info/?probe=fdfc8e2b9b) | Mar 17, 2021 |
| ASUSTek       | H81M-C/BR                   | [c4b2356821](https://bsd-hardware.info/?probe=c4b2356821) | Mar 17, 2021 |
| ASUSTek       | H81M-C/BR                   | [c23066d56d](https://bsd-hardware.info/?probe=c23066d56d) | Mar 17, 2021 |
| Gigabyte      | 970A-UD3P                   | [cc3151bc6f](https://bsd-hardware.info/?probe=cc3151bc6f) | Mar 17, 2021 |
| Gigabyte      | H61M-S2-B3                  | [35f1d21b73](https://bsd-hardware.info/?probe=35f1d21b73) | Mar 16, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [49509bf7ee](https://bsd-hardware.info/?probe=49509bf7ee) | Mar 13, 2021 |
| Dell          | 0HN7XN A01                  | [3339a68c44](https://bsd-hardware.info/?probe=3339a68c44) | Mar 12, 2021 |
| ASRock        | 970A-G                      | [3e474f93cf](https://bsd-hardware.info/?probe=3e474f93cf) | Mar 04, 2021 |
| ASUSTek       | H110M-K                     | [b33294491e](https://bsd-hardware.info/?probe=b33294491e) | Mar 02, 2021 |
| MSI           | E350IS-E45                  | [2d4f50994d](https://bsd-hardware.info/?probe=2d4f50994d) | Feb 24, 2021 |
| ASUSTek       | P5Q                         | [22fa0d8178](https://bsd-hardware.info/?probe=22fa0d8178) | Feb 23, 2021 |
| Intel         | H61                         | [a8ae96a0ab](https://bsd-hardware.info/?probe=a8ae96a0ab) | Feb 23, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [405b36b911](https://bsd-hardware.info/?probe=405b36b911) | Feb 21, 2021 |
| Dell          | 0M8K4M A00                  | [6d3defcde3](https://bsd-hardware.info/?probe=6d3defcde3) | Feb 21, 2021 |
| Intel         | Q3XXG4-P V1.0               | [337aa08686](https://bsd-hardware.info/?probe=337aa08686) | Feb 18, 2021 |
| Intel         | Q3XXG4-P V1.0               | [7699b1e79f](https://bsd-hardware.info/?probe=7699b1e79f) | Feb 18, 2021 |
| Intel         | Q3XXG4-P V1.0               | [7ef872c122](https://bsd-hardware.info/?probe=7ef872c122) | Feb 18, 2021 |
| ASRock        | A320M-DGS                   | [d8a1ca5210](https://bsd-hardware.info/?probe=d8a1ca5210) | Feb 17, 2021 |
| Pegatron      | IPM41-D3                    | [ffc1292c18](https://bsd-hardware.info/?probe=ffc1292c18) | Feb 16, 2021 |
| Pegatron      | IPM41-D3                    | [6e5c330c9c](https://bsd-hardware.info/?probe=6e5c330c9c) | Feb 16, 2021 |
| Intel         | Q3XXG4-P V1.0               | [190d0ed47e](https://bsd-hardware.info/?probe=190d0ed47e) | Feb 16, 2021 |
| Intel         | Q3XXG4-P V1.0               | [32a87da376](https://bsd-hardware.info/?probe=32a87da376) | Feb 16, 2021 |
| Intel         | Q3XXG4-P V1.0               | [cf042892e7](https://bsd-hardware.info/?probe=cf042892e7) | Feb 16, 2021 |
| Dell          | 0GDG8Y A02                  | [5cda8abfad](https://bsd-hardware.info/?probe=5cda8abfad) | Feb 14, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [694204751b](https://bsd-hardware.info/?probe=694204751b) | Feb 13, 2021 |
| Dell          | 07N90W A02                  | [6bbd0de8d9](https://bsd-hardware.info/?probe=6bbd0de8d9) | Feb 08, 2021 |
| ASRock        | A320M-DGS                   | [7c179e0033](https://bsd-hardware.info/?probe=7c179e0033) | Feb 06, 2021 |
| HP            | ProLiant ML350 G6           | [0539585a88](https://bsd-hardware.info/?probe=0539585a88) | Feb 05, 2021 |
| Positivo      | POS-EAA75DE                 | [cb30dbeef2](https://bsd-hardware.info/?probe=cb30dbeef2) | Feb 05, 2021 |
| Positivo      | POS-EAA75DE                 | [65147f9da6](https://bsd-hardware.info/?probe=65147f9da6) | Feb 05, 2021 |
| Positivo      | POS-EAA75DE                 | [c1fb910e23](https://bsd-hardware.info/?probe=c1fb910e23) | Feb 05, 2021 |
| Intel         | Q3XXG4-P V1.0               | [7833038238](https://bsd-hardware.info/?probe=7833038238) | Feb 01, 2021 |
| Intel         | Q3XXG4-P V1.0               | [d46871a402](https://bsd-hardware.info/?probe=d46871a402) | Feb 01, 2021 |
| Intel         | Q3XXG4-P V1.0               | [52d17aa061](https://bsd-hardware.info/?probe=52d17aa061) | Jan 28, 2021 |
| Intel         | DH61WW AAG23116-206         | [85a0e6c728](https://bsd-hardware.info/?probe=85a0e6c728) | Jan 24, 2021 |
| Intel         | DH61WW AAG23116-206         | [3e468c1461](https://bsd-hardware.info/?probe=3e468c1461) | Jan 23, 2021 |
| PCWare        | IPX1800G2                   | [bc9bce51bc](https://bsd-hardware.info/?probe=bc9bce51bc) | Jan 22, 2021 |
| MSI           | J1800I                      | [98abf7d1f0](https://bsd-hardware.info/?probe=98abf7d1f0) | Jan 22, 2021 |
| MSI           | J1800I                      | [b6adf4005e](https://bsd-hardware.info/?probe=b6adf4005e) | Jan 21, 2021 |
| HP            | ProLiant ML310e Gen8 v2     | [ba328938c3](https://bsd-hardware.info/?probe=ba328938c3) | Jan 21, 2021 |
| Intel         | Q3XXG4-P V1.0               | [23e48fdef0](https://bsd-hardware.info/?probe=23e48fdef0) | Jan 21, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [75e86a92f7](https://bsd-hardware.info/?probe=75e86a92f7) | Dec 05, 2020 |
| HP            | ProLiant MicroServer Gen... | [825a724001](https://bsd-hardware.info/?probe=825a724001) | Oct 25, 2020 |
| HP            | ProLiant MicroServer        | [04b6ad9952](https://bsd-hardware.info/?probe=04b6ad9952) | Oct 25, 2020 |
| ASUSTek       | Z8P                         | [7b0818f96a](https://bsd-hardware.info/?probe=7b0818f96a) | Sep 16, 2020 |
| ASUSTek       | Z8P                         | [f59746efd0](https://bsd-hardware.info/?probe=f59746efd0) | Sep 09, 2020 |
| ASUSTek       | Z8P                         | [4876488739](https://bsd-hardware.info/?probe=4876488739) | Sep 02, 2020 |
| ASUSTek       | STRIX B250G GAMING          | [a02398f78f](https://bsd-hardware.info/?probe=a02398f78f) | Sep 01, 2020 |
| ASUSTek       | Z8P                         | [9f5845a398](https://bsd-hardware.info/?probe=9f5845a398) | Jul 27, 2020 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | [7e845aab76](https://bsd-hardware.info/?probe=7e845aab76) | Jul 26, 2020 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | [7febd3108d](https://bsd-hardware.info/?probe=7febd3108d) | Jul 26, 2020 |
| Procomp In... | G41MXE                      | [a76a3bb201](https://bsd-hardware.info/?probe=a76a3bb201) | Jul 25, 2020 |
| ASUSTek       | Z8P                         | [5071a32803](https://bsd-hardware.info/?probe=5071a32803) | Jun 05, 2020 |
| ASUSTek       | Z8P                         | [a0723b0566](https://bsd-hardware.info/?probe=a0723b0566) | Jun 05, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| OPNsense 20.7.8      | 6        | 6.74%   |
| OPNsense 21.1.3      | 5        | 5.62%   |
| OPNsense 21.1        | 5        | 5.62%   |
| helloSystem 0.7.0    | 5        | 5.62%   |
| helloSystem 0.4.0    | 5        | 5.62%   |
| OPNsense 21.1.1      | 4        | 4.49%   |
| helloSystem 0.6.0    | 4        | 4.49%   |
| helloSystem 0.5.0    | 4        | 4.49%   |
| OPNsense 21.7.7      | 3        | 3.37%   |
| OPNsense 21.7.1      | 3        | 3.37%   |
| OPNsense 21.1.9      | 3        | 3.37%   |
| OPNsense 21.1.6      | 3        | 3.37%   |
| OPNsense 21.1.4      | 3        | 3.37%   |
| FreeBSD 14.0-CURRENT | 3        | 3.37%   |
| OPNsense 22.1        | 2        | 2.25%   |
| OPNsense 21.1.7      | 2        | 2.25%   |
| OPNsense 21.1.2      | 2        | 2.25%   |
| NomadBSD 5806f915    | 2        | 2.25%   |
| FreeBSD 13.0-p7      | 2        | 2.25%   |
| FreeBSD 13.0         | 2        | 2.25%   |
| TrueNAS 12.2-p9      | 1        | 1.12%   |
| pfSense 2.4.5        | 1        | 1.12%   |
| OPNsense 22.1.3      | 1        | 1.12%   |
| OPNsense 22.1.2      | 1        | 1.12%   |
| OPNsense 21.7.3      | 1        | 1.12%   |
| OPNsense 21.7.2      | 1        | 1.12%   |
| OPNsense 21.7        | 1        | 1.12%   |
| OPNsense 21.1.8      | 1        | 1.12%   |
| OpenBSD 6.8          | 1        | 1.12%   |
| NetBSD 9.2           | 1        | 1.12%   |
| FreeNAS 11.3-p9      | 1        | 1.12%   |
| FreeNAS 11.3-p11     | 1        | 1.12%   |
| FreeBSD 13.0-p4      | 1        | 1.12%   |
| FreeBSD 13.0-p3      | 1        | 1.12%   |
| FreeBSD 13.0-CURRENT | 1        | 1.12%   |
| FreeBSD 12.2-p3      | 1        | 1.12%   |
| FreeBSD 12.2-p1      | 1        | 1.12%   |
| FreeBSD 12.2         | 1        | 1.12%   |
| FreeBSD 12.1-p7      | 1        | 1.12%   |
| FreeBSD 12.1-p10     | 1        | 1.12%   |
| FreeBSD 12.1         | 1        | 1.12%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 35       | 47.3%   |
| helloSystem | 16       | 21.62%  |
| FreeBSD     | 16       | 21.62%  |
| NomadBSD    | 2        | 2.7%    |
| TrueNAS     | 1        | 1.35%   |
| pfSense     | 1        | 1.35%   |
| OpenBSD     | 1        | 1.35%   |
| NetBSD      | 1        | 1.35%   |
| FreeNAS     | 1        | 1.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 71       | 98.61%  |
| i386  | 1        | 1.39%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 38       | 51.35%  |
| helloDesktop | 17       | 22.97%  |
| KDE5         | 8        | 10.81%  |
| Openbox      | 4        | 5.41%   |
| XFCE         | 3        | 4.05%   |
| Window Maker | 1        | 1.35%   |
| TWM          | 1        | 1.35%   |
| MATE         | 1        | 1.35%   |
| GNOME        | 1        | 1.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 40       | 55.56%  |
| X11     | 32       | 44.44%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 44       | 60.27%  |
| SLiM    | 18       | 24.66%  |
| SDDM    | 7        | 9.59%   |
| GDM     | 3        | 4.11%   |
| XDM     | 1        | 1.37%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 39       | 53.42%  |
| en_US   | 17       | 23.29%  |
| pt_BR   | 9        | 12.33%  |
| C       | 7        | 9.59%   |
| fr_FR   | 1        | 1.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 52       | 69.33%  |
| BIOS | 23       | 30.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 45       | 61.64%  |
| Zfs    | 25       | 34.25%  |
| Cd9660 | 2        | 2.74%   |
| Ffs    | 1        | 1.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 60       | 81.08%  |
| MBR     | 13       | 17.57%  |
| Unknown | 1        | 1.35%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUSTek Computer        | 17       | 23.61%  |
| Intel                   | 8        | 11.11%  |
| Hewlett-Packard         | 7        | 9.72%   |
| Gigabyte Technology     | 7        | 9.72%   |
| Dell                    | 7        | 9.72%   |
| Unknown                 | 4        | 5.56%   |
| MSI                     | 3        | 4.17%   |
| Pegatron                | 2        | 2.78%   |
| PCWare                  | 2        | 2.78%   |
| Itautec                 | 2        | 2.78%   |
| ECS                     | 2        | 2.78%   |
| ASRock                  | 2        | 2.78%   |
| Yanling                 | 1        | 1.39%   |
| ULTRATOP                | 1        | 1.39%   |
| Semp Toshiba            | 1        | 1.39%   |
| Procomp Ind. Eletronica | 1        | 1.39%   |
| Positivo                | 1        | 1.39%   |
| KLLISRE                 | 1        | 1.39%   |
| HC                      | 1        | 1.39%   |
| GALAX                   | 1        | 1.39%   |
| ECS-USA                 | 1        | 1.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Intel Q3XXG4-P V1.0                | 5        | 6.94%   |
| ASUS All Series                    | 4        | 5.56%   |
| Unknown                            | 4        | 5.56%   |
| Pegatron IPM41-D3                  | 2        | 2.78%   |
| Gigabyte H61M-S2-B3                | 2        | 2.78%   |
| ASUS PRIME B450M-GAMING/BR         | 2        | 2.78%   |
| ASUS P8H61-M LX3 PLUS R2.0         | 2        | 2.78%   |
| ASUS M5A78L-M LX/BR                | 2        | 2.78%   |
| Yanling NS-1U8L                    | 1        | 1.39%   |
| ULTRATOP C2017-LIVA-ZE             | 1        | 1.39%   |
| Semp Toshiba STI                   | 1        | 1.39%   |
| Procomp Ind. Eletronica G41MXE     | 1        | 1.39%   |
| Positivo POS-EAA75DE               | 1        | 1.39%   |
| PCWare PW-945GCX                   | 1        | 1.39%   |
| PCWare IPX1800G2                   | 1        | 1.39%   |
| MSI U-100                          | 1        | 1.39%   |
| MSI MS-7877                        | 1        | 1.39%   |
| MSI MS-7698                        | 1        | 1.39%   |
| KLLISRE X99-B5 V1.0                | 1        | 1.39%   |
| Itautec Infoway ST-4344            | 1        | 1.39%   |
| Itautec Infoway                    | 1        | 1.39%   |
| Intel H61                          | 1        | 1.39%   |
| Intel H55                          | 1        | 1.39%   |
| Intel DH61WW AAG23116-206          | 1        | 1.39%   |
| HP Z230 Tower Workstation          | 1        | 1.39%   |
| HP ProLiant ML350 G6               | 1        | 1.39%   |
| HP ProLiant ML310e Gen8 v2         | 1        | 1.39%   |
| HP ProLiant MicroServer Gen8       | 1        | 1.39%   |
| HP ProLiant MicroServer            | 1        | 1.39%   |
| HP EliteDesk 800 G4 SFF            | 1        | 1.39%   |
| HP Compaq dc5800 Small Form Factor | 1        | 1.39%   |
| HC HCAR357-MI                      | 1        | 1.39%   |
| Gigabyte H61M-S1                   | 1        | 1.39%   |
| Gigabyte G41MT-S2                  | 1        | 1.39%   |
| Gigabyte C847N                     | 1        | 1.39%   |
| Gigabyte AB350M-Gaming 3           | 1        | 1.39%   |
| Gigabyte 970A-UD3P                 | 1        | 1.39%   |
| GALAX B365M                        | 1        | 1.39%   |
| ECS-USA GeForce6100PM-M2           | 1        | 1.39%   |
| ECS H55H-CM                        | 1        | 1.39%   |
| ECS BAT-I                          | 1        | 1.39%   |
| Dell Vostro 230                    | 1        | 1.39%   |
| Dell Vostro 220s Series            | 1        | 1.39%   |
| Dell OptiPlex 390                  | 1        | 1.39%   |
| Dell OptiPlex 380                  | 1        | 1.39%   |
| Dell OptiPlex 3020                 | 1        | 1.39%   |
| Dell Inspiron 620                  | 1        | 1.39%   |
| Dell Inspiron 5680                 | 1        | 1.39%   |
| ASUS Z8P                           | 1        | 1.39%   |
| ASUS STRIX B250G GAMING            | 1        | 1.39%   |
| ASUS P5Q                           | 1        | 1.39%   |
| ASUS P5G41T-M LX V2                | 1        | 1.39%   |
| ASUS M5A97 LE R2.0                 | 1        | 1.39%   |
| ASUS M5A78L-M PLUS/USB3            | 1        | 1.39%   |
| ASUS H110M-K                       | 1        | 1.39%   |
| ASRock A320M-DGS                   | 1        | 1.39%   |
| ASRock 970A-G                      | 1        | 1.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel Q3XXG4-P                 | 5        | 6.94%   |
| HP ProLiant                    | 4        | 5.56%   |
| ASUS All                       | 4        | 5.56%   |
| Unknown                        | 4        | 5.56%   |
| Dell OptiPlex                  | 3        | 4.17%   |
| ASUS M5A78L-M                  | 3        | 4.17%   |
| Pegatron IPM41-D3              | 2        | 2.78%   |
| Itautec Infoway                | 2        | 2.78%   |
| Gigabyte H61M-S2-B3            | 2        | 2.78%   |
| Dell Vostro                    | 2        | 2.78%   |
| Dell Inspiron                  | 2        | 2.78%   |
| ASUS PRIME                     | 2        | 2.78%   |
| ASUS P8H61-M                   | 2        | 2.78%   |
| Yanling NS-1U8L                | 1        | 1.39%   |
| ULTRATOP C2017-LIVA-ZE         | 1        | 1.39%   |
| Semp Toshiba STI               | 1        | 1.39%   |
| Procomp Ind. Eletronica G41MXE | 1        | 1.39%   |
| Positivo POS-EAA75DE           | 1        | 1.39%   |
| PCWare PW-945GCX               | 1        | 1.39%   |
| PCWare IPX1800G2               | 1        | 1.39%   |
| MSI U-100                      | 1        | 1.39%   |
| MSI MS-7877                    | 1        | 1.39%   |
| MSI MS-7698                    | 1        | 1.39%   |
| KLLISRE X99-B5                 | 1        | 1.39%   |
| Intel H61                      | 1        | 1.39%   |
| Intel H55                      | 1        | 1.39%   |
| Intel DH61WW                   | 1        | 1.39%   |
| HP Z230                        | 1        | 1.39%   |
| HP EliteDesk                   | 1        | 1.39%   |
| HP Compaq                      | 1        | 1.39%   |
| HC HCAR357-MI                  | 1        | 1.39%   |
| Gigabyte H61M-S1               | 1        | 1.39%   |
| Gigabyte G41MT-S2              | 1        | 1.39%   |
| Gigabyte C847N                 | 1        | 1.39%   |
| Gigabyte AB350M-Gaming         | 1        | 1.39%   |
| Gigabyte 970A-UD3P             | 1        | 1.39%   |
| GALAX B365M                    | 1        | 1.39%   |
| ECS-USA GeForce6100PM-M2       | 1        | 1.39%   |
| ECS H55H-CM                    | 1        | 1.39%   |
| ECS BAT-I                      | 1        | 1.39%   |
| ASUS Z8P                       | 1        | 1.39%   |
| ASUS STRIX                     | 1        | 1.39%   |
| ASUS P5Q                       | 1        | 1.39%   |
| ASUS P5G41T-M                  | 1        | 1.39%   |
| ASUS M5A97                     | 1        | 1.39%   |
| ASUS H110M-K                   | 1        | 1.39%   |
| ASRock A320M-DGS               | 1        | 1.39%   |
| ASRock 970A-G                  | 1        | 1.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2016 | 13       | 18.06%  |
| 2010 | 7        | 9.72%   |
| 2018 | 6        | 8.33%   |
| 2013 | 6        | 8.33%   |
| 2009 | 6        | 8.33%   |
| 2019 | 5        | 6.94%   |
| 2012 | 5        | 6.94%   |
| 2011 | 5        | 6.94%   |
| 2020 | 4        | 5.56%   |
| 2017 | 3        | 4.17%   |
| 2015 | 3        | 4.17%   |
| 2014 | 3        | 4.17%   |
| 2008 | 3        | 4.17%   |
| 2021 | 2        | 2.78%   |
| 2007 | 1        | 1.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 72       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 72       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 28       | 38.89%  |
| 8.01-16.0  | 22       | 30.56%  |
| 16.01-24.0 | 12       | 16.67%  |
| 2.01-3.0   | 6        | 8.33%   |
| 32.01-64.0 | 4        | 5.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 49       | 67.12%  |
| 0.51-1.0   | 16       | 21.92%  |
| 1.01-2.0   | 4        | 5.48%   |
| 4.01-8.0   | 2        | 2.74%   |
| 16.01-24.0 | 1        | 1.37%   |
| Unknown    | 1        | 1.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 53       | 70.67%  |
| 2      | 8        | 10.67%  |
| 3      | 6        | 8%      |
| 0      | 3        | 4%      |
| 5      | 2        | 2.67%   |
| 7      | 1        | 1.33%   |
| 6      | 1        | 1.33%   |
| 4      | 1        | 1.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 56       | 77.78%  |
| Yes       | 16       | 22.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 71       | 98.61%  |
| No        | 1        | 1.39%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 60       | 83.33%  |
| Yes       | 12       | 16.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 70       | 97.22%  |
| Yes       | 2        | 2.78%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Brazil  | 72       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| SГЈo Paulo              | 12       | 15%     |
| Rio de Janeiro            | 7        | 8.75%   |
| SÃ£o Paulo              | 3        | 3.75%   |
| Curitiba                  | 3        | 3.75%   |
| RondonГіpolis           | 2        | 2.5%    |
| Rio Claro                 | 2        | 2.5%    |
| Porto Alegre              | 2        | 2.5%    |
| Pirapora                  | 2        | 2.5%    |
| BrasÃ­lia               | 2        | 2.5%    |
| VitГіria da Conquista   | 1        | 1.25%   |
| Urupes                    | 1        | 1.25%   |
| Unai                      | 1        | 1.25%   |
| Teresina                  | 1        | 1.25%   |
| SГЈo JosГ© dos Campos | 1        | 1.25%   |
| Serra                     | 1        | 1.25%   |
| Sao Vicente               | 1        | 1.25%   |
| Sao Paulo                 | 1        | 1.25%   |
| Reriutaba                 | 1        | 1.25%   |
| Piracicaba                | 1        | 1.25%   |
| Pelotas                   | 1        | 1.25%   |
| Patos de Minas            | 1        | 1.25%   |
| Pato Branco               | 1        | 1.25%   |
| Novo Horizonte do Norte   | 1        | 1.25%   |
| Novo Hamburgo             | 1        | 1.25%   |
| Morungaba                 | 1        | 1.25%   |
| Manaus                    | 1        | 1.25%   |
| Macatuba                  | 1        | 1.25%   |
| JundiaГ­                | 1        | 1.25%   |
| Juazeiro                  | 1        | 1.25%   |
| Juara                     | 1        | 1.25%   |
| JoГЈo Pessoa            | 1        | 1.25%   |
| Joinville                 | 1        | 1.25%   |
| JaraguГЎ do Sul         | 1        | 1.25%   |
| JaraguÃ¡ do Sul         | 1        | 1.25%   |
| JacareГ­                | 1        | 1.25%   |
| Jaboatao dos Guararapes   | 1        | 1.25%   |
| Itaocara                  | 1        | 1.25%   |
| ItajaГ­                 | 1        | 1.25%   |
| Inhapim                   | 1        | 1.25%   |
| IlhÃ©us                 | 1        | 1.25%   |
| Guarulhos                 | 1        | 1.25%   |
| Frederico Westphalen      | 1        | 1.25%   |
| Franca                    | 1        | 1.25%   |
| FlorianÃ³polis          | 1        | 1.25%   |
| Farroupilha               | 1        | 1.25%   |
| Cruzeiro do Sul           | 1        | 1.25%   |
| CriciÃºma               | 1        | 1.25%   |
| Campinas                  | 1        | 1.25%   |
| BrasГ­lia               | 1        | 1.25%   |
| Boa Vista do Jauato       | 1        | 1.25%   |
| Benevides                 | 1        | 1.25%   |
| Belo Horizonte            | 1        | 1.25%   |
| Belém                    | 1        | 1.25%   |
| Barracao                  | 1        | 1.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 21       | 28     | 21.65%  |
| Seagate             | 19       | 43     | 19.59%  |
| Kingston            | 17       | 24     | 17.53%  |
| Samsung Electronics | 11       | 12     | 11.34%  |
| SanDisk             | 5        | 5      | 5.15%   |
| Toshiba             | 4        | 4      | 4.12%   |
| Hoodisk             | 4        | 4      | 4.12%   |
| Hitachi             | 2        | 4      | 2.06%   |
| Crucial             | 2        | 3      | 2.06%   |
| China               | 2        | 4      | 2.06%   |
| A-DATA Technology   | 2        | 2      | 2.06%   |
| XrayDisk            | 1        | 1      | 1.03%   |
| Silicon Motion      | 1        | 1      | 1.03%   |
| NTC                 | 1        | 1      | 1.03%   |
| HGST                | 1        | 2      | 1.03%   |
| Hewlett-Packard     | 1        | 1      | 1.03%   |
| Gigabyte Technology | 1        | 1      | 1.03%   |
| faspeed             | 1        | 1      | 1.03%   |
| Drevo               | 1        | 3      | 1.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Kingston SA400S37120G 120GB         | 6        | 5.45%   |
| Kingston SA400S37240G 240GB         | 5        | 4.55%   |
| WDC WD10EZEX-00RKKA0 1TB            | 3        | 2.73%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3        | 2.73%   |
| Seagate ST500DM002-1BD142 500GB     | 3        | 2.73%   |
| Seagate ST4000DM000-1F2168 4TB      | 3        | 2.73%   |
| Seagate ST1000DM010-2EP102 1TB      | 3        | 2.73%   |
| Samsung HD322HJ 320GB               | 3        | 2.73%   |
| Seagate ST2000DM006-2DM164 2TB      | 2        | 1.82%   |
| SanDisk SDSSDA240G 240GB            | 2        | 1.82%   |
| Samsung HD502HJ 500GB               | 2        | 1.82%   |
| Samsung HD161HJ 160GB               | 2        | 1.82%   |
| Kingston SA400S37480G 480GB         | 2        | 1.82%   |
| Hoodisk SSD 64GB                    | 2        | 1.82%   |
| Hoodisk SSD 32GB                    | 2        | 1.82%   |
| A-DATA SU630 240GB                  | 2        | 1.82%   |
| XrayDisk SSD 128GB                  | 1        | 0.91%   |
| WDC WDS120G2G0A-00JH30 120GB        | 1        | 0.91%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1        | 0.91%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 1        | 0.91%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 1        | 0.91%   |
| WDC WD5000AAKS-08V0A0 500GB         | 1        | 0.91%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 1        | 0.91%   |
| WDC WD400BD-75LRA0 40GB             | 1        | 0.91%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1        | 0.91%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 1        | 0.91%   |
| WDC WD3200BEVT-00A0RT0 233GB        | 1        | 0.91%   |
| WDC WD3200AAKS-00UU3A0 320GB        | 1        | 0.91%   |
| WDC WD3200AAJS-56M0A0 320GB         | 1        | 0.91%   |
| WDC WD3200AAJS-00YZCA0 320GB        | 1        | 0.91%   |
| WDC WD2500AAKX-75U6AA0 250GB        | 1        | 0.91%   |
| WDC WD1600AVJS-63WNA0 160GB         | 1        | 0.91%   |
| WDC WD1200BEVT-22ZCT0 120GB         | 1        | 0.91%   |
| WDC WD10SPZX-21Z10T0 1TB            | 1        | 0.91%   |
| WDC WD10PURX-64E5EY0 1TB            | 1        | 0.91%   |
| WDC WD10JPVX-80JC3T0 1TB            | 1        | 0.91%   |
| WDC WD10EZEX-75WN4A1 1TB            | 1        | 0.91%   |
| WDC WD10EZEX-75WN4A0 1TB            | 1        | 0.91%   |
| WDC WD10EZEX-60WN4A0 1TB            | 1        | 0.91%   |
| Toshiba MQ01ABF050 500GB            | 1        | 0.91%   |
| Toshiba MQ01ABD050 500GB            | 1        | 0.91%   |
| Toshiba DT01ACA100 1TB              | 1        | 0.91%   |
| Toshiba DT01ACA050 LENOVO 500GB     | 1        | 0.91%   |
| Silicon Motion ShiJi 256GB M.2-NVMe | 1        | 0.91%   |
| Seagate ST9160314AS 160GB           | 1        | 0.91%   |
| Seagate ST500LM021-1KJ152 500GB     | 1        | 0.91%   |
| Seagate ST500DM002-1BC142 500GB     | 1        | 0.91%   |
| Seagate ST380817AS 80GB             | 1        | 0.91%   |
| Seagate ST3500312CS 500GB           | 1        | 0.91%   |
| Seagate ST3250310AS 250GB           | 1        | 0.91%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 1        | 0.91%   |
| Seagate ST3160813AS 160GB           | 1        | 0.91%   |
| Seagate ST2000DM001-1E6164 2TB      | 1        | 0.91%   |
| Seagate ST2000DL003-9VT166 2TB      | 1        | 0.91%   |
| Seagate ST1000VM002-1SD102 1TB      | 1        | 0.91%   |
| Seagate ST1000VM002-1ET162 1TB      | 1        | 0.91%   |
| Seagate ST1000DM003-1CH162 1TB      | 1        | 0.91%   |
| SanDisk SSD PLUS 240 GB             | 1        | 0.91%   |
| SanDisk SSD PLUS 120GB              | 1        | 0.91%   |
| SanDisk SDSSDA120G 120GB            | 1        | 0.91%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 27     | 35.71%  |
| Seagate             | 19       | 43     | 33.93%  |
| Samsung Electronics | 10       | 11     | 17.86%  |
| Toshiba             | 4        | 4      | 7.14%   |
| Hitachi             | 2        | 4      | 3.57%   |
| HGST                | 1        | 2      | 1.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 17       | 24     | 42.5%   |
| SanDisk             | 5        | 5      | 12.5%   |
| Hoodisk             | 4        | 4      | 10%     |
| Crucial             | 2        | 3      | 5%      |
| China               | 2        | 4      | 5%      |
| A-DATA Technology   | 2        | 2      | 5%      |
| XrayDisk            | 1        | 1      | 2.5%    |
| WDC                 | 1        | 1      | 2.5%    |
| Samsung Electronics | 1        | 1      | 2.5%    |
| NTC                 | 1        | 1      | 2.5%    |
| Hewlett-Packard     | 1        | 1      | 2.5%    |
| Gigabyte Technology | 1        | 1      | 2.5%    |
| faspeed             | 1        | 1      | 2.5%    |
| Drevo               | 1        | 3      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 45       | 91     | 54.88%  |
| SSD  | 36       | 52     | 43.9%   |
| NVMe | 1        | 1      | 1.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 68       | 143    | 98.55%  |
| NVMe | 1        | 1      | 1.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 62       | 99     | 76.54%  |
| 0.51-1.0   | 12       | 24     | 14.81%  |
| 1.01-2.0   | 4        | 12     | 4.94%   |
| 3.01-4.0   | 3        | 8      | 3.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 20       | 25.32%  |
| 1-20           | 16       | 20.25%  |
| 251-500        | 15       | 18.99%  |
| 51-100         | 11       | 13.92%  |
| 21-50          | 9        | 11.39%  |
| 501-1000       | 5        | 6.33%   |
| More than 3000 | 1        | 1.27%   |
| 2001-3000      | 1        | 1.27%   |
| 1001-2000      | 1        | 1.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 62       | 86.11%  |
| 21-50     | 5        | 6.94%   |
| 101-250   | 3        | 4.17%   |
| 2001-3000 | 1        | 1.39%   |
| 501-1000  | 1        | 1.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Samsung Electronics HD322HJ 320GB   | 3        | 3      | 9.38%   |
| WDC WD10EZEX-00RKKA0 1TB            | 2        | 2      | 6.25%   |
| Samsung Electronics HD161HJ 160GB   | 2        | 2      | 6.25%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1        | 1      | 3.13%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 1        | 1      | 3.13%   |
| WDC WD5000AAKS-08V0A0 500GB         | 1        | 1      | 3.13%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 1        | 1      | 3.13%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1        | 1      | 3.13%   |
| WDC WD3200BEVT-00A0RT0 233GB        | 1        | 1      | 3.13%   |
| WDC WD3200AAKS-00UU3A0 320GB        | 1        | 1      | 3.13%   |
| WDC WD3200AAJS-56M0A0 320GB         | 1        | 1      | 3.13%   |
| WDC WD10PURX-64E5EY0 1TB            | 1        | 1      | 3.13%   |
| Toshiba MQ01ABD050 500GB            | 1        | 1      | 3.13%   |
| Seagate ST9160314AS 160GB           | 1        | 1      | 3.13%   |
| Seagate ST500LM021-1KJ152 500GB     | 1        | 1      | 3.13%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1        | 1      | 3.13%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 3.13%   |
| Seagate ST500DM002-1BC142 500GB     | 1        | 1      | 3.13%   |
| Seagate ST3250310AS 250GB           | 1        | 1      | 3.13%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 1        | 1      | 3.13%   |
| Seagate ST2000DM006-2DM164 2TB      | 1        | 1      | 3.13%   |
| Seagate ST2000DM001-1E6164 2TB      | 1        | 1      | 3.13%   |
| Seagate ST2000DL003-9VT166 2TB      | 1        | 9      | 3.13%   |
| SanDisk SSD PLUS 240 GB             | 1        | 1      | 3.13%   |
| Samsung Electronics HD642JJ 640GB   | 1        | 1      | 3.13%   |
| Samsung Electronics HD502HJ 500GB   | 1        | 1      | 3.13%   |
| Hitachi HTS541680J9SA00 80GB        | 1        | 2      | 3.13%   |
| Hitachi HTS541612J9SA00 120GB       | 1        | 2      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 18     | 34.48%  |
| WDC                 | 9        | 11     | 31.03%  |
| Samsung Electronics | 6        | 7      | 20.69%  |
| Hitachi             | 2        | 4      | 6.9%    |
| Toshiba             | 1        | 1      | 3.45%   |
| SanDisk             | 1        | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 18     | 35.71%  |
| WDC                 | 9        | 11     | 32.14%  |
| Samsung Electronics | 6        | 7      | 21.43%  |
| Hitachi             | 2        | 4      | 7.14%   |
| Toshiba             | 1        | 1      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 25       | 41     | 96.15%  |
| SSD  | 1        | 1      | 3.85%   |

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
| Works    | 52       | 95     | 62.65%  |
| Malfunc  | 26       | 42     | 31.33%  |
| Detected | 4        | 6      | 4.82%   |
| Failed   | 1        | 1      | 1.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 55       | 73.33%  |
| AMD                           | 14       | 18.67%  |
| Silicon Motion                | 2        | 2.67%   |
| Nvidia                        | 1        | 1.33%   |
| Integrated Technology Express | 1        | 1.33%   |
| Hewlett-Packard               | 1        | 1.33%   |
| Adaptec                       | 1        | 1.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 13       | 13.27%  |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 8        | 8.16%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5        | 5.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 5.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 5.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 5.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 5.1%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 5.1%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 5        | 5.1%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 3.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 3.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3        | 3.06%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 2.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2        | 2.04%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 2.04%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 2.04%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 2.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 2.04%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 2.04%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 1.02%   |
| Nvidia MCP61 IDE                                                                        | 1        | 1.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 1.02%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1        | 1.02%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.02%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 1.02%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.02%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 1        | 1.02%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 1.02%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 1        | 1.02%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 1.02%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 1.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 1        | 1.02%   |
| Integrated Express IT8213 IDE Controller                                                | 1        | 1.02%   |
| HP Smart Array G6 controllers                                                           | 1        | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [Non-RAID5 mode]                                  | 1        | 1.02%   |
| AMD FCH SATA Controller D                                                               | 1        | 1.02%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 1.02%   |
| Adaptec AIC-7870P/7881U [AHA-2940U/UW/D/S76]                                            | 1        | 1.02%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 43       | 55.13%  |
| IDE  | 28       | 35.9%   |
| RAID | 4        | 5.13%   |
| NVMe | 2        | 2.56%   |
| SCSI | 1        | 1.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 57       | 79.17%  |
| AMD    | 15       | 20.83%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Celeron CPU J1800 @ 2.41GHz             | 4        | 5.56%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2        | 2.78%   |
| Intel Core i3-3240 CPU @ 3.40GHz              | 2        | 2.78%   |
| Intel Core i3-2100 CPU                        | 2        | 2.78%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2        | 2.78%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 2        | 2.78%   |
| AMD FX-8320E Eight-Core Processor             | 2        | 2.78%   |
| Intel Xeon CPU X5680 @ 3.33GHz                | 1        | 1.39%   |
| Intel Xeon CPU E5506 @ 2.13GHz                | 1        | 1.39%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz            | 1        | 1.39%   |
| Intel Xeon CPU E5-2630L v3 @ 1.80GHz          | 1        | 1.39%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz           | 1        | 1.39%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz           | 1        | 1.39%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz   | 1        | 1.39%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 1        | 1.39%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz   | 1        | 1.39%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 1        | 1.39%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 1        | 1.39%   |
| Intel Pentium CPU G2020T @ 2.50GHz            | 1        | 1.39%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1        | 1.39%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 1        | 1.39%   |
| Intel Core i7-4770K CPU @ 3.50GHz             | 1        | 1.39%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1        | 1.39%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 1        | 1.39%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 1        | 1.39%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 1        | 1.39%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1        | 1.39%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 1        | 1.39%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 1        | 1.39%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 1        | 1.39%   |
| Intel Core i3-5020U CPU @ 2.20GHz             | 1        | 1.39%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1        | 1.39%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 1        | 1.39%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1        | 1.39%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 1        | 1.39%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 1        | 1.39%   |
| Intel Core i3-2120 CPU @ 3.30GH               | 1        | 1.39%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 1        | 1.39%   |
| Intel Core i3 CPU 550 @ 3.20GHz               | 1        | 1.39%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz         | 1        | 1.39%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 1        | 1.39%   |
| Intel Core 2 Duo CPU                          | 1        | 1.39%   |
| Intel Core 2 Duo                              | 1        | 1.39%   |
| Intel Core 2 CPU 6600 @ 2.40GHz               | 1        | 1.39%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1        | 1.39%   |
| Intel Celeron CPU E3400 @ 2.60GHz             | 1        | 1.39%   |
| Intel Celeron CPU 847 @ 1.10GHz               | 1        | 1.39%   |
| Intel Celeron CPU 450 @ 2.20GHz               | 1        | 1.39%   |
| Intel Atom CPU N270 @ 1.60GH                  | 1        | 1.39%   |
| Intel Atom CPU E3845 @ 1.91GHz                | 1        | 1.39%   |
| AMD Turion II Neo N40L Dual-Core Processor    | 1        | 1.39%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1        | 1.39%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 1        | 1.39%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 1        | 1.39%   |
| AMD Ryzen 5 1500X Quad-Core Processor         | 1        | 1.39%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 1        | 1.39%   |
| AMD PRO A8-8650B R7, 10 Compute Cores 4C+6G   | 1        | 1.39%   |
| AMD Phenom 9650 Quad-Core Processor           | 1        | 1.39%   |
| AMD FX-8320 Eight-Core Processor              | 1        | 1.39%   |
| AMD FX-8300 Eight-Core Processor              | 1        | 1.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i3           | 16       | 22.22%  |
| Intel Celeron           | 8        | 11.11%  |
| Intel Core i5           | 7        | 9.72%   |
| Intel Xeon              | 6        | 8.33%   |
| Intel Core 2 Duo        | 6        | 8.33%   |
| AMD FX                  | 6        | 8.33%   |
| Intel Pentium Dual-Core | 5        | 6.94%   |
| AMD Ryzen 5             | 4        | 5.56%   |
| Intel Core i7           | 3        | 4.17%   |
| Intel Core 2 Quad       | 2        | 2.78%   |
| Intel Atom              | 2        | 2.78%   |
| Intel Pentium           | 1        | 1.39%   |
| Intel Core 2            | 1        | 1.39%   |
| AMD Turion II Neo       | 1        | 1.39%   |
| AMD Ryzen 3             | 1        | 1.39%   |
| AMD PRO A8              | 1        | 1.39%   |
| AMD Phenom              | 1        | 1.39%   |
| AMD E                   | 1        | 1.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 36       | 50%     |
| 4       | 16       | 22.22%  |
| 8       | 8        | 11.11%  |
| 6       | 5        | 6.94%   |
| 12      | 3        | 4.17%   |
| Unknown | 3        | 4.17%   |
| 1       | 1        | 1.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 71       | 98.61%  |
| 2      | 1        | 1.39%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 45       | 62.5%   |
| 2       | 24       | 33.33%  |
| Unknown | 3        | 4.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 12       | 16.67%  |
| Haswell     | 10       | 13.89%  |
| SandyBridge | 8        | 11.11%  |
| Silvermont  | 5        | 6.94%   |
| Piledriver  | 5        | 6.94%   |
| KabyLake    | 5        | 6.94%   |
| IvyBridge   | 5        | 6.94%   |
| Zen+        | 4        | 5.56%   |
| Westmere    | 3        | 4.17%   |
| Core        | 3        | 4.17%   |
| K10         | 2        | 2.78%   |
| Broadwell   | 2        | 2.78%   |
| Zen         | 1        | 1.39%   |
| Steamroller | 1        | 1.39%   |
| Nehalem     | 1        | 1.39%   |
| Goldmont    | 1        | 1.39%   |
| Bulldozer   | 1        | 1.39%   |
| Bonnell     | 1        | 1.39%   |
| Bobcat      | 1        | 1.39%   |
| Unknown     | 1        | 1.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 44       | 59.46%  |
| AMD                        | 16       | 21.62%  |
| Nvidia                     | 11       | 14.86%  |
| Matrox Electronics Systems | 2        | 2.7%    |
| ASPEED Technology          | 1        | 1.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                         | 8        | 10.67%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 7        | 9.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 5        | 6.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 4        | 5.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3        | 4%      |
| Intel 82G33/G31 Express Integrated Graphics Controller                        | 3        | 4%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 3        | 4%      |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 2        | 2.67%   |
| Nvidia GK208B [GeForce GT 710]                                                | 2        | 2.67%   |
| Matrox Electronics Systems MGA G200EH                                         | 2        | 2.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 2        | 2.67%   |
| Intel HD Graphics 630                                                         | 2        | 2.67%   |
| Intel HD Graphics 5500                                                        | 2        | 2.67%   |
| Intel Core Processor Integrated Graphics Controller                           | 2        | 2.67%   |
| AMD RV710 [Radeon HD 4350/4550]                                               | 2        | 2.67%   |
| AMD RS780L [Radeon 3000]                                                      | 2        | 2.67%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                    | 2        | 2.67%   |
| Nvidia GT218 [GeForce 210]                                                    | 1        | 1.33%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                           | 1        | 1.33%   |
| Nvidia GK107GL [Quadro K2000]                                                 | 1        | 1.33%   |
| Nvidia GF119 [GeForce GT 610]                                                 | 1        | 1.33%   |
| Nvidia GF108 [GeForce GT 430]                                                 | 1        | 1.33%   |
| Nvidia GF106 [GeForce GTS 450]                                                | 1        | 1.33%   |
| Nvidia G86 [GeForce 8500 GT]                                                  | 1        | 1.33%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1        | 1.33%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1        | 1.33%   |
| Intel HD Graphics 500                                                         | 1        | 1.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 1        | 1.33%   |
| Intel 82Q33 Express Integrated Graphics Controller                            | 1        | 1.33%   |
| Intel 82945G/GZ Integrated Graphics Controller                                | 1        | 1.33%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller     | 1        | 1.33%   |
| ASPEED Technology ASPEED Graphics Family                                      | 1        | 1.33%   |
| AMD Wrestler [Radeon HD 6310]                                                 | 1        | 1.33%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                     | 1        | 1.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1        | 1.33%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]         | 1        | 1.33%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                | 1        | 1.33%   |
| AMD Kaveri [Radeon R7 Graphics]                                               | 1        | 1.33%   |
| AMD ES1000                                                                    | 1        | 1.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Intel   | 40       | 54.79%  |
| 1 x AMD     | 15       | 20.55%  |
| 1 x Nvidia  | 11       | 15.07%  |
| 2 x Intel   | 3        | 4.11%   |
| 1 x Matrox  | 2        | 2.74%   |
| Intel + AMD | 1        | 1.37%   |
| 1 x ASPEED  | 1        | 1.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 65       | 89.04%  |
| Proprietary | 8        | 10.96%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 56       | 74.67%  |
| 3.01-4.0   | 6        | 8%      |
| 1.01-2.0   | 4        | 5.33%   |
| 0.51-1.0   | 4        | 5.33%   |
| 0.01-0.5   | 3        | 4%      |
| 7.01-8.0   | 1        | 1.33%   |
| 2.01-3.0   | 1        | 1.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Goldstar            | 11       | 39.29%  |
| Samsung Electronics | 9        | 32.14%  |
| VIE                 | 1        | 3.57%   |
| Philips             | 1        | 3.57%   |
| Panasonic           | 1        | 3.57%   |
| LG Electronics      | 1        | 3.57%   |
| Lenovo              | 1        | 3.57%   |
| Hewlett-Packard     | 1        | 3.57%   |
| ASUSTek Computer    | 1        | 3.57%   |
| AOC                 | 1        | 3.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| VIE E195 VIE1950 1600x900 410x280mm 19.5-inch                        | 1        | 3.23%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch | 1        | 3.23%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                      | 1        | 3.23%   |
| Samsung Electronics SyncMaster SAM0600 1600x900 440x250mm 19.9-inch  | 1        | 3.23%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch  | 1        | 3.23%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                     | 1        | 3.23%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x260mm 19.1-inch  | 1        | 3.23%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 340x190mm 15.3-inch  | 1        | 3.23%   |
| Samsung Electronics SyncMaster SAM0117 1280x1024 310x230mm 15.2-inch | 1        | 3.23%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 280x210mm 13.8-inch  | 1        | 3.23%   |
| Samsung Electronics S19B300 SAM08A6 1366x768 410x230mm 18.5-inch     | 1        | 3.23%   |
| Samsung Electronics LCD Monitor SMT27A550 1920x1080                  | 1        | 3.23%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch              | 1        | 3.23%   |
| Panasonic TV MEIC136 1280x720 698x392mm 31.5-inch                    | 1        | 3.23%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 3640x1920                    | 1        | 3.23%   |
| LG Electronics LCD Monitor 23MP55                                    | 1        | 3.23%   |
| Lenovo LEN T22i-10 LEN61A9 1920x1080 480x270mm 21.7-inch             | 1        | 3.23%   |
| Hewlett-Packard E233 HPN345F 1920x1080 510x290mm 23.1-inch           | 1        | 3.23%   |
| Goldstar W2043 GSM4E9D 1600x900 450x250mm 20.3-inch                  | 1        | 3.23%   |
| Goldstar W1952 GSM4B78 1440x900 410x260mm 19.1-inch                  | 1        | 3.23%   |
| Goldstar W1942 GSM4B6F 1440x900 410x260mm 19.1-inch                  | 1        | 3.23%   |
| Goldstar LCD Monitor GSM5AB7 1920x1080 480x270mm 21.7-inch           | 1        | 3.23%   |
| Goldstar L1950H GSM4AA2 1280x1024 380x300mm 19.1-inch                | 1        | 3.23%   |
| Goldstar L1753T GSM4433 1280x1024 340x270mm 17.1-inch                | 1        | 3.23%   |
| Goldstar L1553S GSM3BB0 1024x768 300x230mm 14.9-inch                 | 1        | 3.23%   |
| Goldstar E2241 GSM581A 1920x1080 480x270mm 21.7-inch                 | 1        | 3.23%   |
| Goldstar D2342P GSM5840 1920x1080 510x290mm 23.1-inch                | 1        | 3.23%   |
| Goldstar 23EA53 GSM59A8 1920x1080 510x290mm 23.1-inch                | 1        | 3.23%   |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                | 1        | 3.23%   |
| ASUSTek Computer VG248 AUS24C2 1920x1080 530x300mm 24.0-inch         | 1        | 3.23%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 1        | 3.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 12       | 40%     |
| 1600x900 (HD+)   | 4        | 13.33%  |
| 1440x900 (WXGA+) | 3        | 10%     |
| 1280x1024 (SXGA) | 3        | 10%     |
| 1366x768 (WXGA)  | 2        | 6.67%   |
| 1024x768 (XGA)   | 2        | 6.67%   |
| 3640x1920        | 1        | 3.33%   |
| 1360x768         | 1        | 3.33%   |
| 1280x720 (HD)    | 1        | 3.33%   |
| Unknown          | 1        | 3.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 19      | 6        | 20.69%  |
| 23      | 5        | 17.24%  |
| 21      | 4        | 13.79%  |
| Unknown | 4        | 13.79%  |
| 18      | 2        | 6.9%    |
| 15      | 2        | 6.9%    |
| 31      | 1        | 3.45%   |
| 24      | 1        | 3.45%   |
| 20      | 1        | 3.45%   |
| 17      | 1        | 3.45%   |
| 14      | 1        | 3.45%   |
| 13      | 1        | 3.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 11       | 39.29%  |
| 501-600     | 6        | 21.43%  |
| Unknown     | 4        | 14.29%  |
| 301-350     | 3        | 10.71%  |
| 201-300     | 2        | 7.14%   |
| 601-700     | 1        | 3.57%   |
| 351-400     | 1        | 3.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 17       | 60.71%  |
| 4/3     | 3        | 10.71%  |
| 16/10   | 3        | 10.71%  |
| 5/4     | 2        | 7.14%   |
| Unknown | 2        | 7.14%   |
| 3/2     | 1        | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 10       | 34.48%  |
| 151-200        | 7        | 24.14%  |
| Unknown        | 4        | 13.79%  |
| 141-150        | 3        | 10.34%  |
| 91-100         | 2        | 6.9%    |
| 351-500        | 1        | 3.45%   |
| 111-120        | 1        | 3.45%   |
| 101-110        | 1        | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 18       | 62.07%  |
| 101-120 | 6        | 20.69%  |
| Unknown | 4        | 13.79%  |
| 1-50    | 1        | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 44       | 60.27%  |
| 1     | 26       | 35.62%  |
| 2     | 3        | 4.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 48       | 48.98%  |
| Intel                 | 24       | 24.49%  |
| Qualcomm Atheros      | 7        | 7.14%   |
| Broadcom              | 7        | 7.14%   |
| Ralink                | 4        | 4.08%   |
| TP-Link               | 1        | 1.02%   |
| Samsung Electronics   | 1        | 1.02%   |
| Ralink Technology     | 1        | 1.02%   |
| MediaTek              | 1        | 1.02%   |
| ICS Advent            | 1        | 1.02%   |
| D-Link System         | 1        | 1.02%   |
| Arduino SA            | 1        | 1.02%   |
| 3Com                  | 1        | 1.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 41       | 37.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 6        | 5.56%   |
| Intel I211 Gigabit Network Connection                                | 5        | 4.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 3        | 2.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 3        | 2.78%   |
| Intel 82576 Gigabit Network Connection                               | 3        | 2.78%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 2        | 1.85%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 2        | 1.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 2        | 1.85%   |
| Intel Ethernet Connection (2) I218-V                                 | 2        | 1.85%   |
| Intel 82583V Gigabit Network Connection                              | 2        | 1.85%   |
| Intel 82574L Gigabit Network Connection                              | 2        | 1.85%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                     | 2        | 1.85%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1        | 0.93%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)          | 1        | 0.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1        | 0.93%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 0.93%   |
| Realtek RTL8187SE Wireless LAN Controller                            | 1        | 0.93%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                      | 1        | 0.93%   |
| Ralink RT5370 Wireless Adapter                                       | 1        | 0.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1        | 0.93%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                           | 1        | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 0.93%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                        | 1        | 0.93%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 1        | 0.93%   |
| MediaTek USB Ethernet-RNDIS                                          | 1        | 0.93%   |
| Intel Wireless 7265                                                  | 1        | 0.93%   |
| Intel I350 Gigabit Network Connection                                | 1        | 0.93%   |
| Intel Ethernet Connection I217-LM                                    | 1        | 0.93%   |
| Intel Ethernet Connection (7) I219-LM                                | 1        | 0.93%   |
| Intel Ethernet Connection (2) I219-V                                 | 1        | 0.93%   |
| Intel 82579V Gigabit Network Connection                              | 1        | 0.93%   |
| Intel 82578DC Gigabit Network Connection                             | 1        | 0.93%   |
| Intel 82575GB Gigabit Network Connection                             | 1        | 0.93%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)           | 1        | 0.93%   |
| Intel 82566DM-2 Gigabit Network Connection                           | 1        | 0.93%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                 | 1        | 0.93%   |
| ICS Advent DM9601 Fast Ethernet Adapter                              | 1        | 0.93%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 1        | 0.93%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                       | 1        | 0.93%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                     | 1        | 0.93%   |
| Broadcom NetXtreme BCM5715 Gigabit Ethernet                          | 1        | 0.93%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                      | 1        | 0.93%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                      | 1        | 0.93%   |
| Arduino SA Uno R3 (CDC ACM)                                          | 1        | 0.93%   |
| 3Com 3c905 100BaseTX [Boomerang]                                     | 1        | 0.93%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 6        | 37.5%   |
| Ralink                | 4        | 25%     |
| Qualcomm Atheros      | 2        | 12.5%   |
| TP-Link               | 1        | 6.25%   |
| Ralink Technology     | 1        | 6.25%   |
| Intel                 | 1        | 6.25%   |
| D-Link System         | 1        | 6.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 3        | 18.75%  |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 2        | 12.5%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 2        | 12.5%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1        | 6.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1        | 6.25%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 6.25%   |
| Realtek RTL8187SE Wireless LAN Controller                            | 1        | 6.25%   |
| Ralink RT5370 Wireless Adapter                                       | 1        | 6.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1        | 6.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 6.25%   |
| Intel Wireless 7265                                                  | 1        | 6.25%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 1        | 6.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 48       | 54.55%  |
| Intel                 | 24       | 27.27%  |
| Broadcom              | 7        | 7.95%   |
| Qualcomm Atheros      | 5        | 5.68%   |
| Samsung Electronics   | 1        | 1.14%   |
| MediaTek              | 1        | 1.14%   |
| ICS Advent            | 1        | 1.14%   |
| 3Com                  | 1        | 1.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41       | 45.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6        | 6.59%   |
| Intel I211 Gigabit Network Connection                             | 5        | 5.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 3.3%    |
| Intel 82576 Gigabit Network Connection                            | 3        | 3.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 2.2%    |
| Intel Ethernet Connection (2) I218-V                              | 2        | 2.2%    |
| Intel 82583V Gigabit Network Connection                           | 2        | 2.2%    |
| Intel 82574L Gigabit Network Connection                           | 2        | 2.2%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2        | 2.2%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 1.1%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.1%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 1.1%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 1.1%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 1.1%    |
| MediaTek USB Ethernet-RNDIS                                       | 1        | 1.1%    |
| Intel I350 Gigabit Network Connection                             | 1        | 1.1%    |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.1%    |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.1%    |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.1%    |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.1%    |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.1%    |
| Intel 82575GB Gigabit Network Connection                          | 1        | 1.1%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 1.1%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.1%    |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 1.1%    |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1        | 1.1%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1        | 1.1%    |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 1        | 1.1%    |
| Broadcom NetXtreme BCM5715 Gigabit Ethernet                       | 1        | 1.1%    |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 1.1%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 1.1%    |
| 3Com 3c905 100BaseTX [Boomerang]                                  | 1        | 1.1%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 71       | 84.52%  |
| WiFi     | 12       | 14.29%  |
| Modem    | 1        | 1.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 70       | 87.5%   |
| WiFi     | 10       | 12.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 25       | 34.72%  |
| 1     | 25       | 34.72%  |
| 4     | 9        | 12.5%   |
| 3     | 9        | 12.5%   |
| 6     | 2        | 2.78%   |
| 5     | 2        | 2.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 68       | 90.67%  |
| Yes  | 7        | 9.33%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 1        | 50%     |
| Intel                 | 1        | 50%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Realtek  Bluetooth Adapter         | 1        | 50%     |
| Intel Bluetooth wireless interface | 1        | 50%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 44       | 56.41%  |
| AMD                                             | 18       | 23.08%  |
| Nvidia                                          | 11       | 14.1%   |
| C-Media Electronics                             | 3        | 3.85%   |
| Licensed by Sony Computer Entertainment America | 1        | 1.28%   |
| Generalplus Technology                          | 1        | 1.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 12       | 13.04%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6        | 6.52%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 6.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4        | 4.35%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3        | 3.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3        | 3.26%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 3.26%   |
| Intel 8 Series HD Audio Controller                                         | 3        | 3.26%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 3.26%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 3.26%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 3.26%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 2.17%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 2.17%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2        | 2.17%   |
| Intel Broadwell-U Audio Controller                                         | 2        | 2.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 2.17%   |
| C-Media Electronics CM108 Audio Controller                                 | 2        | 2.17%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2        | 2.17%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 2.17%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 2.17%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 2.17%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.09%   |
| Nvidia High Definition Audio Controller                                    | 1        | 1.09%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 1.09%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 1.09%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia GF106 High Definition Audio Controller                              | 1        | 1.09%   |
| Licensed by Sony Computer Entertainment America Wireless Stereo Headset    | 1        | 1.09%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1        | 1.09%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.09%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 1.09%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 1.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 1.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 1.09%   |
| Generalplus Technology USB Audio Device                                    | 1        | 1.09%   |
| C-Media Electronics Audio Adapter                                          | 1        | 1.09%   |
| AMD Wrestler HDMI Audio                                                    | 1        | 1.09%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1        | 1.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 1.09%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1        | 1.09%   |
| AMD FCH Azalia Controller                                                  | 1        | 1.09%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 27       | 36.49%  |
| Kingston            | 16       | 21.62%  |
| Smart               | 5        | 6.76%   |
| Crucial             | 4        | 5.41%   |
| Micron Technology   | 3        | 4.05%   |
| Teikon              | 2        | 2.7%    |
| Hewlett-Packard     | 2        | 2.7%    |
| Unknown             | 2        | 2.7%    |
| Tigo                | 1        | 1.35%   |
| SK Hynix            | 1        | 1.35%   |
| Samsung Electronics | 1        | 1.35%   |
| RZX                 | 1        | 1.35%   |
| PUSKILL             | 1        | 1.35%   |
| Nanya Technology    | 1        | 1.35%   |
| Multilaser          | 1        | 1.35%   |
| Kreton              | 1        | 1.35%   |
| G.Skill             | 1        | 1.35%   |
| CSX                 | 1        | 1.35%   |
| Corsair             | 1        | 1.35%   |
| Apacer              | 1        | 1.35%   |
| A-DATA Technology   | 1        | 1.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                        | 4        | 4.88%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 2        | 2.44%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 2        | 2.44%   |
| Unknown RAM Module 2GB DIMM DDR2                         | 2        | 2.44%   |
| Unknown RAM Module 2GB DIMM                              | 2        | 2.44%   |
| Unknown                                                  | 2        | 2.44%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                     | 1        | 1.22%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s             | 1        | 1.22%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s             | 1        | 1.22%   |
| Unknown RAM Module 4GB DIMM SDRAM                        | 1        | 1.22%   |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s                 | 1        | 1.22%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 1.22%   |
| Unknown RAM Module 4GB DIMM 400MT/s                      | 1        | 1.22%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                     | 1        | 1.22%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 1.22%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s             | 1        | 1.22%   |
| Unknown RAM Module 4096MB DIMM DDR2                      | 1        | 1.22%   |
| Unknown RAM Module 2GB DIMM SDRAM 1333MT/s               | 1        | 1.22%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 1.22%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                     | 1        | 1.22%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 1        | 1.22%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 1.22%   |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s             | 1        | 1.22%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 1.22%   |
| Unknown RAM Module 2048MB DIMM DDR2                      | 1        | 1.22%   |
| Unknown RAM Module 1GB DIMM SDRAM                        | 1        | 1.22%   |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 1        | 1.22%   |
| Tigo RAM 1600Mhz-8G 8GB SODIMM DDR3 1600MT/s             | 1        | 1.22%   |
| Teikon RAM TMTS8G58DFRBFHC-16 8GB SODIMM DDR3 1600MT/s   | 1        | 1.22%   |
| Teikon RAM TMT41GU6BFR8C-PBHJ 8GB DIMM DDR3 1600MT/s     | 1        | 1.22%   |
| Smart RAM SH564568FH8NZQNSCR 2GB DIMM DDR3 1600MT/s      | 1        | 1.22%   |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s      | 1        | 1.22%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s      | 1        | 1.22%   |
| Smart RAM SG564568FG8N6KF-Z1 2GB DIMM DDR2 800MT/s       | 1        | 1.22%   |
| SMART RAM Module 8GB DIMM DDR4 2667MT/s                  | 1        | 1.22%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 1        | 1.22%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 1.22%   |
| RZX RAM D3D9M1333G/4G 4GB DIMM DDR3 1333MT/s             | 1        | 1.22%   |
| PUSKILL RAM DDR3 1600 8G 8GB SODIMM DDR3 1600MT/s        | 1        | 1.22%   |
| Nanya RAM NT4GC72B8PB0NF-CG 4GB DIMM DDR3 1333MT/s       | 1        | 1.22%   |
| Multilaser RAM MS3512NSZ-CA3G1 4GB DIMM DDR3 1600MT/s    | 1        | 1.22%   |
| Micron RAM Module 16GB SODIMM DDR4 2667MT/s              | 1        | 1.22%   |
| Micron RAM 36JSF1G72PZ-1 8GB DIMM DDR3 1600MT/s          | 1        | 1.22%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s     | 1        | 1.22%   |
| Kreton RAM 51624xxxx68x45xxxx 2GB DIMM DDR2 800MT/s      | 1        | 1.22%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 2400MT/s      | 1        | 1.22%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2133MT/s        | 1        | 1.22%   |
| Kingston RAM KHX1600C10D3/ 8GB DIMM DDR3 1600MT/s        | 1        | 1.22%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 2400MT/s    | 1        | 1.22%   |
| Kingston RAM 99U5584-010.A00LF 4096MB DIMM DDR3 1866MT/s | 1        | 1.22%   |
| Kingston RAM 99U5474-038.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 1.22%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 1.22%   |
| Kingston RAM 99U5471-057.A00LF 8GB DIMM DDR3 1333MT/s    | 1        | 1.22%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s    | 1        | 1.22%   |
| Kingston RAM 99U5471-047.A00LF 8GB DIMM DDR3 1333MT/s    | 1        | 1.22%   |
| Kingston RAM 99U5471-025.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 1.22%   |
| Kingston RAM 99U5469-045.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 1.22%   |
| Kingston RAM 9905713-030.A00G 8GB DIMM DDR4 2666MT/s     | 1        | 1.22%   |
| Kingston RAM 9905665-020.A00G 4GB DIMM DDR4 2667MT/s     | 1        | 1.22%   |
| Kingston RAM 9905584-023.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 1.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 36       | 54.55%  |
| DDR4    | 10       | 15.15%  |
| SDRAM   | 8        | 12.12%  |
| Unknown | 7        | 10.61%  |
| DDR2    | 5        | 7.58%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 60       | 90.91%  |
| SODIMM | 6        | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 28       | 38.36%  |
| 2048  | 21       | 28.77%  |
| 8192  | 18       | 24.66%  |
| 16384 | 4        | 5.48%   |
| 1024  | 2        | 2.74%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 19       | 27.54%  |
| 1333    | 19       | 27.54%  |
| Unknown | 12       | 17.39%  |
| 800     | 4        | 5.8%    |
| 2667    | 3        | 4.35%   |
| 2400    | 3        | 4.35%   |
| 2666    | 2        | 2.9%    |
| 2133    | 2        | 2.9%    |
| 1867    | 1        | 1.45%   |
| 1866    | 1        | 1.45%   |
| 1067    | 1        | 1.45%   |
| 1066    | 1        | 1.45%   |
| 400     | 1        | 1.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Logitech        | 1        | 50%     |
| Aveo Technology | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| Logitech Webcam C270 | 1        | 50%     |
| Aveo USB2.0 Camera   | 1        | 50%     |

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
| 0     | 39       | 54.17%  |
| 1     | 29       | 40.28%  |
| 2     | 3        | 4.17%   |
| 3     | 1        | 1.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 28       | 77.78%  |
| Net/wireless             | 4        | 11.11%  |
| Sound                    | 3        | 8.33%   |
| Firewire controller      | 1        | 2.78%   |

