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

Total: 226

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | Inspiron 15-7568            | [9e555f0b24](https://bsd-hardware.info/?probe=9e555f0b24) | Aug 24, 2023 |
| Dell          | Latitude 7490               | [0b05de2297](https://bsd-hardware.info/?probe=0b05de2297) | Aug 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [26995b5321](https://bsd-hardware.info/?probe=26995b5321) | Aug 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [1bc7f67754](https://bsd-hardware.info/?probe=1bc7f67754) | Aug 18, 2023 |
| Samsung       | Q210                        | [2e25c6d2ec](https://bsd-hardware.info/?probe=2e25c6d2ec) | Aug 03, 2023 |
| Samsung       | Q210                        | [d3c5ab902d](https://bsd-hardware.info/?probe=d3c5ab902d) | Aug 03, 2023 |
| ASUSTek       | X555LD                      | [9c0c41b663](https://bsd-hardware.info/?probe=9c0c41b663) | Jul 30, 2023 |
| Dell          | Inspiron 3180               | [e97b5d9219](https://bsd-hardware.info/?probe=e97b5d9219) | Jul 25, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [020e17c2f8](https://bsd-hardware.info/?probe=020e17c2f8) | Jul 23, 2023 |
| Toshiba       | Satellite L655              | [67080aeb1d](https://bsd-hardware.info/?probe=67080aeb1d) | Jul 20, 2023 |
| MSI           | Sword 17 A11UD              | [c9852c1ee3](https://bsd-hardware.info/?probe=c9852c1ee3) | Jul 19, 2023 |
| Lenovo        | ThinkPad W530 2447GW3       | [57b4bfc1bf](https://bsd-hardware.info/?probe=57b4bfc1bf) | Jul 17, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [826ba238d8](https://bsd-hardware.info/?probe=826ba238d8) | Jul 16, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [0273f2f271](https://bsd-hardware.info/?probe=0273f2f271) | Jul 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [03e83e60ca](https://bsd-hardware.info/?probe=03e83e60ca) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [3096d8532a](https://bsd-hardware.info/?probe=3096d8532a) | Jul 07, 2023 |
| Dell          | G3 3579                     | [8d9b29f231](https://bsd-hardware.info/?probe=8d9b29f231) | Jul 05, 2023 |
| Dell          | G3 3579                     | [f6fc15b1f4](https://bsd-hardware.info/?probe=f6fc15b1f4) | Jul 05, 2023 |
| HP            | 15                          | [4664b4c93f](https://bsd-hardware.info/?probe=4664b4c93f) | Jun 11, 2023 |
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


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GhostBSD 20.04.02 | 58        | 33.33%  |
| GhostBSD 21.08.27 | 29        | 16.67%  |
| GhostBSD 22.01.12 | 13        | 7.47%   |
| GhostBSD 22.06.18 | 10        | 5.75%   |
| GhostBSD 23.02.02 | 6         | 3.45%   |
| GhostBSD 23.07.13 | 4         | 2.3%    |
| GhostBSD 23.06.01 | 4         | 2.3%    |
| GhostBSD 23.07.29 | 3         | 1.72%   |
| GhostBSD 23.06.05 | 3         | 1.72%   |
| GhostBSD 22.06.26 | 3         | 1.72%   |
| GhostBSD 23.07.20 | 2         | 1.15%   |
| GhostBSD 23.05.22 | 2         | 1.15%   |
| GhostBSD 23.04.23 | 2         | 1.15%   |
| GhostBSD 23.03.17 | 2         | 1.15%   |
| GhostBSD 22.11.22 | 2         | 1.15%   |
| GhostBSD 22.11.02 | 2         | 1.15%   |
| GhostBSD 22.08.23 | 2         | 1.15%   |
| GhostBSD 22.08.06 | 2         | 1.15%   |
| GhostBSD 22.07.16 | 2         | 1.15%   |
| GhostBSD 23.07.04 | 1         | 0.57%   |
| GhostBSD 23.06.22 | 1         | 0.57%   |
| GhostBSD 23.05.18 | 1         | 0.57%   |
| GhostBSD 23.04.02 | 1         | 0.57%   |
| GhostBSD 23.01.13 | 1         | 0.57%   |
| GhostBSD 22.10.30 | 1         | 0.57%   |
| GhostBSD 22.09.16 | 1         | 0.57%   |
| GhostBSD 22.08.27 | 1         | 0.57%   |
| GhostBSD 22.07.31 | 1         | 0.57%   |
| GhostBSD 22.07.28 | 1         | 0.57%   |
| GhostBSD 22.07.13 | 1         | 0.57%   |
| GhostBSD 22.07.10 | 1         | 0.57%   |
| GhostBSD 22.06.20 | 1         | 0.57%   |
| GhostBSD 22.06.07 | 1         | 0.57%   |
| GhostBSD 22.05.13 | 1         | 0.57%   |
| GhostBSD 22.04.30 | 1         | 0.57%   |
| GhostBSD 22.04.22 | 1         | 0.57%   |
| GhostBSD 22.04.06 | 1         | 0.57%   |
| GhostBSD 21.12.29 | 1         | 0.57%   |
| GhostBSD 21.11.24 | 1         | 0.57%   |
| GhostBSD 20.07.14 | 1         | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| GhostBSD | 161       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 161       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| MATE         | 124       | 75.61%  |
| XFCE         | 27        | 16.46%  |
| KDE5         | 8         | 4.88%   |
| Cinnamon     | 2         | 1.22%   |
| helloDesktop | 1         | 0.61%   |
| GNOME        | 1         | 0.61%   |
| Console      | 1         | 0.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 159       | 98.76%  |
| Wayland | 1         | 0.62%   |
| Console | 1         | 0.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 158       | 98.14%  |
| SDDM    | 2         | 1.24%   |
| Console | 1         | 0.62%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 64        | 37.87%  |
| C       | 58        | 34.32%  |
| Unknown | 16        | 9.47%   |
| de_DE   | 8         | 4.73%   |
| pt_BR   | 4         | 2.37%   |
| en_GB   | 4         | 2.37%   |
| pl_PL   | 3         | 1.78%   |
| it_IT   | 3         | 1.78%   |
| ru_RU   | 2         | 1.18%   |
| es_ES   | 2         | 1.18%   |
| zh_CN   | 1         | 0.59%   |
| sv_SE   | 1         | 0.59%   |
| sk_SK   | 1         | 0.59%   |
| en_NZ   | 1         | 0.59%   |
| el_GR   | 1         | 0.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 127       | 78.88%  |
| BIOS | 34        | 21.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 153       | 92.73%  |
| Ufs  | 12        | 7.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 158       | 98.14%  |
| MBR  | 3         | 1.86%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 45        | 27.95%  |
| Dell                | 37        | 22.98%  |
| Hewlett-Packard     | 15        | 9.32%   |
| ASUSTek Computer    | 12        | 7.45%   |
| Acer                | 11        | 6.83%   |
| MSI                 | 6         | 3.73%   |
| Sony                | 4         | 2.48%   |
| Notebook            | 4         | 2.48%   |
| Apple               | 4         | 2.48%   |
| Toshiba             | 3         | 1.86%   |
| System76            | 3         | 1.86%   |
| Samsung Electronics | 3         | 1.86%   |
| Fujitsu             | 3         | 1.86%   |
| TUXEDO              | 2         | 1.24%   |
| Star Labs           | 2         | 1.24%   |
| Panasonic           | 1         | 0.62%   |
| MouseComputer       | 1         | 0.62%   |
| Jumper              | 1         | 0.62%   |
| HUAWEI              | 1         | 0.62%   |
| GPU Company         | 1         | 0.62%   |
| Alienware           | 1         | 0.62%   |
| Unknown             | 1         | 0.62%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Inspiron 3542                       | 3         | 1.86%   |
| MSI Modern 14 A10M                       | 2         | 1.24%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS       | 2         | 1.24%   |
| Lenovo ThinkPad T430s 2352CTO            | 2         | 1.24%   |
| Dell XPS 13 7390                         | 2         | 1.24%   |
| Dell Latitude E6420                      | 2         | 1.24%   |
| Dell Latitude 7490                       | 2         | 1.24%   |
| ASUS ZenBook UX325UA_UM325UA             | 2         | 1.24%   |
| Unknown                                  | 2         | 1.24%   |
| TUXEDO InfinityBook13V3                  | 1         | 0.62%   |
| TUXEDO Aura 15 Gen1                      | 1         | 0.62%   |
| Toshiba Satellite L655                   | 1         | 0.62%   |
| Toshiba Satellite C855-1U4               | 1         | 0.62%   |
| Toshiba Satellite C855                   | 1         | 0.62%   |
| System76 Lemur Pro                       | 1         | 0.62%   |
| System76 Kudu                            | 1         | 0.62%   |
| System76 Gazelle                         | 1         | 0.62%   |
| Star Labs StarBook                       | 1         | 0.62%   |
| Star Labs LabTop                         | 1         | 0.62%   |
| Sony VPCCB17FG                           | 1         | 0.62%   |
| Sony VGN-SZ3VWP_X                        | 1         | 0.62%   |
| Sony SVP1322M1EBI                        | 1         | 0.62%   |
| Sony SVP13225SCBI                        | 1         | 0.62%   |
| Samsung Q210                             | 1         | 0.62%   |
| Samsung 550P5C/550P7C                    | 1         | 0.62%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV | 1         | 0.62%   |
| Panasonic CF-19AHNC8FN                   | 1         | 0.62%   |
| Notebook N8xEJEK                         | 1         | 0.62%   |
| Notebook N85_N87,HJ,HJ1,HK1              | 1         | 0.62%   |
| Notebook N7x0WU                          | 1         | 0.62%   |
| Notebook N13xWU                          | 1         | 0.62%   |
| MSI Sword 17 A11UD                       | 1         | 0.62%   |
| MSI GF63 Thin 10SCSR                     | 1         | 0.62%   |
| MSI GE75 Raider 10SFS                    | 1         | 0.62%   |
| MSI GE62 6QC                             | 1         | 0.62%   |
| MouseComputer X5-aR5CEZAR-WA             | 1         | 0.62%   |
| Lenovo Yoga 2 13 20344                   | 1         | 0.62%   |
| Lenovo ThinkPad X395 20NLCTO1WW          | 1         | 0.62%   |
| Lenovo ThinkPad X250 20CM003WMS          | 1         | 0.62%   |
| Lenovo ThinkPad X250 20CL001GZA          | 1         | 0.62%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Lenovo ThinkPad              | 33        | 20.5%   |
| Dell Latitude                | 17        | 10.56%  |
| Dell Inspiron                | 14        | 8.7%    |
| Acer Aspire                  | 8         | 4.97%   |
| Lenovo IdeaPad               | 5         | 3.11%   |
| HP Laptop                    | 5         | 3.11%   |
| Toshiba Satellite            | 3         | 1.86%   |
| Lenovo Yoga                  | 3         | 1.86%   |
| HP EliteBook                 | 3         | 1.86%   |
| Dell XPS                     | 3         | 1.86%   |
| ASUS VivoBook                | 3         | 1.86%   |
| MSI Modern                   | 2         | 1.24%   |
| Lenovo Legion                | 2         | 1.24%   |
| Dell Precision               | 2         | 1.24%   |
| ASUS ZenBook                 | 2         | 1.24%   |
| Unknown                      | 2         | 1.24%   |
| TUXEDO InfinityBook13V3      | 1         | 0.62%   |
| TUXEDO Aura                  | 1         | 0.62%   |
| System76 Lemur               | 1         | 0.62%   |
| System76 Kudu                | 1         | 0.62%   |
| System76 Gazelle             | 1         | 0.62%   |
| Star Labs StarBook           | 1         | 0.62%   |
| Star Labs LabTop             | 1         | 0.62%   |
| Sony VPCCB17FG               | 1         | 0.62%   |
| Sony VGN-SZ3VWP              | 1         | 0.62%   |
| Sony SVP1322M1EBI            | 1         | 0.62%   |
| Sony SVP13225SCBI            | 1         | 0.62%   |
| Samsung Q210                 | 1         | 0.62%   |
| Samsung 550P5C               | 1         | 0.62%   |
| Samsung 3570R                | 1         | 0.62%   |
| Panasonic CF-19AHNC8FN       | 1         | 0.62%   |
| Notebook N8xEJEK             | 1         | 0.62%   |
| Notebook N85                 | 1         | 0.62%   |
| Notebook N7x0WU              | 1         | 0.62%   |
| Notebook N13xWU              | 1         | 0.62%   |
| MSI Sword                    | 1         | 0.62%   |
| MSI GF63                     | 1         | 0.62%   |
| MSI GE75                     | 1         | 0.62%   |
| MSI GE62                     | 1         | 0.62%   |
| MouseComputer X5-aR5CEZAR-WA | 1         | 0.62%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 24        | 14.91%  |
| 2013 | 17        | 10.56%  |
| 2021 | 15        | 9.32%   |
| 2018 | 13        | 8.07%   |
| 2014 | 13        | 8.07%   |
| 2022 | 10        | 6.21%   |
| 2016 | 10        | 6.21%   |
| 2012 | 10        | 6.21%   |
| 2011 | 9         | 5.59%   |
| 2017 | 8         | 4.97%   |
| 2015 | 8         | 4.97%   |
| 2019 | 7         | 4.35%   |
| 2009 | 7         | 4.35%   |
| 2010 | 4         | 2.48%   |
| 2008 | 4         | 2.48%   |
| 2023 | 1         | 0.62%   |
| 2007 | 1         | 0.62%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 161       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 159       | 98.76%  |
| Yes  | 2         | 1.24%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 77        | 47.53%  |
| 16.01-24.0  | 48        | 29.63%  |
| 4.01-8.0    | 27        | 16.67%  |
| 24.01-32.0  | 4         | 2.47%   |
| 32.01-64.0  | 3         | 1.85%   |
| 64.01-256.0 | 2         | 1.23%   |
| 2.01-3.0    | 1         | 0.62%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 73        | 44.24%  |
| 0.51-1.0   | 65        | 39.39%  |
| 1.01-2.0   | 13        | 7.88%   |
| 2.01-3.0   | 12        | 7.27%   |
| 4.01-8.0   | 1         | 0.61%   |
| 24.01-32.0 | 1         | 0.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 124       | 76.07%  |
| 2      | 30        | 18.4%   |
| 0      | 8         | 4.91%   |
| 3      | 1         | 0.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 101       | 62.35%  |
| Yes       | 61        | 37.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 136       | 84.47%  |
| No        | 25        | 15.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 160       | 99.38%  |
| No        | 1         | 0.62%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 126       | 78.26%  |
| No        | 35        | 21.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 37        | 22.98%  |
| Germany      | 17        | 10.56%  |
| UK           | 10        | 6.21%   |
| France       | 9         | 5.59%   |
| Spain        | 7         | 4.35%   |
| Russia       | 7         | 4.35%   |
| Poland       | 7         | 4.35%   |
| Italy        | 5         | 3.11%   |
| Japan        | 4         | 2.48%   |
| Indonesia    | 4         | 2.48%   |
| India        | 4         | 2.48%   |
| Brazil       | 4         | 2.48%   |
| Switzerland  | 3         | 1.86%   |
| Sweden       | 3         | 1.86%   |
| New Zealand  | 3         | 1.86%   |
| Slovenia     | 2         | 1.24%   |
| Slovakia     | 2         | 1.24%   |
| Portugal     | 2         | 1.24%   |
| Philippines  | 2         | 1.24%   |
| Netherlands  | 2         | 1.24%   |
| Mauritius    | 2         | 1.24%   |
| Hong Kong    | 2         | 1.24%   |
| Finland      | 2         | 1.24%   |
| China        | 2         | 1.24%   |
| Canada       | 2         | 1.24%   |
| Bulgaria     | 2         | 1.24%   |
| Belgium      | 2         | 1.24%   |
| Ukraine      | 1         | 0.62%   |
| Uganda       | 1         | 0.62%   |
| South Africa | 1         | 0.62%   |
| Serbia       | 1         | 0.62%   |
| Norway       | 1         | 0.62%   |
| Namibia      | 1         | 0.62%   |
| Malaysia     | 1         | 0.62%   |
| Kazakhstan   | 1         | 0.62%   |
| Hungary      | 1         | 0.62%   |
| Greece       | 1         | 0.62%   |
| Egypt        | 1         | 0.62%   |
| Belarus      | 1         | 0.62%   |
| Argentina    | 1         | 0.62%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Bedburg            | 6         | 3.59%   |
| Saratov            | 3         | 1.8%    |
| Rome               | 3         | 1.8%    |
| Madrid             | 3         | 1.8%    |
| Jakarta            | 3         | 1.8%    |
| Indian Trail       | 3         | 1.8%    |
| Franconville       | 3         | 1.8%    |
| Chrusty            | 3         | 1.8%    |
| Bonn               | 3         | 1.8%    |
| Zurich             | 2         | 1.2%    |
| Yokohama           | 2         | 1.2%    |
| Whittier           | 2         | 1.2%    |
| Wezeren            | 2         | 1.2%    |
| Tomball            | 2         | 1.2%    |
| Stiring-Wendel     | 2         | 1.2%    |
| Skiatook           | 2         | 1.2%    |
| Paris              | 2         | 1.2%    |
| London             | 2         | 1.2%    |
| Giessen            | 2         | 1.2%    |
| Clemmons           | 2         | 1.2%    |
| Chiyoda-ku         | 2         | 1.2%    |
| Celje              | 2         | 1.2%    |
| Asnieres-sur-Seine | 2         | 1.2%    |
| Yaroslavl          | 1         | 0.6%    |
| Wraysbury          | 1         | 0.6%    |
| Witbank            | 1         | 0.6%    |
| Winnipeg           | 1         | 0.6%    |
| Windhoek           | 1         | 0.6%    |
| Wenatchee          | 1         | 0.6%    |
| Valencia           | 1         | 0.6%    |
| Toronto            | 1         | 0.6%    |
| Tatsfield          | 1         | 0.6%    |
| Taita              | 1         | 0.6%    |
| Starkville         | 1         | 0.6%    |
| Staffanstorp       | 1         | 0.6%    |
| St Petersburg      | 1         | 0.6%    |
| St Austell         | 1         | 0.6%    |
| Sollentuna         | 1         | 0.6%    |
| Sofia              | 1         | 0.6%    |
| Shelby             | 1         | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 44        | 56     | 23.78%  |
| WDC                 | 24        | 26     | 12.97%  |
| Kingston            | 19        | 19     | 10.27%  |
| Seagate             | 15        | 18     | 8.11%   |
| SK hynix            | 11        | 14     | 5.95%   |
| Toshiba             | 10        | 13     | 5.41%   |
| Crucial             | 10        | 11     | 5.41%   |
| SanDisk             | 8         | 8      | 4.32%   |
| Intel               | 5         | 5      | 2.7%    |
| A-DATA Technology   | 4         | 4      | 2.16%   |
| Phison              | 3         | 4      | 1.62%   |
| Micron Technology   | 3         | 3      | 1.62%   |
| Hitachi             | 3         | 3      | 1.62%   |
| HGST                | 3         | 3      | 1.62%   |
| Star Drive          | 2         | 2      | 1.08%   |
| PNY                 | 2         | 2      | 1.08%   |
| Patriot             | 2         | 2      | 1.08%   |
| KingSpec            | 2         | 2      | 1.08%   |
| GOODRAM             | 2         | 2      | 1.08%   |
| Fujitsu             | 2         | 2      | 1.08%   |
| XUM                 | 1         | 1      | 0.54%   |
| SSSTC               | 1         | 1      | 0.54%   |
| SPCC                | 1         | 1      | 0.54%   |
| Silicon Motion      | 1         | 1      | 0.54%   |
| Plextor             | 1         | 1      | 0.54%   |
| Netac               | 1         | 1      | 0.54%   |
| LITEONIT            | 1         | 1      | 0.54%   |
| Hewlett-Packard     | 1         | 1      | 0.54%   |
| Gigabyte Technology | 1         | 1      | 0.54%   |
| Dell                | 1         | 2      | 0.54%   |
| Apple               | 1         | 1      | 0.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB            | 4         | 2.11%   |
| Seagate ST1000LM035-1RK172 1TB         | 3         | 1.58%   |
| Samsung SSD 860 EVO 500GB              | 3         | 1.58%   |
| Samsung SSD 850 EVO 250GB              | 3         | 1.58%   |
| WDC WDS500G2B0A-00SM50 500GB           | 2         | 1.05%   |
| WDC WD10JPVX-22JC3T0 1TB               | 2         | 1.05%   |
| Toshiba KXG50ZNV512G NVMe 512GB        | 2         | 1.05%   |
| Star Drive PCIe SSD 960GB              | 2         | 1.05%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB | 2         | 1.05%   |
| SK hynix HFM512GD3JX013N 512GB         | 2         | 1.05%   |
| Seagate ST1000LM049-2GH172 1TB         | 2         | 1.05%   |
| Samsung SSD 860 QVO 1TB                | 2         | 1.05%   |
| Samsung PM981 NVMe 256GB               | 2         | 1.05%   |
| Samsung MZNTE128HMGR-000SO 128GB       | 2         | 1.05%   |
| Kingston SV300S37A240G 240GB           | 2         | 1.05%   |
| Kingston SA400S37960G 960GB            | 2         | 1.05%   |
| Kingston SA400S37120G 120GB            | 2         | 1.05%   |
| Kingston RBUSNS8154P3512GJ 512GB       | 2         | 1.05%   |
| KingSpec Q-720 720GB                   | 2         | 1.05%   |
| XUM HX256GSSDSATA3 256GB               | 1         | 0.53%   |
| WDC WDS240G2G0A-00JH30 240GB           | 1         | 0.53%   |
| WDC WDS120G2G0A-00JH30 120GB           | 1         | 0.53%   |
| WDC WDS100T3X0C-00SJG0 1TB             | 1         | 0.53%   |
| WDC WDS100T2B0B-00YS70 1TB             | 1         | 0.53%   |
| WDC WDS100T1B0A-00H9H0 1TB             | 1         | 0.53%   |
| WDC WD7500BPVT-80HXZT3 752GB           | 1         | 0.53%   |
| WDC WD7500BPKX-80HPJT0 752GB           | 1         | 0.53%   |
| WDC WD6400BEVT-22A0RT0 640GB           | 1         | 0.53%   |
| WDC WD5000LPCX-24C6HT0 500GB           | 1         | 0.53%   |
| WDC WD5000BPVT-00HXZT3 500GB           | 1         | 0.53%   |
| WDC WD3200LPVX-75V0TT0 320GB           | 1         | 0.53%   |
| WDC WD10SPZX-75Z10T3 1TB               | 1         | 0.53%   |
| WDC WD10SPZX-75Z10T2 1TB               | 1         | 0.53%   |
| WDC WD10SPZX-24Z10T0 1TB               | 1         | 0.53%   |
| WDC WD10SPZX-21Z10T0 1TB               | 1         | 0.53%   |
| WDC WD10JPVX-00JC3T0 1TB               | 1         | 0.53%   |
| WDC WD10JMVW-11AJGS1 1TB               | 1         | 0.53%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB   | 1         | 0.53%   |
| WDC PC SN530 NVMe 256GB                | 1         | 0.53%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB   | 1         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 18     | 34.88%  |
| WDC                 | 14        | 15     | 32.56%  |
| Toshiba             | 4         | 4      | 9.3%    |
| Hitachi             | 3         | 3      | 6.98%   |
| HGST                | 3         | 3      | 6.98%   |
| Samsung Electronics | 2         | 2      | 4.65%   |
| Fujitsu             | 2         | 2      | 4.65%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 27        | 36     | 29.35%  |
| Kingston            | 16        | 16     | 17.39%  |
| SanDisk             | 8         | 8      | 8.7%    |
| Crucial             | 8         | 9      | 8.7%    |
| WDC                 | 6         | 6      | 6.52%   |
| SK hynix            | 4         | 4      | 4.35%   |
| PNY                 | 2         | 2      | 2.17%   |
| Patriot             | 2         | 2      | 2.17%   |
| Micron Technology   | 2         | 2      | 2.17%   |
| KingSpec            | 2         | 2      | 2.17%   |
| Intel               | 2         | 2      | 2.17%   |
| GOODRAM             | 2         | 2      | 2.17%   |
| A-DATA Technology   | 2         | 2      | 2.17%   |
| XUM                 | 1         | 1      | 1.09%   |
| Toshiba             | 1         | 2      | 1.09%   |
| SPCC                | 1         | 1      | 1.09%   |
| Plextor             | 1         | 1      | 1.09%   |
| Phison              | 1         | 1      | 1.09%   |
| Netac               | 1         | 1      | 1.09%   |
| LITEONIT            | 1         | 1      | 1.09%   |
| Dell                | 1         | 2      | 1.09%   |
| Apple               | 1         | 1      | 1.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 84        | 104    | 48.84%  |
| NVMe | 48        | 60     | 27.91%  |
| HDD  | 40        | 47     | 23.26%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 118       | 151    | 71.08%  |
| NVMe | 48        | 60     | 28.92%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 85        | 98     | 67.46%  |
| 0.51-1.0   | 36        | 47     | 28.57%  |
| 1.01-2.0   | 5         | 6      | 3.97%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 54        | 31.76%  |
| 101-250    | 38        | 22.35%  |
| 251-500    | 28        | 16.47%  |
| 501-1000   | 17        | 10%     |
| 51-100     | 15        | 8.82%   |
| Unknown    | 11        | 6.47%   |
| 21-50      | 5         | 2.94%   |
| 1001-2000  | 2         | 1.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 143       | 84.62%  |
| 21-50   | 12        | 7.1%    |
| Unknown | 11        | 6.51%   |
| 51-100  | 2         | 1.18%   |
| 101-250 | 1         | 0.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| Kingston SA400S37240G 240GB                     | 2         | 2      | 9.09%   |
| WDC WD6400BEVT-22A0RT0 640GB                    | 1         | 1      | 4.55%   |
| WDC WD3200LPVX-75V0TT0 320GB                    | 1         | 1      | 4.55%   |
| Toshiba MQ01ACF032 320GB                        | 1         | 1      | 4.55%   |
| Toshiba MK1252GSX 120GB                         | 1         | 1      | 4.55%   |
| Seagate ST9250827AS 250GB                       | 1         | 1      | 4.55%   |
| Seagate ST500LT012-9WS142 500GB                 | 1         | 2      | 4.55%   |
| Seagate ST500LM021-1KJ152 500GB                 | 1         | 1      | 4.55%   |
| Seagate ST1000LM035-1RK172 1TB                  | 1         | 2      | 4.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 1         | 1      | 4.55%   |
| Samsung Electronics SSD 980 500GB               | 1         | 1      | 4.55%   |
| Samsung Electronics SSD 840 PRO Series 256GB    | 1         | 1      | 4.55%   |
| Samsung Electronics MZNTE128HMGR-000SO 128GB    | 1         | 1      | 4.55%   |
| Samsung Electronics HM320JI 320GB               | 1         | 1      | 4.55%   |
| Patriot Inferno 60GB SSD                        | 1         | 1      | 4.55%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB | 1         | 1      | 4.55%   |
| Intel SSDSC2BF180A5L 180GB                      | 1         | 1      | 4.55%   |
| Intel SSDSC2BF180A4L 180GB                      | 1         | 1      | 4.55%   |
| Hitachi HTS543225L9A300 250GB                   | 1         | 1      | 4.55%   |
| HGST HTS721010A9E630 1TB                        | 1         | 1      | 4.55%   |
| HGST HTS541010A9E680 1TB                        | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 7      | 22.73%  |
| Samsung Electronics | 4         | 4      | 18.18%  |
| WDC                 | 2         | 2      | 9.09%   |
| Toshiba             | 2         | 2      | 9.09%   |
| Kingston            | 2         | 2      | 9.09%   |
| Intel               | 2         | 2      | 9.09%   |
| HGST                | 2         | 2      | 9.09%   |
| Patriot             | 1         | 1      | 4.55%   |
| Micron Technology   | 1         | 1      | 4.55%   |
| Hitachi             | 1         | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 7      | 38.46%  |
| WDC                 | 2         | 2      | 15.38%  |
| Toshiba             | 2         | 2      | 15.38%  |
| HGST                | 2         | 2      | 15.38%  |
| Samsung Electronics | 1         | 1      | 7.69%   |
| Hitachi             | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 15     | 57.14%  |
| SSD  | 8         | 8      | 38.1%   |
| NVMe | 1         | 1      | 4.76%   |

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
| Works   | 138       | 187    | 86.79%  |
| Malfunc | 21        | 24     | 13.21%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 119       | 63.98%  |
| Samsung Electronics            | 17        | 9.14%   |
| AMD                            | 14        | 7.53%   |
| SK hynix                       | 7         | 3.76%   |
| SanDisk                        | 5         | 2.69%   |
| Phison Electronics             | 5         | 2.69%   |
| Toshiba                        | 3         | 1.61%   |
| Nvidia                         | 3         | 1.61%   |
| Kingston Technology Company    | 3         | 1.61%   |
| Micron/Crucial Technology      | 2         | 1.08%   |
| ADATA Technology               | 2         | 1.08%   |
| Solid State Storage Technology | 1         | 0.54%   |
| Silicon Motion                 | 1         | 0.54%   |
| Micron Technology              | 1         | 0.54%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.54%   |
| KIOXIA                         | 1         | 0.54%   |
| Biwin Storage Technology       | 1         | 0.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 19        | 9.95%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 16        | 8.38%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 12        | 6.28%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 12        | 6.28%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 11        | 5.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 5.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 4.71%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 8         | 4.19%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 2.62%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 2.62%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 2.62%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 2.09%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 2.09%   |
| Nvidia MCP79 AHCI Controller                                                   | 3         | 1.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 1.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 1.57%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.57%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 1.05%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 1.05%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.05%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 2         | 1.05%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 1.05%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 1.05%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.05%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 1.05%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.05%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.05%   |
| Toshiba XG5 NVMe SSD Controller                                                | 1         | 0.52%   |
| Toshiba XG4 NVMe SSD Controller                                                | 1         | 0.52%   |
| Toshiba BG3 NVMe SSD Controller                                                | 1         | 0.52%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 1         | 0.52%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 0.52%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.52%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1         | 0.52%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.52%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.52%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.52%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 0.52%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 121       | 65.41%  |
| NVMe | 47        | 25.41%  |
| RAID | 11        | 5.95%   |
| IDE  | 6         | 3.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 135       | 83.85%  |
| AMD    | 26        | 16.15%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz             | 6         | 3.73%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 5         | 3.11%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 2.48%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 2.48%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 2.48%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 2.48%   |
| Intel Core 2 Duo                              | 4         | 2.48%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.86%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.86%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 1.86%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 1.86%   |
| Intel Core i9-10980HK CPU @ 2.40GHz           | 2         | 1.24%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 1.24%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 1.24%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.24%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 2         | 1.24%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.24%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 1.24%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.24%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 1.24%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 1.24%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.24%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.24%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.24%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.24%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.24%   |
| Intel Core i5-2520M CPU @ 2.50GH              | 2         | 1.24%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 1.24%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 1.24%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz          | 2         | 1.24%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.24%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.24%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.24%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 1.24%   |
| AMD Ryzen 5 3450U with Radeon Vega Mobile Gfx | 2         | 1.24%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 2         | 1.24%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.62%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 0.62%   |
| Intel Pentium 3558U @ 1.70GHz                 | 1         | 0.62%   |
| Intel Genuine CPU                             | 1         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 50        | 31.06%  |
| Intel Core i7    | 45        | 27.95%  |
| Intel Core i3    | 12        | 7.45%   |
| Intel Core 2 Duo | 11        | 6.83%   |
| AMD Ryzen 7      | 8         | 4.97%   |
| AMD Ryzen 5      | 8         | 4.97%   |
| Other            | 6         | 3.73%   |
| Intel Celeron    | 5         | 3.11%   |
| AMD A6           | 3         | 1.86%   |
| Intel Pentium    | 2         | 1.24%   |
| Intel Core i9    | 2         | 1.24%   |
| AMD A4           | 2         | 1.24%   |
| Intel Xeon       | 1         | 0.62%   |
| Intel Genuine    | 1         | 0.62%   |
| Intel Core 2     | 1         | 0.62%   |
| AMD Ryzen 7 PRO  | 1         | 0.62%   |
| AMD Ryzen 3      | 1         | 0.62%   |
| AMD Athlon       | 1         | 0.62%   |
| AMD A10          | 1         | 0.62%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 80        | 49.69%  |
| 4       | 46        | 28.57%  |
| 8       | 11        | 6.83%   |
| 6       | 8         | 4.97%   |
| Unknown | 7         | 4.35%   |
| 16      | 5         | 3.11%   |
| 12      | 4         | 2.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 158       | 98.14%  |
| 2      | 3         | 1.86%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 114       | 70.81%  |
| 1       | 40        | 24.84%  |
| Unknown | 7         | 4.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 30        | 18.63%  |
| IvyBridge   | 20        | 12.42%  |
| Haswell     | 16        | 9.94%   |
| Skylake     | 14        | 8.7%    |
| SandyBridge | 12        | 7.45%   |
| Penryn      | 9         | 5.59%   |
| Broadwell   | 9         | 5.59%   |
| Zen+        | 8         | 4.97%   |
| Zen 3       | 5         | 3.11%   |
| Westmere    | 5         | 3.11%   |
| Unknown     | 5         | 3.11%   |
| IceLake     | 4         | 2.48%   |
| Excavator   | 4         | 2.48%   |
| Core        | 4         | 2.48%   |
| CometLake   | 4         | 2.48%   |
| Zen 2       | 3         | 1.86%   |
| TigerLake   | 2         | 1.24%   |
| Silvermont  | 2         | 1.24%   |
| Goldmont    | 2         | 1.24%   |
| Puma        | 1         | 0.62%   |
| K10 Llano   | 1         | 0.62%   |
| K10         | 1         | 0.62%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 123       | 62.76%  |
| Nvidia | 41        | 20.92%  |
| AMD    | 32        | 16.33%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 16        | 7.96%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 13        | 6.47%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 12        | 5.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 9         | 4.48%   |
| Intel HD Graphics 5500                                                    | 9         | 4.48%   |
| Intel UHD Graphics 620                                                    | 8         | 3.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 8         | 3.98%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 7         | 3.48%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 6         | 2.99%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 6         | 2.99%   |
| Intel HD Graphics 620                                                     | 5         | 2.49%   |
| Intel HD Graphics 530                                                     | 4         | 1.99%   |
| Intel Core Processor Integrated Graphics Controller                       | 4         | 1.99%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 4         | 1.99%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 1.49%   |
| Nvidia C79 [GeForce 9400M]                                                | 3         | 1.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 3         | 1.49%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 3         | 1.49%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 3         | 1.49%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 1.49%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 3         | 1.49%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 3         | 1.49%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 3         | 1.49%   |
| AMD Renoir                                                                | 3         | 1.49%   |
| AMD Lucienne                                                              | 3         | 1.49%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 2         | 1%      |
| Nvidia GK107GLM [Quadro K1000M]                                           | 2         | 1%      |
| Nvidia GF108GLM [NVS 5200M]                                               | 2         | 1%      |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 1%      |
| Intel HD Graphics 500                                                     | 2         | 1%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 2         | 1%      |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.5%    |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                     | 1         | 0.5%    |
| Nvidia GT218M [NVS 3100M]                                                 | 1         | 0.5%    |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                     | 1         | 0.5%    |
| Nvidia GM206M [GeForce GTX 965M]                                          | 1         | 0.5%    |
| Nvidia GM108M [GeForce MX130]                                             | 1         | 0.5%    |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.5%    |
| Nvidia GM107GLM [Quadro M2000M]                                           | 1         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 82        | 50.93%  |
| Intel + Nvidia | 30        | 18.63%  |
| 1 x AMD        | 26        | 16.15%  |
| 1 x Nvidia     | 10        | 6.21%   |
| 2 x Intel      | 7         | 4.35%   |
| Intel + AMD    | 4         | 2.48%   |
| 2 x AMD        | 1         | 0.62%   |
| AMD + Nvidia   | 1         | 0.62%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 152       | 93.83%  |
| Proprietary | 10        | 6.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 139       | 84.24%  |
| 0.01-0.5   | 10        | 6.06%   |
| 1.01-2.0   | 9         | 5.45%   |
| 0.51-1.0   | 4         | 2.42%   |
| 3.01-4.0   | 2         | 1.21%   |
| 5.01-6.0   | 1         | 0.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 30        | 20.98%  |
| AU Optronics            | 27        | 18.88%  |
| LG Display              | 25        | 17.48%  |
| Samsung Electronics     | 17        | 11.89%  |
| BOE                     | 12        | 8.39%   |
| Lenovo                  | 4         | 2.8%    |
| Philips                 | 3         | 2.1%    |
| InfoVision              | 3         | 2.1%    |
| Dell                    | 3         | 2.1%    |
| CSO                     | 3         | 2.1%    |
| PANDA                   | 2         | 1.4%    |
| Panasonic               | 2         | 1.4%    |
| BenQ                    | 2         | 1.4%    |
| ___                     | 1         | 0.7%    |
| Iiyama                  | 1         | 0.7%    |
| IBM                     | 1         | 0.7%    |
| Hewlett-Packard         | 1         | 0.7%    |
| Goldstar                | 1         | 0.7%    |
| Fujitsu Siemens         | 1         | 0.7%    |
| Chi Mei Optoelectronics | 1         | 0.7%    |
| BOE Technology Group    | 1         | 0.7%    |
| Apple                   | 1         | 0.7%    |
| Unknown                 | 1         | 0.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 2         | 1.39%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch  | 2         | 1.39%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 290x170mm 13.2-inch | 2         | 1.39%   |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch              | 2         | 1.39%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch          | 2         | 1.39%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch           | 2         | 1.39%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch           | 2         | 1.39%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch           | 2         | 1.39%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 2         | 1.39%   |
| LG Display LCD Monitor LGD01E9 1920x1080 350x190mm 15.7-inch          | 2         | 1.39%   |
| CSO LCD Monitor CSO1402 2880x1800 300x190mm 14.0-inch                 | 2         | 1.39%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch      | 2         | 1.39%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch      | 2         | 1.39%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 2         | 1.39%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch       | 2         | 1.39%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch       | 2         | 1.39%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 340x190mm 15.3-inch        | 2         | 1.39%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 1.39%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 290x160mm 13.0-inch        | 2         | 1.39%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch         | 2         | 1.39%   |
| ___ MY TV LED TV ___0101 1920x1080                                    | 1         | 0.69%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch  | 1         | 0.69%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 340x190mm 15.3-inch | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 310x170mm 13.9-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SDC4C46 3840x2160 340x190mm 15.3-inch | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 340x190mm 15.3-inch  | 1         | 0.69%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 1         | 0.69%   |
| Philips PHL BDM4065 PHL08E1 3840x2160 880x490mm 39.7-inch             | 1         | 0.69%   |
| PANDA LCD Monitor NCP0040 1920x1080 340x190mm 15.3-inch               | 1         | 0.69%   |
| PANDA LC133LF1L02 NCP0019 1920x1080 290x170mm 13.2-inch               | 1         | 0.69%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 340x190mm 15.3-inch         | 1         | 0.69%   |
| LG Display LCD Monitor LGD066E 1920x1080 340x190mm 15.3-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD0616 1920x1080 340x190mm 15.3-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch          | 1         | 0.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 60        | 43.17%  |
| 1366x768 (WXGA)    | 50        | 35.97%  |
| 1600x900 (HD+)     | 8         | 5.76%   |
| 2560x1440 (QHD)    | 4         | 2.88%   |
| 3840x2160 (4K)     | 3         | 2.16%   |
| 2880x1800          | 3         | 2.16%   |
| 2880x1620          | 2         | 1.44%   |
| 1680x1050 (WSXGA+) | 2         | 1.44%   |
| 1280x800 (WXGA)    | 2         | 1.44%   |
| 9600x2160          | 1         | 0.72%   |
| 3840x1600          | 1         | 0.72%   |
| 2560x1600          | 1         | 0.72%   |
| 1440x900 (WXGA+)   | 1         | 0.72%   |
| 1280x1024 (SXGA)   | 1         | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 68        | 47.22%  |
| 13      | 33        | 22.92%  |
| 17      | 8         | 5.56%   |
| 14      | 6         | 4.17%   |
| 12      | 6         | 4.17%   |
| 23      | 5         | 3.47%   |
| 11      | 5         | 3.47%   |
| 24      | 3         | 2.08%   |
| Unknown | 3         | 2.08%   |
| 39      | 1         | 0.69%   |
| 37      | 1         | 0.69%   |
| 31      | 1         | 0.69%   |
| 27      | 1         | 0.69%   |
| 22      | 1         | 0.69%   |
| 21      | 1         | 0.69%   |
| 16      | 1         | 0.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 92        | 64.34%  |
| 201-300     | 26        | 18.18%  |
| 501-600     | 9         | 6.29%   |
| 351-400     | 8         | 5.59%   |
| Unknown     | 3         | 2.1%    |
| 801-900     | 2         | 1.4%    |
| 401-500     | 2         | 1.4%    |
| 601-700     | 1         | 0.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 116       | 87.88%  |
| 16/10   | 11        | 8.33%   |
| Unknown | 2         | 1.52%   |
| 5/4     | 1         | 0.76%   |
| 3/2     | 1         | 0.76%   |
| 21/9    | 1         | 0.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 57        | 39.58%  |
| 81-90          | 30        | 20.83%  |
| 101-110        | 11        | 7.64%   |
| 201-250        | 10        | 6.94%   |
| 71-80          | 9         | 6.25%   |
| 121-130        | 7         | 4.86%   |
| 61-70          | 6         | 4.17%   |
| 51-60          | 5         | 3.47%   |
| Unknown        | 3         | 2.08%   |
| 501-1000       | 2         | 1.39%   |
| 351-500        | 1         | 0.69%   |
| 301-350        | 1         | 0.69%   |
| 141-150        | 1         | 0.69%   |
| 111-120        | 1         | 0.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 62        | 43.66%  |
| 101-120       | 40        | 28.17%  |
| 51-100        | 18        | 12.68%  |
| 161-240       | 15        | 10.56%  |
| More than 240 | 4         | 2.82%   |
| Unknown       | 3         | 2.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 128       | 77.58%  |
| 0     | 22        | 13.33%  |
| 2     | 15        | 9.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 103       | 39.31%  |
| Realtek Semiconductor             | 68        | 25.95%  |
| Qualcomm Atheros                  | 38        | 14.5%   |
| Broadcom                          | 14        | 5.34%   |
| TP-Link                           | 7         | 2.67%   |
| Ericsson Business Mobile Networks | 4         | 1.53%   |
| Edimax Technology                 | 4         | 1.53%   |
| Nvidia                            | 3         | 1.15%   |
| Marvell Technology Group          | 3         | 1.15%   |
| ASUSTek Computer                  | 3         | 1.15%   |
| Sierra Wireless                   | 2         | 0.76%   |
| Samsung Electronics               | 2         | 0.76%   |
| Ralink Technology                 | 2         | 0.76%   |
| Xiaomi                            | 1         | 0.38%   |
| Ralink                            | 1         | 0.38%   |
| Qualcomm Atheros Communications   | 1         | 0.38%   |
| Qualcomm                          | 1         | 0.38%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.38%   |
| Huawei Technologies               | 1         | 0.38%   |
| Hewlett-Packard                   | 1         | 0.38%   |
| Generic                           | 1         | 0.38%   |
| Dell                              | 1         | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44        | 13.41%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 5.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 3.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 3.05%   |
| Intel Wireless 8265 / 8275                                        | 10        | 3.05%   |
| Intel Wi-Fi 6 AX200                                               | 9         | 2.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 2.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 2.44%   |
| Intel Wireless 8260                                               | 8         | 2.44%   |
| Intel Wireless 7265                                               | 8         | 2.44%   |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 2.13%   |
| Intel Wireless 7260                                               | 6         | 1.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.83%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.52%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.52%   |
| Intel Centrino Ultimate-N 6300                                    | 5         | 1.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 4         | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.22%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 1.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.22%   |
| Intel Wireless 3165                                               | 4         | 1.22%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3         | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.91%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.91%   |
| Intel Wireless 3160                                               | 3         | 0.91%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 0.91%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.91%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.61%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.61%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.61%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 2         | 0.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 99        | 55%     |
| Qualcomm Atheros                | 30        | 16.67%  |
| Realtek Semiconductor           | 23        | 12.78%  |
| Broadcom                        | 8         | 4.44%   |
| TP-Link                         | 7         | 3.89%   |
| Edimax Technology               | 4         | 2.22%   |
| ASUSTek Computer                | 3         | 1.67%   |
| Sierra Wireless                 | 2         | 1.11%   |
| Ralink Technology               | 2         | 1.11%   |
| Ralink                          | 1         | 0.56%   |
| Qualcomm Atheros Communications | 1         | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 5.52%   |
| Intel Wireless 8265 / 8275                                     | 10        | 5.52%   |
| Intel Wi-Fi 6 AX200                                            | 9         | 4.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 4.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 8         | 4.42%   |
| Intel Wireless 8260                                            | 8         | 4.42%   |
| Intel Wireless 7265                                            | 8         | 4.42%   |
| Intel Wireless 7260                                            | 6         | 3.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 3.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 2.76%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 2.76%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 4         | 2.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.21%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 2.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 2.21%   |
| Intel Wireless 3165                                            | 4         | 2.21%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 1.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 1.66%   |
| Intel Wireless 3160                                            | 3         | 1.66%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 1.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.1%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.1%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 1.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.1%    |
| Intel Wi-Fi 6 AX201                                            | 2         | 1.1%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 1.1%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 2         | 1.1%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.1%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.1%    |
| Intel Centrino Advanced-N 6235                                 | 2         | 1.1%    |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 1.1%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 2         | 1.1%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2         | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 1.1%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.55%   |
| TP-Link High Power Wireless USB Adapter                        | 1         | 0.55%   |
| Sierra Wireless EM7455                                         | 1         | 0.55%   |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 58        | 42.03%  |
| Intel                         | 51        | 36.96%  |
| Qualcomm Atheros              | 11        | 7.97%   |
| Broadcom                      | 7         | 5.07%   |
| Nvidia                        | 3         | 2.17%   |
| Marvell Technology Group      | 3         | 2.17%   |
| Samsung Electronics           | 2         | 1.45%   |
| Xiaomi                        | 1         | 0.72%   |
| Qualcomm                      | 1         | 0.72%   |
| OnePlus Technology (Shenzhen) | 1         | 0.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44        | 31.65%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 12.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 9.35%   |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 5.04%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 3.6%    |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 3.6%    |
| Nvidia MCP79 Ethernet                                             | 3         | 2.16%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 2.16%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 2.16%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.44%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.44%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.44%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.44%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.44%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.72%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.72%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.72%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.72%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.72%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.72%   |
| Qualcomm ALCATEL RNDIS Interface                                  | 1         | 0.72%   |
| OnePlus (Shenzhen) Android Remote NDIS Device                     | 1         | 0.72%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.72%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.72%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.72%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.72%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller               | 1         | 0.72%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.72%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.72%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.72%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.72%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 0.72%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.72%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 161       | 52.61%  |
| Ethernet | 137       | 44.77%  |
| Modem    | 6         | 1.96%   |
| Unknown  | 2         | 0.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 108       | 52.43%  |
| Ethernet | 95        | 46.12%  |
| Modem    | 3         | 1.46%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 130       | 80.75%  |
| 1     | 30        | 18.63%  |
| 3     | 1         | 0.62%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 160       | 99.38%  |
| Yes  | 1         | 0.62%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 71        | 55.91%  |
| Realtek Semiconductor           | 12        | 9.45%   |
| Qualcomm Atheros Communications | 9         | 7.09%   |
| Lite-On Technology              | 8         | 6.3%    |
| Broadcom                        | 8         | 6.3%    |
| IMC Networks                    | 6         | 4.72%   |
| Dell                            | 5         | 3.94%   |
| Apple                           | 4         | 3.15%   |
| Alps Electric                   | 2         | 1.57%   |
| Toshiba                         | 1         | 0.79%   |
| ASUSTek Computer                | 1         | 0.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 36        | 28.35%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 12        | 9.45%   |
| Intel AX201 Bluetooth                                       | 9         | 7.09%   |
| Intel AX200 Bluetooth                                       | 8         | 6.3%    |
| Realtek Bluetooth Adapter                                   | 5         | 3.94%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 4         | 3.15%   |
| Apple Bluetooth Host Controller                             | 4         | 3.15%   |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 2.36%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 3         | 2.36%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 3         | 2.36%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 3         | 2.36%   |
| Lite-On Atheros AR3012 Bluetooth                            | 3         | 2.36%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 3         | 2.36%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 1.57%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 1.57%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 1.57%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 1.57%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.57%   |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip             | 1         | 0.79%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.79%   |
| Realtek Bluetooth 4.2 Adapter                               | 1         | 0.79%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 0.79%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 0.79%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.79%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 1         | 0.79%   |
| Lite-On Broadcom Bluetooth 4.0 USB                          | 1         | 0.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.79%   |
| Intel AX210 Bluetooth                                       | 1         | 0.79%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 0.79%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 0.79%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0          | 1         | 0.79%   |
| IMC Networks Bluetooth Module                               | 1         | 0.79%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 0.79%   |
| Dell DW375 Bluetooth Module                                 | 1         | 0.79%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 0.79%   |
| Broadcom BCM2045 Bluetooth                                  | 1         | 0.79%   |
| ASUS USB-BT500                                              | 1         | 0.79%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 0.79%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)             | 1         | 0.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 132       | 73.33%  |
| AMD                   | 28        | 15.56%  |
| Nvidia                | 13        | 7.22%   |
| Lenovo                | 2         | 1.11%   |
| RODE Microphones      | 1         | 0.56%   |
| Realtek Semiconductor | 1         | 0.56%   |
| Logitech              | 1         | 0.56%   |
| DSEA A/S              | 1         | 0.56%   |
| Cambridge Audio       | 1         | 0.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 22        | 9.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 21        | 9.13%   |
| AMD Family 17h/19h HD Audio Controller                                     | 19        | 8.26%   |
| Intel Haswell-ULT HD Audio Controller                                      | 13        | 5.65%   |
| Intel 8 Series HD Audio Controller                                         | 13        | 5.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 4.78%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 4.35%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 9         | 3.91%   |
| Intel Broadwell-U Audio Controller                                         | 9         | 3.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 3.48%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 3.04%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 3.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6         | 2.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 2.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 2.17%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1.74%   |
| Nvidia MCP79 High Definition Audio                                         | 3         | 1.3%    |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.3%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.3%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 1.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 1.3%    |
| AMD High Definition Audio Controller                                       | 3         | 1.3%    |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.87%   |
| Lenovo Lenovo USB-C Mini Dock                                              | 2         | 0.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 0.87%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 0.87%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 0.87%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 0.87%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.87%   |
| AMD FCH Azalia Controller                                                  | 2         | 0.87%   |
| RODE Microphones RDE NT-USB Mini                                           | 1         | 0.43%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.43%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.43%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.43%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.43%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.43%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.43%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 66        | 31.88%  |
| SK hynix            | 54        | 26.09%  |
| Micron Technology   | 19        | 9.18%   |
| Crucial             | 13        | 6.28%   |
| Kingston            | 12        | 5.8%    |
| Unknown             | 10        | 4.83%   |
| Elpida              | 6         | 2.9%    |
| Corsair             | 4         | 1.93%   |
| Ramaxel Technology  | 3         | 1.45%   |
| Unknown (ABCD)      | 2         | 0.97%   |
| Transcend           | 2         | 0.97%   |
| Goodram             | 2         | 0.97%   |
| G.Skill             | 2         | 0.97%   |
| A-DATA Technology   | 2         | 0.97%   |
| Unknown             | 2         | 0.97%   |
| Team                | 1         | 0.48%   |
| Smart Modular       | 1         | 0.48%   |
| Smart               | 1         | 0.48%   |
| Neo Forza           | 1         | 0.48%   |
| Nanya Technology    | 1         | 0.48%   |
| GSkill              | 1         | 0.48%   |
| Apacer              | 1         | 0.48%   |
| 09490000802C        | 1         | 0.48%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 4.23%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 3.29%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 2.35%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 2.35%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 5         | 2.35%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 2.35%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.88%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.88%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 1.88%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.41%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 3         | 1.41%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 3         | 1.41%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.41%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 3         | 1.41%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.94%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 2         | 0.94%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s             | 2         | 0.94%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.94%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.94%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.94%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 2         | 0.94%   |
| Samsung RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.94%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.94%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.94%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.94%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.94%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.94%   |
| Micron RAM Module 8GB SODIMM DDR3 1600MT/s                       | 2         | 0.94%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 2         | 0.94%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 0.94%   |
| Unknown                                                          | 2         | 0.94%   |
| Unknown SODIMM 4GB SODIMM 800MT/s                                | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.47%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 1         | 0.47%   |
| Unknown RAM GD2.09293S.001 16GB SODIMM DDR4 2400MT/s             | 1         | 0.47%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR2 667MT/s                | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 81        | 49.39%  |
| DDR4    | 66        | 40.24%  |
| DDR2    | 6         | 3.66%   |
| LPDDR4  | 4         | 2.44%   |
| LPDDR3  | 3         | 1.83%   |
| DDR     | 2         | 1.22%   |
| Unknown | 2         | 1.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 157       | 95.73%  |
| Row Of Chips | 7         | 4.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 80        | 43.72%  |
| 4096  | 72        | 39.34%  |
| 16384 | 14        | 7.65%   |
| 2048  | 14        | 7.65%   |
| 32768 | 2         | 1.09%   |
| 1024  | 1         | 0.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 57        | 32.39%  |
| 2667    | 29        | 16.48%  |
| 2400    | 21        | 11.93%  |
| 3200    | 17        | 9.66%   |
| 1334    | 12        | 6.82%   |
| 2133    | 9         | 5.11%   |
| 1333    | 9         | 5.11%   |
| 800     | 6         | 3.41%   |
| 667     | 4         | 2.27%   |
| Unknown | 4         | 2.27%   |
| 1067    | 3         | 1.7%    |
| 4266    | 2         | 1.14%   |
| 1867    | 2         | 1.14%   |
| 1200    | 1         | 0.57%   |

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
| Chicony Electronics                    | 33        | 26.19%  |
| Realtek Semiconductor                  | 15        | 11.9%   |
| Microdia                               | 13        | 10.32%  |
| IMC Networks                           | 12        | 9.52%   |
| Bison Electronics                      | 12        | 9.52%   |
| Sunplus Innovation Technology          | 9         | 7.14%   |
| Suyin                                  | 6         | 4.76%   |
| Quanta                                 | 6         | 4.76%   |
| Alcor Micro                            | 4         | 3.17%   |
| Syntek                                 | 2         | 1.59%   |
| Silicon Motion                         | 2         | 1.59%   |
| Ricoh                                  | 2         | 1.59%   |
| Lite-On Technology                     | 2         | 1.59%   |
| OmniVision Technologies                | 1         | 0.79%   |
| Luxvisions Innotech Limited            | 1         | 0.79%   |
| Logitech                               | 1         | 0.79%   |
| Lenovo                                 | 1         | 0.79%   |
| Jiangxi Shinetech Optical              | 1         | 0.79%   |
| Intel                                  | 1         | 0.79%   |
| Importek                               | 1         | 0.79%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 0.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 9         | 7.14%   |
| Bison Integrated Camera                  | 7         | 5.56%   |
| Sunplus Integrated_Webcam_HD             | 5         | 3.97%   |
| Microdia Integrated_Webcam_HD            | 5         | 3.97%   |
| Microdia Integrated Webcam               | 5         | 3.97%   |
| IMC Networks Integrated Camera           | 5         | 3.97%   |
| Realtek USB 2.0 PC Camera                | 3         | 2.38%   |
| Realtek Integrated_Webcam_HD             | 3         | 2.38%   |
| Chicony USB2.0 HD UVC WebCam             | 3         | 2.38%   |
| Chicony HD WebCam                        | 3         | 2.38%   |
| Suyin Integrated_Webcam_HD               | 2         | 1.59%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 2         | 1.59%   |
| Sunplus Laptop_Integrated_Webcam_FHD     | 2         | 1.59%   |
| Realtek Lenovo EasyCamera                | 2         | 1.59%   |
| Realtek Integrated Webcam HD             | 2         | 1.59%   |
| Realtek Front Camera                     | 2         | 1.59%   |
| Quanta VGA WebCam                        | 2         | 1.59%   |
| Quanta HP TrueVision HD Camera           | 2         | 1.59%   |
| IMC Networks Realtek PC Camera           | 2         | 1.59%   |
| IMC Networks Realtek DMFT RGB            | 2         | 1.59%   |
| Chicony Realtek DMFT RGB                 | 2         | 1.59%   |
| Chicony Integrated Camera (1280x720@30)  | 2         | 1.59%   |
| Bison ThinkPad P50 Integrated Camera     | 2         | 1.59%   |
| Bison ThinkPad Integrated Camera         | 2         | 1.59%   |
| Alcor Micro USB 2.0 Camera               | 2         | 1.59%   |
| Syntek USB 2.0 UVC 1.3M WebCam           | 1         | 0.79%   |
| Syntek Lenovo EasyCamera                 | 1         | 0.79%   |
| Suyin RGBIR Camera                       | 1         | 0.79%   |
| Suyin HD WebCam                          | 1         | 0.79%   |
| Sunplus SPCA2085 PC Camera               | 1         | 0.79%   |
| Sunplus MTD camera                       | 1         | 0.79%   |
| Silicon Motion WebCam SC-13HDL11939N     | 1         | 0.79%   |
| Silicon Motion Realtek USB 2.0 PC Camera | 1         | 0.79%   |
| Ricoh USB2.0 Camera                      | 1         | 0.79%   |
| Ricoh HD Webcam                          | 1         | 0.79%   |
| Realtek USB Camera                       | 1         | 0.79%   |
| Realtek USB 2.0 Webcam                   | 1         | 0.79%   |
| Realtek Dell EasyCamera                  | 1         | 0.79%   |
| Quanta Realtek PC Camera                 | 1         | 0.79%   |
| Quanta HP Universal Camera               | 1         | 0.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 34.62%  |
| Synaptics                  | 4         | 15.38%  |
| Upek                       | 3         | 11.54%  |
| STMicroelectronics         | 2         | 7.69%   |
| Shenzhen Goodix Technology | 2         | 7.69%   |
| Next Biometrics            | 1         | 3.85%   |
| LighTuning Technology      | 1         | 3.85%   |
| FocalTech Systems          | 1         | 3.85%   |
| Elan Microelectronics      | 1         | 3.85%   |
| Broadcom                   | 1         | 3.85%   |
| AuthenTec                  | 1         | 3.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 5         | 19.23%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 7.69%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 2         | 7.69%   |
| STMicroelectronics Fingerprint Reader                                        | 2         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 7.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 3.85%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 3.85%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 3.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 1         | 3.85%   |
| Upek TCS5B Fingerprint sensor                                                | 1         | 3.85%   |
| Synaptics WBDI                                                               | 1         | 3.85%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 3.85%   |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 3.85%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 1         | 3.85%   |
| FocalTech Systems Fingerprint Reader                                         | 1         | 3.85%   |
| Elan Fingerprint Sensor                                                      | 1         | 3.85%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.85%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 3.85%   |

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
| 2     | 56        | 33.33%  |
| 1     | 40        | 23.81%  |
| 3     | 35        | 20.83%  |
| 4     | 21        | 12.5%   |
| 0     | 12        | 7.14%   |
| 5     | 4         | 2.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 120       | 35.82%  |
| Bluetooth                | 84        | 25.07%  |
| Net/wireless             | 43        | 12.84%  |
| Card reader              | 38        | 11.34%  |
| Fingerprint reader       | 27        | 8.06%   |
| Firewire controller      | 10        | 2.99%   |
| Network                  | 7         | 2.09%   |
| Storage                  | 4         | 1.19%   |
| Sound                    | 1         | 0.3%    |
| Net/ethernet             | 1         | 0.3%    |

