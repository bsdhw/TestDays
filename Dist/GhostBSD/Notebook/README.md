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

Total: 207

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | Inspiron 3180               | [cb769078b4](https://bsd-hardware.info/?probe=cb769078b4) | Jun 10, 2023 |
| Dell          | Inspiron 5593               | [8bedc249ea](https://bsd-hardware.info/?probe=8bedc249ea) | Jun 10, 2023 |
| Dell          | Inspiron 7548               | [c80bb80e8f](https://bsd-hardware.info/?probe=c80bb80e8f) | Jun 10, 2023 |
| Dell          | Inspiron 5559               | [fe5f99c4b0](https://bsd-hardware.info/?probe=fe5f99c4b0) | Jun 06, 2023 |
| Dell          | Inspiron 5559               | [330c08c388](https://bsd-hardware.info/?probe=330c08c388) | Jun 01, 2023 |
| Dell          | Inspiron 5559               | [53cf3cea13](https://bsd-hardware.info/?probe=53cf3cea13) | Jun 01, 2023 |
| Dell          | Inspiron 5559               | [23cad3f06e](https://bsd-hardware.info/?probe=23cad3f06e) | May 28, 2023 |
| Acer          | Nitro AN515-57              | [c39ea00de5](https://bsd-hardware.info/?probe=c39ea00de5) | May 25, 2023 |
| HP            | ProBook 455 G3              | [b6a6c91115](https://bsd-hardware.info/?probe=b6a6c91115) | May 21, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0S300     | [44d30cfcf6](https://bsd-hardware.info/?probe=44d30cfcf6) | May 21, 2023 |
| Dell          | Inspiron 5559               | [dca662fc41](https://bsd-hardware.info/?probe=dca662fc41) | May 16, 2023 |
| MSI           | GE62 6QC                    | [7c3fd3c9ca](https://bsd-hardware.info/?probe=7c3fd3c9ca) | May 08, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [95695f78c5](https://bsd-hardware.info/?probe=95695f78c5) | May 08, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [692b42afcd](https://bsd-hardware.info/?probe=692b42afcd) | Apr 08, 2023 |
| Dell          | Inspiron 5547               | [4f4f6e06d7](https://bsd-hardware.info/?probe=4f4f6e06d7) | Mar 29, 2023 |
| Unknown       | Unknown                     | [2a50573c9f](https://bsd-hardware.info/?probe=2a50573c9f) | Mar 29, 2023 |
| MouseCompu... | X5-aR5CEZAR-WA              | [b960dc3bde](https://bsd-hardware.info/?probe=b960dc3bde) | Mar 25, 2023 |
| MouseCompu... | X5-aR5CEZAR-WA              | [4cd1097c65](https://bsd-hardware.info/?probe=4cd1097c65) | Mar 24, 2023 |
| Dell          | Inspiron 5559               | [705ac0b37f](https://bsd-hardware.info/?probe=705ac0b37f) | Mar 18, 2023 |
| Dell          | Inspiron 5559               | [dcab531d1e](https://bsd-hardware.info/?probe=dcab531d1e) | Mar 18, 2023 |
| Star Labs     | StarBook                    | [80f6445f54](https://bsd-hardware.info/?probe=80f6445f54) | Mar 10, 2023 |
| Fujitsu       | FMVA532BSJ                  | [695e38d0ea](https://bsd-hardware.info/?probe=695e38d0ea) | Mar 10, 2023 |
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
| GhostBSD 20.04.02    | 58        | 36.25%  |
| GhostBSD 21.08.27    | 29        | 18.13%  |
| GhostBSD 22.01.12    | 13        | 8.13%   |
| GhostBSD 22.06.18    | 10        | 6.25%   |
| GhostBSD 23.02.02    | 6         | 3.75%   |
| GhostBSD 22.06.26    | 3         | 1.88%   |
| GhostBSD 23.06.05    | 2         | 1.25%   |
| GhostBSD 23.06.01    | 2         | 1.25%   |
| GhostBSD 23.05.22    | 2         | 1.25%   |
| GhostBSD 23.04.23    | 2         | 1.25%   |
| GhostBSD 23.03.17    | 2         | 1.25%   |
| GhostBSD 22.11.22    | 2         | 1.25%   |
| GhostBSD 22.11.02    | 2         | 1.25%   |
| GhostBSD 22.08.23    | 2         | 1.25%   |
| GhostBSD 22.08.06    | 2         | 1.25%   |
| GhostBSD 22.07.16    | 2         | 1.25%   |
| GhostBSD 23.05.18    | 1         | 0.63%   |
| GhostBSD 23.04.02    | 1         | 0.63%   |
| GhostBSD 23.01.13    | 1         | 0.63%   |
| GhostBSD 22.10.30    | 1         | 0.63%   |
| GhostBSD 22.09.16    | 1         | 0.63%   |
| GhostBSD 22.08.27    | 1         | 0.63%   |
| GhostBSD 22.07.31    | 1         | 0.63%   |
| GhostBSD 22.07.28    | 1         | 0.63%   |
| GhostBSD 22.07.13    | 1         | 0.63%   |
| GhostBSD 22.07.10    | 1         | 0.63%   |
| GhostBSD 22.06.20    | 1         | 0.63%   |
| GhostBSD 22.06.07    | 1         | 0.63%   |
| GhostBSD 22.05.13    | 1         | 0.63%   |
| GhostBSD 22.04.30    | 1         | 0.63%   |
| GhostBSD 22.04.22    | 1         | 0.63%   |
| GhostBSD 22.04.06    | 1         | 0.63%   |
| GhostBSD 21.12.29    | 1         | 0.63%   |
| GhostBSD 21.11.24    | 1         | 0.63%   |
| GhostBSD 20.07.14    | 1         | 0.63%   |
| GhostBSD 20.03.01    | 1         | 0.63%   |
| GhostBSD 12.2-STABLE | 1         | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| GhostBSD | 148       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 148       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| MATE         | 113       | 74.83%  |
| XFCE         | 26        | 17.22%  |
| KDE5         | 7         | 4.64%   |
| Cinnamon     | 2         | 1.32%   |
| helloDesktop | 1         | 0.66%   |
| GNOME        | 1         | 0.66%   |
| Console      | 1         | 0.66%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 146       | 98.65%  |
| Wayland | 1         | 0.68%   |
| Console | 1         | 0.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 145       | 97.97%  |
| SDDM    | 2         | 1.35%   |
| Console | 1         | 0.68%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 59        | 38.06%  |
| C       | 53        | 34.19%  |
| Unknown | 16        | 10.32%  |
| de_DE   | 7         | 4.52%   |
| pt_BR   | 4         | 2.58%   |
| en_GB   | 4         | 2.58%   |
| pl_PL   | 2         | 1.29%   |
| it_IT   | 2         | 1.29%   |
| es_ES   | 2         | 1.29%   |
| zh_CN   | 1         | 0.65%   |
| sv_SE   | 1         | 0.65%   |
| sk_SK   | 1         | 0.65%   |
| ru_RU   | 1         | 0.65%   |
| en_NZ   | 1         | 0.65%   |
| el_GR   | 1         | 0.65%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 117       | 79.05%  |
| BIOS | 31        | 20.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 140       | 92.11%  |
| Ufs  | 12        | 7.89%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 145       | 97.97%  |
| MBR  | 3         | 2.03%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 41        | 27.7%   |
| Dell                | 34        | 22.97%  |
| Hewlett-Packard     | 14        | 9.46%   |
| Acer                | 11        | 7.43%   |
| ASUSTek Computer    | 10        | 6.76%   |
| MSI                 | 5         | 3.38%   |
| Sony                | 4         | 2.7%    |
| Notebook            | 4         | 2.7%    |
| Apple               | 4         | 2.7%    |
| System76            | 3         | 2.03%   |
| Fujitsu             | 3         | 2.03%   |
| TUXEDO              | 2         | 1.35%   |
| Toshiba             | 2         | 1.35%   |
| Star Labs           | 2         | 1.35%   |
| Samsung Electronics | 2         | 1.35%   |
| Panasonic           | 1         | 0.68%   |
| MouseComputer       | 1         | 0.68%   |
| Jumper              | 1         | 0.68%   |
| HUAWEI              | 1         | 0.68%   |
| GPU Company         | 1         | 0.68%   |
| Alienware           | 1         | 0.68%   |
| Unknown             | 1         | 0.68%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Inspiron 3542                       | 3         | 2.03%   |
| MSI Modern 14 A10M                       | 2         | 1.35%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS       | 2         | 1.35%   |
| Lenovo ThinkPad T430s 2352CTO            | 2         | 1.35%   |
| Dell XPS 13 7390                         | 2         | 1.35%   |
| Dell Latitude E6420                      | 2         | 1.35%   |
| ASUS ZenBook UX325UA_UM325UA             | 2         | 1.35%   |
| Unknown                                  | 2         | 1.35%   |
| TUXEDO InfinityBook13V3                  | 1         | 0.68%   |
| TUXEDO Aura 15 Gen1                      | 1         | 0.68%   |
| Toshiba Satellite C855-1U4               | 1         | 0.68%   |
| Toshiba Satellite C855                   | 1         | 0.68%   |
| System76 Lemur Pro                       | 1         | 0.68%   |
| System76 Kudu                            | 1         | 0.68%   |
| System76 Gazelle                         | 1         | 0.68%   |
| Star Labs StarBook                       | 1         | 0.68%   |
| Star Labs LabTop                         | 1         | 0.68%   |
| Sony VPCCB17FG                           | 1         | 0.68%   |
| Sony VGN-SZ3VWP_X                        | 1         | 0.68%   |
| Sony SVP1322M1EBI                        | 1         | 0.68%   |
| Sony SVP13225SCBI                        | 1         | 0.68%   |
| Samsung 550P5C/550P7C                    | 1         | 0.68%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV | 1         | 0.68%   |
| Panasonic CF-19AHNC8FN                   | 1         | 0.68%   |
| Notebook N8xEJEK                         | 1         | 0.68%   |
| Notebook N85_N87,HJ,HJ1,HK1              | 1         | 0.68%   |
| Notebook N7x0WU                          | 1         | 0.68%   |
| Notebook N13xWU                          | 1         | 0.68%   |
| MSI GF63 Thin 10SCSR                     | 1         | 0.68%   |
| MSI GE75 Raider 10SFS                    | 1         | 0.68%   |
| MSI GE62 6QC                             | 1         | 0.68%   |
| MouseComputer X5-aR5CEZAR-WA             | 1         | 0.68%   |
| Lenovo Yoga 2 13 20344                   | 1         | 0.68%   |
| Lenovo ThinkPad X250 20CM003WMS          | 1         | 0.68%   |
| Lenovo ThinkPad X250 20CL001GZA          | 1         | 0.68%   |
| Lenovo ThinkPad X220 4290W42             | 1         | 0.68%   |
| Lenovo ThinkPad X220 42872VU             | 1         | 0.68%   |
| Lenovo ThinkPad X201 32492EU             | 1         | 0.68%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS6J30W | 1         | 0.68%   |
| Lenovo ThinkPad T590 20N40016CD          | 1         | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Lenovo ThinkPad              | 31        | 20.95%  |
| Dell Latitude                | 16        | 10.81%  |
| Dell Inspiron                | 13        | 8.78%   |
| Acer Aspire                  | 8         | 5.41%   |
| HP Laptop                    | 5         | 3.38%   |
| Lenovo IdeaPad               | 4         | 2.7%    |
| Lenovo Yoga                  | 3         | 2.03%   |
| HP EliteBook                 | 3         | 2.03%   |
| Dell XPS                     | 3         | 2.03%   |
| Toshiba Satellite            | 2         | 1.35%   |
| MSI Modern                   | 2         | 1.35%   |
| Dell Precision               | 2         | 1.35%   |
| ASUS ZenBook                 | 2         | 1.35%   |
| ASUS VivoBook                | 2         | 1.35%   |
| Unknown                      | 2         | 1.35%   |
| TUXEDO InfinityBook13V3      | 1         | 0.68%   |
| TUXEDO Aura                  | 1         | 0.68%   |
| System76 Lemur               | 1         | 0.68%   |
| System76 Kudu                | 1         | 0.68%   |
| System76 Gazelle             | 1         | 0.68%   |
| Star Labs StarBook           | 1         | 0.68%   |
| Star Labs LabTop             | 1         | 0.68%   |
| Sony VPCCB17FG               | 1         | 0.68%   |
| Sony VGN-SZ3VWP              | 1         | 0.68%   |
| Sony SVP1322M1EBI            | 1         | 0.68%   |
| Sony SVP13225SCBI            | 1         | 0.68%   |
| Samsung 550P5C               | 1         | 0.68%   |
| Samsung 3570R                | 1         | 0.68%   |
| Panasonic CF-19AHNC8FN       | 1         | 0.68%   |
| Notebook N8xEJEK             | 1         | 0.68%   |
| Notebook N85                 | 1         | 0.68%   |
| Notebook N7x0WU              | 1         | 0.68%   |
| Notebook N13xWU              | 1         | 0.68%   |
| MSI GF63                     | 1         | 0.68%   |
| MSI GE75                     | 1         | 0.68%   |
| MSI GE62                     | 1         | 0.68%   |
| MouseComputer X5-aR5CEZAR-WA | 1         | 0.68%   |
| Lenovo Legion                | 1         | 0.68%   |
| Lenovo G500s                 | 1         | 0.68%   |
| Lenovo Flex                  | 1         | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 23        | 15.54%  |
| 2013 | 17        | 11.49%  |
| 2021 | 15        | 10.14%  |
| 2018 | 11        | 7.43%   |
| 2014 | 11        | 7.43%   |
| 2016 | 9         | 6.08%   |
| 2011 | 9         | 6.08%   |
| 2022 | 8         | 5.41%   |
| 2019 | 8         | 5.41%   |
| 2015 | 8         | 5.41%   |
| 2012 | 8         | 5.41%   |
| 2009 | 7         | 4.73%   |
| 2017 | 6         | 4.05%   |
| 2010 | 4         | 2.7%    |
| 2008 | 3         | 2.03%   |
| 2007 | 1         | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 148       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 146       | 98.65%  |
| Yes  | 2         | 1.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 71        | 47.97%  |
| 16.01-24.0  | 42        | 28.38%  |
| 4.01-8.0    | 25        | 16.89%  |
| 24.01-32.0  | 4         | 2.7%    |
| 32.01-64.0  | 3         | 2.03%   |
| 64.01-256.0 | 2         | 1.35%   |
| 2.01-3.0    | 1         | 0.68%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 67        | 44.37%  |
| 0.51-1.0   | 59        | 39.07%  |
| 1.01-2.0   | 12        | 7.95%   |
| 2.01-3.0   | 11        | 7.28%   |
| 4.01-8.0   | 1         | 0.66%   |
| 24.01-32.0 | 1         | 0.66%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 114       | 76%     |
| 2      | 27        | 18%     |
| 0      | 8         | 5.33%   |
| 3      | 1         | 0.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 92        | 61.74%  |
| Yes       | 57        | 38.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 125       | 84.46%  |
| No        | 23        | 15.54%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 147       | 99.32%  |
| No        | 1         | 0.68%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 115       | 77.7%   |
| No        | 33        | 22.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 32        | 21.62%  |
| Germany      | 16        | 10.81%  |
| UK           | 9         | 6.08%   |
| France       | 9         | 6.08%   |
| Spain        | 7         | 4.73%   |
| Poland       | 6         | 4.05%   |
| Russia       | 5         | 3.38%   |
| Japan        | 4         | 2.7%    |
| Italy        | 4         | 2.7%    |
| Indonesia    | 4         | 2.7%    |
| India        | 4         | 2.7%    |
| Brazil       | 4         | 2.7%    |
| Switzerland  | 3         | 2.03%   |
| Sweden       | 3         | 2.03%   |
| New Zealand  | 3         | 2.03%   |
| Slovenia     | 2         | 1.35%   |
| Slovakia     | 2         | 1.35%   |
| Portugal     | 2         | 1.35%   |
| Philippines  | 2         | 1.35%   |
| Netherlands  | 2         | 1.35%   |
| Mauritius    | 2         | 1.35%   |
| Hong Kong    | 2         | 1.35%   |
| Finland      | 2         | 1.35%   |
| China        | 2         | 1.35%   |
| Canada       | 2         | 1.35%   |
| Belgium      | 2         | 1.35%   |
| Ukraine      | 1         | 0.68%   |
| Uganda       | 1         | 0.68%   |
| South Africa | 1         | 0.68%   |
| Serbia       | 1         | 0.68%   |
| Norway       | 1         | 0.68%   |
| Namibia      | 1         | 0.68%   |
| Malaysia     | 1         | 0.68%   |
| Kazakhstan   | 1         | 0.68%   |
| Hungary      | 1         | 0.68%   |
| Greece       | 1         | 0.68%   |
| Egypt        | 1         | 0.68%   |
| Bulgaria     | 1         | 0.68%   |
| Argentina    | 1         | 0.68%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Bedburg            | 6         | 3.9%    |
| Madrid             | 3         | 1.95%   |
| Jakarta            | 3         | 1.95%   |
| Indian Trail       | 3         | 1.95%   |
| Franconville       | 3         | 1.95%   |
| Chrusty            | 3         | 1.95%   |
| Bonn               | 3         | 1.95%   |
| Zurich             | 2         | 1.3%    |
| Yokohama           | 2         | 1.3%    |
| Whittier           | 2         | 1.3%    |
| Wezeren            | 2         | 1.3%    |
| Stiring-Wendel     | 2         | 1.3%    |
| Skiatook           | 2         | 1.3%    |
| Rome               | 2         | 1.3%    |
| Paris              | 2         | 1.3%    |
| London             | 2         | 1.3%    |
| Giessen            | 2         | 1.3%    |
| Clemmons           | 2         | 1.3%    |
| Chiyoda-ku         | 2         | 1.3%    |
| Celje              | 2         | 1.3%    |
| Asnieres-sur-Seine | 2         | 1.3%    |
| Yaroslavl          | 1         | 0.65%   |
| Wraysbury          | 1         | 0.65%   |
| Witbank            | 1         | 0.65%   |
| Winnipeg           | 1         | 0.65%   |
| Windhoek           | 1         | 0.65%   |
| Wenatchee          | 1         | 0.65%   |
| Valencia           | 1         | 0.65%   |
| Toronto            | 1         | 0.65%   |
| Tatsfield          | 1         | 0.65%   |
| Taita              | 1         | 0.65%   |
| Staffanstorp       | 1         | 0.65%   |
| St Petersburg      | 1         | 0.65%   |
| St Austell         | 1         | 0.65%   |
| Sollentuna         | 1         | 0.65%   |
| Sofia              | 1         | 0.65%   |
| Saratov            | 1         | 0.65%   |
| Sao Paulo          | 1         | 0.65%   |
| Santo Tomas        | 1         | 0.65%   |
| Salinas            | 1         | 0.65%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 41        | 53     | 24.26%  |
| WDC                 | 22        | 24     | 13.02%  |
| Kingston            | 19        | 19     | 11.24%  |
| Seagate             | 14        | 17     | 8.28%   |
| SK hynix            | 9         | 11     | 5.33%   |
| Crucial             | 9         | 11     | 5.33%   |
| Toshiba             | 8         | 11     | 4.73%   |
| SanDisk             | 8         | 8      | 4.73%   |
| A-DATA Technology   | 4         | 4      | 2.37%   |
| Phison              | 3         | 4      | 1.78%   |
| Intel               | 3         | 3      | 1.78%   |
| Hitachi             | 3         | 3      | 1.78%   |
| Star Drive          | 2         | 2      | 1.18%   |
| PNY                 | 2         | 2      | 1.18%   |
| Patriot             | 2         | 2      | 1.18%   |
| Micron Technology   | 2         | 2      | 1.18%   |
| KingSpec            | 2         | 2      | 1.18%   |
| HGST                | 2         | 2      | 1.18%   |
| Goodram             | 2         | 2      | 1.18%   |
| Fujitsu             | 2         | 2      | 1.18%   |
| XUM                 | 1         | 1      | 0.59%   |
| SSSTC               | 1         | 1      | 0.59%   |
| Silicon Motion      | 1         | 1      | 0.59%   |
| Plextor             | 1         | 1      | 0.59%   |
| Netac               | 1         | 1      | 0.59%   |
| LITEONIT            | 1         | 1      | 0.59%   |
| Hewlett-Packard     | 1         | 1      | 0.59%   |
| Gigabyte Technology | 1         | 1      | 0.59%   |
| Dell                | 1         | 1      | 0.59%   |
| Apple               | 1         | 1      | 0.59%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB            | 4         | 2.3%    |
| Seagate ST1000LM035-1RK172 1TB         | 3         | 1.72%   |
| Samsung SSD 860 EVO 500GB              | 3         | 1.72%   |
| Samsung SSD 850 EVO 250GB              | 3         | 1.72%   |
| WDC WDS500G2B0A-00SM50 500GB           | 2         | 1.15%   |
| WDC WD10JPVX-22JC3T0 1TB               | 2         | 1.15%   |
| Star Drive PCIe SSD 960GB              | 2         | 1.15%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB | 2         | 1.15%   |
| SK hynix HFM512GD3JX013N 512GB         | 2         | 1.15%   |
| Seagate ST1000LM049-2GH172 1TB         | 2         | 1.15%   |
| Samsung SSD 860 QVO 1TB                | 2         | 1.15%   |
| Samsung PM981 NVMe 256GB               | 2         | 1.15%   |
| Samsung MZNTE128HMGR-000SO 128GB       | 2         | 1.15%   |
| Kingston SV300S37A240G 240GB           | 2         | 1.15%   |
| Kingston SA400S37960G 960GB            | 2         | 1.15%   |
| Kingston SA400S37120G 120GB            | 2         | 1.15%   |
| Kingston RBUSNS8154P3512GJ 512GB       | 2         | 1.15%   |
| KingSpec Q-720 720GB                   | 2         | 1.15%   |
| XUM HX256GSSDSATA3 256GB               | 1         | 0.57%   |
| WDC WDS240G2G0A-00JH30 240GB           | 1         | 0.57%   |
| WDC WDS120G2G0A-00JH30 120GB           | 1         | 0.57%   |
| WDC WDS100T3X0C-00SJG0 1TB             | 1         | 0.57%   |
| WDC WDS100T2B0B-00YS70 1TB             | 1         | 0.57%   |
| WDC WDS100T1B0A-00H9H0 1TB             | 1         | 0.57%   |
| WDC WD7500BPVT-80HXZT3 752GB           | 1         | 0.57%   |
| WDC WD7500BPKX-80HPJT0 752GB           | 1         | 0.57%   |
| WDC WD6400BEVT-22A0RT0 640GB           | 1         | 0.57%   |
| WDC WD5000LPCX-24C6HT0 500GB           | 1         | 0.57%   |
| WDC WD5000BPVT-00HXZT3 500GB           | 1         | 0.57%   |
| WDC WD3200LPVX-75V0TT0 320GB           | 1         | 0.57%   |
| WDC WD10SPZX-75Z10T3 1TB               | 1         | 0.57%   |
| WDC WD10SPZX-21Z10T0 1TB               | 1         | 0.57%   |
| WDC WD10JPVX-00JC3T0 1TB               | 1         | 0.57%   |
| WDC WD10JMVW-11AJGS1 1TB               | 1         | 0.57%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB   | 1         | 0.57%   |
| WDC PC SN530 NVMe 256GB                | 1         | 0.57%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB   | 1         | 0.57%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB   | 1         | 0.57%   |
| Toshiba THNSF5256GPUK 256GB            | 1         | 0.57%   |
| Toshiba MQ04ABF100 1TB                 | 1         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 17     | 37.84%  |
| WDC                 | 12        | 13     | 32.43%  |
| Toshiba             | 3         | 3      | 8.11%   |
| Hitachi             | 3         | 3      | 8.11%   |
| HGST                | 2         | 2      | 5.41%   |
| Fujitsu             | 2         | 2      | 5.41%   |
| Samsung Electronics | 1         | 1      | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 35     | 29.55%  |
| Kingston            | 16        | 16     | 18.18%  |
| SanDisk             | 8         | 8      | 9.09%   |
| Crucial             | 8         | 10     | 9.09%   |
| WDC                 | 6         | 6      | 6.82%   |
| SK hynix            | 3         | 3      | 3.41%   |
| PNY                 | 2         | 2      | 2.27%   |
| Patriot             | 2         | 2      | 2.27%   |
| Micron Technology   | 2         | 2      | 2.27%   |
| KingSpec            | 2         | 2      | 2.27%   |
| Goodram             | 2         | 2      | 2.27%   |
| A-DATA Technology   | 2         | 2      | 2.27%   |
| XUM                 | 1         | 1      | 1.14%   |
| Toshiba             | 1         | 2      | 1.14%   |
| Plextor             | 1         | 1      | 1.14%   |
| Phison              | 1         | 1      | 1.14%   |
| Netac               | 1         | 1      | 1.14%   |
| LITEONIT            | 1         | 1      | 1.14%   |
| Intel               | 1         | 1      | 1.14%   |
| Dell                | 1         | 1      | 1.14%   |
| Apple               | 1         | 1      | 1.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 80        | 100    | 50.63%  |
| NVMe | 43        | 53     | 27.22%  |
| HDD  | 35        | 41     | 22.15%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 110       | 141    | 71.9%   |
| NVMe | 43        | 53     | 28.1%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 80        | 92     | 68.97%  |
| 0.51-1.0   | 31        | 43     | 26.72%  |
| 1.01-2.0   | 5         | 6      | 4.31%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 50        | 32.05%  |
| 101-250    | 38        | 24.36%  |
| 251-500    | 23        | 14.74%  |
| 501-1000   | 15        | 9.62%   |
| 51-100     | 14        | 8.97%   |
| Unknown    | 11        | 7.05%   |
| 21-50      | 3         | 1.92%   |
| 1001-2000  | 2         | 1.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 132       | 84.62%  |
| Unknown | 11        | 7.05%   |
| 21-50   | 10        | 6.41%   |
| 51-100  | 2         | 1.28%   |
| 101-250 | 1         | 0.64%   |

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
| Works   | 129       | 175    | 88.36%  |
| Malfunc | 17        | 19     | 11.64%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 109       | 64.12%  |
| Samsung Electronics            | 16        | 9.41%   |
| AMD                            | 13        | 7.65%   |
| SK hynix                       | 6         | 3.53%   |
| SanDisk                        | 5         | 2.94%   |
| Phison Electronics             | 5         | 2.94%   |
| Nvidia                         | 3         | 1.76%   |
| Kingston Technology Company    | 3         | 1.76%   |
| Toshiba                        | 2         | 1.18%   |
| ADATA Technology               | 2         | 1.18%   |
| Solid State Storage Technology | 1         | 0.59%   |
| Silicon Motion                 | 1         | 0.59%   |
| Micron/Crucial Technology      | 1         | 0.59%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.59%   |
| KIOXIA                         | 1         | 0.59%   |
| Biwin Storage Technology       | 1         | 0.59%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 18        | 10.29%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 14        | 8%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 11        | 6.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 11        | 6.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 6.29%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 6.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 4.57%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 7         | 4%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 2.86%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 4         | 2.29%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 2.29%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 2.29%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 2.29%   |
| Nvidia MCP79 AHCI Controller                                                   | 3         | 1.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 1.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 1.71%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 1.14%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 1.14%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.14%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 2         | 1.14%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 1.14%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.14%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 1.14%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.14%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 1.14%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.14%   |
| Unknown                                                                        | 2         | 1.14%   |
| Toshiba XG4 NVMe SSD Controller                                                | 1         | 0.57%   |
| Toshiba BG3 NVMe SSD Controller                                                | 1         | 0.57%   |
| Solid State Storage CL1                                                        | 1         | 0.57%   |
| SK hynix BC511                                                                 | 1         | 0.57%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.57%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 0.57%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.57%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.57%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.57%   |
| SanDisk unknown                                                                | 1         | 0.57%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 0.57%   |
| Samsung SM951 AHCI                                                             | 1         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 112       | 65.88%  |
| NVMe | 42        | 24.71%  |
| RAID | 11        | 6.47%   |
| IDE  | 5         | 2.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 125       | 84.46%  |
| AMD    | 23        | 15.54%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz             | 6         | 4.05%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 5         | 3.38%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 2.7%    |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 2.7%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 2.7%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 2.7%    |
| Intel Core 2 Duo                              | 4         | 2.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 2.03%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 2.03%   |
| Intel Core i9-10980HK CPU @ 2.40GHz           | 2         | 1.35%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 1.35%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.35%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 1.35%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.35%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 1.35%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.35%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 1.35%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 1.35%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.35%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.35%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.35%   |
| Intel Core i5-2520M CPU @ 2.50GH              | 2         | 1.35%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 1.35%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 1.35%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz          | 2         | 1.35%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.35%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.35%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.35%   |
| AMD Ryzen 5 3450U with Radeon Vega Mobile Gfx | 2         | 1.35%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 2         | 1.35%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.68%   |
| Intel Pentium 3558U @ 1.70GHz                 | 1         | 0.68%   |
| Intel Genuine CPU                             | 1         | 0.68%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.68%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.68%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 0.68%   |
| Intel Core i7-4770HQ CPU @ 2.20GHz            | 1         | 0.68%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.68%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 48        | 32.43%  |
| Intel Core i7    | 41        | 27.7%   |
| Intel Core i3    | 11        | 7.43%   |
| Intel Core 2 Duo | 11        | 7.43%   |
| AMD Ryzen 7      | 7         | 4.73%   |
| AMD Ryzen 5      | 7         | 4.73%   |
| Intel Celeron    | 5         | 3.38%   |
| Other            | 4         | 2.7%    |
| AMD A6           | 3         | 2.03%   |
| Intel Core i9    | 2         | 1.35%   |
| AMD A4           | 2         | 1.35%   |
| Intel Xeon       | 1         | 0.68%   |
| Intel Pentium    | 1         | 0.68%   |
| Intel Genuine    | 1         | 0.68%   |
| Intel Core 2     | 1         | 0.68%   |
| AMD Ryzen 3      | 1         | 0.68%   |
| AMD Athlon       | 1         | 0.68%   |
| AMD A10          | 1         | 0.68%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 74        | 50%     |
| 4       | 44        | 29.73%  |
| 8       | 9         | 6.08%   |
| 6       | 7         | 4.73%   |
| Unknown | 7         | 4.73%   |
| 16      | 4         | 2.7%    |
| 12      | 3         | 2.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 145       | 97.97%  |
| 2      | 3         | 2.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 106       | 71.62%  |
| 1       | 35        | 23.65%  |
| Unknown | 7         | 4.73%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 27        | 18.24%  |
| IvyBridge   | 19        | 12.84%  |
| Haswell     | 15        | 10.14%  |
| Skylake     | 13        | 8.78%   |
| SandyBridge | 12        | 8.11%   |
| Penryn      | 9         | 6.08%   |
| Broadwell   | 8         | 5.41%   |
| Zen+        | 7         | 4.73%   |
| Zen 3       | 4         | 2.7%    |
| Westmere    | 4         | 2.7%    |
| IceLake     | 4         | 2.7%    |
| Excavator   | 4         | 2.7%    |
| CometLake   | 4         | 2.7%    |
| Unknown     | 4         | 2.7%    |
| Core        | 3         | 2.03%   |
| Zen 2       | 2         | 1.35%   |
| TigerLake   | 2         | 1.35%   |
| Silvermont  | 2         | 1.35%   |
| Goldmont    | 2         | 1.35%   |
| Puma        | 1         | 0.68%   |
| K10 Llano   | 1         | 0.68%   |
| K10         | 1         | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 115       | 63.89%  |
| Nvidia | 34        | 18.89%  |
| AMD    | 31        | 17.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 16        | 8.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 12        | 6.49%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 12        | 6.49%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 8         | 4.32%   |
| Intel HD Graphics 5500                                                    | 8         | 4.32%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 7         | 3.78%   |
| Intel UHD Graphics 620                                                    | 6         | 3.24%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 6         | 3.24%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 6         | 3.24%   |
| Intel HD Graphics 620                                                     | 5         | 2.7%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 4         | 2.16%   |
| Intel HD Graphics 530                                                     | 4         | 2.16%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 4         | 2.16%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 1.62%   |
| Nvidia C79 [GeForce 9400M]                                                | 3         | 1.62%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 3         | 1.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 3         | 1.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 3         | 1.62%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 1.62%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 3         | 1.62%   |
| Intel Core Processor Integrated Graphics Controller                       | 3         | 1.62%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 3         | 1.62%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 3         | 1.62%   |
| AMD Lucienne                                                              | 3         | 1.62%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.08%   |
| Nvidia GF108GLM [NVS 5200M]                                               | 2         | 1.08%   |
| Intel HD Graphics 500                                                     | 2         | 1.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 2         | 1.08%   |
| AMD Renoir                                                                | 2         | 1.08%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.54%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                     | 1         | 0.54%   |
| Nvidia GT218M [NVS 3100M]                                                 | 1         | 0.54%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.54%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                     | 1         | 0.54%   |
| Nvidia GM206M [GeForce GTX 965M]                                          | 1         | 0.54%   |
| Nvidia GM108M [GeForce MX130]                                             | 1         | 0.54%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.54%   |
| Nvidia GM107GLM [Quadro M2000M]                                           | 1         | 0.54%   |
| Nvidia GM107 [GeForce 940MX]                                              | 1         | 0.54%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 78        | 52.35%  |
| Intel + Nvidia | 26        | 17.45%  |
| 1 x AMD        | 24        | 16.11%  |
| 2 x Intel      | 7         | 4.7%    |
| 1 x Nvidia     | 7         | 4.7%    |
| Intel + AMD    | 5         | 3.36%   |
| 2 x AMD        | 1         | 0.67%   |
| AMD + Nvidia   | 1         | 0.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 141       | 94.63%  |
| Proprietary | 8         | 5.37%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 129       | 85.43%  |
| 1.01-2.0   | 8         | 5.3%    |
| 0.01-0.5   | 8         | 5.3%    |
| 0.51-1.0   | 4         | 2.65%   |
| 3.01-4.0   | 2         | 1.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 27        | 20.93%  |
| AU Optronics            | 25        | 19.38%  |
| LG Display              | 23        | 17.83%  |
| Samsung Electronics     | 15        | 11.63%  |
| BOE                     | 10        | 7.75%   |
| Lenovo                  | 4         | 3.1%    |
| Philips                 | 3         | 2.33%   |
| InfoVision              | 3         | 2.33%   |
| PANDA                   | 2         | 1.55%   |
| Panasonic               | 2         | 1.55%   |
| Dell                    | 2         | 1.55%   |
| CSO                     | 2         | 1.55%   |
| BenQ                    | 2         | 1.55%   |
| ___                     | 1         | 0.78%   |
| Iiyama                  | 1         | 0.78%   |
| IBM                     | 1         | 0.78%   |
| Hewlett-Packard         | 1         | 0.78%   |
| Goldstar                | 1         | 0.78%   |
| Fujitsu Siemens         | 1         | 0.78%   |
| Chi Mei Optoelectronics | 1         | 0.78%   |
| Apple                   | 1         | 0.78%   |
| Unknown                 | 1         | 0.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 2         | 1.54%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch  | 2         | 1.54%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 290x170mm 13.2-inch | 2         | 1.54%   |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch              | 2         | 1.54%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch          | 2         | 1.54%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch           | 2         | 1.54%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch           | 2         | 1.54%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch           | 2         | 1.54%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 2         | 1.54%   |
| LG Display LCD Monitor LGD01E9 1920x1080 350x190mm 15.7-inch          | 2         | 1.54%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch      | 2         | 1.54%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch      | 2         | 1.54%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 2         | 1.54%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch       | 2         | 1.54%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch       | 2         | 1.54%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 340x190mm 15.3-inch        | 2         | 1.54%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 290x160mm 13.0-inch        | 2         | 1.54%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch         | 2         | 1.54%   |
| ___ MY TV LED TV ___0101 1920x1080                                    | 1         | 0.77%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch  | 1         | 0.77%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch  | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch  | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch  | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch  | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch  | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch  | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 340x190mm 15.3-inch | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 310x170mm 13.9-inch  | 1         | 0.77%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 1         | 0.77%   |
| Philips PHL BDM4065 PHL08E1 3840x2160 880x490mm 39.7-inch             | 1         | 0.77%   |
| PANDA LCD Monitor NCP0040 1920x1080 340x190mm 15.3-inch               | 1         | 0.77%   |
| PANDA LC133LF1L02 NCP0019 1920x1080 290x170mm 13.2-inch               | 1         | 0.77%   |
| LG Display LCD Monitor LGD066E 1920x1080 340x190mm 15.3-inch          | 1         | 0.77%   |
| LG Display LCD Monitor LGD0616 1920x1080 340x190mm 15.3-inch          | 1         | 0.77%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch          | 1         | 0.77%   |
| LG Display LCD Monitor LGD0558 1920x1080 310x170mm 13.9-inch          | 1         | 0.77%   |
| LG Display LCD Monitor LGD0533 1920x1080 340x190mm 15.3-inch          | 1         | 0.77%   |
| LG Display LCD Monitor LGD04D5 1920x1080 340x190mm 15.3-inch          | 1         | 0.77%   |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch           | 1         | 0.77%   |
| LG Display LCD Monitor LGD042D 1920x1080 290x170mm 13.2-inch          | 1         | 0.77%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 53        | 42.4%   |
| 1366x768 (WXGA)    | 46        | 36.8%   |
| 1600x900 (HD+)     | 8         | 6.4%    |
| 2560x1440 (QHD)    | 4         | 3.2%    |
| 3840x2160 (4K)     | 2         | 1.6%    |
| 2880x1800          | 2         | 1.6%    |
| 2880x1620          | 2         | 1.6%    |
| 1680x1050 (WSXGA+) | 2         | 1.6%    |
| 1280x800 (WXGA)    | 2         | 1.6%    |
| 9600x2160          | 1         | 0.8%    |
| 3840x1600          | 1         | 0.8%    |
| 1440x900 (WXGA+)   | 1         | 0.8%    |
| 1280x1024 (SXGA)   | 1         | 0.8%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 60        | 46.15%  |
| 13      | 31        | 23.85%  |
| 17      | 7         | 5.38%   |
| 12      | 6         | 4.62%   |
| 14      | 5         | 3.85%   |
| 11      | 5         | 3.85%   |
| 23      | 4         | 3.08%   |
| 24      | 3         | 2.31%   |
| Unknown | 2         | 1.54%   |
| 39      | 1         | 0.77%   |
| 37      | 1         | 0.77%   |
| 31      | 1         | 0.77%   |
| 27      | 1         | 0.77%   |
| 22      | 1         | 0.77%   |
| 21      | 1         | 0.77%   |
| 16      | 1         | 0.77%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 83        | 64.34%  |
| 201-300     | 24        | 18.6%   |
| 501-600     | 8         | 6.2%    |
| 351-400     | 7         | 5.43%   |
| 801-900     | 2         | 1.55%   |
| 401-500     | 2         | 1.55%   |
| Unknown     | 2         | 1.55%   |
| 601-700     | 1         | 0.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 105       | 88.24%  |
| 16/10   | 10        | 8.4%    |
| 5/4     | 1         | 0.84%   |
| 3/2     | 1         | 0.84%   |
| 21/9    | 1         | 0.84%   |
| Unknown | 1         | 0.84%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 49        | 37.69%  |
| 81-90          | 28        | 21.54%  |
| 101-110        | 11        | 8.46%   |
| 201-250        | 9         | 6.92%   |
| 71-80          | 8         | 6.15%   |
| 61-70          | 6         | 4.62%   |
| 121-130        | 6         | 4.62%   |
| 51-60          | 5         | 3.85%   |
| 501-1000       | 2         | 1.54%   |
| Unknown        | 2         | 1.54%   |
| 351-500        | 1         | 0.77%   |
| 301-350        | 1         | 0.77%   |
| 141-150        | 1         | 0.77%   |
| 111-120        | 1         | 0.77%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 57        | 44.53%  |
| 101-120       | 36        | 28.13%  |
| 51-100        | 17        | 13.28%  |
| 161-240       | 14        | 10.94%  |
| More than 240 | 2         | 1.56%   |
| Unknown       | 2         | 1.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 117       | 76.97%  |
| 0     | 21        | 13.82%  |
| 2     | 14        | 9.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 97        | 40.59%  |
| Realtek Semiconductor             | 59        | 24.69%  |
| Qualcomm Atheros                  | 34        | 14.23%  |
| Broadcom                          | 14        | 5.86%   |
| TP-Link                           | 5         | 2.09%   |
| Ericsson Business Mobile Networks | 4         | 1.67%   |
| Nvidia                            | 3         | 1.26%   |
| Edimax Technology                 | 3         | 1.26%   |
| ASUSTek Computer                  | 3         | 1.26%   |
| Sierra Wireless                   | 2         | 0.84%   |
| Samsung Electronics               | 2         | 0.84%   |
| Ralink Technology                 | 2         | 0.84%   |
| Marvell Technology Group          | 2         | 0.84%   |
| Xiaomi                            | 1         | 0.42%   |
| Ralink                            | 1         | 0.42%   |
| Qualcomm Atheros Communications   | 1         | 0.42%   |
| Qualcomm                          | 1         | 0.42%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.42%   |
| Huawei Technologies               | 1         | 0.42%   |
| Hewlett-Packard                   | 1         | 0.42%   |
| Generic                           | 1         | 0.42%   |
| Dell                              | 1         | 0.42%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38        | 12.62%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 5.32%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 3.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 2.99%   |
| Intel Wireless 8265 / 8275                                        | 9         | 2.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 2.99%   |
| Intel Wireless 8260                                               | 8         | 2.66%   |
| Intel Wireless 7265                                               | 8         | 2.66%   |
| Intel Wi-Fi 6 AX200                                               | 8         | 2.66%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 2.33%   |
| Intel Wireless 7260                                               | 6         | 1.99%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 1.99%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.66%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 1.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.33%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 1.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 1%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 1%      |
| Nvidia MCP79 Ethernet                                             | 3         | 1%      |
| Intel Wireless 3165                                               | 3         | 1%      |
| Intel Wireless 3160                                               | 3         | 1%      |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 1%      |
| Intel 82567LM Gigabit Network Connection                          | 3         | 1%      |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 0.66%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.66%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.66%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.66%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.66%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.66%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 2         | 0.66%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.66%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.66%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 93        | 56.71%  |
| Qualcomm Atheros                | 27        | 16.46%  |
| Realtek Semiconductor           | 19        | 11.59%  |
| Broadcom                        | 8         | 4.88%   |
| TP-Link                         | 5         | 3.05%   |
| Edimax Technology               | 3         | 1.83%   |
| ASUSTek Computer                | 3         | 1.83%   |
| Sierra Wireless                 | 2         | 1.22%   |
| Ralink Technology               | 2         | 1.22%   |
| Ralink                          | 1         | 0.61%   |
| Qualcomm Atheros Communications | 1         | 0.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 5.45%   |
| Intel Wireless 8265 / 8275                                     | 9         | 5.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 5.45%   |
| Intel Wireless 8260                                            | 8         | 4.85%   |
| Intel Wireless 7265                                            | 8         | 4.85%   |
| Intel Wi-Fi 6 AX200                                            | 8         | 4.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 7         | 4.24%   |
| Intel Wireless 7260                                            | 6         | 3.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 3.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 3.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 2.42%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 2.42%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 1.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.82%   |
| Intel Wireless 3165                                            | 3         | 1.82%   |
| Intel Wireless 3160                                            | 3         | 1.82%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 1.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.21%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.21%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 1.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.21%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 1.21%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 2         | 1.21%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.21%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.21%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.21%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 1.21%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 1.21%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2         | 1.21%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 1.21%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.61%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.61%   |
| TP-Link High Power Wireless USB Adapter                        | 1         | 0.61%   |
| Sierra Wireless EM7455                                         | 1         | 0.61%   |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 0.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.61%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 51        | 40.16%  |
| Intel                         | 49        | 38.58%  |
| Qualcomm Atheros              | 10        | 7.87%   |
| Broadcom                      | 7         | 5.51%   |
| Nvidia                        | 3         | 2.36%   |
| Samsung Electronics           | 2         | 1.57%   |
| Marvell Technology Group      | 2         | 1.57%   |
| Xiaomi                        | 1         | 0.79%   |
| Qualcomm                      | 1         | 0.79%   |
| OnePlus Technology (Shenzhen) | 1         | 0.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38        | 29.69%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 12.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 9.38%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 4.69%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 3.91%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 3.91%   |
| Nvidia MCP79 Ethernet                                             | 3         | 2.34%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 2.34%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 2.34%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.56%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.56%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.56%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.56%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.56%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.78%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.78%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.78%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.78%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.78%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.78%   |
| Qualcomm ALCATEL RNDIS Interface                                  | 1         | 0.78%   |
| OnePlus (Shenzhen) Android Remote NDIS Device                     | 1         | 0.78%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.78%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.78%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.78%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller               | 1         | 0.78%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.78%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.78%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.78%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.78%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 0.78%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.78%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.78%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 148       | 52.48%  |
| Ethernet | 126       | 44.68%  |
| Modem    | 6         | 2.13%   |
| Unknown  | 2         | 0.71%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 103       | 52.55%  |
| Ethernet | 90        | 45.92%  |
| Modem    | 3         | 1.53%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 119       | 80.41%  |
| 1     | 28        | 18.92%  |
| 3     | 1         | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 148       | 99.33%  |
| Yes  | 1         | 0.67%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 66        | 56.9%   |
| Realtek Semiconductor           | 10        | 8.62%   |
| Qualcomm Atheros Communications | 8         | 6.9%    |
| Lite-On Technology              | 7         | 6.03%   |
| Broadcom                        | 7         | 6.03%   |
| IMC Networks                    | 5         | 4.31%   |
| Dell                            | 5         | 4.31%   |
| Apple                           | 4         | 3.45%   |
| Alps Electric                   | 2         | 1.72%   |
| Toshiba                         | 1         | 0.86%   |
| ASUSTek Computer                | 1         | 0.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 34        | 29.31%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 11        | 9.48%   |
| Intel AX201 Bluetooth                                       | 8         | 6.9%    |
| Intel AX200 Bluetooth                                       | 7         | 6.03%   |
| Realtek Bluetooth Adapter                                   | 4         | 3.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 4         | 3.45%   |
| Apple Bluetooth Host Controller                             | 4         | 3.45%   |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 2.59%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 3         | 2.59%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 3         | 2.59%   |
| Lite-On Atheros AR3012 Bluetooth                            | 3         | 2.59%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 3         | 2.59%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 2         | 1.72%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 1.72%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 1.72%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 1.72%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 1.72%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.72%   |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip             | 1         | 0.86%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.86%   |
| Realtek Bluetooth 4.2 Adapter                               | 1         | 0.86%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 0.86%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.86%   |
| Lite-On Broadcom Bluetooth 4.0 USB                          | 1         | 0.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.86%   |
| Intel AX210 Bluetooth                                       | 1         | 0.86%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 0.86%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0          | 1         | 0.86%   |
| IMC Networks Bluetooth Module                               | 1         | 0.86%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 0.86%   |
| Dell DW375 Bluetooth Module                                 | 1         | 0.86%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 0.86%   |
| ASUS USB-BT500                                              | 1         | 0.86%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 0.86%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)             | 1         | 0.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 122       | 73.94%  |
| AMD                   | 25        | 15.15%  |
| Nvidia                | 11        | 6.67%   |
| Lenovo                | 2         | 1.21%   |
| RODE Microphones      | 1         | 0.61%   |
| Realtek Semiconductor | 1         | 0.61%   |
| Logitech              | 1         | 0.61%   |
| DSEA A/S              | 1         | 0.61%   |
| Cambridge Audio       | 1         | 0.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 20        | 9.48%   |
| Intel Sunrise Point-LP HD Audio                                            | 19        | 9%      |
| AMD Family 17h/19h HD Audio Controller                                     | 16        | 7.58%   |
| Intel Haswell-ULT HD Audio Controller                                      | 12        | 5.69%   |
| Intel 8 Series HD Audio Controller                                         | 12        | 5.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 5.21%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 4.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 3.79%   |
| Intel Broadwell-U Audio Controller                                         | 8         | 3.79%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 3.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 3.32%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 2.84%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 2.37%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 2.37%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.9%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1.9%    |
| Nvidia MCP79 High Definition Audio                                         | 3         | 1.42%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.42%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 1.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 1.42%   |
| AMD High Definition Audio Controller                                       | 3         | 1.42%   |
| Lenovo Lenovo USB-C Mini Dock                                              | 2         | 0.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 0.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 0.95%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 0.95%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.95%   |
| AMD FCH Azalia Controller                                                  | 2         | 0.95%   |
| RODE Microphones RDE NT-USB Mini                                           | 1         | 0.47%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.47%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.47%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.47%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.47%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.47%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.47%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.47%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.47%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 59        | 31.05%  |
| SK hynix            | 52        | 27.37%  |
| Micron Technology   | 17        | 8.95%   |
| Kingston            | 11        | 5.79%   |
| Crucial             | 10        | 5.26%   |
| Unknown             | 9         | 4.74%   |
| Elpida              | 6         | 3.16%   |
| Corsair             | 4         | 2.11%   |
| Unknown (ABCD)      | 2         | 1.05%   |
| Transcend           | 2         | 1.05%   |
| Ramaxel Technology  | 2         | 1.05%   |
| Goodram             | 2         | 1.05%   |
| G.Skill             | 2         | 1.05%   |
| A-DATA Technology   | 2         | 1.05%   |
| Unknown             | 2         | 1.05%   |
| Team                | 1         | 0.53%   |
| Smart Modular       | 1         | 0.53%   |
| Smart               | 1         | 0.53%   |
| Neo Forza           | 1         | 0.53%   |
| Nanya Technology    | 1         | 0.53%   |
| GSkill              | 1         | 0.53%   |
| Apacer              | 1         | 0.53%   |
| 09490000802C        | 1         | 0.53%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 4.59%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 3.57%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 2.55%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 2.55%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 5         | 2.55%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 2.04%   |
| Samsung RAM M471B5273DH0-CK0 8GB SODIMM DDR3 1600MT/s            | 4         | 2.04%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 2.04%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 2.04%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.53%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 3         | 1.53%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.53%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 1.02%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2133MT/s | 2         | 1.02%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s             | 2         | 1.02%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 1.02%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.02%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 2         | 1.02%   |
| Samsung RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 1.02%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.02%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1.02%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 2         | 1.02%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 1.02%   |
| Micron RAM Module 8GB SODIMM DDR3 1600MT/s                       | 2         | 1.02%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 1.02%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 2         | 1.02%   |
| Unknown                                                          | 2         | 1.02%   |
| Unknown SODIMM 4GB SODIMM 800MT/s                                | 1         | 0.51%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.51%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.51%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 1         | 0.51%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 1         | 0.51%   |
| Unknown RAM GD2.09293S.001 16GB SODIMM DDR4 2400MT/s             | 1         | 0.51%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR 667MT/s                 | 1         | 0.51%   |
| Transcend RAM JM1333KSH-8G 8GB SODIMM DDR3 1333MT/s              | 1         | 0.51%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.51%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 1         | 0.51%   |
| Smart Modular RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s    | 1         | 0.51%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 76        | 50%     |
| DDR4    | 59        | 38.82%  |
| DDR2    | 5         | 3.29%   |
| LPDDR4  | 4         | 2.63%   |
| LPDDR3  | 3         | 1.97%   |
| DDR     | 3         | 1.97%   |
| Unknown | 2         | 1.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 144       | 95.36%  |
| Row Of Chips | 7         | 4.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 72        | 42.6%   |
| 4096  | 68        | 40.24%  |
| 16384 | 13        | 7.69%   |
| 2048  | 13        | 7.69%   |
| 32768 | 2         | 1.18%   |
| 1024  | 1         | 0.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 53        | 32.72%  |
| 2667    | 27        | 16.67%  |
| 2400    | 16        | 9.88%   |
| 3200    | 14        | 8.64%   |
| 1334    | 12        | 7.41%   |
| 2133    | 11        | 6.79%   |
| 1333    | 9         | 5.56%   |
| 800     | 6         | 3.7%    |
| Unknown | 4         | 2.47%   |
| 1067    | 3         | 1.85%   |
| 667     | 3         | 1.85%   |
| 4266    | 2         | 1.23%   |
| 1867    | 1         | 0.62%   |
| 1200    | 1         | 0.62%   |

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
| Chicony Electronics                    | 30        | 25.86%  |
| Realtek Semiconductor                  | 13        | 11.21%  |
| Microdia                               | 13        | 11.21%  |
| IMC Networks                           | 12        | 10.34%  |
| Bison Electronics                      | 11        | 9.48%   |
| Sunplus Innovation Technology          | 7         | 6.03%   |
| Suyin                                  | 6         | 5.17%   |
| Quanta                                 | 6         | 5.17%   |
| Alcor Micro                            | 4         | 3.45%   |
| Silicon Motion                         | 2         | 1.72%   |
| Ricoh                                  | 2         | 1.72%   |
| Lite-On Technology                     | 2         | 1.72%   |
| Syntek                                 | 1         | 0.86%   |
| OmniVision Technologies                | 1         | 0.86%   |
| Luxvisions Innotech Limited            | 1         | 0.86%   |
| Logitech                               | 1         | 0.86%   |
| Lenovo                                 | 1         | 0.86%   |
| Intel                                  | 1         | 0.86%   |
| Importek                               | 1         | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 0.86%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 9         | 7.76%   |
| Bison Integrated Camera                  | 7         | 6.03%   |
| Microdia Integrated_Webcam_HD            | 5         | 4.31%   |
| Microdia Integrated Webcam               | 5         | 4.31%   |
| IMC Networks Integrated Camera           | 5         | 4.31%   |
| Sunplus Integrated_Webcam_HD             | 3         | 2.59%   |
| Realtek Integrated_Webcam_HD             | 3         | 2.59%   |
| Chicony USB2.0 HD UVC WebCam             | 3         | 2.59%   |
| Chicony HD WebCam                        | 3         | 2.59%   |
| Suyin Integrated_Webcam_HD               | 2         | 1.72%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 2         | 1.72%   |
| Sunplus Laptop_Integrated_Webcam_FHD     | 2         | 1.72%   |
| Realtek Lenovo EasyCamera                | 2         | 1.72%   |
| Realtek Integrated Webcam HD             | 2         | 1.72%   |
| Realtek Front Camera                     | 2         | 1.72%   |
| Quanta VGA WebCam                        | 2         | 1.72%   |
| Quanta HP TrueVision HD Camera           | 2         | 1.72%   |
| IMC Networks Realtek PC Camera           | 2         | 1.72%   |
| IMC Networks Realtek DMFT RGB            | 2         | 1.72%   |
| Chicony Realtek DMFT RGB                 | 2         | 1.72%   |
| Chicony Integrated Camera (1280x720@30)  | 2         | 1.72%   |
| Bison ThinkPad P50 Integrated Camera     | 2         | 1.72%   |
| Syntek Lenovo EasyCamera                 | 1         | 0.86%   |
| Suyin RGBIR Camera                       | 1         | 0.86%   |
| Suyin HD WebCam                          | 1         | 0.86%   |
| Sunplus SPCA2085 PC Camera               | 1         | 0.86%   |
| Sunplus MTD camera                       | 1         | 0.86%   |
| Silicon Motion WebCam SC-13HDL11939N     | 1         | 0.86%   |
| Silicon Motion Realtek USB 2.0 PC Camera | 1         | 0.86%   |
| Ricoh USB2.0 Camera                      | 1         | 0.86%   |
| Ricoh HD Webcam                          | 1         | 0.86%   |
| Realtek USB Camera                       | 1         | 0.86%   |
| Realtek USB 2.0 Webcam                   | 1         | 0.86%   |
| Realtek USB 2.0 PC Camera                | 1         | 0.86%   |
| Realtek Dell EasyCamera                  | 1         | 0.86%   |
| Quanta Realtek PC Camera                 | 1         | 0.86%   |
| Quanta HP Universal Camera               | 1         | 0.86%   |
| OmniVision OV2640 Webcam                 | 1         | 0.86%   |
| Microdia Webcam Vitade AF                | 1         | 0.86%   |
| Microdia Sonix Integrated Webcam         | 1         | 0.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 36%     |
| Upek                       | 3         | 12%     |
| Synaptics                  | 3         | 12%     |
| STMicroelectronics         | 2         | 8%      |
| Shenzhen Goodix Technology | 2         | 8%      |
| Next Biometrics            | 1         | 4%      |
| LighTuning Technology      | 1         | 4%      |
| FocalTech Systems          | 1         | 4%      |
| Elan Microelectronics      | 1         | 4%      |
| Broadcom                   | 1         | 4%      |
| AuthenTec                  | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 5         | 20%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 8%      |
| STMicroelectronics Fingerprint Reader                                        | 2         | 8%      |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 8%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 4%      |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 4%      |
| Validity Sensors Synaptics WBDI                                              | 1         | 4%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 1         | 4%      |
| Upek TCS5B Fingerprint sensor                                                | 1         | 4%      |
| Synaptics WBDI                                                               | 1         | 4%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 4%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 4%      |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 4%      |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 1         | 4%      |
| FocalTech Systems Fingerprint Reader                                         | 1         | 4%      |
| Elan Fingerprint Sensor                                                      | 1         | 4%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4%      |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 4%      |

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
| 2     | 53        | 33.97%  |
| 1     | 37        | 23.72%  |
| 3     | 31        | 19.87%  |
| 4     | 20        | 12.82%  |
| 0     | 11        | 7.05%   |
| 5     | 4         | 2.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 110       | 35.37%  |
| Bluetooth                | 79        | 25.4%   |
| Net/wireless             | 39        | 12.54%  |
| Card reader              | 36        | 11.58%  |
| Fingerprint reader       | 26        | 8.36%   |
| Firewire controller      | 9         | 2.89%   |
| Network                  | 7         | 2.25%   |
| Storage                  | 4         | 1.29%   |
| Net/ethernet             | 1         | 0.32%   |

