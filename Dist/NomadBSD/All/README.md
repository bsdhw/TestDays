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

Total: 194

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| NomadBSD 1.3.2    | 52        | 35.37%  |
| NomadBSD 5806f915 | 50        | 34.01%  |
| NomadBSD 1.4      | 23        | 15.65%  |
| NomadBSD 1.4-RC1  | 10        | 6.8%    |
| NomadBSD 1.3.1    | 10        | 6.8%    |
| NomadBSD 1.3      | 1         | 0.68%   |
| NomadBSD 1.0      | 1         | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| NomadBSD | 142       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 135       | 94.41%  |
| i386  | 8         | 5.59%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Openbox       | 129       | 90.21%  |
| GNOME         | 7         | 4.9%    |
| KDE5          | 3         | 2.1%    |
| XFCE          | 1         | 0.7%    |
| GNUstep       | 1         | 0.7%    |
| filer         | 1         | 0.7%    |
| Enlightenment | 1         | 0.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 142       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 140       | 98.59%  |
| SDDM | 2         | 1.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 55        | 38.19%  |
| Unknown | 27        | 18.75%  |
| de_DE   | 15        | 10.42%  |
| ru_RU   | 7         | 4.86%   |
| en_GB   | 7         | 4.86%   |
| it_IT   | 5         | 3.47%   |
| hu_HU   | 5         | 3.47%   |
| zh_CN   | 3         | 2.08%   |
| tr_TR   | 3         | 2.08%   |
| es_ES   | 3         | 2.08%   |
| pt_BR   | 2         | 1.39%   |
| pl_PL   | 2         | 1.39%   |
| fr_FR   | 2         | 1.39%   |
| en_AU   | 2         | 1.39%   |
| cs_CZ   | 2         | 1.39%   |
| ko_KR   | 1         | 0.69%   |
| fi_FI   | 1         | 0.69%   |
| et_EE   | 1         | 0.69%   |
| bg_BG   | 1         | 0.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 136       | 95.1%   |
| BIOS | 7         | 4.9%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ufs  | 128       | 90.14%  |
| Zfs  | 14        | 9.86%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 102       | 71.33%  |
| MBR  | 41        | 28.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 23        | 16.2%   |
| Hewlett-Packard     | 23        | 16.2%   |
| Dell                | 22        | 15.49%  |
| ASUSTek Computer    | 20        | 14.08%  |
| Acer                | 9         | 6.34%   |
| Gigabyte Technology | 6         | 4.23%   |
| ASRock              | 5         | 3.52%   |
| Apple               | 4         | 2.82%   |
| Sony                | 3         | 2.11%   |
| Intel               | 3         | 2.11%   |
| Samsung Electronics | 2         | 1.41%   |
| Pegatron            | 2         | 1.41%   |
| Notebook            | 2         | 1.41%   |
| Google              | 2         | 1.41%   |
| Fujitsu             | 2         | 1.41%   |
| Unknown             | 2         | 1.41%   |
| TUXEDO              | 1         | 0.7%    |
| Toshiba             | 1         | 0.7%    |
| Semp Toshiba        | 1         | 0.7%    |
| Panasonic           | 1         | 0.7%    |
| NEC Computers       | 1         | 0.7%    |
| MSI                 | 1         | 0.7%    |
| IBM                 | 1         | 0.7%    |
| GEO                 | 1         | 0.7%    |
| Fujitsu Siemens     | 1         | 0.7%    |
| Foxconn             | 1         | 0.7%    |
| Clevo               | 1         | 0.7%    |
| Alienware           | 1         | 0.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Unknown                                   | 3         | 2.11%   |
| Acer Veriton M460                         | 2         | 1.41%   |
| Toshiba Satellite C660                    | 1         | 0.7%    |
| Sony VPCM13M1R                            | 1         | 0.7%    |
| Sony VJS121C11N                           | 1         | 0.7%    |
| Sony SVE1713S1RW                          | 1         | 0.7%    |
| Semp Toshiba STI                          | 1         | 0.7%    |
| Samsung N145P/N250P/N260P                 | 1         | 0.7%    |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV   | 1         | 0.7%    |
| Pegatron T12Ah                            | 1         | 0.7%    |
| Pegatron Elite 7300 Series MT             | 1         | 0.7%    |
| Panasonic CF-C1BD06EFG                    | 1         | 0.7%    |
| Notebook W650DC,DD                        | 1         | 0.7%    |
| Notebook N650DU                           | 1         | 0.7%    |
| NEC Computers PC-GL186Y3AZ                | 1         | 0.7%    |
| MSI MS-N033                               | 1         | 0.7%    |
| Lenovo ThinkPad X380 Yoga 20LJ000WUK      | 1         | 0.7%    |
| Lenovo ThinkPad X201 Tablet 311396U       | 1         | 0.7%    |
| Lenovo ThinkPad X13 Yoga Gen 1 20SYS22H00 | 1         | 0.7%    |
| Lenovo ThinkPad X1 Yoga 3rd 20LDS1CG00    | 1         | 0.7%    |
| Lenovo ThinkPad X1 Carbon 4th 20FB001XAU  | 1         | 0.7%    |
| Lenovo ThinkPad W541 20EGS04800           | 1         | 0.7%    |
| Lenovo ThinkPad T530 24295VU              | 1         | 0.7%    |
| Lenovo ThinkPad T510 4384FF3              | 1         | 0.7%    |
| Lenovo ThinkPad T490s 20NX000DRT          | 1         | 0.7%    |
| Lenovo ThinkPad T490 20RYS06R00           | 1         | 0.7%    |
| Lenovo ThinkPad T470s W10DG 20JS001FGE    | 1         | 0.7%    |
| Lenovo ThinkPad T460 20FMS78014           | 1         | 0.7%    |
| Lenovo ThinkPad T450 20BUS06B00           | 1         | 0.7%    |
| Lenovo ThinkPad T440s 20AQ006HUS          | 1         | 0.7%    |
| Lenovo ThinkPad T440p 20AWS0VK00          | 1         | 0.7%    |
| Lenovo ThinkPad T430 2347C32              | 1         | 0.7%    |
| Lenovo ThinkPad S1 Yoga 20C0S0M300        | 1         | 0.7%    |
| Lenovo ThinkCentre M93p 10A8001HUS        | 1         | 0.7%    |
| Lenovo Legion Y7000 2019 PG0 81T0         | 1         | 0.7%    |
| Lenovo IdeaPad S145-15API 81UT            | 1         | 0.7%    |
| Lenovo IdeaPad 110-15IBR 80T7             | 1         | 0.7%    |
| Lenovo G570 20079                         | 1         | 0.7%    |
| Lenovo G50-45 80E3                        | 1         | 0.7%    |
| Intel NUC6i5SYB H81131-502                | 1         | 0.7%    |
| Intel NUC5i3RYB H41000-507                | 1         | 0.7%    |
| Intel DCP847SKE                           | 1         | 0.7%    |
| IBM 2647NG8                               | 1         | 0.7%    |
| HP ZBook Studio G3                        | 1         | 0.7%    |
| HP Z620 Workstation                       | 1         | 0.7%    |
| HP Z420 Workstation                       | 1         | 0.7%    |
| HP Spectre x360 Convertible 13-w0XX       | 1         | 0.7%    |
| HP ProBook x360 11 G6 EE                  | 1         | 0.7%    |
| HP ProBook 640 G1                         | 1         | 0.7%    |
| HP ProBook 450 G2                         | 1         | 0.7%    |
| HP Pavilion Notebook                      | 1         | 0.7%    |
| HP Pavilion g6                            | 1         | 0.7%    |
| HP Pavilion dv6000 (RP981EA#AB8)          | 1         | 0.7%    |
| HP OMEN by HP Laptop 17-cb1xxx            | 1         | 0.7%    |
| HP Notebook                               | 1         | 0.7%    |
| HP Laptop 15-db0xxx                       | 1         | 0.7%    |
| HP Laptop 15-da0xxx                       | 1         | 0.7%    |
| HP EliteBook 820 G1                       | 1         | 0.7%    |
| HP Desktop M01-F1xxx                      | 1         | 0.7%    |
| HP Compaq Elite 8300 Touch All-in-One PC  | 1         | 0.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 17        | 11.97%  |
| Dell Latitude              | 8         | 5.63%   |
| Acer Aspire                | 7         | 4.93%   |
| Dell OptiPlex              | 5         | 3.52%   |
| HP Compaq                  | 4         | 2.82%   |
| HP ProBook                 | 3         | 2.11%   |
| HP Pavilion                | 3         | 2.11%   |
| Dell Studio                | 3         | 2.11%   |
| Dell Inspiron              | 3         | 2.11%   |
| Unknown                    | 3         | 2.11%   |
| Lenovo IdeaPad             | 2         | 1.41%   |
| HP Laptop                  | 2         | 1.41%   |
| Gigabyte Z370              | 2         | 1.41%   |
| Gigabyte X570              | 2         | 1.41%   |
| Fujitsu LIFEBOOK           | 2         | 1.41%   |
| ASUS TUF                   | 2         | 1.41%   |
| ASUS PRIME                 | 2         | 1.41%   |
| Acer Veriton               | 2         | 1.41%   |
| Toshiba Satellite          | 1         | 0.7%    |
| Sony VPCM13M1R             | 1         | 0.7%    |
| Sony VJS121C11N            | 1         | 0.7%    |
| Sony SVE1713S1RW           | 1         | 0.7%    |
| Semp Toshiba STI           | 1         | 0.7%    |
| Samsung N145P              | 1         | 0.7%    |
| Samsung 300E5EV            | 1         | 0.7%    |
| Pegatron T12Ah             | 1         | 0.7%    |
| Pegatron Elite             | 1         | 0.7%    |
| Panasonic CF-C1BD06EFG     | 1         | 0.7%    |
| Notebook W650DC            | 1         | 0.7%    |
| Notebook N650DU            | 1         | 0.7%    |
| NEC Computers PC-GL186Y3AZ | 1         | 0.7%    |
| MSI MS-N033                | 1         | 0.7%    |
| Lenovo ThinkCentre         | 1         | 0.7%    |
| Lenovo Legion              | 1         | 0.7%    |
| Lenovo G570                | 1         | 0.7%    |
| Lenovo G50-45              | 1         | 0.7%    |
| Intel NUC6i5SYB            | 1         | 0.7%    |
| Intel NUC5i3RYB            | 1         | 0.7%    |
| Intel DCP847SKE            | 1         | 0.7%    |
| IBM 2647NG8                | 1         | 0.7%    |
| HP ZBook                   | 1         | 0.7%    |
| HP Z620                    | 1         | 0.7%    |
| HP Z420                    | 1         | 0.7%    |
| HP Spectre                 | 1         | 0.7%    |
| HP OMEN                    | 1         | 0.7%    |
| HP Notebook                | 1         | 0.7%    |
| HP EliteBook               | 1         | 0.7%    |
| HP Desktop                 | 1         | 0.7%    |
| HP 550-a114                | 1         | 0.7%    |
| HP 255                     | 1         | 0.7%    |
| HP 2000                    | 1         | 0.7%    |
| Google Lulu                | 1         | 0.7%    |
| Google Chell               | 1         | 0.7%    |
| Gigabyte X570S             | 1         | 0.7%    |
| Gigabyte MZGLKBP-00        | 1         | 0.7%    |
| GEO GeoBook3               | 1         | 0.7%    |
| Fujitsu Siemens AMILO      | 1         | 0.7%    |
| Foxconn Napa               | 1         | 0.7%    |
| Dell Vostro                | 1         | 0.7%    |
| Dell Precision             | 1         | 0.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 19        | 13.38%  |
| 2020 | 17        | 11.97%  |
| 2017 | 14        | 9.86%   |
| 2015 | 11        | 7.75%   |
| 2021 | 8         | 5.63%   |
| 2013 | 8         | 5.63%   |
| 2010 | 8         | 5.63%   |
| 2009 | 8         | 5.63%   |
| 2018 | 7         | 4.93%   |
| 2016 | 7         | 4.93%   |
| 2014 | 7         | 4.93%   |
| 2012 | 7         | 4.93%   |
| 2011 | 7         | 4.93%   |
| 2008 | 7         | 4.93%   |
| 2006 | 3         | 2.11%   |
| 2022 | 2         | 1.41%   |
| 2007 | 1         | 0.7%    |
| 2004 | 1         | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 89        | 62.68%  |
| Desktop     | 43        | 30.28%  |
| Convertible | 5         | 3.52%   |
| Mini pc     | 2         | 1.41%   |
| All in one  | 2         | 1.41%   |
| Server      | 1         | 0.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 140       | 98.59%  |
| Yes  | 2         | 1.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 54        | 37.76%  |
| 4.01-8.0    | 33        | 23.08%  |
| 16.01-24.0  | 30        | 20.98%  |
| 32.01-64.0  | 10        | 6.99%   |
| 64.01-256.0 | 5         | 3.5%    |
| 2.01-3.0    | 4         | 2.8%    |
| 3.01-4.0    | 3         | 2.1%    |
| 0.51-1.0    | 3         | 2.1%    |
| 24.01-32.0  | 1         | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 76        | 52.41%  |
| 0.51-1.0  | 42        | 28.97%  |
| 1.01-2.0  | 18        | 12.41%  |
| 2.01-3.0  | 5         | 3.45%   |
| 4.01-8.0  | 2         | 1.38%   |
| 3.01-4.0  | 1         | 0.69%   |
| 8.01-16.0 | 1         | 0.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 95        | 66.43%  |
| 2      | 26        | 18.18%  |
| 3      | 11        | 7.69%   |
| 0      | 7         | 4.9%    |
| 4      | 3         | 2.1%    |
| 7      | 1         | 0.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 82        | 57.34%  |
| Yes       | 61        | 42.66%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 131       | 91.61%  |
| No        | 12        | 8.39%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 116       | 81.69%  |
| No        | 26        | 18.31%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 56.64%  |
| No        | 62        | 43.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 32        | 22.54%  |
| Germany     | 18        | 12.68%  |
| Russia      | 15        | 10.56%  |
| France      | 14        | 9.86%   |
| UK          | 7         | 4.93%   |
| Italy       | 7         | 4.93%   |
| Turkey      | 5         | 3.52%   |
| Hungary     | 5         | 3.52%   |
| Mexico      | 3         | 2.11%   |
| Colombia    | 3         | 2.11%   |
| China       | 3         | 2.11%   |
| Thailand    | 2         | 1.41%   |
| Romania     | 2         | 1.41%   |
| Poland      | 2         | 1.41%   |
| Norway      | 2         | 1.41%   |
| Japan       | 2         | 1.41%   |
| Czechia     | 2         | 1.41%   |
| Brazil      | 2         | 1.41%   |
| Australia   | 2         | 1.41%   |
| Argentina   | 2         | 1.41%   |
| Ukraine     | 1         | 0.7%    |
| Spain       | 1         | 0.7%    |
| South Korea | 1         | 0.7%    |
| Slovakia    | 1         | 0.7%    |
| Serbia      | 1         | 0.7%    |
| Philippines | 1         | 0.7%    |
| Hong Kong   | 1         | 0.7%    |
| Finland     | 1         | 0.7%    |
| Estonia     | 1         | 0.7%    |
| Denmark     | 1         | 0.7%    |
| Bulgaria    | 1         | 0.7%    |
| Belarus     | 1         | 0.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Moscow                | 9         | 6.25%   |
| Franconville          | 6         | 4.17%   |
| Paris                 | 5         | 3.47%   |
| Hodmezovasarhely      | 5         | 3.47%   |
| Istanbul              | 4         | 2.78%   |
| Duncan                | 4         | 2.78%   |
| Woodland              | 3         | 2.08%   |
| Whittier              | 3         | 2.08%   |
| Tijuana               | 3         | 2.08%   |
| Milan                 | 3         | 2.08%   |
| Markt Indersdorf      | 3         | 2.08%   |
| Zwingenberg           | 2         | 1.39%   |
| Volzhskiy             | 2         | 1.39%   |
| St Petersburg         | 2         | 1.39%   |
| Setagaya-ku           | 2         | 1.39%   |
| Rome                  | 2         | 1.39%   |
| Rio de Janeiro        | 2         | 1.39%   |
| New Braunfels         | 2         | 1.39%   |
| McDonough             | 2         | 1.39%   |
| Los Angeles           | 2         | 1.39%   |
| Greenwich             | 2         | 1.39%   |
| Drobeta-Turnu Severin | 2         | 1.39%   |
| Cologne               | 2         | 1.39%   |
| Changzhou             | 2         | 1.39%   |
| Brisbane              | 2         | 1.39%   |
| BogotГЎ             | 2         | 1.39%   |
| Bangkok               | 2         | 1.39%   |
| Wloszczowa            | 1         | 0.69%   |
| Wissen                | 1         | 0.69%   |
| Winter Haven          | 1         | 0.69%   |
| Wilhelmshaven         | 1         | 0.69%   |
| Warsaw                | 1         | 0.69%   |
| Vollen                | 1         | 0.69%   |
| Vladimir              | 1         | 0.69%   |
| Vertou                | 1         | 0.69%   |
| Tucson                | 1         | 0.69%   |
| Trieste               | 1         | 0.69%   |
| Tallinn               | 1         | 0.69%   |
| Syracuse              | 1         | 0.69%   |
| Swindon               | 1         | 0.69%   |
| Suwon                 | 1         | 0.69%   |
| Southampton           | 1         | 0.69%   |
| Sofia                 | 1         | 0.69%   |
| Shanghai              | 1         | 0.69%   |
| Sedavi                | 1         | 0.69%   |
| Scottsdale            | 1         | 0.69%   |
| San Francisco         | 1         | 0.69%   |
| San Bernardino        | 1         | 0.69%   |
| Saint-Denis           | 1         | 0.69%   |
| Rionegro              | 1         | 0.69%   |
| Peoria                | 1         | 0.69%   |
| Pasig                 | 1         | 0.69%   |
| Palmer                | 1         | 0.69%   |
| Palm Bay              | 1         | 0.69%   |
| Oslo                  | 1         | 0.69%   |
| Nueve de Julio        | 1         | 0.69%   |
| Novosibirsk           | 1         | 0.69%   |
| Niederlauer           | 1         | 0.69%   |
| Munich                | 1         | 0.69%   |
| Mogilev               | 1         | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 40     | 17.93%  |
| WDC                 | 32        | 40     | 17.39%  |
| Seagate             | 27        | 30     | 14.67%  |
| Toshiba             | 19        | 22     | 10.33%  |
| Crucial             | 8         | 8      | 4.35%   |
| SanDisk             | 6         | 7      | 3.26%   |
| Kingston            | 6         | 6      | 3.26%   |
| SK hynix            | 5         | 6      | 2.72%   |
| Intel               | 5         | 5      | 2.72%   |
| Hitachi             | 5         | 5      | 2.72%   |
| Apple               | 5         | 6      | 2.72%   |
| A-DATA Technology   | 5         | 5      | 2.72%   |
| Micron Technology   | 3         | 3      | 1.63%   |
| Hewlett-Packard     | 3         | 3      | 1.63%   |
| Transcend           | 2         | 2      | 1.09%   |
| PNY                 | 2         | 2      | 1.09%   |
| OCZ                 | 2         | 2      | 1.09%   |
| Intenso             | 2         | 2      | 1.09%   |
| HGST                | 2         | 2      | 1.09%   |
| Gigabyte Technology | 2         | 2      | 1.09%   |
| Fujitsu             | 2         | 3      | 1.09%   |
| Team                | 1         | 1      | 0.54%   |
| SPCC                | 1         | 1      | 0.54%   |
| ORICO               | 1         | 1      | 0.54%   |
| Maxtor              | 1         | 1      | 0.54%   |
| LITEONIT            | 1         | 1      | 0.54%   |
| KingDian            | 1         | 1      | 0.54%   |
| Corsair             | 1         | 1      | 0.54%   |
| ASUSTek Computer    | 1         | 2      | 0.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB               | 3         | 1.52%   |
| Seagate ST1000LM049-2GH172 1TB       | 3         | 1.52%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 2         | 1.02%   |
| WDC WD40PURX-64GVNY0 4TB             | 2         | 1.02%   |
| WDC WD1600AAJS-22L7A0 160GB          | 2         | 1.02%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB | 2         | 1.02%   |
| Toshiba MQ01ABF050 500GB             | 2         | 1.02%   |
| Toshiba HDWD120 2TB                  | 2         | 1.02%   |
| Seagate ST95005620AS 500GB           | 2         | 1.02%   |
| Seagate ST9500325AS 500GB            | 2         | 1.02%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 1.02%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.02%   |
| SanDisk SSD U100 24GB                | 2         | 1.02%   |
| SanDisk pSSD 256GB                   | 2         | 1.02%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 1.02%   |
| Samsung SSD 970 EVO 500GB            | 2         | 1.02%   |
| Samsung SSD 870 QVO 2TB              | 2         | 1.02%   |
| Samsung SSD 840 EVO 250GB            | 2         | 1.02%   |
| Samsung MZVLB256HBHQ-000L7 256GB     | 2         | 1.02%   |
| Kingston SA400S37480G 480GB          | 2         | 1.02%   |
| Kingston SA400S37240G 240GB          | 2         | 1.02%   |
| HGST HTS725050A7E630 500GB           | 2         | 1.02%   |
| HP SSD EX950 2TB                     | 2         | 1.02%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 1.02%   |
| Crucial CT1000P1SSD8 1TB             | 2         | 1.02%   |
| Apple SSD SM0512F 500GB              | 2         | 1.02%   |
| A-DATA SU630 240GB                   | 2         | 1.02%   |
| WDC WDS240G2G0B-00EPW0 240GB         | 1         | 0.51%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 0.51%   |
| WDC WDS120G2G0B-00EPW0 120GB         | 1         | 0.51%   |
| WDC WDS120G2G0A-00JH30 120GB         | 1         | 0.51%   |
| WDC WDS120G1G0A-00SS50 120GB         | 1         | 0.51%   |
| WDC WD7500BPKT-75PK4T0 752GB         | 1         | 0.51%   |
| WDC WD6400AAKS-22A7B2 640GB          | 1         | 0.51%   |
| WDC WD60EZRZ-00GZ5B1 6TB             | 1         | 0.51%   |
| WDC WD40NMZW-11GX6S1 4TB             | 1         | 0.51%   |
| WDC WD3200BEVT-75ZCT2 320GB          | 1         | 0.51%   |
| WDC WD3200BEKT-60PVMT0 320GB         | 1         | 0.51%   |
| WDC WD2500LPCX-24C6HT0 250GB         | 1         | 0.51%   |
| WDC WD2500BEVT-80A23T0 250GB         | 1         | 0.51%   |
| WDC WD2500BEKT-00PVMT0 250GB         | 1         | 0.51%   |
| WDC WD2004FBYZ-01YCBB1 2TB           | 1         | 0.51%   |
| WDC WD1200BEVS-07LAT0 120GB          | 1         | 0.51%   |
| WDC WD1200BEVE-00UYT0 120GB          | 1         | 0.51%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.51%   |
| WDC WD10SPZX-00Z10T0 1TB             | 1         | 0.51%   |
| WDC WD10SMRW-11Y43S0 1TB             | 1         | 0.51%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.51%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 0.51%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.51%   |
| WDC WD10JPLX-00MBPT0 1TB             | 1         | 0.51%   |
| WDC WD10EZRZ-00HTKB0 1TB             | 1         | 0.51%   |
| WDC WD10EZRX-00L4HB0 1TB             | 1         | 0.51%   |
| WDC WD10EFRX-68PJCN0 1TB             | 1         | 0.51%   |
| WDC WD10EADS-00P8B0 1TB              | 1         | 0.51%   |
| WDC PC SN720 SDAPNTW-1T00-1006 1TB   | 1         | 0.51%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB | 1         | 0.51%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB | 1         | 0.51%   |
| Transcend TS512GSSD370S 512GB        | 1         | 0.51%   |
| Transcend TS32GCF800 32GB            | 1         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 30     | 32.53%  |
| WDC                 | 25        | 28     | 30.12%  |
| Toshiba             | 15        | 17     | 18.07%  |
| Hitachi             | 5         | 5      | 6.02%   |
| Samsung Electronics | 4         | 4      | 4.82%   |
| HGST                | 2         | 2      | 2.41%   |
| Fujitsu             | 2         | 3      | 2.41%   |
| Maxtor              | 1         | 1      | 1.2%    |
| Hewlett-Packard     | 1         | 1      | 1.2%    |
| Apple               | 1         | 1      | 1.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 19     | 21.43%  |
| SanDisk             | 6         | 7      | 8.57%   |
| Kingston            | 5         | 5      | 7.14%   |
| Crucial             | 5         | 5      | 7.14%   |
| A-DATA Technology   | 5         | 5      | 7.14%   |
| WDC                 | 4         | 5      | 5.71%   |
| Apple               | 4         | 5      | 5.71%   |
| Toshiba             | 3         | 3      | 4.29%   |
| Intel               | 3         | 3      | 4.29%   |
| Transcend           | 2         | 2      | 2.86%   |
| SK hynix            | 2         | 2      | 2.86%   |
| PNY                 | 2         | 2      | 2.86%   |
| OCZ                 | 2         | 2      | 2.86%   |
| Micron Technology   | 2         | 2      | 2.86%   |
| Intenso             | 2         | 2      | 2.86%   |
| Gigabyte Technology | 2         | 2      | 2.86%   |
| Team                | 1         | 1      | 1.43%   |
| SPCC                | 1         | 1      | 1.43%   |
| LITEONIT            | 1         | 1      | 1.43%   |
| KingDian            | 1         | 1      | 1.43%   |
| Corsair             | 1         | 1      | 1.43%   |
| ASUSTek Computer    | 1         | 2      | 1.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 72        | 92     | 43.37%  |
| SSD  | 62        | 78     | 37.35%  |
| NVMe | 32        | 40     | 19.28%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 119       | 170    | 78.81%  |
| NVMe | 32        | 40     | 21.19%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 87        | 110    | 62.14%  |
| 0.51-1.0   | 37        | 42     | 26.43%  |
| 1.01-2.0   | 8         | 8      | 5.71%   |
| 3.01-4.0   | 4         | 4      | 2.86%   |
| 2.01-3.0   | 3         | 3      | 2.14%   |
| 4.01-10.0  | 1         | 3      | 0.71%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 119       | 83.8%   |
| 101-250    | 12        | 8.45%   |
| 51-100     | 5         | 3.52%   |
| 251-500    | 2         | 1.41%   |
| 21-50      | 2         | 1.41%   |
| 501-1000   | 2         | 1.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 138       | 96.5%   |
| 21-50   | 3         | 2.1%    |
| 51-100  | 2         | 1.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPKT-75PK4T0 752GB                     | 1         | 1      | 3.45%   |
| WDC WD40PURX-64GVNY0 4TB                         | 1         | 1      | 3.45%   |
| WDC WD2500BEVT-80A23T0 250GB                     | 1         | 1      | 3.45%   |
| WDC WD1200BEVS-07LAT0 120GB                      | 1         | 1      | 3.45%   |
| WDC WD10JPVX-75JC3T0 1TB                         | 1         | 1      | 3.45%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 3.45%   |
| WDC WD10EFRX-68PJCN0 1TB                         | 1         | 2      | 3.45%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 3.45%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 3.45%   |
| Toshiba MK7575GSX 752GB                          | 1         | 1      | 3.45%   |
| Toshiba HDWD120 2TB                              | 1         | 1      | 3.45%   |
| Toshiba DT01ABA300 3TB                           | 1         | 1      | 3.45%   |
| Seagate ST95005620AS 500GB                       | 1         | 1      | 3.45%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 3.45%   |
| Seagate ST500LM021-1KJ152 500GB                  | 1         | 1      | 3.45%   |
| Seagate ST500DM002-1BD142 500GB                  | 1         | 1      | 3.45%   |
| Seagate ST3250823AS 250GB                        | 1         | 1      | 3.45%   |
| SanDisk SD9SN8W-128G-1006 128GB                  | 1         | 1      | 3.45%   |
| Samsung Electronics SSD PM810 2.5-inch 7mm 256GB | 1         | 1      | 3.45%   |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 3.45%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB       | 1         | 1      | 3.45%   |
| Intenso SSD Sata III 128GB                       | 1         | 1      | 3.45%   |
| Intel SSDSC2CW060A3 64GB                         | 1         | 1      | 3.45%   |
| Hitachi HTS545032B9A302 320GB                    | 1         | 1      | 3.45%   |
| Hitachi HTS545032B9A300 320GB                    | 1         | 1      | 3.45%   |
| HGST HTS725050A7E630 500GB                       | 1         | 1      | 3.45%   |
| Hewlett-Packard MB1000GCWCV 1TB                  | 1         | 1      | 3.45%   |
| Corsair Neutron GTX SSD 120GB                    | 1         | 1      | 3.45%   |
| A-DATA Technology XM13 32GB                      | 1         | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 8      | 24.14%  |
| Toshiba             | 5         | 5      | 17.24%  |
| Seagate             | 5         | 5      | 17.24%  |
| Samsung Electronics | 2         | 2      | 6.9%    |
| Hitachi             | 2         | 2      | 6.9%    |
| SanDisk             | 1         | 1      | 3.45%   |
| Micron Technology   | 1         | 1      | 3.45%   |
| Intenso             | 1         | 1      | 3.45%   |
| Intel               | 1         | 1      | 3.45%   |
| HGST                | 1         | 1      | 3.45%   |
| Hewlett-Packard     | 1         | 1      | 3.45%   |
| Corsair             | 1         | 1      | 3.45%   |
| A-DATA Technology   | 1         | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 8      | 31.82%  |
| Toshiba             | 5         | 5      | 22.73%  |
| Seagate             | 5         | 5      | 22.73%  |
| Hitachi             | 2         | 2      | 9.09%   |
| Samsung Electronics | 1         | 1      | 4.55%   |
| HGST                | 1         | 1      | 4.55%   |
| Hewlett-Packard     | 1         | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 23     | 75%     |
| SSD  | 7         | 7      | 25%     |

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
| Works    | 115       | 172    | 79.31%  |
| Malfunc  | 28        | 30     | 19.31%  |
| Detected | 2         | 8      | 1.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 103       | 58.86%  |
| AMD                              | 24        | 13.71%  |
| Samsung Electronics              | 19        | 10.86%  |
| SanDisk                          | 7         | 4%      |
| ASMedia Technology               | 5         | 2.86%   |
| Micron/Crucial Technology        | 3         | 1.71%   |
| VIA Technologies                 | 2         | 1.14%   |
| SK hynix                         | 2         | 1.14%   |
| Nvidia                           | 2         | 1.14%   |
| Biwin Storage Technology         | 2         | 1.14%   |
| Toshiba                          | 1         | 0.57%   |
| Silicon Motion                   | 1         | 0.57%   |
| Silicon Integrated Systems [SiS] | 1         | 0.57%   |
| Micron Technology                | 1         | 0.57%   |
| Kingston Technology Company      | 1         | 0.57%   |
| JMicron Technology               | 1         | 0.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 19        | 9.22%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 12        | 5.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 11        | 5.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 3.4%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 3.4%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 2.91%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 5         | 2.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 2.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 2.43%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 5         | 2.43%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 4         | 1.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 1.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 1.94%   |
| Unknown                                                                          | 4         | 1.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.46%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.46%   |
| Intel SATA Controller [RAID mode]                                                | 3         | 1.46%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 1.46%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.46%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 1.46%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 2         | 0.97%   |
| SanDisk PC SN520 NVMe SSD                                                        | 2         | 0.97%   |
| Samsung SM951 AHCI                                                               | 2         | 0.97%   |
| Samsung Apple PCIe SSD                                                           | 2         | 0.97%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 0.97%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.97%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 2         | 0.97%   |
| Intel C600/X79 series chipset IDE-r Controller                                   | 2         | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.97%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2         | 0.97%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2         | 0.97%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 2         | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 0.97%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 0.97%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 2         | 0.97%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 2         | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 0.97%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 2         | 0.97%   |
| AMD 500 Series Chipset SATA Controller                                           | 2         | 0.97%   |
| AMD 400 Series Chipset SATA Controller                                           | 2         | 0.97%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.49%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 0.49%   |
| VIA VT6421 IDE/SATA Controller                                                   | 1         | 0.49%   |
| Toshiba unknown                                                                  | 1         | 0.49%   |
| SK hynix hynix unknown                                                           | 1         | 0.49%   |
| SK hynix BC511                                                                   | 1         | 0.49%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.49%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.49%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.49%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.49%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.49%   |
| Nvidia MCP73 SATA Controller (IDE mode)                                          | 1         | 0.49%   |
| Nvidia MCP73 IDE Controller                                                      | 1         | 0.49%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 0.49%   |
| Nvidia MCP61 IDE                                                                 | 1         | 0.49%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1         | 0.49%   |
| Micron/Crucial NVMe Controller                                                   | 1         | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 101       | 57.39%  |
| NVMe | 32        | 18.18%  |
| IDE  | 28        | 15.91%  |
| RAID | 13        | 7.39%   |
| SAS  | 2         | 1.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 118       | 82.52%  |
| AMD    | 25        | 17.48%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 2.8%    |
| Intel Core i7-4600U CPU @ 2.10GHz           | 3         | 2.1%    |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 2.1%    |
| Intel CPU Version                           | 2         | 1.4%    |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 2         | 1.4%    |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 1.4%    |
| Intel Core i5-8350U CPU @ 1.70GHz           | 2         | 1.4%    |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.4%    |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.4%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2         | 1.4%    |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.4%    |
| Intel Core i5-2430M CPU @ 2.40GHz           | 2         | 1.4%    |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 2         | 1.4%    |
| Intel Core 2 Duo                            | 2         | 1.4%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 2         | 1.4%    |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2         | 1.4%    |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 1.4%    |
| Intel Xeon CPU E5640 @ 2.67GHz              | 1         | 0.7%    |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1         | 0.7%    |
| Intel Xeon CPU E5-2670 @ 2.60GHz            | 1         | 0.7%    |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz         | 1         | 0.7%    |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz        | 1         | 0.7%    |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1         | 0.7%    |
| Intel Pentium III                           | 1         | 0.7%    |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1         | 0.7%    |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1         | 0.7%    |
| Intel Pentium D CPU 2.80GHz                 | 1         | 0.7%    |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 0.7%    |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.7%    |
| Intel Pentium CPU 2117U @ 1.80GHz           | 1         | 0.7%    |
| Intel Genuine CPU U7300 @ 1.30GHz           | 1         | 0.7%    |
| Intel Core m5-6Y57 CPU @ 1.10GHz            | 1         | 0.7%    |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 0.7%    |
| Intel Core i9-7960X CPU @ 2.80GHz           | 1         | 0.7%    |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1         | 0.7%    |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.7%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.7%    |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.7%    |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 0.7%    |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 0.7%    |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 0.7%    |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.7%    |
| Intel Core i7-4900MQ CPU @ 2.80GHz          | 1         | 0.7%    |
| Intel Core i7-4850HQ CPU @ 2.30GHz          | 1         | 0.7%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.7%    |
| Intel Core i7-4770HQ CPU @ 2.20GHz          | 1         | 0.7%    |
| Intel Core i7-4650U CPU @ 1.70GHz           | 1         | 0.7%    |
| Intel Core i7-4610M CPU @ 3.00GHz           | 1         | 0.7%    |
| Intel Core i7-4510U CPU @ 2.00GHz           | 1         | 0.7%    |
| Intel Core i7-4500U CPU @ 1.80GHz           | 1         | 0.7%    |
| Intel Core i7-4500U CPU                     | 1         | 0.7%    |
| Intel Core i7-3537U CPU @ 2.00GHz           | 1         | 0.7%    |
| Intel Core i7-2820QM CPU @ 2.30GHz          | 1         | 0.7%    |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 0.7%    |
| Intel Core i7-10610U CPU @ 1.80GHz          | 1         | 0.7%    |
| Intel Core i7 CPU L 640 @ 2.13GHz           | 1         | 0.7%    |
| Intel Core i7 CPU 920 @ 2.67GHz             | 1         | 0.7%    |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1         | 0.7%    |
| Intel Core i5-9300HF CPU @ 2.40GHz          | 1         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 40        | 27.97%  |
| Intel Core i7           | 32        | 22.38%  |
| Intel Core 2 Duo        | 10        | 6.99%   |
| Intel Core i3           | 8         | 5.59%   |
| AMD Ryzen 5             | 8         | 5.59%   |
| Intel Xeon              | 5         | 3.5%    |
| Other                   | 4         | 2.8%    |
| Intel Pentium           | 3         | 2.1%    |
| Intel Celeron           | 3         | 2.1%    |
| Intel Atom              | 3         | 2.1%    |
| AMD Ryzen 7             | 3         | 2.1%    |
| AMD A8                  | 3         | 2.1%    |
| AMD A6                  | 3         | 2.1%    |
| Intel Pentium Dual-Core | 2         | 1.4%    |
| Intel Core i9           | 2         | 1.4%    |
| AMD Ryzen 9             | 2         | 1.4%    |
| AMD Athlon 64 X2        | 2         | 1.4%    |
| Intel Pentium Silver    | 1         | 0.7%    |
| Intel Pentium III       | 1         | 0.7%    |
| Intel Pentium D         | 1         | 0.7%    |
| Intel Genuine           | 1         | 0.7%    |
| Intel Core m5           | 1         | 0.7%    |
| Intel Core 2            | 1         | 0.7%    |
| Intel Celeron M         | 1         | 0.7%    |
| AMD FX                  | 1         | 0.7%    |
| AMD E1                  | 1         | 0.7%    |
| AMD A10                 | 1         | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 62        | 43.36%  |
| 4       | 46        | 32.17%  |
| 8       | 9         | 6.29%   |
| Unknown | 9         | 6.29%   |
| 6       | 6         | 4.2%    |
| 12      | 4         | 2.8%    |
| 1       | 3         | 2.1%    |
| 24      | 2         | 1.4%    |
| 16      | 2         | 1.4%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 141       | 99.3%   |
| 2      | 1         | 0.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 80        | 55.94%  |
| 1       | 52        | 36.36%  |
| Unknown | 11        | 7.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 26        | 18.18%  |
| Haswell       | 18        | 12.59%  |
| Skylake       | 14        | 9.79%   |
| Penryn        | 13        | 9.09%   |
| IvyBridge     | 12        | 8.39%   |
| SandyBridge   | 10        | 6.99%   |
| Zen+          | 5         | 3.5%    |
| Puma          | 5         | 3.5%    |
| Broadwell     | 4         | 2.8%    |
| Bonnell       | 4         | 2.8%    |
| Zen           | 3         | 2.1%    |
| Westmere      | 3         | 2.1%    |
| Nehalem       | 3         | 2.1%    |
| Core          | 3         | 2.1%    |
| Zen 3         | 2         | 1.4%    |
| Zen 2         | 2         | 1.4%    |
| Silvermont    | 2         | 1.4%    |
| P6            | 2         | 1.4%    |
| K8 Hammer     | 2         | 1.4%    |
| Goldmont plus | 2         | 1.4%    |
| Steamroller   | 1         | 0.7%    |
| Piledriver    | 1         | 0.7%    |
| NetBurst      | 1         | 0.7%    |
| K10 Llano     | 1         | 0.7%    |
| Jaguar        | 1         | 0.7%    |
| Excavator     | 1         | 0.7%    |
| CometLake     | 1         | 0.7%    |
| Unknown       | 1         | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 88        | 56.77%  |
| AMD                        | 35        | 22.58%  |
| Nvidia                     | 29        | 18.71%  |
| VIA Technologies           | 1         | 0.65%   |
| S3 Graphics                | 1         | 0.65%   |
| Matrox Electronics Systems | 1         | 0.65%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 5.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 5%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 5%      |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 4.38%   |
| Intel UHD Graphics 620                                                                   | 5         | 3.13%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 4         | 2.5%    |
| Intel HD Graphics 620                                                                    | 4         | 2.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 2.5%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.5%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 2.5%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.88%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.88%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 1.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.25%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 1.25%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.25%   |
| Intel HD Graphics 630                                                                    | 2         | 1.25%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.25%   |
| Intel HD Graphics 530                                                                    | 2         | 1.25%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.25%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.25%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 1.25%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2         | 1.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.25%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 1.25%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.63%   |
| S3 Graphics SuperSavage IX/C SDR                                                         | 1         | 0.63%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.63%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.63%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 0.63%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.63%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.63%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 1         | 0.63%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.63%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.63%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.63%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.63%   |
| Nvidia GM107GL [Quadro K2200]                                                            | 1         | 0.63%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 1         | 0.63%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.63%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 1         | 0.63%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 0.63%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.63%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                                     | 1         | 0.63%   |
| Nvidia GF114M [GeForce GTX 580M]                                                         | 1         | 0.63%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.63%   |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 1         | 0.63%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 0.63%   |
| Nvidia G72M [GeForce Go 7400]                                                            | 1         | 0.63%   |
| Nvidia G72 [GeForce 7300 LE]                                                             | 1         | 0.63%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1         | 0.63%   |
| Intel UHD Graphics 615                                                                   | 1         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.63%   |
| Intel Iris Graphics 540                                                                  | 1         | 0.63%   |
| Intel HD Graphics P530                                                                   | 1         | 0.63%   |
| Intel HD Graphics 6000                                                                   | 1         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 70        | 48.95%  |
| 1 x AMD         | 31        | 21.68%  |
| 1 x Nvidia      | 19        | 13.29%  |
| Intel + Nvidia  | 9         | 6.29%   |
| 2 x Intel       | 7         | 4.9%    |
| Intel + AMD     | 2         | 1.4%    |
| 2 x AMD         | 1         | 0.7%    |
| 1 x VIA         | 1         | 0.7%    |
| 1 x S3 Graphics | 1         | 0.7%    |
| 1 x Matrox      | 1         | 0.7%    |
| AMD + Nvidia    | 1         | 0.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 112       | 78.87%  |
| Proprietary | 15        | 10.56%  |
| Unknown     | 15        | 10.56%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 111       | 77.62%  |
| 0.01-0.5   | 10        | 6.99%   |
| 1.01-2.0   | 8         | 5.59%   |
| 0.51-1.0   | 5         | 3.5%    |
| 5.01-6.0   | 4         | 2.8%    |
| 3.01-4.0   | 3         | 2.1%    |
| 7.01-8.0   | 2         | 1.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 14        | 11.29%  |
| Samsung Electronics     | 13        | 10.48%  |
| AU Optronics            | 13        | 10.48%  |
| BOE                     | 12        | 9.68%   |
| Goldstar                | 9         | 7.26%   |
| Dell                    | 8         | 6.45%   |
| Chimei Innolux          | 8         | 6.45%   |
| Acer                    | 6         | 4.84%   |
| Hewlett-Packard         | 5         | 4.03%   |
| Sharp                   | 3         | 2.42%   |
| Lenovo                  | 3         | 2.42%   |
| HannStar                | 3         | 2.42%   |
| Chi Mei Optoelectronics | 3         | 2.42%   |
| Apple                   | 3         | 2.42%   |
| Philips                 | 2         | 1.61%   |
| Panasonic               | 2         | 1.61%   |
| BenQ                    | 2         | 1.61%   |
| ASUSTek Computer        | 2         | 1.61%   |
| Ancor Communications    | 2         | 1.61%   |
| ___                     | 1         | 0.81%   |
| Westinghouse            | 1         | 0.81%   |
| Vizio                   | 1         | 0.81%   |
| ViewSonic               | 1         | 0.81%   |
| Toshiba                 | 1         | 0.81%   |
| Sony                    | 1         | 0.81%   |
| NEC Computers           | 1         | 0.81%   |
| LG Philips              | 1         | 0.81%   |
| LG Electronics          | 1         | 0.81%   |
| CPT                     | 1         | 0.81%   |
| AOC                     | 1         | 0.81%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch          | 2         | 1.59%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 2         | 1.59%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch             | 2         | 1.59%   |
| BOE LCD Monitor BOE0671 1366x768 340x190mm 15.3-inch                  | 2         | 1.59%   |
| AU Optronics LCD Monitor AUO8174 1280x800 330x210mm 15.4-inch         | 2         | 1.59%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch         | 2         | 1.59%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 2         | 1.59%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch          | 2         | 1.59%   |
| ___ MY TV LED TV ___0101 1920x1080                                    | 1         | 0.79%   |
| Westinghouse DWM40F3G1 WET1ECC 1920x1080 880x480mm 39.5-inch          | 1         | 0.79%   |
| Vizio SV370XVT VIZ0057 1920x1080 820x460mm 37.0-inch                  | 1         | 0.79%   |
| ViewSonic VX910 VSC3C19 1280x1024 380x300mm 19.1-inch                 | 1         | 0.79%   |
| Toshiba LCD-MONITOR LCDC980 1280x1024 380x300mm 19.1-inch             | 1         | 0.79%   |
| Sony TV SNY5D01 1360x768                                              | 1         | 0.79%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch               | 1         | 0.79%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch               | 1         | 0.79%   |
| Sharp LCD Monitor SHP140E 2560x1440 290x170mm 13.2-inch               | 1         | 0.79%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch     | 1         | 0.79%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 410x260mm 19.1-inch   | 1         | 0.79%   |
| Samsung Electronics S27E330 SAM0D91 1920x1080 600x340mm 27.2-inch     | 1         | 0.79%   |
| Samsung Electronics LF24T450F SAM7094 1920x1080 530x300mm 24.0-inch   | 1         | 0.79%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                     | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 220x130mm 10.1-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 290x160mm 13.0-inch | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 310x170mm 13.9-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 290x160mm 13.0-inch | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch  | 1         | 0.79%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 1         | 0.79%   |
| Philips 170S PHL0856 1280x1024 340x270mm 17.1-inch                    | 1         | 0.79%   |
| NEC Computers EA223WM NEC6890 1680x1050 470x300mm 22.0-inch           | 1         | 0.79%   |
| LG Philips LCD Monitor LPLA101 1440x900 370x230mm 17.2-inch           | 1         | 0.79%   |
| LG Electronics LCD Monitor LG HDR QHD 2560x1440                       | 1         | 0.79%   |
| LG Display LCD Monitor LGD7001 1366x768 340x190mm 15.3-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD6301 1366x768 340x190mm 15.3-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD05B3 1920x1080 290x170mm 13.2-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD0414 1920x1080 280x160mm 12.7-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD040A 1920x1080 310x170mm 13.9-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD034D 1366x768 340x190mm 15.3-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD0303 1600x900 380x210mm 17.1-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD01F7 1366x768 290x160mm 13.0-inch           | 1         | 0.79%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch               | 1         | 0.79%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch               | 1         | 0.79%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch               | 1         | 0.79%   |
| Hewlett-Packard W2072a HWP299F 1600x900 440x250mm 19.9-inch           | 1         | 0.79%   |
| Hewlett-Packard vs17 HWP2647 1280x1024 340x270mm 17.1-inch            | 1         | 0.79%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch           | 1         | 0.79%   |
| Hewlett-Packard HPQ 8300 AiO HWP4212 1920x1080 510x290mm 23.1-inch    | 1         | 0.79%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch            | 1         | 0.79%   |
| HannStar LCD Monitor HSD0013 1280x1024 380x300mm 19.1-inch            | 1         | 0.79%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                  | 1         | 0.79%   |
| Goldstar W1943 GSM4BAD 1360x768 410x230mm 18.5-inch                   | 1         | 0.79%   |
| Goldstar LG UltraFine GSM5B10 3840x2160 480x270mm 21.7-inch           | 1         | 0.79%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch            | 1         | 0.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 40        | 32.79%  |
| 1366x768 (WXGA)    | 33        | 27.05%  |
| 1280x1024 (SXGA)   | 11        | 9.02%   |
| 1600x900 (HD+)     | 7         | 5.74%   |
| 3840x2160 (4K)     | 5         | 4.1%    |
| 1440x900 (WXGA+)   | 4         | 3.28%   |
| 1280x800 (WXGA)    | 4         | 3.28%   |
| 1024x600           | 4         | 3.28%   |
| 2560x1440 (QHD)    | 3         | 2.46%   |
| 2880x1620          | 2         | 1.64%   |
| 1920x1200 (WUXGA)  | 2         | 1.64%   |
| 1680x1050 (WSXGA+) | 2         | 1.64%   |
| 1360x768           | 2         | 1.64%   |
| 3200x1800 (QHD+)   | 1         | 0.82%   |
| 2880x1800          | 1         | 0.82%   |
| 1600x1200          | 1         | 0.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 32        | 25.6%   |
| 13      | 20        | 16%     |
| 17      | 12        | 9.6%    |
| 24      | 10        | 8%      |
| 19      | 9         | 7.2%    |
| 21      | 7         | 5.6%    |
| 12      | 7         | 5.6%    |
| 27      | 6         | 4.8%    |
| 10      | 4         | 3.2%    |
| Unknown | 4         | 3.2%    |
| 18      | 3         | 2.4%    |
| 11      | 3         | 2.4%    |
| 23      | 2         | 1.6%    |
| 22      | 2         | 1.6%    |
| 39      | 1         | 0.8%    |
| 37      | 1         | 0.8%    |
| 25      | 1         | 0.8%    |
| 14      | 1         | 0.8%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 49        | 39.84%  |
| 201-300     | 24        | 19.51%  |
| 501-600     | 16        | 13.01%  |
| 401-500     | 15        | 12.2%   |
| 351-400     | 11        | 8.94%   |
| Unknown     | 4         | 3.25%   |
| 801-900     | 2         | 1.63%   |
| 601-700     | 2         | 1.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 89        | 76.72%  |
| 16/10   | 14        | 12.07%  |
| 5/4     | 11        | 9.48%   |
| Unknown | 2         | 1.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 25        | 20%     |
| 201-250        | 20        | 16%     |
| 81-90          | 14        | 11.2%   |
| 151-200        | 9         | 7.2%    |
| 141-150        | 9         | 7.2%    |
| 71-80          | 7         | 5.6%    |
| 61-70          | 7         | 5.6%    |
| 101-110        | 7         | 5.6%    |
| 301-350        | 6         | 4.8%    |
| 121-130        | 5         | 4%      |
| 41-50          | 4         | 3.2%    |
| Unknown        | 4         | 3.2%    |
| 51-60          | 3         | 2.4%    |
| 251-300        | 2         | 1.6%    |
| 501-1000       | 2         | 1.6%    |
| 131-140        | 1         | 0.8%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 41        | 34.17%  |
| 51-100        | 36        | 30%     |
| 121-160       | 25        | 20.83%  |
| 161-240       | 12        | 10%     |
| Unknown       | 4         | 3.33%   |
| More than 240 | 2         | 1.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 108       | 75%     |
| 0     | 26        | 18.06%  |
| 2     | 8         | 5.56%   |
| 3     | 2         | 1.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 80        | 38.65%  |
| Realtek Semiconductor             | 59        | 28.5%   |
| Qualcomm Atheros                  | 29        | 14.01%  |
| Broadcom                          | 14        | 6.76%   |
| Ralink                            | 3         | 1.45%   |
| Qualcomm                          | 2         | 0.97%   |
| Mellanox Technologies             | 2         | 0.97%   |
| Marvell Technology Group          | 2         | 0.97%   |
| Fibocom                           | 2         | 0.97%   |
| VIA Technologies                  | 1         | 0.48%   |
| TP-Link                           | 1         | 0.48%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.48%   |
| Sierra Wireless                   | 1         | 0.48%   |
| Samsung Electronics               | 1         | 0.48%   |
| Ralink Technology                 | 1         | 0.48%   |
| Nvidia                            | 1         | 0.48%   |
| Microchip Technology              | 1         | 0.48%   |
| JMicron Technology                | 1         | 0.48%   |
| Ericsson Business Mobile Networks | 1         | 0.48%   |
| Edimax Technology                 | 1         | 0.48%   |
| D-Link System                     | 1         | 0.48%   |
| Brooktrout Technology             | 1         | 0.48%   |
| Atheros                           | 1         | 0.48%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38        | 14.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 4.83%   |
| Intel Wireless 7260                                               | 10        | 3.72%   |
| Intel Wireless 8265 / 8275                                        | 7         | 2.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.6%    |
| Intel Wireless 8260                                               | 6         | 2.23%   |
| Intel Wireless 3165                                               | 6         | 2.23%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 2.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.86%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.86%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 1.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 1.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.49%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 4         | 1.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 1.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.12%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 1.12%   |
| Intel Wireless 7265                                               | 3         | 1.12%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.12%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.12%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.12%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 1.12%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 2         | 0.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.74%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 2         | 0.74%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 2         | 0.74%   |
| Intel Wireless-AC 9260                                            | 2         | 0.74%   |
| Intel WiFi Link 5100                                              | 2         | 0.74%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.74%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 2         | 0.74%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.74%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.74%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.74%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.74%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.74%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.74%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                 | 2         | 0.74%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 0.74%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.37%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.37%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.37%   |
| Sierra Wireless EM7455                                            | 1         | 0.37%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.37%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.37%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.37%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1         | 0.37%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.37%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.37%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.37%   |
| Realtek Realtek Bluetooth 4.2 Adapter                             | 1         | 0.37%   |
| Ralink RT5372 Wireless Adapter                                    | 1         | 0.37%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 60        | 49.18%  |
| Qualcomm Atheros      | 23        | 18.85%  |
| Realtek Semiconductor | 21        | 17.21%  |
| Broadcom              | 9         | 7.38%   |
| Ralink                | 3         | 2.46%   |
| TP-Link               | 1         | 0.82%   |
| Sierra Wireless       | 1         | 0.82%   |
| Ralink Technology     | 1         | 0.82%   |
| Edimax Technology     | 1         | 0.82%   |
| D-Link System         | 1         | 0.82%   |
| Atheros               | 1         | 0.82%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                                   | 10        | 8%      |
| Intel Wireless 8265 / 8275                                                            | 7         | 5.6%    |
| Intel Wireless 8260                                                                   | 6         | 4.8%    |
| Intel Wireless 3165                                                                   | 6         | 4.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 5         | 4%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 5         | 4%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 4         | 3.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 4         | 3.2%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 4         | 3.2%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 3         | 2.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 3         | 2.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 3         | 2.4%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 3         | 2.4%    |
| Intel Wireless 7265                                                                   | 3         | 2.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 3         | 2.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 3         | 2.4%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 2         | 1.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 1.6%    |
| Intel Wireless-AC 9260                                                                | 2         | 1.6%    |
| Intel WiFi Link 5100                                                                  | 2         | 1.6%    |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 1.6%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 2         | 1.6%    |
| Intel Centrino Advanced-N 6200                                                        | 2         | 1.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 2         | 1.6%    |
| Broadcom BCM43142 802.11b/g/n                                                         | 2         | 1.6%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 0.8%    |
| Sierra Wireless EM7455                                                                | 1         | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1         | 0.8%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.8%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1         | 0.8%    |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 0.8%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1         | 0.8%    |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 0.8%    |
| Realtek Realtek Bluetooth 4.2 Adapter                                                 | 1         | 0.8%    |
| Ralink RT5372 Wireless Adapter                                                        | 1         | 0.8%    |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 1         | 0.8%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.8%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.8%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.8%    |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.8%    |
| Intel WiMAX/WiFi Link 5150                                                            | 1         | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 0.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 0.8%    |
| Intel Centrino Wireless-N 6150                                                        | 1         | 0.8%    |
| Intel Centrino Wireless-N 135                                                         | 1         | 0.8%    |
| Intel Centrino Wireless-N 105                                                         | 1         | 0.8%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                         | 1         | 0.8%    |
| Intel Centrino WiMAX 6150                                                             | 1         | 0.8%    |
| Intel Centrino Ultimate-N 6300                                                        | 1         | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 1         | 0.8%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                        | 1         | 0.8%    |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]                  | 1         | 0.8%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                           | 1         | 0.8%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                    | 1         | 0.8%    |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 1         | 0.8%    |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller                   | 1         | 0.8%    |
| Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]                  | 1         | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 55        | 41.04%  |
| Intel                            | 54        | 40.3%   |
| Qualcomm Atheros                 | 8         | 5.97%   |
| Broadcom                         | 8         | 5.97%   |
| Qualcomm                         | 2         | 1.49%   |
| Marvell Technology Group         | 2         | 1.49%   |
| VIA Technologies                 | 1         | 0.75%   |
| Silicon Integrated Systems [SiS] | 1         | 0.75%   |
| Samsung Electronics              | 1         | 0.75%   |
| Nvidia                           | 1         | 0.75%   |
| JMicron Technology               | 1         | 0.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38        | 27.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 9.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 5.11%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 4.38%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 3.65%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 3.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 2.92%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.19%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 2.19%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 2.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.46%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 2         | 1.46%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.46%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.46%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.46%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.46%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.46%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.73%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.73%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.73%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.73%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.73%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.73%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.73%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.73%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.73%   |
| Nvidia MCP73 Ethernet                                             | 1         | 0.73%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.73%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.73%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.73%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1         | 0.73%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.73%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.73%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.73%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.73%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.73%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.73%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.73%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.73%   |
| Intel 82801CAM (ICH3) PRO/100 VE (LOM) Ethernet Controller        | 1         | 0.73%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.73%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.73%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 0.73%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1         | 0.73%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1         | 0.73%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 0.73%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                    | 1         | 0.73%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 0.73%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.73%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 0.73%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1         | 0.73%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.73%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.73%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 130       | 51.38%  |
| WiFi     | 116       | 45.85%  |
| Unknown  | 6         | 2.37%   |
| Modem    | 1         | 0.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 120       | 56.6%   |
| WiFi     | 87        | 41.04%  |
| Unknown  | 5         | 2.36%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 100       | 69.93%  |
| 1     | 40        | 27.97%  |
| 4     | 2         | 1.4%    |
| 3     | 1         | 0.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 131       | 91.61%  |
| Yes  | 12        | 8.39%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 38        | 45.78%  |
| Realtek Semiconductor           | 7         | 8.43%   |
| Qualcomm Atheros Communications | 6         | 7.23%   |
| Broadcom                        | 6         | 7.23%   |
| Lite-On Technology              | 5         | 6.02%   |
| ASUSTek Computer                | 5         | 6.02%   |
| Apple                           | 5         | 6.02%   |
| IMC Networks                    | 4         | 4.82%   |
| Foxconn / Hon Hai               | 2         | 2.41%   |
| Cambridge Silicon Radio         | 2         | 2.41%   |
| Hewlett-Packard                 | 1         | 1.2%    |
| Dell                            | 1         | 1.2%    |
| Alps Electric                   | 1         | 1.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 25        | 30.12%  |
| Intel AX201 Bluetooth                                       | 4         | 4.82%   |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 3.61%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3         | 3.61%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 3         | 3.61%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 2.41%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 2.41%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 2.41%   |
| Intel AX200 Bluetooth                                       | 2         | 2.41%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 2.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 2.41%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 2.41%   |
| ASUS BT-253 Bluetooth Adapter                               | 2         | 2.41%   |
| Apple Bluetooth Host Controller                             | 2         | 2.41%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 1.2%    |
| Realtek RTL8723B Bluetooth                                  | 1         | 1.2%    |
| Realtek  Bluetooth 4.0 Adapter                              | 1         | 1.2%    |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 1         | 1.2%    |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 1         | 1.2%    |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.2%    |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.2%    |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device        | 1         | 1.2%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.2%    |
| Lite-On Bluetooth USB Module                                | 1         | 1.2%    |
| Lite-On Atheros Bluetooth                                   | 1         | 1.2%    |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.2%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 1.2%    |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 1.2%    |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 1.2%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.2%    |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 1.2%    |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 1.2%    |
| Dell DW375 Bluetooth Module                                 | 1         | 1.2%    |
| Broadcom BCM43142A0 Bluetooth Device                        | 1         | 1.2%    |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 1         | 1.2%    |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.2%    |
| Broadcom BCM2045 Bluetooth                                  | 1         | 1.2%    |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                       | 1         | 1.2%    |
| ASUS Bluetooth Controller                                   | 1         | 1.2%    |
| ASUS ASUS USB-BT500                                         | 1         | 1.2%    |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 1.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 112       | 61.54%  |
| AMD                              | 35        | 19.23%  |
| Nvidia                           | 19        | 10.44%  |
| XMOS                             | 2         | 1.1%    |
| Sony                             | 2         | 1.1%    |
| Corsair                          | 2         | 1.1%    |
| C-Media Electronics              | 2         | 1.1%    |
| VIA Technologies                 | 1         | 0.55%   |
| Silicon Integrated Systems [SiS] | 1         | 0.55%   |
| Realtek Semiconductor            | 1         | 0.55%   |
| Quanta                           | 1         | 0.55%   |
| LG Electronics                   | 1         | 0.55%   |
| Creative Technology              | 1         | 0.55%   |
| Blue Microphones                 | 1         | 0.55%   |
| Audio-Technica                   | 1         | 0.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 8.93%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 5.36%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 4.02%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 4.02%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 4.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 4.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 3.57%   |
| AMD FCH Azalia Controller                                                                         | 8         | 3.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 3.13%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 3.13%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 2.68%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 2.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 2.23%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 1.79%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.79%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.79%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.79%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.79%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 1.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.34%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 1.34%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 1.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.34%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.34%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.89%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 2         | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.89%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 0.89%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.89%   |
| Corsair Corsair VOID PRO Wireless Gaming Headset                                                  | 2         | 0.89%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.89%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.89%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 0.89%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 0.89%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 0.89%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.89%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 0.89%   |
| XMOS XMOS XS1-U8 MFA (ST)                                                                         | 1         | 0.45%   |
| XMOS Shanling UA2                                                                                 | 1         | 0.45%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.45%   |
| Sony Sony Audio                                                                                   | 1         | 0.45%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1         | 0.45%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.45%   |
| Realtek Semiconductor Realtek USB Audio                                                           | 1         | 0.45%   |
| Quanta USB Audio Realtek USB2.0 Audio Microphone                                                  | 1         | 0.45%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.45%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.45%   |
| Nvidia MCP73 High Definition Audio                                                                | 1         | 0.45%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.45%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.45%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.45%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.45%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.45%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.45%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.45%   |
| LG Electronics USB Audio LG UltraFine Display Audio                                               | 1         | 0.45%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 41        | 24.7%   |
| SK hynix            | 33        | 19.88%  |
| Micron Technology   | 20        | 12.05%  |
| Unknown             | 19        | 11.45%  |
| Kingston            | 13        | 7.83%   |
| Crucial             | 8         | 4.82%   |
| G.Skill             | 7         | 4.22%   |
| Elpida              | 6         | 3.61%   |
| Corsair             | 6         | 3.61%   |
| Nanya Technology    | 4         | 2.41%   |
| Transcend           | 2         | 1.2%    |
| A-DATA Technology   | 2         | 1.2%    |
| Unknown (ABCD)      | 1         | 0.6%    |
| Unknown (09D5)      | 1         | 0.6%    |
| Magnum Tech         | 1         | 0.6%    |
| EVGA                | 1         | 0.6%    |
| 48spaces            | 1         | 0.6%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 19        | 10.8%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 7         | 3.98%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 2.27%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.7%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.7%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.7%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 3         | 1.7%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.7%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 2         | 1.14%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.14%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.14%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 1.14%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                    | 2         | 1.14%   |
| Micron RAM ITC 4096MB DIMM DDR3 1066MT/s                         | 2         | 1.14%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 2400MT/s            | 2         | 1.14%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2133MT/s | 1         | 0.57%   |
| Unknown (09D5) RAM Module 16GB SODIMM DDR4 2400MT/s              | 1         | 0.57%   |
| Transcend RAM TS512MSK64V1N 4GB SODIMM 800MT/s                   | 1         | 0.57%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR 667MT/s                 | 1         | 0.57%   |
| SK hynix RAM Zhidian4GDDR800000 4GB DIMM DDR2 800MT/s            | 1         | 0.57%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.57%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s             | 1         | 0.57%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 1         | 0.57%   |
| SK hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s             | 1         | 0.57%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s             | 1         | 0.57%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.57%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.57%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.57%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.57%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1067MT/s             | 1         | 0.57%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1333MT/s           | 1         | 0.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.57%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.57%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s             | 1         | 0.57%   |
| SK hynix RAM HMT31GR7AFR4C-H9 8GB DIMM DDR3 1333MT/s             | 1         | 0.57%   |
| SK hynix RAM HMT125U6AFP8C-G7 2048MB DIMM DDR3 1066MT/s          | 1         | 0.57%   |
| SK hynix RAM HMT112U6AFP8C-G7 1GB DIMM 1066MT/s                  | 1         | 0.57%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s       | 1         | 0.57%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s          | 1         | 0.57%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.57%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.57%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 0.57%   |
| SK hynix RAM H9CCNNNBJTMLAR-NUD 4096MB SODIMM LPDDR3 1867MT/s    | 1         | 0.57%   |
| SK hynix RAM H5TC8G63AMR-PBA 4096MB 1600MT/s                     | 1         | 0.57%   |
| Samsung RAM Module 16GB SODIMM DDR4 2133MT/s                     | 1         | 0.57%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 0.57%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 1         | 0.57%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.57%   |
| Samsung RAM M471B5273CM0-CH9 4GB SODIMM DDR3 1333MT/s            | 1         | 0.57%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.57%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.57%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 0.57%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.57%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.57%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.57%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.57%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.57%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 1         | 0.57%   |
| Samsung RAM M471A4G43MB1-CTD 0kB SODIMM DDR4 2667MT/s            | 1         | 0.57%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 63        | 43.45%  |
| DDR4    | 48        | 33.1%   |
| DDR2    | 16        | 11.03%  |
| LPDDR3  | 5         | 3.45%   |
| SDRAM   | 4         | 2.76%   |
| Unknown | 4         | 2.76%   |
| DDR     | 2         | 1.38%   |
| RAM     | 1         | 0.69%   |
| LPDDR4  | 1         | 0.69%   |
| DRAM    | 1         | 0.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 95        | 65.97%  |
| DIMM         | 42        | 29.17%  |
| Chip         | 3         | 2.08%   |
| Row Of Chips | 2         | 1.39%   |
| Unknown      | 2         | 1.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 61        | 37.89%  |
| 8192  | 48        | 29.81%  |
| 2048  | 26        | 16.15%  |
| 16384 | 14        | 8.7%    |
| 1024  | 9         | 5.59%   |
| 32768 | 1         | 0.62%   |
| 512   | 1         | 0.62%   |
| 128   | 1         | 0.62%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 41        | 26.8%   |
| 2400    | 21        | 13.73%  |
| 2667    | 13        | 8.5%    |
| 1333    | 12        | 7.84%   |
| 2133    | 10        | 6.54%   |
| 3200    | 9         | 5.88%   |
| 800     | 8         | 5.23%   |
| 667     | 7         | 4.58%   |
| 1334    | 6         | 3.92%   |
| Unknown | 6         | 3.92%   |
| 1066    | 5         | 3.27%   |
| 1867    | 4         | 2.61%   |
| 1067    | 3         | 1.96%   |
| 3600    | 2         | 1.31%   |
| 2933    | 2         | 1.31%   |
| 533     | 2         | 1.31%   |
| 1866    | 1         | 0.65%   |
| 975     | 1         | 0.65%   |

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
| Chicony Electronics                    | 20        | 24.69%  |
| Realtek Semiconductor                  | 9         | 11.11%  |
| Acer                                   | 9         | 11.11%  |
| Sunplus Innovation Technology          | 7         | 8.64%   |
| Suyin                                  | 6         | 7.41%   |
| Microdia                               | 5         | 6.17%   |
| Logitech                               | 4         | 4.94%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.94%   |
| Silicon Motion                         | 3         | 3.7%    |
| Quanta                                 | 3         | 3.7%    |
| Lite-On Technology                     | 3         | 3.7%    |
| IMC Networks                           | 3         | 3.7%    |
| Novatek Microelectronics               | 1         | 1.23%   |
| Intel                                  | 1         | 1.23%   |
| Genesys Logic                          | 1         | 1.23%   |
| Apple                                  | 1         | 1.23%   |
| Alcor Micro                            | 1         | 1.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 8         | 9.76%   |
| Acer Integrated Camera                                         | 5         | 6.1%    |
| Sunplus Integrated_Webcam_HD                                   | 4         | 4.88%   |
| Suyin Acer Crystal Eye webcam                                  | 2         | 2.44%   |
| Realtek Realtek USB2.0 PC Camera                               | 2         | 2.44%   |
| Realtek Lenovo EasyCamera                                      | 2         | 2.44%   |
| Quanta Realtek DMFT - RGB                                      | 2         | 2.44%   |
| Microdia Integrated_Webcam_HD                                  | 2         | 2.44%   |
| Microdia Integrated Webcam                                     | 2         | 2.44%   |
| Chicony HD WebCam                                              | 2         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam            | 2         | 2.44%   |
| Suyin USB 2.0 UVC 1.3M WebCam                                  | 1         | 1.22%   |
| Suyin Laptop_Integrated_Webcam_3M                              | 1         | 1.22%   |
| Suyin HD WebCam                                                | 1         | 1.22%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 1         | 1.22%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 1.22%   |
| Sunplus Integrated Webcam                                      | 1         | 1.22%   |
| Sunplus Asus Webcam                                            | 1         | 1.22%   |
| Silicon Motion WebCam SCX Series                               | 1         | 1.22%   |
| Silicon Motion Realtek USB2.0 PC Camera                        | 1         | 1.22%   |
| Silicon Motion 300k Pixel Camera                               | 1         | 1.22%   |
| Realtek USB2.0 VGA UVC WebCam                                  | 1         | 1.22%   |
| Realtek USB2.0 HD UVC WebCam                                   | 1         | 1.22%   |
| Realtek USB Camera                                             | 1         | 1.22%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 1.22%   |
| Realtek HD Webcam - Realtek                                    | 1         | 1.22%   |
| Quanta Front camera                                            | 1         | 1.22%   |
| Novatek HP High Definition 2MP Webcam                          | 1         | 1.22%   |
| Microdia Sonix USB 2.0 Camera                                  | 1         | 1.22%   |
| Logitech Webcam C310                                           | 1         | 1.22%   |
| Logitech Webcam C270                                           | 1         | 1.22%   |
| Logitech HD Pro Webcam C920                                    | 1         | 1.22%   |
| Logitech C505 HD Webcam                                        | 1         | 1.22%   |
| Lite-On Realtek PC Camera                                      | 1         | 1.22%   |
| Lite-On Integrated Camera                                      | 1         | 1.22%   |
| Lite-On HP Universal Camera                                    | 1         | 1.22%   |
| Intel WiMAX Connection 2400m                                   | 1         | 1.22%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 1         | 1.22%   |
| IMC Networks USB2.0 UVC HD Webcam                              | 1         | 1.22%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 1.22%   |
| Genesys Logic Camera                                           | 1         | 1.22%   |
| Chicony Webcam                                                 | 1         | 1.22%   |
| Chicony USB2.0 HD UVC WebCam                                   | 1         | 1.22%   |
| Chicony Thinkpad T430 camera                                   | 1         | 1.22%   |
| Chicony Realtek DMFT - IR                                      | 1         | 1.22%   |
| Chicony Lenovo EasyCamera                                      | 1         | 1.22%   |
| Chicony Integrated Camera [ThinkPad]                           | 1         | 1.22%   |
| Chicony Integrated Camera (1280x720@30)                        | 1         | 1.22%   |
| Chicony HP TrueVision HD Camera                                | 1         | 1.22%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 1.22%   |
| Chicony FJ Camera                                              | 1         | 1.22%   |
| Chicony Chicony USB2.0 Camera                                  | 1         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 1         | 1.22%   |
| Apple FaceTime HD Camera                                       | 1         | 1.22%   |
| Alcor Micro HP WebCam-101                                      | 1         | 1.22%   |
| Acer USB2.0 Camera                                             | 1         | 1.22%   |
| Acer NEC HD WebCam                                             | 1         | 1.22%   |
| Acer Lenovo EasyCamera                                         | 1         | 1.22%   |
| Acer EasyCamera                                                | 1         | 1.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


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

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


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

![Unsupported Devices](./images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 53        | 36.3%   |
| 2     | 42        | 28.77%  |
| 0     | 24        | 16.44%  |
| 3     | 16        | 10.96%  |
| 4     | 7         | 4.79%   |
| 5     | 2         | 1.37%   |
| 7     | 1         | 0.68%   |
| 6     | 1         | 0.68%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 92        | 43.6%   |
| Net/wireless             | 35        | 16.59%  |
| Bluetooth                | 21        | 9.95%   |
| Firewire controller      | 20        | 9.48%   |
| Fingerprint reader       | 18        | 8.53%   |
| Card reader              | 16        | 7.58%   |
| Network                  | 5         | 2.37%   |
| Sound                    | 3         | 1.42%   |
| Storage/raid             | 1         | 0.47%   |

