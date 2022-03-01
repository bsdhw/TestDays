NomadBSD - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for NomadBSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/NomadBSD/Desktop/README.md) and [notebooks](/Dist/NomadBSD/Notebook/README.md).

Full-feature report is available here: https://bsd-hardware.info/?view=trends

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

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Dell          | Latitude D630               | Notebook    | [ae56d2cedd](https://bsd-hardware.info/?probe=ae56d2cedd) | Feb 28, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e27a6f46fc](https://bsd-hardware.info/?probe=e27a6f46fc) | Feb 26, 2022 |
| Gigabyte      | X570S GAMING X              | Desktop     | [ff39ace6ec](https://bsd-hardware.info/?probe=ff39ace6ec) | Feb 16, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [766e62f699](https://bsd-hardware.info/?probe=766e62f699) | Feb 12, 2022 |
| HP            | Notebook                    | Notebook    | [1758596e26](https://bsd-hardware.info/?probe=1758596e26) | Feb 12, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [24f3a7da57](https://bsd-hardware.info/?probe=24f3a7da57) | Feb 07, 2022 |
| Intel         | DCP847SKE G80890-105        | Desktop     | [2828ef2a6d](https://bsd-hardware.info/?probe=2828ef2a6d) | Jan 20, 2022 |
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

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 122       | 93.85%  |
| i386  | 8         | 6.15%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Openbox       | 116       | 89.23%  |
| GNOME         | 7         | 5.38%   |
| KDE5          | 3         | 2.31%   |
| XFCE          | 1         | 0.77%   |
| GNUstep       | 1         | 0.77%   |
| filer         | 1         | 0.77%   |
| Enlightenment | 1         | 0.77%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 129       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 127       | 98.45%  |
| SDDM | 2         | 1.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 48        | 36.64%  |
| Unknown | 26        | 19.85%  |
| de_DE   | 14        | 10.69%  |
| en_GB   | 7         | 5.34%   |
| ru_RU   | 6         | 4.58%   |
| it_IT   | 5         | 3.82%   |
| hu_HU   | 5         | 3.82%   |
| tr_TR   | 3         | 2.29%   |
| es_ES   | 3         | 2.29%   |
| pt_BR   | 2         | 1.53%   |
| pl_PL   | 2         | 1.53%   |
| en_AU   | 2         | 1.53%   |
| cs_CZ   | 2         | 1.53%   |
| zh_CN   | 1         | 0.76%   |
| ko_KR   | 1         | 0.76%   |
| fr_FR   | 1         | 0.76%   |
| fi_FI   | 1         | 0.76%   |
| et_EE   | 1         | 0.76%   |
| bg_BG   | 1         | 0.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 123       | 94.62%  |
| BIOS | 7         | 5.38%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ufs  | 115       | 89.15%  |
| Zfs  | 14        | 10.85%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 92        | 70.77%  |
| MBR  | 38        | 29.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 22        | 17.05%  |
| Hewlett-Packard     | 19        | 14.73%  |
| Dell                | 19        | 14.73%  |
| ASUSTek Computer    | 18        | 13.95%  |
| Acer                | 9         | 6.98%   |
| Gigabyte Technology | 6         | 4.65%   |
| ASRock              | 4         | 3.1%    |
| Apple               | 4         | 3.1%    |
| Sony                | 3         | 2.33%   |
| Samsung Electronics | 2         | 1.55%   |
| Pegatron            | 2         | 1.55%   |
| Intel               | 2         | 1.55%   |
| Google              | 2         | 1.55%   |
| Fujitsu             | 2         | 1.55%   |
| Unknown             | 2         | 1.55%   |
| TUXEDO              | 1         | 0.78%   |
| Toshiba             | 1         | 0.78%   |
| Semp Toshiba        | 1         | 0.78%   |
| Panasonic           | 1         | 0.78%   |
| Notebook            | 1         | 0.78%   |
| NEC Computers       | 1         | 0.78%   |
| MSI                 | 1         | 0.78%   |
| IBM                 | 1         | 0.78%   |
| GEO                 | 1         | 0.78%   |
| Fujitsu Siemens     | 1         | 0.78%   |
| Foxconn             | 1         | 0.78%   |
| Clevo               | 1         | 0.78%   |
| Alienware           | 1         | 0.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Unknown                                   | 3         | 2.33%   |
| Acer Veriton M460                         | 2         | 1.55%   |
| Toshiba Satellite C660                    | 1         | 0.78%   |
| Sony VPCM13M1R                            | 1         | 0.78%   |
| Sony VJS121C11N                           | 1         | 0.78%   |
| Sony SVE1713S1RW                          | 1         | 0.78%   |
| Semp Toshiba STI                          | 1         | 0.78%   |
| Samsung N145P/N250P/N260P                 | 1         | 0.78%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV   | 1         | 0.78%   |
| Pegatron T12Ah                            | 1         | 0.78%   |
| Pegatron Elite 7300 Series MT             | 1         | 0.78%   |
| Panasonic CF-C1BD06EFG                    | 1         | 0.78%   |
| Notebook N650DU                           | 1         | 0.78%   |
| NEC Computers PC-GL186Y3AZ                | 1         | 0.78%   |
| MSI MS-N033                               | 1         | 0.78%   |
| Lenovo ThinkPad X380 Yoga 20LJ000WUK      | 1         | 0.78%   |
| Lenovo ThinkPad X201 Tablet 311396U       | 1         | 0.78%   |
| Lenovo ThinkPad X13 Yoga Gen 1 20SYS22H00 | 1         | 0.78%   |
| Lenovo ThinkPad X1 Yoga 3rd 20LDS1CG00    | 1         | 0.78%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB001XAU  | 1         | 0.78%   |
| Lenovo ThinkPad W541 20EGS04800           | 1         | 0.78%   |
| Lenovo ThinkPad T530 24295VU              | 1         | 0.78%   |
| Lenovo ThinkPad T510 4384FF3              | 1         | 0.78%   |
| Lenovo ThinkPad T490s 20NX000DRT          | 1         | 0.78%   |
| Lenovo ThinkPad T490 20RYS06R00           | 1         | 0.78%   |
| Lenovo ThinkPad T470s W10DG 20JS001FGE    | 1         | 0.78%   |
| Lenovo ThinkPad T460 20FMS78014           | 1         | 0.78%   |
| Lenovo ThinkPad T450 20BUS06B00           | 1         | 0.78%   |
| Lenovo ThinkPad T440p 20AWS0VK00          | 1         | 0.78%   |
| Lenovo ThinkPad T430 2347C32              | 1         | 0.78%   |
| Lenovo ThinkPad S1 Yoga 20C0S0M300        | 1         | 0.78%   |
| Lenovo ThinkCentre M93p 10A8001HUS        | 1         | 0.78%   |
| Lenovo Legion Y7000 2019 PG0 81T0         | 1         | 0.78%   |
| Lenovo IdeaPad S145-15API 81UT            | 1         | 0.78%   |
| Lenovo IdeaPad 110-15IBR 80T7             | 1         | 0.78%   |
| Lenovo G570 20079                         | 1         | 0.78%   |
| Lenovo G50-45 80E3                        | 1         | 0.78%   |
| Intel NUC5i3RYB H41000-507                | 1         | 0.78%   |
| Intel DCP847SKE G80890-105                | 1         | 0.78%   |
| IBM 2647NG8                               | 1         | 0.78%   |
| HP ZBook Studio G3                        | 1         | 0.78%   |
| HP Z620 Workstation                       | 1         | 0.78%   |
| HP Spectre x360 Convertible 13-w0XX       | 1         | 0.78%   |
| HP ProBook x360 11 G6 EE                  | 1         | 0.78%   |
| HP ProBook 640 G1                         | 1         | 0.78%   |
| HP Pavilion Notebook                      | 1         | 0.78%   |
| HP Pavilion g6                            | 1         | 0.78%   |
| HP Pavilion dv6000 (RP981EA#AB8)          | 1         | 0.78%   |
| HP OMEN by HP Laptop 17-cb1xxx            | 1         | 0.78%   |
| HP Notebook                               | 1         | 0.78%   |
| HP Laptop 15-db0xxx                       | 1         | 0.78%   |
| HP Laptop 15-da0xxx                       | 1         | 0.78%   |
| HP EliteBook 820 G1                       | 1         | 0.78%   |
| HP Desktop M01-F1xxx                      | 1         | 0.78%   |
| HP Compaq Elite 8300 Touch All-in-One PC  | 1         | 0.78%   |
| HP Compaq dc7900 Convertible Minitower    | 1         | 0.78%   |
| HP Compaq dc7800p Convertible Minitower   | 1         | 0.78%   |
| HP Compaq dc5750 Microtower               | 1         | 0.78%   |
| HP 2000                                   | 1         | 0.78%   |
| Google Lulu                               | 1         | 0.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 16        | 12.4%   |
| Dell Latitude              | 7         | 5.43%   |
| Acer Aspire                | 7         | 5.43%   |
| Dell OptiPlex              | 5         | 3.88%   |
| HP Compaq                  | 4         | 3.1%    |
| HP Pavilion                | 3         | 2.33%   |
| Dell Inspiron              | 3         | 2.33%   |
| Unknown                    | 3         | 2.33%   |
| Lenovo IdeaPad             | 2         | 1.55%   |
| HP ProBook                 | 2         | 1.55%   |
| HP Laptop                  | 2         | 1.55%   |
| Gigabyte Z370              | 2         | 1.55%   |
| Gigabyte X570              | 2         | 1.55%   |
| Fujitsu LIFEBOOK           | 2         | 1.55%   |
| Dell Studio                | 2         | 1.55%   |
| ASUS TUF                   | 2         | 1.55%   |
| ASUS PRIME                 | 2         | 1.55%   |
| Acer Veriton               | 2         | 1.55%   |
| Toshiba Satellite          | 1         | 0.78%   |
| Sony VPCM13M1R             | 1         | 0.78%   |
| Sony VJS121C11N            | 1         | 0.78%   |
| Sony SVE1713S1RW           | 1         | 0.78%   |
| Semp Toshiba STI           | 1         | 0.78%   |
| Samsung N145P              | 1         | 0.78%   |
| Samsung 300E5EV            | 1         | 0.78%   |
| Pegatron T12Ah             | 1         | 0.78%   |
| Pegatron Elite             | 1         | 0.78%   |
| Panasonic CF-C1BD06EFG     | 1         | 0.78%   |
| Notebook N650DU            | 1         | 0.78%   |
| NEC Computers PC-GL186Y3AZ | 1         | 0.78%   |
| MSI MS-N033                | 1         | 0.78%   |
| Lenovo ThinkCentre         | 1         | 0.78%   |
| Lenovo Legion              | 1         | 0.78%   |
| Lenovo G570                | 1         | 0.78%   |
| Lenovo G50-45              | 1         | 0.78%   |
| Intel NUC5i3RYB            | 1         | 0.78%   |
| Intel DCP847SKE            | 1         | 0.78%   |
| IBM 2647NG8                | 1         | 0.78%   |
| HP ZBook                   | 1         | 0.78%   |
| HP Z620                    | 1         | 0.78%   |
| HP Spectre                 | 1         | 0.78%   |
| HP OMEN                    | 1         | 0.78%   |
| HP Notebook                | 1         | 0.78%   |
| HP EliteBook               | 1         | 0.78%   |
| HP Desktop                 | 1         | 0.78%   |
| HP 2000                    | 1         | 0.78%   |
| Google Lulu                | 1         | 0.78%   |
| Google Chell               | 1         | 0.78%   |
| Gigabyte X570S             | 1         | 0.78%   |
| Gigabyte MZGLKBP-00        | 1         | 0.78%   |
| GEO GeoBook3               | 1         | 0.78%   |
| Fujitsu Siemens AMILO      | 1         | 0.78%   |
| Foxconn Napa               | 1         | 0.78%   |
| Dell Vostro                | 1         | 0.78%   |
| Dell Precision             | 1         | 0.78%   |
| Clevo W55xEU               | 1         | 0.78%   |
| ASUS Z170-A                | 1         | 0.78%   |
| ASUS X751LN                | 1         | 0.78%   |
| ASUS X71SL                 | 1         | 0.78%   |
| ASUS X550LC                | 1         | 0.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 19        | 14.73%  |
| 2020 | 17        | 13.18%  |
| 2017 | 11        | 8.53%   |
| 2016 | 8         | 6.2%    |
| 2015 | 8         | 6.2%    |
| 2010 | 8         | 6.2%    |
| 2021 | 7         | 5.43%   |
| 2014 | 7         | 5.43%   |
| 2012 | 7         | 5.43%   |
| 2011 | 7         | 5.43%   |
| 2009 | 7         | 5.43%   |
| 2018 | 6         | 4.65%   |
| 2013 | 6         | 4.65%   |
| 2008 | 6         | 4.65%   |
| 2006 | 3         | 2.33%   |
| 2007 | 1         | 0.78%   |
| 2004 | 1         | 0.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 82        | 63.57%  |
| Desktop     | 39        | 30.23%  |
| Convertible | 5         | 3.88%   |
| All in one  | 2         | 1.55%   |
| Mini pc     | 1         | 0.78%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 127       | 98.45%  |
| Yes  | 2         | 1.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 52        | 40%     |
| 4.01-8.0    | 31        | 23.85%  |
| 16.01-24.0  | 25        | 19.23%  |
| 32.01-64.0  | 9         | 6.92%   |
| 2.01-3.0    | 4         | 3.08%   |
| 3.01-4.0    | 3         | 2.31%   |
| 64.01-256.0 | 3         | 2.31%   |
| 0.51-1.0    | 3         | 2.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 72        | 54.96%  |
| 0.51-1.0  | 37        | 28.24%  |
| 1.01-2.0  | 13        | 9.92%   |
| 2.01-3.0  | 5         | 3.82%   |
| 4.01-8.0  | 2         | 1.53%   |
| 3.01-4.0  | 1         | 0.76%   |
| 8.01-16.0 | 1         | 0.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 88        | 67.69%  |
| 2      | 22        | 16.92%  |
| 3      | 10        | 7.69%   |
| 0      | 7         | 5.38%   |
| 4      | 2         | 1.54%   |
| 7      | 1         | 0.77%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 75        | 57.69%  |
| Yes       | 55        | 42.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 118       | 90.77%  |
| No        | 12        | 9.23%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 82.17%  |
| No        | 23        | 17.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 56.92%  |
| No        | 56        | 43.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 26        | 20.16%  |
| Germany     | 17        | 13.18%  |
| Russia      | 14        | 10.85%  |
| France      | 13        | 10.08%  |
| UK          | 7         | 5.43%   |
| Italy       | 7         | 5.43%   |
| Turkey      | 5         | 3.88%   |
| Hungary     | 5         | 3.88%   |
| Mexico      | 3         | 2.33%   |
| Colombia    | 3         | 2.33%   |
| Romania     | 2         | 1.55%   |
| Poland      | 2         | 1.55%   |
| Norway      | 2         | 1.55%   |
| Japan       | 2         | 1.55%   |
| Czechia     | 2         | 1.55%   |
| Brazil      | 2         | 1.55%   |
| Australia   | 2         | 1.55%   |
| Argentina   | 2         | 1.55%   |
| Ukraine     | 1         | 0.78%   |
| Thailand    | 1         | 0.78%   |
| Spain       | 1         | 0.78%   |
| South Korea | 1         | 0.78%   |
| Slovakia    | 1         | 0.78%   |
| Serbia      | 1         | 0.78%   |
| Philippines | 1         | 0.78%   |
| Hong Kong   | 1         | 0.78%   |
| Finland     | 1         | 0.78%   |
| Estonia     | 1         | 0.78%   |
| Denmark     | 1         | 0.78%   |
| China       | 1         | 0.78%   |
| Bulgaria    | 1         | 0.78%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Moscow                | 8         | 6.11%   |
| Franconville          | 6         | 4.58%   |
| Paris                 | 5         | 3.82%   |
| Hodmezovasarhely      | 5         | 3.82%   |
| Istanbul              | 4         | 3.05%   |
| Woodland              | 3         | 2.29%   |
| Whittier              | 3         | 2.29%   |
| Tijuana               | 3         | 2.29%   |
| Milan                 | 3         | 2.29%   |
| Markt Indersdorf      | 3         | 2.29%   |
| Zwingenberg           | 2         | 1.53%   |
| Volzhskiy             | 2         | 1.53%   |
| St Petersburg         | 2         | 1.53%   |
| Setagaya-ku           | 2         | 1.53%   |
| Rome                  | 2         | 1.53%   |
| Rio de Janeiro        | 2         | 1.53%   |
| New Braunfels         | 2         | 1.53%   |
| McDonough             | 2         | 1.53%   |
| Los Angeles           | 2         | 1.53%   |
| Greenwich             | 2         | 1.53%   |
| Drobeta-Turnu Severin | 2         | 1.53%   |
| Cologne               | 2         | 1.53%   |
| Brisbane              | 2         | 1.53%   |
| BogotГЎ             | 2         | 1.53%   |
| Wloszczowa            | 1         | 0.76%   |
| Wissen                | 1         | 0.76%   |
| Winter Haven          | 1         | 0.76%   |
| Wilhelmshaven         | 1         | 0.76%   |
| Warsaw                | 1         | 0.76%   |
| Vollen                | 1         | 0.76%   |
| Vladimir              | 1         | 0.76%   |
| Vertou                | 1         | 0.76%   |
| Tucson                | 1         | 0.76%   |
| Trieste               | 1         | 0.76%   |
| Tallinn               | 1         | 0.76%   |
| Swindon               | 1         | 0.76%   |
| Suwon                 | 1         | 0.76%   |
| Southampton           | 1         | 0.76%   |
| Sofia                 | 1         | 0.76%   |
| Shanghai              | 1         | 0.76%   |
| Sedavi                | 1         | 0.76%   |
| San Francisco         | 1         | 0.76%   |
| San Bernardino        | 1         | 0.76%   |
| Saint-Denis           | 1         | 0.76%   |
| Rionegro              | 1         | 0.76%   |
| Peoria                | 1         | 0.76%   |
| Pasig                 | 1         | 0.76%   |
| Palmer                | 1         | 0.76%   |
| Palm Bay              | 1         | 0.76%   |
| Oslo                  | 1         | 0.76%   |
| Nueve de Julio        | 1         | 0.76%   |
| Novosibirsk           | 1         | 0.76%   |
| Niederlauer           | 1         | 0.76%   |
| Munich                | 1         | 0.76%   |
| Melcice               | 1         | 0.76%   |
| Marburg               | 1         | 0.76%   |
| Malton                | 1         | 0.76%   |
| London                | 1         | 0.76%   |
| Langen                | 1         | 0.76%   |
| Kyiv                  | 1         | 0.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 38     | 18.9%   |
| WDC                 | 29        | 36     | 17.68%  |
| Seagate             | 25        | 28     | 15.24%  |
| Toshiba             | 17        | 19     | 10.37%  |
| Kingston            | 6         | 6      | 3.66%   |
| Hitachi             | 5         | 5      | 3.05%   |
| Crucial             | 5         | 5      | 3.05%   |
| Apple               | 5         | 6      | 3.05%   |
| A-DATA Technology   | 5         | 5      | 3.05%   |
| SK Hynix            | 4         | 4      | 2.44%   |
| SanDisk             | 4         | 5      | 2.44%   |
| Intel               | 4         | 4      | 2.44%   |
| Transcend           | 2         | 2      | 1.22%   |
| OCZ                 | 2         | 2      | 1.22%   |
| Micron Technology   | 2         | 2      | 1.22%   |
| Intenso             | 2         | 2      | 1.22%   |
| HGST                | 2         | 2      | 1.22%   |
| Hewlett-Packard     | 2         | 2      | 1.22%   |
| Fujitsu             | 2         | 3      | 1.22%   |
| Team                | 1         | 1      | 0.61%   |
| SPCC                | 1         | 1      | 0.61%   |
| PNY                 | 1         | 1      | 0.61%   |
| ORICO               | 1         | 1      | 0.61%   |
| MAXTOR              | 1         | 1      | 0.61%   |
| LITEONIT            | 1         | 1      | 0.61%   |
| KingDian            | 1         | 1      | 0.61%   |
| Gigabyte Technology | 1         | 1      | 0.61%   |
| Corsair             | 1         | 1      | 0.61%   |
| ASUSTek Computer    | 1         | 2      | 0.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB               | 3         | 1.7%    |
| Seagate ST1000LM049-2GH172 1TB       | 3         | 1.7%    |
| WDC WD1600AAJS-22L7A0 160GB          | 2         | 1.14%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB | 2         | 1.14%   |
| Toshiba MQ01ABF050 500GB             | 2         | 1.14%   |
| Toshiba HDWD120 2TB                  | 2         | 1.14%   |
| Seagate ST95005620AS 500GB           | 2         | 1.14%   |
| Seagate ST9500325AS 500GB            | 2         | 1.14%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 1.14%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.14%   |
| SanDisk pSSD 256GB                   | 2         | 1.14%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 1.14%   |
| Samsung SSD 970 EVO 500GB            | 2         | 1.14%   |
| Samsung SSD 870 QVO 2TB              | 2         | 1.14%   |
| Samsung SSD 840 EVO 250GB            | 2         | 1.14%   |
| Samsung MZVLB256HBHQ-000L7 256GB     | 2         | 1.14%   |
| Kingston SA400S37480G 480GB          | 2         | 1.14%   |
| Kingston SA400S37240G 240GB          | 2         | 1.14%   |
| HGST HTS725050A7E630 500GB           | 2         | 1.14%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 1.14%   |
| Crucial CT1000P1SSD8 1TB             | 2         | 1.14%   |
| Apple SSD SM0512F 500GB              | 2         | 1.14%   |
| A-DATA SU630 240GB                   | 2         | 1.14%   |
| WDC WDS240G2G0B-00EPW0 240GB         | 1         | 0.57%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 0.57%   |
| WDC WDS120G2G0B-00EPW0 120GB         | 1         | 0.57%   |
| WDC WDS120G2G0A-00JH30 120GB         | 1         | 0.57%   |
| WDC WDS120G1G0A-00SS50 120GB         | 1         | 0.57%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 1         | 0.57%   |
| WDC WD7500BPKT-75PK4T0 752GB         | 1         | 0.57%   |
| WDC WD6400AAKS-22A7B2 640GB          | 1         | 0.57%   |
| WDC WD40PURX-64GVNY0 4TB             | 1         | 0.57%   |
| WDC WD40NMZW-11GX6S1 4TB             | 1         | 0.57%   |
| WDC WD3200BEKT-60PVMT0 320GB         | 1         | 0.57%   |
| WDC WD2500LPCX-24C6HT0 250GB         | 1         | 0.57%   |
| WDC WD2500BEVT-80A23T0 250GB         | 1         | 0.57%   |
| WDC WD2500BEKT-00PVMT0 250GB         | 1         | 0.57%   |
| WDC WD2004FBYZ-01YCBB1 2TB           | 1         | 0.57%   |
| WDC WD1200BEVS-07LAT0 120GB          | 1         | 0.57%   |
| WDC WD1200BEVE-00UYT0 120GB          | 1         | 0.57%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.57%   |
| WDC WD10SPZX-00Z10T0 1TB             | 1         | 0.57%   |
| WDC WD10SMRW-11Y43S0 1TB             | 1         | 0.57%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.57%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 0.57%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.57%   |
| WDC WD10JPLX-00MBPT0 1TB             | 1         | 0.57%   |
| WDC WD10EZRZ-00HTKB0 1TB             | 1         | 0.57%   |
| WDC WD10EZRX-00L4HB0 1TB             | 1         | 0.57%   |
| WDC WD10EFRX-68PJCN0 1TB             | 1         | 0.57%   |
| WDC WD10EADS-00P8B0 1TB              | 1         | 0.57%   |
| WDC PC SN720 SDAPNTW-1T00-1006 1TB   | 1         | 0.57%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB | 1         | 0.57%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB | 1         | 0.57%   |
| Transcend TS512GSSD370S 512GB        | 1         | 0.57%   |
| Transcend TS32GCF800 32GB            | 1         | 0.57%   |
| Toshiba TR200 240GB                  | 1         | 0.57%   |
| Toshiba THNSNC128GBSJ                | 1         | 0.57%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.57%   |
| Toshiba MK7575GSX 752GB              | 1         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 28     | 32.89%  |
| WDC                 | 22        | 25     | 28.95%  |
| Toshiba             | 13        | 14     | 17.11%  |
| Hitachi             | 5         | 5      | 6.58%   |
| Samsung Electronics | 4         | 4      | 5.26%   |
| HGST                | 2         | 2      | 2.63%   |
| Fujitsu             | 2         | 3      | 2.63%   |
| MAXTOR              | 1         | 1      | 1.32%   |
| Hewlett-Packard     | 1         | 1      | 1.32%   |
| Apple               | 1         | 1      | 1.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 17     | 21.67%  |
| Kingston            | 5         | 5      | 8.33%   |
| A-DATA Technology   | 5         | 5      | 8.33%   |
| WDC                 | 4         | 5      | 6.67%   |
| SanDisk             | 4         | 5      | 6.67%   |
| Apple               | 4         | 5      | 6.67%   |
| Toshiba             | 3         | 3      | 5%      |
| Crucial             | 3         | 3      | 5%      |
| Transcend           | 2         | 2      | 3.33%   |
| OCZ                 | 2         | 2      | 3.33%   |
| Micron Technology   | 2         | 2      | 3.33%   |
| Intenso             | 2         | 2      | 3.33%   |
| Intel               | 2         | 2      | 3.33%   |
| Team                | 1         | 1      | 1.67%   |
| SPCC                | 1         | 1      | 1.67%   |
| SK Hynix            | 1         | 1      | 1.67%   |
| PNY                 | 1         | 1      | 1.67%   |
| LITEONIT            | 1         | 1      | 1.67%   |
| KingDian            | 1         | 1      | 1.67%   |
| Gigabyte Technology | 1         | 1      | 1.67%   |
| Corsair             | 1         | 1      | 1.67%   |
| ASUSTek Computer    | 1         | 2      | 1.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 66        | 84     | 44.3%   |
| SSD  | 54        | 68     | 36.24%  |
| NVMe | 29        | 35     | 19.46%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 107       | 152    | 78.68%  |
| NVMe | 29        | 35     | 21.32%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 79        | 99     | 62.2%   |
| 0.51-1.0   | 35        | 40     | 27.56%  |
| 1.01-2.0   | 7         | 7      | 5.51%   |
| 3.01-4.0   | 3         | 3      | 2.36%   |
| 2.01-3.0   | 3         | 3      | 2.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 106       | 82.17%  |
| 101-250    | 12        | 9.3%    |
| 51-100     | 5         | 3.88%   |
| 251-500    | 2         | 1.55%   |
| 21-50      | 2         | 1.55%   |
| 501-1000   | 2         | 1.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 125       | 96.15%  |
| 21-50   | 3         | 2.31%   |
| 51-100  | 2         | 1.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


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

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 102       | 150    | 77.86%  |
| Malfunc  | 27        | 29     | 20.61%  |
| Detected | 2         | 8      | 1.53%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 93        | 59.62%  |
| AMD                              | 21        | 13.46%  |
| Samsung Electronics              | 19        | 12.18%  |
| Sandisk                          | 6         | 3.85%   |
| ASMedia Technology               | 4         | 2.56%   |
| VIA Technologies                 | 2         | 1.28%   |
| SK Hynix                         | 2         | 1.28%   |
| Nvidia                           | 2         | 1.28%   |
| Micron/Crucial Technology        | 2         | 1.28%   |
| Toshiba                          | 1         | 0.64%   |
| Silicon Motion                   | 1         | 0.64%   |
| Silicon Integrated Systems [SiS] | 1         | 0.64%   |
| Kingston Technology Company      | 1         | 0.64%   |
| Biwin Storage Technology         | 1         | 0.64%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 17        | 9.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 11        | 6.01%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 5.46%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 3.83%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 3.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 2.73%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 2.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 2.73%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 4         | 2.19%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 2.19%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 4         | 2.19%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.64%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.64%   |
| Intel SATA Controller [RAID mode]                                                | 3         | 1.64%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 1.64%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 1.64%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.64%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 1.64%   |
| Sandisk PC SN520 NVMe SSD                                                        | 2         | 1.09%   |
| Samsung SM951 AHCI                                                               | 2         | 1.09%   |
| Samsung Apple PCIe SSD                                                           | 2         | 1.09%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.09%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.09%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 2         | 1.09%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 1.09%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 2         | 1.09%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 2         | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 1.09%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 2         | 1.09%   |
| AMD 400 Series Chipset SATA Controller                                           | 2         | 1.09%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.55%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 0.55%   |
| VIA VT6421 IDE/SATA Controller                                                   | 1         | 0.55%   |
| Toshiba unknown                                                                  | 1         | 0.55%   |
| SK Hynix hynix unknown                                                           | 1         | 0.55%   |
| SK Hynix BC511                                                                   | 1         | 0.55%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.55%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.55%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.55%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.55%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.55%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.55%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.55%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.55%   |
| Nvidia MCP73 SATA Controller (IDE mode)                                          | 1         | 0.55%   |
| Nvidia MCP73 IDE Controller                                                      | 1         | 0.55%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 0.55%   |
| Nvidia MCP61 IDE                                                                 | 1         | 0.55%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1         | 0.55%   |
| Micron/Crucial NVMe Controller                                                   | 1         | 0.55%   |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 0.55%   |
| Intel SSD 660P Series                                                            | 1         | 0.55%   |
| Intel NVMe Optane Memory Series                                                  | 1         | 0.55%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 0.55%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.55%   |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                             | 1         | 0.55%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 0.55%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 1         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 90        | 57.32%  |
| NVMe | 29        | 18.47%  |
| IDE  | 25        | 15.92%  |
| RAID | 12        | 7.64%   |
| SAS  | 1         | 0.64%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 108       | 83.08%  |
| AMD    | 22        | 16.92%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 3.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 2.31%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 2         | 1.54%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 2         | 1.54%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 1.54%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 2         | 1.54%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.54%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2         | 1.54%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.54%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 2         | 1.54%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 2         | 1.54%   |
| Intel Core 2 Duo                            | 2         | 1.54%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2         | 1.54%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 1.54%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1         | 0.77%   |
| Intel Xeon CPU E5-2670 @ 2.60GHz            | 1         | 0.77%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz        | 1         | 0.77%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1         | 0.77%   |
| Intel Pentium III                           | 1         | 0.77%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1         | 0.77%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1         | 0.77%   |
| Intel Pentium D CPU 2.80GHz                 | 1         | 0.77%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 0.77%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.77%   |
| Intel Pentium CPU 2117U @ 1.80GHz           | 1         | 0.77%   |
| Intel Genuine CPU U7300 @ 1.30GHz           | 1         | 0.77%   |
| Intel CPU Version                           | 1         | 0.77%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz            | 1         | 0.77%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 0.77%   |
| Intel Core i9-7960X CPU @ 2.80GHz           | 1         | 0.77%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1         | 0.77%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.77%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.77%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.77%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.77%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 0.77%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 0.77%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.77%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz          | 1         | 0.77%   |
| Intel Core i7-4850HQ CPU @ 2.30GHz          | 1         | 0.77%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.77%   |
| Intel Core i7-4770HQ CPU @ 2.20GHz          | 1         | 0.77%   |
| Intel Core i7-4650U CPU @ 1.70GHz           | 1         | 0.77%   |
| Intel Core i7-4610M CPU @ 3.00GHz           | 1         | 0.77%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 1         | 0.77%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 1         | 0.77%   |
| Intel Core i7-4500U CPU                     | 1         | 0.77%   |
| Intel Core i7-3537U CPU @ 2.00GHz           | 1         | 0.77%   |
| Intel Core i7-2820QM CPU @ 2.30GHz          | 1         | 0.77%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 0.77%   |
| Intel Core i7-10610U CPU @ 1.80GHz          | 1         | 0.77%   |
| Intel Core i7 CPU L 640 @ 2.13GHz           | 1         | 0.77%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 1         | 0.77%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1         | 0.77%   |
| Intel Core i5-9300HF CPU @ 2.40GHz          | 1         | 0.77%   |
| Intel Core i5-8600K CPU @ 3.60GHz           | 1         | 0.77%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 0.77%   |
| Intel Core i5-5350U CPU @ 1.80GHz           | 1         | 0.77%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 0.77%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 37        | 28.46%  |
| Intel Core i7           | 30        | 23.08%  |
| Intel Core 2 Duo        | 9         | 6.92%   |
| Intel Core i3           | 7         | 5.38%   |
| AMD Ryzen 5             | 7         | 5.38%   |
| Other                   | 3         | 2.31%   |
| Intel Xeon              | 3         | 2.31%   |
| Intel Pentium           | 3         | 2.31%   |
| Intel Celeron           | 3         | 2.31%   |
| Intel Atom              | 3         | 2.31%   |
| AMD Ryzen 7             | 3         | 2.31%   |
| AMD A6                  | 3         | 2.31%   |
| Intel Pentium Dual-Core | 2         | 1.54%   |
| Intel Core i9           | 2         | 1.54%   |
| AMD Athlon 64 X2        | 2         | 1.54%   |
| AMD A8                  | 2         | 1.54%   |
| Intel Pentium Silver    | 1         | 0.77%   |
| Intel Pentium III       | 1         | 0.77%   |
| Intel Pentium D         | 1         | 0.77%   |
| Intel Genuine           | 1         | 0.77%   |
| Intel Core m5           | 1         | 0.77%   |
| Intel Core 2            | 1         | 0.77%   |
| Intel Celeron M         | 1         | 0.77%   |
| AMD Ryzen 9             | 1         | 0.77%   |
| AMD FX                  | 1         | 0.77%   |
| AMD E1                  | 1         | 0.77%   |
| AMD A10                 | 1         | 0.77%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 57        | 43.85%  |
| 4       | 41        | 31.54%  |
| 8       | 9         | 6.92%   |
| Unknown | 8         | 6.15%   |
| 6       | 6         | 4.62%   |
| 12      | 3         | 2.31%   |
| 1       | 3         | 2.31%   |
| 16      | 2         | 1.54%   |
| 24      | 1         | 0.77%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 128       | 99.22%  |
| 2      | 1         | 0.78%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 73        | 56.15%  |
| 1       | 47        | 36.15%  |
| Unknown | 10        | 7.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 24        | 18.46%  |
| Haswell       | 16        | 12.31%  |
| Skylake       | 12        | 9.23%   |
| Penryn        | 11        | 8.46%   |
| IvyBridge     | 11        | 8.46%   |
| SandyBridge   | 10        | 7.69%   |
| Zen+          | 5         | 3.85%   |
| Puma          | 4         | 3.08%   |
| Broadwell     | 4         | 3.08%   |
| Bonnell       | 4         | 3.08%   |
| Zen           | 3         | 2.31%   |
| Nehalem       | 3         | 2.31%   |
| Core          | 3         | 2.31%   |
| Zen 2         | 2         | 1.54%   |
| Westmere      | 2         | 1.54%   |
| Silvermont    | 2         | 1.54%   |
| P6            | 2         | 1.54%   |
| K8 Hammer     | 2         | 1.54%   |
| Goldmont plus | 2         | 1.54%   |
| Zen 3         | 1         | 0.77%   |
| Steamroller   | 1         | 0.77%   |
| Piledriver    | 1         | 0.77%   |
| NetBurst      | 1         | 0.77%   |
| K10 Llano     | 1         | 0.77%   |
| Jaguar        | 1         | 0.77%   |
| Excavator     | 1         | 0.77%   |
| CometLake     | 1         | 0.77%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 82        | 58.57%  |
| Nvidia           | 28        | 20%     |
| AMD              | 28        | 20%     |
| VIA Technologies | 1         | 0.71%   |
| S3 Graphics      | 1         | 0.71%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 5.52%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 5.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 4.83%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 4.83%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 4         | 2.76%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.76%   |
| Intel HD Graphics 620                                                                    | 4         | 2.76%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 2.76%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 2.07%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 2.07%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 2.07%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 2.07%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 1.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.38%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 1.38%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.38%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.38%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.38%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.38%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 1.38%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.38%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 1.38%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.69%   |
| S3 Graphics SuperSavage IX/C SDR                                                         | 1         | 0.69%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.69%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.69%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 0.69%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.69%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.69%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 1         | 0.69%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.69%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.69%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.69%   |
| Nvidia GM107GL [Quadro K2200]                                                            | 1         | 0.69%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 1         | 0.69%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.69%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 1         | 0.69%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 0.69%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.69%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                                     | 1         | 0.69%   |
| Nvidia GF114M [GeForce GTX 580M]                                                         | 1         | 0.69%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.69%   |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 1         | 0.69%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 0.69%   |
| Nvidia G72M [GeForce Go 7400]                                                            | 1         | 0.69%   |
| Nvidia G72 [GeForce 7300 LE]                                                             | 1         | 0.69%   |
| Intel UHD Graphics 615                                                                   | 1         | 0.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.69%   |
| Intel HD Graphics P530                                                                   | 1         | 0.69%   |
| Intel HD Graphics 630                                                                    | 1         | 0.69%   |
| Intel HD Graphics 6000                                                                   | 1         | 0.69%   |
| Intel HD Graphics 530                                                                    | 1         | 0.69%   |
| Intel HD Graphics 515                                                                    | 1         | 0.69%   |
| Intel HD Graphics                                                                        | 1         | 0.69%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 0.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 66        | 50.77%  |
| 1 x AMD         | 25        | 19.23%  |
| 1 x Nvidia      | 19        | 14.62%  |
| Intel + Nvidia  | 8         | 6.15%   |
| 2 x Intel       | 7         | 5.38%   |
| 2 x AMD         | 1         | 0.77%   |
| 1 x VIA         | 1         | 0.77%   |
| 1 x S3 Graphics | 1         | 0.77%   |
| Intel + AMD     | 1         | 0.77%   |
| AMD + Nvidia    | 1         | 0.77%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 100       | 77.52%  |
| Proprietary | 15        | 11.63%  |
| Unknown     | 14        | 10.85%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 101       | 77.69%  |
| 1.01-2.0   | 8         | 6.15%   |
| 0.01-0.5   | 8         | 6.15%   |
| 0.51-1.0   | 5         | 3.85%   |
| 5.01-6.0   | 4         | 3.08%   |
| 7.01-8.0   | 2         | 1.54%   |
| 3.01-4.0   | 2         | 1.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 13        | 11.61%  |
| LG Display              | 12        | 10.71%  |
| BOE                     | 11        | 9.82%   |
| AU Optronics            | 11        | 9.82%   |
| Goldstar                | 8         | 7.14%   |
| Dell                    | 7         | 6.25%   |
| Chimei Innolux          | 7         | 6.25%   |
| Hewlett-Packard         | 5         | 4.46%   |
| Acer                    | 5         | 4.46%   |
| Sharp                   | 3         | 2.68%   |
| Lenovo                  | 3         | 2.68%   |
| HannStar                | 3         | 2.68%   |
| Chi Mei Optoelectronics | 3         | 2.68%   |
| Apple                   | 3         | 2.68%   |
| Philips                 | 2         | 1.79%   |
| Panasonic               | 2         | 1.79%   |
| BenQ                    | 2         | 1.79%   |
| ___                     | 1         | 0.89%   |
| Westinghouse            | 1         | 0.89%   |
| Vizio                   | 1         | 0.89%   |
| ViewSonic               | 1         | 0.89%   |
| Toshiba                 | 1         | 0.89%   |
| Sony                    | 1         | 0.89%   |
| NEC Computers           | 1         | 0.89%   |
| LG Philips              | 1         | 0.89%   |
| LG Electronics          | 1         | 0.89%   |
| CPT                     | 1         | 0.89%   |
| AOC                     | 1         | 0.89%   |
| Ancor Communications    | 1         | 0.89%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch          | 2         | 1.75%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 2         | 1.75%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch             | 2         | 1.75%   |
| BOE LCD Monitor BOE0671 1366x768 340x190mm 15.3-inch                  | 2         | 1.75%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch         | 2         | 1.75%   |
| ___ MY TV LED TV ___0101 1920x1080                                    | 1         | 0.88%   |
| Westinghouse DWM40F3G1 WET1ECC 1920x1080 880x480mm 39.5-inch          | 1         | 0.88%   |
| Vizio SV370XVT VIZ0057 1920x1080 820x460mm 37.0-inch                  | 1         | 0.88%   |
| ViewSonic VX910 VSC3C19 1280x1024 380x300mm 19.1-inch                 | 1         | 0.88%   |
| Toshiba LCD-MONITOR LCDC980 1280x1024 380x300mm 19.1-inch             | 1         | 0.88%   |
| Sony TV SNY5D01 1360x768                                              | 1         | 0.88%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch               | 1         | 0.88%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch               | 1         | 0.88%   |
| Sharp LCD Monitor SHP140E 2560x1440 290x170mm 13.2-inch               | 1         | 0.88%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch     | 1         | 0.88%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 410x260mm 19.1-inch   | 1         | 0.88%   |
| Samsung Electronics S27E330 SAM0D91 1920x1080 600x340mm 27.2-inch     | 1         | 0.88%   |
| Samsung Electronics LF24T450F SAM7094 1920x1080 530x300mm 24.0-inch   | 1         | 0.88%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                     | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 220x130mm 10.1-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 290x160mm 13.0-inch | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 310x170mm 13.9-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 290x160mm 13.0-inch | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch  | 1         | 0.88%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 1         | 0.88%   |
| Philips 170S PHL0856 1280x1024 340x270mm 17.1-inch                    | 1         | 0.88%   |
| NEC Computers EA223WM NEC6890 1680x1050 470x300mm 22.0-inch           | 1         | 0.88%   |
| LG Philips LCD Monitor LPLA101 1440x900 370x230mm 17.2-inch           | 1         | 0.88%   |
| LG Electronics LCD Monitor LG HDR QHD 2560x1440                       | 1         | 0.88%   |
| LG Display LCD Monitor LGD6301 1366x768 340x190mm 15.3-inch           | 1         | 0.88%   |
| LG Display LCD Monitor LGD05B3 1920x1080 290x170mm 13.2-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch           | 1         | 0.88%   |
| LG Display LCD Monitor LGD0414 1920x1080 280x160mm 12.7-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch           | 1         | 0.88%   |
| LG Display LCD Monitor LGD034D 1366x768 340x190mm 15.3-inch           | 1         | 0.88%   |
| LG Display LCD Monitor LGD0303 1600x900 380x210mm 17.1-inch           | 1         | 0.88%   |
| LG Display LCD Monitor LGD01F7 1366x768 290x160mm 13.0-inch           | 1         | 0.88%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch               | 1         | 0.88%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch               | 1         | 0.88%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch               | 1         | 0.88%   |
| Hewlett-Packard W2072a HWP299F 1600x900 440x250mm 19.9-inch           | 1         | 0.88%   |
| Hewlett-Packard vs17 HWP2647 1280x1024 340x270mm 17.1-inch            | 1         | 0.88%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch           | 1         | 0.88%   |
| Hewlett-Packard HPQ 8300 AiO HWP4212 1920x1080 510x290mm 23.1-inch    | 1         | 0.88%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch            | 1         | 0.88%   |
| HannStar LCD Monitor HSD0013 1280x1024 380x300mm 19.1-inch            | 1         | 0.88%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                  | 1         | 0.88%   |
| Goldstar W1943 GSM4BAD 1360x768 410x230mm 18.5-inch                   | 1         | 0.88%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch            | 1         | 0.88%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 1         | 0.88%   |
| Goldstar LCD Monitor GSM5AB7 1920x1080 480x270mm 21.7-inch            | 1         | 0.88%   |
| Goldstar E2742 GSM58C9 1920x1080 600x340mm 27.2-inch                  | 1         | 0.88%   |
| Goldstar E2241 GSM581A 1920x1080 480x270mm 21.7-inch                  | 1         | 0.88%   |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                 | 1         | 0.88%   |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch                     | 1         | 0.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 36        | 32.73%  |
| 1366x768 (WXGA)    | 30        | 27.27%  |
| 1280x1024 (SXGA)   | 10        | 9.09%   |
| 1600x900 (HD+)     | 7         | 6.36%   |
| 3840x2160 (4K)     | 4         | 3.64%   |
| 1440x900 (WXGA+)   | 4         | 3.64%   |
| 1024x600           | 4         | 3.64%   |
| 1280x800 (WXGA)    | 3         | 2.73%   |
| 2880x1620          | 2         | 1.82%   |
| 2560x1440 (QHD)    | 2         | 1.82%   |
| 1680x1050 (WSXGA+) | 2         | 1.82%   |
| 1360x768           | 2         | 1.82%   |
| 3200x1800 (QHD+)   | 1         | 0.91%   |
| 2880x1800          | 1         | 0.91%   |
| 1920x1200 (WUXGA)  | 1         | 0.91%   |
| 1600x1200          | 1         | 0.91%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 28        | 24.78%  |
| 13      | 19        | 16.81%  |
| 17      | 12        | 10.62%  |
| 24      | 8         | 7.08%   |
| 19      | 8         | 7.08%   |
| 21      | 6         | 5.31%   |
| 12      | 6         | 5.31%   |
| 27      | 5         | 4.42%   |
| 10      | 4         | 3.54%   |
| Unknown | 4         | 3.54%   |
| 18      | 3         | 2.65%   |
| 11      | 3         | 2.65%   |
| 23      | 2         | 1.77%   |
| 22      | 2         | 1.77%   |
| 39      | 1         | 0.88%   |
| 37      | 1         | 0.88%   |
| 14      | 1         | 0.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 44        | 39.29%  |
| 201-300     | 23        | 20.54%  |
| 401-500     | 14        | 12.5%   |
| 501-600     | 13        | 11.61%  |
| 351-400     | 10        | 8.93%   |
| Unknown     | 4         | 3.57%   |
| 801-900     | 2         | 1.79%   |
| 601-700     | 2         | 1.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 80        | 76.92%  |
| 16/10   | 12        | 11.54%  |
| 5/4     | 10        | 9.62%   |
| Unknown | 2         | 1.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 22        | 19.47%  |
| 201-250        | 17        | 15.04%  |
| 81-90          | 13        | 11.5%   |
| 141-150        | 9         | 7.96%   |
| 151-200        | 8         | 7.08%   |
| 71-80          | 7         | 6.19%   |
| 61-70          | 6         | 5.31%   |
| 101-110        | 6         | 5.31%   |
| 301-350        | 5         | 4.42%   |
| 121-130        | 5         | 4.42%   |
| 41-50          | 4         | 3.54%   |
| Unknown        | 4         | 3.54%   |
| 51-60          | 3         | 2.65%   |
| 501-1000       | 2         | 1.77%   |
| 251-300        | 1         | 0.88%   |
| 131-140        | 1         | 0.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 38        | 34.86%  |
| 51-100        | 32        | 29.36%  |
| 121-160       | 22        | 20.18%  |
| 161-240       | 11        | 10.09%  |
| Unknown       | 4         | 3.67%   |
| More than 240 | 2         | 1.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 98        | 74.81%  |
| 0     | 24        | 18.32%  |
| 2     | 7         | 5.34%   |
| 3     | 2         | 1.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 72        | 38.71%  |
| Realtek Semiconductor             | 54        | 29.03%  |
| Qualcomm Atheros                  | 27        | 14.52%  |
| Broadcom                          | 10        | 5.38%   |
| Ralink                            | 3         | 1.61%   |
| Qualcomm                          | 2         | 1.08%   |
| Mellanox Technologies             | 2         | 1.08%   |
| Marvell Technology Group          | 2         | 1.08%   |
| Fibocom                           | 2         | 1.08%   |
| VIA Technologies                  | 1         | 0.54%   |
| TP-Link                           | 1         | 0.54%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.54%   |
| Sierra Wireless                   | 1         | 0.54%   |
| Ralink Technology                 | 1         | 0.54%   |
| Nvidia                            | 1         | 0.54%   |
| Microchip Technology              | 1         | 0.54%   |
| JMicron Technology                | 1         | 0.54%   |
| Ericsson Business Mobile Networks | 1         | 0.54%   |
| D-Link System                     | 1         | 0.54%   |
| Brooktrout Technology             | 1         | 0.54%   |
| Atheros                           | 1         | 0.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 14.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 4.92%   |
| Intel Wireless 7260                                               | 10        | 4.1%    |
| Intel Wireless 8265 / 8275                                        | 7         | 2.87%   |
| Intel Wireless 8260                                               | 6         | 2.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 2.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 2.05%   |
| Intel Wireless 3165                                               | 5         | 2.05%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 2.05%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 2.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 1.64%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.23%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 1.23%   |
| Intel Wireless 7265                                               | 3         | 1.23%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.23%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 1.23%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3         | 1.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.82%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 2         | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.82%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 2         | 0.82%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 2         | 0.82%   |
| Intel Wireless-AC 9260                                            | 2         | 0.82%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.82%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.82%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.82%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.82%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.82%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.82%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                 | 2         | 0.82%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.41%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.41%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.41%   |
| Sierra Wireless EM7455                                            | 1         | 0.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.41%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.41%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1         | 0.41%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.41%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.41%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.41%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.41%   |
| Realtek Realtek Bluetooth 4.2 Adapter                             | 1         | 0.41%   |
| Ralink RT5372 Wireless Adapter                                    | 1         | 0.41%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 0.41%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.41%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.41%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.41%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 56        | 50%     |
| Qualcomm Atheros      | 22        | 19.64%  |
| Realtek Semiconductor | 19        | 16.96%  |
| Broadcom              | 7         | 6.25%   |
| Ralink                | 3         | 2.68%   |
| TP-Link               | 1         | 0.89%   |
| Sierra Wireless       | 1         | 0.89%   |
| Ralink Technology     | 1         | 0.89%   |
| D-Link System         | 1         | 0.89%   |
| Atheros               | 1         | 0.89%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                                   | 10        | 8.7%    |
| Intel Wireless 8265 / 8275                                                            | 7         | 6.09%   |
| Intel Wireless 8260                                                                   | 6         | 5.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 5         | 4.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 5         | 4.35%   |
| Intel Wireless 3165                                                                   | 5         | 4.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 4         | 3.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 2.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 3         | 2.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 3         | 2.61%   |
| Intel Wireless 7265                                                                   | 3         | 2.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 3         | 2.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 3         | 2.61%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 3         | 2.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 2         | 1.74%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 2         | 1.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 2         | 1.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 1.74%   |
| Intel Wireless-AC 9260                                                                | 2         | 1.74%   |
| Intel Centrino Advanced-N 6200                                                        | 2         | 1.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 2         | 1.74%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 0.87%   |
| Sierra Wireless EM7455                                                                | 1         | 0.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.87%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1         | 0.87%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.87%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1         | 0.87%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 0.87%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1         | 0.87%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.87%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 0.87%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                                 | 1         | 0.87%   |
| Ralink RT5372 Wireless Adapter                                                        | 1         | 0.87%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 1         | 0.87%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.87%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.87%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.87%   |
| Intel WiMAX/WiFi Link 5150                                                            | 1         | 0.87%   |
| Intel WiFi Link 5100                                                                  | 1         | 0.87%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 0.87%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 1         | 0.87%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 0.87%   |
| Intel Centrino Wireless-N 6150                                                        | 1         | 0.87%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 0.87%   |
| Intel Centrino Wireless-N 105                                                         | 1         | 0.87%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                         | 1         | 0.87%   |
| Intel Centrino WiMAX 6150                                                             | 1         | 0.87%   |
| Intel Centrino Ultimate-N 6300                                                        | 1         | 0.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 1         | 0.87%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]                  | 1         | 0.87%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                           | 1         | 0.87%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                    | 1         | 0.87%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 1         | 0.87%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller                   | 1         | 0.87%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 0.87%   |
| Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]                  | 1         | 0.87%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 50        | 41.67%  |
| Intel                            | 49        | 40.83%  |
| Qualcomm Atheros                 | 7         | 5.83%   |
| Broadcom                         | 6         | 5%      |
| Qualcomm                         | 2         | 1.67%   |
| Marvell Technology Group         | 2         | 1.67%   |
| VIA Technologies                 | 1         | 0.83%   |
| Silicon Integrated Systems [SiS] | 1         | 0.83%   |
| Nvidia                           | 1         | 0.83%   |
| JMicron Technology               | 1         | 0.83%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 28.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 9.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 4.92%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 4.1%    |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 4.1%    |
| Intel Ethernet Connection (2) I219-V                              | 4         | 3.28%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 2.46%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.46%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 2.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.64%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 2         | 1.64%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.64%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.64%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.64%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.64%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.64%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.82%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.82%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.82%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.82%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.82%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.82%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.82%   |
| Nvidia MCP73 Ethernet                                             | 1         | 0.82%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.82%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.82%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.82%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1         | 0.82%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.82%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.82%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.82%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.82%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.82%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.82%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.82%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.82%   |
| Intel 82801CAM (ICH3) PRO/100 VE (LOM) Ethernet Controller        | 1         | 0.82%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.82%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.82%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 0.82%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1         | 0.82%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1         | 0.82%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 0.82%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.82%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 0.82%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1         | 0.82%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 117       | 50.87%  |
| WiFi     | 106       | 46.09%  |
| Unknown  | 6         | 2.61%   |
| Modem    | 1         | 0.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 112       | 56%     |
| WiFi     | 83        | 41.5%   |
| Unknown  | 5         | 2.5%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 91        | 70%     |
| 1     | 37        | 28.46%  |
| 4     | 1         | 0.77%   |
| 3     | 1         | 0.77%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 121       | 93.08%  |
| Yes  | 9         | 6.92%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 48.68%  |
| Realtek Semiconductor           | 5         | 6.58%   |
| Qualcomm Atheros Communications | 5         | 6.58%   |
| Lite-On Technology              | 5         | 6.58%   |
| Broadcom                        | 5         | 6.58%   |
| IMC Networks                    | 4         | 5.26%   |
| ASUSTek Computer                | 4         | 5.26%   |
| Apple                           | 4         | 5.26%   |
| Foxconn / Hon Hai               | 2         | 2.63%   |
| Cambridge Silicon Radio         | 2         | 2.63%   |
| Hewlett-Packard                 | 1         | 1.32%   |
| Dell                            | 1         | 1.32%   |
| Alps Electric                   | 1         | 1.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 25        | 32.89%  |
| Intel AX201 Bluetooth                                       | 4         | 5.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3         | 3.95%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 2.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 2.63%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 2.63%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 2.63%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 2.63%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 2.63%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 2.63%   |
| ASUS BT-253 Bluetooth Adapter                               | 2         | 2.63%   |
| Apple Bluetooth Host Controller                             | 2         | 2.63%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 2         | 2.63%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 1.32%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 1.32%   |
| Realtek  Bluetooth 4.0 Adapter                              | 1         | 1.32%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 1         | 1.32%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.32%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device        | 1         | 1.32%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.32%   |
| Lite-On Bluetooth USB Module                                | 1         | 1.32%   |
| Lite-On Atheros Bluetooth                                   | 1         | 1.32%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.32%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 1.32%   |
| Intel AX200 Bluetooth                                       | 1         | 1.32%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 1.32%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 1.32%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.32%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 1.32%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 1.32%   |
| Dell DW375 Bluetooth Module                                 | 1         | 1.32%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 1         | 1.32%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.32%   |
| Broadcom BCM2045 Bluetooth                                  | 1         | 1.32%   |
| ASUS Bluetooth Controller                                   | 1         | 1.32%   |
| ASUS ASUS USB-BT500                                         | 1         | 1.32%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 1.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 103       | 62.05%  |
| AMD                              | 30        | 18.07%  |
| Nvidia                           | 19        | 11.45%  |
| Sony                             | 2         | 1.2%    |
| Corsair                          | 2         | 1.2%    |
| C-Media Electronics              | 2         | 1.2%    |
| XMOS                             | 1         | 0.6%    |
| VIA Technologies                 | 1         | 0.6%    |
| Silicon Integrated Systems [SiS] | 1         | 0.6%    |
| Realtek Semiconductor            | 1         | 0.6%    |
| Quanta                           | 1         | 0.6%    |
| Creative Technology              | 1         | 0.6%    |
| Blue Microphones                 | 1         | 0.6%    |
| Audio-Technica                   | 1         | 0.6%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 18        | 8.87%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 5.91%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 4.43%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 4.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 3.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 3.45%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 3.45%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 3.45%   |
| AMD FCH Azalia Controller                                                                         | 7         | 3.45%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 2.96%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 2.46%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 1.97%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.97%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.97%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.97%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.97%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 1.48%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.48%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 1.48%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.48%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.48%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.99%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.99%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 0.99%   |
| Corsair Corsair VOID PRO Wireless Gaming Headset                                                  | 2         | 0.99%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 0.99%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.99%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 0.99%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.99%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 0.99%   |
| XMOS XMOS XS1-U8 MFA (ST)                                                                         | 1         | 0.49%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.49%   |
| Sony Sony Audio                                                                                   | 1         | 0.49%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.49%   |
| Realtek Semiconductor Realtek USB Audio                                                           | 1         | 0.49%   |
| Quanta USB Audio Realtek USB2.0 Audio Microphone                                                  | 1         | 0.49%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.49%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.49%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.49%   |
| Nvidia MCP73 High Definition Audio                                                                | 1         | 0.49%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.49%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.49%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.49%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.49%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.49%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.49%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.49%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.49%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.49%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 0.49%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 0.49%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1         | 0.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.49%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                                          | 1         | 0.49%   |
| Creative Technology Sound Blaster Omni Surround 5.1                                               | 1         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 36        | 24.16%  |
| SK Hynix            | 29        | 19.46%  |
| Micron Technology   | 17        | 11.41%  |
| Unknown             | 15        | 10.07%  |
| Kingston            | 12        | 8.05%   |
| Crucial             | 8         | 5.37%   |
| G.Skill             | 6         | 4.03%   |
| Elpida              | 6         | 4.03%   |
| Corsair             | 5         | 3.36%   |
| Nanya Technology    | 4         | 2.68%   |
| Transcend           | 2         | 1.34%   |
| A-DATA Technology   | 2         | 1.34%   |
| Unknown             | 2         | 1.34%   |
| Unknown (ABCD)      | 1         | 0.67%   |
| Unknown (09D5)      | 1         | 0.67%   |
| Magnum Tech         | 1         | 0.67%   |
| EVGA                | 1         | 0.67%   |
| 48spaces            | 1         | 0.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s              | 6         | 3.73%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 4         | 2.48%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 1.86%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 3         | 1.86%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s               | 3         | 1.86%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 1.86%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 2         | 1.24%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                            | 2         | 1.24%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 2         | 1.24%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.24%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.24%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.24%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                       | 2         | 1.24%   |
| Micron RAM ITC 4096MB DIMM DDR3 1066MT/s                            | 2         | 1.24%   |
| Unknown                                                             | 2         | 1.24%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                           | 1         | 0.62%   |
| Unknown SODIMM 1024MB SODIMM DDR2 667MT/s                           | 1         | 0.62%   |
| Unknown RAM Module 512MB SODIMM SDRAM                               | 1         | 0.62%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                      | 1         | 0.62%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 1         | 0.62%   |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 1         | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                            | 1         | 0.62%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                              | 1         | 0.62%   |
| Unknown RAM Module 1GB SODIMM DRAM 533MT/s                          | 1         | 0.62%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 1         | 0.62%   |
| Unknown RAM Module 128MB SODIMM SDRAM                               | 1         | 0.62%   |
| Unknown RAM Module 1024MB SODIMM RAM                                | 1         | 0.62%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s                         | 1         | 0.62%   |
| Unknown RAM 7TE39AA# 8GB DIMM DDR4 2667MT/s                         | 1         | 0.62%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB SODIMM LPDDR4 2133MT/s | 1         | 0.62%   |
| Unknown (09D5) RAM Module 16GB SODIMM DDR4 2400MT/s                 | 1         | 0.62%   |
| Transcend RAM TS512MSK64V1N 4GB SODIMM 800MT/s                      | 1         | 0.62%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR 667MT/s                    | 1         | 0.62%   |
| SK Hynix RAM Zhidian4GDDR800000 4GB DIMM DDR2 800MT/s               | 1         | 0.62%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 1         | 0.62%   |
| SK Hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s                | 1         | 0.62%   |
| SK Hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s                | 1         | 0.62%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s                | 1         | 0.62%   |
| SK Hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.62%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.62%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s                | 1         | 0.62%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM 192MT/s                      | 1         | 0.62%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1333MT/s              | 1         | 0.62%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.62%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 1         | 0.62%   |
| SK Hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s                | 1         | 0.62%   |
| SK Hynix RAM HMT31GR7AFR4C-H9 8GB DIMM DDR3 1333MT/s                | 1         | 0.62%   |
| SK Hynix RAM HMT125U6AFP8C-G7 2048MB DIMM DDR3 1066MT/s             | 1         | 0.62%   |
| SK Hynix RAM HMT112U6AFP8C-G7 1GB DIMM 1066MT/s                     | 1         | 0.62%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s          | 1         | 0.62%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 0.62%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.62%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s              | 1         | 0.62%   |
| SK Hynix RAM H9CCNNNBJTMLAR-NUD 4096MB SODIMM LPDDR3 1867MT/s       | 1         | 0.62%   |
| SK Hynix RAM H5TC8G63AMR-PBA 4096MB 1600MT/s                        | 1         | 0.62%   |
| Samsung RAM Module 16GB SODIMM DDR4 2133MT/s                        | 1         | 0.62%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s               | 1         | 0.62%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s               | 1         | 0.62%   |
| Samsung RAM M471B5273DH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 0.62%   |
| Samsung RAM M471B5273CM0-CH9 4GB SODIMM DDR3 1333MT/s               | 1         | 0.62%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 57        | 43.51%  |
| DDR4    | 42        | 32.06%  |
| DDR2    | 14        | 10.69%  |
| LPDDR3  | 5         | 3.82%   |
| SDRAM   | 4         | 3.05%   |
| Unknown | 4         | 3.05%   |
| DDR     | 2         | 1.53%   |
| RAM     | 1         | 0.76%   |
| LPDDR4  | 1         | 0.76%   |
| DRAM    | 1         | 0.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 87        | 66.92%  |
| DIMM         | 37        | 28.46%  |
| Row Of Chips | 2         | 1.54%   |
| Chip         | 2         | 1.54%   |
| Unknown      | 2         | 1.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 58        | 39.46%  |
| 8192  | 42        | 28.57%  |
| 2048  | 24        | 16.33%  |
| 16384 | 11        | 7.48%   |
| 1024  | 9         | 6.12%   |
| 32768 | 1         | 0.68%   |
| 512   | 1         | 0.68%   |
| 128   | 1         | 0.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 39        | 28.26%  |
| 2400    | 19        | 13.77%  |
| 2667    | 13        | 9.42%   |
| 1333    | 10        | 7.25%   |
| 800     | 9         | 6.52%   |
| 2133    | 8         | 5.8%    |
| 3200    | 7         | 5.07%   |
| 1334    | 6         | 4.35%   |
| 667     | 6         | 4.35%   |
| Unknown | 6         | 4.35%   |
| 1066    | 4         | 2.9%    |
| 3600    | 2         | 1.45%   |
| 2933    | 2         | 1.45%   |
| 1867    | 2         | 1.45%   |
| 533     | 2         | 1.45%   |
| 1866    | 1         | 0.72%   |
| 1067    | 1         | 0.72%   |
| 192     | 1         | 0.72%   |

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
| Chicony Electronics                    | 18        | 24.32%  |
| Realtek Semiconductor                  | 9         | 12.16%  |
| Acer                                   | 8         | 10.81%  |
| Sunplus Innovation Technology          | 7         | 9.46%   |
| Suyin                                  | 5         | 6.76%   |
| Logitech                               | 4         | 5.41%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 5.41%   |
| Silicon Motion                         | 3         | 4.05%   |
| Quanta                                 | 3         | 4.05%   |
| Microdia                               | 3         | 4.05%   |
| IMC Networks                           | 3         | 4.05%   |
| Lite-On Technology                     | 2         | 2.7%    |
| Novatek Microelectronics               | 1         | 1.35%   |
| Intel                                  | 1         | 1.35%   |
| Genesys Logic                          | 1         | 1.35%   |
| Apple                                  | 1         | 1.35%   |
| Alcor Micro                            | 1         | 1.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 8         | 10.67%  |
| Sunplus Integrated_Webcam_HD                                   | 4         | 5.33%   |
| Acer Integrated Camera                                         | 4         | 5.33%   |
| Suyin Acer Crystal Eye webcam                                  | 2         | 2.67%   |
| Realtek Realtek USB2.0 PC Camera                               | 2         | 2.67%   |
| Realtek Lenovo EasyCamera                                      | 2         | 2.67%   |
| Quanta Realtek DMFT - RGB                                      | 2         | 2.67%   |
| Chicony HD WebCam                                              | 2         | 2.67%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam            | 2         | 2.67%   |
| Suyin Laptop_Integrated_Webcam_3M                              | 1         | 1.33%   |
| Suyin HD WebCam                                                | 1         | 1.33%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 1         | 1.33%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 1.33%   |
| Sunplus Integrated Webcam                                      | 1         | 1.33%   |
| Sunplus Asus Webcam                                            | 1         | 1.33%   |
| Silicon Motion WebCam SCX Series                               | 1         | 1.33%   |
| Silicon Motion Realtek USB2.0 PC Camera                        | 1         | 1.33%   |
| Silicon Motion 300k Pixel Camera                               | 1         | 1.33%   |
| Realtek USB2.0 VGA UVC WebCam                                  | 1         | 1.33%   |
| Realtek USB2.0 HD UVC WebCam                                   | 1         | 1.33%   |
| Realtek USB Camera                                             | 1         | 1.33%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 1.33%   |
| Realtek HD Webcam - Realtek                                    | 1         | 1.33%   |
| Quanta Front camera                                            | 1         | 1.33%   |
| Novatek HP High Definition 2MP Webcam                          | 1         | 1.33%   |
| Microdia Sonix USB 2.0 Camera                                  | 1         | 1.33%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 1.33%   |
| Microdia Integrated Webcam                                     | 1         | 1.33%   |
| Logitech Webcam C310                                           | 1         | 1.33%   |
| Logitech Webcam C270                                           | 1         | 1.33%   |
| Logitech HD Pro Webcam C920                                    | 1         | 1.33%   |
| Logitech C505 HD Webcam                                        | 1         | 1.33%   |
| Lite-On Integrated Camera                                      | 1         | 1.33%   |
| Lite-On HP Universal Camera                                    | 1         | 1.33%   |
| Intel WiMAX Connection 2400m                                   | 1         | 1.33%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 1         | 1.33%   |
| IMC Networks USB2.0 UVC HD Webcam                              | 1         | 1.33%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 1.33%   |
| Genesys Logic Camera                                           | 1         | 1.33%   |
| Chicony Webcam                                                 | 1         | 1.33%   |
| Chicony USB2.0 HD UVC WebCam                                   | 1         | 1.33%   |
| Chicony Thinkpad T430 camera                                   | 1         | 1.33%   |
| Chicony Realtek DMFT - IR                                      | 1         | 1.33%   |
| Chicony Lenovo EasyCamera                                      | 1         | 1.33%   |
| Chicony Integrated Camera [ThinkPad]                           | 1         | 1.33%   |
| Chicony Integrated Camera (1280x720@30)                        | 1         | 1.33%   |
| Chicony HP TrueVision HD Camera                                | 1         | 1.33%   |
| Chicony FJ Camera                                              | 1         | 1.33%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.33%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 1         | 1.33%   |
| Apple FaceTime HD Camera                                       | 1         | 1.33%   |
| Alcor Micro HP WebCam-101                                      | 1         | 1.33%   |
| Acer USB2.0 Camera                                             | 1         | 1.33%   |
| Acer NEC HD WebCam                                             | 1         | 1.33%   |
| Acer Lenovo EasyCamera                                         | 1         | 1.33%   |
| Acer EasyCamera                                                | 1         | 1.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 9         | 60%     |
| Synaptics        | 4         | 26.67%  |
| Upek             | 1         | 6.67%   |
| Broadcom         | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 13.33%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 2         | 13.33%  |
| Validity Sensors Synaptics WBDI                                              | 2         | 13.33%  |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 13.33%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 2         | 13.33%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 6.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.67%   |
| Unknown                                                                      | 1         | 6.67%   |

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
| 1     | 47        | 35.61%  |
| 2     | 39        | 29.55%  |
| 0     | 23        | 17.42%  |
| 3     | 14        | 10.61%  |
| 4     | 5         | 3.79%   |
| 5     | 2         | 1.52%   |
| 7     | 1         | 0.76%   |
| 6     | 1         | 0.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 85        | 44.74%  |
| Net/wireless             | 29        | 15.26%  |
| Bluetooth                | 21        | 11.05%  |
| Firewire controller      | 17        | 8.95%   |
| Card reader              | 16        | 8.42%   |
| Fingerprint reader       | 15        | 7.89%   |
| Network                  | 4         | 2.11%   |
| Sound                    | 2         | 1.05%   |
| Storage/raid             | 1         | 0.53%   |

