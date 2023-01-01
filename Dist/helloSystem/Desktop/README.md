helloSystem - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for helloSystem.

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

Total: 616

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Gigabyte      | X399 AORUS Gaming 7         | [1769da5143](https://bsd-hardware.info/?probe=1769da5143) | Dec 25, 2022 |
| Dell          | 0UW457 A03                  | [47b66a0d86](https://bsd-hardware.info/?probe=47b66a0d86) | Dec 21, 2022 |
| Gigabyte      | H81M-DS2                    | [29ad5ee336](https://bsd-hardware.info/?probe=29ad5ee336) | Dec 19, 2022 |
| Apple         | Mac-F221BEC8                | [bc15367e9f](https://bsd-hardware.info/?probe=bc15367e9f) | Dec 14, 2022 |
| HP            | 3397                        | [bc9e5c3ab7](https://bsd-hardware.info/?probe=bc9e5c3ab7) | Dec 09, 2022 |
| Pegatron      | 2A72h                       | [87e76fd095](https://bsd-hardware.info/?probe=87e76fd095) | Dec 09, 2022 |
| ASUSTek       | CM1530                      | [902c77b5dc](https://bsd-hardware.info/?probe=902c77b5dc) | Dec 06, 2022 |
| Dell          | 0WMJ54 A01                  | [5441995e7b](https://bsd-hardware.info/?probe=5441995e7b) | Dec 05, 2022 |
| Gigabyte      | M68MT-S2P                   | [2fe00838c3](https://bsd-hardware.info/?probe=2fe00838c3) | Dec 05, 2022 |
| Gigabyte      | M68MT-S2P                   | [71f95dafb4](https://bsd-hardware.info/?probe=71f95dafb4) | Dec 05, 2022 |
| Intel         | X99                         | [c21a466fc1](https://bsd-hardware.info/?probe=c21a466fc1) | Dec 01, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [43163b0170](https://bsd-hardware.info/?probe=43163b0170) | Nov 28, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [d00aa0021e](https://bsd-hardware.info/?probe=d00aa0021e) | Nov 28, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | [7329e04c22](https://bsd-hardware.info/?probe=7329e04c22) | Nov 27, 2022 |
| Dell          | 09M8Y8 A02                  | [2299b7c270](https://bsd-hardware.info/?probe=2299b7c270) | Nov 27, 2022 |
| ASRock        | N68-S                       | [3813c8856e](https://bsd-hardware.info/?probe=3813c8856e) | Nov 27, 2022 |
| Dell          | 0M017G A00                  | [3acaad9a7d](https://bsd-hardware.info/?probe=3acaad9a7d) | Nov 26, 2022 |
| HP            | 3048h                       | [3f43816a5d](https://bsd-hardware.info/?probe=3f43816a5d) | Nov 25, 2022 |
| Lenovo        | ThinkStation S30 0569A93    | [dd545fb588](https://bsd-hardware.info/?probe=dd545fb588) | Nov 25, 2022 |
| Pegatron      | IPM41-D3                    | [898f645e32](https://bsd-hardware.info/?probe=898f645e32) | Nov 25, 2022 |
| MSI           | Z170A GAMING M5             | [5740972ddc](https://bsd-hardware.info/?probe=5740972ddc) | Nov 25, 2022 |
| MSI           | A320M-A PRO                 | [fc71b97d90](https://bsd-hardware.info/?probe=fc71b97d90) | Nov 24, 2022 |
| Gigabyte      | E2500N                      | [64b937b551](https://bsd-hardware.info/?probe=64b937b551) | Nov 23, 2022 |
| Gigabyte      | G31M-S2L                    | [d376385d80](https://bsd-hardware.info/?probe=d376385d80) | Nov 23, 2022 |
| ASUSTek       | A55BM-K                     | [dc487b5779](https://bsd-hardware.info/?probe=dc487b5779) | Nov 23, 2022 |
| ASUSTek       | PRIME A320M-K               | [9701222998](https://bsd-hardware.info/?probe=9701222998) | Nov 23, 2022 |
| Intel         | H61                         | [689ebf0e57](https://bsd-hardware.info/?probe=689ebf0e57) | Nov 22, 2022 |
| Gigabyte      | P61-USB3-B3                 | [1ec1683acd](https://bsd-hardware.info/?probe=1ec1683acd) | Nov 21, 2022 |
| Gigabyte      | P61-USB3-B3                 | [5f442f0c65](https://bsd-hardware.info/?probe=5f442f0c65) | Nov 21, 2022 |
| Gigabyte      | H61M-S1                     | [2b851dbbc1](https://bsd-hardware.info/?probe=2b851dbbc1) | Nov 21, 2022 |
| Gigabyte      | 970A-D3P                    | [cced487ec5](https://bsd-hardware.info/?probe=cced487ec5) | Nov 21, 2022 |
| Gigabyte      | 970A-D3P                    | [c28a22ecb5](https://bsd-hardware.info/?probe=c28a22ecb5) | Nov 21, 2022 |
| ASUSTek       | P5KPL-VM-TWPC               | [6a5ff282a7](https://bsd-hardware.info/?probe=6a5ff282a7) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [92eab8d065](https://bsd-hardware.info/?probe=92eab8d065) | Nov 19, 2022 |
| HP            | 1998                        | [9239fe7437](https://bsd-hardware.info/?probe=9239fe7437) | Nov 15, 2022 |
| ASUSTek       | P5E-VM SE                   | [910dc6412e](https://bsd-hardware.info/?probe=910dc6412e) | Nov 10, 2022 |
| MSI           | Z370I GAMING PRO CARBON ... | [dd9f7679b5](https://bsd-hardware.info/?probe=dd9f7679b5) | Nov 09, 2022 |
| Dell          | 0F428D A00                  | [0a9ca655d3](https://bsd-hardware.info/?probe=0a9ca655d3) | Nov 08, 2022 |
| ASUSTek       | Z97-A                       | [6a2b1c8105](https://bsd-hardware.info/?probe=6a2b1c8105) | Nov 05, 2022 |
| Gigabyte      | H270M-DS3H-CF               | [5784d8bed6](https://bsd-hardware.info/?probe=5784d8bed6) | Nov 04, 2022 |
| HP            | 8053                        | [92583639f6](https://bsd-hardware.info/?probe=92583639f6) | Nov 02, 2022 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | [d20bfb6d64](https://bsd-hardware.info/?probe=d20bfb6d64) | Oct 30, 2022 |
| HP            | 843B                        | [d7d572f9ad](https://bsd-hardware.info/?probe=d7d572f9ad) | Oct 29, 2022 |
| HP            | 843B                        | [9ea2590610](https://bsd-hardware.info/?probe=9ea2590610) | Oct 23, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [54e4202bc7](https://bsd-hardware.info/?probe=54e4202bc7) | Oct 21, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [c6ee09790d](https://bsd-hardware.info/?probe=c6ee09790d) | Oct 20, 2022 |
| ASUSTek       | N3050I-C                    | [4a83b0953e](https://bsd-hardware.info/?probe=4a83b0953e) | Oct 18, 2022 |
| HP            | 8169                        | [86b1fbf917](https://bsd-hardware.info/?probe=86b1fbf917) | Oct 15, 2022 |
| Lenovo        | ThinkCentre M57p 6078AJ6    | [a808a7360d](https://bsd-hardware.info/?probe=a808a7360d) | Oct 14, 2022 |
| ASUSTek       | H110M-PLUS                  | [ba30f2772b](https://bsd-hardware.info/?probe=ba30f2772b) | Oct 12, 2022 |
| HP            | 86FC MVB                    | [56453b00c8](https://bsd-hardware.info/?probe=56453b00c8) | Oct 08, 2022 |
| HP            | 86FC MVB                    | [c542b16d75](https://bsd-hardware.info/?probe=c542b16d75) | Oct 08, 2022 |
| Dell          | 0T10XW A01                  | [c2ff0bc0b9](https://bsd-hardware.info/?probe=c2ff0bc0b9) | Sep 30, 2022 |
| ASRock        | A320M-HD                    | [6418fd0b23](https://bsd-hardware.info/?probe=6418fd0b23) | Sep 28, 2022 |
| Apple         | Mac-7BA5B2D9E42DDD94        | [d2e169b8ad](https://bsd-hardware.info/?probe=d2e169b8ad) | Sep 13, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | [7c9c1db9d7](https://bsd-hardware.info/?probe=7c9c1db9d7) | Sep 10, 2022 |
| Pegatron      | IPM41-D3                    | [2d3a5a5260](https://bsd-hardware.info/?probe=2d3a5a5260) | Sep 06, 2022 |
| Dell          | 0Y7WYT A00                  | [2870b9e4c7](https://bsd-hardware.info/?probe=2870b9e4c7) | Sep 05, 2022 |
| HP            | 8719                        | [f3132fc160](https://bsd-hardware.info/?probe=f3132fc160) | Sep 05, 2022 |
| ASUSTek       | H81M-A                      | [11ac5a7932](https://bsd-hardware.info/?probe=11ac5a7932) | Sep 02, 2022 |
| ASRock        | ConRoeXFire-eSATA2          | [caf005ed95](https://bsd-hardware.info/?probe=caf005ed95) | Sep 01, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [079adb24f8](https://bsd-hardware.info/?probe=079adb24f8) | Aug 28, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [17f4ac1979](https://bsd-hardware.info/?probe=17f4ac1979) | Aug 23, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [5ea9441653](https://bsd-hardware.info/?probe=5ea9441653) | Aug 19, 2022 |
| Lenovo        | SDK0E50510 WIN              | [a45977c76b](https://bsd-hardware.info/?probe=a45977c76b) | Aug 10, 2022 |
| ASRock        | Z370 Pro4                   | [038c5f8763](https://bsd-hardware.info/?probe=038c5f8763) | Aug 10, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | [50a0d392e7](https://bsd-hardware.info/?probe=50a0d392e7) | Aug 06, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [af241a5384](https://bsd-hardware.info/?probe=af241a5384) | Aug 06, 2022 |
| ASUSTek       | K30AM-J                     | [470ced8f30](https://bsd-hardware.info/?probe=470ced8f30) | Aug 05, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | [d61693dffb](https://bsd-hardware.info/?probe=d61693dffb) | Aug 05, 2022 |
| ASUSTek       | K30AM-J                     | [e032724bc2](https://bsd-hardware.info/?probe=e032724bc2) | Aug 05, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [850198c512](https://bsd-hardware.info/?probe=850198c512) | Aug 05, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [cddf42b097](https://bsd-hardware.info/?probe=cddf42b097) | Aug 05, 2022 |
| HP            | 1497                        | [c6f6ddf728](https://bsd-hardware.info/?probe=c6f6ddf728) | Aug 04, 2022 |
| Gigabyte      | X570 AORUS PRO              | [ad56307789](https://bsd-hardware.info/?probe=ad56307789) | Aug 01, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [6d5bfb02a0](https://bsd-hardware.info/?probe=6d5bfb02a0) | Jul 28, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [f50526a6d6](https://bsd-hardware.info/?probe=f50526a6d6) | Jul 27, 2022 |
| MAXSUN        | MS-H110D4L FS M.2           | [39d06b12fd](https://bsd-hardware.info/?probe=39d06b12fd) | Jul 25, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [a96e41f99e](https://bsd-hardware.info/?probe=a96e41f99e) | Jul 20, 2022 |
| ASUSTek       | P8B WS                      | [dd7f8123d2](https://bsd-hardware.info/?probe=dd7f8123d2) | Jul 19, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [a80b1c4f3c](https://bsd-hardware.info/?probe=a80b1c4f3c) | Jul 17, 2022 |
| HP            | 8055                        | [269b4f3210](https://bsd-hardware.info/?probe=269b4f3210) | Jul 17, 2022 |
| Shuttle       | FH170                       | [a156048964](https://bsd-hardware.info/?probe=a156048964) | Jul 16, 2022 |
| Shuttle       | FH170                       | [81b62c2839](https://bsd-hardware.info/?probe=81b62c2839) | Jul 16, 2022 |
| HP            | 1998                        | [e4fda48283](https://bsd-hardware.info/?probe=e4fda48283) | Jul 15, 2022 |
| ASUSTek       | Maximus IX HERO             | [ea2f21a15f](https://bsd-hardware.info/?probe=ea2f21a15f) | Jul 12, 2022 |
| ASUSTek       | Maximus IX HERO             | [81668557c6](https://bsd-hardware.info/?probe=81668557c6) | Jul 08, 2022 |
| Pegatron      | IPM41-D3                    | [8b2af1b843](https://bsd-hardware.info/?probe=8b2af1b843) | Jul 06, 2022 |
| Lenovo        | NO DPK                      | [2c79a92fc4](https://bsd-hardware.info/?probe=2c79a92fc4) | Jul 06, 2022 |
| Pegatron      | IPM41-D3                    | [1cd93cd5d3](https://bsd-hardware.info/?probe=1cd93cd5d3) | Jul 04, 2022 |
| Biostar       | G41D3C                      | [118bd083bf](https://bsd-hardware.info/?probe=118bd083bf) | Jul 01, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [4d4993a732](https://bsd-hardware.info/?probe=4d4993a732) | Jun 24, 2022 |
| ALLEGIANCE... | X79 V3.3F                   | [190560a4f4](https://bsd-hardware.info/?probe=190560a4f4) | Jun 23, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | [346bc6f0ae](https://bsd-hardware.info/?probe=346bc6f0ae) | Jun 20, 2022 |
| Gigabyte      | GA-970A-UD3                 | [a094c1c53b](https://bsd-hardware.info/?probe=a094c1c53b) | Jun 20, 2022 |
| HP            | 304Bh                       | [8a3151b3cd](https://bsd-hardware.info/?probe=8a3151b3cd) | Jun 16, 2022 |
| Lenovo        | ThinkCentre XXXX Y          | [162bbe4eac](https://bsd-hardware.info/?probe=162bbe4eac) | Jun 10, 2022 |
| ASUSTek       | TUF B360M-E GAMING          | [26375bae48](https://bsd-hardware.info/?probe=26375bae48) | Jun 08, 2022 |
| Acer          | EM61SM/EM61PM               | [3b8d6cb36e](https://bsd-hardware.info/?probe=3b8d6cb36e) | Jun 07, 2022 |
| Positivo      | POS-PIQ77CL POSITIVO        | [848361c724](https://bsd-hardware.info/?probe=848361c724) | May 31, 2022 |
| Gigabyte      | F2A88XM-HD3                 | [c734325ede](https://bsd-hardware.info/?probe=c734325ede) | May 31, 2022 |
| Dell          | 048DY8 A00                  | [7d1c59b392](https://bsd-hardware.info/?probe=7d1c59b392) | May 29, 2022 |
| ASUSTek       | P5LD2                       | [64208afa2c](https://bsd-hardware.info/?probe=64208afa2c) | May 25, 2022 |
| T-bao         | MINI PC V1.0                | [a89b2081bb](https://bsd-hardware.info/?probe=a89b2081bb) | May 25, 2022 |
| Gigabyte      | B75M-D3H                    | [d0565222dc](https://bsd-hardware.info/?probe=d0565222dc) | May 24, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [ee8ba76de5](https://bsd-hardware.info/?probe=ee8ba76de5) | May 22, 2022 |
| ASUSTek       | P8Z77-V LX                  | [e7055d83e2](https://bsd-hardware.info/?probe=e7055d83e2) | May 20, 2022 |
| ASUSTek       | K30AM-J                     | [f4352f7897](https://bsd-hardware.info/?probe=f4352f7897) | May 16, 2022 |
| Dell          | 0G261D A00                  | [c0fafdb905](https://bsd-hardware.info/?probe=c0fafdb905) | May 14, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [d9c28e14df](https://bsd-hardware.info/?probe=d9c28e14df) | May 13, 2022 |
| ASUSTek       | PRIME X570-P                | [aad86a8b8e](https://bsd-hardware.info/?probe=aad86a8b8e) | May 10, 2022 |
| Lenovo        | MAHOBAY                     | [b54df77b59](https://bsd-hardware.info/?probe=b54df77b59) | May 07, 2022 |
| Gigabyte      | F2A68HM-H                   | [daed3f9401](https://bsd-hardware.info/?probe=daed3f9401) | May 06, 2022 |
| ASUSTek       | P8Z77-V LX                  | [bf3d4941a2](https://bsd-hardware.info/?probe=bf3d4941a2) | May 06, 2022 |
| Dell          | 0Y7WYT A00                  | [76674e4d62](https://bsd-hardware.info/?probe=76674e4d62) | May 06, 2022 |
| OEM           | B85 JHS359                  | [c5d29cc6b3](https://bsd-hardware.info/?probe=c5d29cc6b3) | May 03, 2022 |
| Gigabyte      | A320M-H-CF                  | [24d308754b](https://bsd-hardware.info/?probe=24d308754b) | May 02, 2022 |
| HP            | 0AA8h                       | [f9b906ea47](https://bsd-hardware.info/?probe=f9b906ea47) | Apr 30, 2022 |
| Supermicro    | X9DAL                       | [ef1f3da3ce](https://bsd-hardware.info/?probe=ef1f3da3ce) | Apr 26, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [271f1aa4d1](https://bsd-hardware.info/?probe=271f1aa4d1) | Apr 24, 2022 |
| Gigabyte      | B450 AORUS M                | [427cf12b45](https://bsd-hardware.info/?probe=427cf12b45) | Apr 22, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [f7a3f1dfd3](https://bsd-hardware.info/?probe=f7a3f1dfd3) | Apr 21, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [2fd6d176ce](https://bsd-hardware.info/?probe=2fd6d176ce) | Apr 21, 2022 |
| Intel         | H55                         | [1478e4af73](https://bsd-hardware.info/?probe=1478e4af73) | Apr 20, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [ab8aea2f5c](https://bsd-hardware.info/?probe=ab8aea2f5c) | Apr 17, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | [680303f943](https://bsd-hardware.info/?probe=680303f943) | Apr 16, 2022 |
| Dell          | 0Y7WYT A00                  | [399a4fb92e](https://bsd-hardware.info/?probe=399a4fb92e) | Apr 15, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | [47d17d48a7](https://bsd-hardware.info/?probe=47d17d48a7) | Apr 15, 2022 |
| Gigabyte      | B85M-D3H                    | [5502c7fd2f](https://bsd-hardware.info/?probe=5502c7fd2f) | Apr 15, 2022 |
| ASUSTek       | PRIME X399-A                | [3d26c05fda](https://bsd-hardware.info/?probe=3d26c05fda) | Apr 14, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [11ec99d4b7](https://bsd-hardware.info/?probe=11ec99d4b7) | Apr 11, 2022 |
| HP            | 1998                        | [06f0a28858](https://bsd-hardware.info/?probe=06f0a28858) | Apr 10, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [844323ad2d](https://bsd-hardware.info/?probe=844323ad2d) | Apr 09, 2022 |
| ASUSTek       | P5G41T-M LX3                | [ded0d1a114](https://bsd-hardware.info/?probe=ded0d1a114) | Apr 09, 2022 |
| ASUSTek       | P5G41T-M LX3                | [14a6449380](https://bsd-hardware.info/?probe=14a6449380) | Apr 09, 2022 |
| ASUSTek       | M4A88T-M                    | [9d1a8b4886](https://bsd-hardware.info/?probe=9d1a8b4886) | Apr 09, 2022 |
| ASRock        | X570 Steel Legend WiFi a... | [703e042cfe](https://bsd-hardware.info/?probe=703e042cfe) | Apr 09, 2022 |
| Dell          | 0D6H9T A00                  | [e58bc4937d](https://bsd-hardware.info/?probe=e58bc4937d) | Apr 09, 2022 |
| Gigabyte      | E3000N                      | [7169c296cc](https://bsd-hardware.info/?probe=7169c296cc) | Apr 08, 2022 |
| MSI           | MS-7369                     | [25f2161cac](https://bsd-hardware.info/?probe=25f2161cac) | Apr 08, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [964ceb3616](https://bsd-hardware.info/?probe=964ceb3616) | Apr 03, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [5038186437](https://bsd-hardware.info/?probe=5038186437) | Apr 02, 2022 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | [9b6f9eac6f](https://bsd-hardware.info/?probe=9b6f9eac6f) | Apr 01, 2022 |
| Dell          | 0D6H9T A00                  | [7daab72741](https://bsd-hardware.info/?probe=7daab72741) | Apr 01, 2022 |
| ASUSTek       | P6-P8H61E                   | [11664cd9d7](https://bsd-hardware.info/?probe=11664cd9d7) | Mar 30, 2022 |
| ASUSTek       | M4A88T-M                    | [6a615f6be5](https://bsd-hardware.info/?probe=6a615f6be5) | Mar 30, 2022 |
| ASUSTek       | P6-P8H61E                   | [540f66f678](https://bsd-hardware.info/?probe=540f66f678) | Mar 29, 2022 |
| ASUSTek       | M5A78L-M LX3                | [0906d116eb](https://bsd-hardware.info/?probe=0906d116eb) | Mar 29, 2022 |
| Gigabyte      | H110N-CF                    | [89593af061](https://bsd-hardware.info/?probe=89593af061) | Mar 29, 2022 |
| Gigabyte      | H61M-S2PV                   | [553f2beb91](https://bsd-hardware.info/?probe=553f2beb91) | Mar 27, 2022 |
| ASRock        | A320M-HDV R4.0              | [8c89faeb24](https://bsd-hardware.info/?probe=8c89faeb24) | Mar 26, 2022 |
| ASRock        | A320M-HDV R4.0              | [ae1fa6cbce](https://bsd-hardware.info/?probe=ae1fa6cbce) | Mar 26, 2022 |
| MSI           | B85-G43                     | [f0a919c35f](https://bsd-hardware.info/?probe=f0a919c35f) | Mar 25, 2022 |
| MSI           | B85-G43                     | [7bd545fda8](https://bsd-hardware.info/?probe=7bd545fda8) | Mar 25, 2022 |
| ASUSTek       | P8Z77-V LX                  | [8696405d09](https://bsd-hardware.info/?probe=8696405d09) | Mar 24, 2022 |
| ECS           | G41T-M9                     | [9ef50c47da](https://bsd-hardware.info/?probe=9ef50c47da) | Mar 21, 2022 |
| Gigabyte      | H270-Gaming 3               | [2727a8e439](https://bsd-hardware.info/?probe=2727a8e439) | Mar 15, 2022 |
| Gigabyte      | G31M-S2C                    | [5a22bb6991](https://bsd-hardware.info/?probe=5a22bb6991) | Mar 12, 2022 |
| Lenovo        | IdeaCentre B545 10100       | [2f13d4a946](https://bsd-hardware.info/?probe=2f13d4a946) | Mar 12, 2022 |
| MSI           | B350M BAZOOKA               | [bac8d0bdb7](https://bsd-hardware.info/?probe=bac8d0bdb7) | Mar 11, 2022 |
| ASUSTek       | P5Q DELUXE                  | [b4234170e8](https://bsd-hardware.info/?probe=b4234170e8) | Mar 10, 2022 |
| Pegatron      | IPM41-D3                    | [a58b9a4f8f](https://bsd-hardware.info/?probe=a58b9a4f8f) | Mar 09, 2022 |
| Koloe         | X58                         | [58e098eca2](https://bsd-hardware.info/?probe=58e098eca2) | Mar 09, 2022 |
| HP            | 8054                        | [86b6b8373c](https://bsd-hardware.info/?probe=86b6b8373c) | Mar 08, 2022 |
| HP            | 8054                        | [00078554d2](https://bsd-hardware.info/?probe=00078554d2) | Mar 08, 2022 |
| Koloe         | X58                         | [c501dfa5c8](https://bsd-hardware.info/?probe=c501dfa5c8) | Mar 07, 2022 |
| Dell          | 0GXM1W A00                  | [c4d10a26fd](https://bsd-hardware.info/?probe=c4d10a26fd) | Mar 04, 2022 |
| ASRock        | G41C-VS                     | [a9a1b1a493](https://bsd-hardware.info/?probe=a9a1b1a493) | Mar 03, 2022 |
| Intel         | DN2800MT AAG23738-600       | [8ecf2d023f](https://bsd-hardware.info/?probe=8ecf2d023f) | Mar 02, 2022 |
| HP            | 1905                        | [e271589365](https://bsd-hardware.info/?probe=e271589365) | Mar 01, 2022 |
| Gigabyte      | B450M S2H                   | [78f79fab6f](https://bsd-hardware.info/?probe=78f79fab6f) | Feb 28, 2022 |
| Dell          | 0KV62T A00                  | [0541a207c7](https://bsd-hardware.info/?probe=0541a207c7) | Feb 28, 2022 |
| HP            | 1905                        | [aa010e00f2](https://bsd-hardware.info/?probe=aa010e00f2) | Feb 28, 2022 |
| ASRock        | TRX40 Taichi                | [a2df68e1d1](https://bsd-hardware.info/?probe=a2df68e1d1) | Feb 26, 2022 |
| Intel         | H81                         | [dd19abd47d](https://bsd-hardware.info/?probe=dd19abd47d) | Feb 25, 2022 |
| Intel         | H81                         | [04d2739bdc](https://bsd-hardware.info/?probe=04d2739bdc) | Feb 25, 2022 |
| Intel         | DCP847SKE G80890-107        | [f9d33f1ab1](https://bsd-hardware.info/?probe=f9d33f1ab1) | Feb 23, 2022 |
| Medion        | H61H2-LM3                   | [beb12f2884](https://bsd-hardware.info/?probe=beb12f2884) | Feb 23, 2022 |
| ASRock        | H81M-DG4                    | [e20db6ad83](https://bsd-hardware.info/?probe=e20db6ad83) | Feb 23, 2022 |
| HP            | 1998                        | [485d417a2e](https://bsd-hardware.info/?probe=485d417a2e) | Feb 23, 2022 |
| Dell          | 0VD5HY A07                  | [bb86fb3e67](https://bsd-hardware.info/?probe=bb86fb3e67) | Feb 22, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [1e6ff84e5d](https://bsd-hardware.info/?probe=1e6ff84e5d) | Feb 21, 2022 |
| Gigabyte      | P41T-D3                     | [e5417931a7](https://bsd-hardware.info/?probe=e5417931a7) | Feb 18, 2022 |
| ASRock        | B460M Pro4                  | [7a2781344f](https://bsd-hardware.info/?probe=7a2781344f) | Feb 17, 2022 |
| ASUSTek       | PRIME Z390-P                | [3a72227408](https://bsd-hardware.info/?probe=3a72227408) | Feb 16, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | [64999a24c1](https://bsd-hardware.info/?probe=64999a24c1) | Feb 16, 2022 |
| Gigabyte      | C246M-WU4-CF                | [4b6c6d8bde](https://bsd-hardware.info/?probe=4b6c6d8bde) | Feb 15, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [df6278638e](https://bsd-hardware.info/?probe=df6278638e) | Feb 15, 2022 |
| AMD           | X64                         | [e5a9ff1138](https://bsd-hardware.info/?probe=e5a9ff1138) | Feb 15, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [eddeb5c246](https://bsd-hardware.info/?probe=eddeb5c246) | Feb 13, 2022 |
| ASRock        | H61M/U3S3                   | [257e13f206](https://bsd-hardware.info/?probe=257e13f206) | Feb 12, 2022 |
| ASRock        | H61M/U3S3                   | [34dac4c0cd](https://bsd-hardware.info/?probe=34dac4c0cd) | Feb 11, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [6997de25f9](https://bsd-hardware.info/?probe=6997de25f9) | Feb 11, 2022 |
| MACHINIST     | X99-k9 V2.0                 | [0a36d71db1](https://bsd-hardware.info/?probe=0a36d71db1) | Feb 10, 2022 |
| Intel         | X58                         | [f7075908f6](https://bsd-hardware.info/?probe=f7075908f6) | Feb 09, 2022 |
| ASUSTek       | PRIME Z390-P                | [b1931633be](https://bsd-hardware.info/?probe=b1931633be) | Feb 09, 2022 |
| ASUSTek       | PRIME Z390-P                | [f9c1e787a9](https://bsd-hardware.info/?probe=f9c1e787a9) | Feb 09, 2022 |
| MSI           | B75A-G43                    | [8e445eb2d4](https://bsd-hardware.info/?probe=8e445eb2d4) | Feb 08, 2022 |
| ASUSTek       | P6-P8H61E                   | [e838981914](https://bsd-hardware.info/?probe=e838981914) | Feb 06, 2022 |
| ASRock        | H81M-VG4 R2.0               | [8af8b5270e](https://bsd-hardware.info/?probe=8af8b5270e) | Feb 04, 2022 |
| Apple         | Mac-F221BEC8                | [e5043f0af4](https://bsd-hardware.info/?probe=e5043f0af4) | Feb 04, 2022 |
| Pegatron      | NARRA5                      | [64d4fb9b97](https://bsd-hardware.info/?probe=64d4fb9b97) | Feb 02, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | [ee05643521](https://bsd-hardware.info/?probe=ee05643521) | Feb 01, 2022 |
| ASUSTek       | P5P43TD PRO                 | [5999e0ebfb](https://bsd-hardware.info/?probe=5999e0ebfb) | Jan 31, 2022 |
| Intel         | H81                         | [c2f3025900](https://bsd-hardware.info/?probe=c2f3025900) | Jan 31, 2022 |
| Pegatron      | 2A99h                       | [e34b6118a2](https://bsd-hardware.info/?probe=e34b6118a2) | Jan 30, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [58ea01e4e6](https://bsd-hardware.info/?probe=58ea01e4e6) | Jan 29, 2022 |
| Intel         | DH77EB AAG39073-400         | [bfe6ef301b](https://bsd-hardware.info/?probe=bfe6ef301b) | Jan 29, 2022 |
| Dell          | 014GRG A03                  | [8e0a22c065](https://bsd-hardware.info/?probe=8e0a22c065) | Jan 28, 2022 |
| Pegatron      | IPPPV-D3G                   | [d5e44ccf6b](https://bsd-hardware.info/?probe=d5e44ccf6b) | Jan 28, 2022 |
| Dell          | 014GRG A03                  | [5996ba19b1](https://bsd-hardware.info/?probe=5996ba19b1) | Jan 27, 2022 |
| ASUSTek       | P5GC-MX                     | [372749f9d7](https://bsd-hardware.info/?probe=372749f9d7) | Jan 27, 2022 |
| Unknown       | Unknown                     | [a9d799ca71](https://bsd-hardware.info/?probe=a9d799ca71) | Jan 27, 2022 |
| ASUSTek       | P5B SE                      | [f97fba19c1](https://bsd-hardware.info/?probe=f97fba19c1) | Jan 26, 2022 |
| Dell          | 014GRG A03                  | [223d955a90](https://bsd-hardware.info/?probe=223d955a90) | Jan 26, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [9f0a000ceb](https://bsd-hardware.info/?probe=9f0a000ceb) | Jan 25, 2022 |
| ASUSTek       | P5B SE                      | [e3332e7b94](https://bsd-hardware.info/?probe=e3332e7b94) | Jan 25, 2022 |
| ASRock        | B460M Pro4                  | [107a1e59f5](https://bsd-hardware.info/?probe=107a1e59f5) | Jan 25, 2022 |
| ASRock        | A300M-STX                   | [8edf072b67](https://bsd-hardware.info/?probe=8edf072b67) | Jan 25, 2022 |
| Intel         | MAHOBAY                     | [2036093b68](https://bsd-hardware.info/?probe=2036093b68) | Jan 25, 2022 |
| ASUSTek       | BM6835_BM6635_BP6335        | [73562aa169](https://bsd-hardware.info/?probe=73562aa169) | Jan 25, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [df08e2e8f0](https://bsd-hardware.info/?probe=df08e2e8f0) | Jan 24, 2022 |
| Dell          | 05DN3X A00                  | [e0e63e69ef](https://bsd-hardware.info/?probe=e0e63e69ef) | Jan 23, 2022 |
| ASUSTek       | P7H55-M                     | [fb73c2f7dc](https://bsd-hardware.info/?probe=fb73c2f7dc) | Jan 23, 2022 |
| HP            | 8648                        | [b0adf55067](https://bsd-hardware.info/?probe=b0adf55067) | Jan 23, 2022 |
| HP            | 1998                        | [b59dbcdc9c](https://bsd-hardware.info/?probe=b59dbcdc9c) | Jan 23, 2022 |
| Dell          | 05DN3X A00                  | [460ea5c41d](https://bsd-hardware.info/?probe=460ea5c41d) | Jan 23, 2022 |
| Dell          | 0593VH A00                  | [484d14dbef](https://bsd-hardware.info/?probe=484d14dbef) | Jan 22, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [670e41ed41](https://bsd-hardware.info/?probe=670e41ed41) | Jan 21, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [04abd226f3](https://bsd-hardware.info/?probe=04abd226f3) | Jan 21, 2022 |
| ASUSTek       | Maximus VIII HERO           | [a780a7bab2](https://bsd-hardware.info/?probe=a780a7bab2) | Jan 18, 2022 |
| ASRock        | B365M Pro4                  | [8449bd20c1](https://bsd-hardware.info/?probe=8449bd20c1) | Jan 18, 2022 |
| Dell          | 0YF8P5 A00                  | [913b2a7483](https://bsd-hardware.info/?probe=913b2a7483) | Jan 18, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | [9cd2758a5f](https://bsd-hardware.info/?probe=9cd2758a5f) | Jan 18, 2022 |
| ASUSTek       | PRIME X570-P                | [3dead218e1](https://bsd-hardware.info/?probe=3dead218e1) | Jan 16, 2022 |
| Gigabyte      | B365 HD3                    | [62fc48bd99](https://bsd-hardware.info/?probe=62fc48bd99) | Jan 15, 2022 |
| Dell          | 0XCR8D A03                  | [48e9447b37](https://bsd-hardware.info/?probe=48e9447b37) | Jan 15, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [d377e06101](https://bsd-hardware.info/?probe=d377e06101) | Jan 15, 2022 |
| Gigabyte      | Z77N-WIFI                   | [459bb6486d](https://bsd-hardware.info/?probe=459bb6486d) | Jan 13, 2022 |
| Dell          | 0X4N41 A01                  | [87000234dc](https://bsd-hardware.info/?probe=87000234dc) | Jan 11, 2022 |
| ASUSTek       | P8Z68-M PRO                 | [a0885f4f44](https://bsd-hardware.info/?probe=a0885f4f44) | Jan 10, 2022 |
| HP            | 8169                        | [85e0cf058c](https://bsd-hardware.info/?probe=85e0cf058c) | Jan 10, 2022 |
| ASUSTek       | GA35DX                      | [eccb947ae4](https://bsd-hardware.info/?probe=eccb947ae4) | Jan 05, 2022 |
| Unknown       | G31T-M7                     | [ed7d80e01a](https://bsd-hardware.info/?probe=ed7d80e01a) | Jan 03, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | [a671e3eb04](https://bsd-hardware.info/?probe=a671e3eb04) | Dec 31, 2021 |
| ASUSTek       | M5A78L/USB3                 | [f1fe3fe225](https://bsd-hardware.info/?probe=f1fe3fe225) | Dec 30, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [15211db056](https://bsd-hardware.info/?probe=15211db056) | Dec 28, 2021 |
| Dell          | 0200DY A01                  | [fb37dcbb93](https://bsd-hardware.info/?probe=fb37dcbb93) | Dec 28, 2021 |
| Pegatron      | IPM41-D3                    | [6829928dad](https://bsd-hardware.info/?probe=6829928dad) | Dec 28, 2021 |
| Dell          | 0H9KW5 A00                  | [e962ca25b3](https://bsd-hardware.info/?probe=e962ca25b3) | Dec 28, 2021 |
| Gigabyte      | 970A-DS3P                   | [0918f0a5b9](https://bsd-hardware.info/?probe=0918f0a5b9) | Dec 25, 2021 |
| ASUSTek       | PRIME B350M-A               | [b0aa3885bb](https://bsd-hardware.info/?probe=b0aa3885bb) | Dec 25, 2021 |
| ASUSTek       | Z170-P                      | [bde74629f9](https://bsd-hardware.info/?probe=bde74629f9) | Dec 25, 2021 |
| Gigabyte      | E3000N                      | [eb0ba1b296](https://bsd-hardware.info/?probe=eb0ba1b296) | Dec 22, 2021 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [936afa4de3](https://bsd-hardware.info/?probe=936afa4de3) | Dec 21, 2021 |
| ASUSTek       | PRIME A320M-K               | [42599b554e](https://bsd-hardware.info/?probe=42599b554e) | Dec 21, 2021 |
| Gigabyte      | X58A-UD5                    | [62b94dd372](https://bsd-hardware.info/?probe=62b94dd372) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [5cc62c68f9](https://bsd-hardware.info/?probe=5cc62c68f9) | Dec 21, 2021 |
| Gigabyte      | H170-D3HP-CF                | [a490614a39](https://bsd-hardware.info/?probe=a490614a39) | Dec 21, 2021 |
| ASRock        | H110M-DGS                   | [40c4553adb](https://bsd-hardware.info/?probe=40c4553adb) | Dec 21, 2021 |
| ASUSTek       | P5VD2-VM                    | [7e8f3cf783](https://bsd-hardware.info/?probe=7e8f3cf783) | Dec 20, 2021 |
| ASUSTek       | Q170M-C                     | [7f9e35a31c](https://bsd-hardware.info/?probe=7f9e35a31c) | Dec 20, 2021 |
| Dell          | 0TDG4V A00                  | [3ce808c135](https://bsd-hardware.info/?probe=3ce808c135) | Dec 20, 2021 |
| Dell          | 0TDG4V A00                  | [5292ad64ef](https://bsd-hardware.info/?probe=5292ad64ef) | Dec 20, 2021 |
| ASUSTek       | P8Z77-V LX                  | [3c71a8ba4e](https://bsd-hardware.info/?probe=3c71a8ba4e) | Dec 20, 2021 |
| MSI           | X370 SLI PLUS               | [73853f1fc2](https://bsd-hardware.info/?probe=73853f1fc2) | Dec 19, 2021 |
| Quanta        | 2AC7 011                    | [1a831a1d34](https://bsd-hardware.info/?probe=1a831a1d34) | Dec 18, 2021 |
| Gigabyte      | Z77X-UD3H                   | [759ce775c9](https://bsd-hardware.info/?probe=759ce775c9) | Dec 15, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [32d20b9b8e](https://bsd-hardware.info/?probe=32d20b9b8e) | Dec 14, 2021 |
| HP            | 843B                        | [f0d279747f](https://bsd-hardware.info/?probe=f0d279747f) | Dec 13, 2021 |
| HP            | 843B                        | [56400d3999](https://bsd-hardware.info/?probe=56400d3999) | Dec 13, 2021 |
| ASUSTek       | PRIME B450M-A               | [aea4a33dee](https://bsd-hardware.info/?probe=aea4a33dee) | Dec 13, 2021 |
| ASUSTek       | H110M-K                     | [2921401f70](https://bsd-hardware.info/?probe=2921401f70) | Dec 12, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [50fba6deda](https://bsd-hardware.info/?probe=50fba6deda) | Dec 11, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [6a1100cfdb](https://bsd-hardware.info/?probe=6a1100cfdb) | Dec 11, 2021 |
| Acer          | RevoOne RL85                | [a1e32de7da](https://bsd-hardware.info/?probe=a1e32de7da) | Dec 10, 2021 |
| HP            | 8054                        | [de953100f6](https://bsd-hardware.info/?probe=de953100f6) | Dec 10, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [a9423b3232](https://bsd-hardware.info/?probe=a9423b3232) | Dec 09, 2021 |
| Dell          | 0YF8P5 A00                  | [0f03a66475](https://bsd-hardware.info/?probe=0f03a66475) | Dec 09, 2021 |
| Dell          | 0YF8P5 A00                  | [83b36f7c3d](https://bsd-hardware.info/?probe=83b36f7c3d) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [a084ff48c2](https://bsd-hardware.info/?probe=a084ff48c2) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [17b557d792](https://bsd-hardware.info/?probe=17b557d792) | Dec 08, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [35b01f0f56](https://bsd-hardware.info/?probe=35b01f0f56) | Dec 05, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [14f1956220](https://bsd-hardware.info/?probe=14f1956220) | Dec 04, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [8cfe11fe93](https://bsd-hardware.info/?probe=8cfe11fe93) | Nov 30, 2021 |
| Intel         | DG41TY AAE47335-300         | [dd357bcaa5](https://bsd-hardware.info/?probe=dd357bcaa5) | Nov 30, 2021 |
| HP            | 843B                        | [404224439d](https://bsd-hardware.info/?probe=404224439d) | Nov 29, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [bc3b65334e](https://bsd-hardware.info/?probe=bc3b65334e) | Nov 29, 2021 |
| HP            | 1825                        | [32f07d2ba3](https://bsd-hardware.info/?probe=32f07d2ba3) | Nov 28, 2021 |
| Dell          | 0DR845                      | [4d07453a93](https://bsd-hardware.info/?probe=4d07453a93) | Nov 27, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [4cd5e5166a](https://bsd-hardware.info/?probe=4cd5e5166a) | Nov 27, 2021 |
| ASRock        | 775i945GZ                   | [16fc4ee10d](https://bsd-hardware.info/?probe=16fc4ee10d) | Nov 26, 2021 |
| ASRock        | AB350 Pro4                  | [ef35dd084e](https://bsd-hardware.info/?probe=ef35dd084e) | Nov 26, 2021 |
| HP            | 0A80h                       | [1e1153ee69](https://bsd-hardware.info/?probe=1e1153ee69) | Nov 22, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [afd0cf45c6](https://bsd-hardware.info/?probe=afd0cf45c6) | Nov 21, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [12a360ddd1](https://bsd-hardware.info/?probe=12a360ddd1) | Nov 14, 2021 |
| T-bao         | MINI PC V1.0                | [4ee7de3597](https://bsd-hardware.info/?probe=4ee7de3597) | Nov 12, 2021 |
| Biostar       | B365MHC                     | [0c059bab3f](https://bsd-hardware.info/?probe=0c059bab3f) | Nov 11, 2021 |
| Itautec       | ST 4344 ST-4344 Padrao 0... | [ec13cb0829](https://bsd-hardware.info/?probe=ec13cb0829) | Nov 07, 2021 |
| Shuttle       | FH61R                       | [a231590743](https://bsd-hardware.info/?probe=a231590743) | Nov 07, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [7e27b1bc46](https://bsd-hardware.info/?probe=7e27b1bc46) | Nov 07, 2021 |
| Intel         | H81                         | [7f07aecffc](https://bsd-hardware.info/?probe=7f07aecffc) | Nov 07, 2021 |
| HP            | 844C                        | [fb7d8eaf5d](https://bsd-hardware.info/?probe=fb7d8eaf5d) | Nov 06, 2021 |
| Unknown       | X79                         | [ef88cbc606](https://bsd-hardware.info/?probe=ef88cbc606) | Nov 05, 2021 |
| ASRock        | X370 Gaming X               | [2a874a33dd](https://bsd-hardware.info/?probe=2a874a33dd) | Nov 05, 2021 |
| Lenovo        | SHARKBAY No DPK             | [b9ad64f354](https://bsd-hardware.info/?probe=b9ad64f354) | Nov 04, 2021 |
| Gigabyte      | F2A78M-DS2                  | [45576fddfa](https://bsd-hardware.info/?probe=45576fddfa) | Nov 02, 2021 |
| Dell          | 0M5DCD A02                  | [4ff4198768](https://bsd-hardware.info/?probe=4ff4198768) | Nov 02, 2021 |
| Gateway       | DX4840                      | [1d2e9e175c](https://bsd-hardware.info/?probe=1d2e9e175c) | Nov 01, 2021 |
| ASRock        | X300M-STX                   | [e25f042400](https://bsd-hardware.info/?probe=e25f042400) | Oct 30, 2021 |
| Unknown       | Intel X79                   | [044908e7c3](https://bsd-hardware.info/?probe=044908e7c3) | Oct 30, 2021 |
| HP            | 843B                        | [9761f29b5e](https://bsd-hardware.info/?probe=9761f29b5e) | Oct 25, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [9f8010bdbe](https://bsd-hardware.info/?probe=9f8010bdbe) | Oct 25, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | [9959c0900a](https://bsd-hardware.info/?probe=9959c0900a) | Oct 23, 2021 |
| Gigabyte      | H410M S2 V2                 | [b106820e47](https://bsd-hardware.info/?probe=b106820e47) | Oct 21, 2021 |
| Acer          | RS880M05                    | [4718f0cb0c](https://bsd-hardware.info/?probe=4718f0cb0c) | Oct 21, 2021 |
| Apple         | Mac-F221BEC8                | [cb2cc35e6c](https://bsd-hardware.info/?probe=cb2cc35e6c) | Oct 19, 2021 |
| Gigabyte      | 990FXA-UD3                  | [3cf20ca77c](https://bsd-hardware.info/?probe=3cf20ca77c) | Oct 19, 2021 |
| Dell          | 0VRWRC A00                  | [9b4defb194](https://bsd-hardware.info/?probe=9b4defb194) | Oct 19, 2021 |
| HP            | 3398                        | [892f19c9bd](https://bsd-hardware.info/?probe=892f19c9bd) | Oct 18, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [0cdd3497f6](https://bsd-hardware.info/?probe=0cdd3497f6) | Oct 18, 2021 |
| Gigabyte      | G41MT-S2                    | [2847d63db0](https://bsd-hardware.info/?probe=2847d63db0) | Oct 18, 2021 |
| ASUSTek       | P5P43TD PRO                 | [2870e26de1](https://bsd-hardware.info/?probe=2870e26de1) | Oct 17, 2021 |
| ASUSTek       | F2A85-M                     | [b4e3f33e5c](https://bsd-hardware.info/?probe=b4e3f33e5c) | Oct 14, 2021 |
| Lenovo        | SHARKBAY No DPK             | [14dcd924b5](https://bsd-hardware.info/?probe=14dcd924b5) | Oct 13, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [b3b31d25b0](https://bsd-hardware.info/?probe=b3b31d25b0) | Oct 13, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [5a7c1871b1](https://bsd-hardware.info/?probe=5a7c1871b1) | Oct 11, 2021 |
| Acer          | Aspire TC-780               | [77101a00b3](https://bsd-hardware.info/?probe=77101a00b3) | Oct 11, 2021 |
| Acer          | Aspire TC-780               | [3ce8481842](https://bsd-hardware.info/?probe=3ce8481842) | Oct 10, 2021 |
| ASUSTek       | D940MX                      | [4e798f3ef0](https://bsd-hardware.info/?probe=4e798f3ef0) | Oct 10, 2021 |
| Medion        | H61H2-LM3                   | [67ed0f639c](https://bsd-hardware.info/?probe=67ed0f639c) | Oct 10, 2021 |
| ASUSTek       | H81M-K                      | [e24f67a603](https://bsd-hardware.info/?probe=e24f67a603) | Oct 08, 2021 |
| MSI           | G41M-P25                    | [21eec496b4](https://bsd-hardware.info/?probe=21eec496b4) | Oct 08, 2021 |
| ASRock        | A320M-DGS                   | [11cf5c923a](https://bsd-hardware.info/?probe=11cf5c923a) | Oct 08, 2021 |
| Gigabyte      | B450 AORUS M                | [d09f63f257](https://bsd-hardware.info/?probe=d09f63f257) | Oct 07, 2021 |
| Intel         | H61                         | [6ce71c1b9e](https://bsd-hardware.info/?probe=6ce71c1b9e) | Oct 06, 2021 |
| HP            | 3397                        | [4c71aae5bf](https://bsd-hardware.info/?probe=4c71aae5bf) | Oct 05, 2021 |
| ASRock        | B365M-ITX/ac                | [1c8820a6d0](https://bsd-hardware.info/?probe=1c8820a6d0) | Oct 04, 2021 |
| MSI           | B450I GAMING PLUS AC        | [43388a27a4](https://bsd-hardware.info/?probe=43388a27a4) | Oct 04, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | [bd312d1c88](https://bsd-hardware.info/?probe=bd312d1c88) | Oct 03, 2021 |
| HP            | ProLiant ML350 G5           | [4d525cba3e](https://bsd-hardware.info/?probe=4d525cba3e) | Oct 03, 2021 |
| HP            | 87D6 SMVB                   | [90d91bc113](https://bsd-hardware.info/?probe=90d91bc113) | Sep 26, 2021 |
| Gigabyte      | H61M-D2P-B3                 | [c6da80d54b](https://bsd-hardware.info/?probe=c6da80d54b) | Sep 25, 2021 |
| ASUSTek       | M5A78L-M LX3                | [f336d13e01](https://bsd-hardware.info/?probe=f336d13e01) | Sep 24, 2021 |
| Gigabyte      | H61M-D2P-B3                 | [6ed62a3798](https://bsd-hardware.info/?probe=6ed62a3798) | Sep 23, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [9b14548c15](https://bsd-hardware.info/?probe=9b14548c15) | Sep 21, 2021 |
| Sapphire      | EDGE-FT1M1 E450 1AOVU044    | [ea8fefdf4e](https://bsd-hardware.info/?probe=ea8fefdf4e) | Sep 20, 2021 |
| Dell          | 0MGK50 A02                  | [9d2959b4f1](https://bsd-hardware.info/?probe=9d2959b4f1) | Sep 20, 2021 |
| HP            | 81B4 01                     | [179504116d](https://bsd-hardware.info/?probe=179504116d) | Sep 20, 2021 |
| HP            | 81B4 01                     | [5b28c9bb75](https://bsd-hardware.info/?probe=5b28c9bb75) | Sep 20, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [790d020ebe](https://bsd-hardware.info/?probe=790d020ebe) | Sep 19, 2021 |
| Foxconn       | A88GMX FAB                  | [b46845b69f](https://bsd-hardware.info/?probe=b46845b69f) | Sep 19, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [9b046b157e](https://bsd-hardware.info/?probe=9b046b157e) | Sep 17, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [bc2a287495](https://bsd-hardware.info/?probe=bc2a287495) | Sep 13, 2021 |
| HP            | 87D6 SMVB                   | [61fc69edfe](https://bsd-hardware.info/?probe=61fc69edfe) | Sep 13, 2021 |
| ASUSTek       | P8H77-I                     | [1feb22dc52](https://bsd-hardware.info/?probe=1feb22dc52) | Sep 12, 2021 |
| Sapphire      | EDGE-FT1M1 E450 1AOVU044    | [85ed325446](https://bsd-hardware.info/?probe=85ed325446) | Sep 11, 2021 |
| ASUSTek       | PRIME B360M-C               | [0f6e7e26fc](https://bsd-hardware.info/?probe=0f6e7e26fc) | Sep 11, 2021 |
| ASRock        | B460M Pro4                  | [cfc7818691](https://bsd-hardware.info/?probe=cfc7818691) | Sep 10, 2021 |
| ASUSTek       | H110M-PLUS                  | [08b4825275](https://bsd-hardware.info/?probe=08b4825275) | Sep 09, 2021 |
| ASRock        | B550M Pro4                  | [dc582ea4d3](https://bsd-hardware.info/?probe=dc582ea4d3) | Sep 09, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [c729f82f4c](https://bsd-hardware.info/?probe=c729f82f4c) | Sep 08, 2021 |
| Packard Be... | imedia S2110A               | [d62a38660c](https://bsd-hardware.info/?probe=d62a38660c) | Sep 08, 2021 |
| Lenovo        | Board                       | [685abcc739](https://bsd-hardware.info/?probe=685abcc739) | Sep 07, 2021 |
| HP            | 3397                        | [5d95b75768](https://bsd-hardware.info/?probe=5d95b75768) | Sep 06, 2021 |
| Medion        | H61H2-LM3                   | [7a42009a08](https://bsd-hardware.info/?probe=7a42009a08) | Sep 02, 2021 |
| Medion        | H61H2-LM3                   | [eb81abe401](https://bsd-hardware.info/?probe=eb81abe401) | Sep 02, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [9e13729a12](https://bsd-hardware.info/?probe=9e13729a12) | Sep 02, 2021 |
| ASRock        | Z390 Pro4                   | [ecbf097bc5](https://bsd-hardware.info/?probe=ecbf097bc5) | Sep 02, 2021 |
| ASUSTek       | TUF B360M-PLUS GAMING S     | [33ba0b7c38](https://bsd-hardware.info/?probe=33ba0b7c38) | Aug 29, 2021 |
| HP            | 0A60h                       | [0f28538e3d](https://bsd-hardware.info/?probe=0f28538e3d) | Aug 25, 2021 |
| HP            | 1589                        | [4d51cc9c4b](https://bsd-hardware.info/?probe=4d51cc9c4b) | Aug 24, 2021 |
| Acer          | Aspire TC-895 V:1.0         | [da3e8986a3](https://bsd-hardware.info/?probe=da3e8986a3) | Aug 22, 2021 |
| EVGA          | X299 MICRO                  | [d04b55d1f6](https://bsd-hardware.info/?probe=d04b55d1f6) | Aug 19, 2021 |
| ASRock        | Z390 Pro4                   | [aca402061b](https://bsd-hardware.info/?probe=aca402061b) | Aug 18, 2021 |
| Foxconn       | 2ADA                        | [e96976b2cc](https://bsd-hardware.info/?probe=e96976b2cc) | Aug 18, 2021 |
| Dell          | 0MGK50 A02                  | [2468e9d0ba](https://bsd-hardware.info/?probe=2468e9d0ba) | Aug 17, 2021 |
| HC            | HCAR357-MI V1.0             | [3293b7bad9](https://bsd-hardware.info/?probe=3293b7bad9) | Aug 17, 2021 |
| ASUSTek       | P7H55-M LX                  | [5fe1a9e521](https://bsd-hardware.info/?probe=5fe1a9e521) | Aug 16, 2021 |
| Gigabyte      | HA65M-D2H-B3                | [fc9b50bb85](https://bsd-hardware.info/?probe=fc9b50bb85) | Aug 16, 2021 |
| Gigabyte      | B360M D3H-CF                | [1c88ce5779](https://bsd-hardware.info/?probe=1c88ce5779) | Aug 10, 2021 |
| Pegatron      | IPPCR-SS                    | [8a7fc2689b](https://bsd-hardware.info/?probe=8a7fc2689b) | Aug 09, 2021 |
| Gigabyte      | A75M-DS2                    | [2010fe5fab](https://bsd-hardware.info/?probe=2010fe5fab) | Aug 09, 2021 |
| ASUSTek       | P7H55-M LX                  | [df393cc673](https://bsd-hardware.info/?probe=df393cc673) | Aug 08, 2021 |
| Intel         | D54250WYK H13922-304        | [45c86d174e](https://bsd-hardware.info/?probe=45c86d174e) | Aug 08, 2021 |
| ASUSTek       | M5A78L LE                   | [7a1d31be72](https://bsd-hardware.info/?probe=7a1d31be72) | Aug 07, 2021 |
| ASUSTek       | H81M-A                      | [bb65c30be3](https://bsd-hardware.info/?probe=bb65c30be3) | Aug 07, 2021 |
| ASUSTek       | H81M-A                      | [9e0c8e8024](https://bsd-hardware.info/?probe=9e0c8e8024) | Aug 07, 2021 |
| ASUSTek       | Crosshair V Formula         | [90c27497d9](https://bsd-hardware.info/?probe=90c27497d9) | Aug 05, 2021 |
| PCPartner     | MILANO-P Rev.00             | [526390c559](https://bsd-hardware.info/?probe=526390c559) | Aug 04, 2021 |
| Biostar       | A770E3                      | [4d0ac19b8e](https://bsd-hardware.info/?probe=4d0ac19b8e) | Aug 03, 2021 |
| Dell          | 0RY007                      | [c67ccf8bc6](https://bsd-hardware.info/?probe=c67ccf8bc6) | Aug 01, 2021 |
| PCPartner     | MILANO-P Rev.00             | [ef8217ac30](https://bsd-hardware.info/?probe=ef8217ac30) | Aug 01, 2021 |
| Gigabyte      | H110-D3A-CF                 | [7923f57fbe](https://bsd-hardware.info/?probe=7923f57fbe) | Aug 01, 2021 |
| ASUSTek       | A58M-A/USB3                 | [9ffd4220e8](https://bsd-hardware.info/?probe=9ffd4220e8) | Aug 01, 2021 |
| Biostar       | N68S3+                      | [528c9d6eab](https://bsd-hardware.info/?probe=528c9d6eab) | Jul 26, 2021 |
| Gigabyte      | PH67A-D3-B3                 | [73dff53f04](https://bsd-hardware.info/?probe=73dff53f04) | Jul 23, 2021 |
| ASUSTek       | H110M-PLUS                  | [d0f2da9c41](https://bsd-hardware.info/?probe=d0f2da9c41) | Jul 21, 2021 |
| Gigabyte      | H110-D3A-CF                 | [58e49f458e](https://bsd-hardware.info/?probe=58e49f458e) | Jul 19, 2021 |
| PCPartner     | MILANO-P Rev.00             | [f20ac8df75](https://bsd-hardware.info/?probe=f20ac8df75) | Jul 19, 2021 |
| MSI           | IONA                        | [bb2c6b383b](https://bsd-hardware.info/?probe=bb2c6b383b) | Jul 17, 2021 |
| ASRock        | N68C-GS FX                  | [012356047f](https://bsd-hardware.info/?probe=012356047f) | Jul 17, 2021 |
| ASRock        | N68C-GS FX                  | [e1f439def9](https://bsd-hardware.info/?probe=e1f439def9) | Jul 17, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [20fc88018b](https://bsd-hardware.info/?probe=20fc88018b) | Jul 16, 2021 |
| HP            | 0AE8h C                     | [23df6b2e94](https://bsd-hardware.info/?probe=23df6b2e94) | Jul 12, 2021 |
| Gigabyte      | H110-D3A-CF                 | [2c390b4301](https://bsd-hardware.info/?probe=2c390b4301) | Jul 09, 2021 |
| Gigabyte      | H110-D3A-CF                 | [aea3a11daf](https://bsd-hardware.info/?probe=aea3a11daf) | Jul 08, 2021 |
| Dell          | 0GXM1W A02                  | [269edf2dcf](https://bsd-hardware.info/?probe=269edf2dcf) | Jul 06, 2021 |
| ASRock        | B450M-HDV                   | [dca41aa10a](https://bsd-hardware.info/?probe=dca41aa10a) | Jul 05, 2021 |
| ASRock        | X99 Taichi                  | [149d7abd05](https://bsd-hardware.info/?probe=149d7abd05) | Jul 04, 2021 |
| ASUSTek       | PRIME Z390-P                | [4060cdec72](https://bsd-hardware.info/?probe=4060cdec72) | Jul 04, 2021 |
| ASRock        | Z390 Pro4                   | [dc4eb674ea](https://bsd-hardware.info/?probe=dc4eb674ea) | Jul 03, 2021 |
| Shuttle       | NC10U                       | [5d2d20dd04](https://bsd-hardware.info/?probe=5d2d20dd04) | Jul 02, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [6cf3337855](https://bsd-hardware.info/?probe=6cf3337855) | Jul 01, 2021 |
| Protectli     | FW2B Ver                    | [7b6f704247](https://bsd-hardware.info/?probe=7b6f704247) | Jun 30, 2021 |
| HP            | 0B4Ch D                     | [b56bd19073](https://bsd-hardware.info/?probe=b56bd19073) | Jun 30, 2021 |
| Biostar       | B450MH                      | [167f09a25c](https://bsd-hardware.info/?probe=167f09a25c) | Jun 29, 2021 |
| ASUSTek       | M5A97 R2.0                  | [e7a0dfcecf](https://bsd-hardware.info/?probe=e7a0dfcecf) | Jun 28, 2021 |
| Huanan        | X99-8M-F V1.2               | [6477b9ef24](https://bsd-hardware.info/?probe=6477b9ef24) | Jun 28, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [f0e80b0788](https://bsd-hardware.info/?probe=f0e80b0788) | Jun 28, 2021 |
| ASUSTek       | H110M-E/M.2                 | [f3b0bb0930](https://bsd-hardware.info/?probe=f3b0bb0930) | Jun 28, 2021 |
| ASUSTek       | H81M-K                      | [1a35d2f6ab](https://bsd-hardware.info/?probe=1a35d2f6ab) | Jun 26, 2021 |
| ASUSTek       | PRIME H410M-D               | [8ea103b783](https://bsd-hardware.info/?probe=8ea103b783) | Jun 26, 2021 |
| MSI           | G41M-P25                    | [5cc75b4df0](https://bsd-hardware.info/?probe=5cc75b4df0) | Jun 25, 2021 |
| Dell          | 0P03DX A03                  | [b2f0c90d79](https://bsd-hardware.info/?probe=b2f0c90d79) | Jun 24, 2021 |
| ASUSTek       | P7H55                       | [c33ec074f8](https://bsd-hardware.info/?probe=c33ec074f8) | Jun 22, 2021 |
| ASUSTek       | P8H67-M PRO                 | [616c7043bd](https://bsd-hardware.info/?probe=616c7043bd) | Jun 22, 2021 |
| ASUSTek       | CP5141                      | [73c62835c1](https://bsd-hardware.info/?probe=73c62835c1) | Jun 21, 2021 |
| Foxconn       | 2ABF                        | [d30b2629eb](https://bsd-hardware.info/?probe=d30b2629eb) | Jun 21, 2021 |
| Intel         | DH67CL AAG10212-206         | [f2367a4249](https://bsd-hardware.info/?probe=f2367a4249) | Jun 21, 2021 |
| Gigabyte      | H97-D3H-CF                  | [a326fd4061](https://bsd-hardware.info/?probe=a326fd4061) | Jun 20, 2021 |
| Dell          | 0PGKWF A01                  | [9f09d62462](https://bsd-hardware.info/?probe=9f09d62462) | Jun 20, 2021 |
| MSI           | H110M PRO-VH PLUS           | [45b842180e](https://bsd-hardware.info/?probe=45b842180e) | Jun 20, 2021 |
| ASUSTek       | ROG STRIX H370-I GAMING     | [d2dd261a2a](https://bsd-hardware.info/?probe=d2dd261a2a) | Jun 20, 2021 |
| MSI           | B450M PRO-M2 MAX            | [edcbaf755f](https://bsd-hardware.info/?probe=edcbaf755f) | Jun 19, 2021 |
| Dell          | 0XPDFK A01                  | [631dbb841b](https://bsd-hardware.info/?probe=631dbb841b) | Jun 19, 2021 |
| Lenovo        | ThinkServer RS140           | [0f5d669e9f](https://bsd-hardware.info/?probe=0f5d669e9f) | Jun 18, 2021 |
| Lenovo        | ThinkServer RS140           | [63ba615299](https://bsd-hardware.info/?probe=63ba615299) | Jun 18, 2021 |
| Gigabyte      | AX370-Gaming-CF             | [d77be09267](https://bsd-hardware.info/?probe=d77be09267) | Jun 18, 2021 |
| Dell          | 0XPDFK A01                  | [7a1c26edeb](https://bsd-hardware.info/?probe=7a1c26edeb) | Jun 18, 2021 |
| ASUSTek       | H110I-PLUS                  | [0cb30b464d](https://bsd-hardware.info/?probe=0cb30b464d) | Jun 17, 2021 |
| ASUSTek       | H110M-E/M.2                 | [b0b67667d3](https://bsd-hardware.info/?probe=b0b67667d3) | Jun 16, 2021 |
| HP            | 3397                        | [3dd97c60ca](https://bsd-hardware.info/?probe=3dd97c60ca) | Jun 16, 2021 |
| Lenovo        | Board                       | [c981ffdff7](https://bsd-hardware.info/?probe=c981ffdff7) | Jun 15, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [5f9b56c8ae](https://bsd-hardware.info/?probe=5f9b56c8ae) | Jun 15, 2021 |
| ASUSTek       | M4A78LT-M                   | [0c8d6cd661](https://bsd-hardware.info/?probe=0c8d6cd661) | Jun 14, 2021 |
| ASUSTek       | PRIME A320M-K               | [fea57181b5](https://bsd-hardware.info/?probe=fea57181b5) | Jun 14, 2021 |
| ASRock        | G31M-VS2                    | [f2f5b95f4b](https://bsd-hardware.info/?probe=f2f5b95f4b) | Jun 14, 2021 |
| Intel         | X79 V2.72A                  | [88173bcf06](https://bsd-hardware.info/?probe=88173bcf06) | Jun 14, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [eeb4489d2f](https://bsd-hardware.info/?probe=eeb4489d2f) | Jun 13, 2021 |
| Gigabyte      | H470M DS3H                  | [7c37a0319b](https://bsd-hardware.info/?probe=7c37a0319b) | Jun 13, 2021 |
| ASRock        | FM2A68M-HD+                 | [8bb0d23eb4](https://bsd-hardware.info/?probe=8bb0d23eb4) | Jun 13, 2021 |
| ASUSTek       | Z97-A-USB31                 | [7fe10badbb](https://bsd-hardware.info/?probe=7fe10badbb) | Jun 11, 2021 |
| Lenovo        | Board                       | [1d6f23a5de](https://bsd-hardware.info/?probe=1d6f23a5de) | May 24, 2021 |
| Apple         | Mac-F221BEC8                | [869f003493](https://bsd-hardware.info/?probe=869f003493) | May 17, 2021 |
| MSI           | B450M-A PRO MAX             | [6317bd7dbd](https://bsd-hardware.info/?probe=6317bd7dbd) | May 05, 2021 |
| MSI           | B450-A PRO                  | [ed656e816f](https://bsd-hardware.info/?probe=ed656e816f) | May 01, 2021 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [6e874538cb](https://bsd-hardware.info/?probe=6e874538cb) | Apr 20, 2021 |
| HP            | 18E7                        | [e6354de524](https://bsd-hardware.info/?probe=e6354de524) | Apr 20, 2021 |
| ASUSTek       | P5G41T-M LX3                | [1759329ae3](https://bsd-hardware.info/?probe=1759329ae3) | Apr 12, 2021 |
| Dell          | 0RW199                      | [e78392bc4c](https://bsd-hardware.info/?probe=e78392bc4c) | Apr 02, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [62376c16a4](https://bsd-hardware.info/?probe=62376c16a4) | Mar 31, 2021 |
| Medion        | H61H2-LM3                   | [6483c8390f](https://bsd-hardware.info/?probe=6483c8390f) | Mar 31, 2021 |
| Pegatron      | IPM41-D3                    | [687047b3d2](https://bsd-hardware.info/?probe=687047b3d2) | Mar 30, 2021 |
| Gigabyte      | Z77X-UD5H                   | [d3742d3898](https://bsd-hardware.info/?probe=d3742d3898) | Mar 29, 2021 |
| Dell          | 0NW6H5 A00                  | [1499695aae](https://bsd-hardware.info/?probe=1499695aae) | Mar 25, 2021 |
| HP            | 18E7                        | [0e835b61ff](https://bsd-hardware.info/?probe=0e835b61ff) | Mar 24, 2021 |
| ASRock        | H71M-DGS                    | [d05d6281d3](https://bsd-hardware.info/?probe=d05d6281d3) | Mar 21, 2021 |
| HP            | 1825                        | [15e822a4dc](https://bsd-hardware.info/?probe=15e822a4dc) | Mar 20, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [f9c3fc3b84](https://bsd-hardware.info/?probe=f9c3fc3b84) | Mar 19, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [5ae508dfa8](https://bsd-hardware.info/?probe=5ae508dfa8) | Mar 19, 2021 |
| Pegatron      | IPM41-D3                    | [fdfc8e2b9b](https://bsd-hardware.info/?probe=fdfc8e2b9b) | Mar 17, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [9f780aff14](https://bsd-hardware.info/?probe=9f780aff14) | Mar 16, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [83aacceb4c](https://bsd-hardware.info/?probe=83aacceb4c) | Mar 16, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [adb0e59aa1](https://bsd-hardware.info/?probe=adb0e59aa1) | Mar 15, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [8964a02114](https://bsd-hardware.info/?probe=8964a02114) | Mar 15, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [0a3b290f9f](https://bsd-hardware.info/?probe=0a3b290f9f) | Mar 15, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [1c30f7523f](https://bsd-hardware.info/?probe=1c30f7523f) | Mar 15, 2021 |
| ASUSTek       | PRIME B350M-A               | [416039a620](https://bsd-hardware.info/?probe=416039a620) | Mar 13, 2021 |
| ASUSTek       | BM6AD_BM1AD_BP1AD           | [60dedd3dcc](https://bsd-hardware.info/?probe=60dedd3dcc) | Mar 13, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [436706f322](https://bsd-hardware.info/?probe=436706f322) | Mar 12, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [002e54c256](https://bsd-hardware.info/?probe=002e54c256) | Mar 12, 2021 |
| Dell          | 0HN7XN A01                  | [3339a68c44](https://bsd-hardware.info/?probe=3339a68c44) | Mar 12, 2021 |
| ASUSTek       | H110M-PLUS                  | [80e7c230d7](https://bsd-hardware.info/?probe=80e7c230d7) | Mar 12, 2021 |
| Dell          | 0W2PJY A01                  | [f162510a27](https://bsd-hardware.info/?probe=f162510a27) | Mar 12, 2021 |
| MSI           | B150M PRO-VDH               | [bc75a3ab13](https://bsd-hardware.info/?probe=bc75a3ab13) | Mar 11, 2021 |
| ASUSTek       | H110M-PLUS                  | [cf00023cef](https://bsd-hardware.info/?probe=cf00023cef) | Mar 11, 2021 |
| ASRock        | B450M Pro4                  | [e9ca160a2d](https://bsd-hardware.info/?probe=e9ca160a2d) | Mar 11, 2021 |
| ASUSTek       | M4A78                       | [00dc46f0a1](https://bsd-hardware.info/?probe=00dc46f0a1) | Mar 10, 2021 |
| Gigabyte      | 970A-DS3P                   | [47d17e6983](https://bsd-hardware.info/?probe=47d17e6983) | Mar 10, 2021 |
| Dell          | 0JP3NX A01                  | [fc94b8c422](https://bsd-hardware.info/?probe=fc94b8c422) | Mar 09, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [66a223add9](https://bsd-hardware.info/?probe=66a223add9) | Mar 08, 2021 |
| ASUSTek       | PRIME B350M-A               | [b79872a08e](https://bsd-hardware.info/?probe=b79872a08e) | Mar 07, 2021 |
| ASUSTek       | P8Z77-V                     | [88ee81b089](https://bsd-hardware.info/?probe=88ee81b089) | Mar 06, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | [a03927cc2e](https://bsd-hardware.info/?probe=a03927cc2e) | Mar 06, 2021 |
| Medion        | H61H2-LM3                   | [01df19257a](https://bsd-hardware.info/?probe=01df19257a) | Mar 05, 2021 |
| Gigabyte      | Z77M-D3H                    | [2f1e8f315f](https://bsd-hardware.info/?probe=2f1e8f315f) | Mar 05, 2021 |
| VeryPC        | S400                        | [77b744169b](https://bsd-hardware.info/?probe=77b744169b) | Mar 04, 2021 |
| ASRock        | 970A-G                      | [3e474f93cf](https://bsd-hardware.info/?probe=3e474f93cf) | Mar 04, 2021 |
| Dell          | 0W2PJY A01                  | [d8c2f0b19f](https://bsd-hardware.info/?probe=d8c2f0b19f) | Mar 04, 2021 |
| Gigabyte      | Z87-D3HP-CF                 | [4c2d7f9b3b](https://bsd-hardware.info/?probe=4c2d7f9b3b) | Mar 03, 2021 |
| Foxconn       | 2ADA                        | [10d02d0982](https://bsd-hardware.info/?probe=10d02d0982) | Mar 03, 2021 |
| HP            | 339A                        | [6b1072ee33](https://bsd-hardware.info/?probe=6b1072ee33) | Mar 01, 2021 |
| HP            | 18E7                        | [091b80c404](https://bsd-hardware.info/?probe=091b80c404) | Mar 01, 2021 |
| ASRock        | AB350 Pro4                  | [8e0afc66b5](https://bsd-hardware.info/?probe=8e0afc66b5) | Feb 26, 2021 |
| ASRock        | H61M-VG3                    | [68d5d3c6cd](https://bsd-hardware.info/?probe=68d5d3c6cd) | Feb 26, 2021 |
| ASUSTek       | P8Z77-V LX2                 | [0aeea0fec9](https://bsd-hardware.info/?probe=0aeea0fec9) | Feb 23, 2021 |
| ASUSTek       | P5Q                         | [22fa0d8178](https://bsd-hardware.info/?probe=22fa0d8178) | Feb 23, 2021 |
| Intel         | H61                         | [a8ae96a0ab](https://bsd-hardware.info/?probe=a8ae96a0ab) | Feb 23, 2021 |
| ASUSTek       | P8Z77-V LX                  | [8390039d0b](https://bsd-hardware.info/?probe=8390039d0b) | Feb 22, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [58c6bf426e](https://bsd-hardware.info/?probe=58c6bf426e) | Feb 22, 2021 |
| MSI           | A78M-E35                    | [0a1462e4a7](https://bsd-hardware.info/?probe=0a1462e4a7) | Feb 22, 2021 |
| Dell          | 0M863N A01                  | [8dd5cd14a9](https://bsd-hardware.info/?probe=8dd5cd14a9) | Feb 22, 2021 |
| Biostar       | B365MHC                     | [adb029c65f](https://bsd-hardware.info/?probe=adb029c65f) | Feb 22, 2021 |
| Gigabyte      | Z77M-D3H                    | [d0b9e29aed](https://bsd-hardware.info/?probe=d0b9e29aed) | Feb 21, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [405b36b911](https://bsd-hardware.info/?probe=405b36b911) | Feb 21, 2021 |
| Dell          | 0RW199                      | [e0ecb4caa7](https://bsd-hardware.info/?probe=e0ecb4caa7) | Feb 21, 2021 |
| ASUSTek       | P5B-Deluxe                  | [a471763f19](https://bsd-hardware.info/?probe=a471763f19) | Feb 20, 2021 |
| ASUSTek       | PRIME H310M-A               | [cda0bac40d](https://bsd-hardware.info/?probe=cda0bac40d) | Feb 20, 2021 |
| Gigabyte      | GA-870-UD3P                 | [e228db2983](https://bsd-hardware.info/?probe=e228db2983) | Feb 20, 2021 |
| Dell          | 0M863N A01                  | [94f2627d79](https://bsd-hardware.info/?probe=94f2627d79) | Feb 20, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [d60f06a51d](https://bsd-hardware.info/?probe=d60f06a51d) | Feb 20, 2021 |
| ASRock        | 970 Extreme3                | [daa7afc688](https://bsd-hardware.info/?probe=daa7afc688) | Feb 19, 2021 |
| ASUSTek       | PRIME H270-PLUS             | [0b5194e68e](https://bsd-hardware.info/?probe=0b5194e68e) | Feb 19, 2021 |
| ASRock        | Z170 Pro4/D3                | [7df0653726](https://bsd-hardware.info/?probe=7df0653726) | Feb 19, 2021 |
| Unknown       | Unknown                     | [22af66ce96](https://bsd-hardware.info/?probe=22af66ce96) | Feb 18, 2021 |
| ASRock        | B365M Pro4                  | [1c438d977e](https://bsd-hardware.info/?probe=1c438d977e) | Feb 18, 2021 |
| HARDKERNEL    | ODROID-H2                   | [6fe9279f1f](https://bsd-hardware.info/?probe=6fe9279f1f) | Feb 18, 2021 |
| Fujitsu       | D3517-A1 S26361-D3517-A1    | [8891e427e1](https://bsd-hardware.info/?probe=8891e427e1) | Feb 17, 2021 |
| Dell          | 0GM819                      | [836d0f9057](https://bsd-hardware.info/?probe=836d0f9057) | Feb 17, 2021 |
| ASUSTek       | P8H61-MX R2.0               | [e601d28f5e](https://bsd-hardware.info/?probe=e601d28f5e) | Feb 17, 2021 |
| Lenovo        | NO DPK                      | [1ec71f814b](https://bsd-hardware.info/?probe=1ec71f814b) | Feb 17, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [b087324f05](https://bsd-hardware.info/?probe=b087324f05) | Feb 17, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [d03a5bbea5](https://bsd-hardware.info/?probe=d03a5bbea5) | Feb 17, 2021 |
| Lenovo        | ThinkServer TS140           | [29fb200d1a](https://bsd-hardware.info/?probe=29fb200d1a) | Feb 17, 2021 |
| Pegatron      | IPM41-D3                    | [ffc1292c18](https://bsd-hardware.info/?probe=ffc1292c18) | Feb 16, 2021 |
| Lenovo        | Board                       | [966a037b6d](https://bsd-hardware.info/?probe=966a037b6d) | Feb 16, 2021 |
| Gigabyte      | F2A88XM-D3H                 | [c112c8a9fe](https://bsd-hardware.info/?probe=c112c8a9fe) | Feb 16, 2021 |
| MSI           | G41M-P25                    | [3e037419d7](https://bsd-hardware.info/?probe=3e037419d7) | Feb 16, 2021 |
| Pegatron      | IPM41-D3                    | [6e5c330c9c](https://bsd-hardware.info/?probe=6e5c330c9c) | Feb 16, 2021 |
| ASUSTek       | VM62                        | [4d02a33fec](https://bsd-hardware.info/?probe=4d02a33fec) | Feb 16, 2021 |
| Gigabyte      | B360N WIFI-CF               | [0a48ee3b16](https://bsd-hardware.info/?probe=0a48ee3b16) | Feb 16, 2021 |
| Google        | Guado                       | [f6473eeb71](https://bsd-hardware.info/?probe=f6473eeb71) | Feb 16, 2021 |
| ASUSTek       | P5B SE                      | [425210021c](https://bsd-hardware.info/?probe=425210021c) | Feb 16, 2021 |
| HP            | 8768 A                      | [f2be4b7b65](https://bsd-hardware.info/?probe=f2be4b7b65) | Feb 16, 2021 |
| ASUSTek       | P5E-VM SE                   | [89fbf4a403](https://bsd-hardware.info/?probe=89fbf4a403) | Feb 16, 2021 |
| Dell          | 0HY9JP A00                  | [ddabefae47](https://bsd-hardware.info/?probe=ddabefae47) | Feb 15, 2021 |
| HP            | 304Bh                       | [ebd3736a78](https://bsd-hardware.info/?probe=ebd3736a78) | Feb 15, 2021 |
| Intel         | DN2820FYK H24582-201        | [be56203e79](https://bsd-hardware.info/?probe=be56203e79) | Feb 15, 2021 |
| Gigabyte      | B450M DS3H-CF               | [9181a2479b](https://bsd-hardware.info/?probe=9181a2479b) | Feb 15, 2021 |
| HP            | 2B3C                        | [6c628d33ab](https://bsd-hardware.info/?probe=6c628d33ab) | Feb 15, 2021 |
| ASUSTek       | EX-B85M-V                   | [54c319f2c0](https://bsd-hardware.info/?probe=54c319f2c0) | Feb 15, 2021 |
| ASRock        | B450M Pro4                  | [ef29c46355](https://bsd-hardware.info/?probe=ef29c46355) | Feb 15, 2021 |
| HP            | 81B4 01                     | [1bf2cb9506](https://bsd-hardware.info/?probe=1bf2cb9506) | Feb 15, 2021 |
| ASRock        | A300M-STX                   | [9d7266ffc2](https://bsd-hardware.info/?probe=9d7266ffc2) | Feb 15, 2021 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | [02f241b7d7](https://bsd-hardware.info/?probe=02f241b7d7) | Feb 14, 2021 |
| Gigabyte      | Z68X-UD3H-B3                | [290991af1f](https://bsd-hardware.info/?probe=290991af1f) | Feb 14, 2021 |
| ASRock        | B550M Pro4                  | [61a5641019](https://bsd-hardware.info/?probe=61a5641019) | Feb 14, 2021 |
| Gigabyte      | Z97M-D3H                    | [a335917871](https://bsd-hardware.info/?probe=a335917871) | Feb 14, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [c996e74ebc](https://bsd-hardware.info/?probe=c996e74ebc) | Feb 14, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [8082fefc2e](https://bsd-hardware.info/?probe=8082fefc2e) | Feb 14, 2021 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [94167310ae](https://bsd-hardware.info/?probe=94167310ae) | Feb 14, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [565ceb36f0](https://bsd-hardware.info/?probe=565ceb36f0) | Feb 14, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [694204751b](https://bsd-hardware.info/?probe=694204751b) | Feb 13, 2021 |
| Dell          | 0PC5F7 A01                  | [f1e8c08e31](https://bsd-hardware.info/?probe=f1e8c08e31) | Feb 13, 2021 |
| ASUSTek       | Z170-K                      | [aa525de283](https://bsd-hardware.info/?probe=aa525de283) | Feb 13, 2021 |
| Gigabyte      | Z68X-UD3H-B3                | [a2040528cc](https://bsd-hardware.info/?probe=a2040528cc) | Feb 13, 2021 |
| Dell          | 06NWYK A00                  | [32acfb4467](https://bsd-hardware.info/?probe=32acfb4467) | Feb 13, 2021 |
| ASUSTek       | H61M-E                      | [98b498ddb0](https://bsd-hardware.info/?probe=98b498ddb0) | Feb 13, 2021 |
| ASUSTek       | P8H61-M LE                  | [b861820636](https://bsd-hardware.info/?probe=b861820636) | Feb 13, 2021 |
| Dell          | 0KWVT8 A03                  | [289b3114ec](https://bsd-hardware.info/?probe=289b3114ec) | Feb 13, 2021 |
| Dell          | 06NWYK A00                  | [2ff05af403](https://bsd-hardware.info/?probe=2ff05af403) | Feb 13, 2021 |
| ASUSTek       | P8H61-M LE                  | [3a3d7d0701](https://bsd-hardware.info/?probe=3a3d7d0701) | Feb 12, 2021 |
| Google        | Panther                     | [1d1512889f](https://bsd-hardware.info/?probe=1d1512889f) | Feb 12, 2021 |
| HP            | 339A                        | [18b86b645a](https://bsd-hardware.info/?probe=18b86b645a) | Feb 12, 2021 |
| Gigabyte      | Z87-D3HP-CF                 | [64551b8203](https://bsd-hardware.info/?probe=64551b8203) | Feb 12, 2021 |
| HP            | 2B17                        | [572bf634a8](https://bsd-hardware.info/?probe=572bf634a8) | Feb 12, 2021 |
| HP            | 8055                        | [8ecc5bbb55](https://bsd-hardware.info/?probe=8ecc5bbb55) | Feb 12, 2021 |
| ASUSTek       | PRIME B450M-A               | [ac6b550ff4](https://bsd-hardware.info/?probe=ac6b550ff4) | Feb 12, 2021 |
| Lenovo        | MAHOBAY                     | [bacae1ddbb](https://bsd-hardware.info/?probe=bacae1ddbb) | Feb 12, 2021 |
| ASUSTek       | P8H77-V                     | [aaaffba650](https://bsd-hardware.info/?probe=aaaffba650) | Feb 11, 2021 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | [5965bc8a1d](https://bsd-hardware.info/?probe=5965bc8a1d) | Feb 11, 2021 |
| MSI           | PRESTIGE X570 CREATION      | [261aa9d7ab](https://bsd-hardware.info/?probe=261aa9d7ab) | Feb 11, 2021 |
| Intel         | DG41RQ AAE54511-203         | [e0f72bc85e](https://bsd-hardware.info/?probe=e0f72bc85e) | Feb 11, 2021 |
| Intel         | DG41RQ AAE54511-203         | [3030d78460](https://bsd-hardware.info/?probe=3030d78460) | Feb 11, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | [3a6a5a66f7](https://bsd-hardware.info/?probe=3a6a5a66f7) | Feb 11, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [a49ff2b77a](https://bsd-hardware.info/?probe=a49ff2b77a) | Feb 11, 2021 |
| ASUSTek       | M5A78L-M LX PLUS            | [f19ced0784](https://bsd-hardware.info/?probe=f19ced0784) | Feb 11, 2021 |
| Medion        | H81H3-EM2 H81EM2W08.308     | [9958f514c9](https://bsd-hardware.info/?probe=9958f514c9) | Feb 10, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [b507d43de5](https://bsd-hardware.info/?probe=b507d43de5) | Feb 10, 2021 |
| Gigabyte      | B150M-D3H-CF                | [cba616392a](https://bsd-hardware.info/?probe=cba616392a) | Feb 10, 2021 |
| ASRock        | H270M Pro4                  | [37af53e334](https://bsd-hardware.info/?probe=37af53e334) | Feb 10, 2021 |
| Acer          | Aspire X1700                | [06dc1753ef](https://bsd-hardware.info/?probe=06dc1753ef) | Feb 10, 2021 |
| Acer          | Aspire X1700                | [6886acf351](https://bsd-hardware.info/?probe=6886acf351) | Feb 10, 2021 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | [6fdcef7c9e](https://bsd-hardware.info/?probe=6fdcef7c9e) | Feb 10, 2021 |
| MSI           | Z87-G41 PC Mate             | [23fc631dec](https://bsd-hardware.info/?probe=23fc631dec) | Feb 10, 2021 |
| Gigabyte      | Z97P-D3                     | [a3bd8f5772](https://bsd-hardware.info/?probe=a3bd8f5772) | Feb 10, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [9517fd0273](https://bsd-hardware.info/?probe=9517fd0273) | Feb 10, 2021 |
| Dell          | 0PC5F7 A01                  | [f045556287](https://bsd-hardware.info/?probe=f045556287) | Feb 09, 2021 |
| ASUSTek       | PRIME X470-PRO              | [a77e980850](https://bsd-hardware.info/?probe=a77e980850) | Feb 09, 2021 |
| ASRock        | A320M-DGS                   | [7c179e0033](https://bsd-hardware.info/?probe=7c179e0033) | Feb 06, 2021 |
| Dell          | 096JG8 A00                  | [e73a728a76](https://bsd-hardware.info/?probe=e73a728a76) | Feb 03, 2021 |
| Dell          | 096JG8 A00                  | [612272e598](https://bsd-hardware.info/?probe=612272e598) | Feb 03, 2021 |
| Acer          | EM61SM/EM61PM               | [b82613052e](https://bsd-hardware.info/?probe=b82613052e) | Jan 27, 2021 |
| ASRock        | X399 Taichi                 | [875e6714ca](https://bsd-hardware.info/?probe=875e6714ca) | Jan 27, 2021 |
| Acer          | RevoOne RL85                | [6cbf99ef86](https://bsd-hardware.info/?probe=6cbf99ef86) | Jan 26, 2021 |
| Acer          | RevoOne RL85                | [ce03b7b713](https://bsd-hardware.info/?probe=ce03b7b713) | Jan 23, 2021 |
| Dell          | 088DT1 A01                  | [fcc759e013](https://bsd-hardware.info/?probe=fcc759e013) | Jan 21, 2021 |
| ASUSTek       | VM40B                       | [58b6a3291e](https://bsd-hardware.info/?probe=58b6a3291e) | Jan 21, 2021 |
| Dell          | 0Y7WYT A00                  | [4af9b92154](https://bsd-hardware.info/?probe=4af9b92154) | Jan 19, 2021 |
| MSI           | Boston                      | [aa9d7bae21](https://bsd-hardware.info/?probe=aa9d7bae21) | Jan 17, 2021 |
| MSI           | Boston                      | [f21954fa35](https://bsd-hardware.info/?probe=f21954fa35) | Jan 17, 2021 |
| Gigabyte      | TRX40 DESIGNARE             | [f506b21449](https://bsd-hardware.info/?probe=f506b21449) | Jan 17, 2021 |
| Dell          | 0M863N A01                  | [4feae8b20d](https://bsd-hardware.info/?probe=4feae8b20d) | Jan 15, 2021 |
| ASUSTek       | Z170-A                      | [271f2c1186](https://bsd-hardware.info/?probe=271f2c1186) | Jan 12, 2021 |
| Acer          | RevoOne RL85                | [259c54d264](https://bsd-hardware.info/?probe=259c54d264) | Jan 02, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/helloSystem/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| helloSystem 0.7.0   | 182      | 36.62%  |
| helloSystem 0.5.0   | 115      | 23.14%  |
| helloSystem 0.4.0   | 90       | 18.11%  |
| helloSystem 0.6.0   | 60       | 12.07%  |
| helloSystem 0.8.0   | 38       | 7.65%   |
| helloSystem 0.3.0   | 9        | 1.81%   |
| helloSystem 13.1-p2 | 2        | 0.4%    |
| helloSystem 13.1    | 1        | 0.2%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| helloSystem | 466      | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 466      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 464      | 99.15%  |
| GNOME        | 2        | 0.43%   |
| XFCE         | 1        | 0.21%   |
| Cinnamon     | 1        | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 466      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SLiM    | 464      | 99.36%  |
| Console | 2        | 0.43%   |
| GDM     | 1        | 0.21%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 453      | 96.59%  |
| es_ES | 5        | 1.07%   |
| C     | 4        | 0.85%   |
| fr_FR | 2        | 0.43%   |
| zh_TW | 1        | 0.21%   |
| it_IT | 1        | 0.21%   |
| fr    | 1        | 0.21%   |
| es_AR | 1        | 0.21%   |
| de_DE | 1        | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 423      | 90.19%  |
| BIOS | 46       | 9.81%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Zfs    | 342      | 70.66%  |
| Cd9660 | 141      | 29.13%  |
| Ufs    | 1        | 0.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 461      | 98.93%  |
| MBR  | 5        | 1.07%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 128      | 27.47%  |
| Gigabyte Technology | 67       | 14.38%  |
| Dell                | 45       | 9.66%   |
| ASRock              | 45       | 9.66%   |
| Hewlett-Packard     | 44       | 9.44%   |
| MSI                 | 28       | 6.01%   |
| Lenovo              | 22       | 4.72%   |
| Intel               | 17       | 3.65%   |
| Pegatron            | 7        | 1.5%    |
| Acer                | 7        | 1.5%    |
| Biostar             | 6        | 1.29%   |
| Apple               | 6        | 1.29%   |
| Fujitsu             | 4        | 0.86%   |
| Foxconn             | 4        | 0.86%   |
| Unknown             | 4        | 0.86%   |
| Shuttle             | 3        | 0.64%   |
| Medion              | 2        | 0.43%   |
| Google              | 2        | 0.43%   |
| VeryPC              | 1        | 0.21%   |
| T-bao               | 1        | 0.21%   |
| Supermicro          | 1        | 0.21%   |
| Sapphire            | 1        | 0.21%   |
| Quanta              | 1        | 0.21%   |
| QIYIDA              | 1        | 0.21%   |
| Protectli           | 1        | 0.21%   |
| Positivo            | 1        | 0.21%   |
| PCPartner           | 1        | 0.21%   |
| Packard Bell        | 1        | 0.21%   |
| OEM                 | 1        | 0.21%   |
| MAXSUN              | 1        | 0.21%   |
| MACHINIST           | 1        | 0.21%   |
| Koloe               | 1        | 0.21%   |
| Itautec             | 1        | 0.21%   |
| Huanan              | 1        | 0.21%   |
| HC                  | 1        | 0.21%   |
| HARDKERNEL          | 1        | 0.21%   |
| Gateway             | 1        | 0.21%   |
| EVGA                | 1        | 0.21%   |
| ECS                 | 1        | 0.21%   |
| BESSTAR Tech        | 1        | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 7        | 1.5%    |
| Apple MacPro5,1              | 5        | 1.07%   |
| Unknown                      | 4        | 0.86%   |
| Intel H61                    | 3        | 0.64%   |
| HP Compaq Elite 8300 SFF     | 3        | 0.64%   |
| Dell OptiPlex 9020           | 3        | 0.64%   |
| ASUS PRIME A320M-K           | 3        | 0.64%   |
| ASUS P8Z77-V LX              | 3        | 0.64%   |
| ASUS M5A78L-M/USB3           | 3        | 0.64%   |
| Pegatron IPM41-D3            | 2        | 0.43%   |
| MSI MS-7C37                  | 2        | 0.43%   |
| MSI MS-7B86                  | 2        | 0.43%   |
| MSI MS-7A38                  | 2        | 0.43%   |
| MSI MS-7592                  | 2        | 0.43%   |
| HP ProDesk 600 G2 DM         | 2        | 0.43%   |
| HP ProDesk 600 G1 SFF        | 2        | 0.43%   |
| HP EliteDesk 800 G2 SFF      | 2        | 0.43%   |
| HP EliteDesk 800 G2 DM 35W   | 2        | 0.43%   |
| HP EliteDesk 800 G1 DM       | 2        | 0.43%   |
| HP EliteDesk 700 G1 SFF      | 2        | 0.43%   |
| HP Compaq 8100 Elite CMT PC  | 2        | 0.43%   |
| Gigabyte X570 AORUS ELITE    | 2        | 0.43%   |
| Gigabyte F2A88XM-D3H         | 2        | 0.43%   |
| Gigabyte B450 AORUS M        | 2        | 0.43%   |
| Gigabyte 970A-DS3P           | 2        | 0.43%   |
| Dell Precision T1700         | 2        | 0.43%   |
| Dell OptiPlex 990            | 2        | 0.43%   |
| Dell OptiPlex 960            | 2        | 0.43%   |
| Dell OptiPlex 760            | 2        | 0.43%   |
| Dell OptiPlex 755            | 2        | 0.43%   |
| Dell OptiPlex 7040           | 2        | 0.43%   |
| Dell OptiPlex 7010           | 2        | 0.43%   |
| Biostar B365MHC              | 2        | 0.43%   |
| ASUS TUF GAMING X570-PLUS    | 2        | 0.43%   |
| ASUS ROG STRIX B450-F GAMING | 2        | 0.43%   |
| ASUS PRIME X570-P            | 2        | 0.43%   |
| ASUS PRIME B450M-A           | 2        | 0.43%   |
| ASUS PRIME B350M-A           | 2        | 0.43%   |
| ASUS P5P43TD PRO             | 2        | 0.43%   |
| ASUS P5E-VM SE               | 2        | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 27       | 5.79%   |
| ASUS PRIME           | 18       | 3.86%   |
| Lenovo ThinkCentre   | 16       | 3.43%   |
| ASUS ROG             | 14       | 3%      |
| HP Compaq            | 12       | 2.58%   |
| HP EliteDesk         | 10       | 2.15%   |
| Dell Precision       | 8        | 1.72%   |
| ASUS TUF             | 7        | 1.5%    |
| ASUS All             | 7        | 1.5%    |
| HP ProDesk           | 6        | 1.29%   |
| ASUS P8Z77-V         | 6        | 1.29%   |
| ASUS M5A78L-M        | 6        | 1.29%   |
| Apple MacPro5        | 5        | 1.07%   |
| Gigabyte X570        | 4        | 0.86%   |
| Gigabyte B450        | 4        | 0.86%   |
| Dell Inspiron        | 4        | 0.86%   |
| ASUS Crosshair       | 4        | 0.86%   |
| Acer Aspire          | 4        | 0.86%   |
| Unknown              | 4        | 0.86%   |
| Intel H61            | 3        | 0.64%   |
| Pegatron IPM41-D3    | 2        | 0.43%   |
| Pegatron Compaq      | 2        | 0.43%   |
| MSI MS-7C37          | 2        | 0.43%   |
| MSI MS-7B86          | 2        | 0.43%   |
| MSI MS-7A38          | 2        | 0.43%   |
| MSI MS-7592          | 2        | 0.43%   |
| Lenovo ThinkStation  | 2        | 0.43%   |
| HP Slim              | 2        | 0.43%   |
| HP Pavilion          | 2        | 0.43%   |
| HP Desktop           | 2        | 0.43%   |
| Gigabyte F2A88XM-D3H | 2        | 0.43%   |
| Gigabyte B450M       | 2        | 0.43%   |
| Gigabyte 970A-DS3P   | 2        | 0.43%   |
| Fujitsu ESPRIMO      | 2        | 0.43%   |
| Dell Studio          | 2        | 0.43%   |
| Biostar B365MHC      | 2        | 0.43%   |
| ASUS P8H61-M         | 2        | 0.43%   |
| ASUS P7H55-M         | 2        | 0.43%   |
| ASUS P5Q             | 2        | 0.43%   |
| ASUS P5P43TD         | 2        | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 52       | 11.16%  |
| 2019 | 49       | 10.52%  |
| 2012 | 46       | 9.87%   |
| 2020 | 43       | 9.23%   |
| 2013 | 43       | 9.23%   |
| 2014 | 37       | 7.94%   |
| 2021 | 35       | 7.51%   |
| 2010 | 34       | 7.3%    |
| 2016 | 23       | 4.94%   |
| 2011 | 22       | 4.72%   |
| 2017 | 19       | 4.08%   |
| 2015 | 19       | 4.08%   |
| 2009 | 18       | 3.86%   |
| 2008 | 13       | 2.79%   |
| 2007 | 9        | 1.93%   |
| 2022 | 4        | 0.86%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 466      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 464      | 99.57%  |
| Yes  | 2        | 0.43%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 138      | 29.55%  |
| 8.01-16.0   | 135      | 28.91%  |
| 4.01-8.0    | 101      | 21.63%  |
| 32.01-64.0  | 62       | 13.28%  |
| 64.01-256.0 | 14       | 3%      |
| 2.01-3.0    | 7        | 1.5%    |
| 24.01-32.0  | 6        | 1.28%   |
| 0.51-1.0    | 2        | 0.43%   |
| 3.01-4.0    | 1        | 0.21%   |
| 1.01-2.0    | 1        | 0.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 207      | 44.04%  |
| 0.51-1.0  | 164      | 34.89%  |
| 1.01-2.0  | 81       | 17.23%  |
| 2.01-3.0  | 11       | 2.34%   |
| 3.01-4.0  | 4        | 0.85%   |
| 4.01-8.0  | 2        | 0.43%   |
| 8.01-16.0 | 1        | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 216      | 44.63%  |
| 2      | 120      | 24.79%  |
| 3      | 62       | 12.81%  |
| 4      | 39       | 8.06%   |
| 0      | 21       | 4.34%   |
| 5      | 11       | 2.27%   |
| 6      | 10       | 2.07%   |
| 7      | 2        | 0.41%   |
| 10     | 1        | 0.21%   |
| 9      | 1        | 0.21%   |
| 8      | 1        | 0.21%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 295      | 63.17%  |
| Yes       | 172      | 36.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 458      | 98.28%  |
| No        | 8        | 1.72%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 324      | 69.23%  |
| Yes       | 144      | 30.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 348      | 74.2%   |
| Yes       | 121      | 25.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 67       | 14.38%  |
| Russia       | 51       | 10.94%  |
| Germany      | 39       | 8.37%   |
| Brazil       | 25       | 5.36%   |
| UK           | 22       | 4.72%   |
| Spain        | 22       | 4.72%   |
| Canada       | 20       | 4.29%   |
| Italy        | 17       | 3.65%   |
| China        | 17       | 3.65%   |
| Ukraine      | 14       | 3%      |
| Poland       | 14       | 3%      |
| France       | 14       | 3%      |
| Taiwan       | 11       | 2.36%   |
| Australia    | 11       | 2.36%   |
| Mexico       | 10       | 2.15%   |
| Hungary      | 10       | 2.15%   |
| India        | 9        | 1.93%   |
| South Korea  | 6        | 1.29%   |
| Turkey       | 5        | 1.07%   |
| Argentina    | 5        | 1.07%   |
| Venezuela    | 4        | 0.86%   |
| Peru         | 4        | 0.86%   |
| Norway       | 4        | 0.86%   |
| Finland      | 4        | 0.86%   |
| Switzerland  | 3        | 0.64%   |
| South Africa | 3        | 0.64%   |
| Romania      | 3        | 0.64%   |
| Portugal     | 3        | 0.64%   |
| Netherlands  | 3        | 0.64%   |
| Guatemala    | 3        | 0.64%   |
| Greece       | 3        | 0.64%   |
| Chile        | 3        | 0.64%   |
| Thailand     | 2        | 0.43%   |
| Sweden       | 2        | 0.43%   |
| Slovenia     | 2        | 0.43%   |
| Serbia       | 2        | 0.43%   |
| New Zealand  | 2        | 0.43%   |
| Egypt        | 2        | 0.43%   |
| Denmark      | 2        | 0.43%   |
| Bulgaria     | 2        | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 7        | 1.42%   |
| St Petersburg     | 6        | 1.22%   |
| Paris             | 5        | 1.02%   |
| Kyiv              | 4        | 0.81%   |
| Aquan             | 4        | 0.81%   |
| Temple            | 3        | 0.61%   |
| SГЈo Paulo      | 3        | 0.61%   |
| Munich            | 3        | 0.61%   |
| Lima              | 3        | 0.61%   |
| Guatemala City    | 3        | 0.61%   |
| Chelyabinsk       | 3        | 0.61%   |
| Calgary           | 3        | 0.61%   |
| Brisbane          | 3        | 0.61%   |
| Barnaul           | 3        | 0.61%   |
| Zhengzhou         | 2        | 0.41%   |
| Yekaterinburg     | 2        | 0.41%   |
| Voronezh          | 2        | 0.41%   |
| Volgograd         | 2        | 0.41%   |
| Ufa               | 2        | 0.41%   |
| Surgut            | 2        | 0.41%   |
| Stuttgart         | 2        | 0.41%   |
| Stourbridge       | 2        | 0.41%   |
| Stavropol         | 2        | 0.41%   |
| St. Jean Baptiste | 2        | 0.41%   |
| Sheffield         | 2        | 0.41%   |
| Seville           | 2        | 0.41%   |
| Sevastopol        | 2        | 0.41%   |
| Sao Paulo         | 2        | 0.41%   |
| Santiago          | 2        | 0.41%   |
| Rudersberg        | 2        | 0.41%   |
| Pflugerville      | 2        | 0.41%   |
| Perth             | 2        | 0.41%   |
| Myrtle Beach      | 2        | 0.41%   |
| Melbourne         | 2        | 0.41%   |
| Marlborough       | 2        | 0.41%   |
| Madrid            | 2        | 0.41%   |
| Krasnodar         | 2        | 0.41%   |
| Kitchener         | 2        | 0.41%   |
| Kharkiv           | 2        | 0.41%   |
| Istanbul          | 2        | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 154      | 223    | 20%     |
| Seagate             | 146      | 216    | 18.96%  |
| Samsung Electronics | 118      | 181    | 15.32%  |
| Kingston            | 46       | 58     | 5.97%   |
| Toshiba             | 44       | 56     | 5.71%   |
| Crucial             | 40       | 60     | 5.19%   |
| Hitachi             | 30       | 38     | 3.9%    |
| SanDisk             | 26       | 30     | 3.38%   |
| A-DATA Technology   | 16       | 24     | 2.08%   |
| Intel               | 15       | 15     | 1.95%   |
| SPCC                | 9        | 10     | 1.17%   |
| HGST                | 9        | 9      | 1.17%   |
| Phison              | 8        | 11     | 1.04%   |
| Goodram             | 8        | 9      | 1.04%   |
| SK hynix            | 7        | 10     | 0.91%   |
| PNY                 | 7        | 18     | 0.91%   |
| Gigabyte Technology | 6        | 8      | 0.78%   |
| Patriot             | 5        | 5      | 0.65%   |
| OCZ                 | 5        | 6      | 0.65%   |
| Hewlett-Packard     | 5        | 5      | 0.65%   |
| Corsair             | 5        | 5      | 0.65%   |
| Silicon Motion      | 4        | 5      | 0.52%   |
| KingSpec            | 4        | 6      | 0.52%   |
| Apple               | 4        | 5      | 0.52%   |
| Apacer              | 4        | 4      | 0.52%   |
| XPG                 | 3        | 3      | 0.39%   |
| Micron Technology   | 3        | 3      | 0.39%   |
| Intenso             | 3        | 4      | 0.39%   |
| Transcend           | 2        | 2      | 0.26%   |
| Team                | 2        | 2      | 0.26%   |
| Smartbuy            | 2        | 2      | 0.26%   |
| Plextor             | 2        | 2      | 0.26%   |
| LITEONIT            | 2        | 2      | 0.26%   |
| LITEON              | 2        | 3      | 0.26%   |
| Fujitsu             | 2        | 3      | 0.26%   |
| EMTEC               | 2        | 4      | 0.26%   |
| China               | 2        | 2      | 0.26%   |
| XrayDisk            | 1        | 1      | 0.13%   |
| Verbatim            | 1        | 1      | 0.13%   |
| tigo                | 1        | 1      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST1000DM003-1ER162 1TB      | 10       | 1.12%   |
| Samsung SSD 860 EVO 500GB           | 10       | 1.12%   |
| Samsung SSD 850 EVO 250GB           | 10       | 1.12%   |
| Toshiba DT01ACA100 1TB              | 9        | 1.01%   |
| Seagate ST500DM002-1BD142 500GB     | 9        | 1.01%   |
| Crucial CT500MX500SSD1 500GB        | 9        | 1.01%   |
| Seagate ST1000DM010-2EP102 1TB      | 8        | 0.9%    |
| Samsung SSD 970 EVO Plus 500GB      | 7        | 0.79%   |
| Samsung SSD 860 EVO 250GB           | 7        | 0.79%   |
| Samsung HD322HJ 320GB               | 7        | 0.79%   |
| Kingston SA400S37240G 240GB         | 7        | 0.79%   |
| Kingston SA400S37120G 120GB         | 7        | 0.79%   |
| Seagate ST2000DM008-2FR102 2TB      | 6        | 0.67%   |
| Kingston SV300S37A120G 120GB        | 6        | 0.67%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 5        | 0.56%   |
| Samsung SSD 970 EVO 250GB           | 5        | 0.56%   |
| Samsung SSD 860 EVO 1TB             | 5        | 0.56%   |
| Samsung HD103SI 1TB                 | 5        | 0.56%   |
| Crucial CT240BX500SSD1 240GB        | 5        | 0.56%   |
| WDC WDS500G2B0A-00SM50 500GB        | 4        | 0.45%   |
| WDC WDS100T2B0A-00SM50 1TB          | 4        | 0.45%   |
| Toshiba HDWD110 1TB                 | 4        | 0.45%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 4        | 0.45%   |
| Seagate ST4000DM004-2CV104 4TB      | 4        | 0.45%   |
| Seagate ST3500312CS 500GB           | 4        | 0.45%   |
| Seagate ST3250410AS 250GB           | 4        | 0.45%   |
| Seagate ST31000528AS 1TB            | 4        | 0.45%   |
| Seagate ST1000LM035-1RK172 1TB      | 4        | 0.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 4        | 0.45%   |
| Seagate ST1000DM003-1CH162 1TB      | 4        | 0.45%   |
| SanDisk SDSSDA240G 240GB            | 4        | 0.45%   |
| Samsung SSD 980 PRO 1TB             | 4        | 0.45%   |
| Kingston SA2000M8250G 250GB         | 4        | 0.45%   |
| A-DATA SU650 120GB                  | 4        | 0.45%   |
| XPG GAMMIX S11 Pro 256GB            | 3        | 0.34%   |
| WDC WDS240G2G0A-00JH30 240GB        | 3        | 0.34%   |
| WDC WDS100T2B0C-00PXH0 1TB          | 3        | 0.34%   |
| WDC WD10EZEX-08WN4A0 1TB            | 3        | 0.34%   |
| Toshiba DT01ACA050 500GB            | 3        | 0.34%   |
| SPCC Solid State Disk 512GB         | 3        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 146      | 213    | 36.78%  |
| WDC                 | 135      | 183    | 34.01%  |
| Toshiba             | 36       | 44     | 9.07%   |
| Samsung Electronics | 34       | 46     | 8.56%   |
| Hitachi             | 30       | 38     | 7.56%   |
| HGST                | 9        | 9      | 2.27%   |
| Hewlett-Packard     | 2        | 2      | 0.5%    |
| Fujitsu             | 2        | 3      | 0.5%    |
| Maxtor              | 1        | 1      | 0.25%   |
| LSI                 | 1        | 1      | 0.25%   |
| CLOVER              | 1        | 1      | 0.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 60       | 81     | 20.91%  |
| Kingston            | 37       | 47     | 12.89%  |
| Crucial             | 36       | 55     | 12.54%  |
| SanDisk             | 26       | 30     | 9.06%   |
| WDC                 | 17       | 23     | 5.92%   |
| A-DATA Technology   | 13       | 14     | 4.53%   |
| Intel               | 10       | 10     | 3.48%   |
| GOODRAM             | 8        | 9      | 2.79%   |
| Toshiba             | 7        | 11     | 2.44%   |
| SPCC                | 7        | 8      | 2.44%   |
| PNY                 | 7        | 16     | 2.44%   |
| Patriot             | 5        | 5      | 1.74%   |
| OCZ                 | 5        | 6      | 1.74%   |
| KingSpec            | 4        | 6      | 1.39%   |
| Apple               | 4        | 5      | 1.39%   |
| Apacer              | 4        | 4      | 1.39%   |
| Micron Technology   | 3        | 3      | 1.05%   |
| Intenso             | 3        | 4      | 1.05%   |
| Gigabyte Technology | 3        | 4      | 1.05%   |
| Transcend           | 2        | 2      | 0.7%    |
| Smartbuy            | 2        | 2      | 0.7%    |
| Plextor             | 2        | 2      | 0.7%    |
| LITEONIT            | 2        | 2      | 0.7%    |
| LITEON              | 2        | 3      | 0.7%    |
| Emtec               | 2        | 4      | 0.7%    |
| China               | 2        | 2      | 0.7%    |
| XrayDisk            | 1        | 1      | 0.35%   |
| Verbatim            | 1        | 1      | 0.35%   |
| tigo                | 1        | 1      | 0.35%   |
| Team                | 1        | 1      | 0.35%   |
| SK hynix            | 1        | 1      | 0.35%   |
| ORICO               | 1        | 2      | 0.35%   |
| Lite-On             | 1        | 1      | 0.35%   |
| Lexar               | 1        | 1      | 0.35%   |
| Leven               | 1        | 2      | 0.35%   |
| Lenovo              | 1        | 1      | 0.35%   |
| Kingchuxing         | 1        | 1      | 0.35%   |
| Hoodisk             | 1        | 1      | 0.35%   |
| Hewlett-Packard     | 1        | 1      | 0.35%   |
| Corsair             | 1        | 1      | 0.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 310      | 541    | 48.06%  |
| SSD  | 229      | 374    | 35.5%   |
| NVMe | 106      | 155    | 16.43%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 424      | 915    | 80%     |
| NVMe | 106      | 155    | 20%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 360      | 603    | 62.72%  |
| 0.51-1.0   | 130      | 187    | 22.65%  |
| 1.01-2.0   | 43       | 58     | 7.49%   |
| 3.01-4.0   | 18       | 29     | 3.14%   |
| 2.01-3.0   | 12       | 23     | 2.09%   |
| 4.01-10.0  | 10       | 14     | 1.74%   |
| 10.01-20.0 | 1        | 1      | 0.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 319      | 66.18%  |
| 101-250        | 76       | 15.77%  |
| 251-500        | 47       | 9.75%   |
| 501-1000       | 21       | 4.36%   |
| 51-100         | 9        | 1.87%   |
| 21-50          | 6        | 1.24%   |
| 1001-2000      | 3        | 0.62%   |
| More than 3000 | 1        | 0.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 461      | 98.93%  |
| 21-50          | 2        | 0.43%   |
| More than 3000 | 1        | 0.21%   |
| 101-250        | 1        | 0.21%   |
| 501-1000       | 1        | 0.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 4        | 5      | 2.7%    |
| WDC WD5000AAKX-00ERMA0 500GB      | 3        | 3      | 2.03%   |
| Seagate ST3250410AS 250GB         | 3        | 3      | 2.03%   |
| Samsung Electronics HD322HJ 320GB | 3        | 3      | 2.03%   |
| HGST HTS545032A7E380 320GB        | 3        | 3      | 2.03%   |
| Toshiba DT01ACA100 1TB            | 2        | 5      | 1.35%   |
| Seagate ST9320325AS 320GB         | 2        | 2      | 1.35%   |
| Seagate ST380815AS 80GB           | 2        | 2      | 1.35%   |
| Seagate ST3500413AS 500GB         | 2        | 5      | 1.35%   |
| Seagate ST3320418AS 320GB         | 2        | 2      | 1.35%   |
| Seagate ST31000528AS 1TB          | 2        | 3      | 1.35%   |
| Samsung Electronics HD161HJ 160GB | 2        | 2      | 1.35%   |
| XrayDisk SSD 240GB                | 1        | 1      | 0.68%   |
| WDC WDS240G2G0A-00JH30 240GB      | 1        | 1      | 0.68%   |
| WDC WD800JD-55MUA1 80GB           | 1        | 1      | 0.68%   |
| WDC WD6400AAKS-22A7B0 640GB       | 1        | 1      | 0.68%   |
| WDC WD60EZRZ-00RWYB1 6TB          | 1        | 1      | 0.68%   |
| WDC WD5000AZLX-00CL5A0 500GB      | 1        | 1      | 0.68%   |
| WDC WD5000AVVS-63H0B1 500GB       | 1        | 1      | 0.68%   |
| WDC WD5000AVCS-632DY1 500GB       | 1        | 1      | 0.68%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 1        | 1      | 0.68%   |
| WDC WD5000AAKX-08ERMA0 500GB      | 1        | 1      | 0.68%   |
| WDC WD5000AAKS-22A7B0 500GB       | 1        | 1      | 0.68%   |
| WDC WD5000AAKS-08V0A0 500GB       | 1        | 1      | 0.68%   |
| WDC WD5000AAKS-00V1A0 500GB       | 1        | 1      | 0.68%   |
| WDC WD5000AAKS-00E4A0 500GB       | 1        | 1      | 0.68%   |
| WDC WD40EFRX-68WT0N0 4TB          | 1        | 1      | 0.68%   |
| WDC WD400JB-00ENA0 40GB           | 1        | 1      | 0.68%   |
| WDC WD3200BPVT-22JJ5T0 320GB      | 1        | 1      | 0.68%   |
| WDC WD3200BEVT-00A0RT0 233GB      | 1        | 1      | 0.68%   |
| WDC WD3200AAKS-75L9A0 320GB       | 1        | 1      | 0.68%   |
| WDC WD3200AAKS-00UU3A0 320GB      | 1        | 1      | 0.68%   |
| WDC WD3200AAJS-22B4A0 320GB       | 1        | 1      | 0.68%   |
| WDC WD3200AAJS-00YZCA0 320GB      | 1        | 1      | 0.68%   |
| WDC WD3200AAJS-00L7A0 320GB       | 1        | 1      | 0.68%   |
| WDC WD30EZRX-22D8PB0 3TB          | 1        | 1      | 0.68%   |
| WDC WD30EFRX-68EUZN0 3TB          | 1        | 1      | 0.68%   |
| WDC WD2500AAKX-083CA1 250GB       | 1        | 2      | 0.68%   |
| WDC WD20EVDS-63T3B0 2TB           | 1        | 1      | 0.68%   |
| WDC WD20EURS-63S48Y0 2TB          | 1        | 1      | 0.68%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 43       | 44     | 30.71%  |
| Seagate             | 40       | 50     | 28.57%  |
| Samsung Electronics | 17       | 20     | 12.14%  |
| Hitachi             | 13       | 16     | 9.29%   |
| Toshiba             | 8        | 13     | 5.71%   |
| HGST                | 5        | 5      | 3.57%   |
| Crucial             | 3        | 4      | 2.14%   |
| SanDisk             | 2        | 2      | 1.43%   |
| Kingston            | 2        | 2      | 1.43%   |
| Intel               | 2        | 2      | 1.43%   |
| XrayDisk            | 1        | 1      | 0.71%   |
| OCZ                 | 1        | 1      | 0.71%   |
| KingSpec            | 1        | 1      | 0.71%   |
| Fujitsu             | 1        | 1      | 0.71%   |
| A-DATA Technology   | 1        | 1      | 0.71%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 42       | 43     | 34.43%  |
| Seagate             | 40       | 50     | 32.79%  |
| Samsung Electronics | 14       | 17     | 11.48%  |
| Hitachi             | 13       | 16     | 10.66%  |
| Toshiba             | 7        | 12     | 5.74%   |
| HGST                | 5        | 5      | 4.1%    |
| Fujitsu             | 1        | 1      | 0.82%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 108      | 144    | 85.71%  |
| SSD  | 16       | 17     | 12.7%   |
| NVMe | 2        | 2      | 1.59%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                        | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC WD3200AAJS-00YZCA0 320GB | 1        | 1      | 50%     |
| HGST HTS725050A7E630 500GB   | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 50%     |
| HGST   | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 382      | 881    | 73.46%  |
| Malfunc  | 122      | 163    | 23.46%  |
| Detected | 14       | 24     | 2.69%   |
| Failed   | 2        | 2      | 0.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 317      | 50.64%  |
| AMD                          | 132      | 21.09%  |
| Samsung Electronics          | 42       | 6.71%   |
| ASMedia Technology           | 18       | 2.88%   |
| Phison Electronics           | 17       | 2.72%   |
| Nvidia                       | 12       | 1.92%   |
| SanDisk                      | 11       | 1.76%   |
| Kingston Technology Company  | 10       | 1.6%    |
| JMicron Technology           | 10       | 1.6%    |
| Silicon Motion               | 8        | 1.28%   |
| Broadcom / LSI               | 8        | 1.28%   |
| Marvell Technology Group     | 7        | 1.12%   |
| SK hynix                     | 6        | 0.96%   |
| ADATA Technology             | 6        | 0.96%   |
| Micron/Crucial Technology    | 5        | 0.8%    |
| VIA Technologies             | 4        | 0.64%   |
| Shenzhen Longsys Electronics | 3        | 0.48%   |
| Adaptec                      | 2        | 0.32%   |
| Toshiba                      | 1        | 0.16%   |
| Silicon Image                | 1        | 0.16%   |
| Seagate Technology           | 1        | 0.16%   |
| Realtek Semiconductor        | 1        | 0.16%   |
| Lite-On IT Corp. / Plextor   | 1        | 0.16%   |
| KIOXIA                       | 1        | 0.16%   |
| Hewlett-Packard              | 1        | 0.16%   |
| Enmotus                      | 1        | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 81       | 10.49%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 35       | 4.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 35       | 4.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 31       | 4.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 30       | 3.89%   |
| AMD 400 Series Chipset SATA Controller                                                  | 27       | 3.5%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 25       | 3.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 22       | 2.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 22       | 2.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 19       | 2.46%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 18       | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 18       | 2.33%   |
| Intel SATA Controller [RAID mode]                                                       | 17       | 2.2%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 17       | 2.2%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 17       | 2.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 16       | 2.07%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 13       | 1.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 12       | 1.55%   |
| Phison E12 NVMe Controller                                                              | 9        | 1.17%   |
| Nvidia MCP61 SATA Controller                                                            | 9        | 1.17%   |
| Kingston Company A2000 NVMe SSD                                                         | 9        | 1.17%   |
| AMD 300 Series Chipset SATA Controller                                                  | 9        | 1.17%   |
| AMD FCH SATA Controller D                                                               | 8        | 1.04%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 7        | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 0.91%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 7        | 0.91%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 6        | 0.78%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 6        | 0.78%   |
| Unknown                                                                                 | 6        | 0.78%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 5        | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 5        | 0.65%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 5        | 0.65%   |
| Nvidia MCP61 IDE                                                                        | 5        | 0.65%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 0.65%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 0.65%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 5        | 0.65%   |
| Samsung NVMe SSD Controller 980                                                         | 4        | 0.52%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 4        | 0.52%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 4        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 356      | 57.79%  |
| IDE  | 114      | 18.51%  |
| NVMe | 105      | 17.05%  |
| RAID | 29       | 4.71%   |
| SAS  | 8        | 1.3%    |
| SCSI | 4        | 0.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 320      | 68.67%  |
| AMD    | 146      | 31.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 7        | 1.5%    |
| Intel Core 2 Duo                            | 7        | 1.5%    |
| AMD Ryzen 5 3600 6-Core Processor           | 7        | 1.5%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 6        | 1.28%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 6        | 1.28%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 6        | 1.28%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 6        | 1.28%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 6        | 1.28%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 6        | 1.28%   |
| Intel Xeon                                  | 5        | 1.07%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 5        | 1.07%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 5        | 1.07%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 4        | 0.86%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 4        | 0.86%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 4        | 0.86%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 0.86%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 4        | 0.86%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 0.86%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 4        | 0.86%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 4        | 0.86%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 4        | 0.86%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 4        | 0.86%   |
| AMD Phenom II X4 965 Processor              | 4        | 0.86%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 3        | 0.64%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 3        | 0.64%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 3        | 0.64%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 3        | 0.64%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 0.64%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 3        | 0.64%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3        | 0.64%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 3        | 0.64%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 0.64%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 3        | 0.64%   |
| Intel Core i3-6100T CPU @ 3.20GHz           | 3        | 0.64%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 3        | 0.64%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 3        | 0.64%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 3        | 0.64%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 3        | 0.64%   |
| AMD FX-8350 Eight-Core Processor            | 3        | 0.64%   |
| AMD FX-8320 Eight-Core Processor            | 3        | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 88       | 18.84%  |
| Intel Core i7           | 50       | 10.71%  |
| Intel Xeon              | 46       | 9.85%   |
| Intel Core i3           | 44       | 9.42%   |
| AMD Ryzen 5             | 37       | 7.92%   |
| Intel Core 2 Duo        | 22       | 4.71%   |
| AMD Ryzen 7             | 19       | 4.07%   |
| AMD FX                  | 18       | 3.85%   |
| Intel Celeron           | 15       | 3.21%   |
| Intel Pentium           | 14       | 3%      |
| Intel Core 2 Quad       | 13       | 2.78%   |
| Intel Pentium Dual-Core | 12       | 2.57%   |
| AMD Ryzen 3             | 11       | 2.36%   |
| AMD Phenom II X4        | 11       | 2.36%   |
| AMD Ryzen Threadripper  | 6        | 1.28%   |
| AMD Ryzen 9             | 6        | 1.28%   |
| AMD Athlon II X4        | 4        | 0.86%   |
| AMD A8                  | 4        | 0.86%   |
| AMD A10                 | 4        | 0.86%   |
| Other                   | 3        | 0.64%   |
| Intel Atom              | 3        | 0.64%   |
| AMD Ryzen 5 PRO         | 3        | 0.64%   |
| AMD Athlon II X2        | 3        | 0.64%   |
| AMD Athlon 64 X2        | 3        | 0.64%   |
| Intel Genuine           | 2        | 0.43%   |
| Intel Core i9           | 2        | 0.43%   |
| Intel Core 2            | 2        | 0.43%   |
| AMD Phenom II X6        | 2        | 0.43%   |
| AMD E1                  | 2        | 0.43%   |
| AMD E                   | 2        | 0.43%   |
| AMD Athlon Dual Core    | 2        | 0.43%   |
| AMD Athlon              | 2        | 0.43%   |
| AMD A6                  | 2        | 0.43%   |
| AMD A4                  | 2        | 0.43%   |
| Intel Pentium Silver    | 1        | 0.21%   |
| Intel Pentium Gold      | 1        | 0.21%   |
| Intel Pentium Dual      | 1        | 0.21%   |
| Intel Pentium D         | 1        | 0.21%   |
| Intel Pentium 4         | 1        | 0.21%   |
| AMD Sempron             | 1        | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 181      | 38.76%  |
| 2       | 118      | 25.27%  |
| 8       | 42       | 8.99%   |
| 6       | 42       | 8.99%   |
| 12      | 29       | 6.21%   |
| Unknown | 20       | 4.28%   |
| 16      | 19       | 4.07%   |
| 24      | 6        | 1.28%   |
| 64      | 2        | 0.43%   |
| 48      | 2        | 0.43%   |
| 1       | 2        | 0.43%   |
| 32      | 1        | 0.21%   |
| 14      | 1        | 0.21%   |
| 10      | 1        | 0.21%   |
| 3       | 1        | 0.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 458      | 98.28%  |
| 2      | 7        | 1.5%    |
| 8      | 1        | 0.21%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 301      | 64.59%  |
| 2       | 145      | 31.12%  |
| Unknown | 20       | 4.29%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 55       | 11.8%   |
| KabyLake      | 48       | 10.3%   |
| IvyBridge     | 46       | 9.87%   |
| Penryn        | 40       | 8.58%   |
| SandyBridge   | 35       | 7.51%   |
| Skylake       | 32       | 6.87%   |
| Zen 2         | 28       | 6.01%   |
| Zen+          | 26       | 5.58%   |
| Piledriver    | 25       | 5.36%   |
| Zen           | 21       | 4.51%   |
| K10           | 20       | 4.29%   |
| Core          | 15       | 3.22%   |
| Westmere      | 11       | 2.36%   |
| Nehalem       | 11       | 2.36%   |
| Zen 3         | 9        | 1.93%   |
| CometLake     | 9        | 1.93%   |
| K8 Hammer     | 5        | 1.07%   |
| Silvermont    | 4        | 0.86%   |
| Bulldozer     | 4        | 0.86%   |
| Broadwell     | 4        | 0.86%   |
| Goldmont plus | 3        | 0.64%   |
| Bonnell       | 3        | 0.64%   |
| Bobcat        | 3        | 0.64%   |
| Unknown       | 3        | 0.64%   |
| NetBurst      | 2        | 0.43%   |
| Jaguar        | 2        | 0.43%   |
| K10 Llano     | 1        | 0.21%   |
| Excavator     | 1        | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 208      | 42.02%  |
| Intel  | 160      | 32.32%  |
| AMD    | 127      | 25.66%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 26       | 5.22%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 22       | 4.42%   |
| Intel HD Graphics 530                                                       | 17       | 3.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 17       | 3.41%   |
| Nvidia GK208B [GeForce GT 710]                                              | 15       | 3.01%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 15       | 3.01%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 12       | 2.41%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 11       | 2.21%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 11       | 2.21%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 11       | 2.21%   |
| Nvidia GT218 [GeForce 210]                                                  | 10       | 2.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 10       | 2.01%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 9        | 1.81%   |
| Nvidia GF119 [GeForce GT 610]                                               | 9        | 1.81%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 9        | 1.81%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 8        | 1.61%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 7        | 1.41%   |
| Intel HD Graphics 630                                                       | 6        | 1.2%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 6        | 1.2%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 5        | 1%      |
| Nvidia GK208B [GeForce GT 730]                                              | 5        | 1%      |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5        | 1%      |
| Nvidia TU116 [GeForce GTX 1660]                                             | 4        | 0.8%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 4        | 0.8%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 4        | 0.8%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 0.8%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 4        | 0.8%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 4        | 0.8%    |
| AMD RS780L [Radeon 3000]                                                    | 4        | 0.8%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 0.8%    |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 4        | 0.8%    |
| AMD Juniper XT [Radeon HD 5770]                                             | 4        | 0.8%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 0.8%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 4        | 0.8%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 0.6%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 0.6%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 0.6%    |
| Nvidia GM206 [GeForce GTX 950]                                              | 3        | 0.6%    |
| Nvidia GK107 [GeForce GT 740]                                               | 3        | 0.6%    |
| Nvidia GK106 [GeForce GTX 660]                                              | 3        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 194      | 40.76%  |
| 1 x Intel      | 128      | 26.89%  |
| 1 x AMD        | 118      | 24.79%  |
| Intel + Nvidia | 12       | 2.52%   |
| 2 x Intel      | 11       | 2.31%   |
| Intel + AMD    | 9        | 1.89%   |
| AMD + Nvidia   | 2        | 0.42%   |
| 2 x Nvidia     | 1        | 0.21%   |
| 2 x AMD        | 1        | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 303      | 64.47%  |
| Proprietary | 149      | 31.7%   |
| Unknown     | 18       | 3.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 231      | 48.43%  |
| 1.01-2.0   | 73       | 15.3%   |
| 3.01-4.0   | 49       | 10.27%  |
| 0.51-1.0   | 46       | 9.64%   |
| 7.01-8.0   | 27       | 5.66%   |
| 0.01-0.5   | 23       | 4.82%   |
| 5.01-6.0   | 20       | 4.19%   |
| 2.01-3.0   | 6        | 1.26%   |
| 8.01-16.0  | 2        | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 55       | 14.67%  |
| Goldstar             | 51       | 13.6%   |
| Dell                 | 44       | 11.73%  |
| Hewlett-Packard      | 31       | 8.27%   |
| Acer                 | 29       | 7.73%   |
| AOC                  | 22       | 5.87%   |
| BenQ                 | 21       | 5.6%    |
| Philips              | 16       | 4.27%   |
| Ancor Communications | 14       | 3.73%   |
| Lenovo               | 9        | 2.4%    |
| Iiyama               | 9        | 2.4%    |
| ASUSTek Computer     | 8        | 2.13%   |
| ViewSonic            | 7        | 1.87%   |
| Sony                 | 6        | 1.6%    |
| Fujitsu Siemens      | 6        | 1.6%    |
| MSI                  | 5        | 1.33%   |
| Vizio                | 3        | 0.8%    |
| Toshiba              | 3        | 0.8%    |
| Packard Bell         | 3        | 0.8%    |
| Eizo                 | 3        | 0.8%    |
| Vestel Elektronik    | 2        | 0.53%   |
| NEC Computers        | 2        | 0.53%   |
| Insignia             | 2        | 0.53%   |
| HannStar             | 2        | 0.53%   |
| ZL_                  | 1        | 0.27%   |
| Westinghouse         | 1        | 0.27%   |
| VIE                  | 1        | 0.27%   |
| Videoseven           | 1        | 0.27%   |
| Sun                  | 1        | 0.27%   |
| SGT                  | 1        | 0.27%   |
| RS                   | 1        | 0.27%   |
| PRI                  | 1        | 0.27%   |
| Medion               | 1        | 0.27%   |
| LTV                  | 1        | 0.27%   |
| LED                  | 1        | 0.27%   |
| KJT                  | 1        | 0.27%   |
| Haier                | 1        | 0.27%   |
| GRR                  | 1        | 0.27%   |
| Gateway              | 1        | 0.27%   |
| FND                  | 1        | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                        | 3        | 0.78%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                      | 3        | 0.78%   |
| Acer G227HQL ACR03DE 1920x1080 480x270mm 21.7-inch                     | 3        | 0.78%   |
| ViewSonic VX1940w VSC6A20 1680x1050 410x260mm 19.1-inch                | 2        | 0.52%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch     | 2        | 0.52%   |
| Sony TV SNY9C01 1360x768                                               | 2        | 0.52%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                        | 2        | 0.52%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                       | 2        | 0.52%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 1110x620mm 50.1-inch | 2        | 0.52%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                 | 2        | 0.52%   |
| Philips LCD Monitor PHLC0B1 1920x1080 480x270mm 21.7-inch              | 2        | 0.52%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch                | 2        | 0.52%   |
| Hewlett-Packard 27f HPN354A 1920x1080 600x340mm 27.2-inch              | 2        | 0.52%   |
| Hewlett-Packard 27er HWP3325 1920x1080 600x340mm 27.2-inch             | 2        | 0.52%   |
| Goldstar W2242 GSM4B6F 1680x1050 490x320mm 23.0-inch                   | 2        | 0.52%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch             | 2        | 0.52%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch              | 2        | 0.52%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2        | 0.52%   |
| Goldstar E2441 GSM581F 1920x1080 530x300mm 24.0-inch                   | 2        | 0.52%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                    | 2        | 0.52%   |
| Goldstar 2D FHD LG TV GSM59C6 1920x1080 510x290mm 23.1-inch            | 2        | 0.52%   |
| Dell U3415W DELA0A6 3440x1440 800x330mm 34.1-inch                      | 2        | 0.52%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                      | 2        | 0.52%   |
| Dell S2418HN/NX DEL4123 1920x1080 530x300mm 24.0-inch                  | 2        | 0.52%   |
| BenQ GW2780 BNQ78E6 1920x1080 600x340mm 27.2-inch                      | 2        | 0.52%   |
| BenQ GW2260 BNQ78C4 1920x1080 480x270mm 21.7-inch                      | 2        | 0.52%   |
| BenQ GL2460 BNQ78CE 1920x1080 530x300mm 24.0-inch                      | 2        | 0.52%   |
| BenQ GL2450 BNQ78A4 1920x1080 530x300mm 24.0-inch                      | 2        | 0.52%   |
| ASUSTek Computer VP228 AUS22A1 1920x1080 480x270mm 21.7-inch           | 2        | 0.52%   |
| ASUSTek Computer ROG XG279Q AUS278D 2560x1440 600x340mm 27.2-inch      | 2        | 0.52%   |
| AOC 24G2W1G4 AOC2402 1920x1080 530x300mm 24.0-inch                     | 2        | 0.52%   |
| AOC 22V2WG5 AOC2202 1920x1080 480x270mm 21.7-inch                      | 2        | 0.52%   |
| Ancor Communications MX27AQ ACI27A5 2560x1440 600x340mm 27.2-inch      | 2        | 0.52%   |
| Acer S240HL ACR0289 1920x1080 530x300mm 24.0-inch                      | 2        | 0.52%   |
| ZL_ zhuoyue-HDMI ZL_2716 2560x1440 600x330mm 27.0-inch                 | 1        | 0.26%   |
| Westinghouse LCM-19w4 WDE1904 1440x900 410x260mm 19.1-inch             | 1        | 0.26%   |
| Vizio LCD Monitor VIZ0022 1920x540 480x270mm 21.7-inch                 | 1        | 0.26%   |
| Vizio D43-D2 VIZ1004 1920x1080 930x520mm 41.9-inch                     | 1        | 0.26%   |
| Vizio D32f-F1 VIZ1027 1920x1080 700x390mm 31.5-inch                    | 1        | 0.26%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 520x290mm 23.4-inch             | 1        | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 169      | 45.92%  |
| 1280x1024 (SXGA)   | 31       | 8.42%   |
| 1680x1050 (WSXGA+) | 26       | 7.07%   |
| 2560x1440 (QHD)    | 25       | 6.79%   |
| 3840x2160 (4K)     | 21       | 5.71%   |
| 1440x900 (WXGA+)   | 20       | 5.43%   |
| 1366x768 (WXGA)    | 18       | 4.89%   |
| 1600x900 (HD+)     | 14       | 3.8%    |
| 1920x1200 (WUXGA)  | 11       | 2.99%   |
| 2560x1080          | 8        | 2.17%   |
| 3440x1440          | 6        | 1.63%   |
| 1360x768           | 5        | 1.36%   |
| 1024x768 (XGA)     | 5        | 1.36%   |
| 1920x540           | 4        | 1.09%   |
| 2048x1152          | 2        | 0.54%   |
| 1600x1200          | 2        | 0.54%   |
| 2560x1600          | 1        | 0.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 58       | 15.43%  |
| 21      | 57       | 15.16%  |
| 19      | 51       | 13.56%  |
| 23      | 45       | 11.97%  |
| 27      | 44       | 11.7%   |
| 18      | 21       | 5.59%   |
| 31      | 17       | 4.52%   |
| 17      | 13       | 3.46%   |
| 22      | 11       | 2.93%   |
| Unknown | 11       | 2.93%   |
| 34      | 9        | 2.39%   |
| 20      | 8        | 2.13%   |
| 50      | 3        | 0.8%    |
| 42      | 3        | 0.8%    |
| 28      | 3        | 0.8%    |
| 14      | 3        | 0.8%    |
| 33      | 2        | 0.53%   |
| 29      | 2        | 0.53%   |
| 16      | 2        | 0.53%   |
| 15      | 2        | 0.53%   |
| 64      | 1        | 0.27%   |
| 54      | 1        | 0.27%   |
| 52      | 1        | 0.27%   |
| 41      | 1        | 0.27%   |
| 40      | 1        | 0.27%   |
| 39      | 1        | 0.27%   |
| 36      | 1        | 0.27%   |
| 32      | 1        | 0.27%   |
| 30      | 1        | 0.27%   |
| 25      | 1        | 0.27%   |
| 13      | 1        | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 136      | 36.96%  |
| 401-500     | 128      | 34.78%  |
| 601-700     | 26       | 7.07%   |
| 351-400     | 24       | 6.52%   |
| 301-350     | 14       | 3.8%    |
| 701-800     | 13       | 3.53%   |
| Unknown     | 11       | 2.99%   |
| 1001-1500   | 6        | 1.63%   |
| 201-300     | 4        | 1.09%   |
| 901-1000    | 4        | 1.09%   |
| 801-900     | 2        | 0.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 254      | 70.17%  |
| 16/10 | 54       | 14.92%  |
| 5/4   | 29       | 8.01%   |
| 21/9  | 14       | 3.87%   |
| 4/3   | 7        | 1.93%   |
| 3/2   | 4        | 1.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 148      | 40.11%  |
| 151-200        | 64       | 17.34%  |
| 301-350        | 45       | 12.2%   |
| 351-500        | 31       | 8.4%    |
| 141-150        | 28       | 7.59%   |
| 251-300        | 19       | 5.15%   |
| Unknown        | 11       | 2.98%   |
| 501-1000       | 7        | 1.9%    |
| More than 1000 | 6        | 1.63%   |
| 101-110        | 3        | 0.81%   |
| 91-100         | 3        | 0.81%   |
| 121-130        | 2        | 0.54%   |
| 131-140        | 1        | 0.27%   |
| 111-120        | 1        | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 245      | 66.76%  |
| 101-120 | 91       | 24.8%   |
| Unknown | 11       | 3%      |
| 161-240 | 8        | 2.18%   |
| 121-160 | 8        | 2.18%   |
| 1-50    | 4        | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 346      | 73%     |
| 0     | 100      | 21.1%   |
| 2     | 26       | 5.49%   |
| 3     | 2        | 0.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 270      | 46.63%  |
| Intel                           | 196      | 33.85%  |
| Qualcomm Atheros                | 36       | 6.22%   |
| Broadcom                        | 25       | 4.32%   |
| Ralink Technology               | 9        | 1.55%   |
| Ralink                          | 9        | 1.55%   |
| Marvell Technology Group        | 6        | 1.04%   |
| D-Link System                   | 3        | 0.52%   |
| TP-Link                         | 2        | 0.35%   |
| Mellanox Technologies           | 2        | 0.35%   |
| MediaTek                        | 2        | 0.35%   |
| IMC Networks                    | 2        | 0.35%   |
| Edimax Technology               | 2        | 0.35%   |
| ASUSTek Computer                | 2        | 0.35%   |
| Xiaomi                          | 1        | 0.17%   |
| VIA Technologies                | 1        | 0.17%   |
| Samsung Electronics             | 1        | 0.17%   |
| Qualcomm Atheros Communications | 1        | 0.17%   |
| Nvidia                          | 1        | 0.17%   |
| NetGear                         | 1        | 0.17%   |
| Microchip Technology            | 1        | 0.17%   |
| Google                          | 1        | 0.17%   |
| D-Link                          | 1        | 0.17%   |
| Bluegiga Technologies           | 1        | 0.17%   |
| Belkin Components               | 1        | 0.17%   |
| Aquantia                        | 1        | 0.17%   |
| 3Com                            | 1        | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 231      | 35.76%  |
| Intel I211 Gigabit Network Connection                             | 29       | 4.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 26       | 4.02%   |
| Intel Ethernet Connection I217-LM                                 | 20       | 3.1%    |
| Intel Wi-Fi 6 AX200                                               | 16       | 2.48%   |
| Intel Ethernet Connection (7) I219-V                              | 14       | 2.17%   |
| Intel Ethernet Connection (2) I219-V                              | 13       | 2.01%   |
| Intel Ethernet Connection (2) I219-LM                             | 13       | 2.01%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11       | 1.7%    |
| Intel 82574L Gigabit Network Connection                           | 10       | 1.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 8        | 1.24%   |
| Intel 82579V Gigabit Network Connection                           | 8        | 1.24%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7        | 1.08%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 7        | 1.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6        | 0.93%   |
| Intel Wireless 7260                                               | 6        | 0.93%   |
| Intel Ethernet Connection I217-V                                  | 6        | 0.93%   |
| Ralink RT5370 Wireless Adapter                                    | 5        | 0.77%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 5        | 0.77%   |
| Intel Wireless 7265                                               | 5        | 0.77%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 4        | 0.62%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 4        | 0.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 0.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4        | 0.62%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 4        | 0.62%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 0.62%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 4        | 0.62%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 4        | 0.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3        | 0.46%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.46%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.46%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 3        | 0.46%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3        | 0.46%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 0.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3        | 0.46%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 0.46%   |
| Intel Wireless-AC 9260                                            | 3        | 0.46%   |
| Intel Wireless 8265 / 8275                                        | 3        | 0.46%   |
| Intel Wireless 3165                                               | 3        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 52       | 33.55%  |
| Realtek Semiconductor           | 44       | 28.39%  |
| Qualcomm Atheros                | 15       | 9.68%   |
| Broadcom                        | 12       | 7.74%   |
| Ralink Technology               | 9        | 5.81%   |
| Ralink                          | 9        | 5.81%   |
| TP-Link                         | 2        | 1.29%   |
| IMC Networks                    | 2        | 1.29%   |
| Edimax Technology               | 2        | 1.29%   |
| ASUSTek Computer                | 2        | 1.29%   |
| Qualcomm Atheros Communications | 1        | 0.65%   |
| NetGear                         | 1        | 0.65%   |
| MediaTek                        | 1        | 0.65%   |
| D-Link System                   | 1        | 0.65%   |
| D-Link                          | 1        | 0.65%   |
| Belkin Components               | 1        | 0.65%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                         | 16       | 10.19%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 8        | 5.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 7        | 4.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 6        | 3.82%   |
| Intel Wireless 7260                                                         | 6        | 3.82%   |
| Ralink RT5370 Wireless Adapter                                              | 5        | 3.18%   |
| Intel Wireless 7265                                                         | 5        | 3.18%   |
| Realtek RTL8188EE Wireless Network Adapter                                  | 4        | 2.55%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 4        | 2.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 4        | 2.55%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 4        | 2.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                             | 3        | 1.91%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                    | 3        | 1.91%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                    | 3        | 1.91%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                      | 3        | 1.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 3        | 1.91%   |
| Ralink MT7601U Wireless Adapter                                             | 3        | 1.91%   |
| Intel Wireless-AC 9260                                                      | 3        | 1.91%   |
| Intel Wireless 8265 / 8275                                                  | 3        | 1.91%   |
| Intel Wireless 3165                                                         | 3        | 1.91%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 3        | 1.91%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                         | 2        | 1.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2        | 1.27%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                      | 2        | 1.27%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                       | 2        | 1.27%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                      | 2        | 1.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 2        | 1.27%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                            | 2        | 1.27%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2        | 1.27%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)              | 2        | 1.27%   |
| Intel Centrino Wireless-N 2230                                              | 2        | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                             | 2        | 1.27%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 2        | 1.27%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]           | 2        | 1.27%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                          | 2        | 1.27%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                   | 2        | 1.27%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                          | 1        | 0.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                    | 1        | 0.64%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                             | 1        | 0.64%   |
| Ralink RT3072 Wireless Adapter                                              | 1        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 250      | 52.74%  |
| Intel                    | 175      | 36.92%  |
| Qualcomm Atheros         | 21       | 4.43%   |
| Broadcom                 | 13       | 2.74%   |
| Marvell Technology Group | 6        | 1.27%   |
| D-Link System            | 2        | 0.42%   |
| Xiaomi                   | 1        | 0.21%   |
| VIA Technologies         | 1        | 0.21%   |
| Samsung Electronics      | 1        | 0.21%   |
| Nvidia                   | 1        | 0.21%   |
| MediaTek                 | 1        | 0.21%   |
| Google                   | 1        | 0.21%   |
| Aquantia                 | 1        | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 231      | 47.93%  |
| Intel I211 Gigabit Network Connection                                         | 29       | 6.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 26       | 5.39%   |
| Intel Ethernet Connection I217-LM                                             | 20       | 4.15%   |
| Intel Ethernet Connection (7) I219-V                                          | 14       | 2.9%    |
| Intel Ethernet Connection (2) I219-V                                          | 13       | 2.7%    |
| Intel Ethernet Connection (2) I219-LM                                         | 13       | 2.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 11       | 2.28%   |
| Intel 82574L Gigabit Network Connection                                       | 10       | 2.07%   |
| Intel 82579V Gigabit Network Connection                                       | 8        | 1.66%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 7        | 1.45%   |
| Intel Ethernet Connection I217-V                                              | 6        | 1.24%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 5        | 1.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4        | 0.83%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 4        | 0.83%   |
| Intel Ethernet Connection (2) I218-V                                          | 4        | 0.83%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 4        | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 3        | 0.62%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 3        | 0.62%   |
| Intel 82583V Gigabit Network Connection                                       | 3        | 0.62%   |
| Intel 82578DM Gigabit Network Connection                                      | 3        | 0.62%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3        | 0.62%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 3        | 0.62%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2        | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 2        | 0.41%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 2        | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 2        | 0.41%   |
| Intel I210 Gigabit Network Connection                                         | 2        | 0.41%   |
| Intel Ethernet Controller I225-V                                              | 2        | 0.41%   |
| Intel Ethernet Connection (12) I219-V                                         | 2        | 0.41%   |
| Intel Ethernet Connection (11) I219-V                                         | 2        | 0.41%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2        | 0.41%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 2        | 0.41%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 2        | 0.41%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2        | 0.41%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 2        | 0.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1        | 0.21%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 1        | 0.21%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 0.21%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.21%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 458      | 75.33%  |
| WiFi     | 143      | 23.52%  |
| Unknown  | 5        | 0.82%   |
| Modem    | 2        | 0.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 445      | 84.76%  |
| WiFi     | 78       | 14.86%  |
| Unknown  | 2        | 0.38%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 326      | 69.81%  |
| 2     | 112      | 23.98%  |
| 3     | 19       | 4.07%   |
| 0     | 6        | 1.28%   |
| 4     | 4        | 0.86%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 459      | 97.25%  |
| Yes  | 13       | 2.75%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 46       | 36.8%   |
| Cambridge Silicon Radio         | 29       | 23.2%   |
| Realtek Semiconductor           | 14       | 11.2%   |
| ASUSTek Computer                | 8        | 6.4%    |
| Apple                           | 8        | 6.4%    |
| Broadcom                        | 7        | 5.6%    |
| Integrated System Solution      | 3        | 2.4%    |
| IMC Networks                    | 3        | 2.4%    |
| Qualcomm Atheros Communications | 2        | 1.6%    |
| TP-Link                         | 1        | 0.8%    |
| HTC (High Tech Computer)        | 1        | 0.8%    |
| Foxconn / Hon Hai               | 1        | 0.8%    |
| Edimax Technology               | 1        | 0.8%    |
| Bluetooth Device                | 1        | 0.8%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 29       | 23.2%   |
| Intel Bluetooth wireless interface                                   | 15       | 12%     |
| Intel AX200 Bluetooth                                                | 15       | 12%     |
| Intel Wireless-AC 3168 Bluetooth                                     | 7        | 5.6%    |
| Realtek  Bluetooth 4.2 Adapter                                       | 6        | 4.8%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 5        | 4%      |
| Realtek  Bluetooth Adapter                                           | 4        | 3.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 3        | 2.4%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 3        | 2.4%    |
| ASUS ASUS USB-BT500                                                  | 3        | 2.4%    |
| Apple Apple Broadcom Built-in Bluetooth                              | 3        | 2.4%    |
| Realtek  Bluetooth 4.0 Adapter                                       | 2        | 1.6%    |
| Intel Centrino Bluetooth Wireless Transceiver                        | 2        | 1.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 2        | 1.6%    |
| Intel AX201 Bluetooth                                                | 2        | 1.6%    |
| Integrated System Solution Bluetooth Device                          | 2        | 1.6%    |
| ASUS Realtek Bluetooth 4.0 + High Speed Chip                         | 2        | 1.6%    |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2        | 1.6%    |
| TP-Link TP-Link UB500 Adapter                                        | 1        | 0.8%    |
| Realtek Dell Wireless 1801 Bluetooth 4.0 LE                          | 1        | 0.8%    |
| Realtek Bluetooth Radio                                              | 1        | 0.8%    |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device          | 1        | 0.8%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 1        | 0.8%    |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1        | 0.8%    |
| IMC Networks Realtek Bluetooth Adapter                               | 1        | 0.8%    |
| IMC Networks Realtek Bluetooth 4.0 Adapter                           | 1        | 0.8%    |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0 + HS              | 1        | 0.8%    |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.8%    |
| Foxconn / Hon Hai Broadcom Bluetooth 4.0 USB                         | 1        | 0.8%    |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter              | 1        | 0.8%    |
| Broadcom Broadcom 4371 Bluetooth 4.1 Adapter                         | 1        | 0.8%    |
| Broadcom Bluetooth Device                                            | 1        | 0.8%    |
| Broadcom Bluetooth 2.0+eDR dongle                                    | 1        | 0.8%    |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 1        | 0.8%    |
| Bluetooth Device Silicon Wave Bluetooth Wireless Adapter             | 1        | 0.8%    |
| ASUS Bluetooth Controller                                            | 1        | 0.8%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 309      | 40.82%  |
| Nvidia                      | 190      | 25.1%   |
| AMD                         | 176      | 23.25%  |
| C-Media Electronics         | 23       | 3.04%   |
| Texas Instruments           | 8        | 1.06%   |
| Creative Labs               | 6        | 0.79%   |
| Logitech                    | 4        | 0.53%   |
| SteelSeries ApS             | 3        | 0.4%    |
| JMTek                       | 3        | 0.4%    |
| GN Netcom                   | 3        | 0.4%    |
| Yamaha                      | 2        | 0.26%   |
| Kingston Technology         | 2        | 0.26%   |
| Google                      | 2        | 0.26%   |
| Focusrite-Novation          | 2        | 0.26%   |
| Creative Technology         | 2        | 0.26%   |
| BEHRINGER International     | 2        | 0.26%   |
| ZOOM                        | 1        | 0.13%   |
| XMOS                        | 1        | 0.13%   |
| VIA Technologies            | 1        | 0.13%   |
| Steinberg Soft-und Hardware | 1        | 0.13%   |
| Realtek Semiconductor       | 1        | 0.13%   |
| Plantronics                 | 1        | 0.13%   |
| Nektar                      | 1        | 0.13%   |
| KORG                        | 1        | 0.13%   |
| Hewlett-Packard             | 1        | 0.13%   |
| Griffin Technology          | 1        | 0.13%   |
| Giga-Byte Technology        | 1        | 0.13%   |
| Generalplus Technology      | 1        | 0.13%   |
| FiiO Electronics Technology | 1        | 0.13%   |
| Ensoniq                     | 1        | 0.13%   |
| Elgato Systems              | 1        | 0.13%   |
| Corsair                     | 1        | 0.13%   |
| Cambridge Silicon Radio     | 1        | 0.13%   |
| Bose                        | 1        | 0.13%   |
| ASUSTek Computer            | 1        | 0.13%   |
| Astro Gaming                | 1        | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 44       | 5.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 37       | 4.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 36       | 4.12%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 34       | 3.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 32       | 3.66%   |
| AMD Starship/Matisse HD Audio Controller                                   | 31       | 3.55%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 30       | 3.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 28       | 3.2%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 26       | 2.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 25       | 2.86%   |
| AMD Family 17h/19h HD Audio Controller                                     | 25       | 2.86%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 22       | 2.52%   |
| Intel Cannon Lake PCH cAVS                                                 | 20       | 2.29%   |
| Intel 200 Series PCH HD Audio                                              | 20       | 2.29%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 18       | 2.06%   |
| AMD FCH Azalia Controller                                                  | 15       | 1.72%   |
| Nvidia TU116 High Definition Audio Controller                              | 14       | 1.6%    |
| Nvidia GP107GL High Definition Audio Controller                            | 14       | 1.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 14       | 1.6%    |
| Nvidia GP106 High Definition Audio Controller                              | 12       | 1.37%   |
| Nvidia GF119 HDMI Audio Controller                                         | 12       | 1.37%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 12       | 1.37%   |
| Nvidia High Definition Audio Controller                                    | 11       | 1.26%   |
| Nvidia GP108 High Definition Audio Controller                              | 11       | 1.26%   |
| AMD Navi 10 HDMI Audio                                                     | 11       | 1.26%   |
| Nvidia GK107 HDMI Audio Controller                                         | 10       | 1.14%   |
| Nvidia GF108 High Definition Audio Controller                              | 10       | 1.14%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 10       | 1.14%   |
| Nvidia GM206 High Definition Audio Controller                              | 9        | 1.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 9        | 1.03%   |
| Nvidia MCP61 High Definition Audio                                         | 8        | 0.92%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 8        | 0.92%   |
| Nvidia GP104 High Definition Audio Controller                              | 7        | 0.8%    |
| Nvidia GM204 High Definition Audio Controller                              | 7        | 0.8%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 7        | 0.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7        | 0.8%    |
| Nvidia GK104 HDMI Audio Controller                                         | 6        | 0.69%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 6        | 0.69%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 6        | 0.69%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 6        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Kingston                   | 106      | 19.38%  |
| Unknown                    | 79       | 14.44%  |
| Samsung Electronics        | 55       | 10.05%  |
| Crucial                    | 52       | 9.51%   |
| SK hynix                   | 43       | 7.86%   |
| Corsair                    | 41       | 7.5%    |
| Micron Technology          | 36       | 6.58%   |
| G.Skill                    | 32       | 5.85%   |
| Unknown                    | 16       | 2.93%   |
| Team                       | 12       | 2.19%   |
| Nanya Technology           | 11       | 2.01%   |
| Transcend                  | 8        | 1.46%   |
| A-DATA Technology          | 8        | 1.46%   |
| Patriot                    | 6        | 1.1%    |
| Ramaxel Technology         | 5        | 0.91%   |
| Avant                      | 5        | 0.91%   |
| Elpida                     | 4        | 0.73%   |
| AMD                        | 4        | 0.73%   |
| PNY                        | 2        | 0.37%   |
| Goldkey                    | 2        | 0.37%   |
| Atermiter                  | 2        | 0.37%   |
| Unknown (D386)             | 1        | 0.18%   |
| Unknown (ABCD)             | 1        | 0.18%   |
| Unknown (7F7F7F94FFFFFFFF) | 1        | 0.18%   |
| Unknown (09A4)             | 1        | 0.18%   |
| Unifosa                    | 1        | 0.18%   |
| TakeMS                     | 1        | 0.18%   |
| Super Talent               | 1        | 0.18%   |
| Strontium                  | 1        | 0.18%   |
| Smart                      | 1        | 0.18%   |
| Silicon Power              | 1        | 0.18%   |
| Ramos Technology           | 1        | 0.18%   |
| KomputerBay                | 1        | 0.18%   |
| Kllisre                    | 1        | 0.18%   |
| Hyundai lnc                | 1        | 0.18%   |
| Hikvision                  | 1        | 0.18%   |
| Goodram                    | 1        | 0.18%   |
| GLOWAY                     | 1        | 0.18%   |
| Apacer                     | 1        | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown                                                 | 16       | 2.65%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                    | 7        | 1.16%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 6        | 0.99%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s    | 6        | 0.99%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s     | 5        | 0.83%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 4        | 0.66%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s             | 4        | 0.66%   |
| Unknown RAM Module 1GB DIMM SDRAM                       | 4        | 0.66%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s     | 4        | 0.66%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s     | 4        | 0.66%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 3        | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR2                        | 3        | 0.5%    |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s    | 3        | 0.5%    |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s            | 3        | 0.5%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s       | 3        | 0.5%    |
| Kingston RAM KHX1600C10D3/8G 4GB DIMM DDR3 1600MT/s     | 3        | 0.5%    |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3200MT/s     | 3        | 0.5%    |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s   | 3        | 0.5%    |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1333MT/s   | 3        | 0.5%    |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s    | 3        | 0.5%    |
| Crucial RAM CT8G4DFD8213.C16FAR1 8GB DIMM DDR4 2133MT/s | 3        | 0.5%    |
| Crucial RAM CT16G4DFRA266.C8FE 16GB DIMM DDR4 2667MT/s  | 3        | 0.5%    |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s     | 3        | 0.5%    |
| Corsair RAM CMX8GX3M2A1333C9 4GB DIMM 1333MT/s          | 3        | 0.5%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s   | 3        | 0.5%    |
| Corsair RAM CMK16GX4M2A2400C16 8GB DIMM DDR4 2400MT/s   | 3        | 0.5%    |
| Unknown RAM Module 4GB DIMM SDRAM                       | 2        | 0.33%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                | 2        | 0.33%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                    | 2        | 0.33%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                 | 2        | 0.33%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 2        | 0.33%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                | 2        | 0.33%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                | 2        | 0.33%   |
| Unknown RAM Module 2GB DIMM 800MT/s                     | 2        | 0.33%   |
| Unknown RAM Module 2GB DIMM 400MT/s                     | 2        | 0.33%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s       | 2        | 0.33%   |
| SK hynix RAM HMT451U7BFR8A-PB 4GB DIMM DDR3 1600MT/s    | 2        | 0.33%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s    | 2        | 0.33%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 2        | 0.33%   |
| SK hynix RAM HMT451S6BCFR8A-PB 4GB DIMM DDR3 1600MT/s   | 2        | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 193      | 41.96%  |
| DDR4    | 178      | 38.7%   |
| DDR2    | 39       | 8.48%   |
| Unknown | 33       | 7.17%   |
| SDRAM   | 13       | 2.83%   |
| DDR     | 3        | 0.65%   |
| LPDDR4  | 1        | 0.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 417      | 90.85%  |
| SODIMM  | 38       | 8.28%   |
| FB-DIMM | 3        | 0.65%   |
| Unknown | 1        | 0.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 171      | 32.45%  |
| 8192  | 168      | 31.88%  |
| 2048  | 101      | 19.17%  |
| 16384 | 61       | 11.57%  |
| 1024  | 19       | 3.61%   |
| 32768 | 5        | 0.95%   |
| 512   | 2        | 0.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 113      | 22.83%  |
| 1333    | 88       | 17.78%  |
| 2400    | 44       | 8.89%   |
| 2133    | 42       | 8.48%   |
| 3200    | 41       | 8.28%   |
| 2667    | 33       | 6.67%   |
| 800     | 30       | 6.06%   |
| 2666    | 16       | 3.23%   |
| 667     | 16       | 3.23%   |
| Unknown | 14       | 2.83%   |
| 1066    | 12       | 2.42%   |
| 1866    | 7        | 1.41%   |
| 1867    | 6        | 1.21%   |
| 3600    | 5        | 1.01%   |
| 3000    | 5        | 1.01%   |
| 533     | 5        | 1.01%   |
| 400     | 5        | 1.01%   |
| 1067    | 4        | 0.81%   |
| 2933    | 3        | 0.61%   |
| 333     | 2        | 0.4%    |
| 3733    | 1        | 0.2%    |
| 3400    | 1        | 0.2%    |
| 1334    | 1        | 0.2%    |
| 1200    | 1        | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 6        | 35.29%  |
| Brother Industries    | 6        | 35.29%  |
| Lexmark International | 2        | 11.76%  |
| Seiko Epson           | 1        | 5.88%   |
| Ricoh                 | 1        | 5.88%   |
| Kyocera               | 1        | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                                             | Desktops | Percent |
|-------------------------------------------------------------------------------------------------------------------|----------|---------|
| Seiko Epson USB2.0 Printer (Hi-speed)                                                                             | 1        | 5.56%   |
| Ricoh SP 112                                                                                                      | 1        | 5.56%   |
| Lexmark International SINDOH A603_A608 Print                                                                      | 1        | 5.56%   |
| Lexmark International Lexmark MS710 Print                                                                         | 1        | 5.56%   |
| Kyocera FS-1025MFP                                                                                                | 1        | 5.56%   |
| HP LaserJet P3005                                                                                                 | 1        | 5.56%   |
| HP LaserJet 2200                                                                                                  | 1        | 5.56%   |
| HP LaserJet 1200                                                                                                  | 1        | 5.56%   |
| HP HP LaserJet P2035 HP Print                                                                                     | 1        | 5.56%   |
| HP HP LaserJet MFP E52645 LaserJet 0 LaserJet 0 LaserJet 1 LaserJet 1 LaserJet 2 LaserJet 2 LaserJet 3 LaserJet 3 | 1        | 5.56%   |
| HP DeskJet 5850c                                                                                                  | 1        | 5.56%   |
| HP Color LaserJet CP1215                                                                                          | 1        | 5.56%   |
| Brother MFC-L2685DW                                                                                               | 1        | 5.56%   |
| Brother MFC-J200                                                                                                  | 1        | 5.56%   |
| Brother MFC-7360N                                                                                                 | 1        | 5.56%   |
| Brother HL-L2310D series                                                                                          | 1        | 5.56%   |
| Brother HL-1430 Laser Printer                                                                                     | 1        | 5.56%   |
| Brother DCP-J100                                                                                                  | 1        | 5.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Canon       | 2        | 66.67%  |
| Seiko Epson | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Desktops | Percent |
|-------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                             | 2        | 66.67%  |
| Seiko Epson WF-2860 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 14       | 28.57%  |
| Z-Star Microelectronics       | 6        | 12.24%  |
| Microdia                      | 5        | 10.2%   |
| Chicony Electronics           | 3        | 6.12%   |
| Arkmicro Technologies         | 3        | 6.12%   |
| IMC Networks                  | 2        | 4.08%   |
| Hewlett-Packard               | 2        | 4.08%   |
| Generalplus Technology        | 2        | 4.08%   |
| ARC International             | 2        | 4.08%   |
| Sunplus Innovation Technology | 1        | 2.04%   |
| Linux Foundation              | 1        | 2.04%   |
| KYE Systems (Mouse Systems)   | 1        | 2.04%   |
| HD WEBCAM                     | 1        | 2.04%   |
| Genesys Logic                 | 1        | 2.04%   |
| GEMBIRD                       | 1        | 2.04%   |
| Creative Technology           | 1        | 2.04%   |
| Aveo Technology               | 1        | 2.04%   |
| Alcor Micro                   | 1        | 2.04%   |
| A4Tech                        | 1        | 2.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 3        | 6.12%   |
| Logitech HD Pro Webcam C920                       | 3        | 6.12%   |
| Z-Star Venus USB2.0 Camera                        | 2        | 4.08%   |
| Microdia ASUS USB2.0 Webcam                       | 2        | 4.08%   |
| Logitech Webcam C310                              | 2        | 4.08%   |
| Logitech C922 Pro Stream Webcam                   | 2        | 4.08%   |
| IMC Networks XHC Camera                           | 2        | 4.08%   |
| Generalplus GENERAL WEBCAM                        | 2        | 4.08%   |
| Arkmicro USB2.0 PC CAMERA                         | 2        | 4.08%   |
| ARC International Camera                          | 2        | 4.08%   |
| Z-Star Vega USB 2.0 Camera                        | 1        | 2.04%   |
| Z-Star Lenovo USB2.0 UVC Camera                   | 1        | 2.04%   |
| Z-Star Integrated Camera                          | 1        | 2.04%   |
| Z-Star A4 TECH USB2.0 PC Camera J                 | 1        | 2.04%   |
| Sunplus Aukey-PC-LM1E Camera                      | 1        | 2.04%   |
| Microdia Webcam Vitade AF                         | 1        | 2.04%   |
| Microdia FHD Webcam                               | 1        | 2.04%   |
| Microdia Camera                                   | 1        | 2.04%   |
| Logitech Webcam C930e                             | 1        | 2.04%   |
| Logitech Webcam C170                              | 1        | 2.04%   |
| Logitech C670i FHD Webcam                         | 1        | 2.04%   |
| Logitech BRIO Ultra HD Webcam                     | 1        | 2.04%   |
| Linux Foundation HD Camera                        | 1        | 2.04%   |
| KYE Systems (Mouse Systems) AUKEY PC-LM1E Camera  | 1        | 2.04%   |
| HP Realtek PC Camera                              | 1        | 2.04%   |
| HP Premium Starter Webcam                         | 1        | 2.04%   |
| HD WEBCAM HD WEBCAM                               | 1        | 2.04%   |
| Genesys Logic Digital Microscope                  | 1        | 2.04%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 2.04%   |
| Creative Webcam Instant                           | 1        | 2.04%   |
| Chicony HP Integrated Webcam                      | 1        | 2.04%   |
| Chicony HP Display Camera                         | 1        | 2.04%   |
| Chicony HP 0.3MP Webcam                           | 1        | 2.04%   |
| Aveo Camera                                       | 1        | 2.04%   |
| Arkmicro Webcam Carrefour                         | 1        | 2.04%   |
| Alcor Micro PC Camera                             | 1        | 2.04%   |
| A4Tech A4tech FHD 1080P PC Camera                 | 1        | 2.04%   |

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
| 1     | 218      | 46.48%  |
| 0     | 179      | 38.17%  |
| 2     | 59       | 12.58%  |
| 3     | 10       | 2.13%   |
| 4     | 3        | 0.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 239      | 67.9%   |
| Net/wireless             | 57       | 16.19%  |
| Sound                    | 20       | 5.68%   |
| Firewire controller      | 9        | 2.56%   |
| Bluetooth                | 9        | 2.56%   |
| Card reader              | 8        | 2.27%   |
| Network                  | 5        | 1.42%   |
| Net/ethernet             | 4        | 1.14%   |
| Storage/raid             | 1        | 0.28%   |

