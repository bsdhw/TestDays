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

Total: 220

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Chuwi         | CoreBook X                  | Notebook    | [2854f97c81](https://bsd-hardware.info/?probe=2854f97c81) | Aug 01, 2023 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [7a5d32eb7f](https://bsd-hardware.info/?probe=7a5d32eb7f) | Jul 29, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [648c09752f](https://bsd-hardware.info/?probe=648c09752f) | Jun 27, 2023 |
| HP            | EliteBook 750 G1            | Notebook    | [e0af4797d4](https://bsd-hardware.info/?probe=e0af4797d4) | Jun 24, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | Notebook    | [461a92a1a2](https://bsd-hardware.info/?probe=461a92a1a2) | Jun 20, 2023 |
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

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| NomadBSD 5806f915 | 54        | 30.86%  |
| NomadBSD 1.3.2    | 52        | 29.71%  |
| NomadBSD 1.4      | 23        | 13.14%  |
| NomadBSD 20221130 | 22        | 12.57%  |
| NomadBSD 1.4-RC1  | 10        | 5.71%   |
| NomadBSD 1.3.1    | 10        | 5.71%   |
| NomadBSD 81e34fc3 | 1         | 0.57%   |
| NomadBSD 80dec9b9 | 1         | 0.57%   |
| NomadBSD 1.3      | 1         | 0.57%   |
| NomadBSD 1.0      | 1         | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| NomadBSD | 170       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 162       | 94.74%  |
| i386  | 9         | 5.26%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Openbox       | 147       | 85.96%  |
| GNOME         | 7         | 4.09%   |
| xinitrc       | 6         | 3.51%   |
| KDE5          | 5         | 2.92%   |
| Enlightenment | 3         | 1.75%   |
| XFCE          | 1         | 0.58%   |
| GNUstep       | 1         | 0.58%   |
| filer         | 1         | 0.58%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 170       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SLiM    | 144       | 84.71%  |
| SDDM    | 24        | 14.12%  |
| LightDM | 2         | 1.18%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 63        | 36.63%  |
| Unknown | 31        | 18.02%  |
| de_DE   | 17        | 9.88%   |
| en_GB   | 12        | 6.98%   |
| ru_RU   | 8         | 4.65%   |
| fr_FR   | 6         | 3.49%   |
| it_IT   | 5         | 2.91%   |
| hu_HU   | 5         | 2.91%   |
| zh_CN   | 3         | 1.74%   |
| tr_TR   | 3         | 1.74%   |
| fi_FI   | 3         | 1.74%   |
| es_ES   | 3         | 1.74%   |
| pt_BR   | 2         | 1.16%   |
| pl_PL   | 2         | 1.16%   |
| en_AU   | 2         | 1.16%   |
| cs_CZ   | 2         | 1.16%   |
| bg_BG   | 2         | 1.16%   |
| lt_LT   | 1         | 0.58%   |
| ko_KR   | 1         | 0.58%   |
| et_EE   | 1         | 0.58%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 164       | 95.91%  |
| BIOS | 7         | 4.09%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ufs  | 145       | 85.29%  |
| Zfs  | 25        | 14.71%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 121       | 70.76%  |
| MBR  | 50        | 29.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 33        | 19.41%  |
| Hewlett-Packard     | 25        | 14.71%  |
| Dell                | 24        | 14.12%  |
| ASUSTek Computer    | 22        | 12.94%  |
| Acer                | 11        | 6.47%   |
| Gigabyte Technology | 6         | 3.53%   |
| ASRock              | 6         | 3.53%   |
| Apple               | 5         | 2.94%   |
| TUXEDO              | 3         | 1.76%   |
| Sony                | 3         | 1.76%   |
| Samsung Electronics | 3         | 1.76%   |
| Intel               | 3         | 1.76%   |
| Fujitsu             | 3         | 1.76%   |
| Pegatron            | 2         | 1.18%   |
| Notebook            | 2         | 1.18%   |
| Google              | 2         | 1.18%   |
| Fujitsu Siemens     | 2         | 1.18%   |
| Unknown             | 2         | 1.18%   |
| Toshiba             | 1         | 0.59%   |
| Semp Toshiba        | 1         | 0.59%   |
| Panasonic           | 1         | 0.59%   |
| NEC Computers       | 1         | 0.59%   |
| MSI                 | 1         | 0.59%   |
| IBM                 | 1         | 0.59%   |
| GEO                 | 1         | 0.59%   |
| Foxconn             | 1         | 0.59%   |
| ECS                 | 1         | 0.59%   |
| Clevo               | 1         | 0.59%   |
| Chuwi               | 1         | 0.59%   |
| ASRockRack          | 1         | 0.59%   |
| Alienware           | 1         | 0.59%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Unknown                                   | 3         | 1.76%   |
| HP Z420 Workstation                       | 2         | 1.18%   |
| ASUS ROG STRIX B550-F GAMING              | 2         | 1.18%   |
| Acer Veriton M460                         | 2         | 1.18%   |
| TUXEDO Pulse 15 Gen2                      | 1         | 0.59%   |
| TUXEDO InfinityBook S 15 Gen6             | 1         | 0.59%   |
| Toshiba Satellite C660                    | 1         | 0.59%   |
| Sony VPCM13M1R                            | 1         | 0.59%   |
| Sony VJS121C11N                           | 1         | 0.59%   |
| Sony SVE1713S1RW                          | 1         | 0.59%   |
| Semp Toshiba STI                          | 1         | 0.59%   |
| Samsung N150/N210/N220                    | 1         | 0.59%   |
| Samsung N145P/N250P/N260P                 | 1         | 0.59%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV   | 1         | 0.59%   |
| Pegatron T12Ah                            | 1         | 0.59%   |
| Pegatron Elite 7300 Series MT             | 1         | 0.59%   |
| Panasonic CF-C1BD06EFG                    | 1         | 0.59%   |
| Notebook W650DC,DD                        | 1         | 0.59%   |
| Notebook N650DU                           | 1         | 0.59%   |
| NEC Computers PC-GL186Y3AZ                | 1         | 0.59%   |
| MSI MS-N033                               | 1         | 0.59%   |
| Lenovo Yoga 710-11IKB 80V6                | 1         | 0.59%   |
| Lenovo V580 20147                         | 1         | 0.59%   |
| Lenovo ThinkPad X380 Yoga 20LJ000WUK      | 1         | 0.59%   |
| Lenovo ThinkPad X280 20KESB4T00           | 1         | 0.59%   |
| Lenovo ThinkPad X230 23255NG              | 1         | 0.59%   |
| Lenovo ThinkPad X201 Tablet 311396U       | 1         | 0.59%   |
| Lenovo ThinkPad X13 Yoga Gen 1 20SYS22H00 | 1         | 0.59%   |
| Lenovo ThinkPad X1 Yoga 3rd 20LDS1CG00    | 1         | 0.59%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB001XAU  | 1         | 0.59%   |
| Lenovo ThinkPad W541 20EGS04800           | 1         | 0.59%   |
| Lenovo ThinkPad W520 42844DG              | 1         | 0.59%   |
| Lenovo ThinkPad T530 24295VU              | 1         | 0.59%   |
| Lenovo ThinkPad T510 4384FF3              | 1         | 0.59%   |
| Lenovo ThinkPad T490s 20NX000DRT          | 1         | 0.59%   |
| Lenovo ThinkPad T490 20RYS06R00           | 1         | 0.59%   |
| Lenovo ThinkPad T480 20L50000GE           | 1         | 0.59%   |
| Lenovo ThinkPad T470s W10DG 20JS001FGE    | 1         | 0.59%   |
| Lenovo ThinkPad T470 20HES0EV0A           | 1         | 0.59%   |
| Lenovo ThinkPad T460 20FMS78014           | 1         | 0.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 24        | 14.12%  |
| Dell Latitude              | 9         | 5.29%   |
| Acer Aspire                | 8         | 4.71%   |
| Dell OptiPlex              | 5         | 2.94%   |
| HP Compaq                  | 4         | 2.35%   |
| HP ProBook                 | 3         | 1.76%   |
| HP Pavilion                | 3         | 1.76%   |
| Dell Studio                | 3         | 1.76%   |
| Dell Inspiron              | 3         | 1.76%   |
| ASUS ROG                   | 3         | 1.76%   |
| Unknown                    | 3         | 1.76%   |
| Lenovo IdeaPad             | 2         | 1.18%   |
| HP Z420                    | 2         | 1.18%   |
| HP Laptop                  | 2         | 1.18%   |
| HP EliteBook               | 2         | 1.18%   |
| Gigabyte Z370              | 2         | 1.18%   |
| Gigabyte X570              | 2         | 1.18%   |
| Fujitsu Siemens AMILO      | 2         | 1.18%   |
| Fujitsu LIFEBOOK           | 2         | 1.18%   |
| ASUS TUF                   | 2         | 1.18%   |
| ASUS PRIME                 | 2         | 1.18%   |
| Acer Veriton               | 2         | 1.18%   |
| TUXEDO Pulse               | 1         | 0.59%   |
| TUXEDO InfinityBook        | 1         | 0.59%   |
| Toshiba Satellite          | 1         | 0.59%   |
| Sony VPCM13M1R             | 1         | 0.59%   |
| Sony VJS121C11N            | 1         | 0.59%   |
| Sony SVE1713S1RW           | 1         | 0.59%   |
| Semp Toshiba STI           | 1         | 0.59%   |
| Samsung N150               | 1         | 0.59%   |
| Samsung N145P              | 1         | 0.59%   |
| Samsung 300E5EV            | 1         | 0.59%   |
| Pegatron T12Ah             | 1         | 0.59%   |
| Pegatron Elite             | 1         | 0.59%   |
| Panasonic CF-C1BD06EFG     | 1         | 0.59%   |
| Notebook W650DC            | 1         | 0.59%   |
| Notebook N650DU            | 1         | 0.59%   |
| NEC Computers PC-GL186Y3AZ | 1         | 0.59%   |
| MSI MS-N033                | 1         | 0.59%   |
| Lenovo Yoga                | 1         | 0.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 22        | 12.94%  |
| 2020 | 20        | 11.76%  |
| 2017 | 15        | 8.82%   |
| 2013 | 12        | 7.06%   |
| 2021 | 11        | 6.47%   |
| 2012 | 11        | 6.47%   |
| 2018 | 10        | 5.88%   |
| 2015 | 10        | 5.88%   |
| 2009 | 10        | 5.88%   |
| 2010 | 9         | 5.29%   |
| 2014 | 8         | 4.71%   |
| 2011 | 8         | 4.71%   |
| 2016 | 7         | 4.12%   |
| 2008 | 7         | 4.12%   |
| 2022 | 4         | 2.35%   |
| 2006 | 3         | 1.76%   |
| 2023 | 1         | 0.59%   |
| 2007 | 1         | 0.59%   |
| 2004 | 1         | 0.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 111       | 65.29%  |
| Desktop     | 49        | 28.82%  |
| Convertible | 5         | 2.94%   |
| Mini pc     | 2         | 1.18%   |
| All in one  | 2         | 1.18%   |
| Server      | 1         | 0.59%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 167       | 98.24%  |
| Yes  | 3         | 1.76%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 64        | 37.43%  |
| 16.01-24.0  | 39        | 22.81%  |
| 4.01-8.0    | 34        | 19.88%  |
| 32.01-64.0  | 14        | 8.19%   |
| 2.01-3.0    | 6         | 3.51%   |
| 64.01-256.0 | 6         | 3.51%   |
| 3.01-4.0    | 3         | 1.75%   |
| 0.51-1.0    | 3         | 1.75%   |
| 24.01-32.0  | 2         | 1.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 87        | 50.29%  |
| 0.51-1.0  | 52        | 30.06%  |
| 1.01-2.0  | 23        | 13.29%  |
| 2.01-3.0  | 7         | 4.05%   |
| 4.01-8.0  | 2         | 1.16%   |
| 3.01-4.0  | 1         | 0.58%   |
| 8.01-16.0 | 1         | 0.58%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 112       | 65.5%   |
| 2      | 32        | 18.71%  |
| 3      | 13        | 7.6%    |
| 0      | 9         | 5.26%   |
| 4      | 4         | 2.34%   |
| 7      | 1         | 0.58%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 105       | 61.4%   |
| Yes       | 66        | 38.6%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 153       | 89.47%  |
| No        | 18        | 10.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 139       | 81.76%  |
| No        | 31        | 18.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 99        | 57.89%  |
| No        | 72        | 42.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 36        | 21.18%  |
| Germany     | 21        | 12.35%  |
| France      | 19        | 11.18%  |
| Russia      | 17        | 10%     |
| UK          | 11        | 6.47%   |
| Italy       | 7         | 4.12%   |
| Turkey      | 5         | 2.94%   |
| Hungary     | 5         | 2.94%   |
| Norway      | 3         | 1.76%   |
| Mexico      | 3         | 1.76%   |
| Finland     | 3         | 1.76%   |
| Colombia    | 3         | 1.76%   |
| China       | 3         | 1.76%   |
| Australia   | 3         | 1.76%   |
| Argentina   | 3         | 1.76%   |
| Thailand    | 2         | 1.18%   |
| Spain       | 2         | 1.18%   |
| Romania     | 2         | 1.18%   |
| Poland      | 2         | 1.18%   |
| Japan       | 2         | 1.18%   |
| Czechia     | 2         | 1.18%   |
| Bulgaria    | 2         | 1.18%   |
| Brazil      | 2         | 1.18%   |
| Ukraine     | 1         | 0.59%   |
| South Korea | 1         | 0.59%   |
| Slovakia    | 1         | 0.59%   |
| Serbia      | 1         | 0.59%   |
| San Marino  | 1         | 0.59%   |
| Philippines | 1         | 0.59%   |
| Netherlands | 1         | 0.59%   |
| Lithuania   | 1         | 0.59%   |
| Hong Kong   | 1         | 0.59%   |
| Estonia     | 1         | 0.59%   |
| Denmark     | 1         | 0.59%   |
| Belarus     | 1         | 0.59%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Moscow                | 10        | 5.81%   |
| Franconville          | 6         | 3.49%   |
| Paris                 | 5         | 2.91%   |
| Hodmezovasarhely      | 5         | 2.91%   |
| Istanbul              | 4         | 2.33%   |
| Duncan                | 4         | 2.33%   |
| Woodland              | 3         | 1.74%   |
| Whittier              | 3         | 1.74%   |
| Tijuana               | 3         | 1.74%   |
| Milan                 | 3         | 1.74%   |
| Markt Indersdorf      | 3         | 1.74%   |
| Zwingenberg           | 2         | 1.16%   |
| Volzhskiy             | 2         | 1.16%   |
| Vollen                | 2         | 1.16%   |
| St Petersburg         | 2         | 1.16%   |
| Sofia                 | 2         | 1.16%   |
| Setagaya-ku           | 2         | 1.16%   |
| Rome                  | 2         | 1.16%   |
| Rio de Janeiro        | 2         | 1.16%   |
| New Braunfels         | 2         | 1.16%   |
| Melun                 | 2         | 1.16%   |
| McDonough             | 2         | 1.16%   |
| Lutherville-Timonium  | 2         | 1.16%   |
| Los Angeles           | 2         | 1.16%   |
| Greenwich             | 2         | 1.16%   |
| Drobeta-Turnu Severin | 2         | 1.16%   |
| Cologne               | 2         | 1.16%   |
| Changzhou             | 2         | 1.16%   |
| Brisbane              | 2         | 1.16%   |
| BogotГЎ             | 2         | 1.16%   |
| Bangkok               | 2         | 1.16%   |
| Wloszczowa            | 1         | 0.58%   |
| Wissen                | 1         | 0.58%   |
| Winter Haven          | 1         | 0.58%   |
| Wilhelmshaven         | 1         | 0.58%   |
| West Bromwich         | 1         | 0.58%   |
| Warsaw                | 1         | 0.58%   |
| Wakefield             | 1         | 0.58%   |
| Vladimir              | 1         | 0.58%   |
| Vilnius               | 1         | 0.58%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 41        | 52     | 18.81%  |
| WDC                 | 36        | 44     | 16.51%  |
| Seagate             | 31        | 34     | 14.22%  |
| Toshiba             | 19        | 22     | 8.72%   |
| Crucial             | 11        | 11     | 5.05%   |
| SanDisk             | 9         | 10     | 4.13%   |
| Kingston            | 8         | 9      | 3.67%   |
| SK hynix            | 7         | 8      | 3.21%   |
| Intel               | 6         | 6      | 2.75%   |
| Hitachi             | 6         | 7      | 2.75%   |
| A-DATA Technology   | 6         | 6      | 2.75%   |
| Apple               | 5         | 6      | 2.29%   |
| Micron Technology   | 3         | 3      | 1.38%   |
| Hewlett-Packard     | 3         | 3      | 1.38%   |
| Transcend           | 2         | 2      | 0.92%   |
| SPCC                | 2         | 2      | 0.92%   |
| PNY                 | 2         | 2      | 0.92%   |
| OCZ                 | 2         | 2      | 0.92%   |
| Intenso             | 2         | 2      | 0.92%   |
| HGST                | 2         | 2      | 0.92%   |
| Gigabyte Technology | 2         | 2      | 0.92%   |
| Fujitsu             | 2         | 3      | 0.92%   |
| Corsair             | 2         | 2      | 0.92%   |
| UMIS                | 1         | 1      | 0.46%   |
| Team                | 1         | 1      | 0.46%   |
| Phison              | 1         | 1      | 0.46%   |
| ORICO               | 1         | 1      | 0.46%   |
| Maxtor              | 1         | 1      | 0.46%   |
| LITEONIT            | 1         | 1      | 0.46%   |
| KingDian            | 1         | 1      | 0.46%   |
| ASUSTek Computer    | 1         | 2      | 0.46%   |
| AirDisk             | 1         | 1      | 0.46%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB          | 4         | 1.71%   |
| Toshiba MQ01ABD100 1TB               | 3         | 1.28%   |
| Seagate ST1000LM049-2GH172 1TB       | 3         | 1.28%   |
| SanDisk pSSD 16GB                    | 3         | 1.28%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 1.28%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 2         | 0.85%   |
| WDC WD40PURX-64GVNY0 4TB             | 2         | 0.85%   |
| WDC WD1600AAJS-22L7A0 160GB          | 2         | 0.85%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB | 2         | 0.85%   |
| Toshiba MQ01ABF050 500GB             | 2         | 0.85%   |
| Toshiba HDWD120 2TB                  | 2         | 0.85%   |
| Seagate ST95005620AS 500GB           | 2         | 0.85%   |
| Seagate ST9500325AS 500GB            | 2         | 0.85%   |
| Seagate ST500DM002-1BD142 496GB      | 2         | 0.85%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 0.85%   |
| SanDisk SSD U100 24GB                | 2         | 0.85%   |
| Samsung SSD 980 PRO 250GB            | 2         | 0.85%   |
| Samsung SSD 970 EVO 500GB            | 2         | 0.85%   |
| Samsung SSD 870 QVO 2TB              | 2         | 0.85%   |
| Samsung SSD 840 EVO 250GB            | 2         | 0.85%   |
| Samsung MZVLB256HBHQ-000L7 256GB     | 2         | 0.85%   |
| Kingston SA400S37480G 480GB          | 2         | 0.85%   |
| HGST HTS725050A7E630 500GB           | 2         | 0.85%   |
| HP SSD EX950 2TB                     | 2         | 0.85%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 0.85%   |
| Crucial CT1000P1SSD8 1TB             | 2         | 0.85%   |
| Apple SSD SM0512F 500GB              | 2         | 0.85%   |
| A-DATA SU630 240GB                   | 2         | 0.85%   |
| WDC WDS240G2G0B-00EPW0 240GB         | 1         | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 0.43%   |
| WDC WDS120G2G0B-00EPW0 120GB         | 1         | 0.43%   |
| WDC WDS120G2G0A-00JH30 120GB         | 1         | 0.43%   |
| WDC WDS120G1G0A-00SS50 120GB         | 1         | 0.43%   |
| WDC WD7500BPKX-00HPJT0 752GB         | 1         | 0.43%   |
| WDC WD7500BPKT-75PK4T0 752GB         | 1         | 0.43%   |
| WDC WD6400AAKS-22A7B2 640GB          | 1         | 0.43%   |
| WDC WD60EZRZ-00GZ5B1 6TB             | 1         | 0.43%   |
| WDC WD40NMZW-11GX6S1 4TB             | 1         | 0.43%   |
| WDC WD40EFAX-68JH4N0 4TB             | 1         | 0.43%   |
| WDC WD3200BEVT-75ZCT2 320GB          | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 34     | 33.7%   |
| WDC                 | 29        | 32     | 31.52%  |
| Toshiba             | 15        | 17     | 16.3%   |
| Hitachi             | 6         | 7      | 6.52%   |
| Samsung Electronics | 4         | 4      | 4.35%   |
| HGST                | 2         | 2      | 2.17%   |
| Fujitsu             | 2         | 3      | 2.17%   |
| Maxtor              | 1         | 1      | 1.09%   |
| Hewlett-Packard     | 1         | 1      | 1.09%   |
| Apple               | 1         | 1      | 1.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 23     | 22.89%  |
| SanDisk             | 9         | 10     | 10.84%  |
| Kingston            | 7         | 8      | 8.43%   |
| Crucial             | 7         | 7      | 8.43%   |
| A-DATA Technology   | 6         | 6      | 7.23%   |
| WDC                 | 4         | 5      | 4.82%   |
| Apple               | 4         | 5      | 4.82%   |
| Toshiba             | 3         | 3      | 3.61%   |
| Intel               | 3         | 3      | 3.61%   |
| Transcend           | 2         | 2      | 2.41%   |
| SPCC                | 2         | 2      | 2.41%   |
| SK hynix            | 2         | 2      | 2.41%   |
| PNY                 | 2         | 2      | 2.41%   |
| OCZ                 | 2         | 2      | 2.41%   |
| Micron Technology   | 2         | 2      | 2.41%   |
| Intenso             | 2         | 2      | 2.41%   |
| Gigabyte Technology | 2         | 2      | 2.41%   |
| Team                | 1         | 1      | 1.2%    |
| LITEONIT            | 1         | 1      | 1.2%    |
| KingDian            | 1         | 1      | 1.2%    |
| Corsair             | 1         | 1      | 1.2%    |
| ASUSTek Computer    | 1         | 2      | 1.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 79        | 102    | 40.1%   |
| SSD  | 75        | 92     | 38.07%  |
| NVMe | 43        | 56     | 21.83%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 137       | 194    | 76.11%  |
| NVMe | 43        | 56     | 23.89%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 99        | 125    | 61.49%  |
| 0.51-1.0   | 42        | 47     | 26.09%  |
| 1.01-2.0   | 10        | 10     | 6.21%   |
| 3.01-4.0   | 5         | 5      | 3.11%   |
| 2.01-3.0   | 4         | 4      | 2.48%   |
| 4.01-10.0  | 1         | 3      | 0.62%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 136       | 80%     |
| 101-250    | 16        | 9.41%   |
| 51-100     | 6         | 3.53%   |
| 21-50      | 5         | 2.94%   |
| 251-500    | 4         | 2.35%   |
| 501-1000   | 3         | 1.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 166       | 97.08%  |
| 21-50   | 3         | 1.75%   |
| 51-100  | 2         | 1.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


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
| Seagate ST500DM002-1BD142 496GB                  | 1         | 1      | 3.13%   |
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

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 27     | 77.42%  |
| SSD  | 7         | 7      | 22.58%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model             | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| SanDisk pSSD 16GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 140       | 207    | 80.46%  |
| Malfunc  | 31        | 34     | 17.82%  |
| Detected | 2         | 8      | 1.15%   |
| Failed   | 1         | 1      | 0.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 122       | 58.1%   |
| AMD                                     | 26        | 12.38%  |
| Samsung Electronics                     | 24        | 11.43%  |
| SanDisk                                 | 7         | 3.33%   |
| ASMedia Technology                      | 6         | 2.86%   |
| SK hynix                                | 4         | 1.9%    |
| Micron/Crucial Technology               | 4         | 1.9%    |
| Nvidia                                  | 3         | 1.43%   |
| VIA Technologies                        | 2         | 0.95%   |
| Phison Electronics                      | 2         | 0.95%   |
| Biwin Storage Technology                | 2         | 0.95%   |
| Toshiba                                 | 1         | 0.48%   |
| Silicon Motion                          | 1         | 0.48%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.48%   |
| Shenzhen Unionmemory Information System | 1         | 0.48%   |
| Micron Technology                       | 1         | 0.48%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.48%   |
| Kingston Technology Company             | 1         | 0.48%   |
| JMicron Technology                      | 1         | 0.48%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 19        | 7.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 14        | 5.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 13        | 5.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 10        | 4.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 3.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 3.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 7         | 2.86%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 2.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 2.45%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 6         | 2.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 5         | 2.04%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 4         | 1.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 1.63%   |
| AMD 500 Series Chipset SATA Controller                                           | 4         | 1.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.22%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.22%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.22%   |
| Intel SATA Controller [RAID mode]                                                | 3         | 1.22%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 3         | 1.22%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 1.22%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.22%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 1.22%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 2         | 0.82%   |
| SanDisk PC SN520 NVMe SSD                                                        | 2         | 0.82%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 2         | 0.82%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                               | 2         | 0.82%   |
| Nvidia MCP61 SATA Controller                                                     | 2         | 0.82%   |
| Nvidia MCP61 IDE                                                                 | 2         | 0.82%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 0.82%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 0.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.82%   |
| Intel C600/X79 series chipset IDE-r Controller                                   | 2         | 0.82%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                         | 2         | 0.82%   |
| Intel C600/X79 series chipset 2-Port SATA IDE Controller                         | 2         | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.82%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2         | 0.82%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2         | 0.82%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 2         | 0.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 118       | 56.19%  |
| NVMe | 43        | 20.48%  |
| IDE  | 31        | 14.76%  |
| RAID | 15        | 7.14%   |
| SAS  | 3         | 1.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 141       | 82.46%  |
| AMD    | 30        | 17.54%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 2.34%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 2.34%   |
| Intel CPU Version                             | 3         | 1.75%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 1.75%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 1.75%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.75%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.75%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 1.17%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.17%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.17%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.17%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.17%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.17%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 1.17%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 1.17%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.17%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz          | 2         | 1.17%   |
| Intel Core 2 Duo                              | 2         | 1.17%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 2         | 1.17%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.17%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 2         | 1.17%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 2         | 1.17%   |
| Intel Xeon CPU E5640 @ 2.67GHz                | 1         | 0.58%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz            | 1         | 0.58%   |
| Intel Xeon CPU E5-2670 @ 2.60GHz              | 1         | 0.58%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz           | 1         | 0.58%   |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz           | 1         | 0.58%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.58%   |
| Intel Xeon CPU E3-1276 v3 @ 3.60GHz           | 1         | 0.58%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz      | 1         | 0.58%   |
| Intel Pentium III                             | 1         | 0.58%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz   | 1         | 0.58%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 1         | 0.58%   |
| Intel Pentium D CPU 2.80GHz                   | 1         | 0.58%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.58%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.58%   |
| Intel Pentium CPU 2117U @ 1.80GHz             | 1         | 0.58%   |
| Intel Genuine CPU U7300 @ 1.30GHz             | 1         | 0.58%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 0.58%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 49        | 28.65%  |
| Intel Core i7           | 38        | 22.22%  |
| Intel Core 2 Duo        | 10        | 5.85%   |
| Intel Core i3           | 9         | 5.26%   |
| AMD Ryzen 5             | 9         | 5.26%   |
| Other                   | 7         | 4.09%   |
| Intel Xeon              | 7         | 4.09%   |
| AMD Ryzen 7             | 6         | 3.51%   |
| Intel Atom              | 4         | 2.34%   |
| Intel Pentium           | 3         | 1.75%   |
| Intel Celeron           | 3         | 1.75%   |
| AMD A8                  | 3         | 1.75%   |
| AMD A6                  | 3         | 1.75%   |
| Intel Pentium Dual-Core | 2         | 1.17%   |
| Intel Core i9           | 2         | 1.17%   |
| AMD Ryzen 9             | 2         | 1.17%   |
| AMD Athlon 64 X2        | 2         | 1.17%   |
| Intel Pentium Silver    | 1         | 0.58%   |
| Intel Pentium III       | 1         | 0.58%   |
| Intel Pentium D         | 1         | 0.58%   |
| Intel Genuine           | 1         | 0.58%   |
| Intel Core m5           | 1         | 0.58%   |
| Intel Core 2            | 1         | 0.58%   |
| Intel Celeron M         | 1         | 0.58%   |
| Intel Celeron Dual-Core | 1         | 0.58%   |
| AMD Phenom II X4        | 1         | 0.58%   |
| AMD FX                  | 1         | 0.58%   |
| AMD E1                  | 1         | 0.58%   |
| AMD A10                 | 1         | 0.58%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 71        | 41.52%  |
| 4       | 58        | 33.92%  |
| 8       | 10        | 5.85%   |
| Unknown | 10        | 5.85%   |
| 6       | 7         | 4.09%   |
| 12      | 6         | 3.51%   |
| 16      | 4         | 2.34%   |
| 1       | 3         | 1.75%   |
| 24      | 2         | 1.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 168       | 98.82%  |
| 2       | 1         | 0.59%   |
| Unknown | 1         | 0.59%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 99        | 57.89%  |
| 1       | 60        | 35.09%  |
| Unknown | 12        | 7.02%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 35        | 20.47%  |
| Haswell       | 22        | 12.87%  |
| IvyBridge     | 16        | 9.36%   |
| Penryn        | 15        | 8.77%   |
| Skylake       | 14        | 8.19%   |
| SandyBridge   | 11        | 6.43%   |
| Zen+          | 6         | 3.51%   |
| Puma          | 5         | 2.92%   |
| Bonnell       | 5         | 2.92%   |
| Broadwell     | 4         | 2.34%   |
| Zen 3         | 3         | 1.75%   |
| Zen 2         | 3         | 1.75%   |
| Zen           | 3         | 1.75%   |
| Westmere      | 3         | 1.75%   |
| Nehalem       | 3         | 1.75%   |
| Core          | 3         | 1.75%   |
| Unknown       | 3         | 1.75%   |
| Silvermont    | 2         | 1.17%   |
| P6            | 2         | 1.17%   |
| K8 Hammer     | 2         | 1.17%   |
| Goldmont plus | 2         | 1.17%   |
| TigerLake     | 1         | 0.58%   |
| Steamroller   | 1         | 0.58%   |
| Piledriver    | 1         | 0.58%   |
| NetBurst      | 1         | 0.58%   |
| K10 Llano     | 1         | 0.58%   |
| K10           | 1         | 0.58%   |
| Jaguar        | 1         | 0.58%   |
| Excavator     | 1         | 0.58%   |
| CometLake     | 1         | 0.58%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 109       | 58.29%  |
| AMD                        | 40        | 21.39%  |
| Nvidia                     | 35        | 18.72%  |
| VIA Technologies           | 1         | 0.53%   |
| S3 Graphics                | 1         | 0.53%   |
| Matrox Electronics Systems | 1         | 0.53%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 5.73%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 5.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 4.69%   |
| Intel UHD Graphics 620                                                                   | 8         | 4.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 4.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2.6%    |
| Intel HD Graphics 620                                                                    | 5         | 2.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.6%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 2.6%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 4         | 2.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 2.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.08%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 2.08%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.56%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.56%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 1.04%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 1.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.04%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 1.04%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.04%   |
| Intel HD Graphics 630                                                                    | 2         | 1.04%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.04%   |
| Intel HD Graphics 530                                                                    | 2         | 1.04%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.04%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 1.04%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2         | 1.04%   |
| AMD Lucienne                                                                             | 2         | 1.04%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.04%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 1.04%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.52%   |
| S3 Graphics SuperSavage IX/C SDR                                                         | 1         | 0.52%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.52%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.52%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 0.52%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.52%   |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.52%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.52%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 1         | 0.52%   |
| Nvidia GP102 [TITAN X]                                                                   | 1         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 85        | 49.71%  |
| 1 x AMD         | 36        | 21.05%  |
| 1 x Nvidia      | 22        | 12.87%  |
| Intel + Nvidia  | 12        | 7.02%   |
| 2 x Intel       | 9         | 5.26%   |
| Intel + AMD     | 2         | 1.17%   |
| 2 x AMD         | 1         | 0.58%   |
| 1 x VIA         | 1         | 0.58%   |
| 1 x S3 Graphics | 1         | 0.58%   |
| 1 x Matrox      | 1         | 0.58%   |
| AMD + Nvidia    | 1         | 0.58%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 137       | 80.59%  |
| Proprietary | 17        | 10%     |
| Unknown     | 16        | 9.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 138       | 80.7%   |
| 0.01-0.5   | 10        | 5.85%   |
| 1.01-2.0   | 8         | 4.68%   |
| 0.51-1.0   | 5         | 2.92%   |
| 5.01-6.0   | 4         | 2.34%   |
| 7.01-8.0   | 3         | 1.75%   |
| 3.01-4.0   | 3         | 1.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 16        | 11.76%  |
| LG Display              | 15        | 11.03%  |
| AU Optronics            | 15        | 11.03%  |
| BOE                     | 13        | 9.56%   |
| Goldstar                | 9         | 6.62%   |
| Chimei Innolux          | 9         | 6.62%   |
| Dell                    | 8         | 5.88%   |
| Acer                    | 6         | 4.41%   |
| Hewlett-Packard         | 5         | 3.68%   |
| Sharp                   | 4         | 2.94%   |
| Chi Mei Optoelectronics | 4         | 2.94%   |
| Apple                   | 4         | 2.94%   |
| Lenovo                  | 3         | 2.21%   |
| HannStar                | 3         | 2.21%   |
| Philips                 | 2         | 1.47%   |
| Panasonic               | 2         | 1.47%   |
| NEC Computers           | 2         | 1.47%   |
| BenQ                    | 2         | 1.47%   |
| ASUSTek Computer        | 2         | 1.47%   |
| Ancor Communications    | 2         | 1.47%   |
| ___                     | 1         | 0.74%   |
| Westinghouse            | 1         | 0.74%   |
| Vizio                   | 1         | 0.74%   |
| ViewSonic               | 1         | 0.74%   |
| Toshiba                 | 1         | 0.74%   |
| Sony                    | 1         | 0.74%   |
| LG Philips              | 1         | 0.74%   |
| LG Electronics          | 1         | 0.74%   |
| CPT                     | 1         | 0.74%   |
| AOC                     | 1         | 0.74%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 2         | 1.45%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 2         | 1.45%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                | 2         | 1.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 350x190mm 15.7-inch | 2         | 1.45%   |
| BOE LCD Monitor BOE0671 1366x768 340x190mm 15.3-inch                     | 2         | 1.45%   |
| AU Optronics LCD Monitor AUO8174 1280x800 330x210mm 15.4-inch            | 2         | 1.45%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch            | 2         | 1.45%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 2         | 1.45%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 2         | 1.45%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch             | 2         | 1.45%   |
| ___ MY TV LED TV ___0101 1920x1080                                       | 1         | 0.72%   |
| Westinghouse DWM40F3G1 WET1ECC 1920x1080 880x480mm 39.5-inch             | 1         | 0.72%   |
| Vizio SV370XVT VIZ0057 1920x1080 820x460mm 37.0-inch                     | 1         | 0.72%   |
| ViewSonic VX910 VSC3C19 1280x1024 380x300mm 19.1-inch                    | 1         | 0.72%   |
| Toshiba LCD-MONITOR LCDC980 1280x1024 380x300mm 19.1-inch                | 1         | 0.72%   |
| Sony TV SNY5D01 1360x768                                                 | 1         | 0.72%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch                  | 1         | 0.72%   |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch                  | 1         | 0.72%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 0.72%   |
| Sharp LCD Monitor SHP140E 2560x1440 290x170mm 13.2-inch                  | 1         | 0.72%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch        | 1         | 0.72%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 410x260mm 19.1-inch      | 1         | 0.72%   |
| Samsung Electronics S27E330 SAM0D91 1920x1080 600x340mm 27.2-inch        | 1         | 0.72%   |
| Samsung Electronics LF24T450F SAM7094 1920x1080 530x300mm 24.0-inch      | 1         | 0.72%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                        | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch    | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC4E41 1366x768 350x200mm 15.9-inch     | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch     | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch     | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 220x130mm 10.1-inch     | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 290x160mm 13.0-inch    | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 310x170mm 13.9-inch     | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 290x160mm 13.0-inch    | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch     | 1         | 0.72%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 600x340mm 27.2-inch        | 1         | 0.72%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                  | 1         | 0.72%   |
| Philips 170S PHL0856 1280x1024 340x270mm 17.1-inch                       | 1         | 0.72%   |
| NEC Computers EA275WMi NEC2BA7 2560x1440 600x340mm 27.2-inch             | 1         | 0.72%   |
| NEC Computers EA223WM NEC6890 1680x1050 470x300mm 22.0-inch              | 1         | 0.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 48        | 35.82%  |
| 1366x768 (WXGA)    | 35        | 26.12%  |
| 1280x1024 (SXGA)   | 11        | 8.21%   |
| 1600x900 (HD+)     | 7         | 5.22%   |
| 3840x2160 (4K)     | 5         | 3.73%   |
| 2560x1440 (QHD)    | 4         | 2.99%   |
| 1440x900 (WXGA+)   | 4         | 2.99%   |
| 1280x800 (WXGA)    | 4         | 2.99%   |
| 1024x600           | 4         | 2.99%   |
| 2880x1800          | 2         | 1.49%   |
| 2880x1620          | 2         | 1.49%   |
| 1920x1200 (WUXGA)  | 2         | 1.49%   |
| 1680x1050 (WSXGA+) | 2         | 1.49%   |
| 1360x768           | 2         | 1.49%   |
| 3200x1800 (QHD+)   | 1         | 0.75%   |
| 1600x1200          | 1         | 0.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 37        | 27.01%  |
| 13      | 24        | 17.52%  |
| 17      | 12        | 8.76%   |
| 24      | 10        | 7.3%    |
| 19      | 9         | 6.57%   |
| 27      | 8         | 5.84%   |
| 21      | 7         | 5.11%   |
| 12      | 7         | 5.11%   |
| 11      | 4         | 2.92%   |
| 10      | 4         | 2.92%   |
| Unknown | 4         | 2.92%   |
| 18      | 3         | 2.19%   |
| 23      | 2         | 1.46%   |
| 22      | 2         | 1.46%   |
| 39      | 1         | 0.73%   |
| 37      | 1         | 0.73%   |
| 25      | 1         | 0.73%   |
| 14      | 1         | 0.73%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 56        | 41.48%  |
| 201-300     | 27        | 20%     |
| 501-600     | 18        | 13.33%  |
| 401-500     | 15        | 11.11%  |
| 351-400     | 11        | 8.15%   |
| Unknown     | 4         | 2.96%   |
| 801-900     | 2         | 1.48%   |
| 601-700     | 2         | 1.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 100       | 78.13%  |
| 16/10   | 14        | 10.94%  |
| 5/4     | 11        | 8.59%   |
| Unknown | 2         | 1.56%   |
| 3/2     | 1         | 0.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 28        | 20.44%  |
| 201-250        | 20        | 14.6%   |
| 81-90          | 17        | 12.41%  |
| 151-200        | 9         | 6.57%   |
| 141-150        | 9         | 6.57%   |
| 101-110        | 9         | 6.57%   |
| 71-80          | 8         | 5.84%   |
| 301-350        | 8         | 5.84%   |
| 61-70          | 7         | 5.11%   |
| 121-130        | 5         | 3.65%   |
| 51-60          | 4         | 2.92%   |
| 41-50          | 4         | 2.92%   |
| Unknown        | 4         | 2.92%   |
| 251-300        | 2         | 1.46%   |
| 501-1000       | 2         | 1.46%   |
| 131-140        | 1         | 0.73%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 43        | 32.58%  |
| 51-100        | 39        | 29.55%  |
| 121-160       | 29        | 21.97%  |
| 161-240       | 14        | 10.61%  |
| Unknown       | 4         | 3.03%   |
| More than 240 | 3         | 2.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 130       | 75.58%  |
| 0     | 32        | 18.6%   |
| 2     | 8         | 4.65%   |
| 3     | 2         | 1.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 100       | 39.53%  |
| Realtek Semiconductor             | 69        | 27.27%  |
| Qualcomm Atheros                  | 33        | 13.04%  |
| Broadcom                          | 18        | 7.11%   |
| Ralink                            | 3         | 1.19%   |
| Marvell Technology Group          | 3         | 1.19%   |
| TP-Link                           | 2         | 0.79%   |
| Sierra Wireless                   | 2         | 0.79%   |
| Ralink Technology                 | 2         | 0.79%   |
| Qualcomm                          | 2         | 0.79%   |
| Mellanox Technologies             | 2         | 0.79%   |
| Fibocom                           | 2         | 0.79%   |
| Ericsson Business Mobile Networks | 2         | 0.79%   |
| VIA Technologies                  | 1         | 0.4%    |
| Silicon Integrated Systems [SiS]  | 1         | 0.4%    |
| Samsung Electronics               | 1         | 0.4%    |
| Nvidia                            | 1         | 0.4%    |
| NetGear                           | 1         | 0.4%    |
| Microchip Technology              | 1         | 0.4%    |
| JMicron Technology                | 1         | 0.4%    |
| Edimax Technology                 | 1         | 0.4%    |
| Dell                              | 1         | 0.4%    |
| D-Link System                     | 1         | 0.4%    |
| Brooktrout Technology             | 1         | 0.4%    |
| Atheros                           | 1         | 0.4%    |
| Apple                             | 1         | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45        | 13.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 4.32%   |
| Intel Wireless 7260                                               | 11        | 3.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 3.4%    |
| Intel Wireless 8265 / 8275                                        | 10        | 3.09%   |
| Intel Wireless 8260                                               | 7         | 2.16%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 2.16%   |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 2.16%   |
| Intel Wireless 3165                                               | 6         | 1.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5         | 1.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.54%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 1.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.23%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 1.23%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.23%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 4         | 1.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 0.93%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 0.93%   |
| Intel Wireless 7265                                               | 3         | 0.93%   |
| Intel WiFi Link 5100                                              | 3         | 0.93%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 0.93%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.93%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 0.93%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.62%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 2         | 0.62%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.62%   |
| Qualcomm ALCATEL RNDIS Interface                                  | 2         | 0.62%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 2         | 0.62%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.62%   |
| Intel Wireless-AC 9260                                            | 2         | 0.62%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 2         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 74        | 49.33%  |
| Qualcomm Atheros      | 27        | 18%     |
| Realtek Semiconductor | 25        | 16.67%  |
| Broadcom              | 12        | 8%      |
| Ralink                | 3         | 2%      |
| TP-Link               | 2         | 1.33%   |
| Ralink Technology     | 2         | 1.33%   |
| Sierra Wireless       | 1         | 0.67%   |
| NetGear               | 1         | 0.67%   |
| Edimax Technology     | 1         | 0.67%   |
| D-Link System         | 1         | 0.67%   |
| Atheros               | 1         | 0.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 11        | 7.19%   |
| Intel Wireless 8265 / 8275                                     | 10        | 6.54%   |
| Intel Wireless 8260                                            | 7         | 4.58%   |
| Intel Wireless 3165                                            | 6         | 3.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 5         | 3.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 3.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 3.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 2.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 2.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 2.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 2.61%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 4         | 2.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 1.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 1.96%   |
| Intel Wireless 7265                                            | 3         | 1.96%   |
| Intel WiFi Link 5100                                           | 3         | 1.96%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 1.96%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 1.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 1.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.31%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 2         | 1.31%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.31%   |
| Intel Wireless-AC 9260                                         | 2         | 1.31%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 2         | 1.31%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.31%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.31%   |
| TP-Link Wireless USB Adapter                                   | 1         | 0.65%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.65%   |
| Sierra Wireless EM7455                                         | 1         | 0.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.65%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.65%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1         | 0.65%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.65%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller             | 1         | 0.65%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 0.65%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.65%   |
| Realtek Realtek Bluetooth 4.2 Adapter                          | 1         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 66        | 42.04%  |
| Realtek Semiconductor            | 63        | 40.13%  |
| Broadcom                         | 9         | 5.73%   |
| Qualcomm Atheros                 | 8         | 5.1%    |
| Marvell Technology Group         | 3         | 1.91%   |
| Qualcomm                         | 2         | 1.27%   |
| VIA Technologies                 | 1         | 0.64%   |
| Silicon Integrated Systems [SiS] | 1         | 0.64%   |
| Samsung Electronics              | 1         | 0.64%   |
| Nvidia                           | 1         | 0.64%   |
| JMicron Technology               | 1         | 0.64%   |
| Apple                            | 1         | 0.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45        | 27.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 8.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 6.83%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 4.35%   |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 4.35%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 3.11%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 2.48%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 2.48%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.86%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 1.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.24%   |
| Qualcomm ALCATEL RNDIS Interface                                  | 2         | 1.24%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 1.24%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.24%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.24%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.24%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.24%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.24%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.24%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.24%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 1.24%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.62%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.62%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.62%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.62%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.62%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.62%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.62%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.62%   |
| Nvidia MCP73 Ethernet                                             | 1         | 0.62%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.62%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.62%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1         | 0.62%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.62%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.62%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.62%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.62%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.62%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 153       | 50.5%   |
| WiFi     | 140       | 46.2%   |
| Unknown  | 9         | 2.97%   |
| Modem    | 1         | 0.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 137       | 57.81%  |
| WiFi     | 95        | 40.08%  |
| Unknown  | 5         | 2.11%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 116       | 67.84%  |
| 1     | 50        | 29.24%  |
| 4     | 2         | 1.17%   |
| 3     | 2         | 1.17%   |
| 0     | 1         | 0.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 156       | 91.23%  |
| Yes  | 15        | 8.77%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 48        | 47.52%  |
| Realtek Semiconductor           | 9         | 8.91%   |
| Broadcom                        | 9         | 8.91%   |
| Qualcomm Atheros Communications | 8         | 7.92%   |
| Lite-On Technology              | 5         | 4.95%   |
| ASUSTek Computer                | 5         | 4.95%   |
| Apple                           | 5         | 4.95%   |
| IMC Networks                    | 4         | 3.96%   |
| Cambridge Silicon Radio         | 3         | 2.97%   |
| Foxconn / Hon Hai               | 2         | 1.98%   |
| Hewlett-Packard                 | 1         | 0.99%   |
| Dell                            | 1         | 0.99%   |
| Alps Electric                   | 1         | 0.99%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 30        | 29.7%   |
| Intel AX201 Bluetooth                                       | 6         | 5.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5         | 4.95%   |
| Intel AX200 Bluetooth                                       | 3         | 2.97%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 2.97%   |
| Apple Bluetooth Host Controller                             | 3         | 2.97%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 1.98%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 1.98%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.98%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 1.98%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 1.98%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 1.98%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 1.98%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.98%   |
| ASUS BT-253 Bluetooth Adapter                               | 2         | 1.98%   |
| Apple Broadcom Built-in Bluetooth                           | 2         | 1.98%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 0.99%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.99%   |
| Realtek Bluetooth 4.2 Adapter                               | 1         | 0.99%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 0.99%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 0.99%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1         | 0.99%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.99%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.99%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 0.99%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device        | 1         | 0.99%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.99%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.99%   |
| Lite-On Bluetooth USB Module                                | 1         | 0.99%   |
| Lite-On Atheros Bluetooth                                   | 1         | 0.99%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 0.99%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 0.99%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 0.99%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 0.99%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.99%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 0.99%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 0.99%   |
| Dell DW375 Bluetooth Module                                 | 1         | 0.99%   |
| Broadcom Bluetooth 4.0                                      | 1         | 0.99%   |
| Broadcom Bluetooth 2.1 Device                               | 1         | 0.99%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 136       | 62.67%  |
| AMD                              | 40        | 18.43%  |
| Nvidia                           | 22        | 10.14%  |
| XMOS                             | 2         | 0.92%   |
| Sony                             | 2         | 0.92%   |
| Corsair                          | 2         | 0.92%   |
| C-Media Electronics              | 2         | 0.92%   |
| VIA Technologies                 | 1         | 0.46%   |
| Tenx Technology                  | 1         | 0.46%   |
| Silicon Integrated Systems [SiS] | 1         | 0.46%   |
| Realtek Semiconductor            | 1         | 0.46%   |
| Quanta                           | 1         | 0.46%   |
| LG Electronics                   | 1         | 0.46%   |
| Creative Technology              | 1         | 0.46%   |
| Creative Labs                    | 1         | 0.46%   |
| Blue Microphones                 | 1         | 0.46%   |
| BEHRINGER International          | 1         | 0.46%   |
| Audio-Technica                   | 1         | 0.46%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 26        | 9.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 5.97%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 4.1%    |
| Intel 8 Series HD Audio Controller                                                                | 11        | 4.1%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 3.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 3.73%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 3.73%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 3.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 3.36%   |
| AMD FCH Azalia Controller                                                                         | 8         | 2.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 2.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 2.24%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.87%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.87%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 1.49%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.49%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.49%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.49%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 1.49%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.49%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 1.12%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3         | 1.12%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 1.12%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 3         | 1.12%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.12%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 0.75%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.75%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 0.75%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.75%   |
| Corsair VOID PRO Wireless Gaming Headset                                                          | 2         | 0.75%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.75%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.75%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.75%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 0.75%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 51        | 25.63%  |
| SK hynix            | 40        | 20.1%   |
| Micron Technology   | 23        | 11.56%  |
| Kingston            | 18        | 9.05%   |
| Unknown             | 17        | 8.54%   |
| G.Skill             | 8         | 4.02%   |
| Crucial             | 8         | 4.02%   |
| Corsair             | 7         | 3.52%   |
| Elpida              | 6         | 3.02%   |
| Unknown             | 5         | 2.51%   |
| Nanya Technology    | 4         | 2.01%   |
| Transcend           | 2         | 1.01%   |
| Ramaxel Technology  | 2         | 1.01%   |
| A-DATA Technology   | 2         | 1.01%   |
| 48spaces            | 2         | 1.01%   |
| Unknown (ABCD)      | 1         | 0.5%    |
| Unknown (09D5)      | 1         | 0.5%    |
| Magnum Tech         | 1         | 0.5%    |
| EVGA                | 1         | 0.5%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 7         | 3.27%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 5         | 2.34%   |
| Unknown                                                                   | 5         | 2.34%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 3         | 1.4%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 1.4%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 3         | 1.4%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 3         | 1.4%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 3         | 1.4%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 3         | 1.4%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                  | 2         | 0.93%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 2         | 0.93%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 2         | 0.93%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 2         | 0.93%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 2         | 0.93%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.93%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.93%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.93%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                     | 2         | 0.93%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 0.93%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                             | 2         | 0.93%   |
| Micron RAM ITC 4GB DIMM DDR3 1066MT/s                                     | 2         | 0.93%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s                     | 2         | 0.93%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s                       | 2         | 0.93%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 2         | 0.93%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                                 | 1         | 0.47%   |
| Unknown SODIMM 1024MB SODIMM DDR2 667MT/s                                 | 1         | 0.47%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                                 | 1         | 0.47%   |
| Unknown RAM Module 512MB SODIMM SDRAM                                     | 1         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                            | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 1         | 0.47%   |
| Unknown RAM Module 2GB DIMM SDRAM                                         | 1         | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                                  | 1         | 0.47%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                                    | 1         | 0.47%   |
| Unknown RAM Module 1GB SODIMM DRAM 533MT/s                                | 1         | 0.47%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 1         | 0.47%   |
| Unknown RAM Module 128MB SODIMM SDRAM                                     | 1         | 0.47%   |
| Unknown RAM Module 1024MB SODIMM RAM                                      | 1         | 0.47%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s                               | 1         | 0.47%   |
| Unknown RAM 7TE39AA# 8GB DIMM DDR4 2667MT/s                               | 1         | 0.47%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2133MT/s          | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 73        | 42.2%   |
| DDR4    | 60        | 34.68%  |
| DDR2    | 19        | 10.98%  |
| LPDDR3  | 8         | 4.62%   |
| SDRAM   | 4         | 2.31%   |
| Unknown | 4         | 2.31%   |
| RAM     | 1         | 0.58%   |
| LPDDR5  | 1         | 0.58%   |
| LPDDR4  | 1         | 0.58%   |
| DRAM    | 1         | 0.58%   |
| DDR     | 1         | 0.58%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 114       | 66.28%  |
| DIMM         | 48        | 27.91%  |
| Row Of Chips | 5         | 2.91%   |
| Chip         | 3         | 1.74%   |
| Unknown      | 2         | 1.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 69        | 35.94%  |
| 8192  | 64        | 33.33%  |
| 2048  | 30        | 15.63%  |
| 16384 | 16        | 8.33%   |
| 1024  | 9         | 4.69%   |
| 32768 | 2         | 1.04%   |
| 512   | 1         | 0.52%   |
| 128   | 1         | 0.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 49        | 26.78%  |
| 2400    | 21        | 11.48%  |
| 2667    | 19        | 10.38%  |
| 3200    | 14        | 7.65%   |
| 1333    | 13        | 7.1%    |
| 2133    | 12        | 6.56%   |
| 1334    | 8         | 4.37%   |
| 800     | 8         | 4.37%   |
| 667     | 8         | 4.37%   |
| Unknown | 6         | 3.28%   |
| 1867    | 5         | 2.73%   |
| 1066    | 5         | 2.73%   |
| 3600    | 3         | 1.64%   |
| 533     | 3         | 1.64%   |
| 1866    | 2         | 1.09%   |
| 1067    | 2         | 1.09%   |
| 6400    | 1         | 0.55%   |
| 3000    | 1         | 0.55%   |
| 2933    | 1         | 0.55%   |
| 975     | 1         | 0.55%   |
| 400     | 1         | 0.55%   |

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
| Chicony Electronics                    | 27        | 27.55%  |
| Realtek Semiconductor                  | 12        | 12.24%  |
| Bison Electronics                      | 11        | 11.22%  |
| Sunplus Innovation Technology          | 8         | 8.16%   |
| Suyin                                  | 7         | 7.14%   |
| Microdia                               | 5         | 5.1%    |
| IMC Networks                           | 5         | 5.1%    |
| Logitech                               | 4         | 4.08%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.08%   |
| Silicon Motion                         | 3         | 3.06%   |
| Quanta                                 | 3         | 3.06%   |
| Lite-On Technology                     | 3         | 3.06%   |
| Z-Star Microelectronics                | 1         | 1.02%   |
| Novatek Microelectronics               | 1         | 1.02%   |
| Intel                                  | 1         | 1.02%   |
| Genesys Logic                          | 1         | 1.02%   |
| Apple                                  | 1         | 1.02%   |
| Alcor Micro                            | 1         | 1.02%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 10        | 10.1%   |
| Bison Integrated Camera                             | 5         | 5.05%   |
| Sunplus Integrated_Webcam_HD                        | 3         | 3.03%   |
| Realtek Lenovo EasyCamera                           | 3         | 3.03%   |
| Realtek Integrated_Webcam_HD                        | 3         | 3.03%   |
| Chicony HD WebCam                                   | 3         | 3.03%   |
| Suyin Acer Crystal Eye webcam                       | 2         | 2.02%   |
| Realtek USB 2.0 PC Camera                           | 2         | 2.02%   |
| Quanta Realtek DMFT RGB                             | 2         | 2.02%   |
| Microdia Integrated_Webcam_HD                       | 2         | 2.02%   |
| Microdia Integrated Webcam                          | 2         | 2.02%   |
| IMC Networks EasyCamera                             | 2         | 2.02%   |
| Chicony FJ Camera                                   | 2         | 2.02%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 2         | 2.02%   |
| Bison SunplusIT Integrated Camera                   | 2         | 2.02%   |
| Z-Star Webcam                                       | 1         | 1.01%   |
| Suyin USB 2.0 UVC 1.3M WebCam                       | 1         | 1.01%   |
| Suyin Laptop_Integrated_Webcam_3M                   | 1         | 1.01%   |
| Suyin HD WebCam                                     | 1         | 1.01%   |
| Suyin HD Video WebCam                               | 1         | 1.01%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 1.01%   |
| Sunplus SPCA2650 AV Camera                          | 1         | 1.01%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 1.01%   |
| Sunplus Integrated Webcam                           | 1         | 1.01%   |
| Sunplus Hy HD Camera                                | 1         | 1.01%   |
| Sunplus Asus Webcam                                 | 1         | 1.01%   |
| Silicon Motion WebCam SCX Series                    | 1         | 1.01%   |
| Silicon Motion Realtek USB 2.0 PC Camera            | 1         | 1.01%   |
| Silicon Motion 300k Pixel Camera                    | 1         | 1.01%   |
| Realtek USB2.0 VGA UVC WebCam                       | 1         | 1.01%   |
| Realtek USB Video Composite                         | 1         | 1.01%   |
| Realtek USB Camera                                  | 1         | 1.01%   |
| Realtek HD Webcam - Realtek                         | 1         | 1.01%   |
| Quanta Front camera                                 | 1         | 1.01%   |
| Novatek HP High Definition 2MP Webcam               | 1         | 1.01%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 1.01%   |
| Logitech Webcam C310                                | 1         | 1.01%   |
| Logitech Webcam C270                                | 1         | 1.01%   |
| Logitech HD Pro Webcam C920                         | 1         | 1.01%   |
| Logitech C505 HD Webcam                             | 1         | 1.01%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 13        | 48.15%  |
| Synaptics             | 6         | 22.22%  |
| Upek                  | 3         | 11.11%  |
| LighTuning Technology | 2         | 7.41%   |
| Elan Microelectronics | 1         | 3.7%    |
| Broadcom              | 1         | 3.7%    |
| AuthenTec             | 1         | 3.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 3         | 11.11%  |
| Validity Sensors Synaptics WBDI                                              | 3         | 11.11%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 3         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 3         | 11.11%  |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 7.41%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 2         | 7.41%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                            | 1         | 3.7%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 3.7%    |
| LighTuning Fingerprint Reader                                                | 1         | 3.7%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 3.7%    |
| Elan Fingerprint Sensor                                                      | 1         | 3.7%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.7%    |
| AuthenTec AES1600                                                            | 1         | 3.7%    |
| Unknown                                                                      | 1         | 3.7%    |

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
| 1     | 60        | 34.48%  |
| 2     | 51        | 29.31%  |
| 0     | 27        | 15.52%  |
| 3     | 20        | 11.49%  |
| 4     | 10        | 5.75%   |
| 5     | 3         | 1.72%   |
| 7     | 2         | 1.15%   |
| 6     | 1         | 0.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 111       | 41.57%  |
| Net/wireless             | 45        | 16.85%  |
| Bluetooth                | 31        | 11.61%  |
| Fingerprint reader       | 27        | 10.11%  |
| Firewire controller      | 23        | 8.61%   |
| Card reader              | 19        | 7.12%   |
| Network                  | 6         | 2.25%   |
| Sound                    | 4         | 1.5%    |
| Storage/raid             | 1         | 0.37%   |

