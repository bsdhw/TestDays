BSD in Australia - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for BSD in Australia.

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

Total: 735

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Protectli     | FW2B Ver                    | [f3be3b3acc](https://bsd-hardware.info/?probe=f3be3b3acc) | Dec 31, 2025 |
| Unknown       | QDNV01                      | [7782909112](https://bsd-hardware.info/?probe=7782909112) | Dec 31, 2025 |
| Unknown       | Unknown                     | [257e8393ec](https://bsd-hardware.info/?probe=257e8393ec) | Dec 24, 2025 |
| Gigabyte      | B360M D3H-CF                | [181e2e0e68](https://bsd-hardware.info/?probe=181e2e0e68) | Dec 15, 2025 |
| MSI           | B450M-A PRO MAX II          | [50e2dafd2a](https://bsd-hardware.info/?probe=50e2dafd2a) | Dec 14, 2025 |
| Dell          | 0C1R19 A02                  | [c0edad3b9e](https://bsd-hardware.info/?probe=c0edad3b9e) | Dec 13, 2025 |
| Unknown       | Unknown                     | [e60e976fcc](https://bsd-hardware.info/?probe=e60e976fcc) | Dec 13, 2025 |
| Unknown       | Unknown                     | [e3c5a7d8a0](https://bsd-hardware.info/?probe=e3c5a7d8a0) | Dec 09, 2025 |
| Shenzhen M... | AHBNB OEM                   | [e87e11e303](https://bsd-hardware.info/?probe=e87e11e303) | Dec 09, 2025 |
| Shenzhen M... | AHBNB OEM                   | [928730b34f](https://bsd-hardware.info/?probe=928730b34f) | Dec 09, 2025 |
| Unknown       | Unknown                     | [a9ddb2b45d](https://bsd-hardware.info/?probe=a9ddb2b45d) | Dec 07, 2025 |
| Unknown       | Unknown                     | [bebe952710](https://bsd-hardware.info/?probe=bebe952710) | Nov 29, 2025 |
| ASUSTek       | PRIME B250M-C               | [7d166f4be3](https://bsd-hardware.info/?probe=7d166f4be3) | Nov 28, 2025 |
| ASUSTek       | PRIME B250M-C               | [e77e132d34](https://bsd-hardware.info/?probe=e77e132d34) | Nov 27, 2025 |
| Unknown       | QGLK03                      | [4a31564adb](https://bsd-hardware.info/?probe=4a31564adb) | Nov 26, 2025 |
| Unknown       | Unknown                     | [6a0bdd5f1a](https://bsd-hardware.info/?probe=6a0bdd5f1a) | Nov 25, 2025 |
| Dell          | 0HV8FN A01                  | [f3f98de7a9](https://bsd-hardware.info/?probe=f3f98de7a9) | Nov 23, 2025 |
| NP93B         | 1.0                         | [6f1223b8b2](https://bsd-hardware.info/?probe=6f1223b8b2) | Nov 23, 2025 |
| Dell          | 0HD5W2 A01                  | [ea7fbcfa45](https://bsd-hardware.info/?probe=ea7fbcfa45) | Nov 23, 2025 |
| Dell          | 0HV8FN A01                  | [f3140018c7](https://bsd-hardware.info/?probe=f3140018c7) | Nov 22, 2025 |
| Dell          | 0NW6H5 A00                  | [9ad54fb46b](https://bsd-hardware.info/?probe=9ad54fb46b) | Nov 19, 2025 |
| Unknown       | Unknown                     | [3e673d4541](https://bsd-hardware.info/?probe=3e673d4541) | Nov 17, 2025 |
| Dell          | 0HV8FN A01                  | [3d1e92c58a](https://bsd-hardware.info/?probe=3d1e92c58a) | Nov 16, 2025 |
| Dell          | 0NW6H5 A00                  | [6bf6b0188f](https://bsd-hardware.info/?probe=6bf6b0188f) | Nov 13, 2025 |
| MSI           | B450M-A PRO MAX II          | [355a233604](https://bsd-hardware.info/?probe=355a233604) | Nov 09, 2025 |
| Dell          | 0NC2VH A01                  | [aad305c619](https://bsd-hardware.info/?probe=aad305c619) | Nov 07, 2025 |
| ADI Engine... | RCC-VE                      | [bdd2ca79b8](https://bsd-hardware.info/?probe=bdd2ca79b8) | Nov 07, 2025 |
| Unknown       | Unknown                     | [c81ec1565c](https://bsd-hardware.info/?probe=c81ec1565c) | Nov 06, 2025 |
| Protectli     | V1410                       | [8eb8ae712d](https://bsd-hardware.info/?probe=8eb8ae712d) | Nov 05, 2025 |
| Unknown       | Unknown                     | [7f3c67382d](https://bsd-hardware.info/?probe=7f3c67382d) | Nov 04, 2025 |
| Unknown       | Unknown                     | [19d5f6fc2e](https://bsd-hardware.info/?probe=19d5f6fc2e) | Nov 03, 2025 |
| Dell          | 0YC03K A04                  | [0ad1654af2](https://bsd-hardware.info/?probe=0ad1654af2) | Nov 01, 2025 |
| Protectli     | VP4670                      | [0cb44017eb](https://bsd-hardware.info/?probe=0cb44017eb) | Oct 31, 2025 |
| Unknown       | Unknown                     | [533b617aa9](https://bsd-hardware.info/?probe=533b617aa9) | Oct 30, 2025 |
| MSI           | MS-B0A81                    | [bf65eaba1d](https://bsd-hardware.info/?probe=bf65eaba1d) | Oct 29, 2025 |
| TianBei       | N1 PRO                      | [63ae5ffd65](https://bsd-hardware.info/?probe=63ae5ffd65) | Oct 25, 2025 |
| Unknown       | Unknown                     | [f64d141e9a](https://bsd-hardware.info/?probe=f64d141e9a) | Oct 23, 2025 |
| Unknown       | Unknown                     | [73a0b1ec82](https://bsd-hardware.info/?probe=73a0b1ec82) | Oct 17, 2025 |
| Unknown       | Unknown                     | [71edad02c1](https://bsd-hardware.info/?probe=71edad02c1) | Oct 11, 2025 |
| Unknown       | Unknown                     | [0c58822675](https://bsd-hardware.info/?probe=0c58822675) | Oct 07, 2025 |
| Unknown       | Unknown                     | [69449c5ebb](https://bsd-hardware.info/?probe=69449c5ebb) | Oct 06, 2025 |
| Gigabyte      | Z87-HD3                     | [2bf937d238](https://bsd-hardware.info/?probe=2bf937d238) | Oct 06, 2025 |
| Gigabyte      | Z87-HD3                     | [72832870f1](https://bsd-hardware.info/?probe=72832870f1) | Oct 05, 2025 |
| Gigabyte      | Z790 AORUS ELITE DDR4       | [d5f342b91d](https://bsd-hardware.info/?probe=d5f342b91d) | Oct 04, 2025 |
| Datto         | SSD                         | [7fb3456566](https://bsd-hardware.info/?probe=7fb3456566) | Oct 02, 2025 |
| Protectli     | VP2410 10                   | [74e93e9803](https://bsd-hardware.info/?probe=74e93e9803) | Sep 30, 2025 |
| Gigabyte      | Z790 AORUS ELITE DDR4       | [c269c0cb0e](https://bsd-hardware.info/?probe=c269c0cb0e) | Sep 29, 2025 |
| MSI           | B450M-A PRO MAX II          | [4ec36facdc](https://bsd-hardware.info/?probe=4ec36facdc) | Sep 28, 2025 |
| Dell          | 0D6H9T A01                  | [a5aa09e802](https://bsd-hardware.info/?probe=a5aa09e802) | Sep 28, 2025 |
| Unknown       | Unknown                     | [faba9ef2a2](https://bsd-hardware.info/?probe=faba9ef2a2) | Sep 27, 2025 |
| Protectli     | FW2B                        | [ad5108cb3b](https://bsd-hardware.info/?probe=ad5108cb3b) | Sep 27, 2025 |
| Unknown       | Unknown                     | [466958e099](https://bsd-hardware.info/?probe=466958e099) | Sep 27, 2025 |
| Unknown       | Unknown                     | [5b8b173624](https://bsd-hardware.info/?probe=5b8b173624) | Sep 26, 2025 |
| Unknown       | Unknown                     | [de80f263e0](https://bsd-hardware.info/?probe=de80f263e0) | Sep 24, 2025 |
| Unknown       | Unknown                     | [ac07639f07](https://bsd-hardware.info/?probe=ac07639f07) | Sep 22, 2025 |
| Dell          | 0NW6H5 A00                  | [9ea6d64621](https://bsd-hardware.info/?probe=9ea6d64621) | Sep 21, 2025 |
| Unknown       | Unknown                     | [4ab315db11](https://bsd-hardware.info/?probe=4ab315db11) | Sep 19, 2025 |
| MW            | GMLK-2_5G4L                 | [eca82f1479](https://bsd-hardware.info/?probe=eca82f1479) | Sep 19, 2025 |
| Winston Ma... | PICO PC V1.2                | [b81dd0f407](https://bsd-hardware.info/?probe=b81dd0f407) | Sep 17, 2025 |
| HP            | 8299                        | [44109f1adf](https://bsd-hardware.info/?probe=44109f1adf) | Sep 17, 2025 |
| Protectli     | VP4630                      | [8a46f1574f](https://bsd-hardware.info/?probe=8a46f1574f) | Sep 16, 2025 |
| Protectli     | VP4630                      | [87f440eea7](https://bsd-hardware.info/?probe=87f440eea7) | Sep 16, 2025 |
| Techvision    | TVI7309X B0                 | [22ad1a6ae2](https://bsd-hardware.info/?probe=22ad1a6ae2) | Sep 15, 2025 |
| Dell          | 0XCR8D A01                  | [1563de278c](https://bsd-hardware.info/?probe=1563de278c) | Sep 15, 2025 |
| Unknown       | Unknown                     | [115183390a](https://bsd-hardware.info/?probe=115183390a) | Sep 14, 2025 |
| Unknown       | Unknown                     | [29a9ccec16](https://bsd-hardware.info/?probe=29a9ccec16) | Sep 14, 2025 |
| YANYU         | H67SL                       | [c072dcc982](https://bsd-hardware.info/?probe=c072dcc982) | Sep 13, 2025 |
| Unknown       | Unknown                     | [0bfcac0761](https://bsd-hardware.info/?probe=0bfcac0761) | Sep 05, 2025 |
| Techvision    | TVI7309X B0                 | [788707444e](https://bsd-hardware.info/?probe=788707444e) | Sep 05, 2025 |
| Unknown       | Unknown                     | [4cb009287a](https://bsd-hardware.info/?probe=4cb009287a) | Sep 04, 2025 |
| Dell          | 0D6H9T A01                  | [52b9561767](https://bsd-hardware.info/?probe=52b9561767) | Aug 26, 2025 |
| Dell          | 0NW6H5 A00                  | [3107de51de](https://bsd-hardware.info/?probe=3107de51de) | Aug 26, 2025 |
| Dell          | 0NW6H5 A00                  | [d837670268](https://bsd-hardware.info/?probe=d837670268) | Aug 26, 2025 |
| Unknown       | Unknown                     | [d11c3c4b4c](https://bsd-hardware.info/?probe=d11c3c4b4c) | Aug 25, 2025 |
| HP            | 212A                        | [30b0fc9b4b](https://bsd-hardware.info/?probe=30b0fc9b4b) | Aug 24, 2025 |
| Dell          | 0C522T A03                  | [eb89c60c0c](https://bsd-hardware.info/?probe=eb89c60c0c) | Aug 24, 2025 |
| Unknown       | Unknown                     | [735deaf0f1](https://bsd-hardware.info/?probe=735deaf0f1) | Aug 23, 2025 |
| MSI           | MS-B0A81                    | [fc0a60684a](https://bsd-hardware.info/?probe=fc0a60684a) | Aug 23, 2025 |
| Unknown       | Unknown                     | [852a1a2d11](https://bsd-hardware.info/?probe=852a1a2d11) | Aug 23, 2025 |
| HP            | 3048h                       | [efd50eb795](https://bsd-hardware.info/?probe=efd50eb795) | Aug 23, 2025 |
| Inventec      | D CLASS A02                 | [3cc1d7bf13](https://bsd-hardware.info/?probe=3cc1d7bf13) | Aug 22, 2025 |
| Techvision    | TVI7309X B0                 | [6ee3a79a4e](https://bsd-hardware.info/?probe=6ee3a79a4e) | Aug 21, 2025 |
| TianBei       | N1 PRO                      | [d6622f16f1](https://bsd-hardware.info/?probe=d6622f16f1) | Aug 20, 2025 |
| Techvision    | TVI7309X B0                 | [475e154cc0](https://bsd-hardware.info/?probe=475e154cc0) | Aug 20, 2025 |
| Intel         | D54250WYK H13922-305        | [360e04f1d2](https://bsd-hardware.info/?probe=360e04f1d2) | Aug 19, 2025 |
| MW            | GMLK-2_5G4L                 | [deae839e4d](https://bsd-hardware.info/?probe=deae839e4d) | Aug 18, 2025 |
| Dell          | 0D6H9T A01                  | [8ac7db7775](https://bsd-hardware.info/?probe=8ac7db7775) | Aug 18, 2025 |
| Gigabyte      | B550M AORUS PRO             | [04f23441a1](https://bsd-hardware.info/?probe=04f23441a1) | Aug 15, 2025 |
| Lenovo        | 30D0 SDK0L22692 WIN 3306... | [7f492e6106](https://bsd-hardware.info/?probe=7f492e6106) | Aug 12, 2025 |
| MW            | GMLK-2_5G4L                 | [d9b9a43146](https://bsd-hardware.info/?probe=d9b9a43146) | Aug 10, 2025 |
| CWWK          | CW-ADLN-6L                  | [dcf30c34c1](https://bsd-hardware.info/?probe=dcf30c34c1) | Aug 06, 2025 |
| Gigabyte      | Q370M D3H GSM PLUS          | [184b8f1112](https://bsd-hardware.info/?probe=184b8f1112) | Aug 05, 2025 |
| Unknown       | Unknown                     | [b2f5ba69c4](https://bsd-hardware.info/?probe=b2f5ba69c4) | Aug 05, 2025 |
| Unknown       | Unknown                     | [86f7a75fa7](https://bsd-hardware.info/?probe=86f7a75fa7) | Aug 02, 2025 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [54699e46ab](https://bsd-hardware.info/?probe=54699e46ab) | Jul 30, 2025 |
| Intel         | BKHD-1264-SFP               | [6652d83aac](https://bsd-hardware.info/?probe=6652d83aac) | Jul 29, 2025 |
| Lenovo        | 30D0 SDK0L22692 WIN 3306... | [6cad88d666](https://bsd-hardware.info/?probe=6cad88d666) | Jul 27, 2025 |
| Protectli     | VP4630                      | [6701c837f7](https://bsd-hardware.info/?probe=6701c837f7) | Jul 26, 2025 |
| Unknown       | Unknown                     | [88cb9f9ef6](https://bsd-hardware.info/?probe=88cb9f9ef6) | Jul 24, 2025 |
| Protectli     | FW4B Ver                    | [efd941891b](https://bsd-hardware.info/?probe=efd941891b) | Jul 22, 2025 |
| Unknown       | Unknown                     | [19a1044651](https://bsd-hardware.info/?probe=19a1044651) | Jul 22, 2025 |
| Unknown       | Unknown                     | [b9949ee84f](https://bsd-hardware.info/?probe=b9949ee84f) | Jul 21, 2025 |
| Techvision    | TVI7309X B0                 | [ec73493808](https://bsd-hardware.info/?probe=ec73493808) | Jul 20, 2025 |
| Dell          | 0NC2VH A01                  | [0f1b12cd50](https://bsd-hardware.info/?probe=0f1b12cd50) | Jul 19, 2025 |
| PC Engines    | APU2                        | [6824c194a5](https://bsd-hardware.info/?probe=6824c194a5) | Jul 13, 2025 |
| Intel         | DENLOW_WS                   | [d89f914c6b](https://bsd-hardware.info/?probe=d89f914c6b) | Jul 11, 2025 |
| Intel         | DENLOW_WS                   | [c1640614b1](https://bsd-hardware.info/?probe=c1640614b1) | Jul 11, 2025 |
| ASUSTek       | PRIME B250M-PLUS            | [5c93fe81a4](https://bsd-hardware.info/?probe=5c93fe81a4) | Jul 10, 2025 |
| Protectli     | VP2410 10                   | [2fd150def7](https://bsd-hardware.info/?probe=2fd150def7) | Jul 07, 2025 |
| Gigabyte      | Z790 AORUS ELITE DDR4       | [8386db50b7](https://bsd-hardware.info/?probe=8386db50b7) | Jul 07, 2025 |
| Unknown       | Unknown                     | [b1e054b1ef](https://bsd-hardware.info/?probe=b1e054b1ef) | Jul 04, 2025 |
| Gigabyte      | B250M-D3H-CF                | [3ab859ab25](https://bsd-hardware.info/?probe=3ab859ab25) | Jul 03, 2025 |
| Unknown       | Unknown                     | [7118d6b609](https://bsd-hardware.info/?probe=7118d6b609) | Jul 03, 2025 |
| Gigabyte      | Z790 AORUS ELITE DDR4       | [e9bc7f47c0](https://bsd-hardware.info/?probe=e9bc7f47c0) | Jun 30, 2025 |
| Unknown       | Unknown                     | [8629885ea3](https://bsd-hardware.info/?probe=8629885ea3) | Jun 30, 2025 |
| ASUSTek       | H61M-K                      | [ae9d91cce3](https://bsd-hardware.info/?probe=ae9d91cce3) | Jun 28, 2025 |
| Unknown       | Unknown                     | [5dc2f76004](https://bsd-hardware.info/?probe=5dc2f76004) | Jun 27, 2025 |
| Unknown       | Unknown                     | [46a3594e44](https://bsd-hardware.info/?probe=46a3594e44) | Jun 25, 2025 |
| HP            | 8299                        | [6f482a75f7](https://bsd-hardware.info/?probe=6f482a75f7) | Jun 24, 2025 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | [08a43c80ed](https://bsd-hardware.info/?probe=08a43c80ed) | Jun 23, 2025 |
| HP            | 8299                        | [c971eb05c2](https://bsd-hardware.info/?probe=c971eb05c2) | Jun 23, 2025 |
| Dell          | 096JG8 A01                  | [d951945344](https://bsd-hardware.info/?probe=d951945344) | Jun 22, 2025 |
| Dell          | 00CV7F A00                  | [28f4056136](https://bsd-hardware.info/?probe=28f4056136) | Jun 22, 2025 |
| Unknown       | Unknown                     | [8bbced361a](https://bsd-hardware.info/?probe=8bbced361a) | Jun 20, 2025 |
| MW            | GMLK-2_5G4L                 | [9dc4b45e85](https://bsd-hardware.info/?probe=9dc4b45e85) | Jun 19, 2025 |
| Dell          | 05842Y A00                  | [33562da12c](https://bsd-hardware.info/?probe=33562da12c) | Jun 19, 2025 |
| Unknown       | Unknown                     | [97b9cf55d3](https://bsd-hardware.info/?probe=97b9cf55d3) | Jun 15, 2025 |
| Unknown       | Unknown                     | [4a928d008a](https://bsd-hardware.info/?probe=4a928d008a) | Jun 11, 2025 |
| ASUSTek       | PRIME B550M-K               | [fa655ea070](https://bsd-hardware.info/?probe=fa655ea070) | Jun 03, 2025 |
| Citrix        | CB-1100                     | [08bb9f20a8](https://bsd-hardware.info/?probe=08bb9f20a8) | Jun 01, 2025 |
| Protectli     | FW4B Ver                    | [d2e468f4ae](https://bsd-hardware.info/?probe=d2e468f4ae) | May 31, 2025 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [08b55e0bab](https://bsd-hardware.info/?probe=08b55e0bab) | May 27, 2025 |
| AZW           | GK55                        | [81600568e3](https://bsd-hardware.info/?probe=81600568e3) | May 27, 2025 |
| Unknown       | Unknown                     | [dbc29e346b](https://bsd-hardware.info/?probe=dbc29e346b) | May 26, 2025 |
| Unknown       | Unknown                     | [e523323e19](https://bsd-hardware.info/?probe=e523323e19) | May 25, 2025 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [f8a8851ab5](https://bsd-hardware.info/?probe=f8a8851ab5) | May 20, 2025 |
| ASUSTek       | PRIME B550M-K               | [dd4f6b856f](https://bsd-hardware.info/?probe=dd4f6b856f) | May 18, 2025 |
| Unknown       | Unknown                     | [ada674b101](https://bsd-hardware.info/?probe=ada674b101) | May 16, 2025 |
| Unknown       | Unknown                     | [c563722734](https://bsd-hardware.info/?probe=c563722734) | May 16, 2025 |
| ASRock        | X99 Taichi                  | [89be650fad](https://bsd-hardware.info/?probe=89be650fad) | May 15, 2025 |
| LinuxConta... | Incus pc-q35-7.2            | [f4c11c64c9](https://bsd-hardware.info/?probe=f4c11c64c9) | May 12, 2025 |
| ASRock        | Z590M-ITX/ax                | [2f03153022](https://bsd-hardware.info/?probe=2f03153022) | May 11, 2025 |
| ASRock        | Z590M-ITX/ax                | [b36c519819](https://bsd-hardware.info/?probe=b36c519819) | May 09, 2025 |
| ASUSTek       | PRIME B550M-K               | [8d2de26425](https://bsd-hardware.info/?probe=8d2de26425) | May 09, 2025 |
| Unknown       | Unknown                     | [1b97008abd](https://bsd-hardware.info/?probe=1b97008abd) | May 08, 2025 |
| HP            | 83E1                        | [6593b9ba45](https://bsd-hardware.info/?probe=6593b9ba45) | May 07, 2025 |
| HP            | 0AA8h                       | [5b054216cd](https://bsd-hardware.info/?probe=5b054216cd) | May 07, 2025 |
| Unknown       | Unknown                     | [85eeb318a6](https://bsd-hardware.info/?probe=85eeb318a6) | May 05, 2025 |
| HP            | 8055                        | [9dc9734e98](https://bsd-hardware.info/?probe=9dc9734e98) | May 04, 2025 |
| HP            | 8055                        | [51385d0be6](https://bsd-hardware.info/?probe=51385d0be6) | May 04, 2025 |
| Dell          | 0NW6H5 A00                  | [aaabda123b](https://bsd-hardware.info/?probe=aaabda123b) | May 03, 2025 |
| MW            | GMLK-2_5G4L                 | [e7af97ff92](https://bsd-hardware.info/?probe=e7af97ff92) | May 02, 2025 |
| Unknown       | Unknown                     | [6f9574cfd4](https://bsd-hardware.info/?probe=6f9574cfd4) | Apr 29, 2025 |
| CncTion       | 1338NP-12 B0                | [7675411a96](https://bsd-hardware.info/?probe=7675411a96) | Apr 29, 2025 |
| HP            | 0AA8h                       | [6a1203b154](https://bsd-hardware.info/?probe=6a1203b154) | Apr 28, 2025 |
| HP            | 8299                        | [aadd48eb34](https://bsd-hardware.info/?probe=aadd48eb34) | Apr 27, 2025 |
| Unknown       | QDNV01                      | [c793424764](https://bsd-hardware.info/?probe=c793424764) | Apr 24, 2025 |
| Unknown       | Unknown                     | [8eb8a4d6aa](https://bsd-hardware.info/?probe=8eb8a4d6aa) | Apr 22, 2025 |
| Lenovo        | 3321 SDK0T76461 WIN 3422... | [896d6ce1f6](https://bsd-hardware.info/?probe=896d6ce1f6) | Apr 16, 2025 |
| ASUSTek       | PRIME A320I-K               | [a1fa126927](https://bsd-hardware.info/?probe=a1fa126927) | Apr 03, 2025 |
| HP            | 83EE                        | [5eac034bc7](https://bsd-hardware.info/?probe=5eac034bc7) | Apr 03, 2025 |
| Unknown       | Unknown                     | [c8c4df43b1](https://bsd-hardware.info/?probe=c8c4df43b1) | Apr 02, 2025 |
| HP            | 8055                        | [ba941fb4d9](https://bsd-hardware.info/?probe=ba941fb4d9) | Apr 01, 2025 |
| Protectli     | FW4B Ver                    | [438f617d84](https://bsd-hardware.info/?probe=438f617d84) | Mar 30, 2025 |
| Protectli     | FW4C Ver                    | [5cfe707b85](https://bsd-hardware.info/?probe=5cfe707b85) | Mar 30, 2025 |
| HP            | ProLiant ML350p Gen8        | [770b60c2fd](https://bsd-hardware.info/?probe=770b60c2fd) | Mar 29, 2025 |
| Unknown       | adnasc01                    | [4a9e7aca14](https://bsd-hardware.info/?probe=4a9e7aca14) | Mar 29, 2025 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [3d0c9119ea](https://bsd-hardware.info/?probe=3d0c9119ea) | Mar 22, 2025 |
| Protectli     | FW4C Ver                    | [af204be1e6](https://bsd-hardware.info/?probe=af204be1e6) | Mar 15, 2025 |
| AZW           | EQ                          | [533d0c8945](https://bsd-hardware.info/?probe=533d0c8945) | Mar 14, 2025 |
| Unknown       | Unknown                     | [4f2f667607](https://bsd-hardware.info/?probe=4f2f667607) | Mar 14, 2025 |
| ASUSTek       | PRIME B250M-PLUS            | [ce28752002](https://bsd-hardware.info/?probe=ce28752002) | Mar 07, 2025 |
| Winston Ma... | PICO PC V1.2                | [41efa9e187](https://bsd-hardware.info/?probe=41efa9e187) | Feb 28, 2025 |
| ASRock        | H570M-ITX/ac                | [87e8319e25](https://bsd-hardware.info/?probe=87e8319e25) | Feb 26, 2025 |
| Unknown       | DS2309 MotherBoard          | [9f7e10d4b6](https://bsd-hardware.info/?probe=9f7e10d4b6) | Feb 23, 2025 |
| Techvision    | TVI7309X B0                 | [34c42b0d5f](https://bsd-hardware.info/?probe=34c42b0d5f) | Feb 19, 2025 |
| MW            | GMLK-2_5G4L                 | [a7d4cedc20](https://bsd-hardware.info/?probe=a7d4cedc20) | Feb 18, 2025 |
| AZW           | GK55                        | [f9f93d031a](https://bsd-hardware.info/?probe=f9f93d031a) | Feb 15, 2025 |
| AZW           | GK55                        | [3630266c91](https://bsd-hardware.info/?probe=3630266c91) | Feb 13, 2025 |
| Protectli     | VP4630                      | [214404737d](https://bsd-hardware.info/?probe=214404737d) | Feb 10, 2025 |
| Unknown       | Unknown                     | [d1b040ed41](https://bsd-hardware.info/?probe=d1b040ed41) | Feb 08, 2025 |
| Unknown       | Unknown                     | [566a65354f](https://bsd-hardware.info/?probe=566a65354f) | Feb 08, 2025 |
| Protectli     | FW4B                        | [8b48c1b35d](https://bsd-hardware.info/?probe=8b48c1b35d) | Feb 06, 2025 |
| Unknown       | DS2309 MotherBoard          | [739b355479](https://bsd-hardware.info/?probe=739b355479) | Feb 06, 2025 |
| Unknown       | Unknown                     | [385e4d1c3e](https://bsd-hardware.info/?probe=385e4d1c3e) | Feb 03, 2025 |
| Protectli     | FW4B Ver                    | [2c08f58b71](https://bsd-hardware.info/?probe=2c08f58b71) | Feb 03, 2025 |
| Unknown       | Unknown                     | [17982a6be9](https://bsd-hardware.info/?probe=17982a6be9) | Jan 30, 2025 |
| CWWK          | CW-ADLN-6L                  | [26a2de7191](https://bsd-hardware.info/?probe=26a2de7191) | Jan 30, 2025 |
| Dell          | 08NPPY A00                  | [1d032b6320](https://bsd-hardware.info/?probe=1d032b6320) | Jan 28, 2025 |
| Dell          | Precision T1650             | [3b9943f0fa](https://bsd-hardware.info/?probe=3b9943f0fa) | Jan 27, 2025 |
| Unknown       | Unknown                     | [b3544d9a76](https://bsd-hardware.info/?probe=b3544d9a76) | Jan 26, 2025 |
| Intel         | PB-X6000                    | [5102f2f6ff](https://bsd-hardware.info/?probe=5102f2f6ff) | Jan 26, 2025 |
| Protectli     | VP4670                      | [436dc612a8](https://bsd-hardware.info/?probe=436dc612a8) | Jan 26, 2025 |
| Dell          | 07KY25 A00                  | [4e8472f65f](https://bsd-hardware.info/?probe=4e8472f65f) | Jan 24, 2025 |
| Dell          | 07KY25 A00                  | [f149a101c7](https://bsd-hardware.info/?probe=f149a101c7) | Jan 24, 2025 |
| Trigkey       | Green G5                    | [8a78158aca](https://bsd-hardware.info/?probe=8a78158aca) | Jan 23, 2025 |
| MSI           | MAG B550M MORTAR            | [ad8de19c61](https://bsd-hardware.info/?probe=ad8de19c61) | Jan 21, 2025 |
| CWWK          | CW-ADLN-6L                  | [1672bc92cd](https://bsd-hardware.info/?probe=1672bc92cd) | Jan 20, 2025 |
| Protectli     | V1410                       | [87e8299d80](https://bsd-hardware.info/?probe=87e8299d80) | Jan 19, 2025 |
| HPE           | ProLiant MicroServer Gen... | [d01f2efa37](https://bsd-hardware.info/?probe=d01f2efa37) | Jan 17, 2025 |
| MSI           | MS-B0A81                    | [d9bbff761d](https://bsd-hardware.info/?probe=d9bbff761d) | Jan 17, 2025 |
| CWWK          | CW-ADLN-6L                  | [0d0b40294a](https://bsd-hardware.info/?probe=0d0b40294a) | Jan 15, 2025 |
| AZW           | EQ                          | [03a9b46b8f](https://bsd-hardware.info/?probe=03a9b46b8f) | Jan 14, 2025 |
| Unknown       | Unknown                     | [85b47857df](https://bsd-hardware.info/?probe=85b47857df) | Jan 11, 2025 |
| Techvision    | TVI7309X B0                 | [e54714fe40](https://bsd-hardware.info/?probe=e54714fe40) | Jan 11, 2025 |
| Techvision    | TVI7309X B0                 | [4bca5d6829](https://bsd-hardware.info/?probe=4bca5d6829) | Jan 11, 2025 |
| ASRock        | H570M-ITX/ac                | [5b40284fbe](https://bsd-hardware.info/?probe=5b40284fbe) | Jan 04, 2025 |
| Protectli     | VP4670                      | [1649d4be0f](https://bsd-hardware.info/?probe=1649d4be0f) | Dec 29, 2024 |
| Unknown       | Unknown                     | [a92bf0ef02](https://bsd-hardware.info/?probe=a92bf0ef02) | Dec 27, 2024 |
| ASRock        | H570M-ITX/ac                | [eb9e3863e0](https://bsd-hardware.info/?probe=eb9e3863e0) | Dec 22, 2024 |
| Unknown       | Unknown                     | [02119a1b45](https://bsd-hardware.info/?probe=02119a1b45) | Dec 22, 2024 |
| Protectli     | VP4670                      | [8d641a410f](https://bsd-hardware.info/?probe=8d641a410f) | Dec 16, 2024 |
| WeiBu         | ADL-N Prod                  | [de66071f16](https://bsd-hardware.info/?probe=de66071f16) | Dec 12, 2024 |
| Unknown       | Unknown                     | [fa422c4eec](https://bsd-hardware.info/?probe=fa422c4eec) | Dec 11, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | [1b2c50f225](https://bsd-hardware.info/?probe=1b2c50f225) | Dec 08, 2024 |
| ASUSTek       | Q87I-PLUS                   | [9d857bfe96](https://bsd-hardware.info/?probe=9d857bfe96) | Dec 07, 2024 |
| Protectli     | V1410                       | [78a29a9a78](https://bsd-hardware.info/?probe=78a29a9a78) | Dec 07, 2024 |
| Lenovo        | 1052 NOK                    | [44cfb1316c](https://bsd-hardware.info/?probe=44cfb1316c) | Dec 06, 2024 |
| Protectli     | V1410                       | [de051ba319](https://bsd-hardware.info/?probe=de051ba319) | Dec 03, 2024 |
| Unknown       | Unknown                     | [6348954925](https://bsd-hardware.info/?probe=6348954925) | Dec 02, 2024 |
| Techvision    | TVI7309X B0                 | [648268f0e3](https://bsd-hardware.info/?probe=648268f0e3) | Dec 01, 2024 |
| Gigabyte      | Z490 AORUS MASTER           | [5a7a5ce019](https://bsd-hardware.info/?probe=5a7a5ce019) | Nov 30, 2024 |
| Dell          | 0NW6H5 A00                  | [a25be40b42](https://bsd-hardware.info/?probe=a25be40b42) | Nov 26, 2024 |
| Gigabyte      | Z490 AORUS MASTER           | [acfb1a77bf](https://bsd-hardware.info/?probe=acfb1a77bf) | Nov 24, 2024 |
| Dell          | 00V62H A01                  | [c4ffe49c04](https://bsd-hardware.info/?probe=c4ffe49c04) | Nov 23, 2024 |
| Dell          | 0H0P0M A00                  | [67846a1472](https://bsd-hardware.info/?probe=67846a1472) | Nov 23, 2024 |
| Dell          | 0H0P0M A00                  | [5e1cccc11c](https://bsd-hardware.info/?probe=5e1cccc11c) | Nov 17, 2024 |
| Unknown       | Unknown                     | [9411c1202b](https://bsd-hardware.info/?probe=9411c1202b) | Nov 16, 2024 |
| Dell          | 0XCR8D A01                  | [2ab0785e7a](https://bsd-hardware.info/?probe=2ab0785e7a) | Nov 14, 2024 |
| Shenzhen M... | AHWSA                       | [d296c3e157](https://bsd-hardware.info/?probe=d296c3e157) | Nov 13, 2024 |
| Unknown       | AD18                        | [c134167984](https://bsd-hardware.info/?probe=c134167984) | Nov 12, 2024 |
| HP            | 3048h                       | [9a81b371b5](https://bsd-hardware.info/?probe=9a81b371b5) | Nov 12, 2024 |
| HP            | 83E2                        | [e5c43ed134](https://bsd-hardware.info/?probe=e5c43ed134) | Nov 11, 2024 |
| HP            | 870C                        | [d18863b8e4](https://bsd-hardware.info/?probe=d18863b8e4) | Nov 10, 2024 |
| Dell          | 00V62H A01                  | [1841d9a2d3](https://bsd-hardware.info/?probe=1841d9a2d3) | Oct 29, 2024 |
| Dell          | 096JG8 A01                  | [aad472393b](https://bsd-hardware.info/?probe=aad472393b) | Oct 27, 2024 |
| Unknown       | Unknown                     | [1082ecf333](https://bsd-hardware.info/?probe=1082ecf333) | Oct 26, 2024 |
| Unknown       | Unknown                     | [57f630266f](https://bsd-hardware.info/?probe=57f630266f) | Oct 25, 2024 |
| OEM           | PB-1900-A                   | [fac430a8c9](https://bsd-hardware.info/?probe=fac430a8c9) | Oct 25, 2024 |
| CheckPoint    | T-120-00                    | [62b73d8e40](https://bsd-hardware.info/?probe=62b73d8e40) | Oct 21, 2024 |
| HPE           | ProLiant MicroServer Gen... | [223ca94998](https://bsd-hardware.info/?probe=223ca94998) | Oct 15, 2024 |
| Intel         | D34010WYK H14771-302        | [67245b0423](https://bsd-hardware.info/?probe=67245b0423) | Oct 15, 2024 |
| HP            | 3048h                       | [9a6218dc9f](https://bsd-hardware.info/?probe=9a6218dc9f) | Oct 13, 2024 |
| ASRock        | H570M-ITX/ac                | [4e0d157a76](https://bsd-hardware.info/?probe=4e0d157a76) | Oct 09, 2024 |
| ASRock        | H570M-ITX/ac                | [e54bd4924f](https://bsd-hardware.info/?probe=e54bd4924f) | Oct 09, 2024 |
| Dell          | 00V62H A00                  | [87e3fa093a](https://bsd-hardware.info/?probe=87e3fa093a) | Oct 09, 2024 |
| Techvision    | TVI7309X B0                 | [156ab405d2](https://bsd-hardware.info/?probe=156ab405d2) | Oct 09, 2024 |
| Gigabyte      | GA-78LMT-S2P                | [7b97e06782](https://bsd-hardware.info/?probe=7b97e06782) | Oct 04, 2024 |
| Intel         | DH67BL AAG10189-206         | [45d47552af](https://bsd-hardware.info/?probe=45d47552af) | Oct 02, 2024 |
| Techvision    | TVI7309X B0                 | [45a12f9a8b](https://bsd-hardware.info/?probe=45a12f9a8b) | Oct 01, 2024 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [b50eb75680](https://bsd-hardware.info/?probe=b50eb75680) | Sep 28, 2024 |
| HP            | 870C                        | [a0a04f0fa9](https://bsd-hardware.info/?probe=a0a04f0fa9) | Sep 27, 2024 |
| Unknown       | Unknown                     | [9be3134b8f](https://bsd-hardware.info/?probe=9be3134b8f) | Sep 26, 2024 |
| AZW           | EQ                          | [5cc403e6aa](https://bsd-hardware.info/?probe=5cc403e6aa) | Sep 24, 2024 |
| Unknown       | Unknown                     | [9fcfe381ae](https://bsd-hardware.info/?probe=9fcfe381ae) | Sep 24, 2024 |
| Intel         | PB-X6000                    | [b0a7e628cf](https://bsd-hardware.info/?probe=b0a7e628cf) | Sep 23, 2024 |
| Citrix        | CB-1100                     | [304a4f6d5f](https://bsd-hardware.info/?probe=304a4f6d5f) | Sep 23, 2024 |
| Protectli     | VP4630                      | [f599050faf](https://bsd-hardware.info/?probe=f599050faf) | Sep 18, 2024 |
| HP            | 870C                        | [6a8b48c698](https://bsd-hardware.info/?probe=6a8b48c698) | Sep 17, 2024 |
| Citrix        | CB-1100                     | [6e070920d0](https://bsd-hardware.info/?probe=6e070920d0) | Sep 15, 2024 |
| Unknown       | Unknown                     | [6575dfb8e4](https://bsd-hardware.info/?probe=6575dfb8e4) | Sep 15, 2024 |
| Gigabyte      | G41MT-ES2L                  | [8afe8ddad6](https://bsd-hardware.info/?probe=8afe8ddad6) | Sep 15, 2024 |
| MSI           | PRO Z690-A DDR4             | [0a5ecbce04](https://bsd-hardware.info/?probe=0a5ecbce04) | Sep 12, 2024 |
| Gigabyte      | G41MT-ES2L                  | [8016457889](https://bsd-hardware.info/?probe=8016457889) | Sep 10, 2024 |
| Unknown       | Unknown                     | [f19fafe503](https://bsd-hardware.info/?probe=f19fafe503) | Sep 07, 2024 |
| Unknown       | Unknown                     | [170e17cd46](https://bsd-hardware.info/?probe=170e17cd46) | Sep 07, 2024 |
| Gigabyte      | GA-78LMT-S2P                | [c1fb0928df](https://bsd-hardware.info/?probe=c1fb0928df) | Sep 06, 2024 |
| Unknown       | Unknown                     | [2399243ff8](https://bsd-hardware.info/?probe=2399243ff8) | Sep 06, 2024 |
| OEM           | PB-1900-A                   | [6334dac48a](https://bsd-hardware.info/?probe=6334dac48a) | Sep 06, 2024 |
| Trigkey       | Green G5                    | [fcaa5a268e](https://bsd-hardware.info/?probe=fcaa5a268e) | Sep 05, 2024 |
| Gigabyte      | B360M D3H-CF                | [b5d95279a6](https://bsd-hardware.info/?probe=b5d95279a6) | Sep 03, 2024 |
| Unknown       | Unknown                     | [13fa129348](https://bsd-hardware.info/?probe=13fa129348) | Aug 31, 2024 |
| Unknown       | Unknown                     | [e31fb6e0e8](https://bsd-hardware.info/?probe=e31fb6e0e8) | Aug 31, 2024 |
| Unknown       | Unknown                     | [a4cdaf25d6](https://bsd-hardware.info/?probe=a4cdaf25d6) | Aug 30, 2024 |
| Gigabyte      | B250M-D3H-CF                | [ce9b1b23e1](https://bsd-hardware.info/?probe=ce9b1b23e1) | Aug 29, 2024 |
| Trigkey       | Green G5                    | [13c389b9df](https://bsd-hardware.info/?probe=13c389b9df) | Aug 29, 2024 |
| Protectli     | FW4B                        | [92d79ae389](https://bsd-hardware.info/?probe=92d79ae389) | Aug 26, 2024 |
| Unknown       | Unknown                     | [104269f26b](https://bsd-hardware.info/?probe=104269f26b) | Aug 25, 2024 |
| Dell          | 0NC2VH A01                  | [cba2c1f636](https://bsd-hardware.info/?probe=cba2c1f636) | Aug 22, 2024 |
| CheckPoint    | T-120-00                    | [25c29c6dcc](https://bsd-hardware.info/?probe=25c29c6dcc) | Aug 21, 2024 |
| Unknown       | QDNV01                      | [2b68f6c1ec](https://bsd-hardware.info/?probe=2b68f6c1ec) | Aug 21, 2024 |
| HP            | 870C                        | [2a69ceab02](https://bsd-hardware.info/?probe=2a69ceab02) | Aug 19, 2024 |
| Unknown       | Unknown                     | [c1a44667bd](https://bsd-hardware.info/?probe=c1a44667bd) | Aug 14, 2024 |
| Unknown       | Unknown                     | [d69a19bb41](https://bsd-hardware.info/?probe=d69a19bb41) | Aug 12, 2024 |
| Unknown       | Unknown                     | [9a967b67dd](https://bsd-hardware.info/?probe=9a967b67dd) | Aug 08, 2024 |
| OEM           | PB-1900-A                   | [e45310d73f](https://bsd-hardware.info/?probe=e45310d73f) | Aug 04, 2024 |
| Gigabyte      | B250M-D3H-CF                | [43ccbf96cb](https://bsd-hardware.info/?probe=43ccbf96cb) | Aug 04, 2024 |
| Unknown       | Unknown                     | [edece0ced6](https://bsd-hardware.info/?probe=edece0ced6) | Aug 03, 2024 |
| HP            | 870C                        | [8f559ae44d](https://bsd-hardware.info/?probe=8f559ae44d) | Jul 31, 2024 |
| HP            | 870C                        | [00c53213af](https://bsd-hardware.info/?probe=00c53213af) | Jul 27, 2024 |
| Techvision    | TVI7309X B0                 | [1cc0e919ed](https://bsd-hardware.info/?probe=1cc0e919ed) | Jul 26, 2024 |
| Apple         | Mac-F221BEC8                | [dd834b1229](https://bsd-hardware.info/?probe=dd834b1229) | Jul 26, 2024 |
| Unknown       | Unknown                     | [7054a512d1](https://bsd-hardware.info/?probe=7054a512d1) | Jul 23, 2024 |
| Unknown       | Unknown                     | [90daceb808](https://bsd-hardware.info/?probe=90daceb808) | Jul 22, 2024 |
| Unknown       | Unknown                     | [ff3ada3808](https://bsd-hardware.info/?probe=ff3ada3808) | Jul 22, 2024 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [3ae423a460](https://bsd-hardware.info/?probe=3ae423a460) | Jul 14, 2024 |
| Unknown       | QGLK03                      | [2c06f0a474](https://bsd-hardware.info/?probe=2c06f0a474) | Jul 13, 2024 |
| Gigabyte      | B250M-D3H-CF                | [eb82e44d2d](https://bsd-hardware.info/?probe=eb82e44d2d) | Jul 10, 2024 |
| Unknown       | Unknown                     | [b9e0599645](https://bsd-hardware.info/?probe=b9e0599645) | Jul 10, 2024 |
| Techvision    | TVI7309X B0                 | [2676698df8](https://bsd-hardware.info/?probe=2676698df8) | Jul 03, 2024 |
| Protectli     | VP4650                      | [a9edd6c51a](https://bsd-hardware.info/?probe=a9edd6c51a) | Jul 03, 2024 |
| HP            | 870C                        | [655f793071](https://bsd-hardware.info/?probe=655f793071) | Jul 02, 2024 |
| HP            | 870C                        | [1cd554e5e9](https://bsd-hardware.info/?probe=1cd554e5e9) | Jul 01, 2024 |
| HP            | 870C                        | [2caaf86446](https://bsd-hardware.info/?probe=2caaf86446) | Jun 30, 2024 |
| Unknown       | Unknown                     | [d8e556e598](https://bsd-hardware.info/?probe=d8e556e598) | Jun 30, 2024 |
| Unknown       | Unknown                     | [82db566380](https://bsd-hardware.info/?probe=82db566380) | Jun 30, 2024 |
| Techvision    | TVI7309X B0                 | [0a8aa195eb](https://bsd-hardware.info/?probe=0a8aa195eb) | Jun 26, 2024 |
| HP            | 870C                        | [b844ce2068](https://bsd-hardware.info/?probe=b844ce2068) | Jun 26, 2024 |
| Dell          | 096JG8 A01                  | [6cba39a47b](https://bsd-hardware.info/?probe=6cba39a47b) | Jun 25, 2024 |
| Gigabyte      | B250M-D3H-CF                | [fb21431b06](https://bsd-hardware.info/?probe=fb21431b06) | Jun 24, 2024 |
| Dell          | 096JG8 A01                  | [24c2c59c3a](https://bsd-hardware.info/?probe=24c2c59c3a) | Jun 23, 2024 |
| Techvision    | TVI7309X B0                 | [9daa772291](https://bsd-hardware.info/?probe=9daa772291) | Jun 21, 2024 |
| Protectli     | VP2410 10                   | [3ffa3a7b97](https://bsd-hardware.info/?probe=3ffa3a7b97) | Jun 20, 2024 |
| Dell          | 0PC5F7 A00                  | [5c88193dc4](https://bsd-hardware.info/?probe=5c88193dc4) | Jun 16, 2024 |
| HP            | 83EE                        | [c5a71d4e06](https://bsd-hardware.info/?probe=c5a71d4e06) | Jun 15, 2024 |
| HP            | 82A2                        | [d4a521d5f7](https://bsd-hardware.info/?probe=d4a521d5f7) | Jun 13, 2024 |
| ASUSTek       | Z97-A                       | [f2787a24ba](https://bsd-hardware.info/?probe=f2787a24ba) | Jun 11, 2024 |
| OEM           | PB-1900-A                   | [af1a4c2802](https://bsd-hardware.info/?probe=af1a4c2802) | Jun 10, 2024 |
| Unknown       | Unknown                     | [0f3d5ece0c](https://bsd-hardware.info/?probe=0f3d5ece0c) | Jun 10, 2024 |
| ASUSTek       | CROSSHAIR VI HERO           | [51df4f57c5](https://bsd-hardware.info/?probe=51df4f57c5) | Jun 02, 2024 |
| Unknown       | Unknown                     | [94f269663c](https://bsd-hardware.info/?probe=94f269663c) | Jun 01, 2024 |
| Intel         | DENLOW_WS                   | [27f73c0ae9](https://bsd-hardware.info/?probe=27f73c0ae9) | May 31, 2024 |
| Unknown       | QDNV01                      | [5d8b4c676b](https://bsd-hardware.info/?probe=5d8b4c676b) | May 29, 2024 |
| Unknown       | Unknown                     | [c20215f991](https://bsd-hardware.info/?probe=c20215f991) | May 29, 2024 |
| Gigabyte      | Z790 EAGLE AX               | [65d52d2137](https://bsd-hardware.info/?probe=65d52d2137) | May 28, 2024 |
| Unknown       | Unknown                     | [d0919f78df](https://bsd-hardware.info/?probe=d0919f78df) | May 27, 2024 |
| Gigabyte      | Z790 EAGLE AX               | [354c2b5195](https://bsd-hardware.info/?probe=354c2b5195) | May 26, 2024 |
| Unknown       | Unknown                     | [c74d50d97d](https://bsd-hardware.info/?probe=c74d50d97d) | May 25, 2024 |
| IceWhale T... | ZimaBoard 432 ZMB           | [72d4c7046e](https://bsd-hardware.info/?probe=72d4c7046e) | May 23, 2024 |
| Gigabyte      | Z790 EAGLE AX               | [011ed158e0](https://bsd-hardware.info/?probe=011ed158e0) | May 18, 2024 |
| Gigabyte      | Z790 EAGLE AX               | [d96abdd063](https://bsd-hardware.info/?probe=d96abdd063) | May 17, 2024 |
| HP            | 83E1                        | [2227565c4c](https://bsd-hardware.info/?probe=2227565c4c) | May 15, 2024 |
| Intel         | QHSW02                      | [945cf47cc6](https://bsd-hardware.info/?probe=945cf47cc6) | May 14, 2024 |
| AMD           | Inagua CRB                  | [d5ba9b512c](https://bsd-hardware.info/?probe=d5ba9b512c) | May 13, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [e82997fc22](https://bsd-hardware.info/?probe=e82997fc22) | May 13, 2024 |
| HP            | 83EE                        | [cb1389a074](https://bsd-hardware.info/?probe=cb1389a074) | May 12, 2024 |
| Unknown       | QGLK03                      | [3a6ac054e6](https://bsd-hardware.info/?probe=3a6ac054e6) | May 09, 2024 |
| HP            | 83EE                        | [c2a0b11bfa](https://bsd-hardware.info/?probe=c2a0b11bfa) | May 08, 2024 |
| AZW           | EQ                          | [edb4b64548](https://bsd-hardware.info/?probe=edb4b64548) | May 06, 2024 |
| Intel         | MAHOBAY                     | [dfe3417cfb](https://bsd-hardware.info/?probe=dfe3417cfb) | May 05, 2024 |
| Unknown       | Unknown                     | [c77ff29728](https://bsd-hardware.info/?probe=c77ff29728) | May 04, 2024 |
| Intel         | PB-X6000                    | [23a7529eaa](https://bsd-hardware.info/?probe=23a7529eaa) | May 04, 2024 |
| Unknown       | Unknown                     | [da95fe1264](https://bsd-hardware.info/?probe=da95fe1264) | May 02, 2024 |
| Dell          | 0PC5F7 A00                  | [25be1b099a](https://bsd-hardware.info/?probe=25be1b099a) | May 02, 2024 |
| Dell          | 0PC5F7 A00                  | [217f8e63db](https://bsd-hardware.info/?probe=217f8e63db) | May 01, 2024 |
| Unknown       | Unknown                     | [1c2459184f](https://bsd-hardware.info/?probe=1c2459184f) | Apr 28, 2024 |
| Protectli     | VP4630                      | [a128743268](https://bsd-hardware.info/?probe=a128743268) | Apr 25, 2024 |
| Dell          | 0DNMV1 A01                  | [97161dac8a](https://bsd-hardware.info/?probe=97161dac8a) | Apr 24, 2024 |
| Gigabyte      | H110M-H-CF                  | [2000d6447a](https://bsd-hardware.info/?probe=2000d6447a) | Apr 23, 2024 |
| Gigabyte      | H110M-H-CF                  | [3e1def845f](https://bsd-hardware.info/?probe=3e1def845f) | Apr 23, 2024 |
| Gigabyte      | X570 AORUS MASTER           | [58a64ecc64](https://bsd-hardware.info/?probe=58a64ecc64) | Apr 23, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [d9b4db06cf](https://bsd-hardware.info/?probe=d9b4db06cf) | Apr 21, 2024 |
| Dell          | 0XCR8D A01                  | [716181ac45](https://bsd-hardware.info/?probe=716181ac45) | Apr 21, 2024 |
| Gigabyte      | B460 AORUS PRO AC           | [fe0730cde5](https://bsd-hardware.info/?probe=fe0730cde5) | Apr 20, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [572876d341](https://bsd-hardware.info/?probe=572876d341) | Apr 20, 2024 |
| AZW           | EQ                          | [f822d4127d](https://bsd-hardware.info/?probe=f822d4127d) | Apr 20, 2024 |
| Intel         | Q3XXG4-P V1.0               | [dd5c8c3088](https://bsd-hardware.info/?probe=dd5c8c3088) | Apr 17, 2024 |
| Techvision    | TVI7309X B0                 | [7e1d43786b](https://bsd-hardware.info/?probe=7e1d43786b) | Apr 15, 2024 |
| Intel         | MAHOBAY                     | [9202be9d8d](https://bsd-hardware.info/?probe=9202be9d8d) | Apr 12, 2024 |
| Protectli     | VP4650                      | [95ce732272](https://bsd-hardware.info/?probe=95ce732272) | Apr 12, 2024 |
| Unknown       | Unknown                     | [bafb4c3fd6](https://bsd-hardware.info/?probe=bafb4c3fd6) | Apr 06, 2024 |
| Intel         | SKYBAY                      | [7d6e63d688](https://bsd-hardware.info/?probe=7d6e63d688) | Apr 02, 2024 |
| Lenovo        | SHARKBAY 0C48431 WIN        | [893075f24f](https://bsd-hardware.info/?probe=893075f24f) | Apr 02, 2024 |
| HP            | 83E2                        | [c1765c598f](https://bsd-hardware.info/?probe=c1765c598f) | Apr 02, 2024 |
| Dell          | 0XCR8D A01                  | [39679bc463](https://bsd-hardware.info/?probe=39679bc463) | Apr 01, 2024 |
| Gigabyte      | B360M D3H-CF                | [f89dd6d1c9](https://bsd-hardware.info/?probe=f89dd6d1c9) | Mar 31, 2024 |
| Gigabyte      | B360M D3H-CF                | [28f484158e](https://bsd-hardware.info/?probe=28f484158e) | Mar 31, 2024 |
| Unknown       | Unknown                     | [673473a1a0](https://bsd-hardware.info/?probe=673473a1a0) | Mar 27, 2024 |
| MSI           | MS-B0A81                    | [17e87ae023](https://bsd-hardware.info/?probe=17e87ae023) | Mar 26, 2024 |
| Intel         | SKYBAY                      | [8aaca978dc](https://bsd-hardware.info/?probe=8aaca978dc) | Mar 26, 2024 |
| HP            | 870C                        | [736b0fa24b](https://bsd-hardware.info/?probe=736b0fa24b) | Mar 26, 2024 |
| Unknown       | Unknown                     | [5b7761ce38](https://bsd-hardware.info/?probe=5b7761ce38) | Mar 23, 2024 |
| OEM           | PB-1900-A                   | [7172e173cb](https://bsd-hardware.info/?probe=7172e173cb) | Mar 19, 2024 |
| Unknown       | Unknown                     | [5e613125ca](https://bsd-hardware.info/?probe=5e613125ca) | Mar 10, 2024 |
| Unknown       | Unknown                     | [3dadeb1ccc](https://bsd-hardware.info/?probe=3dadeb1ccc) | Mar 08, 2024 |
| Intel         | QHSW02                      | [54d2883b0f](https://bsd-hardware.info/?probe=54d2883b0f) | Mar 08, 2024 |
| Unknown       | Unknown                     | [cf72715739](https://bsd-hardware.info/?probe=cf72715739) | Mar 07, 2024 |
| Techvision    | TVI7309X B0                 | [e8ed936537](https://bsd-hardware.info/?probe=e8ed936537) | Mar 06, 2024 |
| Unknown       | Unknown                     | [ed75f5f715](https://bsd-hardware.info/?probe=ed75f5f715) | Mar 05, 2024 |
| Dell          | 0XCR8D A02                  | [8919d9eb09](https://bsd-hardware.info/?probe=8919d9eb09) | Mar 05, 2024 |
| Dell          | 07F37C A00                  | [53928dbf53](https://bsd-hardware.info/?probe=53928dbf53) | Mar 03, 2024 |
| MSI           | MS-B0A81                    | [2f6a08c240](https://bsd-hardware.info/?probe=2f6a08c240) | Mar 03, 2024 |
| Unknown       | Unknown                     | [83a5d4bd8b](https://bsd-hardware.info/?probe=83a5d4bd8b) | Mar 01, 2024 |
| HP            | 83EE                        | [0c83be53f1](https://bsd-hardware.info/?probe=0c83be53f1) | Feb 27, 2024 |
| Unknown       | Unknown                     | [dc82774d4b](https://bsd-hardware.info/?probe=dc82774d4b) | Feb 21, 2024 |
| Unknown       | Unknown                     | [c64774303d](https://bsd-hardware.info/?probe=c64774303d) | Feb 20, 2024 |
| Unknown       | Unknown                     | [e5e747ec86](https://bsd-hardware.info/?probe=e5e747ec86) | Feb 16, 2024 |
| Unknown       | Unknown                     | [7dc7c39f38](https://bsd-hardware.info/?probe=7dc7c39f38) | Feb 15, 2024 |
| Unknown       | Unknown                     | [7b626b5a2c](https://bsd-hardware.info/?probe=7b626b5a2c) | Feb 07, 2024 |
| HP            | 83EE                        | [3fdb0e4625](https://bsd-hardware.info/?probe=3fdb0e4625) | Feb 05, 2024 |
| HP            | 83EE                        | [92258e181d](https://bsd-hardware.info/?probe=92258e181d) | Feb 05, 2024 |
| Unknown       | Unknown                     | [5eb0f3d517](https://bsd-hardware.info/?probe=5eb0f3d517) | Jan 20, 2024 |
| Gigabyte      | J1900N-D3V                  | [4d9e3faf1d](https://bsd-hardware.info/?probe=4d9e3faf1d) | Jan 06, 2024 |
| Unknown       | Unknown                     | [3ae4489483](https://bsd-hardware.info/?probe=3ae4489483) | Jan 05, 2024 |
| HP            | 83EE                        | [cbfaae0ca7](https://bsd-hardware.info/?probe=cbfaae0ca7) | Jan 05, 2024 |
| Unknown       | Unknown                     | [0d4b103495](https://bsd-hardware.info/?probe=0d4b103495) | Jan 04, 2024 |
| Intel         | Q3XXG4-P V1.0               | [52345f2706](https://bsd-hardware.info/?probe=52345f2706) | Jan 02, 2024 |
| Hardkernel    | ODROID-H2                   | [959e70a37e](https://bsd-hardware.info/?probe=959e70a37e) | Jan 02, 2024 |
| Unknown       | Unknown                     | [5354734c83](https://bsd-hardware.info/?probe=5354734c83) | Dec 29, 2023 |
| Intel         | Q3XXG4-P V1.0               | [bc5f165c4a](https://bsd-hardware.info/?probe=bc5f165c4a) | Dec 29, 2023 |
| Unknown       | Unknown                     | [03f7101d55](https://bsd-hardware.info/?probe=03f7101d55) | Dec 25, 2023 |
| Dell          | 00V62H A00                  | [b99ed60ab6](https://bsd-hardware.info/?probe=b99ed60ab6) | Dec 18, 2023 |
| Dell          | 00V62H A00                  | [8f6f4d38d3](https://bsd-hardware.info/?probe=8f6f4d38d3) | Dec 17, 2023 |
| Techvision    | TVI7309X B0                 | [878769cc62](https://bsd-hardware.info/?probe=878769cc62) | Dec 17, 2023 |
| Lenovo        | SDK0E50510 WIN              | [57a4adcc91](https://bsd-hardware.info/?probe=57a4adcc91) | Dec 17, 2023 |
| Unknown       | Unknown                     | [784c8ae515](https://bsd-hardware.info/?probe=784c8ae515) | Dec 16, 2023 |
| HP            | 82A2                        | [906fd206fe](https://bsd-hardware.info/?probe=906fd206fe) | Dec 15, 2023 |
| HP            | 82A2                        | [0a816d2760](https://bsd-hardware.info/?probe=0a816d2760) | Dec 15, 2023 |
| Dell          | 0PC5F7 A00                  | [e47e643ced](https://bsd-hardware.info/?probe=e47e643ced) | Dec 14, 2023 |
| Intel         | DENLOW_WS                   | [d8b2ccabda](https://bsd-hardware.info/?probe=d8b2ccabda) | Nov 30, 2023 |
| Unknown       | Unknown                     | [2a34bc9613](https://bsd-hardware.info/?probe=2a34bc9613) | Nov 28, 2023 |
| AZW           | SER                         | [48a259ae28](https://bsd-hardware.info/?probe=48a259ae28) | Nov 28, 2023 |
| Unknown       | Unknown                     | [c8960ff614](https://bsd-hardware.info/?probe=c8960ff614) | Nov 22, 2023 |
| Unknown       | Unknown                     | [066991fce5](https://bsd-hardware.info/?probe=066991fce5) | Nov 16, 2023 |
| HP            | 213D A01                    | [eff9e5704a](https://bsd-hardware.info/?probe=eff9e5704a) | Nov 16, 2023 |
| Unknown       | Unknown                     | [696dae397c](https://bsd-hardware.info/?probe=696dae397c) | Nov 12, 2023 |
| Shenzhen M... | RPBNB                       | [ab2de15a7a](https://bsd-hardware.info/?probe=ab2de15a7a) | Nov 11, 2023 |
| Shenzhen M... | RPBNB                       | [b04823f9e5](https://bsd-hardware.info/?probe=b04823f9e5) | Nov 07, 2023 |
| Dell          | 0D24M8 A01                  | [4c874fa8af](https://bsd-hardware.info/?probe=4c874fa8af) | Nov 06, 2023 |
| Dell          | 0D24M8 A01                  | [3ca7f9b6d1](https://bsd-hardware.info/?probe=3ca7f9b6d1) | Nov 06, 2023 |
| Shuttle       | FS61                        | [1ed38ceb8c](https://bsd-hardware.info/?probe=1ed38ceb8c) | Nov 05, 2023 |
| Unknown       | Unknown                     | [97f4527aab](https://bsd-hardware.info/?probe=97f4527aab) | Nov 05, 2023 |
| HP            | 83EE                        | [1ab86be61a](https://bsd-hardware.info/?probe=1ab86be61a) | Nov 05, 2023 |
| HP            | 213D A01                    | [da7d91889e](https://bsd-hardware.info/?probe=da7d91889e) | Nov 03, 2023 |
| Unknown       | Unknown                     | [743d5aec59](https://bsd-hardware.info/?probe=743d5aec59) | Nov 02, 2023 |
| Intel         | Q3XXG4-P V1.0               | [cac29f9a35](https://bsd-hardware.info/?probe=cac29f9a35) | Oct 30, 2023 |
| Unknown       | Unknown                     | [850878776a](https://bsd-hardware.info/?probe=850878776a) | Oct 27, 2023 |
| HP            | 3397                        | [3dad1378f7](https://bsd-hardware.info/?probe=3dad1378f7) | Oct 27, 2023 |
| Winston Ma... | PICO PC V1.2                | [244102bda8](https://bsd-hardware.info/?probe=244102bda8) | Oct 26, 2023 |
| Intel         | MAHOBAY                     | [9b797e809a](https://bsd-hardware.info/?probe=9b797e809a) | Oct 26, 2023 |
| Intel         | MAHOBAY                     | [4dd20af1a3](https://bsd-hardware.info/?probe=4dd20af1a3) | Oct 26, 2023 |
| Intel         | MAHOBAY                     | [c66be142de](https://bsd-hardware.info/?probe=c66be142de) | Oct 26, 2023 |
| Unknown       | Unknown                     | [530528316f](https://bsd-hardware.info/?probe=530528316f) | Oct 21, 2023 |
| CWWK          | MINIPC-G12                  | [c51a6f8459](https://bsd-hardware.info/?probe=c51a6f8459) | Oct 20, 2023 |
| Unknown       | Unknown                     | [af12786272](https://bsd-hardware.info/?probe=af12786272) | Oct 18, 2023 |
| Unknown       | J3160-4L                    | [95e017977c](https://bsd-hardware.info/?probe=95e017977c) | Oct 14, 2023 |
| HP            | 83EE                        | [88d80d215a](https://bsd-hardware.info/?probe=88d80d215a) | Sep 30, 2023 |
| HP            | 83EE                        | [d08ae678b5](https://bsd-hardware.info/?probe=d08ae678b5) | Sep 28, 2023 |
| Unknown       | Unknown                     | [a5643cabc4](https://bsd-hardware.info/?probe=a5643cabc4) | Sep 24, 2023 |
| GoWin Solu... | R86S                        | [0cfd79f7fe](https://bsd-hardware.info/?probe=0cfd79f7fe) | Sep 18, 2023 |
| HP            | 82A2                        | [4f125fbc75](https://bsd-hardware.info/?probe=4f125fbc75) | Sep 17, 2023 |
| Unknown       | Unknown                     | [21e851e9e9](https://bsd-hardware.info/?probe=21e851e9e9) | Sep 07, 2023 |
| TYAN Compu... | S5510HE                     | [99d23c35ca](https://bsd-hardware.info/?probe=99d23c35ca) | Sep 07, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [3dab6f4044](https://bsd-hardware.info/?probe=3dab6f4044) | Aug 28, 2023 |
| Unknown       | Unknown                     | [b5a786e411](https://bsd-hardware.info/?probe=b5a786e411) | Aug 18, 2023 |
| ASUSTek       | PRIME B450M-K               | [74bfa3e0cd](https://bsd-hardware.info/?probe=74bfa3e0cd) | Aug 15, 2023 |
| Protectli     | FW4B Ver                    | [064ee65b5c](https://bsd-hardware.info/?probe=064ee65b5c) | Aug 10, 2023 |
| Techvision    | TVI7309X B0                 | [fd4046c4d9](https://bsd-hardware.info/?probe=fd4046c4d9) | Aug 07, 2023 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | [f65647a6be](https://bsd-hardware.info/?probe=f65647a6be) | Aug 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | [eee3c082b5](https://bsd-hardware.info/?probe=eee3c082b5) | Aug 05, 2023 |
| Unknown       | Unknown                     | [e9977bfffe](https://bsd-hardware.info/?probe=e9977bfffe) | Aug 02, 2023 |
| HP            | 18E9                        | [04c971a0de](https://bsd-hardware.info/?probe=04c971a0de) | Jul 31, 2023 |
| HP            | 83E1                        | [b211795736](https://bsd-hardware.info/?probe=b211795736) | Jul 27, 2023 |
| Unknown       | Unknown                     | [64c9b0f743](https://bsd-hardware.info/?probe=64c9b0f743) | Jul 25, 2023 |
| ASRock        | H570M-ITX/ac                | [8ac2939575](https://bsd-hardware.info/?probe=8ac2939575) | Jul 23, 2023 |
| Lenovo        | SDK0E50510 WIN              | [63ab45fcb1](https://bsd-hardware.info/?probe=63ab45fcb1) | Jul 21, 2023 |
| Unknown       | Unknown                     | [5bea9c433e](https://bsd-hardware.info/?probe=5bea9c433e) | Jul 17, 2023 |
| YANYU         | H67SL                       | [699da6c722](https://bsd-hardware.info/?probe=699da6c722) | Jul 13, 2023 |
| Gigabyte      | M85M-US2H                   | [e0a38ef6ad](https://bsd-hardware.info/?probe=e0a38ef6ad) | Jul 03, 2023 |
| PC Engines    | APU2                        | [c1272678e6](https://bsd-hardware.info/?probe=c1272678e6) | Jul 02, 2023 |
| Gigabyte      | H77M-D3H                    | [9f6d45e43e](https://bsd-hardware.info/?probe=9f6d45e43e) | Jul 02, 2023 |
| Gigabyte      | H77M-D3H                    | [3eb03fa8a7](https://bsd-hardware.info/?probe=3eb03fa8a7) | Jul 02, 2023 |
| HP            | 82A2                        | [4b8d139419](https://bsd-hardware.info/?probe=4b8d139419) | Jun 29, 2023 |
| Unknown       | Unknown                     | [23cdf1d4af](https://bsd-hardware.info/?probe=23cdf1d4af) | Jun 27, 2023 |
| Unknown       | Unknown                     | [a548b021da](https://bsd-hardware.info/?probe=a548b021da) | Jun 27, 2023 |
| YANYU         | H67SL                       | [5d5fd8a8cd](https://bsd-hardware.info/?probe=5d5fd8a8cd) | Jun 27, 2023 |
| HP            | 18E9                        | [aba608120b](https://bsd-hardware.info/?probe=aba608120b) | Jun 26, 2023 |
| Shuttle       | DH370                       | [95eb3bd4a8](https://bsd-hardware.info/?probe=95eb3bd4a8) | Jun 24, 2023 |
| Protectli     | FW4B                        | [6c993e8f34](https://bsd-hardware.info/?probe=6c993e8f34) | Jun 23, 2023 |
| Intel         | SKYBAY                      | [940adce39f](https://bsd-hardware.info/?probe=940adce39f) | Jun 23, 2023 |
| ASRock        | 4X4-4000 Series             | [c9420276e7](https://bsd-hardware.info/?probe=c9420276e7) | Jun 23, 2023 |
| Intel         | J1900                       | [4a3a52030b](https://bsd-hardware.info/?probe=4a3a52030b) | Jun 15, 2023 |
| Acer          | Aspire TC-230               | [d7eacfafe1](https://bsd-hardware.info/?probe=d7eacfafe1) | Jun 04, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [d4247f35c8](https://bsd-hardware.info/?probe=d4247f35c8) | Jun 02, 2023 |
| Dell          | 00V62H A01                  | [a87429607b](https://bsd-hardware.info/?probe=a87429607b) | Jun 01, 2023 |
| Intel         | QHSW02                      | [ed6d01bc2b](https://bsd-hardware.info/?probe=ed6d01bc2b) | May 31, 2023 |
| Intel         | QHSW02                      | [9f3d95a494](https://bsd-hardware.info/?probe=9f3d95a494) | May 31, 2023 |
| Protectli     | FW4B Ver                    | [1587da94da](https://bsd-hardware.info/?probe=1587da94da) | May 30, 2023 |
| Dell          | 0HD5W2 A00                  | [bd3ea7e1d6](https://bsd-hardware.info/?probe=bd3ea7e1d6) | May 28, 2023 |
| Intel         | J1900                       | [4d849f4f34](https://bsd-hardware.info/?probe=4d849f4f34) | May 27, 2023 |
| CWWK          | CW-AD4L-N V1                | [310da4e6e5](https://bsd-hardware.info/?probe=310da4e6e5) | May 26, 2023 |
| Dell          | 096JG8 A01                  | [f350405f61](https://bsd-hardware.info/?probe=f350405f61) | May 26, 2023 |
| Inventec      | R CLASS A02                 | [85f3673aa8](https://bsd-hardware.info/?probe=85f3673aa8) | May 24, 2023 |
| Intel         | J1900                       | [52081bc55b](https://bsd-hardware.info/?probe=52081bc55b) | May 24, 2023 |
| Dell          | 0M9KCM A02                  | [932e96060f](https://bsd-hardware.info/?probe=932e96060f) | May 21, 2023 |
| Dell          | 096JG8 A01                  | [3abf2c7ee2](https://bsd-hardware.info/?probe=3abf2c7ee2) | May 19, 2023 |
| Dell          | 096JG8 A01                  | [6f7bcae20b](https://bsd-hardware.info/?probe=6f7bcae20b) | May 19, 2023 |
| Protectli     | FW2B                        | [aa52b30ddf](https://bsd-hardware.info/?probe=aa52b30ddf) | May 14, 2023 |
| Dell          | 07F37C A00                  | [a23a95f97a](https://bsd-hardware.info/?probe=a23a95f97a) | May 07, 2023 |
| Dell          | 096JG8 A01                  | [633fa55df0](https://bsd-hardware.info/?probe=633fa55df0) | May 07, 2023 |
| Dell          | 0YC03K A04                  | [979aea14cc](https://bsd-hardware.info/?probe=979aea14cc) | May 06, 2023 |
| Unknown       | Unknown                     | [28253dd080](https://bsd-hardware.info/?probe=28253dd080) | Apr 28, 2023 |
| HP            | 82B4                        | [b75bb5fe83](https://bsd-hardware.info/?probe=b75bb5fe83) | Apr 20, 2023 |
| Techvision    | TVI7309X B0                 | [28c2a703c7](https://bsd-hardware.info/?probe=28c2a703c7) | Apr 18, 2023 |
| Gigabyte      | B560M DS3H V2               | [737250a1c8](https://bsd-hardware.info/?probe=737250a1c8) | Apr 15, 2023 |
| Dell          | 0HD5W2 A00                  | [1835073ded](https://bsd-hardware.info/?probe=1835073ded) | Apr 14, 2023 |
| MW            | GMLK-2_5G4L                 | [41bf2600a5](https://bsd-hardware.info/?probe=41bf2600a5) | Apr 13, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | [036b48e4c3](https://bsd-hardware.info/?probe=036b48e4c3) | Apr 13, 2023 |
| Acer          | Veriton X4630G              | [93987b345d](https://bsd-hardware.info/?probe=93987b345d) | Apr 12, 2023 |
| Acer          | Veriton M6620G              | [13f7e5c23b](https://bsd-hardware.info/?probe=13f7e5c23b) | Apr 07, 2023 |
| MW            | GMLK-2_5G4L                 | [459fdd8cdd](https://bsd-hardware.info/?probe=459fdd8cdd) | Mar 28, 2023 |
| HP            | 82B4                        | [6edc033f79](https://bsd-hardware.info/?probe=6edc033f79) | Mar 25, 2023 |
| Unknown       | Unknown                     | [a66dffcb5c](https://bsd-hardware.info/?probe=a66dffcb5c) | Mar 23, 2023 |
| Techvision    | TVI7309X B0                 | [7db8753b08](https://bsd-hardware.info/?probe=7db8753b08) | Mar 17, 2023 |
| Intel         | MAHOBAY                     | [b2176fafcf](https://bsd-hardware.info/?probe=b2176fafcf) | Mar 07, 2023 |
| ASUSTek       | PRIME A320M-E               | [ca70bceb83](https://bsd-hardware.info/?probe=ca70bceb83) | Mar 05, 2023 |
| AMD           | Kabini CRB                  | [c9e69ff953](https://bsd-hardware.info/?probe=c9e69ff953) | Mar 03, 2023 |
| Protectli     | VP2410 10                   | [74eedb42ea](https://bsd-hardware.info/?probe=74eedb42ea) | Mar 03, 2023 |
| Gigabyte      | Z87X-OC-CF                  | [dca82c50d0](https://bsd-hardware.info/?probe=dca82c50d0) | Feb 23, 2023 |
| Acer          | Aspire TC-230               | [f3f963fb6a](https://bsd-hardware.info/?probe=f3f963fb6a) | Feb 22, 2023 |
| Gigabyte      | A320M-H-CF                  | [02970305db](https://bsd-hardware.info/?probe=02970305db) | Feb 21, 2023 |
| ASUSTek       | H110I-PLUS D3               | [1f347f15e2](https://bsd-hardware.info/?probe=1f347f15e2) | Feb 19, 2023 |
| Protectli     | FW4B Ver                    | [81911bb61f](https://bsd-hardware.info/?probe=81911bb61f) | Feb 17, 2023 |
| ASUSTek       | H110I-PLUS D3               | [4d3dee18a0](https://bsd-hardware.info/?probe=4d3dee18a0) | Feb 16, 2023 |
| ASRock        | Z97 Killer                  | [67d58b9cde](https://bsd-hardware.info/?probe=67d58b9cde) | Feb 14, 2023 |
| Acer          | Aspire TC-230               | [a8ce4299ae](https://bsd-hardware.info/?probe=a8ce4299ae) | Feb 13, 2023 |
| PC Engines    | APU2                        | [3bc47445d4](https://bsd-hardware.info/?probe=3bc47445d4) | Jan 26, 2023 |
| IBM           | 9210MML                     | [8b7e2413ee](https://bsd-hardware.info/?probe=8b7e2413ee) | Jan 25, 2023 |
| ADI Engine... | RCC-VE                      | [e2941c00fc](https://bsd-hardware.info/?probe=e2941c00fc) | Jan 25, 2023 |
| Dell          | OptiPlex 3040               | [9c925f4e7f](https://bsd-hardware.info/?probe=9c925f4e7f) | Jan 23, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | [0d3e0df928](https://bsd-hardware.info/?probe=0d3e0df928) | Jan 20, 2023 |
| Gigabyte      | H110-D3A-CF                 | [6bb5667269](https://bsd-hardware.info/?probe=6bb5667269) | Jan 17, 2023 |
| HP            | 870C                        | [d7afab37f3](https://bsd-hardware.info/?probe=d7afab37f3) | Jan 15, 2023 |
| HP            | 870C                        | [7a5bbc7546](https://bsd-hardware.info/?probe=7a5bbc7546) | Jan 15, 2023 |
| Dell          | OptiPlex 3040               | [07abf8e8b2](https://bsd-hardware.info/?probe=07abf8e8b2) | Jan 14, 2023 |
| Gigabyte      | H110-D3A-CF                 | [9c1f7ead89](https://bsd-hardware.info/?probe=9c1f7ead89) | Jan 06, 2023 |
| Techvision    | TVI7309X B0                 | [b1ee757669](https://bsd-hardware.info/?probe=b1ee757669) | Jan 03, 2023 |
| Techvision    | TVI7309X B0                 | [5d360961d4](https://bsd-hardware.info/?probe=5d360961d4) | Jan 02, 2023 |
| Intel         | CRESCENTBAY                 | [d5f8e71171](https://bsd-hardware.info/?probe=d5f8e71171) | Jan 02, 2023 |
| HP            | ProLiant MicroServer        | [50c8cb79f7](https://bsd-hardware.info/?probe=50c8cb79f7) | Dec 26, 2022 |
| HP            | 870C                        | [6715ee2886](https://bsd-hardware.info/?probe=6715ee2886) | Dec 24, 2022 |
| Dell          | 0NW6H5 A00                  | [b19a4d1696](https://bsd-hardware.info/?probe=b19a4d1696) | Dec 23, 2022 |
| HP            | 870C                        | [d9eec3c9f5](https://bsd-hardware.info/?probe=d9eec3c9f5) | Dec 23, 2022 |
| Unknown       | Unknown                     | [0f03a7f2ce](https://bsd-hardware.info/?probe=0f03a7f2ce) | Dec 22, 2022 |
| Acer          | Veriton X2640G V:1.0        | [f241237f76](https://bsd-hardware.info/?probe=f241237f76) | Dec 22, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [a8ec4c3ae4](https://bsd-hardware.info/?probe=a8ec4c3ae4) | Dec 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [4667028e67](https://bsd-hardware.info/?probe=4667028e67) | Dec 20, 2022 |
| HP            | ProLiant MicroServer        | [b730e64d4a](https://bsd-hardware.info/?probe=b730e64d4a) | Dec 19, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [92593f4e79](https://bsd-hardware.info/?probe=92593f4e79) | Dec 17, 2022 |
| ASUSTek       | STRIX Z270I GAMING          | [d44c580408](https://bsd-hardware.info/?probe=d44c580408) | Dec 16, 2022 |
| Dell          | 08NPPY A00                  | [e199c0ec3d](https://bsd-hardware.info/?probe=e199c0ec3d) | Dec 15, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [d7d0ebf605](https://bsd-hardware.info/?probe=d7d0ebf605) | Dec 15, 2022 |
| HP            | ProLiant MicroServer        | [617f431099](https://bsd-hardware.info/?probe=617f431099) | Dec 14, 2022 |
| Unknown       | Unknown                     | [85520bf6bf](https://bsd-hardware.info/?probe=85520bf6bf) | Dec 14, 2022 |
| HP            | 82A2                        | [c612b7e283](https://bsd-hardware.info/?probe=c612b7e283) | Dec 06, 2022 |
| Protectli     | FW4B Ver                    | [4bf1aae972](https://bsd-hardware.info/?probe=4bf1aae972) | Dec 02, 2022 |
| Shuttle       | FS81                        | [f714ba647f](https://bsd-hardware.info/?probe=f714ba647f) | Nov 28, 2022 |
| Protectli     | FW2B                        | [d15326180f](https://bsd-hardware.info/?probe=d15326180f) | Nov 10, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [9945b6b3e7](https://bsd-hardware.info/?probe=9945b6b3e7) | Nov 09, 2022 |
| HP            | ProLiant MicroServer        | [798219138a](https://bsd-hardware.info/?probe=798219138a) | Nov 07, 2022 |
| HP            | ProLiant MicroServer        | [394e873da0](https://bsd-hardware.info/?probe=394e873da0) | Nov 07, 2022 |
| ASRock        | H570M-ITX/ac                | [06a8abdbf4](https://bsd-hardware.info/?probe=06a8abdbf4) | Oct 29, 2022 |
| Dell          | 0HD5W2 A00                  | [7b330abf44](https://bsd-hardware.info/?probe=7b330abf44) | Oct 26, 2022 |
| Unknown       | Unknown                     | [1f2cd1f9ea](https://bsd-hardware.info/?probe=1f2cd1f9ea) | Oct 24, 2022 |
| MSI           | MAG B550M MORTAR            | [607fcd2571](https://bsd-hardware.info/?probe=607fcd2571) | Oct 24, 2022 |
| Dell          | 0200DY A02                  | [d32449b8c4](https://bsd-hardware.info/?probe=d32449b8c4) | Oct 16, 2022 |
| Dell          | 0HD5W2 A00                  | [f80953ee2f](https://bsd-hardware.info/?probe=f80953ee2f) | Oct 16, 2022 |
| Dell          | 0HD5W2 A00                  | [f27ffa7217](https://bsd-hardware.info/?probe=f27ffa7217) | Oct 16, 2022 |
| MW            | GMLK-2_5G4L                 | [ae4868c65b](https://bsd-hardware.info/?probe=ae4868c65b) | Oct 15, 2022 |
| PC Engines    | apu1                        | [06debf0076](https://bsd-hardware.info/?probe=06debf0076) | Oct 14, 2022 |
| Unknown       | Unknown                     | [6c330d9bab](https://bsd-hardware.info/?probe=6c330d9bab) | Oct 14, 2022 |
| Unknown       | YL-1900L4-V2                | [1f55db62cc](https://bsd-hardware.info/?probe=1f55db62cc) | Oct 12, 2022 |
| ASRock        | H570M-ITX/ac                | [ea8b1fd760](https://bsd-hardware.info/?probe=ea8b1fd760) | Oct 12, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [9d3b9cb318](https://bsd-hardware.info/?probe=9d3b9cb318) | Oct 11, 2022 |
| Unknown       | Unknown                     | [7718c8e9ca](https://bsd-hardware.info/?probe=7718c8e9ca) | Oct 05, 2022 |
| Protectli     | FW4B Ver                    | [63b36c077a](https://bsd-hardware.info/?probe=63b36c077a) | Oct 05, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [e001150f93](https://bsd-hardware.info/?probe=e001150f93) | Oct 03, 2022 |
| IBM           | 9210MML                     | [a6e7d7483f](https://bsd-hardware.info/?probe=a6e7d7483f) | Oct 03, 2022 |
| Unknown       | Unknown                     | [9f998deaa4](https://bsd-hardware.info/?probe=9f998deaa4) | Sep 25, 2022 |
| Unknown       | Unknown                     | [ffa40a08e8](https://bsd-hardware.info/?probe=ffa40a08e8) | Sep 23, 2022 |
| Protectli     | FW4B Ver                    | [58caab8946](https://bsd-hardware.info/?probe=58caab8946) | Sep 14, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | [05b5d1e01a](https://bsd-hardware.info/?probe=05b5d1e01a) | Sep 12, 2022 |
| AOpen         | iBTMx-DS R1.03 55DED10A0... | [50ac5c0aaf](https://bsd-hardware.info/?probe=50ac5c0aaf) | Sep 10, 2022 |
| Dell          | 0200DY A02                  | [cd90f548c8](https://bsd-hardware.info/?probe=cd90f548c8) | Sep 06, 2022 |
| Protectli     | FW4B Ver                    | [91664c3bc1](https://bsd-hardware.info/?probe=91664c3bc1) | Sep 05, 2022 |
| MW            | GMLK-2_5G4L                 | [bb379f7083](https://bsd-hardware.info/?probe=bb379f7083) | Sep 03, 2022 |
| Gigabyte      | H81M-DS2                    | [75ec0260f9](https://bsd-hardware.info/?probe=75ec0260f9) | Aug 28, 2022 |
| Unknown       | YL-J3160L4                  | [aad241ba36](https://bsd-hardware.info/?probe=aad241ba36) | Aug 08, 2022 |
| Gigabyte      | H81M-DS2                    | [5b88dea745](https://bsd-hardware.info/?probe=5b88dea745) | Aug 06, 2022 |
| Protectli     | VP2410                      | [f9b42e4a75](https://bsd-hardware.info/?probe=f9b42e4a75) | Jul 27, 2022 |
| Protectli     | VP2410                      | [db66cc446e](https://bsd-hardware.info/?probe=db66cc446e) | Jul 27, 2022 |
| HP            | 8055                        | [269b4f3210](https://bsd-hardware.info/?probe=269b4f3210) | Jul 17, 2022 |
| Intel         | Q3XXG4-P V1.0               | [607a66e533](https://bsd-hardware.info/?probe=607a66e533) | Jul 14, 2022 |
| AZW           | GK55                        | [40d9df6faa](https://bsd-hardware.info/?probe=40d9df6faa) | Jul 12, 2022 |
| Lenovo        | SHARKBAY NOK                | [f68c3695ea](https://bsd-hardware.info/?probe=f68c3695ea) | Jul 08, 2022 |
| Dell          | 00V62H A00                  | [a3aff65df2](https://bsd-hardware.info/?probe=a3aff65df2) | Jun 27, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [4d4993a732](https://bsd-hardware.info/?probe=4d4993a732) | Jun 24, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [7d054ce34f](https://bsd-hardware.info/?probe=7d054ce34f) | Jun 23, 2022 |
| HP            | ProLiant ML10 v2            | [72254b033d](https://bsd-hardware.info/?probe=72254b033d) | Jun 06, 2022 |
| Dell          | 0MGK50 A02                  | [1de9982d19](https://bsd-hardware.info/?probe=1de9982d19) | Jun 05, 2022 |
| AOpen         | iBTMx-DS R1.03 55DED10A0... | [94bdba6302](https://bsd-hardware.info/?probe=94bdba6302) | Jun 04, 2022 |
| Protectli     | FW4B Ver                    | [f1838b29ff](https://bsd-hardware.info/?probe=f1838b29ff) | Jun 01, 2022 |
| MW            | GMLK-2_5G4L                 | [fdab123532](https://bsd-hardware.info/?probe=fdab123532) | May 07, 2022 |
| MW            | GMLK-2_5G4L                 | [59083ac5ac](https://bsd-hardware.info/?probe=59083ac5ac) | May 06, 2022 |
| MSI           | 2A9C                        | [506b970279](https://bsd-hardware.info/?probe=506b970279) | May 03, 2022 |
| HP            | 0B4Ch D                     | [3f170bdee6](https://bsd-hardware.info/?probe=3f170bdee6) | May 01, 2022 |
| ASUSTek       | AM1M-A                      | [76a2d4f148](https://bsd-hardware.info/?probe=76a2d4f148) | Apr 22, 2022 |
| MSI           | 2A9C                        | [595c9a1da2](https://bsd-hardware.info/?probe=595c9a1da2) | Apr 18, 2022 |
| MSI           | 2A9C                        | [7f44d30f83](https://bsd-hardware.info/?probe=7f44d30f83) | Apr 15, 2022 |
| Lenovo        | SHARKBAY NOK                | [e32f0f2130](https://bsd-hardware.info/?probe=e32f0f2130) | Apr 08, 2022 |
| ASRock        | 970 Pro3 R2.0               | [c807e1d8eb](https://bsd-hardware.info/?probe=c807e1d8eb) | Apr 07, 2022 |
| Protectli     | FW4B                        | [a2f902524b](https://bsd-hardware.info/?probe=a2f902524b) | Apr 06, 2022 |
| Protectli     | FW4B                        | [af9f2d81b5](https://bsd-hardware.info/?probe=af9f2d81b5) | Apr 06, 2022 |
| Gigabyte      | Z87N-WIFI                   | [1800a41f61](https://bsd-hardware.info/?probe=1800a41f61) | Mar 28, 2022 |
| Inventec      | D CLASS A02                 | [2ea328c95d](https://bsd-hardware.info/?probe=2ea328c95d) | Mar 28, 2022 |
| Gigabyte      | Z87N-WIFI                   | [8f20a3214b](https://bsd-hardware.info/?probe=8f20a3214b) | Mar 25, 2022 |
| Intel         | Q3XXG4-P V1.0               | [1e9ea7cdbc](https://bsd-hardware.info/?probe=1e9ea7cdbc) | Mar 19, 2022 |
| Dell          | 00V62H A00                  | [8da46f8dd0](https://bsd-hardware.info/?probe=8da46f8dd0) | Mar 18, 2022 |
| Gigabyte      | 970A-D3P                    | [fa03bdabb6](https://bsd-hardware.info/?probe=fa03bdabb6) | Mar 15, 2022 |
| MSI           | MS-B1831                    | [346c445c21](https://bsd-hardware.info/?probe=346c445c21) | Mar 12, 2022 |
| MSI           | MS-B1831                    | [572bb2c98c](https://bsd-hardware.info/?probe=572bb2c98c) | Mar 02, 2022 |
| Protectli     | VP2410 10                   | [8d5986c1f4](https://bsd-hardware.info/?probe=8d5986c1f4) | Feb 26, 2022 |
| MSI           | MAG B550M BAZOOKA           | [68f6eb4328](https://bsd-hardware.info/?probe=68f6eb4328) | Feb 23, 2022 |
| MSI           | MAG B550M BAZOOKA           | [c1397b851e](https://bsd-hardware.info/?probe=c1397b851e) | Feb 22, 2022 |
| Protectli     | VP2410 10                   | [1d9eaaaf62](https://bsd-hardware.info/?probe=1d9eaaaf62) | Feb 18, 2022 |
| Hardkernel    | ODROID-H2                   | [adcfe67709](https://bsd-hardware.info/?probe=adcfe67709) | Feb 16, 2022 |
| MSI           | MS-B1831                    | [5bdc589f33](https://bsd-hardware.info/?probe=5bdc589f33) | Feb 10, 2022 |
| HP            | ProLiant MicroServer Gen... | [0cc80ca4ec](https://bsd-hardware.info/?probe=0cc80ca4ec) | Feb 07, 2022 |
| MSI           | MS-B1831                    | [c8072d090e](https://bsd-hardware.info/?probe=c8072d090e) | Feb 06, 2022 |
| Protectli     | FW4B Ver                    | [6eecbfde04](https://bsd-hardware.info/?probe=6eecbfde04) | Feb 05, 2022 |
| Lenovo        | ThinkCentre M58 7360BB6     | [8751a2776e](https://bsd-hardware.info/?probe=8751a2776e) | Jan 31, 2022 |
| Dell          | 0NW6H5 A00                  | [21e1806645](https://bsd-hardware.info/?probe=21e1806645) | Jan 29, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | [50b7edb511](https://bsd-hardware.info/?probe=50b7edb511) | Jan 29, 2022 |
| Dell          | 0NW6H5 A00                  | [8587a16b51](https://bsd-hardware.info/?probe=8587a16b51) | Jan 29, 2022 |
| Lenovo        | SHARKBAY NOK                | [6ea3284f28](https://bsd-hardware.info/?probe=6ea3284f28) | Jan 29, 2022 |
| Lenovo        | ThinkCentre M58 7360BB6     | [f53622f02b](https://bsd-hardware.info/?probe=f53622f02b) | Jan 27, 2022 |
| HP            | ProLiant MicroServer        | [b62251041b](https://bsd-hardware.info/?probe=b62251041b) | Jan 26, 2022 |
| Cisco         | ASA5512 A0                  | [99d276f574](https://bsd-hardware.info/?probe=99d276f574) | Jan 18, 2022 |
| Dell          | 0XCR8D A03                  | [48e9447b37](https://bsd-hardware.info/?probe=48e9447b37) | Jan 15, 2022 |
| Gigabyte      | Z77N-WIFI                   | [459bb6486d](https://bsd-hardware.info/?probe=459bb6486d) | Jan 13, 2022 |
| Protectli     | FW4B Ver                    | [e0eb7a3239](https://bsd-hardware.info/?probe=e0eb7a3239) | Jan 13, 2022 |
| HP            | 1998                        | [1d46974005](https://bsd-hardware.info/?probe=1d46974005) | Jan 03, 2022 |
| HP            | ProLiant MicroServer        | [d641a4bea9](https://bsd-hardware.info/?probe=d641a4bea9) | Dec 30, 2021 |
| ASUSTek       | X99-E-10G WS                | [dacf7f604c](https://bsd-hardware.info/?probe=dacf7f604c) | Dec 20, 2021 |
| Intel         | SKYBAY                      | [40d8768e52](https://bsd-hardware.info/?probe=40d8768e52) | Dec 20, 2021 |
| Protectli     | FW6 Ver                     | [52ba0807f9](https://bsd-hardware.info/?probe=52ba0807f9) | Dec 17, 2021 |
| Intel         | Q3XXG4-P V1.0               | [bc910b229a](https://bsd-hardware.info/?probe=bc910b229a) | Dec 12, 2021 |
| Intel         | Q3XXG4-P V1.0               | [ab56e6eca2](https://bsd-hardware.info/?probe=ab56e6eca2) | Nov 23, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | [645f845f43](https://bsd-hardware.info/?probe=645f845f43) | Nov 21, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | [8a8efba0b3](https://bsd-hardware.info/?probe=8a8efba0b3) | Nov 19, 2021 |
| Dell          | 0T10XW A01                  | [ae2203b146](https://bsd-hardware.info/?probe=ae2203b146) | Nov 12, 2021 |
| AAEON         | EMB-H61A V1.0               | [f13f63617f](https://bsd-hardware.info/?probe=f13f63617f) | Nov 11, 2021 |
| Protectli     | FW4B Ver                    | [fc32ac51e4](https://bsd-hardware.info/?probe=fc32ac51e4) | Nov 10, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | [4d9532acfa](https://bsd-hardware.info/?probe=4d9532acfa) | Nov 07, 2021 |
| ASRock        | X370 Gaming X               | [2a874a33dd](https://bsd-hardware.info/?probe=2a874a33dd) | Nov 05, 2021 |
| Gateway       | DX4840                      | [1d2e9e175c](https://bsd-hardware.info/?probe=1d2e9e175c) | Nov 01, 2021 |
| Dell          | 0NW6H5 A00                  | [1f3657128e](https://bsd-hardware.info/?probe=1f3657128e) | Oct 30, 2021 |
| ADI Engine... | RCC-VE                      | [9744b5eca0](https://bsd-hardware.info/?probe=9744b5eca0) | Oct 29, 2021 |
| HP            | 18E9                        | [9c9a3a0297](https://bsd-hardware.info/?probe=9c9a3a0297) | Oct 27, 2021 |
| ASUSTek       | P10S WS                     | [e2d86f8c45](https://bsd-hardware.info/?probe=e2d86f8c45) | Oct 23, 2021 |
| HP            | ProLiant ML150 G6           | [06b8fc5c06](https://bsd-hardware.info/?probe=06b8fc5c06) | Oct 18, 2021 |
| Hardkernel    | ODROID-H2                   | [63850e668d](https://bsd-hardware.info/?probe=63850e668d) | Oct 16, 2021 |
| Protectli     | FW4B                        | [e20e889703](https://bsd-hardware.info/?probe=e20e889703) | Oct 16, 2021 |
| Acer          | Veriton X4610G              | [2ca4d093d3](https://bsd-hardware.info/?probe=2ca4d093d3) | Oct 01, 2021 |
| ASRock        | B560M Pro4/ac               | [1b057f3b7d](https://bsd-hardware.info/?probe=1b057f3b7d) | Sep 23, 2021 |
| ASRock        | B560M Pro4/ac               | [fcf75fc410](https://bsd-hardware.info/?probe=fcf75fc410) | Sep 23, 2021 |
| Yanling       | YL-KBR6L Ver:1.00           | [be32d2981b](https://bsd-hardware.info/?probe=be32d2981b) | Sep 19, 2021 |
| Gigabyte      | EP45-UD3R                   | [21e4a40d62](https://bsd-hardware.info/?probe=21e4a40d62) | Sep 18, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | [49f080ea2e](https://bsd-hardware.info/?probe=49f080ea2e) | Sep 12, 2021 |
| Dell          | 0NW6H5 A00                  | [8125c50b2a](https://bsd-hardware.info/?probe=8125c50b2a) | Sep 11, 2021 |
| Protectli     | FW4B                        | [941392a0bb](https://bsd-hardware.info/?probe=941392a0bb) | Sep 11, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | [fa4da2509b](https://bsd-hardware.info/?probe=fa4da2509b) | Sep 03, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | [97035edd33](https://bsd-hardware.info/?probe=97035edd33) | Sep 03, 2021 |
| ASRock        | Z390 Pro4                   | [ecbf097bc5](https://bsd-hardware.info/?probe=ecbf097bc5) | Sep 02, 2021 |
| HP            | ProLiant MicroServer        | [114ef9a519](https://bsd-hardware.info/?probe=114ef9a519) | Aug 30, 2021 |
| ASRock        | 990FX Killer                | [9f6f8fe218](https://bsd-hardware.info/?probe=9f6f8fe218) | Aug 22, 2021 |
| ASRock        | Z390 Pro4                   | [aca402061b](https://bsd-hardware.info/?probe=aca402061b) | Aug 18, 2021 |
| Foxconn       | 2ADA                        | [e96976b2cc](https://bsd-hardware.info/?probe=e96976b2cc) | Aug 18, 2021 |
| HP            | 1825                        | [970bb6f787](https://bsd-hardware.info/?probe=970bb6f787) | Aug 17, 2021 |
| Acer          | Veriton X4610G              | [619dedc13e](https://bsd-hardware.info/?probe=619dedc13e) | Aug 11, 2021 |
| Dell          | 0XPDFK A01                  | [97781253f2](https://bsd-hardware.info/?probe=97781253f2) | Aug 03, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | [8e67b63c6a](https://bsd-hardware.info/?probe=8e67b63c6a) | Jul 19, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | [cfb68fd411](https://bsd-hardware.info/?probe=cfb68fd411) | Jul 14, 2021 |
| HP            | ProLiant MicroServer Gen... | [519168441f](https://bsd-hardware.info/?probe=519168441f) | Jul 10, 2021 |
| Dell          | 0NW6H5 A00                  | [d713cecb20](https://bsd-hardware.info/?probe=d713cecb20) | Jul 10, 2021 |
| ASRock        | Z390 Pro4                   | [dc4eb674ea](https://bsd-hardware.info/?probe=dc4eb674ea) | Jul 03, 2021 |
| Protectli     | FW2B Ver                    | [7b6f704247](https://bsd-hardware.info/?probe=7b6f704247) | Jun 30, 2021 |
| Dell          | 0GTK4K A02                  | [53f4f785ba](https://bsd-hardware.info/?probe=53f4f785ba) | Jun 22, 2021 |
| Dell          | 0GTK4K A02                  | [bb610333d0](https://bsd-hardware.info/?probe=bb610333d0) | Jun 22, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | [2a6f8cdb64](https://bsd-hardware.info/?probe=2a6f8cdb64) | Jun 20, 2021 |
| Gigabyte      | J1900N-D3V                  | [c2cdbdb012](https://bsd-hardware.info/?probe=c2cdbdb012) | Jun 15, 2021 |
| Protectli     | VP2410 10                   | [27a4d07d70](https://bsd-hardware.info/?probe=27a4d07d70) | Jun 12, 2021 |
| Protectli     | VP2410 10                   | [5dd0792386](https://bsd-hardware.info/?probe=5dd0792386) | Jun 12, 2021 |
| Unknown       | J3160-4L                    | [3e773132b3](https://bsd-hardware.info/?probe=3e773132b3) | Jun 06, 2021 |
| Protectli     | FW4B Ver                    | [700ba3f063](https://bsd-hardware.info/?probe=700ba3f063) | May 31, 2021 |
| ASUSTek       | PRIME A320M-A               | [10d9e99990](https://bsd-hardware.info/?probe=10d9e99990) | May 31, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | [33b86a7df2](https://bsd-hardware.info/?probe=33b86a7df2) | May 22, 2021 |
| Unknown       | Unknown                     | [7ea373882a](https://bsd-hardware.info/?probe=7ea373882a) | May 19, 2021 |
| Unknown       | Unknown                     | [72eb276213](https://bsd-hardware.info/?probe=72eb276213) | May 05, 2021 |
| Shuttle       | DH370                       | [ad380cb985](https://bsd-hardware.info/?probe=ad380cb985) | May 04, 2021 |
| Lenovo        | SHARKBAY SDK0J40705 WIN     | [6a62687665](https://bsd-hardware.info/?probe=6a62687665) | May 03, 2021 |
| Gigabyte      | J1900N-D3V                  | [3e211c52ea](https://bsd-hardware.info/?probe=3e211c52ea) | Apr 21, 2021 |
| ASUSTek       | PRIME H310M-K               | [cb97f230b8](https://bsd-hardware.info/?probe=cb97f230b8) | Apr 09, 2021 |
| Dell          | 0WMJ54 A01                  | [bc3913fead](https://bsd-hardware.info/?probe=bc3913fead) | Apr 06, 2021 |
| Hardkernel    | ODROID-H2                   | [bcaa207f9b](https://bsd-hardware.info/?probe=bcaa207f9b) | Apr 05, 2021 |
| Unknown       | Unknown                     | [e66fe7a153](https://bsd-hardware.info/?probe=e66fe7a153) | Mar 21, 2021 |
| Gigabyte      | H270N-WIFI-CF               | [bf9f69e68b](https://bsd-hardware.info/?probe=bf9f69e68b) | Mar 11, 2021 |
| Dell          | 0NW6H5 A00                  | [bb7f6e1db9](https://bsd-hardware.info/?probe=bb7f6e1db9) | Mar 10, 2021 |
| Gigabyte      | H270N-WIFI-CF               | [c88b021c05](https://bsd-hardware.info/?probe=c88b021c05) | Mar 09, 2021 |
| Gigabyte      | H270N-WIFI-CF               | [7201058b50](https://bsd-hardware.info/?probe=7201058b50) | Mar 08, 2021 |
| Unknown       | Unknown                     | [635419dc18](https://bsd-hardware.info/?probe=635419dc18) | Mar 07, 2021 |
| ASUSTek       | X99-E-10G WS                | [4e73497945](https://bsd-hardware.info/?probe=4e73497945) | Mar 06, 2021 |
| PC Engines    | apu4                        | [2a3c8a81d5](https://bsd-hardware.info/?probe=2a3c8a81d5) | Mar 02, 2021 |
| Dell          | 0NW6H5 A00                  | [ec20bc7cea](https://bsd-hardware.info/?probe=ec20bc7cea) | Feb 28, 2021 |
| Lenovo        | MAHOBAY NOK                 | [8fda503f16](https://bsd-hardware.info/?probe=8fda503f16) | Feb 27, 2021 |
| ASUSTek       | B75M-PLUS                   | [8379cc790c](https://bsd-hardware.info/?probe=8379cc790c) | Feb 25, 2021 |
| Dell          | 0XCR8D A03                  | [8aa33e35ad](https://bsd-hardware.info/?probe=8aa33e35ad) | Feb 21, 2021 |
| Hardkernel    | ODROID-H2                   | [1f25ddeb54](https://bsd-hardware.info/?probe=1f25ddeb54) | Feb 20, 2021 |
| Unknown       | Unknown                     | [6b724a36cd](https://bsd-hardware.info/?probe=6b724a36cd) | Feb 19, 2021 |
| Unknown       | Unknown                     | [baf854930a](https://bsd-hardware.info/?probe=baf854930a) | Feb 19, 2021 |
| ASRock        | B365M Pro4                  | [1c438d977e](https://bsd-hardware.info/?probe=1c438d977e) | Feb 18, 2021 |
| Intel         | DN2820FYK H24582-201        | [be56203e79](https://bsd-hardware.info/?probe=be56203e79) | Feb 15, 2021 |
| ASUSTek       | P5E3                        | [1d1edd3551](https://bsd-hardware.info/?probe=1d1edd3551) | Feb 08, 2021 |
| Yanling       | YL-KBR6L Ver:1.00           | [98e358b324](https://bsd-hardware.info/?probe=98e358b324) | Feb 05, 2021 |
| Radxa         | ROCK Pi X v1.4              | [688c95bda6](https://bsd-hardware.info/?probe=688c95bda6) | Feb 05, 2021 |
| Lenovo        | SDK0E50510 WIN              | [a7b2c5457c](https://bsd-hardware.info/?probe=a7b2c5457c) | Jan 29, 2021 |
| Gigabyte      | Z68MA-D2H-B3                | [40793aaedb](https://bsd-hardware.info/?probe=40793aaedb) | Jan 26, 2021 |
| Gigabyte      | Z68MA-D2H-B3                | [a2c7bfe3a1](https://bsd-hardware.info/?probe=a2c7bfe3a1) | Jan 26, 2021 |
| Yanling       | YL-KBR6L Ver:1.00           | [a344f83f2e](https://bsd-hardware.info/?probe=a344f83f2e) | Jan 25, 2021 |
| Acer          | Veriton S6610G              | [64587ce287](https://bsd-hardware.info/?probe=64587ce287) | Jan 23, 2021 |
| HP            | ProLiant MicroServer        | [a78907417f](https://bsd-hardware.info/?probe=a78907417f) | Jan 22, 2021 |
| Dell          | 0NW6H5 A00                  | [4afdd92b10](https://bsd-hardware.info/?probe=4afdd92b10) | Jan 20, 2021 |
| HP            | ProLiant MicroServer        | [f51f3873ce](https://bsd-hardware.info/?probe=f51f3873ce) | Dec 25, 2020 |
| ASRock        | A320M-HDV R4.0              | [5e8506d20e](https://bsd-hardware.info/?probe=5e8506d20e) | Dec 24, 2020 |
| HP            | 0B4Ch D                     | [bf0d7fe4f1](https://bsd-hardware.info/?probe=bf0d7fe4f1) | Dec 22, 2020 |
| ASRock        | X370 Gaming-ITX/ac          | [33724c243d](https://bsd-hardware.info/?probe=33724c243d) | Dec 06, 2020 |
| Dell          | 0M5DCD A00                  | [ec13cfdd0d](https://bsd-hardware.info/?probe=ec13cfdd0d) | Oct 29, 2020 |
| Dell          | 042P49 A02                  | [c34a9c7091](https://bsd-hardware.info/?probe=c34a9c7091) | Oct 29, 2020 |
| HP            | ProLiant MicroServer        | [c1c3ffb720](https://bsd-hardware.info/?probe=c1c3ffb720) | Oct 29, 2020 |
| Unknown       | Unknown                     | [a28ef1d2b8](https://bsd-hardware.info/?probe=a28ef1d2b8) | Oct 20, 2020 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [af179a268f](https://bsd-hardware.info/?probe=af179a268f) | Oct 19, 2020 |
| Unknown       | Unknown                     | [864589fce0](https://bsd-hardware.info/?probe=864589fce0) | Oct 02, 2020 |
| Dell          | 0D6H9T A00                  | [764aaaa200](https://bsd-hardware.info/?probe=764aaaa200) | Jun 04, 2020 |
| Dell          | 0D6H9T A00                  | [158ff0f1b6](https://bsd-hardware.info/?probe=158ff0f1b6) | Jun 04, 2020 |
| HP            | ProLiant ML10 v2            | [aea3696f41](https://bsd-hardware.info/?probe=aea3696f41) | May 24, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Australia/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| OPNsense 25.7.3   | 17       | 2.88%   |
| OPNsense 24.1.6   | 16       | 2.71%   |
| OPNsense 24.7.12  | 13       | 2.2%    |
| OPNsense 25.1.5   | 12       | 2.03%   |
| OPNsense 24.1.9   | 11       | 1.86%   |
| OPNsense 23.7.10  | 11       | 1.86%   |
| OPNsense 23.1.11  | 11       | 1.86%   |
| OPNsense 24.1.10  | 10       | 1.69%   |
| OPNsense 25.1.9   | 9        | 1.52%   |
| OPNsense 24.7.3   | 9        | 1.52%   |
| OPNsense 25.7.7   | 8        | 1.35%   |
| OPNsense 25.1.7   | 8        | 1.35%   |
| OPNsense 24.1.8   | 8        | 1.35%   |
| OPNsense 24.1.4   | 8        | 1.35%   |
| OPNsense 23.7.7   | 8        | 1.35%   |
| OPNsense 22.7.10  | 8        | 1.35%   |
| OPNsense 22.1     | 8        | 1.35%   |
| helloSystem 0.8.1 | 8        | 1.35%   |
| OPNsense 25.7.9   | 7        | 1.18%   |
| OPNsense 25.7.6   | 7        | 1.18%   |
| OPNsense 25.1.4   | 7        | 1.18%   |
| OPNsense 25.1.10  | 7        | 1.18%   |
| OPNsense 22.7.6   | 7        | 1.18%   |
| OPNsense 25.7.2   | 6        | 1.02%   |
| OPNsense 25.7.1   | 6        | 1.02%   |
| OPNsense 25.1.12  | 6        | 1.02%   |
| OPNsense 25.1     | 6        | 1.02%   |
| OPNsense 24.7.8   | 6        | 1.02%   |
| OPNsense 24.7.11  | 6        | 1.02%   |
| OPNsense 24.7.10  | 6        | 1.02%   |
| OPNsense 24.1.2   | 6        | 1.02%   |
| OPNsense 23.1.8   | 6        | 1.02%   |
| OPNsense 23.1.5   | 6        | 1.02%   |
| OPNsense 23.1.10  | 6        | 1.02%   |
| OPNsense 25.7     | 5        | 0.85%   |
| OPNsense 24.7.6   | 5        | 0.85%   |
| OPNsense 24.7.5   | 5        | 0.85%   |
| OPNsense 24.7.1   | 5        | 0.85%   |
| OPNsense 24.1.5   | 5        | 0.85%   |
| OPNsense 22.7.9   | 5        | 0.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 326      | 79.51%  |
| FreeBSD     | 40       | 9.76%   |
| helloSystem | 21       | 5.12%   |
| OpenBSD     | 8        | 1.95%   |
| TrueNAS     | 5        | 1.22%   |
| GhostBSD    | 3        | 0.73%   |
| XigmaNAS    | 2        | 0.49%   |
| NetBSD      | 2        | 0.49%   |
| FreeNAS     | 2        | 0.49%   |
| NomadBSD    | 1        | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 407      | 99.51%  |
| i386  | 1        | 0.24%   |
| arm64 | 1        | 0.24%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 350      | 84.95%  |
| helloDesktop | 28       | 6.8%    |
| KDE5         | 12       | 2.91%   |
| XFCE         | 9        | 2.18%   |
| TWM          | 4        | 0.97%   |
| GNOME        | 3        | 0.73%   |
| MATE         | 2        | 0.49%   |
| xinitrc      | 1        | 0.24%   |
| Openbox      | 1        | 0.24%   |
| Lumina       | 1        | 0.24%   |
| i3           | 1        | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 359      | 87.35%  |
| X11     | 51       | 12.41%  |
| Wayland | 1        | 0.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 363      | 88.54%  |
| SLiM    | 23       | 5.61%   |
| SDDM    | 12       | 2.93%   |
| LightDM | 8        | 1.95%   |
| XDM     | 3        | 0.73%   |
| GDM     | 1        | 0.24%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 338      | 80.86%  |
| C       | 38       | 9.09%   |
| en_US   | 26       | 6.22%   |
| en_AU   | 11       | 2.63%   |
| fr_FR   | 2        | 0.48%   |
| ru_RU   | 1        | 0.24%   |
| fr      | 1        | 0.24%   |
| en      | 1        | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 364      | 89%     |
| BIOS | 45       | 11%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Zfs    | 214      | 50.59%  |
| Ufs    | 191      | 45.15%  |
| Cd9660 | 10       | 2.36%   |
| Ffs    | 8        | 1.89%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 392      | 95.84%  |
| MBR     | 14       | 3.42%   |
| Unknown | 2        | 0.49%   |
| BSD     | 1        | 0.24%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Unknown                              | 95       | 23.23%  |
| Dell                                 | 51       | 12.47%  |
| Hewlett-Packard                      | 34       | 8.31%   |
| Protectli                            | 30       | 7.33%   |
| Gigabyte Technology                  | 29       | 7.09%   |
| ASUSTek Computer                     | 28       | 6.85%   |
| Lenovo                               | 22       | 5.38%   |
| Intel                                | 18       | 4.4%    |
| Techvision                           | 14       | 3.42%   |
| ASRock                               | 13       | 3.18%   |
| MSI                                  | 10       | 2.44%   |
| Acer                                 | 6        | 1.47%   |
| PC Engines                           | 5        | 1.22%   |
| MW                                   | 4        | 0.98%   |
| AZW                                  | 4        | 0.98%   |
| Shuttle                              | 3        | 0.73%   |
| Shenzhen Meigao Electronic Equipment | 3        | 0.73%   |
| Inventec                             | 3        | 0.73%   |
| CWWK                                 | 3        | 0.73%   |
| Citrix                               | 2        | 0.49%   |
| CheckPoint                           | 2        | 0.49%   |
| AMD                                  | 2        | 0.49%   |
| YANYU                                | 1        | 0.24%   |
| Yanling                              | 1        | 0.24%   |
| Winston Marriot                      | 1        | 0.24%   |
| WeiBu                                | 1        | 0.24%   |
| Unknown                              | 1        | 0.24%   |
| TYAN Computer                        | 1        | 0.24%   |
| Trigkey                              | 1        | 0.24%   |
| TianBei                              | 1        | 0.24%   |
| ShenZhen MinWin Technology           | 1        | 0.24%   |
| SeeedStudio                          | 1        | 0.24%   |
| Radxa                                | 1        | 0.24%   |
| OEM                                  | 1        | 0.24%   |
| NP93B                                | 1        | 0.24%   |
| LinuxContainers                      | 1        | 0.24%   |
| IceWhale Technology                  | 1        | 0.24%   |
| IBM                                  | 1        | 0.24%   |
| HPE                                  | 1        | 0.24%   |
| Hardkernel                           | 1        | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Unknown                                           | 96       | 23.47%  |
| Techvision TVI7309X                               | 14       | 3.42%   |
| Protectli FW4B                                    | 13       | 3.18%   |
| Dell OptiPlex 9020                                | 12       | 2.93%   |
| Dell OptiPlex 7050                                | 7        | 1.71%   |
| Protectli VP2410                                  | 6        | 1.47%   |
| Dell OptiPlex 7040                                | 5        | 1.22%   |
| Protectli FW2B                                    | 4        | 0.98%   |
| MW GMLK-2_5G4L                                    | 4        | 0.98%   |
| Intel MAHOBAY                                     | 4        | 0.98%   |
| HP ProLiant MicroServer                           | 4        | 0.98%   |
| Shenzhen Meigao Electronic Equipment Venus series | 3        | 0.73%   |
| PC Engines APU2                                   | 3        | 0.73%   |
| MSI PRO ADL-U Cubi 5 (MS-B0A8)                    | 3        | 0.73%   |
| HP ProDesk 400 G4 SFF                             | 3        | 0.73%   |
| HP EliteDesk 800 G2 DM 35W                        | 3        | 0.73%   |
| ASUS All Series                                   | 3        | 0.73%   |
| Protectli FW4C                                    | 2        | 0.49%   |
| MSI MS-7C94                                       | 2        | 0.49%   |
| Lenovo ThinkCentre M93p 10AAS2A100                | 2        | 0.49%   |
| Lenovo ThinkCentre M700 10HYS0Q400                | 2        | 0.49%   |
| Inventec D CLASS                                  | 2        | 0.49%   |
| Intel QHSW02                                      | 2        | 0.49%   |
| Intel Q3XXG4-P V1.0                               | 2        | 0.49%   |
| HP ProLiant MicroServer Gen8                      | 2        | 0.49%   |
| HP ProDesk 600 G4 SFF                             | 2        | 0.49%   |
| HP EliteDesk 800 G6 Small Form Factor PC          | 2        | 0.49%   |
| HP EliteDesk 800 G3 SFF                           | 2        | 0.49%   |
| Gigabyte Z790 EAGLE AX                            | 2        | 0.49%   |
| Gigabyte J1900N-D3V                               | 2        | 0.49%   |
| Dell OptiPlex 990                                 | 2        | 0.49%   |
| Dell OptiPlex 7080                                | 2        | 0.49%   |
| Dell OptiPlex 7060                                | 2        | 0.49%   |
| Dell OptiPlex 3040                                | 2        | 0.49%   |
| Dell OptiPlex 3010                                | 2        | 0.49%   |
| Citrix CB-1100                                    | 2        | 0.49%   |
| CheckPoint T-120-00                               | 2        | 0.49%   |
| AZW GK55                                          | 2        | 0.49%   |
| ASUS STRIX Z270I GAMING                           | 2        | 0.49%   |
| YANYU H67SL                                       | 1        | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Unknown                                    | 96       | 23.47%  |
| Dell OptiPlex                              | 43       | 10.51%  |
| Lenovo ThinkCentre                         | 18       | 4.4%    |
| Techvision TVI7309X                        | 14       | 3.42%   |
| Protectli FW4B                             | 13       | 3.18%   |
| HP EliteDesk                               | 11       | 2.69%   |
| HP ProLiant                                | 9        | 2.2%    |
| HP prodesk                                 | 8        | 1.96%   |
| ASUS PRIME                                 | 8        | 1.96%   |
| Protectli VP2410                           | 6        | 1.47%   |
| ASUS ROG                                   | 6        | 1.47%   |
| Acer Veriton                               | 5        | 1.22%   |
| Protectli FW2B                             | 4        | 0.98%   |
| MW GMLK-2                                  | 4        | 0.98%   |
| MSI Pro                                    | 4        | 0.98%   |
| Intel MAHOBAY                              | 4        | 0.98%   |
| Shenzhen Meigao Electronic Equipment Venus | 3        | 0.73%   |
| PC Engines APU2                            | 3        | 0.73%   |
| HP Compaq                                  | 3        | 0.73%   |
| Gigabyte Z790                              | 3        | 0.73%   |
| Dell Precision                             | 3        | 0.73%   |
| Dell Inspiron                              | 3        | 0.73%   |
| ASUS All                                   | 3        | 0.73%   |
| Protectli FW4C                             | 2        | 0.49%   |
| MSI MS-7C94                                | 2        | 0.49%   |
| Inventec D                                 | 2        | 0.49%   |
| Intel QHSW02                               | 2        | 0.49%   |
| Intel Q3XXG4-P                             | 2        | 0.49%   |
| Gigabyte J1900N-D3V                        | 2        | 0.49%   |
| Citrix CB-1100                             | 2        | 0.49%   |
| CheckPoint T-120-00                        | 2        | 0.49%   |
| AZW GK55                                   | 2        | 0.49%   |
| ASUS STRIX                                 | 2        | 0.49%   |
| ASRock X370                                | 2        | 0.49%   |
| YANYU H67SL                                | 1        | 0.24%   |
| Yanling YL-KBR6L                           | 1        | 0.24%   |
| Winston Marriot PICO                       | 1        | 0.24%   |
| WeiBu ADL-N                                | 1        | 0.24%   |
| TYAN S5510HE                               | 1        | 0.24%   |
| Trigkey Green                              | 1        | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2023    | 69       | 16.87%  |
| 2022    | 44       | 10.76%  |
| 2018    | 38       | 9.29%   |
| 2014    | 29       | 7.09%   |
| 2021    | 28       | 6.85%   |
| 2016    | 27       | 6.6%    |
| 2024    | 22       | 5.38%   |
| 2013    | 21       | 5.13%   |
| 2019    | 20       | 4.89%   |
| 2020    | 19       | 4.65%   |
| 2012    | 18       | 4.4%    |
| 2015    | 16       | 3.91%   |
| 2017    | 14       | 3.42%   |
| 2011    | 13       | 3.18%   |
| 2025    | 8        | 1.96%   |
| 2010    | 6        | 1.47%   |
| 2009    | 6        | 1.47%   |
| Unknown | 5        | 1.22%   |
| 2008    | 4        | 0.98%   |
| 2007    | 1        | 0.24%   |
| 2006    | 1        | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 409      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 395      | 96.58%  |
| Yes  | 14       | 3.42%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 151      | 35.78%  |
| 8.01-16.0   | 151      | 35.78%  |
| 32.01-64.0  | 46       | 10.9%   |
| 4.01-8.0    | 45       | 10.66%  |
| 64.01-256.0 | 15       | 3.55%   |
| 2.01-3.0    | 7        | 1.66%   |
| 24.01-32.0  | 5        | 1.18%   |
| 0.51-1.0    | 2        | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.51-1.0   | 176      | 41.61%  |
| 0.01-0.5   | 163      | 38.53%  |
| 1.01-2.0   | 55       | 13%     |
| 2.01-3.0   | 11       | 2.6%    |
| 4.01-8.0   | 7        | 1.65%   |
| 3.01-4.0   | 4        | 0.95%   |
| 16.01-24.0 | 2        | 0.47%   |
| 8.01-16.0  | 2        | 0.47%   |
| Unknown    | 2        | 0.47%   |
| 32.01-64.0 | 1        | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 256      | 59.26%  |
| 0      | 101      | 23.38%  |
| 2      | 35       | 8.1%    |
| 3      | 19       | 4.4%    |
| 4      | 8        | 1.85%   |
| 5      | 4        | 0.93%   |
| 8      | 3        | 0.69%   |
| 7      | 3        | 0.69%   |
| 6      | 2        | 0.46%   |
| 10     | 1        | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 351      | 85.4%   |
| Yes       | 60       | 14.6%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 406      | 99.27%  |
| No        | 3        | 0.73%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 330      | 80.49%  |
| Yes       | 80       | 19.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 349      | 84.5%   |
| Yes       | 64       | 15.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Australia | 409      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sydney         | 125      | 27.9%   |
| Melbourne      | 101      | 22.54%  |
| Brisbane       | 55       | 12.28%  |
| Perth          | 42       | 9.38%   |
| Adelaide       | 26       | 5.8%    |
| Nyngan         | 12       | 2.68%   |
| Canberra       | 12       | 2.68%   |
| Launceston     | 4        | 0.89%   |
| Kooyong        | 4        | 0.89%   |
| Geelong        | 4        | 0.89%   |
| Morwell        | 3        | 0.67%   |
| Hobart         | 3        | 0.67%   |
| Townsville     | 2        | 0.45%   |
| Marrickville   | 2        | 0.45%   |
| Macquarie Park | 2        | 0.45%   |
| Longreach      | 2        | 0.45%   |
| Ipswich        | 2        | 0.45%   |
| Bundaberg      | 2        | 0.45%   |
| Unknown        | 2        | 0.45%   |
| Yallourn       | 1        | 0.22%   |
| Wollongong     | 1        | 0.22%   |
| Wheelers Hill  | 1        | 0.22%   |
| Warrnambool    | 1        | 0.22%   |
| Warragul       | 1        | 0.22%   |
| Wallan         | 1        | 0.22%   |
| Two Wells      | 1        | 0.22%   |
| Southport      | 1        | 0.22%   |
| Shell Cove     | 1        | 0.22%   |
| Ryde           | 1        | 0.22%   |
| Roxby Downs    | 1        | 0.22%   |
| Rosanna        | 1        | 0.22%   |
| Ringwood       | 1        | 0.22%   |
| Port Fairy     | 1        | 0.22%   |
| North Shore    | 1        | 0.22%   |
| Noble Park     | 1        | 0.22%   |
| Nickol         | 1        | 0.22%   |
| Newport        | 1        | 0.22%   |
| Mount Waverley | 1        | 0.22%   |
| Mooroolbark    | 1        | 0.22%   |
| Malvern        | 1        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 72       | 132    | 17.35%  |
| Seagate             | 42       | 66     | 10.12%  |
| WDC                 | 40       | 92     | 9.64%   |
| Crucial             | 37       | 53     | 8.92%   |
| SanDisk             | 26       | 34     | 6.27%   |
| Kingston            | 25       | 35     | 6.02%   |
| Toshiba             | 19       | 30     | 4.58%   |
| Intel               | 17       | 27     | 4.1%    |
| China               | 14       | 16     | 3.37%   |
| Hoodisk             | 13       | 25     | 3.13%   |
| SPCC                | 10       | 18     | 2.41%   |
| Micron Technology   | 9        | 10     | 2.17%   |
| OCZ                 | 6        | 7      | 1.45%   |
| SK hynix            | 5        | 11     | 1.2%    |
| Silicon Motion      | 5        | 6      | 1.2%    |
| ShiJi               | 5        | 8      | 1.2%    |
| Protectli           | 5        | 5      | 1.2%    |
| Gigabyte Technology | 5        | 6      | 1.2%    |
| Transcend           | 4        | 8      | 0.96%   |
| Patriot             | 4        | 6      | 0.96%   |
| Phison              | 3        | 4      | 0.72%   |
| Hewlett-Packard     | 3        | 6      | 0.72%   |
| FORESEE             | 3        | 6      | 0.72%   |
| A-DATA Technology   | 3        | 8      | 0.72%   |
| NVMe                | 2        | 2      | 0.48%   |
| LITEONIT            | 2        | 2      | 0.48%   |
| KIOXIA              | 2        | 2      | 0.48%   |
| KingDian            | 2        | 2      | 0.48%   |
| Hitachi             | 2        | 3      | 0.48%   |
| HGST                | 2        | 3      | 0.48%   |
| Fanxiang            | 2        | 2      | 0.48%   |
| Dogfish             | 2        | 3      | 0.48%   |
| Corsair             | 2        | 3      | 0.48%   |
| BIWIN               | 2        | 2      | 0.48%   |
| YMTC                | 1        | 2      | 0.24%   |
| XUNZHE              | 1        | 2      | 0.24%   |
| Wicgtyp             | 1        | 1      | 0.24%   |
| Western             | 1        | 3      | 0.24%   |
| Vaseky              | 1        | 4      | 0.24%   |
| Synology            | 1        | 3      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Hoodisk SSD 128GB                | 8        | 1.77%   |
| Samsung SSD 850 EVO 500GB        | 7        | 1.55%   |
| Crucial CT250MX500SSD1 250GB     | 6        | 1.33%   |
| Samsung SSD 870 EVO 250GB        | 5        | 1.11%   |
| Kingston SA400S37240G 240GB      | 5        | 1.11%   |
| Crucial CT250P2SSD8 250GB        | 5        | 1.11%   |
| Samsung SSD 970 EVO Plus 500GB   | 4        | 0.88%   |
| Samsung SSD 870 EVO 500GB        | 4        | 0.88%   |
| Samsung SSD 840 EVO 120GB        | 4        | 0.88%   |
| Kingston SA400S37120G 120GB      | 4        | 0.88%   |
| WDC WDS250G2B0A-00SM50 250GB     | 3        | 0.66%   |
| WDC WD30EFRX-68EUZN0 3TB         | 3        | 0.66%   |
| Seagate ST500LM021-1KJ152 500GB  | 3        | 0.66%   |
| Seagate ST1000DM010-2EP102 1TB   | 3        | 0.66%   |
| Samsung SSD 980 500GB            | 3        | 0.66%   |
| Samsung SSD 970 EVO Plus 250GB   | 3        | 0.66%   |
| Samsung SSD 860 EVO 500GB        | 3        | 0.66%   |
| Samsung MZ7PD256HCGM-000H7 256GB | 3        | 0.66%   |
| Kingston SA400S37480G 480GB      | 3        | 0.66%   |
| Crucial CT500P3SSD8 500GB        | 3        | 0.66%   |
| Crucial CT500MX500SSD1 500GB     | 3        | 0.66%   |
| Crucial CT480BX500SSD1 480GB     | 3        | 0.66%   |
| Crucial CT240BX500SSD1 240GB     | 3        | 0.66%   |
| Crucial CT1000P3SSD8 1TB         | 3        | 0.66%   |
| China YSE128GTLCW-SBC-2 128GB    | 3        | 0.66%   |
| China SATA SSD 16GB              | 3        | 0.66%   |
| WDC WDS240G2G0A-00JH30 240GB     | 2        | 0.44%   |
| WDC WD40EFRX-68WT0N0 4TB         | 2        | 0.44%   |
| WDC WD40EFRX-68N32N0 4TB         | 2        | 0.44%   |
| WDC WD2503ABYX-01WERA1 256GB     | 2        | 0.44%   |
| WDC WD20EZRX-00D8PB0 2TB         | 2        | 0.44%   |
| WDC WD20EZAZ-00GGJB0 2TB         | 2        | 0.44%   |
| WDC WD20EARX-00PASB0 2TB         | 2        | 0.44%   |
| Toshiba MQ04UBF100 1TB           | 2        | 0.44%   |
| Toshiba MK6475GSX 640GB          | 2        | 0.44%   |
| Toshiba KXG50ZNV256G 256GB       | 2        | 0.44%   |
| Toshiba DT01ACA100 1TB           | 2        | 0.44%   |
| SPCC Solid State Disk 256GB      | 2        | 0.44%   |
| SPCC M.2 SSD 256GB               | 2        | 0.44%   |
| SPCC M.2 PCIe SSD 256GB          | 2        | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 40       | 63     | 39.22%  |
| WDC                 | 33       | 79     | 32.35%  |
| Toshiba             | 13       | 22     | 12.75%  |
| Samsung Electronics | 4        | 6      | 3.92%   |
| Hewlett-Packard     | 3        | 6      | 2.94%   |
| Hitachi             | 2        | 3      | 1.96%   |
| HGST                | 2        | 3      | 1.96%   |
| Western             | 1        | 3      | 0.98%   |
| Synology            | 1        | 3      | 0.98%   |
| NVMe                | 1        | 1      | 0.98%   |
| Maxtor              | 1        | 1      | 0.98%   |
| China               | 1        | 1      | 0.98%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 51       | 92     | 21.16%  |
| SanDisk             | 26       | 34     | 10.79%  |
| Crucial             | 24       | 36     | 9.96%   |
| Kingston            | 22       | 31     | 9.13%   |
| Intel               | 15       | 25     | 6.22%   |
| Hoodisk             | 13       | 25     | 5.39%   |
| China               | 13       | 15     | 5.39%   |
| SPCC                | 7        | 11     | 2.9%    |
| Micron Technology   | 7        | 8      | 2.9%    |
| OCZ                 | 6        | 7      | 2.49%   |
| WDC                 | 5        | 8      | 2.07%   |
| Protectli           | 5        | 5      | 2.07%   |
| Transcend           | 4        | 8      | 1.66%   |
| Toshiba             | 3        | 5      | 1.24%   |
| SK hynix            | 3        | 7      | 1.24%   |
| ShiJi               | 3        | 5      | 1.24%   |
| Seagate             | 2        | 2      | 0.83%   |
| Patriot             | 2        | 3      | 0.83%   |
| LITEONIT            | 2        | 2      | 0.83%   |
| KingDian            | 2        | 2      | 0.83%   |
| Gigabyte Technology | 2        | 2      | 0.83%   |
| FORESEE             | 2        | 5      | 0.83%   |
| Dogfish             | 2        | 3      | 0.83%   |
| Corsair             | 2        | 3      | 0.83%   |
| XUNZHE              | 1        | 2      | 0.41%   |
| Wicgtyp             | 1        | 1      | 0.41%   |
| Vaseky              | 1        | 4      | 0.41%   |
| SATADOM             | 1        | 1      | 0.41%   |
| Qunion              | 1        | 4      | 0.41%   |
| Plextor             | 1        | 2      | 0.41%   |
| Phison              | 1        | 1      | 0.41%   |
| OSCOO               | 1        | 2      | 0.41%   |
| NVMe                | 1        | 1      | 0.41%   |
| Netac               | 1        | 1      | 0.41%   |
| KingSpec            | 1        | 1      | 0.41%   |
| HUGWORLD            | 1        | 1      | 0.41%   |
| GOFATOO             | 1        | 1      | 0.41%   |
| Fordisk             | 1        | 1      | 0.41%   |
| BIWIN               | 1        | 1      | 0.41%   |
| ASint Technology    | 1        | 2      | 0.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 214      | 372    | 58.79%  |
| HDD  | 77       | 191    | 21.15%  |
| NVMe | 73       | 115    | 20.05%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 269      | 563    | 78.65%  |
| NVMe | 73       | 115    | 21.35%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 230      | 401    | 74.43%  |
| 0.51-1.0   | 35       | 54     | 11.33%  |
| 1.01-2.0   | 18       | 40     | 5.83%   |
| 3.01-4.0   | 12       | 27     | 3.88%   |
| 2.01-3.0   | 5        | 15     | 1.62%   |
| 4.01-10.0  | 5        | 15     | 1.62%   |
| 10.01-20.0 | 3        | 7      | 0.97%   |
| 20.01-50.0 | 1        | 4      | 0.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 198      | 46.37%  |
| 251-500        | 88       | 20.61%  |
| 501-1000       | 38       | 8.9%    |
| 51-100         | 35       | 8.2%    |
| 1-20           | 32       | 7.49%   |
| 21-50          | 23       | 5.39%   |
| 1001-2000      | 9        | 2.11%   |
| More than 3000 | 2        | 0.47%   |
| 2001-3000      | 2        | 0.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 378      | 87.91%  |
| 21-50          | 36       | 8.37%   |
| 101-250        | 6        | 1.4%    |
| 51-100         | 6        | 1.4%    |
| 1001-2000      | 3        | 0.7%    |
| More than 3000 | 1        | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Desktops | Drives | Percent |
|-------------------------------------------|----------|--------|---------|
| Seagate ST500LM021-1KJ152 500GB           | 2        | 2      | 5.56%   |
| WDC WDS240G2G0A-00JH30 240GB              | 1        | 1      | 2.78%   |
| WDC WD40EZRZ-00WN9B0 4TB                  | 1        | 1      | 2.78%   |
| WDC WD30EFRX-68EUZN0 3TB                  | 1        | 1      | 2.78%   |
| WDC WD20EZRX-00D8PB0 2TB                  | 1        | 2      | 2.78%   |
| WDC WD20EARX-008FB0 2TB                   | 1        | 4      | 2.78%   |
| WDC WD20EARS-00MVWB0 2TB                  | 1        | 1      | 2.78%   |
| Toshiba THNSNF128GMCS 128GB               | 1        | 1      | 2.78%   |
| Toshiba MK5059GSX 500GB                   | 1        | 1      | 2.78%   |
| Toshiba KSG60ZSE256G SATA 256GB           | 1        | 1      | 2.78%   |
| Seagate ST9160827AS 160GB                 | 1        | 2      | 2.78%   |
| Seagate ST9160314AS 160GB                 | 1        | 1      | 2.78%   |
| Seagate ST500LT012-1DG142 500GB           | 1        | 1      | 2.78%   |
| Seagate ST3250310AS 250GB                 | 1        | 1      | 2.78%   |
| Seagate ST240FN0021 240GB                 | 1        | 1      | 2.78%   |
| Seagate ST2000LM015-2E8174 2TB            | 1        | 1      | 2.78%   |
| Seagate ST2000DL003-9VT166 2TB            | 1        | 1      | 2.78%   |
| Seagate ST1000DM003-1CH162 1TB            | 1        | 1      | 2.78%   |
| SanDisk SSD PLUS 240 GB                   | 1        | 1      | 2.78%   |
| SanDisk SDSSDA240G 240GB                  | 1        | 1      | 2.78%   |
| SanDisk SDSSDA120G 120GB                  | 1        | 1      | 2.78%   |
| Samsung Electronics SSD 870 EVO 500GB     | 1        | 1      | 2.78%   |
| Samsung Electronics SSD 870 EVO 1TB       | 1        | 1      | 2.78%   |
| Samsung Electronics SP0812C 80GB          | 1        | 1      | 2.78%   |
| Samsung Electronics HM500LI 500GB         | 1        | 2      | 2.78%   |
| OCZ VERTEX3 120GB                         | 1        | 1      | 2.78%   |
| OCZ OCTANE 128GB                          | 1        | 1      | 2.78%   |
| Micron Technology C400-MTFDDAT064MAM 64GB | 1        | 1      | 2.78%   |
| Intel SSDSC2BB480G7 480GB                 | 1        | 1      | 2.78%   |
| Intel SSDSA2BW120G3H 120GB                | 1        | 1      | 2.78%   |
| Hitachi HDS721010KLA330 1TB               | 1        | 1      | 2.78%   |
| HGST HTS721010A9E630 1TB                  | 1        | 2      | 2.78%   |
| Hewlett-Packard VB0250EAVER 250GB         | 1        | 1      | 2.78%   |
| Crucial CT500MX500SSD1 500GB              | 1        | 1      | 2.78%   |
| BIWIN SSD 8GB                             | 1        | 1      | 2.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 11     | 28.57%  |
| WDC                 | 5        | 10     | 14.29%  |
| Samsung Electronics | 4        | 5      | 11.43%  |
| Toshiba             | 3        | 3      | 8.57%   |
| SanDisk             | 3        | 3      | 8.57%   |
| OCZ                 | 2        | 2      | 5.71%   |
| Intel               | 2        | 2      | 5.71%   |
| Micron Technology   | 1        | 1      | 2.86%   |
| Hitachi             | 1        | 1      | 2.86%   |
| HGST                | 1        | 2      | 2.86%   |
| Hewlett-Packard     | 1        | 1      | 2.86%   |
| Crucial             | 1        | 1      | 2.86%   |
| BIWIN               | 1        | 1      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 10     | 47.37%  |
| WDC                 | 4        | 9      | 21.05%  |
| Samsung Electronics | 2        | 3      | 10.53%  |
| Toshiba             | 1        | 1      | 5.26%   |
| Hitachi             | 1        | 1      | 5.26%   |
| HGST                | 1        | 2      | 5.26%   |
| Hewlett-Packard     | 1        | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 19       | 27     | 54.29%  |
| SSD  | 16       | 16     | 45.71%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                        | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB | 1        | 1      | 50%     |
| Patriot M.2 P310 240GB       | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Patriot | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 297      | 628    | 87.87%  |
| Malfunc  | 35       | 43     | 10.36%  |
| Detected | 4        | 5      | 1.18%   |
| Failed   | 2        | 2      | 0.59%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel                                   | 347      | 60.56%  |
| AMD                                     | 44       | 7.68%   |
| Samsung Electronics                     | 38       | 6.63%   |
| Silicon Motion                          | 21       | 3.66%   |
| Micron/Crucial Technology               | 19       | 3.32%   |
| Phison Electronics                      | 15       | 2.62%   |
| Micron Technology                       | 10       | 1.75%   |
| Sandisk                                 | 9        | 1.57%   |
| Kingston Technology Company             | 9        | 1.57%   |
| MAXIO Technology (Hangzhou)             | 8        | 1.4%    |
| Toshiba                                 | 6        | 1.05%   |
| Realtek Semiconductor                   | 5        | 0.87%   |
| Hosin Global Electronics                | 5        | 0.87%   |
| Broadcom / LSI                          | 5        | 0.87%   |
| SK hynix                                | 4        | 0.7%    |
| Yangtze Memory Technologies             | 3        | 0.52%   |
| Hewlett-Packard                         | 3        | 0.52%   |
| ASMedia Technology                      | 3        | 0.52%   |
| ADATA Technology                        | 3        | 0.52%   |
| Shenzhen Unionmemory Information System | 2        | 0.35%   |
| Shenzhen Longsys Electronics            | 2        | 0.35%   |
| Netac Technology                        | 2        | 0.35%   |
| Chelsio Communications                  | 2        | 0.35%   |
| Silicon Image                           | 1        | 0.17%   |
| Seagate Technology                      | 1        | 0.17%   |
| Red Hat                                 | 1        | 0.17%   |
| QLogic                                  | 1        | 0.17%   |
| Nvidia                                  | 1        | 0.17%   |
| Marvell Technology Group                | 1        | 0.17%   |
| JMicron Technology                      | 1        | 0.17%   |
| Adaptec                                 | 1        | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel Alder Lake-N SATA AHCI Controller                                                 | 42       | 6.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 30       | 4.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 24       | 3.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 24       | 3.8%    |
| Intel Jasper Lake SATA AHCI Controller                                                  | 23       | 3.65%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 23       | 3.65%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 22       | 3.49%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 21       | 3.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 21       | 3.33%   |
| Intel SATA Controller [RAID mode]                                                       | 17       | 2.69%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 16       | 2.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 16       | 2.54%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 14       | 2.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 13       | 2.06%   |
| Intel Alder Lake-P SATA AHCI Controller                                                 | 13       | 2.06%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 10       | 1.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 10       | 1.58%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 9        | 1.43%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 9        | 1.43%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9        | 1.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 8        | 1.27%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 8        | 1.27%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 8        | 1.27%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 7        | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7        | 1.11%   |
| Micron 2550 NVMe SSD (DRAM-less)                                                        | 6        | 0.95%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6        | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 0.95%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                       | 5        | 0.79%   |
| Intel Atom Processor C3000 Series SATA Controller 1                                     | 5        | 0.79%   |
| Hosin Global Patriot P300 NVMe SSD (DRAM-less)                                          | 5        | 0.79%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 5        | 0.79%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 0.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 0.63%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 4        | 0.63%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 4        | 0.63%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4        | 0.63%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 4        | 0.63%   |
| AMD X370 Series Chipset SATA Controller                                                 | 4        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 353      | 61.61%  |
| NVMe | 153      | 26.7%   |
| IDE  | 32       | 5.58%   |
| RAID | 25       | 4.36%   |
| SCSI | 7        | 1.22%   |
| SAS  | 3        | 0.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 359      | 87.78%  |
| AMD    | 48       | 11.74%  |
| QEMU   | 1        | 0.24%   |
| ARM    | 1        | 0.24%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel N100                             | 36       | 8.65%   |
| Intel Celeron J4125 CPU @ 2.00GHz      | 20       | 4.81%   |
| Intel Celeron N5105 @ 2.00GHz          | 19       | 4.57%   |
| Intel Celeron CPU J3160 @ 1.60GHz      | 15       | 3.61%   |
| Intel N150                             | 10       | 2.4%    |
| Intel Core i5-6500T CPU @ 2.50GHz      | 9        | 2.16%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 8        | 1.92%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 6        | 1.44%   |
| Intel Core i7-7700 CPU @ 3.60GHz       | 5        | 1.2%    |
| Intel Core i5-4570T CPU @ 2.90GHz      | 5        | 1.2%    |
| Intel Core i5-3470 CPU @ 3.20GHz       | 5        | 1.2%    |
| Intel Celeron CPU J1900 @ 1.99GHz      | 5        | 1.2%    |
| Intel Pentium Silver N6005 @ 2.00GHz   | 4        | 0.96%   |
| Intel Core i7-10700 CPU @ 2.90GHz      | 4        | 0.96%   |
| Intel Core i5-6400 CPU @ 2.70GHz       | 4        | 0.96%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 4        | 0.96%   |
| Intel Celeron CPU J3060 @ 1.60GHz      | 4        | 0.96%   |
| Intel 12th Gen Core i5-12400           | 4        | 0.96%   |
| Intel 12th Gen Core i3-1215U           | 4        | 0.96%   |
| AMD GX-412TC SOC                       | 4        | 0.96%   |
| Intel Pentium CPU G4560 @ 3.50GHz      | 3        | 0.72%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 3        | 0.72%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 3        | 0.72%   |
| Intel Core i7-4770 CPU @ 3.40GHz       | 3        | 0.72%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 3        | 0.72%   |
| Intel Core i5-6500 CPU @ 3.20GHz       | 3        | 0.72%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 3        | 0.72%   |
| Intel Core i3-N305                     | 3        | 0.72%   |
| Intel Core i3-6100 CPU @ 3.70GHz       | 3        | 0.72%   |
| Intel Core i3-3220 CPU @ 3.30GHz       | 3        | 0.72%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 3        | 0.72%   |
| Intel Xeon CPU E5504 @ 2.00GHz         | 2        | 0.48%   |
| Intel Pentium Gold 8505                | 2        | 0.48%   |
| Intel Pentium CPU J3710 @ 1.60GHz      | 2        | 0.48%   |
| Intel Core i7-9700K CPU @ 3.60GHz      | 2        | 0.48%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 2        | 0.48%   |
| Intel Core i5-8500 CPU @ 3.00GHz       | 2        | 0.48%   |
| Intel Core i5-7400 CPU @ 3.00GHz       | 2        | 0.48%   |
| Intel Core i5-6400T CPU @ 2.20GHz      | 2        | 0.48%   |
| Intel Core i5-5300U CPU @ 2.30GHz      | 2        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 89       | 21.45%  |
| Intel Celeron           | 83       | 20%     |
| Other                   | 74       | 17.83%  |
| Intel Core i7           | 38       | 9.16%   |
| Intel Core i3           | 28       | 6.75%   |
| Intel Xeon              | 19       | 4.58%   |
| AMD Ryzen 5             | 13       | 3.13%   |
| Intel Atom              | 10       | 2.41%   |
| Intel Pentium           | 9        | 2.17%   |
| AMD GX                  | 6        | 1.45%   |
| Intel Pentium Silver    | 5        | 1.2%    |
| AMD Ryzen 3             | 5        | 1.2%    |
| Intel Core 2 Quad       | 4        | 0.96%   |
| AMD Turion II Neo       | 4        | 0.96%   |
| AMD Ryzen 7             | 4        | 0.96%   |
| AMD G                   | 4        | 0.96%   |
| AMD FX                  | 4        | 0.96%   |
| Intel Pentium Gold      | 2        | 0.48%   |
| Intel Core 2 Duo        | 2        | 0.48%   |
| AMD Ryzen 9             | 2        | 0.48%   |
| AMD Athlon              | 2        | 0.48%   |
| Intel Pentium Dual-Core | 1        | 0.24%   |
| Intel Pentium 4         | 1        | 0.24%   |
| Intel Core i9           | 1        | 0.24%   |
| Intel Core              | 1        | 0.24%   |
| ARM Cortex              | 1        | 0.24%   |
| AMD E2                  | 1        | 0.24%   |
| AMD Athlon X2           | 1        | 0.24%   |
| AMD A4                  | 1        | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 244      | 58.8%   |
| 2       | 74       | 17.83%  |
| 8       | 35       | 8.43%   |
| 6       | 34       | 8.19%   |
| 16      | 6        | 1.45%   |
| 12      | 6        | 1.45%   |
| Unknown | 6        | 1.45%   |
| 10      | 3        | 0.72%   |
| 32      | 2        | 0.48%   |
| 24      | 2        | 0.48%   |
| 22      | 1        | 0.24%   |
| 18      | 1        | 0.24%   |
| 1       | 1        | 0.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 404      | 98.78%  |
| 2       | 3        | 0.73%   |
| Unknown | 2        | 0.49%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 292      | 70.19%  |
| 2       | 118      | 28.37%  |
| Unknown | 6        | 1.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Unknown       | 105      | 25.42%  |
| KabyLake      | 47       | 11.38%  |
| Haswell       | 41       | 9.93%   |
| Skylake       | 33       | 7.99%   |
| Silvermont    | 32       | 7.75%   |
| Goldmont plus | 24       | 5.81%   |
| IvyBridge     | 23       | 5.57%   |
| SandyBridge   | 12       | 2.91%   |
| CometLake     | 12       | 2.91%   |
| Zen 3         | 10       | 2.42%   |
| Goldmont      | 8        | 1.94%   |
| Broadwell     | 8        | 1.94%   |
| Zen+          | 5        | 1.21%   |
| Zen 2         | 5        | 1.21%   |
| Westmere      | 5        | 1.21%   |
| Puma          | 5        | 1.21%   |
| K10           | 5        | 1.21%   |
| Bobcat        | 5        | 1.21%   |
| Zen           | 4        | 0.97%   |
| Piledriver    | 4        | 0.97%   |
| Penryn        | 4        | 0.97%   |
| Nehalem       | 4        | 0.97%   |
| Jaguar        | 3        | 0.73%   |
| Core          | 3        | 0.73%   |
| TigerLake     | 2        | 0.48%   |
| Bonnell       | 2        | 0.48%   |
| NetBurst      | 1        | 0.24%   |
| K8 Hammer     | 1        | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 317      | 78.08%  |
| AMD                        | 45       | 11.08%  |
| Nvidia                     | 28       | 6.9%    |
| Matrox Electronics Systems | 8        | 1.97%   |
| ASPEED Technology          | 6        | 1.48%   |
| Tseng Labs                 | 1        | 0.25%   |
| Red Hat                    | 1        | 0.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Alder Lake-N [UHD Graphics]                                                        | 41       | 9.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 35       | 8.43%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 24       | 5.78%   |
| Intel JasperLake [UHD Graphics]                                                          | 24       | 5.78%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 24       | 5.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 22       | 5.3%    |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                                  | 17       | 4.1%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 16       | 3.86%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11       | 2.65%   |
| Intel Alder Lake-N [Intel Graphics]                                                      | 10       | 2.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10       | 2.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9        | 2.17%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                                  | 6        | 1.45%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 6        | 1.45%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5        | 1.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5        | 1.2%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 0.96%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4        | 0.96%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 4        | 0.96%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 4        | 0.96%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 4        | 0.96%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4        | 0.96%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 4        | 0.96%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4        | 0.96%   |
| Nvidia GT218 [GeForce 210]                                                               | 3        | 0.72%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 3        | 0.72%   |
| Matrox Electronics Systems MGA G200EH                                                    | 3        | 0.72%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 3        | 0.72%   |
| Intel Kaby Lake-S GT1 [HD Graphics 610]                                                  | 3        | 0.72%   |
| Intel Comet Lake UHD Graphics                                                            | 3        | 0.72%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 0.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 0.72%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 3        | 0.72%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 3        | 0.72%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 2        | 0.48%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 0.48%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2        | 0.48%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 2        | 0.48%   |
| Intel Skylake-S GT1 [HD Graphics 510]                                                    | 2        | 0.48%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 2        | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 301      | 73.06%  |
| 1 x AMD        | 37       | 8.98%   |
| 1 x Nvidia     | 23       | 5.58%   |
| Other          | 16       | 3.88%   |
| 1 x Matrox     | 8        | 1.94%   |
| Intel + AMD    | 7        | 1.7%    |
| 2 x Intel      | 6        | 1.46%   |
| 1 x ASPEED     | 6        | 1.46%   |
| Intel + Nvidia | 4        | 0.97%   |
| 2 x AMD        | 1        | 0.24%   |
| 1 x Tseng Labs | 1        | 0.24%   |
| 1 x Red Hat    | 1        | 0.24%   |
| AMD + Nvidia   | 1        | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 380      | 92.46%  |
| Unknown     | 17       | 4.14%   |
| Proprietary | 14       | 3.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 384      | 92.75%  |
| 1.01-2.0   | 9        | 2.17%   |
| 0.51-1.0   | 7        | 1.69%   |
| 7.01-8.0   | 6        | 1.45%   |
| 3.01-4.0   | 4        | 0.97%   |
| 8.01-16.0  | 2        | 0.48%   |
| 0.01-0.5   | 2        | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| ViewSonic               | 6        | 12.24%  |
| Acer                    | 6        | 12.24%  |
| Dell                    | 5        | 10.2%   |
| Samsung Electronics     | 4        | 8.16%   |
| Philips                 | 4        | 8.16%   |
| ASUSTek Computer        | 4        | 8.16%   |
| Hewlett-Packard         | 3        | 6.12%   |
| Goldstar                | 3        | 6.12%   |
| AOC                     | 3        | 6.12%   |
| Sony                    | 2        | 4.08%   |
| BenQ                    | 2        | 4.08%   |
| ___                     | 1        | 2.04%   |
| Toshiba                 | 1        | 2.04%   |
| Lenovo                  | 1        | 2.04%   |
| Konka                   | 1        | 2.04%   |
| Compal                  | 1        | 2.04%   |
| Chi Mei Optoelectronics | 1        | 2.04%   |
| AU Optronics            | 1        | 2.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| ViewSonic VA2026w VSC5020 1680x1050 430x270mm 20.0-inch                | 2        | 3.92%   |
| ASUSTek Computer ROG XG279Q AUS278D 2560x1440 600x340mm 27.2-inch      | 2        | 3.92%   |
| ___ MY TV LED TV ___0101 1920x1080                                     | 1        | 1.96%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 700x390mm 31.5-inch              | 1        | 1.96%   |
| ViewSonic VG910s VSCDA18 1280x1024 380x300mm 19.1-inch                 | 1        | 1.96%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 600x340mm 27.2-inch              | 1        | 1.96%   |
| ViewSonic VA1912w-3 VSC711C 1440x900 410x260mm 19.1-inch               | 1        | 1.96%   |
| Toshiba TV TSB010E 1920x1080 1040x590mm 47.1-inch                      | 1        | 1.96%   |
| Sony TV SNYB801 1360x768                                               | 1        | 1.96%   |
| Sony AVAMP SNY1F02 1280x720 800x450mm 36.1-inch                        | 1        | 1.96%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 1        | 1.96%   |
| Samsung Electronics SyncMaster SAM056A 1680x1050 470x300mm 22.0-inch   | 1        | 1.96%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch   | 1        | 1.96%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch      | 1        | 1.96%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch                | 1        | 1.96%   |
| Philips PHL 271S9 PHL0987 1920x1080 600x340mm 27.2-inch                | 1        | 1.96%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                | 1        | 1.96%   |
| Philips PHL 221V8 PHLC211 1920x1080 480x270mm 21.7-inch                | 1        | 1.96%   |
| Lenovo D27-30 LEN66B8 1920x1080 600x340mm 27.2-inch                    | 1        | 1.96%   |
| Konka TV_MONITOR KOA0030 2288x1430 1150x650mm 52.0-inch                | 1        | 1.96%   |
| Hewlett-Packard LCD Monitor HWP2915 1920x1080 510x290mm 23.1-inch      | 1        | 1.96%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 470x300mm 22.0-inch           | 1        | 1.96%   |
| Hewlett-Packard 24f HPN3545 1920x1080 530x300mm 24.0-inch              | 1        | 1.96%   |
| Goldstar LG HDR WQHD GSM7716 3840x1600 880x370mm 37.6-inch             | 1        | 1.96%   |
| Goldstar LG FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch              | 1        | 1.96%   |
| Goldstar E2340 GSM57C7 1920x1080 510x290mm 23.1-inch                   | 1        | 1.96%   |
| Dell U2711 DELA057 2560x1440 600x340mm 27.2-inch                       | 1        | 1.96%   |
| Dell SP2309W DELD01C 2048x1152 510x290mm 23.1-inch                     | 1        | 1.96%   |
| Dell P2414H DELA09B 1920x1080 530x300mm 24.0-inch                      | 1        | 1.96%   |
| Dell LCD Monitor U2713H 2560x1440                                      | 1        | 1.96%   |
| Dell E248WFP DELA02D 1920x1200 520x320mm 24.0-inch                     | 1        | 1.96%   |
| Compal LCD Monitor WOR2760 2560x1440 600x340mm 27.2-inch               | 1        | 1.96%   |
| Chi Mei Optoelectronics CMC 22 W CMO2228 1680x1050 470x300mm 22.0-inch | 1        | 1.96%   |
| BenQ XL2430T BNQ7F3F 1920x1080 530x300mm 24.0-inch                     | 1        | 1.96%   |
| BenQ GW2255 BNQ78CD 1920x1080 480x270mm 21.7-inch                      | 1        | 1.96%   |
| BenQ EX2710Q BNQ7F87 2560x1440 600x340mm 27.2-inch                     | 1        | 1.96%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 340x190mm 15.3-inch         | 1        | 1.96%   |
| ASUSTek Computer XG49V AUS49A1 3840x1080 1200x340mm 49.1-inch          | 1        | 1.96%   |
| ASUSTek Computer VA32U AUS32A4 3840x2160 700x390mm 31.5-inch           | 1        | 1.96%   |
| AOC Q27P1B AOC2701 2560x1440 600x340mm 27.2-inch                       | 1        | 1.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 21       | 43.75%  |
| 2560x1440 (QHD)    | 9        | 18.75%  |
| 1680x1050 (WSXGA+) | 5        | 10.42%  |
| 3840x2160 (4K)     | 2        | 4.17%   |
| 3840x1600          | 1        | 2.08%   |
| 3840x1080          | 1        | 2.08%   |
| 3440x1440          | 1        | 2.08%   |
| 2560x1080          | 1        | 2.08%   |
| 2288x1430          | 1        | 2.08%   |
| 2048x1152          | 1        | 2.08%   |
| 1920x1200 (WUXGA)  | 1        | 2.08%   |
| 1440x900 (WXGA+)   | 1        | 2.08%   |
| 1360x768           | 1        | 2.08%   |
| 1280x720 (HD)      | 1        | 2.08%   |
| 1280x1024 (SXGA)   | 1        | 2.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 14       | 28%     |
| 24      | 6        | 12%     |
| 21      | 5        | 10%     |
| Unknown | 5        | 10%     |
| 23      | 4        | 8%      |
| 22      | 3        | 6%      |
| 31      | 2        | 4%      |
| 20      | 2        | 4%      |
| 19      | 2        | 4%      |
| 52      | 1        | 2%      |
| 49      | 1        | 2%      |
| 47      | 1        | 2%      |
| 37      | 1        | 2%      |
| 36      | 1        | 2%      |
| 28      | 1        | 2%      |
| 15      | 1        | 2%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 22       | 45.83%  |
| 401-500     | 10       | 20.83%  |
| Unknown     | 5        | 10.42%  |
| 601-700     | 4        | 8.33%   |
| 1001-1500   | 3        | 6.25%   |
| 801-900     | 1        | 2.08%   |
| 701-800     | 1        | 2.08%   |
| 351-400     | 1        | 2.08%   |
| 301-350     | 1        | 2.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 31       | 70.45%  |
| 16/10   | 6        | 13.64%  |
| Unknown | 3        | 6.82%   |
| 21/9    | 2        | 4.55%   |
| 5/4     | 1        | 2.27%   |
| 32/9    | 1        | 2.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 16       | 32.65%  |
| 301-350        | 14       | 28.57%  |
| Unknown        | 5        | 10.2%   |
| 151-200        | 4        | 8.16%   |
| 501-1000       | 4        | 8.16%   |
| 351-500        | 2        | 4.08%   |
| 251-300        | 2        | 4.08%   |
| More than 1000 | 1        | 2.04%   |
| 91-100         | 1        | 2.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 26       | 53.06%  |
| 101-120 | 13       | 26.53%  |
| Unknown | 5        | 10.2%   |
| 121-160 | 3        | 6.12%   |
| 1-50    | 2        | 4.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 361      | 87.83%  |
| 1     | 45       | 10.95%  |
| 2     | 4        | 0.97%   |
| 3     | 1        | 0.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 339      | 63.25%  |
| Realtek Semiconductor    | 122      | 22.76%  |
| Qualcomm Atheros         | 20       | 3.73%   |
| Broadcom                 | 17       | 3.17%   |
| U-Blox                   | 4        | 0.75%   |
| TP-Link                  | 4        | 0.75%   |
| Mellanox Technologies    | 3        | 0.56%   |
| MediaTek                 | 3        | 0.56%   |
| IMC Networks             | 2        | 0.37%   |
| D-Link System            | 2        | 0.37%   |
| Chelsio Communications   | 2        | 0.37%   |
| VIA Technologies         | 1        | 0.19%   |
| TRENDnet                 | 1        | 0.19%   |
| Texas Instruments        | 1        | 0.19%   |
| sipeed                   | 1        | 0.19%   |
| Sierra Wireless          | 1        | 0.19%   |
| Seeed Technology         | 1        | 0.19%   |
| Samsung Electronics      | 1        | 0.19%   |
| Red Hat                  | 1        | 0.19%   |
| Ralink Technology        | 1        | 0.19%   |
| Ralink                   | 1        | 0.19%   |
| Qualcomm                 | 1        | 0.19%   |
| Nvidia                   | 1        | 0.19%   |
| Motorola PCS             | 1        | 0.19%   |
| Marvell Technology Group | 1        | 0.19%   |
| Fry's Electronics        | 1        | 0.19%   |
| D-Link                   | 1        | 0.19%   |
| Arduino SA               | 1        | 0.19%   |
| Aquantia                 | 1        | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 96       | 14.24%  |
| Intel Ethernet Controller I226-V                                              | 93       | 13.8%   |
| Intel I211 Gigabit Network Connection                                         | 48       | 7.12%   |
| Intel Ethernet Controller I225-V                                              | 27       | 4.01%   |
| Intel Ethernet Connection I217-LM                                             | 21       | 3.12%   |
| Intel I210 Gigabit Network Connection                                         | 20       | 2.97%   |
| Realtek RTL8125 2.5GbE Controller                                             | 18       | 2.67%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 18       | 2.67%   |
| Intel I350 Gigabit Network Connection                                         | 12       | 1.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 12       | 1.78%   |
| Intel 82576 Gigabit Network Connection                                        | 12       | 1.78%   |
| Intel Ethernet Connection (7) I219-LM                                         | 11       | 1.63%   |
| Intel Ethernet Connection (5) I219-LM                                         | 11       | 1.63%   |
| Intel Ethernet Connection (2) I219-LM                                         | 11       | 1.63%   |
| Intel 82574L Gigabit Network Connection                                       | 11       | 1.63%   |
| Intel Ethernet Connection (2) I219-V                                          | 10       | 1.48%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 10       | 1.48%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 9        | 1.34%   |
| Intel 82580 Gigabit Network Connection                                        | 8        | 1.19%   |
| Intel Wireless 7260                                                           | 7        | 1.04%   |
| Intel 82583V Gigabit Network Connection                                       | 7        | 1.04%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 6        | 0.89%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 6        | 0.89%   |
| Intel Ethernet Connection (11) I219-LM                                        | 5        | 0.74%   |
| U-Blox [u-blox 7]                                                             | 4        | 0.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 4        | 0.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 4        | 0.59%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 4        | 0.59%   |
| Intel Wireless 3165                                                           | 4        | 0.59%   |
| Intel Wi-Fi 6 AX200                                                           | 4        | 0.59%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 4        | 0.59%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 4        | 0.59%   |
| Intel Ethernet Connection I217-V                                              | 4        | 0.59%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 4        | 0.59%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 4        | 0.59%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 3        | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 3        | 0.45%   |
| Intel Wireless 8265 / 8275                                                    | 3        | 0.45%   |
| Intel Ethernet Controller X550                                                | 3        | 0.45%   |
| Intel Ethernet Connection (7) I219-V                                          | 3        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 43       | 52.44%  |
| Qualcomm Atheros      | 15       | 18.29%  |
| Realtek Semiconductor | 11       | 13.41%  |
| TP-Link               | 3        | 3.66%   |
| MediaTek              | 3        | 3.66%   |
| IMC Networks          | 2        | 2.44%   |
| Sierra Wireless       | 1        | 1.22%   |
| Ralink Technology     | 1        | 1.22%   |
| Ralink                | 1        | 1.22%   |
| D-Link                | 1        | 1.22%   |
| Broadcom              | 1        | 1.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wireless 7260                                                  | 7        | 8.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 4        | 4.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 4        | 4.82%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 4        | 4.82%   |
| Intel Wireless 3165                                                  | 4        | 4.82%   |
| Intel Wi-Fi 6 AX200                                                  | 4        | 4.82%   |
| Intel Wireless 8265 / 8275                                           | 3        | 3.61%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 3        | 3.61%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 2        | 2.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 2        | 2.41%   |
| Intel Wireless 8260                                                  | 2        | 2.41%   |
| Intel Wireless 3160                                                  | 2        | 2.41%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 2        | 2.41%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 2        | 2.41%   |
| Intel Centrino Wireless-N 2230                                       | 2        | 2.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2        | 2.41%   |
| Intel Alder Lake-N PCH CNVi WiFi                                     | 2        | 2.41%   |
| Intel 700 Series Chipset CNVi WiFi                                   | 2        | 2.41%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                 | 2        | 2.41%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 1        | 1.2%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                  | 1        | 1.2%    |
| Sierra Wireless EM7455                                               | 1        | 1.2%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 1        | 1.2%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 1        | 1.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1        | 1.2%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 1        | 1.2%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 1        | 1.2%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                               | 1        | 1.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1        | 1.2%    |
| Ralink RT5572 Wireless Adapter                                       | 1        | 1.2%    |
| Ralink RT5392 PCIe Wireless Network Adapter                          | 1        | 1.2%    |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter      | 1        | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 1.2%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 1        | 1.2%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 1        | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1        | 1.2%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 1        | 1.2%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 1        | 1.2%    |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 1        | 1.2%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 1        | 1.2%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 321      | 67.86%  |
| Realtek Semiconductor    | 115      | 24.31%  |
| Broadcom                 | 16       | 3.38%   |
| Qualcomm Atheros         | 7        | 1.48%   |
| D-Link System            | 2        | 0.42%   |
| Chelsio Communications   | 2        | 0.42%   |
| VIA Technologies         | 1        | 0.21%   |
| TRENDnet                 | 1        | 0.21%   |
| TP-Link                  | 1        | 0.21%   |
| sipeed                   | 1        | 0.21%   |
| Samsung Electronics      | 1        | 0.21%   |
| Qualcomm                 | 1        | 0.21%   |
| Nvidia                   | 1        | 0.21%   |
| Motorola PCS             | 1        | 0.21%   |
| Marvell Technology Group | 1        | 0.21%   |
| Aquantia                 | 1        | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 96       | 16.67%  |
| Intel Ethernet Controller I226-V                                              | 93       | 16.15%  |
| Intel I211 Gigabit Network Connection                                         | 48       | 8.33%   |
| Intel Ethernet Controller I225-V                                              | 27       | 4.69%   |
| Intel Ethernet Connection I217-LM                                             | 21       | 3.65%   |
| Intel I210 Gigabit Network Connection                                         | 20       | 3.47%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 18       | 3.13%   |
| Realtek RTL8125 2.5GbE Controller                                             | 17       | 2.95%   |
| Intel I350 Gigabit Network Connection                                         | 12       | 2.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 12       | 2.08%   |
| Intel 82576 Gigabit Network Connection                                        | 12       | 2.08%   |
| Intel Ethernet Connection (7) I219-LM                                         | 11       | 1.91%   |
| Intel Ethernet Connection (5) I219-LM                                         | 11       | 1.91%   |
| Intel Ethernet Connection (2) I219-LM                                         | 11       | 1.91%   |
| Intel 82574L Gigabit Network Connection                                       | 11       | 1.91%   |
| Intel Ethernet Connection (2) I219-V                                          | 10       | 1.74%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 10       | 1.74%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 9        | 1.56%   |
| Intel 82580 Gigabit Network Connection                                        | 8        | 1.39%   |
| Intel 82583V Gigabit Network Connection                                       | 7        | 1.22%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 6        | 1.04%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 6        | 1.04%   |
| Intel Ethernet Connection (11) I219-LM                                        | 5        | 0.87%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 4        | 0.69%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 4        | 0.69%   |
| Intel Ethernet Connection I217-V                                              | 4        | 0.69%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 4        | 0.69%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 4        | 0.69%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 3        | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 3        | 0.52%   |
| Intel Ethernet Controller X550                                                | 3        | 0.52%   |
| Intel Ethernet Connection (7) I219-V                                          | 3        | 0.52%   |
| Intel 82575EB Gigabit Network Connection                                      | 3        | 0.52%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 0.52%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3        | 0.52%   |
| Realtek USB 2.5GbE Controller                                                 | 2        | 0.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2        | 0.35%   |
| Intel Ethernet Controller I226-LM                                             | 2        | 0.35%   |
| Intel Ethernet Connection X553 Backplane                                      | 2        | 0.35%   |
| Intel Ethernet Connection X553 1GbE                                           | 2        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 406      | 81.04%  |
| WiFi     | 80       | 15.97%  |
| Unknown  | 8        | 1.6%    |
| Modem    | 7        | 1.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 401      | 97.57%  |
| WiFi     | 10       | 2.43%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 4     | 110      | 26.44%  |
| 2     | 87       | 20.91%  |
| 3     | 66       | 15.87%  |
| 1     | 59       | 14.18%  |
| 6     | 37       | 8.89%   |
| 5     | 31       | 7.45%   |
| 9     | 9        | 2.16%   |
| 7     | 7        | 1.68%   |
| 8     | 6        | 1.44%   |
| 10    | 2        | 0.48%   |
| 12    | 1        | 0.24%   |
| 0     | 1        | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 313      | 72.79%  |
| Yes  | 117      | 27.21%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 38       | 57.58%  |
| Realtek Semiconductor           | 7        | 10.61%  |
| Cambridge Silicon Radio         | 7        | 10.61%  |
| Qualcomm Atheros Communications | 5        | 7.58%   |
| MediaTek                        | 3        | 4.55%   |
| ASUSTek Computer                | 3        | 4.55%   |
| Broadcom                        | 2        | 3.03%   |
| Apple                           | 1        | 1.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                          | 15       | 22.39%  |
| Realtek Bluetooth Adapter                                   | 7        | 10.45%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 7        | 10.45%  |
| Intel AX201 Bluetooth                                       | 6        | 8.96%   |
| Intel AX211 Bluetooth                                       | 5        | 7.46%   |
| Intel AX200 Bluetooth                                       | 5        | 7.46%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2        | 2.99%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2        | 2.99%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 2        | 2.99%   |
| Intel AX210 Bluetooth                                       | 2        | 2.99%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 2        | 2.99%   |
| ASUS Qualcomm Bluetooth 4.1                                 | 2        | 2.99%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1        | 1.49%   |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE        | 1        | 1.49%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1        | 1.49%   |
| MediaTek Wireless_Device                                    | 1        | 1.49%   |
| MediaTek RZ608 Bluetooth Adapter                            | 1        | 1.49%   |
| MediaTek Bluetooth Adapter                                  | 1        | 1.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1        | 1.49%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1        | 1.49%   |
| ASUS Bluetooth Controller                                   | 1        | 1.49%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1        | 1.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 306      | 77.86%  |
| AMD                                          | 47       | 11.96%  |
| Nvidia                                       | 25       | 6.36%   |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 0.51%   |
| Thesycon Systemsoftware & Consulting         | 2        | 0.51%   |
| Texas Instruments                            | 2        | 0.51%   |
| Focusrite-Novation                           | 2        | 0.51%   |
| C-Media Electronics                          | 2        | 0.51%   |
| Walmart                                      | 1        | 0.25%   |
| Sony                                         | 1        | 0.25%   |
| Logitech                                     | 1        | 0.25%   |
| Creative Labs                                | 1        | 0.25%   |
| Blue Microphones                             | 1        | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 49       | 10.7%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 33       | 7.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 30       | 6.55%   |
| Intel Jasper Lake HD Audio                                                                        | 24       | 5.24%   |
| Intel 200 Series PCH HD Audio                                                                     | 23       | 5.02%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 22       | 4.8%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 21       | 4.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 17       | 3.71%   |
| Intel Cannon Lake PCH cAVS                                                                        | 14       | 3.06%   |
| AMD Ryzen HD Audio Controller                                                                     | 13       | 2.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12       | 2.62%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 11       | 2.4%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10       | 2.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9        | 1.97%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8        | 1.75%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 7        | 1.53%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7        | 1.53%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 7        | 1.53%   |
| Intel Broadwell-U Audio Controller                                                                | 6        | 1.31%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6        | 1.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5        | 1.09%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5        | 1.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5        | 1.09%   |
| Nvidia High Definition Audio Controller                                                           | 4        | 0.87%   |
| Intel Comet Lake PCH cAVS                                                                         | 4        | 0.87%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 4        | 0.87%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 4        | 0.87%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4        | 0.87%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 4        | 0.87%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4        | 0.87%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4        | 0.87%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 4        | 0.87%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 3        | 0.66%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 3        | 0.66%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3        | 0.66%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3        | 0.66%   |
| AMD Wrestler HDMI Audio                                                                           | 3        | 0.66%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3        | 0.66%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 2        | 0.44%   |
| Nvidia TU102 High Definition Audio Controller                                                     | 2        | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Samsung Electronics                     | 74       | 16.86%  |
| Kingston                                | 55       | 12.53%  |
| SK hynix                                | 51       | 11.62%  |
| Crucial                                 | 50       | 11.39%  |
| Micron Technology                       | 47       | 10.71%  |
| Corsair                                 | 37       | 8.43%   |
| Unknown                                 | 29       | 6.61%   |
| G.Skill                                 | 15       | 3.42%   |
| Unknown                                 | 10       | 2.28%   |
| Team                                    | 8        | 1.82%   |
| Ramaxel Technology                      | 8        | 1.82%   |
| Apacer                                  | 5        | 1.14%   |
| GeIL                                    | 4        | 0.91%   |
| Unknown (ABCD)                          | 3        | 0.68%   |
| Transcend                               | 3        | 0.68%   |
| Silicon Power                           | 3        | 0.68%   |
| Patriot                                 | 3        | 0.68%   |
| Kimtigo                                 | 3        | 0.68%   |
| Innodisk                                | 3        | 0.68%   |
| Unknown (0x0FBA)                        | 2        | 0.46%   |
| Patriot Memory (PDP Systems)            | 2        | 0.46%   |
| Nanya Technology                        | 2        | 0.46%   |
| Hewlett-Packard                         | 2        | 0.46%   |
| Golden Empire                           | 2        | 0.46%   |
| Elpida                                  | 2        | 0.46%   |
| Vasekey                                 | 1        | 0.23%   |
| Uroad                                   | 1        | 0.23%   |
| Unknown (AB)                            | 1        | 0.23%   |
| Unknown (0x0B45)                        | 1        | 0.23%   |
| Unknown (0x0080)                        | 1        | 0.23%   |
| Timetec                                 | 1        | 0.23%   |
| Smart Modular                           | 1        | 0.23%   |
| SK_Hynix                                | 1        | 0.23%   |
| Silicon Power Computer & Communications | 1        | 0.23%   |
| QEMU                                    | 1        | 0.23%   |
| PNY                                     | 1        | 0.23%   |
| Lexar                                   | 1        | 0.23%   |
| Kingmax                                 | 1        | 0.23%   |
| HPE                                     | 1        | 0.23%   |
| Heoriady                                | 1        | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Unknown                                                          | 10       | 2.16%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s              | 9        | 1.95%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s          | 9        | 1.95%   |
| Corsair RAM Module 8GB DIMM DDR4 2133MT/s                        | 5        | 1.08%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s             | 4        | 0.87%   |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s              | 4        | 0.87%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s              | 4        | 0.87%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2133MT/s            | 4        | 0.87%   |
| Micron RAM 8ATF1G64AZ-2G3H1 8GB DIMM DDR4 2400MT/s               | 4        | 0.87%   |
| Crucial RAM CT8G48C40S5.M4A1 8GB SODIMM DDR5 4800MT/s            | 4        | 0.87%   |
| Corsair RAM CMSX16GX5M1A4800C40 16GB SODIMM DDR5 4800MT/s        | 4        | 0.87%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 3        | 0.65%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 3        | 0.65%   |
| Unknown (ABCD) RAM 123456789012345678 8GB DIMM DDR4 2400MT/s     | 3        | 0.65%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3        | 0.65%   |
| SK hynix RAM HMCG78AEBSA092N 16GB SODIMM DDR5 4800MT/s           | 3        | 0.65%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 3        | 0.65%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3        | 0.65%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3        | 0.65%   |
| Micron RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s           | 3        | 0.65%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                   | 3        | 0.65%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s            | 3        | 0.65%   |
| Crucial RAM CT16G4SFRA32A.M16FR 16GB SODIMM DDR4 3200MT/s        | 3        | 0.65%   |
| Corsair RAM CMZ16GX3M2A1600C9 8GB DIMM DDR3 1600MT/s             | 3        | 0.65%   |
| Corsair RAM CMK16GX4M2A2133C13 8GB DIMM DDR4 3200MT/s            | 3        | 0.65%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 2        | 0.43%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 2        | 0.43%   |
| Unknown RAM Module 8GB 1600MT/s                                  | 2        | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 2        | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 2        | 0.43%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 2        | 0.43%   |
| Unknown (0x0FBA) RAM TENGYIN-16GB-5600 16GB SODIMM DDR5 5600MT/s | 2        | 0.43%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s               | 2        | 0.43%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2667MT/s              | 2        | 0.43%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s             | 2        | 0.43%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2        | 0.43%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s             | 2        | 0.43%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s           | 2        | 0.43%   |
| SK hynix RAM HMCG66AEBSA095N 8GB SODIMM DDR5 4800MT/s            | 2        | 0.43%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 2        | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 178      | 45.64%  |
| DDR3    | 129      | 33.08%  |
| DDR5    | 55       | 14.1%   |
| Unknown | 13       | 3.33%   |
| DDR2    | 5        | 1.28%   |
| LPDDR4  | 4        | 1.03%   |
| LPDDR5  | 3        | 0.77%   |
| DDR     | 2        | 0.51%   |
| RAM     | 1        | 0.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 206      | 53.09%  |
| SODIMM       | 170      | 43.81%  |
| Unknown      | 7        | 1.8%    |
| Row Of Chips | 4        | 1.03%   |
| RIMM         | 1        | 0.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 178      | 43.63%  |
| 16384 | 97       | 23.77%  |
| 4096  | 86       | 21.08%  |
| 2048  | 26       | 6.37%   |
| 32768 | 15       | 3.68%   |
| 1024  | 5        | 1.23%   |
| 3072  | 1        | 0.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 108      | 26.21%  |
| 3200    | 50       | 12.14%  |
| 2400    | 45       | 10.92%  |
| 2133    | 42       | 10.19%  |
| 4800    | 41       | 9.95%   |
| 2667    | 39       | 9.47%   |
| 1333    | 30       | 7.28%   |
| 5600    | 16       | 3.88%   |
| 800     | 9        | 2.18%   |
| 3600    | 7        | 1.7%    |
| 2666    | 5        | 1.21%   |
| 1066    | 4        | 0.97%   |
| Unknown | 3        | 0.73%   |
| 6400    | 2        | 0.49%   |
| 3066    | 2        | 0.49%   |
| 3000    | 2        | 0.49%   |
| 1867    | 2        | 0.49%   |
| 400     | 2        | 0.49%   |
| 59392   | 1        | 0.24%   |
| 3733    | 1        | 0.24%   |
| 667     | 1        | 0.24%   |

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


| Model               | Desktops | Percent |
|---------------------|----------|---------|
| HP LaserJet 3390    | 1        | 50%     |
| Brother DCP-9015CDW | 1        | 50%     |

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


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Logitech | 2        | 66.67%  |
| Microdia | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Microdia USB  Live camera       | 1        | 33.33%  |
| Logitech HD Pro Webcam C920     | 1        | 33.33%  |
| Logitech C922 Pro Stream Webcam | 1        | 33.33%  |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Shenzhen Goodix Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Shenzhen Goodix Fingerprint Reader | 1        | 100%    |

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
| 1     | 245      | 58.33%  |
| 0     | 100      | 23.81%  |
| 2     | 47       | 11.19%  |
| 3     | 20       | 4.76%   |
| 4     | 7        | 1.67%   |
| 5     | 1        | 0.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 296      | 78.1%   |
| Bluetooth                | 29       | 7.65%   |
| Net/wireless             | 19       | 5.01%   |
| Network                  | 10       | 2.64%   |
| Card reader              | 7        | 1.85%   |
| Sound                    | 6        | 1.58%   |
| Net/ethernet             | 4        | 1.06%   |
| Firewire controller      | 4        | 1.06%   |
| Storage/raid             | 2        | 0.53%   |
| Modem                    | 1        | 0.26%   |
| Dvb card                 | 1        | 0.26%   |

