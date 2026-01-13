BSD in Australia - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for BSD in Australia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Australia/Desktop/README.md) and [notebooks](/Location/Australia/Notebook/README.md).

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

Total: 1007

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Protectli     | FW2B Ver                    | Desktop     | [f3be3b3acc](https://bsd-hardware.info/?probe=f3be3b3acc) | Dec 31, 2025 |
| Unknown       | QDNV01                      | Desktop     | [7782909112](https://bsd-hardware.info/?probe=7782909112) | Dec 31, 2025 |
| Shuttle       | DS77U                       | Notebook    | [6bf60f3010](https://bsd-hardware.info/?probe=6bf60f3010) | Dec 27, 2025 |
| Unknown       | Unknown                     | Desktop     | [257e8393ec](https://bsd-hardware.info/?probe=257e8393ec) | Dec 24, 2025 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [ea74c27094](https://bsd-hardware.info/?probe=ea74c27094) | Dec 18, 2025 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [181e2e0e68](https://bsd-hardware.info/?probe=181e2e0e68) | Dec 15, 2025 |
| Intel         | CM11EBI38W K93946-306       | Mini pc     | [d4c7315e12](https://bsd-hardware.info/?probe=d4c7315e12) | Dec 15, 2025 |
| MSI           | B450M-A PRO MAX II          | Desktop     | [50e2dafd2a](https://bsd-hardware.info/?probe=50e2dafd2a) | Dec 14, 2025 |
| HP            | 8103 A01                    | Mini pc     | [e63548e14d](https://bsd-hardware.info/?probe=e63548e14d) | Dec 13, 2025 |
| Dynabook      | TECRA A65-M                 | Notebook    | [840b58a6a7](https://bsd-hardware.info/?probe=840b58a6a7) | Dec 13, 2025 |
| Dell          | 0C1R19 A02                  | Desktop     | [c0edad3b9e](https://bsd-hardware.info/?probe=c0edad3b9e) | Dec 13, 2025 |
| Unknown       | Unknown                     | Desktop     | [e60e976fcc](https://bsd-hardware.info/?probe=e60e976fcc) | Dec 13, 2025 |
| Unknown       | Unknown                     | Desktop     | [e3c5a7d8a0](https://bsd-hardware.info/?probe=e3c5a7d8a0) | Dec 09, 2025 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [e87e11e303](https://bsd-hardware.info/?probe=e87e11e303) | Dec 09, 2025 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [928730b34f](https://bsd-hardware.info/?probe=928730b34f) | Dec 09, 2025 |
| Unknown       | Unknown                     | Desktop     | [a9ddb2b45d](https://bsd-hardware.info/?probe=a9ddb2b45d) | Dec 07, 2025 |
| Lenovo        | ThinkPad Yoga 370 20JH00... | Convertible | [76fc7495eb](https://bsd-hardware.info/?probe=76fc7495eb) | Dec 05, 2025 |
| AMI           | Aptio CRB                   | Mini pc     | [dc04f5ab9d](https://bsd-hardware.info/?probe=dc04f5ab9d) | Dec 04, 2025 |
| Unknown       | Unknown                     | Desktop     | [bebe952710](https://bsd-hardware.info/?probe=bebe952710) | Nov 29, 2025 |
| Dell          | 0GCPWH A00                  | Mini pc     | [a5a17e1c0e](https://bsd-hardware.info/?probe=a5a17e1c0e) | Nov 29, 2025 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [7d166f4be3](https://bsd-hardware.info/?probe=7d166f4be3) | Nov 28, 2025 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [e77e132d34](https://bsd-hardware.info/?probe=e77e132d34) | Nov 27, 2025 |
| Unknown       | QGLK03                      | Desktop     | [4a31564adb](https://bsd-hardware.info/?probe=4a31564adb) | Nov 26, 2025 |
| Unknown       | Unknown                     | Desktop     | [6a0bdd5f1a](https://bsd-hardware.info/?probe=6a0bdd5f1a) | Nov 25, 2025 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [84ae69157a](https://bsd-hardware.info/?probe=84ae69157a) | Nov 24, 2025 |
| Dell          | 0HV8FN A01                  | Desktop     | [f3f98de7a9](https://bsd-hardware.info/?probe=f3f98de7a9) | Nov 23, 2025 |
| NP93B         | 1.0                         | Desktop     | [6f1223b8b2](https://bsd-hardware.info/?probe=6f1223b8b2) | Nov 23, 2025 |
| Dell          | 0HD5W2 A01                  | Desktop     | [ea7fbcfa45](https://bsd-hardware.info/?probe=ea7fbcfa45) | Nov 23, 2025 |
| Dell          | 0HV8FN A01                  | Desktop     | [f3140018c7](https://bsd-hardware.info/?probe=f3140018c7) | Nov 22, 2025 |
| Dell          | 0NW6H5 A00                  | Desktop     | [9ad54fb46b](https://bsd-hardware.info/?probe=9ad54fb46b) | Nov 19, 2025 |
| Lenovo        | LOQ 15IRX9 83DV             | Notebook    | [dd92947fcc](https://bsd-hardware.info/?probe=dd92947fcc) | Nov 18, 2025 |
| Unknown       | Unknown                     | Desktop     | [3e673d4541](https://bsd-hardware.info/?probe=3e673d4541) | Nov 17, 2025 |
| Dell          | 0HV8FN A01                  | Desktop     | [3d1e92c58a](https://bsd-hardware.info/?probe=3d1e92c58a) | Nov 16, 2025 |
| Dell          | 0GCPWH A00                  | Mini pc     | [a6a4008dc7](https://bsd-hardware.info/?probe=a6a4008dc7) | Nov 15, 2025 |
| Dell          | 0NW6H5 A00                  | Desktop     | [6bf6b0188f](https://bsd-hardware.info/?probe=6bf6b0188f) | Nov 13, 2025 |
| AMI           | Aptio CRB                   | Mini pc     | [3e768ef965](https://bsd-hardware.info/?probe=3e768ef965) | Nov 11, 2025 |
| MSI           | B450M-A PRO MAX II          | Desktop     | [355a233604](https://bsd-hardware.info/?probe=355a233604) | Nov 09, 2025 |
| BESSTAR Te... | GB7                         | Mini pc     | [c806461b9e](https://bsd-hardware.info/?probe=c806461b9e) | Nov 07, 2025 |
| Dell          | 0NC2VH A01                  | Desktop     | [aad305c619](https://bsd-hardware.info/?probe=aad305c619) | Nov 07, 2025 |
| ADI Engine... | RCC-VE                      | Desktop     | [bdd2ca79b8](https://bsd-hardware.info/?probe=bdd2ca79b8) | Nov 07, 2025 |
| Supermicro    | X11SSH-F                    | Server      | [5da89bbb29](https://bsd-hardware.info/?probe=5da89bbb29) | Nov 07, 2025 |
| BESSTAR Te... | GB7                         | Mini pc     | [50b4c41ecc](https://bsd-hardware.info/?probe=50b4c41ecc) | Nov 06, 2025 |
| Unknown       | Unknown                     | Desktop     | [c81ec1565c](https://bsd-hardware.info/?probe=c81ec1565c) | Nov 06, 2025 |
| Protectli     | V1410                       | Desktop     | [8eb8ae712d](https://bsd-hardware.info/?probe=8eb8ae712d) | Nov 05, 2025 |
| Unknown       | Unknown                     | Desktop     | [7f3c67382d](https://bsd-hardware.info/?probe=7f3c67382d) | Nov 04, 2025 |
| HP            | ProLiant DL380 Gen9         | Server      | [999f068923](https://bsd-hardware.info/?probe=999f068923) | Nov 04, 2025 |
| Unknown       | Unknown                     | Desktop     | [19d5f6fc2e](https://bsd-hardware.info/?probe=19d5f6fc2e) | Nov 03, 2025 |
| Dell          | 0YC03K A04                  | Desktop     | [0ad1654af2](https://bsd-hardware.info/?probe=0ad1654af2) | Nov 01, 2025 |
| Protectli     | VP4670                      | Desktop     | [0cb44017eb](https://bsd-hardware.info/?probe=0cb44017eb) | Oct 31, 2025 |
| Apple         | MacBookPro7,1               | Notebook    | [f4e3b1813c](https://bsd-hardware.info/?probe=f4e3b1813c) | Oct 31, 2025 |
| Unknown       | Unknown                     | Desktop     | [533b617aa9](https://bsd-hardware.info/?probe=533b617aa9) | Oct 30, 2025 |
| MSI           | MS-B0A81                    | Desktop     | [bf65eaba1d](https://bsd-hardware.info/?probe=bf65eaba1d) | Oct 29, 2025 |
| GMKtec        | NucBox M6 Ultra             | Mini pc     | [7d8e022be2](https://bsd-hardware.info/?probe=7d8e022be2) | Oct 26, 2025 |
| TianBei       | N1 PRO                      | Desktop     | [63ae5ffd65](https://bsd-hardware.info/?probe=63ae5ffd65) | Oct 25, 2025 |
| Supermicro    | X10SDV-TLN4F                | Server      | [b040cb35ec](https://bsd-hardware.info/?probe=b040cb35ec) | Oct 23, 2025 |
| Unknown       | Unknown                     | Desktop     | [f64d141e9a](https://bsd-hardware.info/?probe=f64d141e9a) | Oct 23, 2025 |
| Supermicro    | X10SDV-TLN4F                | Server      | [f2e2757a7c](https://bsd-hardware.info/?probe=f2e2757a7c) | Oct 21, 2025 |
| GMKtec        | NucBox M6 Ultra             | Mini pc     | [0c50e7547e](https://bsd-hardware.info/?probe=0c50e7547e) | Oct 18, 2025 |
| Unknown       | Unknown                     | Desktop     | [73a0b1ec82](https://bsd-hardware.info/?probe=73a0b1ec82) | Oct 17, 2025 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [69314d3cdb](https://bsd-hardware.info/?probe=69314d3cdb) | Oct 12, 2025 |
| Unknown       | Unknown                     | Desktop     | [71edad02c1](https://bsd-hardware.info/?probe=71edad02c1) | Oct 11, 2025 |
| Unknown       | Unknown                     | Desktop     | [0c58822675](https://bsd-hardware.info/?probe=0c58822675) | Oct 07, 2025 |
| Unknown       | Unknown                     | Desktop     | [69449c5ebb](https://bsd-hardware.info/?probe=69449c5ebb) | Oct 06, 2025 |
| Gigabyte      | Z87-HD3                     | Desktop     | [2bf937d238](https://bsd-hardware.info/?probe=2bf937d238) | Oct 06, 2025 |
| Gigabyte      | Z87-HD3                     | Desktop     | [72832870f1](https://bsd-hardware.info/?probe=72832870f1) | Oct 05, 2025 |
| Deciso        | NetBoard-A20 R2.0           | Server      | [232037e5c8](https://bsd-hardware.info/?probe=232037e5c8) | Oct 05, 2025 |
| Gigabyte      | Z790 AORUS ELITE DDR4       | Desktop     | [d5f342b91d](https://bsd-hardware.info/?probe=d5f342b91d) | Oct 04, 2025 |
| Datto         | SSD                         | Desktop     | [7fb3456566](https://bsd-hardware.info/?probe=7fb3456566) | Oct 02, 2025 |
| Protectli     | VP2410 10                   | Desktop     | [74e93e9803](https://bsd-hardware.info/?probe=74e93e9803) | Sep 30, 2025 |
| Gigabyte      | Z790 AORUS ELITE DDR4       | Desktop     | [c269c0cb0e](https://bsd-hardware.info/?probe=c269c0cb0e) | Sep 29, 2025 |
| MSI           | B450M-A PRO MAX II          | Desktop     | [4ec36facdc](https://bsd-hardware.info/?probe=4ec36facdc) | Sep 28, 2025 |
| Dell          | 0D6H9T A01                  | Desktop     | [a5aa09e802](https://bsd-hardware.info/?probe=a5aa09e802) | Sep 28, 2025 |
| Unknown       | Unknown                     | Desktop     | [faba9ef2a2](https://bsd-hardware.info/?probe=faba9ef2a2) | Sep 27, 2025 |
| Protectli     | FW2B                        | Desktop     | [ad5108cb3b](https://bsd-hardware.info/?probe=ad5108cb3b) | Sep 27, 2025 |
| Unknown       | Unknown                     | Desktop     | [466958e099](https://bsd-hardware.info/?probe=466958e099) | Sep 27, 2025 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [a3a26a3389](https://bsd-hardware.info/?probe=a3a26a3389) | Sep 27, 2025 |
| Unknown       | Unknown                     | Desktop     | [5b8b173624](https://bsd-hardware.info/?probe=5b8b173624) | Sep 26, 2025 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [af25961555](https://bsd-hardware.info/?probe=af25961555) | Sep 26, 2025 |
| Unknown       | Unknown                     | Desktop     | [de80f263e0](https://bsd-hardware.info/?probe=de80f263e0) | Sep 24, 2025 |
| Sophos        | SG                          | Firewall    | [115907cd5f](https://bsd-hardware.info/?probe=115907cd5f) | Sep 22, 2025 |
| Unknown       | Unknown                     | Desktop     | [ac07639f07](https://bsd-hardware.info/?probe=ac07639f07) | Sep 22, 2025 |
| Dell          | 0NW6H5 A00                  | Desktop     | [9ea6d64621](https://bsd-hardware.info/?probe=9ea6d64621) | Sep 21, 2025 |
| Unknown       | Unknown                     | Desktop     | [4ab315db11](https://bsd-hardware.info/?probe=4ab315db11) | Sep 19, 2025 |
| MW            | GMLK-2_5G4L                 | Desktop     | [eca82f1479](https://bsd-hardware.info/?probe=eca82f1479) | Sep 19, 2025 |
| Winston Ma... | PICO PC V1.2                | Desktop     | [b81dd0f407](https://bsd-hardware.info/?probe=b81dd0f407) | Sep 17, 2025 |
| HP            | 8299                        | Desktop     | [44109f1adf](https://bsd-hardware.info/?probe=44109f1adf) | Sep 17, 2025 |
| Protectli     | VP4630                      | Desktop     | [8a46f1574f](https://bsd-hardware.info/?probe=8a46f1574f) | Sep 16, 2025 |
| Protectli     | VP4630                      | Desktop     | [87f440eea7](https://bsd-hardware.info/?probe=87f440eea7) | Sep 16, 2025 |
| Techvision    | TVI7309X B0                 | Desktop     | [22ad1a6ae2](https://bsd-hardware.info/?probe=22ad1a6ae2) | Sep 15, 2025 |
| Dell          | 0XCR8D A01                  | Desktop     | [1563de278c](https://bsd-hardware.info/?probe=1563de278c) | Sep 15, 2025 |
| Unknown       | Unknown                     | Desktop     | [115183390a](https://bsd-hardware.info/?probe=115183390a) | Sep 14, 2025 |
| Unknown       | Unknown                     | Desktop     | [29a9ccec16](https://bsd-hardware.info/?probe=29a9ccec16) | Sep 14, 2025 |
| YANYU         | H67SL                       | Desktop     | [c072dcc982](https://bsd-hardware.info/?probe=c072dcc982) | Sep 13, 2025 |
| HP            | EliteBook 850 G2            | Notebook    | [735796bf17](https://bsd-hardware.info/?probe=735796bf17) | Sep 11, 2025 |
| Supermicro    | H11SSL-i                    | Server      | [630e6220a6](https://bsd-hardware.info/?probe=630e6220a6) | Sep 07, 2025 |
| Supermicro    | H11SSL-i                    | Server      | [4c131105e4](https://bsd-hardware.info/?probe=4c131105e4) | Sep 07, 2025 |
| HP            | EliteBook 850 G2            | Notebook    | [cf6d05a5d4](https://bsd-hardware.info/?probe=cf6d05a5d4) | Sep 07, 2025 |
| Unknown       | Unknown                     | Desktop     | [0bfcac0761](https://bsd-hardware.info/?probe=0bfcac0761) | Sep 05, 2025 |
| Techvision    | TVI7309X B0                 | Desktop     | [788707444e](https://bsd-hardware.info/?probe=788707444e) | Sep 05, 2025 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [b4dfb3fe25](https://bsd-hardware.info/?probe=b4dfb3fe25) | Sep 04, 2025 |
| Unknown       | Unknown                     | Desktop     | [4cb009287a](https://bsd-hardware.info/?probe=4cb009287a) | Sep 04, 2025 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [c0bd53c3e2](https://bsd-hardware.info/?probe=c0bd53c3e2) | Sep 03, 2025 |
| Dell          | 0D6H9T A01                  | Desktop     | [52b9561767](https://bsd-hardware.info/?probe=52b9561767) | Aug 26, 2025 |
| Dell          | 0NW6H5 A00                  | Desktop     | [3107de51de](https://bsd-hardware.info/?probe=3107de51de) | Aug 26, 2025 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d837670268](https://bsd-hardware.info/?probe=d837670268) | Aug 26, 2025 |
| Unknown       | Unknown                     | Desktop     | [d11c3c4b4c](https://bsd-hardware.info/?probe=d11c3c4b4c) | Aug 25, 2025 |
| HP            | 212A                        | Desktop     | [30b0fc9b4b](https://bsd-hardware.info/?probe=30b0fc9b4b) | Aug 24, 2025 |
| HP            | ProLiant DL380 Gen9         | Server      | [86d2f511df](https://bsd-hardware.info/?probe=86d2f511df) | Aug 24, 2025 |
| Dell          | 0C522T A03                  | Desktop     | [eb89c60c0c](https://bsd-hardware.info/?probe=eb89c60c0c) | Aug 24, 2025 |
| Deciso        | NetBoard-A10_Gen.3          | Notebook    | [542252ee3c](https://bsd-hardware.info/?probe=542252ee3c) | Aug 23, 2025 |
| Unknown       | Unknown                     | Desktop     | [735deaf0f1](https://bsd-hardware.info/?probe=735deaf0f1) | Aug 23, 2025 |
| MSI           | MS-B0A81                    | Desktop     | [fc0a60684a](https://bsd-hardware.info/?probe=fc0a60684a) | Aug 23, 2025 |
| Unknown       | Unknown                     | Desktop     | [852a1a2d11](https://bsd-hardware.info/?probe=852a1a2d11) | Aug 23, 2025 |
| HP            | 3048h                       | Desktop     | [efd50eb795](https://bsd-hardware.info/?probe=efd50eb795) | Aug 23, 2025 |
| Inventec      | D CLASS A02                 | Desktop     | [3cc1d7bf13](https://bsd-hardware.info/?probe=3cc1d7bf13) | Aug 22, 2025 |
| Techvision    | TVI7309X B0                 | Desktop     | [6ee3a79a4e](https://bsd-hardware.info/?probe=6ee3a79a4e) | Aug 21, 2025 |
| TianBei       | N1 PRO                      | Desktop     | [d6622f16f1](https://bsd-hardware.info/?probe=d6622f16f1) | Aug 20, 2025 |
| Techvision    | TVI7309X B0                 | Desktop     | [475e154cc0](https://bsd-hardware.info/?probe=475e154cc0) | Aug 20, 2025 |
| Intel         | D54250WYK H13922-305        | Desktop     | [360e04f1d2](https://bsd-hardware.info/?probe=360e04f1d2) | Aug 19, 2025 |
| Supermicro    | X10SDV-TLN4F                | Server      | [4e0e9480ac](https://bsd-hardware.info/?probe=4e0e9480ac) | Aug 18, 2025 |
| MW            | GMLK-2_5G4L                 | Desktop     | [deae839e4d](https://bsd-hardware.info/?probe=deae839e4d) | Aug 18, 2025 |
| Dell          | 0D6H9T A01                  | Desktop     | [8ac7db7775](https://bsd-hardware.info/?probe=8ac7db7775) | Aug 18, 2025 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [04f23441a1](https://bsd-hardware.info/?probe=04f23441a1) | Aug 15, 2025 |
| Lenovo        | 30D0 SDK0L22692 WIN 3306... | Desktop     | [7f492e6106](https://bsd-hardware.info/?probe=7f492e6106) | Aug 12, 2025 |
| MW            | GMLK-2_5G4L                 | Desktop     | [d9b9a43146](https://bsd-hardware.info/?probe=d9b9a43146) | Aug 10, 2025 |
| CWWK          | CW-ADLN-6L                  | Desktop     | [dcf30c34c1](https://bsd-hardware.info/?probe=dcf30c34c1) | Aug 06, 2025 |
| Gigabyte      | Q370M D3H GSM PLUS          | Desktop     | [184b8f1112](https://bsd-hardware.info/?probe=184b8f1112) | Aug 05, 2025 |
| Unknown       | Unknown                     | Desktop     | [b2f5ba69c4](https://bsd-hardware.info/?probe=b2f5ba69c4) | Aug 05, 2025 |
| Unknown       | Unknown                     | Desktop     | [86f7a75fa7](https://bsd-hardware.info/?probe=86f7a75fa7) | Aug 02, 2025 |
| Sophos        | XG                          | Firewall    | [787a553861](https://bsd-hardware.info/?probe=787a553861) | Jul 31, 2025 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [54699e46ab](https://bsd-hardware.info/?probe=54699e46ab) | Jul 30, 2025 |
| Intel         | BKHD-1264-SFP               | Desktop     | [6652d83aac](https://bsd-hardware.info/?probe=6652d83aac) | Jul 29, 2025 |
| Lenovo        | 30D0 SDK0L22692 WIN 3306... | Desktop     | [6cad88d666](https://bsd-hardware.info/?probe=6cad88d666) | Jul 27, 2025 |
| Protectli     | VP4630                      | Desktop     | [6701c837f7](https://bsd-hardware.info/?probe=6701c837f7) | Jul 26, 2025 |
| Unknown       | Unknown                     | Desktop     | [88cb9f9ef6](https://bsd-hardware.info/?probe=88cb9f9ef6) | Jul 24, 2025 |
| Protectli     | FW4B Ver                    | Desktop     | [efd941891b](https://bsd-hardware.info/?probe=efd941891b) | Jul 22, 2025 |
| Unknown       | Unknown                     | Desktop     | [19a1044651](https://bsd-hardware.info/?probe=19a1044651) | Jul 22, 2025 |
| Deciso        | NetBoard-A20 R2.0           | Server      | [0089c08cf7](https://bsd-hardware.info/?probe=0089c08cf7) | Jul 22, 2025 |
| Unknown       | Unknown                     | Desktop     | [b9949ee84f](https://bsd-hardware.info/?probe=b9949ee84f) | Jul 21, 2025 |
| Techvision    | TVI7309X B0                 | Desktop     | [ec73493808](https://bsd-hardware.info/?probe=ec73493808) | Jul 20, 2025 |
| Supermicro    | X11SSH-F                    | Server      | [a541fadf5c](https://bsd-hardware.info/?probe=a541fadf5c) | Jul 19, 2025 |
| Dell          | 0NC2VH A01                  | Desktop     | [0f1b12cd50](https://bsd-hardware.info/?probe=0f1b12cd50) | Jul 19, 2025 |
| PC Engines    | APU2                        | Desktop     | [6824c194a5](https://bsd-hardware.info/?probe=6824c194a5) | Jul 13, 2025 |
| Sophos        | XG                          | Firewall    | [8820eb7d2d](https://bsd-hardware.info/?probe=8820eb7d2d) | Jul 12, 2025 |
| Intel         | DENLOW_WS                   | Desktop     | [d89f914c6b](https://bsd-hardware.info/?probe=d89f914c6b) | Jul 11, 2025 |
| Intel         | DENLOW_WS                   | Desktop     | [c1640614b1](https://bsd-hardware.info/?probe=c1640614b1) | Jul 11, 2025 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [5c93fe81a4](https://bsd-hardware.info/?probe=5c93fe81a4) | Jul 10, 2025 |
| Protectli     | VP2410 10                   | Desktop     | [2fd150def7](https://bsd-hardware.info/?probe=2fd150def7) | Jul 07, 2025 |
| Intel         | S1200BTL E98681-352         | Server      | [0311f177b2](https://bsd-hardware.info/?probe=0311f177b2) | Jul 07, 2025 |
| Gigabyte      | Z790 AORUS ELITE DDR4       | Desktop     | [8386db50b7](https://bsd-hardware.info/?probe=8386db50b7) | Jul 07, 2025 |
| Intel         | S1200BTL E98681-352         | Server      | [454e49af0d](https://bsd-hardware.info/?probe=454e49af0d) | Jul 05, 2025 |
| Unknown       | Unknown                     | Desktop     | [b1e054b1ef](https://bsd-hardware.info/?probe=b1e054b1ef) | Jul 04, 2025 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [3ab859ab25](https://bsd-hardware.info/?probe=3ab859ab25) | Jul 03, 2025 |
| Unknown       | Unknown                     | All in one  | [e3a1bb1aa8](https://bsd-hardware.info/?probe=e3a1bb1aa8) | Jul 03, 2025 |
| Unknown       | Unknown                     | Desktop     | [7118d6b609](https://bsd-hardware.info/?probe=7118d6b609) | Jul 03, 2025 |
| Deciso        | NetBoard-A20 R2.0           | Server      | [8cfb907b2e](https://bsd-hardware.info/?probe=8cfb907b2e) | Jul 02, 2025 |
| Gigabyte      | Z790 AORUS ELITE DDR4       | Desktop     | [e9bc7f47c0](https://bsd-hardware.info/?probe=e9bc7f47c0) | Jun 30, 2025 |
| Unknown       | Unknown                     | Desktop     | [8629885ea3](https://bsd-hardware.info/?probe=8629885ea3) | Jun 30, 2025 |
| Deciso        | NetBoard-A20 R2.0           | Server      | [0134ddfc5c](https://bsd-hardware.info/?probe=0134ddfc5c) | Jun 28, 2025 |
| ASUSTek       | H61M-K                      | Desktop     | [ae9d91cce3](https://bsd-hardware.info/?probe=ae9d91cce3) | Jun 28, 2025 |
| Unknown       | Unknown                     | Desktop     | [5dc2f76004](https://bsd-hardware.info/?probe=5dc2f76004) | Jun 27, 2025 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [13d0033aa3](https://bsd-hardware.info/?probe=13d0033aa3) | Jun 27, 2025 |
| Unknown       | Unknown                     | Desktop     | [46a3594e44](https://bsd-hardware.info/?probe=46a3594e44) | Jun 25, 2025 |
| HP            | 8299                        | Desktop     | [6f482a75f7](https://bsd-hardware.info/?probe=6f482a75f7) | Jun 24, 2025 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | Desktop     | [08a43c80ed](https://bsd-hardware.info/?probe=08a43c80ed) | Jun 23, 2025 |
| HP            | 8299                        | Desktop     | [c971eb05c2](https://bsd-hardware.info/?probe=c971eb05c2) | Jun 23, 2025 |
| Dell          | 096JG8 A01                  | Desktop     | [d951945344](https://bsd-hardware.info/?probe=d951945344) | Jun 22, 2025 |
| Dell          | 00CV7F A00                  | Desktop     | [28f4056136](https://bsd-hardware.info/?probe=28f4056136) | Jun 22, 2025 |
| Unknown       | Unknown                     | Desktop     | [8bbced361a](https://bsd-hardware.info/?probe=8bbced361a) | Jun 20, 2025 |
| MW            | GMLK-2_5G4L                 | Desktop     | [9dc4b45e85](https://bsd-hardware.info/?probe=9dc4b45e85) | Jun 19, 2025 |
| Dell          | 05842Y A00                  | Desktop     | [33562da12c](https://bsd-hardware.info/?probe=33562da12c) | Jun 19, 2025 |
| Unknown       | Unknown                     | Desktop     | [97b9cf55d3](https://bsd-hardware.info/?probe=97b9cf55d3) | Jun 15, 2025 |
| Dell          | 0M877N A02                  | Server      | [cfb026b878](https://bsd-hardware.info/?probe=cfb026b878) | Jun 14, 2025 |
| Unknown       | Unknown                     | Desktop     | [4a928d008a](https://bsd-hardware.info/?probe=4a928d008a) | Jun 11, 2025 |
| Sophos        | XG                          | Firewall    | [5a9f653f09](https://bsd-hardware.info/?probe=5a9f653f09) | Jun 10, 2025 |
| Sophos        | XG                          | Firewall    | [4867816ff1](https://bsd-hardware.info/?probe=4867816ff1) | Jun 10, 2025 |
| AZW           | U57                         | Mini pc     | [dbd834c2a3](https://bsd-hardware.info/?probe=dbd834c2a3) | Jun 06, 2025 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [fa655ea070](https://bsd-hardware.info/?probe=fa655ea070) | Jun 03, 2025 |
| Citrix        | CB-1100                     | Desktop     | [08bb9f20a8](https://bsd-hardware.info/?probe=08bb9f20a8) | Jun 01, 2025 |
| Protectli     | FW4B Ver                    | Desktop     | [d2e468f4ae](https://bsd-hardware.info/?probe=d2e468f4ae) | May 31, 2025 |
| Apple         | Mac-7BA5B2794B2CDB12 Mac... | Mini pc     | [d1a4b4b4f2](https://bsd-hardware.info/?probe=d1a4b4b4f2) | May 31, 2025 |
| Apple         | Mac-7BA5B2794B2CDB12 Mac... | Mini pc     | [0e9d8144b0](https://bsd-hardware.info/?probe=0e9d8144b0) | May 31, 2025 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [08b55e0bab](https://bsd-hardware.info/?probe=08b55e0bab) | May 27, 2025 |
| AZW           | GK55                        | Desktop     | [81600568e3](https://bsd-hardware.info/?probe=81600568e3) | May 27, 2025 |
| Unknown       | Unknown                     | Desktop     | [dbc29e346b](https://bsd-hardware.info/?probe=dbc29e346b) | May 26, 2025 |
| Unknown       | Unknown                     | Desktop     | [e523323e19](https://bsd-hardware.info/?probe=e523323e19) | May 25, 2025 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [f8a8851ab5](https://bsd-hardware.info/?probe=f8a8851ab5) | May 20, 2025 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [dd4f6b856f](https://bsd-hardware.info/?probe=dd4f6b856f) | May 18, 2025 |
| Unknown       | Unknown                     | Desktop     | [ada674b101](https://bsd-hardware.info/?probe=ada674b101) | May 16, 2025 |
| Unknown       | Unknown                     | Desktop     | [c563722734](https://bsd-hardware.info/?probe=c563722734) | May 16, 2025 |
| ASRock        | X99 Taichi                  | Desktop     | [89be650fad](https://bsd-hardware.info/?probe=89be650fad) | May 15, 2025 |
| LinuxConta... | Incus pc-q35-7.2            | Desktop     | [f4c11c64c9](https://bsd-hardware.info/?probe=f4c11c64c9) | May 12, 2025 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [2f03153022](https://bsd-hardware.info/?probe=2f03153022) | May 11, 2025 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [b36c519819](https://bsd-hardware.info/?probe=b36c519819) | May 09, 2025 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [8d2de26425](https://bsd-hardware.info/?probe=8d2de26425) | May 09, 2025 |
| Unknown       | Unknown                     | Desktop     | [1b97008abd](https://bsd-hardware.info/?probe=1b97008abd) | May 08, 2025 |
| Lenovo        | ThinkPad P50 20EQS4RV00     | Notebook    | [370957ec7c](https://bsd-hardware.info/?probe=370957ec7c) | May 08, 2025 |
| HP            | 83E1                        | Desktop     | [6593b9ba45](https://bsd-hardware.info/?probe=6593b9ba45) | May 07, 2025 |
| HP            | 0AA8h                       | Desktop     | [5b054216cd](https://bsd-hardware.info/?probe=5b054216cd) | May 07, 2025 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [56f32392c8](https://bsd-hardware.info/?probe=56f32392c8) | May 05, 2025 |
| Unknown       | Unknown                     | Desktop     | [85eeb318a6](https://bsd-hardware.info/?probe=85eeb318a6) | May 05, 2025 |
| HP            | 8055                        | Desktop     | [9dc9734e98](https://bsd-hardware.info/?probe=9dc9734e98) | May 04, 2025 |
| HP            | 8055                        | Desktop     | [51385d0be6](https://bsd-hardware.info/?probe=51385d0be6) | May 04, 2025 |
| Dell          | 0NW6H5 A00                  | Desktop     | [aaabda123b](https://bsd-hardware.info/?probe=aaabda123b) | May 03, 2025 |
| Intel         | NUC62D 2C                   | Mini pc     | [7557a8bbc1](https://bsd-hardware.info/?probe=7557a8bbc1) | May 02, 2025 |
| MW            | GMLK-2_5G4L                 | Desktop     | [e7af97ff92](https://bsd-hardware.info/?probe=e7af97ff92) | May 02, 2025 |
| Unknown       | Unknown                     | Desktop     | [6f9574cfd4](https://bsd-hardware.info/?probe=6f9574cfd4) | Apr 29, 2025 |
| CncTion       | 1338NP-12 B0                | Desktop     | [7675411a96](https://bsd-hardware.info/?probe=7675411a96) | Apr 29, 2025 |
| HP            | 0AA8h                       | Desktop     | [6a1203b154](https://bsd-hardware.info/?probe=6a1203b154) | Apr 28, 2025 |
| HP            | 8299                        | Desktop     | [aadd48eb34](https://bsd-hardware.info/?probe=aadd48eb34) | Apr 27, 2025 |
| Unknown       | QDNV01                      | Desktop     | [c793424764](https://bsd-hardware.info/?probe=c793424764) | Apr 24, 2025 |
| Unknown       | Unknown                     | Desktop     | [8eb8a4d6aa](https://bsd-hardware.info/?probe=8eb8a4d6aa) | Apr 22, 2025 |
| Lenovo        | 3321 SDK0T76461 WIN 3422... | Desktop     | [896d6ce1f6](https://bsd-hardware.info/?probe=896d6ce1f6) | Apr 16, 2025 |
| Lenovo        | ThinkPad X390 20Q1S30100    | Notebook    | [10f654b932](https://bsd-hardware.info/?probe=10f654b932) | Apr 12, 2025 |
| Sophos        | SG                          | Firewall    | [28cf153259](https://bsd-hardware.info/?probe=28cf153259) | Apr 05, 2025 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [a1fa126927](https://bsd-hardware.info/?probe=a1fa126927) | Apr 03, 2025 |
| HP            | 83EE                        | Desktop     | [5eac034bc7](https://bsd-hardware.info/?probe=5eac034bc7) | Apr 03, 2025 |
| Unknown       | Unknown                     | Desktop     | [c8c4df43b1](https://bsd-hardware.info/?probe=c8c4df43b1) | Apr 02, 2025 |
| Sophos        | SG                          | Firewall    | [bac9d04231](https://bsd-hardware.info/?probe=bac9d04231) | Apr 02, 2025 |
| HP            | 8055                        | Desktop     | [ba941fb4d9](https://bsd-hardware.info/?probe=ba941fb4d9) | Apr 01, 2025 |
| Protectli     | FW4B Ver                    | Desktop     | [438f617d84](https://bsd-hardware.info/?probe=438f617d84) | Mar 30, 2025 |
| Protectli     | FW4C Ver                    | Desktop     | [5cfe707b85](https://bsd-hardware.info/?probe=5cfe707b85) | Mar 30, 2025 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [770b60c2fd](https://bsd-hardware.info/?probe=770b60c2fd) | Mar 29, 2025 |
| Dell          | G16 7630                    | Notebook    | [3b19a7c28a](https://bsd-hardware.info/?probe=3b19a7c28a) | Mar 29, 2025 |
| Unknown       | adnasc01                    | Desktop     | [4a9e7aca14](https://bsd-hardware.info/?probe=4a9e7aca14) | Mar 29, 2025 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [3d0c9119ea](https://bsd-hardware.info/?probe=3d0c9119ea) | Mar 22, 2025 |
| Protectli     | FW4C Ver                    | Desktop     | [af204be1e6](https://bsd-hardware.info/?probe=af204be1e6) | Mar 15, 2025 |
| AZW           | EQ                          | Desktop     | [533d0c8945](https://bsd-hardware.info/?probe=533d0c8945) | Mar 14, 2025 |
| Unknown       | Unknown                     | Desktop     | [4f2f667607](https://bsd-hardware.info/?probe=4f2f667607) | Mar 14, 2025 |
| Lenovo        | 3334 SEK1H03548 IOT 4364... | Mini pc     | [5370bd0076](https://bsd-hardware.info/?probe=5370bd0076) | Mar 08, 2025 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [ce28752002](https://bsd-hardware.info/?probe=ce28752002) | Mar 07, 2025 |
| Winston Ma... | PICO PC V1.2                | Desktop     | [41efa9e187](https://bsd-hardware.info/?probe=41efa9e187) | Feb 28, 2025 |
| Intel         | NUC62D 2C                   | Mini pc     | [cedd3e6e44](https://bsd-hardware.info/?probe=cedd3e6e44) | Feb 27, 2025 |
| ASRock        | H570M-ITX/ac                | Desktop     | [87e8319e25](https://bsd-hardware.info/?probe=87e8319e25) | Feb 26, 2025 |
| HP            | 8103 A01                    | Mini pc     | [a3a5af3678](https://bsd-hardware.info/?probe=a3a5af3678) | Feb 25, 2025 |
| HP            | 8103 A01                    | Mini pc     | [7069631a3a](https://bsd-hardware.info/?probe=7069631a3a) | Feb 25, 2025 |
| Raspberry ... | Raspberry Pi                | Soc         | [9bb8c007ee](https://bsd-hardware.info/?probe=9bb8c007ee) | Feb 24, 2025 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS4... | Notebook    | [8e22203722](https://bsd-hardware.info/?probe=8e22203722) | Feb 24, 2025 |
| Unknown       | DS2309 MotherBoard          | Desktop     | [9f7e10d4b6](https://bsd-hardware.info/?probe=9f7e10d4b6) | Feb 23, 2025 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [7a0b5ab0c5](https://bsd-hardware.info/?probe=7a0b5ab0c5) | Feb 22, 2025 |
| Techvision    | TVI7309X B0                 | Desktop     | [34c42b0d5f](https://bsd-hardware.info/?probe=34c42b0d5f) | Feb 19, 2025 |
| MW            | GMLK-2_5G4L                 | Desktop     | [a7d4cedc20](https://bsd-hardware.info/?probe=a7d4cedc20) | Feb 18, 2025 |
| AZW           | GK55                        | Desktop     | [f9f93d031a](https://bsd-hardware.info/?probe=f9f93d031a) | Feb 15, 2025 |
| Deciso        | NetBoard-A10_Gen.3          | Notebook    | [e9045ae700](https://bsd-hardware.info/?probe=e9045ae700) | Feb 13, 2025 |
| AZW           | GK55                        | Desktop     | [3630266c91](https://bsd-hardware.info/?probe=3630266c91) | Feb 13, 2025 |
| Toshiba       | Satellite L50D-C            | Notebook    | [f8d95e1977](https://bsd-hardware.info/?probe=f8d95e1977) | Feb 12, 2025 |
| Protectli     | VP4630                      | Desktop     | [214404737d](https://bsd-hardware.info/?probe=214404737d) | Feb 10, 2025 |
| Unknown       | Unknown                     | Desktop     | [d1b040ed41](https://bsd-hardware.info/?probe=d1b040ed41) | Feb 08, 2025 |
| Unknown       | Unknown                     | Desktop     | [566a65354f](https://bsd-hardware.info/?probe=566a65354f) | Feb 08, 2025 |
| Protectli     | FW4B                        | Desktop     | [8b48c1b35d](https://bsd-hardware.info/?probe=8b48c1b35d) | Feb 06, 2025 |
| Unknown       | DS2309 MotherBoard          | Desktop     | [739b355479](https://bsd-hardware.info/?probe=739b355479) | Feb 06, 2025 |
| Dell          | 0NRF6V A01                  | Server      | [a071a02fad](https://bsd-hardware.info/?probe=a071a02fad) | Feb 04, 2025 |
| Unknown       | Unknown                     | Desktop     | [385e4d1c3e](https://bsd-hardware.info/?probe=385e4d1c3e) | Feb 03, 2025 |
| Protectli     | FW4B Ver                    | Desktop     | [2c08f58b71](https://bsd-hardware.info/?probe=2c08f58b71) | Feb 03, 2025 |
| Unknown       | Unknown                     | Desktop     | [17982a6be9](https://bsd-hardware.info/?probe=17982a6be9) | Jan 30, 2025 |
| CWWK          | CW-ADLN-6L                  | Desktop     | [26a2de7191](https://bsd-hardware.info/?probe=26a2de7191) | Jan 30, 2025 |
| HP            | 8103 A01                    | Mini pc     | [c58cfcf6c3](https://bsd-hardware.info/?probe=c58cfcf6c3) | Jan 30, 2025 |
| Dell          | 08NPPY A00                  | Desktop     | [1d032b6320](https://bsd-hardware.info/?probe=1d032b6320) | Jan 28, 2025 |
| Dell          | Precision T1650             | Desktop     | [3b9943f0fa](https://bsd-hardware.info/?probe=3b9943f0fa) | Jan 27, 2025 |
| Unknown       | Unknown                     | Desktop     | [b3544d9a76](https://bsd-hardware.info/?probe=b3544d9a76) | Jan 26, 2025 |
| Intel         | PB-X6000                    | Desktop     | [5102f2f6ff](https://bsd-hardware.info/?probe=5102f2f6ff) | Jan 26, 2025 |
| Protectli     | VP4670                      | Desktop     | [436dc612a8](https://bsd-hardware.info/?probe=436dc612a8) | Jan 26, 2025 |
| Dell          | 07KY25 A00                  | Desktop     | [4e8472f65f](https://bsd-hardware.info/?probe=4e8472f65f) | Jan 24, 2025 |
| Dell          | 07KY25 A00                  | Desktop     | [f149a101c7](https://bsd-hardware.info/?probe=f149a101c7) | Jan 24, 2025 |
| Lenovo        | ThinkPad P50 20EQS4RV00     | Notebook    | [f4361f3b6f](https://bsd-hardware.info/?probe=f4361f3b6f) | Jan 23, 2025 |
| Trigkey       | Green G5                    | Desktop     | [8a78158aca](https://bsd-hardware.info/?probe=8a78158aca) | Jan 23, 2025 |
| MSI           | MAG B550M MORTAR            | Desktop     | [ad8de19c61](https://bsd-hardware.info/?probe=ad8de19c61) | Jan 21, 2025 |
| CWWK          | CW-ADLN-6L                  | Desktop     | [1672bc92cd](https://bsd-hardware.info/?probe=1672bc92cd) | Jan 20, 2025 |
| Protectli     | V1410                       | Desktop     | [87e8299d80](https://bsd-hardware.info/?probe=87e8299d80) | Jan 19, 2025 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [d01f2efa37](https://bsd-hardware.info/?probe=d01f2efa37) | Jan 17, 2025 |
| IP3 Tech      | AB3                         | Mini pc     | [421a7f6472](https://bsd-hardware.info/?probe=421a7f6472) | Jan 17, 2025 |
| Intel         | NUC32R                      | Mini pc     | [d4fc8ee462](https://bsd-hardware.info/?probe=d4fc8ee462) | Jan 17, 2025 |
| MSI           | MS-B0A81                    | Desktop     | [d9bbff761d](https://bsd-hardware.info/?probe=d9bbff761d) | Jan 17, 2025 |
| HP            | 8103 A01                    | Mini pc     | [9e25728da8](https://bsd-hardware.info/?probe=9e25728da8) | Jan 15, 2025 |
| CWWK          | CW-ADLN-6L                  | Desktop     | [0d0b40294a](https://bsd-hardware.info/?probe=0d0b40294a) | Jan 15, 2025 |
| Dell          | 0P3GYK A00                  | Mini pc     | [4a49e111a1](https://bsd-hardware.info/?probe=4a49e111a1) | Jan 15, 2025 |
| AZW           | EQ                          | Desktop     | [03a9b46b8f](https://bsd-hardware.info/?probe=03a9b46b8f) | Jan 14, 2025 |
| Unknown       | Unknown                     | Desktop     | [85b47857df](https://bsd-hardware.info/?probe=85b47857df) | Jan 11, 2025 |
| Techvision    | TVI7309X B0                 | Desktop     | [e54714fe40](https://bsd-hardware.info/?probe=e54714fe40) | Jan 11, 2025 |
| Techvision    | TVI7309X B0                 | Desktop     | [4bca5d6829](https://bsd-hardware.info/?probe=4bca5d6829) | Jan 11, 2025 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [3a6b25c1a5](https://bsd-hardware.info/?probe=3a6b25c1a5) | Jan 10, 2025 |
| Dell          | 0P3GYK A00                  | Mini pc     | [d4124af502](https://bsd-hardware.info/?probe=d4124af502) | Jan 07, 2025 |
| Dell          | Latitude E5520              | Notebook    | [e8415a5758](https://bsd-hardware.info/?probe=e8415a5758) | Jan 05, 2025 |
| ASRock        | H570M-ITX/ac                | Desktop     | [5b40284fbe](https://bsd-hardware.info/?probe=5b40284fbe) | Jan 04, 2025 |
| Dell          | Inspiron 14 7440 2-in-1     | Convertible | [1dca2d5f7d](https://bsd-hardware.info/?probe=1dca2d5f7d) | Jan 01, 2025 |
| Protectli     | VP4670                      | Desktop     | [1649d4be0f](https://bsd-hardware.info/?probe=1649d4be0f) | Dec 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [a92bf0ef02](https://bsd-hardware.info/?probe=a92bf0ef02) | Dec 27, 2024 |
| ASRock        | H570M-ITX/ac                | Desktop     | [eb9e3863e0](https://bsd-hardware.info/?probe=eb9e3863e0) | Dec 22, 2024 |
| Unknown       | Unknown                     | Desktop     | [02119a1b45](https://bsd-hardware.info/?probe=02119a1b45) | Dec 22, 2024 |
| Protectli     | VP4670                      | Desktop     | [8d641a410f](https://bsd-hardware.info/?probe=8d641a410f) | Dec 16, 2024 |
| WeiBu         | ADL-N Prod                  | Desktop     | [de66071f16](https://bsd-hardware.info/?probe=de66071f16) | Dec 12, 2024 |
| Unknown       | Unknown                     | Desktop     | [fa422c4eec](https://bsd-hardware.info/?probe=fa422c4eec) | Dec 11, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | Desktop     | [1b2c50f225](https://bsd-hardware.info/?probe=1b2c50f225) | Dec 08, 2024 |
| ASUSTek       | Q87I-PLUS                   | Desktop     | [9d857bfe96](https://bsd-hardware.info/?probe=9d857bfe96) | Dec 07, 2024 |
| Protectli     | V1410                       | Desktop     | [78a29a9a78](https://bsd-hardware.info/?probe=78a29a9a78) | Dec 07, 2024 |
| Lenovo        | 1052 NOK                    | Desktop     | [44cfb1316c](https://bsd-hardware.info/?probe=44cfb1316c) | Dec 06, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [b659f5f797](https://bsd-hardware.info/?probe=b659f5f797) | Dec 03, 2024 |
| Protectli     | V1410                       | Desktop     | [de051ba319](https://bsd-hardware.info/?probe=de051ba319) | Dec 03, 2024 |
| Unknown       | Unknown                     | Desktop     | [6348954925](https://bsd-hardware.info/?probe=6348954925) | Dec 02, 2024 |
| Sophos        | XG                          | Firewall    | [8baa06b96b](https://bsd-hardware.info/?probe=8baa06b96b) | Dec 01, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [648268f0e3](https://bsd-hardware.info/?probe=648268f0e3) | Dec 01, 2024 |
| Gigabyte      | Z490 AORUS MASTER           | Desktop     | [5a7a5ce019](https://bsd-hardware.info/?probe=5a7a5ce019) | Nov 30, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [a25be40b42](https://bsd-hardware.info/?probe=a25be40b42) | Nov 26, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [c472067efe](https://bsd-hardware.info/?probe=c472067efe) | Nov 25, 2024 |
| Sophos        | XG                          | Firewall    | [1dcbc78986](https://bsd-hardware.info/?probe=1dcbc78986) | Nov 24, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [1abb405f84](https://bsd-hardware.info/?probe=1abb405f84) | Nov 24, 2024 |
| Gigabyte      | Z490 AORUS MASTER           | Desktop     | [acfb1a77bf](https://bsd-hardware.info/?probe=acfb1a77bf) | Nov 24, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [c4ffe49c04](https://bsd-hardware.info/?probe=c4ffe49c04) | Nov 23, 2024 |
| Dell          | 0H0P0M A00                  | Desktop     | [67846a1472](https://bsd-hardware.info/?probe=67846a1472) | Nov 23, 2024 |
| Dell          | 0H0P0M A00                  | Desktop     | [5e1cccc11c](https://bsd-hardware.info/?probe=5e1cccc11c) | Nov 17, 2024 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [b16a33c476](https://bsd-hardware.info/?probe=b16a33c476) | Nov 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [9411c1202b](https://bsd-hardware.info/?probe=9411c1202b) | Nov 16, 2024 |
| Dell          | 0XCR8D A01                  | Desktop     | [2ab0785e7a](https://bsd-hardware.info/?probe=2ab0785e7a) | Nov 14, 2024 |
| Shenzhen M... | AHWSA                       | Desktop     | [d296c3e157](https://bsd-hardware.info/?probe=d296c3e157) | Nov 13, 2024 |
| Unknown       | AD18                        | Desktop     | [c134167984](https://bsd-hardware.info/?probe=c134167984) | Nov 12, 2024 |
| HP            | 3048h                       | Desktop     | [9a81b371b5](https://bsd-hardware.info/?probe=9a81b371b5) | Nov 12, 2024 |
| HP            | 83E2                        | Desktop     | [e5c43ed134](https://bsd-hardware.info/?probe=e5c43ed134) | Nov 11, 2024 |
| HP            | 870C                        | Desktop     | [d18863b8e4](https://bsd-hardware.info/?probe=d18863b8e4) | Nov 10, 2024 |
| Dell          | 0P3GYK A00                  | Mini pc     | [559edaf2ae](https://bsd-hardware.info/?probe=559edaf2ae) | Oct 31, 2024 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [bfccac9212](https://bsd-hardware.info/?probe=bfccac9212) | Oct 30, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [1841d9a2d3](https://bsd-hardware.info/?probe=1841d9a2d3) | Oct 29, 2024 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [0d8d529514](https://bsd-hardware.info/?probe=0d8d529514) | Oct 29, 2024 |
| Dell          | 096JG8 A01                  | Desktop     | [aad472393b](https://bsd-hardware.info/?probe=aad472393b) | Oct 27, 2024 |
| Unknown       | Unknown                     | Desktop     | [1082ecf333](https://bsd-hardware.info/?probe=1082ecf333) | Oct 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [57f630266f](https://bsd-hardware.info/?probe=57f630266f) | Oct 25, 2024 |
| OEM           | PB-1900-A                   | Desktop     | [fac430a8c9](https://bsd-hardware.info/?probe=fac430a8c9) | Oct 25, 2024 |
| CheckPoint    | T-120-00                    | Desktop     | [62b73d8e40](https://bsd-hardware.info/?probe=62b73d8e40) | Oct 21, 2024 |
| Supermicro    | X9SBAA                      | Server      | [ac201903f8](https://bsd-hardware.info/?probe=ac201903f8) | Oct 19, 2024 |
| Supermicro    | X9SBAA                      | Server      | [91fdb7ce3a](https://bsd-hardware.info/?probe=91fdb7ce3a) | Oct 18, 2024 |
| HP            | 81C6 MVB 0C                 | Server      | [6e680b95d7](https://bsd-hardware.info/?probe=6e680b95d7) | Oct 17, 2024 |
| HP            | ProLiant DL160 Gen8         | Server      | [6cb4069800](https://bsd-hardware.info/?probe=6cb4069800) | Oct 15, 2024 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [223ca94998](https://bsd-hardware.info/?probe=223ca94998) | Oct 15, 2024 |
| Intel         | D34010WYK H14771-302        | Desktop     | [67245b0423](https://bsd-hardware.info/?probe=67245b0423) | Oct 15, 2024 |
| Lenovo        | ThinkPad T490 20N2S0QE00    | Notebook    | [4ea2230818](https://bsd-hardware.info/?probe=4ea2230818) | Oct 15, 2024 |
| Lenovo        | ThinkPad T490 20N2S0QE00    | Notebook    | [b7f189a238](https://bsd-hardware.info/?probe=b7f189a238) | Oct 14, 2024 |
| HP            | 3048h                       | Desktop     | [9a6218dc9f](https://bsd-hardware.info/?probe=9a6218dc9f) | Oct 13, 2024 |
| ASRock        | H570M-ITX/ac                | Desktop     | [4e0d157a76](https://bsd-hardware.info/?probe=4e0d157a76) | Oct 09, 2024 |
| ASRock        | H570M-ITX/ac                | Desktop     | [e54bd4924f](https://bsd-hardware.info/?probe=e54bd4924f) | Oct 09, 2024 |
| Dell          | 00V62H A00                  | Desktop     | [87e3fa093a](https://bsd-hardware.info/?probe=87e3fa093a) | Oct 09, 2024 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [f009e46a16](https://bsd-hardware.info/?probe=f009e46a16) | Oct 09, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [156ab405d2](https://bsd-hardware.info/?probe=156ab405d2) | Oct 09, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [6ab6c7929b](https://bsd-hardware.info/?probe=6ab6c7929b) | Oct 06, 2024 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [7b97e06782](https://bsd-hardware.info/?probe=7b97e06782) | Oct 04, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | Notebook    | [869d37ac5e](https://bsd-hardware.info/?probe=869d37ac5e) | Oct 04, 2024 |
| BESSTAR Te... | GB7                         | Mini pc     | [afbc442edb](https://bsd-hardware.info/?probe=afbc442edb) | Oct 03, 2024 |
| BESSTAR Te... | GB7                         | Mini pc     | [17848fd98f](https://bsd-hardware.info/?probe=17848fd98f) | Oct 03, 2024 |
| Intel         | DH67BL AAG10189-206         | Desktop     | [45d47552af](https://bsd-hardware.info/?probe=45d47552af) | Oct 02, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [45a12f9a8b](https://bsd-hardware.info/?probe=45a12f9a8b) | Oct 01, 2024 |
| Sophos        | SG                          | Firewall    | [66fdc7a753](https://bsd-hardware.info/?probe=66fdc7a753) | Sep 30, 2024 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [b50eb75680](https://bsd-hardware.info/?probe=b50eb75680) | Sep 28, 2024 |
| HP            | 870C                        | Desktop     | [a0a04f0fa9](https://bsd-hardware.info/?probe=a0a04f0fa9) | Sep 27, 2024 |
| Unknown       | Unknown                     | Desktop     | [9be3134b8f](https://bsd-hardware.info/?probe=9be3134b8f) | Sep 26, 2024 |
| AZW           | EQ                          | Desktop     | [5cc403e6aa](https://bsd-hardware.info/?probe=5cc403e6aa) | Sep 24, 2024 |
| Unknown       | Unknown                     | Desktop     | [9fcfe381ae](https://bsd-hardware.info/?probe=9fcfe381ae) | Sep 24, 2024 |
| Intel         | PB-X6000                    | Desktop     | [b0a7e628cf](https://bsd-hardware.info/?probe=b0a7e628cf) | Sep 23, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [deccb2f9c3](https://bsd-hardware.info/?probe=deccb2f9c3) | Sep 23, 2024 |
| Citrix        | CB-1100                     | Desktop     | [304a4f6d5f](https://bsd-hardware.info/?probe=304a4f6d5f) | Sep 23, 2024 |
| Sophos        | XG                          | Firewall    | [f0f76c35c3](https://bsd-hardware.info/?probe=f0f76c35c3) | Sep 21, 2024 |
| Protectli     | VP4630                      | Desktop     | [f599050faf](https://bsd-hardware.info/?probe=f599050faf) | Sep 18, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [9aea4f42bc](https://bsd-hardware.info/?probe=9aea4f42bc) | Sep 18, 2024 |
| HP            | 870C                        | Desktop     | [6a8b48c698](https://bsd-hardware.info/?probe=6a8b48c698) | Sep 17, 2024 |
| Citrix        | CB-1100                     | Desktop     | [6e070920d0](https://bsd-hardware.info/?probe=6e070920d0) | Sep 15, 2024 |
| Unknown       | Unknown                     | Desktop     | [6575dfb8e4](https://bsd-hardware.info/?probe=6575dfb8e4) | Sep 15, 2024 |
| Gigabyte      | G41MT-ES2L                  | Desktop     | [8afe8ddad6](https://bsd-hardware.info/?probe=8afe8ddad6) | Sep 15, 2024 |
| HP            | 8103 A01                    | Mini pc     | [c08435c348](https://bsd-hardware.info/?probe=c08435c348) | Sep 13, 2024 |
| HP            | 8103 A01                    | Mini pc     | [54f0ddfe23](https://bsd-hardware.info/?probe=54f0ddfe23) | Sep 12, 2024 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [0a5ecbce04](https://bsd-hardware.info/?probe=0a5ecbce04) | Sep 12, 2024 |
| Intel         | NUC8v5PNB K59997-403        | Mini pc     | [93d6a9c9a3](https://bsd-hardware.info/?probe=93d6a9c9a3) | Sep 10, 2024 |
| Gigabyte      | G41MT-ES2L                  | Desktop     | [8016457889](https://bsd-hardware.info/?probe=8016457889) | Sep 10, 2024 |
| Unknown       | Unknown                     | Desktop     | [f19fafe503](https://bsd-hardware.info/?probe=f19fafe503) | Sep 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [170e17cd46](https://bsd-hardware.info/?probe=170e17cd46) | Sep 07, 2024 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [c1fb0928df](https://bsd-hardware.info/?probe=c1fb0928df) | Sep 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [2399243ff8](https://bsd-hardware.info/?probe=2399243ff8) | Sep 06, 2024 |
| OEM           | PB-1900-A                   | Desktop     | [6334dac48a](https://bsd-hardware.info/?probe=6334dac48a) | Sep 06, 2024 |
| Trigkey       | Green G5                    | Desktop     | [fcaa5a268e](https://bsd-hardware.info/?probe=fcaa5a268e) | Sep 05, 2024 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [b5d95279a6](https://bsd-hardware.info/?probe=b5d95279a6) | Sep 03, 2024 |
| Unknown       | Unknown                     | Desktop     | [13fa129348](https://bsd-hardware.info/?probe=13fa129348) | Aug 31, 2024 |
| Unknown       | Unknown                     | Desktop     | [e31fb6e0e8](https://bsd-hardware.info/?probe=e31fb6e0e8) | Aug 31, 2024 |
| Unknown       | Unknown                     | Desktop     | [a4cdaf25d6](https://bsd-hardware.info/?probe=a4cdaf25d6) | Aug 30, 2024 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [ce9b1b23e1](https://bsd-hardware.info/?probe=ce9b1b23e1) | Aug 29, 2024 |
| Trigkey       | Green G5                    | Desktop     | [13c389b9df](https://bsd-hardware.info/?probe=13c389b9df) | Aug 29, 2024 |
| Protectli     | FW4B                        | Desktop     | [92d79ae389](https://bsd-hardware.info/?probe=92d79ae389) | Aug 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [104269f26b](https://bsd-hardware.info/?probe=104269f26b) | Aug 25, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [91106574a4](https://bsd-hardware.info/?probe=91106574a4) | Aug 24, 2024 |
| Dell          | 0NC2VH A01                  | Desktop     | [cba2c1f636](https://bsd-hardware.info/?probe=cba2c1f636) | Aug 22, 2024 |
| CheckPoint    | T-120-00                    | Desktop     | [25c29c6dcc](https://bsd-hardware.info/?probe=25c29c6dcc) | Aug 21, 2024 |
| Unknown       | QDNV01                      | Desktop     | [2b68f6c1ec](https://bsd-hardware.info/?probe=2b68f6c1ec) | Aug 21, 2024 |
| HP            | 870C                        | Desktop     | [2a69ceab02](https://bsd-hardware.info/?probe=2a69ceab02) | Aug 19, 2024 |
| Unknown       | Unknown                     | Desktop     | [c1a44667bd](https://bsd-hardware.info/?probe=c1a44667bd) | Aug 14, 2024 |
| Unknown       | Unknown                     | Desktop     | [d69a19bb41](https://bsd-hardware.info/?probe=d69a19bb41) | Aug 12, 2024 |
| Unknown       | Unknown                     | Desktop     | [9a967b67dd](https://bsd-hardware.info/?probe=9a967b67dd) | Aug 08, 2024 |
| OEM           | PB-1900-A                   | Desktop     | [e45310d73f](https://bsd-hardware.info/?probe=e45310d73f) | Aug 04, 2024 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [43ccbf96cb](https://bsd-hardware.info/?probe=43ccbf96cb) | Aug 04, 2024 |
| Unknown       | Unknown                     | Desktop     | [edece0ced6](https://bsd-hardware.info/?probe=edece0ced6) | Aug 03, 2024 |
| HP            | 8103 A01                    | Mini pc     | [7dc83e394c](https://bsd-hardware.info/?probe=7dc83e394c) | Aug 02, 2024 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [7432c6d49d](https://bsd-hardware.info/?probe=7432c6d49d) | Jul 31, 2024 |
| HP            | 870C                        | Desktop     | [8f559ae44d](https://bsd-hardware.info/?probe=8f559ae44d) | Jul 31, 2024 |
| Intel         | CM11EBI38W K93946-306       | Mini pc     | [65532a4b31](https://bsd-hardware.info/?probe=65532a4b31) | Jul 31, 2024 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [14634a95c5](https://bsd-hardware.info/?probe=14634a95c5) | Jul 29, 2024 |
| HP            | 870C                        | Desktop     | [00c53213af](https://bsd-hardware.info/?probe=00c53213af) | Jul 27, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [1cc0e919ed](https://bsd-hardware.info/?probe=1cc0e919ed) | Jul 26, 2024 |
| Apple         | Mac-F221BEC8                | Desktop     | [dd834b1229](https://bsd-hardware.info/?probe=dd834b1229) | Jul 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [7054a512d1](https://bsd-hardware.info/?probe=7054a512d1) | Jul 23, 2024 |
| Unknown       | Unknown                     | Desktop     | [90daceb808](https://bsd-hardware.info/?probe=90daceb808) | Jul 22, 2024 |
| Unknown       | Unknown                     | Desktop     | [ff3ada3808](https://bsd-hardware.info/?probe=ff3ada3808) | Jul 22, 2024 |
| Sophos        | XG                          | Firewall    | [0ae31bce76](https://bsd-hardware.info/?probe=0ae31bce76) | Jul 18, 2024 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [3ae423a460](https://bsd-hardware.info/?probe=3ae423a460) | Jul 14, 2024 |
| Unknown       | QGLK03                      | Desktop     | [2c06f0a474](https://bsd-hardware.info/?probe=2c06f0a474) | Jul 13, 2024 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [eb82e44d2d](https://bsd-hardware.info/?probe=eb82e44d2d) | Jul 10, 2024 |
| Unknown       | Unknown                     | Desktop     | [b9e0599645](https://bsd-hardware.info/?probe=b9e0599645) | Jul 10, 2024 |
| ASUSTek       | U50Vg                       | Notebook    | [02c8f9cdf5](https://bsd-hardware.info/?probe=02c8f9cdf5) | Jul 06, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [58313a536e](https://bsd-hardware.info/?probe=58313a536e) | Jul 04, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [2676698df8](https://bsd-hardware.info/?probe=2676698df8) | Jul 03, 2024 |
| Protectli     | VP4650                      | Desktop     | [a9edd6c51a](https://bsd-hardware.info/?probe=a9edd6c51a) | Jul 03, 2024 |
| HP            | 870C                        | Desktop     | [655f793071](https://bsd-hardware.info/?probe=655f793071) | Jul 02, 2024 |
| HP            | 870C                        | Desktop     | [1cd554e5e9](https://bsd-hardware.info/?probe=1cd554e5e9) | Jul 01, 2024 |
| HP            | 870C                        | Desktop     | [2caaf86446](https://bsd-hardware.info/?probe=2caaf86446) | Jun 30, 2024 |
| Unknown       | Unknown                     | Desktop     | [d8e556e598](https://bsd-hardware.info/?probe=d8e556e598) | Jun 30, 2024 |
| Unknown       | Unknown                     | Desktop     | [82db566380](https://bsd-hardware.info/?probe=82db566380) | Jun 30, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [0a8aa195eb](https://bsd-hardware.info/?probe=0a8aa195eb) | Jun 26, 2024 |
| HP            | 870C                        | Desktop     | [b844ce2068](https://bsd-hardware.info/?probe=b844ce2068) | Jun 26, 2024 |
| Dell          | 096JG8 A01                  | Desktop     | [6cba39a47b](https://bsd-hardware.info/?probe=6cba39a47b) | Jun 25, 2024 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [fb21431b06](https://bsd-hardware.info/?probe=fb21431b06) | Jun 24, 2024 |
| Dell          | 096JG8 A01                  | Desktop     | [24c2c59c3a](https://bsd-hardware.info/?probe=24c2c59c3a) | Jun 23, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [9daa772291](https://bsd-hardware.info/?probe=9daa772291) | Jun 21, 2024 |
| Protectli     | VP2410 10                   | Desktop     | [3ffa3a7b97](https://bsd-hardware.info/?probe=3ffa3a7b97) | Jun 20, 2024 |
| Dell          | 0PC5F7 A00                  | Desktop     | [5c88193dc4](https://bsd-hardware.info/?probe=5c88193dc4) | Jun 16, 2024 |
| HP            | 83EE                        | Desktop     | [c5a71d4e06](https://bsd-hardware.info/?probe=c5a71d4e06) | Jun 15, 2024 |
| Supermicro    | X10SDV-TP8F                 | Server      | [030b0b67f0](https://bsd-hardware.info/?probe=030b0b67f0) | Jun 15, 2024 |
| HP            | 82A2                        | Desktop     | [d4a521d5f7](https://bsd-hardware.info/?probe=d4a521d5f7) | Jun 13, 2024 |
| ASUSTek       | Z97-A                       | Desktop     | [f2787a24ba](https://bsd-hardware.info/?probe=f2787a24ba) | Jun 11, 2024 |
| OEM           | PB-1900-A                   | Desktop     | [af1a4c2802](https://bsd-hardware.info/?probe=af1a4c2802) | Jun 10, 2024 |
| Unknown       | Unknown                     | Desktop     | [0f3d5ece0c](https://bsd-hardware.info/?probe=0f3d5ece0c) | Jun 10, 2024 |
| Sophos        | XG                          | Firewall    | [ebef777cbb](https://bsd-hardware.info/?probe=ebef777cbb) | Jun 04, 2024 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [51df4f57c5](https://bsd-hardware.info/?probe=51df4f57c5) | Jun 02, 2024 |
| Unknown       | Unknown                     | Desktop     | [94f269663c](https://bsd-hardware.info/?probe=94f269663c) | Jun 01, 2024 |
| Intel         | DENLOW_WS                   | Desktop     | [27f73c0ae9](https://bsd-hardware.info/?probe=27f73c0ae9) | May 31, 2024 |
| Unknown       | QDNV01                      | Desktop     | [5d8b4c676b](https://bsd-hardware.info/?probe=5d8b4c676b) | May 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [c20215f991](https://bsd-hardware.info/?probe=c20215f991) | May 29, 2024 |
| HP            | 8103 A01                    | Mini pc     | [2381b0f0b3](https://bsd-hardware.info/?probe=2381b0f0b3) | May 29, 2024 |
| Gigabyte      | Z790 EAGLE AX               | Desktop     | [65d52d2137](https://bsd-hardware.info/?probe=65d52d2137) | May 28, 2024 |
| Unknown       | Unknown                     | Desktop     | [d0919f78df](https://bsd-hardware.info/?probe=d0919f78df) | May 27, 2024 |
| Gigabyte      | Z790 EAGLE AX               | Desktop     | [354c2b5195](https://bsd-hardware.info/?probe=354c2b5195) | May 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [c74d50d97d](https://bsd-hardware.info/?probe=c74d50d97d) | May 25, 2024 |
| IceWhale T... | ZimaBoard 432 ZMB           | Desktop     | [72d4c7046e](https://bsd-hardware.info/?probe=72d4c7046e) | May 23, 2024 |
| Shenzhen M... | F7BSH                       | Mini pc     | [d915452fc5](https://bsd-hardware.info/?probe=d915452fc5) | May 20, 2024 |
| HP            | 8103 A01                    | Mini pc     | [5da5b7c525](https://bsd-hardware.info/?probe=5da5b7c525) | May 19, 2024 |
| Gigabyte      | Z790 EAGLE AX               | Desktop     | [011ed158e0](https://bsd-hardware.info/?probe=011ed158e0) | May 18, 2024 |
| Gigabyte      | Z790 EAGLE AX               | Desktop     | [d96abdd063](https://bsd-hardware.info/?probe=d96abdd063) | May 17, 2024 |
| HP            | 83E1                        | Desktop     | [2227565c4c](https://bsd-hardware.info/?probe=2227565c4c) | May 15, 2024 |
| Intel         | QHSW02                      | Desktop     | [945cf47cc6](https://bsd-hardware.info/?probe=945cf47cc6) | May 14, 2024 |
| AMD           | Inagua CRB                  | Desktop     | [d5ba9b512c](https://bsd-hardware.info/?probe=d5ba9b512c) | May 13, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [e82997fc22](https://bsd-hardware.info/?probe=e82997fc22) | May 13, 2024 |
| HP            | 83EE                        | Desktop     | [cb1389a074](https://bsd-hardware.info/?probe=cb1389a074) | May 12, 2024 |
| Intel         | NUC62D 2C                   | Mini pc     | [3c4d498679](https://bsd-hardware.info/?probe=3c4d498679) | May 11, 2024 |
| Unknown       | QGLK03                      | Desktop     | [3a6ac054e6](https://bsd-hardware.info/?probe=3a6ac054e6) | May 09, 2024 |
| HP            | 83EE                        | Desktop     | [c2a0b11bfa](https://bsd-hardware.info/?probe=c2a0b11bfa) | May 08, 2024 |
| AZW           | EQ                          | Desktop     | [edb4b64548](https://bsd-hardware.info/?probe=edb4b64548) | May 06, 2024 |
| Intel         | MAHOBAY                     | Desktop     | [dfe3417cfb](https://bsd-hardware.info/?probe=dfe3417cfb) | May 05, 2024 |
| Unknown       | Unknown                     | Desktop     | [c77ff29728](https://bsd-hardware.info/?probe=c77ff29728) | May 04, 2024 |
| Intel         | PB-X6000                    | Desktop     | [23a7529eaa](https://bsd-hardware.info/?probe=23a7529eaa) | May 04, 2024 |
| Unknown       | Unknown                     | Desktop     | [da95fe1264](https://bsd-hardware.info/?probe=da95fe1264) | May 02, 2024 |
| Dell          | 0PC5F7 A00                  | Desktop     | [25be1b099a](https://bsd-hardware.info/?probe=25be1b099a) | May 02, 2024 |
| Dell          | 0PC5F7 A00                  | Desktop     | [217f8e63db](https://bsd-hardware.info/?probe=217f8e63db) | May 01, 2024 |
| Unknown       | Unknown                     | Desktop     | [1c2459184f](https://bsd-hardware.info/?probe=1c2459184f) | Apr 28, 2024 |
| Protectli     | VP4630                      | Desktop     | [a128743268](https://bsd-hardware.info/?probe=a128743268) | Apr 25, 2024 |
| Dell          | 0DNMV1 A01                  | Desktop     | [97161dac8a](https://bsd-hardware.info/?probe=97161dac8a) | Apr 24, 2024 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [2000d6447a](https://bsd-hardware.info/?probe=2000d6447a) | Apr 23, 2024 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [3e1def845f](https://bsd-hardware.info/?probe=3e1def845f) | Apr 23, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [58a64ecc64](https://bsd-hardware.info/?probe=58a64ecc64) | Apr 23, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [d9b4db06cf](https://bsd-hardware.info/?probe=d9b4db06cf) | Apr 21, 2024 |
| Dell          | 0XCR8D A01                  | Desktop     | [716181ac45](https://bsd-hardware.info/?probe=716181ac45) | Apr 21, 2024 |
| Gigabyte      | B460 AORUS PRO AC           | Desktop     | [fe0730cde5](https://bsd-hardware.info/?probe=fe0730cde5) | Apr 20, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [572876d341](https://bsd-hardware.info/?probe=572876d341) | Apr 20, 2024 |
| AZW           | EQ                          | Desktop     | [f822d4127d](https://bsd-hardware.info/?probe=f822d4127d) | Apr 20, 2024 |
| HP            | 8103 A01                    | Mini pc     | [a6a185dfad](https://bsd-hardware.info/?probe=a6a185dfad) | Apr 19, 2024 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [dd5c8c3088](https://bsd-hardware.info/?probe=dd5c8c3088) | Apr 17, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [7e1d43786b](https://bsd-hardware.info/?probe=7e1d43786b) | Apr 15, 2024 |
| Intel         | MAHOBAY                     | Desktop     | [9202be9d8d](https://bsd-hardware.info/?probe=9202be9d8d) | Apr 12, 2024 |
| Protectli     | VP4650                      | Desktop     | [95ce732272](https://bsd-hardware.info/?probe=95ce732272) | Apr 12, 2024 |
| Unknown       | Unknown                     | Desktop     | [bafb4c3fd6](https://bsd-hardware.info/?probe=bafb4c3fd6) | Apr 06, 2024 |
| Intel         | SKYBAY                      | Desktop     | [7d6e63d688](https://bsd-hardware.info/?probe=7d6e63d688) | Apr 02, 2024 |
| Lenovo        | SHARKBAY 0C48431 WIN        | Desktop     | [893075f24f](https://bsd-hardware.info/?probe=893075f24f) | Apr 02, 2024 |
| HP            | 83E2                        | Desktop     | [c1765c598f](https://bsd-hardware.info/?probe=c1765c598f) | Apr 02, 2024 |
| Dell          | 0XCR8D A01                  | Desktop     | [39679bc463](https://bsd-hardware.info/?probe=39679bc463) | Apr 01, 2024 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [f89dd6d1c9](https://bsd-hardware.info/?probe=f89dd6d1c9) | Mar 31, 2024 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [28f484158e](https://bsd-hardware.info/?probe=28f484158e) | Mar 31, 2024 |
| Unknown       | Unknown                     | Desktop     | [673473a1a0](https://bsd-hardware.info/?probe=673473a1a0) | Mar 27, 2024 |
| MSI           | MS-B0A81                    | Desktop     | [17e87ae023](https://bsd-hardware.info/?probe=17e87ae023) | Mar 26, 2024 |
| Intel         | SKYBAY                      | Desktop     | [8aaca978dc](https://bsd-hardware.info/?probe=8aaca978dc) | Mar 26, 2024 |
| HP            | 870C                        | Desktop     | [736b0fa24b](https://bsd-hardware.info/?probe=736b0fa24b) | Mar 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [5b7761ce38](https://bsd-hardware.info/?probe=5b7761ce38) | Mar 23, 2024 |
| OEM           | PB-1900-A                   | Desktop     | [7172e173cb](https://bsd-hardware.info/?probe=7172e173cb) | Mar 19, 2024 |
| Sophos        | XG                          | Firewall    | [c0c41acc9a](https://bsd-hardware.info/?probe=c0c41acc9a) | Mar 18, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [2ae7a73498](https://bsd-hardware.info/?probe=2ae7a73498) | Mar 15, 2024 |
| Unknown       | Unknown                     | Desktop     | [5e613125ca](https://bsd-hardware.info/?probe=5e613125ca) | Mar 10, 2024 |
| Unknown       | Unknown                     | Desktop     | [3dadeb1ccc](https://bsd-hardware.info/?probe=3dadeb1ccc) | Mar 08, 2024 |
| Intel         | QHSW02                      | Desktop     | [54d2883b0f](https://bsd-hardware.info/?probe=54d2883b0f) | Mar 08, 2024 |
| Intel         | S1200BTL E98681-352         | Server      | [3d02743f6e](https://bsd-hardware.info/?probe=3d02743f6e) | Mar 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [cf72715739](https://bsd-hardware.info/?probe=cf72715739) | Mar 07, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [e8ed936537](https://bsd-hardware.info/?probe=e8ed936537) | Mar 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [ed75f5f715](https://bsd-hardware.info/?probe=ed75f5f715) | Mar 05, 2024 |
| Dell          | 0XCR8D A02                  | Desktop     | [8919d9eb09](https://bsd-hardware.info/?probe=8919d9eb09) | Mar 05, 2024 |
| Dell          | 07F37C A00                  | Desktop     | [53928dbf53](https://bsd-hardware.info/?probe=53928dbf53) | Mar 03, 2024 |
| MSI           | MS-B0A81                    | Desktop     | [2f6a08c240](https://bsd-hardware.info/?probe=2f6a08c240) | Mar 03, 2024 |
| Unknown       | Unknown                     | Desktop     | [83a5d4bd8b](https://bsd-hardware.info/?probe=83a5d4bd8b) | Mar 01, 2024 |
| HP            | 83EE                        | Desktop     | [0c83be53f1](https://bsd-hardware.info/?probe=0c83be53f1) | Feb 27, 2024 |
| Sophos        | XG                          | Firewall    | [9616774ad2](https://bsd-hardware.info/?probe=9616774ad2) | Feb 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [dc82774d4b](https://bsd-hardware.info/?probe=dc82774d4b) | Feb 21, 2024 |
| Unknown       | Unknown                     | Desktop     | [c64774303d](https://bsd-hardware.info/?probe=c64774303d) | Feb 20, 2024 |
| Unknown       | Unknown                     | Desktop     | [e5e747ec86](https://bsd-hardware.info/?probe=e5e747ec86) | Feb 16, 2024 |
| Unknown       | Unknown                     | Desktop     | [7dc7c39f38](https://bsd-hardware.info/?probe=7dc7c39f38) | Feb 15, 2024 |
| Google        | Ultima                      | Notebook    | [732adeb5e4](https://bsd-hardware.info/?probe=732adeb5e4) | Feb 15, 2024 |
| Dell          | 0PC10G A00                  | Mini pc     | [836dac7d2c](https://bsd-hardware.info/?probe=836dac7d2c) | Feb 13, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [9376dd68e3](https://bsd-hardware.info/?probe=9376dd68e3) | Feb 12, 2024 |
| Unknown       | Unknown                     | Desktop     | [7b626b5a2c](https://bsd-hardware.info/?probe=7b626b5a2c) | Feb 07, 2024 |
| HP            | 83EE                        | Desktop     | [3fdb0e4625](https://bsd-hardware.info/?probe=3fdb0e4625) | Feb 05, 2024 |
| HP            | 83EE                        | Desktop     | [92258e181d](https://bsd-hardware.info/?probe=92258e181d) | Feb 05, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [93b7fdf97e](https://bsd-hardware.info/?probe=93b7fdf97e) | Feb 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [6a78256797](https://bsd-hardware.info/?probe=6a78256797) | Feb 04, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [1d2c689952](https://bsd-hardware.info/?probe=1d2c689952) | Jan 30, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [8c7a8c5a07](https://bsd-hardware.info/?probe=8c7a8c5a07) | Jan 28, 2024 |
| Unknown       | Unknown                     | Desktop     | [5eb0f3d517](https://bsd-hardware.info/?probe=5eb0f3d517) | Jan 20, 2024 |
| Supermicro    | A2SDi-H-TF                  | Server      | [e8c04a2779](https://bsd-hardware.info/?probe=e8c04a2779) | Jan 14, 2024 |
| Sophos        | SG                          | Firewall    | [aa8ce9bcaa](https://bsd-hardware.info/?probe=aa8ce9bcaa) | Jan 10, 2024 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [4d9e3faf1d](https://bsd-hardware.info/?probe=4d9e3faf1d) | Jan 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [3ae4489483](https://bsd-hardware.info/?probe=3ae4489483) | Jan 05, 2024 |
| HP            | 83EE                        | Desktop     | [cbfaae0ca7](https://bsd-hardware.info/?probe=cbfaae0ca7) | Jan 05, 2024 |
| Unknown       | Unknown                     | Desktop     | [0d4b103495](https://bsd-hardware.info/?probe=0d4b103495) | Jan 04, 2024 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [52345f2706](https://bsd-hardware.info/?probe=52345f2706) | Jan 02, 2024 |
| Hardkernel    | ODROID-H2                   | Desktop     | [959e70a37e](https://bsd-hardware.info/?probe=959e70a37e) | Jan 02, 2024 |
| Unknown       | Unknown                     | Desktop     | [5354734c83](https://bsd-hardware.info/?probe=5354734c83) | Dec 29, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [bc5f165c4a](https://bsd-hardware.info/?probe=bc5f165c4a) | Dec 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [03f7101d55](https://bsd-hardware.info/?probe=03f7101d55) | Dec 25, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [b99ed60ab6](https://bsd-hardware.info/?probe=b99ed60ab6) | Dec 18, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [8f6f4d38d3](https://bsd-hardware.info/?probe=8f6f4d38d3) | Dec 17, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [878769cc62](https://bsd-hardware.info/?probe=878769cc62) | Dec 17, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [57a4adcc91](https://bsd-hardware.info/?probe=57a4adcc91) | Dec 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [784c8ae515](https://bsd-hardware.info/?probe=784c8ae515) | Dec 16, 2023 |
| HP            | 82A2                        | Desktop     | [906fd206fe](https://bsd-hardware.info/?probe=906fd206fe) | Dec 15, 2023 |
| HP            | 82A2                        | Desktop     | [0a816d2760](https://bsd-hardware.info/?probe=0a816d2760) | Dec 15, 2023 |
| Dell          | 0PC5F7 A00                  | Desktop     | [e47e643ced](https://bsd-hardware.info/?probe=e47e643ced) | Dec 14, 2023 |
| Sophos        | XG                          | Firewall    | [a851304161](https://bsd-hardware.info/?probe=a851304161) | Dec 03, 2023 |
| Intel         | DENLOW_WS                   | Desktop     | [d8b2ccabda](https://bsd-hardware.info/?probe=d8b2ccabda) | Nov 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [2a34bc9613](https://bsd-hardware.info/?probe=2a34bc9613) | Nov 28, 2023 |
| AZW           | SER                         | Desktop     | [48a259ae28](https://bsd-hardware.info/?probe=48a259ae28) | Nov 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [c8960ff614](https://bsd-hardware.info/?probe=c8960ff614) | Nov 22, 2023 |
| Supermicro    | X11SBA-LN4F-SI011A          | Server      | [5480de19a2](https://bsd-hardware.info/?probe=5480de19a2) | Nov 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [2c33e6e9e7](https://bsd-hardware.info/?probe=2c33e6e9e7) | Nov 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [066991fce5](https://bsd-hardware.info/?probe=066991fce5) | Nov 16, 2023 |
| HP            | 213D A01                    | Desktop     | [eff9e5704a](https://bsd-hardware.info/?probe=eff9e5704a) | Nov 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [ed79ea60c4](https://bsd-hardware.info/?probe=ed79ea60c4) | Nov 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [696dae397c](https://bsd-hardware.info/?probe=696dae397c) | Nov 12, 2023 |
| Shenzhen M... | RPBNB                       | Desktop     | [ab2de15a7a](https://bsd-hardware.info/?probe=ab2de15a7a) | Nov 11, 2023 |
| HP            | 8103 A01                    | Mini pc     | [c577648b65](https://bsd-hardware.info/?probe=c577648b65) | Nov 09, 2023 |
| HP            | 8103 A01                    | Mini pc     | [3c74f82659](https://bsd-hardware.info/?probe=3c74f82659) | Nov 08, 2023 |
| Shenzhen M... | RPBNB                       | Desktop     | [b04823f9e5](https://bsd-hardware.info/?probe=b04823f9e5) | Nov 07, 2023 |
| Dell          | 0D24M8 A01                  | Desktop     | [4c874fa8af](https://bsd-hardware.info/?probe=4c874fa8af) | Nov 06, 2023 |
| Dell          | 0D24M8 A01                  | Desktop     | [3ca7f9b6d1](https://bsd-hardware.info/?probe=3ca7f9b6d1) | Nov 06, 2023 |
| Shuttle       | FS61                        | Desktop     | [1ed38ceb8c](https://bsd-hardware.info/?probe=1ed38ceb8c) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [97f4527aab](https://bsd-hardware.info/?probe=97f4527aab) | Nov 05, 2023 |
| HP            | 83EE                        | Desktop     | [1ab86be61a](https://bsd-hardware.info/?probe=1ab86be61a) | Nov 05, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [c7d016caa9](https://bsd-hardware.info/?probe=c7d016caa9) | Nov 04, 2023 |
| HP            | 213D A01                    | Desktop     | [da7d91889e](https://bsd-hardware.info/?probe=da7d91889e) | Nov 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [743d5aec59](https://bsd-hardware.info/?probe=743d5aec59) | Nov 02, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [cac29f9a35](https://bsd-hardware.info/?probe=cac29f9a35) | Oct 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [850878776a](https://bsd-hardware.info/?probe=850878776a) | Oct 27, 2023 |
| HP            | 3397                        | Desktop     | [3dad1378f7](https://bsd-hardware.info/?probe=3dad1378f7) | Oct 27, 2023 |
| Winston Ma... | PICO PC V1.2                | Desktop     | [244102bda8](https://bsd-hardware.info/?probe=244102bda8) | Oct 26, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [9b797e809a](https://bsd-hardware.info/?probe=9b797e809a) | Oct 26, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [4dd20af1a3](https://bsd-hardware.info/?probe=4dd20af1a3) | Oct 26, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [fa2f4e1f86](https://bsd-hardware.info/?probe=fa2f4e1f86) | Oct 26, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [c66be142de](https://bsd-hardware.info/?probe=c66be142de) | Oct 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [530528316f](https://bsd-hardware.info/?probe=530528316f) | Oct 21, 2023 |
| Dell          | G16 7630                    | Notebook    | [deb5f3bd32](https://bsd-hardware.info/?probe=deb5f3bd32) | Oct 21, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [c51a6f8459](https://bsd-hardware.info/?probe=c51a6f8459) | Oct 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [af12786272](https://bsd-hardware.info/?probe=af12786272) | Oct 18, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [95e017977c](https://bsd-hardware.info/?probe=95e017977c) | Oct 14, 2023 |
| Unknown       | Unknown                     | Notebook    | [9c6c7f9d6b](https://bsd-hardware.info/?probe=9c6c7f9d6b) | Oct 10, 2023 |
| Intel         | NUC9i7QNB K49245-402        | Mini pc     | [30be7bec3f](https://bsd-hardware.info/?probe=30be7bec3f) | Oct 06, 2023 |
| HP            | 83EE                        | Desktop     | [88d80d215a](https://bsd-hardware.info/?probe=88d80d215a) | Sep 30, 2023 |
| HP            | 83EE                        | Desktop     | [d08ae678b5](https://bsd-hardware.info/?probe=d08ae678b5) | Sep 28, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [c2291f803c](https://bsd-hardware.info/?probe=c2291f803c) | Sep 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [a5643cabc4](https://bsd-hardware.info/?probe=a5643cabc4) | Sep 24, 2023 |
| Dell          | G16 7630                    | Notebook    | [4e39a5ebdf](https://bsd-hardware.info/?probe=4e39a5ebdf) | Sep 21, 2023 |
| GoWin Solu... | R86S                        | Desktop     | [0cfd79f7fe](https://bsd-hardware.info/?probe=0cfd79f7fe) | Sep 18, 2023 |
| HP            | 82A2                        | Desktop     | [4f125fbc75](https://bsd-hardware.info/?probe=4f125fbc75) | Sep 17, 2023 |
| Lenovo        | ThinkPad L390 20NRS00Q00    | Notebook    | [b9885ea126](https://bsd-hardware.info/?probe=b9885ea126) | Sep 17, 2023 |
| Lenovo        | ThinkPad T480s 20L7S24F0... | Notebook    | [bb7eb8b380](https://bsd-hardware.info/?probe=bb7eb8b380) | Sep 15, 2023 |
| HP            | Pavilion dv5                | Notebook    | [b7dad77d0d](https://bsd-hardware.info/?probe=b7dad77d0d) | Sep 14, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | Notebook    | [2e6af170b9](https://bsd-hardware.info/?probe=2e6af170b9) | Sep 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [21e851e9e9](https://bsd-hardware.info/?probe=21e851e9e9) | Sep 07, 2023 |
| TYAN Compu... | S5510HE                     | Desktop     | [99d23c35ca](https://bsd-hardware.info/?probe=99d23c35ca) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [0ebdda5146](https://bsd-hardware.info/?probe=0ebdda5146) | Aug 31, 2023 |
| Sophos        | XG                          | Firewall    | [29789e14c0](https://bsd-hardware.info/?probe=29789e14c0) | Aug 28, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [3dab6f4044](https://bsd-hardware.info/?probe=3dab6f4044) | Aug 28, 2023 |
| Dell          | G5 5590                     | Notebook    | [2e496efada](https://bsd-hardware.info/?probe=2e496efada) | Aug 26, 2023 |
| Dell          | G5 5590                     | Notebook    | [fd4f457391](https://bsd-hardware.info/?probe=fd4f457391) | Aug 26, 2023 |
| HP            | 8103 A01                    | Mini pc     | [d4394bc192](https://bsd-hardware.info/?probe=d4394bc192) | Aug 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [b5a786e411](https://bsd-hardware.info/?probe=b5a786e411) | Aug 18, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [74bfa3e0cd](https://bsd-hardware.info/?probe=74bfa3e0cd) | Aug 15, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [064ee65b5c](https://bsd-hardware.info/?probe=064ee65b5c) | Aug 10, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [fd4046c4d9](https://bsd-hardware.info/?probe=fd4046c4d9) | Aug 07, 2023 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | Desktop     | [f65647a6be](https://bsd-hardware.info/?probe=f65647a6be) | Aug 06, 2023 |
| Sophos        | XG                          | Firewall    | [a452891edc](https://bsd-hardware.info/?probe=a452891edc) | Aug 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [eee3c082b5](https://bsd-hardware.info/?probe=eee3c082b5) | Aug 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [e9977bfffe](https://bsd-hardware.info/?probe=e9977bfffe) | Aug 02, 2023 |
| HP            | 18E9                        | Desktop     | [04c971a0de](https://bsd-hardware.info/?probe=04c971a0de) | Jul 31, 2023 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [76ce6888f7](https://bsd-hardware.info/?probe=76ce6888f7) | Jul 29, 2023 |
| HP            | 83E1                        | Desktop     | [b211795736](https://bsd-hardware.info/?probe=b211795736) | Jul 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [64c9b0f743](https://bsd-hardware.info/?probe=64c9b0f743) | Jul 25, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [60dac781b2](https://bsd-hardware.info/?probe=60dac781b2) | Jul 24, 2023 |
| ASRock        | H570M-ITX/ac                | Desktop     | [8ac2939575](https://bsd-hardware.info/?probe=8ac2939575) | Jul 23, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [6d25aa067d](https://bsd-hardware.info/?probe=6d25aa067d) | Jul 22, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [63ab45fcb1](https://bsd-hardware.info/?probe=63ab45fcb1) | Jul 21, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1BK0... | Notebook    | [01f4886e09](https://bsd-hardware.info/?probe=01f4886e09) | Jul 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [5bea9c433e](https://bsd-hardware.info/?probe=5bea9c433e) | Jul 17, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [babdc9e843](https://bsd-hardware.info/?probe=babdc9e843) | Jul 15, 2023 |
| YANYU         | H67SL                       | Desktop     | [699da6c722](https://bsd-hardware.info/?probe=699da6c722) | Jul 13, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [4274ca291e](https://bsd-hardware.info/?probe=4274ca291e) | Jul 08, 2023 |
| Gigabyte      | M85M-US2H                   | Desktop     | [e0a38ef6ad](https://bsd-hardware.info/?probe=e0a38ef6ad) | Jul 03, 2023 |
| PC Engines    | APU2                        | Desktop     | [c1272678e6](https://bsd-hardware.info/?probe=c1272678e6) | Jul 02, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [9f6d45e43e](https://bsd-hardware.info/?probe=9f6d45e43e) | Jul 02, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [3eb03fa8a7](https://bsd-hardware.info/?probe=3eb03fa8a7) | Jul 02, 2023 |
| HP            | 82A2                        | Desktop     | [4b8d139419](https://bsd-hardware.info/?probe=4b8d139419) | Jun 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [23cdf1d4af](https://bsd-hardware.info/?probe=23cdf1d4af) | Jun 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [a548b021da](https://bsd-hardware.info/?probe=a548b021da) | Jun 27, 2023 |
| YANYU         | H67SL                       | Desktop     | [5d5fd8a8cd](https://bsd-hardware.info/?probe=5d5fd8a8cd) | Jun 27, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [648c09752f](https://bsd-hardware.info/?probe=648c09752f) | Jun 27, 2023 |
| HP            | 18E9                        | Desktop     | [aba608120b](https://bsd-hardware.info/?probe=aba608120b) | Jun 26, 2023 |
| Shuttle       | DH370                       | Desktop     | [95eb3bd4a8](https://bsd-hardware.info/?probe=95eb3bd4a8) | Jun 24, 2023 |
| Protectli     | FW4B                        | Desktop     | [6c993e8f34](https://bsd-hardware.info/?probe=6c993e8f34) | Jun 23, 2023 |
| Intel         | SKYBAY                      | Desktop     | [940adce39f](https://bsd-hardware.info/?probe=940adce39f) | Jun 23, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [c9420276e7](https://bsd-hardware.info/?probe=c9420276e7) | Jun 23, 2023 |
| Intel         | J1900                       | Desktop     | [4a3a52030b](https://bsd-hardware.info/?probe=4a3a52030b) | Jun 15, 2023 |
| HP            | Compaq 6830s                | Notebook    | [1a06917a0f](https://bsd-hardware.info/?probe=1a06917a0f) | Jun 14, 2023 |
| Acer          | Aspire TC-230               | Desktop     | [d7eacfafe1](https://bsd-hardware.info/?probe=d7eacfafe1) | Jun 04, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [d4247f35c8](https://bsd-hardware.info/?probe=d4247f35c8) | Jun 02, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [a87429607b](https://bsd-hardware.info/?probe=a87429607b) | Jun 01, 2023 |
| Intel         | QHSW02                      | Desktop     | [ed6d01bc2b](https://bsd-hardware.info/?probe=ed6d01bc2b) | May 31, 2023 |
| Intel         | QHSW02                      | Desktop     | [9f3d95a494](https://bsd-hardware.info/?probe=9f3d95a494) | May 31, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [1587da94da](https://bsd-hardware.info/?probe=1587da94da) | May 30, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [bd3ea7e1d6](https://bsd-hardware.info/?probe=bd3ea7e1d6) | May 28, 2023 |
| Intel         | J1900                       | Desktop     | [4d849f4f34](https://bsd-hardware.info/?probe=4d849f4f34) | May 27, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [310da4e6e5](https://bsd-hardware.info/?probe=310da4e6e5) | May 26, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [f350405f61](https://bsd-hardware.info/?probe=f350405f61) | May 26, 2023 |
| Timi          | TM1701                      | Notebook    | [1dd768a721](https://bsd-hardware.info/?probe=1dd768a721) | May 25, 2023 |
| Inventec      | R CLASS A02                 | Desktop     | [85f3673aa8](https://bsd-hardware.info/?probe=85f3673aa8) | May 24, 2023 |
| Intel         | J1900                       | Desktop     | [52081bc55b](https://bsd-hardware.info/?probe=52081bc55b) | May 24, 2023 |
| Dell          | 0M9KCM A02                  | Desktop     | [932e96060f](https://bsd-hardware.info/?probe=932e96060f) | May 21, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [3abf2c7ee2](https://bsd-hardware.info/?probe=3abf2c7ee2) | May 19, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [6f7bcae20b](https://bsd-hardware.info/?probe=6f7bcae20b) | May 19, 2023 |
| Protectli     | FW2B                        | Desktop     | [aa52b30ddf](https://bsd-hardware.info/?probe=aa52b30ddf) | May 14, 2023 |
| Dell          | 07F37C A00                  | Desktop     | [a23a95f97a](https://bsd-hardware.info/?probe=a23a95f97a) | May 07, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [633fa55df0](https://bsd-hardware.info/?probe=633fa55df0) | May 07, 2023 |
| Dell          | 0YC03K A04                  | Desktop     | [979aea14cc](https://bsd-hardware.info/?probe=979aea14cc) | May 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [28253dd080](https://bsd-hardware.info/?probe=28253dd080) | Apr 28, 2023 |
| Sophos        | XG                          | Firewall    | [5202fd70b1](https://bsd-hardware.info/?probe=5202fd70b1) | Apr 23, 2023 |
| Intel Clie... | LAPBC510                    | Notebook    | [68b1300903](https://bsd-hardware.info/?probe=68b1300903) | Apr 22, 2023 |
| HP            | 82B4                        | Desktop     | [b75bb5fe83](https://bsd-hardware.info/?probe=b75bb5fe83) | Apr 20, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [28c2a703c7](https://bsd-hardware.info/?probe=28c2a703c7) | Apr 18, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [737250a1c8](https://bsd-hardware.info/?probe=737250a1c8) | Apr 15, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [1835073ded](https://bsd-hardware.info/?probe=1835073ded) | Apr 14, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [41bf2600a5](https://bsd-hardware.info/?probe=41bf2600a5) | Apr 13, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [036b48e4c3](https://bsd-hardware.info/?probe=036b48e4c3) | Apr 13, 2023 |
| Acer          | Veriton X4630G              | Desktop     | [93987b345d](https://bsd-hardware.info/?probe=93987b345d) | Apr 12, 2023 |
| Acer          | Veriton M6620G              | Desktop     | [13f7e5c23b](https://bsd-hardware.info/?probe=13f7e5c23b) | Apr 07, 2023 |
| Dell          | 08VT7V A00                  | Server      | [e801f9c0de](https://bsd-hardware.info/?probe=e801f9c0de) | Apr 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [ee06e14aa2](https://bsd-hardware.info/?probe=ee06e14aa2) | Mar 29, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [459fdd8cdd](https://bsd-hardware.info/?probe=459fdd8cdd) | Mar 28, 2023 |
| HP            | 82B4                        | Desktop     | [6edc033f79](https://bsd-hardware.info/?probe=6edc033f79) | Mar 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a66dffcb5c](https://bsd-hardware.info/?probe=a66dffcb5c) | Mar 23, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [7db8753b08](https://bsd-hardware.info/?probe=7db8753b08) | Mar 17, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [e023282dcd](https://bsd-hardware.info/?probe=e023282dcd) | Mar 13, 2023 |
| ASUSTek       | G74Sx                       | Notebook    | [6b7cf8fcac](https://bsd-hardware.info/?probe=6b7cf8fcac) | Mar 13, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [b2176fafcf](https://bsd-hardware.info/?probe=b2176fafcf) | Mar 07, 2023 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [ca70bceb83](https://bsd-hardware.info/?probe=ca70bceb83) | Mar 05, 2023 |
| AMD           | Kabini CRB                  | Desktop     | [c9e69ff953](https://bsd-hardware.info/?probe=c9e69ff953) | Mar 03, 2023 |
| Protectli     | VP2410 10                   | Desktop     | [74eedb42ea](https://bsd-hardware.info/?probe=74eedb42ea) | Mar 03, 2023 |
| Gigabyte      | Z87X-OC-CF                  | Desktop     | [dca82c50d0](https://bsd-hardware.info/?probe=dca82c50d0) | Feb 23, 2023 |
| Acer          | Aspire TC-230               | Desktop     | [f3f963fb6a](https://bsd-hardware.info/?probe=f3f963fb6a) | Feb 22, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [02970305db](https://bsd-hardware.info/?probe=02970305db) | Feb 21, 2023 |
| ASUSTek       | H110I-PLUS D3               | Desktop     | [1f347f15e2](https://bsd-hardware.info/?probe=1f347f15e2) | Feb 19, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [81911bb61f](https://bsd-hardware.info/?probe=81911bb61f) | Feb 17, 2023 |
| ASUSTek       | H110I-PLUS D3               | Desktop     | [4d3dee18a0](https://bsd-hardware.info/?probe=4d3dee18a0) | Feb 16, 2023 |
| ASRock        | Z97 Killer                  | Desktop     | [67d58b9cde](https://bsd-hardware.info/?probe=67d58b9cde) | Feb 14, 2023 |
| Acer          | Aspire TC-230               | Desktop     | [a8ce4299ae](https://bsd-hardware.info/?probe=a8ce4299ae) | Feb 13, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [4d69517a13](https://bsd-hardware.info/?probe=4d69517a13) | Feb 07, 2023 |
| Intel         | S1200BTL E98681-352         | Server      | [31989714d5](https://bsd-hardware.info/?probe=31989714d5) | Feb 04, 2023 |
| Intel         | S1200BTL E98681-352         | Server      | [5459c67905](https://bsd-hardware.info/?probe=5459c67905) | Feb 04, 2023 |
| PC Engines    | APU2                        | Desktop     | [3bc47445d4](https://bsd-hardware.info/?probe=3bc47445d4) | Jan 26, 2023 |
| IBM           | 9210MML                     | Desktop     | [8b7e2413ee](https://bsd-hardware.info/?probe=8b7e2413ee) | Jan 25, 2023 |
| ADI Engine... | RCC-VE                      | Desktop     | [e2941c00fc](https://bsd-hardware.info/?probe=e2941c00fc) | Jan 25, 2023 |
| Supermicro    | X11SSH-F                    | Server      | [106cf811d8](https://bsd-hardware.info/?probe=106cf811d8) | Jan 25, 2023 |
| Dell          | OptiPlex 3040               | Desktop     | [9c925f4e7f](https://bsd-hardware.info/?probe=9c925f4e7f) | Jan 23, 2023 |
| Dell          | 0R5KP9 A04                  | Server      | [7b811598b5](https://bsd-hardware.info/?probe=7b811598b5) | Jan 22, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | Desktop     | [0d3e0df928](https://bsd-hardware.info/?probe=0d3e0df928) | Jan 20, 2023 |
| Dell          | 0R5KP9 A04                  | Server      | [03a26b8a34](https://bsd-hardware.info/?probe=03a26b8a34) | Jan 20, 2023 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [6bb5667269](https://bsd-hardware.info/?probe=6bb5667269) | Jan 17, 2023 |
| HP            | 870C                        | Desktop     | [d7afab37f3](https://bsd-hardware.info/?probe=d7afab37f3) | Jan 15, 2023 |
| HP            | 870C                        | Desktop     | [7a5bbc7546](https://bsd-hardware.info/?probe=7a5bbc7546) | Jan 15, 2023 |
| Dell          | OptiPlex 3040               | Desktop     | [07abf8e8b2](https://bsd-hardware.info/?probe=07abf8e8b2) | Jan 14, 2023 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [9c1f7ead89](https://bsd-hardware.info/?probe=9c1f7ead89) | Jan 06, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [b1ee757669](https://bsd-hardware.info/?probe=b1ee757669) | Jan 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [5d360961d4](https://bsd-hardware.info/?probe=5d360961d4) | Jan 02, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [d5f8e71171](https://bsd-hardware.info/?probe=d5f8e71171) | Jan 02, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [50c8cb79f7](https://bsd-hardware.info/?probe=50c8cb79f7) | Dec 26, 2022 |
| HP            | 870C                        | Desktop     | [6715ee2886](https://bsd-hardware.info/?probe=6715ee2886) | Dec 24, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b19a4d1696](https://bsd-hardware.info/?probe=b19a4d1696) | Dec 23, 2022 |
| HP            | 870C                        | Desktop     | [d9eec3c9f5](https://bsd-hardware.info/?probe=d9eec3c9f5) | Dec 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [0f03a7f2ce](https://bsd-hardware.info/?probe=0f03a7f2ce) | Dec 22, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [f241237f76](https://bsd-hardware.info/?probe=f241237f76) | Dec 22, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [a8ec4c3ae4](https://bsd-hardware.info/?probe=a8ec4c3ae4) | Dec 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [4667028e67](https://bsd-hardware.info/?probe=4667028e67) | Dec 20, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [b730e64d4a](https://bsd-hardware.info/?probe=b730e64d4a) | Dec 19, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [92593f4e79](https://bsd-hardware.info/?probe=92593f4e79) | Dec 17, 2022 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [d44c580408](https://bsd-hardware.info/?probe=d44c580408) | Dec 16, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [e199c0ec3d](https://bsd-hardware.info/?probe=e199c0ec3d) | Dec 15, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [d7d0ebf605](https://bsd-hardware.info/?probe=d7d0ebf605) | Dec 15, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [617f431099](https://bsd-hardware.info/?probe=617f431099) | Dec 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [85520bf6bf](https://bsd-hardware.info/?probe=85520bf6bf) | Dec 14, 2022 |
| HP            | 82A2                        | Desktop     | [c612b7e283](https://bsd-hardware.info/?probe=c612b7e283) | Dec 06, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [4bf1aae972](https://bsd-hardware.info/?probe=4bf1aae972) | Dec 02, 2022 |
| Shuttle       | FS81                        | Desktop     | [f714ba647f](https://bsd-hardware.info/?probe=f714ba647f) | Nov 28, 2022 |
| Protectli     | FW2B                        | Desktop     | [d15326180f](https://bsd-hardware.info/?probe=d15326180f) | Nov 10, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [9945b6b3e7](https://bsd-hardware.info/?probe=9945b6b3e7) | Nov 09, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [798219138a](https://bsd-hardware.info/?probe=798219138a) | Nov 07, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [394e873da0](https://bsd-hardware.info/?probe=394e873da0) | Nov 07, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [06a8abdbf4](https://bsd-hardware.info/?probe=06a8abdbf4) | Oct 29, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [7b330abf44](https://bsd-hardware.info/?probe=7b330abf44) | Oct 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [1f2cd1f9ea](https://bsd-hardware.info/?probe=1f2cd1f9ea) | Oct 24, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [607fcd2571](https://bsd-hardware.info/?probe=607fcd2571) | Oct 24, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [d32449b8c4](https://bsd-hardware.info/?probe=d32449b8c4) | Oct 16, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [f80953ee2f](https://bsd-hardware.info/?probe=f80953ee2f) | Oct 16, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [f27ffa7217](https://bsd-hardware.info/?probe=f27ffa7217) | Oct 16, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [ae4868c65b](https://bsd-hardware.info/?probe=ae4868c65b) | Oct 15, 2022 |
| PC Engines    | apu1                        | Desktop     | [06debf0076](https://bsd-hardware.info/?probe=06debf0076) | Oct 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [6c330d9bab](https://bsd-hardware.info/?probe=6c330d9bab) | Oct 14, 2022 |
| Unknown       | YL-1900L4-V2                | Desktop     | [1f55db62cc](https://bsd-hardware.info/?probe=1f55db62cc) | Oct 12, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [ea8b1fd760](https://bsd-hardware.info/?probe=ea8b1fd760) | Oct 12, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [9d3b9cb318](https://bsd-hardware.info/?probe=9d3b9cb318) | Oct 11, 2022 |
| Apple         | Mac-7BA5B2794B2CDB12 Mac... | Mini pc     | [b164bfcf33](https://bsd-hardware.info/?probe=b164bfcf33) | Oct 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [7718c8e9ca](https://bsd-hardware.info/?probe=7718c8e9ca) | Oct 05, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [63b36c077a](https://bsd-hardware.info/?probe=63b36c077a) | Oct 05, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Desktop     | [e001150f93](https://bsd-hardware.info/?probe=e001150f93) | Oct 03, 2022 |
| IBM           | 9210MML                     | Desktop     | [a6e7d7483f](https://bsd-hardware.info/?probe=a6e7d7483f) | Oct 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [9f998deaa4](https://bsd-hardware.info/?probe=9f998deaa4) | Sep 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [ffa40a08e8](https://bsd-hardware.info/?probe=ffa40a08e8) | Sep 23, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [58caab8946](https://bsd-hardware.info/?probe=58caab8946) | Sep 14, 2022 |
| Sophos        | XG                          | Firewall    | [1540138670](https://bsd-hardware.info/?probe=1540138670) | Sep 13, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [05b5d1e01a](https://bsd-hardware.info/?probe=05b5d1e01a) | Sep 12, 2022 |
| AOpen         | iBTMx-DS R1.03 55DED10A0... | Desktop     | [50ac5c0aaf](https://bsd-hardware.info/?probe=50ac5c0aaf) | Sep 10, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [cd90f548c8](https://bsd-hardware.info/?probe=cd90f548c8) | Sep 06, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [91664c3bc1](https://bsd-hardware.info/?probe=91664c3bc1) | Sep 05, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [bb379f7083](https://bsd-hardware.info/?probe=bb379f7083) | Sep 03, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [75ec0260f9](https://bsd-hardware.info/?probe=75ec0260f9) | Aug 28, 2022 |
| Intel         | NUC6i5SYB H81131-505        | Mini pc     | [d448c2dd6c](https://bsd-hardware.info/?probe=d448c2dd6c) | Aug 19, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | Notebook    | [4cc4d44e43](https://bsd-hardware.info/?probe=4cc4d44e43) | Aug 15, 2022 |
| Intel         | NUC6i5SYB H81131-505        | Mini pc     | [eee1d83783](https://bsd-hardware.info/?probe=eee1d83783) | Aug 14, 2022 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [9130257c6a](https://bsd-hardware.info/?probe=9130257c6a) | Aug 09, 2022 |
| Unknown       | YL-J3160L4                  | Desktop     | [aad241ba36](https://bsd-hardware.info/?probe=aad241ba36) | Aug 08, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [5b88dea745](https://bsd-hardware.info/?probe=5b88dea745) | Aug 06, 2022 |
| Protectli     | VP2410                      | Desktop     | [f9b42e4a75](https://bsd-hardware.info/?probe=f9b42e4a75) | Jul 27, 2022 |
| Protectli     | VP2410                      | Desktop     | [db66cc446e](https://bsd-hardware.info/?probe=db66cc446e) | Jul 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [ee70a58bd6](https://bsd-hardware.info/?probe=ee70a58bd6) | Jul 26, 2022 |
| HP            | 8055                        | Desktop     | [269b4f3210](https://bsd-hardware.info/?probe=269b4f3210) | Jul 17, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [607a66e533](https://bsd-hardware.info/?probe=607a66e533) | Jul 14, 2022 |
| AZW           | GK55                        | Desktop     | [40d9df6faa](https://bsd-hardware.info/?probe=40d9df6faa) | Jul 12, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [f68c3695ea](https://bsd-hardware.info/?probe=f68c3695ea) | Jul 08, 2022 |
| Firewalla     | FirewallaGold               | Firewall    | [e7d2dca92d](https://bsd-hardware.info/?probe=e7d2dca92d) | Jul 02, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [a3aff65df2](https://bsd-hardware.info/?probe=a3aff65df2) | Jun 27, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [4d4993a732](https://bsd-hardware.info/?probe=4d4993a732) | Jun 24, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [7d054ce34f](https://bsd-hardware.info/?probe=7d054ce34f) | Jun 23, 2022 |
| HP            | ProLiant ML10 v2            | Desktop     | [72254b033d](https://bsd-hardware.info/?probe=72254b033d) | Jun 06, 2022 |
| Dell          | 0MGK50 A02                  | Desktop     | [1de9982d19](https://bsd-hardware.info/?probe=1de9982d19) | Jun 05, 2022 |
| AOpen         | iBTMx-DS R1.03 55DED10A0... | Desktop     | [94bdba6302](https://bsd-hardware.info/?probe=94bdba6302) | Jun 04, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [f1838b29ff](https://bsd-hardware.info/?probe=f1838b29ff) | Jun 01, 2022 |
| Dell          | G5 5590                     | Notebook    | [86bac52410](https://bsd-hardware.info/?probe=86bac52410) | May 29, 2022 |
| Intel         | NUC9i7QNB K49245-402        | Mini pc     | [92881489e1](https://bsd-hardware.info/?probe=92881489e1) | May 22, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [fdab123532](https://bsd-hardware.info/?probe=fdab123532) | May 07, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [59083ac5ac](https://bsd-hardware.info/?probe=59083ac5ac) | May 06, 2022 |
| MSI           | 2A9C                        | Desktop     | [506b970279](https://bsd-hardware.info/?probe=506b970279) | May 03, 2022 |
| HP            | ZBook 14                    | Notebook    | [a646255b51](https://bsd-hardware.info/?probe=a646255b51) | May 02, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [3f170bdee6](https://bsd-hardware.info/?probe=3f170bdee6) | May 01, 2022 |
| Lenovo        | ThinkPad T470 20HES0ES1F    | Notebook    | [f1f0676663](https://bsd-hardware.info/?probe=f1f0676663) | Apr 28, 2022 |
| HP            | Notebook                    | Notebook    | [eea4cff90b](https://bsd-hardware.info/?probe=eea4cff90b) | Apr 27, 2022 |
| ASUSTek       | P9D-C Series                | Server      | [ac16999995](https://bsd-hardware.info/?probe=ac16999995) | Apr 22, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [76a2d4f148](https://bsd-hardware.info/?probe=76a2d4f148) | Apr 22, 2022 |
| HP            | Notebook                    | Notebook    | [eaff4f0fbf](https://bsd-hardware.info/?probe=eaff4f0fbf) | Apr 19, 2022 |
| MSI           | 2A9C                        | Desktop     | [595c9a1da2](https://bsd-hardware.info/?probe=595c9a1da2) | Apr 18, 2022 |
| MSI           | 2A9C                        | Desktop     | [7f44d30f83](https://bsd-hardware.info/?probe=7f44d30f83) | Apr 15, 2022 |
| HP            | Notebook                    | Notebook    | [6a112cfe6c](https://bsd-hardware.info/?probe=6a112cfe6c) | Apr 11, 2022 |
| HP            | Notebook                    | Notebook    | [a31dd5f48d](https://bsd-hardware.info/?probe=a31dd5f48d) | Apr 11, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [e32f0f2130](https://bsd-hardware.info/?probe=e32f0f2130) | Apr 08, 2022 |
| Lenovo        | 7X08CTO1WW                  | Server      | [46c59d0de8](https://bsd-hardware.info/?probe=46c59d0de8) | Apr 08, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [c807e1d8eb](https://bsd-hardware.info/?probe=c807e1d8eb) | Apr 07, 2022 |
| Protectli     | FW4B                        | Desktop     | [a2f902524b](https://bsd-hardware.info/?probe=a2f902524b) | Apr 06, 2022 |
| Protectli     | FW4B                        | Desktop     | [af9f2d81b5](https://bsd-hardware.info/?probe=af9f2d81b5) | Apr 06, 2022 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [1800a41f61](https://bsd-hardware.info/?probe=1800a41f61) | Mar 28, 2022 |
| Inventec      | D CLASS A02                 | Desktop     | [2ea328c95d](https://bsd-hardware.info/?probe=2ea328c95d) | Mar 28, 2022 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [8f20a3214b](https://bsd-hardware.info/?probe=8f20a3214b) | Mar 25, 2022 |
| Dell          | 0F0XJ6 A06                  | Server      | [e0599f5c69](https://bsd-hardware.info/?probe=e0599f5c69) | Mar 21, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [1e9ea7cdbc](https://bsd-hardware.info/?probe=1e9ea7cdbc) | Mar 19, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [8da46f8dd0](https://bsd-hardware.info/?probe=8da46f8dd0) | Mar 18, 2022 |
| Gigabyte      | 970A-D3P                    | Desktop     | [fa03bdabb6](https://bsd-hardware.info/?probe=fa03bdabb6) | Mar 15, 2022 |
| MSI           | MS-B1831                    | Desktop     | [346c445c21](https://bsd-hardware.info/?probe=346c445c21) | Mar 12, 2022 |
| HP            | 8103 A01                    | Mini pc     | [23b35e5b18](https://bsd-hardware.info/?probe=23b35e5b18) | Mar 10, 2022 |
| Dell          | G5 5590                     | Notebook    | [0871c1269b](https://bsd-hardware.info/?probe=0871c1269b) | Mar 07, 2022 |
| MSI           | MS-B1831                    | Desktop     | [572bb2c98c](https://bsd-hardware.info/?probe=572bb2c98c) | Mar 02, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [8d5986c1f4](https://bsd-hardware.info/?probe=8d5986c1f4) | Feb 26, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [68f6eb4328](https://bsd-hardware.info/?probe=68f6eb4328) | Feb 23, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [c1397b851e](https://bsd-hardware.info/?probe=c1397b851e) | Feb 22, 2022 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [51b0a953b5](https://bsd-hardware.info/?probe=51b0a953b5) | Feb 22, 2022 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [85441a65a9](https://bsd-hardware.info/?probe=85441a65a9) | Feb 21, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [1d9eaaaf62](https://bsd-hardware.info/?probe=1d9eaaaf62) | Feb 18, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [adcfe67709](https://bsd-hardware.info/?probe=adcfe67709) | Feb 16, 2022 |
| HP            | 8103 A01                    | Mini pc     | [d9222c59e5](https://bsd-hardware.info/?probe=d9222c59e5) | Feb 12, 2022 |
| MSI           | MS-B1831                    | Desktop     | [5bdc589f33](https://bsd-hardware.info/?probe=5bdc589f33) | Feb 10, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [0cc80ca4ec](https://bsd-hardware.info/?probe=0cc80ca4ec) | Feb 07, 2022 |
| MSI           | MS-B1831                    | Desktop     | [c8072d090e](https://bsd-hardware.info/?probe=c8072d090e) | Feb 06, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [6eecbfde04](https://bsd-hardware.info/?probe=6eecbfde04) | Feb 05, 2022 |
| Dell          | Latitude E7450              | Notebook    | [8a3867f171](https://bsd-hardware.info/?probe=8a3867f171) | Feb 03, 2022 |
| Lenovo        | ThinkCentre M58 7360BB6     | Desktop     | [8751a2776e](https://bsd-hardware.info/?probe=8751a2776e) | Jan 31, 2022 |
| Dell          | 0CN7CM A09                  | Server      | [3ec53e21df](https://bsd-hardware.info/?probe=3ec53e21df) | Jan 29, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [21e1806645](https://bsd-hardware.info/?probe=21e1806645) | Jan 29, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [50b7edb511](https://bsd-hardware.info/?probe=50b7edb511) | Jan 29, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [8587a16b51](https://bsd-hardware.info/?probe=8587a16b51) | Jan 29, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [6ea3284f28](https://bsd-hardware.info/?probe=6ea3284f28) | Jan 29, 2022 |
| Lenovo        | ThinkCentre M58 7360BB6     | Desktop     | [f53622f02b](https://bsd-hardware.info/?probe=f53622f02b) | Jan 27, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [b62251041b](https://bsd-hardware.info/?probe=b62251041b) | Jan 26, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [d180b0d394](https://bsd-hardware.info/?probe=d180b0d394) | Jan 25, 2022 |
| HP            | 8103 A01                    | Mini pc     | [147f49ca42](https://bsd-hardware.info/?probe=147f49ca42) | Jan 22, 2022 |
| Toshiba       | Satellite L50-A             | Notebook    | [94b87158aa](https://bsd-hardware.info/?probe=94b87158aa) | Jan 21, 2022 |
| Cisco         | ASA5512 A0                  | Desktop     | [99d276f574](https://bsd-hardware.info/?probe=99d276f574) | Jan 18, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [53b106bbb6](https://bsd-hardware.info/?probe=53b106bbb6) | Jan 16, 2022 |
| Dell          | 0XCR8D A03                  | Desktop     | [48e9447b37](https://bsd-hardware.info/?probe=48e9447b37) | Jan 15, 2022 |
| Gigabyte      | Z77N-WIFI                   | Desktop     | [459bb6486d](https://bsd-hardware.info/?probe=459bb6486d) | Jan 13, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [e0eb7a3239](https://bsd-hardware.info/?probe=e0eb7a3239) | Jan 13, 2022 |
| HP            | 8103 A01                    | Mini pc     | [2f22679aa6](https://bsd-hardware.info/?probe=2f22679aa6) | Jan 10, 2022 |
| HP            | 1998                        | Desktop     | [1d46974005](https://bsd-hardware.info/?probe=1d46974005) | Jan 03, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [d641a4bea9](https://bsd-hardware.info/?probe=d641a4bea9) | Dec 30, 2021 |
| ASUSTek       | X99-E-10G WS                | Desktop     | [dacf7f604c](https://bsd-hardware.info/?probe=dacf7f604c) | Dec 20, 2021 |
| Intel         | SKYBAY                      | Desktop     | [40d8768e52](https://bsd-hardware.info/?probe=40d8768e52) | Dec 20, 2021 |
| Protectli     | FW6 Ver                     | Desktop     | [52ba0807f9](https://bsd-hardware.info/?probe=52ba0807f9) | Dec 17, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [bc910b229a](https://bsd-hardware.info/?probe=bc910b229a) | Dec 12, 2021 |
| Intel         | NUC7JYB J67970-400          | Mini pc     | [c55f468566](https://bsd-hardware.info/?probe=c55f468566) | Dec 12, 2021 |
| Intel         | NUC7JYB J67970-400          | Mini pc     | [82c010f13c](https://bsd-hardware.info/?probe=82c010f13c) | Dec 09, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ab56e6eca2](https://bsd-hardware.info/?probe=ab56e6eca2) | Nov 23, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [645f845f43](https://bsd-hardware.info/?probe=645f845f43) | Nov 21, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [8a8efba0b3](https://bsd-hardware.info/?probe=8a8efba0b3) | Nov 19, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [8ebeac18ca](https://bsd-hardware.info/?probe=8ebeac18ca) | Nov 19, 2021 |
| HP            | 8103 A01                    | Mini pc     | [12763190f5](https://bsd-hardware.info/?probe=12763190f5) | Nov 16, 2021 |
| HP            | 8103 A01                    | Mini pc     | [8e779b15f3](https://bsd-hardware.info/?probe=8e779b15f3) | Nov 15, 2021 |
| Dell          | 0T10XW A01                  | Desktop     | [ae2203b146](https://bsd-hardware.info/?probe=ae2203b146) | Nov 12, 2021 |
| AAEON         | EMB-H61A V1.0               | Desktop     | [f13f63617f](https://bsd-hardware.info/?probe=f13f63617f) | Nov 11, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [fc32ac51e4](https://bsd-hardware.info/?probe=fc32ac51e4) | Nov 10, 2021 |
| HP            | 8103 A01                    | Mini pc     | [a6c494cc8f](https://bsd-hardware.info/?probe=a6c494cc8f) | Nov 08, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [4d9532acfa](https://bsd-hardware.info/?probe=4d9532acfa) | Nov 07, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [2a874a33dd](https://bsd-hardware.info/?probe=2a874a33dd) | Nov 05, 2021 |
| Gateway       | DX4840                      | Desktop     | [1d2e9e175c](https://bsd-hardware.info/?probe=1d2e9e175c) | Nov 01, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [1f3657128e](https://bsd-hardware.info/?probe=1f3657128e) | Oct 30, 2021 |
| ADI Engine... | RCC-VE                      | Desktop     | [9744b5eca0](https://bsd-hardware.info/?probe=9744b5eca0) | Oct 29, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d2ffea0e21](https://bsd-hardware.info/?probe=d2ffea0e21) | Oct 29, 2021 |
| Supermicro    | X11SSH-F                    | Server      | [06db2a9c2f](https://bsd-hardware.info/?probe=06db2a9c2f) | Oct 29, 2021 |
| HP            | 18E9                        | Desktop     | [9c9a3a0297](https://bsd-hardware.info/?probe=9c9a3a0297) | Oct 27, 2021 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [ced0819a8e](https://bsd-hardware.info/?probe=ced0819a8e) | Oct 24, 2021 |
| ASUSTek       | P10S WS                     | Desktop     | [e2d86f8c45](https://bsd-hardware.info/?probe=e2d86f8c45) | Oct 23, 2021 |
| HP            | ProLiant ML150 G6           | Desktop     | [06b8fc5c06](https://bsd-hardware.info/?probe=06b8fc5c06) | Oct 18, 2021 |
| Hardkernel    | ODROID-H2                   | Desktop     | [63850e668d](https://bsd-hardware.info/?probe=63850e668d) | Oct 16, 2021 |
| Protectli     | FW4B                        | Desktop     | [e20e889703](https://bsd-hardware.info/?probe=e20e889703) | Oct 16, 2021 |
| Acer          | Veriton X4610G              | Desktop     | [2ca4d093d3](https://bsd-hardware.info/?probe=2ca4d093d3) | Oct 01, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [3fafbcecc5](https://bsd-hardware.info/?probe=3fafbcecc5) | Sep 30, 2021 |
| Dell          | 0NRF6V A01                  | Server      | [c08c97aacc](https://bsd-hardware.info/?probe=c08c97aacc) | Sep 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [2494d9d2db](https://bsd-hardware.info/?probe=2494d9d2db) | Sep 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [28bbeb8b2e](https://bsd-hardware.info/?probe=28bbeb8b2e) | Sep 26, 2021 |
| ASRock        | B560M Pro4/ac               | Desktop     | [1b057f3b7d](https://bsd-hardware.info/?probe=1b057f3b7d) | Sep 23, 2021 |
| ASRock        | B560M Pro4/ac               | Desktop     | [fcf75fc410](https://bsd-hardware.info/?probe=fcf75fc410) | Sep 23, 2021 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [be32d2981b](https://bsd-hardware.info/?probe=be32d2981b) | Sep 19, 2021 |
| Lenovo        | G40-70 20369                | Notebook    | [ef8eafa662](https://bsd-hardware.info/?probe=ef8eafa662) | Sep 18, 2021 |
| Gigabyte      | EP45-UD3R                   | Desktop     | [21e4a40d62](https://bsd-hardware.info/?probe=21e4a40d62) | Sep 18, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [49f080ea2e](https://bsd-hardware.info/?probe=49f080ea2e) | Sep 12, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [8125c50b2a](https://bsd-hardware.info/?probe=8125c50b2a) | Sep 11, 2021 |
| Protectli     | FW4B                        | Desktop     | [941392a0bb](https://bsd-hardware.info/?probe=941392a0bb) | Sep 11, 2021 |
| HP            | 8103 A01                    | Mini pc     | [341ca2f887](https://bsd-hardware.info/?probe=341ca2f887) | Sep 03, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [fa4da2509b](https://bsd-hardware.info/?probe=fa4da2509b) | Sep 03, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [97035edd33](https://bsd-hardware.info/?probe=97035edd33) | Sep 03, 2021 |
| Intel         | SandyBridge Platform        | Notebook    | [f0aaf635c3](https://bsd-hardware.info/?probe=f0aaf635c3) | Sep 02, 2021 |
| ASRock        | Z390 Pro4                   | Desktop     | [ecbf097bc5](https://bsd-hardware.info/?probe=ecbf097bc5) | Sep 02, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [114ef9a519](https://bsd-hardware.info/?probe=114ef9a519) | Aug 30, 2021 |
| ASRock        | 990FX Killer                | Desktop     | [9f6f8fe218](https://bsd-hardware.info/?probe=9f6f8fe218) | Aug 22, 2021 |
| ASRock        | Z390 Pro4                   | Desktop     | [aca402061b](https://bsd-hardware.info/?probe=aca402061b) | Aug 18, 2021 |
| HP            | 8103 A01                    | Mini pc     | [f02d97dbeb](https://bsd-hardware.info/?probe=f02d97dbeb) | Aug 18, 2021 |
| Foxconn       | 2ADA                        | Desktop     | [e96976b2cc](https://bsd-hardware.info/?probe=e96976b2cc) | Aug 18, 2021 |
| HP            | 1825                        | Desktop     | [970bb6f787](https://bsd-hardware.info/?probe=970bb6f787) | Aug 17, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [7b20265c8e](https://bsd-hardware.info/?probe=7b20265c8e) | Aug 14, 2021 |
| Acer          | Veriton X4610G              | Desktop     | [619dedc13e](https://bsd-hardware.info/?probe=619dedc13e) | Aug 11, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [97781253f2](https://bsd-hardware.info/?probe=97781253f2) | Aug 03, 2021 |
| Microsoft     | Surface Go                  | Tablet      | [1dfbc72509](https://bsd-hardware.info/?probe=1dfbc72509) | Jul 30, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [8e67b63c6a](https://bsd-hardware.info/?probe=8e67b63c6a) | Jul 19, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [cfb68fd411](https://bsd-hardware.info/?probe=cfb68fd411) | Jul 14, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [519168441f](https://bsd-hardware.info/?probe=519168441f) | Jul 10, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d713cecb20](https://bsd-hardware.info/?probe=d713cecb20) | Jul 10, 2021 |
| ASRock        | Z390 Pro4                   | Desktop     | [dc4eb674ea](https://bsd-hardware.info/?probe=dc4eb674ea) | Jul 03, 2021 |
| Protectli     | FW2B Ver                    | Desktop     | [7b6f704247](https://bsd-hardware.info/?probe=7b6f704247) | Jun 30, 2021 |
| Dell          | 0NRF6V A01                  | Server      | [70fffc6930](https://bsd-hardware.info/?probe=70fffc6930) | Jun 22, 2021 |
| Dell          | 0GTK4K A02                  | Desktop     | [53f4f785ba](https://bsd-hardware.info/?probe=53f4f785ba) | Jun 22, 2021 |
| Dell          | 0GTK4K A02                  | Desktop     | [bb610333d0](https://bsd-hardware.info/?probe=bb610333d0) | Jun 22, 2021 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [cb7cbd17d0](https://bsd-hardware.info/?probe=cb7cbd17d0) | Jun 20, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [2a6f8cdb64](https://bsd-hardware.info/?probe=2a6f8cdb64) | Jun 20, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [c2cdbdb012](https://bsd-hardware.info/?probe=c2cdbdb012) | Jun 15, 2021 |
| HP            | 8103 A01                    | Mini pc     | [ffd1dd6fb1](https://bsd-hardware.info/?probe=ffd1dd6fb1) | Jun 14, 2021 |
| Protectli     | VP2410 10                   | Desktop     | [27a4d07d70](https://bsd-hardware.info/?probe=27a4d07d70) | Jun 12, 2021 |
| Protectli     | VP2410 10                   | Desktop     | [5dd0792386](https://bsd-hardware.info/?probe=5dd0792386) | Jun 12, 2021 |
| HP            | 8103 A01                    | Mini pc     | [8549e8b3c4](https://bsd-hardware.info/?probe=8549e8b3c4) | Jun 09, 2021 |
| Unknown       | J3160-4L                    | Desktop     | [3e773132b3](https://bsd-hardware.info/?probe=3e773132b3) | Jun 06, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [700ba3f063](https://bsd-hardware.info/?probe=700ba3f063) | May 31, 2021 |
| HP            | 8103 A01                    | Mini pc     | [1b26a44944](https://bsd-hardware.info/?probe=1b26a44944) | May 31, 2021 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [10d9e99990](https://bsd-hardware.info/?probe=10d9e99990) | May 31, 2021 |
| Dell          | 0CN7CM A09                  | Server      | [92a93d51c5](https://bsd-hardware.info/?probe=92a93d51c5) | May 23, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [33b86a7df2](https://bsd-hardware.info/?probe=33b86a7df2) | May 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [7ea373882a](https://bsd-hardware.info/?probe=7ea373882a) | May 19, 2021 |
| Intel         | NUC10i5FNB K61361-305       | Mini pc     | [a09fbe5fcc](https://bsd-hardware.info/?probe=a09fbe5fcc) | May 12, 2021 |
| Unknown       | Unknown                     | Desktop     | [72eb276213](https://bsd-hardware.info/?probe=72eb276213) | May 05, 2021 |
| Shuttle       | DH370                       | Desktop     | [ad380cb985](https://bsd-hardware.info/?probe=ad380cb985) | May 04, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [1c9feef8e7](https://bsd-hardware.info/?probe=1c9feef8e7) | May 03, 2021 |
| Lenovo        | SHARKBAY SDK0J40705 WIN     | Desktop     | [6a62687665](https://bsd-hardware.info/?probe=6a62687665) | May 03, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [3e211c52ea](https://bsd-hardware.info/?probe=3e211c52ea) | Apr 21, 2021 |
| Sophos        | SG                          | Firewall    | [88ea908224](https://bsd-hardware.info/?probe=88ea908224) | Apr 14, 2021 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [cb97f230b8](https://bsd-hardware.info/?probe=cb97f230b8) | Apr 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [821c81e652](https://bsd-hardware.info/?probe=821c81e652) | Apr 09, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [bc3913fead](https://bsd-hardware.info/?probe=bc3913fead) | Apr 06, 2021 |
| ASUSTek       | TP500LNG                    | Notebook    | [6501322932](https://bsd-hardware.info/?probe=6501322932) | Apr 06, 2021 |
| Hardkernel    | ODROID-H2                   | Desktop     | [bcaa207f9b](https://bsd-hardware.info/?probe=bcaa207f9b) | Apr 05, 2021 |
| Dell          | G5 5590                     | Notebook    | [18863bc535](https://bsd-hardware.info/?probe=18863bc535) | Apr 05, 2021 |
| Sophos        | SG                          | Firewall    | [76a33ea7ea](https://bsd-hardware.info/?probe=76a33ea7ea) | Mar 28, 2021 |
| Sophos        | SG                          | Firewall    | [487e450695](https://bsd-hardware.info/?probe=487e450695) | Mar 23, 2021 |
| HP            | ProBook 430 G3              | Notebook    | [32dfd5e52a](https://bsd-hardware.info/?probe=32dfd5e52a) | Mar 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [e66fe7a153](https://bsd-hardware.info/?probe=e66fe7a153) | Mar 21, 2021 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [bf9f69e68b](https://bsd-hardware.info/?probe=bf9f69e68b) | Mar 11, 2021 |
| Unknown       | Unknown                     | Notebook    | [70304f9c5d](https://bsd-hardware.info/?probe=70304f9c5d) | Mar 11, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [bb7f6e1db9](https://bsd-hardware.info/?probe=bb7f6e1db9) | Mar 10, 2021 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [c88b021c05](https://bsd-hardware.info/?probe=c88b021c05) | Mar 09, 2021 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [7201058b50](https://bsd-hardware.info/?probe=7201058b50) | Mar 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [635419dc18](https://bsd-hardware.info/?probe=635419dc18) | Mar 07, 2021 |
| ASUSTek       | X99-E-10G WS                | Desktop     | [4e73497945](https://bsd-hardware.info/?probe=4e73497945) | Mar 06, 2021 |
| Intel         | NUC10i5FNB K61361-305       | Mini pc     | [953b768755](https://bsd-hardware.info/?probe=953b768755) | Mar 03, 2021 |
| PC Engines    | apu4                        | Desktop     | [2a3c8a81d5](https://bsd-hardware.info/?probe=2a3c8a81d5) | Mar 02, 2021 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [0951c73dba](https://bsd-hardware.info/?probe=0951c73dba) | Mar 01, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [ec20bc7cea](https://bsd-hardware.info/?probe=ec20bc7cea) | Feb 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [950cf51db1](https://bsd-hardware.info/?probe=950cf51db1) | Feb 28, 2021 |
| HP            | 8103 A01                    | Mini pc     | [d436c0a897](https://bsd-hardware.info/?probe=d436c0a897) | Feb 27, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [8fda503f16](https://bsd-hardware.info/?probe=8fda503f16) | Feb 27, 2021 |
| ASUSTek       | B75M-PLUS                   | Desktop     | [8379cc790c](https://bsd-hardware.info/?probe=8379cc790c) | Feb 25, 2021 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [13c1f72630](https://bsd-hardware.info/?probe=13c1f72630) | Feb 24, 2021 |
| Dell          | 0XCR8D A03                  | Desktop     | [8aa33e35ad](https://bsd-hardware.info/?probe=8aa33e35ad) | Feb 21, 2021 |
| Hardkernel    | ODROID-H2                   | Desktop     | [1f25ddeb54](https://bsd-hardware.info/?probe=1f25ddeb54) | Feb 20, 2021 |
| Unknown       | Unknown                     | Desktop     | [6b724a36cd](https://bsd-hardware.info/?probe=6b724a36cd) | Feb 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [baf854930a](https://bsd-hardware.info/?probe=baf854930a) | Feb 19, 2021 |
| ASRock        | B365M Pro4                  | Desktop     | [1c438d977e](https://bsd-hardware.info/?probe=1c438d977e) | Feb 18, 2021 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [be56203e79](https://bsd-hardware.info/?probe=be56203e79) | Feb 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [a2833c6695](https://bsd-hardware.info/?probe=a2833c6695) | Feb 08, 2021 |
| ASUSTek       | P5E3                        | Desktop     | [1d1edd3551](https://bsd-hardware.info/?probe=1d1edd3551) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | Notebook    | [a201c5f713](https://bsd-hardware.info/?probe=a201c5f713) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | Notebook    | [d0a5d1cb86](https://bsd-hardware.info/?probe=d0a5d1cb86) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | Notebook    | [a51cf81e58](https://bsd-hardware.info/?probe=a51cf81e58) | Feb 06, 2021 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [98e358b324](https://bsd-hardware.info/?probe=98e358b324) | Feb 05, 2021 |
| Radxa         | ROCK Pi X v1.4              | Desktop     | [688c95bda6](https://bsd-hardware.info/?probe=688c95bda6) | Feb 05, 2021 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [a7b2c5457c](https://bsd-hardware.info/?probe=a7b2c5457c) | Jan 29, 2021 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [40793aaedb](https://bsd-hardware.info/?probe=40793aaedb) | Jan 26, 2021 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [a2c7bfe3a1](https://bsd-hardware.info/?probe=a2c7bfe3a1) | Jan 26, 2021 |
| Lenovo        | 312D SDK0J40700 WIN 3258... | Mini pc     | [d15116d2eb](https://bsd-hardware.info/?probe=d15116d2eb) | Jan 25, 2021 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [a344f83f2e](https://bsd-hardware.info/?probe=a344f83f2e) | Jan 25, 2021 |
| Acer          | Veriton S6610G              | Desktop     | [64587ce287](https://bsd-hardware.info/?probe=64587ce287) | Jan 23, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [a78907417f](https://bsd-hardware.info/?probe=a78907417f) | Jan 22, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [4afdd92b10](https://bsd-hardware.info/?probe=4afdd92b10) | Jan 20, 2021 |
| Toshiba       | KIRA                        | Notebook    | [1ee77fde0b](https://bsd-hardware.info/?probe=1ee77fde0b) | Jan 18, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [f51f3873ce](https://bsd-hardware.info/?probe=f51f3873ce) | Dec 25, 2020 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [5e8506d20e](https://bsd-hardware.info/?probe=5e8506d20e) | Dec 24, 2020 |
| HP            | 0B4Ch D                     | Desktop     | [bf0d7fe4f1](https://bsd-hardware.info/?probe=bf0d7fe4f1) | Dec 22, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [de7d8622aa](https://bsd-hardware.info/?probe=de7d8622aa) | Dec 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [7f6ebffad8](https://bsd-hardware.info/?probe=7f6ebffad8) | Dec 18, 2020 |
| Lenovo        | ThinkPad T460p 20FXCTO1W... | Notebook    | [ddc907ccf4](https://bsd-hardware.info/?probe=ddc907ccf4) | Dec 17, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [1414d7ae80](https://bsd-hardware.info/?probe=1414d7ae80) | Dec 16, 2020 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [4e217288fe](https://bsd-hardware.info/?probe=4e217288fe) | Dec 16, 2020 |
| ASUSTek       | K72F                        | Notebook    | [321cd9d139](https://bsd-hardware.info/?probe=321cd9d139) | Dec 08, 2020 |
| ASUSTek       | K72F                        | Notebook    | [b36ff0b052](https://bsd-hardware.info/?probe=b36ff0b052) | Dec 08, 2020 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [33724c243d](https://bsd-hardware.info/?probe=33724c243d) | Dec 06, 2020 |
| HP            | Setzer                      | Notebook    | [da7914cdd5](https://bsd-hardware.info/?probe=da7914cdd5) | Nov 22, 2020 |
| Lenovo        | ThinkPad T450 20BVA020AU    | Notebook    | [5d8bce59e8](https://bsd-hardware.info/?probe=5d8bce59e8) | Nov 16, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [ec13cfdd0d](https://bsd-hardware.info/?probe=ec13cfdd0d) | Oct 29, 2020 |
| Dell          | 0TW856 A02                  | Server      | [f181777604](https://bsd-hardware.info/?probe=f181777604) | Oct 29, 2020 |
| Dell          | 042P49 A02                  | Desktop     | [c34a9c7091](https://bsd-hardware.info/?probe=c34a9c7091) | Oct 29, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [c1c3ffb720](https://bsd-hardware.info/?probe=c1c3ffb720) | Oct 29, 2020 |
| Lenovo        | ThinkPad X230 2320JXM       | Notebook    | [cdbf62a168](https://bsd-hardware.info/?probe=cdbf62a168) | Oct 29, 2020 |
| Lenovo        | ThinkPad X60s 17033JM       | Notebook    | [67e701adb7](https://bsd-hardware.info/?probe=67e701adb7) | Oct 21, 2020 |
| Unknown       | Unknown                     | Desktop     | [a28ef1d2b8](https://bsd-hardware.info/?probe=a28ef1d2b8) | Oct 20, 2020 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [af179a268f](https://bsd-hardware.info/?probe=af179a268f) | Oct 19, 2020 |
| Acer          | Peppy                       | Notebook    | [d68bd5cbb5](https://bsd-hardware.info/?probe=d68bd5cbb5) | Oct 02, 2020 |
| Acer          | Peppy                       | Notebook    | [26058cddbf](https://bsd-hardware.info/?probe=26058cddbf) | Oct 02, 2020 |
| Unknown       | Unknown                     | Desktop     | [864589fce0](https://bsd-hardware.info/?probe=864589fce0) | Oct 02, 2020 |
| Apple         | MacBookAir5,1               | Notebook    | [6cced6fcf0](https://bsd-hardware.info/?probe=6cced6fcf0) | Sep 23, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Australia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| OPNsense 25.7.3   | 18        | 2.2%    |
| OPNsense 24.7.12  | 18        | 2.2%    |
| OPNsense 24.1.6   | 18        | 2.2%    |
| OPNsense 23.1.11  | 15        | 1.83%   |
| OPNsense 24.1.9   | 13        | 1.59%   |
| OPNsense 24.1.10  | 13        | 1.59%   |
| helloSystem 0.8.1 | 13        | 1.59%   |
| OPNsense 25.1.5   | 12        | 1.47%   |
| OPNsense 25.7.7   | 11        | 1.34%   |
| OPNsense 25.1.9   | 11        | 1.34%   |
| OPNsense 24.7.3   | 11        | 1.34%   |
| OPNsense 23.7.10  | 11        | 1.34%   |
| OPNsense 25.1.7   | 10        | 1.22%   |
| OPNsense 24.1.8   | 10        | 1.22%   |
| OPNsense 25.7.9   | 9         | 1.1%    |
| OPNsense 25.1.10  | 9         | 1.1%    |
| OPNsense 24.7.11  | 9         | 1.1%    |
| OPNsense 23.7.7   | 9         | 1.1%    |
| OPNsense 22.1     | 9         | 1.1%    |
| OPNsense 25.7.6   | 8         | 0.98%   |
| OPNsense 24.1.4   | 8         | 0.98%   |
| OPNsense 22.7.10  | 8         | 0.98%   |
| OPNsense 21.7.7   | 8         | 0.98%   |
| helloSystem 0.5.0 | 8         | 0.98%   |
| OPNsense 25.7.2   | 7         | 0.86%   |
| OPNsense 25.7.1   | 7         | 0.86%   |
| OPNsense 25.1.4   | 7         | 0.86%   |
| OPNsense 25.1.12  | 7         | 0.86%   |
| OPNsense 24.7.9   | 7         | 0.86%   |
| OPNsense 24.7.8   | 7         | 0.86%   |
| OPNsense 24.7.6   | 7         | 0.86%   |
| OPNsense 24.7.5   | 7         | 0.86%   |
| OPNsense 23.7.12  | 7         | 0.86%   |
| OPNsense 22.7.6   | 7         | 0.86%   |
| OPNsense 22.1.6   | 7         | 0.86%   |
| OPNsense 25.7     | 6         | 0.73%   |
| OPNsense 25.1     | 6         | 0.73%   |
| OPNsense 24.7.7   | 6         | 0.73%   |
| OPNsense 24.7.4   | 6         | 0.73%   |
| OPNsense 24.7.10  | 6         | 0.73%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 422       | 71.04%  |
| FreeBSD     | 93        | 15.66%  |
| helloSystem | 39        | 6.57%   |
| OpenBSD     | 14        | 2.36%   |
| GhostBSD    | 7         | 1.18%   |
| TrueNAS     | 5         | 0.84%   |
| NomadBSD    | 5         | 0.84%   |
| NetBSD      | 3         | 0.51%   |
| XigmaNAS    | 2         | 0.34%   |
| FreeNAS     | 2         | 0.34%   |
| FuguIta     | 1         | 0.17%   |
| ClonOS      | 1         | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 588       | 99.16%  |
| arm64 | 3         | 0.51%   |
| i386  | 2         | 0.34%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 463       | 77.17%  |
| helloDesktop | 49        | 8.17%   |
| XFCE         | 19        | 3.17%   |
| KDE5         | 17        | 2.83%   |
| TWM          | 10        | 1.67%   |
| GNOME        | 10        | 1.67%   |
| MATE         | 6         | 1%      |
| i3           | 6         | 1%      |
| Openbox      | 4         | 0.67%   |
| fvwm         | 4         | 0.67%   |
| Fluxbox      | 2         | 0.33%   |
| xinitrc      | 1         | 0.17%   |
| wlroots      | 1         | 0.17%   |
| sway         | 1         | 0.17%   |
| Picom        | 1         | 0.17%   |
| LXQt         | 1         | 0.17%   |
| Lumina       | 1         | 0.17%   |
| KDE6         | 1         | 0.17%   |
| KDE          | 1         | 0.17%   |
| Budgie       | 1         | 0.17%   |
| AwesomeWM    | 1         | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 470       | 78.86%  |
| X11     | 118       | 19.8%   |
| Wayland | 8         | 1.34%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 498       | 83.42%  |
| SLiM    | 45        | 7.54%   |
| SDDM    | 24        | 4.02%   |
| LightDM | 18        | 3.02%   |
| XDM     | 5         | 0.84%   |
| GDM     | 4         | 0.67%   |
| Ly      | 2         | 0.34%   |
| PCDM    | 1         | 0.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 454       | 74.79%  |
| C               | 71        | 11.7%   |
| en_US           | 50        | 8.24%   |
| en_AU           | 25        | 4.12%   |
| fr_FR           | 2         | 0.33%   |
| ru_RU           | 1         | 0.16%   |
| fr              | 1         | 0.16%   |
| en_AU.US-ASCII  | 1         | 0.16%   |
| en_AU.ISO8859-1 | 1         | 0.16%   |
| en              | 1         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 533       | 89.73%  |
| BIOS | 61        | 10.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Zfs    | 313       | 51.48%  |
| Ufs    | 265       | 43.59%  |
| Ffs    | 15        | 2.47%   |
| Cd9660 | 15        | 2.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 566       | 95.45%  |
| MBR     | 24        | 4.05%   |
| Unknown | 2         | 0.34%   |
| BSD     | 1         | 0.17%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 99        | 16.69%  |
| Lenovo                               | 72        | 12.14%  |
| Dell                                 | 70        | 11.8%   |
| Hewlett-Packard                      | 58        | 9.78%   |
| ASUSTek Computer                     | 33        | 5.56%   |
| Intel                                | 32        | 5.4%    |
| Protectli                            | 30        | 5.06%   |
| Gigabyte Technology                  | 29        | 4.89%   |
| Techvision                           | 14        | 2.36%   |
| ASRock                               | 13        | 2.19%   |
| Sophos                               | 11        | 1.85%   |
| Apple                                | 11        | 1.85%   |
| AMI                                  | 11        | 1.85%   |
| MSI                                  | 10        | 1.69%   |
| Acer                                 | 8         | 1.35%   |
| Supermicro                           | 7         | 1.18%   |
| PC Engines                           | 5         | 0.84%   |
| AZW                                  | 5         | 0.84%   |
| Toshiba                              | 4         | 0.67%   |
| Shuttle                              | 4         | 0.67%   |
| Shenzhen Meigao Electronic Equipment | 4         | 0.67%   |
| MW                                   | 4         | 0.67%   |
| Inventec                             | 3         | 0.51%   |
| Deciso                               | 3         | 0.51%   |
| CWWK                                 | 3         | 0.51%   |
| Raspberry Pi Foundation              | 2         | 0.34%   |
| Framework                            | 2         | 0.34%   |
| Citrix                               | 2         | 0.34%   |
| CheckPoint                           | 2         | 0.34%   |
| BESSTAR Tech                         | 2         | 0.34%   |
| AMD                                  | 2         | 0.34%   |
| ZOTAC                                | 1         | 0.17%   |
| YANYU                                | 1         | 0.17%   |
| Yanling                              | 1         | 0.17%   |
| Winston Marriot                      | 1         | 0.17%   |
| WeiBu                                | 1         | 0.17%   |
| Unknown                              | 1         | 0.17%   |
| TYAN Computer                        | 1         | 0.17%   |
| Trigkey                              | 1         | 0.17%   |
| Timi                                 | 1         | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 100       | 16.86%  |
| Techvision TVI7309X                               | 14        | 2.36%   |
| Protectli FW4B                                    | 13        | 2.19%   |
| Dell OptiPlex 9020                                | 12        | 2.02%   |
| HP t730 Thin Client                               | 11        | 1.85%   |
| AMI Aptio CRB                                     | 10        | 1.69%   |
| Sophos XG                                         | 8         | 1.35%   |
| Dell OptiPlex 7050                                | 7         | 1.18%   |
| Protectli VP2410                                  | 6         | 1.01%   |
| Dell OptiPlex 7040                                | 5         | 0.84%   |
| Supermicro Super Server                           | 4         | 0.67%   |
| Shenzhen Meigao Electronic Equipment Venus series | 4         | 0.67%   |
| Protectli FW2B                                    | 4         | 0.67%   |
| MW GMLK-2_5G4L                                    | 4         | 0.67%   |
| Intel MAHOBAY                                     | 4         | 0.67%   |
| HP ProLiant MicroServer                           | 4         | 0.67%   |
| Dell PowerEdge R320                               | 4         | 0.67%   |
| Sophos SG                                         | 3         | 0.51%   |
| PC Engines APU2                                   | 3         | 0.51%   |
| MSI PRO ADL-U Cubi 5 (MS-B0A8)                    | 3         | 0.51%   |
| HP ProDesk 400 G4 SFF                             | 3         | 0.51%   |
| HP EliteDesk 800 G2 DM 35W                        | 3         | 0.51%   |
| Dell Wyse 5070 Thin Client                        | 3         | 0.51%   |
| ASUS All Series                                   | 3         | 0.51%   |
| RPi Raspberry Pi                                  | 2         | 0.34%   |
| Protectli FW4C                                    | 2         | 0.34%   |
| MSI MS-7C94                                       | 2         | 0.34%   |
| Lenovo ThinkCentre M93p 10AAS2A100                | 2         | 0.34%   |
| Lenovo ThinkCentre M720q 10T8S6UW00               | 2         | 0.34%   |
| Lenovo ThinkCentre M720q 10T8S1Y610               | 2         | 0.34%   |
| Lenovo ThinkCentre M720q 10T7008UAU               | 2         | 0.34%   |
| Lenovo ThinkCentre M700 10HYS0Q400                | 2         | 0.34%   |
| Inventec D CLASS                                  | 2         | 0.34%   |
| Intel QHSW02                                      | 2         | 0.34%   |
| Intel Q3XXG4-P V1.0                               | 2         | 0.34%   |
| Intel NUC9i7QNX                                   | 2         | 0.34%   |
| Intel NUC10i5FNH                                  | 2         | 0.34%   |
| HP ProLiant MicroServer Gen8                      | 2         | 0.34%   |
| HP ProDesk 600 G4 SFF                             | 2         | 0.34%   |
| HP EliteDesk 800 G6 Small Form Factor PC          | 2         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 100       | 16.86%  |
| Dell OptiPlex                              | 43        | 7.25%   |
| Lenovo ThinkPad                            | 30        | 5.06%   |
| Lenovo ThinkCentre                         | 29        | 4.89%   |
| Techvision TVI7309X                        | 14        | 2.36%   |
| Protectli FW4B                             | 13        | 2.19%   |
| HP t730                                    | 11        | 1.85%   |
| HP ProLiant                                | 11        | 1.85%   |
| HP EliteDesk                               | 11        | 1.85%   |
| AMI Aptio                                  | 10        | 1.69%   |
| Dell PowerEdge                             | 9         | 1.52%   |
| Sophos XG                                  | 8         | 1.35%   |
| HP ProDesk                                 | 8         | 1.35%   |
| ASUS PRIME                                 | 8         | 1.35%   |
| Protectli VP2410                           | 6         | 1.01%   |
| ASUS ROG                                   | 6         | 1.01%   |
| Acer Veriton                               | 5         | 0.84%   |
| Supermicro Super                           | 4         | 0.67%   |
| Shenzhen Meigao Electronic Equipment Venus | 4         | 0.67%   |
| Protectli FW2B                             | 4         | 0.67%   |
| MW GMLK-2                                  | 4         | 0.67%   |
| MSI PRO                                    | 4         | 0.67%   |
| Lenovo IdeaPad                             | 4         | 0.67%   |
| Intel MAHOBAY                              | 4         | 0.67%   |
| HP Compaq                                  | 4         | 0.67%   |
| Dell Inspiron                              | 4         | 0.67%   |
| Sophos SG                                  | 3         | 0.51%   |
| PC Engines APU2                            | 3         | 0.51%   |
| HP EliteBook                               | 3         | 0.51%   |
| Gigabyte Z790                              | 3         | 0.51%   |
| Dell XPS                                   | 3         | 0.51%   |
| Dell Wyse                                  | 3         | 0.51%   |
| Dell Precision                             | 3         | 0.51%   |
| ASUS All                                   | 3         | 0.51%   |
| Toshiba Satellite                          | 2         | 0.34%   |
| RPi Raspberry                              | 2         | 0.34%   |
| Protectli FW4C                             | 2         | 0.34%   |
| MSI MS-7C94                                | 2         | 0.34%   |
| Lenovo ThinkStation                        | 2         | 0.34%   |
| Inventec D                                 | 2         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2023    | 82        | 13.83%  |
| 2018    | 57        | 9.61%   |
| 2022    | 52        | 8.77%   |
| 2021    | 44        | 7.42%   |
| 2020    | 40        | 6.75%   |
| 2015    | 39        | 6.58%   |
| 2016    | 37        | 6.24%   |
| 2014    | 35        | 5.9%    |
| 2019    | 34        | 5.73%   |
| 2024    | 33        | 5.56%   |
| 2013    | 28        | 4.72%   |
| 2017    | 25        | 4.22%   |
| 2012    | 24        | 4.05%   |
| 2011    | 17        | 2.87%   |
| 2025    | 12        | 2.02%   |
| 2010    | 9         | 1.52%   |
| 2009    | 9         | 1.52%   |
| Unknown | 7         | 1.18%   |
| 2008    | 5         | 0.84%   |
| 2007    | 3         | 0.51%   |
| 2006    | 1         | 0.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 409       | 68.97%  |
| Notebook       | 80        | 13.49%  |
| Mini pc        | 60        | 10.12%  |
| Server         | 22        | 3.71%   |
| Firewall       | 12        | 2.02%   |
| All in one     | 4         | 0.67%   |
| Convertible    | 3         | 0.51%   |
| System on chip | 2         | 0.34%   |
| Tablet         | 1         | 0.17%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 576       | 97.13%  |
| Yes  | 17        | 2.87%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 224       | 36.66%  |
| 16.01-24.0      | 204       | 33.39%  |
| 4.01-8.0        | 70        | 11.46%  |
| 32.01-64.0      | 60        | 9.82%   |
| 64.01-256.0     | 26        | 4.26%   |
| 2.01-3.0        | 13        | 2.13%   |
| 24.01-32.0      | 6         | 0.98%   |
| 3.01-4.0        | 3         | 0.49%   |
| 1.01-2.0        | 2         | 0.33%   |
| 0.51-1.0        | 2         | 0.33%   |
| More than 256.0 | 1         | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 241       | 39.31%  |
| 0.51-1.0   | 239       | 38.99%  |
| 1.01-2.0   | 82        | 13.38%  |
| 2.01-3.0   | 20        | 3.26%   |
| 4.01-8.0   | 12        | 1.96%   |
| 3.01-4.0   | 6         | 0.98%   |
| 8.01-16.0  | 5         | 0.82%   |
| Unknown    | 3         | 0.49%   |
| 16.01-24.0 | 2         | 0.33%   |
| 32.01-64.0 | 1         | 0.16%   |
| 24.01-32.0 | 1         | 0.16%   |
| 0          | 1         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 366       | 59.03%  |
| 0      | 153       | 24.68%  |
| 2      | 51        | 8.23%   |
| 3      | 23        | 3.71%   |
| 4      | 12        | 1.94%   |
| 5      | 5         | 0.81%   |
| 8      | 3         | 0.48%   |
| 7      | 3         | 0.48%   |
| 6      | 2         | 0.32%   |
| 18     | 1         | 0.16%   |
| 10     | 1         | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 512       | 86.05%  |
| Yes       | 83        | 13.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 572       | 96.46%  |
| No        | 21        | 3.54%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 401       | 67.51%  |
| Yes       | 193       | 32.49%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 442       | 73.91%  |
| Yes       | 156       | 26.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Australia | 593       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sydney         | 177       | 27.7%   |
| Melbourne      | 138       | 21.6%   |
| Brisbane       | 78        | 12.21%  |
| Perth          | 67        | 10.49%  |
| Adelaide       | 38        | 5.95%   |
| Canberra       | 19        | 2.97%   |
| Nyngan         | 14        | 2.19%   |
| Morwell        | 6         | 0.94%   |
| Hobart         | 5         | 0.78%   |
| Geelong        | 5         | 0.78%   |
| Launceston     | 4         | 0.63%   |
| Kooyong        | 4         | 0.63%   |
| Roxby Downs    | 3         | 0.47%   |
| Blackburn      | 3         | 0.47%   |
| Warrnambool    | 2         | 0.31%   |
| Townsville     | 2         | 0.31%   |
| Southport      | 2         | 0.31%   |
| Ryde           | 2         | 0.31%   |
| Port Fairy     | 2         | 0.31%   |
| Marrickville   | 2         | 0.31%   |
| Macquarie Park | 2         | 0.31%   |
| Longreach      | 2         | 0.31%   |
| Kellyville     | 2         | 0.31%   |
| Ipswich        | 2         | 0.31%   |
| Gold Coast     | 2         | 0.31%   |
| East Malvern   | 2         | 0.31%   |
| Burwood        | 2         | 0.31%   |
| Bundaberg      | 2         | 0.31%   |
| Unknown        | 2         | 0.31%   |
| Yallourn       | 1         | 0.16%   |
| Wollongong     | 1         | 0.16%   |
| Whitebridge    | 1         | 0.16%   |
| Wheelers Hill  | 1         | 0.16%   |
| Warragul       | 1         | 0.16%   |
| Wallan         | 1         | 0.16%   |
| Two Wells      | 1         | 0.16%   |
| South Yarra    | 1         | 0.16%   |
| Shell Cove     | 1         | 0.16%   |
| Rosanna        | 1         | 0.16%   |
| Ringwood       | 1         | 0.16%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 97        | 167    | 17.14%  |
| WDC                 | 54        | 127    | 9.54%   |
| Seagate             | 52        | 96     | 9.19%   |
| Crucial             | 48        | 70     | 8.48%   |
| SanDisk             | 35        | 48     | 6.18%   |
| Kingston            | 33        | 43     | 5.83%   |
| Toshiba             | 31        | 44     | 5.48%   |
| Intel               | 28        | 47     | 4.95%   |
| China               | 16        | 18     | 2.83%   |
| Hoodisk             | 14        | 26     | 2.47%   |
| Micron Technology   | 12        | 14     | 2.12%   |
| SPCC                | 11        | 19     | 1.94%   |
| A-DATA Technology   | 9         | 14     | 1.59%   |
| SK hynix            | 8         | 16     | 1.41%   |
| OCZ                 | 8         | 9      | 1.41%   |
| Transcend           | 6         | 11     | 1.06%   |
| Silicon Motion      | 6         | 7      | 1.06%   |
| Gigabyte Technology | 6         | 7      | 1.06%   |
| ShiJi               | 5         | 8      | 0.88%   |
| Protectli           | 5         | 5      | 0.88%   |
| Patriot             | 5         | 8      | 0.88%   |
| Apacer              | 5         | 7      | 0.88%   |
| Phison              | 4         | 5      | 0.71%   |
| NVMe                | 4         | 5      | 0.71%   |
| Hitachi             | 4         | 8      | 0.71%   |
| Hewlett-Packard     | 4         | 8      | 0.71%   |
| FORESEE             | 4         | 7      | 0.71%   |
| HGST                | 3         | 4      | 0.53%   |
| Dogfish             | 3         | 4      | 0.53%   |
| Apple               | 3         | 3      | 0.53%   |
| LITEONIT            | 2         | 2      | 0.35%   |
| Lenovo              | 2         | 2      | 0.35%   |
| KIOXIA              | 2         | 2      | 0.35%   |
| KingDian            | 2         | 2      | 0.35%   |
| Fanxiang            | 2         | 2      | 0.35%   |
| Corsair             | 2         | 3      | 0.35%   |
| BIWIN               | 2         | 2      | 0.35%   |
| ZOTAC               | 1         | 1      | 0.18%   |
| YMTC                | 1         | 2      | 0.18%   |
| XUNZHE              | 1         | 2      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Hoodisk SSD 128GB                           | 8         | 1.32%   |
| Crucial CT250MX500SSD1 250GB                | 8         | 1.32%   |
| Samsung SSD 850 EVO 500GB                   | 7         | 1.15%   |
| Kingston SA400S37240G 240GB                 | 6         | 0.99%   |
| Samsung SSD 970 EVO Plus 500GB              | 5         | 0.82%   |
| Samsung SSD 870 EVO 250GB                   | 5         | 0.82%   |
| Kingston SA400S37120G 120GB                 | 5         | 0.82%   |
| Crucial CT500MX500SSD1 500GB                | 5         | 0.82%   |
| Crucial CT250P2SSD8 250GB                   | 5         | 0.82%   |
| Samsung SSD 870 EVO 500GB                   | 4         | 0.66%   |
| Samsung SSD 860 EVO 500GB                   | 4         | 0.66%   |
| Samsung SSD 840 EVO 120GB                   | 4         | 0.66%   |
| Kingston SA400S37480G 480GB                 | 4         | 0.66%   |
| WDC WDS250G2B0A-00SM50 250GB                | 3         | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB                | 3         | 0.49%   |
| WDC WDS120G2G0B-00EPW0 120GB                | 3         | 0.49%   |
| WDC WD30EFRX-68EUZN0 3TB                    | 3         | 0.49%   |
| Toshiba THNSF5256GPUK 256GB                 | 3         | 0.49%   |
| Seagate ST500LM021-1KJ152 500GB             | 3         | 0.49%   |
| Seagate ST1000DM010-2EP102 1TB              | 3         | 0.49%   |
| Seagate FireCuda 520 SSD ZP500GM30002 500GB | 3         | 0.49%   |
| Samsung SSD 980 500GB                       | 3         | 0.49%   |
| Samsung SSD 970 EVO Plus 250GB              | 3         | 0.49%   |
| Samsung SSD 840 EVO 250GB                   | 3         | 0.49%   |
| Samsung MZ7PD256HCGM-000H7 256GB            | 3         | 0.49%   |
| Micron MTFDDAK256MAM-1K1 256GB              | 3         | 0.49%   |
| Intel SSDSCKKW240H6 240GB                   | 3         | 0.49%   |
| Hoodisk SSD 32GB                            | 3         | 0.49%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB            | 3         | 0.49%   |
| Crucial CT500P3SSD8 500GB                   | 3         | 0.49%   |
| Crucial CT480BX500SSD1 480GB                | 3         | 0.49%   |
| Crucial CT480BX200SSD1 480GB                | 3         | 0.49%   |
| Crucial CT240BX500SSD1 240GB                | 3         | 0.49%   |
| Crucial CT1000P3SSD8 1TB                    | 3         | 0.49%   |
| Crucial CT1000BX500SSD1 1TB                 | 3         | 0.49%   |
| China YSE128GTLCW-SBC-2 128GB               | 3         | 0.49%   |
| China SATA SSD 16GB                         | 3         | 0.49%   |
| A-DATA IM2S3134N-064GM 64GB                 | 3         | 0.49%   |
| WDC WDS480G2G0A-00JH30 480GB                | 2         | 0.33%   |
| WDC WD40EFRX-68WT0N0 4TB                    | 2         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 48        | 91     | 36.36%  |
| WDC                 | 40        | 103    | 30.3%   |
| Toshiba             | 17        | 26     | 12.88%  |
| Samsung Electronics | 4         | 6      | 3.03%   |
| Hitachi             | 4         | 8      | 3.03%   |
| Hewlett-Packard     | 4         | 8      | 3.03%   |
| NVMe                | 3         | 3      | 2.27%   |
| HGST                | 3         | 4      | 2.27%   |
| WLW                 | 1         | 1      | 0.76%   |
| Western             | 1         | 3      | 0.76%   |
| Synology            | 1         | 3      | 0.76%   |
| Maxtor              | 1         | 1      | 0.76%   |
| Jetflash            | 1         | 1      | 0.76%   |
| HPE                 | 1         | 2      | 0.76%   |
| Fujitsu             | 1         | 1      | 0.76%   |
| China               | 1         | 1      | 0.76%   |
| Apple               | 1         | 1      | 0.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 66        | 115    | 19.76%  |
| SanDisk             | 35        | 48     | 10.48%  |
| Crucial             | 34        | 50     | 10.18%  |
| Kingston            | 28        | 37     | 8.38%   |
| Intel               | 25        | 44     | 7.49%   |
| China               | 15        | 17     | 4.49%   |
| Hoodisk             | 14        | 26     | 4.19%   |
| WDC                 | 12        | 19     | 3.59%   |
| Micron Technology   | 10        | 12     | 2.99%   |
| SPCC                | 8         | 12     | 2.4%    |
| OCZ                 | 8         | 9      | 2.4%    |
| A-DATA Technology   | 7         | 7      | 2.1%    |
| Transcend           | 6         | 11     | 1.8%    |
| Toshiba             | 6         | 9      | 1.8%    |
| Protectli           | 5         | 5      | 1.5%    |
| Apacer              | 5         | 7      | 1.5%    |
| SK hynix            | 3         | 7      | 0.9%    |
| ShiJi               | 3         | 5      | 0.9%    |
| Patriot             | 3         | 5      | 0.9%    |
| FORESEE             | 3         | 6      | 0.9%    |
| Dogfish             | 3         | 4      | 0.9%    |
| Seagate             | 2         | 2      | 0.6%    |
| Phison              | 2         | 2      | 0.6%    |
| NVMe                | 2         | 2      | 0.6%    |
| LITEONIT            | 2         | 2      | 0.6%    |
| KingDian            | 2         | 2      | 0.6%    |
| Gigabyte Technology | 2         | 2      | 0.6%    |
| Corsair             | 2         | 3      | 0.6%    |
| ZOTAC               | 1         | 1      | 0.3%    |
| XUNZHE              | 1         | 2      | 0.3%    |
| Wicgtyp             | 1         | 1      | 0.3%    |
| Vaseky              | 1         | 4      | 0.3%    |
| SATADOM             | 1         | 1      | 0.3%    |
| Qunion              | 1         | 4      | 0.3%    |
| Plextor             | 1         | 2      | 0.3%    |
| OSCOO               | 1         | 2      | 0.3%    |
| Netac               | 1         | 1      | 0.3%    |
| LITEON              | 1         | 3      | 0.3%    |
| Lenovo              | 1         | 1      | 0.3%    |
| Kston               | 1         | 1      | 0.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 298       | 506    | 58.89%  |
| HDD  | 106       | 263    | 20.95%  |
| NVMe | 102       | 151    | 20.16%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 376       | 769    | 78.66%  |
| NVMe | 102       | 151    | 21.34%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 323       | 555    | 76.18%  |
| 0.51-1.0   | 47        | 69     | 11.08%  |
| 1.01-2.0   | 23        | 52     | 5.42%   |
| 3.01-4.0   | 16        | 48     | 3.77%   |
| 4.01-10.0  | 6         | 19     | 1.42%   |
| 2.01-3.0   | 5         | 15     | 1.18%   |
| 10.01-20.0 | 3         | 7      | 0.71%   |
| 20.01-50.0 | 1         | 4      | 0.24%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 275       | 44.64%  |
| 251-500        | 123       | 19.97%  |
| 1-20           | 55        | 8.93%   |
| 51-100         | 53        | 8.6%    |
| 501-1000       | 50        | 8.12%   |
| 21-50          | 40        | 6.49%   |
| 1001-2000      | 13        | 2.11%   |
| More than 3000 | 4         | 0.65%   |
| 2001-3000      | 2         | 0.32%   |
| Unknown        | 1         | 0.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 546       | 87.92%  |
| 21-50          | 45        | 7.25%   |
| 51-100         | 14        | 2.25%   |
| 101-250        | 10        | 1.61%   |
| 1001-2000      | 3         | 0.48%   |
| More than 3000 | 1         | 0.16%   |
| 251-500        | 1         | 0.16%   |
| Unknown        | 1         | 0.16%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB              | 2         | 5      | 3.51%   |
| Seagate ST500LM021-1KJ152 500GB           | 2         | 2      | 3.51%   |
| Intel SSDSC2BW120H6 120GB                 | 2         | 4      | 3.51%   |
| WDC WDS480G2G0A-00JH30 480GB              | 1         | 1      | 1.75%   |
| WDC WD40EZRZ-00WN9B0 4TB                  | 1         | 1      | 1.75%   |
| WDC WD30EFRX-68EUZN0 3TB                  | 1         | 1      | 1.75%   |
| WDC WD20EZRX-00D8PB0 2TB                  | 1         | 2      | 1.75%   |
| WDC WD20EARX-008FB0 2TB                   | 1         | 4      | 1.75%   |
| WDC WD20EARS-00MVWB0 2TB                  | 1         | 1      | 1.75%   |
| Toshiba THNSNF128GMCS 128GB               | 1         | 1      | 1.75%   |
| Toshiba MK5059GSX 500GB                   | 1         | 1      | 1.75%   |
| Toshiba KSG60ZSE256G SATA 256GB           | 1         | 1      | 1.75%   |
| Seagate ST9160827AS 160GB                 | 1         | 2      | 1.75%   |
| Seagate ST9160314AS 160GB                 | 1         | 1      | 1.75%   |
| Seagate ST500LT012-1DG142 500GB           | 1         | 1      | 1.75%   |
| Seagate ST3250310AS 250GB                 | 1         | 1      | 1.75%   |
| Seagate ST240FN0021 240GB                 | 1         | 1      | 1.75%   |
| Seagate ST2000LM015-2E8174 2TB            | 1         | 1      | 1.75%   |
| Seagate ST2000LM003 HN-M201RAD 2TB        | 1         | 1      | 1.75%   |
| Seagate ST2000DL003-9VT166 2TB            | 1         | 1      | 1.75%   |
| Seagate ST1000DM003-1CH162 1TB            | 1         | 1      | 1.75%   |
| SanDisk SSD PLUS 240 GB                   | 1         | 1      | 1.75%   |
| SanDisk SDSSDA240G 240GB                  | 1         | 1      | 1.75%   |
| SanDisk SDSSDA120G 120GB                  | 1         | 1      | 1.75%   |
| Samsung Electronics SSD 870 EVO 500GB     | 1         | 1      | 1.75%   |
| Samsung Electronics SSD 870 EVO 1TB       | 1         | 1      | 1.75%   |
| Samsung Electronics SP0812C 80GB          | 1         | 1      | 1.75%   |
| Samsung Electronics HM500LI 500GB         | 1         | 2      | 1.75%   |
| Phison SATA SSD 32GB                      | 1         | 1      | 1.75%   |
| Patriot Burst Elite 120GB                 | 1         | 2      | 1.75%   |
| OCZ VERTEX3 120GB                         | 1         | 1      | 1.75%   |
| OCZ OCTANE 128GB                          | 1         | 1      | 1.75%   |
| Micron Technology C400-MTFDDAT064MAM 64GB | 1         | 1      | 1.75%   |
| LITEON LCH-128V2S-11 2.5 7mm 128GB        | 1         | 3      | 1.75%   |
| Kingston SNS4151S316G 16GB                | 1         | 1      | 1.75%   |
| Kingston SA400S37480G 480GB               | 1         | 1      | 1.75%   |
| Kingston SA400S37120G 120GB               | 1         | 1      | 1.75%   |
| Intel SSDSC2BF180A4L 180GB                | 1         | 1      | 1.75%   |
| Intel SSDSC2BB480G7 480GB                 | 1         | 1      | 1.75%   |
| Intel SSDSA2BW120G3H 120GB                | 1         | 1      | 1.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 19.64%  |
| WDC                 | 7         | 15     | 12.5%   |
| Intel               | 5         | 7      | 8.93%   |
| Samsung Electronics | 4         | 5      | 7.14%   |
| Toshiba             | 3         | 3      | 5.36%   |
| SanDisk             | 3         | 3      | 5.36%   |
| Kingston            | 3         | 3      | 5.36%   |
| OCZ                 | 2         | 2      | 3.57%   |
| Hitachi             | 2         | 2      | 3.57%   |
| HGST                | 2         | 3      | 3.57%   |
| Crucial             | 2         | 3      | 3.57%   |
| Apple               | 2         | 2      | 3.57%   |
| Apacer              | 2         | 3      | 3.57%   |
| Phison              | 1         | 1      | 1.79%   |
| Patriot             | 1         | 2      | 1.79%   |
| Micron Technology   | 1         | 1      | 1.79%   |
| LITEON              | 1         | 3      | 1.79%   |
| HPE                 | 1         | 2      | 1.79%   |
| HP Phison           | 1         | 4      | 1.79%   |
| Hewlett-Packard     | 1         | 1      | 1.79%   |
| BIWIN               | 1         | 1      | 1.79%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 41.67%  |
| WDC                 | 4         | 9      | 16.67%  |
| Samsung Electronics | 2         | 3      | 8.33%   |
| Hitachi             | 2         | 2      | 8.33%   |
| HGST                | 2         | 3      | 8.33%   |
| Toshiba             | 1         | 1      | 4.17%   |
| HPE                 | 1         | 2      | 4.17%   |
| Hewlett-Packard     | 1         | 1      | 4.17%   |
| Apple               | 1         | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 32        | 45     | 57.14%  |
| HDD  | 24        | 33     | 42.86%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB | 1         | 1      | 33.33%  |
| Patriot M.2 P310 240GB       | 1         | 1      | 33.33%  |
| China SSD 256GB              | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Patriot | 1         | 1      | 33.33%  |
| China   | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 410       | 828    | 85.77%  |
| Malfunc  | 56        | 78     | 11.72%  |
| Detected | 9         | 11     | 1.88%   |
| Failed   | 3         | 3      | 0.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 467       | 59.04%  |
| AMD                                     | 62        | 7.84%   |
| Samsung Electronics                     | 55        | 6.95%   |
| Silicon Motion                          | 23        | 2.91%   |
| SanDisk                                 | 22        | 2.78%   |
| Micron/Crucial Technology               | 21        | 2.65%   |
| Phison Electronics                      | 18        | 2.28%   |
| Toshiba                                 | 14        | 1.77%   |
| Micron Technology                       | 14        | 1.77%   |
| Broadcom / LSI                          | 14        | 1.77%   |
| Kingston Technology Company             | 12        | 1.52%   |
| MAXIO Technology (Hangzhou)             | 11        | 1.39%   |
| SK hynix                                | 8         | 1.01%   |
| Realtek Semiconductor                   | 6         | 0.76%   |
| Hosin Global Electronics                | 5         | 0.63%   |
| Hewlett-Packard                         | 4         | 0.51%   |
| Yangtze Memory Technologies             | 3         | 0.38%   |
| Transcend                               | 3         | 0.38%   |
| Seagate Technology                      | 3         | 0.38%   |
| Nvidia                                  | 3         | 0.38%   |
| ASMedia Technology                      | 3         | 0.38%   |
| ADATA Technology                        | 3         | 0.38%   |
| Shenzhen Unionmemory Information System | 2         | 0.25%   |
| Shenzhen Longsys Electronics            | 2         | 0.25%   |
| Netac Technology                        | 2         | 0.25%   |
| Marvell Technology Group                | 2         | 0.25%   |
| Chelsio Communications                  | 2         | 0.25%   |
| Union Memory (Shenzhen)                 | 1         | 0.13%   |
| Silicon Image                           | 1         | 0.13%   |
| Red Hat                                 | 1         | 0.13%   |
| QLogic                                  | 1         | 0.13%   |
| Lenovo                                  | 1         | 0.13%   |
| JMicron Technology                      | 1         | 0.13%   |
| Adaptec                                 | 1         | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-N SATA AHCI Controller                                                 | 43        | 4.97%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 41        | 4.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 38        | 4.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 30        | 3.46%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 30        | 3.46%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 25        | 2.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 25        | 2.89%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 24        | 2.77%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 22        | 2.54%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 22        | 2.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 21        | 2.42%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 19        | 2.19%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 18        | 2.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 18        | 2.08%   |
| Intel SATA Controller [RAID mode]                                                       | 17        | 1.96%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 15        | 1.73%   |
| Intel Alder Lake-P SATA AHCI Controller                                                 | 13        | 1.5%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 12        | 1.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 12        | 1.39%   |
| AMD FCH IDE Controller                                                                  | 12        | 1.39%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 11        | 1.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 10        | 1.15%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 10        | 1.15%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 10        | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 10        | 1.15%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 9         | 1.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 8         | 0.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8         | 0.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 7         | 0.81%   |
| Micron 2550 NVMe SSD (DRAM-less)                                                        | 7         | 0.81%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 7         | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 7         | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7         | 0.81%   |
| Intel Atom Processor C3000 Series SATA Controller 1                                     | 6         | 0.69%   |
| Intel Atom Processor C3000 Series SATA Controller 0                                     | 6         | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6         | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6         | 0.69%   |
| Toshiba XG6 NVMe SSD Controller                                                         | 5         | 0.58%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 5         | 0.58%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                       | 5         | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 488       | 60.77%  |
| NVMe | 220       | 27.4%   |
| IDE  | 47        | 5.85%   |
| RAID | 34        | 4.23%   |
| SCSI | 8         | 1%      |
| SAS  | 6         | 0.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 515       | 86.85%  |
| AMD    | 74        | 12.48%  |
| ARM    | 3         | 0.51%   |
| QEMU   | 1         | 0.17%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel N100                               | 37        | 6.15%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 22        | 3.65%   |
| Intel Celeron N5105 @ 2.00GHz            | 20        | 3.32%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 15        | 2.49%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 11        | 1.83%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 11        | 1.83%   |
| Intel N150                               | 10        | 1.66%   |
| Intel Core i5-6500T CPU @ 2.50GHz        | 9         | 1.5%    |
| Intel Core i5-7500 CPU @ 3.40GHz         | 8         | 1.33%   |
| Intel Core i5-4570T CPU @ 2.90GHz        | 6         | 1%      |
| Intel Core i5-4570 CPU @ 3.20GHz         | 6         | 1%      |
| Intel Core i7-7700 CPU @ 3.60GHz         | 5         | 0.83%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 5         | 0.83%   |
| Intel Pentium Silver N6005 @ 2.00GHz     | 4         | 0.66%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 4         | 0.66%   |
| Intel Core i7-10700 CPU @ 2.90GHz        | 4         | 0.66%   |
| Intel Core i5-7400 CPU @ 3.00GHz         | 4         | 0.66%   |
| Intel Core i5-6400 CPU @ 2.70GHz         | 4         | 0.66%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 4         | 0.66%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 4         | 0.66%   |
| Intel Celeron CPU J3060 @ 1.60GHz        | 4         | 0.66%   |
| Intel 12th Gen Core i5-1240P             | 4         | 0.66%   |
| Intel 12th Gen Core i5-12400             | 4         | 0.66%   |
| Intel 12th Gen Core i3-1215U             | 4         | 0.66%   |
| AMD GX-412TC SOC                         | 4         | 0.66%   |
| Intel Pentium CPU G4560 @ 3.50GHz        | 3         | 0.5%    |
| Intel Core i7-9700T CPU @ 2.00GHz        | 3         | 0.5%    |
| Intel Core i7-8700 CPU @ 3.20GHz         | 3         | 0.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz        | 3         | 0.5%    |
| Intel Core i7-7500U CPU @ 2.70GHz        | 3         | 0.5%    |
| Intel Core i7-6700 CPU @ 3.40GHz         | 3         | 0.5%    |
| Intel Core i7-4790 CPU @ 3.60GHz         | 3         | 0.5%    |
| Intel Core i7-4770 CPU @ 3.40GHz         | 3         | 0.5%    |
| Intel Core i7-3770 CPU @ 3.40GHz         | 3         | 0.5%    |
| Intel Core i7-10750H CPU @ 2.60GHz       | 3         | 0.5%    |
| Intel Core i7-10510U CPU @ 1.80GHz       | 3         | 0.5%    |
| Intel Core i5-8500T CPU @ 2.10GHz        | 3         | 0.5%    |
| Intel Core i5-8400T CPU @ 1.70GHz        | 3         | 0.5%    |
| Intel Core i5-8250U CPU @ 1.60GHz        | 3         | 0.5%    |
| Intel Core i5-7200U CPU @ 2.50GHz        | 3         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 127       | 21.17%  |
| Intel Celeron           | 109       | 18.17%  |
| Other                   | 96        | 16%     |
| Intel Core i7           | 76        | 12.67%  |
| Intel Xeon              | 35        | 5.83%   |
| Intel Core i3           | 34        | 5.67%   |
| Intel Atom              | 19        | 3.17%   |
| AMD Ryzen 5             | 17        | 2.83%   |
| Intel Pentium           | 12        | 2%      |
| Intel Pentium Silver    | 7         | 1.17%   |
| Intel Core 2 Duo        | 7         | 1.17%   |
| AMD Ryzen 7             | 6         | 1%      |
| AMD Ryzen 3             | 6         | 1%      |
| AMD GX                  | 6         | 1%      |
| Intel Core 2 Quad       | 4         | 0.67%   |
| AMD Turion II Neo       | 4         | 0.67%   |
| AMD G                   | 4         | 0.67%   |
| AMD FX                  | 4         | 0.67%   |
| ARM Cortex              | 3         | 0.5%    |
| AMD Ryzen 9             | 3         | 0.5%    |
| Intel Pentium Gold      | 2         | 0.33%   |
| Intel Core              | 2         | 0.33%   |
| AMD Ryzen Embedded      | 2         | 0.33%   |
| AMD EPYC                | 2         | 0.33%   |
| AMD Athlon              | 2         | 0.33%   |
| Intel Xeon Silver       | 1         | 0.17%   |
| Intel Xeon Gold         | 1         | 0.17%   |
| Intel Pentium Dual-Core | 1         | 0.17%   |
| Intel Pentium 4         | 1         | 0.17%   |
| Intel Core i9           | 1         | 0.17%   |
| Intel Core Duo          | 1         | 0.17%   |
| AMD E2                  | 1         | 0.17%   |
| AMD Athlon X2           | 1         | 0.17%   |
| AMD A8                  | 1         | 0.17%   |
| AMD A6                  | 1         | 0.17%   |
| AMD A4                  | 1         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 324       | 54%     |
| 2       | 130       | 21.67%  |
| 6       | 51        | 8.5%    |
| 8       | 49        | 8.17%   |
| Unknown | 13        | 2.17%   |
| 12      | 9         | 1.5%    |
| 16      | 8         | 1.33%   |
| 10      | 6         | 1%      |
| 24      | 3         | 0.5%    |
| 32      | 2         | 0.33%   |
| 1       | 2         | 0.33%   |
| 64      | 1         | 0.17%   |
| 22      | 1         | 0.17%   |
| 18      | 1         | 0.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 579       | 97.64%  |
| 2       | 9         | 1.52%   |
| Unknown | 5         | 0.84%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 376       | 62.46%  |
| 2       | 213       | 35.38%  |
| Unknown | 13        | 2.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 122       | 20.44%  |
| KabyLake      | 85        | 14.24%  |
| Haswell       | 54        | 9.05%   |
| Silvermont    | 49        | 8.21%   |
| Skylake       | 48        | 8.04%   |
| IvyBridge     | 36        | 6.03%   |
| Goldmont plus | 30        | 5.03%   |
| SandyBridge   | 23        | 3.85%   |
| Broadwell     | 17        | 2.85%   |
| CometLake     | 15        | 2.51%   |
| Goldmont      | 14        | 2.35%   |
| Zen 3         | 11        | 1.84%   |
| Steamroller   | 11        | 1.84%   |
| Penryn        | 8         | 1.34%   |
| Zen 2         | 7         | 1.17%   |
| Zen           | 7         | 1.17%   |
| Westmere      | 7         | 1.17%   |
| Puma          | 7         | 1.17%   |
| Zen+          | 6         | 1.01%   |
| TigerLake     | 5         | 0.84%   |
| Nehalem       | 5         | 0.84%   |
| K10           | 5         | 0.84%   |
| Core          | 5         | 0.84%   |
| Bobcat        | 5         | 0.84%   |
| Piledriver    | 4         | 0.67%   |
| Bonnell       | 4         | 0.67%   |
| Jaguar        | 3         | 0.5%    |
| P6            | 1         | 0.17%   |
| NetBurst      | 1         | 0.17%   |
| K8 Hammer     | 1         | 0.17%   |
| Excavator     | 1         | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 437       | 72.23%  |
| AMD                        | 77        | 12.73%  |
| Nvidia                     | 51        | 8.43%   |
| Matrox Electronics Systems | 20        | 3.31%   |
| ASPEED Technology          | 17        | 2.81%   |
| Tseng Labs                 | 1         | 0.17%   |
| Silicon Motion             | 1         | 0.17%   |
| Red Hat                    | 1         | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-N [UHD Graphics]                                                        | 42        | 6.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 38        | 6.16%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 28        | 4.54%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 28        | 4.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 28        | 4.54%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 25        | 4.05%   |
| Intel JasperLake [UHD Graphics]                                                          | 25        | 4.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 19        | 3.08%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                                  | 17        | 2.76%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 17        | 2.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 2.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11        | 1.78%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 11        | 1.78%   |
| Intel Alder Lake-N [Intel Graphics]                                                      | 10        | 1.62%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 9         | 1.46%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 8         | 1.3%    |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 8         | 1.3%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 1.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 1.13%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 6         | 0.97%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 0.97%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                                  | 6         | 0.97%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 6         | 0.97%   |
| Matrox Electronics Systems MGA G200EH                                                    | 5         | 0.81%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 5         | 0.81%   |
| Matrox Electronics Systems G200eR2                                                       | 5         | 0.81%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 0.81%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5         | 0.81%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 0.81%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 0.65%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 4         | 0.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 0.65%   |
| Intel Skylake-S GT1 [HD Graphics 510]                                                    | 4         | 0.65%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4         | 0.65%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 0.65%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 4         | 0.65%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 4         | 0.65%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 0.65%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 4         | 0.65%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 401       | 67.17%  |
| 1 x AMD            | 62        | 10.39%  |
| 1 x Nvidia         | 33        | 5.53%   |
| Other              | 21        | 3.52%   |
| 1 x Matrox         | 19        | 3.18%   |
| Intel + Nvidia     | 16        | 2.68%   |
| 1 x ASPEED         | 16        | 2.68%   |
| Intel + AMD        | 12        | 2.01%   |
| 2 x Intel          | 8         | 1.34%   |
| 2 x AMD            | 2         | 0.34%   |
| 1 x Tseng Labs     | 1         | 0.17%   |
| 1 x Silicon Motion | 1         | 0.17%   |
| 1 x Red Hat        | 1         | 0.17%   |
| Nvidia + Matrox    | 1         | 0.17%   |
| Intel + ASPEED     | 1         | 0.17%   |
| AMD + Nvidia       | 1         | 0.17%   |
| AMD + Matrox       | 1         | 0.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 548       | 91.95%  |
| Unknown     | 25        | 4.19%   |
| Proprietary | 23        | 3.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 553       | 92.32%  |
| 1.01-2.0   | 14        | 2.34%   |
| 0.51-1.0   | 9         | 1.5%    |
| 7.01-8.0   | 8         | 1.34%   |
| 3.01-4.0   | 6         | 1%      |
| 0.01-0.5   | 6         | 1%      |
| 8.01-16.0  | 2         | 0.33%   |
| 5.01-6.0   | 1         | 0.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 11        | 10.38%  |
| BOE                     | 9         | 8.49%   |
| Dell                    | 8         | 7.55%   |
| ViewSonic               | 7         | 6.6%    |
| Acer                    | 7         | 6.6%    |
| Samsung Electronics     | 6         | 5.66%   |
| LG Display              | 6         | 5.66%   |
| Sharp                   | 4         | 3.77%   |
| Philips                 | 4         | 3.77%   |
| Lenovo                  | 4         | 3.77%   |
| Hewlett-Packard         | 4         | 3.77%   |
| Goldstar                | 4         | 3.77%   |
| ASUSTek Computer        | 4         | 3.77%   |
| Chimei Innolux          | 3         | 2.83%   |
| AOC                     | 3         | 2.83%   |
| Ancor Communications    | 3         | 2.83%   |
| Sony                    | 2         | 1.89%   |
| Panasonic               | 2         | 1.89%   |
| BenQ                    | 2         | 1.89%   |
| Apple                   | 2         | 1.89%   |
| ___                     | 1         | 0.94%   |
| Toshiba                 | 1         | 0.94%   |
| LG Philips              | 1         | 0.94%   |
| Konka                   | 1         | 0.94%   |
| InfoVision              | 1         | 0.94%   |
| CTO                     | 1         | 0.94%   |
| CSW                     | 1         | 0.94%   |
| CSO                     | 1         | 0.94%   |
| Compal                  | 1         | 0.94%   |
| Chi Mei Optoelectronics | 1         | 0.94%   |
| Unknown                 | 1         | 0.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| ViewSonic VA2026w VSC5020 1680x1050 430x270mm 20.0-inch              | 3         | 2.75%   |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch              | 2         | 1.83%   |
| Lenovo D27-30 LEN66B8 1920x1080 600x340mm 27.2-inch                  | 2         | 1.83%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch       | 2         | 1.83%   |
| ASUSTek Computer ROG XG279Q AUS278D 2560x1440 600x340mm 27.2-inch    | 2         | 1.83%   |
| ___ MY TV LED TV ___0101 1920x1080                                   | 1         | 0.92%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 700x390mm 31.5-inch            | 1         | 0.92%   |
| ViewSonic VG910s VSCDA18 1280x1024 380x300mm 19.1-inch               | 1         | 0.92%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 600x340mm 27.2-inch            | 1         | 0.92%   |
| ViewSonic VA1912w-3 VSC711C 1440x900 410x260mm 19.1-inch             | 1         | 0.92%   |
| Toshiba TV TSB010E 1920x1080 1040x590mm 47.1-inch                    | 1         | 0.92%   |
| Sony TV SNYB801 1360x768                                             | 1         | 0.92%   |
| Sony AVAMP SNY1F02 1280x720 800x450mm 36.1-inch                      | 1         | 0.92%   |
| Sharp LQ133T1JX03 SHP140F 2560x1440 290x170mm 13.2-inch              | 1         | 0.92%   |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 210x140mm 9.9-inch               | 1         | 0.92%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch    | 1         | 0.92%   |
| Samsung Electronics SyncMaster SAM056A 1680x1050 470x300mm 22.0-inch | 1         | 0.92%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch | 1         | 0.92%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch    | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SDC4445 1366x768 340x190mm 15.3-inch | 1         | 0.92%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch              | 1         | 0.92%   |
| Philips PHL 271S9 PHL0987 1920x1080 600x340mm 27.2-inch              | 1         | 0.92%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch              | 1         | 0.92%   |
| Philips PHL 221V8 PHLC211 1920x1080 480x270mm 21.7-inch              | 1         | 0.92%   |
| Panasonic TV MEIA0A4 1920x1080 698x392mm 31.5-inch                   | 1         | 0.92%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 340x190mm 15.3-inch          | 1         | 0.92%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 330x210mm 15.4-inch        | 1         | 0.92%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 1         | 0.92%   |
| LG Display LCD Monitor LGD04A9 1920x1080 310x170mm 13.9-inch         | 1         | 0.92%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x170mm 13.9-inch         | 1         | 0.92%   |
| LG Display LCD Monitor LGD046D 1920x1080 310x170mm 13.9-inch         | 1         | 0.92%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD01DD 1600x900 380x210mm 17.1-inch          | 1         | 0.92%   |
| Lenovo LEN T24i-10 LEN61CE 1920x1080 530x300mm 24.0-inch             | 1         | 0.92%   |
| Lenovo LCD Monitor LEN40C1 1280x720 220x130mm 10.1-inch              | 1         | 0.92%   |
| Konka TV_MONITOR KOA0030 2288x1430 1150x650mm 52.0-inch              | 1         | 0.92%   |
| InfoVision LCD Monitor IVO0536 1920x1080 290x170mm 13.2-inch         | 1         | 0.92%   |
| Hewlett-Packard W2072a HWP299F 1600x900 440x250mm 19.9-inch          | 1         | 0.92%   |
| Hewlett-Packard LCD Monitor HWP2915 1920x1080 510x290mm 23.1-inch    | 1         | 0.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 47        | 47%     |
| 2560x1440 (QHD)    | 12        | 12%     |
| 1366x768 (WXGA)    | 10        | 10%     |
| 1680x1050 (WSXGA+) | 6         | 6%      |
| 3840x2160 (4K)     | 5         | 5%      |
| 1920x1200 (WUXGA)  | 4         | 4%      |
| 1600x900 (HD+)     | 2         | 2%      |
| 1280x720 (HD)      | 2         | 2%      |
| 3840x1600          | 1         | 1%      |
| 3840x1080          | 1         | 1%      |
| 3440x1440          | 1         | 1%      |
| 2560x1600          | 1         | 1%      |
| 2560x1080          | 1         | 1%      |
| 2288x1430          | 1         | 1%      |
| 2048x1152          | 1         | 1%      |
| 1800x1200          | 1         | 1%      |
| 1440x900 (WXGA+)   | 1         | 1%      |
| 1360x768           | 1         | 1%      |
| 1280x800 (WXGA)    | 1         | 1%      |
| 1280x1024 (SXGA)   | 1         | 1%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 27      | 17        | 16.04%  |
| 15      | 16        | 15.09%  |
| 13      | 14        | 13.21%  |
| 24      | 9         | 8.49%   |
| 21      | 9         | 8.49%   |
| Unknown | 6         | 5.66%   |
| 23      | 5         | 4.72%   |
| 11      | 4         | 3.77%   |
| 31      | 3         | 2.83%   |
| 22      | 3         | 2.83%   |
| 20      | 3         | 2.83%   |
| 19      | 3         | 2.83%   |
| 17      | 2         | 1.89%   |
| 12      | 2         | 1.89%   |
| 52      | 1         | 0.94%   |
| 49      | 1         | 0.94%   |
| 47      | 1         | 0.94%   |
| 37      | 1         | 0.94%   |
| 36      | 1         | 0.94%   |
| 28      | 1         | 0.94%   |
| 16      | 1         | 0.94%   |
| 14      | 1         | 0.94%   |
| 10      | 1         | 0.94%   |
| 9       | 1         | 0.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 29        | 27.88%  |
| 301-350     | 26        | 25%     |
| 401-500     | 16        | 15.38%  |
| 201-300     | 14        | 13.46%  |
| Unknown     | 6         | 5.77%   |
| 601-700     | 5         | 4.81%   |
| 351-400     | 3         | 2.88%   |
| 1001-1500   | 3         | 2.88%   |
| 801-900     | 1         | 0.96%   |
| 701-800     | 1         | 0.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 74        | 78.72%  |
| 16/10   | 10        | 10.64%  |
| Unknown | 4         | 4.26%   |
| 3/2     | 2         | 2.13%   |
| 21/9    | 2         | 2.13%   |
| 5/4     | 1         | 1.06%   |
| 32/9    | 1         | 1.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 24        | 22.86%  |
| 301-350        | 17        | 16.19%  |
| 91-100         | 12        | 11.43%  |
| 81-90          | 10        | 9.52%   |
| 151-200        | 6         | 5.71%   |
| Unknown        | 6         | 5.71%   |
| 71-80          | 5         | 4.76%   |
| 51-60          | 4         | 3.81%   |
| 501-1000       | 4         | 3.81%   |
| 351-500        | 3         | 2.86%   |
| 101-110        | 3         | 2.86%   |
| 61-70          | 2         | 1.9%    |
| 41-50          | 2         | 1.9%    |
| 251-300        | 2         | 1.9%    |
| 121-130        | 2         | 1.9%    |
| 111-120        | 2         | 1.9%    |
| More than 1000 | 1         | 0.95%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 36        | 34.62%  |
| 121-160       | 26        | 25%     |
| 101-120       | 22        | 21.15%  |
| 161-240       | 11        | 10.58%  |
| Unknown       | 6         | 5.77%   |
| 1-50          | 2         | 1.92%   |
| More than 240 | 1         | 0.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 490       | 82.21%  |
| 1     | 94        | 15.77%  |
| 2     | 10        | 1.68%   |
| 3     | 2         | 0.34%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 478       | 59.68%  |
| Realtek Semiconductor             | 180       | 22.47%  |
| Broadcom                          | 43        | 5.37%   |
| Qualcomm Atheros                  | 33        | 4.12%   |
| TP-Link                           | 8         | 1%      |
| MediaTek                          | 7         | 0.87%   |
| U-Blox                            | 4         | 0.5%    |
| Mellanox Technologies             | 4         | 0.5%    |
| Sierra Wireless                   | 3         | 0.37%   |
| AMD                               | 3         | 0.37%   |
| Samsung Electronics               | 2         | 0.25%   |
| Ralink Technology                 | 2         | 0.25%   |
| Nvidia                            | 2         | 0.25%   |
| Marvell Technology Group          | 2         | 0.25%   |
| Lenovo                            | 2         | 0.25%   |
| IMC Networks                      | 2         | 0.25%   |
| Ericsson Business Mobile Networks | 2         | 0.25%   |
| Emulex                            | 2         | 0.25%   |
| D-Link System                     | 2         | 0.25%   |
| Chelsio Communications            | 2         | 0.25%   |
| Aquantia                          | 2         | 0.25%   |
| VIA Technologies                  | 1         | 0.12%   |
| TRENDnet                          | 1         | 0.12%   |
| Texas Instruments                 | 1         | 0.12%   |
| sipeed                            | 1         | 0.12%   |
| Seeed Technology                  | 1         | 0.12%   |
| Red Hat                           | 1         | 0.12%   |
| Ralink                            | 1         | 0.12%   |
| Qualcomm                          | 1         | 0.12%   |
| NetGear                           | 1         | 0.12%   |
| Motorola PCS                      | 1         | 0.12%   |
| Microsoft                         | 1         | 0.12%   |
| Google                            | 1         | 0.12%   |
| Fry's Electronics                 | 1         | 0.12%   |
| D-Link                            | 1         | 0.12%   |
| Arduino SA                        | 1         | 0.12%   |
| Apple                             | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 138       | 13.33%  |
| Intel Ethernet Controller I226-V                                              | 99        | 9.57%   |
| Intel I211 Gigabit Network Connection                                         | 62        | 5.99%   |
| Intel I210 Gigabit Network Connection                                         | 32        | 3.09%   |
| Intel Ethernet Controller I225-V                                              | 30        | 2.9%    |
| Realtek RTL8125 2.5GbE Controller                                             | 24        | 2.32%   |
| Intel I350 Gigabit Network Connection                                         | 23        | 2.22%   |
| Intel Ethernet Connection I217-LM                                             | 21        | 2.03%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 20        | 1.93%   |
| Intel Ethernet Connection (7) I219-LM                                         | 16        | 1.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 16        | 1.55%   |
| Intel 82574L Gigabit Network Connection                                       | 15        | 1.45%   |
| Intel Wireless 8260                                                           | 14        | 1.35%   |
| Intel 82580 Gigabit Network Connection                                        | 14        | 1.35%   |
| Intel 82576 Gigabit Network Connection                                        | 14        | 1.35%   |
| Intel Ethernet Connection (2) I219-LM                                         | 12        | 1.16%   |
| Intel Wireless 7260                                                           | 11        | 1.06%   |
| Intel Ethernet Connection (7) I219-V                                          | 11        | 1.06%   |
| Intel Ethernet Connection (5) I219-LM                                         | 11        | 1.06%   |
| Intel Ethernet Connection (2) I219-V                                          | 11        | 1.06%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 11        | 1.06%   |
| Intel Wireless 8265 / 8275                                                    | 10        | 0.97%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 10        | 0.97%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 9         | 0.87%   |
| Intel Wireless 7265                                                           | 9         | 0.87%   |
| Intel 82583V Gigabit Network Connection                                       | 9         | 0.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 7         | 0.68%   |
| Intel Wireless 3165                                                           | 7         | 0.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 7         | 0.68%   |
| Realtek USB 2.5GbE Controller                                                 | 6         | 0.58%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 6         | 0.58%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 6         | 0.58%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 6         | 0.58%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 6         | 0.58%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 6         | 0.58%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 6         | 0.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 5         | 0.48%   |
| Intel Wi-Fi 6 AX200                                                           | 5         | 0.48%   |
| Intel Ethernet Connection X553 1GbE                                           | 5         | 0.48%   |
| Intel Ethernet Connection I219-LM                                             | 5         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 121       | 59.9%   |
| Qualcomm Atheros      | 27        | 13.37%  |
| Realtek Semiconductor | 16        | 7.92%   |
| Broadcom              | 14        | 6.93%   |
| TP-Link               | 7         | 3.47%   |
| MediaTek              | 7         | 3.47%   |
| Sierra Wireless       | 3         | 1.49%   |
| Ralink Technology     | 2         | 0.99%   |
| IMC Networks          | 2         | 0.99%   |
| Ralink                | 1         | 0.5%    |
| NetGear               | 1         | 0.5%    |
| D-Link                | 1         | 0.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                                  | 14        | 6.83%   |
| Intel Wireless 7260                                                  | 11        | 5.37%   |
| Intel Wireless 8265 / 8275                                           | 10        | 4.88%   |
| Intel Wireless 7265                                                  | 9         | 4.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 7         | 3.41%   |
| Intel Wireless 3165                                                  | 7         | 3.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 7         | 3.41%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 6         | 2.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 5         | 2.44%   |
| Intel Wi-Fi 6 AX200                                                  | 5         | 2.44%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 5         | 2.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 5         | 2.44%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 4         | 1.95%   |
| Intel Wi-Fi 6 AX201                                                  | 4         | 1.95%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 4         | 1.95%   |
| Intel 700 Series Chipset CNVi WiFi                                   | 4         | 1.95%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 4         | 1.95%   |
| Sierra Wireless EM7455                                               | 3         | 1.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 3         | 1.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 3         | 1.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 3         | 1.46%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 3         | 1.46%   |
| Intel Wireless 3160                                                  | 3         | 1.46%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection              | 3         | 1.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 3         | 1.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 3         | 1.46%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 3         | 1.46%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 3         | 1.46%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2         | 0.98%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                  | 2         | 0.98%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 2         | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 2         | 0.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 2         | 0.98%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter      | 2         | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2         | 0.98%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 2         | 0.98%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 2         | 0.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 2         | 0.98%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 2         | 0.98%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 422       | 63.27%  |
| Realtek Semiconductor    | 171       | 25.64%  |
| Broadcom                 | 37        | 5.55%   |
| Qualcomm Atheros         | 10        | 1.5%    |
| AMD                      | 3         | 0.45%   |
| Samsung Electronics      | 2         | 0.3%    |
| Nvidia                   | 2         | 0.3%    |
| Marvell Technology Group | 2         | 0.3%    |
| Lenovo                   | 2         | 0.3%    |
| Emulex                   | 2         | 0.3%    |
| D-Link System            | 2         | 0.3%    |
| Chelsio Communications   | 2         | 0.3%    |
| Aquantia                 | 2         | 0.3%    |
| VIA Technologies         | 1         | 0.15%   |
| TRENDnet                 | 1         | 0.15%   |
| TP-Link                  | 1         | 0.15%   |
| sipeed                   | 1         | 0.15%   |
| Qualcomm                 | 1         | 0.15%   |
| Motorola PCS             | 1         | 0.15%   |
| Microsoft                | 1         | 0.15%   |
| Apple                    | 1         | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 138       | 17.02%  |
| Intel Ethernet Controller I226-V                                              | 99        | 12.21%  |
| Intel I211 Gigabit Network Connection                                         | 62        | 7.64%   |
| Intel I210 Gigabit Network Connection                                         | 32        | 3.95%   |
| Intel Ethernet Controller I225-V                                              | 30        | 3.7%    |
| Realtek RTL8125 2.5GbE Controller                                             | 23        | 2.84%   |
| Intel I350 Gigabit Network Connection                                         | 23        | 2.84%   |
| Intel Ethernet Connection I217-LM                                             | 21        | 2.59%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 20        | 2.47%   |
| Intel Ethernet Connection (7) I219-LM                                         | 16        | 1.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 16        | 1.97%   |
| Intel 82574L Gigabit Network Connection                                       | 15        | 1.85%   |
| Intel 82580 Gigabit Network Connection                                        | 14        | 1.73%   |
| Intel 82576 Gigabit Network Connection                                        | 14        | 1.73%   |
| Intel Ethernet Connection (2) I219-LM                                         | 12        | 1.48%   |
| Intel Ethernet Connection (7) I219-V                                          | 11        | 1.36%   |
| Intel Ethernet Connection (5) I219-LM                                         | 11        | 1.36%   |
| Intel Ethernet Connection (2) I219-V                                          | 11        | 1.36%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 11        | 1.36%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 10        | 1.23%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 9         | 1.11%   |
| Intel 82583V Gigabit Network Connection                                       | 9         | 1.11%   |
| Realtek USB 2.5GbE Controller                                                 | 6         | 0.74%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 6         | 0.74%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 6         | 0.74%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 6         | 0.74%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 6         | 0.74%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 6         | 0.74%   |
| Intel Ethernet Connection X553 1GbE                                           | 5         | 0.62%   |
| Intel Ethernet Connection I219-LM                                             | 5         | 0.62%   |
| Intel Ethernet Connection (11) I219-LM                                        | 5         | 0.62%   |
| Intel Ethernet Controller X550                                                | 4         | 0.49%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 4         | 0.49%   |
| Intel Ethernet Connection I217-V                                              | 4         | 0.49%   |
| Intel Ethernet Connection (6) I219-V                                          | 4         | 0.49%   |
| Intel Ethernet Connection (4) I219-V                                          | 4         | 0.49%   |
| Intel Ethernet Connection (3) I218-LM                                         | 4         | 0.49%   |
| Intel 82575EB Gigabit Network Connection                                      | 4         | 0.49%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 4         | 0.49%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 4         | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 572       | 72.96%  |
| WiFi     | 193       | 24.62%  |
| Unknown  | 10        | 1.28%   |
| Modem    | 9         | 1.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 543       | 90.05%  |
| WiFi     | 59        | 9.78%   |
| Modem    | 1         | 0.17%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 168       | 28%     |
| 4     | 128       | 21.33%  |
| 3     | 92        | 15.33%  |
| 1     | 84        | 14%     |
| 6     | 45        | 7.5%    |
| 5     | 42        | 7%      |
| 9     | 12        | 2%      |
| 8     | 12        | 2%      |
| 7     | 8         | 1.33%   |
| 10    | 4         | 0.67%   |
| 0     | 3         | 0.5%    |
| 14    | 1         | 0.17%   |
| 12    | 1         | 0.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 470       | 75.93%  |
| Yes  | 149       | 24.07%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 99        | 62.66%  |
| Apple                           | 11        | 6.96%   |
| Qualcomm Atheros Communications | 10        | 6.33%   |
| Realtek Semiconductor           | 9         | 5.7%    |
| Cambridge Silicon Radio         | 8         | 5.06%   |
| MediaTek                        | 5         | 3.16%   |
| Broadcom                        | 5         | 3.16%   |
| IMC Networks                    | 3         | 1.9%    |
| ASUSTek Computer                | 3         | 1.9%    |
| Hewlett-Packard                 | 2         | 1.27%   |
| Foxconn / Hon Hai               | 2         | 1.27%   |
| Toshiba                         | 1         | 0.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 46        | 28.93%  |
| Intel AX201 Bluetooth                                       | 16        | 10.06%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 12        | 7.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 8         | 5.03%   |
| Realtek Bluetooth Adapter                                   | 7         | 4.4%    |
| Intel AX211 Bluetooth                                       | 7         | 4.4%    |
| Intel AX210 Bluetooth                                       | 7         | 4.4%    |
| Intel AX200 Bluetooth                                       | 7         | 4.4%    |
| Apple Bluetooth Host Controller                             | 5         | 3.14%   |
| Apple Broadcom Built-in Bluetooth                           | 4         | 2.52%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 3         | 1.89%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 1.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.26%   |
| MediaTek Wireless_Device                                    | 2         | 1.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 1.26%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 1.26%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 2         | 1.26%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 2         | 1.26%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 2         | 1.26%   |
| ASUS Qualcomm Bluetooth 4.1                                 | 2         | 1.26%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 1.26%   |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip             | 1         | 0.63%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 0.63%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 0.63%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1         | 0.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.1                      | 1         | 0.63%   |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE        | 1         | 0.63%   |
| MediaTek RZ616 Bluetooth Adapter                            | 1         | 0.63%   |
| MediaTek RZ608 Bluetooth Adapter                            | 1         | 0.63%   |
| MediaTek Bluetooth Adapter                                  | 1         | 0.63%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 0.63%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]      | 1         | 0.63%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 0.63%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 0.63%   |
| Broadcom Bluetooth 4.0                                      | 1         | 0.63%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 0.63%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 0.63%   |
| ASUS Bluetooth Controller                                   | 1         | 0.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 426       | 76.07%  |
| AMD                                          | 74        | 13.21%  |
| Nvidia                                       | 40        | 7.14%   |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 0.54%   |
| Thesycon Systemsoftware & Consulting         | 2         | 0.36%   |
| Texas Instruments                            | 2         | 0.36%   |
| Logitech                                     | 2         | 0.36%   |
| Lenovo                                       | 2         | 0.36%   |
| Focusrite-Novation                           | 2         | 0.36%   |
| C-Media Electronics                          | 2         | 0.36%   |
| Walmart                                      | 1         | 0.18%   |
| Sony                                         | 1         | 0.18%   |
| FiiO Electronics Technology                  | 1         | 0.18%   |
| Creative Labs                                | 1         | 0.18%   |
| Blue Microphones                             | 1         | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 50        | 7.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 37        | 5.62%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 32        | 4.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 28        | 4.26%   |
| Intel Cannon Lake PCH cAVS                                                                        | 27        | 4.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 27        | 4.1%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 25        | 3.8%    |
| Intel Jasper Lake HD Audio                                                                        | 25        | 3.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 23        | 3.5%    |
| Intel 200 Series PCH HD Audio                                                                     | 23        | 3.5%    |
| AMD Ryzen HD Audio Controller                                                                     | 22        | 3.34%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 2.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 19        | 2.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 18        | 2.74%   |
| AMD FCH Azalia Controller                                                                         | 15        | 2.28%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 14        | 2.13%   |
| Intel Broadwell-U Audio Controller                                                                | 12        | 1.82%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 1.67%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 11        | 1.67%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 11        | 1.67%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 7         | 1.06%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 1.06%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 1.06%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 1.06%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 1.06%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 0.91%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 0.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 0.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 0.76%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 0.76%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 5         | 0.76%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 0.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.61%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.61%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 4         | 0.61%   |
| Intel Raptor Lake High Definition Audio Controller                                                | 4         | 0.61%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 0.61%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 4         | 0.61%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 4         | 0.61%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 4         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 129       | 20.67%  |
| SK hynix                                | 78        | 12.5%   |
| Micron Technology                       | 69        | 11.06%  |
| Crucial                                 | 68        | 10.9%   |
| Kingston                                | 64        | 10.26%  |
| Corsair                                 | 41        | 6.57%   |
| Unknown                                 | 36        | 5.77%   |
| G.Skill                                 | 15        | 2.4%    |
| Ramaxel Technology                      | 14        | 2.24%   |
| Unknown                                 | 14        | 2.24%   |
| Team                                    | 10        | 1.6%    |
| Transcend                               | 8         | 1.28%   |
| A-DATA Technology                       | 8         | 1.28%   |
| Apacer                                  | 6         | 0.96%   |
| Unknown (ABCD)                          | 5         | 0.8%    |
| Timetec                                 | 5         | 0.8%    |
| Silicon Power                           | 4         | 0.64%   |
| Kimtigo                                 | 4         | 0.64%   |
| GeIL                                    | 4         | 0.64%   |
| Elpida                                  | 4         | 0.64%   |
| Patriot                                 | 3         | 0.48%   |
| Innodisk                                | 3         | 0.48%   |
| Hewlett-Packard                         | 3         | 0.48%   |
| Unknown (0x0FBA)                        | 2         | 0.32%   |
| Unknown (0x0080)                        | 2         | 0.32%   |
| Patriot Memory (PDP Systems)            | 2         | 0.32%   |
| Nanya Technology                        | 2         | 0.32%   |
| Heoriady                                | 2         | 0.32%   |
| Golden Empire                           | 2         | 0.32%   |
| Vasekey                                 | 1         | 0.16%   |
| Uroad                                   | 1         | 0.16%   |
| Unknown (AB)                            | 1         | 0.16%   |
| Unknown (0x0B45)                        | 1         | 0.16%   |
| Unifosa                                 | 1         | 0.16%   |
| Toshiba                                 | 1         | 0.16%   |
| Smart Modular                           | 1         | 0.16%   |
| SK_Hynix                                | 1         | 0.16%   |
| Silicon Power Computer & Communications | 1         | 0.16%   |
| QEMU                                    | 1         | 0.16%   |
| PNY                                     | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 14        | 2.14%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 9         | 1.38%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s      | 9         | 1.38%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 6         | 0.92%   |
| Unknown (ABCD) RAM 123456789012345678 8GB DIMM DDR4 2400MT/s | 5         | 0.76%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 5         | 0.76%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 5         | 0.76%   |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s          | 5         | 0.76%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 5         | 0.76%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s        | 5         | 0.76%   |
| Corsair RAM Module 8GB DIMM DDR4 2133MT/s                    | 5         | 0.76%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 4         | 0.61%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s         | 4         | 0.61%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 4         | 0.61%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 0.61%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s          | 4         | 0.61%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s        | 4         | 0.61%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2133MT/s        | 4         | 0.61%   |
| Micron RAM 8ATF1G64AZ-2G3H1 8GB DIMM DDR4 2400MT/s           | 4         | 0.61%   |
| Crucial RAM CT8G48C40S5.M4A1 8GB SODIMM DDR5 4800MT/s        | 4         | 0.61%   |
| Corsair RAM CMSX16GX5M1A4800C40 16GB SODIMM DDR5 4800MT/s    | 4         | 0.61%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 3         | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                   | 3         | 0.46%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s        | 3         | 0.46%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 3         | 0.46%   |
| SK hynix RAM HMCG78AEBSA092N 16GB SODIMM DDR5 4800MT/s       | 3         | 0.46%   |
| SK hynix RAM HMCG66AEBSA095N 8GB SODIMM DDR5 4800MT/s        | 3         | 0.46%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 3         | 0.46%   |
| Micron RAM MTC4C10163S1SC56BD1 8GB SODIMM DDR5 5600MT/s      | 3         | 0.46%   |
| Micron RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s       | 3         | 0.46%   |
| Kingston RAM 99U5469-045.A00LF 4GB DIMM DDR3 1600MT/s        | 3         | 0.46%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s               | 3         | 0.46%   |
| Crucial RAM CT8G4SFRA32A.M4FEA 8GB SODIMM DDR4 3200MT/s      | 3         | 0.46%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s        | 3         | 0.46%   |
| Crucial RAM CT16G4SFRA32A.M16FR 16GB SODIMM DDR4 3200MT/s    | 3         | 0.46%   |
| Corsair RAM CMZ16GX3M2A1600C9 8GB DIMM DDR3 1600MT/s         | 3         | 0.46%   |
| Corsair RAM CMK16GX4M2A2133C13 8GB DIMM DDR4 3200MT/s        | 3         | 0.46%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                  | 2         | 0.31%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 2         | 0.31%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 2         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 246       | 44.24%  |
| DDR3    | 200       | 35.97%  |
| DDR5    | 61        | 10.97%  |
| Unknown | 14        | 2.52%   |
| LPDDR4  | 10        | 1.8%    |
| LPDDR3  | 10        | 1.8%    |
| DDR2    | 8         | 1.44%   |
| LPDDR5  | 4         | 0.72%   |
| DDR     | 2         | 0.36%   |
| RAM     | 1         | 0.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 278       | 49.82%  |
| DIMM         | 247       | 44.27%  |
| Row Of Chips | 16        | 2.87%   |
| Unknown      | 10        | 1.79%   |
| Chip         | 6         | 1.08%   |
| RIMM         | 1         | 0.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 243       | 41.61%  |
| 4096  | 141       | 24.14%  |
| 16384 | 119       | 20.38%  |
| 2048  | 43        | 7.36%   |
| 32768 | 28        | 4.79%   |
| 1024  | 7         | 1.2%    |
| 65536 | 1         | 0.17%   |
| 12288 | 1         | 0.17%   |
| 3072  | 1         | 0.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 156       | 26.71%  |
| 3200    | 68        | 11.64%  |
| 2667    | 65        | 11.13%  |
| 2400    | 60        | 10.27%  |
| 2133    | 52        | 8.9%    |
| 1333    | 46        | 7.88%   |
| 4800    | 45        | 7.71%   |
| 5600    | 18        | 3.08%   |
| 1867    | 13        | 2.23%   |
| 800     | 12        | 2.05%   |
| 2666    | 8         | 1.37%   |
| 3600    | 7         | 1.2%    |
| 1066    | 6         | 1.03%   |
| 6400    | 3         | 0.51%   |
| 4267    | 3         | 0.51%   |
| 1067    | 3         | 0.51%   |
| 667     | 3         | 0.51%   |
| Unknown | 3         | 0.51%   |
| 3733    | 2         | 0.34%   |
| 3066    | 2         | 0.34%   |
| 3000    | 2         | 0.34%   |
| 1866    | 2         | 0.34%   |
| 400     | 2         | 0.34%   |
| 59392   | 1         | 0.17%   |
| 2933    | 1         | 0.17%   |
| 1334    | 1         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model               | Computers | Percent |
|---------------------|-----------|---------|
| HP LaserJet 3390    | 1         | 50%     |
| Brother DCP-9015CDW | 1         | 50%     |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 21        | 34.43%  |
| Bison Electronics                      | 8         | 13.11%  |
| IMC Networks                           | 7         | 11.48%  |
| Microdia                               | 5         | 8.2%    |
| Realtek Semiconductor                  | 4         | 6.56%   |
| Apple                                  | 4         | 6.56%   |
| Sunplus Innovation Technology          | 3         | 4.92%   |
| Suyin                                  | 2         | 3.28%   |
| Logitech                               | 2         | 3.28%   |
| Z-Star Microelectronics                | 1         | 1.64%   |
| Syntek                                 | 1         | 1.64%   |
| Quanta                                 | 1         | 1.64%   |
| Luxvisions Innotech Limited            | 1         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.64%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 12        | 19.35%  |
| Bison Integrated Camera                                      | 4         | 6.45%   |
| Apple FaceTime HD Camera (Built-in)                          | 4         | 6.45%   |
| Microdia Integrated_Webcam_HD                                | 3         | 4.84%   |
| IMC Networks Integrated Webcam                               | 2         | 3.23%   |
| IMC Networks EasyCamera                                      | 2         | 3.23%   |
| Chicony Integrated Camera (1280x720@30)                      | 2         | 3.23%   |
| Chicony EasyCamera                                           | 2         | 3.23%   |
| Z-Star WebCam SC-03FFL11739P                                 | 1         | 1.61%   |
| Syntek Integrated Camera                                     | 1         | 1.61%   |
| Suyin Lenovo Integrated Webcam                               | 1         | 1.61%   |
| Suyin HP webcam [dv6-1190en]                                 | 1         | 1.61%   |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 1.61%   |
| Sunplus Laptop Integrated Webcam HD                          | 1         | 1.61%   |
| Sunplus HD WebCam                                            | 1         | 1.61%   |
| Realtek Laptop Camera                                        | 1         | 1.61%   |
| Realtek Integrated_Webcam_HD                                 | 1         | 1.61%   |
| Realtek Integrated_Webcam_FHD                                | 1         | 1.61%   |
| Realtek Integrated Camera                                    | 1         | 1.61%   |
| Quanta HP Universal Camera                                   | 1         | 1.61%   |
| Microdia USB  Live camera                                    | 1         | 1.61%   |
| Microdia Integrated Webcam HD                                | 1         | 1.61%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera          | 1         | 1.61%   |
| Logitech HD Pro Webcam C920                                  | 1         | 1.61%   |
| Logitech C922 Pro Stream Webcam                              | 1         | 1.61%   |
| IMC Networks TOSHIBA Web Camera - HD                         | 1         | 1.61%   |
| IMC Networks SunplusIT Integrated Camera                     | 1         | 1.61%   |
| IMC Networks Integrated Camera                               | 1         | 1.61%   |
| Chicony USB2.0 VGA UVC WebCam                                | 1         | 1.61%   |
| Chicony TOSHIBA Web Camera - HD                              | 1         | 1.61%   |
| Chicony TOSHIBA Web Camera - 3M                              | 1         | 1.61%   |
| Chicony ThinkPad T490 Webcam                                 | 1         | 1.61%   |
| Chicony Lenovo Integrated Camera (0.3MP)                     | 1         | 1.61%   |
| Chicony Lenovo Integrated Camera                             | 1         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 1.61%   |
| Bison Web Camera - FHD                                       | 1         | 1.61%   |
| Bison SunplusIT Integrated Camera                            | 1         | 1.61%   |
| Bison Lenovo Integrated Webcam                               | 1         | 1.61%   |
| Bison Lenovo EasyCamera                                      | 1         | 1.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 14        | 60.87%  |
| Synaptics                  | 4         | 17.39%  |
| Shenzhen Goodix Technology | 2         | 8.7%    |
| Elan Microelectronics      | 2         | 8.7%    |
| Upek                       | 1         | 4.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 5         | 21.74%  |
| Validity Sensors Synaptics WBDI                        | 5         | 21.74%  |
| Validity Sensors VFS7552 Touch Fingerprint Sensor      | 2         | 8.7%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 8.7%    |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 8.7%    |
| Elan Fingerprint Sensor                                | 2         | 8.7%    |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 4.35%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 4.35%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 4.35%   |
| Synaptics WBDI                                         | 1         | 4.35%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 4.35%   |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 300       | 49.26%  |
| 0     | 144       | 23.65%  |
| 2     | 95        | 15.6%   |
| 3     | 55        | 9.03%   |
| 4     | 12        | 1.97%   |
| 5     | 2         | 0.33%   |
| 6     | 1         | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 415       | 66.08%  |
| Bluetooth                | 76        | 12.1%   |
| Net/wireless             | 41        | 6.53%   |
| Card reader              | 24        | 3.82%   |
| Fingerprint reader       | 19        | 3.03%   |
| Net/ethernet             | 13        | 2.07%   |
| Network                  | 12        | 1.91%   |
| Firewire controller      | 10        | 1.59%   |
| Sound                    | 8         | 1.27%   |
| Graphics card            | 3         | 0.48%   |
| Storage/raid             | 2         | 0.32%   |
| Storage                  | 2         | 0.32%   |
| Dvb card                 | 2         | 0.32%   |
| Modem                    | 1         | 0.16%   |

