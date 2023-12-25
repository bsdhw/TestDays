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

Total: 257

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T480 20L6S8LW00    | [32c06c5669](https://bsd-hardware.info/?probe=32c06c5669) | Dec 23, 2023 |
| Apple         | MacBookPro9,2               | [851f118bd5](https://bsd-hardware.info/?probe=851f118bd5) | Dec 19, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [5281bb9e20](https://bsd-hardware.info/?probe=5281bb9e20) | Dec 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d81a233601](https://bsd-hardware.info/?probe=d81a233601) | Dec 12, 2023 |
| Dell          | Inspiron 5559               | [09f5b25e72](https://bsd-hardware.info/?probe=09f5b25e72) | Dec 12, 2023 |
| Dell          | Latitude E6330              | [7e0a01e9ad](https://bsd-hardware.info/?probe=7e0a01e9ad) | Dec 05, 2023 |
| Dell          | Inspiron 7558               | [b34a8742d5](https://bsd-hardware.info/?probe=b34a8742d5) | Nov 26, 2023 |
| Dell          | Inspiron 7558               | [aad8d359f3](https://bsd-hardware.info/?probe=aad8d359f3) | Nov 24, 2023 |
| Dell          | Latitude E5440              | [629fba28cc](https://bsd-hardware.info/?probe=629fba28cc) | Nov 23, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [19dfa9e36a](https://bsd-hardware.info/?probe=19dfa9e36a) | Nov 21, 2023 |
| Dell          | Precision 5520              | [45f5e399a4](https://bsd-hardware.info/?probe=45f5e399a4) | Nov 18, 2023 |
| HP            | Notebook                    | [c583c221c7](https://bsd-hardware.info/?probe=c583c221c7) | Nov 17, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0fd2711a56](https://bsd-hardware.info/?probe=0fd2711a56) | Nov 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d87ea88953](https://bsd-hardware.info/?probe=d87ea88953) | Nov 09, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [05bf5fb9f4](https://bsd-hardware.info/?probe=05bf5fb9f4) | Nov 07, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [19514dd0bd](https://bsd-hardware.info/?probe=19514dd0bd) | Nov 03, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [965e71ac80](https://bsd-hardware.info/?probe=965e71ac80) | Oct 21, 2023 |
| Dell          | Latitude 5490               | [eeab525ffd](https://bsd-hardware.info/?probe=eeab525ffd) | Oct 20, 2023 |
| ASUSTek       | N552VX                      | [f927cf5ba4](https://bsd-hardware.info/?probe=f927cf5ba4) | Oct 16, 2023 |
| Fujitsu       | LIFEBOOK E744               | [72a9b731f6](https://bsd-hardware.info/?probe=72a9b731f6) | Oct 14, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [36daf066ca](https://bsd-hardware.info/?probe=36daf066ca) | Oct 08, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2AD0... | [ac6742bd0f](https://bsd-hardware.info/?probe=ac6742bd0f) | Oct 07, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2AD0... | [3e15173331](https://bsd-hardware.info/?probe=3e15173331) | Oct 07, 2023 |
| Apple         | MacBookPro7,1               | [070c5dab4f](https://bsd-hardware.info/?probe=070c5dab4f) | Oct 02, 2023 |
| ASUSTek       | K40IN                       | [6b58792f5e](https://bsd-hardware.info/?probe=6b58792f5e) | Oct 02, 2023 |
| Acer          | TravelMate 5730             | [dffc2e116d](https://bsd-hardware.info/?probe=dffc2e116d) | Sep 30, 2023 |
| Apple         | MacBookPro9,1               | [b0aca42c84](https://bsd-hardware.info/?probe=b0aca42c84) | Sep 29, 2023 |
| MSI           | CX62 6QD                    | [68b8b9f531](https://bsd-hardware.info/?probe=68b8b9f531) | Sep 29, 2023 |
| TUXEDO        | Aura 15 Gen1                | [b31f8c12f8](https://bsd-hardware.info/?probe=b31f8c12f8) | Sep 24, 2023 |
| Lenovo        | ThinkPad T470 20HES0HU00    | [a64fe205a9](https://bsd-hardware.info/?probe=a64fe205a9) | Sep 17, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [0f92b89ffb](https://bsd-hardware.info/?probe=0f92b89ffb) | Sep 09, 2023 |
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
| GhostBSD 20.04.02 | 58        | 29.15%  |
| GhostBSD 21.08.27 | 29        | 14.57%  |
| GhostBSD 22.01.12 | 13        | 6.53%   |
| GhostBSD 23.10.1  | 12        | 6.03%   |
| GhostBSD 23.06.01 | 11        | 5.53%   |
| GhostBSD 22.06.18 | 10        | 5.03%   |
| GhostBSD 23.02.02 | 6         | 3.02%   |
| GhostBSD 23.07.13 | 4         | 2.01%   |
| GhostBSD 23.07.29 | 3         | 1.51%   |
| GhostBSD 23.06.05 | 3         | 1.51%   |
| GhostBSD 22.06.26 | 3         | 1.51%   |
| GhostBSD 23.09.16 | 2         | 1.01%   |
| GhostBSD 23.09.06 | 2         | 1.01%   |
| GhostBSD 23.07.20 | 2         | 1.01%   |
| GhostBSD 23.05.22 | 2         | 1.01%   |
| GhostBSD 23.04.23 | 2         | 1.01%   |
| GhostBSD 23.03.17 | 2         | 1.01%   |
| GhostBSD 22.11.22 | 2         | 1.01%   |
| GhostBSD 22.11.02 | 2         | 1.01%   |
| GhostBSD 22.08.23 | 2         | 1.01%   |
| GhostBSD 22.08.06 | 2         | 1.01%   |
| GhostBSD 22.07.16 | 2         | 1.01%   |
| GhostBSD 23.10.09 | 1         | 0.5%    |
| GhostBSD 23.09.29 | 1         | 0.5%    |
| GhostBSD 23.07.04 | 1         | 0.5%    |
| GhostBSD 23.06.22 | 1         | 0.5%    |
| GhostBSD 23.05.18 | 1         | 0.5%    |
| GhostBSD 23.04.02 | 1         | 0.5%    |
| GhostBSD 23.01.13 | 1         | 0.5%    |
| GhostBSD 22.10.30 | 1         | 0.5%    |
| GhostBSD 22.09.16 | 1         | 0.5%    |
| GhostBSD 22.08.27 | 1         | 0.5%    |
| GhostBSD 22.07.31 | 1         | 0.5%    |
| GhostBSD 22.07.28 | 1         | 0.5%    |
| GhostBSD 22.07.13 | 1         | 0.5%    |
| GhostBSD 22.07.10 | 1         | 0.5%    |
| GhostBSD 22.06.20 | 1         | 0.5%    |
| GhostBSD 22.06.07 | 1         | 0.5%    |
| GhostBSD 22.05.13 | 1         | 0.5%    |
| GhostBSD 22.04.30 | 1         | 0.5%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| GhostBSD | 183       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 183       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| MATE         | 146       | 78.49%  |
| XFCE         | 27        | 14.52%  |
| KDE5         | 8         | 4.3%    |
| Cinnamon     | 2         | 1.08%   |
| helloDesktop | 1         | 0.54%   |
| GNOME        | 1         | 0.54%   |
| Console      | 1         | 0.54%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 181       | 98.91%  |
| Wayland | 1         | 0.55%   |
| Console | 1         | 0.55%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 180       | 98.36%  |
| SDDM    | 2         | 1.09%   |
| Console | 1         | 0.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 75        | 39.06%  |
| C       | 67        | 34.9%   |
| Unknown | 16        | 8.33%   |
| de_DE   | 9         | 4.69%   |
| pt_BR   | 4         | 2.08%   |
| es_ES   | 4         | 2.08%   |
| en_GB   | 4         | 2.08%   |
| pl_PL   | 3         | 1.56%   |
| it_IT   | 3         | 1.56%   |
| ru_RU   | 2         | 1.04%   |
| zh_CN   | 1         | 0.52%   |
| sv_SE   | 1         | 0.52%   |
| sk_SK   | 1         | 0.52%   |
| en_NZ   | 1         | 0.52%   |
| el_GR   | 1         | 0.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 144       | 78.69%  |
| BIOS | 39        | 21.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 175       | 93.58%  |
| Ufs  | 12        | 6.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 180       | 98.36%  |
| MBR  | 3         | 1.64%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 51        | 27.87%  |
| Dell                | 42        | 22.95%  |
| Hewlett-Packard     | 17        | 9.29%   |
| ASUSTek Computer    | 15        | 8.2%    |
| Acer                | 12        | 6.56%   |
| MSI                 | 7         | 3.83%   |
| Apple               | 7         | 3.83%   |
| Sony                | 4         | 2.19%   |
| Notebook            | 4         | 2.19%   |
| Fujitsu             | 4         | 2.19%   |
| Toshiba             | 3         | 1.64%   |
| System76            | 3         | 1.64%   |
| Samsung Electronics | 3         | 1.64%   |
| TUXEDO              | 2         | 1.09%   |
| Star Labs           | 2         | 1.09%   |
| Panasonic           | 1         | 0.55%   |
| MouseComputer       | 1         | 0.55%   |
| Jumper              | 1         | 0.55%   |
| HUAWEI              | 1         | 0.55%   |
| GPU Company         | 1         | 0.55%   |
| Alienware           | 1         | 0.55%   |
| Unknown             | 1         | 0.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Inspiron 3542                       | 3         | 1.64%   |
| MSI Modern 14 A10M                       | 2         | 1.09%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS       | 2         | 1.09%   |
| Lenovo ThinkPad T430s 2352CTO            | 2         | 1.09%   |
| Dell XPS 13 7390                         | 2         | 1.09%   |
| Dell Latitude E6420                      | 2         | 1.09%   |
| Dell Latitude E5440                      | 2         | 1.09%   |
| Dell Latitude 7490                       | 2         | 1.09%   |
| ASUS ZenBook UX325UA_UM325UA             | 2         | 1.09%   |
| Unknown                                  | 2         | 1.09%   |
| TUXEDO InfinityBook13V3                  | 1         | 0.55%   |
| TUXEDO Aura 15 Gen1                      | 1         | 0.55%   |
| Toshiba Satellite L655                   | 1         | 0.55%   |
| Toshiba Satellite C855-1U4               | 1         | 0.55%   |
| Toshiba Satellite C855                   | 1         | 0.55%   |
| System76 Lemur Pro                       | 1         | 0.55%   |
| System76 Kudu                            | 1         | 0.55%   |
| System76 Gazelle                         | 1         | 0.55%   |
| Star Labs StarBook                       | 1         | 0.55%   |
| Star Labs LabTop                         | 1         | 0.55%   |
| Sony VPCCB17FG                           | 1         | 0.55%   |
| Sony VGN-SZ3VWP_X                        | 1         | 0.55%   |
| Sony SVP1322M1EBI                        | 1         | 0.55%   |
| Sony SVP13225SCBI                        | 1         | 0.55%   |
| Samsung Q210                             | 1         | 0.55%   |
| Samsung 550P5C/550P7C                    | 1         | 0.55%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV | 1         | 0.55%   |
| Panasonic CF-19AHNC8FN                   | 1         | 0.55%   |
| Notebook N8xEJEK                         | 1         | 0.55%   |
| Notebook N85_N87,HJ,HJ1,HK1              | 1         | 0.55%   |
| Notebook N7x0WU                          | 1         | 0.55%   |
| Notebook N13xWU                          | 1         | 0.55%   |
| MSI Sword 17 A11UD                       | 1         | 0.55%   |
| MSI GF63 Thin 10SCSR                     | 1         | 0.55%   |
| MSI GE75 Raider 10SFS                    | 1         | 0.55%   |
| MSI GE62 6QC                             | 1         | 0.55%   |
| MSI CX62 6QD                             | 1         | 0.55%   |
| MouseComputer X5-aR5CEZAR-WA             | 1         | 0.55%   |
| Lenovo Yoga 2 13 20344                   | 1         | 0.55%   |
| Lenovo V15 G2 ALC 82KD                   | 1         | 0.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 37        | 20.22%  |
| Dell Latitude           | 20        | 10.93%  |
| Dell Inspiron           | 15        | 8.2%    |
| Acer Aspire             | 8         | 4.37%   |
| Lenovo IdeaPad          | 5         | 2.73%   |
| HP Laptop               | 5         | 2.73%   |
| Toshiba Satellite       | 3         | 1.64%   |
| Lenovo Yoga             | 3         | 1.64%   |
| Lenovo Legion           | 3         | 1.64%   |
| HP EliteBook            | 3         | 1.64%   |
| Dell XPS                | 3         | 1.64%   |
| Dell Precision          | 3         | 1.64%   |
| ASUS VivoBook           | 3         | 1.64%   |
| MSI Modern              | 2         | 1.09%   |
| HP OMEN                 | 2         | 1.09%   |
| Fujitsu LIFEBOOK        | 2         | 1.09%   |
| ASUS ZenBook            | 2         | 1.09%   |
| Apple MacBookPro9       | 2         | 1.09%   |
| Acer TravelMate         | 2         | 1.09%   |
| Unknown                 | 2         | 1.09%   |
| TUXEDO InfinityBook13V3 | 1         | 0.55%   |
| TUXEDO Aura             | 1         | 0.55%   |
| System76 Lemur          | 1         | 0.55%   |
| System76 Kudu           | 1         | 0.55%   |
| System76 Gazelle        | 1         | 0.55%   |
| Star Labs StarBook      | 1         | 0.55%   |
| Star Labs LabTop        | 1         | 0.55%   |
| Sony VPCCB17FG          | 1         | 0.55%   |
| Sony VGN-SZ3VWP         | 1         | 0.55%   |
| Sony SVP1322M1EBI       | 1         | 0.55%   |
| Sony SVP13225SCBI       | 1         | 0.55%   |
| Samsung Q210            | 1         | 0.55%   |
| Samsung 550P5C          | 1         | 0.55%   |
| Samsung 3570R           | 1         | 0.55%   |
| Panasonic CF-19AHNC8FN  | 1         | 0.55%   |
| Notebook N8xEJEK        | 1         | 0.55%   |
| Notebook N85            | 1         | 0.55%   |
| Notebook N7x0WU         | 1         | 0.55%   |
| Notebook N13xWU         | 1         | 0.55%   |
| MSI Sword               | 1         | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 26        | 14.21%  |
| 2018 | 17        | 9.29%   |
| 2013 | 17        | 9.29%   |
| 2021 | 15        | 8.2%    |
| 2014 | 14        | 7.65%   |
| 2016 | 13        | 7.1%    |
| 2022 | 11        | 6.01%   |
| 2011 | 11        | 6.01%   |
| 2019 | 10        | 5.46%   |
| 2015 | 10        | 5.46%   |
| 2012 | 10        | 5.46%   |
| 2017 | 9         | 4.92%   |
| 2009 | 7         | 3.83%   |
| 2008 | 5         | 2.73%   |
| 2010 | 4         | 2.19%   |
| 2023 | 3         | 1.64%   |
| 2007 | 1         | 0.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 183       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 181       | 98.91%  |
| Yes  | 2         | 1.09%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 90        | 48.65%  |
| 16.01-24.0  | 56        | 30.27%  |
| 4.01-8.0    | 29        | 15.68%  |
| 24.01-32.0  | 4         | 2.16%   |
| 32.01-64.0  | 3         | 1.62%   |
| 64.01-256.0 | 2         | 1.08%   |
| 2.01-3.0    | 1         | 0.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 83        | 44.15%  |
| 0.51-1.0   | 73        | 38.83%  |
| 1.01-2.0   | 16        | 8.51%   |
| 2.01-3.0   | 13        | 6.91%   |
| 4.01-8.0   | 2         | 1.06%   |
| 24.01-32.0 | 1         | 0.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 138       | 74.59%  |
| 2      | 34        | 18.38%  |
| 0      | 11        | 5.95%   |
| 3      | 2         | 1.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 113       | 61.41%  |
| Yes       | 71        | 38.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 156       | 85.25%  |
| No        | 27        | 14.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 182       | 99.45%  |
| No        | 1         | 0.55%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 146       | 79.78%  |
| No        | 37        | 20.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 42        | 22.83%  |
| Germany      | 22        | 11.96%  |
| UK           | 10        | 5.43%   |
| France       | 9         | 4.89%   |
| Spain        | 8         | 4.35%   |
| Poland       | 8         | 4.35%   |
| Russia       | 7         | 3.8%    |
| Italy        | 6         | 3.26%   |
| Taiwan       | 4         | 2.17%   |
| Japan        | 4         | 2.17%   |
| Indonesia    | 4         | 2.17%   |
| India        | 4         | 2.17%   |
| Canada       | 4         | 2.17%   |
| Brazil       | 4         | 2.17%   |
| Switzerland  | 3         | 1.63%   |
| Sweden       | 3         | 1.63%   |
| New Zealand  | 3         | 1.63%   |
| South Africa | 2         | 1.09%   |
| Slovenia     | 2         | 1.09%   |
| Slovakia     | 2         | 1.09%   |
| Portugal     | 2         | 1.09%   |
| Philippines  | 2         | 1.09%   |
| Norway       | 2         | 1.09%   |
| Netherlands  | 2         | 1.09%   |
| Mauritius    | 2         | 1.09%   |
| Hong Kong    | 2         | 1.09%   |
| Finland      | 2         | 1.09%   |
| China        | 2         | 1.09%   |
| Bulgaria     | 2         | 1.09%   |
| Belgium      | 2         | 1.09%   |
| Ukraine      | 1         | 0.54%   |
| Uganda       | 1         | 0.54%   |
| Turkey       | 1         | 0.54%   |
| Serbia       | 1         | 0.54%   |
| Namibia      | 1         | 0.54%   |
| Malaysia     | 1         | 0.54%   |
| Kazakhstan   | 1         | 0.54%   |
| Hungary      | 1         | 0.54%   |
| Greece       | 1         | 0.54%   |
| El Salvador  | 1         | 0.54%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Bedburg            | 6         | 3.13%   |
| Indian Trail       | 4         | 2.08%   |
| Saratov            | 3         | 1.56%   |
| Rome               | 3         | 1.56%   |
| Madrid             | 3         | 1.56%   |
| Jakarta            | 3         | 1.56%   |
| Franconville       | 3         | 1.56%   |
| Chrusty            | 3         | 1.56%   |
| Bonn               | 3         | 1.56%   |
| Zurich             | 2         | 1.04%   |
| Yokohama           | 2         | 1.04%   |
| Whittier           | 2         | 1.04%   |
| Wezeren            | 2         | 1.04%   |
| Tomball            | 2         | 1.04%   |
| Taipei             | 2         | 1.04%   |
| Taichung           | 2         | 1.04%   |
| Stiring-Wendel     | 2         | 1.04%   |
| Skiatook           | 2         | 1.04%   |
| Paris              | 2         | 1.04%   |
| Oslo               | 2         | 1.04%   |
| Nuremberg          | 2         | 1.04%   |
| Milan              | 2         | 1.04%   |
| London             | 2         | 1.04%   |
| Lebanon            | 2         | 1.04%   |
| Jarosław          | 2         | 1.04%   |
| Giessen            | 2         | 1.04%   |
| Clemmons           | 2         | 1.04%   |
| Chiyoda-ku         | 2         | 1.04%   |
| Celje              | 2         | 1.04%   |
| Asnieres-sur-Seine | 2         | 1.04%   |
| Zaragoza           | 1         | 0.52%   |
| Yaroslavl          | 1         | 0.52%   |
| Wraysbury          | 1         | 0.52%   |
| Witbank            | 1         | 0.52%   |
| Winnipeg           | 1         | 0.52%   |
| Windhoek           | 1         | 0.52%   |
| Wenatchee          | 1         | 0.52%   |
| Vancouver          | 1         | 0.52%   |
| Valencia           | 1         | 0.52%   |
| Tsarevo            | 1         | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 49        | 62     | 23.22%  |
| WDC                 | 27        | 29     | 12.8%   |
| Kingston            | 22        | 22     | 10.43%  |
| Seagate             | 16        | 19     | 7.58%   |
| Toshiba             | 13        | 16     | 6.16%   |
| SK hynix            | 12        | 16     | 5.69%   |
| Crucial             | 10        | 13     | 4.74%   |
| SanDisk             | 9         | 9      | 4.27%   |
| Intel               | 7         | 7      | 3.32%   |
| Hitachi             | 5         | 5      | 2.37%   |
| A-DATA Technology   | 4         | 4      | 1.9%    |
| Phison              | 3         | 4      | 1.42%   |
| Micron Technology   | 3         | 3      | 1.42%   |
| HGST                | 3         | 3      | 1.42%   |
| Transcend           | 2         | 2      | 0.95%   |
| Star Drive          | 2         | 2      | 0.95%   |
| PNY                 | 2         | 2      | 0.95%   |
| Patriot             | 2         | 2      | 0.95%   |
| KingSpec            | 2         | 2      | 0.95%   |
| Goodram             | 2         | 2      | 0.95%   |
| Fujitsu             | 2         | 2      | 0.95%   |
| Apple               | 2         | 2      | 0.95%   |
| XUM                 | 1         | 1      | 0.47%   |
| SSSTC               | 1         | 1      | 0.47%   |
| SPCC                | 1         | 1      | 0.47%   |
| Silicon Motion      | 1         | 1      | 0.47%   |
| Plextor             | 1         | 1      | 0.47%   |
| Netac               | 1         | 1      | 0.47%   |
| LITEONIT            | 1         | 1      | 0.47%   |
| Intenso             | 1         | 1      | 0.47%   |
| Hewlett-Packard     | 1         | 1      | 0.47%   |
| Gigabyte Technology | 1         | 1      | 0.47%   |
| Dell                | 1         | 2      | 0.47%   |
| China               | 1         | 1      | 0.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB            | 5         | 2.31%   |
| WDC WD10JPVX-22JC3T0 1TB               | 3         | 1.39%   |
| Seagate ST1000LM035-1RK172 1TB         | 3         | 1.39%   |
| Samsung SSD 860 EVO 500GB              | 3         | 1.39%   |
| Samsung SSD 850 EVO 250GB              | 3         | 1.39%   |
| Kingston SA400S37120G 120GB            | 3         | 1.39%   |
| WDC WDS500G2B0A-00SM50 500GB           | 2         | 0.93%   |
| Toshiba KXG50ZNV512G NVMe 512GB        | 2         | 0.93%   |
| Toshiba KBG40ZNT512G MEMORY 512GB      | 2         | 0.93%   |
| Star Drive PCIe SSD 960GB              | 2         | 0.93%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB | 2         | 0.93%   |
| SK hynix HFM512GD3JX013N 512GB         | 2         | 0.93%   |
| Seagate ST1000LM049-2GH172 1TB         | 2         | 0.93%   |
| Samsung SSD 870 EVO 500GB              | 2         | 0.93%   |
| Samsung SSD 860 QVO 1TB                | 2         | 0.93%   |
| Samsung SSD 860 EVO 1TB                | 2         | 0.93%   |
| Samsung PM981 NVMe 256GB               | 2         | 0.93%   |
| Samsung MZNTE128HMGR-000SO 128GB       | 2         | 0.93%   |
| Kingston SV300S37A240G 240GB           | 2         | 0.93%   |
| Kingston SA400S37960G 960GB            | 2         | 0.93%   |
| Kingston RBUSNS8154P3512GJ 512GB       | 2         | 0.93%   |
| KingSpec Q-720 720GB                   | 2         | 0.93%   |
| Intel SSDPEKKF256G8L 256GB             | 2         | 0.93%   |
| Hitachi HTS541612J9SA00 120GB          | 2         | 0.93%   |
| XUM HX256GSSDSATA3 256GB               | 1         | 0.46%   |
| WDC WDS240G2G0A-00JH30 240GB           | 1         | 0.46%   |
| WDC WDS120G2G0A-00JH30 120GB           | 1         | 0.46%   |
| WDC WDS100T3X0C-00SJG0 1TB             | 1         | 0.46%   |
| WDC WDS100T2B0B-00YS70 1TB             | 1         | 0.46%   |
| WDC WDS100T1B0A-00H9H0 1TB             | 1         | 0.46%   |
| WDC WD7500BPVT-80HXZT3 752GB           | 1         | 0.46%   |
| WDC WD7500BPKX-80HPJT0 752GB           | 1         | 0.46%   |
| WDC WD7500BPKX-00HPJT0 752GB           | 1         | 0.46%   |
| WDC WD6400BEVT-22A0RT0 640GB           | 1         | 0.46%   |
| WDC WD5000LPCX-24C6HT0 500GB           | 1         | 0.46%   |
| WDC WD5000BPVT-00HXZT3 500GB           | 1         | 0.46%   |
| WDC WD3200LPVX-75V0TT0 320GB           | 1         | 0.46%   |
| WDC WD10SPZX-75Z10T3 1TB               | 1         | 0.46%   |
| WDC WD10SPZX-75Z10T2 1TB               | 1         | 0.46%   |
| WDC WD10SPZX-24Z10T0 1TB               | 1         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 17     | 32%     |
| Seagate             | 16        | 19     | 32%     |
| Toshiba             | 5         | 5      | 10%     |
| Hitachi             | 5         | 5      | 10%     |
| HGST                | 3         | 3      | 6%      |
| Samsung Electronics | 2         | 2      | 4%      |
| Fujitsu             | 2         | 2      | 4%      |
| Apple               | 1         | 1      | 2%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 29        | 38     | 28.43%  |
| Kingston            | 18        | 18     | 17.65%  |
| SanDisk             | 9         | 9      | 8.82%   |
| Crucial             | 8         | 10     | 7.84%   |
| WDC                 | 6         | 6      | 5.88%   |
| SK hynix            | 5         | 5      | 4.9%    |
| Transcend           | 2         | 2      | 1.96%   |
| Toshiba             | 2         | 3      | 1.96%   |
| PNY                 | 2         | 2      | 1.96%   |
| Patriot             | 2         | 2      | 1.96%   |
| Micron Technology   | 2         | 2      | 1.96%   |
| KingSpec            | 2         | 2      | 1.96%   |
| Intel               | 2         | 2      | 1.96%   |
| GOODRAM             | 2         | 2      | 1.96%   |
| A-DATA Technology   | 2         | 2      | 1.96%   |
| XUM                 | 1         | 1      | 0.98%   |
| SPCC                | 1         | 1      | 0.98%   |
| Plextor             | 1         | 1      | 0.98%   |
| Phison              | 1         | 1      | 0.98%   |
| Netac               | 1         | 1      | 0.98%   |
| LITEONIT            | 1         | 1      | 0.98%   |
| Dell                | 1         | 2      | 0.98%   |
| China               | 1         | 1      | 0.98%   |
| Apple               | 1         | 1      | 0.98%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 94        | 115    | 48.21%  |
| NVMe | 54        | 72     | 27.69%  |
| HDD  | 47        | 54     | 24.1%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 132       | 169    | 70.97%  |
| NVMe | 54        | 72     | 29.03%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 95        | 110    | 67.38%  |
| 0.51-1.0   | 41        | 53     | 29.08%  |
| 1.01-2.0   | 5         | 6      | 3.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 63        | 32.47%  |
| 101-250    | 45        | 23.2%   |
| 251-500    | 31        | 15.98%  |
| 501-1000   | 20        | 10.31%  |
| 51-100     | 17        | 8.76%   |
| Unknown    | 11        | 5.67%   |
| 21-50      | 5         | 2.58%   |
| 1001-2000  | 2         | 1.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 165       | 86.39%  |
| 21-50   | 12        | 6.28%   |
| Unknown | 11        | 5.76%   |
| 51-100  | 2         | 1.05%   |
| 101-250 | 1         | 0.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| Kingston SA400S37240G 240GB                     | 2         | 2      | 7.41%   |
| Hitachi HTS541612J9SA00 120GB                   | 2         | 2      | 7.41%   |
| WDC WD6400BEVT-22A0RT0 640GB                    | 1         | 1      | 3.7%    |
| WDC WD3200LPVX-75V0TT0 320GB                    | 1         | 1      | 3.7%    |
| Toshiba MQ01ACF032 320GB                        | 1         | 1      | 3.7%    |
| Toshiba MK1252GSX 120GB                         | 1         | 1      | 3.7%    |
| SK hynix HFS256G39MND-2300A 256GB               | 1         | 1      | 3.7%    |
| Seagate ST9250827AS 250GB                       | 1         | 1      | 3.7%    |
| Seagate ST500LT012-9WS142 500GB                 | 1         | 2      | 3.7%    |
| Seagate ST500LM021-1KJ152 500GB                 | 1         | 1      | 3.7%    |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 3.7%    |
| Seagate ST1000LM035-1RK172 1TB                  | 1         | 2      | 3.7%    |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 1         | 1      | 3.7%    |
| Samsung Electronics SSD 980 500GB               | 1         | 1      | 3.7%    |
| Samsung Electronics SSD 870 EVO 500GB           | 1         | 1      | 3.7%    |
| Samsung Electronics SSD 840 PRO Series 256GB    | 1         | 1      | 3.7%    |
| Samsung Electronics MZNTE128HMGR-000SO 128GB    | 1         | 1      | 3.7%    |
| Samsung Electronics HM320JI 320GB               | 1         | 1      | 3.7%    |
| Patriot Inferno 60GB SSD                        | 1         | 1      | 3.7%    |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB | 1         | 1      | 3.7%    |
| Intel SSDSC2BF180A5L 180GB                      | 1         | 1      | 3.7%    |
| Intel SSDSC2BF180A4L 180GB                      | 1         | 1      | 3.7%    |
| Hitachi HTS543225L9A300 250GB                   | 1         | 1      | 3.7%    |
| HGST HTS721010A9E630 1TB                        | 1         | 1      | 3.7%    |
| HGST HTS541010A9E680 1TB                        | 1         | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 8      | 22.22%  |
| Samsung Electronics | 5         | 5      | 18.52%  |
| Hitachi             | 3         | 3      | 11.11%  |
| WDC                 | 2         | 2      | 7.41%   |
| Toshiba             | 2         | 2      | 7.41%   |
| Kingston            | 2         | 2      | 7.41%   |
| Intel               | 2         | 2      | 7.41%   |
| HGST                | 2         | 2      | 7.41%   |
| SK hynix            | 1         | 1      | 3.7%    |
| Patriot             | 1         | 1      | 3.7%    |
| Micron Technology   | 1         | 1      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 8      | 37.5%   |
| Hitachi             | 3         | 3      | 18.75%  |
| WDC                 | 2         | 2      | 12.5%   |
| Toshiba             | 2         | 2      | 12.5%   |
| HGST                | 2         | 2      | 12.5%   |
| Samsung Electronics | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 18     | 57.69%  |
| SSD  | 10        | 10     | 38.46%  |
| NVMe | 1         | 1      | 3.85%   |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 155       | 211    | 85.16%  |
| Malfunc  | 26        | 29     | 14.29%  |
| Detected | 1         | 1      | 0.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 135       | 63.38%  |
| Samsung Electronics            | 20        | 9.39%   |
| AMD                            | 16        | 7.51%   |
| SK hynix                       | 7         | 3.29%   |
| Sandisk                        | 7         | 3.29%   |
| Phison Electronics             | 5         | 2.35%   |
| Nvidia                         | 5         | 2.35%   |
| Kingston Technology Company    | 4         | 1.88%   |
| Toshiba                        | 3         | 1.41%   |
| Silicon Motion                 | 2         | 0.94%   |
| Micron/Crucial Technology      | 2         | 0.94%   |
| ADATA Technology               | 2         | 0.94%   |
| Solid State Storage Technology | 1         | 0.47%   |
| Micron Technology              | 1         | 0.47%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.47%   |
| KIOXIA                         | 1         | 0.47%   |
| Biwin Storage Technology       | 1         | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 21        | 9.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 20        | 9.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 14        | 6.42%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 14        | 6.42%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 12        | 5.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 11        | 5.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 5.05%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 9         | 4.13%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 3.21%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 2.29%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 5         | 2.29%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 2.29%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 2.29%   |
| Nvidia MCP79 AHCI Controller                                                   | 4         | 1.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 1.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 1.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 1.38%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.38%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2         | 0.92%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 0.92%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 0.92%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2         | 0.92%   |
| Phison E12 NVMe Controller                                                     | 2         | 0.92%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                 | 2         | 0.92%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 0.92%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 2         | 0.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 0.92%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.92%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 0.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 0.92%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 0.92%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 0.92%   |
| Toshiba XG5 NVMe SSD Controller                                                | 1         | 0.46%   |
| Toshiba XG4 NVMe SSD Controller                                                | 1         | 0.46%   |
| Toshiba BG3 x2 NVMe SSD Controller (DRAM-less)                                 | 1         | 0.46%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 1         | 0.46%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 0.46%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.46%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 1         | 0.46%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 137       | 65.24%  |
| NVMe | 53        | 25.24%  |
| RAID | 14        | 6.67%   |
| IDE  | 6         | 2.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 153       | 83.61%  |
| AMD    | 30        | 16.39%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz             | 7         | 3.83%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 5         | 2.73%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 5         | 2.73%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 2.19%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 2.19%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 2.19%   |
| Intel Core 2 Duo                              | 4         | 2.19%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.64%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 3         | 1.64%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.64%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 1.64%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 3         | 1.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.64%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.64%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 1.64%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 3         | 1.64%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 1.64%   |
| Intel CPU Version                             | 2         | 1.09%   |
| Intel Core i9-10980HK CPU @ 2.40GHz           | 2         | 1.09%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 1.09%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.09%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 1.09%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 2         | 1.09%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.09%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 1.09%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.09%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.09%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.09%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.09%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.09%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.09%   |
| Intel Core i5-2520M CPU @ 2.50GH              | 2         | 1.09%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 1.09%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz          | 2         | 1.09%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.09%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.09%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 1.09%   |
| AMD Ryzen 5 3450U with Radeon Vega Mobile Gfx | 2         | 1.09%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 2         | 1.09%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 59        | 32.24%  |
| Intel Core i7           | 51        | 27.87%  |
| Intel Core i3           | 12        | 6.56%   |
| Intel Core 2 Duo        | 12        | 6.56%   |
| AMD Ryzen 7             | 9         | 4.92%   |
| AMD Ryzen 5             | 9         | 4.92%   |
| Other                   | 7         | 3.83%   |
| Intel Celeron           | 5         | 2.73%   |
| AMD A6                  | 3         | 1.64%   |
| Intel Pentium           | 2         | 1.09%   |
| Intel Core i9           | 2         | 1.09%   |
| AMD Ryzen 3             | 2         | 1.09%   |
| AMD A4                  | 2         | 1.09%   |
| Intel Xeon              | 1         | 0.55%   |
| Intel Genuine           | 1         | 0.55%   |
| Intel Core 2            | 1         | 0.55%   |
| Intel Celeron Dual-Core | 1         | 0.55%   |
| AMD Ryzen 9             | 1         | 0.55%   |
| AMD Ryzen 7 PRO         | 1         | 0.55%   |
| AMD Athlon              | 1         | 0.55%   |
| AMD A10                 | 1         | 0.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 92        | 50.27%  |
| 4       | 51        | 27.87%  |
| 8       | 12        | 6.56%   |
| 6       | 8         | 4.37%   |
| Unknown | 8         | 4.37%   |
| 16      | 7         | 3.83%   |
| 12      | 5         | 2.73%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 179       | 97.81%  |
| 2      | 4         | 2.19%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 128       | 69.95%  |
| 1       | 47        | 25.68%  |
| Unknown | 8         | 4.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 34        | 18.58%  |
| IvyBridge   | 23        | 12.57%  |
| Skylake     | 19        | 10.38%  |
| Haswell     | 18        | 9.84%   |
| SandyBridge | 12        | 6.56%   |
| Penryn      | 12        | 6.56%   |
| Broadwell   | 10        | 5.46%   |
| Zen+        | 8         | 4.37%   |
| Unknown     | 7         | 3.83%   |
| Zen 3       | 6         | 3.28%   |
| Westmere    | 5         | 2.73%   |
| Zen 2       | 4         | 2.19%   |
| IceLake     | 4         | 2.19%   |
| Excavator   | 4         | 2.19%   |
| Core        | 4         | 2.19%   |
| CometLake   | 4         | 2.19%   |
| TigerLake   | 2         | 1.09%   |
| Silvermont  | 2         | 1.09%   |
| Goldmont    | 2         | 1.09%   |
| Puma        | 1         | 0.55%   |
| K10 Llano   | 1         | 0.55%   |
| K10         | 1         | 0.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 139       | 61.78%  |
| Nvidia | 50        | 22.22%  |
| AMD    | 36        | 16%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 19        | 8.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 14        | 6.09%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 12        | 5.22%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 12        | 5.22%   |
| Intel HD Graphics 5500                                                    | 10        | 4.35%   |
| Intel UHD Graphics 620                                                    | 9         | 3.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 8         | 3.48%   |
| Intel HD Graphics 620                                                     | 7         | 3.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 7         | 3.04%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 6         | 2.61%   |
| Intel HD Graphics 530                                                     | 6         | 2.61%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 6         | 2.61%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 5         | 2.17%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 4         | 1.74%   |
| Intel Core Processor Integrated Graphics Controller                       | 4         | 1.74%   |
| AMD Lucienne                                                              | 4         | 1.74%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 1.3%    |
| Nvidia C79 [GeForce 9400M]                                                | 3         | 1.3%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 3         | 1.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 3         | 1.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 3         | 1.3%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 3         | 1.3%    |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 3         | 1.3%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 3         | 1.3%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 3         | 1.3%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 3         | 1.3%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 2         | 0.87%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 2         | 0.87%   |
| Nvidia GK107GLM [Quadro K1000M]                                           | 2         | 0.87%   |
| Nvidia GF108GLM [NVS 5200M]                                               | 2         | 0.87%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 2         | 0.87%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 0.87%   |
| Intel HD Graphics 630                                                     | 2         | 0.87%   |
| Intel HD Graphics 500                                                     | 2         | 0.87%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                     | 1         | 0.43%   |
| Nvidia MCP89 [GeForce 320M]                                               | 1         | 0.43%   |
| Nvidia GT218M [NVS 3100M]                                                 | 1         | 0.43%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                     | 1         | 0.43%   |
| Nvidia GM206M [GeForce GTX 965M]                                          | 1         | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 93        | 50.54%  |
| Intel + Nvidia | 34        | 18.48%  |
| 1 x AMD        | 27        | 14.67%  |
| 1 x Nvidia     | 13        | 7.07%   |
| 2 x Intel      | 8         | 4.35%   |
| Intel + AMD    | 5         | 2.72%   |
| AMD + Nvidia   | 3         | 1.63%   |
| 2 x AMD        | 1         | 0.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 172       | 92.97%  |
| Proprietary | 13        | 7.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 160       | 85.11%  |
| 0.01-0.5   | 10        | 5.32%   |
| 1.01-2.0   | 9         | 4.79%   |
| 0.51-1.0   | 4         | 2.13%   |
| 3.01-4.0   | 3         | 1.6%    |
| 5.01-6.0   | 2         | 1.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 32        | 19.63%  |
| AU Optronics            | 31        | 19.02%  |
| LG Display              | 27        | 16.56%  |
| Samsung Electronics     | 18        | 11.04%  |
| BOE                     | 17        | 10.43%  |
| Lenovo                  | 5         | 3.07%   |
| Philips                 | 3         | 1.84%   |
| InfoVision              | 3         | 1.84%   |
| Dell                    | 3         | 1.84%   |
| CSO                     | 3         | 1.84%   |
| BenQ                    | 3         | 1.84%   |
| Apple                   | 3         | 1.84%   |
| PANDA                   | 2         | 1.23%   |
| Panasonic               | 2         | 1.23%   |
| Chi Mei Optoelectronics | 2         | 1.23%   |
| ___                     | 1         | 0.61%   |
| Sharp                   | 1         | 0.61%   |
| Iiyama                  | 1         | 0.61%   |
| IBM                     | 1         | 0.61%   |
| Hewlett-Packard         | 1         | 0.61%   |
| Goldstar                | 1         | 0.61%   |
| Fujitsu Siemens         | 1         | 0.61%   |
| BOE Technology Group    | 1         | 0.61%   |
| Unknown                 | 1         | 0.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 2         | 1.22%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch  | 2         | 1.22%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 290x170mm 13.2-inch | 2         | 1.22%   |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch              | 2         | 1.22%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch           | 2         | 1.22%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch           | 2         | 1.22%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch           | 2         | 1.22%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch           | 2         | 1.22%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 2         | 1.22%   |
| LG Display LCD Monitor LGD01E9 1920x1080 350x190mm 15.7-inch          | 2         | 1.22%   |
| CSO LCD Monitor CSO1402 2880x1800 300x190mm 14.0-inch                 | 2         | 1.22%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch      | 2         | 1.22%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch      | 2         | 1.22%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 2         | 1.22%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch       | 2         | 1.22%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch       | 2         | 1.22%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 340x190mm 15.3-inch        | 2         | 1.22%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 1.22%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 290x160mm 13.0-inch        | 2         | 1.22%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch        | 2         | 1.22%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch        | 2         | 1.22%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch         | 2         | 1.22%   |
| ___ MY TV LED TV ___0101 1920x1080                                    | 1         | 0.61%   |
| Sharp LCD Monitor SHP1453 1920x1080 350x190mm 15.7-inch               | 1         | 0.61%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch  | 1         | 0.61%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 340x190mm 15.3-inch | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 340x190mm 15.3-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC4C46 3840x2160 340x190mm 15.3-inch | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 340x190mm 15.3-inch  | 1         | 0.61%   |
| Samsung Electronics C27F398 SAM0D45 1920x1080 600x340mm 27.2-inch     | 1         | 0.61%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 1         | 0.61%   |
| Philips PHL BDM4065 PHL08E1 3840x2160 880x490mm 39.7-inch             | 1         | 0.61%   |
| PANDA LCD Monitor NCP0040 1920x1080 340x190mm 15.3-inch               | 1         | 0.61%   |
| PANDA LC133LF1L02 NCP0019 1920x1080 290x170mm 13.2-inch               | 1         | 0.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 71        | 44.94%  |
| 1366x768 (WXGA)    | 54        | 34.18%  |
| 1600x900 (HD+)     | 8         | 5.06%   |
| 3840x2160 (4K)     | 5         | 3.16%   |
| 1280x800 (WXGA)    | 5         | 3.16%   |
| 2560x1440 (QHD)    | 4         | 2.53%   |
| 2880x1800          | 3         | 1.9%    |
| 1680x1050 (WSXGA+) | 3         | 1.9%    |
| 9600x2160          | 1         | 0.63%   |
| 3840x1600          | 1         | 0.63%   |
| 2560x1600          | 1         | 0.63%   |
| 1440x900 (WXGA+)   | 1         | 0.63%   |
| 1280x1024 (SXGA)   | 1         | 0.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 75        | 45.73%  |
| 13      | 41        | 25%     |
| 17      | 10        | 6.1%    |
| 14      | 7         | 4.27%   |
| 12      | 6         | 3.66%   |
| 23      | 5         | 3.05%   |
| 11      | 5         | 3.05%   |
| 24      | 4         | 2.44%   |
| Unknown | 3         | 1.83%   |
| 27      | 2         | 1.22%   |
| 39      | 1         | 0.61%   |
| 37      | 1         | 0.61%   |
| 31      | 1         | 0.61%   |
| 22      | 1         | 0.61%   |
| 21      | 1         | 0.61%   |
| 16      | 1         | 0.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 105       | 64.42%  |
| 201-300     | 29        | 17.79%  |
| 501-600     | 11        | 6.75%   |
| 351-400     | 10        | 6.13%   |
| Unknown     | 3         | 1.84%   |
| 801-900     | 2         | 1.23%   |
| 401-500     | 2         | 1.23%   |
| 601-700     | 1         | 0.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 131       | 86.75%  |
| 16/10   | 15        | 9.93%   |
| Unknown | 2         | 1.32%   |
| 5/4     | 1         | 0.66%   |
| 3/2     | 1         | 0.66%   |
| 21/9    | 1         | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 60        | 36.59%  |
| 81-90          | 38        | 23.17%  |
| 101-110        | 15        | 9.15%   |
| 201-250        | 11        | 6.71%   |
| 71-80          | 10        | 6.1%    |
| 121-130        | 9         | 5.49%   |
| 61-70          | 6         | 3.66%   |
| 51-60          | 5         | 3.05%   |
| Unknown        | 3         | 1.83%   |
| 301-350        | 2         | 1.22%   |
| 501-1000       | 2         | 1.22%   |
| 351-500        | 1         | 0.61%   |
| 141-150        | 1         | 0.61%   |
| 111-120        | 1         | 0.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 73        | 45.06%  |
| 101-120       | 46        | 28.4%   |
| 51-100        | 21        | 12.96%  |
| 161-240       | 13        | 8.02%   |
| More than 240 | 6         | 3.7%    |
| Unknown       | 3         | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 146       | 77.66%  |
| 0     | 26        | 13.83%  |
| 2     | 16        | 8.51%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 118       | 39.73%  |
| Realtek Semiconductor             | 75        | 25.25%  |
| Qualcomm Atheros                  | 40        | 13.47%  |
| Broadcom                          | 19        | 6.4%    |
| TP-Link                           | 7         | 2.36%   |
| Sierra Wireless                   | 4         | 1.35%   |
| Samsung Electronics               | 4         | 1.35%   |
| Ericsson Business Mobile Networks | 4         | 1.35%   |
| Edimax Technology                 | 4         | 1.35%   |
| Ralink Technology                 | 3         | 1.01%   |
| Nvidia                            | 3         | 1.01%   |
| Marvell Technology Group          | 3         | 1.01%   |
| ASUSTek Computer                  | 3         | 1.01%   |
| Xiaomi                            | 1         | 0.34%   |
| Ralink                            | 1         | 0.34%   |
| Qualcomm Atheros Communications   | 1         | 0.34%   |
| Qualcomm                          | 1         | 0.34%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.34%   |
| NetGear                           | 1         | 0.34%   |
| Huawei Technologies               | 1         | 0.34%   |
| Hewlett-Packard                   | 1         | 0.34%   |
| Generic                           | 1         | 0.34%   |
| Dell                              | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 50        | 13.33%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 4.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 3.73%   |
| Intel Wireless 8265 / 8275                                        | 14        | 3.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 2.67%   |
| Intel Wireless 8260                                               | 10        | 2.67%   |
| Intel Wireless 7265                                               | 10        | 2.67%   |
| Intel Wi-Fi 6 AX200                                               | 10        | 2.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 9         | 2.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 2.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 2.13%   |
| Intel Wireless 7260                                               | 8         | 2.13%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 1.87%   |
| Intel Wireless 3165                                               | 6         | 1.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.6%    |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.33%   |
| Intel Centrino Ultimate-N 6300                                    | 5         | 1.33%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 1.07%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 4         | 1.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.07%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 1.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.07%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3         | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.8%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 0.8%    |
| Nvidia MCP79 Ethernet                                             | 3         | 0.8%    |
| Intel Wireless 3160                                               | 3         | 0.8%    |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.8%    |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 0.8%    |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.8%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 3         | 0.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.8%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 0.53%   |
| Sierra Wireless EM7455                                            | 2         | 0.53%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 2         | 0.53%   |
| Ralink RT5370 Wireless Adapter                                    | 2         | 0.53%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.53%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 113       | 55.39%  |
| Qualcomm Atheros                | 31        | 15.2%   |
| Realtek Semiconductor           | 25        | 12.25%  |
| Broadcom                        | 12        | 5.88%   |
| TP-Link                         | 7         | 3.43%   |
| Edimax Technology               | 4         | 1.96%   |
| Sierra Wireless                 | 3         | 1.47%   |
| Ralink Technology               | 3         | 1.47%   |
| ASUSTek Computer                | 3         | 1.47%   |
| Ralink                          | 1         | 0.49%   |
| Qualcomm Atheros Communications | 1         | 0.49%   |
| NetGear                         | 1         | 0.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 14        | 6.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 4.88%   |
| Intel Wireless 8260                                            | 10        | 4.88%   |
| Intel Wireless 7265                                            | 10        | 4.88%   |
| Intel Wi-Fi 6 AX200                                            | 10        | 4.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 4.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 8         | 3.9%    |
| Intel Wireless 7260                                            | 8         | 3.9%    |
| Intel Wireless 3165                                            | 6         | 2.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 2.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 2.44%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 2.44%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 4         | 1.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.95%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 1.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 1.95%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 1.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 1.46%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 1.46%   |
| Intel Wireless 3160                                            | 3         | 1.46%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 1.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.46%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 0.98%   |
| Sierra Wireless EM7455                                         | 2         | 0.98%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2         | 0.98%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 0.98%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 0.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 0.98%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 2         | 0.98%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 0.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 0.98%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 0.98%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 0.98%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 2         | 0.98%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 2         | 0.98%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 65        | 40.63%  |
| Intel                         | 59        | 36.88%  |
| Qualcomm Atheros              | 12        | 7.5%    |
| Broadcom                      | 11        | 6.88%   |
| Samsung Electronics           | 4         | 2.5%    |
| Nvidia                        | 3         | 1.88%   |
| Marvell Technology Group      | 3         | 1.88%   |
| Xiaomi                        | 1         | 0.63%   |
| Qualcomm                      | 1         | 0.63%   |
| OnePlus Technology (Shenzhen) | 1         | 0.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 50        | 31.06%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 11.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 8.7%    |
| Intel Ethernet Connection (4) I219-LM                             | 9         | 5.59%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 4.35%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 3.11%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 2.48%   |
| Nvidia MCP79 Ethernet                                             | 3         | 1.86%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.86%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 1.86%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 1.86%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.24%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.24%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.24%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.24%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.24%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.24%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.24%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1.24%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.62%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.62%   |
| Qualcomm FP3                                                      | 1         | 0.62%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.62%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.62%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.62%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.62%   |
| OnePlus (Shenzhen) Android Remote NDIS Device                     | 1         | 0.62%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.62%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.62%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.62%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.62%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller               | 1         | 0.62%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.62%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.62%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.62%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.62%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.62%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 183       | 52.44%  |
| Ethernet | 157       | 44.99%  |
| Modem    | 6         | 1.72%   |
| Unknown  | 3         | 0.86%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 120       | 53.57%  |
| Ethernet | 101       | 45.09%  |
| Modem    | 3         | 1.34%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 149       | 81.42%  |
| 1     | 33        | 18.03%  |
| 3     | 1         | 0.55%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 182       | 99.45%  |
| Yes  | 1         | 0.55%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 84        | 57.14%  |
| Realtek Semiconductor           | 13        | 8.84%   |
| Qualcomm Atheros Communications | 9         | 6.12%   |
| Lite-On Technology              | 8         | 5.44%   |
| Broadcom                        | 8         | 5.44%   |
| IMC Networks                    | 7         | 4.76%   |
| Apple                           | 7         | 4.76%   |
| Dell                            | 6         | 4.08%   |
| ASUSTek Computer                | 2         | 1.36%   |
| Alps Electric                   | 2         | 1.36%   |
| Toshiba                         | 1         | 0.68%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 48        | 32.65%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 12        | 8.16%   |
| Intel AX201 Bluetooth                                       | 9         | 6.12%   |
| Intel AX200 Bluetooth                                       | 9         | 6.12%   |
| Realtek Bluetooth Adapter                                   | 6         | 4.08%   |
| Apple Bluetooth Host Controller                             | 6         | 4.08%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 4         | 2.72%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 4         | 2.72%   |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 2.04%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 3         | 2.04%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 3         | 2.04%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 3         | 2.04%   |
| Lite-On Atheros AR3012 Bluetooth                            | 3         | 2.04%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 1.36%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 1.36%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 1.36%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 1.36%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 1.36%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.36%   |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip             | 1         | 0.68%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.68%   |
| Realtek Bluetooth 4.2 Adapter                               | 1         | 0.68%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 0.68%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 0.68%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.68%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 1         | 0.68%   |
| Lite-On Broadcom Bluetooth 4.0 USB                          | 1         | 0.68%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.68%   |
| Intel AX210 Bluetooth                                       | 1         | 0.68%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 0.68%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0          | 1         | 0.68%   |
| IMC Networks Bluetooth Module                               | 1         | 0.68%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 0.68%   |
| Dell DW375 Bluetooth Module                                 | 1         | 0.68%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 0.68%   |
| Broadcom BCM2045 Bluetooth                                  | 1         | 0.68%   |
| ASUS USB-BT500                                              | 1         | 0.68%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1         | 0.68%   |
| Apple Broadcom Built-in Bluetooth                           | 1         | 0.68%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 0.68%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 148       | 71.5%   |
| AMD                   | 32        | 15.46%  |
| Nvidia                | 19        | 9.18%   |
| Lenovo                | 2         | 0.97%   |
| RODE Microphones      | 1         | 0.48%   |
| Realtek Semiconductor | 1         | 0.48%   |
| Logitech              | 1         | 0.48%   |
| DSEA A/S              | 1         | 0.48%   |
| Cambridge Audio       | 1         | 0.48%   |
| C-Media Electronics   | 1         | 0.48%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 28        | 10.69%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 24        | 9.16%   |
| AMD Family 17h/19h HD Audio Controller                                     | 23        | 8.78%   |
| Intel Haswell-ULT HD Audio Controller                                      | 14        | 5.34%   |
| Intel 8 Series HD Audio Controller                                         | 14        | 5.34%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 4.2%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 4.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 10        | 3.82%   |
| Intel Broadwell-U Audio Controller                                         | 10        | 3.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 3.05%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 2.67%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 2.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 2.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 2.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 1.91%   |
| Nvidia MCP79 High Definition Audio                                         | 4         | 1.53%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.53%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 1.53%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1.53%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 1.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 1.15%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.15%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 1.15%   |
| AMD High Definition Audio Controller                                       | 3         | 1.15%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.76%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 0.76%   |
| Lenovo Lenovo USB-C Mini Dock                                              | 2         | 0.76%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 0.76%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.76%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 0.76%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 0.76%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.76%   |
| AMD FCH Azalia Controller                                                  | 2         | 0.76%   |
| RODE Microphones RDE NT-USB Mini                                           | 1         | 0.38%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.38%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.38%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 0.38%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 73        | 30.8%   |
| SK hynix            | 65        | 27.43%  |
| Micron Technology   | 20        | 8.44%   |
| Kingston            | 15        | 6.33%   |
| Crucial             | 15        | 6.33%   |
| Unknown             | 11        | 4.64%   |
| Elpida              | 6         | 2.53%   |
| Ramaxel Technology  | 4         | 1.69%   |
| Corsair             | 4         | 1.69%   |
| Unknown             | 4         | 1.69%   |
| Transcend           | 3         | 1.27%   |
| A-DATA Technology   | 3         | 1.27%   |
| Unknown (ABCD)      | 2         | 0.84%   |
| Goodram             | 2         | 0.84%   |
| G.Skill             | 2         | 0.84%   |
| Team                | 1         | 0.42%   |
| Smart Modular       | 1         | 0.42%   |
| Smart               | 1         | 0.42%   |
| Neo Forza           | 1         | 0.42%   |
| Nanya Technology    | 1         | 0.42%   |
| GSkill              | 1         | 0.42%   |
| Apacer              | 1         | 0.42%   |
| 09490000802C        | 1         | 0.42%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 3.69%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 2.87%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 2.46%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 6         | 2.46%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 2.46%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 2.05%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.64%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.64%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.64%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 1.64%   |
| Unknown                                                          | 4         | 1.64%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 3         | 1.23%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 3         | 1.23%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 3         | 1.23%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.23%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.23%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 1.23%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 3         | 1.23%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.82%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.82%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.82%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.82%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2400MT/s          | 2         | 0.82%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.82%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 0.82%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 2         | 0.82%   |
| Samsung RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.82%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.82%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.82%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.82%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 0.82%   |
| Micron RAM Module 8GB SODIMM DDR3 1600MT/s                       | 2         | 0.82%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 2         | 0.82%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 0.82%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.82%   |
| Unknown SODIMM 4GB SODIMM 800MT/s                                | 1         | 0.41%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.41%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.41%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.41%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 88        | 47.31%  |
| DDR4    | 78        | 41.94%  |
| DDR2    | 7         | 3.76%   |
| LPDDR4  | 4         | 2.15%   |
| LPDDR3  | 3         | 1.61%   |
| DDR     | 2         | 1.08%   |
| Unknown | 2         | 1.08%   |
| SDRAM   | 1         | 0.54%   |
| DDR5    | 1         | 0.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 178       | 95.19%  |
| Row Of Chips | 8         | 4.28%   |
| Chip         | 1         | 0.53%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 93        | 44.5%   |
| 4096  | 78        | 37.32%  |
| 2048  | 18        | 8.61%   |
| 16384 | 17        | 8.13%   |
| 32768 | 2         | 0.96%   |
| 1024  | 1         | 0.48%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 62        | 31%     |
| 2667    | 32        | 16%     |
| 2400    | 25        | 12.5%   |
| 3200    | 20        | 10%     |
| 2133    | 12        | 6%      |
| 1334    | 12        | 6%      |
| 1333    | 10        | 5%      |
| 800     | 6         | 3%      |
| 667     | 5         | 2.5%    |
| 1067    | 4         | 2%      |
| Unknown | 4         | 2%      |
| 4266    | 2         | 1%      |
| 1867    | 2         | 1%      |
| 4800    | 1         | 0.5%    |
| 1639    | 1         | 0.5%    |
| 1200    | 1         | 0.5%    |
| 975     | 1         | 0.5%    |

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
| Chicony Electronics                    | 37        | 26.06%  |
| Microdia                               | 17        | 11.97%  |
| Realtek Semiconductor                  | 15        | 10.56%  |
| Bison Electronics                      | 15        | 10.56%  |
| IMC Networks                           | 12        | 8.45%   |
| Sunplus Innovation Technology          | 10        | 7.04%   |
| Suyin                                  | 6         | 4.23%   |
| Quanta                                 | 6         | 4.23%   |
| Alcor Micro                            | 4         | 2.82%   |
| Syntek                                 | 3         | 2.11%   |
| Silicon Motion                         | 2         | 1.41%   |
| Ricoh                                  | 2         | 1.41%   |
| Luxvisions Innotech Limited            | 2         | 1.41%   |
| Lite-On Technology                     | 2         | 1.41%   |
| Apple                                  | 2         | 1.41%   |
| OmniVision Technologies                | 1         | 0.7%    |
| Logitech                               | 1         | 0.7%    |
| Lenovo                                 | 1         | 0.7%    |
| Jiangxi Shinetech Optical              | 1         | 0.7%    |
| Intel                                  | 1         | 0.7%    |
| Importek                               | 1         | 0.7%    |
| Cheng Uei Precision Industry (Foxlink) | 1         | 0.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 11        | 7.75%   |
| Bison Integrated Camera                  | 9         | 6.34%   |
| Microdia Integrated_Webcam_HD            | 7         | 4.93%   |
| Microdia Integrated Webcam               | 7         | 4.93%   |
| Sunplus Integrated_Webcam_HD             | 6         | 4.23%   |
| IMC Networks Integrated Camera           | 5         | 3.52%   |
| Realtek USB 2.0 PC Camera                | 3         | 2.11%   |
| Realtek Integrated_Webcam_HD             | 3         | 2.11%   |
| Chicony USB2.0 HD UVC WebCam             | 3         | 2.11%   |
| Chicony HD WebCam                        | 3         | 2.11%   |
| Suyin Integrated_Webcam_HD               | 2         | 1.41%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 2         | 1.41%   |
| Sunplus Laptop_Integrated_Webcam_FHD     | 2         | 1.41%   |
| Realtek Lenovo EasyCamera                | 2         | 1.41%   |
| Realtek Integrated Webcam HD             | 2         | 1.41%   |
| Realtek Front Camera                     | 2         | 1.41%   |
| Quanta VGA WebCam                        | 2         | 1.41%   |
| Quanta HP TrueVision HD Camera           | 2         | 1.41%   |
| IMC Networks Realtek PC Camera           | 2         | 1.41%   |
| IMC Networks Realtek DMFT RGB            | 2         | 1.41%   |
| Chicony Realtek DMFT RGB                 | 2         | 1.41%   |
| Chicony Integrated Camera (1280x720@30)  | 2         | 1.41%   |
| Bison ThinkPad P50 Integrated Camera     | 2         | 1.41%   |
| Bison ThinkPad Integrated Camera         | 2         | 1.41%   |
| Apple FaceTime HD Camera                 | 2         | 1.41%   |
| Alcor Micro USB 2.0 Camera               | 2         | 1.41%   |
| Syntek USB 2.0 UVC 1.3M WebCam           | 1         | 0.7%    |
| Syntek Lenovo EasyCamera                 | 1         | 0.7%    |
| Syntek Integrated Camera                 | 1         | 0.7%    |
| Suyin RGBIR Camera                       | 1         | 0.7%    |
| Suyin HD WebCam                          | 1         | 0.7%    |
| Sunplus SPCA2085 PC Camera               | 1         | 0.7%    |
| Sunplus MTD camera                       | 1         | 0.7%    |
| Silicon Motion WebCam SC-13HDL11939N     | 1         | 0.7%    |
| Silicon Motion Realtek USB 2.0 PC Camera | 1         | 0.7%    |
| Ricoh USB2.0 Camera                      | 1         | 0.7%    |
| Ricoh HD Webcam                          | 1         | 0.7%    |
| Realtek USB Camera                       | 1         | 0.7%    |
| Realtek USB 2.0 Webcam                   | 1         | 0.7%    |
| Realtek Dell EasyCamera                  | 1         | 0.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 37.93%  |
| Synaptics                  | 5         | 17.24%  |
| Upek                       | 3         | 10.34%  |
| STMicroelectronics         | 2         | 6.9%    |
| Shenzhen Goodix Technology | 2         | 6.9%    |
| Next Biometrics            | 1         | 3.45%   |
| LighTuning Technology      | 1         | 3.45%   |
| FocalTech Systems          | 1         | 3.45%   |
| Elan Microelectronics      | 1         | 3.45%   |
| Broadcom                   | 1         | 3.45%   |
| AuthenTec                  | 1         | 3.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 5         | 17.24%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 2         | 6.9%    |
| Validity Sensors Synaptics WBDI                                              | 2         | 6.9%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 6.9%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 2         | 6.9%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 2         | 6.9%    |
| STMicroelectronics Fingerprint Reader                                        | 2         | 6.9%    |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 6.9%    |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 3.45%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 1         | 3.45%   |
| Upek TCS5B Fingerprint sensor                                                | 1         | 3.45%   |
| Synaptics WBDI                                                               | 1         | 3.45%   |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 3.45%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 1         | 3.45%   |
| FocalTech Systems Fingerprint Reader                                         | 1         | 3.45%   |
| Elan Fingerprint Sensor                                                      | 1         | 3.45%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.45%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 3.45%   |

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
| 2     | 64        | 33.33%  |
| 1     | 48        | 25%     |
| 3     | 38        | 19.79%  |
| 4     | 23        | 11.98%  |
| 0     | 14        | 7.29%   |
| 5     | 5         | 2.6%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 135       | 36.19%  |
| Bluetooth                | 95        | 25.47%  |
| Net/wireless             | 46        | 12.33%  |
| Card reader              | 40        | 10.72%  |
| Fingerprint reader       | 30        | 8.04%   |
| Firewire controller      | 13        | 3.49%   |
| Network                  | 7         | 1.88%   |
| Storage                  | 5         | 1.34%   |
| Sound                    | 1         | 0.27%   |
| Net/ethernet             | 1         | 0.27%   |

