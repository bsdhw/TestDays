helloSystem 0.7.0 - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.7.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/helloSystem_0.7.0/Desktop/README.md) and [notebooks](/Dist/helloSystem_0.7.0/Notebook/README.md).

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

Total: 358

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Positivo      | POS-PIQ77CL POSITIVO        | Desktop     | [848361c724](https://bsd-hardware.info/?probe=848361c724) | May 31, 2022 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [c734325ede](https://bsd-hardware.info/?probe=c734325ede) | May 31, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [7152e4b816](https://bsd-hardware.info/?probe=7152e4b816) | May 29, 2022 |
| Dell          | 048DY8 A00                  | Desktop     | [7d1c59b392](https://bsd-hardware.info/?probe=7d1c59b392) | May 29, 2022 |
| Unknown       | Unknown                     | All in one  | [732a9df612](https://bsd-hardware.info/?probe=732a9df612) | May 27, 2022 |
| ASUSTek       | P5LD2                       | Desktop     | [64208afa2c](https://bsd-hardware.info/?probe=64208afa2c) | May 25, 2022 |
| T-bao         | MINI PC V1.0                | Desktop     | [a89b2081bb](https://bsd-hardware.info/?probe=a89b2081bb) | May 25, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [d0565222dc](https://bsd-hardware.info/?probe=d0565222dc) | May 24, 2022 |
| Intel         | NUC7i7BNB J31145-306        | Mini pc     | [934edfe03d](https://bsd-hardware.info/?probe=934edfe03d) | May 24, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [9e2661b9e0](https://bsd-hardware.info/?probe=9e2661b9e0) | May 24, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [ee8ba76de5](https://bsd-hardware.info/?probe=ee8ba76de5) | May 22, 2022 |
| ASUSTek       | F50SL                       | Notebook    | [e26b522868](https://bsd-hardware.info/?probe=e26b522868) | May 22, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [e7055d83e2](https://bsd-hardware.info/?probe=e7055d83e2) | May 20, 2022 |
| HP            | Pavilion dv6                | Notebook    | [73e328ad87](https://bsd-hardware.info/?probe=73e328ad87) | May 20, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [23396b461f](https://bsd-hardware.info/?probe=23396b461f) | May 18, 2022 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [b74299204a](https://bsd-hardware.info/?probe=b74299204a) | May 18, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [55cda59c51](https://bsd-hardware.info/?probe=55cda59c51) | May 17, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [5688deb0a7](https://bsd-hardware.info/?probe=5688deb0a7) | May 16, 2022 |
| ASUSTek       | K52F                        | Notebook    | [6e86ce2a12](https://bsd-hardware.info/?probe=6e86ce2a12) | May 15, 2022 |
| ASUSTek       | K52F                        | Notebook    | [4c12c55177](https://bsd-hardware.info/?probe=4c12c55177) | May 15, 2022 |
| Dell          | 0G261D A00                  | Desktop     | [c0fafdb905](https://bsd-hardware.info/?probe=c0fafdb905) | May 14, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [d9c28e14df](https://bsd-hardware.info/?probe=d9c28e14df) | May 13, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [5e781a451d](https://bsd-hardware.info/?probe=5e781a451d) | May 12, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [34ac291019](https://bsd-hardware.info/?probe=34ac291019) | May 11, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [97d7714d47](https://bsd-hardware.info/?probe=97d7714d47) | May 10, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [aad86a8b8e](https://bsd-hardware.info/?probe=aad86a8b8e) | May 10, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [3ff916acf7](https://bsd-hardware.info/?probe=3ff916acf7) | May 09, 2022 |
| HP            | ProBook 4340s               | Notebook    | [6cc978f98f](https://bsd-hardware.info/?probe=6cc978f98f) | May 09, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [33367fe342](https://bsd-hardware.info/?probe=33367fe342) | May 09, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [b54df77b59](https://bsd-hardware.info/?probe=b54df77b59) | May 07, 2022 |
| Unknown       | W1415A                      | Notebook    | [1b2c63a845](https://bsd-hardware.info/?probe=1b2c63a845) | May 07, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [daed3f9401](https://bsd-hardware.info/?probe=daed3f9401) | May 06, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [bf3d4941a2](https://bsd-hardware.info/?probe=bf3d4941a2) | May 06, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [dd3afff7f0](https://bsd-hardware.info/?probe=dd3afff7f0) | May 06, 2022 |
| Dell          | 0Y7WYT A00                  | Desktop     | [76674e4d62](https://bsd-hardware.info/?probe=76674e4d62) | May 06, 2022 |
| Sony          | VGN-NW25GF_S                | Notebook    | [84b50ca3f1](https://bsd-hardware.info/?probe=84b50ca3f1) | May 06, 2022 |
| Toshiba       | Satellite P300              | Notebook    | [fca7b38039](https://bsd-hardware.info/?probe=fca7b38039) | May 04, 2022 |
| Lenovo        | B470 HuronRiver Platform    | Notebook    | [e0ef68c720](https://bsd-hardware.info/?probe=e0ef68c720) | May 04, 2022 |
| HP            | Pavilion m6                 | Notebook    | [c720817018](https://bsd-hardware.info/?probe=c720817018) | May 03, 2022 |
| OEM           | B85 JHS359                  | Desktop     | [c5d29cc6b3](https://bsd-hardware.info/?probe=c5d29cc6b3) | May 03, 2022 |
| HP            | Pavilion g6                 | Notebook    | [4b8ee6729a](https://bsd-hardware.info/?probe=4b8ee6729a) | May 02, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [24d308754b](https://bsd-hardware.info/?probe=24d308754b) | May 02, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [c59d8482e8](https://bsd-hardware.info/?probe=c59d8482e8) | May 01, 2022 |
| HP            | 0AA8h                       | Desktop     | [f9b906ea47](https://bsd-hardware.info/?probe=f9b906ea47) | Apr 30, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [807676e010](https://bsd-hardware.info/?probe=807676e010) | Apr 30, 2022 |
| Lenovo        | ThinkPad T420 4236BD5       | Notebook    | [867ed989e2](https://bsd-hardware.info/?probe=867ed989e2) | Apr 27, 2022 |
| Supermicro    | X9DAL                       | Desktop     | [ef1f3da3ce](https://bsd-hardware.info/?probe=ef1f3da3ce) | Apr 26, 2022 |
| MSI           | GF65 Thin 10SER             | Notebook    | [cedf98c955](https://bsd-hardware.info/?probe=cedf98c955) | Apr 26, 2022 |
| Dell          | Inspiron 5437               | Notebook    | [830ea686ab](https://bsd-hardware.info/?probe=830ea686ab) | Apr 24, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [271f1aa4d1](https://bsd-hardware.info/?probe=271f1aa4d1) | Apr 24, 2022 |
| HP            | 2000                        | Notebook    | [e9599a9bc3](https://bsd-hardware.info/?probe=e9599a9bc3) | Apr 22, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [427cf12b45](https://bsd-hardware.info/?probe=427cf12b45) | Apr 22, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [f7a3f1dfd3](https://bsd-hardware.info/?probe=f7a3f1dfd3) | Apr 21, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [2fd6d176ce](https://bsd-hardware.info/?probe=2fd6d176ce) | Apr 21, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [bae3bbc2be](https://bsd-hardware.info/?probe=bae3bbc2be) | Apr 21, 2022 |
| Intel         | H55                         | Desktop     | [1478e4af73](https://bsd-hardware.info/?probe=1478e4af73) | Apr 20, 2022 |
| ASUSTek       | X556UJ                      | Notebook    | [ca63749774](https://bsd-hardware.info/?probe=ca63749774) | Apr 19, 2022 |
| Lenovo        | G51-35 80M8                 | Notebook    | [285328cb61](https://bsd-hardware.info/?probe=285328cb61) | Apr 16, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [680303f943](https://bsd-hardware.info/?probe=680303f943) | Apr 16, 2022 |
| Dell          | 0Y7WYT A00                  | Desktop     | [399a4fb92e](https://bsd-hardware.info/?probe=399a4fb92e) | Apr 15, 2022 |
| Sony          | SVZ1311C5E                  | Notebook    | [c1c429a7e6](https://bsd-hardware.info/?probe=c1c429a7e6) | Apr 15, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [47d17d48a7](https://bsd-hardware.info/?probe=47d17d48a7) | Apr 15, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [5502c7fd2f](https://bsd-hardware.info/?probe=5502c7fd2f) | Apr 15, 2022 |
| Dell          | Latitude E6540              | Notebook    | [a3da09ae5e](https://bsd-hardware.info/?probe=a3da09ae5e) | Apr 15, 2022 |
| Intel         | NUC7JYB J67967-402          | Mini pc     | [e94a3a5a08](https://bsd-hardware.info/?probe=e94a3a5a08) | Apr 14, 2022 |
| ASUSTek       | PRIME X399-A                | Desktop     | [3d26c05fda](https://bsd-hardware.info/?probe=3d26c05fda) | Apr 14, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [562a4d0421](https://bsd-hardware.info/?probe=562a4d0421) | Apr 14, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [9f70756cb2](https://bsd-hardware.info/?probe=9f70756cb2) | Apr 14, 2022 |
| System76      | Lemur Pro                   | Notebook    | [276ee4e96e](https://bsd-hardware.info/?probe=276ee4e96e) | Apr 13, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [11ec99d4b7](https://bsd-hardware.info/?probe=11ec99d4b7) | Apr 11, 2022 |
| Lenovo        | ThinkPad X61 7675K2U        | Notebook    | [24f93b9532](https://bsd-hardware.info/?probe=24f93b9532) | Apr 10, 2022 |
| HP            | 1998                        | Desktop     | [06f0a28858](https://bsd-hardware.info/?probe=06f0a28858) | Apr 10, 2022 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [844323ad2d](https://bsd-hardware.info/?probe=844323ad2d) | Apr 09, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [ded0d1a114](https://bsd-hardware.info/?probe=ded0d1a114) | Apr 09, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [14a6449380](https://bsd-hardware.info/?probe=14a6449380) | Apr 09, 2022 |
| ASUSTek       | M4A88T-M                    | Desktop     | [9d1a8b4886](https://bsd-hardware.info/?probe=9d1a8b4886) | Apr 09, 2022 |
| ASRock        | X570 Steel Legend WiFi a... | Desktop     | [703e042cfe](https://bsd-hardware.info/?probe=703e042cfe) | Apr 09, 2022 |
| Dell          | 0D6H9T A00                  | Desktop     | [e58bc4937d](https://bsd-hardware.info/?probe=e58bc4937d) | Apr 09, 2022 |
| Panasonic     | CF-B11JWCYS                 | Notebook    | [6699d408ad](https://bsd-hardware.info/?probe=6699d408ad) | Apr 08, 2022 |
| Gigabyte      | E3000N                      | Desktop     | [7169c296cc](https://bsd-hardware.info/?probe=7169c296cc) | Apr 08, 2022 |
| MSI           | MS-7369                     | Desktop     | [25f2161cac](https://bsd-hardware.info/?probe=25f2161cac) | Apr 08, 2022 |
| HP            | Pavilion 11                 | Notebook    | [a13373b255](https://bsd-hardware.info/?probe=a13373b255) | Apr 07, 2022 |
| DNS           | W9x0LU                      | Notebook    | [8ac57e3b59](https://bsd-hardware.info/?probe=8ac57e3b59) | Apr 06, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [e72b47b6de](https://bsd-hardware.info/?probe=e72b47b6de) | Apr 04, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [5038186437](https://bsd-hardware.info/?probe=5038186437) | Apr 02, 2022 |
| LG Electro... | E300-A.CP20T                | Notebook    | [304701f666](https://bsd-hardware.info/?probe=304701f666) | Apr 02, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [1be95af210](https://bsd-hardware.info/?probe=1be95af210) | Apr 01, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [e0c61311da](https://bsd-hardware.info/?probe=e0c61311da) | Apr 01, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [42419abab8](https://bsd-hardware.info/?probe=42419abab8) | Apr 01, 2022 |
| Dell          | 0D6H9T A00                  | Desktop     | [7daab72741](https://bsd-hardware.info/?probe=7daab72741) | Apr 01, 2022 |
| HP            | Compaq 6510b (GF910AW#AB... | Notebook    | [a7bccf74e4](https://bsd-hardware.info/?probe=a7bccf74e4) | Mar 31, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [49627775f3](https://bsd-hardware.info/?probe=49627775f3) | Mar 31, 2022 |
| ASUSTek       | P6-P8H61E                   | Desktop     | [11664cd9d7](https://bsd-hardware.info/?probe=11664cd9d7) | Mar 30, 2022 |
| ASUSTek       | M4A88T-M                    | Desktop     | [6a615f6be5](https://bsd-hardware.info/?probe=6a615f6be5) | Mar 30, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [0906d116eb](https://bsd-hardware.info/?probe=0906d116eb) | Mar 29, 2022 |
| Gigabyte      | H110N-CF                    | Desktop     | [89593af061](https://bsd-hardware.info/?probe=89593af061) | Mar 29, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [553f2beb91](https://bsd-hardware.info/?probe=553f2beb91) | Mar 27, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [47ef9ef91a](https://bsd-hardware.info/?probe=47ef9ef91a) | Mar 27, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [8c89faeb24](https://bsd-hardware.info/?probe=8c89faeb24) | Mar 26, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [ae1fa6cbce](https://bsd-hardware.info/?probe=ae1fa6cbce) | Mar 26, 2022 |
| Dell          | Latitude E6540              | Notebook    | [0ac0f8f1d8](https://bsd-hardware.info/?probe=0ac0f8f1d8) | Mar 26, 2022 |
| ASUSTek       | ET2411_W8                   | All in one  | [fb186da68e](https://bsd-hardware.info/?probe=fb186da68e) | Mar 26, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [00213ecee9](https://bsd-hardware.info/?probe=00213ecee9) | Mar 25, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [70d10ce47c](https://bsd-hardware.info/?probe=70d10ce47c) | Mar 25, 2022 |
| MSI           | B85-G43                     | Desktop     | [f0a919c35f](https://bsd-hardware.info/?probe=f0a919c35f) | Mar 25, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [99d079bd5a](https://bsd-hardware.info/?probe=99d079bd5a) | Mar 25, 2022 |
| MSI           | B85-G43                     | Desktop     | [7bd545fda8](https://bsd-hardware.info/?probe=7bd545fda8) | Mar 25, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [c76aa38baf](https://bsd-hardware.info/?probe=c76aa38baf) | Mar 24, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [8696405d09](https://bsd-hardware.info/?probe=8696405d09) | Mar 24, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [9b3dac520a](https://bsd-hardware.info/?probe=9b3dac520a) | Mar 24, 2022 |
| Dell          | Vostro 3490                 | Notebook    | [34956934f5](https://bsd-hardware.info/?probe=34956934f5) | Mar 22, 2022 |
| ECS           | G41T-M9                     | Desktop     | [9ef50c47da](https://bsd-hardware.info/?probe=9ef50c47da) | Mar 21, 2022 |
| Packard Be... | EasyNote TE69HW             | Notebook    | [851eea349f](https://bsd-hardware.info/?probe=851eea349f) | Mar 17, 2022 |
| ASUSTek       | ET2411_W8                   | All in one  | [b95da98f21](https://bsd-hardware.info/?probe=b95da98f21) | Mar 17, 2022 |
| Lenovo        | ThinkPad X220 4293B43       | Notebook    | [148a268a0f](https://bsd-hardware.info/?probe=148a268a0f) | Mar 16, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [2727a8e439](https://bsd-hardware.info/?probe=2727a8e439) | Mar 15, 2022 |
| HASEE Comp... | CW35S                       | Notebook    | [737c8bb48a](https://bsd-hardware.info/?probe=737c8bb48a) | Mar 14, 2022 |
| Lenovo        | ThinkPad L440 20ASS0FP00    | Notebook    | [0fbc782835](https://bsd-hardware.info/?probe=0fbc782835) | Mar 14, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e0576dd008](https://bsd-hardware.info/?probe=e0576dd008) | Mar 13, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [5a22bb6991](https://bsd-hardware.info/?probe=5a22bb6991) | Mar 12, 2022 |
| Lenovo        | IdeaCentre B545 10100       | Desktop     | [2f13d4a946](https://bsd-hardware.info/?probe=2f13d4a946) | Mar 12, 2022 |
| Acer          | Aspire E1-421               | Notebook    | [cc83218496](https://bsd-hardware.info/?probe=cc83218496) | Mar 10, 2022 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [b4234170e8](https://bsd-hardware.info/?probe=b4234170e8) | Mar 10, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [a1f85aff27](https://bsd-hardware.info/?probe=a1f85aff27) | Mar 10, 2022 |
| Lenovo        | IdeaPad N585                | Notebook    | [e22da97709](https://bsd-hardware.info/?probe=e22da97709) | Mar 10, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [ab71ed7239](https://bsd-hardware.info/?probe=ab71ed7239) | Mar 10, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [a58b9a4f8f](https://bsd-hardware.info/?probe=a58b9a4f8f) | Mar 09, 2022 |
| Itautec       | Infoway w7535               | Notebook    | [b55f9d1bfb](https://bsd-hardware.info/?probe=b55f9d1bfb) | Mar 09, 2022 |
| Koloe         | X58                         | Desktop     | [58e098eca2](https://bsd-hardware.info/?probe=58e098eca2) | Mar 09, 2022 |
| HP            | 8054                        | Desktop     | [86b6b8373c](https://bsd-hardware.info/?probe=86b6b8373c) | Mar 08, 2022 |
| HP            | 8054                        | Desktop     | [00078554d2](https://bsd-hardware.info/?probe=00078554d2) | Mar 08, 2022 |
| Koloe         | X58                         | Desktop     | [c501dfa5c8](https://bsd-hardware.info/?probe=c501dfa5c8) | Mar 07, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [dbd5c6e5e3](https://bsd-hardware.info/?probe=dbd5c6e5e3) | Mar 07, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [8b51036856](https://bsd-hardware.info/?probe=8b51036856) | Mar 06, 2022 |
| HP            | 1905                        | Desktop     | [e271589365](https://bsd-hardware.info/?probe=e271589365) | Mar 01, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [78f79fab6f](https://bsd-hardware.info/?probe=78f79fab6f) | Feb 28, 2022 |
| HP            | EliteBook Folio 9470m       | Notebook    | [e2cc942e3e](https://bsd-hardware.info/?probe=e2cc942e3e) | Feb 28, 2022 |
| Dell          | 0KV62T A00                  | Desktop     | [0541a207c7](https://bsd-hardware.info/?probe=0541a207c7) | Feb 28, 2022 |
| HP            | 1905                        | Desktop     | [aa010e00f2](https://bsd-hardware.info/?probe=aa010e00f2) | Feb 28, 2022 |
| Acer          | V5-131                      | Notebook    | [d175137636](https://bsd-hardware.info/?probe=d175137636) | Feb 27, 2022 |
| ASRock        | TRX40 Taichi                | Desktop     | [a2df68e1d1](https://bsd-hardware.info/?probe=a2df68e1d1) | Feb 26, 2022 |
| Intel         | H81                         | Desktop     | [04d2739bdc](https://bsd-hardware.info/?probe=04d2739bdc) | Feb 25, 2022 |
| Intel         | DCP847SKE G80890-107        | Desktop     | [f9d33f1ab1](https://bsd-hardware.info/?probe=f9d33f1ab1) | Feb 23, 2022 |
| Medion        | H61H2-LM3                   | Desktop     | [beb12f2884](https://bsd-hardware.info/?probe=beb12f2884) | Feb 23, 2022 |
| ASRock        | H81M-DG4                    | Desktop     | [e20db6ad83](https://bsd-hardware.info/?probe=e20db6ad83) | Feb 23, 2022 |
| HP            | 1998                        | Desktop     | [485d417a2e](https://bsd-hardware.info/?probe=485d417a2e) | Feb 23, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [feb7882341](https://bsd-hardware.info/?probe=feb7882341) | Feb 22, 2022 |
| Dell          | 0VD5HY A07                  | Desktop     | [bb86fb3e67](https://bsd-hardware.info/?probe=bb86fb3e67) | Feb 22, 2022 |
| Dell          | Latitude E4310              | Notebook    | [ba69f80b7f](https://bsd-hardware.info/?probe=ba69f80b7f) | Feb 22, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [e0cf5200de](https://bsd-hardware.info/?probe=e0cf5200de) | Feb 22, 2022 |
| Lenovo        | ThinkPad T61 766301U        | Notebook    | [f5f25efdcc](https://bsd-hardware.info/?probe=f5f25efdcc) | Feb 22, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [d680290d84](https://bsd-hardware.info/?probe=d680290d84) | Feb 22, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [1e6ff84e5d](https://bsd-hardware.info/?probe=1e6ff84e5d) | Feb 21, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [304508ed18](https://bsd-hardware.info/?probe=304508ed18) | Feb 21, 2022 |
| Dell          | Latitude E5470              | Notebook    | [9e479e9c50](https://bsd-hardware.info/?probe=9e479e9c50) | Feb 21, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [932550132e](https://bsd-hardware.info/?probe=932550132e) | Feb 20, 2022 |
| Lenovo        | ThinkPad T61 766301U        | Notebook    | [6eec3232e2](https://bsd-hardware.info/?probe=6eec3232e2) | Feb 19, 2022 |
| Intel         | NUC5CPYB H61145-404         | Mini pc     | [5f4e1c30b8](https://bsd-hardware.info/?probe=5f4e1c30b8) | Feb 19, 2022 |
| Gigabyte      | P41T-D3                     | Desktop     | [e5417931a7](https://bsd-hardware.info/?probe=e5417931a7) | Feb 18, 2022 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [2f90d5c2bd](https://bsd-hardware.info/?probe=2f90d5c2bd) | Feb 18, 2022 |
| ASRock        | B460M Pro4                  | Desktop     | [7a2781344f](https://bsd-hardware.info/?probe=7a2781344f) | Feb 17, 2022 |
| TUXEDO        | InfinityBook13V3            | Notebook    | [5a75db9142](https://bsd-hardware.info/?probe=5a75db9142) | Feb 17, 2022 |
| TUXEDO        | InfinityBook13V3            | Notebook    | [edc2c4ec36](https://bsd-hardware.info/?probe=edc2c4ec36) | Feb 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0VH08    | Notebook    | [fa2cd8964e](https://bsd-hardware.info/?probe=fa2cd8964e) | Feb 17, 2022 |
| Samsung       | N100                        | Notebook    | [3125d76ba4](https://bsd-hardware.info/?probe=3125d76ba4) | Feb 16, 2022 |
| Lenovo        | E31-80 80MX                 | Notebook    | [098afac660](https://bsd-hardware.info/?probe=098afac660) | Feb 16, 2022 |
| Lenovo        | ThinkPad T430 2349AK1       | Notebook    | [86fd351c81](https://bsd-hardware.info/?probe=86fd351c81) | Feb 16, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [3a72227408](https://bsd-hardware.info/?probe=3a72227408) | Feb 16, 2022 |
| Gigabyte      | C246M-WU4-CF                | Desktop     | [4b6c6d8bde](https://bsd-hardware.info/?probe=4b6c6d8bde) | Feb 15, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [df6278638e](https://bsd-hardware.info/?probe=df6278638e) | Feb 15, 2022 |
| Acer          | V5-131                      | Notebook    | [2d5bfae3b4](https://bsd-hardware.info/?probe=2d5bfae3b4) | Feb 15, 2022 |
| ASRock        | H61M/U3S3                   | Desktop     | [257e13f206](https://bsd-hardware.info/?probe=257e13f206) | Feb 12, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [abf34bbc7e](https://bsd-hardware.info/?probe=abf34bbc7e) | Feb 12, 2022 |
| ASRock        | H61M/U3S3                   | Desktop     | [34dac4c0cd](https://bsd-hardware.info/?probe=34dac4c0cd) | Feb 11, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [6997de25f9](https://bsd-hardware.info/?probe=6997de25f9) | Feb 11, 2022 |
| ASUSTek       | X555LA                      | Notebook    | [28b3002182](https://bsd-hardware.info/?probe=28b3002182) | Feb 10, 2022 |
| ASUSTek       | X555LA                      | Notebook    | [9aa18b2e33](https://bsd-hardware.info/?probe=9aa18b2e33) | Feb 09, 2022 |
| Intel         | X58                         | Desktop     | [f7075908f6](https://bsd-hardware.info/?probe=f7075908f6) | Feb 09, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [b1931633be](https://bsd-hardware.info/?probe=b1931633be) | Feb 09, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [f9c1e787a9](https://bsd-hardware.info/?probe=f9c1e787a9) | Feb 09, 2022 |
| MSI           | B75A-G43                    | Desktop     | [8e445eb2d4](https://bsd-hardware.info/?probe=8e445eb2d4) | Feb 08, 2022 |
| Acer          | Aspire E5-511G              | Notebook    | [b14c4c1ac5](https://bsd-hardware.info/?probe=b14c4c1ac5) | Feb 07, 2022 |
| TWINHEAD      | U12CT                       | Notebook    | [32247012ca](https://bsd-hardware.info/?probe=32247012ca) | Feb 06, 2022 |
| ASUSTek       | P6-P8H61E                   | Desktop     | [e838981914](https://bsd-hardware.info/?probe=e838981914) | Feb 06, 2022 |
| Dell          | Latitude D630               | Notebook    | [b34db656b5](https://bsd-hardware.info/?probe=b34db656b5) | Feb 05, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | Notebook    | [a6c02e440b](https://bsd-hardware.info/?probe=a6c02e440b) | Feb 05, 2022 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [328f9e8d94](https://bsd-hardware.info/?probe=328f9e8d94) | Feb 04, 2022 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [8af8b5270e](https://bsd-hardware.info/?probe=8af8b5270e) | Feb 04, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [d8fb34de12](https://bsd-hardware.info/?probe=d8fb34de12) | Feb 04, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [e5043f0af4](https://bsd-hardware.info/?probe=e5043f0af4) | Feb 04, 2022 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [bf63607cd6](https://bsd-hardware.info/?probe=bf63607cd6) | Feb 03, 2022 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [342915fccd](https://bsd-hardware.info/?probe=342915fccd) | Feb 03, 2022 |
| Lenovo        | ThinkPad X220 4291H77       | Notebook    | [dd4d3a9dcc](https://bsd-hardware.info/?probe=dd4d3a9dcc) | Feb 02, 2022 |
| Pegatron      | NARRA5                      | Desktop     | [64d4fb9b97](https://bsd-hardware.info/?probe=64d4fb9b97) | Feb 02, 2022 |
| HP            | Mini 210-1000               | Notebook    | [8a8bfdaee1](https://bsd-hardware.info/?probe=8a8bfdaee1) | Feb 02, 2022 |
| HP            | G62                         | Notebook    | [476193bfd0](https://bsd-hardware.info/?probe=476193bfd0) | Feb 01, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [ee05643521](https://bsd-hardware.info/?probe=ee05643521) | Feb 01, 2022 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [5999e0ebfb](https://bsd-hardware.info/?probe=5999e0ebfb) | Jan 31, 2022 |
| Lenovo        | ThinkPad T510 4384AJ6       | Notebook    | [70a56029e7](https://bsd-hardware.info/?probe=70a56029e7) | Jan 31, 2022 |
| Intel         | H81                         | Desktop     | [c2f3025900](https://bsd-hardware.info/?probe=c2f3025900) | Jan 31, 2022 |
| HP            | Laptop 15-rb0xx             | Notebook    | [8e9a6cff62](https://bsd-hardware.info/?probe=8e9a6cff62) | Jan 31, 2022 |
| Pegatron      | 2A99h                       | Desktop     | [e34b6118a2](https://bsd-hardware.info/?probe=e34b6118a2) | Jan 30, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [58ea01e4e6](https://bsd-hardware.info/?probe=58ea01e4e6) | Jan 29, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [e89404ebed](https://bsd-hardware.info/?probe=e89404ebed) | Jan 29, 2022 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [901a483718](https://bsd-hardware.info/?probe=901a483718) | Jan 29, 2022 |
| Intel         | DH77EB AAG39073-400         | Desktop     | [bfe6ef301b](https://bsd-hardware.info/?probe=bfe6ef301b) | Jan 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ee6e794728](https://bsd-hardware.info/?probe=ee6e794728) | Jan 29, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [754db09c98](https://bsd-hardware.info/?probe=754db09c98) | Jan 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [11bbfce5d4](https://bsd-hardware.info/?probe=11bbfce5d4) | Jan 27, 2022 |
| ASUSTek       | P5GC-MX                     | Desktop     | [372749f9d7](https://bsd-hardware.info/?probe=372749f9d7) | Jan 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [a9d799ca71](https://bsd-hardware.info/?probe=a9d799ca71) | Jan 27, 2022 |
| Dell          | Latitude 7280               | Notebook    | [089b61bb38](https://bsd-hardware.info/?probe=089b61bb38) | Jan 27, 2022 |
| ASUSTek       | P5B SE                      | Desktop     | [f97fba19c1](https://bsd-hardware.info/?probe=f97fba19c1) | Jan 26, 2022 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [2506316700](https://bsd-hardware.info/?probe=2506316700) | Jan 26, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [b1d702812e](https://bsd-hardware.info/?probe=b1d702812e) | Jan 26, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [9f0a000ceb](https://bsd-hardware.info/?probe=9f0a000ceb) | Jan 25, 2022 |
| MSI           | GE75 Raider 10SFS           | Notebook    | [306f312c47](https://bsd-hardware.info/?probe=306f312c47) | Jan 25, 2022 |
| ASUSTek       | P5B SE                      | Desktop     | [e3332e7b94](https://bsd-hardware.info/?probe=e3332e7b94) | Jan 25, 2022 |
| ASRock        | B460M Pro4                  | Desktop     | [107a1e59f5](https://bsd-hardware.info/?probe=107a1e59f5) | Jan 25, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [8edf072b67](https://bsd-hardware.info/?probe=8edf072b67) | Jan 25, 2022 |
| ASUSTek       | BM6835_BM6635_BP6335        | Desktop     | [73562aa169](https://bsd-hardware.info/?probe=73562aa169) | Jan 25, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [df08e2e8f0](https://bsd-hardware.info/?probe=df08e2e8f0) | Jan 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1c8f50f7eb](https://bsd-hardware.info/?probe=1c8f50f7eb) | Jan 24, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [fb73c2f7dc](https://bsd-hardware.info/?probe=fb73c2f7dc) | Jan 23, 2022 |
| HP            | 1998                        | Desktop     | [b59dbcdc9c](https://bsd-hardware.info/?probe=b59dbcdc9c) | Jan 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7859f220b9](https://bsd-hardware.info/?probe=7859f220b9) | Jan 22, 2022 |
| Acer          | Aspire ES1-311              | Notebook    | [83addddaa5](https://bsd-hardware.info/?probe=83addddaa5) | Jan 22, 2022 |
| Dell          | Latitude E6540              | Notebook    | [529768f8c8](https://bsd-hardware.info/?probe=529768f8c8) | Jan 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [670e41ed41](https://bsd-hardware.info/?probe=670e41ed41) | Jan 21, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [04abd226f3](https://bsd-hardware.info/?probe=04abd226f3) | Jan 21, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [4d04ececbb](https://bsd-hardware.info/?probe=4d04ececbb) | Jan 19, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [a780a7bab2](https://bsd-hardware.info/?probe=a780a7bab2) | Jan 18, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [384d2f888b](https://bsd-hardware.info/?probe=384d2f888b) | Jan 18, 2022 |
| Acer          | V5-131                      | Notebook    | [ff427cb0c9](https://bsd-hardware.info/?probe=ff427cb0c9) | Jan 18, 2022 |
| Gateway       | NE56R                       | Notebook    | [a5aa8aa49a](https://bsd-hardware.info/?probe=a5aa8aa49a) | Jan 18, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [9cd2758a5f](https://bsd-hardware.info/?probe=9cd2758a5f) | Jan 18, 2022 |
| Lenovo        | ThinkPad T410 2522E38       | Notebook    | [2dbb2679f1](https://bsd-hardware.info/?probe=2dbb2679f1) | Jan 17, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [e795c7ec91](https://bsd-hardware.info/?probe=e795c7ec91) | Jan 17, 2022 |
| Lenovo        | ThinkPad T440 20B7000PHV    | Notebook    | [9584ae69fa](https://bsd-hardware.info/?probe=9584ae69fa) | Jan 16, 2022 |
| Lenovo        | ThinkPad R61 8935WCS        | Notebook    | [9cc0f26f6f](https://bsd-hardware.info/?probe=9cc0f26f6f) | Jan 16, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [3dead218e1](https://bsd-hardware.info/?probe=3dead218e1) | Jan 16, 2022 |
| Gigabyte      | B365 HD3                    | Desktop     | [62fc48bd99](https://bsd-hardware.info/?probe=62fc48bd99) | Jan 15, 2022 |
| Dell          | 0XCR8D A03                  | Desktop     | [48e9447b37](https://bsd-hardware.info/?probe=48e9447b37) | Jan 15, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [d377e06101](https://bsd-hardware.info/?probe=d377e06101) | Jan 15, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [5a585443b2](https://bsd-hardware.info/?probe=5a585443b2) | Jan 15, 2022 |
| Acer          | V5-131                      | Notebook    | [e4d0f66ff8](https://bsd-hardware.info/?probe=e4d0f66ff8) | Jan 13, 2022 |
| Gigabyte      | Z77N-WIFI                   | Desktop     | [459bb6486d](https://bsd-hardware.info/?probe=459bb6486d) | Jan 13, 2022 |
| Acer          | Aspire ES1-533              | Notebook    | [a9d2458de5](https://bsd-hardware.info/?probe=a9d2458de5) | Jan 13, 2022 |
| Acer          | Aspire E5-476G              | Notebook    | [2a8624ee35](https://bsd-hardware.info/?probe=2a8624ee35) | Jan 10, 2022 |
| ASUSTek       | P8Z68-M PRO                 | Desktop     | [a0885f4f44](https://bsd-hardware.info/?probe=a0885f4f44) | Jan 10, 2022 |
| HP            | 8169                        | Desktop     | [85e0cf058c](https://bsd-hardware.info/?probe=85e0cf058c) | Jan 10, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | Notebook    | [3c27c8bf31](https://bsd-hardware.info/?probe=3c27c8bf31) | Jan 09, 2022 |
| Dell          | Latitude E6530              | Notebook    | [0fa21bcf23](https://bsd-hardware.info/?probe=0fa21bcf23) | Jan 09, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [8d4b342fda](https://bsd-hardware.info/?probe=8d4b342fda) | Jan 08, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [8cbe3d4581](https://bsd-hardware.info/?probe=8cbe3d4581) | Jan 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [7aea2ccaa7](https://bsd-hardware.info/?probe=7aea2ccaa7) | Jan 08, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MX     | Notebook    | [0fa4700d17](https://bsd-hardware.info/?probe=0fa4700d17) | Jan 07, 2022 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [e7b40f6e3b](https://bsd-hardware.info/?probe=e7b40f6e3b) | Jan 06, 2022 |
| ASUSTek       | GA35DX                      | Desktop     | [eccb947ae4](https://bsd-hardware.info/?probe=eccb947ae4) | Jan 05, 2022 |
| Notebook      | N15_17RD                    | Notebook    | [47c30b962d](https://bsd-hardware.info/?probe=47c30b962d) | Jan 05, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | Notebook    | [bf95cdeb53](https://bsd-hardware.info/?probe=bf95cdeb53) | Jan 04, 2022 |
| Unknown       | G31T-M7                     | Desktop     | [ed7d80e01a](https://bsd-hardware.info/?probe=ed7d80e01a) | Jan 03, 2022 |
| Dell          | Latitude 7380               | Notebook    | [590b374836](https://bsd-hardware.info/?probe=590b374836) | Jan 02, 2022 |
| Dell          | Latitude E6540              | Notebook    | [f5a43a9f8b](https://bsd-hardware.info/?probe=f5a43a9f8b) | Jan 02, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [4979175779](https://bsd-hardware.info/?probe=4979175779) | Jan 01, 2022 |
| Lenovo        | ThinkPad X220 4293AF4       | Notebook    | [8c7992e557](https://bsd-hardware.info/?probe=8c7992e557) | Jan 01, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [a671e3eb04](https://bsd-hardware.info/?probe=a671e3eb04) | Dec 31, 2021 |
| Dell          | Latitude E6540              | Notebook    | [97d152656e](https://bsd-hardware.info/?probe=97d152656e) | Dec 31, 2021 |
| HP            | ProBook 655 G1              | Notebook    | [da312d7c14](https://bsd-hardware.info/?probe=da312d7c14) | Dec 30, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [b77a4ee97c](https://bsd-hardware.info/?probe=b77a4ee97c) | Dec 30, 2021 |
| ASUSTek       | S550CA                      | Notebook    | [1263a5fb37](https://bsd-hardware.info/?probe=1263a5fb37) | Dec 29, 2021 |
| Lenovo        | ThinkPad E580 20KS005BRI    | Notebook    | [b533989df5](https://bsd-hardware.info/?probe=b533989df5) | Dec 29, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [15211db056](https://bsd-hardware.info/?probe=15211db056) | Dec 28, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [b246d110af](https://bsd-hardware.info/?probe=b246d110af) | Dec 28, 2021 |
| Dell          | 0200DY A01                  | Desktop     | [fb37dcbb93](https://bsd-hardware.info/?probe=fb37dcbb93) | Dec 28, 2021 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [07221fc111](https://bsd-hardware.info/?probe=07221fc111) | Dec 28, 2021 |
| Pegatron      | IPM41-D3                    | Desktop     | [6829928dad](https://bsd-hardware.info/?probe=6829928dad) | Dec 28, 2021 |
| Dell          | 0H9KW5 A00                  | Desktop     | [e962ca25b3](https://bsd-hardware.info/?probe=e962ca25b3) | Dec 28, 2021 |
| Lenovo        | ThinkPad T460 20FMS75800    | Notebook    | [5f17e74f2f](https://bsd-hardware.info/?probe=5f17e74f2f) | Dec 27, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [0918f0a5b9](https://bsd-hardware.info/?probe=0918f0a5b9) | Dec 25, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [b0aa3885bb](https://bsd-hardware.info/?probe=b0aa3885bb) | Dec 25, 2021 |
| ASUSTek       | Z170-P                      | Desktop     | [bde74629f9](https://bsd-hardware.info/?probe=bde74629f9) | Dec 25, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [b650885b00](https://bsd-hardware.info/?probe=b650885b00) | Dec 24, 2021 |
| Apple         | Mac-F2218EA9                | All in one  | [ea002bb42a](https://bsd-hardware.info/?probe=ea002bb42a) | Dec 24, 2021 |
| Acer          | TravelMate 5760G            | Notebook    | [46204b90d0](https://bsd-hardware.info/?probe=46204b90d0) | Dec 24, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [8ac48ba9c3](https://bsd-hardware.info/?probe=8ac48ba9c3) | Dec 23, 2021 |
| Lenovo        | ThinkPad SL510 2847R96      | Notebook    | [b0a9802877](https://bsd-hardware.info/?probe=b0a9802877) | Dec 22, 2021 |
| Lenovo        | ThinkPad T410 2537EA8       | Notebook    | [8b457cd635](https://bsd-hardware.info/?probe=8b457cd635) | Dec 22, 2021 |
| Gigabyte      | E3000N                      | Desktop     | [eb0ba1b296](https://bsd-hardware.info/?probe=eb0ba1b296) | Dec 22, 2021 |
| Lenovo        | ThinkPad X250 20CLS1WP01    | Notebook    | [87bc0b8924](https://bsd-hardware.info/?probe=87bc0b8924) | Dec 22, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [6b03a2c4c2](https://bsd-hardware.info/?probe=6b03a2c4c2) | Dec 22, 2021 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [936afa4de3](https://bsd-hardware.info/?probe=936afa4de3) | Dec 21, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [5188a12b26](https://bsd-hardware.info/?probe=5188a12b26) | Dec 21, 2021 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [839eed529d](https://bsd-hardware.info/?probe=839eed529d) | Dec 21, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [42599b554e](https://bsd-hardware.info/?probe=42599b554e) | Dec 21, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [2e1c585715](https://bsd-hardware.info/?probe=2e1c585715) | Dec 21, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [73076dd5de](https://bsd-hardware.info/?probe=73076dd5de) | Dec 21, 2021 |
| Gigabyte      | X58A-UD5                    | Desktop     | [62b94dd372](https://bsd-hardware.info/?probe=62b94dd372) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [5cc62c68f9](https://bsd-hardware.info/?probe=5cc62c68f9) | Dec 21, 2021 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [a490614a39](https://bsd-hardware.info/?probe=a490614a39) | Dec 21, 2021 |
| ASRock        | H110M-DGS                   | Desktop     | [40c4553adb](https://bsd-hardware.info/?probe=40c4553adb) | Dec 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4c22212c20](https://bsd-hardware.info/?probe=4c22212c20) | Dec 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1a193c7bf9](https://bsd-hardware.info/?probe=1a193c7bf9) | Dec 20, 2021 |
| Toshiba       | Satellite L550              | Notebook    | [977298a601](https://bsd-hardware.info/?probe=977298a601) | Dec 20, 2021 |
| ASUSTek       | N56VB                       | Notebook    | [f53b3fba5c](https://bsd-hardware.info/?probe=f53b3fba5c) | Dec 20, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [1e888f2278](https://bsd-hardware.info/?probe=1e888f2278) | Dec 20, 2021 |
| ASUSTek       | P5VD2-VM                    | Desktop     | [7e8f3cf783](https://bsd-hardware.info/?probe=7e8f3cf783) | Dec 20, 2021 |
| ASUSTek       | Q170M-C                     | Desktop     | [7f9e35a31c](https://bsd-hardware.info/?probe=7f9e35a31c) | Dec 20, 2021 |
| Dell          | 0TDG4V A00                  | Desktop     | [3ce808c135](https://bsd-hardware.info/?probe=3ce808c135) | Dec 20, 2021 |
| Dell          | 0TDG4V A00                  | Desktop     | [5292ad64ef](https://bsd-hardware.info/?probe=5292ad64ef) | Dec 20, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [6321f4bd3a](https://bsd-hardware.info/?probe=6321f4bd3a) | Dec 20, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [3c71a8ba4e](https://bsd-hardware.info/?probe=3c71a8ba4e) | Dec 20, 2021 |
| Dell          | Latitude E5470              | Notebook    | [18470afd9d](https://bsd-hardware.info/?probe=18470afd9d) | Dec 19, 2021 |
| Apple         | Mac-F2218EA9                | All in one  | [510b7cb091](https://bsd-hardware.info/?probe=510b7cb091) | Dec 19, 2021 |
| MSI           | X370 SLI PLUS               | Desktop     | [73853f1fc2](https://bsd-hardware.info/?probe=73853f1fc2) | Dec 19, 2021 |
| Quanta        | 2AC7 011                    | Desktop     | [1a831a1d34](https://bsd-hardware.info/?probe=1a831a1d34) | Dec 18, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [7daf32eb4f](https://bsd-hardware.info/?probe=7daf32eb4f) | Dec 17, 2021 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [759ce775c9](https://bsd-hardware.info/?probe=759ce775c9) | Dec 15, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [32d20b9b8e](https://bsd-hardware.info/?probe=32d20b9b8e) | Dec 14, 2021 |
| HP            | ZBook Studio G4             | Notebook    | [cdc6f54d97](https://bsd-hardware.info/?probe=cdc6f54d97) | Dec 14, 2021 |
| HP            | 843B                        | Desktop     | [f0d279747f](https://bsd-hardware.info/?probe=f0d279747f) | Dec 13, 2021 |
| HP            | 843B                        | Desktop     | [56400d3999](https://bsd-hardware.info/?probe=56400d3999) | Dec 13, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [aea4a33dee](https://bsd-hardware.info/?probe=aea4a33dee) | Dec 13, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [50fba6deda](https://bsd-hardware.info/?probe=50fba6deda) | Dec 11, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [6a1100cfdb](https://bsd-hardware.info/?probe=6a1100cfdb) | Dec 11, 2021 |
| Acer          | RevoOne RL85                | Desktop     | [a1e32de7da](https://bsd-hardware.info/?probe=a1e32de7da) | Dec 10, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [b900b364f6](https://bsd-hardware.info/?probe=b900b364f6) | Dec 10, 2021 |
| Dell          | 0YF8P5 A00                  | Desktop     | [0f03a66475](https://bsd-hardware.info/?probe=0f03a66475) | Dec 09, 2021 |
| Dell          | 0YF8P5 A00                  | Desktop     | [83b36f7c3d](https://bsd-hardware.info/?probe=83b36f7c3d) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [a084ff48c2](https://bsd-hardware.info/?probe=a084ff48c2) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [17b557d792](https://bsd-hardware.info/?probe=17b557d792) | Dec 08, 2021 |
| Apple         | MacBookAir1,1               | Notebook    | [61c7028e83](https://bsd-hardware.info/?probe=61c7028e83) | Dec 07, 2021 |
| ASUSTek       | X540LA                      | Notebook    | [fa809be73f](https://bsd-hardware.info/?probe=fa809be73f) | Dec 04, 2021 |
| ASUSTek       | X540LA                      | Notebook    | [cf5fd87781](https://bsd-hardware.info/?probe=cf5fd87781) | Dec 04, 2021 |
| Acer          | Swift SF314-52              | Notebook    | [e3ece211a0](https://bsd-hardware.info/?probe=e3ece211a0) | Dec 03, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [8cfe11fe93](https://bsd-hardware.info/?probe=8cfe11fe93) | Nov 30, 2021 |
| HP            | 843B                        | Desktop     | [376e006a40](https://bsd-hardware.info/?probe=376e006a40) | Nov 30, 2021 |
| Intel         | DG41TY AAE47335-300         | Desktop     | [dd357bcaa5](https://bsd-hardware.info/?probe=dd357bcaa5) | Nov 30, 2021 |
| HP            | 843B                        | Desktop     | [404224439d](https://bsd-hardware.info/?probe=404224439d) | Nov 29, 2021 |
| HP            | 843B                        | Desktop     | [a8ac0e9efb](https://bsd-hardware.info/?probe=a8ac0e9efb) | Nov 29, 2021 |
| Toshiba       | Satellite S55t-B            | Notebook    | [f6983391aa](https://bsd-hardware.info/?probe=f6983391aa) | Nov 28, 2021 |
| HP            | 1825                        | Desktop     | [32f07d2ba3](https://bsd-hardware.info/?probe=32f07d2ba3) | Nov 28, 2021 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | Notebook    | [66cfdd2419](https://bsd-hardware.info/?probe=66cfdd2419) | Nov 27, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [4cd5e5166a](https://bsd-hardware.info/?probe=4cd5e5166a) | Nov 27, 2021 |
| Apple         | Mac-F2218FA9                | All in one  | [7154bea350](https://bsd-hardware.info/?probe=7154bea350) | Nov 27, 2021 |
| ASRock        | 775i945GZ                   | Desktop     | [16fc4ee10d](https://bsd-hardware.info/?probe=16fc4ee10d) | Nov 26, 2021 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [f5421b8fe0](https://bsd-hardware.info/?probe=f5421b8fe0) | Nov 23, 2021 |
| Apple         | Mac-F2218FA9                | All in one  | [1802f6c891](https://bsd-hardware.info/?probe=1802f6c891) | Nov 21, 2021 |
| Toshiba       | Satellite C640              | Notebook    | [2d60f00479](https://bsd-hardware.info/?probe=2d60f00479) | Nov 17, 2021 |
| Toshiba       | Satellite C640              | Notebook    | [89a9551487](https://bsd-hardware.info/?probe=89a9551487) | Nov 17, 2021 |
| Lenovo        | ThinkPad T60 1951FEG        | Notebook    | [e2d5391a1a](https://bsd-hardware.info/?probe=e2d5391a1a) | Nov 14, 2021 |
| ASUSTek       | K52Jc                       | Notebook    | [92b975763f](https://bsd-hardware.info/?probe=92b975763f) | Nov 08, 2021 |
| HP            | 844C                        | Desktop     | [fb7d8eaf5d](https://bsd-hardware.info/?probe=fb7d8eaf5d) | Nov 06, 2021 |
| Unknown       | X79                         | Desktop     | [ef88cbc606](https://bsd-hardware.info/?probe=ef88cbc606) | Nov 05, 2021 |
| Apple         | MacBookAir5,1               | Notebook    | [10d629e1a0](https://bsd-hardware.info/?probe=10d629e1a0) | Nov 04, 2021 |
| HP            | 843B                        | Desktop     | [9761f29b5e](https://bsd-hardware.info/?probe=9761f29b5e) | Oct 25, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3c64328fbe](https://bsd-hardware.info/?probe=3c64328fbe) | Oct 13, 2021 |
| Acer          | Aspire TC-780               | Desktop     | [3ce8481842](https://bsd-hardware.info/?probe=3ce8481842) | Oct 10, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 276       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 274       | 99.28%  |
| GNOME        | 2         | 0.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 276       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 276       | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 262       | 94.93%  |
| de_DE | 4         | 1.45%   |
| es_ES | 3         | 1.09%   |
| C     | 3         | 1.09%   |
| fr_FR | 2         | 0.72%   |
| uk_UA | 1         | 0.36%   |
| it_IT | 1         | 0.36%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 268       | 97.1%   |
| BIOS | 8         | 2.9%    |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Cd9660 | 165       | 58.51%  |
| Zfs    | 117       | 41.49%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 271       | 98.19%  |
| MBR  | 5         | 1.81%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 49        | 17.75%  |
| Lenovo              | 43        | 15.58%  |
| Hewlett-Packard     | 29        | 10.51%  |
| Dell                | 27        | 9.78%   |
| Gigabyte Technology | 25        | 9.06%   |
| Apple               | 16        | 5.8%    |
| Acer                | 14        | 5.07%   |
| Intel               | 13        | 4.71%   |
| ASRock              | 12        | 4.35%   |
| MSI                 | 7         | 2.54%   |
| Toshiba             | 5         | 1.81%   |
| Unknown             | 4         | 1.45%   |
| TUXEDO              | 3         | 1.09%   |
| Samsung Electronics | 3         | 1.09%   |
| Pegatron            | 3         | 1.09%   |
| Sony                | 2         | 0.72%   |
| TWINHEAD            | 1         | 0.36%   |
| T-bao               | 1         | 0.36%   |
| Supermicro          | 1         | 0.36%   |
| Razer               | 1         | 0.36%   |
| Quanta              | 1         | 0.36%   |
| Positivo            | 1         | 0.36%   |
| Panasonic           | 1         | 0.36%   |
| Packard Bell        | 1         | 0.36%   |
| OEM                 | 1         | 0.36%   |
| Notebook            | 1         | 0.36%   |
| Medion              | 1         | 0.36%   |
| LG Electronics      | 1         | 0.36%   |
| Koloe               | 1         | 0.36%   |
| Itautec             | 1         | 0.36%   |
| HASEE Computer      | 1         | 0.36%   |
| Gateway             | 1         | 0.36%   |
| Fujitsu             | 1         | 0.36%   |
| ECS                 | 1         | 0.36%   |
| DNS                 | 1         | 0.36%   |
| BESSTAR Tech        | 1         | 0.36%   |
| Acidanthera         | 1         | 0.36%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                               | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Apple iMac9,1                                      | 5         | 1.81%   |
| Unknown                                            | 4         | 1.45%   |
| TUXEDO Aura 15 Gen1                                | 2         | 0.72%   |
| HP EliteDesk 700 G1 SFF                            | 2         | 0.72%   |
| Dell Precision T1700                               | 2         | 0.72%   |
| Dell Latitude E5470                                | 2         | 0.72%   |
| ASUS TUF GAMING X570-PLUS                          | 2         | 0.72%   |
| ASUS PRIME X570-P                                  | 2         | 0.72%   |
| ASUS P8Z77-V LX                                    | 2         | 0.72%   |
| ASRock X570 Phantom Gaming 4                       | 2         | 0.72%   |
| Apple MacBook4,1                                   | 2         | 0.72%   |
| Acer V5-131                                        | 2         | 0.72%   |
| TWINHEAD U12CT                                     | 1         | 0.36%   |
| TUXEDO InfinityBook13V3                            | 1         | 0.36%   |
| Toshiba Satellite S55t-B                           | 1         | 0.36%   |
| Toshiba Satellite P300                             | 1         | 0.36%   |
| Toshiba Satellite L550                             | 1         | 0.36%   |
| Toshiba Satellite C640                             | 1         | 0.36%   |
| Toshiba Satellite C50-B                            | 1         | 0.36%   |
| T-bao MINI PC                                      | 1         | 0.36%   |
| Supermicro X9DAL                                   | 1         | 0.36%   |
| Sony VGN-NW25GF_S                                  | 1         | 0.36%   |
| Sony SVZ1311C5E                                    | 1         | 0.36%   |
| Samsung N150P/N210P/N220P                          | 1         | 0.36%   |
| Samsung N100                                       | 1         | 0.36%   |
| Samsung 305E4A/305E5A/305E7A                       | 1         | 0.36%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.36%   |
| Quanta 120-1135                                    | 1         | 0.36%   |
| Positivo POS-PIQ77CL                               | 1         | 0.36%   |
| Pegatron IPM41-D3                                  | 1         | 0.36%   |
| Pegatron Compaq 505B Microtower PC                 | 1         | 0.36%   |
| Pegatron AY627AA-ABA a4313w                        | 1         | 0.36%   |
| Panasonic CF-B11JWCYS                              | 1         | 0.36%   |
| Packard Bell EasyNote TE69HW                       | 1         | 0.36%   |
| OEM B85 JHS359                                     | 1         | 0.36%   |
| Notebook N15_17RD                                  | 1         | 0.36%   |
| MSI MS-7D25                                        | 1         | 0.36%   |
| MSI MS-7B86                                        | 1         | 0.36%   |
| MSI MS-7A33                                        | 1         | 0.36%   |
| MSI MS-7816                                        | 1         | 0.36%   |
| MSI MS-7758                                        | 1         | 0.36%   |
| MSI MS-7369                                        | 1         | 0.36%   |
| MSI GF65 Thin 10SER                                | 1         | 0.36%   |
| Medion H61H2-LM3                                   | 1         | 0.36%   |
| LG E300-A.CP20T                                    | 1         | 0.36%   |
| Lenovo Z50-70 20354                                | 1         | 0.36%   |
| Lenovo YangTianA8800T                              | 1         | 0.36%   |
| Lenovo V310-14IKB 80T2                             | 1         | 0.36%   |
| Lenovo ThinkPad X61 7675K2U                        | 1         | 0.36%   |
| Lenovo ThinkPad X270 W10DG 20K5S0BM01              | 1         | 0.36%   |
| Lenovo ThinkPad X250 20CLS1WP01                    | 1         | 0.36%   |
| Lenovo ThinkPad X240 20AMS2QDOC                    | 1         | 0.36%   |
| Lenovo ThinkPad X220 Tablet 4298B65                | 1         | 0.36%   |
| Lenovo ThinkPad X220 Tablet 42962WU                | 1         | 0.36%   |
| Lenovo ThinkPad X220 4293B43                       | 1         | 0.36%   |
| Lenovo ThinkPad X220 4293AF4                       | 1         | 0.36%   |
| Lenovo ThinkPad X220 4291H77                       | 1         | 0.36%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRS04C00           | 1         | 0.36%   |
| Lenovo ThinkPad T61 766301U                        | 1         | 0.36%   |
| Lenovo ThinkPad T60 1951FEG                        | 1         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 26        | 9.42%   |
| Dell Latitude           | 9         | 3.26%   |
| ASUS PRIME              | 9         | 3.26%   |
| Acer Aspire             | 9         | 3.26%   |
| HP Pavilion             | 7         | 2.54%   |
| Lenovo IdeaPad          | 6         | 2.17%   |
| Dell OptiPlex           | 6         | 2.17%   |
| Dell Inspiron           | 6         | 2.17%   |
| Toshiba Satellite       | 5         | 1.81%   |
| ASUS ROG                | 5         | 1.81%   |
| Apple iMac9             | 5         | 1.81%   |
| HP EliteDesk            | 4         | 1.45%   |
| ASUS TUF                | 4         | 1.45%   |
| Unknown                 | 4         | 1.45%   |
| HP Laptop               | 3         | 1.09%   |
| HP EliteBook            | 3         | 1.09%   |
| TUXEDO Aura             | 2         | 0.72%   |
| Lenovo ThinkCentre      | 2         | 0.72%   |
| HP ProBook              | 2         | 0.72%   |
| HP Compaq               | 2         | 0.72%   |
| Gigabyte B450           | 2         | 0.72%   |
| Dell Vostro             | 2         | 0.72%   |
| Dell Precision          | 2         | 0.72%   |
| ASUS P8Z77-V            | 2         | 0.72%   |
| ASRock X570             | 2         | 0.72%   |
| Apple MacBook4          | 2         | 0.72%   |
| Acer V5-131             | 2         | 0.72%   |
| TWINHEAD U12CT          | 1         | 0.36%   |
| TUXEDO InfinityBook13V3 | 1         | 0.36%   |
| T-bao MINI              | 1         | 0.36%   |
| Supermicro X9DAL        | 1         | 0.36%   |
| Sony VGN-NW25GF         | 1         | 0.36%   |
| Sony SVZ1311C5E         | 1         | 0.36%   |
| Samsung N150P           | 1         | 0.36%   |
| Samsung N100            | 1         | 0.36%   |
| Samsung 305E4A          | 1         | 0.36%   |
| Razer Blade             | 1         | 0.36%   |
| Quanta 120-1135         | 1         | 0.36%   |
| Positivo POS-PIQ77CL    | 1         | 0.36%   |
| Pegatron IPM41-D3       | 1         | 0.36%   |
| Pegatron Compaq         | 1         | 0.36%   |
| Pegatron AY627AA-ABA    | 1         | 0.36%   |
| Panasonic CF-B11JWCYS   | 1         | 0.36%   |
| Packard Bell EasyNote   | 1         | 0.36%   |
| OEM B85                 | 1         | 0.36%   |
| Notebook N15            | 1         | 0.36%   |
| MSI MS-7D25             | 1         | 0.36%   |
| MSI MS-7B86             | 1         | 0.36%   |
| MSI MS-7A33             | 1         | 0.36%   |
| MSI MS-7816             | 1         | 0.36%   |
| MSI MS-7758             | 1         | 0.36%   |
| MSI MS-7369             | 1         | 0.36%   |
| MSI GF65                | 1         | 0.36%   |
| Medion H61H2-LM3        | 1         | 0.36%   |
| LG E300-A.CP20T         | 1         | 0.36%   |
| Lenovo Z50-70           | 1         | 0.36%   |
| Lenovo YangTianA8800T   | 1         | 0.36%   |
| Lenovo V310-14IKB       | 1         | 0.36%   |
| Lenovo ThinkBook        | 1         | 0.36%   |
| Lenovo Legion           | 1         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 32        | 11.59%  |
| 2018    | 25        | 9.06%   |
| 2019    | 24        | 8.7%    |
| 2013    | 22        | 7.97%   |
| 2012    | 22        | 7.97%   |
| 2009    | 22        | 7.97%   |
| 2020    | 19        | 6.88%   |
| 2010    | 18        | 6.52%   |
| 2015    | 17        | 6.16%   |
| 2017    | 16        | 5.8%    |
| 2016    | 15        | 5.43%   |
| 2011    | 15        | 5.43%   |
| 2014    | 14        | 5.07%   |
| 2008    | 7         | 2.54%   |
| 2007    | 6         | 2.17%   |
| 2006    | 1         | 0.36%   |
| Unknown | 1         | 0.36%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 129       | 46.74%  |
| Desktop    | 127       | 46.01%  |
| Mini pc    | 11        | 3.99%   |
| All in one | 9         | 3.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 276       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 83        | 30.07%  |
| 4.01-8.0    | 79        | 28.62%  |
| 16.01-24.0  | 63        | 22.83%  |
| 32.01-64.0  | 22        | 7.97%   |
| 2.01-3.0    | 14        | 5.07%   |
| 64.01-256.0 | 7         | 2.54%   |
| 24.01-32.0  | 4         | 1.45%   |
| 3.01-4.0    | 2         | 0.72%   |
| 1.01-2.0    | 1         | 0.36%   |
| 0.51-1.0    | 1         | 0.36%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 147       | 53.07%  |
| 0.51-1.0  | 85        | 30.69%  |
| 1.01-2.0  | 36        | 13%     |
| 2.01-3.0  | 7         | 2.53%   |
| 3.01-4.0  | 1         | 0.36%   |
| 8.01-16.0 | 1         | 0.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 169       | 60.57%  |
| 2      | 66        | 23.66%  |
| 0      | 13        | 4.66%   |
| 3      | 12        | 4.3%    |
| 4      | 11        | 3.94%   |
| 5      | 4         | 1.43%   |
| 6      | 2         | 0.72%   |
| 9      | 1         | 0.36%   |
| 7      | 1         | 0.36%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 166       | 60.14%  |
| Yes       | 110       | 39.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 265       | 96.01%  |
| No        | 11        | 3.99%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 189       | 68.48%  |
| No        | 87        | 31.52%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 138       | 50%     |
| No        | 138       | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country             | Computers | Percent |
|---------------------|-----------|---------|
| USA                 | 43        | 15.58%  |
| Russia              | 31        | 11.23%  |
| Germany             | 19        | 6.88%   |
| Italy               | 14        | 5.07%   |
| Brazil              | 13        | 4.71%   |
| Spain               | 12        | 4.35%   |
| Ukraine             | 10        | 3.62%   |
| China               | 10        | 3.62%   |
| Canada              | 10        | 3.62%   |
| UK                  | 9         | 3.26%   |
| Poland              | 9         | 3.26%   |
| Hungary             | 9         | 3.26%   |
| France              | 7         | 2.54%   |
| Romania             | 6         | 2.17%   |
| Turkey              | 5         | 1.81%   |
| Mexico              | 5         | 1.81%   |
| India               | 5         | 1.81%   |
| Vietnam             | 4         | 1.45%   |
| Norway              | 4         | 1.45%   |
| Netherlands         | 4         | 1.45%   |
| Portugal            | 3         | 1.09%   |
| Peru                | 3         | 1.09%   |
| Indonesia           | 3         | 1.09%   |
| Greece              | 3         | 1.09%   |
| Denmark             | 3         | 1.09%   |
| Chile               | 3         | 1.09%   |
| South Korea         | 2         | 0.72%   |
| New Zealand         | 2         | 0.72%   |
| Australia           | 2         | 0.72%   |
| Argentina           | 2         | 0.72%   |
| Trinidad and Tobago | 1         | 0.36%   |
| Thailand            | 1         | 0.36%   |
| Tanzania            | 1         | 0.36%   |
| Taiwan              | 1         | 0.36%   |
| Sweden              | 1         | 0.36%   |
| South Africa        | 1         | 0.36%   |
| Serbia              | 1         | 0.36%   |
| Philippines         | 1         | 0.36%   |
| Panama              | 1         | 0.36%   |
| Malaysia            | 1         | 0.36%   |
| Lithuania           | 1         | 0.36%   |
| Kazakhstan          | 1         | 0.36%   |
| Iceland             | 1         | 0.36%   |
| Georgia             | 1         | 0.36%   |
| Finland             | 1         | 0.36%   |
| Czechia             | 1         | 0.36%   |
| Cuba                | 1         | 0.36%   |
| Colombia            | 1         | 0.36%   |
| Bulgaria            | 1         | 0.36%   |
| Belarus             | 1         | 0.36%   |
| Austria             | 1         | 0.36%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Moscow                        | 6         | 2.12%   |
| St Petersburg                 | 5         | 1.77%   |
| Hanoi                         | 4         | 1.41%   |
| Warsaw                        | 3         | 1.06%   |
| Rio de Janeiro                | 3         | 1.06%   |
| Lima                          | 3         | 1.06%   |
| Kharkiv                       | 3         | 1.06%   |
| Tromsø                       | 2         | 0.71%   |
| Tiruchi                       | 2         | 0.71%   |
| Surgut                        | 2         | 0.71%   |
| Suceava                       | 2         | 0.71%   |
| Smiths Falls                  | 2         | 0.71%   |
| Sherwood Park                 | 2         | 0.71%   |
| San SebastiÃ¡n de los Reyes | 2         | 0.71%   |
| Pflugerville                  | 2         | 0.71%   |
| Novosibirsk                   | 2         | 0.71%   |
| Myrtle Beach                  | 2         | 0.71%   |
| Leatherhead                   | 2         | 0.71%   |
| Kyiv                          | 2         | 0.71%   |
| Katowice                      | 2         | 0.71%   |
| Jakarta                       | 2         | 0.71%   |
| Izhevsk                       | 2         | 0.71%   |
| Istanbul                      | 2         | 0.71%   |
| Dreieich                      | 2         | 0.71%   |
| Dijon                         | 2         | 0.71%   |
| Curitiba                      | 2         | 0.71%   |
| Coria del RÃ­o              | 2         | 0.71%   |
| Castilleja de la Cuesta       | 2         | 0.71%   |
| Bucharest                     | 2         | 0.71%   |
| Beijing                       | 2         | 0.71%   |
| Barnaul                       | 2         | 0.71%   |
| Ankara                        | 2         | 0.71%   |
| Amsterdam                     | 2         | 0.71%   |
| Adelfia                       | 2         | 0.71%   |
| Zhengzhou                     | 1         | 0.35%   |
| Zhaoqing                      | 1         | 0.35%   |
| Zaporizhzhya                  | 1         | 0.35%   |
| Zapopan                       | 1         | 0.35%   |
| Yunlin                        | 1         | 0.35%   |
| Youngsville                   | 1         | 0.35%   |
| Yaphank                       | 1         | 0.35%   |
| Washington                    | 1         | 0.35%   |
| Vilnius                       | 1         | 0.35%   |
| VÃ¤sterÃ¥s                | 1         | 0.35%   |
| Vandalia                      | 1         | 0.35%   |
| Ugarchin                      | 1         | 0.35%   |
| Turley                        | 1         | 0.35%   |
| Turin                         | 1         | 0.35%   |
| Torokszentmiklos              | 1         | 0.35%   |
| Tolyatti                      | 1         | 0.35%   |
| Thessaloniki                  | 1         | 0.35%   |
| Tampa                         | 1         | 0.35%   |
| Szombathely                   | 1         | 0.35%   |
| Szeged                        | 1         | 0.35%   |
| SzÃ©kesfehÃ©rvÃ¡r       | 1         | 0.35%   |
| Susanville                    | 1         | 0.35%   |
| Stavropol                     | 1         | 0.35%   |
| Sparta                        | 1         | 0.35%   |
| Spalice                       | 1         | 0.35%   |
| Sopron                        | 1         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 71        | 89     | 18.3%   |
| Seagate             | 58        | 78     | 14.95%  |
| Samsung Electronics | 58        | 71     | 14.95%  |
| Toshiba             | 29        | 32     | 7.47%   |
| Kingston            | 29        | 34     | 7.47%   |
| Crucial             | 23        | 29     | 5.93%   |
| SanDisk             | 13        | 14     | 3.35%   |
| Hitachi             | 12        | 13     | 3.09%   |
| A-DATA Technology   | 11        | 12     | 2.84%   |
| Intel               | 10        | 11     | 2.58%   |
| HGST                | 8         | 8      | 2.06%   |
| SK Hynix            | 6         | 8      | 1.55%   |
| Patriot             | 6         | 6      | 1.55%   |
| XPG                 | 4         | 4      | 1.03%   |
| Phison              | 4         | 4      | 1.03%   |
| GOODRAM             | 4         | 4      | 1.03%   |
| SPCC                | 3         | 4      | 0.77%   |
| Micron Technology   | 3         | 3      | 0.77%   |
| Intenso             | 3         | 3      | 0.77%   |
| PNY                 | 2         | 2      | 0.52%   |
| OCZ                 | 2         | 2      | 0.52%   |
| Mushkin             | 2         | 2      | 0.52%   |
| LITEON              | 2         | 3      | 0.52%   |
| KingSpec            | 2         | 2      | 0.52%   |
| Gigabyte Technology | 2         | 3      | 0.52%   |
| Fujitsu             | 2         | 2      | 0.52%   |
| Apple               | 2         | 2      | 0.52%   |
| Apacer              | 2         | 2      | 0.52%   |
| Zheino              | 1         | 1      | 0.26%   |
| Transcend           | 1         | 1      | 0.26%   |
| Team                | 1         | 1      | 0.26%   |
| Silicon Motion      | 1         | 1      | 0.26%   |
| PLEXTOR             | 1         | 1      | 0.26%   |
| Netac               | 1         | 1      | 0.26%   |
| Lite-On             | 1         | 1      | 0.26%   |
| KIOXIA              | 1         | 1      | 0.26%   |
| Integral            | 1         | 1      | 0.26%   |
| INDMEM              | 1         | 1      | 0.26%   |
| Hewlett-Packard     | 1         | 1      | 0.26%   |
| EMTEC               | 1         | 1      | 0.26%   |
| Corsair             | 1         | 1      | 0.26%   |
| China               | 1         | 1      | 0.26%   |
| AGI                 | 1         | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Kingston SA400S37120G 120GB             | 9         | 2.14%   |
| Crucial CT500MX500SSD1 500GB            | 6         | 1.43%   |
| WDC WDS120G2G0A-00JH30 120GB            | 5         | 1.19%   |
| Toshiba MQ01ABF050 500GB                | 5         | 1.19%   |
| Seagate ST1000DM010-2EP102 1TB          | 5         | 1.19%   |
| HGST HTS545050A7E680 500GB              | 5         | 1.19%   |
| Crucial CT240BX500SSD1 240GB            | 5         | 1.19%   |
| XPG GAMMIX S11 Pro 256GB                | 4         | 0.95%   |
| WDC WDS240G2G0A-00JH30 240GB            | 4         | 0.95%   |
| Kingston SA400S37240G 240GB             | 4         | 0.95%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 3         | 0.71%   |
| Toshiba HDWD110 1TB                     | 3         | 0.71%   |
| Seagate ST4000DM004-2CV104 4TB          | 3         | 0.71%   |
| Seagate ST2000DM008-2FR102 2TB          | 3         | 0.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 0.71%   |
| Seagate ST1000DM003-1ER162 1TB          | 3         | 0.71%   |
| Samsung SSD 980 PRO 1TB                 | 3         | 0.71%   |
| Samsung SSD 860 EVO 500GB               | 3         | 0.71%   |
| Samsung SSD 860 EVO 1TB                 | 3         | 0.71%   |
| Samsung SSD 850 EVO 500GB               | 3         | 0.71%   |
| Samsung SSD 850 EVO 250GB               | 3         | 0.71%   |
| Crucial CT120BX500SSD1 120GB            | 3         | 0.71%   |
| WDC WDS500G2B0C-00PXH0 500GB            | 2         | 0.48%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 2         | 0.48%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 2         | 0.48%   |
| WDC WD20PURZ-85GU6Y0 2TB                | 2         | 0.48%   |
| WDC WD10JPCX-24UE4T0 1TB                | 2         | 0.48%   |
| Toshiba DT01ACA050 500GB                | 2         | 0.48%   |
| SK Hynix HFS256G39TND-N210A 256GB       | 2         | 0.48%   |
| SK Hynix BC501 HFM128GDJTNG-8310A 128GB | 2         | 0.48%   |
| Seagate ST9500325AS 500GB               | 2         | 0.48%   |
| Seagate ST500LT012-9WS142 500GB         | 2         | 0.48%   |
| Seagate ST3500418AS 500GB               | 2         | 0.48%   |
| Seagate ST3500413AS 500GB               | 2         | 0.48%   |
| Seagate ST3320418AS 320GB               | 2         | 0.48%   |
| Seagate ST31000528AS 1TB                | 2         | 0.48%   |
| SanDisk SDSSDA120G 120GB                | 2         | 0.48%   |
| Samsung SSD 970 EVO Plus 500GB          | 2         | 0.48%   |
| Samsung SSD 970 EVO Plus 1TB            | 2         | 0.48%   |
| Samsung SSD 970 EVO 250GB               | 2         | 0.48%   |
| Samsung SSD 870 EVO 500GB               | 2         | 0.48%   |
| Samsung SSD 860 EVO 250GB               | 2         | 0.48%   |
| Samsung Portable SSD T5 500GB           | 2         | 0.48%   |
| Samsung MZVLW256HEHP-000L7 256GB        | 2         | 0.48%   |
| Samsung HD322HJ 320GB                   | 2         | 0.48%   |
| Patriot Burst 240GB                     | 2         | 0.48%   |
| Patriot Burst 120GB                     | 2         | 0.48%   |
| Kingston SV300S37A120G 120GB            | 2         | 0.48%   |
| Kingston SA2000M81000G 1TB              | 2         | 0.48%   |
| Hitachi HTS541680J9SA00 80GB            | 2         | 0.48%   |
| GOODRAM SSDPR-CL100-120-G2 120GB        | 2         | 0.48%   |
| Crucial CT480BX500SSD1 480GB            | 2         | 0.48%   |
| Crucial CT256MX100SSD1 256GB            | 2         | 0.48%   |
| Crucial CT1050MX300SSD1 1TB             | 2         | 0.48%   |
| A-DATA SP550 240GB                      | 2         | 0.48%   |
| Zheino CHN mSATAM1 256 256GB            | 1         | 0.24%   |
| WDC WDS500G2B0B-00YS70 500GB            | 1         | 0.24%   |
| WDC WDS500G2B0A-00SM50 500GB            | 1         | 0.24%   |
| WDC WDS250G1B0A-00H9H0 250GB            | 1         | 0.24%   |
| WDC WDS240G1G0A-00SS50 240GB            | 1         | 0.24%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 57        | 74     | 35.19%  |
| WDC                 | 49        | 57     | 30.25%  |
| Toshiba             | 26        | 29     | 16.05%  |
| Hitachi             | 12        | 13     | 7.41%   |
| Samsung Electronics | 8         | 8      | 4.94%   |
| HGST                | 8         | 8      | 4.94%   |
| Fujitsu             | 1         | 1      | 0.62%   |
| Apple               | 1         | 1      | 0.62%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 37     | 19.3%   |
| Kingston            | 23        | 26     | 13.45%  |
| Crucial             | 23        | 28     | 13.45%  |
| WDC                 | 14        | 18     | 8.19%   |
| SanDisk             | 13        | 14     | 7.6%    |
| A-DATA Technology   | 9         | 9      | 5.26%   |
| Intel               | 7         | 7      | 4.09%   |
| Patriot             | 6         | 6      | 3.51%   |
| GOODRAM             | 4         | 4      | 2.34%   |
| SPCC                | 3         | 4      | 1.75%   |
| SK Hynix            | 3         | 3      | 1.75%   |
| Intenso             | 3         | 3      | 1.75%   |
| Toshiba             | 2         | 2      | 1.17%   |
| PNY                 | 2         | 2      | 1.17%   |
| OCZ                 | 2         | 2      | 1.17%   |
| LITEON              | 2         | 3      | 1.17%   |
| KingSpec            | 2         | 2      | 1.17%   |
| Gigabyte Technology | 2         | 3      | 1.17%   |
| Apacer              | 2         | 2      | 1.17%   |
| Zheino              | 1         | 1      | 0.58%   |
| Transcend           | 1         | 1      | 0.58%   |
| Team                | 1         | 1      | 0.58%   |
| PLEXTOR             | 1         | 1      | 0.58%   |
| Netac               | 1         | 1      | 0.58%   |
| Mushkin             | 1         | 1      | 0.58%   |
| Micron Technology   | 1         | 1      | 0.58%   |
| Lite-On             | 1         | 1      | 0.58%   |
| Integral            | 1         | 1      | 0.58%   |
| INDMEM              | 1         | 1      | 0.58%   |
| Hewlett-Packard     | 1         | 1      | 0.58%   |
| Fujitsu             | 1         | 1      | 0.58%   |
| EMTEC               | 1         | 1      | 0.58%   |
| Corsair             | 1         | 1      | 0.58%   |
| China               | 1         | 1      | 0.58%   |
| Apple               | 1         | 1      | 0.58%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 143       | 191    | 41.69%  |
| HDD  | 140       | 191    | 40.82%  |
| NVMe | 60        | 80     | 17.49%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 240       | 382    | 80%     |
| NVMe | 60        | 80     | 20%     |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 203       | 277    | 70.49%  |
| 0.51-1.0   | 53        | 63     | 18.4%   |
| 1.01-2.0   | 15        | 16     | 5.21%   |
| 3.01-4.0   | 9         | 16     | 3.13%   |
| 2.01-3.0   | 4         | 5      | 1.39%   |
| 4.01-10.0  | 3         | 4      | 1.04%   |
| 10.01-20.0 | 1         | 1      | 0.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 160       | 56.94%  |
| 101-250    | 56        | 19.93%  |
| 251-500    | 38        | 13.52%  |
| 501-1000   | 14        | 4.98%   |
| 21-50      | 7         | 2.49%   |
| 51-100     | 6         | 2.14%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 273       | 98.91%  |
| 21-50   | 2         | 0.72%   |
| 101-250 | 1         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST3500413AS 500GB           | 2         | 3      | 2.74%   |
| Seagate ST3320418AS 320GB           | 2         | 2      | 2.74%   |
| Seagate ST31000528AS 1TB            | 2         | 3      | 2.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 2      | 2.74%   |
| WDC WD60EZRZ-00RWYB1 6TB            | 1         | 1      | 1.37%   |
| WDC WD5000LPLX-60ZNTT1 500GB        | 1         | 1      | 1.37%   |
| WDC WD5000LPCX-75VHAT0 500GB        | 1         | 1      | 1.37%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 1         | 1      | 1.37%   |
| WDC WD5000BPVT-22HXZT3 500GB        | 1         | 1      | 1.37%   |
| WDC WD5000AZLX-00CL5A0 500GB        | 1         | 1      | 1.37%   |
| WDC WD5000AAKS-22A7B0 500GB         | 1         | 1      | 1.37%   |
| WDC WD400JB-00ENA0 40GB             | 1         | 1      | 1.37%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 1      | 1.37%   |
| WDC WD3200AAJS-22B4A0 320GB         | 1         | 1      | 1.37%   |
| WDC WD1600BEVT-80A23T0 160GB        | 1         | 1      | 1.37%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 1         | 1      | 1.37%   |
| WDC WD1600BEKT-66F3T2 160GB         | 1         | 1      | 1.37%   |
| WDC WD1600AAJS-40H3A0 160GB         | 1         | 1      | 1.37%   |
| WDC WD10EZEX-08M2NA0 1TB            | 1         | 1      | 1.37%   |
| WDC WD10EARS-003BB1 1TB             | 1         | 1      | 1.37%   |
| Toshiba THNSNX024GMNT 24GB          | 1         | 1      | 1.37%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 1.37%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 1.37%   |
| Toshiba MQ01ABD075 752GB            | 1         | 1      | 1.37%   |
| Toshiba MK8034GSX 80GB              | 1         | 1      | 1.37%   |
| Toshiba MK7559GSXF 752GB            | 1         | 1      | 1.37%   |
| Toshiba MK3265GSXN 320GB            | 1         | 1      | 1.37%   |
| Toshiba MK3261GSYN 320GB            | 1         | 1      | 1.37%   |
| Toshiba MD04ACA400 4TB              | 1         | 1      | 1.37%   |
| Toshiba DT01ACA100 1TB              | 1         | 3      | 1.37%   |
| Toshiba DT01ABA300 3TB              | 1         | 1      | 1.37%   |
| Seagate ST9640320AS 640GB           | 1         | 1      | 1.37%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 1.37%   |
| Seagate ST9320423AS 320GB           | 1         | 1      | 1.37%   |
| Seagate ST8000NM0055-1RM112 8TB     | 1         | 1      | 1.37%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1      | 1.37%   |
| Seagate ST380211AS 80GB             | 1         | 1      | 1.37%   |
| Seagate ST3500418AS 500GB           | 1         | 1      | 1.37%   |
| Seagate ST3250310AS 250GB           | 1         | 1      | 1.37%   |
| Seagate ST320LT007-9ZV142 320GB     | 1         | 1      | 1.37%   |
| Seagate ST3160812AS 160GB           | 1         | 1      | 1.37%   |
| Seagate ST31000520AS 1TB            | 1         | 1      | 1.37%   |
| Seagate ST1000DM003-1ER162 1TB      | 1         | 1      | 1.37%   |
| SanDisk SSD PLUS 240GB              | 1         | 1      | 1.37%   |
| Samsung Electronics SSD 970 EVO 2TB | 1         | 1      | 1.37%   |
| Samsung Electronics SSD 870 EVO 1TB | 1         | 1      | 1.37%   |
| Samsung Electronics SSD 860 EVO 1TB | 1         | 2      | 1.37%   |
| Samsung Electronics HS082HB 80GB    | 1         | 1      | 1.37%   |
| Samsung Electronics HM160HI 160GB   | 1         | 1      | 1.37%   |
| Samsung Electronics HD322HJ 320GB   | 1         | 1      | 1.37%   |
| Samsung Electronics HD250HJ 250GB   | 1         | 1      | 1.37%   |
| LITEON CV8-8E128-HP 128GB           | 1         | 1      | 1.37%   |
| Kingston SV300S37A120G 120GB        | 1         | 1      | 1.37%   |
| Kingston SV200S3128G 128GB          | 1         | 1      | 1.37%   |
| Kingston SMS200S3120G 120GB         | 1         | 1      | 1.37%   |
| Hitachi HTS723216L9SA60 160GB       | 1         | 1      | 1.37%   |
| Hitachi HTS547564A9E384 640GB       | 1         | 1      | 1.37%   |
| Hitachi HTS545050A7E380 500GB       | 1         | 1      | 1.37%   |
| Hitachi HTS543232L9SA02 320GB       | 1         | 1      | 1.37%   |
| Hitachi HTS542516K9SA00 160GB       | 1         | 1      | 1.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 22     | 27.14%  |
| WDC                 | 16        | 16     | 22.86%  |
| Toshiba             | 10        | 13     | 14.29%  |
| Hitachi             | 8         | 9      | 11.43%  |
| Samsung Electronics | 6         | 8      | 8.57%   |
| Kingston            | 3         | 3      | 4.29%   |
| HGST                | 2         | 2      | 2.86%   |
| Crucial             | 2         | 2      | 2.86%   |
| SanDisk             | 1         | 1      | 1.43%   |
| LITEON              | 1         | 1      | 1.43%   |
| AGI                 | 1         | 1      | 1.43%   |
| A-DATA Technology   | 1         | 1      | 1.43%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 22     | 32.76%  |
| WDC                 | 16        | 16     | 27.59%  |
| Toshiba             | 9         | 12     | 15.52%  |
| Hitachi             | 8         | 9      | 13.79%  |
| Samsung Electronics | 4         | 4      | 6.9%    |
| HGST                | 2         | 2      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 54        | 65     | 80.6%   |
| SSD  | 10        | 11     | 14.93%  |
| NVMe | 3         | 3      | 4.48%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD3200AAJS-00YZCA0 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 221       | 379    | 76.47%  |
| Malfunc  | 64        | 79     | 22.15%  |
| Detected | 3         | 3      | 1.04%   |
| Failed   | 1         | 1      | 0.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 198       | 57.73%  |
| AMD                              | 54        | 15.74%  |
| Samsung Electronics              | 23        | 6.71%   |
| Nvidia                           | 13        | 3.79%   |
| Sandisk                          | 10        | 2.92%   |
| Kingston Technology Company      | 6         | 1.75%   |
| ADATA Technology                 | 6         | 1.75%   |
| Phison Electronics               | 4         | 1.17%   |
| SK Hynix                         | 3         | 0.87%   |
| Silicon Motion                   | 3         | 0.87%   |
| Marvell Technology Group         | 3         | 0.87%   |
| JMicron Technology               | 3         | 0.87%   |
| Broadcom / LSI                   | 3         | 0.87%   |
| ASMedia Technology               | 3         | 0.87%   |
| Seagate Technology               | 2         | 0.58%   |
| Micron Technology                | 2         | 0.58%   |
| KIOXIA                           | 2         | 0.58%   |
| VIA Technologies                 | 1         | 0.29%   |
| Silicon Integrated Systems [SiS] | 1         | 0.29%   |
| Realtek Semiconductor            | 1         | 0.29%   |
| Micron/Crucial Technology        | 1         | 0.29%   |
| Apple                            | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 45        | 11.54%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 14        | 3.59%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 14        | 3.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 13        | 3.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 12        | 3.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 11        | 2.82%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 11        | 2.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 10        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 2.56%   |
| Nvidia MCP79 AHCI Controller                                                     | 9         | 2.31%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 9         | 2.31%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 8         | 2.05%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 8         | 2.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 2.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 8         | 2.05%   |
| Intel SATA Controller [RAID mode]                                                | 7         | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 7         | 1.79%   |
| AMD 400 Series Chipset SATA Controller                                           | 7         | 1.79%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 6         | 1.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 1.54%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 1.54%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 6         | 1.54%   |
| Unknown                                                                          | 6         | 1.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 1.28%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 1.28%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 1.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 1.03%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 1.03%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 4         | 1.03%   |
| Phison E12 NVMe Controller                                                       | 3         | 0.77%   |
| Kingston Company A2000 NVMe SSD                                                  | 3         | 0.77%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 0.77%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 0.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 3         | 0.77%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 0.77%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 0.77%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3         | 0.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 0.77%   |
| AMD FCH SATA Controller D                                                        | 3         | 0.77%   |
| AMD 300 Series Chipset SATA Controller                                           | 3         | 0.77%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 2         | 0.51%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.51%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 0.51%   |
| Nvidia MCP61 SATA Controller                                                     | 2         | 0.51%   |
| KIOXIA unknown                                                                   | 2         | 0.51%   |
| JMicron JMB363 SATA/IDE Controller                                               | 2         | 0.51%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 0.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 0.51%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.51%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2         | 0.51%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2         | 0.51%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 2         | 0.51%   |
| AMD X370 Series Chipset SATA Controller                                          | 2         | 0.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 2         | 0.51%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 0.51%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.26%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 0.26%   |
| SK Hynix Gold P31 SSD                                                            | 1         | 0.26%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 230       | 66.67%  |
| NVMe | 61        | 17.68%  |
| IDE  | 38        | 11.01%  |
| RAID | 14        | 4.06%   |
| SAS  | 1         | 0.29%   |
| SCSI | 1         | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 215       | 77.9%   |
| AMD    | 61        | 22.1%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz           | 7         | 2.54%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4         | 1.45%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4         | 1.45%   |
| Intel CPU Version                           | 3         | 1.09%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3         | 1.09%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 1.09%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 1.09%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 1.09%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 3         | 1.09%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz        | 3         | 1.09%   |
| Intel Core 2 Duo                            | 3         | 1.09%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz         | 2         | 0.72%   |
| Intel Pentium CPU G860 @ 3.00GHz            | 2         | 0.72%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2         | 0.72%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 2         | 0.72%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 0.72%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2         | 0.72%   |
| Intel Core i7-3612QM CPU @ 2.10GHz          | 2         | 0.72%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2         | 0.72%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 0.72%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 0.72%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2         | 0.72%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2         | 0.72%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 0.72%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 0.72%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2         | 0.72%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2         | 0.72%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 2         | 0.72%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 0.72%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 2         | 0.72%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 0.72%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 2         | 0.72%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 0.72%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2         | 0.72%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 2         | 0.72%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz        | 2         | 0.72%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz        | 2         | 0.72%   |
| Intel Core 2 Duo CPU E8135 @ 2.66GHz        | 2         | 0.72%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 2         | 0.72%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 0.72%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 2         | 0.72%   |
| Intel Atom CPU N450 @ 1.66GHz               | 2         | 0.72%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2         | 0.72%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2         | 0.72%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 2         | 0.72%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2         | 0.72%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2         | 0.72%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2         | 0.72%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2         | 0.72%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2         | 0.72%   |
| AMD E1-1200 APU with Radeon HD Graphics     | 2         | 0.72%   |
| Intel Xeon E-2136 CPU @ 3.30GHz             | 1         | 0.36%   |
| Intel Xeon CPU X5647 @ 2.93GHz              | 1         | 0.36%   |
| Intel Xeon CPU X3470 @ 2.93GHz              | 1         | 0.36%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1         | 0.36%   |
| Intel Xeon CPU E5504 @ 2.00GHz              | 1         | 0.36%   |
| Intel Xeon CPU E5-2403 v2 @ 1.80GHz         | 1         | 0.36%   |
| Intel Xeon CPU E31245 @ 3.30GHz             | 1         | 0.36%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz        | 1         | 0.36%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1         | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 71        | 25.72%  |
| Intel Core i7           | 31        | 11.23%  |
| Intel Core 2 Duo        | 27        | 9.78%   |
| Intel Core i3           | 24        | 8.7%    |
| AMD Ryzen 5             | 16        | 5.8%    |
| Intel Celeron           | 15        | 5.43%   |
| Intel Xeon              | 13        | 4.71%   |
| AMD Ryzen 7             | 12        | 4.35%   |
| Intel Pentium           | 9         | 3.26%   |
| Other                   | 5         | 1.81%   |
| Intel Pentium Dual-Core | 5         | 1.81%   |
| Intel Core 2 Quad       | 5         | 1.81%   |
| AMD A6                  | 5         | 1.81%   |
| Intel Atom              | 4         | 1.45%   |
| AMD Ryzen 9             | 4         | 1.45%   |
| AMD Ryzen 3             | 4         | 1.45%   |
| AMD E2                  | 3         | 1.09%   |
| AMD A10                 | 3         | 1.09%   |
| Intel Core 2            | 2         | 0.72%   |
| AMD Ryzen Threadripper  | 2         | 0.72%   |
| AMD Phenom II X4        | 2         | 0.72%   |
| AMD FX                  | 2         | 0.72%   |
| AMD E1                  | 2         | 0.72%   |
| Intel Pentium Dual      | 1         | 0.36%   |
| Intel Pentium D         | 1         | 0.36%   |
| Intel Core M            | 1         | 0.36%   |
| Intel Core i9           | 1         | 0.36%   |
| AMD Ryzen 5 PRO         | 1         | 0.36%   |
| AMD E                   | 1         | 0.36%   |
| AMD Athlon II X4        | 1         | 0.36%   |
| AMD Athlon II X2        | 1         | 0.36%   |
| AMD Athlon Dual Core    | 1         | 0.36%   |
| AMD A8                  | 1         | 0.36%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 107       | 38.77%  |
| 4       | 79        | 28.62%  |
| Unknown | 33        | 11.96%  |
| 6       | 17        | 6.16%   |
| 8       | 13        | 4.71%   |
| 12      | 10        | 3.62%   |
| 16      | 9         | 3.26%   |
| 24      | 3         | 1.09%   |
| 64      | 1         | 0.36%   |
| 48      | 1         | 0.36%   |
| 32      | 1         | 0.36%   |
| 14      | 1         | 0.36%   |
| 1       | 1         | 0.36%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 260       | 94.2%   |
| 2       | 14        | 5.07%   |
| Unknown | 2         | 0.72%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 130       | 47.1%   |
| 2       | 113       | 40.94%  |
| Unknown | 33        | 11.96%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Penryn        | 32        | 11.59%  |
| KabyLake      | 29        | 10.51%  |
| IvyBridge     | 29        | 10.51%  |
| Haswell       | 26        | 9.42%   |
| Skylake       | 22        | 7.97%   |
| SandyBridge   | 19        | 6.88%   |
| Zen 2         | 15        | 5.43%   |
| Westmere      | 14        | 5.07%   |
| Core          | 11        | 3.99%   |
| Zen+          | 9         | 3.26%   |
| Zen           | 9         | 3.26%   |
| Silvermont    | 8         | 2.9%    |
| Zen 3         | 6         | 2.17%   |
| Piledriver    | 6         | 2.17%   |
| CometLake     | 6         | 2.17%   |
| Broadwell     | 6         | 2.17%   |
| K10           | 4         | 1.45%   |
| Bonnell       | 4         | 1.45%   |
| Bobcat        | 4         | 1.45%   |
| Nehalem       | 3         | 1.09%   |
| Jaguar        | 3         | 1.09%   |
| Goldmont      | 2         | 0.72%   |
| Excavator     | 2         | 0.72%   |
| Unknown       | 2         | 0.72%   |
| Puma          | 1         | 0.36%   |
| NetBurst      | 1         | 0.36%   |
| K8 Hammer     | 1         | 0.36%   |
| K10 Llano     | 1         | 0.36%   |
| Goldmont plus | 1         | 0.36%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 152       | 49.84%  |
| Nvidia | 85        | 27.87%  |
| AMD    | 68        | 22.3%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 4.79%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 4.79%   |
| Intel HD Graphics 530                                                                    | 10        | 3.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 2.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 2.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 2.56%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 2.24%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 1.92%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 1.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 1.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 1.92%   |
| Intel HD Graphics 620                                                                    | 6         | 1.92%   |
| Nvidia C79 [GeForce 9400]                                                                | 5         | 1.6%    |
| Intel HD Graphics 5500                                                                   | 5         | 1.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.6%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 1.6%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 1.28%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4         | 1.28%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 1.28%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.28%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 1.28%   |
| AMD Renoir                                                                               | 4         | 1.28%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.28%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 4         | 1.28%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.96%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 0.96%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 0.96%   |
| Intel UHD Graphics 620                                                                   | 3         | 0.96%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.96%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.96%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 3         | 0.96%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 3         | 0.96%   |
| Nvidia TU117M                                                                            | 2         | 0.64%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2         | 0.64%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.64%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 2         | 0.64%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 0.64%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.64%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.64%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2         | 0.64%   |
| Nvidia GK107GL [Quadro K2000]                                                            | 2         | 0.64%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 2         | 0.64%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 0.64%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 2         | 0.64%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.64%   |
| Intel HD Graphics 630                                                                    | 2         | 0.64%   |
| Intel HD Graphics 500                                                                    | 2         | 0.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.64%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 0.64%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 0.64%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 2         | 0.64%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2         | 0.64%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.64%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.64%   |
| AMD Cezanne                                                                              | 2         | 0.64%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 0.64%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.32%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.32%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 0.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 111       | 39.78%  |
| 1 x Nvidia     | 66        | 23.66%  |
| 1 x AMD        | 58        | 20.79%  |
| Intel + Nvidia | 18        | 6.45%   |
| 2 x Intel      | 16        | 5.73%   |
| Intel + AMD    | 7         | 2.51%   |
| AMD + Nvidia   | 2         | 0.72%   |
| 2 x AMD        | 1         | 0.36%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 214       | 76.98%  |
| Proprietary | 58        | 20.86%  |
| Unknown     | 6         | 2.16%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 172       | 61.65%  |
| 0.01-0.5   | 34        | 12.19%  |
| 0.51-1.0   | 20        | 7.17%   |
| 1.01-2.0   | 19        | 6.81%   |
| 3.01-4.0   | 17        | 6.09%   |
| 7.01-8.0   | 12        | 4.3%    |
| 5.01-6.0   | 5         | 1.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 32        | 12.17%  |
| LG Display              | 27        | 10.27%  |
| AU Optronics            | 23        | 8.75%   |
| Chimei Innolux          | 19        | 7.22%   |
| Goldstar                | 18        | 6.84%   |
| Lenovo                  | 16        | 6.08%   |
| Dell                    | 16        | 6.08%   |
| BOE                     | 14        | 5.32%   |
| Apple                   | 13        | 4.94%   |
| AOC                     | 12        | 4.56%   |
| BenQ                    | 11        | 4.18%   |
| Acer                    | 9         | 3.42%   |
| Hewlett-Packard         | 8         | 3.04%   |
| Ancor Communications    | 7         | 2.66%   |
| Philips                 | 6         | 2.28%   |
| Sony                    | 4         | 1.52%   |
| Fujitsu Siemens         | 3         | 1.14%   |
| ASUSTek Computer        | 3         | 1.14%   |
| ViewSonic               | 2         | 0.76%   |
| Vestel Elektronik       | 2         | 0.76%   |
| Chi Mei Optoelectronics | 2         | 0.76%   |
| ZL_                     | 1         | 0.38%   |
| Westinghouse            | 1         | 0.38%   |
| Toshiba                 | 1         | 0.38%   |
| SLD                     | 1         | 0.38%   |
| SGT                     | 1         | 0.38%   |
| RTK                     | 1         | 0.38%   |
| NEC Computers           | 1         | 0.38%   |
| MSI                     | 1         | 0.38%   |
| Medion                  | 1         | 0.38%   |
| LTV                     | 1         | 0.38%   |
| Lenovo Group Limited    | 1         | 0.38%   |
| LED                     | 1         | 0.38%   |
| Iiyama                  | 1         | 0.38%   |
| FND                     | 1         | 0.38%   |
| Denver                  | 1         | 0.38%   |
| CND                     | 1         | 0.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 530x300mm 24.0-inch     | 2         | 0.74%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch  | 2         | 0.74%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 2         | 0.74%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                 | 2         | 0.74%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch            | 2         | 0.74%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch            | 2         | 0.74%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch                | 2         | 0.74%   |
| Lenovo LCD Monitor LEN4031 1280x800 290x180mm 13.4-inch                | 2         | 0.74%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch                | 2         | 0.74%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch        | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch       | 2         | 0.74%   |
| BenQ GW2780 BNQ78E6 1920x1080 600x340mm 27.2-inch                      | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch          | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch         | 2         | 0.74%   |
| Apple Color LCD APP9C96 1920x1200 520x320mm 24.0-inch                  | 2         | 0.74%   |
| Apple Color LCD APP9C93 1680x1050 430x270mm 20.0-inch                  | 2         | 0.74%   |
| AOC 24G2W1G4 AOC2402 1920x1080 530x300mm 24.0-inch                     | 2         | 0.74%   |
| Ancor Communications MX27AQ ACI27A5 2560x1440 600x340mm 27.2-inch      | 2         | 0.74%   |
| ZL_ zhuoyue-DP ZL_2716 2560x1440 600x330mm 27.0-inch                   | 1         | 0.37%   |
| Westinghouse LCM-19w4 WDE1904 1440x900 410x260mm 19.1-inch             | 1         | 0.37%   |
| ViewSonic VX1940w VSC6A20 1680x1050 410x260mm 19.1-inch                | 1         | 0.37%   |
| ViewSonic LCD Monitor VSCBD2B 1920x1080 480x270mm 21.7-inch            | 1         | 0.37%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                        | 1         | 0.37%   |
| Sony TV SNYEE01 1920x1080                                              | 1         | 0.37%   |
| Sony TV SNY9C01 1360x768                                               | 1         | 0.37%   |
| Sony SDM-S75D/F/N SNY3800 1280x1024 340x270mm 17.1-inch                | 1         | 0.37%   |
| Sony LCD SNY06FA 1600x900 290x160mm 13.0-inch                          | 1         | 0.37%   |
| SLD LCD Monitor SLD003C 1366x768 310x170mm 13.9-inch                   | 1         | 0.37%   |
| SGT YSD SGT1700 1280x1024 380x210mm 17.1-inch                          | 1         | 0.37%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch      | 1         | 0.37%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 520x290mm 23.4-inch      | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                        | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch    | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                       | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM05B0 1920x1080                       | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM0373 1680x1050 440x300mm 21.0-inch   | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM027D 1680x1050 430x270mm 20.0-inch   | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 280x210mm 13.8-inch    | 1         | 0.37%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 480x270mm 21.7-inch     | 1         | 0.37%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 600x340mm 27.2-inch      | 1         | 0.37%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch      | 1         | 0.37%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch      | 1         | 0.37%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 530x300mm 24.0-inch      | 1         | 0.37%   |
| Samsung Electronics S24C450 SAM09CB 1920x1080 530x300mm 24.0-inch      | 1         | 0.37%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch       | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch   | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch   | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 370x230mm 17.2-inch   | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch   | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch   | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 300x190mm 14.0-inch   | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch  | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 220x130mm 10.1-inch   | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 350x200mm 15.9-inch   | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 340x190mm 15.3-inch   | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1420x800mm 64.2-inch | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 1110x620mm 50.1-inch | 1         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 93        | 35.63%  |
| 1366x768 (WXGA)    | 68        | 26.05%  |
| 1280x800 (WXGA)    | 14        | 5.36%   |
| 2560x1440 (QHD)    | 13        | 4.98%   |
| 1280x1024 (SXGA)   | 13        | 4.98%   |
| 1600x900 (HD+)     | 12        | 4.6%    |
| 3840x2160 (4K)     | 9         | 3.45%   |
| 1920x1200 (WUXGA)  | 9         | 3.45%   |
| 1440x900 (WXGA+)   | 9         | 3.45%   |
| 1680x1050 (WSXGA+) | 7         | 2.68%   |
| 2560x1080          | 3         | 1.15%   |
| 1920x540           | 3         | 1.15%   |
| 1024x768 (XGA)     | 3         | 1.15%   |
| 3440x1440          | 2         | 0.77%   |
| 1024x600           | 2         | 0.77%   |
| 1360x768           | 1         | 0.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 49        | 18.28%  |
| 13      | 36        | 13.43%  |
| 24      | 30        | 11.19%  |
| 27      | 22        | 8.21%   |
| 23      | 17        | 6.34%   |
| 21      | 16        | 5.97%   |
| 19      | 16        | 5.97%   |
| 17      | 13        | 4.85%   |
| 12      | 12        | 4.48%   |
| 18      | 8         | 2.99%   |
| 14      | 7         | 2.61%   |
| 31      | 6         | 2.24%   |
| 20      | 6         | 2.24%   |
| Unknown | 6         | 2.24%   |
| 11      | 5         | 1.87%   |
| 34      | 3         | 1.12%   |
| 10      | 3         | 1.12%   |
| 42      | 2         | 0.75%   |
| 29      | 2         | 0.75%   |
| 16      | 2         | 0.75%   |
| 64      | 1         | 0.37%   |
| 54      | 1         | 0.37%   |
| 50      | 1         | 0.37%   |
| 40      | 1         | 0.37%   |
| 36      | 1         | 0.37%   |
| 33      | 1         | 0.37%   |
| 22      | 1         | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 79        | 29.92%  |
| 501-600     | 66        | 25%     |
| 201-300     | 40        | 15.15%  |
| 401-500     | 37        | 14.02%  |
| 351-400     | 16        | 6.06%   |
| 601-700     | 9         | 3.41%   |
| Unknown     | 6         | 2.27%   |
| 701-800     | 5         | 1.89%   |
| 1001-1500   | 3         | 1.14%   |
| 901-1000    | 2         | 0.76%   |
| 801-900     | 1         | 0.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 190       | 75.7%   |
| 16/10   | 37        | 14.74%  |
| 5/4     | 11        | 4.38%   |
| 21/9    | 5         | 1.99%   |
| 3/2     | 4         | 1.59%   |
| 4/3     | 3         | 1.2%    |
| Unknown | 1         | 0.4%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 51        | 19.1%   |
| 91-100         | 41        | 15.36%  |
| 81-90          | 35        | 13.11%  |
| 151-200        | 26        | 9.74%   |
| 301-350        | 23        | 8.61%   |
| 61-70          | 12        | 4.49%   |
| 251-300        | 12        | 4.49%   |
| 141-150        | 11        | 4.12%   |
| 351-500        | 10        | 3.75%   |
| 101-110        | 10        | 3.75%   |
| 71-80          | 6         | 2.25%   |
| 121-130        | 6         | 2.25%   |
| Unknown        | 6         | 2.25%   |
| 51-60          | 5         | 1.87%   |
| 501-1000       | 4         | 1.5%    |
| More than 1000 | 3         | 1.12%   |
| 41-50          | 3         | 1.12%   |
| 131-140        | 2         | 0.75%   |
| 111-120        | 1         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 110       | 41.67%  |
| 101-120 | 83        | 31.44%  |
| 121-160 | 56        | 21.21%  |
| 161-240 | 7         | 2.65%   |
| Unknown | 6         | 2.27%   |
| 1-50    | 2         | 0.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 231       | 83.09%  |
| 2     | 25        | 8.99%   |
| 0     | 21        | 7.55%   |
| 3     | 1         | 0.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 149       | 36.25%  |
| Intel                             | 129       | 31.39%  |
| Qualcomm Atheros                  | 45        | 10.95%  |
| Broadcom                          | 36        | 8.76%   |
| Nvidia                            | 9         | 2.19%   |
| Marvell Technology Group          | 9         | 2.19%   |
| Ralink                            | 5         | 1.22%   |
| Ralink Technology                 | 3         | 0.73%   |
| NetGear                           | 3         | 0.73%   |
| JMicron Technology                | 3         | 0.73%   |
| Edimax Technology                 | 3         | 0.73%   |
| TP-Link                           | 2         | 0.49%   |
| Ericsson Business Mobile Networks | 2         | 0.49%   |
| Dell                              | 2         | 0.49%   |
| D-Link System                     | 2         | 0.49%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.24%   |
| Sierra Wireless                   | 1         | 0.24%   |
| OPPO Electronics                  | 1         | 0.24%   |
| Microchip Technology              | 1         | 0.24%   |
| Mercucys                          | 1         | 0.24%   |
| MediaTek                          | 1         | 0.24%   |
| Huawei Technologies               | 1         | 0.24%   |
| Hewlett-Packard                   | 1         | 0.24%   |
| Google                            | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 111       | 22.47%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 20        | 4.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 15        | 3.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 2.23%   |
| Intel Wi-Fi 6 AX200                                                     | 11        | 2.23%   |
| Intel I211 Gigabit Network Connection                                   | 11        | 2.23%   |
| Intel Ethernet Connection I217-LM                                       | 11        | 2.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 2.02%   |
| Nvidia MCP79 Ethernet                                                   | 9         | 1.82%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 9         | 1.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 1.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 1.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 1.42%   |
| Intel Wireless 8260                                                     | 7         | 1.42%   |
| Intel Wireless 7265                                                     | 7         | 1.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 1.21%   |
| Intel Wireless 8265 / 8275                                              | 6         | 1.21%   |
| Intel Ethernet Connection (2) I219-LM                                   | 6         | 1.21%   |
| Intel Wireless 7260                                                     | 5         | 1.01%   |
| Intel Ethernet Connection (7) I219-V                                    | 5         | 1.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.81%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 4         | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 4         | 0.81%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.81%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 0.81%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 0.81%   |
| Intel 82579V Gigabit Network Connection                                 | 4         | 0.81%   |
| Intel 82577LM Gigabit Network Connection                                | 4         | 0.81%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 4         | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.61%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.61%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 3         | 0.61%   |
| Intel Wireless 3165                                                     | 3         | 0.61%   |
| Intel WiFi Link 5100                                                    | 3         | 0.61%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.61%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.61%   |
| Intel Ethernet Connection I219-LM                                       | 3         | 0.61%   |
| Intel Ethernet Connection (4) I219-V                                    | 3         | 0.61%   |
| Intel Ethernet Connection (2) I219-V                                    | 3         | 0.61%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 3         | 0.61%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 0.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 0.61%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 2         | 0.4%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.4%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.4%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.4%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 2         | 0.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 0.4%    |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 2         | 0.4%    |
| Realtek 802.11n WLAN Adapter                                            | 2         | 0.4%    |
| Ralink RT5370 Wireless Adapter                                          | 2         | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 2         | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 2         | 0.4%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.4%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 2         | 0.4%    |
| Intel Wireless-AC 9260                                                  | 2         | 0.4%    |
| Intel I210 Gigabit Network Connection                                   | 2         | 0.4%    |
| Intel Ethernet Connection I218-LM                                       | 2         | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 91        | 43.75%  |
| Qualcomm Atheros      | 36        | 17.31%  |
| Realtek Semiconductor | 35        | 16.83%  |
| Broadcom              | 26        | 12.5%   |
| Ralink                | 5         | 2.4%    |
| Ralink Technology     | 3         | 1.44%   |
| NetGear               | 3         | 1.44%   |
| Edimax Technology     | 3         | 1.44%   |
| TP-Link               | 2         | 0.96%   |
| Sierra Wireless       | 1         | 0.48%   |
| Mercucys              | 1         | 0.48%   |
| MediaTek              | 1         | 0.48%   |
| Dell                  | 1         | 0.48%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 5.16%   |
| Intel Wi-Fi 6 AX200                                                     | 11        | 5.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 4.69%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 9         | 4.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 3.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 3.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 3.29%   |
| Intel Wireless 8260                                                     | 7         | 3.29%   |
| Intel Wireless 7265                                                     | 7         | 3.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 2.82%   |
| Intel Wireless 8265 / 8275                                              | 6         | 2.82%   |
| Intel Wireless 7260                                                     | 5         | 2.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.88%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 4         | 1.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.88%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 1.88%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 1.88%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 4         | 1.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.41%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.41%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.41%   |
| Intel Wireless 3165                                                     | 3         | 1.41%   |
| Intel WiFi Link 5100                                                    | 3         | 1.41%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.41%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.41%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 1.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.41%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 2         | 0.94%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.94%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.94%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.94%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 2         | 0.94%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 2         | 0.94%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 0.94%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 0.94%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.94%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.94%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.94%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.94%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 0.94%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 2         | 0.94%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                           | 1         | 0.47%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.47%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.47%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.47%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.47%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.47%   |
| Ralink RT2500 Wireless 802.11bg                                         | 1         | 0.47%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 0.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.47%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.47%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                         | 1         | 0.47%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]        | 1         | 0.47%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]             | 1         | 0.47%   |
| Mercucys MERCUSYS Wireless USB Adapter                                  | 1         | 0.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 135       | 49.63%  |
| Intel                            | 87        | 31.99%  |
| Qualcomm Atheros                 | 13        | 4.78%   |
| Broadcom                         | 12        | 4.41%   |
| Nvidia                           | 9         | 3.31%   |
| Marvell Technology Group         | 9         | 3.31%   |
| JMicron Technology               | 3         | 1.1%    |
| Silicon Integrated Systems [SiS] | 1         | 0.37%   |
| OPPO Electronics                 | 1         | 0.37%   |
| Google                           | 1         | 0.37%   |
| D-Link System                    | 1         | 0.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 111       | 40.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 20        | 7.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 15        | 5.47%   |
| Intel I211 Gigabit Network Connection                                         | 11        | 4.01%   |
| Intel Ethernet Connection I217-LM                                             | 11        | 4.01%   |
| Nvidia MCP79 Ethernet                                                         | 9         | 3.28%   |
| Intel Ethernet Connection (2) I219-LM                                         | 6         | 2.19%   |
| Intel Ethernet Connection (7) I219-V                                          | 5         | 1.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 4         | 1.46%   |
| Intel 82579V Gigabit Network Connection                                       | 4         | 1.46%   |
| Intel 82577LM Gigabit Network Connection                                      | 4         | 1.46%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 3         | 1.09%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 1.09%   |
| Intel Ethernet Connection (4) I219-V                                          | 3         | 1.09%   |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 1.09%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                               | 3         | 1.09%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 0.73%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 2         | 0.73%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 2         | 0.73%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 2         | 0.73%   |
| Intel I210 Gigabit Network Connection                                         | 2         | 0.73%   |
| Intel Ethernet Connection I218-LM                                             | 2         | 0.73%   |
| Intel Ethernet Connection (3) I218-V                                          | 2         | 0.73%   |
| Intel 82574L Gigabit Network Connection                                       | 2         | 0.73%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2         | 0.73%   |
| Intel 82566MM Gigabit Network Connection                                      | 2         | 0.73%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 2         | 0.73%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                        | 2         | 0.73%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 1         | 0.36%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.36%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1         | 0.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 0.36%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1         | 0.36%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1         | 0.36%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                    | 1         | 0.36%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 0.36%   |
| OPPO SDM720G-IDP _SN:8A58D65F RNDIS Control RNDIS Ethernet Data               | 1         | 0.36%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                       | 1         | 0.36%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                       | 1         | 0.36%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 0.36%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1         | 0.36%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                         | 1         | 0.36%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 1         | 0.36%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                          | 1         | 0.36%   |
| Intel Ethernet Controller I225-V                                              | 1         | 0.36%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 0.36%   |
| Intel Ethernet Connection (6) I219-V                                          | 1         | 0.36%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 0.36%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 0.36%   |
| Intel Ethernet Connection (12) I219-V                                         | 1         | 0.36%   |
| Intel Ethernet Connection (10) I219-V                                         | 1         | 0.36%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1         | 0.36%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1         | 0.36%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.36%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 0.36%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1         | 0.36%   |
| Google Nexus/Pixel Device (tether)                                            | 1         | 0.36%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 1         | 0.36%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                             | 1         | 0.36%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 1         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 265       | 57.48%  |
| WiFi     | 189       | 41%     |
| Modem    | 4         | 0.87%   |
| Unknown  | 3         | 0.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 240       | 65.57%  |
| WiFi     | 122       | 33.33%  |
| Unknown  | 3         | 0.82%   |
| Modem    | 1         | 0.27%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 167       | 60.51%  |
| 1     | 97        | 35.14%  |
| 3     | 6         | 2.17%   |
| 4     | 3         | 1.09%   |
| 0     | 3         | 1.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 263       | 94.27%  |
| Yes  | 16        | 5.73%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 58        | 41.73%  |
| Apple                           | 16        | 11.51%  |
| Realtek Semiconductor           | 10        | 7.19%   |
| Qualcomm Atheros Communications | 10        | 7.19%   |
| Cambridge Silicon Radio         | 10        | 7.19%   |
| Broadcom                        | 10        | 7.19%   |
| Lite-On Technology              | 5         | 3.6%    |
| IMC Networks                    | 4         | 2.88%   |
| Ralink                          | 3         | 2.16%   |
| Hewlett-Packard                 | 3         | 2.16%   |
| Foxconn / Hon Hai               | 3         | 2.16%   |
| Integrated System Solution      | 2         | 1.44%   |
| Dell                            | 2         | 1.44%   |
| ASUSTek Computer                | 2         | 1.44%   |
| HTC (High Tech Computer)        | 1         | 0.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 30        | 21.28%  |
| Intel AX200 Bluetooth                                                | 11        | 7.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 10        | 7.09%   |
| Intel AX201 Bluetooth                                                | 6         | 4.26%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 6         | 4.26%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                              | 5         | 3.55%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 5         | 3.55%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 4         | 2.84%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 4         | 2.84%   |
| Ralink RT3290 Bluetooth                                              | 3         | 2.13%   |
| Lite-On Atheros AR3012 Bluetooth                                     | 3         | 2.13%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 3         | 2.13%   |
| Apple Built-in iSight (no firmware loaded)                           | 3         | 2.13%   |
| Apple Bluetooth Host Controller                                      | 3         | 2.13%   |
| Apple Apple Broadcom Built-in Bluetooth                              | 3         | 2.13%   |
| Realtek Bluetooth Radio                                              | 2         | 1.42%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device          | 2         | 1.42%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2         | 1.42%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 2         | 1.42%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                        | 2         | 1.42%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                     | 2         | 1.42%   |
| Realtek RTL8821A Bluetooth                                           | 1         | 0.71%   |
| Realtek RTL8723B Bluetooth                                           | 1         | 0.71%   |
| Realtek  Bluetooth Adapter                                           | 1         | 0.71%   |
| Realtek  Bluetooth 4.0 Adapter                                       | 1         | 0.71%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                             | 1         | 0.71%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 1         | 0.71%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 1         | 0.71%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)                      | 1         | 0.71%   |
| Lite-On Realtek Bluetooth Adapter                                    | 1         | 0.71%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 1         | 0.71%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1         | 0.71%   |
| Integrated System Solution Bluetooth Device                          | 1         | 0.71%   |
| IMC Networks Realtek Bluetooth Adapter                               | 1         | 0.71%   |
| IMC Networks Realtek Bluetooth 4.0 Adapter                           | 1         | 0.71%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS                     | 1         | 0.71%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                    | 1         | 0.71%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 0.71%   |
| HP Broadcom 2070 Bluetooth Combo                                     | 1         | 0.71%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0                     | 1         | 0.71%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                      | 1         | 0.71%   |
| Foxconn / Hon Hai Bluetooth USB Module                               | 1         | 0.71%   |
| Dell DW375 Bluetooth Module                                          | 1         | 0.71%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                          | 1         | 0.71%   |
| Broadcom Broadcom BCM2070 Bluetooth 2.1+EDR USB Device               | 1         | 0.71%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1         | 0.71%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 1         | 0.71%   |
| ASUS Bluetooth Controller                                            | 1         | 0.71%   |
| ASUS ASUS USB-BT500                                                  | 1         | 0.71%   |
| Apple Broadcom Bluetooth 2.1 module                                  | 1         | 0.71%   |
| Apple Bluetooth USB Host Controller                                  | 1         | 0.71%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 199       | 52.09%  |
| AMD                              | 77        | 20.16%  |
| Nvidia                           | 67        | 17.54%  |
| C-Media Electronics              | 7         | 1.83%   |
| GN Netcom                        | 6         | 1.57%   |
| Texas Instruments                | 4         | 1.05%   |
| Logitech                         | 3         | 0.79%   |
| JMTek                            | 2         | 0.52%   |
| Yamaha                           | 1         | 0.26%   |
| VIA Technologies                 | 1         | 0.26%   |
| SteelSeries ApS                  | 1         | 0.26%   |
| Silicon Integrated Systems [SiS] | 1         | 0.26%   |
| Nektar                           | 1         | 0.26%   |
| Lenovo                           | 1         | 0.26%   |
| KORG                             | 1         | 0.26%   |
| Kingston Technology              | 1         | 0.26%   |
| Focusrite-Novation               | 1         | 0.26%   |
| FiiO Electronics Technology      | 1         | 0.26%   |
| DSEA A/S                         | 1         | 0.26%   |
| Creative Technology              | 1         | 0.26%   |
| Creative Labs                    | 1         | 0.26%   |
| Corsair                          | 1         | 0.26%   |
| Cambridge Silicon Radio          | 1         | 0.26%   |
| ASUSTek Computer                 | 1         | 0.26%   |
| Astro Gaming                     | 1         | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 29        | 6.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 18        | 4.01%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 17        | 3.79%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 17        | 3.79%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 16        | 3.56%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 15        | 3.34%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 14        | 3.12%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 14        | 3.12%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 13        | 2.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 2.67%   |
| AMD FCH Azalia Controller                                                                         | 12        | 2.67%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 2.45%   |
| Nvidia MCP79 High Definition Audio                                                                | 9         | 2%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 9         | 2%      |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 1.78%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 1.78%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 8         | 1.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 7         | 1.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.56%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 7         | 1.56%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 6         | 1.34%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.34%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 6         | 1.34%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 1.34%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 6         | 1.34%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.11%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 1.11%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 0.89%   |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 0.89%   |
| AMD Navi 10 HDMI Audio                                                                            | 4         | 0.89%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 0.89%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4         | 0.89%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 0.67%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.67%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.67%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.67%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.67%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.67%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.67%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.67%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.67%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.67%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2         | 0.45%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 0.45%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.45%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2         | 0.45%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.45%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.45%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 0.45%   |
| JMTek USB PnP Audio Device                                                                        | 2         | 0.45%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 2         | 0.45%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.45%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 0.45%   |
| GN Netcom Jabra SPEAK 510 USB                                                                     | 2         | 0.45%   |
| C-Media Electronics Digital Hifi Audio Digital Hifi Audio SPDIFs                                  | 2         | 0.45%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 2         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 57        | 17.87%  |
| Kingston            | 56        | 17.55%  |
| Unknown             | 37        | 11.6%   |
| SK Hynix            | 37        | 11.6%   |
| Micron Technology   | 21        | 6.58%   |
| Crucial             | 17        | 5.33%   |
| Corsair             | 16        | 5.02%   |
| G.Skill             | 11        | 3.45%   |
| Nanya Technology    | 8         | 2.51%   |
| Ramaxel Technology  | 7         | 2.19%   |
| A-DATA Technology   | 7         | 2.19%   |
| Unknown             | 6         | 1.88%   |
| Elpida              | 5         | 1.57%   |
| Team                | 4         | 1.25%   |
| Transcend           | 3         | 0.94%   |
| Smart               | 3         | 0.94%   |
| Patriot             | 3         | 0.94%   |
| Silicon Power       | 2         | 0.63%   |
| AMD                 | 2         | 0.63%   |
| 48spaces            | 2         | 0.63%   |
| Unknown (ABCD)      | 1         | 0.31%   |
| Unifosa             | 1         | 0.31%   |
| TakeMS              | 1         | 0.31%   |
| Super Talent        | 1         | 0.31%   |
| Strontium           | 1         | 0.31%   |
| Sesame              | 1         | 0.31%   |
| Kingmax             | 1         | 0.31%   |
| Hikvision           | 1         | 0.31%   |
| High Bridge         | 1         | 0.31%   |
| GOODRAM             | 1         | 0.31%   |
| Goldkey             | 1         | 0.31%   |
| Avant               | 1         | 0.31%   |
| Atermiter           | 1         | 0.31%   |
| ASint Technology    | 1         | 0.31%   |
| Apacer              | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                   | 6         | 1.73%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 5         | 1.44%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 4         | 1.15%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 4         | 1.15%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 4         | 1.15%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1067MT/s                              | 3         | 0.86%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 0.86%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 0.86%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 3         | 0.86%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s                      | 3         | 0.86%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s                   | 3         | 0.86%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                               | 2         | 0.58%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                                 | 2         | 0.58%   |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 2         | 0.58%   |
| Unknown RAM Module 2GB DIMM DDR2                                          | 2         | 0.58%   |
| Unknown RAM Module 2GB DIMM 400MT/s                                       | 2         | 0.58%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                      | 2         | 0.58%   |
| Unknown RAM Module 1GB DIMM SDRAM                                         | 2         | 0.58%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s                       | 2         | 0.58%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 2         | 0.58%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s                     | 2         | 0.58%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.58%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.58%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 2         | 0.58%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s                    | 2         | 0.58%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s                     | 2         | 0.58%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s                | 2         | 0.58%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.58%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                      | 2         | 0.58%   |
| Micron RAM 18KSF51272AZ-1G4M1 4GB DIMM DDR3 1333MT/s                      | 2         | 0.58%   |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                               | 2         | 0.58%   |
| Kingston RAM Module 1GB DIMM DDR2 667MT/s                                 | 2         | 0.58%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 2400MT/s                       | 2         | 0.58%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s                    | 2         | 0.58%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s                     | 2         | 0.58%   |
| Crucial RAM BL16G32C16U4B.16FE 16GB DIMM DDR4 3200MT/s                    | 2         | 0.58%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s                     | 2         | 0.58%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 2667MT/s                     | 2         | 0.58%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 2         | 0.58%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                                 | 1         | 0.29%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                                 | 1         | 0.29%   |
| Unknown RAM Module 512MB DIMM SDRAM                                       | 1         | 0.29%   |
| Unknown RAM Module 4GB SODIMM DDR3 800MT/s                                | 1         | 0.29%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                               | 1         | 0.29%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                               | 1         | 0.29%   |
| Unknown RAM Module 4GB SODIMM DDR3                                        | 1         | 0.29%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                                | 1         | 0.29%   |
| Unknown RAM Module 4GB DIMM SDRAM                                         | 1         | 0.29%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                                 | 1         | 0.29%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                      | 1         | 0.29%   |
| Unknown RAM Module 2GB DIMM SDRAM 533MT/s                                 | 1         | 0.29%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                  | 1         | 0.29%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                                  | 1         | 0.29%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                                  | 1         | 0.29%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                       | 1         | 0.29%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 1         | 0.29%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                                  | 1         | 0.29%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                                  | 1         | 0.29%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2133MT/s          | 1         | 0.29%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s                         | 1         | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 131       | 48.7%   |
| DDR4    | 93        | 34.57%  |
| DDR2    | 25        | 9.29%   |
| Unknown | 9         | 3.35%   |
| SDRAM   | 6         | 2.23%   |
| LPDDR3  | 2         | 0.74%   |
| LPDDR4  | 1         | 0.37%   |
| DRAM    | 1         | 0.37%   |
| DDR     | 1         | 0.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 153       | 57.09%  |
| DIMM         | 114       | 42.54%  |
| Row Of Chips | 1         | 0.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 98        | 33%     |
| 8192  | 85        | 28.62%  |
| 2048  | 67        | 22.56%  |
| 16384 | 29        | 9.76%   |
| 1024  | 13        | 4.38%   |
| 32768 | 4         | 1.35%   |
| 512   | 1         | 0.34%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 74        | 25.08%  |
| 1333    | 39        | 13.22%  |
| 2667    | 25        | 8.47%   |
| 3200    | 22        | 7.46%   |
| 2400    | 22        | 7.46%   |
| 2133    | 21        | 7.12%   |
| 667     | 17        | 5.76%   |
| 1067    | 14        | 4.75%   |
| 1334    | 13        | 4.41%   |
| 800     | 12        | 4.07%   |
| Unknown | 11        | 3.73%   |
| 2666    | 6         | 2.03%   |
| 1867    | 6         | 2.03%   |
| 3600    | 3         | 1.02%   |
| 1066    | 3         | 1.02%   |
| 400     | 2         | 0.68%   |
| 3733    | 1         | 0.34%   |
| 3400    | 1         | 0.34%   |
| 1200    | 1         | 0.34%   |
| 533     | 1         | 0.34%   |
| 333     | 1         | 0.34%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Prolific Technology | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |
| Brother Industries  | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model                                                                                                             | Computers | Percent |
|-------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                                                                                     | 1         | 33.33%  |
| HP HP LaserJet MFP E52645 LaserJet 0 LaserJet 0 LaserJet 1 LaserJet 1 LaserJet 2 LaserJet 2 LaserJet 3 LaserJet 3 | 1         | 33.33%  |
| Brother HL-1430 Laser Printer                                                                                     | 1         | 33.33%  |

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

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 31        | 27.93%  |
| Realtek Semiconductor                  | 9         | 8.11%   |
| IMC Networks                           | 8         | 7.21%   |
| Quanta                                 | 7         | 6.31%   |
| Microdia                               | 7         | 6.31%   |
| Logitech                               | 6         | 5.41%   |
| Acer                                   | 6         | 5.41%   |
| Lite-On Technology                     | 5         | 4.5%    |
| Syntek                                 | 4         | 3.6%    |
| Sunplus Innovation Technology          | 4         | 3.6%    |
| Z-Star Microelectronics                | 3         | 2.7%    |
| Alcor Micro                            | 3         | 2.7%    |
| Suyin                                  | 2         | 1.8%    |
| Lenovo                                 | 2         | 1.8%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.8%    |
| Apple                                  | 2         | 1.8%    |
| Silicon Motion                         | 1         | 0.9%    |
| Ricoh                                  | 1         | 0.9%    |
| Primax Electronics                     | 1         | 0.9%    |
| Luxvisions Innotech Limited            | 1         | 0.9%    |
| Importek                               | 1         | 0.9%    |
| Hewlett-Packard                        | 1         | 0.9%    |
| Genesys Logic                          | 1         | 0.9%    |
| Aveo Technology                        | 1         | 0.9%    |
| Arkmicro Technologies                  | 1         | 0.9%    |
| ARC International                      | 1         | 0.9%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Lenovo Integrated Camera (0.3MP)            | 5         | 4.46%   |
| Chicony HD WebCam                                   | 4         | 3.57%   |
| Realtek USB Camera                                  | 3         | 2.68%   |
| Lite-On Integrated Camera                           | 3         | 2.68%   |
| Chicony EasyCamera                                  | 3         | 2.68%   |
| Syntek Lenovo EasyCamera                            | 2         | 1.79%   |
| Realtek Realtek USB2.0 PC Camera                    | 2         | 1.79%   |
| Realtek Integrated_Webcam_HD                        | 2         | 1.79%   |
| Quanta HP Webcam                                    | 2         | 1.79%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.79%   |
| Microdia Sonix USB 2.0 Camera                       | 2         | 1.79%   |
| Microdia Integrated_Webcam_HD                       | 2         | 1.79%   |
| Microdia Dell Laptop Integrated Webcam HD           | 2         | 1.79%   |
| IMC Networks Integrated Camera                      | 2         | 1.79%   |
| Chicony Integrated Camera                           | 2         | 1.79%   |
| Chicony HD WebCam (Acer)                            | 2         | 1.79%   |
| Chicony Chicony USB 2.0 Camera                      | 2         | 1.79%   |
| Apple FaceTime HD Camera (Built-in)                 | 2         | 1.79%   |
| Acer Lenovo EasyCamera                              | 2         | 1.79%   |
| Z-Star WebCam SC-03FFL11739P                        | 1         | 0.89%   |
| Z-Star Webcam                                       | 1         | 0.89%   |
| Z-Star Lenovo USB2.0 UVC Camera                     | 1         | 0.89%   |
| Syntek EasyCamera                                   | 1         | 0.89%   |
| Syntek ASUS USB2.0 camera                           | 1         | 0.89%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.89%   |
| Suyin HD Video WebCam                               | 1         | 0.89%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 0.89%   |
| Sunplus Integrated Camera                           | 1         | 0.89%   |
| Sunplus HP Universal Camera                         | 1         | 0.89%   |
| Sunplus HD WebCam                                   | 1         | 0.89%   |
| Silicon Motion HP Webcam-50                         | 1         | 0.89%   |
| Ricoh USB2.0 Camera                                 | 1         | 0.89%   |
| Realtek Integrated_Webcam_FHD                       | 1         | 0.89%   |
| Realtek Integrated_Webcam_8M                        | 1         | 0.89%   |
| Realtek HD WebCam                                   | 1         | 0.89%   |
| Quanta VGA WebCam                                   | 1         | 0.89%   |
| Quanta Realtek DMFT - RGB                           | 1         | 0.89%   |
| Quanta HD WebCam                                    | 1         | 0.89%   |
| Primax Dell Laptop Integrated Webcam 2Mpix          | 1         | 0.89%   |
| Microdia Integrated Webcam                          | 1         | 0.89%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 0.89%   |
| Logitech Webcam C930e                               | 1         | 0.89%   |
| Logitech Webcam C310                                | 1         | 0.89%   |
| Logitech Webcam C270                                | 1         | 0.89%   |
| Logitech C922 Pro Stream Webcam                     | 1         | 0.89%   |
| Logitech C670i FHD Webcam                           | 1         | 0.89%   |
| Logitech BRIO Ultra HD Webcam                       | 1         | 0.89%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 0.89%   |
| Lite-On HP HD Camera                                | 1         | 0.89%   |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 0.89%   |
| Lenovo Integrated Webcam                            | 1         | 0.89%   |
| Importek TOSHIBA Web Camera                         | 1         | 0.89%   |
| IMC Networks XHC Camera                             | 1         | 0.89%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 0.89%   |
| IMC Networks USB Camera                             | 1         | 0.89%   |
| IMC Networks SunplusIT Integrated Camera            | 1         | 0.89%   |
| IMC Networks Integrated Webcam                      | 1         | 0.89%   |
| IMC Networks EasyCamera                             | 1         | 0.89%   |
| HP Realtek PC Camera                                | 1         | 0.89%   |
| Genesys Logic Digital Microscope                    | 1         | 0.89%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 32.14%  |
| Upek                       | 8         | 28.57%  |
| AuthenTec                  | 4         | 14.29%  |
| STMicroelectronics         | 3         | 10.71%  |
| LighTuning Technology      | 2         | 7.14%   |
| Synaptics                  | 1         | 3.57%   |
| Shenzhen Goodix Technology | 1         | 3.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 7         | 25%     |
| STMicroelectronics Fingerprint Reader                  | 3         | 10.71%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 7.14%   |
| Validity Sensors VFS491                                | 2         | 7.14%   |
| Validity Sensors Synaptics WBDI                        | 2         | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 3.57%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 3.57%   |
| Validity Sensors Fingerprint scanner                   | 1         | 3.57%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 3.57%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 3.57%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 3.57%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 3.57%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 3.57%   |
| AuthenTec AES2810                                      | 1         | 3.57%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 3.57%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 3.57%   |
| AuthenTec AES1600                                      | 1         | 3.57%   |

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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 110       | 39.43%  |
| 0     | 78        | 27.96%  |
| 2     | 59        | 21.15%  |
| 3     | 22        | 7.89%   |
| 4     | 10        | 3.58%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 156       | 50.49%  |
| Net/wireless             | 60        | 19.42%  |
| Bluetooth                | 32        | 10.36%  |
| Fingerprint reader       | 27        | 8.74%   |
| Card reader              | 21        | 6.8%    |
| Sound                    | 6         | 1.94%   |
| Network                  | 3         | 0.97%   |
| Storage/nvme             | 1         | 0.32%   |
| Storage                  | 1         | 0.32%   |
| Net/ethernet             | 1         | 0.32%   |
| Dvb card                 | 1         | 0.32%   |

