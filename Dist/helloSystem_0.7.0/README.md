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

Total: 450

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| HP            | 8053                        | Desktop     | [92583639f6](https://bsd-hardware.info/?probe=92583639f6) | Nov 02, 2022 |
| Lenovo        | ThinkPad W530 24491A0       | Notebook    | [4a700f43f8](https://bsd-hardware.info/?probe=4a700f43f8) | Oct 30, 2022 |
| Samsung       | Q430/Q530                   | Notebook    | [fb98c8c797](https://bsd-hardware.info/?probe=fb98c8c797) | Oct 29, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [015f0a0a6d](https://bsd-hardware.info/?probe=015f0a0a6d) | Oct 27, 2022 |
| Samsung       | Q430/Q530                   | Notebook    | [4965215a13](https://bsd-hardware.info/?probe=4965215a13) | Oct 25, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [8a4e3767e9](https://bsd-hardware.info/?probe=8a4e3767e9) | Oct 22, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [c6ee09790d](https://bsd-hardware.info/?probe=c6ee09790d) | Oct 20, 2022 |
| ASUSTek       | N3050I-C                    | Desktop     | [4a83b0953e](https://bsd-hardware.info/?probe=4a83b0953e) | Oct 18, 2022 |
| Lenovo        | ThinkPad T61 765912G        | Notebook    | [50c3c93790](https://bsd-hardware.info/?probe=50c3c93790) | Oct 17, 2022 |
| HP            | SpectreXT Pro 13-b000 PC    | Notebook    | [f45ea42873](https://bsd-hardware.info/?probe=f45ea42873) | Oct 16, 2022 |
| HP            | 8169                        | Desktop     | [86b1fbf917](https://bsd-hardware.info/?probe=86b1fbf917) | Oct 15, 2022 |
| HP            | Laptop 15q-bu0xx            | Notebook    | [99c01654a2](https://bsd-hardware.info/?probe=99c01654a2) | Oct 15, 2022 |
| Lenovo        | ThinkCentre M57p 6078AJ6    | Desktop     | [a808a7360d](https://bsd-hardware.info/?probe=a808a7360d) | Oct 14, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [dec7108b53](https://bsd-hardware.info/?probe=dec7108b53) | Oct 11, 2022 |
| Acer          | Aspire 5336                 | Notebook    | [127ddc93fb](https://bsd-hardware.info/?probe=127ddc93fb) | Oct 10, 2022 |
| Acer          | Aspire E5-722G              | Notebook    | [7a4eb565fe](https://bsd-hardware.info/?probe=7a4eb565fe) | Oct 10, 2022 |
| Dell          | Latitude E6420              | Notebook    | [48c26d2a17](https://bsd-hardware.info/?probe=48c26d2a17) | Oct 10, 2022 |
| Fujitsu       | LIFEBOOK U904               | Notebook    | [3a86733538](https://bsd-hardware.info/?probe=3a86733538) | Oct 09, 2022 |
| Acer          | Aspire F5-573               | Notebook    | [9c092c9cd7](https://bsd-hardware.info/?probe=9c092c9cd7) | Oct 05, 2022 |
| HP            | ProBook 4540s               | Notebook    | [df94757940](https://bsd-hardware.info/?probe=df94757940) | Oct 02, 2022 |
| Lenovo        | ThinkPad E15 2ORES4XJ00     | Notebook    | [323a95e6a9](https://bsd-hardware.info/?probe=323a95e6a9) | Oct 01, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [62b9a56103](https://bsd-hardware.info/?probe=62b9a56103) | Sep 29, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [6418fd0b23](https://bsd-hardware.info/?probe=6418fd0b23) | Sep 28, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7763... | Notebook    | [1f37ebf2bb](https://bsd-hardware.info/?probe=1f37ebf2bb) | Sep 28, 2022 |
| Dell          | Precision 7710              | Notebook    | [4c4937d824](https://bsd-hardware.info/?probe=4c4937d824) | Sep 18, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [da4bd87fee](https://bsd-hardware.info/?probe=da4bd87fee) | Sep 17, 2022 |
| Lenovo        | ThinkPad X270 20HMS2LL00    | Notebook    | [12f6a8866f](https://bsd-hardware.info/?probe=12f6a8866f) | Sep 14, 2022 |
| Apple         | Mac-7BA5B2D9E42DDD94        | Desktop     | [d2e169b8ad](https://bsd-hardware.info/?probe=d2e169b8ad) | Sep 13, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [7c9c1db9d7](https://bsd-hardware.info/?probe=7c9c1db9d7) | Sep 10, 2022 |
| Lenovo        | ThinkPad T440 20B7S2LT00    | Notebook    | [5104875f94](https://bsd-hardware.info/?probe=5104875f94) | Sep 06, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [2d3a5a5260](https://bsd-hardware.info/?probe=2d3a5a5260) | Sep 06, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [f4d84edb3b](https://bsd-hardware.info/?probe=f4d84edb3b) | Sep 04, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [11ac5a7932](https://bsd-hardware.info/?probe=11ac5a7932) | Sep 02, 2022 |
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
| ASUSTek       | PRIME X570-P                | Desktop     | [aad86a8b8e](https://bsd-hardware.info/?probe=aad86a8b8e) | May 10, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [3ff916acf7](https://bsd-hardware.info/?probe=3ff916acf7) | May 09, 2022 |
| HP            | ProBook 4340s               | Notebook    | [6cc978f98f](https://bsd-hardware.info/?probe=6cc978f98f) | May 09, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [33367fe342](https://bsd-hardware.info/?probe=33367fe342) | May 09, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [b54df77b59](https://bsd-hardware.info/?probe=b54df77b59) | May 07, 2022 |
| Unknown       | W1415A                      | Notebook    | [1b2c63a845](https://bsd-hardware.info/?probe=1b2c63a845) | May 07, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [daed3f9401](https://bsd-hardware.info/?probe=daed3f9401) | May 06, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [bf3d4941a2](https://bsd-hardware.info/?probe=bf3d4941a2) | May 06, 2022 |
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
| Dell          | 0D6H9T A00                  | Desktop     | [7daab72741](https://bsd-hardware.info/?probe=7daab72741) | Apr 01, 2022 |
| HP            | Compaq 6510b (GF910AW#AB... | Notebook    | [a7bccf74e4](https://bsd-hardware.info/?probe=a7bccf74e4) | Mar 31, 2022 |
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
| MSI           | B85-G43                     | Desktop     | [f0a919c35f](https://bsd-hardware.info/?probe=f0a919c35f) | Mar 25, 2022 |
| MSI           | B85-G43                     | Desktop     | [7bd545fda8](https://bsd-hardware.info/?probe=7bd545fda8) | Mar 25, 2022 |
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
| Dell          | 0YF8P5 A00                  | Desktop     | [0f03a66475](https://bsd-hardware.info/?probe=0f03a66475) | Dec 09, 2021 |
| Dell          | 0YF8P5 A00                  | Desktop     | [83b36f7c3d](https://bsd-hardware.info/?probe=83b36f7c3d) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [a084ff48c2](https://bsd-hardware.info/?probe=a084ff48c2) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [17b557d792](https://bsd-hardware.info/?probe=17b557d792) | Dec 08, 2021 |
| Apple         | MacBookAir1,1               | Notebook    | [61c7028e83](https://bsd-hardware.info/?probe=61c7028e83) | Dec 07, 2021 |
| ASUSTek       | X540LA                      | Notebook    | [fa809be73f](https://bsd-hardware.info/?probe=fa809be73f) | Dec 04, 2021 |
| ASUSTek       | X540LA                      | Notebook    | [cf5fd87781](https://bsd-hardware.info/?probe=cf5fd87781) | Dec 04, 2021 |
| Acer          | Swift SF314-52              | Notebook    | [e3ece211a0](https://bsd-hardware.info/?probe=e3ece211a0) | Dec 03, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [8cfe11fe93](https://bsd-hardware.info/?probe=8cfe11fe93) | Nov 30, 2021 |
| Intel         | DG41TY AAE47335-300         | Desktop     | [dd357bcaa5](https://bsd-hardware.info/?probe=dd357bcaa5) | Nov 30, 2021 |
| HP            | 843B                        | Desktop     | [404224439d](https://bsd-hardware.info/?probe=404224439d) | Nov 29, 2021 |
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
| amd64 | 368       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 365       | 99.18%  |
| GNOME        | 3         | 0.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 368       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 368       | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 349       | 94.58%  |
| es_ES | 5         | 1.36%   |
| de_DE | 5         | 1.36%   |
| fr_FR | 4         | 1.08%   |
| C     | 4         | 1.08%   |
| uk_UA | 1         | 0.27%   |
| it_IT | 1         | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 359       | 97.55%  |
| BIOS | 9         | 2.45%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Cd9660 | 208       | 55.47%  |
| Zfs    | 167       | 44.53%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 363       | 98.64%  |
| MBR  | 5         | 1.36%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 68        | 18.48%  |
| ASUSTek Computer    | 58        | 15.76%  |
| Hewlett-Packard     | 45        | 12.23%  |
| Dell                | 35        | 9.51%   |
| Gigabyte Technology | 30        | 8.15%   |
| Apple               | 24        | 6.52%   |
| Acer                | 21        | 5.71%   |
| Intel               | 14        | 3.8%    |
| ASRock              | 14        | 3.8%    |
| MSI                 | 8         | 2.17%   |
| Toshiba             | 6         | 1.63%   |
| Samsung Electronics | 4         | 1.09%   |
| Fujitsu             | 4         | 1.09%   |
| Unknown             | 4         | 1.09%   |
| TUXEDO              | 3         | 0.82%   |
| Pegatron            | 3         | 0.82%   |
| Sony                | 2         | 0.54%   |
| TWINHEAD            | 1         | 0.27%   |
| T-bao               | 1         | 0.27%   |
| Supermicro          | 1         | 0.27%   |
| Shuttle             | 1         | 0.27%   |
| Razer               | 1         | 0.27%   |
| Quanta              | 1         | 0.27%   |
| Positivo            | 1         | 0.27%   |
| Panasonic           | 1         | 0.27%   |
| Packard Bell        | 1         | 0.27%   |
| OEM                 | 1         | 0.27%   |
| Notebook            | 1         | 0.27%   |
| Medion              | 1         | 0.27%   |
| MAXSUN              | 1         | 0.27%   |
| LG Electronics      | 1         | 0.27%   |
| Koloe               | 1         | 0.27%   |
| Itautec             | 1         | 0.27%   |
| HASEE Computer      | 1         | 0.27%   |
| Gateway             | 1         | 0.27%   |
| eMachines           | 1         | 0.27%   |
| ECS                 | 1         | 0.27%   |
| DNS                 | 1         | 0.27%   |
| BESSTAR Tech        | 1         | 0.27%   |
| ALLEGIANCE GAMING   | 1         | 0.27%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                               | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Apple iMac9,1                                      | 7         | 1.9%    |
| Apple MacBook4,1                                   | 4         | 1.09%   |
| Unknown                                            | 4         | 1.09%   |
| TUXEDO Aura 15 Gen1                                | 2         | 0.54%   |
| HP ProDesk 600 G2 DM                               | 2         | 0.54%   |
| HP ProBook 4540s                                   | 2         | 0.54%   |
| HP EliteDesk 700 G1 SFF                            | 2         | 0.54%   |
| Dell Precision T1700                               | 2         | 0.54%   |
| Dell Precision 7710                                | 2         | 0.54%   |
| Dell Latitude E5470                                | 2         | 0.54%   |
| ASUS TUF GAMING X570-PLUS                          | 2         | 0.54%   |
| ASUS PRIME X570-P                                  | 2         | 0.54%   |
| ASUS P8Z77-V LX                                    | 2         | 0.54%   |
| ASUS All Series                                    | 2         | 0.54%   |
| ASRock X570 Phantom Gaming 4                       | 2         | 0.54%   |
| Apple MacPro5,1                                    | 2         | 0.54%   |
| Apple MacBook6,1                                   | 2         | 0.54%   |
| Acer V5-131                                        | 2         | 0.54%   |
| Acer Aspire E1-522                                 | 2         | 0.54%   |
| Acer Aspire 5930                                   | 2         | 0.54%   |
| TWINHEAD U12CT                                     | 1         | 0.27%   |
| TUXEDO InfinityBook13V3                            | 1         | 0.27%   |
| Toshiba Satellite S55t-B                           | 1         | 0.27%   |
| Toshiba Satellite P300                             | 1         | 0.27%   |
| Toshiba Satellite L550                             | 1         | 0.27%   |
| Toshiba Satellite C640                             | 1         | 0.27%   |
| Toshiba Satellite C50-B                            | 1         | 0.27%   |
| Toshiba PORTEGE R700                               | 1         | 0.27%   |
| T-bao MINI PC                                      | 1         | 0.27%   |
| Supermicro X9DAL                                   | 1         | 0.27%   |
| Sony VGN-NW25GF_S                                  | 1         | 0.27%   |
| Sony SVZ1311C5E                                    | 1         | 0.27%   |
| Shuttle XH170                                      | 1         | 0.27%   |
| Samsung Q430/Q530                                  | 1         | 0.27%   |
| Samsung N150P/N210P/N220P                          | 1         | 0.27%   |
| Samsung N100                                       | 1         | 0.27%   |
| Samsung 305E4A/305E5A/305E7A                       | 1         | 0.27%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.27%   |
| Quanta 120-1135                                    | 1         | 0.27%   |
| Positivo POS-PIQ77CL                               | 1         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 40        | 10.87%  |
| Acer Aspire        | 16        | 4.35%   |
| Dell Latitude      | 11        | 2.99%   |
| HP Pavilion        | 10        | 2.72%   |
| ASUS PRIME         | 9         | 2.45%   |
| Lenovo IdeaPad     | 8         | 2.17%   |
| HP ProBook         | 7         | 1.9%    |
| Dell Inspiron      | 7         | 1.9%    |
| Apple iMac9        | 7         | 1.9%    |
| Lenovo ThinkCentre | 6         | 1.63%   |
| HP EliteDesk       | 6         | 1.63%   |
| Dell OptiPlex      | 6         | 1.63%   |
| ASUS TUF           | 6         | 1.63%   |
| ASUS ROG           | 6         | 1.63%   |
| Toshiba Satellite  | 5         | 1.36%   |
| HP Compaq          | 5         | 1.36%   |
| Dell Precision     | 5         | 1.36%   |
| HP Laptop          | 4         | 1.09%   |
| Apple MacBook4     | 4         | 1.09%   |
| Unknown            | 4         | 1.09%   |
| HP EliteBook       | 3         | 0.82%   |
| Gigabyte X570      | 3         | 0.82%   |
| TUXEDO Aura        | 2         | 0.54%   |
| Lenovo Legion      | 2         | 0.54%   |
| HP ProDesk         | 2         | 0.54%   |
| Gigabyte B450      | 2         | 0.54%   |
| Fujitsu LIFEBOOK   | 2         | 0.54%   |
| Fujitsu ESPRIMO    | 2         | 0.54%   |
| Dell Vostro        | 2         | 0.54%   |
| Dell PowerEdge     | 2         | 0.54%   |
| ASUS P8Z77-V       | 2         | 0.54%   |
| ASUS P5GC-MX       | 2         | 0.54%   |
| ASUS Maximus       | 2         | 0.54%   |
| ASUS All           | 2         | 0.54%   |
| ASRock X570        | 2         | 0.54%   |
| Apple MacPro5      | 2         | 0.54%   |
| Apple MacBookPro5  | 2         | 0.54%   |
| Apple MacBook6     | 2         | 0.54%   |
| Apple MacBook5     | 2         | 0.54%   |
| Acer V5-131        | 2         | 0.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 38        | 10.33%  |
| 2018    | 31        | 8.42%   |
| 2012    | 30        | 8.15%   |
| 2013    | 29        | 7.88%   |
| 2019    | 28        | 7.61%   |
| 2020    | 25        | 6.79%   |
| 2016    | 25        | 6.79%   |
| 2009    | 25        | 6.79%   |
| 2010    | 24        | 6.52%   |
| 2014    | 21        | 5.71%   |
| 2011    | 21        | 5.71%   |
| 2017    | 20        | 5.43%   |
| 2015    | 19        | 5.16%   |
| 2008    | 13        | 3.53%   |
| 2007    | 11        | 2.99%   |
| 2022    | 5         | 1.36%   |
| 2006    | 2         | 0.54%   |
| Unknown | 1         | 0.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 186       | 50.54%  |
| Desktop     | 157       | 42.66%  |
| Mini pc     | 12        | 3.26%   |
| All in one  | 11        | 2.99%   |
| Convertible | 1         | 0.27%   |
| Server      | 1         | 0.27%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 368       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 110       | 29.89%  |
| 4.01-8.0    | 109       | 29.62%  |
| 16.01-24.0  | 78        | 21.2%   |
| 32.01-64.0  | 33        | 8.97%   |
| 2.01-3.0    | 19        | 5.16%   |
| 64.01-256.0 | 8         | 2.17%   |
| 3.01-4.0    | 5         | 1.36%   |
| 24.01-32.0  | 4         | 1.09%   |
| 1.01-2.0    | 1         | 0.27%   |
| 0.51-1.0    | 1         | 0.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 198       | 53.66%  |
| 0.51-1.0  | 109       | 29.54%  |
| 1.01-2.0  | 48        | 13.01%  |
| 2.01-3.0  | 11        | 2.98%   |
| 3.01-4.0  | 2         | 0.54%   |
| 8.01-16.0 | 1         | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 226       | 60.43%  |
| 2      | 88        | 23.53%  |
| 3      | 19        | 5.08%   |
| 0      | 18        | 4.81%   |
| 4      | 15        | 4.01%   |
| 5      | 4         | 1.07%   |
| 6      | 2         | 0.53%   |
| 9      | 1         | 0.27%   |
| 7      | 1         | 0.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 220       | 59.78%  |
| Yes       | 148       | 40.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 352       | 95.65%  |
| No        | 16        | 4.35%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 254       | 69.02%  |
| No        | 114       | 30.98%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 187       | 50.82%  |
| No        | 181       | 49.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country             | Computers | Percent |
|---------------------|-----------|---------|
| USA                 | 59        | 16.03%  |
| Russia              | 38        | 10.33%  |
| Germany             | 22        | 5.98%   |
| Brazil              | 22        | 5.98%   |
| Spain               | 17        | 4.62%   |
| Italy               | 17        | 4.62%   |
| China               | 15        | 4.08%   |
| Poland              | 14        | 3.8%    |
| UK                  | 13        | 3.53%   |
| Canada              | 13        | 3.53%   |
| France              | 11        | 2.99%   |
| Ukraine             | 10        | 2.72%   |
| Hungary             | 9         | 2.45%   |
| Romania             | 8         | 2.17%   |
| Netherlands         | 7         | 1.9%    |
| India               | 7         | 1.9%    |
| Mexico              | 6         | 1.63%   |
| Turkey              | 5         | 1.36%   |
| Vietnam             | 4         | 1.09%   |
| Peru                | 4         | 1.09%   |
| Norway              | 4         | 1.09%   |
| Indonesia           | 4         | 1.09%   |
| Australia           | 4         | 1.09%   |
| South Korea         | 3         | 0.82%   |
| Portugal            | 3         | 0.82%   |
| Greece              | 3         | 0.82%   |
| Denmark             | 3         | 0.82%   |
| Chile               | 3         | 0.82%   |
| Taiwan              | 2         | 0.54%   |
| Switzerland         | 2         | 0.54%   |
| Sweden              | 2         | 0.54%   |
| New Zealand         | 2         | 0.54%   |
| Finland             | 2         | 0.54%   |
| Czechia             | 2         | 0.54%   |
| Colombia            | 2         | 0.54%   |
| Argentina           | 2         | 0.54%   |
| Venezuela           | 1         | 0.27%   |
| Trinidad and Tobago | 1         | 0.27%   |
| Thailand            | 1         | 0.27%   |
| Tanzania            | 1         | 0.27%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Moscow                        | 7         | 1.86%   |
| St Petersburg                 | 5         | 1.33%   |
| Lima                          | 4         | 1.06%   |
| Hanoi                         | 4         | 1.06%   |
| Amsterdam                     | 4         | 1.06%   |
| Warsaw                        | 3         | 0.8%    |
| Sao Paulo                     | 3         | 0.8%    |
| Rio de Janeiro                | 3         | 0.8%    |
| Kharkiv                       | 3         | 0.8%    |
| Guangzhou                     | 3         | 0.8%    |
| Curitiba                      | 3         | 0.8%    |
| Bucharest                     | 3         | 0.8%    |
| Tromsø                       | 2         | 0.53%   |
| Tiruchi                       | 2         | 0.53%   |
| Surgut                        | 2         | 0.53%   |
| Suceava                       | 2         | 0.53%   |
| Stavropol                     | 2         | 0.53%   |
| Smiths Falls                  | 2         | 0.53%   |
| Sherwood Park                 | 2         | 0.53%   |
| Scottsdale                    | 2         | 0.53%   |
| San SebastiÃ¡n de los Reyes | 2         | 0.53%   |
| Pflugerville                  | 2         | 0.53%   |
| Perth                         | 2         | 0.53%   |
| Novosibirsk                   | 2         | 0.53%   |
| Myrtle Beach                  | 2         | 0.53%   |
| Madrid                        | 2         | 0.53%   |
| Leatherhead                   | 2         | 0.53%   |
| Kyiv                          | 2         | 0.53%   |
| Katowice                      | 2         | 0.53%   |
| Jakarta                       | 2         | 0.53%   |
| Izhevsk                       | 2         | 0.53%   |
| Istanbul                      | 2         | 0.53%   |
| Dreieich                      | 2         | 0.53%   |
| Dijon                         | 2         | 0.53%   |
| Coria del RÃ­o              | 2         | 0.53%   |
| Castilleja de la Cuesta       | 2         | 0.53%   |
| Beijing                       | 2         | 0.53%   |
| Barnaul                       | 2         | 0.53%   |
| Ankara                        | 2         | 0.53%   |
| Adelfia                       | 2         | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 87        | 106    | 16.99%  |
| Seagate             | 84        | 106    | 16.41%  |
| Samsung Electronics | 81        | 103    | 15.82%  |
| Toshiba             | 37        | 42     | 7.23%   |
| Kingston            | 35        | 41     | 6.84%   |
| Crucial             | 30        | 36     | 5.86%   |
| SanDisk             | 18        | 19     | 3.52%   |
| Hitachi             | 16        | 18     | 3.13%   |
| Intel               | 15        | 16     | 2.93%   |
| A-DATA Technology   | 11        | 12     | 2.15%   |
| HGST                | 9         | 9      | 1.76%   |
| SK hynix            | 6         | 8      | 1.17%   |
| Patriot             | 6         | 6      | 1.17%   |
| Phison              | 5         | 5      | 0.98%   |
| Micron Technology   | 5         | 5      | 0.98%   |
| GOODRAM             | 5         | 6      | 0.98%   |
| Fujitsu             | 5         | 5      | 0.98%   |
| XPG                 | 4         | 4      | 0.78%   |
| SPCC                | 4         | 5      | 0.78%   |
| KingSpec            | 4         | 4      | 0.78%   |
| Intenso             | 4         | 4      | 0.78%   |
| Team                | 3         | 3      | 0.59%   |
| PNY                 | 3         | 3      | 0.59%   |
| OCZ                 | 3         | 3      | 0.59%   |
| Mushkin             | 2         | 2      | 0.39%   |
| LITEON              | 2         | 3      | 0.39%   |
| Gigabyte Technology | 2         | 3      | 0.39%   |
| Corsair             | 2         | 2      | 0.39%   |
| Apple               | 2         | 2      | 0.39%   |
| Apacer              | 2         | 2      | 0.39%   |
| Zheino              | 1         | 1      | 0.2%    |
| XrayDisk            | 1         | 1      | 0.2%    |
| Transcend           | 1         | 1      | 0.2%    |
| tigo                | 1         | 1      | 0.2%    |
| SSSTC               | 1         | 1      | 0.2%    |
| Smartbuy            | 1         | 1      | 0.2%    |
| Silicon Motion      | 1         | 1      | 0.2%    |
| Plextor             | 1         | 1      | 0.2%    |
| Netac               | 1         | 1      | 0.2%    |
| Lite-On             | 1         | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37120G 120GB        | 9         | 1.63%   |
| WDC WDS120G2G0A-00JH30 120GB       | 6         | 1.09%   |
| Kingston SA400S37240G 240GB        | 6         | 1.09%   |
| HGST HTS545050A7E680 500GB         | 6         | 1.09%   |
| Crucial CT500MX500SSD1 500GB       | 6         | 1.09%   |
| Crucial CT240BX500SSD1 240GB       | 6         | 1.09%   |
| Toshiba MQ01ABF050 500GB           | 5         | 0.91%   |
| Seagate ST1000DM010-2EP102 1TB     | 5         | 0.91%   |
| Seagate ST1000DM003-1ER162 1TB     | 5         | 0.91%   |
| XPG GAMMIX S11 Pro 256GB           | 4         | 0.73%   |
| WDC WDS240G2G0A-00JH30 240GB       | 4         | 0.73%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 4         | 0.73%   |
| Samsung SSD 980 PRO 1TB            | 4         | 0.73%   |
| Samsung SSD 860 EVO 250GB          | 4         | 0.73%   |
| Samsung SSD 850 EVO 500GB          | 4         | 0.73%   |
| Toshiba MQ01ABD100 1TB             | 3         | 0.54%   |
| Toshiba HDWD110 1TB                | 3         | 0.54%   |
| Seagate ST4000DM004-2CV104 4TB     | 3         | 0.54%   |
| Seagate ST31000528AS 1TB           | 3         | 0.54%   |
| Seagate ST2000DM008-2FR102 2TB     | 3         | 0.54%   |
| Seagate ST1000LM035-1RK172 1TB     | 3         | 0.54%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 0.54%   |
| Samsung SSD 970 EVO Plus 500GB     | 3         | 0.54%   |
| Samsung SSD 970 EVO Plus 1TB       | 3         | 0.54%   |
| Samsung SSD 870 EVO 500GB          | 3         | 0.54%   |
| Samsung SSD 860 EVO 500GB          | 3         | 0.54%   |
| Samsung SSD 860 EVO 1TB            | 3         | 0.54%   |
| Samsung SSD 850 EVO 250GB          | 3         | 0.54%   |
| Samsung HD322HJ 320GB              | 3         | 0.54%   |
| Hitachi HTS541680J9SA00 80GB       | 3         | 0.54%   |
| Crucial CT480BX500SSD1 480GB       | 3         | 0.54%   |
| Crucial CT120BX500SSD1 120GB       | 3         | 0.54%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 2         | 0.36%   |
| WDC WDS100T2B0C-00PXH0 1TB         | 2         | 0.36%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 2         | 0.36%   |
| WDC WD3200AAJS-00YZCA0 320GB       | 2         | 0.36%   |
| WDC WD20PURZ-85GU6Y0 2TB           | 2         | 0.36%   |
| WDC WD1600AAJS-40H3A0 160GB        | 2         | 0.36%   |
| WDC WD10JPCX-24UE4T0 1TB           | 2         | 0.36%   |
| Toshiba DT01ACA100 1TB             | 2         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 83        | 102    | 37.56%  |
| WDC                 | 64        | 72     | 28.96%  |
| Toshiba             | 33        | 37     | 14.93%  |
| Hitachi             | 16        | 18     | 7.24%   |
| Samsung Electronics | 11        | 11     | 4.98%   |
| HGST                | 9         | 9      | 4.07%   |
| Fujitsu             | 4         | 4      | 1.81%   |
| Apple               | 1         | 1      | 0.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 47        | 52     | 21.17%  |
| Crucial             | 29        | 34     | 13.06%  |
| Kingston            | 28        | 32     | 12.61%  |
| SanDisk             | 18        | 19     | 8.11%   |
| WDC                 | 15        | 19     | 6.76%   |
| Intel               | 11        | 11     | 4.95%   |
| A-DATA Technology   | 9         | 9      | 4.05%   |
| Patriot             | 6         | 6      | 2.7%    |
| Goodram             | 5         | 6      | 2.25%   |
| SPCC                | 4         | 5      | 1.8%    |
| KingSpec            | 4         | 4      | 1.8%    |
| Intenso             | 4         | 4      | 1.8%    |
| Toshiba             | 3         | 4      | 1.35%   |
| SK hynix            | 3         | 3      | 1.35%   |
| PNY                 | 3         | 3      | 1.35%   |
| OCZ                 | 3         | 3      | 1.35%   |
| Team                | 2         | 2      | 0.9%    |
| LITEON              | 2         | 3      | 0.9%    |
| Gigabyte Technology | 2         | 3      | 0.9%    |
| Corsair             | 2         | 2      | 0.9%    |
| Apacer              | 2         | 2      | 0.9%    |
| Zheino              | 1         | 1      | 0.45%   |
| XrayDisk            | 1         | 1      | 0.45%   |
| Transcend           | 1         | 1      | 0.45%   |
| tigo                | 1         | 1      | 0.45%   |
| Smartbuy            | 1         | 1      | 0.45%   |
| Plextor             | 1         | 1      | 0.45%   |
| Netac               | 1         | 1      | 0.45%   |
| Mushkin             | 1         | 1      | 0.45%   |
| Micron Technology   | 1         | 1      | 0.45%   |
| Lite-On             | 1         | 1      | 0.45%   |
| Lexar               | 1         | 1      | 0.45%   |
| Leven               | 1         | 1      | 0.45%   |
| Integral            | 1         | 1      | 0.45%   |
| INDMEM              | 1         | 1      | 0.45%   |
| Hewlett-Packard     | 1         | 1      | 0.45%   |
| Fujitsu             | 1         | 1      | 0.45%   |
| EMTEC               | 1         | 1      | 0.45%   |
| China               | 1         | 1      | 0.45%   |
| Apple               | 1         | 1      | 0.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 190       | 254    | 41.76%  |
| SSD  | 189       | 246    | 41.54%  |
| NVMe | 76        | 103    | 16.7%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 323       | 500    | 80.95%  |
| NVMe | 76        | 103    | 19.05%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 270       | 361    | 70.31%  |
| 0.51-1.0   | 76        | 90     | 19.79%  |
| 1.01-2.0   | 19        | 21     | 4.95%   |
| 3.01-4.0   | 9         | 16     | 2.34%   |
| 2.01-3.0   | 5         | 6      | 1.3%    |
| 4.01-10.0  | 4         | 5      | 1.04%   |
| 10.01-20.0 | 1         | 1      | 0.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 201       | 53.6%   |
| 101-250    | 86        | 22.93%  |
| 251-500    | 50        | 13.33%  |
| 501-1000   | 23        | 6.13%   |
| 21-50      | 7         | 1.87%   |
| 51-100     | 7         | 1.87%   |
| Unknown    | 1         | 0.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 363       | 98.64%  |
| 21-50   | 3         | 0.82%   |
| 101-250 | 1         | 0.27%   |
| Unknown | 1         | 0.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST3500413AS 500GB          | 2         | 3      | 2.04%   |
| Seagate ST3320418AS 320GB          | 2         | 2      | 2.04%   |
| Seagate ST31000528AS 1TB           | 2         | 3      | 2.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 2      | 2.04%   |
| XrayDisk SSD 240GB                 | 1         | 1      | 1.02%   |
| WDC WD60EZRZ-00RWYB1 6TB           | 1         | 1      | 1.02%   |
| WDC WD5000LPLX-60ZNTT1 500GB       | 1         | 1      | 1.02%   |
| WDC WD5000LPCX-75VHAT0 500GB       | 1         | 1      | 1.02%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 1         | 1      | 1.02%   |
| WDC WD5000BPVT-22HXZT3 500GB       | 1         | 1      | 1.02%   |
| WDC WD5000AZLX-00CL5A0 500GB       | 1         | 1      | 1.02%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1         | 1      | 1.02%   |
| WDC WD5000AAKS-22A7B0 500GB        | 1         | 1      | 1.02%   |
| WDC WD400JB-00ENA0 40GB            | 1         | 1      | 1.02%   |
| WDC WD3200BPVT-80ZEST0 320GB       | 1         | 1      | 1.02%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 1         | 1      | 1.02%   |
| WDC WD3200AAJS-22B4A0 320GB        | 1         | 1      | 1.02%   |
| WDC WD3200AAJS-00YZCA0 320GB       | 1         | 1      | 1.02%   |
| WDC WD20EURS-63S48Y0 2TB           | 1         | 1      | 1.02%   |
| WDC WD1600BEVT-80A23T0 160GB       | 1         | 1      | 1.02%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 1         | 1      | 1.02%   |
| WDC WD1600BEKT-66F3T2 160GB        | 1         | 1      | 1.02%   |
| WDC WD1600AAJS-40H3A0 160GB        | 1         | 1      | 1.02%   |
| WDC WD10SPZX-24Z10T0 1TB           | 1         | 1      | 1.02%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 1.02%   |
| WDC WD10EZEX-08M2NA0 1TB           | 1         | 1      | 1.02%   |
| WDC WD10EARS-003BB1 1TB            | 1         | 1      | 1.02%   |
| Toshiba THNSNX024GMNT 24GB         | 1         | 1      | 1.02%   |
| Toshiba MQ01UBD100 1TB             | 1         | 1      | 1.02%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 1.02%   |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 1.02%   |
| Toshiba MQ01ABD075 752GB           | 1         | 1      | 1.02%   |
| Toshiba MQ01ABD025 250GB           | 1         | 1      | 1.02%   |
| Toshiba MK8034GSX 80GB             | 1         | 1      | 1.02%   |
| Toshiba MK7559GSXF 752GB           | 1         | 1      | 1.02%   |
| Toshiba MK6034GSX 64GB             | 1         | 1      | 1.02%   |
| Toshiba MK3265GSXN 320GB           | 1         | 1      | 1.02%   |
| Toshiba MK3261GSYN 320GB           | 1         | 1      | 1.02%   |
| Toshiba MD04ACA400 4TB             | 1         | 1      | 1.02%   |
| Toshiba DT01ACA100 1TB             | 1         | 3      | 1.02%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 30     | 27.37%  |
| WDC                 | 22        | 22     | 23.16%  |
| Toshiba             | 13        | 16     | 13.68%  |
| Hitachi             | 9         | 11     | 9.47%   |
| Samsung Electronics | 7         | 9      | 7.37%   |
| Kingston            | 4         | 4      | 4.21%   |
| Intel               | 2         | 2      | 2.11%   |
| HGST                | 2         | 2      | 2.11%   |
| Crucial             | 2         | 2      | 2.11%   |
| XrayDisk            | 1         | 1      | 1.05%   |
| SanDisk             | 1         | 1      | 1.05%   |
| LITEON              | 1         | 1      | 1.05%   |
| KingSpec            | 1         | 1      | 1.05%   |
| Fujitsu             | 1         | 1      | 1.05%   |
| Corsair             | 1         | 1      | 1.05%   |
| AGI                 | 1         | 1      | 1.05%   |
| A-DATA Technology   | 1         | 1      | 1.05%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 30     | 33.77%  |
| WDC                 | 22        | 22     | 28.57%  |
| Toshiba             | 12        | 15     | 15.58%  |
| Hitachi             | 9         | 11     | 11.69%  |
| Samsung Electronics | 5         | 5      | 6.49%   |
| HGST                | 2         | 2      | 2.6%    |
| Fujitsu             | 1         | 1      | 1.3%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 71        | 86     | 78.89%  |
| SSD  | 16        | 17     | 17.78%  |
| NVMe | 3         | 3      | 3.33%   |

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
| Works    | 295       | 493    | 76.42%  |
| Malfunc  | 87        | 106    | 22.54%  |
| Detected | 3         | 3      | 0.78%   |
| Failed   | 1         | 1      | 0.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 271       | 60.36%  |
| AMD                              | 65        | 14.48%  |
| Samsung Electronics              | 32        | 7.13%   |
| Nvidia                           | 19        | 4.23%   |
| SanDisk                          | 10        | 2.23%   |
| Kingston Technology Company      | 6         | 1.34%   |
| ADATA Technology                 | 6         | 1.34%   |
| Phison Electronics               | 5         | 1.11%   |
| Micron Technology                | 4         | 0.89%   |
| Marvell Technology Group         | 4         | 0.89%   |
| SK hynix                         | 3         | 0.67%   |
| Silicon Motion                   | 3         | 0.67%   |
| JMicron Technology               | 3         | 0.67%   |
| Broadcom / LSI                   | 3         | 0.67%   |
| ASMedia Technology               | 3         | 0.67%   |
| Seagate Technology               | 2         | 0.45%   |
| Micron/Crucial Technology        | 2         | 0.45%   |
| KIOXIA                           | 2         | 0.45%   |
| VIA Technologies                 | 1         | 0.22%   |
| Solid State Storage Technology   | 1         | 0.22%   |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |
| Shenzhen Longsys Electronics     | 1         | 0.22%   |
| Realtek Semiconductor            | 1         | 0.22%   |
| Apple                            | 1         | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 54        | 10.53%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 21        | 4.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 21        | 4.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 19        | 3.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 16        | 3.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 14        | 2.73%   |
| Nvidia MCP79 AHCI Controller                                                     | 14        | 2.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 14        | 2.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 13        | 2.53%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 2.34%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 12        | 2.34%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 11        | 2.14%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 11        | 2.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 11        | 2.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 11        | 2.14%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 10        | 1.95%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 10        | 1.95%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 10        | 1.95%   |
| Unknown                                                                          | 10        | 1.95%   |
| Intel SATA Controller [RAID mode]                                                | 9         | 1.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 8         | 1.56%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 8         | 1.56%   |
| AMD 400 Series Chipset SATA Controller                                           | 8         | 1.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 1.36%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 6         | 1.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 1.17%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 6         | 1.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 5         | 0.97%   |
| Samsung NVMe SSD Controller 980                                                  | 5         | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 0.97%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 0.97%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 5         | 0.97%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 0.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 0.78%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 4         | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 0.78%   |
| AMD FCH SATA Controller D                                                        | 4         | 0.78%   |
| AMD 300 Series Chipset SATA Controller                                           | 4         | 0.78%   |
| Phison E12 NVMe Controller                                                       | 3         | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 311       | 67.9%   |
| NVMe | 76        | 16.59%  |
| IDE  | 51        | 11.14%  |
| RAID | 18        | 3.93%   |
| SAS  | 1         | 0.22%   |
| SCSI | 1         | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 294       | 79.89%  |
| AMD    | 74        | 20.11%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz      | 8         | 2.17%   |
| Intel CPU Version                      | 5         | 1.36%   |
| Intel Core i5-7200U CPU @ 2.50GHz      | 5         | 1.36%   |
| Intel Core i5-6500 CPU @ 3.20GHz       | 5         | 1.36%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 5         | 1.36%   |
| Intel Core i5 CPU M 520 @ 2.40GHz      | 4         | 1.09%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz   | 4         | 1.09%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz   | 4         | 1.09%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 3         | 0.82%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 3         | 0.82%   |
| Intel Core i7-3612QM CPU @ 2.10GHz     | 3         | 0.82%   |
| Intel Core i5-6300U CPU @ 2.40GHz      | 3         | 0.82%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 3         | 0.82%   |
| Intel Core i5-4300M CPU @ 2.60GHz      | 3         | 0.82%   |
| Intel Core i5-3320M CPU @ 2.60GHz      | 3         | 0.82%   |
| Intel Core i5-3210M CPU @ 2.50GHz      | 3         | 0.82%   |
| Intel Core i3-6006U CPU @ 2.00GHz      | 3         | 0.82%   |
| Intel Core i3-3110M CPU @ 2.40GHz      | 3         | 0.82%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz   | 3         | 0.82%   |
| Intel Core 2 Duo CPU E8135 @ 2.66GHz   | 3         | 0.82%   |
| Intel Core 2 Duo                       | 3         | 0.82%   |
| Intel Celeron CPU N3050 @ 1.60GHz      | 3         | 0.82%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 3         | 0.82%   |
| Intel Xeon CPU X3470 @ 2.93GHz         | 2         | 0.54%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz    | 2         | 0.54%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz    | 2         | 0.54%   |
| Intel Pentium CPU G860 @ 3.00GHz       | 2         | 0.54%   |
| Intel Genuine CPU                      | 2         | 0.54%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz     | 2         | 0.54%   |
| Intel Core i7-6500U CPU @ 2.50GHz      | 2         | 0.54%   |
| Intel Core i7-4600U CPU @ 2.10GHz      | 2         | 0.54%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 2         | 0.54%   |
| Intel Core i7-10510U CPU @ 1.80GHz     | 2         | 0.54%   |
| Intel Core i5-9400 CPU @ 2.90GHz       | 2         | 0.54%   |
| Intel Core i5-9300H CPU @ 2.40GHz      | 2         | 0.54%   |
| Intel Core i5-8250U CPU @ 1.60GHz      | 2         | 0.54%   |
| Intel Core i5-7300U CPU @ 2.60GHz      | 2         | 0.54%   |
| Intel Core i5-6500T CPU @ 2.50GHz      | 2         | 0.54%   |
| Intel Core i5-6200U CPU @ 2.30GHz      | 2         | 0.54%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 2         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 94        | 25.54%  |
| Intel Core i7           | 43        | 11.68%  |
| Intel Core 2 Duo        | 40        | 10.87%  |
| Intel Core i3           | 34        | 9.24%   |
| Intel Xeon              | 20        | 5.43%   |
| Intel Celeron           | 19        | 5.16%   |
| AMD Ryzen 5             | 18        | 4.89%   |
| AMD Ryzen 7             | 15        | 4.08%   |
| Intel Pentium           | 10        | 2.72%   |
| Other                   | 8         | 2.17%   |
| Intel Pentium Dual-Core | 6         | 1.63%   |
| Intel Core 2 Quad       | 6         | 1.63%   |
| AMD A6                  | 6         | 1.63%   |
| AMD Ryzen 3             | 5         | 1.36%   |
| Intel Atom              | 4         | 1.09%   |
| AMD Ryzen 9             | 4         | 1.09%   |
| Intel Core 2            | 3         | 0.82%   |
| AMD Phenom II X4        | 3         | 0.82%   |
| AMD E2                  | 3         | 0.82%   |
| AMD E1                  | 3         | 0.82%   |
| AMD A10                 | 3         | 0.82%   |
| Intel Genuine           | 2         | 0.54%   |
| AMD Ryzen Threadripper  | 2         | 0.54%   |
| AMD FX                  | 2         | 0.54%   |
| Intel Pentium M         | 1         | 0.27%   |
| Intel Pentium Dual      | 1         | 0.27%   |
| Intel Pentium D         | 1         | 0.27%   |
| Intel Core M            | 1         | 0.27%   |
| Intel Core i9           | 1         | 0.27%   |
| Intel Celeron Dual-Core | 1         | 0.27%   |
| AMD Ryzen 5 PRO         | 1         | 0.27%   |
| AMD E                   | 1         | 0.27%   |
| AMD Athlon II X4        | 1         | 0.27%   |
| AMD Athlon II X2        | 1         | 0.27%   |
| AMD Athlon Dual Core    | 1         | 0.27%   |
| AMD Athlon 64 X2        | 1         | 0.27%   |
| AMD Athlon              | 1         | 0.27%   |
| AMD A8                  | 1         | 0.27%   |
| AMD A4                  | 1         | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 150       | 40.76%  |
| 4       | 103       | 27.99%  |
| Unknown | 46        | 12.5%   |
| 6       | 22        | 5.98%   |
| 8       | 17        | 4.62%   |
| 16      | 11        | 2.99%   |
| 12      | 11        | 2.99%   |
| 24      | 3         | 0.82%   |
| 64      | 1         | 0.27%   |
| 48      | 1         | 0.27%   |
| 32      | 1         | 0.27%   |
| 14      | 1         | 0.27%   |
| 1       | 1         | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 344       | 93.48%  |
| 2       | 22        | 5.98%   |
| Unknown | 2         | 0.54%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 162       | 44.02%  |
| 1       | 160       | 43.48%  |
| Unknown | 46        | 12.5%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Penryn        | 46        | 12.5%   |
| KabyLake      | 41        | 11.14%  |
| IvyBridge     | 40        | 10.87%  |
| Haswell       | 33        | 8.97%   |
| Skylake       | 32        | 8.7%    |
| SandyBridge   | 26        | 7.07%   |
| Westmere      | 18        | 4.89%   |
| Core          | 17        | 4.62%   |
| Zen 2         | 16        | 4.35%   |
| Zen+          | 14        | 3.8%    |
| Silvermont    | 11        | 2.99%   |
| Zen           | 10        | 2.72%   |
| Zen 3         | 7         | 1.9%    |
| Piledriver    | 7         | 1.9%    |
| CometLake     | 7         | 1.9%    |
| Broadwell     | 7         | 1.9%    |
| Nehalem       | 5         | 1.36%   |
| K10           | 5         | 1.36%   |
| Jaguar        | 4         | 1.09%   |
| Bonnell       | 4         | 1.09%   |
| Bobcat        | 4         | 1.09%   |
| Goldmont      | 3         | 0.82%   |
| Puma          | 2         | 0.54%   |
| K8 Hammer     | 2         | 0.54%   |
| Excavator     | 2         | 0.54%   |
| Unknown       | 2         | 0.54%   |
| NetBurst      | 1         | 0.27%   |
| K10 Llano     | 1         | 0.27%   |
| Goldmont plus | 1         | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 209       | 51.48%  |
| Nvidia                     | 112       | 27.59%  |
| AMD                        | 84        | 20.69%  |
| Matrox Electronics Systems | 1         | 0.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 5.2%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 4.73%   |
| Intel HD Graphics 530                                                                    | 16        | 3.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 2.84%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 2.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 11        | 2.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 11        | 2.6%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 2.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 2.13%   |
| Intel HD Graphics 620                                                                    | 9         | 2.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 2.13%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 1.89%   |
| Nvidia C79 [GeForce 9400]                                                                | 7         | 1.65%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 1.42%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.42%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 1.42%   |
| Nvidia C79 [GeForce 9400M]                                                               | 5         | 1.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.18%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.18%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 1.18%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 0.95%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 0.95%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 0.95%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4         | 0.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 0.95%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 0.95%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 0.95%   |
| AMD Renoir                                                                               | 4         | 0.95%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 4         | 0.95%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.71%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.71%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.71%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 0.71%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 3         | 0.71%   |
| Intel UHD Graphics 620                                                                   | 3         | 0.71%   |
| Intel HD Graphics 500                                                                    | 3         | 0.71%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.71%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 3         | 0.71%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 3         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 151       | 40.7%   |
| 1 x Nvidia     | 84        | 22.64%  |
| 1 x AMD        | 71        | 19.14%  |
| 2 x Intel      | 25        | 6.74%   |
| Intel + Nvidia | 25        | 6.74%   |
| Intel + AMD    | 8         | 2.16%   |
| AMD + Nvidia   | 3         | 0.81%   |
| 2 x AMD        | 2         | 0.54%   |
| 2 x Nvidia     | 1         | 0.27%   |
| 1 x Matrox     | 1         | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 287       | 77.57%  |
| Proprietary | 77        | 20.81%  |
| Unknown     | 6         | 1.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 231       | 62.1%   |
| 0.01-0.5   | 45        | 12.1%   |
| 1.01-2.0   | 27        | 7.26%   |
| 0.51-1.0   | 24        | 6.45%   |
| 3.01-4.0   | 21        | 5.65%   |
| 7.01-8.0   | 14        | 3.76%   |
| 5.01-6.0   | 7         | 1.88%   |
| 8.01-16.0  | 2         | 0.54%   |
| 2.01-3.0   | 1         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 46        | 13.03%  |
| LG Display              | 36        | 10.2%   |
| AU Optronics            | 33        | 9.35%   |
| Chimei Innolux          | 29        | 8.22%   |
| Lenovo                  | 22        | 6.23%   |
| Goldstar                | 21        | 5.95%   |
| Apple                   | 20        | 5.67%   |
| Dell                    | 19        | 5.38%   |
| BOE                     | 17        | 4.82%   |
| BenQ                    | 12        | 3.4%    |
| AOC                     | 12        | 3.4%    |
| Acer                    | 11        | 3.12%   |
| Philips                 | 10        | 2.83%   |
| Hewlett-Packard         | 9         | 2.55%   |
| Ancor Communications    | 8         | 2.27%   |
| Sony                    | 5         | 1.42%   |
| Fujitsu Siemens         | 5         | 1.42%   |
| ASUSTek Computer        | 5         | 1.42%   |
| ViewSonic               | 3         | 0.85%   |
| Chi Mei Optoelectronics | 3         | 0.85%   |
| Vestel Elektronik       | 2         | 0.57%   |
| Sharp                   | 2         | 0.57%   |
| NEC Computers           | 2         | 0.57%   |
| MSI                     | 2         | 0.57%   |
| Iiyama                  | 2         | 0.57%   |
| ZL_                     | 1         | 0.28%   |
| Westinghouse            | 1         | 0.28%   |
| Toshiba                 | 1         | 0.28%   |
| SLD                     | 1         | 0.28%   |
| SGT                     | 1         | 0.28%   |
| RTK                     | 1         | 0.28%   |
| PANDA                   | 1         | 0.28%   |
| Medion                  | 1         | 0.28%   |
| LTV                     | 1         | 0.28%   |
| LG Philips              | 1         | 0.28%   |
| Lenovo Group Limited    | 1         | 0.28%   |
| LED                     | 1         | 0.28%   |
| InfoVision              | 1         | 0.28%   |
| GRR                     | 1         | 0.28%   |
| FND                     | 1         | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 4         | 1.1%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 4         | 1.1%    |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch       | 3         | 0.83%   |
| Apple Color LCD APP9C93 1680x1050 430x270mm 20.0-inch                 | 3         | 0.83%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 2         | 0.55%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 2         | 0.55%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                       | 2         | 0.55%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 300x170mm 13.6-inch  | 2         | 0.55%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch  | 2         | 0.55%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 2         | 0.55%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 2         | 0.55%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 2         | 0.55%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch          | 2         | 0.55%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 2         | 0.55%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch           | 2         | 0.55%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch               | 2         | 0.55%   |
| Lenovo LCD Monitor LEN40A0 1366x768 310x170mm 13.9-inch               | 2         | 0.55%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 2         | 0.55%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch               | 2         | 0.55%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch            | 2         | 0.55%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch       | 2         | 0.55%   |
| BenQ GW2780 BNQ78E6 1920x1080 600x340mm 27.2-inch                     | 2         | 0.55%   |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch         | 2         | 0.55%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 2         | 0.55%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch        | 2         | 0.55%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 2         | 0.55%   |
| ASUSTek Computer ROG XG279Q AUS278D 2560x1440 600x340mm 27.2-inch     | 2         | 0.55%   |
| Apple Color LCD APP9C96 1920x1200 520x320mm 24.0-inch                 | 2         | 0.55%   |
| Apple Color LCD APP9C5E 1280x800 290x190mm 13.6-inch                  | 2         | 0.55%   |
| AOC 24G2W1G4 AOC2402 1920x1080 530x300mm 24.0-inch                    | 2         | 0.55%   |
| Ancor Communications MX27AQ ACI27A5 2560x1440 600x340mm 27.2-inch     | 2         | 0.55%   |
| ZL_ zhuoyue-HDMI ZL_2716 2560x1440 600x330mm 27.0-inch                | 1         | 0.28%   |
| Westinghouse LCM-19w4 WDE1904 1440x900 410x260mm 19.1-inch            | 1         | 0.28%   |
| ViewSonic VX1940w VSC6A20 1680x1050 410x260mm 19.1-inch               | 1         | 0.28%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 600x340mm 27.2-inch             | 1         | 0.28%   |
| ViewSonic LCD Monitor VSCBD2B 1920x1080 480x270mm 21.7-inch           | 1         | 0.28%   |
| ViewSonic LCD Monitor VSC6332 1920x1080 510x290mm 23.1-inch           | 1         | 0.28%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                       | 1         | 0.28%   |
| Sony TV SNYEE01 1920x1080                                             | 1         | 0.28%   |
| Sony TV SNY9C01 1360x768                                              | 1         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 118       | 33.62%  |
| 1366x768 (WXGA)    | 94        | 26.78%  |
| 1280x800 (WXGA)    | 23        | 6.55%   |
| 2560x1440 (QHD)    | 18        | 5.13%   |
| 1600x900 (HD+)     | 18        | 5.13%   |
| 1280x1024 (SXGA)   | 17        | 4.84%   |
| 1440x900 (WXGA+)   | 12        | 3.42%   |
| 3840x2160 (4K)     | 11        | 3.13%   |
| 1680x1050 (WSXGA+) | 11        | 3.13%   |
| 1920x1200 (WUXGA)  | 9         | 2.56%   |
| 1024x768 (XGA)     | 5         | 1.42%   |
| 2560x1080          | 4         | 1.14%   |
| 1920x540           | 3         | 0.85%   |
| 3440x1440          | 2         | 0.57%   |
| 1360x768           | 2         | 0.57%   |
| 1024x600           | 2         | 0.57%   |
| 3200x1800 (QHD+)   | 1         | 0.28%   |
| 1600x1200          | 1         | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 73        | 20.33%  |
| 13      | 53        | 14.76%  |
| 24      | 33        | 9.19%   |
| 27      | 27        | 7.52%   |
| 23      | 21        | 5.85%   |
| 19      | 21        | 5.85%   |
| 17      | 21        | 5.85%   |
| 21      | 20        | 5.57%   |
| 12      | 16        | 4.46%   |
| 18      | 10        | 2.79%   |
| 14      | 10        | 2.79%   |
| 20      | 9         | 2.51%   |
| 31      | 8         | 2.23%   |
| 11      | 7         | 1.95%   |
| Unknown | 7         | 1.95%   |
| 34      | 4         | 1.11%   |
| 22      | 3         | 0.84%   |
| 10      | 3         | 0.84%   |
| 42      | 2         | 0.56%   |
| 29      | 2         | 0.56%   |
| 16      | 2         | 0.56%   |
| 64      | 1         | 0.28%   |
| 54      | 1         | 0.28%   |
| 50      | 1         | 0.28%   |
| 40      | 1         | 0.28%   |
| 36      | 1         | 0.28%   |
| 33      | 1         | 0.28%   |
| 28      | 1         | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 117       | 33.05%  |
| 501-600     | 76        | 21.47%  |
| 201-300     | 54        | 15.25%  |
| 401-500     | 51        | 14.41%  |
| 351-400     | 24        | 6.78%   |
| 601-700     | 13        | 3.67%   |
| Unknown     | 7         | 1.98%   |
| 701-800     | 6         | 1.69%   |
| 1001-1500   | 3         | 0.85%   |
| 901-1000    | 2         | 0.56%   |
| 801-900     | 1         | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 253       | 74.41%  |
| 16/10   | 53        | 15.59%  |
| 5/4     | 15        | 4.41%   |
| 4/3     | 6         | 1.76%   |
| 3/2     | 6         | 1.76%   |
| 21/9    | 6         | 1.76%   |
| Unknown | 1         | 0.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 63        | 17.6%   |
| 91-100         | 60        | 16.76%  |
| 81-90          | 54        | 15.08%  |
| 151-200        | 35        | 9.78%   |
| 301-350        | 28        | 7.82%   |
| 61-70          | 17        | 4.75%   |
| 141-150        | 15        | 4.19%   |
| 101-110        | 15        | 4.19%   |
| 351-500        | 14        | 3.91%   |
| 251-300        | 12        | 3.35%   |
| 121-130        | 11        | 3.07%   |
| 71-80          | 7         | 1.96%   |
| Unknown        | 7         | 1.96%   |
| 51-60          | 6         | 1.68%   |
| 501-1000       | 4         | 1.12%   |
| More than 1000 | 3         | 0.84%   |
| 41-50          | 3         | 0.84%   |
| 131-140        | 3         | 0.84%   |
| 111-120        | 1         | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 137       | 38.59%  |
| 101-120       | 124       | 34.93%  |
| 121-160       | 77        | 21.69%  |
| 161-240       | 7         | 1.97%   |
| Unknown       | 7         | 1.97%   |
| 1-50          | 2         | 0.56%   |
| More than 240 | 1         | 0.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 316       | 85.41%  |
| 2     | 30        | 8.11%   |
| 0     | 23        | 6.22%   |
| 3     | 1         | 0.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 182       | 33.64%  |
| Intel                             | 178       | 32.9%   |
| Qualcomm Atheros                  | 58        | 10.72%  |
| Broadcom                          | 50        | 9.24%   |
| Nvidia                            | 14        | 2.59%   |
| Marvell Technology Group          | 14        | 2.59%   |
| Ralink                            | 6         | 1.11%   |
| Xiaomi                            | 4         | 0.74%   |
| Ralink Technology                 | 4         | 0.74%   |
| NetGear                           | 3         | 0.55%   |
| JMicron Technology                | 3         | 0.55%   |
| Edimax Technology                 | 3         | 0.55%   |
| TP-Link                           | 2         | 0.37%   |
| Sierra Wireless                   | 2         | 0.37%   |
| Ericsson Business Mobile Networks | 2         | 0.37%   |
| Dell                              | 2         | 0.37%   |
| D-Link System                     | 2         | 0.37%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.18%   |
| Samsung Electronics               | 1         | 0.18%   |
| OPPO Electronics                  | 1         | 0.18%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.18%   |
| Napatech A/S                      | 1         | 0.18%   |
| Microchip Technology              | 1         | 0.18%   |
| Mercucys                          | 1         | 0.18%   |
| Mellanox Technologies             | 1         | 0.18%   |
| MediaTek                          | 1         | 0.18%   |
| Huawei Technologies               | 1         | 0.18%   |
| Hewlett-Packard                   | 1         | 0.18%   |
| Google                            | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 140       | 21.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 3.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20        | 3.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 15        | 2.29%   |
| Nvidia MCP79 Ethernet                                             | 14        | 2.13%   |
| Intel I211 Gigabit Network Connection                             | 13        | 1.98%   |
| Intel Ethernet Connection I217-LM                                 | 13        | 1.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 13        | 1.98%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 13        | 1.98%   |
| Intel Wireless 8260                                               | 11        | 1.68%   |
| Intel Wireless 7260                                               | 11        | 1.68%   |
| Intel Wi-Fi 6 AX200                                               | 11        | 1.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 11        | 1.68%   |
| Intel Wireless 7265                                               | 9         | 1.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 1.22%   |
| Intel Wireless 8265 / 8275                                        | 8         | 1.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 7         | 1.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.07%   |
| Intel Centrino Advanced-N 6200                                    | 7         | 1.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 0.91%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 6         | 0.91%   |
| Intel Ethernet Connection (7) I219-V                              | 6         | 0.91%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 0.91%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 6         | 0.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 0.76%   |
| Intel WiFi Link 5100                                              | 5         | 0.76%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 5         | 0.76%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 0.76%   |
| Intel 82566MM Gigabit Network Connection                          | 5         | 0.76%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 4         | 0.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 0.61%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 0.61%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 4         | 0.61%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.61%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.61%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 4         | 0.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 127       | 46.35%  |
| Qualcomm Atheros      | 46        | 16.79%  |
| Realtek Semiconductor | 44        | 16.06%  |
| Broadcom              | 35        | 12.77%  |
| Ralink                | 6         | 2.19%   |
| Ralink Technology     | 4         | 1.46%   |
| NetGear               | 3         | 1.09%   |
| Edimax Technology     | 3         | 1.09%   |
| TP-Link               | 2         | 0.73%   |
| Sierra Wireless       | 1         | 0.36%   |
| Mercucys              | 1         | 0.36%   |
| MediaTek              | 1         | 0.36%   |
| Dell                  | 1         | 0.36%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 15        | 5.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 13        | 4.64%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 13        | 4.64%   |
| Intel Wireless 8260                                            | 11        | 3.93%   |
| Intel Wireless 7260                                            | 11        | 3.93%   |
| Intel Wi-Fi 6 AX200                                            | 11        | 3.93%   |
| Intel Wireless 7265                                            | 9         | 3.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 8         | 2.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 8         | 2.86%   |
| Intel Wireless 8265 / 8275                                     | 8         | 2.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 7         | 2.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 2.5%    |
| Intel Centrino Advanced-N 6200                                 | 7         | 2.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 2.14%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 6         | 2.14%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 6         | 2.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.79%   |
| Intel WiFi Link 5100                                           | 5         | 1.79%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 5         | 1.79%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 4         | 1.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 1.43%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 1.43%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 1.43%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 4         | 1.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 1.43%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 4         | 1.43%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 1.07%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 1.07%   |
| Realtek Realtek Bluetooth 4.2 Adapter                          | 3         | 1.07%   |
| Ralink RT5370 Wireless Adapter                                 | 3         | 1.07%   |
| Intel Wireless-AC 9260                                         | 3         | 1.07%   |
| Intel Wireless 3165                                            | 3         | 1.07%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.07%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 1.07%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.07%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 2         | 0.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.71%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.71%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 167       | 45.88%  |
| Intel                            | 121       | 33.24%  |
| Qualcomm Atheros                 | 18        | 4.95%   |
| Broadcom                         | 17        | 4.67%   |
| Nvidia                           | 14        | 3.85%   |
| Marvell Technology Group         | 14        | 3.85%   |
| Xiaomi                           | 4         | 1.1%    |
| JMicron Technology               | 3         | 0.82%   |
| Silicon Integrated Systems [SiS] | 1         | 0.27%   |
| Samsung Electronics              | 1         | 0.27%   |
| OPPO Electronics                 | 1         | 0.27%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.27%   |
| Google                           | 1         | 0.27%   |
| D-Link System                    | 1         | 0.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 140       | 38.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 6.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20        | 5.46%   |
| Nvidia MCP79 Ethernet                                             | 14        | 3.83%   |
| Intel I211 Gigabit Network Connection                             | 13        | 3.55%   |
| Intel Ethernet Connection I217-LM                                 | 13        | 3.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 11        | 3.01%   |
| Intel Ethernet Connection (7) I219-V                              | 6         | 1.64%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 1.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 1.37%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 1.37%   |
| Intel 82566MM Gigabit Network Connection                          | 5         | 1.37%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 4         | 1.09%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 1.09%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.09%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.09%   |
| Intel 82574L Gigabit Network Connection                           | 4         | 1.09%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.82%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.82%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 0.82%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.82%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 0.82%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.55%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2         | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.55%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 0.55%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2         | 0.55%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.55%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.55%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.55%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.55%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 0.55%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2         | 0.55%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.55%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 0.55%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.27%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.27%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 352       | 57.14%  |
| WiFi     | 254       | 41.23%  |
| Unknown  | 6         | 0.97%   |
| Modem    | 4         | 0.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 289       | 64.37%  |
| WiFi     | 156       | 34.74%  |
| Unknown  | 3         | 0.67%   |
| Modem    | 1         | 0.22%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 226       | 61.41%  |
| 1     | 128       | 34.78%  |
| 3     | 8         | 2.17%   |
| 4     | 3         | 0.82%   |
| 0     | 3         | 0.82%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 353       | 94.89%  |
| Yes  | 19        | 5.11%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 74        | 39.36%  |
| Apple                           | 22        | 11.7%   |
| Broadcom                        | 17        | 9.04%   |
| Realtek Semiconductor           | 16        | 8.51%   |
| Qualcomm Atheros Communications | 13        | 6.91%   |
| Cambridge Silicon Radio         | 12        | 6.38%   |
| Lite-On Technology              | 7         | 3.72%   |
| IMC Networks                    | 5         | 2.66%   |
| Foxconn / Hon Hai               | 5         | 2.66%   |
| Ralink                          | 4         | 2.13%   |
| Hewlett-Packard                 | 4         | 2.13%   |
| Dell                            | 3         | 1.6%    |
| Integrated System Solution      | 2         | 1.06%   |
| ASUSTek Computer                | 2         | 1.06%   |
| TP-Link                         | 1         | 0.53%   |
| HTC (High Tech Computer)        | 1         | 0.53%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 38        | 20%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 12        | 6.32%   |
| Intel AX200 Bluetooth                                       | 11        | 5.79%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 8         | 4.21%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 8         | 4.21%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 7         | 3.68%   |
| Intel AX201 Bluetooth                                       | 7         | 3.68%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 6         | 3.16%   |
| Apple Bluetooth Host Controller                             | 6         | 3.16%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 5         | 2.63%   |
| Realtek  Bluetooth 4.2 Adapter                              | 4         | 2.11%   |
| Realtek  Bluetooth 4.0 Adapter                              | 4         | 2.11%   |
| Ralink RT3290 Bluetooth                                     | 4         | 2.11%   |
| Lite-On Atheros AR3012 Bluetooth                            | 4         | 2.11%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 4         | 2.11%   |
| Apple Built-in iSight (no firmware loaded)                  | 4         | 2.11%   |
| Realtek  Bluetooth Adapter                                  | 3         | 1.58%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 3         | 1.58%   |
| Intel Wireless-AC 3168 Bluetooth                            | 3         | 1.58%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 3         | 1.58%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 1.05%   |
| Realtek Bluetooth Radio                                     | 2         | 1.05%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 1.05%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 1.05%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 2         | 1.05%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 2         | 1.05%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 1.05%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 1.05%   |
| TP-Link TP-Link UB500 Adapter                               | 1         | 0.53%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.53%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 1         | 0.53%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.53%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 0.53%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 0.53%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.53%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.53%   |
| Lite-On Realtek Bluetooth Adapter                           | 1         | 0.53%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.53%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 1         | 0.53%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter       | 1         | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 272       | 54.84%  |
| AMD                              | 93        | 18.75%  |
| Nvidia                           | 88        | 17.74%  |
| C-Media Electronics              | 7         | 1.41%   |
| GN Netcom                        | 6         | 1.21%   |
| Texas Instruments                | 4         | 0.81%   |
| Logitech                         | 3         | 0.6%    |
| SteelSeries ApS                  | 2         | 0.4%    |
| JMTek                            | 2         | 0.4%    |
| Focusrite-Novation               | 2         | 0.4%    |
| Yamaha                           | 1         | 0.2%    |
| VIA Technologies                 | 1         | 0.2%    |
| Silicon Integrated Systems [SiS] | 1         | 0.2%    |
| Nektar                           | 1         | 0.2%    |
| Lenovo                           | 1         | 0.2%    |
| KORG                             | 1         | 0.2%    |
| Kingston Technology              | 1         | 0.2%    |
| Generalplus Technology           | 1         | 0.2%    |
| FiiO Electronics Technology      | 1         | 0.2%    |
| DSEA A/S                         | 1         | 0.2%    |
| Creative Technology              | 1         | 0.2%    |
| Creative Labs                    | 1         | 0.2%    |
| Corsair                          | 1         | 0.2%    |
| Cambridge Silicon Radio          | 1         | 0.2%    |
| BEHRINGER International          | 1         | 0.2%    |
| ASUSTek Computer                 | 1         | 0.2%    |
| Astro Gaming                     | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 38        | 6.54%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 24        | 4.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 24        | 4.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 21        | 3.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 21        | 3.61%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 21        | 3.61%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 18        | 3.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 18        | 3.1%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 17        | 2.93%   |
| Intel Cannon Lake PCH cAVS                                                                        | 15        | 2.58%   |
| AMD FCH Azalia Controller                                                                         | 15        | 2.58%   |
| Nvidia MCP79 High Definition Audio                                                                | 14        | 2.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 14        | 2.41%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 14        | 2.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 13        | 2.24%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 2.07%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 2.07%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 2.07%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 9         | 1.55%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 8         | 1.38%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 7         | 1.2%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 1.2%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 7         | 1.2%    |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.2%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 7         | 1.2%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 1.2%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 1.03%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.03%   |
| Intel 200 Series PCH HD Audio                                                                     | 6         | 1.03%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 6         | 1.03%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 0.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 0.86%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 0.69%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.69%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 4         | 0.69%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.69%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 0.69%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 77        | 18.42%  |
| Kingston            | 70        | 16.75%  |
| SK hynix            | 53        | 12.68%  |
| Unknown             | 43        | 10.29%  |
| Micron Technology   | 34        | 8.13%   |
| Crucial             | 20        | 4.78%   |
| Corsair             | 17        | 4.07%   |
| Unknown             | 14        | 3.35%   |
| G.Skill             | 13        | 3.11%   |
| Nanya Technology    | 10        | 2.39%   |
| Ramaxel Technology  | 8         | 1.91%   |
| A-DATA Technology   | 8         | 1.91%   |
| Elpida              | 7         | 1.67%   |
| Team                | 6         | 1.44%   |
| Smart               | 4         | 0.96%   |
| Transcend           | 3         | 0.72%   |
| Patriot             | 3         | 0.72%   |
| Silicon Power       | 2         | 0.48%   |
| Goodram             | 2         | 0.48%   |
| Avant               | 2         | 0.48%   |
| ASint Technology    | 2         | 0.48%   |
| AMD                 | 2         | 0.48%   |
| 48spaces            | 2         | 0.48%   |
| Unknown (D386)      | 1         | 0.24%   |
| Unknown (ABCD)      | 1         | 0.24%   |
| Unknown (0x0809)    | 1         | 0.24%   |
| Unifosa             | 1         | 0.24%   |
| TakeMS              | 1         | 0.24%   |
| Super Talent        | 1         | 0.24%   |
| Strontium           | 1         | 0.24%   |
| Smart Brazil        | 1         | 0.24%   |
| Sesame              | 1         | 0.24%   |
| PNY                 | 1         | 0.24%   |
| Kingmax             | 1         | 0.24%   |
| Hikvision           | 1         | 0.24%   |
| High Bridge         | 1         | 0.24%   |
| Goldkey             | 1         | 0.24%   |
| Atermiter           | 1         | 0.24%   |
| Apacer              | 1         | 0.24%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown                                                    | 14        | 3.07%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                 | 7         | 1.54%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 5         | 1.1%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s      | 5         | 1.1%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                 | 4         | 0.88%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s        | 4         | 0.88%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 4         | 0.88%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s      | 4         | 0.88%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s      | 4         | 0.88%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 4         | 0.88%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 4         | 0.88%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s       | 4         | 0.88%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s               | 3         | 0.66%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s      | 3         | 0.66%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 3         | 0.66%   |
| Samsung RAM Module 4GB SODIMM DDR4 2133MT/s                | 3         | 0.66%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s      | 3         | 0.66%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s      | 3         | 0.66%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s      | 3         | 0.66%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s      | 3         | 0.66%   |
| Micron RAM 18KSF51272AZ-1G4M1 4GB DIMM DDR3 1333MT/s       | 3         | 0.66%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s     | 3         | 0.66%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s    | 3         | 0.66%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                | 2         | 0.44%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                  | 2         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2                         | 2         | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR2                           | 2         | 0.44%   |
| Unknown RAM Module 2GB DIMM 400MT/s                        | 2         | 0.44%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                       | 2         | 0.44%   |
| Unknown RAM Module 1GB DIMM SDRAM                          | 2         | 0.44%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 800MT/s      | 2         | 0.44%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 2         | 0.44%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                | 2         | 0.44%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s      | 2         | 0.44%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s      | 2         | 0.44%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s     | 2         | 0.44%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 2         | 0.44%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s        | 2         | 0.44%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s    | 2         | 0.44%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s | 2         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 173       | 48.19%  |
| DDR4    | 122       | 33.98%  |
| DDR2    | 38        | 10.58%  |
| Unknown | 13        | 3.62%   |
| SDRAM   | 6         | 1.67%   |
| LPDDR4  | 2         | 0.56%   |
| LPDDR3  | 2         | 0.56%   |
| DDR     | 2         | 0.56%   |
| DRAM    | 1         | 0.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 213       | 59.5%   |
| DIMM         | 142       | 39.66%  |
| Row Of Chips | 2         | 0.56%   |
| Chip         | 1         | 0.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 127       | 31.91%  |
| 8192  | 112       | 28.14%  |
| 2048  | 91        | 22.86%  |
| 16384 | 41        | 10.3%   |
| 1024  | 22        | 5.53%   |
| 32768 | 4         | 1.01%   |
| 512   | 1         | 0.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 96        | 24.49%  |
| 1333    | 48        | 12.24%  |
| 2667    | 33        | 8.42%   |
| 2133    | 31        | 7.91%   |
| 3200    | 30        | 7.65%   |
| 2400    | 27        | 6.89%   |
| 667     | 24        | 6.12%   |
| 1067    | 22        | 5.61%   |
| 800     | 16        | 4.08%   |
| 1334    | 15        | 3.83%   |
| Unknown | 12        | 3.06%   |
| 1867    | 8         | 2.04%   |
| 2666    | 7         | 1.79%   |
| 1066    | 5         | 1.28%   |
| 3600    | 4         | 1.02%   |
| 975     | 3         | 0.77%   |
| 533     | 2         | 0.51%   |
| 400     | 2         | 0.51%   |
| 333     | 2         | 0.51%   |
| 3733    | 1         | 0.26%   |
| 3400    | 1         | 0.26%   |
| 2933    | 1         | 0.26%   |
| 1866    | 1         | 0.26%   |
| 1200    | 1         | 0.26%   |

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
| Chicony Electronics                    | 40        | 26.14%  |
| Realtek Semiconductor                  | 13        | 8.5%    |
| Microdia                               | 12        | 7.84%   |
| Acer                                   | 11        | 7.19%   |
| IMC Networks                           | 10        | 6.54%   |
| Logitech                               | 9         | 5.88%   |
| Quanta                                 | 8         | 5.23%   |
| Sunplus Innovation Technology          | 7         | 4.58%   |
| Lite-On Technology                     | 7         | 4.58%   |
| Syntek                                 | 6         | 3.92%   |
| Suyin                                  | 4         | 2.61%   |
| Z-Star Microelectronics                | 3         | 1.96%   |
| Lenovo                                 | 3         | 1.96%   |
| Alcor Micro                            | 3         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.31%   |
| Apple                                  | 2         | 1.31%   |
| ALi                                    | 2         | 1.31%   |
| Silicon Motion                         | 1         | 0.65%   |
| Ricoh                                  | 1         | 0.65%   |
| Primax Electronics                     | 1         | 0.65%   |
| Luxvisions Innotech Limited            | 1         | 0.65%   |
| Importek                               | 1         | 0.65%   |
| Hewlett-Packard                        | 1         | 0.65%   |
| Genesys Logic                          | 1         | 0.65%   |
| DigiTech                               | 1         | 0.65%   |
| Aveo Technology                        | 1         | 0.65%   |
| Arkmicro Technologies                  | 1         | 0.65%   |
| ARC International                      | 1         | 0.65%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Chicony HD WebCam                         | 6         | 3.9%    |
| Chicony Lenovo Integrated Camera (0.3MP)  | 5         | 3.25%   |
| Realtek Integrated_Webcam_HD              | 4         | 2.6%    |
| Lite-On Integrated Camera                 | 4         | 2.6%    |
| Chicony Integrated Camera                 | 4         | 2.6%    |
| Syntek Lenovo EasyCamera                  | 3         | 1.95%   |
| Realtek USB Camera                        | 3         | 1.95%   |
| Realtek Realtek USB2.0 PC Camera          | 3         | 1.95%   |
| Microdia Integrated Webcam                | 3         | 1.95%   |
| IMC Networks Integrated Camera            | 3         | 1.95%   |
| Chicony HD WebCam (Acer)                  | 3         | 1.95%   |
| Chicony EasyCamera                        | 3         | 1.95%   |
| Syntek EasyCamera                         | 2         | 1.3%    |
| Suyin HD Video WebCam                     | 2         | 1.3%    |
| Sunplus HD WebCam                         | 2         | 1.3%    |
| Quanta Realtek DMFT - RGB                 | 2         | 1.3%    |
| Quanta HP Webcam                          | 2         | 1.3%    |
| Quanta HP TrueVision HD Camera            | 2         | 1.3%    |
| Microdia Sonix USB 2.0 Camera             | 2         | 1.3%    |
| Microdia Integrated_Webcam_HD             | 2         | 1.3%    |
| Microdia Dell Laptop Integrated Webcam HD | 2         | 1.3%    |
| Logitech Webcam C270                      | 2         | 1.3%    |
| Lite-On HP HD Camera                      | 2         | 1.3%    |
| Lenovo Integrated Webcam [R5U877]         | 2         | 1.3%    |
| IMC Networks USB2.0 HD UVC WebCam         | 2         | 1.3%    |
| Chicony HP HD Webcam [Fixed]              | 2         | 1.3%    |
| Chicony Chicony USB 2.0 Camera            | 2         | 1.3%    |
| Apple FaceTime HD Camera (Built-in)       | 2         | 1.3%    |
| ALi Gateway Webcam                        | 2         | 1.3%    |
| Acer SunplusIT INC. Integrated Camera     | 2         | 1.3%    |
| Acer Lenovo EasyCamera                    | 2         | 1.3%    |
| Acer Integrated Camera                    | 2         | 1.3%    |
| Z-Star WebCam SC-03FFL11739P              | 1         | 0.65%   |
| Z-Star Webcam                             | 1         | 0.65%   |
| Z-Star Lenovo USB2.0 UVC Camera           | 1         | 0.65%   |
| Syntek ASUS USB2.0 camera                 | 1         | 0.65%   |
| Suyin Laptop_Integrated_Webcam_FHD        | 1         | 0.65%   |
| Suyin Integrated_Webcam_HD                | 1         | 0.65%   |
| Sunplus Laptop_Integrated_Webcam_FHD      | 1         | 0.65%   |
| Sunplus Integrated_Webcam_HD              | 1         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 15        | 35.71%  |
| Upek                       | 11        | 26.19%  |
| AuthenTec                  | 7         | 16.67%  |
| STMicroelectronics         | 4         | 9.52%   |
| Shenzhen Goodix Technology | 2         | 4.76%   |
| LighTuning Technology      | 2         | 4.76%   |
| Synaptics                  | 1         | 2.38%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 9         | 21.43%  |
| STMicroelectronics Fingerprint Reader                  | 4         | 9.52%   |
| Validity Sensors VFS491                                | 3         | 7.14%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 4.76%   |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 4.76%   |
| Validity Sensors VFS471 Fingerprint Reader             | 2         | 4.76%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 4.76%   |
| Validity Sensors Synaptics WBDI                        | 2         | 4.76%   |
| Upek TCS5B Fingerprint sensor                          | 2         | 4.76%   |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 4.76%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 4.76%   |
| AuthenTec AES1600                                      | 2         | 4.76%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 2.38%   |
| Validity Sensors Fingerprint scanner                   | 1         | 2.38%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 2.38%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 2.38%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 2.38%   |
| AuthenTec AuthenTec Inc. AES1660                       | 1         | 2.38%   |
| AuthenTec AES2810                                      | 1         | 2.38%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 2.38%   |

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
| 1     | 139       | 37.47%  |
| 0     | 104       | 28.03%  |
| 2     | 88        | 23.72%  |
| 3     | 29        | 7.82%   |
| 4     | 11        | 2.96%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 211       | 50.97%  |
| Net/wireless             | 73        | 17.63%  |
| Bluetooth                | 41        | 9.9%    |
| Fingerprint reader       | 40        | 9.66%   |
| Card reader              | 30        | 7.25%   |
| Sound                    | 8         | 1.93%   |
| Network                  | 5         | 1.21%   |
| Storage                  | 3         | 0.72%   |
| Storage/nvme             | 1         | 0.24%   |
| Net/ethernet             | 1         | 0.24%   |
| Dvb card                 | 1         | 0.24%   |

