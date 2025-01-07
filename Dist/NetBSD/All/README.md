NetBSD - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for NetBSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/NetBSD/Desktop/README.md) and [notebooks](/Dist/NetBSD/Notebook/README.md).

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

Total: 171

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| HUAWEI        | KPL-W0X                     | Notebook    | [ac7b8b09f0](https://bsd-hardware.info/?probe=ac7b8b09f0) | Dec 24, 2024 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [279c62fea7](https://bsd-hardware.info/?probe=279c62fea7) | Nov 22, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [17b78fd12d](https://bsd-hardware.info/?probe=17b78fd12d) | Oct 14, 2024 |
| Lenovo        | 3130 NOK                    | Mini pc     | [5669374138](https://bsd-hardware.info/?probe=5669374138) | Sep 04, 2024 |
| Lenovo        | ThinkPad A285 20MXS01R00    | Notebook    | [9c548c9ffb](https://bsd-hardware.info/?probe=9c548c9ffb) | Sep 01, 2024 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [f78f3487b8](https://bsd-hardware.info/?probe=f78f3487b8) | Aug 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [424a038d10](https://bsd-hardware.info/?probe=424a038d10) | Aug 16, 2024 |
| eMachines     | eM250                       | Notebook    | [98c37607a3](https://bsd-hardware.info/?probe=98c37607a3) | Aug 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ffdc8ec717](https://bsd-hardware.info/?probe=ffdc8ec717) | Aug 15, 2024 |
| Lenovo        | ThinkPad X260 20F60097US    | Notebook    | [248dd70da2](https://bsd-hardware.info/?probe=248dd70da2) | Jul 25, 2024 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [ed6505a58e](https://bsd-hardware.info/?probe=ed6505a58e) | Jul 19, 2024 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [b1de030d31](https://bsd-hardware.info/?probe=b1de030d31) | Jul 19, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [bc76e0ecdb](https://bsd-hardware.info/?probe=bc76e0ecdb) | Jul 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [ae3e63c3e6](https://bsd-hardware.info/?probe=ae3e63c3e6) | Jun 25, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [3589bb8629](https://bsd-hardware.info/?probe=3589bb8629) | Jun 16, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [5c5138d19f](https://bsd-hardware.info/?probe=5c5138d19f) | Jun 08, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [ab9b2e3147](https://bsd-hardware.info/?probe=ab9b2e3147) | Jun 07, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [9b896d73b3](https://bsd-hardware.info/?probe=9b896d73b3) | Jun 07, 2024 |
| Intel         | NUC8BEB J72688-306          | Mini pc     | [80440d6327](https://bsd-hardware.info/?probe=80440d6327) | Jun 06, 2024 |
| Dell          | Precision 7520              | Notebook    | [48232bd1d6](https://bsd-hardware.info/?probe=48232bd1d6) | Jun 06, 2024 |
| HP            | 8594                        | Desktop     | [39702449a8](https://bsd-hardware.info/?probe=39702449a8) | May 20, 2024 |
| MSI           | GE62 6QC                    | Notebook    | [d8fe2ac91a](https://bsd-hardware.info/?probe=d8fe2ac91a) | May 18, 2024 |
| GEEKOM        | Mini IT13                   | Desktop     | [18e5e61859](https://bsd-hardware.info/?probe=18e5e61859) | May 18, 2024 |
| HP            | 8594                        | Desktop     | [209ddea7e7](https://bsd-hardware.info/?probe=209ddea7e7) | May 17, 2024 |
| Lenovo        | 3136 NOK                    | Mini pc     | [b9552d38f2](https://bsd-hardware.info/?probe=b9552d38f2) | May 15, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [0f9e113064](https://bsd-hardware.info/?probe=0f9e113064) | May 14, 2024 |
| Acer          | TravelMate B118-M           | Notebook    | [66fbf7ab6c](https://bsd-hardware.info/?probe=66fbf7ab6c) | May 12, 2024 |
| Unknown       | Unknown                     | Desktop     | [c70960854a](https://bsd-hardware.info/?probe=c70960854a) | May 06, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [23e113910f](https://bsd-hardware.info/?probe=23e113910f) | May 05, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [55560acf02](https://bsd-hardware.info/?probe=55560acf02) | May 05, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B      | Soc         | [755a7a8614](https://bsd-hardware.info/?probe=755a7a8614) | Apr 28, 2024 |
| Lenovo        | 3743 NOK                    | Desktop     | [4b8389c575](https://bsd-hardware.info/?probe=4b8389c575) | Apr 27, 2024 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [47b751dfa0](https://bsd-hardware.info/?probe=47b751dfa0) | Apr 20, 2024 |
| Timi          | TM1612                      | Notebook    | [c139dfdf05](https://bsd-hardware.info/?probe=c139dfdf05) | Apr 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [a818576415](https://bsd-hardware.info/?probe=a818576415) | Apr 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d8288ba73a](https://bsd-hardware.info/?probe=d8288ba73a) | Apr 09, 2024 |
| Gigabyte      | B360M D2V                   | Desktop     | [766a437527](https://bsd-hardware.info/?probe=766a437527) | Apr 07, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [3208fef860](https://bsd-hardware.info/?probe=3208fef860) | Apr 04, 2024 |
| Google        | Monroe                      | Desktop     | [7c9648d197](https://bsd-hardware.info/?probe=7c9648d197) | Apr 04, 2024 |
| Google        | Monroe                      | Desktop     | [383d7ee0f2](https://bsd-hardware.info/?probe=383d7ee0f2) | Apr 04, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [767ef499db](https://bsd-hardware.info/?probe=767ef499db) | Apr 03, 2024 |
| Unknown       | Unknown                     | Desktop     | [3bcc4b4df3](https://bsd-hardware.info/?probe=3bcc4b4df3) | Mar 31, 2024 |
| Lenovo        | ThinkPad X260 20F60097US    | Notebook    | [5fa2016fc1](https://bsd-hardware.info/?probe=5fa2016fc1) | Mar 11, 2024 |
| Lenovo        | ThinkPad T490 20N3S4PX02    | Notebook    | [0dc4820d7e](https://bsd-hardware.info/?probe=0dc4820d7e) | Mar 05, 2024 |
| Lenovo        | ThinkPad T490 20N3S4PX02    | Notebook    | [c3f8fdaebb](https://bsd-hardware.info/?probe=c3f8fdaebb) | Mar 05, 2024 |
| Lenovo        | ThinkPad T480s 20L8S45W0... | Notebook    | [6c6fcc3427](https://bsd-hardware.info/?probe=6c6fcc3427) | Mar 04, 2024 |
| Lenovo        | ThinkPad T480s 20L8S45W0... | Notebook    | [b35f962bce](https://bsd-hardware.info/?probe=b35f962bce) | Mar 01, 2024 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [13c1963782](https://bsd-hardware.info/?probe=13c1963782) | Mar 01, 2024 |
| MSI           | KA790GX                     | Desktop     | [7b431178e5](https://bsd-hardware.info/?probe=7b431178e5) | Feb 25, 2024 |
| Unknown       | Unknown                     | Desktop     | [d3ed7d1552](https://bsd-hardware.info/?probe=d3ed7d1552) | Feb 24, 2024 |
| Dell          | 096JG8 A01                  | Desktop     | [5a03257c9a](https://bsd-hardware.info/?probe=5a03257c9a) | Feb 19, 2024 |
| Dell          | Precision 7520              | Notebook    | [bd40dd5305](https://bsd-hardware.info/?probe=bd40dd5305) | Feb 19, 2024 |
| Intel         | Jasper Lake Client Platf... | Notebook    | [6a041adf7a](https://bsd-hardware.info/?probe=6a041adf7a) | Feb 19, 2024 |
| Lenovo        | ThinkPad T410 2518A37       | Notebook    | [b2515cf7fb](https://bsd-hardware.info/?probe=b2515cf7fb) | Feb 19, 2024 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | Notebook    | [05ecc99fe8](https://bsd-hardware.info/?probe=05ecc99fe8) | Feb 13, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [9b41695cf4](https://bsd-hardware.info/?probe=9b41695cf4) | Jan 30, 2024 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [14e2e2c18c](https://bsd-hardware.info/?probe=14e2e2c18c) | Jan 16, 2024 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [d318950ac5](https://bsd-hardware.info/?probe=d318950ac5) | Jan 15, 2024 |
| Samsung       | N150/N210/N220              | Notebook    | [92c052e0d7](https://bsd-hardware.info/?probe=92c052e0d7) | Jan 14, 2024 |
| Unknown       | Unknown                     | Desktop     | [5deb235717](https://bsd-hardware.info/?probe=5deb235717) | Jan 05, 2024 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [5d4fc3e285](https://bsd-hardware.info/?probe=5d4fc3e285) | Jan 05, 2024 |
| Unknown       | Unknown                     | Desktop     | [d4bedea996](https://bsd-hardware.info/?probe=d4bedea996) | Dec 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [19daaf5eee](https://bsd-hardware.info/?probe=19daaf5eee) | Dec 30, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [c1c8f32b44](https://bsd-hardware.info/?probe=c1c8f32b44) | Dec 30, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [4ccf9a2566](https://bsd-hardware.info/?probe=4ccf9a2566) | Dec 21, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [f3a2321558](https://bsd-hardware.info/?probe=f3a2321558) | Nov 29, 2023 |
| Google        | Kohaku                      | Notebook    | [94c3c0f6b7](https://bsd-hardware.info/?probe=94c3c0f6b7) | Nov 26, 2023 |
| Google        | Kohaku                      | Notebook    | [198b445c4e](https://bsd-hardware.info/?probe=198b445c4e) | Nov 26, 2023 |
| HP            | ProLiant DL360 G5           | Server      | [8b2811bcf5](https://bsd-hardware.info/?probe=8b2811bcf5) | Nov 14, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [875b045b38](https://bsd-hardware.info/?probe=875b045b38) | Oct 29, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [424c33d278](https://bsd-hardware.info/?probe=424c33d278) | Oct 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [a88541d6a6](https://bsd-hardware.info/?probe=a88541d6a6) | Oct 27, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [753b30d88b](https://bsd-hardware.info/?probe=753b30d88b) | Oct 27, 2023 |
| ASRock        | H270 Pro4                   | Desktop     | [cba80ecde3](https://bsd-hardware.info/?probe=cba80ecde3) | Sep 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [dcf1ebd901](https://bsd-hardware.info/?probe=dcf1ebd901) | Sep 20, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [1808e7891c](https://bsd-hardware.info/?probe=1808e7891c) | Sep 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [9c1891cda7](https://bsd-hardware.info/?probe=9c1891cda7) | Sep 03, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [2beb3e34d8](https://bsd-hardware.info/?probe=2beb3e34d8) | Aug 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [29fc7f6f45](https://bsd-hardware.info/?probe=29fc7f6f45) | Aug 19, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [d1a2b99edc](https://bsd-hardware.info/?probe=d1a2b99edc) | Jul 28, 2023 |
| Intel         | NUC5i7RYB H73774-102        | Mini pc     | [a2119ba1fe](https://bsd-hardware.info/?probe=a2119ba1fe) | Jul 10, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | Notebook    | [6969cd9e1a](https://bsd-hardware.info/?probe=6969cd9e1a) | Jun 20, 2023 |
| Acer          | Revo RN86                   | Desktop     | [2e52c2b9b2](https://bsd-hardware.info/?probe=2e52c2b9b2) | May 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [d6f92a5ecc](https://bsd-hardware.info/?probe=d6f92a5ecc) | Apr 28, 2023 |
| Samsung       | DP700A3D-A05UK SEC_SW_RE... | All in one  | [5718d8d05e](https://bsd-hardware.info/?probe=5718d8d05e) | Apr 24, 2023 |
| HP            | Pavilion 17                 | Notebook    | [0f891b4377](https://bsd-hardware.info/?probe=0f891b4377) | Apr 21, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [f73cb94828](https://bsd-hardware.info/?probe=f73cb94828) | Apr 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [8c93a7e552](https://bsd-hardware.info/?probe=8c93a7e552) | Mar 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [85fdc49ec4](https://bsd-hardware.info/?probe=85fdc49ec4) | Mar 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [8ae1891a85](https://bsd-hardware.info/?probe=8ae1891a85) | Feb 16, 2023 |
| Lenovo        | ThinkPad 13 20GJCTO1WW      | Notebook    | [59713ca193](https://bsd-hardware.info/?probe=59713ca193) | Feb 15, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [5921937764](https://bsd-hardware.info/?probe=5921937764) | Feb 06, 2023 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [5f6f4145d4](https://bsd-hardware.info/?probe=5f6f4145d4) | Feb 06, 2023 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [ae05d4c6cd](https://bsd-hardware.info/?probe=ae05d4c6cd) | Feb 06, 2023 |
| Lenovo        | ThinkPad T460s 20FAS3L00... | Notebook    | [ef6972d07a](https://bsd-hardware.info/?probe=ef6972d07a) | Jan 03, 2023 |
| Acer          | Revo RN86                   | Desktop     | [a4dcb7f7a2](https://bsd-hardware.info/?probe=a4dcb7f7a2) | Nov 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [1d3bd58d18](https://bsd-hardware.info/?probe=1d3bd58d18) | Nov 25, 2022 |
| Dell          | Precision M4500             | Notebook    | [ab63467f38](https://bsd-hardware.info/?probe=ab63467f38) | Nov 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [410283dd4f](https://bsd-hardware.info/?probe=410283dd4f) | Oct 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [5e2f93a960](https://bsd-hardware.info/?probe=5e2f93a960) | Aug 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [66fefba790](https://bsd-hardware.info/?probe=66fefba790) | Aug 06, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [aeee3a91e6](https://bsd-hardware.info/?probe=aeee3a91e6) | Jul 03, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [4e7d57df3b](https://bsd-hardware.info/?probe=4e7d57df3b) | Apr 18, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [6bf51cc915](https://bsd-hardware.info/?probe=6bf51cc915) | Mar 28, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [57765224eb](https://bsd-hardware.info/?probe=57765224eb) | Mar 18, 2022 |
| Gigabyte      | 970A-D3P                    | Desktop     | [fa03bdabb6](https://bsd-hardware.info/?probe=fa03bdabb6) | Mar 15, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [0394e3272e](https://bsd-hardware.info/?probe=0394e3272e) | Mar 03, 2022 |
| KLLISRE       | X99-B5 V1.0                 | Desktop     | [5dea1304b9](https://bsd-hardware.info/?probe=5dea1304b9) | Feb 26, 2022 |
| MiTAC         | 5033                        | Notebook    | [54df5c9e9e](https://bsd-hardware.info/?probe=54df5c9e9e) | Feb 10, 2022 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [18eeaf2963](https://bsd-hardware.info/?probe=18eeaf2963) | Dec 29, 2021 |
| Acer          | Revo RN86                   | Desktop     | [6d184a1e62](https://bsd-hardware.info/?probe=6d184a1e62) | Dec 23, 2021 |
| ASRock        | 970 Extreme3                | Desktop     | [14907c62f1](https://bsd-hardware.info/?probe=14907c62f1) | Dec 04, 2021 |
| HP            | 3397                        | Desktop     | [155eceb394](https://bsd-hardware.info/?probe=155eceb394) | Nov 07, 2021 |
| Lenovo        | ThinkPad T420 4236D26       | Notebook    | [5c64875424](https://bsd-hardware.info/?probe=5c64875424) | Oct 12, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [7259ec87e9](https://bsd-hardware.info/?probe=7259ec87e9) | Oct 05, 2021 |
| ASUSTek       | X555LJ                      | Notebook    | [81dd2ba2f0](https://bsd-hardware.info/?probe=81dd2ba2f0) | Oct 02, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c574dcc409](https://bsd-hardware.info/?probe=c574dcc409) | Oct 01, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [b3a18fcab3](https://bsd-hardware.info/?probe=b3a18fcab3) | Sep 29, 2021 |
| Unknown       | Unknown                     | Desktop     | [2a56bcb7c1](https://bsd-hardware.info/?probe=2a56bcb7c1) | Sep 19, 2021 |
| Toshiba       | Satellite A100              | Notebook    | [9ccf97d62c](https://bsd-hardware.info/?probe=9ccf97d62c) | Sep 05, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [4e3b1f226b](https://bsd-hardware.info/?probe=4e3b1f226b) | Jun 22, 2021 |
| Sony          | SVF1421DSGW                 | Notebook    | [abadb65058](https://bsd-hardware.info/?probe=abadb65058) | Jun 01, 2021 |
| Unknown       | Unknown                     | Desktop     | [f9fa9ae41a](https://bsd-hardware.info/?probe=f9fa9ae41a) | May 24, 2021 |
| Acer          | Revo RN86                   | Desktop     | [ec302a221a](https://bsd-hardware.info/?probe=ec302a221a) | May 15, 2021 |
| Unknown       | Unknown                     | Desktop     | [364a778de1](https://bsd-hardware.info/?probe=364a778de1) | May 14, 2021 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [82e63b3fb9](https://bsd-hardware.info/?probe=82e63b3fb9) | Apr 14, 2021 |
| Unknown       | Unknown                     | Desktop     | [df793cf09f](https://bsd-hardware.info/?probe=df793cf09f) | Apr 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [f8ba0ba112](https://bsd-hardware.info/?probe=f8ba0ba112) | Apr 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [0541b120c2](https://bsd-hardware.info/?probe=0541b120c2) | Apr 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [91dd02d436](https://bsd-hardware.info/?probe=91dd02d436) | Mar 30, 2021 |
| Unknown       | Unknown                     | Desktop     | [a1220fba93](https://bsd-hardware.info/?probe=a1220fba93) | Mar 24, 2021 |
| Unknown       | Unknown                     | Desktop     | [edea2d1a64](https://bsd-hardware.info/?probe=edea2d1a64) | Mar 18, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [360f29bf3b](https://bsd-hardware.info/?probe=360f29bf3b) | Mar 05, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [f6e7638f87](https://bsd-hardware.info/?probe=f6e7638f87) | Mar 05, 2021 |
| Unknown       | Unknown                     | Desktop     | [1afd7d4381](https://bsd-hardware.info/?probe=1afd7d4381) | Feb 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [4c0171bc04](https://bsd-hardware.info/?probe=4c0171bc04) | Feb 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [a5fa760573](https://bsd-hardware.info/?probe=a5fa760573) | Jan 02, 2021 |
| IBM           | ThinkPad R51 2887AVG        | Notebook    | [289177c624](https://bsd-hardware.info/?probe=289177c624) | Jan 02, 2021 |
| IBM           | ThinkPad R51 2887AVG        | Notebook    | [88d4fc2693](https://bsd-hardware.info/?probe=88d4fc2693) | Dec 30, 2020 |
| Lenovo        | ThinkPad T430s 23564H3      | Notebook    | [eda02dc46b](https://bsd-hardware.info/?probe=eda02dc46b) | Dec 25, 2020 |
| Fujitsu Si... | AMILO L7310                 | Notebook    | [0603b64315](https://bsd-hardware.info/?probe=0603b64315) | Dec 25, 2020 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [647ab5967e](https://bsd-hardware.info/?probe=647ab5967e) | Dec 22, 2020 |
| Unknown       | Unknown                     | Desktop     | [8668b1d651](https://bsd-hardware.info/?probe=8668b1d651) | Dec 17, 2020 |
| ASUSTek       | E45M1-I DELUXE              | Desktop     | [8e767b517d](https://bsd-hardware.info/?probe=8e767b517d) | Dec 16, 2020 |
| Unknown       | Unknown                     | Desktop     | [153be3caa3](https://bsd-hardware.info/?probe=153be3caa3) | Nov 28, 2020 |
| HP            | System Board R3A            | Desktop     | [80593fc3da](https://bsd-hardware.info/?probe=80593fc3da) | Nov 03, 2020 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [615ac68e50](https://bsd-hardware.info/?probe=615ac68e50) | Oct 29, 2020 |
| Unknown       | Unknown                     | Desktop     | [d08d610bd0](https://bsd-hardware.info/?probe=d08d610bd0) | Oct 29, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [a4e45f3551](https://bsd-hardware.info/?probe=a4e45f3551) | Oct 22, 2020 |
| ASUSTek       | B150M-K                     | Desktop     | [135db0e455](https://bsd-hardware.info/?probe=135db0e455) | Oct 22, 2020 |
| Unknown       | Unknown                     | Desktop     | [223aa9e0a3](https://bsd-hardware.info/?probe=223aa9e0a3) | Oct 22, 2020 |
| Gigabyte      | P75-D3                      | Desktop     | [980218cf46](https://bsd-hardware.info/?probe=980218cf46) | Oct 02, 2020 |
| ASUSTek       | H81M-D PLUS                 | Desktop     | [95b75130f4](https://bsd-hardware.info/?probe=95b75130f4) | Sep 26, 2020 |
| Dell          | 0W7H8C A03                  | Server      | [639b47e2ad](https://bsd-hardware.info/?probe=639b47e2ad) | Sep 21, 2020 |
| Acer          | Revo RN86                   | Desktop     | [c6b2c64d14](https://bsd-hardware.info/?probe=c6b2c64d14) | Sep 20, 2020 |
| ASUSTek       | H81M-D PLUS                 | Desktop     | [7be45f1bec](https://bsd-hardware.info/?probe=7be45f1bec) | Sep 19, 2020 |
| MSI           | KA790GX                     | Desktop     | [bba5499a4b](https://bsd-hardware.info/?probe=bba5499a4b) | Aug 29, 2020 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [7f6095b266](https://bsd-hardware.info/?probe=7f6095b266) | Aug 20, 2020 |
| eMachines     | eME642G                     | Notebook    | [42027dfbb9](https://bsd-hardware.info/?probe=42027dfbb9) | Jul 25, 2020 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [35c4a3608e](https://bsd-hardware.info/?probe=35c4a3608e) | Jul 19, 2020 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [9fbca0a216](https://bsd-hardware.info/?probe=9fbca0a216) | Jun 17, 2020 |
| Lenovo        | G500 20236                  | Notebook    | [99cf14c489](https://bsd-hardware.info/?probe=99cf14c489) | Jun 03, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a49cf5c20b](https://bsd-hardware.info/?probe=a49cf5c20b) | May 28, 2020 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [14e00aa09f](https://bsd-hardware.info/?probe=14e00aa09f) | May 25, 2020 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [6cb240a9f6](https://bsd-hardware.info/?probe=6cb240a9f6) | May 25, 2020 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [8ba62bd121](https://bsd-hardware.info/?probe=8ba62bd121) | May 25, 2020 |
| Lenovo        | ThinkPad X240 20AMS0J01N    | Notebook    | [4df07718d1](https://bsd-hardware.info/?probe=4df07718d1) | May 23, 2020 |
| Unknown       | Unknown                     | Desktop     | [d3ad2b17ed](https://bsd-hardware.info/?probe=d3ad2b17ed) | May 22, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [3258f01592](https://bsd-hardware.info/?probe=3258f01592) | May 16, 2020 |
| ASUSTek       | A3L                         | Notebook    | [6b65fcf9c1](https://bsd-hardware.info/?probe=6b65fcf9c1) | May 15, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [cd45078232](https://bsd-hardware.info/?probe=cd45078232) | May 05, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| NetBSD 10.0        | 26        | 18.98%  |
| NetBSD 9.3         | 17        | 12.41%  |
| NetBSD 9.2         | 13        | 9.49%   |
| NetBSD 9.1         | 11        | 8.03%   |
| NetBSD 9.0_STABLE  | 8         | 5.84%   |
| NetBSD 9.0         | 6         | 4.38%   |
| NetBSD 10.0_RC2    | 5         | 3.65%   |
| NetBSD 10.0_RC1    | 5         | 3.65%   |
| NetBSD 10.0_BETA   | 5         | 3.65%   |
| NetBSD 10.0_RC4    | 4         | 2.92%   |
| NetBSD 9.99.94     | 3         | 2.19%   |
| NetBSD 9.99.93     | 3         | 2.19%   |
| NetBSD 9.1_STABLE  | 3         | 2.19%   |
| NetBSD 10.0_RC5    | 3         | 2.19%   |
| NetBSD 9.99.77     | 2         | 1.46%   |
| NetBSD 9.3_STABLE  | 2         | 1.46%   |
| NetBSD 9.2_STABLE  | 2         | 1.46%   |
| NetBSD 10.0_STABLE | 2         | 1.46%   |
| NetBSD 10.0_RC3    | 2         | 1.46%   |
| NetBSD 9.99.85     | 1         | 0.73%   |
| NetBSD 9.99.81     | 1         | 0.73%   |
| NetBSD 9.99.74     | 1         | 0.73%   |
| NetBSD 9.99.71     | 1         | 0.73%   |
| NetBSD 9.99.61     | 1         | 0.73%   |
| NetBSD 9.99.23     | 1         | 0.73%   |
| NetBSD 9.99.107    | 1         | 0.73%   |
| NetBSD 8.99.51     | 1         | 0.73%   |
| NetBSD 8.2         | 1         | 0.73%   |
| NetBSD 7.2         | 1         | 0.73%   |
| NetBSD 10.99.7     | 1         | 0.73%   |
| NetBSD 10.99.12    | 1         | 0.73%   |
| NetBSD 10.99.10    | 1         | 0.73%   |
| NetBSD 10.99.1     | 1         | 0.73%   |
| NetBSD 10.1        | 1         | 0.73%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| NetBSD | 122       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 94        | 77.05%  |
| evbarm  | 16        | 13.11%  |
| i386    | 9         | 7.38%   |
| macppc  | 2         | 1.64%   |
| sparc64 | 1         | 0.82%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 47        | 37.6%   |
| XFCE         | 31        | 24.8%   |
| helloDesktop | 9         | 7.2%    |
| CTWM         | 6         | 4.8%    |
| MATE         | 5         | 4%      |
| Fluxbox      | 5         | 4%      |
| DWM          | 4         | 3.2%    |
| iwm          | 3         | 2.4%    |
| Ratpoison    | 2         | 1.6%    |
| LXQt         | 2         | 1.6%    |
| GNOME        | 2         | 1.6%    |
| Xfwm4        | 1         | 0.8%    |
| Window Maker | 1         | 0.8%    |
| spectrwm     | 1         | 0.8%    |
| sdorfehs     | 1         | 0.8%    |
| PekWM        | 1         | 0.8%    |
| JWM          | 1         | 0.8%    |
| IceWM        | 1         | 0.8%    |
| i3           | 1         | 0.8%    |
| Awesome      | 1         | 0.8%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 94        | 77.05%  |
| Console | 28        | 22.95%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 107       | 87.7%   |
| SLiM    | 8         | 6.56%   |
| XDM     | 4         | 3.28%   |
| GDM     | 2         | 1.64%   |
| LightDM | 1         | 0.82%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 96        | 75%     |
| en_US   | 18        | 14.06%  |
| ru_RU   | 3         | 2.34%   |
| fr_FR   | 2         | 1.56%   |
| fi_FI   | 2         | 1.56%   |
| es_ES   | 2         | 1.56%   |
| C       | 2         | 1.56%   |
| hu_HU   | 1         | 0.78%   |
| es_MX   | 1         | 0.78%   |
| en_GB   | 1         | 0.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 117       | 95.9%   |
| EFI  | 5         | 4.1%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 119       | 97.54%  |
| Ffs     | 1         | 0.82%   |
| Cd9660  | 1         | 0.82%   |
| Unknown | 1         | 0.82%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 85        | 69.11%  |
| Unknown | 38        | 30.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Unknown                 | 26        | 21.31%  |
| Lenovo                  | 19        | 15.57%  |
| ASUSTek Computer        | 11        | 9.02%   |
| Raspberry Pi Foundation | 10        | 8.2%    |
| Gigabyte Technology     | 9         | 7.38%   |
| Intel                   | 6         | 4.92%   |
| Dell                    | 5         | 4.1%    |
| ASRock                  | 5         | 4.1%    |
| Apple                   | 5         | 4.1%    |
| Hewlett-Packard         | 4         | 3.28%   |
| Samsung Electronics     | 3         | 2.46%   |
| MSI                     | 3         | 2.46%   |
| Acer                    | 3         | 2.46%   |
| Google                  | 2         | 1.64%   |
| eMachines               | 2         | 1.64%   |
| Toshiba                 | 1         | 0.82%   |
| Timi                    | 1         | 0.82%   |
| Sony                    | 1         | 0.82%   |
| MiTAC                   | 1         | 0.82%   |
| KLLISRE                 | 1         | 0.82%   |
| IBM                     | 1         | 0.82%   |
| HUAWEI                  | 1         | 0.82%   |
| GEEKOM                  | 1         | 0.82%   |
| Fujitsu Siemens         | 1         | 0.82%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 26        | 21.31%  |
| RPi Raspberry Pi                            | 6         | 4.92%   |
| RPi Raspberry Pi 4 Model B                  | 3         | 2.46%   |
| ASUS PRIME A320M-K                          | 2         | 1.64%   |
| Toshiba Satellite A100                      | 1         | 0.82%   |
| Timi TM1612                                 | 1         | 0.82%   |
| Sony SVF1421DSGW                            | 1         | 0.82%   |
| Samsung N150/N210/N220                      | 1         | 0.82%   |
| Samsung DP700A3D/DM700A3D/DB701A3D/DP700A7D | 1         | 0.82%   |
| Samsung 530U3C/530U4C/532U3C                | 1         | 0.82%   |
| RPi Raspberry Pi 5 Model B                  | 1         | 0.82%   |
| MSI MS-7B86                                 | 1         | 0.82%   |
| MSI MS-7551                                 | 1         | 0.82%   |
| MSI GE62 6QC                                | 1         | 0.82%   |
| MiTAC 5033                                  | 1         | 0.82%   |
| Lenovo ThinkPad X260 20F60097US             | 1         | 0.82%   |
| Lenovo ThinkPad X240 20AMS0J01N             | 1         | 0.82%   |
| Lenovo ThinkPad T510 4313CTO                | 1         | 0.82%   |
| Lenovo ThinkPad T490 20N3S4PX02             | 1         | 0.82%   |
| Lenovo ThinkPad T480s 20L8S45W00            | 1         | 0.82%   |
| Lenovo ThinkPad T470 W10DG 20JNS0L300       | 1         | 0.82%   |
| Lenovo ThinkPad T470 20HES0EV0A             | 1         | 0.82%   |
| Lenovo ThinkPad T460s 20FAS3L002            | 1         | 0.82%   |
| Lenovo ThinkPad T430s 23564H3               | 1         | 0.82%   |
| Lenovo ThinkPad T430 2347A45                | 1         | 0.82%   |
| Lenovo ThinkPad T420 4236D26                | 1         | 0.82%   |
| Lenovo ThinkPad T410 2518A37                | 1         | 0.82%   |
| Lenovo ThinkPad 13 20GJCTO1WW               | 1         | 0.82%   |
| Lenovo ThinkCentre M920q 10RRS1CB00         | 1         | 0.82%   |
| Lenovo ThinkCentre M920q 10RRS09W00         | 1         | 0.82%   |
| Lenovo ThinkCentre M72e 3598CP8             | 1         | 0.82%   |
| Lenovo ThinkCentre M715q 10VMS05C00         | 1         | 0.82%   |
| Lenovo IdeaCentre Gaming5 14ACN6 90RW005PUL | 1         | 0.82%   |
| Lenovo G500 20236                           | 1         | 0.82%   |
| KLLISRE X99-B5 V1.0                         | 1         | 0.82%   |
| Intel NUC8i7BEH                             | 1         | 0.82%   |
| Intel NUC7PJYH                              | 1         | 0.82%   |
| Intel NUC5PPYB H76558-102                   | 1         | 0.82%   |
| Intel NUC5i7RYB H73774-102                  | 1         | 0.82%   |
| Intel Jasper Lake Client Platform           | 1         | 0.82%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 26        | 21.31%  |
| Lenovo ThinkPad       | 13        | 10.66%  |
| RPi Raspberry         | 10        | 8.2%    |
| Lenovo ThinkCentre    | 4         | 3.28%   |
| ASUS TUF              | 3         | 2.46%   |
| Gigabyte X570         | 2         | 1.64%   |
| Dell Precision        | 2         | 1.64%   |
| ASUS PRIME            | 2         | 1.64%   |
| ASRock 970            | 2         | 1.64%   |
| Acer Aspire           | 2         | 1.64%   |
| Toshiba Satellite     | 1         | 0.82%   |
| Timi TM1612           | 1         | 0.82%   |
| Sony SVF1421DSGW      | 1         | 0.82%   |
| Samsung N150          | 1         | 0.82%   |
| Samsung DP700A3D      | 1         | 0.82%   |
| Samsung 530U3C        | 1         | 0.82%   |
| MSI MS-7B86           | 1         | 0.82%   |
| MSI MS-7551           | 1         | 0.82%   |
| MSI GE62              | 1         | 0.82%   |
| MiTAC 5033            | 1         | 0.82%   |
| Lenovo IdeaCentre     | 1         | 0.82%   |
| Lenovo G500           | 1         | 0.82%   |
| KLLISRE X99-B5        | 1         | 0.82%   |
| Intel NUC8i7BEH       | 1         | 0.82%   |
| Intel NUC7PJYH        | 1         | 0.82%   |
| Intel NUC5PPYB        | 1         | 0.82%   |
| Intel NUC5i7RYB       | 1         | 0.82%   |
| Intel Jasper          | 1         | 0.82%   |
| Intel DN2820FYK       | 1         | 0.82%   |
| IBM ThinkPad          | 1         | 0.82%   |
| HUAWEI KPL-W0X        | 1         | 0.82%   |
| HP Vectra             | 1         | 0.82%   |
| HP ProLiant           | 1         | 0.82%   |
| HP Pavilion           | 1         | 0.82%   |
| HP EliteDesk          | 1         | 0.82%   |
| Google Monroe         | 1         | 0.82%   |
| Google Kohaku         | 1         | 0.82%   |
| Gigabyte Z170X-Gaming | 1         | 0.82%   |
| Gigabyte P75-D3       | 1         | 0.82%   |
| Gigabyte H61M-S2PV    | 1         | 0.82%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 30        | 24.59%  |
| 2020    | 13        | 10.66%  |
| 2018    | 10        | 8.2%    |
| 2013    | 8         | 6.56%   |
| 2021    | 7         | 5.74%   |
| 2016    | 7         | 5.74%   |
| 2022    | 6         | 4.92%   |
| 2019    | 6         | 4.92%   |
| 2017    | 5         | 4.1%    |
| 2010    | 5         | 4.1%    |
| 2014    | 4         | 3.28%   |
| 2024    | 3         | 2.46%   |
| 2015    | 3         | 2.46%   |
| 2012    | 3         | 2.46%   |
| 2011    | 3         | 2.46%   |
| 2007    | 3         | 2.46%   |
| 2005    | 3         | 2.46%   |
| 2023    | 1         | 0.82%   |
| 2009    | 1         | 0.82%   |
| 2001    | 1         | 0.82%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 60        | 49.18%  |
| Notebook       | 41        | 33.61%  |
| System on chip | 10        | 8.2%    |
| Mini pc        | 8         | 6.56%   |
| Server         | 2         | 1.64%   |
| All in one     | 1         | 0.82%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 119       | 97.54%  |
| Yes  | 3         | 2.46%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 32        | 26.02%  |
| 16.01-24.0  | 21        | 17.07%  |
| 8.01-16.0   | 17        | 13.82%  |
| 3.01-4.0    | 13        | 10.57%  |
| 0.01-0.5    | 12        | 9.76%   |
| 32.01-64.0  | 8         | 6.5%    |
| 0.51-1.0    | 6         | 4.88%   |
| 1.01-2.0    | 5         | 4.07%   |
| 24.01-32.0  | 4         | 3.25%   |
| 64.01-256.0 | 3         | 2.44%   |
| 0           | 1         | 0.81%   |
| Unknown     | 1         | 0.81%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| Unknown | 122       | 100%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 0      | 65        | 51.18%  |
| 1      | 42        | 33.07%  |
| 2      | 14        | 11.02%  |
| 4      | 3         | 2.36%   |
| 3      | 3         | 2.36%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 118       | 96.72%  |
| Yes       | 4         | 3.28%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 77.87%  |
| No        | 27        | 22.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 72        | 59.02%  |
| No        | 50        | 40.98%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 68        | 55.74%  |
| Yes       | 54        | 44.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 17        | 13.93%  |
| Russia                 | 17        | 13.93%  |
| Germany                | 11        | 9.02%   |
| France                 | 11        | 9.02%   |
| Italy                  | 9         | 7.38%   |
| Spain                  | 8         | 6.56%   |
| UK                     | 6         | 4.92%   |
| Hungary                | 5         | 4.1%    |
| Poland                 | 4         | 3.28%   |
| Saudi Arabia           | 3         | 2.46%   |
| Romania                | 3         | 2.46%   |
| Finland                | 3         | 2.46%   |
| Denmark                | 3         | 2.46%   |
| Brazil                 | 3         | 2.46%   |
| Vietnam                | 2         | 1.64%   |
| Latvia                 | 2         | 1.64%   |
| Japan                  | 2         | 1.64%   |
| India                  | 2         | 1.64%   |
| Canada                 | 2         | 1.64%   |
| Taiwan                 | 1         | 0.82%   |
| Norway                 | 1         | 0.82%   |
| Netherlands            | 1         | 0.82%   |
| Mexico                 | 1         | 0.82%   |
| Czechia                | 1         | 0.82%   |
| China                  | 1         | 0.82%   |
| Bosnia and Herzegovina | 1         | 0.82%   |
| Austria                | 1         | 0.82%   |
| Australia              | 1         | 0.82%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Ozersk                | 9         | 7.2%    |
| Rome                  | 8         | 6.4%    |
| Moscow                | 5         | 4%      |
| Noyon                 | 4         | 3.2%    |
| Madrid                | 4         | 3.2%    |
| Riyadh                | 3         | 2.4%    |
| Lille                 | 3         | 2.4%    |
| Gardony               | 3         | 2.4%    |
| Frederiksberg         | 3         | 2.4%    |
| Bucharest             | 3         | 2.4%    |
| Berlin                | 3         | 2.4%    |
| Warsaw                | 2         | 1.6%    |
| Tampere               | 2         | 1.6%    |
| Riga                  | 2         | 1.6%    |
| Novosibirsk           | 2         | 1.6%    |
| Long Beach            | 2         | 1.6%    |
| Ho Chi Minh City      | 2         | 1.6%    |
| Higashihatsuishi      | 2         | 1.6%    |
| Hayward               | 2         | 1.6%    |
| A Coruña             | 2         | 1.6%    |
| Washington            | 1         | 0.8%    |
| Urupes                | 1         | 0.8%    |
| Unterhaching          | 1         | 0.8%    |
| Ulan-Ude              | 1         | 0.8%    |
| Turin                 | 1         | 0.8%    |
| Turenki               | 1         | 0.8%    |
| Taipei                | 1         | 0.8%    |
| Sydney                | 1         | 0.8%    |
| Surrey                | 1         | 0.8%    |
| Sun Prairie           | 1         | 0.8%    |
| Stourbridge           | 1         | 0.8%    |
| Sopron                | 1         | 0.8%    |
| Sarajevo              | 1         | 0.8%    |
| Sandnes               | 1         | 0.8%    |
| Royal Tunbridge Wells | 1         | 0.8%    |
| Rio Blanco            | 1         | 0.8%    |
| Reno                  | 1         | 0.8%    |
| Prague                | 1         | 0.8%    |
| Poznan                | 1         | 0.8%    |
| Portland              | 1         | 0.8%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC                                | 13        | 16     | 16.05%  |
| Seagate                            | 12        | 13     | 14.81%  |
| SanDisk                            | 8         | 9      | 9.88%   |
| Kingston                           | 7         | 8      | 8.64%   |
| Samsung Electronics                | 6         | 6      | 7.41%   |
| Toshiba                            | 4         | 6      | 4.94%   |
| Maxtor                             | 3         | 4      | 3.7%    |
| Intel                              | 3         | 3      | 3.7%    |
| Hitachi                            | 3         | 4      | 3.7%    |
| HGST                               | 3         | 3      | 3.7%    |
| Crucial                            | 3         | 4      | 3.7%    |
| JetFlash                           | 2         | 2      | 2.47%   |
| Hewlett-Packard                    | 2         | 2      | 2.47%   |
| Generic                            | 2         | 2      | 2.47%   |
| USB                                | 1         | 1      | 1.23%   |
| SMI                                | 1         | 1      | 1.23%   |
| SK hynix                           | 1         | 2      | 1.23%   |
| Product:              USB DISK 2.0 | 1         | 1      | 1.23%   |
| Lexar                              | 1         | 1      | 1.23%   |
| Intenso                            | 1         | 1      | 1.23%   |
| IBM/Hitachi                        | 1         | 1      | 1.23%   |
| Fanxiang                           | 1         | 1      | 1.23%   |
| Dell                               | 1         | 2      | 1.23%   |
| China                              | 1         | 1      | 1.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Toshiba DT01ACA100 1TB              | 3         | 3.66%   |
| SanDisk Extreme SSD 1TB             | 3         | 3.66%   |
| Seagate ST1000DM010-2EP102 1TB      | 2         | 2.44%   |
| Samsung SSD 860 EVO 500GB           | 2         | 2.44%   |
| Samsung HD103UJ 1TB                 | 2         | 2.44%   |
| Maxtor STM3250310AS 250GB           | 2         | 2.44%   |
| Kingston DataTraveler 3.0 64GB      | 2         | 2.44%   |
| JetFlash Transcend 16GB             | 2         | 2.44%   |
| HGST HTS541010A9E680 1TB            | 2         | 2.44%   |
| WDC WDS240G2G0B-00EPW0 240GB        | 1         | 1.22%   |
| WDC WDS240G2G0A-00JH30 240GB        | 1         | 1.22%   |
| WDC WDS120G2G0A-00JH30 120GB        | 1         | 1.22%   |
| WDC WD5003AZEX-00K3CA0 500GB        | 1         | 1.22%   |
| WDC WD5000AAKX-753CA1 500GB         | 1         | 1.22%   |
| WDC WD5000AACS-00ZUB0 500GB         | 1         | 1.22%   |
| WDC WD2502ABYS-01B7A0 256GB         | 1         | 1.22%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1         | 1.22%   |
| WDC WD200EB-00BHF0 20GB             | 1         | 1.22%   |
| WDC WD1600BEVT-00A23T0 160GB        | 1         | 1.22%   |
| WDC WD10EZRZ-00HTKB0 1TB            | 1         | 1.22%   |
| WDC WD10EZEX-60WN4A0 1TB            | 1         | 1.22%   |
| WDC WD1002FAEX-00Y9A0 1TB           | 1         | 1.22%   |
| WDC WD Elements 2621 2TB            | 1         | 1.22%   |
| USB SanDisk 3.2Gen1 64GB            | 1         | 1.22%   |
| Toshiba DT01ACA200 2TB              | 1         | 1.22%   |
| SMI USB DISK 16GB                   | 1         | 1.22%   |
| SK hynix HFS128G39TND-N210A 128GB   | 1         | 1.22%   |
| Seagate ST940110A 40GB              | 1         | 1.22%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1.22%   |
| Seagate ST500VT000-1DK142 500GB     | 1         | 1.22%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1.22%   |
| Seagate ST380011A 80GB              | 1         | 1.22%   |
| Seagate ST33221A 3GB                | 1         | 1.22%   |
| Seagate ST2000DM001-1CH164 2TB      | 1         | 1.22%   |
| Seagate ST2000DL003-9VT166 2TB      | 1         | 1.22%   |
| Seagate ST1000LM 024 HN-M101MBB 1TB | 1         | 1.22%   |
| Seagate ST1000DX001-1CM162 1TB      | 1         | 1.22%   |
| SanDisk Ultra USB 3.0 64GB          | 1         | 1.22%   |
| SanDisk SSD i110 16GB               | 1         | 1.22%   |
| SanDisk SSD i100 24GB               | 1         | 1.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate                            | 12        | 13     | 22.64%  |
| WDC                                | 11        | 13     | 20.75%  |
| Toshiba                            | 4         | 6      | 7.55%   |
| Samsung Electronics                | 4         | 4      | 7.55%   |
| Maxtor                             | 3         | 4      | 5.66%   |
| Hitachi                            | 3         | 4      | 5.66%   |
| HGST                               | 3         | 3      | 5.66%   |
| JetFlash                           | 2         | 2      | 3.77%   |
| Hewlett-Packard                    | 2         | 2      | 3.77%   |
| Generic                            | 2         | 2      | 3.77%   |
| USB                                | 1         | 1      | 1.89%   |
| SMI                                | 1         | 1      | 1.89%   |
| Product:              USB DISK 2.0 | 1         | 1      | 1.89%   |
| Lexar                              | 1         | 1      | 1.89%   |
| Intenso                            | 1         | 1      | 1.89%   |
| IBM/Hitachi                        | 1         | 1      | 1.89%   |
| Dell                               | 1         | 2      | 1.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 8         | 9      | 27.59%  |
| Kingston            | 7         | 8      | 24.14%  |
| WDC                 | 3         | 3      | 10.34%  |
| Intel               | 3         | 3      | 10.34%  |
| Crucial             | 3         | 4      | 10.34%  |
| Samsung Electronics | 2         | 2      | 6.9%    |
| SK hynix            | 1         | 2      | 3.45%   |
| Fanxiang            | 1         | 1      | 3.45%   |
| China               | 1         | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 40        | 61     | 59.7%   |
| SSD  | 27        | 33     | 40.3%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 58        | 94     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 49        | 62     | 67.12%  |
| 0.51-1.0   | 19        | 23     | 26.03%  |
| 1.01-2.0   | 4         | 7      | 5.48%   |
| 4.01-10.0  | 1         | 2      | 1.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 45        | 36%     |
| 251-500        | 20        | 16%     |
| 501-1000       | 18        | 14.4%   |
| 1-20           | 13        | 10.4%   |
| 51-100         | 12        | 9.6%    |
| 21-50          | 8         | 6.4%    |
| 1001-2000      | 5         | 4%      |
| 2001-3000      | 3         | 2.4%    |
| More than 3000 | 1         | 0.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 91        | 70.54%  |
| 21-50          | 19        | 14.73%  |
| 51-100         | 7         | 5.43%   |
| 101-250        | 4         | 3.1%    |
| 501-1000       | 3         | 2.33%   |
| 251-500        | 2         | 1.55%   |
| 1001-2000      | 2         | 1.55%   |
| More than 3000 | 1         | 0.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB        | 1         | 1      | 6.67%   |
| WDC WD10EZEX-60WN4A0 1TB            | 1         | 1      | 6.67%   |
| SK hynix HFS128G39TND-N210A 128GB   | 1         | 1      | 6.67%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 6.67%   |
| Seagate ST500VT000-1DK142 500GB     | 1         | 1      | 6.67%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1      | 6.67%   |
| Seagate ST2000DL003-9VT166 2TB      | 1         | 1      | 6.67%   |
| Seagate ST1000DX001-1CM162 1TB      | 1         | 1      | 6.67%   |
| Maxtor 6E040L0 40GB                 | 1         | 1      | 6.67%   |
| Intel SSDSC2KW120H6 120GB           | 1         | 1      | 6.67%   |
| Intel SSDSC2CW120A3 120GB           | 1         | 1      | 6.67%   |
| Intel SSDSC2BF180A4L 180GB          | 1         | 1      | 6.67%   |
| IBM/Hitachi IC25N040ATMR04-0 40GB   | 1         | 1      | 6.67%   |
| Hitachi HTS721060G9AT00 64GB        | 1         | 1      | 6.67%   |
| Hitachi HTS548040M9AT00 37GB        | 1         | 2      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 5         | 5      | 33.33%  |
| Intel       | 3         | 3      | 20%     |
| WDC         | 2         | 2      | 13.33%  |
| Hitachi     | 2         | 3      | 13.33%  |
| SK hynix    | 1         | 1      | 6.67%   |
| Maxtor      | 1         | 1      | 6.67%   |
| IBM/Hitachi | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 5         | 5      | 50%     |
| Hitachi     | 2         | 3      | 20%     |
| WDC         | 1         | 1      | 10%     |
| Maxtor      | 1         | 1      | 10%     |
| IBM/Hitachi | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 11     | 66.67%  |
| SSD  | 5         | 5      | 33.33%  |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 37        | 61     | 55.22%  |
| Detected | 15        | 17     | 22.39%  |
| Malfunc  | 15        | 16     | 22.39%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 74        | 53.62%  |
| AMD                            | 24        | 17.39%  |
| Samsung Electronics            | 12        | 8.7%    |
| Phison Electronics             | 5         | 3.62%   |
| Silicon Motion                 | 4         | 2.9%    |
| Micron/Crucial Technology      | 4         | 2.9%    |
| SanDisk                        | 3         | 2.17%   |
| VIA Technologies               | 2         | 1.45%   |
| ULi Electronics                | 1         | 0.72%   |
| Solid State Storage Technology | 1         | 0.72%   |
| SK hynix                       | 1         | 0.72%   |
| Nvidia                         | 1         | 0.72%   |
| Micron Technology              | 1         | 0.72%   |
| Kingston Technology Company    | 1         | 0.72%   |
| Hewlett-Packard                | 1         | 0.72%   |
| Broadcom / LSI                 | 1         | 0.72%   |
| ASMedia Technology             | 1         | 0.72%   |
| Apple                          | 1         | 0.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 12        | 7.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 8         | 5.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 4.61%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 3.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 3.95%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 6         | 3.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 3.29%   |
| AMD 400 Series Chipset SATA Controller                                         | 5         | 3.29%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 4         | 2.63%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 3         | 1.97%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 1.97%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 3         | 1.97%   |
| Intel Alder Lake-N SATA AHCI Controller                                        | 3         | 1.97%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 1.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 1.97%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.97%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 1.97%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                   | 3         | 1.97%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 2         | 1.32%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 2         | 1.32%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2         | 1.32%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 1.32%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.32%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 2         | 1.32%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 2         | 1.32%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.32%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 1.32%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 2         | 1.32%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 1.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.32%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 1.32%   |
| ULi M5229 IDE                                                                  | 1         | 0.66%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 1         | 0.66%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 1         | 0.66%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 1         | 0.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.66%   |
| Phison PS5021-E21 PCIe4 NVMe Controller (DRAM-less)                            | 1         | 0.66%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 0.66%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 92        | 63.45%  |
| NVMe | 33        | 22.76%  |
| IDE  | 16        | 11.03%  |
| RAID | 4         | 2.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Intel           | 77        | 63.11%  |
| AMD             | 25        | 20.49%  |
| Unknown         | 9         | 7.38%   |
| Broadcom        | 4         | 3.28%   |
| Arm             | 3         | 2.46%   |
| 7447A           | 2         | 1.64%   |
| SUNW,UltraAX-i2 | 1         | 0.82%   |
| 123456789ABC    | 1         | 0.82%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel 686-class                                 | 17        | 13.6%   |
|                                                 | 9         | 7.2%    |
| Broadcom BCM2711 (ARM Cortex-A72)               | 3         | 2.4%    |
| ARM Cortex-A53 r0p4 (v8-A)                      | 3         | 2.4%    |
| Intel N100                                      | 2         | 1.6%    |
| Intel Core i5-6300U CPU @ 2.40GHz               | 2         | 1.6%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 2         | 1.6%    |
| Intel Core i3-3217U CPU @ 1.80GHz               | 2         | 1.6%    |
| AMD Ryzen 9 3900X 12-Core Processor             | 2         | 1.6%    |
| AMD 686-class                                   | 2         | 1.6%    |
| 7447A (Revision 1.2)                            | 2         | 1.6%    |
| SUNW,UltraAX-i2 (SUNW,UltraSPARC-IIe @ 500 MHz) | 1         | 0.8%    |
| Intel Xeon CPU E5-2630L v3 @ 1.80GHz            | 1         | 0.8%    |
| Intel Xeon CPU E5-2450L 0 @ 1.80GHz             | 1         | 0.8%    |
| Intel Xeon                                      | 1         | 0.8%    |
| Intel Pentium Silver J5005 CPU @ 1.50GHz        | 1         | 0.8%    |
| Intel Pentium M processor 1.60GHz               | 1         | 0.8%    |
| Intel Pentium M processor                       | 1         | 0.8%    |
| Intel Pentium III                               | 1         | 0.8%    |
| Intel Pentium CPU 2020M @ 2.40GHz               | 1         | 0.8%    |
| Intel Core m3-6Y30 CPU @ 0.90GHz                | 1         | 0.8%    |
| Intel Core i7-9700 CPU @ 3.00GHz                | 1         | 0.8%    |
| Intel Core i7-8559U CPU @ 2.70GHz               | 1         | 0.8%    |
| Intel Core i7-7920HQ CPU @ 3.10GHz              | 1         | 0.8%    |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1         | 0.8%    |
| Intel Core i7-6700K CPU @ 4.00GHz               | 1         | 0.8%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 1         | 0.8%    |
| Intel Core i7-6600U CPU @ 2.60GHz               | 1         | 0.8%    |
| Intel Core i7-5557U CPU @ 3.10GHz               | 1         | 0.8%    |
| Intel Core i7-5500U CPU @ 2.40GHz               | 1         | 0.8%    |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1         | 0.8%    |
| Intel Core i7-3520M CPU @ 2.90GHz               | 1         | 0.8%    |
| Intel Core i7-2640M CPU @ 2.80GHz               | 1         | 0.8%    |
| Intel Core i5-9600K CPU @ 3.70GHz               | 1         | 0.8%    |
| Intel Core i5-9400T CPU @ 1.80GHz               | 1         | 0.8%    |
| Intel Core i5-9400F CPU @ 2.90GHz               | 1         | 0.8%    |
| Intel Core i5-8600T CPU @ 2.30GHz               | 1         | 0.8%    |
| Intel Core i5-8500T CPU @ 2.10GHz               | 1         | 0.8%    |
| Intel Core i5-8500B CPU @ 3.00GHz               | 1         | 0.8%    |
| Intel Core i5-8365U CPU @ 1.60GHz               | 1         | 0.8%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 26        | 20.97%  |
| Other                | 25        | 20.16%  |
| Intel 686-class      | 17        | 13.71%  |
| Intel Core i7        | 12        | 9.68%   |
| Intel Core i3        | 4         | 3.23%   |
| AMD Ryzen 5          | 4         | 3.23%   |
| Intel Xeon           | 3         | 2.42%   |
| Intel Celeron        | 3         | 2.42%   |
| AMD Ryzen 3          | 3         | 2.42%   |
| AMD FX               | 3         | 2.42%   |
| Intel Pentium M      | 2         | 1.61%   |
| Intel Core 2         | 2         | 1.61%   |
| Intel Atom           | 2         | 1.61%   |
| AMD Ryzen 9          | 2         | 1.61%   |
| AMD Ryzen 7          | 2         | 1.61%   |
| AMD 686-class        | 2         | 1.61%   |
| Intel Pentium Silver | 1         | 0.81%   |
| Intel Pentium III    | 1         | 0.81%   |
| Intel Pentium        | 1         | 0.81%   |
| Intel Core m3        | 1         | 0.81%   |
| ARM Cortex           | 1         | 0.81%   |
| AMD Sempron          | 1         | 0.81%   |
| AMD Ryzen 3 PRO      | 1         | 0.81%   |
| AMD Phenom II X6     | 1         | 0.81%   |
| AMD Phenom II X4     | 1         | 0.81%   |
| AMD E                | 1         | 0.81%   |
| AMD Athlon II        | 1         | 0.81%   |
| AMD A10              | 1         | 0.81%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 50        | 40%     |
| 4       | 30        | 24%     |
| 2       | 25        | 20%     |
| 6       | 10        | 8%      |
| 8       | 7         | 5.6%    |
| 12      | 2         | 1.6%    |
| 10      | 1         | 0.8%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 85        | 68.55%  |
| Unknown | 38        | 30.65%  |
| 2       | 1         | 0.81%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 50        | 40.32%  |
| 2       | 41        | 33.06%  |
| 1       | 32        | 25.81%  |
| 6       | 1         | 0.81%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 49        | 39.2%   |
| KabyLake      | 15        | 12%     |
| Skylake       | 8         | 6.4%    |
| IvyBridge     | 7         | 5.6%    |
| SandyBridge   | 5         | 4%      |
| Zen 2         | 4         | 3.2%    |
| Zen           | 4         | 3.2%    |
| Piledriver    | 4         | 3.2%    |
| P6            | 4         | 3.2%    |
| Haswell       | 4         | 3.2%    |
| Zen+          | 3         | 2.4%    |
| K10           | 3         | 2.4%    |
| Core          | 3         | 2.4%    |
| Broadwell     | 3         | 2.4%    |
| Zen 3         | 1         | 0.8%    |
| Westmere      | 1         | 0.8%    |
| TigerLake     | 1         | 0.8%    |
| Silvermont    | 1         | 0.8%    |
| IceLake       | 1         | 0.8%    |
| Goldmont plus | 1         | 0.8%    |
| Geode         | 1         | 0.8%    |
| Bonnell       | 1         | 0.8%    |
| Bobcat        | 1         | 0.8%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 66        | 57.89%  |
| AMD                        | 27        | 23.68%  |
| Nvidia                     | 18        | 15.79%  |
| VIA Technologies           | 1         | 0.88%   |
| Trident Microsystems       | 1         | 0.88%   |
| Matrox Electronics Systems | 1         | 0.88%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 6         | 5.04%   |
| Intel HD Graphics 530                                                         | 5         | 4.2%    |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 3.36%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 4         | 3.36%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 4         | 3.36%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 4         | 3.36%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 3         | 2.52%   |
| Intel JasperLake [UHD Graphics]                                               | 3         | 2.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 2.52%   |
| Intel Alder Lake-N [UHD Graphics]                                             | 3         | 2.52%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 3         | 2.52%   |
| Nvidia GT218M [NVS 3100M]                                                     | 2         | 1.68%   |
| Nvidia GF114 [GeForce GTX 560]                                                | 2         | 1.68%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 2         | 1.68%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 2         | 1.68%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 1.68%   |
| Intel Iris Graphics 6100                                                      | 2         | 1.68%   |
| Intel HD Graphics 630                                                         | 2         | 1.68%   |
| Intel HD Graphics 6000                                                        | 2         | 1.68%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 1.68%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 2         | 1.68%   |
| AMD RV280 [Radeon 9200]                                                       | 2         | 1.68%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 2         | 1.68%   |
| VIA Technologies CN400/PM800/PM880/PN800/PN880 [S3 UniChrome Pro]             | 1         | 0.84%   |
| Trident Microsystems TGUI 9660/938x/968x                                      | 1         | 0.84%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 1         | 0.84%   |
| Nvidia NV5 [Riva TNT2 Model 64 / Model 64 Pro]                                | 1         | 0.84%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                          | 1         | 0.84%   |
| Nvidia GT216GLM [Quadro FX 880M]                                              | 1         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 0.84%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 1         | 0.84%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 1         | 0.84%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                         | 1         | 0.84%   |
| Nvidia GM206 [GeForce GTX 960]                                                | 1         | 0.84%   |
| Nvidia GM204 [GeForce GTX 970]                                                | 1         | 0.84%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 1         | 0.84%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 0.84%   |
| Nvidia G86 [GeForce 8500 GT]                                                  | 1         | 0.84%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                       | 1         | 0.84%   |
| Matrox Electronics Systems G200eR2                                            | 1         | 0.84%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 55        | 44.72%  |
| 1 x AMD                  | 23        | 18.7%   |
| Other                    | 17        | 13.82%  |
| 1 x Nvidia               | 15        | 12.2%   |
| 2 x Intel                | 4         | 3.25%   |
| Intel + Nvidia           | 4         | 3.25%   |
| 2 x AMD                  | 1         | 0.81%   |
| 1 x VIA                  | 1         | 0.81%   |
| 1 x Trident Microsystems | 1         | 0.81%   |
| 1 x Matrox               | 1         | 0.81%   |
| Intel + AMD              | 1         | 0.81%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 82        | 65.08%  |
| Unknown | 44        | 34.92%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 76        | 61.29%  |
| 1.01-2.0   | 17        | 13.71%  |
| 3.01-4.0   | 11        | 8.87%   |
| 0.01-0.5   | 11        | 8.87%   |
| 0.51-1.0   | 7         | 5.65%   |
| 7.01-8.0   | 1         | 0.81%   |
| 5.01-6.0   | 1         | 0.81%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 9         | 17.65%  |
| LG Display              | 6         | 11.76%  |
| Goldstar                | 6         | 11.76%  |
| Chimei Innolux          | 4         | 7.84%   |
| Lenovo                  | 3         | 5.88%   |
| Apple                   | 3         | 5.88%   |
| Philips                 | 2         | 3.92%   |
| Eizo                    | 2         | 3.92%   |
| Dell                    | 2         | 3.92%   |
| BOE                     | 2         | 3.92%   |
| Acer                    | 2         | 3.92%   |
| ViewSonic               | 1         | 1.96%   |
| Unknown (CDD)           | 1         | 1.96%   |
| Sony                    | 1         | 1.96%   |
| NEC Computers           | 1         | 1.96%   |
| LG Philips              | 1         | 1.96%   |
| InfoVision              | 1         | 1.96%   |
| Impression              | 1         | 1.96%   |
| Iiyama                  | 1         | 1.96%   |
| Fujitsu Siemens         | 1         | 1.96%   |
| Chi Mei Optoelectronics | 1         | 1.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 890x500mm 40.2-inch | 2         | 3.92%   |
| Eizo M170 ENC1768 1280x1024 340x270mm 17.1-inch                       | 2         | 3.92%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch         | 1         | 1.96%   |
| Unknown (CDD) VGA CDD0030 1920x1080 1150x650mm 52.0-inch              | 1         | 1.96%   |
| Sony TV SNY4D04 1920x1080                                             | 1         | 1.96%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 410x310mm 20.2-inch  | 1         | 1.96%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch  | 1         | 1.96%   |
| Samsung Electronics S24C650 SAM09E9 1920x1080 520x290mm 23.4-inch     | 1         | 1.96%   |
| Samsung Electronics S23C570 SAM0A56 1920x1080 510x290mm 23.1-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC554E 1024x600 220x130mm 10.1-inch  | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch  | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 340x190mm 15.3-inch  | 1         | 1.96%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch               | 1         | 1.96%   |
| Philips PHL 245E1 PHLC20B 2560x1440 530x300mm 24.0-inch               | 1         | 1.96%   |
| NEC Computers P221W NEC674A 1680x1050 470x300mm 22.0-inch             | 1         | 1.96%   |
| LG Philips LCD Monitor LPLDD00 1280x800 330x210mm 15.4-inch           | 1         | 1.96%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x170mm 13.9-inch           | 1         | 1.96%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch          | 1         | 1.96%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch           | 1         | 1.96%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch           | 1         | 1.96%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch           | 1         | 1.96%   |
| LG Display LCD Monitor LGD029E 1600x900 340x190mm 15.3-inch           | 1         | 1.96%   |
| Lenovo P27h-20 LEN61E9 2560x1440 600x340mm 27.2-inch                  | 1         | 1.96%   |
| Lenovo LCD Monitor LEN40B1 1600x900 350x190mm 15.7-inch               | 1         | 1.96%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch               | 1         | 1.96%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch          | 1         | 1.96%   |
| Impression R19W11 IMP1911 1440x900 410x260mm 19.1-inch                | 1         | 1.96%   |
| Iiyama PL2792Q IVM6630 2560x1440 600x340mm 27.2-inch                  | 1         | 1.96%   |
| Goldstar W1952 GSM4B78 1440x900 410x260mm 19.1-inch                   | 1         | 1.96%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 580x240mm 24.7-inch           | 1         | 1.96%   |
| Goldstar LG IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch          | 1         | 1.96%   |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch              | 1         | 1.96%   |
| Goldstar L226WTQ GSM564D 1680x1050 490x320mm 23.0-inch                | 1         | 1.96%   |
| Goldstar L194WT GSM4B05 1440x900 410x260mm 19.1-inch                  | 1         | 1.96%   |
| Fujitsu Siemens SL27T-1 LED FUS07E5 1920x1080 600x340mm 27.2-inch     | 1         | 1.96%   |
| Dell SE2419H DELF109 1920x1080 530x300mm 24.0-inch                    | 1         | 1.96%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                     | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 340x190mm 15.3-inch      | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 340x190mm 15.3-inch      | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch       | 1         | 1.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 19        | 38%     |
| 1366x768 (WXGA)    | 8         | 16%     |
| 1440x900 (WXGA+)   | 4         | 8%      |
| 2560x1440 (QHD)    | 3         | 6%      |
| 1600x900 (HD+)     | 3         | 6%      |
| 1280x800 (WXGA)    | 3         | 6%      |
| 1680x1050 (WSXGA+) | 2         | 4%      |
| 1280x1024 (SXGA)   | 2         | 4%      |
| 1024x600           | 2         | 4%      |
| 3840x2160 (4K)     | 1         | 2%      |
| 2560x1600          | 1         | 2%      |
| 2560x1080          | 1         | 2%      |
| 1600x1200          | 1         | 2%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 12        | 23.53%  |
| 15      | 7         | 13.73%  |
| 27      | 6         | 11.76%  |
| 24      | 4         | 7.84%   |
| 23      | 4         | 7.84%   |
| 19      | 3         | 5.88%   |
| 40      | 2         | 3.92%   |
| 21      | 2         | 3.92%   |
| 17      | 2         | 3.92%   |
| 52      | 1         | 1.96%   |
| 34      | 1         | 1.96%   |
| 22      | 1         | 1.96%   |
| 20      | 1         | 1.96%   |
| 14      | 1         | 1.96%   |
| 12      | 1         | 1.96%   |
| 10      | 1         | 1.96%   |
| 9       | 1         | 1.96%   |
| Unknown | 1         | 1.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 18        | 35.29%  |
| 501-600     | 13        | 25.49%  |
| 401-500     | 8         | 15.69%  |
| 201-300     | 7         | 13.73%  |
| 801-900     | 2         | 3.92%   |
| 701-800     | 1         | 1.96%   |
| 1001-1500   | 1         | 1.96%   |
| Unknown     | 1         | 1.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 35        | 70%     |
| 16/10 | 10        | 20%     |
| 5/4   | 2         | 4%      |
| 4/3   | 1         | 2%      |
| 3/2   | 1         | 2%      |
| 21/9  | 1         | 2%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 13        | 25.49%  |
| 201-250        | 10        | 19.61%  |
| 301-350        | 6         | 11.76%  |
| 151-200        | 4         | 7.84%   |
| 91-100         | 4         | 7.84%   |
| 101-110        | 3         | 5.88%   |
| 41-50          | 2         | 3.92%   |
| 141-150        | 2         | 3.92%   |
| 501-1000       | 2         | 3.92%   |
| More than 1000 | 1         | 1.96%   |
| 61-70          | 1         | 1.96%   |
| 351-500        | 1         | 1.96%   |
| 251-300        | 1         | 1.96%   |
| Unknown        | 1         | 1.96%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 21        | 42%     |
| 101-120 | 15        | 30%     |
| 121-160 | 10        | 20%     |
| 161-240 | 2         | 4%      |
| 1-50    | 1         | 2%      |
| Unknown | 1         | 2%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 67        | 54.03%  |
| 0     | 56        | 45.16%  |
| 2     | 1         | 0.81%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 57        | 36.77%  |
| Realtek Semiconductor             | 48        | 30.97%  |
| Qualcomm Atheros                  | 17        | 10.97%  |
| Broadcom                          | 13        | 8.39%   |
| Huawei Technologies               | 3         | 1.94%   |
| TP-Link                           | 2         | 1.29%   |
| Marvell Technology Group          | 2         | 1.29%   |
| 3Com                              | 2         | 1.29%   |
| VIA Technologies                  | 1         | 0.65%   |
| Qualcomm Atheros Communications   | 1         | 0.65%   |
| Oculus VR                         | 1         | 0.65%   |
| Netchip Technology                | 1         | 0.65%   |
| Mercucys                          | 1         | 0.65%   |
| MediaTek                          | 1         | 0.65%   |
| Ericsson Business Mobile Networks | 1         | 0.65%   |
| Dell                              | 1         | 0.65%   |
| Davicom Semiconductor             | 1         | 0.65%   |
| D-Link                            | 1         | 0.65%   |
| Apple                             | 1         | 0.65%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 40        | 20.3%   |
| Intel Wireless 8265 / 8275                                                    | 6         | 3.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 3.05%   |
| Intel Wireless 8260                                                           | 5         | 2.54%   |
| Intel I211 Gigabit Network Connection                                         | 4         | 2.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 1.52%   |
| Intel Wireless 7265                                                           | 3         | 1.52%   |
| Intel Wi-Fi 6 AX200                                                           | 3         | 1.52%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 3         | 1.52%   |
| Intel Ethernet Controller I225-V                                              | 3         | 1.52%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 1.52%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3         | 1.52%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3         | 1.52%   |
| Huawei USB Device                                                             | 3         | 1.52%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 3         | 1.52%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2         | 1.02%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 1.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2         | 1.02%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 2         | 1.02%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 1.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2         | 1.02%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2         | 1.02%   |
| Intel Wireless 7260                                                           | 2         | 1.02%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 2         | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 2         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 1.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2         | 1.02%   |
| Intel CNVi: Wi-Fi                                                             | 2         | 1.02%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 1.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2         | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 2         | 1.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 1.02%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 1.02%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 2         | 1.02%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2         | 1.02%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 2         | 1.02%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1         | 0.51%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1         | 0.51%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1         | 0.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 53.66%  |
| Realtek Semiconductor           | 12        | 14.63%  |
| Qualcomm Atheros                | 11        | 13.41%  |
| Broadcom                        | 9         | 10.98%  |
| TP-Link                         | 2         | 2.44%   |
| Qualcomm Atheros Communications | 1         | 1.22%   |
| Mercucys                        | 1         | 1.22%   |
| MediaTek                        | 1         | 1.22%   |
| D-Link                          | 1         | 1.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                            | 6         | 7.23%   |
| Intel Wireless 8260                                                                   | 5         | 6.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 3         | 3.61%   |
| Intel Wireless 7265                                                                   | 3         | 3.61%   |
| Intel Wi-Fi 6 AX200                                                                   | 3         | 3.61%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                               | 3         | 3.61%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                          | 3         | 3.61%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 2         | 2.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 2.41%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 2         | 2.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 2.41%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 2.41%   |
| Intel Wireless 7260                                                                   | 2         | 2.41%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 2         | 2.41%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 2         | 2.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 2.41%   |
| Intel CNVi: Wi-Fi                                                                     | 2         | 2.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 2.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 2         | 2.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2         | 2.41%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 2.41%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                           | 1         | 1.2%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1         | 1.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.2%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.2%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1         | 1.2%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 1.2%    |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.2%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 1.2%    |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 1.2%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 1.2%    |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.2%    |
| Mercucys MERCUSYS Wireless USB Adapter                                                | 1         | 1.2%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                         | 1         | 1.2%    |
| Intel Wireless 3165                                                                   | 1         | 1.2%    |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 1.2%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 1.2%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 44        | 41.9%   |
| Intel                    | 37        | 35.24%  |
| Broadcom                 | 8         | 7.62%   |
| Qualcomm Atheros         | 6         | 5.71%   |
| Huawei Technologies      | 3         | 2.86%   |
| Marvell Technology Group | 2         | 1.9%    |
| 3Com                     | 2         | 1.9%    |
| VIA Technologies         | 1         | 0.95%   |
| Davicom Semiconductor    | 1         | 0.95%   |
| Apple                    | 1         | 0.95%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 40        | 37.74%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 5.66%   |
| Intel I211 Gigabit Network Connection                                  | 4         | 3.77%   |
| Intel Ethernet Controller I225-V                                       | 3         | 2.83%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 2.83%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 2.83%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 2.83%   |
| Huawei USB Device                                                      | 3         | 2.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 1.89%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 1.89%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 1.89%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 1.89%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 2         | 1.89%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 2         | 1.89%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 0.94%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1         | 0.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 0.94%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.94%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.94%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.94%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 0.94%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 0.94%   |
| Intel PRO/100 VE Network Connection                                    | 1         | 0.94%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.94%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.94%   |
| Intel Ethernet Connection I217-V                                       | 1         | 0.94%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 0.94%   |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 0.94%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 0.94%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 0.94%   |
| Intel Ethernet Connection (3) I218-V                                   | 1         | 0.94%   |
| Intel Ethernet Connection (2) I219-V                                   | 1         | 0.94%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                     | 1         | 0.94%   |
| Intel 82574L Gigabit Network Connection                                | 1         | 0.94%   |
| Davicom DM9102 Fast Ethernet Controller                                | 1         | 0.94%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                         | 1         | 0.94%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 0.94%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 1         | 0.94%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 0.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 99        | 54.7%   |
| WiFi     | 74        | 40.88%  |
| Modem    | 4         | 2.21%   |
| Unknown  | 4         | 2.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 78        | 71.56%  |
| WiFi     | 29        | 26.61%  |
| Unknown  | 2         | 1.83%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 59        | 47.97%  |
| 1     | 37        | 30.08%  |
| 0     | 21        | 17.07%  |
| 3     | 5         | 4.07%   |
| 4     | 1         | 0.81%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 95        | 76.61%  |
| Yes  | 29        | 23.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 63.16%  |
| Apple                           | 7         | 12.28%  |
| Realtek Semiconductor           | 4         | 7.02%   |
| Broadcom                        | 3         | 5.26%   |
| Qualcomm Atheros Communications | 2         | 3.51%   |
| IMC Networks                    | 2         | 3.51%   |
| Cambridge Silicon Radio         | 2         | 3.51%   |
| Lite-On Technology              | 1         | 1.75%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 16        | 28.07%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 9         | 15.79%  |
| Realtek Bluetooth Adapter                           | 3         | 5.26%   |
| Intel AX201 Bluetooth                               | 3         | 5.26%   |
| Apple Broadcom Built-in Bluetooth                   | 3         | 5.26%   |
| Apple Bluetooth Host Controller                     | 3         | 5.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 3.51%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 3.51%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 3.51%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 3.51%   |
| Intel AX200 Bluetooth                               | 2         | 3.51%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 3.51%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 3.51%   |
| Realtek Bluetooth 4.0 Adapter                       | 1         | 1.75%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.75%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS    | 1         | 1.75%   |
| IMC Networks MediaTek Bluetooth Adapter             | 1         | 1.75%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.75%   |
| Apple Built-in iSight (no firmware loaded)          | 1         | 1.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 75        | 58.14%  |
| AMD                                          | 27        | 20.93%  |
| Nvidia                                       | 12        | 9.3%    |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 1.55%   |
| Logitech                                     | 2         | 1.55%   |
| Yamaha                                       | 1         | 0.78%   |
| Walmart                                      | 1         | 0.78%   |
| VIA Technologies                             | 1         | 0.78%   |
| Texas Instruments                            | 1         | 0.78%   |
| Samsung Electronics                          | 1         | 0.78%   |
| Realtek Semiconductor                        | 1         | 0.78%   |
| Native Instruments                           | 1         | 0.78%   |
| M-Audio                                      | 1         | 0.78%   |
| ESS Technology                               | 1         | 0.78%   |
| Creative Labs                                | 1         | 0.78%   |
| Apple                                        | 1         | 0.78%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 9         | 5.66%   |
| Intel Cannon Lake PCH cAVS                                                        | 8         | 5.03%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 8         | 5.03%   |
| Intel Sunrise Point-LP HD Audio                                                   | 7         | 4.4%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 6         | 3.77%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 5         | 3.14%   |
| Intel Broadwell-U Audio Controller                                                | 5         | 3.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 5         | 3.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 5         | 3.14%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                        | 5         | 3.14%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 4         | 2.52%   |
| AMD Starship/Matisse HD Audio Controller                                          | 4         | 2.52%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 4         | 2.52%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4         | 2.52%   |
| Intel Jasper Lake HD Audio                                                        | 3         | 1.89%   |
| Intel Haswell-ULT HD Audio Controller                                             | 3         | 1.89%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                           | 3         | 1.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 3         | 1.89%   |
| Intel 8 Series HD Audio Controller                                                | 3         | 1.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3         | 1.89%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 3         | 1.89%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 3         | 1.89%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                    | 2         | 1.26%   |
| Nvidia High Definition Audio Controller                                           | 2         | 1.26%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2         | 1.26%   |
| Nvidia GM206 High Definition Audio Controller                                     | 2         | 1.26%   |
| Nvidia GF114 HDMI Audio Controller                                                | 2         | 1.26%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 2         | 1.26%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 2         | 1.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 2         | 1.26%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                 | 2         | 1.26%   |
| AMD Wrestler HDMI Audio                                                           | 2         | 1.26%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 1.26%   |
| Yamaha AG06/AG03                                                                  | 1         | 0.63%   |
| Walmart AB13X Headset Adapter                                                     | 1         | 0.63%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                         | 1         | 0.63%   |
| Texas Instruments PCM2902 Audio Codec                                             | 1         | 0.63%   |
| Samsung Electronics Samsung Type-C to 3.5pi gender adapter                        | 1         | 0.63%   |
| Realtek Semiconductor ATH-M50xSTS-USB                                             | 1         | 0.63%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 17.14%  |
| Kingston            | 14        | 13.33%  |
| Micron Technology   | 13        | 12.38%  |
| Crucial             | 13        | 12.38%  |
| Unknown             | 10        | 9.52%   |
| SK hynix            | 9         | 8.57%   |
| G.Skill             | 5         | 4.76%   |
| A-DATA Technology   | 4         | 3.81%   |
| Unknown             | 4         | 3.81%   |
| Ramaxel Technology  | 3         | 2.86%   |
| Patriot             | 3         | 2.86%   |
| Corsair             | 3         | 2.86%   |
| SHARETRONIC         | 1         | 0.95%   |
| Nanya Technology    | 1         | 0.95%   |
| Lexar Co Limited    | 1         | 0.95%   |
| Elpida              | 1         | 0.95%   |
| AMD                 | 1         | 0.95%   |
| 48spaces            | 1         | 0.95%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown                                                     | 4         | 3.42%   |
| Micron RAM Module 8GB Chip LPDDR4                           | 3         | 2.56%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s       | 2         | 1.71%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s      | 2         | 1.71%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s      | 2         | 1.71%   |
| Crucial RAM CT16G4SFS832A.C8FF 16GB SODIMM DDR4 3200MT/s    | 2         | 1.71%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                 | 1         | 0.85%   |
| Unknown RAM Module 8192MB DIMM 400MT/s                      | 1         | 0.85%   |
| Unknown RAM Module 512MB SODIMM DRAM 166MT/s                | 1         | 0.85%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                | 1         | 0.85%   |
| Unknown RAM Module 4GB FB-DIMM DDR2 667MT/s                 | 1         | 0.85%   |
| Unknown RAM Module 2GB SODIMM DDR3                          | 1         | 0.85%   |
| Unknown RAM Module 2GB FB-DIMM DDR2 667MT/s                 | 1         | 0.85%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                    | 1         | 0.85%   |
| Unknown RAM Module 256MB SODIMM DDR                         | 1         | 0.85%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                 | 1         | 0.85%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                      | 1         | 0.85%   |
| Unknown RAM Module 128MB DIMM DRAM                          | 1         | 0.85%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266MT/s              | 1         | 0.85%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s               | 1         | 0.85%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 0.85%   |
| SK hynix RAM HMT351U6CFR8C 4GB DIMM DDR3 667MT/s            | 1         | 0.85%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s      | 1         | 0.85%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s      | 1         | 0.85%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s      | 1         | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 1         | 0.85%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 1         | 0.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s      | 1         | 0.85%   |
| SHARETRONIC RAM Module 2048MB SODIMM DDR3 1600MT/s          | 1         | 0.85%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s         | 1         | 0.85%   |
| Samsung RAM Module 2GB SODIMM LPDDR3 1867MT/s               | 1         | 0.85%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                 | 1         | 0.85%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s       | 1         | 0.85%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s       | 1         | 0.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 0.85%   |
| Samsung RAM M471A5644EB0-CRC 2GB SODIMM DDR4 2400MT/s       | 1         | 0.85%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s       | 1         | 0.85%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s       | 1         | 0.85%   |
| Samsung RAM M471A5244BB0-CRC 4GB Row Of Chips DDR4 2400MT/s | 1         | 0.85%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 1         | 0.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 42        | 48.28%  |
| DDR3    | 29        | 33.33%  |
| DDR2    | 5         | 5.75%   |
| LPDDR4  | 3         | 3.45%   |
| LPDDR3  | 2         | 2.3%    |
| DRAM    | 2         | 2.3%    |
| SDRAM   | 1         | 1.15%   |
| LPDDR2  | 1         | 1.15%   |
| DDR     | 1         | 1.15%   |
| Unknown | 1         | 1.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 47        | 54.65%  |
| DIMM         | 31        | 36.05%  |
| Chip         | 5         | 5.81%   |
| Row Of Chips | 2         | 2.33%   |
| FB-DIMM      | 1         | 1.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 32        | 33.33%  |
| 4096  | 24        | 25%     |
| 16384 | 17        | 17.71%  |
| 2048  | 15        | 15.63%  |
| 32768 | 2         | 2.08%   |
| 1024  | 2         | 2.08%   |
| 512   | 2         | 2.08%   |
| 256   | 1         | 1.04%   |
| 128   | 1         | 1.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 16        | 16.49%  |
| 3200    | 12        | 12.37%  |
| 2667    | 12        | 12.37%  |
| 2400    | 11        | 11.34%  |
| 2133    | 9         | 9.28%   |
| Unknown | 7         | 7.22%   |
| 1333    | 6         | 6.19%   |
| 1867    | 3         | 3.09%   |
| 1334    | 3         | 3.09%   |
| 800     | 3         | 3.09%   |
| 667     | 3         | 3.09%   |
| 2933    | 2         | 2.06%   |
| 1067    | 2         | 2.06%   |
| 533     | 2         | 2.06%   |
| 3000    | 1         | 1.03%   |
| 2666    | 1         | 1.03%   |
| 1066    | 1         | 1.03%   |
| 400     | 1         | 1.03%   |
| 266     | 1         | 1.03%   |
| 166     | 1         | 1.03%   |

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

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 210 | 2         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Chicony Electronics              | 11        | 29.73%  |
| Silicon Motion                   | 4         | 10.81%  |
| Realtek Semiconductor            | 3         | 8.11%   |
| IMC Networks                     | 3         | 8.11%   |
| Logitech                         | 2         | 5.41%   |
| Lenovo                           | 2         | 5.41%   |
| Bison Electronics                | 2         | 5.41%   |
| Z-Star Microelectronics          | 1         | 2.7%    |
| Syntek                           | 1         | 2.7%    |
| Sunplus Innovation Technology    | 1         | 2.7%    |
| Shenzhen Kingcome Optoelectronic | 1         | 2.7%    |
| Quanta                           | 1         | 2.7%    |
| Microdia                         | 1         | 2.7%    |
| Lite-On Technology               | 1         | 2.7%    |
| ARC International                | 1         | 2.7%    |
| Apple                            | 1         | 2.7%    |
| ALi                              | 1         | 2.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                     | 4         | 10.53%  |
| Lenovo Integrated Webcam [R5U877]                             | 2         | 5.26%   |
| IMC Networks Realtek PC Camera                                | 2         | 5.26%   |
| Z-Star Webcam                                                 | 1         | 2.63%   |
| Syntek Lenovo EasyCamera                                      | 1         | 2.63%   |
| Sunplus Integrated Camera                                     | 1         | 2.63%   |
| Silicon Motion WebCam SC-10IRQ12340N                          | 1         | 2.63%   |
| Silicon Motion Realtek USB 2.0 PC Camera                      | 1         | 2.63%   |
| Silicon Motion LG HD WebCam                                   | 1         | 2.63%   |
| Silicon Motion 300k Pixel Camera                              | 1         | 2.63%   |
| Shenzhen Kingcome Optoelectronic NexiGo HelloCam N930W Camera | 1         | 2.63%   |
| Realtek USB Camera                                            | 1         | 2.63%   |
| Realtek USB 2.0 PC Camera                                     | 1         | 2.63%   |
| Realtek Acer 640 x 480 laptop camera                          | 1         | 2.63%   |
| Quanta VGA WebCam                                             | 1         | 2.63%   |
| Microdia Integrated_Webcam_HD                                 | 1         | 2.63%   |
| Logitech Webcam C270                                          | 1         | 2.63%   |
| Logitech C922 Pro Stream Webcam                               | 1         | 2.63%   |
| Lite-On Integrated Camera                                     | 1         | 2.63%   |
| IMC Networks EasyCamera                                       | 1         | 2.63%   |
| Chicony XiaoMi USB 2.0 Webcam                                 | 1         | 2.63%   |
| Chicony USB2.0 VGA UVC WebCam                                 | 1         | 2.63%   |
| Chicony Thinkpad T430 camera                                  | 1         | 2.63%   |
| Chicony Integrated Camera (1280x720@30)                       | 1         | 2.63%   |
| Chicony HP HD Webcam [Fixed]                                  | 1         | 2.63%   |
| Chicony Front Camera                                          | 1         | 2.63%   |
| Chicony 8M Camera                                             | 1         | 2.63%   |
| Chicony 720p HD Camera                                        | 1         | 2.63%   |
| Bison ThinkPad P50 Integrated Camera                          | 1         | 2.63%   |
| Bison Integrated Camera                                       | 1         | 2.63%   |
| ARC International Camera                                      | 1         | 2.63%   |
| Apple FaceTime HD Camera                                      | 1         | 2.63%   |
| ALi Gateway Webcam                                            | 1         | 2.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 60%     |
| Upek             | 1         | 20%     |
| Synaptics        | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                        | 2         | 40%     |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 20%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 20%     |

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
| 0     | 39        | 31.2%   |
| 1     | 38        | 30.4%   |
| 2     | 30        | 24%     |
| 3     | 11        | 8.8%    |
| 5     | 4         | 3.2%    |
| 4     | 3         | 2.4%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 69        | 49.29%  |
| Net/wireless             | 41        | 29.29%  |
| Card reader              | 11        | 7.86%   |
| Graphics card            | 7         | 5%      |
| Storage                  | 2         | 1.43%   |
| Sound                    | 2         | 1.43%   |
| Net/ethernet             | 2         | 1.43%   |
| Bluetooth                | 2         | 1.43%   |
| Wireless                 | 1         | 0.71%   |
| Storage/nvme             | 1         | 0.71%   |
| Modem                    | 1         | 0.71%   |
| Dvb card                 | 1         | 0.71%   |

