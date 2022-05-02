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

Total: 188

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Dell          | Latitude 5290               | Notebook    | [11c3db8f1b](https://bsd-hardware.info/?probe=11c3db8f1b) | Apr 23, 2022 |
| Notebook      | W650DC,DD                   | Notebook    | [0f474b9ebb](https://bsd-hardware.info/?probe=0f474b9ebb) | Apr 23, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [c4f7b8a774](https://bsd-hardware.info/?probe=c4f7b8a774) | Apr 22, 2022 |
| Dell          | Studio 1555                 | Notebook    | [6da8f97bcd](https://bsd-hardware.info/?probe=6da8f97bcd) | Apr 22, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [c776760a11](https://bsd-hardware.info/?probe=c776760a11) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490s 20NX000DR... | Notebook    | [c052d7cab0](https://bsd-hardware.info/?probe=c052d7cab0) | Apr 01, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [95646c7b48](https://bsd-hardware.info/?probe=95646c7b48) | Mar 25, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [94f78425f1](https://bsd-hardware.info/?probe=94f78425f1) | Mar 25, 2022 |
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
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | Convertible | [2d874470d0](https://bsd-hardware.info/?probe=2d874470d0) | Jun 01, 2021 |
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
| Dell          | 0C27VV A02                  | Desktop     | [c532e18070](https://bsd-hardware.info/?probe=c532e18070) | Jan 04, 2021 |
| Dell          | 0C27VV A02                  | Desktop     | [876f5d7b92](https://bsd-hardware.info/?probe=876f5d7b92) | Jan 02, 2021 |
| Dell          | 0C27VV A02                  | Desktop     | [0bf1fa2725](https://bsd-hardware.info/?probe=0bf1fa2725) | Jan 02, 2021 |
| Dell          | 0C27VV A02                  | Desktop     | [87e4734cb8](https://bsd-hardware.info/?probe=87e4734cb8) | Dec 30, 2020 |
| Dell          | 0C27VV A02                  | Desktop     | [d892bd7805](https://bsd-hardware.info/?probe=d892bd7805) | Dec 30, 2020 |
| Dell          | 0C27VV A02                  | Desktop     | [917e6fde25](https://bsd-hardware.info/?probe=917e6fde25) | Dec 30, 2020 |
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

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| NomadBSD 1.3.2    | 52        | 36.62%  |
| NomadBSD 5806f915 | 45        | 31.69%  |
| NomadBSD 1.4      | 23        | 16.2%   |
| NomadBSD 1.4-RC1  | 10        | 7.04%   |
| NomadBSD 1.3.1    | 10        | 7.04%   |
| NomadBSD 1.3      | 1         | 0.7%    |
| NomadBSD 1.0      | 1         | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| NomadBSD | 137       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 130       | 94.2%   |
| i386  | 8         | 5.8%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Openbox       | 124       | 89.86%  |
| GNOME         | 7         | 5.07%   |
| KDE5          | 3         | 2.17%   |
| XFCE          | 1         | 0.72%   |
| GNUstep       | 1         | 0.72%   |
| filer         | 1         | 0.72%   |
| Enlightenment | 1         | 0.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 137       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 135       | 98.54%  |
| SDDM | 2         | 1.46%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 52        | 37.41%  |
| Unknown | 26        | 18.71%  |
| de_DE   | 14        | 10.07%  |
| ru_RU   | 7         | 5.04%   |
| en_GB   | 7         | 5.04%   |
| it_IT   | 5         | 3.6%    |
| hu_HU   | 5         | 3.6%    |
| zh_CN   | 3         | 2.16%   |
| tr_TR   | 3         | 2.16%   |
| es_ES   | 3         | 2.16%   |
| pt_BR   | 2         | 1.44%   |
| pl_PL   | 2         | 1.44%   |
| fr_FR   | 2         | 1.44%   |
| en_AU   | 2         | 1.44%   |
| cs_CZ   | 2         | 1.44%   |
| ko_KR   | 1         | 0.72%   |
| fi_FI   | 1         | 0.72%   |
| et_EE   | 1         | 0.72%   |
| bg_BG   | 1         | 0.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 131       | 94.93%  |
| BIOS | 7         | 5.07%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ufs  | 123       | 89.78%  |
| Zfs  | 14        | 10.22%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 97        | 70.29%  |
| MBR  | 41        | 29.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 23        | 16.79%  |
| Dell                | 21        | 15.33%  |
| Hewlett-Packard     | 20        | 14.6%   |
| ASUSTek Computer    | 20        | 14.6%   |
| Acer                | 9         | 6.57%   |
| Gigabyte Technology | 6         | 4.38%   |
| ASRock              | 4         | 2.92%   |
| Apple               | 4         | 2.92%   |
| Sony                | 3         | 2.19%   |
| Intel               | 3         | 2.19%   |
| Samsung Electronics | 2         | 1.46%   |
| Pegatron            | 2         | 1.46%   |
| Notebook            | 2         | 1.46%   |
| Google              | 2         | 1.46%   |
| Fujitsu             | 2         | 1.46%   |
| Unknown             | 2         | 1.46%   |
| TUXEDO              | 1         | 0.73%   |
| Toshiba             | 1         | 0.73%   |
| Semp Toshiba        | 1         | 0.73%   |
| Panasonic           | 1         | 0.73%   |
| NEC Computers       | 1         | 0.73%   |
| MSI                 | 1         | 0.73%   |
| IBM                 | 1         | 0.73%   |
| GEO                 | 1         | 0.73%   |
| Fujitsu Siemens     | 1         | 0.73%   |
| Foxconn             | 1         | 0.73%   |
| Clevo               | 1         | 0.73%   |
| Alienware           | 1         | 0.73%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Unknown                                   | 3         | 2.19%   |
| Acer Veriton M460                         | 2         | 1.46%   |
| Toshiba Satellite C660                    | 1         | 0.73%   |
| Sony VPCM13M1R                            | 1         | 0.73%   |
| Sony VJS121C11N                           | 1         | 0.73%   |
| Sony SVE1713S1RW                          | 1         | 0.73%   |
| Semp Toshiba STI                          | 1         | 0.73%   |
| Samsung N145P/N250P/N260P                 | 1         | 0.73%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV   | 1         | 0.73%   |
| Pegatron T12Ah                            | 1         | 0.73%   |
| Pegatron Elite 7300 Series MT             | 1         | 0.73%   |
| Panasonic CF-C1BD06EFG                    | 1         | 0.73%   |
| Notebook W650DC,DD                        | 1         | 0.73%   |
| Notebook N650DU                           | 1         | 0.73%   |
| NEC Computers PC-GL186Y3AZ                | 1         | 0.73%   |
| MSI MS-N033                               | 1         | 0.73%   |
| Lenovo ThinkPad X380 Yoga 20LJ000WUK      | 1         | 0.73%   |
| Lenovo ThinkPad X201 Tablet 311396U       | 1         | 0.73%   |
| Lenovo ThinkPad X13 Yoga Gen 1 20SYS22H00 | 1         | 0.73%   |
| Lenovo ThinkPad X1 Yoga 3rd 20LDS1CG00    | 1         | 0.73%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB001XAU  | 1         | 0.73%   |
| Lenovo ThinkPad W541 20EGS04800           | 1         | 0.73%   |
| Lenovo ThinkPad T530 24295VU              | 1         | 0.73%   |
| Lenovo ThinkPad T510 4384FF3              | 1         | 0.73%   |
| Lenovo ThinkPad T490s 20NX000DRT          | 1         | 0.73%   |
| Lenovo ThinkPad T490 20RYS06R00           | 1         | 0.73%   |
| Lenovo ThinkPad T470s W10DG 20JS001FGE    | 1         | 0.73%   |
| Lenovo ThinkPad T460 20FMS78014           | 1         | 0.73%   |
| Lenovo ThinkPad T450 20BUS06B00           | 1         | 0.73%   |
| Lenovo ThinkPad T440s 20AQ006HUS          | 1         | 0.73%   |
| Lenovo ThinkPad T440p 20AWS0VK00          | 1         | 0.73%   |
| Lenovo ThinkPad T430 2347C32              | 1         | 0.73%   |
| Lenovo ThinkPad S1 Yoga 20C0S0M300        | 1         | 0.73%   |
| Lenovo ThinkCentre M93p 10A8001HUS        | 1         | 0.73%   |
| Lenovo Legion Y7000 2019 PG0 81T0         | 1         | 0.73%   |
| Lenovo IdeaPad S145-15API 81UT            | 1         | 0.73%   |
| Lenovo IdeaPad 110-15IBR 80T7             | 1         | 0.73%   |
| Lenovo G570 20079                         | 1         | 0.73%   |
| Lenovo G50-45 80E3                        | 1         | 0.73%   |
| Intel NUC6i5SYB H81131-502                | 1         | 0.73%   |
| Intel NUC5i3RYB H41000-507                | 1         | 0.73%   |
| Intel DCP847SKE                           | 1         | 0.73%   |
| IBM 2647NG8                               | 1         | 0.73%   |
| HP ZBook Studio G3                        | 1         | 0.73%   |
| HP Z620 Workstation                       | 1         | 0.73%   |
| HP Spectre x360 Convertible 13-w0XX       | 1         | 0.73%   |
| HP ProBook x360 11 G6 EE                  | 1         | 0.73%   |
| HP ProBook 640 G1                         | 1         | 0.73%   |
| HP ProBook 450 G2                         | 1         | 0.73%   |
| HP Pavilion Notebook                      | 1         | 0.73%   |
| HP Pavilion g6                            | 1         | 0.73%   |
| HP Pavilion dv6000 (RP981EA#AB8)          | 1         | 0.73%   |
| HP OMEN by HP Laptop 17-cb1xxx            | 1         | 0.73%   |
| HP Notebook                               | 1         | 0.73%   |
| HP Laptop 15-db0xxx                       | 1         | 0.73%   |
| HP Laptop 15-da0xxx                       | 1         | 0.73%   |
| HP EliteBook 820 G1                       | 1         | 0.73%   |
| HP Desktop M01-F1xxx                      | 1         | 0.73%   |
| HP Compaq Elite 8300 Touch All-in-One PC  | 1         | 0.73%   |
| HP Compaq dc7900 Convertible Minitower    | 1         | 0.73%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 17        | 12.41%  |
| Dell Latitude              | 8         | 5.84%   |
| Acer Aspire                | 7         | 5.11%   |
| Dell OptiPlex              | 5         | 3.65%   |
| HP Compaq                  | 4         | 2.92%   |
| HP ProBook                 | 3         | 2.19%   |
| HP Pavilion                | 3         | 2.19%   |
| Dell Studio                | 3         | 2.19%   |
| Dell Inspiron              | 3         | 2.19%   |
| Unknown                    | 3         | 2.19%   |
| Lenovo IdeaPad             | 2         | 1.46%   |
| HP Laptop                  | 2         | 1.46%   |
| Gigabyte Z370              | 2         | 1.46%   |
| Gigabyte X570              | 2         | 1.46%   |
| Fujitsu LIFEBOOK           | 2         | 1.46%   |
| ASUS TUF                   | 2         | 1.46%   |
| ASUS PRIME                 | 2         | 1.46%   |
| Acer Veriton               | 2         | 1.46%   |
| Toshiba Satellite          | 1         | 0.73%   |
| Sony VPCM13M1R             | 1         | 0.73%   |
| Sony VJS121C11N            | 1         | 0.73%   |
| Sony SVE1713S1RW           | 1         | 0.73%   |
| Semp Toshiba STI           | 1         | 0.73%   |
| Samsung N145P              | 1         | 0.73%   |
| Samsung 300E5EV            | 1         | 0.73%   |
| Pegatron T12Ah             | 1         | 0.73%   |
| Pegatron Elite             | 1         | 0.73%   |
| Panasonic CF-C1BD06EFG     | 1         | 0.73%   |
| Notebook W650DC            | 1         | 0.73%   |
| Notebook N650DU            | 1         | 0.73%   |
| NEC Computers PC-GL186Y3AZ | 1         | 0.73%   |
| MSI MS-N033                | 1         | 0.73%   |
| Lenovo ThinkCentre         | 1         | 0.73%   |
| Lenovo Legion              | 1         | 0.73%   |
| Lenovo G570                | 1         | 0.73%   |
| Lenovo G50-45              | 1         | 0.73%   |
| Intel NUC6i5SYB            | 1         | 0.73%   |
| Intel NUC5i3RYB            | 1         | 0.73%   |
| Intel DCP847SKE            | 1         | 0.73%   |
| IBM 2647NG8                | 1         | 0.73%   |
| HP ZBook                   | 1         | 0.73%   |
| HP Z620                    | 1         | 0.73%   |
| HP Spectre                 | 1         | 0.73%   |
| HP OMEN                    | 1         | 0.73%   |
| HP Notebook                | 1         | 0.73%   |
| HP EliteBook               | 1         | 0.73%   |
| HP Desktop                 | 1         | 0.73%   |
| HP 2000                    | 1         | 0.73%   |
| Google Lulu                | 1         | 0.73%   |
| Google Chell               | 1         | 0.73%   |
| Gigabyte X570S             | 1         | 0.73%   |
| Gigabyte MZGLKBP-00        | 1         | 0.73%   |
| GEO GeoBook3               | 1         | 0.73%   |
| Fujitsu Siemens AMILO      | 1         | 0.73%   |
| Foxconn Napa               | 1         | 0.73%   |
| Dell Vostro                | 1         | 0.73%   |
| Dell Precision             | 1         | 0.73%   |
| Clevo W55xEU               | 1         | 0.73%   |
| ASUS Z170-A                | 1         | 0.73%   |
| ASUS X751LN                | 1         | 0.73%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 19        | 13.87%  |
| 2020 | 17        | 12.41%  |
| 2017 | 14        | 10.22%  |
| 2015 | 10        | 7.3%    |
| 2010 | 8         | 5.84%   |
| 2009 | 8         | 5.84%   |
| 2021 | 7         | 5.11%   |
| 2018 | 7         | 5.11%   |
| 2016 | 7         | 5.11%   |
| 2014 | 7         | 5.11%   |
| 2012 | 7         | 5.11%   |
| 2011 | 7         | 5.11%   |
| 2008 | 7         | 5.11%   |
| 2013 | 6         | 4.38%   |
| 2006 | 3         | 2.19%   |
| 2022 | 1         | 0.73%   |
| 2007 | 1         | 0.73%   |
| 2004 | 1         | 0.73%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 88        | 64.23%  |
| Desktop     | 40        | 29.2%   |
| Convertible | 5         | 3.65%   |
| Mini pc     | 2         | 1.46%   |
| All in one  | 2         | 1.46%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 135       | 98.54%  |
| Yes  | 2         | 1.46%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 54        | 39.13%  |
| 4.01-8.0    | 33        | 23.91%  |
| 16.01-24.0  | 27        | 19.57%  |
| 32.01-64.0  | 10        | 7.25%   |
| 2.01-3.0    | 4         | 2.9%    |
| 3.01-4.0    | 3         | 2.17%   |
| 64.01-256.0 | 3         | 2.17%   |
| 0.51-1.0    | 3         | 2.17%   |
| 24.01-32.0  | 1         | 0.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 75        | 53.57%  |
| 0.51-1.0  | 41        | 29.29%  |
| 1.01-2.0  | 15        | 10.71%  |
| 2.01-3.0  | 5         | 3.57%   |
| 4.01-8.0  | 2         | 1.43%   |
| 3.01-4.0  | 1         | 0.71%   |
| 8.01-16.0 | 1         | 0.71%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 92        | 66.67%  |
| 2      | 26        | 18.84%  |
| 3      | 10        | 7.25%   |
| 0      | 7         | 5.07%   |
| 4      | 2         | 1.45%   |
| 7      | 1         | 0.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 80        | 57.97%  |
| Yes       | 58        | 42.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 126       | 91.3%   |
| No        | 12        | 8.7%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 82.48%  |
| No        | 24        | 17.52%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 57.25%  |
| No        | 59        | 42.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 29        | 21.17%  |
| Germany     | 17        | 12.41%  |
| Russia      | 15        | 10.95%  |
| France      | 14        | 10.22%  |
| UK          | 7         | 5.11%   |
| Italy       | 7         | 5.11%   |
| Turkey      | 5         | 3.65%   |
| Hungary     | 5         | 3.65%   |
| Mexico      | 3         | 2.19%   |
| Colombia    | 3         | 2.19%   |
| China       | 3         | 2.19%   |
| Romania     | 2         | 1.46%   |
| Poland      | 2         | 1.46%   |
| Norway      | 2         | 1.46%   |
| Japan       | 2         | 1.46%   |
| Czechia     | 2         | 1.46%   |
| Brazil      | 2         | 1.46%   |
| Australia   | 2         | 1.46%   |
| Argentina   | 2         | 1.46%   |
| Ukraine     | 1         | 0.73%   |
| Thailand    | 1         | 0.73%   |
| Spain       | 1         | 0.73%   |
| South Korea | 1         | 0.73%   |
| Slovakia    | 1         | 0.73%   |
| Serbia      | 1         | 0.73%   |
| Philippines | 1         | 0.73%   |
| Hong Kong   | 1         | 0.73%   |
| Finland     | 1         | 0.73%   |
| Estonia     | 1         | 0.73%   |
| Denmark     | 1         | 0.73%   |
| Bulgaria    | 1         | 0.73%   |
| Belarus     | 1         | 0.73%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Moscow                | 9         | 6.47%   |
| Franconville          | 6         | 4.32%   |
| Paris                 | 5         | 3.6%    |
| Hodmezovasarhely      | 5         | 3.6%    |
| Istanbul              | 4         | 2.88%   |
| Woodland              | 3         | 2.16%   |
| Whittier              | 3         | 2.16%   |
| Tijuana               | 3         | 2.16%   |
| Milan                 | 3         | 2.16%   |
| Markt Indersdorf      | 3         | 2.16%   |
| Zwingenberg           | 2         | 1.44%   |
| Volzhskiy             | 2         | 1.44%   |
| St Petersburg         | 2         | 1.44%   |
| Setagaya-ku           | 2         | 1.44%   |
| Rome                  | 2         | 1.44%   |
| Rio de Janeiro        | 2         | 1.44%   |
| New Braunfels         | 2         | 1.44%   |
| McDonough             | 2         | 1.44%   |
| Los Angeles           | 2         | 1.44%   |
| Greenwich             | 2         | 1.44%   |
| Drobeta-Turnu Severin | 2         | 1.44%   |
| Cologne               | 2         | 1.44%   |
| Changzhou             | 2         | 1.44%   |
| Brisbane              | 2         | 1.44%   |
| BogotГЎ             | 2         | 1.44%   |
| Wloszczowa            | 1         | 0.72%   |
| Wissen                | 1         | 0.72%   |
| Winter Haven          | 1         | 0.72%   |
| Wilhelmshaven         | 1         | 0.72%   |
| Warsaw                | 1         | 0.72%   |
| Vollen                | 1         | 0.72%   |
| Vladimir              | 1         | 0.72%   |
| Vertou                | 1         | 0.72%   |
| Tucson                | 1         | 0.72%   |
| Trieste               | 1         | 0.72%   |
| Tallinn               | 1         | 0.72%   |
| Syracuse              | 1         | 0.72%   |
| Swindon               | 1         | 0.72%   |
| Suwon                 | 1         | 0.72%   |
| Southampton           | 1         | 0.72%   |
| Sofia                 | 1         | 0.72%   |
| Shanghai              | 1         | 0.72%   |
| Sedavi                | 1         | 0.72%   |
| Scottsdale            | 1         | 0.72%   |
| San Francisco         | 1         | 0.72%   |
| San Bernardino        | 1         | 0.72%   |
| Saint-Denis           | 1         | 0.72%   |
| Rionegro              | 1         | 0.72%   |
| Peoria                | 1         | 0.72%   |
| Pasig                 | 1         | 0.72%   |
| Palmer                | 1         | 0.72%   |
| Palm Bay              | 1         | 0.72%   |
| Oslo                  | 1         | 0.72%   |
| Nueve de Julio        | 1         | 0.72%   |
| Novosibirsk           | 1         | 0.72%   |
| Niederlauer           | 1         | 0.72%   |
| Munich                | 1         | 0.72%   |
| Mogilev               | 1         | 0.72%   |
| Melcice               | 1         | 0.72%   |
| Marburg               | 1         | 0.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 40     | 18.75%  |
| WDC                 | 30        | 37     | 17.05%  |
| Seagate             | 26        | 29     | 14.77%  |
| Toshiba             | 18        | 20     | 10.23%  |
| Crucial             | 7         | 7      | 3.98%   |
| SanDisk             | 6         | 7      | 3.41%   |
| Kingston            | 6         | 6      | 3.41%   |
| Intel               | 5         | 5      | 2.84%   |
| Hitachi             | 5         | 5      | 2.84%   |
| Apple               | 5         | 6      | 2.84%   |
| A-DATA Technology   | 5         | 5      | 2.84%   |
| SK Hynix            | 4         | 5      | 2.27%   |
| Transcend           | 2         | 2      | 1.14%   |
| PNY                 | 2         | 2      | 1.14%   |
| OCZ                 | 2         | 2      | 1.14%   |
| Micron Technology   | 2         | 2      | 1.14%   |
| Intenso             | 2         | 2      | 1.14%   |
| HGST                | 2         | 2      | 1.14%   |
| Hewlett-Packard     | 2         | 2      | 1.14%   |
| Gigabyte Technology | 2         | 2      | 1.14%   |
| Fujitsu             | 2         | 3      | 1.14%   |
| Team                | 1         | 1      | 0.57%   |
| SPCC                | 1         | 1      | 0.57%   |
| ORICO               | 1         | 1      | 0.57%   |
| MAXTOR              | 1         | 1      | 0.57%   |
| LITEONIT            | 1         | 1      | 0.57%   |
| KingDian            | 1         | 1      | 0.57%   |
| Corsair             | 1         | 1      | 0.57%   |
| ASUSTek Computer    | 1         | 2      | 0.57%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB               | 3         | 1.6%    |
| Seagate ST1000LM049-2GH172 1TB       | 3         | 1.6%    |
| WDC WD1600AAJS-22L7A0 160GB          | 2         | 1.06%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB | 2         | 1.06%   |
| Toshiba MQ01ABF050 500GB             | 2         | 1.06%   |
| Toshiba HDWD120 2TB                  | 2         | 1.06%   |
| Seagate ST95005620AS 500GB           | 2         | 1.06%   |
| Seagate ST9500325AS 500GB            | 2         | 1.06%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 1.06%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.06%   |
| SanDisk SSD U100 24GB                | 2         | 1.06%   |
| SanDisk pSSD 256GB                   | 2         | 1.06%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 1.06%   |
| Samsung SSD 970 EVO 500GB            | 2         | 1.06%   |
| Samsung SSD 870 QVO 2TB              | 2         | 1.06%   |
| Samsung SSD 840 EVO 250GB            | 2         | 1.06%   |
| Samsung MZVLB256HBHQ-000L7 256GB     | 2         | 1.06%   |
| Kingston SA400S37480G 480GB          | 2         | 1.06%   |
| Kingston SA400S37240G 240GB          | 2         | 1.06%   |
| HGST HTS725050A7E630 500GB           | 2         | 1.06%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 1.06%   |
| Crucial CT1000P1SSD8 1TB             | 2         | 1.06%   |
| Apple SSD SM0512F 500GB              | 2         | 1.06%   |
| A-DATA SU630 240GB                   | 2         | 1.06%   |
| WDC WDS240G2G0B-00EPW0 240GB         | 1         | 0.53%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 0.53%   |
| WDC WDS120G2G0B-00EPW0 120GB         | 1         | 0.53%   |
| WDC WDS120G2G0A-00JH30 120GB         | 1         | 0.53%   |
| WDC WDS120G1G0A-00SS50 120GB         | 1         | 0.53%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 1         | 0.53%   |
| WDC WD7500BPKT-75PK4T0 752GB         | 1         | 0.53%   |
| WDC WD6400AAKS-22A7B2 640GB          | 1         | 0.53%   |
| WDC WD40PURX-64GVNY0 4TB             | 1         | 0.53%   |
| WDC WD40NMZW-11GX6S1 4TB             | 1         | 0.53%   |
| WDC WD3200BEVT-75ZCT2 320GB          | 1         | 0.53%   |
| WDC WD3200BEKT-60PVMT0 320GB         | 1         | 0.53%   |
| WDC WD2500LPCX-24C6HT0 250GB         | 1         | 0.53%   |
| WDC WD2500BEVT-80A23T0 250GB         | 1         | 0.53%   |
| WDC WD2500BEKT-00PVMT0 250GB         | 1         | 0.53%   |
| WDC WD2004FBYZ-01YCBB1 2TB           | 1         | 0.53%   |
| WDC WD1200BEVS-07LAT0 120GB          | 1         | 0.53%   |
| WDC WD1200BEVE-00UYT0 120GB          | 1         | 0.53%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.53%   |
| WDC WD10SPZX-00Z10T0 1TB             | 1         | 0.53%   |
| WDC WD10SMRW-11Y43S0 1TB             | 1         | 0.53%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.53%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 0.53%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.53%   |
| WDC WD10JPLX-00MBPT0 1TB             | 1         | 0.53%   |
| WDC WD10EZRZ-00HTKB0 1TB             | 1         | 0.53%   |
| WDC WD10EZRX-00L4HB0 1TB             | 1         | 0.53%   |
| WDC WD10EFRX-68PJCN0 1TB             | 1         | 0.53%   |
| WDC WD10EADS-00P8B0 1TB              | 1         | 0.53%   |
| WDC PC SN720 SDAPNTW-1T00-1006 1TB   | 1         | 0.53%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB | 1         | 0.53%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB | 1         | 0.53%   |
| Transcend TS512GSSD370S 512GB        | 1         | 0.53%   |
| Transcend TS32GCF800 32GB            | 1         | 0.53%   |
| Toshiba TR200 240GB                  | 1         | 0.53%   |
| Toshiba THNSNC128GBSJ                | 1         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 29     | 32.91%  |
| WDC                 | 23        | 26     | 29.11%  |
| Toshiba             | 14        | 15     | 17.72%  |
| Hitachi             | 5         | 5      | 6.33%   |
| Samsung Electronics | 4         | 4      | 5.06%   |
| HGST                | 2         | 2      | 2.53%   |
| Fujitsu             | 2         | 3      | 2.53%   |
| MAXTOR              | 1         | 1      | 1.27%   |
| Hewlett-Packard     | 1         | 1      | 1.27%   |
| Apple               | 1         | 1      | 1.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 19     | 22.06%  |
| SanDisk             | 6         | 7      | 8.82%   |
| Kingston            | 5         | 5      | 7.35%   |
| A-DATA Technology   | 5         | 5      | 7.35%   |
| WDC                 | 4         | 5      | 5.88%   |
| Crucial             | 4         | 4      | 5.88%   |
| Apple               | 4         | 5      | 5.88%   |
| Toshiba             | 3         | 3      | 4.41%   |
| Intel               | 3         | 3      | 4.41%   |
| Transcend           | 2         | 2      | 2.94%   |
| PNY                 | 2         | 2      | 2.94%   |
| OCZ                 | 2         | 2      | 2.94%   |
| Micron Technology   | 2         | 2      | 2.94%   |
| Intenso             | 2         | 2      | 2.94%   |
| Gigabyte Technology | 2         | 2      | 2.94%   |
| Team                | 1         | 1      | 1.47%   |
| SPCC                | 1         | 1      | 1.47%   |
| SK Hynix            | 1         | 1      | 1.47%   |
| LITEONIT            | 1         | 1      | 1.47%   |
| KingDian            | 1         | 1      | 1.47%   |
| Corsair             | 1         | 1      | 1.47%   |
| ASUSTek Computer    | 1         | 2      | 1.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 69        | 87     | 43.4%   |
| SSD  | 60        | 76     | 37.74%  |
| NVMe | 30        | 37     | 18.87%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 115       | 163    | 79.31%  |
| NVMe | 30        | 37     | 20.69%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 86        | 109    | 63.7%   |
| 0.51-1.0   | 36        | 41     | 26.67%  |
| 1.01-2.0   | 7         | 7      | 5.19%   |
| 3.01-4.0   | 3         | 3      | 2.22%   |
| 2.01-3.0   | 3         | 3      | 2.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 114       | 83.21%  |
| 101-250    | 12        | 8.76%   |
| 51-100     | 5         | 3.65%   |
| 251-500    | 2         | 1.46%   |
| 21-50      | 2         | 1.46%   |
| 501-1000   | 2         | 1.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 133       | 96.38%  |
| 21-50   | 3         | 2.17%   |
| 51-100  | 2         | 1.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPKT-75PK4T0 752GB                     | 1         | 1      | 3.57%   |
| WDC WD2500BEVT-80A23T0 250GB                     | 1         | 1      | 3.57%   |
| WDC WD1200BEVS-07LAT0 120GB                      | 1         | 1      | 3.57%   |
| WDC WD10JPVX-75JC3T0 1TB                         | 1         | 1      | 3.57%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 3.57%   |
| WDC WD10EFRX-68PJCN0 1TB                         | 1         | 2      | 3.57%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 3.57%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 3.57%   |
| Toshiba MK7575GSX 752GB                          | 1         | 1      | 3.57%   |
| Toshiba HDWD120 2TB                              | 1         | 1      | 3.57%   |
| Toshiba DT01ABA300 3TB                           | 1         | 1      | 3.57%   |
| Seagate ST95005620AS 500GB                       | 1         | 1      | 3.57%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 3.57%   |
| Seagate ST500LM021-1KJ152 500GB                  | 1         | 1      | 3.57%   |
| Seagate ST500DM002-1BD142 500GB                  | 1         | 1      | 3.57%   |
| Seagate ST3250823AS 250GB                        | 1         | 1      | 3.57%   |
| SanDisk SD9SN8W-128G-1006 128GB                  | 1         | 1      | 3.57%   |
| Samsung Electronics SSD PM810 2.5-inch 7mm 256GB | 1         | 1      | 3.57%   |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 3.57%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB       | 1         | 1      | 3.57%   |
| Intenso SSD Sata III 128GB                       | 1         | 1      | 3.57%   |
| Intel SSDSC2CW060A3 64GB                         | 1         | 1      | 3.57%   |
| Hitachi HTS545032B9A302 320GB                    | 1         | 1      | 3.57%   |
| Hitachi HTS545032B9A300 320GB                    | 1         | 1      | 3.57%   |
| HGST HTS725050A7E630 500GB                       | 1         | 1      | 3.57%   |
| Hewlett-Packard MB1000GCWCV 1TB                  | 1         | 1      | 3.57%   |
| Corsair Neutron GTX SSD 120GB                    | 1         | 1      | 3.57%   |
| A-DATA Technology XM13 32GB                      | 1         | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 7      | 21.43%  |
| Toshiba             | 5         | 5      | 17.86%  |
| Seagate             | 5         | 5      | 17.86%  |
| Samsung Electronics | 2         | 2      | 7.14%   |
| Hitachi             | 2         | 2      | 7.14%   |
| SanDisk             | 1         | 1      | 3.57%   |
| Micron Technology   | 1         | 1      | 3.57%   |
| Intenso             | 1         | 1      | 3.57%   |
| Intel               | 1         | 1      | 3.57%   |
| HGST                | 1         | 1      | 3.57%   |
| Hewlett-Packard     | 1         | 1      | 3.57%   |
| Corsair             | 1         | 1      | 3.57%   |
| A-DATA Technology   | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 7      | 28.57%  |
| Toshiba             | 5         | 5      | 23.81%  |
| Seagate             | 5         | 5      | 23.81%  |
| Hitachi             | 2         | 2      | 9.52%   |
| Samsung Electronics | 1         | 1      | 4.76%   |
| HGST                | 1         | 1      | 4.76%   |
| Hewlett-Packard     | 1         | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 22     | 74.07%  |
| SSD  | 7         | 7      | 25.93%  |

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

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 110       | 163    | 79.14%  |
| Malfunc  | 27        | 29     | 19.42%  |
| Detected | 2         | 8      | 1.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 101       | 60.48%  |
| AMD                              | 21        | 12.57%  |
| Samsung Electronics              | 19        | 11.38%  |
| Sandisk                          | 6         | 3.59%   |
| ASMedia Technology               | 5         | 2.99%   |
| Micron/Crucial Technology        | 3         | 1.8%    |
| VIA Technologies                 | 2         | 1.2%    |
| SK Hynix                         | 2         | 1.2%    |
| Nvidia                           | 2         | 1.2%    |
| Toshiba                          | 1         | 0.6%    |
| Silicon Motion                   | 1         | 0.6%    |
| Silicon Integrated Systems [SiS] | 1         | 0.6%    |
| Kingston Technology Company      | 1         | 0.6%    |
| JMicron Technology               | 1         | 0.6%    |
| Biwin Storage Technology         | 1         | 0.6%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 17        | 8.72%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 12        | 6.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 11        | 5.64%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 3.59%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 3.59%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 3.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 5         | 2.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 2.56%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 5         | 2.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 4         | 2.05%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 2.05%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 2.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.54%   |
| Intel SATA Controller [RAID mode]                                                | 3         | 1.54%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.54%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 1.54%   |
| Sandisk PC SN520 NVMe SSD                                                        | 2         | 1.03%   |
| Samsung SM951 AHCI                                                               | 2         | 1.03%   |
| Samsung Apple PCIe SSD                                                           | 2         | 1.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.03%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.03%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 2         | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.03%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 1.03%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 2         | 1.03%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 2         | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 1.03%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 2         | 1.03%   |
| AMD 400 Series Chipset SATA Controller                                           | 2         | 1.03%   |
| Unknown                                                                          | 2         | 1.03%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.51%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 0.51%   |
| VIA VT6421 IDE/SATA Controller                                                   | 1         | 0.51%   |
| Toshiba unknown                                                                  | 1         | 0.51%   |
| SK Hynix hynix unknown                                                           | 1         | 0.51%   |
| SK Hynix BC511                                                                   | 1         | 0.51%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.51%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.51%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.51%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.51%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.51%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.51%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.51%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.51%   |
| Nvidia MCP73 SATA Controller (IDE mode)                                          | 1         | 0.51%   |
| Nvidia MCP73 IDE Controller                                                      | 1         | 0.51%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 0.51%   |
| Nvidia MCP61 IDE                                                                 | 1         | 0.51%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1         | 0.51%   |
| Micron/Crucial NVMe Controller                                                   | 1         | 0.51%   |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 0.51%   |
| JMicron JMB360 AHCI Controller                                                   | 1         | 0.51%   |
| Intel SSD 660P Series                                                            | 1         | 0.51%   |
| Intel NVMe Optane Memory Series                                                  | 1         | 0.51%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 98        | 58.68%  |
| NVMe | 30        | 17.96%  |
| IDE  | 26        | 15.57%  |
| RAID | 12        | 7.19%   |
| SAS  | 1         | 0.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 116       | 84.06%  |
| AMD    | 22        | 15.94%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 2.9%    |
| Intel Core i7-4600U CPU @ 2.10GHz           | 3         | 2.17%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 2.17%   |
| Intel CPU Version                           | 2         | 1.45%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 2         | 1.45%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 1.45%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 2         | 1.45%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.45%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.45%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2         | 1.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.45%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 2         | 1.45%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 2         | 1.45%   |
| Intel Core 2 Duo                            | 2         | 1.45%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2         | 1.45%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 1.45%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1         | 0.72%   |
| Intel Xeon CPU E5-2670 @ 2.60GHz            | 1         | 0.72%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz        | 1         | 0.72%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1         | 0.72%   |
| Intel Pentium III                           | 1         | 0.72%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1         | 0.72%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1         | 0.72%   |
| Intel Pentium D CPU 2.80GHz                 | 1         | 0.72%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 0.72%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.72%   |
| Intel Pentium CPU 2117U @ 1.80GHz           | 1         | 0.72%   |
| Intel Genuine CPU U7300 @ 1.30GHz           | 1         | 0.72%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz            | 1         | 0.72%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 0.72%   |
| Intel Core i9-7960X CPU @ 2.80GHz           | 1         | 0.72%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1         | 0.72%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.72%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.72%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.72%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.72%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 0.72%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 0.72%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 0.72%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.72%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz          | 1         | 0.72%   |
| Intel Core i7-4850HQ CPU @ 2.30GHz          | 1         | 0.72%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.72%   |
| Intel Core i7-4770HQ CPU @ 2.20GHz          | 1         | 0.72%   |
| Intel Core i7-4650U CPU @ 1.70GHz           | 1         | 0.72%   |
| Intel Core i7-4610M CPU @ 3.00GHz           | 1         | 0.72%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 1         | 0.72%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 1         | 0.72%   |
| Intel Core i7-4500U CPU                     | 1         | 0.72%   |
| Intel Core i7-3537U CPU @ 2.00GHz           | 1         | 0.72%   |
| Intel Core i7-2820QM CPU @ 2.30GHz          | 1         | 0.72%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 0.72%   |
| Intel Core i7-10610U CPU @ 1.80GHz          | 1         | 0.72%   |
| Intel Core i7 CPU L 640 @ 2.13GHz           | 1         | 0.72%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 1         | 0.72%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1         | 0.72%   |
| Intel Core i5-9300HF CPU @ 2.40GHz          | 1         | 0.72%   |
| Intel Core i5-8600K CPU @ 3.60GHz           | 1         | 0.72%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 0.72%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 40        | 28.99%  |
| Intel Core i7           | 32        | 23.19%  |
| Intel Core 2 Duo        | 10        | 7.25%   |
| Intel Core i3           | 8         | 5.8%    |
| AMD Ryzen 5             | 7         | 5.07%   |
| Other                   | 4         | 2.9%    |
| Intel Xeon              | 3         | 2.17%   |
| Intel Pentium           | 3         | 2.17%   |
| Intel Celeron           | 3         | 2.17%   |
| Intel Atom              | 3         | 2.17%   |
| AMD Ryzen 7             | 3         | 2.17%   |
| AMD A6                  | 3         | 2.17%   |
| Intel Pentium Dual-Core | 2         | 1.45%   |
| Intel Core i9           | 2         | 1.45%   |
| AMD Athlon 64 X2        | 2         | 1.45%   |
| AMD A8                  | 2         | 1.45%   |
| Intel Pentium Silver    | 1         | 0.72%   |
| Intel Pentium III       | 1         | 0.72%   |
| Intel Pentium D         | 1         | 0.72%   |
| Intel Genuine           | 1         | 0.72%   |
| Intel Core m5           | 1         | 0.72%   |
| Intel Core 2            | 1         | 0.72%   |
| Intel Celeron M         | 1         | 0.72%   |
| AMD Ryzen 9             | 1         | 0.72%   |
| AMD FX                  | 1         | 0.72%   |
| AMD E1                  | 1         | 0.72%   |
| AMD A10                 | 1         | 0.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 62        | 44.93%  |
| 4       | 43        | 31.16%  |
| 8       | 9         | 6.52%   |
| Unknown | 9         | 6.52%   |
| 6       | 6         | 4.35%   |
| 12      | 3         | 2.17%   |
| 1       | 3         | 2.17%   |
| 16      | 2         | 1.45%   |
| 24      | 1         | 0.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 136       | 99.27%  |
| 2      | 1         | 0.73%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 78        | 56.52%  |
| 1       | 49        | 35.51%  |
| Unknown | 11        | 7.97%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 26        | 18.84%  |
| Haswell       | 18        | 13.04%  |
| Skylake       | 14        | 10.14%  |
| Penryn        | 13        | 9.42%   |
| IvyBridge     | 11        | 7.97%   |
| SandyBridge   | 10        | 7.25%   |
| Zen+          | 5         | 3.62%   |
| Puma          | 4         | 2.9%    |
| Broadwell     | 4         | 2.9%    |
| Bonnell       | 4         | 2.9%    |
| Zen           | 3         | 2.17%   |
| Nehalem       | 3         | 2.17%   |
| Core          | 3         | 2.17%   |
| Zen 2         | 2         | 1.45%   |
| Westmere      | 2         | 1.45%   |
| Silvermont    | 2         | 1.45%   |
| P6            | 2         | 1.45%   |
| K8 Hammer     | 2         | 1.45%   |
| Goldmont plus | 2         | 1.45%   |
| Zen 3         | 1         | 0.72%   |
| Steamroller   | 1         | 0.72%   |
| Piledriver    | 1         | 0.72%   |
| NetBurst      | 1         | 0.72%   |
| K10 Llano     | 1         | 0.72%   |
| Jaguar        | 1         | 0.72%   |
| Excavator     | 1         | 0.72%   |
| CometLake     | 1         | 0.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 88        | 58.67%  |
| AMD              | 31        | 20.67%  |
| Nvidia           | 29        | 19.33%  |
| VIA Technologies | 1         | 0.67%   |
| S3 Graphics      | 1         | 0.67%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 5.81%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 5.16%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 5.16%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 4.52%   |
| Intel UHD Graphics 620                                                                   | 5         | 3.23%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 4         | 2.58%   |
| Intel HD Graphics 620                                                                    | 4         | 2.58%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 2.58%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.58%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.94%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.94%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 1.94%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 1.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.29%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 1.29%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.29%   |
| Intel HD Graphics 630                                                                    | 2         | 1.29%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.29%   |
| Intel HD Graphics 530                                                                    | 2         | 1.29%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.29%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.29%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 1.29%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.29%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 1.29%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.65%   |
| S3 Graphics SuperSavage IX/C SDR                                                         | 1         | 0.65%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.65%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.65%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 0.65%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.65%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.65%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 1         | 0.65%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.65%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.65%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.65%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.65%   |
| Nvidia GM107GL [Quadro K2200]                                                            | 1         | 0.65%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 1         | 0.65%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.65%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 1         | 0.65%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 0.65%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.65%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                                     | 1         | 0.65%   |
| Nvidia GF114M [GeForce GTX 580M]                                                         | 1         | 0.65%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.65%   |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 1         | 0.65%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 0.65%   |
| Nvidia G72M [GeForce Go 7400]                                                            | 1         | 0.65%   |
| Nvidia G72 [GeForce 7300 LE]                                                             | 1         | 0.65%   |
| Intel UHD Graphics 615                                                                   | 1         | 0.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.65%   |
| Intel Iris Graphics 540                                                                  | 1         | 0.65%   |
| Intel HD Graphics P530                                                                   | 1         | 0.65%   |
| Intel HD Graphics 6000                                                                   | 1         | 0.65%   |
| Intel HD Graphics 515                                                                    | 1         | 0.65%   |
| Intel HD Graphics                                                                        | 1         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 70        | 50.72%  |
| 1 x AMD         | 27        | 19.57%  |
| 1 x Nvidia      | 19        | 13.77%  |
| Intel + Nvidia  | 9         | 6.52%   |
| 2 x Intel       | 7         | 5.07%   |
| Intel + AMD     | 2         | 1.45%   |
| 2 x AMD         | 1         | 0.72%   |
| 1 x VIA         | 1         | 0.72%   |
| 1 x S3 Graphics | 1         | 0.72%   |
| AMD + Nvidia    | 1         | 0.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 108       | 78.83%  |
| Proprietary | 15        | 10.95%  |
| Unknown     | 14        | 10.22%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 108       | 78.26%  |
| 0.01-0.5   | 9         | 6.52%   |
| 1.01-2.0   | 8         | 5.8%    |
| 0.51-1.0   | 5         | 3.62%   |
| 5.01-6.0   | 4         | 2.9%    |
| 7.01-8.0   | 2         | 1.45%   |
| 3.01-4.0   | 2         | 1.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 14        | 11.67%  |
| Samsung Electronics     | 13        | 10.83%  |
| AU Optronics            | 13        | 10.83%  |
| BOE                     | 12        | 10%     |
| Goldstar                | 9         | 7.5%    |
| Chimei Innolux          | 8         | 6.67%   |
| Dell                    | 7         | 5.83%   |
| Acer                    | 6         | 5%      |
| Hewlett-Packard         | 5         | 4.17%   |
| Sharp                   | 3         | 2.5%    |
| Lenovo                  | 3         | 2.5%    |
| HannStar                | 3         | 2.5%    |
| Chi Mei Optoelectronics | 3         | 2.5%    |
| Apple                   | 3         | 2.5%    |
| Philips                 | 2         | 1.67%   |
| Panasonic               | 2         | 1.67%   |
| BenQ                    | 2         | 1.67%   |
| ___                     | 1         | 0.83%   |
| Westinghouse            | 1         | 0.83%   |
| Vizio                   | 1         | 0.83%   |
| ViewSonic               | 1         | 0.83%   |
| Toshiba                 | 1         | 0.83%   |
| Sony                    | 1         | 0.83%   |
| NEC Computers           | 1         | 0.83%   |
| LG Philips              | 1         | 0.83%   |
| LG Electronics          | 1         | 0.83%   |
| CPT                     | 1         | 0.83%   |
| AOC                     | 1         | 0.83%   |
| Ancor Communications    | 1         | 0.83%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch          | 2         | 1.64%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 2         | 1.64%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch             | 2         | 1.64%   |
| BOE LCD Monitor BOE0671 1366x768 340x190mm 15.3-inch                  | 2         | 1.64%   |
| AU Optronics LCD Monitor AUO8174 1280x800 330x210mm 15.4-inch         | 2         | 1.64%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch         | 2         | 1.64%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 2         | 1.64%   |
| ___ MY TV LED TV ___0101 1920x1080                                    | 1         | 0.82%   |
| Westinghouse DWM40F3G1 WET1ECC 1920x1080 880x480mm 39.5-inch          | 1         | 0.82%   |
| Vizio SV370XVT VIZ0057 1920x1080 820x460mm 37.0-inch                  | 1         | 0.82%   |
| ViewSonic VX910 VSC3C19 1280x1024 380x300mm 19.1-inch                 | 1         | 0.82%   |
| Toshiba LCD-MONITOR LCDC980 1280x1024 380x300mm 19.1-inch             | 1         | 0.82%   |
| Sony TV SNY5D01 1360x768                                              | 1         | 0.82%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch               | 1         | 0.82%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch               | 1         | 0.82%   |
| Sharp LCD Monitor SHP140E 2560x1440 290x170mm 13.2-inch               | 1         | 0.82%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch     | 1         | 0.82%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 410x260mm 19.1-inch   | 1         | 0.82%   |
| Samsung Electronics S27E330 SAM0D91 1920x1080 600x340mm 27.2-inch     | 1         | 0.82%   |
| Samsung Electronics LF24T450F SAM7094 1920x1080 530x300mm 24.0-inch   | 1         | 0.82%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                     | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch  | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch  | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 220x130mm 10.1-inch  | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 290x160mm 13.0-inch | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 310x170mm 13.9-inch  | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 290x160mm 13.0-inch | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch  | 1         | 0.82%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 1         | 0.82%   |
| Philips 170S PHL0856 1280x1024 340x270mm 17.1-inch                    | 1         | 0.82%   |
| NEC Computers EA223WM NEC6890 1680x1050 470x300mm 22.0-inch           | 1         | 0.82%   |
| LG Philips LCD Monitor LPLA101 1440x900 370x230mm 17.2-inch           | 1         | 0.82%   |
| LG Electronics LCD Monitor LG HDR QHD 2560x1440                       | 1         | 0.82%   |
| LG Display LCD Monitor LGD7001 1366x768 340x190mm 15.3-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD6301 1366x768 340x190mm 15.3-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD05B3 1920x1080 290x170mm 13.2-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD0414 1920x1080 280x160mm 12.7-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD040A 1920x1080 310x170mm 13.9-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD034D 1366x768 340x190mm 15.3-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD0303 1600x900 380x210mm 17.1-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD01F7 1366x768 290x160mm 13.0-inch           | 1         | 0.82%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch               | 1         | 0.82%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch               | 1         | 0.82%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch               | 1         | 0.82%   |
| Hewlett-Packard W2072a HWP299F 1600x900 440x250mm 19.9-inch           | 1         | 0.82%   |
| Hewlett-Packard vs17 HWP2647 1280x1024 340x270mm 17.1-inch            | 1         | 0.82%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch           | 1         | 0.82%   |
| Hewlett-Packard HPQ 8300 AiO HWP4212 1920x1080 510x290mm 23.1-inch    | 1         | 0.82%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch            | 1         | 0.82%   |
| HannStar LCD Monitor HSD0013 1280x1024 380x300mm 19.1-inch            | 1         | 0.82%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                  | 1         | 0.82%   |
| Goldstar W1943 GSM4BAD 1360x768 410x230mm 18.5-inch                   | 1         | 0.82%   |
| Goldstar LG UltraFine GSM5B10 3840x2160 480x270mm 21.7-inch           | 1         | 0.82%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch            | 1         | 0.82%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 1         | 0.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 38        | 32.2%   |
| 1366x768 (WXGA)    | 33        | 27.97%  |
| 1280x1024 (SXGA)   | 10        | 8.47%   |
| 1600x900 (HD+)     | 7         | 5.93%   |
| 3840x2160 (4K)     | 5         | 4.24%   |
| 1440x900 (WXGA+)   | 4         | 3.39%   |
| 1280x800 (WXGA)    | 4         | 3.39%   |
| 1024x600           | 4         | 3.39%   |
| 2560x1440 (QHD)    | 3         | 2.54%   |
| 2880x1620          | 2         | 1.69%   |
| 1680x1050 (WSXGA+) | 2         | 1.69%   |
| 1360x768           | 2         | 1.69%   |
| 3200x1800 (QHD+)   | 1         | 0.85%   |
| 2880x1800          | 1         | 0.85%   |
| 1920x1200 (WUXGA)  | 1         | 0.85%   |
| 1600x1200          | 1         | 0.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 32        | 26.45%  |
| 13      | 20        | 16.53%  |
| 17      | 12        | 9.92%   |
| 24      | 8         | 6.61%   |
| 19      | 8         | 6.61%   |
| 21      | 7         | 5.79%   |
| 12      | 7         | 5.79%   |
| 27      | 6         | 4.96%   |
| 10      | 4         | 3.31%   |
| Unknown | 4         | 3.31%   |
| 18      | 3         | 2.48%   |
| 11      | 3         | 2.48%   |
| 23      | 2         | 1.65%   |
| 22      | 2         | 1.65%   |
| 39      | 1         | 0.83%   |
| 37      | 1         | 0.83%   |
| 14      | 1         | 0.83%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 49        | 40.83%  |
| 201-300     | 24        | 20%     |
| 401-500     | 15        | 12.5%   |
| 501-600     | 14        | 11.67%  |
| 351-400     | 10        | 8.33%   |
| Unknown     | 4         | 3.33%   |
| 801-900     | 2         | 1.67%   |
| 601-700     | 2         | 1.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 87        | 77.68%  |
| 16/10   | 13        | 11.61%  |
| 5/4     | 10        | 8.93%   |
| Unknown | 2         | 1.79%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 25        | 20.66%  |
| 201-250        | 18        | 14.88%  |
| 81-90          | 14        | 11.57%  |
| 141-150        | 9         | 7.44%   |
| 151-200        | 8         | 6.61%   |
| 71-80          | 7         | 5.79%   |
| 61-70          | 7         | 5.79%   |
| 101-110        | 7         | 5.79%   |
| 301-350        | 6         | 4.96%   |
| 121-130        | 5         | 4.13%   |
| 41-50          | 4         | 3.31%   |
| Unknown        | 4         | 3.31%   |
| 51-60          | 3         | 2.48%   |
| 501-1000       | 2         | 1.65%   |
| 251-300        | 1         | 0.83%   |
| 131-140        | 1         | 0.83%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 41        | 35.04%  |
| 51-100        | 33        | 28.21%  |
| 121-160       | 25        | 21.37%  |
| 161-240       | 12        | 10.26%  |
| Unknown       | 4         | 3.42%   |
| More than 240 | 2         | 1.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 106       | 76.26%  |
| 0     | 24        | 17.27%  |
| 2     | 7         | 5.04%   |
| 3     | 2         | 1.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 79        | 39.5%   |
| Realtek Semiconductor             | 56        | 28%     |
| Qualcomm Atheros                  | 29        | 14.5%   |
| Broadcom                          | 12        | 6%      |
| Ralink                            | 3         | 1.5%    |
| Qualcomm                          | 2         | 1%      |
| Mellanox Technologies             | 2         | 1%      |
| Marvell Technology Group          | 2         | 1%      |
| Fibocom                           | 2         | 1%      |
| VIA Technologies                  | 1         | 0.5%    |
| TP-Link                           | 1         | 0.5%    |
| Silicon Integrated Systems [SiS]  | 1         | 0.5%    |
| Sierra Wireless                   | 1         | 0.5%    |
| Samsung Electronics               | 1         | 0.5%    |
| Ralink Technology                 | 1         | 0.5%    |
| Nvidia                            | 1         | 0.5%    |
| Microchip Technology              | 1         | 0.5%    |
| JMicron Technology                | 1         | 0.5%    |
| Ericsson Business Mobile Networks | 1         | 0.5%    |
| D-Link System                     | 1         | 0.5%    |
| Brooktrout Technology             | 1         | 0.5%    |
| Atheros                           | 1         | 0.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 14.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 4.62%   |
| Intel Wireless 7260                                               | 10        | 3.85%   |
| Intel Wireless 8265 / 8275                                        | 7         | 2.69%   |
| Intel Wireless 8260                                               | 6         | 2.31%   |
| Intel Wireless 3165                                               | 6         | 2.31%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 2.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.92%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.92%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 1.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 1.54%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 4         | 1.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 1.15%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.15%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 1.15%   |
| Intel Wireless 7265                                               | 3         | 1.15%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.15%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.15%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 1.15%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 2         | 0.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.77%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 2         | 0.77%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 2         | 0.77%   |
| Intel Wireless-AC 9260                                            | 2         | 0.77%   |
| Intel WiFi Link 5100                                              | 2         | 0.77%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.77%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 2         | 0.77%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.77%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.77%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.77%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.77%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.77%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.77%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                 | 2         | 0.77%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.38%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.38%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.38%   |
| Sierra Wireless EM7455                                            | 1         | 0.38%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.38%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.38%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1         | 0.38%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.38%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.38%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.38%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.38%   |
| Realtek Realtek Bluetooth 4.2 Adapter                             | 1         | 0.38%   |
| Ralink RT5372 Wireless Adapter                                    | 1         | 0.38%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 0.38%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 60        | 50.42%  |
| Qualcomm Atheros      | 23        | 19.33%  |
| Realtek Semiconductor | 20        | 16.81%  |
| Broadcom              | 8         | 6.72%   |
| Ralink                | 3         | 2.52%   |
| TP-Link               | 1         | 0.84%   |
| Sierra Wireless       | 1         | 0.84%   |
| Ralink Technology     | 1         | 0.84%   |
| D-Link System         | 1         | 0.84%   |
| Atheros               | 1         | 0.84%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                                   | 10        | 8.2%    |
| Intel Wireless 8265 / 8275                                                            | 7         | 5.74%   |
| Intel Wireless 8260                                                                   | 6         | 4.92%   |
| Intel Wireless 3165                                                                   | 6         | 4.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 5         | 4.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 5         | 4.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 4         | 3.28%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 4         | 3.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 2.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 3         | 2.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 3         | 2.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 3         | 2.46%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 3         | 2.46%   |
| Intel Wireless 7265                                                                   | 3         | 2.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 3         | 2.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 3         | 2.46%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 2         | 1.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 1.64%   |
| Intel Wireless-AC 9260                                                                | 2         | 1.64%   |
| Intel WiFi Link 5100                                                                  | 2         | 1.64%   |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 1.64%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 2         | 1.64%   |
| Intel Centrino Advanced-N 6200                                                        | 2         | 1.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 2         | 1.64%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 0.82%   |
| Sierra Wireless EM7455                                                                | 1         | 0.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1         | 0.82%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.82%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1         | 0.82%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 0.82%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1         | 0.82%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 0.82%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                                 | 1         | 0.82%   |
| Ralink RT5372 Wireless Adapter                                                        | 1         | 0.82%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 1         | 0.82%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.82%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.82%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.82%   |
| Intel WiMAX/WiFi Link 5150                                                            | 1         | 0.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 0.82%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 0.82%   |
| Intel Centrino Wireless-N 6150                                                        | 1         | 0.82%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 0.82%   |
| Intel Centrino Wireless-N 105                                                         | 1         | 0.82%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                         | 1         | 0.82%   |
| Intel Centrino WiMAX 6150                                                             | 1         | 0.82%   |
| Intel Centrino Ultimate-N 6300                                                        | 1         | 0.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 1         | 0.82%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]                  | 1         | 0.82%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                           | 1         | 0.82%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                    | 1         | 0.82%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 1         | 0.82%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller                   | 1         | 0.82%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 0.82%   |
| Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]                  | 1         | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 53        | 41.09%  |
| Realtek Semiconductor            | 52        | 40.31%  |
| Qualcomm Atheros                 | 8         | 6.2%    |
| Broadcom                         | 7         | 5.43%   |
| Qualcomm                         | 2         | 1.55%   |
| Marvell Technology Group         | 2         | 1.55%   |
| VIA Technologies                 | 1         | 0.78%   |
| Silicon Integrated Systems [SiS] | 1         | 0.78%   |
| Samsung Electronics              | 1         | 0.78%   |
| Nvidia                           | 1         | 0.78%   |
| JMicron Technology               | 1         | 0.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 28.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 9.16%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 4.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 4.58%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 3.82%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 3.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 2.29%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.29%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 2.29%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 2.29%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.53%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 2         | 1.53%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.53%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.53%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.53%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.53%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.53%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.76%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.76%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.76%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.76%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.76%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.76%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.76%   |
| Nvidia MCP73 Ethernet                                             | 1         | 0.76%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.76%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.76%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.76%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1         | 0.76%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.76%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.76%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.76%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.76%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.76%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.76%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.76%   |
| Intel 82801CAM (ICH3) PRO/100 VE (LOM) Ethernet Controller        | 1         | 0.76%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.76%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.76%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 0.76%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1         | 0.76%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1         | 0.76%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 0.76%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.76%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 0.76%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1         | 0.76%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.76%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 125       | 51.02%  |
| WiFi     | 113       | 46.12%  |
| Unknown  | 6         | 2.45%   |
| Modem    | 1         | 0.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 117       | 55.98%  |
| WiFi     | 87        | 41.63%  |
| Unknown  | 5         | 2.39%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 98        | 71.01%  |
| 1     | 38        | 27.54%  |
| 4     | 1         | 0.72%   |
| 3     | 1         | 0.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 126       | 91.3%   |
| Yes  | 12        | 8.7%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 38        | 46.91%  |
| Realtek Semiconductor           | 6         | 7.41%   |
| Qualcomm Atheros Communications | 6         | 7.41%   |
| Lite-On Technology              | 5         | 6.17%   |
| Broadcom                        | 5         | 6.17%   |
| ASUSTek Computer                | 5         | 6.17%   |
| Apple                           | 5         | 6.17%   |
| IMC Networks                    | 4         | 4.94%   |
| Foxconn / Hon Hai               | 2         | 2.47%   |
| Cambridge Silicon Radio         | 2         | 2.47%   |
| Hewlett-Packard                 | 1         | 1.23%   |
| Dell                            | 1         | 1.23%   |
| Alps Electric                   | 1         | 1.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 25        | 30.86%  |
| Intel AX201 Bluetooth                                       | 4         | 4.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3         | 3.7%    |
| Apple Apple Broadcom Built-in Bluetooth                     | 3         | 3.7%    |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 2.47%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 2.47%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 2.47%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 2.47%   |
| Intel AX200 Bluetooth                                       | 2         | 2.47%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 2.47%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 2.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 2.47%   |
| ASUS BT-253 Bluetooth Adapter                               | 2         | 2.47%   |
| Apple Bluetooth Host Controller                             | 2         | 2.47%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 1.23%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 1.23%   |
| Realtek  Bluetooth 4.0 Adapter                              | 1         | 1.23%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 1         | 1.23%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 1         | 1.23%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.23%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.23%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device        | 1         | 1.23%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.23%   |
| Lite-On Bluetooth USB Module                                | 1         | 1.23%   |
| Lite-On Atheros Bluetooth                                   | 1         | 1.23%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.23%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 1.23%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 1.23%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 1.23%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.23%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 1.23%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 1.23%   |
| Dell DW375 Bluetooth Module                                 | 1         | 1.23%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 1         | 1.23%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.23%   |
| Broadcom BCM2045 Bluetooth                                  | 1         | 1.23%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                       | 1         | 1.23%   |
| ASUS Bluetooth Controller                                   | 1         | 1.23%   |
| ASUS ASUS USB-BT500                                         | 1         | 1.23%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 1.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 111       | 63.07%  |
| AMD                              | 31        | 17.61%  |
| Nvidia                           | 19        | 10.8%   |
| Sony                             | 2         | 1.14%   |
| Corsair                          | 2         | 1.14%   |
| C-Media Electronics              | 2         | 1.14%   |
| XMOS                             | 1         | 0.57%   |
| VIA Technologies                 | 1         | 0.57%   |
| Silicon Integrated Systems [SiS] | 1         | 0.57%   |
| Realtek Semiconductor            | 1         | 0.57%   |
| Quanta                           | 1         | 0.57%   |
| LG Electronics                   | 1         | 0.57%   |
| Creative Technology              | 1         | 0.57%   |
| Blue Microphones                 | 1         | 0.57%   |
| Audio-Technica                   | 1         | 0.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 9.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 5.58%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 4.19%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 4.19%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 4.19%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 4.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 3.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 3.26%   |
| AMD FCH Azalia Controller                                                                         | 7         | 3.26%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 2.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 2.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 2.33%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 2.33%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 1.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.86%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.86%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.86%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.86%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.86%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 1.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.4%    |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 1.4%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.4%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.4%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.93%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.93%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 0.93%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.93%   |
| Corsair Corsair VOID PRO Wireless Gaming Headset                                                  | 2         | 0.93%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 0.93%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.93%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.93%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 0.93%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.93%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 0.93%   |
| XMOS XMOS XS1-U8 MFA (ST)                                                                         | 1         | 0.47%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.47%   |
| Sony Sony Audio                                                                                   | 1         | 0.47%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1         | 0.47%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.47%   |
| Realtek Semiconductor Realtek USB Audio                                                           | 1         | 0.47%   |
| Quanta USB Audio Realtek USB2.0 Audio Microphone                                                  | 1         | 0.47%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.47%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.47%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.47%   |
| Nvidia MCP73 High Definition Audio                                                                | 1         | 0.47%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.47%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.47%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.47%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.47%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.47%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.47%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.47%   |
| LG Electronics USB Audio LG UltraFine Display Audio                                               | 1         | 0.47%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.47%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.47%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 0.47%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 0.47%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 38        | 24.05%  |
| SK Hynix            | 33        | 20.89%  |
| Micron Technology   | 17        | 10.76%  |
| Unknown             | 16        | 10.13%  |
| Kingston            | 12        | 7.59%   |
| Crucial             | 8         | 5.06%   |
| G.Skill             | 7         | 4.43%   |
| Elpida              | 6         | 3.8%    |
| Corsair             | 6         | 3.8%    |
| Nanya Technology    | 4         | 2.53%   |
| Transcend           | 2         | 1.27%   |
| A-DATA Technology   | 2         | 1.27%   |
| Unknown             | 2         | 1.27%   |
| Unknown (ABCD)      | 1         | 0.63%   |
| Unknown (09D5)      | 1         | 0.63%   |
| Magnum Tech         | 1         | 0.63%   |
| EVGA                | 1         | 0.63%   |
| 48spaces            | 1         | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s              | 7         | 4.09%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 4         | 2.34%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 3         | 1.75%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 1.75%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 1.75%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 3         | 1.75%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s               | 3         | 1.75%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 1.75%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                            | 2         | 1.17%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 2         | 1.17%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.17%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.17%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.17%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                       | 2         | 1.17%   |
| Micron RAM ITC 4096MB DIMM DDR3 1066MT/s                            | 2         | 1.17%   |
| Unknown                                                             | 2         | 1.17%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                           | 1         | 0.58%   |
| Unknown SODIMM 1024MB SODIMM DDR2 667MT/s                           | 1         | 0.58%   |
| Unknown RAM Module 512MB SODIMM SDRAM                               | 1         | 0.58%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                      | 1         | 0.58%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 1         | 0.58%   |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 1         | 0.58%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                            | 1         | 0.58%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                              | 1         | 0.58%   |
| Unknown RAM Module 1GB SODIMM DRAM 533MT/s                          | 1         | 0.58%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 1         | 0.58%   |
| Unknown RAM Module 128MB SODIMM SDRAM                               | 1         | 0.58%   |
| Unknown RAM Module 1024MB SODIMM RAM                                | 1         | 0.58%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s                         | 1         | 0.58%   |
| Unknown RAM 7TE39AA# 8GB DIMM DDR4 2667MT/s                         | 1         | 0.58%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB SODIMM LPDDR4 2133MT/s | 1         | 0.58%   |
| Unknown (09D5) RAM Module 16GB SODIMM DDR4 2400MT/s                 | 1         | 0.58%   |
| Transcend RAM TS512MSK64V1N 4GB SODIMM 800MT/s                      | 1         | 0.58%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR 667MT/s                    | 1         | 0.58%   |
| SK Hynix RAM Zhidian4GDDR800000 4GB DIMM DDR2 800MT/s               | 1         | 0.58%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 1         | 0.58%   |
| SK Hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s                | 1         | 0.58%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s               | 1         | 0.58%   |
| SK Hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s                | 1         | 0.58%   |
| SK Hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s                | 1         | 0.58%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s                | 1         | 0.58%   |
| SK Hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.58%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.58%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s                | 1         | 0.58%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1067MT/s                | 1         | 0.58%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1333MT/s              | 1         | 0.58%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.58%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 1         | 0.58%   |
| SK Hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s                | 1         | 0.58%   |
| SK Hynix RAM HMT31GR7AFR4C-H9 8GB DIMM DDR3 1333MT/s                | 1         | 0.58%   |
| SK Hynix RAM HMT125U6AFP8C-G7 2048MB DIMM DDR3 1066MT/s             | 1         | 0.58%   |
| SK Hynix RAM HMT112U6AFP8C-G7 1GB DIMM 1066MT/s                     | 1         | 0.58%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s          | 1         | 0.58%   |
| SK Hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s             | 1         | 0.58%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 0.58%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.58%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s              | 1         | 0.58%   |
| SK Hynix RAM H9CCNNNBJTMLAR-NUD 4096MB SODIMM LPDDR3 1867MT/s       | 1         | 0.58%   |
| SK Hynix RAM H5TC8G63AMR-PBA 4096MB 1600MT/s                        | 1         | 0.58%   |
| Samsung RAM Module 16GB SODIMM DDR4 2133MT/s                        | 1         | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 60        | 42.86%  |
| DDR4    | 46        | 32.86%  |
| DDR2    | 16        | 11.43%  |
| LPDDR3  | 5         | 3.57%   |
| SDRAM   | 4         | 2.86%   |
| Unknown | 4         | 2.86%   |
| DDR     | 2         | 1.43%   |
| RAM     | 1         | 0.71%   |
| LPDDR4  | 1         | 0.71%   |
| DRAM    | 1         | 0.71%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 94        | 67.63%  |
| DIMM         | 38        | 27.34%  |
| Chip         | 3         | 2.16%   |
| Row Of Chips | 2         | 1.44%   |
| Unknown      | 2         | 1.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 60        | 38.46%  |
| 8192  | 45        | 28.85%  |
| 2048  | 26        | 16.67%  |
| 16384 | 13        | 8.33%   |
| 1024  | 9         | 5.77%   |
| 32768 | 1         | 0.64%   |
| 512   | 1         | 0.64%   |
| 128   | 1         | 0.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 41        | 28.08%  |
| 2400    | 20        | 13.7%   |
| 2667    | 13        | 8.9%    |
| 2133    | 10        | 6.85%   |
| 1333    | 10        | 6.85%   |
| 3200    | 8         | 5.48%   |
| 800     | 8         | 5.48%   |
| 667     | 7         | 4.79%   |
| 1334    | 6         | 4.11%   |
| Unknown | 6         | 4.11%   |
| 1066    | 4         | 2.74%   |
| 1067    | 3         | 2.05%   |
| 3600    | 2         | 1.37%   |
| 2933    | 2         | 1.37%   |
| 1867    | 2         | 1.37%   |
| 533     | 2         | 1.37%   |
| 1866    | 1         | 0.68%   |
| 975     | 1         | 0.68%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 33.33%  |
| Dymo-CoStar     | 1         | 33.33%  |
| Apple           | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


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

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 20        | 25%     |
| Realtek Semiconductor                  | 9         | 11.25%  |
| Acer                                   | 9         | 11.25%  |
| Sunplus Innovation Technology          | 7         | 8.75%   |
| Suyin                                  | 6         | 7.5%    |
| Microdia                               | 5         | 6.25%   |
| Logitech                               | 4         | 5%      |
| Cheng Uei Precision Industry (Foxlink) | 4         | 5%      |
| Silicon Motion                         | 3         | 3.75%   |
| Quanta                                 | 3         | 3.75%   |
| IMC Networks                           | 3         | 3.75%   |
| Lite-On Technology                     | 2         | 2.5%    |
| Novatek Microelectronics               | 1         | 1.25%   |
| Intel                                  | 1         | 1.25%   |
| Genesys Logic                          | 1         | 1.25%   |
| Apple                                  | 1         | 1.25%   |
| Alcor Micro                            | 1         | 1.25%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 8         | 9.88%   |
| Acer Integrated Camera                                         | 5         | 6.17%   |
| Sunplus Integrated_Webcam_HD                                   | 4         | 4.94%   |
| Suyin Acer Crystal Eye webcam                                  | 2         | 2.47%   |
| Realtek Realtek USB2.0 PC Camera                               | 2         | 2.47%   |
| Realtek Lenovo EasyCamera                                      | 2         | 2.47%   |
| Quanta Realtek DMFT - RGB                                      | 2         | 2.47%   |
| Microdia Integrated_Webcam_HD                                  | 2         | 2.47%   |
| Microdia Integrated Webcam                                     | 2         | 2.47%   |
| Chicony HD WebCam                                              | 2         | 2.47%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam            | 2         | 2.47%   |
| Suyin USB 2.0 UVC 1.3M WebCam                                  | 1         | 1.23%   |
| Suyin Laptop_Integrated_Webcam_3M                              | 1         | 1.23%   |
| Suyin HD WebCam                                                | 1         | 1.23%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 1         | 1.23%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 1.23%   |
| Sunplus Integrated Webcam                                      | 1         | 1.23%   |
| Sunplus Asus Webcam                                            | 1         | 1.23%   |
| Silicon Motion WebCam SCX Series                               | 1         | 1.23%   |
| Silicon Motion Realtek USB2.0 PC Camera                        | 1         | 1.23%   |
| Silicon Motion 300k Pixel Camera                               | 1         | 1.23%   |
| Realtek USB2.0 VGA UVC WebCam                                  | 1         | 1.23%   |
| Realtek USB2.0 HD UVC WebCam                                   | 1         | 1.23%   |
| Realtek USB Camera                                             | 1         | 1.23%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 1.23%   |
| Realtek HD Webcam - Realtek                                    | 1         | 1.23%   |
| Quanta Front camera                                            | 1         | 1.23%   |
| Novatek HP High Definition 2MP Webcam                          | 1         | 1.23%   |
| Microdia Sonix USB 2.0 Camera                                  | 1         | 1.23%   |
| Logitech Webcam C310                                           | 1         | 1.23%   |
| Logitech Webcam C270                                           | 1         | 1.23%   |
| Logitech HD Pro Webcam C920                                    | 1         | 1.23%   |
| Logitech C505 HD Webcam                                        | 1         | 1.23%   |
| Lite-On Integrated Camera                                      | 1         | 1.23%   |
| Lite-On HP Universal Camera                                    | 1         | 1.23%   |
| Intel WiMAX Connection 2400m                                   | 1         | 1.23%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 1         | 1.23%   |
| IMC Networks USB2.0 UVC HD Webcam                              | 1         | 1.23%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 1.23%   |
| Genesys Logic Camera                                           | 1         | 1.23%   |
| Chicony Webcam                                                 | 1         | 1.23%   |
| Chicony USB2.0 HD UVC WebCam                                   | 1         | 1.23%   |
| Chicony Thinkpad T430 camera                                   | 1         | 1.23%   |
| Chicony Realtek DMFT - IR                                      | 1         | 1.23%   |
| Chicony Lenovo EasyCamera                                      | 1         | 1.23%   |
| Chicony Integrated Camera [ThinkPad]                           | 1         | 1.23%   |
| Chicony Integrated Camera (1280x720@30)                        | 1         | 1.23%   |
| Chicony HP TrueVision HD Camera                                | 1         | 1.23%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 1.23%   |
| Chicony FJ Camera                                              | 1         | 1.23%   |
| Chicony Chicony USB2.0 Camera                                  | 1         | 1.23%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.23%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 1         | 1.23%   |
| Apple FaceTime HD Camera                                       | 1         | 1.23%   |
| Alcor Micro HP WebCam-101                                      | 1         | 1.23%   |
| Acer USB2.0 Camera                                             | 1         | 1.23%   |
| Acer NEC HD WebCam                                             | 1         | 1.23%   |
| Acer Lenovo EasyCamera                                         | 1         | 1.23%   |
| Acer EasyCamera                                                | 1         | 1.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 11        | 61.11%  |
| Synaptics        | 4         | 22.22%  |
| Upek             | 1         | 5.56%   |
| Broadcom         | 1         | 5.56%   |
| AuthenTec        | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 3         | 16.67%  |
| Validity Sensors Synaptics WBDI                                              | 2         | 11.11%  |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 2         | 11.11%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 5.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 5.56%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 5.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.56%   |
| AuthenTec AES1600                                                            | 1         | 5.56%   |
| Unknown                                                                      | 1         | 5.56%   |

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
| 1     | 50        | 35.46%  |
| 2     | 42        | 29.79%  |
| 0     | 23        | 16.31%  |
| 3     | 15        | 10.64%  |
| 4     | 7         | 4.96%   |
| 5     | 2         | 1.42%   |
| 7     | 1         | 0.71%   |
| 6     | 1         | 0.71%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 91        | 44.39%  |
| Net/wireless             | 33        | 16.1%   |
| Bluetooth                | 21        | 10.24%  |
| Firewire controller      | 19        | 9.27%   |
| Fingerprint reader       | 18        | 8.78%   |
| Card reader              | 16        | 7.8%    |
| Network                  | 4         | 1.95%   |
| Sound                    | 2         | 0.98%   |
| Storage/raid             | 1         | 0.49%   |

