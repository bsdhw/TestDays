GhostBSD - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for GhostBSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/GhostBSD/Desktop/README.md) and [notebooks](/Dist/GhostBSD/Notebook/README.md).

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

Total: 279

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| HP            | Laptop 14s-fq0xxx           | Notebook    | [920a2fe2e9](https://bsd-hardware.info/?probe=920a2fe2e9) | Nov 30, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [9618eb0cbe](https://bsd-hardware.info/?probe=9618eb0cbe) | Nov 29, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [39ece5deaf](https://bsd-hardware.info/?probe=39ece5deaf) | Nov 27, 2022 |
| MSI           | X299 PRO                    | Desktop     | [d615157be7](https://bsd-hardware.info/?probe=d615157be7) | Nov 16, 2022 |
| Acer          | Aspire 5251                 | Notebook    | [c9eb0051ed](https://bsd-hardware.info/?probe=c9eb0051ed) | Nov 16, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [45316a9769](https://bsd-hardware.info/?probe=45316a9769) | Nov 07, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [72d95a4938](https://bsd-hardware.info/?probe=72d95a4938) | Nov 03, 2022 |
| Dell          | Latitude 5591               | Notebook    | [40957fa567](https://bsd-hardware.info/?probe=40957fa567) | Oct 31, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [51ec4ce710](https://bsd-hardware.info/?probe=51ec4ce710) | Oct 24, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [3d62c50607](https://bsd-hardware.info/?probe=3d62c50607) | Oct 20, 2022 |
| Dell          | Latitude 5591               | Notebook    | [04f53f51c8](https://bsd-hardware.info/?probe=04f53f51c8) | Oct 12, 2022 |
| ASUSTek       | P8Z68-V                     | Desktop     | [6674bbf7f3](https://bsd-hardware.info/?probe=6674bbf7f3) | Oct 11, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [a773a82ff4](https://bsd-hardware.info/?probe=a773a82ff4) | Oct 11, 2022 |
| Dell          | Latitude 5591               | Notebook    | [eda94b6c48](https://bsd-hardware.info/?probe=eda94b6c48) | Oct 11, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [8ad31cc470](https://bsd-hardware.info/?probe=8ad31cc470) | Sep 29, 2022 |
| Dell          | XPS M1330                   | Notebook    | [d84548dd9b](https://bsd-hardware.info/?probe=d84548dd9b) | Sep 11, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [4f31f81571](https://bsd-hardware.info/?probe=4f31f81571) | Sep 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [fc259fcf3e](https://bsd-hardware.info/?probe=fc259fcf3e) | Aug 30, 2022 |
| HP            | Unknown                     | Notebook    | [7bd69ee984](https://bsd-hardware.info/?probe=7bd69ee984) | Aug 29, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [0d7d7288c0](https://bsd-hardware.info/?probe=0d7d7288c0) | Aug 27, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [0a90c3c566](https://bsd-hardware.info/?probe=0a90c3c566) | Aug 27, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [692e2f0837](https://bsd-hardware.info/?probe=692e2f0837) | Aug 20, 2022 |
| Lenovo        | ThinkPad 11e 4th Gen 20H... | Notebook    | [ba1ea734b1](https://bsd-hardware.info/?probe=ba1ea734b1) | Aug 19, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [c9bda4b49d](https://bsd-hardware.info/?probe=c9bda4b49d) | Aug 14, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [e1a29d8008](https://bsd-hardware.info/?probe=e1a29d8008) | Aug 14, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [cdc6bc6ef8](https://bsd-hardware.info/?probe=cdc6bc6ef8) | Aug 03, 2022 |
| Acer          | Aspire E5-521G              | Notebook    | [dcc5d3116f](https://bsd-hardware.info/?probe=dcc5d3116f) | Jul 29, 2022 |
| Lenovo        | IdeaPad Y580 20132          | Notebook    | [3df3bd2f62](https://bsd-hardware.info/?probe=3df3bd2f62) | Jul 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [52cc45aba9](https://bsd-hardware.info/?probe=52cc45aba9) | Jul 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [3182740b56](https://bsd-hardware.info/?probe=3182740b56) | Jul 21, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [15c5d9fdd9](https://bsd-hardware.info/?probe=15c5d9fdd9) | Jul 17, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [ead2595782](https://bsd-hardware.info/?probe=ead2595782) | Jul 17, 2022 |
| MSI           | B85M-E45                    | Desktop     | [80f2d74d1a](https://bsd-hardware.info/?probe=80f2d74d1a) | Jul 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [9771cb16c0](https://bsd-hardware.info/?probe=9771cb16c0) | Jul 15, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [3ee4c986b4](https://bsd-hardware.info/?probe=3ee4c986b4) | Jul 15, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [d9efb0425b](https://bsd-hardware.info/?probe=d9efb0425b) | Jul 15, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [6e85a064f0](https://bsd-hardware.info/?probe=6e85a064f0) | Jul 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1e8b0433e8](https://bsd-hardware.info/?probe=1e8b0433e8) | Jul 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [85a49cb7be](https://bsd-hardware.info/?probe=85a49cb7be) | Jul 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b09ba0c799](https://bsd-hardware.info/?probe=b09ba0c799) | Jul 12, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [4c74cdfb76](https://bsd-hardware.info/?probe=4c74cdfb76) | Jul 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [6edc61f549](https://bsd-hardware.info/?probe=6edc61f549) | Jul 10, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [0434c94fad](https://bsd-hardware.info/?probe=0434c94fad) | Jul 09, 2022 |
| Lenovo        | ThinkPad T470 20HD000MUK    | Notebook    | [866724656a](https://bsd-hardware.info/?probe=866724656a) | Jul 06, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [5d668f86de](https://bsd-hardware.info/?probe=5d668f86de) | Jul 06, 2022 |
| Star Labs     | LabTop                      | Notebook    | [390c4c4d55](https://bsd-hardware.info/?probe=390c4c4d55) | Jul 03, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [3c2e2da462](https://bsd-hardware.info/?probe=3c2e2da462) | Jul 02, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [b870cd3698](https://bsd-hardware.info/?probe=b870cd3698) | Jul 01, 2022 |
| System76      | Gazelle                     | Notebook    | [7e2dbb0a5b](https://bsd-hardware.info/?probe=7e2dbb0a5b) | Jun 28, 2022 |
| System76      | Gazelle                     | Notebook    | [8cb2a30786](https://bsd-hardware.info/?probe=8cb2a30786) | Jun 28, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [bb3de13b1a](https://bsd-hardware.info/?probe=bb3de13b1a) | Jun 23, 2022 |
| ASUSTek       | X202E                       | Notebook    | [bdbe613858](https://bsd-hardware.info/?probe=bdbe613858) | Jun 22, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [a03ff6ad9e](https://bsd-hardware.info/?probe=a03ff6ad9e) | Jun 10, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [03cb6c6c7f](https://bsd-hardware.info/?probe=03cb6c6c7f) | Jun 09, 2022 |
| Dell          | Latitude 7490               | Notebook    | [22224f46f4](https://bsd-hardware.info/?probe=22224f46f4) | Jun 02, 2022 |
| Dell          | 0M3F6C A01                  | Desktop     | [21d45bc75d](https://bsd-hardware.info/?probe=21d45bc75d) | May 23, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [e9524e612d](https://bsd-hardware.info/?probe=e9524e612d) | May 22, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [115de395dd](https://bsd-hardware.info/?probe=115de395dd) | May 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [d2334d7be3](https://bsd-hardware.info/?probe=d2334d7be3) | May 14, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [6dce802641](https://bsd-hardware.info/?probe=6dce802641) | May 10, 2022 |
| Gigabyte      | AX370-Gaming 3-CF           | Desktop     | [62ab2bc823](https://bsd-hardware.info/?probe=62ab2bc823) | May 07, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0d5b872ec1](https://bsd-hardware.info/?probe=0d5b872ec1) | May 02, 2022 |
| Dell          | Latitude 7490               | Notebook    | [03c97fe4d9](https://bsd-hardware.info/?probe=03c97fe4d9) | May 02, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [3f170bdee6](https://bsd-hardware.info/?probe=3f170bdee6) | May 01, 2022 |
| Dell          | Precision 7730              | Notebook    | [bdb3e3d4ce](https://bsd-hardware.info/?probe=bdb3e3d4ce) | Apr 30, 2022 |
| Dell          | Latitude 7490               | Notebook    | [1586880dd7](https://bsd-hardware.info/?probe=1586880dd7) | Apr 30, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [ece6d63cfb](https://bsd-hardware.info/?probe=ece6d63cfb) | Apr 25, 2022 |
| Dell          | Latitude E5450              | Notebook    | [ca5eb083f9](https://bsd-hardware.info/?probe=ca5eb083f9) | Apr 16, 2022 |
| Dell          | 0DXJD9 A01                  | Desktop     | [4023d86091](https://bsd-hardware.info/?probe=4023d86091) | Apr 15, 2022 |
| Dell          | 0Y56T3 A00                  | Desktop     | [d9d86d5bfd](https://bsd-hardware.info/?probe=d9d86d5bfd) | Apr 12, 2022 |
| Notebook      | N13xWU                      | Notebook    | [8986953acd](https://bsd-hardware.info/?probe=8986953acd) | Mar 22, 2022 |
| Notebook      | N7x0WU                      | Notebook    | [b80f84aef1](https://bsd-hardware.info/?probe=b80f84aef1) | Mar 22, 2022 |
| Notebook      | N8xEJEK                     | Notebook    | [9a62677ea8](https://bsd-hardware.info/?probe=9a62677ea8) | Mar 22, 2022 |
| Lenovo        | ThinkPad Yoga 460 20ELS1... | Convertible | [c216d655ae](https://bsd-hardware.info/?probe=c216d655ae) | Mar 22, 2022 |
| Dell          | Latitude E6500              | Notebook    | [5fad69bbf0](https://bsd-hardware.info/?probe=5fad69bbf0) | Mar 22, 2022 |
| Dell          | Latitude E6510              | Notebook    | [a040a1a04b](https://bsd-hardware.info/?probe=a040a1a04b) | Mar 22, 2022 |
| Dell          | Latitude E6530              | Notebook    | [9bc5fc70a7](https://bsd-hardware.info/?probe=9bc5fc70a7) | Mar 22, 2022 |
| MSI           | B250 PC MATE                | Desktop     | [612b0f0a34](https://bsd-hardware.info/?probe=612b0f0a34) | Mar 19, 2022 |
| Lenovo        | ThinkPad X201 32492EU       | Notebook    | [4a5ba4f3e4](https://bsd-hardware.info/?probe=4a5ba4f3e4) | Mar 13, 2022 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [8307275b2e](https://bsd-hardware.info/?probe=8307275b2e) | Mar 07, 2022 |
| Dell          | 0GDJXY A00                  | All in one  | [589f10057f](https://bsd-hardware.info/?probe=589f10057f) | Mar 01, 2022 |
| Dell          | 0GDJXY A00                  | All in one  | [e14fd85d4a](https://bsd-hardware.info/?probe=e14fd85d4a) | Feb 27, 2022 |
| Lenovo        | ThinkPad T450 20BUS0VH08    | Notebook    | [bc2860431e](https://bsd-hardware.info/?probe=bc2860431e) | Feb 17, 2022 |
| Jumper        | EZbook                      | Notebook    | [35869ff0db](https://bsd-hardware.info/?probe=35869ff0db) | Feb 14, 2022 |
| Lenovo        | G500s 20245                 | Notebook    | [41f9f804ac](https://bsd-hardware.info/?probe=41f9f804ac) | Feb 04, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [0b290f2ac3](https://bsd-hardware.info/?probe=0b290f2ac3) | Feb 02, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [84d7fb3f1e](https://bsd-hardware.info/?probe=84d7fb3f1e) | Jan 30, 2022 |
| MSI           | GE75 Raider 10SFS           | Notebook    | [48b172bfe8](https://bsd-hardware.info/?probe=48b172bfe8) | Jan 25, 2022 |
| MSI           | GF63 Thin 10SCSR            | Notebook    | [5b9c617dc8](https://bsd-hardware.info/?probe=5b9c617dc8) | Jan 22, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [6d580e8270](https://bsd-hardware.info/?probe=6d580e8270) | Jan 21, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [52f4bdd7d0](https://bsd-hardware.info/?probe=52f4bdd7d0) | Jan 21, 2022 |
| Supermicro    | X10DRiB                     | Server      | [b4999ca89f](https://bsd-hardware.info/?probe=b4999ca89f) | Jan 21, 2022 |
| Dell          | 0NNNCT A01                  | Desktop     | [290f10c785](https://bsd-hardware.info/?probe=290f10c785) | Jan 21, 2022 |
| Dell          | Latitude E6540              | Notebook    | [f13972c935](https://bsd-hardware.info/?probe=f13972c935) | Jan 21, 2022 |
| Fujitsu       | CELSIUS H780                | Notebook    | [a173366c78](https://bsd-hardware.info/?probe=a173366c78) | Jan 21, 2022 |
| Jumper        | EZbook                      | Notebook    | [7d648bcdc7](https://bsd-hardware.info/?probe=7d648bcdc7) | Jan 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [cf360a6098](https://bsd-hardware.info/?probe=cf360a6098) | Jan 16, 2022 |
| Acer          | Extensa 5635Z               | Notebook    | [d76873c5dd](https://bsd-hardware.info/?probe=d76873c5dd) | Jan 16, 2022 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [a6d7796cea](https://bsd-hardware.info/?probe=a6d7796cea) | Jan 13, 2022 |
| Dell          | Latitude 5510               | Notebook    | [a620d284cb](https://bsd-hardware.info/?probe=a620d284cb) | Jan 12, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [19be37f181](https://bsd-hardware.info/?probe=19be37f181) | Jan 09, 2022 |
| Dell          | Latitude E5450              | Notebook    | [c2ef231757](https://bsd-hardware.info/?probe=c2ef231757) | Jan 04, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [3ada7b4079](https://bsd-hardware.info/?probe=3ada7b4079) | Jan 03, 2022 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | Notebook    | [259b5cc7b2](https://bsd-hardware.info/?probe=259b5cc7b2) | Dec 28, 2021 |
| Intel         | NUC7JYB J67970-400          | Mini pc     | [82c010f13c](https://bsd-hardware.info/?probe=82c010f13c) | Dec 09, 2021 |
| Alienware     | 01NYPT A00                  | Desktop     | [75aa0c00fb](https://bsd-hardware.info/?probe=75aa0c00fb) | Dec 06, 2021 |
| ASUSTek       | X202E                       | Notebook    | [7f4e6f4541](https://bsd-hardware.info/?probe=7f4e6f4541) | Dec 05, 2021 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [c501c5c75e](https://bsd-hardware.info/?probe=c501c5c75e) | Dec 04, 2021 |
| Samsung       | 530XBB                      | Notebook    | [41d5f95889](https://bsd-hardware.info/?probe=41d5f95889) | Dec 03, 2021 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [a2270b6f09](https://bsd-hardware.info/?probe=a2270b6f09) | Dec 02, 2021 |
| Alienware     | m15 R4                      | Notebook    | [a724a7d7c7](https://bsd-hardware.info/?probe=a724a7d7c7) | Nov 29, 2021 |
| Lenovo        | ThinkPad T520 4243E51       | Notebook    | [82f5612822](https://bsd-hardware.info/?probe=82f5612822) | Nov 29, 2021 |
| Sony          | SVP13225SCBI                | Notebook    | [03ef84679c](https://bsd-hardware.info/?probe=03ef84679c) | Nov 27, 2021 |
| Dell          | Latitude 5510               | Notebook    | [3da78c9445](https://bsd-hardware.info/?probe=3da78c9445) | Nov 24, 2021 |
| Acer          | TravelMate B117-M           | Notebook    | [4f02660d9c](https://bsd-hardware.info/?probe=4f02660d9c) | Nov 14, 2021 |
| Toshiba       | Satellite C855-1U4          | Notebook    | [4107fc9eee](https://bsd-hardware.info/?probe=4107fc9eee) | Nov 14, 2021 |
| Medion        | MS-7728                     | Desktop     | [5b5a847fdd](https://bsd-hardware.info/?probe=5b5a847fdd) | Nov 02, 2021 |
| Dell          | Latitude D630               | Notebook    | [7e3a92badc](https://bsd-hardware.info/?probe=7e3a92badc) | Nov 02, 2021 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [d23636abb2](https://bsd-hardware.info/?probe=d23636abb2) | Oct 31, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [69fe175fb8](https://bsd-hardware.info/?probe=69fe175fb8) | Oct 30, 2021 |
| HP            | Pavilion g6                 | Notebook    | [9754bc2e72](https://bsd-hardware.info/?probe=9754bc2e72) | Oct 27, 2021 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [9cf5948654](https://bsd-hardware.info/?probe=9cf5948654) | Oct 13, 2021 |
| MSI           | Modern 14 A10M              | Notebook    | [84838cd532](https://bsd-hardware.info/?probe=84838cd532) | Oct 07, 2021 |
| MSI           | Modern 14 A10M              | Notebook    | [db33045561](https://bsd-hardware.info/?probe=db33045561) | Oct 07, 2021 |
| Acer          | Aspire A315-56              | Notebook    | [03ca802f4b](https://bsd-hardware.info/?probe=03ca802f4b) | Oct 02, 2021 |
| MSI           | Modern 14 A10M              | Notebook    | [277d8118da](https://bsd-hardware.info/?probe=277d8118da) | Sep 30, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [76ea6529ac](https://bsd-hardware.info/?probe=76ea6529ac) | Sep 26, 2021 |
| MSI           | Modern 14 A10M              | Notebook    | [103ccaf452](https://bsd-hardware.info/?probe=103ccaf452) | Sep 25, 2021 |
| Lenovo        | ThinkPad X220 4290W42       | Notebook    | [8be5183e21](https://bsd-hardware.info/?probe=8be5183e21) | Sep 25, 2021 |
| Lenovo        | ThinkPad T500 2056Y2Z       | Notebook    | [88b86ecf8b](https://bsd-hardware.info/?probe=88b86ecf8b) | Sep 25, 2021 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [8f00f132de](https://bsd-hardware.info/?probe=8f00f132de) | Sep 23, 2021 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [bd5b726e52](https://bsd-hardware.info/?probe=bd5b726e52) | Sep 19, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [2a54a0c338](https://bsd-hardware.info/?probe=2a54a0c338) | Sep 14, 2021 |
| Lenovo        | ThinkPad T400 6474E18       | Notebook    | [2dd5b5869f](https://bsd-hardware.info/?probe=2dd5b5869f) | Sep 13, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [27f01061f2](https://bsd-hardware.info/?probe=27f01061f2) | Sep 12, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [9dc50c0bcb](https://bsd-hardware.info/?probe=9dc50c0bcb) | Sep 11, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | Notebook    | [ecd69774c0](https://bsd-hardware.info/?probe=ecd69774c0) | Sep 06, 2021 |
| System76      | Kudu                        | Notebook    | [c10fc12e40](https://bsd-hardware.info/?probe=c10fc12e40) | Sep 05, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [0ee3fe080c](https://bsd-hardware.info/?probe=0ee3fe080c) | Aug 30, 2021 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [d60f1bc575](https://bsd-hardware.info/?probe=d60f1bc575) | Aug 29, 2021 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [31b995146e](https://bsd-hardware.info/?probe=31b995146e) | Aug 25, 2021 |
| Acer          | Aspire 5750                 | Notebook    | [2bc72bf29e](https://bsd-hardware.info/?probe=2bc72bf29e) | Aug 23, 2021 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [6f89733e13](https://bsd-hardware.info/?probe=6f89733e13) | Aug 16, 2021 |
| MSI           | H81M-P33                    | Desktop     | [6dcb3aa559](https://bsd-hardware.info/?probe=6dcb3aa559) | Aug 05, 2021 |
| Dell          | Latitude E5440              | Notebook    | [3f2e8586a7](https://bsd-hardware.info/?probe=3f2e8586a7) | Aug 05, 2021 |
| Dell          | Latitude E6430              | Notebook    | [4149fa5ec3](https://bsd-hardware.info/?probe=4149fa5ec3) | Aug 04, 2021 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [9fe86991b5](https://bsd-hardware.info/?probe=9fe86991b5) | Aug 04, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [011fb96fe0](https://bsd-hardware.info/?probe=011fb96fe0) | Aug 04, 2021 |
| Lenovo        | Legion Y7000P 81LD          | Notebook    | [7364ae3b3d](https://bsd-hardware.info/?probe=7364ae3b3d) | Aug 04, 2021 |
| ASRock        | Z77 Extreme6                | Desktop     | [2521c70747](https://bsd-hardware.info/?probe=2521c70747) | Aug 02, 2021 |
| Lenovo        | ThinkPad L512 44444XG       | Notebook    | [a6c8fbcb20](https://bsd-hardware.info/?probe=a6c8fbcb20) | Aug 01, 2021 |
| GPU Compan... | GWTN156-5                   | Notebook    | [bc44d767cc](https://bsd-hardware.info/?probe=bc44d767cc) | Jul 22, 2021 |
| Dell          | Latitude E5520              | Notebook    | [e0dd26220f](https://bsd-hardware.info/?probe=e0dd26220f) | Jul 21, 2021 |
| Apple         | MacBook5,1                  | Notebook    | [1e54d2fbdf](https://bsd-hardware.info/?probe=1e54d2fbdf) | Jul 05, 2021 |
| Apple         | MacBook5,1                  | Notebook    | [f5d7a16498](https://bsd-hardware.info/?probe=f5d7a16498) | Jul 05, 2021 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [bde8057846](https://bsd-hardware.info/?probe=bde8057846) | Jun 29, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [668bf95221](https://bsd-hardware.info/?probe=668bf95221) | Jun 25, 2021 |
| Dell          | Latitude E6420              | Notebook    | [2e8b431cc6](https://bsd-hardware.info/?probe=2e8b431cc6) | Jun 25, 2021 |
| Lenovo        | ThinkPad T440 20B7S1860W    | Notebook    | [8552205176](https://bsd-hardware.info/?probe=8552205176) | Jun 22, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [9f82e215c3](https://bsd-hardware.info/?probe=9f82e215c3) | Jun 22, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [a2deab0991](https://bsd-hardware.info/?probe=a2deab0991) | Jun 15, 2021 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [10d9e99990](https://bsd-hardware.info/?probe=10d9e99990) | May 31, 2021 |
| Sony          | SVP1322M1EBI                | Notebook    | [23316d0f2b](https://bsd-hardware.info/?probe=23316d0f2b) | May 29, 2021 |
| Lenovo        | Board                       | Desktop     | [428f39cbff](https://bsd-hardware.info/?probe=428f39cbff) | May 21, 2021 |
| Lenovo        | ThinkPad T470 20HD000MUK    | Notebook    | [e27342ab94](https://bsd-hardware.info/?probe=e27342ab94) | May 13, 2021 |
| Lenovo        | ThinkPad X250 20CM003WMS    | Notebook    | [11fe52be5e](https://bsd-hardware.info/?probe=11fe52be5e) | May 13, 2021 |
| ASUSTek       | V-P7H55E                    | Desktop     | [7634d3b6ca](https://bsd-hardware.info/?probe=7634d3b6ca) | May 12, 2021 |
| ASUSTek       | V-P7H55E                    | Desktop     | [f2e42a5ca3](https://bsd-hardware.info/?probe=f2e42a5ca3) | May 10, 2021 |
| ASUSTek       | V-P7H55E                    | Desktop     | [0af6399c18](https://bsd-hardware.info/?probe=0af6399c18) | May 10, 2021 |
| Lenovo        | ThinkPad T430 2344C4U       | Notebook    | [0f001f65d2](https://bsd-hardware.info/?probe=0f001f65d2) | Apr 27, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [f8389b0546](https://bsd-hardware.info/?probe=f8389b0546) | Apr 24, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [cb09a1b771](https://bsd-hardware.info/?probe=cb09a1b771) | Apr 08, 2021 |
| Dell          | 0TP412                      | Desktop     | [1bc05b5951](https://bsd-hardware.info/?probe=1bc05b5951) | Apr 04, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e4e3731289](https://bsd-hardware.info/?probe=e4e3731289) | Apr 01, 2021 |
| Acer          | Aspire E5-521G              | Notebook    | [e2b6dbfe40](https://bsd-hardware.info/?probe=e2b6dbfe40) | Apr 01, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [ec9e43382e](https://bsd-hardware.info/?probe=ec9e43382e) | Mar 25, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [3e500c12a3](https://bsd-hardware.info/?probe=3e500c12a3) | Mar 24, 2021 |
| HP            | 1850                        | Desktop     | [3055c06d45](https://bsd-hardware.info/?probe=3055c06d45) | Mar 22, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [a64a4e0792](https://bsd-hardware.info/?probe=a64a4e0792) | Mar 19, 2021 |
| Lenovo        | ThinkPad X250 20CM003WMS    | Notebook    | [196cd8a730](https://bsd-hardware.info/?probe=196cd8a730) | Mar 11, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [240171b234](https://bsd-hardware.info/?probe=240171b234) | Mar 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9ede3128c5](https://bsd-hardware.info/?probe=9ede3128c5) | Mar 07, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [39a46ce44e](https://bsd-hardware.info/?probe=39a46ce44e) | Mar 06, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [b1ee3da46f](https://bsd-hardware.info/?probe=b1ee3da46f) | Mar 06, 2021 |
| Gigabyte      | EG43M-S2H                   | Desktop     | [f6eaa55ada](https://bsd-hardware.info/?probe=f6eaa55ada) | Mar 06, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [50ac436475](https://bsd-hardware.info/?probe=50ac436475) | Mar 06, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f27578615f](https://bsd-hardware.info/?probe=f27578615f) | Mar 05, 2021 |
| Acer          | Aspire XC-115               | Desktop     | [95f63df64d](https://bsd-hardware.info/?probe=95f63df64d) | Feb 21, 2021 |
| Lenovo        | Kabini CRB 31900058 STD     | Desktop     | [c08ca084b0](https://bsd-hardware.info/?probe=c08ca084b0) | Feb 21, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [3680c4cd75](https://bsd-hardware.info/?probe=3680c4cd75) | Feb 20, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ade306695d](https://bsd-hardware.info/?probe=ade306695d) | Feb 20, 2021 |
| Acer          | Extensa 5635Z               | Notebook    | [837c6f28b4](https://bsd-hardware.info/?probe=837c6f28b4) | Feb 19, 2021 |
| Acer          | WG43M                       | Desktop     | [28a6795710](https://bsd-hardware.info/?probe=28a6795710) | Feb 15, 2021 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [e6fa5753b5](https://bsd-hardware.info/?probe=e6fa5753b5) | Feb 12, 2021 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [fd798dae01](https://bsd-hardware.info/?probe=fd798dae01) | Feb 12, 2021 |
| Dell          | 030VXY A01                  | Desktop     | [23e7163f58](https://bsd-hardware.info/?probe=23e7163f58) | Feb 10, 2021 |
| Lenovo        | ThinkPad T470 20HD000MUK    | Notebook    | [39c8cd6d0c](https://bsd-hardware.info/?probe=39c8cd6d0c) | Feb 08, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [5a0b61ac41](https://bsd-hardware.info/?probe=5a0b61ac41) | Feb 07, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [254e518190](https://bsd-hardware.info/?probe=254e518190) | Feb 03, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [cf41f72474](https://bsd-hardware.info/?probe=cf41f72474) | Jan 31, 2021 |
| Dell          | Latitude 5480               | Notebook    | [9b38a72dd4](https://bsd-hardware.info/?probe=9b38a72dd4) | Jan 26, 2021 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [fb318623f3](https://bsd-hardware.info/?probe=fb318623f3) | Jan 23, 2021 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [97a89d4eb0](https://bsd-hardware.info/?probe=97a89d4eb0) | Jan 23, 2021 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [806c954739](https://bsd-hardware.info/?probe=806c954739) | Jan 23, 2021 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [3d18f3f8a9](https://bsd-hardware.info/?probe=3d18f3f8a9) | Jan 23, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [f6df3820b5](https://bsd-hardware.info/?probe=f6df3820b5) | Jan 18, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [3c41c474ad](https://bsd-hardware.info/?probe=3c41c474ad) | Jan 16, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | Convertible | [9e58a182a8](https://bsd-hardware.info/?probe=9e58a182a8) | Jan 16, 2021 |
| MSI           | Z97 GAMING 5                | Desktop     | [9ef0da6093](https://bsd-hardware.info/?probe=9ef0da6093) | Jan 16, 2021 |
| HP            | OMEN by HP Laptop           | Notebook    | [14857eb6b7](https://bsd-hardware.info/?probe=14857eb6b7) | Jan 15, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [f7c32488e9](https://bsd-hardware.info/?probe=f7c32488e9) | Jan 15, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [06cbb5cd5f](https://bsd-hardware.info/?probe=06cbb5cd5f) | Jan 15, 2021 |
| Dell          | Latitude 5280               | Notebook    | [c9bfb73262](https://bsd-hardware.info/?probe=c9bfb73262) | Jan 15, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [a9228fa7c3](https://bsd-hardware.info/?probe=a9228fa7c3) | Jan 15, 2021 |
| Dell          | 030VXY A01                  | Desktop     | [5af442bf61](https://bsd-hardware.info/?probe=5af442bf61) | Jan 15, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [a395c023bf](https://bsd-hardware.info/?probe=a395c023bf) | Jan 10, 2021 |
| Dell          | 0HY9JP A02                  | Desktop     | [b4d2af272e](https://bsd-hardware.info/?probe=b4d2af272e) | Jan 05, 2021 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [5124b24d30](https://bsd-hardware.info/?probe=5124b24d30) | Jan 04, 2021 |
| Dell          | Inspiron 5758               | Notebook    | [c096e37be5](https://bsd-hardware.info/?probe=c096e37be5) | Jan 03, 2021 |
| Fujitsu       | D3617-A1 S26361-D3617-A1    | Desktop     | [2a0187ef7a](https://bsd-hardware.info/?probe=2a0187ef7a) | Jan 02, 2021 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [5cd8e23152](https://bsd-hardware.info/?probe=5cd8e23152) | Dec 26, 2020 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [fdbd71db5e](https://bsd-hardware.info/?probe=fdbd71db5e) | Dec 26, 2020 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [c51c202b8d](https://bsd-hardware.info/?probe=c51c202b8d) | Dec 25, 2020 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [4c24fe6fc4](https://bsd-hardware.info/?probe=4c24fe6fc4) | Dec 24, 2020 |
| HP            | 0B4Ch D                     | Desktop     | [bf0d7fe4f1](https://bsd-hardware.info/?probe=bf0d7fe4f1) | Dec 22, 2020 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [a3a96da3fb](https://bsd-hardware.info/?probe=a3a96da3fb) | Dec 19, 2020 |
| Lenovo        | ThinkPad T450 20BV0064US    | Notebook    | [b397848c7e](https://bsd-hardware.info/?probe=b397848c7e) | Dec 16, 2020 |
| Toshiba       | Satellite C855              | Notebook    | [6bc78fc7fc](https://bsd-hardware.info/?probe=6bc78fc7fc) | Dec 16, 2020 |
| Panasonic     | CF-19AHNC8FN                | Notebook    | [04a42812bb](https://bsd-hardware.info/?probe=04a42812bb) | Dec 11, 2020 |
| Lenovo        | ThinkPad X220 42872VU       | Notebook    | [c843b5d271](https://bsd-hardware.info/?probe=c843b5d271) | Dec 10, 2020 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [464223cefe](https://bsd-hardware.info/?probe=464223cefe) | Dec 07, 2020 |
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | Convertible | [a6b923675d](https://bsd-hardware.info/?probe=a6b923675d) | Dec 07, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [d8a67b4a30](https://bsd-hardware.info/?probe=d8a67b4a30) | Dec 06, 2020 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [6c55fc2866](https://bsd-hardware.info/?probe=6c55fc2866) | Dec 05, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [53bf449015](https://bsd-hardware.info/?probe=53bf449015) | Dec 02, 2020 |
| Quanta        | 2AF5 011                    | Desktop     | [172f23efac](https://bsd-hardware.info/?probe=172f23efac) | Nov 29, 2020 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [8afa16fc20](https://bsd-hardware.info/?probe=8afa16fc20) | Nov 29, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [5d5ecb38cd](https://bsd-hardware.info/?probe=5d5ecb38cd) | Nov 25, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [7fc23a57bb](https://bsd-hardware.info/?probe=7fc23a57bb) | Nov 25, 2020 |
| MSI           | B450 GAMING PLUS            | Desktop     | [4cf3dd682b](https://bsd-hardware.info/?probe=4cf3dd682b) | Nov 24, 2020 |
| MSI           | B450 GAMING PLUS            | Desktop     | [edee76372b](https://bsd-hardware.info/?probe=edee76372b) | Nov 21, 2020 |
| Acer          | Aspire 7540                 | Notebook    | [65d215a03b](https://bsd-hardware.info/?probe=65d215a03b) | Nov 17, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [cc075b3932](https://bsd-hardware.info/?probe=cc075b3932) | Nov 15, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [6a0c640524](https://bsd-hardware.info/?probe=6a0c640524) | Nov 12, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [6060033216](https://bsd-hardware.info/?probe=6060033216) | Nov 12, 2020 |
| Apple         | MacBook6,1                  | Notebook    | [64b1b1910c](https://bsd-hardware.info/?probe=64b1b1910c) | Nov 01, 2020 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [dc33c84287](https://bsd-hardware.info/?probe=dc33c84287) | Oct 22, 2020 |
| Acer          | Aspire A315-42              | Notebook    | [1ac21e1660](https://bsd-hardware.info/?probe=1ac21e1660) | Oct 08, 2020 |
| Acer          | Aspire E1-532               | Notebook    | [10bff44534](https://bsd-hardware.info/?probe=10bff44534) | Oct 07, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [7faf1699d6](https://bsd-hardware.info/?probe=7faf1699d6) | Oct 04, 2020 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | Desktop     | [86e9866c03](https://bsd-hardware.info/?probe=86e9866c03) | Oct 02, 2020 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | Desktop     | [3b8f8a2033](https://bsd-hardware.info/?probe=3b8f8a2033) | Oct 02, 2020 |
| Lenovo        | ThinkPad T590 20N40016CD    | Notebook    | [1d9786ac9f](https://bsd-hardware.info/?probe=1d9786ac9f) | Aug 31, 2020 |
| Lenovo        | ThinkPad T590 20N40016CD    | Notebook    | [e505894bee](https://bsd-hardware.info/?probe=e505894bee) | Aug 29, 2020 |
| System76      | Lemur Pro                   | Notebook    | [0163d0f084](https://bsd-hardware.info/?probe=0163d0f084) | Aug 29, 2020 |
| Lenovo        | ThinkPad T430s 23539JM      | Notebook    | [facf6fa0f8](https://bsd-hardware.info/?probe=facf6fa0f8) | Aug 27, 2020 |
| ASUSTek       | K53SD                       | Notebook    | [975e9ccbe2](https://bsd-hardware.info/?probe=975e9ccbe2) | Aug 27, 2020 |
| Lenovo        | ThinkPad T530 239242U       | Notebook    | [7c8087322d](https://bsd-hardware.info/?probe=7c8087322d) | Aug 27, 2020 |
| Sony          | VGN-SZ3VWP_X                | Notebook    | [ace534d784](https://bsd-hardware.info/?probe=ace534d784) | Aug 10, 2020 |
| TUXEDO        | InfinityBook13V3            | Notebook    | [d508fb472b](https://bsd-hardware.info/?probe=d508fb472b) | Aug 10, 2020 |
| MSI           | H61M-P20                    | Desktop     | [fefac5637b](https://bsd-hardware.info/?probe=fefac5637b) | Aug 03, 2020 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [0073f8ff71](https://bsd-hardware.info/?probe=0073f8ff71) | Aug 02, 2020 |
| Gigabyte      | H67A-UD3H-B3                | Desktop     | [aa29eb9c75](https://bsd-hardware.info/?probe=aa29eb9c75) | Aug 01, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [b89da90904](https://bsd-hardware.info/?probe=b89da90904) | Aug 01, 2020 |
| ASUSTek       | G750JS                      | Notebook    | [8214170523](https://bsd-hardware.info/?probe=8214170523) | Aug 01, 2020 |
| ASUSTek       | G750JS                      | Notebook    | [60b904f003](https://bsd-hardware.info/?probe=60b904f003) | Aug 01, 2020 |
| Unknown       | SKYBAY                      | Desktop     | [34bb81770b](https://bsd-hardware.info/?probe=34bb81770b) | Jul 22, 2020 |
| ASRock        | X370 Gaming K4              | Desktop     | [4473708fd0](https://bsd-hardware.info/?probe=4473708fd0) | Jul 22, 2020 |
| ASRock        | X370 Gaming K4              | Desktop     | [174569bf55](https://bsd-hardware.info/?probe=174569bf55) | Jul 21, 2020 |
| ASRock        | A300M-STX                   | Desktop     | [f62a2ace5a](https://bsd-hardware.info/?probe=f62a2ace5a) | Jul 16, 2020 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [db7146b868](https://bsd-hardware.info/?probe=db7146b868) | Jul 14, 2020 |
| Dell          | Latitude E6420              | Notebook    | [324265fe3f](https://bsd-hardware.info/?probe=324265fe3f) | May 31, 2020 |
| Lenovo        | ThinkPad T430s 2352CTO      | Notebook    | [f4e8ffb5dc](https://bsd-hardware.info/?probe=f4e8ffb5dc) | May 27, 2020 |
| Lenovo        | ThinkPad T430s 2352CTO      | Notebook    | [59c5b6d6b9](https://bsd-hardware.info/?probe=59c5b6d6b9) | May 27, 2020 |
| Dell          | Precision M4700             | Notebook    | [a7761ee829](https://bsd-hardware.info/?probe=a7761ee829) | May 25, 2020 |
| Gigabyte      | Z170X-UD5 TH-CF             | Desktop     | [2fc2952380](https://bsd-hardware.info/?probe=2fc2952380) | May 25, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [6a1b7867f0](https://bsd-hardware.info/?probe=6a1b7867f0) | May 16, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [25fd1154c0](https://bsd-hardware.info/?probe=25fd1154c0) | May 08, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [0370bc0522](https://bsd-hardware.info/?probe=0370bc0522) | May 02, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| GhostBSD 20.04.02    | 109       | 49.55%  |
| GhostBSD 21.08.27    | 40        | 18.18%  |
| GhostBSD 22.01.12    | 18        | 8.18%   |
| GhostBSD 22.06.18    | 5         | 2.27%   |
| GhostBSD 22.07.16    | 4         | 1.82%   |
| GhostBSD 22.06.26    | 4         | 1.82%   |
| GhostBSD 22.11.02    | 3         | 1.36%   |
| GhostBSD 22.09.16    | 3         | 1.36%   |
| GhostBSD 22.08.23    | 3         | 1.36%   |
| GhostBSD 22.04.06    | 3         | 1.36%   |
| GhostBSD 22.11.22    | 2         | 0.91%   |
| GhostBSD 22.08.06    | 2         | 0.91%   |
| GhostBSD 22.07.13    | 2         | 0.91%   |
| GhostBSD 22.04.22    | 2         | 0.91%   |
| GhostBSD 22.10.30    | 1         | 0.45%   |
| GhostBSD 22.10.12    | 1         | 0.45%   |
| GhostBSD 22.08.27    | 1         | 0.45%   |
| GhostBSD 22.07.31    | 1         | 0.45%   |
| GhostBSD 22.07.28    | 1         | 0.45%   |
| GhostBSD 22.07.10    | 1         | 0.45%   |
| GhostBSD 22.06.20    | 1         | 0.45%   |
| GhostBSD 22.06.07    | 1         | 0.45%   |
| GhostBSD 22.05.14    | 1         | 0.45%   |
| GhostBSD 22.05.13    | 1         | 0.45%   |
| GhostBSD 22.04.30    | 1         | 0.45%   |
| GhostBSD 22.02.26    | 1         | 0.45%   |
| GhostBSD 22.02.20    | 1         | 0.45%   |
| GhostBSD 22.01.28    | 1         | 0.45%   |
| GhostBSD 21.12.29    | 1         | 0.45%   |
| GhostBSD 21.11.24    | 1         | 0.45%   |
| GhostBSD 20.07.14    | 1         | 0.45%   |
| GhostBSD 20.03.01    | 1         | 0.45%   |
| GhostBSD 19.12       | 1         | 0.45%   |
| GhostBSD 12.2-STABLE | 1         | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| GhostBSD | 207       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 207       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| MATE             | 161       | 75.94%  |
| XFCE             | 28        | 13.21%  |
| KDE5             | 11        | 5.19%   |
| Cinnamon         | 3         | 1.42%   |
| Metacity (Marco) | 2         | 0.94%   |
| GNOME            | 2         | 0.94%   |
| openbox          | 1         | 0.47%   |
| LXQt             | 1         | 0.47%   |
| i3               | 1         | 0.47%   |
| helloDesktop     | 1         | 0.47%   |
| Console          | 1         | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 205       | 99.03%  |
| Wayland | 1         | 0.48%   |
| Console | 1         | 0.48%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 203       | 98.07%  |
| SDDM    | 3         | 1.45%   |
| Console | 1         | 0.48%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 90        | 41.86%  |
| C       | 59        | 27.44%  |
| Unknown | 28        | 13.02%  |
| de_DE   | 13        | 6.05%   |
| ru_RU   | 5         | 2.33%   |
| en_GB   | 3         | 1.4%    |
| sk_SK   | 2         | 0.93%   |
| pt_BR   | 2         | 0.93%   |
| pl_PL   | 2         | 0.93%   |
| it_IT   | 2         | 0.93%   |
| fr_FR   | 2         | 0.93%   |
| es_ES   | 2         | 0.93%   |
| zh_CN   | 1         | 0.47%   |
| sv_SE   | 1         | 0.47%   |
| en_NZ   | 1         | 0.47%   |
| en_AU   | 1         | 0.47%   |
| el_GR   | 1         | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 161       | 77.78%  |
| BIOS | 46        | 22.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 196       | 92.89%  |
| Ufs  | 15        | 7.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 199       | 96.14%  |
| MBR  | 8         | 3.86%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 39        | 18.84%  |
| Dell                | 39        | 18.84%  |
| ASUSTek Computer    | 27        | 13.04%  |
| Hewlett-Packard     | 15        | 7.25%   |
| MSI                 | 13        | 6.28%   |
| Gigabyte Technology | 13        | 6.28%   |
| Acer                | 12        | 5.8%    |
| ASRock              | 9         | 4.35%   |
| Apple               | 6         | 2.9%    |
| Sony                | 4         | 1.93%   |
| Notebook            | 4         | 1.93%   |
| Fujitsu             | 4         | 1.93%   |
| System76            | 3         | 1.45%   |
| Toshiba             | 2         | 0.97%   |
| Samsung Electronics | 2         | 0.97%   |
| Intel               | 2         | 0.97%   |
| Alienware           | 2         | 0.97%   |
| TUXEDO              | 1         | 0.48%   |
| Supermicro          | 1         | 0.48%   |
| Star Labs           | 1         | 0.48%   |
| Quanta              | 1         | 0.48%   |
| Panasonic           | 1         | 0.48%   |
| Medion              | 1         | 0.48%   |
| Jumper              | 1         | 0.48%   |
| HUAWEI              | 1         | 0.48%   |
| Huanan              | 1         | 0.48%   |
| GPU Company         | 1         | 0.48%   |
| Unknown             | 1         | 0.48%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Dell Inspiron 3542                       | 3         | 1.45%   |
| MSI MS-7B86                              | 2         | 0.97%   |
| MSI MS-7817                              | 2         | 0.97%   |
| MSI Modern 14 A10M                       | 2         | 0.97%   |
| Lenovo ThinkPad T430s 2352CTO            | 2         | 0.97%   |
| Dell XPS 13 7390                         | 2         | 0.97%   |
| Dell Latitude E6420                      | 2         | 0.97%   |
| ASUS ZenBook UX325UA_UM325UA             | 2         | 0.97%   |
| ASUS All Series                          | 2         | 0.97%   |
| Unknown                                  | 2         | 0.97%   |
| TUXEDO InfinityBook13V3                  | 1         | 0.48%   |
| Toshiba Satellite C855-1U4               | 1         | 0.48%   |
| Toshiba Satellite C855                   | 1         | 0.48%   |
| System76 Lemur Pro                       | 1         | 0.48%   |
| System76 Kudu                            | 1         | 0.48%   |
| System76 Gazelle                         | 1         | 0.48%   |
| Supermicro X10DRi                        | 1         | 0.48%   |
| Star Labs LabTop                         | 1         | 0.48%   |
| Sony VPCCB17FG                           | 1         | 0.48%   |
| Sony VGN-SZ3VWP_X                        | 1         | 0.48%   |
| Sony SVP1322M1EBI                        | 1         | 0.48%   |
| Sony SVP13225SCBI                        | 1         | 0.48%   |
| Samsung 550P5C/550P7C                    | 1         | 0.48%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV | 1         | 0.48%   |
| Quanta 120-1333w                         | 1         | 0.48%   |
| Panasonic CF-19AHNC8FN                   | 1         | 0.48%   |
| Notebook N8xEJEK                         | 1         | 0.48%   |
| Notebook N85_N87,HJ,HJ1,HK1              | 1         | 0.48%   |
| Notebook N7x0WU                          | 1         | 0.48%   |
| Notebook N13xWU                          | 1         | 0.48%   |
| MSI MS-7C36                              | 1         | 0.48%   |
| MSI MS-7B94                              | 1         | 0.48%   |
| MSI MS-7A72                              | 1         | 0.48%   |
| MSI MS-7917                              | 1         | 0.48%   |
| MSI MS-7788                              | 1         | 0.48%   |
| MSI GF63 Thin 10SCSR                     | 1         | 0.48%   |
| MSI GE75 Raider 10SFS                    | 1         | 0.48%   |
| Medion MS-7728                           | 1         | 0.48%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS       | 1         | 0.48%   |
| Lenovo Yoga 2 13 20344                   | 1         | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 26        | 12.56%  |
| Dell Latitude           | 16        | 7.73%   |
| Acer Aspire             | 10        | 4.83%   |
| Dell Inspiron           | 9         | 4.35%   |
| ASUS PRIME              | 6         | 2.9%    |
| HP Laptop               | 5         | 2.42%   |
| Dell Precision          | 5         | 2.42%   |
| Dell OptiPlex           | 5         | 2.42%   |
| Lenovo IdeaPad          | 4         | 1.93%   |
| ASUS TUF                | 4         | 1.93%   |
| HP EliteBook            | 3         | 1.45%   |
| Dell XPS                | 3         | 1.45%   |
| ASRock X570             | 3         | 1.45%   |
| Toshiba Satellite       | 2         | 0.97%   |
| MSI MS-7B86             | 2         | 0.97%   |
| MSI MS-7817             | 2         | 0.97%   |
| MSI Modern              | 2         | 0.97%   |
| Lenovo Yoga             | 2         | 0.97%   |
| Lenovo ThinkCentre      | 2         | 0.97%   |
| HP Pavilion             | 2         | 0.97%   |
| Fujitsu CELSIUS         | 2         | 0.97%   |
| ASUS ZenBook            | 2         | 0.97%   |
| ASUS VivoBook           | 2         | 0.97%   |
| ASUS ROG                | 2         | 0.97%   |
| ASUS All                | 2         | 0.97%   |
| ASRock B450             | 2         | 0.97%   |
| Unknown                 | 2         | 0.97%   |
| TUXEDO InfinityBook13V3 | 1         | 0.48%   |
| System76 Lemur          | 1         | 0.48%   |
| System76 Kudu           | 1         | 0.48%   |
| System76 Gazelle        | 1         | 0.48%   |
| Supermicro X10DRi       | 1         | 0.48%   |
| Star Labs LabTop        | 1         | 0.48%   |
| Sony VPCCB17FG          | 1         | 0.48%   |
| Sony VGN-SZ3VWP         | 1         | 0.48%   |
| Sony SVP1322M1EBI       | 1         | 0.48%   |
| Sony SVP13225SCBI       | 1         | 0.48%   |
| Samsung 550P5C          | 1         | 0.48%   |
| Samsung 3570R           | 1         | 0.48%   |
| Quanta 120-1333w        | 1         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 31        | 14.98%  |
| 2018 | 24        | 11.59%  |
| 2019 | 19        | 9.18%   |
| 2013 | 19        | 9.18%   |
| 2021 | 17        | 8.21%   |
| 2014 | 15        | 7.25%   |
| 2012 | 14        | 6.76%   |
| 2015 | 11        | 5.31%   |
| 2011 | 11        | 5.31%   |
| 2016 | 9         | 4.35%   |
| 2009 | 9         | 4.35%   |
| 2017 | 8         | 3.86%   |
| 2022 | 7         | 3.38%   |
| 2008 | 7         | 3.38%   |
| 2010 | 5         | 2.42%   |
| 2007 | 1         | 0.48%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 125       | 60.39%  |
| Desktop     | 71        | 34.3%   |
| Mini pc     | 5         | 2.42%   |
| Convertible | 4         | 1.93%   |
| All in one  | 1         | 0.48%   |
| Server      | 1         | 0.48%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 206       | 99.52%  |
| Yes  | 1         | 0.48%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 86        | 41.55%  |
| 16.01-24.0      | 59        | 28.5%   |
| 4.01-8.0        | 32        | 15.46%  |
| 32.01-64.0      | 21        | 10.14%  |
| 64.01-256.0     | 4         | 1.93%   |
| 24.01-32.0      | 3         | 1.45%   |
| More than 256.0 | 1         | 0.48%   |
| 2.01-3.0        | 1         | 0.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 86        | 40.95%  |
| 0.01-0.5   | 84        | 40%     |
| 1.01-2.0   | 23        | 10.95%  |
| 2.01-3.0   | 10        | 4.76%   |
| 3.01-4.0   | 4         | 1.9%    |
| 4.01-8.0   | 2         | 0.95%   |
| 24.01-32.0 | 1         | 0.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 122       | 57.28%  |
| 2      | 58        | 27.23%  |
| 0      | 9         | 4.23%   |
| 4      | 7         | 3.29%   |
| 3      | 7         | 3.29%   |
| 5      | 6         | 2.82%   |
| 6      | 2         | 0.94%   |
| 22     | 1         | 0.47%   |
| 7      | 1         | 0.47%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 125       | 60.1%   |
| Yes       | 83        | 39.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 186       | 89.86%  |
| No        | 21        | 10.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 160       | 77.29%  |
| No        | 47        | 22.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 123       | 59.42%  |
| No        | 84        | 40.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 46        | 22.22%  |
| Germany      | 32        | 15.46%  |
| France       | 14        | 6.76%   |
| UK           | 13        | 6.28%   |
| Russia       | 9         | 4.35%   |
| Poland       | 6         | 2.9%    |
| Canada       | 6         | 2.9%    |
| Switzerland  | 5         | 2.42%   |
| Spain        | 5         | 2.42%   |
| Sweden       | 4         | 1.93%   |
| Italy        | 4         | 1.93%   |
| India        | 4         | 1.93%   |
| Norway       | 3         | 1.45%   |
| New Zealand  | 3         | 1.45%   |
| Netherlands  | 3         | 1.45%   |
| Malaysia     | 3         | 1.45%   |
| Japan        | 3         | 1.45%   |
| Finland      | 3         | 1.45%   |
| China        | 3         | 1.45%   |
| Argentina    | 3         | 1.45%   |
| Ukraine      | 2         | 0.97%   |
| Slovenia     | 2         | 0.97%   |
| Slovakia     | 2         | 0.97%   |
| Portugal     | 2         | 0.97%   |
| Philippines  | 2         | 0.97%   |
| Indonesia    | 2         | 0.97%   |
| Hungary      | 2         | 0.97%   |
| Hong Kong    | 2         | 0.97%   |
| Czechia      | 2         | 0.97%   |
| Brazil       | 2         | 0.97%   |
| Belgium      | 2         | 0.97%   |
| Australia    | 2         | 0.97%   |
| Uganda       | 1         | 0.48%   |
| UAE          | 1         | 0.48%   |
| South Africa | 1         | 0.48%   |
| Serbia       | 1         | 0.48%   |
| Namibia      | 1         | 0.48%   |
| Mexico       | 1         | 0.48%   |
| Luxembourg   | 1         | 0.48%   |
| Kazakhstan   | 1         | 0.48%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Bonn               | 6         | 2.82%   |
| Bedburg            | 6         | 2.82%   |
| Paris              | 5         | 2.35%   |
| London             | 3         | 1.41%   |
| Franconville       | 3         | 1.41%   |
| Denver             | 3         | 1.41%   |
| Chrusty            | 3         | 1.41%   |
| Berlin             | 3         | 1.41%   |
| Zurich             | 2         | 0.94%   |
| Yokohama           | 2         | 0.94%   |
| Whittier           | 2         | 0.94%   |
| Wezeren            | 2         | 0.94%   |
| Stiring-Wendel     | 2         | 0.94%   |
| St Petersburg      | 2         | 0.94%   |
| Salem              | 2         | 0.94%   |
| Rome               | 2         | 0.94%   |
| Richmond           | 2         | 0.94%   |
| Oslo               | 2         | 0.94%   |
| Obninsk            | 2         | 0.94%   |
| Madrid             | 2         | 0.94%   |
| Kyiv               | 2         | 0.94%   |
| JyvГ¤skylГ¤    | 2         | 0.94%   |
| Jakarta            | 2         | 0.94%   |
| Hamilton           | 2         | 0.94%   |
| Hamburg            | 2         | 0.94%   |
| Giessen            | 2         | 0.94%   |
| Eiken              | 2         | 0.94%   |
| Cologne            | 2         | 0.94%   |
| Clemmons           | 2         | 0.94%   |
| Celje              | 2         | 0.94%   |
| Berkeley           | 2         | 0.94%   |
| Bayan Lepas        | 2         | 0.94%   |
| Atascadero         | 2         | 0.94%   |
| Asnieres-sur-Seine | 2         | 0.94%   |
| ЕЊta-ku          | 1         | 0.47%   |
| Zapopan            | 1         | 0.47%   |
| Yaroslavl          | 1         | 0.47%   |
| Wraysbury          | 1         | 0.47%   |
| Witbank            | 1         | 0.47%   |
| Winnipeg           | 1         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 70        | 95     | 23.18%  |
| WDC                 | 56        | 76     | 18.54%  |
| Seagate             | 33        | 45     | 10.93%  |
| Crucial             | 23        | 26     | 7.62%   |
| Toshiba             | 17        | 22     | 5.63%   |
| Kingston            | 17        | 17     | 5.63%   |
| SanDisk             | 12        | 13     | 3.97%   |
| Hitachi             | 10        | 10     | 3.31%   |
| SK hynix            | 6         | 8      | 1.99%   |
| Micron Technology   | 5         | 5      | 1.66%   |
| HGST                | 5         | 5      | 1.66%   |
| PNY                 | 4         | 6      | 1.32%   |
| Phison              | 4         | 6      | 1.32%   |
| Intel               | 4         | 4      | 1.32%   |
| A-DATA Technology   | 4         | 4      | 1.32%   |
| Patriot             | 3         | 3      | 0.99%   |
| Gigabyte Technology | 3         | 3      | 0.99%   |
| Plextor             | 2         | 2      | 0.66%   |
| OCZ                 | 2         | 2      | 0.66%   |
| Maxtor              | 2         | 2      | 0.66%   |
| KingSpec            | 2         | 2      | 0.66%   |
| Goodram             | 2         | 2      | 0.66%   |
| Fujitsu             | 2         | 2      | 0.66%   |
| XPG                 | 1         | 1      | 0.33%   |
| Transcend           | 1         | 1      | 0.33%   |
| Star Drive          | 1         | 1      | 0.33%   |
| SSSTC               | 1         | 1      | 0.33%   |
| SPCC                | 1         | 1      | 0.33%   |
| Netac               | 1         | 1      | 0.33%   |
| LITEONIT            | 1         | 1      | 0.33%   |
| LDLC                | 1         | 1      | 0.33%   |
| HPT                 | 1         | 4      | 0.33%   |
| Hewlett-Packard     | 1         | 1      | 0.33%   |
| Corsair             | 1         | 1      | 0.33%   |
| China               | 1         | 1      | 0.33%   |
| Apple               | 1         | 1      | 0.33%   |
| AMD                 | 1         | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB          | 7         | 2.1%    |
| Samsung SSD 860 QVO 1TB            | 5         | 1.5%    |
| Samsung SSD 850 EVO 500GB          | 5         | 1.5%    |
| Samsung SSD 860 EVO 500GB          | 4         | 1.2%    |
| Crucial CT1000MX500SSD1 1TB        | 4         | 1.2%    |
| WDC WDS500G2B0A-00SM50 500GB       | 3         | 0.9%    |
| Seagate ST1000LM049-2GH172 1TB     | 3         | 0.9%    |
| Seagate ST1000LM035-1RK172 1TB     | 3         | 0.9%    |
| Samsung SSD 860 EVO 1TB            | 3         | 0.9%    |
| WDC WDS480G2G0A-00JH30 480GB       | 2         | 0.6%    |
| WDC WDS240G2G0A-00JH30 240GB       | 2         | 0.6%    |
| WDC WDS100T3X0C-00SJG0 1TB         | 2         | 0.6%    |
| WDC WD40EFRX-68N32N0 4TB           | 2         | 0.6%    |
| WDC WD2000JS-55MHB0 192GB          | 2         | 0.6%    |
| WDC WD10EZEX-21M2NA0 1TB           | 2         | 0.6%    |
| Toshiba Q300 480GB                 | 2         | 0.6%    |
| Toshiba HDWD120 2TB                | 2         | 0.6%    |
| SK hynix HFM512GD3JX013N 512GB     | 2         | 0.6%    |
| Seagate ST500DM002-1BD142 500GB    | 2         | 0.6%    |
| Seagate ST4000DM004-2CV104 4TB     | 2         | 0.6%    |
| Seagate ST2000LM003 HN-M201RAD 2TB | 2         | 0.6%    |
| SanDisk SSD PLUS 1000GB            | 2         | 0.6%    |
| Samsung SSD 970 EVO Plus 1TB       | 2         | 0.6%    |
| Samsung SSD 970 EVO 500GB          | 2         | 0.6%    |
| Samsung SSD 970 EVO 250GB          | 2         | 0.6%    |
| Samsung SSD 870 EVO 1TB            | 2         | 0.6%    |
| Samsung SSD 840 PRO Series 256GB   | 2         | 0.6%    |
| Samsung PM981 NVMe 256GB           | 2         | 0.6%    |
| Samsung MZNTE128HMGR-000SO 128GB   | 2         | 0.6%    |
| Micron 1100 SATA 256GB             | 2         | 0.6%    |
| Maxtor STM3320613AS 320GB          | 2         | 0.6%    |
| Kingston SA400S37240G 240GB        | 2         | 0.6%    |
| Kingston SA400S37120G 120GB        | 2         | 0.6%    |
| Kingston RBUSNS8154P3512GJ 512GB   | 2         | 0.6%    |
| KingSpec Q-720 720GB               | 2         | 0.6%    |
| HGST HTS721010A9E630 1TB           | 2         | 0.6%    |
| Gigabyte GP-GSM2NE3100TNTD 1TB     | 2         | 0.6%    |
| Crucial CT250MX500SSD1 250GB       | 2         | 0.6%    |
| Crucial CT1050MX300SSD1 1TB        | 2         | 0.6%    |
| XPG GAMMIX S11 Pro 256GB           | 1         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 38        | 51     | 36.89%  |
| Seagate             | 32        | 43     | 31.07%  |
| Hitachi             | 10        | 10     | 9.71%   |
| Toshiba             | 8         | 9      | 7.77%   |
| Samsung Electronics | 5         | 6      | 4.85%   |
| HGST                | 5         | 5      | 4.85%   |
| Maxtor              | 2         | 2      | 1.94%   |
| Fujitsu             | 2         | 2      | 1.94%   |
| HPT                 | 1         | 4      | 0.97%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 47        | 61     | 32.87%  |
| Crucial             | 19        | 22     | 13.29%  |
| Kingston            | 13        | 13     | 9.09%   |
| WDC                 | 12        | 14     | 8.39%   |
| SanDisk             | 12        | 13     | 8.39%   |
| PNY                 | 4         | 6      | 2.8%    |
| Micron Technology   | 4         | 4      | 2.8%    |
| A-DATA Technology   | 4         | 4      | 2.8%    |
| Toshiba             | 3         | 4      | 2.1%    |
| SK hynix            | 3         | 3      | 2.1%    |
| Patriot             | 3         | 3      | 2.1%    |
| Plextor             | 2         | 2      | 1.4%    |
| OCZ                 | 2         | 2      | 1.4%    |
| KingSpec            | 2         | 2      | 1.4%    |
| Intel               | 2         | 2      | 1.4%    |
| Goodram             | 2         | 2      | 1.4%    |
| Transcend           | 1         | 1      | 0.7%    |
| SPCC                | 1         | 1      | 0.7%    |
| Seagate             | 1         | 1      | 0.7%    |
| Phison              | 1         | 1      | 0.7%    |
| Netac               | 1         | 1      | 0.7%    |
| LITEONIT            | 1         | 1      | 0.7%    |
| China               | 1         | 1      | 0.7%    |
| Apple               | 1         | 1      | 0.7%    |
| AMD                 | 1         | 1      | 0.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 115       | 166    | 44.57%  |
| HDD  | 82        | 132    | 31.78%  |
| NVMe | 61        | 79     | 23.64%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 170       | 298    | 73.59%  |
| NVMe | 61        | 79     | 26.41%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 126       | 166    | 58.06%  |
| 0.51-1.0   | 57        | 82     | 26.27%  |
| 1.01-2.0   | 19        | 26     | 8.76%   |
| 3.01-4.0   | 8         | 10     | 3.69%   |
| 4.01-10.0  | 5         | 10     | 2.3%    |
| 2.01-3.0   | 1         | 2      | 0.46%   |
| 10.01-20.0 | 1         | 2      | 0.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 66        | 30.56%  |
| 101-250    | 51        | 23.61%  |
| 251-500    | 36        | 16.67%  |
| 501-1000   | 22        | 10.19%  |
| 51-100     | 19        | 8.8%    |
| Unknown    | 14        | 6.48%   |
| 21-50      | 4         | 1.85%   |
| 1001-2000  | 4         | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 182       | 83.87%  |
| 21-50   | 17        | 7.83%   |
| Unknown | 14        | 6.45%   |
| 51-100  | 3         | 1.38%   |
| 101-250 | 1         | 0.46%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Computers | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| Maxtor STM3320613AS 320GB                       | 2         | 2      | 6.25%   |
| WDC WDS480G2G0A-00JH30 480GB                    | 1         | 2      | 3.13%   |
| WDC WD6400BEVT-22A0RT0 640GB                    | 1         | 1      | 3.13%   |
| WDC WD5000AAKS-60WWPA0 500GB                    | 1         | 1      | 3.13%   |
| WDC WD3200LPVX-75V0TT0 320GB                    | 1         | 1      | 3.13%   |
| WDC WD10EZEX-21M2NA0 1TB                        | 1         | 1      | 3.13%   |
| Toshiba MQ01ACF032 320GB                        | 1         | 1      | 3.13%   |
| Seagate ST9250827AS 250GB                       | 1         | 1      | 3.13%   |
| Seagate ST500LT012-9WS142 500GB                 | 1         | 2      | 3.13%   |
| Seagate ST500LM021-1KJ152 500GB                 | 1         | 1      | 3.13%   |
| Seagate ST500DM002-1BD142 500GB                 | 1         | 1      | 3.13%   |
| Seagate ST500DM002-1BC142 500GB                 | 1         | 1      | 3.13%   |
| Seagate ST4000DM004-2CV104 4TB                  | 1         | 1      | 3.13%   |
| Seagate ST31500541AS 1.5TB                      | 1         | 1      | 3.13%   |
| Seagate ST1000LM035-1RK172 1TB                  | 1         | 2      | 3.13%   |
| Samsung Electronics SSD 980 500GB               | 1         | 1      | 3.13%   |
| Samsung Electronics SSD 840 PRO Series 256GB    | 1         | 1      | 3.13%   |
| Samsung Electronics MZNTE128HMGR-000SO 128GB    | 1         | 1      | 3.13%   |
| Samsung Electronics HD103SJ 1TB                 | 1         | 2      | 3.13%   |
| Patriot Inferno 60GB SSD                        | 1         | 1      | 3.13%   |
| OCZ AGILITY3 240GB                              | 1         | 1      | 3.13%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB | 1         | 1      | 3.13%   |
| Intel SSDSC2BF180A5L 180GB                      | 1         | 1      | 3.13%   |
| Hitachi HTS725032A9A364 320GB                   | 1         | 1      | 3.13%   |
| Hitachi HTS547575A9E384 752GB                   | 1         | 1      | 3.13%   |
| Hitachi HTS543225L9A300 250GB                   | 1         | 1      | 3.13%   |
| Hitachi HTS541680J9SA00 80GB                    | 1         | 1      | 3.13%   |
| HGST HTS721010A9E630 1TB                        | 1         | 1      | 3.13%   |
| Crucial CT480M500SSD1 480GB                     | 1         | 1      | 3.13%   |
| Crucial CT1050MX300SSD1 1TB                     | 1         | 1      | 3.13%   |
| Crucial CT1000MX500SSD1 1TB                     | 1         | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 10     | 25%     |
| WDC                 | 5         | 6      | 15.63%  |
| Samsung Electronics | 4         | 5      | 12.5%   |
| Hitachi             | 4         | 4      | 12.5%   |
| Crucial             | 3         | 3      | 9.38%   |
| Maxtor              | 2         | 2      | 6.25%   |
| Toshiba             | 1         | 1      | 3.13%   |
| Patriot             | 1         | 1      | 3.13%   |
| OCZ                 | 1         | 1      | 3.13%   |
| Micron Technology   | 1         | 1      | 3.13%   |
| Intel               | 1         | 1      | 3.13%   |
| HGST                | 1         | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 10     | 38.1%   |
| WDC                 | 4         | 4      | 19.05%  |
| Hitachi             | 4         | 4      | 19.05%  |
| Maxtor              | 2         | 2      | 9.52%   |
| Toshiba             | 1         | 1      | 4.76%   |
| Samsung Electronics | 1         | 2      | 4.76%   |
| HGST                | 1         | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 24     | 64.52%  |
| SSD  | 10        | 11     | 32.26%  |
| NVMe | 1         | 1      | 3.23%   |

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
| Works    | 188       | 337    | 85.45%  |
| Malfunc  | 31        | 36     | 14.09%  |
| Detected | 1         | 4      | 0.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 140       | 53.85%  |
| AMD                            | 42        | 16.15%  |
| Samsung Electronics            | 24        | 9.23%   |
| SanDisk                        | 9         | 3.46%   |
| Phison Electronics             | 8         | 3.08%   |
| Nvidia                         | 5         | 1.92%   |
| Micron/Crucial Technology      | 4         | 1.54%   |
| Kingston Technology Company    | 4         | 1.54%   |
| Toshiba                        | 3         | 1.15%   |
| SK hynix                       | 3         | 1.15%   |
| ASMedia Technology             | 3         | 1.15%   |
| Marvell Technology Group       | 2         | 0.77%   |
| Solid State Storage Technology | 1         | 0.38%   |
| Silicon Motion                 | 1         | 0.38%   |
| Seagate Technology             | 1         | 0.38%   |
| OCZ Technology Group           | 1         | 0.38%   |
| Micron Technology              | 1         | 0.38%   |
| KIOXIA                         | 1         | 0.38%   |
| JMicron Technology             | 1         | 0.38%   |
| Integrated Technology Express  | 1         | 0.38%   |
| HighPoint Technologies         | 1         | 0.38%   |
| Broadcom / LSI                 | 1         | 0.38%   |
| Biwin Storage Technology       | 1         | 0.38%   |
| ADATA Technology               | 1         | 0.38%   |
| Adaptec                        | 1         | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 36        | 12.54%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 16        | 5.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 14        | 4.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 13        | 4.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 11        | 3.83%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 11        | 3.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 3.83%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 2.79%   |
| Intel SATA Controller [RAID mode]                                              | 7         | 2.44%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 2.09%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 1.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 1.74%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 5         | 1.74%   |
| Unknown                                                                        | 5         | 1.74%   |
| Nvidia MCP79 AHCI Controller                                                   | 4         | 1.39%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 1.39%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.39%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 1.39%   |
| Phison PS5013 E13 NVMe Controller                                              | 3         | 1.05%   |
| Phison E16 PCIe4 NVMe Controller                                               | 3         | 1.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.05%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 1.05%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 3         | 1.05%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 3         | 1.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 1.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 1.05%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 1.05%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 1.05%   |
| AMD FCH SATA Controller [IDE mode]                                             | 3         | 1.05%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 1.05%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 2         | 0.7%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 0.7%    |
| SanDisk unknown                                                                | 2         | 0.7%    |
| SanDisk PC SN520 NVMe SSD                                                      | 2         | 0.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.7%    |
| Phison E12 NVMe Controller                                                     | 2         | 0.7%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 0.7%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 2         | 0.7%    |
| Intel SSD 660P Series                                                          | 2         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 162       | 62.79%  |
| NVMe | 60        | 23.26%  |
| RAID | 19        | 7.36%   |
| IDE  | 14        | 5.43%   |
| SCSI | 2         | 0.78%   |
| SAS  | 1         | 0.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 158       | 76.33%  |
| AMD    | 49        | 23.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 2.42%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 5         | 2.42%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 1.93%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 1.93%   |
| Intel Core 2 Duo                              | 4         | 1.93%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 1.45%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 1.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.45%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 1.45%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz          | 3         | 1.45%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 3         | 1.45%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 3         | 1.45%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 3         | 1.45%   |
| Intel Core i9-10980HK CPU @ 2.40GHz           | 2         | 0.97%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 0.97%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.97%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.97%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 2         | 0.97%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.97%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 0.97%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.97%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 0.97%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 2         | 0.97%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.97%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 0.97%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.97%   |
| Intel Core i5-2520M CPU @ 2.50GH              | 2         | 0.97%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 2         | 0.97%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 0.97%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.97%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 2         | 0.97%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 0.97%   |
| AMD Ryzen 5 3450U with Radeon Vega Mobile Gfx | 2         | 0.97%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 2         | 0.97%   |
| Intel Xeon E-2236 CPU @ 3.40GHz               | 1         | 0.48%   |
| Intel Xeon CPU W3680 @ 3.33GHz                | 1         | 0.48%   |
| Intel Xeon CPU E5-2650 v4 @ 2.20GHz           | 1         | 0.48%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz            | 1         | 0.48%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GH             | 1         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 66        | 31.88%  |
| Intel Core i7           | 46        | 22.22%  |
| AMD Ryzen 5             | 15        | 7.25%   |
| AMD Ryzen 7             | 14        | 6.76%   |
| Intel Core i3           | 12        | 5.8%    |
| Intel Core 2 Duo        | 12        | 5.8%    |
| Intel Xeon              | 6         | 2.9%    |
| Intel Celeron           | 4         | 1.93%   |
| AMD Ryzen 3             | 4         | 1.93%   |
| Other                   | 3         | 1.45%   |
| Intel Core i9           | 3         | 1.45%   |
| AMD Ryzen 9             | 3         | 1.45%   |
| AMD A6                  | 3         | 1.45%   |
| Intel Pentium           | 2         | 0.97%   |
| Intel Core 2 Quad       | 2         | 0.97%   |
| AMD E1                  | 2         | 0.97%   |
| AMD A4                  | 2         | 0.97%   |
| Intel Pentium Dual-Core | 1         | 0.48%   |
| Intel Genuine           | 1         | 0.48%   |
| Intel Core 2            | 1         | 0.48%   |
| AMD Ryzen 3 PRO         | 1         | 0.48%   |
| AMD E2                  | 1         | 0.48%   |
| AMD Athlon X4           | 1         | 0.48%   |
| AMD Athlon              | 1         | 0.48%   |
| AMD A10                 | 1         | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 75        | 36.23%  |
| 4       | 68        | 32.85%  |
| 6       | 14        | 6.76%   |
| 16      | 12        | 5.8%    |
| 8       | 12        | 5.8%    |
| 12      | 11        | 5.31%   |
| Unknown | 10        | 4.83%   |
| 32      | 2         | 0.97%   |
| 24      | 2         | 0.97%   |
| 10      | 1         | 0.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 201       | 97.1%   |
| 2      | 6         | 2.9%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 117       | 56.52%  |
| 1       | 80        | 38.65%  |
| Unknown | 10        | 4.83%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 39        | 18.84%  |
| Haswell     | 23        | 11.11%  |
| IvyBridge   | 21        | 10.14%  |
| SandyBridge | 18        | 8.7%    |
| Zen+        | 15        | 7.25%   |
| Penryn      | 15        | 7.25%   |
| Skylake     | 13        | 6.28%   |
| Zen 2       | 11        | 5.31%   |
| Broadwell   | 8         | 3.86%   |
| Zen 3       | 6         | 2.9%    |
| CometLake   | 6         | 2.9%    |
| Westmere    | 4         | 1.93%   |
| Zen         | 3         | 1.45%   |
| IceLake     | 3         | 1.45%   |
| Excavator   | 3         | 1.45%   |
| Core        | 3         | 1.45%   |
| Unknown     | 3         | 1.45%   |
| Puma        | 2         | 0.97%   |
| Piledriver  | 2         | 0.97%   |
| Goldmont    | 2         | 0.97%   |
| TigerLake   | 1         | 0.48%   |
| Silvermont  | 1         | 0.48%   |
| Nehalem     | 1         | 0.48%   |
| K10 Llano   | 1         | 0.48%   |
| K10         | 1         | 0.48%   |
| Jaguar      | 1         | 0.48%   |
| Bobcat      | 1         | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 123       | 51.04%  |
| Nvidia            | 74        | 30.71%  |
| AMD               | 43        | 17.84%  |
| ASPEED Technology | 1         | 0.41%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                            | 15        | 6.07%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 14        | 5.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 12        | 4.86%   |
| Intel UHD Graphics 620                                                      | 7         | 2.83%   |
| Intel HD Graphics 620                                                       | 7         | 2.83%   |
| Intel HD Graphics 5500                                                      | 7         | 2.83%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 7         | 2.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 7         | 2.83%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 6         | 2.43%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 5         | 2.02%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5         | 2.02%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4         | 1.62%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4         | 1.62%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 4         | 1.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4         | 1.62%   |
| Intel HD Graphics 530                                                       | 4         | 1.62%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 1.21%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3         | 1.21%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3         | 1.21%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 3         | 1.21%   |
| Nvidia C79 [GeForce 9400M]                                                  | 3         | 1.21%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 3         | 1.21%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 3         | 1.21%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 3         | 1.21%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 3         | 1.21%   |
| Intel HD Graphics 630                                                       | 3         | 1.21%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 3         | 1.21%   |
| AMD Lucienne                                                                | 3         | 1.21%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3         | 1.21%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2         | 0.81%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 0.81%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2         | 0.81%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2         | 0.81%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2         | 0.81%   |
| Nvidia GF108GLM [NVS 5200M]                                                 | 2         | 0.81%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2         | 0.81%   |
| Intel HD Graphics 500                                                       | 2         | 0.81%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 0.81%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 0.81%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 2         | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 84        | 40.58%  |
| 1 x Nvidia      | 42        | 20.29%  |
| 1 x AMD         | 37        | 17.87%  |
| Intel + Nvidia  | 28        | 13.53%  |
| 2 x Intel       | 8         | 3.86%   |
| Intel + AMD     | 3         | 1.45%   |
| AMD + Nvidia    | 2         | 0.97%   |
| 2 x Nvidia      | 1         | 0.48%   |
| 2 x AMD         | 1         | 0.48%   |
| Nvidia + ASPEED | 1         | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 164       | 78.85%  |
| Proprietary | 44        | 21.15%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 151       | 71.9%   |
| 1.01-2.0   | 16        | 7.62%   |
| 0.51-1.0   | 12        | 5.71%   |
| 7.01-8.0   | 10        | 4.76%   |
| 3.01-4.0   | 10        | 4.76%   |
| 0.01-0.5   | 8         | 3.81%   |
| 5.01-6.0   | 1         | 0.48%   |
| 2.01-3.0   | 1         | 0.48%   |
| 8.01-16.0  | 1         | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 24        | 12.06%  |
| Samsung Electronics     | 23        | 11.56%  |
| Chimei Innolux          | 23        | 11.56%  |
| AU Optronics            | 22        | 11.06%  |
| Dell                    | 15        | 7.54%   |
| BOE                     | 11        | 5.53%   |
| BenQ                    | 9         | 4.52%   |
| Goldstar                | 8         | 4.02%   |
| Philips                 | 6         | 3.02%   |
| Lenovo                  | 6         | 3.02%   |
| Hewlett-Packard         | 5         | 2.51%   |
| Acer                    | 5         | 2.51%   |
| Ancor Communications    | 4         | 2.01%   |
| LG Electronics          | 3         | 1.51%   |
| Iiyama                  | 3         | 1.51%   |
| Fujitsu Siemens         | 3         | 1.51%   |
| AOC                     | 3         | 1.51%   |
| Vizio                   | 2         | 1.01%   |
| ViewSonic               | 2         | 1.01%   |
| PANDA                   | 2         | 1.01%   |
| Panasonic               | 2         | 1.01%   |
| InfoVision              | 2         | 1.01%   |
| ASUSTek Computer        | 2         | 1.01%   |
| ___                     | 1         | 0.5%    |
| WYT                     | 1         | 0.5%    |
| Toshiba                 | 1         | 0.5%    |
| SAC                     | 1         | 0.5%    |
| Pixio                   | 1         | 0.5%    |
| OEM                     | 1         | 0.5%    |
| Mi                      | 1         | 0.5%    |
| Idek Iiyama             | 1         | 0.5%    |
| IBM                     | 1         | 0.5%    |
| HannStar                | 1         | 0.5%    |
| CSO                     | 1         | 0.5%    |
| Chi Mei Optoelectronics | 1         | 0.5%    |
| CHD                     | 1         | 0.5%    |
| Apple                   | 1         | 0.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 2         | 0.98%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 300x170mm 13.6-inch   | 2         | 0.98%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch   | 2         | 0.98%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 290x170mm 13.2-inch  | 2         | 0.98%   |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch               | 2         | 0.98%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch           | 2         | 0.98%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch            | 2         | 0.98%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch            | 2         | 0.98%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch            | 2         | 0.98%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch            | 2         | 0.98%   |
| LG Display LCD Monitor LGD01E9 1920x1080 350x190mm 15.7-inch           | 2         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch       | 2         | 0.98%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch       | 2         | 0.98%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch       | 2         | 0.98%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch        | 2         | 0.98%   |
| BenQ EX3203R BNQ7F66 2560x1440 700x390mm 31.5-inch                     | 2         | 0.98%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 290x160mm 13.0-inch         | 2         | 0.98%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch          | 2         | 0.98%   |
| ___ MY TV LED TV ___0101 1920x1080                                     | 1         | 0.49%   |
| WYT MNT-ANALOG WYT0323 1280x1024 330x270mm 16.8-inch                   | 1         | 0.49%   |
| Vizio E320i-B2 VIZ1002 1360x768 700x400mm 31.7-inch                    | 1         | 0.49%   |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                    | 1         | 0.49%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 700x390mm 31.5-inch              | 1         | 0.49%   |
| ViewSonic LCD Monitor VA1938 Series                                    | 1         | 0.49%   |
| Toshiba TV TSB010F 1920x1080 890x500mm 40.2-inch                       | 1         | 0.49%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch      | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch   | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch   | 1         | 0.49%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 600x340mm 27.2-inch    | 1         | 0.49%   |
| Samsung Electronics SMBX2231 SAM076D 1920x1080 480x270mm 21.7-inch     | 1         | 0.49%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 480x270mm 21.7-inch  | 1         | 0.49%   |
| Samsung Electronics S24E650 SAM0CC1 1920x1200 520x320mm 24.0-inch      | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch   | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch   | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch   | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch   | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 310x170mm 13.9-inch   | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch | 1         | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 88        | 44.44%  |
| 1366x768 (WXGA)    | 42        | 21.21%  |
| 2560x1440 (QHD)    | 14        | 7.07%   |
| 1600x900 (HD+)     | 12        | 6.06%   |
| 3840x2160 (4K)     | 9         | 4.55%   |
| 1680x1050 (WSXGA+) | 5         | 2.53%   |
| 1280x1024 (SXGA)   | 5         | 2.53%   |
| 2560x1080          | 3         | 1.52%   |
| 1440x900 (WXGA+)   | 3         | 1.52%   |
| Unknown            | 3         | 1.52%   |
| 3840x1600          | 2         | 1.01%   |
| 2880x1620          | 2         | 1.01%   |
| 1360x768           | 2         | 1.01%   |
| 1280x800 (WXGA)    | 2         | 1.01%   |
| 5120x1440          | 1         | 0.51%   |
| 3200x1080          | 1         | 0.51%   |
| 2880x1800          | 1         | 0.51%   |
| 2806x900           | 1         | 0.51%   |
| 1920x540           | 1         | 0.51%   |
| 1920x1200 (WUXGA)  | 1         | 0.51%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 53        | 26.5%   |
| 13      | 33        | 16.5%   |
| 27      | 15        | 7.5%    |
| 21      | 14        | 7%      |
| 24      | 13        | 6.5%    |
| 23      | 11        | 5.5%    |
| Unknown | 11        | 5.5%    |
| 19      | 8         | 4%      |
| 17      | 8         | 4%      |
| 12      | 6         | 3%      |
| 31      | 5         | 2.5%    |
| 22      | 4         | 2%      |
| 14      | 4         | 2%      |
| 11      | 3         | 1.5%    |
| 54      | 2         | 1%      |
| 40      | 2         | 1%      |
| 34      | 2         | 1%      |
| 16      | 2         | 1%      |
| 65      | 1         | 0.5%    |
| 39      | 1         | 0.5%    |
| 37      | 1         | 0.5%    |
| 32      | 1         | 0.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 78        | 39.59%  |
| 501-600     | 35        | 17.77%  |
| 401-500     | 23        | 11.68%  |
| 201-300     | 23        | 11.68%  |
| Unknown     | 11        | 5.58%   |
| 351-400     | 9         | 4.57%   |
| 601-700     | 8         | 4.06%   |
| 801-900     | 4         | 2.03%   |
| 701-800     | 3         | 1.52%   |
| 1001-1500   | 3         | 1.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 151       | 82.07%  |
| 16/10   | 15        | 8.15%   |
| Unknown | 8         | 4.35%   |
| 5/4     | 4         | 2.17%   |
| 21/9    | 3         | 1.63%   |
| 6/5     | 1         | 0.54%   |
| 32/9    | 1         | 0.54%   |
| 3/2     | 1         | 0.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 42        | 21.11%  |
| 201-250        | 38        | 19.1%   |
| 81-90          | 27        | 13.57%  |
| 301-350        | 15        | 7.54%   |
| 101-110        | 11        | 5.53%   |
| Unknown        | 11        | 5.53%   |
| 71-80          | 10        | 5.03%   |
| 151-200        | 9         | 4.52%   |
| 351-500        | 8         | 4.02%   |
| 61-70          | 6         | 3.02%   |
| 121-130        | 6         | 3.02%   |
| 501-1000       | 4         | 2.01%   |
| More than 1000 | 3         | 1.51%   |
| 51-60          | 3         | 1.51%   |
| 251-300        | 2         | 1.01%   |
| 141-150        | 2         | 1.01%   |
| 131-140        | 1         | 0.5%    |
| 111-120        | 1         | 0.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 59        | 29.8%   |
| 121-160       | 55        | 27.78%  |
| 101-120       | 53        | 26.77%  |
| 161-240       | 17        | 8.59%   |
| Unknown       | 11        | 5.56%   |
| 1-50          | 2         | 1.01%   |
| More than 240 | 1         | 0.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 154       | 72.99%  |
| 0     | 30        | 14.22%  |
| 2     | 27        | 12.8%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 124       | 39.62%  |
| Realtek Semiconductor                 | 85        | 27.16%  |
| Qualcomm Atheros                      | 39        | 12.46%  |
| Broadcom                              | 21        | 6.71%   |
| TP-Link                               | 7         | 2.24%   |
| Nvidia                                | 5         | 1.6%    |
| Ericsson Business Mobile Networks     | 4         | 1.28%   |
| Ralink Technology                     | 3         | 0.96%   |
| ASUSTek Computer                      | 3         | 0.96%   |
| Samsung Electronics                   | 2         | 0.64%   |
| Ralink                                | 2         | 0.64%   |
| Qualcomm Atheros Communications       | 2         | 0.64%   |
| Qualcomm                              | 2         | 0.64%   |
| Marvell Technology Group              | 2         | 0.64%   |
| Generic                               | 2         | 0.64%   |
| Edimax Technology                     | 2         | 0.64%   |
| Xiaomi                                | 1         | 0.32%   |
| Sierra Wireless                       | 1         | 0.32%   |
| OnePlus Technology (Shenzhen)         | 1         | 0.32%   |
| Microchip Technology                  | 1         | 0.32%   |
| Hewlett-Packard                       | 1         | 0.32%   |
| Fibocom                               | 1         | 0.32%   |
| Aquantia                              | 1         | 0.32%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 59        | 15.32%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 4.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 3.12%   |
| Intel Wi-Fi 6 AX200                                               | 11        | 2.86%   |
| Intel I211 Gigabit Network Connection                             | 11        | 2.86%   |
| Intel Wireless 8265 / 8275                                        | 10        | 2.6%    |
| Intel Wireless 7265                                               | 10        | 2.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 2.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 1.82%   |
| Intel Wireless 8260                                               | 7         | 1.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 1.82%   |
| Intel Wireless 7260                                               | 6         | 1.56%   |
| Intel Ethernet Connection (2) I219-V                              | 6         | 1.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 5         | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 1.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.04%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.04%   |
| Nvidia MCP79 Ethernet                                             | 4         | 1.04%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 1.04%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 1.04%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 3         | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.78%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 3         | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.78%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.78%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.78%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.78%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.52%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.52%   |
| Ralink RT5370 Wireless Adapter                                    | 2         | 0.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.52%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 95        | 53.98%  |
| Qualcomm Atheros                      | 30        | 17.05%  |
| Realtek Semiconductor                 | 20        | 11.36%  |
| Broadcom                              | 10        | 5.68%   |
| TP-Link                               | 7         | 3.98%   |
| Ralink Technology                     | 3         | 1.7%    |
| ASUSTek Computer                      | 3         | 1.7%    |
| Ralink                                | 2         | 1.14%   |
| Qualcomm Atheros Communications       | 2         | 1.14%   |
| Edimax Technology                     | 2         | 1.14%   |
| Sierra Wireless                       | 1         | 0.57%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 11        | 6.21%   |
| Intel Wireless 8265 / 8275                                     | 10        | 5.65%   |
| Intel Wireless 7265                                            | 10        | 5.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8         | 4.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 4.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 7         | 3.95%   |
| Intel Wireless 8260                                            | 7         | 3.95%   |
| Intel Wireless 7260                                            | 6         | 3.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 3.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 5         | 2.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 2.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 2.26%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 2.26%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 3         | 1.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.69%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 3         | 1.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 1.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 1.13%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.13%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 1.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 1.13%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 1.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.13%   |
| Intel Wireless-AC 9260                                         | 2         | 1.13%   |
| Intel Wireless 3165                                            | 2         | 1.13%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 2         | 1.13%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.13%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.13%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 1.13%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 1.13%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2         | 1.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 1.13%   |
| TP-Link TP-LINK Wireless USB Adapter                           | 1         | 0.56%   |
| TP-Link TP-Link High Power Wireless USB Adapter                | 1         | 0.56%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.56%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 80        | 41.24%  |
| Realtek Semiconductor         | 75        | 38.66%  |
| Broadcom                      | 13        | 6.7%    |
| Qualcomm Atheros              | 12        | 6.19%   |
| Nvidia                        | 5         | 2.58%   |
| Samsung Electronics           | 2         | 1.03%   |
| Qualcomm                      | 2         | 1.03%   |
| Marvell Technology Group      | 2         | 1.03%   |
| Xiaomi                        | 1         | 0.52%   |
| OnePlus Technology (Shenzhen) | 1         | 0.52%   |
| Aquantia                      | 1         | 0.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 59        | 29.95%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 8.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 6.09%   |
| Intel I211 Gigabit Network Connection                             | 11        | 5.58%   |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 3.55%   |
| Intel Ethernet Connection (2) I219-V                              | 6         | 3.05%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 2.54%   |
| Nvidia MCP79 Ethernet                                             | 4         | 2.03%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 2.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.52%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.52%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.52%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 1.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.02%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.02%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 2         | 1.02%   |
| Intel I350 Gigabit Network Connection                             | 2         | 1.02%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 2         | 1.02%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.02%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.02%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.02%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.02%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 1.02%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2         | 1.02%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.51%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.51%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.51%   |
| OnePlus (Shenzhen) OnePlus RNDIS Control RNDIS Ethernet Data      | 1         | 0.51%   |
| Nvidia MCP73 Ethernet                                             | 1         | 0.51%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.51%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.51%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 187       | 52.09%  |
| WiFi     | 161       | 44.85%  |
| Modem    | 7         | 1.95%   |
| Unknown  | 4         | 1.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 161       | 58.76%  |
| WiFi     | 110       | 40.15%  |
| Modem    | 3         | 1.09%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 129       | 62.32%  |
| 1     | 70        | 33.82%  |
| 3     | 6         | 2.9%    |
| 5     | 1         | 0.48%   |
| 4     | 1         | 0.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 206       | 99.52%  |
| Yes  | 1         | 0.48%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 69        | 56.1%   |
| Realtek Semiconductor           | 8         | 6.5%    |
| Broadcom                        | 8         | 6.5%    |
| Qualcomm Atheros Communications | 7         | 5.69%   |
| Lite-On Technology              | 7         | 5.69%   |
| Apple                           | 6         | 4.88%   |
| IMC Networks                    | 5         | 4.07%   |
| Dell                            | 5         | 4.07%   |
| Cambridge Silicon Radio         | 2         | 1.63%   |
| ASUSTek Computer                | 2         | 1.63%   |
| Alps Electric                   | 2         | 1.63%   |
| Toshiba                         | 1         | 0.81%   |
| HTC (High Tech Computer)        | 1         | 0.81%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 32        | 26.02%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 12        | 9.76%   |
| Intel AX200 Bluetooth                                                | 10        | 8.13%   |
| Intel AX201 Bluetooth                                                | 6         | 4.88%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 5         | 4.07%   |
| Apple Bluetooth Host Controller                                      | 5         | 4.07%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 4         | 3.25%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 3         | 2.44%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 3         | 2.44%   |
| Lite-On Atheros AR3012 Bluetooth                                     | 3         | 2.44%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                          | 3         | 2.44%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 3         | 2.44%   |
| Realtek Bluetooth Radio                                              | 2         | 1.63%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                              | 2         | 1.63%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device          | 2         | 1.63%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2         | 1.63%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 2         | 1.63%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                    | 2         | 1.63%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 2         | 1.63%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2         | 1.63%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 2         | 1.63%   |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip                      | 1         | 0.81%   |
| Realtek RTL8723B Bluetooth                                           | 1         | 0.81%   |
| Realtek  Bluetooth Adapter                                           | 1         | 0.81%   |
| Lite-On Broadcom Bluetooth 4.0 USB                                   | 1         | 0.81%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                          | 1         | 0.81%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0                   | 1         | 0.81%   |
| IMC Networks Bluetooth Module                                        | 1         | 0.81%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 0.81%   |
| Dell Wireless 355 Bluetooth                                          | 1         | 0.81%   |
| Dell DW375 Bluetooth Module                                          | 1         | 0.81%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                   | 1         | 0.81%   |
| ASUS Realtek Bluetooth 4.0 + High Speed Chip                         | 1         | 0.81%   |
| ASUS ASUS USB-BT500                                                  | 1         | 0.81%   |
| Apple Bluetooth USB Host Controller                                  | 1         | 0.81%   |
| Alps Electric UGTZ4 Bluetooth                                        | 1         | 0.81%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)                      | 1         | 0.81%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 149       | 53.02%  |
| AMD                   | 56        | 19.93%  |
| Nvidia                | 51        | 18.15%  |
| Logitech              | 4         | 1.42%   |
| C-Media Electronics   | 4         | 1.42%   |
| VIA Technologies      | 2         | 0.71%   |
| SteelSeries ApS       | 2         | 0.71%   |
| RODE Microphones      | 2         | 0.71%   |
| Creative Labs         | 2         | 0.71%   |
| Corsair               | 2         | 0.71%   |
| Realtek Semiconductor | 1         | 0.36%   |
| Nam Tai E&E Products  | 1         | 0.36%   |
| JMTek                 | 1         | 0.36%   |
| Focusrite-Novation    | 1         | 0.36%   |
| DSEA A/S              | 1         | 0.36%   |
| Creative Technology   | 1         | 0.36%   |
| Cambridge Audio       | 1         | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                   | 21        | 6.14%   |
| Intel Sunrise Point-LP HD Audio                                                       | 19        | 5.56%   |
| AMD Family 17h/19h HD Audio Controller                                                | 17        | 4.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller            | 16        | 4.68%   |
| Intel Haswell-ULT HD Audio Controller                                                 | 12        | 3.51%   |
| Intel 8 Series HD Audio Controller                                                    | 12        | 3.51%   |
| AMD Starship/Matisse HD Audio Controller                                              | 11        | 3.22%   |
| Intel Cannon Lake PCH cAVS                                                            | 10        | 2.92%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                   | 10        | 2.92%   |
| AMD Renoir Radeon High Definition Audio Controller                                    | 9         | 2.63%   |
| Intel Comet Lake PCH-LP cAVS                                                          | 8         | 2.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                   | 8         | 2.34%   |
| Nvidia GP107GL High Definition Audio Controller                                       | 7         | 2.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                      | 7         | 2.05%   |
| Intel Wildcat Point-LP High Definition Audio Controller                               | 7         | 2.05%   |
| Intel Broadwell-U Audio Controller                                                    | 7         | 2.05%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                        | 7         | 2.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                   | 7         | 2.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                       | 7         | 2.05%   |
| Nvidia GP104 High Definition Audio Controller                                         | 6         | 1.75%   |
| Nvidia GK107 HDMI Audio Controller                                                    | 6         | 1.75%   |
| AMD FCH Azalia Controller                                                             | 6         | 1.75%   |
| Intel 200 Series PCH HD Audio                                                         | 5         | 1.46%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                            | 5         | 1.46%   |
| Nvidia MCP79 High Definition Audio                                                    | 4         | 1.17%   |
| Nvidia GP108 High Definition Audio Controller                                         | 4         | 1.17%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                      | 4         | 1.17%   |
| AMD Kabini HDMI/DP Audio                                                              | 4         | 1.17%   |
| Nvidia TU106 High Definition Audio Controller                                         | 3         | 0.88%   |
| Nvidia GM206 High Definition Audio Controller                                         | 3         | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                         | 3         | 0.88%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                             | 3         | 0.88%   |
| Intel Comet Lake PCH cAVS                                                             | 3         | 0.88%   |
| Intel 9 Series Chipset Family HD Audio Controller                                     | 3         | 0.88%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                        | 3         | 0.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                              | 3         | 0.88%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                      | 3         | 0.88%   |
| SteelSeries ApS SteelSeries Arctis 7 Arctis 7 Chat Arctis 7 Game SteelSeries Arctis 7 | 2         | 0.58%   |
| RODE Microphones RDE NT-USB Mini                                                      | 2         | 0.58%   |
| Nvidia TU104 HD Audio Controller                                                      | 2         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 61        | 24.21%  |
| SK hynix            | 53        | 21.03%  |
| Kingston            | 27        | 10.71%  |
| Micron Technology   | 16        | 6.35%   |
| G.Skill             | 15        | 5.95%   |
| Crucial             | 15        | 5.95%   |
| Corsair             | 15        | 5.95%   |
| Unknown             | 14        | 5.56%   |
| Elpida              | 7         | 2.78%   |
| A-DATA Technology   | 4         | 1.59%   |
| Unknown             | 4         | 1.59%   |
| Nanya Technology    | 3         | 1.19%   |
| Unknown (ABCD)      | 2         | 0.79%   |
| Transcend           | 2         | 0.79%   |
| Ramaxel Technology  | 2         | 0.79%   |
| Goodram             | 2         | 0.79%   |
| Undefined-00BA      | 1         | 0.4%    |
| TIMETEC             | 1         | 0.4%    |
| Team                | 1         | 0.4%    |
| Smart               | 1         | 0.4%    |
| S                   | 1         | 0.4%    |
| Neo Forza           | 1         | 0.4%    |
| Kingmax             | 1         | 0.4%    |
| Avant               | 1         | 0.4%    |
| Apacer              | 1         | 0.4%    |
| 09490000802C        | 1         | 0.4%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 3.47%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 2.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 1.93%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.93%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 5         | 1.93%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s            | 5         | 1.93%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.54%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.54%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.54%   |
| Unknown                                                          | 4         | 1.54%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 3         | 1.16%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s              | 3         | 1.16%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.77%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2133MT/s | 2         | 0.77%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s             | 2         | 0.77%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.77%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.77%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.77%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.77%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 2         | 0.77%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.77%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.77%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.77%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 2         | 0.77%   |
| Micron RAM Module 8GB SODIMM DDR3 1600MT/s                       | 2         | 0.77%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 2         | 0.77%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s              | 2         | 0.77%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1333MT/s            | 2         | 0.77%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 2         | 0.77%   |
| Unknown SODIMM 4GB SODIMM 800MT/s                                | 1         | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.39%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 0.39%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.39%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 1         | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                        | 1         | 0.39%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 1         | 0.39%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 0.39%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 1         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 95        | 45.02%  |
| DDR3    | 95        | 45.02%  |
| DDR2    | 7         | 3.32%   |
| LPDDR4  | 4         | 1.9%    |
| Unknown | 4         | 1.9%    |
| LPDDR3  | 3         | 1.42%   |
| DDR     | 3         | 1.42%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 137       | 65.24%  |
| DIMM         | 66        | 31.43%  |
| Row Of Chips | 6         | 2.86%   |
| Chip         | 1         | 0.48%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 95        | 42.41%  |
| 4096  | 83        | 37.05%  |
| 16384 | 22        | 9.82%   |
| 2048  | 19        | 8.48%   |
| 32768 | 4         | 1.79%   |
| 1024  | 1         | 0.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 63        | 27.88%  |
| 2667    | 32        | 14.16%  |
| 2400    | 26        | 11.5%   |
| 3200    | 24        | 10.62%  |
| 1333    | 19        | 8.41%   |
| 2133    | 17        | 7.52%   |
| 1334    | 10        | 4.42%   |
| 800     | 8         | 3.54%   |
| 1067    | 5         | 2.21%   |
| 2666    | 4         | 1.77%   |
| Unknown | 4         | 1.77%   |
| 1867    | 3         | 1.33%   |
| 667     | 3         | 1.33%   |
| 4266    | 2         | 0.88%   |
| 3600    | 2         | 0.88%   |
| 3333    | 1         | 0.44%   |
| 3066    | 1         | 0.44%   |
| 3000    | 1         | 0.44%   |
| 1066    | 1         | 0.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| HP HP Laser 107w   | 1         | 50%     |
| Brother MFC-J485DW | 1         | 50%     |

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
| Chicony Electronics                    | 26        | 23.64%  |
| Realtek Semiconductor                  | 13        | 11.82%  |
| Microdia                               | 12        | 10.91%  |
| IMC Networks                           | 11        | 10%     |
| Acer                                   | 9         | 8.18%   |
| Quanta                                 | 6         | 5.45%   |
| Logitech                               | 6         | 5.45%   |
| Suyin                                  | 5         | 4.55%   |
| Sunplus Innovation Technology          | 4         | 3.64%   |
| Alcor Micro                            | 4         | 3.64%   |
| Silicon Motion                         | 2         | 1.82%   |
| Ricoh                                  | 2         | 1.82%   |
| Lite-On Technology                     | 2         | 1.82%   |
| Xiongmai                               | 1         | 0.91%   |
| Trust                                  | 1         | 0.91%   |
| Syntek                                 | 1         | 0.91%   |
| OmniVision Technologies                | 1         | 0.91%   |
| Luxvisions Innotech Limited            | 1         | 0.91%   |
| Lenovo                                 | 1         | 0.91%   |
| Importek                               | 1         | 0.91%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 0.91%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Acer Integrated Camera                   | 7         | 6.31%   |
| Chicony Integrated Camera                | 6         | 5.41%   |
| Microdia Integrated_Webcam_HD            | 5         | 4.5%    |
| Microdia Integrated Webcam               | 5         | 4.5%    |
| Realtek Integrated_Webcam_HD             | 4         | 3.6%    |
| IMC Networks Integrated Camera           | 4         | 3.6%    |
| Logitech HD Pro Webcam C920              | 3         | 2.7%    |
| Chicony USB2.0 HD UVC WebCam             | 3         | 2.7%    |
| Chicony Integrated Camera (1280x720@30)  | 3         | 2.7%    |
| Chicony HD WebCam                        | 3         | 2.7%    |
| Chicony Chicony USB2.0 Camera            | 3         | 2.7%    |
| Suyin Acer/HP Integrated Webcam [CN0314] | 2         | 1.8%    |
| Sunplus Laptop_Integrated_Webcam_FHD     | 2         | 1.8%    |
| Realtek Lenovo EasyCamera                | 2         | 1.8%    |
| Realtek Integrated Webcam HD             | 2         | 1.8%    |
| Realtek Front Camera                     | 2         | 1.8%    |
| Quanta VGA WebCam                        | 2         | 1.8%    |
| Quanta HP TrueVision HD Camera           | 2         | 1.8%    |
| IMC Networks USB2.0 VGA UVC WebCam       | 2         | 1.8%    |
| IMC Networks USB2.0 HD UVC WebCam        | 2         | 1.8%    |
| Xiongmai web camera                      | 1         | 0.9%    |
| Trust Trust USB Camera                   | 1         | 0.9%    |
| Syntek Lenovo EasyCamera                 | 1         | 0.9%    |
| Suyin RGBIR Camera                       | 1         | 0.9%    |
| Suyin Integrated_Webcam_HD               | 1         | 0.9%    |
| Suyin HD WebCam                          | 1         | 0.9%    |
| Sunplus MTD camera                       | 1         | 0.9%    |
| Sunplus Integrated_Webcam_HD             | 1         | 0.9%    |
| Silicon Motion WebCam SC-13HDL11939N     | 1         | 0.9%    |
| Silicon Motion Realtek USB2.0 PC Camera  | 1         | 0.9%    |
| Ricoh USB2.0 Camera                      | 1         | 0.9%    |
| Ricoh HD Webcam                          | 1         | 0.9%    |
| Realtek USB Camera                       | 1         | 0.9%    |
| Realtek Realtek USB2.0 PC Camera         | 1         | 0.9%    |
| Realtek Realtek PC Camera                | 1         | 0.9%    |
| Quanta USB2.0 HD UVC WebCam              | 1         | 0.9%    |
| Quanta HP Universal Camera               | 1         | 0.9%    |
| OmniVision OV2640 Webcam                 | 1         | 0.9%    |
| Microdia Sonix Integrated Webcam         | 1         | 0.9%    |
| Microdia Laptop_Integrated_Webcam_HD     | 1         | 0.9%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 36.36%  |
| Upek                       | 3         | 13.64%  |
| Synaptics                  | 3         | 13.64%  |
| STMicroelectronics         | 2         | 9.09%   |
| Shenzhen Goodix Technology | 1         | 4.55%   |
| Next Biometrics            | 1         | 4.55%   |
| LighTuning Technology      | 1         | 4.55%   |
| Focal-systems.Corp         | 1         | 4.55%   |
| Broadcom                   | 1         | 4.55%   |
| AuthenTec                  | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 4         | 18.18%  |
| Validity Sensors Synaptics WBDI                                              | 2         | 9.09%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 9.09%   |
| STMicroelectronics Fingerprint Reader                                        | 2         | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 4.55%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 1         | 4.55%   |
| Upek TCS5B Fingerprint sensor                                                | 1         | 4.55%   |
| Synaptics  WBDI                                                              | 1         | 4.55%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 4.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 4.55%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 4.55%   |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 4.55%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 1         | 4.55%   |
| Focal-systems.Corp FocalTech Fingerprint reader                              | 1         | 4.55%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.55%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 4.55%   |

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
| 1     | 73        | 33.95%  |
| 2     | 62        | 28.84%  |
| 3     | 32        | 14.88%  |
| 0     | 26        | 12.09%  |
| 4     | 18        | 8.37%   |
| 5     | 4         | 1.86%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 135       | 37.5%   |
| Bluetooth                | 84        | 23.33%  |
| Net/wireless             | 47        | 13.06%  |
| Card reader              | 36        | 10%     |
| Fingerprint reader       | 23        | 6.39%   |
| Firewire controller      | 17        | 4.72%   |
| Network                  | 8         | 2.22%   |
| Storage                  | 4         | 1.11%   |
| Sound                    | 4         | 1.11%   |
| Net/ethernet             | 1         | 0.28%   |
| Modem                    | 1         | 0.28%   |

