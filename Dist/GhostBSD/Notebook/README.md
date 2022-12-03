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

Total: 172

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| GhostBSD 20.04.02    | 58        | 42.96%  |
| GhostBSD 21.08.27    | 29        | 21.48%  |
| GhostBSD 22.01.12    | 13        | 9.63%   |
| GhostBSD 22.06.18    | 5         | 3.7%    |
| GhostBSD 22.06.26    | 3         | 2.22%   |
| GhostBSD 22.11.02    | 2         | 1.48%   |
| GhostBSD 22.08.23    | 2         | 1.48%   |
| GhostBSD 22.08.06    | 2         | 1.48%   |
| GhostBSD 22.07.16    | 2         | 1.48%   |
| GhostBSD 22.11.22    | 1         | 0.74%   |
| GhostBSD 22.10.30    | 1         | 0.74%   |
| GhostBSD 22.09.16    | 1         | 0.74%   |
| GhostBSD 22.08.27    | 1         | 0.74%   |
| GhostBSD 22.07.31    | 1         | 0.74%   |
| GhostBSD 22.07.28    | 1         | 0.74%   |
| GhostBSD 22.07.13    | 1         | 0.74%   |
| GhostBSD 22.07.10    | 1         | 0.74%   |
| GhostBSD 22.06.20    | 1         | 0.74%   |
| GhostBSD 22.06.07    | 1         | 0.74%   |
| GhostBSD 22.05.13    | 1         | 0.74%   |
| GhostBSD 22.04.30    | 1         | 0.74%   |
| GhostBSD 22.04.22    | 1         | 0.74%   |
| GhostBSD 22.04.06    | 1         | 0.74%   |
| GhostBSD 21.12.29    | 1         | 0.74%   |
| GhostBSD 21.11.24    | 1         | 0.74%   |
| GhostBSD 20.07.14    | 1         | 0.74%   |
| GhostBSD 20.03.01    | 1         | 0.74%   |
| GhostBSD 12.2-STABLE | 1         | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| GhostBSD | 125       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 125       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| MATE         | 98        | 76.56%  |
| XFCE         | 19        | 14.84%  |
| KDE5         | 6         | 4.69%   |
| Cinnamon     | 2         | 1.56%   |
| helloDesktop | 1         | 0.78%   |
| GNOME        | 1         | 0.78%   |
| Console      | 1         | 0.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 123       | 98.4%   |
| Wayland | 1         | 0.8%    |
| Console | 1         | 0.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 123       | 98.4%   |
| SDDM    | 1         | 0.8%    |
| Console | 1         | 0.8%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 52        | 39.69%  |
| C       | 43        | 32.82%  |
| Unknown | 16        | 12.21%  |
| de_DE   | 5         | 3.82%   |
| pt_BR   | 2         | 1.53%   |
| pl_PL   | 2         | 1.53%   |
| it_IT   | 2         | 1.53%   |
| en_GB   | 2         | 1.53%   |
| zh_CN   | 1         | 0.76%   |
| sv_SE   | 1         | 0.76%   |
| sk_SK   | 1         | 0.76%   |
| ru_RU   | 1         | 0.76%   |
| es_ES   | 1         | 0.76%   |
| en_NZ   | 1         | 0.76%   |
| el_GR   | 1         | 0.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 96        | 76.8%   |
| BIOS | 29        | 23.2%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 118       | 91.47%  |
| Ufs  | 11        | 8.53%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 122       | 97.6%   |
| MBR  | 3         | 2.4%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 32        | 25.6%   |
| Dell                | 29        | 23.2%   |
| Hewlett-Packard     | 12        | 9.6%    |
| ASUSTek Computer    | 10        | 8%      |
| Acer                | 10        | 8%      |
| Sony                | 4         | 3.2%    |
| Notebook            | 4         | 3.2%    |
| MSI                 | 4         | 3.2%    |
| Apple               | 4         | 3.2%    |
| System76            | 3         | 2.4%    |
| Toshiba             | 2         | 1.6%    |
| Samsung Electronics | 2         | 1.6%    |
| Fujitsu             | 2         | 1.6%    |
| TUXEDO              | 1         | 0.8%    |
| Star Labs           | 1         | 0.8%    |
| Panasonic           | 1         | 0.8%    |
| Jumper              | 1         | 0.8%    |
| HUAWEI              | 1         | 0.8%    |
| GPU Company         | 1         | 0.8%    |
| Alienware           | 1         | 0.8%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Inspiron 3542                       | 3         | 2.4%    |
| MSI Modern 14 A10M                       | 2         | 1.6%    |
| Lenovo ThinkPad T430s 2352CTO            | 2         | 1.6%    |
| Dell XPS 13 7390                         | 2         | 1.6%    |
| Dell Latitude E6420                      | 2         | 1.6%    |
| ASUS ZenBook UX325UA_UM325UA             | 2         | 1.6%    |
| TUXEDO InfinityBook13V3                  | 1         | 0.8%    |
| Toshiba Satellite C855-1U4               | 1         | 0.8%    |
| Toshiba Satellite C855                   | 1         | 0.8%    |
| System76 Lemur Pro                       | 1         | 0.8%    |
| System76 Kudu                            | 1         | 0.8%    |
| System76 Gazelle                         | 1         | 0.8%    |
| Star Labs LabTop                         | 1         | 0.8%    |
| Sony VPCCB17FG                           | 1         | 0.8%    |
| Sony VGN-SZ3VWP_X                        | 1         | 0.8%    |
| Sony SVP1322M1EBI                        | 1         | 0.8%    |
| Sony SVP13225SCBI                        | 1         | 0.8%    |
| Samsung 550P5C/550P7C                    | 1         | 0.8%    |
| Samsung 3570R/370R/470R/450R/510R/4450RV | 1         | 0.8%    |
| Panasonic CF-19AHNC8FN                   | 1         | 0.8%    |
| Notebook N8xEJEK                         | 1         | 0.8%    |
| Notebook N85_N87,HJ,HJ1,HK1              | 1         | 0.8%    |
| Notebook N7x0WU                          | 1         | 0.8%    |
| Notebook N13xWU                          | 1         | 0.8%    |
| MSI GF63 Thin 10SCSR                     | 1         | 0.8%    |
| MSI GE75 Raider 10SFS                    | 1         | 0.8%    |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS       | 1         | 0.8%    |
| Lenovo Yoga 2 13 20344                   | 1         | 0.8%    |
| Lenovo ThinkPad X250 20CM003WMS          | 1         | 0.8%    |
| Lenovo ThinkPad X250 20CL001GZA          | 1         | 0.8%    |
| Lenovo ThinkPad X220 4290W42             | 1         | 0.8%    |
| Lenovo ThinkPad X220 42872VU             | 1         | 0.8%    |
| Lenovo ThinkPad X201 32492EU             | 1         | 0.8%    |
| Lenovo ThinkPad T590 20N40016CD          | 1         | 0.8%    |
| Lenovo ThinkPad T530 239242U             | 1         | 0.8%    |
| Lenovo ThinkPad T520 4243E51             | 1         | 0.8%    |
| Lenovo ThinkPad T500 2056Y2Z             | 1         | 0.8%    |
| Lenovo ThinkPad T470 W10DG 20JNS0JU01    | 1         | 0.8%    |
| Lenovo ThinkPad T470 20HD000MUK          | 1         | 0.8%    |
| Lenovo ThinkPad T450 20BV0064US          | 1         | 0.8%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 23        | 18.4%   |
| Dell Latitude           | 16        | 12.8%   |
| Dell Inspiron           | 8         | 6.4%    |
| Acer Aspire             | 8         | 6.4%    |
| HP Laptop               | 5         | 4%      |
| Lenovo IdeaPad          | 4         | 3.2%    |
| HP EliteBook            | 3         | 2.4%    |
| Dell XPS                | 3         | 2.4%    |
| Toshiba Satellite       | 2         | 1.6%    |
| MSI Modern              | 2         | 1.6%    |
| Lenovo Yoga             | 2         | 1.6%    |
| Dell Precision          | 2         | 1.6%    |
| ASUS ZenBook            | 2         | 1.6%    |
| ASUS VivoBook           | 2         | 1.6%    |
| TUXEDO InfinityBook13V3 | 1         | 0.8%    |
| System76 Lemur          | 1         | 0.8%    |
| System76 Kudu           | 1         | 0.8%    |
| System76 Gazelle        | 1         | 0.8%    |
| Star Labs LabTop        | 1         | 0.8%    |
| Sony VPCCB17FG          | 1         | 0.8%    |
| Sony VGN-SZ3VWP         | 1         | 0.8%    |
| Sony SVP1322M1EBI       | 1         | 0.8%    |
| Sony SVP13225SCBI       | 1         | 0.8%    |
| Samsung 550P5C          | 1         | 0.8%    |
| Samsung 3570R           | 1         | 0.8%    |
| Panasonic CF-19AHNC8FN  | 1         | 0.8%    |
| Notebook N8xEJEK        | 1         | 0.8%    |
| Notebook N85            | 1         | 0.8%    |
| Notebook N7x0WU         | 1         | 0.8%    |
| Notebook N13xWU         | 1         | 0.8%    |
| MSI GF63                | 1         | 0.8%    |
| MSI GE75                | 1         | 0.8%    |
| Lenovo Legion           | 1         | 0.8%    |
| Lenovo G500s            | 1         | 0.8%    |
| Lenovo Flex             | 1         | 0.8%    |
| Jumper EZbook           | 1         | 0.8%    |
| HUAWEI HLY-WX9XX        | 1         | 0.8%    |
| HP Pavilion             | 1         | 0.8%    |
| HP OMEN                 | 1         | 0.8%    |
| HP 255                  | 1         | 0.8%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 19        | 15.2%   |
| 2013 | 16        | 12.8%   |
| 2021 | 14        | 11.2%   |
| 2018 | 10        | 8%      |
| 2014 | 10        | 8%      |
| 2011 | 8         | 6.4%    |
| 2015 | 7         | 5.6%    |
| 2012 | 7         | 5.6%    |
| 2009 | 7         | 5.6%    |
| 2017 | 6         | 4.8%    |
| 2019 | 5         | 4%      |
| 2022 | 4         | 3.2%    |
| 2016 | 4         | 3.2%    |
| 2010 | 4         | 3.2%    |
| 2008 | 3         | 2.4%    |
| 2007 | 1         | 0.8%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 125       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 124       | 99.2%   |
| Yes  | 1         | 0.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 65        | 52%     |
| 16.01-24.0 | 33        | 26.4%   |
| 4.01-8.0   | 22        | 17.6%   |
| 32.01-64.0 | 2         | 1.6%    |
| 24.01-32.0 | 2         | 1.6%    |
| 2.01-3.0   | 1         | 0.8%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 59        | 46.09%  |
| 0.51-1.0   | 51        | 39.84%  |
| 2.01-3.0   | 9         | 7.03%   |
| 1.01-2.0   | 7         | 5.47%   |
| 4.01-8.0   | 1         | 0.78%   |
| 24.01-32.0 | 1         | 0.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 94        | 74.02%  |
| 2      | 26        | 20.47%  |
| 0      | 7         | 5.51%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 76        | 60.32%  |
| Yes       | 50        | 39.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 84.8%   |
| No        | 19        | 15.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 125       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 94        | 75.2%   |
| No        | 31        | 24.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 26        | 20.8%   |
| Germany      | 15        | 12%     |
| France       | 9         | 7.2%    |
| UK           | 7         | 5.6%    |
| Poland       | 6         | 4.8%    |
| Spain        | 4         | 3.2%    |
| Russia       | 4         | 3.2%    |
| Italy        | 4         | 3.2%    |
| India        | 4         | 3.2%    |
| Sweden       | 3         | 2.4%    |
| New Zealand  | 3         | 2.4%    |
| Switzerland  | 2         | 1.6%    |
| Slovenia     | 2         | 1.6%    |
| Slovakia     | 2         | 1.6%    |
| Portugal     | 2         | 1.6%    |
| Philippines  | 2         | 1.6%    |
| Japan        | 2         | 1.6%    |
| Indonesia    | 2         | 1.6%    |
| Hong Kong    | 2         | 1.6%    |
| Finland      | 2         | 1.6%    |
| China        | 2         | 1.6%    |
| Canada       | 2         | 1.6%    |
| Brazil       | 2         | 1.6%    |
| Belgium      | 2         | 1.6%    |
| Ukraine      | 1         | 0.8%    |
| Uganda       | 1         | 0.8%    |
| South Africa | 1         | 0.8%    |
| Serbia       | 1         | 0.8%    |
| Norway       | 1         | 0.8%    |
| Netherlands  | 1         | 0.8%    |
| Namibia      | 1         | 0.8%    |
| Malaysia     | 1         | 0.8%    |
| Kazakhstan   | 1         | 0.8%    |
| Hungary      | 1         | 0.8%    |
| Greece       | 1         | 0.8%    |
| Egypt        | 1         | 0.8%    |
| Bulgaria     | 1         | 0.8%    |
| Argentina    | 1         | 0.8%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Bedburg            | 6         | 4.58%   |
| Franconville       | 3         | 2.29%   |
| Chrusty            | 3         | 2.29%   |
| Bonn               | 3         | 2.29%   |
| Yokohama           | 2         | 1.53%   |
| Whittier           | 2         | 1.53%   |
| Wezeren            | 2         | 1.53%   |
| Stiring-Wendel     | 2         | 1.53%   |
| Rome               | 2         | 1.53%   |
| Paris              | 2         | 1.53%   |
| London             | 2         | 1.53%   |
| Jakarta            | 2         | 1.53%   |
| Giessen            | 2         | 1.53%   |
| Clemmons           | 2         | 1.53%   |
| Celje              | 2         | 1.53%   |
| Asnieres-sur-Seine | 2         | 1.53%   |
| Zurich             | 1         | 0.76%   |
| Yaroslavl          | 1         | 0.76%   |
| Wraysbury          | 1         | 0.76%   |
| Witbank            | 1         | 0.76%   |
| Winnipeg           | 1         | 0.76%   |
| Windhoek           | 1         | 0.76%   |
| Wenatchee          | 1         | 0.76%   |
| Valencia           | 1         | 0.76%   |
| Toronto            | 1         | 0.76%   |
| Taita              | 1         | 0.76%   |
| Staffanstorp       | 1         | 0.76%   |
| St Petersburg      | 1         | 0.76%   |
| St Austell         | 1         | 0.76%   |
| Sollentuna         | 1         | 0.76%   |
| Sofia              | 1         | 0.76%   |
| Santo Tomas        | 1         | 0.76%   |
| Salinas            | 1         | 0.76%   |
| Salem              | 1         | 0.76%   |
| Rochester          | 1         | 0.76%   |
| Richmond           | 1         | 0.76%   |
| Resistencia        | 1         | 0.76%   |
| Portland           | 1         | 0.76%   |
| Peoria             | 1         | 0.76%   |
| Oslo               | 1         | 0.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 36        | 47     | 25.17%  |
| WDC                 | 20        | 22     | 13.99%  |
| Seagate             | 14        | 17     | 9.79%   |
| Kingston            | 14        | 14     | 9.79%   |
| Toshiba             | 8         | 11     | 5.59%   |
| Crucial             | 8         | 9      | 5.59%   |
| SanDisk             | 7         | 7      | 4.9%    |
| SK hynix            | 5         | 7      | 3.5%    |
| Phison              | 3         | 4      | 2.1%    |
| Hitachi             | 3         | 3      | 2.1%    |
| PNY                 | 2         | 2      | 1.4%    |
| Patriot             | 2         | 2      | 1.4%    |
| Micron Technology   | 2         | 2      | 1.4%    |
| KingSpec            | 2         | 2      | 1.4%    |
| Intel               | 2         | 2      | 1.4%    |
| HGST                | 2         | 2      | 1.4%    |
| Goodram             | 2         | 2      | 1.4%    |
| Fujitsu             | 2         | 2      | 1.4%    |
| Star Drive          | 1         | 1      | 0.7%    |
| SSSTC               | 1         | 1      | 0.7%    |
| Plextor             | 1         | 1      | 0.7%    |
| Netac               | 1         | 1      | 0.7%    |
| LITEONIT            | 1         | 1      | 0.7%    |
| Hewlett-Packard     | 1         | 1      | 0.7%    |
| Gigabyte Technology | 1         | 1      | 0.7%    |
| Apple               | 1         | 1      | 0.7%    |
| A-DATA Technology   | 1         | 1      | 0.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 3         | 2.04%   |
| Samsung SSD 860 EVO 500GB            | 3         | 2.04%   |
| Samsung SSD 850 EVO 250GB            | 3         | 2.04%   |
| WDC WDS500G2B0A-00SM50 500GB         | 2         | 1.36%   |
| SK hynix HFM512GD3JX013N 512GB       | 2         | 1.36%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 1.36%   |
| Samsung SSD 860 QVO 1TB              | 2         | 1.36%   |
| Samsung PM981 NVMe 256GB             | 2         | 1.36%   |
| Samsung MZNTE128HMGR-000SO 128GB     | 2         | 1.36%   |
| Kingston SA400S37240G 240GB          | 2         | 1.36%   |
| Kingston SA400S37120G 120GB          | 2         | 1.36%   |
| Kingston RBUSNS8154P3512GJ 512GB     | 2         | 1.36%   |
| KingSpec Q-720 720GB                 | 2         | 1.36%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 0.68%   |
| WDC WDS120G2G0A-00JH30 120GB         | 1         | 0.68%   |
| WDC WDS100T2B0B-00YS70 1TB           | 1         | 0.68%   |
| WDC WDS100T1B0A-00H9H0 1TB           | 1         | 0.68%   |
| WDC WD7500BPVT-80HXZT3 752GB         | 1         | 0.68%   |
| WDC WD7500BPKX-80HPJT0 752GB         | 1         | 0.68%   |
| WDC WD6400BEVT-22A0RT0 640GB         | 1         | 0.68%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 1         | 0.68%   |
| WDC WD5000BPVT-00HXZT3 500GB         | 1         | 0.68%   |
| WDC WD3200LPVX-75V0TT0 320GB         | 1         | 0.68%   |
| WDC WD10SPZX-75Z10T3 1TB             | 1         | 0.68%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.68%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.68%   |
| WDC WD10JPVX-00JC3T0 1TB             | 1         | 0.68%   |
| WDC WD10JMVW-11AJGS1 1TB             | 1         | 0.68%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 0.68%   |
| WDC PC SN530 NVMe 256GB              | 1         | 0.68%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB | 1         | 0.68%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB | 1         | 0.68%   |
| Toshiba THNSF5256GPUK 256GB          | 1         | 0.68%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.68%   |
| Toshiba MQ01ACF032 320GB             | 1         | 0.68%   |
| Toshiba MQ01ABF050 500GB             | 1         | 0.68%   |
| Toshiba KXG50ZNV512G NVMe 512GB      | 1         | 0.68%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB  | 1         | 0.68%   |
| Toshiba KBG40ZNT512G MEMORY 512GB    | 1         | 0.68%   |
| Toshiba KBG30ZMV512G 512GB           | 1         | 0.68%   |

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
| Samsung Electronics | 22        | 31     | 30.14%  |
| Kingston            | 11        | 11     | 15.07%  |
| SanDisk             | 7         | 7      | 9.59%   |
| Crucial             | 7         | 8      | 9.59%   |
| WDC                 | 6         | 6      | 8.22%   |
| SK hynix            | 2         | 2      | 2.74%   |
| PNY                 | 2         | 2      | 2.74%   |
| Patriot             | 2         | 2      | 2.74%   |
| Micron Technology   | 2         | 2      | 2.74%   |
| KingSpec            | 2         | 2      | 2.74%   |
| Goodram             | 2         | 2      | 2.74%   |
| Toshiba             | 1         | 2      | 1.37%   |
| Plextor             | 1         | 1      | 1.37%   |
| Phison              | 1         | 1      | 1.37%   |
| Netac               | 1         | 1      | 1.37%   |
| LITEONIT            | 1         | 1      | 1.37%   |
| Intel               | 1         | 1      | 1.37%   |
| Apple               | 1         | 1      | 1.37%   |
| A-DATA Technology   | 1         | 1      | 1.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 65        | 84     | 48.87%  |
| NVMe | 34        | 42     | 25.56%  |
| HDD  | 34        | 40     | 25.56%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 94        | 124    | 73.44%  |
| NVMe | 34        | 42     | 26.56%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 68        | 80     | 68%     |
| 0.51-1.0   | 28        | 39     | 28%     |
| 1.01-2.0   | 4         | 5      | 4%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 44        | 33.33%  |
| 101-250    | 31        | 23.48%  |
| 251-500    | 19        | 14.39%  |
| 501-1000   | 13        | 9.85%   |
| 51-100     | 12        | 9.09%   |
| Unknown    | 10        | 7.58%   |
| 1001-2000  | 2         | 1.52%   |
| 21-50      | 1         | 0.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 114       | 85.71%  |
| Unknown | 10        | 7.52%   |
| 21-50   | 7         | 5.26%   |
| 101-250 | 1         | 0.75%   |
| 51-100  | 1         | 0.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD6400BEVT-22A0RT0 640GB                    | 1         | 1      | 6.67%   |
| WDC WD3200LPVX-75V0TT0 320GB                    | 1         | 1      | 6.67%   |
| Toshiba MQ01ACF032 320GB                        | 1         | 1      | 6.67%   |
| Seagate ST9250827AS 250GB                       | 1         | 1      | 6.67%   |
| Seagate ST500LT012-9WS142 500GB                 | 1         | 2      | 6.67%   |
| Seagate ST500LM021-1KJ152 500GB                 | 1         | 1      | 6.67%   |
| Seagate ST1000LM035-1RK172 1TB                  | 1         | 2      | 6.67%   |
| Samsung Electronics SSD 980 500GB               | 1         | 1      | 6.67%   |
| Samsung Electronics SSD 840 PRO Series 256GB    | 1         | 1      | 6.67%   |
| Samsung Electronics MZNTE128HMGR-000SO 128GB    | 1         | 1      | 6.67%   |
| Patriot Inferno 60GB SSD                        | 1         | 1      | 6.67%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB | 1         | 1      | 6.67%   |
| Intel SSDSC2BF180A5L 180GB                      | 1         | 1      | 6.67%   |
| Hitachi HTS543225L9A300 250GB                   | 1         | 1      | 6.67%   |
| HGST HTS721010A9E630 1TB                        | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 6      | 26.67%  |
| Samsung Electronics | 3         | 3      | 20%     |
| WDC                 | 2         | 2      | 13.33%  |
| Toshiba             | 1         | 1      | 6.67%   |
| Patriot             | 1         | 1      | 6.67%   |
| Micron Technology   | 1         | 1      | 6.67%   |
| Intel               | 1         | 1      | 6.67%   |
| Hitachi             | 1         | 1      | 6.67%   |
| HGST                | 1         | 1      | 6.67%   |

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
| HDD  | 9         | 11     | 60%     |
| SSD  | 5         | 5      | 33.33%  |
| NVMe | 1         | 1      | 6.67%   |

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
| Works   | 108       | 149    | 87.8%   |
| Malfunc | 15        | 17     | 12.2%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 93        | 65.96%  |
| Samsung Electronics            | 14        | 9.93%   |
| AMD                            | 11        | 7.8%    |
| SanDisk                        | 4         | 2.84%   |
| Phison Electronics             | 4         | 2.84%   |
| SK hynix                       | 3         | 2.13%   |
| Nvidia                         | 3         | 2.13%   |
| Kingston Technology Company    | 3         | 2.13%   |
| Toshiba                        | 2         | 1.42%   |
| Solid State Storage Technology | 1         | 0.71%   |
| Micron/Crucial Technology      | 1         | 0.71%   |
| KIOXIA                         | 1         | 0.71%   |
| Biwin Storage Technology       | 1         | 0.71%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 16        | 10.96%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 11        | 7.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 11        | 7.53%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 6.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 10        | 6.85%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 9         | 6.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 4.79%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 4.11%   |
| Samsung NVMe SSD Controller 980                                                  | 4         | 2.74%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 2.74%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 2.74%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 2.74%   |
| Unknown                                                                          | 4         | 2.74%   |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 2.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 2.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 2.05%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 2         | 1.37%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 1.37%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 2         | 1.37%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.37%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 1.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.37%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 1.37%   |
| Toshiba XG4 NVMe SSD Controller                                                  | 1         | 0.68%   |
| Toshiba BG3 NVMe SSD Controller                                                  | 1         | 0.68%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.68%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.68%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.68%   |
| SanDisk unknown                                                                  | 1         | 0.68%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.68%   |
| Samsung SM951 AHCI                                                               | 1         | 0.68%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.68%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.68%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.68%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 0.68%   |
| Intel SSD 660P Series                                                            | 1         | 0.68%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 95        | 65.97%  |
| NVMe | 33        | 22.92%  |
| RAID | 11        | 7.64%   |
| IDE  | 5         | 3.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 107       | 85.6%   |
| AMD    | 18        | 14.4%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz             | 5         | 4%      |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 3.2%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 3.2%    |
| Intel Core 2 Duo                              | 4         | 3.2%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 2.4%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 2.4%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 2.4%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 2.4%    |
| Intel Core i9-10980HK CPU @ 2.40GHz           | 2         | 1.6%    |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 1.6%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.6%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.6%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.6%    |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 1.6%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.6%    |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 1.6%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 1.6%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.6%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.6%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.6%    |
| Intel Core i5-2520M CPU @ 2.50GH              | 2         | 1.6%    |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 1.6%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 1.6%    |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz          | 2         | 1.6%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.6%    |
| AMD Ryzen 5 3450U with Radeon Vega Mobile Gfx | 2         | 1.6%    |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 2         | 1.6%    |
| Intel Pentium 3558U @ 1.70GHz                 | 1         | 0.8%    |
| Intel Genuine CPU                             | 1         | 0.8%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.8%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.8%    |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 0.8%    |
| Intel Core i7-4770HQ CPU @ 2.20GHz            | 1         | 0.8%    |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.8%    |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 0.8%    |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 0.8%    |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 0.8%    |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.8%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.8%    |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 0.8%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 44        | 35.2%   |
| Intel Core i7    | 33        | 26.4%   |
| Intel Core 2 Duo | 11        | 8.8%    |
| Intel Core i3    | 9         | 7.2%    |
| AMD Ryzen 5      | 6         | 4.8%    |
| AMD Ryzen 7      | 5         | 4%      |
| Intel Celeron    | 4         | 3.2%    |
| Other            | 2         | 1.6%    |
| Intel Core i9    | 2         | 1.6%    |
| AMD A6           | 2         | 1.6%    |
| AMD A4           | 2         | 1.6%    |
| Intel Pentium    | 1         | 0.8%    |
| Intel Genuine    | 1         | 0.8%    |
| Intel Core 2     | 1         | 0.8%    |
| AMD Ryzen 3      | 1         | 0.8%    |
| AMD Athlon       | 1         | 0.8%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 64        | 51.2%   |
| 4       | 35        | 28%     |
| 8       | 8         | 6.4%    |
| Unknown | 7         | 5.6%    |
| 6       | 6         | 4.8%    |
| 16      | 3         | 2.4%    |
| 12      | 2         | 1.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 122       | 97.6%   |
| 2      | 3         | 2.4%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 89        | 71.2%   |
| 1       | 29        | 23.2%   |
| Unknown | 7         | 5.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 24        | 19.2%   |
| IvyBridge   | 18        | 14.4%   |
| Haswell     | 14        | 11.2%   |
| SandyBridge | 11        | 8.8%    |
| Penryn      | 9         | 7.2%    |
| Zen+        | 7         | 5.6%    |
| Skylake     | 7         | 5.6%    |
| Broadwell   | 7         | 5.6%    |
| CometLake   | 4         | 3.2%    |
| Westmere    | 3         | 2.4%    |
| IceLake     | 3         | 2.4%    |
| Core        | 3         | 2.4%    |
| Unknown     | 3         | 2.4%    |
| Zen 3       | 2         | 1.6%    |
| Goldmont    | 2         | 1.6%    |
| Excavator   | 2         | 1.6%    |
| Zen 2       | 1         | 0.8%    |
| TigerLake   | 1         | 0.8%    |
| Silvermont  | 1         | 0.8%    |
| Puma        | 1         | 0.8%    |
| K10 Llano   | 1         | 0.8%    |
| K10         | 1         | 0.8%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 98        | 64.05%  |
| Nvidia | 31        | 20.26%  |
| AMD    | 24        | 15.69%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 15        | 9.49%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 11        | 6.96%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 11        | 6.96%   |
| Intel HD Graphics 5500                                                    | 7         | 4.43%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 7         | 4.43%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 6         | 3.8%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 6         | 3.8%    |
| Intel UHD Graphics 620                                                    | 5         | 3.16%   |
| Intel HD Graphics 620                                                     | 5         | 3.16%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 4         | 2.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 4         | 2.53%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 1.9%    |
| Nvidia C79 [GeForce 9400M]                                                | 3         | 1.9%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 3         | 1.9%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 3         | 1.9%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 1.9%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 3         | 1.9%    |
| Intel HD Graphics 530                                                     | 3         | 1.9%    |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 3         | 1.9%    |
| AMD Lucienne                                                              | 3         | 1.9%    |
| Nvidia GF108GLM [NVS 5200M]                                               | 2         | 1.27%   |
| Intel HD Graphics 500                                                     | 2         | 1.27%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 2         | 1.27%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 2         | 1.27%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 1.27%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.63%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.63%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                     | 1         | 0.63%   |
| Nvidia GT218M [NVS 3100M]                                                 | 1         | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.63%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                     | 1         | 0.63%   |
| Nvidia GM206M [GeForce GTX 965M]                                          | 1         | 0.63%   |
| Nvidia GM108M [GeForce MX130]                                             | 1         | 0.63%   |
| Nvidia GM107 [GeForce 940MX]                                              | 1         | 0.63%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 0.63%   |
| Nvidia GK107M [GeForce GTX 660M]                                          | 1         | 0.63%   |
| Nvidia GK107M [GeForce GT 650M]                                           | 1         | 0.63%   |
| Nvidia GK107GLM [Quadro K1000M]                                           | 1         | 0.63%   |
| Nvidia GK104M [GeForce GTX 870M]                                          | 1         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 64        | 51.2%   |
| Intel + Nvidia | 24        | 19.2%   |
| 1 x AMD        | 19        | 15.2%   |
| 2 x Intel      | 7         | 5.6%    |
| 1 x Nvidia     | 6         | 4.8%    |
| Intel + AMD    | 3         | 2.4%    |
| 2 x AMD        | 1         | 0.8%    |
| AMD + Nvidia   | 1         | 0.8%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 119       | 94.44%  |
| Proprietary | 7         | 5.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 111       | 87.4%   |
| 1.01-2.0   | 6         | 4.72%   |
| 0.01-0.5   | 5         | 3.94%   |
| 0.51-1.0   | 4         | 3.15%   |
| 3.01-4.0   | 1         | 0.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 22        | 18.97%  |
| Chimei Innolux          | 22        | 18.97%  |
| AU Optronics            | 22        | 18.97%  |
| Samsung Electronics     | 14        | 12.07%  |
| BOE                     | 10        | 8.62%   |
| Lenovo                  | 4         | 3.45%   |
| Philips                 | 3         | 2.59%   |
| PANDA                   | 2         | 1.72%   |
| Panasonic               | 2         | 1.72%   |
| InfoVision              | 2         | 1.72%   |
| Dell                    | 2         | 1.72%   |
| BenQ                    | 2         | 1.72%   |
| ___                     | 1         | 0.86%   |
| Iiyama                  | 1         | 0.86%   |
| IBM                     | 1         | 0.86%   |
| Hewlett-Packard         | 1         | 0.86%   |
| Goldstar                | 1         | 0.86%   |
| Fujitsu Siemens         | 1         | 0.86%   |
| CSO                     | 1         | 0.86%   |
| Chi Mei Optoelectronics | 1         | 0.86%   |
| Apple                   | 1         | 0.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 300x170mm 13.6-inch  | 2         | 1.71%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch  | 2         | 1.71%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 290x170mm 13.2-inch | 2         | 1.71%   |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch              | 2         | 1.71%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch          | 2         | 1.71%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch           | 2         | 1.71%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch           | 2         | 1.71%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch           | 2         | 1.71%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 2         | 1.71%   |
| LG Display LCD Monitor LGD01E9 1920x1080 350x190mm 15.7-inch          | 2         | 1.71%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch      | 2         | 1.71%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch      | 2         | 1.71%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 2         | 1.71%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch       | 2         | 1.71%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 290x160mm 13.0-inch        | 2         | 1.71%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch         | 2         | 1.71%   |
| ___ MY TV LED TV ___0101 1920x1080                                    | 1         | 0.85%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch  | 1         | 0.85%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 310x170mm 13.9-inch  | 1         | 0.85%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 1         | 0.85%   |
| Philips PHL BDM4065 PHL08E1 3840x2160 880x490mm 39.7-inch             | 1         | 0.85%   |
| PANDA LCD Monitor NCP0040 1920x1080 340x190mm 15.3-inch               | 1         | 0.85%   |
| PANDA LC133LF1L02 NCP0019 1920x1080 290x170mm 13.2-inch               | 1         | 0.85%   |
| LG Display LCD Monitor LGD066E 1920x1080 340x190mm 15.3-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD0558 1920x1080 310x170mm 13.9-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD0533 1920x1080 340x190mm 15.3-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD04D5 1920x1080 340x190mm 15.3-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD042D 1920x1080 290x170mm 13.2-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 1         | 0.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 47        | 41.96%  |
| 1366x768 (WXGA)    | 42        | 37.5%   |
| 1600x900 (HD+)     | 8         | 7.14%   |
| 2560x1440 (QHD)    | 3         | 2.68%   |
| 3840x2160 (4K)     | 2         | 1.79%   |
| 2880x1620          | 2         | 1.79%   |
| 1680x1050 (WSXGA+) | 2         | 1.79%   |
| 1280x800 (WXGA)    | 2         | 1.79%   |
| 3840x1600          | 1         | 0.89%   |
| 2880x1800          | 1         | 0.89%   |
| 1440x900 (WXGA+)   | 1         | 0.89%   |
| 1280x1024 (SXGA)   | 1         | 0.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 53        | 45.3%   |
| 13      | 29        | 24.79%  |
| 17      | 7         | 5.98%   |
| 12      | 6         | 5.13%   |
| 23      | 4         | 3.42%   |
| 14      | 4         | 3.42%   |
| 24      | 3         | 2.56%   |
| 11      | 3         | 2.56%   |
| 39      | 1         | 0.85%   |
| 37      | 1         | 0.85%   |
| 31      | 1         | 0.85%   |
| 27      | 1         | 0.85%   |
| 22      | 1         | 0.85%   |
| 21      | 1         | 0.85%   |
| 16      | 1         | 0.85%   |
| Unknown | 1         | 0.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 74        | 63.79%  |
| 201-300     | 21        | 18.1%   |
| 501-600     | 8         | 6.9%    |
| 351-400     | 7         | 6.03%   |
| 801-900     | 2         | 1.72%   |
| 401-500     | 2         | 1.72%   |
| 601-700     | 1         | 0.86%   |
| Unknown     | 1         | 0.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 94        | 88.68%  |
| 16/10 | 9         | 8.49%   |
| 5/4   | 1         | 0.94%   |
| 3/2   | 1         | 0.94%   |
| 21/9  | 1         | 0.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 42        | 35.9%   |
| 81-90          | 25        | 21.37%  |
| 101-110        | 11        | 9.4%    |
| 201-250        | 9         | 7.69%   |
| 71-80          | 8         | 6.84%   |
| 61-70          | 6         | 5.13%   |
| 121-130        | 6         | 5.13%   |
| 51-60          | 3         | 2.56%   |
| 501-1000       | 2         | 1.71%   |
| 351-500        | 1         | 0.85%   |
| 301-350        | 1         | 0.85%   |
| 141-150        | 1         | 0.85%   |
| 111-120        | 1         | 0.85%   |
| Unknown        | 1         | 0.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 49        | 42.61%  |
| 101-120       | 34        | 29.57%  |
| 51-100        | 17        | 14.78%  |
| 161-240       | 13        | 11.3%   |
| More than 240 | 1         | 0.87%   |
| Unknown       | 1         | 0.87%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 94        | 73.44%  |
| 0     | 20        | 15.63%  |
| 2     | 14        | 10.94%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 78        | 38.61%  |
| Realtek Semiconductor             | 47        | 23.27%  |
| Qualcomm Atheros                  | 32        | 15.84%  |
| Broadcom                          | 14        | 6.93%   |
| TP-Link                           | 5         | 2.48%   |
| Ericsson Business Mobile Networks | 4         | 1.98%   |
| Nvidia                            | 3         | 1.49%   |
| ASUSTek Computer                  | 3         | 1.49%   |
| Samsung Electronics               | 2         | 0.99%   |
| Ralink Technology                 | 2         | 0.99%   |
| Marvell Technology Group          | 2         | 0.99%   |
| Edimax Technology                 | 2         | 0.99%   |
| Xiaomi                            | 1         | 0.5%    |
| Sierra Wireless                   | 1         | 0.5%    |
| Ralink                            | 1         | 0.5%    |
| Qualcomm Atheros Communications   | 1         | 0.5%    |
| Qualcomm                          | 1         | 0.5%    |
| OnePlus Technology (Shenzhen)     | 1         | 0.5%    |
| Hewlett-Packard                   | 1         | 0.5%    |
| Generic                           | 1         | 0.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31        | 12.16%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 5.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 3.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 3.14%   |
| Intel Wireless 8265 / 8275                                        | 8         | 3.14%   |
| Intel Wireless 7265                                               | 8         | 3.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 3.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 2.75%   |
| Intel Wireless 8260                                               | 5         | 1.96%   |
| Intel Wireless 7260                                               | 5         | 1.96%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 1.96%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.57%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 1.57%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 1.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 1.18%   |
| Nvidia MCP79 Ethernet                                             | 3         | 1.18%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 1.18%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 1.18%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 0.78%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.78%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.78%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.78%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.78%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 2         | 0.78%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.78%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.78%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.78%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 0.78%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.78%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 74        | 53.24%  |
| Qualcomm Atheros                | 26        | 18.71%  |
| Realtek Semiconductor           | 16        | 11.51%  |
| Broadcom                        | 8         | 5.76%   |
| TP-Link                         | 5         | 3.6%    |
| ASUSTek Computer                | 3         | 2.16%   |
| Ralink Technology               | 2         | 1.44%   |
| Edimax Technology               | 2         | 1.44%   |
| Sierra Wireless                 | 1         | 0.72%   |
| Ralink                          | 1         | 0.72%   |
| Qualcomm Atheros Communications | 1         | 0.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8         | 5.71%   |
| Intel Wireless 8265 / 8275                                     | 8         | 5.71%   |
| Intel Wireless 7265                                            | 8         | 5.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 5.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 7         | 5%      |
| Intel Wireless 8260                                            | 5         | 3.57%   |
| Intel Wireless 7260                                            | 5         | 3.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 3.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 3.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 2.86%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 2.86%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 2.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 2.14%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 1.43%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 1.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.43%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.43%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 1.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.43%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 2         | 1.43%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.43%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.43%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 1.43%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.43%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2         | 1.43%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 1.43%   |
| TP-Link TP-Link High Power Wireless USB Adapter                | 1         | 0.71%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.71%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.71%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                  | 1         | 0.71%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 0.71%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.71%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.71%   |
| Realtek Realtek Bluetooth 4.2 Adapter                          | 1         | 0.71%   |
| Ralink RT5572 Wireless Adapter                                 | 1         | 0.71%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 42        | 38.89%  |
| Realtek Semiconductor         | 40        | 37.04%  |
| Qualcomm Atheros              | 9         | 8.33%   |
| Broadcom                      | 7         | 6.48%   |
| Nvidia                        | 3         | 2.78%   |
| Samsung Electronics           | 2         | 1.85%   |
| Marvell Technology Group      | 2         | 1.85%   |
| Xiaomi                        | 1         | 0.93%   |
| Qualcomm                      | 1         | 0.93%   |
| OnePlus Technology (Shenzhen) | 1         | 0.93%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31        | 28.44%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 13.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 8.26%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 4.59%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 4.59%   |
| Nvidia MCP79 Ethernet                                             | 3         | 2.75%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 2.75%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 2.75%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.83%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.83%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.83%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.83%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.83%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.83%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.92%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.92%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.92%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.92%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.92%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.92%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 0.92%   |
| OnePlus (Shenzhen) OnePlus RNDIS Control RNDIS Ethernet Data      | 1         | 0.92%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.92%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.92%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.92%   |
| Intel I225-K2                                                     | 1         | 0.92%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.92%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.92%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.92%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.92%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.92%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 0.92%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.92%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.92%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.92%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 126       | 52.72%  |
| Ethernet | 107       | 44.77%  |
| Modem    | 5         | 2.09%   |
| Unknown  | 1         | 0.42%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 88        | 49.72%  |
| Ethernet | 86        | 48.59%  |
| Modem    | 3         | 1.69%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 101       | 80.8%   |
| 1     | 23        | 18.4%   |
| 3     | 1         | 0.8%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 125       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 49        | 51.58%  |
| Realtek Semiconductor           | 8         | 8.42%   |
| Qualcomm Atheros Communications | 7         | 7.37%   |
| Lite-On Technology              | 7         | 7.37%   |
| Broadcom                        | 6         | 6.32%   |
| IMC Networks                    | 5         | 5.26%   |
| Dell                            | 5         | 5.26%   |
| Apple                           | 4         | 4.21%   |
| Alps Electric                   | 2         | 2.11%   |
| Toshiba                         | 1         | 1.05%   |
| ASUSTek Computer                | 1         | 1.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 24        | 25.26%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 10        | 10.53%  |
| Intel AX201 Bluetooth                                       | 6         | 6.32%   |
| Realtek  Bluetooth 4.2 Adapter                              | 4         | 4.21%   |
| Intel AX200 Bluetooth                                       | 4         | 4.21%   |
| Apple Bluetooth Host Controller                             | 4         | 4.21%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 3         | 3.16%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 3         | 3.16%   |
| Lite-On Atheros AR3012 Bluetooth                            | 3         | 3.16%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 3         | 3.16%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 3         | 3.16%   |
| Realtek Bluetooth Radio                                     | 2         | 2.11%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 2         | 2.11%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 2.11%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 2.11%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 2.11%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 2.11%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 2.11%   |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip             | 1         | 1.05%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 1.05%   |
| Realtek  Bluetooth Adapter                                  | 1         | 1.05%   |
| Lite-On Broadcom Bluetooth 4.0 USB                          | 1         | 1.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.05%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 1.05%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0          | 1         | 1.05%   |
| IMC Networks Bluetooth Module                               | 1         | 1.05%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 1.05%   |
| Dell DW375 Bluetooth Module                                 | 1         | 1.05%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 1.05%   |
| ASUS ASUS USB-BT500                                         | 1         | 1.05%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 1.05%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)             | 1         | 1.05%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 104       | 75.36%  |
| AMD                   | 20        | 14.49%  |
| Nvidia                | 9         | 6.52%   |
| RODE Microphones      | 1         | 0.72%   |
| Realtek Semiconductor | 1         | 0.72%   |
| Logitech              | 1         | 0.72%   |
| DSEA A/S              | 1         | 0.72%   |
| Cambridge Audio       | 1         | 0.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18        | 10.17%  |
| Intel Sunrise Point-LP HD Audio                                            | 14        | 7.91%   |
| AMD Family 17h/19h HD Audio Controller                                     | 13        | 7.34%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 6.21%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 6.21%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 6.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 3.95%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 3.95%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 3.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 3.95%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 3.39%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 3.39%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 2.82%   |
| Nvidia MCP79 High Definition Audio                                         | 3         | 1.69%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.69%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.69%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 1.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 1.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 1.13%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 1.13%   |
| AMD High Definition Audio Controller                                       | 2         | 1.13%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.13%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.13%   |
| RODE Microphones RDE NT-USB Mini                                           | 1         | 0.56%   |
| Realtek Semiconductor Realtek USB Audio                                    | 1         | 0.56%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.56%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.56%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.56%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.56%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.56%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.56%   |
| Logitech H600 [Wireless Headset]                                           | 1         | 0.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 0.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.56%   |
| Intel Crystal Well HD Audio Controller                                     | 1         | 0.56%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 49        | 30.63%  |
| SK hynix            | 45        | 28.13%  |
| Micron Technology   | 13        | 8.13%   |
| Kingston            | 11        | 6.88%   |
| Unknown             | 8         | 5%      |
| Crucial             | 7         | 4.38%   |
| Elpida              | 6         | 3.75%   |
| Corsair             | 3         | 1.88%   |
| Unknown (ABCD)      | 2         | 1.25%   |
| Transcend           | 2         | 1.25%   |
| Goodram             | 2         | 1.25%   |
| G.Skill             | 2         | 1.25%   |
| A-DATA Technology   | 2         | 1.25%   |
| Team                | 1         | 0.63%   |
| Smart               | 1         | 0.63%   |
| Ramaxel Technology  | 1         | 0.63%   |
| Neo Forza           | 1         | 0.63%   |
| Nanya Technology    | 1         | 0.63%   |
| Apacer              | 1         | 0.63%   |
| 09490000802C        | 1         | 0.63%   |
| Unknown             | 1         | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 5.49%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 4.27%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 3.05%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 3.05%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 5         | 3.05%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 2.44%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 4         | 2.44%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 2.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 3         | 1.83%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 1.22%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2133MT/s | 2         | 1.22%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s             | 2         | 1.22%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.22%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 1.22%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.22%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 2         | 1.22%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.22%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.22%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1.22%   |
| Micron RAM Module 8GB SODIMM DDR3 1600MT/s                       | 2         | 1.22%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1333MT/s            | 2         | 1.22%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 2         | 1.22%   |
| Unknown SODIMM 4GB SODIMM 800MT/s                                | 1         | 0.61%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 1         | 0.61%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 1         | 0.61%   |
| Unknown RAM GD2.09293S.001 16GB SODIMM DDR4 2400MT/s             | 1         | 0.61%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR 667MT/s                 | 1         | 0.61%   |
| Transcend RAM JM1333KSH-8G 8GB SODIMM DDR3 1333MT/s              | 1         | 0.61%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.61%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 1         | 0.61%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 0.61%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 0.61%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 1         | 0.61%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.61%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.61%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.61%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.61%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 66        | 51.16%  |
| DDR4    | 48        | 37.21%  |
| DDR2    | 5         | 3.88%   |
| LPDDR4  | 4         | 3.1%    |
| DDR     | 3         | 2.33%   |
| LPDDR3  | 2         | 1.55%   |
| Unknown | 1         | 0.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 123       | 96.09%  |
| Row Of Chips | 5         | 3.91%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 63        | 44.68%  |
| 8192  | 55        | 39.01%  |
| 2048  | 12        | 8.51%   |
| 16384 | 10        | 7.09%   |
| 1024  | 1         | 0.71%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 44        | 31.88%  |
| 2667    | 24        | 17.39%  |
| 2400    | 15        | 10.87%  |
| 1334    | 10        | 7.25%   |
| 3200    | 9         | 6.52%   |
| 2133    | 9         | 6.52%   |
| 1333    | 9         | 6.52%   |
| 800     | 6         | 4.35%   |
| Unknown | 4         | 2.9%    |
| 1067    | 3         | 2.17%   |
| 4266    | 2         | 1.45%   |
| 667     | 2         | 1.45%   |
| 1867    | 1         | 0.72%   |

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
| Chicony Electronics                    | 23        | 23.47%  |
| Realtek Semiconductor                  | 12        | 12.24%  |
| Microdia                               | 12        | 12.24%  |
| IMC Networks                           | 10        | 10.2%   |
| Acer                                   | 9         | 9.18%   |
| Quanta                                 | 6         | 6.12%   |
| Suyin                                  | 5         | 5.1%    |
| Sunplus Innovation Technology          | 4         | 4.08%   |
| Alcor Micro                            | 4         | 4.08%   |
| Silicon Motion                         | 2         | 2.04%   |
| Ricoh                                  | 2         | 2.04%   |
| Lite-On Technology                     | 2         | 2.04%   |
| Syntek                                 | 1         | 1.02%   |
| OmniVision Technologies                | 1         | 1.02%   |
| Luxvisions Innotech Limited            | 1         | 1.02%   |
| Logitech                               | 1         | 1.02%   |
| Lenovo                                 | 1         | 1.02%   |
| Importek                               | 1         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.02%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Acer Integrated Camera                        | 7         | 7.14%   |
| Microdia Integrated_Webcam_HD                 | 5         | 5.1%    |
| Microdia Integrated Webcam                    | 5         | 5.1%    |
| Chicony Integrated Camera                     | 5         | 5.1%    |
| Realtek Integrated_Webcam_HD                  | 4         | 4.08%   |
| IMC Networks Integrated Camera                | 3         | 3.06%   |
| Chicony USB2.0 HD UVC WebCam                  | 3         | 3.06%   |
| Chicony HD WebCam                             | 3         | 3.06%   |
| Chicony Chicony USB2.0 Camera                 | 3         | 3.06%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 2         | 2.04%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 2         | 2.04%   |
| Realtek Lenovo EasyCamera                     | 2         | 2.04%   |
| Realtek Integrated Webcam HD                  | 2         | 2.04%   |
| Realtek Front Camera                          | 2         | 2.04%   |
| Quanta VGA WebCam                             | 2         | 2.04%   |
| Quanta HP TrueVision HD Camera                | 2         | 2.04%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 2         | 2.04%   |
| IMC Networks USB2.0 HD UVC WebCam             | 2         | 2.04%   |
| Chicony Integrated Camera (1280x720@30)       | 2         | 2.04%   |
| Syntek Lenovo EasyCamera                      | 1         | 1.02%   |
| Suyin RGBIR Camera                            | 1         | 1.02%   |
| Suyin Integrated_Webcam_HD                    | 1         | 1.02%   |
| Suyin HD WebCam                               | 1         | 1.02%   |
| Sunplus MTD camera                            | 1         | 1.02%   |
| Sunplus Integrated_Webcam_HD                  | 1         | 1.02%   |
| Silicon Motion WebCam SC-13HDL11939N          | 1         | 1.02%   |
| Silicon Motion Realtek USB2.0 PC Camera       | 1         | 1.02%   |
| Ricoh USB2.0 Camera                           | 1         | 1.02%   |
| Ricoh HD Webcam                               | 1         | 1.02%   |
| Realtek USB Camera                            | 1         | 1.02%   |
| Realtek Realtek USB2.0 PC Camera              | 1         | 1.02%   |
| Quanta USB2.0 HD UVC WebCam                   | 1         | 1.02%   |
| Quanta HP Universal Camera                    | 1         | 1.02%   |
| OmniVision OV2640 Webcam                      | 1         | 1.02%   |
| Microdia Sonix Integrated Webcam              | 1         | 1.02%   |
| Microdia Laptop_Integrated_Webcam_HD          | 1         | 1.02%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 1.02%   |
| Logitech HD Pro Webcam C920                   | 1         | 1.02%   |
| Lite-On Integrated Camera                     | 1         | 1.02%   |
| Lite-On HP TrueVision HD Camera               | 1         | 1.02%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 31.58%  |
| Upek                       | 3         | 15.79%  |
| Synaptics                  | 2         | 10.53%  |
| STMicroelectronics         | 2         | 10.53%  |
| Shenzhen Goodix Technology | 1         | 5.26%   |
| Next Biometrics            | 1         | 5.26%   |
| LighTuning Technology      | 1         | 5.26%   |
| Focal-systems.Corp         | 1         | 5.26%   |
| Broadcom                   | 1         | 5.26%   |
| AuthenTec                  | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 3         | 15.79%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 10.53%  |
| STMicroelectronics Fingerprint Reader                                        | 2         | 10.53%  |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 5.26%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 5.26%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 1         | 5.26%   |
| Upek TCS5B Fingerprint sensor                                                | 1         | 5.26%   |
| Synaptics  WBDI                                                              | 1         | 5.26%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 5.26%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 5.26%   |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 5.26%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 1         | 5.26%   |
| Focal-systems.Corp FocalTech Fingerprint reader                              | 1         | 5.26%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.26%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 5.26%   |

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
| 2     | 45        | 34.09%  |
| 1     | 33        | 25%     |
| 3     | 27        | 20.45%  |
| 4     | 16        | 12.12%  |
| 0     | 9         | 6.82%   |
| 5     | 2         | 1.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 93        | 35.63%  |
| Bluetooth                | 65        | 24.9%   |
| Net/wireless             | 36        | 13.79%  |
| Card reader              | 30        | 11.49%  |
| Fingerprint reader       | 20        | 7.66%   |
| Firewire controller      | 9         | 3.45%   |
| Storage                  | 4         | 1.53%   |
| Network                  | 4         | 1.53%   |

