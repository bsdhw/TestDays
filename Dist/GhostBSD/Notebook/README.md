GhostBSD - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for GhostBSD.

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

Total: 185

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T430 2349S31       | [2b13f68cd6](https://bsd-hardware.info/?probe=2b13f68cd6) | Feb 28, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | [7d7fa2bbc9](https://bsd-hardware.info/?probe=7d7fa2bbc9) | Feb 22, 2023 |
| Lenovo        | ThinkPad T460 20FMS3320G    | [c85f94d574](https://bsd-hardware.info/?probe=c85f94d574) | Feb 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a9928bd16e](https://bsd-hardware.info/?probe=a9928bd16e) | Feb 10, 2023 |
| HP            | 650                         | [48099613ec](https://bsd-hardware.info/?probe=48099613ec) | Feb 05, 2023 |
| Lenovo        | ThinkPad P50 20EN0008GE     | [8cb09e34ec](https://bsd-hardware.info/?probe=8cb09e34ec) | Feb 04, 2023 |
| TUXEDO        | Aura 15 Gen1                | [e6ad419f5e](https://bsd-hardware.info/?probe=e6ad419f5e) | Jan 20, 2023 |
| Lenovo        | B50-80 80EW                 | [fa42e2faf7](https://bsd-hardware.info/?probe=fa42e2faf7) | Jan 20, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [32207ea5d9](https://bsd-hardware.info/?probe=32207ea5d9) | Dec 19, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [3a9623cfb4](https://bsd-hardware.info/?probe=3a9623cfb4) | Dec 16, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [0314add226](https://bsd-hardware.info/?probe=0314add226) | Dec 16, 2022 |
| Lenovo        | B50-80 80EW                 | [9551c57fc3](https://bsd-hardware.info/?probe=9551c57fc3) | Dec 14, 2022 |
| Apple         | MacBookPro14,1              | [ddeb9befdf](https://bsd-hardware.info/?probe=ddeb9befdf) | Dec 03, 2022 |
| HP            | Laptop 14s-fq0xxx           | [920a2fe2e9](https://bsd-hardware.info/?probe=920a2fe2e9) | Nov 30, 2022 |
| HP            | Laptop 14s-fq0xxx           | [9618eb0cbe](https://bsd-hardware.info/?probe=9618eb0cbe) | Nov 29, 2022 |
| Acer          | Aspire 5251                 | [c9eb0051ed](https://bsd-hardware.info/?probe=c9eb0051ed) | Nov 16, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [45316a9769](https://bsd-hardware.info/?probe=45316a9769) | Nov 07, 2022 |
| HP            | Laptop 15-da0xxx            | [72d95a4938](https://bsd-hardware.info/?probe=72d95a4938) | Nov 03, 2022 |
| Dell          | Latitude 5591               | [40957fa567](https://bsd-hardware.info/?probe=40957fa567) | Oct 31, 2022 |
| Acer          | Aspire E1-570               | [3d62c50607](https://bsd-hardware.info/?probe=3d62c50607) | Oct 20, 2022 |
| Dell          | Latitude 5591               | [04f53f51c8](https://bsd-hardware.info/?probe=04f53f51c8) | Oct 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [a773a82ff4](https://bsd-hardware.info/?probe=a773a82ff4) | Oct 11, 2022 |
| Dell          | Latitude 5591               | [eda94b6c48](https://bsd-hardware.info/?probe=eda94b6c48) | Oct 11, 2022 |
| Dell          | XPS M1330                   | [d84548dd9b](https://bsd-hardware.info/?probe=d84548dd9b) | Sep 11, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [4f31f81571](https://bsd-hardware.info/?probe=4f31f81571) | Sep 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [fc259fcf3e](https://bsd-hardware.info/?probe=fc259fcf3e) | Aug 30, 2022 |
| HP            | Unknown                     | [7bd69ee984](https://bsd-hardware.info/?probe=7bd69ee984) | Aug 29, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [692e2f0837](https://bsd-hardware.info/?probe=692e2f0837) | Aug 20, 2022 |
| Lenovo        | ThinkPad 11e 4th Gen 20H... | [ba1ea734b1](https://bsd-hardware.info/?probe=ba1ea734b1) | Aug 19, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [c9bda4b49d](https://bsd-hardware.info/?probe=c9bda4b49d) | Aug 14, 2022 |
| Dell          | Inspiron 1545               | [e1a29d8008](https://bsd-hardware.info/?probe=e1a29d8008) | Aug 14, 2022 |
| Dell          | Inspiron 15-3567            | [cdc6bc6ef8](https://bsd-hardware.info/?probe=cdc6bc6ef8) | Aug 03, 2022 |
| Acer          | Aspire E5-521G              | [dcc5d3116f](https://bsd-hardware.info/?probe=dcc5d3116f) | Jul 29, 2022 |
| Lenovo        | IdeaPad Y580 20132          | [3df3bd2f62](https://bsd-hardware.info/?probe=3df3bd2f62) | Jul 22, 2022 |
| Dell          | Inspiron 15-3567            | [15c5d9fdd9](https://bsd-hardware.info/?probe=15c5d9fdd9) | Jul 17, 2022 |
| Dell          | Inspiron 3505               | [ead2595782](https://bsd-hardware.info/?probe=ead2595782) | Jul 17, 2022 |
| Dell          | XPS 13 7390                 | [d9efb0425b](https://bsd-hardware.info/?probe=d9efb0425b) | Jul 15, 2022 |
| Dell          | XPS 13 7390                 | [6e85a064f0](https://bsd-hardware.info/?probe=6e85a064f0) | Jul 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b09ba0c799](https://bsd-hardware.info/?probe=b09ba0c799) | Jul 12, 2022 |
| HP            | Laptop 15-da0xxx            | [0434c94fad](https://bsd-hardware.info/?probe=0434c94fad) | Jul 09, 2022 |
| Lenovo        | ThinkPad T470 20HD000MUK    | [866724656a](https://bsd-hardware.info/?probe=866724656a) | Jul 06, 2022 |
| Star Labs     | LabTop                      | [390c4c4d55](https://bsd-hardware.info/?probe=390c4c4d55) | Jul 03, 2022 |
| Dell          | XPS 13 7390                 | [3c2e2da462](https://bsd-hardware.info/?probe=3c2e2da462) | Jul 02, 2022 |
| Dell          | XPS 13 7390                 | [b870cd3698](https://bsd-hardware.info/?probe=b870cd3698) | Jul 01, 2022 |
| System76      | Gazelle                     | [7e2dbb0a5b](https://bsd-hardware.info/?probe=7e2dbb0a5b) | Jun 28, 2022 |
| System76      | Gazelle                     | [8cb2a30786](https://bsd-hardware.info/?probe=8cb2a30786) | Jun 28, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [bb3de13b1a](https://bsd-hardware.info/?probe=bb3de13b1a) | Jun 23, 2022 |
| ASUSTek       | X202E                       | [bdbe613858](https://bsd-hardware.info/?probe=bdbe613858) | Jun 22, 2022 |
| HP            | EliteBook 830 G5            | [03cb6c6c7f](https://bsd-hardware.info/?probe=03cb6c6c7f) | Jun 09, 2022 |
| Dell          | Latitude 7490               | [22224f46f4](https://bsd-hardware.info/?probe=22224f46f4) | Jun 02, 2022 |
| TUXEDO        | Aura 15 Gen1                | [115de395dd](https://bsd-hardware.info/?probe=115de395dd) | May 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [d2334d7be3](https://bsd-hardware.info/?probe=d2334d7be3) | May 14, 2022 |
| Acer          | Aspire A715-42G             | [6dce802641](https://bsd-hardware.info/?probe=6dce802641) | May 10, 2022 |
| Dell          | Latitude 7490               | [0d5b872ec1](https://bsd-hardware.info/?probe=0d5b872ec1) | May 02, 2022 |
| Dell          | Latitude 7490               | [03c97fe4d9](https://bsd-hardware.info/?probe=03c97fe4d9) | May 02, 2022 |
| Dell          | Precision 7730              | [bdb3e3d4ce](https://bsd-hardware.info/?probe=bdb3e3d4ce) | Apr 30, 2022 |
| Dell          | Latitude 7490               | [1586880dd7](https://bsd-hardware.info/?probe=1586880dd7) | Apr 30, 2022 |
| ASUSTek       | X550CC                      | [ece6d63cfb](https://bsd-hardware.info/?probe=ece6d63cfb) | Apr 25, 2022 |
| Dell          | Latitude E5450              | [ca5eb083f9](https://bsd-hardware.info/?probe=ca5eb083f9) | Apr 16, 2022 |
| Notebook      | N13xWU                      | [8986953acd](https://bsd-hardware.info/?probe=8986953acd) | Mar 22, 2022 |
| Notebook      | N7x0WU                      | [b80f84aef1](https://bsd-hardware.info/?probe=b80f84aef1) | Mar 22, 2022 |
| Notebook      | N8xEJEK                     | [9a62677ea8](https://bsd-hardware.info/?probe=9a62677ea8) | Mar 22, 2022 |
| Dell          | Latitude E6500              | [5fad69bbf0](https://bsd-hardware.info/?probe=5fad69bbf0) | Mar 22, 2022 |
| Dell          | Latitude E6510              | [a040a1a04b](https://bsd-hardware.info/?probe=a040a1a04b) | Mar 22, 2022 |
| Dell          | Latitude E6530              | [9bc5fc70a7](https://bsd-hardware.info/?probe=9bc5fc70a7) | Mar 22, 2022 |
| Lenovo        | ThinkPad X201 32492EU       | [4a5ba4f3e4](https://bsd-hardware.info/?probe=4a5ba4f3e4) | Mar 13, 2022 |
| Lenovo        | ThinkPad T450 20BUS0VH08    | [bc2860431e](https://bsd-hardware.info/?probe=bc2860431e) | Feb 17, 2022 |
| Jumper        | EZbook                      | [35869ff0db](https://bsd-hardware.info/?probe=35869ff0db) | Feb 14, 2022 |
| Lenovo        | G500s 20245                 | [41f9f804ac](https://bsd-hardware.info/?probe=41f9f804ac) | Feb 04, 2022 |
| Dell          | Vostro 3550                 | [0b290f2ac3](https://bsd-hardware.info/?probe=0b290f2ac3) | Feb 02, 2022 |
| MSI           | GE75 Raider 10SFS           | [48b172bfe8](https://bsd-hardware.info/?probe=48b172bfe8) | Jan 25, 2022 |
| MSI           | GF63 Thin 10SCSR            | [5b9c617dc8](https://bsd-hardware.info/?probe=5b9c617dc8) | Jan 22, 2022 |
| Apple         | MacBookPro11,4              | [6d580e8270](https://bsd-hardware.info/?probe=6d580e8270) | Jan 21, 2022 |
| Dell          | Latitude E6540              | [f13972c935](https://bsd-hardware.info/?probe=f13972c935) | Jan 21, 2022 |
| Fujitsu       | CELSIUS H780                | [a173366c78](https://bsd-hardware.info/?probe=a173366c78) | Jan 21, 2022 |
| Jumper        | EZbook                      | [7d648bcdc7](https://bsd-hardware.info/?probe=7d648bcdc7) | Jan 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cf360a6098](https://bsd-hardware.info/?probe=cf360a6098) | Jan 16, 2022 |
| Acer          | Extensa 5635Z               | [d76873c5dd](https://bsd-hardware.info/?probe=d76873c5dd) | Jan 16, 2022 |
| HP            | Laptop 15-dw2xxx            | [a6d7796cea](https://bsd-hardware.info/?probe=a6d7796cea) | Jan 13, 2022 |
| Dell          | Latitude 5510               | [a620d284cb](https://bsd-hardware.info/?probe=a620d284cb) | Jan 12, 2022 |
| Dell          | Inspiron N5110              | [19be37f181](https://bsd-hardware.info/?probe=19be37f181) | Jan 09, 2022 |
| Dell          | Latitude E5450              | [c2ef231757](https://bsd-hardware.info/?probe=c2ef231757) | Jan 04, 2022 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | [259b5cc7b2](https://bsd-hardware.info/?probe=259b5cc7b2) | Dec 28, 2021 |
| ASUSTek       | X202E                       | [7f4e6f4541](https://bsd-hardware.info/?probe=7f4e6f4541) | Dec 05, 2021 |
| Fujitsu       | LIFEBOOK A555               | [c501c5c75e](https://bsd-hardware.info/?probe=c501c5c75e) | Dec 04, 2021 |
| Samsung       | 530XBB                      | [41d5f95889](https://bsd-hardware.info/?probe=41d5f95889) | Dec 03, 2021 |
| Alienware     | m15 R4                      | [a724a7d7c7](https://bsd-hardware.info/?probe=a724a7d7c7) | Nov 29, 2021 |
| Lenovo        | ThinkPad T520 4243E51       | [82f5612822](https://bsd-hardware.info/?probe=82f5612822) | Nov 29, 2021 |
| Sony          | SVP13225SCBI                | [03ef84679c](https://bsd-hardware.info/?probe=03ef84679c) | Nov 27, 2021 |
| Dell          | Latitude 5510               | [3da78c9445](https://bsd-hardware.info/?probe=3da78c9445) | Nov 24, 2021 |
| Acer          | TravelMate B117-M           | [4f02660d9c](https://bsd-hardware.info/?probe=4f02660d9c) | Nov 14, 2021 |
| Toshiba       | Satellite C855-1U4          | [4107fc9eee](https://bsd-hardware.info/?probe=4107fc9eee) | Nov 14, 2021 |
| Dell          | Latitude D630               | [7e3a92badc](https://bsd-hardware.info/?probe=7e3a92badc) | Nov 02, 2021 |
| HP            | EliteBook Folio 1040 G3     | [d23636abb2](https://bsd-hardware.info/?probe=d23636abb2) | Oct 31, 2021 |
| Samsung       | 550P5C/550P7C               | [69fe175fb8](https://bsd-hardware.info/?probe=69fe175fb8) | Oct 30, 2021 |
| HP            | Pavilion g6                 | [9754bc2e72](https://bsd-hardware.info/?probe=9754bc2e72) | Oct 27, 2021 |
| MSI           | Modern 14 A10M              | [84838cd532](https://bsd-hardware.info/?probe=84838cd532) | Oct 07, 2021 |
| MSI           | Modern 14 A10M              | [db33045561](https://bsd-hardware.info/?probe=db33045561) | Oct 07, 2021 |
| Acer          | Aspire A315-56              | [03ca802f4b](https://bsd-hardware.info/?probe=03ca802f4b) | Oct 02, 2021 |
| MSI           | Modern 14 A10M              | [277d8118da](https://bsd-hardware.info/?probe=277d8118da) | Sep 30, 2021 |
| Lenovo        | Flex 2-15 20405             | [76ea6529ac](https://bsd-hardware.info/?probe=76ea6529ac) | Sep 26, 2021 |
| MSI           | Modern 14 A10M              | [103ccaf452](https://bsd-hardware.info/?probe=103ccaf452) | Sep 25, 2021 |
| Lenovo        | ThinkPad X220 4290W42       | [8be5183e21](https://bsd-hardware.info/?probe=8be5183e21) | Sep 25, 2021 |
| Lenovo        | ThinkPad T500 2056Y2Z       | [88b86ecf8b](https://bsd-hardware.info/?probe=88b86ecf8b) | Sep 25, 2021 |
| HUAWEI        | HLY-WX9XX                   | [bd5b726e52](https://bsd-hardware.info/?probe=bd5b726e52) | Sep 19, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [2a54a0c338](https://bsd-hardware.info/?probe=2a54a0c338) | Sep 14, 2021 |
| Lenovo        | ThinkPad T400 6474E18       | [2dd5b5869f](https://bsd-hardware.info/?probe=2dd5b5869f) | Sep 13, 2021 |
| HP            | EliteBook 8570p             | [27f01061f2](https://bsd-hardware.info/?probe=27f01061f2) | Sep 12, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | [ecd69774c0](https://bsd-hardware.info/?probe=ecd69774c0) | Sep 06, 2021 |
| System76      | Kudu                        | [c10fc12e40](https://bsd-hardware.info/?probe=c10fc12e40) | Sep 05, 2021 |
| Acer          | Aspire 5750                 | [2bc72bf29e](https://bsd-hardware.info/?probe=2bc72bf29e) | Aug 23, 2021 |
| Dell          | Latitude E5440              | [3f2e8586a7](https://bsd-hardware.info/?probe=3f2e8586a7) | Aug 05, 2021 |
| Dell          | Latitude E6430              | [4149fa5ec3](https://bsd-hardware.info/?probe=4149fa5ec3) | Aug 04, 2021 |
| Lenovo        | Legion Y7000P 81LD          | [7364ae3b3d](https://bsd-hardware.info/?probe=7364ae3b3d) | Aug 04, 2021 |
| Lenovo        | ThinkPad L512 44444XG       | [a6c8fbcb20](https://bsd-hardware.info/?probe=a6c8fbcb20) | Aug 01, 2021 |
| GPU Compan... | GWTN156-5                   | [bc44d767cc](https://bsd-hardware.info/?probe=bc44d767cc) | Jul 22, 2021 |
| Dell          | Latitude E5520              | [e0dd26220f](https://bsd-hardware.info/?probe=e0dd26220f) | Jul 21, 2021 |
| Apple         | MacBook5,1                  | [1e54d2fbdf](https://bsd-hardware.info/?probe=1e54d2fbdf) | Jul 05, 2021 |
| Apple         | MacBook5,1                  | [f5d7a16498](https://bsd-hardware.info/?probe=f5d7a16498) | Jul 05, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [668bf95221](https://bsd-hardware.info/?probe=668bf95221) | Jun 25, 2021 |
| Dell          | Latitude E6420              | [2e8b431cc6](https://bsd-hardware.info/?probe=2e8b431cc6) | Jun 25, 2021 |
| Lenovo        | ThinkPad T440 20B7S1860W    | [8552205176](https://bsd-hardware.info/?probe=8552205176) | Jun 22, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [9f82e215c3](https://bsd-hardware.info/?probe=9f82e215c3) | Jun 22, 2021 |
| Dell          | Inspiron 3542               | [a2deab0991](https://bsd-hardware.info/?probe=a2deab0991) | Jun 15, 2021 |
| Sony          | SVP1322M1EBI                | [23316d0f2b](https://bsd-hardware.info/?probe=23316d0f2b) | May 29, 2021 |
| Lenovo        | ThinkPad T470 20HD000MUK    | [e27342ab94](https://bsd-hardware.info/?probe=e27342ab94) | May 13, 2021 |
| Lenovo        | ThinkPad X250 20CM003WMS    | [11fe52be5e](https://bsd-hardware.info/?probe=11fe52be5e) | May 13, 2021 |
| Lenovo        | ThinkPad T430 2344C4U       | [0f001f65d2](https://bsd-hardware.info/?probe=0f001f65d2) | Apr 27, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [f8389b0546](https://bsd-hardware.info/?probe=f8389b0546) | Apr 24, 2021 |
| HP            | Laptop 15-da0xxx            | [cb09a1b771](https://bsd-hardware.info/?probe=cb09a1b771) | Apr 08, 2021 |
| Apple         | MacBookPro8,1               | [e4e3731289](https://bsd-hardware.info/?probe=e4e3731289) | Apr 01, 2021 |
| Acer          | Aspire E5-521G              | [e2b6dbfe40](https://bsd-hardware.info/?probe=e2b6dbfe40) | Apr 01, 2021 |
| HP            | 255 G7 Notebook PC          | [3e500c12a3](https://bsd-hardware.info/?probe=3e500c12a3) | Mar 24, 2021 |
| Lenovo        | ThinkPad X250 20CM003WMS    | [196cd8a730](https://bsd-hardware.info/?probe=196cd8a730) | Mar 11, 2021 |
| Acer          | Aspire F5-573G              | [240171b234](https://bsd-hardware.info/?probe=240171b234) | Mar 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9ede3128c5](https://bsd-hardware.info/?probe=9ede3128c5) | Mar 07, 2021 |
| HP            | Laptop 15-db0xxx            | [b1ee3da46f](https://bsd-hardware.info/?probe=b1ee3da46f) | Mar 06, 2021 |
| Apple         | MacBookPro5,5               | [50ac436475](https://bsd-hardware.info/?probe=50ac436475) | Mar 06, 2021 |
| Acer          | Extensa 5635Z               | [837c6f28b4](https://bsd-hardware.info/?probe=837c6f28b4) | Feb 19, 2021 |
| Lenovo        | ThinkPad T470 20HD000MUK    | [39c8cd6d0c](https://bsd-hardware.info/?probe=39c8cd6d0c) | Feb 08, 2021 |
| Apple         | MacBookPro5,5               | [254e518190](https://bsd-hardware.info/?probe=254e518190) | Feb 03, 2021 |
| Dell          | Latitude 5480               | [9b38a72dd4](https://bsd-hardware.info/?probe=9b38a72dd4) | Jan 26, 2021 |
| HP            | Laptop 17-ca1xxx            | [fb318623f3](https://bsd-hardware.info/?probe=fb318623f3) | Jan 23, 2021 |
| HP            | Laptop 17-ca1xxx            | [97a89d4eb0](https://bsd-hardware.info/?probe=97a89d4eb0) | Jan 23, 2021 |
| HP            | Laptop 17-ca1xxx            | [806c954739](https://bsd-hardware.info/?probe=806c954739) | Jan 23, 2021 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [3d18f3f8a9](https://bsd-hardware.info/?probe=3d18f3f8a9) | Jan 23, 2021 |
| Dell          | Inspiron 3542               | [3c41c474ad](https://bsd-hardware.info/?probe=3c41c474ad) | Jan 16, 2021 |
| HP            | OMEN by HP Laptop           | [14857eb6b7](https://bsd-hardware.info/?probe=14857eb6b7) | Jan 15, 2021 |
| ASUSTek       | X550LC                      | [f7c32488e9](https://bsd-hardware.info/?probe=f7c32488e9) | Jan 15, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [06cbb5cd5f](https://bsd-hardware.info/?probe=06cbb5cd5f) | Jan 15, 2021 |
| Dell          | Latitude 5280               | [c9bfb73262](https://bsd-hardware.info/?probe=c9bfb73262) | Jan 15, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [a395c023bf](https://bsd-hardware.info/?probe=a395c023bf) | Jan 10, 2021 |
| Dell          | Inspiron 5758               | [c096e37be5](https://bsd-hardware.info/?probe=c096e37be5) | Jan 03, 2021 |
| HP            | Laptop 14-dk0xxx            | [5cd8e23152](https://bsd-hardware.info/?probe=5cd8e23152) | Dec 26, 2020 |
| HP            | Laptop 14-dk0xxx            | [fdbd71db5e](https://bsd-hardware.info/?probe=fdbd71db5e) | Dec 26, 2020 |
| Lenovo        | Yoga 2 13 20344             | [c51c202b8d](https://bsd-hardware.info/?probe=c51c202b8d) | Dec 25, 2020 |
| Lenovo        | ThinkPad T450 20BV0064US    | [b397848c7e](https://bsd-hardware.info/?probe=b397848c7e) | Dec 16, 2020 |
| Toshiba       | Satellite C855              | [6bc78fc7fc](https://bsd-hardware.info/?probe=6bc78fc7fc) | Dec 16, 2020 |
| Panasonic     | CF-19AHNC8FN                | [04a42812bb](https://bsd-hardware.info/?probe=04a42812bb) | Dec 11, 2020 |
| Lenovo        | ThinkPad X220 42872VU       | [c843b5d271](https://bsd-hardware.info/?probe=c843b5d271) | Dec 10, 2020 |
| Sony          | VPCCB17FG                   | [d8a67b4a30](https://bsd-hardware.info/?probe=d8a67b4a30) | Dec 06, 2020 |
| Sony          | VPCCB17FG                   | [7fc23a57bb](https://bsd-hardware.info/?probe=7fc23a57bb) | Nov 25, 2020 |
| Acer          | Aspire 7540                 | [65d215a03b](https://bsd-hardware.info/?probe=65d215a03b) | Nov 17, 2020 |
| Apple         | MacBook6,1                  | [64b1b1910c](https://bsd-hardware.info/?probe=64b1b1910c) | Nov 01, 2020 |
| Acer          | Aspire A315-42              | [1ac21e1660](https://bsd-hardware.info/?probe=1ac21e1660) | Oct 08, 2020 |
| Acer          | Aspire E1-532               | [10bff44534](https://bsd-hardware.info/?probe=10bff44534) | Oct 07, 2020 |
| HP            | Laptop 15-da0xxx            | [7faf1699d6](https://bsd-hardware.info/?probe=7faf1699d6) | Oct 04, 2020 |
| Lenovo        | ThinkPad T590 20N40016CD    | [1d9786ac9f](https://bsd-hardware.info/?probe=1d9786ac9f) | Aug 31, 2020 |
| Lenovo        | ThinkPad T590 20N40016CD    | [e505894bee](https://bsd-hardware.info/?probe=e505894bee) | Aug 29, 2020 |
| System76      | Lemur Pro                   | [0163d0f084](https://bsd-hardware.info/?probe=0163d0f084) | Aug 29, 2020 |
| Lenovo        | ThinkPad T430s 23539JM      | [facf6fa0f8](https://bsd-hardware.info/?probe=facf6fa0f8) | Aug 27, 2020 |
| ASUSTek       | K53SD                       | [975e9ccbe2](https://bsd-hardware.info/?probe=975e9ccbe2) | Aug 27, 2020 |
| Lenovo        | ThinkPad T530 239242U       | [7c8087322d](https://bsd-hardware.info/?probe=7c8087322d) | Aug 27, 2020 |
| Sony          | VGN-SZ3VWP_X                | [ace534d784](https://bsd-hardware.info/?probe=ace534d784) | Aug 10, 2020 |
| TUXEDO        | InfinityBook13V3            | [d508fb472b](https://bsd-hardware.info/?probe=d508fb472b) | Aug 10, 2020 |
| Dell          | Inspiron 3542               | [b89da90904](https://bsd-hardware.info/?probe=b89da90904) | Aug 01, 2020 |
| ASUSTek       | G750JS                      | [8214170523](https://bsd-hardware.info/?probe=8214170523) | Aug 01, 2020 |
| ASUSTek       | G750JS                      | [60b904f003](https://bsd-hardware.info/?probe=60b904f003) | Aug 01, 2020 |
| Dell          | Latitude E6420              | [324265fe3f](https://bsd-hardware.info/?probe=324265fe3f) | May 31, 2020 |
| Lenovo        | ThinkPad T430s 2352CTO      | [f4e8ffb5dc](https://bsd-hardware.info/?probe=f4e8ffb5dc) | May 27, 2020 |
| Lenovo        | ThinkPad T430s 2352CTO      | [59c5b6d6b9](https://bsd-hardware.info/?probe=59c5b6d6b9) | May 27, 2020 |
| Dell          | Precision M4700             | [a7761ee829](https://bsd-hardware.info/?probe=a7761ee829) | May 25, 2020 |
| Lenovo        | G570 20079                  | [6a1b7867f0](https://bsd-hardware.info/?probe=6a1b7867f0) | May 16, 2020 |
| Lenovo        | G570 20079                  | [25fd1154c0](https://bsd-hardware.info/?probe=25fd1154c0) | May 08, 2020 |
| Lenovo        | G570 20079                  | [0370bc0522](https://bsd-hardware.info/?probe=0370bc0522) | May 02, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| GhostBSD 20.04.02    | 58        | 40.28%  |
| GhostBSD 21.08.27    | 29        | 20.14%  |
| GhostBSD 22.01.12    | 13        | 9.03%   |
| GhostBSD 22.06.18    | 8         | 5.56%   |
| GhostBSD 23.02.02    | 4         | 2.78%   |
| GhostBSD 22.06.26    | 3         | 2.08%   |
| GhostBSD 22.11.22    | 2         | 1.39%   |
| GhostBSD 22.11.02    | 2         | 1.39%   |
| GhostBSD 22.08.23    | 2         | 1.39%   |
| GhostBSD 22.08.06    | 2         | 1.39%   |
| GhostBSD 22.07.16    | 2         | 1.39%   |
| GhostBSD 23.01.13    | 1         | 0.69%   |
| GhostBSD 22.10.30    | 1         | 0.69%   |
| GhostBSD 22.09.16    | 1         | 0.69%   |
| GhostBSD 22.08.27    | 1         | 0.69%   |
| GhostBSD 22.07.31    | 1         | 0.69%   |
| GhostBSD 22.07.28    | 1         | 0.69%   |
| GhostBSD 22.07.13    | 1         | 0.69%   |
| GhostBSD 22.07.10    | 1         | 0.69%   |
| GhostBSD 22.06.20    | 1         | 0.69%   |
| GhostBSD 22.06.07    | 1         | 0.69%   |
| GhostBSD 22.05.13    | 1         | 0.69%   |
| GhostBSD 22.04.30    | 1         | 0.69%   |
| GhostBSD 22.04.22    | 1         | 0.69%   |
| GhostBSD 22.04.06    | 1         | 0.69%   |
| GhostBSD 21.12.29    | 1         | 0.69%   |
| GhostBSD 21.11.24    | 1         | 0.69%   |
| GhostBSD 20.07.14    | 1         | 0.69%   |
| GhostBSD 20.03.01    | 1         | 0.69%   |
| GhostBSD 12.2-STABLE | 1         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| GhostBSD | 134       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 134       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| MATE         | 102       | 74.45%  |
| XFCE         | 24        | 17.52%  |
| KDE5         | 6         | 4.38%   |
| Cinnamon     | 2         | 1.46%   |
| helloDesktop | 1         | 0.73%   |
| GNOME        | 1         | 0.73%   |
| Console      | 1         | 0.73%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 132       | 98.51%  |
| Wayland | 1         | 0.75%   |
| Console | 1         | 0.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 132       | 98.51%  |
| SDDM    | 1         | 0.75%   |
| Console | 1         | 0.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 56        | 40%     |
| C       | 45        | 32.14%  |
| Unknown | 16        | 11.43%  |
| de_DE   | 7         | 5%      |
| pt_BR   | 3         | 2.14%   |
| pl_PL   | 2         | 1.43%   |
| it_IT   | 2         | 1.43%   |
| en_GB   | 2         | 1.43%   |
| zh_CN   | 1         | 0.71%   |
| sv_SE   | 1         | 0.71%   |
| sk_SK   | 1         | 0.71%   |
| ru_RU   | 1         | 0.71%   |
| es_ES   | 1         | 0.71%   |
| en_NZ   | 1         | 0.71%   |
| el_GR   | 1         | 0.71%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 105       | 78.36%  |
| BIOS | 29        | 21.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 126       | 91.3%   |
| Ufs  | 12        | 8.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 131       | 97.76%  |
| MBR  | 3         | 2.24%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 39        | 29.1%   |
| Dell                | 29        | 21.64%  |
| Hewlett-Packard     | 13        | 9.7%    |
| ASUSTek Computer    | 10        | 7.46%   |
| Acer                | 10        | 7.46%   |
| Sony                | 4         | 2.99%   |
| Notebook            | 4         | 2.99%   |
| MSI                 | 4         | 2.99%   |
| Apple               | 4         | 2.99%   |
| System76            | 3         | 2.24%   |
| TUXEDO              | 2         | 1.49%   |
| Toshiba             | 2         | 1.49%   |
| Samsung Electronics | 2         | 1.49%   |
| Fujitsu             | 2         | 1.49%   |
| Star Labs           | 1         | 0.75%   |
| Panasonic           | 1         | 0.75%   |
| Jumper              | 1         | 0.75%   |
| HUAWEI              | 1         | 0.75%   |
| GPU Company         | 1         | 0.75%   |
| Alienware           | 1         | 0.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Inspiron 3542                       | 3         | 2.24%   |
| MSI Modern 14 A10M                       | 2         | 1.49%   |
| Lenovo ThinkPad T430s 2352CTO            | 2         | 1.49%   |
| Dell XPS 13 7390                         | 2         | 1.49%   |
| Dell Latitude E6420                      | 2         | 1.49%   |
| ASUS ZenBook UX325UA_UM325UA             | 2         | 1.49%   |
| TUXEDO InfinityBook13V3                  | 1         | 0.75%   |
| TUXEDO Aura 15 Gen1                      | 1         | 0.75%   |
| Toshiba Satellite C855-1U4               | 1         | 0.75%   |
| Toshiba Satellite C855                   | 1         | 0.75%   |
| System76 Lemur Pro                       | 1         | 0.75%   |
| System76 Kudu                            | 1         | 0.75%   |
| System76 Gazelle                         | 1         | 0.75%   |
| Star Labs LabTop                         | 1         | 0.75%   |
| Sony VPCCB17FG                           | 1         | 0.75%   |
| Sony VGN-SZ3VWP_X                        | 1         | 0.75%   |
| Sony SVP1322M1EBI                        | 1         | 0.75%   |
| Sony SVP13225SCBI                        | 1         | 0.75%   |
| Samsung 550P5C/550P7C                    | 1         | 0.75%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV | 1         | 0.75%   |
| Panasonic CF-19AHNC8FN                   | 1         | 0.75%   |
| Notebook N8xEJEK                         | 1         | 0.75%   |
| Notebook N85_N87,HJ,HJ1,HK1              | 1         | 0.75%   |
| Notebook N7x0WU                          | 1         | 0.75%   |
| Notebook N13xWU                          | 1         | 0.75%   |
| MSI GF63 Thin 10SCSR                     | 1         | 0.75%   |
| MSI GE75 Raider 10SFS                    | 1         | 0.75%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS       | 1         | 0.75%   |
| Lenovo Yoga 2 13 20344                   | 1         | 0.75%   |
| Lenovo ThinkPad X250 20CM003WMS          | 1         | 0.75%   |
| Lenovo ThinkPad X250 20CL001GZA          | 1         | 0.75%   |
| Lenovo ThinkPad X220 4290W42             | 1         | 0.75%   |
| Lenovo ThinkPad X220 42872VU             | 1         | 0.75%   |
| Lenovo ThinkPad X201 32492EU             | 1         | 0.75%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS6J30W | 1         | 0.75%   |
| Lenovo ThinkPad T590 20N40016CD          | 1         | 0.75%   |
| Lenovo ThinkPad T530 239242U             | 1         | 0.75%   |
| Lenovo ThinkPad T520 4243E51             | 1         | 0.75%   |
| Lenovo ThinkPad T500 2056Y2Z             | 1         | 0.75%   |
| Lenovo ThinkPad T490 20N2CTO1WW          | 1         | 0.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 30        | 22.39%  |
| Dell Latitude           | 16        | 11.94%  |
| Dell Inspiron           | 8         | 5.97%   |
| Acer Aspire             | 8         | 5.97%   |
| HP Laptop               | 5         | 3.73%   |
| Lenovo IdeaPad          | 4         | 2.99%   |
| HP EliteBook            | 3         | 2.24%   |
| Dell XPS                | 3         | 2.24%   |
| Toshiba Satellite       | 2         | 1.49%   |
| MSI Modern              | 2         | 1.49%   |
| Lenovo Yoga             | 2         | 1.49%   |
| Dell Precision          | 2         | 1.49%   |
| ASUS ZenBook            | 2         | 1.49%   |
| ASUS VivoBook           | 2         | 1.49%   |
| TUXEDO InfinityBook13V3 | 1         | 0.75%   |
| TUXEDO Aura             | 1         | 0.75%   |
| System76 Lemur          | 1         | 0.75%   |
| System76 Kudu           | 1         | 0.75%   |
| System76 Gazelle        | 1         | 0.75%   |
| Star Labs LabTop        | 1         | 0.75%   |
| Sony VPCCB17FG          | 1         | 0.75%   |
| Sony VGN-SZ3VWP         | 1         | 0.75%   |
| Sony SVP1322M1EBI       | 1         | 0.75%   |
| Sony SVP13225SCBI       | 1         | 0.75%   |
| Samsung 550P5C          | 1         | 0.75%   |
| Samsung 3570R           | 1         | 0.75%   |
| Panasonic CF-19AHNC8FN  | 1         | 0.75%   |
| Notebook N8xEJEK        | 1         | 0.75%   |
| Notebook N85            | 1         | 0.75%   |
| Notebook N7x0WU         | 1         | 0.75%   |
| Notebook N13xWU         | 1         | 0.75%   |
| MSI GF63                | 1         | 0.75%   |
| MSI GE75                | 1         | 0.75%   |
| Lenovo Legion           | 1         | 0.75%   |
| Lenovo G500s            | 1         | 0.75%   |
| Lenovo Flex             | 1         | 0.75%   |
| Jumper EZbook           | 1         | 0.75%   |
| HUAWEI HLY-WX9XX        | 1         | 0.75%   |
| HP Pavilion             | 1         | 0.75%   |
| HP OMEN                 | 1         | 0.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 21        | 15.67%  |
| 2013 | 17        | 12.69%  |
| 2021 | 14        | 10.45%  |
| 2018 | 11        | 8.21%   |
| 2014 | 10        | 7.46%   |
| 2012 | 8         | 5.97%   |
| 2011 | 8         | 5.97%   |
| 2019 | 7         | 5.22%   |
| 2015 | 7         | 5.22%   |
| 2009 | 7         | 5.22%   |
| 2017 | 6         | 4.48%   |
| 2016 | 6         | 4.48%   |
| 2022 | 4         | 2.99%   |
| 2010 | 4         | 2.99%   |
| 2008 | 3         | 2.24%   |
| 2007 | 1         | 0.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 134       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 133       | 99.25%  |
| Yes  | 1         | 0.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 68        | 50.75%  |
| 16.01-24.0  | 37        | 27.61%  |
| 4.01-8.0    | 22        | 16.42%  |
| 32.01-64.0  | 3         | 2.24%   |
| 24.01-32.0  | 2         | 1.49%   |
| 2.01-3.0    | 1         | 0.75%   |
| 64.01-256.0 | 1         | 0.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 61        | 44.53%  |
| 0.51-1.0   | 56        | 40.88%  |
| 2.01-3.0   | 10        | 7.3%    |
| 1.01-2.0   | 8         | 5.84%   |
| 4.01-8.0   | 1         | 0.73%   |
| 24.01-32.0 | 1         | 0.73%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 102       | 75%     |
| 2      | 26        | 19.12%  |
| 0      | 7         | 5.15%   |
| 3      | 1         | 0.74%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 82        | 60.74%  |
| Yes       | 53        | 39.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 115       | 85.82%  |
| No        | 19        | 14.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 134       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 103       | 76.87%  |
| No        | 31        | 23.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 26        | 19.4%   |
| Germany      | 16        | 11.94%  |
| France       | 9         | 6.72%   |
| UK           | 8         | 5.97%   |
| Poland       | 6         | 4.48%   |
| Spain        | 5         | 3.73%   |
| Russia       | 4         | 2.99%   |
| Italy        | 4         | 2.99%   |
| Indonesia    | 4         | 2.99%   |
| India        | 4         | 2.99%   |
| Sweden       | 3         | 2.24%   |
| New Zealand  | 3         | 2.24%   |
| Brazil       | 3         | 2.24%   |
| Switzerland  | 2         | 1.49%   |
| Slovenia     | 2         | 1.49%   |
| Slovakia     | 2         | 1.49%   |
| Portugal     | 2         | 1.49%   |
| Philippines  | 2         | 1.49%   |
| Netherlands  | 2         | 1.49%   |
| Mauritius    | 2         | 1.49%   |
| Japan        | 2         | 1.49%   |
| Hong Kong    | 2         | 1.49%   |
| Finland      | 2         | 1.49%   |
| China        | 2         | 1.49%   |
| Canada       | 2         | 1.49%   |
| Belgium      | 2         | 1.49%   |
| Ukraine      | 1         | 0.75%   |
| Uganda       | 1         | 0.75%   |
| South Africa | 1         | 0.75%   |
| Serbia       | 1         | 0.75%   |
| Norway       | 1         | 0.75%   |
| Namibia      | 1         | 0.75%   |
| Malaysia     | 1         | 0.75%   |
| Kazakhstan   | 1         | 0.75%   |
| Hungary      | 1         | 0.75%   |
| Greece       | 1         | 0.75%   |
| Egypt        | 1         | 0.75%   |
| Bulgaria     | 1         | 0.75%   |
| Argentina    | 1         | 0.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Bedburg            | 6         | 4.29%   |
| Jakarta            | 3         | 2.14%   |
| Franconville       | 3         | 2.14%   |
| Chrusty            | 3         | 2.14%   |
| Bonn               | 3         | 2.14%   |
| Yokohama           | 2         | 1.43%   |
| Whittier           | 2         | 1.43%   |
| Wezeren            | 2         | 1.43%   |
| Stiring-Wendel     | 2         | 1.43%   |
| Rome               | 2         | 1.43%   |
| Paris              | 2         | 1.43%   |
| London             | 2         | 1.43%   |
| Giessen            | 2         | 1.43%   |
| Clemmons           | 2         | 1.43%   |
| Celje              | 2         | 1.43%   |
| Asnieres-sur-Seine | 2         | 1.43%   |
| Zurich             | 1         | 0.71%   |
| Yaroslavl          | 1         | 0.71%   |
| Wraysbury          | 1         | 0.71%   |
| Witbank            | 1         | 0.71%   |
| Winnipeg           | 1         | 0.71%   |
| Windhoek           | 1         | 0.71%   |
| Wenatchee          | 1         | 0.71%   |
| Valencia           | 1         | 0.71%   |
| Toronto            | 1         | 0.71%   |
| Taita              | 1         | 0.71%   |
| Staffanstorp       | 1         | 0.71%   |
| St Petersburg      | 1         | 0.71%   |
| St Austell         | 1         | 0.71%   |
| Sollentuna         | 1         | 0.71%   |
| Sofia              | 1         | 0.71%   |
| Santo Tomas        | 1         | 0.71%   |
| Salinas            | 1         | 0.71%   |
| Salem              | 1         | 0.71%   |
| Rochester          | 1         | 0.71%   |
| Richmond           | 1         | 0.71%   |
| Resistencia        | 1         | 0.71%   |
| Portland           | 1         | 0.71%   |
| Peoria             | 1         | 0.71%   |
| Pailles            | 1         | 0.71%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 41        | 53     | 26.62%  |
| WDC                 | 21        | 23     | 13.64%  |
| Kingston            | 16        | 16     | 10.39%  |
| Seagate             | 14        | 17     | 9.09%   |
| Toshiba             | 8         | 11     | 5.19%   |
| Crucial             | 8         | 9      | 5.19%   |
| SanDisk             | 7         | 7      | 4.55%   |
| SK hynix            | 5         | 7      | 3.25%   |
| Phison              | 3         | 4      | 1.95%   |
| Intel               | 3         | 3      | 1.95%   |
| Hitachi             | 3         | 3      | 1.95%   |
| PNY                 | 2         | 2      | 1.3%    |
| Patriot             | 2         | 2      | 1.3%    |
| Micron Technology   | 2         | 2      | 1.3%    |
| KingSpec            | 2         | 2      | 1.3%    |
| HGST                | 2         | 2      | 1.3%    |
| Goodram             | 2         | 2      | 1.3%    |
| Fujitsu             | 2         | 2      | 1.3%    |
| XUM                 | 1         | 1      | 0.65%   |
| Star Drive          | 1         | 1      | 0.65%   |
| SSSTC               | 1         | 1      | 0.65%   |
| Silicon Motion      | 1         | 1      | 0.65%   |
| Plextor             | 1         | 1      | 0.65%   |
| Netac               | 1         | 1      | 0.65%   |
| LITEONIT            | 1         | 1      | 0.65%   |
| Hewlett-Packard     | 1         | 1      | 0.65%   |
| Gigabyte Technology | 1         | 1      | 0.65%   |
| Apple               | 1         | 1      | 0.65%   |
| A-DATA Technology   | 1         | 1      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB          | 4         | 2.52%   |
| Seagate ST1000LM035-1RK172 1TB       | 3         | 1.89%   |
| Samsung SSD 860 EVO 500GB            | 3         | 1.89%   |
| Samsung SSD 850 EVO 250GB            | 3         | 1.89%   |
| WDC WDS500G2B0A-00SM50 500GB         | 2         | 1.26%   |
| SK hynix HFM512GD3JX013N 512GB       | 2         | 1.26%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 1.26%   |
| Samsung SSD 860 QVO 1TB              | 2         | 1.26%   |
| Samsung PM981 NVMe 256GB             | 2         | 1.26%   |
| Samsung MZNTE128HMGR-000SO 128GB     | 2         | 1.26%   |
| Kingston SA400S37120G 120GB          | 2         | 1.26%   |
| Kingston RBUSNS8154P3512GJ 512GB     | 2         | 1.26%   |
| KingSpec Q-720 720GB                 | 2         | 1.26%   |
| XUM HX256GSSDSATA3 256GB             | 1         | 0.63%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 0.63%   |
| WDC WDS120G2G0A-00JH30 120GB         | 1         | 0.63%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.63%   |
| WDC WDS100T2B0B-00YS70 1TB           | 1         | 0.63%   |
| WDC WDS100T1B0A-00H9H0 1TB           | 1         | 0.63%   |
| WDC WD7500BPVT-80HXZT3 752GB         | 1         | 0.63%   |
| WDC WD7500BPKX-80HPJT0 752GB         | 1         | 0.63%   |
| WDC WD6400BEVT-22A0RT0 640GB         | 1         | 0.63%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 1         | 0.63%   |
| WDC WD5000BPVT-00HXZT3 500GB         | 1         | 0.63%   |
| WDC WD3200LPVX-75V0TT0 320GB         | 1         | 0.63%   |
| WDC WD10SPZX-75Z10T3 1TB             | 1         | 0.63%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.63%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.63%   |
| WDC WD10JPVX-00JC3T0 1TB             | 1         | 0.63%   |
| WDC WD10JMVW-11AJGS1 1TB             | 1         | 0.63%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 0.63%   |
| WDC PC SN530 NVMe 256GB              | 1         | 0.63%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB | 1         | 0.63%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB | 1         | 0.63%   |
| Toshiba THNSF5256GPUK 256GB          | 1         | 0.63%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.63%   |
| Toshiba MQ01ACF032 320GB             | 1         | 0.63%   |
| Toshiba MQ01ABF050 500GB             | 1         | 0.63%   |
| Toshiba KXG50ZNV512G NVMe 512GB      | 1         | 0.63%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB  | 1         | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 17     | 38.89%  |
| WDC                 | 11        | 12     | 30.56%  |
| Toshiba             | 3         | 3      | 8.33%   |
| Hitachi             | 3         | 3      | 8.33%   |
| HGST                | 2         | 2      | 5.56%   |
| Fujitsu             | 2         | 2      | 5.56%   |
| Samsung Electronics | 1         | 1      | 2.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 35     | 32.5%   |
| Kingston            | 13        | 13     | 16.25%  |
| SanDisk             | 7         | 7      | 8.75%   |
| Crucial             | 7         | 8      | 8.75%   |
| WDC                 | 6         | 6      | 7.5%    |
| SK hynix            | 2         | 2      | 2.5%    |
| PNY                 | 2         | 2      | 2.5%    |
| Patriot             | 2         | 2      | 2.5%    |
| Micron Technology   | 2         | 2      | 2.5%    |
| KingSpec            | 2         | 2      | 2.5%    |
| Goodram             | 2         | 2      | 2.5%    |
| XUM                 | 1         | 1      | 1.25%   |
| Toshiba             | 1         | 2      | 1.25%   |
| Plextor             | 1         | 1      | 1.25%   |
| Phison              | 1         | 1      | 1.25%   |
| Netac               | 1         | 1      | 1.25%   |
| LITEONIT            | 1         | 1      | 1.25%   |
| Intel               | 1         | 1      | 1.25%   |
| Apple               | 1         | 1      | 1.25%   |
| A-DATA Technology   | 1         | 1      | 1.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 72        | 91     | 50%     |
| NVMe | 38        | 47     | 26.39%  |
| HDD  | 34        | 40     | 23.61%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 101       | 131    | 72.66%  |
| NVMe | 38        | 47     | 27.34%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 74        | 86     | 69.16%  |
| 0.51-1.0   | 28        | 39     | 26.17%  |
| 1.01-2.0   | 5         | 6      | 4.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 46        | 32.62%  |
| 101-250    | 35        | 24.82%  |
| 251-500    | 19        | 13.48%  |
| 501-1000   | 14        | 9.93%   |
| 51-100     | 13        | 9.22%   |
| Unknown    | 11        | 7.8%    |
| 1001-2000  | 2         | 1.42%   |
| 21-50      | 1         | 0.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 120       | 84.51%  |
| Unknown | 11        | 7.75%   |
| 21-50   | 8         | 5.63%   |
| 51-100  | 2         | 1.41%   |
| 101-250 | 1         | 0.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| Kingston SA400S37240G 240GB                     | 2         | 2      | 11.76%  |
| WDC WD6400BEVT-22A0RT0 640GB                    | 1         | 1      | 5.88%   |
| WDC WD3200LPVX-75V0TT0 320GB                    | 1         | 1      | 5.88%   |
| Toshiba MQ01ACF032 320GB                        | 1         | 1      | 5.88%   |
| Seagate ST9250827AS 250GB                       | 1         | 1      | 5.88%   |
| Seagate ST500LT012-9WS142 500GB                 | 1         | 2      | 5.88%   |
| Seagate ST500LM021-1KJ152 500GB                 | 1         | 1      | 5.88%   |
| Seagate ST1000LM035-1RK172 1TB                  | 1         | 2      | 5.88%   |
| Samsung Electronics SSD 980 500GB               | 1         | 1      | 5.88%   |
| Samsung Electronics SSD 840 PRO Series 256GB    | 1         | 1      | 5.88%   |
| Samsung Electronics MZNTE128HMGR-000SO 128GB    | 1         | 1      | 5.88%   |
| Patriot Inferno 60GB SSD                        | 1         | 1      | 5.88%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB | 1         | 1      | 5.88%   |
| Intel SSDSC2BF180A5L 180GB                      | 1         | 1      | 5.88%   |
| Hitachi HTS543225L9A300 250GB                   | 1         | 1      | 5.88%   |
| HGST HTS721010A9E630 1TB                        | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 6      | 23.53%  |
| Samsung Electronics | 3         | 3      | 17.65%  |
| WDC                 | 2         | 2      | 11.76%  |
| Kingston            | 2         | 2      | 11.76%  |
| Toshiba             | 1         | 1      | 5.88%   |
| Patriot             | 1         | 1      | 5.88%   |
| Micron Technology   | 1         | 1      | 5.88%   |
| Intel               | 1         | 1      | 5.88%   |
| Hitachi             | 1         | 1      | 5.88%   |
| HGST                | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 6      | 44.44%  |
| WDC     | 2         | 2      | 22.22%  |
| Toshiba | 1         | 1      | 11.11%  |
| Hitachi | 1         | 1      | 11.11%  |
| HGST    | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 11     | 52.94%  |
| SSD  | 7         | 7      | 41.18%  |
| NVMe | 1         | 1      | 5.88%   |

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


| Status  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 116       | 159    | 87.22%  |
| Malfunc | 17        | 19     | 12.78%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 100       | 65.79%  |
| Samsung Electronics            | 16        | 10.53%  |
| AMD                            | 11        | 7.24%   |
| SanDisk                        | 5         | 3.29%   |
| Phison Electronics             | 4         | 2.63%   |
| SK hynix                       | 3         | 1.97%   |
| Nvidia                         | 3         | 1.97%   |
| Kingston Technology Company    | 3         | 1.97%   |
| Toshiba                        | 2         | 1.32%   |
| Solid State Storage Technology | 1         | 0.66%   |
| Silicon Motion                 | 1         | 0.66%   |
| Micron/Crucial Technology      | 1         | 0.66%   |
| KIOXIA                         | 1         | 0.66%   |
| Biwin Storage Technology       | 1         | 0.66%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 18        | 11.46%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 13        | 8.28%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 11        | 7.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 7.01%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 10        | 6.37%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 5.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 5.1%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 3.82%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 2.55%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 2.55%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 2.55%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 2.55%   |
| Unknown                                                                        | 4         | 2.55%   |
| Nvidia MCP79 AHCI Controller                                                   | 3         | 1.91%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 1.91%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 1.91%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 2         | 1.27%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 1.27%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 1.27%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 2         | 1.27%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.27%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 1.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.27%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.27%   |
| Toshiba XG4 NVMe SSD Controller                                                | 1         | 0.64%   |
| Toshiba BG3 NVMe SSD Controller                                                | 1         | 0.64%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.64%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 0.64%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.64%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.64%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.64%   |
| SanDisk unknown                                                                | 1         | 0.64%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 0.64%   |
| Samsung SM951 AHCI                                                             | 1         | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.64%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 0.64%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.64%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 0.64%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 0.64%   |
| Intel SSD 660P Series                                                          | 1         | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 101       | 65.58%  |
| NVMe | 37        | 24.03%  |
| RAID | 11        | 7.14%   |
| IDE  | 5         | 3.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 115       | 85.82%  |
| AMD    | 19        | 14.18%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz             | 6         | 4.48%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 5         | 3.73%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 2.99%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 2.99%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 2.99%   |
| Intel Core 2 Duo                              | 4         | 2.99%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 2.24%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 2.24%   |
| Intel Core i9-10980HK CPU @ 2.40GHz           | 2         | 1.49%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 1.49%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.49%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.49%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.49%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 1.49%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.49%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 1.49%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 1.49%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.49%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.49%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.49%   |
| Intel Core i5-2520M CPU @ 2.50GH              | 2         | 1.49%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 1.49%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 1.49%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz          | 2         | 1.49%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.49%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.49%   |
| AMD Ryzen 5 3450U with Radeon Vega Mobile Gfx | 2         | 1.49%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 2         | 1.49%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.75%   |
| Intel Pentium 3558U @ 1.70GHz                 | 1         | 0.75%   |
| Intel Genuine CPU                             | 1         | 0.75%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.75%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.75%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 0.75%   |
| Intel Core i7-4770HQ CPU @ 2.20GHz            | 1         | 0.75%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.75%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 0.75%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 0.75%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 48        | 35.82%  |
| Intel Core i7    | 35        | 26.12%  |
| Intel Core 2 Duo | 11        | 8.21%   |
| Intel Core i3    | 10        | 7.46%   |
| AMD Ryzen 7      | 6         | 4.48%   |
| AMD Ryzen 5      | 6         | 4.48%   |
| Intel Celeron    | 4         | 2.99%   |
| Other            | 2         | 1.49%   |
| Intel Core i9    | 2         | 1.49%   |
| AMD A6           | 2         | 1.49%   |
| AMD A4           | 2         | 1.49%   |
| Intel Xeon       | 1         | 0.75%   |
| Intel Pentium    | 1         | 0.75%   |
| Intel Genuine    | 1         | 0.75%   |
| Intel Core 2     | 1         | 0.75%   |
| AMD Ryzen 3      | 1         | 0.75%   |
| AMD Athlon       | 1         | 0.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 69        | 51.49%  |
| 4       | 38        | 28.36%  |
| 8       | 9         | 6.72%   |
| Unknown | 7         | 5.22%   |
| 6       | 6         | 4.48%   |
| 16      | 3         | 2.24%   |
| 12      | 2         | 1.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 131       | 97.76%  |
| 2      | 3         | 2.24%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 97        | 72.39%  |
| 1       | 30        | 22.39%  |
| Unknown | 7         | 5.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 26        | 19.4%   |
| IvyBridge   | 19        | 14.18%  |
| Haswell     | 14        | 10.45%  |
| SandyBridge | 12        | 8.96%   |
| Skylake     | 11        | 8.21%   |
| Penryn      | 9         | 6.72%   |
| Zen+        | 7         | 5.22%   |
| Broadwell   | 7         | 5.22%   |
| CometLake   | 4         | 2.99%   |
| Westmere    | 3         | 2.24%   |
| IceLake     | 3         | 2.24%   |
| Core        | 3         | 2.24%   |
| Unknown     | 3         | 2.24%   |
| Zen 3       | 2         | 1.49%   |
| Zen 2       | 2         | 1.49%   |
| Goldmont    | 2         | 1.49%   |
| Excavator   | 2         | 1.49%   |
| TigerLake   | 1         | 0.75%   |
| Silvermont  | 1         | 0.75%   |
| Puma        | 1         | 0.75%   |
| K10 Llano   | 1         | 0.75%   |
| K10         | 1         | 0.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 105       | 64.81%  |
| Nvidia | 32        | 19.75%  |
| AMD    | 25        | 15.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 16        | 9.58%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 12        | 7.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 11        | 6.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 7         | 4.19%   |
| Intel HD Graphics 5500                                                    | 7         | 4.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 7         | 4.19%   |
| Intel UHD Graphics 620                                                    | 6         | 3.59%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 6         | 3.59%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 6         | 3.59%   |
| Intel HD Graphics 620                                                     | 5         | 2.99%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 4         | 2.4%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 1.8%    |
| Nvidia C79 [GeForce 9400M]                                                | 3         | 1.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 3         | 1.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 3         | 1.8%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 1.8%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 3         | 1.8%    |
| Intel HD Graphics 530                                                     | 3         | 1.8%    |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 3         | 1.8%    |
| AMD Lucienne                                                              | 3         | 1.8%    |
| Nvidia GF108GLM [NVS 5200M]                                               | 2         | 1.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 1.2%    |
| Intel HD Graphics 500                                                     | 2         | 1.2%    |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.2%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 2         | 1.2%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 2         | 1.2%    |
| AMD Renoir                                                                | 2         | 1.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 1.2%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.6%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.6%    |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                     | 1         | 0.6%    |
| Nvidia GT218M [NVS 3100M]                                                 | 1         | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.6%    |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                     | 1         | 0.6%    |
| Nvidia GM206M [GeForce GTX 965M]                                          | 1         | 0.6%    |
| Nvidia GM108M [GeForce MX130]                                             | 1         | 0.6%    |
| Nvidia GM107GLM [Quadro M2000M]                                           | 1         | 0.6%    |
| Nvidia GM107 [GeForce 940MX]                                              | 1         | 0.6%    |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 0.6%    |
| Nvidia GK107M [GeForce GTX 660M]                                          | 1         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 71        | 52.99%  |
| Intel + Nvidia | 24        | 17.91%  |
| 1 x AMD        | 20        | 14.93%  |
| 2 x Intel      | 7         | 5.22%   |
| 1 x Nvidia     | 7         | 5.22%   |
| Intel + AMD    | 3         | 2.24%   |
| 2 x AMD        | 1         | 0.75%   |
| AMD + Nvidia   | 1         | 0.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 127       | 94.07%  |
| Proprietary | 8         | 5.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 118       | 86.76%  |
| 1.01-2.0   | 6         | 4.41%   |
| 0.01-0.5   | 6         | 4.41%   |
| 0.51-1.0   | 4         | 2.94%   |
| 3.01-4.0   | 2         | 1.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 24        | 20%     |
| AU Optronics            | 23        | 19.17%  |
| LG Display              | 22        | 18.33%  |
| Samsung Electronics     | 14        | 11.67%  |
| BOE                     | 10        | 8.33%   |
| Lenovo                  | 4         | 3.33%   |
| Philips                 | 3         | 2.5%    |
| PANDA                   | 2         | 1.67%   |
| Panasonic               | 2         | 1.67%   |
| InfoVision              | 2         | 1.67%   |
| Dell                    | 2         | 1.67%   |
| BenQ                    | 2         | 1.67%   |
| ___                     | 1         | 0.83%   |
| Iiyama                  | 1         | 0.83%   |
| IBM                     | 1         | 0.83%   |
| Hewlett-Packard         | 1         | 0.83%   |
| Goldstar                | 1         | 0.83%   |
| Fujitsu Siemens         | 1         | 0.83%   |
| CSO                     | 1         | 0.83%   |
| Chi Mei Optoelectronics | 1         | 0.83%   |
| Apple                   | 1         | 0.83%   |
| Unknown                 | 1         | 0.83%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 2         | 1.65%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch  | 2         | 1.65%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 290x170mm 13.2-inch | 2         | 1.65%   |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch              | 2         | 1.65%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch          | 2         | 1.65%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch           | 2         | 1.65%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch           | 2         | 1.65%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch           | 2         | 1.65%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 2         | 1.65%   |
| LG Display LCD Monitor LGD01E9 1920x1080 350x190mm 15.7-inch          | 2         | 1.65%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch      | 2         | 1.65%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch      | 2         | 1.65%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 2         | 1.65%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch       | 2         | 1.65%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 290x160mm 13.0-inch        | 2         | 1.65%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch         | 2         | 1.65%   |
| ___ MY TV LED TV ___0101 1920x1080                                    | 1         | 0.83%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch  | 1         | 0.83%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 310x170mm 13.9-inch  | 1         | 0.83%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 1         | 0.83%   |
| Philips PHL BDM4065 PHL08E1 3840x2160 880x490mm 39.7-inch             | 1         | 0.83%   |
| PANDA LCD Monitor NCP0040 1920x1080 340x190mm 15.3-inch               | 1         | 0.83%   |
| PANDA LC133LF1L02 NCP0019 1920x1080 290x170mm 13.2-inch               | 1         | 0.83%   |
| LG Display LCD Monitor LGD066E 1920x1080 340x190mm 15.3-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD0558 1920x1080 310x170mm 13.9-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD0533 1920x1080 340x190mm 15.3-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD04D5 1920x1080 340x190mm 15.3-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD042D 1920x1080 290x170mm 13.2-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 1         | 0.83%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 48        | 41.38%  |
| 1366x768 (WXGA)    | 43        | 37.07%  |
| 1600x900 (HD+)     | 8         | 6.9%    |
| 2560x1440 (QHD)    | 4         | 3.45%   |
| 3840x2160 (4K)     | 2         | 1.72%   |
| 2880x1620          | 2         | 1.72%   |
| 1680x1050 (WSXGA+) | 2         | 1.72%   |
| 1280x800 (WXGA)    | 2         | 1.72%   |
| 9600x2160          | 1         | 0.86%   |
| 3840x1600          | 1         | 0.86%   |
| 2880x1800          | 1         | 0.86%   |
| 1440x900 (WXGA+)   | 1         | 0.86%   |
| 1280x1024 (SXGA)   | 1         | 0.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 54        | 44.63%  |
| 13      | 31        | 25.62%  |
| 17      | 7         | 5.79%   |
| 12      | 6         | 4.96%   |
| 23      | 4         | 3.31%   |
| 14      | 4         | 3.31%   |
| 24      | 3         | 2.48%   |
| 11      | 3         | 2.48%   |
| Unknown | 2         | 1.65%   |
| 39      | 1         | 0.83%   |
| 37      | 1         | 0.83%   |
| 31      | 1         | 0.83%   |
| 27      | 1         | 0.83%   |
| 22      | 1         | 0.83%   |
| 21      | 1         | 0.83%   |
| 16      | 1         | 0.83%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 77        | 64.17%  |
| 201-300     | 21        | 17.5%   |
| 501-600     | 8         | 6.67%   |
| 351-400     | 7         | 5.83%   |
| 801-900     | 2         | 1.67%   |
| 401-500     | 2         | 1.67%   |
| Unknown     | 2         | 1.67%   |
| 601-700     | 1         | 0.83%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 97        | 88.18%  |
| 16/10   | 9         | 8.18%   |
| 5/4     | 1         | 0.91%   |
| 3/2     | 1         | 0.91%   |
| 21/9    | 1         | 0.91%   |
| Unknown | 1         | 0.91%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 43        | 35.54%  |
| 81-90          | 27        | 22.31%  |
| 101-110        | 11        | 9.09%   |
| 201-250        | 9         | 7.44%   |
| 71-80          | 8         | 6.61%   |
| 61-70          | 6         | 4.96%   |
| 121-130        | 6         | 4.96%   |
| 51-60          | 3         | 2.48%   |
| 501-1000       | 2         | 1.65%   |
| Unknown        | 2         | 1.65%   |
| 351-500        | 1         | 0.83%   |
| 301-350        | 1         | 0.83%   |
| 141-150        | 1         | 0.83%   |
| 111-120        | 1         | 0.83%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 50        | 42.02%  |
| 101-120       | 35        | 29.41%  |
| 51-100        | 17        | 14.29%  |
| 161-240       | 14        | 11.76%  |
| Unknown       | 2         | 1.68%   |
| More than 240 | 1         | 0.84%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 102       | 74.45%  |
| 0     | 21        | 15.33%  |
| 2     | 14        | 10.22%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 86        | 40%     |
| Realtek Semiconductor             | 49        | 22.79%  |
| Qualcomm Atheros                  | 33        | 15.35%  |
| Broadcom                          | 14        | 6.51%   |
| TP-Link                           | 5         | 2.33%   |
| Ericsson Business Mobile Networks | 4         | 1.86%   |
| Nvidia                            | 3         | 1.4%    |
| ASUSTek Computer                  | 3         | 1.4%    |
| Sierra Wireless                   | 2         | 0.93%   |
| Samsung Electronics               | 2         | 0.93%   |
| Ralink Technology                 | 2         | 0.93%   |
| Marvell Technology Group          | 2         | 0.93%   |
| Edimax Technology                 | 2         | 0.93%   |
| Xiaomi                            | 1         | 0.47%   |
| Ralink                            | 1         | 0.47%   |
| Qualcomm Atheros Communications   | 1         | 0.47%   |
| Qualcomm                          | 1         | 0.47%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.47%   |
| Huawei Technologies               | 1         | 0.47%   |
| Hewlett-Packard                   | 1         | 0.47%   |
| Generic                           | 1         | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33        | 11.96%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 5.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 3.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 3.26%   |
| Intel Wireless 8265 / 8275                                        | 9         | 3.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 3.26%   |
| Intel Wireless 8260                                               | 8         | 2.9%    |
| Intel Wireless 7265                                               | 8         | 2.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 2.54%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 2.17%   |
| Intel Wireless 7260                                               | 5         | 1.81%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 1.81%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.81%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 1.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.45%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 1.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 1.09%   |
| Nvidia MCP79 Ethernet                                             | 3         | 1.09%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 1.09%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 1.09%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.72%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.72%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.72%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 2         | 0.72%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.72%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.72%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.72%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 0.72%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 82        | 54.67%  |
| Qualcomm Atheros                | 27        | 18%     |
| Realtek Semiconductor           | 17        | 11.33%  |
| Broadcom                        | 8         | 5.33%   |
| TP-Link                         | 5         | 3.33%   |
| ASUSTek Computer                | 3         | 2%      |
| Sierra Wireless                 | 2         | 1.33%   |
| Ralink Technology               | 2         | 1.33%   |
| Edimax Technology               | 2         | 1.33%   |
| Ralink                          | 1         | 0.67%   |
| Qualcomm Atheros Communications | 1         | 0.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 5.96%   |
| Intel Wireless 8265 / 8275                                     | 9         | 5.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 5.96%   |
| Intel Wireless 8260                                            | 8         | 5.3%    |
| Intel Wireless 7265                                            | 8         | 5.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 7         | 4.64%   |
| Intel Wireless 7260                                            | 5         | 3.31%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 3.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 3.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 3.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 2.65%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 2.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.99%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 1.32%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 1.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.32%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.32%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 1.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.32%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 2         | 1.32%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.32%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.32%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.32%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 1.32%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 1.32%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2         | 1.32%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 1.32%   |
| TP-Link TP-Link High Power Wireless USB Adapter                | 1         | 0.66%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.66%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.66%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                  | 1         | 0.66%   |
| Sierra Wireless EM7455                                         | 1         | 0.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.66%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 0.66%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.66%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 49        | 41.88%  |
| Realtek Semiconductor         | 42        | 35.9%   |
| Qualcomm Atheros              | 9         | 7.69%   |
| Broadcom                      | 7         | 5.98%   |
| Nvidia                        | 3         | 2.56%   |
| Samsung Electronics           | 2         | 1.71%   |
| Marvell Technology Group      | 2         | 1.71%   |
| Xiaomi                        | 1         | 0.85%   |
| Qualcomm                      | 1         | 0.85%   |
| OnePlus Technology (Shenzhen) | 1         | 0.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33        | 27.97%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 13.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 7.63%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 5.08%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 4.24%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 4.24%   |
| Nvidia MCP79 Ethernet                                             | 3         | 2.54%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 2.54%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 2.54%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.69%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.69%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.69%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.69%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.69%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.69%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.85%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.85%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.85%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 0.85%   |
| OnePlus (Shenzhen) OnePlus RNDIS Control RNDIS Ethernet Data      | 1         | 0.85%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.85%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.85%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.85%   |
| Intel I225-K2                                                     | 1         | 0.85%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.85%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.85%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.85%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.85%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 0.85%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.85%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.85%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 135       | 52.33%  |
| Ethernet | 116       | 44.96%  |
| Modem    | 6         | 2.33%   |
| Unknown  | 1         | 0.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 94        | 50.81%  |
| Ethernet | 88        | 47.57%  |
| Modem    | 3         | 1.62%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 110       | 82.09%  |
| 1     | 23        | 17.16%  |
| 3     | 1         | 0.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 134       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 56        | 53.85%  |
| Realtek Semiconductor           | 8         | 7.69%   |
| Qualcomm Atheros Communications | 8         | 7.69%   |
| Lite-On Technology              | 7         | 6.73%   |
| Broadcom                        | 7         | 6.73%   |
| IMC Networks                    | 5         | 4.81%   |
| Dell                            | 5         | 4.81%   |
| Apple                           | 4         | 3.85%   |
| Alps Electric                   | 2         | 1.92%   |
| Toshiba                         | 1         | 0.96%   |
| ASUSTek Computer                | 1         | 0.96%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 28        | 26.92%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 11        | 10.58%  |
| Intel AX201 Bluetooth                                       | 6         | 5.77%   |
| Intel AX200 Bluetooth                                       | 5         | 4.81%   |
| Realtek  Bluetooth 4.2 Adapter                              | 4         | 3.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 4         | 3.85%   |
| Apple Bluetooth Host Controller                             | 4         | 3.85%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 3         | 2.88%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 3         | 2.88%   |
| Lite-On Atheros AR3012 Bluetooth                            | 3         | 2.88%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 3         | 2.88%   |
| Realtek Bluetooth Radio                                     | 2         | 1.92%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 2         | 1.92%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 1.92%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 1.92%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 1.92%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 1.92%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.92%   |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip             | 1         | 0.96%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.96%   |
| Realtek  Bluetooth Adapter                                  | 1         | 0.96%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.96%   |
| Lite-On Broadcom Bluetooth 4.0 USB                          | 1         | 0.96%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.96%   |
| Intel AX210 Bluetooth                                       | 1         | 0.96%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 0.96%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0          | 1         | 0.96%   |
| IMC Networks Bluetooth Module                               | 1         | 0.96%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 0.96%   |
| Dell DW375 Bluetooth Module                                 | 1         | 0.96%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 0.96%   |
| ASUS ASUS USB-BT500                                         | 1         | 0.96%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 0.96%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)             | 1         | 0.96%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 112       | 75.68%  |
| AMD                   | 21        | 14.19%  |
| Nvidia                | 10        | 6.76%   |
| RODE Microphones      | 1         | 0.68%   |
| Realtek Semiconductor | 1         | 0.68%   |
| Logitech              | 1         | 0.68%   |
| DSEA A/S              | 1         | 0.68%   |
| Cambridge Audio       | 1         | 0.68%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 20        | 10.64%  |
| Intel Sunrise Point-LP HD Audio                                            | 18        | 9.57%   |
| AMD Family 17h/19h HD Audio Controller                                     | 14        | 7.45%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 5.85%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 5.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 5.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 3.72%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 3.72%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 3.72%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 3.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 3.72%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 3.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 2.66%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 2.13%   |
| Nvidia MCP79 High Definition Audio                                         | 3         | 1.6%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.6%    |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.6%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 1.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 1.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 1.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.06%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 1.06%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.06%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 1.06%   |
| AMD High Definition Audio Controller                                       | 2         | 1.06%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.06%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.06%   |
| RODE Microphones RDE NT-USB Mini                                           | 1         | 0.53%   |
| Realtek Semiconductor Realtek USB Audio                                    | 1         | 0.53%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.53%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.53%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.53%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.53%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.53%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.53%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.53%   |
| Logitech H600 [Wireless Headset]                                           | 1         | 0.53%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 0.53%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.53%   |
| Intel Crystal Well HD Audio Controller                                     | 1         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 54        | 31.03%  |
| SK hynix            | 49        | 28.16%  |
| Micron Technology   | 16        | 9.2%    |
| Kingston            | 11        | 6.32%   |
| Unknown             | 8         | 4.6%    |
| Crucial             | 7         | 4.02%   |
| Elpida              | 6         | 3.45%   |
| Corsair             | 4         | 2.3%    |
| Unknown (ABCD)      | 2         | 1.15%   |
| Transcend           | 2         | 1.15%   |
| Ramaxel Technology  | 2         | 1.15%   |
| Goodram             | 2         | 1.15%   |
| G.Skill             | 2         | 1.15%   |
| A-DATA Technology   | 2         | 1.15%   |
| Team                | 1         | 0.57%   |
| Smart               | 1         | 0.57%   |
| Neo Forza           | 1         | 0.57%   |
| Nanya Technology    | 1         | 0.57%   |
| Apacer              | 1         | 0.57%   |
| 09490000802C        | 1         | 0.57%   |
| Unknown             | 1         | 0.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 5.06%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 3.93%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 2.81%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 2.81%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 5         | 2.81%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 2.25%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 4         | 2.25%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 2.25%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 2.25%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 3         | 1.69%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 1.12%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2133MT/s | 2         | 1.12%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s             | 2         | 1.12%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.12%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 1.12%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.12%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 2         | 1.12%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.12%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1.12%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.12%   |
| Micron RAM Module 8GB SODIMM DDR3 1600MT/s                       | 2         | 1.12%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 1.12%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 2         | 1.12%   |
| Unknown SODIMM 4GB SODIMM 800MT/s                                | 1         | 0.56%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.56%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 1         | 0.56%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 1         | 0.56%   |
| Unknown RAM GD2.09293S.001 16GB SODIMM DDR4 2400MT/s             | 1         | 0.56%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR 667MT/s                 | 1         | 0.56%   |
| Transcend RAM JM1333KSH-8G 8GB SODIMM DDR3 1333MT/s              | 1         | 0.56%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.56%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 1         | 0.56%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 0.56%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 0.56%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 1         | 0.56%   |
| SK hynix RAM LX8GDDR3LS1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.56%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.56%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.56%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 71        | 51.45%  |
| DDR4    | 51        | 36.96%  |
| DDR2    | 5         | 3.62%   |
| LPDDR4  | 4         | 2.9%    |
| LPDDR3  | 3         | 2.17%   |
| DDR     | 3         | 2.17%   |
| Unknown | 1         | 0.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 131       | 95.62%  |
| Row Of Chips | 6         | 4.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 65        | 43.05%  |
| 8192  | 62        | 41.06%  |
| 2048  | 12        | 7.95%   |
| 16384 | 10        | 6.62%   |
| 32768 | 1         | 0.66%   |
| 1024  | 1         | 0.66%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 49        | 33.11%  |
| 2667    | 25        | 16.89%  |
| 2400    | 15        | 10.14%  |
| 1334    | 12        | 8.11%   |
| 2133    | 11        | 7.43%   |
| 3200    | 10        | 6.76%   |
| 1333    | 8         | 5.41%   |
| 800     | 6         | 4.05%   |
| Unknown | 4         | 2.7%    |
| 1067    | 3         | 2.03%   |
| 4266    | 2         | 1.35%   |
| 667     | 2         | 1.35%   |
| 1867    | 1         | 0.68%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 27        | 25.47%  |
| Realtek Semiconductor                  | 12        | 11.32%  |
| Microdia                               | 12        | 11.32%  |
| IMC Networks                           | 11        | 10.38%  |
| Bison Electronics                      | 11        | 10.38%  |
| Quanta                                 | 6         | 5.66%   |
| Suyin                                  | 5         | 4.72%   |
| Sunplus Innovation Technology          | 5         | 4.72%   |
| Alcor Micro                            | 4         | 3.77%   |
| Silicon Motion                         | 2         | 1.89%   |
| Ricoh                                  | 2         | 1.89%   |
| Lite-On Technology                     | 2         | 1.89%   |
| Syntek                                 | 1         | 0.94%   |
| OmniVision Technologies                | 1         | 0.94%   |
| Luxvisions Innotech Limited            | 1         | 0.94%   |
| Logitech                               | 1         | 0.94%   |
| Lenovo                                 | 1         | 0.94%   |
| Importek                               | 1         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 0.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 8         | 7.55%   |
| Bison Integrated Camera                       | 7         | 6.6%    |
| Microdia Integrated_Webcam_HD                 | 5         | 4.72%   |
| Microdia Integrated Webcam                    | 5         | 4.72%   |
| Realtek Integrated_Webcam_HD                  | 4         | 3.77%   |
| IMC Networks Integrated Camera                | 4         | 3.77%   |
| Chicony USB2.0 HD UVC WebCam                  | 3         | 2.83%   |
| Chicony HD WebCam                             | 3         | 2.83%   |
| Chicony Chicony USB2.0 Camera                 | 3         | 2.83%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 2         | 1.89%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 2         | 1.89%   |
| Realtek Lenovo EasyCamera                     | 2         | 1.89%   |
| Realtek Integrated Webcam HD                  | 2         | 1.89%   |
| Realtek Front Camera                          | 2         | 1.89%   |
| Quanta VGA WebCam                             | 2         | 1.89%   |
| Quanta HP TrueVision HD Camera                | 2         | 1.89%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 2         | 1.89%   |
| IMC Networks USB2.0 HD UVC WebCam             | 2         | 1.89%   |
| Chicony Integrated Camera (1280x720@30)       | 2         | 1.89%   |
| Bison ThinkPad P50 Integrated Camera          | 2         | 1.89%   |
| Syntek Lenovo EasyCamera                      | 1         | 0.94%   |
| Suyin RGBIR Camera                            | 1         | 0.94%   |
| Suyin Integrated_Webcam_HD                    | 1         | 0.94%   |
| Suyin HD WebCam                               | 1         | 0.94%   |
| Sunplus SPCA2085 PC Camera                    | 1         | 0.94%   |
| Sunplus MTD camera                            | 1         | 0.94%   |
| Sunplus Integrated_Webcam_HD                  | 1         | 0.94%   |
| Silicon Motion WebCam SC-13HDL11939N          | 1         | 0.94%   |
| Silicon Motion Realtek USB2.0 PC Camera       | 1         | 0.94%   |
| Ricoh USB2.0 Camera                           | 1         | 0.94%   |
| Ricoh HD Webcam                               | 1         | 0.94%   |
| Realtek USB Camera                            | 1         | 0.94%   |
| Realtek Realtek USB2.0 PC Camera              | 1         | 0.94%   |
| Quanta USB2.0 HD UVC WebCam                   | 1         | 0.94%   |
| Quanta HP Universal Camera                    | 1         | 0.94%   |
| OmniVision OV2640 Webcam                      | 1         | 0.94%   |
| Microdia Sonix Integrated Webcam              | 1         | 0.94%   |
| Microdia Laptop_Integrated_Webcam_HD          | 1         | 0.94%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 0.94%   |
| Logitech HD Pro Webcam C920                   | 1         | 0.94%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 39.13%  |
| Upek                       | 3         | 13.04%  |
| Synaptics                  | 3         | 13.04%  |
| STMicroelectronics         | 2         | 8.7%    |
| Shenzhen Goodix Technology | 1         | 4.35%   |
| Next Biometrics            | 1         | 4.35%   |
| LighTuning Technology      | 1         | 4.35%   |
| Focal-systems.Corp         | 1         | 4.35%   |
| Broadcom                   | 1         | 4.35%   |
| AuthenTec                  | 1         | 4.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 5         | 21.74%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 8.7%    |
| STMicroelectronics Fingerprint Reader                                        | 2         | 8.7%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 4.35%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 4.35%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 4.35%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 1         | 4.35%   |
| Upek TCS5B Fingerprint sensor                                                | 1         | 4.35%   |
| Synaptics  WBDI                                                              | 1         | 4.35%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 4.35%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 4.35%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 4.35%   |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 4.35%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 1         | 4.35%   |
| Focal-systems.Corp FocalTech Fingerprint reader                              | 1         | 4.35%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.35%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 4.35%   |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 47        | 33.33%  |
| 1     | 35        | 24.82%  |
| 3     | 28        | 19.86%  |
| 4     | 19        | 13.48%  |
| 0     | 9         | 6.38%   |
| 5     | 3         | 2.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 101       | 35.56%  |
| Bluetooth                | 71        | 25%     |
| Net/wireless             | 37        | 13.03%  |
| Card reader              | 32        | 11.27%  |
| Fingerprint reader       | 24        | 8.45%   |
| Firewire controller      | 9         | 3.17%   |
| Network                  | 6         | 2.11%   |
| Storage                  | 4         | 1.41%   |

