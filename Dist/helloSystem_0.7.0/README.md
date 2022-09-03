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

Total: 432

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Dell          | Precision 7710              | Notebook    | [339099bbf0](https://bsd-hardware.info/?probe=339099bbf0) | Sep 01, 2022 |
| Dell          | Precision 5540              | Notebook    | [0c5089634d](https://bsd-hardware.info/?probe=0c5089634d) | Aug 30, 2022 |
| Dell          | Precision 5540              | Notebook    | [afb80a84fb](https://bsd-hardware.info/?probe=afb80a84fb) | Aug 30, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [17f4ac1979](https://bsd-hardware.info/?probe=17f4ac1979) | Aug 23, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [5ea9441653](https://bsd-hardware.info/?probe=5ea9441653) | Aug 19, 2022 |
| Dell          | Studio 1537                 | Notebook    | [a185649600](https://bsd-hardware.info/?probe=a185649600) | Aug 17, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [f8c10bf25a](https://bsd-hardware.info/?probe=f8c10bf25a) | Aug 15, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [a45977c76b](https://bsd-hardware.info/?probe=a45977c76b) | Aug 10, 2022 |
| ASRock        | Z370 Pro4                   | Desktop     | [038c5f8763](https://bsd-hardware.info/?probe=038c5f8763) | Aug 10, 2022 |
| HP            | ProBook 4540s               | Notebook    | [0a7891d53f](https://bsd-hardware.info/?probe=0a7891d53f) | Aug 06, 2022 |
| eMachines     | eME728                      | Notebook    | [96d745589c](https://bsd-hardware.info/?probe=96d745589c) | Aug 06, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [af241a5384](https://bsd-hardware.info/?probe=af241a5384) | Aug 06, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | Desktop     | [d61693dffb](https://bsd-hardware.info/?probe=d61693dffb) | Aug 05, 2022 |
| ASUSTek       | K30AM-J                     | Desktop     | [e032724bc2](https://bsd-hardware.info/?probe=e032724bc2) | Aug 05, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [850198c512](https://bsd-hardware.info/?probe=850198c512) | Aug 05, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [cddf42b097](https://bsd-hardware.info/?probe=cddf42b097) | Aug 05, 2022 |
| HP            | 1497                        | Desktop     | [c6f6ddf728](https://bsd-hardware.info/?probe=c6f6ddf728) | Aug 04, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [4bd9ec4253](https://bsd-hardware.info/?probe=4bd9ec4253) | Aug 02, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [ad56307789](https://bsd-hardware.info/?probe=ad56307789) | Aug 01, 2022 |
| Lenovo        | ThinkPad T61 7661GY9        | Notebook    | [7ab5339eee](https://bsd-hardware.info/?probe=7ab5339eee) | Jul 30, 2022 |
| HP            | ProBook 430 G4              | Notebook    | [2a9d4e9b0b](https://bsd-hardware.info/?probe=2a9d4e9b0b) | Jul 30, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [55ab4bc8d6](https://bsd-hardware.info/?probe=55ab4bc8d6) | Jul 29, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [6d5bfb02a0](https://bsd-hardware.info/?probe=6d5bfb02a0) | Jul 28, 2022 |
| Dell          | Latitude E7440              | Notebook    | [03497b7b2a](https://bsd-hardware.info/?probe=03497b7b2a) | Jul 27, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [f50526a6d6](https://bsd-hardware.info/?probe=f50526a6d6) | Jul 27, 2022 |
| MAXSUN        | MS-H110D4L FS M.2           | Desktop     | [39d06b12fd](https://bsd-hardware.info/?probe=39d06b12fd) | Jul 25, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [e2a5a65135](https://bsd-hardware.info/?probe=e2a5a65135) | Jul 23, 2022 |
| HP            | ProBook 4730s               | Notebook    | [e70725dd32](https://bsd-hardware.info/?probe=e70725dd32) | Jul 23, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | Notebook    | [b779706b7a](https://bsd-hardware.info/?probe=b779706b7a) | Jul 21, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [a96e41f99e](https://bsd-hardware.info/?probe=a96e41f99e) | Jul 20, 2022 |
| Lenovo        | ThinkPad L412 0585AD9       | Notebook    | [cba0fc2340](https://bsd-hardware.info/?probe=cba0fc2340) | Jul 20, 2022 |
| ASUSTek       | P8B WS                      | Desktop     | [dd7f8123d2](https://bsd-hardware.info/?probe=dd7f8123d2) | Jul 19, 2022 |
| HP            | 8055                        | Desktop     | [269b4f3210](https://bsd-hardware.info/?probe=269b4f3210) | Jul 17, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [64b17b1b35](https://bsd-hardware.info/?probe=64b17b1b35) | Jul 17, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [3c7cfd537b](https://bsd-hardware.info/?probe=3c7cfd537b) | Jul 17, 2022 |
| Shuttle       | FH170                       | Desktop     | [a156048964](https://bsd-hardware.info/?probe=a156048964) | Jul 16, 2022 |
| Shuttle       | FH170                       | Desktop     | [81b62c2839](https://bsd-hardware.info/?probe=81b62c2839) | Jul 16, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [56a7002cc5](https://bsd-hardware.info/?probe=56a7002cc5) | Jul 16, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [db03ba8975](https://bsd-hardware.info/?probe=db03ba8975) | Jul 14, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [ea2f21a15f](https://bsd-hardware.info/?probe=ea2f21a15f) | Jul 12, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [139855ab73](https://bsd-hardware.info/?probe=139855ab73) | Jul 12, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [d680e0d05d](https://bsd-hardware.info/?probe=d680e0d05d) | Jul 10, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [81668557c6](https://bsd-hardware.info/?probe=81668557c6) | Jul 08, 2022 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [1062220932](https://bsd-hardware.info/?probe=1062220932) | Jul 07, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [2c79a92fc4](https://bsd-hardware.info/?probe=2c79a92fc4) | Jul 06, 2022 |
| Dell          | 0F9NPY A02                  | Server      | [f1bb207022](https://bsd-hardware.info/?probe=f1bb207022) | Jul 06, 2022 |
| Dell          | 0F9NPY A02                  | Server      | [919d608fda](https://bsd-hardware.info/?probe=919d608fda) | Jul 05, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [1cd93cd5d3](https://bsd-hardware.info/?probe=1cd93cd5d3) | Jul 04, 2022 |
| Intel         | NUC8i5BESB K75953-303       | Mini pc     | [b0a9749159](https://bsd-hardware.info/?probe=b0a9749159) | Jul 01, 2022 |
| Lenovo        | ThinkPad T430s 2356CV6      | Notebook    | [20df9d5df2](https://bsd-hardware.info/?probe=20df9d5df2) | Jun 29, 2022 |
| Toshiba       | PORTEGE R700                | Notebook    | [d9c359c2ab](https://bsd-hardware.info/?probe=d9c359c2ab) | Jun 28, 2022 |
| Lenovo        | ThinkPad T460 20FN004CUK    | Notebook    | [18b5875c95](https://bsd-hardware.info/?probe=18b5875c95) | Jun 26, 2022 |
| Lenovo        | ThinkPad T410 2522CS7       | Notebook    | [a1561dacb2](https://bsd-hardware.info/?probe=a1561dacb2) | Jun 26, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [4d4993a732](https://bsd-hardware.info/?probe=4d4993a732) | Jun 24, 2022 |
| ALLEGIANCE... | X79 V3.3F                   | Desktop     | [190560a4f4](https://bsd-hardware.info/?probe=190560a4f4) | Jun 23, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [346bc6f0ae](https://bsd-hardware.info/?probe=346bc6f0ae) | Jun 20, 2022 |
| Lenovo        | 300e 81FY                   | Convertible | [eb136e5d7e](https://bsd-hardware.info/?probe=eb136e5d7e) | Jun 20, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [a094c1c53b](https://bsd-hardware.info/?probe=a094c1c53b) | Jun 20, 2022 |
| HP            | Compaq tc4400 (EN357UT#A... | Notebook    | [f4e4e3826b](https://bsd-hardware.info/?probe=f4e4e3826b) | Jun 19, 2022 |
| HP            | 304Bh                       | Desktop     | [8a3151b3cd](https://bsd-hardware.info/?probe=8a3151b3cd) | Jun 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [aaf7ed146a](https://bsd-hardware.info/?probe=aaf7ed146a) | Jun 16, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [6116216a6d](https://bsd-hardware.info/?probe=6116216a6d) | Jun 15, 2022 |
| Alienware     | M18xR2                      | Notebook    | [6d55881f6a](https://bsd-hardware.info/?probe=6d55881f6a) | Jun 15, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [8ba77d7208](https://bsd-hardware.info/?probe=8ba77d7208) | Jun 13, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [f478f5edc1](https://bsd-hardware.info/?probe=f478f5edc1) | Jun 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S45W00    | Notebook    | [acfa5c94d5](https://bsd-hardware.info/?probe=acfa5c94d5) | Jun 12, 2022 |
| HP            | ProBook 4230s               | Notebook    | [8c853f8ca9](https://bsd-hardware.info/?probe=8c853f8ca9) | Jun 11, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [4be2393c8d](https://bsd-hardware.info/?probe=4be2393c8d) | Jun 11, 2022 |
| Lenovo        | ThinkCentre XXXX Y          | Desktop     | [162bbe4eac](https://bsd-hardware.info/?probe=162bbe4eac) | Jun 10, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [d1a197ec53](https://bsd-hardware.info/?probe=d1a197ec53) | Jun 09, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [3b8d6cb36e](https://bsd-hardware.info/?probe=3b8d6cb36e) | Jun 07, 2022 |
| Lenovo        | ThinkPad T420 4236MY0       | Notebook    | [94095d4c11](https://bsd-hardware.info/?probe=94095d4c11) | Jun 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | Notebook    | [8029eb2018](https://bsd-hardware.info/?probe=8029eb2018) | Jun 04, 2022 |
| HP            | Pavilion g4                 | Notebook    | [79d8ca2681](https://bsd-hardware.info/?probe=79d8ca2681) | Jun 04, 2022 |
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
| amd64 | 338       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 335       | 99.11%  |
| GNOME        | 3         | 0.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 338       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 338       | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 320       | 94.4%   |
| es_ES | 5         | 1.47%   |
| de_DE | 5         | 1.47%   |
| C     | 4         | 1.18%   |
| fr_FR | 3         | 0.88%   |
| uk_UA | 1         | 0.29%   |
| it_IT | 1         | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 329       | 97.34%  |
| BIOS | 9         | 2.66%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Cd9660 | 195       | 56.52%  |
| Zfs    | 150       | 43.48%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 333       | 98.52%  |
| MBR  | 5         | 1.48%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 57        | 16.86%  |
| ASUSTek Computer    | 55        | 16.27%  |
| Hewlett-Packard     | 40        | 11.83%  |
| Dell                | 33        | 9.76%   |
| Gigabyte Technology | 30        | 8.88%   |
| Apple               | 21        | 6.21%   |
| Acer                | 18        | 5.33%   |
| Intel               | 14        | 4.14%   |
| ASRock              | 13        | 3.85%   |
| MSI                 | 8         | 2.37%   |
| Toshiba             | 6         | 1.78%   |
| Unknown             | 4         | 1.18%   |
| TUXEDO              | 3         | 0.89%   |
| Samsung Electronics | 3         | 0.89%   |
| Pegatron            | 3         | 0.89%   |
| Fujitsu             | 3         | 0.89%   |
| Sony                | 2         | 0.59%   |
| TWINHEAD            | 1         | 0.3%    |
| T-bao               | 1         | 0.3%    |
| Supermicro          | 1         | 0.3%    |
| Shuttle             | 1         | 0.3%    |
| Razer               | 1         | 0.3%    |
| Quanta              | 1         | 0.3%    |
| Positivo            | 1         | 0.3%    |
| Panasonic           | 1         | 0.3%    |
| Packard Bell        | 1         | 0.3%    |
| OEM                 | 1         | 0.3%    |
| Notebook            | 1         | 0.3%    |
| Medion              | 1         | 0.3%    |
| MAXSUN              | 1         | 0.3%    |
| LG Electronics      | 1         | 0.3%    |
| Koloe               | 1         | 0.3%    |
| Itautec             | 1         | 0.3%    |
| HASEE Computer      | 1         | 0.3%    |
| Gateway             | 1         | 0.3%    |
| eMachines           | 1         | 0.3%    |
| ECS                 | 1         | 0.3%    |
| DNS                 | 1         | 0.3%    |
| BESSTAR Tech        | 1         | 0.3%    |
| ALLEGIANCE GAMING   | 1         | 0.3%    |
| Alienware           | 1         | 0.3%    |
| Acidanthera         | 1         | 0.3%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                               | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Apple iMac9,1                                      | 7         | 2.07%   |
| Unknown                                            | 4         | 1.18%   |
| Apple MacBook4,1                                   | 3         | 0.89%   |
| TUXEDO Aura 15 Gen1                                | 2         | 0.59%   |
| HP EliteDesk 700 G1 SFF                            | 2         | 0.59%   |
| Dell Precision T1700                               | 2         | 0.59%   |
| Dell Latitude E5470                                | 2         | 0.59%   |
| ASUS TUF GAMING X570-PLUS                          | 2         | 0.59%   |
| ASUS PRIME X570-P                                  | 2         | 0.59%   |
| ASUS P8Z77-V LX                                    | 2         | 0.59%   |
| ASRock X570 Phantom Gaming 4                       | 2         | 0.59%   |
| Apple MacBook6,1                                   | 2         | 0.59%   |
| Acer V5-131                                        | 2         | 0.59%   |
| Acer Aspire E1-522                                 | 2         | 0.59%   |
| Acer Aspire 5930                                   | 2         | 0.59%   |
| TWINHEAD U12CT                                     | 1         | 0.3%    |
| TUXEDO InfinityBook13V3                            | 1         | 0.3%    |
| Toshiba Satellite S55t-B                           | 1         | 0.3%    |
| Toshiba Satellite P300                             | 1         | 0.3%    |
| Toshiba Satellite L550                             | 1         | 0.3%    |
| Toshiba Satellite C640                             | 1         | 0.3%    |
| Toshiba Satellite C50-B                            | 1         | 0.3%    |
| Toshiba PORTEGE R700                               | 1         | 0.3%    |
| T-bao MINI PC                                      | 1         | 0.3%    |
| Supermicro X9DAL                                   | 1         | 0.3%    |
| Sony VGN-NW25GF_S                                  | 1         | 0.3%    |
| Sony SVZ1311C5E                                    | 1         | 0.3%    |
| Shuttle XH170                                      | 1         | 0.3%    |
| Samsung N150P/N210P/N220P                          | 1         | 0.3%    |
| Samsung N100                                       | 1         | 0.3%    |
| Samsung 305E4A/305E5A/305E7A                       | 1         | 0.3%    |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.3%    |
| Quanta 120-1135                                    | 1         | 0.3%    |
| Positivo POS-PIQ77CL                               | 1         | 0.3%    |
| Pegatron IPM41-D3                                  | 1         | 0.3%    |
| Pegatron Compaq 505B Microtower PC                 | 1         | 0.3%    |
| Pegatron AY627AA-ABA a4313w                        | 1         | 0.3%    |
| Panasonic CF-B11JWCYS                              | 1         | 0.3%    |
| Packard Bell EasyNote TE69HW                       | 1         | 0.3%    |
| OEM B85 JHS359                                     | 1         | 0.3%    |
| Notebook N15_17RD                                  | 1         | 0.3%    |
| MSI MS-7D25                                        | 1         | 0.3%    |
| MSI MS-7B86                                        | 1         | 0.3%    |
| MSI MS-7A33                                        | 1         | 0.3%    |
| MSI MS-7816                                        | 1         | 0.3%    |
| MSI MS-7758                                        | 1         | 0.3%    |
| MSI MS-7369                                        | 1         | 0.3%    |
| MSI GF65 Thin 10SER                                | 1         | 0.3%    |
| MSI GF63 Thin 10SC                                 | 1         | 0.3%    |
| Medion H61H2-LM3                                   | 1         | 0.3%    |
| MAXSUN MS-H110D4L FS M.2                           | 1         | 0.3%    |
| LG E300-A.CP20T                                    | 1         | 0.3%    |
| Lenovo Z50-70 20354                                | 1         | 0.3%    |
| Lenovo YangTianA8800T                              | 1         | 0.3%    |
| Lenovo V310-14IKB 80T2                             | 1         | 0.3%    |
| Lenovo ThinkPad X61 7675K2U                        | 1         | 0.3%    |
| Lenovo ThinkPad X270 W10DG 20K5S0BM01              | 1         | 0.3%    |
| Lenovo ThinkPad X260 20F5S45W00                    | 1         | 0.3%    |
| Lenovo ThinkPad X250 20CLS1WP01                    | 1         | 0.3%    |
| Lenovo ThinkPad X240 20AMS2QDOC                    | 1         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 34        | 10.06%  |
| Acer Aspire             | 13        | 3.85%   |
| HP Pavilion             | 10        | 2.96%   |
| Dell Latitude           | 10        | 2.96%   |
| ASUS PRIME              | 9         | 2.66%   |
| Lenovo IdeaPad          | 7         | 2.07%   |
| Dell Inspiron           | 7         | 2.07%   |
| Apple iMac9             | 7         | 2.07%   |
| HP ProBook              | 6         | 1.78%   |
| Dell OptiPlex           | 6         | 1.78%   |
| ASUS ROG                | 6         | 1.78%   |
| Toshiba Satellite       | 5         | 1.48%   |
| Lenovo ThinkCentre      | 5         | 1.48%   |
| HP EliteDesk            | 5         | 1.48%   |
| HP Compaq               | 5         | 1.48%   |
| ASUS TUF                | 5         | 1.48%   |
| Dell Precision          | 4         | 1.18%   |
| Unknown                 | 4         | 1.18%   |
| HP Laptop               | 3         | 0.89%   |
| HP EliteBook            | 3         | 0.89%   |
| Gigabyte X570           | 3         | 0.89%   |
| Apple MacBook4          | 3         | 0.89%   |
| TUXEDO Aura             | 2         | 0.59%   |
| Gigabyte B450           | 2         | 0.59%   |
| Fujitsu ESPRIMO         | 2         | 0.59%   |
| Dell Vostro             | 2         | 0.59%   |
| Dell PowerEdge          | 2         | 0.59%   |
| ASUS P8Z77-V            | 2         | 0.59%   |
| ASUS P5GC-MX            | 2         | 0.59%   |
| ASUS Maximus            | 2         | 0.59%   |
| ASRock X570             | 2         | 0.59%   |
| Apple MacBook6          | 2         | 0.59%   |
| Apple MacBook5          | 2         | 0.59%   |
| Acer V5-131             | 2         | 0.59%   |
| TWINHEAD U12CT          | 1         | 0.3%    |
| TUXEDO InfinityBook13V3 | 1         | 0.3%    |
| Toshiba PORTEGE         | 1         | 0.3%    |
| T-bao MINI              | 1         | 0.3%    |
| Supermicro X9DAL        | 1         | 0.3%    |
| Sony VGN-NW25GF         | 1         | 0.3%    |
| Sony SVZ1311C5E         | 1         | 0.3%    |
| Shuttle XH170           | 1         | 0.3%    |
| Samsung N150P           | 1         | 0.3%    |
| Samsung N100            | 1         | 0.3%    |
| Samsung 305E4A          | 1         | 0.3%    |
| Razer Blade             | 1         | 0.3%    |
| Quanta 120-1135         | 1         | 0.3%    |
| Positivo POS-PIQ77CL    | 1         | 0.3%    |
| Pegatron IPM41-D3       | 1         | 0.3%    |
| Pegatron Compaq         | 1         | 0.3%    |
| Pegatron AY627AA-ABA    | 1         | 0.3%    |
| Panasonic CF-B11JWCYS   | 1         | 0.3%    |
| Packard Bell EasyNote   | 1         | 0.3%    |
| OEM B85                 | 1         | 0.3%    |
| Notebook N15            | 1         | 0.3%    |
| MSI MS-7D25             | 1         | 0.3%    |
| MSI MS-7B86             | 1         | 0.3%    |
| MSI MS-7A33             | 1         | 0.3%    |
| MSI MS-7816             | 1         | 0.3%    |
| MSI MS-7758             | 1         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 38        | 11.24%  |
| 2018    | 30        | 8.88%   |
| 2019    | 29        | 8.58%   |
| 2012    | 26        | 7.69%   |
| 2009    | 26        | 7.69%   |
| 2013    | 24        | 7.1%    |
| 2020    | 22        | 6.51%   |
| 2010    | 22        | 6.51%   |
| 2016    | 21        | 6.21%   |
| 2015    | 19        | 5.62%   |
| 2011    | 19        | 5.62%   |
| 2017    | 18        | 5.33%   |
| 2014    | 18        | 5.33%   |
| 2008    | 10        | 2.96%   |
| 2007    | 10        | 2.96%   |
| 2022    | 3         | 0.89%   |
| 2006    | 2         | 0.59%   |
| Unknown | 1         | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 164       | 48.52%  |
| Desktop     | 149       | 44.08%  |
| Mini pc     | 12        | 3.55%   |
| All in one  | 11        | 3.25%   |
| Convertible | 1         | 0.3%    |
| Server      | 1         | 0.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 338       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 101       | 29.88%  |
| 4.01-8.0    | 98        | 28.99%  |
| 16.01-24.0  | 74        | 21.89%  |
| 32.01-64.0  | 31        | 9.17%   |
| 2.01-3.0    | 17        | 5.03%   |
| 64.01-256.0 | 7         | 2.07%   |
| 3.01-4.0    | 4         | 1.18%   |
| 24.01-32.0  | 4         | 1.18%   |
| 1.01-2.0    | 1         | 0.3%    |
| 0.51-1.0    | 1         | 0.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 180       | 53.1%   |
| 0.51-1.0  | 103       | 30.38%  |
| 1.01-2.0  | 45        | 13.27%  |
| 2.01-3.0  | 9         | 2.65%   |
| 3.01-4.0  | 1         | 0.29%   |
| 8.01-16.0 | 1         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 204       | 59.48%  |
| 2      | 83        | 24.2%   |
| 3      | 17        | 4.96%   |
| 0      | 17        | 4.96%   |
| 4      | 14        | 4.08%   |
| 5      | 4         | 1.17%   |
| 6      | 2         | 0.58%   |
| 9      | 1         | 0.29%   |
| 7      | 1         | 0.29%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 198       | 58.58%  |
| Yes       | 140       | 41.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 325       | 96.15%  |
| No        | 13        | 3.85%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 231       | 68.34%  |
| No        | 107       | 31.66%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 170       | 50.3%   |
| Yes       | 168       | 49.7%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country             | Computers | Percent |
|---------------------|-----------|---------|
| USA                 | 54        | 15.98%  |
| Russia              | 34        | 10.06%  |
| Germany             | 21        | 6.21%   |
| Brazil              | 19        | 5.62%   |
| Italy               | 16        | 4.73%   |
| China               | 15        | 4.44%   |
| Spain               | 14        | 4.14%   |
| Canada              | 13        | 3.85%   |
| UK                  | 12        | 3.55%   |
| Poland              | 12        | 3.55%   |
| Ukraine             | 10        | 2.96%   |
| France              | 10        | 2.96%   |
| Hungary             | 9         | 2.66%   |
| Romania             | 8         | 2.37%   |
| Netherlands         | 6         | 1.78%   |
| Mexico              | 6         | 1.78%   |
| India               | 6         | 1.78%   |
| Turkey              | 5         | 1.48%   |
| Vietnam             | 4         | 1.18%   |
| Peru                | 4         | 1.18%   |
| Norway              | 4         | 1.18%   |
| Indonesia           | 4         | 1.18%   |
| Australia           | 4         | 1.18%   |
| Portugal            | 3         | 0.89%   |
| Greece              | 3         | 0.89%   |
| Denmark             | 3         | 0.89%   |
| Chile               | 3         | 0.89%   |
| Taiwan              | 2         | 0.59%   |
| Sweden              | 2         | 0.59%   |
| South Korea         | 2         | 0.59%   |
| New Zealand         | 2         | 0.59%   |
| Finland             | 2         | 0.59%   |
| Colombia            | 2         | 0.59%   |
| Argentina           | 2         | 0.59%   |
| Venezuela           | 1         | 0.3%    |
| Trinidad and Tobago | 1         | 0.3%    |
| Thailand            | 1         | 0.3%    |
| Tanzania            | 1         | 0.3%    |
| South Africa        | 1         | 0.3%    |
| Serbia              | 1         | 0.3%    |
| Philippines         | 1         | 0.3%    |
| Panama              | 1         | 0.3%    |
| Myanmar             | 1         | 0.3%    |
| Malaysia            | 1         | 0.3%    |
| Lithuania           | 1         | 0.3%    |
| Latvia              | 1         | 0.3%    |
| Kazakhstan          | 1         | 0.3%    |
| Ireland             | 1         | 0.3%    |
| Iran                | 1         | 0.3%    |
| Iceland             | 1         | 0.3%    |
| Georgia             | 1         | 0.3%    |
| Czechia             | 1         | 0.3%    |
| Cuba                | 1         | 0.3%    |
| Bulgaria            | 1         | 0.3%    |
| Belarus             | 1         | 0.3%    |
| Austria             | 1         | 0.3%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Moscow                        | 7         | 2.02%   |
| St Petersburg                 | 5         | 1.44%   |
| Lima                          | 4         | 1.15%   |
| Hanoi                         | 4         | 1.15%   |
| Warsaw                        | 3         | 0.86%   |
| Sao Paulo                     | 3         | 0.86%   |
| Rio de Janeiro                | 3         | 0.86%   |
| Kharkiv                       | 3         | 0.86%   |
| Guangzhou                     | 3         | 0.86%   |
| Curitiba                      | 3         | 0.86%   |
| Bucharest                     | 3         | 0.86%   |
| Amsterdam                     | 3         | 0.86%   |
| Tromsø                       | 2         | 0.58%   |
| Tiruchi                       | 2         | 0.58%   |
| Surgut                        | 2         | 0.58%   |
| Suceava                       | 2         | 0.58%   |
| Smiths Falls                  | 2         | 0.58%   |
| Sherwood Park                 | 2         | 0.58%   |
| Scottsdale                    | 2         | 0.58%   |
| San SebastiÃ¡n de los Reyes | 2         | 0.58%   |
| Pflugerville                  | 2         | 0.58%   |
| Perth                         | 2         | 0.58%   |
| Novosibirsk                   | 2         | 0.58%   |
| Myrtle Beach                  | 2         | 0.58%   |
| Leatherhead                   | 2         | 0.58%   |
| Kyiv                          | 2         | 0.58%   |
| Katowice                      | 2         | 0.58%   |
| Jakarta                       | 2         | 0.58%   |
| Izhevsk                       | 2         | 0.58%   |
| Istanbul                      | 2         | 0.58%   |
| Dreieich                      | 2         | 0.58%   |
| Dijon                         | 2         | 0.58%   |
| Coria del RÃ­o              | 2         | 0.58%   |
| Castilleja de la Cuesta       | 2         | 0.58%   |
| Beijing                       | 2         | 0.58%   |
| Barnaul                       | 2         | 0.58%   |
| Ankara                        | 2         | 0.58%   |
| Adelfia                       | 2         | 0.58%   |
| Zhengzhou                     | 1         | 0.29%   |
| Zhaoqing                      | 1         | 0.29%   |
| Zaporizhzhya                  | 1         | 0.29%   |
| Zapopan                       | 1         | 0.29%   |
| Yunlin                        | 1         | 0.29%   |
| Youngsville                   | 1         | 0.29%   |
| Yichun                        | 1         | 0.29%   |
| Yaphank                       | 1         | 0.29%   |
| Yangon                        | 1         | 0.29%   |
| Xicheng District              | 1         | 0.29%   |
| Windsor                       | 1         | 0.29%   |
| Washington                    | 1         | 0.29%   |
| Vilnius                       | 1         | 0.29%   |
| Ventura                       | 1         | 0.29%   |
| VÃ¤sterÃ¥s                | 1         | 0.29%   |
| Vaudreuil-Dorion              | 1         | 0.29%   |
| Vandalia                      | 1         | 0.29%   |
| Vancouver                     | 1         | 0.29%   |
| Ugarchin                      | 1         | 0.29%   |
| Tver                          | 1         | 0.29%   |
| Turley                        | 1         | 0.29%   |
| Turin                         | 1         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 83        | 102    | 17.4%   |
| Seagate             | 77        | 99     | 16.14%  |
| Samsung Electronics | 75        | 95     | 15.72%  |
| Toshiba             | 35        | 39     | 7.34%   |
| Kingston            | 33        | 38     | 6.92%   |
| Crucial             | 28        | 34     | 5.87%   |
| SanDisk             | 17        | 18     | 3.56%   |
| Hitachi             | 15        | 16     | 3.14%   |
| Intel               | 14        | 15     | 2.94%   |
| A-DATA Technology   | 11        | 12     | 2.31%   |
| HGST                | 9         | 9      | 1.89%   |
| SK hynix            | 6         | 8      | 1.26%   |
| Patriot             | 6         | 6      | 1.26%   |
| Phison              | 5         | 5      | 1.05%   |
| Micron Technology   | 5         | 5      | 1.05%   |
| Goodram             | 5         | 6      | 1.05%   |
| XPG                 | 4         | 4      | 0.84%   |
| KingSpec            | 4         | 4      | 0.84%   |
| Fujitsu             | 4         | 4      | 0.84%   |
| SPCC                | 3         | 4      | 0.63%   |
| OCZ                 | 3         | 3      | 0.63%   |
| Intenso             | 3         | 3      | 0.63%   |
| Team                | 2         | 2      | 0.42%   |
| PNY                 | 2         | 2      | 0.42%   |
| Mushkin             | 2         | 2      | 0.42%   |
| LITEON              | 2         | 3      | 0.42%   |
| Gigabyte Technology | 2         | 3      | 0.42%   |
| Apple               | 2         | 2      | 0.42%   |
| Apacer              | 2         | 2      | 0.42%   |
| Zheino              | 1         | 1      | 0.21%   |
| Transcend           | 1         | 1      | 0.21%   |
| tigo                | 1         | 1      | 0.21%   |
| SSSTC               | 1         | 1      | 0.21%   |
| Silicon Motion      | 1         | 1      | 0.21%   |
| Plextor             | 1         | 1      | 0.21%   |
| Netac               | 1         | 1      | 0.21%   |
| Lite-On             | 1         | 1      | 0.21%   |
| Lexar               | 1         | 1      | 0.21%   |
| KIOXIA              | 1         | 1      | 0.21%   |
| Integral            | 1         | 1      | 0.21%   |
| INDMEM              | 1         | 1      | 0.21%   |
| Hewlett-Packard     | 1         | 1      | 0.21%   |
| EMTEC               | 1         | 1      | 0.21%   |
| Corsair             | 1         | 1      | 0.21%   |
| China               | 1         | 1      | 0.21%   |
| ANACOMDA            | 1         | 1      | 0.21%   |
| AGI                 | 1         | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Kingston SA400S37120G 120GB             | 9         | 1.75%   |
| HGST HTS545050A7E680 500GB              | 6         | 1.17%   |
| Crucial CT500MX500SSD1 500GB            | 6         | 1.17%   |
| Crucial CT240BX500SSD1 240GB            | 6         | 1.17%   |
| WDC WDS120G2G0A-00JH30 120GB            | 5         | 0.97%   |
| Toshiba MQ01ABF050 500GB                | 5         | 0.97%   |
| Seagate ST1000DM010-2EP102 1TB          | 5         | 0.97%   |
| Kingston SA400S37240G 240GB             | 5         | 0.97%   |
| XPG GAMMIX S11 Pro 256GB                | 4         | 0.78%   |
| WDC WDS240G2G0A-00JH30 240GB            | 4         | 0.78%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 4         | 0.78%   |
| Seagate ST1000DM003-1ER162 1TB          | 4         | 0.78%   |
| Samsung SSD 980 PRO 1TB                 | 4         | 0.78%   |
| Toshiba MQ01ABD100 1TB                  | 3         | 0.58%   |
| Toshiba HDWD110 1TB                     | 3         | 0.58%   |
| Seagate ST4000DM004-2CV104 4TB          | 3         | 0.58%   |
| Seagate ST31000528AS 1TB                | 3         | 0.58%   |
| Seagate ST2000DM008-2FR102 2TB          | 3         | 0.58%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 0.58%   |
| Samsung SSD 970 EVO Plus 1TB            | 3         | 0.58%   |
| Samsung SSD 870 EVO 500GB               | 3         | 0.58%   |
| Samsung SSD 860 EVO 500GB               | 3         | 0.58%   |
| Samsung SSD 860 EVO 250GB               | 3         | 0.58%   |
| Samsung SSD 860 EVO 1TB                 | 3         | 0.58%   |
| Samsung SSD 850 EVO 500GB               | 3         | 0.58%   |
| Samsung SSD 850 EVO 250GB               | 3         | 0.58%   |
| Samsung HD322HJ 320GB                   | 3         | 0.58%   |
| Crucial CT120BX500SSD1 120GB            | 3         | 0.58%   |
| WDC WDS500G2B0C-00PXH0 500GB            | 2         | 0.39%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 2         | 0.39%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 2         | 0.39%   |
| WDC WD20PURZ-85GU6Y0 2TB                | 2         | 0.39%   |
| WDC WD1600AAJS-40H3A0 160GB             | 2         | 0.39%   |
| WDC WD10JPCX-24UE4T0 1TB                | 2         | 0.39%   |
| Toshiba DT01ACA100 1TB                  | 2         | 0.39%   |
| Toshiba DT01ACA050 500GB                | 2         | 0.39%   |
| SK hynix HFS256G39TND-N210A 256GB       | 2         | 0.39%   |
| SK hynix BC501 HFM128GDJTNG-8310A 128GB | 2         | 0.39%   |
| Seagate ST9500325AS 500GB               | 2         | 0.39%   |
| Seagate ST500LT012-9WS142 500GB         | 2         | 0.39%   |
| Seagate ST3500418AS 500GB               | 2         | 0.39%   |
| Seagate ST3500413AS 500GB               | 2         | 0.39%   |
| Seagate ST3320418AS 320GB               | 2         | 0.39%   |
| Seagate ST320LT020-9YG142 320GB         | 2         | 0.39%   |
| Seagate ST3160812AS 160GB               | 2         | 0.39%   |
| Seagate ST1000LM035-1RK172 1TB          | 2         | 0.39%   |
| Seagate ST1000DM003-1CH162 1TB          | 2         | 0.39%   |
| SanDisk SDSSDA120G 120GB                | 2         | 0.39%   |
| Samsung SSD PM871 2.5 7mm 128GB         | 2         | 0.39%   |
| Samsung SSD 970 EVO Plus 500GB          | 2         | 0.39%   |
| Samsung SSD 970 EVO 250GB               | 2         | 0.39%   |
| Samsung SSD 850 EVO 120GB               | 2         | 0.39%   |
| Samsung SSD 840 PRO Series 128GB        | 2         | 0.39%   |
| Samsung SSD 750 EVO 120GB               | 2         | 0.39%   |
| Samsung Portable SSD T5 500GB           | 2         | 0.39%   |
| Samsung MZVLW256HEHP-000L7 256GB        | 2         | 0.39%   |
| Patriot Burst 240GB                     | 2         | 0.39%   |
| Patriot Burst 120GB                     | 2         | 0.39%   |
| Kingston SV300S37A120G 120GB            | 2         | 0.39%   |
| Kingston SA2000M81000G 1TB              | 2         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 76        | 95     | 36.54%  |
| WDC                 | 61        | 69     | 29.33%  |
| Toshiba             | 32        | 36     | 15.38%  |
| Hitachi             | 15        | 16     | 7.21%   |
| Samsung Electronics | 11        | 11     | 5.29%   |
| HGST                | 9         | 9      | 4.33%   |
| Fujitsu             | 3         | 3      | 1.44%   |
| Apple               | 1         | 1      | 0.48%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 42        | 47     | 20.69%  |
| Crucial             | 27        | 32     | 13.3%   |
| Kingston            | 26        | 29     | 12.81%  |
| SanDisk             | 17        | 18     | 8.37%   |
| WDC                 | 14        | 18     | 6.9%    |
| Intel               | 11        | 11     | 5.42%   |
| A-DATA Technology   | 9         | 9      | 4.43%   |
| Patriot             | 6         | 6      | 2.96%   |
| Goodram             | 5         | 6      | 2.46%   |
| KingSpec            | 4         | 4      | 1.97%   |
| SPCC                | 3         | 4      | 1.48%   |
| SK hynix            | 3         | 3      | 1.48%   |
| OCZ                 | 3         | 3      | 1.48%   |
| Intenso             | 3         | 3      | 1.48%   |
| Toshiba             | 2         | 2      | 0.99%   |
| Team                | 2         | 2      | 0.99%   |
| PNY                 | 2         | 2      | 0.99%   |
| LITEON              | 2         | 3      | 0.99%   |
| Gigabyte Technology | 2         | 3      | 0.99%   |
| Apacer              | 2         | 2      | 0.99%   |
| Zheino              | 1         | 1      | 0.49%   |
| Transcend           | 1         | 1      | 0.49%   |
| tigo                | 1         | 1      | 0.49%   |
| Plextor             | 1         | 1      | 0.49%   |
| Netac               | 1         | 1      | 0.49%   |
| Mushkin             | 1         | 1      | 0.49%   |
| Micron Technology   | 1         | 1      | 0.49%   |
| Lite-On             | 1         | 1      | 0.49%   |
| Lexar               | 1         | 1      | 0.49%   |
| Integral            | 1         | 1      | 0.49%   |
| INDMEM              | 1         | 1      | 0.49%   |
| Hewlett-Packard     | 1         | 1      | 0.49%   |
| Fujitsu             | 1         | 1      | 0.49%   |
| EMTEC               | 1         | 1      | 0.49%   |
| Corsair             | 1         | 1      | 0.49%   |
| China               | 1         | 1      | 0.49%   |
| Apple               | 1         | 1      | 0.49%   |
| ANACOMDA            | 1         | 1      | 0.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 177       | 240    | 42.14%  |
| SSD  | 171       | 225    | 40.71%  |
| NVMe | 72        | 98     | 17.14%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 295       | 465    | 80.38%  |
| NVMe | 72        | 98     | 19.62%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 247       | 334    | 69.97%  |
| 0.51-1.0   | 70        | 84     | 19.83%  |
| 1.01-2.0   | 17        | 19     | 4.82%   |
| 3.01-4.0   | 9         | 16     | 2.55%   |
| 2.01-3.0   | 5         | 6      | 1.42%   |
| 4.01-10.0  | 4         | 5      | 1.13%   |
| 10.01-20.0 | 1         | 1      | 0.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 189       | 54.78%  |
| 101-250    | 75        | 21.74%  |
| 251-500    | 45        | 13.04%  |
| 501-1000   | 21        | 6.09%   |
| 21-50      | 7         | 2.03%   |
| 51-100     | 7         | 2.03%   |
| Unknown    | 1         | 0.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 333       | 98.52%  |
| 21-50   | 3         | 0.89%   |
| 101-250 | 1         | 0.3%    |
| Unknown | 1         | 0.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST3500413AS 500GB           | 2         | 3      | 2.22%   |
| Seagate ST3320418AS 320GB           | 2         | 2      | 2.22%   |
| Seagate ST31000528AS 1TB            | 2         | 3      | 2.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 2      | 2.22%   |
| WDC WD60EZRZ-00RWYB1 6TB            | 1         | 1      | 1.11%   |
| WDC WD5000LPLX-60ZNTT1 500GB        | 1         | 1      | 1.11%   |
| WDC WD5000LPCX-75VHAT0 500GB        | 1         | 1      | 1.11%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 1         | 1      | 1.11%   |
| WDC WD5000BPVT-22HXZT3 500GB        | 1         | 1      | 1.11%   |
| WDC WD5000AZLX-00CL5A0 500GB        | 1         | 1      | 1.11%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1         | 1      | 1.11%   |
| WDC WD5000AAKS-22A7B0 500GB         | 1         | 1      | 1.11%   |
| WDC WD400JB-00ENA0 40GB             | 1         | 1      | 1.11%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 1      | 1.11%   |
| WDC WD3200AAJS-22B4A0 320GB         | 1         | 1      | 1.11%   |
| WDC WD20EURS-63S48Y0 2TB            | 1         | 1      | 1.11%   |
| WDC WD1600BEVT-80A23T0 160GB        | 1         | 1      | 1.11%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 1         | 1      | 1.11%   |
| WDC WD1600BEKT-66F3T2 160GB         | 1         | 1      | 1.11%   |
| WDC WD1600AAJS-40H3A0 160GB         | 1         | 1      | 1.11%   |
| WDC WD10SPZX-24Z10T0 1TB            | 1         | 1      | 1.11%   |
| WDC WD10JPVX-22JC3T0 1TB            | 1         | 1      | 1.11%   |
| WDC WD10EZEX-08M2NA0 1TB            | 1         | 1      | 1.11%   |
| WDC WD10EARS-003BB1 1TB             | 1         | 1      | 1.11%   |
| Toshiba THNSNX024GMNT 24GB          | 1         | 1      | 1.11%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 1.11%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 1.11%   |
| Toshiba MQ01ABD075 752GB            | 1         | 1      | 1.11%   |
| Toshiba MQ01ABD025 250GB            | 1         | 1      | 1.11%   |
| Toshiba MK8034GSX 80GB              | 1         | 1      | 1.11%   |
| Toshiba MK7559GSXF 752GB            | 1         | 1      | 1.11%   |
| Toshiba MK6034GSX 64GB              | 1         | 1      | 1.11%   |
| Toshiba MK3265GSXN 320GB            | 1         | 1      | 1.11%   |
| Toshiba MK3261GSYN 320GB            | 1         | 1      | 1.11%   |
| Toshiba MD04ACA400 4TB              | 1         | 1      | 1.11%   |
| Toshiba DT01ACA100 1TB              | 1         | 3      | 1.11%   |
| Toshiba DT01ABA300 3TB              | 1         | 1      | 1.11%   |
| Seagate ST9640320AS 640GB           | 1         | 1      | 1.11%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 1.11%   |
| Seagate ST9320423AS 320GB           | 1         | 1      | 1.11%   |
| Seagate ST9120821AS 118GB           | 1         | 1      | 1.11%   |
| Seagate ST8000NM0055-1RM112 8TB     | 1         | 1      | 1.11%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1      | 1.11%   |
| Seagate ST380211AS 80GB             | 1         | 1      | 1.11%   |
| Seagate ST3500418AS 500GB           | 1         | 1      | 1.11%   |
| Seagate ST3250310AS 250GB           | 1         | 1      | 1.11%   |
| Seagate ST320LT020-9YG142 320GB     | 1         | 1      | 1.11%   |
| Seagate ST320LT007-9ZV142 320GB     | 1         | 1      | 1.11%   |
| Seagate ST320LM000 HM321HI 320GB    | 1         | 2      | 1.11%   |
| Seagate ST3160812AS 160GB           | 1         | 1      | 1.11%   |
| Seagate ST3160212AS 160GB           | 1         | 1      | 1.11%   |
| Seagate ST31000520AS 1TB            | 1         | 1      | 1.11%   |
| Seagate ST1000DM003-1ER162 1TB      | 1         | 1      | 1.11%   |
| SanDisk SSD PLUS 240GB              | 1         | 1      | 1.11%   |
| Samsung Electronics SSD 970 EVO 2TB | 1         | 1      | 1.11%   |
| Samsung Electronics SSD 870 EVO 1TB | 1         | 1      | 1.11%   |
| Samsung Electronics SSD 860 EVO 1TB | 1         | 2      | 1.11%   |
| Samsung Electronics HS082HB 80GB    | 1         | 1      | 1.11%   |
| Samsung Electronics HM160HI 160GB   | 1         | 1      | 1.11%   |
| Samsung Electronics HD322HJ 320GB   | 1         | 1      | 1.11%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 27     | 26.44%  |
| WDC                 | 20        | 20     | 22.99%  |
| Toshiba             | 12        | 15     | 13.79%  |
| Hitachi             | 9         | 10     | 10.34%  |
| Samsung Electronics | 7         | 9      | 8.05%   |
| Kingston            | 4         | 4      | 4.6%    |
| Intel               | 2         | 2      | 2.3%    |
| HGST                | 2         | 2      | 2.3%    |
| Crucial             | 2         | 2      | 2.3%    |
| SanDisk             | 1         | 1      | 1.15%   |
| LITEON              | 1         | 1      | 1.15%   |
| KingSpec            | 1         | 1      | 1.15%   |
| Fujitsu             | 1         | 1      | 1.15%   |
| AGI                 | 1         | 1      | 1.15%   |
| A-DATA Technology   | 1         | 1      | 1.15%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 27     | 32.39%  |
| WDC                 | 20        | 20     | 28.17%  |
| Toshiba             | 11        | 14     | 15.49%  |
| Hitachi             | 9         | 10     | 12.68%  |
| Samsung Electronics | 5         | 5      | 7.04%   |
| HGST                | 2         | 2      | 2.82%   |
| Fujitsu             | 1         | 1      | 1.41%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 65        | 79     | 79.27%  |
| SSD  | 14        | 15     | 17.07%  |
| NVMe | 3         | 3      | 3.66%   |

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
| Works    | 271       | 462    | 76.55%  |
| Malfunc  | 79        | 97     | 22.32%  |
| Detected | 3         | 3      | 0.85%   |
| Failed   | 1         | 1      | 0.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 247       | 59.23%  |
| AMD                              | 61        | 14.63%  |
| Samsung Electronics              | 30        | 7.19%   |
| Nvidia                           | 18        | 4.32%   |
| SanDisk                          | 10        | 2.4%    |
| Kingston Technology Company      | 6         | 1.44%   |
| ADATA Technology                 | 6         | 1.44%   |
| Phison Electronics               | 5         | 1.2%    |
| Micron Technology                | 4         | 0.96%   |
| Marvell Technology Group         | 4         | 0.96%   |
| SK hynix                         | 3         | 0.72%   |
| Silicon Motion                   | 3         | 0.72%   |
| JMicron Technology               | 3         | 0.72%   |
| Broadcom / LSI                   | 3         | 0.72%   |
| ASMedia Technology               | 3         | 0.72%   |
| Seagate Technology               | 2         | 0.48%   |
| Micron/Crucial Technology        | 2         | 0.48%   |
| KIOXIA                           | 2         | 0.48%   |
| VIA Technologies                 | 1         | 0.24%   |
| Solid State Storage Technology   | 1         | 0.24%   |
| Silicon Integrated Systems [SiS] | 1         | 0.24%   |
| Realtek Semiconductor            | 1         | 0.24%   |
| Apple                            | 1         | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 50        | 10.59%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 18        | 3.81%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 18        | 3.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 16        | 3.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 15        | 3.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 13        | 2.75%   |
| Nvidia MCP79 AHCI Controller                                                     | 13        | 2.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 13        | 2.75%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 12        | 2.54%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 11        | 2.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 11        | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 11        | 2.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 10        | 2.12%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 10        | 2.12%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 10        | 2.12%   |
| Intel SATA Controller [RAID mode]                                                | 9         | 1.91%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 9         | 1.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 9         | 1.91%   |
| Unknown                                                                          | 9         | 1.91%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 8         | 1.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 8         | 1.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 7         | 1.48%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 1.48%   |
| AMD 400 Series Chipset SATA Controller                                           | 7         | 1.48%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 6         | 1.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 1.27%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 6         | 1.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 5         | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 1.06%   |
| Samsung NVMe SSD Controller 980                                                  | 4         | 0.85%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 0.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 0.85%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 4         | 0.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 4         | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 0.85%   |
| AMD 300 Series Chipset SATA Controller                                           | 4         | 0.85%   |
| Phison E12 NVMe Controller                                                       | 3         | 0.64%   |
| Nvidia MCP61 SATA Controller                                                     | 3         | 0.64%   |
| Kingston Company A2000 NVMe SSD                                                  | 3         | 0.64%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 0.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 0.64%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 0.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 3         | 0.64%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 0.64%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 3         | 0.64%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3         | 0.64%   |
| AMD FCH SATA Controller D                                                        | 3         | 0.64%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 0.42%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.42%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 0.42%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 0.42%   |
| JMicron JMB363 SATA/IDE Controller                                               | 2         | 0.42%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 0.42%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.42%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 2         | 0.42%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2         | 0.42%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2         | 0.42%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                       | 2         | 0.42%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                       | 2         | 0.42%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 283       | 67.22%  |
| NVMe | 72        | 17.1%   |
| IDE  | 46        | 10.93%  |
| RAID | 18        | 4.28%   |
| SAS  | 1         | 0.24%   |
| SCSI | 1         | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 268       | 79.29%  |
| AMD    | 70        | 20.71%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz           | 8         | 2.37%   |
| Intel CPU Version                           | 5         | 1.48%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 5         | 1.48%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4         | 1.18%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4         | 1.18%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 4         | 1.18%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 4         | 1.18%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz        | 4         | 1.18%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 3         | 0.89%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3         | 0.89%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 0.89%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 0.89%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 3         | 0.89%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 0.89%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 0.89%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz        | 3         | 0.89%   |
| Intel Core 2 Duo CPU E8135 @ 2.66GHz        | 3         | 0.89%   |
| Intel Core 2 Duo                            | 3         | 0.89%   |
| Intel Xeon CPU X3470 @ 2.93GHz              | 2         | 0.59%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz         | 2         | 0.59%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 2         | 0.59%   |
| Intel Pentium CPU G860 @ 3.00GHz            | 2         | 0.59%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 2         | 0.59%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 0.59%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2         | 0.59%   |
| Intel Core i7-3612QM CPU @ 2.10GHz          | 2         | 0.59%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2         | 0.59%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 2         | 0.59%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 0.59%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 0.59%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2         | 0.59%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2         | 0.59%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 0.59%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2         | 0.59%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2         | 0.59%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 2         | 0.59%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 2         | 0.59%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 2         | 0.59%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2         | 0.59%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 2         | 0.59%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2         | 0.59%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 2         | 0.59%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 2         | 0.59%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 0.59%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2         | 0.59%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 2         | 0.59%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz        | 2         | 0.59%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 0.59%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 2         | 0.59%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 0.59%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 2         | 0.59%   |
| Intel Atom CPU N450 @ 1.66GHz               | 2         | 0.59%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2         | 0.59%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2         | 0.59%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 2         | 0.59%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2         | 0.59%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2         | 0.59%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2         | 0.59%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2         | 0.59%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2         | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 87        | 25.74%  |
| Intel Core i7           | 36        | 10.65%  |
| Intel Core 2 Duo        | 35        | 10.36%  |
| Intel Core i3           | 32        | 9.47%   |
| Intel Xeon              | 19        | 5.62%   |
| AMD Ryzen 5             | 18        | 5.33%   |
| Intel Celeron           | 17        | 5.03%   |
| AMD Ryzen 7             | 14        | 4.14%   |
| Intel Pentium           | 10        | 2.96%   |
| Other                   | 7         | 2.07%   |
| Intel Pentium Dual-Core | 6         | 1.78%   |
| Intel Core 2 Quad       | 6         | 1.78%   |
| AMD Ryzen 3             | 5         | 1.48%   |
| AMD A6                  | 5         | 1.48%   |
| Intel Atom              | 4         | 1.18%   |
| AMD Ryzen 9             | 4         | 1.18%   |
| Intel Core 2            | 3         | 0.89%   |
| AMD Phenom II X4        | 3         | 0.89%   |
| AMD E2                  | 3         | 0.89%   |
| AMD E1                  | 3         | 0.89%   |
| AMD A10                 | 3         | 0.89%   |
| AMD Ryzen Threadripper  | 2         | 0.59%   |
| AMD FX                  | 2         | 0.59%   |
| Intel Pentium M         | 1         | 0.3%    |
| Intel Pentium Dual      | 1         | 0.3%    |
| Intel Pentium D         | 1         | 0.3%    |
| Intel Genuine           | 1         | 0.3%    |
| Intel Core M            | 1         | 0.3%    |
| Intel Core i9           | 1         | 0.3%    |
| AMD Ryzen 5 PRO         | 1         | 0.3%    |
| AMD E                   | 1         | 0.3%    |
| AMD Athlon II X4        | 1         | 0.3%    |
| AMD Athlon II X2        | 1         | 0.3%    |
| AMD Athlon Dual Core    | 1         | 0.3%    |
| AMD Athlon 64 X2        | 1         | 0.3%    |
| AMD A8                  | 1         | 0.3%    |
| AMD A4                  | 1         | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 137       | 40.53%  |
| 4       | 94        | 27.81%  |
| Unknown | 41        | 12.13%  |
| 6       | 21        | 6.21%   |
| 8       | 16        | 4.73%   |
| 12      | 11        | 3.25%   |
| 16      | 10        | 2.96%   |
| 24      | 3         | 0.89%   |
| 64      | 1         | 0.3%    |
| 48      | 1         | 0.3%    |
| 32      | 1         | 0.3%    |
| 14      | 1         | 0.3%    |
| 1       | 1         | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 317       | 93.79%  |
| 2       | 19        | 5.62%   |
| Unknown | 2         | 0.59%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 150       | 44.38%  |
| 2       | 147       | 43.49%  |
| Unknown | 41        | 12.13%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Penryn        | 43        | 12.72%  |
| KabyLake      | 37        | 10.95%  |
| IvyBridge     | 36        | 10.65%  |
| Haswell       | 30        | 8.88%   |
| Skylake       | 28        | 8.28%   |
| SandyBridge   | 25        | 7.4%    |
| Westmere      | 17        | 5.03%   |
| Zen 2         | 16        | 4.73%   |
| Core          | 14        | 4.14%   |
| Zen+          | 12        | 3.55%   |
| Zen           | 9         | 2.66%   |
| Silvermont    | 9         | 2.66%   |
| Zen 3         | 7         | 2.07%   |
| Piledriver    | 7         | 2.07%   |
| CometLake     | 7         | 2.07%   |
| Broadwell     | 7         | 2.07%   |
| K10           | 5         | 1.48%   |
| Nehalem       | 4         | 1.18%   |
| Jaguar        | 4         | 1.18%   |
| Bonnell       | 4         | 1.18%   |
| Bobcat        | 4         | 1.18%   |
| Goldmont      | 3         | 0.89%   |
| K8 Hammer     | 2         | 0.59%   |
| Excavator     | 2         | 0.59%   |
| Unknown       | 2         | 0.59%   |
| Puma          | 1         | 0.3%    |
| NetBurst      | 1         | 0.3%    |
| K10 Llano     | 1         | 0.3%    |
| Goldmont plus | 1         | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 188       | 50.27%  |
| Nvidia                     | 105       | 28.07%  |
| AMD                        | 80        | 21.39%  |
| Matrox Electronics Systems | 1         | 0.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19        | 4.94%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 4.68%   |
| Intel HD Graphics 530                                                                    | 13        | 3.38%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 3.12%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 2.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 2.34%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2.34%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 2.08%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 2.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 2.08%   |
| Nvidia C79 [GeForce 9400]                                                                | 7         | 1.82%   |
| Intel HD Graphics 620                                                                    | 7         | 1.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 1.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 1.56%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.56%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 1.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.3%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.3%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 1.3%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 1.04%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 1.04%   |
| Nvidia C79 [GeForce 9400M]                                                               | 4         | 1.04%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4         | 1.04%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.04%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 1.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.04%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 1.04%   |
| AMD Renoir                                                                               | 4         | 1.04%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 4         | 1.04%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.78%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.78%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 0.78%   |
| Intel UHD Graphics 620                                                                   | 3         | 0.78%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.78%   |
| Intel HD Graphics 500                                                                    | 3         | 0.78%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 3         | 0.78%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 3         | 0.78%   |
| Nvidia TU117M                                                                            | 2         | 0.52%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2         | 0.52%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.52%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 2         | 0.52%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 0.52%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2         | 0.52%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2         | 0.52%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.52%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.52%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2         | 0.52%   |
| Nvidia GK107GL [Quadro K2000]                                                            | 2         | 0.52%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 2         | 0.52%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 2         | 0.52%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 2         | 0.52%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 2         | 0.52%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.52%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.52%   |
| Intel HD Graphics 630                                                                    | 2         | 0.52%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.52%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 0.52%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.52%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 0.52%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 136       | 39.88%  |
| 1 x Nvidia     | 80        | 23.46%  |
| 1 x AMD        | 68        | 19.94%  |
| Intel + Nvidia | 23        | 6.74%   |
| 2 x Intel      | 21        | 6.16%   |
| Intel + AMD    | 8         | 2.35%   |
| AMD + Nvidia   | 3         | 0.88%   |
| 2 x AMD        | 1         | 0.29%   |
| 1 x Matrox     | 1         | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 262       | 77.06%  |
| Proprietary | 72        | 21.18%  |
| Unknown     | 6         | 1.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 210       | 61.58%  |
| 0.01-0.5   | 43        | 12.61%  |
| 1.01-2.0   | 24        | 7.04%   |
| 0.51-1.0   | 22        | 6.45%   |
| 3.01-4.0   | 20        | 5.87%   |
| 7.01-8.0   | 14        | 4.11%   |
| 5.01-6.0   | 5         | 1.47%   |
| 8.01-16.0  | 2         | 0.59%   |
| 2.01-3.0   | 1         | 0.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 42        | 12.96%  |
| LG Display              | 34        | 10.49%  |
| AU Optronics            | 28        | 8.64%   |
| Chimei Innolux          | 26        | 8.02%   |
| Goldstar                | 21        | 6.48%   |
| Lenovo                  | 20        | 6.17%   |
| Dell                    | 19        | 5.86%   |
| Apple                   | 18        | 5.56%   |
| BOE                     | 16        | 4.94%   |
| AOC                     | 12        | 3.7%    |
| BenQ                    | 11        | 3.4%    |
| Acer                    | 10        | 3.09%   |
| Hewlett-Packard         | 9         | 2.78%   |
| Philips                 | 8         | 2.47%   |
| Ancor Communications    | 8         | 2.47%   |
| ASUSTek Computer        | 5         | 1.54%   |
| Sony                    | 4         | 1.23%   |
| Fujitsu Siemens         | 4         | 1.23%   |
| ViewSonic               | 3         | 0.93%   |
| Vestel Elektronik       | 2         | 0.62%   |
| NEC Computers           | 2         | 0.62%   |
| Iiyama                  | 2         | 0.62%   |
| Chi Mei Optoelectronics | 2         | 0.62%   |
| ZL_                     | 1         | 0.31%   |
| Westinghouse            | 1         | 0.31%   |
| Toshiba                 | 1         | 0.31%   |
| SLD                     | 1         | 0.31%   |
| Sharp                   | 1         | 0.31%   |
| SGT                     | 1         | 0.31%   |
| RTK                     | 1         | 0.31%   |
| PANDA                   | 1         | 0.31%   |
| MSI                     | 1         | 0.31%   |
| Medion                  | 1         | 0.31%   |
| LTV                     | 1         | 0.31%   |
| LG Philips              | 1         | 0.31%   |
| Lenovo Group Limited    | 1         | 0.31%   |
| LED                     | 1         | 0.31%   |
| GRR                     | 1         | 0.31%   |
| FND                     | 1         | 0.31%   |
| Denver                  | 1         | 0.31%   |
| CND                     | 1         | 0.31%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 4         | 1.2%    |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 3         | 0.9%    |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch       | 3         | 0.9%    |
| Apple Color LCD APP9C93 1680x1050 430x270mm 20.0-inch                 | 3         | 0.9%    |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 2         | 0.6%    |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 2         | 0.6%    |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch  | 2         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 2         | 0.6%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 2         | 0.6%    |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 2         | 0.6%    |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 2         | 0.6%    |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch           | 2         | 0.6%    |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch               | 2         | 0.6%    |
| Lenovo LCD Monitor LEN40A0 1366x768 310x170mm 13.9-inch               | 2         | 0.6%    |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 2         | 0.6%    |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch               | 2         | 0.6%    |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch            | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch       | 2         | 0.6%    |
| BenQ GW2780 BNQ78E6 1920x1080 600x340mm 27.2-inch                     | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch         | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch        | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 2         | 0.6%    |
| ASUSTek Computer ROG XG279Q AUS278D 2560x1440 600x340mm 27.2-inch     | 2         | 0.6%    |
| Apple Color LCD APP9C96 1920x1200 520x320mm 24.0-inch                 | 2         | 0.6%    |
| AOC 24G2W1G4 AOC2402 1920x1080 530x300mm 24.0-inch                    | 2         | 0.6%    |
| Ancor Communications MX27AQ ACI27A5 2560x1440 600x340mm 27.2-inch     | 2         | 0.6%    |
| ZL_ zhuoyue-HDMI ZL_2716 2560x1440 600x330mm 27.0-inch                | 1         | 0.3%    |
| Westinghouse LCM-19w4 WDE1904 1440x900 410x260mm 19.1-inch            | 1         | 0.3%    |
| ViewSonic VX1940w VSC6A20 1680x1050 410x260mm 19.1-inch               | 1         | 0.3%    |
| ViewSonic VA2719-2K VSC6B34 2560x1440 600x340mm 27.2-inch             | 1         | 0.3%    |
| ViewSonic LCD Monitor VSCBD2B 1920x1080 480x270mm 21.7-inch           | 1         | 0.3%    |
| ViewSonic LCD Monitor VSC6332 1920x1080 510x290mm 23.1-inch           | 1         | 0.3%    |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                       | 1         | 0.3%    |
| Sony TV SNYEE01 1920x1080                                             | 1         | 0.3%    |
| Sony TV SNY9C01 1360x768                                              | 1         | 0.3%    |
| Sony SDM-S75D/F/N SNY3800 1280x1024 340x270mm 17.1-inch               | 1         | 0.3%    |
| Sony LCD SNY06FA 1600x900 290x160mm 13.0-inch                         | 1         | 0.3%    |
| SLD LCD Monitor SLD003C 1366x768 310x170mm 13.9-inch                  | 1         | 0.3%    |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch               | 1         | 0.3%    |
| SGT YSD SGT1700 1280x1024 380x210mm 17.1-inch                         | 1         | 0.3%    |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch     | 1         | 0.3%    |
| Samsung Electronics T24E390 SAM0C20 1920x1080 520x290mm 23.4-inch     | 1         | 0.3%    |
| Samsung Electronics SyncMaster SAM0601 1600x900                       | 1         | 0.3%    |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch   | 1         | 0.3%    |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                      | 1         | 0.3%    |
| Samsung Electronics SyncMaster SAM05B0 1920x1080                      | 1         | 0.3%    |
| Samsung Electronics SyncMaster SAM0373 1680x1050 440x300mm 21.0-inch  | 1         | 0.3%    |
| Samsung Electronics SyncMaster SAM02FA 1440x900 410x260mm 19.1-inch   | 1         | 0.3%    |
| Samsung Electronics SyncMaster SAM02E3 1440x900 370x230mm 17.2-inch   | 1         | 0.3%    |
| Samsung Electronics SyncMaster SAM027D 1680x1050 430x270mm 20.0-inch  | 1         | 0.3%    |
| Samsung Electronics SyncMaster SAM0116 1024x768 280x210mm 13.8-inch   | 1         | 0.3%    |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 480x270mm 21.7-inch    | 1         | 0.3%    |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 440x250mm 19.9-inch  | 1         | 0.3%    |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 600x340mm 27.2-inch     | 1         | 0.3%    |
| Samsung Electronics S24H85x SAM0E0C 2560x1440 530x300mm 24.0-inch     | 1         | 0.3%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 1         | 0.3%    |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch     | 1         | 0.3%    |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 530x300mm 24.0-inch     | 1         | 0.3%    |
| Samsung Electronics S24C450 SAM09CB 1920x1080 530x300mm 24.0-inch     | 1         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 110       | 34.16%  |
| 1366x768 (WXGA)    | 83        | 25.78%  |
| 1280x800 (WXGA)    | 21        | 6.52%   |
| 2560x1440 (QHD)    | 17        | 5.28%   |
| 1600x900 (HD+)     | 16        | 4.97%   |
| 1280x1024 (SXGA)   | 15        | 4.66%   |
| 3840x2160 (4K)     | 11        | 3.42%   |
| 1680x1050 (WSXGA+) | 11        | 3.42%   |
| 1440x900 (WXGA+)   | 11        | 3.42%   |
| 1920x1200 (WUXGA)  | 9         | 2.8%    |
| 2560x1080          | 4         | 1.24%   |
| 1024x768 (XGA)     | 4         | 1.24%   |
| 1920x540           | 3         | 0.93%   |
| 3440x1440          | 2         | 0.62%   |
| 1360x768           | 2         | 0.62%   |
| 1024x600           | 2         | 0.62%   |
| 1600x1200          | 1         | 0.31%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 61        | 18.54%  |
| 13      | 49        | 14.89%  |
| 24      | 33        | 10.03%  |
| 27      | 26        | 7.9%    |
| 23      | 21        | 6.38%   |
| 19      | 19        | 5.78%   |
| 21      | 18        | 5.47%   |
| 17      | 17        | 5.17%   |
| 12      | 14        | 4.26%   |
| 18      | 10        | 3.04%   |
| 20      | 9         | 2.74%   |
| 14      | 9         | 2.74%   |
| 31      | 7         | 2.13%   |
| 11      | 7         | 2.13%   |
| Unknown | 6         | 1.82%   |
| 34      | 4         | 1.22%   |
| 22      | 3         | 0.91%   |
| 10      | 3         | 0.91%   |
| 42      | 2         | 0.61%   |
| 29      | 2         | 0.61%   |
| 16      | 2         | 0.61%   |
| 64      | 1         | 0.3%    |
| 54      | 1         | 0.3%    |
| 50      | 1         | 0.3%    |
| 40      | 1         | 0.3%    |
| 36      | 1         | 0.3%    |
| 33      | 1         | 0.3%    |
| 28      | 1         | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 101       | 31.17%  |
| 501-600     | 75        | 23.15%  |
| 201-300     | 50        | 15.43%  |
| 401-500     | 48        | 14.81%  |
| 351-400     | 20        | 6.17%   |
| 601-700     | 12        | 3.7%    |
| 701-800     | 6         | 1.85%   |
| Unknown     | 6         | 1.85%   |
| 1001-1500   | 3         | 0.93%   |
| 901-1000    | 2         | 0.62%   |
| 801-900     | 1         | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 231       | 74.28%  |
| 16/10   | 50        | 16.08%  |
| 5/4     | 13        | 4.18%   |
| 21/9    | 6         | 1.93%   |
| 4/3     | 5         | 1.61%   |
| 3/2     | 5         | 1.61%   |
| Unknown | 1         | 0.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 62        | 18.9%   |
| 91-100         | 50        | 15.24%  |
| 81-90          | 49        | 14.94%  |
| 151-200        | 32        | 9.76%   |
| 301-350        | 27        | 8.23%   |
| 61-70          | 15        | 4.57%   |
| 141-150        | 14        | 4.27%   |
| 351-500        | 13        | 3.96%   |
| 101-110        | 13        | 3.96%   |
| 251-300        | 12        | 3.66%   |
| 121-130        | 8         | 2.44%   |
| 71-80          | 7         | 2.13%   |
| 51-60          | 6         | 1.83%   |
| Unknown        | 6         | 1.83%   |
| 501-1000       | 4         | 1.22%   |
| More than 1000 | 3         | 0.91%   |
| 41-50          | 3         | 0.91%   |
| 131-140        | 3         | 0.91%   |
| 111-120        | 1         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 132       | 40.62%  |
| 101-120 | 106       | 32.62%  |
| 121-160 | 72        | 22.15%  |
| 161-240 | 7         | 2.15%   |
| Unknown | 6         | 1.85%   |
| 1-50    | 2         | 0.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 287       | 84.41%  |
| 2     | 29        | 8.53%   |
| 0     | 23        | 6.76%   |
| 3     | 1         | 0.29%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 171       | 34.34%  |
| Intel                             | 162       | 32.53%  |
| Qualcomm Atheros                  | 53        | 10.64%  |
| Broadcom                          | 46        | 9.24%   |
| Nvidia                            | 13        | 2.61%   |
| Marvell Technology Group          | 12        | 2.41%   |
| Ralink                            | 5         | 1%      |
| Xiaomi                            | 4         | 0.8%    |
| Ralink Technology                 | 3         | 0.6%    |
| NetGear                           | 3         | 0.6%    |
| JMicron Technology                | 3         | 0.6%    |
| Edimax Technology                 | 3         | 0.6%    |
| TP-Link                           | 2         | 0.4%    |
| Ericsson Business Mobile Networks | 2         | 0.4%    |
| Dell                              | 2         | 0.4%    |
| D-Link System                     | 2         | 0.4%    |
| Silicon Integrated Systems [SiS]  | 1         | 0.2%    |
| Sierra Wireless                   | 1         | 0.2%    |
| Samsung Electronics               | 1         | 0.2%    |
| OPPO Electronics                  | 1         | 0.2%    |
| Napatech A/S                      | 1         | 0.2%    |
| Microchip Technology              | 1         | 0.2%    |
| Mercucys                          | 1         | 0.2%    |
| Mellanox Technologies             | 1         | 0.2%    |
| MediaTek                          | 1         | 0.2%    |
| Huawei Technologies               | 1         | 0.2%    |
| Hewlett-Packard                   | 1         | 0.2%    |
| Google                            | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 129       | 21.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 3.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 2.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 13        | 2.16%   |
| Nvidia MCP79 Ethernet                                             | 13        | 2.16%   |
| Intel I211 Gigabit Network Connection                             | 13        | 2.16%   |
| Intel Ethernet Connection I217-LM                                 | 13        | 2.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 12        | 1.99%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 12        | 1.99%   |
| Intel Wi-Fi 6 AX200                                               | 11        | 1.83%   |
| Intel Wireless 8260                                               | 10        | 1.66%   |
| Intel Ethernet Connection (2) I219-LM                             | 9         | 1.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 1.33%   |
| Intel Wireless 7265                                               | 8         | 1.33%   |
| Intel Wireless 7260                                               | 8         | 1.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 7         | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.16%   |
| Intel Wireless 8265 / 8275                                        | 7         | 1.16%   |
| Intel Centrino Advanced-N 6200                                    | 7         | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 1%      |
| Intel Ethernet Connection (7) I219-V                              | 6         | 1%      |
| Intel 82577LM Gigabit Network Connection                          | 6         | 1%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 0.83%   |
| Intel WiFi Link 5100                                              | 5         | 0.83%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 5         | 0.83%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 0.83%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 5         | 0.83%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 4         | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 0.66%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 4         | 0.66%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.66%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.66%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 4         | 0.66%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.66%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 4         | 0.66%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.5%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.5%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.5%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 0.5%    |
| Intel Wireless-AC 9260                                            | 3         | 0.5%    |
| Intel Wireless 3165                                               | 3         | 0.5%    |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.5%    |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.5%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.5%    |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.5%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 0.5%    |
| Intel 82566MM Gigabit Network Connection                          | 3         | 0.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.5%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 2         | 0.33%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.33%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.33%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.33%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 114       | 45.6%   |
| Realtek Semiconductor | 42        | 16.8%   |
| Qualcomm Atheros      | 42        | 16.8%   |
| Broadcom              | 32        | 12.8%   |
| Ralink                | 5         | 2%      |
| Ralink Technology     | 3         | 1.2%    |
| NetGear               | 3         | 1.2%    |
| Edimax Technology     | 3         | 1.2%    |
| TP-Link               | 2         | 0.8%    |
| Sierra Wireless       | 1         | 0.4%    |
| Mercucys              | 1         | 0.4%    |
| MediaTek              | 1         | 0.4%    |
| Dell                  | 1         | 0.4%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 5.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 4.71%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 12        | 4.71%   |
| Intel Wi-Fi 6 AX200                                                     | 11        | 4.31%   |
| Intel Wireless 8260                                                     | 10        | 3.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 3.14%   |
| Intel Wireless 7265                                                     | 8         | 3.14%   |
| Intel Wireless 7260                                                     | 8         | 3.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 2.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 2.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 2.75%   |
| Intel Wireless 8265 / 8275                                              | 7         | 2.75%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 2.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 2.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.96%   |
| Intel WiFi Link 5100                                                    | 5         | 1.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 1.96%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 5         | 1.96%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 4         | 1.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 1.57%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 1.57%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.57%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 1.57%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 4         | 1.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.18%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.18%   |
| Intel Wireless-AC 9260                                                  | 3         | 1.18%   |
| Intel Wireless 3165                                                     | 3         | 1.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.18%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.18%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.18%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 2         | 0.78%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.78%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.78%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.78%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 2         | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.78%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 2         | 0.78%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 0.78%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 0.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.78%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.78%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.78%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 2         | 0.78%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                           | 1         | 0.39%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.39%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.39%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.39%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.39%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.39%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.39%   |
| Ralink RT2500 Wireless 802.11bg                                         | 1         | 0.39%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.39%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 0.39%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.39%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                         | 1         | 0.39%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 156       | 46.43%  |
| Intel                            | 110       | 32.74%  |
| Qualcomm Atheros                 | 17        | 5.06%   |
| Broadcom                         | 16        | 4.76%   |
| Nvidia                           | 13        | 3.87%   |
| Marvell Technology Group         | 12        | 3.57%   |
| Xiaomi                           | 4         | 1.19%   |
| JMicron Technology               | 3         | 0.89%   |
| Silicon Integrated Systems [SiS] | 1         | 0.3%    |
| Samsung Electronics              | 1         | 0.3%    |
| OPPO Electronics                 | 1         | 0.3%    |
| Google                           | 1         | 0.3%    |
| D-Link System                    | 1         | 0.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 129       | 38.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 23        | 6.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 18        | 5.33%   |
| Nvidia MCP79 Ethernet                                                         | 13        | 3.85%   |
| Intel I211 Gigabit Network Connection                                         | 13        | 3.85%   |
| Intel Ethernet Connection I217-LM                                             | 13        | 3.85%   |
| Intel Ethernet Connection (2) I219-LM                                         | 9         | 2.66%   |
| Intel Ethernet Connection (7) I219-V                                          | 6         | 1.78%   |
| Intel 82577LM Gigabit Network Connection                                      | 6         | 1.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 5         | 1.48%   |
| Intel Ethernet Connection (2) I219-V                                          | 5         | 1.48%   |
| Intel Ethernet Connection I219-LM                                             | 4         | 1.18%   |
| Intel 82579V Gigabit Network Connection                                       | 4         | 1.18%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 3         | 0.89%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 3         | 0.89%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 3         | 0.89%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 3         | 0.89%   |
| Intel Ethernet Connection I218-LM                                             | 3         | 0.89%   |
| Intel Ethernet Connection (4) I219-V                                          | 3         | 0.89%   |
| Intel 82574L Gigabit Network Connection                                       | 3         | 0.89%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3         | 0.89%   |
| Intel 82566MM Gigabit Network Connection                                      | 3         | 0.89%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                               | 3         | 0.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 0.59%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 2         | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 2         | 0.59%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                       | 2         | 0.59%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 2         | 0.59%   |
| Intel I210 Gigabit Network Connection                                         | 2         | 0.59%   |
| Intel Ethernet Connection (6) I219-V                                          | 2         | 0.59%   |
| Intel Ethernet Connection (3) I218-V                                          | 2         | 0.59%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 2         | 0.59%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                        | 2         | 0.59%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1         | 0.3%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 1         | 0.3%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1         | 0.3%    |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.3%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1         | 0.3%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 0.3%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1         | 0.3%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                    | 1         | 0.3%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1         | 0.3%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 0.3%    |
| OPPO SDM720G-IDP _SN:8A58D65F RNDIS Control RNDIS Ethernet Data               | 1         | 0.3%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                       | 1         | 0.3%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1         | 0.3%    |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                         | 1         | 0.3%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 1         | 0.3%    |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                          | 1         | 0.3%    |
| Intel Ethernet Controller I225-V                                              | 1         | 0.3%    |
| Intel Ethernet Connection I219-V                                              | 1         | 0.3%    |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 0.3%    |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 0.3%    |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 0.3%    |
| Intel Ethernet Connection (12) I219-V                                         | 1         | 0.3%    |
| Intel Ethernet Connection (10) I219-V                                         | 1         | 0.3%    |
| Intel 82578DM Gigabit Network Connection                                      | 1         | 0.3%    |
| Intel 82573L Gigabit Ethernet Controller                                      | 1         | 0.3%    |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1         | 0.3%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 325       | 57.52%  |
| WiFi     | 231       | 40.88%  |
| Unknown  | 5         | 0.88%   |
| Modem    | 4         | 0.71%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 275       | 65.01%  |
| WiFi     | 144       | 34.04%  |
| Unknown  | 3         | 0.71%   |
| Modem    | 1         | 0.24%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 205       | 60.65%  |
| 1     | 119       | 35.21%  |
| 3     | 8         | 2.37%   |
| 4     | 3         | 0.89%   |
| 0     | 3         | 0.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 324       | 94.74%  |
| Yes  | 18        | 5.26%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 67        | 39.64%  |
| Apple                           | 19        | 11.24%  |
| Realtek Semiconductor           | 14        | 8.28%   |
| Broadcom                        | 14        | 8.28%   |
| Qualcomm Atheros Communications | 12        | 7.1%    |
| Cambridge Silicon Radio         | 12        | 7.1%    |
| Lite-On Technology              | 6         | 3.55%   |
| IMC Networks                    | 5         | 2.96%   |
| Hewlett-Packard                 | 4         | 2.37%   |
| Foxconn / Hon Hai               | 4         | 2.37%   |
| Ralink                          | 3         | 1.78%   |
| Dell                            | 3         | 1.78%   |
| Integrated System Solution      | 2         | 1.18%   |
| ASUSTek Computer                | 2         | 1.18%   |
| TP-Link                         | 1         | 0.59%   |
| HTC (High Tech Computer)        | 1         | 0.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 34        | 19.88%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 12        | 7.02%   |
| Intel AX200 Bluetooth                                                | 11        | 6.43%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 8         | 4.68%   |
| Intel AX201 Bluetooth                                                | 7         | 4.09%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 7         | 4.09%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                              | 6         | 3.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 6         | 3.51%   |
| Apple Bluetooth Host Controller                                      | 5         | 2.92%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 4         | 2.34%   |
| Realtek  Bluetooth 4.0 Adapter                                       | 4         | 2.34%   |
| Lite-On Atheros AR3012 Bluetooth                                     | 4         | 2.34%   |
| Ralink RT3290 Bluetooth                                              | 3         | 1.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 3         | 1.75%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 3         | 1.75%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 3         | 1.75%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                     | 3         | 1.75%   |
| Apple Built-in iSight (no firmware loaded)                           | 3         | 1.75%   |
| Apple Apple Broadcom Built-in Bluetooth                              | 3         | 1.75%   |
| Realtek RTL8723B Bluetooth                                           | 2         | 1.17%   |
| Realtek Bluetooth Radio                                              | 2         | 1.17%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device          | 2         | 1.17%   |
| IMC Networks Realtek Bluetooth Adapter                               | 2         | 1.17%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                        | 2         | 1.17%   |
| Foxconn / Hon Hai Bluetooth USB Module                               | 2         | 1.17%   |
| TP-Link TP-Link UB500 Adapter                                        | 1         | 0.58%   |
| Realtek RTL8821A Bluetooth                                           | 1         | 0.58%   |
| Realtek  Bluetooth Adapter                                           | 1         | 0.58%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                             | 1         | 0.58%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 1         | 0.58%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 1         | 0.58%   |
| Qualcomm Atheros AR3012 Bluetooth                                    | 1         | 0.58%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)                      | 1         | 0.58%   |
| Lite-On Realtek Bluetooth Adapter                                    | 1         | 0.58%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 1         | 0.58%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1         | 0.58%   |
| Integrated System Solution Bluetooth Device                          | 1         | 0.58%   |
| IMC Networks Realtek Bluetooth 4.0 Adapter                           | 1         | 0.58%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS                     | 1         | 0.58%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                    | 1         | 0.58%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 0.58%   |
| HP Broadcom 2070 Bluetooth Combo                                     | 1         | 0.58%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                           | 1         | 0.58%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0                     | 1         | 0.58%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                      | 1         | 0.58%   |
| Dell Wireless 355 Bluetooth                                          | 1         | 0.58%   |
| Dell DW375 Bluetooth Module                                          | 1         | 0.58%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                          | 1         | 0.58%   |
| Broadcom Broadcom BCM2070 Bluetooth 2.1+EDR USB Device               | 1         | 0.58%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1         | 0.58%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 1         | 0.58%   |
| ASUS Bluetooth Controller                                            | 1         | 0.58%   |
| ASUS ASUS USB-BT500                                                  | 1         | 0.58%   |
| Apple Broadcom Bluetooth 2.1 module                                  | 1         | 0.58%   |
| Apple Bluetooth USB Host Controller                                  | 1         | 0.58%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 247       | 53.7%   |
| AMD                              | 88        | 19.13%  |
| Nvidia                           | 83        | 18.04%  |
| C-Media Electronics              | 7         | 1.52%   |
| GN Netcom                        | 6         | 1.3%    |
| Texas Instruments                | 4         | 0.87%   |
| Logitech                         | 3         | 0.65%   |
| SteelSeries ApS                  | 2         | 0.43%   |
| JMTek                            | 2         | 0.43%   |
| Focusrite-Novation               | 2         | 0.43%   |
| Yamaha                           | 1         | 0.22%   |
| VIA Technologies                 | 1         | 0.22%   |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |
| Nektar                           | 1         | 0.22%   |
| Lenovo                           | 1         | 0.22%   |
| KORG                             | 1         | 0.22%   |
| Kingston Technology              | 1         | 0.22%   |
| Generalplus Technology           | 1         | 0.22%   |
| FiiO Electronics Technology      | 1         | 0.22%   |
| DSEA A/S                         | 1         | 0.22%   |
| Creative Technology              | 1         | 0.22%   |
| Creative Labs                    | 1         | 0.22%   |
| Corsair                          | 1         | 0.22%   |
| Cambridge Silicon Radio          | 1         | 0.22%   |
| ASUSTek Computer                 | 1         | 0.22%   |
| Astro Gaming                     | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 34        | 6.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 23        | 4.27%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 3.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 20        | 3.71%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 19        | 3.53%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 18        | 3.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 18        | 3.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 17        | 3.15%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 17        | 3.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 14        | 2.6%    |
| Intel Cannon Lake PCH cAVS                                                                        | 14        | 2.6%    |
| AMD FCH Azalia Controller                                                                         | 14        | 2.6%    |
| Nvidia MCP79 High Definition Audio                                                                | 13        | 2.41%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 11        | 2.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 2.04%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 1.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 1.86%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 1.86%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 8         | 1.48%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 8         | 1.48%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 1.3%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 7         | 1.3%    |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.3%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 1.3%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 6         | 1.11%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 1.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.11%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 6         | 1.11%   |
| Intel 200 Series PCH HD Audio                                                                     | 6         | 1.11%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 6         | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 0.93%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 0.93%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.74%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.74%   |
| AMD Navi 10 HDMI Audio                                                                            | 4         | 0.74%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4         | 0.74%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 0.56%   |
| Nvidia MCP61 High Definition Audio                                                                | 3         | 0.56%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.56%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 3         | 0.56%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 3         | 0.56%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.56%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.56%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 3         | 0.56%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.56%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.56%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 0.56%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.56%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.56%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 0.56%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 3         | 0.56%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2         | 0.37%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.37%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 2         | 0.37%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.37%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 0.37%   |
| JMTek USB PnP Audio Device                                                                        | 2         | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 66        | 17.14%  |
| Kingston            | 65        | 16.88%  |
| SK hynix            | 49        | 12.73%  |
| Unknown             | 41        | 10.65%  |
| Micron Technology   | 31        | 8.05%   |
| Crucial             | 19        | 4.94%   |
| Corsair             | 17        | 4.42%   |
| G.Skill             | 13        | 3.38%   |
| Unknown             | 12        | 3.12%   |
| Nanya Technology    | 10        | 2.6%    |
| Ramaxel Technology  | 7         | 1.82%   |
| Elpida              | 7         | 1.82%   |
| A-DATA Technology   | 7         | 1.82%   |
| Team                | 6         | 1.56%   |
| Transcend           | 3         | 0.78%   |
| Smart               | 3         | 0.78%   |
| Patriot             | 3         | 0.78%   |
| Silicon Power       | 2         | 0.52%   |
| Goodram             | 2         | 0.52%   |
| Avant               | 2         | 0.52%   |
| ASint Technology    | 2         | 0.52%   |
| AMD                 | 2         | 0.52%   |
| 48spaces            | 2         | 0.52%   |
| Unknown (ABCD)      | 1         | 0.26%   |
| Unifosa             | 1         | 0.26%   |
| TakeMS              | 1         | 0.26%   |
| Super Talent        | 1         | 0.26%   |
| Strontium           | 1         | 0.26%   |
| Smart Brazil        | 1         | 0.26%   |
| Sesame              | 1         | 0.26%   |
| PNY                 | 1         | 0.26%   |
| Kingmax             | 1         | 0.26%   |
| Hikvision           | 1         | 0.26%   |
| High Bridge         | 1         | 0.26%   |
| Goldkey             | 1         | 0.26%   |
| Atermiter           | 1         | 0.26%   |
| Apacer              | 1         | 0.26%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                   | 12        | 2.86%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 7         | 1.67%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 5         | 1.19%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s                       | 4         | 0.95%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 4         | 0.95%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 4         | 0.95%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 4         | 0.95%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 4         | 0.95%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 4         | 0.95%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                              | 3         | 0.71%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s                     | 3         | 0.71%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 3         | 0.71%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 3         | 0.71%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 3         | 0.71%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 3         | 0.71%   |
| Micron RAM 18KSF51272AZ-1G4M1 4GB DIMM DDR3 1333MT/s                      | 3         | 0.71%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s                      | 3         | 0.71%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s                   | 3         | 0.71%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                               | 2         | 0.48%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                                 | 2         | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 2         | 0.48%   |
| Unknown RAM Module 2GB DIMM DDR2                                          | 2         | 0.48%   |
| Unknown RAM Module 2GB DIMM 400MT/s                                       | 2         | 0.48%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                      | 2         | 0.48%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 2         | 0.48%   |
| Unknown RAM Module 1GB DIMM SDRAM                                         | 2         | 0.48%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 800MT/s                     | 2         | 0.48%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 2         | 0.48%   |
| Samsung RAM Module 4GB SODIMM DDR4 2133MT/s                               | 2         | 0.48%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s                     | 2         | 0.48%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.48%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s                    | 2         | 0.48%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 2         | 0.48%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s                     | 2         | 0.48%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s                       | 2         | 0.48%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s                | 2         | 0.48%   |
| Nanya RAM Module 1GB SODIMM DDR2 667MT/s                                  | 2         | 0.48%   |
| Micron RAM Module 2GB SODIMM DDR3 1067MT/s                                | 2         | 0.48%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.48%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                      | 2         | 0.48%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s                    | 2         | 0.48%   |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                               | 2         | 0.48%   |
| Kingston RAM Module 1GB DIMM DDR2 667MT/s                                 | 2         | 0.48%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 2400MT/s                       | 2         | 0.48%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s                    | 2         | 0.48%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1333MT/s                     | 2         | 0.48%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s                     | 2         | 0.48%   |
| Crucial RAM BL16G32C16U4B.16FE 16GB DIMM DDR4 3200MT/s                    | 2         | 0.48%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s                     | 2         | 0.48%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 2667MT/s                     | 2         | 0.48%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 2         | 0.48%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                                 | 1         | 0.24%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                                 | 1         | 0.24%   |
| Unknown RAM Module 512MB DIMM SDRAM                                       | 1         | 0.24%   |
| Unknown RAM Module 4GB SODIMM DDR3 800MT/s                                | 1         | 0.24%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                               | 1         | 0.24%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                               | 1         | 0.24%   |
| Unknown RAM Module 4GB SODIMM DDR3                                        | 1         | 0.24%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                                | 1         | 0.24%   |
| Unknown RAM Module 4GB DIMM SDRAM                                         | 1         | 0.24%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 160       | 48.48%  |
| DDR4    | 111       | 33.64%  |
| DDR2    | 34        | 10.3%   |
| Unknown | 12        | 3.64%   |
| SDRAM   | 6         | 1.82%   |
| LPDDR4  | 2         | 0.61%   |
| LPDDR3  | 2         | 0.61%   |
| DDR     | 2         | 0.61%   |
| DRAM    | 1         | 0.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 193       | 58.66%  |
| DIMM         | 135       | 41.03%  |
| Row Of Chips | 1         | 0.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 118       | 32.42%  |
| 8192  | 103       | 28.3%   |
| 2048  | 82        | 22.53%  |
| 16384 | 37        | 10.16%  |
| 1024  | 19        | 5.22%   |
| 32768 | 4         | 1.1%    |
| 512   | 1         | 0.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 89        | 24.59%  |
| 1333    | 47        | 12.98%  |
| 2667    | 30        | 8.29%   |
| 3200    | 29        | 8.01%   |
| 2133    | 27        | 7.46%   |
| 2400    | 25        | 6.91%   |
| 1067    | 21        | 5.8%    |
| 667     | 21        | 5.8%    |
| 1334    | 14        | 3.87%   |
| 800     | 14        | 3.87%   |
| Unknown | 12        | 3.31%   |
| 2666    | 7         | 1.93%   |
| 1867    | 6         | 1.66%   |
| 3600    | 4         | 1.1%    |
| 1066    | 3         | 0.83%   |
| 975     | 3         | 0.83%   |
| 533     | 2         | 0.55%   |
| 400     | 2         | 0.55%   |
| 333     | 2         | 0.55%   |
| 3733    | 1         | 0.28%   |
| 3400    | 1         | 0.28%   |
| 1866    | 1         | 0.28%   |
| 1200    | 1         | 0.28%   |

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
| Chicony Electronics                    | 37        | 26.62%  |
| Microdia                               | 12        | 8.63%   |
| Realtek Semiconductor                  | 11        | 7.91%   |
| Acer                                   | 10        | 7.19%   |
| Logitech                               | 9         | 6.47%   |
| IMC Networks                           | 9         | 6.47%   |
| Quanta                                 | 8         | 5.76%   |
| Lite-On Technology                     | 7         | 5.04%   |
| Syntek                                 | 4         | 2.88%   |
| Suyin                                  | 4         | 2.88%   |
| Sunplus Innovation Technology          | 4         | 2.88%   |
| Z-Star Microelectronics                | 3         | 2.16%   |
| Lenovo                                 | 3         | 2.16%   |
| Alcor Micro                            | 3         | 2.16%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.44%   |
| Apple                                  | 2         | 1.44%   |
| Silicon Motion                         | 1         | 0.72%   |
| Ricoh                                  | 1         | 0.72%   |
| Primax Electronics                     | 1         | 0.72%   |
| Luxvisions Innotech Limited            | 1         | 0.72%   |
| Importek                               | 1         | 0.72%   |
| Hewlett-Packard                        | 1         | 0.72%   |
| Genesys Logic                          | 1         | 0.72%   |
| Aveo Technology                        | 1         | 0.72%   |
| Arkmicro Technologies                  | 1         | 0.72%   |
| ARC International                      | 1         | 0.72%   |
| ALi                                    | 1         | 0.72%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Lenovo Integrated Camera (0.3MP)            | 5         | 3.57%   |
| Chicony HD WebCam                                   | 5         | 3.57%   |
| Lite-On Integrated Camera                           | 4         | 2.86%   |
| Realtek USB Camera                                  | 3         | 2.14%   |
| Realtek Realtek USB2.0 PC Camera                    | 3         | 2.14%   |
| Realtek Integrated_Webcam_HD                        | 3         | 2.14%   |
| Microdia Integrated Webcam                          | 3         | 2.14%   |
| Chicony Integrated Camera                           | 3         | 2.14%   |
| Chicony HD WebCam (Acer)                            | 3         | 2.14%   |
| Chicony EasyCamera                                  | 3         | 2.14%   |
| Syntek Lenovo EasyCamera                            | 2         | 1.43%   |
| Suyin HD Video WebCam                               | 2         | 1.43%   |
| Quanta Realtek DMFT - RGB                           | 2         | 1.43%   |
| Quanta HP Webcam                                    | 2         | 1.43%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.43%   |
| Microdia Sonix USB 2.0 Camera                       | 2         | 1.43%   |
| Microdia Integrated_Webcam_HD                       | 2         | 1.43%   |
| Microdia Dell Laptop Integrated Webcam HD           | 2         | 1.43%   |
| Logitech Webcam C270                                | 2         | 1.43%   |
| Lite-On HP HD Camera                                | 2         | 1.43%   |
| Lenovo Integrated Webcam [R5U877]                   | 2         | 1.43%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 1.43%   |
| IMC Networks Integrated Camera                      | 2         | 1.43%   |
| Chicony HP HD Webcam [Fixed]                        | 2         | 1.43%   |
| Chicony Chicony USB 2.0 Camera                      | 2         | 1.43%   |
| Apple FaceTime HD Camera (Built-in)                 | 2         | 1.43%   |
| Acer SunplusIT INC. Integrated Camera               | 2         | 1.43%   |
| Acer Lenovo EasyCamera                              | 2         | 1.43%   |
| Acer Integrated Camera                              | 2         | 1.43%   |
| Z-Star WebCam SC-03FFL11739P                        | 1         | 0.71%   |
| Z-Star Webcam                                       | 1         | 0.71%   |
| Z-Star Lenovo USB2.0 UVC Camera                     | 1         | 0.71%   |
| Syntek EasyCamera                                   | 1         | 0.71%   |
| Syntek ASUS USB2.0 camera                           | 1         | 0.71%   |
| Suyin Laptop_Integrated_Webcam_FHD                  | 1         | 0.71%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.71%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 0.71%   |
| Sunplus Integrated Camera                           | 1         | 0.71%   |
| Sunplus HP Universal Camera                         | 1         | 0.71%   |
| Sunplus HD WebCam                                   | 1         | 0.71%   |
| Silicon Motion HP Webcam-50                         | 1         | 0.71%   |
| Ricoh USB2.0 Camera                                 | 1         | 0.71%   |
| Realtek Integrated_Webcam_FHD                       | 1         | 0.71%   |
| Realtek Integrated_Webcam_8M                        | 1         | 0.71%   |
| Realtek HD WebCam                                   | 1         | 0.71%   |
| Quanta VGA WebCam                                   | 1         | 0.71%   |
| Quanta HD WebCam                                    | 1         | 0.71%   |
| Primax Dell Laptop Integrated Webcam 2Mpix          | 1         | 0.71%   |
| Microdia USB 2.0 Camera                             | 1         | 0.71%   |
| Microdia Lenovo EasyCamera                          | 1         | 0.71%   |
| Microdia ASUS USB2.0 Webcam                         | 1         | 0.71%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 0.71%   |
| Logitech Webcam C930e                               | 1         | 0.71%   |
| Logitech Webcam C310                                | 1         | 0.71%   |
| Logitech Webcam C170                                | 1         | 0.71%   |
| Logitech HD Webcam C615                             | 1         | 0.71%   |
| Logitech C922 Pro Stream Webcam                     | 1         | 0.71%   |
| Logitech C670i FHD Webcam                           | 1         | 0.71%   |
| Logitech BRIO Ultra HD Webcam                       | 1         | 0.71%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 0.71%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 13        | 33.33%  |
| Upek                       | 11        | 28.21%  |
| AuthenTec                  | 7         | 17.95%  |
| STMicroelectronics         | 3         | 7.69%   |
| Shenzhen Goodix Technology | 2         | 5.13%   |
| LighTuning Technology      | 2         | 5.13%   |
| Synaptics                  | 1         | 2.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 9         | 23.08%  |
| STMicroelectronics Fingerprint Reader                  | 3         | 7.69%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 5.13%   |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 5.13%   |
| Validity Sensors VFS491                                | 2         | 5.13%   |
| Validity Sensors VFS471 Fingerprint Reader             | 2         | 5.13%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 5.13%   |
| Validity Sensors Synaptics WBDI                        | 2         | 5.13%   |
| Upek TCS5B Fingerprint sensor                          | 2         | 5.13%   |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 5.13%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 5.13%   |
| AuthenTec AES1600                                      | 2         | 5.13%   |
| Validity Sensors Fingerprint scanner                   | 1         | 2.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 2.56%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 2.56%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 2.56%   |
| AuthenTec AuthenTec Inc. AES1660                       | 1         | 2.56%   |
| AuthenTec AES2810                                      | 1         | 2.56%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 2.56%   |

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
| 1     | 132       | 38.71%  |
| 0     | 95        | 27.86%  |
| 2     | 76        | 22.29%  |
| 3     | 28        | 8.21%   |
| 4     | 10        | 2.93%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 194       | 50.92%  |
| Net/wireless             | 68        | 17.85%  |
| Bluetooth                | 38        | 9.97%   |
| Fingerprint reader       | 37        | 9.71%   |
| Card reader              | 26        | 6.82%   |
| Sound                    | 8         | 2.1%    |
| Network                  | 5         | 1.31%   |
| Storage                  | 2         | 0.52%   |
| Storage/nvme             | 1         | 0.26%   |
| Net/ethernet             | 1         | 0.26%   |
| Dvb card                 | 1         | 0.26%   |

