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

Total: 123

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Positivo      | POS-PIQ77CL POSITIVO        | [848361c724](https://bsd-hardware.info/?probe=848361c724) | May 31, 2022 |
| Dell          | 0D28YY A00                  | [8f25636c51](https://bsd-hardware.info/?probe=8f25636c51) | May 19, 2022 |
| CNCTION-IA... | Unknown                     | [d6602975d3](https://bsd-hardware.info/?probe=d6602975d3) | May 16, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | [8675ff74d8](https://bsd-hardware.info/?probe=8675ff74d8) | May 09, 2022 |
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
| ASUSTek       | PRIME H310M-K R2.0          | [0a1be200c6](https://bsd-hardware.info/?probe=0a1be200c6) | Aug 29, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [a129f532bd](https://bsd-hardware.info/?probe=a129f532bd) | Aug 28, 2021 |
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
| OPNsense 20.7.8      | 6        | 6.45%   |
| helloSystem 0.7.0    | 6        | 6.45%   |
| OPNsense 21.1.3      | 5        | 5.38%   |
| OPNsense 21.1        | 5        | 5.38%   |
| helloSystem 0.4.0    | 5        | 5.38%   |
| OPNsense 21.1.1      | 4        | 4.3%    |
| helloSystem 0.6.0    | 4        | 4.3%    |
| helloSystem 0.5.0    | 4        | 4.3%    |
| OPNsense 21.7.7      | 3        | 3.23%   |
| OPNsense 21.7.1      | 3        | 3.23%   |
| OPNsense 21.1.9      | 3        | 3.23%   |
| OPNsense 21.1.6      | 3        | 3.23%   |
| OPNsense 21.1.4      | 3        | 3.23%   |
| FreeBSD 14.0-CURRENT | 3        | 3.23%   |
| OPNsense 22.1.7      | 2        | 2.15%   |
| OPNsense 22.1        | 2        | 2.15%   |
| OPNsense 21.1.7      | 2        | 2.15%   |
| OPNsense 21.1.2      | 2        | 2.15%   |
| NomadBSD 5806f915    | 2        | 2.15%   |
| FreeBSD 13.0-p7      | 2        | 2.15%   |
| FreeBSD 13.0         | 2        | 2.15%   |
| TrueNAS 12.2-p9      | 1        | 1.08%   |
| pfSense 2.4.5        | 1        | 1.08%   |
| OPNsense 22.1.6      | 1        | 1.08%   |
| OPNsense 22.1.3      | 1        | 1.08%   |
| OPNsense 22.1.2      | 1        | 1.08%   |
| OPNsense 21.7.3      | 1        | 1.08%   |
| OPNsense 21.7.2      | 1        | 1.08%   |
| OPNsense 21.7        | 1        | 1.08%   |
| OPNsense 21.1.8      | 1        | 1.08%   |
| OpenBSD 6.8          | 1        | 1.08%   |
| NetBSD 9.2           | 1        | 1.08%   |
| FreeNAS 11.3-p9      | 1        | 1.08%   |
| FreeNAS 11.3-p11     | 1        | 1.08%   |
| FreeBSD 13.0-p4      | 1        | 1.08%   |
| FreeBSD 13.0-p3      | 1        | 1.08%   |
| FreeBSD 13.0-CURRENT | 1        | 1.08%   |
| FreeBSD 12.2-p3      | 1        | 1.08%   |
| FreeBSD 12.2-p1      | 1        | 1.08%   |
| FreeBSD 12.2         | 1        | 1.08%   |
| FreeBSD 12.1-p7      | 1        | 1.08%   |
| FreeBSD 12.1-p10     | 1        | 1.08%   |
| FreeBSD 12.1         | 1        | 1.08%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 37       | 48.05%  |
| helloSystem | 17       | 22.08%  |
| FreeBSD     | 16       | 20.78%  |
| NomadBSD    | 2        | 2.6%    |
| TrueNAS     | 1        | 1.3%    |
| pfSense     | 1        | 1.3%    |
| OpenBSD     | 1        | 1.3%    |
| NetBSD      | 1        | 1.3%    |
| FreeNAS     | 1        | 1.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 74       | 98.67%  |
| i386  | 1        | 1.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 40       | 51.95%  |
| helloDesktop | 18       | 23.38%  |
| KDE5         | 8        | 10.39%  |
| Openbox      | 4        | 5.19%   |
| XFCE         | 3        | 3.9%    |
| Window Maker | 1        | 1.3%    |
| TWM          | 1        | 1.3%    |
| MATE         | 1        | 1.3%    |
| GNOME        | 1        | 1.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 42       | 56%     |
| X11     | 33       | 44%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 46       | 60.53%  |
| SLiM    | 19       | 25%     |
| SDDM    | 7        | 9.21%   |
| GDM     | 3        | 3.95%   |
| XDM     | 1        | 1.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 41       | 53.95%  |
| en_US   | 18       | 23.68%  |
| pt_BR   | 9        | 11.84%  |
| C       | 7        | 9.21%   |
| fr_FR   | 1        | 1.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 55       | 70.51%  |
| BIOS | 23       | 29.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 47       | 61.04%  |
| Zfs    | 26       | 33.77%  |
| Cd9660 | 3        | 3.9%    |
| Ffs    | 1        | 1.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 63       | 81.82%  |
| MBR     | 13       | 16.88%  |
| Unknown | 1        | 1.3%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUSTek Computer        | 18       | 24%     |
| Intel                   | 8        | 10.67%  |
| Dell                    | 8        | 10.67%  |
| Hewlett-Packard         | 7        | 9.33%   |
| Gigabyte Technology     | 6        | 8%      |
| Unknown                 | 4        | 5.33%   |
| MSI                     | 3        | 4%      |
| Positivo                | 2        | 2.67%   |
| Pegatron                | 2        | 2.67%   |
| PCWare                  | 2        | 2.67%   |
| Itautec                 | 2        | 2.67%   |
| ECS                     | 2        | 2.67%   |
| ASRock                  | 2        | 2.67%   |
| Yanling                 | 1        | 1.33%   |
| ULTRATOP                | 1        | 1.33%   |
| Semp Toshiba            | 1        | 1.33%   |
| Procomp Ind. Eletronica | 1        | 1.33%   |
| KLLISRE                 | 1        | 1.33%   |
| HC                      | 1        | 1.33%   |
| GALAX                   | 1        | 1.33%   |
| ECS-USA                 | 1        | 1.33%   |
| CNCTION-IAF-E3845       | 1        | 1.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Intel Q3XXG4-P V1.0                | 5        | 6.67%   |
| Unknown                            | 5        | 6.67%   |
| ASUS All Series                    | 4        | 5.33%   |
| Pegatron IPM41-D3                  | 2        | 2.67%   |
| Gigabyte H61M-S2-B3                | 2        | 2.67%   |
| ASUS PRIME B450M-GAMING/BR         | 2        | 2.67%   |
| ASUS P8H61-M LX3 PLUS R2.0         | 2        | 2.67%   |
| ASUS M5A78L-M LX/BR                | 2        | 2.67%   |
| Yanling NS-1U8L                    | 1        | 1.33%   |
| ULTRATOP C2017-LIVA-ZE             | 1        | 1.33%   |
| Semp Toshiba STI                   | 1        | 1.33%   |
| Procomp Ind. Eletronica G41MXE     | 1        | 1.33%   |
| Positivo POS-PIQ77CL               | 1        | 1.33%   |
| Positivo POS-EAA75DE               | 1        | 1.33%   |
| PCWare PW-945GCX                   | 1        | 1.33%   |
| PCWare IPX1800G2                   | 1        | 1.33%   |
| MSI U-100                          | 1        | 1.33%   |
| MSI MS-7877                        | 1        | 1.33%   |
| MSI MS-7698                        | 1        | 1.33%   |
| KLLISRE X99-B5 V1.0                | 1        | 1.33%   |
| Itautec Infoway ST-4344            | 1        | 1.33%   |
| Itautec Infoway                    | 1        | 1.33%   |
| Intel H61                          | 1        | 1.33%   |
| Intel H55                          | 1        | 1.33%   |
| Intel DH61WW AAG23116-206          | 1        | 1.33%   |
| HP Z230 Tower Workstation          | 1        | 1.33%   |
| HP ProLiant ML350 G6               | 1        | 1.33%   |
| HP ProLiant ML310e Gen8 v2         | 1        | 1.33%   |
| HP ProLiant MicroServer Gen8       | 1        | 1.33%   |
| HP ProLiant MicroServer            | 1        | 1.33%   |
| HP EliteDesk 800 G4 SFF            | 1        | 1.33%   |
| HP Compaq dc5800 Small Form Factor | 1        | 1.33%   |
| HC HCAR357-MI                      | 1        | 1.33%   |
| Gigabyte G41MT-S2                  | 1        | 1.33%   |
| Gigabyte C847N                     | 1        | 1.33%   |
| Gigabyte AB350M-Gaming 3           | 1        | 1.33%   |
| Gigabyte 970A-UD3P                 | 1        | 1.33%   |
| GALAX B365M                        | 1        | 1.33%   |
| ECS-USA GeForce6100PM-M2           | 1        | 1.33%   |
| ECS H55H-CM                        | 1        | 1.33%   |
| ECS BAT-I                          | 1        | 1.33%   |
| Dell Vostro 230                    | 1        | 1.33%   |
| Dell Vostro 220s Series            | 1        | 1.33%   |
| Dell OptiPlex 790                  | 1        | 1.33%   |
| Dell OptiPlex 390                  | 1        | 1.33%   |
| Dell OptiPlex 380                  | 1        | 1.33%   |
| Dell OptiPlex 3020                 | 1        | 1.33%   |
| Dell Inspiron 620                  | 1        | 1.33%   |
| Dell Inspiron 5680                 | 1        | 1.33%   |
| ASUS Z8P                           | 1        | 1.33%   |
| ASUS STRIX B250G GAMING            | 1        | 1.33%   |
| ASUS PRIME H310M-K R2.0            | 1        | 1.33%   |
| ASUS P5Q                           | 1        | 1.33%   |
| ASUS P5G41T-M LX V2                | 1        | 1.33%   |
| ASUS M5A97 LE R2.0                 | 1        | 1.33%   |
| ASUS M5A78L-M PLUS/USB3            | 1        | 1.33%   |
| ASUS H110M-K                       | 1        | 1.33%   |
| ASRock A320M-DGS                   | 1        | 1.33%   |
| ASRock 970A-G                      | 1        | 1.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel Q3XXG4-P                 | 5        | 6.67%   |
| Unknown                        | 5        | 6.67%   |
| HP ProLiant                    | 4        | 5.33%   |
| Dell OptiPlex                  | 4        | 5.33%   |
| ASUS All                       | 4        | 5.33%   |
| ASUS PRIME                     | 3        | 4%      |
| ASUS M5A78L-M                  | 3        | 4%      |
| Pegatron IPM41-D3              | 2        | 2.67%   |
| Itautec Infoway                | 2        | 2.67%   |
| Gigabyte H61M-S2-B3            | 2        | 2.67%   |
| Dell Vostro                    | 2        | 2.67%   |
| Dell Inspiron                  | 2        | 2.67%   |
| ASUS P8H61-M                   | 2        | 2.67%   |
| Yanling NS-1U8L                | 1        | 1.33%   |
| ULTRATOP C2017-LIVA-ZE         | 1        | 1.33%   |
| Semp Toshiba STI               | 1        | 1.33%   |
| Procomp Ind. Eletronica G41MXE | 1        | 1.33%   |
| Positivo POS-PIQ77CL           | 1        | 1.33%   |
| Positivo POS-EAA75DE           | 1        | 1.33%   |
| PCWare PW-945GCX               | 1        | 1.33%   |
| PCWare IPX1800G2               | 1        | 1.33%   |
| MSI U-100                      | 1        | 1.33%   |
| MSI MS-7877                    | 1        | 1.33%   |
| MSI MS-7698                    | 1        | 1.33%   |
| KLLISRE X99-B5                 | 1        | 1.33%   |
| Intel H61                      | 1        | 1.33%   |
| Intel H55                      | 1        | 1.33%   |
| Intel DH61WW                   | 1        | 1.33%   |
| HP Z230                        | 1        | 1.33%   |
| HP EliteDesk                   | 1        | 1.33%   |
| HP Compaq                      | 1        | 1.33%   |
| HC HCAR357-MI                  | 1        | 1.33%   |
| Gigabyte G41MT-S2              | 1        | 1.33%   |
| Gigabyte C847N                 | 1        | 1.33%   |
| Gigabyte AB350M-Gaming         | 1        | 1.33%   |
| Gigabyte 970A-UD3P             | 1        | 1.33%   |
| GALAX B365M                    | 1        | 1.33%   |
| ECS-USA GeForce6100PM-M2       | 1        | 1.33%   |
| ECS H55H-CM                    | 1        | 1.33%   |
| ECS BAT-I                      | 1        | 1.33%   |
| ASUS Z8P                       | 1        | 1.33%   |
| ASUS STRIX                     | 1        | 1.33%   |
| ASUS P5Q                       | 1        | 1.33%   |
| ASUS P5G41T-M                  | 1        | 1.33%   |
| ASUS M5A97                     | 1        | 1.33%   |
| ASUS H110M-K                   | 1        | 1.33%   |
| ASRock A320M-DGS               | 1        | 1.33%   |
| ASRock 970A-G                  | 1        | 1.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2016 | 13       | 17.33%  |
| 2013 | 7        | 9.33%   |
| 2010 | 7        | 9.33%   |
| 2018 | 6        | 8%      |
| 2011 | 6        | 8%      |
| 2009 | 6        | 8%      |
| 2019 | 5        | 6.67%   |
| 2012 | 5        | 6.67%   |
| 2020 | 4        | 5.33%   |
| 2017 | 4        | 5.33%   |
| 2015 | 3        | 4%      |
| 2014 | 3        | 4%      |
| 2008 | 3        | 4%      |
| 2021 | 2        | 2.67%   |
| 2007 | 1        | 1.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 75       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 75       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 28       | 36.84%  |
| 8.01-16.0  | 25       | 32.89%  |
| 16.01-24.0 | 12       | 15.79%  |
| 2.01-3.0   | 7        | 9.21%   |
| 32.01-64.0 | 4        | 5.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 51       | 66.23%  |
| 0.51-1.0   | 18       | 23.38%  |
| 1.01-2.0   | 4        | 5.19%   |
| 4.01-8.0   | 2        | 2.6%    |
| 16.01-24.0 | 1        | 1.3%    |
| Unknown    | 1        | 1.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 55       | 70.51%  |
| 2      | 8        | 10.26%  |
| 3      | 6        | 7.69%   |
| 0      | 4        | 5.13%   |
| 5      | 2        | 2.56%   |
| 7      | 1        | 1.28%   |
| 6      | 1        | 1.28%   |
| 4      | 1        | 1.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 57       | 76%     |
| Yes       | 18       | 24%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 74       | 98.67%  |
| No        | 1        | 1.33%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 62       | 82.67%  |
| Yes       | 13       | 17.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 73       | 97.33%  |
| Yes       | 2        | 2.67%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Brazil  | 75       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| SГЈo Paulo              | 12       | 14.29%  |
| Rio de Janeiro            | 7        | 8.33%   |
| SÃ£o Paulo              | 3        | 3.57%   |
| Curitiba                  | 3        | 3.57%   |
| RondonГіpolis           | 2        | 2.38%   |
| Rio Claro                 | 2        | 2.38%   |
| Porto Alegre              | 2        | 2.38%   |
| Pirapora                  | 2        | 2.38%   |
| Campinas                  | 2        | 2.38%   |
| BrasÃ­lia               | 2        | 2.38%   |
| VitГіria da Conquista   | 1        | 1.19%   |
| Urupes                    | 1        | 1.19%   |
| Unai                      | 1        | 1.19%   |
| Teresina                  | 1        | 1.19%   |
| SГЈo JosГ© dos Campos | 1        | 1.19%   |
| Serra                     | 1        | 1.19%   |
| Sao Vicente               | 1        | 1.19%   |
| Sao Paulo                 | 1        | 1.19%   |
| Reriutaba                 | 1        | 1.19%   |
| Piracicaba                | 1        | 1.19%   |
| Pelotas                   | 1        | 1.19%   |
| Patos de Minas            | 1        | 1.19%   |
| Pato Branco               | 1        | 1.19%   |
| Novo Horizonte do Norte   | 1        | 1.19%   |
| Novo Hamburgo             | 1        | 1.19%   |
| Morungaba                 | 1        | 1.19%   |
| Manaus                    | 1        | 1.19%   |
| Macatuba                  | 1        | 1.19%   |
| JundiaГ­                | 1        | 1.19%   |
| Juazeiro                  | 1        | 1.19%   |
| Juara                     | 1        | 1.19%   |
| JoГЈo Pessoa            | 1        | 1.19%   |
| Joinville                 | 1        | 1.19%   |
| JaraguГЎ do Sul         | 1        | 1.19%   |
| JaraguÃ¡ do Sul         | 1        | 1.19%   |
| Jaraguá do Sul           | 1        | 1.19%   |
| JacareГ­                | 1        | 1.19%   |
| Jaboatao dos Guararapes   | 1        | 1.19%   |
| Itaperuna                 | 1        | 1.19%   |
| Itaocara                  | 1        | 1.19%   |
| ItajaГ­                 | 1        | 1.19%   |
| Inhapim                   | 1        | 1.19%   |
| IlhÃ©us                 | 1        | 1.19%   |
| Guarulhos                 | 1        | 1.19%   |
| Frederico Westphalen      | 1        | 1.19%   |
| Franca                    | 1        | 1.19%   |
| FlorianÃ³polis          | 1        | 1.19%   |
| Farroupilha               | 1        | 1.19%   |
| Cruzeiro do Sul           | 1        | 1.19%   |
| CriciÃºma               | 1        | 1.19%   |
| Cidade Universitária     | 1        | 1.19%   |
| BrasГ­lia               | 1        | 1.19%   |
| Boa Vista do Jauato       | 1        | 1.19%   |
| Benevides                 | 1        | 1.19%   |
| Belo Horizonte            | 1        | 1.19%   |
| Belém                    | 1        | 1.19%   |
| Barracao                  | 1        | 1.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 22       | 29     | 22.22%  |
| Seagate             | 19       | 43     | 19.19%  |
| Kingston            | 17       | 25     | 17.17%  |
| Samsung Electronics | 11       | 12     | 11.11%  |
| SanDisk             | 5        | 5      | 5.05%   |
| Toshiba             | 4        | 4      | 4.04%   |
| Hoodisk             | 4        | 4      | 4.04%   |
| A-DATA Technology   | 3        | 3      | 3.03%   |
| Hitachi             | 2        | 4      | 2.02%   |
| Crucial             | 2        | 3      | 2.02%   |
| China               | 2        | 4      | 2.02%   |
| XrayDisk            | 1        | 1      | 1.01%   |
| Silicon Motion      | 1        | 1      | 1.01%   |
| NTC                 | 1        | 1      | 1.01%   |
| HGST                | 1        | 2      | 1.01%   |
| Hewlett-Packard     | 1        | 1      | 1.01%   |
| Gigabyte Technology | 1        | 1      | 1.01%   |
| faspeed             | 1        | 1      | 1.01%   |
| Drevo               | 1        | 3      | 1.01%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB         | 6        | 5.31%   |
| Kingston SA400S37120G 120GB         | 6        | 5.31%   |
| WDC WD10EZEX-00RKKA0 1TB            | 3        | 2.65%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3        | 2.65%   |
| Seagate ST500DM002-1BD142 500GB     | 3        | 2.65%   |
| Seagate ST4000DM000-1F2168 4TB      | 3        | 2.65%   |
| Seagate ST1000DM010-2EP102 1TB      | 3        | 2.65%   |
| Samsung HD322HJ 320GB               | 3        | 2.65%   |
| A-DATA SU630 240GB                  | 3        | 2.65%   |
| Seagate ST2000DM006-2DM164 2TB      | 2        | 1.77%   |
| SanDisk SDSSDA240G 240GB            | 2        | 1.77%   |
| Samsung HD502HJ 500GB               | 2        | 1.77%   |
| Samsung HD161HJ 160GB               | 2        | 1.77%   |
| Kingston SA400S37480G 480GB         | 2        | 1.77%   |
| Hoodisk SSD 64GB                    | 2        | 1.77%   |
| Hoodisk SSD 32GB                    | 2        | 1.77%   |
| XrayDisk SSD 128GB                  | 1        | 0.88%   |
| WDC WDS120G2G0A-00JH30 120GB        | 1        | 0.88%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1        | 0.88%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 1        | 0.88%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 1        | 0.88%   |
| WDC WD5000AAKS-08V0A0 500GB         | 1        | 0.88%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 1        | 0.88%   |
| WDC WD400BD-75LRA0 40GB             | 1        | 0.88%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1        | 0.88%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 1        | 0.88%   |
| WDC WD3200BEVT-00A0RT0 233GB        | 1        | 0.88%   |
| WDC WD3200AAKS-00UU3A0 320GB        | 1        | 0.88%   |
| WDC WD3200AAJS-60Z0A0 320GB         | 1        | 0.88%   |
| WDC WD3200AAJS-56M0A0 320GB         | 1        | 0.88%   |
| WDC WD3200AAJS-00YZCA0 320GB        | 1        | 0.88%   |
| WDC WD2500AAKX-75U6AA0 250GB        | 1        | 0.88%   |
| WDC WD1600AVJS-63WNA0 160GB         | 1        | 0.88%   |
| WDC WD1200BEVT-22ZCT0 120GB         | 1        | 0.88%   |
| WDC WD10SPZX-21Z10T0 1TB            | 1        | 0.88%   |
| WDC WD10PURX-64E5EY0 1TB            | 1        | 0.88%   |
| WDC WD10JPVX-80JC3T0 1TB            | 1        | 0.88%   |
| WDC WD10EZEX-75WN4A1 1TB            | 1        | 0.88%   |
| WDC WD10EZEX-75WN4A0 1TB            | 1        | 0.88%   |
| WDC WD10EZEX-60WN4A0 1TB            | 1        | 0.88%   |
| Toshiba MQ01ABF050 500GB            | 1        | 0.88%   |
| Toshiba MQ01ABD050 500GB            | 1        | 0.88%   |
| Toshiba DT01ACA100 1TB              | 1        | 0.88%   |
| Toshiba DT01ACA050 LENOVO 500GB     | 1        | 0.88%   |
| Silicon Motion ShiJi 256GB M.2-NVMe | 1        | 0.88%   |
| Seagate ST9160314AS 160GB           | 1        | 0.88%   |
| Seagate ST500LM021-1KJ152 500GB     | 1        | 0.88%   |
| Seagate ST500DM002-1BC142 500GB     | 1        | 0.88%   |
| Seagate ST380817AS 80GB             | 1        | 0.88%   |
| Seagate ST3500312CS 500GB           | 1        | 0.88%   |
| Seagate ST3250310AS 250GB           | 1        | 0.88%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 1        | 0.88%   |
| Seagate ST3160813AS 160GB           | 1        | 0.88%   |
| Seagate ST2000DM001-1E6164 2TB      | 1        | 0.88%   |
| Seagate ST2000DL003-9VT166 2TB      | 1        | 0.88%   |
| Seagate ST1000VM002-1SD102 1TB      | 1        | 0.88%   |
| Seagate ST1000VM002-1ET162 1TB      | 1        | 0.88%   |
| Seagate ST1000DM003-1CH162 1TB      | 1        | 0.88%   |
| SanDisk SSD PLUS 240 GB             | 1        | 0.88%   |
| SanDisk SSD PLUS 120GB              | 1        | 0.88%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 21       | 28     | 36.21%  |
| Seagate             | 19       | 43     | 32.76%  |
| Samsung Electronics | 10       | 11     | 17.24%  |
| Toshiba             | 4        | 4      | 6.9%    |
| Hitachi             | 2        | 4      | 3.45%   |
| HGST                | 1        | 2      | 1.72%   |
| Hewlett-Packard     | 1        | 1      | 1.72%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 17       | 25     | 42.5%   |
| SanDisk             | 5        | 5      | 12.5%   |
| Hoodisk             | 4        | 4      | 10%     |
| A-DATA Technology   | 3        | 3      | 7.5%    |
| Crucial             | 2        | 3      | 5%      |
| China               | 2        | 4      | 5%      |
| XrayDisk            | 1        | 1      | 2.5%    |
| WDC                 | 1        | 1      | 2.5%    |
| Samsung Electronics | 1        | 1      | 2.5%    |
| NTC                 | 1        | 1      | 2.5%    |
| Gigabyte Technology | 1        | 1      | 2.5%    |
| faspeed             | 1        | 1      | 2.5%    |
| Drevo               | 1        | 3      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 47       | 93     | 55.95%  |
| SSD  | 36       | 53     | 42.86%  |
| NVMe | 1        | 1      | 1.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 70       | 146    | 98.59%  |
| NVMe | 1        | 1      | 1.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 64       | 102    | 77.11%  |
| 0.51-1.0   | 12       | 24     | 14.46%  |
| 1.01-2.0   | 4        | 12     | 4.82%   |
| 3.01-4.0   | 3        | 8      | 3.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 22       | 26.51%  |
| 1-20           | 17       | 20.48%  |
| 251-500        | 15       | 18.07%  |
| 51-100         | 11       | 13.25%  |
| 21-50          | 10       | 12.05%  |
| 501-1000       | 5        | 6.02%   |
| More than 3000 | 1        | 1.2%    |
| 2001-3000      | 1        | 1.2%    |
| 1001-2000      | 1        | 1.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 65       | 86.67%  |
| 21-50     | 5        | 6.67%   |
| 101-250   | 3        | 4%      |
| 2001-3000 | 1        | 1.33%   |
| 501-1000  | 1        | 1.33%   |

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
| Works    | 54       | 98     | 63.53%  |
| Malfunc  | 26       | 42     | 30.59%  |
| Detected | 4        | 6      | 4.71%   |
| Failed   | 1        | 1      | 1.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 58       | 74.36%  |
| AMD                           | 14       | 17.95%  |
| Silicon Motion                | 2        | 2.56%   |
| Nvidia                        | 1        | 1.28%   |
| Integrated Technology Express | 1        | 1.28%   |
| Hewlett-Packard               | 1        | 1.28%   |
| Adaptec                       | 1        | 1.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 13       | 12.75%  |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 8        | 7.84%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 6        | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6        | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 4.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 4.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 4.9%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 4.9%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 5        | 4.9%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 2.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 2.94%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3        | 2.94%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 2.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 2.94%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 1.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2        | 1.96%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.96%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 1.96%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.98%   |
| Nvidia MCP61 IDE                                                                        | 1        | 0.98%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 0.98%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1        | 0.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 0.98%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 0.98%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 0.98%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 1        | 0.98%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 0.98%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 1        | 0.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 0.98%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 0.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 1        | 0.98%   |
| Integrated Express IT8213 IDE Controller                                                | 1        | 0.98%   |
| HP Smart Array G6 controllers                                                           | 1        | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [Non-RAID5 mode]                                  | 1        | 0.98%   |
| AMD FCH SATA Controller D                                                               | 1        | 0.98%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 0.98%   |
| Adaptec AIC-7870P/7881U [AHA-2940U/UW/D/S76]                                            | 1        | 0.98%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 46       | 56.79%  |
| IDE  | 28       | 34.57%  |
| RAID | 4        | 4.94%   |
| NVMe | 2        | 2.47%   |
| SCSI | 1        | 1.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 60       | 80%     |
| AMD    | 15       | 20%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Celeron CPU J1800 @ 2.41GHz             | 4        | 5.26%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2        | 2.63%   |
| Intel Core i3-3240 CPU @ 3.40GHz              | 2        | 2.63%   |
| Intel Core i3-2100 CPU                        | 2        | 2.63%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2        | 2.63%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 2        | 2.63%   |
| AMD FX-8320E Eight-Core Processor             | 2        | 2.63%   |
| Intel Xeon CPU X5680 @ 3.33GHz                | 1        | 1.32%   |
| Intel Xeon CPU E5506 @ 2.13GHz                | 1        | 1.32%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz            | 1        | 1.32%   |
| Intel Xeon CPU E5-2630L v3 @ 1.80GHz          | 1        | 1.32%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz           | 1        | 1.32%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz           | 1        | 1.32%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz   | 1        | 1.32%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 1        | 1.32%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz   | 1        | 1.32%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 1        | 1.32%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 1        | 1.32%   |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1        | 1.32%   |
| Intel Pentium CPU G2020T @ 2.50GHz            | 1        | 1.32%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1        | 1.32%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 1        | 1.32%   |
| Intel Core i7-4770K CPU @ 3.50GHz             | 1        | 1.32%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1        | 1.32%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 1        | 1.32%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 1        | 1.32%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 1        | 1.32%   |
| Intel Core i5-3570 CPU @ 3.40GHz              | 1        | 1.32%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1        | 1.32%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 1        | 1.32%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 1        | 1.32%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 1        | 1.32%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 1        | 1.32%   |
| Intel Core i3-5020U CPU @ 2.20GHz             | 1        | 1.32%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1        | 1.32%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 1        | 1.32%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1        | 1.32%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 1        | 1.32%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 1        | 1.32%   |
| Intel Core i3-2120 CPU @ 3.30GH               | 1        | 1.32%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 1        | 1.32%   |
| Intel Core i3-2100 CPU @ 3.10GH               | 1        | 1.32%   |
| Intel Core i3 CPU 550 @ 3.20GHz               | 1        | 1.32%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz         | 1        | 1.32%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 1        | 1.32%   |
| Intel Core 2 Duo CPU                          | 1        | 1.32%   |
| Intel Core 2 Duo                              | 1        | 1.32%   |
| Intel Core 2 CPU 6600 @ 2.40GHz               | 1        | 1.32%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1        | 1.32%   |
| Intel Celeron CPU E3400 @ 2.60GHz             | 1        | 1.32%   |
| Intel Celeron CPU 847 @ 1.10GHz               | 1        | 1.32%   |
| Intel Celeron CPU 450 @ 2.20GHz               | 1        | 1.32%   |
| Intel Atom CPU N270 @ 1.60GH                  | 1        | 1.32%   |
| Intel Atom CPU E3845 @ 1.91GHz                | 1        | 1.32%   |
| AMD Turion II Neo N40L Dual-Core Processor    | 1        | 1.32%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1        | 1.32%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 1        | 1.32%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 1        | 1.32%   |
| AMD Ryzen 5 1500X Quad-Core Processor         | 1        | 1.32%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 1        | 1.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i3           | 17       | 22.67%  |
| Intel Core i5           | 8        | 10.67%  |
| Intel Celeron           | 8        | 10.67%  |
| Intel Xeon              | 6        | 8%      |
| Intel Core 2 Duo        | 6        | 8%      |
| AMD FX                  | 6        | 8%      |
| Intel Pentium Dual-Core | 5        | 6.67%   |
| AMD Ryzen 5             | 4        | 5.33%   |
| Intel Core i7           | 3        | 4%      |
| Intel Pentium           | 2        | 2.67%   |
| Intel Core 2 Quad       | 2        | 2.67%   |
| Intel Atom              | 2        | 2.67%   |
| Intel Core 2            | 1        | 1.33%   |
| AMD Turion II Neo       | 1        | 1.33%   |
| AMD Ryzen 3             | 1        | 1.33%   |
| AMD PRO A8              | 1        | 1.33%   |
| AMD Phenom              | 1        | 1.33%   |
| AMD E                   | 1        | 1.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 37       | 48.68%  |
| 4       | 19       | 25%     |
| 8       | 8        | 10.53%  |
| 6       | 5        | 6.58%   |
| 12      | 3        | 3.95%   |
| Unknown | 3        | 3.95%   |
| 1       | 1        | 1.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 74       | 98.67%  |
| 2      | 1        | 1.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 48       | 63.16%  |
| 2       | 25       | 32.89%  |
| Unknown | 3        | 3.95%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 12       | 15.79%  |
| Haswell     | 10       | 13.16%  |
| SandyBridge | 9        | 11.84%  |
| Silvermont  | 6        | 7.89%   |
| KabyLake    | 6        | 7.89%   |
| IvyBridge   | 6        | 7.89%   |
| Piledriver  | 5        | 6.58%   |
| Zen+        | 4        | 5.26%   |
| Westmere    | 3        | 3.95%   |
| Core        | 3        | 3.95%   |
| K10         | 2        | 2.63%   |
| Broadwell   | 2        | 2.63%   |
| Zen         | 1        | 1.32%   |
| Steamroller | 1        | 1.32%   |
| Nehalem     | 1        | 1.32%   |
| Goldmont    | 1        | 1.32%   |
| Bulldozer   | 1        | 1.32%   |
| Bonnell     | 1        | 1.32%   |
| Bobcat      | 1        | 1.32%   |
| Unknown     | 1        | 1.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 47       | 61.04%  |
| AMD                        | 16       | 20.78%  |
| Nvidia                     | 11       | 14.29%  |
| Matrox Electronics Systems | 2        | 2.6%    |
| ASPEED Technology          | 1        | 1.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                         | 8        | 10.13%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 8        | 10.13%  |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 6        | 7.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 5        | 6.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3        | 3.8%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                        | 3        | 3.8%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 3        | 3.8%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 2        | 2.53%   |
| Nvidia GK208B [GeForce GT 710]                                                | 2        | 2.53%   |
| Matrox Electronics Systems MGA G200EH                                         | 2        | 2.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 2        | 2.53%   |
| Intel HD Graphics 630                                                         | 2        | 2.53%   |
| Intel HD Graphics 5500                                                        | 2        | 2.53%   |
| Intel Core Processor Integrated Graphics Controller                           | 2        | 2.53%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 2        | 2.53%   |
| AMD RV710 [Radeon HD 4350/4550]                                               | 2        | 2.53%   |
| AMD RS780L [Radeon 3000]                                                      | 2        | 2.53%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                    | 2        | 2.53%   |
| Nvidia GT218 [GeForce 210]                                                    | 1        | 1.27%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                           | 1        | 1.27%   |
| Nvidia GK107GL [Quadro K2000]                                                 | 1        | 1.27%   |
| Nvidia GF119 [GeForce GT 610]                                                 | 1        | 1.27%   |
| Nvidia GF108 [GeForce GT 430]                                                 | 1        | 1.27%   |
| Nvidia GF106 [GeForce GTS 450]                                                | 1        | 1.27%   |
| Nvidia G86 [GeForce 8500 GT]                                                  | 1        | 1.27%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1        | 1.27%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1        | 1.27%   |
| Intel HD Graphics 500                                                         | 1        | 1.27%   |
| Intel 82Q33 Express Integrated Graphics Controller                            | 1        | 1.27%   |
| Intel 82945G/GZ Integrated Graphics Controller                                | 1        | 1.27%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller     | 1        | 1.27%   |
| ASPEED Technology ASPEED Graphics Family                                      | 1        | 1.27%   |
| AMD Wrestler [Radeon HD 6310]                                                 | 1        | 1.27%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                     | 1        | 1.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1        | 1.27%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]         | 1        | 1.27%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                | 1        | 1.27%   |
| AMD Kaveri [Radeon R7 Graphics]                                               | 1        | 1.27%   |
| AMD ES1000                                                                    | 1        | 1.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Intel   | 43       | 56.58%  |
| 1 x AMD     | 15       | 19.74%  |
| 1 x Nvidia  | 11       | 14.47%  |
| 2 x Intel   | 3        | 3.95%   |
| 1 x Matrox  | 2        | 2.63%   |
| Intel + AMD | 1        | 1.32%   |
| 1 x ASPEED  | 1        | 1.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 68       | 89.47%  |
| Proprietary | 8        | 10.53%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 59       | 75.64%  |
| 3.01-4.0   | 6        | 7.69%   |
| 1.01-2.0   | 4        | 5.13%   |
| 0.51-1.0   | 4        | 5.13%   |
| 0.01-0.5   | 3        | 3.85%   |
| 7.01-8.0   | 1        | 1.28%   |
| 2.01-3.0   | 1        | 1.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Goldstar            | 11       | 37.93%  |
| Samsung Electronics | 9        | 31.03%  |
| AOC                 | 2        | 6.9%    |
| VIE                 | 1        | 3.45%   |
| Philips             | 1        | 3.45%   |
| Panasonic           | 1        | 3.45%   |
| LG Electronics      | 1        | 3.45%   |
| Lenovo              | 1        | 3.45%   |
| Hewlett-Packard     | 1        | 3.45%   |
| ASUSTek Computer    | 1        | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| VIE E195 VIE1950 1600x900 410x280mm 19.5-inch                        | 1        | 3.13%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch | 1        | 3.13%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                      | 1        | 3.13%   |
| Samsung Electronics SyncMaster SAM0600 1600x900 440x250mm 19.9-inch  | 1        | 3.13%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch  | 1        | 3.13%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                     | 1        | 3.13%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x260mm 19.1-inch  | 1        | 3.13%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 340x190mm 15.3-inch  | 1        | 3.13%   |
| Samsung Electronics SyncMaster SAM0117 1280x1024 310x230mm 15.2-inch | 1        | 3.13%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 280x210mm 13.8-inch  | 1        | 3.13%   |
| Samsung Electronics S19B300 SAM08A6 1366x768 410x230mm 18.5-inch     | 1        | 3.13%   |
| Samsung Electronics LCD Monitor SMT27A550 1920x1080                  | 1        | 3.13%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch              | 1        | 3.13%   |
| Panasonic TV MEIC136 1280x720 698x392mm 31.5-inch                    | 1        | 3.13%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 3640x1920                    | 1        | 3.13%   |
| LG Electronics LCD Monitor 23MP55                                    | 1        | 3.13%   |
| Lenovo LEN T22i-10 LEN61A9 1920x1080 480x270mm 21.7-inch             | 1        | 3.13%   |
| Hewlett-Packard E233 HPN345F 1920x1080 510x290mm 23.1-inch           | 1        | 3.13%   |
| Goldstar W2043 GSM4E9D 1600x900 450x250mm 20.3-inch                  | 1        | 3.13%   |
| Goldstar W1952 GSM4B78 1440x900 410x260mm 19.1-inch                  | 1        | 3.13%   |
| Goldstar W1942 GSM4B6F 1440x900 410x260mm 19.1-inch                  | 1        | 3.13%   |
| Goldstar LCD Monitor GSM5AB7 1920x1080 480x270mm 21.7-inch           | 1        | 3.13%   |
| Goldstar L1950H GSM4AA2 1280x1024 380x300mm 19.1-inch                | 1        | 3.13%   |
| Goldstar L1753T GSM4433 1280x1024 340x270mm 17.1-inch                | 1        | 3.13%   |
| Goldstar L1553S GSM3BB0 1024x768 300x230mm 14.9-inch                 | 1        | 3.13%   |
| Goldstar E2241 GSM581A 1920x1080 480x270mm 21.7-inch                 | 1        | 3.13%   |
| Goldstar D2342P GSM5840 1920x1080 510x290mm 23.1-inch                | 1        | 3.13%   |
| Goldstar 23EA53 GSM59A8 1920x1080 510x290mm 23.1-inch                | 1        | 3.13%   |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                | 1        | 3.13%   |
| ASUSTek Computer VG248 AUS24C2 1920x1080 530x300mm 24.0-inch         | 1        | 3.13%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                         | 1        | 3.13%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 1        | 3.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 12       | 38.71%  |
| 1600x900 (HD+)   | 4        | 12.9%   |
| 1440x900 (WXGA+) | 3        | 9.68%   |
| 1366x768 (WXGA)  | 3        | 9.68%   |
| 1280x1024 (SXGA) | 3        | 9.68%   |
| 1024x768 (XGA)   | 2        | 6.45%   |
| 3640x1920        | 1        | 3.23%   |
| 1360x768         | 1        | 3.23%   |
| 1280x720 (HD)    | 1        | 3.23%   |
| Unknown          | 1        | 3.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 19      | 6        | 20%     |
| 23      | 5        | 16.67%  |
| 21      | 4        | 13.33%  |
| Unknown | 4        | 13.33%  |
| 18      | 3        | 10%     |
| 15      | 2        | 6.67%   |
| 31      | 1        | 3.33%   |
| 24      | 1        | 3.33%   |
| 20      | 1        | 3.33%   |
| 17      | 1        | 3.33%   |
| 14      | 1        | 3.33%   |
| 13      | 1        | 3.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 12       | 41.38%  |
| 501-600     | 6        | 20.69%  |
| Unknown     | 4        | 13.79%  |
| 301-350     | 3        | 10.34%  |
| 201-300     | 2        | 6.9%    |
| 601-700     | 1        | 3.45%   |
| 351-400     | 1        | 3.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 18       | 62.07%  |
| 4/3     | 3        | 10.34%  |
| 16/10   | 3        | 10.34%  |
| 5/4     | 2        | 6.9%    |
| Unknown | 2        | 6.9%    |
| 3/2     | 1        | 3.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 10       | 33.33%  |
| 151-200        | 7        | 23.33%  |
| 141-150        | 4        | 13.33%  |
| Unknown        | 4        | 13.33%  |
| 91-100         | 2        | 6.67%   |
| 351-500        | 1        | 3.33%   |
| 111-120        | 1        | 3.33%   |
| 101-110        | 1        | 3.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 19       | 63.33%  |
| 101-120 | 6        | 20%     |
| Unknown | 4        | 13.33%  |
| 1-50    | 1        | 3.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 46       | 60.53%  |
| 1     | 27       | 35.53%  |
| 2     | 3        | 3.95%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 51       | 49.04%  |
| Intel                 | 27       | 25.96%  |
| Qualcomm Atheros      | 7        | 6.73%   |
| Broadcom              | 7        | 6.73%   |
| Ralink                | 4        | 3.85%   |
| TP-Link               | 1        | 0.96%   |
| Samsung Electronics   | 1        | 0.96%   |
| Ralink Technology     | 1        | 0.96%   |
| MediaTek              | 1        | 0.96%   |
| ICS Advent            | 1        | 0.96%   |
| D-Link System         | 1        | 0.96%   |
| Arduino SA            | 1        | 0.96%   |
| 3Com                  | 1        | 0.96%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 43       | 37.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 6        | 5.26%   |
| Intel I211 Gigabit Network Connection                                | 6        | 5.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 3        | 2.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 3        | 2.63%   |
| Intel 82576 Gigabit Network Connection                               | 3        | 2.63%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 2        | 1.75%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 2        | 1.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 2        | 1.75%   |
| Intel Ethernet Connection (2) I218-V                                 | 2        | 1.75%   |
| Intel 82583V Gigabit Network Connection                              | 2        | 1.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 2        | 1.75%   |
| Intel 82574L Gigabit Network Connection                              | 2        | 1.75%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                     | 2        | 1.75%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1        | 0.88%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)          | 1        | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1        | 0.88%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 0.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1        | 0.88%   |
| Realtek RTL8187SE Wireless LAN Controller                            | 1        | 0.88%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                      | 1        | 0.88%   |
| Ralink RT5370 Wireless Adapter                                       | 1        | 0.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1        | 0.88%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                           | 1        | 0.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 0.88%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                        | 1        | 0.88%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 1        | 0.88%   |
| MediaTek USB Ethernet-RNDIS                                          | 1        | 0.88%   |
| Intel Wireless 7265                                                  | 1        | 0.88%   |
| Intel I350 Gigabit Network Connection                                | 1        | 0.88%   |
| Intel Ethernet Connection I217-LM                                    | 1        | 0.88%   |
| Intel Ethernet Connection (7) I219-LM                                | 1        | 0.88%   |
| Intel Ethernet Connection (2) I219-V                                 | 1        | 0.88%   |
| Intel 82579V Gigabit Network Connection                              | 1        | 0.88%   |
| Intel 82578DC Gigabit Network Connection                             | 1        | 0.88%   |
| Intel 82575GB Gigabit Network Connection                             | 1        | 0.88%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)           | 1        | 0.88%   |
| Intel 82566DM-2 Gigabit Network Connection                           | 1        | 0.88%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                 | 1        | 0.88%   |
| ICS Advent DM9601 Fast Ethernet Adapter                              | 1        | 0.88%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 1        | 0.88%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                       | 1        | 0.88%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                     | 1        | 0.88%   |
| Broadcom NetXtreme BCM5715 Gigabit Ethernet                          | 1        | 0.88%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                      | 1        | 0.88%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                      | 1        | 0.88%   |
| Arduino SA Uno R3 (CDC ACM)                                          | 1        | 0.88%   |
| 3Com 3c905 100BaseTX [Boomerang]                                     | 1        | 0.88%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 41.18%  |
| Ralink                | 4        | 23.53%  |
| Qualcomm Atheros      | 2        | 11.76%  |
| TP-Link               | 1        | 5.88%   |
| Ralink Technology     | 1        | 5.88%   |
| Intel                 | 1        | 5.88%   |
| D-Link System         | 1        | 5.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 3        | 17.65%  |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 2        | 11.76%  |
| Ralink RT2561/RT61 rev B 802.11g                                     | 2        | 11.76%  |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1        | 5.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1        | 5.88%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 5.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1        | 5.88%   |
| Realtek RTL8187SE Wireless LAN Controller                            | 1        | 5.88%   |
| Ralink RT5370 Wireless Adapter                                       | 1        | 5.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1        | 5.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 5.88%   |
| Intel Wireless 7265                                                  | 1        | 5.88%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 1        | 5.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 50       | 53.76%  |
| Intel                 | 27       | 29.03%  |
| Broadcom              | 7        | 7.53%   |
| Qualcomm Atheros      | 5        | 5.38%   |
| Samsung Electronics   | 1        | 1.08%   |
| MediaTek              | 1        | 1.08%   |
| ICS Advent            | 1        | 1.08%   |
| 3Com                  | 1        | 1.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 43       | 44.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6        | 6.25%   |
| Intel I211 Gigabit Network Connection                             | 6        | 6.25%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 3.13%   |
| Intel 82576 Gigabit Network Connection                            | 3        | 3.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 2.08%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 2.08%   |
| Intel 82583V Gigabit Network Connection                           | 2        | 2.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 2.08%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 2.08%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2        | 2.08%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 1.04%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.04%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 1.04%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 1.04%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 1.04%   |
| MediaTek USB Ethernet-RNDIS                                       | 1        | 1.04%   |
| Intel I350 Gigabit Network Connection                             | 1        | 1.04%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.04%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.04%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.04%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.04%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.04%   |
| Intel 82575GB Gigabit Network Connection                          | 1        | 1.04%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 1.04%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.04%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 1.04%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1        | 1.04%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1        | 1.04%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 1        | 1.04%   |
| Broadcom NetXtreme BCM5715 Gigabit Ethernet                       | 1        | 1.04%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 1.04%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 1.04%   |
| 3Com 3c905 100BaseTX [Boomerang]                                  | 1        | 1.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 74       | 84.09%  |
| WiFi     | 13       | 14.77%  |
| Modem    | 1        | 1.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 73       | 87.95%  |
| WiFi     | 10       | 12.05%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 26       | 34.21%  |
| 1     | 25       | 32.89%  |
| 4     | 10       | 13.16%  |
| 3     | 10       | 13.16%  |
| 5     | 3        | 3.95%   |
| 6     | 2        | 2.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 71       | 91.03%  |
| Yes  | 7        | 8.97%   |

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
| Intel                                           | 47       | 58.02%  |
| AMD                                             | 18       | 22.22%  |
| Nvidia                                          | 11       | 13.58%  |
| C-Media Electronics                             | 3        | 3.7%    |
| Licensed by Sony Computer Entertainment America | 1        | 1.23%   |
| Generalplus Technology                          | 1        | 1.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 12       | 12.63%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7        | 7.37%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 6.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 4        | 4.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4        | 4.21%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3        | 3.16%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 3.16%   |
| Intel 8 Series HD Audio Controller                                         | 3        | 3.16%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 3.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 3.16%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 3.16%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 2.11%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 2.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 2.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2        | 2.11%   |
| Intel Broadwell-U Audio Controller                                         | 2        | 2.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 2.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 2.11%   |
| C-Media Electronics CM108 Audio Controller                                 | 2        | 2.11%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2        | 2.11%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 2.11%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 2.11%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 2.11%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.05%   |
| Nvidia High Definition Audio Controller                                    | 1        | 1.05%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 1.05%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 1.05%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 1.05%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 1.05%   |
| Nvidia GF106 High Definition Audio Controller                              | 1        | 1.05%   |
| Licensed by Sony Computer Entertainment America Wireless Stereo Headset    | 1        | 1.05%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1        | 1.05%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.05%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 1.05%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 1.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 1.05%   |
| Generalplus Technology USB Audio Device                                    | 1        | 1.05%   |
| C-Media Electronics Audio Adapter                                          | 1        | 1.05%   |
| AMD Wrestler HDMI Audio                                                    | 1        | 1.05%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1        | 1.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 1.05%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1        | 1.05%   |
| AMD FCH Azalia Controller                                                  | 1        | 1.05%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 27       | 34.62%  |
| Kingston            | 16       | 20.51%  |
| Smart               | 6        | 7.69%   |
| Crucial             | 5        | 6.41%   |
| Samsung Electronics | 3        | 3.85%   |
| Micron Technology   | 3        | 3.85%   |
| Teikon              | 2        | 2.56%   |
| Hewlett-Packard     | 2        | 2.56%   |
| Unknown             | 2        | 2.56%   |
| Tigo                | 1        | 1.28%   |
| SK Hynix            | 1        | 1.28%   |
| RZX                 | 1        | 1.28%   |
| PUSKILL             | 1        | 1.28%   |
| Nanya Technology    | 1        | 1.28%   |
| Multilaser          | 1        | 1.28%   |
| Kreton              | 1        | 1.28%   |
| G.Skill             | 1        | 1.28%   |
| CSX                 | 1        | 1.28%   |
| Corsair             | 1        | 1.28%   |
| Apacer              | 1        | 1.28%   |
| A-DATA Technology   | 1        | 1.28%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                        | 4        | 4.55%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 2        | 2.27%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 2        | 2.27%   |
| Unknown RAM Module 2GB DIMM DDR2                         | 2        | 2.27%   |
| Unknown RAM Module 2GB DIMM                              | 2        | 2.27%   |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s      | 2        | 2.27%   |
| Unknown                                                  | 2        | 2.27%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                     | 1        | 1.14%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s             | 1        | 1.14%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s             | 1        | 1.14%   |
| Unknown RAM Module 4GB DIMM SDRAM                        | 1        | 1.14%   |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s                 | 1        | 1.14%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 1.14%   |
| Unknown RAM Module 4GB DIMM 400MT/s                      | 1        | 1.14%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                     | 1        | 1.14%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 1.14%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s             | 1        | 1.14%   |
| Unknown RAM Module 4096MB DIMM DDR2                      | 1        | 1.14%   |
| Unknown RAM Module 2GB DIMM SDRAM 1333MT/s               | 1        | 1.14%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 1.14%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                     | 1        | 1.14%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 1        | 1.14%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 1.14%   |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s             | 1        | 1.14%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 1.14%   |
| Unknown RAM Module 2048MB DIMM DDR2                      | 1        | 1.14%   |
| Unknown RAM Module 1GB DIMM SDRAM                        | 1        | 1.14%   |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 1        | 1.14%   |
| Tigo RAM 1600Mhz-8G 8GB SODIMM DDR3 1600MT/s             | 1        | 1.14%   |
| Teikon RAM TMTS8G58DFRBFHC-16 8GB SODIMM DDR3 1600MT/s   | 1        | 1.14%   |
| Teikon RAM TMT41GU6BFR8C-PBHJ 8GB DIMM DDR3 1600MT/s     | 1        | 1.14%   |
| Smart RAM SH564568FH8NZQNSCR 2GB DIMM DDR3 1600MT/s      | 1        | 1.14%   |
| Smart RAM SH564568FH8N0QHSCG 2GB DIMM DDR3 1333MT/s      | 1        | 1.14%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s      | 1        | 1.14%   |
| Smart RAM SG564568FG8N6KF-Z1 2GB DIMM DDR2 800MT/s       | 1        | 1.14%   |
| SMART RAM Module 8GB DIMM DDR4 2667MT/s                  | 1        | 1.14%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 1        | 1.14%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 1.14%   |
| Samsung RAM M471B5674EB0-YK0 2GB DIMM DDR3 1600MT/s      | 1        | 1.14%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s      | 1        | 1.14%   |
| RZX RAM D3D9M1333G/4G 4GB DIMM DDR3 1333MT/s             | 1        | 1.14%   |
| PUSKILL RAM DDR3 1600 8G 8GB SODIMM DDR3 1600MT/s        | 1        | 1.14%   |
| Nanya RAM NT4GC72B8PB0NF-CG 4GB DIMM DDR3 1333MT/s       | 1        | 1.14%   |
| Multilaser RAM MS3512NSZ-CA3G1 4GB DIMM DDR3 1600MT/s    | 1        | 1.14%   |
| Micron RAM Module 16GB SODIMM DDR4 2667MT/s              | 1        | 1.14%   |
| Micron RAM 36JSF1G72PZ-1 8GB DIMM DDR3 1600MT/s          | 1        | 1.14%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s     | 1        | 1.14%   |
| Kreton RAM 51624xxxx68x45xxxx 2GB DIMM DDR2 800MT/s      | 1        | 1.14%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 2400MT/s      | 1        | 1.14%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2133MT/s        | 1        | 1.14%   |
| Kingston RAM KHX1600C10D3/ 8GB DIMM DDR3 1600MT/s        | 1        | 1.14%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 2400MT/s    | 1        | 1.14%   |
| Kingston RAM 99U5584-010.A00LF 4096MB DIMM DDR3 1866MT/s | 1        | 1.14%   |
| Kingston RAM 99U5474-038.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 1.14%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 1.14%   |
| Kingston RAM 99U5471-057.A00LF 8GB DIMM DDR3 1333MT/s    | 1        | 1.14%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s    | 1        | 1.14%   |
| Kingston RAM 99U5471-047.A00LF 8GB DIMM DDR3 1333MT/s    | 1        | 1.14%   |
| Kingston RAM 99U5471-025.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 1.14%   |
| Kingston RAM 99U5469-045.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 1.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 38       | 55.07%  |
| DDR4    | 11       | 15.94%  |
| SDRAM   | 8        | 11.59%  |
| Unknown | 7        | 10.14%  |
| DDR2    | 5        | 7.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 62       | 91.18%  |
| SODIMM | 6        | 8.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 28       | 37.33%  |
| 2048  | 23       | 30.67%  |
| 8192  | 18       | 24%     |
| 16384 | 4        | 5.33%   |
| 1024  | 2        | 2.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 20       | 27.78%  |
| 1333    | 20       | 27.78%  |
| Unknown | 12       | 16.67%  |
| 2400    | 4        | 5.56%   |
| 800     | 4        | 5.56%   |
| 2667    | 3        | 4.17%   |
| 2666    | 2        | 2.78%   |
| 2133    | 2        | 2.78%   |
| 1867    | 1        | 1.39%   |
| 1866    | 1        | 1.39%   |
| 1067    | 1        | 1.39%   |
| 1066    | 1        | 1.39%   |
| 400     | 1        | 1.39%   |

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
| 0     | 40       | 53.33%  |
| 1     | 31       | 41.33%  |
| 2     | 3        | 4%      |
| 3     | 1        | 1.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 30       | 78.95%  |
| Net/wireless             | 4        | 10.53%  |
| Sound                    | 3        | 7.89%   |
| Firewire controller      | 1        | 2.63%   |

