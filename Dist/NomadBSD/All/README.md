NomadBSD - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for NomadBSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/NomadBSD/Desktop/README.md) and [notebooks](/Dist/NomadBSD/Notebook/README.md).

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

Total: 215

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E495 20NE000BSP    | Notebook    | [0e02b323ee](https://bsd-hardware.info/?probe=0e02b323ee) | Jun 01, 2023 |
| ASRockRack    | C226M WS                    | Desktop     | [06a8ca514a](https://bsd-hardware.info/?probe=06a8ca514a) | Apr 14, 2023 |
| ECS           | Z77H2-AX                    | Desktop     | [32a290eb5f](https://bsd-hardware.info/?probe=32a290eb5f) | Apr 13, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [f6e5189f54](https://bsd-hardware.info/?probe=f6e5189f54) | Apr 11, 2023 |
| Lenovo        | ThinkPad X280 20KESB4T00    | Notebook    | [fb6c7b3b09](https://bsd-hardware.info/?probe=fb6c7b3b09) | Apr 11, 2023 |
| Dell          | Latitude 7300               | Notebook    | [d036260cce](https://bsd-hardware.info/?probe=d036260cce) | Apr 08, 2023 |
| Lenovo        | ThinkPad X230 23255NG       | Notebook    | [2ef93a7621](https://bsd-hardware.info/?probe=2ef93a7621) | Mar 29, 2023 |
| Acer          | Swift SF314-56              | Notebook    | [94c7da1b3f](https://bsd-hardware.info/?probe=94c7da1b3f) | Mar 13, 2023 |
| Intel         | Jasper Lake Client Platf... | Notebook    | [de93a79b7d](https://bsd-hardware.info/?probe=de93a79b7d) | Mar 10, 2023 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | Notebook    | [dd6c3fa0f7](https://bsd-hardware.info/?probe=dd6c3fa0f7) | Mar 10, 2023 |
| Fujitsu       | CELSIUS H730                | Notebook    | [d2292bbcda](https://bsd-hardware.info/?probe=d2292bbcda) | Mar 10, 2023 |
| ASRock        | N68-S UCC                   | Desktop     | [04f43c3d70](https://bsd-hardware.info/?probe=04f43c3d70) | Feb 23, 2023 |
| Acer          | Aspire 7738                 | Notebook    | [e61cd20061](https://bsd-hardware.info/?probe=e61cd20061) | Feb 18, 2023 |
| Lenovo        | ThinkPad W520 42844DG       | Notebook    | [d341f3c6f6](https://bsd-hardware.info/?probe=d341f3c6f6) | Feb 11, 2023 |
| Lenovo        | ThinkPad E14 20RA0036RT     | Notebook    | [941da31f26](https://bsd-hardware.info/?probe=941da31f26) | Feb 02, 2023 |
| HP            | 1589                        | Desktop     | [8a927b43cb](https://bsd-hardware.info/?probe=8a927b43cb) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [335c3c990a](https://bsd-hardware.info/?probe=335c3c990a) | Jan 08, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [6a1ff80054](https://bsd-hardware.info/?probe=6a1ff80054) | Jan 04, 2023 |
| Lenovo        | Yoga 710-11IKB 80V6         | Notebook    | [1d3ccd1fe6](https://bsd-hardware.info/?probe=1d3ccd1fe6) | Dec 22, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [5234a39100](https://bsd-hardware.info/?probe=5234a39100) | Dec 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d893e02d90](https://bsd-hardware.info/?probe=d893e02d90) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7518e4f06a](https://bsd-hardware.info/?probe=7518e4f06a) | Nov 21, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [17d766d55a](https://bsd-hardware.info/?probe=17d766d55a) | Oct 08, 2022 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [91a1870b65](https://bsd-hardware.info/?probe=91a1870b65) | Sep 01, 2022 |
| Lenovo        | ThinkPad T480 20L50000GE    | Notebook    | [cd7d7d83ba](https://bsd-hardware.info/?probe=cd7d7d83ba) | Aug 20, 2022 |
| Lenovo        | ThinkPad T480 20L6SB2N00    | Notebook    | [995a8a5e6f](https://bsd-hardware.info/?probe=995a8a5e6f) | Jul 16, 2022 |
| Lenovo        | V580 20147                  | Notebook    | [0615e8260d](https://bsd-hardware.info/?probe=0615e8260d) | Jul 02, 2022 |
| Lenovo        | V580 20147                  | Notebook    | [6f1fd71366](https://bsd-hardware.info/?probe=6f1fd71366) | Jul 02, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [4e6381e037](https://bsd-hardware.info/?probe=4e6381e037) | Jun 22, 2022 |
| HP            | 2B29                        | Desktop     | [e8c355314e](https://bsd-hardware.info/?probe=e8c355314e) | Jun 17, 2022 |
| HP            | 1589                        | Desktop     | [3765f1cb09](https://bsd-hardware.info/?probe=3765f1cb09) | Jun 17, 2022 |
| Dell          | 0Y2G6P A03                  | Server      | [ecb370bba4](https://bsd-hardware.info/?probe=ecb370bba4) | Jun 17, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [004e039a23](https://bsd-hardware.info/?probe=004e039a23) | May 19, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [555a7733b7](https://bsd-hardware.info/?probe=555a7733b7) | May 19, 2022 |
| Dell          | Latitude 5290               | Notebook    | [11c3db8f1b](https://bsd-hardware.info/?probe=11c3db8f1b) | Apr 23, 2022 |
| Notebook      | W650DC,DD                   | Notebook    | [0f474b9ebb](https://bsd-hardware.info/?probe=0f474b9ebb) | Apr 23, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [c4f7b8a774](https://bsd-hardware.info/?probe=c4f7b8a774) | Apr 22, 2022 |
| Dell          | Studio 1555                 | Notebook    | [6da8f97bcd](https://bsd-hardware.info/?probe=6da8f97bcd) | Apr 22, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [c776760a11](https://bsd-hardware.info/?probe=c776760a11) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490s 20NX000DR... | Notebook    | [c052d7cab0](https://bsd-hardware.info/?probe=c052d7cab0) | Apr 01, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [95646c7b48](https://bsd-hardware.info/?probe=95646c7b48) | Mar 25, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [09116f9139](https://bsd-hardware.info/?probe=09116f9139) | Mar 24, 2022 |
| ASUSTek       | M51Sr                       | Notebook    | [936a577d1a](https://bsd-hardware.info/?probe=936a577d1a) | Mar 10, 2022 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | Notebook    | [2af47b6502](https://bsd-hardware.info/?probe=2af47b6502) | Mar 03, 2022 |
| MSI           | U-100 Ver.001               | Desktop     | [6859308aa9](https://bsd-hardware.info/?probe=6859308aa9) | Mar 01, 2022 |
| Dell          | Latitude D630               | Notebook    | [ae56d2cedd](https://bsd-hardware.info/?probe=ae56d2cedd) | Feb 28, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e27a6f46fc](https://bsd-hardware.info/?probe=e27a6f46fc) | Feb 26, 2022 |
| Gigabyte      | X570S GAMING X              | Desktop     | [ff39ace6ec](https://bsd-hardware.info/?probe=ff39ace6ec) | Feb 16, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [766e62f699](https://bsd-hardware.info/?probe=766e62f699) | Feb 12, 2022 |
| HP            | Notebook                    | Notebook    | [1758596e26](https://bsd-hardware.info/?probe=1758596e26) | Feb 12, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [24f3a7da57](https://bsd-hardware.info/?probe=24f3a7da57) | Feb 07, 2022 |
| Intel         | DCP847SKE                   | Desktop     | [2828ef2a6d](https://bsd-hardware.info/?probe=2828ef2a6d) | Jan 20, 2022 |
| ASUSTek       | 1000                        | Notebook    | [da8689c840](https://bsd-hardware.info/?probe=da8689c840) | Dec 08, 2021 |
| Dell          | 0M9KCM A01                  | Desktop     | [4db0a0ea05](https://bsd-hardware.info/?probe=4db0a0ea05) | Dec 06, 2021 |
| Gigabyte      | MZGLKBP-00                  | Desktop     | [e713e3adee](https://bsd-hardware.info/?probe=e713e3adee) | Dec 05, 2021 |
| HP            | ProBook x360 11 G6 EE       | Convertible | [7eaff44a64](https://bsd-hardware.info/?probe=7eaff44a64) | Nov 27, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [1bd9270845](https://bsd-hardware.info/?probe=1bd9270845) | Nov 15, 2021 |
| Acer          | Aspire 3810T                | Notebook    | [86782a69be](https://bsd-hardware.info/?probe=86782a69be) | Nov 13, 2021 |
| Acer          | Aspire 3810T                | Notebook    | [608e43163d](https://bsd-hardware.info/?probe=608e43163d) | Nov 12, 2021 |
| Dell          | 0T10XW A01                  | Desktop     | [ae2203b146](https://bsd-hardware.info/?probe=ae2203b146) | Nov 12, 2021 |
| Unknown       | X79                         | Desktop     | [c80b658f36](https://bsd-hardware.info/?probe=c80b658f36) | Nov 09, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [1d261120d3](https://bsd-hardware.info/?probe=1d261120d3) | Nov 06, 2021 |
| HP            | ZBook Studio G3             | Notebook    | [767b44a6ae](https://bsd-hardware.info/?probe=767b44a6ae) | Oct 30, 2021 |
| ASUSTek       | X202E                       | Notebook    | [54259ac9a1](https://bsd-hardware.info/?probe=54259ac9a1) | Oct 29, 2021 |
| Sony          | VJS121C11N                  | Notebook    | [d86c621ef0](https://bsd-hardware.info/?probe=d86c621ef0) | Oct 25, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [2d72b6939d](https://bsd-hardware.info/?probe=2d72b6939d) | Oct 24, 2021 |
| HP            | 87D6 SMVB                   | Desktop     | [f601f00e7c](https://bsd-hardware.info/?probe=f601f00e7c) | Oct 07, 2021 |
| Dell          | OptiPlex 3020               | Desktop     | [c391177240](https://bsd-hardware.info/?probe=c391177240) | Oct 05, 2021 |
| Dell          | OptiPlex 3020               | Desktop     | [070a0c6d62](https://bsd-hardware.info/?probe=070a0c6d62) | Sep 19, 2021 |
| ASUSTek       | X540YA                      | Notebook    | [c5751c736c](https://bsd-hardware.info/?probe=c5751c736c) | Sep 19, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [d8f8901ae7](https://bsd-hardware.info/?probe=d8f8901ae7) | Sep 19, 2021 |
| Lenovo        | ThinkPad X13 Yoga Gen 1 ... | Convertible | [8818f01ff2](https://bsd-hardware.info/?probe=8818f01ff2) | Aug 27, 2021 |
| HP            | OMEN by HP Laptop 17-cb1... | Notebook    | [b00c8e76e8](https://bsd-hardware.info/?probe=b00c8e76e8) | Aug 23, 2021 |
| HP            | Pavilion g6                 | Notebook    | [f1dc5150c2](https://bsd-hardware.info/?probe=f1dc5150c2) | Aug 13, 2021 |
| HP            | 2000                        | Notebook    | [d2240a960b](https://bsd-hardware.info/?probe=d2240a960b) | Aug 05, 2021 |
| HP            | 2000                        | Notebook    | [65d183fe41](https://bsd-hardware.info/?probe=65d183fe41) | Aug 05, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0M... | Notebook    | [39ef89f214](https://bsd-hardware.info/?probe=39ef89f214) | Aug 05, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0M... | Notebook    | [4e7ace8a39](https://bsd-hardware.info/?probe=4e7ace8a39) | Aug 04, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [3348992bef](https://bsd-hardware.info/?probe=3348992bef) | Jul 23, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | Notebook    | [77676fbcfc](https://bsd-hardware.info/?probe=77676fbcfc) | Jul 18, 2021 |
| Lenovo        | ThinkPad T510 4384FF3       | Notebook    | [25e208721d](https://bsd-hardware.info/?probe=25e208721d) | Jul 02, 2021 |
| Dell          | Inspiron 15-5568            | Notebook    | [3ed52ae70d](https://bsd-hardware.info/?probe=3ed52ae70d) | Jul 01, 2021 |
| Gigabyte      | Z370 AORUS ULTRAGAMING W... | Desktop     | [13371b2ab8](https://bsd-hardware.info/?probe=13371b2ab8) | Jun 27, 2021 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [e91dc55970](https://bsd-hardware.info/?probe=e91dc55970) | Jun 22, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [46bf9edc63](https://bsd-hardware.info/?probe=46bf9edc63) | Jun 17, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [dbda48cff7](https://bsd-hardware.info/?probe=dbda48cff7) | Jun 17, 2021 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [5abce24217](https://bsd-hardware.info/?probe=5abce24217) | Jun 06, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | Convertible | [dab0ca2417](https://bsd-hardware.info/?probe=dab0ca2417) | Jun 01, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [c6a1c1fa15](https://bsd-hardware.info/?probe=c6a1c1fa15) | May 25, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | Convertible | [96cc0c27b0](https://bsd-hardware.info/?probe=96cc0c27b0) | May 25, 2021 |
| ASUSTek       | V-P7H55E                    | Desktop     | [8cf113ac55](https://bsd-hardware.info/?probe=8cf113ac55) | May 22, 2021 |
| Toshiba       | STI 005492G                 | Desktop     | [9a8e4a1328](https://bsd-hardware.info/?probe=9a8e4a1328) | May 17, 2021 |
| Acer          | Aspire E5-551               | Notebook    | [c9ab1cb207](https://bsd-hardware.info/?probe=c9ab1cb207) | Apr 29, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0M... | Notebook    | [e9155d12c7](https://bsd-hardware.info/?probe=e9155d12c7) | Apr 27, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [d1aaeaad42](https://bsd-hardware.info/?probe=d1aaeaad42) | Apr 26, 2021 |
| Lenovo        | ThinkPad W541 20EGS04800    | Notebook    | [91d2cd471c](https://bsd-hardware.info/?probe=91d2cd471c) | Apr 16, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [0621acab4e](https://bsd-hardware.info/?probe=0621acab4e) | Apr 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [821c81e652](https://bsd-hardware.info/?probe=821c81e652) | Apr 09, 2021 |
| ECT           | One Computer AMD A10-785... | Desktop     | [41a2a2e434](https://bsd-hardware.info/?probe=41a2a2e434) | Apr 07, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [6bc6c5b2bf](https://bsd-hardware.info/?probe=6bc6c5b2bf) | Mar 31, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [35aa6590c6](https://bsd-hardware.info/?probe=35aa6590c6) | Mar 29, 2021 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [c5e824b558](https://bsd-hardware.info/?probe=c5e824b558) | Mar 29, 2021 |
| Acer          | EG43M                       | Desktop     | [0bc978756c](https://bsd-hardware.info/?probe=0bc978756c) | Mar 27, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [650cd9b653](https://bsd-hardware.info/?probe=650cd9b653) | Mar 24, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [7d64801e2b](https://bsd-hardware.info/?probe=7d64801e2b) | Mar 21, 2021 |
| MSI           | MS-N033                     | Notebook    | [650f6a1b70](https://bsd-hardware.info/?probe=650f6a1b70) | Mar 21, 2021 |
| Samsung       | N145P/N250P/N260P           | Notebook    | [eff02dafe1](https://bsd-hardware.info/?probe=eff02dafe1) | Mar 18, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [83f9d05407](https://bsd-hardware.info/?probe=83f9d05407) | Mar 14, 2021 |
| Notebook      | N650DU                      | Notebook    | [90d705dd1e](https://bsd-hardware.info/?probe=90d705dd1e) | Mar 14, 2021 |
| HP            | Pavilion dv6000 (RP981EA... | Notebook    | [733c5edb74](https://bsd-hardware.info/?probe=733c5edb74) | Mar 08, 2021 |
| HP            | Pavilion dv6000 (RP981EA... | Notebook    | [56844725d1](https://bsd-hardware.info/?probe=56844725d1) | Mar 08, 2021 |
| Acer          | EG31M R01-C3                | Desktop     | [1186d46ac9](https://bsd-hardware.info/?probe=1186d46ac9) | Mar 08, 2021 |
| HP            | 158A                        | Desktop     | [da9d6bf86f](https://bsd-hardware.info/?probe=da9d6bf86f) | Mar 07, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [bf572bc102](https://bsd-hardware.info/?probe=bf572bc102) | Mar 06, 2021 |
| Dell          | 0R849J A00                  | Desktop     | [1bd1dc24c9](https://bsd-hardware.info/?probe=1bd1dc24c9) | Mar 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [be2ad24d1b](https://bsd-hardware.info/?probe=be2ad24d1b) | Mar 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [0e06b5f17f](https://bsd-hardware.info/?probe=0e06b5f17f) | Mar 06, 2021 |
| ASRock        | Z490M Pro4                  | Desktop     | [348d592fab](https://bsd-hardware.info/?probe=348d592fab) | Mar 05, 2021 |
| Dell          | 03CDJK A01                  | All in one  | [9468eeef92](https://bsd-hardware.info/?probe=9468eeef92) | Mar 04, 2021 |
| VeryPC        | S400                        | Desktop     | [edcea11cb7](https://bsd-hardware.info/?probe=edcea11cb7) | Mar 04, 2021 |
| Dell          | Latitude 5280               | Notebook    | [b84364959d](https://bsd-hardware.info/?probe=b84364959d) | Mar 04, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [1f226262cc](https://bsd-hardware.info/?probe=1f226262cc) | Mar 04, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [e056f1c77c](https://bsd-hardware.info/?probe=e056f1c77c) | Mar 03, 2021 |
| Fujitsu       | LIFEBOOK E754               | Notebook    | [d3d033f879](https://bsd-hardware.info/?probe=d3d033f879) | Mar 03, 2021 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [845c584693](https://bsd-hardware.info/?probe=845c584693) | Mar 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [eb7d8c3502](https://bsd-hardware.info/?probe=eb7d8c3502) | Mar 02, 2021 |
| Acer          | EG31M R01-C3                | Desktop     | [046404e65c](https://bsd-hardware.info/?probe=046404e65c) | Mar 01, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [0dc468c860](https://bsd-hardware.info/?probe=0dc468c860) | Feb 22, 2021 |
| ASUSTek       | X751LN                      | Notebook    | [fe7d72b06a](https://bsd-hardware.info/?probe=fe7d72b06a) | Feb 21, 2021 |
| GEO           | GeoBook3                    | Notebook    | [ba18b9bf80](https://bsd-hardware.info/?probe=ba18b9bf80) | Feb 19, 2021 |
| Clevo         | W55xEU                      | Notebook    | [a66041bae0](https://bsd-hardware.info/?probe=a66041bae0) | Feb 17, 2021 |
| Pegatron      | T12Ah                       | Notebook    | [a5ab7068dc](https://bsd-hardware.info/?probe=a5ab7068dc) | Feb 14, 2021 |
| Dell          | 0T568R A00                  | Desktop     | [cd086a9092](https://bsd-hardware.info/?probe=cd086a9092) | Feb 12, 2021 |
| Clevo         | W55xEU                      | Notebook    | [796ad51947](https://bsd-hardware.info/?probe=796ad51947) | Feb 11, 2021 |
| Clevo         | W55xEU                      | Notebook    | [c28a6397b5](https://bsd-hardware.info/?probe=c28a6397b5) | Feb 11, 2021 |
| Alienware     | M18xR1                      | Notebook    | [67a336fac6](https://bsd-hardware.info/?probe=67a336fac6) | Feb 08, 2021 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [2d0beb2534](https://bsd-hardware.info/?probe=2d0beb2534) | Feb 08, 2021 |
| Dell          | Latitude 3410               | Notebook    | [f81c1e338f](https://bsd-hardware.info/?probe=f81c1e338f) | Feb 07, 2021 |
| Dell          | Latitude E4300              | Notebook    | [84925c014a](https://bsd-hardware.info/?probe=84925c014a) | Feb 01, 2021 |
| Pegatron      | T12Ah                       | Notebook    | [4bda74f229](https://bsd-hardware.info/?probe=4bda74f229) | Jan 31, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [2917a6fbe1](https://bsd-hardware.info/?probe=2917a6fbe1) | Jan 31, 2021 |
| HP            | 0AACh                       | Desktop     | [b7cac343f6](https://bsd-hardware.info/?probe=b7cac343f6) | Jan 29, 2021 |
| HP            | 3399                        | Desktop     | [b11946a41a](https://bsd-hardware.info/?probe=b11946a41a) | Jan 13, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [8093f75ea2](https://bsd-hardware.info/?probe=8093f75ea2) | Jan 13, 2021 |
| Dell          | Latitude 5400               | Notebook    | [f242897c33](https://bsd-hardware.info/?probe=f242897c33) | Jan 13, 2021 |
| Dell          | Latitude 5490               | Notebook    | [3fba47b07f](https://bsd-hardware.info/?probe=3fba47b07f) | Jan 12, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [ba45e27f88](https://bsd-hardware.info/?probe=ba45e27f88) | Jan 12, 2021 |
| ASUSTek       | N75SF                       | Notebook    | [7efb6557a2](https://bsd-hardware.info/?probe=7efb6557a2) | Jan 10, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [9ccf63e228](https://bsd-hardware.info/?probe=9ccf63e228) | Jan 09, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [e18df4623a](https://bsd-hardware.info/?probe=e18df4623a) | Jan 09, 2021 |
| Dell          | 03CDJK A01                  | All in one  | [d894ae5d09](https://bsd-hardware.info/?probe=d894ae5d09) | Jan 07, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d54f451ea5](https://bsd-hardware.info/?probe=d54f451ea5) | Jan 07, 2021 |
| HP            | 3032h                       | Desktop     | [13648fd22d](https://bsd-hardware.info/?probe=13648fd22d) | Jan 07, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [ee2d5f3289](https://bsd-hardware.info/?probe=ee2d5f3289) | Jan 07, 2021 |
| Dell          | 030VXY A01                  | Desktop     | [c117ffdc98](https://bsd-hardware.info/?probe=c117ffdc98) | Jan 07, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [cfc292e9e8](https://bsd-hardware.info/?probe=cfc292e9e8) | Jan 07, 2021 |
| Sony          | VPCM13M1R                   | Notebook    | [30bb4fc23c](https://bsd-hardware.info/?probe=30bb4fc23c) | Jan 06, 2021 |
| NEC Comput... | PC-GL186Y3AZ                | Notebook    | [b9f8e78467](https://bsd-hardware.info/?probe=b9f8e78467) | Jan 05, 2021 |
| Dell          | Latitude 5280               | Notebook    | [1ae6e6ee2d](https://bsd-hardware.info/?probe=1ae6e6ee2d) | Jan 05, 2021 |
| Dell          | 0C27VV A02                  | Desktop     | [cfd6a0ab4b](https://bsd-hardware.info/?probe=cfd6a0ab4b) | Jan 04, 2021 |
| Dell          | 0C27VV A02                  | Desktop     | [876f5d7b92](https://bsd-hardware.info/?probe=876f5d7b92) | Jan 02, 2021 |
| Dell          | 0C27VV A02                  | Desktop     | [889bba9dbc](https://bsd-hardware.info/?probe=889bba9dbc) | Dec 30, 2020 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [a3e2c4eda1](https://bsd-hardware.info/?probe=a3e2c4eda1) | Dec 30, 2020 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [df9318dcea](https://bsd-hardware.info/?probe=df9318dcea) | Dec 27, 2020 |
| Dell          | Inspiron 5758               | Notebook    | [51ed7b02c2](https://bsd-hardware.info/?probe=51ed7b02c2) | Dec 21, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [c8c11a071d](https://bsd-hardware.info/?probe=c8c11a071d) | Dec 14, 2020 |
| Acer          | Aspire V5-122               | Notebook    | [ce0c079fd5](https://bsd-hardware.info/?probe=ce0c079fd5) | Dec 14, 2020 |
| Apple         | MacBookPro11,3              | Notebook    | [26f15a2838](https://bsd-hardware.info/?probe=26f15a2838) | Dec 07, 2020 |
| Lenovo        | ThinkPad T490 20RYS06R00    | Notebook    | [21d88f733e](https://bsd-hardware.info/?probe=21d88f733e) | Dec 07, 2020 |
| Lenovo        | ThinkPad T490 20RYS06R00    | Notebook    | [cdfcd11f7b](https://bsd-hardware.info/?probe=cdfcd11f7b) | Dec 07, 2020 |
| IBM           | 2647NG8                     | Notebook    | [a0f38de52f](https://bsd-hardware.info/?probe=a0f38de52f) | Nov 22, 2020 |
| HP            | ProBook 640 G1              | Notebook    | [bf763e72ad](https://bsd-hardware.info/?probe=bf763e72ad) | Nov 13, 2020 |
| Acer          | Aspire E5-432               | Notebook    | [39fb05c049](https://bsd-hardware.info/?probe=39fb05c049) | Nov 01, 2020 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [31f5a66353](https://bsd-hardware.info/?probe=31f5a66353) | Oct 25, 2020 |
| Acer          | Aspire V3-575G              | Notebook    | [1ff0e90d9d](https://bsd-hardware.info/?probe=1ff0e90d9d) | Oct 24, 2020 |
| ASUSTek       | Z170-A                      | Desktop     | [a1c6966373](https://bsd-hardware.info/?probe=a1c6966373) | Oct 21, 2020 |
| Google        | Chell                       | Notebook    | [4ffe68c199](https://bsd-hardware.info/?probe=4ffe68c199) | Oct 21, 2020 |
| ASRock        | AB350 Pro4                  | Desktop     | [407652fc8d](https://bsd-hardware.info/?probe=407652fc8d) | Oct 05, 2020 |
| Apple         | MacBookAir7,2               | Notebook    | [36d0d99aa6](https://bsd-hardware.info/?probe=36d0d99aa6) | Oct 04, 2020 |
| Lenovo        | G50-45 80E3                 | Notebook    | [1d227a9cd2](https://bsd-hardware.info/?probe=1d227a9cd2) | Oct 04, 2020 |
| Dell          | Precision 7530              | Notebook    | [717309ee39](https://bsd-hardware.info/?probe=717309ee39) | Sep 28, 2020 |
| Dell          | Precision 7530              | Notebook    | [6a2635237f](https://bsd-hardware.info/?probe=6a2635237f) | Sep 28, 2020 |
| Lenovo        | ThinkPad T530 24295VU       | Notebook    | [f7d13e4696](https://bsd-hardware.info/?probe=f7d13e4696) | Sep 23, 2020 |
| Lenovo        | ThinkPad T530 24295VU       | Notebook    | [45f410f4e4](https://bsd-hardware.info/?probe=45f410f4e4) | Sep 23, 2020 |
| Lenovo        | ThinkPad T430 2347C32       | Notebook    | [339c63a941](https://bsd-hardware.info/?probe=339c63a941) | Sep 22, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [89bb299f1e](https://bsd-hardware.info/?probe=89bb299f1e) | Sep 22, 2020 |
| Dell          | Vostro 3750                 | Notebook    | [587a9276bb](https://bsd-hardware.info/?probe=587a9276bb) | Sep 06, 2020 |
| Foxconn       | Napa HP P/N                 | Desktop     | [2a7cb7b214](https://bsd-hardware.info/?probe=2a7cb7b214) | Sep 03, 2020 |
| Panasonic     | CF-C1BD06EFG                | Notebook    | [3e876bada1](https://bsd-hardware.info/?probe=3e876bada1) | Sep 02, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [4d1897ed1f](https://bsd-hardware.info/?probe=4d1897ed1f) | Aug 29, 2020 |
| ASUSTek       | EMERY                       | Desktop     | [c93b86b3ba](https://bsd-hardware.info/?probe=c93b86b3ba) | Aug 27, 2020 |
| Lenovo        | ThinkPad T460 20FMS78014    | Notebook    | [d78837860f](https://bsd-hardware.info/?probe=d78837860f) | Aug 23, 2020 |
| ASUSTek       | V241ICR-R                   | All in one  | [f21adeb92c](https://bsd-hardware.info/?probe=f21adeb92c) | Aug 20, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [5ef34cd40f](https://bsd-hardware.info/?probe=5ef34cd40f) | Aug 20, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [6ca9384f34](https://bsd-hardware.info/?probe=6ca9384f34) | Aug 20, 2020 |
| HP            | 0A64h                       | Desktop     | [10c48336b0](https://bsd-hardware.info/?probe=10c48336b0) | Aug 20, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [78d714a1a3](https://bsd-hardware.info/?probe=78d714a1a3) | Aug 19, 2020 |
| ASUSTek       | X71SL                       | Notebook    | [a2ee0c9edb](https://bsd-hardware.info/?probe=a2ee0c9edb) | Aug 15, 2020 |
| HP            | ProBook 640 G1              | Notebook    | [4b7eaf5a6a](https://bsd-hardware.info/?probe=4b7eaf5a6a) | Aug 12, 2020 |
| Dell          | Latitude 5480               | Notebook    | [907e0da9a4](https://bsd-hardware.info/?probe=907e0da9a4) | Aug 08, 2020 |
| HP            | EliteBook 820 G1            | Notebook    | [12ac8fc96f](https://bsd-hardware.info/?probe=12ac8fc96f) | Aug 07, 2020 |
| Google        | Lulu                        | Notebook    | [64aef60e6b](https://bsd-hardware.info/?probe=64aef60e6b) | Aug 02, 2020 |
| Lenovo        | ThinkPad T490s 20NX000DR... | Notebook    | [0919d8936f](https://bsd-hardware.info/?probe=0919d8936f) | Jul 27, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [15e87049a7](https://bsd-hardware.info/?probe=15e87049a7) | Jul 27, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8a3cb911c3](https://bsd-hardware.info/?probe=8a3cb911c3) | Jul 18, 2020 |
| Lenovo        | ThinkPad T450 20BUS06B00    | Notebook    | [f437a3b5ab](https://bsd-hardware.info/?probe=f437a3b5ab) | Jul 06, 2020 |
| Unknown       | Unknown                     | Notebook    | [f9ed1dce06](https://bsd-hardware.info/?probe=f9ed1dce06) | Jul 05, 2020 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [a03e1c19c1](https://bsd-hardware.info/?probe=a03e1c19c1) | Jul 04, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0VK0... | Notebook    | [b726c4536b](https://bsd-hardware.info/?probe=b726c4536b) | Jul 04, 2020 |
| ASRock        | Z97 Extreme6/ac             | Desktop     | [9c2d19d0c3](https://bsd-hardware.info/?probe=9c2d19d0c3) | Jul 03, 2020 |
| Intel         | NUC5i3RYB H41000-507        | Mini pc     | [5fac785920](https://bsd-hardware.info/?probe=5fac785920) | Jul 03, 2020 |
| Dell          | Latitude E7240              | Notebook    | [1de87c0000](https://bsd-hardware.info/?probe=1de87c0000) | May 30, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [aa58b291b3](https://bsd-hardware.info/?probe=aa58b291b3) | May 24, 2020 |
| ASUSTek       | X71SL                       | Notebook    | [adf290251e](https://bsd-hardware.info/?probe=adf290251e) | May 09, 2020 |
| Sony          | SVE1713S1RW                 | Notebook    | [9a751ddfd8](https://bsd-hardware.info/?probe=9a751ddfd8) | May 08, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| NomadBSD 5806f915 | 54        | 31.58%  |
| NomadBSD 1.3.2    | 52        | 30.41%  |
| NomadBSD 1.4      | 23        | 13.45%  |
| NomadBSD 20221130 | 19        | 11.11%  |
| NomadBSD 1.4-RC1  | 10        | 5.85%   |
| NomadBSD 1.3.1    | 10        | 5.85%   |
| NomadBSD 80dec9b9 | 1         | 0.58%   |
| NomadBSD 1.3      | 1         | 0.58%   |
| NomadBSD 1.0      | 1         | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| NomadBSD | 166       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 158       | 94.61%  |
| i386  | 9         | 5.39%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Openbox       | 143       | 85.63%  |
| GNOME         | 7         | 4.19%   |
| xinitrc       | 6         | 3.59%   |
| KDE5          | 5         | 2.99%   |
| Enlightenment | 3         | 1.8%    |
| XFCE          | 1         | 0.6%    |
| GNUstep       | 1         | 0.6%    |
| filer         | 1         | 0.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 166       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SLiM    | 144       | 86.75%  |
| SDDM    | 20        | 12.05%  |
| LightDM | 2         | 1.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 62        | 36.9%   |
| Unknown | 29        | 17.26%  |
| de_DE   | 17        | 10.12%  |
| en_GB   | 12        | 7.14%   |
| ru_RU   | 8         | 4.76%   |
| fr_FR   | 6         | 3.57%   |
| it_IT   | 5         | 2.98%   |
| hu_HU   | 5         | 2.98%   |
| zh_CN   | 3         | 1.79%   |
| tr_TR   | 3         | 1.79%   |
| es_ES   | 3         | 1.79%   |
| pt_BR   | 2         | 1.19%   |
| pl_PL   | 2         | 1.19%   |
| fi_FI   | 2         | 1.19%   |
| en_AU   | 2         | 1.19%   |
| cs_CZ   | 2         | 1.19%   |
| bg_BG   | 2         | 1.19%   |
| lt_LT   | 1         | 0.6%    |
| ko_KR   | 1         | 0.6%    |
| et_EE   | 1         | 0.6%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 160       | 95.81%  |
| BIOS | 7         | 4.19%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ufs  | 142       | 85.54%  |
| Zfs  | 24        | 14.46%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 118       | 70.66%  |
| MBR  | 49        | 29.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 33        | 19.88%  |
| Hewlett-Packard     | 24        | 14.46%  |
| Dell                | 23        | 13.86%  |
| ASUSTek Computer    | 22        | 13.25%  |
| Acer                | 11        | 6.63%   |
| Gigabyte Technology | 6         | 3.61%   |
| ASRock              | 6         | 3.61%   |
| Apple               | 5         | 3.01%   |
| TUXEDO              | 3         | 1.81%   |
| Sony                | 3         | 1.81%   |
| Samsung Electronics | 3         | 1.81%   |
| Intel               | 3         | 1.81%   |
| Fujitsu             | 3         | 1.81%   |
| Pegatron            | 2         | 1.2%    |
| Notebook            | 2         | 1.2%    |
| Google              | 2         | 1.2%    |
| Unknown             | 2         | 1.2%    |
| Toshiba             | 1         | 0.6%    |
| Semp Toshiba        | 1         | 0.6%    |
| Panasonic           | 1         | 0.6%    |
| NEC Computers       | 1         | 0.6%    |
| MSI                 | 1         | 0.6%    |
| IBM                 | 1         | 0.6%    |
| GEO                 | 1         | 0.6%    |
| Fujitsu Siemens     | 1         | 0.6%    |
| Foxconn             | 1         | 0.6%    |
| ECS                 | 1         | 0.6%    |
| Clevo               | 1         | 0.6%    |
| ASRockRack          | 1         | 0.6%    |
| Alienware           | 1         | 0.6%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Unknown                                   | 3         | 1.81%   |
| HP Z420 Workstation                       | 2         | 1.2%    |
| ASUS ROG STRIX B550-F GAMING              | 2         | 1.2%    |
| Acer Veriton M460                         | 2         | 1.2%    |
| TUXEDO Pulse 15 Gen2                      | 1         | 0.6%    |
| TUXEDO InfinityBook S 15 Gen6             | 1         | 0.6%    |
| Toshiba Satellite C660                    | 1         | 0.6%    |
| Sony VPCM13M1R                            | 1         | 0.6%    |
| Sony VJS121C11N                           | 1         | 0.6%    |
| Sony SVE1713S1RW                          | 1         | 0.6%    |
| Semp Toshiba STI                          | 1         | 0.6%    |
| Samsung N150/N210/N220                    | 1         | 0.6%    |
| Samsung N145P/N250P/N260P                 | 1         | 0.6%    |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV   | 1         | 0.6%    |
| Pegatron T12Ah                            | 1         | 0.6%    |
| Pegatron Elite 7300 Series MT             | 1         | 0.6%    |
| Panasonic CF-C1BD06EFG                    | 1         | 0.6%    |
| Notebook W650DC,DD                        | 1         | 0.6%    |
| Notebook N650DU                           | 1         | 0.6%    |
| NEC Computers PC-GL186Y3AZ                | 1         | 0.6%    |
| MSI MS-N033                               | 1         | 0.6%    |
| Lenovo Yoga 710-11IKB 80V6                | 1         | 0.6%    |
| Lenovo V580 20147                         | 1         | 0.6%    |
| Lenovo ThinkPad X380 Yoga 20LJ000WUK      | 1         | 0.6%    |
| Lenovo ThinkPad X280 20KESB4T00           | 1         | 0.6%    |
| Lenovo ThinkPad X230 23255NG              | 1         | 0.6%    |
| Lenovo ThinkPad X201 Tablet 311396U       | 1         | 0.6%    |
| Lenovo ThinkPad X13 Yoga Gen 1 20SYS22H00 | 1         | 0.6%    |
| Lenovo ThinkPad X1 Yoga 3rd 20LDS1CG00    | 1         | 0.6%    |
| Lenovo ThinkPad X1 Carbon 4th 20FB001XAU  | 1         | 0.6%    |
| Lenovo ThinkPad W541 20EGS04800           | 1         | 0.6%    |
| Lenovo ThinkPad W520 42844DG              | 1         | 0.6%    |
| Lenovo ThinkPad T530 24295VU              | 1         | 0.6%    |
| Lenovo ThinkPad T510 4384FF3              | 1         | 0.6%    |
| Lenovo ThinkPad T490s 20NX000DRT          | 1         | 0.6%    |
| Lenovo ThinkPad T490 20RYS06R00           | 1         | 0.6%    |
| Lenovo ThinkPad T480 20L50000GE           | 1         | 0.6%    |
| Lenovo ThinkPad T470s W10DG 20JS001FGE    | 1         | 0.6%    |
| Lenovo ThinkPad T470 20HES0EV0A           | 1         | 0.6%    |
| Lenovo ThinkPad T460 20FMS78014           | 1         | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 24        | 14.46%  |
| Dell Latitude              | 9         | 5.42%   |
| Acer Aspire                | 8         | 4.82%   |
| Dell OptiPlex              | 5         | 3.01%   |
| HP Compaq                  | 4         | 2.41%   |
| HP ProBook                 | 3         | 1.81%   |
| HP Pavilion                | 3         | 1.81%   |
| Dell Studio                | 3         | 1.81%   |
| Dell Inspiron              | 3         | 1.81%   |
| ASUS ROG                   | 3         | 1.81%   |
| Unknown                    | 3         | 1.81%   |
| Lenovo IdeaPad             | 2         | 1.2%    |
| HP Z420                    | 2         | 1.2%    |
| HP Laptop                  | 2         | 1.2%    |
| Gigabyte Z370              | 2         | 1.2%    |
| Gigabyte X570              | 2         | 1.2%    |
| Fujitsu LIFEBOOK           | 2         | 1.2%    |
| ASUS TUF                   | 2         | 1.2%    |
| ASUS PRIME                 | 2         | 1.2%    |
| Acer Veriton               | 2         | 1.2%    |
| TUXEDO Pulse               | 1         | 0.6%    |
| TUXEDO InfinityBook        | 1         | 0.6%    |
| Toshiba Satellite          | 1         | 0.6%    |
| Sony VPCM13M1R             | 1         | 0.6%    |
| Sony VJS121C11N            | 1         | 0.6%    |
| Sony SVE1713S1RW           | 1         | 0.6%    |
| Semp Toshiba STI           | 1         | 0.6%    |
| Samsung N150               | 1         | 0.6%    |
| Samsung N145P              | 1         | 0.6%    |
| Samsung 300E5EV            | 1         | 0.6%    |
| Pegatron T12Ah             | 1         | 0.6%    |
| Pegatron Elite             | 1         | 0.6%    |
| Panasonic CF-C1BD06EFG     | 1         | 0.6%    |
| Notebook W650DC            | 1         | 0.6%    |
| Notebook N650DU            | 1         | 0.6%    |
| NEC Computers PC-GL186Y3AZ | 1         | 0.6%    |
| MSI MS-N033                | 1         | 0.6%    |
| Lenovo Yoga                | 1         | 0.6%    |
| Lenovo V580                | 1         | 0.6%    |
| Lenovo ThinkCentre         | 1         | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 22        | 13.25%  |
| 2020 | 19        | 11.45%  |
| 2017 | 14        | 8.43%   |
| 2021 | 11        | 6.63%   |
| 2015 | 11        | 6.63%   |
| 2013 | 11        | 6.63%   |
| 2012 | 11        | 6.63%   |
| 2018 | 10        | 6.02%   |
| 2010 | 9         | 5.42%   |
| 2009 | 9         | 5.42%   |
| 2014 | 8         | 4.82%   |
| 2011 | 8         | 4.82%   |
| 2016 | 7         | 4.22%   |
| 2008 | 7         | 4.22%   |
| 2022 | 4         | 2.41%   |
| 2006 | 3         | 1.81%   |
| 2007 | 1         | 0.6%    |
| 2004 | 1         | 0.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 107       | 64.46%  |
| Desktop     | 49        | 29.52%  |
| Convertible | 5         | 3.01%   |
| Mini pc     | 2         | 1.2%    |
| All in one  | 2         | 1.2%    |
| Server      | 1         | 0.6%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 163       | 98.19%  |
| Yes  | 3         | 1.81%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 64        | 38.32%  |
| 16.01-24.0  | 36        | 21.56%  |
| 4.01-8.0    | 34        | 20.36%  |
| 32.01-64.0  | 14        | 8.38%   |
| 64.01-256.0 | 6         | 3.59%   |
| 2.01-3.0    | 5         | 2.99%   |
| 3.01-4.0    | 3         | 1.8%    |
| 0.51-1.0    | 3         | 1.8%    |
| 24.01-32.0  | 2         | 1.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 86        | 50.89%  |
| 0.51-1.0  | 50        | 29.59%  |
| 1.01-2.0  | 22        | 13.02%  |
| 2.01-3.0  | 7         | 4.14%   |
| 4.01-8.0  | 2         | 1.18%   |
| 3.01-4.0  | 1         | 0.59%   |
| 8.01-16.0 | 1         | 0.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 108       | 64.67%  |
| 2      | 32        | 19.16%  |
| 3      | 13        | 7.78%   |
| 0      | 9         | 5.39%   |
| 4      | 4         | 2.4%    |
| 7      | 1         | 0.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 102       | 61.08%  |
| Yes       | 65        | 38.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 151       | 90.42%  |
| No        | 16        | 9.58%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 135       | 81.33%  |
| No        | 31        | 18.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 58.08%  |
| No        | 70        | 41.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 36        | 21.69%  |
| Germany     | 21        | 12.65%  |
| France      | 18        | 10.84%  |
| Russia      | 17        | 10.24%  |
| UK          | 11        | 6.63%   |
| Italy       | 7         | 4.22%   |
| Turkey      | 5         | 3.01%   |
| Hungary     | 5         | 3.01%   |
| Norway      | 3         | 1.81%   |
| Mexico      | 3         | 1.81%   |
| Colombia    | 3         | 1.81%   |
| China       | 3         | 1.81%   |
| Argentina   | 3         | 1.81%   |
| Thailand    | 2         | 1.2%    |
| Spain       | 2         | 1.2%    |
| Romania     | 2         | 1.2%    |
| Poland      | 2         | 1.2%    |
| Japan       | 2         | 1.2%    |
| Finland     | 2         | 1.2%    |
| Czechia     | 2         | 1.2%    |
| Bulgaria    | 2         | 1.2%    |
| Brazil      | 2         | 1.2%    |
| Australia   | 2         | 1.2%    |
| Ukraine     | 1         | 0.6%    |
| South Korea | 1         | 0.6%    |
| Slovakia    | 1         | 0.6%    |
| Serbia      | 1         | 0.6%    |
| Philippines | 1         | 0.6%    |
| Netherlands | 1         | 0.6%    |
| Lithuania   | 1         | 0.6%    |
| Hong Kong   | 1         | 0.6%    |
| Estonia     | 1         | 0.6%    |
| Denmark     | 1         | 0.6%    |
| Belarus     | 1         | 0.6%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Moscow                | 10        | 5.95%   |
| Franconville          | 6         | 3.57%   |
| Paris                 | 5         | 2.98%   |
| Hodmezovasarhely      | 5         | 2.98%   |
| Istanbul              | 4         | 2.38%   |
| Duncan                | 4         | 2.38%   |
| Woodland              | 3         | 1.79%   |
| Whittier              | 3         | 1.79%   |
| Tijuana               | 3         | 1.79%   |
| Milan                 | 3         | 1.79%   |
| Markt Indersdorf      | 3         | 1.79%   |
| Zwingenberg           | 2         | 1.19%   |
| Volzhskiy             | 2         | 1.19%   |
| Vollen                | 2         | 1.19%   |
| St Petersburg         | 2         | 1.19%   |
| Sofia                 | 2         | 1.19%   |
| Setagaya-ku           | 2         | 1.19%   |
| Rome                  | 2         | 1.19%   |
| Rio de Janeiro        | 2         | 1.19%   |
| New Braunfels         | 2         | 1.19%   |
| Melun                 | 2         | 1.19%   |
| McDonough             | 2         | 1.19%   |
| Lutherville-Timonium  | 2         | 1.19%   |
| Los Angeles           | 2         | 1.19%   |
| Greenwich             | 2         | 1.19%   |
| Drobeta-Turnu Severin | 2         | 1.19%   |
| Cologne               | 2         | 1.19%   |
| Changzhou             | 2         | 1.19%   |
| Brisbane              | 2         | 1.19%   |
| BogotГЎ             | 2         | 1.19%   |
| Bangkok               | 2         | 1.19%   |
| Wloszczowa            | 1         | 0.6%    |
| Wissen                | 1         | 0.6%    |
| Winter Haven          | 1         | 0.6%    |
| Wilhelmshaven         | 1         | 0.6%    |
| West Bromwich         | 1         | 0.6%    |
| Warsaw                | 1         | 0.6%    |
| Wakefield             | 1         | 0.6%    |
| Vladimir              | 1         | 0.6%    |
| Vilnius               | 1         | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 41        | 52     | 19.25%  |
| WDC                 | 36        | 44     | 16.9%   |
| Seagate             | 30        | 33     | 14.08%  |
| Toshiba             | 19        | 22     | 8.92%   |
| Crucial             | 11        | 11     | 5.16%   |
| SanDisk             | 8         | 9      | 3.76%   |
| Kingston            | 8         | 9      | 3.76%   |
| SK hynix            | 6         | 7      | 2.82%   |
| Intel               | 6         | 6      | 2.82%   |
| Hitachi             | 6         | 7      | 2.82%   |
| Apple               | 5         | 6      | 2.35%   |
| A-DATA Technology   | 5         | 5      | 2.35%   |
| Micron Technology   | 3         | 3      | 1.41%   |
| Hewlett-Packard     | 3         | 3      | 1.41%   |
| Transcend           | 2         | 2      | 0.94%   |
| SPCC                | 2         | 2      | 0.94%   |
| PNY                 | 2         | 2      | 0.94%   |
| OCZ                 | 2         | 2      | 0.94%   |
| Intenso             | 2         | 2      | 0.94%   |
| HGST                | 2         | 2      | 0.94%   |
| Gigabyte Technology | 2         | 2      | 0.94%   |
| Fujitsu             | 2         | 3      | 0.94%   |
| Corsair             | 2         | 2      | 0.94%   |
| UMIS                | 1         | 1      | 0.47%   |
| Team                | 1         | 1      | 0.47%   |
| Phison              | 1         | 1      | 0.47%   |
| ORICO               | 1         | 1      | 0.47%   |
| Maxtor              | 1         | 1      | 0.47%   |
| LITEONIT            | 1         | 1      | 0.47%   |
| KingDian            | 1         | 1      | 0.47%   |
| ASUSTek Computer    | 1         | 2      | 0.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB          | 4         | 1.75%   |
| Toshiba MQ01ABD100 1TB               | 3         | 1.31%   |
| Seagate ST1000LM049-2GH172 1TB       | 3         | 1.31%   |
| SanDisk pSSD 128GB                   | 3         | 1.31%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 1.31%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 2         | 0.87%   |
| WDC WD40PURX-64GVNY0 4TB             | 2         | 0.87%   |
| WDC WD1600AAJS-22L7A0 160GB          | 2         | 0.87%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB | 2         | 0.87%   |
| Toshiba MQ01ABF050 500GB             | 2         | 0.87%   |
| Toshiba HDWD120 2TB                  | 2         | 0.87%   |
| Seagate ST95005620AS 500GB           | 2         | 0.87%   |
| Seagate ST9500325AS 500GB            | 2         | 0.87%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 0.87%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 0.87%   |
| SanDisk SSD U100 24GB                | 2         | 0.87%   |
| Samsung SSD 980 PRO 250GB            | 2         | 0.87%   |
| Samsung SSD 970 EVO 500GB            | 2         | 0.87%   |
| Samsung SSD 870 QVO 2TB              | 2         | 0.87%   |
| Samsung SSD 840 EVO 250GB            | 2         | 0.87%   |
| Samsung MZVLB256HBHQ-000L7 256GB     | 2         | 0.87%   |
| Kingston SA400S37480G 480GB          | 2         | 0.87%   |
| HGST HTS725050A7E630 500GB           | 2         | 0.87%   |
| HP SSD EX950 2TB                     | 2         | 0.87%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 0.87%   |
| Crucial CT1000P1SSD8 1TB             | 2         | 0.87%   |
| Apple SSD SM0512F 500GB              | 2         | 0.87%   |
| A-DATA SU630 240GB                   | 2         | 0.87%   |
| WDC WDS240G2G0B-00EPW0 240GB         | 1         | 0.44%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 0.44%   |
| WDC WDS120G2G0B-00EPW0 120GB         | 1         | 0.44%   |
| WDC WDS120G2G0A-00JH30 120GB         | 1         | 0.44%   |
| WDC WDS120G1G0A-00SS50 120GB         | 1         | 0.44%   |
| WDC WD7500BPKX-00HPJT0 752GB         | 1         | 0.44%   |
| WDC WD7500BPKT-75PK4T0 752GB         | 1         | 0.44%   |
| WDC WD6400AAKS-22A7B2 640GB          | 1         | 0.44%   |
| WDC WD60EZRZ-00GZ5B1 6TB             | 1         | 0.44%   |
| WDC WD40NMZW-11GX6S1 4TB             | 1         | 0.44%   |
| WDC WD40EFAX-68JH4N0 4TB             | 1         | 0.44%   |
| WDC WD3200BEVT-75ZCT2 320GB          | 1         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 30        | 33     | 32.97%  |
| WDC                 | 29        | 32     | 31.87%  |
| Toshiba             | 15        | 17     | 16.48%  |
| Hitachi             | 6         | 7      | 6.59%   |
| Samsung Electronics | 4         | 4      | 4.4%    |
| HGST                | 2         | 2      | 2.2%    |
| Fujitsu             | 2         | 3      | 2.2%    |
| Maxtor              | 1         | 1      | 1.1%    |
| Hewlett-Packard     | 1         | 1      | 1.1%    |
| Apple               | 1         | 1      | 1.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 23     | 23.46%  |
| SanDisk             | 8         | 9      | 9.88%   |
| Kingston            | 7         | 8      | 8.64%   |
| Crucial             | 7         | 7      | 8.64%   |
| A-DATA Technology   | 5         | 5      | 6.17%   |
| WDC                 | 4         | 5      | 4.94%   |
| Apple               | 4         | 5      | 4.94%   |
| Toshiba             | 3         | 3      | 3.7%    |
| Intel               | 3         | 3      | 3.7%    |
| Transcend           | 2         | 2      | 2.47%   |
| SPCC                | 2         | 2      | 2.47%   |
| SK hynix            | 2         | 2      | 2.47%   |
| PNY                 | 2         | 2      | 2.47%   |
| OCZ                 | 2         | 2      | 2.47%   |
| Micron Technology   | 2         | 2      | 2.47%   |
| Intenso             | 2         | 2      | 2.47%   |
| Gigabyte Technology | 2         | 2      | 2.47%   |
| Team                | 1         | 1      | 1.23%   |
| LITEONIT            | 1         | 1      | 1.23%   |
| KingDian            | 1         | 1      | 1.23%   |
| Corsair             | 1         | 1      | 1.23%   |
| ASUSTek Computer    | 1         | 2      | 1.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 78        | 101    | 40.63%  |
| SSD  | 73        | 90     | 38.02%  |
| NVMe | 41        | 54     | 21.35%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 134       | 191    | 76.57%  |
| NVMe | 41        | 54     | 23.43%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 97        | 123    | 61.39%  |
| 0.51-1.0   | 41        | 46     | 25.95%  |
| 1.01-2.0   | 10        | 10     | 6.33%   |
| 3.01-4.0   | 5         | 5      | 3.16%   |
| 2.01-3.0   | 4         | 4      | 2.53%   |
| 4.01-10.0  | 1         | 3      | 0.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 133       | 80.12%  |
| 101-250    | 16        | 9.64%   |
| 51-100     | 6         | 3.61%   |
| 21-50      | 5         | 3.01%   |
| 251-500    | 3         | 1.81%   |
| 501-1000   | 3         | 1.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 162       | 97.01%  |
| 21-50   | 3         | 1.8%    |
| 51-100  | 2         | 1.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPKT-75PK4T0 752GB                     | 1         | 1      | 3.13%   |
| WDC WD40PURX-64GVNY0 4TB                         | 1         | 1      | 3.13%   |
| WDC WD2500BEVT-80A23T0 250GB                     | 1         | 1      | 3.13%   |
| WDC WD1200BEVS-07LAT0 120GB                      | 1         | 1      | 3.13%   |
| WDC WD10JPVX-75JC3T0 1TB                         | 1         | 1      | 3.13%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 3.13%   |
| WDC WD10EFRX-68PJCN0 1TB                         | 1         | 2      | 3.13%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 3.13%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 3.13%   |
| Toshiba MK7575GSX 752GB                          | 1         | 1      | 3.13%   |
| Toshiba HDWD120 2TB                              | 1         | 1      | 3.13%   |
| Toshiba DT01ABA300 3TB                           | 1         | 1      | 3.13%   |
| Seagate ST95005620AS 500GB                       | 1         | 1      | 3.13%   |
| Seagate ST9250315AS 250GB                        | 1         | 1      | 3.13%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 3.13%   |
| Seagate ST500LM021-1KJ152 500GB                  | 1         | 1      | 3.13%   |
| Seagate ST500DM002-1BD142 500GB                  | 1         | 1      | 3.13%   |
| Seagate ST3250823AS 250GB                        | 1         | 1      | 3.13%   |
| Seagate ST310212A 10GB                           | 1         | 1      | 3.13%   |
| SanDisk SD9SN8W-128G-1006 128GB                  | 1         | 1      | 3.13%   |
| Samsung Electronics SSD PM810 2.5-inch 7mm 256GB | 1         | 1      | 3.13%   |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 3.13%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB       | 1         | 1      | 3.13%   |
| Intenso SSD Sata III 128GB                       | 1         | 1      | 3.13%   |
| Intel SSDSC2CW060A3 64GB                         | 1         | 1      | 3.13%   |
| Hitachi HTS545050B9A300 500GB                    | 1         | 2      | 3.13%   |
| Hitachi HTS545032B9A302 320GB                    | 1         | 1      | 3.13%   |
| Hitachi HTS545032B9A300 320GB                    | 1         | 1      | 3.13%   |
| HGST HTS725050A7E630 500GB                       | 1         | 1      | 3.13%   |
| Hewlett-Packard MB1000GCWCV 1TB                  | 1         | 1      | 3.13%   |
| Corsair Neutron GTX SSD 120GB                    | 1         | 1      | 3.13%   |
| A-DATA Technology XM13 32GB                      | 1         | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 8      | 21.88%  |
| Seagate             | 7         | 7      | 21.88%  |
| Toshiba             | 5         | 5      | 15.63%  |
| Hitachi             | 3         | 4      | 9.38%   |
| Samsung Electronics | 2         | 2      | 6.25%   |
| SanDisk             | 1         | 1      | 3.13%   |
| Micron Technology   | 1         | 1      | 3.13%   |
| Intenso             | 1         | 1      | 3.13%   |
| Intel               | 1         | 1      | 3.13%   |
| HGST                | 1         | 1      | 3.13%   |
| Hewlett-Packard     | 1         | 1      | 3.13%   |
| Corsair             | 1         | 1      | 3.13%   |
| A-DATA Technology   | 1         | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 8      | 28%     |
| Seagate             | 7         | 7      | 28%     |
| Toshiba             | 5         | 5      | 20%     |
| Hitachi             | 3         | 4      | 12%     |
| Samsung Electronics | 1         | 1      | 4%      |
| HGST                | 1         | 1      | 4%      |
| Hewlett-Packard     | 1         | 1      | 4%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 27     | 77.42%  |
| SSD  | 7         | 7      | 22.58%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model              | Computers | Drives | Percent |
|--------------------|-----------|--------|---------|
| SanDisk pSSD 128GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 135       | 202    | 79.88%  |
| Malfunc  | 31        | 34     | 18.34%  |
| Detected | 2         | 8      | 1.18%   |
| Failed   | 1         | 1      | 0.59%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 119       | 58.05%  |
| AMD                                     | 26        | 12.68%  |
| Samsung Electronics                     | 24        | 11.71%  |
| SanDisk                                 | 7         | 3.41%   |
| ASMedia Technology                      | 6         | 2.93%   |
| Micron/Crucial Technology               | 4         | 1.95%   |
| SK hynix                                | 3         | 1.46%   |
| Nvidia                                  | 3         | 1.46%   |
| VIA Technologies                        | 2         | 0.98%   |
| Phison Electronics                      | 2         | 0.98%   |
| Biwin Storage Technology                | 2         | 0.98%   |
| Toshiba                                 | 1         | 0.49%   |
| Silicon Motion                          | 1         | 0.49%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.49%   |
| Shenzhen Unionmemory Information System | 1         | 0.49%   |
| Micron Technology                       | 1         | 0.49%   |
| Kingston Technology Company             | 1         | 0.49%   |
| JMicron Technology                      | 1         | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 19        | 7.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 14        | 5.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 13        | 5.42%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 9         | 3.75%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 3.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 3.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 7         | 2.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 2.5%    |
| ASMedia ASM1062 Serial ATA Controller                                            | 6         | 2.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 5         | 2.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 2.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 4         | 1.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 1.67%   |
| AMD 500 Series Chipset SATA Controller                                           | 4         | 1.67%   |
| Unknown                                                                          | 4         | 1.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.25%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.25%   |
| Intel SATA Controller [RAID mode]                                                | 3         | 1.25%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 3         | 1.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 1.25%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 1.25%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 2         | 0.83%   |
| SanDisk PC SN520 NVMe SSD                                                        | 2         | 0.83%   |
| Samsung SM951 AHCI                                                               | 2         | 0.83%   |
| Samsung Apple PCIe SSD                                                           | 2         | 0.83%   |
| Nvidia MCP61 SATA Controller                                                     | 2         | 0.83%   |
| Nvidia MCP61 IDE                                                                 | 2         | 0.83%   |
| Micron/Crucial NVMe Storage Controller                                           | 2         | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 0.83%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 0.83%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.83%   |
| Intel C600/X79 series chipset IDE-r Controller                                   | 2         | 0.83%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                         | 2         | 0.83%   |
| Intel C600/X79 series chipset 2-Port SATA IDE Controller                         | 2         | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.83%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2         | 0.83%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 115       | 56.1%   |
| NVMe | 41        | 20%     |
| IDE  | 31        | 15.12%  |
| RAID | 15        | 7.32%   |
| SAS  | 3         | 1.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 137       | 82.04%  |
| AMD    | 30        | 17.96%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 2.4%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 2.4%    |
| Intel CPU Version                             | 3         | 1.8%    |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 1.8%    |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 1.8%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.8%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.8%    |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 1.2%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.2%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.2%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.2%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.2%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 1.2%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 1.2%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.2%    |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz          | 2         | 1.2%    |
| Intel Core 2 Duo                              | 2         | 1.2%    |
| AMD Ryzen 9 5900X 12-Core Processor           | 2         | 1.2%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.2%    |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 2         | 1.2%    |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 2         | 1.2%    |
| Intel Xeon CPU E5640 @ 2.67GHz                | 1         | 0.6%    |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz            | 1         | 0.6%    |
| Intel Xeon CPU E5-2670 @ 2.60GHz              | 1         | 0.6%    |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz           | 1         | 0.6%    |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz           | 1         | 0.6%    |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.6%    |
| Intel Xeon CPU E3-1276 v3 @ 3.60GHz           | 1         | 0.6%    |
| Intel Pentium Silver J5005 CPU @ 1.50GHz      | 1         | 0.6%    |
| Intel Pentium III                             | 1         | 0.6%    |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz   | 1         | 0.6%    |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 1         | 0.6%    |
| Intel Pentium D CPU 2.80GHz                   | 1         | 0.6%    |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.6%    |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.6%    |
| Intel Pentium CPU 2117U @ 1.80GHz             | 1         | 0.6%    |
| Intel Genuine CPU U7300 @ 1.30GHz             | 1         | 0.6%    |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 0.6%    |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.6%    |
| Intel Core i9-7960X CPU @ 2.80GHz             | 1         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 48        | 28.74%  |
| Intel Core i7           | 37        | 22.16%  |
| Intel Core 2 Duo        | 10        | 5.99%   |
| Intel Core i3           | 9         | 5.39%   |
| AMD Ryzen 5             | 9         | 5.39%   |
| Intel Xeon              | 7         | 4.19%   |
| Other                   | 6         | 3.59%   |
| AMD Ryzen 7             | 6         | 3.59%   |
| Intel Atom              | 4         | 2.4%    |
| Intel Pentium           | 3         | 1.8%    |
| Intel Celeron           | 3         | 1.8%    |
| AMD A8                  | 3         | 1.8%    |
| AMD A6                  | 3         | 1.8%    |
| Intel Pentium Dual-Core | 2         | 1.2%    |
| Intel Core i9           | 2         | 1.2%    |
| AMD Ryzen 9             | 2         | 1.2%    |
| AMD Athlon 64 X2        | 2         | 1.2%    |
| Intel Pentium Silver    | 1         | 0.6%    |
| Intel Pentium III       | 1         | 0.6%    |
| Intel Pentium D         | 1         | 0.6%    |
| Intel Genuine           | 1         | 0.6%    |
| Intel Core m5           | 1         | 0.6%    |
| Intel Core 2            | 1         | 0.6%    |
| Intel Celeron M         | 1         | 0.6%    |
| AMD Phenom II X4        | 1         | 0.6%    |
| AMD FX                  | 1         | 0.6%    |
| AMD E1                  | 1         | 0.6%    |
| AMD A10                 | 1         | 0.6%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 69        | 41.32%  |
| 4       | 57        | 34.13%  |
| 8       | 10        | 5.99%   |
| Unknown | 10        | 5.99%   |
| 6       | 7         | 4.19%   |
| 12      | 5         | 2.99%   |
| 16      | 4         | 2.4%    |
| 1       | 3         | 1.8%    |
| 24      | 2         | 1.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 164       | 98.8%   |
| 2       | 1         | 0.6%    |
| Unknown | 1         | 0.6%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 97        | 58.08%  |
| 1       | 58        | 34.73%  |
| Unknown | 12        | 7.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 34        | 20.36%  |
| Haswell       | 21        | 12.57%  |
| IvyBridge     | 16        | 9.58%   |
| Skylake       | 14        | 8.38%   |
| Penryn        | 14        | 8.38%   |
| SandyBridge   | 11        | 6.59%   |
| Zen+          | 6         | 3.59%   |
| Puma          | 5         | 2.99%   |
| Bonnell       | 5         | 2.99%   |
| Broadwell     | 4         | 2.4%    |
| Zen 3         | 3         | 1.8%    |
| Zen 2         | 3         | 1.8%    |
| Zen           | 3         | 1.8%    |
| Westmere      | 3         | 1.8%    |
| Nehalem       | 3         | 1.8%    |
| Core          | 3         | 1.8%    |
| Silvermont    | 2         | 1.2%    |
| P6            | 2         | 1.2%    |
| K8 Hammer     | 2         | 1.2%    |
| Goldmont plus | 2         | 1.2%    |
| Unknown       | 2         | 1.2%    |
| TigerLake     | 1         | 0.6%    |
| Steamroller   | 1         | 0.6%    |
| Piledriver    | 1         | 0.6%    |
| NetBurst      | 1         | 0.6%    |
| K10 Llano     | 1         | 0.6%    |
| K10           | 1         | 0.6%    |
| Jaguar        | 1         | 0.6%    |
| Excavator     | 1         | 0.6%    |
| CometLake     | 1         | 0.6%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 104       | 57.14%  |
| AMD                        | 40        | 21.98%  |
| Nvidia                     | 35        | 19.23%  |
| VIA Technologies           | 1         | 0.55%   |
| S3 Graphics                | 1         | 0.55%   |
| Matrox Electronics Systems | 1         | 0.55%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 5.35%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 4.81%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 4.81%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 4.28%   |
| Intel UHD Graphics 620                                                                   | 7         | 3.74%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2.67%   |
| Intel HD Graphics 620                                                                    | 5         | 2.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 2.67%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 4         | 2.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.14%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 2.14%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.6%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.6%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 1.07%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 1.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.07%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 1.07%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.07%   |
| Intel HD Graphics 630                                                                    | 2         | 1.07%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.07%   |
| Intel HD Graphics 530                                                                    | 2         | 1.07%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.07%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 1.07%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2         | 1.07%   |
| AMD Lucienne                                                                             | 2         | 1.07%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.07%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 1.07%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.53%   |
| S3 Graphics SuperSavage IX/C SDR                                                         | 1         | 0.53%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.53%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.53%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 0.53%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.53%   |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.53%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.53%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 1         | 0.53%   |
| Nvidia GP102 [TITAN X]                                                                   | 1         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 82        | 49.1%   |
| 1 x AMD         | 36        | 21.56%  |
| 1 x Nvidia      | 22        | 13.17%  |
| Intel + Nvidia  | 12        | 7.19%   |
| 2 x Intel       | 8         | 4.79%   |
| Intel + AMD     | 2         | 1.2%    |
| 2 x AMD         | 1         | 0.6%    |
| 1 x VIA         | 1         | 0.6%    |
| 1 x S3 Graphics | 1         | 0.6%    |
| 1 x Matrox      | 1         | 0.6%    |
| AMD + Nvidia    | 1         | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 133       | 80.12%  |
| Proprietary | 17        | 10.24%  |
| Unknown     | 16        | 9.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 134       | 80.24%  |
| 0.01-0.5   | 10        | 5.99%   |
| 1.01-2.0   | 8         | 4.79%   |
| 0.51-1.0   | 5         | 2.99%   |
| 5.01-6.0   | 4         | 2.4%    |
| 7.01-8.0   | 3         | 1.8%    |
| 3.01-4.0   | 3         | 1.8%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 15        | 11.28%  |
| LG Display              | 15        | 11.28%  |
| AU Optronics            | 14        | 10.53%  |
| BOE                     | 13        | 9.77%   |
| Goldstar                | 9         | 6.77%   |
| Chimei Innolux          | 9         | 6.77%   |
| Dell                    | 8         | 6.02%   |
| Acer                    | 6         | 4.51%   |
| Hewlett-Packard         | 5         | 3.76%   |
| Chi Mei Optoelectronics | 4         | 3.01%   |
| Apple                   | 4         | 3.01%   |
| Sharp                   | 3         | 2.26%   |
| Lenovo                  | 3         | 2.26%   |
| HannStar                | 3         | 2.26%   |
| Philips                 | 2         | 1.5%    |
| Panasonic               | 2         | 1.5%    |
| NEC Computers           | 2         | 1.5%    |
| BenQ                    | 2         | 1.5%    |
| ASUSTek Computer        | 2         | 1.5%    |
| Ancor Communications    | 2         | 1.5%    |
| ___                     | 1         | 0.75%   |
| Westinghouse            | 1         | 0.75%   |
| Vizio                   | 1         | 0.75%   |
| ViewSonic               | 1         | 0.75%   |
| Toshiba                 | 1         | 0.75%   |
| Sony                    | 1         | 0.75%   |
| LG Philips              | 1         | 0.75%   |
| LG Electronics          | 1         | 0.75%   |
| CPT                     | 1         | 0.75%   |
| AOC                     | 1         | 0.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 2         | 1.48%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 2         | 1.48%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 220x130mm 10.1-inch                 | 2         | 1.48%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 350x190mm 15.7-inch | 2         | 1.48%   |
| BOE LCD Monitor BOE0671 1366x768 340x190mm 15.3-inch                     | 2         | 1.48%   |
| AU Optronics LCD Monitor AUO8174 1280x800 330x210mm 15.4-inch            | 2         | 1.48%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch            | 2         | 1.48%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 2         | 1.48%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 2         | 1.48%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch             | 2         | 1.48%   |
| ___ MY TV LED TV ___0101 1920x1080                                       | 1         | 0.74%   |
| Westinghouse DWM40F3G1 WET1ECC 1920x1080 880x480mm 39.5-inch             | 1         | 0.74%   |
| Vizio SV370XVT VIZ0057 1920x1080 820x460mm 37.0-inch                     | 1         | 0.74%   |
| ViewSonic VX910 VSC3C19 1280x1024 380x300mm 19.1-inch                    | 1         | 0.74%   |
| Toshiba LCD-MONITOR LCDC980 1280x1024 380x300mm 19.1-inch                | 1         | 0.74%   |
| Sony TV SNY5D01 1360x768                                                 | 1         | 0.74%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch                  | 1         | 0.74%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 0.74%   |
| Sharp LCD Monitor SHP140E 2560x1440 290x170mm 13.2-inch                  | 1         | 0.74%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch        | 1         | 0.74%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 410x260mm 19.1-inch      | 1         | 0.74%   |
| Samsung Electronics S27E330 SAM0D91 1920x1080 600x340mm 27.2-inch        | 1         | 0.74%   |
| Samsung Electronics LF24T450F SAM7094 1920x1080 530x300mm 24.0-inch      | 1         | 0.74%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                        | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch    | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch     | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch     | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 220x130mm 10.1-inch     | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 290x160mm 13.0-inch    | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 310x170mm 13.9-inch     | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 290x160mm 13.0-inch    | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch     | 1         | 0.74%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 600x340mm 27.2-inch        | 1         | 0.74%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                  | 1         | 0.74%   |
| Philips 170S PHL0856 1280x1024 340x270mm 17.1-inch                       | 1         | 0.74%   |
| NEC Computers EA275WMi NEC2BA7 2560x1440 600x340mm 27.2-inch             | 1         | 0.74%   |
| NEC Computers EA223WM NEC6890 1680x1050 470x300mm 22.0-inch              | 1         | 0.74%   |
| LG Philips LCD Monitor LPLA101 1440x900 370x230mm 17.2-inch              | 1         | 0.74%   |
| LG Electronics LCD Monitor LG HDR QHD 2560x1440                          | 1         | 0.74%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 46        | 35.11%  |
| 1366x768 (WXGA)    | 34        | 25.95%  |
| 1280x1024 (SXGA)   | 11        | 8.4%    |
| 1600x900 (HD+)     | 7         | 5.34%   |
| 3840x2160 (4K)     | 5         | 3.82%   |
| 2560x1440 (QHD)    | 4         | 3.05%   |
| 1440x900 (WXGA+)   | 4         | 3.05%   |
| 1280x800 (WXGA)    | 4         | 3.05%   |
| 1024x600           | 4         | 3.05%   |
| 2880x1800          | 2         | 1.53%   |
| 2880x1620          | 2         | 1.53%   |
| 1920x1200 (WUXGA)  | 2         | 1.53%   |
| 1680x1050 (WSXGA+) | 2         | 1.53%   |
| 1360x768           | 2         | 1.53%   |
| 3200x1800 (QHD+)   | 1         | 0.76%   |
| 1600x1200          | 1         | 0.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 35        | 26.12%  |
| 13      | 23        | 17.16%  |
| 17      | 12        | 8.96%   |
| 24      | 10        | 7.46%   |
| 19      | 9         | 6.72%   |
| 27      | 8         | 5.97%   |
| 21      | 7         | 5.22%   |
| 12      | 7         | 5.22%   |
| 11      | 4         | 2.99%   |
| 10      | 4         | 2.99%   |
| Unknown | 4         | 2.99%   |
| 18      | 3         | 2.24%   |
| 23      | 2         | 1.49%   |
| 22      | 2         | 1.49%   |
| 39      | 1         | 0.75%   |
| 37      | 1         | 0.75%   |
| 25      | 1         | 0.75%   |
| 14      | 1         | 0.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 54        | 40.91%  |
| 201-300     | 26        | 19.7%   |
| 501-600     | 18        | 13.64%  |
| 401-500     | 15        | 11.36%  |
| 351-400     | 11        | 8.33%   |
| Unknown     | 4         | 3.03%   |
| 801-900     | 2         | 1.52%   |
| 601-700     | 2         | 1.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 97        | 77.6%   |
| 16/10   | 14        | 11.2%   |
| 5/4     | 11        | 8.8%    |
| Unknown | 2         | 1.6%    |
| 3/2     | 1         | 0.8%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 27        | 20.15%  |
| 201-250        | 20        | 14.93%  |
| 81-90          | 17        | 12.69%  |
| 151-200        | 9         | 6.72%   |
| 141-150        | 9         | 6.72%   |
| 301-350        | 8         | 5.97%   |
| 101-110        | 8         | 5.97%   |
| 71-80          | 7         | 5.22%   |
| 61-70          | 7         | 5.22%   |
| 121-130        | 5         | 3.73%   |
| 51-60          | 4         | 2.99%   |
| 41-50          | 4         | 2.99%   |
| Unknown        | 4         | 2.99%   |
| 251-300        | 2         | 1.49%   |
| 501-1000       | 2         | 1.49%   |
| 131-140        | 1         | 0.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 43        | 33.33%  |
| 51-100        | 38        | 29.46%  |
| 121-160       | 28        | 21.71%  |
| 161-240       | 13        | 10.08%  |
| Unknown       | 4         | 3.1%    |
| More than 240 | 3         | 2.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 127       | 75.6%   |
| 0     | 31        | 18.45%  |
| 2     | 8         | 4.76%   |
| 3     | 2         | 1.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 97        | 39.59%  |
| Realtek Semiconductor             | 68        | 27.76%  |
| Qualcomm Atheros                  | 31        | 12.65%  |
| Broadcom                          | 17        | 6.94%   |
| Ralink                            | 3         | 1.22%   |
| Marvell Technology Group          | 3         | 1.22%   |
| TP-Link                           | 2         | 0.82%   |
| Sierra Wireless                   | 2         | 0.82%   |
| Ralink Technology                 | 2         | 0.82%   |
| Qualcomm                          | 2         | 0.82%   |
| Mellanox Technologies             | 2         | 0.82%   |
| Fibocom                           | 2         | 0.82%   |
| Ericsson Business Mobile Networks | 2         | 0.82%   |
| VIA Technologies                  | 1         | 0.41%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.41%   |
| Samsung Electronics               | 1         | 0.41%   |
| Nvidia                            | 1         | 0.41%   |
| Microchip Technology              | 1         | 0.41%   |
| JMicron Technology                | 1         | 0.41%   |
| Edimax Technology                 | 1         | 0.41%   |
| Dell                              | 1         | 0.41%   |
| D-Link System                     | 1         | 0.41%   |
| Brooktrout Technology             | 1         | 0.41%   |
| Atheros                           | 1         | 0.41%   |
| Apple                             | 1         | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45        | 14.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 4.13%   |
| Intel Wireless 7260                                               | 11        | 3.49%   |
| Intel Wireless 8265 / 8275                                        | 10        | 3.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 3.17%   |
| Intel Wireless 8260                                               | 7         | 2.22%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 2.22%   |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 2.22%   |
| Intel Wireless 3165                                               | 6         | 1.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5         | 1.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.59%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 1.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.27%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.27%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 4         | 1.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.95%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 0.95%   |
| Intel Wireless 7265                                               | 3         | 0.95%   |
| Intel WiFi Link 5100                                              | 3         | 0.95%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 0.95%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.95%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 0.95%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 0.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.63%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 2         | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.63%   |
| Qualcomm ALCATEL RNDIS Interface                                  | 2         | 0.63%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 2         | 0.63%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.63%   |
| Intel Wireless-AC 9260                                            | 2         | 0.63%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 2         | 0.63%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 72        | 50%     |
| Realtek Semiconductor | 25        | 17.36%  |
| Qualcomm Atheros      | 25        | 17.36%  |
| Broadcom              | 11        | 7.64%   |
| Ralink                | 3         | 2.08%   |
| TP-Link               | 2         | 1.39%   |
| Ralink Technology     | 2         | 1.39%   |
| Sierra Wireless       | 1         | 0.69%   |
| Edimax Technology     | 1         | 0.69%   |
| D-Link System         | 1         | 0.69%   |
| Atheros               | 1         | 0.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 11        | 7.48%   |
| Intel Wireless 8265 / 8275                                     | 10        | 6.8%    |
| Intel Wireless 8260                                            | 7         | 4.76%   |
| Intel Wireless 3165                                            | 6         | 4.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 5         | 3.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 3.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 3.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 2.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 2.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 2.72%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 4         | 2.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 2.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 2.04%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 2.04%   |
| Intel Wireless 7265                                            | 3         | 2.04%   |
| Intel WiFi Link 5100                                           | 3         | 2.04%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 2.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 2.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.36%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 2         | 1.36%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.36%   |
| Intel Wireless-AC 9260                                         | 2         | 1.36%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 2         | 1.36%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.36%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.36%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.36%   |
| TP-Link Wireless USB Adapter                                   | 1         | 0.68%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.68%   |
| Sierra Wireless EM7455                                         | 1         | 0.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.68%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.68%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1         | 0.68%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.68%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller             | 1         | 0.68%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 0.68%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.68%   |
| Realtek Realtek Bluetooth 4.2 Adapter                          | 1         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 64        | 41.56%  |
| Realtek Semiconductor            | 62        | 40.26%  |
| Broadcom                         | 9         | 5.84%   |
| Qualcomm Atheros                 | 8         | 5.19%   |
| Marvell Technology Group         | 3         | 1.95%   |
| Qualcomm                         | 2         | 1.3%    |
| VIA Technologies                 | 1         | 0.65%   |
| Silicon Integrated Systems [SiS] | 1         | 0.65%   |
| Samsung Electronics              | 1         | 0.65%   |
| Nvidia                           | 1         | 0.65%   |
| JMicron Technology               | 1         | 0.65%   |
| Apple                            | 1         | 0.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45        | 28.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 8.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 6.33%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 4.43%   |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 4.43%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 3.16%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 2.53%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.9%    |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.9%    |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 1.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.27%   |
| Qualcomm ALCATEL RNDIS Interface                                  | 2         | 1.27%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 1.27%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.27%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.27%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.27%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.27%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.27%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.27%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.27%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 1.27%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.63%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.63%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.63%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.63%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.63%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.63%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.63%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.63%   |
| Nvidia MCP73 Ethernet                                             | 1         | 0.63%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.63%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.63%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1         | 0.63%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.63%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.63%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.63%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 150       | 50.85%  |
| WiFi     | 135       | 45.76%  |
| Unknown  | 9         | 3.05%   |
| Modem    | 1         | 0.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 135       | 57.94%  |
| WiFi     | 93        | 39.91%  |
| Unknown  | 5         | 2.15%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 114       | 68.26%  |
| 1     | 48        | 28.74%  |
| 4     | 2         | 1.2%    |
| 3     | 2         | 1.2%    |
| 0     | 1         | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 152       | 91.02%  |
| Yes  | 15        | 8.98%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 47        | 47.47%  |
| Realtek Semiconductor           | 9         | 9.09%   |
| Broadcom                        | 9         | 9.09%   |
| Qualcomm Atheros Communications | 7         | 7.07%   |
| Lite-On Technology              | 5         | 5.05%   |
| ASUSTek Computer                | 5         | 5.05%   |
| Apple                           | 5         | 5.05%   |
| IMC Networks                    | 4         | 4.04%   |
| Cambridge Silicon Radio         | 3         | 3.03%   |
| Foxconn / Hon Hai               | 2         | 2.02%   |
| Hewlett-Packard                 | 1         | 1.01%   |
| Dell                            | 1         | 1.01%   |
| Alps Electric                   | 1         | 1.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 30        | 30.3%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5         | 5.05%   |
| Intel AX201 Bluetooth                                       | 5         | 5.05%   |
| Intel AX200 Bluetooth                                       | 3         | 3.03%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 3.03%   |
| Apple Bluetooth Host Controller                             | 3         | 3.03%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 2.02%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 2.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 2.02%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 2.02%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 2.02%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 2.02%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 2.02%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 2.02%   |
| ASUS BT-253 Bluetooth Adapter                               | 2         | 2.02%   |
| Apple Broadcom Built-in Bluetooth                           | 2         | 2.02%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 1.01%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 1.01%   |
| Realtek Bluetooth 4.2 Adapter                               | 1         | 1.01%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 1.01%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 1.01%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1         | 1.01%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.01%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.01%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device        | 1         | 1.01%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 1.01%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.01%   |
| Lite-On Bluetooth USB Module                                | 1         | 1.01%   |
| Lite-On Atheros Bluetooth                                   | 1         | 1.01%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.01%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 1.01%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 1.01%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 1.01%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.01%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 1.01%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 1.01%   |
| Dell DW375 Bluetooth Module                                 | 1         | 1.01%   |
| Broadcom Bluetooth 4.0                                      | 1         | 1.01%   |
| Broadcom Bluetooth 2.1 Device                               | 1         | 1.01%   |
| Broadcom BCM43142A0 Bluetooth Device                        | 1         | 1.01%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 131       | 61.79%  |
| AMD                              | 40        | 18.87%  |
| Nvidia                           | 22        | 10.38%  |
| XMOS                             | 2         | 0.94%   |
| Sony                             | 2         | 0.94%   |
| Corsair                          | 2         | 0.94%   |
| C-Media Electronics              | 2         | 0.94%   |
| VIA Technologies                 | 1         | 0.47%   |
| Tenx Technology                  | 1         | 0.47%   |
| Silicon Integrated Systems [SiS] | 1         | 0.47%   |
| Realtek Semiconductor            | 1         | 0.47%   |
| Quanta                           | 1         | 0.47%   |
| LG Electronics                   | 1         | 0.47%   |
| Creative Technology              | 1         | 0.47%   |
| Creative Labs                    | 1         | 0.47%   |
| Blue Microphones                 | 1         | 0.47%   |
| BEHRINGER International          | 1         | 0.47%   |
| Audio-Technica                   | 1         | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 25        | 9.54%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 15        | 5.73%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 3.82%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 3.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 3.82%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 3.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 3.82%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 3.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 3.44%   |
| AMD FCH Azalia Controller                                                                         | 8         | 3.05%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 2.29%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 2.29%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.91%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.91%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 1.53%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.53%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.53%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.53%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 1.53%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.53%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.53%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 1.15%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3         | 1.15%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 1.15%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 3         | 1.15%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.15%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 0.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.76%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 0.76%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.76%   |
| Corsair VOID PRO Wireless Gaming Headset                                                          | 2         | 0.76%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.76%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.76%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.76%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 0.76%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 51        | 26.15%  |
| SK hynix            | 38        | 19.49%  |
| Micron Technology   | 22        | 11.28%  |
| Kingston            | 18        | 9.23%   |
| Unknown             | 17        | 8.72%   |
| G.Skill             | 8         | 4.1%    |
| Crucial             | 8         | 4.1%    |
| Corsair             | 7         | 3.59%   |
| Elpida              | 6         | 3.08%   |
| Nanya Technology    | 4         | 2.05%   |
| Unknown             | 4         | 2.05%   |
| Transcend           | 2         | 1.03%   |
| Ramaxel Technology  | 2         | 1.03%   |
| A-DATA Technology   | 2         | 1.03%   |
| 48spaces            | 2         | 1.03%   |
| Unknown (ABCD)      | 1         | 0.51%   |
| Unknown (09D5)      | 1         | 0.51%   |
| Magnum Tech         | 1         | 0.51%   |
| EVGA                | 1         | 0.51%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 7         | 3.33%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 5         | 2.38%   |
| Unknown                                                                   | 4         | 1.9%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 3         | 1.43%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 1.43%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 3         | 1.43%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 3         | 1.43%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 3         | 1.43%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 3         | 1.43%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                  | 2         | 0.95%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 2         | 0.95%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 2         | 0.95%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 2         | 0.95%   |
| Samsung RAM M471B5273DH0-CK0 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.95%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.95%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.95%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                     | 2         | 0.95%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 0.95%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                             | 2         | 0.95%   |
| Micron RAM ITC 4GB DIMM DDR3 1066MT/s                                     | 2         | 0.95%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s                     | 2         | 0.95%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s                       | 2         | 0.95%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 2         | 0.95%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                                 | 1         | 0.48%   |
| Unknown SODIMM 1024MB SODIMM DDR2 667MT/s                                 | 1         | 0.48%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                                 | 1         | 0.48%   |
| Unknown RAM Module 512MB SODIMM SDRAM                                     | 1         | 0.48%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                            | 1         | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 1         | 0.48%   |
| Unknown RAM Module 2GB DIMM SDRAM                                         | 1         | 0.48%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                                  | 1         | 0.48%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                                    | 1         | 0.48%   |
| Unknown RAM Module 1GB SODIMM DRAM 533MT/s                                | 1         | 0.48%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 1         | 0.48%   |
| Unknown RAM Module 128MB SODIMM SDRAM                                     | 1         | 0.48%   |
| Unknown RAM Module 1024MB SODIMM RAM                                      | 1         | 0.48%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s                               | 1         | 0.48%   |
| Unknown RAM 7TE39AA# 8GB DIMM DDR4 2667MT/s                               | 1         | 0.48%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2133MT/s          | 1         | 0.48%   |
| Unknown (09D5) RAM Module 16GB SODIMM DDR4 2400MT/s                       | 1         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 72        | 42.35%  |
| DDR4    | 60        | 35.29%  |
| DDR2    | 18        | 10.59%  |
| LPDDR3  | 7         | 4.12%   |
| SDRAM   | 4         | 2.35%   |
| Unknown | 4         | 2.35%   |
| DDR     | 2         | 1.18%   |
| RAM     | 1         | 0.59%   |
| LPDDR4  | 1         | 0.59%   |
| DRAM    | 1         | 0.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 112       | 66.67%  |
| DIMM         | 48        | 28.57%  |
| Row Of Chips | 3         | 1.79%   |
| Chip         | 3         | 1.79%   |
| Unknown      | 2         | 1.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 69        | 36.7%   |
| 8192  | 62        | 32.98%  |
| 2048  | 28        | 14.89%  |
| 16384 | 16        | 8.51%   |
| 1024  | 9         | 4.79%   |
| 32768 | 2         | 1.06%   |
| 512   | 1         | 0.53%   |
| 128   | 1         | 0.53%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 48        | 26.67%  |
| 2400    | 22        | 12.22%  |
| 2667    | 19        | 10.56%  |
| 3200    | 14        | 7.78%   |
| 1333    | 13        | 7.22%   |
| 2133    | 11        | 6.11%   |
| 1334    | 8         | 4.44%   |
| 800     | 8         | 4.44%   |
| 667     | 8         | 4.44%   |
| Unknown | 6         | 3.33%   |
| 1867    | 5         | 2.78%   |
| 1066    | 5         | 2.78%   |
| 3600    | 3         | 1.67%   |
| 533     | 3         | 1.67%   |
| 1866    | 2         | 1.11%   |
| 1067    | 2         | 1.11%   |
| 3000    | 1         | 0.56%   |
| 2933    | 1         | 0.56%   |
| 975     | 1         | 0.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 33.33%  |
| Dymo-CoStar     | 1         | 33.33%  |
| Apple           | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HP PNP Fax Null                                                          | 1         | 25%     |
| HP HP LaserJet M101-M106 Printer HP LEDM HP LEDM IPP Printer IPP Printer | 1         | 25%     |
| Dymo-CoStar DYMO LabelWriter 450 DUO                                     | 1         | 25%     |
| Apple Gamesir-G3s 2.10                                                   | 1         | 25%     |

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
| Chicony Electronics                    | 27        | 28.13%  |
| Realtek Semiconductor                  | 11        | 11.46%  |
| Bison Electronics                      | 11        | 11.46%  |
| Suyin                                  | 7         | 7.29%   |
| Sunplus Innovation Technology          | 7         | 7.29%   |
| Microdia                               | 5         | 5.21%   |
| IMC Networks                           | 5         | 5.21%   |
| Logitech                               | 4         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.17%   |
| Silicon Motion                         | 3         | 3.13%   |
| Quanta                                 | 3         | 3.13%   |
| Lite-On Technology                     | 3         | 3.13%   |
| Z-Star Microelectronics                | 1         | 1.04%   |
| Novatek Microelectronics               | 1         | 1.04%   |
| Intel                                  | 1         | 1.04%   |
| Genesys Logic                          | 1         | 1.04%   |
| Apple                                  | 1         | 1.04%   |
| Alcor Micro                            | 1         | 1.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 10        | 10.31%  |
| Bison Integrated Camera                             | 5         | 5.15%   |
| Sunplus Integrated_Webcam_HD                        | 3         | 3.09%   |
| Realtek Lenovo EasyCamera                           | 3         | 3.09%   |
| Chicony HD WebCam                                   | 3         | 3.09%   |
| Suyin Acer Crystal Eye webcam                       | 2         | 2.06%   |
| Realtek USB 2.0 PC Camera                           | 2         | 2.06%   |
| Realtek Integrated_Webcam_HD                        | 2         | 2.06%   |
| Quanta Realtek DMFT RGB                             | 2         | 2.06%   |
| Microdia Integrated_Webcam_HD                       | 2         | 2.06%   |
| Microdia Integrated Webcam                          | 2         | 2.06%   |
| IMC Networks EasyCamera                             | 2         | 2.06%   |
| Chicony FJ Camera                                   | 2         | 2.06%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 2         | 2.06%   |
| Bison SunplusIT Integrated Camera                   | 2         | 2.06%   |
| Z-Star Webcam                                       | 1         | 1.03%   |
| Suyin USB 2.0 UVC 1.3M WebCam                       | 1         | 1.03%   |
| Suyin Laptop_Integrated_Webcam_3M                   | 1         | 1.03%   |
| Suyin HD WebCam                                     | 1         | 1.03%   |
| Suyin HD Video WebCam                               | 1         | 1.03%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 1.03%   |
| Sunplus SPCA2650 AV Camera                          | 1         | 1.03%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 1.03%   |
| Sunplus Integrated Webcam                           | 1         | 1.03%   |
| Sunplus Asus Webcam                                 | 1         | 1.03%   |
| Silicon Motion WebCam SCX Series                    | 1         | 1.03%   |
| Silicon Motion Realtek USB 2.0 PC Camera            | 1         | 1.03%   |
| Silicon Motion 300k Pixel Camera                    | 1         | 1.03%   |
| Realtek USB2.0 VGA UVC WebCam                       | 1         | 1.03%   |
| Realtek USB Video Composite                         | 1         | 1.03%   |
| Realtek USB Camera                                  | 1         | 1.03%   |
| Realtek HD Webcam - Realtek                         | 1         | 1.03%   |
| Quanta Front camera                                 | 1         | 1.03%   |
| Novatek HP High Definition 2MP Webcam               | 1         | 1.03%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 1.03%   |
| Logitech Webcam C310                                | 1         | 1.03%   |
| Logitech Webcam C270                                | 1         | 1.03%   |
| Logitech HD Pro Webcam C920                         | 1         | 1.03%   |
| Logitech C505 HD Webcam                             | 1         | 1.03%   |
| Lite-On Realtek PC Camera                           | 1         | 1.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 12        | 46.15%  |
| Synaptics             | 6         | 23.08%  |
| Upek                  | 3         | 11.54%  |
| LighTuning Technology | 2         | 7.69%   |
| Elan Microelectronics | 1         | 3.85%   |
| Broadcom              | 1         | 3.85%   |
| AuthenTec             | 1         | 3.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 11.54%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 3         | 11.54%  |
| Validity Sensors Synaptics WBDI                                              | 3         | 11.54%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 3         | 11.54%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 3         | 11.54%  |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 7.69%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 2         | 7.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 3.85%   |
| LighTuning Fingerprint Reader                                                | 1         | 3.85%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 3.85%   |
| Elan Fingerprint Sensor                                                      | 1         | 3.85%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.85%   |
| AuthenTec AES1600                                                            | 1         | 3.85%   |
| Unknown                                                                      | 1         | 3.85%   |

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
| 1     | 60        | 35.29%  |
| 2     | 49        | 28.82%  |
| 0     | 26        | 15.29%  |
| 3     | 19        | 11.18%  |
| 4     | 10        | 5.88%   |
| 5     | 3         | 1.76%   |
| 7     | 2         | 1.18%   |
| 6     | 1         | 0.59%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 107       | 41.31%  |
| Net/wireless             | 43        | 16.6%   |
| Bluetooth                | 30        | 11.58%  |
| Fingerprint reader       | 26        | 10.04%  |
| Firewire controller      | 23        | 8.88%   |
| Card reader              | 19        | 7.34%   |
| Network                  | 6         | 2.32%   |
| Sound                    | 4         | 1.54%   |
| Storage/raid             | 1         | 0.39%   |

