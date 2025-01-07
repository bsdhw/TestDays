FreeBSD - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for FreeBSD.

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

Total: 2313

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Unknown       | DH61BR G32662-203           | [c082ba6276](https://bsd-hardware.info/?probe=c082ba6276) | Jan 06, 2025 |
| MSI           | H81M-P33                    | [4de04d7c63](https://bsd-hardware.info/?probe=4de04d7c63) | Jan 05, 2025 |
| ASUSTek       | P5Q-E                       | [ced4dbfd4b](https://bsd-hardware.info/?probe=ced4dbfd4b) | Jan 05, 2025 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c5f2cf7f1e](https://bsd-hardware.info/?probe=c5f2cf7f1e) | Jan 05, 2025 |
| Dell          | 0YP4HV A00                  | [f4bf8c469e](https://bsd-hardware.info/?probe=f4bf8c469e) | Jan 03, 2025 |
| Dell          | 0YP4HV A00                  | [7c407b8021](https://bsd-hardware.info/?probe=7c407b8021) | Jan 03, 2025 |
| MSI           | MS-B1711                    | [98df812bc4](https://bsd-hardware.info/?probe=98df812bc4) | Jan 03, 2025 |
| MSI           | MS-B1711                    | [c58187f624](https://bsd-hardware.info/?probe=c58187f624) | Jan 03, 2025 |
| Dell          | 0JJ7YG A00                  | [60a9be6897](https://bsd-hardware.info/?probe=60a9be6897) | Jan 02, 2025 |
| Dell          | 01D4TT A00                  | [447a0925d1](https://bsd-hardware.info/?probe=447a0925d1) | Jan 02, 2025 |
| Dell          | 0JJ7YG A00                  | [f586af63cf](https://bsd-hardware.info/?probe=f586af63cf) | Jan 02, 2025 |
| HP            | 83E2                        | [c0cce366c3](https://bsd-hardware.info/?probe=c0cce366c3) | Jan 01, 2025 |
| Gigabyte      | EP43T-UD3L                  | [4c4764a3fe](https://bsd-hardware.info/?probe=4c4764a3fe) | Jan 01, 2025 |
| ASRockRack    | EPYC3101D4I-2T              | [be896d46e1](https://bsd-hardware.info/?probe=be896d46e1) | Dec 31, 2024 |
| HP            | 8055                        | [ad2cab0e5d](https://bsd-hardware.info/?probe=ad2cab0e5d) | Dec 31, 2024 |
| Shenzhen s... | miniPC                      | [974d78e0bf](https://bsd-hardware.info/?probe=974d78e0bf) | Dec 31, 2024 |
| ASUSTek       | P8H67-M PRO                 | [002e1aabfa](https://bsd-hardware.info/?probe=002e1aabfa) | Dec 30, 2024 |
| MSI           | H81M-P33                    | [a1fc208c90](https://bsd-hardware.info/?probe=a1fc208c90) | Dec 29, 2024 |
| ASUSTek       | P5Q-E                       | [f497fed563](https://bsd-hardware.info/?probe=f497fed563) | Dec 29, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [71afdfab99](https://bsd-hardware.info/?probe=71afdfab99) | Dec 29, 2024 |
| NF533MS       | 1.0                         | [3f9b4a5c4f](https://bsd-hardware.info/?probe=3f9b4a5c4f) | Dec 28, 2024 |
| Intel         | HURONRIVER                  | [dda4ccd2af](https://bsd-hardware.info/?probe=dda4ccd2af) | Dec 26, 2024 |
| Dell          | 0T7D40 A01                  | [af31d44d1f](https://bsd-hardware.info/?probe=af31d44d1f) | Dec 24, 2024 |
| Gigabyte      | Z790 AORUS MASTER X         | [d8022a2734](https://bsd-hardware.info/?probe=d8022a2734) | Dec 24, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2c141d9a6e](https://bsd-hardware.info/?probe=2c141d9a6e) | Dec 24, 2024 |
| Dell          | 0FF3FN A00                  | [33a3dcb343](https://bsd-hardware.info/?probe=33a3dcb343) | Dec 24, 2024 |
| Gigabyte      | M68MT-S2                    | [0ac816abb8](https://bsd-hardware.info/?probe=0ac816abb8) | Dec 22, 2024 |
| Dell          | 00V62H A00                  | [0b6e2a4e95](https://bsd-hardware.info/?probe=0b6e2a4e95) | Dec 21, 2024 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [bee58d9e52](https://bsd-hardware.info/?probe=bee58d9e52) | Dec 21, 2024 |
| Lenovo        | SHARKBAY NO DPK             | [0e54b0ed66](https://bsd-hardware.info/?probe=0e54b0ed66) | Dec 20, 2024 |
| Gigabyte      | G41M-Combo                  | [d2d73e5ab9](https://bsd-hardware.info/?probe=d2d73e5ab9) | Dec 16, 2024 |
| Dell          | 0FF3FN A00                  | [6f008745da](https://bsd-hardware.info/?probe=6f008745da) | Dec 16, 2024 |
| PC Engines    | APU2                        | [731738fd98](https://bsd-hardware.info/?probe=731738fd98) | Dec 15, 2024 |
| Gigabyte      | H97M-HD3                    | [b916e546ab](https://bsd-hardware.info/?probe=b916e546ab) | Dec 14, 2024 |
| ASUSTek       | P5Q-E                       | [814f666054](https://bsd-hardware.info/?probe=814f666054) | Dec 14, 2024 |
| Gigabyte      | M68MT-S2                    | [87ce6d4615](https://bsd-hardware.info/?probe=87ce6d4615) | Dec 13, 2024 |
| JGINYUE       | X99-8D4G Server             | [8a6322442d](https://bsd-hardware.info/?probe=8a6322442d) | Dec 13, 2024 |
| WeiBu         | ADL-N Prod                  | [de66071f16](https://bsd-hardware.info/?probe=de66071f16) | Dec 12, 2024 |
| Intel         | X79_PLUS                    | [0382eb3cd4](https://bsd-hardware.info/?probe=0382eb3cd4) | Dec 10, 2024 |
| ASUSTek       | PRIME Z790-A WIFI           | [09413cb67c](https://bsd-hardware.info/?probe=09413cb67c) | Dec 10, 2024 |
| JGINYUE       | X99-8D4G Server             | [0a59d0dd76](https://bsd-hardware.info/?probe=0a59d0dd76) | Dec 09, 2024 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [57a5cf527b](https://bsd-hardware.info/?probe=57a5cf527b) | Dec 08, 2024 |
| Gigabyte      | Z690 AORUS ULTRA            | [3ec2b38bad](https://bsd-hardware.info/?probe=3ec2b38bad) | Dec 07, 2024 |
| ASUSTek       | ROG STRIX X870E-E GAMING... | [4edaabd936](https://bsd-hardware.info/?probe=4edaabd936) | Dec 07, 2024 |
| Unknown       | Unknown                     | [5077b94887](https://bsd-hardware.info/?probe=5077b94887) | Dec 06, 2024 |
| ASUSTek       | PRIME Z790-A WIFI           | [7839a021dc](https://bsd-hardware.info/?probe=7839a021dc) | Dec 06, 2024 |
| MSI           | B550M PRO-VDH               | [2bd3d72cbb](https://bsd-hardware.info/?probe=2bd3d72cbb) | Dec 06, 2024 |
| MSI           | Z77A-G41                    | [7091f79308](https://bsd-hardware.info/?probe=7091f79308) | Dec 05, 2024 |
| HP            | 1998                        | [6233446d5e](https://bsd-hardware.info/?probe=6233446d5e) | Dec 04, 2024 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [8fbade62a5](https://bsd-hardware.info/?probe=8fbade62a5) | Dec 04, 2024 |
| ASUSTek       | PRIME B650M-K               | [b75044f43a](https://bsd-hardware.info/?probe=b75044f43a) | Dec 04, 2024 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [e3cc180fdd](https://bsd-hardware.info/?probe=e3cc180fdd) | Dec 02, 2024 |
| MSI           | H61M-P21                    | [55ae602922](https://bsd-hardware.info/?probe=55ae602922) | Dec 02, 2024 |
| MSI           | Z77A-G41                    | [76cc6deb79](https://bsd-hardware.info/?probe=76cc6deb79) | Dec 01, 2024 |
| MSI           | H81M-P33                    | [a910f6b4a8](https://bsd-hardware.info/?probe=a910f6b4a8) | Dec 01, 2024 |
| ASUSTek       | P5Q-E                       | [dd9d2b4701](https://bsd-hardware.info/?probe=dd9d2b4701) | Dec 01, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [aaabbe33c6](https://bsd-hardware.info/?probe=aaabbe33c6) | Dec 01, 2024 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [ee30758c43](https://bsd-hardware.info/?probe=ee30758c43) | Nov 30, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | [a070b11044](https://bsd-hardware.info/?probe=a070b11044) | Nov 30, 2024 |
| ASUSTek       | PRIME B650M-K               | [cae7ae1e3f](https://bsd-hardware.info/?probe=cae7ae1e3f) | Nov 30, 2024 |
| ASUSTek       | Pro B560M-C                 | [d459b88a7a](https://bsd-hardware.info/?probe=d459b88a7a) | Nov 30, 2024 |
| Gigabyte      | Z490 AORUS MASTER           | [5a7a5ce019](https://bsd-hardware.info/?probe=5a7a5ce019) | Nov 30, 2024 |
| HP            | 21B4 A01                    | [8540ec3124](https://bsd-hardware.info/?probe=8540ec3124) | Nov 29, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [f309cf2bee](https://bsd-hardware.info/?probe=f309cf2bee) | Nov 28, 2024 |
| MSI           | B450M MORTAR MAX            | [f1ade048b2](https://bsd-hardware.info/?probe=f1ade048b2) | Nov 28, 2024 |
| MSI           | B450M MORTAR MAX            | [b7056e45fd](https://bsd-hardware.info/?probe=b7056e45fd) | Nov 27, 2024 |
| MSI           | B450M MORTAR MAX            | [8c4222d88e](https://bsd-hardware.info/?probe=8c4222d88e) | Nov 27, 2024 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [8282b592ac](https://bsd-hardware.info/?probe=8282b592ac) | Nov 27, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ba28a2eea4](https://bsd-hardware.info/?probe=ba28a2eea4) | Nov 27, 2024 |
| MSI           | H310M PRO-M2 PLUS           | [db040ae85a](https://bsd-hardware.info/?probe=db040ae85a) | Nov 26, 2024 |
| Unknown       | Unknown                     | [52c9820eec](https://bsd-hardware.info/?probe=52c9820eec) | Nov 24, 2024 |
| MSI           | H81M-P33                    | [9e5c756f1f](https://bsd-hardware.info/?probe=9e5c756f1f) | Nov 24, 2024 |
| ASUSTek       | P5Q-E                       | [2d7f40d5f5](https://bsd-hardware.info/?probe=2d7f40d5f5) | Nov 24, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ed997ac3e9](https://bsd-hardware.info/?probe=ed997ac3e9) | Nov 24, 2024 |
| Gigabyte      | Z490 AORUS MASTER           | [acfb1a77bf](https://bsd-hardware.info/?probe=acfb1a77bf) | Nov 24, 2024 |
| ASUSTek       | Maximus VI HERO             | [e606e48c03](https://bsd-hardware.info/?probe=e606e48c03) | Nov 23, 2024 |
| Intel         | DG45ID AAE27729-307         | [14f367aa0a](https://bsd-hardware.info/?probe=14f367aa0a) | Nov 23, 2024 |
| pc1           | ID-PCI7E                    | [faccfe1d3b](https://bsd-hardware.info/?probe=faccfe1d3b) | Nov 22, 2024 |
| ASRockRack    | X470D4U2-2T                 | [638b70ebe3](https://bsd-hardware.info/?probe=638b70ebe3) | Nov 20, 2024 |
| HP            | 21B4 A01                    | [53fb142fb3](https://bsd-hardware.info/?probe=53fb142fb3) | Nov 20, 2024 |
| Unknown       | Unknown                     | [9cb678b64b](https://bsd-hardware.info/?probe=9cb678b64b) | Nov 19, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [43f93bb4ab](https://bsd-hardware.info/?probe=43f93bb4ab) | Nov 19, 2024 |
| ASUSTek       | PRIME B650M-K               | [f4ba847672](https://bsd-hardware.info/?probe=f4ba847672) | Nov 18, 2024 |
| ASUSTek       | PRIME H310M-D R2.0          | [e59272c611](https://bsd-hardware.info/?probe=e59272c611) | Nov 18, 2024 |
| Dell          | 0D517D A00                  | [1bc1b8eb94](https://bsd-hardware.info/?probe=1bc1b8eb94) | Nov 17, 2024 |
| Gigabyte      | H61M-DS2                    | [b475794daf](https://bsd-hardware.info/?probe=b475794daf) | Nov 16, 2024 |
| ASUSTek       | M5A97 LE R2.0               | [b9b63a6ca9](https://bsd-hardware.info/?probe=b9b63a6ca9) | Nov 15, 2024 |
| ASUSTek       | M5A97 LE R2.0               | [0def0b220f](https://bsd-hardware.info/?probe=0def0b220f) | Nov 13, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [2cda07b3f5](https://bsd-hardware.info/?probe=2cda07b3f5) | Nov 12, 2024 |
| ASRock        | X570 PG Velocita            | [2a30e356a7](https://bsd-hardware.info/?probe=2a30e356a7) | Nov 12, 2024 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [e36d556ad9](https://bsd-hardware.info/?probe=e36d556ad9) | Nov 12, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [8583a7eb2e](https://bsd-hardware.info/?probe=8583a7eb2e) | Nov 09, 2024 |
| RDW Comput... | Kama-10                     | [0886b2b851](https://bsd-hardware.info/?probe=0886b2b851) | Nov 07, 2024 |
| Gigabyte      | B650M D3HP                  | [adf503f345](https://bsd-hardware.info/?probe=adf503f345) | Nov 06, 2024 |
| Gigabyte      | B650M D3HP                  | [fe8076ef02](https://bsd-hardware.info/?probe=fe8076ef02) | Nov 06, 2024 |
| ASUSTek       | PRIME B650M-K               | [45f3b7828e](https://bsd-hardware.info/?probe=45f3b7828e) | Nov 04, 2024 |
| Unknown       | Unknown                     | [85bc2300d4](https://bsd-hardware.info/?probe=85bc2300d4) | Nov 04, 2024 |
| HPE           | ProLiant MicroServer Gen... | [6ac27395ac](https://bsd-hardware.info/?probe=6ac27395ac) | Nov 03, 2024 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [b140c0e1d4](https://bsd-hardware.info/?probe=b140c0e1d4) | Nov 01, 2024 |
| ASRock        | Z790M-ITX WiFi              | [ef9a5f66a2](https://bsd-hardware.info/?probe=ef9a5f66a2) | Oct 31, 2024 |
| MSI           | B450M MORTAR                | [eb24aa8d7d](https://bsd-hardware.info/?probe=eb24aa8d7d) | Oct 31, 2024 |
| MSI           | H310M PRO-M2 PLUS           | [8c3d77a23b](https://bsd-hardware.info/?probe=8c3d77a23b) | Oct 31, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | [1c6bd76968](https://bsd-hardware.info/?probe=1c6bd76968) | Oct 31, 2024 |
| ASUSTek       | PRIME B650M-K               | [9a4c1afe1d](https://bsd-hardware.info/?probe=9a4c1afe1d) | Oct 31, 2024 |
| MSI           | H310M PRO-M2 PLUS           | [8ad31a1bad](https://bsd-hardware.info/?probe=8ad31a1bad) | Oct 30, 2024 |
| Dell          | 053CWD A00                  | [1a6b365ab4](https://bsd-hardware.info/?probe=1a6b365ab4) | Oct 30, 2024 |
| Shenzhen M... | AHWSA                       | [03cf413a7e](https://bsd-hardware.info/?probe=03cf413a7e) | Oct 30, 2024 |
| Gigabyte      | B450M DS3H-CF               | [ef22672b81](https://bsd-hardware.info/?probe=ef22672b81) | Oct 29, 2024 |
| ASRock        | Z790M-ITX WiFi              | [ae87d2f3a1](https://bsd-hardware.info/?probe=ae87d2f3a1) | Oct 29, 2024 |
| ASRock        | X570 Taichi                 | [4c642bb872](https://bsd-hardware.info/?probe=4c642bb872) | Oct 28, 2024 |
| Quantum en... | HackBoard 2                 | [77f7cc8b05](https://bsd-hardware.info/?probe=77f7cc8b05) | Oct 27, 2024 |
| Intel         | D2500CC AAG81477-401        | [0c7e857ac8](https://bsd-hardware.info/?probe=0c7e857ac8) | Oct 27, 2024 |
| Gigabyte      | B450M S2H V2                | [1dd8ec6cbc](https://bsd-hardware.info/?probe=1dd8ec6cbc) | Oct 27, 2024 |
| Gigabyte      | H55M-UD2H                   | [273712e14f](https://bsd-hardware.info/?probe=273712e14f) | Oct 25, 2024 |
| HP            | 18E7                        | [dbdd29df9f](https://bsd-hardware.info/?probe=dbdd29df9f) | Oct 25, 2024 |
| MSI           | B450M MORTAR MAX            | [69990077f3](https://bsd-hardware.info/?probe=69990077f3) | Oct 25, 2024 |
| ASRock        | B550M Phantom Gaming 4      | [c963db262c](https://bsd-hardware.info/?probe=c963db262c) | Oct 22, 2024 |
| Gigabyte      | B450M DS3H WIFI-CF          | [2c4cb4fd49](https://bsd-hardware.info/?probe=2c4cb4fd49) | Oct 20, 2024 |
| Unknown       | Unknown                     | [7d49a8dfcd](https://bsd-hardware.info/?probe=7d49a8dfcd) | Oct 20, 2024 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [c163cc64f9](https://bsd-hardware.info/?probe=c163cc64f9) | Oct 16, 2024 |
| Shenzhen M... | F7BFD                       | [def723c09a](https://bsd-hardware.info/?probe=def723c09a) | Oct 15, 2024 |
| Shenzhen M... | AHBNB OEM                   | [cb7d2d44d9](https://bsd-hardware.info/?probe=cb7d2d44d9) | Oct 14, 2024 |
| MSI           | H81M-P33                    | [a47d55306c](https://bsd-hardware.info/?probe=a47d55306c) | Oct 13, 2024 |
| ASUSTek       | P5Q-E                       | [5f32e7b082](https://bsd-hardware.info/?probe=5f32e7b082) | Oct 13, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [27016d6537](https://bsd-hardware.info/?probe=27016d6537) | Oct 13, 2024 |
| Gigabyte      | X99-UD4P-CF                 | [a7f00617a4](https://bsd-hardware.info/?probe=a7f00617a4) | Oct 12, 2024 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [b8416db286](https://bsd-hardware.info/?probe=b8416db286) | Oct 12, 2024 |
| ASUSTek       | PRIME A320M-K/BR            | [3e9754954d](https://bsd-hardware.info/?probe=3e9754954d) | Oct 12, 2024 |
| Dell          | 0R1PCR A00                  | [d4abcde1eb](https://bsd-hardware.info/?probe=d4abcde1eb) | Oct 10, 2024 |
| MSI           | PRO B550M-VC WIFI           | [566f6b1b2f](https://bsd-hardware.info/?probe=566f6b1b2f) | Oct 09, 2024 |
| MSI           | PRO B550M-VC WIFI           | [8ad5f1d680](https://bsd-hardware.info/?probe=8ad5f1d680) | Oct 09, 2024 |
| ASUSTek       | PRIME A320M-K/BR            | [cb476ab6ab](https://bsd-hardware.info/?probe=cb476ab6ab) | Oct 09, 2024 |
| MSI           | MAG B550M MORTAR WIFI       | [97e0c04743](https://bsd-hardware.info/?probe=97e0c04743) | Oct 07, 2024 |
| MSI           | H81M-P33                    | [fd33f9f838](https://bsd-hardware.info/?probe=fd33f9f838) | Oct 06, 2024 |
| ASUSTek       | P5Q-E                       | [a1eb43b45a](https://bsd-hardware.info/?probe=a1eb43b45a) | Oct 06, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [4c2adb15b8](https://bsd-hardware.info/?probe=4c2adb15b8) | Oct 06, 2024 |
| ASUSTek       | PRIME A320M-K/BR            | [e4e1bf6fa2](https://bsd-hardware.info/?probe=e4e1bf6fa2) | Oct 05, 2024 |
| Unknown       | Unknown                     | [de2fbce313](https://bsd-hardware.info/?probe=de2fbce313) | Oct 04, 2024 |
| ASUSTek       | Pro B560M-C                 | [a19e1fcd0e](https://bsd-hardware.info/?probe=a19e1fcd0e) | Oct 04, 2024 |
| MSI           | B450M PRO-VDH MAX           | [54719a13c6](https://bsd-hardware.info/?probe=54719a13c6) | Oct 03, 2024 |
| Intel         | DH67BL AAG10189-206         | [45d47552af](https://bsd-hardware.info/?probe=45d47552af) | Oct 02, 2024 |
| HP            | ProLiant MicroServer Gen... | [762010dd94](https://bsd-hardware.info/?probe=762010dd94) | Sep 30, 2024 |
| ASUSTek       | P7H55-M LX                  | [74ed82c97a](https://bsd-hardware.info/?probe=74ed82c97a) | Sep 30, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | [eb2586d6b5](https://bsd-hardware.info/?probe=eb2586d6b5) | Sep 30, 2024 |
| ASUSTek       | P8Z77-V LX                  | [7557aa9e0a](https://bsd-hardware.info/?probe=7557aa9e0a) | Sep 30, 2024 |
| ASUSTek       | P8Z77-V LX                  | [0372d7f73b](https://bsd-hardware.info/?probe=0372d7f73b) | Sep 30, 2024 |
| Gigabyte      | H61M-S2P                    | [63b5ffc944](https://bsd-hardware.info/?probe=63b5ffc944) | Sep 30, 2024 |
| Intel         | DB75EN AAG39650-400         | [800f9bb0b7](https://bsd-hardware.info/?probe=800f9bb0b7) | Sep 29, 2024 |
| Gigabyte      | X670E AORUS XTREME          | [3a93bb7f24](https://bsd-hardware.info/?probe=3a93bb7f24) | Sep 26, 2024 |
| HP            | ProLiant ML350 Gen9         | [14aefb427d](https://bsd-hardware.info/?probe=14aefb427d) | Sep 24, 2024 |
| Gigabyte      | B450 AORUS M                | [38e250ae59](https://bsd-hardware.info/?probe=38e250ae59) | Sep 24, 2024 |
| Unknown       | Unknown                     | [170341d296](https://bsd-hardware.info/?probe=170341d296) | Sep 19, 2024 |
| ASUSTek       | PRIME Z370-P II             | [5d6734e438](https://bsd-hardware.info/?probe=5d6734e438) | Sep 18, 2024 |
| Shuttle       | FZ270                       | [eff73dcdb7](https://bsd-hardware.info/?probe=eff73dcdb7) | Sep 17, 2024 |
| ASUSTek       | P7P55D                      | [dd70c06a90](https://bsd-hardware.info/?probe=dd70c06a90) | Sep 17, 2024 |
| ASRock        | B550 Taichi                 | [4d8657f05e](https://bsd-hardware.info/?probe=4d8657f05e) | Sep 17, 2024 |
| Unknown       | Unknown                     | [bda2cdb68d](https://bsd-hardware.info/?probe=bda2cdb68d) | Sep 16, 2024 |
| Dell          | 0T7D40 A01                  | [c69ca23766](https://bsd-hardware.info/?probe=c69ca23766) | Sep 15, 2024 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [0582bbb64f](https://bsd-hardware.info/?probe=0582bbb64f) | Sep 15, 2024 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [25bed13946](https://bsd-hardware.info/?probe=25bed13946) | Sep 15, 2024 |
| MSI           | 970 GAMING                  | [54a49ef19c](https://bsd-hardware.info/?probe=54a49ef19c) | Sep 14, 2024 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [7fd8e4f735](https://bsd-hardware.info/?probe=7fd8e4f735) | Sep 14, 2024 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [91c0b794d3](https://bsd-hardware.info/?probe=91c0b794d3) | Sep 14, 2024 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [df5b4013a0](https://bsd-hardware.info/?probe=df5b4013a0) | Sep 14, 2024 |
| ASUSTek       | PRIME A520M-K               | [b4a25585d8](https://bsd-hardware.info/?probe=b4a25585d8) | Sep 13, 2024 |
| Unknown       | Unknown                     | [92a6c31579](https://bsd-hardware.info/?probe=92a6c31579) | Sep 12, 2024 |
| MSI           | H81M-P33                    | [501f155011](https://bsd-hardware.info/?probe=501f155011) | Sep 08, 2024 |
| ASUSTek       | P5Q-E                       | [6d991754a1](https://bsd-hardware.info/?probe=6d991754a1) | Sep 08, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [4555603f55](https://bsd-hardware.info/?probe=4555603f55) | Sep 08, 2024 |
| Lenovo        | 36E2 SDK0J40709 WIN 3259... | [402a485372](https://bsd-hardware.info/?probe=402a485372) | Sep 05, 2024 |
| Lenovo        | 36E2 SDK0J40709 WIN 3259... | [f9efdc8b31](https://bsd-hardware.info/?probe=f9efdc8b31) | Sep 05, 2024 |
| Dell          | 0KYWH7 A03                  | [e7685ec40f](https://bsd-hardware.info/?probe=e7685ec40f) | Sep 05, 2024 |
| Lenovo        | SHARKBAY NOK                | [024f86a86f](https://bsd-hardware.info/?probe=024f86a86f) | Sep 03, 2024 |
| MSI           | H81M-P33                    | [e3c0874758](https://bsd-hardware.info/?probe=e3c0874758) | Sep 01, 2024 |
| ASUSTek       | P5Q-E                       | [50014d5a6e](https://bsd-hardware.info/?probe=50014d5a6e) | Sep 01, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [6d2430cad3](https://bsd-hardware.info/?probe=6d2430cad3) | Sep 01, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | [a740cbb4da](https://bsd-hardware.info/?probe=a740cbb4da) | Aug 31, 2024 |
| ASUSTek       | M5A78L LE                   | [ce3bee8f61](https://bsd-hardware.info/?probe=ce3bee8f61) | Aug 29, 2024 |
| Dell          | 06X1TJ A01                  | [a3a44c5d03](https://bsd-hardware.info/?probe=a3a44c5d03) | Aug 26, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [db7a0dda31](https://bsd-hardware.info/?probe=db7a0dda31) | Aug 26, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [c56df5fe7c](https://bsd-hardware.info/?probe=c56df5fe7c) | Aug 25, 2024 |
| MSI           | B85M-G43                    | [54097f5004](https://bsd-hardware.info/?probe=54097f5004) | Aug 25, 2024 |
| Lenovo        | MAHOBAY                     | [c29f65325f](https://bsd-hardware.info/?probe=c29f65325f) | Aug 24, 2024 |
| ASUSTek       | Z10PA-U8 Series             | [4e57035d21](https://bsd-hardware.info/?probe=4e57035d21) | Aug 24, 2024 |
| ASRockRack    | X470D4U                     | [841d8b72ac](https://bsd-hardware.info/?probe=841d8b72ac) | Aug 24, 2024 |
| MSI           | B450M PRO-M2 V2             | [fe3c1c44f8](https://bsd-hardware.info/?probe=fe3c1c44f8) | Aug 24, 2024 |
| Gigabyte      | B550M DS3H                  | [04c96f56e7](https://bsd-hardware.info/?probe=04c96f56e7) | Aug 22, 2024 |
| ASUSTek       | P7P55D                      | [4d303038e8](https://bsd-hardware.info/?probe=4d303038e8) | Aug 21, 2024 |
| Gigabyte      | Z77N-WIFI                   | [ce8cad61be](https://bsd-hardware.info/?probe=ce8cad61be) | Aug 21, 2024 |
| Aquarius      | AQH610T SKU 00              | [62fbfbc201](https://bsd-hardware.info/?probe=62fbfbc201) | Aug 20, 2024 |
| Aquarius      | AQH610T SKU 00              | [0b32fb7cf5](https://bsd-hardware.info/?probe=0b32fb7cf5) | Aug 20, 2024 |
| ASUSTek       | P7P55D                      | [d457cff496](https://bsd-hardware.info/?probe=d457cff496) | Aug 19, 2024 |
| MSI           | H81M-P33                    | [6b69bd06db](https://bsd-hardware.info/?probe=6b69bd06db) | Aug 18, 2024 |
| ASUSTek       | P5Q-E                       | [f4e719a968](https://bsd-hardware.info/?probe=f4e719a968) | Aug 18, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [5fe961f1a0](https://bsd-hardware.info/?probe=5fe961f1a0) | Aug 18, 2024 |
| MSI           | B450M PRO-VDH PLUS          | [d9c45f3bef](https://bsd-hardware.info/?probe=d9c45f3bef) | Aug 15, 2024 |
| Dell          | 0T7D40 A01                  | [d051177b97](https://bsd-hardware.info/?probe=d051177b97) | Aug 12, 2024 |
| MSI           | B450I GAMING PLUS MAX WI... | [abca29e921](https://bsd-hardware.info/?probe=abca29e921) | Aug 12, 2024 |
| MSI           | B550 GAMING GEN3            | [09c4b51ebb](https://bsd-hardware.info/?probe=09c4b51ebb) | Aug 12, 2024 |
| ASUSTek       | P5Q-E                       | [eb7aecd79c](https://bsd-hardware.info/?probe=eb7aecd79c) | Aug 11, 2024 |
| BCM           | MX3160N                     | [21903781a9](https://bsd-hardware.info/?probe=21903781a9) | Aug 10, 2024 |
| MSI           | B350M BAZOOKA               | [ea0e584b5e](https://bsd-hardware.info/?probe=ea0e584b5e) | Aug 09, 2024 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | [4b81b4bd7f](https://bsd-hardware.info/?probe=4b81b4bd7f) | Aug 08, 2024 |
| Unknown       | Unknown                     | [d7fba3c543](https://bsd-hardware.info/?probe=d7fba3c543) | Aug 08, 2024 |
| ASUSTek       | M5A97 LE R2.0               | [19c38af5df](https://bsd-hardware.info/?probe=19c38af5df) | Aug 08, 2024 |
| Shuttle       | FZ270                       | [a509bdd918](https://bsd-hardware.info/?probe=a509bdd918) | Aug 06, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [3a97ebc128](https://bsd-hardware.info/?probe=3a97ebc128) | Aug 05, 2024 |
| ASUSTek       | Z10PA-U8 Series             | [6c162eb9de](https://bsd-hardware.info/?probe=6c162eb9de) | Aug 04, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d5924117c3](https://bsd-hardware.info/?probe=d5924117c3) | Aug 04, 2024 |
| Unknown       | DH61BR G32662-203           | [596a891e0a](https://bsd-hardware.info/?probe=596a891e0a) | Aug 04, 2024 |
| AMI           | Intel                       | [8cd545a638](https://bsd-hardware.info/?probe=8cd545a638) | Aug 03, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | [f7134ef010](https://bsd-hardware.info/?probe=f7134ef010) | Jul 31, 2024 |
| Unknown       | Unknown                     | [875611436f](https://bsd-hardware.info/?probe=875611436f) | Jul 30, 2024 |
| Unknown       | Unknown                     | [483220bff7](https://bsd-hardware.info/?probe=483220bff7) | Jul 29, 2024 |
| ASRock        | C2550D4I                    | [2eaa4d9c12](https://bsd-hardware.info/?probe=2eaa4d9c12) | Jul 28, 2024 |
| MSI           | H81M-P33                    | [c810c53c9c](https://bsd-hardware.info/?probe=c810c53c9c) | Jul 28, 2024 |
| ASUSTek       | STRIX B250G GAMING          | [f18c3a7168](https://bsd-hardware.info/?probe=f18c3a7168) | Jul 27, 2024 |
| Unknown       | DH61BR G32662-203           | [6e073b5233](https://bsd-hardware.info/?probe=6e073b5233) | Jul 26, 2024 |
| Apple         | Mac-F221BEC8                | [dd834b1229](https://bsd-hardware.info/?probe=dd834b1229) | Jul 26, 2024 |
| Dell EMC      | EDGE680-CPU A00             | [4934b78db6](https://bsd-hardware.info/?probe=4934b78db6) | Jul 24, 2024 |
| Unknown       | Unknown                     | [2e77b6eb96](https://bsd-hardware.info/?probe=2e77b6eb96) | Jul 21, 2024 |
| Unknown       | Unknown                     | [0a7faa3d8b](https://bsd-hardware.info/?probe=0a7faa3d8b) | Jul 21, 2024 |
| HP            | 158A                        | [3645ec654d](https://bsd-hardware.info/?probe=3645ec654d) | Jul 18, 2024 |
| Supermicro    | X7DVL-3                     | [cee10ef296](https://bsd-hardware.info/?probe=cee10ef296) | Jul 17, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [cca488376a](https://bsd-hardware.info/?probe=cca488376a) | Jul 14, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [37831b36d6](https://bsd-hardware.info/?probe=37831b36d6) | Jul 14, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [bc91fdaa8c](https://bsd-hardware.info/?probe=bc91fdaa8c) | Jul 14, 2024 |
| MSI           | H81M-P33                    | [b218dc32a8](https://bsd-hardware.info/?probe=b218dc32a8) | Jul 14, 2024 |
| ASUSTek       | P5Q-E                       | [a93627695c](https://bsd-hardware.info/?probe=a93627695c) | Jul 14, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [444d8544de](https://bsd-hardware.info/?probe=444d8544de) | Jul 14, 2024 |
| iKOOLCORE ... | R2                          | [457c9ab408](https://bsd-hardware.info/?probe=457c9ab408) | Jul 14, 2024 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [c853ac7461](https://bsd-hardware.info/?probe=c853ac7461) | Jul 13, 2024 |
| MSI           | PRO B760-VC WIFI            | [e7fae0a304](https://bsd-hardware.info/?probe=e7fae0a304) | Jul 11, 2024 |
| ASUSTek       | ProArt Z790-CREATOR WIFI    | [9e1ff60a44](https://bsd-hardware.info/?probe=9e1ff60a44) | Jul 11, 2024 |
| HP            | 83E8                        | [06b44184a4](https://bsd-hardware.info/?probe=06b44184a4) | Jul 09, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [4b9cdbf4d2](https://bsd-hardware.info/?probe=4b9cdbf4d2) | Jul 07, 2024 |
| MSI           | H81M-P33                    | [e76ffa15a4](https://bsd-hardware.info/?probe=e76ffa15a4) | Jul 07, 2024 |
| ASUSTek       | P5Q-E                       | [a33387b7a5](https://bsd-hardware.info/?probe=a33387b7a5) | Jul 07, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [e923df9fa3](https://bsd-hardware.info/?probe=e923df9fa3) | Jul 07, 2024 |
| Gigabyte      | G41M-Combo                  | [ddeb9d1478](https://bsd-hardware.info/?probe=ddeb9d1478) | Jul 05, 2024 |
| MSI           | B450M-A PRO MAX             | [da4d14dbcb](https://bsd-hardware.info/?probe=da4d14dbcb) | Jul 03, 2024 |
| ASUSTek       | PRIME B660M-K D4            | [22e00e24fa](https://bsd-hardware.info/?probe=22e00e24fa) | Jul 03, 2024 |
| Gigabyte      | B450M DS3H-CF               | [df8915643d](https://bsd-hardware.info/?probe=df8915643d) | Jul 02, 2024 |
| ASUSTek       | P9X79 WS                    | [08fdfb0356](https://bsd-hardware.info/?probe=08fdfb0356) | Jul 02, 2024 |
| Gigabyte      | A320M-S2H-CF                | [4bfb98c555](https://bsd-hardware.info/?probe=4bfb98c555) | Jul 01, 2024 |
| HP            | 18E7                        | [ece3f5dee1](https://bsd-hardware.info/?probe=ece3f5dee1) | Jul 01, 2024 |
| HP            | 18E7                        | [87f79e3014](https://bsd-hardware.info/?probe=87f79e3014) | Jul 01, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | [38cebb1de0](https://bsd-hardware.info/?probe=38cebb1de0) | Jun 30, 2024 |
| ASRock        | X300M-STX                   | [2c4cc4c744](https://bsd-hardware.info/?probe=2c4cc4c744) | Jun 26, 2024 |
| MSI           | PRO B760M-P                 | [18ecac9dc3](https://bsd-hardware.info/?probe=18ecac9dc3) | Jun 26, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [c2ac893b66](https://bsd-hardware.info/?probe=c2ac893b66) | Jun 25, 2024 |
| Gigabyte      | X570 AORUS ELITE            | [6df2b85c04](https://bsd-hardware.info/?probe=6df2b85c04) | Jun 24, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6d499422cd](https://bsd-hardware.info/?probe=6d499422cd) | Jun 23, 2024 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [cd04d52df4](https://bsd-hardware.info/?probe=cd04d52df4) | Jun 22, 2024 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [c77c97d1e0](https://bsd-hardware.info/?probe=c77c97d1e0) | Jun 21, 2024 |
| Dell          | 0KC9NP A01                  | [bb7ac1fa79](https://bsd-hardware.info/?probe=bb7ac1fa79) | Jun 19, 2024 |
| Unknown       | Unknown                     | [dd5f673761](https://bsd-hardware.info/?probe=dd5f673761) | Jun 17, 2024 |
| Alienware     | 0T76PD A01                  | [df36192471](https://bsd-hardware.info/?probe=df36192471) | Jun 16, 2024 |
| ASUSTek       | Z10PA-U8 Series             | [ed87446558](https://bsd-hardware.info/?probe=ed87446558) | Jun 15, 2024 |
| ASUSTek       | Z10PA-U8 Series             | [386e93d33b](https://bsd-hardware.info/?probe=386e93d33b) | Jun 15, 2024 |
| Dell          | 0Y2K8N A01                  | [9754002682](https://bsd-hardware.info/?probe=9754002682) | Jun 14, 2024 |
| HP            | ProLiant ML350p Gen8        | [820bfd0c77](https://bsd-hardware.info/?probe=820bfd0c77) | Jun 14, 2024 |
| MSI           | B85M-G43                    | [933e4d7430](https://bsd-hardware.info/?probe=933e4d7430) | Jun 14, 2024 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | [3ef620dd9a](https://bsd-hardware.info/?probe=3ef620dd9a) | Jun 12, 2024 |
| MSI           | B450I GAMING PLUS MAX WI... | [8a90f18f6a](https://bsd-hardware.info/?probe=8a90f18f6a) | Jun 11, 2024 |
| Gigabyte      | Z370P D3-CF                 | [68dcdfd73f](https://bsd-hardware.info/?probe=68dcdfd73f) | Jun 10, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [0b068fd252](https://bsd-hardware.info/?probe=0b068fd252) | Jun 07, 2024 |
| TYAN Compu... | Intel 440BX/GX Rev. 4       | [84ad498f3e](https://bsd-hardware.info/?probe=84ad498f3e) | Jun 07, 2024 |
| Dell          | 0Y2V0C A03                  | [efc4ae0ffc](https://bsd-hardware.info/?probe=efc4ae0ffc) | Jun 04, 2024 |
| ASRock        | X99 Extreme4                | [af182c3b9b](https://bsd-hardware.info/?probe=af182c3b9b) | Jun 04, 2024 |
| Dell          | 0Y2V0C A03                  | [515e7801ba](https://bsd-hardware.info/?probe=515e7801ba) | Jun 04, 2024 |
| MSI           | A520M-A PRO                 | [403fce848d](https://bsd-hardware.info/?probe=403fce848d) | Jun 02, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | [eafa09a812](https://bsd-hardware.info/?probe=eafa09a812) | May 31, 2024 |
| ASUSTek       | PRIME Z270-P                | [e9d5c616a0](https://bsd-hardware.info/?probe=e9d5c616a0) | May 31, 2024 |
| pine64        | rock64_rk3328               | [d417f7c182](https://bsd-hardware.info/?probe=d417f7c182) | May 30, 2024 |
| MSI           | H110M PRO-VH                | [7fdc7a3552](https://bsd-hardware.info/?probe=7fdc7a3552) | May 30, 2024 |
| Gigabyte      | Z790 EAGLE AX               | [65d52d2137](https://bsd-hardware.info/?probe=65d52d2137) | May 28, 2024 |
| ASRock        | B85M Pro3                   | [e534762e31](https://bsd-hardware.info/?probe=e534762e31) | May 26, 2024 |
| Gigabyte      | GA-990FXA-UD5               | [73ad6d19d7](https://bsd-hardware.info/?probe=73ad6d19d7) | May 26, 2024 |
| Gigabyte      | Z790 EAGLE AX               | [354c2b5195](https://bsd-hardware.info/?probe=354c2b5195) | May 26, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [1f9f3170fd](https://bsd-hardware.info/?probe=1f9f3170fd) | May 25, 2024 |
| Dell          | 0M9KCM A02                  | [eef1fbf128](https://bsd-hardware.info/?probe=eef1fbf128) | May 24, 2024 |
| Unknown       | Unknown                     | [a4498a9e10](https://bsd-hardware.info/?probe=a4498a9e10) | May 24, 2024 |
| Apple         | Mac-F221BEC8                | [169fdec0c9](https://bsd-hardware.info/?probe=169fdec0c9) | May 22, 2024 |
| Dell          | 04Y8V0 A02                  | [7ed99b125e](https://bsd-hardware.info/?probe=7ed99b125e) | May 22, 2024 |
| Dell          | 040DDP A01                  | [402d9046c4](https://bsd-hardware.info/?probe=402d9046c4) | May 22, 2024 |
| ASRock        | B550 Phantom Gaming 4       | [e9e0fec5c7](https://bsd-hardware.info/?probe=e9e0fec5c7) | May 21, 2024 |
| ASRock        | B550 PG Velocita            | [76ab3f40af](https://bsd-hardware.info/?probe=76ab3f40af) | May 20, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [ae59cb0577](https://bsd-hardware.info/?probe=ae59cb0577) | May 16, 2024 |
| MSI           | H81M-P33                    | [ee2140f432](https://bsd-hardware.info/?probe=ee2140f432) | May 12, 2024 |
| ASUSTek       | P5Q-E                       | [787f507077](https://bsd-hardware.info/?probe=787f507077) | May 12, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [642b430f22](https://bsd-hardware.info/?probe=642b430f22) | May 12, 2024 |
| ASUSTek       | H110M-C                     | [fbfee7e505](https://bsd-hardware.info/?probe=fbfee7e505) | May 09, 2024 |
| ASUSTek       | TUF B360-PLUS GAMING        | [c809f82bd6](https://bsd-hardware.info/?probe=c809f82bd6) | May 09, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | [c23ee67c69](https://bsd-hardware.info/?probe=c23ee67c69) | May 08, 2024 |
| MSI           | MS-7097                     | [df5c7407fd](https://bsd-hardware.info/?probe=df5c7407fd) | May 06, 2024 |
| Dell          | 0GXM1W A01                  | [1238d729a7](https://bsd-hardware.info/?probe=1238d729a7) | May 06, 2024 |
| ASUSTek       | G11CD                       | [e4d4f0e1b2](https://bsd-hardware.info/?probe=e4d4f0e1b2) | May 06, 2024 |
| ASUSTek       | PRIME Z690-P D4             | [e7a48c0ebb](https://bsd-hardware.info/?probe=e7a48c0ebb) | May 05, 2024 |
| MSI           | H81M-P33                    | [db35e993b4](https://bsd-hardware.info/?probe=db35e993b4) | May 05, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [76bd355935](https://bsd-hardware.info/?probe=76bd355935) | May 05, 2024 |
| ASUSTek       | P5Q-E                       | [4e42133f58](https://bsd-hardware.info/?probe=4e42133f58) | May 05, 2024 |
| Protectli     | FW2B                        | [92725f96b8](https://bsd-hardware.info/?probe=92725f96b8) | May 05, 2024 |
| Gigabyte      | GA-78LMT-S2 sex             | [89beae510f](https://bsd-hardware.info/?probe=89beae510f) | May 04, 2024 |
| Dell          | 0MGK50 A02                  | [6f9b5b3cad](https://bsd-hardware.info/?probe=6f9b5b3cad) | May 03, 2024 |
| Gigabyte      | Z370P D3-CF                 | [591ac5deba](https://bsd-hardware.info/?probe=591ac5deba) | May 03, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [5240c726c5](https://bsd-hardware.info/?probe=5240c726c5) | May 03, 2024 |
| ASUSTek       | TUF Gaming A620-PRO WIFI    | [a186355a65](https://bsd-hardware.info/?probe=a186355a65) | May 02, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [db2e2d1fbc](https://bsd-hardware.info/?probe=db2e2d1fbc) | May 02, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | [15e26ac086](https://bsd-hardware.info/?probe=15e26ac086) | Apr 30, 2024 |
| ASUSTek       | Z170 PRO GAMING             | [72deae70f8](https://bsd-hardware.info/?probe=72deae70f8) | Apr 29, 2024 |
| Dell          | 07N90W A02                  | [f0520bbeb9](https://bsd-hardware.info/?probe=f0520bbeb9) | Apr 29, 2024 |
| Quantum en... | HackBoard 2                 | [a7b0ea1eca](https://bsd-hardware.info/?probe=a7b0ea1eca) | Apr 28, 2024 |
| Shenzhen M... | AHWSA                       | [eb205801e7](https://bsd-hardware.info/?probe=eb205801e7) | Apr 27, 2024 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [ac75273460](https://bsd-hardware.info/?probe=ac75273460) | Apr 25, 2024 |
| Dell          | 048DY8 A00                  | [9604806e18](https://bsd-hardware.info/?probe=9604806e18) | Apr 24, 2024 |
| ASUSTek       | M5A97 LE R2.0               | [0b322f0da8](https://bsd-hardware.info/?probe=0b322f0da8) | Apr 24, 2024 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [f5683de21a](https://bsd-hardware.info/?probe=f5683de21a) | Apr 24, 2024 |
| ASUSTek       | P8H61-M LX                  | [eaee094e07](https://bsd-hardware.info/?probe=eaee094e07) | Apr 23, 2024 |
| Gigabyte      | X570 AORUS MASTER           | [58a64ecc64](https://bsd-hardware.info/?probe=58a64ecc64) | Apr 23, 2024 |
| Lenovo        | 367D 31900059 STD           | [eed4d35722](https://bsd-hardware.info/?probe=eed4d35722) | Apr 21, 2024 |
| Gigabyte      | B460 AORUS PRO AC           | [fe0730cde5](https://bsd-hardware.info/?probe=fe0730cde5) | Apr 20, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [572876d341](https://bsd-hardware.info/?probe=572876d341) | Apr 20, 2024 |
| AZW           | SER V1                      | [4e085db4ef](https://bsd-hardware.info/?probe=4e085db4ef) | Apr 19, 2024 |
| HP            | 3646h                       | [615b37fb0f](https://bsd-hardware.info/?probe=615b37fb0f) | Apr 19, 2024 |
| ASUSTek       | Maximus VII HERO            | [909b53a869](https://bsd-hardware.info/?probe=909b53a869) | Apr 19, 2024 |
| Gigabyte      | Z590I AORUS ULTRA           | [bf06ab7481](https://bsd-hardware.info/?probe=bf06ab7481) | Apr 19, 2024 |
| Intel         | DN2820FYK H24582-201        | [1bc36f8af1](https://bsd-hardware.info/?probe=1bc36f8af1) | Apr 17, 2024 |
| Lenovo        | 367D 31900059 STD           | [b6e893449c](https://bsd-hardware.info/?probe=b6e893449c) | Apr 17, 2024 |
| Intel         | DP965LT AAD41694-210        | [90e9ba9d77](https://bsd-hardware.info/?probe=90e9ba9d77) | Apr 16, 2024 |
| Intel         | MAHOBAY                     | [c76dc714f2](https://bsd-hardware.info/?probe=c76dc714f2) | Apr 15, 2024 |
| Unknown       | Unknown                     | [08cdf907e4](https://bsd-hardware.info/?probe=08cdf907e4) | Apr 15, 2024 |
| Unknown       | Unknown                     | [75fccc1dbe](https://bsd-hardware.info/?probe=75fccc1dbe) | Apr 15, 2024 |
| Unknown       | Unknown                     | [ba545bb931](https://bsd-hardware.info/?probe=ba545bb931) | Apr 15, 2024 |
| MSI           | B450I GAMING PLUS MAX WI... | [7ab7294373](https://bsd-hardware.info/?probe=7ab7294373) | Apr 14, 2024 |
| Unknown       | Unknown                     | [34d08de74d](https://bsd-hardware.info/?probe=34d08de74d) | Apr 13, 2024 |
| ASRock        | X99 Extreme4                | [8d5a19e786](https://bsd-hardware.info/?probe=8d5a19e786) | Apr 13, 2024 |
| ASRock        | X99 Extreme4                | [f2fdbc8d66](https://bsd-hardware.info/?probe=f2fdbc8d66) | Apr 13, 2024 |
| Fujitsu       | D3427-A1 S26361-D3427-A1    | [0f9af3b2b5](https://bsd-hardware.info/?probe=0f9af3b2b5) | Apr 13, 2024 |
| Dell          | 0GM819                      | [6140b5e6ad](https://bsd-hardware.info/?probe=6140b5e6ad) | Apr 12, 2024 |
| MSI           | A520M-A PRO                 | [ad2494f0c0](https://bsd-hardware.info/?probe=ad2494f0c0) | Apr 11, 2024 |
| ASUSTek       | Z97-A                       | [2f83e16bd9](https://bsd-hardware.info/?probe=2f83e16bd9) | Apr 11, 2024 |
| Gigabyte      | H97M-D3H                    | [8c0a605e99](https://bsd-hardware.info/?probe=8c0a605e99) | Apr 10, 2024 |
| MSI           | A520M-A PRO                 | [3fb8a577ad](https://bsd-hardware.info/?probe=3fb8a577ad) | Apr 10, 2024 |
| MSI           | B450M MORTAR MAX            | [816bfd4777](https://bsd-hardware.info/?probe=816bfd4777) | Apr 09, 2024 |
| Intel         | D525MW AAE93082-401         | [9a37f5660f](https://bsd-hardware.info/?probe=9a37f5660f) | Apr 09, 2024 |
| ASUSTek       | PRIME B650-PLUS             | [1335666f76](https://bsd-hardware.info/?probe=1335666f76) | Apr 09, 2024 |
| ASRock        | AMD BC-250                  | [3b38d89497](https://bsd-hardware.info/?probe=3b38d89497) | Apr 09, 2024 |
| HP            | ProLiant ML310e Gen8        | [040c686c32](https://bsd-hardware.info/?probe=040c686c32) | Apr 07, 2024 |
| Foxconn       | H61MXV/H67MXV               | [53663c4ae5](https://bsd-hardware.info/?probe=53663c4ae5) | Apr 07, 2024 |
| SolidRun      | CEX7 Platform               | [7c5ed3c2fe](https://bsd-hardware.info/?probe=7c5ed3c2fe) | Apr 06, 2024 |
| HP            | 2B28                        | [b4f2207b5d](https://bsd-hardware.info/?probe=b4f2207b5d) | Apr 06, 2024 |
| HP            | 2B28                        | [5a64d57e01](https://bsd-hardware.info/?probe=5a64d57e01) | Apr 05, 2024 |
| ASRock        | Z790M-ITX WiFi              | [b2bbe7eb8d](https://bsd-hardware.info/?probe=b2bbe7eb8d) | Apr 04, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [0ab49168ee](https://bsd-hardware.info/?probe=0ab49168ee) | Apr 02, 2024 |
| ASRock        | Q1900-ITX                   | [cfceb60c9e](https://bsd-hardware.info/?probe=cfceb60c9e) | Mar 28, 2024 |
| ASRock        | Q1900-ITX                   | [d29def9398](https://bsd-hardware.info/?probe=d29def9398) | Mar 28, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS        | [f960805584](https://bsd-hardware.info/?probe=f960805584) | Mar 26, 2024 |
| Intel         | DH61CR AAG14064-204         | [c1d0a393a3](https://bsd-hardware.info/?probe=c1d0a393a3) | Mar 25, 2024 |
| ASRock        | J5040-ITX                   | [075487240d](https://bsd-hardware.info/?probe=075487240d) | Mar 25, 2024 |
| ASUSTek       | PRIME J4005I-C              | [33c6bf6200](https://bsd-hardware.info/?probe=33c6bf6200) | Mar 25, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | [c2fcfcd39d](https://bsd-hardware.info/?probe=c2fcfcd39d) | Mar 24, 2024 |
| Intel         | D53427RKE G87971-403        | [5cf0576fee](https://bsd-hardware.info/?probe=5cf0576fee) | Mar 23, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [c00f4d37cc](https://bsd-hardware.info/?probe=c00f4d37cc) | Mar 22, 2024 |
| HP            | ProLiant MicroServer        | [7fa3a9e12a](https://bsd-hardware.info/?probe=7fa3a9e12a) | Mar 22, 2024 |
| HP            | ProLiant MicroServer        | [c158a70e91](https://bsd-hardware.info/?probe=c158a70e91) | Mar 22, 2024 |
| PC Engines    | APU2                        | [1f2d9aef5b](https://bsd-hardware.info/?probe=1f2d9aef5b) | Mar 22, 2024 |
| Gigabyte      | H81M-S2V                    | [f04f1f2154](https://bsd-hardware.info/?probe=f04f1f2154) | Mar 20, 2024 |
| ASUSTek       | PRIME A520M-K               | [aeaeb5bff5](https://bsd-hardware.info/?probe=aeaeb5bff5) | Mar 19, 2024 |
| Unknown       | Unknown                     | [9acbce6ef2](https://bsd-hardware.info/?probe=9acbce6ef2) | Mar 19, 2024 |
| Protectli     | FW6 Ver                     | [bab06633ba](https://bsd-hardware.info/?probe=bab06633ba) | Mar 19, 2024 |
| Lenovo        | 30D9 SDK0J40700 WIN 3258... | [139d9be65a](https://bsd-hardware.info/?probe=139d9be65a) | Mar 18, 2024 |
| ASRock        | B450M-HDV R4.0              | [bbc697af5e](https://bsd-hardware.info/?probe=bbc697af5e) | Mar 17, 2024 |
| Unknown       | Unknown                     | [2776bdbd27](https://bsd-hardware.info/?probe=2776bdbd27) | Mar 16, 2024 |
| Alienware     | 0446JC A01                  | [d207e3f488](https://bsd-hardware.info/?probe=d207e3f488) | Mar 16, 2024 |
| Dell          | 0T7D40 A01                  | [5b8f4fe788](https://bsd-hardware.info/?probe=5b8f4fe788) | Mar 14, 2024 |
| Dell          | 08NPPY A00                  | [adcbf8a526](https://bsd-hardware.info/?probe=adcbf8a526) | Mar 12, 2024 |
| Unknown       | Unknown                     | [820c6cbe0c](https://bsd-hardware.info/?probe=820c6cbe0c) | Mar 10, 2024 |
| ZOTAC         | Unknown                     | [9217678a4f](https://bsd-hardware.info/?probe=9217678a4f) | Mar 10, 2024 |
| Dell          | 002KVM A01                  | [92ae9e6766](https://bsd-hardware.info/?probe=92ae9e6766) | Mar 07, 2024 |
| ASUSTek       | PRIME A520M-E               | [b0e5a68883](https://bsd-hardware.info/?probe=b0e5a68883) | Mar 03, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | [cd922b0100](https://bsd-hardware.info/?probe=cd922b0100) | Feb 29, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0857785c6d](https://bsd-hardware.info/?probe=0857785c6d) | Feb 27, 2024 |
| ASUSTek       | P8P67                       | [1971d6c84c](https://bsd-hardware.info/?probe=1971d6c84c) | Feb 27, 2024 |
| Supermicro    | X7DWE                       | [23e991022f](https://bsd-hardware.info/?probe=23e991022f) | Feb 27, 2024 |
| ASUSTek       | M4A89TD PRO USB3            | [c0561cccdd](https://bsd-hardware.info/?probe=c0561cccdd) | Feb 26, 2024 |
| MSI           | H81M-P33                    | [7e215d6165](https://bsd-hardware.info/?probe=7e215d6165) | Feb 25, 2024 |
| ASUSTek       | P5Q-E                       | [d86a9bc700](https://bsd-hardware.info/?probe=d86a9bc700) | Feb 25, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [7c8bd6104e](https://bsd-hardware.info/?probe=7c8bd6104e) | Feb 25, 2024 |
| ASUSTek       | PRIME B450M-A               | [101b5912bf](https://bsd-hardware.info/?probe=101b5912bf) | Feb 25, 2024 |
| Dell          | 0T7D40 A01                  | [151b04e792](https://bsd-hardware.info/?probe=151b04e792) | Feb 23, 2024 |
| Advatronix... | C2750D4I v1.0               | [ba0ab14231](https://bsd-hardware.info/?probe=ba0ab14231) | Feb 22, 2024 |
| ASRock        | B650 PG Lightning           | [54d6c96d25](https://bsd-hardware.info/?probe=54d6c96d25) | Feb 22, 2024 |
| Unknown       | Unknown                     | [a5ae8a1c9d](https://bsd-hardware.info/?probe=a5ae8a1c9d) | Feb 21, 2024 |
| ASRock        | 4X4-5000 Series             | [dc9ef8f030](https://bsd-hardware.info/?probe=dc9ef8f030) | Feb 21, 2024 |
| Gigabyte      | Z97X-UD3H-CF                | [054056b5fa](https://bsd-hardware.info/?probe=054056b5fa) | Feb 21, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [59c7610a80](https://bsd-hardware.info/?probe=59c7610a80) | Feb 19, 2024 |
| Dell          | 0FF3FN A00                  | [cb83e35a3e](https://bsd-hardware.info/?probe=cb83e35a3e) | Feb 19, 2024 |
| Gigabyte      | Z97X-UD3H-CF                | [d84e00c746](https://bsd-hardware.info/?probe=d84e00c746) | Feb 19, 2024 |
| Gigabyte      | G1.Sniper H6                | [471f2213f0](https://bsd-hardware.info/?probe=471f2213f0) | Feb 19, 2024 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [057ab23bee](https://bsd-hardware.info/?probe=057ab23bee) | Feb 18, 2024 |
| Dell          | 0T7D40 A01                  | [7aeebe2c82](https://bsd-hardware.info/?probe=7aeebe2c82) | Feb 18, 2024 |
| ASUSTek       | P5Q-E                       | [6c06931b93](https://bsd-hardware.info/?probe=6c06931b93) | Feb 18, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [84aa76dfc8](https://bsd-hardware.info/?probe=84aa76dfc8) | Feb 18, 2024 |
| HP            | 83E9                        | [f5a6f9001d](https://bsd-hardware.info/?probe=f5a6f9001d) | Feb 17, 2024 |
| ASUSTek       | PRIME A520M-A II            | [acb70accb8](https://bsd-hardware.info/?probe=acb70accb8) | Feb 14, 2024 |
| ASUSTek       | PRIME X370-PRO              | [7a18edf610](https://bsd-hardware.info/?probe=7a18edf610) | Feb 13, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [d24c0ab2c0](https://bsd-hardware.info/?probe=d24c0ab2c0) | Feb 13, 2024 |
| ASRock        | Z590 Steel Legend           | [e7dfc1ffe5](https://bsd-hardware.info/?probe=e7dfc1ffe5) | Feb 13, 2024 |
| ASRock        | Z590 Steel Legend           | [30702fa4b5](https://bsd-hardware.info/?probe=30702fa4b5) | Feb 13, 2024 |
| Dell          | 0FF3FN A00                  | [56b53a9e68](https://bsd-hardware.info/?probe=56b53a9e68) | Feb 11, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [fa2107c718](https://bsd-hardware.info/?probe=fa2107c718) | Feb 11, 2024 |
| ASUSTek       | P5Q-E                       | [08506a1aff](https://bsd-hardware.info/?probe=08506a1aff) | Feb 11, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [5f3d8e3288](https://bsd-hardware.info/?probe=5f3d8e3288) | Feb 11, 2024 |
| Gigabyte      | H81M-D2V                    | [1b2b064c64](https://bsd-hardware.info/?probe=1b2b064c64) | Feb 08, 2024 |
| ASRock        | B450M-HDV                   | [841a005fc8](https://bsd-hardware.info/?probe=841a005fc8) | Feb 06, 2024 |
| MSI           | PRO B550M-P GEN3            | [6a6b1dbe8f](https://bsd-hardware.info/?probe=6a6b1dbe8f) | Feb 06, 2024 |
| Lenovo        | ThinkCentre M90p 3853RN9    | [c0395ca728](https://bsd-hardware.info/?probe=c0395ca728) | Feb 05, 2024 |
| MSI           | H81M-P33                    | [444eaddd27](https://bsd-hardware.info/?probe=444eaddd27) | Feb 04, 2024 |
| ASUSTek       | P5Q-E                       | [87358bcf94](https://bsd-hardware.info/?probe=87358bcf94) | Feb 04, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [94f15f8857](https://bsd-hardware.info/?probe=94f15f8857) | Feb 04, 2024 |
| ASUSTek       | Pro B560M-C                 | [676019447d](https://bsd-hardware.info/?probe=676019447d) | Feb 03, 2024 |
| Gigabyte      | GA-MA78GM-S2HP              | [c0ca7a18ae](https://bsd-hardware.info/?probe=c0ca7a18ae) | Feb 01, 2024 |
| Gigabyte      | Z97-HD3                     | [b41ed8f957](https://bsd-hardware.info/?probe=b41ed8f957) | Feb 01, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | [aae98167a1](https://bsd-hardware.info/?probe=aae98167a1) | Jan 31, 2024 |
| Gigabyte      | Z690 UD DDR4                | [8b93ca6177](https://bsd-hardware.info/?probe=8b93ca6177) | Jan 29, 2024 |
| Gigabyte      | Z690 UD DDR4                | [5d0e727014](https://bsd-hardware.info/?probe=5d0e727014) | Jan 29, 2024 |
| Dell          | 0T7D40 A01                  | [19ab947fb4](https://bsd-hardware.info/?probe=19ab947fb4) | Jan 29, 2024 |
| MSI           | H81M-P33                    | [d411f5eb4b](https://bsd-hardware.info/?probe=d411f5eb4b) | Jan 28, 2024 |
| ASUSTek       | P5Q-E                       | [22436fad84](https://bsd-hardware.info/?probe=22436fad84) | Jan 28, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ec38d3e15f](https://bsd-hardware.info/?probe=ec38d3e15f) | Jan 28, 2024 |
| ASRock        | H310CM-HDV/M.2              | [4f45811a17](https://bsd-hardware.info/?probe=4f45811a17) | Jan 27, 2024 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [713a924dbc](https://bsd-hardware.info/?probe=713a924dbc) | Jan 26, 2024 |
| HC Technol... | HCAR5000-MI                 | [70f47b16e5](https://bsd-hardware.info/?probe=70f47b16e5) | Jan 25, 2024 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [d1da11d4cd](https://bsd-hardware.info/?probe=d1da11d4cd) | Jan 24, 2024 |
| ASRock        | B660M-STX                   | [5ee66bbf7a](https://bsd-hardware.info/?probe=5ee66bbf7a) | Jan 23, 2024 |
| SolidRun      | CEX7 Platform               | [ae1a4bcbae](https://bsd-hardware.info/?probe=ae1a4bcbae) | Jan 23, 2024 |
| Gigabyte      | H87-D3H-CF                  | [60fb8ff088](https://bsd-hardware.info/?probe=60fb8ff088) | Jan 21, 2024 |
| SolidRun      | CEX7 Platform               | [d876c335eb](https://bsd-hardware.info/?probe=d876c335eb) | Jan 21, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [86b81c8374](https://bsd-hardware.info/?probe=86b81c8374) | Jan 19, 2024 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [e2053919c4](https://bsd-hardware.info/?probe=e2053919c4) | Jan 15, 2024 |
| ASUSTek       | PRIME X370-PRO              | [a95eae54ba](https://bsd-hardware.info/?probe=a95eae54ba) | Jan 13, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [f1224c8ebd](https://bsd-hardware.info/?probe=f1224c8ebd) | Jan 13, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [9736c485c9](https://bsd-hardware.info/?probe=9736c485c9) | Jan 12, 2024 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [33704d0025](https://bsd-hardware.info/?probe=33704d0025) | Jan 12, 2024 |
| Dell          | 0MGK50 A02                  | [311083cbe9](https://bsd-hardware.info/?probe=311083cbe9) | Jan 11, 2024 |
| Dell          | 0MGK50 A02                  | [7c2faad499](https://bsd-hardware.info/?probe=7c2faad499) | Jan 11, 2024 |
| ASRock        | B450M-HDV                   | [c15701f2a9](https://bsd-hardware.info/?probe=c15701f2a9) | Jan 10, 2024 |
| ASRock        | B450M-HDV                   | [82d5d6af92](https://bsd-hardware.info/?probe=82d5d6af92) | Jan 10, 2024 |
| HP            | 3641h                       | [90626880cf](https://bsd-hardware.info/?probe=90626880cf) | Jan 09, 2024 |
| Unknown       | Unknown                     | [821748c324](https://bsd-hardware.info/?probe=821748c324) | Jan 08, 2024 |
| MSI           | B450-A PRO                  | [f7e3102e87](https://bsd-hardware.info/?probe=f7e3102e87) | Jan 07, 2024 |
| MSI           | H81M-P33                    | [e2407e0579](https://bsd-hardware.info/?probe=e2407e0579) | Jan 07, 2024 |
| ASUSTek       | P5Q-E                       | [e97b058f7c](https://bsd-hardware.info/?probe=e97b058f7c) | Jan 07, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d429a5298b](https://bsd-hardware.info/?probe=d429a5298b) | Jan 07, 2024 |
| Unknown       | Unknown                     | [6564d3ecfe](https://bsd-hardware.info/?probe=6564d3ecfe) | Jan 07, 2024 |
| Roqos         | Core RC10                   | [3f3aabf270](https://bsd-hardware.info/?probe=3f3aabf270) | Jan 06, 2024 |
| Dell          | 0D24M8 A01                  | [17862ade20](https://bsd-hardware.info/?probe=17862ade20) | Jan 03, 2024 |
| ASUSTek       | CM6870                      | [d7b4e67cdc](https://bsd-hardware.info/?probe=d7b4e67cdc) | Jan 03, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [a29eec0aa5](https://bsd-hardware.info/?probe=a29eec0aa5) | Jan 02, 2024 |
| Alienware     | 07HV66 A00                  | [ea6a3f3020](https://bsd-hardware.info/?probe=ea6a3f3020) | Jan 01, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | [7e2b858339](https://bsd-hardware.info/?probe=7e2b858339) | Dec 31, 2023 |
| ASRock        | B450 Gaming K4              | [84985aa669](https://bsd-hardware.info/?probe=84985aa669) | Dec 31, 2023 |
| MSI           | H81M-P33                    | [82e08820f2](https://bsd-hardware.info/?probe=82e08820f2) | Dec 31, 2023 |
| ASUSTek       | P5Q-E                       | [da3b88ef85](https://bsd-hardware.info/?probe=da3b88ef85) | Dec 31, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [391f4c0e0b](https://bsd-hardware.info/?probe=391f4c0e0b) | Dec 31, 2023 |
| ASUSTek       | CM6870                      | [1889675f37](https://bsd-hardware.info/?probe=1889675f37) | Dec 30, 2023 |
| HP            | 3397                        | [46b6923bcd](https://bsd-hardware.info/?probe=46b6923bcd) | Dec 30, 2023 |
| Unknown       | Unknown                     | [ba78787dff](https://bsd-hardware.info/?probe=ba78787dff) | Dec 29, 2023 |
| ASUSTek       | ROG STRIX B460-G GAMING     | [6b9d713fe0](https://bsd-hardware.info/?probe=6b9d713fe0) | Dec 28, 2023 |
| MSI           | Aspen                       | [ac6dd2b153](https://bsd-hardware.info/?probe=ac6dd2b153) | Dec 27, 2023 |
| Lenovo        | 30D9 SDK0J40700 WIN 3258... | [504fb1678f](https://bsd-hardware.info/?probe=504fb1678f) | Dec 24, 2023 |
| ASUSTek       | P5Q-E                       | [04675127c2](https://bsd-hardware.info/?probe=04675127c2) | Dec 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1ef7136151](https://bsd-hardware.info/?probe=1ef7136151) | Dec 24, 2023 |
| Acer          | Veriton X490G               | [3f4dbee6d1](https://bsd-hardware.info/?probe=3f4dbee6d1) | Dec 24, 2023 |
| Acer          | Veriton X490G               | [1865afdae1](https://bsd-hardware.info/?probe=1865afdae1) | Dec 24, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [06457349dc](https://bsd-hardware.info/?probe=06457349dc) | Dec 22, 2023 |
| Dell          | 0VD5HY A00                  | [03b0e973ca](https://bsd-hardware.info/?probe=03b0e973ca) | Dec 19, 2023 |
| ASUSTek       | P5Q-E                       | [5a4d01667e](https://bsd-hardware.info/?probe=5a4d01667e) | Dec 17, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ea79e98108](https://bsd-hardware.info/?probe=ea79e98108) | Dec 17, 2023 |
| MSI           | A520M-A PRO                 | [11e5e87b70](https://bsd-hardware.info/?probe=11e5e87b70) | Dec 16, 2023 |
| ASUSTek       | PRO B460M-C                 | [7a32a123f6](https://bsd-hardware.info/?probe=7a32a123f6) | Dec 15, 2023 |
| Gigabyte      | H61M-S2PV                   | [88d2ae1175](https://bsd-hardware.info/?probe=88d2ae1175) | Dec 14, 2023 |
| Dell          | 0NK5PH A00                  | [60451d4e43](https://bsd-hardware.info/?probe=60451d4e43) | Dec 14, 2023 |
| AZW           | EQ                          | [d83e11a7dc](https://bsd-hardware.info/?probe=d83e11a7dc) | Dec 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [bc50d301fa](https://bsd-hardware.info/?probe=bc50d301fa) | Dec 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [dced442907](https://bsd-hardware.info/?probe=dced442907) | Dec 13, 2023 |
| Unknown       | Unknown                     | [123088175c](https://bsd-hardware.info/?probe=123088175c) | Dec 11, 2023 |
| EVGA          | X570 DARK.0                 | [1c84a8169b](https://bsd-hardware.info/?probe=1c84a8169b) | Dec 11, 2023 |
| Dell          | 0NC2VH A01                  | [6e876a349f](https://bsd-hardware.info/?probe=6e876a349f) | Dec 11, 2023 |
| Dell          | 0NW6H5 A00                  | [2febbeffc2](https://bsd-hardware.info/?probe=2febbeffc2) | Dec 11, 2023 |
| AZW           | EQ                          | [0280c1cdb9](https://bsd-hardware.info/?probe=0280c1cdb9) | Dec 10, 2023 |
| ASUSTek       | CM6870                      | [881ad2eacf](https://bsd-hardware.info/?probe=881ad2eacf) | Dec 10, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [47480f848d](https://bsd-hardware.info/?probe=47480f848d) | Dec 10, 2023 |
| MSI           | H81M-P33                    | [2b1599aacd](https://bsd-hardware.info/?probe=2b1599aacd) | Dec 10, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [89f0463ec6](https://bsd-hardware.info/?probe=89f0463ec6) | Dec 10, 2023 |
| ASUSTek       | CM6870                      | [78399ba39e](https://bsd-hardware.info/?probe=78399ba39e) | Dec 09, 2023 |
| Gigabyte      | B650 AORUS ELITE AX V2      | [7a6cdb3f06](https://bsd-hardware.info/?probe=7a6cdb3f06) | Dec 09, 2023 |
| ASUSTek       | PRIME X399-A                | [d62ad0d622](https://bsd-hardware.info/?probe=d62ad0d622) | Dec 09, 2023 |
| ASUSTek       | Z10PE-D16 WS                | [7fd4743b86](https://bsd-hardware.info/?probe=7fd4743b86) | Dec 07, 2023 |
| Dell          | 0NW6H5 A00                  | [41e61ade9a](https://bsd-hardware.info/?probe=41e61ade9a) | Dec 06, 2023 |
| ECS           | MCP61M-M3                   | [6d6c04c278](https://bsd-hardware.info/?probe=6d6c04c278) | Dec 05, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [8c023b9c33](https://bsd-hardware.info/?probe=8c023b9c33) | Dec 05, 2023 |
| MSI           | G31TM-P21                   | [4f5b576aff](https://bsd-hardware.info/?probe=4f5b576aff) | Dec 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [a9b3beae66](https://bsd-hardware.info/?probe=a9b3beae66) | Dec 02, 2023 |
| ASRock        | Z590 Pro4                   | [0457bab107](https://bsd-hardware.info/?probe=0457bab107) | Dec 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [f1cb9a41ba](https://bsd-hardware.info/?probe=f1cb9a41ba) | Nov 30, 2023 |
| MSI           | B450M MORTAR                | [4017ce5221](https://bsd-hardware.info/?probe=4017ce5221) | Nov 29, 2023 |
| CNCTION-IA... | Unknown                     | [1b4871792b](https://bsd-hardware.info/?probe=1b4871792b) | Nov 28, 2023 |
| ASUSTek       | PRIME A520M-E               | [8d7c03be2f](https://bsd-hardware.info/?probe=8d7c03be2f) | Nov 28, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | [806a29d40a](https://bsd-hardware.info/?probe=806a29d40a) | Nov 28, 2023 |
| ASRock        | B450 Steel Legend           | [c9f6264329](https://bsd-hardware.info/?probe=c9f6264329) | Nov 27, 2023 |
| ASRock        | B450 Steel Legend           | [1e9f19c4ae](https://bsd-hardware.info/?probe=1e9f19c4ae) | Nov 27, 2023 |
| Lenovo        | 1036 NO DPK                 | [3b18ff26c0](https://bsd-hardware.info/?probe=3b18ff26c0) | Nov 27, 2023 |
| ASUSTek       | PRIME A320M-K               | [42bddda351](https://bsd-hardware.info/?probe=42bddda351) | Nov 26, 2023 |
| MSI           | H81M-P33                    | [b653e75063](https://bsd-hardware.info/?probe=b653e75063) | Nov 26, 2023 |
| ASUSTek       | P5Q-E                       | [1454187842](https://bsd-hardware.info/?probe=1454187842) | Nov 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [28f6ec2a7b](https://bsd-hardware.info/?probe=28f6ec2a7b) | Nov 26, 2023 |
| HP            | ProLiant ML350p Gen8        | [24f4b0ec7e](https://bsd-hardware.info/?probe=24f4b0ec7e) | Nov 24, 2023 |
| Silicom       | 80300-0214-G16 R310         | [34382c8f4b](https://bsd-hardware.info/?probe=34382c8f4b) | Nov 24, 2023 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [4c80855e88](https://bsd-hardware.info/?probe=4c80855e88) | Nov 22, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [a37a33268d](https://bsd-hardware.info/?probe=a37a33268d) | Nov 21, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [fb283e956a](https://bsd-hardware.info/?probe=fb283e956a) | Nov 21, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [4b6284d041](https://bsd-hardware.info/?probe=4b6284d041) | Nov 20, 2023 |
| PICO PC       | MNHO-113                    | [c9a12372b4](https://bsd-hardware.info/?probe=c9a12372b4) | Nov 20, 2023 |
| MSI           | H81M-P33                    | [6406980bbf](https://bsd-hardware.info/?probe=6406980bbf) | Nov 19, 2023 |
| ASUSTek       | P5Q-E                       | [e7ccb4156e](https://bsd-hardware.info/?probe=e7ccb4156e) | Nov 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a570c7994c](https://bsd-hardware.info/?probe=a570c7994c) | Nov 19, 2023 |
| MSI           | B560-A PRO                  | [cf9b5a14ce](https://bsd-hardware.info/?probe=cf9b5a14ce) | Nov 19, 2023 |
| ASUSTek       | P7P55D                      | [9eab94b4f7](https://bsd-hardware.info/?probe=9eab94b4f7) | Nov 18, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [cfbda53125](https://bsd-hardware.info/?probe=cfbda53125) | Nov 18, 2023 |
| HP            | 18E7                        | [3cbe1117fa](https://bsd-hardware.info/?probe=3cbe1117fa) | Nov 14, 2023 |
| ASUSTek       | P7P55D                      | [2487233a5d](https://bsd-hardware.info/?probe=2487233a5d) | Nov 13, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [ee4c8ddddc](https://bsd-hardware.info/?probe=ee4c8ddddc) | Nov 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [771c13f8ea](https://bsd-hardware.info/?probe=771c13f8ea) | Nov 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [35ae423f7a](https://bsd-hardware.info/?probe=35ae423f7a) | Nov 13, 2023 |
| MSI           | H81M-P33                    | [a062354358](https://bsd-hardware.info/?probe=a062354358) | Nov 12, 2023 |
| ASUSTek       | P5Q-E                       | [0869172a54](https://bsd-hardware.info/?probe=0869172a54) | Nov 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b1e348523f](https://bsd-hardware.info/?probe=b1e348523f) | Nov 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | [f32f8bdf95](https://bsd-hardware.info/?probe=f32f8bdf95) | Nov 12, 2023 |
| ASUSTek       | Z97-A                       | [3ce8e78453](https://bsd-hardware.info/?probe=3ce8e78453) | Nov 11, 2023 |
| Unknown       | Unknown                     | [c535fae89f](https://bsd-hardware.info/?probe=c535fae89f) | Nov 10, 2023 |
| ASRock        | B460M Steel Legend          | [13bdfc626b](https://bsd-hardware.info/?probe=13bdfc626b) | Nov 09, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [3c3b2abb3d](https://bsd-hardware.info/?probe=3c3b2abb3d) | Nov 09, 2023 |
| ASRockRack    | X470D4U2-2T                 | [b7b9df03f3](https://bsd-hardware.info/?probe=b7b9df03f3) | Nov 09, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [6588258570](https://bsd-hardware.info/?probe=6588258570) | Nov 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e8c7d22b1f](https://bsd-hardware.info/?probe=e8c7d22b1f) | Nov 05, 2023 |
| MSI           | H81M-P33                    | [d44c30f985](https://bsd-hardware.info/?probe=d44c30f985) | Nov 05, 2023 |
| ASUSTek       | P5Q-E                       | [dac3ca2eca](https://bsd-hardware.info/?probe=dac3ca2eca) | Nov 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [e744712416](https://bsd-hardware.info/?probe=e744712416) | Nov 05, 2023 |
| ASUSTek       | Z97-A                       | [a8aad4a386](https://bsd-hardware.info/?probe=a8aad4a386) | Nov 04, 2023 |
| Dell          | 0Y2V0C A03                  | [5c7de92bb3](https://bsd-hardware.info/?probe=5c7de92bb3) | Nov 03, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | [2fab5b5adf](https://bsd-hardware.info/?probe=2fab5b5adf) | Nov 01, 2023 |
| ASRock        | Z590 Pro4                   | [03fa12a885](https://bsd-hardware.info/?probe=03fa12a885) | Nov 01, 2023 |
| MSI           | 970 GAMING                  | [f93d5865b8](https://bsd-hardware.info/?probe=f93d5865b8) | Nov 01, 2023 |
| Unknown       | Unknown                     | [1a63df656e](https://bsd-hardware.info/?probe=1a63df656e) | Oct 31, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [87e3260963](https://bsd-hardware.info/?probe=87e3260963) | Oct 31, 2023 |
| ASUSTek       | PRIME A520M-K               | [c60aeb219e](https://bsd-hardware.info/?probe=c60aeb219e) | Oct 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [c163891517](https://bsd-hardware.info/?probe=c163891517) | Oct 31, 2023 |
| Intel         | DCP847SKE                   | [ba44d23972](https://bsd-hardware.info/?probe=ba44d23972) | Oct 29, 2023 |
| Dell          | 02YYK5 A01                  | [1b42e4a912](https://bsd-hardware.info/?probe=1b42e4a912) | Oct 26, 2023 |
| Unknown       | Unknown                     | [6b3f2cf24c](https://bsd-hardware.info/?probe=6b3f2cf24c) | Oct 25, 2023 |
| Unknown       | Unknown                     | [8e245ccb85](https://bsd-hardware.info/?probe=8e245ccb85) | Oct 25, 2023 |
| Unknown       | Unknown                     | [db96ffb93a](https://bsd-hardware.info/?probe=db96ffb93a) | Oct 25, 2023 |
| Unknown       | Unknown                     | [06f91445cb](https://bsd-hardware.info/?probe=06f91445cb) | Oct 24, 2023 |
| Shuttle       | FZ270                       | [1aa4ad0971](https://bsd-hardware.info/?probe=1aa4ad0971) | Oct 23, 2023 |
| Dell          | 02YYK5 A01                  | [ab44e043d2](https://bsd-hardware.info/?probe=ab44e043d2) | Oct 23, 2023 |
| MSI           | H81M-P33                    | [dd9ff802a9](https://bsd-hardware.info/?probe=dd9ff802a9) | Oct 22, 2023 |
| ASUSTek       | P5Q-E                       | [1b94fd9385](https://bsd-hardware.info/?probe=1b94fd9385) | Oct 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [cc7fb797f5](https://bsd-hardware.info/?probe=cc7fb797f5) | Oct 22, 2023 |
| Unknown       | Unknown                     | [629eefe0c2](https://bsd-hardware.info/?probe=629eefe0c2) | Oct 21, 2023 |
| ASUSTek       | PRIME H470M-PLUS            | [88cdd6135f](https://bsd-hardware.info/?probe=88cdd6135f) | Oct 20, 2023 |
| Dell          | 02YYK5 A01                  | [a8727c3ee3](https://bsd-hardware.info/?probe=a8727c3ee3) | Oct 19, 2023 |
| MSI           | PRO H610M-B DDR4            | [1cc822b8c1](https://bsd-hardware.info/?probe=1cc822b8c1) | Oct 19, 2023 |
| Dell          | 0NW6H5 A00                  | [606ed441ae](https://bsd-hardware.info/?probe=606ed441ae) | Oct 19, 2023 |
| ASUSTek       | X99-A/USB                   | [0f914c6351](https://bsd-hardware.info/?probe=0f914c6351) | Oct 17, 2023 |
| MSI           | H81M-P33                    | [6902d492db](https://bsd-hardware.info/?probe=6902d492db) | Oct 15, 2023 |
| ASUSTek       | P5Q-E                       | [094b766a05](https://bsd-hardware.info/?probe=094b766a05) | Oct 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b502116394](https://bsd-hardware.info/?probe=b502116394) | Oct 15, 2023 |
| ASUSTek       | PRIME X370-PRO              | [697f24cf01](https://bsd-hardware.info/?probe=697f24cf01) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [d14ff47394](https://bsd-hardware.info/?probe=d14ff47394) | Oct 13, 2023 |
| Unknown       | Unknown                     | [0fd1a7196f](https://bsd-hardware.info/?probe=0fd1a7196f) | Oct 13, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [a7307b8de1](https://bsd-hardware.info/?probe=a7307b8de1) | Oct 12, 2023 |
| ANGXUN        | X79-VG2 V1.3                | [c823cbad48](https://bsd-hardware.info/?probe=c823cbad48) | Oct 10, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [f55c557bcf](https://bsd-hardware.info/?probe=f55c557bcf) | Oct 09, 2023 |
| EVGA          | X299 MICRO                  | [2907f2166d](https://bsd-hardware.info/?probe=2907f2166d) | Oct 09, 2023 |
| MSI           | H81M-P33                    | [a9729ebc38](https://bsd-hardware.info/?probe=a9729ebc38) | Oct 08, 2023 |
| ASUSTek       | P5Q-E                       | [06a76899d6](https://bsd-hardware.info/?probe=06a76899d6) | Oct 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [cacbb83f98](https://bsd-hardware.info/?probe=cacbb83f98) | Oct 08, 2023 |
| MSI           | Aspen                       | [7bb665508f](https://bsd-hardware.info/?probe=7bb665508f) | Oct 07, 2023 |
| Unknown       | Unknown                     | [1aa25f04a8](https://bsd-hardware.info/?probe=1aa25f04a8) | Oct 07, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [b3580a1e53](https://bsd-hardware.info/?probe=b3580a1e53) | Oct 07, 2023 |
| Unknown       | Unknown                     | [9d236eb8bb](https://bsd-hardware.info/?probe=9d236eb8bb) | Oct 06, 2023 |
| Unknown       | Unknown                     | [9ad768a37a](https://bsd-hardware.info/?probe=9ad768a37a) | Oct 04, 2023 |
| ASUSTek       | Pro WS W680-ACE IPMI        | [6a98aea3f9](https://bsd-hardware.info/?probe=6a98aea3f9) | Oct 03, 2023 |
| MSI           | H81M-P33                    | [da12fe3c05](https://bsd-hardware.info/?probe=da12fe3c05) | Oct 01, 2023 |
| ASUSTek       | P5Q-E                       | [6975204e47](https://bsd-hardware.info/?probe=6975204e47) | Oct 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [c6903de57a](https://bsd-hardware.info/?probe=c6903de57a) | Sep 30, 2023 |
| Gigabyte      | B450M S2H V2                | [31da8655d1](https://bsd-hardware.info/?probe=31da8655d1) | Sep 28, 2023 |
| Biostar       | A55MLC2                     | [fac0f247d0](https://bsd-hardware.info/?probe=fac0f247d0) | Sep 28, 2023 |
| Dell          | 07T4MC A09                  | [bde8cc45df](https://bsd-hardware.info/?probe=bde8cc45df) | Sep 26, 2023 |
| Dell          | 07T4MC A09                  | [0ce8f84155](https://bsd-hardware.info/?probe=0ce8f84155) | Sep 26, 2023 |
| Unknown       | Unknown                     | [1ba135fef1](https://bsd-hardware.info/?probe=1ba135fef1) | Sep 24, 2023 |
| Unknown       | Unknown                     | [9c8516c8a8](https://bsd-hardware.info/?probe=9c8516c8a8) | Sep 24, 2023 |
| MSI           | H81M-P33                    | [971f3fdba1](https://bsd-hardware.info/?probe=971f3fdba1) | Sep 24, 2023 |
| ASUSTek       | P5Q-E                       | [6538212bd6](https://bsd-hardware.info/?probe=6538212bd6) | Sep 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [f7aee1db53](https://bsd-hardware.info/?probe=f7aee1db53) | Sep 24, 2023 |
| AZW           | SEi V1.0                    | [1d0307b36d](https://bsd-hardware.info/?probe=1d0307b36d) | Sep 23, 2023 |
| ASUSTek       | PRIME B550M-A (WI-FI)       | [ab77dcfd74](https://bsd-hardware.info/?probe=ab77dcfd74) | Sep 15, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [6fc18e3db7](https://bsd-hardware.info/?probe=6fc18e3db7) | Sep 15, 2023 |
| ASUSTek       | PRIME X370-PRO              | [5dee3a945f](https://bsd-hardware.info/?probe=5dee3a945f) | Sep 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [9fee6e83fc](https://bsd-hardware.info/?probe=9fee6e83fc) | Sep 13, 2023 |
| HP            | 212B                        | [3370718b29](https://bsd-hardware.info/?probe=3370718b29) | Sep 13, 2023 |
| ASUSTek       | PRIME B550M-A (WI-FI)       | [78bc36f5a9](https://bsd-hardware.info/?probe=78bc36f5a9) | Sep 11, 2023 |
| Gigabyte      | GA-870A-UD3                 | [095b8aa8fb](https://bsd-hardware.info/?probe=095b8aa8fb) | Sep 11, 2023 |
| MSI           | H81M-P33                    | [57a847859f](https://bsd-hardware.info/?probe=57a847859f) | Sep 10, 2023 |
| ASUSTek       | P5Q-E                       | [b7e0d87f47](https://bsd-hardware.info/?probe=b7e0d87f47) | Sep 10, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c2378b3e83](https://bsd-hardware.info/?probe=c2378b3e83) | Sep 10, 2023 |
| MSI           | PRESTIGE X570 CREATION      | [7947ecdca3](https://bsd-hardware.info/?probe=7947ecdca3) | Sep 08, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [24e745026c](https://bsd-hardware.info/?probe=24e745026c) | Sep 08, 2023 |
| Unknown       | Unknown                     | [29578638c1](https://bsd-hardware.info/?probe=29578638c1) | Sep 08, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [0b7d85b124](https://bsd-hardware.info/?probe=0b7d85b124) | Sep 06, 2023 |
| Unknown       | Unknown                     | [50f509c032](https://bsd-hardware.info/?probe=50f509c032) | Sep 05, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [1bde5a65b6](https://bsd-hardware.info/?probe=1bde5a65b6) | Sep 03, 2023 |
| MSI           | H81M-P33                    | [b47290007a](https://bsd-hardware.info/?probe=b47290007a) | Sep 03, 2023 |
| ASUSTek       | P5Q-E                       | [ef4604a40f](https://bsd-hardware.info/?probe=ef4604a40f) | Sep 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [8d37c44440](https://bsd-hardware.info/?probe=8d37c44440) | Sep 03, 2023 |
| AAEON         | FWS-2363 V1.0               | [098bc5466b](https://bsd-hardware.info/?probe=098bc5466b) | Sep 03, 2023 |
| Shuttle       | DS20U                       | [d034a8e5b8](https://bsd-hardware.info/?probe=d034a8e5b8) | Sep 02, 2023 |
| Intel         | HM570                       | [de018603ae](https://bsd-hardware.info/?probe=de018603ae) | Sep 02, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [82ac08abc0](https://bsd-hardware.info/?probe=82ac08abc0) | Aug 31, 2023 |
| HP            | 802F                        | [1f64f7e11f](https://bsd-hardware.info/?probe=1f64f7e11f) | Aug 30, 2023 |
| SolidRun      | CEX7 Platform               | [b83ebfd33b](https://bsd-hardware.info/?probe=b83ebfd33b) | Aug 29, 2023 |
| Nvidia        | MCP79                       | [0897b3a117](https://bsd-hardware.info/?probe=0897b3a117) | Aug 29, 2023 |
| Supermicro    | X9DRD-iF                    | [be36f2fe2b](https://bsd-hardware.info/?probe=be36f2fe2b) | Aug 28, 2023 |
| MSI           | PRESTIGE X570 CREATION      | [df915d5ab9](https://bsd-hardware.info/?probe=df915d5ab9) | Aug 27, 2023 |
| MSI           | H81M-P33                    | [2e9a066a01](https://bsd-hardware.info/?probe=2e9a066a01) | Aug 27, 2023 |
| ASUSTek       | P5Q-E                       | [9898ae1ead](https://bsd-hardware.info/?probe=9898ae1ead) | Aug 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [0bb56ff672](https://bsd-hardware.info/?probe=0bb56ff672) | Aug 27, 2023 |
| SolidRun      | CEX7 Platform               | [4d51e18ce4](https://bsd-hardware.info/?probe=4d51e18ce4) | Aug 25, 2023 |
| MSI           | G31M3-L V2                  | [7335b3dea2](https://bsd-hardware.info/?probe=7335b3dea2) | Aug 22, 2023 |
| MSI           | MEG X570 ACE                | [0d69491bdd](https://bsd-hardware.info/?probe=0d69491bdd) | Aug 21, 2023 |
| MSI           | MEG X570 ACE                | [913cc77381](https://bsd-hardware.info/?probe=913cc77381) | Aug 21, 2023 |
| Lenovo        | ThinkCentre M90p 3853RN9    | [818c1b5f31](https://bsd-hardware.info/?probe=818c1b5f31) | Aug 20, 2023 |
| Shuttle       | DS20U                       | [5c511e0613](https://bsd-hardware.info/?probe=5c511e0613) | Aug 20, 2023 |
| Lenovo        | 30C7 SDK0J40700 WIN 3258... | [9e92903663](https://bsd-hardware.info/?probe=9e92903663) | Aug 18, 2023 |
| MSI           | MS-7721                     | [678c81c8c1](https://bsd-hardware.info/?probe=678c81c8c1) | Aug 18, 2023 |
| Supermicro    | M12SWA-TF                   | [2e38f0b91a](https://bsd-hardware.info/?probe=2e38f0b91a) | Aug 16, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [fc152ce8d4](https://bsd-hardware.info/?probe=fc152ce8d4) | Aug 16, 2023 |
| MSI           | A520M-A PRO                 | [cc946b2a89](https://bsd-hardware.info/?probe=cc946b2a89) | Aug 15, 2023 |
| ASUSTek       | PRIME X370-PRO              | [2529ce32a7](https://bsd-hardware.info/?probe=2529ce32a7) | Aug 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [80fbf43a6c](https://bsd-hardware.info/?probe=80fbf43a6c) | Aug 13, 2023 |
| ASUSTek       | P5Q-E                       | [fbb75a1ace](https://bsd-hardware.info/?probe=fbb75a1ace) | Aug 13, 2023 |
| MSI           | H81M-P33                    | [c7b0e4ca6c](https://bsd-hardware.info/?probe=c7b0e4ca6c) | Aug 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [245d908d1a](https://bsd-hardware.info/?probe=245d908d1a) | Aug 13, 2023 |
| PC Engines    | APU2                        | [2e9106fc92](https://bsd-hardware.info/?probe=2e9106fc92) | Aug 11, 2023 |
| Gigabyte      | AX370M-DS3H-CF              | [7b00ddd0a1](https://bsd-hardware.info/?probe=7b00ddd0a1) | Aug 11, 2023 |
| PC Engines    | apu1                        | [0b3594d9a3](https://bsd-hardware.info/?probe=0b3594d9a3) | Aug 11, 2023 |
| MSI           | PRESTIGE X570 CREATION      | [65092dde79](https://bsd-hardware.info/?probe=65092dde79) | Aug 09, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [2f6574d368](https://bsd-hardware.info/?probe=2f6574d368) | Aug 08, 2023 |
| MSI           | H81M-P33                    | [1f7493ada9](https://bsd-hardware.info/?probe=1f7493ada9) | Aug 06, 2023 |
| ASUSTek       | P5Q-E                       | [46b9ec2e56](https://bsd-hardware.info/?probe=46b9ec2e56) | Aug 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [5bd8b552e6](https://bsd-hardware.info/?probe=5bd8b552e6) | Aug 06, 2023 |
| ASRock        | B550 PG Velocita            | [3ff5fcfbc0](https://bsd-hardware.info/?probe=3ff5fcfbc0) | Aug 02, 2023 |
| HP            | 8298                        | [961bfad69a](https://bsd-hardware.info/?probe=961bfad69a) | Aug 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [be9b9caa66](https://bsd-hardware.info/?probe=be9b9caa66) | Jul 31, 2023 |
| ASUSTek       | PRIME A320I-K               | [09f173d4b6](https://bsd-hardware.info/?probe=09f173d4b6) | Jul 30, 2023 |
| MSI           | H81M-P33                    | [9c27c27611](https://bsd-hardware.info/?probe=9c27c27611) | Jul 30, 2023 |
| ASUSTek       | P5Q-E                       | [a2dbe84ed3](https://bsd-hardware.info/?probe=a2dbe84ed3) | Jul 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [591f8397a9](https://bsd-hardware.info/?probe=591f8397a9) | Jul 30, 2023 |
| ASUSTek       | P8P67                       | [0e10359af8](https://bsd-hardware.info/?probe=0e10359af8) | Jul 29, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [64137e0eec](https://bsd-hardware.info/?probe=64137e0eec) | Jul 29, 2023 |
| Dell          | 0PTTT9 A01                  | [a3624fdcfc](https://bsd-hardware.info/?probe=a3624fdcfc) | Jul 24, 2023 |
| MSI           | H81M-P33                    | [14b1509851](https://bsd-hardware.info/?probe=14b1509851) | Jul 23, 2023 |
| ASUSTek       | P5Q-E                       | [7b725a65c4](https://bsd-hardware.info/?probe=7b725a65c4) | Jul 23, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [877ddd1995](https://bsd-hardware.info/?probe=877ddd1995) | Jul 23, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [ce0f05e871](https://bsd-hardware.info/?probe=ce0f05e871) | Jul 18, 2023 |
| Unknown       | Unknown                     | [4a82a6a375](https://bsd-hardware.info/?probe=4a82a6a375) | Jul 17, 2023 |
| Intel         | HM570                       | [a9abbf1e12](https://bsd-hardware.info/?probe=a9abbf1e12) | Jul 15, 2023 |
| Unknown       | Unknown                     | [a322b1ee22](https://bsd-hardware.info/?probe=a322b1ee22) | Jul 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [88fae8d98c](https://bsd-hardware.info/?probe=88fae8d98c) | Jul 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [1516e2960a](https://bsd-hardware.info/?probe=1516e2960a) | Jul 13, 2023 |
| Radxa         | rock-pi-n10a                | [a9767501e2](https://bsd-hardware.info/?probe=a9767501e2) | Jul 12, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [08b0409497](https://bsd-hardware.info/?probe=08b0409497) | Jul 12, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [d0f09cc8c4](https://bsd-hardware.info/?probe=d0f09cc8c4) | Jul 11, 2023 |
| ASRock        | Z690 PG Riptide             | [813e46e924](https://bsd-hardware.info/?probe=813e46e924) | Jul 10, 2023 |
| MSI           | H81M-P33                    | [f0de15f4e2](https://bsd-hardware.info/?probe=f0de15f4e2) | Jul 09, 2023 |
| ASUSTek       | P5Q-E                       | [3bb3ebc39d](https://bsd-hardware.info/?probe=3bb3ebc39d) | Jul 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [87bb7727a2](https://bsd-hardware.info/?probe=87bb7727a2) | Jul 09, 2023 |
| HP            | 3397                        | [3d32ba4cd9](https://bsd-hardware.info/?probe=3d32ba4cd9) | Jul 08, 2023 |
| Dell          | 0PTTT9 A01                  | [0f55bad1af](https://bsd-hardware.info/?probe=0f55bad1af) | Jul 08, 2023 |
| MSI           | MAG B560 TORPEDO            | [e0d3f841c7](https://bsd-hardware.info/?probe=e0d3f841c7) | Jul 07, 2023 |
| MSI           | H510I PRO WIFI              | [743d249ba5](https://bsd-hardware.info/?probe=743d249ba5) | Jul 07, 2023 |
| Intel         | DQ67SW AAG12527-310         | [e36e748937](https://bsd-hardware.info/?probe=e36e748937) | Jul 06, 2023 |
| ASRock        | Z690 PG Riptide             | [364cf5800b](https://bsd-hardware.info/?probe=364cf5800b) | Jul 06, 2023 |
| HP            | 82F2 A01                    | [a77d73b637](https://bsd-hardware.info/?probe=a77d73b637) | Jul 04, 2023 |
| ASUSTek       | PRIME H510M-A               | [fd5fa70fb7](https://bsd-hardware.info/?probe=fd5fa70fb7) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | [e569621be2](https://bsd-hardware.info/?probe=e569621be2) | Jul 03, 2023 |
| Gigabyte      | H270N-WIFI-CF               | [553cd9ecae](https://bsd-hardware.info/?probe=553cd9ecae) | Jul 03, 2023 |
| ASRock        | J3455B-ITX                  | [3c80c960d3](https://bsd-hardware.info/?probe=3c80c960d3) | Jul 03, 2023 |
| ASRock        | J3455B-ITX                  | [051ddf6f8d](https://bsd-hardware.info/?probe=051ddf6f8d) | Jul 03, 2023 |
| Gigabyte      | H270N-WIFI-CF               | [dfdb0bd650](https://bsd-hardware.info/?probe=dfdb0bd650) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | [e68bb73773](https://bsd-hardware.info/?probe=e68bb73773) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | [3b4a248520](https://bsd-hardware.info/?probe=3b4a248520) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | [0a2a221aae](https://bsd-hardware.info/?probe=0a2a221aae) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | [7e5ee8de12](https://bsd-hardware.info/?probe=7e5ee8de12) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | [3b50a90ebc](https://bsd-hardware.info/?probe=3b50a90ebc) | Jul 03, 2023 |
| Gigabyte      | M85M-US2H                   | [e0a38ef6ad](https://bsd-hardware.info/?probe=e0a38ef6ad) | Jul 03, 2023 |
| MSI           | H81M-P33                    | [71edaf952e](https://bsd-hardware.info/?probe=71edaf952e) | Jul 02, 2023 |
| ASUSTek       | P5Q-E                       | [98254451c1](https://bsd-hardware.info/?probe=98254451c1) | Jul 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [977d44457e](https://bsd-hardware.info/?probe=977d44457e) | Jul 02, 2023 |
| Dell          | 03KWTV A00                  | [d8f6429e70](https://bsd-hardware.info/?probe=d8f6429e70) | Jul 02, 2023 |
| Gigabyte      | H77M-D3H                    | [9f6d45e43e](https://bsd-hardware.info/?probe=9f6d45e43e) | Jul 02, 2023 |
| Gigabyte      | H77M-D3H                    | [3eb03fa8a7](https://bsd-hardware.info/?probe=3eb03fa8a7) | Jul 02, 2023 |
| Gigabyte      | B360M D2V                   | [bf5f6fd6dd](https://bsd-hardware.info/?probe=bf5f6fd6dd) | Jun 30, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [6479d60da2](https://bsd-hardware.info/?probe=6479d60da2) | Jun 30, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [b6cfa09740](https://bsd-hardware.info/?probe=b6cfa09740) | Jun 30, 2023 |
| Unknown       | Unknown                     | [c07f4ffa1e](https://bsd-hardware.info/?probe=c07f4ffa1e) | Jun 29, 2023 |
| MSI           | H81M-P33                    | [80bd24461a](https://bsd-hardware.info/?probe=80bd24461a) | Jun 25, 2023 |
| ASUSTek       | P5Q-E                       | [e368d55893](https://bsd-hardware.info/?probe=e368d55893) | Jun 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [483865aca5](https://bsd-hardware.info/?probe=483865aca5) | Jun 25, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [6172c8b66f](https://bsd-hardware.info/?probe=6172c8b66f) | Jun 22, 2023 |
| ASUSTek       | P5K PRO                     | [f0b283fdaf](https://bsd-hardware.info/?probe=f0b283fdaf) | Jun 19, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [705c750691](https://bsd-hardware.info/?probe=705c750691) | Jun 17, 2023 |
| Lenovo        | ThinkCentre A70 7099A5P     | [4e827b2cbf](https://bsd-hardware.info/?probe=4e827b2cbf) | Jun 16, 2023 |
| Lenovo        | ThinkCentre A70 7099A5P     | [3d71827388](https://bsd-hardware.info/?probe=3d71827388) | Jun 16, 2023 |
| Dell          | 053CWD A00                  | [7a5418ac7e](https://bsd-hardware.info/?probe=7a5418ac7e) | Jun 16, 2023 |
| Unknown       | Unknown                     | [6b4f214b72](https://bsd-hardware.info/?probe=6b4f214b72) | Jun 15, 2023 |
| Unknown       | Unknown                     | [615e7cbf52](https://bsd-hardware.info/?probe=615e7cbf52) | Jun 15, 2023 |
| Unknown       | Unknown                     | [8357f0f72e](https://bsd-hardware.info/?probe=8357f0f72e) | Jun 15, 2023 |
| Unknown       | Unknown                     | [f41e1f2b83](https://bsd-hardware.info/?probe=f41e1f2b83) | Jun 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | [6e8e70ddc2](https://bsd-hardware.info/?probe=6e8e70ddc2) | Jun 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [c19a29f083](https://bsd-hardware.info/?probe=c19a29f083) | Jun 13, 2023 |
| MSI           | H81M-P33                    | [3d9a05635f](https://bsd-hardware.info/?probe=3d9a05635f) | Jun 11, 2023 |
| ASUSTek       | P5Q-E                       | [b8f3eeed4b](https://bsd-hardware.info/?probe=b8f3eeed4b) | Jun 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [9c888141fb](https://bsd-hardware.info/?probe=9c888141fb) | Jun 11, 2023 |
| MSI           | PRESTIGE X570 CREATION      | [7e0151a93f](https://bsd-hardware.info/?probe=7e0151a93f) | Jun 10, 2023 |
| ASRock        | Z590 Pro4                   | [d04a63aa31](https://bsd-hardware.info/?probe=d04a63aa31) | Jun 06, 2023 |
| HP            | 212B                        | [4db61072c4](https://bsd-hardware.info/?probe=4db61072c4) | Jun 05, 2023 |
| MSI           | H81M-P33                    | [88598bfbf5](https://bsd-hardware.info/?probe=88598bfbf5) | Jun 04, 2023 |
| ASUSTek       | P5Q-E                       | [fac0ed387e](https://bsd-hardware.info/?probe=fac0ed387e) | Jun 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [3c76deca15](https://bsd-hardware.info/?probe=3c76deca15) | Jun 04, 2023 |
| ASRock        | Z590 Pro4                   | [314d462dcd](https://bsd-hardware.info/?probe=314d462dcd) | Jun 04, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [d4247f35c8](https://bsd-hardware.info/?probe=d4247f35c8) | Jun 02, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [2445651c96](https://bsd-hardware.info/?probe=2445651c96) | May 31, 2023 |
| ASRock        | Z590 Pro4                   | [a9b9a2e045](https://bsd-hardware.info/?probe=a9b9a2e045) | May 29, 2023 |
| ASRock        | Z590 Pro4                   | [e63f1f4874](https://bsd-hardware.info/?probe=e63f1f4874) | May 29, 2023 |
| ASRock        | Z590 Pro4                   | [382fe30ec1](https://bsd-hardware.info/?probe=382fe30ec1) | May 28, 2023 |
| Gigabyte      | H170-D3HP-CF                | [d5fdf2ff2c](https://bsd-hardware.info/?probe=d5fdf2ff2c) | May 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [28c84f71fd](https://bsd-hardware.info/?probe=28c84f71fd) | May 28, 2023 |
| ASUSTek       | P5Q-E                       | [cf8b2af78b](https://bsd-hardware.info/?probe=cf8b2af78b) | May 28, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [8514299fe4](https://bsd-hardware.info/?probe=8514299fe4) | May 26, 2023 |
| ASRockRack    | GENOAD8UD-2T/X550           | [c6b62c6b5b](https://bsd-hardware.info/?probe=c6b62c6b5b) | May 26, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [81775d5ca1](https://bsd-hardware.info/?probe=81775d5ca1) | May 26, 2023 |
| ASUSTek       | PRIME A520M-A II            | [eba55377e0](https://bsd-hardware.info/?probe=eba55377e0) | May 22, 2023 |
| MSI           | H81M-P33                    | [cadb0f588f](https://bsd-hardware.info/?probe=cadb0f588f) | May 21, 2023 |
| ASUSTek       | P5Q-E                       | [4a55c4a669](https://bsd-hardware.info/?probe=4a55c4a669) | May 21, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [f2fb56c7dc](https://bsd-hardware.info/?probe=f2fb56c7dc) | May 21, 2023 |
| HP            | 158B                        | [1ef3762103](https://bsd-hardware.info/?probe=1ef3762103) | May 20, 2023 |
| HP            | 158B                        | [a9c63041a6](https://bsd-hardware.info/?probe=a9c63041a6) | May 20, 2023 |
| ASUSTek       | PRO B460M-C                 | [9350bb37db](https://bsd-hardware.info/?probe=9350bb37db) | May 18, 2023 |
| Gigabyte      | H170-D3HP-CF                | [830100249f](https://bsd-hardware.info/?probe=830100249f) | May 17, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [27be69ed61](https://bsd-hardware.info/?probe=27be69ed61) | May 15, 2023 |
| ASRock        | Z790M-ITX WiFi              | [3bf2cd6d1e](https://bsd-hardware.info/?probe=3bf2cd6d1e) | May 14, 2023 |
| MSI           | B450M MORTAR                | [7d0fe109f0](https://bsd-hardware.info/?probe=7d0fe109f0) | May 14, 2023 |
| MSI           | B85M-G43                    | [6d2160dcee](https://bsd-hardware.info/?probe=6d2160dcee) | May 14, 2023 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [47800f4d42](https://bsd-hardware.info/?probe=47800f4d42) | May 14, 2023 |
| MSI           | H81M-P33                    | [ebf1ee8152](https://bsd-hardware.info/?probe=ebf1ee8152) | May 14, 2023 |
| ASUSTek       | P5Q-E                       | [2bf04b4cf1](https://bsd-hardware.info/?probe=2bf04b4cf1) | May 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ae7796a444](https://bsd-hardware.info/?probe=ae7796a444) | May 14, 2023 |
| HP            | 802F                        | [fdf293f78f](https://bsd-hardware.info/?probe=fdf293f78f) | May 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | [a477479a00](https://bsd-hardware.info/?probe=a477479a00) | May 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [de9fcd9543](https://bsd-hardware.info/?probe=de9fcd9543) | May 13, 2023 |
| Unknown       | Unknown                     | [990b3eb510](https://bsd-hardware.info/?probe=990b3eb510) | May 12, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [dcea67b6a6](https://bsd-hardware.info/?probe=dcea67b6a6) | May 08, 2023 |
| MSI           | H81M-P33                    | [55cfed4de4](https://bsd-hardware.info/?probe=55cfed4de4) | May 07, 2023 |
| ASUSTek       | P5Q-E                       | [0cb51a327e](https://bsd-hardware.info/?probe=0cb51a327e) | May 07, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [7e41914431](https://bsd-hardware.info/?probe=7e41914431) | May 07, 2023 |
| HP            | 805D                        | [648c680432](https://bsd-hardware.info/?probe=648c680432) | May 07, 2023 |
| ASUSTek       | P5K SE/EPU                  | [4cde43ac30](https://bsd-hardware.info/?probe=4cde43ac30) | May 04, 2023 |
| Supermicro    | X10DRi-T                    | [ba54a43cb4](https://bsd-hardware.info/?probe=ba54a43cb4) | May 03, 2023 |
| HP            | 1589                        | [4aee1909c8](https://bsd-hardware.info/?probe=4aee1909c8) | May 03, 2023 |
| Unknown       | HX90                        | [b3300c45bc](https://bsd-hardware.info/?probe=b3300c45bc) | May 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [9d82570c34](https://bsd-hardware.info/?probe=9d82570c34) | Apr 30, 2023 |
| Dell          | 0FF3FN A00                  | [717b46840a](https://bsd-hardware.info/?probe=717b46840a) | Apr 30, 2023 |
| Dell          | 0H634K A00                  | [5e783a1c2e](https://bsd-hardware.info/?probe=5e783a1c2e) | Apr 30, 2023 |
| Unknown       | Unknown                     | [21b338db1b](https://bsd-hardware.info/?probe=21b338db1b) | Apr 30, 2023 |
| MSI           | H81M-P33                    | [e28acf1164](https://bsd-hardware.info/?probe=e28acf1164) | Apr 30, 2023 |
| ASUSTek       | P5Q-E                       | [33d1b6e2d2](https://bsd-hardware.info/?probe=33d1b6e2d2) | Apr 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b0d9eaaceb](https://bsd-hardware.info/?probe=b0d9eaaceb) | Apr 30, 2023 |
| MSI           | H110M PRO-VD                | [ce8453fcce](https://bsd-hardware.info/?probe=ce8453fcce) | Apr 27, 2023 |
| Gigabyte      | B360M D2V                   | [d4881f1fb6](https://bsd-hardware.info/?probe=d4881f1fb6) | Apr 25, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [d3373e972b](https://bsd-hardware.info/?probe=d3373e972b) | Apr 24, 2023 |
| MSI           | H81M-P33                    | [6df7a17ff2](https://bsd-hardware.info/?probe=6df7a17ff2) | Apr 23, 2023 |
| ASUSTek       | P5Q-E                       | [37564b68c3](https://bsd-hardware.info/?probe=37564b68c3) | Apr 23, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d44a98739c](https://bsd-hardware.info/?probe=d44a98739c) | Apr 23, 2023 |
| ASUSTek       | P8H77-V                     | [60f61f7ecb](https://bsd-hardware.info/?probe=60f61f7ecb) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [838979f891](https://bsd-hardware.info/?probe=838979f891) | Apr 20, 2023 |
| HP            | 158B                        | [40fe372619](https://bsd-hardware.info/?probe=40fe372619) | Apr 20, 2023 |
| ASUSTek       | Pro B560M-C                 | [b341a9c9c9](https://bsd-hardware.info/?probe=b341a9c9c9) | Apr 19, 2023 |
| Lenovo        | YangTianM6880N              | [a567c3062c](https://bsd-hardware.info/?probe=a567c3062c) | Apr 18, 2023 |
| MSI           | H81M-P33                    | [e285cc821f](https://bsd-hardware.info/?probe=e285cc821f) | Apr 16, 2023 |
| ASUSTek       | P5Q-E                       | [b79bdd39da](https://bsd-hardware.info/?probe=b79bdd39da) | Apr 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [e6734bf5e3](https://bsd-hardware.info/?probe=e6734bf5e3) | Apr 16, 2023 |
| Dell          | 09KPNV A01                  | [cf533da9bf](https://bsd-hardware.info/?probe=cf533da9bf) | Apr 16, 2023 |
| ASUSTek       | PRIME X299-A II             | [8c345e7a24](https://bsd-hardware.info/?probe=8c345e7a24) | Apr 14, 2023 |
| Unknown       | Unknown                     | [926ab149ae](https://bsd-hardware.info/?probe=926ab149ae) | Apr 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | [e2b6422180](https://bsd-hardware.info/?probe=e2b6422180) | Apr 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [f54d0b103e](https://bsd-hardware.info/?probe=f54d0b103e) | Apr 13, 2023 |
| Unknown       | Unknown                     | [c960f2dc8b](https://bsd-hardware.info/?probe=c960f2dc8b) | Apr 12, 2023 |
| HP            | 212B                        | [0fb2a36b23](https://bsd-hardware.info/?probe=0fb2a36b23) | Apr 12, 2023 |
| MSI           | H81M-P33                    | [90ab4216eb](https://bsd-hardware.info/?probe=90ab4216eb) | Apr 09, 2023 |
| ASUSTek       | P5Q-E                       | [62358071bf](https://bsd-hardware.info/?probe=62358071bf) | Apr 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a06682a305](https://bsd-hardware.info/?probe=a06682a305) | Apr 09, 2023 |
| HP            | 212B                        | [6dc537109d](https://bsd-hardware.info/?probe=6dc537109d) | Apr 09, 2023 |
| Unknown       | Unknown                     | [f96c113329](https://bsd-hardware.info/?probe=f96c113329) | Apr 08, 2023 |
| ASUSTek       | PRIME B450M-K II            | [ee2b566f14](https://bsd-hardware.info/?probe=ee2b566f14) | Apr 04, 2023 |
| Unknown       | Unknown                     | [c801b9e5af](https://bsd-hardware.info/?probe=c801b9e5af) | Apr 03, 2023 |
| Unknown       | Unknown                     | [9b2420726f](https://bsd-hardware.info/?probe=9b2420726f) | Apr 03, 2023 |
| HP            | 212B                        | [00c0cbbc9a](https://bsd-hardware.info/?probe=00c0cbbc9a) | Apr 03, 2023 |
| Unknown       | Unknown                     | [414cbf5935](https://bsd-hardware.info/?probe=414cbf5935) | Apr 03, 2023 |
| Unknown       | Unknown                     | [6b79c64c73](https://bsd-hardware.info/?probe=6b79c64c73) | Apr 03, 2023 |
| Gigabyte      | GB-BSi3-1115G4              | [2a7e5e0e71](https://bsd-hardware.info/?probe=2a7e5e0e71) | Apr 02, 2023 |
| MSI           | B450M MORTAR MAX            | [01bf5e8678](https://bsd-hardware.info/?probe=01bf5e8678) | Apr 02, 2023 |
| MSI           | H81M-P33                    | [0013b5dfa4](https://bsd-hardware.info/?probe=0013b5dfa4) | Apr 02, 2023 |
| ASUSTek       | P5Q-E                       | [ff7383d618](https://bsd-hardware.info/?probe=ff7383d618) | Apr 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d4cc6cf349](https://bsd-hardware.info/?probe=d4cc6cf349) | Apr 02, 2023 |
| ASRock        | X570S PG Riptide            | [8ccb321056](https://bsd-hardware.info/?probe=8ccb321056) | Apr 01, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [c7944c3ce9](https://bsd-hardware.info/?probe=c7944c3ce9) | Mar 31, 2023 |
| SolidRun      | CEX7 Platform               | [8e2e4d6686](https://bsd-hardware.info/?probe=8e2e4d6686) | Mar 31, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [3c3a780d95](https://bsd-hardware.info/?probe=3c3a780d95) | Mar 31, 2023 |
| ASRockRack    | EPYCD8-2T                   | [75f414997a](https://bsd-hardware.info/?probe=75f414997a) | Mar 31, 2023 |
| HP            | 339A                        | [ad10416fe3](https://bsd-hardware.info/?probe=ad10416fe3) | Mar 31, 2023 |
| Biostar       | TH67B                       | [234c5e0b83](https://bsd-hardware.info/?probe=234c5e0b83) | Mar 31, 2023 |
| ASRock        | X570M Pro4                  | [1d7c737c38](https://bsd-hardware.info/?probe=1d7c737c38) | Mar 29, 2023 |
| Alienware     | 049PDM A00                  | [139d115cdb](https://bsd-hardware.info/?probe=139d115cdb) | Mar 29, 2023 |
| Shuttle       | FH110                       | [4fa8a9cc08](https://bsd-hardware.info/?probe=4fa8a9cc08) | Mar 28, 2023 |
| ASRock        | X570S PG Riptide            | [0d66edbd38](https://bsd-hardware.info/?probe=0d66edbd38) | Mar 27, 2023 |
| Dell          | 0VD5HY A00                  | [1b54a68123](https://bsd-hardware.info/?probe=1b54a68123) | Mar 26, 2023 |
| MSI           | H81M-P33                    | [f07e9fd36c](https://bsd-hardware.info/?probe=f07e9fd36c) | Mar 26, 2023 |
| ASUSTek       | P5Q-E                       | [3f21567fdf](https://bsd-hardware.info/?probe=3f21567fdf) | Mar 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [38a22651c6](https://bsd-hardware.info/?probe=38a22651c6) | Mar 26, 2023 |
| HP            | 1497                        | [08daaf3be1](https://bsd-hardware.info/?probe=08daaf3be1) | Mar 25, 2023 |
| HP            | 21B4 A01                    | [8de4b8231a](https://bsd-hardware.info/?probe=8de4b8231a) | Mar 25, 2023 |
| HP            | 1497                        | [fc6a7ebc91](https://bsd-hardware.info/?probe=fc6a7ebc91) | Mar 25, 2023 |
| HP            | 1497                        | [e98b5284d9](https://bsd-hardware.info/?probe=e98b5284d9) | Mar 25, 2023 |
| HP            | 3397                        | [a3a77965fc](https://bsd-hardware.info/?probe=a3a77965fc) | Mar 23, 2023 |
| ASRock        | B550M Pro4                  | [4dc54510d2](https://bsd-hardware.info/?probe=4dc54510d2) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | [cab50cddd5](https://bsd-hardware.info/?probe=cab50cddd5) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | [ff4dda40eb](https://bsd-hardware.info/?probe=ff4dda40eb) | Mar 19, 2023 |
| MSI           | H81M-P33                    | [17f0f138ee](https://bsd-hardware.info/?probe=17f0f138ee) | Mar 19, 2023 |
| ASUSTek       | P5Q-E                       | [da50d91be4](https://bsd-hardware.info/?probe=da50d91be4) | Mar 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [726abe2f1d](https://bsd-hardware.info/?probe=726abe2f1d) | Mar 19, 2023 |
| HP            | 212B                        | [d4d93ad679](https://bsd-hardware.info/?probe=d4d93ad679) | Mar 19, 2023 |
| Unknown       | Unknown                     | [88455ed9e7](https://bsd-hardware.info/?probe=88455ed9e7) | Mar 18, 2023 |
| HP            | 3397                        | [2851f91f5f](https://bsd-hardware.info/?probe=2851f91f5f) | Mar 17, 2023 |
| ASUSTek       | PRIME X370-PRO              | [49764ec5fa](https://bsd-hardware.info/?probe=49764ec5fa) | Mar 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [a8a9ed7f9e](https://bsd-hardware.info/?probe=a8a9ed7f9e) | Mar 13, 2023 |
| HP            | 0AA8h                       | [15ddd97321](https://bsd-hardware.info/?probe=15ddd97321) | Mar 12, 2023 |
| Supermicro    | X7DWE                       | [e40b569ff7](https://bsd-hardware.info/?probe=e40b569ff7) | Mar 12, 2023 |
| MSI           | H81M-P33                    | [12dbc1a2b3](https://bsd-hardware.info/?probe=12dbc1a2b3) | Mar 12, 2023 |
| ASUSTek       | P5Q-E                       | [bcd9058821](https://bsd-hardware.info/?probe=bcd9058821) | Mar 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d93ae717cc](https://bsd-hardware.info/?probe=d93ae717cc) | Mar 12, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [c8abf1f5bf](https://bsd-hardware.info/?probe=c8abf1f5bf) | Mar 11, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [3548f4efa2](https://bsd-hardware.info/?probe=3548f4efa2) | Mar 11, 2023 |
| MSI           | PRO H610M-B DDR4            | [654bdb4eb2](https://bsd-hardware.info/?probe=654bdb4eb2) | Mar 10, 2023 |
| Gigabyte      | B360M D2V                   | [6ac60b8104](https://bsd-hardware.info/?probe=6ac60b8104) | Mar 10, 2023 |
| Huanan        | X99-QD4 V1.0                | [58090b9dbf](https://bsd-hardware.info/?probe=58090b9dbf) | Mar 09, 2023 |
| ASRock        | H610M-HVS/M.2 R2.0          | [98fe8cc428](https://bsd-hardware.info/?probe=98fe8cc428) | Mar 09, 2023 |
| ASUSTek       | PRO B460M-C                 | [a3f77b82cc](https://bsd-hardware.info/?probe=a3f77b82cc) | Mar 05, 2023 |
| MSI           | H81M-P33                    | [dfa124b6f9](https://bsd-hardware.info/?probe=dfa124b6f9) | Mar 05, 2023 |
| ASUSTek       | P5Q-E                       | [64513c0ff5](https://bsd-hardware.info/?probe=64513c0ff5) | Mar 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ebba69095d](https://bsd-hardware.info/?probe=ebba69095d) | Mar 05, 2023 |
| ASRock        | E350M1                      | [461f8cca23](https://bsd-hardware.info/?probe=461f8cca23) | Mar 04, 2023 |
| Intel         | D510MO AAE76523-403         | [0da634580f](https://bsd-hardware.info/?probe=0da634580f) | Mar 03, 2023 |
| ASRock        | H470M-STX                   | [98096adfaa](https://bsd-hardware.info/?probe=98096adfaa) | Mar 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [d675a5bab2](https://bsd-hardware.info/?probe=d675a5bab2) | Feb 28, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | [735f2f3ece](https://bsd-hardware.info/?probe=735f2f3ece) | Feb 28, 2023 |
| Dell          | 0HHV7N A00                  | [ffbb7e1a96](https://bsd-hardware.info/?probe=ffbb7e1a96) | Feb 27, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | [b0fcea0c90](https://bsd-hardware.info/?probe=b0fcea0c90) | Feb 27, 2023 |
| MSI           | PRO H610M-B DDR4            | [e85ed3f609](https://bsd-hardware.info/?probe=e85ed3f609) | Feb 27, 2023 |
| MSI           | H81M-P33                    | [806efadc12](https://bsd-hardware.info/?probe=806efadc12) | Feb 26, 2023 |
| ASUSTek       | P5Q-E                       | [efb350b5f2](https://bsd-hardware.info/?probe=efb350b5f2) | Feb 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [62567aa5d4](https://bsd-hardware.info/?probe=62567aa5d4) | Feb 26, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [b2681fdfb4](https://bsd-hardware.info/?probe=b2681fdfb4) | Feb 23, 2023 |
| Gigabyte      | Z87X-OC-CF                  | [dca82c50d0](https://bsd-hardware.info/?probe=dca82c50d0) | Feb 23, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [e55635df08](https://bsd-hardware.info/?probe=e55635df08) | Feb 23, 2023 |
| Unknown       | Unknown                     | [9e92cf3575](https://bsd-hardware.info/?probe=9e92cf3575) | Feb 22, 2023 |
| ASRock        | X570 Taichi                 | [8eb068a097](https://bsd-hardware.info/?probe=8eb068a097) | Feb 20, 2023 |
| MSI           | H81M-P33                    | [28f48b7936](https://bsd-hardware.info/?probe=28f48b7936) | Feb 19, 2023 |
| ASUSTek       | P5Q-E                       | [b3525afaa7](https://bsd-hardware.info/?probe=b3525afaa7) | Feb 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [19c7044a7d](https://bsd-hardware.info/?probe=19c7044a7d) | Feb 19, 2023 |
| Intel         | DN2820FYK H24582-203        | [dd0d96422f](https://bsd-hardware.info/?probe=dd0d96422f) | Feb 19, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [b241a8afd7](https://bsd-hardware.info/?probe=b241a8afd7) | Feb 16, 2023 |
| ASRock        | A520M-ITX/ac                | [dd083df1a2](https://bsd-hardware.info/?probe=dd083df1a2) | Feb 16, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | [6f4b514959](https://bsd-hardware.info/?probe=6f4b514959) | Feb 14, 2023 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | [d69aba5432](https://bsd-hardware.info/?probe=d69aba5432) | Feb 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | [b3f41e1cb4](https://bsd-hardware.info/?probe=b3f41e1cb4) | Feb 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [b962baf73d](https://bsd-hardware.info/?probe=b962baf73d) | Feb 13, 2023 |
| ASUSTek       | P8Z68 DELUXE                | [f65675c771](https://bsd-hardware.info/?probe=f65675c771) | Feb 13, 2023 |
| ASUSTek       | H170I-PRO                   | [63000ada74](https://bsd-hardware.info/?probe=63000ada74) | Feb 12, 2023 |
| HP            | 212B                        | [0e13beb9f6](https://bsd-hardware.info/?probe=0e13beb9f6) | Feb 12, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [5507e05838](https://bsd-hardware.info/?probe=5507e05838) | Feb 12, 2023 |
| MSI           | H81M-P33                    | [84aff26f99](https://bsd-hardware.info/?probe=84aff26f99) | Feb 12, 2023 |
| ASUSTek       | P5Q-E                       | [4e899d9a1c](https://bsd-hardware.info/?probe=4e899d9a1c) | Feb 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d16e93b7f3](https://bsd-hardware.info/?probe=d16e93b7f3) | Feb 12, 2023 |
| ASUSTek       | PRIME H410M-K               | [d2edba8775](https://bsd-hardware.info/?probe=d2edba8775) | Feb 11, 2023 |
| Gigabyte      | Z490 VISION G               | [6f8ad1a8b9](https://bsd-hardware.info/?probe=6f8ad1a8b9) | Feb 11, 2023 |
| ASUSTek       | P7P55D DELUXE               | [dd9685a909](https://bsd-hardware.info/?probe=dd9685a909) | Feb 09, 2023 |
| Gigabyte      | H61M-S2V-B3                 | [33af90dd93](https://bsd-hardware.info/?probe=33af90dd93) | Feb 08, 2023 |
| MSI           | B450M MORTAR MAX            | [ec37957aed](https://bsd-hardware.info/?probe=ec37957aed) | Feb 05, 2023 |
| MSI           | H81M-P33                    | [6f8f329a5b](https://bsd-hardware.info/?probe=6f8f329a5b) | Feb 05, 2023 |
| ASUSTek       | P5Q-E                       | [bd418783d4](https://bsd-hardware.info/?probe=bd418783d4) | Feb 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ec1ab0bf97](https://bsd-hardware.info/?probe=ec1ab0bf97) | Feb 05, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [6d46662662](https://bsd-hardware.info/?probe=6d46662662) | Jan 31, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [82ab576c6c](https://bsd-hardware.info/?probe=82ab576c6c) | Jan 31, 2023 |
| ASRock        | 970 Extreme3                | [5e2fd4b48f](https://bsd-hardware.info/?probe=5e2fd4b48f) | Jan 30, 2023 |
| MSI           | H81M-P33                    | [e6626da98c](https://bsd-hardware.info/?probe=e6626da98c) | Jan 29, 2023 |
| ASUSTek       | P5Q-E                       | [3d5ea9f313](https://bsd-hardware.info/?probe=3d5ea9f313) | Jan 29, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [9b7532b795](https://bsd-hardware.info/?probe=9b7532b795) | Jan 29, 2023 |
| Dell          | 08NPPY A00                  | [1c4edf62e6](https://bsd-hardware.info/?probe=1c4edf62e6) | Jan 28, 2023 |
| Gigabyte      | B550 AORUS PRO              | [8fd7f80256](https://bsd-hardware.info/?probe=8fd7f80256) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [87e25e2abd](https://bsd-hardware.info/?probe=87e25e2abd) | Jan 26, 2023 |
| Shuttle       | DS20U                       | [71033e4a64](https://bsd-hardware.info/?probe=71033e4a64) | Jan 26, 2023 |
| IBM           | 9210MML                     | [8b7e2413ee](https://bsd-hardware.info/?probe=8b7e2413ee) | Jan 25, 2023 |
| ADI Engine... | RCC-VE                      | [e2941c00fc](https://bsd-hardware.info/?probe=e2941c00fc) | Jan 25, 2023 |
| ASUSTek       | P5Q-E                       | [26d1d923d6](https://bsd-hardware.info/?probe=26d1d923d6) | Jan 22, 2023 |
| MSI           | H81M-P33                    | [0bbc074f1c](https://bsd-hardware.info/?probe=0bbc074f1c) | Jan 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [28d8d82d34](https://bsd-hardware.info/?probe=28d8d82d34) | Jan 22, 2023 |
| Unknown       | AMD-GX3                     | [a38ff8331a](https://bsd-hardware.info/?probe=a38ff8331a) | Jan 20, 2023 |
| Unknown       | Unknown                     | [3afbfc6cea](https://bsd-hardware.info/?probe=3afbfc6cea) | Jan 20, 2023 |
| Unknown       | YL-SKUL6                    | [ef4abfe322](https://bsd-hardware.info/?probe=ef4abfe322) | Jan 20, 2023 |
| Unknown       | Unknown                     | [e13627df1a](https://bsd-hardware.info/?probe=e13627df1a) | Jan 20, 2023 |
| MSI           | B85M-G43                    | [35e269ef1c](https://bsd-hardware.info/?probe=35e269ef1c) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [b528c0bbe3](https://bsd-hardware.info/?probe=b528c0bbe3) | Jan 18, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [c3281eb186](https://bsd-hardware.info/?probe=c3281eb186) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | [f7de27b0ca](https://bsd-hardware.info/?probe=f7de27b0ca) | Jan 18, 2023 |
| Lenovo        | H30-05 90BJ0085SP           | [d491694079](https://bsd-hardware.info/?probe=d491694079) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | [9eee9cc526](https://bsd-hardware.info/?probe=9eee9cc526) | Jan 18, 2023 |
| Intel         | DH67BL AAG10189-206         | [37ae895d75](https://bsd-hardware.info/?probe=37ae895d75) | Jan 17, 2023 |
| Intel         | DQ45CB AAE30148-302         | [349da05405](https://bsd-hardware.info/?probe=349da05405) | Jan 17, 2023 |
| HP            | 1998                        | [6c36e5e82e](https://bsd-hardware.info/?probe=6c36e5e82e) | Jan 17, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [7ef714a7f1](https://bsd-hardware.info/?probe=7ef714a7f1) | Jan 16, 2023 |
| MSI           | H81M-P33                    | [800b3bc34b](https://bsd-hardware.info/?probe=800b3bc34b) | Jan 15, 2023 |
| ASUSTek       | P5Q-E                       | [ffbcac312f](https://bsd-hardware.info/?probe=ffbcac312f) | Jan 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [48e7397e29](https://bsd-hardware.info/?probe=48e7397e29) | Jan 15, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [05cc17947c](https://bsd-hardware.info/?probe=05cc17947c) | Jan 15, 2023 |
| ASUSTek       | PRIME X370-PRO              | [f682e06d06](https://bsd-hardware.info/?probe=f682e06d06) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [917972b6ae](https://bsd-hardware.info/?probe=917972b6ae) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [bd60eadfc4](https://bsd-hardware.info/?probe=bd60eadfc4) | Jan 12, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [95ebd841b2](https://bsd-hardware.info/?probe=95ebd841b2) | Jan 12, 2023 |
| ASUSTek       | PRIME Z390-P                | [3126dc27f1](https://bsd-hardware.info/?probe=3126dc27f1) | Jan 12, 2023 |
| ASRockRack    | X470D4U2/1N1                | [07f15d0014](https://bsd-hardware.info/?probe=07f15d0014) | Jan 11, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [8def3dc9b2](https://bsd-hardware.info/?probe=8def3dc9b2) | Jan 09, 2023 |
| MSI           | H81M-P33                    | [585a3dc78c](https://bsd-hardware.info/?probe=585a3dc78c) | Jan 08, 2023 |
| ASUSTek       | P5Q-E                       | [1e9d8cc278](https://bsd-hardware.info/?probe=1e9d8cc278) | Jan 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [490261883c](https://bsd-hardware.info/?probe=490261883c) | Jan 08, 2023 |
| MSI           | MEG Z690 UNIFY-X            | [e70cd80d11](https://bsd-hardware.info/?probe=e70cd80d11) | Jan 05, 2023 |
| Dell          | 02YYK5 A01                  | [219200b0b6](https://bsd-hardware.info/?probe=219200b0b6) | Jan 05, 2023 |
| MSI           | PRO H610M-B DDR4            | [cc9d84d5ed](https://bsd-hardware.info/?probe=cc9d84d5ed) | Jan 05, 2023 |
| ASUSTek       | X99-DELUXE                  | [9dc3183152](https://bsd-hardware.info/?probe=9dc3183152) | Jan 04, 2023 |
| Supermicro    | X10DRiB                     | [d120c268f7](https://bsd-hardware.info/?probe=d120c268f7) | Jan 04, 2023 |
| HP            | ProLiant MicroServer Gen... | [409d119307](https://bsd-hardware.info/?probe=409d119307) | Jan 02, 2023 |
| Intel         | DH77KC AAG39641-400         | [d66b90249d](https://bsd-hardware.info/?probe=d66b90249d) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [1697219032](https://bsd-hardware.info/?probe=1697219032) | Jan 02, 2023 |
| Shuttle       | DS20U                       | [a5aa09e49f](https://bsd-hardware.info/?probe=a5aa09e49f) | Jan 01, 2023 |
| MSI           | H81M-P33                    | [0a57dcce99](https://bsd-hardware.info/?probe=0a57dcce99) | Jan 01, 2023 |
| ASUSTek       | P5Q-E                       | [d3306559de](https://bsd-hardware.info/?probe=d3306559de) | Jan 01, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [772779fadf](https://bsd-hardware.info/?probe=772779fadf) | Jan 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [ab7e64f657](https://bsd-hardware.info/?probe=ab7e64f657) | Dec 31, 2022 |
| Lenovo        | 30D9 SDK0J40700 WIN 3258... | [ac867149f2](https://bsd-hardware.info/?probe=ac867149f2) | Dec 31, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [d22c37fa81](https://bsd-hardware.info/?probe=d22c37fa81) | Dec 29, 2022 |
| MSI           | H270 GAMING M3              | [5d14519e73](https://bsd-hardware.info/?probe=5d14519e73) | Dec 28, 2022 |
| MSI           | H270 GAMING M3              | [5dcdab1ee3](https://bsd-hardware.info/?probe=5dcdab1ee3) | Dec 28, 2022 |
| HP            | ProLiant MicroServer        | [50c8cb79f7](https://bsd-hardware.info/?probe=50c8cb79f7) | Dec 26, 2022 |
| ASUSTek       | P5Q-E                       | [bc829dbb1a](https://bsd-hardware.info/?probe=bc829dbb1a) | Dec 25, 2022 |
| MSI           | H81M-P33                    | [f73a37ab81](https://bsd-hardware.info/?probe=f73a37ab81) | Dec 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2e842ddb27](https://bsd-hardware.info/?probe=2e842ddb27) | Dec 25, 2022 |
| Supermicro    | X10SRH-CLN4FA               | [84c360ad02](https://bsd-hardware.info/?probe=84c360ad02) | Dec 24, 2022 |
| HP            | ProLiant MicroServer Gen... | [a2bc442acd](https://bsd-hardware.info/?probe=a2bc442acd) | Dec 23, 2022 |
| Unknown       | Unknown                     | [d702dfcde2](https://bsd-hardware.info/?probe=d702dfcde2) | Dec 23, 2022 |
| Supermicro    | X9DR3-F                     | [b8c89bdca8](https://bsd-hardware.info/?probe=b8c89bdca8) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | [b0d1792185](https://bsd-hardware.info/?probe=b0d1792185) | Dec 21, 2022 |
| ASRock        | 4X4-4000 Series             | [009ef73bd1](https://bsd-hardware.info/?probe=009ef73bd1) | Dec 20, 2022 |
| HP            | ProLiant MicroServer Gen... | [8de4ff8626](https://bsd-hardware.info/?probe=8de4ff8626) | Dec 20, 2022 |
| Dell          | 09KPNV A01                  | [0eea35e069](https://bsd-hardware.info/?probe=0eea35e069) | Dec 19, 2022 |
| HP            | ProLiant MicroServer        | [b730e64d4a](https://bsd-hardware.info/?probe=b730e64d4a) | Dec 19, 2022 |
| Acer          | Veriton M680G               | [cb44a9e848](https://bsd-hardware.info/?probe=cb44a9e848) | Dec 19, 2022 |
| Acer          | Veriton M680G               | [f7184d9158](https://bsd-hardware.info/?probe=f7184d9158) | Dec 19, 2022 |
| ASRock        | B660M-ITX/ac                | [f6c8eb4e18](https://bsd-hardware.info/?probe=f6c8eb4e18) | Dec 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c1b0b83306](https://bsd-hardware.info/?probe=c1b0b83306) | Dec 18, 2022 |
| MSI           | H81M-P33                    | [78e4743abd](https://bsd-hardware.info/?probe=78e4743abd) | Dec 18, 2022 |
| ASUSTek       | P5Q-E                       | [f232e5746e](https://bsd-hardware.info/?probe=f232e5746e) | Dec 18, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | [108c9de5cc](https://bsd-hardware.info/?probe=108c9de5cc) | Dec 18, 2022 |
| BESSTAR Te... | UM350                       | [b7e599f99d](https://bsd-hardware.info/?probe=b7e599f99d) | Dec 17, 2022 |
| Unknown       | Unknown                     | [7c644cc639](https://bsd-hardware.info/?probe=7c644cc639) | Dec 15, 2022 |
| HP            | ProLiant MicroServer        | [617f431099](https://bsd-hardware.info/?probe=617f431099) | Dec 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | [f52a3d3fa6](https://bsd-hardware.info/?probe=f52a3d3fa6) | Dec 13, 2022 |
| ASUSTek       | PRIME H410M-A               | [f51b401c31](https://bsd-hardware.info/?probe=f51b401c31) | Dec 13, 2022 |
| Huanan        | X99-F8D V2.4                | [3d06b605c5](https://bsd-hardware.info/?probe=3d06b605c5) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [73cb5d86bc](https://bsd-hardware.info/?probe=73cb5d86bc) | Dec 12, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/FreeBSD/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| FreeBSD 13.1         | 96       | 5.64%   |
| FreeBSD 13.0         | 78       | 4.58%   |
| FreeBSD 13.2         | 69       | 4.05%   |
| FreeBSD 12.2         | 66       | 3.88%   |
| FreeBSD 14.0-CURRENT | 62       | 3.64%   |
| FreeBSD 13.0-p5      | 43       | 2.53%   |
| FreeBSD 12.2-p2      | 41       | 2.41%   |
| FreeBSD 14.0         | 40       | 2.35%   |
| FreeBSD 13.1-p2      | 40       | 2.35%   |
| FreeBSD 14.1         | 38       | 2.23%   |
| FreeBSD 14.0-p6      | 35       | 2.06%   |
| FreeBSD 13.0-p4      | 35       | 2.06%   |
| FreeBSD 12.1-p8      | 35       | 2.06%   |
| FreeBSD 12.1-p10     | 35       | 2.06%   |
| FreeBSD 13.1-p5      | 33       | 1.94%   |
| FreeBSD 13.0-STABLE  | 33       | 1.94%   |
| FreeBSD 12.1-STABLE  | 29       | 1.7%    |
| FreeBSD 12.1-p5      | 29       | 1.7%    |
| FreeBSD 12.1-p7      | 28       | 1.65%   |
| FreeBSD 13.1-p7      | 26       | 1.53%   |
| FreeBSD 14.1-p6      | 24       | 1.41%   |
| FreeBSD 14.0-p4      | 24       | 1.41%   |
| FreeBSD 12.2-p3      | 24       | 1.41%   |
| FreeBSD 14.2         | 23       | 1.35%   |
| FreeBSD 13.0-CURRENT | 22       | 1.29%   |
| FreeBSD 12.1         | 22       | 1.29%   |
| FreeBSD 14.1-p5      | 21       | 1.23%   |
| FreeBSD 13.0-p11     | 21       | 1.23%   |
| FreeBSD 14.0-p5      | 20       | 1.18%   |
| FreeBSD 13.0-p7      | 20       | 1.18%   |
| FreeBSD 12.2-p4      | 19       | 1.12%   |
| FreeBSD 13.0-p3      | 18       | 1.06%   |
| FreeBSD 12.2-STABLE  | 17       | 1%      |
| FreeBSD 13.2-p2      | 16       | 0.94%   |
| FreeBSD 12.3         | 16       | 0.94%   |
| FreeBSD 13.1-STABLE  | 15       | 0.88%   |
| FreeBSD 13.0-p10     | 14       | 0.82%   |
| FreeBSD 15.0-CURRENT | 13       | 0.76%   |
| FreeBSD 14.1-p3      | 13       | 0.76%   |
| FreeBSD 14.0-BETA5   | 13       | 0.76%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| FreeBSD | 1327     | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 1234     | 92.99%  |
| arm64   | 40       | 3.01%   |
| i386    | 35       | 2.64%   |
| arm     | 10       | 0.75%   |
| powerpc | 6        | 0.45%   |
| sparc64 | 1        | 0.08%   |
| riscv   | 1        | 0.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 574      | 41.47%  |
| KDE5          | 230      | 16.62%  |
| XFCE          | 175      | 12.64%  |
| GNOME         | 89       | 6.43%   |
| TWM           | 86       | 6.21%   |
| MATE          | 62       | 4.48%   |
| i3            | 33       | 2.38%   |
| Openbox       | 28       | 2.02%   |
| LXQt          | 13       | 0.94%   |
| AwesomeWM     | 11       | 0.79%   |
| Fluxbox       | 10       | 0.72%   |
| Cinnamon      | 10       | 0.72%   |
| Enlightenment | 8        | 0.58%   |
| LXDE          | 7        | 0.51%   |
| DWM           | 6        | 0.43%   |
| X-Cinnamon    | 5        | 0.36%   |
| Lumina        | 5        | 0.36%   |
| CDE           | 4        | 0.29%   |
| Picom         | 3        | 0.22%   |
| KDE           | 3        | 0.22%   |
| xinitrc       | 2        | 0.14%   |
| xfwm          | 2        | 0.14%   |
| Window Maker  | 2        | 0.14%   |
| GNUstep       | 2        | 0.14%   |
| Budgie        | 2        | 0.14%   |
| wlroots       | 1        | 0.07%   |
| WindowMaker   | 1        | 0.07%   |
| spectrwm      | 1        | 0.07%   |
| plasma        | 1        | 0.07%   |
| KWin          | 1        | 0.07%   |
| ICEWM         | 1        | 0.07%   |
| Hyprland      | 1        | 0.07%   |
| fvwm2         | 1        | 0.07%   |
| Compton       | 1        | 0.07%   |
| bspwm         | 1        | 0.07%   |
| Blackbox      | 1        | 0.07%   |
| akonadi_newm  | 1        | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 710      | 52.51%  |
| Console | 615      | 45.49%  |
| Wayland | 26       | 1.92%   |
| Tty     | 1        | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 828      | 60.57%  |
| SDDM    | 222      | 16.24%  |
| LightDM | 86       | 6.29%   |
| SLiM    | 85       | 6.22%   |
| XDM     | 80       | 5.85%   |
| GDM     | 54       | 3.95%   |
| Ly      | 12       | 0.88%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Desktops | Percent |
|------------------|----------|---------|
| C                | 599      | 42.85%  |
| Unknown          | 331      | 23.68%  |
| en_US            | 220      | 15.74%  |
| ru_RU            | 89       | 6.37%   |
| de_DE            | 25       | 1.79%   |
| fr_FR            | 18       | 1.29%   |
| en_GB            | 15       | 1.07%   |
| pt_BR            | 9        | 0.64%   |
| en_CA            | 9        | 0.64%   |
| zh_CN            | 8        | 0.57%   |
| ja_JP            | 7        | 0.5%    |
| it_IT            | 7        | 0.5%    |
| uk_UA            | 6        | 0.43%   |
| pl_PL            | 6        | 0.43%   |
| es_ES            | 5        | 0.36%   |
| en_AU            | 5        | 0.36%   |
| fi_FI            | 4        | 0.29%   |
| en_IE            | 4        | 0.29%   |
| el_GR            | 4        | 0.29%   |
| ru_RU.KOI8-R     | 3        | 0.21%   |
| sv_SE            | 2        | 0.14%   |
| nb_NO            | 2        | 0.14%   |
| es_AR            | 2        | 0.14%   |
| zh_TW            | 1        | 0.07%   |
| sv_SE.US-ASCII   | 1        | 0.07%   |
| ru               | 1        | 0.07%   |
| nl_NL            | 1        | 0.07%   |
| it_IT.ISO8859-15 | 1        | 0.07%   |
| fr_FR.US-ASCII   | 1        | 0.07%   |
| fi_FI.ISO8859-15 | 1        | 0.07%   |
| et_EE.US-ASCII   | 1        | 0.07%   |
| es_MX            | 1        | 0.07%   |
| es_ES.ISO8859-15 | 1        | 0.07%   |
| en_US.utf-8      | 1        | 0.07%   |
| en_US.ISO8859-15 | 1        | 0.07%   |
| en_US.ISO8859-1  | 1        | 0.07%   |
| en_GB.US-ASCII   | 1        | 0.07%   |
| de_DE.ISO8859-1  | 1        | 0.07%   |
| de_CH            | 1        | 0.07%   |
| da_DK            | 1        | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 829      | 61.54%  |
| BIOS | 518      | 38.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Zfs    | 858      | 63.89%  |
| Ufs    | 481      | 35.82%  |
| Cd9660 | 2        | 0.15%   |
| Nullfs | 1        | 0.07%   |
| Nfs    | 1        | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1198     | 89.87%  |
| MBR     | 119      | 8.93%   |
| Unknown | 11       | 0.83%   |
| BSD     | 5        | 0.38%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 292      | 22%     |
| Gigabyte Technology                  | 175      | 13.19%  |
| ASRock                               | 131      | 9.87%   |
| MSI                                  | 117      | 8.82%   |
| Hewlett-Packard                      | 109      | 8.21%   |
| Dell                                 | 101      | 7.61%   |
| Unknown                              | 78       | 5.88%   |
| Intel                                | 52       | 3.92%   |
| Supermicro                           | 37       | 2.79%   |
| Lenovo                               | 30       | 2.26%   |
| Fujitsu                              | 23       | 1.73%   |
| PC Engines                           | 18       | 1.36%   |
| ASRockRack                           | 17       | 1.28%   |
| Acer                                 | 11       | 0.83%   |
| Shuttle                              | 8        | 0.6%    |
| Biostar                              | 6        | 0.45%   |
| Apple                                | 6        | 0.45%   |
| Foxconn                              | 5        | 0.38%   |
| Beckhoff Automation                  | 5        | 0.38%   |
| AZW                                  | 5        | 0.38%   |
| Wistron                              | 4        | 0.3%    |
| Shenzhen Meigao Electronic Equipment | 4        | 0.3%    |
| Huanan                               | 4        | 0.3%    |
| HPE                                  | 4        | 0.3%    |
| Alienware                            | 4        | 0.3%    |
| Pegatron                             | 3        | 0.23%   |
| EVGA                                 | 3        | 0.23%   |
| AMI                                  | 3        | 0.23%   |
| TYAN Computer                        | 2        | 0.15%   |
| Radxa                                | 2        | 0.15%   |
| Protectli                            | 2        | 0.15%   |
| pine64                               | 2        | 0.15%   |
| Google                               | 2        | 0.15%   |
| Gateway                              | 2        | 0.15%   |
| ECS                                  | 2        | 0.15%   |
| Deciso                               | 2        | 0.15%   |
| BESSTAR Tech                         | 2        | 0.15%   |
| ADI Engineering                      | 2        | 0.15%   |
| ZOTAC                                | 1        | 0.08%   |
| WeiBu                                | 1        | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Unknown                                           | 80       | 6.03%   |
| ASUS All Series                                   | 31       | 2.34%   |
| HP ProLiant MicroServer Gen8                      | 11       | 0.83%   |
| PC Engines APU2                                   | 10       | 0.75%   |
| MSI MS-7B89                                       | 10       | 0.75%   |
| Intel Nobilis                                     | 9        | 0.68%   |
| ASUS TUF Gaming X570-PLUS                         | 9        | 0.68%   |
| HP ProLiant MicroServer                           | 8        | 0.6%    |
| Dell OptiPlex 9020                                | 8        | 0.6%    |
| Gigabyte B450M DS3H                               | 6        | 0.45%   |
| ASRock Z590 Pro4                                  | 6        | 0.45%   |
| MSI MS-7C02                                       | 5        | 0.38%   |
| HP Z620 Workstation                               | 5        | 0.38%   |
| HP Z440 Workstation                               | 5        | 0.38%   |
| Gigabyte B360N WIFI                               | 5        | 0.38%   |
| Fujitsu D3401-H2 S26361-D3401-H2                  | 5        | 0.38%   |
| Dell OptiPlex 7050                                | 5        | 0.38%   |
| ASUS M5A97 LE R2.0                                | 5        | 0.38%   |
| ASRock X570 Phantom Gaming 4                      | 5        | 0.38%   |
| Supermicro X9SCL/X9SCM                            | 4        | 0.3%    |
| Shenzhen Meigao Electronic Equipment Venus Series | 4        | 0.3%    |
| MSI MS-7B86                                       | 4        | 0.3%    |
| MSI MS-7A38                                       | 4        | 0.3%    |
| MSI MS-7693                                       | 4        | 0.3%    |
| HP Z420 Workstation                               | 4        | 0.3%    |
| HP t620 Quad Core TC                              | 4        | 0.3%    |
| HP Compaq Elite 8300 SFF                          | 4        | 0.3%    |
| Gigabyte X570 I AORUS PRO WIFI                    | 4        | 0.3%    |
| Dell PowerEdge T30                                | 4        | 0.3%    |
| Dell OptiPlex 7040                                | 4        | 0.3%    |
| Dell OptiPlex 3010                                | 4        | 0.3%    |
| ASUS TUF Gaming B550-PLUS                         | 4        | 0.3%    |
| ASUS SABERTOOTH 990FX R2.0                        | 4        | 0.3%    |
| ASUS ROG STRIX B550-F GAMING                      | 4        | 0.3%    |
| ASRock Q1900B-ITX                                 | 4        | 0.3%    |
| Apple MacPro5,1                                   | 4        | 0.3%    |
| Wistron ProLiant ML110 G6                         | 3        | 0.23%   |
| Supermicro X7SPA-HF                               | 3        | 0.23%   |
| PC Engines apu4                                   | 3        | 0.23%   |
| PC Engines APU                                    | 3        | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 80       | 6.03%   |
| Dell OptiPlex       | 63       | 4.75%   |
| ASUS PRIME          | 57       | 4.3%    |
| ASUS TUF            | 38       | 2.86%   |
| ASUS ROG            | 35       | 2.64%   |
| ASUS All            | 31       | 2.34%   |
| HP ProLiant         | 26       | 1.96%   |
| HP Compaq           | 22       | 1.66%   |
| Dell Precision      | 16       | 1.21%   |
| Lenovo ThinkCentre  | 15       | 1.13%   |
| ASRock X570         | 15       | 1.13%   |
| HP EliteDesk        | 12       | 0.9%    |
| Gigabyte B450M      | 12       | 0.9%    |
| Gigabyte X570       | 11       | 0.83%   |
| PC Engines APU2     | 10       | 0.75%   |
| MSI MS-7B89         | 10       | 0.75%   |
| Intel Nobilis       | 9        | 0.68%   |
| Fujitsu ESPRIMO     | 9        | 0.68%   |
| ASUS PRO            | 9        | 0.68%   |
| Dell PowerEdge      | 8        | 0.6%    |
| ASRock X370         | 8        | 0.6%    |
| HP t620             | 7        | 0.53%   |
| HP ProDesk          | 7        | 0.53%   |
| ASRock Z590         | 7        | 0.53%   |
| ASRock B550         | 7        | 0.53%   |
| ASUS M5A97          | 6        | 0.45%   |
| MSI MS-7C02         | 5        | 0.38%   |
| Lenovo ThinkStation | 5        | 0.38%   |
| Lenovo IdeaCentre   | 5        | 0.38%   |
| HP Z620             | 5        | 0.38%   |
| HP Z440             | 5        | 0.38%   |
| Gigabyte X470       | 5        | 0.38%   |
| Gigabyte B360N      | 5        | 0.38%   |
| Fujitsu D3401-H2    | 5        | 0.38%   |
| ASUS SABERTOOTH     | 5        | 0.38%   |
| ASRock 970          | 5        | 0.38%   |
| Acer Veriton        | 5        | 0.38%   |
| Acer Aspire         | 5        | 0.38%   |
| Wistron ProLiant    | 4        | 0.3%    |
| Supermicro X9SCL    | 4        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2019    | 129      | 9.72%   |
| 2020    | 113      | 8.52%   |
| 2018    | 109      | 8.21%   |
| 2013    | 94       | 7.08%   |
| 2021    | 89       | 6.71%   |
| 2014    | 84       | 6.33%   |
| 2012    | 83       | 6.25%   |
| 2011    | 78       | 5.88%   |
| 2017    | 69       | 5.2%    |
| 2016    | 64       | 4.82%   |
| Unknown | 58       | 4.37%   |
| 2023    | 57       | 4.3%    |
| 2015    | 56       | 4.22%   |
| 2010    | 54       | 4.07%   |
| 2022    | 53       | 3.99%   |
| 2009    | 42       | 3.17%   |
| 2008    | 35       | 2.64%   |
| 2024    | 24       | 1.81%   |
| 2007    | 15       | 1.13%   |
| 2006    | 7        | 0.53%   |
| 2005    | 5        | 0.38%   |
| 2004    | 4        | 0.3%    |
| 2003    | 2        | 0.15%   |
| 2002    | 2        | 0.15%   |
| 2001    | 1        | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1327     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1299     | 97.89%  |
| Yes  | 28       | 2.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 332      | 24.59%  |
| 8.01-16.0       | 295      | 21.85%  |
| 32.01-64.0      | 272      | 20.15%  |
| 64.01-256.0     | 172      | 12.74%  |
| 4.01-8.0        | 142      | 10.52%  |
| 2.01-3.0        | 37       | 2.74%   |
| 24.01-32.0      | 26       | 1.93%   |
| 0.51-1.0        | 26       | 1.93%   |
| 3.01-4.0        | 21       | 1.56%   |
| 0.01-0.5        | 14       | 1.04%   |
| More than 256.0 | 6        | 0.44%   |
| 1.01-2.0        | 6        | 0.44%   |
| Unknown         | 1        | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.51-1.0    | 420      | 30.19%  |
| 0.01-0.5    | 388      | 27.89%  |
| 1.01-2.0    | 305      | 21.93%  |
| 2.01-3.0    | 84       | 6.04%   |
| 4.01-8.0    | 54       | 3.88%   |
| 3.01-4.0    | 50       | 3.59%   |
| 8.01-16.0   | 25       | 1.8%    |
| 0           | 20       | 1.44%   |
| 24.01-32.0  | 14       | 1.01%   |
| 32.01-64.0  | 11       | 0.79%   |
| 16.01-24.0  | 10       | 0.72%   |
| 64.01-256.0 | 9        | 0.65%   |
| Unknown     | 1        | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 401      | 28.18%  |
| 2      | 339      | 23.82%  |
| 3      | 204      | 14.34%  |
| 4      | 141      | 9.91%   |
| 0      | 120      | 8.43%   |
| 5      | 91       | 6.39%   |
| 6      | 46       | 3.23%   |
| 7      | 28       | 1.97%   |
| 8      | 13       | 0.91%   |
| 9      | 10       | 0.7%    |
| 10     | 9        | 0.63%   |
| 12     | 4        | 0.28%   |
| 14     | 3        | 0.21%   |
| 11     | 3        | 0.21%   |
| 23     | 2        | 0.14%   |
| 17     | 2        | 0.14%   |
| 13     | 2        | 0.14%   |
| 24     | 1        | 0.07%   |
| 21     | 1        | 0.07%   |
| 19     | 1        | 0.07%   |
| 18     | 1        | 0.07%   |
| 15     | 1        | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 945      | 70.58%  |
| Yes       | 394      | 29.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1276     | 96.08%  |
| No        | 52       | 3.92%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 964      | 71.73%  |
| Yes       | 380      | 28.27%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1055     | 78.85%  |
| Yes       | 283      | 21.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 303      | 22.6%   |
| Russia      | 182      | 13.57%  |
| Germany     | 138      | 10.29%  |
| France      | 61       | 4.55%   |
| Canada      | 59       | 4.4%    |
| Poland      | 51       | 3.8%    |
| UK          | 48       | 3.58%   |
| Netherlands | 33       | 2.46%   |
| Australia   | 31       | 2.31%   |
| Brazil      | 29       | 2.16%   |
| Ukraine     | 24       | 1.79%   |
| Czechia     | 24       | 1.79%   |
| Italy       | 22       | 1.64%   |
| China       | 22       | 1.64%   |
| Japan       | 20       | 1.49%   |
| Sweden      | 19       | 1.42%   |
| Spain       | 19       | 1.42%   |
| Finland     | 17       | 1.27%   |
| Romania     | 15       | 1.12%   |
| Indonesia   | 15       | 1.12%   |
| Switzerland | 14       | 1.04%   |
| Ireland     | 12       | 0.89%   |
| Austria     | 12       | 0.89%   |
| Greece      | 11       | 0.82%   |
| Norway      | 10       | 0.75%   |
| Hungary     | 9        | 0.67%   |
| India       | 8        | 0.6%    |
| Thailand    | 7        | 0.52%   |
| Taiwan      | 7        | 0.52%   |
| Serbia      | 7        | 0.52%   |
| Bulgaria    | 7        | 0.52%   |
| Belgium     | 7        | 0.52%   |
| Mexico      | 6        | 0.45%   |
| Argentina   | 6        | 0.45%   |
| Slovenia    | 5        | 0.37%   |
| Denmark     | 5        | 0.37%   |
| Chile       | 5        | 0.37%   |
| Turkey      | 4        | 0.3%    |
| Slovakia    | 4        | 0.3%    |
| New Zealand | 4        | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 65       | 4.5%    |
| St Petersburg     | 17       | 1.18%   |
| Krasnodar         | 16       | 1.11%   |
| Grand Rapids      | 16       | 1.11%   |
| Berlin            | 16       | 1.11%   |
| Sydney            | 13       | 0.9%    |
| Kyiv              | 12       | 0.83%   |
| Ludwigsburg       | 11       | 0.76%   |
| Helsinki          | 10       | 0.69%   |
| Yekaterinburg     | 9        | 0.62%   |
| Vienna            | 9        | 0.62%   |
| Paris             | 9        | 0.62%   |
| Amsterdam         | 9        | 0.62%   |
| Warsaw            | 8        | 0.55%   |
| Tuklaty           | 8        | 0.55%   |
| Montreal          | 8        | 0.55%   |
| Madrid            | 8        | 0.55%   |
| New York          | 7        | 0.48%   |
| London            | 7        | 0.48%   |
| Kamensk-Ural'skiy | 7        | 0.48%   |
| Hamburg           | 7        | 0.48%   |
| Falkenstein       | 7        | 0.48%   |
| Dublin            | 7        | 0.48%   |
| Chicago           | 7        | 0.48%   |
| Toronto           | 6        | 0.41%   |
| Stockholm         | 6        | 0.41%   |
| Rochester         | 6        | 0.41%   |
| Prague            | 6        | 0.41%   |
| Poway             | 6        | 0.41%   |
| Portland          | 6        | 0.41%   |
| Novosibirsk       | 6        | 0.41%   |
| Medan             | 6        | 0.41%   |
| Lublin            | 6        | 0.41%   |
| Brooklyn          | 6        | 0.41%   |
| Zurich            | 5        | 0.35%   |
| Zaporizhzhya      | 5        | 0.35%   |
| Vancouver         | 5        | 0.35%   |
| Teaneck           | 5        | 0.35%   |
| Sofia             | 5        | 0.35%   |
| Shenzhen          | 5        | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 490      | 1703   | 22.31%  |
| Seagate             | 389      | 1010   | 17.71%  |
| Samsung Electronics | 330      | 869    | 15.03%  |
| Toshiba             | 138      | 316    | 6.28%   |
| Kingston            | 126      | 172    | 5.74%   |
| Crucial             | 124      | 201    | 5.65%   |
| Intel               | 75       | 160    | 3.42%   |
| Hitachi             | 60       | 137    | 2.73%   |
| SanDisk             | 53       | 73     | 2.41%   |
| HGST                | 49       | 112    | 2.23%   |
| A-DATA Technology   | 40       | 51     | 1.82%   |
| Transcend           | 17       | 24     | 0.77%   |
| SPCC                | 16       | 37     | 0.73%   |
| SK hynix            | 16       | 32     | 0.73%   |
| OCZ                 | 14       | 17     | 0.64%   |
| Micron Technology   | 14       | 28     | 0.64%   |
| Corsair             | 14       | 43     | 0.64%   |
| Phison              | 13       | 17     | 0.59%   |
| Hewlett-Packard     | 13       | 44     | 0.59%   |
| GOODRAM             | 11       | 25     | 0.5%    |
| PNY                 | 10       | 13     | 0.46%   |
| Maxtor              | 10       | 14     | 0.46%   |
| Patriot             | 9        | 13     | 0.41%   |
| China               | 9        | 15     | 0.41%   |
| Plextor             | 8        | 14     | 0.36%   |
| Gigabyte Technology | 8        | 13     | 0.36%   |
| Intenso             | 7        | 8      | 0.32%   |
| Apacer              | 7        | 8      | 0.32%   |
| MidasForce          | 6        | 8      | 0.27%   |
| KingSpec            | 6        | 9      | 0.27%   |
| Mushkin             | 5        | 7      | 0.23%   |
| FORESEE             | 5        | 5      | 0.23%   |
| Verbatim            | 4        | 4      | 0.18%   |
| Team                | 4        | 5      | 0.18%   |
| T-FORCE             | 4        | 5      | 0.18%   |
| Silicon Motion      | 4        | 5      | 0.18%   |
| Netac               | 4        | 4      | 0.18%   |
| LITEON              | 4        | 5      | 0.18%   |
| KIOXIA-EXCERIA      | 4        | 10     | 0.18%   |
| Vaseky              | 3        | 3      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB        | 27       | 0.98%   |
| Samsung SSD 850 EVO 250GB       | 26       | 0.95%   |
| Seagate ST1000DM010-2EP102 1TB  | 25       | 0.91%   |
| Seagate ST2000DM008-2FR102 2TB  | 22       | 0.8%    |
| Kingston SA400S37240G 240GB     | 21       | 0.76%   |
| Kingston SA400S37480G 480GB     | 20       | 0.73%   |
| WDC WD40EFRX-68N32N0 4TB        | 18       | 0.66%   |
| WDC WD30EFRX-68EUZN0 3TB        | 18       | 0.66%   |
| Toshiba DT01ACA100 1TB          | 18       | 0.66%   |
| Kingston SA400S37120G 120GB     | 18       | 0.66%   |
| WDC WD800JD-75MSA3 80GB         | 16       | 0.58%   |
| Seagate ST4000DM004-2CV104 4TB  | 16       | 0.58%   |
| Samsung SSD 970 EVO Plus 1TB    | 16       | 0.58%   |
| Samsung SSD 870 EVO 1TB         | 16       | 0.58%   |
| Samsung SSD 860 EVO 1TB         | 16       | 0.58%   |
| Crucial CT240BX500SSD1 240GB    | 15       | 0.55%   |
| Samsung SSD 860 EVO 250GB       | 14       | 0.51%   |
| Samsung SSD 850 EVO 500GB       | 14       | 0.51%   |
| WDC WD20EFRX-68EUZN0 2TB        | 13       | 0.47%   |
| Seagate ST4000DM000-1F2168 4TB  | 13       | 0.47%   |
| Seagate ST500DM002-1BD142 500GB | 12       | 0.44%   |
| Seagate ST1000DM003-1ER162 1TB  | 12       | 0.44%   |
| Seagate ST1000DM003-1CH162 1TB  | 12       | 0.44%   |
| Samsung SSD 860 EVO 500GB       | 12       | 0.44%   |
| Crucial CT250MX500SSD1 250GB    | 12       | 0.44%   |
| Seagate ST3500418AS 500GB       | 11       | 0.4%    |
| Samsung SSD 870 EVO 500GB       | 11       | 0.4%    |
| Samsung SSD 970 EVO Plus 500GB  | 10       | 0.36%   |
| Samsung SSD 850 EVO 1TB         | 10       | 0.36%   |
| Kingston SV300S37A120G 120GB    | 10       | 0.36%   |
| Crucial CT1000MX500SSD1 1TB     | 10       | 0.36%   |
| WDC WD40EFRX-68WT0N0 4TB        | 9        | 0.33%   |
| WDC WD20EZRZ-00Z5HB0 2TB        | 9        | 0.33%   |
| WDC WD20EARX-00PASB0 2TB        | 9        | 0.33%   |
| Toshiba DT01ACA050 500GB        | 9        | 0.33%   |
| Seagate ST8000DM004-2CX188 8TB  | 9        | 0.33%   |
| Seagate ST4000VN008-2DR166 4TB  | 9        | 0.33%   |
| Seagate ST2000DM001-1CH164 2TB  | 9        | 0.33%   |
| Crucial CT500MX500SSD1 500GB    | 9        | 0.33%   |
| WDC WD10EFRX-68FYTN0 1TB        | 8        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor               | Desktops | Drives | Percent |
|----------------------|----------|--------|---------|
| WDC                  | 444      | 1549   | 38.81%  |
| Seagate              | 381      | 994    | 33.3%   |
| Toshiba              | 128      | 303    | 11.19%  |
| Hitachi              | 59       | 133    | 5.16%   |
| Samsung Electronics  | 50       | 81     | 4.37%   |
| HGST                 | 49       | 112    | 4.28%   |
| Maxtor               | 10       | 14     | 0.87%   |
| Hewlett-Packard      | 7        | 32     | 0.61%   |
| HPE                  | 3        | 9      | 0.26%   |
| Apple                | 3        | 4      | 0.26%   |
| HPT                  | 2        | 9      | 0.17%   |
| WD MediaMax          | 1        | 4      | 0.09%   |
| QUANTUM              | 1        | 2      | 0.09%   |
| MaxDigital           | 1        | 1      | 0.09%   |
| IBM/Hitachi          | 1        | 1      | 0.09%   |
| IBM                  | 1        | 1      | 0.09%   |
| Fujitsu              | 1        | 2      | 0.09%   |
| ExcelStor Technology | 1        | 4      | 0.09%   |
| Areca                | 1        | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 214      | 605    | 24.91%  |
| Kingston            | 109      | 146    | 12.69%  |
| Crucial             | 108      | 174    | 12.57%  |
| Intel               | 56       | 135    | 6.52%   |
| SanDisk             | 53       | 73     | 6.17%   |
| WDC                 | 50       | 91     | 5.82%   |
| A-DATA Technology   | 29       | 38     | 3.38%   |
| Transcend           | 15       | 21     | 1.75%   |
| OCZ                 | 14       | 17     | 1.63%   |
| SPCC                | 12       | 31     | 1.4%    |
| Micron Technology   | 12       | 25     | 1.4%    |
| Toshiba             | 9        | 9      | 1.05%   |
| SK hynix            | 9        | 16     | 1.05%   |
| Patriot             | 9        | 13     | 1.05%   |
| China               | 9        | 15     | 1.05%   |
| GOODRAM             | 8        | 21     | 0.93%   |
| Corsair             | 8        | 11     | 0.93%   |
| Seagate             | 7        | 11     | 0.81%   |
| PNY                 | 7        | 9      | 0.81%   |
| Plextor             | 7        | 10     | 0.81%   |
| Intenso             | 7        | 8      | 0.81%   |
| Apacer              | 7        | 8      | 0.81%   |
| MidasForce          | 6        | 8      | 0.7%    |
| KingSpec            | 6        | 9      | 0.7%    |
| Gigabyte Technology | 6        | 11     | 0.7%    |
| Verbatim            | 4        | 4      | 0.47%   |
| Team                | 4        | 5      | 0.47%   |
| Mushkin             | 4        | 5      | 0.47%   |
| LITEON              | 4        | 5      | 0.47%   |
| FORESEE             | 4        | 4      | 0.47%   |
| Vaseky              | 3        | 3      | 0.35%   |
| Hoodisk             | 3        | 5      | 0.35%   |
| Hewlett-Packard     | 3        | 5      | 0.35%   |
| Emtec               | 3        | 4      | 0.35%   |
| AMD                 | 3        | 4      | 0.35%   |
| walram              | 2        | 2      | 0.23%   |
| ViperTeq            | 2        | 2      | 0.23%   |
| T-FORCE             | 2        | 2      | 0.23%   |
| Smartbuy            | 2        | 2      | 0.23%   |
| SATADOM             | 2        | 3      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 844      | 3256   | 46.48%  |
| SSD  | 722      | 1626   | 39.76%  |
| NVMe | 250      | 474    | 13.77%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1162     | 4882   | 82.29%  |
| NVMe | 250      | 474    | 17.71%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 819      | 1727   | 44.66%  |
| 0.51-1.0   | 414      | 876    | 22.57%  |
| 1.01-2.0   | 225      | 691    | 12.27%  |
| 3.01-4.0   | 151      | 552    | 8.23%   |
| 4.01-10.0  | 120      | 666    | 6.54%   |
| 2.01-3.0   | 70       | 224    | 3.82%   |
| 10.01-20.0 | 34       | 145    | 1.85%   |
| 20.01-50.0 | 1        | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 368      | 26.14%  |
| 251-500        | 276      | 19.6%   |
| 501-1000       | 226      | 16.05%  |
| 51-100         | 152      | 10.8%   |
| 1001-2000      | 100      | 7.1%    |
| 21-50          | 97       | 6.89%   |
| 1-20           | 81       | 5.75%   |
| More than 3000 | 66       | 4.69%   |
| 2001-3000      | 25       | 1.78%   |
| Unknown        | 17       | 1.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 953      | 68.51%  |
| 21-50          | 184      | 13.23%  |
| 51-100         | 68       | 4.89%   |
| 101-250        | 51       | 3.67%   |
| 251-500        | 39       | 2.8%    |
| 501-1000       | 27       | 1.94%   |
| More than 3000 | 24       | 1.73%   |
| 1001-2000      | 17       | 1.22%   |
| Unknown        | 17       | 1.22%   |
| 2001-3000      | 9        | 0.65%   |
| 0              | 2        | 0.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 870 EVO 1TB | 7        | 9      | 1.85%   |
| WDC WD30EFRX-68EUZN0 3TB            | 6        | 18     | 1.58%   |
| Seagate ST3500413AS 500GB           | 6        | 9      | 1.58%   |
| WDC WD40EFRX-68WT0N0 4TB            | 5        | 11     | 1.32%   |
| WDC WD20EFRX-68EUZN0 2TB            | 5        | 12     | 1.32%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 4        | 4      | 1.06%   |
| Seagate ST2000DM001-9YN164 2TB      | 4        | 4      | 1.06%   |
| HGST HTS725050A7E630 500GB          | 4        | 13     | 1.06%   |
| WDC WD2000FYYZ-01UL1B2 2TB          | 3        | 9      | 0.79%   |
| Seagate ST3500418AS 500GB           | 3        | 6      | 0.79%   |
| Seagate ST1000DM003-1CH162 1TB      | 3        | 4      | 0.79%   |
| Samsung Electronics HD501LJ 500GB   | 3        | 4      | 0.79%   |
| Samsung Electronics HD154UI 1.5TB   | 3        | 4      | 0.79%   |
| Samsung Electronics HD103UJ 1TB     | 3        | 6      | 0.79%   |
| Kingston SV300S37A120G 120GB        | 3        | 3      | 0.79%   |
| Intel SSDSA2M080G2GC 80GB           | 3        | 3      | 0.79%   |
| Crucial CT525MX300SSD1 528GB        | 3        | 3      | 0.79%   |
| WDC WD5003AZEX-00MK2A0 500GB        | 2        | 2      | 0.53%   |
| WDC WD5000LPLX-22ZNTT0 500GB        | 2        | 2      | 0.53%   |
| WDC WD5000AAKX-08U6AA0 500GB        | 2        | 2      | 0.53%   |
| WDC WD5000AAKX-083CA0 500GB         | 2        | 2      | 0.53%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 2        | 2      | 0.53%   |
| WDC WD40EZRZ-00WN9B0 4TB            | 2        | 2      | 0.53%   |
| WDC WD40EFRX-68N32N0 4TB            | 2        | 5      | 0.53%   |
| WDC WD20EZRX-00D8PB0 2TB            | 2        | 3      | 0.53%   |
| WDC WD20EARX-00PASB0 2TB            | 2        | 2      | 0.53%   |
| WDC WD20EARS-00MVWB0 2TB            | 2        | 2      | 0.53%   |
| WDC WD2002FYPS-02W3B0 2TB           | 2        | 2      | 0.53%   |
| WDC WD2002FYPS-01U1B0 2TB           | 2        | 5      | 0.53%   |
| WDC WD2000FYYZ-01UL1B1 2TB          | 2        | 4      | 0.53%   |
| WDC WD15EADS-00P8B0 1.5TB           | 2        | 2      | 0.53%   |
| WDC WD10EZEX-75M2NA0 1TB            | 2        | 2      | 0.53%   |
| Toshiba MQ01ABD100 1TB              | 2        | 2      | 0.53%   |
| Toshiba MK5076GSXN 500GB            | 2        | 2      | 0.53%   |
| Toshiba MK3265GSX 320GB             | 2        | 2      | 0.53%   |
| Toshiba HDWE140 4TB                 | 2        | 11     | 0.53%   |
| Toshiba DT01ACA300 3TB              | 2        | 11     | 0.53%   |
| SK hynix SC308 SATA 128GB           | 2        | 9      | 0.53%   |
| Seagate ST9250827AS 250GB           | 2        | 3      | 0.53%   |
| Seagate ST500LT012-9WS142 500GB     | 2        | 2      | 0.53%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor               | Desktops | Drives | Percent |
|----------------------|----------|--------|---------|
| WDC                  | 104      | 197    | 29.38%  |
| Seagate              | 84       | 121    | 23.73%  |
| Samsung Electronics  | 40       | 57     | 11.3%   |
| Toshiba              | 22       | 48     | 6.21%   |
| Hitachi              | 17       | 26     | 4.8%    |
| Kingston             | 13       | 14     | 3.67%   |
| Intel                | 13       | 19     | 3.67%   |
| Crucial              | 12       | 19     | 3.39%   |
| HGST                 | 11       | 22     | 3.11%   |
| Maxtor               | 7        | 11     | 1.98%   |
| SanDisk              | 4        | 5      | 1.13%   |
| A-DATA Technology    | 4        | 5      | 1.13%   |
| SK hynix             | 3        | 10     | 0.85%   |
| SPCC                 | 2        | 2      | 0.56%   |
| OCZ                  | 2        | 3      | 0.56%   |
| Micron Technology    | 2        | 6      | 0.56%   |
| LITEON               | 2        | 3      | 0.56%   |
| Hewlett-Packard      | 2        | 4      | 0.56%   |
| Corsair              | 2        | 4      | 0.56%   |
| walram               | 1        | 1      | 0.28%   |
| TEXTORM              | 1        | 1      | 0.28%   |
| Plextor              | 1        | 1      | 0.28%   |
| Leven                | 1        | 1      | 0.28%   |
| HPE                  | 1        | 4      | 0.28%   |
| GK                   | 1        | 1      | 0.28%   |
| ExcelStor Technology | 1        | 2      | 0.28%   |
| AMD                  | 1        | 2      | 0.28%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Desktops | Drives | Percent |
|----------------------|----------|--------|---------|
| WDC                  | 103      | 196    | 38.01%  |
| Seagate              | 83       | 120    | 30.63%  |
| Samsung Electronics  | 24       | 35     | 8.86%   |
| Toshiba              | 22       | 48     | 8.12%   |
| Hitachi              | 17       | 26     | 6.27%   |
| HGST                 | 11       | 22     | 4.06%   |
| Maxtor               | 7        | 11     | 2.58%   |
| Hewlett-Packard      | 2        | 4      | 0.74%   |
| HPE                  | 1        | 4      | 0.37%   |
| ExcelStor Technology | 1        | 2      | 0.37%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 248      | 468    | 75.38%  |
| SSD  | 80       | 120    | 24.32%  |
| NVMe | 1        | 1      | 0.3%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                        | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB     | 1        | 1      | 25%     |
| Toshiba MG05ACA800E 8TB      | 1        | 1      | 25%     |
| Maxtor 6E040L0 40GB          | 1        | 1      | 25%     |
| Crucial M4-CT256M4SSD1 256GB | 1        | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 25%     |
| Toshiba | 1        | 1      | 25%     |
| Maxtor  | 1        | 1      | 25%     |
| Crucial | 1        | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 1129     | 4658   | 75.98%  |
| Malfunc  | 310      | 589    | 20.86%  |
| Detected | 43       | 105    | 2.89%   |
| Failed   | 4        | 4      | 0.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 820      | 41.88%  |
| AMD                              | 413      | 21.09%  |
| Samsung Electronics              | 142      | 7.25%   |
| ASMedia Technology               | 82       | 4.19%   |
| Broadcom / LSI                   | 62       | 3.17%   |
| Marvell Technology Group         | 60       | 3.06%   |
| SanDisk                          | 59       | 3.01%   |
| Phison Electronics               | 41       | 2.09%   |
| Kingston Technology Company      | 31       | 1.58%   |
| Silicon Motion                   | 30       | 1.53%   |
| JMicron Technology               | 30       | 1.53%   |
| Micron/Crucial Technology        | 29       | 1.48%   |
| Nvidia                           | 21       | 1.07%   |
| SK hynix                         | 14       | 0.72%   |
| Realtek Semiconductor            | 11       | 0.56%   |
| ADATA Technology                 | 11       | 0.56%   |
| Adaptec                          | 10       | 0.51%   |
| Silicon Image                    | 9        | 0.46%   |
| VIA Technologies                 | 8        | 0.41%   |
| MAXIO Technology (Hangzhou)      | 8        | 0.41%   |
| Micron Technology                | 7        | 0.36%   |
| Areca Technology                 | 6        | 0.31%   |
| Seagate Technology               | 5        | 0.26%   |
| KIOXIA                           | 5        | 0.26%   |
| Chelsio Communications           | 5        | 0.26%   |
| Toshiba                          | 4        | 0.2%    |
| Hewlett-Packard                  | 4        | 0.2%    |
| Silicon Integrated Systems [SiS] | 3        | 0.15%   |
| Shenzhen Longsys Electronics     | 3        | 0.15%   |
| Lite-On Technology               | 3        | 0.15%   |
| Integrated Technology Express    | 3        | 0.15%   |
| 3ware                            | 3        | 0.15%   |
| Promise Technology               | 2        | 0.1%    |
| Hosin Global Electronics         | 2        | 0.1%    |
| HighPoint Technologies           | 2        | 0.1%    |
| ULi Electronics                  | 1        | 0.05%   |
| Transcend                        | 1        | 0.05%   |
| TenaFe                           | 1        | 0.05%   |
| O2 Micro                         | 1        | 0.05%   |
| Netac Technology                 | 1        | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 219      | 9.29%   |
| AMD 400 Series Chipset SATA Controller                                         | 82       | 3.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 78       | 3.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 74       | 3.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 72       | 3.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 67       | 2.84%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 67       | 2.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 66       | 2.8%    |
| AMD 500 Series Chipset SATA Controller                                         | 55       | 2.33%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 47       | 1.99%   |
| Intel SATA Controller [RAID mode]                                              | 46       | 1.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 41       | 1.74%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 41       | 1.74%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 39       | 1.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 32       | 1.36%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 29       | 1.23%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 28       | 1.19%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 27       | 1.15%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 27       | 1.15%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 25       | 1.06%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 24       | 1.02%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 23       | 0.98%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 23       | 0.98%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 21       | 0.89%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 21       | 0.89%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 20       | 0.85%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 20       | 0.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 20       | 0.85%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 19       | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                          | 19       | 0.81%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 19       | 0.81%   |
| AMD 600 Series Chipset SATA Controller                                         | 19       | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 18       | 0.76%   |
| Phison E12 NVMe Controller                                                     | 16       | 0.68%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 15       | 0.64%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 15       | 0.64%   |
| AMD X370 Series Chipset SATA Controller                                        | 15       | 0.64%   |
| AMD 300 Series Chipset SATA Controller                                         | 15       | 0.64%   |
| JMicron JMB363 SATA/IDE Controller                                             | 14       | 0.59%   |
| Intel SSD 660P Series                                                          | 14       | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1072     | 56.9%   |
| NVMe | 391      | 20.75%  |
| IDE  | 241      | 12.79%  |
| RAID | 94       | 4.99%   |
| SAS  | 60       | 3.18%   |
| SCSI | 26       | 1.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Intel    | 832      | 62.46%  |
| AMD      | 435      | 32.66%  |
| ARM      | 45       | 3.38%   |
| Unknown  | 9        | 0.68%   |
| IBM      | 3        | 0.23%   |
| VIA      | 2        | 0.15%   |
| i        | 2        | 0.15%   |
| Sun      | 1        | 0.08%   |
| Research | 1        | 0.08%   |
| NXP      | 1        | 0.08%   |
| Motorola | 1        | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 5600G with Radeon Graphics      | 21       | 1.56%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 18       | 1.34%   |
| ARM Cortex-A55 r2p0                         | 15       | 1.12%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 14       | 1.04%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 14       | 1.04%   |
| AMD GX-412TC SOC                            | 14       | 1.04%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 13       | 0.97%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 13       | 0.97%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 12       | 0.89%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 11       | 0.82%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 11       | 0.82%   |
| ARM Cortex-A53 r0p4                         | 11       | 0.82%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 11       | 0.82%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 11       | 0.82%   |
| AMD FX-8350 Eight-Core Processor            | 11       | 0.82%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 10       | 0.74%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 10       | 0.74%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 10       | 0.74%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 10       | 0.74%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 9        | 0.67%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 9        | 0.67%   |
| AMD Ryzen 5 3600 6-Core Processor           | 9        | 0.67%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 9        | 0.67%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 9        | 0.67%   |
|                                             | 9        | 0.67%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 8        | 0.6%    |
| Intel Core i5-2500 CPU @ 3.30GHz            | 8        | 0.6%    |
| Intel Core i7-10700 CPU @ 2.90GHz           | 7        | 0.52%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 7        | 0.52%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 7        | 0.52%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 7        | 0.52%   |
| Intel Celeron CPU N3150 @ 1.60GHz           | 7        | 0.52%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 7        | 0.52%   |
| AMD FX-6300 Six-Core Processor              | 7        | 0.52%   |
| AMD Athlon 3000G with Radeon Vega Graphics  | 7        | 0.52%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 6        | 0.45%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 6        | 0.45%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 6        | 0.45%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 6        | 0.45%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 6        | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 177      | 13.23%  |
| Intel Core i7           | 160      | 11.96%  |
| Intel Xeon              | 136      | 10.16%  |
| AMD Ryzen 5             | 90       | 6.73%   |
| AMD Ryzen 7             | 84       | 6.28%   |
| Other                   | 78       | 5.83%   |
| Intel Core i3           | 73       | 5.46%   |
| Intel Celeron           | 66       | 4.93%   |
| AMD Ryzen 9             | 60       | 4.48%   |
| Intel Atom              | 39       | 2.91%   |
| ARM Cortex              | 39       | 2.91%   |
| AMD FX                  | 38       | 2.84%   |
| Intel Pentium           | 33       | 2.47%   |
| Intel Core 2 Duo        | 30       | 2.24%   |
| AMD GX                  | 25       | 1.87%   |
| AMD Ryzen 3             | 23       | 1.72%   |
| Intel Core 2 Quad       | 19       | 1.42%   |
| Intel Pentium 4         | 13       | 0.97%   |
| Intel Core i9           | 11       | 0.82%   |
| AMD Ryzen Threadripper  | 11       | 0.82%   |
| AMD Athlon 64 X2        | 9        | 0.67%   |
| AMD Athlon              | 9        | 0.67%   |
| AMD Turion II Neo       | 8        | 0.6%    |
| AMD Phenom II X6        | 7        | 0.52%   |
| AMD Phenom II X4        | 7        | 0.52%   |
| AMD A10                 | 7        | 0.52%   |
| AMD Ryzen 5 PRO         | 6        | 0.45%   |
| AMD Phenom              | 6        | 0.45%   |
| Intel Pentium Silver    | 5        | 0.37%   |
| Intel Pentium Gold      | 5        | 0.37%   |
| Intel Core 2            | 5        | 0.37%   |
| AMD Ryzen 7 PRO         | 5        | 0.37%   |
| AMD G                   | 5        | 0.37%   |
| Intel Pentium Dual-Core | 4        | 0.3%    |
| AMD Athlon II X2        | 4        | 0.3%    |
| AMD Sempron             | 3        | 0.22%   |
| AMD Opteron             | 3        | 0.22%   |
| AMD EPYC                | 3        | 0.22%   |
| AMD A4                  | 3        | 0.22%   |
| Intel Xeon Bronze       | 2        | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 460      | 34.25%  |
| 2       | 214      | 15.93%  |
| 8       | 121      | 9.01%   |
| 6       | 117      | 8.71%   |
| Unknown | 113      | 8.41%   |
| 16      | 101      | 7.52%   |
| 12      | 88       | 6.55%   |
| 24      | 34       | 2.53%   |
| 32      | 30       | 2.23%   |
| 1       | 25       | 1.86%   |
| 10      | 16       | 1.19%   |
| 14      | 7        | 0.52%   |
| 64      | 4        | 0.3%    |
| 28      | 3        | 0.22%   |
| 20      | 3        | 0.22%   |
| 3       | 2        | 0.15%   |
| 48      | 1        | 0.07%   |
| 36      | 1        | 0.07%   |
| 22      | 1        | 0.07%   |
| 18      | 1        | 0.07%   |
| 11      | 1        | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1243     | 93.32%  |
| Unknown | 56       | 4.2%    |
| 2       | 32       | 2.4%    |
| 4       | 1        | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 761      | 57.05%  |
| 2       | 446      | 33.43%  |
| Unknown | 127      | 9.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Unknown       | 143      | 10.68%  |
| Haswell       | 125      | 9.34%   |
| KabyLake      | 115      | 8.59%   |
| IvyBridge     | 102      | 7.62%   |
| Zen 2         | 85       | 6.35%   |
| Zen 3         | 81       | 6.05%   |
| SandyBridge   | 81       | 6.05%   |
| Skylake       | 67       | 5%      |
| Zen+          | 56       | 4.18%   |
| Penryn        | 51       | 3.81%   |
| Zen           | 45       | 3.36%   |
| CometLake     | 44       | 3.29%   |
| K10           | 40       | 2.99%   |
| Silvermont    | 38       | 2.84%   |
| Piledriver    | 36       | 2.69%   |
| Westmere      | 28       | 2.09%   |
| Core          | 23       | 1.72%   |
| Bonnell       | 23       | 1.72%   |
| Puma          | 19       | 1.42%   |
| NetBurst      | 19       | 1.42%   |
| Broadwell     | 19       | 1.42%   |
| Nehalem       | 17       | 1.27%   |
| Goldmont      | 13       | 0.97%   |
| K8 Hammer     | 12       | 0.9%    |
| Jaguar        | 12       | 0.9%    |
| Goldmont plus | 10       | 0.75%   |
| Bulldozer     | 9        | 0.67%   |
| Bobcat        | 8        | 0.6%    |
| Excavator     | 5        | 0.37%   |
| P6            | 4        | 0.3%    |
| Steamroller   | 3        | 0.22%   |
| TigerLake     | 2        | 0.15%   |
| Geode         | 2        | 0.15%   |
| K10 Llano     | 1        | 0.07%   |
| IceLake       | 1        | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 468      | 35.4%   |
| Nvidia                                       | 397      | 30.03%  |
| AMD                                          | 368      | 27.84%  |
| ASPEED Technology                            | 42       | 3.18%   |
| Matrox Electronics Systems                   | 36       | 2.72%   |
| XGI Technology (eXtreme Graphics Innovation) | 4        | 0.3%    |
| VIA Technologies                             | 3        | 0.23%   |
| S3 Graphics                                  | 2        | 0.15%   |
| Silicon Integrated Systems [SiS]             | 1        | 0.08%   |
| NVidia / SGS Thomson (Joint Venture)         | 1        | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 58       | 4.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 51       | 3.76%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 42       | 3.09%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 37       | 2.72%   |
| Intel HD Graphics 530                                                                    | 34       | 2.5%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 34       | 2.5%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 33       | 2.43%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 33       | 2.43%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 29       | 2.14%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 29       | 2.14%   |
| Intel HD Graphics 630                                                                    | 27       | 1.99%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 26       | 1.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 22       | 1.62%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 18       | 1.33%   |
| Matrox Electronics Systems MGA G200EH                                                    | 17       | 1.25%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 17       | 1.25%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 16       | 1.18%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 16       | 1.18%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 14       | 1.03%   |
| AMD Raphael                                                                              | 13       | 0.96%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 13       | 0.96%   |
| Nvidia GT218 [GeForce 210]                                                               | 12       | 0.88%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 12       | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11       | 0.81%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 11       | 0.81%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 11       | 0.81%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 10       | 0.74%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 10       | 0.74%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 10       | 0.74%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 10       | 0.74%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 9        | 0.66%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 9        | 0.66%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 9        | 0.66%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 9        | 0.66%   |
| AMD RV730 XT [Radeon HD 4670]                                                            | 9        | 0.66%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 8        | 0.59%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 8        | 0.59%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 8        | 0.59%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 8        | 0.59%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 8        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| 1 x Intel                                | 402      | 29.96%  |
| 1 x Nvidia                               | 344      | 25.63%  |
| 1 x AMD                                  | 324      | 24.14%  |
| Other                                    | 84       | 6.26%   |
| 1 x ASPEED                               | 37       | 2.76%   |
| 1 x Matrox                               | 36       | 2.68%   |
| Intel + Nvidia                           | 34       | 2.53%   |
| 2 x AMD                                  | 21       | 1.56%   |
| 2 x Intel                                | 16       | 1.19%   |
| Intel + AMD                              | 14       | 1.04%   |
| AMD + Nvidia                             | 8        | 0.6%    |
| Nvidia + ASPEED                          | 5        | 0.37%   |
| 2 x Nvidia                               | 4        | 0.3%    |
| 1 x XGI                                  | 4        | 0.3%    |
| 1 x VIA                                  | 3        | 0.22%   |
| 1 x S3 Graphics                          | 2        | 0.15%   |
| 1 x SiS                                  | 1        | 0.07%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1        | 0.07%   |
| Intel + ASPEED                           | 1        | 0.07%   |
| AMD + ASPEED                             | 1        | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 941      | 70.49%  |
| Proprietary | 303      | 22.7%   |
| Unknown     | 91       | 6.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 848      | 62.35%  |
| 1.01-2.0   | 123      | 9.04%   |
| 7.01-8.0   | 101      | 7.43%   |
| 3.01-4.0   | 83       | 6.1%    |
| 0.51-1.0   | 71       | 5.22%   |
| 0.01-0.5   | 55       | 4.04%   |
| 5.01-6.0   | 34       | 2.5%    |
| 8.01-16.0  | 28       | 2.06%   |
| 2.01-3.0   | 10       | 0.74%   |
| 16.01-24.0 | 5        | 0.37%   |
| 4.01-5.0   | 2        | 0.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 120      | 16.35%  |
| Dell                 | 111      | 15.12%  |
| Goldstar             | 69       | 9.4%    |
| Acer                 | 43       | 5.86%   |
| Hewlett-Packard      | 40       | 5.45%   |
| AOC                  | 36       | 4.9%    |
| BenQ                 | 31       | 4.22%   |
| Philips              | 30       | 4.09%   |
| Ancor Communications | 27       | 3.68%   |
| ViewSonic            | 24       | 3.27%   |
| Iiyama               | 24       | 3.27%   |
| LG Electronics       | 21       | 2.86%   |
| Lenovo               | 16       | 2.18%   |
| Sony                 | 14       | 1.91%   |
| NEC Computers        | 9        | 1.23%   |
| MSI                  | 9        | 1.23%   |
| Eizo                 | 9        | 1.23%   |
| Idek Iiyama          | 8        | 1.09%   |
| ASUSTek Computer     | 8        | 1.09%   |
| Unknown              | 6        | 0.82%   |
| RTK                  | 5        | 0.68%   |
| Sceptre Tech         | 4        | 0.54%   |
| Unknown              | 4        | 0.54%   |
| Toshiba              | 3        | 0.41%   |
| Mi                   | 3        | 0.41%   |
| Gigabyte Technology  | 3        | 0.41%   |
| Plain Tree Systems   | 2        | 0.27%   |
| Panasonic            | 2        | 0.27%   |
| Microstep            | 2        | 0.27%   |
| IOD                  | 2        | 0.27%   |
| Insignia             | 2        | 0.27%   |
| IBM                  | 2        | 0.27%   |
| HPN                  | 2        | 0.27%   |
| Gateway              | 2        | 0.27%   |
| Fujitsu Siemens      | 2        | 0.27%   |
| Apple                | 2        | 0.27%   |
| Wacom                | 1        | 0.14%   |
| VMO                  | 1        | 0.14%   |
| VKK                  | 1        | 0.14%   |
| Vizio                | 1        | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| MSI G241 MSI3BA4 1920x1080 530x300mm 24.0-inch                       | 6        | 0.74%   |
| Iiyama PL2775HD IVM6604 1920x1080 600x340mm 27.2-inch                | 6        | 0.74%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 5        | 0.62%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                    | 5        | 0.62%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch    | 4        | 0.5%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 4        | 0.5%    |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                | 4        | 0.5%    |
| Unknown                                                              | 4        | 0.5%    |
| ViewSonic VA2342 SERIES VSCFA2B 1920x1080 510x290mm 23.1-inch        | 3        | 0.37%   |
| Samsung Electronics SyncMaster SAM00A4 1024x768 300x230mm 14.9-inch  | 3        | 0.37%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch    | 3        | 0.37%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch    | 3        | 0.37%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch    | 3        | 0.37%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch              | 3        | 0.37%   |
| LG Electronics LCD Monitor LG Ultra HD                               | 3        | 0.37%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 3        | 0.37%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch         | 3        | 0.37%   |
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch             | 3        | 0.37%   |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch             | 3        | 0.37%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 3        | 0.37%   |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                | 3        | 0.37%   |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch                    | 3        | 0.37%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                    | 3        | 0.37%   |
| Dell LCD Monitor U2412M                                              | 3        | 0.37%   |
| AOC Q27P1B AOC2701 2560x1440 600x340mm 27.2-inch                     | 3        | 0.37%   |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                    | 3        | 0.37%   |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch | 3        | 0.37%   |
| ViewSonic VX2457 VSCB931 1920x1080 520x290mm 23.4-inch               | 2        | 0.25%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch        | 2        | 0.25%   |
| unknown LCD Monitor SAMSUNG 1920x1080                                | 2        | 0.25%   |
| Sony TV SNY4B03 1920x1080 930x520mm 41.9-inch                        | 2        | 0.25%   |
| Sony LCD Monitor TV XV 1920x1080                                     | 2        | 0.25%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 700x390mm 31.5-inch    | 2        | 0.25%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch | 2        | 0.25%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 380x300mm 19.1-inch | 2        | 0.25%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 380x300mm 19.1-inch  | 2        | 0.25%   |
| Samsung Electronics S27C750 SAM0A60 1920x1080 600x340mm 27.2-inch    | 2        | 0.25%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 530x300mm 24.0-inch    | 2        | 0.25%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch    | 2        | 0.25%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                 | 2        | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 324      | 44.51%  |
| 3840x2160 (4K)     | 77       | 10.58%  |
| 2560x1440 (QHD)    | 66       | 9.07%   |
| 1920x1200 (WUXGA)  | 51       | 7.01%   |
| 1280x1024 (SXGA)   | 41       | 5.63%   |
| 1680x1050 (WSXGA+) | 24       | 3.3%    |
| Unknown            | 24       | 3.3%    |
| 1600x900 (HD+)     | 15       | 2.06%   |
| 1366x768 (WXGA)    | 15       | 2.06%   |
| 3440x1440          | 13       | 1.79%   |
| 2560x1080          | 12       | 1.65%   |
| 1440x900 (WXGA+)   | 12       | 1.65%   |
| 1600x1200          | 9        | 1.24%   |
| 3840x1080          | 7        | 0.96%   |
| 1024x768 (XGA)     | 6        | 0.82%   |
| 2560x1600          | 3        | 0.41%   |
| 1360x768           | 3        | 0.41%   |
| 3840x1600          | 2        | 0.27%   |
| 3840x1200          | 2        | 0.27%   |
| 1920x540           | 2        | 0.27%   |
| 1280x720 (HD)      | 2        | 0.27%   |
| 8960x1440          | 1        | 0.14%   |
| 7860x2400          | 1        | 0.14%   |
| 7680x2160          | 1        | 0.14%   |
| 5760x1256          | 1        | 0.14%   |
| 5760x1200          | 1        | 0.14%   |
| 5760x1080          | 1        | 0.14%   |
| 5120x1440          | 1        | 0.14%   |
| 3640x1920          | 1        | 0.14%   |
| 3600x1080          | 1        | 0.14%   |
| 3520x1200          | 1        | 0.14%   |
| 3360x1050          | 1        | 0.14%   |
| 2648x1024          | 1        | 0.14%   |
| 2560x2520          | 1        | 0.14%   |
| 2390x1280          | 1        | 0.14%   |
| 2288x1430          | 1        | 0.14%   |
| 2048x1152          | 1        | 0.14%   |
| 11520x2160         | 1        | 0.14%   |
| 1024x600           | 1        | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 129      | 17.5%   |
| 27      | 120      | 16.28%  |
| 24      | 115      | 15.6%   |
| 21      | 77       | 10.45%  |
| 23      | 71       | 9.63%   |
| 19      | 38       | 5.16%   |
| 31      | 32       | 4.34%   |
| 22      | 20       | 2.71%   |
| 17      | 19       | 2.58%   |
| 18      | 16       | 2.17%   |
| 34      | 11       | 1.49%   |
| 15      | 10       | 1.36%   |
| 20      | 8        | 1.09%   |
| 14      | 8        | 1.09%   |
| 32      | 6        | 0.81%   |
| 29      | 5        | 0.68%   |
| 25      | 5        | 0.68%   |
| 52      | 4        | 0.54%   |
| 46      | 4        | 0.54%   |
| 42      | 4        | 0.54%   |
| 54      | 3        | 0.41%   |
| 40      | 3        | 0.41%   |
| 28      | 3        | 0.41%   |
| 26      | 3        | 0.41%   |
| 13      | 3        | 0.41%   |
| 41      | 2        | 0.27%   |
| 16      | 2        | 0.27%   |
| 74      | 1        | 0.14%   |
| 64      | 1        | 0.14%   |
| 57      | 1        | 0.14%   |
| 55      | 1        | 0.14%   |
| 50      | 1        | 0.14%   |
| 49      | 1        | 0.14%   |
| 48      | 1        | 0.14%   |
| 47      | 1        | 0.14%   |
| 43      | 1        | 0.14%   |
| 39      | 1        | 0.14%   |
| 37      | 1        | 0.14%   |
| 36      | 1        | 0.14%   |
| 35      | 1        | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 287      | 40.2%   |
| 401-500     | 139      | 19.47%  |
| Unknown     | 129      | 18.07%  |
| 601-700     | 49       | 6.86%   |
| 301-350     | 33       | 4.62%   |
| 701-800     | 19       | 2.66%   |
| 1001-1500   | 17       | 2.38%   |
| 351-400     | 15       | 2.1%    |
| 201-300     | 10       | 1.4%    |
| 901-1000    | 9        | 1.26%   |
| 801-900     | 5        | 0.7%    |
| 1501-2000   | 1        | 0.14%   |
| 101-200     | 1        | 0.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 421      | 61.28%  |
| Unknown | 117      | 17.03%  |
| 16/10   | 70       | 10.19%  |
| 5/4     | 31       | 4.51%   |
| 21/9    | 18       | 2.62%   |
| 4/3     | 17       | 2.47%   |
| 3/2     | 8        | 1.16%   |
| 6/5     | 3        | 0.44%   |
| 32/9    | 2        | 0.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 222      | 30.71%  |
| Unknown        | 129      | 17.84%  |
| 301-350        | 124      | 17.15%  |
| 351-500        | 55       | 7.61%   |
| 151-200        | 54       | 7.47%   |
| 251-300        | 50       | 6.92%   |
| 141-150        | 32       | 4.43%   |
| 501-1000       | 19       | 2.63%   |
| More than 1000 | 13       | 1.8%    |
| 101-110        | 10       | 1.38%   |
| 111-120        | 5        | 0.69%   |
| 81-90          | 4        | 0.55%   |
| 121-130        | 3        | 0.41%   |
| 71-80          | 1        | 0.14%   |
| 51-60          | 1        | 0.14%   |
| 1-40           | 1        | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 364      | 51.34%  |
| Unknown | 129      | 18.19%  |
| 101-120 | 128      | 18.05%  |
| 121-160 | 46       | 6.49%   |
| 161-240 | 30       | 4.23%   |
| 1-50    | 12       | 1.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 676      | 49.74%  |
| 1     | 572      | 42.09%  |
| 2     | 97       | 7.14%   |
| 3     | 13       | 0.96%   |
| 4     | 1        | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 705      | 40.38%  |
| Realtek Semiconductor             | 640      | 36.66%  |
| Qualcomm Atheros                  | 97       | 5.56%   |
| Broadcom                          | 81       | 4.64%   |
| MediaTek                          | 21       | 1.2%    |
| Mellanox Technologies             | 14       | 0.8%    |
| TP-Link                           | 13       | 0.74%   |
| Ralink Technology                 | 13       | 0.74%   |
| Marvell Technology Group          | 13       | 0.74%   |
| Aquantia                          | 12       | 0.69%   |
| Ralink                            | 11       | 0.63%   |
| Samsung Electronics               | 10       | 0.57%   |
| VIA Technologies                  | 9        | 0.52%   |
| American Megatrends               | 8        | 0.46%   |
| D-Link System                     | 7        | 0.4%    |
| Chelsio Communications            | 5        | 0.29%   |
| ASUSTek Computer                  | 5        | 0.29%   |
| 3Com                              | 5        | 0.29%   |
| Xiaomi                            | 4        | 0.23%   |
| Nvidia                            | 4        | 0.23%   |
| Apple                             | 4        | 0.23%   |
| QinHeng Electronics               | 3        | 0.17%   |
| OPPO Electronics                  | 3        | 0.17%   |
| IMC Networks                      | 3        | 0.17%   |
| Edimax Technology                 | 3        | 0.17%   |
| Dresden Elektronik                | 3        | 0.17%   |
| Arduino SA                        | 3        | 0.17%   |
| Accton Technology                 | 3        | 0.17%   |
| Sundance Technology Inc / IC Plus | 2        | 0.11%   |
| Qualcomm Atheros Communications   | 2        | 0.11%   |
| Qualcomm                          | 2        | 0.11%   |
| Microchip Technology              | 2        | 0.11%   |
| Micro Star International          | 2        | 0.11%   |
| LG Electronics                    | 2        | 0.11%   |
| Huawei Technologies               | 2        | 0.11%   |
| Emulex                            | 2        | 0.11%   |
| D-Link                            | 2        | 0.11%   |
| Atmel                             | 2        | 0.11%   |
| ADMtek                            | 2        | 0.11%   |
| U.S. Robotics                     | 1        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 496      | 24.22%  |
| Intel I211 Gigabit Network Connection                                         | 116      | 5.66%   |
| Realtek RTL8125 2.5GbE Controller                                             | 75       | 3.66%   |
| Intel 82574L Gigabit Network Connection                                       | 64       | 3.13%   |
| Intel Wi-Fi 6 AX200                                                           | 51       | 2.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 51       | 2.49%   |
| Intel I210 Gigabit Network Connection                                         | 47       | 2.29%   |
| Intel Ethernet Controller I225-V                                              | 42       | 2.05%   |
| Intel Ethernet Connection I217-LM                                             | 34       | 1.66%   |
| Intel Ethernet Connection (2) I219-V                                          | 32       | 1.56%   |
| Intel 82579V Gigabit Network Connection                                       | 32       | 1.56%   |
| Intel Ethernet Connection (2) I219-LM                                         | 29       | 1.42%   |
| Intel I350 Gigabit Network Connection                                         | 21       | 1.03%   |
| Intel Ethernet Connection (7) I219-V                                          | 19       | 0.93%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 18       | 0.88%   |
| Intel Ethernet Connection (2) I218-V                                          | 17       | 0.83%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 16       | 0.78%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 16       | 0.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 14       | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 14       | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 14       | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 14       | 0.68%   |
| Intel Ethernet Controller I226-V                                              | 13       | 0.63%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 12       | 0.59%   |
| Intel Ethernet Connection I217-V                                              | 12       | 0.59%   |
| Intel Wireless 7265                                                           | 11       | 0.54%   |
| Intel Ethernet Controller X550                                                | 11       | 0.54%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 11       | 0.54%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 11       | 0.54%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 10       | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                                         | 10       | 0.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 10       | 0.49%   |
| Intel 82580 Gigabit Network Connection                                        | 10       | 0.49%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 10       | 0.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 9        | 0.44%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 9        | 0.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 9        | 0.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 9        | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 9        | 0.44%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 9        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 165      | 40.64%  |
| Realtek Semiconductor                 | 81       | 19.95%  |
| Qualcomm Atheros                      | 64       | 15.76%  |
| MediaTek                              | 20       | 4.93%   |
| Broadcom                              | 17       | 4.19%   |
| TP-Link                               | 13       | 3.2%    |
| Ralink Technology                     | 13       | 3.2%    |
| Ralink                                | 11       | 2.71%   |
| ASUSTek Computer                      | 5        | 1.23%   |
| IMC Networks                          | 3        | 0.74%   |
| Edimax Technology                     | 3        | 0.74%   |
| Qualcomm Atheros Communications       | 2        | 0.49%   |
| Micro Star International              | 2        | 0.49%   |
| D-Link                                | 2        | 0.49%   |
| Qualcomm Technologies                 | 1        | 0.25%   |
| Linksys                               | 1        | 0.25%   |
| Atheros                               | 1        | 0.25%   |
| AboCom Systems                        | 1        | 0.25%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 51       | 12.38%  |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                                       | 16       | 3.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 14       | 3.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 14       | 3.4%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                                     | 12       | 2.91%   |
| Intel Wireless 7265                                                                           | 11       | 2.67%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 10       | 2.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 10       | 2.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 9        | 2.18%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 9        | 2.18%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 9        | 2.18%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 9        | 2.18%   |
| Intel Wireless 8260                                                                           | 9        | 2.18%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 8        | 1.94%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                                  | 8        | 1.94%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                                                  | 7        | 1.7%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 7        | 1.7%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 6        | 1.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 6        | 1.46%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 5        | 1.21%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 5        | 1.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 5        | 1.21%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 5        | 1.21%   |
| Intel Wireless 8265 / 8275                                                                    | 5        | 1.21%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 5        | 1.21%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                   | 4        | 0.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 4        | 0.97%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 4        | 0.97%   |
| Intel Wireless 7260                                                                           | 4        | 0.97%   |
| Intel Wireless 3160                                                                           | 4        | 0.97%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                                             | 4        | 0.97%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 4        | 0.97%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 0.73%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 3        | 0.73%   |
| Ralink RT5572 Wireless Adapter                                                                | 3        | 0.73%   |
| Ralink RT5370 Wireless Adapter                                                                | 3        | 0.73%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 3        | 0.73%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 3        | 0.73%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter                               | 3        | 0.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 3        | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 642      | 44.25%  |
| Realtek Semiconductor             | 604      | 41.63%  |
| Broadcom                          | 65       | 4.48%   |
| Qualcomm Atheros                  | 36       | 2.48%   |
| Marvell Technology Group          | 13       | 0.9%    |
| Aquantia                          | 12       | 0.83%   |
| Samsung Electronics               | 10       | 0.69%   |
| VIA Technologies                  | 9        | 0.62%   |
| American Megatrends               | 8        | 0.55%   |
| D-Link System                     | 7        | 0.48%   |
| Chelsio Communications            | 5        | 0.34%   |
| 3Com                              | 5        | 0.34%   |
| Xiaomi                            | 4        | 0.28%   |
| Nvidia                            | 4        | 0.28%   |
| OPPO Electronics                  | 3        | 0.21%   |
| Apple                             | 3        | 0.21%   |
| Sundance Technology Inc / IC Plus | 2        | 0.14%   |
| Qualcomm                          | 2        | 0.14%   |
| Emulex                            | 2        | 0.14%   |
| ADMtek                            | 2        | 0.14%   |
| Accton Technology                 | 2        | 0.14%   |
| U.S. Robotics                     | 1        | 0.07%   |
| Tehuti Networks                   | 1        | 0.07%   |
| Solarflare Communications         | 1        | 0.07%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.07%   |
| OnePlus Technology (Shenzhen)     | 1        | 0.07%   |
| National Semiconductor            | 1        | 0.07%   |
| MYRICOM                           | 1        | 0.07%   |
| Motorola PCS                      | 1        | 0.07%   |
| MediaTek                          | 1        | 0.07%   |
| Huawei Technologies               | 1        | 0.07%   |
| Davicom Semiconductor             | 1        | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 496      | 31.23%  |
| Intel I211 Gigabit Network Connection                                         | 116      | 7.3%    |
| Realtek RTL8125 2.5GbE Controller                                             | 72       | 4.53%   |
| Intel 82574L Gigabit Network Connection                                       | 64       | 4.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 51       | 3.21%   |
| Intel I210 Gigabit Network Connection                                         | 47       | 2.96%   |
| Intel Ethernet Controller I225-V                                              | 42       | 2.64%   |
| Intel Ethernet Connection I217-LM                                             | 34       | 2.14%   |
| Intel Ethernet Connection (2) I219-V                                          | 32       | 2.02%   |
| Intel 82579V Gigabit Network Connection                                       | 32       | 2.02%   |
| Intel Ethernet Connection (2) I219-LM                                         | 29       | 1.83%   |
| Intel I350 Gigabit Network Connection                                         | 21       | 1.32%   |
| Intel Ethernet Connection (7) I219-V                                          | 19       | 1.2%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 18       | 1.13%   |
| Intel Ethernet Connection (2) I218-V                                          | 17       | 1.07%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 16       | 1.01%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 14       | 0.88%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 14       | 0.88%   |
| Intel Ethernet Controller I226-V                                              | 13       | 0.82%   |
| Intel Ethernet Connection I217-V                                              | 12       | 0.76%   |
| Intel Ethernet Controller X550                                                | 11       | 0.69%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 11       | 0.69%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 11       | 0.69%   |
| Intel Ethernet Connection (7) I219-LM                                         | 10       | 0.63%   |
| Intel 82580 Gigabit Network Connection                                        | 10       | 0.63%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 10       | 0.63%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 9        | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 9        | 0.57%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 9        | 0.57%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 9        | 0.57%   |
| Intel 82576 Gigabit Network Connection                                        | 9        | 0.57%   |
| Intel Ethernet Connection (5) I219-LM                                         | 8        | 0.5%    |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 8        | 0.5%    |
| American Megatrends Virtual Ethernet                                          | 8        | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                                 | 7        | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 7        | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 6        | 0.38%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 6        | 0.38%   |
| Intel Ethernet Connection (11) I219-V                                         | 6        | 0.38%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 6        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1277     | 74.9%   |
| WiFi     | 381      | 22.35%  |
| Unknown  | 28       | 1.64%   |
| Modem    | 19       | 1.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1197     | 90.75%  |
| WiFi     | 117      | 8.87%   |
| Unknown  | 5        | 0.38%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 649      | 48.22%  |
| 2     | 417      | 30.98%  |
| 3     | 132      | 9.81%   |
| 4     | 54       | 4.01%   |
| 0     | 44       | 3.27%   |
| 5     | 20       | 1.49%   |
| 6     | 19       | 1.41%   |
| 7     | 6        | 0.45%   |
| 8     | 3        | 0.22%   |
| 10    | 1        | 0.07%   |
| 9     | 1        | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1174     | 86.07%  |
| Yes  | 190      | 13.93%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 152      | 51.7%   |
| Cambridge Silicon Radio         | 39       | 13.27%  |
| Realtek Semiconductor           | 25       | 8.5%    |
| ASUSTek Computer                | 14       | 4.76%   |
| MediaTek                        | 12       | 4.08%   |
| Qualcomm Atheros Communications | 9        | 3.06%   |
| Apple                           | 9        | 3.06%   |
| IMC Networks                    | 7        | 2.38%   |
| Foxconn / Hon Hai               | 7        | 2.38%   |
| Broadcom                        | 6        | 2.04%   |
| Lite-On Technology              | 4        | 1.36%   |
| Micro Star International        | 3        | 1.02%   |
| Unknown                         | 2        | 0.68%   |
| TP-Link                         | 1        | 0.34%   |
| Sino Wealth Electronic          | 1        | 0.34%   |
| Realtek                         | 1        | 0.34%   |
| Ralink                          | 1        | 0.34%   |
| Corsair                         | 1        | 0.34%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                       | 48       | 16.16%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 39       | 13.13%  |
| Intel Bluetooth wireless interface                          | 30       | 10.1%   |
| Realtek Bluetooth Adapter                                   | 17       | 5.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 17       | 5.72%   |
| Intel AX201 Bluetooth                                       | 16       | 5.39%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 14       | 4.71%   |
| Intel Wireless-AC 3168 Bluetooth                            | 13       | 4.38%   |
| Intel AX210 Bluetooth                                       | 10       | 3.37%   |
| MediaTek RZ608 Bluetooth Adapter                            | 7        | 2.36%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 6        | 2.02%   |
| Realtek  Bluetooth 4.2 Adapter                              | 5        | 1.68%   |
| Intel AX211 Bluetooth                                       | 5        | 1.68%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter                   | 5        | 1.68%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 5        | 1.68%   |
| Apple Bluetooth Host Controller                             | 5        | 1.68%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 4        | 1.35%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0          | 3        | 1.01%   |
| Realtek Bluetooth 4.2 Adapter                               | 2        | 0.67%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2        | 0.67%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 2        | 0.67%   |
| Micro Star International Bluetooth 2.1+EDR USB Device       | 2        | 0.67%   |
| MediaTek Wireless_Device                                    | 2        | 0.67%   |
| MediaTek RZ616 Bluetooth Adapter                            | 2        | 0.67%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2        | 0.67%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2        | 0.67%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 2        | 0.67%   |
| ASUS Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter     | 2        | 0.67%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE       | 2        | 0.67%   |
| ASUS Bluetooth USB module                                   | 2        | 0.67%   |
| Unknown                                                     | 2        | 0.67%   |
| TP-Link Bluetooth 5.0 USB Adapter                           | 1        | 0.34%   |
| Sino Wealth Electronic RK Bluetooth Keyboar                 | 1        | 0.34%   |
| Realtek RTL8723B Bluetooth                                  | 1        | 0.34%   |
| Realtek  Bluetooth 4.0 Adapter                              | 1        | 0.34%   |
| Ralink RT3290 Bluetooth                                     | 1        | 0.34%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.1                      | 1        | 0.34%   |
| Qualcomm Atheros Dell Wireless 1901 Bluetooth               | 1        | 0.34%   |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE        | 1        | 0.34%   |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1        | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 637      | 37.83%  |
| AMD                                          | 465      | 27.61%  |
| Nvidia                                       | 364      | 21.62%  |
| C-Media Electronics                          | 31       | 1.84%   |
| Logitech                                     | 19       | 1.13%   |
| Creative Labs                                | 19       | 1.13%   |
| Texas Instruments                            | 10       | 0.59%   |
| Realtek Semiconductor                        | 8        | 0.48%   |
| Focusrite-Novation                           | 8        | 0.48%   |
| Blue Microphones                             | 7        | 0.42%   |
| Thesycon Systemsoftware & Consulting         | 6        | 0.36%   |
| JMTek                                        | 6        | 0.36%   |
| ASUSTek Computer                             | 6        | 0.36%   |
| Sony                                         | 5        | 0.3%    |
| Generalplus Technology                       | 5        | 0.3%    |
| Creative Technology                          | 5        | 0.3%    |
| BEHRINGER International                      | 5        | 0.3%    |
| Plantronics                                  | 4        | 0.24%   |
| Kingston Technology                          | 4        | 0.24%   |
| VIA Technologies                             | 3        | 0.18%   |
| Tenx Technology                              | 3        | 0.18%   |
| SteelSeries ApS                              | 3        | 0.18%   |
| Silicon Integrated Systems [SiS]             | 3        | 0.18%   |
| Micro Star International                     | 3        | 0.18%   |
| Huawei Technologies                          | 3        | 0.18%   |
| GN Netcom                                    | 3        | 0.18%   |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 0.12%   |
| Yamaha                                       | 2        | 0.12%   |
| Trust                                        | 2        | 0.12%   |
| ROCCAT                                       | 2        | 0.12%   |
| Razer USA                                    | 2        | 0.12%   |
| M-Audio                                      | 2        | 0.12%   |
| FiiO Electronics Technology                  | 2        | 0.12%   |
| Dell                                         | 2        | 0.12%   |
| Corsair                                      | 2        | 0.12%   |
| Cambridge Silicon Radio                      | 2        | 0.12%   |
| Audio-Technica                               | 2        | 0.12%   |
| XMOS                                         | 1        | 0.06%   |
| Xilinx                                       | 1        | 0.06%   |
| Universal Audio                              | 1        | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 111      | 5.54%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 100      | 4.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 68       | 3.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 62       | 3.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 61       | 3.04%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 61       | 3.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 56       | 2.79%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 53       | 2.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 52       | 2.59%   |
| Intel 200 Series PCH HD Audio                                              | 51       | 2.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 50       | 2.5%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 48       | 2.4%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 47       | 2.35%   |
| Intel Cannon Lake PCH cAVS                                                 | 36       | 1.8%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 33       | 1.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 32       | 1.6%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 31       | 1.55%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 30       | 1.5%    |
| Nvidia GP108 High Definition Audio Controller                              | 26       | 1.3%    |
| Nvidia GP107GL High Definition Audio Controller                            | 26       | 1.3%    |
| Nvidia TU116 High Definition Audio Controller                              | 24       | 1.2%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 24       | 1.2%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 23       | 1.15%   |
| Nvidia High Definition Audio Controller                                    | 21       | 1.05%   |
| AMD FCH Azalia Controller                                                  | 21       | 1.05%   |
| Nvidia GP104 High Definition Audio Controller                              | 20       | 1%      |
| Nvidia GF119 HDMI Audio Controller                                         | 20       | 1%      |
| Intel C610/X99 series chipset HD Audio Controller                          | 20       | 1%      |
| Intel 9 Series Chipset Family HD Audio Controller                          | 20       | 1%      |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 19       | 0.95%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 19       | 0.95%   |
| Nvidia GP106 High Definition Audio Controller                              | 18       | 0.9%    |
| Intel Alder Lake-S HD Audio Controller                                     | 17       | 0.85%   |
| Nvidia GK107 HDMI Audio Controller                                         | 16       | 0.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 16       | 0.8%    |
| AMD Navi 10 HDMI Audio                                                     | 16       | 0.8%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 15       | 0.75%   |
| Nvidia GF108 High Definition Audio Controller                              | 15       | 0.75%   |
| Intel Comet Lake PCH cAVS                                                  | 15       | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 15       | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 234      | 16.68%  |
| Unknown                      | 198      | 14.11%  |
| Corsair                      | 164      | 11.69%  |
| Samsung Electronics          | 139      | 9.91%   |
| SK hynix                     | 135      | 9.62%   |
| Crucial                      | 111      | 7.91%   |
| G.Skill                      | 104      | 7.41%   |
| Micron Technology            | 84       | 5.99%   |
| Unknown                      | 34       | 2.42%   |
| A-DATA Technology            | 27       | 1.92%   |
| Patriot                      | 18       | 1.28%   |
| Team                         | 15       | 1.07%   |
| Ramaxel Technology           | 11       | 0.78%   |
| Hewlett-Packard              | 11       | 0.78%   |
| Nanya Technology             | 10       | 0.71%   |
| GOODRAM                      | 10       | 0.71%   |
| Transcend                    | 9        | 0.64%   |
| Patriot Memory (PDP Systems) | 8        | 0.57%   |
| AMD                          | 5        | 0.36%   |
| Unknown (ABCD)               | 4        | 0.29%   |
| Lexar Co Limited             | 4        | 0.29%   |
| Apacer                       | 4        | 0.29%   |
| Tigo                         | 3        | 0.21%   |
| Super Talent                 | 3        | 0.21%   |
| Qimonda                      | 3        | 0.21%   |
| Kllisre                      | 3        | 0.21%   |
| Kingmax                      | 3        | 0.21%   |
| GeIL                         | 3        | 0.21%   |
| Avant                        | 3        | 0.21%   |
| V-GeN                        | 2        | 0.14%   |
| Silicon Power                | 2        | 0.14%   |
| PNY                          | 2        | 0.14%   |
| Kreton                       | 2        | 0.14%   |
| HPE                          | 2        | 0.14%   |
| Goldkey                      | 2        | 0.14%   |
| Golden Empire                | 2        | 0.14%   |
| Elpida                       | 2        | 0.14%   |
| ASint Technology             | 2        | 0.14%   |
| V-Color                      | 1        | 0.07%   |
| Unknown (AB)                 | 1        | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown                                                        | 34       | 2.21%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 15       | 0.98%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s          | 14       | 0.91%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 11       | 0.72%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 9        | 0.59%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 9        | 0.59%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s          | 9        | 0.59%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 8        | 0.52%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 3200MT/s           | 8        | 0.52%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 8        | 0.52%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s           | 8        | 0.52%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s          | 8        | 0.52%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s           | 7        | 0.46%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s            | 7        | 0.46%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s              | 7        | 0.46%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                   | 6        | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 6        | 0.39%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 6        | 0.39%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 6        | 0.39%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 6        | 0.39%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s            | 6        | 0.39%   |
| G.Skill RAM F4-3200C16-32GVK 32GB DIMM DDR4 3200MT/s           | 6        | 0.39%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s          | 6        | 0.39%   |
| Unknown RAM Module 512MB DIMM SDRAM                            | 5        | 0.33%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 5        | 0.33%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 5        | 0.33%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s           | 5        | 0.33%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1333MT/s            | 5        | 0.33%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 2666MT/s           | 5        | 0.33%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2933MT/s              | 5        | 0.33%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1866MT/s          | 5        | 0.33%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s         | 5        | 0.33%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3000MT/s         | 5        | 0.33%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                       | 4        | 0.26%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 4        | 0.26%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s | 4        | 0.26%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 4        | 0.26%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 4        | 0.26%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s             | 4        | 0.26%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s           | 4        | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 565      | 45.31%  |
| DDR3         | 451      | 36.17%  |
| Unknown      | 69       | 5.53%   |
| DDR2         | 59       | 4.73%   |
| DDR5         | 41       | 3.29%   |
| SDRAM        | 32       | 2.57%   |
| DDR          | 18       | 1.44%   |
| LPDDR4       | 6        | 0.48%   |
| DRAM         | 3        | 0.24%   |
| LPDDR5       | 1        | 0.08%   |
| LPDDR3       | 1        | 0.08%   |
| DDR2 FB-DIMM | 1        | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1096     | 88.39%  |
| SODIMM       | 129      | 10.4%   |
| RIMM         | 8        | 0.65%   |
| Row Of Chips | 4        | 0.32%   |
| FB-DIMM      | 1        | 0.08%   |
| Chip         | 1        | 0.08%   |
| Unknown      | 1        | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 474      | 35.11%  |
| 4096  | 296      | 21.93%  |
| 16384 | 256      | 18.96%  |
| 2048  | 152      | 11.26%  |
| 32768 | 104      | 7.7%    |
| 1024  | 44       | 3.26%   |
| 512   | 13       | 0.96%   |
| 49152 | 4        | 0.3%    |
| 128   | 2        | 0.15%   |
| 6144  | 1        | 0.07%   |
| 256   | 1        | 0.07%   |
| 64    | 1        | 0.07%   |
| 32    | 1        | 0.07%   |
| 8     | 1        | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 267      | 20.14%  |
| 1333    | 187      | 14.1%   |
| 3200    | 183      | 13.8%   |
| 2400    | 130      | 9.8%    |
| 2133    | 99       | 7.47%   |
| 2667    | 77       | 5.81%   |
| 800     | 65       | 4.9%    |
| 667     | 33       | 2.49%   |
| 2666    | 31       | 2.34%   |
| 3600    | 29       | 2.19%   |
| Unknown | 29       | 2.19%   |
| 4800    | 28       | 2.11%   |
| 3000    | 27       | 2.04%   |
| 2933    | 20       | 1.51%   |
| 1866    | 17       | 1.28%   |
| 1066    | 16       | 1.21%   |
| 1867    | 11       | 0.83%   |
| 400     | 11       | 0.83%   |
| 533     | 10       | 0.75%   |
| 5600    | 6        | 0.45%   |
| 1067    | 6        | 0.45%   |
| 5200    | 5        | 0.38%   |
| 3400    | 4        | 0.3%    |
| 1334    | 4        | 0.3%    |
| 6400    | 3        | 0.23%   |
| 4000    | 3        | 0.23%   |
| 3733    | 2        | 0.15%   |
| 3534    | 2        | 0.15%   |
| 2800    | 2        | 0.15%   |
| 2048    | 2        | 0.15%   |
| 1400    | 2        | 0.15%   |
| 1332    | 2        | 0.15%   |
| 333     | 2        | 0.15%   |
| 65535   | 1        | 0.08%   |
| 7200    | 1        | 0.08%   |
| 4133    | 1        | 0.08%   |
| 3500    | 1        | 0.08%   |
| 3066    | 1        | 0.08%   |
| 2600    | 1        | 0.08%   |
| 2134    | 1        | 0.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 4        | 30.77%  |
| Prolific Technology | 2        | 15.38%  |
| Hewlett-Packard     | 2        | 15.38%  |
| Seiko Epson         | 1        | 7.69%   |
| Samsung Electronics | 1        | 7.69%   |
| QinHeng Electronics | 1        | 7.69%   |
| Dymo-CoStar         | 1        | 7.69%   |
| Canon               | 1        | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                      | Desktops | Percent |
|--------------------------------------------------------------------------------------------|----------|---------|
| Prolific PL2305 Parallel Port                                                              | 2        | 15.38%  |
| Seiko Epson Printer                                                                        | 1        | 7.69%   |
| Samsung ML-1640 Series Laser Printer                                                       | 1        | 7.69%   |
| QinHeng CH340S                                                                             | 1        | 7.69%   |
| HP LaserJet 1012                                                                           | 1        | 7.69%   |
| HP HP LaserJet M14-M17 Printer HP LEDM IPP Printer HP LEDM IPP Printer HP LEDM IPP Printer | 1        | 7.69%   |
| Dymo-CoStar LabelWriter 450                                                                | 1        | 7.69%   |
| Canon LBP2900                                                                              | 1        | 7.69%   |
| Brother MFC-7360N                                                                          | 1        | 7.69%   |
| Brother HL-L5200DW series                                                                  | 1        | 7.69%   |
| Brother HL-2030 Laser Printer                                                              | 1        | 7.69%   |
| Brother HL-1430 Laser Printer                                                              | 1        | 7.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 4        | 50%     |
| Seiko Epson     | 3        | 37.5%   |
| Hewlett-Packard | 1        | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Desktops | Percent |
|-------------------------------------------------------------------------------------|----------|---------|
| Seiko Epson WF-2850 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 2        | 25%     |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                       | 1        | 12.5%   |
| HP ScanJet 5300c/5370c                                                              | 1        | 12.5%   |
| Canon CanoScan LIDE 25                                                              | 1        | 12.5%   |
| Canon CanoScan LiDE 220                                                             | 1        | 12.5%   |
| Canon CanoScan LiDE 110                                                             | 1        | 12.5%   |
| Canon CanoScan 9000F                                                                | 1        | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 49       | 57.65%  |
| Microdia                      | 13       | 15.29%  |
| ARC International             | 3        | 3.53%   |
| WCM_USB                       | 2        | 2.35%   |
| Trust                         | 2        | 2.35%   |
| SHENZHEN EMEET TECHNOLOGY     | 2        | 2.35%   |
| Z-Star Microelectronics       | 1        | 1.18%   |
| YGTek                         | 1        | 1.18%   |
| Valve Software                | 1        | 1.18%   |
| Suyin                         | 1        | 1.18%   |
| Sunplus Innovation Technology | 1        | 1.18%   |
| Sonix Technology              | 1        | 1.18%   |
| Realtek Semiconductor         | 1        | 1.18%   |
| OmniVision Technologies       | 1        | 1.18%   |
| Nam Tai E&E Products          | 1        | 1.18%   |
| Lenovo                        | 1        | 1.18%   |
| Huawei Technologies           | 1        | 1.18%   |
| Cubeternet                    | 1        | 1.18%   |
| Aveo Technology               | 1        | 1.18%   |
| Arkmicro Technologies         | 1        | 1.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech Webcam C270                           | 14       | 16.47%  |
| Logitech HD Pro Webcam C920                    | 7        | 8.24%   |
| Logitech C920 PRO HD Webcam                    | 5        | 5.88%   |
| Logitech Webcam C310                           | 3        | 3.53%   |
| Logitech C922 Pro Stream Webcam                | 3        | 3.53%   |
| ARC International Camera                       | 3        | 3.53%   |
| WCM_USB WEB CAM                                | 2        | 2.35%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960 | 2        | 2.35%   |
| Microdia Webcam Vitade AF                      | 2        | 2.35%   |
| Microdia USB 2.0 Camera                        | 2        | 2.35%   |
| Microdia PC-LM1E                               | 2        | 2.35%   |
| Microdia Lenovo EasyCamera                     | 2        | 2.35%   |
| Microdia HP Integrated Webcam                  | 2        | 2.35%   |
| Logitech Webcam C930e                          | 2        | 2.35%   |
| Logitech Logi Webcam C920e                     | 2        | 2.35%   |
| Logitech Labtec Webcam Pro                     | 2        | 2.35%   |
| Logitech C920 HD Pro Webcam                    | 2        | 2.35%   |
| Logitech C505 HD Webcam                        | 2        | 2.35%   |
| Logitech BRIO Ultra HD Webcam                  | 2        | 2.35%   |
| Z-Star Venus USB2.0 Camera                     | 1        | 1.18%   |
| YGTek Webcam                                   | 1        | 1.18%   |
| Valve Software 3D Camera                       | 1        | 1.18%   |
| Trust Trust QHD Webcam                         | 1        | 1.18%   |
| Trust Canyon CNS-CWC6 Webcam                   | 1        | 1.18%   |
| Suyin Acer CrystalEye Webcam                   | 1        | 1.18%   |
| Sunplus 2-USB 2.0 Camera                       | 1        | 1.18%   |
| Sonix FHD Webcam                               | 1        | 1.18%   |
| Realtek USB Video Device                       | 1        | 1.18%   |
| OmniVision Monitor Webcam                      | 1        | 1.18%   |
| Nam Tai E&E Products Sony Playstation Eye      | 1        | 1.18%   |
| Microdia USB  Live camera                      | 1        | 1.18%   |
| Microdia JOYACCESS JA-Webcam                   | 1        | 1.18%   |
| Microdia Camera                                | 1        | 1.18%   |
| Logitech Webcam C170                           | 1        | 1.18%   |
| Logitech QuickCam OEM Cisco VT Camera II       | 1        | 1.18%   |
| Logitech Logitech Webcam C925e                 | 1        | 1.18%   |
| Logitech HD Webcam C615                        | 1        | 1.18%   |
| Logitech HD Webcam C525                        | 1        | 1.18%   |
| Lenovo Integrated Camera                       | 1        | 1.18%   |
| Huawei HiCamera                                | 1        | 1.18%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| FocalTech Systems | 1        | 50%     |
| DigitalPersona    | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| FocalTech Systems Fingerprint Reader | 1        | 50%     |
| DigitalPersona Fingerprint Reader    | 1        | 50%     |

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
| 1     | 570      | 41.61%  |
| 0     | 536      | 39.12%  |
| 2     | 205      | 14.96%  |
| 3     | 45       | 3.28%   |
| 4     | 11       | 0.8%    |
| 6     | 2        | 0.15%   |
| 5     | 1        | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 617      | 58.43%  |
| Net/wireless             | 144      | 13.64%  |
| Bluetooth                | 98       | 9.28%   |
| Firewire controller      | 73       | 6.91%   |
| Net/ethernet             | 37       | 3.5%    |
| Sound                    | 32       | 3.03%   |
| Network                  | 25       | 2.37%   |
| Card reader              | 21       | 1.99%   |
| Dvb card                 | 5        | 0.47%   |
| Storage/raid             | 2        | 0.19%   |
| Fingerprint reader       | 2        | 0.19%   |

