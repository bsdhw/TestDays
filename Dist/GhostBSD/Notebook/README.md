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

Total: 293

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Acer          | TravelMate B118-M           | [68d9d26fe5](https://bsd-hardware.info/?probe=68d9d26fe5) | May 09, 2024 |
| Alienware     | Area-51m A00                | [53d5d4eb1e](https://bsd-hardware.info/?probe=53d5d4eb1e) | May 07, 2024 |
| Unknown       | X133                        | [524b7e6d8e](https://bsd-hardware.info/?probe=524b7e6d8e) | May 07, 2024 |
| Dell          | XPS 13 9360                 | [c9ad91fc61](https://bsd-hardware.info/?probe=c9ad91fc61) | May 07, 2024 |
| Lenovo        | ThinkPad X240 20AMS3FY00    | [1dc74d60e6](https://bsd-hardware.info/?probe=1dc74d60e6) | May 06, 2024 |
| Dell          | Latitude 7390               | [b9b511f4d6](https://bsd-hardware.info/?probe=b9b511f4d6) | May 04, 2024 |
| MSI           | GE75 Raider 10SFS           | [cda74e2f91](https://bsd-hardware.info/?probe=cda74e2f91) | May 02, 2024 |
| ASUSTek       | X202E                       | [0ed385a36d](https://bsd-hardware.info/?probe=0ed385a36d) | May 02, 2024 |
| HP            | 255 G8 Notebook PC          | [4878c18c8a](https://bsd-hardware.info/?probe=4878c18c8a) | May 01, 2024 |
| Dell          | XPS 13 9360                 | [26185f189e](https://bsd-hardware.info/?probe=26185f189e) | Apr 30, 2024 |
| HP            | EliteBook 2560p             | [bb6303ed5b](https://bsd-hardware.info/?probe=bb6303ed5b) | Apr 29, 2024 |
| Lenovo        | ThinkPad X220 429135G       | [b681d0b406](https://bsd-hardware.info/?probe=b681d0b406) | Apr 23, 2024 |
| F-Plus Mob... | FLAPTOP r                   | [150e135ba6](https://bsd-hardware.info/?probe=150e135ba6) | Apr 18, 2024 |
| Dell          | Latitude 7490               | [38f6023f20](https://bsd-hardware.info/?probe=38f6023f20) | Apr 14, 2024 |
| Dell          | Vostro 3350                 | [abe739e6c2](https://bsd-hardware.info/?probe=abe739e6c2) | Apr 13, 2024 |
| HP            | ProBook 645 G3              | [ea10ac1f83](https://bsd-hardware.info/?probe=ea10ac1f83) | Apr 12, 2024 |
| Apple         | MacBookAir7,2               | [a26013b913](https://bsd-hardware.info/?probe=a26013b913) | Apr 05, 2024 |
| Dell          | Latitude E5540              | [108e2acb98](https://bsd-hardware.info/?probe=108e2acb98) | Apr 01, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [0ae72ec0ff](https://bsd-hardware.info/?probe=0ae72ec0ff) | Mar 31, 2024 |
| HP            | OMEN Laptop 15-ek0xxx       | [f4dde6ddf5](https://bsd-hardware.info/?probe=f4dde6ddf5) | Mar 22, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [db1d3cd098](https://bsd-hardware.info/?probe=db1d3cd098) | Mar 19, 2024 |
| Google        | Cave                        | [d9df48c781](https://bsd-hardware.info/?probe=d9df48c781) | Mar 16, 2024 |
| Dell          | XPS 13 9305                 | [7cc4588e07](https://bsd-hardware.info/?probe=7cc4588e07) | Mar 07, 2024 |
| HP            | Notebook                    | [15839305ee](https://bsd-hardware.info/?probe=15839305ee) | Mar 01, 2024 |
| Dell          | Inspiron 5559               | [ac72a9a34a](https://bsd-hardware.info/?probe=ac72a9a34a) | Feb 23, 2024 |
| Dell          | Latitude E6540              | [92ba9b26e1](https://bsd-hardware.info/?probe=92ba9b26e1) | Feb 21, 2024 |
| Dell          | Latitude 7490               | [32828d5d84](https://bsd-hardware.info/?probe=32828d5d84) | Feb 10, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [0e644c21cc](https://bsd-hardware.info/?probe=0e644c21cc) | Feb 02, 2024 |
| TUXEDO        | Aura 15 Gen1                | [4768e0001d](https://bsd-hardware.info/?probe=4768e0001d) | Feb 01, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [e747b9066e](https://bsd-hardware.info/?probe=e747b9066e) | Jan 29, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [7e24e6c0f2](https://bsd-hardware.info/?probe=7e24e6c0f2) | Jan 29, 2024 |
| ASUSTek       | X555LAB                     | [c396fcc8d9](https://bsd-hardware.info/?probe=c396fcc8d9) | Jan 22, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [d08f6339ae](https://bsd-hardware.info/?probe=d08f6339ae) | Jan 12, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [2ab7b9d6b2](https://bsd-hardware.info/?probe=2ab7b9d6b2) | Jan 02, 2024 |
| HP            | EliteBook 2540p             | [c915c03729](https://bsd-hardware.info/?probe=c915c03729) | Dec 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S8LW00    | [b6c3c05155](https://bsd-hardware.info/?probe=b6c3c05155) | Dec 25, 2023 |
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
| GhostBSD 20.04.02 | 58        | 25%     |
| GhostBSD 21.08.27 | 29        | 12.5%   |
| GhostBSD 24.01.1  | 23        | 9.91%   |
| GhostBSD 23.10.1  | 21        | 9.05%   |
| GhostBSD 22.01.12 | 13        | 5.6%    |
| GhostBSD 23.06.01 | 11        | 4.74%   |
| GhostBSD 22.06.18 | 11        | 4.74%   |
| GhostBSD 23.02.02 | 6         | 2.59%   |
| GhostBSD 23.07.13 | 4         | 1.72%   |
| GhostBSD 23.07.29 | 3         | 1.29%   |
| GhostBSD 23.06.05 | 3         | 1.29%   |
| GhostBSD 22.06.26 | 3         | 1.29%   |
| GhostBSD 23.09.16 | 2         | 0.86%   |
| GhostBSD 23.09.06 | 2         | 0.86%   |
| GhostBSD 23.07.20 | 2         | 0.86%   |
| GhostBSD 23.05.22 | 2         | 0.86%   |
| GhostBSD 23.04.23 | 2         | 0.86%   |
| GhostBSD 23.03.17 | 2         | 0.86%   |
| GhostBSD 22.11.22 | 2         | 0.86%   |
| GhostBSD 22.11.02 | 2         | 0.86%   |
| GhostBSD 22.08.23 | 2         | 0.86%   |
| GhostBSD 22.08.06 | 2         | 0.86%   |
| GhostBSD 22.07.16 | 2         | 0.86%   |
| GhostBSD 23.10.09 | 1         | 0.43%   |
| GhostBSD 23.09.29 | 1         | 0.43%   |
| GhostBSD 23.07.04 | 1         | 0.43%   |
| GhostBSD 23.06.22 | 1         | 0.43%   |
| GhostBSD 23.05.18 | 1         | 0.43%   |
| GhostBSD 23.04.02 | 1         | 0.43%   |
| GhostBSD 23.01.13 | 1         | 0.43%   |
| GhostBSD 22.10.30 | 1         | 0.43%   |
| GhostBSD 22.09.16 | 1         | 0.43%   |
| GhostBSD 22.08.27 | 1         | 0.43%   |
| GhostBSD 22.07.31 | 1         | 0.43%   |
| GhostBSD 22.07.28 | 1         | 0.43%   |
| GhostBSD 22.07.13 | 1         | 0.43%   |
| GhostBSD 22.07.10 | 1         | 0.43%   |
| GhostBSD 22.06.20 | 1         | 0.43%   |
| GhostBSD 22.06.07 | 1         | 0.43%   |
| GhostBSD 22.05.13 | 1         | 0.43%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| GhostBSD | 212       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 212       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| MATE         | 170       | 79.07%  |
| XFCE         | 31        | 14.42%  |
| KDE5         | 8         | 3.72%   |
| Cinnamon     | 2         | 0.93%   |
| helloDesktop | 1         | 0.47%   |
| GNOME        | 1         | 0.47%   |
| dwm          | 1         | 0.47%   |
| Console      | 1         | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 210       | 99.06%  |
| Wayland | 1         | 0.47%   |
| Console | 1         | 0.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 209       | 98.58%  |
| SDDM    | 2         | 0.94%   |
| Console | 1         | 0.47%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 91        | 40.81%  |
| C       | 75        | 33.63%  |
| Unknown | 16        | 7.17%   |
| de_DE   | 10        | 4.48%   |
| es_ES   | 7         | 3.14%   |
| ru_RU   | 4         | 1.79%   |
| pt_BR   | 4         | 1.79%   |
| en_GB   | 4         | 1.79%   |
| pl_PL   | 3         | 1.35%   |
| it_IT   | 3         | 1.35%   |
| zh_CN   | 1         | 0.45%   |
| sv_SE   | 1         | 0.45%   |
| sk_SK   | 1         | 0.45%   |
| fr_FR   | 1         | 0.45%   |
| en_NZ   | 1         | 0.45%   |
| el_GR   | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 170       | 80.19%  |
| BIOS | 42        | 19.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 203       | 93.98%  |
| Ufs  | 13        | 6.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 209       | 98.58%  |
| MBR  | 3         | 1.42%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 59        | 27.83%  |
| Dell                | 50        | 23.58%  |
| Hewlett-Packard     | 23        | 10.85%  |
| ASUSTek Computer    | 17        | 8.02%   |
| Acer                | 13        | 6.13%   |
| MSI                 | 7         | 3.3%    |
| Apple               | 7         | 3.3%    |
| Sony                | 4         | 1.89%   |
| Notebook            | 4         | 1.89%   |
| Fujitsu             | 4         | 1.89%   |
| Toshiba             | 3         | 1.42%   |
| System76            | 3         | 1.42%   |
| Samsung Electronics | 3         | 1.42%   |
| TUXEDO              | 2         | 0.94%   |
| Star Labs           | 2         | 0.94%   |
| Alienware           | 2         | 0.94%   |
| Unknown             | 2         | 0.94%   |
| Panasonic           | 1         | 0.47%   |
| MouseComputer       | 1         | 0.47%   |
| Jumper              | 1         | 0.47%   |
| HUAWEI              | 1         | 0.47%   |
| GPU Company         | 1         | 0.47%   |
| Google              | 1         | 0.47%   |
| F-Plus Mobile       | 1         | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Latitude 7490                       | 3         | 1.42%   |
| Dell Inspiron 3542                       | 3         | 1.42%   |
| Unknown                                  | 3         | 1.42%   |
| MSI Modern 14 A10M                       | 2         | 0.94%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS       | 2         | 0.94%   |
| Lenovo ThinkPad T430s 2352CTO            | 2         | 0.94%   |
| HP Notebook                              | 2         | 0.94%   |
| Dell XPS 13 9360                         | 2         | 0.94%   |
| Dell XPS 13 7390                         | 2         | 0.94%   |
| Dell Latitude E6540                      | 2         | 0.94%   |
| Dell Latitude E6420                      | 2         | 0.94%   |
| Dell Latitude E5440                      | 2         | 0.94%   |
| ASUS ZenBook UX325UA_UM325UA             | 2         | 0.94%   |
| ASUS X202E                               | 2         | 0.94%   |
| TUXEDO InfinityBook13V3                  | 1         | 0.47%   |
| TUXEDO Aura 15 Gen1                      | 1         | 0.47%   |
| Toshiba Satellite L655                   | 1         | 0.47%   |
| Toshiba Satellite C855-1U4               | 1         | 0.47%   |
| Toshiba Satellite C855                   | 1         | 0.47%   |
| System76 Lemur Pro                       | 1         | 0.47%   |
| System76 Kudu                            | 1         | 0.47%   |
| System76 Gazelle                         | 1         | 0.47%   |
| Star Labs StarBook                       | 1         | 0.47%   |
| Star Labs LabTop                         | 1         | 0.47%   |
| Sony VPCCB17FG                           | 1         | 0.47%   |
| Sony VGN-SZ3VWP_X                        | 1         | 0.47%   |
| Sony SVP1322M1EBI                        | 1         | 0.47%   |
| Sony SVP13225SCBI                        | 1         | 0.47%   |
| Samsung Q210                             | 1         | 0.47%   |
| Samsung 550P5C/550P7C                    | 1         | 0.47%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV | 1         | 0.47%   |
| Panasonic CF-19AHNC8FN                   | 1         | 0.47%   |
| Notebook N8xEJEK                         | 1         | 0.47%   |
| Notebook N85_N87,HJ,HJ1,HK1              | 1         | 0.47%   |
| Notebook N7x0WU                          | 1         | 0.47%   |
| Notebook N13xWU                          | 1         | 0.47%   |
| MSI Sword 17 A11UD                       | 1         | 0.47%   |
| MSI GF63 Thin 10SCSR                     | 1         | 0.47%   |
| MSI GE75 Raider 10SFS                    | 1         | 0.47%   |
| MSI GE62 6QC                             | 1         | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 44        | 20.75%  |
| Dell Latitude           | 24        | 11.32%  |
| Dell Inspiron           | 15        | 7.08%   |
| Acer Aspire             | 8         | 3.77%   |
| Lenovo IdeaPad          | 6         | 2.83%   |
| Dell XPS                | 6         | 2.83%   |
| HP Laptop               | 5         | 2.36%   |
| HP EliteBook            | 5         | 2.36%   |
| Toshiba Satellite       | 3         | 1.42%   |
| Lenovo Yoga             | 3         | 1.42%   |
| Lenovo Legion           | 3         | 1.42%   |
| HP OMEN                 | 3         | 1.42%   |
| Dell Precision          | 3         | 1.42%   |
| ASUS VivoBook           | 3         | 1.42%   |
| Acer TravelMate         | 3         | 1.42%   |
| Unknown                 | 3         | 1.42%   |
| MSI Modern              | 2         | 0.94%   |
| HP ProBook              | 2         | 0.94%   |
| HP Notebook             | 2         | 0.94%   |
| HP 255                  | 2         | 0.94%   |
| Fujitsu LIFEBOOK        | 2         | 0.94%   |
| ASUS ZenBook            | 2         | 0.94%   |
| ASUS X202E              | 2         | 0.94%   |
| Apple MacBookPro9       | 2         | 0.94%   |
| TUXEDO InfinityBook13V3 | 1         | 0.47%   |
| TUXEDO Aura             | 1         | 0.47%   |
| System76 Lemur          | 1         | 0.47%   |
| System76 Kudu           | 1         | 0.47%   |
| System76 Gazelle        | 1         | 0.47%   |
| Star Labs StarBook      | 1         | 0.47%   |
| Star Labs LabTop        | 1         | 0.47%   |
| Sony VPCCB17FG          | 1         | 0.47%   |
| Sony VGN-SZ3VWP         | 1         | 0.47%   |
| Sony SVP1322M1EBI       | 1         | 0.47%   |
| Sony SVP13225SCBI       | 1         | 0.47%   |
| Samsung Q210            | 1         | 0.47%   |
| Samsung 550P5C          | 1         | 0.47%   |
| Samsung 3570R           | 1         | 0.47%   |
| Panasonic CF-19AHNC8FN  | 1         | 0.47%   |
| Notebook N8xEJEK        | 1         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 29        | 13.68%  |
| 2021 | 20        | 9.43%   |
| 2018 | 19        | 8.96%   |
| 2013 | 18        | 8.49%   |
| 2022 | 15        | 7.08%   |
| 2015 | 15        | 7.08%   |
| 2014 | 15        | 7.08%   |
| 2016 | 13        | 6.13%   |
| 2011 | 13        | 6.13%   |
| 2012 | 11        | 5.19%   |
| 2019 | 10        | 4.72%   |
| 2017 | 9         | 4.25%   |
| 2023 | 8         | 3.77%   |
| 2009 | 7         | 3.3%    |
| 2008 | 5         | 2.36%   |
| 2010 | 4         | 1.89%   |
| 2007 | 1         | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 212       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 209       | 98.58%  |
| Yes  | 3         | 1.42%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 98        | 45.79%  |
| 16.01-24.0  | 67        | 31.31%  |
| 4.01-8.0    | 34        | 15.89%  |
| 32.01-64.0  | 6         | 2.8%    |
| 24.01-32.0  | 5         | 2.34%   |
| 64.01-256.0 | 3         | 1.4%    |
| 2.01-3.0    | 1         | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 90        | 41.47%  |
| 0.51-1.0   | 87        | 40.09%  |
| 1.01-2.0   | 20        | 9.22%   |
| 2.01-3.0   | 17        | 7.83%   |
| 4.01-8.0   | 2         | 0.92%   |
| 24.01-32.0 | 1         | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 156       | 72.22%  |
| 2      | 37        | 17.13%  |
| 0      | 20        | 9.26%   |
| 3      | 3         | 1.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 138       | 64.79%  |
| Yes       | 75        | 35.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 177       | 83.49%  |
| No        | 35        | 16.51%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 210       | 99.06%  |
| No        | 2         | 0.94%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 169       | 79.72%  |
| No        | 43        | 20.28%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 48        | 22.54%  |
| Germany      | 25        | 11.74%  |
| UK           | 10        | 4.69%   |
| Spain        | 10        | 4.69%   |
| France       | 10        | 4.69%   |
| Russia       | 9         | 4.23%   |
| Poland       | 8         | 3.76%   |
| Italy        | 7         | 3.29%   |
| Canada       | 7         | 3.29%   |
| Switzerland  | 5         | 2.35%   |
| India        | 5         | 2.35%   |
| Taiwan       | 4         | 1.88%   |
| Japan        | 4         | 1.88%   |
| Indonesia    | 4         | 1.88%   |
| Brazil       | 4         | 1.88%   |
| Sweden       | 3         | 1.41%   |
| New Zealand  | 3         | 1.41%   |
| Bulgaria     | 3         | 1.41%   |
| South Africa | 2         | 0.94%   |
| Slovenia     | 2         | 0.94%   |
| Slovakia     | 2         | 0.94%   |
| Portugal     | 2         | 0.94%   |
| Philippines  | 2         | 0.94%   |
| Norway       | 2         | 0.94%   |
| Netherlands  | 2         | 0.94%   |
| Mauritius    | 2         | 0.94%   |
| Hong Kong    | 2         | 0.94%   |
| Finland      | 2         | 0.94%   |
| China        | 2         | 0.94%   |
| Belgium      | 2         | 0.94%   |
| Argentina    | 2         | 0.94%   |
| Ukraine      | 1         | 0.47%   |
| Uganda       | 1         | 0.47%   |
| Turkey       | 1         | 0.47%   |
| Serbia       | 1         | 0.47%   |
| Paraguay     | 1         | 0.47%   |
| Namibia      | 1         | 0.47%   |
| Malaysia     | 1         | 0.47%   |
| Lithuania    | 1         | 0.47%   |
| Kazakhstan   | 1         | 0.47%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Bedburg            | 6         | 2.69%   |
| Zurich             | 4         | 1.79%   |
| Indian Trail       | 4         | 1.79%   |
| Saratov            | 3         | 1.35%   |
| Rome               | 3         | 1.35%   |
| Madrid             | 3         | 1.35%   |
| Jakarta            | 3         | 1.35%   |
| Franconville       | 3         | 1.35%   |
| Chrusty            | 3         | 1.35%   |
| Bonn               | 3         | 1.35%   |
| Yokohama           | 2         | 0.9%    |
| Winnipeg           | 2         | 0.9%    |
| Whittier           | 2         | 0.9%    |
| Wezeren            | 2         | 0.9%    |
| Tomball            | 2         | 0.9%    |
| Taipei             | 2         | 0.9%    |
| Taichung           | 2         | 0.9%    |
| Stiring-Wendel     | 2         | 0.9%    |
| Sofia              | 2         | 0.9%    |
| Skiatook           | 2         | 0.9%    |
| Roslindale         | 2         | 0.9%    |
| Paris              | 2         | 0.9%    |
| Oslo               | 2         | 0.9%    |
| Nuremberg          | 2         | 0.9%    |
| Milan              | 2         | 0.9%    |
| London             | 2         | 0.9%    |
| Lebanon            | 2         | 0.9%    |
| Jarosław          | 2         | 0.9%    |
| Giessen            | 2         | 0.9%    |
| Clemmons           | 2         | 0.9%    |
| Chiyoda-ku         | 2         | 0.9%    |
| Celje              | 2         | 0.9%    |
| Asnieres-sur-Seine | 2         | 0.9%    |
| Zaragoza           | 1         | 0.45%   |
| Zagreb             | 1         | 0.45%   |
| Yaroslavl          | 1         | 0.45%   |
| Wraysbury          | 1         | 0.45%   |
| Witbank            | 1         | 0.45%   |
| Windhoek           | 1         | 0.45%   |
| Wenatchee          | 1         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 55        | 68     | 23.11%  |
| WDC                 | 30        | 32     | 12.61%  |
| Kingston            | 22        | 22     | 9.24%   |
| Seagate             | 18        | 21     | 7.56%   |
| Toshiba             | 14        | 18     | 5.88%   |
| SK hynix            | 14        | 18     | 5.88%   |
| Crucial             | 13        | 17     | 5.46%   |
| Intel               | 10        | 10     | 4.2%    |
| SanDisk             | 9         | 9      | 3.78%   |
| Hitachi             | 5         | 5      | 2.1%    |
| Micron Technology   | 4         | 4      | 1.68%   |
| HGST                | 4         | 4      | 1.68%   |
| A-DATA Technology   | 4         | 4      | 1.68%   |
| Phison              | 3         | 4      | 1.26%   |
| Apple               | 3         | 3      | 1.26%   |
| Transcend           | 2         | 2      | 0.84%   |
| Star Drive          | 2         | 2      | 0.84%   |
| PNY                 | 2         | 2      | 0.84%   |
| Patriot             | 2         | 2      | 0.84%   |
| KingSpec            | 2         | 2      | 0.84%   |
| GOODRAM             | 2         | 2      | 0.84%   |
| Fujitsu             | 2         | 2      | 0.84%   |
| China               | 2         | 2      | 0.84%   |
| XUM                 | 1         | 1      | 0.42%   |
| Team                | 1         | 1      | 0.42%   |
| SSSTC               | 1         | 1      | 0.42%   |
| SPCC                | 1         | 1      | 0.42%   |
| Silicon Motion      | 1         | 1      | 0.42%   |
| ShiJi               | 1         | 1      | 0.42%   |
| Plextor             | 1         | 1      | 0.42%   |
| Netac               | 1         | 1      | 0.42%   |
| LITEONIT            | 1         | 1      | 0.42%   |
| Intenso             | 1         | 1      | 0.42%   |
| Hewlett-Packard     | 1         | 1      | 0.42%   |
| Gigabyte Technology | 1         | 1      | 0.42%   |
| Fanxiang            | 1         | 1      | 0.42%   |
| Dell                | 1         | 2      | 0.42%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB            | 5         | 2.06%   |
| WDC WD10JPVX-22JC3T0 1TB               | 3         | 1.23%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB | 3         | 1.23%   |
| Seagate ST1000LM035-1RK172 1TB         | 3         | 1.23%   |
| Samsung SSD 860 EVO 500GB              | 3         | 1.23%   |
| Samsung SSD 850 EVO 250GB              | 3         | 1.23%   |
| Kingston SA400S37120G 120GB            | 3         | 1.23%   |
| WDC WDS500G2B0A-00SM50 500GB           | 2         | 0.82%   |
| Toshiba KXG50ZNV512G NVMe 512GB        | 2         | 0.82%   |
| Toshiba KBG40ZNT512G MEMORY 512GB      | 2         | 0.82%   |
| Star Drive PCIe SSD 960GB              | 2         | 0.82%   |
| SK hynix SC311 SATA 512GB              | 2         | 0.82%   |
| SK hynix HFM512GD3JX013N 512GB         | 2         | 0.82%   |
| Seagate ST500LT012-9WS142 500GB        | 2         | 0.82%   |
| Seagate ST1000LM049-2GH172 1TB         | 2         | 0.82%   |
| Samsung SSD 870 EVO 500GB              | 2         | 0.82%   |
| Samsung SSD 860 QVO 1TB                | 2         | 0.82%   |
| Samsung SSD 860 PRO 512GB              | 2         | 0.82%   |
| Samsung SSD 860 EVO 1TB                | 2         | 0.82%   |
| Samsung PM981 NVMe 256GB               | 2         | 0.82%   |
| Samsung MZNTE128HMGR-000SO 128GB       | 2         | 0.82%   |
| Kingston SV300S37A240G 240GB           | 2         | 0.82%   |
| Kingston SA400S37960G 960GB            | 2         | 0.82%   |
| Kingston RBUSNS8154P3512GJ 512GB       | 2         | 0.82%   |
| KingSpec Q-720 720GB                   | 2         | 0.82%   |
| Intel SSDPEKNW512G8 512GB              | 2         | 0.82%   |
| Intel SSDPEKKF256G8L 256GB             | 2         | 0.82%   |
| Hitachi HTS541612J9SA00 120GB          | 2         | 0.82%   |
| HGST HTS541010A9E680 1TB               | 2         | 0.82%   |
| Crucial CT1000MX500SSD1 1TB            | 2         | 0.82%   |
| XUM HX256GSSDSATA3 256GB               | 1         | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB           | 1         | 0.41%   |
| WDC WDS120G2G0A-00JH30 120GB           | 1         | 0.41%   |
| WDC WDS100T3X0C-00SJG0 1TB             | 1         | 0.41%   |
| WDC WDS100T2B0B-00YS70 1TB             | 1         | 0.41%   |
| WDC WDS100T1B0A-00H9H0 1TB             | 1         | 0.41%   |
| WDC WD7500BPVT-80HXZT3 752GB           | 1         | 0.41%   |
| WDC WD7500BPKX-80HPJT0 752GB           | 1         | 0.41%   |
| WDC WD7500BPKX-00HPJT0 752GB           | 1         | 0.41%   |
| WDC WD6400BEVT-22A0RT0 640GB           | 1         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 18        | 19     | 32.73%  |
| Seagate             | 18        | 21     | 32.73%  |
| Toshiba             | 5         | 5      | 9.09%   |
| Hitachi             | 5         | 5      | 9.09%   |
| HGST                | 4         | 4      | 7.27%   |
| Samsung Electronics | 2         | 2      | 3.64%   |
| Fujitsu             | 2         | 2      | 3.64%   |
| Apple               | 1         | 1      | 1.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 42     | 27.97%  |
| Kingston            | 18        | 18     | 15.25%  |
| Crucial             | 11        | 14     | 9.32%   |
| SanDisk             | 9         | 9      | 7.63%   |
| WDC                 | 6         | 6      | 5.08%   |
| SK hynix            | 6         | 6      | 5.08%   |
| Intel               | 4         | 4      | 3.39%   |
| Toshiba             | 3         | 5      | 2.54%   |
| Transcend           | 2         | 2      | 1.69%   |
| PNY                 | 2         | 2      | 1.69%   |
| Patriot             | 2         | 2      | 1.69%   |
| Micron Technology   | 2         | 2      | 1.69%   |
| KingSpec            | 2         | 2      | 1.69%   |
| GOODRAM             | 2         | 2      | 1.69%   |
| China               | 2         | 2      | 1.69%   |
| Apple               | 2         | 2      | 1.69%   |
| A-DATA Technology   | 2         | 2      | 1.69%   |
| XUM                 | 1         | 1      | 0.85%   |
| Team                | 1         | 1      | 0.85%   |
| SPCC                | 1         | 1      | 0.85%   |
| ShiJi               | 1         | 1      | 0.85%   |
| Plextor             | 1         | 1      | 0.85%   |
| Phison              | 1         | 1      | 0.85%   |
| Netac               | 1         | 1      | 0.85%   |
| LITEONIT            | 1         | 1      | 0.85%   |
| Fanxiang            | 1         | 1      | 0.85%   |
| Dell                | 1         | 2      | 0.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 109       | 133    | 49.55%  |
| NVMe | 59        | 78     | 26.82%  |
| HDD  | 52        | 59     | 23.64%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 150       | 192    | 71.77%  |
| NVMe | 59        | 78     | 28.23%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 105       | 121    | 64.81%  |
| 0.51-1.0   | 49        | 62     | 30.25%  |
| 1.01-2.0   | 8         | 9      | 4.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 68        | 30.36%  |
| 101-250    | 54        | 24.11%  |
| 251-500    | 38        | 16.96%  |
| 501-1000   | 22        | 9.82%   |
| 51-100     | 19        | 8.48%   |
| Unknown    | 12        | 5.36%   |
| 21-50      | 8         | 3.57%   |
| 1001-2000  | 3         | 1.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 191       | 86.82%  |
| 21-50   | 13        | 5.91%   |
| Unknown | 12        | 5.45%   |
| 101-250 | 2         | 0.91%   |
| 51-100  | 2         | 0.91%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB                 | 2         | 3      | 6.06%   |
| Kingston SA400S37240G 240GB                     | 2         | 2      | 6.06%   |
| Hitachi HTS541612J9SA00 120GB                   | 2         | 2      | 6.06%   |
| HGST HTS541010A9E680 1TB                        | 2         | 2      | 6.06%   |
| WDC WD6400BEVT-22A0RT0 640GB                    | 1         | 1      | 3.03%   |
| WDC WD3200LPVX-75V0TT0 320GB                    | 1         | 1      | 3.03%   |
| WDC WD10JPVX-60JC3T0 1TB                        | 1         | 1      | 3.03%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB            | 1         | 1      | 3.03%   |
| Toshiba MQ01ACF032 320GB                        | 1         | 1      | 3.03%   |
| Toshiba MK1252GSX 120GB                         | 1         | 1      | 3.03%   |
| SK hynix HFS256G39MND-2300A 256GB               | 1         | 1      | 3.03%   |
| ShiJi SSD 512GB                                 | 1         | 1      | 3.03%   |
| Seagate ST9250827AS 250GB                       | 1         | 1      | 3.03%   |
| Seagate ST500LM021-1KJ152 500GB                 | 1         | 1      | 3.03%   |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 3.03%   |
| Seagate ST1000LM035-1RK172 1TB                  | 1         | 2      | 3.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 1         | 1      | 3.03%   |
| Samsung Electronics SSD 980 500GB               | 1         | 1      | 3.03%   |
| Samsung Electronics SSD 870 EVO 500GB           | 1         | 1      | 3.03%   |
| Samsung Electronics SSD 840 PRO Series 256GB    | 1         | 1      | 3.03%   |
| Samsung Electronics MZNTE128HMGR-000SO 128GB    | 1         | 1      | 3.03%   |
| Samsung Electronics HM320JI 320GB               | 1         | 1      | 3.03%   |
| Patriot Inferno 60GB SSD                        | 1         | 1      | 3.03%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB | 1         | 1      | 3.03%   |
| Intel SSDSC2BF180A5L 180GB                      | 1         | 1      | 3.03%   |
| Intel SSDSC2BF180A4L 180GB                      | 1         | 1      | 3.03%   |
| Hitachi HTS543225L9A300 250GB                   | 1         | 1      | 3.03%   |
| HGST HTS721010A9E630 1TB                        | 1         | 1      | 3.03%   |
| Fanxiang S101 512GB                             | 1         | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 9      | 21.21%  |
| Samsung Electronics | 5         | 5      | 15.15%  |
| WDC                 | 3         | 3      | 9.09%   |
| Toshiba             | 3         | 3      | 9.09%   |
| Hitachi             | 3         | 3      | 9.09%   |
| HGST                | 3         | 3      | 9.09%   |
| Kingston            | 2         | 2      | 6.06%   |
| Intel               | 2         | 2      | 6.06%   |
| SK hynix            | 1         | 1      | 3.03%   |
| ShiJi               | 1         | 1      | 3.03%   |
| Patriot             | 1         | 1      | 3.03%   |
| Micron Technology   | 1         | 1      | 3.03%   |
| Fanxiang            | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 9      | 36.84%  |
| WDC                 | 3         | 3      | 15.79%  |
| Hitachi             | 3         | 3      | 15.79%  |
| HGST                | 3         | 3      | 15.79%  |
| Toshiba             | 2         | 2      | 10.53%  |
| Samsung Electronics | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 21     | 56.25%  |
| SSD  | 13        | 13     | 40.63%  |
| NVMe | 1         | 1      | 3.13%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Intel SSDSCKKF512G8 SATA 512GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| Intel  | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 173       | 233    | 83.98%  |
| Malfunc  | 31        | 35     | 15.05%  |
| Detected | 1         | 1      | 0.49%   |
| Failed   | 1         | 1      | 0.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 156       | 63.67%  |
| Samsung Electronics            | 23        | 9.39%   |
| AMD                            | 18        | 7.35%   |
| SanDisk                        | 9         | 3.67%   |
| SK hynix                       | 8         | 3.27%   |
| Phison Electronics             | 5         | 2.04%   |
| Nvidia                         | 5         | 2.04%   |
| Kingston Technology Company    | 5         | 2.04%   |
| Toshiba                        | 3         | 1.22%   |
| Silicon Motion                 | 2         | 0.82%   |
| Micron/Crucial Technology      | 2         | 0.82%   |
| Micron Technology              | 2         | 0.82%   |
| ADATA Technology               | 2         | 0.82%   |
| Solid State Storage Technology | 1         | 0.41%   |
| Shenzhen Longsys Electronics   | 1         | 0.41%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.41%   |
| KIOXIA                         | 1         | 0.41%   |
| Biwin Storage Technology       | 1         | 0.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 24        | 9.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 22        | 8.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 17        | 6.77%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 16        | 6.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 14        | 5.58%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 13        | 5.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 12        | 4.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 10        | 3.98%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 7         | 2.79%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 6         | 2.39%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 5         | 1.99%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 1.99%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 1.99%   |
| Nvidia MCP79 AHCI Controller                                                     | 4         | 1.59%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 3         | 1.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 1.2%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 1.2%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 2         | 0.8%    |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 2         | 0.8%    |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 0.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.8%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 2         | 0.8%    |
| Phison E12 NVMe Controller                                                       | 2         | 0.8%    |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                               | 2         | 0.8%    |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                   | 2         | 0.8%    |
| Intel Tiger Lake SATA AHCI Controller                                            | 2         | 0.8%    |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 2         | 0.8%    |
| Intel SSD 660P Series                                                            | 2         | 0.8%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.8%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 0.8%    |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 0.8%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.8%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 0.8%    |
| Toshiba XG5 NVMe SSD Controller                                                  | 1         | 0.4%    |
| Toshiba XG4 NVMe SSD Controller                                                  | 1         | 0.4%    |
| Toshiba BG3 x2 NVMe SSD Controller (DRAM-less)                                   | 1         | 0.4%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 154       | 63.64%  |
| NVMe | 63        | 26.03%  |
| RAID | 18        | 7.44%   |
| IDE  | 7         | 2.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 175       | 82.55%  |
| AMD    | 37        | 17.45%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz       | 7         | 3.3%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 5         | 2.36%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 5         | 2.36%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 5         | 2.36%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 4         | 1.89%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 4         | 1.89%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 4         | 1.89%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 4         | 1.89%   |
| Intel Core 2 Duo                        | 4         | 1.89%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 3         | 1.42%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 3         | 1.42%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 1.42%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 3         | 1.42%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 1.42%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 3         | 1.42%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 3         | 1.42%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 3         | 1.42%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 3         | 1.42%   |
| Intel Core i3-3217U CPU @ 1.80GHz       | 3         | 1.42%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 3         | 1.42%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 3         | 1.42%   |
| Intel CPU Version                       | 2         | 0.94%   |
| Intel Core i9-10980HK CPU @ 2.40GHz     | 2         | 0.94%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 2         | 0.94%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 2         | 0.94%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 2         | 0.94%   |
| Intel Core i7-3740QM CPU @ 2.70GHz      | 2         | 0.94%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 2         | 0.94%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 0.94%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 2         | 0.94%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 2         | 0.94%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 0.94%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 2         | 0.94%   |
| Intel Core i5-2520M CPU @ 2.50GH        | 2         | 0.94%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 2         | 0.94%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz    | 2         | 0.94%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 0.94%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 2         | 0.94%   |
| AMD Ryzen 7 5825U with Radeon Graphics  | 2         | 0.94%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 2         | 0.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 65        | 30.66%  |
| Intel Core i7           | 57        | 26.89%  |
| Intel Core i3           | 14        | 6.6%    |
| Intel Core 2 Duo        | 12        | 5.66%   |
| AMD Ryzen 7             | 11        | 5.19%   |
| AMD Ryzen 5             | 11        | 5.19%   |
| Other                   | 10        | 4.72%   |
| Intel Celeron           | 7         | 3.3%    |
| Intel Pentium           | 3         | 1.42%   |
| Intel Core i9           | 3         | 1.42%   |
| AMD A6                  | 3         | 1.42%   |
| AMD Ryzen 7 PRO         | 2         | 0.94%   |
| AMD Ryzen 3             | 2         | 0.94%   |
| AMD A4                  | 2         | 0.94%   |
| Intel Xeon              | 1         | 0.47%   |
| Intel Genuine           | 1         | 0.47%   |
| Intel Core m3           | 1         | 0.47%   |
| Intel Core 2            | 1         | 0.47%   |
| Intel Celeron Dual-Core | 1         | 0.47%   |
| AMD Ryzen 9             | 1         | 0.47%   |
| AMD Ryzen 3 PRO         | 1         | 0.47%   |
| AMD PRO A10             | 1         | 0.47%   |
| AMD Athlon              | 1         | 0.47%   |
| AMD A10                 | 1         | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 105       | 49.53%  |
| 4       | 59        | 27.83%  |
| 8       | 14        | 6.6%    |
| 16      | 10        | 4.72%   |
| 6       | 9         | 4.25%   |
| Unknown | 8         | 3.77%   |
| 12      | 7         | 3.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 208       | 98.11%  |
| 2      | 4         | 1.89%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 147       | 69.34%  |
| 1       | 57        | 26.89%  |
| Unknown | 8         | 3.77%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 39        | 18.4%   |
| IvyBridge     | 24        | 11.32%  |
| Haswell       | 21        | 9.91%   |
| Skylake       | 20        | 9.43%   |
| SandyBridge   | 15        | 7.08%   |
| Penryn        | 12        | 5.66%   |
| Broadwell     | 11        | 5.19%   |
| Unknown       | 10        | 4.72%   |
| Zen 3         | 9         | 4.25%   |
| Zen+          | 8         | 3.77%   |
| Westmere      | 6         | 2.83%   |
| Zen 2         | 5         | 2.36%   |
| TigerLake     | 5         | 2.36%   |
| Excavator     | 5         | 2.36%   |
| CometLake     | 5         | 2.36%   |
| IceLake       | 4         | 1.89%   |
| Core          | 4         | 1.89%   |
| Silvermont    | 3         | 1.42%   |
| Goldmont      | 2         | 0.94%   |
| Puma          | 1         | 0.47%   |
| K10 Llano     | 1         | 0.47%   |
| K10           | 1         | 0.47%   |
| Goldmont plus | 1         | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 161       | 62.16%  |
| Nvidia | 53        | 20.46%  |
| AMD    | 45        | 17.37%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 20        | 7.58%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 6.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 5.68%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 4.55%   |
| Intel UHD Graphics 620                                                                   | 11        | 4.17%   |
| Intel HD Graphics 5500                                                                   | 11        | 4.17%   |
| Intel HD Graphics 620                                                                    | 9         | 3.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 3.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 2.65%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 2.27%   |
| Intel HD Graphics 530                                                                    | 6         | 2.27%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.27%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 2.27%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.89%   |
| AMD Lucienne                                                                             | 5         | 1.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.52%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.52%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 4         | 1.52%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.14%   |
| Nvidia C79 [GeForce 9400M]                                                               | 3         | 1.14%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.14%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.14%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.14%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 1.14%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.14%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.76%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.76%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.76%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 2         | 0.76%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 2         | 0.76%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.76%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.76%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.76%   |
| Intel HD Graphics 630                                                                    | 2         | 0.76%   |
| Intel HD Graphics 500                                                                    | 2         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.76%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.76%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 111       | 52.11%  |
| Intel + Nvidia | 35        | 16.43%  |
| 1 x AMD        | 33        | 15.49%  |
| 1 x Nvidia     | 14        | 6.57%   |
| 2 x Intel      | 8         | 3.76%   |
| Intel + AMD    | 7         | 3.29%   |
| AMD + Nvidia   | 4         | 1.88%   |
| 2 x AMD        | 1         | 0.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 200       | 93.46%  |
| Proprietary | 14        | 6.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 185       | 85.25%  |
| 0.01-0.5   | 11        | 5.07%   |
| 1.01-2.0   | 10        | 4.61%   |
| 0.51-1.0   | 5         | 2.3%    |
| 3.01-4.0   | 3         | 1.38%   |
| 5.01-6.0   | 2         | 0.92%   |
| 7.01-8.0   | 1         | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 40        | 20.73%  |
| Chimei Innolux          | 35        | 18.13%  |
| LG Display              | 31        | 16.06%  |
| BOE                     | 23        | 11.92%  |
| Samsung Electronics     | 20        | 10.36%  |
| Lenovo                  | 6         | 3.11%   |
| Apple                   | 4         | 2.07%   |
| Sharp                   | 3         | 1.55%   |
| Philips                 | 3         | 1.55%   |
| InfoVision              | 3         | 1.55%   |
| Dell                    | 3         | 1.55%   |
| CSO                     | 3         | 1.55%   |
| BenQ                    | 3         | 1.55%   |
| PANDA                   | 2         | 1.04%   |
| Panasonic               | 2         | 1.04%   |
| Chi Mei Optoelectronics | 2         | 1.04%   |
| ___                     | 1         | 0.52%   |
| Iiyama                  | 1         | 0.52%   |
| IBM                     | 1         | 0.52%   |
| HKC                     | 1         | 0.52%   |
| Hewlett-Packard         | 1         | 0.52%   |
| HannStar                | 1         | 0.52%   |
| Goldstar                | 1         | 0.52%   |
| Fujitsu Siemens         | 1         | 0.52%   |
| BOE Technology Group    | 1         | 0.52%   |
| Unknown                 | 1         | 0.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO5B2D 1920x1080 290x160mm 13.0-inch        | 3         | 1.55%   |
| Sharp LCD Monitor SHP1481 1920x1080 290x170mm 13.2-inch               | 2         | 1.03%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 2         | 1.03%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 300x170mm 13.6-inch  | 2         | 1.03%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch  | 2         | 1.03%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 290x170mm 13.2-inch | 2         | 1.03%   |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch              | 2         | 1.03%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch           | 2         | 1.03%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch           | 2         | 1.03%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch           | 2         | 1.03%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch           | 2         | 1.03%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 2         | 1.03%   |
| LG Display LCD Monitor LGD01E9 1920x1080 350x190mm 15.7-inch          | 2         | 1.03%   |
| CSO LCD Monitor CSO1402 2880x1800 300x190mm 14.0-inch                 | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch      | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch      | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch       | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch       | 2         | 1.03%   |
| BOE LCD Monitor BOE08D5 1920x1080 340x190mm 15.3-inch                 | 2         | 1.03%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 340x190mm 15.3-inch        | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch        | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO35EC 1366x768 340x190mm 15.3-inch         | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO305C 1366x768 260x140mm 11.6-inch         | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch        | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch        | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch         | 2         | 1.03%   |
| ___ MY TV LED TV ___0101 1920x1080                                    | 1         | 0.52%   |
| Sharp LCD Monitor SHP1453 1920x1080 350x190mm 15.7-inch               | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch  | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch  | 1         | 0.52%   |
| Samsung Electronics S27C36x SAM7315 1920x1080 600x340mm 27.2-inch     | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 340x190mm 15.3-inch | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 340x190mm 15.3-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4C46 3840x2160 340x190mm 15.3-inch | 1         | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 88        | 47.06%  |
| 1366x768 (WXGA)    | 63        | 33.69%  |
| 1600x900 (HD+)     | 8         | 4.28%   |
| 1280x800 (WXGA)    | 6         | 3.21%   |
| 3840x2160 (4K)     | 5         | 2.67%   |
| 2560x1440 (QHD)    | 4         | 2.14%   |
| 2880x1800          | 3         | 1.6%    |
| 1680x1050 (WSXGA+) | 3         | 1.6%    |
| 1440x900 (WXGA+)   | 2         | 1.07%   |
| 9600x2160          | 1         | 0.53%   |
| 3840x1600          | 1         | 0.53%   |
| 2560x1600          | 1         | 0.53%   |
| 1920x1200 (WUXGA)  | 1         | 0.53%   |
| 1280x1024 (SXGA)   | 1         | 0.53%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 85        | 43.81%  |
| 13      | 51        | 26.29%  |
| 17      | 11        | 5.67%   |
| 12      | 11        | 5.67%   |
| 14      | 7         | 3.61%   |
| 11      | 7         | 3.61%   |
| 24      | 5         | 2.58%   |
| 23      | 5         | 2.58%   |
| 27      | 3         | 1.55%   |
| Unknown | 3         | 1.55%   |
| 39      | 1         | 0.52%   |
| 37      | 1         | 0.52%   |
| 31      | 1         | 0.52%   |
| 22      | 1         | 0.52%   |
| 21      | 1         | 0.52%   |
| 16      | 1         | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 120       | 62.18%  |
| 201-300     | 41        | 21.24%  |
| 501-600     | 13        | 6.74%   |
| 351-400     | 11        | 5.7%    |
| Unknown     | 3         | 1.55%   |
| 801-900     | 2         | 1.04%   |
| 401-500     | 2         | 1.04%   |
| 601-700     | 1         | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 157       | 86.74%  |
| 16/10   | 19        | 10.5%   |
| Unknown | 2         | 1.1%    |
| 5/4     | 1         | 0.55%   |
| 3/2     | 1         | 0.55%   |
| 21/9    | 1         | 0.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 68        | 35.05%  |
| 81-90          | 44        | 22.68%  |
| 101-110        | 16        | 8.25%   |
| 71-80          | 14        | 7.22%   |
| 61-70          | 11        | 5.67%   |
| 201-250        | 11        | 5.67%   |
| 121-130        | 10        | 5.15%   |
| 51-60          | 7         | 3.61%   |
| 301-350        | 3         | 1.55%   |
| Unknown        | 3         | 1.55%   |
| 111-120        | 2         | 1.03%   |
| 501-1000       | 2         | 1.03%   |
| 351-500        | 1         | 0.52%   |
| 251-300        | 1         | 0.52%   |
| 141-150        | 1         | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 91        | 47.4%   |
| 101-120       | 49        | 25.52%  |
| 51-100        | 24        | 12.5%   |
| 161-240       | 19        | 9.9%    |
| More than 240 | 6         | 3.13%   |
| Unknown       | 3         | 1.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 172       | 79.26%  |
| 0     | 28        | 12.9%   |
| 2     | 17        | 7.83%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 139       | 40.64%  |
| Realtek Semiconductor             | 87        | 25.44%  |
| Qualcomm Atheros                  | 44        | 12.87%  |
| Broadcom                          | 21        | 6.14%   |
| TP-Link                           | 8         | 2.34%   |
| Ericsson Business Mobile Networks | 5         | 1.46%   |
| Sierra Wireless                   | 4         | 1.17%   |
| Samsung Electronics               | 4         | 1.17%   |
| Edimax Technology                 | 4         | 1.17%   |
| Ralink Technology                 | 3         | 0.88%   |
| Nvidia                            | 3         | 0.88%   |
| Marvell Technology Group          | 3         | 0.88%   |
| ASUSTek Computer                  | 3         | 0.88%   |
| Hewlett-Packard                   | 2         | 0.58%   |
| Xiaomi                            | 1         | 0.29%   |
| Ralink                            | 1         | 0.29%   |
| Qualcomm Technologies             | 1         | 0.29%   |
| Qualcomm Atheros Communications   | 1         | 0.29%   |
| Qualcomm                          | 1         | 0.29%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.29%   |
| NetGear                           | 1         | 0.29%   |
| MediaTek                          | 1         | 0.29%   |
| Lenovo                            | 1         | 0.29%   |
| Huawei Technologies               | 1         | 0.29%   |
| Generic                           | 1         | 0.29%   |
| Dell                              | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 60        | 13.95%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 20        | 4.65%   |
| Intel Wireless 8265 / 8275                                             | 16        | 3.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 15        | 3.49%   |
| Intel Wireless 7265                                                    | 15        | 3.49%   |
| Intel Wi-Fi 6 AX200                                                    | 13        | 3.02%   |
| Intel Ethernet Connection (4) I219-LM                                  | 11        | 2.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 10        | 2.33%   |
| Intel Wireless 8260                                                    | 10        | 2.33%   |
| Intel Wireless 7260                                                    | 10        | 2.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 10        | 2.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 8         | 1.86%   |
| Intel Ethernet Connection I219-LM                                      | 7         | 1.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 6         | 1.4%    |
| Intel Wireless 3165                                                    | 6         | 1.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 6         | 1.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 5         | 1.16%   |
| Intel Ethernet Connection I218-LM                                      | 5         | 1.16%   |
| Intel Ethernet Connection (3) I218-LM                                  | 5         | 1.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 5         | 1.16%   |
| Intel Centrino Ultimate-N 6300                                         | 5         | 1.16%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 0.93%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 4         | 0.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 4         | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 4         | 0.93%   |
| Intel Wireless 3160                                                    | 4         | 0.93%   |
| Intel Wi-Fi 6 AX201                                                    | 4         | 0.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 4         | 0.93%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 3         | 0.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 0.7%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 3         | 0.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 3         | 0.7%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 0.7%    |
| Nvidia MCP79 Ethernet                                                  | 3         | 0.7%    |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 3         | 0.7%    |
| Intel Centrino Advanced-N 6200                                         | 3         | 0.7%    |
| Intel 82577LM Gigabit Network Connection                               | 3         | 0.7%    |
| Intel 82567LM Gigabit Network Connection                               | 3         | 0.7%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 3         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 132       | 56.41%  |
| Qualcomm Atheros                | 35        | 14.96%  |
| Realtek Semiconductor           | 27        | 11.54%  |
| Broadcom                        | 14        | 5.98%   |
| TP-Link                         | 8         | 3.42%   |
| Edimax Technology               | 4         | 1.71%   |
| Sierra Wireless                 | 3         | 1.28%   |
| Ralink Technology               | 3         | 1.28%   |
| ASUSTek Computer                | 3         | 1.28%   |
| Ralink                          | 1         | 0.43%   |
| Qualcomm Technologies           | 1         | 0.43%   |
| Qualcomm Atheros Communications | 1         | 0.43%   |
| NetGear                         | 1         | 0.43%   |
| MediaTek                        | 1         | 0.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 16        | 6.81%   |
| Intel Wireless 7265                                            | 15        | 6.38%   |
| Intel Wi-Fi 6 AX200                                            | 13        | 5.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 4.26%   |
| Intel Wireless 8260                                            | 10        | 4.26%   |
| Intel Wireless 7260                                            | 10        | 4.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 10        | 4.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 8         | 3.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 2.55%   |
| Intel Wireless 3165                                            | 6         | 2.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 2.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 2.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 2.13%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 2.13%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 4         | 1.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 1.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 1.7%    |
| Intel Wireless 3160                                            | 4         | 1.7%    |
| Intel Wi-Fi 6 AX201                                            | 4         | 1.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 1.7%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 1.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.28%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 1.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 1.28%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 1.28%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 1.28%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 1.28%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 0.85%   |
| Sierra Wireless EM7455                                         | 2         | 0.85%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2         | 0.85%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 2         | 0.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 0.85%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 2         | 0.85%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 0.85%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 0.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 0.85%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 2         | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 76        | 41.76%  |
| Intel                         | 68        | 37.36%  |
| Qualcomm Atheros              | 13        | 7.14%   |
| Broadcom                      | 11        | 6.04%   |
| Samsung Electronics           | 4         | 2.2%    |
| Nvidia                        | 3         | 1.65%   |
| Marvell Technology Group      | 3         | 1.65%   |
| Xiaomi                        | 1         | 0.55%   |
| Qualcomm                      | 1         | 0.55%   |
| OnePlus Technology (Shenzhen) | 1         | 0.55%   |
| Lenovo                        | 1         | 0.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 60        | 32.79%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 20        | 10.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 15        | 8.2%    |
| Intel Ethernet Connection (4) I219-LM                                  | 11        | 6.01%   |
| Intel Ethernet Connection I219-LM                                      | 7         | 3.83%   |
| Intel Ethernet Connection I218-LM                                      | 5         | 2.73%   |
| Intel Ethernet Connection (3) I218-LM                                  | 5         | 2.73%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 2.19%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 1.64%   |
| Nvidia MCP79 Ethernet                                                  | 3         | 1.64%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 1.64%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 1.64%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 1.64%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 1.09%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 1.09%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 1.09%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 2         | 1.09%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 1.09%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 1.09%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.55%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.55%   |
| Qualcomm FP3                                                           | 1         | 0.55%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.55%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.55%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.55%   |
| OnePlus (Shenzhen) Android Remote NDIS Device                          | 1         | 0.55%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.55%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 0.55%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 0.55%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                   | 1         | 0.55%   |
| Lenovo Lenovo Tab M10 Plus 3rd Gen RNDIS Control RNDIS Ethernet Data   | 1         | 0.55%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                    | 1         | 0.55%   |
| Intel Ethernet Connection I217-V                                       | 1         | 0.55%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 0.55%   |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 0.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 212       | 52.74%  |
| Ethernet | 178       | 44.28%  |
| Modem    | 7         | 1.74%   |
| Unknown  | 5         | 1.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 136       | 54.18%  |
| Ethernet | 112       | 44.62%  |
| Modem    | 3         | 1.2%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 170       | 80.19%  |
| 1     | 41        | 19.34%  |
| 3     | 1         | 0.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 212       | 99.53%  |
| Yes  | 1         | 0.47%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 99        | 58.58%  |
| Realtek Semiconductor           | 15        | 8.88%   |
| Qualcomm Atheros Communications | 11        | 6.51%   |
| Lite-On Technology              | 9         | 5.33%   |
| Broadcom                        | 8         | 4.73%   |
| IMC Networks                    | 7         | 4.14%   |
| Apple                           | 7         | 4.14%   |
| Dell                            | 6         | 3.55%   |
| ASUSTek Computer                | 2         | 1.18%   |
| Alps Electric                   | 2         | 1.18%   |
| USI                             | 1         | 0.59%   |
| Toshiba                         | 1         | 0.59%   |
| Foxconn / Hon Hai               | 1         | 0.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 56        | 33.14%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 12        | 7.1%    |
| Intel AX201 Bluetooth                                       | 12        | 7.1%    |
| Intel AX200 Bluetooth                                       | 12        | 7.1%    |
| Realtek Bluetooth Adapter                                   | 6         | 3.55%   |
| Apple Bluetooth Host Controller                             | 6         | 3.55%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 4         | 2.37%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 4         | 2.37%   |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 1.78%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 3         | 1.78%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 3         | 1.78%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 3         | 1.78%   |
| Lite-On Atheros AR3012 Bluetooth                            | 3         | 1.78%   |
| Realtek Bluetooth 4.2 Adapter                               | 2         | 1.18%   |
| Realtek Bluetooth 4.0 Adapter                               | 2         | 1.18%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 1.18%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 1.18%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 1.18%   |
| Intel AX210 Bluetooth                                       | 2         | 1.18%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 1.18%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 1.18%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.18%   |
| USI Qualcomm WCN685x Bluetooth Adapter                      | 1         | 0.59%   |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip             | 1         | 0.59%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.59%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 0.59%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.1                      | 1         | 0.59%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.59%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 0.59%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 1         | 0.59%   |
| Lite-On Broadcom Bluetooth 4.0 USB                          | 1         | 0.59%   |
| Lite-On Atheros Bluetooth                                   | 1         | 0.59%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.59%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 0.59%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0          | 1         | 0.59%   |
| IMC Networks Bluetooth Module                               | 1         | 0.59%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 0.59%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 0.59%   |
| Dell DW375 Bluetooth Module                                 | 1         | 0.59%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 0.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 171       | 69.8%   |
| AMD                   | 39        | 15.92%  |
| Nvidia                | 22        | 8.98%   |
| Lenovo                | 3         | 1.22%   |
| C-Media Electronics   | 2         | 0.82%   |
| RODE Microphones      | 1         | 0.41%   |
| Realtek Semiconductor | 1         | 0.41%   |
| Microsoft             | 1         | 0.41%   |
| Logitech              | 1         | 0.41%   |
| GN Netcom             | 1         | 0.41%   |
| DSEA A/S              | 1         | 0.41%   |
| Creative Technology   | 1         | 0.41%   |
| Cambridge Audio       | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 33        | 10.58%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 29        | 9.29%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 25        | 8.01%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 16        | 5.13%   |
| Intel 8 Series HD Audio Controller                                                                | 16        | 5.13%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 16        | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 4.49%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 3.85%   |
| Intel Broadwell-U Audio Controller                                                                | 12        | 3.85%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 2.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 2.56%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 2.24%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 2.24%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 2.24%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 1.92%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.6%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 1.6%    |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 1.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.28%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.28%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.28%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.96%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.96%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.96%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 0.96%   |
| AMD High Definition Audio Controller                                                              | 3         | 0.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.64%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.64%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 0.64%   |
| Lenovo Lenovo USB-C Mini Dock                                                                     | 2         | 0.64%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.64%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.64%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2         | 0.64%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.64%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 2         | 0.64%   |
| AMD FCH Azalia Controller                                                                         | 2         | 0.64%   |
| RODE Microphones RDE NT-USB Mini                                                                  | 1         | 0.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 82        | 29.93%  |
| SK hynix            | 76        | 27.74%  |
| Micron Technology   | 28        | 10.22%  |
| Kingston            | 18        | 6.57%   |
| Crucial             | 18        | 6.57%   |
| Unknown             | 11        | 4.01%   |
| Elpida              | 7         | 2.55%   |
| Unknown             | 6         | 2.19%   |
| Ramaxel Technology  | 4         | 1.46%   |
| Corsair             | 4         | 1.46%   |
| Transcend           | 3         | 1.09%   |
| A-DATA Technology   | 3         | 1.09%   |
| Unknown (ABCD)      | 2         | 0.73%   |
| GOODRAM             | 2         | 0.73%   |
| G.Skill             | 2         | 0.73%   |
| Team                | 1         | 0.36%   |
| Smart Modular       | 1         | 0.36%   |
| Smart               | 1         | 0.36%   |
| Neo Forza           | 1         | 0.36%   |
| Nanya Technology    | 1         | 0.36%   |
| GSkill              | 1         | 0.36%   |
| Apacer              | 1         | 0.36%   |
| 09490000802C        | 1         | 0.36%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 3.18%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 7         | 2.47%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 2.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 2.12%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 2.12%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 2.12%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 2.12%   |
| Unknown                                                          | 6         | 2.12%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.77%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.41%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 1.41%   |
| Samsung RAM M471A1K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 1.41%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 3         | 1.06%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.06%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.06%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 3         | 1.06%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 3         | 1.06%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.06%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 1.06%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 3         | 1.06%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 3         | 1.06%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.71%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.71%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 2         | 0.71%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.71%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.71%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2400MT/s          | 2         | 0.71%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.71%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 0.71%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 2         | 0.71%   |
| SK hynix RAM H9CCNNNBJTMLAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 2         | 0.71%   |
| Samsung RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.71%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.71%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.71%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 0.71%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.71%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 0.71%   |
| Micron RAM Module 8GB SODIMM DDR3 1600MT/s                       | 2         | 0.71%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 0.71%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 2         | 0.71%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 98        | 45.58%  |
| DDR4    | 91        | 42.33%  |
| DDR2    | 7         | 3.26%   |
| LPDDR4  | 6         | 2.79%   |
| LPDDR3  | 6         | 2.79%   |
| DDR     | 2         | 0.93%   |
| Unknown | 2         | 0.93%   |
| SDRAM   | 1         | 0.47%   |
| LPDDR5  | 1         | 0.47%   |
| DDR5    | 1         | 0.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 201       | 92.63%  |
| Row Of Chips | 13        | 5.99%   |
| DIMM         | 1         | 0.46%   |
| Chip         | 1         | 0.46%   |
| Unknown      | 1         | 0.46%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 103       | 42.21%  |
| 4096  | 88        | 36.07%  |
| 16384 | 26        | 10.66%  |
| 2048  | 21        | 8.61%   |
| 32768 | 5         | 2.05%   |
| 1024  | 1         | 0.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 68        | 29.57%  |
| 2667    | 34        | 14.78%  |
| 2400    | 29        | 12.61%  |
| 3200    | 27        | 11.74%  |
| 2133    | 13        | 5.65%   |
| 1334    | 13        | 5.65%   |
| 1333    | 13        | 5.65%   |
| 800     | 6         | 2.61%   |
| 1867    | 5         | 2.17%   |
| 667     | 5         | 2.17%   |
| 1067    | 4         | 1.74%   |
| Unknown | 4         | 1.74%   |
| 4266    | 2         | 0.87%   |
| 6400    | 1         | 0.43%   |
| 4800    | 1         | 0.43%   |
| 4267    | 1         | 0.43%   |
| 3733    | 1         | 0.43%   |
| 1639    | 1         | 0.43%   |
| 1200    | 1         | 0.43%   |
| 975     | 1         | 0.43%   |

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
| Chicony Electronics                    | 46        | 27.38%  |
| Microdia                               | 25        | 14.88%  |
| Bison Electronics                      | 17        | 10.12%  |
| Realtek Semiconductor                  | 15        | 8.93%   |
| IMC Networks                           | 14        | 8.33%   |
| Sunplus Innovation Technology          | 11        | 6.55%   |
| Suyin                                  | 6         | 3.57%   |
| Quanta                                 | 6         | 3.57%   |
| Luxvisions Innotech Limited            | 4         | 2.38%   |
| Alcor Micro                            | 4         | 2.38%   |
| Syntek                                 | 3         | 1.79%   |
| Lite-On Technology                     | 3         | 1.79%   |
| Silicon Motion                         | 2         | 1.19%   |
| Ricoh                                  | 2         | 1.19%   |
| Apple                                  | 2         | 1.19%   |
| USB Camera                             | 1         | 0.6%    |
| OmniVision Technologies                | 1         | 0.6%    |
| Logitech                               | 1         | 0.6%    |
| Lenovo                                 | 1         | 0.6%    |
| Jiangxi Shinetech Optical              | 1         | 0.6%    |
| Intel                                  | 1         | 0.6%    |
| Importek                               | 1         | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) | 1         | 0.6%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 15        | 8.93%   |
| Bison Integrated Camera                              | 10        | 5.95%   |
| Microdia Integrated_Webcam_HD                        | 9         | 5.36%   |
| Microdia Integrated Webcam                           | 8         | 4.76%   |
| Sunplus Integrated_Webcam_HD                         | 7         | 4.17%   |
| IMC Networks Integrated Camera                       | 5         | 2.98%   |
| Realtek USB 2.0 PC Camera                            | 3         | 1.79%   |
| Realtek Integrated_Webcam_HD                         | 3         | 1.79%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 3         | 1.79%   |
| Chicony USB2.0 HD UVC WebCam                         | 3         | 1.79%   |
| Chicony HD WebCam                                    | 3         | 1.79%   |
| Suyin Integrated_Webcam_HD                           | 2         | 1.19%   |
| Suyin Acer/HP Integrated Webcam [CN0314]             | 2         | 1.19%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 2         | 1.19%   |
| Realtek Lenovo EasyCamera                            | 2         | 1.19%   |
| Realtek Integrated Webcam HD                         | 2         | 1.19%   |
| Realtek Front Camera                                 | 2         | 1.19%   |
| Quanta VGA WebCam                                    | 2         | 1.19%   |
| Quanta HP TrueVision HD Camera                       | 2         | 1.19%   |
| Microdia Integrated Webcam HD                        | 2         | 1.19%   |
| Luxvisions Innotech Limited Integrated Camera        | 2         | 1.19%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 1.19%   |
| IMC Networks USB 2.0 UVC HD Webcam                   | 2         | 1.19%   |
| IMC Networks Realtek PC Camera                       | 2         | 1.19%   |
| IMC Networks Realtek DMFT RGB                        | 2         | 1.19%   |
| Chicony USB2.0 VGA UVC WebCam                        | 2         | 1.19%   |
| Chicony Realtek DMFT RGB                             | 2         | 1.19%   |
| Chicony Lenovo Integrated Camera (0.3MP)             | 2         | 1.19%   |
| Chicony Integrated HP HD Webcam                      | 2         | 1.19%   |
| Chicony Integrated Camera (1280x720@30)              | 2         | 1.19%   |
| Chicony HP HD Camera                                 | 2         | 1.19%   |
| Bison ThinkPad P50 Integrated Camera                 | 2         | 1.19%   |
| Bison ThinkPad Integrated Camera                     | 2         | 1.19%   |
| Apple FaceTime HD Camera                             | 2         | 1.19%   |
| Alcor Micro USB 2.0 Camera                           | 2         | 1.19%   |
| USB Camera USB Camera                                | 1         | 0.6%    |
| Syntek USB 2.0 UVC 1.3M WebCam                       | 1         | 0.6%    |
| Syntek Lenovo EasyCamera                             | 1         | 0.6%    |
| Syntek Integrated Camera                             | 1         | 0.6%    |
| Suyin RGBIR Camera                                   | 1         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 15        | 39.47%  |
| Synaptics                  | 6         | 15.79%  |
| Upek                       | 3         | 7.89%   |
| Shenzhen Goodix Technology | 3         | 7.89%   |
| STMicroelectronics         | 2         | 5.26%   |
| FocalTech Systems          | 2         | 5.26%   |
| Elan Microelectronics      | 2         | 5.26%   |
| Next Biometrics            | 1         | 2.63%   |
| LighTuning Technology      | 1         | 2.63%   |
| Fingerprint Cards          | 1         | 2.63%   |
| Broadcom                   | 1         | 2.63%   |
| AuthenTec                  | 1         | 2.63%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 6         | 15.79%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 3         | 7.89%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                            | 2         | 5.26%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 2         | 5.26%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 5.26%   |
| Validity Sensors Synaptics WBDI                                              | 2         | 5.26%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 5.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 2         | 5.26%   |
| STMicroelectronics Fingerprint Reader                                        | 2         | 5.26%   |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 5.26%   |
| FocalTech Systems Fingerprint Reader                                         | 2         | 5.26%   |
| Elan Fingerprint Sensor                                                      | 2         | 5.26%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 1         | 2.63%   |
| Upek TCS5B Fingerprint sensor                                                | 1         | 2.63%   |
| Synaptics WBDI                                                               | 1         | 2.63%   |
| Shenzhen Goodix  Fingerprint Device                                          | 1         | 2.63%   |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 2.63%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 1         | 2.63%   |
| Fingerprint Cards FPC Fingerprint Reader                                     | 1         | 2.63%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.63%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 2.63%   |

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
| 2     | 79        | 35.43%  |
| 1     | 53        | 23.77%  |
| 3     | 43        | 19.28%  |
| 4     | 24        | 10.76%  |
| 0     | 17        | 7.62%   |
| 5     | 7         | 3.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 156       | 36.28%  |
| Bluetooth                | 110       | 25.58%  |
| Net/wireless             | 54        | 12.56%  |
| Card reader              | 43        | 10%     |
| Fingerprint reader       | 38        | 8.84%   |
| Firewire controller      | 14        | 3.26%   |
| Network                  | 8         | 1.86%   |
| Storage                  | 5         | 1.16%   |
| Sound                    | 1         | 0.23%   |
| Net/ethernet             | 1         | 0.23%   |

