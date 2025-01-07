BSD in Spain - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for BSD in Spain.

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

Total: 247

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [89ce4b4a9f](https://bsd-hardware.info/?probe=89ce4b4a9f) | Jan 06, 2025 |
| MSI           | MS-B1711                    | [98df812bc4](https://bsd-hardware.info/?probe=98df812bc4) | Jan 03, 2025 |
| MSI           | MS-B1711                    | [c58187f624](https://bsd-hardware.info/?probe=c58187f624) | Jan 03, 2025 |
| AAEON         | UP-APL01 V0.4               | [32312b45f8](https://bsd-hardware.info/?probe=32312b45f8) | Dec 21, 2024 |
| Intel         | J1900                       | [1eabaeb91b](https://bsd-hardware.info/?probe=1eabaeb91b) | Dec 16, 2024 |
| Dell          | 0WR7PY A01                  | [cac8fa73da](https://bsd-hardware.info/?probe=cac8fa73da) | Dec 15, 2024 |
| Unknown       | Unknown                     | [23b03d29a7](https://bsd-hardware.info/?probe=23b03d29a7) | Dec 06, 2024 |
| Unknown       | Unknown                     | [5077b94887](https://bsd-hardware.info/?probe=5077b94887) | Dec 06, 2024 |
| Unknown       | Unknown                     | [d5087399ae](https://bsd-hardware.info/?probe=d5087399ae) | Dec 02, 2024 |
| Unknown       | QDNV01                      | [b61894118e](https://bsd-hardware.info/?probe=b61894118e) | Nov 25, 2024 |
| Unknown       | QDNV01                      | [e70e28cd40](https://bsd-hardware.info/?probe=e70e28cd40) | Nov 21, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [4fd991795f](https://bsd-hardware.info/?probe=4fd991795f) | Nov 20, 2024 |
| Unknown       | Unknown                     | [401a8352cd](https://bsd-hardware.info/?probe=401a8352cd) | Nov 05, 2024 |
| HP            | 8597                        | [a20615c5a0](https://bsd-hardware.info/?probe=a20615c5a0) | Oct 29, 2024 |
| Techvision    | TVI7309X B0                 | [76c5dea6bb](https://bsd-hardware.info/?probe=76c5dea6bb) | Oct 27, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [6c77bc229e](https://bsd-hardware.info/?probe=6c77bc229e) | Oct 24, 2024 |
| Unknown       | Unknown                     | [7d49a8dfcd](https://bsd-hardware.info/?probe=7d49a8dfcd) | Oct 20, 2024 |
| Intel         | SKYBAY                      | [9847be081f](https://bsd-hardware.info/?probe=9847be081f) | Oct 16, 2024 |
| Shenzhen M... | F7BFD                       | [def723c09a](https://bsd-hardware.info/?probe=def723c09a) | Oct 15, 2024 |
| HP            | Compaq Presario CQ50        | [462666f013](https://bsd-hardware.info/?probe=462666f013) | Oct 13, 2024 |
| ECS           | APLD-MINI                   | [47d8c66ac9](https://bsd-hardware.info/?probe=47d8c66ac9) | Oct 07, 2024 |
| PC Engines    | APU                         | [58bd860024](https://bsd-hardware.info/?probe=58bd860024) | Oct 05, 2024 |
| Intel         | DB75EN AAG39650-400         | [800f9bb0b7](https://bsd-hardware.info/?probe=800f9bb0b7) | Sep 29, 2024 |
| Techvision    | TVI7309X B0                 | [42acfbe729](https://bsd-hardware.info/?probe=42acfbe729) | Sep 07, 2024 |
| Dell EMC      | EDGE680-CPU A00             | [4934b78db6](https://bsd-hardware.info/?probe=4934b78db6) | Jul 24, 2024 |
| Unknown       | Unknown                     | [2e77b6eb96](https://bsd-hardware.info/?probe=2e77b6eb96) | Jul 21, 2024 |
| Unknown       | Unknown                     | [0a7faa3d8b](https://bsd-hardware.info/?probe=0a7faa3d8b) | Jul 21, 2024 |
| OEM           | NU93 Series                 | [8eaae8a84d](https://bsd-hardware.info/?probe=8eaae8a84d) | Jun 24, 2024 |
| Gigabyte      | B550 GAMING X V2            | [65d6791029](https://bsd-hardware.info/?probe=65d6791029) | Jun 19, 2024 |
| Protectli     | FW4B Ver                    | [b11c396037](https://bsd-hardware.info/?probe=b11c396037) | Jun 04, 2024 |
| Unknown       | Unknown                     | [06a1266a2e](https://bsd-hardware.info/?probe=06a1266a2e) | May 30, 2024 |
| Unknown       | Unknown                     | [30cc9d07af](https://bsd-hardware.info/?probe=30cc9d07af) | May 07, 2024 |
| MSI           | MS-7097                     | [df5c7407fd](https://bsd-hardware.info/?probe=df5c7407fd) | May 06, 2024 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [6da31bada9](https://bsd-hardware.info/?probe=6da31bada9) | Apr 27, 2024 |
| Unknown       | Unknown                     | [2caa0fe8f7](https://bsd-hardware.info/?probe=2caa0fe8f7) | Apr 26, 2024 |
| Unknown       | Unknown                     | [1d373fbfcd](https://bsd-hardware.info/?probe=1d373fbfcd) | Apr 26, 2024 |
| AZW           | EQ                          | [9225d89862](https://bsd-hardware.info/?probe=9225d89862) | Apr 23, 2024 |
| Unknown       | Unknown                     | [242348310b](https://bsd-hardware.info/?probe=242348310b) | Apr 22, 2024 |
| Intel         | DN2820FYK H24582-201        | [1bc36f8af1](https://bsd-hardware.info/?probe=1bc36f8af1) | Apr 17, 2024 |
| Unknown       | Unknown                     | [d231a9531b](https://bsd-hardware.info/?probe=d231a9531b) | Apr 17, 2024 |
| Gigabyte      | G431-MM0-OT                 | [16c58f7ccb](https://bsd-hardware.info/?probe=16c58f7ccb) | Apr 07, 2024 |
| Gigabyte      | B85M-D3H                    | [3f85beaa54](https://bsd-hardware.info/?probe=3f85beaa54) | Apr 05, 2024 |
| ASRock        | Z790M-ITX WiFi              | [b2bbe7eb8d](https://bsd-hardware.info/?probe=b2bbe7eb8d) | Apr 04, 2024 |
| Unknown       | Unknown                     | [0687b8c8e1](https://bsd-hardware.info/?probe=0687b8c8e1) | Mar 29, 2024 |
| Protectli     | FW4B Ver                    | [0d486d6705](https://bsd-hardware.info/?probe=0d486d6705) | Mar 26, 2024 |
| Protectli     | FW4B Ver                    | [bad44928d7](https://bsd-hardware.info/?probe=bad44928d7) | Mar 25, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [313ab74587](https://bsd-hardware.info/?probe=313ab74587) | Mar 22, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [3a0ef703ef](https://bsd-hardware.info/?probe=3a0ef703ef) | Mar 10, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [88b774a83d](https://bsd-hardware.info/?probe=88b774a83d) | Mar 10, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [9b40b121ec](https://bsd-hardware.info/?probe=9b40b121ec) | Mar 10, 2024 |
| Unknown       | Unknown                     | [e35907b66f](https://bsd-hardware.info/?probe=e35907b66f) | Mar 04, 2024 |
| Gigabyte      | H270M-DS3H-CF               | [05b6d7a915](https://bsd-hardware.info/?probe=05b6d7a915) | Feb 29, 2024 |
| ASRock        | H81M-VG4 R2.0               | [0275a7e6b3](https://bsd-hardware.info/?probe=0275a7e6b3) | Feb 26, 2024 |
| Unknown       | Unknown                     | [d3ed7d1552](https://bsd-hardware.info/?probe=d3ed7d1552) | Feb 24, 2024 |
| ECS           | APLD-MINI                   | [d0d3c5d2c3](https://bsd-hardware.info/?probe=d0d3c5d2c3) | Feb 16, 2024 |
| Unknown       | ITX-M41V                    | [957fb292ad](https://bsd-hardware.info/?probe=957fb292ad) | Feb 06, 2024 |
| Techvision    | TVI7309X B0                 | [fa94c9a549](https://bsd-hardware.info/?probe=fa94c9a549) | Feb 04, 2024 |
| Unknown       | ITX-M41V                    | [3ab7929f1b](https://bsd-hardware.info/?probe=3ab7929f1b) | Feb 02, 2024 |
| YANYU         | R250                        | [93dceedd1f](https://bsd-hardware.info/?probe=93dceedd1f) | Feb 01, 2024 |
| YANYU         | R250                        | [76a55db1e1](https://bsd-hardware.info/?probe=76a55db1e1) | Jan 31, 2024 |
| YANYU         | R250                        | [f6e4c67d9a](https://bsd-hardware.info/?probe=f6e4c67d9a) | Jan 26, 2024 |
| Unknown       | Unknown                     | [2f9d003e12](https://bsd-hardware.info/?probe=2f9d003e12) | Jan 21, 2024 |
| ASRock        | H81M-VG4 R2.0               | [ec9b6a27b9](https://bsd-hardware.info/?probe=ec9b6a27b9) | Jan 18, 2024 |
| ASRock        | H81M-VG4 R2.0               | [bece75e284](https://bsd-hardware.info/?probe=bece75e284) | Jan 14, 2024 |
| Techvision    | TVI7309X B0                 | [766493f0dd](https://bsd-hardware.info/?probe=766493f0dd) | Jan 03, 2024 |
| Unknown       | Unknown                     | [ef2a5b9804](https://bsd-hardware.info/?probe=ef2a5b9804) | Dec 01, 2023 |
| Unknown       | Unknown                     | [d5da0ab59d](https://bsd-hardware.info/?probe=d5da0ab59d) | Dec 01, 2023 |
| YANYU         | R250                        | [74ee81493f](https://bsd-hardware.info/?probe=74ee81493f) | Nov 20, 2023 |
| MSI           | Z170-A PRO                  | [ab9a7eb894](https://bsd-hardware.info/?probe=ab9a7eb894) | Nov 08, 2023 |
| Dell          | 08NPPY A00                  | [42b9e61011](https://bsd-hardware.info/?probe=42b9e61011) | Nov 08, 2023 |
| Gigabyte      | MZBSWAP-00                  | [a01a7d9576](https://bsd-hardware.info/?probe=a01a7d9576) | Nov 06, 2023 |
| Unknown       | Unknown                     | [790368b718](https://bsd-hardware.info/?probe=790368b718) | Nov 03, 2023 |
| Gigabyte      | MZBSWAP-00                  | [d52347dd3d](https://bsd-hardware.info/?probe=d52347dd3d) | Nov 02, 2023 |
| ASUSTek       | MINIPC PN53-G               | [57d8823b4b](https://bsd-hardware.info/?probe=57d8823b4b) | Oct 28, 2023 |
| ASUSTek       | M3A78-CM                    | [a40b6fde47](https://bsd-hardware.info/?probe=a40b6fde47) | Oct 22, 2023 |
| ECS           | APLD-MINI                   | [d063eeb7d5](https://bsd-hardware.info/?probe=d063eeb7d5) | Oct 08, 2023 |
| Unknown       | Unknown                     | [1aa25f04a8](https://bsd-hardware.info/?probe=1aa25f04a8) | Oct 07, 2023 |
| Intel         | SKYBAY                      | [9d49471591](https://bsd-hardware.info/?probe=9d49471591) | Aug 29, 2023 |
| YANYU         | R250                        | [69dbe1a014](https://bsd-hardware.info/?probe=69dbe1a014) | Aug 24, 2023 |
| YANYU         | R250                        | [95a37ee143](https://bsd-hardware.info/?probe=95a37ee143) | Aug 06, 2023 |
| Techvision    | TVI7309X B0                 | [6bd995374a](https://bsd-hardware.info/?probe=6bd995374a) | Jul 30, 2023 |
| Gigabyte      | A320M-H-CF                  | [d1a2b99edc](https://bsd-hardware.info/?probe=d1a2b99edc) | Jul 28, 2023 |
| Techvision    | TVI7309X B0                 | [38255b17fe](https://bsd-hardware.info/?probe=38255b17fe) | Jul 19, 2023 |
| Unknown       | Unknown                     | [b44e00cdf3](https://bsd-hardware.info/?probe=b44e00cdf3) | Jun 25, 2023 |
| ASUSTek       | P5K PRO                     | [f0b283fdaf](https://bsd-hardware.info/?probe=f0b283fdaf) | Jun 19, 2023 |
| ASUSTek       | PRIME B460M-A               | [4c8047dca3](https://bsd-hardware.info/?probe=4c8047dca3) | May 19, 2023 |
| Lenovo        | 0B98401 PRO                 | [c61a0b39fa](https://bsd-hardware.info/?probe=c61a0b39fa) | May 09, 2023 |
| Unknown       | Unknown                     | [678ab85729](https://bsd-hardware.info/?probe=678ab85729) | May 08, 2023 |
| Unknown       | Unknown                     | [d574fd446b](https://bsd-hardware.info/?probe=d574fd446b) | May 08, 2023 |
| Unknown       | Unknown                     | [21b338db1b](https://bsd-hardware.info/?probe=21b338db1b) | Apr 30, 2023 |
| Gigabyte      | H81M-S2PH                   | [b7ec959c9f](https://bsd-hardware.info/?probe=b7ec959c9f) | Apr 13, 2023 |
| Techvision    | TVI7309X B0                 | [64b66f1fed](https://bsd-hardware.info/?probe=64b66f1fed) | Apr 11, 2023 |
| Techvision    | TVI7309X B0                 | [9ee2a1ee72](https://bsd-hardware.info/?probe=9ee2a1ee72) | Apr 11, 2023 |
| ASUSTek       | PRIME B250M-A               | [0747d0a699](https://bsd-hardware.info/?probe=0747d0a699) | Apr 11, 2023 |
| Techvision    | TVI7309X B0                 | [e3efaa8d57](https://bsd-hardware.info/?probe=e3efaa8d57) | Apr 09, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [ca6badc637](https://bsd-hardware.info/?probe=ca6badc637) | Mar 30, 2023 |
| Unknown       | Unknown                     | [88455ed9e7](https://bsd-hardware.info/?probe=88455ed9e7) | Mar 18, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [eb6b70b310](https://bsd-hardware.info/?probe=eb6b70b310) | Mar 16, 2023 |
| HP            | 3398                        | [b14de43688](https://bsd-hardware.info/?probe=b14de43688) | Mar 15, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [cb6b586564](https://bsd-hardware.info/?probe=cb6b586564) | Mar 14, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | [34c4bab715](https://bsd-hardware.info/?probe=34c4bab715) | Mar 14, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [b337baf50e](https://bsd-hardware.info/?probe=b337baf50e) | Mar 13, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [0eeb0661dd](https://bsd-hardware.info/?probe=0eeb0661dd) | Mar 12, 2023 |
| MSI           | B450-A PRO                  | [b2d29a5bbc](https://bsd-hardware.info/?probe=b2d29a5bbc) | Mar 12, 2023 |
| HP            | 8768 A                      | [5ab1dadbab](https://bsd-hardware.info/?probe=5ab1dadbab) | Mar 12, 2023 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [c34d5e6357](https://bsd-hardware.info/?probe=c34d5e6357) | Feb 17, 2023 |
| YANYU         | R250                        | [24ebc43209](https://bsd-hardware.info/?probe=24ebc43209) | Feb 12, 2023 |
| Gigabyte      | H510M S2H V2                | [85628154a2](https://bsd-hardware.info/?probe=85628154a2) | Feb 05, 2023 |
| ASUSTek       | PRIME B450M-A               | [7c56590eaa](https://bsd-hardware.info/?probe=7c56590eaa) | Feb 03, 2023 |
| HP            | 1496                        | [fae90baa23](https://bsd-hardware.info/?probe=fae90baa23) | Jan 31, 2023 |
| ASUSTek       | PRIME B460M-A               | [a6b109939f](https://bsd-hardware.info/?probe=a6b109939f) | Jan 28, 2023 |
| YANYU         | R250                        | [866e67f059](https://bsd-hardware.info/?probe=866e67f059) | Jan 27, 2023 |
| MW            | GMLK-2_5G4L                 | [142b3ad8d6](https://bsd-hardware.info/?probe=142b3ad8d6) | Jan 20, 2023 |
| Dell          | 0WMJ54 A01                  | [8580d62bf3](https://bsd-hardware.info/?probe=8580d62bf3) | Jan 19, 2023 |
| Lenovo        | H30-05 90BJ0085SP           | [1424b3641c](https://bsd-hardware.info/?probe=1424b3641c) | Jan 18, 2023 |
| Lenovo        | H30-05 90BJ0085SP           | [d491694079](https://bsd-hardware.info/?probe=d491694079) | Jan 18, 2023 |
| Intel         | SKYBAY                      | [21ed0daf1c](https://bsd-hardware.info/?probe=21ed0daf1c) | Jan 08, 2023 |
| YANYU         | R250                        | [7ea489eae6](https://bsd-hardware.info/?probe=7ea489eae6) | Jan 06, 2023 |
| YANYU         | R250                        | [bb364271b2](https://bsd-hardware.info/?probe=bb364271b2) | Dec 05, 2022 |
| YANYU         | R250                        | [0be0925e5b](https://bsd-hardware.info/?probe=0be0925e5b) | Nov 27, 2022 |
| HP            | 3048h                       | [3f43816a5d](https://bsd-hardware.info/?probe=3f43816a5d) | Nov 25, 2022 |
| Lenovo        | ThinkStation S30 0569A93    | [dd545fb588](https://bsd-hardware.info/?probe=dd545fb588) | Nov 25, 2022 |
| MSI           | A320M-A PRO                 | [fc71b97d90](https://bsd-hardware.info/?probe=fc71b97d90) | Nov 24, 2022 |
| ASUSTek       | PRIME A320M-K               | [9701222998](https://bsd-hardware.info/?probe=9701222998) | Nov 23, 2022 |
| HP            | 1998                        | [9239fe7437](https://bsd-hardware.info/?probe=9239fe7437) | Nov 15, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [443891740b](https://bsd-hardware.info/?probe=443891740b) | Nov 13, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [e5b3cb0bcd](https://bsd-hardware.info/?probe=e5b3cb0bcd) | Nov 12, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [5dcd51844e](https://bsd-hardware.info/?probe=5dcd51844e) | Nov 09, 2022 |
| YANYU         | R250                        | [f39d55e42d](https://bsd-hardware.info/?probe=f39d55e42d) | Oct 28, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [079830f938](https://bsd-hardware.info/?probe=079830f938) | Oct 24, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [2fa4641b0e](https://bsd-hardware.info/?probe=2fa4641b0e) | Oct 24, 2022 |
| YANYU         | H67SL                       | [373902d38b](https://bsd-hardware.info/?probe=373902d38b) | Oct 07, 2022 |
| Dell          | 0TDG4V A00                  | [cc92be7e52](https://bsd-hardware.info/?probe=cc92be7e52) | Sep 25, 2022 |
| ASUSTek       | All Series                  | [ab3b339cf0](https://bsd-hardware.info/?probe=ab3b339cf0) | Sep 24, 2022 |
| Gigabyte      | Z370P D3-CF                 | [10f0cfa344](https://bsd-hardware.info/?probe=10f0cfa344) | Sep 15, 2022 |
| HP            | 213D A01                    | [54288c6759](https://bsd-hardware.info/?probe=54288c6759) | Sep 11, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | [7c9c1db9d7](https://bsd-hardware.info/?probe=7c9c1db9d7) | Sep 10, 2022 |
| Dell          | 00V62H A01                  | [e7dc9cc5ee](https://bsd-hardware.info/?probe=e7dc9cc5ee) | Aug 28, 2022 |
| YANYU         | R250                        | [c4f1ec0d5b](https://bsd-hardware.info/?probe=c4f1ec0d5b) | Aug 27, 2022 |
| YANYU         | H67SL                       | [57afa0c5d1](https://bsd-hardware.info/?probe=57afa0c5d1) | Aug 25, 2022 |
| ASUSTek       | PRIME B460M-A               | [21fed03fa2](https://bsd-hardware.info/?probe=21fed03fa2) | Aug 24, 2022 |
| ASUSTek       | PRIME B460M-A               | [48210e4d2a](https://bsd-hardware.info/?probe=48210e4d2a) | Aug 24, 2022 |
| Lenovo        | ThinkCentre M91p 4512A47    | [3556794570](https://bsd-hardware.info/?probe=3556794570) | Aug 23, 2022 |
| YANYU         | R250                        | [bd7edcafbe](https://bsd-hardware.info/?probe=bd7edcafbe) | Aug 22, 2022 |
| MW            | GMLK-2_5G4L                 | [2325f41325](https://bsd-hardware.info/?probe=2325f41325) | Aug 20, 2022 |
| HP            | 213D A01                    | [4b231023a1](https://bsd-hardware.info/?probe=4b231023a1) | Aug 16, 2022 |
| YANYU         | R250                        | [4552b74317](https://bsd-hardware.info/?probe=4552b74317) | Aug 12, 2022 |
| Unknown       | Unknown                     | [c0daba1c48](https://bsd-hardware.info/?probe=c0daba1c48) | Aug 09, 2022 |
| YANYU         | R250                        | [ffad8eb019](https://bsd-hardware.info/?probe=ffad8eb019) | Aug 07, 2022 |
| MW            | GMLK-2_5G4L                 | [b2858de568](https://bsd-hardware.info/?probe=b2858de568) | Aug 06, 2022 |
| Unknown       | Unknown                     | [ea08102a81](https://bsd-hardware.info/?probe=ea08102a81) | Aug 06, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | [50a0d392e7](https://bsd-hardware.info/?probe=50a0d392e7) | Aug 06, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | [f2836f4a6c](https://bsd-hardware.info/?probe=f2836f4a6c) | Aug 01, 2022 |
| Wistron       | ProLiant ML110 G6           | [091fe7ca40](https://bsd-hardware.info/?probe=091fe7ca40) | Jul 28, 2022 |
| HP            | ProLiant ML310e Gen8 v2     | [6cdc79a36f](https://bsd-hardware.info/?probe=6cdc79a36f) | Jul 22, 2022 |
| ASUSTek       | Maximus VIII HERO           | [051f604f9a](https://bsd-hardware.info/?probe=051f604f9a) | Jul 21, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [a96e41f99e](https://bsd-hardware.info/?probe=a96e41f99e) | Jul 20, 2022 |
| PC Engines    | APU2                        | [c84cb618c0](https://bsd-hardware.info/?probe=c84cb618c0) | Jul 17, 2022 |
| ASUSTek       | Z87M-PLUS                   | [5e51d228ec](https://bsd-hardware.info/?probe=5e51d228ec) | Jun 21, 2022 |
| Intel         | SKYBAY                      | [e9dafa8427](https://bsd-hardware.info/?probe=e9dafa8427) | Jun 10, 2022 |
| Intel         | SKYBAY                      | [7a88f52138](https://bsd-hardware.info/?probe=7a88f52138) | Jun 01, 2022 |
| Unknown       | Unknown                     | [938866fb80](https://bsd-hardware.info/?probe=938866fb80) | May 21, 2022 |
| OEM           | NU93 Series                 | [e558435c70](https://bsd-hardware.info/?probe=e558435c70) | Apr 12, 2022 |
| OEM           | NU93 Series                 | [505cbbac5d](https://bsd-hardware.info/?probe=505cbbac5d) | Apr 12, 2022 |
| ASUSTek       | CP6230                      | [a407409700](https://bsd-hardware.info/?probe=a407409700) | Apr 11, 2022 |
| HP            | 1998                        | [06f0a28858](https://bsd-hardware.info/?probe=06f0a28858) | Apr 10, 2022 |
| HP            | 213D A01                    | [b8b1c05451](https://bsd-hardware.info/?probe=b8b1c05451) | Mar 25, 2022 |
| Unknown       | Unknown                     | [f25a608944](https://bsd-hardware.info/?probe=f25a608944) | Mar 19, 2022 |
| HP            | 213D A01                    | [88eb5a2df5](https://bsd-hardware.info/?probe=88eb5a2df5) | Mar 18, 2022 |
| ASUSTek       | P5K PRO                     | [fbde5657e8](https://bsd-hardware.info/?probe=fbde5657e8) | Mar 11, 2022 |
| HP            | 8054                        | [86b6b8373c](https://bsd-hardware.info/?probe=86b6b8373c) | Mar 08, 2022 |
| HP            | 8054                        | [00078554d2](https://bsd-hardware.info/?probe=00078554d2) | Mar 08, 2022 |
| Unknown       | YL-SKUL6-7 Series           | [6f969a5cf2](https://bsd-hardware.info/?probe=6f969a5cf2) | Feb 27, 2022 |
| ASRock        | TRX40 Taichi                | [a2df68e1d1](https://bsd-hardware.info/?probe=a2df68e1d1) | Feb 26, 2022 |
| Medion        | H61H2-LM3                   | [beb12f2884](https://bsd-hardware.info/?probe=beb12f2884) | Feb 23, 2022 |
| HP            | 1998                        | [485d417a2e](https://bsd-hardware.info/?probe=485d417a2e) | Feb 23, 2022 |
| HP            | 213D A01                    | [1506ef3d9c](https://bsd-hardware.info/?probe=1506ef3d9c) | Feb 17, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [eddeb5c246](https://bsd-hardware.info/?probe=eddeb5c246) | Feb 13, 2022 |
| Pegatron      | 2AD5                        | [84219d3418](https://bsd-hardware.info/?probe=84219d3418) | Feb 10, 2022 |
| Pegatron      | 2AD5                        | [2fe214dc2b](https://bsd-hardware.info/?probe=2fe214dc2b) | Feb 01, 2022 |
| Intel         | MAHOBAY                     | [020a9098cd](https://bsd-hardware.info/?probe=020a9098cd) | Feb 01, 2022 |
| Unknown       | YL-1900L4-V2                | [fccaf1b541](https://bsd-hardware.info/?probe=fccaf1b541) | Jan 31, 2022 |
| ECS           | APLD-MINI                   | [e64118d206](https://bsd-hardware.info/?probe=e64118d206) | Jan 30, 2022 |
| HP            | 213D A01                    | [8419869d89](https://bsd-hardware.info/?probe=8419869d89) | Jan 29, 2022 |
| ASUSTek       | P7H55-M LX                  | [72630c073d](https://bsd-hardware.info/?probe=72630c073d) | Jan 27, 2022 |
| HP            | 1998                        | [b59dbcdc9c](https://bsd-hardware.info/?probe=b59dbcdc9c) | Jan 23, 2022 |
| MSI           | A320M-A PRO MAX             | [34805f5f83](https://bsd-hardware.info/?probe=34805f5f83) | Jan 17, 2022 |
| Unknown       | YL-1900L4-V2                | [ec13024551](https://bsd-hardware.info/?probe=ec13024551) | Jan 12, 2022 |
| ASRock        | N3700-ITX                   | [fb058e0b37](https://bsd-hardware.info/?probe=fb058e0b37) | Jan 03, 2022 |
| ASRock        | N3700-ITX                   | [dda4b4e02b](https://bsd-hardware.info/?probe=dda4b4e02b) | Dec 29, 2021 |
| AMI           | PEISIA E3845 VER1.0         | [d19f149583](https://bsd-hardware.info/?probe=d19f149583) | Dec 26, 2021 |
| OEM           | AR-B5800                    | [90f43e277a](https://bsd-hardware.info/?probe=90f43e277a) | Dec 20, 2021 |
| Unknown       | Unknown                     | [bb3183702b](https://bsd-hardware.info/?probe=bb3183702b) | Dec 17, 2021 |
| ShenZhen M... | 3865U-6L                    | [09d0d26857](https://bsd-hardware.info/?probe=09d0d26857) | Dec 13, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [6a1100cfdb](https://bsd-hardware.info/?probe=6a1100cfdb) | Dec 11, 2021 |
| OEM           | AR-B5800                    | [ec11b97e0e](https://bsd-hardware.info/?probe=ec11b97e0e) | Dec 08, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [4cd5e5166a](https://bsd-hardware.info/?probe=4cd5e5166a) | Nov 27, 2021 |
| ASUSTek       | Rampage Formula             | [09f67a9982](https://bsd-hardware.info/?probe=09f67a9982) | Nov 09, 2021 |
| ASUSTek       | Rampage Formula             | [183f1a8d62](https://bsd-hardware.info/?probe=183f1a8d62) | Nov 08, 2021 |
| ECS           | APLD-MINI                   | [402d7bc95c](https://bsd-hardware.info/?probe=402d7bc95c) | Nov 07, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | [9959c0900a](https://bsd-hardware.info/?probe=9959c0900a) | Oct 23, 2021 |
| ASUSTek       | D940MX                      | [4e798f3ef0](https://bsd-hardware.info/?probe=4e798f3ef0) | Oct 10, 2021 |
| ASRock        | J5005-ITX                   | [a7f333eedb](https://bsd-hardware.info/?probe=a7f333eedb) | Oct 10, 2021 |
| Medion        | H61H2-LM3                   | [67ed0f639c](https://bsd-hardware.info/?probe=67ed0f639c) | Oct 10, 2021 |
| ASRock        | J5005-ITX                   | [6589a62805](https://bsd-hardware.info/?probe=6589a62805) | Oct 08, 2021 |
| Medion        | H61H2-LM3                   | [7a42009a08](https://bsd-hardware.info/?probe=7a42009a08) | Sep 02, 2021 |
| Medion        | H61H2-LM3                   | [eb81abe401](https://bsd-hardware.info/?probe=eb81abe401) | Sep 02, 2021 |
| Intel         | CARLOW                      | [035b6b4b42](https://bsd-hardware.info/?probe=035b6b4b42) | Sep 02, 2021 |
| ShenZhen M... | 3865U-6L                    | [ebf562c2d6](https://bsd-hardware.info/?probe=ebf562c2d6) | Sep 01, 2021 |
| Unknown       | Unknown                     | [5c37b14dd5](https://bsd-hardware.info/?probe=5c37b14dd5) | Aug 27, 2021 |
| Gigabyte      | GA-7VT600                   | [83b86f3e8c](https://bsd-hardware.info/?probe=83b86f3e8c) | Aug 23, 2021 |
| Lenovo        | 0B98401 PRO                 | [e2f0f95779](https://bsd-hardware.info/?probe=e2f0f95779) | Jul 18, 2021 |
| Lenovo        | 0B98401 PRO                 | [7727ec2d09](https://bsd-hardware.info/?probe=7727ec2d09) | Jul 07, 2021 |
| Gigabyte      | 965P-DS4                    | [c4d4537787](https://bsd-hardware.info/?probe=c4d4537787) | Jul 02, 2021 |
| ASUSTek       | Rampage Formula             | [477a2a84f4](https://bsd-hardware.info/?probe=477a2a84f4) | Jun 24, 2021 |
| Unknown       | Unknown                     | [3e8940224f](https://bsd-hardware.info/?probe=3e8940224f) | Jun 13, 2021 |
| Unknown       | Unknown                     | [9ff0fb7df4](https://bsd-hardware.info/?probe=9ff0fb7df4) | May 01, 2021 |
| Unknown       | Unknown                     | [2acd0848c8](https://bsd-hardware.info/?probe=2acd0848c8) | May 01, 2021 |
| Lenovo        | 0B98401 PRO                 | [0d584c2a00](https://bsd-hardware.info/?probe=0d584c2a00) | Apr 26, 2021 |
| ASUSTek       | Maximus VIII HERO           | [7f9cdc62a2](https://bsd-hardware.info/?probe=7f9cdc62a2) | Apr 14, 2021 |
| Unknown       | Unknown                     | [f49d7529c0](https://bsd-hardware.info/?probe=f49d7529c0) | Apr 11, 2021 |
| Unknown       | Unknown                     | [08da04fdf6](https://bsd-hardware.info/?probe=08da04fdf6) | Apr 09, 2021 |
| Medion        | H61H2-LM3                   | [6483c8390f](https://bsd-hardware.info/?probe=6483c8390f) | Mar 31, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | [a03927cc2e](https://bsd-hardware.info/?probe=a03927cc2e) | Mar 06, 2021 |
| Medion        | H61H2-LM3                   | [01df19257a](https://bsd-hardware.info/?probe=01df19257a) | Mar 05, 2021 |
| ASUSTek       | Rampage Formula             | [3d2377b221](https://bsd-hardware.info/?probe=3d2377b221) | Mar 03, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [ac108deea2](https://bsd-hardware.info/?probe=ac108deea2) | Feb 28, 2021 |
| Acer          | Aspire XC-115               | [95f63df64d](https://bsd-hardware.info/?probe=95f63df64d) | Feb 21, 2021 |
| YANYU         | H67SL                       | [d8d30a13fa](https://bsd-hardware.info/?probe=d8d30a13fa) | Feb 14, 2021 |
| HP            | 2B17                        | [572bf634a8](https://bsd-hardware.info/?probe=572bf634a8) | Feb 12, 2021 |
| HP            | 8055                        | [8ecc5bbb55](https://bsd-hardware.info/?probe=8ecc5bbb55) | Feb 12, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [a49ff2b77a](https://bsd-hardware.info/?probe=a49ff2b77a) | Feb 11, 2021 |
| Medion        | H81H3-EM2 H81EM2W08.308     | [9958f514c9](https://bsd-hardware.info/?probe=9958f514c9) | Feb 10, 2021 |
| ASRock        | H270M Pro4                  | [37af53e334](https://bsd-hardware.info/?probe=37af53e334) | Feb 10, 2021 |
| Acer          | Aspire X1700                | [06dc1753ef](https://bsd-hardware.info/?probe=06dc1753ef) | Feb 10, 2021 |
| Acer          | Aspire X1700                | [6886acf351](https://bsd-hardware.info/?probe=6886acf351) | Feb 10, 2021 |
| HP            | ProLiant MicroServer Gen... | [415023d5a1](https://bsd-hardware.info/?probe=415023d5a1) | Jan 10, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8227b36f77](https://bsd-hardware.info/?probe=8227b36f77) | Oct 31, 2020 |
| eMachines     | EL1200                      | [ae59908738](https://bsd-hardware.info/?probe=ae59908738) | Oct 30, 2020 |
| Acer          | Veriton M6610G              | [7dd00aa8b1](https://bsd-hardware.info/?probe=7dd00aa8b1) | Oct 30, 2020 |
| eMachines     | EL1200                      | [5bc54351be](https://bsd-hardware.info/?probe=5bc54351be) | Oct 30, 2020 |
| ECS           | BSWI-D2                     | [c5b07f5c31](https://bsd-hardware.info/?probe=c5b07f5c31) | Oct 30, 2020 |
| Lenovo        | SHARKBAY WIN                | [53feb1fec6](https://bsd-hardware.info/?probe=53feb1fec6) | Oct 19, 2020 |
| Acer          | Aspire XC-605               | [d8688fe23f](https://bsd-hardware.info/?probe=d8688fe23f) | Aug 24, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | [1dbb703a8b](https://bsd-hardware.info/?probe=1dbb703a8b) | Aug 23, 2020 |
| Gigabyte      | B450M DS3H-CF               | [c7c50d64cf](https://bsd-hardware.info/?probe=c7c50d64cf) | May 29, 2020 |
| ASUSTek       | PRIME A320M-K               | [a49cf5c20b](https://bsd-hardware.info/?probe=a49cf5c20b) | May 28, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| helloSystem 0.8.1 | 11       | 5.58%   |
| helloSystem 0.7.0 | 11       | 5.58%   |
| OPNsense 22.1     | 7        | 3.55%   |
| helloSystem 0.4.0 | 7        | 3.55%   |
| helloSystem 0.8.0 | 6        | 3.05%   |
| FreeBSD 13.1      | 5        | 2.54%   |
| OPNsense 24.7.7   | 4        | 2.03%   |
| OPNsense 24.1.6   | 4        | 2.03%   |
| OPNsense 23.7.7   | 4        | 2.03%   |
| OPNsense 23.7.12  | 4        | 2.03%   |
| OPNsense 21.7.7   | 4        | 2.03%   |
| OpenBSD 6.8       | 4        | 2.03%   |
| OPNsense 24.7.10  | 3        | 1.52%   |
| OPNsense 24.1.4   | 3        | 1.52%   |
| OPNsense 24.1.2   | 3        | 1.52%   |
| OPNsense 21.7.1   | 3        | 1.52%   |
| helloSystem 0.6.0 | 3        | 1.52%   |
| OPNsense 24.7.9   | 2        | 1.02%   |
| OPNsense 24.7.5   | 2        | 1.02%   |
| OPNsense 24.1.8   | 2        | 1.02%   |
| OPNsense 24.1     | 2        | 1.02%   |
| OPNsense 23.7.2   | 2        | 1.02%   |
| OPNsense 23.1.7   | 2        | 1.02%   |
| OPNsense 23.1     | 2        | 1.02%   |
| OPNsense 22.7.9   | 2        | 1.02%   |
| OPNsense 22.7.6   | 2        | 1.02%   |
| OPNsense 22.7.4   | 2        | 1.02%   |
| OPNsense 22.7.2   | 2        | 1.02%   |
| OPNsense 22.7.11  | 2        | 1.02%   |
| OPNsense 22.7.10  | 2        | 1.02%   |
| OPNsense 22.7.1   | 2        | 1.02%   |
| OPNsense 22.1.5   | 2        | 1.02%   |
| OPNsense 22.1.3   | 2        | 1.02%   |
| OPNsense 22.1.10  | 2        | 1.02%   |
| OPNsense 22.1.1   | 2        | 1.02%   |
| OPNsense 21.7.3   | 2        | 1.02%   |
| OPNsense 21.1.7   | 2        | 1.02%   |
| OpenBSD 7.6       | 2        | 1.02%   |
| OpenBSD 7.2       | 2        | 1.02%   |
| OpenBSD 7.1       | 2        | 1.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 65       | 46.43%  |
| helloSystem | 38       | 27.14%  |
| FreeBSD     | 19       | 13.57%  |
| OpenBSD     | 12       | 8.57%   |
| NetBSD      | 3        | 2.14%   |
| TrueNAS     | 1        | 0.71%   |
| GhostBSD    | 1        | 0.71%   |
| DragonFly   | 1        | 0.71%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 136      | 97.84%  |
| i386  | 2        | 1.44%   |
| arm64 | 1        | 0.72%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 76       | 54.29%  |
| helloDesktop | 45       | 32.14%  |
| XFCE         | 4        | 2.86%   |
| fvwm         | 4        | 2.86%   |
| MATE         | 3        | 2.14%   |
| GNOME        | 3        | 2.14%   |
| TWM          | 1        | 0.71%   |
| LXQt         | 1        | 0.71%   |
| KDE5         | 1        | 0.71%   |
| i3           | 1        | 0.71%   |
| Fluxbox      | 1        | 0.71%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 77       | 55.4%   |
| X11     | 62       | 44.6%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 91       | 65%     |
| SLiM    | 41       | 29.29%  |
| LightDM | 4        | 2.86%   |
| SDDM    | 2        | 1.43%   |
| GDM     | 2        | 1.43%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 86       | 59.72%  |
| en_US            | 23       | 15.97%  |
| C                | 16       | 11.11%  |
| es_ES            | 12       | 8.33%   |
| fr_FR            | 4        | 2.78%   |
| fr               | 1        | 0.69%   |
| es_ES.ISO8859-15 | 1        | 0.69%   |
| es               | 1        | 0.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 119      | 85%     |
| BIOS | 21       | 15%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Zfs     | 67       | 45.58%  |
| Ufs     | 46       | 31.29%  |
| Cd9660  | 20       | 13.61%  |
| Ffs     | 12       | 8.16%   |
| Hammer2 | 1        | 0.68%   |
| Unknown | 1        | 0.68%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 125      | 89.29%  |
| MBR     | 12       | 8.57%   |
| Unknown | 3        | 2.14%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 23       | 16.55%  |
| Unknown                              | 15       | 10.79%  |
| Hewlett-Packard                      | 14       | 10.07%  |
| Gigabyte Technology                  | 14       | 10.07%  |
| MSI                                  | 8        | 5.76%   |
| ASRock                               | 8        | 5.76%   |
| Lenovo                               | 7        | 5.04%   |
| Intel                                | 6        | 4.32%   |
| Fujitsu                              | 6        | 4.32%   |
| Dell                                 | 5        | 3.6%    |
| YANYU                                | 4        | 2.88%   |
| Techvision                           | 4        | 2.88%   |
| Acer                                 | 4        | 2.88%   |
| PC Engines                           | 2        | 1.44%   |
| OEM                                  | 2        | 1.44%   |
| Medion                               | 2        | 1.44%   |
| ECS                                  | 2        | 1.44%   |
| Wistron                              | 1        | 0.72%   |
| ShenZhen MinWin Technology           | 1        | 0.72%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.72%   |
| Seeed Studio                         | 1        | 0.72%   |
| Protectli                            | 1        | 0.72%   |
| Pegatron                             | 1        | 0.72%   |
| MW                                   | 1        | 0.72%   |
| Fujitsu Siemens                      | 1        | 0.72%   |
| eMachines                            | 1        | 0.72%   |
| Dell EMC                             | 1        | 0.72%   |
| AZW                                  | 1        | 0.72%   |
| AMI                                  | 1        | 0.72%   |
| AAEON                                | 1        | 0.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Unknown                                           | 15       | 10.79%  |
| Techvision TVI7309X                               | 4        | 2.88%   |
| Fujitsu FUTRO S920                                | 3        | 2.16%   |
| ASUS All Series                                   | 3        | 2.16%   |
| YANYU R250                                        | 2        | 1.44%   |
| YANYU H67SL                                       | 2        | 1.44%   |
| HP EliteDesk 700 G1 SFF                           | 2        | 1.44%   |
| ASUS PRIME A320M-K                                | 2        | 1.44%   |
| ASRock N3700-ITX                                  | 2        | 1.44%   |
| ASRock H81M-VG4 R2.0                              | 2        | 1.44%   |
| Wistron ProLiant ML110 G6                         | 1        | 0.72%   |
| ShenZhen MinWin 3865U-6L                          | 1        | 0.72%   |
| Shenzhen Meigao Electronic Equipment Venus series | 1        | 0.72%   |
| Seeed Studio ODYSSEY-X86J4105                     | 1        | 0.72%   |
| Protectli FW4B                                    | 1        | 0.72%   |
| Pegatron Elite 7500 Series MT                     | 1        | 0.72%   |
| PC Engines APU2                                   | 1        | 0.72%   |
| PC Engines APU                                    | 1        | 0.72%   |
| OEM NU93 Series                                   | 1        | 0.72%   |
| OEM AR-B5800                                      | 1        | 0.72%   |
| MW GMLK-2_5G4L                                    | 1        | 0.72%   |
| MSI MS-7C91                                       | 1        | 0.72%   |
| MSI MS-7C52                                       | 1        | 0.72%   |
| MSI MS-7C51                                       | 1        | 0.72%   |
| MSI MS-7C09                                       | 1        | 0.72%   |
| MSI MS-7B86                                       | 1        | 0.72%   |
| MSI MS-7971                                       | 1        | 0.72%   |
| MSI MS-7097                                       | 1        | 0.72%   |
| MSI Cubi N 8GL (MS-B171)                          | 1        | 0.72%   |
| Medion H81H3-EM2                                  | 1        | 0.72%   |
| Medion H61H2-LM3                                  | 1        | 0.72%   |
| Lenovo ThinkStation S30 0569A93                   | 1        | 0.72%   |
| Lenovo ThinkCentre M93p 10AAS1MD00                | 1        | 0.72%   |
| Lenovo ThinkCentre M93p 10AAA0WGUK                | 1        | 0.72%   |
| Lenovo ThinkCentre M91p 4512A47                   | 1        | 0.72%   |
| Lenovo ThinkCentre M710s 10M8S0FW00               | 1        | 0.72%   |
| Lenovo ThinkCentre E73 10AU003FUK                 | 1        | 0.72%   |
| Lenovo H30-05 90BJ0085SP                          | 1        | 0.72%   |
| Intel SKYBAY                                      | 1        | 0.72%   |
| Intel MAHOBAY                                     | 1        | 0.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Unknown                                    | 15       | 10.79%  |
| ASUS PRIME                                 | 6        | 4.32%   |
| Lenovo ThinkCentre                         | 5        | 3.6%    |
| Techvision TVI7309X                        | 4        | 2.88%   |
| HP EliteDesk                               | 4        | 2.88%   |
| HP Compaq                                  | 4        | 2.88%   |
| Dell OptiPlex                              | 4        | 2.88%   |
| Fujitsu FUTRO                              | 3        | 2.16%   |
| Fujitsu ESPRIMO                            | 3        | 2.16%   |
| ASUS All                                   | 3        | 2.16%   |
| Acer Aspire                                | 3        | 2.16%   |
| YANYU R250                                 | 2        | 1.44%   |
| YANYU H67SL                                | 2        | 1.44%   |
| HP ProLiant                                | 2        | 1.44%   |
| ASUS TUF                                   | 2        | 1.44%   |
| ASUS M5A78L-M                              | 2        | 1.44%   |
| ASRock N3700-ITX                           | 2        | 1.44%   |
| ASRock H81M-VG4                            | 2        | 1.44%   |
| Wistron ProLiant                           | 1        | 0.72%   |
| ShenZhen MinWin 3865U-6L                   | 1        | 0.72%   |
| Shenzhen Meigao Electronic Equipment Venus | 1        | 0.72%   |
| Seeed Studio ODYSSEY-X86J4105              | 1        | 0.72%   |
| Protectli FW4B                             | 1        | 0.72%   |
| Pegatron Elite                             | 1        | 0.72%   |
| PC Engines APU2                            | 1        | 0.72%   |
| PC Engines APU                             | 1        | 0.72%   |
| OEM NU93                                   | 1        | 0.72%   |
| OEM AR-B5800                               | 1        | 0.72%   |
| MW GMLK-2                                  | 1        | 0.72%   |
| MSI MS-7C91                                | 1        | 0.72%   |
| MSI MS-7C52                                | 1        | 0.72%   |
| MSI MS-7C51                                | 1        | 0.72%   |
| MSI MS-7C09                                | 1        | 0.72%   |
| MSI MS-7B86                                | 1        | 0.72%   |
| MSI MS-7971                                | 1        | 0.72%   |
| MSI MS-7097                                | 1        | 0.72%   |
| MSI Cubi                                   | 1        | 0.72%   |
| Medion H81H3-EM2                           | 1        | 0.72%   |
| Medion H61H2-LM3                           | 1        | 0.72%   |
| Lenovo ThinkStation                        | 1        | 0.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2014    | 18       | 12.95%  |
| 2018    | 12       | 8.63%   |
| 2020    | 11       | 7.91%   |
| 2023    | 10       | 7.19%   |
| 2019    | 10       | 7.19%   |
| 2017    | 10       | 7.19%   |
| 2022    | 9        | 6.47%   |
| 2015    | 9        | 6.47%   |
| 2013    | 8        | 5.76%   |
| 2021    | 6        | 4.32%   |
| 2016    | 6        | 4.32%   |
| 2012    | 6        | 4.32%   |
| 2011    | 6        | 4.32%   |
| 2010    | 5        | 3.6%    |
| 2009    | 3        | 2.16%   |
| 2008    | 3        | 2.16%   |
| Unknown | 3        | 2.16%   |
| 2024    | 1        | 0.72%   |
| 2006    | 1        | 0.72%   |
| 2005    | 1        | 0.72%   |
| 2003    | 1        | 0.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 139      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 137      | 98.56%  |
| Yes  | 2        | 1.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 55       | 38.73%  |
| 16.01-24.0  | 32       | 22.54%  |
| 4.01-8.0    | 20       | 14.08%  |
| 32.01-64.0  | 17       | 11.97%  |
| 64.01-256.0 | 5        | 3.52%   |
| 3.01-4.0    | 4        | 2.82%   |
| 2.01-3.0    | 4        | 2.82%   |
| 1.01-2.0    | 3        | 2.11%   |
| 0.51-1.0    | 1        | 0.7%    |
| 0.01-0.5    | 1        | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 63       | 43.75%  |
| 0.51-1.0   | 50       | 34.72%  |
| 1.01-2.0   | 17       | 11.81%  |
| 3.01-4.0   | 5        | 3.47%   |
| 0          | 3        | 2.08%   |
| Unknown    | 3        | 2.08%   |
| 4.01-8.0   | 1        | 0.69%   |
| 24.01-32.0 | 1        | 0.69%   |
| 2.01-3.0   | 1        | 0.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 70       | 48.61%  |
| 2      | 28       | 19.44%  |
| 0      | 18       | 12.5%   |
| 4      | 11       | 7.64%   |
| 3      | 8        | 5.56%   |
| 5      | 6        | 4.17%   |
| 6      | 2        | 1.39%   |
| 7      | 1        | 0.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 111      | 79.86%  |
| Yes       | 28       | 20.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 136      | 97.84%  |
| No        | 3        | 2.16%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 105      | 75%     |
| Yes       | 35       | 25%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 113      | 80.71%  |
| Yes       | 27       | 19.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Spain   | 139      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Madrid                        | 35       | 20.96%  |
| Valencia                      | 8        | 4.79%   |
| Barcelona                     | 7        | 4.19%   |
| Zaragoza                      | 4        | 2.4%    |
| Vigo                          | 3        | 1.8%    |
| Seville                       | 3        | 1.8%    |
| Santiago de Compostela        | 3        | 1.8%    |
| Palma                         | 3        | 1.8%    |
| Málaga                       | 3        | 1.8%    |
| Ibiza Town                    | 3        | 1.8%    |
| Bilbao                        | 3        | 1.8%    |
| Torrejon del Rey              | 2        | 1.2%    |
| San SebastiÃ¡n de los Reyes | 2        | 1.2%    |
| Port de Sagunt                | 2        | 1.2%    |
| Paterna                       | 2        | 1.2%    |
| Oviedo                        | 2        | 1.2%    |
| Ourense                       | 2        | 1.2%    |
| Castilleja de la Cuesta       | 2        | 1.2%    |
| Barakaldo                     | 2        | 1.2%    |
| Alcoy                         | 2        | 1.2%    |
| A Coruña                     | 2        | 1.2%    |
| VГ©lez-MГЎlaga            | 1        | 0.6%    |
| Vitoria-Gasteiz               | 1        | 0.6%    |
| Villena                       | 1        | 0.6%    |
| Villanueva de la Canada       | 1        | 0.6%    |
| Viladecans                    | 1        | 0.6%    |
| Valmojado                     | 1        | 0.6%    |
| Valleseco                     | 1        | 0.6%    |
| Valladolid                    | 1        | 0.6%    |
| Valderrobres                  | 1        | 0.6%    |
| Valdemoro                     | 1        | 0.6%    |
| Tres Cantos                   | 1        | 0.6%    |
| Trebujena                     | 1        | 0.6%    |
| Torre del Mar                 | 1        | 0.6%    |
| Sedavi                        | 1        | 0.6%    |
| Santurtzi                     | 1        | 0.6%    |
| Santa Cruz de Tenerife        | 1        | 0.6%    |
| Sant Cugat del Vallès        | 1        | 0.6%    |
| Sant Cugat del VallÃ¨s      | 1        | 0.6%    |
| San Jose de la Rinconada      | 1        | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 31       | 49     | 16.4%   |
| Seagate             | 30       | 54     | 15.87%  |
| Kingston            | 27       | 59     | 14.29%  |
| Samsung Electronics | 22       | 31     | 11.64%  |
| Crucial             | 16       | 20     | 8.47%   |
| Toshiba             | 6        | 8      | 3.17%   |
| Hitachi             | 5        | 5      | 2.65%   |
| China               | 5        | 13     | 2.65%   |
| SanDisk             | 4        | 5      | 2.12%   |
| Transcend           | 3        | 7      | 1.59%   |
| LITEON              | 3        | 3      | 1.59%   |
| FORESEE             | 3        | 3      | 1.59%   |
| Corsair             | 3        | 3      | 1.59%   |
| ViperTeq            | 2        | 2      | 1.06%   |
| Silicon Motion      | 2        | 2      | 1.06%   |
| ShiJi               | 2        | 3      | 1.06%   |
| LITEONIT            | 2        | 2      | 1.06%   |
| Intenso             | 2        | 6      | 1.06%   |
| Innodisk            | 2        | 4      | 1.06%   |
| Apacer              | 2        | 2      | 1.06%   |
| TCSUNBOW            | 1        | 3      | 0.53%   |
| SPCC                | 1        | 1      | 0.53%   |
| Phison              | 1        | 1      | 0.53%   |
| OCZ                 | 1        | 1      | 0.53%   |
| NVMe                | 1        | 1      | 0.53%   |
| Nfortec             | 1        | 1      | 0.53%   |
| Micron Technology   | 1        | 1      | 0.53%   |
| MicroFrom           | 1        | 1      | 0.53%   |
| Maximus             | 1        | 1      | 0.53%   |
| Lexar               | 1        | 1      | 0.53%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.53%   |
| Intel               | 1        | 3      | 0.53%   |
| HGST                | 1        | 1      | 0.53%   |
| Fanxiang            | 1        | 3      | 0.53%   |
| EMTEC               | 1        | 1      | 0.53%   |
| BR                  | 1        | 4      | 0.53%   |
| BAITITON            | 1        | 1      | 0.53%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB      | 8        | 3.65%   |
| Seagate ST500DM002-1BD142 500GB  | 4        | 1.83%   |
| Seagate ST1000DM010-2EP102 1TB   | 4        | 1.83%   |
| Crucial CT500MX500SSD1 500GB     | 4        | 1.83%   |
| Kingston SV300S37A120G 120GB     | 3        | 1.37%   |
| Kingston SKC600MS256G 256GB      | 3        | 1.37%   |
| Kingston SA400S37480G 480GB      | 3        | 1.37%   |
| Kingston SA400S37120G 120GB      | 3        | 1.37%   |
| Crucial CT240BX500SSD1 240GB     | 3        | 1.37%   |
| WDC WDS500G2B0A-00SM50 500GB     | 2        | 0.91%   |
| WDC WDS500G1B0A-00H9H0 500GB     | 2        | 0.91%   |
| WDC WDS250G1B0A-00H9H0 250GB     | 2        | 0.91%   |
| WDC WD20EARX-00PASB0 2TB         | 2        | 0.91%   |
| ViperTeq VT-SSDUP500-120 120GB   | 2        | 0.91%   |
| Toshiba TR200 240GB              | 2        | 0.91%   |
| Seagate ST3500418AS 500GB        | 2        | 0.91%   |
| Seagate ST1000DM003-9YN162 1TB   | 2        | 0.91%   |
| Seagate ST1000DM003-1ER162 1TB   | 2        | 0.91%   |
| Samsung SSD 860 EVO 500GB        | 2        | 0.91%   |
| Samsung SSD 850 EVO 500GB        | 2        | 0.91%   |
| Samsung HD103SI 1TB              | 2        | 0.91%   |
| LITEON CV8-8E128-HP 128GB        | 2        | 0.91%   |
| Kingston SUV500MS120G 120GB      | 2        | 0.91%   |
| Kingston SUV400S37240G 240GB     | 2        | 0.91%   |
| Innodisk DEMSR- 08GB mSATA 3ME A | 2        | 0.91%   |
| FORESEE S326M256G 256GB          | 2        | 0.91%   |
| Crucial M4-CT064M4SSD2 64GB      | 2        | 0.91%   |
| Crucial CT500P1SSD8 500GB        | 2        | 0.91%   |
| Crucial CT250MX500SSD1 250GB     | 2        | 0.91%   |
| WDC WDS500G3XHC-00SJG0 500GB     | 1        | 0.46%   |
| WDC WDS500G2B0B-00YS70 500GB     | 1        | 0.46%   |
| WDC WDS240G2G0A-00JH30 240GB     | 1        | 0.46%   |
| WDC WDS240G1G0A-00SS50 240GB     | 1        | 0.46%   |
| WDC WDS120G2G0B-00EPW0 120GB     | 1        | 0.46%   |
| WDC WD80EZAZ-11TDBA0 8TB         | 1        | 0.46%   |
| WDC WD800JD-75MSA3 80GB          | 1        | 0.46%   |
| WDC WD6400AAKS-22A7B0 640GB      | 1        | 0.46%   |
| WDC WD60EZRX-00MVLB1 6TB         | 1        | 0.46%   |
| WDC WD60EFRX-68L0BN1 6TB         | 1        | 0.46%   |
| WDC WD5000LPLX-66ZNTT0 500GB     | 1        | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 29       | 50     | 44.62%  |
| WDC                 | 21       | 34     | 32.31%  |
| Samsung Electronics | 6        | 9      | 9.23%   |
| Hitachi             | 5        | 5      | 7.69%   |
| Toshiba             | 3        | 4      | 4.62%   |
| HGST                | 1        | 1      | 1.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 26       | 58     | 25%     |
| Crucial             | 14       | 17     | 13.46%  |
| Samsung Electronics | 10       | 13     | 9.62%   |
| WDC                 | 9        | 14     | 8.65%   |
| China               | 5        | 13     | 4.81%   |
| Toshiba             | 4        | 4      | 3.85%   |
| SanDisk             | 4        | 5      | 3.85%   |
| Transcend           | 3        | 7      | 2.88%   |
| LITEON              | 3        | 3      | 2.88%   |
| FORESEE             | 3        | 3      | 2.88%   |
| ViperTeq            | 2        | 2      | 1.92%   |
| ShiJi               | 2        | 3      | 1.92%   |
| LITEONIT            | 2        | 2      | 1.92%   |
| Intenso             | 2        | 6      | 1.92%   |
| Innodisk            | 2        | 4      | 1.92%   |
| Apacer              | 2        | 2      | 1.92%   |
| TCSUNBOW            | 1        | 3      | 0.96%   |
| SPCC                | 1        | 1      | 0.96%   |
| Seagate             | 1        | 1      | 0.96%   |
| OCZ                 | 1        | 1      | 0.96%   |
| NVMe                | 1        | 1      | 0.96%   |
| MicroFrom           | 1        | 1      | 0.96%   |
| Maximus             | 1        | 1      | 0.96%   |
| Intel               | 1        | 3      | 0.96%   |
| EMTEC               | 1        | 1      | 0.96%   |
| BR                  | 1        | 4      | 0.96%   |
| BAITITON            | 1        | 1      | 0.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 88       | 174    | 56.05%  |
| HDD  | 48       | 103    | 30.57%  |
| NVMe | 21       | 30     | 13.38%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 112      | 277    | 84.21%  |
| NVMe | 21       | 30     | 15.79%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 98       | 212    | 70.5%   |
| 0.51-1.0   | 25       | 41     | 17.99%  |
| 1.01-2.0   | 9        | 15     | 6.47%   |
| 4.01-10.0  | 4        | 6      | 2.88%   |
| 3.01-4.0   | 2        | 2      | 1.44%   |
| 2.01-3.0   | 1        | 1      | 0.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 46       | 32.17%  |
| 1-20           | 38       | 26.57%  |
| 251-500        | 23       | 16.08%  |
| 21-50          | 13       | 9.09%   |
| 51-100         | 10       | 6.99%   |
| 501-1000       | 9        | 6.29%   |
| More than 3000 | 1        | 0.7%    |
| 2001-3000      | 1        | 0.7%    |
| 1001-2000      | 1        | 0.7%    |
| Unknown        | 1        | 0.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 129      | 90.21%  |
| 21-50   | 9        | 6.29%   |
| 251-500 | 2        | 1.4%    |
| 51-100  | 2        | 1.4%    |
| Unknown | 1        | 0.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 2        | 2      | 5.41%   |
| LITEON CV8-8E128-HP 128GB         | 2        | 2      | 5.41%   |
| Kingston SV300S37A120G 120GB      | 2        | 2      | 5.41%   |
| WDC WDS240G2G0A-00JH30 240GB      | 1        | 2      | 2.7%    |
| WDC WD6400AAKS-22A7B0 640GB       | 1        | 1      | 2.7%    |
| WDC WD5000AAKX-22ERMA0 500GB      | 1        | 1      | 2.7%    |
| WDC WD1600AAJS-00WAA0 160GB       | 1        | 1      | 2.7%    |
| WDC WD10EZEX-21M2NA0 1TB          | 1        | 1      | 2.7%    |
| Toshiba MQ01UBD100 1TB            | 1        | 2      | 2.7%    |
| Seagate ST6000DM003-2CY186 6TB    | 1        | 1      | 2.7%    |
| Seagate ST500LT012-9WS142 500GB   | 1        | 1      | 2.7%    |
| Seagate ST500LT012-1DG142 500GB   | 1        | 1      | 2.7%    |
| Seagate ST3500418AS 500GB         | 1        | 1      | 2.7%    |
| Seagate ST3500413AS 500GB         | 1        | 3      | 2.7%    |
| Seagate ST340016A 40GB            | 1        | 1      | 2.7%    |
| Seagate ST3160215AS 160GB         | 1        | 1      | 2.7%    |
| Seagate ST31000528AS 1TB          | 1        | 2      | 2.7%    |
| Seagate ST31000333AS 1TB          | 1        | 1      | 2.7%    |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 1      | 2.7%    |
| Seagate ST1000DM003-9YN162 1TB    | 1        | 1      | 2.7%    |
| Seagate ST1000DM003-1ER162 1TB    | 1        | 1      | 2.7%    |
| Samsung Electronics HM320JI 320GB | 1        | 1      | 2.7%    |
| Samsung Electronics HD252HJ 250GB | 1        | 1      | 2.7%    |
| Samsung Electronics HD103UJ 1TB   | 1        | 1      | 2.7%    |
| Samsung Electronics HD103SI 1TB   | 1        | 1      | 2.7%    |
| Maximus SSD 128GB                 | 1        | 1      | 2.7%    |
| Kingston SHFS37A120G 120GB        | 1        | 1      | 2.7%    |
| Kingston SA400S37480G 480GB       | 1        | 3      | 2.7%    |
| Hitachi HTS725050A9A364 500GB     | 1        | 1      | 2.7%    |
| Hitachi HTS725050A7E630 500GB     | 1        | 1      | 2.7%    |
| Hitachi HTS545050A7E380 500GB     | 1        | 1      | 2.7%    |
| Hitachi HDT721010SLA360 1TB       | 1        | 1      | 2.7%    |
| Hitachi HDP725016GLA380 160GB     | 1        | 1      | 2.7%    |
| China GM128 128GB                 | 1        | 1      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 17     | 33.33%  |
| WDC                 | 5        | 6      | 15.15%  |
| Hitachi             | 5        | 5      | 15.15%  |
| Kingston            | 4        | 6      | 12.12%  |
| Samsung Electronics | 3        | 4      | 9.09%   |
| LITEON              | 2        | 2      | 6.06%   |
| Toshiba             | 1        | 2      | 3.03%   |
| Maximus             | 1        | 1      | 3.03%   |
| China               | 1        | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 17     | 45.83%  |
| Hitachi             | 5        | 5      | 20.83%  |
| WDC                 | 4        | 4      | 16.67%  |
| Samsung Electronics | 3        | 4      | 12.5%   |
| Toshiba             | 1        | 2      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 21       | 32     | 70%     |
| SSD  | 9        | 12     | 30%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model             | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| SanDisk pSSD 16GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SanDisk | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 105      | 257    | 75.54%  |
| Malfunc  | 30       | 44     | 21.58%  |
| Detected | 3        | 5      | 2.16%   |
| Failed   | 1        | 1      | 0.72%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 104      | 57.46%  |
| AMD                          | 30       | 16.57%  |
| ASMedia Technology           | 9        | 4.97%   |
| Samsung Electronics          | 8        | 4.42%   |
| Phison Electronics           | 4        | 2.21%   |
| Silicon Motion               | 3        | 1.66%   |
| Shenzhen Longsys Electronics | 3        | 1.66%   |
| Sandisk                      | 3        | 1.66%   |
| Micron/Crucial Technology    | 3        | 1.66%   |
| Nvidia                       | 2        | 1.1%    |
| MAXIO Technology (Hangzhou)  | 2        | 1.1%    |
| Kingston Technology Company  | 2        | 1.1%    |
| VIA Technologies             | 1        | 0.55%   |
| Toshiba                      | 1        | 0.55%   |
| Seagate Technology           | 1        | 0.55%   |
| Micron Technology            | 1        | 0.55%   |
| Marvell Technology Group     | 1        | 0.55%   |
| KIOXIA                       | 1        | 0.55%   |
| JMicron Technology           | 1        | 0.55%   |
| Hosin Global Electronics     | 1        | 0.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                                              | Desktops | Percent |
|--------------------------------------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                                                | 20       | 9.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]                                     | 18       | 8.49%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                                                      | 8        | 3.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                                             | 7        | 3.3%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                                                   | 7        | 3.3%    |
| Intel Alder Lake-N SATA AHCI Controller                                                                            | 6        | 2.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller                                      | 6        | 2.83%   |
| AMD 400 Series Chipset SATA Controller                                                                             | 6        | 2.83%   |
| Intel SATA Controller [RAID mode]                                                                                  | 5        | 2.36%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller                                   | 5        | 2.36%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                                             | 5        | 2.36%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                                                       | 5        | 2.36%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                                                 | 4        | 1.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]                                      | 4        | 1.89%   |
| Intel Jasper Lake SATA AHCI Controller                                                                             | 4        | 1.89%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]                                       | 4        | 1.89%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                                                  | 3        | 1.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 3        | 1.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                                                  | 3        | 1.42%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                                               | 3        | 1.42%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                                                      | 2        | 0.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                                     | 2        | 0.94%   |
| Phison E16 PCIe4 NVMe Controller                                                                                   | 2        | 0.94%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                                                          | 2        | 0.94%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                                           | 2        | 0.94%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                                           | 2        | 0.94%   |
| Intel Atom Processor C3000 Series SATA Controller 0                                                                | 2        | 0.94%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                                               | 2        | 0.94%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]                                        | 2        | 0.94%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]                                        | 2        | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5)                            | 2        | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3)                            | 2        | 0.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                                                     | 2        | 0.94%   |
| AMD 500 Series Chipset SATA Controller                                                                             | 2        | 0.94%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                                                        | 1        | 0.47%   |
| Toshiba BG3 x2 NVMe SSD Controller (DRAM-less)                                                                     | 1        | 0.47%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM NVME SSD (DRAM-less)                                                  | 1        | 0.47%   |
| Shenzhen Longsys Lexar NM790 NVME SSD (DRAM-less)                                                                  | 1        | 0.47%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 1        | 0.47%   |
| Seagate FireCuda 520/IronWolf 525 SSD                                                                              | 1        | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 118      | 65.56%  |
| NVMe | 32       | 17.78%  |
| IDE  | 20       | 11.11%  |
| RAID | 9        | 5%      |
| SAS  | 1        | 0.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 105      | 75.54%  |
| AMD    | 33       | 23.74%  |
| ARM    | 1        | 0.72%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Intel N100                                                   | 6        | 4.29%   |
| Intel Core i3-4160 CPU @ 3.60GHz                             | 4        | 2.86%   |
| Intel Celeron N5105 @ 2.00GHz                                | 4        | 2.86%   |
| Intel Celeron J4125 CPU @ 2.00GHz                            | 4        | 2.86%   |
| Intel Core i5-9500 CPU @ 3.00GHz                             | 3        | 2.14%   |
| Intel Core i5-4590 CPU @ 3.30GHz                             | 3        | 2.14%   |
| Intel Core i5-2400 CPU @ 3.10GHz                             | 3        | 2.14%   |
| Intel Core i3-3240 CPU @ 3.40GHz                             | 3        | 2.14%   |
| AMD GX-415GA SOC with Radeon HD Graphics                     | 3        | 2.14%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz                          | 2        | 1.43%   |
| Intel Pentium CPU N3700 @ 1.60GHz                            | 2        | 1.43%   |
| Intel Core i5-7400 CPU @ 3.00GHz                             | 2        | 1.43%   |
| Intel Core i5-6500 CPU @ 3.20GHz                             | 2        | 1.43%   |
| Intel Core i5-4570T CPU @ 2.90GHz                            | 2        | 1.43%   |
| Intel Core i5-4570 CPU @ 3.20GHz                             | 2        | 1.43%   |
| Intel Core i5-4460 CPU @ 3.20GHz                             | 2        | 1.43%   |
| Intel Core i5-2400S CPU @ 2.50GHz                            | 2        | 1.43%   |
| Intel Core i3-2120 CPU @ 3.30GHz                             | 2        | 1.43%   |
| Intel Core i3-10100 CPU @ 3.60GHz                            | 2        | 1.43%   |
| Intel Celeron CPU J1900 @ 1.99GHz                            | 2        | 1.43%   |
| AMD Ryzen 5 2600 Six-Core Processor                          | 2        | 1.43%   |
| AMD Ryzen 3 1200 Quad-Core Processor                         | 2        | 1.43%   |
| Intel Xeon CPU X3430 @ 2.40GHz                               | 1        | 0.71%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz                           | 1        | 0.71%   |
| Intel Xeon CPU E3-1225 V2 @ 3.20GHz                          | 1        | 0.71%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz                     | 1        | 0.71%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz                     | 1        | 0.71%   |
| Intel Pentium III ("GenuineIntel" 686-class, 512KB L2 cache) | 1        | 0.71%   |
| Intel Pentium II                                             | 1        | 0.71%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz                       | 1        | 0.71%   |
| Intel Pentium Dual-Core CPU E5300                            | 1        | 0.71%   |
| Intel Pentium 4 CPU                                          | 1        | 0.71%   |
| Intel Genuine CPU 0000 @ 2.40GHz                             | 1        | 0.71%   |
| Intel Core i7-9700K CPU @ 3.60GHz                            | 1        | 0.71%   |
| Intel Core i7-7700 CPU @ 3.60GHz                             | 1        | 0.71%   |
| Intel Core i7-7500U CPU @ 2.70GHz                            | 1        | 0.71%   |
| Intel Core i7-6900K CPU @ 3.20GHz                            | 1        | 0.71%   |
| Intel Core i7-6700K CPU @ 4.00GHz                            | 1        | 0.71%   |
| Intel Core i7-6700 CPU @ 3.40GHz                             | 1        | 0.71%   |
| Intel Core i7-6500U CPU @ 2.50GHz                            | 1        | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 28       | 20%     |
| Intel Celeron           | 19       | 13.57%  |
| Intel Core i3           | 16       | 11.43%  |
| Intel Core i7           | 9        | 6.43%   |
| Other                   | 7        | 5%      |
| Intel Xeon              | 5        | 3.57%   |
| Intel Core 2 Duo        | 5        | 3.57%   |
| AMD Ryzen 7             | 5        | 3.57%   |
| AMD GX                  | 5        | 3.57%   |
| Intel Atom              | 4        | 2.86%   |
| AMD Ryzen 5             | 4        | 2.86%   |
| AMD Ryzen 3             | 4        | 2.86%   |
| Intel Pentium           | 3        | 2.14%   |
| Intel Core 2 Quad       | 3        | 2.14%   |
| AMD FX                  | 3        | 2.14%   |
| Intel Pentium Silver    | 2        | 1.43%   |
| AMD Athlon              | 2        | 1.43%   |
| Intel Pentium III       | 1        | 0.71%   |
| Intel Pentium Gold      | 1        | 0.71%   |
| Intel Pentium Dual-Core | 1        | 0.71%   |
| Intel Pentium 4         | 1        | 0.71%   |
| Intel Genuine           | 1        | 0.71%   |
| ARM Cortex              | 1        | 0.71%   |
| AMD Ryzen Threadripper  | 1        | 0.71%   |
| AMD Ryzen 9             | 1        | 0.71%   |
| AMD Phenom              | 1        | 0.71%   |
| AMD G                   | 1        | 0.71%   |
| AMD EPYC                | 1        | 0.71%   |
| AMD E2                  | 1        | 0.71%   |
| AMD E1                  | 1        | 0.71%   |
| AMD Athlon XP           | 1        | 0.71%   |
| AMD A8                  | 1        | 0.71%   |
| AMD A4                  | 1        | 0.71%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 72       | 51.8%   |
| 2       | 30       | 21.58%  |
| 8       | 9        | 6.47%   |
| Unknown | 7        | 5.04%   |
| 16      | 6        | 4.32%   |
| 6       | 6        | 4.32%   |
| 12      | 4        | 2.88%   |
| 1       | 3        | 2.16%   |
| 64      | 1        | 0.72%   |
| 14      | 1        | 0.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 136      | 97.14%  |
| Unknown | 4        | 2.86%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 98       | 70.5%   |
| 2       | 33       | 23.74%  |
| Unknown | 8        | 5.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 19       | 13.67%  |
| Unknown       | 15       | 10.79%  |
| KabyLake      | 13       | 9.35%   |
| Silvermont    | 10       | 7.19%   |
| SandyBridge   | 8        | 5.76%   |
| IvyBridge     | 8        | 5.76%   |
| Zen+          | 7        | 5.04%   |
| Goldmont plus | 7        | 5.04%   |
| Skylake       | 6        | 4.32%   |
| Penryn        | 6        | 4.32%   |
| Piledriver    | 5        | 3.6%    |
| Jaguar        | 4        | 2.88%   |
| Goldmont      | 4        | 2.88%   |
| Zen 3         | 3        | 2.16%   |
| Zen 2         | 3        | 2.16%   |
| Puma          | 3        | 2.16%   |
| Core          | 3        | 2.16%   |
| CometLake     | 3        | 2.16%   |
| Zen           | 2        | 1.44%   |
| P6            | 2        | 1.44%   |
| Westmere      | 1        | 0.72%   |
| NetBurst      | 1        | 0.72%   |
| Nehalem       | 1        | 0.72%   |
| K8 Hammer     | 1        | 0.72%   |
| K6            | 1        | 0.72%   |
| K10           | 1        | 0.72%   |
| Broadwell     | 1        | 0.72%   |
| Bobcat        | 1        | 0.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 82       | 60.29%  |
| Nvidia                               | 27       | 19.85%  |
| AMD                                  | 21       | 15.44%  |
| Matrox Electronics Systems           | 3        | 2.21%   |
| ASPEED Technology                    | 2        | 1.47%   |
| NVidia / SGS Thomson (Joint Venture) | 1        | 0.74%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8        | 5.84%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 7        | 5.11%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6        | 4.38%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 6        | 4.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6        | 4.38%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 5        | 3.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5        | 3.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5        | 3.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5        | 3.65%   |
| Intel JasperLake [UHD Graphics]                                                          | 4        | 2.92%   |
| Intel HD Graphics 530                                                                    | 4        | 2.92%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4        | 2.92%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 3        | 2.19%   |
| Intel HD Graphics 630                                                                    | 3        | 2.19%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 3        | 2.19%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2        | 1.46%   |
| Nvidia GT218 [GeForce 210]                                                               | 2        | 1.46%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2        | 1.46%   |
| Intel HD Graphics 620                                                                    | 2        | 1.46%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2        | 1.46%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 1.46%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 1.46%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 2        | 1.46%   |
| AMD RV280 [Radeon 9200 PRO / 9250]                                                       | 2        | 1.46%   |
| AMD Rembrandt [Radeon 680M]                                                              | 2        | 1.46%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2        | 1.46%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 2        | 1.46%   |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                                     | 1        | 0.73%   |
| Nvidia TU104GL [Quadro RTX 4000]                                                         | 1        | 0.73%   |
| Nvidia GT218 [NVS 300]                                                                   | 1        | 0.73%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 0.73%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 0.73%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1        | 0.73%   |
| Nvidia GK208B [GeForce GT 720]                                                           | 1        | 0.73%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 1        | 0.73%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 0.73%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1        | 0.73%   |
| Nvidia GF100GL [Quadro 5000]                                                             | 1        | 0.73%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 1        | 0.73%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 1        | 0.73%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| 1 x Intel                                | 77       | 55%     |
| 1 x Nvidia                               | 26       | 18.57%  |
| 1 x AMD                                  | 19       | 13.57%  |
| Other                                    | 6        | 4.29%   |
| 2 x Intel                                | 3        | 2.14%   |
| 1 x Matrox                               | 3        | 2.14%   |
| 1 x ASPEED                               | 2        | 1.43%   |
| 2 x AMD                                  | 1        | 0.71%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1        | 0.71%   |
| Intel + Nvidia                           | 1        | 0.71%   |
| Intel + AMD                              | 1        | 0.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 111      | 79.29%  |
| Proprietary | 18       | 12.86%  |
| Unknown     | 11       | 7.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 117      | 83.57%  |
| 1.01-2.0   | 8        | 5.71%   |
| 5.01-6.0   | 4        | 2.86%   |
| 3.01-4.0   | 4        | 2.86%   |
| 2.01-3.0   | 2        | 1.43%   |
| 0.51-1.0   | 2        | 1.43%   |
| 0.01-0.5   | 2        | 1.43%   |
| 7.01-8.0   | 1        | 0.71%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| BenQ                 | 9        | 20.93%  |
| Dell                 | 6        | 13.95%  |
| Goldstar             | 5        | 11.63%  |
| Acer                 | 3        | 6.98%   |
| Plain Tree Systems   | 2        | 4.65%   |
| Philips              | 2        | 4.65%   |
| Lenovo               | 2        | 4.65%   |
| AOC                  | 2        | 4.65%   |
| Vestel Elektronik    | 1        | 2.33%   |
| Samsung Electronics  | 1        | 2.33%   |
| MSI                  | 1        | 2.33%   |
| Microstep            | 1        | 2.33%   |
| Medion               | 1        | 2.33%   |
| LG Philips           | 1        | 2.33%   |
| Lenovo Group Limited | 1        | 2.33%   |
| Impression           | 1        | 2.33%   |
| Hewlett-Packard      | 1        | 2.33%   |
| CHD                  | 1        | 2.33%   |
| ASUSTek Computer     | 1        | 2.33%   |
| Ancor Communications | 1        | 2.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Plain Tree Systems LCD Monitor PTS0313 1600x1200 320x240mm 15.7-inch  | 2        | 4.65%   |
| BenQ GW2765 BNQ78D6 2560x1440 600x340mm 27.2-inch                     | 2        | 4.65%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 1        | 2.33%   |
| Samsung Electronics S27H85x SAM0E0F 2560x1440 600x340mm 27.2-inch     | 1        | 2.33%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch               | 1        | 2.33%   |
| Philips 190S PHL083F 1280x1024 380x300mm 19.1-inch                    | 1        | 2.33%   |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                       | 1        | 2.33%   |
| Microstep LCD Monitor MSI MAG241C 1920x1080                           | 1        | 2.33%   |
| Medion MD21281 MED3947 1366x768 410x230mm 18.5-inch                   | 1        | 2.33%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 330x210mm 15.4-inch         | 1        | 2.33%   |
| Lenovo LEN T24i-10 LEN61CE 1920x1080 530x300mm 24.0-inch              | 1        | 2.33%   |
| Lenovo Group Limited LCD Monitor C24-25 1920x1080                     | 1        | 2.33%   |
| Lenovo C24-25 LEN66B0 1920x1080 530x300mm 24.0-inch                   | 1        | 2.33%   |
| Impression R19W11 IMP1911 1440x900 410x260mm 19.1-inch                | 1        | 2.33%   |
| Hewlett-Packard x23LED HWP2912 1920x1080 510x290mm 23.1-inch          | 1        | 2.33%   |
| Goldstar W2242 GSM4B6F 1680x1050 490x320mm 23.0-inch                  | 1        | 2.33%   |
| Goldstar MP59G GSM5B35 1920x1080 600x340mm 27.2-inch                  | 1        | 2.33%   |
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch              | 1        | 2.33%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch             | 1        | 2.33%   |
| Goldstar L1715S GSM436F 1280x1024 340x270mm 17.1-inch                 | 1        | 2.33%   |
| Dell U3415W DELA0A6 3440x1440 800x330mm 34.1-inch                     | 1        | 2.33%   |
| Dell U2723QE DEL4277 3840x2160 600x340mm 27.2-inch                    | 1        | 2.33%   |
| Dell S2522HG DELA1C1 1920x1080 540x300mm 24.3-inch                    | 1        | 2.33%   |
| Dell P1914S DELF04B 1280x1024 380x300mm 19.1-inch                     | 1        | 2.33%   |
| Dell LCD Monitor U2414H 1920x1080                                     | 1        | 2.33%   |
| Dell LCD Monitor SP2309W 2048x1152                                    | 1        | 2.33%   |
| CHD M27 CHD0270 1920x1080 530x290mm 23.8-inch                         | 1        | 2.33%   |
| BenQ LCD Monitor GW2270 1920x1080                                     | 1        | 2.33%   |
| BenQ GL940 BNQ7883 1366x768 410x230mm 18.5-inch                       | 1        | 2.33%   |
| BenQ GL2480 BNQ78ED 1920x1080 530x300mm 24.0-inch                     | 1        | 2.33%   |
| BenQ GL2460 BNQ78CE 1920x1080 530x300mm 24.0-inch                     | 1        | 2.33%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                    | 1        | 2.33%   |
| BenQ GL2240 BNQ7887 1920x1080 480x270mm 21.7-inch                     | 1        | 2.33%   |
| BenQ EW2440L BNQ7938 1920x1080 530x300mm 24.0-inch                    | 1        | 2.33%   |
| ASUSTek Computer XG49WCR AUS4932 3840x1080 1190x340mm 48.7-inch       | 1        | 2.33%   |
| AOC 2481W AOC2481 1920x1080 530x300mm 24.0-inch                       | 1        | 2.33%   |
| AOC 2050W AOC2050 1600x900 430x240mm 19.4-inch                        | 1        | 2.33%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 480x270mm 21.7-inch | 1        | 2.33%   |
| Acer V193W ACR001A 1440x900 410x260mm 19.1-inch                       | 1        | 2.33%   |
| Acer KA240Y ACR0970 1920x1080 530x300mm 24.0-inch                     | 1        | 2.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 20       | 47.62%  |
| 2560x1440 (QHD)    | 3        | 7.14%   |
| 1440x900 (WXGA+)   | 3        | 7.14%   |
| 1280x1024 (SXGA)   | 3        | 7.14%   |
| 3840x2160 (4K)     | 2        | 4.76%   |
| 1600x1200          | 2        | 4.76%   |
| 1366x768 (WXGA)    | 2        | 4.76%   |
| 3840x1080          | 1        | 2.38%   |
| 3440x1440          | 1        | 2.38%   |
| 2048x1152          | 1        | 2.38%   |
| 1920x540           | 1        | 2.38%   |
| 1680x1050 (WSXGA+) | 1        | 2.38%   |
| 1600x900 (HD+)     | 1        | 2.38%   |
| 1280x800 (WXGA)    | 1        | 2.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 10       | 23.26%  |
| 27      | 6        | 13.95%  |
| 19      | 5        | 11.63%  |
| Unknown | 5        | 11.63%  |
| 23      | 4        | 9.3%    |
| 21      | 3        | 6.98%   |
| 18      | 3        | 6.98%   |
| 15      | 3        | 6.98%   |
| 48      | 1        | 2.33%   |
| 42      | 1        | 2.33%   |
| 34      | 1        | 2.33%   |
| 17      | 1        | 2.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 19       | 45.24%  |
| 401-500     | 8        | 19.05%  |
| Unknown     | 5        | 11.9%   |
| 301-350     | 4        | 9.52%   |
| 351-400     | 3        | 7.14%   |
| 701-800     | 1        | 2.38%   |
| 1001-1500   | 1        | 2.38%   |
| 901-1000    | 1        | 2.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 25       | 59.52%  |
| Unknown | 5        | 11.9%   |
| 16/10   | 4        | 9.52%   |
| 5/4     | 3        | 7.14%   |
| 4/3     | 2        | 4.76%   |
| 32/9    | 1        | 2.38%   |
| 3/2     | 1        | 2.38%   |
| 21/9    | 1        | 2.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 15       | 36.59%  |
| 301-350        | 6        | 14.63%  |
| 151-200        | 5        | 12.2%   |
| Unknown        | 5        | 12.2%   |
| 141-150        | 3        | 7.32%   |
| 111-120        | 2        | 4.88%   |
| 501-1000       | 2        | 4.88%   |
| 351-500        | 1        | 2.44%   |
| 251-300        | 1        | 2.44%   |
| 101-110        | 1        | 2.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 24       | 60%     |
| 101-120 | 7        | 17.5%   |
| Unknown | 5        | 12.5%   |
| 161-240 | 2        | 5%      |
| 121-160 | 2        | 5%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 88       | 63.31%  |
| 1     | 49       | 35.25%  |
| 2     | 2        | 1.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 80       | 43.24%  |
| Realtek Semiconductor           | 71       | 38.38%  |
| Qualcomm Atheros                | 9        | 4.86%   |
| Broadcom                        | 8        | 4.32%   |
| Marvell Technology Group        | 3        | 1.62%   |
| TP-Link                         | 2        | 1.08%   |
| MediaTek                        | 2        | 1.08%   |
| D-Link System                   | 2        | 1.08%   |
| Samsung Electronics             | 1        | 0.54%   |
| Ralink Technology               | 1        | 0.54%   |
| Qualcomm Atheros Communications | 1        | 0.54%   |
| Nvidia                          | 1        | 0.54%   |
| Google                          | 1        | 0.54%   |
| Edimax Technology               | 1        | 0.54%   |
| Belkin Components               | 1        | 0.54%   |
| American Megatrends             | 1        | 0.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 60       | 28.3%   |
| Intel I211 Gigabit Network Connection                                  | 10       | 4.72%   |
| Intel Ethernet Controller I226-V                                       | 10       | 4.72%   |
| Intel Ethernet Controller I225-V                                       | 6        | 2.83%   |
| Intel Ethernet Connection I217-LM                                      | 6        | 2.83%   |
| Intel 82583V Gigabit Network Connection                                | 6        | 2.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6        | 2.83%   |
| Intel I350 Gigabit Network Connection                                  | 5        | 2.36%   |
| Intel I210 Gigabit Network Connection                                  | 4        | 1.89%   |
| Intel 82580 Gigabit Network Connection                                 | 4        | 1.89%   |
| Intel 82574L Gigabit Network Connection                                | 4        | 1.89%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3        | 1.42%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 3        | 1.42%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 3        | 1.42%   |
| Intel Wi-Fi 6 AX200                                                    | 3        | 1.42%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 3        | 1.42%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 2        | 0.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 0.94%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2        | 0.94%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 2        | 0.94%   |
| Intel Ethernet Connection X553 10 GbE SFP+                             | 2        | 0.94%   |
| Intel Ethernet Connection (2) I219-V                                   | 2        | 0.94%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 0.94%   |
| Intel 82579V Gigabit Network Connection                                | 2        | 0.94%   |
| Intel 82576 Gigabit Network Connection                                 | 2        | 0.94%   |
| Intel 82575GB Gigabit Network Connection                               | 2        | 0.94%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                     | 2        | 0.94%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 2        | 0.94%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 1        | 0.47%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1        | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 0.47%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1        | 0.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1        | 0.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1        | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 0.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1        | 0.47%   |
| Ralink RT3072 Wireless Adapter                                         | 1        | 0.47%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter        | 1        | 0.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1        | 0.47%   |
| Qualcomm Atheros AR9170 802.11n                                        | 1        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 12       | 31.58%  |
| Qualcomm Atheros                | 8        | 21.05%  |
| Realtek Semiconductor           | 6        | 15.79%  |
| Broadcom                        | 3        | 7.89%   |
| TP-Link                         | 2        | 5.26%   |
| MediaTek                        | 2        | 5.26%   |
| Ralink Technology               | 1        | 2.63%   |
| Qualcomm Atheros Communications | 1        | 2.63%   |
| Edimax Technology               | 1        | 2.63%   |
| D-Link System                   | 1        | 2.63%   |
| Belkin Components               | 1        | 2.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9227 Wireless Network Adapter                                        | 3        | 7.89%   |
| Intel Wi-Fi 6 AX200                                                                     | 3        | 7.89%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                  | 2        | 5.26%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                     | 1        | 2.63%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                              | 1        | 2.63%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                             | 1        | 2.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                | 1        | 2.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                         | 1        | 2.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                     | 1        | 2.63%   |
| Ralink RT3072 Wireless Adapter                                                          | 1        | 2.63%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter                         | 1        | 2.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                              | 1        | 2.63%   |
| Qualcomm Atheros AR9170 802.11n                                                         | 1        | 2.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                        | 1        | 2.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                          | 1        | 2.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                 | 1        | 2.63%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                           | 1        | 2.63%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                           | 1        | 2.63%   |
| Intel Wireless 7260                                                                     | 1        | 2.63%   |
| Intel Wireless 3165                                                                     | 1        | 2.63%   |
| Intel Wireless 3160                                                                     | 1        | 2.63%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                               | 1        | 2.63%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                                 | 1        | 2.63%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                                       | 1        | 2.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                         | 1        | 2.63%   |
| Intel Gemini Lake PCH CNVi WiFi                                                         | 1        | 2.63%   |
| Intel CNVi: Wi-Fi                                                                       | 1        | 2.63%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                          | 1        | 2.63%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]              | 1        | 2.63%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                            | 1        | 2.63%   |
| Broadcom BCM43228 802.11a/b/g/n                                                         | 1        | 2.63%   |
| Broadcom 802.11ac Wireless Network Adapter                                              | 1        | 2.63%   |
| Belkin Components F7D2102 802.11n N300 Micro Wireless Adapter v3000 [Realtek RTL8192CU] | 1        | 2.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 74       | 47.74%  |
| Realtek Semiconductor    | 68       | 43.87%  |
| Broadcom                 | 5        | 3.23%   |
| Marvell Technology Group | 3        | 1.94%   |
| Samsung Electronics      | 1        | 0.65%   |
| Qualcomm Atheros         | 1        | 0.65%   |
| Nvidia                   | 1        | 0.65%   |
| D-Link System            | 1        | 0.65%   |
| American Megatrends      | 1        | 0.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 60       | 34.88%  |
| Intel I211 Gigabit Network Connection                                  | 10       | 5.81%   |
| Intel Ethernet Controller I226-V                                       | 10       | 5.81%   |
| Intel Ethernet Controller I225-V                                       | 6        | 3.49%   |
| Intel Ethernet Connection I217-LM                                      | 6        | 3.49%   |
| Intel 82583V Gigabit Network Connection                                | 6        | 3.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6        | 3.49%   |
| Intel I350 Gigabit Network Connection                                  | 5        | 2.91%   |
| Intel I210 Gigabit Network Connection                                  | 4        | 2.33%   |
| Intel 82580 Gigabit Network Connection                                 | 4        | 2.33%   |
| Intel 82574L Gigabit Network Connection                                | 4        | 2.33%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3        | 1.74%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 3        | 1.74%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 3        | 1.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 1.16%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2        | 1.16%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 2        | 1.16%   |
| Intel Ethernet Connection X553 10 GbE SFP+                             | 2        | 1.16%   |
| Intel Ethernet Connection (2) I219-V                                   | 2        | 1.16%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 1.16%   |
| Intel 82579V Gigabit Network Connection                                | 2        | 1.16%   |
| Intel 82576 Gigabit Network Connection                                 | 2        | 1.16%   |
| Intel 82575GB Gigabit Network Connection                               | 2        | 1.16%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                     | 2        | 1.16%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 2        | 1.16%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 0.58%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1        | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 0.58%   |
| Nvidia MCP73 Ethernet                                                  | 1        | 0.58%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1        | 0.58%   |
| Intel Ethernet Controller I219-V                                       | 1        | 0.58%   |
| Intel Ethernet Connection X553 1GbE                                    | 1        | 0.58%   |
| Intel Ethernet Connection I217-V                                       | 1        | 0.58%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 0.58%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 0.58%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 0.58%   |
| Intel Ethernet Connection (17) I219-V                                  | 1        | 0.58%   |
| Intel 82575EB Gigabit Network Connection                               | 1        | 0.58%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                     | 1        | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 0.58%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 136      | 78.61%  |
| WiFi     | 35       | 20.23%  |
| Unknown  | 2        | 1.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 128      | 94.81%  |
| WiFi     | 7        | 5.19%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 53       | 38.13%  |
| 2     | 27       | 19.42%  |
| 4     | 16       | 11.51%  |
| 3     | 16       | 11.51%  |
| 5     | 11       | 7.91%   |
| 6     | 7        | 5.04%   |
| 8     | 5        | 3.6%    |
| 9     | 2        | 1.44%   |
| 15    | 1        | 0.72%   |
| 0     | 1        | 0.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 138      | 98.57%  |
| Yes  | 2        | 1.43%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 12       | 42.86%  |
| Cambridge Silicon Radio         | 7        | 25%     |
| Realtek Semiconductor           | 3        | 10.71%  |
| Qualcomm Atheros Communications | 1        | 3.57%   |
| MediaTek                        | 1        | 3.57%   |
| IMC Networks                    | 1        | 3.57%   |
| Foxconn / Hon Hai               | 1        | 3.57%   |
| Broadcom                        | 1        | 3.57%   |
| ASUSTek Computer                | 1        | 3.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 7        | 25%     |
| Intel Bluetooth wireless interface                    | 3        | 10.71%  |
| Intel AX200 Bluetooth                                 | 3        | 10.71%  |
| Realtek Bluetooth Adapter                             | 2        | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2        | 7.14%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 3.57%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1        | 3.57%   |
| MediaTek Bluetooth Adapter                            | 1        | 3.57%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 3.57%   |
| Intel AX211 Bluetooth                                 | 1        | 3.57%   |
| Intel AX210 Bluetooth                                 | 1        | 3.57%   |
| Intel AX201 Bluetooth                                 | 1        | 3.57%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip  | 1        | 3.57%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter             | 1        | 3.57%   |
| Broadcom 4371 Bluetooth 4.1 Adapter                   | 1        | 3.57%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 3.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 83       | 52.87%  |
| AMD                                          | 34       | 21.66%  |
| Nvidia                                       | 26       | 16.56%  |
| Cambridge Silicon Radio                      | 2        | 1.27%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.64%   |
| VIA Technologies                             | 1        | 0.64%   |
| Logitech                                     | 1        | 0.64%   |
| Lenovo                                       | 1        | 0.64%   |
| Hewlett-Packard                              | 1        | 0.64%   |
| GEMBIRD                                      | 1        | 0.64%   |
| ESS Technology                               | 1        | 0.64%   |
| Ensoniq                                      | 1        | 0.64%   |
| Dell                                         | 1        | 0.64%   |
| Corsair                                      | 1        | 0.64%   |
| C-Media Electronics                          | 1        | 0.64%   |
| BEHRINGER International                      | 1        | 0.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14       | 7.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12       | 6.7%    |
| Intel 200 Series PCH HD Audio                                                                     | 8        | 4.47%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7        | 3.91%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7        | 3.91%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6        | 3.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6        | 3.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6        | 3.35%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6        | 3.35%   |
| AMD FCH Azalia Controller                                                                         | 6        | 3.35%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 5        | 2.79%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5        | 2.79%   |
| Intel Jasper Lake HD Audio                                                                        | 4        | 2.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4        | 2.23%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4        | 2.23%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 4        | 2.23%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3        | 1.68%   |
| Nvidia High Definition Audio Controller                                                           | 3        | 1.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3        | 1.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3        | 1.68%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2        | 1.12%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2        | 1.12%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2        | 1.12%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 2        | 1.12%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2        | 1.12%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2        | 1.12%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2        | 1.12%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2        | 1.12%   |
| Cambridge Silicon Radio FiiO BTR3K                                                                | 2        | 1.12%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 2        | 1.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2        | 1.12%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2        | 1.12%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1        | 0.56%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 1        | 0.56%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1        | 0.56%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1        | 0.56%   |
| Nvidia MCP73 High Definition Audio                                                                | 1        | 0.56%   |
| Nvidia MCP61 High Definition Audio                                                                | 1        | 0.56%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1        | 0.56%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1        | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 33       | 21.29%  |
| Crucial             | 28       | 18.06%  |
| Samsung Electronics | 16       | 10.32%  |
| Unknown             | 14       | 9.03%   |
| Micron Technology   | 13       | 8.39%   |
| SK hynix            | 11       | 7.1%    |
| Corsair             | 7        | 4.52%   |
| Ramaxel Technology  | 4        | 2.58%   |
| G.Skill             | 4        | 2.58%   |
| Unknown             | 4        | 2.58%   |
| Nanya Technology    | 3        | 1.94%   |
| Apacer              | 3        | 1.94%   |
| Unknown (0B45)      | 2        | 1.29%   |
| Hewlett-Packard     | 2        | 1.29%   |
| A-DATA Technology   | 2        | 1.29%   |
| Wodposit            | 1        | 0.65%   |
| Unknown (ABCD)      | 1        | 0.65%   |
| Transcend           | 1        | 0.65%   |
| Toshiba             | 1        | 0.65%   |
| Kimtigo             | 1        | 0.65%   |
| GOODRAM             | 1        | 0.65%   |
| Goldenmars          | 1        | 0.65%   |
| Essencore           | 1        | 0.65%   |
| ASint Technology    | 1        | 0.65%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 4        | 2.27%   |
| Unknown                                                        | 4        | 2.27%   |
| Unknown (0B45) RAM WPBC26D416SWM-16G 16GB SODIMM DDR4 2667MT/s | 2        | 1.14%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB DIMM DDR3 1600MT/s           | 2        | 1.14%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2        | 1.14%   |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s                      | 2        | 1.14%   |
| Micron RAM MTA8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 2        | 1.14%   |
| Micron RAM 18KSF51272AZ-1G4M1 4GB DIMM DDR3 1333MT/s           | 2        | 1.14%   |
| Kingston RAM KVR13LS9/4 4GB SODIMM DDR3 1333MT/s               | 2        | 1.14%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 2        | 1.14%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s          | 2        | 1.14%   |
| Kingston RAM 99U5474-016.A00LF 4GB DIMM DDR3 1333MT/s          | 2        | 1.14%   |
| Kingston RAM 99U5471-056.A00LF 8GB DIMM DDR3 1600MT/s          | 2        | 1.14%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s        | 2        | 1.14%   |
| Kingston RAM 99U5469-045.A00LF 4GB DIMM DDR3 1600MT/s          | 2        | 1.14%   |
| Crucial RAM CT16G4SFRA266.M8FB 16GB SODIMM DDR4 2667MT/s       | 2        | 1.14%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s        | 2        | 1.14%   |
| Wodposit RAM WPBC26D416SWM-16G 16GB SODIMM DDR4 2667MT/s       | 1        | 0.57%   |
| Unknown RAM Module 8GB DIMM DDR3 1866MT/s                      | 1        | 0.57%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1        | 0.57%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                        | 1        | 0.57%   |
| Unknown RAM Module 512MB DIMM 400MT/s                          | 1        | 0.57%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                    | 1        | 0.57%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 1        | 0.57%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                   | 1        | 0.57%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                        | 1        | 0.57%   |
| Unknown RAM Module 2GB DIMM DDR 1066MT/s                       | 1        | 0.57%   |
| Unknown RAM Module 256MB DIMM 333MT/s                          | 1        | 0.57%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 1        | 0.57%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                       | 1        | 0.57%   |
| Unknown RAM Module 1GB DIMM 667MT/s                            | 1        | 0.57%   |
| Unknown RAM Module 1GB DIMM 400MT/s                            | 1        | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s | 1        | 0.57%   |
| Transcend RAM TS1GLK72V6H 8GB DIMM DDR3 1600MT/s               | 1        | 0.57%   |
| Toshiba RAM 9905711-015.A00G 4GB SODIMM DDR4 2400MT/s          | 1        | 0.57%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1333MT/s                   | 1        | 0.57%   |
| SK hynix RAM Module 4096MB DIMM DDR3 1600MT/s                  | 1        | 0.57%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                  | 1        | 0.57%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.57%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1333MT/s           | 1        | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 56       | 44.44%  |
| DDR4    | 48       | 38.1%   |
| DDR2    | 7        | 5.56%   |
| DDR5    | 6        | 4.76%   |
| Unknown | 3        | 2.38%   |
| SDRAM   | 2        | 1.59%   |
| LPDDR4  | 2        | 1.59%   |
| LPDDR5  | 1        | 0.79%   |
| DDR     | 1        | 0.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 90       | 71.43%  |
| SODIMM       | 34       | 26.98%  |
| Row Of Chips | 1        | 0.79%   |
| Chip         | 1        | 0.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 49       | 35%     |
| 4096  | 45       | 32.14%  |
| 16384 | 24       | 17.14%  |
| 2048  | 15       | 10.71%  |
| 1024  | 4        | 2.86%   |
| 32768 | 1        | 0.71%   |
| 512   | 1        | 0.71%   |
| 256   | 1        | 0.71%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 43       | 30.94%  |
| 1333    | 18       | 12.95%  |
| 2400    | 17       | 12.23%  |
| 3200    | 15       | 10.79%  |
| 2667    | 10       | 7.19%   |
| 2133    | 6        | 4.32%   |
| 800     | 6        | 4.32%   |
| 4800    | 5        | 3.6%    |
| 1866    | 4        | 2.88%   |
| 2666    | 3        | 2.16%   |
| 6400    | 2        | 1.44%   |
| 3600    | 2        | 1.44%   |
| Unknown | 2        | 1.44%   |
| 1332    | 1        | 0.72%   |
| 1066    | 1        | 0.72%   |
| 1033    | 1        | 0.72%   |
| 667     | 1        | 0.72%   |
| 400     | 1        | 0.72%   |
| 333     | 1        | 0.72%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                                             | Desktops | Percent |
|-------------------------------------------------------------------------------------------------------------------|----------|---------|
| HP HP LaserJet MFP E52645 LaserJet 0 LaserJet 0 LaserJet 1 LaserJet 1 LaserJet 2 LaserJet 2 LaserJet 3 LaserJet 3 | 1        | 100%    |

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
| Logitech                | 2        | 25%     |
| Z-Star Microelectronics | 1        | 12.5%   |
| OmniVision Technologies | 1        | 12.5%   |
| IMC Networks            | 1        | 12.5%   |
| HD WEBCAM               | 1        | 12.5%   |
| Chicony Electronics     | 1        | 12.5%   |
| Alcor Micro             | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                          | Desktops | Percent |
|--------------------------------|----------|---------|
| Z-Star Vega USB 2.0 Camera     | 1        | 12.5%   |
| OmniVision Monitor Webcam      | 1        | 12.5%   |
| Logitech C505 HD Webcam        | 1        | 12.5%   |
| Logitech BRIO Ultra HD Webcam  | 1        | 12.5%   |
| IMC Networks Realtek PC Camera | 1        | 12.5%   |
| HD WEBCAM HD WEBCAM            | 1        | 12.5%   |
| Chicony Webcam                 | 1        | 12.5%   |
| Alcor Micro PC Camera          | 1        | 12.5%   |

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
| 1     | 77       | 54.23%  |
| 0     | 43       | 30.28%  |
| 2     | 17       | 11.97%  |
| 3     | 3        | 2.11%   |
| 6     | 1        | 0.7%    |
| 4     | 1        | 0.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 81       | 66.39%  |
| Net/wireless             | 18       | 14.75%  |
| Bluetooth                | 8        | 6.56%   |
| Sound                    | 4        | 3.28%   |
| Network                  | 3        | 2.46%   |
| Graphics card            | 3        | 2.46%   |
| Card reader              | 2        | 1.64%   |
| Storage/ata              | 1        | 0.82%   |
| Net/ethernet             | 1        | 0.82%   |
| Firewire controller      | 1        | 0.82%   |

